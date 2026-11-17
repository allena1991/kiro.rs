# Tapbots — toys with a purpose

## Overview

A playful software showcase with the finish of a miniature animated film. Dark charcoal and near-black stages carry silver toy-like characters, luminous violet accents and crisp interface imagery; occasional colored chapters interrupt the darkness. System sans typography is modest beside the artwork, with light explanatory paragraphs and compact semibold headings. The feeling is personal, crafted and useful rather than enterprise-polished, suited to independent applications and characterful digital tools.

### Essentials

- The artwork gets the first word: a full-width illustrated stage fills roughly the first 720px, followed by a centered 386×125px graphic product title; explanatory copy begins at the bottom of the first 900px, with conversion actions below it.
- Useful software has a physical personality: stage a rounded, softly lit product object or original character at monumental scale, then repeat its visual language in icons and the closing scene. Without a character, turn the product's core tool into a beveled, toy-like object.
- The page is a stack of slanted stages, not a stack of cards: full-width chapter bands use a 72px diagonal bottom cut at 1440px, overlap by 72px and carry 216px top / 144px bottom padding.
- Small headings leave room for large objects: the default section heading is system sans 28px/1.1 at 600 with normal tracking; supporting text is 21px/1.4 at 300. The alternative utility showcase uses 60px/1.05 at 800 with -0.05em tracking.
- Color lives in the scene and selected chapters: most of the default page stays near-black or charcoal, with one saturated violet chapter, pastel lavender copy, blue-to-magenta emphasized phrases and a green feature heading rather than an all-over rainbow canvas.
- Actions are friendly physical controls: rounded 40px-radius pills, compact 47–50px heights, gentle tonal gradients or deep violet fills, and a declared 1.05 hover scale rather than angular outlined controls.
- The closing proof is another illustration: a 700px-wide translucent dark quotation panel floats over an oversized silver character, followed by the repeated download/support cluster and a separate dark company footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet chapter | `#7047ba` | `--color-violet` | background, accent | One full-width explanatory chapter. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Periwinkle copy | `#cdd4f8` | `--color-intro` | text | Centered opening paragraphs. |
| Lilac copy | `#deccff` | `--color-violet-copy` | text | Light body text on the saturated violet chapter. |
| Lavender action | `#ba94ff` | `--color-link` | text, link | Support action text and its matching solid icon. |
| Deep plum | `#301e4f` | `--color-help-fill` | surface | Support pill backing. |
| Plum ink | `#4c278e` | `--color-button-ink` | text | Text on pale gradient action pills. |
| Pale violet | `#d9c3ff` | `--color-button-tint` | surface | Lower stop of pale gradient action pills. |
| Highlight blue | `#6cb0ff` | `--color-gradient-blue` | accent | Start of blue-to-magenta text emphasis. |
| Highlight magenta | `#f747ff` | `--color-gradient-pink` | accent | End of blue-to-magenta text emphasis. |
| Wordmark pearl | `#e7e6ff` | `--color-logo-light` | accent | Upper stop of the graphic product title. |
| Wordmark shadow | `#8a89af` | `--color-logo-dark` | accent | Lower stop of the graphic product title. |
| Feature green | `#74ec5a` | `--color-green` | text, accent | Feature inventory chapter label. |
| Proof violet | `#9466e7` | `--color-proof-label` | text | Short heading above the quotation scene. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | Headings and bright device surfaces; also the top stop of pale controls. |
| Directory silver | `#cccccc` | `--color-footer-copy` | text | Company introduction and directory headings. |
| Secondary silver | `#c3c3c3` | `--color-body` | text | Body copy on medium charcoal and quotation attribution. |
| Dim silver | `#b3b3b3` | `--color-muted` | text | Explanatory copy on the darkest feature stages. |
| Soft gray | `#ababab` | `--color-feature-copy` | text | Visible white at 60% over #2c2c2c in feature descriptions; retain the alpha recipe in the component. |
| Warm gray stage | `#484848` | `--color-device-stage` | background | Large device demonstrations. |
| Graphite | `#2c2c2c` | `--color-feature-stage` | background | Feature inventory band beneath subdued colored illumination. |
| Charcoal canvas | `#1a1a1a` | `--color-canvas` | background | Main dark chapters. |
| Footer black | `#111111` | `--color-footer` | background | Company directory and utility-page outer canvas. |
| Midnight stage | `#05050b` | `--color-hero` | background | Opening illustration and the long introduction stage. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| utility product pricing | Metallic card gray | `#bdbdbd` | `--color-pricing-end` | surface | Bottom stop of purchase cards. |
| utility product pricing | Purchase ink | `#444444` | `--color-pricing-ink` | text | Text within pale purchase cards. |
| utility product demonstrations | Deep green charcoal | `#212c2e` | `--color-utility-stage` | background | Dark organization demonstration chapter. |
| utility product demonstrations | Blue charcoal | `#171d1f` | `--color-utility-stage-deep` | background | Dark processing demonstration chapter. |
| utility product demonstrations | Copper heading | `#c5713e` | `--color-copper` | text | Heading against the butter-yellow feature chapter. |
| utility product demonstrations | Warm brown copy | `#805e4b` | `--color-brown-copy` | text | Support and captions on warm demonstration panels. |

