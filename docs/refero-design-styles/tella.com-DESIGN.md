# Tella — luminous creative workbench

## Overview

A light, approachable software style that puts useful work inside softly molded frames, with flashes of digital color rather than heavy branding. Regular-weight grotesk typography and gray supporting lines make the page feel conversational, while interface demonstrations, natural webcam footage and floating app objects supply the energy. It suits creative tools and versatile productivity products, balancing sparse editorial passages with substantial visual demonstrations.

### Essentials

- The promise is deliberately smaller than the product: a left-aligned 32px/1.2 regular headline and equally sized gray support line sit above a nearly full-width demonstration, separated from it by 64px.
- Headlines speak in two tonal registers rather than bold weights: oracle at weight 400 and -0.02em tracking, with black statements and 50%-ink explanations; the centered manifesto grows to 52px/1.2.
- The page behaves like a softly molded workbench: 1300px-wide stages have 32px corners, 16px inner padding, 1px 8%-ink edges and a white inset highlight; real interfaces float inside with 0px 8px 32px 4px soft shadows.
- Conversion is a small violet capsule, not a colored section: primary actions use #5e51f8, white 16px medium text, 44px minimum height and 8px 48px padding; secondary pills are white with a faint outline.
- Digital light interrupts a predominantly near-white page: include a fragmented cyan, magenta, yellow and green glitch field, washed to 20% behind the opening object and brighter around a closing message. Keep the central text zone clear; a layered SVG rectangle field is the fallback when bespoke animated art is unavailable.
- Demonstration gets two thirds of a chapter and explanation one third: 24px headings, 20px/1.5 support and violet text links sit beside oversized clipped interface windows; compact 33px pills can sit beneath the stage.
- A closing invitation becomes a luminous display object: use a 1300px by 420px rounded art panel, a centered 52px/1.08 line and one capsule action, followed by a pale five-column directory rather than an oversized dark footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversion violet | `#5e51f8` | `--color-violet` | action, accent | Primary buttons and small brand emphasis; not the normal page background. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft violet link | `#8278fa` | `--color-link` | link | Learn-more links beneath chapter descriptions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep ink | `#0c0a09` | `--color-deep-ink` | text | Opening headline and action labels. |
| Statement ink | `#111111` | `--color-ink` | text | Main headings, card labels and strong statements. |
| Supporting gray | `#878787` | `--color-muted` | text | Visible result of 50% #111111 over #fdfdfd; supporting paragraphs and the second line of the promise. |
| Faint molded edge | `#eaeaea` | `--color-edge` | border | Visible 8%-ink outlines over the canvas; chapter shells, FAQ rules and card outlines. |
| Panel shade | `#f5f5f5` | `--color-panel-bottom` | surface | Visible lower end of the 3.5%-ink stage gradient over the canvas. |
| Panel light | `#fbfbfb` | `--color-panel-top` | surface | Visible upper end of the 1%-ink stage gradient over the canvas. |
| Near-white canvas | `#fdfdfd` | `--color-canvas` | background | Default page canvas. |
| Window white | `#ffffff` | `--color-white` | surface, text | Floating windows, secondary actions and text on violet. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| consolidation illustrations | Object edge | `#d6d3d1` | `--color-object-edge` | border | Fine outline on floating app objects. |
| product demonstrations | Media charcoal | `#1c1917` | `--color-window-dark` | surface, text | Dark backing within video and interface demonstrations. |
| product demonstrations | Warm window rule | `#e7e5e4` | `--color-window-edge` | border | Rules within interface windows. |
| product demonstrations | Warm control shade | `#f5f5f4` | `--color-window-shade` | surface | Neutral gradients on small floating app objects. |

## Typography

