# Patreon — human scale, billboard type

## Overview

An expressive, people-first style with almost weightless grotesk headlines stretched across cinematic photography. Cool blue atmospheric fields carry spare black text and isolated product interfaces, while white conversion cards and a black directory footer ground the composition. It suits ambitious consumer products and creative platforms that can pair emotional imagery with direct, practical explanations; the overall density is low, with concentrated pockets of small text.

### Essentials

- Billboard sentences behave like compositions, not centered titles: Oracle at 187.5px, weight 250, -0.06em tracking, with a left-anchored first line and a right-anchored continuation over edge-to-edge photography.
- The first screen belongs to a person or an activity: a 900px full-bleed photographic stage, a restrained 96px navigation overlay and white headline lines occupying its lower half. Without original photography, commission or stage one close, richly lit human-use scene rather than substituting a dashboard hero.
- Color is an environment rather than a button accent: blue cloudlike fields occupy most explanatory chapters, with black text and black actions; white is reserved for conversion islands and interface content. Sage-green fields are the pricing variant, not a second accent competing on the same page.
- Small pill actions counterbalance enormous words: 47px height, 15px 21px padding, 30px corners and 1px monochrome borders. Keep labels at 13.5px rather than enlarging them to match the headline.
- Media floats through the typography: staggered rectangular portraits and content fragments break the edges, while a single 295px-wide tall interface anchors a benefit chapter. Include an off-axis media constellation even when it must be built from new product outputs rather than portraits.
- The conversion signature is an intimate white island in a cinematic world: a 339px by 424px rounded card centered over a 742px photographic band, followed by a flat black footer with five compact directory columns.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Atmospheric blue | `#5c8ff5` | `--color-stage-blue` | background | Main explanatory environment; combine with Sky light in broad, soft fields rather than a flat branded rectangle. |
| Sky light | `#b9dafa` | `--color-sky-light` | background | Diffuse cool highlights within the blue environment. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, action, border | Text over photography, conversion islands, pricing cards and inverse actions. White at 60% alpha supplies the navigation veil. |
| Footer charcoal | `#292929` | `--color-utility-fill` | surface | Visible result of white at 16% alpha over black; locale and currency controls. |
| Black | `#000000` | `--color-ink` | text, background, action, border | Default text and actions on light or atmospheric fields; full footer background. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Link and focus blue | `#0e87eb` | `--color-focus-blue` | link, border | Focus outlines on footer utility actions; editorial inline links. Not a marketing button fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing benefit cards | Secondary gray | `#959595` | `--color-muted` | text | Subordinate explanations in pricing benefit cards. |
| company and editorial pages | Cool paper | `#fcfcfd` | `--color-paper-light` | background | Light end of the very subtle editorial paper gradient. |
| company and editorial pages | Warm paper | `#f7f3f5` | `--color-paper-warm` | background | Warm end of the editorial paper gradient. |
| pricing pages | Sage environment | `#a7ba92` | `--color-sage` | background | Soft green atmospheric field behind pricing, reassurance cards and feature browsing. |
| audience landing pages | Dusty blue environment | `#92a9c9` | `--color-powder` | background | Lower-saturation blue field for audience-focused feature stories. |

## Typography

