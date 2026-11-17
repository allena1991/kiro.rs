# Rulebase — carved matter, live signals

## Overview

A warm, materially grounded software style that pairs charcoal stages and chalky stone relief with spare, regular-weight grotesk typography. Orange actions and fine signal diagrams punctuate a largely bone-and-black palette; small, crisp interface fragments float over tactile backdrops. It suits operational and technical products that need to feel consequential without looking sterile, with airy section spacing and compact information inside each scene.

### Essentials

- The opening is a split between matter and message: a 744px charcoal stage with a roughly 52:48 text-to-art split, a low-set two-line 46px/47px regular headline, a small proof teaser above it and a 36px orange action below.
- Headlines sound decisive without typographic shouting: ABC Diatype at weight 400, 60px/60px with -0.02em tracking for major section leads, and 40px/44px for secondary statements.
- Actions are small rectangular tools, not soft pills: the main button is 36px high with 2px corners and 6px 12px padding; navigation actions use 4px corners.
- Color behaves like an indicator light: the page is overwhelmingly #efedeb and #1a1716, with #fe4c00 confined to compact actions and fine diagrams, never a whole marketing band.
- Software floats against carved matter: sharp white 4px-radius interface fragments overlap cream sculpted relief, sometimes with muted olive accents. Every new page includes a tactile relief-backed scene; use an original grayscale displacement texture when bespoke sculpture is unavailable.
- Fine signal drawings make abstractions legible: 1px orange paths, small nodes and pale halos sit in tall white panels with bottom-aligned 16px titles and 13px explanations. Include a diagram device even when no literal product screen exists.
- A dark reading interlude turns a short statement into an event: centered 40px/44px text within a 900px-wide measure, words shifting from 23% white to full white, with small floating proof fragments. Preserve this device without requiring a fixed section sequence.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#fe4c00` | `--color-orange` | action, accent | Primary conversion action and fine conceptual signal artwork. |
| Burnt action | `#d85210` | `--color-orange-hover` | action | Declared primary-action hover background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pure black | `#000000` | `--color-black` | text | Large light-theme headings and numerical proof. |
| Brown charcoal | `#1a1716` | `--color-stage` | background, text, action | Dark opening and reading bands; primary ink on light surfaces. |
| Body ink | `#1e1e1e` | `--color-body` | text, link | Compact descriptive text and footer links. |
| Charcoal veil | `#252322` | `--color-dark-card` | surface | Raised dark reassurance cards; 5% white over charcoal. |
| Unlit words | `#4f4c4c` | `--color-inverse-dim` | text | Reading-interlude words before illumination; 23% white over charcoal. |
| Muted light-theme ink | `#787776` | `--color-muted` | text | Secondary labels; visible result of 50% black over the warm canvas. |
| Soft inverse ink | `#cbcaca` | `--color-inverse-muted` | text | Opening support copy; visible result of 80% #f7f7f4 over the charcoal stage. |
| Light hairline | `#dcdad8` | `--color-rule` | border | 8% black over the canvas for quiet row and section separators. |
| Integration stone | `#e4e1df` | `--color-tile` | surface | Small integration-logo tile field. |
| Warm gray media bed | `#e8e5e3` | `--color-media-bed` | surface | Feature scene backing. |
| Warm chalk | `#efedeb` | `--color-canvas` | background | Default light canvas and the return surface after dark passages. |
| Warm inverse | `#f7f7f4` | `--color-ivory` | text | Opening headline and primary-button text. |
| Interface white | `#ffffff` | `--color-white` | surface, text, action | Floating interface cards, diagram panels and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| trust strips and detailed product chapters | Stone panel | `#e6e4e2` | `--color-panel` | surface | Visible trust-logo wash from 6% #545252 over the canvas; also the solid chapter-panel backing. |

## Typography

