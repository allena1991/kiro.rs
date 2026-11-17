# The New Yorker — wit in print

## Overview

A literary, image-led style that pairs idiosyncratic display lettering with bookish serif reading text and small, practical sans-serif controls. White paper, black ink, red rubrics, and occasional blue actions frame a dense but carefully paced collection of photographs and commissioned illustrations. It suits products with stories, expertise, and a point of view, balancing serious reportage with small moments of visual wit.

### Essentials

- A magazine cover rather than a sales billboard: an edge-to-edge photographic opening, a centered masthead above it, and a 500px text measure within one half of the image; the main subject occupies the other half.
- Headlines have a hand-lettered literary character, not typographic muscle: IrvinHeadingPro at 36px/40px, weight 400, normal tracking; reading-card titles switch to Caslon at 22px/28px.
- The page behaves like ruled paper: white canvas, 1px #e5e5e5 section rules, 64px desktop margins, 32px column gutters, and 8px gaps within story stacks.
- Color belongs primarily to pictures: black and white dominate the interface, #db3334 marks 12px rubrics, and #0879bf is reserved for compact actions. Multicolored fills are confined to the playful activity-card variant, not spread across ordinary sections.
- Controls stay editorially subordinate: the masthead conversion is a 23px-high blue rectangle with 1px corners; the secondary media action is a transparent 103px × 48px capsule with a 48px radius.
- Illustrated wit is part of the identity: include a small original line-drawn section ornament or a stand-alone cartoon with a serif caption. When custom artwork is unavailable, use a simple black-ink visual metaphor on white rather than generic interface icons.
- The ending reads like a publication's back matter: a compact illustrated conversion banner precedes a #121212 footer with a centered light masthead, four link columns, and #333333 horizontal rules.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Service blue | `#0879bf` | `--color-action` | action, link | Compact subscription action and contextual onward links. |
| Rubric red | `#db3334` | `--color-rubric` | text, accent | Small category labels; not a large-area fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background | Titles and primary text; dark image-feature backing. |
| Back-matter black | `#121212` | `--color-footer` | background, text | Footer fill and compact bylines; also supporting text in collection layouts. |
| Reading charcoal | `#333333` | `--color-body` | text, border | Default supporting serif text and rules within the dark footer. |
| Credit gray | `#666666` | `--color-caption` | text | Small illustration credits. |
| Footer gray | `#a2a2a2` | `--color-footer-link` | text | Footer navigation and social symbols. |
| Paper rule | `#e5e5e5` | `--color-rule` | border | Fine section separators and light media-action outlines. |
| Warm inset paper | `#f6f4ef` | `--color-paper-inset` | surface | Extended reading spotlight backing. |
| Soft reversed text | `#f5f5f5` | `--color-reverse` | text | Longer support text over dark imagery. |
| White paper | `#ffffff` | `--color-canvas` | background, text | Main canvas and reversed feature titles. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| playful activity collections | Activity yellow | `#ffe17d` | `--color-activity-yellow` | surface | Alternate activity tile. |
| playful activity collections | Activity blue | `#84c9ff` | `--color-activity-blue` | surface | Alternate activity tile. |
| playful activity collections | Activity green | `#5cd687` | `--color-activity-green` | surface | First playful activity tile. |
| playful activity collections | Activity cyan | `#a5e8fd` | `--color-activity-cyan` | surface | Alternate activity tile. |
| playful activity collections | Activity lilac | `#ede8f8` | `--color-activity-lilac` | surface | Alternate activity tile. |

## Typography

