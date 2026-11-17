# Pika — cinematic creative bravado

## Overview

A warm, image-led style with the confidence of a fashion campaign and the directness of a useful creative tool. Cream backgrounds, charcoal chapters and white-on-film headlines frame richly colored portraits, surreal still lifes and tactile product scenes. Extended grotesk capitals give the promises a poster-like presence, while regular sans-serif explanations keep the experience approachable. It suits creative platforms and visually expressive products, with spacious storytelling surrounding relatively compact controls.

### Essentials

- The first impression is a campaign still, not a dashboard: nearly edge-to-edge imagery inside a 4px cream rim and 12px corners, with a white 72.3px extended headline anchored low on the left and a 340px support/action column on the right.
- Headlines change register without changing family: bold extended capitals at 72.3px/0.9 for the opening, medium 54px/1.04 with 0.01em tracking for capability chapters, and regular 27px/1.2 sentence-case editorial statements.
- Conversion controls are soft capsules against hard-edged typography: 48px tall, 9999px radius, 24px horizontal padding and 16px uppercase labels tracked 0.1em; white on film, charcoal on cream, translucent for secondary actions.
- Color lives primarily in the pictures: cream and charcoal occupy the structural page, while saturated greens, amber, blue and red appear inside media. Lavender and butter-yellow light form broad, isolated atmosphere rather than a multicolor interface.
- Proof is staged as a portfolio: a large paired image accompanies a stack of muted capability cards, alternating 832px and 372px media tiles form a 12px-gapped mosaic, and a two-row moving gallery mixes portrait and landscape formats. Use staged objects or product outcomes when people are not appropriate.
- The ending carries visual weight: dark editorial chapters give way to a charcoal footer with 17px links and 1px translucent rules, then a monumental low-contrast wordmark spanning the 1392px inner width. Recreate this device with the new product's own typographic name.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender light | `#cfc3ff` | `--color-lavender` | background, accent | Broad soft glows behind commercial proof and highlighted offers. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, action | Opening headline and primary action on photography; purchase panels. |
| Raised paper | `#fdfcfa` | `--color-paper` | surface, text, border | Plan cards, editorial titles and inverse outline borders. |
| Eggshell | `#fcfaf7` | `--color-eggshell` | text | Warm inverse body text and the source hue for translucent controls. |
| Warm cream | `#faf8f4` | `--color-canvas` | background, text | Default marketing canvas and inverse outlined-button labels. |
| Recessed cream | `#f3f1ed` | `--color-card-wash` | surface | Visible capability-card wash: near-black at 3% over warm cream. |
| Inverse secondary | `#bcbab7` | `--color-inverse-muted` | text | Eggshell at 70% over charcoal for footer links. |
| Muted warm gray | `#787875` | `--color-muted` | text | Visible secondary text on cream, using charcoal at 60% opacity. |
| Dark chapter rule | `#383837` | `--color-dark-rule` | border | Eggshell at 10% over charcoal for footer separators. |
| Soft black | `#2e2e2e` | `--color-action` | action, text | Dark capsules and capability titles. |
| Charcoal | `#222222` | `--color-charcoal` | background, border | Footer and base backing for campaign media. |
| Primary ink | `#111111` | `--color-ink` | text, background | Main text on cream and the darkest editorial chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Violet annotation | `#806eca` | `--color-violet-label` | text, accent | Small recommendation and savings labels. |
| developer-focused promotional sections | Butter-yellow light | `#fff785` | `--color-yellow` | background, accent | Center of a warm radial conversion glow. |
| developer-focused promotional sections | Pale yellow light | `#fef7ba` | `--color-yellow-fade` | background | Intermediate fade around the yellow glow. |
| developer and enterprise pages | Developer cream | `#fdf7ef` | `--color-developer-canvas` | background | Warmer canvas for text-led developer and enterprise narratives. |
| developer pages | Developer ink | `#0d0d0d` | `--color-developer-ink` | text, action, background | Text, capsules and directory footer in the developer variant. |
| pricing pages | Pricing cream | `#fcf7f0` | `--color-pricing-canvas` | background | Warm comparison-page canvas. |

## Typography

