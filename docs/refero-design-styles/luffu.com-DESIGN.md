# Luffu — technology in human light

## Overview

A people-first technology style with editorial softness and the warmth of a lived-in home. Cream and sage surfaces, blue-black lettering, flared serif headlines and a restrained sans-serif support cinematic lifestyle photography and tactile product close-ups. It suits companion products and services that make complicated routines feel easier, with spacious storytelling above more practical product information.

### Essentials

- Human context is the main stage: an edge-to-edge 861px-tall photographic opening puts a 48px/1 regular flared-serif promise in a 504px-wide upper-left column, leaving most of the view to people and their surroundings.
- Headlines feel spoken rather than engineered: ABCArizonaFlare at weight 400, 48px/1 with -2px tracking for the main promise, 44px/1 for section leads, and 64px/1 for the shared reassurance call.
- Actions are modest rectangular invitations, not pills: 6px corners, 44px height, 16px/1.2 sans text and a fine right arrow; the opening action sits inside a 359×124px warm translucent panel.
- Color lives in light and materials rather than interface chrome: cream and sage occupy the structural bands, blue-black anchors text, and muted rose, lilac, ochre and blue appear in photography and a full-width atmospheric fabric-like interlude. Include this softly colored interlude on every new landing page; a blurred layered gradient is the fallback.
- Product discovery reads like a photo editorial: three 437×583px portrait cards with 24px gutters, 8px corners, text above the object and an arrow near the lower-left edge. If physical products are unavailable, stage real interface views on warm textured surfaces.
- The closing invitation feels like companionship: a centered 64px reassurance line above six overlapping 56px circular portraits, followed by a 1192px-wide, 52px-high white newsletter action on sage. Preserve the portrait cluster and wide invitation bar with people relevant to the new offering.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sage interaction | `#cdd3bb` | `--color-sage-hover` | action, surface | Button hover fill and backing behind circular portraits. |
| Pale sage | `#e4e7da` | `--color-sage` | background, surface | Shared closing invitation, footer and product-family section backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue-black ink | `#192830` | `--color-ink` | text, action, border, background | Headlines, dark actions, announcement strip and fine rules. |
| Charcoal body | `#2f3136` | `--color-body` | text | Paragraphs and footer links. |
| Muted navigation ink | `#4e5a5e` | `--color-nav-text` | text | Default light-header navigation text; inverse white text over dark photography. |
| Sage divider | `#a7aea3` | `--color-footer-rule` | border | Visible blue-black at 0.3 alpha over sage for footer dividers. |
| Stone canvas | `#d7d7cb` | `--color-canvas` | background | Underlying canvas and neutral backing for light atmospheric media. |
| Warm invitation veil | `#e0dcd0` | `--color-warm-glass` | surface | Visible equivalent of warm cream #f4e7dc at 0.3 alpha over stone; actual photographic backing changes its apparent hue. |
| White header veil | `#ecece7` | `--color-header-glass` | surface | Visible equivalent of white at 0.533 alpha over stone; retain translucency over imagery. |
| Warm ivory | `#f6f7f0` | `--color-cream` | background, text, border | Light editorial bands and inverse text and outlines over photography. |
| Action white | `#ffffff` | `--color-white` | surface, text, action | Newsletter bar, light purchase buttons and selected carousel markers. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| immersive scenario chapters | Daytime sky | `#b5ddff` | `--color-sky` | background | Cool diagonal gradient fading to ivory. |
| premium hardware finish showcases | Gold sand | `#d2b394` | `--color-gold-sand` | background | Top of warm material-showcase gradient. |
| immersive scenario chapters | Morning blush | `#ffd2cd` | `--color-blush` | background | Soft diagonal gradient fading to ivory. |
| premium hardware finish showcases | Champagne backing | `#e2cfb8` | `--color-champagne` | background | Left edge of the complementary close-up panel. |
| immersive scenario chapters | Evening mist | `#d7ebf7` | `--color-mist` | background | Cool pale wash with a short flat color stop before ivory. |
| premium hardware finish showcases | Champagne light | `#ede0cf` | `--color-champagne-light` | background | Right edge of the complementary close-up panel. |
| premium hardware finish showcases | Gold ivory | `#eee3d2` | `--color-gold-ivory` | background | Bottom of warm material-showcase gradient. |
| product-detail tables and questions | Paper hairline | `#d4d6d2` | `--color-fine-rule` | border | Visible blue-black at 0.15 alpha over technical paper. |
| product-detail and company-story sections | Technical paper | `#f5f5ee` | `--color-paper` | background | Specification, packaging and question sections; also the editorial naming section. |
| product-detail feature grids | Feature porcelain | `#fcfcfa` | `--color-porcelain` | background | Backing around inset feature photography. |

## Typography

