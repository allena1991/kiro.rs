# Mobbin — interfaces as bright objects

## Overview

A white, gallery-like marketing style with chunky grotesk headlines and small, matter-of-fact supporting text. Near-black, pale gray and restrained borders leave the color to vivid interface examples and floating app-like objects. It suits software and reference-rich products with a lot to demonstrate, combining low-density page composition with dense, authentic product imagery. Editorial content switches to a literary serif without abandoning the generous white space.

### Essentials

- Headlines behave like sentences punctuated by objects: 80px/1 grotesk at weight 652, -0.6px tracking, with 68px rounded-square icons inserted into the lines.
- The opening sells with words before the demonstration: a centered three-line promise, a 20px/26px gray support line, paired actions, and only the top of a broad product stage entering the first 900px.
- Actions are compact capsules rather than oversized banners: 44px high, 9999px radius, 16px side padding, 16px/22px weight 600 labels, with 8px between black primary and pale-gray secondary.
- Color belongs to the objects, not the page furniture: white and near-white dominate the body, near-black anchors the footer, and saturated hues stay inside small icons and product media. Blue and yellow editorial cards are a scoped exception.
- Product evidence is staged like a collection: 335px-wide pale-gray tiles with 24px corners and 20px gutters, containing cropped interface fragments, overlapping icons and subtle floating shadows. Use authored workflow fragments when the product has no finished media.
- The ending is a physical reveal: a white main sheet with 32px bottom corners gives way to a near-black footer, with a monumental, full-width, low-contrast wordmark cut off along its lower edge. Rebuild this with the new product's name as a bold word sculpture.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Main sheet, raised proof cards and inverse text. |
| Soft gray | `#f4f4f4` | `--color-soft-surface` | surface, background | Feature tiles, product-stage backing, FAQ entries and proof bands; rgba(64,64,64,0.06) over white. |
| Control gray | `#f0f0f0` | `--color-control` | surface, action | Secondary capsule fills; rgba(64,64,64,0.08) over white. |
| Faint edge | `#f0f0f0` | `--color-edge` | border | Card outlines and fine separators; rgba(64,64,64,0.08) over white. |
| Inverse muted text | `#adadad` | `--color-inverse-muted` | text | Footer column labels, legal links and social marks. |
| Reading gray | `#707070` | `--color-secondary` | text | Supporting paragraphs, captions and de-emphasized headline clauses. |
| Submerged lettering | `#222222` | `--color-wordmark` | accent | Visible low-contrast footer word sculpture; white at 0.06 alpha over near-black. |
| Near-black ink | `#141414` | `--color-ink` | text, action, background | Headlines, primary buttons and the inverse footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial related-content cards | Editorial blue | `#9abeff` | `--color-editorial-blue` | surface | Flat blue story cover, with dark text and no gradient. |
| editorial related-content cards | Editorial yellow | `#ffef79` | `--color-editorial-yellow` | surface | Flat yellow story cover paired with the blue variant. |

## Typography

- **saans** — Marketing headlines, paragraphs, actions and labels. Broad, friendly contemporary grotesk with substantial x-height and compact, rounded forms; unusually specific intermediate weights distinguish body and display. OpenType features: "calt" 0, "dlig", "ss07". If unavailable, use **Inter**. Use 440, 456, 600 and 652 variable weights; retain the tight display tracking. Font stack: "saans", "Inter", Arial, sans-serif.
- **Recital** (only for editorial articles) — Long-form article prose, section headings and related-story summaries. Expressive book serif with a fine contrast and tightly spaced display treatment. If unavailable, use **Libre Caslon Text**. Use regular and italic; preserve the narrow reading measure. Font stack: "Recital", "Libre Caslon Text", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | saans | 652 | 80px | 1 | -0.0075em | Centered landing-page promise, normally broken into three deliberate lines. |
| closing | saans | 652 | 56px | 1 | -0.0107em | Final two-line call and occasional broad proof headings. |
| heading | saans | 652 | 44px | 48px | -0.009em | Section leads, large quotations and prominent plan prices. |
| card-heading | saans | 652 | 24px | 1.25 | normal | Customer story titles, plan names and setup-step titles. |
| feature-label | saans | 600 | 20px | 1.3 | normal | Short feature-tile labels and capability titles. |
| lead | saans | 440 | 20px | 1.3 | normal | Hero support and larger section descriptions. |
| body | saans | 456 | 16px | 22px | 0.0125em | Paragraphs, ordinary links and footer navigation. |
| action | saans | 600 | 16px | 22px | 0.0125em | Button labels, navigation and FAQ question text. |
| caption | saans | 456 | 14px | 20px | 0.014em | Proof labels, attribution roles and footer labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial articles | article-heading | Recital | 400 | 56px | 1 | -0.0357em | Large serif section titles within the article. |
| pricing comparisons and category selectors | table-heading | saans | 652 | 32px | 36px | normal | Comparison category titles and large category-selection links. |
| editorial articles | article-body | Recital | 400 | 18px | 26px | -0.0167em, features "ss06" | Long-form prose and table content; inline links remain serif. |
| setup instructions and status badges | step-label | saans | 600 | 12px | 16px | 0.017em | Outlined step markers and compact status tags. |

