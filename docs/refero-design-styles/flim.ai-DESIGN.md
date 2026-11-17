# Flim — cinematic graph-paper playground

## Overview

A bright, playful editorial style that pairs enormous black grotesk lettering with the language of a creative desktop. White space and pale graph paper carry cinematic photography, floating image fragments and cheerful yellow, green and orange geometry. It suits visual tools and products with expressive outputs: sparse at the narrative level, dense and collage-like inside demonstrations.

### Essentials

- Headlines behave like oversized word arrangements, not conventional title blocks: Swizzy 500 at 125.2px/0.86 with -0.02em tracking; graph-paper swatches and simple colored symbols interrupt selected words.
- The opening is a brand masthead above a visual playground: a 448×160px wordmark at left, a 27.2px/1 promise at right, an 183×68px thumbnail button beneath it, then a 700px-tall field of floating media on graph paper.
- Actions mix squared controls with soft utility capsules: the main thumbnail action has 8px corners and 12px uppercase mono text; search and email controls use fully rounded ends, with a smaller white action nested at right.
- Color arrives in concentrated graphic chapters rather than an all-over tint: most of the page is white or #f5f5f5; #30a81d and #ff8400 occupy half-width panels against #141414, while #fecc33 marks symbols and selected emphasis.
- Imagery reads like a moodboard being assembled: cinematic frames, variable-sized rounded cutouts, overlapping browser fragments, tiny captions and selection handles. Every new page needs this staged-media device; use photographs of outcomes or layered annotated artifacts when no visual interface exists.
- Graph paper and a monumental sign-off are identity devices: use 1px ink-at-10% rules on a 32px grid, flat geometric companions, and a closing wordmark spanning 1392px with its bottom edge cut by the page boundary.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal yellow | `#fecc33` | `--color-yellow` | accent, surface, border | Geometric symbols, newsletter art and highlighted plan emphasis. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Play orange | `#ff8400` | `--color-orange` | surface, accent | Contrasting chapter backing, scattered shapes and oversized proof capsules. |
| Play green | `#30a81d` | `--color-green` | surface, accent | Large graphic chapter backing and small geometric accents. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#141414` | `--color-ink` | text, background, action | Primary text, dark chapter bands, circular media stages and black actions. |
| Graph line | `#dfdfdf` | `--color-grid-rule` | border | Visible result of 10% near-black rules over pale graph paper; use the alpha recipe on colored panels. |
| Soft gray | `#e9e9e9` | `--color-chrome` | surface, border | Window title strips, small utility controls, ordinary plan headers and plan outlines. |
| Graph paper | `#f5f5f5` | `--color-paper` | surface, background | Pale backing for grids, dot fields and demonstrations. |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Default page canvas, reversed text and nested capsule actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark newsletter banners | Dark input | `#2d2d2d` | `--color-dark-field` | surface | Email field within the dark newsletter lozenge. |
| question-and-answer sections | Divider gray | `#d9d9d9` | `--color-rule` | border | FAQ row hairlines. |

## Typography

