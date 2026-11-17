# VITURE — objects in electric orbit

## Overview

A cinematic technology style that makes hardware feel like a monumental object suspended in space. Mostly black and charcoal, it combines regular-weight contemporary sans-serif type with cool grey interludes, electric blue actions and tightly contained flashes of orange, violet and red. Glossy product renders, macro details and immersive demonstrations carry most of the story; text is sparse until the spacious, utility-rich ending.

### Essentials

- The object becomes the architecture: a 1440px-wide, 900px-tall opening stage places one oversized dark product behind a centered 90px/1.1, weight-400 promise, with secondary views cut off by the lower corners. Use a clean silhouette with rim lighting when a full 3D scene is unavailable.
- Lightweight words sell heavyweight technology: normal tracking and regular 400-weight display type, 90px for the opening and 54px/1.1 for ordinary chapters; support drops sharply to 15px/1.4 rather than competing with the object.
- Actions are small electric capsules: the default blue-gradient conversion button is 150px by 45px with a 40.5px radius and 12px/1 text. Keep it isolated below the promise; orange and red actions belong to warmer product campaigns.
- Darkness dominates, color behaves like light: black and near-black surround the object, blue is concentrated in actions and illuminated product edges, and orange appears in 12px uppercase footer labels. Cool #c5c6d2 full-screen interludes interrupt the dark story rather than becoming the entire page.
- The stage changes on a slant: full-width scenes meet through diagonal reveals, alternating giant macro product details with concise benefit overlays. Include a luminous hero-scale object treatment and a diagonal scene change on every new landing page; a cutout over a softly lit gradient is the minimum equivalent.
- The ending keeps its cinematic scale before becoming useful: a 54px conversion headline floats over full-bleed blue-lit product imagery beside a 30px-radius glass email panel, followed by a black footer with 144px top padding, four roomy link columns and a square editorial product promotion.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#3655ff` | `--color-blue` | action, accent | Default conversion capsule gradient endpoint. |
| Deep electric blue | `#0022d8` | `--color-blue-deep` | action, accent | Default conversion capsule gradient center. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5f34` | `--color-orange` | text, action, accent | Footer category labels and social hover fills; full conversion fills only in warm accessory stories. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | Primary text and white campaign buttons. |
| Cool grey interlude | `#c5c6d2` | `--color-grey-stage` | background | Full-screen technical and partner chapters contrasting with dark scenes. |
| Half-light text | `#808080` | `--color-muted` | text | White at 50% over black; support lines and lower-priority information. |
| Soft text | `#666666` | `--color-soft-text` | text | White at 40% over black for colorful product-story subtitles. |
| Dim text | `#525252` | `--color-dim` | text | White at 32% over black for small supporting captions. |
| Footer rule | `#262626` | `--color-rule` | border | White at 15% over black for the final horizontal rule. |
| Warm charcoal | `#222127` | `--color-charcoal` | background | Macro product scenes and floating feature summaries. |
| Deep charcoal | `#19191d` | `--color-deep-charcoal` | background | Late-story conversion scenes with a large side-framed product. |
| Glass edge | `#121212` | `--color-glass-edge` | border | White at 7% over black; subtle panel outlines and social-button fills. |
| Blue-black glass | `#070b14` | `--color-glass-blue` | surface | Visible 10% blue tint over black, made with rgba(66,113,201,0.1); intended to pick up scene colors through blur. |
| Near-black stage | `#030303` | `--color-stage` | background | Default opening backing beneath dark product imagery. |
| Black stage | `#000000` | `--color-canvas` | background | Full-bleed scenes and footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| colorful consumer product stories | Graphite panel | `#141414` | `--color-panel` | surface | Dark feature panels; also the visible effect of white at 8% over black. |
| catalog and social-proof sections | Gallery grey | `#efefef` | `--color-light-canvas` | background | Shopping, reviews and editorial proof bands. |
| catalog and social-proof sections | Gallery ink | `#0c0c0c` | `--color-ink` | text | Text on light gallery bands. |
| catalog and social-proof sections | Frosted white | `#f5f5f5` | `--color-light-card` | surface | Visible white at 40% over gallery grey. |
| warm accessory stories | Warm light | `#ffdbbc` | `--color-cream` | text | White-to-cream clipped display text. |
| colorful consumer product stories | Consumer coral | `#f8421e` | `--color-coral` | action, accent | Campaign conversion and focus outlines. |
| colorful consumer product stories | Luminous violet | `#581dff` | `--color-violet` | accent, background | Atmospheric light behind objects, not paragraph text. |
| colorful consumer product stories | Light peach | `#fe7a60` | `--color-peach` | accent, background | Middle of the violet-to-orange lighting gradient. |
| colorful consumer product stories | Orange flare | `#ff2900` | `--color-flare` | accent, background | Warm end of the atmospheric gradient. |
| dramatic collector campaigns | Wine-black | `#0a0607` | `--color-wine-stage` | background | Red-lit collector scenes. |
| dramatic collector campaigns | Collector red | `#ff2c28` | `--color-red` | action, accent | Red conversion capsules and scene highlights. |
| dramatic collector campaigns | Warm ivory | `#efe8df` | `--color-ivory` | text | Serif cinematic prompts. |

