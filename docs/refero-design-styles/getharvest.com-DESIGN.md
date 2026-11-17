# Harvest — business in warm ink

## Overview

An approachable editorial style for practical software, balancing bookish serif promises with straightforward sans-serif explanations. Cream, oatmeal and white keep long pages light, while coral-framed interface scenes and delicate outlined illustrations add warmth. The density is spacious at the section level and purposeful inside product demonstrations, comparison tables and proof cards.

### Essentials

- Bookish promises, workmanlike explanations: Besley headlines use 70px/1.1 at weight 400 with -0.04em tracking; major section headings use 50px/1.1, while explanatory text is Muoto VAR 16px/1.5.
- A compact editorial column faces a larger working product: the opening pairs a 477px centered text column with a 720×457px interface scene across a 60px gap, inside a 1297px wrapper.
- Actions feel like rounded ink stamps: black primary controls, 30px radii, white medium-weight labels, and thin gray outlines for secondary actions; the opening nests its action inside a 75px-high oatmeal email capsule.
- Color is concentrated in the demonstrations, not spread across the canvas: cream #fbf5f0 and white dominate full-width bands; orange #fa5d00 marks small interactions and coral frames carry the largest colored areas.
- Useful interfaces acquire a human touch: fine black-line tool illustrations with cream fills and small peach details accompany real interface imagery. Include this drawn accent language even when the product has no visual UI, using a simple line-drawn object beside a representative result.
- The final invitation becomes a physical inset: a 1297px coral patterned backboard with 40px top corners contains a 1156px white card with 30px top corners, an oversized 67px serif question and a cropped product/device stack. Recreate this framed invitation with a sample output if no device imagery exists.
- Proof is editorial rather than promotional: modest 30px sans-serif metrics sit above tall 20px-radius oatmeal testimonial cards; circular logo medallions, metadata, a hairline and 18px serif quotations create the hierarchy.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#fa5d00` | `--color-orange` | accent, link, action | Brand accent, navigation hover, small badges and billing switch; not a page-wide fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral backboard | `#f28e69` | `--color-coral` | surface, accent | Warm salmon framing around large interface demonstrations and the closing invitation; match this flat coral tone with lighter translucent patterning. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action black | `#000000` | `--color-black` | text, action | Black headings, button fills, icons and emphasized body text. |
| Editorial ink | `#1d1e1c` | `--color-ink` | text, action | Primary editorial text and the opening form action. |
| Plum charcoal | `#2c222d` | `--color-body` | text | Default body text and larger invitation support. |
| Hover charcoal | `#4f4f4f` | `--color-hover` | action | Hover and focus-visible fill for primary buttons. |
| Navigation gray | `#6a696a` | `--color-nav-gray` | text | Navigation links and compact promotional descriptions. |
| Soft ink | `#767471` | `--color-soft-ink` | text | Visible result of ink at 60% opacity over warm paper; opening support and subdued labels. |
| Description gray | `#8b8b8b` | `--color-muted` | text | Feature descriptions, footer column labels and secondary annotations. |
| Outline gray | `#999999` | `--color-outline` | border | Secondary action outlines. |
| Warm hairline | `#e5e0db` | `--color-rule` | border | Visible result of ink at 10% opacity over warm paper; use the underlying alpha for separators on other surfaces. |
| Oatmeal | `#f3ebe4` | `--color-oatmeal` | surface, border | Proof cards, email capsule, selected tabs and footer promotion. |
| Warm paper | `#fbf5f0` | `--color-canvas` | background, surface | Default canvas and alternating warm sections. |
| Media cream | `#fff8f1` | `--color-media-cream` | surface | Warm underlying surface for the opening video. |
| Clean white | `#ffffff` | `--color-white` | background, surface, text | Navigation, content bands, inset invitation card and text on dark actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| consultation panels | Peach accent | `#fea986` | `--color-peach` | surface, accent | Circular consultation illustration backing. |

## Typography

