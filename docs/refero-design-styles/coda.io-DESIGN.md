# Coda — playful working parts

## Overview

A bright, approachable software style that makes complex work feel tangible and manageable. Heavy, tightly fitted sans-serif headlines sit above useful interface scenes, with warm apricot, cream and pale blue giving the otherwise white pages a friendly workshop character. Crisp black offset edges, small illustrated objects and occasional editorial serif quotes keep the spacious, demonstration-led presentation from feeling corporate.

### Essentials

- Headlines feel like compact verbal objects: Calibre-R at 72px/1, weight 700 and -0.045em tracking for the main promise; 52px/1.1 and -0.035em for section leads.
- The opening has a calm runway before the big promise: a 115px navigation stack, a 328px announcement panel, then a left-aligned apricot hero with an 852px text measure and a 1136px-wide interface stage below.
- Actions are rounded rectangles, not capsules: near-black primary buttons use 12px corners, 16px 28px padding and 20px/30px semibold labels; compact actions use 8px corners and 16px/22px labels.
- White carries the long explanatory middle; pale color belongs to full-width chapter bands, media backings and the cream footer. Saturated orange is concentrated in the 36px announcement strip rather than spread across buttons and headings.
- The product is a working object, not a floating device mockup: show real task content in white browser-like panels with thin dark edges and a hard 8px 8px offset shadow. Include this graphic device on every landing page; use a carefully typeset workflow facsimile if a finished interface is unavailable.
- Friendly proof has two distinctive voices: a peach-highlighted phrase inside a 52px bold statement, and a broad apricot testimonial panel using a 38px light serif quote with a small portrait attribution. Carry both devices into new content without prescribing their position in the story.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Announcement orange | `#ee5a29` | `--color-orange` | background, accent | Narrow announcement strip and small identity accents. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Peach emphasis | `#fdc298` | `--color-peach-text` | text | A short inline phrase in a bold section statement. |
| Apricot | `#ffe6c9` | `--color-apricot` | background, surface | Warm hero and testimonial color family; also the comparison migration panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main page canvas, white interface panels and reversed button labels. |
| Warm white | `#fcfaf7` | `--color-navigation` | background, surface | Default navigation backing and light media stages. |
| Footer cream | `#fff6ec` | `--color-cream` | background | Footer and broad template-selection chapter. |
| Oat | `#f7f6f2` | `--color-tile` | surface | Integration tiles and secondary-button hover fill. |
| Faint gray edge | `#e6e6e6` | `--color-header-edge` | border | Visible black-at-10% navigation boundary over white. |
| Soft gray edge | `#e0e0e0` | `--color-media-edge` | border | Visible black-at-12% edge over white; also the secondary action inset outline. |
| Stone rule | `#dedbd5` | `--color-rule` | border | Card outlines, inactive tab rules and inset navigation-button edges. |
| Mid gray | `#8d8a86` | `--color-footer-rule` | border, text | Footer divider, calculator borders and inactive controls. |
| Warm gray | `#73716d` | `--color-muted` | text | Supporting paragraphs and secondary metadata. |
| Soft charcoal | `#474543` | `--color-secondary-ink` | text | Secondary action labels and denser supporting text. |
| Warm charcoal | `#292827` | `--color-heading` | text | Headlines, navigation and strong labels. |
| Near black | `#141413` | `--color-action` | action, text, border | Primary actions, body links, strong rules and graphic offset edges. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| AI and comparison chapters | Pale sky | `#d9f6fc` | `--color-sky` | background | Cool media stages and capability bands. |
| launch announcements | Barely lavender | `#faf3ff` | `--color-lavender` | background | Top announcement panel. |
| comparison calculators | Warm pricing wash | `#fbefdd` | `--color-pricing-warm` | surface | Visible 20% amber wash over white, using rgba(237,175,86,0.2). |
| comparison calculators | Neutral pricing wash | `#f7f7f7` | `--color-pricing-neutral` | surface | Visible 80% light gray over white, using rgba(245,245,245,0.8). |
| comparison calculators | Amber badge | `#edaf56` | `--color-amber` | accent, surface | Small recommended-plan badge. |
| comparison pages | Cream edge | `#f2f0eb` | `--color-panel-edge` | border | Subtle outline on the apricot migration panel. |

## Typography

