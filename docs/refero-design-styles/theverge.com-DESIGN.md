# The Verge — editorial voltage

## Overview

A restless editorial style that mixes newspaper authority with fluorescent internet culture. A mostly white canvas, black headlines, electric violet markings, and mint details support dense, image-led storytelling. Extremely compressed display lettering sits alongside blunt grotesk headlines, readable serif summaries, and tiny monospaced controls. It suits products with strong opinions, frequent updates, and enough substance to reward browsing.

### Essentials

- The opening is a front-page composition rather than a centered sales pitch: a 680×544px lead image in an 800px editorial column sits beside a 380px update rail, separated by a 1px dashed rule and 40px clearance.
- Lettering becomes architecture: use a vertical oversized brand-name treatment alongside the opening image and a compressed 90px/0.8, weight 900 headline on an overlapping white caption plate. A new wordmark or condensed product-name treatment supplies the same graphic force.
- Headlines and explanation speak in different voices: 34px/1 weight 700 grotesk titles contrast with 20px/1.2 serif summaries; metadata drops to 11px/1.2 capitals with 0.1em tracking.
- Color behaves like editorial punctuation: keep ordinary content predominantly white, use #5200ff for rules, links, author lines and compact actions, #eee6ff for rank markers, and #3cffd0 for highlights and footer icons. Full violet title bands belong to category pages, not the default landing page.
- Controls deliberately mix shapes by job: subscription links are 22px high with 2px corners; continuation actions are 40px high with 1px corners; 44px-high feed tabs have 24px corners. Do not turn every action into the same pill.
- Include an acid-colored editorial feature panel: an 800×450px rectangular stage combines geometric marks, a 5px black top rule, translucent 56px header, and a bold-to-light slash-separated statement. Its minimum equivalent is a text-led feature with simple squares, crosses and diagonal bars.
- End in a black publishing-style colophon: an 1100px inner width holds a substantial white brand mark, 39px mint-outlined social circles, horizontal link groups, and a smaller bottom utility row rather than another oversized sales headline.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#5200ff` | `--color-violet` | accent, action, link, border, background | Editorial rules, links, author names, selected tabs, subscription action; category title-band fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal mint | `#3cffd0` | `--color-mint` | accent, action, border | Footer social outlines and title-link highlight; follow actions on category pages. |
| Lavender marker | `#eee6ff` | `--color-rank` | surface | Number tiles in ranked lists. |
| Acid yellow | `#d6f31f` | `--color-acid` | text, accent | Video-action lettering and accent details inside the acid editorial feature. |
| Lemon paper | `#f5fcc7` | `--color-feature-paper` | surface | Pale yellow-green foundation for the geometric editorial feature. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, overlapping lead caption plate, and inverse text. |
| Separator gray | `#e9e9e9` | `--color-rule` | border, surface | Item dividers, thumbnail edges, inactive feed tabs, and heavier feature separators. |
| Colophon gray | `#949494` | `--color-fine-print` | text | Low-emphasis ownership text in the closing band. |
| Metadata gray | `#636363` | `--color-muted` | text | Dates, comments, captions, and inactive control text. |
| Reading gray | `#4a4a4a` | `--color-body` | text | Serif paragraphs and lightweight section explanations. |
| Headline ink | `#131313` | `--color-ink` | text, background | Headlines, navigation, and the closing band. |
| Feature black | `#111111` | `--color-feature-ink` | background, border | Feature-panel top rule and video control. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Editorial red | `#ee0033` | `--color-badge` | surface | Small format labels such as review or interview, never a full card fill. |

## Typography