- **Muoto VAR** — Body text, navigation, controls, capability titles and default statistics. Open, contemporary grotesk with compact negative tracking and a practical, friendly tone. If unavailable, use **Inter**. Use weights 400–500 and retain the role-specific tracking. Font stack: "Muoto VAR", "Inter", MuotoWeb, "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Besley** — Display promises, section leads, quotations and scoped compact feature titles. Sturdy editorial serif with visible bracketed serifs and tightly fitted display setting. Font stack: "Besley", Georgia, "Times New Roman", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Besley | 400 | 70px | 1.1 | -0.04em | Opening promise; also the centered pricing headline. |
| closing-heading | Besley | 400 | 67px | 1.1 | -0.04em | Large two-line question in the framed invitation. |
| heading | Besley | 400 | 50px | 1.1 | -0.04em | Major section headings; centered by default, left-aligned for workflow chapters. |
| workflow-title | Muoto VAR | 400 | 30px | 1.2 | -0.03em | Short verb-led workflow titles. |
| stat | Muoto VAR | 400 | 30px | 1.3 | -0.04em | Default proof metrics, kept smaller than editorial headings. |
| card-heading | Muoto VAR | 500 | 26px | 1.3 | -0.03em | Capability card titles; also plan names. |
| closing-lead | Muoto VAR | 400 | 23px | 1.42 | -0.03em | Two-line supporting copy within the large invitation. |
| lead | Muoto VAR | 400 | 19px | 1.4 | -0.03em | Hero support, section introductions and FAQ questions. |
| quote | Besley | 400 | 18px | 1.5 | -0.03em | Customer quotations in proof cards. |
| button | Muoto VAR | 500 | 17px | 1 | -0.01em | Main invitation action and short promotional action labels. |
| body | Muoto VAR | 400 | 16px | 1.5 | -0.02em | Descriptions, footer links and supporting details. |
| nav-action | Muoto VAR | 500 | 16px | 1.2 | -0.02em | Compact sales and trial actions in the navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-stat | Besley | 400 | 40px | 1 | -0.008em | Compact three-column proof values beneath the comparison. |
| consultation panels | consultation-title | Besley | 400 | 30px | 1.2 | -0.03em | Consultation panel title. |
| pricing pages | price | Muoto VAR | 500 | 30px | 1.2 | -0.03em | Price or custom-price phrase. |
| feature detail pages | related-title | Besley | 400 | 26px | 1.3 | -0.03em | Integration names and related-capability links. |
| feature detail pages | compact-serif | Besley | 500 | 22px | 1.2 | -0.03em | Text-only feature-card titles. |

**Notes:**

- Keep display and section leads at regular serif weight; their tight -0.04em tracking is a stronger identity cue than boldness.
- Sans-serif descriptions remain 16px/1.5 even beside much larger demonstrations. Use 19px introductions rather than enlarging every paragraph.
- The large closing question nearly matches the opening in size. Small serif titles belong to feature-detail and consultation variants, not every card.
- No viewport-relative type formula is established; retain these desktop recipes and tune smaller-screen wrapping without claiming a fixed fluid scale.

## Layout

**Density:** Airy between chapters, economical inside controls and descriptions; alternating surface colors carry the rhythm instead of extra decoration.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Title-to-description and compact supporting-copy gaps. |
| 12px | FAQ row separation and navigation action gap. |
| 16px | Small heading-to-body gaps and pricing-card gutters. |
| 20px | General side inset and integration-card padding. |
| 24px | Media-to-title gap, bento columns and proof-card gutters. |
| 32px | Opening text stack and workflow-card gutters. |
| 40px | Bento row gap and internal testimonial grouping. |
| 56px | Major heading-to-content relationships and footer stack spacing. |
| 60px | Opening columns, metric spacing and heading-to-media separation. |
| 80px | Common content-band padding and opening-to-proof separation. |
| 100px | Typical major section top and bottom padding. |

### Containers and grids

- **wide-wrapper**: max width 1297px · side padding 20px. Centered marketing wrapper; inner content is about 1257px across at desktop. Navigation and large closing backboard align to the outer edges.
- **standard-wrapper**: max width 1200px · side padding 20px. Footer, feature-detail grids and consultation panels.
- **heading-measure**: max width 670px. Centered section heading and introduction measure on feature-detail pages.
- **opening-columns**: 2 columns · gap 60px. 477px text column faces 720px media; both vertically centered rather than aligned to the same top edge.
- **capability-grid**: 12 columns · gap 24px. Three equal four-column capability cards followed by two equal six-column cards; row gap is 40px.
- **workflow-track**: gap 32px. Horizontal row of 350px cards with deliberate overflow revealing the next workflow.
- **faq-stack** (only for FAQ sections): max width 880px · gap 12px. Centered question stack; feature-detail variant narrows to 750px.
- **plan-grid** (only for pricing pages): max width 1440px · 4 columns · gap 16px · side padding 20px. Full-width equal plan cards, each about 338px across at desktop.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 30px |
| cards | 20px |
| navigation | 40px |
| opening-media | 16px |
| footer-promotion | 24px |
| logo-medallion | 50% |
| email-capsule | 999px |
| tab-rail | 15px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| navigation | `rgba(0, 0, 0, 0.08) 0px 4px 16px 0px, rgba(0, 0, 0, 0.06) 0px 1px 3px 0px` | Soft lift for the persistent navigation only. |
| opening-media | `rgba(123, 85, 31, 0.21) 0px 4px 9.9px 0px` | Warm low shadow beneath the opening interface scene. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default background and broad warm chapters.

