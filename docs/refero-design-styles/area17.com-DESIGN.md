# AREA 17 — craft at cinematic scale

## Overview

A modernist editorial style with the confidence of a design studio and the scale of a film opening. White space, black and grey grotesk type, restrained controls and fine rules make room for immersive photography, motion footage and vividly backed work samples. It suits ambitious products and services whose value can be demonstrated visually; the overall density is low, while directories and explanatory chapters become deliberately systematic.

### Essentials

- The opening is a statement followed by an approaching film: a left-aligned 55px/1.1 medium grotesk promise sits below 232px of breathing room after a 64px header; the first media begins at 670px rather than competing beside the headline.
- Headlines behave like continuous editorial speech, not slogans on posters: SuisseIntl 500, 55px/1.1 with -0.015em tracking for promises, 42px/1.1 with -0.014em tracking for chapter statements; sentence case throughout.
- Controls stay deliberately less emphatic than the content: pale grey rectangular buttons, 8px corners, 54px height and 16px/1.4 regular labels; over film the same shape becomes white at 20% alpha with 30px backdrop blur.
- The page is monochrome scaffolding around colored work: white canvas and #1a1a1a text dominate the reading areas; saturated color belongs inside large media rectangles, not a repeated brand-colored button or heading system.
- Images carry the scale of the claim: use near-edge-to-edge films, 1408px-wide landscape work stages or paired 696px media at a 1440px viewport, with 16px outer gutters and 8px corners. If film is unavailable, use full-bleed documentary stills and a simple typographic overlay at the same scale.
- Navigation can become the subject: a 42px grey text index turns its active line #1a1a1a while a related square image appears at the right; preserve this text-led way of exploring new categories rather than replacing it with a wall of chips.
- The ending is a graphic event, not just legal links: a 55px conversational invitation, a small pale button, an 89px ruled utility strip, then a 496px black field containing a monumental white, progressively stretched letterform composition. Rebuild this with the new identity's own initial or symbol.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale grey | `#f2f2f2` | `--color-soft-panel` | surface, action | Default buttons and neutral media backings. |
| Film black | `#000000` | `--color-black` | background, surface | Cinematic stages, inverse testimonials and the graphic ending. |
| Primary ink | `#1a1a1a` | `--color-ink` | text, action, link | Headings, body copy and default navigation. |
| Inactive statement | `#949494` | `--color-muted` | text, link | Inactive index links and page-category headings; secondary large statements. |
| Hairline grey | `#e6e6e6` | `--color-rule` | border | 1px horizontal dividers; faint edges on selected demonstration panels. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Reading canvas; reversed type and letterform artwork on black. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| values narratives | Blue chapter marker | `#69abff` | `--color-tag-blue` | surface, accent | Small rounded chapter marker. |
| values narratives | Mint chapter marker | `#5cdec5` | `--color-tag-mint` | surface, accent | Small rounded chapter marker. |
| capability demonstrations | Wine media backing | `#a12339` | `--color-wine` | surface | A square backing around a light interface example. |
| values narratives | Violet chapter marker | `#b585f8` | `--color-tag-violet` | surface, accent | Small rounded chapter marker. |
| capability demonstrations | Lilac media backing | `#e7d8fe` | `--color-lilac` | surface | A square backing around a dark interface example. |
| long-form project stories | Inset label grey | `#666666` | `--color-toc-label` | text | Small labels inside chapter navigation. |
| people directories and values narratives | Secondary copy | `#757575` | `--color-secondary` | text | Role captions and supporting statements on people and values content. |
| long-form stories and work directories | Frosted pale grey | `#f5f5f5` | `--color-overlay-light` | surface | Visible result of #f2f2f2 at 80% over white; chapter navigation and floating directory controls. |

## Typography

