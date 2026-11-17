# Turso — mint-lit machinery

## Overview

A dark developer-facing style with the feel of a working technical system rather than a glossy launch campaign. White grotesk headlines and electric mint actions sit inside blue-gray structural rails, with compact code windows, explanatory diagrams and flat illustrated infrastructure. It suits technical products that can explain their mechanism and prove their usefulness; generous section space surrounds relatively dense, practical cards.

### Essentials

- The promise reads like a two-part engineering thesis: Inter 60px/1, weight 800, -0.025em tracking, with the concluding phrase in #4ff8d2 and the rest white.
- The opening puts explanation beside execution: a 1fr 1.1fr split with a 56px gap and padding, a 448px support paragraph, and a dark working example occupying the right half. A bordered customer strip grounds the composition below.
- The page is a continuous technical chassis: a 1280px centered frame with 1px #283945 vertical rails and full-width horizontal section dividers; inset 16px-radius panels change the rhythm without changing the dark theme.
- Mint is a signal, not the canvas: #4ff8d2 appears in the 40px announcement band, concluding headline phrase, links, thin rules and 44px pill actions; almost all remaining area stays near-black. Fuchsia is confined to a contrasting participation panel.
- Cards carry small structural markings: 14px sequence numbers or short underlined titles, hairline mint rules, 18px/28px semibold claims, and 14px/24px muted explanations with actions aligned at the bottom.
- A diagrammatic motif makes the system tangible: repeated green modules, dashed boundaries and connector lines on dark slate. Include a mint-outlined repeated-object illustration somewhere on a new landing page, with a cropped ascending procession as the signature closing treatment; simple SVG modules are the fallback when no product artwork exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric mint | `#4ff8d2` | `--color-mint` | accent, action, link, border, background | Primary actions, emphasis, announcement strip and thin structural accents. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Subdued mint edge | `#3bb39a` | `--color-mint-edge` | border | Visible equivalent of mint at 70% over blue-black, around participation and plan panels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-text` | text, surface | Headlines, card titles and primary reading text; white backing is reserved for institutional logo tiles. |
| Footer silver | `#c5cace` | `--color-footer-text` | text | Footer navigation and social symbols. |
| Reading gray | `#b6b8ba` | `--color-body-bright` | text | White at 70% over the dark base for longer company prose and questions. |
| Secondary silver | `#9ea1a3` | `--color-caption` | text | White at 60% over the dark base for the trust-strip introduction. |
| Muted gray | `#86898c` | `--color-muted` | text | Supporting marketing prose, white at 50% over the dark base; actual shade shifts slightly with its backing. |
| Fine-print gray | `#626669` | `--color-fine-print` | text | White at 35% over the dark base for closing reassurance. |
| Diagram edge | `#3a4e5c` | `--color-diagram-edge` | border | Diagram boundaries and expanded accordion outlines. |
| Blue slate | `#293945` | `--color-slate` | surface, border | Form outlines and company information tiles. |
| Structural blue-gray | `#283945` | `--color-rule` | border | Outer rails, section boundaries and accordion outlines. |
| Code edge | `#23313c` | `--color-code-rule` | border | Visible equivalent of #283945 at 80% over blue-black for example windows. |
| Recessed edge | `#1d2a33` | `--color-soft-rule` | border | Visible equivalent of #283945 at 60% over blue-black; ordinary card and panel outlines. |
| Diagram slate | `#152029` | `--color-diagram-fill` | surface | Raised blocks within explanatory architecture diagrams. |
| Toolbar lift | `#12181d` | `--color-toolbar` | surface | White at 2% over blue-black, lifting the code toolbar and trust-strip label without making a bright card. |
| Technical charcoal | `#101317` | `--color-canvas` | background | Default marketing canvas. |
| Inset charcoal | `#0f1317` | `--color-panel` | surface | Large inset explanatory and conversion panels. |
| Blue-black | `#0d1318` | `--color-deep` | surface, background, text | Code window and form backgrounds; also the company-page canvas. Used at 50% for cards and 70% for the navigation backing. |
| Action ink | `#000000` | `--color-black` | text | Text on mint actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| paired participation panels | Participation fuchsia | `#d946ef` | `--color-fuchsia` | accent, action | Contrasting tag and action in the contribution-oriented half of the participation pair. |
| paired participation panels | Subdued fuchsia edge | `#9c37ae` | `--color-fuchsia-edge` | border | Visible equivalent of fuchsia at 70% over blue-black. |

## Typography

