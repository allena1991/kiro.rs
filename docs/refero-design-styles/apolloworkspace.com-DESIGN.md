# Apollo Workspace — brick, linen, belonging

## Overview

A hospitable editorial style that pairs old-world refinement with everyday human usefulness. Linen and espresso grounds, restrained terracotta accents and occasional olive bands frame light serif headlines and lucid sans-serif copy. Warm documentary photography and textured watercolor scenes give low-density marketing pages a tangible sense of place, craft and belonging.

### Essentials

- The opening behaves like a hospitality title card, not a software pitch: a 900px-tall media field, espresso overlay at 55%, centered 600×114px wordmark, tiny uppercase promise above and two flanking context labels.
- Headlines have the lightness of printed literary titles: paradigm-pro at weight 300, 72px/1.05 or 56px/1.05 with 0.01em tracking, paired with Mona Sans paragraphs at 18px/1.625.
- Calls to action look like engraved rectangular signs: square corners, 1px outlines, 12px uppercase type with 0.14em tracking and 16px 32px padding; the fixed navigation uses a smaller 12px 24px version.
- Color is architectural rather than decorative: broad #e1dccf grounds and #2d0f06 media/footer fields dominate; olive #918037 occupies a discrete full-width chapter, while terracotta #e97451 stays in labels, small marks, bullets and conversion actions.
- Imagery supplies material proof: edge-to-edge atmospheric scenes alternate with unrounded portrait media; include a tactile illustrated scene and a tightly spaced image-and-caption gallery. Without suitable photography, use a warm editorial still life and a paper-textured illustration of the product in use.
- Small emblem repetitions unify otherwise spacious chapters: terracotta marks around 45×36px sit above 12px uppercase labels in an olive benefit band; a new product uses its own simple emblem in the same repeated rhythm.
- The ending is a substantial identity plate rather than a slim utility bar: deep espresso, 112px vertical padding, a 419×80px wordmark, 24px serif promise, three compact link columns and a faint rule above the legal row.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Antique olive | `#918037` | `--color-olive` | background | A full-width benefit chapter, with linen text and terracotta emblems. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Terracotta | `#e97451` | `--color-terracotta` | text, accent, action, border, link | Uppercase labels, emblems, bullets, header action border and occasional filled conversion action. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep espresso | `#2d0f06` | `--color-deep` | background, surface | Footer and media-section backing; also the source hue for photographic scrims. |
| Espresso rule | `#4c3229` | `--color-dark-rule` | border | Visible 15% linen rule over deep espresso. |
| Espresso | `#3c261c` | `--color-ink` | text, background | Main light-ground headings and feature text; solid dark information bands. |
| Linen on olive | `#dfdabf` | `--color-olive-copy` | text | Visible 75% linen over olive for benefit descriptions. |
| Translucent espresso | `#442f25` | `--color-nav-ground` | surface | Visible 95% espresso over parchment in the fixed navigation; media behind it changes its appearance slightly. |
| Parchment caption | `#7e6f64` | `--color-caption` | text | Visible 60% espresso over parchment for gallery captions. |
| Warm gray | `#6f675e` | `--color-muted` | text | Paragraphs on parchment. |
| Parchment rule | `#c8c3b4` | `--color-rule` | border | Visible 15% espresso separators over parchment; use rgba(60,38,28,0.15). |
| Soft linen | `#d0c9c1` | `--color-soft-linen` | text, link | Visible 80% linen over deep espresso for footer links; apply rgba(249,248,240,0.8). |
| Inset parchment | `#d9d3c6` | `--color-subtle-fill` | surface | Visible 5% espresso wash over parchment behind gallery media and inactive selector controls. |
| Parchment | `#e1dccf` | `--color-canvas` | background | Default light page ground. |
| Linen | `#f9f8f0` | `--color-linen` | text, border | Headlines, wordmarks and outlined actions over dark or olive fields. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| interactive product explorers | Cream plan backing | `#eae4cb` | `--color-plan-tint` | surface | Visible 40% cream #f7efc5 over parchment behind the interactive diagram. |

## Typography