- **Telka** — Body, controls, card titles and editorial statements. An open, clean grotesk with a soft geometric feel; mostly regular and medium weights. If unavailable, use **DM Sans**. Use 400 and 500; preserve the slightly positive tracking on copy. Font stack: "Telka", "DM Sans", ui-sans-serif, system-ui, sans-serif.
- **Telka Extended** — Poster headlines and broad chapter titles. Wide grotesk with emphatic round forms and generous horizontal reach. If unavailable, use **Unbounded**. Use 400, 500 and 700; tune line breaks for the extended width rather than condensing it. Font stack: "Telka Extended", "Unbounded", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Telka Extended | 700 | 72.3px | 0.9 | normal, uppercase | fixed | White campaign headline, split into a short stack low in the opening image. |
| heading | Telka Extended | 500 | 54px | 1.04 | 0.01em, uppercase | fixed | Centered two-line capability introductions and portfolio heading. |
| card-title | Telka | 400 | 28px | 1.25 | 0.02em | fixed | Capability-list card title. |
| lead | Telka | 400 | 27px | 1.2 | normal | fixed | Editorial statements, enterprise support and contact invitation. |
| media-title | Telka Extended | 400 | 26px | 1.2 | normal | size clamp(26px, 1.67vw, 32px) | Sentence-case title over a media tile. |
| editorial-title | Telka | 500 | 24px | 1.25 | 0.02em | fixed | Article and announcement titles. |
| body | Telka | 400 | 20px | 1.25 | 0.02em | fixed | Opening support and capability descriptions. |
| footer-link | Telka | 400 | 17px | 1 | normal | fixed | Footer column headings and links; hierarchy comes from color. |
| action | Telka | 500 | 16px | 15px | 0.1em, uppercase | fixed | Main capsule labels. |
| caption | Telka | 400 | 16px | 1.35 | 0.02em | fixed | Editorial summaries and dates/categories. |
| navigation | Telka | 500 | 14px | 1.35 | 0.02em | fixed | Header links, audience tabs and compact choices. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| developer-focused manifesto pages | chapter-display | Telka Extended | 500 | 180px | 1 | 0.03em, uppercase | fixed | Monumental left-aligned or staggered chapter statements. |
| developer-focused promotional sections | closing-display | Telka Extended | 500 | 178.2px | 0.88 | 0.03em, uppercase | fixed | Two-line centered conversion statement over yellow light. |
| enterprise pages | enterprise-display | Telka Extended | 500 | 172.4px | 1 | 0.03em, uppercase | fixed | Single-line full-width enterprise title. |
| developer-focused manifesto pages | manifesto-display | Telka Extended | 500 | 139.3px | 1 | 0.03em, uppercase | fixed | Centered four-line problem-and-resolution opening. |
| enterprise pages | contact-display | Telka Extended | 500 | 108px | 1 | 0.03em, uppercase | fixed | Two stacked words opening a contact form. |
| developer-focused commercial proof | stat | Telka Extended | 400 | 96px | 1 | 0.03em, uppercase | size clamp(4rem, 6.67vw, 8rem) | Dominant numerals in a four-column value strip. |
| pricing pages | pricing-display | Telka Extended | 500 | 72px | 1 | 0.03em, uppercase | fixed | Page title and photographic purchase-band headline. |
| pricing pages | pricing-heading | Telka Extended | 500 | 48px | 1 | 0.03em, uppercase | size clamp(32px, 3.33333vw, 64px) | Comparison, selector and FAQ headings. |
| pricing pages | faq-question | Telka | 500 | 18.5px | 1.25 | 0.02em | fixed | Questions on light accordion rows. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Extended capitals are deliberately broad, not narrow or tightly tracked. The opening uses bold weight and close vertical stacking; chapter titles use medium weight and positive tracking.
- Keep long explanations in regular sans-serif. Do not carry the headline's uppercase treatment into paragraphs or ordinary card titles.
- Separate the default media-led marketing hierarchy from the much larger text-led developer variant; do not average their headline sizes.

## Layout

**Density:** Airy at the section level, compact within controls; large image fields alternate with tightly grouped labels and supporting copy.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Small gallery gutters and grouped utility controls. | fixed |
| 12px | Workflow-mosaic gutters and heading-to-action gaps inside media. | fixed |
| 16px | Core grid gutter, card-stack gaps and editorial title-to-summary spacing. | fixed |
| 24px | Page side padding, capability-card padding and image-to-title spacing. | fixed |
| 32px | Internal capability-card separation. | fixed |
| 48px | Editorial statement-to-action spacing and standalone action-strip padding. | fixed |
| 72px | Footer major groups and rules. | clamp(48px, 5vw, 96px) |
| 90px | Chapter introduction-to-content separation. | fixed |
| 108px | Main section lower padding. | clamp(80px, 7.5vw, 144px) |
| 128px | Main chapter upper padding. | clamp(96px, -256px + 26.6667vw, 256px) |
| 150px | Pricing chapter separation. | fixed |

### Containers and grids