- **SuisseIntl** — All marketing text, navigation, captions and buttons. A neutral neo-grotesk with compact, plainspoken shapes; regular text and medium display cuts, without a contrasting editorial serif. If unavailable, use **Inter**. Use 400 and 500; retain the role-specific negative tracking. Font stack: "SuisseIntl", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | SuisseIntl | 500 | 55px | 1.1 | -0.015em | Opening promise, major section statements and closing invitation. |
| heading | SuisseIntl | 500 | 42px | 1.1 | -0.014em | Chapter heading, text index and updates heading. |
| heading-small | SuisseIntl | 500 | 32px | 1.15 | -0.013em | Story card titles, editorial row headlines and directory group headings. |
| body | SuisseIntl | 400 | 20px | 1.4 | normal | Explanatory paragraphs and principle descriptions. |
| label | SuisseIntl | 400 | 16px | 1.4 | 0.004em | Navigation, actions, dates, eyebrow labels and image captions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| capability and testimonial sections | quote-stage | SuisseIntl | 500 | 42px | 1.2 | -0.014em | Centered white quotation inside a large black panel. |
| long-form project stories | quote-editorial | SuisseIntl | 500 | 36px | 1.15 | -0.013em | Left-aligned quotations with a small portrait attribution. |

**Notes:**

- Use size and grey-to-black contrast rather than a multitude of weights. Display text remains 500, body and interface text remain 400.
- Large supporting statements can use the same recipe as their heading with only a color change and no extra gap. Category labels at the top of editorial pages use the display recipe in muted grey.
- Balance long promises over two or three lines, keeping their measure near ten of twelve columns. Never force every headline into a short oversized slogan.
- The giant closing letterforms are graphic artwork, separate from the text scale.

## Layout

**Density:** Airy in statements and transitions, compact within indexes, captions and navigation. Long pauses separate major ideas; closely set heading/support pairs read as one paragraph.

### Spacing

**Spacing system:**

- **layout step** 16px — Declared base spacing token for gutters and common layout multiples; 12px and 24px form supporting increments, not a universal grid.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Inline icon gaps and caption-to-card-title spacing. | fixed |
| 12px | Index row gaps and small link-to-media caption separation. | fixed |
| 16px | Outer gutters, grid gaps and utility-strip padding. | fixed |
| 24px | Inset panel padding and marker-to-heading spacing. | fixed |
| 32px | Closing-heading vertical padding. | fixed |
| 48px | Rule-to-content inset, action gap after statement, portrait-grid row gap. | fixed |
| 80px | Updates-heading to listing separation. | fixed |
| 96px | Work-grid row separation. | fixed |
| 128px | Media-to-reading-column separation and internal long-form block pauses. | fixed |
| 192px | Opening promise to first media; major chapter separation. | fixed |
| 232px | Opening whitespace after header and closing invitation approach. | fixed |
| 480px | Long pause after the interactive text index. | 33.33vw |

### Containers and grids

- **fluid outer container**: side padding 16px. Full-width layout with no fixed maximum. At 1440px, content spans 1408px.
- **editorial grid**: 12 columns · gap 16px · side padding 16px. Twelve equal tracks underpin statements, inset body copy and work grids. Major statements span ten tracks, about 1171px.
- **paired work**: 2 columns · gap 16px. Equal 696px media columns at desktop; full-width 16:9 media can interrupt the pairs.
- **reading column**: max width 696px. Centered six-track body and quote measure, starting around one quarter of the page width.
- **portrait grid** (only for people directories): 3 columns · gap 16px. 459px square portraits, with 48px vertical separation and plain captions below.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media and buttons | 8px |
|  | navigation controls | 4px |
| values narratives | chapter markers | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### White reading canvas · level 0

**Use:** Default background across the marketing page.

**CSS:** `background: #ffffff; color: #1a1a1a`

**Observed:** Flat, uninterrupted reading areas with no decorative texture or panel shadow.

**Transfer:** Let typography and the media rhythm create hierarchy.

#### Neutral media panel · level 1

**Use:** Backings for artwork, image stages and demonstrations.

**CSS:** `background: #f2f2f2; border-radius: 8px; overflow: hidden`

**Observed:** A soft grey backing contains complete compositions rather than forming a generic padded content card. Selected demonstrations add a 1px hairline.

**Transfer:** Place a real interface or visual artifact in the stage, leaving deliberate surrounding space.

#### Ruled editorial surface · level 0

**Use:** Updates, principle rows, closing invitation and utility strip.