- **paradigm-pro** — Headlines, editorial subheads, FAQ questions and footer promise. Light, high-contrast serif with generous, classical letter shapes. If unavailable, use **Cormorant Garamond**. Use weight 300 and retain the positive display tracking; check line breaks against the intended headline width. Font stack: "paradigm-pro", "Cormorant Garamond", Georgia, serif.
- **Mona Sans** — Paragraphs, uppercase labels, navigation and actions. Clean contemporary sans-serif; regular paragraph weight and moderately weighted small labels. Font stack: "Mona Sans", system-ui, -apple-system, "Segoe UI", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | paradigm-pro | 300 | 72px | 1.05 | 0.01em | Large benefit headlines, full-bleed scene headlines and major closing calls. |
| heading | paradigm-pro | 300 | 56px | 1.05 | 0.01em | Default section headings, often wrapping into two or three short lines. |
| footer-promise | paradigm-pro | 300 | 24px | 1.375 | normal | One-sentence editorial statement beneath the footer identity. |
| body | Mona Sans | 400 | 18px | 1.625 | normal | Editorial paragraphs, supporting explanations and FAQ answers. |
| feature-text | Mona Sans | 400 | 18px | 28px | normal | Bulleted benefits and short supporting lines. |
| benefit-copy | Mona Sans | 400 | 16px | 1.625 | normal | Centered short descriptions in the olive emblem band. |
| link | Mona Sans | 400 | 14px | 20px | normal | Compact footer link lists. |
| eyebrow | Mona Sans | 500 | 12px | 1.5 | 0.12em, uppercase | Section labels, gallery captions and short contextual metadata. |
| action | Mona Sans | 500 | 12px | 16px | 0.14em, uppercase | Buttons and header navigation links. |
| hero-promise | Mona Sans | 500 | 12px | 1.05 | 0.12em, uppercase | Small centered opening promise above the wordmark and compact emblem-card titles. |
| hero-context | Mona Sans | 500 | 12px | 1.625 | 0.12em, uppercase | Two-line context labels flanking the opening wordmark. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| offer-comparison pages | offer-number | paradigm-pro | 300 | 36px | 40px | normal | Small leading two-digit offer numbers. |
| offer-comparison pages | offer-title | paradigm-pro | 300 | 30px | 1.05 | 0.01em | Numbered offer-column titles. |
| detail and company-story pages | subheading | paradigm-pro | 300 | 24px | 1.05 | 0.01em | Unboxed benefit-grid titles. |
| FAQ sections | question | paradigm-pro | 300 | 24px | 32px | 0.0067em | Accordion questions and their plus markers. |

**Notes:**

- Keep the serif headings light and positively tracked; do not substitute tight bold display lettering.
- Paragraphs are deliberately more relaxed than headings: 18px/1.625 against a 1.05 heading line height. Restrict prose to roughly 470–660px widths.
- The opening's largest lettering is an identity graphic, not the 12px h1 promise. Make the new identity equally prominent without treating it as a standard paragraph font.
- Use 0.12em tracking for descriptive uppercase labels and 0.14em for actions; preserve this small but deliberate distinction.

## Layout

**Density:** Airy: large editorial chapter gaps surround readable paragraph blocks, while repeated captions and utility lists stay compact.

### Spacing

| Value | Use |
| --- | --- |
| 12px | Repeated list-item gaps, gallery column gutters and image-to-caption separation. |
| 16px | Eyebrow-to-heading gap and paired-action gap. |
| 24px | Paragraph separation, comparison-column top padding and FAQ trigger vertical padding. |
| 32px | Heading-to-paragraph separation and benefit-band column gaps. |
| 40px | Desktop container side padding and headline-object/action spacing in the opening. |
| 48px | Gallery row gap and question-list separation from its section title. |
| 64px | Benefit heading-to-grid gap and footer primary-column gap. |
| 80px | Editorial split-column gap, gallery lead-in and footer legal-row separation. |
| 112px | Footer top and bottom padding. |
| 128px | Default editorial section top and bottom padding. |
| 144px | Major benefit and material-story chapter padding. |

### Containers and grids

