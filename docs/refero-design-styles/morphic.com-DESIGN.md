# Morphic — cinema meets workbench

## Overview

A black-box creative studio with tightly packed grotesk headlines and vivid windows into finished work. White and charcoal typography, small electric-blue actions, soft pools of light and dark interface demonstrations create a cinematic rather than corporate mood. The layouts are spacious around the narrative and dense inside the media, well suited to creative software and visually expressive tools.

### Essentials

- Headlines speak in a bright statement and a dim echo: Inter 700 at 52px/60px with -2.5px tracking, first line #fafafa and second line white at 40% opacity.
- The opening is a split promise above a film strip: a 1040px content area pairs a two-line heading with a 384px support column; two staggered rows of 140px-high media extend to the viewport edges.
- Actions stay small against the spectacle: 40px-high pills with 9px 18px padding; electric blue leads the opening, while off-white leads the closing call and the 32px-high navigation action.
- Color belongs to the work, not the page furniture: retain a black canvas throughout, neutral white-opacity panels at 5–8%, and #0075ff only for short actions and tiny interface accents. Saturated imagery provides the broad color fields.
- Product proof floats in light rather than a bright card: a 1040px-wide dark interface is backed by a soft, low-intensity colored halo fading into black. Include this luminous stage; a carefully composed dark prototype with real sample content is the fallback.
- The ending becomes an editing instrument: compact 24px-high navigation clips sit beneath a second-mark ruler, above a huge outlined word sculpture fading off the bottom. Carry this timeline-and-outline device into every new marketing page with the new product's own name.
- A tactile dark object punctuates the final invitation: a 350×301px low-key object portrait precedes a centered 40px/48px closing line, a 490px text column and small paired pills. Use a simple purpose-related object rendered with restrained edge lighting when no elaborate artwork exists.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0075ff` | `--color-blue` | action, link, accent | Opening conversion action and small links or interaction marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black stage | `#000000` | `--color-canvas` | background, text | Continuous page canvas and dark text on off-white actions. |
| Faint edge | `#080808` | `--color-edge-faint` | border | Visible 3% white over black; extremely subtle outlines. |
| Soft charcoal | `#0d0d0d` | `--color-panel-soft` | surface, border | Visible 5% white fill over black; capability cards and their faint edges. |
| Raised charcoal | `#141414` | `--color-panel` | surface | Visible 8% white fill over black; FAQs, secondary pills and pricing panels. |
| Dim clip | `#171717` | `--color-clip-dim` | surface | Lower-row footer clips; also a dark interface-shell tone. |
| Clip charcoal | `#1e1e1e` | `--color-clip` | surface | Upper-row footer navigation clips. |
| Media backing | `#212121` | `--color-tile` | surface | Dark backing behind full-bleed workflow imagery. |
| Lifted charcoal | `#242424` | `--color-hover` | surface | Footer hover fill. |
| Clip edge | `#252525` | `--color-clip-edge` | border | Visible 6% white outline over the dim footer clip. |
| Headline echo | `#666666` | `--color-echo` | text | Visible white at 40% over black; the second half of a headline. |
| Utility gray | `#737373` | `--color-muted` | text | Footer labels and subordinate utilities. |
| Support gray | `#999999` | `--color-support` | text | Visible white at 60% over black; supporting prose. |
| Soft white | `#f5f5f5` | `--color-action-text` | text | Button labels and compact utility text. |
| Near-white | `#fafafa` | `--color-foreground` | text, action | Main headlines, navigation and inverse action fill. |
| Layer white | `#ffffff` | `--color-white` | accent, border | Base for translucent white layers; not a white page background. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| special pricing offers | Offer indigo | `#4558e7` | `--color-offer-indigo` | accent | Source hue for a diffuse indigo pool behind an offer; never a solid panel fill. |
| special pricing offers | Offer rose | `#91213d` | `--color-offer-rose` | accent | Source hue for a very diffuse, dark rose light behind an offer; blur keeps the visible result near black. |
| special pricing offers | Pencil gold | `#b19943` | `--color-annotation` | text | Handwritten eligibility note. |

## Typography

