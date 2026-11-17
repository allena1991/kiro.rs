# Jitter — bold type, sticker energy

## Overview

An airy, mostly white creative-software style with densely fitted grotesk headlines and small, friendly interface labels. Lilac, electric cyan and acid yellow punctuate pale gray demonstration stages, while expressive sticker lettering brings a handmade counterpoint to the polished product imagery. It suits tools that promise both serious capability and creative freedom, with a sparse opening and increasingly detailed capability chapters.

### Essentials

- Headlines feel like compact typographic objects: TWK Lausanne at 80px/0.95, weight 800, -0.03em tracking for the main display; section statements use 72px/0.95 with -3.2px tracking.
- The opening sells through type rather than a dashboard: centered two-line black promise, small announcement capsule, one lilac 60px-high action, then a fine-rule proof line and monochrome logo row within the first 900px.
- Soft controls meet hard stages: actions have 50px radii; the default feature grid has square pale-gray 420px-wide panels, while emphatic stacked cards and quick links have 40px corners.
- Color arrives in concentrated islands: white dominates the marketing canvas, #f2f1f3 backs demonstrations, lilac and cyan fill selected cards, and #f5ff63 marks short actions and novelty labels rather than washing the whole page.
- Product evidence is art-directed, not dumped: 320×267px detail scenes sit inside 420px panels; larger 576×360px demonstrations float with deep soft shadows inside an 860px-wide stage. Use a designed output sample if no interface exists.
- Playful lettering interrupts the system: include an outlined sticker-word accent or a compact sticker emblem, set against heavy black type or the black closing field; a simple custom SVG letter collage is the fallback.
- The ending has a second act: a pale-gray closing call and link directory ends in 80px bottom corners over a black field containing a colorful emblem and a 40px white newsletter heading.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lilac action | `#b593ff` | `--color-lilac-action` | action | Default opening action. |
| Vivid lilac | `#a981ff` | `--color-violet` | surface, accent | Emphatic stacked and carousel cards. |
| Lavender panel | `#cab3f8` | `--color-lavender` | surface | Related-content tile. |
| Aubergine | `#17082c` | `--color-deep-purple` | text, background | Text on lilac quick links; full dark canvas only for customer directories. |
| Lilac wash | `#f2ecfd` | `--color-lavender-wash` | surface | Lighter companion tile. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric cyan | `#01b2fd` | `--color-cyan` | surface, accent | Selected large proof cards and playful graphic details. |
| Statistic violet | `#711de2` | `--color-gradient-violet` | text | Bottom of the oversize statistic gradient. |
| Acid yellow | `#f5ff63` | `--color-acid` | action, accent | Newsletter submit, proof actions and small novelty markers. |
| Statistic plum | `#140726` | `--color-gradient-dark` | text | Top of the oversize statistic gradient. |
| Ice blue | `#e6f4ff` | `--color-ice` | surface | Pale companion card in the horizontal capability rail. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Closing black | `#000000` | `--color-black` | background | Newsletter reveal field. |
| Warm black ink | `#19171c` | `--color-ink` | text, action | Main text and dark buttons. |
| Charcoal field | `#2d2933` | `--color-field` | surface | Newsletter email input on black. |
| Secondary gray | `#6e6e73` | `--color-muted` | text | Card descriptions and secondary explanation. |
| Tertiary gray | `#97979b` | `--color-faint` | text | Speaker role, inactive information and small-print hierarchy. |
| Fine gray rule | `#d7d7db` | `--color-rule` | border, text | Comparison dividers and unrevealed words in the large reading passage. |
| Soft edge | `#e5e4e7` | `--color-edge` | border, surface | Speaker plates, neutral related-content tile and billing switch track. |
| Pale gray stage | `#f2f1f3` | `--color-stage` | surface, background, border | Demonstration panels, labels and closing shell; full canvas for pricing. |
| White canvas | `#ffffff` | `--color-canvas` | background, text, surface | Default page, title-strip backing and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| customer directories | Translucent purple track | `#2e213f` | `--color-filter-wash` | surface | Visible result of white at 10% over aubergine. |
| pricing pages | Plan blue | `#50b8ff` | `--color-plan-blue` | action | Entry-plan action. |

## Typography

