# Kira Learning — paper meets electric play

## Overview

An editorial serif gives serious software a human, classroom-made warmth, while electric purple and mint collage keep it lively. The predominantly white and pale cream pages pair restrained sans-serif explanations with oversized interface scenes, cut-paper symbols and hand-drawn marks. It suits complex products that need both institutional credibility and an approachable personality; the reading density is low even when the product imagery is detailed.

### Essentials

- Editorial promises with two highlighted nouns: Recife Text at 56px/1.2, weight 400 and -0.4px tracking, with a purple rectangular mark and mint 14px-radius mark embedded in the sentence.
- A compact promise above an expansive product world: a 64px cream navigation bar, a 420px centered cream opening with 64px vertical padding, then a full-width 1440×667 interface collage that continues below the first fold.
- Small, square-ended actions keep the art in charge: 42px-high dark and transparent buttons, 12px 16px padding, 16px sans-serif labels and an 8px gap; not oversized pills.
- Color lives in the artwork, not the reading canvas: white dominates the long body, cream holds the opening, pale stone backs copy panels, and purple, mint, yellow and cyan concentrate inside illustrated product scenes and small symbols.
- Software is staged like a paper craft: readable white interface panels overlap saturated polygons, faint graph-paper grids, textured circles and black scribbles. Every new landing page needs this collage language; use a simplified real workflow panel if full product media is unavailable.
- A monumental brand sign-off balances the intimate typography: a charcoal footer with a narrow utility strip and a purple wordmark artwork spanning 1344×466 inside 48px side insets. Use the new product's own large letterform artwork to retain this device.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Paper purple | `#ac99ff` | `--color-purple` | accent, surface | Purple collage family, headline marking and monumental letterform artwork; match the softly textured purple treatment. Solid card fills belong to the launch variant. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mint marker | `#56eaaf` | `--color-mint` | accent, surface | Rounded word-level highlight within the main promise. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#1a1a1a` | `--color-ink` | text, action, background | Default serif headings, primary buttons and the monumental footer. |
| Warm gray copy | `#6b6761` | `--color-muted` | text | Supporting paragraphs on light surfaces. |
| Soft reversed gray | `#a3a3a3` | `--color-footer-copy` | text | Visible result of white at 60% over charcoal; use rgba(255,255,255,0.6) for footer utility text. |
| Warm pale stone | `#f5f5f4` | `--color-stone` | surface | Flat feature copy panels, capability card bases and the trust band. |
| Cream paper | `#fffdf0` | `--color-cream` | background, text | Opening and navigation canvas; reversed primary-button text. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Long-form page canvas, interface framing and bright footer symbols. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| launch openings | Translucent mint marker | `#7cefc0` | `--color-launch-mint-mark` | accent | Visible mint from rgba(87,235,175,0.78) on cream; a rectangular inline highlight. |
| launch openings | Translucent violet marker | `#a39aff` | `--color-launch-purple-mark` | accent | Visible violet from rgba(119,92,255,0.68) on cream; a rectangular inline highlight. |
| launch pages | Launch black | `#000000` | `--color-launch-black` | text, action | Large launch promise and its single dark action. |
| launch pages | Launch footer charcoal | `#1d1d1d` | `--color-launch-dark` | background | Directory footer background. |
| launch pages | Launch gray | `#464646` | `--color-launch-ink` | text | Capability heading, labels and serif descriptions. |
| launch directory footers | Launch reversed links | `#bbbbbb` | `--color-launch-links` | text, link | Visible white at 70% over launch charcoal; use rgba(255,255,255,0.7). |
| launch pages | Launch neutral canvas | `#f6f6f6` | `--color-launch-canvas` | background | Page backing and the 60px separation before the footer. |

## Typography