- **wide-container**: max width 1400px · side padding 40px. Centered main container; leaves 60px from viewport edge to content at 1440px. Used by feature splits, benefit bands and footer.
- **editorial-container**: max width 1200px · side padding 40px. Centered explanation and proof area; 1120px usable width.
- **editorial-split**: 2 columns · gap 80px. A roughly 472px text block beside a 560px image, vertically centered. Alternate which side holds media in later chapters.
- **benefit-band-grid**: 5 columns · gap 32px. Centered emblem-led items across the olive chapter; four-column variant belongs to company-story content.
- **material-gallery**: 3 columns · gap 12px. Full-width image grid with 48px row gaps; portrait images are 3:4 with captions beneath.
- **detail-grid** (only for detail and company-story pages): 2 columns · gap 40px. Unboxed detail benefits with 48px row gaps.
- **explorer-container** (only for interactive product explorers): max width 1300px · side padding 40px. 1220px-wide plan and availability area at desktop.
- **faq-container** (only for FAQ sections): max width 860px · side padding 40px. 780px-wide question column with left-aligned section title.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-images | 0px |
| interactive product explorers | explorer-panel | 12px |
| interactive product explorers | floor-selector | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Parchment canvas · level 0

**Use:** Default content sections.

**CSS:** `background: #e1dccf; color: #3c261c`

**Observed:** Flat warm paper color without card elevation.

**Transfer:** Let space and typography organize most content; do not put every paragraph in a card.

#### Deep identity field · level 0

**Use:** Media backing and the substantial footer.

**CSS:** `background: #2d0f06; color: #f9f8f0`

**Observed:** Solid reddish espresso, appreciably deeper than the text ink.

**Transfer:** Use as the visual anchor beneath the opening and at the ending.

#### Olive chapter · level 0

**Use:** Emblem-led benefit band.

**CSS:** `background: #918037; color: #f9f8f0; padding: 144px 0`

**Observed:** Full-width flat color, not a gradient; pale copy and small terracotta accents float without boxes.

**Transfer:** Give one cohesive set of product benefits its own colored chapter.

#### Media scrim · level 1

**Use:** Warm darkening over opening photography or video.

**CSS:** `background: rgba(45,15,6,0.55); position: absolute; inset: 0px`

**Observed:** Uniform dark espresso veil lets the image remain visible while supporting linen lettering.

**Transfer:** Apply above the media and below the title-card content.

#### Directional scene scrim · level 1

**Use:** Left-aligned editorial text over a full-bleed image.

**CSS:** `background: linear-gradient(to right, rgba(45,15,6,0.95) 0%, rgba(45,15,6,0.6) 50%, rgba(0,0,0,0) 100%)`

**Observed:** Leaves the right-hand illustration open while the left becomes a readable dark field.

**Transfer:** Choose the gradient direction to protect the text, not to tint every media panel uniformly.

#### Espresso information band · level 0

**Only for:** detail and company-story pages

**Use:** Centered offer statement, growth-benefit chapter or human contact split.

**CSS:** `background: #3c261c; color: #f9f8f0`

**Observed:** Lighter than the footer; used with 96px or 144px vertical padding and no raised cards.

**Transfer:** Use for a concise reassurance chapter or a human-led call to action.

#### Illustrated explorer panel · level 1

**Only for:** interactive product explorers

**Use:** Framing a detailed interactive plan.

**CSS:** `background: rgba(247,239,197,0.4); border-radius: 12px; box-shadow: 0px 0px 0px 1px rgba(60,38,28,0.1); overflow: hidden`

**Observed:** Cream backing and a faint single-pixel ring; no floating drop shadow.

**Transfer:** Keep the actual diagram dominant; controls and labels remain outside its frame.

## Components

### Fixed navigation

**Use:** Persistent page orientation and conversion access.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; z-index: 50; height: 74px; display: flex; align-items: center; justify-content: space-between; gap: 24px; padding: 16px 40px; background: rgba(60,38,28,0.95); backdrop-filter: blur(8px); color: #e97451`

**Text style:** `action` — Mona Sans 500 · 12px/16px · tracking 0.14em · uppercase

**Observed:** Three balanced zones: small uppercase links on the left, a small standalone emblem centered, and Header outline button aligned right. Links are separated by 32px; the emblem is about 35×28px.

**States:** Declared: hover links become #f9f8f0; focus-visible and active treatments are unknown.

**Transfer:** Use the new product's own simple mark at center rather than squeezing a full identity into the bar.

### Outline button

**Use:** Default primary action over media and olive bands; secondary action beside a filled conversion button.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; padding: 16px 32px; border: 1px solid #f9f8f0; border-radius: 0px; color: #f9f8f0; background: transparent; height: 50px`

**Text style:** `action` — Mona Sans 500 · 12px/16px · tracking 0.14em · uppercase

**Observed:** Text only, no arrow. Width follows the label; centered below the opening identity or aligned with editorial text.