- **__Inter_f367f3** — All marketing headings, paragraphs, actions and navigation. Neutral contemporary grotesk; substantial, tightly tracked display weights and untracked utilitarian small text. If unavailable, use **Inter**. Font stack: "__Inter_f367f3", "Inter", Arial, sans-serif.
- **__GeistMono_46451f** — Example filenames and small technical sequence markings. Compact, even-width technical labeling that stays subordinate to the sans-serif message. If unavailable, use **Geist Mono**. Font stack: "__GeistMono_46451f", "Geist Mono", ui-monospace, SFMono-Regular, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | __Inter_f367f3 | 800 | 60px | 1 | -0.025em | Default marketing headline, including its mint concluding phrase. |
| heading | __Inter_f367f3 | 700 | 36px | 40px | -0.025em | Section-leading arguments and closing conversion headline. |
| card-title | __Inter_f367f3 | 600 | 18px | 28px | normal | Claims within cards; also accordion questions. |
| lead | __Inter_f367f3 | 400 | 18px | 32px | normal | Opening support copy and centered explanatory paragraphs. |
| reading-body | __Inter_f367f3 | 400 | 16px | 28px | normal | Long biographies and company descriptions; expanded FAQ answers also use this leading. |
| card-body | __Inter_f367f3 | 400 | 14px | 24px | normal | Dense explanations inside feature and proof cards. |
| navigation | __Inter_f367f3 | 600 | 14px | 20px | normal | Header links, mint arrow links and compact actions. |
| label | __Inter_f367f3 | 500 | 14px | 20px | normal | Announcement sentence, form labels and footer group labels. |
| caption | __Inter_f367f3 | 400 | 14px | 20px | normal | Footer links, trust-strip text and sequence numbers. |
| fine-print | __Inter_f367f3 | 400 | 12px | 16px | normal | Closing reassurance below the actions. |
| technical-label | __GeistMono_46451f | 400 | 12px | 16px | normal | Code-window tabs and small technical numbering. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company pages | company-display | __Inter_f367f3 | 600 | 60px | 1 | normal | Restrained centered company-page title. |
| paired participation panels | portal-title | __Inter_f367f3 | 700 | 36px | 40px | normal | Titles within the two participation panels. |
| company pages | company-heading | __Inter_f367f3 | 600 | 36px | 40px | normal | Company sections and biography names. |
| pricing pages | plan-title | __Inter_f367f3 | 700 | 24px | 32px | normal | Centered plan names. |
| paired participation panels | badge | __Inter_f367f3 | 500 | 12px | 16px | 0.025em, uppercase | Short category pills above participation-panel titles. |

**Notes:**

- The default display and section headings share -0.025em tracking; smaller text returns to normal tracking. Weight, rather than an unusual display font, provides the hierarchy.
- Do not turn technical filenames into the main type voice: mono is a small supporting register.
- Company pages use weight 600 and normal tracking instead of the heavier, tighter marketing hierarchy. The uppercase badge is not a universal section eyebrow.
- Short marketing body copy uses Inter 16px, weight 400, normal line-height and normal tracking. Primary pill text uses Inter 16px, weight 600, normal line-height and normal tracking; pricing action bars increase the weight to 700.

## Layout

**Density:** Airy section framing with compact, text-rich internal cards; dark space separates arguments while rules maintain continuity.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Label-to-input separation and tight supporting details. |
| 12px | Vertical pill padding and compact grid spacing. |
| 16px | Feature-card gaps, paragraph spacing and accordion gaps. |
| 20px | Narrow feature-card padding. |
| 24px | Heading-to-paragraph separation, pill horizontal padding and broad card gaps. |
| 28px | Proof-card and participation-cell padding. |
| 32px | Paragraph-to-action separation and four-column grid gaps. |
| 40px | Inset-panel outer vertical margin and two-column FAQ gap. |
| 48px | Heading group to card grid. |
| 56px | Default desktop section inner padding and split-stage gap. |
| 64px | Company panel padding and larger internal separation. |
| 96px | Centered secondary-page opening and closing-panel top padding. |

### Containers and grids