- **ABCArizonaFlare** — All editorial headings, product-card titles and invitation-panel titles. A softly flared serif with a contemporary, open construction; regular weight feels humane rather than ceremonial. If unavailable, use **Lora**. Use 400; tune line breaks to preserve the compact headline widths. Font stack: "ABCArizonaFlare", "Lora", Georgia, serif.
- **ABCArizonaSans** — Body copy, navigation, actions, timestamps and practical product information. An unobtrusive humanist sans with open counters, set at regular weight and slightly negative tracking. If unavailable, use **DM Sans**. Use 400 and the stated negative tracking. Font stack: "ABCArizonaSans", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| reassurance | ABCArizonaFlare | 400 | 64px | 1 | -0.0313em | Shared closing invitation, usually wrapping to two centered lines. |
| hero | ABCArizonaFlare | 400 | 48px | 1 | -0.0417em | Main promise and centered editorial statement. |
| heading | ABCArizonaFlare | 400 | 44px | 1 | -0.0455em | Product-family lead and major practical-section headings. |
| card-title | ABCArizonaFlare | 400 | 28px | 1 | -0.0357em | Portrait discovery-card titles. |
| panel-title | ABCArizonaFlare | 400 | 24px | 1 | -0.0417em | Opening invitation-panel title and small editorial proof heading. |
| body | ABCArizonaSans | 400 | 20px | 1.2 | -0.01em | Main support copy, discovery-card descriptions and feature tabs. |
| small-body | ABCArizonaSans | 400 | 16px | 1.2 | -0.0125em | Footer links, feature explanations and technical rows. |
| action | ABCArizonaSans | 400 | 16px | 1.2 | -0.02em | Button labels and top navigation. |
| announcement | ABCArizonaSans | 400 | 14px | 1.2 | -0.02em | Compact promotional strip and offer qualifier. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company naming stories | editorial-aside | ABCArizonaFlare | 400 italic | 64px | 1 | -0.0313em | Parenthetical pronunciation or short editorial aside alongside a display heading. |
| immersive scenarios and product packaging sections | chapter-title | ABCArizonaFlare | 400 | 40px | 1 | -0.05em | Scenario narrative headlines and centered packaging title. |
| product-detail feature grids | feature-title | ABCArizonaFlare | 400 | 28px | 1 | -0.007em | Inset product-feature photographs and small capability cards. |
| immersive scenario chapters | timestamp | ABCArizonaSans | 400 | 24px | 1 | -0.0083em | Current time along the narrative rail. |
| product-detail questions | answer | ABCArizonaSans | 400 | 17px | 1.3 | normal | Expanded answers below question rows. |

**Notes:**

- Keep headlines regular and tightly fitted; the 48px hero is not a giant billboard. The 64px closing reassurance is deliberately larger than the opening promise.
- Display line height stays at 1; supporting sans text is generally 1.2. Do not apply heading tracking to body copy.
- Title case belongs to product names and navigation; narrative headings use sentence case. Italic display text is a special editorial aside, not a general accent system.

## Layout

**Density:** Airy image-led storytelling with compact, practical controls and denser information near purchase decisions.

### Spacing

**Spacing system:**

- **gutter** 16px, horizontal — Base declared inline gutter; desktop sections expand to 40px side padding.

| Value | Use |
| --- | --- |
| 8px | Tight grid and minor internal separations. |
| 12px | Arrow-label gap and footer-link vertical rhythm. |
| 16px | Section lead to body copy and compact feature-grid gutters. |
| 24px | Hero title to support, card gutters and technical-row vertical padding. |
| 32px | Header menu spacing. |
| 40px | Desktop side gutters, discovery-card text inset and section header to card grid. |
| 64px | Atmospheric statement stack and practical-section top spacing. |
| 72px | Closing invitation top padding and portrait group to action bar. |
| 96px | Closing invitation bottom padding. |
| 120px | Major editorial section top padding and proof-band vertical breathing room. |

### Containers and grids

- **full-bleed stage**: side padding 40px. Photography spans the viewport. Overlay text respects desktop side gutters instead of sitting inside a narrow central card.
- **editorial copy**: max width 700px. Readable narrative or centered section introduction; main centered statements often narrow to 675px.
- **shared closing container**: max width 1192px · side padding 40px. Centered newsletter and footer content; action bar stretches across the inner width.
- **discovery grid**: 3 columns · gap 24px · side padding 40px. Three equal portrait cards across the 1360px desktop content width; each is 437×583px.
- **feature grid** (only for product-detail feature grids): 3 columns · gap 16px · side padding 40px. Wide photo banner, three narrow photo capabilities, then another wide banner.
- **practical split** (only for product-detail specifications): 2 columns · gap 60px · side padding 40px. A 460px introduction and capability column beside an 840px specification table at desktop.
- **question column** (only for product-detail questions): max width 800px · side padding 40px. Centered single-column questions with full-width ruled rows.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons | 6px |
| photo cards and warm glass | 8px |
| portraits | 50% |
| carousel tray | 24px |