- **polySans** — Headlines, navigation, metadata and footer links. Compact contemporary grotesk with blunt, forceful bold cuts and a markedly lighter supporting cut. If unavailable, use **Inter**. Use 300 for explanations and 700 for headlines; preserve tight line heights. Font stack: "polySans", "Inter", Helvetica, Arial, sans-serif.
- **manuka** — Lead-story headline and monumental category lettering. Extremely narrow, tall display letters, packed into short vertical space at very heavy weights. If unavailable, use **Anton**. Use the heavy condensed silhouette; tune width before increasing size. Font stack: "manuka", "Anton", Impact, Helvetica, sans-serif.
- **fkRomanStandard** — Editorial descriptions, summaries and reading text. Matter-of-fact newspaper roman with a lively italic and strong contrast against the sans headlines. If unavailable, use **Libre Caslon Text**. Font stack: "fkRomanStandard", "Libre Caslon Text", Georgia, serif.
- **polySansMono** — Utility actions, feed tabs, rank numerals and image captions. Mechanical monospaced markings used sparingly rather than as the main reading voice. If unavailable, use **IBM Plex Mono**. Font stack: "polySansMono", "IBM Plex Mono", Courier New, Courier, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | manuka | 900 | 90px | 0.8 | normal | Compressed lead-story headline on the white overlapping plate. |
| feature-title | polySans | 700 | 34px | 1 | normal | Large editorial card title, especially in the update rail. |
| kicker-title | polySans | 700 | 31px | 1.3 | -0.01em | Bold opening clause within the acid editorial panel. |
| kicker-support | polySans | 300 | 31px | 1.3 | -0.01em | Lightweight explanation continuing the feature statement after a slash. |
| section-heading | polySans | 700 | 24px | 1.1 | 0.01em | Curated-section title and lower-page shelf heading. |
| section-support | polySans | 300 | 24px | 1.1 | 0.01em | Inline explanation after the violet slash in section headings. |
| lead-summary | fkRomanStandard | 400 | 24px | 1.2 | normal | Lead-story explanation beneath the display title. |
| rank-number | polySansMono | 400 | 24px | 1 | normal | Large numerals centered in lavender tiles. |
| card-heading | polySans | 700 | 20px | 1 | normal | Compact cards, small shelves and ranked-list headlines. |
| summary | fkRomanStandard | 400 | 20px | 1.2 | normal | One-sentence support under feature titles. |
| navigation | polySans | 300 | 19px | 1.2 | normal | Main topical or product-area navigation. |
| body | fkRomanStandard | 400 | 16px | 1.3 | -0.01em | Update paragraphs and their inline links. |
| footer-link | polySans | 500 | 16px | 1.6 | normal | Primary footer navigation. |
| tab-label | polySansMono | 600 | 12px | 2 | 0.125em, uppercase | Latest and following feed selection. |
| video-label | polySansMono | 700 | 12px | 1 | 0.08em, uppercase | Video action inside the acid feature. |
| metadata | polySans | 400 | 11px | 1.2 | 0.1em, uppercase | Author names, times and comment totals; violet authors contrast with gray times. |
| subscribe-label | polySansMono | 400 | 11px | 13px | 0.1em, uppercase | Compact subscription and account utilities. |
| action-label | polySansMono | 500 | 11px | 1.2 | 0.1em, uppercase | Outlined continuation and sign-up actions. |
| utility-link | polySansMono | 400 | 11px | 1.3 | 0.1em, uppercase | More links and pagination labels. |
| image-caption | polySansMono | 400 italic | 11px | 1.3 | normal | Descriptive image captions immediately beneath media. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| category ranking rails | ranking-watermark | manuka | 1000 | 165px | 0.8 | 0.01em | Vertical mint lettering behind the narrow ranked list. |
| category landing pages | category-display | manuka | 900 | 160px | 1 | 0.01em | White title in the violet category banner. |
| category landing pages | follow-label | polySans | 500 | 16px | 1.2 | normal | Mint follow action. |
| category landing pages | category-eyebrow | polySans | 500 | 12px | 1.1 | 0.13em, uppercase | Small violet feed and ranking headings. |

**Notes:**

- Scale contrast comes from width and family, not just point size: reserve the extremely compressed face for major declarations and keep recurring card titles in the grotesk.
- Keep bold titles tightly stacked at 1 or 1.1 line height. Serif copy gets 1.2–1.3; the light sans explanations remain visibly subordinate even when they share the title's size.
- Uppercase is a metadata and control treatment, not the default headline voice. Normal sentence-case titles retain punctuation and contractions.

## Layout