- **Structural frame**: max width 1280px · side padding 0px. Centered desktop frame; at 1440px the outer gutters are 80px. Carry both vertical rails through successive sections.
- **Section interior**: max width 1280px · side padding 56px. Standard desktop section content, leaving about 1166px of usable width within the rails.
- **Opening split**: 2 columns · gap 56px. Use 1fr 1.1fr tracks: message on the left, working example slightly wider on the right.
- **Centered argument**: max width 768px · side padding 24px. Centered section statement and explanatory paragraph.
- **Lead measure**: max width 448px. Left-aligned opening support text.
- **Narrow capabilities**: 5 columns · gap 16px. Tall, equal-width numbered feature cards.
- **Proof grid**: 3 columns · gap 24px. Equal-height case studies with bottom-aligned story links.
- **Benefits and footer**: 4 columns · gap 32px. Open numbered benefits or footer link groups.
- **Category grid** (only for directory and program pages): 2 columns · gap 16px. Broad icon-led directory cards.
- **Comparison matrix** (only for pricing pages): 5 columns · gap 12px. Equal plan columns beside a separate shared feature-label column.
- **Company proof grid** (only for company pages): 3 columns · gap 32px. Institutional logo tiles and individual backer tiles share a three-column rhythm.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Pill actions and badges | 9999px (pill) |
|  | Cards and inset sections | 16px |
|  | Code and accordion panels | 12px |
|  | Diagram blocks and inputs | 8px |
| company pages | Company framing | 24px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Working example | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Subtle depth beneath code examples; outlines do most of the work. |
| company pages | Institutional logo tile | `0px 4px 20px 0px rgba(0,0,0,0.3)` | White logo tiles in the otherwise dark proof wall. |

### Surfaces

#### Canvas · level 0

**Use:** Default page background.

**CSS:** `background: #101317; color: #ffffff`

**Observed:** Nearly uniform charcoal, crossed by the structural rails.

**Transfer:** Preserve a dark continuous field rather than alternating light and dark chapters.

#### Structural frame · level 0

**Use:** Section chassis.

**CSS:** `max-width: 1280px; margin: 0px auto; border-left: 1px solid #283945; border-right: 1px solid #283945`

**Observed:** Full-width horizontal dividers intersect the two continuous container edges.

**Transfer:** Align navigation, sections and footer to the same rails.

#### Inset panel · level 1

**Use:** Explanation, testimonial, conversion or FAQ chapter.

**CSS:** `background: #0f1317; border: 1px solid rgba(40,57,69,0.6); border-radius: 16px`

**Observed:** A near-black panel sits inside the structural frame with breathing room around all four edges.

**Transfer:** Use for a change in narrative pace, not for every paragraph.

#### Card · level 1

**Use:** Capabilities and case studies.

**CSS:** `background: rgba(13,19,24,0.5); border: 1px solid rgba(40,57,69,0.6); border-radius: 16px`

**Observed:** Low contrast, flat material with content defining the silhouette more than a shadow.

**Transfer:** Keep the card field close to the canvas.

#### Example toolbar · level 2

**Use:** Header strip above a working example.

**CSS:** `background: rgba(255,255,255,0.02); border-bottom: 1px solid rgba(40,57,69,0.6)`

**Observed:** Only a faint lift separates filenames from the example body.

**Transfer:** Use one active tab with a mint underline; keep inactive labels subdued.

#### Diagram block · level 1

**Use:** Nodes and control bars in explanatory diagrams.

**CSS:** `background: #152029; border: 1px solid #3a4e5c; border-radius: 8px`

**Observed:** Blue-slate modules remain darker than the mint marks that explain them.

**Transfer:** Diagram the actual product relationship with a small repeated shape vocabulary.

#### Company panel · level 1

**Only for:** company pages

**Use:** Wide culture and institutional proof framing.

**CSS:** `background: #0d1318; border: 1px solid #293945; border-radius: 24px; padding: 64px`

**Observed:** Larger corners and roomier padding than default marketing cards.

**Transfer:** Use the softer frame for human and organizational material.

#### White logo tile · level 2

**Only for:** company pages

**Use:** Institutional marks.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 40px 12px; box-shadow: 0px 4px 20px 0px rgba(0,0,0,0.3)`

**Observed:** Small centered logos retain their native colors inside wide white tiles.

**Transfer:** Reserve the bright surface for discrete proof marks, not text chapters.

#### Person tile · level 1

**Only for:** company pages

**Use:** Compact individual proof.

**CSS:** `background: #293945; border-radius: 8px; padding: 24px; display: flex; gap: 16px; align-items: center`

**Observed:** An 80px portrait sits beside name and role in the same grid as logo tiles.

**Transfer:** Use short identity text and authentic portraits.

## Components

### Navigation item

**Use:** Top-level product navigation.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; padding: 8px 12px; border-radius: 9999px; color: #ffffff`