- **Swizzy** — Display lettering, headlines, paragraphs and feature descriptions. Compact, blunt neo-grotesk with a large x-height, low contrast and assertive medium-weight texture. If unavailable, use **Inter**. Use 500 for most text and retain the tight tracking; 700 is reserved for plan names. Font stack: "Swizzy", "Inter", Arial, sans-serif.
- **PP Neue Montreal Mono** — Navigation, utility actions, eyebrows, browser captions and form labels. Small monospaced capitals with deliberate letter spacing, like labels on a creative workbench. If unavailable, use **IBM Plex Mono**. Use 400 and 0.06em tracking for standard labels. Font stack: "PP Neue Montreal Mono", "IBM Plex Mono", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Swizzy | 500 | 125.2px | 0.86 | -0.02em | Large narrative chapter headings and oversized question-section titles. |
| statement | Swizzy | 500 | 47.2px | 1.1 | -0.02em | Centered manifesto-style statements and the closing audience promise. |
| compact-heading | Swizzy | 500 | 27.2px | 1 | -0.02em | Three-line opening promise and FAQ questions. |
| body | Swizzy | 500 | 20.7px | 1.1 | -0.02em | Short supporting paragraphs, feature titles and arrow text links. |
| utility | PP Neue Montreal Mono | 400 | 14.5px | 1 | 0.06em, uppercase | Search prompt and larger utility labels. |
| label | PP Neue Montreal Mono | 400 | 12px | 1 | 0.06em, uppercase | Eyebrows, navigation, buttons, window captions and newsletter labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | Swizzy | 500 | 93.6px | 0.86 | -0.02em | Centered two-line pricing promise. |
| feature-detail pages | detail-heading | Swizzy | 500 | 73.1px | 0.86 | -0.02em | Capability chapter titles below a centered feature-page opening. |
| pricing pages | plan-name | Swizzy | 700 | 32px | 1.1 | normal | Tier names in plan header panels. |
| feature and pricing cards | card-copy | Swizzy | 500 | 16.5px | 1.1 | -0.02em | Compact supporting text beneath feature art and plan features. |

**Notes:**

- Most sans text stays at weight 500 and -0.02em, even at paragraph sizes. The compressed 0.86 display leading makes stacked words feel like one graphic object.
- Mono labels contrast with the tight sans: uppercase, weight 400, 0.06em tracking. Do not extend this all-caps treatment to body copy.
- The brand masthead is artwork rather than the display text recipe: give a new wordmark the same broad, heavy silhouette while keeping headings lighter.

## Layout

**Density:** Airy between narrative blocks; compact within the small utility controls and richly populated media stages.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Feature title-to-description gaps and inner capsule spacing. |
| 12px | Small repeated utility stacks. |
| 16px | Thumbnail-to-button-label separation. |
| 20px | Bento grid gutters. |
| 24px | Page side gutters, main grid gaps and ordinary control separation. |
| 32px | Feature card inner gutters and medium text stacks. |
| 52px | Opening masthead vertical inset and larger heading stacks. |
| 100px | White demonstration section vertical padding. |
| 128px | FAQ, footer and feature chapter vertical padding. |
| 180px | Breathing room between major narrative sections. |

### Containers and grids

- **page-container**: max width 1920px · side padding 24px. Wide centered page shell; at a 1440px viewport, content spans 1392px.
- **editorial-grid**: 12 columns · gap 24px. Underlying alignment grid for asymmetric text, demonstrations and the split opening masthead.
- **two-part-stage**: 2 columns · gap 24px. Equal 684px text/media modules within the desktop shell; colored chapter bands instead split edge-to-edge with no gutter.
- **footer-columns**: 5 columns · gap 24px. Five equal link groups above a full-width wordmark.
- **feature-bento** (only for feature-detail pages): 3 columns · gap 20px. Equal third-width cards or a double-width lead tile beside smaller stacked tiles.
- **suite-stage** (only for feature-detail pages): max width 1240px. Centered large demonstration panel with a compact tab row above.
- **plans** (only for pricing pages): 4 columns · gap 24px. Equal-width vertical comparison cards with aligned headers, prices and actions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary-action | 8px |
|  | media-stage | 16px |
|  | capsules | 160px |
|  | circular-art | 50% |
| question-and-answer sections | faq-toggle | 8px |
| dark newsletter banners | newsletter-lozenge | 250px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background-color: #ffffff; color: #141414`

**Observed:** An uninterrupted white field separates the media-heavy chapters.

**Transfer:** Let space, rather than extra card borders, distinguish editorial text.

#### Graph-paper stage · level 1

**Use:** Demonstration backing, inline word highlights and floating-media fields.

**CSS:** `background-color: #f5f5f5; background-image: linear-gradient(0deg, rgba(20, 20, 20, 0.1) 1px, rgba(0, 0, 0, 0) 1px), linear-gradient(90deg, rgba(20, 20, 20, 0.1) 1px, rgba(0, 0, 0, 0) 1px); background-size: 100% 32px, 32px 100%; background-position: 0px 12.8px, 0px 0px`