**Density:** Dense inside editorial modules, with much larger pauses between curated groups; headlines, metadata and imagery are packed together without enclosing every item.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Title-to-summary gap in feature cards. |
| 8px | Image-to-title and title-to-metadata gaps. |
| 10px | Small section-header and update-detail spacing. |
| 12px | Separation between metadata items. |
| 20px | Rank-row padding and grid gaps. |
| 24px | Update-card vertical padding and four-card shelf gutters. |
| 30px | Section-header-to-content gap and curated stacks. |
| 40px | Main-column to rail clearance and rail inset. |
| 50px | Inset of shelf content and padding inside the dark closing band. |
| 60px | Rail module spacing. |
| 130px | Separation between major curated groups and lower shelves. |

### Containers and grids

- **editorial-frame**: max width 1300px · side padding 18px. Centered desktop frame for the default landing composition, with an 800px main column and 380px update rail; rail has a 1px dashed left rule, 40px left padding and 40px outer separation.
- **utility-container**: max width 1100px · side padding 20px. Centered navigation and closing-band contents.
- **curated-pair**: 2 columns · gap 30px. Large image-led story beside a vertical stack of compact stories; main story can be 380px wide.
- **shelf**: 4 columns · gap 24px. Lower-page browsing shelves with 202×134px images in a roughly 928px-wide left-aligned section.
- **category-river** (only for category landing pages): max width 1100px · side padding 20px. 700px story river followed by 100px separation and a 300px supporting rail.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | compact-actions-and-rank-tiles | 2px |
|  | outline-actions | 1px |
|  | thumbnail-edges | 3px |
|  | feed-tabs | 24px |
|  | social-circles | 50% |
|  | video-action | 9999px (pill) |
| category landing pages | follow-action | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| lead-caption-plate | `0px 3px 0px 20px #ffffff, 0px -25px 40px 0px rgba(0,0,0,0.3)` | White paper overlap at the bottom of the lead photo; not a general-purpose card elevation. |

### Surfaces

#### Paper canvas · level 0

**Use:** Continuous backdrop for almost all reading content.

**CSS:** `background-color: #ffffff; color: #131313`

**Observed:** Cards share the page background and are organized by rules rather than elevated boxes.

**Transfer:** Let large media and typography create hierarchy without adding a container fill to every block.

#### Lead caption plate · level 1

**Use:** Lead headline and summary overlapping a photograph.

**CSS:** `background-color: #ffffff; max-width: 480px; box-shadow: 0px 3px 0px 20px #ffffff, 0px -25px 40px 0px rgba(0,0,0,0.3)`

**Observed:** The plate is inset from the image's left edge and overlaps its bottom by 45px; its white surround visually interrupts the photo.

**Transfer:** Use the same paper interruption for the main product story, keeping text opaque and readable.

#### Acid feature stage · level 0

**Use:** A distinctive text-led feature among ordinary editorial modules.

**CSS:** `background-color: #f5fcc7; background-image: linear-gradient(rgba(0,0,0,0.024), rgba(0,0,0,0) 45%), linear-gradient(118deg, rgba(0,0,0,0.04) 0.5px, rgba(0,0,0,0) 0.5px); background-size: auto, 120px 120px; position: relative; overflow: hidden`

**Observed:** An 800×450px pale acid field carries sharp geometric marks under the editorial statement, not photography.

**Transfer:** Use for an important point of view or demonstration invitation.

#### Feature masthead · level 1

**Use:** Top strip of the acid feature.

**CSS:** `background-color: rgba(255,255,255,0.55); border-top: 5px solid #111111; backdrop-filter: blur(14px); height: 56px`

**Observed:** A small mono title and date sit at left; a motion control is aligned right.

**Transfer:** Use a compact issue label and an accessible motion control rather than a conventional card heading.

#### Editorial format badge · level 1

**Use:** Tiny label identifying a story format.

**CSS:** `background-color: #ee0033; color: #ffffff; border-radius: 2px; padding: 2px 4px`

**Observed:** A narrow red strip precedes a headline; it is not a large category pill.

**Transfer:** Reserve for meaningful content formats, not every card.

#### Closing ink band · level 0

**Use:** Full-width ending on both page types.

