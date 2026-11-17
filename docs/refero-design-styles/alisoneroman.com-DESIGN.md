# Alison Roman — butter paper, big opinions

## Overview

A warm, opinionated editorial style that feels closer to a personal journal and a well-loved printed menu than a polished corporate campaign. Cream paper, brown-black ink, olive and deep red grounds support delicate old-style serif headlines and practical sans-serif navigation. Candid, richly colored photography carries the storytelling; dense image indexes alternate with expansive typographic and illustrated interludes. It suits personality-led products, physical goods and services with a tangible everyday use.

### Essentials

- A modest headline inside an enormous lived-in scene: the default opening uses a 1416px-wide image stage beneath a 63px navigation strip, with a two-line 80px/1 light serif title centered within a left-of-center text pocket.
- Menu typography becomes architecture: use 120px/1 serif text at weight 300 and -0.03em tracking on an olive field, interrupted by 20px uppercase serif labels with 4.8px tracking. Include this oversized text-only wayfinding device even when the product has no visual catalog.
- Paper colors are the baseline, not an accent wash: cream #fffaec and white #ffffff carry content, brown #290a08 carries text, while olive #827a04 and maroon #810c00 occupy entire distinct interludes rather than every card. The olive interlude occupies about one fifth of the long landing composition.
- Actions look typeset and cut square: 56px-high rectangular buttons use 18px medium sans text, 32px side padding and a fine right arrow; the opening inverts the usual brown button to white.
- Images feel handled, not composited: tall 330×471px editorial photographs sit in four columns with 24px gaps; isolated merchandise uses pale stone backing instead of glossy floating mockups. For intangible products, photograph real use, tools or work surfaces.
- The invitation is a decorated paper object: a centered maroon panel up to 1200px wide combines uneven vertical stripes, faint hand-drawn outlines, 24px square corner notches, a two-line 120px serif invitation and a single cream email bar. Retain this illustrated invitation and the brown, spacious closing footer on new pages.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brown ink | `#290a08` | `--color-ink` | text, background, action | Primary lettering, ordinary buttons and the full-width closing footer. |
| Invitation red | `#810c00` | `--color-maroon` | background, accent | Decorated invitation panel; a concentrated conversion color rather than the general canvas. |
| Menu olive | `#827a04` | `--color-olive` | background, accent | Full-bleed oversized wayfinding interlude. |
| Butter | `#fff3cc` | `--color-butter` | background, surface, text | Warm excerpt band, photograph backing and pale footer links. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm gray brown | `#826e65` | `--color-muted` | text, action | Support copy, dates, secondary category labels and button hover fill. |
| Excerpt charcoal | `#15171a` | `--color-quote-ink` | text | Long oversized sans-serif quotations. |
| Paper edge | `#d5ccc0` | `--color-rule` | border, accent | Hairline section and pagination dividers and inactive carousel dots. |
| Object backing | `#f3ebdf` | `--color-stone` | surface, action | Isolated object photography backings and secondary action rectangles. |
| Cream paper | `#fffaec` | `--color-canvas` | background, text, surface | Default page canvas, reversed display lettering and the invitation's email bar and corner cutouts. |
| White paper | `#ffffff` | `--color-white` | surface, text, action | Feature spreads, portrait panels, image controls and the opening's inverted button; reversed text over photography. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial archives | Editorial brown | `#4d3938` | `--color-editorial-ink` | text | Serif summaries beneath dated editorial cards. |

## Typography

