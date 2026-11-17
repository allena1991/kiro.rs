# LocalCan — a ruled digital workbench

## Overview

A warm stone-colored technical workbench punctuated by forest-green stages and near-black product demonstrations. Light monospace headlines and tightly tracked sans-serif section titles give developer tooling a tactile, approachable character. Real interfaces dominate the imagery, with pixel graphics, fine grid lines and retro diagram objects adding personality without making the content feel decorative or crowded.

### Essentials

- A framed workbench rather than an endless white canvas: a 1280px centered frame with 1px side rules, warm #e7e5e4 ground and 8px gutters around 12px-radius stages.
- The opening reads like a terminal poster beside a miniature visual laboratory: equal-width columns inside a #0b1d0b stage, a 50px/1 monospace headline at weight 350 and -0.05em tracking, with 24px gaps between its main text blocks.
- Actions resemble small keyboard controls: 44px-high buttons with 8px corners, 13px 22px padding and 16px/1 semibold sans text; primary and secondary actions sit together, with 24px shortcut keycaps on the main stages.
- Color belongs to contained demonstrations, not every section: stone neutrals carry most of the long page; forest green anchors the opening and final call, black marks advanced demonstrations, and mint #a7e68f is concentrated in the closing action and pixel artwork.
- Product proof is monumental but literal: numbered chapters pair 42px sans headings with 42px mono numerals above broad interface videos, on #d6d3d1 panels rather than floating cards on white.
- Technical personality comes from a ruled graphic and a pixel mound: retain a thin-line visual grid with playful technical objects and a mint square-pixel formation in a green callout. When product imagery is unavailable, draw a simple input→product→output diagram and populate the opening grid with meaningful outline symbols and a tightly cropped human or material image.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Diagram green | `#2b5a43` | `--color-board` | background | The textured, gridded explanatory diagram. |
| Diagram rules | `#6b8c7b` | `--color-board-rule` | border | Fine grid lines on the green diagram. |
| Deep forest | `#0b1d0b` | `--color-forest` | background, text | Opening and closing stages; text on the mint button. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pixel mint | `#a7e68f` | `--color-mint` | accent, action | Closing button and square-pixel artwork. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, action, background | Text on dark backgrounds and the light primary button; full-page ground only for the comparison landing variant. |
| Demo charcoal | `#171717` | `--color-night` | background | Advanced interaction and team dashboard stages. |
| Stone ink | `#1c1917` | `--color-ink` | text, action | Headings, dark buttons and dark label strips. |
| Warm gray text | `#57534e` | `--color-body` | text, link | Paragraphs, navigation and footer links. |
| Chapter gray | `#78716c` | `--color-number` | text | Numbered chapter markers and inactive technical controls. |
| Muted stone | `#a8a29e` | `--color-muted` | text, border | Secondary text on dark stages and quiet outline controls. |
| Sunken stone | `#d6d3d1` | `--color-sunken` | surface, border | Card ground, panel edges and section/frame rules. |
| Demo backing | `#d6d3d1` | `--color-demo-back` | background | Warm gray backing behind the large interface videos. |
| Workbench stone | `#e7e5e4` | `--color-canvas` | background, surface, text | Default canvas, testimonial cards and pale support text on forest green. |
| Raised chalk | `#f5f5f4` | `--color-surface` | surface | Pricing columns, inline code and technical code panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| the advanced interaction demonstration | Holographic cyan | `#86efff` | `--color-cyan` | accent | One stop in a short holographic word, not general body text. |
| the advanced interaction demonstration | Holographic violet | `#b699ff` | `--color-violet` | accent | One stop in the holographic word. |
| the advanced interaction demonstration | Holographic green | `#9dffc0` | `--color-holo-green` | accent | One stop in the holographic word. |
| the advanced interaction demonstration | Holographic pink | `#ff9ee9` | `--color-pink` | accent | One stop in the holographic word. |
| the advanced interaction demonstration | Holographic yellow | `#fff6a8` | `--color-yellow` | accent | One stop in the holographic word. |
| comparison landing pages | Comparison black | `#000000` | `--color-black` | text | Comparison text, checkmarks and the top of gradient headlines. |
| comparison landing pages | Olive gradient end | `#676a5d` | `--color-comparison-end` | text | Bottom of the black-to-olive display headline gradient. |
| comparison landing pages | Comparison button gray | `#e5e5e5` | `--color-comparison-gray` | action, border | Pill download button and pale dividing lines. |
| comparison tables | Comparison red | `#ff1414` | `--color-negative` | text | Unavailable capabilities and unfavorable figures; never a page accent. |

## Typography