**CSS:** `background-color: #131313; color: #ffffff; padding: 50px 20px`

**Observed:** A secondary dark utility strip continues the band below the main link groups.

**Transfer:** Close with brand identity, ways to connect, and useful navigation.

#### Violet category band · level 0

**Only for:** category landing pages

**Use:** Monumental category title stage.

**CSS:** `background-color: #5200ff; color: #ffffff`

**Observed:** A full-width saturated upper field carries the navigation and white compressed title; the introduction below returns to white.

**Transfer:** Use for a product family or resource category rather than filling the whole landing page violet.

## Components

### Navigation

**Use:** Compact product-area browsing above the opening composition.

**CSS:** `color: #131313; font-size: 19px; font-weight: 300; line-height: 22.8px; border-bottom: 1px solid #131313`

**Text style:** `navigation` — polySans 300 · 19px/1.2

**Observed:** A small horizontal wordmark leads a single-line list with slash separators, then notification and menu icons. Account actions sit above at the right. The category variant uses white text and rule on violet.

**States:** Declared: hover opacity 0.5 on the navigation-link ancestor.

**Transfer:** Keep the editorial slash rhythm when replacing topic names with product areas.

### Subscribe action

**Use:** Small high-priority utility action in the header.

**CSS:** `background-color: #5200ff; color: #ffffff; border-radius: 2px; padding: 4px 5px 5px; height: 22px`

**Text style:** `subscribe-label` — polySansMono 400 · 11px/13px · tracking 0.1em · uppercase

**Observed:** A compact filled rectangle precedes a plain sign-in link. On violet category headers its fill switches to mint and text to ink.

**States:** Declared: hover background-color #636363; color #ffffff.

**Transfer:** Use for a short commitment action, not a wide promotional button.

### Outline action

**Use:** Continuation or newsletter sign-up.

**CSS:** `color: #5200ff; border: 1px solid #5200ff; border-radius: 1px; padding: 0px 20px; height: 40px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `action-label` — polySansMono 500 · 11px/1.2 · tracking 0.1em · uppercase

**Observed:** A small uppercase label sits in a near-square outline. Feed endings center the action beneath the last item.

**States:** Declared: hover background-color #5200ff; border 1px solid #5200ff; color #ffffff.

### Feed tabs

**Use:** Switch between recency and a personalized feed.

**CSS:** `background-color: #5200ff; color: #ffffff; border-radius: 24px; padding: 10px 24px; height: 44px`

**Text style:** `tab-label` — polySansMono 600 · 12px/2 · tracking 0.125em · uppercase

**Observed:** Selected violet tab sits over the left side of a light-gray paired pill; the inactive label uses reading gray. The pair stays above the update rail while browsing.

**States:** Declared: hover is unspecified; focus-visible outline 2px solid #5200ff; outline-offset 2px.

### Story card

**Use:** Image-led content and compact browsing shelves.

**CSS:** `color: #131313; background-color: #ffffff`

**Text style:** `card-heading` — polySans 700 · 20px/1

**Observed:** Image first, bold sentence-case headline second, optional serif explanation, then violet author and gray time/comment metadata. Four-column shelves use 202×134px media; major rail cards use the feature-title recipe. Compact story stacks can place a 75px thumbnail to the right.

**States:** Declared: hover headline box-shadow inset 0 -1px 0 0 #5200ff; color #131313. Selected larger headline links instead use inset 0 -.6em 0 0 #3cffd0.

**Transfer:** Use customer stories, use cases, release explainers or product comparisons with the same editorial hierarchy.

### Ranked row

**Use:** Ordered proof, popular resources or prioritized reading.

**CSS:** `border-bottom: 1px solid #e9e9e9; display: grid; grid-template-columns: 50px minmax(0px, 1fr); gap: 20px; padding: 20px 0px`

**Text style:** `card-heading` — polySans 700 · 20px/1

**Observed:** A 50×50px lavender tile with 2px corners holds a 24px mono numeral. The adjacent bold title has a small metadata line below. Five items form a typical ranked module.

**Transfer:** Use rank only when it expresses a real order; otherwise adapt the numeral to a deliberate step sequence.

### Inline link