## Typography

- **-apple-system** — Default product marketing typography, including headings, paragraphs, actions and quotations. Native humanist system sans; light paragraphs contrast with compact semibold headings. Font stack: "-apple-system", system-ui, "Helvetica Neue", Helvetica, Arial, sans-serif.
- **urbane** (only for company and portfolio pages) — Large company headings and product-directory labels. Broad friendly geometric sans with rounded forms. If unavailable, use **Montserrat**. Use 500–600 weights; retain normal tracking and the fluid scale. Font stack: "urbane", "Montserrat", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Helvetica Neue** (only for company and portfolio pages) — Thin large support lines and supporting prose. Light neo-grotesk, more restrained than the geometric headings. If unavailable, use **Roboto**. Use light and thin weights. Font stack: "Helvetica Neue", "Roboto", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| quote | -apple-system | 300 italic | 36px | 1.2 | normal | fixed | Centered editorial quotation on the illustrated closing stage. |
| chapter-label | -apple-system | 600 | 32px | 1.1 | normal | fixed | Green heading introducing the dense feature inventory. |
| proof-heading | -apple-system | 600 | 32px | 27px | normal | fixed | Compact centered heading above the quotation panel. |
| heading | -apple-system | 600 | 28px | 1.1 | normal | fixed | Main section headings beside illustrations and device scenes. |
| intro | -apple-system | 300 | 24px | 1.4 | normal | fixed | Centered introductory paragraphs under the graphic product name. |
| intro-emphasis | -apple-system | 600 | 24px | 1.4 | normal | fixed | Short gradient-highlighted phrases within introductory paragraphs. |
| feature-heading | -apple-system | 600 | 24px | 1.1 | normal | fixed | Titles in the two-column icon feature inventory. |
| body | -apple-system | 300 | 21px | 1.4 | normal | fixed | Feature explanations beside product imagery. |
| primary-action | -apple-system | 600 | 21px | 27px | normal | fixed | Pale gradient action label. |
| footer-intro | -apple-system | 400 | 20px | 1.7 | normal | fixed | Company footer introduction and links. |
| footer-heading | -apple-system | 600 | 20px | 1.7 | normal | fixed | Directory group headings. |
| semantic-title | -apple-system | 400 | 18px | 1.5 | normal | fixed | Accessible product-title text behind the graphic wordmark; visible title scale is controlled by the graphic, not this text recipe. |
| feature-body | -apple-system | 300 | 18px | 1.4 | normal | fixed | Feature inventory descriptions and compatibility lines. |
| attribution | -apple-system | 600 | 18px | 1.2 | normal | fixed | Attribution below a quotation. |
| support-action | -apple-system | 500 | 18px | 1.4 | normal | fixed | Help pill label. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company support sections | help-display | urbane | 600 | 100.8px | 1 | normal | size 7vw | Exuberant short help headline. |
| company and portfolio pages | company-display | urbane | 600 | 86.4px | 1 | normal | size 6vw | Oversized company promise and human-story heading. |
| utility product pages | utility-heading | -apple-system | 800 | 60px | 1.05 | -0.05em | fixed | Dense, emphatic feature chapter headings. |
| utility product pages | utility-title | -apple-system | 800 | 48px | 1.1 | -0.03em | fixed | Product name below the illustrated opening and app icon. |
| company and portfolio pages | company-support | Helvetica Neue | 200 | 43.2px | 1.3 | normal | size 3vw | Thin centered mission statement. |
| utility product pages | utility-support | -apple-system | 200 | 30px | 1.25 | -0.05em | fixed | Large lightweight supporting copy beneath feature headings. |
| utility product demonstrations | demo-caption | -apple-system | 600 | 20px | 1.4 | -0.05em | fixed | Centered instruction below a demonstrated operation. |
| utility product pricing | pricing-body | -apple-system | 400 | 18px | 1.5 | normal | fixed | Purchase explanation, with prices emphasized inline rather than enlarged. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Default product typography retains normal tracking, even at 36px. Reserve tight negative tracking and weight 800 for the utility showcase variant.
- The first impression comes from the illustrated object and graphic product name, not a giant conventional headline. The graphic name occupies a 386×125px box at desktop.
- Keep the default 28px headings visually subordinate to the devices. The company variant deliberately reverses that balance with 6vw headings.