- **ABC Diatype** — Headlines, diagram titles, primary conversion label and proof numbers. Plainspoken neo-grotesk with open counters and a compact, slightly tightened regular cut. If unavailable, use **Inter**. Use 400 and preserve the tight tracking; avoid making headlines semibold. Font stack: "ABC Diatype", "Inter", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Inter** — Support copy, navigation, captions and footer links. Neutral, highly legible UI sans with compact lowercase text. Font stack: "Inter", system-ui, sans-serif.
- **STK Bureau Serif** — Customer testimony, contrasting with the sans-serif product voice. Light editorial serif with narrow, finely shaped letterforms. If unavailable, use **Source Serif 4**. Use 300 with -0.03em tracking. Font stack: "STK Bureau Serif", "Source Serif 4", Georgia, "Times New Roman", serif.
- **Hedvig Letters Sans** (only for light secondary-page navigation actions and recruiting actions) — Small action labels in the secondary-page variant. Unadorned regular sans for short utility labels. Font stack: "Hedvig Letters Sans", Inter, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading-lg | ABC Diatype | 400 | 60px | 1 | -0.02em | Major section leads, often broken into two lines. |
| display | ABC Diatype | 400 | 46px | 47px | -0.03em | Default split-stage headline, usually two concise sentence-like lines. |
| heading | ABC Diatype | 400 | 40px | 1.1 | -0.02em | Secondary section leads and the dark reading statement. |
| quote | STK Bureau Serif | 300 | 32px | 38px | -0.03em | Editorial customer quotation. |
| stat | ABC Diatype | 400 | 28px | 24px | normal | Restrained numerical proof above small explanatory captions. |
| body | Inter | 400 | 16px | 1.5 | -0.0056em | Opening support copy and editorial paragraphs. |
| button | ABC Diatype | 400 | 16px | 1.5 | -0.0056em | Primary conversion label. |
| diagram-title | ABC Diatype | 400 | 16px | 18px | -0.02em | Bottom-aligned titles in the signal-diagram panel. |
| compact | Inter | 400 | 14px | 20px | -0.006em | Feature descriptions, small section support and footer navigation. |
| navigation | Inter | 400 | 14px | 24px | -0.006em | Text links across the header. |
| nav-button | Inter | 400 | 14px | 24px | normal | Compact header conversion label. |
| diagram-copy | Inter | 400 | 13px | 16px | -0.007em | Short explanations underneath conceptual diagrams. |
| proof-tag | Inter | 500 | 12px | 1.25 | -0.008em | Small raised case-study tags on trust logos. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| light product-detail and recruiting openings | centered-display | ABC Diatype | 400 | 60px | 56px | -0.03em | Tightly stacked, centered two-line opening on a warm canvas. |
| detailed product chapters | chapter-title | ABC Diatype | 400 | 28px | 32px | -0.02em | Short title inside an alternating text-and-demo chapter. |
| light secondary-page navigation actions and recruiting actions | secondary-action | Hedvig Letters Sans | 400 | 14px | 24px | normal | Utility and application action labels. |

**Notes:**

- Keep the grotesk regular even at display scale. Tracking tightens to -0.03em in opening headlines, while section leads use -0.02em.
- The default opening headline is smaller than the later 60px section leads; hierarchy comes from staging and contrast rather than always making the first title largest.
- The serif belongs to testimony, not product headlines. Small supporting copy stays sans-serif and sentence case; there is no pervasive uppercase eyebrow system.

## Layout

**Density:** Airy between narrative blocks, compact inside diagrams, interface fragments and utility navigation.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Diagram title-to-description separation and tight local stacks. |
| 12px | Tile-field gaps and small card internals. |
| 16px | Trust-logo gaps and chapter-to-chapter separation. |
| 20px | Dark reassurance-card padding and recruiting-row vertical padding. |
| 24px | Opening content stack gaps and common title-to-support separation. |
| 32px | Chapter text padding and feature-sidebar separation. |
| 40px | Desktop side gutters and feature-grid row gaps. |
| 48px | Major heading-to-content separation. |
| 70px | Opening proof teaser to headline-stack separation. |
| 80px | Feature-section lead-in and proof-grid row separation. |
| 100px | Dark-band vertical padding. |
| 120px | Major editorial section vertical padding. |

### Containers and grids