**States:** Declared: hover background becomes a 10% current-color wash; focus-visible and active treatments are unknown.

### Header outline button

**Use:** Compact persistent conversion action in the navigation.

**CSS:** `padding: 12px 24px; height: 42px; border: 1px solid #e97451; border-radius: 0px; background: transparent; color: #e97451`

**Text style:** `action` — Mona Sans 500 · 12px/16px · tracking 0.14em · uppercase

**Observed:** Shares the navigation's terracotta text and is visually quieter than a filled action.

**States:** Declared: hover background becomes #e97451 and text becomes #3c261c; focus-visible and active treatments are unknown.

### Filled conversion button

**Use:** High-intent closing and contact actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; padding: 16px 32px; height: 50px; background: #e97451; color: #f9f8f0; border-radius: 0px`

**Text style:** `action` — Mona Sans 500 · 12px/16px · tracking 0.14em · uppercase

**Observed:** Used selectively beside an outline alternative or as the sole action in a centered closing block; the centered company-story version is 48px tall.

**States:** Declared: hover background becomes #71250e; focus-visible and active treatments are unknown.

### Emblem benefit

**Use:** Repeated, centered benefit descriptions within Olive chapter.

**CSS:** `display: flex; flex-direction: column; align-items: center; text-align: center; gap: 12px; color: rgba(249,248,240,0.75)`

**Text style:** `benefit-copy` — Mona Sans 400 · 16px/1.625

**Observed:** Small terracotta emblem first, uppercase eyebrow title next, then a short pale description. All items reuse the same emblem instead of unrelated pictograms.

**Transfer:** Repeat one proprietary or newly drawn abstract emblem consistently.

### Benefit bullet

**Use:** Compact lists beside tall editorial imagery.

**CSS:** `display: flex; gap: 12px; margin-bottom: 12px; color: #3c261c`

**Text style:** `feature-text` — Mona Sans 400 · 18px/28px

**Observed:** A 6px terracotta circle sits 8px down from the line's top, followed by readable text. No checkmark container or card background.

**Transfer:** Write one specific tangible benefit per line.

### Gallery figure

**Use:** Tactile material and craft proof.

**CSS:** `display: flex; flex-direction: column; gap: 12px; border-radius: 0px`

**Text style:** `eyebrow` — Mona Sans 500 · 12px/1.5 · tracking 0.12em · uppercase

**Observed:** Unrounded 3:4 image above a left-aligned uppercase caption with 16px side inset and 60% espresso text. Figures abut the page edges with 12px column gutters.

**Transfer:** Show detail, use, context and construction through a coherent photographic series.

### Footer link column

**Use:** Compact navigation within the deep identity ending.

**CSS:** `display: flex; flex-direction: column; gap: 12px; color: rgba(249,248,240,0.8)`

**Text style:** `link` — Mona Sans 400 · 14px/20px

**Observed:** Terracotta uppercase category label above the links, with a 20px gap before the list. Three columns sit to the right of a much wider identity block.

**States:** Declared: hover link text becomes #f9f8f0; focus-visible and active treatments are unknown.

### Numbered offer column

**Only for:** offer-comparison pages

**Use:** Simple editorial comparison without pricing-card chrome.

**CSS:** `display: flex; flex-direction: column; border-top: 1px solid rgba(60,38,28,0.15); padding-top: 24px`

**Text style:** `offer-title` — paradigm-pro 300 · 30px/1.05 · tracking 0.01em

**Observed:** Two-digit light serif number precedes the title, then a terracotta uppercase price line and body copy. Three equal columns use 56px gaps, not colored recommendation cards.

**Transfer:** Separate distinct offers using sequence numbers and factual descriptions.

### Question accordion

**Only for:** FAQ sections

**Use:** Long-form objection handling.

**CSS:** `border-bottom: 1px solid rgba(60,38,28,0.15); color: #3c261c`

**Text style:** `question` — paradigm-pro 300 · 24px/32px · tracking 0.0067em

**Observed:** A full-width trigger has 24px vertical padding and a 24px gap between question and right-aligned terracotta plus. The open answer is ordinary Body copy; the plus rotates into a cross. Top and bottom rules enclose the full stack.

**Transfer:** Let the question length determine row height rather than forcing all questions into one line.

## Imagery and graphics

### Warm human documentary

**Use:** Opening media, editorial portraits and human contact blocks.