- **Calibre-R** — Bold marketing headlines and large numeric proof. Soft, compact grotesk with a large x-height and tightly interlocked bold forms. If unavailable, use **Inter Tight**. Use 700 and preserve the tight tracking; check headline wraps. Font stack: "Calibre-R", "Inter Tight", sans-serif.
- **Inter** — Supporting copy, navigation, buttons, cards and questions. Practical neutral sans-serif, regularly spaced in construction but set with negative tracking. Font stack: "Inter", sans-serif.
- **Tiempos-Headline** — Editorial customer quotations. Light, high-contrast headline serif; a deliberate change from the bold sans hierarchy. If unavailable, use **Newsreader**. Use 300 with a generous 52px line height at 38px. Font stack: "Tiempos-Headline", "Newsreader", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Calibre-R | 700 | 72px | 1 | -0.045em | Main promise and expansive closing conversion lines. |
| heading | Calibre-R | 700 | 52px | 1.1 | -0.035em | Main section leads and large pricing figures. |
| heading-small | Calibre-R | 700 | 38px | 1.1 | -0.025em | Use-case chapter labels, announcement headlines and smaller calls. |
| quote | Tiempos-Headline | 300 | 38px | 52px | -0.01em | Wide customer quotation, contrasting with the sans headings. |
| lead | Inter | 400 | 22px | 34px | -0.03em | Hero support and closing support lines. |
| body-large | Inter | 400 | 20px | 1.5 | -0.03em | Section supporting paragraphs. |
| label-large | Inter | 600 | 20px | 1.5 | -0.03em | Large action labels, card titles and tab labels. |
| body | Inter | 400 | 16px | 1.5 | -0.03em | Card descriptions, footer links and compact explanations. |
| action-small | Inter | 600 | 16px | 22px | -0.03em | Compact actions, including the dark header action. |
| navigation | Inter | 600 | 16px | 1.5 | -0.03em | Navigation, attribution names and the header secondary action. |
| announcement | Inter | 600 | 14px | 20px | -0.03em | Announcement strip text. |
| caption | Inter | 400 | 14px | 20px | -0.03em | Attribution roles and short resource-card metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FAQ sections | question | Inter | 400 | 26px | 1.33 | -0.03em | Expandable question rows. |

**Notes:**

- All marketing sans copy has negative tracking; the display face tightens further as size grows, from -0.025em through -0.035em to -0.045em.
- Use the 52px heading as the ordinary section lead; reserve 72px for promises, major anthology dividers and closing calls.
- The serif is a quotation voice, not a replacement heading family. Main support stays warm gray while headlines remain charcoal.

## Layout

**Density:** Airy: broad white chapters surround compact labels, controls and useful interface detail.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-support gap and compact navigation spacing. |
| 12px | Footer link rhythm and attribution portrait-to-label spacing. |
| 16px | Paired-action gap and ordinary inline grouping. |
| 20px | Vertical action-group padding and FAQ row padding. |
| 24px | Card-grid gutter and image-to-text group spacing. |
| 32px | Container side padding, logo-strip gap and tile vertical padding. |
| 40px | Footer utility padding above its divider-separated content. |
| 48px | Heading-pair to card-grid separation and migration-panel inset. |
| 60px | Footer top and bottom padding. |
| 72px | Standard chapter top and bottom padding. |
| 86px | Inset around large tabbed interface previews. |
| 96px | Gutter between equal feature columns. |
| 100px | Hero runway layers before the main headline. |

### Containers and grids

- **container**: max width 1200px · side padding 32px. Centered outer container; the usable content span is 1136px at a 1440px viewport, beginning 152px from either edge.
- **feature-pair**: 2 columns · gap 96px. Equal 520px text/media columns, vertically centered; alternate the media side between capability chapters.
- **hero-copy**: max width 852px. Main promise measure, approximately three quarters of the content width, aligned to the shared left edge.
- **feature-cards**: 3 columns · gap 24px. Three equal cards of about 363px each within the content span.
- **footer-grid**: 6 columns · gap 24px. A small identity-and-tagline column followed by five useful navigation columns, about 169px each.
- **integration-grid** (only for integration catalogs): 4 columns · gap 24px. Two rows of 266px integration tiles.
- **template-grid** (only for template catalogs): 2 columns · gap 0px. Two-column template catalog with internal item insets; previews are about 534px wide.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | compact-actions-and-cards | 8px |
|  | large-actions-and-proof-panels | 12px |
|  | interface-previews | 9.6px |
|  | portrait | 50% |
| catalogs and comparison calculators | integration-and-price-tiles | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| hard-product-edge | `8px 8px 0px 0px #141413` | Signature framed product demonstration. |
| soft-card | `rgba(0, 0, 0, 0.06) 0px 12px 24px -5px, rgba(0, 0, 0, 0.06) 0px 5px 10px -6px` | Resource cards, integration tiles and large preview frames. |
| soft-feature | `rgba(0, 0, 0, 0.06) 0px 18px 36px -6px, rgba(0, 0, 0, 0.06) 0px 6px 12px -6px` | Interface details in feature chapters. |

### Surfaces

#### White canvas · level 0

**Use:** Long-form explanatory middle.

**CSS:** `background: #ffffff; color: #292827`

#### Apricot stage · level 0

**Use:** Hero, large testimonial panel and selected calls.