- **Oracle** — All marketing headings, paragraphs, captions, navigation and actions. Open, lightly geometric grotesk with rounded bowls; very thin display weights and modest regular text weights. If unavailable, use **Inter**. Use its variable 250–500 weights; retain the tightly tracked display and test line widths. Font stack: "Oracle", "Inter", "Noto Sans JP", "Noto Sans KR", "Noto Sans SC", "Noto Sans TC", "Noto Sans Regular", "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| hero | Oracle | 250 | 187.5px | 0.98 | -0.06em | Default two-line photographic opening; words spread across opposing edges. |
| chapter | Oracle | 250 | 127.5px | 1 | -0.06em | Oversized benefit chapters and staggered two-line section promises. |
| compressed-display | Oracle | 250 | 127.5px | 0.87 | -0.06em | Compact stacked manifesto words and centered three-line statements. |
| quote | Oracle | 300 | 39px | 1.1 | -0.0554em | Low-positioned statement over a full-width portrait. |
| feature-heading | Oracle | 400 | 27px | 1 | -0.02em | Small capability titles beneath the oversized chapter line. |
| conversion-heading | Oracle | 400 | 25.5px | 1.2 | -0.04em | Centered heading inside the white closing conversion island. |
| lead | Oracle | 350 | 22px | 1.2 | -0.02em | Longer editorial support underneath a central manifesto. |
| body | Oracle | 400 | 15px | 1.2 | -0.02em | Default explanatory paragraphs, usually confined to a narrow column. |
| button | Oracle | 350 | 13.5px | 1 | -0.018em | Filled and outline pill labels. |
| navigation | Oracle | 400 | 13.5px | 1.5 | normal | Unboxed primary navigation items. |
| small | Oracle | 350 | 13.5px | 1.1 | -0.02em | Footer links, utility selectors and the returning-user line. |
| directory-label | Oracle | 350 | 13.5px | 1.1 | 0.02em | Footer column titles; subtle positive tracking without uppercase. |
| media-caption | Oracle | 500 | 13.5px | 1.2 | -0.02em | Small white names and arrows inset into photographic tiles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product, pricing and audience landing pages | compact-hero | Oracle | 250 | 187.5px | 0.9 | -0.06em | Tighter two- or three-line photographic title. |
| product and audience galleries | gallery-display | Oracle | 250 | 105px | 0.95 | -0.05em | Two-line heading over the staggered portrait gallery. |
| pricing pages | price | Oracle | 250 | 72px | 0.8 | -0.04em | Single dominant percentage beside its explanation. |
| company and editorial pages | editorial-stat | Oracle | 300 | 39px | 0.87 | -0.03em | Company section titles and complete quantified claims; number and noun remain in one sentence. |
| audience testimonial carousels | audience-quote | Oracle | 300 | 39px | 1.2 | -0.03em | Right-aligned testimonial on a studio portrait. |
| pricing pages | plan-heading | Oracle | 400 | 30px | 1.5 | normal | Plain plan title at the top of the pricing card. |
| pricing pages | assurance-heading | Oracle | 400 | 22.5px | 30px | -0.02em | Titles inside white reassurance cards. |
| product, pricing and audience landing pages | hero-support | Oracle | 400 | 18px | 1.2 | -0.02em | Compact lower-left paragraph over the photographic opening. |
| pricing feature explorers | feature-tab | Oracle | 400 | 18px | 1.2 | -0.03em | Numbered capability navigation, number above label. |
| pricing pages | assurance-copy | Oracle | 400 | 11.3px | 15px | -0.01em | Short gray explanations within reassurance cards. |

**Notes:**

- Display weight 250 is essential: scale supplies authority, not boldness. Maintain -0.06em tracking across hero and chapter sizes.
- Separate the huge promise from its explanation: a 127.5px chapter can sit beside 15px copy without an intermediate subtitle.
- Sentence case is dominant. Preserve intentional phrase-level line breaks and opposing alignment rather than allowing every heading to wrap into an ordinary centered block.
- White gallery text uses exclusion blending against the cool environment, producing a warm dark appearance; this is an optical interaction, not a gold brand-text token.

## Layout

**Density:** Airy at section scale, compact in explanatory copy and footer navigation; isolated interfaces have room to breathe.

### Spacing

| Value | Use |
| --- | --- |
| 6.8px | Quarter-base gaps in footer lists and icon rows. |
| 13.5px | Half-base internal navigation and compact spacing. |
| 19.5px | Default paragraph-to-paragraph or paragraph-to-action separation. |
| 27px | Base section inset and compact group separation. |
| 30px | White card padding and pricing grid gaps; independent of the base family. |
| 35.1px | 1.3 × base for broad grid gaps and header side insets. |
| 37.5px | Outer edge inset in footer and photographic openings. |
| 54px | 2 × base for editorial columns and section separations. |
| 75px | Benefit-copy column separation. |
| 120px | Vertical inset in the asymmetrical benefit chapter. |
| 172.5px | Vertical inset for taller interface-led chapters. |

### Containers and grids