- **page-grid**: max width 2000px · 16 columns · gap 16px · side padding 24px. Centered outer grid; at 1440px it spans 1392px. Principal content occupies the inner fourteen columns, producing a 1216px content field.
- **capability-pair**: 2 columns · gap 16px. Two 600px fields at desktop: a persistent 602px by 452px image on the left, a vertical list on the right.
- **workflow-mosaic**: 16 columns · gap 12px. Wide 832px and narrow 372px images exchange sides across two 360px-high rows.
- **news-grid**: 3 columns · gap 20px. Three 392px editorial cards inside the inner content field.
- **pricing-grid** (only for pricing pages): 4 columns · gap 16px. Four 292px-wide plans inside a 1216px field.
- **faq-pair** (only for pricing and enterprise pages): 2 columns · gap 16px. Section label on the left, 600px accordion stack on the right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsules | 9999px (pill) |
|  | campaign-frame | 12px |
|  | capability-and-media-cards | 16px |
|  | navigation | 8px |
| enterprise pages | contact-fields | 12px |
| pricing pages | recommendation-stage | 24px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | media-title-legibility | `0px 2px 4px rgba(0,0,0,0.25)` | Light text over workflow imagery. |
| pricing pages | recommendation-card | `0px 0px 0px 1px rgba(13,13,13,0.06), 0px 24px 60px -28px rgba(80,62,160,0.4)` | Single floating recommended-plan panel. |

### Surfaces

#### Cream canvas · level 0

**Use:** Default canvas between image-led sections.

**CSS:** `background: #faf8f4`

#### Recessed card · level 1

**Use:** Capability cards and low-emphasis groupings.

**CSS:** `background: rgba(13,13,13,0.03); border-radius: 16px; box-shadow: none`

**Observed:** Barely darker than the canvas; relies on shape rather than a visible outline.

**Transfer:** Use for explainer content beside a richer media field.

#### Dark editorial chapter · level 0

**Use:** Deep lower-page editorial content.

**CSS:** `background: #111111; color: #fdfcfa; border-top: 1px solid rgba(252,250,247,0.05)`

#### Charcoal footer · level 0

**Use:** Final navigation and wordmark field.

**CSS:** `background: #222222; color: #ffffff`

#### Campaign backing · level 0

**Use:** Frame underneath full-bleed photography or video.

**CSS:** `background: #222222; border-radius: 12px; overflow: hidden`

#### Lavender atmosphere · level 0

**Use:** Commercial proof backdrop.

**CSS:** `background: radial-gradient(closest-side, #cfc3ff 0%, rgba(0,0,0,0) 100%)`

**Observed:** A broad luminous patch, not a rectangular purple section.

**Transfer:** Place behind one featured offer or proof zone, keeping text black.

#### Raised paper · level 1

**Only for:** pricing pages

**Use:** Plan cards and selector panels.

**CSS:** `background: #fdfcfa; border-radius: 16px`

#### Yellow conversion light · level 0

**Only for:** developer-focused promotional sections

**Use:** Text-led conversion scene.

**CSS:** `background: radial-gradient(47.3% 47.3%, #fff785 0%, #fef7ba 50%, rgba(253,247,239,0) 100%)`

**Observed:** A 1440px square light field spills beyond the section into cream.

**Transfer:** Center behind a short monumental invitation; retain the soft falloff.

## Components

### Floating navigation

**Use:** Persistent global navigation over media and cream.

**CSS:** `height: 48px; border-radius: 8px; background: rgba(17,17,17,0.7); backdrop-filter: blur(64px); padding: 0px 32px; display: flex; gap: 20px`

**Text style:** `navigation` — Telka 500 · 14px/1.35 · tracking 0.02em

**Observed:** A centered 705px bar floats independently of the wordmark at left and login/trial capsules at right. The header sits 24px from the desktop top and sides. On cream, the navigation reads as a pale translucent bar rather than a permanent black stripe.

**Transfer:** Keep the three separate header zones; allow a lighter treatment over pale sections.

### Primary button

**Use:** Default conversion on photographic openings.

**CSS:** `height: 48px; padding: 0px 24px; border-radius: 9999px; background: #ffffff; color: #111111; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Telka 500 · 16px/15px · tracking 0.1em · uppercase

**Observed:** White capsule paired with a translucent secondary action; stacked in the opening's support column.

**States:** Declared: hover retains the flat treatment; focus-visible uses a 2px outline with 2px offset in eggshell at 60%; active scale 0.97.

### Dark button

**Use:** Default conversion on cream.

**CSS:** `height: 48px; padding: 0px 24px; border-radius: 9999px; background: #2e2e2e; color: #ffffff; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Telka 500 · 16px/15px · tracking 0.1em · uppercase

**Observed:** May end with a small up-right arrow. In plan groups the highlighted offer receives this dark button while its neighbors use a muted wash.