**CSS:** `background: #ffe6c9`

**Observed:** A flat, pale warm field, not a glossy gradient. Large areas of white separate the colored chapters.

**Transfer:** Use one warm field to make the main working object feel inviting.

#### Cream band · level 0

**Use:** Footer and template-selector chapter.

**CSS:** `background: #fff6ec`

**Observed:** The warmth is subtle, lighter than the apricot proof panel.

**Transfer:** Use it as a calm organizational surface beneath dense navigation or grouped starter content.

#### Resource card · level 1

**Use:** Image-led capability and resource summaries.

**CSS:** `background: #ffffff; border: 1px solid #dedbd5; border-radius: 8px; box-shadow: rgba(0, 0, 0, 0.06) 0px 12px 24px -5px, rgba(0, 0, 0, 0.06) 0px 5px 10px -6px; overflow: hidden`

**Observed:** A short landscape media header sits over a white text area; several cards share a baseline.

**Transfer:** Keep descriptions concise enough for aligned rows.

#### Soft interface panel · level 1

**Use:** Fine-grained product demonstrations.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 9.6px; box-shadow: rgba(0, 0, 0, 0.06) 0px 18px 36px -6px, rgba(0, 0, 0, 0.06) 0px 6px 12px -6px`

**Observed:** This softer frame complements, rather than replaces, the hard-edged signature frame.

**Transfer:** Use it for close-up interface details.

#### Cool stage · level 0

**Only for:** AI and comparison chapters

**Use:** Cool variant of a feature band or product preview backing.

**CSS:** `background: #d9f6fc`

**Observed:** Flat pale cyan surrounds a crisp white interface; the text remains charcoal.

**Transfer:** Use for a clearly scoped capability rather than alternating color arbitrarily.

#### Recommended comparison surface · level 1

**Only for:** comparison calculators

**Use:** Highlighted price result.

**CSS:** `background: rgba(237, 175, 86, 0.2); border-radius: 16px; padding: 32px`

**Observed:** Paired with an equally sized neutral result using rgba(245,245,245,0.8); both use dark type, not inverse text.

**Transfer:** Differentiate the preferred result with a warm wash, not a more dominant size.

#### Migration panel · level 1

**Only for:** comparison pages

**Use:** A practical switch-or-import call.

**CSS:** `background: #ffe6c9; border: 1px solid #f2f0eb; border-radius: 12px; padding: 48px; box-shadow: rgba(0, 0, 0, 0.06) 0px 12px 24px -5px, rgba(0, 0, 0, 0.06) 0px 5px 10px -6px`

**Observed:** A small sculptural illustration precedes a large heading, support, detail and paired compact actions.

**Transfer:** Pair the conversion action with the concrete migration step.

## Components

### Navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: sticky; top: 0px; z-index: 100; background: #fcfaf7; border-bottom: 1px solid rgba(0, 0, 0, 0.1)`

**Text style:** `navigation` — Inter 600 · 16px/1.5 · tracking -0.03em

**Observed:** A narrow announcement strip is stacked above a roughly 79px navigation row. Identity sits left; dropdown labels, a thin divider, direct links and two compact actions fill the row. Dropdown triggers use 18px chevrons and 8px corners. Comparison and editorial variants use a fixed white header with 24px backdrop blur over their opening color.

**States:** Declared: hover on navigation triggers uses rgba(41,40,39,0.06) backing and #292827 text.

**Transfer:** Keep a compact set of destinations and one clear conversion pair; do not turn the navigation into a full-width menu grid.

### Announcement strip

**Use:** A single timely announcement above navigation.

**CSS:** `background: #ee5a29; height: 36px; display: flex; align-items: center`

**Text style:** `announcement` — Inter 600 · 14px/20px · tracking -0.03em

**Observed:** Text aligns to the same content edge as the page and includes an inline arrow and destination. Its orange is the most saturated large CSS fill in the core shell.

**Transfer:** Keep the message on one compact line at desktop.

### Primary button

**Use:** Main sign-up or conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #141413; color: #ffffff; border-radius: 12px; padding: 16px 28px; height: 62px; box-shadow: #292827 0px 0px 0px 1.5px inset`

**Text style:** `label-large` — Inter 600 · 20px/1.5 · tracking -0.03em

**Observed:** Content-sized rectangle with a single centered label; paired secondary action sits 16px away.

**States:** Declared: hover uses #292827, rgba(0,20,20,0.2) 0px 8px 24px 0px shadow and translateZ(0px) scale(1.02); active uses scale(1).

**Transfer:** Use the large size for opening and closing actions, not every link.

### Secondary button

**Use:** Sales or supporting conversion beside the primary.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: rgba(255, 255, 255, 0.85); color: #474543; border-radius: 12px; padding: 16px 28px; height: 62px; box-shadow: #e0e0e0 0px 0px 0px 1.5px inset`