- **IrvinHeadingPro** — Feature headlines and section headings. Thin, eccentric literary capitals with flared, irregular details; the glyph design supplies the capital-like appearance. If unavailable, use **Marcellus**. Use weight 400 and normal tracking; it approximates the light inscriptional construction, not the custom letterforms. Font stack: "IrvinHeadingPro", "Marcellus", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **TNYAdobeCaslonPro** — Story titles, descriptions, excerpts, and italic section decks. Warm old-style serif with readable contrast, lively italics, and long-form cadence. If unavailable, use **Libre Caslon Text**. Use regular and italic; preserve the separate 17px, 21px, and 22px roles. Font stack: "TNYAdobeCaslonPro", "Libre Caslon Text", "Times New Roman", Times, serif.
- **Graphik** — Navigation, actions, promotional strips, and credits. Compact clean grotesk, mostly medium weight with slightly negative tracking. If unavailable, use **Inter**. Use weights 400 and 500 with the recipe tracking. Font stack: "Graphik", "Inter", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **NeutrafaceNewYorker** — Small author or expert attribution. Geometric sans with a distinctive editorial byline weight. If unavailable, use **Josefin Sans**. Use 600 for bylines; retain the compact measure. Font stack: "NeutrafaceNewYorker", "Josefin Sans", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **IrvinText** — Small category rubrics. Display lettering adapted for miniature literary labels. If unavailable, use **Marcellus SC**. Use regular weight without added tracking. Font stack: "IrvinText", "Marcellus SC", IrvinHeadingPro, Georgia, "Times New Roman", Times, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| feature-headline | IrvinHeadingPro | 400 | 36px | 1.111 | normal | Primary image-feature title; centered within its text column. |
| section-heading | IrvinHeadingPro | 400 | 28px | 1.143 | normal | Centered collection and chapter headings. |
| story-title | TNYAdobeCaslonPro | 400 | 22px | 1.273 | normal | Titles in cards and compact lists. |
| feature-deck | TNYAdobeCaslonPro | 400 | 21px | 1.333 | normal | Centered narrative support beneath feature headlines. |
| section-deck | TNYAdobeCaslonPro | 400 italic | 21px | 1.333 | normal | One-line editorial description beneath a section heading. |
| body | TNYAdobeCaslonPro | 400 | 17px | 1.412 | normal | Card descriptions and compact collection-feature support. |
| byline | NeutrafaceNewYorker | 600 | 15px | 1.143 | normal | Attribution beneath descriptions; prefix with a short 'By' when appropriate. |
| footer-link | Graphik | 500 | 14px | 1.71 | -0.0125em | Muted link lists in the dark footer. |
| action | Graphik | 500 | 13px | 1.23 | -0.0125em | Media actions and underlined onward links. |
| caption | Graphik | 400 | 13px | 1.23 | -0.0125em | Small promotional-strip text and illustration credits. |
| rubric | IrvinText | 400 | 12px | 1.333 | normal | Small red category name above story titles; letterforms supply the capital-like texture. |
| navigation | Graphik | 500 | 12px | 1.27 | -0.0125em | Compact category and utility navigation. |
| compact-cta | Graphik | 500 | 12px | 1.27 | -0.01em | Small filled masthead conversion action. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| collection landing pages | collection-title | IrvinHeadingPro | 400 | 41.6px | 1.13 | normal | Centered title above the lead image-and-text feature. |
| extended reading spotlights | reading-excerpt | TNYAdobeCaslonPro | 400 | 21px | 1.5 | normal | Long excerpt beside an illustrated cover, with a drop capital. |

**Notes:**

- Display headlines remain light even when wrapping across several lines. Do not simulate the distinctive capital-like glyphs by adding wide letter spacing.
- Serif text carries most of the content; sans-serif appears as a smaller service layer. Keep the 22px card title visually separate from the 17px description and 15px attribution.
- Feature text is usually centered in a 500px measure. Ordinary four-column cards are left aligned; portrait-led criticism cards use centered text.

## Layout

**Density:** Dense editorial collections alternate with spacious image features; the whitespace separates chapters rather than inflating every card.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Explains the recurring stack gaps and section padding.
- **horizontal step** 16px, horizontal — Explains gutters, side padding, and text-column inset values.

| Value | Use |
| --- | --- |
| 8px | Story title, description, and byline stack gaps. |
| 16px | Feature title-to-deck gap, section-heading top padding, and inline promotional-strip gap. |
| 24px | Activity tile padding. |
| 32px | Column gutters and image-feature vertical inset. |
| 48px | Space beneath collection headings; feature text side inset. |
| 56px | Recurring separation between major packages. |
| 64px | Desktop page side margins and spacious feature text top inset. |

### Containers and grids

- **editorial container**: max width 1600px · side padding 64px. Centered outer container; at 1440px the usable width is 1312px.
- **underlying grid**: 12 columns · gap 32px. Shared alignment system for card collections, features, and footer.
- **story collection**: 4 columns · gap 32px. Four 304px story columns within the desktop container.
- **portrait criticism**: 3 columns · gap 32px. Three 416px text columns with narrower 200px × 267px pictures centered above.
- **feature text**: max width 500px · side padding 48px. Text centered within one half of the feature, opposite or over an image.
- **archive list** (only for collection archives): max width 752px · gap 32px. Left-aligned row list paired with a separate right rail.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | ordinary editorial images and cards | 0px |
|  | compact subscription action | 1px |
|  | media action | 48px |
|  | small audio overlay | 4px |
| playful activity collections | activity tile | 16px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Continuous main reading plane.

