# Flighty — reassurance in motion

## Overview

A bright, consumer-friendly product style that makes sophisticated information feel immediately useful. Bold system sans headlines and spacious white fields alternate with near-black demonstration theaters; saturated greens, blues and purples live mainly in the product imagery. Photoreal device compositions, floating notifications and softly raised cards give the page a tactile, native-app character. It suits polished software and services with detailed capabilities but a reassuring, approachable promise.

### Essentials

- A plainspoken promise towers over a handheld product: centered 65px/1.2 system sans at 700, -1px tracking, followed by 17px/1.5 support and a tall central device surrounded by notification cards.
- The page has a daylight exterior and a night-mode theater: white is the default canvas; a substantial #05010d capability chapter reverses text to white. Saturated color is concentrated in media, the 39px announcement ribbon and small actions rather than broad decorative page washes.
- Controls feel like compact native-app hardware: primary actions are 44px high with 40px corners, 17px semibold labels and an 18px device icon; a floating navigation capsule is 56px high.
- Capabilities are staged, not listed: 1000px-wide panels use 20px corners, 40px text insets and edge-clipped device imagery; paired panels are 484px wide with a 32px gutter.
- Human-scale information floats around the product: white 16px-radius notification cards with compact two-line content and feathered shadows form a halo around a central object. For products without a native interface, use believable outcome cards surrounding a single representative artifact.
- The finish is a warm send-off plus a physical product family: a centered 48px/1.1 closing line and one pill action lead into a wide white tabletop arrangement of devices and a related tangible object. Recreate this with the new product's artifacts, not a generic illustration.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric indigo | `#12128c` | `--color-ribbon-blue` | background, accent | Saturated end of the announcement ribbon, not a general canvas. |
| Slate violet | `#616170` | `--color-ribbon-muted` | background | Muted end of the narrow announcement gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest ink | `#002111` | `--color-green-ink` | text | Feature title paired with fresh green product imagery. |
| Purple black | `#0d0021` | `--color-purple-ink` | text | Headings in the history and secondary-benefit chapters. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, action, background | Headlines and primary actions; full-page canvas in the pricing variant. |
| Midnight violet | `#05010d` | `--color-theater` | background | Large reversed capability chapter. |
| Obsidian panel | `#050408` | `--color-dark-panel` | surface | Dark feature stage within the midnight chapter. |
| Obsidian edge | `#19181b` | `--color-dark-edge` | border | Visible white-at-8% outline over the dark feature surface. |
| Readable charcoal | `#333333` | `--color-quote-ink` | text | Testimonials and softer display text, black at 80% opacity on white. |
| Soft ink | `#595959` | `--color-body` | text | Supporting copy on white, built as black at 65% opacity. |
| Secondary gray | `#737373` | `--color-secondary` | text, link | Footer links and secondary closing copy, black at 55% opacity on white. |
| Silver on dark | `#999999` | `--color-reverse-body` | text | Dark-stage support copy; white at 60% opacity over near-black. |
| Bright silver | `#cccccc` | `--color-reverse-lead` | text | Dark chapter introduction and navigation; white at 80% opacity. |
| Porcelain | `#fafafa` | `--color-panel` | surface, background | Light feature panels and the footer; footer uses black at 2% opacity over white. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, notification cards and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Orchid | `#bf59f2` | `--color-pro` | action, accent, text | Upgrade actions, included-feature checks and recommendation text. |
| pricing pages | Orchid light | `#deaff6` | `--color-pro-soft` | text | Billing support and trial microcopy. |
| pricing pages | Orchid charcoal wash | `#251b2a` | `--color-pro-wash` | surface | Visible recommendation-pill wash: orchid at 10% opacity over pricing charcoal. |
| pricing pages | Pricing charcoal | `#141414` | `--color-pricing-panel` | surface | Plan presentation and FAQ panels. |
| pricing pages | Unavailable gray | `#404040` | `--color-unavailable` | accent | Disabled comparison marks. |
| pricing pages | Information gray | `#4d4d4d` | `--color-info` | accent | Small comparison information icons. |

## Typography