**Text style:** `label-large` — Inter 600 · 20px/1.5 · tracking -0.03em

**Observed:** The same label scale and geometry as the primary, but a pale translucent face. Header secondary actions instead have 8px corners, 8px 12px padding, 40px height and the navigation recipe.

**States:** Declared: hover uses #f7f6f2 and translateZ(0px) scale(1), retaining the inset outline; active uses scale(0.98).

### Compact button

**Use:** Chapter links and template actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #141413; color: #ffffff; border-radius: 8px; padding: 8px 20px; height: 38px; box-shadow: #292827 0px 0px 0px 1.5px inset`

**Text style:** `action-small` — Inter 600 · 16px/22px · tracking -0.03em

**Observed:** Short dark content-sized action. The header dark variant is 40px high with 8px 12px padding. A pale supporting variant uses the secondary-button face and outline with this compact geometry.

**States:** Declared: hover uses #292827 with rgba(0,20,20,0.2) 0px 8px 24px 0px shadow and translateZ(0px) scale(1.02); active uses scale(1).

### Feature card

**Use:** Three-up capability or learning-resource summary.

**CSS:** `display: flex; flex-direction: column; border: 1px solid #dedbd5; border-radius: 8px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.06) 0px 12px 24px -5px, rgba(0, 0, 0, 0.06) 0px 5px 10px -6px`

**Text style:** `label-large` — Inter 600 · 20px/1.5 · tracking -0.03em

**Observed:** About 363px wide, with a 361px by 144px illustrated interface header. White copy panel has 24px 32px padding, a semibold title and 16px body beneath. Customer-resource variants add a small circular portrait and attribution at the bottom.

**Transfer:** Show one meaningful product interaction per card rather than an abstract icon for every benefit.

### Product frame

**Use:** Signature working-object demonstration.

**CSS:** `border: 2px solid #141413; border-radius: 12px; box-shadow: #141413 8px 8px 0px 0px; overflow: hidden; display: flex`

**Observed:** A white browser-like surface with subtle window controls holds the product at useful scale. Core use-case frames are about 454px by 437px around 450px by 433px media. A larger starter preview uses a 1px outline, 9.6px corners and 6px offset; comparison demonstrations can use a 16px offset.

**Transfer:** Keep the dark offset edge visible on the bottom and right. Fill the frame with a convincing task, not decorative blocks.

### Footer

**Use:** Shared warm ending and dense utility navigation.

**CSS:** `background: #fff6ec; padding: 60px 0px; display: flex; justify-content: center`

**Text style:** `body` — Inter 400 · 16px/1.5 · tracking -0.03em

**Observed:** Six columns include a small mark-and-tagline block followed by five navigation groups. Group labels are gray, links dark, with 12px vertical gaps. A 1px mid-gray divider leads to 40px top padding, legal links, small social marks and a separate privacy-choice link.

**Transfer:** Preserve the compact brand column and generous column spacing; keep the footer light even after a strong conversion section.

### Integration tile

**Only for:** integration catalogs

**Use:** Scannable ecosystem or partner directory.

**CSS:** `display: flex; flex-direction: column; gap: 24px; background: #f7f6f2; border-radius: 16px; padding: 32px 40px; box-shadow: rgba(0, 0, 0, 0.06) 0px 12px 24px -5px, rgba(0, 0, 0, 0.06) 0px 5px 10px -6px`

**Text style:** `label-large` — Inter 600 · 20px/1.5 · tracking -0.03em

**Observed:** A colored 50px partner mark sits above a left-aligned label in a 266px by 168px tile; four tiles fit across.

**Transfer:** Retain each integration's own small mark while keeping the card background neutral.

### Demo tabs

**Only for:** multi-example product demonstrations

**Use:** Switch between full-size examples.

**CSS:** `display: flex; gap: 16px; position: relative`

**Text style:** `label-large` — Inter 600 · 20px/1.5 · tracking -0.03em

**Observed:** Three or four equal labels sit in an 84px row with 24px vertical padding, small marks and a continuous 2px stone top rule; a charcoal segment indicates the selected example. Beneath is an 1136px-wide media stage with 86px insets around a 964px preview.

**Transfer:** Use the same task taxonomy in tab label and preview; keep all tab labels visible rather than hiding choices in a dropdown.

### FAQ row

**Only for:** FAQ sections

**Use:** Late-page objection handling.

**CSS:** `border-top: 1px solid #141413; padding: 20px 0px; display: flex; gap: 24px; align-items: flex-start`

**Text style:** `question` — Inter 400 · 26px/1.33 · tracking -0.03em

**Observed:** Approximately 76px tall at desktop; a regular-weight question fills the row and a 28px plus symbol sits at the far right. No enclosing card or colored answer box is used.

