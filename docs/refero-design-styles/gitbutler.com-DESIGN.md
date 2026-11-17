# GitButler — serif swagger meets terminal

## Overview

An approachable developer-tool aesthetic with narrow, expressive editorial serifs over warm off-white paper. Charcoal product windows and practical sans-serif detail keep the page technical, while aqua grain, italic phrases, marker swashes and a playful ink illustration add personality. It suits software and workflow products that need tangible demonstrations rather than abstract futurism; the overall composition is airy, with dense information contained inside orderly panels.

### Essentials

- Headlines have a tall, literary voice rather than a software grotesk: But Head at 82px/1 for the main promise and 60px/1 for section headings, weight 400, with meaningful phrases in true italic.
- The opening is an inset editorial column, not a centered billboard: an 847px product-and-copy spine sits inside a 1280px stage at a 1440px viewport; the two-line headline is followed by a pill selector beside support copy, oversized action tiles, and a dark application window.
- Conversion controls feel like small objects: the main action is a 467px by 123px rounded rectangle with a 48px serif label and 14px mono secondary line; its companion is an outlined 180px by 123px tile. Mode controls use 100px radii and 40px serif labels.
- Color arrives in substantial but isolated aqua islands: most of the page remains #f3f2f1 with #1c1917 ink; a #d3f3f3 proof panel, #25b1b1 conversion panel and #8dd9d9 illustrated ending carry the chromatic emphasis rather than every card.
- Technical proof is staged as a real instrument: an 847px-wide charcoal window has a white 34px title bar, 20px corners, 24px internal padding and a deep downward shadow. Use an equally concrete workflow preview when a terminal is not relevant.
- Handmade marks interrupt the orderly grid: translucent irregular swashes underline italic emphasis and a short reassurance; broad grainy aqua fields soften proof and conversion panels. Keep these devices even when the subject changes.
- The ending stays useful and playful: a broad illustrated action banner sits beside a narrow utility-link column, separated by 60px. An original cream-and-black line character supplies the human wink; use a simple ink-drawn object with personality if there is no mascot.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Turquoise | `#25b1b1` | `--color-conversion-aqua` | background, action | Large conversion-panel base and small account action. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep aqua | `#1d8a8a` | `--color-aqua-ink` | text | White conversion-tile label and white status-chip text against turquoise. |
| Illustration aqua | `#8dd9d9` | `--color-ending-aqua` | background | Illustrated utility banner behind cream-and-black artwork. |
| Pale aqua detail | `#9fe4e4` | `--color-aqua-detail` | text, border | Mono secondary line in the dark action tile at 0.8 opacity, and companion-tile outline on turquoise. |
| Pale aqua | `#d3f3f3` | `--color-proof-aqua` | background | Large proof-panel base, under a pale grainy light field. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft charcoal | `#3a3532` | `--color-raised-charcoal` | surface, action | Main action tile and selected mode; inset terminal illumination. |
| Warm ink | `#1c1917` | `--color-ink` | text | Headlines, navigation, card labels and light-surface icons. |
| Terminal charcoal | `#272321` | `--color-charcoal` | surface | Dark product demonstration body. |
| Taupe text | `#7c716a` | `--color-muted` | text | Supporting paragraphs, secondary links and low-emphasis iconography. |
| Warm hairline | `#cac6c3` | `--color-rule` | border | Shared feature dividers, table edges and outlined controls. |
| Warm paper | `#f3f2f1` | `--color-canvas` | background, surface | Main page canvas, table header and feature cells. |
| White | `#ffffff` | `--color-white` | text, surface | Table rows and application title bars; reversed headlines and the light conversion tile on aqua. |

## Typography