**CSS:** `background: #ffffff`

**Observed:** Editorial items mostly sit directly on paper without separate card shells.

**Transfer:** Use rules and whitespace to group content.

#### Dark feature · level 0

**Use:** Reversed image-led chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Square-edged media and centered light text; some illustrations extend across the entire panel.

**Transfer:** Let the image provide atmosphere; keep readable space behind the copy.

#### Reading inset · level 0

**Use:** Long-form excerpt spotlight.

**CSS:** `background: #f6f4ef; padding: 48px 64px`

**Observed:** Inset within the main page margins, with no raised edge or shadow.

**Transfer:** Use this warm paper to distinguish a sustained reading moment from a list.

#### Back matter · level 0

**Use:** Full-width closing footer.

**CSS:** `background: #121212; color: #a2a2a2`

**Observed:** Horizontal divisions use darker charcoal rules rather than the light paper rule.

**Transfer:** Keep this as a sober final directory, not another image feature.

#### Activity tile · level 1

**Only for:** playful activity collections

**Use:** A deliberately playful interruption to the publication grid.

**CSS:** `background: #5cd687; border-radius: 16px; padding: 24px`

**Observed:** Blue, cyan, yellow, and lilac siblings share the same construction.

**Transfer:** Choose a flat pastel family and reserve it for an actual interactive diversion.

## Components

### Masthead navigation

**Use:** Brand anchor and compact service controls.

**CSS:** `display: grid; align-items: center; grid-template-columns: 272px auto 272px; height: 64px`

**Text style:** `navigation` — Graphik 500 · 12px/1.27 · tracking -0.0125em

**Observed:** The light masthead is centered over the opening image while utility links, a small blue action, and search sit on the right. After scrolling, a compact dark masthead appears on a white bar. Category navigation is a separate centered row beneath the cover.

**States:** Declared: hover underlines category links.

**Transfer:** Use the new product's own typographic identity as the masthead; keep its service controls visibly subordinate.

### Compact subscription button

**Use:** Persistent masthead conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #0879bf; color: #ffffff; padding: 4px 8px; border-radius: 1px; height: 23px`

**Text style:** `compact-cta` — Graphik 500 · 12px/1.27 · tracking -0.01em

**Observed:** A tiny blue rectangle rather than an oversized hero CTA.

**States:** Declared: hover background rgba(7,88,139,1), no text decoration; active background rgba(51,51,51,1).

### Media capsule

**Use:** Secondary audio or demonstration action in feature panels.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; width: 103px; height: 48px; border: 1px solid rgba(255,255,255,0.3); border-radius: 48px; color: #ffffff; padding: 0px 16px`

**Text style:** `action` — Graphik 500 · 13px/1.23 · tracking -0.0125em

**Observed:** Headphone icon precedes the word. The paper variant uses black text and a light gray outline.

**States:** Declared: hover underlines the label; focus-visible uses an automatic outline.

**Transfer:** Use a similarly understated media action only when it opens real media.

### Ruled section header

**Use:** Opening a grouped editorial chapter.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 16px; border-top: 1px solid #e5e5e5; padding: 16px 0px 48px`

**Text style:** `section-heading` — IrvinHeadingPro 400 · 28px/1.143

**Observed:** Centered heading with an italic deck or small line-art ornament on selected chapters. Category-led collection pages use a tighter lower gap.

**Transfer:** Name the reader's next area of interest, not an abstract sales stage.

### Story card

**Use:** Repeatable information-rich discovery item.

**CSS:** `display: flex; flex-direction: column; gap: 8px; position: relative`

**Text style:** `story-title` — TNYAdobeCaslonPro 400 · 22px/1.273

**Observed:** Image first, red rubric when present, serif title, serif deck, then compact byline. Typical image is 304px × 228px. Some pictures carry a small audio badge in the lower-right corner. No outer border, fill, shadow, or rounding.

**Transfer:** Use the card for a case study, guide, expert opinion, or product application; retain the editorial reading hierarchy.

### Contextual text link

**Use:** Onward action within promotional strips or excerpts.