## Layout

**Density:** Airy between illustrated chapters and comfortable within explanatory blocks; the feature inventory is comparatively dense.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 16.8px | Default gap after a 28px section heading. | fixed |
| 20px | Small image/text separation and purchase-shell padding. | fixed |
| 27px | Paragraph rhythm in explanatory chapters and row separation in the feature inventory. | fixed |
| 30px | Quotation-panel padding and outer paragraph side padding. | fixed |
| 40px | Space below the graphic product title; device-copy side margins. | fixed |
| 48px | Gap after inventory or proof labels. | fixed |
| 60px | Side inset for the utility showcase variant. | fixed |
| 72px | Diagonal chapter overlap at desktop. | 5vw |
| 80px | Top padding of the separate company footer. | fixed |
| 144px | Bottom padding of default chapter bands. | 10vw |
| 216px | Top padding of default chapter bands. | 15vw |

### Containers and grids

- **intro-column**: max width 1000px · side padding 30px. Centered long introduction; padding extends its overall outer width to 1060px.
- **feature-story**: max width 900px · side padding 40px. Alternating illustrations and narrow explanation columns, centered in the full-width stage.
- **device-copy**: max width 500px · side padding 40px. Short prose beside oversized device renders; devices can bleed off the opposite page edge.
- **inventory**: max width 1080px · 2 columns · gap 72px. Two open columns of 504px feature rows, not raised cards.
- **quote-panel**: max width 640px · side padding 30px. Centered content inside a 700px overall translucent quotation panel.
- **utility-frame** (only for utility product pages): max width 1300px · side padding 60px. Centered illustrated chapters with visible dark outer gutters.
- **purchase-grid** (only for utility product pricing): max width 1140px · 2 columns · gap 20px. Two equal 560px purchase cards inside a 1180px frosted shell.
- **portfolio-grid** (only for company and portfolio pages): max width 1152px · 4 columns · gap 29px. Open columns centered below the mission statement, each led by a 187px app icon.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action-pills | 40px |
|  | quote-panel | 18px |
| utility product pricing | purchase-shell | 32px |
| utility product pricing | purchase-cards | 16px |
| utility product demonstrations | demo-panel | 36px |

## Surfaces and depth

### Surfaces

#### Midnight illustration stage · level 0

**Use:** Opening canvas.

**CSS:** `background-color: #05050b; background-size: 100% auto; background-position: 50% 0px`

**Observed:** An edge-to-edge illustration resolves into a nearly black lower area, allowing the title and introductory paragraphs to remain legible.

**Transfer:** Render the dark lower fade as part of the scene or as a transparent-to-midnight overlay.

#### Diagonal chapter · level 0

**Use:** Default full-width chapter construction.

**CSS:** `background-color: #1a1a1a; clip-path: polygon(0px 0px, 100% 0px, 100% calc(100% - 72px), 0px 100%); padding-top: 216px; padding-bottom: 144px; margin-top: -72px; position: relative`

**Observed:** Successive bands overlap; violet, medium gray and graphite versions change the chapter's mood. Text remains level while the bottom edge slopes upward toward the right.

**Transfer:** Use the same edge logic for a few substantial narrative chapters; keep overlap and z-index deliberate.

#### Violet diagram stage · level 0

**Use:** A high-color explanatory chapter.

**CSS:** `background-color: #7047ba; color: #deccff`

**Observed:** Tonal circular texture backs a large connected-node diagram and a narrow explanatory column.

**Transfer:** Give the product's organizing idea one colored stage with a low-contrast related pattern.

#### Quotation glass · level 1

**Use:** Quotation panel over the closing character illustration.

**CSS:** `background-color: rgba(35,35,35,0.8); backdrop-filter: blur(10px); border-radius: 18px; padding: 30px`

**Observed:** The softly translucent panel reads as dark glass without an outline or prominent shadow.

**Transfer:** Float a concise quote above a tangible product object, keeping a readable dark silhouette.

#### Company footer canvas · level 0

**Use:** Separate directory after the final conversion scene.

**CSS:** `background-color: #111111; padding-top: 80px`

**Observed:** A centered maker mark and short introduction precede open link columns, social/contact links and muted copyright.