**States:** Declared: hover retains a flat shadowless fill; focus-visible uses a 2px outline with 2px offset in charcoal at 50%; active scale 0.97.

### Glass button

**Use:** Secondary action over rich media.

**CSS:** `height: 48px; padding: 0px 24px; border-radius: 9999px; background: rgba(252,250,247,0.1); color: #fcfaf7; backdrop-filter: blur(12px); display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Telka 500 · 16px/15px · tracking 0.1em · uppercase

**Observed:** The image remains visible through the capsule. Workflow-tile capsules use 16px blur.

**States:** Declared: hover raises the eggshell fill to 20%; focus-visible adds a 2px outline with 2px offset in eggshell at 60%; active scale 0.97.

### Outline button

**Use:** Secondary editorial action in dark chapters.

**CSS:** `height: 48px; padding: 0px 24px; border: 1px solid #fdfcfa; border-radius: 9999px; color: #faf8f4; background: transparent; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Telka 500 · 16px/15px · tracking 0.1em · uppercase

**Observed:** An outlined sibling on cream uses a charcoal edge and dark text.

**States:** Declared: hover changes the edge to white with eggshell at 5% fill; focus-visible adds a 2px outline with 2px offset; active scale 0.97.

### Capability card

**Use:** Scannable capability list beside a persistent image.

**CSS:** `padding: 24px; border-radius: 16px; background: rgba(13,13,13,0.03); display: flex; flex-direction: column; gap: 32px; align-items: flex-start`

**Text style:** `card-title` — Telka 400 · 28px/1.25 · tracking 0.02em

**Observed:** A black rounded-square icon sits at the upper left, while the title sits toward the bottom. The expanded item includes body copy; compact siblings show just the title and icon. Cards are 600px wide with 16px gaps.

**States:** Declared: focus-visible uses a 2px outline with 4px offset in charcoal at 50%; min-height transitions over 0.5s cubic-bezier(0.23, 1, 0.32, 1).

### Workflow tile

**Use:** Outcome-oriented media mosaic.

**CSS:** `border-radius: 16px; overflow: hidden; background: #111111; position: relative; height: 360px`

**Text style:** `media-title` — Telka Extended 400 · 26px/1.2

**Observed:** Image or video fills the tile. A bottom dark gradient supports a sentence-case title and Glass button, aligned left with 24px inset and 12px separation.

**Transfer:** Use a concrete product outcome as the title, with visual proof filling the tile.

### Editorial card

**Use:** Three-column lower-page stories.

**CSS:** `display: flex; flex-direction: column; gap: 24px; border-radius: 8px; color: #fdfcfa`

**Text style:** `editorial-title` — Telka 500 · 24px/1.25 · tracking 0.02em

**Observed:** A 392px by 325px image with 12px corners precedes the title, a caption-style summary and a date anchored near the base. No contrasting card shell surrounds the text.

### Footer link

**Use:** Grouped final navigation.

**CSS:** `color: rgba(252,250,247,0.7); display: inline; text-decoration: none`

**Text style:** `footer-link` — Telka 400 · 17px/1

**Observed:** Column titles use the same size in white. Link rows have 21px gaps; groups sit below a social strip and a faint rule.

**States:** Declared: hover changes text to white; focus-visible adds 8px radius and a 2px outline with 4px offset in eggshell at 60%.

### Plan card

**Only for:** pricing pages

**Use:** Comparable subscription offers.

**CSS:** `background: #fdfcfa; border: 2px solid transparent; border-radius: 16px; padding: 22px; display: flex; flex-direction: column`

**Observed:** Four equal-width plans order name, allowance, a tall breathing area, price, capsule, feature checks and a learn-more link. One highlighted plan has a lavender halftone-light texture and a dark capsule; others use pale capsules.

**Transfer:** Keep the same vertical landmarks across all offers.

### Contact field

**Only for:** enterprise pages

**Use:** Enterprise enquiry form.

**CSS:** `height: 56px; padding: 0px 24px; border: 1px solid rgba(34,34,34,0.5); border-radius: 12px; background: rgba(13,13,13,0.03)`

**Observed:** Three single-line fields stack above a taller message field. The message field is 115px high with 24px padding. The form faces a large two-line invitation.

### FAQ row

**Only for:** pricing and enterprise pages

**Use:** Final objection handling.

**CSS:** `min-height: 72px; padding: 24px 0px; background: transparent; color: #111111; display: flex; align-items: center; justify-content: space-between`

**Text style:** `faq-question` — Telka 500 · 18.5px/1.25 · tracking 0.02em

**Observed:** A 600px question column uses thin horizontal rules and a small downward chevron at the right. The enterprise version is inverse on charcoal with slightly more open line height.