**Text style:** `navigation` — __Inter_f367f3 600 · 14px/20px

**Observed:** Small downward chevrons accompany expandable categories. The shared header combines a 40px mint announcement band and an 84px navigation row inside the rails, with logo left and login plus primary action right. A translucent blue-black backing stays sticky above scrolling content.

**States:** Declared: hover color becomes #4ff8d2; focus-visible transparent solid 2px outline with 2px offset.

**Transfer:** Use concise navigation categories; preserve the thin announcement strip as a high-signal release or news message.

### Primary button

**Use:** Default conversion action.

**CSS:** `background: #4ff8d2; color: #000000; border-radius: 9999px; padding: 12px 24px; height: 44px; text-align: center; font-family: __Inter_f367f3, Inter, Arial, sans-serif; font-size: 16px; font-weight: 600; line-height: normal`

**Observed:** Solid mint with no border or trailing icon; width follows the label. Secondary choices are mint arrow links rather than competing filled buttons.

**States:** Declared: hover background becomes rgb(136 255 228/1); focus-visible 2px outline, 2px offset, color rgb(22, 163, 74).

### Arrow link

**Use:** Secondary actions and deeper reading.

**CSS:** `display: inline-flex; align-items: center; gap: 6px; color: #4ff8d2`

**Text style:** `navigation` — __Inter_f367f3 600 · 14px/20px

**Observed:** A text arrow follows a specific destination label; card links sit at the bottom of the content column.

**States:** Declared: hover color becomes rgb(136 255 228/1).

**Transfer:** Prefer a contextual verb and destination over a repeated generic label.

### Numbered feature card

**Use:** Parallel architectural benefits.

**CSS:** `display: flex; flex-direction: column; padding: 20px; background: rgba(13,19,24,0.5); border: 1px solid rgba(40,57,69,0.6); border-radius: 16px`

**Text style:** `card-title` — __Inter_f367f3 600 · 18px/28px

**Observed:** A muted two-digit number sits above a short mint rule, followed by the title, card-body explanation and Arrow link. Flexible paragraph space aligns links across unequal copy lengths. Broader proof variants use 28px padding and a short underlined customer name instead of a number.

**Transfer:** Keep the marking, claim, explanation and next action as four distinct reading levels.

### Working example

**Use:** Executable product proof in the opening and implementation sections.

**CSS:** `background: #0d1318; border: 1px solid rgba(40,57,69,0.8); border-radius: 12px; overflow: hidden; box-shadow: 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)`

**Text style:** `technical-label` — __GeistMono_46451f 400 · 12px/16px

**Observed:** A faint toolbar carries the active filename, whose tab has a mint bottom edge. The opening window is about 581px wide and 416px high. Short syntax-colored code and muted comments demonstrate a complete task rather than a large application dashboard.

**Transfer:** For a non-code product, put one compact, legible working workflow in this same restrained frame.

### Participation panel

**Use:** Two distinct ways to engage beyond purchase.

**CSS:** `border: 1px solid rgba(79,248,210,0.7); border-radius: 16px; overflow: hidden`

**Text style:** `portal-title` — __Inter_f367f3 700 · 36px/40px

**Observed:** Two equal panels separated by 24px: one mint, one fuchsia. Each has a padded introductory region with badge, large title, explanation and pill action, then a flush 2-by-2 grid of icon-led cells divided by hairlines. The fuchsia panel carries the matching fuchsia action.

**Transfer:** Use for two genuinely distinct engagement paths; retain the paired colors, internal grid and short practical cell copy.

### Footer link

**Use:** Utility and deep navigation.

**CSS:** `color: #c5cace`

**Text style:** `caption` — __Inter_f367f3 400 · 14px/20px

**Observed:** Plain links stack in four columns with mint group headings; one group continues across two columns. Social symbols occupy the lower-right baseline, opposite a compact brand symbol and copyright.

**States:** Declared: hover color becomes rgb(255 255 255/1).

### Category badge

**Only for:** paired participation panels

**Use:** Identify a participation path.

**CSS:** `display: inline-block; background: #d946ef; color: #ffffff; border-radius: 9999px; padding: 4px 12px`

**Text style:** `badge` — __Inter_f367f3 500 · 12px/16px · tracking 0.025em · uppercase

**Observed:** The contrasting panel uses a mint badge with dark text; each badge sits above a substantially larger panel title.

**Transfer:** Limit badges to the paired-path treatment instead of peppering every section with labels.

### Application input

**Only for:** application forms

