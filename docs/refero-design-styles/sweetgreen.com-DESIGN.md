# Sweetgreen — sunlit appetite editorial

## Overview

An earthy, light-filled style that pairs oversized, close-set sans headlines with soft literary serifs and practical uppercase labels. Cream, sage and warm oat surfaces let richly colored photography supply most of the energy, with small flashes of electric yellow-green. It suits tangible products, welcoming services and purpose-led companies: spacious at the chapter level, candid and information-rich within the product rows.

### Essentials

- The opening is a photograph you can almost touch: a full-width 828px-tall scene, a close product-and-hands composition, and cream 80px/0.85 regular sans type anchored near its lower left.
- Headlines feel spoken rather than typeset into a corporate system: core section titles use SweetSans 70px/0.85 at weight 400, while 48px/1 light Grenette category titles bring a softer editorial counterpoint.
- Calls to action are small capsules against immense images: the default is a 46px-high chartreuse pill with 16px uppercase text and 60px horizontal padding; the navigation reverses this to a 30px forest pill.
- Color behaves like natural materials, not decoration: cream #f4f3e7 is the canvas, sage #d8e5d6 and oat #e8dcc6 occupy whole chapters, and chartreuse #e6ff55 stays concentrated in actions and small badges rather than page-sized fills.
- A tactile product stage is a signature device: use square 437px image fields with 20px corners, actual cast shadows and natural backing, followed by 24px uppercase names; if no physical object exists, stage a printed artifact or a real person using the product instead.
- The editorial spread is a signature device: a full-width 50/50 band, one half a large photograph and the other a flat natural color with 40px side padding and 43px top padding. Keep the text spare and let a small underlined arrow link sit low in the panel.
- The ending stays useful and communal: two equal cream signup/download panels divided by a 1px ink rule lead into a sage directory footer; use 24px support copy, 16px labels and a 50px outlined email field instead of an oversized final sales slogan.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep forest | `#00473c` | `--color-forest` | action, text, background | Default action ink, compact navigation button fill; large dark bands belong to service conversion pages. |
| Warm oat | `#e8dcc6` | `--color-oat` | background, surface | Editorial split panels and portrait-card backing. |
| Pale sage | `#d8e5d6` | `--color-sage` | background, surface | Large editorial bands and the directory footer. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric chartreuse | `#e6ff55` | `--color-lime` | action, accent, text | Primary capsule fills, small availability badges and reversed navigation action text. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Leaf-black ink | `#0e150e` | `--color-ink` | text, border | Default text and fine structural rules. |
| Dry gray-green | `#8c8c82` | `--color-muted` | text | Inactive editorial category navigation. |
| Cream paper | `#f4f3e7` | `--color-canvas` | background, text | Main canvas, navigation and reversed campaign text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| service conversion pages | Spinach green | `#2d6b52` | `--color-spinach` | text, action | White-button text and green hover fills; also used at 12% alpha for secondary actions. |
| company storytelling and service pages | Avocado sage | `#a9c1a9` | `--color-avocado` | background, border | Stronger story-panel background; outlined occasion chips and numbered circles. |
| catalog closing promotions | Blue ink | `#203e70` | `--color-blue-ink` | text | Serif promotional text on pastel tiles. |
| catalog closing promotions | Pale blue | `#d6e9e9` | `--color-sky` | surface | One supporting promotional tile beside cream and sage tiles. |
| service conversion pages | Soft charcoal | `#484d48` | `--color-secondary` | text, border | Supporting copy and focus outlines. |
| service question lists | Translucent forest rule | `#b9cabe` | `--color-faq-rule` | border | Forest at 24% over cream; on sage the same rgba rule takes on the underlying sage tint. |
| service conversion pages | Clean white | `#ffffff` | `--color-white` | surface, text, action | Raised information panels, service-format cards and hero buttons. |

## Typography