- **Jannon Neo** — Headlines, display navigation, wordmark, item titles and long editorial product descriptions. Fine, literary old-style serif with lively angled strokes and a gentle italic; light display cuts have substantial presence without boldness. If unavailable, use **EB Garamond**. Use 400 for the light display approximation; tune widths before changing the tight display tracking. Font stack: "Jannon Neo", "EB Garamond", Georgia, serif.
- **Modale Antique** — Navigation, short practical descriptions, dates, buttons and the occasional oversized quotation. Unshowy, open sans-serif with an everyday printed-label quality; regular text contrasts with the fine serif. If unavailable, use **DM Sans**. Use 400–500 for text and actions, 300 for the excerpt. Font stack: "Modale Antique", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Jannon Neo | 300 | 120px | 1 | -0.03em | Oversized wayfinding and decorated invitation headings; usually centered. |
| headline | Jannon Neo | 300 | 80px | 1 | -0.03em | Opening title, plain index titles and conversational editorial introductions. |
| headline-italic | Jannon Neo | 300 italic | 80px | 1 | -0.03em | A conversational inserted date or connective word within a headline. |
| section-heading | Jannon Neo | 300 | 48px | 1 | -0.03em | Collection headings, feature spread titles and product titles. |
| excerpt | Modale Antique | 300 | 48px | 1 | -0.03em | Long, emphatic quote on the butter-colored illustrated band. |
| item-title | Jannon Neo | 400 | 32px | 1.1 | -0.02em | Card titles, small feature titles and attribution links. |
| eyebrow | Jannon Neo | 400 | 20px | 1.4 | 0.24em, uppercase | Spaced section labels on the oversized menu and paired channel panels. |
| wordmark | Jannon Neo | 400 | 20px | 1.4 | 0.07em, uppercase | Centered typographic brand name in the navigation. |
| body | Modale Antique | 400 | 18px | 1.2 | -0.01em | Navigation, short descriptions and support text. |
| button | Modale Antique | 500 | 18px | 1.5 | normal | Ordinary 56px-high marketing actions. |
| compact-button | Modale Antique | 500 | 18px | 1 | normal | Header conversion and compact product ordering actions. |
| date | Modale Antique | 400 | 14px | 1.3 | normal | Small centered dates above editorial item titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| profile and detailed catalog pages | editorial-body | Jannon Neo | 400 | 20px | 1.3 | normal | Biographies, product descriptions, contact lists and comparison guidance. |
| editorial archives | archive-summary | Jannon Neo | 400 | 20px | 1.3 | -0.009em | Centered short summaries beneath dated titles. |

**Notes:**

- The 48px, 80px and 120px light serif roles share -0.03em tracking and a line height of 1. Item titles are heavier and loosen to 1.1 line height with -0.02em tracking.
- Most short explanatory copy remains sans-serif. The detailed catalog and profile variants switch paragraphs to 20px serif; catalog paragraphs can be justified and softened to 0.7 opacity.
- Sentence case is the norm. Wide uppercase tracking belongs to the small serif eyebrow, not headlines or body text.

## Layout

**Density:** Airy editorial chapters surrounding compact image indexes; large resting spaces coexist with close title-and-summary pairs.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Title to summary and date to title. |
| 12px | Compact text-group gaps and inner top padding of card descriptions. |
| 16px | Invitation title to support line and image-to-content offset before internal padding. |
| 24px | Default grid gap, page side gutter, footer padding and corner-notch size. |
| 28px | Navigation group gap. |
| 32px | Opening title-to-button gap, section top inset after a rule and invitation support-to-form gap. |
| 36px | Vertical margin around oversized wayfinding entries. |
| 48px | Collection heading-to-image interval and feature-panel inner padding. |
| 80px | Space between large profile directory groups and below list actions. |
| 120px | Top padding of plain title openings and conversational lead sections. |
| 160px | Outer vertical breathing room around the invitation and the closing media feature. |

### Containers and grids

- **Wide editorial frame**: max width 2500px · side padding 24px. Near-edge-to-edge indexes and navigation; the desktop content width is 1392px at a 1440px window.
- **Inset chapter**: max width 1200px · side padding 0px. Centered invitation, large menu lettering and detailed catalog chapters.
- **Four-column index**: 4 columns · gap 24px. Equal 330px cards at desktop, with aligned tall imagery and independently wrapping titles.
- **Reading measure**: max width 700px · side padding 16px. Long serif explanations and comparison guidance; invitation headlines use a narrower 650px measure.
- **Email measure**: max width 720px · side padding 0px. Single-line invitation form centered beneath the heading and support.
- **Split feature**: 2 columns · gap 24px. Portrait photograph to the left and centered headline with short support to the right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Buttons and editorial media | 0px |
|  | Carousel indicators | 50% |
| merchandise recommendations | Recommendation card wrapper | 5px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #fffaec; color: #290a08`