**Observed:** People in warm brick-and-timber interiors or walking through an arched entrance; natural daylight, brown and olive clothing, rich wood, plants and imperfect real surfaces. Full-bleed landscape media establishes atmosphere; portrait images are tall, square-cornered and visually comparable in weight to the accompanying text block.

**Transfer:** Photograph people actually using the new product, with side light, natural materials and an unforced pose. If the product is digital, stage a real work scene around it rather than enlarging a floating interface mockup.

### Paper-textured illustrated world

**Use:** A signature tactile product scene, both in an editorial split and as a full-width visual pause.

**Observed:** Watercolor architecture rendered in sepia brick, washed green doors, pale stone and creamy sky. Visible paper weave, fine dark perspective lines, irregular pigment edges and small human figures soften the precision of the built scene.

**Transfer:** Illustrate the new product's world or use context in muted brown, green and cream. The minimum version is a restrained line-and-wash vignette with paper texture, not an empty media rectangle.

**Build:** Create an SVG with a parchment rect, fine espresso perspective outlines at low opacity, irregular translucent brown and olive wash polygons and a few human-scale silhouettes. Layer a very fine feTurbulence paper texture over the drawing at low opacity. Keep the upper third pale and let edges feather into the paper; use a full-bleed composition for a scenic pause or a tall rectangular inset for an editorial split.

### Material proof gallery

**Use:** A signature visual craft chapter beneath a centered serif statement.

**Observed:** A three-column series of portrait photographs: masonry under construction, communal seating, an arched kitchen doorway, a round brick opening at sunset, a carved stair detail and timber-framed exterior. Strong natural light and close detail give the images a physical, durable character; captions remain outside the image.

**Transfer:** Show the new product's equivalent craft evidence: raw materials, making, finished details and lived use. For a nonphysical service, photograph tools, people and artifacts of the work with the same portrait framing.

### Identity title graphic

**Use:** Opening title card and footer signature.

**Observed:** Elegant linen uppercase wordmark, 600×114px in the opening and 419×80px at the ending; thin, broad letterforms act as a graphic rather than a prose headline.

**Transfer:** Set the new product name in a finely drawn, broad uppercase serif identity. Keep its central visual weight and generous clear space even when the name is shorter.

**Build:** Use a custom SVG word treatment or live uppercase light serif lettering fitted into a 600×114px stage at desktop. Center it between two short uppercase labels, then repeat at roughly 70% of that width in the footer. Preserve the new name's natural proportions rather than stretching glyphs.

### Plan illustration

**Only for:** interactive product explorers

**Use:** Detailed product selection and availability.

**Observed:** An architectural plan fills a wide cream-backed panel; pale furnishing outlines, pastel planting and restrained colored regions provide detail while simple controls remain above it.

**Transfer:** Use a similarly restrained diagram or product configuration view. Keep internal UI colors confined to this explorer instead of carrying them into the marketing palette.

### Icons

**Observed:** Small filled SVG emblems in terracotta, usually around 45×36px above benefit labels and 35×28px in the header; the same lyre-like silhouette repeats. Text lists use 6px solid dots rather than icons.

**Transfer:** Use one simple custom emblem with a compact silhouette across navigation and benefit items; do not replace each repeated mark with a different generic outline icon.

## Section recipes

How recurring sections are built.

### First screen: Cinematic identity opening

**Observed:** A full-width 900px media scene sits behind Media scrim, with Fixed navigation above it. The title card is centered vertically and horizontally: Hero-promise above a broad 600×114px Identity title graphic; short uppercase context labels flank it, one right-aligned on the left and one left-aligned on the right. A 40px gap separates the promise from the identity row and another 40px leads to Outline button. The media, promise, both context labels, identity and action all fit inside the first 900px; the pale category strip begins below the fold. The identity graphic, not a giant multi-line sales headline, carries the visual mass.

**Transfer:** For a new marketing page, center the product's own identity over a warm, believable in-use scene. If video is unavailable, a carefully lit still image carries the same composition. Detailed product, location or company-story pages instead open with a left-aligned 72px serif statement low in a full-bleed media field; a small category or timing label and optional support line replace the centered identity row.

**Avoid:** Do not turn the default opening into a left-copy/right-dashboard layout, add several competing actions, or make the tiny promise the largest text.

**Text style:** `hero-promise` — Mona Sans 500 · 12px/1.05 · tracking 0.12em · uppercase