- **full-bleed-stage**: max width 1440px · side padding 37.5px. Edge-to-edge photographic or atmospheric stages at desktop; outer title insets remain much smaller than inner copy gutters.
- **chapter-field**: max width 1185px · side padding 127.5px. Wide benefit composition with a dominant heading, inset copy and a tall interface on the opposite side.
- **demonstration-field**: max width 1110px · side padding 165px. Broad browser demonstration below a split headline-and-copy pair.
- **directory-grid**: 5 columns · gap 35.1px · side padding 37.5px. Five equal footer columns, about 245px each at desktop.
- **editorial-columns** (only for company and editorial pages): max width 1014px · 2 columns · gap 54px · side padding 27px. Two 453px content columns within a 960px inner field; compact company storytelling.
- **assurance-grid** (only for pricing pages): max width 1125px · 3 columns · gap 30px. Three 355px white cards per row, repeated over two rows.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | pill-actions | 30px |
|  | conversion-island | 30px |
|  | utility-selectors | 37.5px |
|  | social-controls | 50% |
| pricing pages | pricing-cards | 22.5px |

## Surfaces and depth

### Surfaces

#### Atmospheric field · level 0

**Use:** Default marketing and product explanation canvas.

**CSS:** `background: radial-gradient(ellipse at 70% 75%, #b9dafa 0%, rgba(185,218,250,0) 55%), radial-gradient(ellipse at 20% 20%, #b9dafa 0%, rgba(185,218,250,0) 45%), #5c8ff5`

**Observed:** Large cloudy blue areas vary softly across successive sections; the light feels behind the content, not like a halo attached to a card.

**Transfer:** Match the soft blue light and unequal cloud distribution; exact stops are not essential.

#### Photo stage · level 0

**Use:** Openings, testimonials and final conversion bands.

**CSS:** `background: #000000; overflow: hidden; position: relative`

**Observed:** Photography fills the stage with no frame, inset or shadow. White title overlays and restrained darkening preserve the scene's natural texture.

**Transfer:** Use an edge-to-edge image or video layer with cover fitting; add only enough black alpha shading for legibility.

#### White island · level 1

**Use:** Conversion modules standing apart from the photographic field.

**CSS:** `background: #ffffff; border-radius: 30px; box-shadow: none`

**Observed:** No visible edge rule or drop shadow; contrast and the generous curve separate the island.

**Transfer:** Use one small, confident conversion object rather than a row of floating cards.

#### Navigation veil · level 2

**Use:** Fixed navigation over scrolled content.

**CSS:** `background: rgba(255,255,255,0.6)`

**Observed:** Opening navigation reads white directly over the scene; scrolled navigation gains a translucent pale backing and dark lettering.

**Transfer:** Keep the veil visually thin enough that imagery and color remain perceptible beneath it.

#### Black directory · level 0

**Use:** Shared site ending.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat and dense compared with the preceding photographic band; there is no decorative divider.

**Transfer:** End with real navigation and utility content, not another oversized slogan.

#### Editorial paper · level 0

**Only for:** company and editorial pages

**Use:** Reading-led pages with history, metrics and mission material.

**CSS:** `background: linear-gradient(150deg, #fcfcfd 15.14%, #f7f3f5 80.54%)`

**Observed:** Almost white, with a barely perceptible warm shift.

**Transfer:** Keep the field restrained so column structure and actual content supply the expression.

#### Sage pricing field · level 0

**Only for:** pricing pages

**Use:** Pricing explanations and reassurance.

**CSS:** `background: radial-gradient(ellipse at 35% 30%, rgba(255,255,255,0.25) 0%, rgba(255,255,255,0) 55%), #a7ba92`

**Observed:** Soft green clouding extends behind the white plan and assurance cards.

**Transfer:** Use the same atmospheric vocabulary as the blue field, but keep this green variant local to pricing.

## Components

### Fixed navigation

**Use:** Global navigation over the opening and subsequent sections.

**CSS:** `position: fixed; height: 96px; z-index: 500; color: #ffffff`

**Text style:** `navigation` — Oracle 400 · 13.5px/1.5

**Observed:** Three-part composition: links on the left, a small centered wordmark, search/login/conversion controls on the right. The inner grid uses 1fr auto 1fr with 54px gaps, 13.5px vertical and 35.1px horizontal padding. Center branding condenses to a mark when scrolling; the Navigation veil and dark lettering appear over later content.

**Transfer:** Keep the center mark independent of the unequal left and right groups.

### Primary button

**Use:** One practical action inside a benefit or conversion module.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #000000; color: #ffffff; border: 1px solid #000000; border-radius: 30px; padding: 15px 21px; height: 47px`

**Text style:** `button` — Oracle 350 · 13.5px/1 · tracking -0.018em