- **Recife Text Web** — Promises, section headings and small card titles; launch descriptions also use the serif. Literary, rounded old-style serif with a substantial x-height and relaxed regular cut. If unavailable, use **Lora**. Use 400, 500 and 700; check line wrapping against the measured column widths. Font stack: "Recife Text Web", "Lora", Georgia, serif.
- **Messina Sans Web** — Navigation, explanations and action labels. Unshowy humanist-grotesk sans, compact enough for dense interface-adjacent explanations. If unavailable, use **Inter**. 400 for prose, 600 for action labels and 700 for launch card labels. Font stack: "Messina Sans Web", "Inter", Arial, sans-serif.
- **Inter** (only for launch directory footers) — Footer links and utility text. Neutral sans with open counters. Font stack: "Inter", Arial, sans-serif.
- **Funnel Display** (only for launch directory footers) — Small bold column headings. Friendly rounded display sans used at body scale. Font stack: "Funnel Display", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Recife Text Web | 400 | 56px | 1.2 | -0.0071em | Centered two-line opening promise. |
| heading | Recife Text Web | 400 | 48px | 1.1 | -0.0062em | Primary section leads and closing call. |
| editorial-statement | Recife Text Web | 400 | 48px | 1.2 | -0.0083em | Centered problem-and-reframe statement with inline marks. |
| feature-heading | Recife Text Web | 400 | 32px | 1.1 | -0.0094em | Headings inside large alternating feature panels. |
| card-heading | Recife Text Web | 400 | 20px | 1.1 | -0.015em | Capability card titles and trust-band title. |
| body-lead | Messina Sans Web | 400 | 18px | 1.4 | -0.0167em | Standalone compatibility-section explanation. |
| body | Messina Sans Web | 400 | 16px | 1.4 | -0.019em | Support lines, navigation and explanatory card paragraphs. |
| action | Messina Sans Web | 600 | 16px | 1 | -0.019em | Compact semibold action labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| launch pages | launch-display | Recife Text Web | 500 | 82px | 1.2 | normal | Oversized two-line campaign promise. |
| launch pages | launch-heading | Recife Text Web | 700 | 52px | 1.2 | normal | Bold heading above the colored capability grid. |
| launch pages | launch-card-heading | Messina Sans Web | 700 | 23px | 1.4 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Bold labels within purple capability cards. |
| launch pages | launch-body | Recife Text Web | 400 | 18px | 1.4 | normal | Serif descriptions on purple cards. |
| launch directory footers | directory-link | Inter | 400 | 16px | 1.4 | normal | Directory links and footer utility text. |
| launch directory footers | directory-heading | Funnel Display | 700 | 16px | 1.4 | normal | Footer category labels. |

**Notes:**

- Use regular serif weight for the default marketing hierarchy; size and line-height, not boldness, establish the hierarchy.
- Keep body copy sans-serif in the default treatment. The serif body and bold section lead are launch-specific reversals, not a second default.
- The action family is the semibold cut; preserve its visual semibold weight rather than making labels black-weight.
- Inline marks stay attached to words and participate in line wrapping; keep surrounding text on the same baseline.

## Layout

**Density:** Airy: long white pauses separate compact paragraphs, while illustrated cards pack their content more closely.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Paired action gap. |
| 10px | Small card title-to-copy gap. |
| 20px | Default grid gutter and feature heading-to-copy gap. |
| 24px | Opening content gaps and launch card padding. |
| 30px | Main page side inset. |
| 32px | Default card and feature-panel padding. |
| 40px | Trust-band padding and spacious heading-to-support separation. |
| 48px | Feature-row separation, heading-to-grid separation and footer inset. |
| 64px | Opening vertical padding and compatibility artwork separation. |
| 100px | Main narrative section top and bottom padding. |
| 200px | Deep white pause before the editorial reframe. |

### Containers and grids