#### White spread · level 0

**Use:** Feature stories, portrait introductions and closing media feature.

**CSS:** `background: #ffffff; border-radius: 0px; box-shadow: none`

**Observed:** A flat editorial field rather than a raised card; in the carousel, offset white edges suggest stacked paper.

**Transfer:** Contrast white feature spreads with the surrounding cream without adding elevation.

#### Olive menu field · level 0

**Use:** Monumental text-only wayfinding.

**CSS:** `background: #827a04; color: #fffaec; padding: 32px 0px 64px`

**Observed:** A full-width field with centered linked entries and a faint divider between topic groups.

**Transfer:** Give a few relevant destinations enough vertical room to read as display typography.

#### Decorated invitation · level 0

**Use:** High-emphasis conversion panel.

**CSS:** `background: #810c00; color: #fffaec; position: relative; overflow: hidden; max-width: 1200px; padding: 160px 80px; border-radius: 0px`

**Observed:** The red ground sits behind striped line art and four cream square corner cutouts; surrounding cream space is substantial.

**Transfer:** Use the illustrated-paper construction for the key invitation, independent of its location in the page.

#### Butter excerpt · level 0

**Use:** A long editorial statement with line art below.

**CSS:** `background: #fff3cc; color: #15171a; position: relative; padding: 32px 77px 480px 32px; overflow-x: hidden`

**Observed:** Text fills nearly the whole width above a 500px-tall loose outline illustration anchored at the bottom.

**Transfer:** Make an editorial opinion or useful explanation into a broad, readable statement rather than a small testimonial tile.

#### Object ground · level 0

**Use:** Backing for isolated recommendation photographs.

**CSS:** `background: #f3ebdf; box-shadow: none`

#### Brown closing field · level 0

**Use:** Site-wide closing footer.

**CSS:** `background: #290a08; color: #fff3cc; padding: 24px; min-height: 400px`

**Observed:** The upper portion carries the content and the lower portion remains spacious.

**Transfer:** End with a small personal emblem and useful links, not a second enormous sales headline.

#### Catalog image mat · level 0

**Only for:** detailed catalog pages

**Use:** Frame flat product covers without distortion.

**CSS:** `background: rgba(211, 198, 182, 0.2); padding: 80px 48px`

**Observed:** A translucent stone tint over cream produces a pale warm mat; product artwork stays contained within it.

**Transfer:** Center intact packaging or cover art within the mat.

## Components

### Centered masthead

**Use:** Persistent navigation across page types.

**CSS:** `position: fixed; top: 0px; z-index: 50; width: 100%; height: 63px; background: #fffaec; color: #290a08`

**Text style:** `body` — Modale Antique 400 · 18px/1.2 · tracking -0.01em

**Observed:** A centered serif wordmark sits between left-aligned navigation and right-aligned utilities. The inner grid is 1fr auto 1fr with 12px vertical and 24px side padding; a tiny dot marks the current destination.

**Transfer:** Use a compact typographic name with a short set of primary links, leaving the conversion at the far right.

### Primary button

**Use:** Actions on ordinary light sections.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; height: 56px; padding: 8px 32px; background: #290a08; color: #ffffff; border-radius: 0px`

**Text style:** `button` — Modale Antique 500 · 18px/1.5

**Observed:** A fine right arrow follows the short label. Repeated index sections center the action below the cards; width follows the label.

**States:** Declared: hover opacity 1 and background-color rgb(130 110 101/1); focus-visible outline #290a08 solid 6px with 2px offset.

### Inverse button

**Use:** Opening conversion over full-bleed photography.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; height: 56px; padding: 8px 32px; background: #ffffff; color: #290a08; border-radius: 0px`

**Text style:** `button` — Modale Antique 500 · 18px/1.5

**Observed:** The only foreground action in the opening; label then a thin right arrow.

**States:** Declared: hover opacity 1 and background-color rgb(130 110 101/1); focus-visible outline #290a08 solid 6px with 2px offset.

### Compact conversion