**CSS:** `background-color: #fbf5f0`

#### White band · level 0

**Use:** Full-width workflow and capability chapters, plus the footer.

**CSS:** `background-color: #ffffff`

**Observed:** White chapters alternate with cream without card-like borders or shadows.

**Transfer:** Use broad surface changes to separate narrative chapters.

#### Oatmeal card · level 1

**Use:** Testimonial and compact promotional grouping.

**CSS:** `background-color: #f3ebe4; border-radius: 20px`

**Observed:** Flat, warm and opaque; the distinction from the canvas is deliberately subtle.

**Transfer:** Keep proof material tactile through tone rather than elevation.

#### Warm media tile · level 1

**Use:** Small capability visuals.

**CSS:** `background-color: #fbf5f0; border-radius: 20px; overflow: hidden`

**Observed:** The illustration or interface fragment sits inside the tile; title and description sit below it.

**Transfer:** Stage one useful result per tile rather than filling it with a miniature dashboard.

#### Coral backboard · level 1

**Use:** Signature framing behind large product scenes and the final invitation.

**CSS:** `background-color: #f28e69; border-radius: 40px 40px 0px 0px; overflow: hidden`

**Observed:** Lighter translucent vertical bars and angular fragments add an understated pattern; the coral is mostly visible around a white inset.

**Transfer:** Use the patterned backing as a frame, leaving readable copy on white.

#### Invitation inset · level 2

**Use:** White inner panel of the large framed invitation.

**CSS:** `background-color: #ffffff; border-radius: 30px 30px 0px 0px; padding: 58px 56px 46px; overflow: hidden`

**Observed:** The bottom edge is visually cut by the next white band; product imagery extends beyond the inner panel.

**Transfer:** Let the framing imply a larger physical board rather than a freestanding floating card.

#### Plan panel · level 1

**Only for:** pricing pages

**Use:** Plan summaries.

**CSS:** `background-color: #ffffff; border: 1px solid rgba(29, 30, 28, 0.1); border-radius: 20px; padding: 20px`

## Components

### Floating navigation

**Use:** Persistent navigation and two conversion paths.

**CSS:** `display: flex; justify-content: space-between; align-items: center; background-color: #ffffff; border-radius: 40px; padding: 12px 16px 12px 24px; max-width: 1297px; gap: 24px; box-shadow: rgba(0, 0, 0, 0.08) 0px 4px 16px 0px, rgba(0, 0, 0, 0.06) 0px 1px 3px 0px`

**Text style:** `body` — Muoto VAR 400 · 16px/1.5 · tracking -0.02em

**Observed:** A fixed wrapper places the bar 20px below the viewport top. Menu labels use 18px regular sans-serif type with -0.03em tracking. Brand mark and menus group on the left, login and outlined/filled actions on the right. Dropdown labels have 12px chevrons; menus use 32px gaps.

**States:** Declared: hover menu text becomes #fa5d00; focus-visible menu text becomes #fa5d00.

### Primary button

**Use:** Primary conversion, especially the large final invitation.

**CSS:** `display: inline-flex; justify-content: center; align-items: center; background-color: #000000; color: #ffffff; border-radius: 30px; padding: 8px 20px; height: 53px`

**Text style:** `button` — Muoto VAR 500 · 17px/1 · tracking -0.01em

**Observed:** Single-line medium-weight label. Navigation uses a compact 49px-high version with the nav-action recipe; the opening email form uses an ink-colored 56px-high submit action.

**States:** Declared: hover background #4f4f4f and white text; focus-visible background #4f4f4f and white text.