- **inter** — Navigation, section titles, supporting copy, tables and buttons. Neutral sans-serif with high x-height; unusually tight large headings and intermediate weights. Font stack: "inter", Arial, sans-serif.
- **cascadiaMono** — Opening headline, chapter numbers, command chip, diagram labels and technical text. Softly rounded programmer monospace, light in display use rather than heavy terminal lettering. If unavailable, use **Cascadia Mono**. Use variable weights 300–400 and preserve tight display tracking. Font stack: "cascadiaMono", "Cascadia Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| heading-lg | inter | 600 | 52px | 1 | -0.05em | size clamp(2rem, 1rem + 3.5vw, 3.25rem) | Major section headings and text-led page titles. |
| display | cascadiaMono | 350 | 50px | 1 | -0.05em | size clamp(1.75rem, 1.5rem + 3vw, 3.125rem) | Opening headline in a narrow, multiline left column. |
| diagram-title | cascadiaMono | 300 | 43px | 0.9 | normal | fixed | Two-line title integrated into the green explanatory board. |
| chapter-heading | inter | 600 | 42px | 1.05 | -0.05em | size clamp(1.5rem, 1.3rem + 2.4vw, 2.625rem) | Numbered product demonstration headings. |
| chapter-number | cascadiaMono | 350 | 42px | 1.05 | -0.05em | size clamp(1.5rem, 1.3rem + 2.4vw, 2.625rem) | Two-digit chapter numbers; also the dark interaction stage heading. |
| price | inter | 700 | 36px | 40px | normal | fixed | Prominent pricing figures. |
| closing-line | inter | 450 | 33px | 1.21 | -0.02em | size clamp(1.625rem, 1.3rem + 1vw, 2.0625rem) | Closing headline and its muted continuation; also the team demonstration introduction. |
| stage-support | inter | 400 | 20px | 1.25 | normal | fixed | Short opening and dark-stage descriptions. |
| chapter-support | inter | 400 | 20px | 1.375 | normal | fixed | Product demonstration support text, up to 725px wide. |
| plan-title | inter | 700 | 20px | 28px | normal | fixed | Plan names. |
| faq-question | inter | 500 | 18px | 1.5 | normal | fixed | Accordion question rows. |
| body | inter | 400 | 16px | 1.5 | normal | fixed | General supporting text and testimonials. |
| card-body | inter | 400 | 16px | 22px | normal | fixed | Compact capability descriptions. |
| button | inter | 600 | 16px | 1 | -0.01em | fixed | Standard stage and pricing actions. |
| small | inter | 400 | 14px | 20px | normal | fixed | Reassurance, footer links and plan descriptions. |
| navigation | inter | 500 | 14px | 20px | normal | fixed | Navigation and footer group labels. |
| nav-button | inter | 600 | 14px | 20px | -0.01em | fixed | Compact navigation conversion action. |
| command | cascadiaMono | 350 | 14px | 20px | normal | fixed | Install command and compact technical control labels. |
| equipment-label | cascadiaMono | 400 | 14px | 1 | 0.06em, uppercase | fixed | Black strips identifying capability cards. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| comparison landing pages | comparison-display | inter | 700 | 72px | 1 | -0.02em | fixed | Centered gradient display titles, including the final call. |
| technical guides and trust documents | editorial-heading | inter | 450 | 44px | 1 | -0.05em | size clamp(1.75rem, 1rem + 2.2vw, 2.75rem) | Left-column chapter headings. |
| comparison landing pages | comparison-support | inter | 400 | 24px | 1.4 | -0.03em | fixed | Centered opening deck. |
| technical guides and trust documents | editorial-lead | inter | 450 | 23px | 1.22 | -0.03em | size clamp(1.25rem, 1.1rem + 0.6vw, 1.4375rem) | Introductory deck beneath the title. |
| comparison landing pages | comparison-button | inter | 400 | 18px | 22px | -0.03em | fixed | Pill download action. |
| trust documents | editorial-subheading | inter | 600 | 16px | 1.4 | normal | fixed | Short factual subheads above paragraphs. |
| technical guides and trust documents | editorial-body | inter | 400 | 15.2px | 1.6 | normal | fixed | Dense but comfortably led explanations and technical cards. |
| technical guides | inline-code | cascadiaMono | 350 | 13.6px | 1.55 | normal | fixed | Inline commands in setup instructions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the distinction between light monospace opening type and semibold sans-serif proof headings. Do not turn the whole site into a terminal.
- Large primary headings and chapter numbers share -0.05em tracking; body copy returns to normal tracking. Closing copy is lighter and less tightly tracked.
- Closing headline and continuation share one 33px recipe, distinguished by white versus muted stone rather than size.

## Layout

**Density:** Airy at the chapter level and compact within controls; broad demonstrations alternate with tightly ruled information.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Inset around large stages, capability grid gaps and control icon gaps. |
| 12px | Closing action gap and footer group item gaps. |
| 16px | Stage inner frame inset, opening action gap and testimonial track gaps. |
| 20px | Heading-to-support gap in demonstration chapters. |
| 24px | Opening text-stack gaps, capability-card padding and document paragraph groups. |
| 32px | Pricing-card sides and gap above closing actions. |
| 40px | Opening text-column vertical padding and testimonial-band padding. |
| 48px | Standard content side padding and editorial column gap. |
| 56px | Closing-stage and footer vertical padding. |
| 64px | Demonstration heading inset and trust-document section padding. |
| 80px | FAQ section vertical padding and trust-document opening inset. |
| 120px | Large section introductions and technical-guide chapter top spacing. |