**Use:** References embedded in serif reading text.

**CSS:** `color: #131313; box-shadow: inset 0px -1px 0px 0px #5200ff`

**Text style:** `body` — fkRomanStandard 400 · 16px/1.3 · tracking -0.01em

**Observed:** The violet underline remains present at rest, contrasting with gray paragraph text.

**States:** Declared: hover color #5200ff; box-shadow inset 0 -1px 0 0 #5200ff.

### Video action

**Use:** Play control within the acid feature.

**CSS:** `background-color: #111111; color: #d6f31f; border-radius: 9999px; padding: 11px 16px; height: 34px; display: flex; align-items: center; gap: 8px`

**Text style:** `video-label` — polySansMono 700 · 12px/1 · tracking 0.08em · uppercase

**Observed:** A small filled triangle precedes the mono label; the control sits beside a tall condensed series-name treatment.

**States:** Declared: hover opacity 0.88.

### Footer links

**Use:** Closing navigation and contact pathways.

**CSS:** `color: #ffffff; font-size: 16px; font-weight: 500; line-height: 25.6px`

**Text style:** `footer-link` — polySans 500 · 16px/1.6

**Observed:** Horizontal groups wrap as needed and use vertical-bar separators rather than a large multi-column sitemap. Smaller policy links occupy the following row.

**States:** Declared: hover text-decoration underline.

### Social circle

**Use:** Social or syndication links in the closing band.

**CSS:** `color: #3cffd0; border: 1px solid #3cffd0; border-radius: 50%; width: 39px; height: 39px; padding: 6px`

**Observed:** Five circles sit in one row with 14px gaps, aligned opposite the large white mark; each contains a 25px solid glyph.

**States:** Declared: hover color #131313; border 1px solid #3cffd0; background-color #3cffd0.

**Transfer:** Use only the channels relevant to the new product, retaining the circular outline family.

### Follow action

**Only for:** category landing pages

**Use:** Subscribe to an individual category.

**CSS:** `background-color: #3cffd0; color: #131313; border: 1px solid transparent; border-radius: 20px; height: 40px; padding: 0px 20px; display: flex; align-items: center; gap: 8px`

**Text style:** `follow-label` — polySans 500 · 16px/1.2

**Observed:** A plus icon precedes the label. The action sits on white immediately below the violet category banner.

**States:** Declared: hover background-color #131313; border 1px solid transparent; color #ffffff.

### Email field

**Only for:** newsletter rail modules

**Use:** Short newsletter conversion beside the content river.

**CSS:** `background-color: #ffffff; border: 1px solid #5200ff; border-radius: 2px; padding: 8px 12px; height: 40px; width: 164px`

**Observed:** The field sits beside an Outline action with a 10px gap, under a thin violet top rule and a compact violet title/support line.

**Transfer:** Keep the form visually smaller than the editorial content and attach it to a specific ongoing benefit.

## Imagery and graphics

### Editorial lead photography

**Use:** Dominant opening story and larger feature cards.

**Observed:** Documentary photographs, people in real settings, devices and colorful editorial composites appear as hard-edged rectangular images. The opening uses a person holding a sign under clear blue sky, with a 680×544px image and an inset paper caption; other stories use roughly 3:2 imagery. Images carry their own color rather than sharing a universal tint.

**Transfer:** Photograph the product in use or show a credible customer scene. When photography is unavailable, create one strong product-and-context composition rather than filling the opening with generic abstract gradients.

### Vertical brand lettering

**Use:** Graphic identity alongside the default opening.

**Observed:** An oversized black brand mark is rotated vertically beside the left edge of the lead image, acting like a printed spine rather than ordinary navigation text.

**Transfer:** Set the new product name or an original wordmark vertically; preserve strong black silhouette and an intentional overlap with the editorial composition.

**Build:** Use an SVG wordmark or heavy text group rotated -90deg, anchored to the lead story's left edge. Give it a tall visual footprint comparable to the lead image height, with a width narrow enough to leave the photo dominant; hide decorative duplicates from assistive technology.

### Acid geometric field

**Use:** Signature backdrop for the acid editorial feature.