**Notes:**

- Display tracking remains slightly negative while small sans text uses +0.2px; do not apply a single tracking token to the entire page.
- Use weight 652 for large sans headings, 600 for actions, 456 for ordinary text and the lighter 440 for prominent support.
- Gray clauses can be as large as the black headline: hierarchy also comes from color, not only size.
- Editorial opening titles retain the 80px grotesk treatment; the body and internal headings switch to serif. Editorial sans uses the separately named M Saans cuts with their corresponding visual weights.

## Layout

**Density:** Airy at section scale, compact inside product demonstrations and controls. Long stretches of white space frame tightly edited groups.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Between paired actions, icons and text, and footer links. |
| 12px | Between FAQ entries. |
| 16px | Badge-to-title and small support gaps; button side padding. |
| 20px | Grid gutters, page edge padding and section-heading support gaps. |
| 24px | Tile corners and common card padding. |
| 40px | Proof-card inset and copy-to-action grouping. |
| 64px | Hero text group to actions and setup-step separation. |
| 80px | Heading group to feature grid or major media. |
| 120px | Large text-to-media intervals and footer row separation. |
| 160px | Default spacious chapter padding and footer top padding. |
| 200px | Hero top padding, closing-call padding and editorial chapter separation. |

### Containers and grids

- **page grid**: max width 1728px · 16 columns · gap 20px · side padding 20px. Centered outer grid. At 1440px the principal content occupies twelve inner columns, about 1045px wide, leaving broad outer margins.
- **feature grid**: 3 columns · gap 20px. Three equal 335px-wide tiles at desktop; two rows for a broad capability collection.
- **reading block**: max width 620px. Centered support text for the closing call; shorter paragraphs are balanced rather than stretched.
- **testimonial block**: max width 690px. Large left-aligned quote, or a centered quote with attribution below.
- **faq split**: 2 columns · gap 20px. Heading in the smaller left portion, approximately 601px-wide accordion at right; the technical-page variant centers a 690px-wide stack.
- **article column** (only for editorial articles): max width 513px. Narrow central prose column; comparison tables expand to about 868px while staying centered.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsules | 9999px (pill) |
|  | feature and story cards | 24px |
|  | FAQ entries | 16px |
|  | media backing and main sheet | 32px |
|  | desktop media top corners | 20px |
| setup instructions | step badges | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating media | `0px 8px 24px 0px rgba(0,0,0,0.04)` | Product windows, small interface fragments and phone panels; not ordinary content cards. |

### Surfaces

#### Main sheet · level 0

**Use:** The continuous white marketing body.

**CSS:** `background: #ffffff; border-radius: 0px 0px 32px 32px; position: relative; overflow: clip; z-index: 2`

**Observed:** The body overlaps the inverse footer with rounded bottom corners.

**Transfer:** Treat the entire light page as one sheet, not a pile of individually rounded sections.

#### Soft backing · level 1

**Use:** Feature imagery and broad product stages.

**CSS:** `background: rgba(64,64,64,0.06); border-radius: 24px; overflow: hidden`

**Observed:** Small feature tiles use 24px corners; large introductory media backings use 32px. Broad proof bands use the same tint without rounded edges.

**Transfer:** Keep this backing neutral so the objects carry the color.

#### Raised white card · level 2

**Use:** Customer stories on the gray proof band.

**CSS:** `background: #ffffff; border-radius: 24px; box-shadow: none`

**Observed:** White-on-gray contrast replaces elevation shadows.