- **SweetSans** — Campaign headlines and major editorial titles. Open, rounded geometric sans with a low, easygoing regular-weight voice and broad circular forms. If unavailable, use **DM Sans**. Use weight 400 and preserve the unusually tight 0.85 headline line height. Font stack: "SweetSans", "DM Sans", SweetSansText, system-ui, sans-serif.
- **SweetSansText** — Body copy, uppercase names, labels, actions and directories. Practical geometric sans, regular by default, with clear capitals and compact information density. If unavailable, use **DM Sans**. Font stack: "SweetSansText", "DM Sans", system-ui, sans-serif.
- **Grenette** — Category navigation and editorial headings; larger statements on storytelling and catalog pages. Soft bracketed serifs, friendly irregularity and tightly fitted light-weight display texture. If unavailable, use **Lora**. Use the lightest available cut and retain role-specific negative tracking. Font stack: "Grenette", "Lora", Georgia, Cambria, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | SweetSans | 400 | 80px | 0.85 | normal | Cream campaign headline on full-bleed photography. |
| heading-lg | SweetSans | 400 | 70px | 0.85 | normal | Main editorial and feature-section headings. |
| category | Grenette | 200 | 48px | 1 | -0.046875em | Large category controls; use title case and center within the category row. |
| editorial-support | SweetSans | 400 | 40px | 1 | normal | Short, oversized supporting paragraph within a split editorial band. |
| item-title | SweetSansText | 400 | 24px | 1.2 | 0.03em, uppercase | Product-card names. |
| body-lg | SweetSansText | 400 | 24px | 1.2 | normal | Editorial feature explanations, signup support and platform links. |
| body | SweetSansText | 400 | 18px | 1.25 | normal | Product descriptions and simple text links. |
| eyebrow | SweetSansText | 400 | 16px | 1 | normal, uppercase | Section labels, navigation and primary action text. |
| directory | SweetSansText | 400 | 16px | 22px | normal | Footer link columns and compact supporting information. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| catalog pages | catalog-opening | Grenette | 200 | 80px | 1 | -0.04375em | Centered three-line introductory promise. |
| company storytelling | story-title | SweetSans | 400 | 80px | 1 | normal | Chapter name at the top of a split panel. |
| company storytelling | story-statement | Grenette | 200 | 80px | 1 | -0.0225em | Long statement wrapped into a narrow half-width column. |
| service conversion pages | service-opening | Grenette | 300 | 80px | 1 | -0.06em | Two-line white headline over darkened photography. |
| catalog pages | catalog-heading | Grenette | 200 | 48px | 1 | -0.046875em | Left-aligned product-family titles above grids. |
| company storytelling | story-subheading | Grenette | 400 | 48px | 1 | -0.046875em | Large prose leads between visual chapters. |
| service conversion pages | service-faq-heading | SweetSans | 400 | 40px | 1 | 0.02em | Left column heading beside question rows. |
| people and partner profiles | portrait-title | Grenette | 200 | 32px | 1 | -0.05625em | Caption beside a circular flip control. |
| service conversion pages | service-heading | SweetSans | 400 | 32px | 36px | 0.0313em | Centered section titles and service-format card headings. |
| company storytelling | story-body | SweetSansText | 400 | 20px | 1.25 | normal | Indented explanatory paragraphs and plus-prefixed principles. |
| service conversion pages | service-body | SweetSansText | 400 | 18px | 24px | -0.011em | Hero support and question titles. |
| service conversion pages | service-action | SweetSansText | 400 | 18px | 22px | normal | Sentence-case text in larger white hero capsules. |
| catalog specifications and service chips | stat-number | SweetSansText | 400 | 16px | 1 | normal | Small values above labels; also plain text inside occasion chips. |
| catalog specifications | stat-label | SweetSansText | 400 | 16px | 1 | 0.08em, uppercase | Compact labels below numbers, in forest green. |
| people and partner profiles | flip-label | SweetSansText | 400 | 16px | 62px | normal, uppercase | Centered label inside the 60px circular control. |

**Notes:**

- Keep the two sans families distinct in role: display titles are broad and tightly stacked, while product information uses the text face with more breathing room.
- Do not apply the serif's negative tracking to the default sans headlines. Large sans titles use normal tracking and create their compactness through line height.
- The default marketing headline is sans. Serif 80px headlines belong to catalog, service and company-story variants; do not average their tracking into one recipe.
- Use regular weight for nearly everything. Bold underlined feature links are local emphasis, not a heavy heading system.

## Layout

**Density:** Airy between chapters, compact inside descriptions and directory lists; large photographs do the work of filling space.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Product name-to-description gap and small action/icon spacing. |
| 16px | Signup form offset, compact content stacks and service hero row gaps. |
| 20px | Eyebrow-to-campaign-title and title-to-action separation. |
| 23px | Declared default stacked-copy spacing. |
| 24px | Product columns, image-to-title gap and common content separation. |
| 30px | Portrait-card side padding and editorial label separation. |
| 40px | Desktop side gutters and editorial text-panel inset. |
| 43px | Editorial band vertical inset and footer utility-panel padding. |
| 48px | Catalog row gaps and footer directory top padding. |
| 54px | Three-step service instruction column gap. |
| 64px | Service-section vertical padding. |
| 70px | Space around the marketing category/product carousel. |
| 100px | Story prose interludes and catalog opening margins. |
| 120px | Separation between catalog product families. |