- **system-ui** — All marketing headings, paragraphs, labels and actions. Native platform sans with familiar open letterforms, bold compact headlines and medium-weight supporting copy. Font stack: "system-ui", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | system-ui | 700 | 65px | 1.2 | -1px | Centered opening promise. |
| chapter | system-ui | 700 | 56px | 1 | -0.005em | Large left-aligned capability chapter headings. |
| proof-heading | system-ui | 700 | 48px | 1.2 | normal | Centered testimonial introduction; also the pricing opening. |
| closing | system-ui | 700 | 48px | 1.1 | normal | Short centered send-off. |
| callout-heading | system-ui | 700 | 44px | 1.1 | normal | Centered demonstration calls to action. |
| secondary-heading | system-ui | 700 | 40px | 1.2 | normal | Secondary benefits and FAQ heading. |
| panel-heading | system-ui | 600 | 32px | 1.1 | normal | Feature-panel benefit, usually a compact two- or three-line statement. |
| lead | system-ui | 500 | 22px | 1.5 | normal | Chapter introductions, 20px below a headline. |
| hero-support | system-ui | 500 | 17px | 1.5 | normal | Centered opening explanation. |
| button | system-ui | 600 | 17px | 1.2 | normal | Primary action labels. |
| body | system-ui | 500 | 16px | 1.5 | normal | Feature descriptions and secondary promotional copy. |
| nav | system-ui | 500 | 15px | 2 | -0.01em | Main navigation links. |
| small-body | system-ui | 400 | 15px | 1.5 | normal | Review text, notification secondary lines and footer links. |
| compact-semibold | system-ui | 600 | 15px | 1.2 | normal | Footer group labels and compact plan actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-heading | system-ui | 600 | 40px | 1.2 | normal | Comparison-table heading. |
| pricing pages | price | system-ui | 500 | 28px | 1.2 | -0.03em | Monthly price, with a smaller adjacent cadence label. |
| pricing pages | question | system-ui | 500 | 17px | 1.3 | normal | Closed accordion question. |
| pricing pages | billing | system-ui | 500 | 14px | 1.2 | -0.02em | Annual billing line and recommendation badge. |
| pricing pages | comparison-label | system-ui | 500 | 14px | 1.3 | normal | Compact feature names in long plan comparisons. |

**Notes:**

- The hero is bold but not oversized poster typography; chapter headings are tighter vertically than the hero. Keep 56px headings at a 1 line height and only slight negative tracking.
- Use medium-weight 16–22px explanatory copy, not thin text. Reviews and footer links step down to 15px regular.
- Most small roles have normal tracking. Reserve stronger tightening for the 28px price; do not apply it across body copy.

## Layout

**Density:** Airy chapter spacing around dense, highly legible product demonstrations; local controls remain compact.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Primary button icon-to-label gap. |
| 10px | Compact flex content gaps, including notification icon and text. |
| 12px | FAQ row spacing. |
| 16px | Hero headline-to-support gap, footer link rhythm and notification padding. |
| 20px | Chapter heading-to-copy gap and review-card insets. |
| 24px | Page side safety padding and navigation inset. |
| 32px | Feature-panel grid gutter and vertical panel separation. |
| 40px | Feature-panel text inset. |
| 48px | Secondary section heading-to-content gap. |
| 64px | Chapter introduction-to-feature stage separation. |
| 72px | Footer top inset and plan-stage bottom space. |
| 140px | Return-to-white chapter opening space. |
| 180px | Space between major light capability chapters. |

### Containers and grids

- **main-container**: max width 1000px · side padding 24px. Centered feature stage and footer content; leaves substantial outer margins on desktop.
- **chapter-copy**: max width 680px. Left-aligned light chapter title and explanation, aligned to the feature stage's left edge.
- **hero-copy**: max width 737px. Centered hero support line; title is allowed a much wider single-line span.
- **feature-pair**: max width 1000px · 2 columns · gap 32px. Two 484px-wide tall feature panels under a full-width 1000px by 480px panel.
- **review-wall**: max width 1400px · 4 columns · gap 20px. Fuller-width staggered testimonial columns; cards are about 331px wide.
- **pricing-shell** (only for pricing pages): max width 1048px · side padding 24px. Outer shell containing a 1000px plan stage and comparison table.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | feature panels | 20px |
|  | notifications | 16px |
|  | review cards | 12px |
|  | primary actions | 40px |
|  | navigation capsule | 9999px (pill) |
| pricing pages | pricing controls | 50px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| review elevation | `rgba(0, 0, 0, 0.04) 0px 0px 0px 1px, rgba(0, 0, 0, 0.02) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.02) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.02) 0px 6px 6px -3px, rgba(0, 0, 0, 0.02) 0px 12px 12px -6px, rgba(0, 0, 0, 0.02) 0px 24px 24px -12px` | White review cards; many very faint layers create a tactile edge rather than a conspicuous cast shadow. |