**Transfer:** Let the richly illustrated ending settle into a plain, useful directory.

#### Purchase shell · level 1

**Only for:** utility product pricing

**Use:** Groups the purchase alternatives.

**CSS:** `background-color: rgba(114,109,106,0.494); backdrop-filter: blur(10px); border-radius: 32px; padding: 20px`

**Observed:** Warm smoky glass floats over the dark illustrated closing environment.

**Transfer:** Keep the illustration visible around the shell while the purchase cards remain opaque.

#### Purchase metal · level 2

**Only for:** utility product pricing

**Use:** Equal purchase option cards.

**CSS:** `background-image: linear-gradient(#ffffff, #bdbdbd); border-radius: 16px`

**Observed:** A white header strip caps a subtly metallic vertical gradient, with prose, ordinary bullets and a bottom action.

**Transfer:** Use restrained silver gradients rather than colored plan-status fills.

## Components

### Primary pill

**Use:** Secondary conversion or joining action within a colored chapter.

**CSS:** `background-image: linear-gradient(#ffffff, #d9c3ff); color: #4c278e; border-radius: 40px; padding: 10px 20px; transition: 0.15s ease-out`

**Text style:** `primary-action` — -apple-system 600 · 21px/27px

**Observed:** An intrinsically sized centered text control, used against the violet scene rather than as an omnipresent navigation CTA.

**States:** Declared: hover transform scale(1.05); focus-visible unknown; active transform translateY(2px).

### Support pill

**Use:** Friendly assistance below the download and requirements cluster.

**CSS:** `background-color: #301e4f; color: #ba94ff; border-radius: 40px; padding: 12px 20px 12px 15px; transition: 0.15s ease-out`

**Text style:** `support-action` — -apple-system 500 · 18px/1.4

**Observed:** A solid 28px icon precedes the label, with a 5px icon-to-text margin; the control is centered.

**States:** Declared: hover transform scale(1.05); focus-visible unknown; active transform translateY(2px).

### Graphic download badge

**Use:** Primary download action repeated near the beginning and end of a product story.

**CSS:** `width: 412px; height: 128px; background-size: 100% auto; transition: 0.15s ease-out`

**Text style:** `intro` — -apple-system 300 · 24px/1.4

**Observed:** A custom metallic store badge incorporates the dimensional app icon at the left. It sits above a bold requirements label, small compatibility lines and the Support pill.

**States:** Declared: hover transform scale(1.05); focus-visible unknown; active transform translateY(2px).

**Transfer:** Compose an original product icon with the appropriate authorized store badge, or make a similarly legible wide download control.

### Gradient phrase

**Use:** Selective emphasis inside the centered introduction.

**CSS:** `background-image: linear-gradient(to right bottom, #6cb0ff, #f747ff); background-clip: text; color: rgba(0,0,0,0)`

**Text style:** `intro-emphasis` — -apple-system 600 · 24px/1.4

**Observed:** Several short craft or performance phrases are bold and gradient-filled while the surrounding paragraph stays pale periwinkle.

### Icon feature row

**Use:** Compact capability inventory in two open columns.

**CSS:** `display: flex; margin-bottom: 27px`

**Text style:** `feature-heading` — -apple-system 600 · 24px/1.1

**Observed:** Small colorful app-like icon at left; a semibold title and lightweight description align in a text column. Description uses rgba(255,255,255,0.6) over graphite; rows are not boxed.

**Transfer:** Use one concrete capability per row and illustrate it with a miniature object or native-feeling icon.

### Quotation panel

**Use:** Editorial proof over an oversized closing object.

**CSS:** `background-color: rgba(35,35,35,0.8); backdrop-filter: blur(10px); border-radius: 18px; padding: 30px; max-width: 640px; text-align: center`

**Text style:** `quote` — -apple-system 300 italic · 36px/1.2

**Observed:** Large italic quotation followed by a semibold attribution; a small publication icon can sit beside the credit. The overall box is 700px wide including padding.

### Footer directory

**Use:** Useful site ending after the visual conversion chapter.

**CSS:** `display: flex; justify-content: space-around; margin-bottom: 32px`

**Text style:** `footer-heading` — -apple-system 600 · 20px/1.7

**Observed:** Open groups of product/resource links under semibold names. A centered introduction precedes them; contact and social links are centered below.

**Transfer:** Group links by products or audience tasks rather than inventing a large navigation bar.

### Purchase option

**Only for:** utility product pricing

**Use:** Two equally weighted purchasing routes.

**CSS:** `background-image: linear-gradient(#ffffff, #bdbdbd); border-radius: 16px; display: flex; flex-direction: column`