### Containers and grids

- **Main container**: max width 1440px · side padding 40px. Centered desktop content; full-bleed color and media extend outside it.
- **Product grid**: 3 columns · gap 24px. Three equal 437px product columns inside a 1360px content area; catalog rows use 48px vertical gaps.
- **Editorial split**: 2 columns · gap 0px. Equal 720px halves at desktop; edge-to-edge image opposite a text panel.
- **Inset feature split**: 2 columns · gap 43px. Two 659px columns inside the main container; square image opposite benefit links and a large heading.
- **Story prose grid** (only for company storytelling): 12 columns · gap 24px. A wide 1014px serif lead begins one column in; a narrower 668px body paragraph sits farther to the right.
- **Service container** (only for service conversion pages): max width 1226px · side padding 40px. Centered narrower service content; two 561px format cards separated by 24px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Action capsules | 9999px (pill) |
|  | Product media and portrait cards | 20px |
|  | Newsletter input | 10px |
| service conversion pages | Service format cards | 24px |
| service conversion pages | Service hero and raised process panel | 32px |
| people and partner profiles | Flip control | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| service conversion pages | Process panel | `8px 8px 8px 8px rgba(14, 21, 14, 0.03)` | Very soft lift for the white process panel overlapping the hero. |
| service occasion clouds | Floating central action | `0px 0px 41px 0px rgba(0, 0, 0, 0.3)` | A dark capsule floats over the middle row of outlined chips. |

### Surfaces

#### Cream canvas · level 0

**Use:** Default page and navigation background.

**CSS:** `background-color: #f4f3e7; color: #0e150e`

#### Sage band · level 0

**Use:** Feature chapters and footer directory.

**CSS:** `background-color: #d8e5d6; color: #0e150e`

**Observed:** Flat, full-width color without texture, outline or elevation.

**Transfer:** Let photography supply texture while the adjacent panel remains a solid field.

#### Oat spread · level 0

**Use:** Warm editorial split chapter.

**CSS:** `background-color: #e8dcc6; color: #0e150e`

#### Forest service band · level 0

**Only for:** service conversion pages

**Use:** Hero surround and service-format chapter.

**CSS:** `background-color: #00473c; color: #ffffff; padding: 64px 40px`

**Transfer:** Use the dark chapter to group decision-making content, not as the default page theme.

#### White service card · level 1

**Only for:** service conversion pages

**Use:** Two service formats with photography above content.

**CSS:** `background-color: #ffffff; border-radius: 24px; overflow: hidden`

**Observed:** Wide landscape photo occupies roughly the upper half; eyebrow, title, explanation and paired pills sit below.

#### Dark photographic overlay · level 1

**Only for:** service conversion openings

**Use:** Legible white text over a rounded inset photograph.

**CSS:** `background-color: rgba(0, 0, 0, 0.6); border-radius: 32px`

**Transfer:** Keep the underlying image recognizable; this is not a flat charcoal panel.

#### Pastel promotional tiles · level 0

**Only for:** catalog closing promotions

**Use:** Tall, three-up next-step promotions.

**CSS:** `background-color: #d8e5d6; border-radius: 20px`

**Observed:** A 700px-tall row mixes cream, sage and pale blue, with centered 48px serif messages and lime capsules. Blue ink distinguishes the supporting tiles.

**Transfer:** Use real next steps and fully rendered messages rather than decorative empty tiles.

## Components

### Navigation

**Use:** Persistent site-level orientation.

**CSS:** `background-color: #f4f3e7; height: 72px; padding: 0px 40px; position: sticky; z-index: 10`

**Text style:** `eyebrow` — SweetSansText 400 · 16px/1 · uppercase

**Observed:** A centered wordmark is balanced by two groups of links, with 35px gaps within each group. A compact action finishes the right side. Links are uppercase and otherwise undecorated.

**States:** Declared: hover links underline with 2px underline offset.

**Transfer:** Center the new identity independently of the two navigation groups; retain the balanced low strip.

### Primary button

**Use:** Default marketing conversion action.