**Observed:** The same fine grid crosses tiny inline tiles and large stages. Green, orange and yellow versions retain the dark translucent linework.

**Transfer:** Reuse one grid texture at multiple scales of container without enlarging its cells.

#### Dark chapter · level 0

**Use:** High-contrast chapter break and circular media backing.

**CSS:** `background-color: #141414; color: #ffffff`

**Observed:** Flat black, without gradients or drop shadows; colored grid panels create the contrast.

**Transfer:** Use a single strong chapter promise against the dark half.

#### Window chrome · level 2

**Use:** Header strips of conceptual browser windows and feature cards.

**CSS:** `background-color: #e9e9e9; height: 44px`

**Observed:** A centered mono caption sits between tiny black utility dots; the outer panel remains rectangular.

**Transfer:** Frame one comprehensible product operation instead of a complete application.

#### Dot-paper stage · level 1

**Only for:** feature-detail pages

**Use:** Capability cards and selected large demos.

**CSS:** `background-color: #f5f5f5; background-image: radial-gradient(rgb(20, 20, 20) 1px, rgba(0, 0, 0, 0) 0px); background-size: 32px 32px; background-position: 0px 0px`

**Observed:** Regular fine dots sit behind collage art; dark variants reverse the dots to white and sometimes combine them with the grid.

**Transfer:** Choose the dot variant for a denser demonstration collection, not for every page surface.

#### Newsletter lozenge · level 1

**Only for:** dark newsletter banners

**Use:** A concentrated subscription call inside a yellow graph-paper band.

**CSS:** `background-color: #141414; color: #ffffff; border-radius: 250px; padding: 72px 48px 56px`

**Observed:** The rounded black form occupies nearly the entire page width inside the yellow backing.

**Transfer:** Keep the enclosing pill monumental, rather than treating it as a small promotional card.

## Components

### Navigation

**Use:** Persistent page navigation.

**CSS:** `position: fixed; top: 0px; height: 58px; width: 100%; z-index: 10`

**Text style:** `label` — PP Neue Montreal Mono 400 · 12px/1 · tracking 0.06em · uppercase

**Observed:** Widely spaced links span the width; account links sit at the far right with a small black sign-up badge. A tiny green right-pointing triangle marks the active item. The bar is visually translucent over moving content.

**Transfer:** Preserve the thin utility-strip character rather than adding a large boxed logo menu.

### Thumbnail action

**Use:** Default opening conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 16px; height: 68px; padding: 8px 20px 8px 8px; background-color: #141414; color: #ffffff; border-radius: 8px`

**Text style:** `label` — PP Neue Montreal Mono 400 · 12px/1 · tracking 0.06em · uppercase

**Observed:** A small yellow-backed image preview precedes the label inside a compact black rectangle. Other conversion actions omit the preview and retain the black rectangular silhouette.

**States:** Declared: hover outline 0px; focus-visible unspecified; active outline 0px.

**Transfer:** Use a crop of an expressive output as the preview, rather than a generic arrow icon.

### Arrow link

**Use:** Secondary action below a short capability description.

**CSS:** `display: flex; align-items: center; gap: 24px; color: #141414; max-width: 100%`

**Text style:** `body` — Swizzy 500 · 20.7px/1.1 · tracking -0.02em

**Observed:** Plain black text followed by a northeast arrow; no button backing.

**States:** Declared: hover outline 0px; focus-visible unspecified; active outline 0px.

### Newsletter field

**Use:** Email collection in the closing area.

**CSS:** `display: flex; gap: 8px; height: 56px; padding: 8px 8px 8px 24px; background-color: rgba(255, 255, 255, 0.1); background-image: linear-gradient(rgba(20, 20, 20, 0.1), rgba(20, 20, 20, 0.1)); border-radius: 160px`

**Text style:** `label` — PP Neue Montreal Mono 400 · 12px/1 · tracking 0.06em · uppercase