- **oracle** — All marketing text, from opening promise to navigation and footer. Unshowy contemporary grotesk with open forms, regular-weight headings and slightly tight spacing. If unavailable, use **Inter**. Use 400 and 500; retain -0.02em marketing tracking. Font stack: "oracle", "Inter", Arial, sans-serif.
- **Inter** (only for product demonstrations) — Text inside reconstructed software windows, not marketing headings. Compact functional sans with a denser, medium-weight UI rhythm. Font stack: "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| manifesto | oracle | 400 | 52px | 1.2 | -0.02em | Centered statement with a black first sentence and gray continuation; selected words are underlined links. |
| closing-heading | oracle | 400 | 52px | 1.08 | -0.02em | Centered final invitation inside the luminous art panel. |
| opening-heading | oracle | 400 | 32px | 1.2 | -0.02em | Opening headline, equal-sized support line and main section headings. |
| chapter-heading | oracle | 400 | 24px | 1.2 | -0.02em | Benefit heading beside a large demonstration. |
| body-large | oracle | 400 | 20px | 1.5 | -0.02em | Chapter explanations and primary text links. |
| quote | oracle | 400 | 18px | 28px | -0.02em | Short conversational quotes in the horizontal proof strip. |
| body | oracle | 400 | 16px | 1.5 | -0.02em | Card headings, short card paragraphs and accordion questions. |
| answer | oracle | 400 | 16px | 1.6 | -0.02em | Expanded FAQ answers. |
| button | oracle | 500 | 16px | 1.5 | -0.02em | Full-sized primary and pricing actions. |
| navigation | oracle | 400 | 15px | 1.5 | -0.02em | Header links, footer headings and directory links. |
| compact-action | oracle | 500 | 15px | 1.5 | -0.02em | Small white pills, header conversion action and chapter tags. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | oracle | 400 | 32px | 1 | -0.02em | Plan amount, currency and custom-price alternative; align period text on the baseline. |
| product demonstrations | product-stat | Inter | 500 | 30px | 1.2 | -0.025em | Numerals within an analytics demonstration, not standalone marketing metrics. |
| pricing pages | plan-title | oracle | 400 | 20px | 1.2 | -0.02em | Plan names in the pricing cards. |
| audience landing pages | audience-label | oracle | 400 | 12px | 1.5 | -0.02em | Small outlined audience pill above an opening promise. |

**Notes:**

- Use regular weight to hold the hierarchy together; change scale and text tone instead of making section headings bold.
- Marketing tracking stays at -0.02em across the scale. Interface text is a separate typography layer and should not inherit that rule.
- The opening uses 32px type, smaller than the 52px manifesto and closing invitation. Do not turn the first screen into a giant typographic billboard.

## Layout

**Density:** Airy between chapters, compact within software scenes and navigation. Large demonstrations give the sparse text a purposeful setting.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Heading-to-support gap in opening copy and card captions. |
| 8px | Chapter heading-to-description gap and spacing between compact pills. |
| 12px | Card-grid gutters and stacked feature-list items. |
| 16px | Stage inner rim, media-tile caption padding and card interior padding. |
| 18px | Outer page side padding. |
| 24px | Promise-to-action gap and gap above pill rows. |
| 32px | Section heading-to-grid gap and chapter text side padding. |
| 48px | FAQ column gap and vertical padding within chapter text. |
| 64px | Chapter section vertical padding, gap before the opening demonstration and footer spacing. |
| 96px | Vertical padding around the manifesto and compact-width major sections. |
| 128px | Desktop opening top padding and major grid-section vertical padding. |

### Containers and grids

- **main-container**: max width 1300px · side padding 18px. Centered content throughout; at 1440px the stage edges sit about 70px from either side.
- **opening-container**: max width 1340px · side padding 18px. Opening text and demonstration share a slightly wider parent with nearly the same visible alignment as later chapters.
- **chapter-grid**: 3 columns · gap 0px. Large media spans two columns; vertically centered copy occupies one. Alternate the media side between chapters.
- **media-card-grid**: 3 columns · gap 12px. Three equal visual tiles with captions outside the media frame.
- **faq-grid**: max width 1300px · 3 columns · gap 48px. Heading takes one column; accordion takes two, about 851px wide; answers stop at 680px.
- **manifesto-container**: max width 1100px. Centered multi-line statement surrounded by substantial empty space.
- **footer-grid**: 5 columns · gap 24px. Equal-width directory columns below a small left-aligned wordmark.
- **catalog-grid** (only for feature catalog pages): 2 columns · gap 12px. Two broad columns of 240px-minimum-height icon cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsules | 9999px (pill) |
|  | chapter-shell | 32px |
|  | media-tile | 28px |
|  | inner-stage | 16px |
|  | floating-video | 20.5px |
| product demonstrations | browser-chrome | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| inset-rim | `inset 0px 0px 0px 1px #ffffff` | White inner highlight on pale chapter and catalog shells. |
| floating-window | `0px 8px 32px 4px rgba(0,0,0,0.15)` | Video windows and floating software objects; not every marketing card. |
| selected-tab | `0px 0px 0px 1px rgba(17,17,17,0.04), 0px 1px 3px rgba(0,0,0,0.08)` | White selected capsule over a pale demonstration background. |