### Category marker strip

**Observed:** A 116px parchment band uses six equal columns across the wide container. Small uppercase labels have 40px breathing room above and below and fine espresso vertical dividers between items.

**Transfer:** Use short product categories, use modes or audience cues as a compact transition out of the media opening; these are labels rather than cards.

### Editorial image and argument

**Observed:** Parchment canvas with an Editorial split: a muted eyebrow, 56px Heading, 32px break before Body paragraphs, 24px paragraph gaps and a short darker concluding sentence. A tall watercolor or portrait image occupies the other column. The text is vertically centered against the image; sections use 128px or 144px bottom breathing room.

**Transfer:** Explain a specific customer frustration and the new product's alternative in humane prose. Alternate text and image sides between related chapters.

**Text style:** `heading` — paradigm-pro 300 · 56px/1.05 · tracking 0.01em

### Benefit and emblem chapter

**Observed:** Olive chapter contains a centered 72px Display statement constrained to about 884px, then a 64px break into Benefit-band-grid using Emblem benefit. An Outline button sits centered beneath the grid. The company-story variant uses four columns under a small centered label rather than a large heading.

**Transfer:** Give a coherent cluster of outcomes a single colored chapter and repeat the new emblem over the descriptions. The four-column variant is reserved for company-story content.

**Text style:** `display` — paradigm-pro 300 · 72px/1.05 · tracking 0.01em

### Immersive visual proof

**Observed:** A 900px-tall watercolor scene fills the width. A Directional scene scrim supports a left-aligned eyebrow, 72px headline, short 18px paragraphs and Outline button, while the right remains visibly illustrative. Other detail pages use the same large media scale as a completely text-free pause.

**Transfer:** Show the product's broader use environment and emotional payoff, not another feature-card grid. Choose between the text-overlay scene and an uninterrupted illustrated pause.

**Text style:** `display` — paradigm-pro 300 · 72px/1.05 · tracking 0.01em

### Material proof chapter

**Observed:** A centered 72px statement on Parchment canvas leads into Material-gallery after 80px. Gallery figure media remains 3:4, with 12px gutters and 48px row gaps. Uppercase captions describe qualities of the material or experience rather than narrating everything in the image. A small contextual external link closes the chapter.

**Transfer:** Use a concise material or quality promise followed by evidence in images. Require a tangible craft or process gallery somewhere in the page, without fixing its position or number of rows.

**Text style:** `display` — paradigm-pro 300 · 72px/1.05 · tracking 0.01em

### Deep identity ending

**Observed:** Deep identity field has 112px top and bottom padding inside Wide-container. Left: 419×80px Identity title graphic, 16px to terracotta metadata, 32px to Footer-promise, then a small seal. Right: three Footer link columns. A 1px 15%-linen rule is separated from the upper layout by 80px; the legal row sits 32px below it. This full ending is shared across all page types.

**Transfer:** Repeat the new identity, a one-sentence human benefit and practical links with the same unequal column emphasis. Use a small original seal or partner mark if there is a real one; preserve the open space rather than filling it with extra cards.

**Text style:** `footer-promise` — paradigm-pro 300 · 24px/1.375

### Unboxed detail grid

**Only for:** detail and company-story pages

**Observed:** A 56px Heading and brief support line introduce a two-column grid of 24px serif subheads and 18px body copy. The grid uses 40px horizontal and 48px vertical gaps. A dark company-story variant uses Espresso information band and linen text.

**Transfer:** Group four specific pieces of factual proof or capability without card backgrounds.

**Text style:** `heading` — paradigm-pro 300 · 56px/1.05 · tracking 0.01em

### Human contact split

**Only for:** offer and contact-oriented pages

**Observed:** A warm portrait fills one half of a roughly 706px-tall band; Espresso information band fills the other. A terracotta eyebrow, multi-line 56px Heading, named contact line and paired outline/filled actions make the block feel personal.

**Transfer:** Use a real accountable person, not a generic support illustration, when human guidance is part of the offer.

**Text style:** `heading` — paradigm-pro 300 · 56px/1.05 · tracking 0.01em

### Explorer and questions

**Only for:** offer-comparison pages

**Observed:** Numbered offer column introduces options; later a 56px heading and explanation lead into the wide Illustrated explorer panel, with compact selectors and legend above. The narrow FAQ area uses Question accordion beneath its own eyebrow and heading; one answer is expanded while the remaining questions form a ruled stack.