### Containers and grids

- **Ruled frame**: max width 1280px · side padding 16px. Center the whole marketing page inside persistent 1px vertical rules; the outer wrapper retains a minimum side gutter.
- **Stage split**: 2 columns · gap 0px · side padding 16px. Equal halves within the green opening and charcoal interaction stage. Text uses 48px side padding; the visual half is divided into two columns and four rows.
- **Editorial split**: 2 columns · gap 48px · side padding 48px. A narrow heading column beside a broad 722px reading column; relative column weights are 0.8fr and 1.4fr.
- **Capability grid**: 3 columns · gap 8px · side padding 8px. Three equal sunken cards, roughly 415px wide, grouped closely inside the frame.
- **Pricing grid**: 4 columns · gap 1px · side padding 8px. Four chalk columns joined by hairlines and one shared 12px perimeter.
- **Comparison container** (only for comparison landing pages): max width 1152px · side padding 24px. Centered white-page content; tables narrow to 1024px and opening media to 948px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Stage and card perimeter | 12px |
|  | Standard action | 8px |
|  | Keycap and technical inset | 6px |
| technical guides | Inline code | 5px |
| comparison landing pages | Comparison pills | 50px |
| comparison landing pages | Comparison proof cards | 16px |
| comparison landing pages | Comparison explanation panel | 24px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Diagram object | `2px 4px 2px 0px rgba(0,0,0,0.3)` | Small, hard-edged drop shadow on the central diagram object, not on general cards. |
| comparison landing pages | Comparison interface float | `0px 80px 80px 0px rgba(0,0,0,0.03)` | Very faint separation beneath the opening interface image. |

### Surfaces

#### Workbench canvas · level 0

**Use:** Default background and persistent frame.

**CSS:** `background: #e7e5e4; border-left: 1px solid #d6d3d1; border-right: 1px solid #d6d3d1`

**Observed:** Every major section is divided by a matching bottom rule.

**Transfer:** Make the frame continuous through the footer.

#### Forest stage · level 1

**Use:** Opening and closing graphic containers.

**CSS:** `background: #0b1d0b; border-radius: 12px; overflow: hidden`

**Observed:** The opening has a white 30% inset frame; the closing trades the grid for pixel art.

**Transfer:** Keep the deep green as a contained stage against stone.

#### Demo stone · level 1

**Use:** Large numbered interface demonstration panels.

**CSS:** `background: #d6d3d1; border-radius: 12px; overflow: hidden`

**Observed:** Text sits above wide, realistically rendered desktop interfaces.

**Transfer:** Give each proof chapter its own framed demonstration.

#### Charcoal stage · level 1

**Use:** Advanced interaction and team demonstration.

**CSS:** `background: #171717; border-radius: 12px; overflow: hidden`

**Observed:** The interaction variant has an inset white 15% grid; the team variant lets the dashboard fill the lower width.

**Transfer:** Use as a deeper product chapter, not a replacement for the stone page.

#### Chalk panel · level 1

**Use:** Pricing columns and technical code panels.

**CSS:** `background: #f5f5f4; border: 1px solid #d6d3d1`

**Observed:** Pricing uses shared hairlines; code panels have a 10px outer radius and a thin toolbar.

**Transfer:** Favor edges and tone differences over elevation shadows.

#### Technical board · level 1

**Use:** Explanatory system diagram.

**CSS:** `background: #2b5a43; border-radius: 12px; padding: 16px; position: relative; overflow: hidden`

**Observed:** Fine green rules, a diagonal construction line and subtle grain make this feel like a printed instrument board.

**Transfer:** Use the board to explain one relationship or transformation.

#### White comparison canvas · level 0

**Only for:** comparison landing pages

**Use:** More conventional centered comparison presentation.

**CSS:** `background: #ffffff`

**Observed:** Open white margins, neutral gradient headlines and faint gray tables replace the ruled stone frame.

**Transfer:** Keep this a complete page-type variant rather than mixing its pills and giant headlines into the default.

## Components

### Sticky navigation

**Use:** Persistent site identity and compact conversion.

**CSS:** `position: sticky; top: 0px; z-index: 50; height: 63px; padding: 0px 16px; background: rgba(231,229,228,0.8); border-bottom: 1px solid #d6d3d1; backdrop-filter: blur(24px)`

**Text style:** `navigation` — inter 500 · 14px/20px

**Observed:** Small outline identity at left; four short links and a compact dark action at right. Navigation action is 38px high with 8px 16px padding and the nav-button recipe.