### Surfaces

#### Canvas · level 0

**Use:** Default continuous light page.

**CSS:** `background: #fdfdfd; color: #0c0a09`

#### Molded stage · level 1

**Use:** Broad product chapters and the opening demonstration.

**CSS:** `background: linear-gradient(rgba(17,17,17,0.01) 0%, rgba(17,17,17,0.035) 100%); border: 1px solid rgba(17,17,17,0.08); border-radius: 32px; padding: 16px; box-shadow: inset 0px 0px 0px 1px #ffffff`

**Observed:** The shell is just darker than the page; its white rim is more important than any external shadow.

**Transfer:** Keep the shell restrained so the product remains the colorful layer.

#### Washed digital field · level 1

**Use:** Backing for demonstrations and floating objects.

**CSS:** `background-color: #ffffff; overflow: hidden; border-radius: 16px`

**Observed:** Fragmented rainbow bars are softened by white veils: the opening artwork is at 0.2 opacity, while chapter artwork can carry a 60% white overlay.

**Transfer:** Use the Digital light field imagery recipe under the content, never over the text.

#### Pale directory band · level 0

**Use:** Footer background across the full viewport.

**CSS:** `background: linear-gradient(rgba(17,17,17,0.01) 0%, rgba(17,17,17,0.035) 100%); border-top: 1px solid rgba(17,17,17,0.08); padding: 64px 18px 32px`

#### Floating browser · level 2

**Only for:** product demonstrations

**Use:** Software window laid over glitch art.

**CSS:** `background: #ffffff; border: 1px solid rgba(17,17,17,0.08); border-radius: 8px; box-shadow: 0px 8px 32px 4px rgba(0,0,0,0.15); backdrop-filter: blur(8px)`

**Observed:** Slim browser chrome with tiny traffic lights sits above a tightly framed real workflow. Windows can extend beyond the visible media area.

**Transfer:** Use one intelligible task rather than a whole unreadable dashboard.

#### Violet closing field · level 1

**Only for:** audience landing pages

**Use:** A more saturated closing invitation variant.

**CSS:** `background-color: #5e51f8; border-radius: 32px; overflow: hidden; color: #ffffff`

**Observed:** Bright linear light fragments cross a violet field; the headline is white and the capsule action is dark.

**Transfer:** Reserve this concentrated color inversion for the final invitation, not every chapter.

## Components

### Sticky navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: sticky; top: 0px; z-index: 50; background: rgba(255,255,255,0.54); border-bottom: 1px solid rgba(17,17,17,0.043); padding: 0px 18px; height: 57px`

**Text style:** `navigation` — oracle 400 · 15px/1.5 · tracking -0.02em

**Observed:** Within a 1300px row, a small symbol-and-wordmark sits left, three short destination links are centered, and white login plus violet signup capsules sit right. Header actions are about 33px tall.

**States:** Declared: hover navigation-link opacity 0.8; focus-visible outline-style none in the original controls.

**Transfer:** Keep the navigation visually smaller than the promise and product stage.

### Primary button

**Use:** One clear conversion action in the opening and closing invitation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #5e51f8; color: #ffffff; border-radius: 9999px; min-height: 44px; padding: 8px 48px`

**Text style:** `button` — oracle 500 · 16px/1.5 · tracking -0.02em

**Observed:** Centered text with no arrow. The opening capsule can be wider than its label requires; pricing actions fill the inner card width. Audience closing sections use a black variant.

**States:** Declared: hover opacity 0.9; focus-visible outline-style none and zero ring shadow; active scale 0.96.

### Secondary pill

**Use:** Compact capability links under a chapter and the secondary header action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #0c0a09; border: 1px solid rgba(17,17,17,0.08); border-radius: 9999px; padding: 4px 24px`

**Text style:** `compact-action` — oracle 500 · 15px/1.5 · tracking -0.02em

**Observed:** A centered wrapping row sits 24px below the shell; use a pill per short capability. The full-size pricing variant uses button typography and 8px 48px padding.

**States:** Declared: hover box-shadow remains zero; focus-visible outline-style none; active scale 0.96.

### Learn-more link

**Use:** Quiet progression from a benefit description to deeper information.

