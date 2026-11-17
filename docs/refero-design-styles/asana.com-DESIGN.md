# Asana — connected work, playful agents

## Overview

An expansive, light-first enterprise style that makes complex coordination feel approachable. Thin grotesk headlines and restrained black-and-white layouts meet candy-colored characters, connected diagrams, and layered interfaces with real people. It suits platforms with many capabilities and audiences: spacious storytelling gives way to practical, denser catalogs and purchasing tools. Dark stages provide contrast without making the whole experience feel technical or nocturnal.

### Essentials

- A promise above a working scene, not a conventional hero banner: a centered 64px/1 headline at weight 300 and -0.02em tracking leads into a 628px + 628px demonstration split with a 32px gutter.
- Light typography carries enterprise confidence: section statements use 54px/1, weight 300, -0.02em; explanatory text uses 20px/1.5, weight 300, 0.02em rather than heavy display lettering.
- Controls are capsules while content stays architectural: 50–64px action pills sit beside 4px-radius fields, 8px-radius feature cards and 20px-radius inset chapter bands.
- Color belongs to the things doing the work: white dominates the ordinary reading sections, near-black anchors major demonstrations and the ending, and pink #ffc9ff marks selected pills. Concentrate other bright colors in compact illustrated objects and media rather than every heading or card.
- Complexity is made tangible with connected layers: include a white interface-and-human collage and a dark connected-node diagram. Without finished product imagery, compose a few representative task panels, portrait circles and fine SVG connectors instead of a generic dashboard rectangle.
- A friendly sculptural counterpoint interrupts the sober grid: use glossy, rounded colored capability objects with tiny expressive black markings on white cards; a simple rounded SVG or CSS object with highlights and a soft contact shadow is the minimum equivalent.
- The page has a connective tissue and a decisive ending: thin pink routing lines with circular human or tool nodes bridge spacious chapters; a 54px white closing statement and white pill action lead into a continuous near-black directory footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Candy pink | `#ffc9ff` | `--color-selected` | accent, surface | Selected audience or product pills; small, concentrated emphasis. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text, action | Dominant canvas, interface cards and inverse actions. |
| Almost white | `#fafafa` | `--color-soft-band` | background, surface | Inset resource and demonstration bands. |
| Pale gray | `#f3f3f3` | `--color-soft-control` | surface, text | Circular chevron backing, secondary plan actions and footer text. |
| Light edge | `#e7e7e7` | `--color-rule` | border | Feature-card outlines and accordion separators. |
| Medium edge | `#cfcfcf` | `--color-field-edge` | border | Input and pricing-card outlines. |
| Muted gray | `#6e6e6e` | `--color-muted` | text, border | Supporting labels and outlined secondary controls. |
| Dark divider | `#565656` | `--color-dark-edge` | border, surface | Separators and outlines inside dark chapters. |
| Charcoal | `#3d3d3d` | `--color-body` | text, surface | Supporting prose and inactive pills on dark stages. |
| Near-black ink | `#0d0d0d` | `--color-ink` | text, background, action | Primary text, dark stages, footer and filled actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| immersive platform capability chapters | Deep purple | `#6a0085` | `--color-chapter-purple` | background, text | Immersive capability chapter backdrop and matching card text. |
| immersive platform capability chapters | Pale orchid | `#ffdcff` | `--color-chapter-tint` | surface, text | Paired demonstration cards and headline on the purple chapter. |
| pricing pages | Mint label | `#b5e9ca` | `--color-purchase-tag` | surface | Small prepaid, on-demand and add-on labels. |
| pricing pages | Deep green label ink | `#004232` | `--color-purchase-ink` | text | Text on mint purchasing labels. |

## Typography