- **But Head** — Headlines, large actions and wordmark-style lettering. Tall, narrow, high-contrast serif with expressive italic forms and compact horizontal proportions. If unavailable, use **Instrument Serif**. Use regular and italic at 400; tune wrapping to preserve the narrow editorial silhouette. Font stack: "But Head", "Instrument Serif", serif.
- **Inter** — Navigation, paragraphs, feature labels, comparison data and utility links. Matter-of-fact sans-serif, regular for explanations and semibold for functional labels. Font stack: "Inter", sans-serif.
- **Geist Mono** — Command-like secondary lines and technical demonstrations. Clean small monospace that separates operational detail from marketing prose. Font stack: "Geist Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | But Head | 400 | 82px | 1 | -0.01em | Opening promise, usually split into two lines. |
| display-emphasis | But Head | 400 italic | 82px | 1 | -0.01em | A meaningful phrase inside the opening promise, backed by a marker swash. |
| closing-display | But Head | 400 | 82px | 1 | normal | White conversion-panel headline. |
| closing-emphasis | But Head | 400 italic | 82px | 1 | normal | Italic phrase within the conversion-panel headline. |
| heading | But Head | 400 | 60px | 1 | normal | Section headings, paired inline with italic words. |
| heading-emphasis | But Head | 400 italic | 60px | 1 | normal | Editorial emphasis inside section headings. |
| banner-heading | But Head | 400 | 60px | 1.1 | normal | Illustrated ending title; a short internal word can take italic at the same metrics. |
| action-title | But Head | 400 | 48px | 1 | normal | Oversized primary action tile label. |
| serif-control | But Head | 400 | 40px | 1 | normal | Mode-selector labels and all-items action. |
| feature-title | Inter | 600 | 18px | 1.2 | normal | Feature-cell headings. |
| body | Inter | 400 | 16px | 1.5 | normal | Opening support text and companion action labels. |
| section-body | Inter | 400 | 16px | 1.6 | normal | Longer section introductions and conversion-panel support. |
| utility-link | Inter | 400 | 16px | 1.2 | normal | Platform choices and footer navigation. |
| data-label | Inter | 500 | 15px | 1.2 | normal | Comparison feature names and status-chip label. |
| reassurance | Inter | 400 | 15px | 1.6 | normal | Centered two-line reassurance below a proof panel. |
| card-body | Inter | 400 | 15px | 1.5 | normal | Compact feature explanations. |
| code | Geist Mono | 400 | 14px | 1.5 | normal | Command secondary lines and product demonstration text. |
| navigation | Inter | 500 | 14px | 1.2 | normal | Top-level navigation links. |

**Notes:**

- Keep the display face at weight 400: its narrow silhouette, large size and italic contrast do the hierarchy work.
- Use -0.01em only for the opening display. Section and conversion headings retain normal tracking.
- Do not turn every heading into italic; alternate roman and italic inside the same sentence. Sans-serif remains the functional voice.
- The 15px data and reassurance recipes are distinct from the 15px feature-body recipe.

## Layout

**Density:** Airy outside the panels, compact inside them: a broad reading spine and regular section gaps contain tightly organized feature and comparison information.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Primary tile label-to-command gap and adjacent carousel controls. |
| 8px | Pill-selector padding and tight title-to-description spacing. |
| 12px | Gap between primary and companion action tiles. |
| 16px | Media-rail gaps and utility-row separation. |
| 20px | Navigation link gaps and companion-tile padding. |
| 24px | Feature-cell and demonstration-body padding. |
| 30px | Section-heading bottom margin. |
| 32px | Hero support-row gap, headline bottom margin and spacing before the product window. |
| 40px | Opening navigation top inset and separation before action tiles. |
| 58px | Vertical padding in colored proof and conversion panels. |
| 60px | Major section gap and ending banner-to-links gap. |
| 80px | Desktop page side padding and bottom clearance. |

### Containers and grids

- **page-stage**: max width 1440px · 12 columns · gap 20px · side padding 80px. Centered desktop stage. Twelve tracks produce a 1280px full content width; narrow content occupies the middle eight tracks.
- **reading-spine**: max width 847px. Left-aligned promise, section headings, demonstration windows and comparison table. Broader grids and colored panels extend outside this spine.
- **feature-matrix**: 3 columns · gap 0px. Equal feature cells sharing dividers inside one rounded outer frame, rather than isolated floating cards.
- **comparison-columns**: 3 columns · gap 0px. A half-width descriptive column and two quarter-width result columns; row content follows a 2:1:1 ratio.
- **support-copy**: max width 520px. Hero paragraph beside the mode selector; conversion headline and reassurance can extend to 600px.
- **ending**: gap 60px. A 959px illustrated action banner beside a 261px utility column.