**Observed:** Long gray capsule with an understated prompt at left and a smaller white Subscribe capsule nested at right. The footer version spans a half-column; the dark banner version is narrower.

**Transfer:** Keep input and submit action inside one continuous soft outline.

### Demonstration window

**Use:** Visual explanation of a single operation.

**CSS:** `background-color: #f5f5f5; background-image: linear-gradient(0deg, rgba(20, 20, 20, 0.1) 1px, rgba(0, 0, 0, 0) 1px), linear-gradient(90deg, rgba(20, 20, 20, 0.1) 1px, rgba(0, 0, 0, 0) 1px); background-size: 100% 32px, 32px 100%; background-position: 0px 12.8px, 0px 0px`

**Text style:** `label` — PP Neue Montreal Mono 400 · 12px/1 · tracking 0.06em · uppercase

**Observed:** Window chrome tops a spacious grid-backed stage. Rounded image cutouts, save notices, cursor names or selected artifacts occupy its center; panels are staggered vertically around editorial text.

**Transfer:** Show a before/after, assembly or shared artifact. Populate the stage with meaningful visual content rather than a full dashboard.

### Proof capsule

**Use:** Playful quantified proof within a graphic scene.

**CSS:** `background-color: #ff8400; border-radius: 160px; padding: 32px 40px`

**Text style:** `statement` — Swizzy 500 · 47.2px/1.1 · tracking -0.02em

**Observed:** The main orange capsule is joined by smaller black capsules with white text. The group is scattered and rotated among geometric forms rather than lined up as a statistic grid.

**Transfer:** Use verified product-specific counts with short units; the treatment can also label outcome categories without numerical claims.

### Footer links

**Use:** Compact destination groups above the closing wordmark.

**CSS:** `color: #141414`

**Text style:** `label` — PP Neue Montreal Mono 400 · 12px/1 · tracking 0.06em · uppercase

**Observed:** Five equal groups use small uppercase mono category labels above sentence-case sans links. A small copyright line precedes the giant wordmark below.

**Transfer:** Group destinations by reader intent, retaining the tight text texture rather than introducing cards.

### FAQ row

**Only for:** question-and-answer sections

**Use:** Concise objection handling beside a monumental question heading.

**CSS:** `display: grid; grid-template-columns: 1fr; border-bottom: 1px solid #d9d9d9; transition: grid-template-rows 0.4s ease-in-out`

**Text style:** `compact-heading` — Swizzy 500 · 27.2px/1 · tracking -0.02em

**Observed:** Question button has 24px top and bottom padding. A 44×44px gray control with 8px corners and a black chevron sits at right; the collapsed desktop row is about 93px tall. Answers use body text below the question.

**Transfer:** Keep the question itself conversational; let the control remain visually secondary.

### Plan card

**Only for:** pricing pages

**Use:** Aligned tier comparison.

**CSS:** `display: flex; flex-direction: column; position: relative; background-color: #ffffff; border: 1px solid #e9e9e9`

**Text style:** `plan-name` — Swizzy 700 · 32px/1.1

**Observed:** A gray header contains the tier, mono audience label and short description. Price, billing detail, outlined action and checkmarked features follow. The recommended tier uses a yellow header and 2px yellow border, a small outlined popularity pill and the black action; ordinary tiers use outlined actions.

**Transfer:** Align the price and action rows across tiers even when descriptions differ.

## Imagery and graphics

### Floating cinematic field

**Use:** Primary visual playground and supporting media fragments.

**Observed:** Mixed wide and near-square cinematic frames float at unequal sizes over pale graph paper, with rounded edges and no shadows. The pictures preserve filmic greens, warm skin, deep shadows and occasional monochrome. They dominate the lower part of the first screen while leaving a calm horizontal lane for the search control.

**Transfer:** Curate a coherent set of output photographs or product artifacts with varied crops and real tonal depth. When the product has no visual output, use editorial photographs showing its world and small annotated documents, not stock dashboard tiles.