**CSS:** `background-color: #e6ff55; color: #00473c; border: 1px solid transparent; border-radius: 9999px; padding: 15px 60px 13px; height: 46px`

**Text style:** `eyebrow` — SweetSansText 400 · 16px/1 · uppercase

**Observed:** A low, broad capsule below the headline, not a tall rectangular control. Arrow glyphs appear on some promotional versions.

**States:** Declared: hover color #F4F3E7; background-color #00473C; border-color #00473C; opacity 1.

### Compact navigation action

**Use:** Rightmost navigation conversion.

**CSS:** `background-color: #00473c; color: #e6ff55; border: 1px solid transparent; border-radius: 9999px; padding: 7px 16px 5px; height: 30px`

**Text style:** `eyebrow` — SweetSansText 400 · 16px/1 · uppercase

**Observed:** Reverses the main capsule's color emphasis and fits within the quiet navigation strip.

**States:** Declared: hover color #0E150E; background-color transparent; border-color #0E150E; opacity 1.

### Category tabs

**Use:** Large editorial controls above a product selection.

**CSS:** `background-color: transparent; color: #8c8c82; border-radius: 4px; height: 48px`

**Text style:** `category` — Grenette 200 · 48px/1 · tracking -0.046875em

**Observed:** Centered text-only controls. Selected text turns ink and a small round dot sits underneath; inactive labels remain gray-green.

**States:** Declared: hover and active color #0e150e with transparent background; focus-visible outline-color #e59700.

**Transfer:** Use a few broad categories, not a dense toolbar of tiny chips.

### Product card

**Use:** Image-first product introduction or catalog entry.

**CSS:** `display: flex; flex-direction: column; color: #0e150e`

**Text style:** `item-title` — SweetSansText 400 · 24px/1.2 · tracking 0.03em · uppercase

**Observed:** No enclosing painted card. A square photograph with 20px corners leads to an uppercase name after 24px, then body copy after 8px. Detail or disclosure copy is separated below, followed by an underlined text action. Small lime badges sit in the image's upper corner. Catalog variants replace the action with a three- or four-column forest specification strip: 16px numbers above tracked uppercase labels.

**Transfer:** Use the specification strip only for useful comparable facts; do not turn its small numbers into oversized KPI tiles.

### Newsletter field

**Use:** Email entry in the closing utility panel.

**CSS:** `border: 1px solid #0e150e; border-radius: 10px; height: 50px; padding: 12px 50px 12px 16px`

**Observed:** A single full-width field, 640px across on desktop, with a bare right-arrow submit control inside its right edge. The heading and 24px explanation sit above it.

**Transfer:** Keep one field and one in-field action rather than building a multistep form.

### Directory footer

**Use:** Shared final navigation and legal information.

**CSS:** `background-color: #d8e5d6; padding: 48px 40px 42px; display: flex; gap: 40px`

**Text style:** `directory` — SweetSansText 400 · 16px/22px

**Observed:** Four compact link columns group company, social, support and legal destinations; small copyright information sits to the far right. Uppercase column labels use the same 16px scale, not large headings.

**Transfer:** Keep the directory information-dense and subordinate to the two utility panels above it.

### Portrait flip card

**Only for:** people and partner profiles

**Use:** Human proof with a short narrative on the reverse.

**CSS:** `background-color: #e8dcc6; border-radius: 20px; position: relative`

**Text style:** `portrait-title` — Grenette 200 · 32px/1 · tracking -0.05625em

**Observed:** Three equal 437px by 547px cards. A photograph sits within 30px side insets, uncropped where possible; varying portrait and landscape image proportions are retained. A serif name shares the bottom row with a 60px outlined circular FLIP control. The reverse contains a bold name and explanatory copy.

**States:** Declared: hover flip control background-color #0E150E; border-color #0E150E; color #F4F3E7; opacity 1.

**Transfer:** Use portraits in their real working environments; the reverse should add concrete context.

### Question row

**Only for:** service conversion pages

**Use:** Objection handling in a two-column FAQ section.

**CSS:** `display: flex; justify-content: space-between; padding: 24px 16px; min-height: 72px; color: #00473c; border-bottom: 1px solid rgba(0, 71, 60, 0.24)`

**Text style:** `service-body` — SweetSansText 400 · 18px/24px · tracking -0.011em

**Observed:** Question text aligns left; a 24px thin chevron sits at the far right. Rows form one quiet vertical list rather than separate filled cards.