- **inter** — All marketing headings, prose, actions and compact navigation. Contemporary grotesk with a high x-height; bold headlines are tightly tracked, while UI-sized labels stay medium weight. Font stack: "inter", Arial, sans-serif.
- **nothingYouCouldDo** (only for special pricing offers) — One handwritten eligibility annotation. Loose connected handwriting that feels like a gold-pencil margin note. If unavailable, use **Nothing You Could Do**. Font stack: "nothingYouCouldDo", "Nothing You Could Do", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | inter | 700 | 52px | 60px | -0.048em | Opening and major section heading pairs. |
| heading | inter | 700 | 40px | 48px | -0.0625em | Centered proof quotations, smaller gallery chapters and closing calls. |
| lead | inter | 500 | 20px | 28px | -0.02em | Hero support and centered conversion copy. |
| body | inter | 500 | 18px | 24px | -0.022em | Capability descriptions and short explanatory labels. |
| action | inter | 500 | 16px | 24px | normal | Main 40px-high action pills. |
| eyebrow | inter | 600 | 16px | 24px | normal | Sentence-case chapter label with a small symbol. |
| caption | inter | 500 | 14px | 1.44 | normal | Media captions, navigation links and compact action labels. |
| nav-action | inter | 500 | 14px | 1.44 | -0.01em | Small inverse navigation conversion pill. |
| footer-link | inter | 500 | 12px | 14px | normal | Navigation labels inside timeline clips. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| enterprise proof sections | stat | inter | 700 | 96px | 1.02 | -0.04em | One monumental result with unit included on the same line. |
| pricing and enterprise pages | commercial-display | inter | 700 | 52px | 60px | -0.05em | Pricing and enterprise headline variant. |
| FAQ sections | faq-heading | inter | 700 | 40px | 48px | -0.05em | Short heading beside the FAQ stack. |
| pricing pages | price | inter | 700 | 36px | 1.2 | -0.04em | Credit-pack amounts. |
| feature explainer pages | article-quote | inter | 600 | 32px | 1.2 | -0.025em | Editorial testimonial with blue rule. |
| feature explainer pages | article-title | inter | 500 | 24px | 1.25 | -0.025em | Restrained opening title for a single-feature explainer. |
| feature explainers and galleries | article-body | inter | 500 | 18px | 28px | -0.022em | Longer feature explanations and gallery introduction prose. |
| special pricing offers | annotation | nothingYouCouldDo | 400 | 18px | 24px | -0.002em | A diagonal human note against otherwise systematic pricing. |
| FAQ and pricing sections | question | inter | 500 | 16px | 22px | -0.015em | FAQ questions and comparison feature labels. |

**Notes:**

- The dim echo keeps exactly the size, weight and baseline rhythm of the bright line; this is a two-tone typographic hierarchy, not a gradient headline.
- Headlines are heavy and unusually tight; 40px closing headings retain -2.5px tracking rather than relaxing to ordinary body spacing.
- Use sentence case throughout, including eyebrows. Most text is medium weight; do not turn the whole page into thin gray type.
- The outline word sculpture is artwork, not a second text heading; keep it subordinate through its faint stroke and bottom fade.

## Layout

**Density:** Airy narrative spacing around dense media and utility clusters.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Paired closing actions and symbol-label gaps. |
| 10px | Hero action pair and closing heading-to-support gap. |
| 12px | Capability rail, pricing grid and masonry gutters. |
| 16px | Media-label separation and compact prose groups. |
| 20px | Container side padding and pricing panel interiors. |
| 24px | Feature-grid gutters and component content groups. |
| 28px | Hero support-to-action spacing and object-to-closing heading. |
| 40px | Closing copy-to-action separation. |
| 60px | Wide three-column feature gutters and closing section top padding. |
| 96px | Separation before the timeline footer. |
| 100px | Product chapter top offset. |
| 140px | Large chapter bottom breathing room. |
| 200px | Deep chapter separation on long enterprise narratives. |

### Containers and grids

- **marketing container**: max width 1080px · side padding 20px. Centered outer container leaves 1040px usable content at desktop.
- **hero split**: 2 columns · gap 96px. Left statement paired with a 384px-wide right support and action column; align the bottom edges rather than equalizing copy lengths.
- **three column proof**: max width 1040px · 3 columns · gap 24px. Compact demonstration cards with captions beneath.
- **wide feature columns**: max width 1040px · 3 columns · gap 60px. Short text-led feature summaries beneath a large product stage.
- **footer clips**: max width 955px · gap 2px. Centered navigation clip rows within a full-width ruler.
- **article column** (only for feature explainer pages): max width 512px. Narrow text column within an 800px feature-explainer wrapper.
- **faq column** (only for FAQ sections): max width 640px. Question stack beside a short left-hand heading.
- **gallery masonry** (only for gallery pages): max width 1040px · 3 columns · gap 12px. Independent stacks of square and landscape media.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action pills | 9999px (pill) |
|  | media strips | 16px |
|  | workflow tiles | 24px |
|  | capability cards | 32px |
|  | footer clips | 6px |
| FAQ sections | faq panels | 16px |
| gallery pages | gallery tiles | 8px |
| pricing pages | pricing actions | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| poster depth | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Very restrained depth on overlapping portrait posters; the overlap does more work than the shadow. |

### Surfaces