**Observed:** Pale lemon-green paper is scattered with brighter squares, hollow squares, crosses and diagonal slashes. A very large cropped diagonal chevron occupies the right edge. The shapes remain flat and crisp behind black and gray text.

**Transfer:** Recreate the geometric vocabulary with original placement; a static arrangement is sufficient when motion is disabled. Keep the text the focal point.

**Build:** Place an SVG layer over the Acid feature stage. Draw solid and outlined squares around 28–56px, crosses made from intersecting bars, and narrow slashes rotated 45deg. Use acid-yellow-family fills, varying opacity, with a much larger thick chevron clipped at the right edge. Keep the center-left reading area less crowded and put the translucent Feature masthead above all marks.

### Editorial thumbnails

**Use:** Compact story stacks, shelves and release rows.

**Observed:** Small device photos, portraits, film stills and graphic illustrations retain their distinct palettes; 75px square and 202×134px landscape formats repeat. Some thumbnails have a very faint 1px gray edge and 3px corners.

**Transfer:** Choose a consistent crop per module, not a consistent filter across unrelated subjects. Make each crop legible at its smallest use.

### Vertical ranking watermark

**Only for:** category ranking rails

**Use:** Distinctive ranked-list backing in a 300px rail.

**Observed:** Huge compressed mint letters run vertically behind a five-item list at half opacity, making a pale mint graphic column while violet numbers and black titles remain in front.

**Transfer:** Use a short original label that describes the ordering, keeping decorative lettering separate from readable list text.

**Build:** Set the ranking-watermark recipe in an absolutely positioned vertical text layer at the rail's right edge, with color rgba(60,255,208,0.5). Place the ranked content above it at a higher stacking level; retain fine gray row separators.

### Icons

**Observed:** Small, simple solid SVG glyphs dominate: 12px gray comment bubbles, 16px link glyphs, 20–32px menu and utility symbols, 25px mint social glyphs inside outlined circles. A tiny triangle marks video playback.

**Transfer:** Use compact solid symbols with the surrounding text color. Keep utility icons modest beside the dense type; do not introduce a large colorful outline-icon feature system.

## Section recipes

How recurring sections are built.

### First screen: Editorial opening

**Observed:** A compact 120px white navigation area leads into a left-heavy editorial spread. The main 800px column contains a 680×544px photograph inset to leave room for the vertical brand lettering; the 380px update rail starts level with the photograph and is divided off by a dashed rule. Back to front: white paper, black vertical mark, documentary image, inset white Lead caption plate, then a 90px compressed headline and 24px serif summary. The caption begins around the image's lower edge, not above it. In the first 900px the navigation, large photograph, vertical identity, feed tabs and initial updates are visible; only the beginning of the caption reaches the fold, with the full title, summary and compact follow-up stories below. Actions remain small in the header and rail rather than forming a hero button pair.

**Transfer:** Lead with a compelling product-in-use scene and an original vertical name treatment. Put a strong editorial promise on the overlapping plate and useful updates or proof in the rail. For a category page, switch to the scoped violet banner with a 160px compressed white title, followed by a mint Follow action and a serif introduction on white. Do not preserve unused advertising clearance as part of the opening.

**Avoid:** Do not replace the spread with a centered headline over a gradient, a floating dashboard mockup, or two oversized CTA pills; do not force all lead copy above the fold.

**Text style:** `display` — manuka 900 · 90px/0.8

### Slash heading pair

**Observed:** A thin violet rule spans the module above a 24px bold section name, a violet slash, and a 24px lightweight gray explanation on the same baseline. Content begins 30px below; the explanation wraps naturally when long.

**Transfer:** Pair a short capability or proof theme with one useful sentence explaining why it matters.

**Text style:** `section-heading` — polySans 700 · 24px/1.1 · tracking 0.01em

### Curated feature cluster

**Observed:** The Slash heading pair introduces a two-column composition: one dominant image-led Story card on the left and three smaller stacked stories on the right. The feature uses a 20px serif summary; compact rows use small right-side thumbnails and faint dividers.

**Transfer:** Use one main use case and a few related examples; retain the unequal visual hierarchy instead of making all tiles identical.

### Ranked proof module