- **page-container**: max width 1440px · side padding 30px. Centered wide body sections with near-full-width card grids.
- **opening-copy**: max width 640px. Centered serif promise; support paragraph is narrower at 550px.
- **reading-column**: max width 620px. Short centered explanations and final call.
- **feature-chapters**: max width 1196px · gap 48px · side padding 60px. Inset alternating two-part rows; inner row spans 1076px with equal 538px halves.
- **capability-grid**: 3 columns · gap 20px. Three equal columns of 447px-wide image-led cards at desktop.
- **trust-grid**: max width 960px · 4 columns · gap 20px. Four centered illustrated assurances with short captions.
- **launch-grid** (only for launch pages): max width 1192px · 3 columns · gap 24px. Equal purple text cards within a white panel.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action-corners | 0px |
|  | mint-word-mark | 14px |
| launch pages | launch-card-corners | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | action-edge | `rgba(235, 235, 235, 0.25) 0px 1px 2px 0px` | Subtle edge under compact actions. |
| launch pages | launch-card-edge | `rgba(18, 43, 105, 0.04) 0px 2px 6px 0px, rgba(18, 43, 105, 0.08) 0px 1px 2px 0px, rgba(18, 43, 105, 0.08) 0px 0px 0px 1px` | Fine raised edge around purple cards. |

### Surfaces

#### White canvas · level 0

**Use:** Default long marketing page.

**CSS:** `background-color: #ffffff`

**Observed:** Large unbroken white intervals let the colorful art remain discrete.

**Transfer:** Keep reading sections on white rather than tinting every chapter.

#### Cream opening · level 0

**Use:** Navigation and promise region.

**CSS:** `background-color: #fffdf0`

**Observed:** A flat pale paper tone, without blur or glow.

**Transfer:** Carry this tone across the opening and navigation.

#### Stone panel · level 1

**Use:** Feature explanations, capability text bases and assurance band.

**CSS:** `background-color: #f5f5f4; border-radius: 0px; box-shadow: none`

**Observed:** Flat rectangular surfaces sit flush beside or beneath image panels.

**Transfer:** Let the artwork supply the saturation; keep explanation surfaces neutral.

#### Charcoal ending · level 0

**Use:** Monumental footer.

**CSS:** `background-color: #1a1a1a; overflow: hidden`

**Observed:** Solid dark ground sharply interrupts the white page and supports oversized purple letterforms.

**Transfer:** Use a single clear dark ending rather than repeated dark bands.

#### Purple launch card · level 1

**Only for:** launch pages

**Use:** Text-led capability grid.

**CSS:** `background-color: #ac99ff; border-radius: 12px; box-shadow: rgba(18, 43, 105, 0.04) 0px 2px 6px 0px, rgba(18, 43, 105, 0.08) 0px 1px 2px 0px, rgba(18, 43, 105, 0.08) 0px 0px 0px 1px`

**Observed:** Uniform purple fills replace image-led neutral cards.

**Transfer:** Reserve this denser color system for a focused release announcement.

## Components

### Sticky navigation

**Use:** Persistent orientation on a full marketing page.

**CSS:** `height: 64px; background-color: #fffdf0; padding: 0px 20px; display: flex; align-items: center; position: sticky; top: 0px; z-index: 10`

**Text style:** `body` — Messina Sans Web 400 · 16px/1.4 · tracking -0.019em

**Observed:** Small dark wordmark at left, text menus immediately beside it, account links and compact primary action at right. Downward purple triangles distinguish menus.

**Transfer:** Keep the header light and shallow; allow the hero rather than the menu to dominate.

### Primary button

**Use:** Main preview or exploration action.

**CSS:** `background-color: #1a1a1a; color: #fffdf0; border-radius: 0px; padding: 12px 16px; height: 42px; display: inline-flex; align-items: center; justify-content: center; box-shadow: rgba(235, 235, 235, 0.25) 0px 1px 2px 0px`

**Text style:** `action` — Messina Sans Web 600 · 16px/1 · tracking -0.019em

**Observed:** A short text-only rectangle; repeated in both the opening and closing action pair.

**Transfer:** Use a short product-specific exploration verb.

### Secondary button

**Use:** Companion sales action.