**States:** Declared: hover background-color rgba(0, 71, 60, 0.05); border-color #0E150E; color #F4F3E7; opacity 1; focus-visible outline #484d48 solid 1px with 2px offset.

### Occasion chip

**Only for:** service occasion clouds

**Use:** A cloud of short use cases surrounding a central action.

**CSS:** `border: 1px solid #a9c1a9; border-radius: 64px; padding: 20px 24px; color: #00473c`

**Text style:** `stat-number` — SweetSansText 400 · 16px/1

**Observed:** Sentence-case outlined capsules wrap into three centered rows with 8px horizontal and 16px vertical gaps. A shadowed forest action overlaps the middle, with a subtle white radial clearing behind it.

**Transfer:** Replace occasions with product-relevant contexts or audiences, not feature buzzwords.

### White service button

**Only for:** service conversion openings

**Use:** Paired hero actions over darkened imagery.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; background-color: #ffffff; color: #2d6b52; border-radius: 9999px; padding: 20px 24px; height: 64px`

**Text style:** `service-action` — SweetSansText 400 · 18px/22px

**Observed:** Sentence-case label followed by a thin right arrow. Two same-weight actions sit side by side with 16px separation.

**States:** Declared: hover color #FFF; background-color #2D6B52; border-color #0E150E; opacity 1; focus-visible outline #484d48 solid 1px with 2px offset.

### Process panel

**Only for:** service conversion pages

**Use:** An approachable instruction block overlapping a hero.

**CSS:** `background-color: #ffffff; border-radius: 32px; padding: 64px 56px; box-shadow: 8px 8px 8px 8px rgba(14, 21, 14, 0.03); margin-top: -134px`

**Observed:** A centered serif heading and short explanation precede three horizontal steps. Each has a 48px outlined numbered circle, a short serif title and a small explanation. The panel is narrower than the hero image.

**Transfer:** Describe a genuine three-step process; preserve the overlap and modest elevation rather than adding a dashboard treatment.

## Imagery and graphics

### Sunlit product-in-hand campaign

**Use:** Default marketing opening; the most immersive image on the page.

**Observed:** Extreme close view of a product held against cream ribbed clothing, with hands, jewelry and red nails bringing human scale. Warm directional sunlight reveals paper, fabric and food texture. The central object dominates while the lower-left darkened area supports cream type.

**Transfer:** Photograph the product in use, close enough to show touch and materials. For a digital offering, show a person's hands interacting with a physical device or printed output in equally warm light; avoid a floating interface rectangle.

**Build:** Use an edge-to-edge cover photograph. Keep the object near center, leave lower-left tonal space for text, and add a transparent-to-dark bottom gradient only as needed for legibility; do not flatten the sunlit highlights.

### Square tactile catalog stage

**Use:** Product grids and the required product-stage device.

**Observed:** Overhead or slightly elevated objects are centered on light gray plaster-like surfaces; bowls nearly fill the square while packaged drinks retain more surrounding air. Actual side-lit cast shadows add depth. The pale gray belongs to the photographed set, not a separate UI card fill.

**Transfer:** Shoot a consistent set on a matte pale surface with one directional light, accurate colors and visible texture. Use a printed artifact, toolkit or device for nonphysical services. Keep framing consistent across each product family.

### Editorial material still life

**Use:** Inset feature image and full-height editorial split.

**Observed:** Rich green produce spills around stacked neutral containers on wood-and-green shelving; another composition arranges glass jars, small bowls, herbs and oil on a worn wooden board beside a metal worktop. Saturation comes from real ingredients, with warm wood, soft shadows and crisp tactile detail. The image occupies roughly half the band.

**Transfer:** Arrange the new product's tools, raw materials or outputs on a real working surface. Retain wood, glass, paper or metal texture and generous image scale; a simple photographed working kit is the minimum acceptable version.

### Documentary people and places

**Only for:** company storytelling and partner profiles

**Use:** Full-height story spreads and closing profile cards.

**Observed:** Bright storefront architecture, an evening first location and candid people beside equipment or among crops. Human portraits vary in aspect ratio and retain their real surroundings. No duotone, heavy vignette or glossy studio isolation.

**Transfer:** Show where the work happens and the people who do it. Alternate broad environmental scenes with intimate process detail, keeping natural color and believable light.

### Occasion cloud clearing

**Only for:** service occasion clouds

**Use:** Subtle separation behind the central floating action.