- **main container**: max width 1432px · side padding 40px. Centered desktop frame; at 1440px the usable content is 1360px wide.
- **opening split**: 2 columns · gap 0px. Text occupies roughly 52% of the opening and full-bleed relief art the remaining 48%; header spans both.
- **signal panel**: 4 columns · gap 0px. Four equal white diagram columns, 340px wide at desktop, with bottom-pinned explanations.
- **feature gallery**: 3 columns · gap 10px. Three media columns beside a 278px explanatory sidebar; separate media rows by 40px.
- **proof grid**: 2 columns · gap 211px. A 471px left heading-and-stat column balanced by a wider quote-and-attribution column.
- **quote measure**: max width 651px. Centered editorial quotation, deliberately narrower than the main container.
- **footer columns**: 4 columns · gap 28.8px. Four compact link columns to the right of a wider brand-and-assurance column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary action | 2px |
|  | cards and navigation actions | 4px |
|  | trust logo cards | 6px |
| product demonstrations | small workflow chips | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | proof tag | `0px 4px 2px 0px rgba(0, 0, 0, 0.05)` | Small white tags raised above a logo card. |
| product demonstrations | workflow chip | `0px 1px 3px 0px rgba(0, 0, 0, 0.1)` | Lightly elevated small workflow labels, not whole marketing cards. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default page field.

**CSS:** `background: #efedeb; color: #1e1e1e`

#### Charcoal stage · level 0

**Use:** Opening, reassurance and narrative reading bands.

**CSS:** `background: #1a1716; color: #ffffff`

**Observed:** A flat warm near-black, not a gradient or blue-black.

**Transfer:** Use it as a deliberate change in atmosphere, with warm light text.

#### Media bed · level 1

**Use:** Feature-scene backing.

**CSS:** `background: #e8e5e3`

**Observed:** A matte warm gray field that can hold white cards and a partial stone relief.

**Transfer:** Keep the backing low contrast so the white interface fragment reads as the active layer.

#### Interface card · level 2

**Use:** Small isolated software examples.

**CSS:** `background: #ffffff; border-radius: 4px`

**Observed:** Mostly shadowless, with crisp edges and tightly grouped content.

**Transfer:** Show one meaningful state or event instead of an entire dashboard.

#### Dark veil card · level 1

**Use:** Reassurance cards inside a charcoal band.

**CSS:** `background: rgba(255, 255, 255, 0.05); border-radius: 4px; padding: 20px`

**Observed:** Only slightly lighter than the stage; an emblem is high in the card and explanatory text is low.

**Transfer:** Let spacing, not heavy borders, distinguish the cards.

#### Ruled editorial band

**Only for:** light editorial and detailed product sections

**Use:** Separate long explanations without introducing another fill.

**CSS:** `background: #efedeb; border-top: 1px solid rgba(0, 0, 0, 0.08); padding: 120px 0px`

#### Chapter stone · level 1

**Only for:** detailed product chapters

**Use:** Alternating text-and-demo panels.

**CSS:** `background: #e6e4e2; border-radius: 4px; overflow: hidden`

**Observed:** Wide, shallow panels with a white scene occupying one half.

**Transfer:** Treat each chapter as a single composed object, not a floating rounded card.

## Components

### Navigation

**Use:** Global identity, short destination links and conversion action.

**CSS:** `display: flex; align-items: center; height: 72px; padding: 0px 40px; z-index: 20`

**Text style:** `navigation` — Inter 400 · 14px/24px · tracking -0.006em

**Observed:** A 134px-wide identity is followed by a 48px offset to a short link group with 28px gaps; the conversion action sits at the far right. The opening uses inverse links on the split stage. The scrolled variant becomes a compact light bar with dark links and an orange action.

**Transfer:** Use a small emblem plus wordmark, keep links close to the identity and leave the center of the header open.

### Primary button

**Use:** Main conversion in the opening.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #fe4c00; color: #f7f7f4; height: 36px; padding: 6px 12px; border-radius: 2px; gap: 10px`

**Text style:** `button` — ABC Diatype 400 · 16px/1.5 · tracking -0.0056em

**Observed:** A compact solid rectangle aligned with the opening copy, not a large standalone banner.

**States:** Declared: hover background #d85210 and box-shadow 0px 6px 20px rgba(0, 0, 0, 0.25); focus-visible unknown; active box-shadow 0px 2px 8px rgba(0, 0, 0, 0.2).

### Header action

**Use:** Persistent secondary conversion entry.

**CSS:** `background: #ffffff; color: #1a1716; height: 36px; padding: 6px 14px; border-radius: 4px`

**Text style:** `nav-button` — Inter 400 · 14px/24px

**Observed:** White over the relief art in the opening; orange in the scrolled light navigation. The light secondary-page variant uses a dark gray fill and white type.