**CSS:** `background-color: transparent; color: #1a1a1a; border-radius: 0px; padding: 12px 16px; height: 42px; display: inline-flex; align-items: center; justify-content: center; box-shadow: rgba(235, 235, 235, 0.25) 0px 1px 2px 0px`

**Text style:** `action` — Messina Sans Web 600 · 16px/1 · tracking -0.019em

**Observed:** Light, visually faint-edged companion to the dark button; follows it horizontally.

**Transfer:** Keep it adjacent with an 8px gap rather than assigning equal dark emphasis.

### Inline mint mark

**Use:** Highlight the destination noun in an editorial promise.

**CSS:** `background-color: #56eaaf; color: #1a1a1a; border-radius: 14px; padding: 0px 8px`

**Text style:** `display` — Recife Text Web 400 · 56px/1.2 · tracking -0.0071em

**Observed:** Word-sized highlight embedded in the serif line, paired with a purple marked term elsewhere.

**Transfer:** Highlight one meaningful destination or audience phrase, not an entire line.

### Feature explanation panel

**Use:** Text half of an alternating product chapter.

**CSS:** `background-color: #f5f5f4; padding: 32px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `feature-heading` — Recife Text Web 400 · 32px/1.1 · tracking -0.0094em

**Observed:** A colorful square symbol sits at the upper left; heading and paragraph settle toward the lower edge. Its partner is an equal-sized vivid product illustration.

**Transfer:** Use a single benefit and concrete mechanism per row.

### Image-led capability card

**Use:** Scannable capability families.

**CSS:** `background-color: #f5f5f4; padding: 32px; display: flex; flex-direction: column; gap: 10px; border-radius: 0px`

**Text style:** `card-heading` — Recife Text Web 400 · 20px/1.1 · tracking -0.015em

**Observed:** This text base sits directly below a 447×252 product collage; title precedes a muted sans paragraph. The whole card is about 418px tall.

**Transfer:** Use equal image ratios and similar paragraph lengths across the grid.

### Assurance band

**Use:** Compact trust or validation strip beneath illustrated principles.

**CSS:** `background-color: #f5f5f4; padding: 40px; display: flex; align-items: center; gap: 24px`

**Text style:** `card-heading` — Recife Text Web 400 · 20px/1.1 · tracking -0.015em

**Observed:** A short serif title occupies the left; a compact row of six 56px credential graphics sits to the right.

**Transfer:** Use only relevant verifiable credentials or concrete product guarantees.

### Monumental footer

**Use:** Default final brand impression.

**CSS:** `background-color: #1a1a1a; padding: 48px 48px 0px; overflow: hidden`

**Observed:** A utility strip with social icons and understated legal text is bounded by fine rules. After a 48px gap, a giant purple wordmark fills nearly all remaining width, with its lower forms cut by the page edge.

**Transfer:** Make the new identity into large letterform artwork; retain the extreme scale contrast between utilities and the mark.

### Launch capability card

**Only for:** launch pages

**Use:** Dense release-summary grid.

**CSS:** `background-color: #ac99ff; border-radius: 12px; padding: 24px; display: flex; flex-direction: column; gap: 4px; box-shadow: rgba(18, 43, 105, 0.04) 0px 2px 6px 0px, rgba(18, 43, 105, 0.08) 0px 1px 2px 0px, rgba(18, 43, 105, 0.08) 0px 0px 0px 1px`

**Text style:** `launch-card-heading` — Messina Sans Web 700 · 23px/1.4 · tracking -0.04em

**Observed:** Small monochrome icon, bold sans label, then a serif description. Equal cards are 381×275 at desktop.

**Transfer:** Let the text carry the capability rather than adding another full-size image.

### Directory footer

**Only for:** launch pages

**Use:** Navigation-heavy ending for a compact campaign.

**CSS:** `background-color: #1d1d1d; padding: 24px 54px; overflow: hidden`

**Text style:** `directory-link` — Inter 400 · 16px/1.4