**Transfer:** Keep the header inside the ruled frame.

### Primary button

**Use:** Conversion on the opening and dark product stage.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 44px; padding: 13px 22px; background: #ffffff; color: #1c1917; border: 1px solid transparent; border-radius: 8px`

**Text style:** `button` — inter 600 · 16px/1 · tracking -0.01em

**Observed:** A small translucent shortcut keycap follows the label. On light surfaces, the same construction reverses to stone ink with white text; the free plan uses an outline instead.

**States:** Declared: hover adds a 4px white ring at 18% alpha; the dark variant adds a 4px ink ring at 12% alpha.

**Transfer:** Use short verb-led labels; retain the compact rectangular silhouette.

### Secondary button

**Use:** Download or alternate path beside the main stage action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 44px; padding: 13px 22px; background: transparent; color: #ffffff; border: 1px solid rgba(255,255,255,0.35); border-radius: 8px`

**Text style:** `button` — inter 600 · 16px/1 · tracking -0.01em

**Observed:** Outline-only sibling with its own shortcut keycap. On a light background the outline and text become stone gray and ink.

**States:** Declared: hover adds a 4px white ring at 18% alpha.

### Mint button

**Use:** Primary action in the forest closing call.

**CSS:** `height: 44px; padding: 13px 22px; background: #a7e68f; color: #0b1d0b; border: 1px solid transparent; border-radius: 8px; display: flex; align-items: center; gap: 8px`

**Text style:** `button` — inter 600 · 16px/1 · tracking -0.01em

**Observed:** Paired with Secondary button and a small reassurance line below.

**States:** Declared: hover adds 0px 0px 0px 4px rgba(167,230,143,0.3).

### Command chip

**Use:** Compact technical invitation above the opening headline.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; padding: 4px 8px 4px 12px; border: 1px solid rgba(255,255,255,0.3); border-radius: 8px; color: #e7e5e4`

**Text style:** `command` — cascadiaMono 350 · 14px/20px

**Observed:** One monospace command followed by a small copy glyph; 30px overall height.

**Transfer:** For a non-CLI product use an equally concise executable step or functional status, not a decorative category badge.

### Capability card

**Use:** Compact supporting capabilities beneath larger proof chapters.

**CSS:** `display: flex; flex-direction: column; gap: 20px; padding: 24px; background: #d6d3d1; border-radius: 12px; overflow: hidden; position: relative`

**Text style:** `card-body` — inter 400 · 16px/22px

**Observed:** An illustrative symbol occupies the upper area, with an Equipment label and short paragraph aligned toward the bottom. Desktop cards are 360px tall.

**Transfer:** Show one concrete capability per card, with a restrained diagram rather than a generic colored icon tile.

### Equipment label

**Use:** Capability identifier on a black strip.

**CSS:** `display: flex; align-items: center; gap: 2px; padding: 0px 10px 0px 4px; height: 24px; background: #1c1917; color: #ffffff`

**Text style:** `equipment-label` — cascadiaMono 400 · 14px/1 · tracking 0.06em · uppercase

**Observed:** A tiny colored star precedes uppercase mono text; the strip hugs the label rather than spanning the card.

### Pricing column

**Use:** Comparable plans within a joined pricing grid.

**CSS:** `display: flex; flex-direction: column; padding: 24px 32px 32px 32px; background: #f5f5f4`

**Text style:** `body` — inter 400 · 16px/1.5

**Observed:** Plan-title, Price, small description, full-width action, then a checked feature list. One shared rounded perimeter encloses all columns; popular and limited offers use small flat highlight labels. A separate horizontal lifetime offer follows the grid.

**Transfer:** Use the same visual weight for every plan and highlight only the intended recommendation.

### FAQ trigger

**Use:** Objection handling in the broad right column.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 16px 0px; color: #1c1917`

**Text style:** `faq-question` — inter 500 · 18px/1.5

**Observed:** Each trigger sits inside a row with a 1px stone bottom rule; the group also has a top rule. A small 16px chevron is pinned right. Questions wrap without becoming separate cards.

### Testimonial card

**Use:** A horizontally overflowing proof strip.

**CSS:** `display: flex; flex-direction: column; gap: 16px; width: 288px; padding: 16px 20px; background: #e7e5e4; border-radius: 12px; flex-shrink: 0`

**Text style:** `body` — inter 400 · 16px/1.5

**Observed:** Avatar, author and handle above variable-length quote text; cards keep natural heights. The track has 16px gaps and faded edges. Handles can receive a restrained green text highlight.

**Transfer:** Keep the uneven heights and conversational texture rather than forcing a row of equal-size quote blocks.

### Footer link

**Use:** Dense categorized navigation beneath the closing stage.

**CSS:** `color: #57534e; text-decoration: none`

**Text style:** `small` — inter 400 · 14px/20px