**Text style:** `pricing-body` — -apple-system 400 · 18px/1.5

**Observed:** White title strip, explanation with inline bold prices, plain bullet list and a small colored pill near the bottom. Neither option is an oversized recommended plan.

### Demonstration caption

**Only for:** utility product demonstrations

**Use:** Explains the single operation visible in the current slide.

**CSS:** `max-width: 80%; text-align: center; margin-bottom: 10px; color: #805e4b`

**Text style:** `demo-caption` — -apple-system 600 · 20px/1.4 · tracking -0.05em

**Observed:** Caption sits well below the isolated interface detail, with small circular slide controls underneath. Text color follows the chapter's warm or cool palette.

## Imagery and graphics

### Cinematic product personality

**Use:** Opening and closing signature illustration.

**Observed:** A polished silver toy-like character occupies the right/lower half while an enormous cropped object enters diagonally from the upper left. A nearly black space field, soft violet nebulae, tiny stars and bright cyan engine light create depth. Surfaces look like smooth molded plastic and brushed metal, with rounded seams and restrained reflections.

**Transfer:** Give a different product an original tangible metaphor: a small rounded instrument, appliance or character. Pair it with one huge cropped prop and directional light. The minimum acceptable version is an original layered vector object with bevel gradients, cast shadows and a luminous accent, not a stock photo.

**Build:** Use a midnight full-width base. Layer a sparse SVG star field of 1–2px white circles at varied low opacity, two large blurred violet ellipses behind the objects, and a cyan radial glow behind the nearest light source. Build the object from rounded SVG paths with silver-to-slate gradients and dark inset slots; place a strong white highlight on the upper-left edge and a violet rim highlight underneath. Keep glow localized and exact stops subordinate to the object.

### Device ensemble

**Use:** First concrete product proof after the introductory copy.

**Observed:** Tablet, phone and laptop renders overlap across the whole width. The phone stands in front of the tablet, light and dark app appearances coexist, and the laptop extends beyond the right edge. Realistic black bezels and silver hardware frame sharp interface content against near-black.

**Transfer:** Show actual work on the product at readable scale. With no physical device, overlap two honest application windows and a smaller focused view, keeping the dark stage and crisp edges.

### Enlarged interface relief

**Use:** Alternating capability explanations.

**Observed:** Isolated menu, filter bar and statistics panel are enlarged as clean tactile UI objects. Behind them, a much larger tilted outline rendering of the app runs at low contrast across charcoal. The foreground stays bright and legible while background words become texture.

**Transfer:** Select one meaningful interaction per illustration; pair it with a 250–500px prose column and a faint oversized outline of related UI.

**Build:** Draw an SVG wireframe of a relevant interface with thin gray lines and no solid panels, rotate it about -15 degrees and scale it beyond the stage bounds. Set the wireframe to low opacity over #1a1a1a. Place an opaque, front-facing menu or chart above it; use a short dark fade under the foreground object rather than blurring its text.

### Customization parade

**Use:** A tactile personalization chapter.

**Observed:** Three dimensional app icons tilt around an upright central icon. Below the centered text, a row of vivid circular color swatches runs wider than the viewport. A tall app image splits light and dark appearance across its center, with large scattered outline symbols behind it.

**Transfer:** Demonstrate real variation in the new product using a trio of skins or outputs, a swatch rail and a side-by-side appearance comparison.

**Build:** Arrange three rounded-square assets in a centered row with the outer two rotated in opposite directions. Draw a horizontally overflowing rail of equal circles with subtle top highlights. Back the comparison with a repeated SVG pattern of original outline tool symbols at low opacity; use diagonal light/dark bands to echo the chapter edges.

### Utility demonstration theater

**Only for:** utility product pages

**Use:** Feature-by-feature demonstrations and the illustrated ending.

**Observed:** The opening is a desaturated cartoon factory with an app-shaped worker, conveyor belts and piles of content. Feature chapters alternate butter yellow, deep green charcoal, teal and white. Large tilted UI artwork bleeds behind foreground rounded demo panels, whose bottom edges fade into the backing. The footer returns to the dim factory, with a cropped arcade cabinet at left and a compact centered maker mark.

**Transfer:** Use a coherent illustrated workspace metaphor appropriate to the tool. Reuse that environment at the ending; preserve the interplay of oversized tilted background UI and crisp foreground operations.

**Build:** Create one original perspective workspace illustration in grayscale with a few product-color details. For feature chapters, enlarge a related UI window behind the main panel, rotate it slightly and fade it into the chapter color. Add an opaque foreground operation view with 36px corners and a background-colored linear fade along its lower edge.