#### Black stage · level 0

**Use:** Unbroken background behind all narrative chapters.

**CSS:** `background: #000000; color: #fafafa`

**Observed:** Sections separate through space, media and light rather than alternating canvas colors.

**Transfer:** Keep one continuous dark world for a new product.

#### Soft capability panel · level 1

**Use:** Large media-led capability cards.

**CSS:** `background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.05); border-radius: 32px; overflow: hidden`

**Observed:** A near-black rounded shell with very faint edges; imagery occupies its upper portion.

**Transfer:** Use for rich capabilities rather than every paragraph.

#### Raised utility panel · level 1

**Use:** Quiet secondary actions, FAQs and pricing groups.

**CSS:** `background: rgba(255,255,255,0.08); border-radius: 16px`

**Observed:** White-opacity fill establishes a barely raised dark plane. FAQ edges add 3% white; pills use their own fully rounded silhouette.

**Transfer:** Use this material for grouped decision-making content.

#### Navigation haze · level 2

**Use:** Soft occlusion behind fixed navigation.

**CSS:** `backdrop-filter: blur(12px); mask-image: linear-gradient(#000000 40%, rgba(0,0,0,0) 100%); height: 120px`

**Observed:** A separate faded blur layer sits behind the 72px navigation bar, which adds a 40%-black-to-transparent vertical gradient.

**Transfer:** Let passing imagery blur gently beneath the header, without a hard rectangular bottom edge.

#### Atmospheric proof veil · level 1

**Use:** Darkened full-width media behind a quote or result.

**CSS:** `background: linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.65)), linear-gradient(90deg, #000000, rgba(0,0,0,0) 50.48%, #000000); backdrop-filter: blur(8px)`

**Observed:** A low-contrast image or film dissolves into black at the sides and below; text remains crisp in front.

**Transfer:** Use real product-related imagery as an atmospheric texture, not as competing foreground content.

## Components

### Navigation

**Use:** Persistent access and conversion.

**CSS:** `position: fixed; top: 0px; height: 72px; width: 100%; padding: 0px 32px; display: flex; align-items: center; justify-content: space-between; background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0))`

**Text style:** `caption` — inter 500 · 14px/1.44

**Observed:** Compact wordmark left, centered link cluster with 28px gaps, login and Navigation action on the right; Navigation haze sits behind it.

**States:** Declared: hover link color becomes near-white at 50% opacity; focus-visible treatment is not specified.

### Primary button

**Use:** Opening self-serve conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 9px 18px; border-radius: 9999px; background: #0075ff; color: #f5f5f5`

**Text style:** `action` — inter 500 · 16px/24px

**Observed:** Short text-only pill paired with a darker secondary action; no large arrow or decorative shadow.

**States:** Declared: hover background #0065db; focus-visible treatment is not specified.

### Inverse button

**Use:** Closing conversions and centered collaboration invitation.

**CSS:** `height: 40px; padding: 9px 18px; border-radius: 9999px; background: #fafafa; color: #000000; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — inter 500 · 16px/24px

**Observed:** The bright pill takes over from blue in the final invitation. Enterprise openings also use this inverse variant.

**States:** Declared: hover background becomes neutral light gray, lab(84.92% 0 -.0000119209); focus-visible treatment is not specified.

### Secondary button

**Use:** Demo and exploration actions beside a primary.

**CSS:** `height: 40px; padding: 9px 18px; border-radius: 9999px; background: rgba(255,255,255,0.08); color: #f5f5f5; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — inter 500 · 16px/24px

**Observed:** The opening variant uses 16% white for greater visibility. Rail links can include a small up-right arrow and a 4px backdrop blur.

**States:** Declared: hover background white at 12%; focus-visible treatment is not specified.

### Navigation action

**Use:** Compact persistent conversion.

**CSS:** `height: 32px; padding: 9px 14px; border-radius: 9999px; background: #fafafa; color: #000000; display: inline-flex; align-items: center; justify-content: center; box-sizing: border-box`

**Text style:** `nav-action` — inter 500 · 14px/1.44 · tracking -0.01em

**Observed:** A smaller inverse pill anchors the right end of the header.

**States:** Declared: hover background becomes neutral light gray, lab(84.92% 0 -.0000119209); focus-visible treatment is not specified.

### Workflow tile

**Use:** Visual discovery rail.

**CSS:** `width: 264px; height: 264px; border-radius: 24px; background: #212121; position: relative; overflow: hidden`

**Text style:** `caption` — inter 500 · 14px/1.44

**Observed:** Full-bleed film still or video; title then one-line description pinned at the bottom over a black gradient and localized blur. Adjacent tiles have 4px gaps. A rail begins at the content edge and continues beyond the viewport.