**Use:** Conversion at the right edge of the masthead.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 39px; padding: 8px 16px; background: #290a08; color: #ffffff; border-radius: 0px`

**Text style:** `compact-button` — Modale Antique 500 · 18px/1

**Observed:** Header version is compact and label-led. The detailed catalog version is 48px high with 32px side padding and a right arrow.

**States:** Declared: hover opacity 1 and background-color rgb(130 110 101/1); focus-visible outline #290a08 solid 6px with 2px offset.

### Editorial index card

**Use:** Repeated image-led content previews.

**CSS:** `position: relative; display: flex; flex-direction: column; border-radius: 0px; box-shadow: none`

**Text style:** `item-title` — Jannon Neo 400 · 32px/1.1 · tracking -0.02em

**Observed:** Tall 330×471px photographs lead. Text starts 28px below the image and summary follows title by 8px. Practical cards are left aligned with sans summaries; dated editorial cards center a small date above the title. Archive summaries use the archive-summary recipe.

**Transfer:** Use a real scene and a specific descriptive title; retain the open page ground behind the text.

### Save control

**Use:** Bookmark action attached to index imagery.

**CSS:** `position: absolute; right: 12px; bottom: 12px; width: 32px; height: 32px; display: flex; align-items: center; justify-content: center; background: #ffffff; border-radius: 0px`

**Observed:** A 24px outline bookmark sits within the square. This control is attached to the image rather than to the card's text block.

**States:** Declared: hover SVG fill changes to brown; focus-visible outline #290a08 solid 2px.

**Transfer:** Use only where the content is actually saveable, with an explicit accessible label.

### Invitation email bar

**Use:** Email conversion inside the decorated panel.

**CSS:** `max-width: 720px; height: 56px; background: #fffaec; color: #290a08; display: flex; align-items: center; justify-content: space-between; border-radius: 0px`

**Text style:** `body` — Modale Antique 400 · 18px/1.2 · tracking -0.01em

**Observed:** Input and submit action share one uninterrupted light rectangle; placeholder on the left, Subscribe with a right arrow on the right. There is no detached pill button.

**Transfer:** Keep the form to one field and one plain action; adapt the field label to the invitation.

### Footer directory

**Use:** Shared closing navigation.

**CSS:** `background: #290a08; color: #fff3cc; min-height: 400px; padding: 24px`

**Text style:** `body` — Modale Antique 400 · 18px/1.2 · tracking -0.01em

**Observed:** A 110×80px script emblem occupies the far left. Three link columns occupy the right half, each 216px wide with 24px gaps; social and legal links belong to the last column. Most content sits at the top, leaving a deep brown resting area below.

**Transfer:** Use an original simple monogram or hand-drawn emblem at left; separate editorial, company and social/legal destinations.

### Editorial inline link

**Only for:** profile and detailed catalog pages

**Use:** Useful cross-references embedded in serif paragraphs.

**CSS:** `color: #290a08; text-decoration: underline`

**Text style:** `editorial-body` — Jannon Neo 400 · 20px/1.3

**Observed:** Links remain in the paragraph's serif typography rather than becoming badges or buttons.

**States:** Declared: hover opacity 0.8; focus-visible outline #290a08 solid 2px.

### Catalog product row

**Only for:** detailed catalog pages

**Use:** Describe one physical release in depth.

**CSS:** `display: flex; align-items: center; max-width: 1152px; box-shadow: none; border-radius: 0px`

**Text style:** `section-heading` — Jannon Neo 300 · 48px/1 · tracking -0.03em

**Observed:** A 461px-wide Catalog image mat sits left of descriptive text with 48px side insets. The intact cover is about 365px wide. Text has a serif title, 20px serif paragraphs, then a brown order button and a stone secondary rectangle.

**Transfer:** Repeat the same image/text orientation for each product rather than alternating rows for decoration.

## Imagery and graphics

### Lived-in moving scene

**Use:** The opening's dominant object and occasional immersive interlude.

**Observed:** Close footage of hands, food and real materials fills nearly the entire first viewport. Warm amber and red tones, shallow focus, motion softness and bright natural highlights feel candid rather than studio-perfect. Text is laid directly over the scene without a visible heavy gradient.