**CSS:** `color: #0879bf; text-decoration: underline`

**Text style:** `action` — Graphik 500 · 13px/1.23 · tracking -0.0125em

**Observed:** Short verb-led link, often ending in a double angle mark. Inline continuation in long reading text inherits the larger serif recipe.

**States:** Declared: hover color #666666 with underline; active color #000000.

### Footer link directory

**Use:** Navigation and institutional back matter.

**CSS:** `background: #121212; color: #a2a2a2; padding: 32px 0px; column-gap: 32px`

**Text style:** `footer-link` — Graphik 500 · 14px/1.71 · tracking -0.0125em

**Observed:** Centered white masthead above two named groups spanning four columns. A second ruled row holds institutional links; legal text and gray social symbols sit below, followed by a centered privacy control.

**States:** Declared: hover and active underline links while retaining #a2a2a2.

### Activity card

**Only for:** playful activity collections

**Use:** Interactive, lighthearted utility.

**CSS:** `display: flex; flex-direction: column; background: #5cd687; border-radius: 16px; padding: 24px; width: 283px; height: 377px`

**Text style:** `story-title` — TNYAdobeCaslonPro 400 · 22px/1.273

**Observed:** Centered title and two-line explanation at top, black-and-white character illustration in the middle, small action at the foot. Multiple flat-color siblings form an overflowing rail with pagination dots.

**Transfer:** Use the playful treatment for a real activity or short exercise rather than ordinary feature marketing.

### Archive row

**Only for:** collection archives

**Use:** Deep browsing after featured collections.

**CSS:** `border-bottom: 1px solid #e5e5e5; padding: 0px 0px 32px`

**Text style:** `story-title` — TNYAdobeCaslonPro 400 · 22px/1.273

**Observed:** Text on the left, 229px × 172px thumbnail on the right within a 752px-wide row. Rubric, title, short deck, and byline form a compact stack.

**Transfer:** Support an extended catalogue without repeating the full four-column composition.

### Pagination button

**Only for:** collection archives

**Use:** Continue a finite listing.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; width: 160px; height: 48px; padding: 0px 16px; background: #0879bf; border: 2px solid #0879bf; color: #ffffff`

**Text style:** `action` — Graphik 500 · 13px/1.23 · tracking -0.0125em

**Observed:** Centered below the list with 56px separation above and below.

**States:** Declared: hover background and border rgba(7,88,139,1), white text; focus-visible outline rgba(0,102,204,1) solid 3px with 3px offset.

## Imagery and graphics

### Documentary cover photography

**Use:** Opening scene and major feature chapters.

**Observed:** Large naturalistic photographs with real people in specific environments. The opening uses a sweeping snowy mountain scene, dark on the left with the brightly dressed subject on the right. Framing is square-edged and expansive; a smaller headline and several lines of text sit inside the image, not above it.

**Transfer:** Photograph the product in a consequential real-world setting with a person or object strongly off center. Reserve a broad low-detail area for copy. If location photography is unavailable, stage a tangible product and working materials in directional natural light rather than defaulting to a floating interface.

**Build:** Use an absolutely positioned cover image in a black-backed panel. Choose object-position to protect the subject on one half. Add a transparent-to-black scrim only over the text half, then layer a centered 500px copy block above it; keep the subject's local color visible.

### Commissioned editorial illustration

**Use:** Feature art, card art, section ornaments, and moments of wit.

**Observed:** A mixture of ink caricature with light watercolor, geometric visual metaphor, flat-color collage, and monochrome drawing. Art is rectangular in cards or dissolves into white paper in larger features. Small chapter drawings sit centered above headings: spare outlines, a little solid black, and ample empty paper.

**Transfer:** Create an original metaphor for the product's problem, using a limited palette and tactile linework. A minimum version is one recognizable object drawn with black contours and a single flat accent, with visible white space.

**Build:** For a small section ornament, use an SVG about 240px wide with a white backing, black paths around 1px–2px, a few solid silhouettes, and one clear visual joke. Keep its composition horizontal and center it above the section label. Do not replace the drawing with a row of feature icons.

### Portrait and criticism framing

**Use:** Centered criticism-style collections and expert profiles.

**Observed:** Narrow 200px × 267px images sit inside much wider text columns; black-and-white photographs mix with colorful paintings. Other feature portraits are larger, naturally lit, and square-edged.