### Company workshop world

**Only for:** company and support pages

**Use:** Human-story, help and company closing sections.

**Observed:** A large stylized hand holds a wrench against a coral drafting grid; circular team portraits sit in a rounded tonal panel. The help chapter turns white and pairs text with a miniature service truck and tools. A dark blueprint texture closes the page with a small centered maker mark.

**Transfer:** Use one enlarged craft tool beside the human story, a relevant assistance vehicle or object beside help, and a dark technical drawing as the closing material.

**Build:** For the grid, layer two low-opacity perpendicular SVG line sets behind a warm solid fill. For the footer, draw oversized rounded mechanical outlines in gray on dark charcoal, rotate in perspective and fade to black toward the central content.

### Icons

**Observed:** Marketing action icons are solid rather than thin line symbols: 28px lavender in the help pill and 24px social icons in footer links. Feature inventory icons resemble tiny colorful application tiles; large outline icons are confined to background illustration.

**Transfer:** Use compact solid action glyphs matched to the text color and small dimensional or colorful feature icons. Keep decorative wireframe marks much larger and much lower contrast.

## Section recipes

How recurring sections are built.

### First screen: Illustrated product opening

**Observed:** An uninterrupted full-width illustrated stage opens without a conventional navigation bar. From back to front: midnight field, faint stars and violet atmosphere, a huge diagonally cropped prop from the upper left, then the rounded silver product character at right with bright cyan and violet rim light. The illustration occupies about the first 720px. A centered graphic title fills a 386×125px box underneath, pearl-to-lavender from top to bottom, with 40px below. Within the first 900px, the complete object scene and product name are visible and the 24px introductory paragraph just begins; no action is above the fold. The semantic title uses semantic-title; its visible form is artwork rather than ordinary headline text. Introductory paragraphs, the Device ensemble and Graphic download badge follow below.

**Transfer:** Make an original physical metaphor for the new product and compose it with a giant cropped prop, localized luminous light and a dark fade for the product name. Without custom 3D, use the layered vector treatment in Cinematic product personality and an original rounded wordmark. Company pages instead open with one monumental robot-like tool scene and defer their 6vw promise; utility pages place a 48px product title and icon near the bottom of an illustrated workshop.

**Avoid:** Do not replace the scene with a conventional headline-left, dashboard-right SaaS hero or pull all conversion controls into the first screen.

**Text style:** `semantic-title` — -apple-system 400 · 18px/1.5

### Centered introduction and conversion

**Observed:** Two centered 24px lightweight paragraphs in the intro-column use Gradient phrase for short emphases. The full-width Device ensemble follows, then the Graphic download badge, compatibility lines and Support pill.

**Transfer:** Explain what the product is, why it feels good and what makes it dependable; prove it visually before asking for the download.

**Text style:** `intro` — -apple-system 300 · 24px/1.4

### Colored explanatory stage

**Observed:** Violet diagram stage combines a 500px-wide diagram bleeding toward the left edge with a 500px explanatory column. Heading uses 28px/1.1, prose uses 18px/1.5 and the Primary pill finishes the column. Diagonal chapter geometry connects it to the next stage.

**Transfer:** Use an explanatory visual for a difficult concept or organizing principle, not necessarily a network diagram.

### Alternating capability relief

**Observed:** Three enlarged interface objects alternate sides inside the feature-story container. Each sits beside a short heading and 21px lightweight body; faint tilted interface linework spans the backing.

**Transfer:** Alternate operational demonstrations with enough room for each object to have its own silhouette.

**Text style:** `heading` — -apple-system 600 · 28px/1.1

### Oversized device chapters

**Observed:** On the medium-gray Diagonal chapter, one large device enters from the left beside a 500px text block; the next enters from the right beside right-aligned copy. Devices occupy more width than prose and extend to the page edge.

**Transfer:** Demonstrate distinct contexts or modes using the appropriate hardware or full product views.

### Customization spectacle

**Observed:** Customization parade places the icon trio above a centered 28px heading and 640px-wide explanation. The swatch rail and split-appearance product view become the dominant material below.

**Transfer:** Turn a meaningful configurable dimension into a playful visual comparison; use outputs or workflows when themes are not relevant.

**Text style:** `heading` — -apple-system 600 · 28px/1.1

### Open feature inventory

**Observed:** A green 32px chapter label sits 48px above the inventory. Icon feature row components form two columns with a 72px gap, white 24px headings and muted 18px copy over graphite with subdued colored illumination.