**Observed:** Small identity and social row above three equal directory columns; bold category labels precede links spaced 12px apart. A fine divider separates copyright and legal links, with double-slash separators.

**Transfer:** Use this in place of a link-heavy expansion of the monumental footer; retain a letterform-art device elsewhere in the campaign.

## Imagery and graphics

### Electric paper product collages

**Use:** Required product storytelling device, from the broad opening stage to feature and capability images.

**Observed:** White software panels are the main subject. Their backing mixes purple graph paper, saturated mint or cyan fields, cropped yellow wedges, textured purple polygons and circles, pink fragments and black scribbles. Small round-eyed purple characters or abstract symbols overlap foreground edges. The opening scene spans the viewport; feature scenes take one half of a row. Smaller grid scenes fade softly into the pale card base.

**Transfer:** Use real UI from the new product in a legible white panel. Where no interface exists, draw a small working process with truthful labels inside the same panel. Keep the backing tactile and geometric rather than rendering a glossy device.

**Build:** Create an SVG collage at 1440×667 for the wide scene or 538×454 for feature scenes. Lay a lavender rectangle behind a low-contrast square grid spaced roughly 28px. Add one oversized cropped circle or irregular 5–6-sided polygon in a deeper violet and one mint field or yellow wedge. Place the white workflow panel above them with generous surrounding color. Apply subtle SVG turbulence as a clipped multiply texture to colored shapes, not the UI. Add a short irregular black path near an edge with a rounded stroke about 4px wide. Use a simple two-eyed geometric helper or stacked paper shapes as the minimum foreground ornament.

### Hand-drawn editorial connector

**Use:** A wide visual release below the problem-and-reframe copy.

**Observed:** A black line loops, stumbles and resolves across a broad white field; a large yellow pencil touches its right end. The illustration is 1196×242 and has no containing card.

**Transfer:** Show a tangled path becoming a clear path, using a drawing tool or equivalent product-relevant object at the end.

**Build:** Use an SVG viewBox of 0 0 1196 242. Draw one uneven continuous black cubic-Bezier path with several narrow vertical loops on the left and a smooth long arc on the right, stroke-width about 4, fill none. Add a few short motion ticks. Build the tool from a yellow rotated rectangle, peach triangle and dark triangular tip; keep the surrounding field white.

### Cut-paper assurance symbols

**Use:** Trust principles and small feature markers.

**Observed:** Bright slightly rotated squares contain simple sliders, magnifier, lock and check symbols. Purple, mint, pink, cyan, yellow and orange contrast without gradients; a little paper texture softens the edges. Large trust symbols are 128×128; feature markers are 64×64.

**Transfer:** Choose one easily understood object per assurance. Keep captions outside the symbol rather than placing text inside the art.

**Build:** Use a 128px SVG square rotated a few degrees. Layer two or three flat rectangles, circles or polygons with deliberately blunt silhouettes; use complementary saturated colors, no outlines, and a low-opacity noise mask. At 64px remove fine detail.

### Graph-paper compatibility ribbon

**Use:** Wide compatibility or ecosystem proof.

**Observed:** A horizontal band overflows the page edges. Slightly skewed cream graph-paper panels about 250×170 contain centered partner marks; bright square symbols alternate between the panels. The rest of the section stays white.

**Transfer:** Use the new product's real ecosystem partners or compatible formats. Retain the alternating paper-panel and symbol rhythm even with fewer partners.

**Build:** Make a horizontal flex strip with overflow clipped at the section boundary. Back each roughly 250×170 panel with cream and repeating thin gray grid lines around 28px apart. Alternate rotations around -4deg and 4deg and place dark centered marks on top. Insert 70px colorful symbol squares between selected panels. Keep the strip visually larger than its text column.

### Monumental letterform artwork

**Use:** Required large identity device, normally in the dark ending.

**Observed:** Purple block letterforms extend across 1344px and occupy a 466px-high art window. Broad geometric strokes, circular counters and a tilted initial make the mark read as a graphic object rather than another heading.