**Build:** On the Graph-paper stage, absolutely position a loose collection of rounded rectangular image masks in three loose horizontal tiers. Vary widths from about 90px to 280px at desktop, let edge images overflow the viewport, and reserve a central lane for a gray pill control. Maintain uneven offsets rather than a masonry grid.

### Geometric companions

**Use:** Inline heading interruptions and playful anchors around media panels.

**Observed:** Flat yellow discs and paired semicircles, a green triangle, an orange rotated square and gray circles with small black-and-colored eyes. Some shapes carry graph-paper linework. They sit behind letters, peek above panel corners and occasionally form small character-like stacks.

**Transfer:** Include a small family of elementary forms that can be built without illustration assets; repeat the same silhouettes rather than inventing a new mascot for each section.

**Build:** Use SVG circles, rectangles and triangles with yellow, green, orange and pale gray fills. Pair two semicircles or four equal discs for a compact icon. For an eye, layer a gray 52px circle, an offset 30px yellow or green iris, then an 18px near-black pupil. Place these at panel corners; build rotated squares with transform: rotate(45deg). Use the 32px graph texture on larger polygons.

### Circular chapter sculpture

**Use:** Large graphic counterweight to dark chapter text.

**Observed:** A 660px near-black circle sits in a 720px-wide saturated grid panel with 30px side inset. In populated scenes it contains a central still and tiny colored cursor-name labels; the opposing half carries white type.

**Transfer:** Use a central outcome image or a small artifact assembly inside the circle. Keep the circle as the dominant silhouette, with supporting details much smaller.

**Build:** Split an edge-to-edge band into equal halves. Give one half green or orange graph paper, center a near-black circle with 50% radius, and layer one rounded image plus tiny colored cursor labels within it. The other half remains near-black for text.

### Monumental wordmark

**Use:** Opening brand anchor and final visual sign-off.

**Observed:** The opening black wordmark is 448×160px. The ending expands to a 1392×497px black graphic across the content width, with the lower edge cut off. A tiny live-action frame is integrated into a letter detail.

**Transfer:** Use the new product's own broad black wordmark as artwork. For a narrow or long name, compose a compact stacked lockup with equivalent visual mass. Include a small image inset as the playful counterpoint.

**Build:** Render the wordmark as inline SVG or heavy vector lettering, scale it to the shell width, and clip a shallow strip at the bottom. Mask a small rectangular media insert into an upper letter detail without impairing recognition.

### Creative-desktop collage

**Only for:** feature-detail pages

**Use:** Capability cards and large product demonstrations.

**Observed:** Layered image frames, white selection outlines, corner handles, file labels and cursor callouts sit on light grids or black dotted fields. Some benefit cards use deliberately cut-and-paste typography, folders, delivery imagery or sticker-like cartoons; others foreground actual interface fragments. Large scenes are much more image-heavy than their short captions.

**Transfer:** Create a collage around one real workflow: three to five artifacts, a selected region and one annotation. Use a simple folder, frame or document metaphor as the minimum version instead of recreating elaborate illustration.

**Build:** Stack rectangular image layers with offset edges, thin white outlines on dark scenes, 8px circular or square selection handles at corners, and small white file-label tabs. Add a flat arrow cursor and one short pill annotation; keep the main content readable.

### Icons

**Observed:** Functional icons are mostly 20×20px outline SVGs with 2px round strokes: checks and chevrons in compact controls. Larger decorative symbols are flat filled geometry around 50–63px; northeast arrows accompany plain text links.

**Transfer:** Keep utility icons sparse and simple; use geometric filled symbols, not a second detailed icon library, for decorative emphasis.

## Section recipes

How recurring sections are built.

### First screen: Brand masthead and floating playground

**Observed:** Navigation occupies the top 58px. Below it, a white masthead uses the editorial grid with 52px vertical inset: a broad 448×160px black wordmark anchors the left, while a compact three-line promise and Thumbnail action occupy the rightmost portion. The promise is 27.2px/1 rather than a second giant title. At 364px the backing changes to graph paper; varied rounded stills float across it behind a centered long search capsule. The first 900px includes the full wordmark, promise, conversion action, search control and the upper media field. More floating imagery and the social proof strip fall below the fold. Layers run from white canvas to graph paper, photographs, then the capsule control.