## Typography

- **FontSeasonSans** — Core display, body, actions and navigation. Season Sans and seasonSans are alternate family declarations used for the same brand sans treatment in product stories. Open, softly geometric contemporary sans with broad round bowls and a notably light-feeling regular display cut. If unavailable, use **DM Sans**. Use 400 for display and 500–700 for compact utility text; preserve normal tracking. Font stack: "FontSeasonSans", "DM Sans", system-ui, sans-serif.
- **Alegreya** (only for dramatic collector campaigns) — Cinematic all-capital phrases, navigation and supporting labels throughout the collector treatment. Literary, calligraphic serif that turns technical promotion into a dramatic artifact story. Font stack: "Alegreya", Georgia, "Times New Roman", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | FontSeasonSans | 400 | 90px | 1.1 | normal | size 6.25vw | Default opening promise, centered on two lines. |
| heading | FontSeasonSans | 400 | 54px | 1.1 | normal | size 3.75vw | Chapter headings and conversion headline. |
| navigation | FontSeasonSans | 500 | 16px | 1 | normal | fixed | Primary navigation labels. |
| link | FontSeasonSans | 400 | 16px | 1.2 | normal | fixed | Footer column links. |
| body | FontSeasonSans | 500 | 15px | 1.4 | normal | size 1.04167vw | Short support lines beneath the opening and partner labels. |
| category | FontSeasonSans | 700 | 12px | 1.6 | normal, uppercase | fixed | Orange footer column labels. |
| caption | FontSeasonSans | 550 | 12px | 1.4 | normal | size 0.833333vw | Small low-contrast panel support and compact descriptive captions. |
| primary-action | FontSeasonSans | 400 | 12px | 1 | normal | fixed | Default blue capsule label. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| warm accessory mode demonstrations | mode-sculpture | FontSeasonSans | 400 | 300px | 1.06 | normal | fixed | Oversized horizontally clipped mode names behind the product. |
| colorful consumer quantified-proof chapters | odometer | FontSeasonSans | 400 | 261px | 0.81 | normal, features "tnum" | fixed | Gradient-filled rolling numerical proof, with a small unit beside it. |
| colorful consumer product stories | story-display | FontSeasonSans | 400 | 84px | 1 | normal | fixed | Broad chapter headlines, often split into separately revealed words. |
| warm accessory stories | warm-display | FontSeasonSans | 400 | 72px | 1.2 | normal | fixed | Cream-gradient benefit headings. |
| warm accessory purchase bars | price-display | FontSeasonSans | 400 | 72px | 1.1 | normal | fixed | Large price paired with a compact product summary and action. |
| colorful consumer product stories | story-heading | FontSeasonSans | 400 | 57px | 1.15 | normal | fixed | Secondary chapters, model choice and stacked closing invitation. |
| colorful consumer product stories | feature-heading | FontSeasonSans | 500 | 33px | 1.15 | normal | size calc(((44*100)/1920)*1vw) | Feature card headings and small promotional-panel title. |
| warm accessory purchase bars | product-summary | FontSeasonSans | 400 | 32px | 1.4 | normal | fixed | Product name in the closing purchase panel. |
| colorful consumer product stories | story-subtitle | FontSeasonSans | 500 | 27px | 1.2 | normal | fixed | Dim subtitle directly beneath a large chapter headline. |
| catalog sections | tile-title | FontSeasonSans | 550 | 18px | 1 | normal | size 1.25vw | Compact product title below a small isolated render. |
| colorful consumer product stories | feature-body | FontSeasonSans | 500 | 18px | 1.16 | normal | size calc(((24*100)/1920)*1vw) | Terse feature explanations within cards. |
| colorful consumer product stories | story-action | FontSeasonSans | 700 | 10.5px | 1.71 | normal, uppercase | size calc(((14*100)/1920)*1vw) | Small white rectangular action labels. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Normal tracking is the default even at monumental sizes; do not import a tightly kerned bold-tech aesthetic.
- Display is weight 400. Weight 550–700 is concentrated in small labels, product cards and actions, not the main promise.
- The consumer story uses a larger 84px chapter scale and 27px dim subtitles; it is a distinct treatment, not the default 54px chapter recipe.
- Keep paragraphs subordinate to the object. A short support line can be much smaller than the heading without filling the negative space.

## Layout