**Transfer:** Represent a concrete outcome in each tile rather than an abstract icon.

### Capability card

**Use:** Rich capability rail.

**CSS:** `width: 340px; height: 482px; border-radius: 32px; background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.05); overflow: hidden`

**Text style:** `body` — inter 500 · 18px/24px · tracking -0.022em

**Observed:** Upper 300px holds the demonstration; lower copy combines a bright short name and muted continuation. A small circular plus sits at the lower right. Cards run horizontally with 12px gaps.

**States:** Declared: hover background white at 8%; background transition 0.1s ease-in-out.

**Transfer:** Keep the demo substantial and the explanatory sentence compact.

### Timeline link clip

**Use:** Footer navigation as an editing timeline.

**CSS:** `height: 24px; padding: 4px 8px; border-radius: 6px; background: #171717; border: 1px solid rgba(255,255,255,0.06); color: #737373; display: flex; align-items: center; box-sizing: border-box`

**Text style:** `footer-link` — inter 500 · 12px/14px

**Observed:** Two compact centered rows below a seconds ruler; upper clips use #1e1e1e, lower clips #171717. Row gap is 8px and horizontal gaps are 2px.

**States:** Declared: hover text #f5f5f5 and background #242424.

### FAQ row

**Only for:** FAQ sections

**Use:** Objection handling without a dense text wall.

**CSS:** `background: rgba(255,255,255,0.08); border: 1px solid rgba(255,255,255,0.03); border-radius: 16px; max-width: 640px; min-height: 60px`

**Text style:** `question` — inter 500 · 16px/22px · tracking -0.015em

**Observed:** A full-width trigger has 18px inner padding, question left and a 20px muted expansion symbol right. Rows have a 4px outer gap; the heading sits separately to the left.

**Transfer:** Use actual reader questions rather than feature slogans.

### Credit pack card

**Only for:** pricing pages

**Use:** Small purchasable capacity bundles.

**CSS:** `background: rgba(255,255,255,0.08); border-radius: 16px; padding: 18px 20px 20px; display: flex; flex-direction: column; gap: 20px; overflow: hidden`

**Text style:** `price` — inter 700 · 36px/1.2 · tracking -0.04em

**Observed:** A 514×191px panel places tier label above the amount, credit allowance at lower left and compact 36px-high purchase action at lower right. Four panels form a two-column grid with 12px gaps; a faint green glow marks the largest bundle.

**Transfer:** Make amount and allowance scannable without multiplying bright recommended-plan badges.

### Editorial quote

**Only for:** feature explainer pages

**Use:** Human validation inside narrow explanatory prose.