**Transfer:** Use a surface change, not a thick outline, to separate proof cards.

#### Glass navigation · level 3

**Use:** The persistent top navigation strip.

**CSS:** `background: rgba(255,255,255,0.9); backdrop-filter: blur(24px); border-bottom: 1px solid rgba(64,64,64,0.03)`

**Observed:** The white strip remains visually light over changing content.

**Transfer:** Keep blur confined to navigation rather than applying glass throughout the page.

#### Inverse footer · level 0

**Use:** The final navigation and word sculpture.

**CSS:** `background: #141414; color: #ffffff; padding: 160px 0px 40px`

**Observed:** A deep dark field under the main sheet, with restrained muted labels and much larger lettering below.

**Transfer:** Keep this as the strong tonal reversal at the end.

#### Hairline panel · level 1

**Only for:** technical demonstrations and pricing

**Use:** Prompt examples, workflow diagrams and secondary plan cards.

**CSS:** `background: #ffffff; border: 1px solid rgba(64,64,64,0.08); border-radius: 24px`

**Observed:** The edge is almost imperceptible; diagram media can occupy most of a panel.

**Transfer:** Preserve the delicate edge around dense information.

## Components

### Primary button

**Use:** Primary conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; padding: 0px 16px; border-radius: 9999px; background: #141414; color: #ffffff`

**Text style:** `action` — saans 600 · 16px/22px · tracking 0.0125em

**Observed:** Paired with a lighter secondary capsule; widths follow the label rather than filling the hero.

**States:** Declared: hover background-color hsl(0 0% 15%); focus-visible box-shadow resolves to zero transparent layers; active background-color hsl(0 0% 15%).

### Secondary button

**Use:** Alternative action beside a primary button or a standalone exploration link.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; padding: 0px 16px; border-radius: 9999px; background: rgba(64,64,64,0.08); color: #141414`

**Text style:** `action` — saans 600 · 16px/22px · tracking 0.0125em

**Observed:** A right arrow can follow the text with an 8px gap; the arrow is 20px and uses a 2px stroke.

**States:** Declared: hover background-color hsl(0 0% 25% / 12%); focus-visible box-shadow resolves to zero transparent layers; active background-color hsl(0 0% 25% / 12%).

### Navigation strip

**Use:** Persistent desktop site navigation.

**CSS:** `display: flex; flex-direction: column; justify-content: center; height: 83px; background: rgba(255,255,255,0.9); backdrop-filter: blur(24px); border-bottom: 1px solid rgba(64,64,64,0.03)`

**Text style:** `action` — saans 600 · 16px/22px · tracking 0.0125em

**Observed:** Compact symbol at left, a short run of product links, then social icons, a fine divider, login and a primary capsule at right. Contents align with the principal page width; action hit areas are 44px high.

**Transfer:** Keep the menu terse and the brand mark small.

### Feature tile

**Use:** Visual capability collection.

**CSS:** `display: flex; flex-direction: column; height: 330px; background: rgba(64,64,64,0.06); border-radius: 24px; overflow: hidden`

**Text style:** `feature-label` — saans 600 · 20px/1.3

**Observed:** Short centered title at the top with 24px top inset, then a large visual object below. Some objects are deliberately clipped by the lower or side edge.

**Transfer:** Use one concrete product object per tile, not a paragraph and a decorative stock icon.

### Story card

**Use:** Outcome-led social proof.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; height: 415px; padding: 40px; background: #ffffff; border-radius: 24px; overflow: hidden`

**Text style:** `card-heading` — saans 652 · 24px/1.25

**Observed:** Monochrome customer mark sits at the top; the outcome title sits near the bottom, leaving purposeful empty space between. Three cards align on a gray band.

**States:** Declared: hover background-color hsl(0 0% 25% / 6%); focus-visible uses the same background with zero transparent shadow layers.

### FAQ entry

**Use:** Objection handling on product and pricing pages.

**CSS:** `background: rgba(64,64,64,0.06); border-radius: 16px; min-height: 64px; padding: 20px 24px`

**Text style:** `action` — saans 600 · 16px/22px · tracking 0.0125em

**Observed:** Full-width question button, text left and 24px chevron right; 12px vertical gaps. The text is a bold child inside the question button, with room for an answer on expansion.

**Transfer:** Keep the FAQ a compact stack rather than a bordered spreadsheet.