**Transfer:** Separate explaining options, inspecting a detailed diagram and answering objections. Keep the distinctive rounded treatment confined to the explorer panel.

**Text style:** `heading` — paradigm-pro 300 · 56px/1.05 · tracking 0.01em

### Centered closing invitation

**Only for:** detail and company-story pages

**Observed:** A centered 72px headline, brief factual support and 40px separation before the action sit within 128px vertical padding. The location-oriented variant uses Olive chapter with a filled action plus outline alternative and concise pricing/reassurance lines; the company-story variant is parchment with one filled action.

**Transfer:** Conclude with one clear commitment and one concrete reassurance appropriate to the new product.

**Text style:** `display` — paradigm-pro 300 · 72px/1.05 · tracking 0.01em

## Page flow

**Storyline:** Atmospheric promise → human problem and alternative → tangible benefit proof → immersive context → considered invitation → substantial identity ending.

### Broad marketing landing page

1. **Promise** — Centered identity title card over warm human video, followed by a slim category strip.
2. **Problem and alternative** — Serif editorial argument beside a watercolor scene.
3. **Capability proof** — Tall human portrait beside specific bullet benefits, then an olive emblem chapter.
4. **Experiential proof** — Full-bleed illustrated scene with editorial overlay, followed by a tactile material gallery.
5. **Identity ending** — Deep footer with large identity, human promise, seal and three link columns.

**Transfer:** Default storyline for a new product landing page: establish how it feels, then prove how it helps with concrete details and material evidence.

### Place or ecosystem detail page

1. **Contextual promise** — Long 72px serif statement low on a full-bleed documentary scene.
2. **Problem reframing** — Centered 56px heading and narrow editorial paragraph on parchment.
3. **Environmental proof** — Uninterrupted full-width photograph, then a four-item factual benefit grid.
4. **Closing call** — Olive reservation band with headline, practical pricing, reassurance and paired actions.
5. **Identity ending** — Shared deep footer.

**Transfer:** Use for an ecosystem, integration or destination story where context is part of the product's value.

### Offer-selection and conversion page

1. **Offer promise** — Media opening with large left-aligned serif proposition.
2. **Offer comparison** — Three numbered, ruled editorial columns with concise pricing and descriptions.
3. **Product inspection** — Illustrated visual pause followed by a detailed interactive plan and availability controls.
4. **Human reassurance** — Half-portrait contact block with two actions.
5. **Objection handling** — Narrow ruled FAQ stack.
6. **Identity ending** — Shared deep footer without an additional colored conversion band.

**Transfer:** Use the diagram-led middle for products that benefit from inspection or configuration, rather than forcing an architectural plan onto unrelated content.

### Company philosophy and audience-fit story

1. **Audience promise** — Left-aligned serif statement over documentary video with one support line.
2. **Problem recognition** — Editorial text beside a portrait, then a full-width watercolor pause.
3. **Offer clarification** — Centered espresso statement band and two-column benefit lists.
4. **Principles and growth** — Four-column olive emblem band followed by a dark unboxed capability grid.
5. **Closing call** — Parchment invitation with one filled action.
6. **Identity ending** — Shared deep footer.

**Transfer:** Explain the new organization's point of view through everyday frustrations, real people and practical outcomes rather than abstract manifesto language.

## Writing

Warm, assured and unpretentious. The tone is premium without aloofness: it ties beauty and thoughtful design to useful everyday outcomes, then makes practical commitments plainly.

**Do not copy:** Do not reuse Apollo or Building Culture names, logos, seals, artwork, location details, opening dates, prices, numerical claims or proprietary promises. Source phrases below illustrate voice and structure, not claims for a new product.