**Transfer:** Film a real interaction with the product at close range, leaving a calm darker pocket for text. Without video, use one atmospheric photograph with hands, tools or a work surface instead of a fabricated dashboard.

### Tall editorial photographs

**Use:** Content grids and split feature spreads.

**Observed:** Tightly framed food, domestic scenes, people and travel images retain rich natural color. Patterned cloth, ceramics, wood and incidental hands supply texture. Grid images are tall, approximately 0.7 width-to-height, with square edges; split features also use tall portraits.

**Transfer:** Photograph concrete outcomes and everyday contexts. Mix close details and people while preserving consistent portrait framing and believable light.

### Isolated objects

**Use:** Merchandise recommendations and detailed product catalogs.

**Observed:** Tools and containers appear isolated at generous scale on pale stone, with little theatrical shadow. Catalog covers retain their original proportions and typography within a warm translucent mat.

**Transfer:** Use clean cutouts of the new product with ample breathing room and a consistent warm backing; keep cover or packaging artwork intact.

### Striped invitation artwork

**Use:** Signature decorated conversion panel.

**Observed:** Uneven broad red and terracotta vertical stripes support faint, wavering outlines of vessels and organic shapes. Line art sits mainly around the edges so the central title remains legible; cream square corner notches make the field look physically cut.

**Transfer:** Draw a few original objects or abstract contours connected to the new product. Minimum version: uneven stripes, several thin irregular outlines at the perimeter, a clear central area and all four square notches.

**Build:** Start with a maroon rectangle. Overlay an SVG with gently wavering vertical bands roughly 80–160px wide, using cream at 0.12–0.2 opacity. Add irregular open contour paths in cream at about 0.25 opacity with 1–2px strokes, mostly at the left, right and lower edges. Enlarge and clip several paths beyond the frame. Place 24×24px cream squares at all four corners above the art. Keep text and form above this layer.

### Oversized outline drawing

**Use:** Bottom of the butter editorial statement band.

**Observed:** Loose pale brown botanical contours spread horizontally across the lower 500px. The drawing is oversized and partly cut off, with no solid fills or photographic shading.

**Transfer:** Use an original contour drawing of a few product-adjacent forms; it should read as a casual margin sketch enlarged to architectural scale.

**Build:** Draw 5–8 uneven closed organic contours in SVG, with occasional thin interior lines, no fill, and brown strokes at about 0.2 opacity. Spread the paths across a 1440×500 viewBox, allow several to continue beyond the bottom and side edges, and anchor the SVG to the band's bottom.

### Icons

**Observed:** Utility marks are mostly 24px brown SVGs, with 1px butt-ended outlines for bookmarks and fine right arrows for actions. White 32px square backings keep image controls legible. Active carousel dots are brown, inactive dots paper-edge gray, all 8px circles.

**Transfer:** Choose simple fine-stroke utility symbols and long thin arrows, not chunky rounded icon tiles. Keep icon color tied to the surrounding text.

## Section recipes

How recurring sections are built.

### First screen: Immersive editorial opening

**Observed:** A 63px cream Centered masthead caps a 837px-high photographic stage with 12px side margins. Back to front: brown fallback ground, full-stage warm moving scene, then white type and the Inverse button. The title is 80px/1 light serif, broken into two short centered lines inside a roughly one-third-width pocket left of the scene's center; the main visual still dominates the right side. A 32px gap separates title and action. Within the first 900px the complete masthead, scene, title and action are visible; the conversational next section begins below the fold. There is no supporting paragraph in the default opening.

**Transfer:** Use a short announcement or product introduction over a tactile use scene. Without source-quality footage, a warm close-up still is sufficient if its composition leaves room for the title. Archive and catalog variants instead open with a centered 80px cream-ground title and 120px top padding; profile variants open as a White spread with a tall image and centered title/support beside it.

**Avoid:** Do not replace the scene with a centered floating mockup and a huge multiline slogan, or add badges, metrics and several competing actions to the opening.