**Transfer:** Create an original SVG of the new product's identity at near-container width. For a long name use an original monogram or a short owned word, with similarly heavy strokes and intentional edge clipping.

**Build:** Draw or outline the new identity in SVG, fill with the paper-purple family, and place it in an overflow-hidden 1344×466 proportional frame on charcoal. Scale to the width so the artwork dominates the lower footer. Keep utilities outside the artwork; do not emulate this with the regular serif heading font.

### Launch video poster

**Only for:** launch pages

**Use:** A focused demonstration beneath the campaign promise and single sales action.

**Observed:** A centered framed poster about 846×407 sits on a cream backing panel about 1000×467. Its upper area repeats a miniature editorial promise and a pink tilted date sticker; below is the purple-backed product collage with a central play control. The frame has a pale substantial edge and a visible soft offset shadow.

**Transfer:** Compose an actual demonstration poster with a short preview title and authentic release detail. Retain the paper edge and collage rather than using a black video rectangle.

### Icons

**Observed:** Navigation uses tiny down triangles. Social marks are small monochrome silhouettes; the default ending uses white 24px social icons. Feature and trust symbols are colorful paper illustrations rather than a uniform outline icon library. Launch cards use restrained 24px monochrome symbols.

**Transfer:** Use flat monochrome marks for utility controls and custom geometric paper symbols for storytelling. Do not replace illustrated assurances with generic thin-stroke shield icons.

## Section recipes

How recurring sections are built.

### First screen: Highlighted promise over product stage

**Observed:** Back-to-front layers are a flat Cream opening, a centered two-line serif promise with purple and mint inline marks, a muted centered support paragraph and a small Primary button plus Secondary button. Sticky navigation occupies the top 64px. The opening beneath it is 420px tall with 64px vertical padding; promise width is capped at 640px, support at 550px and content gaps at 24px. The headline reads at 56px/1.2 and spans about two-fifths of the desktop width. At 484px down the page, Electric paper product collages begin edge-to-edge. Within the first 900px the full promise, support and actions are visible, plus the upper part of the enormous white interface on purple graph paper; the rest of that artwork continues below the fold.

**Transfer:** Lead with a concise product-category promise and two meaningful marked terms. Stage a real workflow panel against paper geometry if no finished product artwork exists. Launch pages instead open with a centered identity above an 82px medium serif promise, then one broad dark action and the Launch video poster; keep that treatment scoped to a release campaign.

**Avoid:** Do not turn the opening into a split hero with a tiny laptop thumbnail, or stretch the text to fill the entire viewport. The first screen needs both the compact complete promise and a substantial start of the collage.

**Text style:** `display` — Recife Text Web 400 · 56px/1.2 · tracking -0.0071em

### Editorial reframe and drawn path

**Observed:** A deep 200px white pause precedes a centered 48px/1.2 statement in a 730px column. A superseded term receives a hand-drawn strike and the replacement receives a purple mark. Two compact sans paragraphs explain the change; the Hand-drawn editorial connector expands underneath.

**Transfer:** Contrast an old fragmented habit with the new approach, then use the line drawing to turn the conceptual shift into a visual beat.

**Text style:** `editorial-statement` — Recife Text Web 400 · 48px/1.2 · tracking -0.0083em

### Alternating feature chapters

**Observed:** A centered 48px lead introduces equal image-and-Stone panel rows. Rows are 1076px wide and about 455px high, separated by 48px; image sides alternate. Feature explanation panel places its marker high and its 32px serif benefit plus body copy low.

**Transfer:** Alternate image and copy to prevent a long explanation from becoming a repeated left-aligned list.

**Text style:** `feature-heading` — Recife Text Web 400 · 32px/1.1 · tracking -0.0094em

### Wide capability family

**Observed:** A left-aligned 48px heading and a short supporting paragraph share a wide introductory row. After 48px, Image-led capability cards form a three-column grid with 20px gaps. Images take roughly three-fifths of each card's height; compact copy is inset 32px.