**States:** Declared: hover changes text to soft black; focus-visible uses 8px radius, a 2px outline and 2px offset.

## Imagery and graphics

### Cinematic campaign still

**Use:** Dominant opening and major promotional panels.

**Observed:** A close portrait in a vivid green feather garment fills the opening against softly lit cloudy gold. The face occupies the center and upper field; typography rests on the garment below. Elsewhere a relaxed creative director, orange tulips and a hand pressing an intercom use tactile editorial detail rather than software mockups.

**Transfer:** Commission one arresting portrait, object study or product-outcome scene. Keep tactile texture, directional soft light, an uncluttered upper field and usable low-contrast regions for white text. A carefully art-directed still is the minimum equivalent when film is unavailable.

### Surreal capability tableaux

**Use:** Paired capability previews and workflow tiles.

**Observed:** A vintage handheld camera, a bird on a ladder, perfume floating in golden clouds, a key encased in ice and formally dressed people holding fruit mix familiar objects with one unexpected premise. Smooth studio backing, natural shadows and clean compositions make the surrealism feel photographed.

**Transfer:** Stage a simple object tied to the new capability with one unusual transformation. Keep one focal subject and believable material response; do not substitute a collage of interface windows.

### Portfolio filmstrip

**Use:** Visual output proof.

**Observed:** Two rows of varied-width portrait and landscape stills run past the viewport edges. Pools, fashion faces, velvet and pearls, perfume and bright gloves create a saturated but curated editorial mix. Tiles share a 286px height, 12px corners and tight gutters.

**Transfer:** Mix several kinds of real outcomes, not the same hero repeated. Use coordinated lighting and alternating close-up, object and environment views.

### Promotional film panel

**Use:** Broad mid-page conversion stage.

**Observed:** A large rounded film field combines an upper-left identity, upper-right support and dark action, with a watch control low left and pause control low right. Moving scenes include horizontally smeared blue, orange and cream color and a yellow commercial interlude.

**Transfer:** Use a short product film or a single purposeful still in the same broad composition. Reserve top areas for small supporting content; keep the central field visually dominant.

### Atmospheric light

**Use:** A signature luminous interruption behind proof or conversion.

**Observed:** Lavender glows fade into cream without a visible box. The developer conversion scene uses a large butter-yellow radial field with a pale-yellow middle and fully transparent edge.

**Transfer:** Include one soft atmospheric light field around a persuasive moment, not behind every card.

**Build:** For lavender, layer a radial gradient with #cfc3ff at center and rgba(207,195,255,0) at the edge behind content. For yellow, use the Yellow conversion light surface on a 1440px square layer centered behind the headline; clip only at the page edges. Keep falloffs broad and do not add sharp rings or neon shadows.

### Monumental wordmark

**Use:** Signature final graphic after footer navigation.

**Observed:** A low-contrast typographic logo fills a 1392px by 430px field below the copyright and a rule. Its charcoal-on-charcoal treatment reads like an embossed end title rather than another call to action.

**Transfer:** Use the new product's own name as an oversized typographic silhouette. Preserve broad proportions and low contrast even when the name has more letters.

**Build:** Render the name as SVG text or outlined lettering in a viewBox sized to its natural word proportions. Scale to the full inner footer width inside an overflow-hidden frame approximately 430px high at desktop. Use #2e2e2e on #222222; align the baseline near the frame base.

### Halftone plan light

**Only for:** pricing pages

**Use:** Featured plan and recommendation stage.

**Observed:** Lavender illumination forms a softly rising irregular mound across a near-white plan card. Fine repeating dots give the glow a printed or pixelated grain, while the card content remains crisp.

**Transfer:** Use on one selected offer only; a diffuse lavender ellipse with fine dots is the minimum version.

**Build:** Place an oversized lavender radial ellipse near the lower center behind the card content. Overlay a repeating SVG dot pattern of 1px circles on a 3px lattice at low opacity, masked by the same radial falloff. Keep the top title region near-white and avoid glowing card borders.

### Icons

**Observed:** Utility chevrons are small solid marks around 12px. Accordion controls use 16px outline icons with 1.5px round strokes. Main arrows and controls are around 20px; capability glyphs are larger white shapes on black rounded squares. Social links use compact monochrome symbols within 56px hit areas.

**Transfer:** Use simple monochrome glyphs and a consistent outline set for utility controls. Capability icons should read as app marks, not colorful decorative illustrations.

## Section recipes

How recurring sections are built.

### First screen: Campaign opening