## Surfaces and depth

### Surfaces

#### Stone canvas · level 0

**Use:** Underlying neutral foundation.

**CSS:** `background: #d7d7cb`

**Observed:** Often covered by photographic or atmospheric media rather than exposed as a plain gray field.

**Transfer:** Use as a neutral foundation, not a replacement for the image-led sections.

#### Sage band · level 0

**Use:** Closing invitation and footer; product-family backing.

**CSS:** `background: #e4e7da`

**Observed:** Broad uninterrupted color fields; no cast shadows.

**Transfer:** Reserve the clearest sage field for the human closing invitation.

#### Ivory editorial band · level 0

**Use:** Light proof and editorial breathing spaces.

**CSS:** `background: #f6f7f0`

#### Warm glass · level 1

**Use:** Compact invitation panel laid over the opening photograph.

**CSS:** `background: rgba(244, 231, 220, 0.3); backdrop-filter: blur(40px); border-radius: 8px`

**Observed:** The warm tint picks up the lawn and scene colors; an isolated product image stands to the left of title and action.

**Transfer:** Keep the underlying image visible through a soft warm veil rather than using frosted blue glass.

#### Atmospheric cloth · level 0

**Use:** Signature full-width editorial interlude and gentle product-story backing.

**CSS:** `background: #f6f7f0; overflow: hidden`

**Observed:** Broad pale lilac and rose fields fold into a warm peach edge, with extremely soft boundaries and a darker mauve diagonal crease. The field feels like diffused light through fabric, not a vivid mesh.

**Transfer:** Use the Atmospheric folds build to back one concise brand promise; match the soft glow, exact stops are not essential.

#### Technical paper · level 0

**Only for:** product-detail information

**Use:** Specifications, packaging and questions.

**CSS:** `background: #f5f5ee; border-top: 1px solid rgba(25, 40, 48, 0.15)`

#### Porcelain feature backing · level 0

**Only for:** product-detail feature grids

**Use:** Narrow frame around large feature photographs.

**CSS:** `background: #fcfcfa; padding: 40px`

#### Scenario wash · level 0

**Only for:** immersive scenario chapters

**Use:** Half-stage background beside lifestyle imagery and demonstrations.

**CSS:** `background: linear-gradient(225deg, #ffd2cd, #f6f7f0)`

**Observed:** Variants use sky fading to ivory at 225deg, and mist at 135deg with mist retained through 22%.

**Transfer:** Let a restrained warm-to-cool light change distinguish narrative moments.

#### Dark scene glass · level 1

**Only for:** immersive scenario summaries

**Use:** A summary overlay on an evening photograph.

**CSS:** `background: rgba(0, 0, 0, 0.4); border: 1px solid rgba(255, 255, 255, 0.3); border-radius: 8px; backdrop-filter: blur(12px)`

**Observed:** Tall translucent summary panel at the right, with centered text and a quiet outlined action.

**Transfer:** Keep its edge fine and the photo readable through it.

#### Material stage · level 0

**Only for:** premium hardware finish showcases

**Use:** Paired warm backdrops for floating object and macro detail.

**CSS:** `background: linear-gradient(#d2b394 15%, #eee3d2 97%)`

**Observed:** The adjacent panel uses a 90deg champagne-to-light-champagne gradient; the two 720px-wide halves form an 810px-high scene.

**Transfer:** Match the backing to the material's warmth without introducing decorative framing.

## Components

### Navigation bar

**Use:** Shared navigation over the stage and above reading sections.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 24px 40px; height: 88px; background: rgba(255, 255, 255, 0.533); color: #4e5a5e`

**Text style:** `action` — ABCArizonaSans 400 · 16px/1.2 · tracking -0.02em

**Observed:** Small horizontal wordmark at left, four centered links separated by 32px, circular shopping-bag control at right. Over a dark opening image the text and mark appear light and the bar reads as part of the scene; in scrolled reading sections it is a pale veil.

**States:** Declared: hover link opacity 0.5.

**Transfer:** Keep navigation visually subordinate to the photographic opening.

### Primary button

**Use:** Solid conversion or deeper-story action on light backgrounds.

**CSS:** `display: flex; justify-content: space-between; align-items: center; background: #192830; color: #ffffff; border-radius: 6px; padding: 12px 18px; height: 44px; gap: 12px; overflow: clip`

**Text style:** `action` — ABCArizonaSans 400 · 16px/1.2 · tracking -0.02em

**Observed:** Label aligned left, thin right arrow aligned right. A purchase variant grows to 56px high with 18px 24px padding and can pair a crossed-out old price with a current price.

**States:** Declared: hover background-color #cdd3bb and color #192830; focus-visible outline 2px solid #192830, outline-offset 2px, same fill and text change.

### Outline button

**Use:** Opening-photo action and lighter editorial invitation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; border: 1px solid #f6f7f0; color: #f6f7f0; background: transparent; border-radius: 6px; padding: 11px 17px; height: 44px`