**CSS:** `border-top: 1px solid #e6e6e6`

**Observed:** Dividers stretch across the content container; no vertical dividers or raised tiles.

**Transfer:** Group repeated information by rhythm and alignment.

#### Black stage · level 0

**Use:** Immersive film and graphic ending; inverse quotation panels use rounded corners.

**CSS:** `background: #000000; color: #ffffff; overflow: hidden`

**Observed:** Black is a destination with substantial scale, not a small ornamental strip.

**Transfer:** Reserve it for visually consequential proof and the identity sculpture.

#### Frosted inset · level 1

**Only for:** long-form stories and work directories

**Use:** Chapter navigation and floating work-directory control.

**CSS:** `background: rgba(242, 242, 242, 0.8); border-radius: 8px; backdrop-filter: blur(30px)`

**Observed:** Low-contrast translucent neutral plate; it can sit on white or over moving work.

**Transfer:** Keep its contents compact and functional.

#### Colored demonstration backing · level 1

**Only for:** capability demonstrations

**Use:** Square interface exhibits.

**CSS:** `background: #e7d8fe; border-radius: 8px; overflow: hidden`

**Observed:** Lilac surrounds a dark screen; wine surrounds a light screen. Color belongs to the example, not to the reading column.

**Transfer:** Choose a backing that separates the exhibited interface from the white page.

## Components

### Navigation bar

**Use:** Persistent orientation.

**CSS:** `position: sticky; top: 0px; height: 64px; background: rgba(255, 255, 255, 0.824); z-index: 99`

**Text style:** `label` — SuisseIntl 400 · 16px/1.4 · tracking 0.004em

**Observed:** Large identity mark at upper left on entry, compact brand label over film; navigation runs along the upper right with 16px gaps. Links have 32px hit areas, 12px side padding and 4px corners. Active editorial-page links sit on a pale plate.

**Transfer:** Keep the navigation visually small relative to the opening statement.

### Primary button

**Use:** Conversion and section exploration.

**CSS:** `display: flex; align-items: center; gap: 8px; background: #f2f2f2; color: #1a1a1a; border-radius: 8px; padding: 16px 24px; height: 54px`

**Text style:** `label` — SuisseIntl 400 · 16px/1.4 · tracking 0.004em

**Observed:** Text-only neutral rectangle; paired exploration actions sit side by side, while the closing action stands alone.

**States:** Declared: hover background-color #E1E1E1; focus-visible solid outline #1A1A1A with 2px offset.

**Transfer:** Use the same restrained treatment for primary and secondary exploration rather than inventing a saturated primary style.

### Film overlay button

**Use:** Action on immersive footage.

**CSS:** `background: rgba(255, 255, 255, 0.2); color: #ffffff; border-radius: 8px; padding: 16px 24px; height: 54px; backdrop-filter: blur(30px)`

**Text style:** `label` — SuisseIntl 400 · 16px/1.4 · tracking 0.004em

**Observed:** Anchored near the lower left of the media stage, not centered beneath a headline.

**States:** Declared: hover background-color rgba(255,255,255,0.27); focus-visible solid outline #1A1A1A with 2px offset.

### Text index link

**Use:** Explore categories through a large editorial list.

**CSS:** `color: #949494; position: relative`

**Text style:** `heading` — SuisseIntl 500 · 42px/1.1 · tracking -0.014em

**Observed:** One label per line; active text is dark and paired with a changing square image to the right. The surrounding list uses 12px row gaps.

**States:** Declared: hover color #1A1A1A; focus-visible solid outline #1A1A1A with 2px offset and 4px radius.

**Transfer:** Use meaningful product use cases or audience categories; do not turn it into a dense sidebar.

### Editorial update row

**Use:** Announcements, articles and related proof.

**CSS:** `border-top: 1px solid #e6e6e6; padding-top: 48px; position: relative`

**Text style:** `heading-small` — SuisseIntl 500 · 32px/1.15 · tracking -0.013em

**Observed:** A small category occupies the left, a wide headline and text action occupy the middle, and a 340px square thumbnail occupies the right. Rows are separated by 48px. No enclosing card fill.