### Surfaces

#### Daylight canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #000000`

#### Night theater · level 0

**Use:** Extended capability demonstration chapter.

**CSS:** `background: #05010d; color: #ffffff`

**Observed:** A full-width dark interval, not merely a dark card on white.

**Transfer:** Give the most technical capability its own immersive chapter.

#### Porcelain feature · level 1

**Use:** Light product panels.

**CSS:** `background: #fafafa; border-radius: 20px; overflow: hidden`

**Observed:** Nearly indistinguishable from the surrounding white until imagery and corner edges define it.

**Transfer:** Use tonal separation instead of stronger borders.

#### Dark feature · level 1

**Use:** Demonstration panels in the night theater.

**CSS:** `background: #050408; border: 1px solid rgba(255,255,255,0.08); border-radius: 20px; overflow: hidden`

**Observed:** Other dark stages vary subtly toward navy, purple or green in sympathy with the interface.

**Transfer:** Tint the near-black backing toward the media without turning the panel into a bright gradient.

#### Pricing charcoal · level 1

**Only for:** pricing pages

**Use:** Upgrade-plan container and questions.

**CSS:** `background: #141414; border-radius: 20px; color: #ffffff`

**Transfer:** Keep commercial information flat and compact against black.

## Components

### Floating navigation

**Use:** Persistent orientation above the content.

**CSS:** `background: rgba(255,255,255,0.447); border-radius: 9999px; height: 56px; padding: 0px 24px; max-width: 1000px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `nav` — system-ui 500 · 15px/2 · tracking -0.01em

**Observed:** Brand mark at left, five short links in the middle, compact download action at right. The centered capsule is about 868px wide in its scrolled form, below the announcement ribbon. It reads white and softly raised over light content; the dark variant uses a near-black translucent backing, light links and a white action.

**Transfer:** Retain the isolated floating capsule instead of a full-width solid navigation slab.

### Announcement ribbon

**Use:** A small persistent product-news strip.

**CSS:** `background: linear-gradient(171deg, #616170 -45%, #12128c 69%); color: #ffffff; height: 39px; display: flex; align-items: center; justify-content: center; gap: 10px`

**Observed:** Small themed icon, news label, short action and arrow centered in one line; close icon at the far right. Type is 14px medium with 16.8px line height.

**Transfer:** Give one concise announcement the entire strip; keep the colored footprint narrow.

### Primary button

**Use:** Main product conversion action.

**CSS:** `background: #000000; color: #ffffff; border-radius: 40px; padding: 12px 18px 12px 20px; height: 44px; display: inline-flex; align-items: center; gap: 8px; box-sizing: border-box`

**Text style:** `button` — system-ui 600 · 17px/1.2

**Observed:** Small device icon precedes the invitation. In the dark demonstration chapter the action reverses to white with black text; pricing uses orchid with white text.

### Feature panel

**Use:** A benefit and its product demonstration in one object.

**CSS:** `background: #fafafa; border-radius: 20px; padding: 40px; overflow: hidden; position: relative`

**Text style:** `panel-heading` — system-ui 600 · 32px/1.1

**Observed:** The wide form is 1000px by 480px. A narrow text column places the title high and explanation low, while device imagery takes the right half and is clipped by the panel. Tall paired variants are 484px wide and roughly 680–703px high.

**Transfer:** Show a distinct outcome in each panel, with real interface detail doing most of the explanation.

### Notification card

**Use:** Tangible outcome proof surrounding the main product object.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 16px; display: flex; align-items: center; gap: 10px; box-shadow: rgba(0, 0, 0, 0.02) 0px 0px 0px 1px, rgba(0, 0, 0, 0.02) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.02) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.02) 0px 6px 6px -3px, rgba(0, 0, 0, 0.02) 0px 12px 12px -6px, rgba(0, 0, 0, 0.02) 0px 24px 24px -12px`

**Text style:** `small-body` — system-ui 400 · 15px/1.5

**Observed:** A compact avatar or service mark precedes two lines: a 16px semibold event and 15px regular secondary detail. Cards are about 79px high; some recede almost to white while a few remain sharply readable.

**Transfer:** Use credible status changes and useful context, not random decorative text.

### Review card

**Use:** A dense wall of human proof.

**CSS:** `background: #ffffff; border-radius: 12px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.04) 0px 0px 0px 1px, rgba(0, 0, 0, 0.02) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.02) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.02) 0px 6px 6px -3px, rgba(0, 0, 0, 0.02) 0px 12px 12px -6px, rgba(0, 0, 0, 0.02) 0px 24px 24px -12px`