**Transfer:** Maintain the small scale so the main body action remains more prominent.

### Text link

**Use:** Header destinations and low-emphasis navigation.

**CSS:** `color: #ffffff; text-decoration: none; transition: opacity 0.2s`

**Text style:** `navigation` — Inter 400 · 14px/24px · tracking -0.006em

**Observed:** No arrow decoration or underline in the resting header. Footer links switch to body ink and the compact recipe.

**States:** Declared: hover opacity 0.7; focus-visible unknown.

### Trust logo card

**Use:** Social proof in a horizontal moving strip.

**CSS:** `display: flex; align-items: center; justify-content: center; position: relative; background: rgba(84, 82, 82, 0.06); border: 1px solid transparent; border-radius: 6px; padding: 12px 16px; height: 51px`

**Observed:** Monochrome logos remain individually recognizable; selected cards carry a raised Proof tag that overlaps the top edge. The strip fades at its sides rather than ending abruptly.

**States:** Declared: hover and focus-visible background #dedcda, box-shadow none, border-color rgba(0, 0, 0, 0), outline none, transform none.

**Transfer:** Use legitimate partners or proof sources and preserve the lightweight tab-like framing.

### Proof tag

**Use:** Case-study or listing label above a trust-logo card.

**CSS:** `position: absolute; display: flex; align-items: center; background: #ffffff; color: #000000; border-radius: 4px; padding: 4px 8px; box-shadow: 0px 4px 2px 0px rgba(0, 0, 0, 0.05)`

**Text style:** `proof-tag` — Inter 500 · 12px/1.25 · tracking -0.008em

**Observed:** The little label protrudes above the logo card, rather than becoming a centered caption below.

### Signal diagram panel

**Use:** Explain a small set of conceptual capabilities.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); background: #ffffff; height: 515px`

**Text style:** `diagram-title` — ABC Diatype 400 · 16px/18px · tracking -0.02em

**Observed:** Tall equal columns hold sparse orange diagrams well above bottom-aligned titles and short Diagram-copy paragraphs. Fine vertical divisions separate the columns.

**Transfer:** Map each panel to a verb and a distinct line behavior, such as branching, peaking, joining or looping.

### Reassurance card

**Use:** Credibility details on a dark band.

**CSS:** `position: relative; background: rgba(255, 255, 255, 0.05); border-radius: 4px; padding: 20px; height: 350px`

**Text style:** `compact` — Inter 400 · 14px/20px · tracking -0.006em

**Observed:** Four near-touching cards sit in one row with 6px gaps. Each reserves a high area for a white emblem and a low area for title and muted explanation.

### Integration tile

**Use:** Dense compatibility artwork near the ending.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 80px; height: 80px; background: #e4e1df; border-radius: 4px; overflow: hidden`

**Observed:** Three rows with 12px gaps form a wide, softly fading field; muted partner marks surround a high-contrast central identity tile.

**Transfer:** Make all intended compatibility marks legible near the center and fade outward. Use relevant tool-category symbols if the product has no partner ecosystem.

### Footer

**Use:** Common quiet ending and site navigation.

**CSS:** `display: flex; flex-direction: column; padding: 64px 40px 40px; position: relative`

**Text style:** `compact` — Inter 400 · 14px/20px · tracking -0.006em

**Observed:** Brand, a short promise and two small assurance seals occupy the left; four link groups occupy the right. Column headings are muted, with 29px before links and 13px between list items. Copyright sits bottom left and a small backing attribution sits bottom right.

**Transfer:** End with useful navigation and concise assurance rather than introducing a new oversized conversion banner.

### Recruiting row

**Only for:** recruiting pages

**Use:** Compare open opportunities with an aligned action.

**CSS:** `display: grid; grid-template-columns: 200px 200px 130px 170px 1fr auto; align-items: center; column-gap: 24px; padding: 20px 0px; border-top: 1px solid rgba(0, 0, 0, 0.08)`

**Text style:** `compact` — Inter 400 · 14px/20px · tracking -0.006em

**Observed:** Columns hold role, location, engagement, compensation, experience and a dark application action. Labels sit in a quiet header row; no outer boxed table.

**Transfer:** Adapt the fields to real hiring information while retaining a light ruled ledger.

### Application action

**Only for:** recruiting pages