**Transfer:** Keep the three-part alignment even when the thumbnail contains typography rather than photography.

### Work media card

**Use:** Large proof exhibits and related stories.

**CSS:** `background: #000000; border-radius: 8px; overflow: hidden; position: relative; aspect-ratio: 16 / 9`

**Text style:** `heading-small` — SuisseIntl 500 · 32px/1.15 · tracking -0.013em

**Observed:** Footage or photography fills the media; an identity can sit centrally over it. A 16px label/date line follows below the media after 16px, then a 32px outcome headline after 8px. Paired variants use square or portrait images rather than forcing uniform heights.

**Transfer:** Use full-width lead examples and paired supporting examples. Put narrative captions outside the image.

### Utility footer

**Use:** Compact functional ending before the identity artwork.

**CSS:** `border-top: 1px solid #e6e6e6`

**Text style:** `label` — SuisseIntl 400 · 16px/1.4 · tracking 0.004em

**Observed:** An 89px horizontal strip: copyright and language at left, newsletter above social links near the middle, policy links aligned right. Its interior has 16px vertical padding.

**Transfer:** Preserve the low profile so the following graphic has the final visual word.

### Chapter navigation

**Only for:** long-form project stories

**Use:** Orient readers in a multi-chapter story.

**CSS:** `background: rgba(242, 242, 242, 0.8); border-radius: 8px; backdrop-filter: blur(30px)`

**Text style:** `label` — SuisseIntl 400 · 16px/1.4 · tracking 0.004em

**Observed:** A centered 696px panel has a small grey title and numbered chapter links. Content is inset 24px; chapter rows are spaced 16px apart.

**Transfer:** Name chapters after progress or outcomes, not generic feature numbers.

### Portrait card

**Only for:** people directories

**Use:** Human attribution and team listings.

**CSS:** `display: flex; flex-direction: column; position: relative`

**Text style:** `label` — SuisseIntl 400 · 16px/1.4 · tracking 0.004em

**Observed:** Square photograph comes first with 8px corners. Name and grey role follow as plain lines without a caption container. Three desktop columns, 16px gutters and 48px row gaps.

**Transfer:** Use consistent studio light and framing, not a mixture of avatars and lifestyle images.

### Principle row

**Only for:** approach and methodology sections

**Use:** Pair a short principle with its practical meaning.

**CSS:** `display: flex; gap: 16px; padding: 48px 0px; border-top: 1px solid #e6e6e6`

**Text style:** `heading-small` — SuisseIntl 500 · 32px/1.15 · tracking -0.013em

**Observed:** Five-track heading at left, seven-track 20px paragraph at right. Final row also closes with a rule.

**Transfer:** Keep each description specific and brief enough to read as an explanation, not a manifesto.

### Chapter marker

**Only for:** values narratives

**Use:** Small colored marker above an editorial statement.

**CSS:** `display: inline-flex; padding: 4px 16px; border-radius: 9999px; background: #5cdec5; color: #1a1a1a`

**Text style:** `label` — SuisseIntl 400 · 16px/1.4 · tracking 0.004em

**Observed:** Mint, blue and violet variants distinguish chapters; a 24px pause separates marker from heading. This is the exception to the rectangular control language.

**Transfer:** Use a short human concept, not an icon or numeric badge.

## Imagery and graphics

### Cinematic proof footage

**Use:** First media stage and major work exhibits.

**Observed:** Natural-light people, buildings seen from the air, exhibitions and real-world product use. Footage is expansive and edge-filling, with restrained darkening to carry white text; there is no browser-frame chrome around documentary material.

**Transfer:** Film the environment in which the new product matters. The minimum equivalent is a high-quality documentary still with natural color, strong spatial depth and a legible white overlay.

### Identity letterform sculpture

**Use:** Signature graphic ending on every marketing page.

**Observed:** A black full-width field carries white angular identity shapes nearly its full 480px artwork height. Repeated forms are extremely narrow at the left, then widen dramatically toward the right, ending in an oversized slash. The composition runs into the edges and feels like stretched typography rather than a conventional logo lockup.