**Observed:** Outlined pills remain visible around a soft white clearing; the action carries a broad dark shadow.

**Transfer:** Use the graphic to bring one action forward without adding a decorative illustration.

**Build:** Center a roughly 220px by 206px absolute layer behind the action with radial-gradient(circle, rgb(255, 255, 255) 0%, rgba(255, 255, 255, 0) 20%). Layer the forest pill above it with a 0px 0px 41px rgba(0,0,0,0.3) shadow; keep surrounding chips in normal wrapping flow.

### Icons

**Observed:** Actions use plain right-arrow glyphs or 24px outlined SVG arrows and chevrons; service icons use forest/spinach strokes at 1.5px with rounded caps. A service-benefit row uses simple 48px line illustrations.

**Transfer:** Prefer a few thin, rounded line icons in forest. Use arrows for movement and chevrons for expansion; do not introduce multicolor icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Immersive campaign opening

**Observed:** A thin 41px accessibility utility strip precedes the 72px cream Navigation. Beneath it a full-width 1440px by 828px photograph fills almost all the remaining first screen. From back to front: warm close-up product-in-hand image, subtle lower tonal darkening, then cream eyebrow and display headline, then Primary button. Text is left-aligned within the 40px gutter near the bottom; the 80px/0.85 headline spans about two thirds of the width. The object remains central and much larger than the action. Within the first 900px the navigation, main object, eyebrow, headline and lime capsule are visible; there is no separate support paragraph. The image bottom and next product-selection section continue below the fold.

**Transfer:** Create the same image-led first impression with a new product-in-use scene, a short topical eyebrow and a direct product or benefit name. Without specialist media, photograph a person's interaction with the product or its tangible output in warm side light. Catalog openings instead use a centered 80px serif promise on cream; story openings use large category links followed by a 50/50 colored spread; service openings use a rounded darkened photo inset in forest with paired white actions.

**Avoid:** Do not replace this opening with centered black text above a small cutout, a floating app dashboard or a pile of promotional cards. Do not give the campaign headline the serif treatment used by the scoped openings.

**Text style:** `display` — SweetSans 400 · 80px/0.85

### Category-led product stage

**Observed:** Category tabs sit centered above a three-column Product grid on Cream canvas. Each Product card gives its square photograph most of the visual area; there is no box around the text. The marketing version has 70px breathing room around the overall block.

**Transfer:** Use a small set of comparable offerings with tactile product images and concise descriptions; category controls should change a meaningful selection.

### Inset feature spread

**Observed:** Sage band holds a small uppercase label, a heading-lg title and three bold underlined feature links with body-lg explanations on the left; a 659px square rounded image balances it on the right. Main container gutters are 40px and the column gap is 43px.

**Transfer:** Use the text side to explain a family of use cases or ways to engage; let the still life convey abundance and material quality.

### Full-bleed editorial spread

**Observed:** Oat spread divides into equal halves with a 720px by 828px edge-to-edge photograph on one side. The text half has a 16px uppercase label, a 70px compact sans heading, a 40px supporting paragraph and a small underlined arrow link anchored near the bottom.

**Transfer:** Make one evocative chapter about craft, learning or use, rather than another feature grid. Carry the product's real working materials into the photograph.

**Text style:** `heading-lg` — SweetSans 400 · 70px/0.85

### Utility close and directory

**Observed:** Two equal cream panels begin with a thin top rule and central divider. Newsletter field sits below an uppercase label and 24px explanation in the left panel; platform links and a small playful app image sit in the right. Each panel uses 43px by 40px padding and is roughly 248px tall. Directory footer follows as a 296px sage band, completing the 545px shared ending.

**Transfer:** Retain this useful, modest ending on a new landing page: subscription or updates on one side, a second practical access route on the other, then compact grouped links. Use a small product token instead of a huge logo or final hero.

### Story chapter and prose interlude

**Only for:** company storytelling

**Observed:** A full-width colored 50/50 spread pairs story-title with a long story-statement and a full-height photograph. Sage, avocado and oat distinguish chapters; image side alternates. Between spreads, Cream canvas supports a 48px serif prose lead and a narrower 20px paragraph indented to the right, with 100px margins around the interlude.

**Transfer:** Use chapter labels for the new organization's purpose, origins or working principles. Keep the contrasting serif statement and sans title, not a generic timeline.

**Text style:** `story-statement` — Grenette 200 · 80px/1 · tracking -0.0225em

### Service conversion suite

**Only for:** service conversion pages