**CSS:** `border-left: 1px solid #0075ff; padding-left: 16px; margin-top: 64px; margin-bottom: 64px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `article-quote` — inter 600 · 32px/1.2 · tracking -0.025em

**Observed:** A left-aligned quote is followed by a small blue author line. It remains in the 512px reading column rather than spanning the page.

**Transfer:** Use one specific experience with attribution, not a large wall of testimonials.

## Imagery and graphics

### Cinematic media strips

**Use:** First-screen proof and recurring discovery rails.

**Observed:** Vivid but carefully composed films, photography, anime and stylized illustration alternate: colored studio portraits, dramatic night scenes, landscapes and action. Two staggered rows have mixed-width tiles about 140px high with 16px corners; the lower row fades into black. Images occupy much more area than labels.

**Transfer:** Use the new product's outputs or usage scenes with similarly deliberate lighting. For a nonvisual product, create varied close-up artifact compositions or real interface-result sequences rather than unrelated stock scenery.

**Build:** Arrange two overflow-hidden flex tracks with 16px gaps, differing starting offsets and mixed square/landscape proportions. Place a bottom overlay from transparent black at 20% to opaque black at 100% across the lower track.

### Luminous product stage

**Use:** Required product demonstration treatment.

**Observed:** A broad dark workspace floats above a hazy blue, green or warm amber pool. Dark toolbars and side panes frame vivid results; the bottom often dissolves into black. The stage is roughly 1040px wide, substantially larger than its heading.

**Transfer:** Create a legible dark prototype with one believable task, a few controls and finished artifacts. Keep the halo subtle and image-driven rather than a neon frame.

**Build:** Put a blurred enlargement of the foreground artwork behind the interface at low opacity; mask it with black edge and bottom gradients. A CSS alternative uses wide radial pools: blue rgba(0,117,255,0.16) at upper left and violet rgba(132,104,255,0.12) at right, each fading to transparent by 72%, blurred 48px. Leave the interface itself crisp.

### Poster fan

**Use:** A dramatic authored-work proof chapter.

**Observed:** Five portrait posters about 357×488px overlap by 130px and rotate slightly in alternating directions. Red, pale yellow and teal film art forms a tactile fan across the lower part of a spacious black section.

**Transfer:** Use original project covers, case-study jackets or finished artifacts with portrait proportions. Minimum version: three art-directed covers with strong cropping and a small alternating tilt.

**Build:** Use 10px rounded portrait rectangles in a flex row with negative 130px overlap, shallow black shadows and alternating small rotations. Keep the top edges loosely aligned; bring successive covers forward with z-index.

### Low-key closing object

**Use:** Required tactile punctuation above the final invitation.

**Observed:** A black director's chair, front-facing and isolated, emerges from black with very subtle edge lighting and a readable pale label. Its image box is 350×301px; the object is not surrounded by a visible card.

**Transfer:** Render or photograph a purpose-related object in charcoal materials with soft rim lighting. A simple geometric object is sufficient if its silhouette is clear and its base blends into the page.

**Build:** Use a transparent-background object render or tightly masked photograph on pure black, lit from above and slightly to one side. Keep the brightest surface below headline brightness except for a small pale label; add a short bottom fade.

### Timeline and outline word sculpture

**Use:** Required full-width footer identity device.

**Observed:** A tiny seconds ruler spans the width above clip-like navigation. Below, an enormous thin outlined name runs beyond the bottom edge and fades away. Legal and social links remain readable in front.

**Transfer:** Use the new product's name or a short meaningful word, stretched across the width as outline artwork. The editing-ruler metaphor can remain even for a different kind of tool.

**Build:** Draw 1px charcoal ticks in SVG at regular intervals with small second labels; use slightly taller ticks at major divisions. Under the clip rows, set an SVG text/path word to fill the width, fill none and a faint white stroke. Translate the artwork down about 48% of its own height; mask from opaque at 5% to transparent at 55%. Keep foreground legal links outside the mask.

### Atmospheric proof field

**Use:** Quotation and quantified-result chapters.

**Observed:** Dark, heavily defocused landscape or film footage produces a soft gray/olive/teal cloud behind centered white text, dissolving into the same black canvas.

**Transfer:** Blur a relevant product or customer scene until it becomes light and tone; the message must remain the sharpest object.

**Build:** Cover a broad shallow band with media, apply 8px backdrop blur plus a 65% black veil, then horizontal black-to-transparent-to-black and vertical edge fades. Keep light concentrated behind the center, not around every edge.

### Paired transformation panels

**Only for:** feature explainer pages

**Use:** A compact before-and-after concept illustration.

**Observed:** Two slightly skewed landscape images overlap in depth; the rear is darker with a dashed selected area, the front is bright and complete. Both float directly on black.

**Transfer:** Show a changed artifact with selection or edit context. Preserve continuity in viewpoint and lighting between states.

**Build:** Place two rounded landscape panels in a 672×596px image stage. Apply matching perspective/skew, offset the front to the right and lower; darken the back and add one fine dashed selection outline. Do not add a bright frame around the whole stage.

### Masonry output wall

**Only for:** gallery pages

**Use:** Long-form breadth of finished work.

**Observed:** Three 339px-wide columns mix square and landscape output imagery, with 12px gutters, 8px corners and faint 8% white outlines. Saturated photography and illustrated scenes are interleaved; captions are generally absent. One dark editorial invitation interrupts a column.

**Transfer:** Mix original outputs in varied aspect ratios while preserving consistent column width. Insert a concise participation or discovery card into the wall, not a floating modal.

### Drafted offer panel

**Only for:** special pricing offers

**Use:** A human exception inside a systematic pricing page.

**Observed:** A dark offer panel is drawn with faint dashed construction lines and subtle indigo and rose light. A gold handwritten eligibility note rises diagonally across the right side.

**Transfer:** Reserve this look for a genuinely distinct offer or eligibility condition, not all pricing cards.

**Build:** Use a 1040px-wide black panel with dashed low-opacity white horizontal and vertical guide lines. Place two 100px circular lights in rose and indigo, blur each 125px behind content. Rotate the gold handwritten note roughly -12deg; keep the prices and benefits aligned to the construction grid.

### Icons

**Observed:** Small outline arrows, chevrons, plus signs and checks use round caps and restrained strokes. Utility icons are usually 16px with 1.3px strokes; FAQ symbols are 20px with 1.5px strokes; pricing checks are 22px with 1.5px strokes. Muted gray is more common than blue.

**Transfer:** Use simple rounded line icons in these sizes. Keep media art expressive and navigation symbols understated; blue belongs to a concrete active control.

## Section recipes

How recurring sections are built.

### First screen: Split promise and film-strip opening

**Observed:** Black stage behind a fixed Navigation and its Navigation haze. In the centered 1040px content area, a two-line bright/dim heading sits on the left and a 384px support-and-actions column on the right. The support begins slightly higher, while the heading and action pair finish near the same baseline. Display is 52px/60px; support is lead. There is generous black space before a small rail label and arrows, then two staggered edge-to-edge cinematic media strips. Within the first 900px, the full heading, support, blue Primary button and Secondary button, both media rows and a small testimonial line are visible. The next product chapter begins below this first screen; no giant interface object competes with the opening strips.

**Transfer:** Use a promise plus a dim audience or outcome echo, followed by tangible result imagery. If finished visual work is unavailable, compose varied real artifacts or task-result interface frames into the same strips. Enterprise pages open with a similar split heading but an Inverse button and a large luminous interface below. Pricing opens centered with a single bright headline, support and action before billing controls. Galleries open with a left two-tone title and right support above portrait covers. Feature explainers use the narrow article-title and a paired transformation illustration.

**Avoid:** Do not replace the split composition with a centered oversized slogan, a full-bleed hero photograph, or a single glowing dashboard. Do not apply a gradient to the echo line.

**Text style:** `display` — inter 700 · 52px/60px · tracking -0.048em

### Heading pair and rail

**Observed:** Bright heading over dim echo, left aligned inside the marketing container. Secondary button and circular rail controls sit to the right. Workflow tile rails start 46px below; capability media rails use larger chapter breathing room. Rails overflow the content width and reveal a partial next tile.

**Transfer:** Pair a concrete category with an outcome, then present visual examples. Use rails to imply breadth without compressing all examples into a grid.

**Text style:** `display` — inter 700 · 52px/60px · tracking -0.048em

### Product stage chapter

**Observed:** A two-tone heading leads a Luminous product stage. The stage is 1040px wide; short feature summaries can form three columns below with 60px gutters. Dark chrome, tabs and a single active blue control keep the demo recognizable as a tool.

**Transfer:** Give each chapter one substantial product operation. Use a believable completed artifact rather than an empty canvas.

### Centered collaboration invitation

**Observed:** A compact centered display heading and lead paragraph sit in a wide black field with Inverse button and Secondary button. Three colored cursor/name markers occupy the surrounding negative space rather than enclosing the copy.

**Transfer:** Use collaborative presence markers only when shared work is a real product behavior; otherwise use the same centered invitation without implying fake live users.

### Atmospheric endorsement

**Observed:** Atmospheric proof field backs a centered heading-size quotation. A small muted attribution and publication mark sit beneath, with roughly 180px vertical section padding.

**Transfer:** Use one authentic external endorsement or concise proof statement; let the blurred field carry atmosphere, not information.

**Text style:** `heading` — inter 700 · 40px/48px · tracking -0.0625em

### Object-led closing and timeline footer

**Observed:** Low-key closing object precedes a centered heading in a 490px text column with a 28px gap. Lead copy follows at 10px and paired Inverse button/Secondary button at 40px. Enterprise variants use one sales action and a wider line. After 96px of separation, the footer places a small wordmark, ruler and Timeline link clip rows over the Timeline and outline word sculpture. The feature explainer ends directly with the same footer after FAQs rather than adding a second sales stage.

**Transfer:** Close with a tangible object and a short next-step invitation; sales pages can reduce the action count. Preserve the timeline footer as the final identity gesture.

**Text style:** `heading` — inter 700 · 40px/48px · tracking -0.0625em

### Monumental result

**Only for:** enterprise proof sections

**Observed:** A single 96px/1.02 bold number-plus-unit line is centered in a roughly 550px-high Atmospheric proof field. A dim 40px/48px descriptor follows after 8px, then a short 18px supporting sentence after 24px.

**Transfer:** Choose one defensible result, keep the unit attached to the number and explain its context in one sentence.

**Text style:** `stat` — inter 700 · 96px/1.02 · tracking -0.04em

### Operational capability chapters

**Only for:** enterprise pages

**Observed:** An initial split chapter pairs a vertical list of five capabilities and a thin active rail with a tall product preview. Later chapters alternate three compact demonstration cards, a four-column icon/text matrix with 24px gutters, and a three-column trust summary. Headings retain the bright/dim pair.

**Transfer:** Move from a few substantial operations to compact administrative detail; use full panels only where a demonstration needs one.

### Commercial decision system

**Only for:** pricing pages

**Observed:** A centered title/support/action opening leads to Monthly/Yearly controls. Four plan columns share a 1040px-wide, 16px-rounded dark panel, with one blue 36px-high action and gray alternatives. Two wide exception panels follow. Credit pack card grid, Drafted offer panel and a three-column comparison table expand the decision. Comparison headers use dark selects; included features are pale and excluded ones muted.

**Transfer:** Keep the plans visually equal except for one action emphasis. Place special offers and exhaustive detail outside the main scan path.

### Narrow feature explanation

**Only for:** feature explainer pages

**Observed:** A 512px reading column opens with article-title, short explanation and two compact actions, followed by Paired transformation panels. Paragraphs explain behavior, an Editorial quote supplies human validation, and an embedded tutorial plus a three-image example rail demonstrate use. A text link leads to a FAQ section.

**Transfer:** Keep an individual feature more editorial and restrained than a broad landing page; use a transformation illustration rather than inventing another giant slogan.

**Text style:** `article-title` — inter 500 · 24px/1.25 · tracking -0.025em

### Gallery immersion

**Only for:** gallery pages

**Observed:** A two-tone display introduction with right-hand explanation opens onto a horizontal portrait-cover rail. A smaller heading pair then introduces the Masonry output wall; a compact participation invitation appears among the media and the wall fades into black before the closing call.

**Transfer:** Let the work sustain a long browse; vary image aspect ratios rather than adding repetitive captions to every tile.

### Split FAQ

**Only for:** FAQ sections

**Observed:** A short 40px heading occupies the left side while a 640px-wide stack of FAQ row components occupies the right. Rows retain the compact 60px closed height and 4px gap; the list can be much longer than the heading.

**Transfer:** Choose a concise FAQ title and order questions from fit and cost to control, privacy and onboarding.

**Text style:** `faq-heading` — inter 700 · 40px/48px · tracking -0.05em

## Page flow

**Storyline:** promise → tangible output → product operation → breadth and proof → decision support → invitation → timeline identity

### Broad product landing page

1. **Promise** — Split two-tone headline and support above two cinematic strips.
2. **Product demonstration** — Luminous workspace stage with compact operation summaries.
3. **Capability breadth** — Workflow rail, capability cards and centered shared-work invitation.
4. **Context and social proof** — Use-case stage, atmospheric endorsement and overlapping authored-work posters.
5. **Closing call** — Dark object, centered conversion copy and paired pills.
6. **Identity** — Timeline clip footer with fading outline word.

**Transfer:** Alternate immersive product proof with short text decisions; retain media, light and the instrument-like ending without requiring an identical section count.

### Single-feature explainer

1. **Promise** — Small editorial title, plain-language benefit and compact actions.
2. **Transformation proof** — Overlapping before-and-after illustration followed by narrow explanatory prose.
3. **Human and instructional proof** — Blue-rule quote, embedded tutorial and output example rail.
4. **Objection handling** — Split FAQ.
5. **Identity** — Timeline footer immediately after the explanatory content.

**Transfer:** Explain one operation deeply and keep the tone more practical than the main product narrative.

### Commercial evaluation

1. **Reassurance** — Centered single headline, low-friction support and free-entry action.
2. **Pricing** — Billing switch, four shared-panel plans and two exception panels.
3. **Expansion** — Credit-pack grid and annotated special offer.
4. **Decision detail** — Three-column feature comparison.
5. **Closing call and identity** — Object-led invitation followed by timeline footer.

**Transfer:** Separate quick choice from detailed comparison while keeping the same black stage and small actions.

### Enterprise sales narrative

1. **Promise** — Split heading and sales support above a luminous collaborative workspace.
2. **Quantified proof** — One monumental result over dark blurred media.
3. **Operational capabilities** — Vertical capability list beside a demo, then three proof cards and a compact feature matrix.
4. **Risk reduction** — Security summary and agreement panel.
5. **Breadth and objections** — Production image rail and longer split FAQ.
6. **Closing call and identity** — Object-led assisted-onboarding invitation and timeline footer.

**Transfer:** Replace broad inspiration with operational specifics, one verified result and explicit risk-reduction copy.

### Output-led gallery

1. **Promise** — Split gallery introduction and portrait-cover rail.
2. **Community proof** — Smaller two-tone heading leading into a long three-column masonry wall.
3. **Participation** — An editorial invitation embedded in the wall.
4. **Closing call and identity** — Media fades away before object-led invitation and timeline footer.

**Transfer:** Give completed work the majority of page area and keep navigation and captions subordinate.

## Writing

Confident, inviting and maker-oriented. The aspirational lines are short, while supporting copy uses plain verbs to explain the work and remove friction.

**Do not copy:** Do not reuse the Morphic name, proprietary product names, logo, poster artwork, testimonials, customer results, prices, credit allowances, certifications or claims as facts for another product. Source phrases below illustrate structure only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your team; use we for hands-on service commitments. Product descriptions alternate a named tool with an active verb.
- **Rhythm:** Headlines usually contain 2–6 words per line. Support is one short sentence or two clipped sentences; lists favor parallel noun phrases. Actions are 2–4 words, without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Short aspirational outcome followed by an audience or scale echo. | 2–6 words per line | “Smart storytelling”<br>“For every creative”<br>“Creative production”<br>“At enterprise scale” |
| Chapter pair | Concrete capability followed by a brief benefit or context. | 2–6 words per line | “Workflows”<br>“Built for speed”<br>“Secure by design”<br>“Private by default” |
| Supporting line | Explain the practical action or remove a barrier, rather than restating the heading. | 12–30 words | “Get started for free today, with the option to upgrade or cancel anytime.”<br>“We map the steps your team repeats and build them into workflows anyone can run.” |
| Action | Direct verb plus an immediate next step. | 2–4 words | “Start for free”<br>“Book a demo”<br>“Talk to us” |
| Question | Ask the user's actual practical concern in ordinary speech. | 5–12 words | “Does inpainting change the rest of the image?”<br>“Do we need engineers to run this?” |
| Closing invitation | Turn the promise into an attainable next step; assisted sales copy states what the team will do. | 5–9 word heading | “Bring your stories to life”<br>“Build your first workflow with us” |

**Words and phrasing to use:** create; shape; build; edit; your team; in one place; by default; get started; with us; repeatable

**Avoid:** revolutionary ecosystem; unleash limitless potential; synergize; best-in-class solutions; frictionless paradigm

**Rules:**

- Pair inspiration with a concrete operation in the next sentence.
- Use parallel verbs in capability groups and short noun phrases for utility labels.
- Explain security and administration in everyday language, not certification jargon alone.
- Keep benefit captions specific enough to correspond to the pictured artifact.
- Use low-friction entry language only when the actual product experience supports it.

## Do's and Don'ts

### Do

- Set the default two-line headline at 52px/60px, weight 700 and -2.5px tracking.
- Keep the bright/dim heading relationship at #fafafa versus 40% white.
- Align narrative content to a 1080px outer container with 20px side padding.
- Let media rails overflow the 1040px content width while headings stay aligned.
- Keep marketing actions at 40px high and the header action at 32px.
- Back substantial product previews with a soft colored halo that disappears into black.
- Use 32px corners on large capability cards but 6px corners on timeline clips.
- Keep the closing copy narrow at about 490px and separate its actions by 40px from the support text.

### Don't

- Do not turn the #0075ff accent into a page-wide blue background or tint every card blue.
- Do not replace the 52px bold grotesk with a light-weight display serif or an ultra-wide futuristic font.
- Do not render the dim headline line in the same bright white as its lead.
- Do not give every surface the 32px capability-card radius; utility clips must remain compact at 6px.
- Do not enlarge ordinary pills to 56px-high sales banners; their modest scale makes the media feel expansive.
- Do not add loud neon outlines around dark interface demonstrations; the halo belongs behind the shell.
- Do not convert the footer into conventional tall link columns and lose the ruler-and-clip construction.
- Do not put opaque white cards behind the closing object or the portrait poster fan.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color transitions of 0.1s with cubic-bezier(.4, 0, .2, 1); navigation links use 0.15s with the same curve.
- Capability cards declare background 0.1s ease-in-out.
- Gallery tiles declare transform-related transitions of 0.3s cubic-bezier(0, 0, .2, 1) and shadow transitions of 0.3s cubic-bezier(.4, 0, .2, 1).
- Rail controls, tabs, transformation examples and moving media provide the sense of an active tool rather than ornamental page animation.

**Transfer:**

- Keep state changes quick and localized to pills, tiles and active controls.
- Use motion to demonstrate a transformation or move through a media rail; retain a strong still composition.

**Unknown:**

- Exact rail autoplay cadence, media playback sequencing and scroll choreography are not established.
- Focus-visible behavior and reduced-motion alternatives are not established.

### Responsive

**Observed:**

- Declared width thresholds include 640px, 768px, 1024px and 1040px, alongside smaller and larger component-specific thresholds.
- Mobile rules hide the centered desktop navigation cluster.
- The closing heading declares a 30px mobile size with unit line height; FAQ headings declare 30px/1.1 and -0.6px tracking. The enterprise stat declares 56px.
- Pricing credit-pack grids declare one column on mobile, while FAQ layout rules stack heading and questions.

**Transfer:**

- On narrow screens, stack promise, support and actions before the media while retaining the two-tone heading.
- Preserve partial-next-item rails instead of shrinking all imagery into tiny tiles.
- Scale the dark closing object to the text width and keep its silhouette isolated.
- Keep the footer ruler and outline identity gesture legible while reorganizing clip links into a usable narrow layout.

**Unknown:**

- Exact rendered mobile compositions, navigation menu behavior and intermediate responsive sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