**CSS:** `color: #8278fa; border-radius: 4px`

**Text style:** `body-large` — oracle 400 · 20px/1.5 · tracking -0.02em

**Observed:** A plain text link without an arrow, separated from chapter text by a 32px gap. The card-caption variant uses body typography.

**States:** Declared: hover opacity 0.75; focus-visible outline-style none and zero ring shadow.

### Chapter panel

**Use:** Main capability demonstration.

**CSS:** `padding: 16px; border: 1px solid rgba(17,17,17,0.08); border-radius: 32px; background: linear-gradient(rgba(17,17,17,0.01) 0%, rgba(17,17,17,0.035) 100%); box-shadow: inset 0px 0px 0px 1px #ffffff`

**Observed:** Media takes two thirds and text one third. The text area has 48px vertical and 32px side padding; its heading and support are separated by 8px. Clip oversized windows inside the media frame rather than shrinking every control.

**Transfer:** Choose a task that visually proves the adjacent benefit.

### Visual capability tile

**Use:** A compact three-column group supporting a larger narrative.

**CSS:** `background: #ffffff; border: 1px solid rgba(17,17,17,0.08); border-radius: 28px; overflow: hidden; aspect-ratio: 16 / 9`

**Text style:** `body` — oracle 400 · 16px/1.5 · tracking -0.02em

**Observed:** The visible media is about 425px by 239px. Heading and support live outside the rounded image, in a 16px padded caption with a 4px gap; some tiles end with a small violet link.

**Transfer:** Use a tightly framed use-case video or a simplified interface vignette, with consistent image ratios across the row.

### FAQ question

**Use:** Low-friction objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; min-height: 64px; padding: 20px 0px; width: 100%; text-align: start`

**Text style:** `body` — oracle 400 · 16px/1.5 · tracking -0.02em

**Observed:** Each row sits beneath a faint 1px rule. A gray 28px plus aligns right and rotates into a cross for an open answer. The first answer is expanded; answer text stops at 680px and has 24px bottom padding.

**Transfer:** Keep answers explanatory and the container unboxed; place the section heading beside the list.

### Footer directory

**Use:** Practical navigation after the closing artwork.

**CSS:** `padding: 64px 18px 32px; background: linear-gradient(rgba(17,17,17,0.01) 0%, rgba(17,17,17,0.035) 100%); border-top: 1px solid rgba(17,17,17,0.08)`

**Text style:** `navigation` — oracle 400 · 15px/1.5 · tracking -0.02em

**Observed:** Small wordmark first; 64px later comes a five-column grid with 24px gutters. Headings are ink, links muted; lists use 12px gaps. A final full-width rule separates left copyright from right legal links.

**Transfer:** Keep the directory useful and visually subordinate to the preceding art panel.

### Icon feature card

**Only for:** feature catalog and organizational capability grids

**Use:** Compact coverage of many capabilities without full demonstrations.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; min-height: 240px; padding: 16px; border: 1px solid rgba(17,17,17,0.08); border-radius: 32px; background: linear-gradient(rgba(17,17,17,0.01) 0%, rgba(17,17,17,0.03) 100%); box-shadow: inset 0px 0px 0px 1px #ffffff`

**Text style:** `body` — oracle 400 · 16px/1.5 · tracking -0.02em

**Observed:** A 24px monochrome icon sits in a 56px square with 16px squircle corners at the top left. Heading and gray description anchor to the bottom left with a 4px gap. Two columns serve a catalog; three serve shorter capability groups.

### Plan card

**Only for:** pricing pages

**Use:** Compare a small set of purchase routes.

**CSS:** `padding: 32px; border: 1px solid rgba(17,17,17,0.08); border-radius: 32px; overflow: hidden; background: linear-gradient(rgba(17,17,17,0.01) 0%, rgba(17,17,17,0.03) 100%); box-shadow: inset 0px 0px 0px 1px #ffffff`

**Text style:** `plan-title` — oracle 400 · 20px/1.2 · tracking -0.02em

**Observed:** Three equal cards are about 425px wide and 595px tall. Order is name, muted one-line positioning, amount with period, wide action, then a divided check list. The middle plan carries the violet action and a washed glitch background; neighboring actions remain white.

**Transfer:** Highlight one recommended route without adding a large badge or changing its scale.

### Comparison row

**Only for:** pricing pages