**Observed:** A full-bleed photographic stage sits inside a 4px cream rim with 12px corners. Back to front: charcoal backing, a cover-fitted golden portrait with a vivid green garment, subtle darkening for legibility, white display type and support copy, then a fixed three-zone Floating navigation. The main subject dominates the upper two thirds. At desktop the lower-left headline occupies about two thirds of the inner content width, stacked across three lines at 72.3px/0.9, weight 700. A 340px-wide right column aligns to its top with 20px body text, then Primary button and Glass button separated by 10px. All of the headline, support and both actions are visible in the first 900px; the image scene continues below, while the capability introduction begins later.

**Transfer:** Choose one tactile outcome, portrait or staged product object strong enough to carry a near-full-screen composition. Place the promise low left and support/actions low right so imagery owns the opening. If there is no film, use one art-directed still rather than replacing this with an ordinary text-and-dashboard split. Enterprise pages instead open on cream with a nearly full-width extended title, a support/action row and a broad photograph beginning below; pricing pages use a 72px title, billing switch and four-plan row.

**Avoid:** Do not put a centered floating white card over the image, make the image a small right-hand thumbnail, or place the entire promise above a gallery of unrelated thumbnails.

**Text style:** `display` — Telka Extended 700 · 72.3px/0.9 · uppercase

### Capability introduction and paired list

**Observed:** A centered two-line heading in the heading recipe and 20px support introduce a 1216px-wide paired field after 90px breathing room. Capability card stacks sit right of a persistent 602px by 452px preview. A Dark button closes the section.

**Transfer:** Show a concise set of capabilities with the active preview beside the expanded card. Keep text short enough that imagery remains the proof.

**Text style:** `heading` — Telka Extended 500 · 54px/1.04 · tracking 0.01em · uppercase

### Outcome mosaic

**Observed:** A centered extended heading and support lead into Workflow tiles. Wide and narrow fields exchange sides across two rows, with 12px gutters and 360px tile heights. Each title and Glass button sit at the lower left.

**Transfer:** Map each tile to a distinct result the product enables, with actual outcome imagery.

**Text style:** `heading` — Telka Extended 500 · 54px/1.04 · tracking 0.01em · uppercase

### Portfolio proof

**Observed:** A left-aligned 54px uppercase heading sits opposite an Outline button and circular pause control. Two image rows bleed beyond the content width below it, using Portfolio filmstrip imagery.

**Transfer:** Use this visual proof device to convey range without writing a long feature inventory.

**Text style:** `heading` — Telka Extended 500 · 54px/1.04 · tracking 0.01em · uppercase

### Film-led conversion panel

**Observed:** Promotional film panel fills most of the page width with roughly 24px side breathing room. A small identity and concise support frame the film, with a Dark button above and translucent watch/pause controls below.

**Transfer:** Introduce a related offering or conversion proposition without reverting to a generic colored CTA rectangle.

### Dark editorial proof

**Observed:** Dark editorial chapter pairs a tall image with a 27px statement and Outline button. Adjacent research rows use top rules, small category/date text and 20px titles. A following news area uses Editorial cards in three columns.

**Transfer:** Use for methods, customer stories or product updates; preserve the editorial scale and dark tonal shift without requiring a particular subject.

**Text style:** `lead` — Telka 400 · 27px/1.2

### Monumental footer ending

**Observed:** Charcoal footer begins with a small brand mark opposite social icons, then a 1px eggshell-at-10% rule. Four left-aligned navigation columns use Footer links, followed by copyright, another rule and Monumental wordmark. The wordmark is the last visual event.

**Transfer:** Retain the oversized end-title device regardless of how few footer links the new product needs; let the link area become shorter without reducing the final wordmark.

### Commercial decision tools

**Only for:** pricing pages

**Observed:** A compact title and billing capsule precede four Plan cards. A white selector stage follows, with a grid of choices and sliders on the left and a floating recommended plan over lavender light on the right. Further sections use broad, lightly ruled comparison tables, a horizontal pack carousel and a photographic purchase band with a white form panel.

**Transfer:** Move from comparable offers to personalized help and concrete usage explanations. Keep selected states black, small annotations violet, and repeated table rows restrained.

**Text style:** `pricing-heading` — Telka Extended 500 · 48px/1 · tracking 0.03em · uppercase

### Contact invitation

**Only for:** enterprise pages

**Observed:** Two stacked 108px extended words on the left sit above a regular 27px invitation. Contact fields form a 636px column on the right with a quiet submit capsule beneath.

**Transfer:** Make the invitation conversational and ask only what the sales team needs to begin.

**Text style:** `contact-display` — Telka Extended 500 · 108px/1 · tracking 0.03em · uppercase

### Monumental warm invitation

**Only for:** developer-focused promotional sections

**Observed:** A centered two-line closing-display sits over Yellow conversion light, with two dark 56px-high capsules beneath. The section uses 192px top and bottom padding.