- **TWK Lausanne** — All marketing headings, paragraphs, navigation and actions. Open, contemporary grotesk with a large x-height, near-circular forms and lightweight display cuts; friendly rather than mechanical. If unavailable, use **Inter**. Use weights 300–600; preserve tight display tracking and generous paragraph leading. Font stack: "TWK Lausanne", "Inter", "Helvetica Neue", Helvetica, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | TWK Lausanne | 300 | 64px | 1 | -0.02em | Centered marketing promise. |
| heading | TWK Lausanne | 300 | 54px | 1 | -0.02em | Major chapter headings and closing statements. |
| heading-small | TWK Lausanne | 400 | 36px | 1.2 | -0.01em | Demonstration subheadings and smaller FAQ leads. |
| quote | TWK Lausanne | 300 | 36px | 1.3 | -0.01em | Large upright customer quotation beside photography. |
| item-heading | TWK Lausanne | 400 | 30px | 1.2 | normal | Resource-row titles, proof statements and explanatory columns. |
| card-heading | TWK Lausanne | 500 | 24px | 1.2 | normal | Feature cards, accordion questions and capability selectors. |
| body | TWK Lausanne | 300 | 20px | 1.5 | 0.02em | Explanatory prose and primary section support. |
| action | TWK Lausanne | 400 | 20px | 1.5 | normal | Prominent 64px action pills. |
| body-small | TWK Lausanne | 300 | 16px | 1.5 | 0.02em | Compact section introductions, card descriptions and opening subtitle. |
| eyebrow | TWK Lausanne | 500 | 16px | 1.5 | 0.04em, uppercase | Short chapter labels above a statement. |
| action-small | TWK Lausanne | 500 | 16px | 1.5 | normal | Signup pills and product selectors. |
| footer-link | TWK Lausanne | 400 | 16px | 1.5 | normal | Directory footer links. |
| navigation | TWK Lausanne | 500 | 14px | 1.5 | normal | Navigation links and compact header actions. |
| audience-tab | TWK Lausanne | 600 | 11px | 1.5 | 0.02em | Compact audience selectors in the opening demonstration. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| feature catalog pages | catalog-display | TWK Lausanne | 300 | 80px | 1 | -0.02em | Extra-large centered introduction for a capability catalog. |
| pricing pages | plan-heading | TWK Lausanne | 400 | 36px | 1 | -0.01em | Plan names in comparison cards. |
| feature catalogs and purchasing cards | card-link | TWK Lausanne | 500 | 16px | 1 | normal | Compact links paired with circular arrow icons. |
| pricing pages | purchase-label | TWK Lausanne | 400 | 11px | 1.75 | normal | Mint purchasing tags. |

**Notes:**

- Keep weight 300 on the largest statements; the difference between light headlines and medium card labels supplies hierarchy without bold display type.
- Display and section type share -0.02em tracking. At 36px tracking relaxes to -0.01em; paragraphs use positive 0.02em tracking.
- Do not apply the 80px catalog introduction to every landing page. The standard opening remains 64px.
- Keep customer quotations upright, not italic. Use the 36px/1.3 quote recipe rather than the tighter subheading recipe.

## Layout

**Density:** Airy narrative sections with compact controls and more densely packed comparison and catalog grids.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-heading spacing, pill gaps and icon-to-label gaps. |
| 12px | Resource title-to-description spacing and header vertical padding. |
| 16px | Heading-to-support spacing, small card content gaps and signup field-to-button gaps. |
| 24px | Feature-card padding, support-to-action spacing and carousel-card gaps. |
| 32px | Main grid gutters, resource-row padding, pricing-card padding and opening headline-to-subtitle spacing. |
| 40px | Section stack gaps and separation between headings and product tabs. |
| 48px | Horizontal inset within wide rounded bands. |
| 64px | Section heading to large visual demonstration. |
| 80px | Narrative section spacing and testimonial lead-in. |
| 120px | Major chapter vertical padding. |
| 160px | Default promise top space and separation after substantial demonstrations. |

### Containers and grids

- **Marketing content**: max width 1288px · 12 columns · gap 32px · side padding 76px. Desktop content span at 1440px; align text, media and cards to the same twelve-column grid.
- **Header and footer container**: max width 1312px · side padding 64px. Slightly wider navigation and directory alignment.
- **Inset chapter**: max width 1384px · side padding 48px. Rounded band sits 28px from either viewport edge; inner content aligns to the marketing grid.
- **Half split**: 2 columns · gap 32px. Two 628px columns for demonstrations, testimonials and resource navigation. Accordion text can occupy a narrower 518px zone within its half.
- **Capability grid**: 4 columns · gap 32px. 298px feature or plan cards across the desktop content span.
- **Explanation grid**: 3 columns · gap 32px. 408px prose or purchasing cards.