**Text style:** `action` — ABCArizonaSans 400 · 16px/1.2 · tracking -0.02em

**Observed:** Opening default is light outline on photography. A dark-ink outline variant is used on the atmospheric light field; common widths are 247–249px.

**States:** Declared: hover background-color #ffffff, color #192830, border-color #ffffff; focus-visible outline 2px solid #192830, outline-offset 2px, same color changes.

**Transfer:** Choose light or dark outline by backing rather than changing the shape.

### Opening invitation panel

**Use:** Small commercial invitation anchored low in a cinematic stage.

**CSS:** `display: flex; align-items: center; width: 359px; height: 124px; background: rgba(244, 231, 220, 0.3); backdrop-filter: blur(40px); border-radius: 8px`

**Text style:** `panel-title` — ABCArizonaFlare 400 · 24px/1 · tracking -0.0417em

**Observed:** An 86px-wide isolated product image sits left; title and Outline button stack in the remaining space with a 20px gap. It remains separate from the upper-left promise.

**Transfer:** Use a real object cutout or a clean miniature interface view; keep this compact rather than a second hero.

### Discovery card

**Use:** Image-led product or capability discovery.

**CSS:** `display: flex; position: relative; border-radius: 8px; overflow: hidden; color: #f6f7f0`

**Text style:** `card-title` — ABCArizonaFlare 400 · 28px/1 · tracking -0.0357em

**Observed:** Full-bleed portrait photo fills the 437×583px desktop card. Content has 40px insets; title, 20px description and lower-left arrow overlay the scene. A black-to-transparent top scrim starts at 0.45 alpha and disappears by 55%.

**Transfer:** Choose photos with dark, calm upper regions and a tangible focal object lower in the frame.

### Capability tabs

**Use:** Organize a centered product demonstration without separate feature boxes.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 16px; width: 264px; height: 42px; color: #192830`

**Text style:** `body` — ABCArizonaSans 400 · 20px/1.2 · tracking -0.01em

**Observed:** Four labels share a centered 1132px row. Each has a 2px line beneath it: active line in ink, inactive lines in charcoal at 0.2 opacity. The selected description and dark action sit below, then a large interface demonstration.

**States:** Declared: hover not specified; focus-visible outline 2px solid #192830, outline-offset 4px.

### Newsletter invitation bar

**Use:** Shared closing conversion below the reassurance and portraits.

**CSS:** `display: flex; justify-content: space-between; align-items: center; width: 100%; max-width: 1192px; height: 52px; padding: 16px 18px; background: #ffffff; color: #192830; border-radius: 6px`

**Text style:** `action` — ABCArizonaSans 400 · 16px/1.2 · tracking -0.02em

**Observed:** A button-shaped full-width invitation, not an exposed email-input form. Label at left and fine arrow at the far right.

**States:** Declared: hover background-color #cdd3bb; focus-visible outline 2px solid #192830, outline-offset 2px, background-color #cdd3bb.

### Portrait cluster

**Use:** Human signature between closing reassurance and invitation bar.

**CSS:** `display: flex; align-items: center`

**Observed:** Six 56×56px circular photo portraits overlap by 16px; each is backed with muted sage. Heads are individually framed rather than all taken from one rectangular group shot.

**Transfer:** Use six distinct relevant people, or people and a meaningful companion subject, with consistent warm lighting.

### Footer columns

**Use:** Shared final navigation and legal area.

**CSS:** `background: #e4e7da; border-top: 1px solid rgba(25, 40, 48, 0.3); color: #2f3136`

**Text style:** `small-body` — ABCArizonaSans 400 · 16px/1.2 · tracking -0.0125em

**Observed:** A 323px-tall desktop footer uses two equal halves separated by a vertical hairline. Large 234×75px wordmark in the left half, two link columns in the right, copyright and small policy links along the bottom. Inner container is 1192px wide; list gaps are 12px.

**States:** Declared: hover link opacity 0.5; focus-visible link opacity 0.5.

### Question row

**Only for:** product-detail questions

**Use:** Purchase objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 24px; padding: 24px 0px; color: #192830`

**Text style:** `body` — ABCArizonaSans 400 · 20px/1.2 · tracking -0.01em

**Observed:** Each summary sits inside a details row with a 1px ink-at-0.15-alpha top rule. Question left and thin plus right; answers use the answer recipe and 24px bottom padding. The final row closes with a bottom rule.

**Transfer:** Use real expandable controls with concise practical questions, not individual rounded cards.

### Specification row

**Only for:** product-detail specifications

**Use:** Compact factual comparison and technical detail.

**CSS:** `display: flex; gap: 16px; padding: 24px 0px; border-top: 1px solid rgba(25, 40, 48, 0.15); color: #192830`