**Text style:** `headline` — Jannon Neo 300 · 80px/1 · tracking -0.03em

### Conversational heading and paper spread

**Observed:** A centered 80px serif sentence introduces a timely recommendation, with an italic date inside it. Beneath it, a White spread pairs a 427×610px portrait image with a centered 48px serif title and short muted 18px sans copy. Offset white edges evoke stacked paper; 8px carousel dots sit beneath the text.

**Transfer:** Present one featured use case or recommendation with a human sentence rather than a generic feature heading. Keep one settled item readable at a time.

**Text style:** `section-heading` — Jannon Neo 300 · 48px/1 · tracking -0.03em

### Ruled magazine index

**Observed:** A 1px paper-edge rule, 32px top inset and a 48px serif heading start the section. The Four-column index follows with a 48px heading-to-image interval. Editorial index cards sit on cream without individual outlines; a centered Primary button closes shorter selections. Full archives add a restrained filter row and a 75px pagination strip bounded by hairlines.

**Transfer:** Use for examples, stories or resources; decide whether the page needs a short selection with one more-link or a full filterable archive.

**Text style:** `item-title` — Jannon Neo 400 · 32px/1.1 · tracking -0.02em

### Monumental menu

**Observed:** The Olive menu field turns destination names into centered 120px serif lines, within a 1200px measure. Entries carry 36px vertical margins, and widely tracked 20px serif labels separate groups. A faint horizontal divider marks a change of group.

**Transfer:** Use the device for product capabilities, collections or alternate paths. Preserve its extraordinary scale even with fewer destinations; let content determine how many entries are useful.

**Text style:** `display` — Jannon Neo 300 · 120px/1 · tracking -0.03em

### Illustrated invitation

**Observed:** The Decorated invitation sits within 160px of cream breathing room above and below. Its 120px centered two-line title uses a 650px measure, followed by a short 18px support line and the Invitation email bar. Signature striped line art and square notches frame the message. Detailed catalog layouts narrow the panel to 1040px while keeping the same treatment.

**Transfer:** Use a concrete invitation to join, receive updates or request access. Keep the hand-rendered paper device even when the conversion changes from email to another one-field action.

**Text style:** `display` — Jannon Neo 300 · 120px/1 · tracking -0.03em

### Opinion as a broadside

**Observed:** Butter excerpt places a 48px light sans statement across almost the full width, inset 32px at top and left. Attribution and contextual links use 32px serif. An oversized outline drawing occupies the lower half rather than becoming an icon beside the text.

**Transfer:** Use a useful opinion, plain-language explanation or firsthand observation. It should read as editorial content, not anonymous social proof.

**Text style:** `excerpt` — Modale Antique 300 · 48px/1 · tracking -0.03em

### Closing media feature and directory

**Observed:** A White spread with 160px vertical padding places a short 32px serif heading and muted sans text to the left, a 708×405px video in the middle, and a stone action on the right. Footer directory then closes the page. Other page types end directly after the illustrated invitation, contact block or paired editorial destinations.

**Transfer:** Offer one final way to experience the product, then end in the quiet brown directory. The footer remains consistent even when the preceding closing block varies.

**Text style:** `item-title` — Jannon Neo 400 · 32px/1.1 · tracking -0.02em

### Detailed catalog chapter

**Only for:** detailed catalog pages

**Observed:** Catalog product row repeats a warm matted cover on the left and 48px title, justified 20px serif body and compact actions on the right. After the products, a 700px reading measure holds a 32px question heading and a 20px answer before the invitation.

**Transfer:** Use for a small number of richly described products and a human comparison answer; keep all product rows oriented consistently.

**Text style:** `editorial-body` — Jannon Neo 400 · 20px/1.3

### Profile directory and contact close

**Only for:** profile pages

**Observed:** A White spread opens with a 600×741px portrait and 80px title. After serif biography copy, an open two-column directory uses muted 80px category labels at left and brown 80px destination names at right, with 80px between groups. A centered 48px contact heading and 20px labeled address lines sit between the illustrated invitation and Footer directory.

**Transfer:** Present people, media or capabilities with typographic links rather than logo cards; finish with plainly labeled contact routes.