**Transfer:** Group offerings by user task, not internal architecture. Keep each card a similarly weighted entry point.

**Text style:** `card-heading` — Recife Text Web 400 · 20px/1.1 · tracking -0.015em

### Illustrated trust chapter

**Observed:** A centered 48px serif heading sits above four Cut-paper assurance symbols and short centered captions. Below them the Assurance band pairs a left title with credential graphics on the right. The chapter uses 100px top padding and a white canvas.

**Transfer:** Translate risk reduction into a few specific assurances, supported by relevant visible proof.

**Text style:** `heading` — Recife Text Web 400 · 48px/1.1 · tracking -0.0062em

### Compatibility ribbon

**Observed:** A centered serif heading over two lines, an 18px sans explanation in a 620px column, then a 64px separation to the Graph-paper compatibility ribbon. The band extends beyond the text column and clips at the page edges.

**Transfer:** Show continuity with the reader's existing setup rather than a detached logo wall.

**Text style:** `heading` — Recife Text Web 400 · 48px/1.1 · tracking -0.0062em

### Compact invitation and huge sign-off

**Observed:** A centered 48px closing line, a short body paragraph and paired actions lead directly into the Monumental footer. The invitation has 100px top padding and a 620px reading width. The ending is 636px tall with the utility strip above the oversized letterform art.

**Transfer:** End with a practical next step, then let the graphic identity provide the emotional full stop.

**Text style:** `heading` — Recife Text Web 400 · 48px/1.1 · tracking -0.0062em

### Launch capability sheet and directory

**Only for:** launch pages

**Observed:** A white 1300px-wide panel with 54px side padding contains a left bold 52px serif lead and a three-by-two purple card grid with 24px gutters. Cards use bold 23px sans headings and 18px serif descriptions. A 60px neutral band precedes Directory footer; no separate final invitation is added.

**Transfer:** Use this shorter, text-led format for a release whose main conversion already happened near the opening.

**Text style:** `launch-heading` — Recife Text Web 700 · 52px/1.2

## Page flow

**Storyline:** Category promise → tangible demonstration → explanation of the change → capability proof → confidence and compatibility → next step → distinctive brand sign-off.

### Full product marketing landing page

1. **Promise** — Cream, highlighted serif promise with concise support and paired actions.
2. **Product demonstration** — A full-width electric paper interface scene.
3. **Problem and reframe** — Editorial contrast, short explanations and a hand-drawn resolving path.
4. **Capability chapters** — Centered lead and alternating image-and-copy feature rows.
5. **Breadth** — A wide three-column image-led capability grid.
6. **Objection handling** — Illustrated assurances, a credential strip and a graph-paper compatibility ribbon.
7. **Closing call** — Small centered invitation with the same action pair.
8. **Brand sign-off** — Dark utility strip and monumental purple identity artwork.

**Transfer:** Adapt the number and order of proof chapters to the product while preserving the mix of editorial explanation, vivid paper-backed demonstrations and a monumental identity device.

### Focused release or campaign page

1. **Promise** — Centered identity and larger highlighted serif category line.
2. **Conversion and demonstration** — Single broad dark sales action above a framed demonstration poster.
3. **Capability summary** — Bold section lead and purple text-card grid.
4. **Navigation ending** — Neutral separator followed by a three-column dark directory and legal row.

**Transfer:** Compress the long product argument into a promise, demonstration and capability sheet. Use the scoped launch typography and surfaces without carrying them into an ordinary landing page.

## Writing

Confident, practical and gently corrective. The product is presented as a coherent way to do real work, not a magical assistant; warm visual play is balanced by grounded operational language.