**Observed:** A simple section heading under a violet rule introduces Ranked rows. Lavender numerals punctuate an otherwise white module, with fine gray rules separating the items.

**Transfer:** Show ordered lessons, popular resources or a clear sequence of practical steps, with short titles and restrained supporting detail.

### Acid editorial statement

**Observed:** The Acid feature stage holds the Feature masthead, a central statement mixing kicker-title and kicker-support around a slash, a tiny author line, then a condensed series identity and Video action. It occupies the main editorial column while the update rail continues beside it.

**Transfer:** Use for the product's sharpest argument, a flagship explanation, or a demonstration. Preserve the geometric backdrop and bold-to-light sentence structure even when no video exists; use a relevant continuation action instead.

### Update river

**Observed:** Fine gray bottom rules separate white update items with 24px vertical padding. Each item can start with an author portrait and metadata, then a bold short lead-in, 16px serif text, underlined references, media, and comment/share details. Image-led Story cards interrupt the text rhythm. Category feature cards use a heavier 8px gray bottom separator.

**Transfer:** Use a release stream, implementation notes, customer evidence or product journal. Keep variations in item length and format instead of imposing equal card heights.

### Four-card shelf

**Observed:** A 24px heading and tiny underlined More link sit beneath a violet rule. Four Story cards use 202×134px images with 24px gutters and 8px image-to-title gaps; the shelf content is inset 50px relative to its heading. Major shelf groups are separated by 130px.

**Transfer:** Use as browsable secondary capabilities, guides or case studies after the main argument.

### Publishing colophon

**Observed:** The Closing ink band ends both page types with a white 300×68px identity at left and mint Social circles at right. Footer links form horizontal rows with vertical separators. The bottom strip pairs a smaller ownership mark and subdued legal text with a white-outlined site selector. A category river reaches this ending through a thin ruled pagination row; the default landing reaches it after browsing shelves.

**Transfer:** Close a new page with the product's own identity and useful human contact paths. Put any final conversion into a compact action before the band rather than changing the colophon into a giant campaign hero.

## Page flow

**Storyline:** lead story → curated explanations → ranked or timely proof → distinctive editorial feature → deeper browsing → publishing colophon

### A broad editorial landing page that gives one strong lead while exposing many paths into the product

1. **Hook** — Large documentary lead, vertical brand lettering, overlapping condensed headline and a live-feeling update rail.
2. **Capability chapters** — Slash heading pairs introduce a dominant story plus compact related examples.
3. **Prioritization** — Ranked modules offer a second way to choose what matters.
4. **Point of view** — Acid geometric feature turns a single argument into a strong visual pause.
5. **Depth** — Continuing update rail and four-card browsing shelves expose more material.
6. **Closing utility** — Dark identity-led colophon provides social, contact and policy paths.

**Transfer:** Translate editorial stories into use cases and concrete evidence. Choose the depth appropriate to the product without reproducing the original volume of updates.

### A category landing page that defines a focused area and supports ongoing exploration

1. **Orientation** — Violet banner with monumental white condensed title, then a mint action and serif introduction on paper.
2. **Featured proof** — A large 3:2 photo story sits beside three compact related stories.
3. **Ongoing detail** — A 700px river alternates quick notes, image features and reference links; a 300px rail carries rankings and a newsletter form.
4. **Continuation** — A small ruled pagination row leads into the shared dark colophon.

**Transfer:** Use for a product family, learning hub or ongoing release area. Keep the saturated banner and vertical mint ranking lettering scoped to this browsing-oriented type.

## Writing

Opinionated, informed and conversational without corporate polish. Headlines make specific observations, ask pointed questions, and permit skepticism; support copy gives the reader enough context to decide what matters.

**Do not copy:** Do not reuse the brand's name, logos, series identities, article claims, named people, proprietary artwork or quotations as new product content. Source examples illustrate voice, not reusable claims.