**Transfer:** Use a very short invitation that works as a poster; keep the glowing light broader than the text.

**Text style:** `closing-display` — Telka Extended 500 · 178.2px/0.88 · tracking 0.03em · uppercase

### Split objections

**Only for:** pricing and enterprise pages

**Observed:** A heading occupies the left half of a 1216px field, with FAQ rows in a 600px stack to the right. Pricing uses the light canvas; enterprise carries this section into charcoal before the footer.

**Transfer:** Address decision-blocking questions immediately before final navigation rather than adding another feature list.

### Text-led value manifesto

**Only for:** developer-focused manifesto pages

**Observed:** A centered 139.3px four-line problem/solution statement places a compact identity between its two halves. Subsequent proof includes a four-column stat strip with 96px extended numerals, sparse comparison rows, broad lavender-backed catalog listings, 180px chapter statements and tall editorial image pairs. The ending uses a yellow invitation, split FAQ and a six-column dark directory footer with legal links at the very bottom.

**Transfer:** Use this variant for a strongly argued value proposition, with quantitative support and fewer interface cards.

**Text style:** `manifesto-display` — Telka Extended 500 · 139.3px/1 · tracking 0.03em · uppercase

## Page flow

**Storyline:** visual promise → focused capabilities → outcome proof → persuasive offer → deeper credibility → useful final navigation and typographic end title

### Media-led product marketing

1. **promise** — Campaign opening with low-anchored white headline and two actions.
2. **capability chapters** — Centered introduction and persistent preview beside expanding capability cards.
3. **product demonstration** — Alternating wide/narrow outcome mosaic.
4. **social proof** — Moving two-row portfolio of produced work.
5. **closing call** — Large film-backed offer panel.
6. **credibility** — Dark editorial methods and news sections.
7. **ending** — Charcoal social/navigation footer and monumental name.

**Transfer:** Lead with an expressive outcome, explain the capabilities behind it, then reinforce trust with work and editorial material.

### Developer-focused value proposition

1. **promise** — Oversized centered problem-and-resolution manifesto.
2. **explanation** — Short membership explanation and bright commercial film.
3. **quantified proof** — Four-column stat strip, editorial pricing argument and comparisons.
4. **capability chapters** — Lavender catalog with linked categories and changing preview imagery.
5. **product demonstration** — Broad photographic integration panel and monumental audience statements.
6. **closing call** — Centered yellow-glow invitation with two actions.
7. **objection handling** — Split FAQ.
8. **ending** — Six-column black directory, social links and final legal row.

**Transfer:** Use when a clear market problem can be resolved with measurable value; keep the rhetoric short and the proof explicit.

### Enterprise sales landing

1. **promise** — Cream poster title, support/action row and editorial workplace photograph.
2. **explanation** — Centered statement over a soft yellow field.
3. **related offer** — Broad promotional media panel.
4. **closing call** — Large two-word contact invitation facing a short enquiry form.
5. **objection handling** — Inverse FAQ.
6. **ending** — Charcoal footer with social strip, four navigation groups and giant low-contrast wordmark.

**Transfer:** Make the enterprise value legible before asking for information, then answer practical concerns close to the form.

### Pricing and purchase decisions

1. **pricing** — Title, billing switch and four comparable plan cards.
2. **decision support** — Interactive selector with a floating recommended plan.
3. **sales escalation** — Editorial photograph with enterprise offer card.
4. **comparison** — Lightly ruled plan and usage tables.
5. **purchase** — Lavender-backed pack carousel followed by a film-backed amount selector.
6. **objection handling** — Light split FAQ.
7. **ending** — Charcoal grouped footer and monumental wordmark.

**Transfer:** Start with comparable choices, give personalized help, then translate prices into understandable outcomes before purchase.

## Writing

Confident, conversational and visually minded. Big promises are short and assertive; supporting language quickly turns practical, with a light human wit rather than technical grandiosity.