- **TWK Lausanne** — Headlines, capsule labels, card titles and button text. Dense modern grotesk with compact counters and emphatic heavy cuts. If unavailable, use **Inter Tight**. Use weights 600–800 and preserve the tight display tracking. Font stack: "TWK Lausanne", "Inter Tight", Arial, sans-serif.
- **Inter** — Paragraphs, navigation, descriptions and speaker metadata. Neutral, highly legible sans; regular paragraphs with selective semibold emphasis. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat | TWK Lausanne | 800 | 200px | 1.5 | -0.032em | Single oversize multiplier in a vivid proof card. |
| display | TWK Lausanne | 800 | 80px | 0.95 | -0.03em | Opening promise and closing call. |
| heading-lg | TWK Lausanne | 800 | 72px | 0.95 | -0.0444em | Centered capability chapter headings. |
| quote | TWK Lausanne | 750 | 72px | 1 | -0.04em | Monumental short testimonials with expressive word inserts. |
| heading | TWK Lausanne | 800 | 48px | 1 | -0.04em | Split capability leads and secondary section titles. |
| proof-heading | TWK Lausanne | 800 | 48px | 0.85 | -0.04em | Tightly stacked heading inside the illustrated proof panel. |
| reading-statement | TWK Lausanne | 800 | 40px | 1 | -0.0375em | Large word-by-word reveal passage. |
| newsletter-heading | TWK Lausanne | 800 | 40px | 1 | -0.04em | White heading beside the closing emblem. |
| tile-heading | TWK Lausanne | 800 | 36px | 1 | -0.0444em | Related-content quick-link titles. |
| eyebrow | TWK Lausanne | 600 | 20px | 1.2 | -0.02em | Sentence-case capsule above a chapter. |
| card-title | TWK Lausanne | 600 | 20px | 1 | -0.01em | Feature titles on white rectangular strips. |
| button | TWK Lausanne | 600 | 20px | 1.38 | -0.02em | Main 60px actions. |
| body-lead | Inter | 400 | 18px | 1.5 | -0.022em | Section introductions and long-form narrative. |
| button-small | TWK Lausanne | 600 | 18px | 1 | -0.02em | Compact 52px actions. |
| body | Inter | 400 | 16px | 1.5 | -0.02em | Muted capability descriptions. |
| nav | Inter | 600 | 16px | 1.5 | -0.022em | Top navigation links. |
| footer-link | Inter | 400 | 16px | 1.5 | -0.022em | Directory links. |
| speaker | Inter | 600 | 16px | 1.25 | -0.02em | Two-line speaker metadata. |
| announcement | Inter | 400 | 15px | 1.2 | -0.021em | Compact release announcement. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case studies | story-title | TWK Lausanne | 800 | 72px | 0.95 | -0.04em | Left-aligned multi-line editorial opening. |
| pricing pages | price | TWK Lausanne | 800 | 42px | 0.95 | -0.04em | Plan price numerals. |
| case studies | story-quote | TWK Lausanne | 750 | 36px | 1 | -0.04em | Longer quotations between narrative chapters. |
| pricing pages | faq | Inter | 600 | 20px | 1.5 | normal | Accordion questions. |

**Notes:**

- Use heavy grotesk display text with unusually tight leading; the 48px proof-panel title compresses further to 0.85 while ordinary 48px section headings stay at 1.
- Eyebrows are not tiny uppercase metadata: they are 20px sentence-case labels. Card titles remain 20px even beneath very large imagery.
- Paragraphs use regular Inter; emphasize the opening benefit clause rather than bolding entire paragraphs.

## Layout

**Density:** Airy around chapters, compact within captions; narrow centered content produces long white margins and concentrated visual islands.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Inline icon spacing and directory row separation. |
| 12px | Card title-to-description gap. |
| 20px | Panel grid gaps and capsule horizontal insets. |
| 30px | Heading-to-support and support-to-action spacing. |
| 40px | Proof action separation and newsletter heading-to-form gap. |
| 50px | Feature panel side inset and media-to-copy gap. |
| 60px | Split lead-to-gallery separation. |
| 80px | Space beneath centered chapter headers. |
| 120px | Closing call-to-directory separation. |
| 160px | Closing shell top padding. |
| 180px | Major chapter and quote breathing room. |
| 200px | Large section separation. |

### Containers and grids