**Use:** Short lead or application forms.

**CSS:** `background: #0d1318; color: #ffffff; border: 1px solid #293945; border-radius: 8px; padding: 12px 16px; height: 46px; width: 100%`

**Text style:** `label` — __Inter_f367f3 500 · 14px/20px

**Observed:** Labels sit above the field with mint required markers. One full-width field precedes two half-width fields; a larger 52px mint submit pill is centered below.

**Transfer:** Ask for only enough information to start the relationship; retain the dark field backing.

### FAQ item

**Only for:** FAQ sections

**Use:** Objection handling.

**CSS:** `border: 1px solid #283945; border-radius: 12px; padding: 24px`

**Text style:** `card-title` — __Inter_f367f3 600 · 18px/28px

**Observed:** Full-width question button with plus at the right; expanded state shows minus, a brighter #3a4e5c outline, short mint rule and a reading-body answer below. Items stack 16px apart in the wider right column.

**Transfer:** Keep answers concise and operational; use the left column for the section title and conversion choices.

### Plan column

**Only for:** pricing pages

**Use:** Aligned feature comparison.

**CSS:** `display: flex; flex-direction: column; background: rgba(13,19,24,0.5); border: 1px solid rgba(79,248,210,0.7); border-radius: 12px`

**Text style:** `plan-title` — __Inter_f367f3 700 · 24px/32px

**Observed:** Five equally outlined plan columns share one feature-label rail. Each begins with a centered 128px header containing name, mint price and small savings line. Thin translucent white rules separate aligned rows. All plans use the same accent treatment rather than one enlarged recommendation.

**Transfer:** Keep features aligned across columns; show limits and overage units explicitly.

### Plan action

**Only for:** pricing pages

**Use:** Conversion at the foot of each comparison column.

**CSS:** `display: block; background: #4ff8d2; color: #000000; border-radius: 0px 0px 11px 11px; padding: 14px 0px; height: 48px; text-align: center; margin-top: auto; font-size: 16px; font-weight: 700; line-height: normal`

**Observed:** Flush, full-width mint bar closes every column; it is not the floating pill used elsewhere.

**States:** Declared: hover background becomes rgb(136 255 228/1).

## Imagery and graphics

### Explanatory machinery

**Use:** Product mechanism and deployment explanations.

**Observed:** Dark-backed architecture diagrams compare one shared block with a fleet of small isolated blocks. A later illustration repeats green, softly tapered database modules inside slate tiles, enclosed by dashed boundaries and linked to a single local module. Mint outlines and restrained green fills make the mechanism readable without photorealism.

**Transfer:** Choose one recognizable unit for the new product, repeat it to explain the system, and show boundaries and relationships. The minimum equivalent is a clear SVG diagram rather than an unrelated stock illustration.

**Build:** Use an SVG viewBox about 896 by 396. Draw one isolated rounded slate tile at left and a 4-by-2 group at right; connect them with a 1px dashed blue-gray line. Inside each tile, repeat a tapered capsule or product-specific unit made from three stacked elliptical bands, green fills at low-to-medium opacity and a 2px mint outer stroke. Add a dashed rounded enclosure around the group and tiny neutral labels. Keep the scene flat, dark and diagrammatic.

### Ascending module procession

**Use:** Signature visual at the base of a large conversion panel.

**Observed:** A broad illustration about 1024px by 266px is clipped by the lower panel edge. Rows of green tapered modules follow rising slate tracks from lower left to upper right; the rear row carries a bright mint contour. The upper portion of the panel remains empty enough for the centered message and actions.

**Transfer:** Include this repeated-object, rising-edge motif on a new landing page using the new product's meaningful unit. A simplified procession of outlined geometric modules is sufficient; it must still feel like a scalable system rather than a decorative wave.

**Build:** Create an SVG with three dark slate ribbons slanting upward to the right. Place repeated tapered rounded modules at equal intervals along each ribbon, using translucent mint bands to suggest layered volume. Trace only the back row and its connecting top edge with a vivid 3px mint stroke; keep front rows darker. Position the SVG bottom-center inside an overflow-hidden 16px-radius Inset panel, and let the lower and side edges cut off modules.

### Customer marks

**Use:** Trust strip directly beneath the opening demonstration.

**Observed:** Small mostly white marks sit on the same dark surface in a single bordered strip. A muted text compartment at left introduces the proof; logos are evenly spaced rather than placed in separate bright cards.

**Transfer:** Use authentic customer or integration marks at comparable optical size; if none exist, use verified integration names in the same compact strip.