## Corner radius

| Element | Radius |
| --- | --- |
| Actions | 100px |
| Chapter bands | 20px |
| Media and pricing cards | 16px |
| Resource rows | 10px |
| Feature cards | 8px |
| Fields and integration tiles | 4px |
| Icon discs | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Inset outline | `rgb(13, 13, 13) 0px 0px 0px 1px inset` | Outlined white header sales action; avoid an external drop shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Default reading surface.

**CSS:** `background: #ffffff; color: #0d0d0d`

**Observed:** Untextured, bright and mostly borderless.

**Transfer:** Let typography, image layers and spacing establish structure.

#### Dark stage · level 0

**Use:** High-contrast product chapter and closing band.

**CSS:** `background: #0d0d0d; color: #ffffff; border-radius: 20px; padding: 120px 48px`

**Observed:** Inset chapters have white outer gutters; the closing area joins the footer as a continuous dark ground.

**Transfer:** Use the inset treatment for a major demonstration and the continuous version for the ending.

#### Soft resource band · level 0

**Use:** Onboarding and resource navigation.

**CSS:** `background: #fafafa; border-radius: 20px; padding: 120px 48px`

**Observed:** Pale neutral backing distinguishes white resource rows without shadows.

**Transfer:** Pair a short left-hand introduction with a right-hand stack of practical next steps.

#### Feature card · level 1

**Use:** Compact capability explanation.

**CSS:** `background: #ffffff; border: 1px solid #e7e7e7; border-radius: 8px; padding: 24px; box-shadow: none`

**Observed:** Fine edges rather than elevation; consistent text and icon slots. Dark counterparts use the stage ground with #565656 outlines.

**Transfer:** Keep the frame understated so the icon and title carry recognition.

#### Immersive chapter · level 0

**Only for:** immersive platform capability chapters

**Use:** Scroll-led paired capability demonstrations.

**CSS:** `background: #6a0085; color: #ffdcff`

**Observed:** A full-bleed saturated scene contains two 628px pale cards with 16px corners, UI art above compact text. Other chapters change to deep blue with cyan cards or burgundy with blush cards.

**Transfer:** Use a dark saturated family and its very pale complement for each chapter, not unrelated bright card colors.

## Components

### Sticky navigation

**Use:** Persistent global wayfinding.

**CSS:** `background: #ffffff; height: 68px; padding: 12px 64px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `navigation` — TWK Lausanne 500 · 14px/1.5

**Observed:** Logo and compact menus sit left; language control, login and two capsule actions sit right. The header stays white over dark content; its primary action is 44px high.

**Transfer:** Keep the menu short and reserve filled ink for the most direct conversion.

### Primary signup pill

**Use:** Email signup in the first demonstration.

**CSS:** `background: #0d0d0d; color: #ffffff; border-radius: 100px; padding: 12px 24px; height: 50px; display: flex; align-items: center; justify-content: center`

**Text style:** `action-small` — TWK Lausanne 500 · 16px/1.5

**Observed:** A compact action follows the email field on the same line. Larger standalone variants use the action recipe with 16px 32px padding and 64px height.

**States:** Declared: hover background #f3f3f3 and text rgb(13, 14, 16); active background #ffffff.

### Inverse action pill

**Use:** Primary action on a dark stage or closing band.

**CSS:** `background: #ffffff; color: #0d0d0d; border-radius: 100px; padding: 16px 32px; height: 64px; display: flex; align-items: center`

**Text style:** `action` — TWK Lausanne 400 · 20px/1.5

**Observed:** Plain text capsule without an icon. A secondary action beside it remains dark with a thin pale outline.

**States:** Declared: hover background #f3f3f3, color rgb(205, 72, 72), border-bottom 2px solid rgb(205, 72, 72); active background #ffffff.

### Product selector

**Use:** Switch the active product demonstration in a dark chapter.

**CSS:** `background: #ffc9ff; color: #0d0d0d; border-radius: 64px; padding: 16px 32px; display: flex; gap: 8px`

**Text style:** `action-small` — TWK Lausanne 500 · 16px/1.5

**Observed:** The selected pink capsule sits among charcoal capsules with white labels; the group is centered and wraps when needed.