### Secondary button

**Use:** Sales or secondary conversion alongside a filled action.

**CSS:** `display: flex; align-items: center; justify-content: center; border: 1px solid #999999; border-radius: 30px; padding: 14px 20px; color: #000000; height: 49px`

**Text style:** `nav-action` — Muoto VAR 500 · 16px/1.2 · tracking -0.02em

**Observed:** Transparent fill keeps it visually subordinate. Plan-grid sales actions stretch across the card and use 17px labels.

**States:** Declared: hover border-color #000000; focus-visible border-color #000000.

### Email signup capsule

**Use:** Default opening conversion form.

**CSS:** `display: flex; align-items: center; gap: 8px; background-color: #f3ebe4; border: 1.5px solid rgba(29, 30, 28, 0.1); border-radius: 999px; padding: 8px 8px 8px 24px; max-width: 516px`

**Text style:** `body` — Muoto VAR 400 · 16px/1.5 · tracking -0.02em

**Observed:** An unboxed email field occupies the left side, with an ink submit pill embedded at right. At desktop the form is 477×75px; a row of three peach checkmarks and short reassurance labels follows beneath.

**Transfer:** Use one field and one low-commitment action, with concise factual reassurance outside the form.

### Workflow item

**Use:** Horizontal capability overview.

**CSS:** `display: flex; flex-direction: column; gap: 8px; max-width: 350px`

**Text style:** `workflow-title` — Muoto VAR 400 · 30px/1.2 · tracking -0.03em

**Observed:** A delicate tool illustration sits above a short verb title, then a dark one-line benefit and muted body description. Items have no card background. Circular 40px previous/next controls sit beside the section heading.

**Transfer:** Give each item a distinct activity and one practical result.

### Capability tabs

**Use:** Navigable product demonstration chapter.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: center; gap: 5px; background-color: #ffffff; border-radius: 15px; padding: 10px`

**Observed:** A compact rail pairs 20px outlined icons with 13px labels. Each tab is 40px high; the active tab has oatmeal fill and 10px corners. Below, a 320px text column faces a much larger coral-backed interface scene.

**States:** Declared: hover inactive text becomes #1d1e1c; focus-visible tabs have a 2px #1d1e1c outline with 2px offset.

### Capability media card

**Use:** Bento capability summaries.

**CSS:** `display: flex; flex-direction: column; gap: 24px`

**Text style:** `card-heading` — Muoto VAR 500 · 26px/1.3 · tracking -0.03em

**Observed:** A Warm media tile precedes the title; muted body copy follows the title at an 8px gap. Three tiles use roughly 403×227px media, while the next row uses two 617×224px visuals.

**Transfer:** Use a focused UI fragment with a visible action, chart or result.

### Testimonial dossier

**Use:** Detailed social proof in a horizontal carousel.

**CSS:** `display: flex; flex-direction: column; gap: 40px; background-color: #f3ebe4; border-radius: 20px; padding: 30px 20px 30px 30px; width: 366px`

**Text style:** `quote` — Besley 400 · 18px/1.5 · tracking -0.03em

**Observed:** A 106px white logo circle leads, followed by company name and uppercase metadata labels with darker values. A thin divider introduces a peach quotation mark, serif quotation and sans-serif attribution. The next card remains partly visible; arrows sit below the track.

**Transfer:** Use real contextual metadata rather than only a logo and an anonymous quote.

### Footer promotion

**Use:** A compact secondary offer beside footer navigation.

**CSS:** `display: flex; align-items: center; background-color: #f3ebe4; border-radius: 24px; padding: 30px 0px 30px 24px; overflow: hidden`

**Text style:** `body` — Muoto VAR 400 · 16px/1.5 · tracking -0.02em

**Observed:** A 444×242px warm card places a small orange label, dark product name, short gray description and white pill on the left. A 220×176px interface image is clipped against the right edge.

**States:** Declared: hover background-color rgba(243, 235, 228, 0.85).

**Transfer:** Use a related product, resource or helpful next step rather than a second main conversion pitch.

### Platform download pill

**Use:** Secondary platform access underneath the final invitation action.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 10px; background-color: #000000; color: #ffffff; border-radius: 30px; padding: 8px 20px`

**Observed:** 37px-high compact black pills combine white platform symbols with 17px medium labels. Desktop and mobile groups have small labels above them and 48px separation.