## Corner radius

| Element | Radius |
| --- | --- |
| major-panels | 20px |
| comparison-table | 16px |
| mode-selector | 100px |
| carousel-controls | 60px |
| account-actions | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| demonstration-window | `0px 1px 6px 0px rgba(0, 0, 0, 0.1), 0px 24px 44px 3px rgba(0, 0, 0, 0.2)` | Lift the product window off warm paper; do not apply to every panel. |
| terminal-inset | `0px 4px 100px 0px #3a3532 inset` | Subtle warm illumination inside the charcoal demonstration. |
| action-inset | `0px -36px 54px 0px rgba(0, 0, 0, 0.2) inset` | Dim the bottom of the dark conversion tile. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #f3f2f1; color: #1c1917`

#### Shared outline · level 1

**Use:** Feature matrices and companion tiles.

**CSS:** `border: 1px solid #cac6c3; border-radius: 20px; overflow: hidden`

**Observed:** The page canvas shows through; feature cells share rules.

**Transfer:** Group related capabilities in one frame rather than giving each its own shadow.

#### Pale proof island · level 0

**Use:** High-information proof against a soft chromatic field.

**CSS:** `background: #d3f3f3; border-radius: 20px; padding: 58px 32px; overflow: hidden; position: relative`

**Observed:** Very broad pale grainy swirls pass behind a crisp white table.

**Transfer:** Keep the table or proof artifact opaque and the surrounding field soft.

#### Turquoise conversion island · level 0

**Use:** High-emphasis action zone.

**CSS:** `background: #25b1b1; border-radius: 20px; padding: 58px 32px; color: #ffffff; overflow: hidden; position: relative`

**Observed:** A darker grain field adds depth without glowing edges; the action tile reverses to white.

**Transfer:** Use a bounded saturated area, not a full-site dark theme.

#### Illustrated ending field · level 0

**Use:** Utility conversion banner.

**CSS:** `background: #8dd9d9; border-radius: 20px; overflow: hidden`

**Observed:** Pale stippled clouds sit behind the typography and cream-and-black figure.

**Transfer:** Preserve contrast and a wide text area beside the drawing.

#### Terminal interior · level 1

**Use:** Operational product preview.

**CSS:** `background: #272321; padding: 24px; box-shadow: 0px 4px 100px 0px #3a3532 inset`

**Observed:** A white title bar caps the warm dark body.

**Transfer:** Reserve dark material for the product artifact and its related action.

## Components

### Navigation link

**Use:** Compact desktop navigation.

**CSS:** `display: flex; align-items: center; gap: 6px; color: #1c1917`

**Text style:** `navigation` — Inter 500 · 14px/1.2

**Observed:** Links form a horizontal group with 20px gaps; occasional small service icons trail the text. The wordmark anchors the left side.

**States:** Declared: hover adds underline and retains dark ink; focus-visible uses a 2px theme-accent outline with -2px offset.

### Mode selector

**Use:** Switch between two product views or usage modes.

**CSS:** `display: flex; gap: 4px; padding: 8px; border: 1px solid #cac6c3; border-radius: 100px`

**Text style:** `serif-control` — But Head 400 · 40px/1

**Observed:** The selected label sits over a soft-charcoal pill with white text; the other label remains dark on paper. Each label has 12px 20px padding.

**Transfer:** Use only for meaningful parallel experiences, not as a decorative badge.

### Primary action tile

**Use:** Prominent conversion with operational detail.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 6px; padding: 24px 40px 24px 24px; background: #3a3532; color: #ffffff; border-radius: 20px; box-shadow: 0px -36px 54px 0px rgba(0, 0, 0, 0.2) inset`

**Text style:** `action-title` — But Head 400 · 48px/1

**Observed:** A large serif label sits above a code secondary line; a terminal/copy icon occupies the upper right. On turquoise, the tile reverses to white with deep-aqua lettering.

**States:** Declared: focus-visible uses a 2px theme-accent outline with -2px offset; background transition is 0.2s.

**Transfer:** For non-command products, use a short operational next step in the secondary line instead of fake code.

### Companion action tile