- **Addressing the reader:** Use you when it helps the reader make a choice; use we or our for a clearly accountable editorial opinion. Let the product name act as a concrete subject rather than repeatedly saying our platform.
- **Rhythm:** Short labels contrast with sentence-like headlines and one-sentence decks. Titles may run across several tight lines; conversational contractions, questions, and a well-placed aside keep the tone lively.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Lead headline | A concrete protagonist plus an active, consequential verb. | About 5–12 words | “The city that fought Flock” |
| Section title and explanation | Short theme followed by a plain-language reason to read. | 2–6 word title; one short support sentence | “Staff picks”<br>“Our favorite stories you don’t want to miss.” |
| Pointed feature title | A direct statement followed by a reader-facing question. | One or two short sentences | “Kevin Roose is AGI-pilled. Why aren’t you?” |
| Summary | Add an angle or reservation instead of repeating the headline. | One sentence | “Not that I believe for a second that Apple will actually make a 2-in-1 convertible.” |
| Action | Plain verb or browsing direction. | 1–3 words | “Subscribe”<br>“More Stories”<br>“Follow” |

**Words and phrasing to use:** what to expect; why; here’s; our favorite; taking stock; a concrete verb plus a named thing

**Avoid:** revolutionary solution; seamlessly empower; unlock your potential; best-in-class ecosystem; unqualified superlatives

**Rules:**

- Make each headline contain an actual observation, not an abstract category promise.
- Let the support line introduce a useful tension, limitation or implication.
- Use short, literal conversion labels; put persuasion in the surrounding editorial content.
- Keep author, date, format and attribution details separate from the persuasive headline.
- Use wit as a precise turn of phrase, not as a joke in every label.

## Do's and Don'ts

### Do

- Use the 90px compressed lead title against the 24px serif deck to create front-page contrast.
- Keep recurring 34px and 20px grotesk headlines at line-height 1.
- Use 11px uppercase metadata with 0.1em tracking, violet for authors and gray for time.
- Separate ordinary stories with 1px #e9e9e9 rules rather than card shadows.
- Retain the 800px main-column and 380px rail imbalance at desktop.
- Use 24px gutters in four-card shelves and 130px pauses between major groups.
- Include the acid geometric feature with its 5px black masthead rule.
- Finish with mint 39px social circles on the #131313 closing band.

### Don't

- Do not use the condensed display family for 16px reading paragraphs; serif copy is a defining countervoice.
- Do not make all controls 44px-high pills: keep the 22px compact action and 40px outlined action distinct.
- Do not add 12px or 24px rounded corners to every story image; thumbnail corners are only 3px.
- Do not tint all photography violet or mint; varied editorial image color belongs on the white page.
- Do not spread the pale lavender rank fill across entire cards; its job is a 50px number tile.
- Do not turn thin violet section rules into thick decorative gradients.
- Do not make lower shelves full-width equal-height feature panels; the measured shelf images are only 202×134px.
- Do not replace horizontal footer link rows with a giant centered CTA or a sprawling column sitemap.

## Motion and responsive

### Motion

**Observed:**

- Background-color transitions of 0.15s are declared on several controls and surfaces; some controls declare 0.1s and one declares a 0.15s transform transition.
- The acid geometric feature has a motion toggle and a declared 150s linear repeating animation. Its geometry changes position across the browsing sequence.
- The feed-tab group and the acid feature remain sticky while adjacent updates continue.

**Transfer:**

- Keep geometric motion behind the reading layer and provide a visible motion control; use the same composed static field when disabled.
- Use the declared short color changes for compact controls rather than introducing cinematic card entrances.

**Unknown:**

- Exact keyframe paths, trigger behavior and per-control easing assignments are not established.

### Responsive

**Observed:**

- Desktop composition is defined at 1440px width. Declared CSS breakpoints include 600px, 767px, 768px, 900px, 1024px, 1180px and 1300px.

**Transfer:**

- On narrow layouts, prioritize the lead image, condensed headline and serif summary before secondary updates. Stack the rail after the main argument rather than shrinking both into unreadable columns.
- Allow slash heading explanations and horizontal footer links to wrap; retain the contrast between tiny utility type and large compressed declarations.
- Collapse four-card shelves to fewer columns while preserving image ratios and the ruled heading treatment.

**Unknown:**

- Exact mobile font sizes, navigation transformations, column-collapse thresholds and sticky behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