**Text style:** `small-body` — ABCArizonaSans 400 · 16px/1.2 · tracking -0.0125em

**Observed:** Label and value share a horizontal row; value text uses ink at 0.7 alpha. Rows form an 840px-wide table beside a narrower explanatory column.

**Transfer:** Keep labels short and values factual; let rows grow for wrapped text instead of truncating.

## Imagery and graphics

### Lived-in cinematic photography

**Use:** Default opening and human-context sections.

**Observed:** Warm, realistic people in a landscaped home, kitchen, living room or outdoors. Natural wood, linen, warm skin, grass and soft daylight create the palette. The opening is mostly photographic space with people distributed across the center and right, leaving shaded upper-left room for text. It is not a face cutout on a neutral background.

**Transfer:** Photograph the new product in an ordinary moment with multiple people or a meaningful human action. A single excellent contextual photograph with natural light is the minimum acceptable opening; keep clear space for the promise and invitation.

### Tactile product portrait

**Use:** Discovery cards and product-detail feature photography.

**Observed:** Phones rest diagonally on ochre upholstery; wearable metal catches directional light against skin and dark clothing. Tight framing, long warm highlights, deep shadows and physical surface detail make technology feel personal. Feature banners show an action in close-up with a small contextual interface overlay.

**Transfer:** Place the new object or screen in a real hand, on fabric or against another tactile surface. Use directional warm light and preserve material detail; for software, stage a restrained real interface in a device rather than a collage of floating panels.

### Atmospheric folds

**Use:** Required signature editorial interlude and soft section light.

**Observed:** A pale lavender-pink field with broad mauve folds and a peach-gold edge. The light seems to pass through translucent fabric; color is low contrast and never competes with the ink headline.

**Transfer:** Recreate the softness without needing fabric footage. Place a simple new brand symbol and concise promise on top; a layered blurred gradient is the minimum version.

**Build:** On an ivory full-width layer, add an oversized pale rose-lilac field using rgba(222, 203, 218, 0.65). Overlay a tall rotated mauve ellipse using rgba(153, 112, 139, 0.3), about 480px wide and 1000px high, tilted 18deg near the middle. Add a broad peach ellipse at the right using rgba(224, 170, 125, 0.45). Blur the colored layers by 60–100px, oversize them past all edges, and keep foreground text crisp. A 595px desktop band is enough to show a broad fold rather than a small glow.

### Human portrait circles

**Use:** Closing signature and editorial identity story.

**Observed:** Warm individual head portraits clipped to circles, with sage or natural pale backgrounds. The closing group is tightly overlapped; the editorial identity row separates the portraits and varies their sizes around a larger center.

**Transfer:** Use individually framed relevant humans, with varied ages and authentic expressions. Keep backgrounds calm and skin tones warm.

### Floating material macro

**Only for:** premium hardware finish showcases

**Use:** Finish and construction demonstration.

**Observed:** A small full object floats horizontally in the lower-left half of a warm sand scene; an extreme close-up of its underside fills the right half and extends beyond the bottom edge. Metal reflects long soft highlights rather than hard chrome sparkles. Three 40px finish swatches sit under the headline.

**Transfer:** Show the complete new object and one revealing material or functional detail at very different scales. Without 3D production, use two carefully lit photographs on matching warm backings.

### Scenario demonstrations

**Only for:** immersive scenario chapters

**Use:** Long-form product-in-life narrative.

**Observed:** Full-height contextual photography alternates with 720px-wide photo halves beside blush or sky washes. Small app outputs, notification cards, maps or a listening orb are integrated into the scene. A fine timeline rail connects the moments; interfaces support the narrative rather than taking over every chapter.

**Transfer:** Choose a few concrete moments in the new user's routine and show what changes. Keep demonstration interiors faithful to the new product and use restrained translucent overlays.

**Build:** For a simple listening visual, center a 110px pale orb on the wash with a white translucent rim, a soft blue inner radial glow and an outer rgba(181, 221, 255, 0.45) blur. Keep it isolated with a short status below rather than surrounding it with decorative particles.

### Dark closing product portrait

**Only for:** immersive scenario endings

**Use:** Resolve the narrative into one centered product action.

**Observed:** A hand holds a vertical phone rising from the bottom of a dark charcoal-to-muted-blue photographic field. Centered inverse 44px heading and outline action occupy the upper third; the object dominates the lower half.

**Transfer:** End the scenario with the new object in a real hand or a single isolated interface against restrained dark light, then transition to the sage human invitation.

### Icons

**Observed:** Thin simple line arrows, generally 16×16px with 1.3px rounded strokes, appear at the right of buttons. Card arrows are larger and airy. The shopping bag is enclosed in a 40px circle. Technical information uses sparse line icons, not colorful filled badges.

**Transfer:** Use fine consistent monochrome arrows and functional outline icons; match ink or inverse cream to the backing.

## Section recipes

How recurring sections are built.

### First screen: Human-context opening