**Use:** Secondary route alongside the primary conversion.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 20px; width: 180px; height: 123px; box-sizing: border-box; border: 1px solid #cac6c3; border-radius: 20px; color: #7c716a`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** A small open-book icon sits above a bottom row of label and thin right arrow. On turquoise the outline changes to pale aqua and text reverses.

**Transfer:** Keep the companion visibly smaller and quieter than the primary tile.

### Demonstration window

**Use:** Concrete product proof.

**CSS:** `display: flex; flex-direction: column; max-width: 847px; border-radius: 20px; overflow: hidden; box-shadow: 0px 1px 6px 0px rgba(0, 0, 0, 0.1), 0px 24px 44px 3px rgba(0, 0, 0, 0.2)`

**Text style:** `code` — Geist Mono 400 · 14px/1.5

**Observed:** A 34px white bar includes three small window dots at left and a centered app title. Terminal interior follows below; the opening version is 400px tall and a later example 300px tall.

**Transfer:** Show one real task in a recognizable application frame; simplify the task rather than using an empty decorative window.

### Feature cell

**Use:** Compact capability explanation within a shared matrix.

**CSS:** `display: flex; flex-direction: column; padding: 24px; border-right: 1px solid #cac6c3; border-bottom: 1px solid #cac6c3; position: relative`

**Text style:** `feature-title` — Inter 600 · 18px/1.2

**Observed:** A muted icon precedes an 18px semibold label and short 15px explanation. A small bracketed learn-more indicator belongs at the upper right. Outer cells omit redundant rules.

**States:** Declared: hover changes background to hsl(60 7.7% 97.5%); focus-visible uses a 2px theme-accent outline with -2px offset; background-color transition is .05s ease.

**Transfer:** Use brief capability names followed by the practical result, not long pitch paragraphs.

### Comparison table

**Use:** Scannable proof of a practical difference.

**CSS:** `background: #ffffff; border: 1px solid #cac6c3; border-radius: 16px; overflow: hidden; position: relative`

**Text style:** `data-label` — Inter 500 · 15px/1.2

**Observed:** A paper-colored header caps white rows about 61px high. Labels have 20px 24px padding, with small thin check/cross marks centered in the two result columns.

**Transfer:** Keep criteria concrete and comparison claims supportable; use concise text where binary marks would mislead.

### Carousel action

**Use:** All-items route alongside directional media controls.

**CSS:** `display: flex; align-items: center; gap: 10px; padding: 10px 14px 10px 16px; border: 1px solid #cac6c3; border-radius: 60px; color: #1c1917`

**Text style:** `serif-control` — But Head 400 · 40px/1

**Observed:** The text action sits beside narrow outlined arrow capsules, about 55px by 65px; the unavailable direction is faded.

**States:** Declared: focus-visible uses a 2px theme-accent outline with -2px offset; padding transition is 0.15s.

### Status chip

**Use:** Short reassurance above the conversion headline.

**CSS:** `background: #ffffff; color: #1d8a8a; border-radius: 100px; padding: 8px 12px`

**Text style:** `data-label` — Inter 500 · 15px/1.2

**Observed:** An inline terminal-prompt prefix gives a technical wink; the chip is followed by a 16px gap before the headline.

### Platform link row

**Use:** Useful choices inside the illustrated ending.

**CSS:** `display: flex; align-items: flex-start; gap: 24px; margin-bottom: 16px`

**Text style:** `utility-link` — Inter 400 · 16px/1.2

**Observed:** A 28px dark platform icon precedes underlined text. Related package choices share a row rather than becoming separate buttons.

**States:** Declared: focus-visible uses a 2px theme-accent outline with -2px offset; footer links can underline with a turquoise decoration on hover.

**Transfer:** For another product, substitute short distribution or next-step choices while preserving the icon-plus-link construction.

## Imagery and graphics

### Grainy aqua light fields

**Use:** Signature atmosphere within proof, conversion and illustrated utility panels.

**Observed:** Broad diagonal swirls of pale light and darker aqua are visibly stippled, not smooth neon gradients. They sit behind the content and occupy much of each panel without obscuring it. Light-field layers use 0.5 opacity in proof and 0.4 in the ending; dark-field layers use 0.14 in conversion.