### Footer columns

**Use:** Final site navigation.

**CSS:** `display: flex; flex-direction: column; gap: 8px; color: #ffffff`

**Text style:** `body` — saans 456 · 16px/22px · tracking 0.0125em

**Observed:** Three narrow link columns occupy the right half of the content grid, with a small wordmark at left. Gray 14px column labels sit 20px above links. A legal/social row follows after 120px.

**States:** Declared: hover opacity 0.8; focus-visible box-shadow resolves to zero transparent layers.

**Transfer:** Preserve the asymmetric left-brand/right-directory arrangement.

### Plan card

**Only for:** pricing and paid add-on offers

**Use:** Plan choice and compact final purchase offer.

**CSS:** `display: flex; flex-direction: column; padding: 24px 24px 32px; background: rgba(64,64,64,0.06); border-radius: 24px`

**Text style:** `card-heading` — saans 652 · 24px/1.25

**Observed:** Plan name and audience line precede a 44px price with small billing annotation, then full-width action, divider and checked feature list. The recommended plan has a gray fill and black action; adjacent plans are white with faint outlines and outlined actions. Desktop comparison cards are 335px by 611px.

**Transfer:** Use a single visual recommendation instead of accent-colored pricing tiers.

### Billing switch

**Only for:** pricing pages

**Use:** Choose billing cadence.

**CSS:** `display: flex; gap: 2px; height: 44px; padding: 4px; background: rgba(64,64,64,0.08); border-radius: 9999px`

**Text style:** `action` — saans 600 · 16px/22px · tracking 0.0125em

**Observed:** Selected option sits on a white 36px-high pill with a 0px 1px 2px rgba(0,0,0,0.04) shadow; the other option is gray. Labels have 12px side padding.

**Transfer:** Keep the selection small and centered above the cards.

### Step badge

**Only for:** setup instructions

**Use:** Number short onboarding instructions.

**CSS:** `display: inline-block; padding: 4px 8px; border: 1px solid #141414; border-radius: 8px; color: #141414`

**Text style:** `step-label` — saans 600 · 12px/16px · tracking 0.017em

**Observed:** Small outlined marker above a 24px title, followed by supporting copy and the relevant action or tool grid.

**Transfer:** Use a compact outlined badge rather than a large numbered circle.

### Editorial cover card

**Only for:** editorial related-content recommendations

**Use:** Text-led related stories.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; height: 402px; padding: 24px; background: #9abeff; border-radius: 0px`

**Text style:** `article-body` — Recital 400 · 18px/26px · tracking -0.0167em

**Observed:** 335px-wide flat covers use a small sans title at the top and a 24px/30px serif summary at the bottom. A yellow cover is paired with the blue; image-led stories use a separate thumbnail with a short title below.

**Transfer:** Keep these square-edged editorial objects distinct from rounded marketing tiles.

## Imagery and graphics

### Interface collection stage

**Use:** The main product demonstration and recurring capability media.

**Observed:** Authentic desktop windows and tall mobile screens sit on pale-gray backing. The introductory desktop window is about 1045px wide on a 1125px-wide stage, with 20px top corners and a very soft shadow. Smaller tiles combine full-color app icons, browser fragments, phones and isolated interface controls. Media can run beyond the frame, but remains crisp rather than stylized.

**Transfer:** Show the new product actually doing work. If no interface exists, author a small believable workflow with real labels and two or three useful states; do not substitute abstract blobs.

**Build:** Use a pale-gray rounded backing, layer a white product window inset 40px from the sides and top, round its top corners 20px and apply 0px 8px 24px rgba(0,0,0,0.04). For smaller tiles, center one or two narrow UI panels and clip their lower edges.

### Inline and floating objects

**Use:** Sentence punctuation in the opening and depth around promotional calls.

**Observed:** Saturated rounded-square app icons replace spaces within the large hero lines at 68px. Elsewhere 80px-class icons float around the edges or form two loose vertical garlands flanking a central text block; overlapping layers, partial occlusion and softened distant objects create depth without a colorful backdrop.

**Transfer:** Use owned product symbols, integration marks or miniature output cards. The default landing opening keeps the object-punctuated headline; peripheral constellations belong to specialized offers and closing calls.