**Text style:** `small-body` — system-ui 400 · 15px/1.5

**Observed:** Identity header above a 20px-inset quote. Cards have variable heights and preserve the feel of social posts or messages rather than uniform star-rating tiles.

**Transfer:** Mix brief and long genuine customer stories while keeping the same card width.

### Footer link group

**Use:** Utility navigation after the emotional close.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 16px; color: rgba(0,0,0,0.55)`

**Text style:** `small-body` — system-ui 400 · 15px/1.5

**Observed:** Four visible groups sit beside a standalone app icon: product, comparison, company and support, with social icons beneath support. Group headings use compact-semibold. A lower line includes three miniature rounded map tiles with location pins and short place names; cookie settings sits below. The dark variant keeps the same composition with muted white links.

### Upgrade button

**Only for:** pricing pages

**Use:** Plan-card trial conversion.

**CSS:** `background: #bf59f2; color: #ffffff; border-radius: 50px; padding: 10px 10px 10px 16px; height: 40px; display: inline-flex; align-items: center; gap: 10px; box-sizing: border-box`

**Text style:** `compact-semibold` — system-ui 600 · 15px/1.2

**Observed:** Label at left and a small arrow in a pale circular end cap at right; a brief trial reassurance sits underneath.

### Recommendation badge

**Only for:** pricing pages

**Use:** Highlight the preferred billing option.

**CSS:** `background: rgba(191,89,242,0.1); color: #bf59f2; border-radius: 50px; padding: 8px 16px`

**Text style:** `billing` — system-ui 500 · 14px/1.2 · tracking -0.02em

**Observed:** Small pill at the upper right of the plan stage, beside a dark segmented billing control.

### Comparison row

**Only for:** pricing pages

**Use:** Feature-by-feature plan evaluation.

**CSS:** `display: flex; padding: 16px 0px; gap: 10px; min-height: 53px; box-sizing: border-box`

**Text style:** `comparison-label` — system-ui 500 · 14px/1.3

**Observed:** Feature name takes about half the table; two equal plan columns occupy the other half. Repeated faint horizontal separators, white free-plan checks, orchid paid-plan checks, gray unavailable marks and occasional information dots keep a long list scannable.

### FAQ row

**Only for:** pricing pages

**Use:** Final objections before the footer.

**CSS:** `background: #141414; color: #ffffff; border-radius: 20px; padding: 26px 48px; min-height: 75px; box-sizing: border-box`

**Text style:** `question` — system-ui 500 · 17px/1.3

**Observed:** Full-width closed questions with a simple downward chevron at right. Four rows are separated by 12px beneath a centered heading.

## Imagery and graphics

### Handheld product halo

**Use:** The signature opening demonstration.

**Observed:** A photoreal black-edged phone held upright in a human hand rises from the white canvas. Its vivid green-and-blue interface is the visual anchor; white notification cards flank it at staggered heights and different opacities. Media occupies the lower half of the first screen and continues below it.

**Transfer:** Use one recognizable product artifact or device held or otherwise given human scale. If there is no app, create a crisp representative document or tool view, with useful outcome notifications around it.

**Build:** Layer a tall central device cutout over two staggered columns of white notification cards across a roughly 1000px stage. Use 16px corners, faint layered black shadows and white edge masks. Keep a few cards at full contrast and others at 15–50% opacity; put the central artifact in front.

### Edge-clipped device mosaics

**Use:** Capability panels and multi-feature demonstrations.

**Observed:** Realistic phones, sometimes tilted, repeat in offset rows or pairs. Hardware rims, glass highlights and soft cast shadows remain visible. Devices are deliberately too large to fit the panel; text stays in the opposite half. Dark panels use moody screens and subtle colored depth; light panels use bright maps or purple data views.

**Transfer:** Place the new interface in believable hardware or a precise application-window frame. Keep enough interface detail to communicate a task, but let the outer composition remain simple.

### Atmospheric data globe

**Use:** A feature demonstrating broad coverage or live state.

**Observed:** A glowing blue-and-green globe with tiny colored data points sits behind a large phone on a deep teal-to-black field with sparse star-like flecks. It fills the right side of a wide feature panel, leaving white text at left.