### Human proof

**Only for:** company pages

**Use:** Biographies and individual backers.

**Observed:** Natural color headshots have rounded-square masks. Large biography portraits overlap the top mint outline of the card; smaller portraits sit inside slate information tiles. Photography stays modest in area compared with text.

**Transfer:** Use direct, unembellished portraits with no dramatic grading. Place a rounded headshot across the upper card border for primary biographies.

### Institutional marks

**Only for:** company pages

**Use:** Organizational proof wall.

**Observed:** Native-color logos are centered on wide white rounded rectangles; these share grid dimensions with darker portrait tiles.

**Transfer:** Preserve native mark colors and ample white backing, maintaining equal tile heights.

### Icons

**Observed:** Small line icons use rounded caps and mostly 1.5px strokes at 20px or 24px. Mint marks identify categories; fuchsia marks belong to the contrasting participation panel. Navigation chevrons are 14px. Social symbols use compact filled silhouettes at about 24px.

**Transfer:** Choose a single restrained outline family for explanatory icons and use official filled social marks only for destinations. Keep icons subordinate to headings.

## Section recipes

How recurring sections are built.

### First screen: Explanation beside execution

**Observed:** The first 900px contains the entire opening and the start of the next panel. Back to front: charcoal canvas, the 1280px rail frame, a left message column and slightly wider right Working example, then a full-width trust strip below. The sticky 125px header includes the mint announcement band. Inside the opening, 56px padding and gap frame a 60px/1 heavy headline that occupies roughly the left half: its white premise wraps to two lines and its mint conclusion makes a third. The 18px/32px support paragraph is limited to 448px, with a Primary button 32px below. The example is about 581px by 416px and vertically centered beside the message. The trust strip spans about 1166px, is 94px high, and has a left text cell plus seven marks. The next explanatory chapter begins just below the opening's 679px section height.

**Transfer:** Make the strongest product promise and its proof coexist above the fold. Use an actual compact workflow in the right panel; a carefully composed static example is the fallback. Program and pricing pages instead center the same two-tone display, support paragraph and action with about 96px top and bottom breathing room. Company pages use a compact outlined title band and the lighter company-display recipe.

**Avoid:** Do not replace the working example with an enormous atmospheric image or center the default opening into an empty headline-only splash. Do not apply mint to every line of the headline.

**Text style:** `display` — __Inter_f367f3 800 · 60px/1 · tracking -0.025em

### Framed argument and diagram

**Observed:** An Inset panel holds a centered Heading and Body explanation within a 768px measure. A highlighted sentence fragment leads into a wide two-part comparison diagram below; the diagram uses Diagram blocks and dashed group boundaries.

**Transfer:** Explain why the existing model is insufficient, then make the alternative visually concrete. Keep prose subordinate to the comparison.

### Marked capability grid

**Observed:** A left-aligned Heading precedes five Numbered feature cards by 48px; equal-height cards use 16px gaps. Broader variants use two or three columns, icon or name markings, and the same low-contrast Card surface.

**Transfer:** Choose the grid count for the content. Preserve a visible marking, concise claim, practical explanation and bottom action rather than forcing five topics.

### Split proof panel

**Observed:** An Inset panel pairs a left Heading, Body and Primary button with a right quote card or stacked proof rows. Testimonial text uses Lead; attribution stays small. Enterprise proof rows add mint line accents and restrained icons rather than giant statistics.

**Transfer:** Put a mechanism or promise beside external confirmation or a short list of verifiable assurances.

### Case-study argument

**Observed:** A centered Heading leads into three equal Card surfaces with 24px gaps. Each begins with an underlined identity, a semibold outcome-led claim, muted Card body and Arrow link. A centered Primary button follows the grid.

**Transfer:** State the measurable or concrete outcome before describing the customer. Do not invent a numerical stat wall when a compact narrative is more credible.

### Paired participation paths

**Observed:** A centered Heading and short Body introduce two Participation panels. Category badges and Portal titles provide the strongest color departure: mint on one side, fuchsia on the other. Flush internal cell grids give the cards a technical directory structure.

**Transfer:** Use the paired device for two routes into an ecosystem, learning program or contribution model; these need not be community and source-code topics.

### Illustrated closing call

**Observed:** A large Inset panel centers a Heading, a compact Body paragraph, Primary button and Arrow link, followed by Fine print. Around 320px of lower breathing room accommodates the Ascending module procession, clipped at the base. The section is followed directly by the utility footer.