**Transfer:** Keep the left-hand graphic brand mass, right-hand compact promise and lower staged-media playground even when the product has no app: use output photographs, documents or a composed artifact collection. Feature-detail openings instead use a centered 125.2px headline with a small inline symbol and a graph-paper phrase highlight, one supporting line and a black rectangular action; their large demo starts at the lower edge. Pricing uses the 93.6px centered variant and brings its plan headers into the first screen.

**Avoid:** Do not replace the opening with a centered heading over one conventional dashboard image, or enlarge the compact promise until it competes with the wordmark.

**Text style:** `compact-heading` — Swizzy 500 · 27.2px/1 · tracking -0.02em

### Cultural proof strip

**Observed:** A centered mono label precedes a wide single-line sequence of black partner marks; the section has 180px surrounding breathing room and no enclosing card.

**Transfer:** Use verified customer or integration marks in a consistent monochrome treatment.

### Inline-symbol statement

**Observed:** A centered 47.2px statement spans multiple phrases with graph-paper tiles and simple symbols inserted between words. A large rounded product-browser montage sits beneath, separated by ample white space.

**Transfer:** Write a short belief or category promise and interrupt only one or two phrases with the Geometric companions.

### Dark split chapter

**Observed:** An edge-to-edge 900px-tall band pairs Circular chapter sculpture with white 125.2px display text on Dark chapter. A small mono eyebrow sits above the title and a single 20.7px support line below. Green and orange panel variants alternate sides.

**Transfer:** Use this device to give an important capability or outcome a forceful chapter break; choose its position from the new page's story rather than a fixed sequence.

### Staggered operation windows

**Observed:** A large display heading and short body block occupy half of the editorial grid, with an Arrow link below. Demonstration windows fill the opposite half and continue in staggered lower positions. Inline geometric tiles interrupt the heading; white gaps keep the windows independent.

**Transfer:** Explain a small set of related operations through separate populated windows rather than a uniform feature-card wall.

### Monumental closing

**Observed:** 128px top padding opens with a two-line 47.2px audience promise opposite Newsletter field. Five footer link groups follow with 24px gutters, then a small copyright line and Monumental wordmark across the full content width. The graphic bottom is deliberately cut at the page boundary; a tiny media inset animates the otherwise black lettering.

**Transfer:** End with a concise audience-facing promise and utility, then an oversized own-brand sign-off. Keep the graphic ending even on shorter decision pages.

### Capability bento

**Only for:** feature-detail pages

**Observed:** A 73.1px chapter heading leads into a three-column grid with 20px gutters. Equal thirds or one double-width lead card share flat Window chrome, a graph or dotted art backing, and a bottom caption with a 20.7px title, 8px gap and 16.5px supporting copy. Card text has 32px side and bottom gutters.

**Transfer:** Group a few complementary capabilities under one editorial argument. Use dark card stages for dense workflow imagery and light stages for cut-and-paste benefit art.

### Tabbed creative stage

**Only for:** feature-detail pages

**Observed:** A centered heading and small capsule tabs sit above a large framed demonstration up to 1240px wide. The active tab is black with white mono text; inactive tabs are gray. A tiny geometric eye peeks over the panel corner; stacked media and handles fill the stage.

**Transfer:** Use tabs only when they switch meaningful demonstrations of related capabilities.

### Pricing comparison

**Only for:** pricing pages

**Observed:** A centered two-line promise and support line lead to a monthly/yearly capsule switch, then four aligned Plan cards with 24px gutters. The recommended column alone receives yellow header and outline emphasis. A broad graph-paper access panel below handles special eligibility with a short link and a separate outlined contact action.

**Transfer:** Make the tier decision legible before explaining exceptions; keep negotiated access outside the main tier grid.