**Transfer:** Use full-width ruled rows and actual questions; expanded-answer behavior is not specified.

### Pricing calculator

**Only for:** comparison calculators

**Use:** Make a pricing difference tangible.

**CSS:** `display: flex; gap: 24px`

**Text style:** `body` — Inter 400 · 16px/1.5 · tracking -0.03em

**Observed:** A roughly 321px control column sits beside two 384px by 319px result panels with 32px padding and 16px corners. White numeric inputs are 90px by 48px with 1px mid-gray edges and a narrow plus/minus stepper; labels sit alongside. Both results use the 52px heading recipe for the amount; the preferred result has a small amber badge and a warm wash.

**Transfer:** Use verified costs, equal visual area for both alternatives and short, comparable benefit lists.

## Imagery and graphics

### Working interface scenes

**Use:** Primary hero object and recurring capability demonstrations.

**Observed:** Real documents, tables, timelines and collaboration controls are shown straight-on in white browser-like panels. Content is detailed enough to read as useful work, with tiny avatars, restrained colored statuses and occasional emoji. Large hero media spans 1136px; chapter images usually occupy a 520px column.

**Transfer:** Show the new product performing a recognizable task. If polished media is unavailable, typeset a faithful, functional-looking task view with a title, short context, a small table or document and a few human collaboration cues; use Product frame rather than a laptop photograph.

### Illustrated working parts

**Use:** Small narrative objects accompanying transitions and use-case chapters.

**Observed:** Flat, outlined objects such as sheets, app tiles and work tools have warm pale faces, black contours and slightly extruded black edges. They act like friendly physical parts of a system rather than glossy 3D sculptures.

**Transfer:** Draw a few objects specific to the new product's workflow; the minimum version is a rounded rectangular sheet or task tile with an offset edge and a simple meaningful symbol.

**Build:** Use SVG with a rounded rectangular front, 1px–2px near-black stroke, cream or apricot fill and a second dark silhouette translated 6px–8px down and right. Add one small line symbol; keep shading flat and the perspective slight.

### Editorial proof panel

**Use:** A substantial testimonial with a contrasting typographic voice.

**Observed:** A broad flat apricot panel with 12px corners contains a customer wordmark, a large light serif quotation and a small round portrait beside name and role. The quotation is the dominant object; there is no oversized decorative quote glyph.

**Transfer:** Use a real, specific outcome and a compact attribution. If no portrait is available, keep the text attribution without introducing stock lifestyle photography.

### Problem-to-order scroll scene

**Only for:** immersive brand explainers

**Use:** An extended visual argument between the initial product stage and detailed use cases.

**Observed:** A white full-viewport scene alternates centered bold lines and large numeric facts with scattered app or document tiles; dense overlapping interfaces embody clutter. A slim progress track sits near the bottom. The narrative resolves into a warm flat statement and a clear product demonstration.

**Transfer:** Use the new product's actual friction and substantiated facts. A minimum version is a static before/after composition of scattered task tiles becoming one legible working panel.

**Build:** Stage a 1440px by 900px composition with text centered and 8–12 outlined rounded tiles of varied scale distributed around the edges. Use white tile faces, dark offset silhouettes, sparse colored symbols and a short dark segment over a pale horizontal progress line. Keep the central message unobstructed.

### Launch collage

**Only for:** launch announcements

**Use:** A special product-evolution chapter, distinct from the ordinary hero.

**Observed:** A softly blurred pink-and-lilac field backs a white folded-paper product collage on one side and bold explanation on the other. The collage shows several interface snippets layered around open paper planes.

**Transfer:** Confine this more atmospheric look to a genuine launch story. Use a clean white folded-sheet SVG and a few genuine product fragments as the minimum equivalent.

**Build:** Place broad pale pink and lilac radial gradients behind the section, with softened transitions rather than sharp stops. Layer three white quadrilateral paper planes at alternating slight angles, each with a faint gray edge and soft shadow; place interface fragments across the planes without obscuring the headline.

### Constructed editorial sculpture

**Only for:** company-use and culture stories

**Use:** An illustration-led split hero.

**Observed:** A mustard-yellow field holds a large green and yellow extruded puzzle-like slab, fine pale graph lines and a diagonal construction line. A black underside makes the object look cut from thick material; the right-hand object is nearly as tall as the hero.

**Transfer:** Use an original interlocking shape expressing the new story, not a generic stock illustration. Keep the construction-grid and solid underside treatment.

**Build:** In SVG, draw a rounded polygon with a circular notch, skew it into an oblique plane, duplicate its silhouette downward for a black underside and connect the edges. Split the top into two flat colors. Behind it draw evenly spaced pale grid lines at low opacity and one fine dark diagonal guide. Keep this saturated treatment confined to editorial storytelling.

### Community proof wall

**Only for:** comparison pages