**Transfer:** Use this denser register for supporting capabilities after the larger visual demonstrations.

**Text style:** `chapter-label` — -apple-system 600 · 32px/1.1

### Illustrated proof and repeat action

**Observed:** Proof-heading introduces a centered Quotation panel over a huge silver character face. The scene spans 864px vertically and the character extends beyond the page edges. The repeated Graphic download badge, compatibility lines and Support pill sit lower in the same illustrated closing environment. Company footer canvas starts a distinct directory after this scene.

**Transfer:** Repeat the original opening object's material and personality at close range. Place a genuine short quote over it, then a clear final action and useful resource ending.

**Text style:** `quote` — -apple-system 300 italic · 36px/1.2

### Utility demonstration chapter

**Only for:** utility product pages

**Observed:** A 1300px framed band has a 40px slanted edge, 100px top and 60px side/bottom padding. A 60px tightly tracked heading and 30px thin explanation sit over a rounded, edge-attached demo panel. Large related UI art fills the opposite side; caption and 16px slide dots finish the panel.

**Transfer:** Use one operation per colored chapter, alternating left and right or using a centered scene for a particularly important action.

**Text style:** `utility-heading` — -apple-system 800 · 60px/1.05 · tracking -0.05em

### Utility purchase ending

**Only for:** utility product pricing

**Observed:** A broad quotation gives way to Purchase shell containing two Purchase option cards. Prices are bold inline phrases, not display numerals. Warm smoky glass overlaps the desaturated workshop illustration, then the scene continues into a compact illustrated footer with a cropped arcade-like object, maker mark, two social icons and copyright.

**Transfer:** Present genuinely different acquisition routes with equal visual weight, explain ownership plainly and bring the opening world back at the ending.

## Page flow

**Storyline:** Personality and promise → tangible product proof → invitation to try → explanatory and capability chapters → compact capability inventory → editorial proof → repeated conversion → useful maker ending.

### Flagship product story with a cinematic introduction and a broad capability tour

1. **Personality** — Full-width character scene and graphic product name.
2. **Promise and proof** — Centered craft/performance introduction, overlapping device ensemble and download/support cluster.
3. **Explanation** — One colored diagram chapter makes the underlying concept understandable.
4. **Capability chapters** — Alternating interface reliefs, edge-bleeding device views and a customization spectacle.
5. **Capability inventory** — Two open columns of icon-led features.
6. **Social proof and closing call** — Dark quotation glass over a huge character, then the download/support cluster again.
7. **Resource ending** — Separate dark maker introduction, directory columns, contact/social links and copyright.

**Transfer:** Use a few richly staged moments to make a useful product feel cared for, with practical explanations between them.

### Company portfolio with human context and direct support access

1. **Personality** — Monumental illustrated tool characters fill the first screen before the promise appears.
2. **Portfolio** — Large mission statement and four open app-icon columns with platform pills.
3. **Human context** — Coral slanted workshop-grid band, huge wrench illustration, human story and small portrait panel.
4. **Objection handling** — White help section with oversized headline, guide/social/email routes and miniature service-truck illustration.
5. **Resource ending** — Dark blueprint scene with centered mark, copyright and two contact links.

**Transfer:** Use the illustrated world to connect a product family; replace an exhaustive feature tour with portfolio choices and approachable help.

### Utility product tour with operational demonstrations and purchasing choices

1. **Personality and promise** — Illustrated factory opening, icon, compact heavy product title and playful marked-up support sentence.
2. **Conversion** — Download and purchase controls, compatibility and a movie-poster preview.
3. **Capability chapters** — Alternating slanted warm, dark, teal and white stages with UI demonstration panels and captions.
4. **Capability inventory** — Conversational transition followed by two columns of icon-led benefits.
5. **Social proof** — Broad quotation on a soft tonal panel.
6. **Purchase decision** — Two silver cards on warm frosted glass explain direct purchase and subscription.
7. **Illustrated ending** — Return to the workshop, cropped arcade cabinet, compact maker mark, social icons and copyright.

**Transfer:** Use the tighter, heavier typography only for a hands-on utility tour; keep the cinematic frame and tactile UI staging.

## Writing

Warm, proud independent makers explaining useful software with genuine affection. Craft, delight and performance coexist with specific operations; confidence stays conversational rather than institutional.

**Do not copy:** Do not reuse the brand's names, characters, logos, custom artwork, founding dates, team facts, feature counts, pricing, compatibility claims, awards or editorial quotations. Source examples below illustrate syntax and tone only.