**Transfer:** Close with a durability or growth promise backed by a low-friction next step. Preserve the rising repeated-object artwork even when the objects change.

### Utility ending

**Observed:** Every page ends with the same approximately 535px footer inside the structural rails. Four link columns use a 32px gap, mint labels and Footer links. Below them, the small brand/copyright sits left while a compact row of social symbols sits right. The background stays dark and the top section boundary remains visible.

**Transfer:** Close every page with a calm information directory, even when the preceding block is a form, FAQ or institutional wall.

### Program application

**Only for:** program and application pages

**Observed:** A two-column Inset panel pairs a Heading and Body at left with Application inputs at right. The right track is slightly wider; a full-width field leads two half-width fields and a centered 52px submit pill.

**Transfer:** End a program narrative with a compact application rather than a second marketing hero.

### Comparison and reassurance

**Only for:** pricing pages

**Observed:** A centered Heading and compact monthly/yearly pill switch precede five Plan columns. Shared left-side feature labels align to the row rules. Plan actions close the columns; a short overage note and a centered usage explanation follow. A large Inset panel then splits a narrow FAQ title/action column from wider FAQ items.

**Transfer:** Keep the matrix factual, explain usage in prose, and use the FAQ as the final decision-support block before the footer.

### Human and institutional proof

**Only for:** company pages

**Observed:** A compact framed title leads to a 24px-radius Company panel with a two-column list of icon-led principles. Two mint-outlined biographies use overlapping portraits, company-heading names, uppercase roles and reading-body prose. A three-column wall combines White logo tiles and Person tiles before the footer.

**Transfer:** Describe the people and operating character behind the product; use authentic institutional and human proof, not a sales conversion panel.

## Page flow

**Storyline:** Promise → explain the mechanism → give concrete routes or proof → reduce commitment friction → utility ending; the emphasis changes with the reader's task.

### Introduce a technical product and earn a trial

1. **Promise and demonstration** — Split headline and working example, grounded by a customer strip.
2. **Reframing** — Centered argument and old-model/new-model diagram.
3. **Capability chapters** — Numbered benefits followed by a short implementation example.
4. **Practical proof** — Mechanism plus quote, customer outcome cards and enterprise assurances.
5. **Adoption routes** — Two entry-point cards and a system diagram.
6. **Participation** — Paired colored panels with practical engagement cells.
7. **Closing call** — Centered conversion panel with a rising repeated-module illustration.
8. **Utility ending** — Four-column shared footer and social baseline.

**Transfer:** Adapt the narrative to the product's mechanism; preserve the working proof, visible technical structure and illustrated closing device without requiring every chapter.

### Help an ecosystem audience find its route and apply

1. **Program promise** — Centered two-tone display, explanatory lead and paired primary/text actions.
2. **Audience routing** — Two-by-two icon-led category cards.
3. **Shared value** — Four open, numbered columns with top hairlines.
4. **Conversion** — Split application panel with compact fields.
5. **Utility ending** — Shared footer immediately after the form.

**Transfer:** Organize any multi-audience program by reader intent, then explain common benefits and present one short form.

### Establish organizational credibility

1. **Orientation** — Compact outlined title band.
2. **Character** — Two-column icon-led statements inside a large rounded frame.
3. **Human proof** — Two extended biography cards with overlapping portraits.
4. **Institutional proof** — White logo tiles and slate individual tiles in one three-column wall.
5. **Utility ending** — Shared footer; no separate sales close.

**Transfer:** Use the lighter type hierarchy and human proof treatment for organizational storytelling, not the ordinary product opening.

### Make purchase economics comprehensible

1. **Value promise** — Centered two-tone display and low-friction action.
2. **Comparison** — Billing-frequency switch and five-column aligned matrix.
3. **Cost explanation** — Small overage note followed by a centered usage paragraph.
4. **Objection handling** — Split FAQ panel with conversion choices beside accordion questions.
5. **Utility ending** — Shared footer directly after the FAQ.

**Transfer:** Use a consistent matrix, explain what determines cost, and resolve likely billing concerns before the utility ending.

## Writing

Confident, practical and technically literate. Claims are explained as consequences of the underlying design rather than celebrated as marketing superlatives.

**Do not copy:** Do not reuse the Turso name, mascot, logos, customer marks, named people, quotes, proprietary terminology, adoption figures, prices, free-tier limits or compliance claims. Examples below illustrate voice only; replace them with truthful content for the new product.