**Use:** Last social confirmation after the practical migration call.

**Observed:** A wide masonry-like collage of small social posts uses white rectangles, fine borders, tiny portraits and naturally varied heights across several columns. It follows the migration panel and precedes the cream footer.

**Transfer:** Use permissioned, real short customer comments, with uneven natural lengths; do not convert them into large polished quotation cards.

### Icons

**Observed:** Navigation uses small 18px chevrons; social and utility marks are mostly 24px filled shapes in charcoal. Expand controls are 28px mixed-stroke plus marks with 2px rounded strokes. Small chapter illustrations are larger, colored and outlined rather than a uniform icon library.

**Transfer:** Use simple filled utility icons for navigation and social links, restrained outline expand controls, and a separate small illustrated-object vocabulary for narrative sections.

## Section recipes

How recurring sections are built.

### First screen: Warm product opening

**Observed:** The first 900px stacks a 36px orange Announcement strip and warm-white Navigation into a 115px shell. A 328px pale-lavender launch announcement follows, aligned to the content left edge, with a 38px bold line, 16px explanation and Compact button. Beneath it a flat apricot hero begins. Two 100px runway layers place the 72px, tightly tracked two-line promise deep in this band; its 852px measure spans roughly three quarters of the shared content width. A gray 22px support line follows at an 8px gap. The paired 62px actions begin near the bottom of the first 900px and continue below it. The main 1136px-wide working interface appears below the first fold, not alongside the headline. Layers are flat color, aligned text and actions, then the large framed product object lower down.

**Transfer:** For an ordinary landing page, retain the warm runway, bold promise and below-headline working object; the launch panel is a scoped announcement variant, not permanent product content. Create a credible workflow facsimile if finished media is unavailable. Product variants can use a neutral or pale-blue stage. Comparison variants open directly with text left and an oversized right-side interface spilling beyond the viewport; editorial variants open directly with text left and a constructed illustration right.

**Avoid:** Do not compress this into a centered headline with a floating dashboard squeezed fully into the first fold, or make the launch panel the main product promise.

**Text style:** `display` — Calibre-R 700 · 72px/1 · tracking -0.045em

### Heading and support pair

**Observed:** A 52px heading and 20px support line sit 8px apart, usually left-aligned; the text group can use a 909px measure. Card chapters leave about 48px before their grid. Standard chapters have 72px top and bottom padding.

**Transfer:** Lead with the outcome, then explain the mechanism in one concise paragraph.

**Text style:** `heading` — Calibre-R 700 · 52px/1.1 · tracking -0.035em

### Alternating capability pair

**Observed:** A 520px text column faces a 520px interface across a 96px gap. Text is vertically centered, with a 52px heading, 20px paragraph and optional Compact button. Media alternates sides; white separates the chapters.

**Transfer:** Use one task and one clear payoff per pair. Keep the interface scene meaningful at its displayed size.

### Use-case proof chapter

**Observed:** A 38px category heading and 16px support sit left beside a Product frame. A small illustrated chapter symbol appears beside the heading; Compact button follows the copy. Near the bottom of the text column a short top rule introduces a small replacement-tool strip. Thin full-width rules separate chapters.

**Transfer:** Show a workflow category, a practical example and a small context comparison without needing an elaborate table.

### Inline quantified statement

**Observed:** A 52px bold statement contains a peach-text span with exactly the same weight, line height and tracking. It reads as one sentence rather than a number above a detached caption.

**Transfer:** Highlight a short verified number or phrase in an otherwise charcoal statement; keep it in the same typographic voice.

**Text style:** `heading` — Calibre-R 700 · 52px/1.1 · tracking -0.035em

### Capability card row

**Observed:** Heading and support pair introduces three Feature cards with 24px gaps. Their short, pale-backed interface headers precede semibold benefit labels and small gray explanations.

**Transfer:** Use three genuinely distinct interactions, not three paraphrases of the main claim.

### Tabbed working example

**Observed:** Demo tabs precede a broad neutral or pale-blue stage. An 86px inset surrounds the large white preview with fine corners and a soft shadow.

**Transfer:** Offer multiple task examples while letting one large realistic working view carry the visual proof.

### Starter selector

**Observed:** A broad Cream band opens with Heading and support pair. A row of role tabs leads to a left-hand list of illustrated starter items and a much larger framed preview on the right. A white selected item contrasts with the cream background; a short caption and Compact button sit below the preview.

**Transfer:** Use categories relevant to the new audience, with the preview showing actual starter content instead of a generic benefit card.

### Serif proof pause

**Observed:** Editorial proof panel occupies the 1136px content width with 38px side insets and 86px vertical padding. Its internal groups are separated by 32px; the 38px/52px serif quote occupies about 848px of width. A 44px portrait and two-line attribution close the panel.