- **main container**: max width 860px · side padding 20px. Centered marketing column; at desktop, extensive white margins frame the content.
- **feature grid**: max width 860px · 2 columns · gap 20px. Two 420px-wide demonstration panels.
- **detail grid**: max width 860px · 3 columns · gap 63px. Three compact unboxed icon-and-copy cells, about 245px wide.
- **quote width**: max width 740px. Short large testimonials centered in the main column.
- **card rail**: gap 20px. 460px-wide cards in an overflowing horizontal rail aligned with the main container.
- **reading column** (only for case studies): max width 508px. Long-form narrative inside the wider editorial stage.
- **editorial media** (only for case studies): max width 684px. Media and centered quotations wider than prose.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 50px |
|  | emphatic cards | 40px |
|  | default feature panels | 0px |
|  | closing shell bottom corners | 80px |
|  | portraits | 50% |
| product feature catalogs | feature panels | 40px |
| pricing pages | plan cards | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating demonstration | `rgba(0, 0, 0, 0.01) 0px 197px 79px 0px, rgba(0, 0, 0, 0.03) 0px 111px 67px 0px, rgba(0, 0, 0, 0.05) 0px 49px 49px 0px, rgba(0, 0, 0, 0.05) 0px 12px 27px 0px` | Isolated product scene, not every panel. |
| stacked card | `rgba(0, 0, 0, 0) 0px 187px 52px 0px, rgba(0, 0, 0, 0.01) 0px 119px 48px 0px, rgba(0, 0, 0, 0.05) 0px 67px 40px 0px, rgba(0, 0, 0, 0.09) 0px 30px 30px 0px, rgba(0, 0, 0, 0.1) 0px 7px 16px 0px` | Vivid overlapping capability cards. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #19171c`

#### Demonstration stage · level 1

**Use:** Feature panels and large media backing.

**CSS:** `background: #f2f1f3; border-radius: 0px`

**Observed:** Flat, borderless backing around a smaller scene. Product catalogs use 40px corners; the ordinary marketing grid remains square.

**Transfer:** Let the output or interface be the colorful object, not the surrounding canvas.

#### Vivid proof card · level 2

**Use:** Stacked capability and statistic cards.

**CSS:** `background: #a981ff; border-radius: 40px; overflow: hidden`

**Observed:** Cyan and pale-gray companions share the same silhouette. White strip headings separate dark text from saturated fields.

**Transfer:** Choose a small set of high-value capabilities for this more theatrical treatment.

#### Closing shell · level 1

**Use:** Closing call and full link directory above the black ending.

**CSS:** `background: #f2f1f3; border-radius: 0px 0px 80px 80px; padding: 160px 20px 98px; position: relative; overflow: hidden`

**Observed:** A broad light sheet conceals and then yields to the black newsletter field.

**Transfer:** Keep call, directory and legal metadata on the same sheet.

#### Newsletter field · level 0

**Use:** Final dark scene.

**CSS:** `background: #000000; color: #ffffff; padding: 220px 20px 240px`

**Observed:** Colorful emblem at left, compact form at right; much darker than the rest of the page.

#### Directory night · level 0

**Only for:** customer directories

**Use:** Full-page proof gallery and its closing directory.

**CSS:** `background: #17082c; color: #ffffff`

**Observed:** White logos sit directly on aubergine; featured story tiles have saturated independent backdrops.

#### Filter track · level 1

**Only for:** customer directories

**Use:** Category switch.

**CSS:** `background: rgba(255, 255, 255, 0.1); border-radius: 60px; padding: 5px`

**Observed:** White active capsule sits inside a translucent purple track.

## Components

### Primary button

**Use:** Opening conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #b593ff; color: #19171c; border-radius: 50px; height: 60px; padding: 8px 50px`

**Text style:** `button` — TWK Lausanne 600 · 20px/1.38 · tracking -0.02em

**Observed:** A single centered action beneath the promise; no competing outlined button.

### Dark button

**Use:** Capability exploration and closing conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #19171c; color: #ffffff; border-radius: 50px; height: 60px; padding: 8px 50px`

**Text style:** `button` — TWK Lausanne 600 · 20px/1.38 · tracking -0.02em

**Observed:** Compact header signup uses the same dark silhouette at 52px high with smaller text.