**Transfer:** Rebuild the granular light pattern rather than requiring a specific image. Match the soft tonal spread; exact gradient stops are not essential.

**Build:** Clip oversized elliptical fields inside a 20px rounded panel. Over a pale-aqua or turquoise base, layer two diagonally opposed radial white-to-transparent ellipses, each roughly panel-width and taller than the panel; soften edges with a 60px blur. Add monochrome SVG fractal-noise texture using feTurbulence, masked by the same gradients. Use the light or dark layer opacity appropriate to the panel; keep text and white proof cards above all texture.

### Marker swashes

**Use:** Signature emphasis beneath an italic hero phrase and behind a short reassurance.

**Observed:** The hero has a pale-aqua, irregular overlapping underline roughly the width of the emphasized word; the proof reassurance sits over a bright yellow-green multi-stroke marker patch. Both have uneven ends and slight diagonal displacement, rather than perfect rounded highlights.

**Transfer:** Keep hand-marked emphasis on a small amount of meaningful text; make each mark follow the phrase width.

**Build:** Place an SVG behind the inline phrase with two or three slightly skewed quadrilateral strokes, no outline. For the hero use pale aqua at about half opacity, extending a little beyond both word edges and covering the lower third of the letters. For reassurance use translucent yellow-green strokes behind two lines, offset horizontally and rotated in opposite directions by a few degrees. Keep ink above the strokes.

### Operational product scene

**Use:** Main opening object and later capability demonstration.

**Observed:** A straight-on warm-charcoal application window is backed by bare paper rather than a colored plinth. The window is as wide as the reading spine and visually heavier than the surrounding copy; mono output uses restrained syntax color.

**Transfer:** Show the new product performing a realistic, compact task. For products without an app interface, compose a clear document, workflow or artifact preview in the same white-bar/dark-body frame.

### Editorial video thumbnails

**Use:** Updates or learning-resource rail.

**Observed:** Wide 560px by 315px thumbnails mix oversized narrow serif lettering, cropped application fragments and colored light on dark backgrounds. A red video play mark signals the media format; 16px gaps and horizontal overflow expose a partial next item.

**Transfer:** Use real learning topics and product fragments with a consistent typographic treatment; preserve the wide cinematic ratio, not the exact artwork.

### Ink character ending

**Use:** Signature human counterweight within the final utility banner.

**Observed:** A cream-and-black cartoon figure with oversized accessories, thin outlines and flat fills occupies the right portion of the aqua banner. Its playful pose and a few tiny color accents contrast with the functional links to its left.

**Transfer:** Commission an original line character or anthropomorphic product-adjacent object. The minimum version is a simple cream silhouette with dark expressive linework and one playful prop, not a glossy stock illustration.

**Build:** Create an SVG in a roughly 320px by 336px artboard: cream flat body shapes, dark contour paths, a few solid black clothing or accessory shapes, sparse aqua accents and small ground-motion strokes. Anchor it to the banner bottom on the right, with no enclosing card or drop shadow.

### Icons

**Observed:** Functional icons are small and understated: 16px inline navigation marks, 22px arrows, 24px feature symbols and 28px platform silhouettes. Outline icons generally use 1.5px strokes with butt caps; muted taupe dominates outside colored panels.

**Transfer:** Use a coherent thin-stroke set for controls and simple filled silhouettes for platform identities. Keep arrows light and elongated rather than heavy chevrons.

## Section recipes

How recurring sections are built.

### First screen: Editorial instrument opening

**Observed:** Warm Paper canvas supports a narrow left-aligned reading spine inset from the full-width stage. Navigation begins with a serif wordmark and ends with small account controls, with a 40px top inset. After 52px, the two-line 82px promise occupies roughly the left two thirds of the spine; its final italic phrase overlaps a pale marker swash. A 32px gap leads to Mode selector on the left and a 520px support paragraph on the right. Primary action tile and Companion action tile follow with a 12px gap and 40px separation from that row. After another 32px, Demonstration window fills the spine. Within the first 900px the navigation, entire headline, support row, both actions, white title bar and upper dark product scene are visible; the window bottom and subsequent feature tiles fall below the fold. The layers are paper, marker art, ink type and controls, then the raised product artifact.