**Observed:** Text-only, compact and content-width; the photographic header uses an inverse white version with black lettering and a white border. Closing-card actions stretch across the text column.

**States:** Declared: hover not specified; focus-visible outline-width 2px, outline-offset 2px.

### Outline button

**Use:** Secondary header actions and low-pressure links.

**CSS:** `display: flex; justify-content: center; align-items: center; color: #ffffff; border: 1px solid #ffffff; border-radius: 30px; padding: 15px 21px; height: 47px; position: relative; overflow: hidden`

**Text style:** `button` — Oracle 350 · 13.5px/1 · tracking -0.018em

**Observed:** Transparent at rest. A white pseudo-element supplies the light hover fill. On editorial light backgrounds the construction reverses to black border and black text with a dark hover fill.

**States:** Declared: hover border-color #fff, color #000; focus-visible outline-width 2px, outline-offset 2px.

### Conversion island

**Use:** Focused closing action over the final photograph.

**CSS:** `display: flex; flex-direction: column; justify-content: center; align-items: center; background: #ffffff; border-radius: 30px; width: 339px; min-height: 424px; padding: 52.5px 30px 75px`

**Text style:** `conversion-heading` — Oracle 400 · 25.5px/1.2 · tracking -0.04em

**Observed:** Order is small brand symbol, centered invitation, Primary button, returning-user sentence with Inline link, then paired distribution badges. The 68px symbol and 25.5px invitation remain modest against the surrounding portrait.

**Transfer:** Use the new product's own mark, one action and only relevant secondary access or distribution choices.

### Inline link

**Use:** Returning-user access or contextual editorial attribution.

**CSS:** `color: #000000; text-decoration: underline`

**Text style:** `small` — Oracle 350 · 13.5px/1.1 · tracking -0.02em

**Observed:** Lives within a sentence instead of in a separate button. Editorial attribution uses blue and the body recipe.