**Do not copy:** Do not reuse Pika's names, logos, artwork, slogans, model lists, dates, prices, savings, uptime figures, partnerships or customer claims. Source quotations below demonstrate structure and tone only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you or your. Use we for the product team and plain product nouns for tools; avoid impersonal corporate distance.
- **Rhythm:** Headlines are short stacks or compact noun phrases. Support combines a useful sentence with occasional clipped fragments; longer explanations remain conversational. Actions are two to five words and begin with a verb.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category and who it is for in a compact poster statement. | 5–10 words | “AI Creative Tools Built for Creatives”<br>“Gen Media is overpriced We’re fixing it” |
| Support | Explain the benefit simply, then reinforce with short fragments. | 15–35 words | “[Brand] is the AI creative platform you’ve been waiting for. Comprehensive. Simple. With outputs that meet your standards.” |
| Capability title | A concrete creative verb and an immediately understandable result. | 4–10 words | “Craft the exact image you need”<br>“Give footage your look” |
| Conversion | An uncomplicated verb-led invitation. | 2–5 words | “See it in Action”<br>“Book enterprise demo” |
| Sales invitation | Ask about the reader's work, then explain the next step in human terms. | 20–35 words | “Tell us about your teams, assets and workflows. We'll map [Brand] to how you work and set you up with a pilot in days, not quarters.” |
| Editorial introduction | Use a small touch of human wit while naming the content. | 4–8 words | “Dispatches from our human brains” |
| Pricing support | Explain what to do and how the tool helps; clarify limits nearby. | 15–30 words | “Tell us what you make in a month. The card keeps a plan and a credit count in step with your answers.” |

**Words and phrasing to use:** make; create; your look; simple; tools; work; try; explore; built for; tell us

**Avoid:** revolutionary ecosystem; synergize; unparalleled excellence; next-generation paradigm; enterprise-grade everything

**Rules:**

- Keep the opening promise about a recognizable outcome or audience, not an internal feature taxonomy.
- Let headings feel expansive while support names specific tasks.
- Use playful phrasing sparingly; forms, prices and restrictions remain literal.
- Use comparisons or superlatives only when the new product has supporting facts.

## Do's and Don'ts

### Do

- Use the 72.3px bold extended opening recipe with 0.9 line height over a dominant photograph.
- Keep the desktop header separate from the image caption, at 24px side and top offsets.
- Use 16px capability-card corners and 24px inner padding against a nearly imperceptible cream wash.
- Alternate 832px and 372px workflow images with 12px gutters.
- Keep ordinary body copy regular at 20px/1.25 and use the 16px/1.35 recipe for editorial summaries.
- Use white, charcoal and translucent capsule variants according to the backing material.
- Include a broad atmospheric light field as one persuasive visual moment.
- Finish with a low-contrast typographic name across the footer's full inner width.

### Don't

- Do not replace the extended display face with a narrow condensed poster font.
- Do not apply negative tracking to every heading; the 54px chapter recipe uses positive 0.01em.
- Do not turn the cream canvas into pure white throughout; reserve white for selected controls and raised panels.
- Do not fill all capability cards with lavender or yellow; color is concentrated in media and isolated atmospheric fields.
- Do not add heavy drop shadows to the capability list; its 3% near-black wash supplies the separation.
- Do not use the 180px developer chapter type as the ordinary marketing section heading.
- Do not make all mosaic tiles equal width; the wide/narrow reversal gives the section its visual rhythm.
- Do not render the footer wordmark in bright white; it is a low-contrast end-title field.

## Motion and responsive

### Motion

**Observed:**

- Control transitions use 0.2s cubic-bezier(0.23, 1, 0.32, 1), including color, background-color, border-color and scale; main capsule active scale is 0.97.
- Capability-card min-height transitions use 0.5s cubic-bezier(0.23, 1, 0.32, 1).
- Content arrivals include 0.5s cubic-bezier(0.23, 1, 0.32, 1) and word arrivals at 0.7s cubic-bezier(0.16, 1, 0.3, 1). Two marquee animations are declared at 60s linear infinite.
- Portfolio and workflow sections expose pause controls; reduced-motion classes remove transforms and transitions on several elements.

**Transfer:**

- Preserve the slow portfolio drift and explicit pause control when using moving proof strips.
- Keep button feedback a small contraction rather than a large bounce.
- Keep the persistent preview and changing card height coordinated so the capability list remains readable.

**Unknown:**

- Exact film timing, scroll choreography and the full reduced-motion behavior are not established.

### Responsive

**Observed:**

- The media-led family declares breakpoints at 360px, 640px, 768px, 1024px, 1280px, 1536px, 1680px and 2050px.
- Desktop navigation is hidden below its xl treatment; header side spacing changes from 12px to 24px.
- Workflow markup includes horizontal snapping and narrow-screen aspect-ratio variants; editorial cards declare two columns before three.
- Fluid media titles and pricing headings use the scales attached to their typography recipes.

**Transfer:**

- On narrow screens, retain one full-bleed campaign subject with the headline and support stacked low rather than shrinking the subject into a thumbnail.
- Convert the desktop outcome mosaic to horizontally snapping media tiles; preserve large images and accessible pause controls.
- Stack editorial cards and form columns while retaining the broad typographic footer ending.

**Unknown:**

- Exact mobile hero height, headline sizes and menu construction are not established; these stacking rules are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