**Build:** Make 68px square inline-block objects with roughly 30% corners and vertical-align: middle. For the peripheral variant, distribute approximately 80px tiles near both outer edges, keep the central text lane clear, overlap selected tiles by about half their width, and blur only rear layers by a few px. Use actual colored assets rather than adding colored page fills.

### Monumental footer word sculpture

**Use:** Signature final graphic across page types.

**Observed:** An extremely large near-black-on-black wordmark spans the entire viewport below the footer links. Individual letter shapes occupy a 312px-high band at desktop; the letter group is translated downward by 48%, so only its upper portion remains visible. The dark field is #141414 and lettering uses white at 0.06 alpha.

**Transfer:** Typeset the new brand name as one heavy grotesk word, or convert it to SVG outlines and fit it across the width. Preserve the low contrast and strong bottom clipping, even for a short name.

**Build:** Create a 352px-high relative stage with overflow: clip. Place a full-width SVG word inside a 312px-high absolute group at the bottom; translateY(48%). Fill letters with rgba(255,255,255,0.06) over #141414. Leave approximately 190px of breathing room above the visible letter tops.

### Workflow map

**Only for:** technical product use-case demonstrations

**Use:** Explain how inputs become outputs.

**Observed:** A large faintly outlined white panel contains tall mobile references, small text nodes, a style document and a final output. Thin pale curved connectors with small circular junctions weave left to right; some nodes fade softly at the lower edge. The visual occupies far more area than its short heading and description.

**Transfer:** Map a real transformation using a few legible inputs and one useful outcome; keep connections secondary to the objects.

**Build:** Lay out three or four columns of white cards inside a 24px rounded hairline panel. Add an absolutely positioned SVG with 1px rgba(64,64,64,0.08) Bézier paths and white circular junctions. Use narrow interface panels as endpoints; apply a white-to-transparent mask only to long overflow content.

### Editorial covers

**Only for:** editorial recommendations

**Use:** Related-story row after an article.

**Observed:** Blue and yellow flat text covers alternate with an image-led thumbnail. The covers have no rounded corners; small sans titles contrast with larger serif summaries.

**Transfer:** Design a simple two-typeface book-jacket composition rather than importing the glossy product-card treatment.

### Icons

**Observed:** Functional icons are monochrome: common chevrons and arrows use 24px or 20px boxes and 2px strokes; checks use 16px boxes and 2px square-ended strokes. Social marks are solid 20px silhouettes. Large colored app marks are imagery, not the functional icon system.

**Transfer:** Choose simple 2px outline arrows, checks and chevrons. Keep them ink-colored on light surfaces and white on inverse actions.

## Section recipes

How recurring sections are built.

### First screen: Object-punctuated opening

**Observed:** A slim Navigation strip spans the top of a white field. The main three-line headline is centered across roughly half the viewport width, with 80px/80px weight-652 type and a 68px colored object inside each line. The actual headline block is about 240px tall, surrounded by far more white space than text. A centered two-line Lead follows, then a pair of Primary button and Secondary button separated by 8px; the action group is set 64px below the text group. Back-to-front layers are white canvas, headline with inline objects, supporting text, capsules, then the Interface collection stage entering at the bottom. Within the first 900px all copy and actions are visible, together with only the upper portion of the broad product window; most of the demonstration falls below the fold.

**Transfer:** Write a short outcome promise that can be broken into balanced lines and insert owned miniature product objects as punctuation. With no finished imagery, make tiny concrete workflow or output cards for these slots and a simple authored product window below. Technical landings can use the same centered promise without inline objects; specialized offers use peripheral floating icons. Pricing opens with a short one-line promise, billing switch and plan cards; articles use a solitary centered grotesk title and a low author/share/deck row.

**Avoid:** Do not turn the first screen into a two-column dashboard hero, stretch the headline to full width, or put the complete demonstration above the actions.

**Text style:** `display` — saans 652 · 80px/1 · tracking -0.0075em

### Problem to collection

**Observed:** A left-aligned 44px Heading states the old difficulty and the new outcome. A following gray paragraph keeps the same headline scale. After a generous gap, a search-like label leads into a full-bleed rail of mixed desktop and mobile references on soft backings.

**Transfer:** Make the problem concrete, then let a horizontal collection demonstrate the variety of useful results.

**Text style:** `heading` — saans 652 · 44px/48px · tracking -0.009em

### Capability gallery