**Observed:** A 40px dark announcement strip precedes a full-width 861px photographic stage, filling the first 900px desktop view. The navigation overlays its top edge: small mark left, centered links and bag right. Behind all foreground content is a warm garden-and-home scene with people and a moving companion subject across the center and right. A subdued dark area in the upper-left holds a 48px/1 serif promise with -2px tracking in a 504px-wide column; a 359px-wide, 20px/1.2 support paragraph follows after 24px. The Opening invitation panel is anchored low on the same left gutter, separate from the promise. A small centered carousel tray sits near the bottom, with an elongated white active marker and three dim dots. The main people, promise, support, navigation and action are visible in the first 900px; the discovery grid begins below it.

**Transfer:** Use the same hierarchy for a different product: lead with a human situation and put the main action in a small glass invitation rather than covering the center. Without video, use one rich contextual photograph. Product-detail openings instead use a dark full-bleed macro with the product title and qualifiers low left and a white purchase action low right; company-story openings center the symbol, heading and two short body columns on Atmospheric cloth. An immersive story can use a photo promise without a support paragraph.

**Avoid:** Do not replace the contextual scene with a generic centered headline over a blank gradient, a boxed image beside a huge slogan, or a grid of dashboard tiles above the fold.

**Text style:** `hero` — ABCArizonaFlare 400 · 48px/1 · tracking -0.0417em

### Editorial discovery gallery

**Observed:** On a light atmospheric backing over Sage band, a left-aligned heading and support block occupy roughly half the content width. The header uses 16px between heading and paragraph, then 40px before a three-column Discovery card grid with 24px gutters and 40px page insets. Cards are portrait format with imagery filling their bounds.

**Transfer:** Introduce a family of offers, workflows or audiences through three evocative visual entry points. Let the card's real image carry more weight than decorative UI.

**Text style:** `heading` — ABCArizonaFlare 400 · 44px/1 · tracking -0.0455em

### Centered demonstration chapter

**Observed:** Centered 48px heading above four Capability tabs, a centered support paragraph around 681px wide, Primary button and a large product demonstration. The image shows a crisp central phone with faded companion phones at either side; the background remains pale and softly tinted. Section top padding is 80px and demonstration content uses 40px separations.

**Transfer:** Select one capability at a time and make one large interface or object the focal point; peripheral states can fade but should not compete.

**Text style:** `hero` — ABCArizonaFlare 400 · 48px/1 · tracking -0.0417em

### Atmospheric brand statement

**Observed:** Atmospheric cloth spans a 595px desktop band. A simple centered symbol sits above a two-line 48px serif statement and a dark Outline button, with a 64px stack gap. The composition is deliberately sparse against the soft fold.

**Transfer:** Use one ownable symbol or restrained geometric emblem and one benefit statement; retain the atmospheric field as a signature device without requiring a particular place in the page sequence.

**Text style:** `hero` — ABCArizonaFlare 400 · 48px/1 · tracking -0.0417em

### Editorial proof band

**Observed:** Ivory editorial band with a centered 24px serif 'Featured in' heading and horizontally arranged publication marks. Vertical padding is 120px, with 60px between title and the moving mark row; typical marks are 130px wide with broad 120px spacing.

**Transfer:** Show a restrained row of genuine partner or publication marks with generous breathing room. Keep credibility subordinate to the people and product narrative.

**Text style:** `panel-title` — ABCArizonaFlare 400 · 24px/1 · tracking -0.0417em

### Companionship close and footer

**Observed:** A 501px Sage band uses 72px top and 96px bottom padding. A 675px-wide centered 64px/1 reassurance spans two lines; Portrait cluster follows with a 25px gap. After 72px, Newsletter invitation bar stretches to 1192px. Footer columns continue the same sage field for 323px, with a fine top rule and center divider, oversized wordmark at left and compact navigation at right.

**Transfer:** Finish with an emotionally direct benefit, a relevant human cluster and one low-pressure invitation. Preserve the broad bar rather than replacing this with a conventional centered CTA button.

**Text style:** `reassurance` — ABCArizonaFlare 400 · 64px/1 · tracking -0.0313em

### Inset product-feature gallery

**Only for:** product-detail feature grids

**Observed:** Porcelain feature backing encloses a 1360×583px wide photograph, three 443×553px capability photos with 16px gutters, and another wide photograph. Corners are 8px. Text sits at 24px insets: 28px feature heading, 16px explanation and a discreet interface output away from the text.

**Transfer:** Explain concrete interactions with action photography and small faithful interface overlays; use the wide panels for deeper explanations and the smaller panels for compact benefits.

**Text style:** `feature-title` — ABCArizonaFlare 400 · 28px/1 · tracking -0.007em

### Premium material split

**Only for:** premium hardware finish showcases

**Observed:** Two equal 720×810px Material stage panels. The left holds a 48px headline at the top, finish label and three circular swatches below, then the complete object floating low; the right is dominated by a greatly enlarged underside detail.