- **Addressing the reader:** Use you and your when describing the reader's work, direct verbs for actions, and an occasional we for an attributed company explanation. The product is usually described plainly in the third person.
- **Rhythm:** Headlines often use two linked clauses or a short repeated construction. Support moves from terse declarations to a practical explanation; occasional fragments supply emphasis. Actions are short and specific.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A broad scale promise followed by a compact organizing principle. | 5–9 words | “Millions of Databases. One Architecture.” |
| Section argument | Reframe a familiar limitation or connect a mechanism to an outcome. | 7–17 words | “Five properties of the architecture, not features layered on top.”<br>“The pattern is the same. The use cases are everywhere.” |
| Supporting line | Start with compatibility or mechanism, then describe the reader's practical next step. | 15–35 words | “SQLite-compatible. SDKs in TypeScript, Python, Rust, and Go. Self-serve from signup to production.” |
| Primary action | Direct verb plus a destination or reduced-friction qualifier. | 2–5 words | “Start for free now”<br>“Become a partner” |
| Card explanation | Concrete operation first, then a brief emphatic clarification. | 20–40 words | “Spin up thousands or millions of isolated databases programmatically, each with its own boundary. Not a workaround. The architecture.” |
| FAQ question | Ask the operational question a prospective buyer would actually ask. | 6–16 words | “When will I be billed for my plan?” |

**Words and phrasing to use:** built on; by design; from … to …; the same; start free; run anywhere; your; build; how … works

**Avoid:** revolutionary; magical; game-changing; unparalleled; unlock your potential; hype-heavy exclamations

**Rules:**

- Make scale credible by naming the mechanism that enables it.
- Use repeated syntax to connect several benefits without a long slogan.
- Put a concrete outcome before a customer-story explanation.
- Name the destination in secondary actions rather than repeating Learn more everywhere.
- Explain pricing terms and limits in ordinary operational language.

## Do's and Don'ts

### Do

- Keep the default display at 60px/1, weight 800, with -0.025em tracking.
- Carry the 1280px frame and 1px blue-gray rails through the footer.
- Use 56px desktop section padding and 48px heading-to-grid separation.
- Keep dense card explanations at 14px/24px and titles at 18px/28px.
- Pair 44px mint pills with unboxed mint arrow links.
- Include the repeated-module illustration and its rising clipped edge in the landing-page visual vocabulary.
- Use 16px-radius near-black cards and subtle alpha outlines instead of bright raised tiles.
- Retain a four-column utility ending even after a form or FAQ.

### Don't

- Do not spread fuchsia across ordinary features; it belongs to the contrasting participation treatment.
- Do not introduce serif headlines or monospace marketing paragraphs; Inter remains the main voice.
- Do not enlarge every section heading to the 60px opening scale; recurring arguments use 36px/40px.
- Do not turn the pricing actions into detached pills; their 48px bars close the columns flush.
- Do not add pronounced shadows to ordinary capability cards; their hierarchy comes from hairlines and spacing.
- Do not put company-logo white tiles into the default opening trust strip; that strip stays dark.
- Do not make all corners 24px; that softer framing is for company material.
- Do not replace outcome-led case-study text with unsupported giant numerals.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.15s color-related transitions with cubic-bezier(0.4, 0, 0.2, 1); some utility links declare the same timing for all properties.
- Arrow-link children declare a small 2px rightward hover displacement.
- The shared header remains sticky while content moves behind its translucent backing.

**Transfer:**

- Keep color feedback quick and local to mint links and pills; do not turn the repeated diagram into an unrelated cinematic animation.

**Unknown:**

- The timing and behavior of illustration or on-scroll animation are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 576px, 640px, 768px, 1024px, 1200px, 1280px, 1440px, 1536px and 1920px.
- The opening declares a single-column base layout and 36px headline, increasing through 48px to the 60px desktop display. Section padding declares 24px, 40px and 56px tiers.
- Narrow capability cards declare horizontal snap scrolling, with a 320px card maximum, before becoming a five-column desktop grid. Footer columns declare two at the base and four at wider widths.
- The desktop pricing matrix is hidden below its large-screen variant.

**Transfer:**

- On narrow screens keep promise before working proof, retain the rail vocabulary and use the declared smaller padding tiers.
- Preserve meaningful diagram groups as a single scalable illustration; avoid separating connected units into unrelated cards.
- Use a compact per-plan presentation on narrow screens rather than squeezing all five comparison columns into the viewport.

**Unknown:**

- Mobile navigation interaction and the exact narrow-screen pricing presentation are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
