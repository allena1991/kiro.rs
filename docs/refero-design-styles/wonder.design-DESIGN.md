# Wonder — the luminous workbench

## Overview

A dark, tool-like visual language with the warmth of a creative studio. White grotesk headings, subdued gray prose and tiny monospace markings sit inside a finely ruled black canvas, with purple controls and pools of colored light. Large working interfaces provide the substance; handwritten notes and tactile photography add humanity without making the page feel busy.

### Essentials

- The page feels like an editable workbench: 24px rulers along the top and left, faint ticks and numerals, and 1px white-at-7% rules around a 1192px content frame. Carry this drafting-device treatment into every new page.
- Headlines speak at human scale rather than billboard scale: Uncut Sans Variable 42px/1.04, weight 600, -0.025em tracking for the opening and closing; section headings are 34px/1.1 with the same weight and tracking.
- The opening is a split promise above an oversized working object: a roughly 480px-wide headline on the left, 16px support and paired actions on the right, then a 1277×758px dark application window that extends beyond the first 900px. Without a full interface, stage a credible workflow specimen in the same window.
- Actions look like small desktop controls, not marketing pills: 32px high, 8px corners, 12px horizontal padding, 14px/1 medium text and subtle inset highlights. Purple identifies the primary action; charcoal holds the secondary.
- Color behaves like light under the desk: most of the page stays near-black; purple fills are concentrated in small controls, while broad low-contrast violet, blue and rose glows occupy occasional inset bands and the bottom edge of the closing area.
- Proof is arranged in joined cells rather than floating cards: 40px padding, zero grid gap, shared hairlines and bottom-aligned 18px/1.4 captions with a white lead phrase fading into half-white explanation.
- Human marks interrupt the technical grid: a luminous inset callout includes 24px handwritten labels floating above a centered 34px heading. Recreate those notes around concepts relevant to the new product, even when the main media is a static specimen.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action purple | `#993abe` | `--color-purple` | action, accent | Small primary-control fills; layered with a white sheen rather than used as a broad section background. |
| Blue light pool | `#1a344c` | `--color-blue-glow` | background, accent | Blue atmospheric light, produced with rgba(58,144,224,0.3) over black and softened further at the closing edge. |
| Rose light pool | `#4f2b41` | `--color-rose-glow` | background, accent | Rose atmospheric light, produced with rgba(232,114,187,0.3) over black and softened further at the closing edge. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Workbench black | `#0d0d0d` | `--color-canvas` | background | Default canvas and the interior of joined marketing cells. |
| Shared hairline | `#1e1e1e` | `--color-rule` | border | Visible result of 7% white over the canvas; shared section and grid edges. |
| Announcement charcoal | `#1e1e1e` | `--color-badge` | surface | Announcement pill in the opening. |
| Charcoal control | `#202020` | `--color-control` | surface, action | Secondary controls and the backing of culture-page photo prints. |
| Recessed gray | `#6e6e6e` | `--color-muted` | text | Visible result of 40% white over the canvas; metadata, section labels and footer headings. |
| Half-white caption | `#868686` | `--color-caption` | text | Visible result of 50% white over the canvas; explanatory halves of feature captions. |
| Soft gray lettering | `#b6b6b6` | `--color-body` | text, link | Visible result of 70% white over the canvas; support paragraphs and navigation. |
| White lettering | `#ffffff` | `--color-heading` | text | Headlines, emphasized caption phrases and button labels. |

### Inside product imagery only

Colors used only inside product imagery and demos: use them to recreate that imagery, not for the page itself.

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Application charcoal | `#181818` | `--color-product-frame` | surface | Large application-window backing at 82% opacity; not an alternative page canvas. |

## Typography