**Transfer:** Retain a strong two-line editorial promise, an italic phrase, practical support and an oversized action pair. Replace the terminal with a real task artifact if the product is not command-oriented. Other page types can shorten the object stage but should keep the serif/italic headline and inset reading alignment.

**Avoid:** Do not replace this composition with a centered sans-serif slogan, two generic small pill CTAs and a floating gradient orb.

**Text style:** `display` — But Head 400 · 82px/1 · tracking -0.01em

### Heading and shared feature matrix

**Observed:** An inline roman/italic 60px heading sits on the reading spine, with 30px bottom margin. Shared outline expands to the full 1280px stage and contains three columns with no gutters. Feature cell supplies the internal rhythm. A later chapter uses the same grid with an introduction and a Demonstration window below.

**Transfer:** Use a concise editorial heading and group related practical capabilities in a joined matrix; vary the number of rows with content.

**Text style:** `heading` — But Head 400 · 60px/1

### Chromatic proof island

**Observed:** Pale proof island contains a reading-spine heading, Comparison table and a centered two-line reassurance 32px below the table. Grainy aqua light fields remain behind the table; Marker swashes highlight the reassurance.

**Transfer:** Apply this treatment to comparisons, quantified proof or another highly structured proof artifact. Keep the short confidence-building line and hand-marked emphasis.

**Text style:** `heading` — But Head 400 · 60px/1

### Media rail chapter

**Observed:** A 60px roman/italic heading shares its row with Carousel action and outlined directional controls. After 30px, a horizontal rail of wide thumbnails extends beyond the reading spine and reveals another partial card. The community heading repeats the same control language.

**Transfer:** Use this construction for tutorials, releases or customer stories, with genuine media filling the rail.

**Text style:** `heading` — But Head 400 · 60px/1

### Bright conversion island

**Observed:** Turquoise conversion island keeps content aligned to the same reading spine. Status chip sits above an 82px white, partly italic question, constrained to 600px. A short white support paragraph follows. The action pair repeats, with Primary action tile reversed to white and its companion outlined in pale aqua.

**Transfer:** Use the bold aqua field to resolve the page into one concrete next step, paired with a lower-commitment route.

**Text style:** `closing-display` — But Head 400 · 82px/1

### Illustrated utility ending

**Observed:** The ending is a two-part horizontal composition: a 959px by 368px Illustrated ending field with 36px 48px inner padding, and a narrow utility column after 60px. The banner has a 60px title, Platform link rows and two smaller help lines, while Ink character ending occupies its right side. The utility column groups social links, a thin horizontal rule, site navigation, legal detail and a tiny theme selector. There is 80px clearance below.

**Transfer:** Keep the illustrated action banner and compact link column as distinct neighbors. Replace platform downloads with distribution, onboarding or resource choices relevant to the new product; preserve the functional ending rather than turning it into only a slogan.

**Text style:** `banner-heading` — But Head 400 · 60px/1.1

## Page flow

**Storyline:** Promise and task preview → practical capabilities → structured proof → deeper workflow demonstration → learning and community → decisive action → illustrated utility ending.

### A product landing page that makes a technical workflow feel useful, legible and personable

1. **Promise** — Inset editorial headline, mode choice, benefit copy and oversized action tiles.
2. **Product demonstration** — A raised dark application window shows the tool in use.
3. **Capability overview** — Joined three-column feature matrix, introduced by a roman/italic heading.
4. **Structured proof** — White comparison table inside a pale grainy aqua island, with a highlighted reassurance.
5. **Capability depth** — Short technical introduction, another feature row and operational example.
6. **Learning and social proof** — Wide video resources and a community-voices heading with rail controls.
7. **Closing call** — Bright turquoise panel repeats the editorial headline language and action pair in reverse colors.
8. **Utility ending** — An illustrated aqua action banner sits beside compact social, site and legal links.

**Transfer:** Adapt the narrative to the product's strongest evidence; preserve the contrast between editorial promise, concrete instrument, structured proof and playful useful ending without requiring the same number of chapters.

## Writing