### Acid button

**Use:** Proof destination and newsletter submission.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #f5ff63; color: #19171c; border-radius: 50px; height: 52px; padding: 8px 40px`

**Text style:** `button-small` — TWK Lausanne 600 · 18px/1 · tracking -0.02em

**Observed:** Newsletter version extends over the right end of the input and uses 50px horizontal padding.

### Navigation link

**Use:** Primary header navigation.

**CSS:** `display: flex; align-items: center; padding: 0px 20px; color: #19171c`

**Text style:** `nav` — Inter 600 · 16px/1.5 · tracking -0.022em

**Observed:** Wordmark left, four short destination labels, login and dark signup right. Header is fixed; deeper scrolling reduces it to signup and a circular menu control. Dark-directory variant reverses the text and signup colors.

### Announcement capsule

**Use:** Short release or product-news hook above the promise.

**CSS:** `display: flex; align-items: center; background: #f2f1f3; border-radius: 40px; padding: 7px 20px`

**Text style:** `announcement` — Inter 400 · 15px/1.2 · tracking -0.021em

**Observed:** One short bold lead-in, regular explanation and a colored learn-more tail.

### Feature panel

**Use:** Default capability demonstration.

**CSS:** `display: flex; flex-direction: column; gap: 50px; background: #f2f1f3; padding-bottom: 10px; border-radius: 0px`

**Text style:** `card-title` — TWK Lausanne 600 · 20px/1 · tracking -0.01em

**Observed:** Media above text; 50px side insets produce a 320px content width within a 420px panel. Title uses a white strip with 3px vertical and 5px horizontal padding, then 12px to muted body copy. Rounded 40px version belongs to product catalogs.

**Transfer:** Show one isolated behavior, not an entire application in every card.

### Quick link tile

**Use:** Related destinations and next-step choices.

**CSS:** `display: flex; background: #cab3f8; color: #17082c; border-radius: 40px`

**Text style:** `tile-heading` — TWK Lausanne 800 · 36px/1 · tracking -0.0444em

**Observed:** 420×272px tile with an inset content stack: capsule, two-line heading, then a small arrow link. Inner padding is 50px with 60px at right; companion uses the lilac wash.

**States:** Declared: hover transform scale(0.96); focus-visible not specified.

**Transfer:** Keep the whole tile clickable and the destination benefit short.

### Speaker plate

**Use:** Attribution beneath a quotation.

**CSS:** `display: flex; align-items: center; gap: 20px; border: 1px solid #e5e4e7; padding: 20px 30px`

**Text style:** `speaker` — Inter 600 · 16px/1.25 · tracking -0.02em

**Observed:** Small circular 44px portrait to the left of two lines: dark name and gray role. The rectangular plate contrasts with the rounded action system.

### Footer link

**Use:** Link-directory rows.

**CSS:** `display: inline-flex; align-items: center; gap: 5px; padding: 5px 0px; color: #19171c; transition: opacity 0.2s cubic-bezier(0.25, 0.46, 0.45, 0.94)`

**Text style:** `footer-link` — Inter 400 · 16px/1.5 · tracking -0.022em

**Observed:** Links are stacked closely beneath heavier group names; selected external destinations append a small northeast arrow.

**States:** Declared: hover opacity 0.54; focus-visible not specified.

### Newsletter input

**Use:** Email entry in the closing black field.

**CSS:** `background: #2d2933; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 0px 50px 50px 0px; height: 52px; width: 440px; padding: 13px 210px 13px 24px`

**Observed:** Square left edge, pill right edge covered by the Acid button. The button is 203px wide and sits in the same row.

**Transfer:** Preserve the joined silhouette and room for entered text.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side subscription offers.

**CSS:** `display: flex; flex-direction: column; gap: 30px; background: #ffffff; border-radius: 20px; padding: 40px 30px`

**Text style:** `price` — TWK Lausanne 800 · 42px/0.95 · tracking -0.04em

**Observed:** Two-column grid of 420px cards: tinted plan badge, price plus small billing unit, short audience description, full-width 60px action, checkmarked feature list. Actions distinguish tiers with blue, acid yellow, lilac and orange.

**Transfer:** Use genuine tier differences; keep pricing easier to scan than the feature catalog.

### FAQ row

**Only for:** pricing pages