**Observed:** Links are grouped with 12px gaps under medium-weight 14px category labels. Three link columns occupy a 672px block to the right of the identity and social links.

**States:** Declared: hover changes text to stone ink.

### Comparison download

**Only for:** comparison landing pages

**Use:** Secondary action on the white centered variant.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 54px; padding: 0px 18px 0px 24px; background: #e5e5e5; color: #000000; border: 1px solid transparent; border-radius: 50px`

**Text style:** `comparison-button` — inter 400 · 18px/22px · tracking -0.03em

**Observed:** Operating-system glyphs follow the label. The paired primary action is a dark green-to-black gradient pill with an arrow; no keyboard keycaps.

**States:** Declared: hover adds a 4px pale gray ring.

## Imagery and graphics

### Opening technical mosaic

**Use:** Right half of the forest opening.

**Observed:** Two columns by four rows of fine outlined cells. Sparse globe and cloud outline symbols alternate with a tightly cropped human face overlaid by pale square pixels; the overall scene remains dark and low-density.

**Transfer:** Use symbols of the new product's inputs and outputs plus one intimate human or material detail. Keep the grid populated with intentional content rather than turning every cell into a feature card.

**Build:** Draw a 2×4 CSS grid with 1px rgba(255,255,255,0.3) shared rules. Center thin mint and warm-orange SVG outlines in selected cells; object-fit:cover a face or relevant material image across a horizontal cell and overlay several small pale square blocks. Keep unifying deep forest behind all cells.

### Desktop interface demonstrations

**Use:** Main proof chapters and team stage.

**Observed:** Large native-window interfaces with rounded window edges and soft realistic shadows, shown nearly full panel width. Warm gray surrounds the light interfaces; a charcoal team dashboard sits on charcoal. These are readable workflows, not device mockups or tiny thumbnail cards.

**Transfer:** Use the new product's real interface in action. If no interface exists, create one faithful, legible workflow illustration with a title bar, sidebar and active detail area; do not invent extensive decorative dashboard metrics.

### Printed system board

**Use:** A signature explanatory diagram within the long-form marketing story.

**Observed:** A green 10-column by four-row construction grid supports a yellow input tag, a lavender-silver square central object and pixel-outline output devices. Thin routes connect them. Grain and hard little object shadows give the diagram a printed, slightly retro hardware feel.

**Transfer:** Explain a real input→transformation→output relationship. Minimum version: a yellow arrow tag, a pale square product block and two outline output symbols connected by lines, on the same green rules and grain.

**Build:** Use #2b5a43 backing with a 16px inset SVG. At desktop draw 123px square cells with #6b8c7b 1px rules, plus one long rising diagonal. Overlay SVG turbulence grain with soft-light blend and 0.4 opacity. Place a rounded yellow arrow tag left, a 230px pale lavender-gray square with a double dark outline and 2px 4px 2px rgba(0,0,0,0.3) shadow centrally, and two pixel-stroke output icons right. Route dashed white and thin yellow-green connectors between them.

### Mint pixel mound

**Use:** Signature graphic in the forest closing call; retain on new marketing pages.

**Observed:** A mint field of hard square pixels rises from the bottom-right edge like a low irregular hill. It occupies the lower/right part of the panel, leaves the left copy readable and is clipped by the panel boundary. No blur or glow.

**Transfer:** Recreate the square-pixel mass rather than substituting a generic gradient blob. Adapt its silhouette to a meaningful abstract output if useful.

**Build:** Create an SVG with a coarse 12px grid and 5–7px square marks in #a7e68f. Increase occupancy toward the bottom, with two uneven hill envelopes rising to roughly half the 304px panel height. Randomize sparse marks above the envelope and merge dense marks near the base. Anchor the field bottom-right across about two thirds of the stage and clip overflow; use image-rendering:pixelated.

### Holographic keyword

**Only for:** the advanced interaction demonstration

**Use:** One emphasized word in the charcoal monospace heading.

**Observed:** Only a short keyword carries a pastel rainbow; the surrounding heading stays white.

**Transfer:** Highlight the capability or actor that makes this chapter different, never an entire sentence.

**Build:** Clip a 110deg linear gradient to text using #86efff, #b699ff, #ff9ee9, #fff6a8, #9dffc0 and #86efff. Use background-size:250% 100% and transparent text fill.

### White comparison diagrams

**Only for:** comparison landing pages

**Use:** Broad product image and explanatory visuals between centered headline sections.

**Observed:** Pale interface images and light line-art device/network diagrams sit directly on white, with sparse green and blue functional cues. The opening interface is 948px wide with a faint long shadow, not a dark illustrated stage.

**Transfer:** Use clean, mostly neutral interface views and one simple relationship diagram; preserve the white margin and restrained color.

### Icons

**Observed:** Small control outlines are usually 16px with 1px round strokes in warm gray; copy glyphs can be 12px. Footer social glyphs are about 14px and filled. Stage diagrams deliberately use larger, simpler and sometimes pixel-stepped outlines.