**States:** Declared: hover background rgb(240, 106, 106), text rgb(13, 14, 16); focus-visible outline 2px solid #4786ff with 2px offset.

### Audience selector

**Use:** Compact tabs above the opening benefit statement.

**CSS:** `background: #ffffff; color: #0d0d0d; border-radius: 146px; padding: 10px 16px; display: flex; align-items: center`

**Text style:** `audience-tab` — TWK Lausanne 600 · 11px/1.5 · tracking 0.02em

**Observed:** Small audience labels run across the text column, with a pink fill on the active item and no enclosing segmented-control tray.

**States:** Declared: hover background #565656 and text #ffffff; focus-visible outline 2px solid #4786ff with 2px offset.

### Capability card

**Use:** A concise feature explanation in a repeated grid.

**CSS:** `background: #ffffff; border: 1px solid #e7e7e7; border-radius: 8px; padding: 24px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `card-heading` — TWK Lausanne 500 · 24px/1.2

**Observed:** Icon first, title, short body-small description, then a short link with a 16px circular arrow. Dark variants reverse the text and use a dark outline. Friendly sculptural-object cards stretch taller in a horizontal carousel.

**Transfer:** Keep the icon small and the text legible rather than making each card a full illustration.

### Resource row

**Use:** High-visibility navigation to support, templates or demonstrations.

**CSS:** `background: #ffffff; border-radius: 10px; padding: 32px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `item-heading` — TWK Lausanne 400 · 30px/1.2

**Observed:** Title and muted description form a left stack; a 59px ink circle with a white right arrow anchors the right. Rows stack with 16px gaps on a soft band; the inverse arrangement uses pale rows on white.

**Transfer:** Make the whole row navigable, with descriptions that clarify the destination.

### FAQ row

**Use:** Objection handling near the end of a page.

**CSS:** `border-bottom: 1px solid #e7e7e7; position: relative`

**Text style:** `card-heading` — TWK Lausanne 500 · 24px/1.2

**Observed:** A roughly 94px closed row has a medium-weight question and a small circular chevron at the far right. Answers use body typography. A left-hand section title balances the wider 738px question column; dark variants use #565656 rules.

**Transfer:** Keep answers collapsed until requested and preserve the understated horizontal rhythm.

### Email field

**Use:** Low-friction signup.

**CSS:** `background: #ffffff; border: 1px solid #cfcfcf; border-radius: 4px; padding: 12px 16px; height: 50px`

**Text style:** `body-small` — TWK Lausanne 300 · 16px/1.5 · tracking 0.02em

**Observed:** The rectangular field contrasts with its adjacent capsule action. Alternative identity-provider pills sit above an 'or' divider.

**Transfer:** For sales-led forms, use the same field geometry with dark fill, paired fields and a full-width inquiry area.

### Footer directory link

**Use:** Dense final navigation.

**CSS:** `color: #f3f3f3; border-bottom: 1px solid transparent; text-decoration: none`

**Text style:** `footer-link` — TWK Lausanne 400 · 16px/1.5

**Observed:** Five directory columns follow a small brand mark; lower utilities contain copyright, language, social circles, legal links and app-store badges.

**States:** Declared: hover text #ffffff and border-bottom-color #ffffff.

### Plan card

**Only for:** pricing pages

**Use:** Plan comparison and purchasing decisions.

**CSS:** `border: 1px solid #cfcfcf; border-radius: 16px; padding: 32px; display: grid; position: relative`

**Text style:** `plan-heading` — TWK Lausanne 400 · 36px/1 · tracking -0.01em

**Observed:** Four equal columns align plan name, short audience description, price, billing explanation, action and checked features. The entry paid plan gets the ink action; surrounding plans use pale actions. Two-column usage cards and three-column add-on cards share this frame.

**Transfer:** Keep purchasing mechanics explicit and align decision-making content across plans.

## Imagery and graphics

### Layered human-interface collage

**Use:** Primary demonstration and opening visual proof.

**Observed:** A roughly square composition occupies half the content width. Warm, naturally lit photography is interleaved with white rounded task panels, tiny portraits, tool badges and thin routing lines. Soft edge shadows separate panels without a large tinted frame.

**Transfer:** Show one authentic user or real-world outcome and three to five representative work objects. Keep most panels white and overlapping; minimum version is a photo tile, two readable interface cards and connecting paths.