**Transfer:** Give individual experts or products breathing room by keeping the image narrower than its text column, without adding a card shell.

### Captioned cartoon

**Use:** A stand-alone visual pause within a long editorial page.

**Observed:** A black-and-white cartoon occupies a 500px square area. Its single-sentence serif caption is centered below in italic, followed by a small gray sans-serif credit and a remote onward link.

**Transfer:** Use an original gently absurd observation about the product's world. A simple ink vignette and one restrained sentence can carry the device without elaborate artwork.

**Build:** Place one black-ink SVG scene on white in a 500px-wide figure. Use uneven contour lines, sparse hatching, and broad solid black areas; leave generous internal white space. Put the italic caption outside the artwork and the credit on a separate line.

### Activity characters

**Only for:** playful activity collections

**Use:** Central art in colored interactive tiles.

**Observed:** Small black-and-white animal characters perform visual puns, including book carrying and crossword-pattern bodies. Art is isolated on flat pastel fills and occupies less area than the tile.

**Transfer:** Develop original little characters or animated objects tied to the activity, not generic colored pictograms.

**Build:** Use simple black SVG silhouettes with white inset shapes, rounded eyes, and one task-related prop. Center within a 235px × 128px art area on the tile, without gradients or texture.

### Icons

**Observed:** Small headphone symbols use thin mixed outlines, at 24px in feature actions and 14px inside 24px square image badges. Search is an outline symbol; footer social marks are solid gray, 32px.

**Transfer:** Keep utility icons literal and compact. Use black or white according to the reading surface, and reserve the more expressive drawing style for editorial artwork.

## Section recipes

How recurring sections are built.

### First screen: Cover-story opening

**Observed:** A white advertising strip occupies 122px above an expansive 1440px × 852px image stage. The masthead and utility controls overlay the top of the scene. The picture, darkened on the left, fills the background; the skier and bright equipment dominate the right half. Centered within the left half is a 500px copy block: the 36px/40px feature headline, a 21px/28px deck separated by 16px, inline author emphasis, and the Media capsule. Within the first 900px the masthead, headline, deck, action, and most of the main subject are visible. The bottom of the cover and the separate 44px category-navigation row fall below the fold; the first ruled story collection appears later.

**Transfer:** For a new landing page, use this image-led cover as the default: real setting or a staged editorial still life, off-center main subject, readable dark copy area, centered literary headline, and one modest media or onward action. The advertising strip is not needed. Collection pages instead open with a centered collection title, then a half-width 640px × 480px lead picture opposite centered text on white.

**Avoid:** Do not turn this into a centered giant slogan over a blurred background, a two-button SaaS hero, or a floating application mockup.

**Text style:** `feature-headline` — IrvinHeadingPro 400 · 36px/1.111

### Ruled discovery collection

**Observed:** The Ruled section header spans the 1312px usable container. Four Story cards follow at 32px gutters; each has a 304px × 228px image. Text stacks stay compact while the collection as a whole receives 56px separation from the next package. Overflowing variants use 283px-wide cards and small centered pagination dots.

**Transfer:** Present a curated set of use cases or guides, mixing genuinely different image subjects while retaining one shared type hierarchy.

**Text style:** `section-heading` — IrvinHeadingPro 400 · 28px/1.143

### Alternating editorial feature

**Observed:** An image and a centered 500px text block occupy opposite halves of a 1312px panel. Pictures range from 583px × 648px to 656px × 648px; the text includes a red rubric, feature headline, deck, byline, and Media capsule where relevant. White and Dark feature variants alternate, sometimes using full-panel artwork instead of a split.

**Transfer:** Use a few sustained stories to interrupt dense collections. Let the art determine which half holds the text; avoid forcing every feature into identical image framing.

**Text style:** `feature-headline` — IrvinHeadingPro 400 · 36px/1.111

### Portrait-led criticism

**Observed:** Three 416px-wide columns carry centered 200px × 267px images, rubric, title, short description, and byline. A small original drawing can sit above the chapter title. A second row repeats the same pattern with 32px gutters.

**Transfer:** Use for expert interpretation, reviews, or thoughtful evaluations where narrower artwork creates a different pace.

**Text style:** `story-title` — TNYAdobeCaslonPro 400 · 22px/1.273

### Short promotional interlude

**Observed:** A narrow centered strip, often 82px–112px high, pairs a small editorial illustration with a 13px sans-serif sentence and underlined blue action. Some strips have light horizontal rules.