**Observed:** A centered two-line Heading precedes the Feature tile grid by 80px. Three equal columns with 20px gutters form a compact collection. The default labels live inside the tiles; specialized feature chapters place a 20px title and 16px paragraph below each visual instead.

**Transfer:** Group related capabilities by tangible outputs or tasks; vary the imagery within consistent tile dimensions.

**Text style:** `heading` — saans 652 · 44px/48px · tracking -0.009em

### Split capability demonstration

**Observed:** A left text block uses a two-line Heading and a Secondary button; a pale visual panel to the right contains a prompt and returned phone screens. Technical variants pair a fixed-looking category list in the left column with vertically stacked screen-pair panels at right.

**Transfer:** Pair a short promise with one visible interaction. Use category selectors only when the product genuinely has distinct collections.

### Proof band and large quotation

**Observed:** A full-width gray band holds a centered Heading, a Secondary button, and three Story cards after 80px. A large quotation follows with an 80px opening quote mark, 44px/48px text and small attribution. The specialized-offer variant is a 690px-wide left-aligned quote on white; the technical variant centers its quotation above a circular portrait.

**Transfer:** Use a real customer outcome, then a short human explanation of the result. Let typography carry proof rather than inventing decorative statistics.

**Text style:** `heading` — saans 652 · 44px/48px · tracking -0.009em

### Floating offer

**Observed:** A central compact heading pair uses gray for the reader's context and black for the offer. A short support paragraph and capsule action sit below. Loose vertical icon garlands flank the text without covering it.

**Transfer:** Use this for a deeper product tier, integration family or adjacent offer, replacing the symbols with relevant owned assets.

### FAQ split or centered stack

**Observed:** The ordinary product and pricing variant aligns a large heading at left and 601px-wide FAQ entries at right. The technical variant centers the heading and a 690px-wide stack below with an 80px gap. Entries are spaced by 12px.

**Transfer:** Choose the split variant for concise commercial questions and the centered stack for a longer technical explanation.

### Closing call and footer reveal

**Observed:** A 720px-tall white call centers a two-line Closing heading, 16px support text 20px below, and paired capsules another 40px below. The light Main sheet ends with 32px bottom corners over the Inverse footer. Footer columns and the legal row precede the Monumental footer word sculpture. A specialized paid offer substitutes a single centered Plan card; pricing ends its FAQ directly into the footer, and editorial ends with related covers.

**Transfer:** Retain a generous closing statement and the word sculpture, adapting the conversion unit to the buying model. Keep the final tonal reversal and clipped lettering even when earlier sections differ.

**Text style:** `closing` — saans 652 · 56px/1 · tracking -0.0107em

### Setup and prompt toolkit

**Only for:** technical product landing pages

**Observed:** A centered Heading introduces a three-column, two-row prompt grid of hairline panels, each about 335px by 184px, with copy above small utility actions. Later, a narrow setup column uses Step badges, 24px titles and a five-column grid of 128px by 100px tool tiles.

**Transfer:** Offer ready-to-use examples before explaining setup; keep instruction markers small and the product affordances tangible.

### Pricing decision and comparison

**Only for:** pricing pages

**Observed:** A centered 80px headline and Lead introduce a Billing switch above three Plan cards with 20px gaps. A monochrome logo rail follows. An adjacent-offer block pairs text with vertically moving logo cards fading into white at top and bottom. Comparison categories use 32px headings, a 405px feature-name column and four 160px plan columns, 64px rows and faint horizontal rules; category blocks are separated by 64px.

**Transfer:** Separate the fast buying decision from exhaustive comparison. Use neutral fill to recommend one plan and retain the broad whitespace around the add-on offer.

### Editorial reading sequence

**Only for:** editorial articles

**Observed:** A minimal 52px header sits over a widely isolated 80px grotesk title. Author portrait, italic metadata, share links and a serif deck form a low horizontal row. The body narrows to 513px, with 18px serif prose and 56px serif section headings separated by 200px chapter breaks. Comparison tables widen beyond the prose column. A small reading-progress marker and return-to-top link sit at opposite bottom corners. The ending is a practical next step, Related covers, then the dark footer.

**Transfer:** Use this as a distinct long-form mode, not as the ordinary marketing-page type system.

**Text style:** `article-heading` — Recital 400 · 56px/1 · tracking -0.0357em

## Page flow

**Storyline:** Promise → visible product evidence → concrete capabilities → human proof → deeper offer or setup → objection handling → conversion and monumental sign-off.