**Transfer:** Give a concrete customer outcome room to be read as a human statement.

**Text style:** `quote` — Tiempos-Headline 300 · 38px/52px · tracking -0.01em

### Closing conversion and warm directory

**Observed:** The default closing chapter is a white, left-aligned value argument with a 52px heading, 20px support and paired Compact buttons before Footer. Product and editorial variants use a larger 72px closing line with 22px support and 62px actions, within a roughly 416px chapter. The AI variant ends with ruled FAQ rows directly before Footer; comparison ends with a migration panel and a Community proof wall before Footer.

**Transfer:** Choose the closing structure that resolves the page's remaining decision: value argument, direct start, objections or practical migration. Preserve the shared cream directory ending.

### Editorial walkthrough anthology

**Only for:** company-use stories

**Observed:** A direct illustrated split opening leads to repeated alternating text-and-media chapters, each roughly 444px high. Text uses a 52px heading, a 20px explanation naming a practitioner and, where relevant, a Compact button. Major topic groups are introduced by 72px lines and large directory actions.

**Transfer:** Organize genuine practitioner walkthroughs into readable families; use a representative task poster or playable video beside each narrative, not an empty decorative panel.

## Page flow

**Storyline:** Promise → tangible working proof → credibility → capability chapters → examples to start from → decision support → warm directory ending.

### Broad marketing landing page

1. **Announcement and promise** — Compact launch announcement followed by a warm, spacious text-first hero and large framed working view.
2. **Credibility and problem framing** — Monochrome logo strip, immersive clutter-to-order argument and external editorial endorsement.
3. **Capability chapters** — Inline quantified statement, ruled use-case chapters, capability cards and an integration demonstration.
4. **Activation** — Role-based starter selector turns the broad promise into ready-made ways to begin.
5. **Decision support** — Wide serif customer quote followed by a concise value argument and paired actions.
6. **Directory ending** — Cream footer with a small identity column, five link groups and ruled utilities.

**Transfer:** Move from broad promise to practical work, and let tangible examples carry most of the explanation.

### Focused product-capability landing page

1. **Promise** — Short, witty headline on a neutral stage above a large interface view.
2. **Credibility** — Launch-evolution chapter and centered customer logo strip.
3. **Capability chapters** — Alternating connected-data, configurable-workflow and collaboration demonstrations; one cool-tinted capability band.
4. **Ecosystem proof** — Four-column integration tile grid and a tabbed large example.
5. **Activation** — Two-column template gallery followed by a 72px closing call and paired large actions.
6. **Directory ending** — Shared cream footer.

**Transfer:** Start with the friction the capability removes, demonstrate its mechanics and end with an immediately usable starter.

### Intelligent-feature landing page

1. **Promise** — Pale-blue text-first hero and a large working demonstration.
2. **Orientation and credibility** — Launch explanation, compact enterprise logo strip and three capability cards.
3. **Capability chapters** — Alternating detailed interface scenes explain finding, writing, extracting and automating work.
4. **Value and activation** — Included-value demonstration, three starter previews and compact learning resources.
5. **Objection handling** — Five full-width ruled question rows lead directly into the cream footer.

**Transfer:** Explain the tool through recognizable tasks, then resolve cost and data concerns instead of appending an unrelated closing sales band.

### Competitive comparison and migration page

1. **Differentiated promise** — Direct pale-blue split hero with a large right-side interface extending offscreen.
2. **Credibility** — Logo strip and illustrated external endorsement.
3. **Comparative demonstration** — Tabbed examples and alternating capability pairs contrast restrictions with useful flexibility.
4. **Breadth and social proof** — Integration grid, small customer-resource cards and a wide serif quote.
5. **Economic proof** — Interactive control column beside equally sized warm and neutral price-result panels.
6. **Objection handling and migration** — Ruled questions lead to an apricot illustrated import call, followed by a community-post collage.
7. **Directory ending** — Shared cream footer.

**Transfer:** Demonstrate the practical difference, quantify it fairly and make the next migration step explicit.

### Practitioner-led editorial anthology

1. **Editorial promise** — Direct mustard illustration-led split hero with a 72px title and paired actions.
2. **Practical proof** — Alternating practitioner walkthroughs and concise task descriptions.
3. **Chapter navigation** — Large topic dividers separate families of examples and link to deeper starter collections.
4. **Closing call** — A 72px conversion line, brief support and paired 62px actions.
5. **Directory ending** — Shared cream footer.

**Transfer:** Use real practitioners and repeatable artifacts to make an internal-use story useful to outsiders.

## Writing

Confident, helpful and a little mischievous. Practical outcomes and specific work situations make the confidence credible; wordplay softens the explanation rather than replacing it.