**Density:** Airy scene composition with compact utility text: most chapters give one object and one claim an entire screen, while the footer is deliberately spacious.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 12px | Small grid gutters and social icon separation. | 0.833333vw |
| 15px | Catalog gutters and consumer heading-to-subtitle gap. | 1.04167vw |
| 24px | Declared layout padding and gallery heading-to-support gap. | fixed |
| 30px | Card padding and image-to-editorial-copy separation. | 2.08333vw |
| 36px | Consumer card horizontal inset. | 2.5vw |
| 40px | Navigation side inset and vertical footer link gap. | fixed |
| 48px | Consumer chapter title-to-card-group separation. | fixed |
| 60px | Footer upper-grid separation. | fixed |
| 72px | Consumer scene inset and spacious editorial content gaps. | fixed |
| 88px | Declared navigation layout height; rendered navigation bar is 87px tall. | fixed |
| 120px | Footer side inset. | fixed |
| 144px | Footer top inset. | fixed |

### Containers and grids

- **scene**: max width 1440px · side padding 0px. Edge-to-edge media stages; at desktop the visual scene is 900px tall, with longer scroll tracks controlling the same stage rather than adding empty content.
- **technical interlude**: max width 1440px · side padding 156px. Text left and large product or portrait right, aligned within a 1128px-wide inner composition.
- **footer**: max width 1440px · 4 columns · gap 12px · side padding 120px. A 1200px inner width: four link columns occupy the left 751px, a 388.8px square promotion sits right, separated by 60px.
- **gallery** (only for catalog sections): max width 1110px · 3 columns · gap 15px · side padding 33px. Centered three-column grid of 360px-wide product tiles.
- **consumer feature grid** (only for colorful consumer product stories): max width 1296px · 3 columns · gap 12px · side padding 72px. Three equal cards or asymmetric spans with one wide feature; headings remain outside the grid.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary capsule | 40.5px |
|  | glass panels | 30px |
|  | social circles | 9999px (pill) |
| colorful consumer product stories | consumer feature cards | 36px |
| colorful consumer product stories | consumer white actions | 12px |
| warm accessory stories | purchase bar | 60px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| warm accessory stories | purchase bar | `0px 10px 30px 0px rgba(0,0,0,0.22), inset 0px 1px 0px 0px rgba(255,255,255,0.1)` | A restrained lower shadow and illuminated upper edge, not a floating white-card effect. |

### Surfaces

#### Black stage · level 0

**Use:** Base for full-bleed cinematic chapters and the footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** The object fades into the background; there is no visible card container around the hero.

**Transfer:** Light the object, not a boxed canvas around it.

#### Cool interlude · level 0

**Use:** A technical explanation or proof chapter contrasting with black scenes.

**CSS:** `background: #c5c6d2`

**Observed:** Large quiet grey field paired with an oversized black product and diagonal scene boundaries.

**Transfer:** Use for a change of narrative mode, not every alternating paragraph.

#### Charcoal stage · level 0

**Use:** Late-story detail and conversion scenes.

**CSS:** `background: #222127`

**Observed:** A closely related #19191d backing supports the final limited-access scene.

**Transfer:** Keep the neutral hue slightly cool and let the rim light separate the product.

#### Blue glass · level 1

**Use:** Email panel and editorial media framing.

**CSS:** `background: rgba(66,113,201,0.1); border: 1px solid rgba(255,255,255,0.07); border-radius: 30px; backdrop-filter: blur(37.5px)`

**Observed:** Dark translucent glass picks up blue illumination from the media behind it.

**Transfer:** Place over an actual scene so the blur has something to soften.

#### Light gallery · level 0

**Only for:** catalog and social-proof sections

**Use:** Product selection, quotes and review carousels.

**CSS:** `background: #efefef; color: #0c0c0c`

**Observed:** A broad neutral respite between dark scenes, with centered 54px headings.

**Transfer:** Reserve for comparison and third-party proof rather than reducing the whole story to a store grid.

#### Consumer graphite · level 1

**Only for:** colorful consumer product stories

**Use:** Feature tile backing.

**CSS:** `background: #141414; border-radius: 36px; overflow: clip`

**Observed:** Most panels are dark neutral; imagery itself supplies blue, violet and orange illumination.

**Transfer:** Keep the tile structure simple and put the visual complexity in one well-lit object detail.

#### Consumer light atmosphere · level 0

**Only for:** colorful consumer product stories

**Use:** Localized glow behind renders and numerical proof.

**CSS:** `background: linear-gradient(90deg, #581dff, #fe7a60 59.08%, #ff2900 80%, rgba(0,0,0,0)); filter: blur(20px)`

**Observed:** Oversized color field masked to a soft oval; much of the surrounding stage remains black.

**Transfer:** Use one low-positioned glow behind the object, fading all outer edges rather than filling every section.

## Components

### Navigation bar

**Use:** Persistent wayfinding above the product story.

**CSS:** `display: flex; align-items: center; justify-content: space-between; height: 87px; padding: 0px 40px; color: #ffffff`

**Text style:** `navigation` — FontSeasonSans 500 · 16px/1

**Observed:** A 44px translucent announcement strip sits above it. Small symbol left, three widely separated text destinations next, then search, account and bag icons right. The default launch treatment has no price cluster; commerce variants add a thumbnail, starting price and order capsule.

**Transfer:** Keep navigation visually subordinate to the full-screen product.