**Observed:** A Forest service band surrounds a 1360px by 492px photographic hero with 32px corners, a dark overlay, service-opening headline and two White service buttons. Process panel overlaps its bottom. Later a forest chapter pairs two White service cards beneath a centered 32px heading, followed by an Occasion chip cloud and a four-column line-icon benefit strip.

**Transfer:** Use this more contained, rounded variant for an offer that needs format selection and reassurance. Keep the photo warm and concrete rather than switching to abstract service illustrations.

**Text style:** `service-opening` — Grenette 300 · 80px/1 · tracking -0.06em

### Quiet objection handling

**Only for:** service conversion pages

**Observed:** A Sage band places service-faq-heading and one support line in the left column, with Question rows in a wider right column. A separate white section follows with a centered 32px help heading, brief explanation and two subdued pills before the shared footer.

**Transfer:** Answer practical purchase questions in short rows, then provide a human-help route rather than another hard-sell banner.

**Text style:** `service-faq-heading` — SweetSans 400 · 40px/1 · tracking 0.02em

### Catalog opening and specification grid

**Only for:** catalog pages

**Observed:** An 80px serif statement is centered in a wide cream header with 100px margins. Left-aligned 48px serif family headings lead into three-column Product cards. Small forest numbers and uppercase labels form aligned specification strips beneath descriptions, with 48px row gaps and 120px family separation.

**Transfer:** Organize a large assortment into clear families. Use the micro-stat strip for meaningful comparable product facts, not invented performance claims.

**Text style:** `catalog-opening` — Grenette 200 · 80px/1 · tracking -0.04375em

### Closing profile or promotion row

**Only for:** company storytelling and catalog pages

**Observed:** The story variant ends its main content with three Portrait flip cards, followed by 100px space before the shared footer. The catalog variant uses three tall Pastel promotional tiles for useful next steps before its footer.

**Transfer:** End long informational content with either human context or a few distinct next steps. Do not force a single universal closing sales banner.

## Page flow

**Storyline:** Immersive promise → concrete offerings or working principles → deeper context and practical reassurance → useful next steps → shared utility close.

### A broad product marketing landing page

1. **Promise** — Full-bleed human-scale campaign photograph, lower-left name and compact lime action.
2. **Product demonstration** — Serif category controls and three image-led offerings.
3. **Use cases** — Sage split with compact large sans heading, linked explanations and a square still life.
4. **Deeper engagement** — Oat editorial spread with a process photograph and low-positioned social/tutorial link.
5. **Ongoing relationship** — Two utility panels above a sage directory.

**Transfer:** Adapt the topic and number of middle chapters, but retain the product stage, editorial spread and useful close.

### A service landing page that converts group or custom purchases

1. **Promise** — Inset photographic hero on forest with a white serif headline and paired white actions.
2. **How it works** — Overlapping three-step white Process panel.
3. **Offer comparison** — Two image-topped white format cards on a forest band.
4. **Use cases** — Outlined occasion cloud with a floating central action.
5. **Reassurance** — Four small line-icon benefits and a quiet two-column FAQ.
6. **Human assistance** — Centered help block on white, then the shared utility close.

**Transfer:** Use the scoped rounded white-card language for an offer requiring selection, timing or fulfillment explanations.

### A comprehensive product catalog

1. **Promise** — Centered serif introductory statement on cream.
2. **Assortment exploration** — Repeated serif family headings and three-column image-led grids, each with compact specification rows.
3. **Next steps** — Three tall cream, sage and pale-blue promotional tiles.
4. **Ongoing relationship** — Shared signup/download panels and sage directory.

**Transfer:** Let product families determine length; maintain consistent image framing, small facts and generous inter-family separation.

### A company story that connects principles to real people

1. **Orientation** — Large serif chapter links with an active dot.
2. **Purpose** — Avocado split spread with a sans label and long serif statement.
3. **Context** — Indented prose interlude on cream.
4. **Origins and principles** — Alternating oat and sage photographic spreads, each followed by explanatory prose.
5. **Human proof** — Three warm-backed portrait flip cards.
6. **Ongoing relationship** — Shared utility close and directory.

**Transfer:** Alternate monumental visual statements with narrower supporting prose; finish with people who substantiate the story.

## Writing

Welcoming, conversational and materially specific. It moves easily between playful campaign naming and earnest explanations, making everyday usefulness feel pleasurable rather than technical.