**Transfer:** Use a full-object-to-macro contrast to demonstrate material quality or a functional detail.

**Text style:** `hero` — ABCArizonaFlare 400 · 48px/1 · tracking -0.0417em

### Technical reassurance

**Only for:** product-detail information

**Observed:** Technical paper first supports a two-column specification layout: 48px heading and four small icon-led capability summaries at left, Specification rows at right. A centered 40px packaging heading, compact contents list and a 987×366px box photograph follow. Question rows use an 800px centered column beneath a 44px heading. Small factual disclaimers precede the shared human close.

**Transfer:** Move from sensory desirability to verifiable detail, included items and practical questions; keep this area flat and ruled rather than decorated.

**Text style:** `heading` — ABCArizonaFlare 400 · 44px/1 · tracking -0.0455em

### Immersive routine chapters

**Only for:** immersive scenario stories

**Observed:** 900px-tall narrative scenes alternate full-bleed photos with half-photo/half-Scenario wash compositions. A 1px timeline rail lies near the left gutter with a 12px solid start dot, 24px current time, and smaller hollow next dot. The 40px serif chapter heading begins after a narrow timestamp column and sits near the top. Daylight, meal, movement and evening scenes move from warm blush to cool mist. A late scene uses Dark scene glass; the narrative resolves with Dark closing product portrait before the shared sage close.

**Transfer:** Show a workflow through concrete human moments, using the rail to establish continuity. Use whichever number of scenes serves the new story rather than copying a long chronology.

**Text style:** `chapter-title` — ABCArizonaFlare 400 · 40px/1 · tracking -0.05em

### Identity explanation

**Only for:** company-story pages

**Observed:** A centered mission opening on Atmospheric cloth pairs a 48px heading with two 20px body columns and two small overlapping founder portraits. A separate Technical paper editorial block uses a 64px title with a matching italic parenthetical, a wide row of circular portraits, and a centered explanation. A dark product bridge leads to three news cards with 8px media corners, 20px article titles and 16px dates, then the shared close.

**Transfer:** Explain the new organization's motivation or name with intimate human details rather than a corporate chronology; use editorial aside styling only where the content warrants it.

**Text style:** `hero` — ABCArizonaFlare 400 · 48px/1 · tracking -0.0417em

## Page flow

**Storyline:** Human promise → tangible product context → useful capability demonstration → emotional or credibility reassurance → practical detail where needed → human invitation.

### Broad brand and product landing page

1. **Promise** — Full-bleed human scene with upper-left promise and compact glass action.
2. **Offer discovery** — Three portrait product cards below a left-aligned introduction.
3. **Capability demonstration** — Centered tabbed explanation with a focused phone demonstration.
4. **Emotional reassurance** — Sparse centered brand statement on an atmospheric fold.
5. **Credibility** — Small editorial heading and publication-mark row.
6. **Closing invitation** — Sage reassurance, overlapping portraits, full-width newsletter action and split footer.

**Transfer:** Use this as the default for a new marketing landing page; vary narrative order without losing its human stage, tactile media, atmospheric statement and companionable ending.

### Long-form scenario or use-case narrative

1. **Promise** — A full-screen lifestyle promise introduces the people and context.
2. **Product-in-life demonstration** — Time-stamped scenes combine domestic photographs, soft color washes and contextual app outputs.
3. **Resolution** — An evening summary overlays a photograph, then a dark centered phone portrait converts the outcome into an action.
4. **Closing invitation** — The same sage human invitation and split footer.

**Transfer:** Follow the new user's routine through a small set of meaningful moments; the timeline is a scoped storytelling device, not the default page scaffold.

### Company motivation and identity story

1. **Mission** — Symbol, centered promise, two body columns and intimate founder sign-off on a fabric-like field.
2. **Identity explanation** — Display heading with italic parenthetical, circular portrait row and centered prose.
3. **Product bridge** — Dark full-bleed product image with invitation panel.
4. **Credibility** — Three editorial news cards.
5. **Closing invitation** — Shared sage reassurance and footer.

**Transfer:** Connect the new organization's motivation to a tangible offering and external proof, keeping a personal voice.

### Detailed physical-product conversion page

1. **Product promise** — Dark macro opening with low title, purchase action and subscription qualifier.
2. **Desirability** — Full-bleed on-body portrait and short introduction.
3. **Capabilities** — Inset wide and three-column photographic feature gallery.
4. **Material proof** — Warm finish selector with complete-object and macro views.
5. **Offer context** — Related product portrait-card gallery.
6. **Practical proof** — Ruled specifications, centered packaging image and contents.
7. **Objection handling** — Questions, answers and factual disclaimers.
8. **Closing invitation** — Shared sage reassurance and footer.

**Transfer:** For hardware use sensual imagery first and restrained technical detail later; the price action may persist as a small dark bar during deeper reading.