**Transfer:** Offer a newsletter, sample, guide, or contact route in the rhythm of the page rather than as a large repeated conversion panel.

**Text style:** `caption` — Graphik 400 · 13px/1.23 · tracking -0.0125em

### Back-cover conversion and directory

**Observed:** A centered 940px × 140px illustrated conversion banner sits on white, separated from the full-width Back matter by 56px. The banner pairs a short benefit with a compact subscription area; its art and wording vary. The dark footer is 675px high at desktop: centered light masthead, thin rules, four columns grouped into two headings, a second institutional link band, legal text left and social icons right, then a centered privacy control.

**Transfer:** Close with one succinct benefit and an unobtrusive conversion, then a real navigational directory. Redraw the banner as original art and live text rather than treating it as another hero.

**Text style:** `footer-link` — Graphik 500 · 14px/1.71 · tracking -0.0125em

### Vertical video shelf

**Only for:** short-form video collections

**Observed:** A left-aligned 28px chapter title heads a five-part rail with 20px gutters. Four 240px × 427px portrait video slots have small white names over dark top scrims; the final slot is a collection promotion with a circular image and outlined View All action.

**Transfer:** Use this only for a real series of short portrait-format videos. Retain the tall framing and compact names rather than fabricating video placeholders.

**Text style:** `section-heading` — IrvinHeadingPro 400 · 28px/1.143

### Playful activity shelf

**Only for:** playful activity collections

**Observed:** A centered chapter title and short deck introduce Activity cards with 32px gutters. Flat green, blue, cyan, yellow, and lilac fills form a horizontally overflowing series. Small black and pale pagination dots sit underneath.

**Transfer:** Introduce a genuinely playful utility as a distinct visual register; the new page decides where the diversion fits.

**Text style:** `section-heading` — IrvinHeadingPro 400 · 28px/1.143

### Extended reading spotlight

**Only for:** extended reading spotlights

**Observed:** The Reading inset contains two balanced columns. A small rubric and feature headline sit above a 282px × 376px cover illustration in the left column, with author and credit beneath. The right column begins with 21px/31.5px excerpt text and a drop cap, ends inline with a blue continuation link, and has two smaller related items beneath light rules.

**Transfer:** Adapt to an essay, founder letter, or substantive case study excerpt. Preserve the act of reading rather than replacing it with bullet points.

**Text style:** `reading-excerpt` — TNYAdobeCaslonPro 400 · 21px/1.5

### Archive continuation

**Only for:** collection archives

**Observed:** After the featured collections, a centered ruled chapter heading introduces a narrow left-hand Archive row list with a separate right rail. Repeated rows keep the thumbnail on the right. A centered Pagination button ends the list before the conversion banner.

**Transfer:** Use for deep catalogues and resource centres; the narrow list deliberately lowers visual volume before the ending.

**Text style:** `story-title` — TNYAdobeCaslonPro 400 · 22px/1.273

## Page flow

**Storyline:** immersive lead → curated discovery → alternating deep features and themed collections → lighter editorial pause → continued reading or browsing → compact conversion → directory

### A broad editorial landing page that turns an initial story into sustained discovery

1. **Hook** — One image-led cover with literary headline and restrained action.
2. **Discovery** — Ruled four-column collection introduces several distinct entry points.
3. **Depth** — Large white and dark image features alternate with topical card collections and portrait-led criticism.
4. **Participation** — Small promotional strips and a colored activity shelf invite a low-pressure next step.
5. **Editorial personality** — Warm-paper reading inset, illustrated short dispatches, and a captioned cartoon vary the cadence.
6. **Closing call** — Compact illustrated conversion banner followed by the dark link directory.

**Transfer:** Use the same alternation of immersion, selection, and deeper reading for a product with substantive applications or stories; adjust length and sequence to the content.

### A focused collection landing page with both curated entry points and a browsable archive

1. **Orientation** — Centered display collection title and split lead feature on white.
2. **Discovery** — Four-column introductory stories followed by ruled thematic collections.
3. **Depth** — Larger image-and-copy features punctuate the collection rhythm.
4. **Continued browsing** — Narrow thumbnail rows and a right rail replace the broad grids; a Next Page action ends the archive.
5. **Closing call** — Illustrated conversion banner and the same dark institutional directory.

**Transfer:** Use for a resource library, product category, or knowledge centre. Keep the white title-led opening scoped to this page type.