**Do not copy:** Do not reuse Coda or Superhuman names, identity artwork, partner logos, customer quotations, competitive claims, integration totals, adoption figures, savings percentages or prices as claims for another product. Replace them with original assets and verified facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Use we sparingly for product choices and pricing philosophy; name the product when stating what it does.
- **Rhythm:** Short headline clauses, often paired or punctuated for emphasis, followed by one conversational explanatory paragraph. Contractions and em dashes are natural; exclamation marks belong to announcements rather than every benefit.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct promise or a compact twist on the reader's familiar frustration. | 4–8 words | “Your all-in-one collaborative workspace.”<br>“Enough of this sheet.”<br>“Collaboration without constraint.” |
| Supporting line | Name who benefits and how the tool changes a recognizable workday. | 12–35 words | “[Brand] brings teams and tools together for a more organized work day.” |
| Section headline | Outcome-first language, sometimes two clipped clauses or a metaphor borrowed from the problem. | 4–10 words | “Get instant insights. Make smarter decisions.”<br>“Apps that work your way, not theirs.”<br>“Pricing that builds bridges, not barriers.” |
| Primary action | Plain verb plus immediate next step; free is included only when true. | 2–5 words | “Get started for free”<br>“Get the template” |
| Value explanation | Dismiss the expected complication in clipped clauses, then state the practical benefit. | 15–30 words | “Not a separate add-on. Not a separate license. Empowering teams to reduce busywork and maximize their impact.” |

**Words and phrasing to use:** your team; work your way; get started; busywork; together; build; connect; ready-to-run; no need to start from scratch

**Avoid:** revolutionary paradigm; unprecedented synergy; enterprise-grade everything; magic without explanation; fear-based competitive insults

**Rules:**

- Make every headline point to a user outcome, with a concrete mechanism in the support line.
- Use playful wording once per thought, then return to clear task language.
- Let labels name real tasks or artifacts rather than abstract pillars.
- Keep comparison language pointed but explain the constraint and the useful alternative.
- Use numbers as proof only when they can be substantiated.

## Do's and Don'ts

### Do

- Keep the main display at 72px/1 and -0.045em tracking at desktop.
- Align hero copy, chapter headings and footer content to the same 1136px usable span.
- Use 72px top and bottom padding for ordinary chapters and 96px between paired feature columns.
- Include a hard-edged product frame with a 2px dark outline and 8px offset shadow.
- Keep large conversion buttons at 62px height with 12px corners, and chapter actions at 38px with 8px corners.
- Set explanation paragraphs in warm gray at 20px/30px; use 16px/24px for card descriptions.
- Pair a peach-highlighted bold statement with a contrasting light-serif customer proof panel somewhere in the page.
- End with the cream footer, preserving 24px column gaps and the separated utility row.

### Don't

- Do not make all corners identical: 8px cards, 9.6px interface previews and 12px large actions have different roles.
- Do not use orange as the default CTA fill; primary actions are near-black.
- Do not set bold section headings in the body sans substitute when the compact display face is available.
- Do not spread peach emphasis over whole paragraphs; it belongs to a short inline phrase.
- Do not turn the soft gray supporting copy into high-contrast black throughout; it collapses the headline hierarchy.
- Do not replace the white explanatory middle with alternating saturated rainbow bands.
- Do not apply the editorial mustard-and-green sculpture treatment to ordinary product chapters.
- Do not use the large 72px conversion line at the top of every small capability pair.

## Motion and responsive

### Motion

**Observed:**

- Primary and compact actions declare 0.05s transitions, hover enlargement to scale(1.02) and active scale(1); secondary actions compress to scale(0.98) when active.
- Resource cards declare 0.2s transitions; integration tiles declare box-shadow 0.2s with ease timing.
- The immersive explainer presents changing full-viewport messages, tile arrangements and a slim progress indicator.

**Transfer:**

- Keep action motion small enough that the rounded rectangle remains visually stable.
- Use staged scroll storytelling only for a real problem-to-order argument, not as a default animation for every capability chapter.

**Unknown:**

- Exact scroll-scene timing, trajectories, activation thresholds and video playback choreography are unspecified.
- No expanded FAQ state or complete keyboard-focus design is established.

### Responsive

**Observed:**

- Declared CSS includes 768px, 1024px and 1440px width breakpoints among many component-specific thresholds.
- The footer uses repeat(auto-fit, minmax(150px, 1fr)); paired actions allow wrapping.

**Transfer:**

- On narrow screens, preserve the text-before-working-object hierarchy and stack feature pairs rather than shrinking 520px media into unreadable columns.
- Allow the six-column footer to reflow using its 150px minimum, and retain the warm directory surface.
- Keep the product frame's dark offset edge visible when its width contracts; fit whole task examples instead of clipping essential content.

**Unknown:**

- Mobile headline sizes, exact navigation collapse and breakpoint-specific layout changes are not established. These transfer rules are recommendations, not measured mobile behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