**Use:** Objection handling.

**CSS:** `padding: 32px 0px; border-bottom: 1px solid #d7d7db`

**Text style:** `faq` — Inter 600 · 20px/1.5

**Observed:** Full 860px column, question left and small down chevron at right. Wrapped questions increase the row height.

## Imagery and graphics

### Isolated product scenes

**Use:** Capability panels and major demonstrations.

**Observed:** Interface fragments, editable poster samples, export windows and selection handles occupy smaller rectangles inside pale-gray stages. Scenes use white or pastel backing, with lilac and cyan often inside the demonstration. Large scenes are 576×360px in an 860px-wide stage; detail scenes are usually 320×267px.

**Transfer:** Compose one legible feature interaction on a clean backing. If an interface is unavailable, use a finished output alongside a small editable control fragment; avoid generic device mockups.

### Expressive sticker lettering

**Use:** A signature counterpoint within testimonials and the closing emblem.

**Observed:** A word interrupts a heavy black quotation with irregular letter shapes, thick outlines and cyan glow, or acid lettering with purple outlines. The closing scene uses a compact animated stack of colorful wordmark stickers against black.

**Transfer:** Create a custom word accent or emblem in the new product's vocabulary, retaining the cutout silhouette and brash color contrast.

**Build:** Use SVG text converted to irregular paths or separately rotated letters. Give the group a thick dark contour and an offset white contour; add a cyan or lilac outer contour using duplicated paths or drop-shadow layers. Keep quote inserts roughly the surrounding cap height, about 245×76px for a short word. For the closing emblem, overlap 3–5 rotated capsule or scalloped outlines in cyan, lilac, acid and white around a dark central label within a 344×164px stage.

### Friendly geometric cutout

**Use:** Illustrated proof panel.

**Observed:** Three smiling geometric figures with skinny limbs, thick black lines and a white sticker edge sit beside tightly stacked proof copy. Cyan, purple and acid bodies are deliberately flat and hand-drawn, not glossy 3D.

**Transfer:** Use a compact symbolic cluster expressing collaboration or the outcome, with comparable visual weight to a 280×182px illustration.

**Build:** Draw a square, circle and triangle in SVG with slightly uneven contours, black eyes and smiles, narrow bent limbs and a shared white outer sticker outline. Use cyan, vivid lilac and acid fills; overlap the shapes and keep the surrounding stage pale gray.

### Output gallery rail

**Use:** Visual inspiration and breadth-of-use proof.

**Observed:** Oversized rounded pale-gray cards carry posters, photographs and motion compositions with soft object shadows. The rail bleeds beyond both sides of the main column; a dark oversized capsule action overlays it.

**Transfer:** Show diverse outputs from the new product, each with a distinct composition but consistent neutral backing.

### Monochrome logo systems

**Use:** Opening proof strip and customer directory.

**Observed:** Opening logos are black with balanced optical sizes. The directory uses white logos in spacious three-column cells; featured stories use larger centered marks on 420×280px saturated rounded tiles.

**Transfer:** Balance marks optically rather than forcing identical widths; use actual available proof and keep decorative logos out of narrative paragraphs.

### Editorial work samples

**Only for:** case studies

**Use:** Between narrative paragraphs and quotations.

**Observed:** Wider 684px media stages show poster sets, typography experiments, fashion imagery and website compositions. Full-color work remains intact within pale neutral backing, with occasional saturated project-specific fields.

**Transfer:** Use the subject's real work; let each project have its own palette while the surrounding editorial typography stays consistent.

### Icons

**Observed:** Mostly simple 22–24px utility symbols, black on light surfaces. Outline feature icons use 2px rounded strokes; filled symbols and small directional arrows coexist without enclosing boxes.

**Transfer:** Choose spare utility icons at 22–24px and align them with the short title, not as large decorative badges.

## Section recipes

How recurring sections are built.

### First screen: Type-led opening

**Observed:** White canvas behind a centered 860px composition. The fixed header spans the same main column, with wordmark and navigation at left and account actions at right. A small Announcement capsule sits above a heavy, centered two-line black promise about two thirds of the column width, using the display recipe. The typographic object is the main image: no giant dashboard competes with it. A single Primary button follows with about 30px separation. A restrained social-proof sentence is flanked by thin rules, with a row of six monochrome marks below. Within the first 900px the navigation, announcement, full promise, action and logo strip are visible; the output gallery begins below the opening.