**Transfer:** Make an equally monumental composition from the new identity's initial or geometric symbol; its final placement can adapt to the page, but retain a dedicated black-and-white graphic event.

**Build:** Create an SVG with a 1440 by 480 viewBox on black, beginning 16px beneath the top of the 496px field. Turn one bold letter or symbol into an outlined path. Duplicate it six or seven times at a common height, bottom-cropped; scale successive copies horizontally from hairline compression through narrow, regular and very wide. Place copies edge-to-edge with thin black intervals. Finish with one enlarged diagonal or terminal stroke at the right. Use white fill only; preserve sharp counters and clip overflow.

### Interface exhibits

**Use:** Product demonstrations within large work stages.

**Observed:** Complete dark or light screens are isolated on grey, lilac, wine, pale yellow or black fields; they appear as designed artifacts with generous surround. Portrait handset demonstrations alternate with wider screens, and detail pairs can have intentionally unequal heights.

**Transfer:** Show one credible new-product task per exhibit. Use its own interface palette internally; keep marketing typography outside the demonstration neutral. A static, carefully framed task screen is an acceptable fallback.

### Soft abstract sound object

**Only for:** abstract technology identity stories

**Use:** Visualize an invisible product quality inside a work exhibit.

**Observed:** A mint-green, glassy circular form with dark folds sits against a very pale mint field; the soft glow and refracted light feel tactile rather than illustrative.

**Transfer:** Translate an invisible product behavior into one restrained abstract object, not a page-wide decorative gradient.

**Build:** Inside a landscape media stage, center a circular SVG or rendered disc about one third of stage width. Layer translucent mint wedges around an off-center convergence point, two dark tapered folds and broad pale highlights. Blur the highlight layers softly and add a larger low-opacity mint halo behind the disc. Match the soft refraction; exact gradient stops are not essential.

### People portraits

**Only for:** people directories

**Use:** Systematic team chapters and small quote attributions.

**Observed:** Waist-up or chest-up people photographed against a cool pale grey studio background, softly lit, in ordinary clothing. Square framing and consistent subject scale make a long directory feel coherent without stripping individuality.

**Transfer:** Match light, backing and scale across portraits. Keep names and roles outside the image.

### Values media stream

**Only for:** values narratives

**Use:** A documentary and graphic counterpoint to large principles.

**Observed:** A narrow right column mixes typographic artifacts, printed material, work samples, gatherings and candid people footage. Rectangles have 8px corners and 16px separation; the left text remains broad and comparatively still. The surrounding canvas shifts through extremely pale mint, blue and lavender washes.

**Transfer:** Mix artifacts and real human moments rather than using only polished product screens.

**Build:** Use a seven-track text area beside a five-track stack of images. Back successive chapters with a very low-opacity wash derived from the corresponding mint, blue or violet marker over white. Keep the wash almost white and the media itself fully colored.

### Icons

**Observed:** Interface arrows and chevrons are small, plain and subordinate to labels; slider SVGs occupy 20px squares within 54px controls. Text links also use literal → and ↗ glyphs. No pervasive decorative icon system accompanies the main text.

**Transfer:** Use simple monochrome directional arrows, reserving larger symbols for media content rather than adding icons to every section heading.

## Section recipes

How recurring sections are built.

### First screen: Statement becoming film

**Observed:** White canvas is the back layer. A 64px Navigation bar sits above it, with a large identity at the upper left and small links along the right. Below 232px of open space after the header, the left-aligned display promise occupies about ten of twelve tracks and wraps into three lines of dark 55px type. There is no separate support paragraph or immediate button row. After 192px of whitespace beneath the promise, the first documentary media enters at 670px, inset 16px with softly rounded upper corners. Within the first 900px, the entire promise and the upper 230px of media are visible. As the reader continues, the media becomes an immersive full-viewport stage; a white lead-in and vertically changing proof names overlay the film, with a Film overlay button at lower left. This overlay and action belong to the media state rather than the initial white opening.