**States:** Declared: hover color color-mix(in srgb,#0e87eb 70%,#fff); focus-visible not specified.

### Footer directory

**Use:** Compact global ending.

**CSS:** `display: flex; flex-direction: column; background: #000000; color: #ffffff; padding: 45px 37.5px 37.5px`

**Text style:** `small` — Oracle 350 · 13.5px/1.1 · tracking -0.02em

**Observed:** Five columns begin with directory-label text, followed by low-opacity white links and 6.8px list gaps. Below come distribution badges, then a horizontal utility row with locale selectors, five social marks and small address/copyright text. Desktop height is 507px.

**Transfer:** Preserve the strong density change and lower utility tier; replace directory categories with useful destinations.

### Locale selector

**Use:** Language, region and currency utilities in the footer.

**CSS:** `display: flex; justify-content: center; align-items: center; background: rgba(255,255,255,0.16); color: #ffffff; border-radius: 37.5px; padding: 10.5px 21px; height: 51px`

**Text style:** `small` — Oracle 350 · 13.5px/1.1 · tracking -0.02em

**Observed:** Icon precedes text; the selectors sit in a tight row and differ in width according to content.

**States:** Declared: hover background-color color-mix(in srgb,#000 70%,#fff); focus-visible outline 1px solid #0e87eb, outline-offset 2px.

### Plan card

**Only for:** pricing pages

**Use:** One comprehensive offer, not an equal-weight comparison table.

**CSS:** `background: #ffffff; border-radius: 22.5px; padding: 30px; max-width: 417.6px; position: relative`

**Text style:** `plan-heading` — Oracle 400 · 30px/1.5

**Observed:** Centered narrow white card. A plain title and short reassurance precede an oversized percentage beside its explanation; grouped bold category labels and checkmarked feature lists occupy most of its height. A full-width action and understated learn-more link close the card.

**Transfer:** Keep a single clear cost model dominant when the new offer supports it; do not invent extra tiers merely to fill horizontal space.

### Assurance card

**Only for:** pricing pages

**Use:** Short concrete answers to financial or operational concerns.

**CSS:** `background: #ffffff; border-radius: 22.5px; padding: 30px; width: 355px; position: relative`

**Text style:** `assurance-heading` — Oracle 400 · 22.5px/30px · tracking -0.02em

**Observed:** Small black pictogram above the title, then assurance-copy in gray. Cards form a three-column grid with 30px gaps, without borders or shadows.

### Numbered feature tab

**Only for:** pricing feature explorers

**Use:** Five-way navigation above one broad product demonstration.

**CSS:** `height: 72px; color: #000000; text-align: left`

**Text style:** `feature-tab` — Oracle 400 · 18px/1.2 · tracking -0.03em

**Observed:** Number sits above the phrase, with 7.5px separation. An active hairline sits above the chosen item; inactive text is faded. Five columns use 67.5px gaps, with the broad demonstration 60px below.

**Transfer:** Use succinct capability categories with a real corresponding demonstration, not decorative tab controls.

## Imagery and graphics

### Cinematic human scene

**Use:** Default opening and photographic closing bands.

**Observed:** People engaged in real creative activity, close enough to see expressions and materials. The opening uses intense blue-violet studio light, grain and deep shadows; other scenes use richly colored rooms, microphones, textiles and natural skin tones. The image fills almost the entire first screen, with words over the bodies rather than a separate text panel.

**Transfer:** Photograph a real user at work with a recognizable tool or output; use a single strong color cast and preserve grain and tactile details. Minimum version is one excellent editorial still with a thoughtful cover position, not a generic team-at-laptop montage.

### Atmospheric color clouds

**Use:** Persistent environment beneath explanatory chapters.

**Observed:** Broad blue, cyan and pale sky regions flow without hard edges. Darker edges and displaced light pools create depth while leaving black type legible. Pricing shifts this treatment to green; audience stories soften it to dusty blue.

**Transfer:** Retain broad fields and low spatial frequency; move the light independently of the text or media.

**Build:** Use a solid Atmospheric blue backing with two or three overlapping radial-gradient ellipses of Sky light, each 600px–1100px wide, offset toward different corners. Fade each to transparent over more than half its radius. If using separate layers, blur them 100px–180px and oversize the layer to hide clipped edges. For pricing replace the base with Sage and use white at 15%–25% alpha. Avoid a crisp centered spotlight.

### Off-axis media constellation

**Use:** Expressive proof and manifesto chapters; a signature device within the page.

**Observed:** Rectangular portraits and content cards are staggered vertically, vary in aspect ratio and extend beyond the left or right edge. Portrait widths are about 289px–447px; later galleries use 375px media with white 13.5px captions and tiny arrows near the lower-left edge. The headline overlaps this field using exclusion blending.

**Transfer:** Use portraits of users or samples of their outcomes; when these are unavailable, stage several genuine product outputs at varied sizes. Keep irregular spacing and edge overflow rather than forming a tidy tile grid.

**Build:** Make an overflow-hidden full-width stage. Position a horizontal set of rectangular media blocks at unequal vertical offsets, mixing portrait and landscape ratios; place one partially outside each edge. Layer the compressed-display heading above the images with white text and mix-blend-mode: exclusion. Attach media-caption labels to the image bottoms; do not add external card chrome.

### Isolated product interface

**Use:** Benefit chapters and broad demonstration sections.

**Observed:** Tall mobile interfaces roughly 295px by 639px or videos about 338px wide stand directly on the color field with rounded native screen edges and little external hardware. Wide browser views occupy a 1110px field below the heading/copy pairing. Internal UI colors belong to the demonstration, not the marketing palette.

**Transfer:** Show the smallest complete workflow that proves the chapter's promise. Keep actual content visible at plausible scale; do not surround it with invented floating control chips.

### Portrait testimonial

**Use:** Full-bleed proof interruption between explanatory sections.

**Observed:** Editorial portrait occupies the entire band; the quote is white and low in the frame. One version has an expansive horizontal quote and separate name; an audience version right-aligns a 39px quote across half the frame and places small circular previous/next controls on the opposite edge.

**Transfer:** Use one expressive portrait and one defensible, specific quotation. Arrange the words in the image's negative space rather than boxing them in a white testimonial card.

### Editorial team and orbital artwork

**Only for:** company and editorial pages

**Use:** Mission narrative and the final vision section before the footer.

**Observed:** A candid group photograph appears in a 453px-wide column, followed later by a square artwork in the same column: dark navy space, fine orbital ellipses and colorful illustrated planets around a glowing yellow center. The text occupies the other column; there is no photographic conversion island here.

**Transfer:** Pair candid documentary imagery with one authored conceptual illustration that explains the new company's worldview. Keep it contained within the editorial column.

**Build:** For a minimum orbital equivalent, draw several thin elliptical SVG paths on a dark field, place differently sized illustrated circles along them, and add a layered warm central disk with translucent blurred rings. Use the new concept's own symbols and palette inside the artwork; keep it separate from the marketing canvas.

### Icons

**Observed:** Small arrows are 11px–12px white strokes at 1.5px with round caps. Header search is about 14px; the down-scroll arrow is a bold 52px white mark. Footer social symbols are 30px solids inside 59px circular targets; pricing reassurance pictograms are black and compact.

**Transfer:** Use simple monochrome icons: tiny arrows for photographic captions, solid pictograms for functional assurances and one conspicuous down arrow on the photographic opening. Do not give each benefit a different colored icon badge.

## Section recipes

How recurring sections are built.

### First screen: Photographic billboard opening

**Observed:** A full-bleed 900px photographic stage fills the first screen. Back to front: richly blue-lit person at work, large white hero text, a small portrait-and-caption credit to the right, then Fixed navigation across the top. The headline begins in the lower half, with the first phrase starting near the left edge and the continuation anchored to the right, covering almost the full width at 187.5px. Both lines and the person remain visible within the first 900px; the explanatory story begins below the fold. Primary access is the inverse action in the header, not a large centered button below the title. A down-scroll indicator sits near the lower edge.

**Transfer:** Use a short promise whose two phrases can occupy opposing edges. Without film, use one deeply colored human-use still and preserve the headline's huge scale and image overlap. Product openings can use compact-hero over three lines with two tall interface fragments entering from below; pricing opens on a warm human workspace; audience openings add a specific proof line and white action at lower left. Editorial pages instead open with compressed-display on Editorial paper and proceed into two-column prose.

**Avoid:** Do not turn this into a left text/right dashboard split, add a centered eyebrow-and-button stack, or shrink the photographic subject into a rounded card.

**Text style:** `hero` — Oracle 250 · 187.5px/0.98 · tracking -0.06em

### Manifesto with floating proof

**Observed:** Compressed-display stacks into two or three huge lines amid the Off-axis media constellation. The Atmospheric field remains visible around isolated media. A narrow lead paragraph and Primary button sit below or off-center instead of directly spanning the headline width.

**Transfer:** Use a core belief or promise and surround it with varied concrete outputs. Include the constellation as a signature device without fixing its location in the story.

**Text style:** `compressed-display` — Oracle 250 · 127.5px/0.87 · tracking -0.06em

### Interface-led benefit chapter

**Observed:** Chapter typography dominates the top of a wide field, often stepping from the left toward a right-aligned second line. A tall Isolated product interface sits on one side; one or two 281px–410px explanatory columns sit on the other with feature-heading, body copy and Primary button. Taller versions use 172.5px vertical padding and 150px side insets; alternate versions use 120px and 127.5px.

**Transfer:** Alternate the visual weight between interface and copy while preserving the enormous-to-small type contrast. Use one main workflow per chapter.

**Text style:** `chapter` — Oracle 250 · 127.5px/1 · tracking -0.06em

### Wide demonstration chapter

**Observed:** A split header pairs a short two-line chapter heading on the left with a small paragraph to the right. A broad Isolated product interface fills the 1110px field below; the shared Atmospheric field continues around it.

**Transfer:** Use this when the proof needs browser width rather than a tall mobile view. Let the demonstration explain the claim rather than adding a card grid.

**Text style:** `chapter` — Oracle 250 · 127.5px/1 · tracking -0.06em

### Full-bleed human proof

**Observed:** Portrait testimonial interrupts the color-field chapters with a near-viewport-height photograph. Quote sits low over the image with no enclosing surface; attribution is separate and small relative to the photo.

**Transfer:** Choose an unusually specific statement and frame the subject so there is genuine space for the words.

**Text style:** `quote` — Oracle 300 · 39px/1.1 · tracking -0.0554em

### Photographic invitation and directory

**Observed:** A 742px Photo stage holds the Conversion island in the center, surrounded by richly tactile people photography. Below, Footer directory changes immediately to flat black with five columns, distribution badges and utility controls. Product and audience variants retain the same island but change the photograph.

**Transfer:** Preserve the intimate conversion object against the expansive scene. Use relevant access paths and real destinations in the dense ending.

**Text style:** `conversion-heading` — Oracle 400 · 25.5px/1.2 · tracking -0.04em

### Pricing clarity and reassurance

**Only for:** pricing pages

**Observed:** After a photographic compact-hero, a centered compressed-display promise introduces a single Plan card on Sage pricing field. Later a chapter heading and support paragraph lead into the three-column Assurance card grid. Numbered feature tabs then browse a broad demonstration.

**Transfer:** Adapt the pricing mechanism honestly; keep the hierarchy of one dominant commercial model, grouped inclusions and concrete operational reassurance.

**Text style:** `price` — Oracle 250 · 72px/0.8 · tracking -0.04em

### Editorial numbers and vision

**Only for:** company and editorial pages

**Observed:** A compressed-display opening leads into two-column history/current-state prose. Subsequent rows pair a small section introduction on the left with complete 39px numerical claims on the right, not giant detached numerals. Mission text pairs with a candid team image; the final vision copy pairs with square conceptual artwork. Black directory follows directly.

**Transfer:** Use a small number of supported metrics and meaningful artifacts of the organization. Keep the metric and what it measures in one readable phrase.

**Text style:** `editorial-stat` — Oracle 300 · 39px/0.87 · tracking -0.03em

## Page flow

**Storyline:** Emotional promise → human or output proof → focused capability demonstrations → concrete value and reassurance → intimate final invitation → useful directory.

### Broad brand and platform introduction

1. **promise** — Cinematic person-at-work opening with opposing giant headline lines.
2. **social proof** — Staggered portrait constellation and full-bleed quote.
3. **capability chapters** — Central manifesto, tall interface-led benefit, then commercial capability with two narrow explanations.
4. **closing call** — White conversion island over a tactile photograph.
5. **navigation** — Black five-column directory and utility row.

**Transfer:** Move from the emotional world to concrete workflows; vary the media format rather than repeating identical feature rows.

### Explain a commercial model and reduce perceived risk

1. **promise** — Warm workspace photograph with giant white free-start message.
2. **pricing** — Centered oversized promise and one comprehensive white percentage card on green atmosphere.
3. **objection handling** — Large reassurance heading with six compact white assurance cards.
4. **product demonstration** — Numbered feature navigation above a broad interface.
5. **closing call** — Photographic conversion island followed by the black directory.

**Transfer:** Pair transparent cost explanation with operational reassurance; keep the emotional opening even on a practical buying page.

### Prove a product capability through successive workflows

1. **promise** — Three-line white title over vivid human photography; two mobile fragments enter the scene.
2. **capability chapters** — Alternating oversized promise and narrow explanation beside a tall interface.
3. **product demonstration** — Large browser-format showcase beneath a split title/copy header.
4. **social proof** — Staggered named photographic gallery.
5. **closing call** — Photo-backed white conversion island and shared black directory.

**Transfer:** Organize around the user's practical journey; use tall and wide demonstrations according to the task.

### Make a specific audience recognize itself and its benefits

1. **promise** — Dark editorial portrait, giant audience title and specific lower-left proof with action.
2. **value overview** — Large introduction and three illustrated benefit summaries.
3. **social proof** — Full-bleed portrait quote carousel.
4. **capability chapters** — Revenue, customization, live workflow and management benefits using tall and wide interfaces.
5. **social proof** — Staggered peer gallery with small inset captions.
6. **closing call** — White invitation card over studio photography, then black directory.

**Transfer:** Replace audience, proof and tasks with relevant specifics; retain the same high-drama opening and practical middle.

### Explain an organization's origin, scale and worldview

1. **context** — Large black editorial title on near-white paper.
2. **origin and present** — Parallel short prose columns with small date/state labels.
3. **quantified proof** — Left introduction and right column of 39px complete numerical claims.
4. **mission** — Text and understated outline action beside candid team photography.
5. **vision** — Two paragraphs beside square authored conceptual artwork.
6. **navigation** — Direct transition to shared black directory, without the photographic conversion island.

**Transfer:** Keep this quieter reading-led variant for company material rather than flattening the main marketing style into editorial columns.

## Writing

Warm, assured and autonomy-minded. Emotional headlines promise freedom or direct connection, while compact explanations name the actual mechanism rather than piling on superlatives.

**Do not copy:** Do not reuse Patreon names, logos, creator identities, quotations, proprietary imagery, revenue figures, membership counts, fees or unsupported comparative claims. Source examples illustrate tone and structure only.

- **Addressing the reader:** Speak directly to you and your goals; refer to the product by name when explaining a capability. Use we for genuine commitments and operational responsibilities.
- **Rhythm:** Headlines tend toward two to six words split into purposeful phrases. Support paragraphs are compact but concrete, often followed by a short verb-led action; longer editorial prose stays in narrow columns.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An expansive emotional outcome expressed as a concise phrase. | 2–6 words | “Your wildest creative reality”<br>“Create on Your Terms with [Brand]” |
| Chapter headline | Concrete benefit expressed through a rhythmic fragment or short sentence. | 3–7 words | “Creators. Fans. Nothing in between.”<br>“Reach every fan every time” |
| Supporting explanation | Name the tool or interaction and explain how it creates the promised outcome. | 1–3 compact sentences | “[Brand] gives you a direct line of access to your fan community, with no ads or gatekeepers in the way.” |
| Primary action | Short verb-led action or a plain start invitation. | 2–5 words | “Build real community”<br>“Get started” |
| Reassurance | State a practical burden handled for the reader. | 4–7 words | “Secure payments handled for you”<br>“No setup headaches” |

**Words and phrasing to use:** your terms; your own; directly; real; build; share; connect; grow; space; work

**Avoid:** revolutionary solution; synergize; unlock limitless potential; best-in-class ecosystem; disrupt everything

**Rules:**

- Lead with the reader's agency, then explain the means.
- Allow short fragments and deliberate full stops in headlines; keep paragraphs grammatical and useful.
- Use numerical proof only when supported and relevant to the audience.
- Make actions describe either a real destination or a useful next step; do not make every link another emotional slogan.

## Do's and Don'ts

### Do

- Keep hero and chapter titles at weight 250 with -0.06em tracking.
- Compose 187.5px headline lines against different edges of the same photograph.
- Use the 27px spacing family alongside the distinct 30px card-padding family.
- Keep 15px explanatory copy narrow even when the adjacent title is 127.5px.
- Stage one tall interface at roughly 295px width instead of spreading many devices across every chapter.
- Give the white conversion island 30px corners and enough photographic space to remain a small object in a larger scene.
- Use tiny 13.5px white inset captions with a small arrow on gallery photography.
- Keep footer information compact at 13.5px within a black, five-column ending.

### Don't

- Do not use bold 700-weight marketing headlines; it removes the airy billboard character.
- Do not make the blue atmosphere a small accent strip while leaving every capability chapter plain white.
- Do not fill primary actions with blue; the action system is black and white.
- Do not add drop shadows to pricing or conversion cards; separation comes from their white surface.
- Do not normalize staggered media into equal square avatars inside bordered tiles.
- Do not detach corporate metrics into enormous numerals; use the 39px complete-claim treatment in that variant.
- Do not carry sage pricing backgrounds onto ordinary feature chapters.
- Do not use uniformly rounded frames for every photograph; portrait galleries retain rectangular silhouettes.

## Motion and responsive

### Motion

**Observed:**

- Declared utility background transition: 0.5s cubic-bezier(0.215,0.61,0.355,1). Navigation text color uses 0.25s with the same easing.
- The navigation veil declares a 1s opacity transition with cubic-bezier(0.215,0.61,0.355,1). Some controls and surfaces declare transform transitions of 0.5s or 1s.
- Hero and gallery content use translated layers; opening and testimonial content have multiple slides.

**Transfer:**

- Preserve the distinction between fast text-color response and slower veil change.
- Keep moving media and translated imagery subordinate to the anchored giant phrases; avoid making the entire screen move as one layer.

**Unknown:**

- Autoplay intervals, scroll synchronization, reduced-motion treatment and exact animation choreography are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 768px, 769px, 960px, 964px and 1300px; some layouts also declare 1024px or 1120px.
- Desktop navigation has separate desktop-only wrappers; footer columns are structured with details and summary elements.

**Transfer:**

- On narrow layouts, preserve the opposing phrase alignment where readable, then reduce display size before sacrificing the human subject.
- Stack explanatory columns and the tall interface in a deliberate reading order; retain one off-edge media fragment rather than shrinking the full desktop constellation.
- Allow the directory to become disclosure groups and keep the conversion island within the available width.

**Unknown:**

- Exact small-screen type sizes, layout switching rules and mobile media replacements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