- **Uncut Sans Variable** — Opening, section and closing headings; editorial card titles. Compact contemporary grotesk with open counters and closely fitted medium-to-semibold shapes. If unavailable, use **Inter Tight**. Use 500–600 and retain negative tracking on large headings. Font stack: "Uncut Sans Variable", "Inter Tight", "Uncut Sans", sans-serif.
- **Inter** — Paragraphs, controls, navigation and feature captions. Neutral high-x-height interface sans; regular prose and slightly firmer controls. Font stack: "Inter", Arial, sans-serif.
- **JetBrainsMono** — Metadata, proof labels, footer group labels and workbench markings. Small technical monospace; restrained rather than code-heavy. If unavailable, use **JetBrains Mono**. Font stack: "JetBrainsMono", "JetBrains Mono", monospace.
- **rollerScript** — Floating handwritten concept labels; photo captions in the culture variant. Loose, slanted personal handwriting that contrasts with the strict grid. If unavailable, use **Caveat**. Use regular weight and keep labels short. Font stack: "rollerScript", "Caveat", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Uncut Sans Variable | 600 | 42px | 1.04 | -0.025em | Opening and closing promise; usually two or three short lines. |
| heading | Uncut Sans Variable | 600 | 34px | 1.1 | -0.025em | Section leads and the luminous callout headline. |
| compact-heading | Uncut Sans Variable | 500 | 26px | 1.15 | -0.01em | Centered integration or compatibility statement. |
| handwritten-note | rollerScript | 400 | 24px | 1.2 | normal | Floating labels above the luminous callout. |
| feature-caption | Inter | 450 | 18px | 1.4 | normal | Feature explanations with an inline white lead phrase and half-white continuation. |
| card-title | Uncut Sans Variable | 500 | 18px | 1.4 | normal | Editorial-card titles. |
| body | Inter | 400 | 16px | 1.45 | normal | Opening support text. |
| question | Inter | 450 | 16px | 1.5 | normal | FAQ summary rows. |
| button | Inter | 500 | 14px | 1 | 0.02em | Primary and secondary controls. |
| navigation | Inter | 400 | 14px | 20px | 0.01em | Top navigation links. |
| link | Inter | 400 | 14px | 20px | normal | Footer and utility links. |
| card-body | Inter | 400 | 14px | 1.625 | normal | Short editorial summaries. |
| answer | Inter | 400 | 14px | 1.5 | normal | FAQ answers. |
| announcement | Inter | 400 | 14px | 1.375 | 0.01em | Compact sentence inside the opening pill. |
| proof-label | JetBrainsMono | 400 | 12px | 16px | 0.05em, uppercase | Centered label above the proof-logo strip. |
| metadata | JetBrainsMono | 400 | 12px | 1.5 | 0.05em, uppercase | Date and category line on editorial cards. |
| footer-label | JetBrainsMono | 400 | 10px | 1.5 | 0.05em, uppercase | Footer group headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| culture and recruiting pages | benefit-title | Inter | 500 | 18px | 28px | normal | Titles in two-column text cells. |
| culture and recruiting pages | photo-caption | rollerScript | 400 | 16px | 1.2 | normal | Centered handwriting below square photographs. |
| culture and recruiting pages | benefit-body | Inter | 400 | 15px | 1.5 | normal | Benefit descriptions and recruiting introduction. |
| recruiting listings | listing-title | Inter | 500 | 14px | 20px | normal | Role titles in full-width recruiting rows. |
| culture and recruiting pages | section-label | JetBrainsMono | 400 | 12px | 1.5 | normal | Small mixed-case eyebrow above culture-page headings. |

**Notes:**

- Keep the opening at 42px rather than inflating it into an oversized display. The large application object supplies the scale.
- The 42px and 34px headings share -0.025em tracking, while the smaller centered heading relaxes to -0.01em. Paragraphs remain normally tracked.
- Inter supplies the letters in body text; the numeral-specific face does not define a separate prose voice.
- Handwriting is a short annotation layer, never the main headline or a paragraph.

## Layout

**Density:** Airy at section scale and compact inside controls; long dark rests separate dense working specimens.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Title-to-description gap and paired-control separation. |
| 12px | Control horizontal inset and label-to-heading gap. |
| 16px | Metadata-to-title gap and supporting-text separation. |
| 24px | Opening support-to-action separation and desktop hero column gap. |
| 32px | Footer column gap and outer right inset. |
| 40px | Default desktop cell padding. |
| 64px | Luminous callout vertical padding and footer links' top inset. |
| 80px | Opening text area's desktop top padding. |
| 96px | Ruled breathing bands between compact sections. |
| 128px | Long breathing bands and extra lead-in before capability headings. |