**Transfer:** Write a substantial outcome-led sentence and stage a real product-use photograph or film beneath it. Without film, use a sequence of strong stills at the same scale and overlay concise proof labels. Editorial index pages open with a muted category title immediately above a dark statement in the same display recipe; a detailed project story can instead open with a 720px film and centered identity, followed by the editorial title.

**Avoid:** Do not substitute a centered SaaS headline, split hero mockup, colorful abstract background or two loud buttons above the fold. Do not expose all overlay states simultaneously.

**Text style:** `display` — SuisseIntl 500 · 55px/1.1 · tracking -0.015em

### Editorial heading pair

**Observed:** A muted category label and dark statement share the display recipe and touch without an extra paragraph gap. The text occupies ten tracks; major editorial openings begin 232px below the header. Later sections can use a single dark statement instead.

**Transfer:** Use a short navigational category followed by a full sentence about the reader's benefit.

**Text style:** `display` — SuisseIntl 500 · 55px/1.1 · tracking -0.015em

### Text-led exploration

**Observed:** A 20px introductory label sits above the Text index link list after 24px. Large grey lines occupy roughly two thirds of the layout. The active line turns dark and reveals a related square media tile to the right. A long 33.33vw pause follows the list before the next major block.

**Transfer:** Use it for product audiences, applications or problem areas, with a distinct image per topic.

**Text style:** `heading` — SuisseIntl 500 · 42px/1.1 · tracking -0.014em

### Editorial updates

**Observed:** A 42px heading leads into a wide listing using Editorial update row. Category, story and square media form a small-left, wide-middle, narrow-right structure. Each row starts with a hairline and 48px inset. A neutral button follows the listing.

**Transfer:** Use a small number of meaningful releases, independent proof points or stories rather than a dense content feed.

**Text style:** `heading-small` — SuisseIntl 500 · 32px/1.15 · tracking -0.013em

### Invitation and identity finale

**Observed:** After 232px of approach space, Ruled editorial surface introduces a left-aligned 55px invitation set across about nine tracks. The headline has 32px vertical padding; a Primary button follows. A 128px pause leads to Utility footer. The final 496px is the Black stage containing Identity letterform sculpture; it is revealed beneath the white reading page and has no extra marketing copy.

**Transfer:** Close with a conversational next step, retain the compact utility strip and rebuild the graphic finale from the new identity. This shared ending works for both short marketing pages and long editorial pages.

**Text style:** `display` — SuisseIntl 500 · 55px/1.1 · tracking -0.015em

### Capability chapter

**Only for:** capability and solution pages

**Observed:** A paired 696px layout places a 42px heading directly above a muted 42px statement on the left. A compact 16px service list sits farther down. The right side is a square exhibit on Colored demonstration backing or Neutral media panel with a small caption and arrow beneath. Chapters are separated by 192px.

**Transfer:** Pair one product capability with one visually specific demonstration and a concise inventory of what it includes.

**Text style:** `heading` — SuisseIntl 500 · 42px/1.1 · tracking -0.014em

### Project narrative chapter

**Only for:** long-form project stories

**Observed:** A large display statement spans about eight tracks before a full-width landscape exhibit. After 128px, body text returns to the centered 696px Reading column; paragraph gaps are 40px. Quote-editorial blocks use that same column with a small square portrait and label attribution. Paired or horizontally overflowing media provides a contrasting rhythm between chapters. A ruled three-column service summary and two related Work media cards conclude the story before the shared invitation.

**Transfer:** Organize chapters around stages of change, alternating tangible artifacts with short explanations. Keep the body measure narrow even when media goes wide.

**Text style:** `display` — SuisseIntl 500 · 55px/1.1 · tracking -0.015em

### Inverse testimonial stage

**Only for:** capability and testimonial sections

**Observed:** A 1408px-wide, 700px-high Black stage with 8px corners centers a white 42px/1.2 quotation across about 933px. A compact identity tile and author sit at lower left; paired 54px previous/next controls sit at lower right. A nearby horizontal strip of pale outcome cards puts short outcomes at the top and identities near the bottom.

**Transfer:** Use one authentic quotation with attribution and one related outcome per proof card. Keep the black panel unillustrated so the sentence is the event.