Confident and practical, with a little conversational play. Technical claims are tied to workflows and concrete consequences rather than grand statements about innovation.

**Do not copy:** Do not reuse GitButler names, wordmark, mascot, product commands, benchmark figures, compatibility claims or community-size claims. Replace them with the new product's identity and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your' in promises and reassurance; name the product when explaining what it does. First-person plural is uncommon.
- **Rhythm:** Headlines are short sentence-case phrases, often 3–8 words, with an italic verbal turn. Feature descriptions use one or two plain sentences; actions are direct and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the job, then the audience or context; emphasize the final phrase. | 4–8 words | “Version Control for your Agents” |
| Section heading | A conversational phrase mixing utility with a lightly playful italic turn. | 2–7 words | “Everything You Wished Git Had”<br>“What But gives you over Git” |
| Feature explanation | State a recognizable frustration, then the practical result. | 1–2 short sentences | “Made a mistake? No problem. Undo and redo any operation, even after commits.” |
| Reassurance | Affirm compatibility and reduce the cost of trying. | 2 short lines | “Zero configuration required. It simply layers onto your current workflow.” |
| Primary action | Literal verb plus the thing received. | 2–5 words | “Get the But CLI”<br>“View docs” |
| Closing headline | A friendly question about improving the reader's work. | 4–7 words | “Ready to Level Up Your Workflow?” |

**Words and phrasing to use:** workflow; works with; built for; simple; predictable; undo; no problem; get; view

**Avoid:** revolutionary; unleash limitless potential; magical AI; synergy; disrupt everything

**Rules:**

- Lead with a job the reader recognizes, not the technology category alone.
- Pair technical terminology with a plain-language consequence.
- Use quantified benefits only with an accessible supporting reference.
- Keep button labels descriptive; put operational detail in the smaller secondary line.
- Let a headline or short question carry the humor; keep technical explanations literal.

## Do's and Don'ts

### Do

- Keep display lettering at weight 400 and preserve real italic contrast within headlines.
- Align the 847px reading spine consistently while allowing matrices and color panels to expand to 1280px.
- Use 20px corners for major panels and 16px corners for the comparison table.
- Keep paired conversion tiles 12px apart and give them visibly different visual weight.
- Reserve the deep downward shadow for the product window; let feature grids rely on 1px shared rules.
- Use 24px feature-cell padding and 15px/1.5 descriptions for compact practical explanations.
- Keep colored islands granular and broad, with opaque readable content above them.
- End with an illustrated utility banner and a compact adjacent navigation area, not a bare legal strip.

### Don't

- Do not substitute a wide geometric sans for the narrow serif display voice.
- Do not increase heading weights to 600 or 700 to create emphasis; use the italic recipe.
- Do not split the shared feature matrix into widely spaced shadow cards.
- Do not apply turquoise to every feature cell; keep most information on warm paper or white.
- Do not round tables to pill shapes; preserve their 16px outer corners and square internal rows.
- Do not turn the 123px-tall primary action tile into an ordinary 44px CTA.
- Do not extend terminal syntax colors into marketing headline text.
- Do not replace the cream-and-black ink illustration with glossy 3D, photorealistic mascots or a generic gradient blob.

## Motion and responsive

### Motion

**Observed:**

- Declared feature-cell background transitions use .05s ease; primary tile background uses 0.2s; carousel padding uses 0.15s; selector text color uses 0.2s.
- The opening product scene presents terminal typing and a cursor; exact playback sequencing is not established.

**Transfer:**

- Keep control feedback quick and local. If demonstrating a task through typed output, keep the interface frame stable while its contents change.

**Unknown:**

- Exact demonstration playback timing, scroll-trigger choreography and keyframe behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 500px, 700px, 740px, 1024px, 1025px, 1100px and 1280px.

**Transfer:**

- On narrow screens, preserve the headline's roman/italic contrast and swash while reducing its scale to fit meaningful lines.
- Stack the selector and support text, then the action tiles; let feature cells collapse without losing their shared frame. Place the utility-link column below the illustrated banner and keep the drawing from overlapping choices.

**Unknown:**

- Only the desktop composition is established; mobile type sizes, navigation behavior and exact breakpoint assignments are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