**Build:** Use a 604px square relative stage; anchor a portrait tile near the upper-left third, place two offset white 16px-radius panels across the center and right, and add 32–48px portrait discs. Draw 1px gray SVG paths behind the panels with small ink connection dots; give panels a soft low-opacity black edge shadow.

### Connected dark diagram

**Use:** Explain an underlying system with a memorable visual rather than prose alone.

**Observed:** A near-black 628px square with rounded corners contains a receding fine dot field, white floating object labels, pastel icon squares, portrait circles and thin multicolored network edges. The diagram fills one half of a heading-and-accordion chapter.

**Transfer:** Map the new product's own objects and relationships, keeping a handful of labels readable. Minimum version: four white object nodes, three avatar or tool discs and a connected SVG graph.

**Build:** Use an ink rounded square, overlay a radial fade on a 16px-spaced low-opacity white dot pattern, and place four white label rectangles around the center. Connect their centers with 1px SVG paths in pink, mint and pale blue at restrained opacity; add tiny white junction dots and a few circular portrait nodes.

### Friendly capability sculptures

**Use:** Compact visual anchors in otherwise sober white carousel cards.

**Observed:** Small glossy pink, green, violet and blue rounded forms have black eye-like marks. Highlights, inflated lobes and a soft contact shadow make them feel like playful physical objects; the art stays small relative to the card and its text.

**Transfer:** Create original rounded objects to distinguish capabilities, not a mascot covering the page. A simple two-lobed vector with tiny dark markings is sufficient.

**Build:** Combine two or three overlapping rounded SVG blobs in a single saturated hue; add an upper-left white highlight at 35% opacity, a darker lower edge and a blurred black shadow beneath. Use two short ink ovals or angular marks near the center. Place a 64–80px object above the card title with generous white space.

### Routing-line interlude

**Use:** A recurring connective device between narrative chapters.

**Observed:** A very thin pink line crosses almost the whole content width, bends softly down a level and passes through a few white-ringed circular portraits and bright tool nodes. The strip is only about 127px tall.

**Transfer:** Use real collaborators, inputs or outputs relevant to the new product. When portraits are unavailable, use small original pictograms within the same circular nodes.

**Build:** Draw a 1288px-wide SVG with a 1–2px pink path, long horizontal runs and two rounded downward bends. Place 48–64px white discs at selected path points with a fine gray outer ring and small ink port dots. Keep the background white and most of the strip empty.

### Customer outcome photography

**Use:** Testimonial proof.

**Observed:** A wide natural-light customer scene in a 628px by 419px rounded frame sits beside a large upright quote, customer mark, small name and role. Muted green and cream tones keep it calmer than the product art.

**Transfer:** Use a real environment or artifact that demonstrates the customer's work, rather than a generic smiling team.

### Technical product panels

**Only for:** dark technical product pages

**Use:** Alternating product-benefit demonstrations.

**Observed:** Square dark interface scenes are offset against a vivid blue edge visible on the top and side. A sharp white or dark floating dialog overlays a dimmed application beneath; the paired text remains spare.

**Transfer:** Use a focused real interaction instead of exposing every UI detail. Preserve the bright edge and dimmed surrounding context.

### Immersive paired demonstrations

**Only for:** immersive platform capability chapters

**Use:** A large scroll-led capability showcase.

**Observed:** Two pale rounded cards sit on a saturated full-width backdrop. Their upper halves contain isolated UI panels or trust symbols with soft matching glows; lower halves contain concise headings, description and outlined pills.

**Transfer:** Use complementary pale and deep shades, with one focused capability per card. Match the soft glow; exact stops are not essential.

**Build:** Place two 628px cards with 16px corners and a 32px gutter. In each upper media region, layer a white representative UI panel over a broad blurred radial wash of the chapter hue; use a solid pale lower text region with 24px 40px 40px padding.

### Icons

**Observed:** Functional chevrons and arrows are compact filled SVGs, commonly 16px; larger resource arrows are white inside ink discs. Feature pictograms are simple fine-line symbols on small pastel circles or colored rounded-square badges, usually within 48px slots.

**Transfer:** Use one coherent simple icon family; reserve bright multicolor marks for actual integrations and keep navigation icons monochrome.