**Text style:** `headline` — Jannon Neo 300 · 80px/1 · tracking -0.03em

### Paired editorial destinations

**Only for:** editorial archives

**Observed:** Two equal white square panels, each 684px at desktop, sit 24px apart. Widely spaced serif uppercase headings, centered descriptive copy and a bottom Explore arrow organize each panel.

**Transfer:** Offer two related formats or experiences with concise explanations. Include meaningful media or artwork when available, rather than treating empty space as content.

**Text style:** `eyebrow` — Jannon Neo 400 · 20px/1.4 · tracking 0.24em · uppercase

## Page flow

**Storyline:** Immersive introduction → timely recommendation or editorial context → browsable detail → expressive wayfinding and invitation → useful final destination → compact directory.

### A personality-led marketing landing page with multiple paths into a larger body of work

1. **Introduction** — Near-full-screen moving image with a short serif announcement and a single light action.
2. **Immediate usefulness** — Conversational timely heading, paper-like feature carousel and four-image selection.
3. **Wayfinding** — An extended olive typographic menu makes the range of content explicit.
4. **Relationship building** — A second immersive scene and decorated invitation make the editorial relationship tangible.
5. **Discovery** — Merchandise and dated editorial selections return to the four-column rhythm.
6. **Editorial depth** — A butter-colored excerpt with line art, then a white media feature.
7. **Closing navigation** — Brown directory with a small script emblem and three link columns.

**Transfer:** Use the contrasts of scene, index, monumental type and illustrated invitation to sustain a long page; adapt the selection and order to the new product.

### A practical searchable content library

1. **Orientation** — Centered serif title with three understated browse modes below it.
2. **Selection** — Slim collection/free/saved filter row and four-column portrait cards.
3. **Continuation** — Centered page count and thin arrow controls between rules.
4. **Conversion and close** — Decorated invitation followed directly by the brown directory.

**Transfer:** Use for catalogs of actionable content, with filters subordinate to the photography.

### An editorial archive that makes current publishing feel personal

1. **Orientation** — Centered cream-ground serif title.
2. **Featured story** — White split spread with a large portrait image, date, 80px title and brief deck.
3. **Relationship building** — Decorated invitation before the complete archive.
4. **Browse** — Ruled heading and filters, then four-column dated stories and pagination.
5. **Related destinations** — Two white editorial channel panels with Explore arrows.
6. **Closing navigation** — Shared brown directory.

**Transfer:** Use for journals or announcements; let specific, conversational story titles carry the personality.

### A personal or company profile with routes into its work

1. **Human introduction** — White portrait-and-title spread with a brief biography and a longer serif paragraph.
2. **Range of work** — Oversized two-column category and destination directory.
3. **Relationship building** — Decorated invitation.
4. **Contact** — Centered heading and concise labeled contact links.
5. **Closing navigation** — Shared brown directory.

**Transfer:** Use a believable portrait or working scene, categorize the work typographically and end with specific contact routes.

### A focused catalog of substantial physical products

1. **Orientation** — Centered two-line serif title with a small italic connective word at the same scale.
2. **Product consideration** — Repeated matted covers beside descriptive serif copy and order/secondary actions.
3. **Objection handling** — A narrow question-and-answer passage helps readers choose.
4. **Conversion and close** — Narrower decorated invitation followed by the shared brown directory.

**Transfer:** Use consistent descriptive rows rather than a dense commerce grid when a few products need thoughtful explanation.

## Writing

Warm, firsthand and slightly irreverent. Confidence comes from specific observations and practical usefulness rather than inflated promises; the writer is comfortable with asides, opinions and a little self-awareness.