**States:** Declared: hover background #4f4f4f and white text; focus-visible background #4f4f4f and white text.

**Transfer:** If the product has no platform apps, retain the grouped compact-pills device for equivalent delivery formats or access channels.

### FAQ row

**Only for:** FAQ sections

**Use:** Objection handling on pricing and feature-detail pages.

**CSS:** `background-color: #ffffff; border-radius: 20px; margin-bottom: 12px`

**Text style:** `lead` — Muoto VAR 400 · 19px/1.4 · tracking -0.03em

**Observed:** Each closed row is 90px high, with a full-width button padded 20px 30px. Question text sits left and a fine circular downward-arrow control sits right. Pricing stacks use 880px width; feature-detail stacks use 750px.

### Plan card

**Only for:** pricing pages

**Use:** Equal-footing plan summaries.

**CSS:** `display: flex; flex-direction: column; background-color: #ffffff; border: 1px solid rgba(29, 30, 28, 0.1); border-radius: 20px; padding: 20px`

**Text style:** `card-heading` — Muoto VAR 500 · 26px/1.3 · tracking -0.03em

**Observed:** Centered name and short audience line precede price, billing context and a full-width pill. A thin rule starts the left-aligned inclusion list. Warm callout panels occupy the card bottom. The custom plan uses an outlined sales action; other plans use black actions.

**Transfer:** Keep price baselines and action rows aligned across plans; avoid promoting one plan through an unrelated color.

## Imagery and graphics

### Drawn tool accents

**Use:** Signature humanizing detail in opening media, workflow summaries and feature openings.

**Observed:** Thin, slightly organic black outlines depict simple work tools such as a stopwatch, chart and invoice. Warm cream fills, tiny coral/peach accents and minimal internal detail keep them lighter than the interface imagery. They are isolated rather than enclosed in colorful icon boxes.

**Transfer:** Draw an equally simple object associated with the new product's work. A single clear line illustration is preferable to stock 3D artwork.

**Build:** Use SVG paths with approximately 1px dark strokes, cream-filled closed shapes and a few peach-filled detail shapes. Construct a circular dial or rectangular tool body from overlapping outlines; add one offset tab, handle or tiny data badge. Keep the background transparent and avoid gradients or heavy shadows.

### Opening product scene

**Use:** Large working-product counterpart to the opening text.

**Observed:** A clean white calendar-like interface occupies a 720×457px rounded frame with a warm low shadow. Bright orange data blocks punctuate fine gray grids; a large line-drawn tool overlaps the lower-left portion. The surrounding hero stays cream.

**Transfer:** Show a credible sample of the product doing one useful job, with one small drawn accent. If no interface exists, arrange a representative output on a white board in the same proportions.

### Coral patterned product stage

**Use:** Signature large product-demonstration framing and closing backboard.

**Observed:** Flat salmon coral carries low-contrast lighter vertical stripes and angular geometric fragments. Crisp white interface windows sit inside, sometimes with a floating tab enlargement, black cursor or curved annotation arrow. The stage is large enough to dominate its chapter but does not tint adjacent text.

**Transfer:** Place a real product view or representative output in an equally bright white inset; preserve the warm geometric backing and the single-point explanation.

**Build:** Create a coral rectangle with rounded top corners; overlay repeating vertical white strips at roughly 10% opacity, varying widths around 16–60px. Add a few white polygon fragments at 6–10% opacity toward the upper edge. Inset a white rounded rectangle, leaving a clearly visible border. For a demonstration, float one enlarged control above the image and add a thin curved SVG leader. For the final invitation use the 1297px outer and 1156px inner widths.

### Capability fragments

**Use:** Small capability tiles within the bento grid.

**Observed:** Warm cream tiles hold carefully clipped white interface fragments: a rate editor, chart bars with an alert, or a short table. Some tiles arrange colorful integration marks in tidy rows or payment badges as a loose stack. Captions remain outside the image area.

**Transfer:** Reduce a workflow to one legible control or result. Keep natural product colors confined to these fragments; neutralize the surrounding staging.

### Cross-device demonstration

**Use:** Feature-detail platform chapter and final invitation.

**Observed:** A front-facing laptop and overlapping upright phone show the same white productivity interface. The platform chapter includes a vivid orange-red desktop wallpaper behind a small app window. The final invitation uses a large pale interface panel with a phone overlapping its front, cropped at the bottom and right.