## Section recipes

How recurring sections are built.

### First screen: Promise and working-scene opening

**Observed:** A white 68px sticky navigation sits above an exceptionally open centered promise. The 64px display headline occupies a 628px-wide central measure, usually two lines, beginning after 160px of top space. A 16px subtitle follows by 32px, then 80px breathing room introduces the demonstration. Below, a compact Audience selector row and 54px benefit statement occupy the left half; body prose, two provider pills, an 'or' divider and an Email field with Primary signup pill follow. The Layered human-interface collage fills the right half. Within the first 900px the promise, subtitle, audience controls, benefit, signup controls and most of the collage are visible; legal detail, the visual's bottom and customer proof continue below. Layers remain white canvas, fine connectors, photography, then floating white work objects.

**Transfer:** Preserve the two-stage opening: broad promise first, concrete benefit and working scene second. Without finished art, use the collage's minimum panel-and-photo recipe. A sales-led technical page instead opens with a dark centered 64px promise, small product identifier, white Contact sales pill and wide video stage. A catalog uses the 80px centered heading and one action; pricing uses a centered 64px promise above comparison cards; a platform overview can put a centered signup form above wide human-interface photography.

**Avoid:** Do not replace this with a giant colored hero slab, a full-width screenshot immediately behind the headline, or a centered pair of buttons with no concrete working scene.

**Text style:** `display` — TWK Lausanne 300 · 64px/1 · tracking -0.02em

### Heading and interactive explanation

**Observed:** A 54px left-aligned section statement precedes the half-width Connected dark diagram by 64px. The right column contains four ruled selectors using card-heading typography, 32px vertical row padding and a small circular chevron. The selected explanation expands in 20px body text.

**Transfer:** Use this for conceptual depth: one visual system, several short facets and one explanation at a time.

### Sculptural capability carousel

**Observed:** Eyebrow, 54px statement, compact support and outlined action sit above a horizontally overflowing set of white Capability cards. Cards have 24px gaps and friendly colored sculptures. Right-aligned 44px circular controls sit above the row; adjacent cards remain partially visible.

**Transfer:** Show multiple use cases or capabilities with original small objects; keep the horizontal overflow intentional and the card copy concise.

### Dark product stage

**Observed:** The Dark stage surface holds a 54px statement, a Product selector group after 40px and a large interface presentation beneath. The active central panel is bright and readable while neighboring panels are dimmed and partially visible.

**Transfer:** Use one high-contrast showcase to organize related offerings or workflows, rather than scattering unrelated color bands.

### Customer proof pair

**Observed:** A Routing-line interlude introduces two equal columns separated by 32px. Customer outcome photography occupies the left; the right contains a customer mark, 36px upright quote, name and small role. The proof band above earlier chapters uses a 30px statement beside a horizontal customer-logo row, not giant numerals.

**Transfer:** Support claims with attributable customer evidence. Give a real quote room rather than compressing it into a tiny testimonial tile.

### Practical next steps

**Observed:** The Soft resource band uses a left-hand 54px statement and 20px support opposite a stack of Resource rows. Rows have 16px gaps, titles above muted support and circular arrow controls.

**Transfer:** Offer a few useful routes for visitors who prefer to explore before converting.

### Capability catalog chapter

**Observed:** A 54px heading, 20px support and capsule action lead into a four-column Capability grid, with 32px horizontal and 40px vertical gaps. Some chapters use the Dark stage and inverse text; most remain white. Integration chapters instead pair introductory text with a two-column stack of compact logo tiles.

**Transfer:** Group features into meaningful categories and let a partial last row remain left-aligned rather than stretching cards.

**Text style:** `heading` — TWK Lausanne 300 · 54px/1 · tracking -0.02em

### Comparison and usage purchase blocks

**Observed:** A centered promise leads to four Plan cards; a billing control sits above at the right. Later purchase choices use two-column usage cards and three-column add-on cards with small mint labels, outlined frames and bottom-aligned actions.

**Transfer:** Use the pricing-specific frames and labels only where the user is making a commercial decision.

**Text style:** `plan-heading` — TWK Lausanne 400 · 36px/1 · tracking -0.01em

### Split FAQ