**Use:** Detailed categorical comparison after the summary plans.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); align-items: center; gap: 12px; padding: 16px 0px; border-bottom: 1px dashed rgba(17,17,17,0.08)`

**Text style:** `body` — oracle 400 · 16px/1.5 · tracking -0.02em

**Observed:** One label column and three plan columns, roughly 57px per row. Use quiet checks and short values, not colored table cells. Category headings have 20px vertical padding; a sticky plan-summary row keeps purchase actions available.

## Imagery and graphics

### Digital light field

**Use:** Signature art behind the opening demonstration, selected product scenes and the closing invitation.

**Observed:** Thin repeated cyan bars, stepped magenta blocks, yellow-green rectangles and occasional long horizontal streaks form an airy digital interference field. White dominates; the effect is softly luminous rather than noisy or grungy. The opening treatment is barely present, while the closing panel shows stronger clusters around a clear central message.

**Transfer:** Recreate a related fragmented light field rather than an all-over rainbow gradient. Preserve sparse interruptions, soft bloom and large white areas.

**Build:** In SVG, layer groups of narrow repeated rectangles and stepped horizontal blocks. Use cyan rgba(50,245,232,0.4), pink rgba(235,77,242,0.35), yellow rgba(244,255,40,0.4) and green rgba(76,246,110,0.35), with a second blurred copy behind each group for bloom. Mix 2px–8px bars with 40px–160px blocks, blur by 2px–8px, and cluster around outer edges. Add a white central radial mask. Place the entire field at opacity 0.2 for the opening; increase visibility for the closing panel. Match the soft glow; exact stops are not essential.

### Human product demonstration

**Use:** The main opening object and supporting use-case tiles.

**Observed:** Natural webcam portraits and desktop work appear together: a speaker in ordinary indoor light, screen content framed beside or behind them, sometimes with a rounded face-camera inset. The demonstration is much larger than the text, with an approximately 1008px by 567px widescreen stage; short-form modes layer portrait videos in front.

**Transfer:** Show actual people using or explaining the new product with believable outputs. If video is unavailable, create a still composite of one genuine output and one naturally lit portrait, retaining the same rounded framing and soft shadow.

### Oversized interface vignettes

**Use:** The visual two-thirds of recurring chapters and compact media tiles.

**Observed:** Realistic white browser windows, edit timelines, small floating settings panels and task-specific overlays sit above washed glitch artwork. Some windows intentionally run out of frame, making details large enough to read. Purple may be strong inside the demonstrated output while the outer marketing shell stays neutral.

**Transfer:** Use authentic new-product UI or construct one coherent task view with a window, one key control group and a result; keep interface colors separate from marketing color roles.

### Output mosaic

**Use:** Late-page proof that the product supports varied results.

**Observed:** A broad cropped four-column mosaic of 16:9 output thumbnails occupies two thirds of a molded panel beside a short heading and support line. People, screens, presentations and dark title cards alternate without a large caption on every thumbnail.

**Transfer:** Show a varied set of credible outputs for the new product with consistent tile ratios. Use a compact editorial selection if there are few outputs; maintain a continuous mosaic rather than isolated floating cards.

### Conversational proof strip

**Use:** A narrow social-proof interruption between the opening and the manifesto.

**Observed:** Short single-line quotes travel horizontally with tiny circular profile pictures. Pale speech-bubble capsules, clipped overflow and faded side edges keep the strip lightweight; text uses the 18px quote recipe.

**Transfer:** Use permissioned, specific short quotes and small avatars. Keep the strip about 112px tall and secondary to the larger product story.

### Floating app sculpture

**Only for:** consolidation illustrations

**Use:** An abstract visual for replacing several tools with one.

**Observed:** A large softly glowing purple rounded-square app object floats to the right of concise text and a small check list. Pale smaller app tiles peek from behind it at slight angles; an elliptical ground shadow gives the group weight. The backing is the very faint digital light field.

**Transfer:** Replace the central icon with the new product's own abstract mark. The minimum version is a luminous rounded square with a simple white symbol, pale rotated tiles behind it and a soft ground shadow.

**Build:** Create a 320px rounded square with roughly 64px corners, a violet-to-lilac gradient, white inset highlights and broad low-opacity purple bloom. Put several approximately 105px white-to-warm-gray tiles behind it, with 26px corners and small rotations such as -8deg. Add a 371px by 39px radial black-to-transparent ellipse underneath at about 10% alpha. Keep the stage near-white.

### Icons

**Observed:** Marketing catalog icons are muted 24px glyphs inside 56px softly squared wells; interface and accordion icons use fine rounded strokes, commonly 1.5px at 20px, with a 28px plus for FAQ controls. Checks are small, monochrome and visually quieter than the text.

**Transfer:** Choose simple functional symbols, not multicolor illustrations. Keep the catalog glyph low-contrast and the action icon geometrically modest.

## Section recipes

How recurring sections are built.

### First screen: Product-stage opening

**Observed:** A 57px translucent Sticky navigation overlays a near-white canvas. The opening content starts with 128px top padding in the Opening container: black 32px regular headline, equally sized gray support line just 4px below, then a left-aligned Primary button after 24px. The right half stays mostly empty. After 64px, a full-width Molded stage begins; its layers are faint Digital light field, a centered row of small mode labels with a white selected capsule, then the oversized Human product demonstration. Within the first 900px the headline, support, action, selector and upper part of the main object are visible; the object and its publication cues continue below the fold. The whole opening is about 1200px tall.

**Transfer:** Use a concise promise over a product output large enough to become the main visual event. Without video, stage a faithful task-and-result composite on the luminous backing. Audience pages can add the small outlined audience pill before the promise and use a workspace scene. Catalog pages open with the same 32px black/gray heading pair over a fading light field and no main action; pricing pages instead center a short title over billing controls and Plan cards.

**Avoid:** Do not center a huge headline above a tiny mockup, cram the entire demonstration above the fold, or convert the open right side into a second hero column.

**Text style:** `opening-heading` — oracle 400 · 32px/1.2 · tracking -0.02em

### Two-tone manifesto

**Observed:** A roughly 700px-tall quiet interval centers a 1100px-wide 52px statement. The first sentence is ink; the continuation is gray and wraps over two lines, with a few darker underlined keywords. Vertical padding is 96px with additional space from vertical centering.

**Transfer:** Use one memorable contrast between outcome and effort, followed by one explanatory sentence; link only a few meaningful words.

**Text style:** `manifesto` — oracle 400 · 52px/1.2 · tracking -0.02em

### Alternating demonstration chapter

**Observed:** Chapter panel sits in a section with 64px vertical padding. Its two-thirds media area carries Oversized interface vignettes, with the remaining third using chapter-heading and body-large typography plus Learn-more link. Alternate left and right media placement; related Secondary pills sit centered beneath the panel after 24px.

**Transfer:** Let each chapter prove one benefit through one visible action. Vary the workflow and media scale while keeping the molded shell consistent.

**Text style:** `chapter-heading` — oracle 400 · 24px/1.2 · tracking -0.02em

### Captioned media row

**Observed:** A 32px main section heading precedes a three-column, 12px-gutter row by 32px. Visual capability tiles use 16:9 media; captions sit below rather than floating over the image. The section uses 128px vertical padding.

**Transfer:** Group parallel outcomes or use cases in a small consistent row; retain human footage where the product benefits from a personal tone.

**Text style:** `opening-heading` — oracle 400 · 32px/1.2 · tracking -0.02em

### Side-heading questions

**Observed:** A 32px heading occupies the left third of a 1300px grid with 48px gutters. FAQ question rows fill the right two thirds; the first answer is open, and remaining rows show a small plus. Section vertical padding is 128px.

**Transfer:** Translate purchase objections into direct questions and answer them without sales language.

**Text style:** `opening-heading` — oracle 400 · 32px/1.2 · tracking -0.02em

### Luminous closing invitation

**Observed:** A 64px-padded section holds a 1300px by 420px rounded panel with 32px corners and a faint edge. Digital light field surrounds a centered 52px/1.08 invitation capped at 760px width, with one Primary button below. The default field is white with bright color fragments; audience pages use Violet closing field with white type and a black capsule. Footer directory follows after 64px.

**Transfer:** Use an outcome-led closing line and the same conversion action as the opening. Preserve the luminous object treatment even if the rest of the page is short.

**Text style:** `closing-heading` — oracle 400 · 52px/1.08 · tracking -0.02em

### Catalog chapter

**Only for:** feature catalog pages

**Observed:** A 32px category title is followed by Icon feature cards in two columns with 12px gaps. Each card is at least 240px tall, with a top-left icon well and bottom-aligned title/description. Major category sections have 128px vertical padding.

**Transfer:** Use concise capability categories and one sentence per card, allowing the sparse composition to remain intentional.

**Text style:** `opening-heading` — oracle 400 · 32px/1.2 · tracking -0.02em

### Pricing choice and detailed matrix

**Only for:** pricing pages

**Observed:** A centered 32px title sits above a compact annual-billing switch, discount badge and user stepper. Three Plan cards follow in a 12px-gutter grid, then a separately centered comparison heading and the long dashed Comparison row matrix grouped by sticky category headings.

**Transfer:** Use the summary cards for choice and the matrix for verification, keeping only the recommended plan chromatic.

**Text style:** `opening-heading` — oracle 400 · 32px/1.2 · tracking -0.02em

## Page flow

**Storyline:** Concise promise → substantial product proof → understandable benefit chapters → breadth and credibility → objections → luminous invitation → practical directory.

### Introduce a versatile product through visual proof

1. **Promise** — Small left-aligned heading pair and one action above an oversized selectable demonstration.
2. **Social proof** — Narrow conversational quote strip.
3. **Positioning** — Centered two-tone manifesto with linked keywords.
4. **Capability chapters** — Alternating media-heavy molded panels, some with compact capability pills.
5. **Breadth** — Captioned tile row and a floating consolidation illustration.
6. **Output proof** — Cropped mosaic of finished work beside short copy.
7. **Objection handling** — Side-heading FAQ with the first answer open.
8. **Closing call** — Bright fragmented-light invitation, then pale directory footer.

**Transfer:** Choose the strongest workflows rather than reproducing the number of chapters; preserve the progression from promise to visible result.

### Provide a browsable capability catalog

1. **Orientation** — Left-aligned heading pair over fading digital color.
2. **Capability catalog** — Category headings and broad two-column icon cards, grouped by workflow stage.
3. **Closing call** — Light glitch-art invitation and shared five-column directory.

**Transfer:** Organize capabilities around the new product's own workflow and keep the cards concise.

### Help buyers select and verify a plan

1. **Pricing** — Centered title, billing and seat controls, then three plan cards with a chromatic middle option.
2. **Decision support** — Detailed grouped matrix with sticky plan summaries, quiet checkmarks and dashed rules.
3. **Objection handling** — FAQ focused on usage, billing and organizational requirements.
4. **Closing call** — Light digital-art invitation followed by the shared pale directory.

**Transfer:** Separate the initial choice from exhaustive detail; put accurate commercial terms in both places.

### Explain the product for a specific audience

1. **Audience promise** — Small outlined audience label, heading pair, action and large workspace demonstration.
2. **Use cases** — Two three-column rows pairing practical scenarios with human or interface videos.
3. **Capability chapters** — Two alternating molded demonstration panels.
4. **Trust** — Three-column icon-card grid for administrative and organizational concerns.
5. **Objection handling** — Audience-specific FAQ.
6. **Closing call** — Violet digital-light field with white headline and dark action, then the shared directory.

**Transfer:** Focus on audience tasks and risks; keep its saturated closing treatment scoped rather than recoloring the entire page.

## Writing

Practical, friendly and confident without sounding grand. Benefits are grounded in recognizable tasks, with light conversational contrasts and very little ceremonial marketing language.

**Do not copy:** Do not reuse Tella's name, logo, proprietary art, customer identities, testimonials, plan names as brand assets, prices, credit amounts, certifications or performance claims. Replace these with accurate information and original assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. Refer to the product by name when explaining what it does; use an occasional conversational analogy rather than a corporate we.
- **Rhythm:** Headlines are usually brief sentence-case fragments; descriptions are one or two straightforward sentences. Contrast pairs and short verb lists create momentum without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the practical scope in a short phrase, then state what the reader can accomplish. | 4–10 words per line | “All-in-one video creation”<br>“Record, edit, and share every video you need” |
| Positioning statement | Pair a high-value outcome with less effort using a compact contrast. | 4–8 words | “High production, low effort.”<br>“More videos. Less subscriptions.” |
| Chapter heading | A useful benefit or reassuring capability rather than a technical category alone. | 3–8 words | “Close control when you need it”<br>“Fits your workflow” |
| Supporting paragraph | Begin with a concrete action and name the result or relief it provides. | 12–35 words | “Your video is always ready to share. Copy its link, embed, password protect and more.”<br>“Only pay for creators. Add as many viewers to your workspace as you like.” |
| Primary action | Direct short verb phrase; no clever substitute for the action. | 2–5 words | “Get started”<br>“Get started for free”<br>“Contact sales” |
| Question and answer | Ask a real concern in the reader's language, then answer directly before adding conditions. | Short question; one compact paragraph | “Can I cancel at any time?”<br>“Can I record without downloading anything?” |

**Words and phrasing to use:** all-in-one; your; ready to share; built in; without switching; fast, flexible; every; get started

**Avoid:** revolutionary; world-class; unlock your potential; synergy; next-generation ecosystem; exclamation-heavy urgency

**Rules:**

- Lead with the task or benefit, then give enough operational detail to make it believable.
- Use a short list of verbs to communicate breadth; save exhaustive terminology for catalogs and comparison tables.
- Keep supporting text gray in visual hierarchy, but make its meaning concrete rather than disposable.
- Use occasional compact contrasts such as more outcome, less overhead; do not turn every heading into a slogan.

## Do's and Don'ts

### Do

- Keep the opening headline at 32px regular and its support line at the same size, separated by 4px.
- Use 1300px centered stages with 32px corners and a 16px inner rim.
- Keep violet conversion capsules at 44px minimum height with 8px 48px padding.
- Stage the principal demonstration roughly two thirds of a chapter's width.
- Give major grid sections 128px vertical padding and keep their internal gutters at 12px.
- Use thin 8%-ink outlines plus a white inset rim for pale shells.
- Include fragmented digital light with a low-opacity opening version and a brighter closing version.
- Keep footer text at 15px, with five columns, 24px gutters and muted links.

### Don't

- Do not make marketing headings weight 700; the characteristic hierarchy is weight 400 with -0.02em tracking.
- Do not fill ordinary chapter backgrounds with violet; save concentrated violet for actions and the scoped closing inversion.
- Do not give every card a heavy drop shadow; the molded shell relies on a faint border and inset highlight.
- Do not use 16px or 24px gutters between catalog cards; retain their tight 12px spacing.
- Do not add arrows to every action; the main capsule and learn-more link are text-led.
- Do not treat interface statistic typography as a separate giant marketing-number system; 30px numerals belong inside the demonstrated UI.
- Do not turn the footer into a dark billboard; it is a pale practical directory.
- Do not replace the fragmented light artwork with a generic full-bleed smooth mesh gradient.

## Motion and responsive

### Motion

**Observed:**

- Primary actions declare transform and opacity transitions of 0.2s cubic-bezier(0,0,.2,1), hover opacity 0.9 and active scale 0.96.
- Secondary pills declare transform and box-shadow transitions of 0.15s cubic-bezier(0,0,.2,1). Learn-more links declare opacity transitions of 0.15s cubic-bezier(.4,0,.2,1).
- Header background and border transition over 0.2s cubic-bezier(.4,0,.2,1).
- FAQ answer containers declare a 0.3s ease-out grid-row transition; the plus uses a 0.2s ease-out transform and rotates 45 degrees when open.
- Product demonstrations include video, and a horizontal quote strip moves through clipped, faded edges.

**Transfer:**

- Use the small press scale and opacity changes on capsules; keep the molded containers visually stable.
- Confine more elaborate movement to the product scene and digital-light layer so surrounding text remains easy to read.

**Unknown:**

- Exact light-field animation timing, mode-change choreography and ticker duration are not established.
- Reduced-motion behavior and keyboard-focus appearance beyond the declared rules are not established.

### Responsive

**Observed:**

- Chapter panels and FAQ adopt three-column layouts at 900px; chapter media spans two columns.
- Catalog cards become two columns at 700px. Pricing cards become two columns at 700px and three at 1050px.
- Main sections use 96px vertical padding below 900px and 128px above it.
- The opening mode selector is hidden below the small-screen breakpoint; footer markup begins with two columns and introduces a wider layout at 640px.

**Transfer:**

- On narrow screens, place chapter text above its media, retain the rounded stage and crop the UI to a readable task rather than shrinking a desktop dashboard.
- Stack the FAQ heading above its list; keep the luminous closing panel and clear central text zone.
- Reduce the number of simultaneously visible demonstration modes rather than squeezing four labels into a narrow row.

**Unknown:**

- Mobile rendering, exact narrow-screen type sizes and the complete intermediate footer-column mapping are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