### Containers and grids

- **outer-shell**: max width 1280px · side padding 32px. Centered outer shell; desktop left inset is 56px to account for the ruler, while the right inset is 32px.
- **ruled-frame**: max width 1192px · gap 0px. Shared vertical rails enclosing approximately 1190px of inner content at desktop.
- **hero-grid**: 12 columns · gap 24px. Headline occupies six columns; support occupies five starting at the eighth column. Align the support and actions toward the headline's lower edge.
- **feature-grid**: 3 columns · gap 0px. Joined cells; some specimens span two columns. A later capability chapter switches to two equal columns.
- **editorial-grid**: 3 columns · gap 0px. Equal-width cards with shared hairlines and 40px cell padding.
- **footer-grid**: 5 columns · gap 32px. Footer groups follow 1fr 1fr 1fr 1.5fr 1.2fr proportions rather than five forced-equal columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 8px |
|  | application-window | 14px |
|  | announcement-pill | 9999px (pill) |
| culture pages | photo-print | 12px |
| culture pages | photo-image | 5px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | control-sheen | `rgba(255, 255, 255, 0.32) 0px 0.5px 0px 0px inset, rgba(255, 255, 255, 0.1) 0px 0px 0px 0.5px inset` | Primary control's machined top edge. |
| culture pages | photo-print | `rgba(255,255,255,0.08) 0px 0px 0px 1px inset, rgba(0,0,0,0.2) 0px 2px 4px 0px, rgba(0,0,0,0.4) 0px 12px 24px -8px` | Tactile photographs above the black canvas. |

### Surfaces

#### Workbench canvas · level 0

**Use:** Default background.

**CSS:** `background: #0d0d0d; color: #ffffff`

**Observed:** Near-black rather than pure black; vertical rails and subtle striped outer gutters make it read as a workspace.

**Transfer:** Keep the same ground behind prose and joined cells.

#### Ruled cells · level 0

**Use:** Feature, editorial, FAQ and information grids.

**CSS:** `background: #0d0d0d; border: 1px solid rgba(255,255,255,0.07); border-radius: 0px`

**Observed:** Edges are shared between neighboring cells; wide empty bands remain inside the same rails.

**Transfer:** Use shared borders, not doubled borders or detached card gutters.

#### Application glass · level 1

**Use:** The main product specimen.

**CSS:** `background: rgba(24,24,24,0.82); backdrop-filter: blur(24px); border-radius: 14px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.1); overflow: hidden`

**Observed:** A broad desktop window sits above the canvas, with darker side panels, top chrome and an inset working artifact.

**Transfer:** Stage the new product's actual task or a static representative workflow, not an empty glass panel.

#### Atmospheric closing edge · level 0

**Use:** Low, broad light behind the bottom of the footer.

**CSS:** `background: radial-gradient(at 30% 40%, rgba(58,144,224,0.3), rgba(0,0,0,0) 65%), radial-gradient(at 65% 65%, rgba(232,114,187,0.3), rgba(0,0,0,0) 65%), #0d0d0d; opacity: 0.4; mask-image: radial-gradient(65% 100% at 50% 100%, rgba(0,0,0,1) 10%, rgba(0,0,0,0) 90%)`

**Observed:** Light is wider than the content frame, fades upward into black and has a fine grain.

**Transfer:** Place this as a noninteractive back layer under the footer's lower area; retain clear text above it.

## Components

### Primary button

**Use:** Main conversion control.

**CSS:** `background-color: #993abe; background-image: linear-gradient(rgba(255,255,255,0.09) 0%, rgba(255,255,255,0.05) 49%, rgba(0,0,0,0) 51%), linear-gradient(oklab(0.540077 0.144746 -0.14589), oklab(0.496871 0.133166 -0.134219)); color: #ffffff; height: 32px; padding: 0px 12px; border-radius: 8px; display: inline-flex; align-items: center; gap: 4px; box-shadow: rgba(255,255,255,0.32) 0px 0.5px 0px 0px inset, rgba(255,255,255,0.1) 0px 0px 0px 0.5px inset`