### Newsletter interlude

**Only for:** feature-detail pages

**Observed:** Two variants: a yellow graph-paper band with Newsletter lozenge and centered 47.2px white headline; or a 720px-tall split stage with a yellow-backed circular collage at left and a 73.1px heading, short copy and Newsletter field on pale graph paper at right.

**Transfer:** Use the dark lozenge for a compact pause; use the split scene when the invitation needs a visual story.

### Questions with a reaction image

**Only for:** question-and-answer sections

**Observed:** 128px section padding surrounds a two-column layout. A two-line 125.2px heading and a small reaction-film frame on graph paper occupy the left, while stacked FAQ rows fill the right.

**Transfer:** Choose an expressive image that makes the practical question section feel human. Keep answers direct and utility-oriented.

## Page flow

**Storyline:** Brand promise → staged visual proof → capability chapters → practical conversion or objections → useful closing promise and monumental sign-off.

### Broad product introduction

1. **Promise** — Asymmetric brand masthead above a floating-media playground.
2. **Social proof** — Monochrome partner strip and centered editorial statement.
3. **Product demonstration** — A browser montage, playful proof capsules and an oversized typographic explanation.
4. **Capability chapters** — Saturated split bands alternate with white staggered operation windows.
5. **Closing call** — Audience promise, newsletter field, destination columns and full-width wordmark.

**Transfer:** Lead with creative possibility, then alternate dramatic chapter promises with concrete demonstrations.

### Purchase decision

1. **Promise** — Centered category statement with inline symbol.
2. **Pricing** — Billing switch and four aligned comparison cards with one yellow recommendation.
3. **Objection handling** — Special-access panel and local-pricing contact path.
4. **Closing call** — Shared newsletter and monumental footer.

**Transfer:** Condense the narrative so comparisons appear immediately; retain the expressive closing.

### Specialized capability introduction

1. **Promise** — Centered oversized headline, inline geometry, supporting line and action.
2. **Product demonstration** — Small visual examples and capability-selection labels.
3. **Capability chapters** — Three illustrated benefit cards and a large tabbed creative stage.
4. **Objection handling** — Two-column reaction-image FAQ.
5. **Closing call** — Shared promise, subscription field and monumental footer.

**Transfer:** Pair expressive output art with a bounded, practical explanation of what the capability does.

### Workflow and collaboration explanation

1. **Promise** — Centered two-line headline with a geometric interruption and concise action.
2. **Product demonstration** — Wide motion-led operation stage.
3. **Capability chapters** — Dark grid-backed organizational bento, paired output examples and a wide collaborative scene.
4. **Conversion** — Yellow band with a large dark subscription lozenge.
5. **Objection handling** — FAQ beside reaction imagery.
6. **Closing call** — Shared audience promise and oversized footer wordmark.

**Transfer:** Show a progression from individual organization to shared work; keep the interfaces as staged stories, not exhaustive documentation.

### Collection or content-platform introduction

1. **Promise** — Centered category promise and action.
2. **Breadth proof** — Asymmetric image-rich category cards.
3. **Differentiation** — Three graph-paper collage cards under an editorial claim.
4. **Product demonstration** — Large layered moving-image stage.
5. **Conversion** — Split newsletter scene with a circular photographic collage.
6. **Objection handling** — Question rows beside a reaction image.
7. **Closing call** — Shared promise, utility links and monumental wordmark.

**Transfer:** Move from range to selection quality, then show a distinctive interaction before handling questions.

## Writing

Confident, culturally fluent and playful without becoming jokey. The language makes tools feel like a creative partner, while practical explanations stay short and direct.

**Do not copy:** Do not reuse Flim's name, wordmark, film clips, customer logos, character imagery, product names, library counts, pricing, model claims or proprietary slogans as facts or assets for another brand. Source examples illustrate rhythm only.