**Transfer:** Make a brief two-line promise with equivalent typographic mass and one clear action; no source animation is necessary. Product-detail openings add an 18px support paragraph below an 80px heading. Pricing opens on pale gray with a 72px title, short reassurance and billing switch. Case studies open left-aligned with a 72px story title, short profile, tags and an author band. Customer directories open on aubergine with white 80px type and story tiles.

**Avoid:** Do not turn the first screen into a split dashboard hero, an enormous illustration, or a row of equal competing buttons.

**Text style:** `display` — TWK Lausanne 800 · 80px/0.95 · tracking -0.03em

### Chapter heading stack

**Observed:** Sentence-case 20px capsule above a 72px centered title; 30px stack gaps, then an 18px introduction in a 500px maximum text width. A key benefit clause can be semibold. About 80px separates this header from the next visual group.

**Transfer:** Group capabilities under an outcome, using a short chapter label rather than a technical taxonomy.

**Text style:** `heading-lg` — TWK Lausanne 800 · 72px/0.95 · tracking -0.0444em

### Progressive reading statement

**Observed:** A left-aligned 40px heavy passage occupies a narrow area inside the main column. Words transition from pale gray to black as the reader progresses; the finished state reads as one compact manifesto.

**Transfer:** Use a concise product thesis that benefits from gradual emphasis; provide the whole sentence as readable text.

**Text style:** `reading-statement` — TWK Lausanne 800 · 40px/1 · tracking -0.0375em

### Stacked color proof

**Observed:** A centered 460px-wide sequence of 580px-tall Vivid proof cards overlaps while scrolling. Copy is inset 50px with a white title strip and white description on saturated cards. One card centers a 200px gradient multiplier instead of interface art.

**Transfer:** Use this concentrated theatrical device for an important set of outcomes. Replace the multiplier with a substantiated statistic or a compact product-output symbol rather than inventing a claim.

**Text style:** `stat` — TWK Lausanne 800 · 200px/1.5 · tracking -0.032em

### Capability panel matrix

**Observed:** Feature panels repeat in two columns separated by 20px. Default square panels form a disciplined grid; product catalogs use 40px rounded corners. Each scene sits above a title strip and muted 16px description. Unboxed three-column icon details provide a lighter follow-up.

**Transfer:** Mix a few visual explanations with compact supporting capabilities; keep every card about one behavior.

### Oversize quote interruption

**Observed:** A 740px-wide centered quote uses 72px type with an expressive word insert; Speaker plate sits 50px below. Broad 180px outer breathing room gives it the status of a chapter break. Case-study quotations reduce to 36px within 686px.

**Transfer:** Use a short genuine quotation and emphasize one meaningful word through the sticker device rather than adding many decorative elements.

**Text style:** `quote` — TWK Lausanne 750 · 72px/1 · tracking -0.04em

### Split lead and output grid

**Observed:** A 48px left-aligned heading and capsule face an 18px explanation to the right. A 60px gap leads into a narrower two-column media grid with 332px-wide tall scenes and copy below.

**Transfer:** Use for scaling or workflow outcomes that need examples rather than a large central hero.

**Text style:** `heading` — TWK Lausanne 800 · 48px/1 · tracking -0.04em

### Proof and onward bento

**Observed:** An 860px pale stage pairs a tightly stacked 48px proof heading, small globe and Acid button on the left with Friendly geometric cutout on the right. Below, two Quick link tiles sit 20px apart in lavender and lilac wash.

**Transfer:** Pair a trust signal with expressive illustration, then provide two different useful next destinations.

**Text style:** `proof-heading` — TWK Lausanne 800 · 48px/0.85 · tracking -0.04em

### Pricing decision system

**Observed:** Pale-gray canvas, centered title and reassurance, 540×70px rounded billing track, then a two-column Plan card grid. A wider white enterprise offer follows. The comparison uses a wide feature-label column and five narrow value columns, 96px rows and 1px gray rules. Proof with colorful avatar circles precedes FAQ rows and a white special-program banner.

**Transfer:** Separate the quick buying decision from exhaustive comparison; keep tier headers aligned across every category.

### Editorial alternating widths