**Transfer:** Use a consistent light outline set for controls; reserve chunky pixel or retro symbols for the explanatory artwork rather than mixing them into navigation.

## Section recipes

How recurring sections are built.

### First screen: Forest workbench opening

**Observed:** The 63px Sticky navigation sits above a forest panel inset 8px from the ruled frame. The stage is about 600px tall with a 16px inner frame; its two halves share a vertical rule. The left half has 48px side and 40px vertical padding. Command chip leads into a 50px/1 light monospace headline about four lines tall and no more than roughly 469px wide; 24px gaps lead into 20px support, Primary button and Secondary button, then a 14px reassurance line. Opening technical mosaic fills the right half. All headline, copy, actions and mosaic are visible within the first 900px; the trust label and logo strip begin below the stage, while the first large product chapter is farther below.

**Transfer:** For another product, keep the copy-versus-grid balance and create a functional technical mosaic without relying on branded artwork. Text-led guides instead open on stone with breadcrumbs, heading-lg and editorial-lead; comparison pages use the scoped centered white opening.

**Avoid:** Do not replace this with a centered giant sans headline above a floating dashboard, or let the decorative half crowd the compact four-line promise.

**Text style:** `display` — cascadiaMono 350 · 50px/1 · tracking -0.05em

### Ruled social proof

**Observed:** A small centered monospace trust label precedes five equal logo cells with fine shared rules; a longer testimonial follows in a broad stone section.

**Transfer:** Use authentic proof in the same subdued grid, with logos normalized to a single neutral tone.

### Numbered interface chapter

**Observed:** Demo stone contains a two-digit chapter-number beside a chapter-heading and chapter-support. The heading group has 64px top and side insets and a 24px number-to-text gap. A broad 1262×710 interface video fills the lower stage; a 48px translucent round pause control sits near the lower edge.

**Transfer:** Give each major workflow a numbered demonstration, retaining realistic interface scale. The number can establish sequence without requiring a fixed number of sections.

**Text style:** `chapter-heading` — inter 600 · 42px/1.05 · tracking -0.05em

### Dark interaction stage

**Observed:** Charcoal stage uses a 16px inset border and equal halves. A mono heading and description sit above stacked 49px technical action rows on the left; a terminal-like response and prompt panel occupy the right. One keyword receives Holographic keyword.

**Transfer:** Use for an interactive or automation capability. Populate the response with a meaningful example and keep its typography subordinate to the stage heading.

### Capability shelf

**Observed:** A heading-lg introduces Capability grid with Capability card and Equipment label. Cards share a muted sunken ground and keep prose low in the composition.

**Transfer:** Group secondary capabilities by actual jobs rather than repeating the main proof as small tiles.

### System explanation

**Observed:** Technical board is a broad 524px-high diagram with diagram-title integrated into the upper-left cells, not a separate heading above. Printed system board occupies most of the width; a restrained compatibility-logo strip can follow.

**Transfer:** Explain one core transformation visually; preserve the grid, tactile objects and short mono labels.

**Text style:** `diagram-title` — cascadiaMono 300 · 43px/0.9

### Team scale demonstration

**Observed:** Charcoal stage combines a 33px opening phrase in white and a muted continuation at the same size, with a small light action to the right. A wide dark dashboard emerges below and is clipped by the stage.

**Transfer:** Use this construction for collaborative or organizational value, with genuine UI rather than an abstract enterprise illustration.

### Joined pricing and separate offer

**Observed:** Heading-lg, 20px support and a compact monthly/yearly segmented control lead to Pricing grid. Pricing column keeps price and action near the top; checked benefits continue below. A distinct horizontal one-time offer follows beneath the grid.

**Transfer:** Expose the actual billing choice clearly, maintain consistent comparison alignment and separate a structurally different offer from subscription columns.

### Split FAQ

**Observed:** A large left title faces a 722px right-column ruled list of FAQ trigger rows. Standard section padding is 80px vertically and 48px horizontally.

**Transfer:** Ask the questions a buyer would actually raise; keep answers within the reading column.

### Faded testimonial strip

**Observed:** A 12px-rounded sunken band with 40px padding contains a modest heading and a horizontally overflowing row of Testimonial card. Natural heights, 16px gaps and a 4% edge fade create a continuous proof stream.

**Transfer:** Use genuine conversational quotes and preserve the moving-strip silhouette rather than building a tidy centered carousel.

### Pixel closing call and directory footer

**Observed:** Forest stage is inset 8px and about 304px tall, with 56px vertical and 48px side padding. A white closing-line runs into a muted continuation within 672px; Mint button and Secondary button follow after 32px, then small reassurance. Mint pixel mound occupies the lower right. The footer returns to stone with 56px vertical padding, left identity/short description/social row and three categorized link columns on the right. A full-width rule separates the copyright tail.