**Text style:** `quote-stage` — SuisseIntl 500 · 42px/1.2 · tracking -0.014em

### Values and people

**Only for:** company and values pages

**Observed:** Chapter marker, 42px heading and grey same-size support sit at left beside Values media stream. Farther down, a large origin-story visual gives way to centered body copy, then an extensive Portrait card grid grouped by 32px role headings. The canvas returns to white for the directory.

**Transfer:** Use this long editorial variant only when real principles, artifacts and people are central to the page purpose.

**Text style:** `heading` — SuisseIntl 500 · 42px/1.1 · tracking -0.014em

## Page flow

**Storyline:** Outcome promise → immersive tangible proof → explanation or exploration → deeper examples and human credibility → conversational next step → identity-scale graphic ending.

### Broad marketing landing page

1. **Promise** — A substantial editorial statement above an approaching film.
2. **Social proof** — Immersive media with a changing list of proof names.
3. **Explanation** — One large integrated-offering statement and paired neutral exploration actions.
4. **Exploration** — Large text index with active image companion.
5. **Fresh proof** — Ruled editorial updates.
6. **Closing call** — Invitation, utility links and stretched identity graphic.

**Transfer:** Choose the proof and explanation blocks suited to the new product; keep the contrast between white reading space and immersive visual proof.

### Company and people narrative

1. **Promise** — Muted category followed by a large human-centered statement.
2. **Principles** — Colored markers and large grey support beside a moving artifact stream.
3. **Origin** — A singular full-width conceptual image followed by centered prose.
4. **Human credibility** — Department headings and systematic three-column portrait grids.
5. **Closing call** — Shared invitation and graphic ending.

**Transfer:** Use a long people directory only when the visitor genuinely needs it; retain coherent portraits and a mix of real artifacts and human scenes.

### Detailed project or transformation story

1. **Visual hook** — 720px cinematic hero with centered identity.
2. **Context** — Outcome headline, date, narrow introduction and numbered chapter panel.
3. **Demonstration** — Progress chapters alternate large media, narrow prose, expert quotes and paired artifacts.
4. **Summary** — Three-column contribution list and external destination.
5. **Continuation** — Two related-work cards.
6. **Closing call** — Shared invitation, utility strip and letterform artwork.

**Transfer:** Tell a sequence of decisions and outcomes, showing an artifact for each rather than adding generic feature cards.

### Work and use-case directory

1. **Promise** — Muted category and large partnership statement.
2. **Proof** — Alternating full-width landscape and paired square or portrait work cards.
3. **Navigation** — Floating industry browser over media, then ruled multi-column taxonomy links.
4. **Closing call** — Shared invitation and identity finale.

**Transfer:** Curate examples with varied media scale; use the floating browser only when a real taxonomy exists.

### Capability or solution overview

1. **Promise** — Muted category with a dark large statement.
2. **Capability chapters** — Large heading/support pair and compact inventory beside a square exhibit.
3. **Outcome proof** — Horizontal pale outcome cards followed by an inverse quotation stage.
4. **Methodology** — Large approach statement followed by ruled principle rows.
5. **Closing call** — Shared invitation and graphic ending.

**Transfer:** Explain what the product enables, then substantiate it with examples and a working approach instead of a long feature matrix.

## Writing

Assured, collaborative and culturally literate. Claims are framed as purposeful work and meaningful outcomes rather than hype or technical superiority alone.

**Do not copy:** Do not reuse AREA 17's names, identity artwork, client logos, proprietary visual assets, project claims, dates, achievements or quotations. Source examples illustrate cadence only; supply substantiated new-product facts and original language.

- **Addressing the reader:** The organization speaks as we; the reader appears as you mainly in invitations. Work descriptions name the subject directly, while action labels use clear verbs.
- **Rhythm:** Large headings are often complete sentences of 12–24 words. Short principles of 3–7 words interrupt longer explanations. Support is generally one paragraph, sentence case, with restrained punctuation and occasional em dashes.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | We + collaborative verb + audience + consequential outcome. | 16–24 words | “We partner with the world’s most influential organizations to realize their vision and achieve their greatest impact.” |
| Principle | Short contrast or human conviction, followed by a practical explanation. | 3–7 words | “Outcomes over outputs”<br>“Great work comes from great lives” |
| Project headline | Active gerund + transformation + business or human destination. | 10–20 words | “Scaling a research start-up into the leading AI audio platform” |
| Primary action | Plain invitation or exploration verb with a named destination. | 3–4 words | “Get in touch”<br>“See our capabilities” |
| Closing invitation | Let's + exploratory verb + how we can help + reader goal. | 10–14 words | “Let’s explore how we can help you achieve your goals.” |