**Transfer:** Use accurate device proportions and bright legible screens, not dramatic perspective or glossy reflections. A flat desktop panel plus one narrower output card is a sufficient equivalent without device artwork.

### Icons

**Observed:** Navigation chevrons are 12px with 1.5px round strokes; carousel arrows are 16–18px inside 40px circles. Feature tabs use 20px outline symbols. Platform actions use white 14–18px solid marks; product and integration logos keep their native colors.

**Transfer:** Keep navigational symbols thin, dark and compact, and reserve full-color marks for actual product or partner identity inside media.

## Section recipes

How recurring sections are built.

### First screen: Editorial product opening

**Observed:** The Warm canvas sits behind a Floating navigation bar at the top. Below it, the opening-columns composition centers a 477px text stack opposite a 720×457px Opening product scene. The text occupies about two fifths of the inner width and the media the remaining majority. A 70px regular serif promise wraps into three short centered lines; its final outcome word has a hand-drawn coral underline. A 19px muted support paragraph follows at 32px, then the Email signup capsule and three checkmarked reassurance phrases. Within the first 900px, the full headline, support, form, product scene, proof sentence and monochrome customer-logo strip are visible; the workflow chapter starts below the fold. The media's white frame and tool accent form the foreground, with only a low warm shadow.

**Transfer:** Write a short transformation promise and isolate its outcome word for the underline. Supply an equally strong working interface or sample-output board rather than a generic illustration. Pricing openings instead center a single display headline over billing controls and equal plan cards. Feature-detail openings use a smaller 50px serif promise, a tool illustration, three concise checked benefits and a centered trial action.

**Avoid:** Do not replace this asymmetric text-and-product composition with a giant centered slogan and a tiny decorative mockup, or put the opening on a solid orange background.

**Text style:** `display` — Besley 400 · 70px/1.1 · tracking -0.04em

### Editorial section heading pair

**Observed:** A 50px Besley heading is centered over a 19px introduction in a roughly 670px measure, with 24–32px between them. Major chapters use about 100px top padding. Workflow chapters instead left-align the heading and place circular controls at its right.

**Transfer:** Pair a concrete benefit headline with one clarifying sentence; let the media or cards below carry detail.

**Text style:** `heading` — Besley 400 · 50px/1.1 · tracking -0.04em

### Workflow strip

**Observed:** A White band contains a left-aligned section heading, circular controls and a horizontal run of Workflow items. Items use a 32px gap, no enclosing card surface and visible overflow at the right edge.

**Transfer:** Explain the main activities users move between, without forcing the new product to share the same categories.

### Tabbed capability chapter

**Observed:** On Warm canvas, a centered two-line section heading precedes Capability tabs. A roughly 56px rhythm separates heading, rail and selected panel. A narrow benefit list at left faces an 887×540px Coral patterned product stage at right.

**Transfer:** Use tabs to organize related capabilities and reveal one demonstrable result per panel.

### Capability bento

**Observed:** A White band uses a centered serif heading and five Capability media cards arranged as three narrow cards above two wider ones. Media and captions are separated by 24px, columns by 24px and rows by 40px.

**Transfer:** Vary visual width according to the explanatory needs of the new product, keeping aligned image tops and unboxed captions.

### Metrics and dossiers

**Observed:** On Warm canvas, a centered 50px heading introduces a compact centered row of four 30px sans-serif metrics with small muted descriptors. A horizontal track of Testimonial dossiers follows; 24px gutters and partial next-card visibility make the overflow intentional. Circular navigation appears below, followed by a compact sales invitation.

**Transfer:** Use a few verified metrics and detailed contextual testimonials; prioritize the texture of evidence over huge numerals.

**Text style:** `stat` — Muoto VAR 400 · 30px/1.3 · tracking -0.04em

### Framed invitation

**Observed:** The Coral backboard spans 1297px and starts 44px into a 606px-high cream section. A white Invitation inset begins further down, leaving a visible coral rim. The left side has a 67px serif question, 23px support, Primary button and grouped Platform download pills. A large interface panel and phone overlap at right and are clipped by the section ending. The next white footer meets the board without an extra floating-card shadow.

**Transfer:** Preserve the large warm frame, white inset, oversized question and cropped useful output. Change the action and grouped access options to suit the new product.