**Transfer:** End with a concrete outcome and next action, not a new feature chapter. Keep the pixel graphic and the substantial directory footer as distinct visual beats.

**Text style:** `closing-line` — inter 450 · 33px/1.21 · tracking -0.02em

### Text-led technical chapter

**Only for:** technical guides and trust documents

**Observed:** Editorial split pairs an editorial-heading on the left with paragraphs, subheads, numbered steps or ruled tables on the right. Trust-document sections use 64px vertical padding; guide chapters often use 120px above and 40px below. Desktop left headings can stick at 80px from the top while the reading column continues.

**Transfer:** Use the same ruled frame for serious detail. Technical guides add inline code, a copyable syntax panel, factual comparison rows and related-document links; trust documents rely on short factual blocks.

**Text style:** `editorial-heading` — inter 450 · 44px/1 · tracking -0.05em

### Centered comparison narrative

**Only for:** comparison landing pages

**Observed:** White comparison canvas uses centered 72px gradient headings with 16px support gaps, paired 54px pill actions and a broad pale interface image. Successive feature sections center their copy above media. Large 1024px tables use a wide label column and two narrow alternatives, pale gray fills, black checks and red crosses or unfavorable numbers. A 24px-rounded two-column explanatory panel precedes a monumental centered final question, product icon, tagline, paired pills and small reassurance. A ruled multi-column footer follows on white.

**Transfer:** Use this full variant when evaluating alternatives; replace the product icon with the new identity and compare substantiated capabilities rather than marketing adjectives.

**Text style:** `comparison-display` — inter 700 · 72px/1 · tracking -0.02em

## Page flow

**Storyline:** Concrete promise → demonstrated workflow → contextual proof → broader capabilities → practical evaluation → objections resolved → outcome-led closing action and directory.

### Broad product marketing landing

1. **Promise** — Forest split stage with command, audience-oriented mono headline and paired actions.
2. **Social proof** — Ruled logo shelf and a substantial customer quote.
3. **Product demonstration** — Numbered broad workflow panels, followed by a dark interactive capability chapter.
4. **Capability expansion** — Three-card shelf, printed system diagram and compatibility strip.
5. **Organizational value** — Dark collaborative dashboard demonstration.
6. **Pricing** — Joined plan grid, billing toggle and a separate one-time offer.
7. **Objection handling** — Split FAQ and faded testimonial strip.
8. **Closing action** — Mint-pixel forest callout followed by a stone directory footer.

**Transfer:** Borrow the alternation of broad demonstrations and compact decision aids; choose the number and order of proof chapters to fit the product.

### Trust and technical accountability document

1. **Promise** — Breadcrumb, concise title, factual deck and update line on stone.
2. **Accountability** — Repeated split chapters with factual subheads, paragraphs and a data table.
3. **Risk resolution** — Operational practices, compliance, reporting commitments and document links.
4. **Closing action** — Contextual forest callout and the shared stone directory footer.

**Transfer:** Replace claims with verifiable operational details while retaining the heading/reading-column split and the same branded ending.

### Use-case guide that converts through useful instructions

1. **Context** — Small green announcement band and standard navigation.
2. **Problem recognition** — Breadcrumb title and deck naming a precise error, with trial and download actions.
3. **Activation** — Numbered short setup steps in the reading column.
4. **Explanation** — Technical rationale followed by three detailed value cards.
5. **Working reference** — Ruled event rows, request-specification table and copyable code panel under sticky left headings.
6. **Evaluation** — Full-width factual comparison table.
7. **Objection handling** — Split FAQ and related-guide links.
8. **Closing action** — Error-to-outcome forest callout and shared directory footer.

**Transfer:** Let the guide solve a real task before asking for conversion; tie the closing sentence to the problem named in the opening.

### Alternative-product evaluation landing

1. **Positioning** — Centered gradient headline, plain-value deck, pill actions and a pale interface image.
2. **Social proof** — Ratings, overlapping avatars and a faintly cyan-backed masonry quote wall.
3. **Capability demonstration** — Centered feature titles above broad interface and network diagrams.
4. **Evaluation** — Two large neutral comparison tables with explicit numeric and capability differences.
5. **Economic consequence** — Rounded two-column explanation showing how differences compound.
6. **Closing action** — Oversized centered question, product icon and pills, then a white multi-column footer.

**Transfer:** Keep this as a scoped white comparison design; preserve factual comparison and the large closing question without importing the default forest stage into every block.

## Writing

Direct, technically literate and practical, with a human builder's confidence rather than enterprise grandiosity. Benefits are explained through concrete actions, constraints and consequences.