**Words and phrasing to use:** partner; craft; purpose; meaningful; co-create; outcomes; clarity; realize; belonging

**Avoid:** revolutionary; game-changing; 10x everything; unlock limitless potential; crush the competition; magic; effortless success

**Rules:**

- Lead with the change in a person's or organization's life, then explain the mechanism.
- Use precise domains and practical verbs in supporting copy; let the large image carry spectacle.
- Name index items as recognizable categories, not clever metaphors.
- Keep controls literal and calm, even after an ambitious headline.
- Use quotations for a distinct human perspective, not a repetition of the marketing promise.

## Do's and Don'ts

### Do

- Keep default promises at 55px, weight 500 and -0.015em tracking.
- Align major statements to the 16px outer gutter instead of centering the whole page.
- Use 8px corners on media and buttons, and 4px corners on navigation plates.
- Give ruled editorial rows 48px of top breathing room.
- Keep prose near a centered 696px desktop measure, even beside full-width media.
- Make the initial white opening yield to a large real-world image or film.
- Preserve the 16px label scale for dates, navigation and captions.
- Give the identity artwork a dedicated black field with white shapes and dramatic horizontal scale changes.

### Don't

- Do not turn the restrained 54px pale button into a saturated pill.
- Do not set every hierarchy level in heavy bold; 500 display and 400 reading text provide the contrast.
- Do not apply lilac or wine across normal reading sections; they are exhibit backings.
- Do not add drop shadows to separate editorial rows; use the #e6e6e6 hairline.
- Do not force all work cards to identical heights; portrait and square pairs are part of the rhythm.
- Do not use uppercase, widely tracked eyebrows in place of the 16px sentence-case labels.
- Do not shrink the graphic ending into a conventional small footer logo.
- Do not put names, dates and outcome headlines inside a padded card shell when the image itself is the card.

## Motion and responsive

### Motion

**Observed:**

- The main opening uses sticky media and layered text; the visual proof names change as the reader advances.
- Declared buttons transition color and background over 0.3s cubic-bezier(0.4, 0, 0.2, 1). Large index links transition color over 0.15s with the same curve.
- Declared editorial rows and portrait cards transition opacity and transform over 0.5s cubic-bezier(0.4, 0, 0.2, 1). Values support text uses 0.3s cubic-bezier(0.61, 1, 0.88, 1), with a 0.3s delay.
- The identity artwork sits in a fixed lower layer and is revealed beneath the departing white content.

**Transfer:**

- Preserve the distinction between slow visual staging and quick category feedback. Keep settled text legible rather than showing several inactive overlays at once.
- If the film cannot be animated, preserve the full-stage still and graphic ending rather than substituting ornamental floating effects.

**Unknown:**

- Exact scroll interpolation, video sequencing and canvas deformation timing are not specified.

### Responsive

**Observed:**

- Declared width breakpoints are 600px, 900px, 1200px and 2000px.
- Button classes define 44px controls with 12px 16px padding below the desktop variant of 54px with 16px 24px padding.
- The large desktop navigation is hidden at narrower layouts; work media declares a 3:4 narrow-screen aspect ratio instead of desktop 16:9 or square. Portrait items declare two columns before the three-column desktop layout.

**Transfer:**

- On narrow pages, preserve the statement-before-media composition and turn paired exhibits into a reading sequence rather than squeezing the headline beside a tiny screen.
- Let the letterform artwork clip horizontally while keeping its strong black-and-white field; do not reduce it to body-text scale.

**Unknown:**

- Exact mobile typography, compact navigation interaction and intermediate spacing behavior remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