**Text style:** `closing-heading` — Besley 400 · 67px/1.1 · tracking -0.04em

### Utility footer with promotion

**Observed:** A White band uses a 1200px wrapper, 56px top padding and 48px bottom padding. A monochrome brand mark sits above three link columns and the Footer promotion at right. Muted category labels precede dark 16px links. A fine rule separates the lower legal/social row, with copyright beneath.

**Transfer:** Close with practical navigation and one compact related offer; retain the warm promotion tile instead of turning the footer dark.

### Feature detail chapters

**Only for:** feature detail pages

**Observed:** A White band introduces a large centered coral-backed product demonstration, then six cream text cards in three columns with 30px gaps. Later, a warm chapter centers a large cross-device visual over two oatmeal explanation cards. Integration tiles use white 20px-radius cards with large partner marks, centered serif names, short descriptions and dot navigation.

**Transfer:** Move from how it works to where it works, then to the surrounding ecosystem; use the compact-serif recipe for text-only card titles.

### Consultation panel

**Only for:** consultation panels

**Observed:** A 1200px white rounded panel uses 40px vertical and 38px horizontal padding. A peach-backed circular illustration sits left of a 30px serif title and 19px support; the primary consultation action aligns right. A thin divider introduces four checked benefits in two columns.

**Transfer:** Use this as a human-assistance bridge for complex adoption, not as another oversized hero.

### Pricing and comparison

**Only for:** pricing pages

**Observed:** A centered 70px headline and 19px support precede a small monthly/annual orange switch and outlined discount badge. Four Plan cards share equal width. Later a white comparison panel places feature labels at left and three centered plan columns at right; 1px alpha-ink rules separate 53px rows, and peach checks indicate inclusion. Compact 40px serif proof metrics appear below the table.

**Transfer:** Keep commercial details scan-friendly and equal-footed; only show genuine differences and verified proof.

### Question stack and related links

**Only for:** feature detail and pricing pages

**Observed:** A centered 50px heading precedes stacked FAQ rows on cream. Feature-detail pages follow with a letterspaced uppercase related-capabilities label between thin rules and two white 585×80px linked rows with small outline icons, 26px serif titles and right circular arrows.

**Transfer:** Answer adoption objections, then offer two adjacent paths without competing with the final conversion.

## Page flow

**Storyline:** Promise → working-product explanation → capability depth → contextual proof → adoption help or objections → framed invitation → practical footer.

### Broad marketing landing page

1. **Promise** — Editorial split opening with embedded signup and a large working-product scene.
2. **Social proof** — Small proof sentence between hairlines and a monochrome logo strip.
3. **Capability overview** — Unboxed illustrated workflow strip followed by a tabbed product chapter.
4. **Capability depth** — Three-plus-two media bento with focused interface fragments.
5. **Quantified and human proof** — Modest metrics above detailed testimonial dossiers.
6. **Closing call** — Large coral-framed white invitation followed by the utility footer and compact promotion.

**Transfer:** Use this as the default landing-page vocabulary, adjusting the number and order of chapters to the new product.

### Plan-selection and purchase-confidence page

1. **Pricing** — Centered promise, small billing switch and four equal plan cards.
2. **Objection handling** — Wide question stack and a human consultation panel.
3. **Comparison** — White feature matrix with three plan columns and fine row rules.
4. **Social proof** — Compact ratings and serif metrics, followed by a testimonial area.
5. **Closing call** — The shared framed invitation and white utility footer.

**Transfer:** Prioritize aligned commercial information and objection handling while retaining the same editorial frame and closing device.

### Focused capability explanation

1. **Promise** — Breadcrumb, tool illustration, compact serif promise, three checked benefits and trial action.
2. **Product demonstration** — Centered introduction and large coral-backed working interface.
3. **Capability depth** — Text-only feature cards, cross-device demonstration and supporting explanations.
4. **Ecosystem proof** — Integration carousel and consultation panel.
5. **Objection handling** — Question stack and paired related-capability links.
6. **Closing call** — The same framed invitation and white footer.

**Transfer:** Keep one capability as the subject, showing usability, availability and adoption reassurance without reproducing the broad landing-page opening.

## Writing

Warm, practical and commercially confident. The language connects ordinary work to measurable outcomes without sounding technical or grandiose.