**Use:** Action at the end of an opportunity row.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #1a1716; color: #ffffff; height: 36px; padding: 0px 18px; border-radius: 4px`

**Text style:** `secondary-action` — Hedvig Letters Sans 400 · 14px/24px

**Observed:** Compact dark rectangle aligned to the final column; not a full-width button.

## Imagery and graphics

### Carved relief scene

**Use:** Signature tactile backing in the opening and recurring product scenes.

**Observed:** Cream-colored sculpted plaster or stone with deep curling leaf-like ridges, shallow granular surfaces and directional shadows. The opening is an edge-to-edge close-up; later scenes use partial irregular chunks or rectangular texture fragments behind crisp white software cards. Subtle olive material appears sparingly in smaller scenes.

**Transfer:** Create original neutral relief forms rather than generic abstract blobs. Preserve the matte surface, directional depth and small white UI layer. The minimum version is a high-resolution grayscale displacement texture with broad carved folds and directional lighting.

**Build:** Use an original height-map or SVG displacement field rendered into a cream material. Layer broad curling contour paths over low-amplitude grain, light from the upper left and retain gray-brown recessed shadows. Fill roughly half the desktop opening with a cover image; in feature scenes place one relief fragment partly off an edge beneath the white card. Do not fake the material with a flat gradient.

### Signal line drawings

**Use:** Required conceptual diagram device.

**Observed:** Sparse warm-orange plots on white: a vertical scan crossing horizontal lines, a single sharp peak, branching curves and an ascending loop. Active points have small solid dots and larger pale circular halos; much of each panel remains open.

**Transfer:** Invent geometry that expresses the new product's operations without reproducing the exact plots.

**Build:** Use SVG paths with 1px #fe4c00 strokes at varied opacity, 3px to 4px-radius active nodes and 16px to 18px-radius halos filled with rgba(254, 76, 0, 0.06). Put muted endpoints at lower opacity, and use one dominant active node per diagram. Center the drawing above a bottom caption stack within a 340px by 515px panel.

### Product fragments

**Use:** Demonstrate an event, diagnosis or handoff in context.

**Observed:** Small, straight-on white cards show a handful of rows, a short message or a simple chart. Crisp black and gray microtype contrasts with the rough organic backing; warning red and muted olive are contained within the interface rather than tinting the marketing page.

**Transfer:** Use a believable moment from the new product. Keep the fragment readable and limited to the event supporting the nearby claim; avoid stuffing in an entire application shell.

### Human proof photography

**Use:** Video proof teaser, case-study media and testimonial portraits.

**Observed:** Natural-color people and workplaces without a heavy brand tint. A tiny landscape interview thumbnail sits above the opening headline; a wide architectural video poster later fills the content width. Small portraits accompany attribution.

**Transfer:** Choose credible people and real work settings, with natural warm lighting and unobtrusive rectangular framing.

### Fading compatibility field

**Use:** Graphic proof near the end of a general marketing narrative.

**Observed:** A broad three-row field of pale square tiles recedes into the warm canvas at the edges. Partner marks are grayscale; one center tile is black with a white emblem.

**Transfer:** Keep the center dense enough to read as an ecosystem, even for a product represented by categories instead of partners.

**Build:** Create 80px square tiles separated by 12px gaps. Use #e4e1df backgrounds and low-contrast grayscale SVG marks. Apply a horizontal mask fading to transparency at both ends and a soft vertical fade on outer rows; keep the central identity tile opaque and high contrast.

### Founder portrait collage

**Only for:** recruiting and company-story openings

**Use:** Humanize a centered light-theme opening.

**Observed:** A 567px by 383px environmental two-person portrait sits in front of offset relief fragments; a short muted centered caption follows with a 12px gap.

**Transfer:** Photograph the actual team in a specific working environment. Retain one central rectangular photograph and two small off-axis material fragments rather than a mosaic of headshots.

### Icons

**Observed:** Utility symbols are small monochrome outlines, usually 16px to 24px, with roughly 1.3px to 1.6px strokes and rounded caps where applicable. Detailed-product lists place 24px symbols in 48px square stone backings. Assurance emblems are larger white filled marks.

**Transfer:** Use a consistent restrained outline set for concepts and reserve solid emblems for identity or assurance. Do not introduce multicolor decorative icon circles.

## Section recipes

How recurring sections are built.

### First screen: Split material opening