**Text style:** `button` — Inter 500 · 14px/1 · tracking 0.02em

**Observed:** White label, sometimes with a platform icon before it. The opening uses a 30px version; the recruiting opening uses 36px.

**States:** Declared: hover brightness(1.06); focus-visible 2px purple outline with 2px offset; active translateY(0.5px), brightness(0.96) and a faint inset white edge.

### Secondary button

**Use:** Adjacent lower-commitment action.

**CSS:** `background: #202020; color: #ffffff; height: 32px; padding: 0px 12px; border-radius: 8px; box-shadow: inset 0px 0px 0px 0.5px rgba(255,255,255,0.08); display: inline-flex; align-items: center; gap: 4px`

**Text style:** `button` — Inter 500 · 14px/1 · tracking 0.02em

**Observed:** Follows the purple action in paired conversions; also used alone for editorial navigation. The opening uses a 30px version.

**States:** Declared: hover mixes 9% white into the charcoal surface; focus-visible 2px purple outline with 2px offset; active translateY(0.5px).

### Navigation link

**Use:** Top-level navigation in the 72px header.

**CSS:** `padding: 8px; color: #b6b6b6; display: inline-flex; align-items: center`

**Text style:** `navigation` — Inter 400 · 14px/20px · tracking 0.01em

**Observed:** Small brand mark and name sit left, links are centered, and secondary then primary controls sit right.

**States:** Declared: hover text becomes white.

### Announcement pill

**Use:** Compact compatibility or timely message above the opening headline.

**CSS:** `background: #1e1e1e; color: #ffffff; border-radius: 9999px; padding: 6px 14px 6px 6px; display: inline-flex; align-items: center; gap: 10px`

**Text style:** `announcement` — Inter 400 · 14px/1.375 · tracking 0.01em

**Observed:** A tight cluster of small circular symbols precedes one sentence. It belongs to the headline column rather than spanning the hero.

### Feature cell

**Use:** Capability proof through a visual specimen and bottom caption.

**CSS:** `padding: 40px; border-right: 1px solid rgba(255,255,255,0.07); border-bottom: 1px solid rgba(255,255,255,0.07); display: flex; flex-direction: column; justify-content: flex-end; gap: 8px; overflow: clip`

**Text style:** `feature-caption` — Inter 450 · 18px/1.4

**Observed:** Visuals occupy most of the cell above the caption and often fade into black at their lower edges. A bright first clause shares the paragraph with a dim continuation.

**Transfer:** Use a diagram, workflow or genuine interface fragment in place of the source task.

### Editorial card

**Use:** Release, journal or proof stories.

**CSS:** `padding: 40px; display: flex; flex-direction: column; border-right: 1px solid rgba(255,255,255,0.07); border-bottom: 1px solid rgba(255,255,255,0.07); gap: 24px`

**Text style:** `card-body` — Inter 400 · 14px/1.625

**Observed:** A 16:9 image leads, followed by metadata, a card title and a short summary. Cards join into a three-column row without detached rounded backings.

### FAQ row

**Use:** Compact objection handling.

**CSS:** `padding: 14px 40px; display: flex; align-items: center; justify-content: space-between; gap: 16px; color: #ffffff`

**Text style:** `question` — Inter 450 · 16px/1.5

**Observed:** Native disclosure structure with a small downward chevron at the right; the parent supplies the 1px bottom rule. Expanded prose uses the answer recipe and stays inset beneath the label.

**States:** Declared: hover remains transparent; focus-visible 2px purple outline with -2px offset.

### Footer link

**Use:** Grouped utility navigation.

**CSS:** `color: #b6b6b6; display: inline-flex; align-items: baseline; gap: 2px`

**Text style:** `link` — Inter 400 · 14px/20px