**Transfer:** Translate coverage into a single luminous data object relevant to the new product. A flat vector sphere or domain diagram with the same restrained depth is an acceptable minimum.

**Build:** Use a large SVG circle behind the device with blue radial shading, translucent green land-like or domain-specific shapes, a thin pale-blue rim and a blurred blue halo. Scatter small status dots only over the meaningful area. Put tiny low-opacity white points on a near-black background; fade all edges into the panel.

### Tabletop product family

**Use:** Signature wide closing artwork after the final action.

**Observed:** Top-down photoreal arrangement on white: a silver laptop in the center, smaller phone and wearable at left, tablet and a purple booklet at right. Objects have natural soft shadows and vivid interfaces. The broad image extends beyond the usual content width and leaves white breathing room before the footer.

**Transfer:** Create a product-family still life using the new product's devices, outputs or related physical artifacts. At minimum, arrange two or three sharply rendered interface frames with one tangible companion object and consistent top-down lighting.

### Tiny location tiles

**Use:** A human sign-off within the footer.

**Observed:** Three rounded-square map illustrations with blue location pins interrupt the lower footer sentence. They look like miniature app icons, softly raised, not flat emoji.

**Transfer:** Use small place or origin artifacts to give the company a specific human geography.

**Build:** Create 48px rounded squares with simplified pale-green land shapes, fine white road lines and blue location dots with translucent outer rings. Add a faint layered shadow; use a dark-map palette in the dark footer.

### Gift-card fan

**Only for:** pricing pages

**Use:** Secondary commerce invitation after comparison.

**Observed:** A diagonal perspective field of rounded black, blue and purple cards is softly vignetted into the black page. Bold duration lettering and one illustrated card provide recognizable content. Text and a white pill action occupy the left half.

**Transfer:** Use a perspective arrangement of purchasable packages or outputs rather than another upright device.

**Build:** Create a small grid of rounded rectangles in dark navy, purple and blue. Add short bold white package labels and minimal line artwork, then apply one shared perspective transform and a black radial mask around the perimeter. Keep the brightest card near the center-right.

### Icons

**Observed:** Predominantly compact solid system-like glyphs, monochrome black or white. Action icons are about 18px, navigation details 14–16px. Utility outline icons use 1.5px round strokes at 18px; comparison marks are 13px circular checks, crosses and information dots.

**Transfer:** Use a consistent native-system icon family with filled symbols for actions and simple round-stroked chevrons for disclosure; avoid colorful outline icon packs outside product illustrations.

## Section recipes

How recurring sections are built.

### First screen: Handheld promise opening

**Observed:** White canvas behind a narrow indigo Announcement ribbon and centered Floating navigation. A bold black single-line promise sits below the navigation at 65px, centered across most of the width; its support paragraph is limited to 737px and separated by 16px. Two small award treatments sit below the paragraph. The hero text and proof occupy approximately the upper 440px; a tall Handheld product halo starts immediately beneath. Within the first 900px, the headline, support, award proof, upper device and flanking notifications are visible, with a dark segmented demonstration control crossing the device near the lower edge. The device, hand and continued demonstration extend below the fold. The download action is in the navigation rather than a large button between the promise and object.

**Transfer:** Keep the same hierarchy of promise, brief reassurance, compact credibility and one oversized tangible product. Use a representative artifact with outcome cards if no mobile screen exists. Pricing pages instead open on black with a left-aligned 48px promise, small publication proof at right and the plan stage immediately below.

**Avoid:** Do not replace the central upright object with a tiny dashboard thumbnail, a split hero, a generic abstract blob or a row of competing conversion buttons.

**Text style:** `display` — system-ui 700 · 65px/1.2 · tracking -1px

### Chapter heading pair

**Observed:** A 56px Chapter heading and 22px Lead are left aligned with 20px between them. Light chapters use a 680px text measure within the 1000px stage; the dark introduction spans the wider stage. A 64px interval leads into Feature panel content.

**Transfer:** Introduce each major outcome with one complete thought and a useful paragraph, then show the result rather than repeating the claim in multiple bullets.

**Text style:** `chapter` — system-ui 700 · 56px/1 · tracking -0.005em

### Night capability theater

**Observed:** Night theater carries an extended technical demonstration: a full-width Dark feature stage followed by two-column tall panels with 32px gaps. Text is white or muted silver. Large devices and enlarged interface details fill the panels. A centered 44px callout and reversed Primary button finish the chapter.