**Observed:** The first 744px is a charcoal stage divided roughly 52:48. A Navigation overlays the top 72px. Left copy is anchored in the lower portion, with a small video proof teaser above it separated by 70px. The two-line Display is followed by a roughly 447px-wide support paragraph and Primary button, with 24px local gaps. The right half is a full-height Carved relief scene with a roughly 378px-wide white product fragment floating centrally and a short status strip beneath. Back-to-front layers are flat charcoal, full-bleed cream relief, white event cards and header. The first 900px includes headline, support, action, the complete main scene, a 123px trust strip and the beginning of the next content area; detailed feature explanations continue below.

**Transfer:** For a different product, replace the event card with a clear moment of useful work and build an original neutral relief backdrop. Preserve the low-set text, early human proof and contrast between material and software. Detailed-product openings use a centered light-theme headline, compact relief-backed demonstration beneath and support line below; recruiting openings substitute the Founder portrait collage and place support above it.

**Avoid:** Do not center the default headline over a full-screen background or move all meaningful copy below the fold. Do not replace the physical relief with neon gradients or an enormous app dashboard.

**Text style:** `display` — ABC Diatype 400 · 46px/47px · tracking -0.03em

### Trust strip

**Observed:** A Warm canvas strip 123px high uses 28px vertical padding, a small left-aligned trust sentence and a horizontally moving row of Trust logo cards with 16px gaps and raised Proof tags.

**Transfer:** Keep the statement compact and let independent proof carry the visual weight.

### Verb diagram panel

**Observed:** Signal diagram panel follows compact mode tabs with 24px separation. Four sparse diagrams share a single white field; captions sit at the bottom with 8px title-to-copy gaps.

**Transfer:** Use three or four sharply differentiated operations, each described with an active verb and one short benefit sentence.

**Text style:** `diagram-title` — ABC Diatype 400 · 16px/18px · tracking -0.02em

### Sidebar and scene gallery

**Observed:** A 60px section lead sits above a narrow text-tab sidebar and three columns of Media beds. Scene media is about 343px by 398px, followed by a short title and compact explanation. The gallery uses 10px horizontal and 40px vertical gaps.

**Transfer:** Group capabilities into a small number of named themes; compose each tile around one fragment and one material detail.

**Text style:** `heading-lg` — ABC Diatype 400 · 60px/1 · tracking -0.02em

### Measured customer proof

**Observed:** A two-column top region balances a 40px headline against a 20px sans quotation. Modest 28px statistics and quiet captions sit below the headline; portrait and attribution sit below the quote. A 1360px-wide, roughly 708px-high video follows with a compact central play control.

**Transfer:** Use a small number of substantiated numbers and a substantial media story, rather than giant KPI numerals.

**Text style:** `heading` — ABC Diatype 400 · 40px/1.1 · tracking -0.02em

### Editorial testimonial

**Observed:** On the light canvas, a centered 651px measure holds 32px serif testimony with a portrait and small attribution below; 120px padding creates breathing room. The detailed-product variant is left-aligned inside a 1360px by 525px charcoal panel with 4px corners, a 142px portrait at the top, a wide quote below and attribution near the bottom.

**Transfer:** Use a real statement with editorial restraint; choose the light centered treatment by default and the dark panel for a product-detail ending.

**Text style:** `quote` — STK Bureau Serif 300 · 32px/38px · tracking -0.03em

### Dark assurance and reading passage

**Observed:** A Charcoal stage supports a 40px section lead and a row of Reassurance cards. A separate dark reading interlude holds a centered 900px-wide statement in a viewport-height sticky region; words light progressively and small proof cards overlap the text.

**Transfer:** Express the new product's consequential problem in a few plain clauses. Keep the reading device, but let its placement and duration fit the new story.

**Text style:** `heading` — ABC Diatype 400 · 40px/1.1 · tracking -0.02em

### Compatibility close and utility ending

**Observed:** A centered 60px heading and compact support line introduce the Fading compatibility field. The Footer follows on the same Warm canvas. Other page types end with opportunities or a dark testimonial panel before the same Footer; none adds a new oversized closing CTA.

**Transfer:** Choose the last proof appropriate to the new page's purpose, then settle into useful navigation and assurance.

**Text style:** `heading-lg` — ABC Diatype 400 · 60px/1 · tracking -0.02em