- **Addressing the reader:** Address the reader as you and your; use we and our for the makers. Name the product naturally when explaining its behavior.
- **Rhythm:** Short functional headings of one to five words alternate with fuller explanatory paragraphs. Use a question to introduce an unfamiliar concept and a playful aside to relieve a long capability list; exclamation marks are occasional and welcoming.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Product title | A plain product name or a short concrete promise; let the illustration carry the fantasy. | 1–6 words | “Pastebot 3”<br>“Robots for iOS & Mac” |
| Supporting promise | Pair utility with the quality of its experience. | One short sentence or two explanatory sentences | “We strive to craft delightful experiences with simple utilitarian apps.” |
| Capability heading | Name the actual tool or behavior rather than a vague outcome. | 1–4 words | “Multiple Timelines”<br>“Powerful Filters” |
| Instruction caption | A concrete action followed by its practical result. | One sentence | “Start typing to quickly search for a clipping.” |
| Transition | Light conversational aside before a dense list. | One short line | “Okay, deep breath. There’s more…” |
| Action | Simple verb or an approachable question; use the product name only when needed for clarity. | 1–5 words | “Download”<br>“Need Help with Ivory?” |

**Words and phrasing to use:** crafted; delightful; simple; utilitarian; thoughtfully designed; your preferred way; quickly; customize; keep; try for yourself

**Avoid:** enterprise-grade transformation; unlock unprecedented synergy; disruptive ecosystem; dominate your workflow; vague AI superlatives

**Rules:**

- Explain a feature through the task it helps a person perform.
- Balance emotional craft words with concrete details about behavior.
- Keep purchase language unusually plain about what the customer owns and how updates work.
- Make support feel like reaching helpful people, not entering a ticket funnel.

## Do's and Don'ts

### Do

- Keep default section headings at 28px/1.1 and weight 600 beside much larger illustrations.
- Use 24px/1.4 lightweight periwinkle introduction text with short 600-weight gradient phrases.
- Preserve the 72px slanted chapter seam and the 216px / 144px desktop chapter padding.
- Give feature inventories two open columns and 18px/1.4 descriptions rather than individual raised tiles.
- Use a 40px action radius and a declared 1.05 hover scale for the product-page pills.
- Keep quotation glass at rgba(35,35,35,0.8) with 10px backdrop blur and 30px padding.
- Return to the opening object's material and personality in the illustrated closing proof.
- Keep utility pricing as equal 560px cards with inline 18px price emphasis rather than giant numerals.

### Don't

- Do not turn every dark section into the same #111111 rectangle; midnight, charcoal, graphite and medium gray have different jobs.
- Do not apply the utility variant's -0.05em tracking or weight 800 to default 28px headings.
- Do not spread the blue-to-magenta gradient across entire paragraphs; it belongs to short emphases.
- Do not add thin outlined boxes around the open icon feature rows.
- Do not treat 18px semantic title text as the visible opening product name; the 386×125px graphic does that work.
- Do not use rainbow fills for every chapter; vivid customization swatches remain a localized demonstration.
- Do not turn ordinary inline pricing into an oversized numeric dashboard.
- Do not use hard black drop shadows on the default quotation glass or surround it with a bright border.

## Motion and responsive

### Motion

**Observed:**

- Product help, pale action and download controls declare 0.15s ease-out transitions with hover scale(1.05) and active translateY(2px).
- Footer text links declare 0.1s ease-in-out with white hover text, scale(1.1) on hover and scale(1) while active.
- A quotation item declares a 36s ease-in-out infinite fade animation with a 9s delay.

**Transfer:**

- Keep action feedback small and springless; use the declared scale and press displacement rather than a large animated scene reaction.
- If rotating proof quotations, retain the long unhurried fade cadence and keep the panel readable over the character.

**Unknown:**

- The complete fade keyframes, precise crossfade sequence and actual playback behavior are not specified.
- Focus-visible appearance is not established.

### Responsive

**Observed:**

- Default product styles declare width breakpoints at 414px, 500px and 700px.
- Company styles declare 600px and 900px breakpoints; company display headings use 6vw or 7vw and support lines use 3vw.
- Utility styles declare 599px, 899px and 999px breakpoints; default diagonal chapter spacing follows 15vw top, 10vw bottom and -5vw overlap.

**Transfer:**

- On narrow screens, preserve the object-first opening and readable graphic name; simplify the number of overlapping props rather than shrinking the whole scene to an illegible thumbnail.
- Stack illustration/copy pairs and feature columns when necessary, retaining the slanted seams and the dark/light chapter contrast.

**Unknown:**

- Exact mobile arrangements, type overrides, device-image substitutions and navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