**Transfer:** Group the deepest capabilities in one immersive mode, then return decisively to daylight rather than alternating theme on every card.

**Text style:** `callout-heading` — system-ui 700 · 44px/1.1

### Light product chapter

**Observed:** A left-aligned Chapter heading pair precedes a wide Porcelain feature, then paired tall Feature panels. Text occupies upper-left and lower-left zones; oversized device mosaics fill and run beyond the right edge. Major chapters have 180px separation.

**Transfer:** Use the wide panel for the core outcome and the paired panels for supporting capabilities; choose fresh screen compositions rather than repeating the same phone angle.

### Proof wall with dissolving edge

**Observed:** Centered 48px Proof-heading above a 1400px-wide four-column Review card wall, with 20px gutters and irregular card heights. The lower edge dissolves into white through a mask and progressive blur layers up to 12px; a black proof-and-more pill sits over the fade.

**Transfer:** Use authentic mixed-length testimonials and fade the wall deliberately so the next section is a clean reset. Keep the proof pill compact and separate from the main conversion action.

**Text style:** `proof-heading` — system-ui 700 · 48px/1.2

### Warm send-off and still life

**Observed:** Centered 48px Closing line, short 17px supporting text, then one black Primary button with 20px rhythm. Tabletop product family follows across a 1500px-wide artwork. Footer link group content sits on a very pale neutral band with 72px top and 24px bottom padding, app icon at left, four groups at right and a tiny location-tile sign-off below.

**Transfer:** End with a friendly outcome-oriented wish, then let a physical-feeling product family provide the final visual statement before practical navigation.

**Text style:** `closing` — system-ui 700 · 48px/1.1

### Plan stage and comparison

**Only for:** pricing pages

**Observed:** Black canvas with 48px opening promise at left. A 1000px by 297px charcoal plan stage has a roughly 243px illustrated purple price rail and a larger right area with billing segments, recommendation pill and five compact benefit lines. The 40px comparison heading follows after 72px, then a long three-column table of 53px Comparison rows grouped under bolder category labels.

**Transfer:** Expose one principal upgrade proposition, let billing choices stay inside its stage, and move exhaustive detail into a calm table.

**Text style:** `pricing-heading` — system-ui 600 · 40px/1.2

### Commerce and objection close

**Only for:** pricing pages

**Observed:** A centered orchid conversion action follows the table. A left-aligned commerce invitation and white pill sit beside the Gift-card fan. A centered secondary heading introduces four FAQ rows. The Footer link group then repeats directly on black, without the daylight tabletop scene.

**Transfer:** Use an adjacent offer only if it is genuinely relevant, then answer purchase objections and close with the dark utility footer.

**Text style:** `secondary-heading` — system-ui 700 · 40px/1.2

## Page flow

**Storyline:** Reassuring promise → tangible product proof → capability chapters → human or detailed decision proof → invitation → distinctive visual or utility close.

### Long-form product introduction that makes complex capabilities feel familiar

1. **Promise** — Centered plainspoken headline with concise explanation, small award proof and a handheld product halo.
2. **Product demonstration** — A persistent segmented control anchors a longer product stage.
3. **Capability chapters** — An extended dark technical theater followed by spacious white chapters with large interface panels.
4. **Social proof** — Wide staggered review wall with a dissolving lower edge and compact more-proof pill.
5. **Closing invitation** — Friendly centered send-off, one action and a panoramic tabletop product family.
6. **Utility close** — Pale footer with app mark, four link groups, social marks and tiny place tiles.

**Transfer:** Adapt the chapter count and order to the product, preserving the alternation between reassuring language and concrete interface proof.

### Upgrade evaluation and purchase reassurance

1. **Promise** — Left-aligned two-line headline on black, compact publication proof and a single illustrated plan stage.
2. **Pricing** — Price rail, billing segments, recommended-plan badge and brief included-benefit list.
3. **Detailed evaluation** — Long grouped comparison table with restrained orchid inclusion marks.
4. **Conversion** — Centered orchid pill after the exhaustive comparison.
5. **Adjacent offer** — A short commerce invitation paired with a vignetted perspective card arrangement.
6. **Objection handling** — Four dark rounded FAQ rows.
7. **Utility close** — Same footer structure in a dark palette, including the miniature location-tile sign-off.

**Transfer:** Use a focused dark commercial variant rather than reproducing the long editorial demonstration journey.