**Observed:** A 36px section title occupies the left; the wider right column contains FAQ rows with 24px questions, pale rules and small chevrons. Dark technical pages use a 54px title, white text and dark rules.

**Transfer:** Answer practical objections after demonstrations; do not expose all long answers simultaneously.

### Closing call and continuous directory

**Observed:** A near-black ending has 120px-scale inner breathing room, a 54px white statement on the left and a white action pill on the right; a secondary outlined action can accompany it. A fine dark divider precedes the five-column footer, with 80px directory padding and lower utilities. Sales-led technical pages replace the simple action pair with a two-column contact form opposite a large statement.

**Transfer:** End with one decisive invitation and maintain the dark ground through the footer. Use the form ending only when qualification is the primary conversion.

**Text style:** `heading` — TWK Lausanne 300 · 54px/1 · tracking -0.02em

## Page flow

**Storyline:** Broad promise → concrete working scene → trust → capability depth → outcomes and useful routes → objections → decisive invitation and directory.

### Broad marketing landing page

1. **Promise** — Centered light headline and compact subtitle.
2. **Product demonstration** — Audience-specific benefit, signup and layered human-interface scene.
3. **Trust** — Short proof statement and customer logos.
4. **Capability depth** — Interactive connected diagram, sculptural capability cards and dark product selector stage.
5. **Outcome proof** — Customer photograph and large quotation.
6. **Useful routes** — Soft band with resource navigation.
7. **Problem framing** — Three open prose columns under a centered statement.
8. **Closing call** — White action on dark statement band, followed by continuous directory.

**Transfer:** Use the reference's contrast between broad promise, specific working proof and playful objects without fixing the number or order of chapters.

### Sales-led technical product landing page

1. **Promise** — Dark centered identifier, promise, white sales action and video.
2. **Product demonstration** — Alternating square product scenes and short benefit text.
3. **Process explanation** — Step-based accordion beside focused product art.
4. **Capability proof** — Four outlined dark cards and a pricing contact strip.
5. **Objection handling** — Dark split FAQ.
6. **Closing conversion** — Large statement opposite paired contact fields and inquiry area.
7. **Directory** — Shared dark footer.

**Transfer:** Keep the immersive dark variant for a focused technical offering and use the final form to qualify interest.

### Platform overview

1. **Promise and conversion** — Centered promise, provider signup, email form and wide photographic product scene.
2. **Social proof** — Customer-logo row.
3. **Platform demonstration** — Dark selector stage.
4. **Capability chapters** — Saturated full-bleed paired demonstration cards.
5. **Problem framing** — Three explanatory columns and a compact related-content banner.
6. **Objection handling** — Light split FAQ.
7. **Closing call** — Dark action pair and directory.

**Transfer:** Use the colored immersive variant when explaining a broad platform's distinct domains, not for every ordinary section.

### Pricing and purchase education

1. **Commercial promise** — Centered statement above four comparison cards and billing control.
2. **Comparison** — Expandable all-features route.
3. **Value demonstration** — Tabbed product scene and compact rate explanation cards.
4. **Purchase mechanics** — Usage choices and add-on grids with mint labels.
5. **Trust** — Customer logos.
6. **Related offerings** — Dark paired product cards.
7. **Objection handling** — Long but visually collapsed FAQ list.
8. **Closing call** — Dark invitation and shared directory.

**Transfer:** Separate plan selection from usage mechanics and eligibility so commercial detail stays understandable.

### Feature discovery catalog

1. **Orientation** — Extra-large centered headline, short support and one capsule action.
2. **Capability chapters** — Category introductions and four-column cards, alternating mostly white with selected dark chapters.
3. **Ecosystem** — Soft band pairing introduction with integration tiles.
4. **Enablement** — Stacked support resource rows.
5. **Objection handling** — Split FAQ.
6. **Closing call** — Dark statement, supporting reassurance, action pair and directory.

**Transfer:** Make this variant navigable and modular; retain left alignment and open space in incomplete rows.

## Writing

Confident and practical, with warmth expressed through the benefits rather than jokes. High-level promises are followed quickly by concrete work, visible outcomes and straightforward mechanics.