### Alternating product chapters

**Only for:** detailed product pages

**Observed:** Chapter stone panels are 1360px wide and 536px high, separated by 16px. Equal text and visual halves alternate sides. The text has 32px padding, a numbered square with a short category label, a 28px title after 24px, and a compact explanatory paragraph pinned low. The white visual half contains one demonstration and relief accents.

**Transfer:** Give each chapter a distinct explanatory task and a single intelligible demonstration.

**Text style:** `chapter-title` — ABC Diatype 400 · 28px/32px · tracking -0.02em

### Outcome inventory

**Only for:** detailed product pages

**Observed:** A 60px lead precedes broad ruled rows. Each row has a short label and muted explanation at left, and a two-column list at right with 48px icon squares, 16px gaps and concise labels.

**Transfer:** Explain inputs, discoveries and practical outputs using comparable visual density rather than a wall of badges.

**Text style:** `heading-lg` — ABC Diatype 400 · 60px/1 · tracking -0.02em

### Editorial columns and opportunities

**Only for:** recruiting and company-story pages

**Observed:** Long-copy sections use 120px vertical padding and a 40px heading in the left column, with two roughly 341px text columns to the right. Later sections begin with a faint top rule. Recruiting rows conclude the body before the common Footer.

**Transfer:** Separate the organization's story, direction and concrete opportunities without turning them into promotional cards.

**Text style:** `heading` — ABC Diatype 400 · 40px/1.1 · tracking -0.02em

## Page flow

**Storyline:** Promise → tangible mechanism → capability explanation → credible proof → consequential reassurance → last relevant proof → useful navigation.

### Broad marketing landing page

1. **Promise** — Split charcoal-and-relief opening with a product event and compact conversion action.
2. **Social proof** — Moving logo cards with small elevated tags.
3. **Mechanism** — Sparse verb-led signal diagrams.
4. **Capability chapters** — Large section lead and sidebar-driven scene gallery.
5. **Quantified proof** — Restrained stats, customer quotation and wide video.
6. **Reassurance** — Editorial testimony and dark assurance cards.
7. **Problem framing** — Progressively illuminated statement with floating event fragments.
8. **Compatibility proof** — Fading tile ecosystem.
9. **Utility ending** — Shared light footer with assurance and four navigation columns.

**Transfer:** Borrow the contrast between tactile staging, clear mechanism and understated proof; reorder blocks around the new product's strongest argument.

### Recruiting and company narrative

1. **Invitation** — Centered light opening with a human portrait collage.
2. **Credibility** — Editorial heading and two columns of leadership context.
3. **Direction** — Ruled long-copy section explaining the organization's intended change.
4. **Actionable opportunities** — Light ledger of roles with aligned dark actions.
5. **Utility ending** — Shared warm footer.

**Transfer:** Use human imagery and specific opportunity details while retaining the same typographic and spacing discipline.

### Focused product-detail explanation

1. **Promise** — Centered light headline, compact material-backed demonstration and support copy.
2. **Social proof** — Shared trust strip.
3. **Problem framing** — Large headline and numbered consequences.
4. **Mechanism** — Alternating numbered text-and-demonstration panels.
5. **Capability summary** — Ruled input, detection and output inventories with small icons.
6. **Customer proof** — Broad dark serif testimonial panel.
7. **Utility ending** — Shared footer without a second sales pitch.

**Transfer:** Go deeper into a single workflow while using the centered light opening and alternating chapters as scoped variants.

## Writing

Direct, operational and consequential. The language is confident but not celebratory, repeatedly connecting an observable action to a practical outcome.

**Do not copy:** Do not reuse the Rulebase name, emblem, proprietary relief artwork, customer identities or logos, founder details, testimonials, investment attribution, compliance claims, numerical results or product-specific claims. Use only substantiated equivalents for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your when discussing existing tools or team needs; use the product name as the subject when explaining what it does. Company narratives can use we.
- **Rhythm:** Short sentence-like headlines, often paired with a second sentence or contrasting clause. Supporting lines are one or two compact sentences with concrete verbs; longer company narratives use several plain sentences rather than slogan chains.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Pair a comprehensive action with the improved consequence. | 6–10 words | “Monitor every agent. Improve every outcome.” |
| Detailed-product headline | Name a hidden problem, then promise understanding. | 6–10 words | “Know where your AI fails. And why.” |
| Section lead | Use a compact causal pair or challenge a misleading proxy. | 4–12 words | “Every conversation. Better outcomes.”<br>“Measure resolution, not just activity.” |
| Supporting line | Show how the product fits existing work, then identify what changes. | 18–35 words | “Your tools hold the data. [Brand] does the work reading signals across every system and acting on them, without changing how your team operates.” |
| Action | A plain verb naming the next step. | 2–4 words | “Schedule a Demo”<br>“Apply now” |
| Recruiting invitation | Invite participation in a specific domain of change. | 8–12 words | “Help shape the future of customer operations” |