## Writing

Warm, capable and reassuring, with technology framed as help rather than spectacle. Emotional promises are followed by clear everyday actions and practical explanation, not technical bravado.

**Do not copy:** Do not reuse Luffu or Fitbit names, logos, proprietary artwork, named family members, testimonials, press quotations, product claims, discounts, shipping dates, subscription terms or prices. Source examples illustrate voice only; write original, supportable claims for the new offering.

- **Addressing the reader:** Speak directly to 'you' and 'your'; use 'we' when explaining motivation. Refer to products by short names while keeping human outcomes in the foreground.
- **Rhythm:** Sentence-case headlines are usually one clear thought across two lines. Supporting paragraphs are compact, often two sentences; feature titles lead with a verb and actions stay short. Contractions and an occasional em dash make the tone conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the reader's responsibility, then offer dependable support using a balanced clause. | 8–14 words | “When the whole family relies on you, rely on [Brand]” |
| Section lead | Use a relational phrase that turns the offer into help for the reader. | 6–10 words | “Our family of products can help yours” |
| Capability explanation | Start with a recognisable burden, explain what the system notices or does, then state the relief. | 30–45 words | “You have enough on your plate. [Brand] watches for changes—missed medications, shifting health and activity patterns—and alerts you before they become concerns, so you can rest easier.” |
| Feature title | Lead with a concrete verb and name the everyday interaction. | 5–12 words | “Capture the moment with voice logging” |
| Closing reassurance | A direct emotional permission or relief statement, without inflated urgency. | 7–12 words | “You don’t have to carry it all alone.” |
| Primary action | Plain verb plus product or destination; avoid cleverness. | 2–6 words | “Preorder [Brand] Link”<br>“Sign up for newsletter updates” |

**Words and phrasing to use:** show up; stay informed; simple; thoughtful; together; rhythm; lightens; rest easier; what matters

**Avoid:** disrupt; revolutionary; supercharge; dominate; unprecedented; hustle; game-changing

**Rules:**

- Name a human outcome before explaining a technical mechanism.
- Use concrete everyday verbs instead of abstract transformation claims.
- Let practical questions state limitations and requirements plainly.
- A reassuring statement can be emotional; quantitative or technical claims must remain specific and supportable.

## Do's and Don'ts

### Do

- Keep editorial headings at weight 400 and line height 1, using -2px tracking at 44–64px.
- Use 40px desktop page gutters and 24px discovery-card gaps.
- Let contextual imagery occupy most of the opening rather than enlarging the headline beyond 48px.
- Keep buttons at 6px corners and give their arrows room at the right edge.
- Use 8px corners on photographic cards with full-bleed media.
- Include the soft atmospheric fold as a broad, low-contrast statement field.
- Make the closing reassurance 64px with overlapping 56px portraits and a wide 52px action bar.
- Use 1px alpha-ink rules to organize practical information without elevation.

### Don't

- Do not turn regular serif headlines into bold grotesk slogans.
- Do not use pill-shaped conversion buttons; reserve circles for portraits, swatches and compact controls.
- Do not replace the sage and cream structure with pure-white panels separated by heavy shadows.
- Do not use bright saturated gradients as default backgrounds or color the main headlines.
- Do not shrink the discovery gallery into icon cards with small thumbnails.
- Do not apply the immersive timeline rail to every ordinary landing section.
- Do not expand the 359px glass invitation into a large opaque purchase box.
- Do not turn the flat technical rows into individually elevated 16px-radius cards.

## Motion and responsive

### Motion

**Observed:**

- Action color and border changes use .24s cubic-bezier(0.4, 0, 0.6, 1). Navigation opacity uses 0.24s ease-in-out.
- Carousel markers declare width and opacity transitions of 0.24s ease-in-out.
- Publication marks declare a 50s linear infinite marquee.
- Opening and editorial sections use video media; the scenario narrative changes with scroll.

**Transfer:**

- Use the declared short color transitions for the restrained action system and the width transition for elongated active carousel markers.
- Keep the atmospheric field slow and broad in appearance rather than adding sharp particles or flashy interface effects.

**Unknown:**

- Video timing, scroll choreography, pause thresholds and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints including 390px, 500px, 600px, 640px, 749px, 768px, 980px, 1024px, 1100px and 1280px.
- The inline gutter token is 16px; desktop compositions use 40px side padding.

**Transfer:**

- As a design adaptation, stack portrait cards and technical columns when they no longer fit; preserve image-led proportions rather than squeezing all three cards into a narrow row.
- Keep the atmospheric statement broad, the human portrait cluster intact and the newsletter invitation full width within the smaller gutter.
- For narrow scenario chapters, place photo and demonstration in a readable vertical sequence while retaining a compact time rail.

**Unknown:**

- Exact narrow-screen type sizes, navigation behavior, media reframing and stacking rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