- **Addressing the reader:** Speak directly to 'you' and 'your'; use 'we' when explaining intentional choices or offering help. Name the product when making a concrete distinction rather than beginning every sentence with the brand.
- **Rhythm:** Short, balanced serif headlines contrast with conversational paragraphs. Use clipped sensory fragments to identify a problem, then a longer explanatory sentence; an occasional one-line conclusion makes the point stick.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A short human outcome expressed without technical qualification. | 5–8 words | “Where your best work happens” |
| Section heading | Link product conditions to a reader outcome, often in a balanced two-part phrase. | 7–12 words | “When Your Space Works, So Do You.”<br>“A place for focus, with room to breathe” |
| Problem recognition | Concrete sensory fragments make the problem recognizable before offering a solution. | A sequence of short fragments | “Stale coffee. Fluorescent lights. Blank walls. Strip-mall parking lots.” |
| Supporting line | A specific design intention followed by its human consequence. | One or two sentences | “Apollo is designed for deep work without distraction, with the freedom to step away so you can return with clarity.” |
| Primary action | Plain verb plus a personal object; no hype or exclamation. | 2–4 words | “Reserve Your Space”<br>“Schedule a Call” |
| Caption | A terse material or craft quality, ending in a period. | 2–4 words | “Real masonry.”<br>“Made to last.” |
| Reassurance | State the practical terms and lower a specific perceived risk. | One short sentence | “Reserve your space with a fully refundable deposit — no risk to get in line now.” |

**Words and phrasing to use:** thoughtfully designed; built for; room to; work better; natural light; craft; focus; humanized; fits; gathering

**Avoid:** disruptive; game-changing; 10x; synergy; hustle harder; exclusive luxury; revolutionary platform

**Rules:**

- Ground intangible outcomes in sensory or operational specifics.
- Use a contrast the reader recognizes, not a dramatic invented enemy.
- Pair important conversion requests with real practical terms or reassurance.
- Keep uppercase for labels and actions; sentence and title case belong to editorial headings.
- Let people and purposeful design carry the premium feeling rather than superlatives.

## Do's and Don'ts

### Do

- Keep major serif headings at weight 300 with 1.05 line height and 0.01em tracking.
- Reserve 128px or 144px vertical padding for major desktop chapters.
- Frame portrait gallery media at 3:4 with 12px column gaps and captions outside the image.
- Use 6px terracotta dots with 12px text gaps in practical benefit lists.
- Keep conversion actions rectangular, with 12px uppercase labels and 0.14em tracking.
- Give the footer 112px vertical padding and a broad identity block beside three smaller link columns.
- Use one repeated terracotta emblem to connect the navigation and olive benefit chapter.
- Protect light media-overlay text with a warm espresso scrim rather than a cold black tint.

### Don't

- Do not use pure white as the default canvas; parchment is #e1dccf.
- Do not turn terracotta into a full-page background; keep it to small text, marks and actions.
- Do not round ordinary images or conversion buttons; 12px panels and pill controls belong only to the explorer.
- Do not add floating drop shadows to editorial content; separation comes from spacing, rules and flat color bands.
- Do not replace the material gallery with a uniform grid of icon cards.
- Do not use bold condensed headlines or negative display tracking; the serif character is light and open.
- Do not make footer links uppercase like the header; they are 14px regular sentence-case links.
- Do not spread explorer status colors into the marketing palette.

## Motion and responsive

### Motion

**Observed:**

- Declared: header and footer link color transitions use .15s cubic-bezier(.4, 0, .2, 1).
- Declared: large conversion buttons use 0.3s cubic-bezier(0.22, 1, 0.36, 1).
- Declared: FAQ answer containers transition over 300ms and the plus marker rotates 45 degrees when open.
- Opening video provides environmental motion; no keyframe animation rules are declared.

**Transfer:**

- Keep action feedback restrained and color-led; the media itself supplies the cinematic character.
- Preserve the plus-to-cross accordion cue rather than introducing a large animated icon.

**Unknown:**

- Scroll-reveal choreography, video looping behavior and focus-visible styling are not established.

### Responsive

**Observed:**

- Declared width breakpoints: 640px, 768px, 1024px, 1280px and 1536px.
- Container classes use 24px side padding below the 40px desktop variant.
- Gallery classes switch from two columns to three at the medium breakpoint; the emblem grid moves from two columns at small widths to five at large widths.
- The opening identity has a declared width cap of 600px and a viewport-relative width limit; its flanking label row stacks at narrow widths.
- The desktop header links and right-hand action are hidden below the medium breakpoint.

**Transfer:**

- Stack context labels around the identity on narrow screens while retaining its title-card emphasis.
- Stack editorial text and portrait media; keep images rectangular and retain captions underneath.
- Allow the gallery to remain two columns on smaller screens and let the benefit grid breathe in two columns before expanding.

**Unknown:**

- Mobile menu interaction, exact small-screen type sizes and the explorer's small-screen pan/zoom behavior are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