**Words and phrasing to use:** monitor; find; compare; trace; improve; outcomes; every; your tools; not just; what needs to change

**Avoid:** revolutionary; supercharge; magic; game-changing; unlimited potential; delightful experiences

**Rules:**

- Prefer observable work and consequences to abstract intelligence claims.
- Use contrast to clarify: apparent success versus actual outcome, activity versus resolution.
- Give each feature a verb-led name, then explain the mechanism in one sentence.
- Keep action labels literal; do not turn them into playful marketing copy.

## Do's and Don'ts

### Do

- Use 46px/47px regular display type for the default opening and let later section leads grow to 60px.
- Keep desktop side gutters at 40px and preserve the full-bleed art half of the opening.
- Combine the 36px orange action with 2px corners rather than increasing its height for emphasis.
- Stage one crisp white product event against a tactile relief fragment in each major media family.
- Use 120px section padding for editorial breathing room and 16px gaps for consecutive product chapters.
- Keep numerical proof at 28px with short muted captions instead of turning it into a billboard.
- Carry the 80px tile and 12px gap rhythm through the compatibility artwork.
- Retain the calm four-column footer and small assurance details as the page's landing point.

### Don't

- Do not substitute bold 700-weight headings for the regular grotesk; the atmosphere relies on weight 400.
- Do not use orange for full-width backgrounds; keep its marketing role to small actions and fine signal strokes.
- Do not round ordinary cards beyond 4px or convert rectangular actions into pills.
- Do not apply large ambient shadows to media beds or chapter panels; their depth comes from relief and overlap.
- Do not set long body paragraphs in the testimonial serif or use a decorative serif hero.
- Do not scale the proof tags up to the logo-card height; they are small 12px labels perched above.
- Do not introduce a separate dark footer after the dark reading passage; the common ending returns to warm chalk.
- Do not turn the three-column scene gallery into a field of identical icon-and-text SaaS cards; preserve material-backed demonstrations.

## Motion and responsive

### Motion

**Observed:**

- Trust strips declare trust-slide at 45s linear infinite.
- Primary conversion action declares background-color and box-shadow transitions of 0.22s and hero-rise at 0.9s cubic-bezier(0.22, 1, 0.36, 1) with a 0.48s delay.
- Text navigation declares opacity transitions of 0.2s.
- Trust-logo cards declare transform 0.18s cubic-bezier(0.2, 0.8, 0.2, 1), with background-color, border-color and box-shadow at 0.18s.
- The dark reading scene uses a viewport-height sticky stage, progressive word illumination and floating proof fragments.

**Transfer:**

- Keep motion concentrated in the moving proof strip, small action feedback and the dark reading device. Give the material stage a composed, legible resting state.
- For a static rendition, show the reading statement fully lit and retain a small proof fragment so the device still has a clear composition.

**Unknown:**

- Exact scroll-to-word mapping and floating-fragment timing are not specified.
- Reduced-motion behavior is not established.

### Responsive

**Observed:**

- Desktop layouts use a centered frame with at least 40px side gutters.
- Declared width breakpoints include 500px, 560px, 640px, 760px, 767px, 900px, 1024px, 1100px, 1200px, 1320px and 1440px.

**Transfer:**

- For narrow layouts, stack the opening text and material scene while keeping the headline, action and a recognizable relief-backed product event early in the page.
- Reduce diagram columns or make them a controlled horizontal sequence; keep their bottom caption relationship and thin-line geometry.
- Stack the feature sidebar above its scenes, convert recruiting rows into labeled groups and keep the final action tied to its opportunity.

**Unknown:**

- Exact mobile typography, navigation menu construction and breakpoint-specific column changes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