## Writing

Literary, observant, and self-possessed. It earns attention with specificity, narrative tension, and occasional dry wit rather than breathless persuasion.

**Do not copy:** Do not reuse the publication's masthead, proprietary characters, article titles, author identities, subscription prices, awards, reporting claims, or quoted passages as the new product's assets or promises. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly third-person editorial narration; direct 'you' appears in practical invitations. Actions are plain imperatives, and institutional 'we' is used sparingly.
- **Rhythm:** Feature headlines can be short and evocative or longer questions. Support copy typically develops a concrete situation over one to three sentences; card descriptions are substantial enough to reward reading.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Feature headline | A compact evocative phrase or a specific question with real stakes. | 3–10 words, with longer editorial questions allowed | “Summit and Shadow”<br>“Did Substack Fix the Internet?” |
| Section heading | Short editorial department name rather than a benefit claim. | 1–5 words | “Today’s Mix”<br>“The Critics” |
| Section support | One lightly voiced sentence explaining the recurring experience. | 6–12 words | “Fun, fizzy dispatches from the city and beyond.”<br>“A daily column on what you need to know.” |
| Contextual action | A direct verb plus a precise destination, often with a double angle mark. | 2–8 words | “Subscribe today »”<br>“Try today’s game »”<br>“Next Page” |
| Support strip | A complete practical invitation, not a slogan. | 8–14 words | “Get cultural recommendations in your in-box each week.”<br>“Have confidential information to share with our newsroom?” |

**Words and phrasing to use:** specific nouns; considered questions; small narrative reversals; dry understatement; clear action verbs

**Avoid:** revolutionary; game-changing; unlock your potential; effortless magic; unqualified superlatives; urgent sales countdown language

**Rules:**

- Make the title intriguing but let the deck clarify the actual subject.
- Use concrete situations and consequences instead of lists of adjectives.
- Allow a playful line to sit beside serious prose without changing the whole voice into comedy.
- Prefer one precise invitation to a cluster of competing calls to action.

## Do's and Don'ts

### Do

- Keep feature headlines at 36px/40px and weight 400.
- Use Caslon 22px/28px titles above 17px/24px descriptions in story cards.
- Align desktop collections to 64px page margins with 32px gutters.
- Use 1px light rules and 16px heading top padding to establish editorial chapters.
- Preserve a 500px centered text measure within split features.
- Pair square-edged documentary images with original line-art moments.
- Keep masthead conversion compact at 23px high with 1px corners.
- End with a concise conversion banner and a dark, ruled directory.

### Don't

- Do not make every title a bold grotesk; sans-serif is the service layer.
- Do not spread #db3334 across backgrounds; it is a small rubric color.
- Do not add 16px corners to ordinary story cards; that radius belongs to activity tiles.
- Do not give story collections raised panels or drop shadows.
- Do not enlarge the masthead action into a 48px-tall primary hero button.
- Do not force all images into the same shape; retain the contrast between 4:3 cards, narrow portraits, and immersive cover scenes.
- Do not center every card's prose; standard four-column cards remain left aligned.
- Do not use the pastel activity palette for the whole marketing canvas.

## Motion and responsive

### Motion

**Observed:**

- Category links declare color, background, and text-shadow transitions of 0.2s ease-in-out. Footer links declare color 200ms.
- Compact subscription controls declare background and color changes including 0.1s cubic-bezier(0, 0.59, 0.32, 1) rules.
- No editorial entrance animation is established.

**Transfer:**

- Keep the interaction emphasis on link underlines and restrained color changes, not on animated editorial entrances.

**Unknown:**

- Actual timing of masthead compaction, carousel travel, and video playback behavior is not established.

### Responsive

**Observed:**

- Desktop layout uses a 12-column grid with 64px side padding. Declared width breakpoints include 720px, 768px, 1024px, and 1280px; additional nearby breakpoint variants exist.
- Horizontal shelves visibly continue beyond the right edge at desktop.

**Transfer:**

- On narrow layouts, preserve the difference between reading collections and sideways shelves: stack reading content while keeping activity cards as a legible horizontal sequence.
- Move cover copy out of busy imagery when needed, maintaining the subject, the centered text block, and their narrative relationship.

**Unknown:**

- Mobile typography, precise breakpoint behavior, and mobile masthead arrangement are not established. The narrow-layout rules are adaptation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