**Do not copy:** Do not reuse Sweetgreen names, product names, partner identities, trademarks, collaboration signatures, recipes, proprietary claims, historical facts or service promises. Source examples illustrate voice only.

- **Addressing the reader:** Speak directly to you and your needs; use we and our for the people behind the product. Calls to action are direct verbs, not impersonal interface jargon.
- **Rhythm:** Campaign names and section headings are usually short and punchy; support is one conversational sentence. Longer purpose statements are allowed to wrap into large serif paragraphs, with concrete explanatory prose underneath.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Campaign eyebrow | A tiny playful reveal before a direct product name. | 3–6 words | “Surprise! There’s a Pickle” |
| Editorial heading | Invite the reader into a place or activity; use plain verbs. | 5–10 words | “Step inside the sweetgreen kitchen” |
| Benefit heading | Repeat an everyday word with a light verbal twist. | 7–12 words | “All the ways we keep your workplace working” |
| Supporting line | Address a broad practical need with a warm, sensory phrase. | 8–20 words | “The freshest way to fuel groups big or small” |
| Primary action | Short action verb plus object only when needed; arrows can signal onward movement. | 1–4 words | “Order now”<br>“View catering menu” |
| Purpose statement | State an ambition through people and action, not a string of abstract virtues. | 10–20 words | “Building healthier communities by connecting people to real food” |
| Practical question | Ask exactly what a buyer would ask, in the first person. | 5–12 words | “How do I place an order?” |

**Words and phrasing to use:** you / your; we / our; fresh, real and made; step inside; big or small; everyday verbal play; occasional + in short phrases

**Avoid:** revolutionary platform; unlock unprecedented value; seamless ecosystem; aggressive scarcity; technical superlatives without explanation

**Rules:**

- Let one playful phrase carry the campaign; keep the practical explanation straightforward.
- Name materials, actions and contexts instead of stacking adjectives.
- Use uppercase as a visual label convention, not as a shouting tone in paragraphs.
- Pair broad purpose statements with specific descriptions of work and relationships.
- Keep action labels short; reserve conversational warmth for the surrounding sentence.

## Do's and Don'ts

### Do

- Keep campaign type at 80px/0.85, weight 400, with normal tracking.
- Make ordinary major editorial titles 70px/0.85 rather than shrinking every heading to a generic 48px.
- Use 40px desktop gutters and 24px product-column gaps.
- Give product photographs 20px corners while leaving their text unboxed.
- Keep the default lime capsule 46px high with 60px horizontal padding.
- Include a half-width tactile image in a flat sage or oat editorial chapter.
- Use 16px forest micro-stat strips for catalog facts, not giant metrics.
- Finish with equal cream utility panels and a sage directory with 16px links.

### Don't

- Do not turn chartreuse into a full-page background; its concentrated button and badge use is the point.
- Do not add heavy bold sans headings; the core display system is weight 400.
- Do not substitute pure white for the default cream canvas.
- Do not wrap every product description in a bordered or shadowed white card; those raised cards belong to the service variant.
- Do not add ambient glows or gradients to ordinary color bands; the broad surfaces are flat.
- Do not standardize all imagery into transparent cutouts; retain real backing, texture and cast shadows.
- Do not set all serif tracking to one value; catalog openings, story statements and category labels have distinct fits.
- Do not enlarge footer columns into promotional headlines or replace the shared utility ending with a giant final CTA.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare 0.3s ease-in-out transitions; text links commonly declare color 0.3s ease-in-out.
- Category controls declare color and outline-color 0.24s ease-in-out.
- Editorial media sections declare opacity 0.25s ease-in-out.
- Portrait flip cards declare transform 0.75s cubic-bezier(0.45, 0.05, 0.55, 0.95).

**Transfer:**

- Use the declared color reversals for capsules and category selection, and preserve the deliberate longer flip transition only for profile cards.

**Unknown:**

- Exact reveal triggers, carousel timing and autoplay behavior are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 768px, 1024px, 1280px and 1440px; only the desktop composition is established.

**Transfer:**

- On narrow screens, preserve the image-first campaign and lower-left text relationship. Stack editorial halves and product columns while retaining the distinction between full-bleed spreads and inset product photography.
- Keep the signup field and its arrow as one control; stack the two footer utility panels rather than compressing their content side by side.

**Unknown:**

- Mobile font sizes, exact breakpoint-specific grid changes and navigation behavior are not established. These narrow-screen arrangements are transfer guidance, not measured layouts.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