- **Addressing the reader:** Speak to the reader as you or your in benefits; describe the product as a helpful tool or shared space rather than an institutional we.
- **Rhythm:** Headlines often use two to six words or two parallel short clauses. Supporting copy fits one to three short lines; utility actions stay terse. Periods can punctuate individual headline phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A compact identity claim followed by audience-facing parallel clauses. | Three short lines | “The Creative Sidekick Made for Directors. Built for Storytellers.” |
| Chapter heading | Short verb-led phrases with a visual or emotional payoff. | Two to five words | “Search Beautifully. Create Purposefully.”<br>“Your vision, structured.”<br>“Curation over collection.” |
| Supporting line | Explain one benefit in creative-process language rather than a list of specifications. | One sentence | “Trained for style, tuned for creators.”<br>“A shared workspace for your creative team.” |
| Action | Plain verb or conversational invitation. | Two to four words | “Sign up now”<br>“Check it out”<br>“Learn more” |
| Question | Ask the practical question a new user would say aloud. | One direct question | “How do I get started?”<br>“Can clients view my Board without a [Brand] account?” |

**Words and phrasing to use:** shape; build; create; your vision; together; curated; references; one place; creative process

**Avoid:** revolutionary ecosystem; unprecedented synergies; enterprise-grade everything; effortlessly disrupt; hype-filled superlatives

**Rules:**

- Pair an evocative heading with a concrete support sentence; do not make both abstract.
- Name the reader's action before naming the technology behind it.
- Keep mono labels functional and short; reserve personality for headings and image choices.
- Use verified specifics only when they help a decision, especially in pricing and FAQs.

## Do's and Don'ts

### Do

- Keep large chapter type at weight 500, 0.86 leading and -0.02em tracking.
- Preserve the 24px desktop shell gutters and 20px bento gutters as distinct roles.
- Use 32px graph cells consistently across tiny tiles and large stages.
- Contrast 12px uppercase mono labels with sentence-case sans headlines.
- Build conversion actions as black rectangles with 8px corners; nest white pills within search and email capsules.
- Use saturated green or orange as concentrated half-panel color against near-black.
- Give demonstrations their own 44px gray caption strips and meaningful populated visual stages.
- Finish with an oversized own-brand wordmark spanning the content width.

### Don't

- Do not introduce a universal 16px rounded-card system; most outer panels are square.
- Do not add drop shadows to the graph-paper stages; separation is flat and tonal.
- Do not turn the green, orange and yellow palette into gradient headline fills.
- Do not align every media fragment into identical thumbnails; the floating field depends on uneven sizes and offsets.
- Do not replace the 12px mono utility voice with bold sans navigation.
- Do not use weight 700 for ordinary chapter headings; that weight belongs to plan names.
- Do not shrink the sign-off into a routine small footer logo.
- Do not put large paragraphs inside 0.86-leading display typography; supporting copy uses 1.1 leading.

## Motion and responsive

### Motion

**Observed:**

- FAQ rows declare grid-template-rows 0.4s ease-in-out; their small icon backings declare color and background-color transitions of 0.4s ease-in-out.
- Other declared transitions include transform 0.5s ease-out, transform 1s ease-out and background-color 0.4s ease-out.
- The visual language includes moving media, floating shapes, a pinned horizontal narrative stage and a changing audience word in the promise.

**Transfer:**

- Keep motion tied to the creative-workbench devices: reveal words, move individual artifacts and expand question rows rather than animating every surface.
- When implementing an equivalent chapter slider, keep its text and media readable at each settled stop.

**Unknown:**

- Exact scroll timelines, floating-shape physics, video timing and animated word-change timing are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 767px, 991px, 1240px and 1440px; desktop composition uses a 12-column grid.

**Transfer:**

- On narrow layouts, retain the wordmark/promise hierarchy and place the promise after the wordmark; keep a compact floating-media field beneath them.
- Stack split chapter text and circular art rather than reducing the display until it loses graphic impact.
- Reduce feature and footer column counts while preserving mono captions, graph texture and the oversized final brand sign-off.

**Unknown:**

- Exact mobile type sizes, navigation behavior, gutters and breakpoint-specific layouts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