### Broad product marketing

1. **Promise** — Centered object-punctuated headline and paired capsules.
2. **Product demonstration** — Broad product window followed by a small trust label.
3. **Problem and capabilities** — Large problem/solution copy, reference rail, capability tiles and split interaction.
4. **Social proof** — Gray story-card band and a large quotation.
5. **Offer expansion** — Central offer framed by floating objects.
6. **Closing call** — Two-line statement, paired actions, rounded sheet and dark wordmark footer.

**Transfer:** Use the richest product demonstration as the spine, with objects and short copy explaining what the reader can accomplish.

### Specialized paid product or vertical offer

1. **Promise** — Centered display promise surrounded by floating app-like objects.
2. **Problem and demonstration** — Access problem in a short heading and paragraph, followed by a large product window.
3. **Capabilities** — Three visual capabilities, then a large left-aligned testimonial.
4. **Coverage proof** — Searchable-looking four-column directory of named items with small icons and badges.
5. **Objection handling** — Split FAQ.
6. **Purchase** — Centered final heading and one gray plan card, followed by the shared footer.

**Transfer:** Replace the directory with real supported systems, deliverables or use cases and end with one clear offer.

### Technical integration landing

1. **Promise** — Centered three-line headline, explanatory lead and action pair.
2. **Demonstration** — Wide dark interface video and compact trust row.
3. **Problem and solution** — Stacked bold claims and an interaction showing references becoming results.
4. **Capabilities** — Category selector and large paired-screen panels.
5. **Activation** — Copyable prompt grid, testimonial and workflow use-case maps.
6. **Setup** — Numbered instructions and tool tiles.
7. **Objections and closing call** — Centered FAQ, icon-framed final call and shared footer.

**Transfer:** Explain the integration through inputs and outputs before setup requirements, using the same neutral marketing shell.

### Pricing decision page

1. **Decision** — Short display promise, cadence switch and three plan cards.
2. **Social proof** — Large trust heading and monochrome logo rail.
3. **Offer expansion** — Split add-on pitch and fading logo-card columns.
4. **Detailed comparison** — Grouped comparison tables with repeated plan headers and fine rules.
5. **Objection handling** — Split FAQ and a help link.
6. **Sign-off** — Dark directory footer and clipped word sculpture without a repeated hero call.

**Transfer:** Keep quick plan selection above the dense feature comparison and clarify billing in small gray annotations.

### Editorial product comparison

1. **Orientation** — Isolated grotesk title with author, share links and serif deck.
2. **Evaluation** — Narrow serif argument, shared context, expanded comparison table and balanced strengths.
3. **Recommendation** — Audience-specific decision guidance, prose FAQ and practical invitation to compare.
4. **Continuation** — Blue and yellow related covers plus an image-led story.
5. **Sign-off** — Shared dark footer and clipped lettering.

**Transfer:** Make a candid argument with concrete criteria; keep commercial persuasion in the prose rather than inserting landing-page cards throughout.

## Writing

Direct, product-literate and mildly conversational. It earns confidence through specific work, access and outcomes rather than grand abstractions; editorial copy is willing to acknowledge a competitor's strengths.

**Do not copy:** Do not reuse Mobbin's name, logo, proprietary app artwork, customer marks, testimonial wording, library counts, pricing, dates or coverage claims. Replace all examples with truthful details for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your team, describe the product by name, and use we sparingly for origin stories and honest qualifications.
- **Rhythm:** Headlines favor short clauses and deliberate sentence breaks. Support text is one or two compact sentences; actions are two or three words. Long-form articles can be discursive, but keep concrete examples close to each assertion.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the audience and the useful result; use everyday verbs. | 6–14 words | “Where teams and agents find designs that work” |
| Problem and solution | Two blunt sentences contrast wasted effort with a simpler present. | 4–7 words per sentence | “Design research took hours. Now, it's one search.” |
| Supporting line | Define the category, then add a verifiable scale or freshness detail. | 15–30 words | “The design reference library for apps and sites. 621,500 shipped screens, new every week.” |
| Action | Verb plus immediate outcome or destination. | 2–3 words | “Join for free”<br>“See plans” |
| Technical reassurance | State time or effort, then remove one concrete obstacle. | 5–15 words | “One-click install for most major tools. No API key needed.” |
| Editorial qualification | Admit a limit without evasive marketing language. | short sentence or heading | “We'll be honest” |
| Closing call | Two short active sentences connect current proof to future work. | 6–10 words | “Find what works. Design what's next.” |