### Primary button

**Use:** Default launch or conversion action.

**CSS:** `background: linear-gradient(90deg, #3655ff -100%, #0022d8 0%, #3655ff 100%); color: #ffffff; border-radius: 40.5px; width: 150px; height: 45px; padding: 16.5px; text-align: center`

**Text style:** `primary-action` — FontSeasonSans 400 · 12px/1

**Observed:** A single small electric capsule sits beneath the support line. Commerce versions can be shorter, with price integrated into the label; warm accessory and collector variants switch to orange or red.

**Transfer:** Choose one short, explicit next step.

### Email glass panel

**Use:** Scene-backed signup.

**CSS:** `background: rgba(66,113,201,0.1); border: 1px solid rgba(255,255,255,0.07); border-radius: 30px; backdrop-filter: blur(37.5px); width: 388px; height: 188px; display: flex; flex-direction: column`

**Text style:** `caption` — FontSeasonSans 550 · 12px/1.4

**Observed:** An unboxed email field shares the upper row with the Submit chevron; dim consent copy sits low in the panel. The panel balances a large conversion heading across the scene.

**Transfer:** Retain the floating-panel relationship rather than turning this into a full-width form.

### Submit chevron

**Use:** Compact form submission inside the glass panel.

**CSS:** `background: rgba(255,255,255,0.08); border-radius: 22.5px; width: 47px; height: 47px; display: flex; align-items: center; justify-content: center`

**Observed:** A tiny right chevron is centered within a soft rounded square; the accessible label names the submission action.

**States:** Declared: hover background rgba(255,255,255,0.1); focus-visible not specified.

**Transfer:** Keep the arrow delicate rather than using a large filled arrowhead.

### Footer menus

**Use:** Utility-rich ending after the final scene.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); column-gap: 12px; row-gap: 60px; color: #ffffff`

**Text style:** `link` — FontSeasonSans 400 · 16px/1.2

**Observed:** Orange Category labels precede white link stacks with 40px vertical gaps. A square promotional image occupies a separate column at the right. Social controls sit below the menus; the lower policy row ends with a faint rule.

**Transfer:** Group by visitor task and preserve the unusually generous vertical link rhythm.

### Social button

**Use:** Small utility controls in the footer.

**CSS:** `background: rgba(255,255,255,0.07); color: rgba(255,255,255,0.4); border-radius: 9999px; width: 32px; height: 32px; display: flex; align-items: center; justify-content: center`

**Observed:** A compact row of subdued circular platform marks sits below an orange category label.

**States:** Declared: hover background-color #ff5f34 and color #ffffff; focus-visible not specified.

**Transfer:** Use a consistent family of platform marks, not multicolor logos.

### Catalog tile

**Only for:** catalog sections

**Use:** Compact product selection within the light gallery.

**CSS:** `background: rgba(255,255,255,0.4); border: 1px solid rgba(255,255,255,0.08); border-radius: 30px; backdrop-filter: blur(37.5px); padding: 30px; display: flex; flex-direction: column; align-items: flex-start; overflow: hidden`

**Text style:** `tile-title` — FontSeasonSans 550 · 18px/1

**Observed:** Small isolated product view at the upper left; title and brief positioning at the lower left, buy-and-price capsule lower right, with an occasional upper-right badge. Dark special-edition tiles use saturated photographic backdrops and white copy.

**Transfer:** Make each card a complete miniature product stage, not a spec list.

### Feature tile

**Only for:** colorful consumer product stories

**Use:** Close inspection of one feature.

**CSS:** `background: rgba(255,255,255,0.08); border-radius: 36px; padding: 43.5px 36px; display: flex; flex-direction: column; overflow: clip`

**Text style:** `feature-heading` — FontSeasonSans 500 · 33px/1.15

**Observed:** One benefit title and dim short support accompany a macro image. Three equal tiles can sit above a wide detail tile; other groups combine one narrow, one double-width and one narrow tile.

**Transfer:** Use a specific material detail or visible mechanism for each claim.

### White story button

**Only for:** colorful consumer product stories

**Use:** Secondary exploration within rich product chapters.

**CSS:** `background: #ffffff; color: #000000; border-radius: 12px; padding: 12px 19.5px; position: relative; overflow: clip`

**Text style:** `story-action` — FontSeasonSans 700 · 10.5px/1.71 · uppercase

**Observed:** Compact uppercase rectangle contrasts with the pill-shaped navigation action. Text is implemented as separately moving label layers.

**States:** Declared: hover color #ffffff and background-color rgba(0,0,0,0); focus-visible outline 2px solid #f8421e.

**Transfer:** Use this treatment only within the colorful chapter system.

### Purchase bar

**Only for:** warm accessory stories

**Use:** Closing price-and-action panel over a final product render.