**Observed:** A 790px story title leads to profile copy, small tags, a pale author band and 860px lead media. Narrative alternates 508px prose, 684px work samples and 686px centered quotes. Sections use 48px headings; results add smaller subheadings. The ending profiles the subject with logo, description and social links, then two Quick link tiles.

**Transfer:** Let interview proof and concrete work interrupt the prose at regular intervals without turning every paragraph into a card.

### Two-act closing

**Observed:** Closing shell begins with an 80px centered invitation, 18px reassurance and Dark button; 120px below comes a multi-column link directory, then copyright and small legal text. Its 80px bottom corners expose Newsletter field underneath. The final black scene pairs Expressive sticker lettering with a 430px-wide white heading and joined Newsletter input plus Acid button. Customer directories retain aubergine, inverse text and acid closing action, and end with their link directory rather than the newsletter scene.

**Transfer:** Retain the visual reveal and compact creative emblem for ordinary marketing pages. For a directory-only page, use the dark variant consistently instead of inserting a disconnected light footer.

**Text style:** `display` — TWK Lausanne 800 · 80px/0.95 · tracking -0.03em

## Page flow

**Storyline:** Promise → visible output → capability outcomes → human proof → deeper detail → next destinations → low-friction closing call and expressive final scene.

### Broad product marketing landing page

1. **Promise** — Compact type-led opening with one action and monochrome proof strip.
2. **Product demonstration** — Output gallery, progressive reading statement and floating product scene.
3. **Capability chapters** — Stacked colored cards, centered chapter headers, panel grids and a lighter icon matrix.
4. **Social proof** — Oversize quotes interrupt detail, followed by an illustrated proof panel and onward tiles.
5. **Closing call** — Light rounded directory sheet reveals the black newsletter scene.

**Transfer:** Alternate typographic pauses with isolated product scenes; preserve the signature devices without fixing their count or order.

### Detailed product capability catalog

1. **Promise** — Centered 80px headline, release capsule, support paragraph and lilac action.
2. **Workflow demonstration** — Repeated chapter stacks introduce import, creation, teamwork and output examples through rounded two-column panels and icon details.
3. **Social proof** — Illustrated proof panel and companion quick links.
4. **Closing call** — Shared light shell and black newsletter reveal.

**Transfer:** Organize details into the new product's natural workflow rather than reproducing the original feature list.

### Customer proof directory

1. **Promise** — White 80px centered title and support on aubergine.
2. **Featured proof** — Two-column gallery of rounded saturated story tiles with centered marks.
3. **Breadth of proof** — 48px trust statement, category capsule switch and spacious three-column white-logo field.
4. **Closing call** — Inverse invitation and acid action continue into the dark link directory and legal ending.

**Transfer:** Use the scoped night palette for an intentionally immersive proof index.

### Long-form customer story

1. **Context** — Left-aligned story title, short profile, tags, author band and lead work sample.
2. **Problem and change** — Large reading statement followed by narrow narrative and centered quotes.
3. **Demonstrated outcomes** — Alternating work samples, use-case chapters and results paragraphs.
4. **Next destinations** — Subject profile, social links and two related tiles.
5. **Closing call** — Shared closing shell and black newsletter scene.

**Transfer:** Explain a real before-and-after through the subject's words and work, not unsupported numerical claims.

### Pricing and purchase decision

1. **Reassurance** — Simple centered title, cancel-or-switch support and billing switch.
2. **Pricing** — Two-column offers plus an enterprise card.
3. **Detailed comparison** — Grouped comparison rows with aligned plan columns.
4. **Objection handling** — Human proof, logo strip, question rows and special-program banner.
5. **Closing call** — Shared rounded directory sheet and black newsletter ending.

**Transfer:** Keep selection quick at the top and put depth below; use accent actions to distinguish tiers.

## Writing

Direct, enabling and creatively optimistic. Capability claims are concrete and workflow-oriented, with occasional playful wordplay rather than a corporate sales register.