**Words and phrasing to use:** real; shipped; works; your team; search; see; build; now; one; updated weekly

**Avoid:** revolutionary; unleash; game-changing; supercharge; seamless ecosystem; limitless possibilities

**Rules:**

- Use actual tasks, blockers and outcomes instead of vague productivity promises.
- Put restrictions and billing qualifications immediately beside the relevant action or price.
- Let large counts be meaningful evidence embedded in a sentence, not an unrelated metric dashboard.
- Use contractions and occasional plainspoken admissions; avoid hype punctuation.
- Write customer story titles as how someone achieved an outcome.

## Do's and Don'ts

### Do

- Keep the main display at 80px/80px and weight 652 on desktop, with -0.6px tracking.
- Keep large product stages wider than their headline blocks: approximately 1045px of media versus a roughly 700px text block.
- Pair 44px capsules with 8px separation, giving the main action black fill.
- Use 20px gutters for three-column tile and story collections.
- Leave 80px between a section heading group and its large visual collection.
- Use 160px chapter padding and 200px closing-call padding to maintain the open page rhythm.
- Keep media shadows exceptionally soft at 0px 8px 24px with 0.04 black alpha.
- Carry the full-width clipped word sculpture through the ending of every page type.

### Don't

- Do not recolor the main controls to match each vivid product object; primary actions remain #141414.
- Do not apply the 24px card radius to editorial cover cards, which stay square-edged.
- Do not give ordinary story cards heavy drop shadows; white on the #f4f4f4 band provides their separation.
- Do not set every text role to 600: supporting text uses 440 or 456 and is visibly lighter.
- Do not turn the 14px captions into uppercase tracked eyebrows; the labels use ordinary case and 0.2px tracking.
- Do not render the final word sculpture as bright white text; its white fill is only 0.06 alpha on the dark footer.
- Do not use the editorial serif for ordinary landing-page headlines.
- Do not expand gray supporting paragraphs across the entire 1045px media width; use short centered reading measures.

## Motion and responsive

### Motion

**Observed:**

- Declared action color and opacity transitions use 0.15s cubic-bezier(0,0,.2,1); story cards use a 0.3s color transition.
- Declared hero support reveal is 0.5s ease with 0.18s delay. Product-window reveal is 0.8s ease with 0.7s delay; backing reveal is 0.8s ease with 1.35s delay.
- Declared hero object slot animation is 440ms ease-out. The top header uses a 0.3s height and border-color transition with cubic-bezier(0.33,1,0.68,1).
- FAQ trigger padding-bottom transitions over 0.3s cubic-bezier(.4,0,.2,1), and the billing thumb uses a 0.2s width/translate transition with the same curve.
- The footer letter controls are labelled as dropping app icons from letters; the word sculpture remains a low-contrast resting composition.

**Transfer:**

- Reveal the headline's object punctuation and supporting group as separate layers, then introduce the product window and backing.
- Keep functional hover changes small and neutral; use object movement rather than background spectacle for playful moments.
- Preserve the footer's large clipped resting shape even if the letter interaction is simplified.

**Unknown:**

- The complete choreography and physics of interactive footer objects are not specified.
- Scroll-dependent category pinning and all animation trigger thresholds are not established.

### Responsive

**Observed:**

- The capability grid declares one column by default, two from 768px and three from 1200px. Pricing declares one column by default, two from 720px and three from 1024px.
- The desktop navigation is enabled from 768px. A smaller headline class uses 40px before desktop overrides.
- Story cards use horizontal snap scrolling below the 980px layout change; their padding changes from 24px to 40px at 768px.
- The introductory media declares a 150%-wide treatment on narrow layouts and full width from 768px.

**Transfer:**

- Use the declared grid progression rather than shrinking three desktop tiles into unreadable columns.
- On narrow screens keep product media intentionally oversized and clipped, while the copy remains readable.
- Retain object punctuation at a scale appropriate to the 40px headline and keep peripheral objects away from text.
- Keep the footer word sculpture full-width and clipped rather than replacing it with an ordinary small logo.

**Unknown:**

- Complete mobile navigation, exact smaller headline line heights and mobile footer arrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