**Do not copy:** Do not reuse Asana names, logos, character designs, product marks, customer logos, quotations, proprietary claims, organization counts, prices or performance figures. Source examples illustrate cadence only; replace them with substantiated content for the new product.

- **Addressing the reader:** Use 'you' and 'your team' for benefits, the product name for explanations and occasional 'we' for clear commitments.
- **Rhythm:** Headlines usually run 4–10 words, often across two short lines. Support is one or two direct sentences; parallel clauses and occasional em dashes keep complex capabilities readable.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A direct outcome for a team, not an abstract category slogan. | 5–10 words | “Supercharge your teams with AI”<br>“Ship faster with humans and agents in sync” |
| Benefit heading | A concise before-and-after contrast or a plain active verb. | 3–8 words | “Stop chasing. Start deciding.”<br>“Stay in flow” |
| Supporting line | Explain what changes in the work and who stays in control. | 12–35 words | “Connect every team’s work to company objectives, then track progress with real-time data.” |
| Primary action | A familiar verb plus a clear next step. | 2–4 words | “Get started”<br>“Contact sales” |
| Pricing explanation | State the mechanism plainly, then remove a specific uncertainty. | 5–20 words | “No rate cards, no surprises” |

**Words and phrasing to use:** your team; work together; connected; visibility; clear owners; ready to go; real-time; goals; workflows; built for scale

**Avoid:** revolutionary magic; unprecedented synergy; disrupt everything; effortless perfection; hacker slang; jokey button labels

**Rules:**

- Lead with a result, then explain the mechanism with concrete nouns.
- Use short contrasts to make the benefit memorable.
- For catalogs, use plain feature names and descriptions that say what the reader can do.
- For purchasing, spell out eligibility, billing and limits rather than hiding them in aspirational copy.
- Keep actions literal and familiar; reserve expressive language for headings.

## Do's and Don'ts

### Do

- Use 64px/1 lightweight type for the default promise and 54px/1 for major statements.
- Align full content to the 1288px desktop span with 32px gutters.
- Preserve 120px chapter padding and large 80–160px narrative pauses.
- Pair a dark demonstration with white readable interface objects.
- Use 8px card corners and fine #e7e7e7 edges for capability grids.
- Make selected product pills pink and inactive dark-stage pills charcoal.
- Give functional resource arrows a clear white-on-ink circular target.
- Keep the closing statement and footer on a continuous near-black ground.

### Don't

- Do not bold the 54px and 64px headlines into weight 700.
- Do not use the catalog's 80px headline as the universal display size.
- Do not turn every neutral feature card into a saturated tile.
- Do not apply pill corners to fields or ordinary content cards; they use 4px and 8px corners.
- Do not add external drop shadows to every marketing card; outlines do most of the work.
- Do not substitute a giant percentage counter for the restrained 30px proof statement.
- Do not use mint purchase labels as general decorative eyebrows.
- Do not make the persistent navigation dark just because the content beneath it is dark.

## Motion and responsive

### Motion

**Observed:**

- Declared: the compact signup pill and audience selectors transition background-color for 150ms and color for 150ms ease-in-out.
- Declared: common links and inverse actions transition color and border over 300ms.
- Declared: resource rows transition background-color over 0.25s ease-in-out; accordion discs transition transform over 200ms ease-in-out.
- Declared: immersive chapter background changes over 500ms ease-in-out, with color changing over 500ms after a 350ms delay.

**Transfer:**

- Use the short declared transitions to reinforce a changed audience, product or accordion selection without making the interface feel animated everywhere.
- Keep the routing graphic and connected scene understandable as static compositions.

**Unknown:**

- Exact playback behavior, scroll-trigger choreography and reduced-motion behavior are not established.

### Responsive

**Observed:**

- The desktop composition uses a twelve-column grid and wrapping product selector groups. The header is sticky and its right-side controls use 8px gaps.

**Transfer:**

- On narrow screens, retain the centered promise but stack benefit text and the collage; keep panels readable rather than shrinking all interface text.
- Collapse four-column grids progressively while preserving card padding and the left alignment of incomplete rows.
- Stack the closing call and sales form, and allow the capability carousel to retain intentional horizontal overflow.

**Unknown:**

- Mobile layouts and exact breakpoint-specific type sizes are not established; these stacking rules are recommendations rather than measured mobile behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