## Writing

Confident, caring and usefully specific. Technical capability is translated into relief, control or enjoyment, with occasional conversational humor rather than a formal enterprise voice.

**Do not copy:** Do not reuse Flighty names, logos, product screens, aviation artwork, award credentials, publication endorsements, customer quotations, prices, usage totals or performance claims. Replace them with the new product's own substantiated material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your. Use we for reassurance and the product name when explaining how something works.
- **Rhythm:** Short, memorable headline clauses are followed by explanatory paragraphs. Fragments and emphatic short sentences punctuate longer practical explanations; a friendly exclamation belongs in a send-off rather than every feature.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A direct reader benefit rather than a category definition. | 5–10 words | “Get the truth when you travel” |
| Feature benefit | Name the frustrating situation, then offer a compact release from it. | 5–14 words | “See why you’re delayed. Finally!”<br>“Never hear, “can you send me your flight info?” ever again.” |
| Support | Begin with the problem or capability, explain the mechanism and land on a practical reader outcome. | 2–4 sentences | “Airlines often keep delay information under wraps until the last minute. [Brand] doesn’t.” |
| Action | Low-pressure invitation, or a short verb for an immediate task. | 1–5 words | “Give [Brand] a try”<br>“Try it for free” |
| Closing | A familiar good wish followed by a division of responsibility that reassures the reader. | 3–12 words per sentence | “Have a nice flight!”<br>“We’ll handle the details. You just enjoy your trip.” |

**Words and phrasing to use:** you’ll; finally; in seconds; at a glance; enjoy; details; get up & running; ever again

**Avoid:** revolutionary; synergy; leverage; best-in-class solutions; unlock limitless possibilities

**Rules:**

- Explain why information matters before describing the data behind it.
- Pair an ambitious benefit with a concrete mechanism or demonstrable interface state.
- Use parentheses for an occasional friendly aside, not as the primary explanatory structure.
- Keep comparison labels literal and compact; reserve personality for headlines, explanation and the send-off.

## Do's and Don'ts

### Do

- Keep the opening at 65px/1.2, weight 700, with -1px tracking and a centered product beneath it.
- Give capability panels 20px corners and 40px text insets.
- Preserve the 1000px main stage and 32px paired-panel gutter on desktop.
- Let vivid interfaces carry most color against white and near-black surfaces.
- Use compact 44px-high primary pills with an 18px icon and 8px icon gap.
- Maintain faint layered shadows on notification and review cards, with 16px and 12px corners respectively.
- Carry the footer's tiny illustrated origin tiles into the final sign-off.
- Use the dark orchid-accented commercial treatment only for pricing and purchase evaluation.

### Don't

- Do not introduce a decorative serif or monospace headline; the native system sans is the marketing voice.
- Do not turn the 39px announcement gradient into a full-page rainbow background.
- Do not replace the 32px feature gutter with tightly packed 8px dashboard spacing.
- Do not put heavy black drop shadows under white cards; the layers use only 2–4% black.
- Do not apply the pricing orchid to every marketing action; the ordinary action is black or reversed white.
- Do not force all review cards to equal heights; their uneven lengths are part of the human proof treatment.
- Do not inflate navigation labels beyond the 15px compact recipe or make navigation a full-width solid bar.
- Do not make the footer an oversized typography statement; it is a restrained utility close after the visual send-off.

## Motion and responsive

### Motion

**Observed:**

- The navigation remains fixed while content changes behind it; the demonstration selector is sticky within its product stage.
- The review wall uses a fading mask and progressive backdrop blur at its lower edge.

**Transfer:**

- Preserve the persistent navigation capsule and anchored demonstration selector as orientation devices; keep the product object readable at settled positions.

**Unknown:**

- No action transition timings or animation sequences are established. Scrolling interpolation and easing assignments are unspecified.

### Responsive

**Observed:**

- Styles define width breakpoints near 790px, 810px and 1200px.

**Transfer:**

- On narrow screens, retain one central product artifact and reduce the surrounding notification halo rather than shrinking all its text.
- Recommended adaptation: stack paired feature panels, keep their image clipping and 20px corners, and preserve a strong title-versus-object hierarchy.
- Recommended adaptation: simplify the floating navigation while keeping a direct conversion route; let the comparison remain aligned rather than wrapping individual cells independently.

**Unknown:**

- Exact mobile navigation, type sizes, device arrangements and table behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