**CSS:** `background: linear-gradient(115deg, rgba(255,255,255,0.14), rgba(255,255,255,0.06) 42%, rgba(255,255,255,0.04) 62%, rgba(255,255,255,0.1)); border: 1px solid rgba(255,255,255,0.16); border-radius: 60px; box-shadow: 0px 10px 30px 0px rgba(0,0,0,0.22), inset 0px 1px 0px 0px rgba(255,255,255,0.1); display: flex; align-items: center; justify-content: space-between; padding: 0px 154px; height: 141px`

**Text style:** `product-summary` — FontSeasonSans 400 · 32px/1.4

**Observed:** Product name and a dim one-line benefit sit left; a 72px regular-weight price, thin vertical separator and orange order capsule sit right. The product floats above and partly behind the panel.

**Transfer:** Use as a consolidated buying decision after the feature story.

### Orange order button

**Only for:** warm accessory stories

**Use:** Final action within the Purchase bar.

**CSS:** `background: #ff5f34; color: #ffffff; border-radius: 54px; width: 167px; height: 52px; display: flex; align-items: center; justify-content: center`

**Observed:** A solid orange capsule has a 16px bold label with 0.01em tracking, contrasting with the thin large price.

**States:** Declared: hover filter brightness(1.08) and transform translateY(-2px); focus-visible not specified.

### Credit invitation

**Only for:** colorful consumer purchase endings

**Use:** Small surprise incentive beneath the closing action.