**Do not copy:** Do not reuse the Jitter name, wordmark artwork, customer identities or logos, quotations, usage counts, template counts, performance multipliers, prices or product-specific claims. Replace them with the new product's authentic content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to you and your team. Name the product as the actor when explaining a workflow; keep we mostly out of benefit copy.
- **Rhythm:** Short, compact headlines contrast with one or two explanatory sentences. Use sentence case, periods in punchy headline fragments and occasional em dashes; avoid exclamatory hype.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Direct outcome phrase or a sequence of terse verbs. | 3–8 words | “Design. Animate. Deliver.” |
| Chapter heading | Benefit-led phrase with a slight conversational twist. | 4–9 words | “Make your team effort effortless”<br>“Never start from scratch again” |
| Supporting line | Name the capability, then the everyday benefit. | 1–2 sentences | “No download, no install, no waiting. Start creating instantly.” |
| Primary action | Verb plus low-friction condition or clear destination. | 3–5 words | “Get started for free”<br>“Explore all the features” |
| Card title | Concrete ability or outcome, not an abstract category. | 2–7 words | “One home for all your assets”<br>“Refine with full control” |
| Objection handling | Actual user question in first person. | 5–14 words | “Can I use [Brand] for free?” |

**Words and phrasing to use:** create; fine-tune; polished; instantly; your team; in one place; full control; ready to; get started; on-brand

**Avoid:** revolutionary ecosystem; unparalleled excellence; synergize; disrupt everything; enterprise-grade solutions for tomorrow

**Rules:**

- Explain how a capability changes the work, not just that the capability exists.
- Use one clear benefit per feature caption.
- Let a short semibold clause carry the key promise inside a regular supporting paragraph.
- Keep closing reassurance specific to actual friction removed.

## Do's and Don'ts

### Do

- Keep main display type at 80px/0.95 with weight 800 and -0.03em tracking.
- Center ordinary marketing content within 860px and use 20px panel gutters.
- Use 50px side insets to stage media and copy inside 420px feature panels.
- Reserve the strongest lilac and cyan fills for selected proof islands.
- Use 60px-high main actions and 52px compact actions with 50px corners.
- Give major quotations 180px of breathing room and a separate rectangular speaker plate.
- Keep the 80px rounded bottom edge of the closing sheet legible against black.
- Include the sticker-letter counterpoint in an otherwise disciplined typographic system.

### Don't

- Do not substitute thin geometric display type for the heavy 800-weight grotesk.
- Do not round every default marketing panel to 40px; that treatment belongs to emphasis cards and the product catalog.
- Do not make captions as heavy or as dark as the headline; use 16px regular secondary gray.
- Do not put shadows on the whole grid; reserve deep layered shadows for floating scenes and stacked proof.
- Do not enlarge utility icons into 64px feature badges; keep them around 22–24px.
- Do not use acid yellow as a full ordinary page background; its core role is concentrated action emphasis.
- Do not turn the speaker plate into a pill; its 1px rectangular outline is a deliberate contrast.
- Do not stop the ordinary marketing ending at a legal line; the black creative newsletter scene is part of the closing identity.

## Motion and responsive

### Motion

**Observed:**

- Directory links declare opacity 0.2s cubic-bezier(0.25, 0.46, 0.45, 0.94), reaching 0.54 on hover.
- Quick-link tiles declare scale(0.96) on hover with transform 0.4s cubic-bezier(0.22, 0.73, 0.3, 1.39).
- Stacked proof cards use sticky positioning; reading passages reveal words progressively; the light closing shell reveals a sticky dark newsletter scene.
- Navigation links declare transform 0.8s cubic-bezier(0.33, 1.42, 0.05, 0.96).

**Transfer:**

- Make motion reinforce the physical metaphor: overlapping cards, individual-word emphasis and a sheet moving away from the final field.
- Keep a stable readable headline and product still as the resting state; preserve the closing composition when motion is unavailable.

**Unknown:**

- Exact scroll progress mappings, video loops and the full spring easing on button interiors are not specified.

### Responsive

**Observed:**

- Styles declare width breakpoints at 640px, 768px, 1024px, 1280px and 1536px.

**Transfer:**

- On narrow layouts, retain the order of announcement, typographic promise, action and proof; reduce display size to maintain compact lines.
- Stack the two-column panels and newsletter illustration/form while keeping the sticker device and rounded closing-sheet edge.
- Allow the horizontal output rail to remain a rail rather than shrinking every sample into illegibility.

**Unknown:**

- Specific mobile type sizes, spacing and navigation states are not established. These collapse rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