**Observed:** Rows sit on a 6px gap beneath tiny uppercase mono group labels. External destinations add a subdued northeast arrow.

**States:** Declared: hover text becomes white.

### Photo print

**Only for:** culture pages

**Use:** Human and place-based storytelling.

**CSS:** `background: #202020; border-radius: 12px; padding: 10px 10px 8px 10px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.08), 0px 2px 4px rgba(0,0,0,0.2), 0px 12px 24px -8px rgba(0,0,0,0.4); transform: translate(0px, 8px) rotate(-7deg)`

**Text style:** `photo-caption` — rollerScript 400 · 16px/1.2

**Observed:** Square image with 5px corners, handwriting beneath, varied rotations and occasional overlapping die-cut stickers. Eight prints form a loose four-column, two-row spread with a reset control.

**Transfer:** Show real people, working places and informal moments, with different small rotations rather than identical repeated angles.

### Listing row

**Only for:** recruiting listings

**Use:** Full-width opportunities with metadata and a trailing action.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); align-items: center; padding: 16px 40px; column-gap: 16px; row-gap: 4px`

**Text style:** `listing-title` — Inter 500 · 14px/20px

**Observed:** Role at left, employment and location metadata in the middle, and a right-aligned learn-more label with arrow. Most rows have a top hairline.

**States:** Declared: hover adds charcoal at 30% opacity; focus-visible 2px purple outline with -2px offset.

## Imagery and graphics

### Working product specimens

**Use:** Opening object and repeated capability cells.

**Observed:** A large dark desktop application contains sidebars, toolbar controls and a smaller live design artifact. Smaller specimens show cursor selection, purple bounds, browser chrome and floating task controls. Warm natural photography appears inside those interfaces, not as full-page background art.

**Transfer:** Use one legible task in a real interface. The minimum equivalent is a carefully composed static window with a sidebar, toolbar and populated working area; preserve large dark negative space around the artifact.

### Drafting marks and textured gutters

**Use:** Persistent framing and connective bands throughout the page.

**Observed:** Fine gray ruler ticks and small coordinate numerals run across the top and down the left in 24px strips. Outer gutters carry very faint diagonal hatching; the luminous concept panel adds tiny dot texture and selection-style corner handles.

**Transfer:** Retain the workbench framing without turning the page into a dense graph-paper illustration.

**Build:** Draw 1px SVG tick lines on 24px strips; use minor ticks at 10px intervals and longer major ticks with tiny mono numerals at wider intervals. Color strokes with rgba(255,255,255,0.15). Use a 6px diagonal repeating pattern at very low white alpha in the gutters. Keep the content area near-black and use four small outlined square handles only on the special concept panel.

### Luminous concept band

**Use:** Signature inset statement or forward-looking callout.

**Observed:** An approximately 1190×451px framed panel glows violet at the lower left and warm amber at the lower right. The top remains nearly black. Three pale handwritten concepts float at different heights and angles above a centered two-line heading and a small charcoal action; fine grain and dots break the smooth light.

**Transfer:** Keep this device on new pages, using product-specific concepts and a relevant next action. Match the soft glow; exact stops are not essential.

**Build:** Inside an overflow-hidden ruled panel, layer two broad radial ellipses anchored near the bottom: violet rgba(153,58,190,0.4) on the left and amber rgba(180,94,22,0.28) on the right, each fading to transparent over roughly 65% of the panel. Add a low-opacity SVG turbulence layer and a sparse tiny-dot SVG texture. Place a three-label script stage above the centered heading, with slight rotations such as -6deg and generous black space around it.

### Closing ambient light

**Use:** Required atmospheric finish beneath the footer links.

**Observed:** A broad grainy blue-to-rose glow rises from the lower edge under the logo and copyright. It stays dim enough that the footer still reads as black; no giant wordmark is visible.

**Transfer:** Use the Atmospheric closing edge surface with a subtle noise layer, maintaining the restrained floor-light effect.

**Build:** Use a 2160×384px light layer centered in a 1440px-wide desktop footer, extending beyond both sides and below the lower boundary. Apply the blue and rose radial gradients, 0.4 opacity and bottom-centered radial mask specified by the surface. Overlay very faint SVG fractal noise and keep links on an independent foreground layer.

### Informal photo spread

**Only for:** culture pages

**Use:** People and place proof.

**Observed:** Candid outdoor groups, terrace work, desks, a pet portrait, coastal scenery and surfing mix in natural color with one monochrome image. Square photos sit in dark tilted prints with handwritten captions and a few white-edged stickers.

**Transfer:** Use a candid mix of work and life instead of uniform corporate headshots. Preserve natural daylight, varied subjects and the physical print treatment.

### Icons

**Observed:** Small filled interface symbols, commonly 14–18px, accompany controls; external arrows are tiny and understated. FAQ chevrons use a 1.5px pale-gray stroke. Larger brand or integration marks appear only as isolated proof objects.

**Transfer:** Choose compact filled symbols for actions and thin chevrons for disclosure. Keep them white or gray except for meaningful status or integration imagery.

## Section recipes

How recurring sections are built.

### First screen: Split promise and working window

**Observed:** A 24px top-and-left ruler frame surrounds a 72px navigation bar. Below it, the text area begins after about 80px of black space. An announcement pill sits over a left-aligned 42px headline, about 480px wide and roughly three lines. Across a broad gap, a similarly narrow support paragraph sits above primary and secondary buttons. The 12-column grid leaves a deliberate empty column between the two text groups. About 92px below the text, a 1277×758px Application glass window extends wider than the text grid. Back to front: black canvas, faint framing marks, text and controls, then the full-width product object. Within the first 900px, the navigation, full promise, support, both actions and upper portion of the object are visible; the object's lower controls and the proof strip continue below the fold.

**Transfer:** Keep the split promise and large working specimen as the default for product landing pages. Without a full application, render a credible task specimen within the same dark window. Culture or recruiting pages instead open with a centered 42px heading, a narrow support paragraph and one purple action over a soft blue-rose light field.

**Avoid:** Do not replace this with a centered billboard headline above tiny isolated cards, or squeeze the entire application object into the first viewport.

**Text style:** `display` — Uncut Sans Variable 600 · 42px/1.04 · tracking -0.025em

### Proof strip

**Observed:** A 200px-tall ruled strip places a centered proof-label above a row of subdued monochrome organization marks. A slow lateral marquee gives the row continuity.

**Transfer:** Use verified organizations or an equivalent compact proof set; keep marks quieter than the promise.

### Capability chapter

**Observed:** A 34px heading appears in a full-width ruled heading cell with 40px padding and an additional 128px dark lead-in. Feature cells follow on a zero-gap three-column grid, including double-width scenes; the next chapter uses two equal cells. Bottom captions align while media above can differ in scale.

**Transfer:** Group a small set of related capabilities around one transformation. Use joined cells and a range of specimen sizes, not an icon for every feature.

**Text style:** `heading` — Uncut Sans Variable 600 · 34px/1.1 · tracking -0.025em

### Luminous statement

**Observed:** The Luminous concept band contains three handwritten labels across a roughly 768px stage, then a centered 34px two-line heading and Secondary button. The panel uses 64px vertical padding and shared rails.

**Transfer:** Use the concepts as an expressive summary of the product's possibilities rather than an additional bullet list.

**Text style:** `heading` — Uncut Sans Variable 600 · 34px/1.1 · tracking -0.025em

### Editorial proof row

**Observed:** A section-heading cell places a 34px two-line title at left and a small Secondary button at right. Below, three Editorial cards share edges and equal column widths.

**Transfer:** Use releases, case studies or journal stories with real images and compact date labels.

**Text style:** `heading` — Uncut Sans Variable 600 · 34px/1.1 · tracking -0.025em

### Split objection panel

**Observed:** Two equal columns: a 40px-padded heading and short contact line on the left, seven approximately 53px FAQ rows on the right. A single vertical hairline separates introduction and disclosures.

**Transfer:** Keep the introduction short enough to leave dark space below it. Answer practical objections with plain paragraphs rather than promotional cards.

**Text style:** `heading` — Uncut Sans Variable 600 · 34px/1.1 · tracking -0.025em

### Closing promise and ambient footer

**Observed:** A 705px closing area starts with a broad ruled call-to-action row. A 42px two-line promise sits left and paired controls align toward the lower right. A horizontal rule separates it from five footer link groups with 10px mono uppercase labels. Below the links, a small mark and subdued copyright line sit over Closing ambient light; the glow grows toward the bottom rather than behind the call to action.

**Transfer:** Repeat the core promise more briefly, retain the paired-control hierarchy and finish with the illuminated floor edge rather than a second hero image.

**Text style:** `display` — Uncut Sans Variable 600 · 42px/1.04 · tracking -0.025em

### Culture heading and text cells

**Only for:** culture and recruiting pages

**Observed:** Mixed-case 12px mono label precedes a 34px heading by 12px inside a 40px-padded ruled cell. Benefits use a two-column, two-row zero-gap grid with 18px titles, 8px title-to-copy gaps and 15px body text.

**Transfer:** Use this variant for people, principles or organizational content where readable text carries more weight than application media.

**Text style:** `heading` — Uncut Sans Variable 600 · 34px/1.1 · tracking -0.025em

### Culture photo table

**Only for:** culture pages

**Observed:** A ruled section heading sits above a loose four-column spread of Photo prints. The image grid uses 24px column gaps and 36px row gaps, with 40px outer insets. Stickers overlap a few corners and a quiet reset action sits at the lower right.

**Transfer:** Bring warmth to the technical frame with authentic pictures, restrained rotations and a few tactile overlays.

### Opportunity list

**Only for:** recruiting listings

**Observed:** The ruled heading area pairs a section title with a short recruiting paragraph; a full-width stack of Listing rows follows directly beneath it.

**Transfer:** Adapt the row anatomy to opportunities, preserving left title, middle metadata and trailing arrow action.

## Page flow

**Storyline:** promise → tangible proof → focused capability or human chapters → current activity or opportunities → objections when needed → repeated promise and illuminated close

### Product marketing: make a new collaborative tool feel tangible and ready to use

1. **Promise** — Split headline and support above an oversized working application.
2. **Social proof** — Small uppercase mono label and subdued logo strip.
3. **Compatibility reassurance** — Centered compact statement with existing-tool symbols and a luminous backing.
4. **Capability chapters** — Joined visual cells explain successive transformations through real work specimens.
5. **Forward-looking proof** — Handwritten concepts float in a luminous statement panel.
6. **Current activity** — Three image-led editorial cards demonstrate ongoing work.
7. **Objection handling** — Split heading and compact disclosures.
8. **Closing call** — Short repeated promise, paired controls, grouped footer links and ambient bottom light.

**Transfer:** Choose the chapters that explain the new product's work; preserve the contrast between real specimens, technical framing and expressive light rather than copying a fixed section count.

### Recruiting: explain the proposition, show the people and lead to specific opportunities

1. **Promise** — Centered heading, short support and one action over blue-rose atmospheric light.
2. **Practical reassurance** — Two-column text grid describing concrete benefits.
3. **Human proof** — Tilted dark photo prints with handwriting and stickers.
4. **Opportunity** — Compact full-width listing rows.
5. **Closing call** — The same paired-action promise and illuminated footer used by the product experience.

**Transfer:** Use the centered opening and photographic variant for culture-oriented content; retain the shared type, rails, controls and closing treatment.

## Writing

Direct and product-literate, with a maker's warmth. Confidence comes from describing what the reader can do and how work moves, not from abstract superiority.

**Do not copy:** Do not reuse Wonder's name, marks, stickers, product artwork, company names, dates, talent-percentile claims, benefit promises or technical compatibility claims as facts about another product. Source examples illustrate cadence only.

- **Addressing the reader:** Use you and your for the reader's tools, team and work. Use we for human recruiting language; product explanations can name the product once and then stay direct.
- **Rhythm:** Headlines are short sentences or paired clauses, sometimes ending in a clipped fragment. Support is normally one plain sentence; controls use short task labels. No exclamation marks are needed.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a shared place or mode of working, linking the user to an outcome. | 10–15 words | “Where you and your agents design and code on the same canvas.” |
| Capability heading | Describe a transformation, then close with a short reversal or outcome. | 8–12 words | “From live product to editable design. And back.”<br>“Start with a design. Make it something you can try.” |
| Reassurance | Recognize what the reader already has, then remove a specific friction. | One heading and one short sentence | “Bring the agent subscriptions you already have.”<br>“Your subscription, skills, and plugins. No extra credit costs.” |
| Primary action | State the action and meaningful destination or platform. | 2–4 words | “Download for macOS”<br>“View open positions” |
| Human chapter | Use everyday language about people and care rather than employer-brand jargon. | 4–7 words | “Built by people who care” |

**Words and phrasing to use:** bring your; start with; connect; explore; try; share; your team; live; existing; details

**Avoid:** revolutionary; unleash; game-changing; supercharge; world-class synergy; limitless magic

**Rules:**

- Use an active verb to explain each capability.
- Follow the bright lead clause with a concrete explanation, not a second slogan.
- Reassurance should resolve a practical concern about ownership, setup, cost or compatibility.
- Use actual task names and tangible objects; avoid stacking broad aspirational nouns.

## Do's and Don'ts

### Do

- Keep the main promise at 42px with 1.04 line height and -0.025em tracking.
- Let the first working specimen exceed the text-grid width and continue below the fold.
- Use 40px desktop cell insets and shared 1px white-at-7% rules.
- Keep purple conversion controls compact at 32px high with 8px corners.
- Use 12px monospace metadata and 10px uppercase footer labels to make the framing feel technical.
- Fade supporting feature clauses to 50% white while keeping the leading action white.
- Include a handwritten concept-and-light device and an ambient illuminated footer edge.
- Use the centered, single-action opening only for the culture-oriented variant.

### Don't

- Do not convert joined feature cells into a collection of 24px-radius floating cards.
- Do not spread saturated purple over whole marketing sections; reserve solid purple for small actions.
- Do not turn the 24px script annotations into a headline font.
- Do not make navigation as bright or heavy as the main heading; it uses 14px regular subdued text.
- Do not use pure white prose throughout; maintain the 70%, 50% and 40% neutral hierarchy.
- Do not add thick outer borders or prominent drop shadows to ordinary content cells.
- Do not replace the footer's small mark with an invented monumental wordmark.
- Do not carry the tilted photo-and-sticker spread into ordinary product capability grids.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare 0.15s transitions with cubic-bezier(0,0,0.2,1); navigation color declares 0.15s cubic-bezier(0.4,0,0.2,1).
- The proof-logo marquee declares 40s linear infinite movement.
- Opening words declare a 1s cubic-bezier(0.19,1,0.22,1) entrance; the product showcase declares the same duration and easing with a 0.4s delay.
- FAQ background transition is 0.18s cubic-bezier(0.23,1,0.32,1).

**Transfer:**

- Keep control motion small: brightness or surface shifts, and a 0.5px press displacement rather than scaling the buttons.
- Use the slow proof-strip motion as continuity beneath the static product stage.

**Unknown:**

- Exact shader behavior, scroll-trigger choreography and photo-drag physics are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 600px, 640px, 768px, 1024px, 1280px and 1536px.
- Navigation links are hidden below the extra-wide layout; small header conversion controls are hidden below the small layout.
- Cell padding changes from 24px to 40px. Capability grids declare single-column and multi-column variants; footer groups declare two, three and five columns.

**Transfer:**

- On narrow screens, stack promise, support and actions above the application specimen, preserving the large working-object impression rather than shrinking every internal label into illegibility.
- Collapse joined cells into a single rail-bounded column. Reduce photo-spread columns while retaining small rotations and avoiding overlap over text.
- Let the drafting strips yield usable content space on small screens rather than keeping desktop insets unchanged.

**Unknown:**

- Mobile rendering and exact media-specific sizing were not observed; narrow-screen composition guidance is an adaptation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