**Do not copy:** Do not reuse LocalCan's name, logo, interface artwork, customer identities or quotations, usage statistics, prices, trial terms, legal commitments, competitor claims or product-specific assertions. Replace these with substantiated content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for the reader's workflow; use we and our for operational responsibility. Product names appear as subjects only when needed for clarity.
- **Rhythm:** Short action-led headings alternate with explanatory paragraphs. Benefits often arrive in two sentences: do the thing, then explain the friction removed. Technical guides can become denser while maintaining literal nouns and verbs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the useful object or outcome, then who it serves. | 6–10 words | “Public URLs for developers, designers and agents.” |
| Capability heading | A direct action and the friction it removes. | 3–7 words | “Share it without deploying”<br>“Share the link, get feedback.” |
| Supporting copy | Concrete workflow followed by a reason it is faster or safer. | Two short sentences | “Point Stripe, Clerk, or GitHub at a stable Public URL and watch every delivery land in the inspector. Replay a failed request instead of re-triggering the provider.” |
| Trust heading | An ordinary phrase promising a factual answer, not a certification slogan. | 3–6 words | “What we can see”<br>“How we run production” |
| Instruction heading | An explicit time-to-task or task description. | 2–6 words | “30-second setup” |
| Closing line | A compact outcome or a conversational release from the page's problem. | 4–9 words | “Twelve seats. One bill.”<br>“Review done, now go build.”<br>“Stop guessing why the webhook 401'd.” |
| Action and reassurance | Start or download, then remove a specific commitment concern. | 1–4 words for action; one short reassurance line | “Start building”<br>“Free 14-day trial included. No credit card required.” |

**Words and phrasing to use:** share; inspect; replay; stable; your machine; without deploying; one bill; read; build; exact; kept

**Avoid:** revolutionary; seamless ecosystem; unlock limitless potential; world-class solution; disrupt; magic; synergy

**Rules:**

- Prefer named tasks and artifacts over broad productivity claims.
- State limits and responsibilities plainly; technical caveats increase credibility.
- Use product terminology consistently but explain it through the reader's actions.
- Keep action labels short and put commitment details in the smaller line below.
- Use occasional conversational contractions or a clipped pair of sentences; avoid relentless promotional exclamation marks.

## Do's and Don'ts

### Do

- Use the 1280px continuous ruled frame as the default, with 8px stage gutters.
- Keep the opening mono display at weight 350 and -0.05em tracking, distinct from 600-weight section titles.
- Preserve 12px panel corners and 8px action corners throughout the default design.
- Use 48px content side padding and 48px editorial column gaps at desktop.
- Let demonstrations occupy nearly the full stage width; keep support text to roughly 725px.
- Reserve the mint action for the green closing call and maintain the hard pixel silhouette.
- Keep pricing columns joined by 1px separators, not detached floating cards.
- Use a small reassurance line at 14px/20px under conversion controls.

### Don't

- Do not use pure white as the default long-page canvas; it belongs to the scoped comparison variant.
- Do not give every capability its own saturated background: the three-card shelf is stone-on-stone.
- Do not turn standard 44px rectangular actions into 54px pills; those belong to comparison pages.
- Do not apply the rainbow gradient to full headlines, body text or ordinary links.
- Do not add soft drop shadows to the general capability cards; separation comes from tone, rules and spacing.
- Do not center the standard FAQ or technical chapter text; preserve the narrow-left/broad-right composition.
- Do not scale desktop interface views down into decorative thumbnail tiles.
- Do not replace the 33px mixed-tone closing sentence with another oversized hero headline in the default design.

## Motion and responsive

### Motion

**Observed:**

- Standard stage buttons declare box-shadow, opacity and background-color transitions of 0.2s. Footer links declare 0.15s color transitions with cubic-bezier(.4,0,.2,1).
- The holographic keyword declares a 7s ease-in-out alternate loop. The diagram declares 3s linear route cycles and 18s state cycles.
- Interface demonstrations expose pause controls. The testimonial track is translated horizontally with a grab cursor and edge masking.

**Transfer:**

- Use quiet control rings rather than bouncing or scaling stage buttons.
- Limit continuous motion to the product demonstration, technical route diagram, short holographic word and testimonial strip; preserve legibility of surrounding text.

**Unknown:**

- The exact testimonial speed and complete reveal choreography are unspecified.
- Reduced-motion behavior and actual keyboard shortcuts are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px and 1280px, plus component-specific intermediate widths.
- Opening split is two columns at the large breakpoint; editorial sections switch to one column below the large breakpoint, and sticky headings become static.
- Small-screen opening text padding changes from 48px/40px to 24px/32px. Capability grids move from three to two and then one column; small cards reduce from 360px to 280px high.
- Display sizes use the clamp formulas attached to their recipes.

**Transfer:**

- Stack the opening text before the technical mosaic, retaining its fine shared rules and meaningful symbols.
- Keep the pixel mound clipped to the lower/right edge while protecting the closing action area.
- Preserve readable interface details by choosing a focused workflow view rather than shrinking the entire desktop scene.

**Unknown:**

- Actual mobile rendering, table overflow and every intermediate breakpoint behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