**Do not copy:** Do not reuse the source's brand or product names, personal identity, monogram, artwork, quotations, contact details, claims, publication dates or recipe titles as new product content. Examples below demonstrate voice only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Talk directly to you; use I or me when a real named narrator stands behind the advice. Refer to the product plainly, without an abstract corporate we.
- **Rhythm:** Short straightforward titles alternate with surprisingly conversational full-sentence headlines. Supporting text ranges from a clipped lower-case fragment to a few flowing sentences with parentheses, contractions and an occasional exclamation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening title | A simple announcement, not a universal promise. | 2–5 words | “Introducing: Roman's” |
| Section invitation | A familiar phrase that tells the reader what is here. | 2–5 words | “What to buy”<br>“More to explore” |
| Editorial headline | A particular opinion or a personal update in ordinary speech. | 5–12 words | “Summer Ends When I Say It Does”<br>“At long last, some very exciting news” |
| Support line | A specific benefit or a casual fragment that adds a human angle. | 5–16 words for a short deck | “for the morning, for snacking, forever”<br>“recipes, opinions, recommendations, and so much more.” |
| Action | Plain verb with no inflated value language; arrow supplies the motion. | 1–4 words | “Order here”<br>“See more” |
| Objection handling | Ask the reader's real question and answer it in the narrator's voice. | One short question followed by a useful paragraph | “What if I’m choosing between them?” |

**Words and phrasing to use:** here; you; favorite; a little; if you want; for everyone; practical details; candid parenthetical asides

**Avoid:** revolutionary; unlock your potential; seamless ecosystem; world-class solutions; future-proof; corporate mission abstractions

**Rules:**

- Name the thing and the situation it helps with before praising it.
- Let an aside add specificity or humor; do not turn every sentence into a joke.
- Use direct actions such as Order, Explore or Subscribe instead of poetic button labels.
- A long paragraph can sound personal and useful; a short card deck can be an incomplete sentence.
- Make contact and comparison information explicit rather than hiding it behind promotional language.

## Do's and Don'ts

### Do

- Keep the serif display cuts light: weight 300 at 80px or 120px, line height 1.
- Use 24px page gutters and 24px four-column gaps for a dense editorial index.
- Keep short explanatory text at 18px/1.2 in the sans-serif.
- Preserve square corners on media, buttons and the illustrated invitation.
- Place the email input and submit action in one 720px-wide, 56px-high cream bar.
- Use 1px paper-edge dividers instead of boxes around every content card.
- Let the 120px olive menu lettering and striped invitation act as visual landmarks.
- Close with the 400px brown field, small emblem and three restrained link columns.

### Don't

- Do not substitute bold geometric sans headlines for the light literary serif.
- Do not turn the 56px rectangular actions into rounded pills.
- Do not spread maroon or olive across every section; keep cream and white as the reading grounds.
- Do not add drop shadows or glass effects to flat paper spreads.
- Do not use landscape thumbnails throughout an index built around 330×471px portrait imagery.
- Do not center-align practical card descriptions just because dated editorial cards are centered.
- Do not enlarge the 14px date into a promotional eyebrow; it is small secondary metadata.
- Do not decorate each utility with a thick-stroke colored icon tile; keep the 24px fine brown marks.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare 0.2s transitions and change to warm gray brown on hover.
- The masthead declares transform 0.3s ease-in-out.
- The carousel declares fadeIn and fadeOut animations lasting 0.3s with ease-in-out easing; card text uses an opacity transition of 0.2s.
- Save controls declare 0.15s transitions with cubic-bezier(0.4, 0, 0.2, 1).

**Transfer:**

- Use a subtle fade between paper-spread carousel stories rather than translating the entire chapter.
- Keep interaction feedback tied to muted color and opacity changes; the immersive scene supplies most of the visible activity.

**Unknown:**

- Autoplay intervals, media playback policy and exact scroll-trigger behavior are not specified.

### Responsive

**Observed:**

- The layout includes narrow-screen column variants for split spreads and paired editorial panels.
- The excerpt illustration has a 276px narrow-screen height versus 500px at desktop, and the narrow excerpt reserves 256px below its text.

**Transfer:**

- On narrow screens, stack the portrait and copy of split spreads while preserving square media and the cream/white contrast.
- Keep the invitation's square notches and single unified form construction; reduce headline size and side insets before sacrificing its illustrated frame.
- Let monumental menu entries wrap as coherent phrases rather than squeezing them into tiny navigation text.

**Unknown:**

- Exact mobile font sizes, navigation menu behavior and index column counts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