**Do not copy:** Do not reuse Kira's name, logo, proprietary illustrations, customer or partner marks, product-version labels, compliance assertions or claims about educational outcomes. Use original identity assets and independently supported claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly declarative third-person product statements and reader-centered benefits; occasional direct 'you' in explanatory copy and evaluation invitations. Buttons use direct verbs.
- **Rhythm:** Headlines are usually 5–10 words, often contrasting a better system with a fragmented habit. Paragraphs mix one longer explanatory sentence with short emphatic conclusions. Actions are 2–4 words; punctuation stays restrained.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a category and the audience or domain it serves, with two words given visual emphasis. | 6–10 words | “The AI operating system for education” |
| Reframe | Reject the familiar accumulation of tools, then name the coherent alternative. | Two short sentences | “Schools do not need more AI tools. They need a system.” |
| Feature benefit | State the desirable operating condition, often with a 'not' contrast. | 5–8 words | “Coherent instruction, not fragmented workflows” |
| Supporting explanation | Explain the mechanism and the practical burden it removes. | 20–35 words | “Kira connects planning, teaching, assessment, and insight into one continuous loop, eliminating handoffs between tools and teams.” |
| Trust lead | Pair suitability with an inherent design assurance. | Two concise clauses | “Built for schools. Compliant by design.” |
| Action | Offer a concrete preview or a conversation rather than an abstract journey. | 2–4 words | “Book a demo”<br>“Preview Kira 2.0” |

**Words and phrasing to use:** connected; one system; works with; real-time; built-in; visible; control; ready to run; not fragmented

**Avoid:** revolutionary magic; unleash limitless potential; disrupt everything; effortless perfection; hype-heavy superlatives

**Rules:**

- Tie every benefit to a mechanism, such as removing a handoff or keeping information current.
- Use contrast to clarify the product's difference, not to mock the reader's current workflow.
- Let reassurance speak in concrete control, compatibility and transparency terms.
- Keep dense technical language in explanatory copy rather than in the highlighted promise.

## Do's and Don'ts

### Do

- Keep the default display at 56px with regular serif weight and 1.2 line-height.
- Use 16px/1.4 sans-serif support copy with warm gray color.
- Keep opening support to 550px and general centered explanations to 620px.
- Preserve 32px copy-panel padding and 20px default card gutters.
- Use the 48px gap to separate alternating feature chapters.
- Include saturated paper geometry behind real product proof, not behind every paragraph.
- Give the final letterform artwork near-full container width with 48px footer insets.
- Retain the 42px compact action height even beside much larger art.

### Don't

- Do not apply the launch grid's 12px radius to default feature and capability panels; those are square.
- Do not promote 82px campaign type to the default opening scale.
- Do not set default body paragraphs in serif just because the headings are serif.
- Do not make all cards purple; neutral reading panels are the normal marketing surface.
- Do not substitute glossy 3D device mockups for the flat paper-and-interface staging.
- Do not use black-weight serif headings in the default 48px section hierarchy.
- Do not replace the edge-clipped compatibility ribbon with a tightly boxed row of tiny logos.
- Do not turn the final identity device into a small conventional footer logo.

## Motion and responsive

### Motion

**Observed:**

- Footer utility links declare a color transition of 0.2s cubic-bezier(0.44, 0, 0.56, 1). Hover changes the muted reversed text to white without an underline.

**Transfer:**

- Use the restrained color transition for small footer utilities; retain static legibility of the paper scenes.

**Unknown:**

- No reliable timing for scene entrances, scrolling artwork or ribbon travel is established.

### Responsive

**Observed:**

- Style rules declare breakpoint boundaries around 780px, 790px, 810px and 992px for the full marketing layout, and around 810px and 1200px for the launch layout.

**Transfer:**

- On narrow screens, stack each feature image with its copy panel, preserving the marker-above-benefit composition.
- Reduce grid columns when the 240px minimum card content width no longer fits; retain the picture-to-text order.
- Keep compatibility panels wider than their text column and clip the outer strip; scale the monumental artwork proportionally rather than shrinking it to a utility logo.

**Unknown:**

- Exact mobile type sizes, navigation behavior and breakpoint-specific geometry are not established; these collapse rules are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