**CSS:** `background: rgba(255,255,255,0.08); border-radius: 24px; backdrop-filter: blur(50px); padding: 36px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `feature-heading` — FontSeasonSans 500 · 33px/1.15

**Observed:** A translucent horizontal panel pairs a friendly heading and dim supporting sentence on the left with a compact coral claim action on the right.

**Transfer:** Use only for a genuine incentive relevant to the visitor, below the main action rather than as an obstructive overlay.

## Imagery and graphics

### Monumental product stage

**Use:** Opening and major chapter transitions.

**Observed:** Dark graphite hardware with satin surfaces, controlled reflections and bright fine edge highlights floats against black. The opening uses one large frontal view behind the words plus partial views at the lower corners; later scenes move to close angles that extend outside the frame.

**Transfer:** Render or photograph the new object against black using a broad soft key light and narrow rim lights. If there is no 3D model, use a high-resolution cutout with one side-view duplicate, careful shadows and a restrained reflected edge; keep the same object-to-type scale.

**Build:** Layer a black 1440px-wide stage, a low soft charcoal radial glow, then an oversized transparent product cutout; place two smaller angled cutouts partially outside the lower edges. Put the centered text above the main image, leaving a dark low-detail region behind the letters.

### Luminous product atmosphere

**Use:** A required lighting device somewhere in the landing-page story, especially the conversion scene.

**Observed:** Blue light washes physical edges while the object remains dark; warmer consumer scenes add orange and violet through transparent surfaces. Text sits in the darker portion of the composition rather than over the brightest flare.

**Transfer:** For software or a service, light a cropped device frame or dimensional representation of the principal outcome instead of inventing a fake physical product.

**Build:** Place a broad elliptical blue glow behind the object at the lower center, using electric blue at low alpha and a 150px blur; add a narrow masked highlight across one material edge. For the colorful variant, use the Consumer light atmosphere surface, soften it with an oval mask, and overlap a smaller warm glow. Keep outer corners black.

### Diagonal scene boundary

**Use:** Transitions between hero-scale scenes.

**Observed:** Broad angled wipes bring cool grey scenes up over black or tilt a dark chapter edge across a full-width image.

**Transfer:** Use a diagonal reveal between two meaningful visual chapters, not a decorative zigzag between every paragraph.

**Build:** Use an absolutely positioned next-scene layer with an SVG quadrilateral or CSS clip-path polygon. Begin with one top corner lower than the other, reveal the full layer as the scene advances, and finish on a clean rectangular reading state. Keep the angle broad and the shape free of strokes.

### Macro feature renders

**Use:** Technical explanations and Feature tiles.

**Observed:** Close views of hinges, transparent shells, optics and small mechanisms use glossy blue-violet illumination and selective warm highlights. A single detail often fills most of a card or the right two thirds of a scene.

**Transfer:** Photograph or render a real construction detail that explains the benefit; minimum equivalent is one clean close-up with directional light, not a generic icon.

### Human-scale demonstration

**Use:** Showing physical scale and actual use.

**Observed:** Hands hold a dark device on a black background in the warm accessory variant; elsewhere a side-profile wearer or a room scene grounds a digital effect in real use. The lighting remains controlled and the background does not become a busy lifestyle montage.

**Transfer:** Show one recognizable action and one clear scale cue, with muted clothing and uncluttered framing.

### Orb and orbit text

**Only for:** broad multi-use brand storytelling

**Use:** A sculptural transition between proof and use-case demonstrations.

**Observed:** A near-page-width sphere rises from below the frame; orange-white illumination shifts to a blue hemisphere against black. A sentence follows the upper curve, then floating media panels take over the foreground.

**Transfer:** Use the sphere as a metaphorical stage for several outcomes, with a short curved promise.

**Build:** Create a 1390px circle with a white-to-orange horizontal gradient, add inset violet and magenta shadow layers, then mask the lower hemisphere into the canvas. Use an SVG textPath along a slightly larger circular arc; overlay dark rounded media panels at varied perspective angles.

### Collector thread theater

**Only for:** dramatic collector campaigns

**Use:** Artifact-focused product reveals and immersive demonstration chapters.

**Observed:** Wine-black space, red-lit black materials, engraved metallic ornament and taut diagonal red cords frame rotating close-ups. Ivory serif capitals supply short dramatic phrases; demonstrations use a thin red frame or a single red line across the scene.

**Transfer:** Translate a product's real craft or material story into shadow, metallic detail and tension lines rather than applying fantasy ornament to an ordinary product.

**Build:** Use a wine-black canvas with a low-alpha red radial light near a lower corner. Draw a sparse SVG network of thin diagonal cords behind the product, with one brighter red edge and a soft duplicate stroke. Add a restrained red glow behind a rectangular demonstration; keep serif statements short.

### Icons

**Observed:** Navigation uses 22px outline icons with 1.5px rounded strokes; feature icons are generally 33px, white and simply drawn. Footer social marks are muted inside 32px circles. Technical controls favor small device outlines rather than decorative illustration.

**Transfer:** Use a consistent thin round-stroke icon set for utilities, with filled marks only for recognizable platforms. Keep feature illustrations in the media layer, not in oversized icon badges.

## Section recipes

How recurring sections are built.

### First screen: Object-framed opening

**Observed:** A full-width 900px stage stacks near-black backing, softly illuminated frontal product imagery and centered white copy. The main object occupies roughly the middle three fifths of the width and most of the height, with two partial angled views entering from the bottom corners. The 44px announcement and 87px Navigation bar float above. A small partner line sits above the two-line 90px/1.1 Display promise, which occupies about 555px of width; a 15px dim support line follows, then the isolated Primary button. The first 900px contains all of these elements plus faint corner captions and a tiny side progress rail; the next technical chapter remains below the fold.

**Transfer:** Use the new product's strongest frontal or structural view as the frame around the promise. Without cinematic footage, use the Monumental product stage recipe with a still cutout and rim light. Catalog-led openings can instead use an oversized single-word material sculpture; warm accessory openings center a product name above hands demonstrating scale; dramatic collector openings let the artifact dominate before adding short serif statements.

**Avoid:** Do not replace the stage with a conventional text-left/product-right card hero, a dense paragraph, or a large rectangular CTA.

**Text style:** `display` — FontSeasonSans 400 · 90px/1.1

### Technical interlude

**Observed:** Cool interlude surface interrupts the dark scenes through a Diagonal scene boundary. A left-aligned heading and short explanation balance a large right-side product or rounded human-use image; the composition uses 156px side insets. Partner marks form a separate restrained proof row.

**Transfer:** Use to explain the mechanism or establish credibility after the emotional promise.

**Text style:** `heading` — FontSeasonSans 400 · 54px/1.1

### Macro chapter

**Observed:** A product detail fills the right side or the entire scene; a Heading and one support sentence sit on the left in a low-detail area. Other chapters center a terse title above the object. The background remains a Black stage or Charcoal stage.

**Transfer:** Pair each visible detail with one user benefit. Alternate center-led spectacle with left-aligned explanation so the page does not become a repetitive card list.

**Text style:** `heading` — FontSeasonSans 400 · 54px/1.1

### Floating feature summaries

**Observed:** A horizontal row of four translucent dark rounded panels overlays an enlarged product view. Each has a thin colored line icon, concise title and a few short lines of explanatory copy; the product remains visibly continuous behind the row.

**Transfer:** Use for a compact cluster of practical reasons to believe, retaining the image as the main surface.

### Scene-backed closing invitation

**Observed:** A full-bleed blue-lit product scene balances a 54px two-line headline and short support at the left with an Email glass panel at the right. A dark overlay protects text, and the lower image fades into black before the utility footer.

**Transfer:** End the narrative with one clear action in a visually memorable scene. Launch pages can first use a side-framed limited-access invitation; commerce pages can use the Purchase bar, while colorful consumer stories use a centered stacked invitation, white order button and Credit invitation beneath.

**Text style:** `heading` — FontSeasonSans 400 · 54px/1.1

### Editorial utility ending

**Observed:** Black stage with 144px top, 120px side and 40px bottom padding. Footer menus occupy four columns on the left and a square product promotion on the right, fading to black behind its title and glass action. Social button row follows the menus. A lower row carries subdued policy links and a locale capsule, finishing with a 1px white-at-15% rule.

**Transfer:** Preserve the final editorial promotion and roomy link columns even when the number of destinations changes.

### Quantified light sculpture

**Only for:** colorful consumer quantified-proof chapters

**Observed:** A giant Odometer sits over a glowing hemispherical light field. A narrow centered explanation and small White story button sit below; the numeric unit shares the display rather than becoming a badge.

**Transfer:** Elevate one substantiated measurement into an atmospheric visual, keeping qualification small but adjacent.

**Text style:** `odometer` — FontSeasonSans 400 · 261px/0.81

### Consumer benefit bento

**Only for:** colorful consumer product stories

**Observed:** Story display plus dim Story subtitle leads into Feature tiles with 12px gutters and 36px corners. A wide demonstration can span two columns, while narrower side tiles carry single material details.

**Transfer:** Group related benefits and vary span according to imagery, not according to copy length.

**Text style:** `story-display` — FontSeasonSans 400 · 84px/1

### Gallery proof and choice

**Only for:** catalog and social-proof sections

**Observed:** Light gallery surface holds a centered 54px Heading, a short support line and either three-column Catalog tiles or a horizontally clipped review carousel. Review images have 30px rounded glass frames; captions and quotes sit outside the image, centered. A separate awards scene uses a large quote, small publisher marks and tiny award logos.

**Transfer:** Separate product choice from independent proof; use real thumbnail imagery and actual quote attribution.

**Text style:** `heading` — FontSeasonSans 400 · 54px/1.1

### Mode word sculpture

**Only for:** warm accessory mode demonstrations

**Observed:** A 300px regular-weight mode name runs horizontally beyond the frame behind a floating object. A compact explanatory headline and one-line support remain near the upper left; the product changes orientation as the named configuration changes.

**Transfer:** Use oversized contrasting words to express two genuine configurations or outcomes, with the object visibly demonstrating the distinction.

**Text style:** `mode-sculpture` — FontSeasonSans 400 · 300px/1.06

## Page flow

**Storyline:** Cinematic promise → tangible product demonstration → mechanism and practical proof → use-case or choice chapters → scene-backed conversion → editorial utility ending.

### Launch a technical product with a concise, cinematic story

1. **Promise** — Object-framed opening with one centered promise and a launch action.
2. **Credibility** — Cool-grey partner and mechanism interlude.
3. **Capability proof** — Giant macro product scenes with floating practical feature summaries.
4. **Closing call** — Side-framed limited-access invitation, then a blue-lit signup scene.
5. **Utility** — Four link columns, editorial promotion and subdued lower row.

**Transfer:** Use this as the default landing-page narrative, adapting the amount of proof to the product.

### Introduce a product family and guide visitors toward a model

1. **Visual hook** — Monumental word sculpture followed by product promise and paired actions.
2. **Quantified proof** — Full-scene metrics and immersive demonstrations.
3. **Choice** — Light three-column product gallery.
4. **Social proof** — Publisher quote, awards and review thumbnail carousel.
5. **Use cases** — Orb-and-orbit transition with floating application media.
6. **Closing call** — Editorial news, full-scene signup and shared utility footer.

**Transfer:** Use the lighter proof-and-choice middle for a multi-product portal, while keeping cinematic object-led bookends.

### Explain a compact accessory through its physical transformations

1. **Promise** — Hands demonstrate scale beneath centered product naming and compatibility.
2. **Physical proof** — In-hand view, turntable, size comparison and assembly.
3. **Configuration demonstration** — Giant mode words behind a rotating object, followed by a numbered three-step usage sequence.
4. **Use cases** — Charging callout and solo/co-use demonstration toggle.
5. **Closing call** — Final object render above a glass purchase bar, then shared footer.

**Transfer:** Use warm light, cream typography and visible scale cues for accessories; let demonstrations answer setup objections.

### Turn a special edition into an immersive artifact story

1. **Visual hook** — Oversized black-and-red product orbit with taut threads.
2. **Craft proof** — Macro metallic ornament, material details and short serif declarations.
3. **Experience proof** — Framed immersive demonstration and selectable viewing modes.
4. **Objection handling** — Room-context demonstration of the customized on-device controls.
5. **Utility** — Shared black footer with serif type and red accents.

**Transfer:** Keep this as a scoped dramatic collector treatment; the final pre-footer campaign scene can follow the new product's own conversion needs.

### Present an extensive consumer product range through colorful visual chapters

1. **Visual hook** — Immersive product-light scene.
2. **Capability chapters** — Broad chapter headlines alternate with macro imagery, benefit bento panels and illuminated numerical proof.
3. **Ecosystem proof** — Floating demonstration screens, content-thumbnail ribbons and compact compatibility rows.
4. **Choice** — Three model presentations with short audience positioning and order actions.
5. **Closing call** — Centered stacked invitation over luminous product imagery, small incentive panel, then shared footer.

**Transfer:** Use the 84px headline scale, violet-orange light and white compact actions for a colorful consumer campaign rather than the default launch treatment.

## Writing

Confident, benefit-led technology promotion with an appetite for short superlatives and cinematic declarations. Practical explanation stays direct and brief; the spectacle comes from the visual, not from lengthy prose.

**Do not copy:** Do not reuse VITURE names, partner logos, proprietary product names, artwork, quotations, prices, performance numbers, awards or first-in-industry claims. Use only substantiated claims and original media for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your; describe the product as a compact enabling tool. Use impersonal technical statements when explaining compatibility or construction.
- **Rhythm:** Headlines are generally two to nine words, sometimes split into two clipped sentences. Support is one short sentence or a balanced pair; repeated fragments build cadence. Title case and sentence case coexist; all caps are reserved for utility labels and the dramatic collector voice.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the useful transformation, not a category description. | 5–9 words | “The AI You Wear To Work.” |
| Benefit headline | Short paired or tripled fragments with a confident comparative rhythm. | 2–8 words | “Mini. Mighty. Always Ready.”<br>“No Glare. No Reflections. No Distortion.” |
| Support | Make the benefit concrete with a short balanced statement. | 7–18 words | “Sees what you see. Hears what you hear.”<br>“Same big-screen power. 34% smaller. 30% lighter.” |
| Feature explanation | Describe a physical action or practical outcome plainly. | 5–20 words | “Optional magnetic mount, thin enough to leave on.”<br>“Seamless multi-screen setup across all platforms” |
| Primary action | Explicit action, with a launch-stage variation where appropriate. | 2–5 words | “Join the First Batch”<br>“Order Now” |
| Dramatic collector statement | Compressed material metaphor in serif capitals. | 3–8 words | “FORGED IN SHADOW. SHARPENED FOR PLAY.” |
| Closing invitation | Invite a personal choice or reward without a long sales pitch. | 3–7 words | “Your Perfect Pick Awaits”<br>“Be the First to Know” |

**Words and phrasing to use:** your; next-level; built for; powered by; seamless; all-day; perfect fit; portable; one system; your call

**Avoid:** enterprise-solution word salad; long philosophical manifestos; cute cartoon banter; unqualified best-in-world claims; abstract innovation without a visible benefit

**Rules:**

- Lead each chapter with one benefit, then support it with one visible mechanism or measurement.
- Keep compatibility lists factual and compact rather than turning them into promotional paragraphs.
- Use periods to create rhythm in short fragments; do not make every line an exclamation.
- Name the audience only where it clarifies choice, not in every headline.
- Reserve theatrical metaphors for a deliberately dramatic campaign variant.

## Do's and Don'ts

### Do

- Keep opening type at 90px/1.1, weight 400, with normal tracking.
- Give one major product image most of a 900px scene instead of surrounding it with cards.
- Use the 45px blue capsule as the default launch action.
- Use 156px side insets for the cool technical interlude at desktop.
- Keep glass edges faint: 1px white at 7%, with 30px corners.
- Preserve the 40px vertical spacing in footer link stacks.
- Use 12px gutters and 36px corners in the colorful feature bento variant.
- Make at least one scene boundary diagonal and at least one product scene luminous.

### Don't

- Do not set main promises in heavy 700-weight type; that weight belongs to compact utility labels.
- Do not make saturated orange the default page canvas; it is a signal or a light source.
- Do not replace the small 12px capsule label with oversized app-style button text.
- Do not apply the 36px consumer card radius to every surface; core glass panels use 30px.
- Do not use hard opaque blue rectangles where translucent blue-black glass is intended.
- Do not fill the cool-grey interlude with dense feature tables; the object still needs room.
- Do not turn all imagery into equally sized thumbnail cards; alternate macro scenes and proof groups.
- Do not carry the collector serif, red cords and ornament into an ordinary launch page.

## Motion and responsive

### Motion

**Observed:**

- Opening copy declares opacity 1.4s and transform 1.4s cubic-bezier(0.22,1,0.36,1).
- Social buttons declare background-color 300ms and color 300ms.
- Warm final order button declares filter 0.25s and transform 0.25s.
- The colorful atmosphere declares a 12s linear circular animation and a 2.5s alternating breathing animation.
- Scenes use sticky visual stages, product rotation, clipped diagonal reveals and word-by-word text layers.

**Transfer:**

- Let scroll move the object and reveal the next scene while keeping one claim readable at a time.
- Use a still product stage as the fallback for elaborate turntable media; retain the same lighting and composition.
- Animate the light field independently of text so the scene feels alive without moving every element.

**Unknown:**

- Complete scroll timelines, interaction thresholds and unlisted animation timings are not specified.

### Responsive

**Observed:**

- Core typography uses viewport formulas including 6.25vw for the opening and 3.75vw for chapter headings.
- Declared width breakpoints include 600px, 640px, 767px, 768px, 1024px, 1280px, 1536px, 1560px and 1920px; product stories include 800px boundaries.
- Consumer grids declare a one-column base and multi-column desktop variants.

**Transfer:**

- On narrow screens, preserve the object-first hierarchy by using one main view rather than three competing views.
- Stack the scene headline and conversion panel, and convert feature grids to one column while retaining dark material continuity.
- Use viewport formulas for desktop scaling, then set readable mobile text sizes without shrinking captions in proportion to the entire stage.

**Unknown:**

- Exact mobile type sizes, scene crop choices and navigation collapse behavior are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