**Do not copy:** Do not reuse Harvest or Forecast names, logos, customer identities, quotations, claimed integrations, audience counts, uptime, money totals, prices or trial terms; replace them with accurate material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your team for benefits; refer to the product by name when explaining a concrete capability. We appears sparingly when describing design intent.
- **Rhythm:** Short benefit-led headings, often one or two clauses, followed by one clear explanatory sentence. Longer descriptions list familiar tasks rather than abstract promises; questions create gentle invitations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Turn a familiar input into a valuable outcome. | 4–8 words | “Turn hours into profit” |
| Section headline | A practical outcome expressed in everyday language. | 6–13 words | “Everything connects, so your business runs more smoothly”<br>“Time tracking that doesn’t get in your way” |
| Supporting line | Describe what the product enables, naming recognizable actions. | 15–25 words | “[Brand] helps professional teams track time, bill clients, optimize team time, and measure performance with confidence.” |
| Capability description | Specific mechanism followed by how it helps. | 12–25 words | “Set rates by person, project, or task type. [Brand] picks the right one automatically.” |
| Primary action | Verb-led, direct, low-commitment invitation. | 2–5 words | “Get started for free”<br>“Book a consultation” |
| Closing question | Restate the core transformation as a readiness question. | 6–10 words | “Ready to turn hours into profit?” |

**Words and phrasing to use:** your team; make it easy; wherever you work; confidence; simple; flexible; connects; keep track; get started

**Avoid:** revolutionary; disruptive; unlock limitless potential; next-gen powerhouse; synergy; hyperautomation

**Rules:**

- Lead with the useful outcome, then name the mechanism in the support copy.
- Use concrete verbs for overview categories and concrete nouns for capability titles.
- Keep reassurance factual and short enough to sit beside a small checkmark.
- State numbers only when they are substantiated; explain each metric in a compact descriptor.
- Use the final question to echo the opening promise rather than introducing a different pitch.

## Do's and Don'ts

### Do

- Keep large serif headings at weight 400 and -0.04em tracking.
- Use 1297px outer and 1200px standard wrappers for the two main desktop alignments.
- Let white and cream full-width bands do most of the section separation.
- Keep product fragments on 20px-radius warm tiles with captions outside.
- Carry the coral backboard device into a new page's major product scene or invitation.
- Use 30px-radius black pills for actions and thin gray outlines for secondary choices.
- Keep default proof values at 30px and pair them with small explanatory labels.
- Use partial next-card visibility in horizontal workflow and testimonial tracks.

### Don't

- Do not turn the serif display into a heavy bold slab or an italic luxury treatment.
- Do not make every card a shadowed floating panel; most cards are flat tonal surfaces.
- Do not spread orange across entire text sections; reserve broad color for media framing.
- Do not enlarge ordinary descriptions beyond the 16px body scale just to fill space.
- Do not use neon gradients, dark glass panels or luminous borders for product stages.
- Do not replace the fine outlined tool accents with thick multicolor icon squares.
- Do not use enormous counter numerals that compete with the 50px section headings.
- Do not reverse the footer to black or erase its compact warm promotional card.

## Motion and responsive

### Motion

**Observed:**

- Navigation text declares color transitions of 0.2s. Primary actions declare background-color and color transitions of 0.2s; platform pills declare background-color 0.2s.
- The email capsule declares background-color and border-color transitions of 0.2s; its submit action declares a 0.15s linear transition.
- The opening outcome word has slide-out and drop-in animation definitions. Workflow, testimonial and integration content use carousel controls.

**Transfer:**

- Keep interaction feedback concentrated on text color, dark-button fill and fine control outlines.
- If rotating the opening outcome word, preserve the centered headline measure and coral underline while changing the word.

**Unknown:**

- Exact hero word timing and easing, carousel timing, scroll triggers and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Desktop composition is established at 1440px. Styles include breakpoints around 640px, 767–768px, 850–851px, 1050–1051px and 1280px; individual behavior is not established.
- The tab rail and platform action groups allow wrapping.

**Transfer:**

- On narrower screens, stack the editorial text before its product scene, preserving the outcome underline and full-width rounded signup treatment.
- Reduce plan and capability grids to fewer columns while keeping media titles outside their tiles.
- Keep the coral invitation frame visible as a rim around a stacked white inset; place the product scene after the action instead of squeezing it beside the headline.

**Unknown:**

- Exact mobile font sizes, navigation replacement, card dimensions and breakpoint-specific ordering remain unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
