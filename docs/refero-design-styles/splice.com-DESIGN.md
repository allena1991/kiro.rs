# Splice — electric creator stages

## Overview

A dark, performance-led style that pairs wide grotesk headlines with candid footage of people making things. Electric blue actions cut through charcoal layouts, while pink, cyan and violet turn selected product chapters into bright visual breaks. Real interfaces, playable previews and large photographic panels make it feel hands-on rather than abstract. It suits creative tools and product ecosystems that need both emotional invitation and practical explanation.

### Essentials

- Headlines have the width and presence of a record sleeve: SoehneBreit at 48px/1.25 with -0.0179em tracking for the main promise, 36px/1.25 for section headings, and 28px/1.25 for benefits.
- The opening is a working-person film, not a centered software slogan: full-width media fills a 789px stage below a 111px combined promotion and navigation band; a three-line white promise sits low on the left above a 400px-wide blue action.
- Conversion controls look like smooth transport buttons: blue #1253ff pills use a 64px radius and 32px horizontal padding; the compact navigation action reverses to white with dark text and a 100px radius.
- Color arrives as a loud break in a mostly charcoal performance: #121214 is the continuous canvas, #232426 supports previews, and large pink, cyan or violet fills belong to isolated product panels rather than every section.
- Proof is something to experience: combine a tall human portrait with compact artifact previews, circular 50px play controls and visible waveform-like traces. For non-audio products, use real outputs and previewable before/after work with the same dense control-strip treatment.
- Oversized single corners turn rectangles into branded stages: editorial panels pair a 128px top-left corner with 8px remaining corners; product banners use a 180px corner. Include this asymmetric framing and a large photographic invitation somewhere in a new landing page, using a documentary still when film is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric action blue | `#1253ff` | `--color-action` | action, background | Primary buttons and selected product feature panels. |
| Link blue | `#528fff` | `--color-link` | link, text | Inline links and declared action hover text. |
| Signal blue | `#0033ff` | `--color-band-blue` | background, action | Promotion strip, pricing closing band and primary-action hover fill. |
| Pressed blue | `#0029cc` | `--color-active-blue` | text, action | Active chip text and primary pressed-state fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm pink | `#ff8aa6` | `--color-pink` | background, text | Product carousel panels and scoped subscription prices. |
| Bright cyan | `#62daff` | `--color-cyan` | background, text | Product banners and selected testimonial accents. |
| Orchid violet | `#b874ff` | `--color-violet` | background, text | Product banners and selected testimonial accents. |
| Acid label yellow | `#f1f607` | `--color-label-yellow` | text | Small uppercase category lead-ins; also a pricing testimonial accent. |
| Selected chip wash | `#bee1ff` | `--color-selected-wash` | surface | Active category chip background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, border | Main headings, icons, white actions and the opening media-strip rule. |
| Headline white | `#fafafb` | `--color-headline-white` | text | Opening promise; slightly softened relative to pure white. |
| Soft body gray | `#c8c9cc` | `--color-body` | text, border | Supporting paragraphs, footer links and white-button edges. |
| Muted label gray | `#a6a8ad` | `--color-muted` | text | Navigation, asset metadata and secondary descriptions. |
| Control edge | `#63656d` | `--color-control-edge` | border, surface | Chip and circular-player outlines; selected secondary hover fills. |
| Secondary edge | `#45464d` | `--color-button-edge` | border, surface | Outlined media buttons and inactive carousel tracks. |
| Section hairline | `#303236` | `--color-rule` | border | FAQ dividers and technical-band edges. |
| Preview charcoal | `#232426` | `--color-panel` | surface | Editorial preview panels, play controls and technical bands. |
| Charcoal canvas | `#121214` | `--color-canvas` | background, text | Continuous marketing background and reversed text on bright panels. |
| Media black | `#000000` | `--color-black` | background, text | Media backing and strong gradients over photography. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| software product explanations | Glow backing navy | `#000a33` | `--color-navy` | surface | Deep blue benefit cards beneath violet light. |
| pricing pages | Offer green | `#a6ff72` | `--color-offer-green` | text, accent | Promotional price, savings badges and checks. |
| flagship product stories | Warm neutral | `#dbd9cf` | `--color-cream` | surface | Interlocking editorial testimonial panels. |
| flagship product stories | Acid panel yellow | `#f1f60a` | `--color-panel-yellow` | background | Full carousel-panel fill rather than small category text. |
| pricing and flagship product panels | Translucent panel edge | `#252527` | `--color-faint-edge` | border, surface | Visible result of white at 8% over the charcoal canvas; pricing module boundaries and translucent panels. |

## Typography

- **SoehneBreit** — Promises, section headings, feature titles and short uppercase category labels. Extended grotesk with broad bowls and substantial horizontal presence, even at the declared regular weight. If unavailable, use **Archivo Expanded**. Use 500–700 as needed to retain the broad, sturdy silhouette; do not substitute a narrow sans. Font stack: "SoehneBreit", "Archivo Expanded", Arial, sans-serif.
- **InterVariable** — Body, navigation, controls, metadata and FAQs. Neutral variable sans with readable compact detail and clear numerical forms. If unavailable, use **Inter**. Font stack: "InterVariable", "Inter", -apple-system, system-ui, Arial, sans-serif.
- **Soehne** (only for pricing pages) — Large pricing numerals. Less extended grotesk that keeps price figures compact beside plan information. If unavailable, use **Inter**. Font stack: "Soehne", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing-line | SoehneBreit | 400 | 54.4px | 77.7px | normal | size clamp(1.5rem, 6vw, 3.4rem) | Centered invitation over full-width working-life photography. |
| promise | SoehneBreit | 400 | 48px | 1.25 | -0.0179em | size clamp(2.25rem, 1.85rem + 2.38vw, 3rem) | Main marketing promise and company-story opening. |
| editorial-title | SoehneBreit | 400 | 48px | 1.25 | normal | size clamp(1.75rem, 4vw, 3rem) | Short multiline story title over a tall portrait. |
| section-heading | SoehneBreit | 400 | 36px | 1.25 | -0.0111em | fixed | Core section lead; left aligned for chapters, centered for demonstrations. |
| benefit-heading | SoehneBreit | 400 | 28px | 1.25 | -0.0069em | fixed | Benefits and product-banner headings. |
| footer-heading | InterVariable | 700 | 20px | 1.429 | normal | fixed | Footer category heads. |
| hero-button | InterVariable | 500 | 18px | 1.2 | normal | fixed | Wide action beneath the opening promise. |
| body | InterVariable | 400 | 16px | 1.5 | normal | fixed | Paragraphs and detailed explanations. |
| nav-label | InterVariable | 500 | 16px | 1.5 | normal | fixed | Navigation and compact white conversion action. |
| button | InterVariable | 500 | 16px | 1.2 | normal | fixed | Standard primary and media actions. |
| eyebrow | SoehneBreit | 400 | 14px | 1.25 | 0.0714em, uppercase | fixed | Acid-yellow category introduction above a white section heading. |
| small-label | InterVariable | 400 | 14px | 1.43 | normal | fixed | Category chips and short artifact links. |
| footer-link | InterVariable | 400 | 12px | 1.43 | normal | fixed | Compact footer directory and utility links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| software product openings | software-title | SoehneBreit | 400 | 72px | 1 | -0.0179em | fixed | Three-line product name beside a large interface demonstration. |
| pricing pages | pricing-outcome | SoehneBreit | 700 | 72px | 1.111 | -0.0156em | fixed | Oversized gradient outcome line. |
| pricing pages | price | Soehne | 700 | 70.9px | 82.8px | -0.0156em | fixed | Plan price with smaller per-period suffix and optional struck former price. |
| flagship product openings | flagship-promise | SoehneBreit | 700 | 48px | 1.167 | -0.0156em | fixed | Compact bold capability promise beside square product artwork. |
| flagship product subscription sections | product-price | SoehneBreit | 700 | 48px | 1 | -0.02em | size clamp(2.25rem, 1.85rem + 2.38vw, 3rem) | Pink single-product subscription price. |
| pricing pages | pricing-lead | SoehneBreit | 700 | 47.8px | 1.2 | -0.0156em | fixed | White introductory line above a rotating outcome. |
| pricing proof rails | testimonial-quote | InterVariable | 200 | 40px | 1.2 | -0.02em | fixed | Very light colored quotation beneath a video thumbnail. |
| pricing pages | pricing-heading | SoehneBreit | 700 | 36px | 1.111 | -0.014em | fixed | Pricing modules and their closing call. |
| flagship product stories | warm-panel-heading | SoehneBreit | 400 | 36px | 1.333 | normal | fixed | Dark text inside warm interlocking testimonial panels. |
| software product openings | software-deck | InterVariable | 500 | 28px | 1.25 | -0.0069em | fixed | Two-line proposition below the software title. |
| pricing and product support sections | faq-question | InterVariable | 700 | 20px | 1.25 | -0.0042em | fixed | Accordion questions and expanded technical questions. |
| software product explanations | software-card-title | SoehneBreit | 400 | 20px | 1.25 | -0.0042em | fixed | Glowing benefit-card title. |
| pricing proof rails | quote-credit | InterVariable | 500 | 12px | 1.333 | 0.083em, uppercase | fixed | Small widely tracked attribution beneath a quote. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Broad display letterforms supply the visual weight; keep Inter for long reading and controls rather than using the display face everywhere.
- Core display sizes use a 1.25 line-height. Short software names tighten to 1, while the closing invitation is deliberately more open.
- Do not normalize regular marketing headings and bold pricing or flagship headings into one weight. Their different widths and density define different page types.

## Layout

**Density:** Airy at section scale, dense inside previews: substantial dark intervals surround compact artifact rows and controls.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Benefit title-to-support gap and footer item separation. |
| 16px | Eyebrow-to-heading gap, small copy groups and promotion padding. |
| 20px | Artifact-row gaps and navigation side inset. |
| 24px | Software benefit-card padding and grid gaps. |
| 32px | Default grid gutter, editorial panel padding and headline-to-action gap. |
| 48px | Artifact-list row spacing and inner chapter breathing room. |
| 64px | Pricing module vertical padding and FAQ heading separation. |
| 80px | Core chapter separation, footer lead-in and bottom padding. |
| 96px | Large chapter openings and spacious product layouts. |
| 120px | Software demonstration and proof chapter separation. |

### Containers and grids

- **Core content**: max width 1175px · 12 columns · gap 32px · side padding 32px. Centered marketing content occupies about 1175px at a 1440px viewport, with actual side margins about 133px. Full-width films and closing images break out of it.
- **Paired catalog**: 2 columns · gap 32px. Two equal-width chapters: compact preview rows on one side and illustrated product descriptions on the other.
- **Footer directory**: max width 1175px · 5 columns · gap 32px. Four narrow categories and one wider organizational category on a twelve-column foundation.
- **Product content** (only for pricing and product pages): max width 1312px · 12 columns · gap 32px · side padding 64px. Wider pricing and product chapters; two balanced text/media halves or three plan columns.
- **FAQ measure** (only for pricing and software support sections): max width 1024px. Inset accordion measure with paragraphs capped at 850px.
- **Benefit grid** (only for software product explanations): 3 columns · gap 24px. Two rows of deep-blue illuminated benefit cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Primary pills | 64px |
|  | Navigation action | 100px |
|  | Secondary controls and chips | 8px |
|  | Editorial frame | 128px |
|  | Banner corner | 180px |
|  | Play controls | 50% |
| software product explanations | Benefit cards | 16px |
| flagship product stories | Feature carousel panels | 24px |
| flagship product stories | Warm editorial blocks | 32px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Thumbnail edge | `0px 0px 0px 1px rgba(0, 0, 0, 0.07) inset` | Subtle definition for square cover art; not a general card elevation. |
| flagship product demonstrations | Interface stage | `0px 30px 70px -30px rgba(0, 0, 0, 0.867)` | Large interface panel floating just above the charcoal canvas. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous page background.

**CSS:** `background: #121214; color: #ffffff`

#### Media backing · level 0

**Use:** Full-bleed opening film base.

**CSS:** `background: #000000; overflow: hidden`

**Observed:** Natural-light footage is darkened toward the lower left so the white promise can sit directly over it.

**Transfer:** Keep a plausible real environment visible; use directional darkening instead of flattening the entire image.

#### Media information strip · level 1

**Use:** Opening support paragraph, signal drawing and secondary media action.

**CSS:** `background: rgba(0, 0, 0, 0.5); border-top: 1px solid #ffffff; backdrop-filter: blur(100px); padding: 16px 0px`

**Observed:** A full-width 105px band anchors the bottom of the film; its information aligns with the narrower content container.

**Transfer:** Use it as a grounded annotation layer, not a floating glass card.

#### Editorial stage · level 1

**Use:** Human story joined to interactive product previews.

**CSS:** `background: #232426; border-radius: 128px 8px 8px 8px; overflow: hidden; display: grid; grid-template-columns: 1fr 1.15fr`

**Observed:** A tall image occupies the smaller half; square covers, metadata, previews and a full-width action occupy the other.

**Transfer:** Preserve the combined narrative-and-artifact construction.

#### Color-break stage · level 1

**Use:** Wide product banner with an exceptionally rounded corner.

**CSS:** `background: #ff8aa6; border-radius: 0px 0px 0px 180px; overflow: hidden; color: #121214`

**Observed:** Pink, cyan and violet versions pair short copy with a large interface or device image; individual variants can move the oversized corner.

**Transfer:** Choose one bright fill for a chapter and leave the surrounding canvas dark.

#### Illuminated benefit card · level 1

**Only for:** software product explanations

**Use:** Practical promises with large simple symbolic artwork.

**CSS:** `background: #000a33; border-radius: 16px; padding: 24px; overflow: hidden; position: relative`

**Observed:** A violet-blue pool of light blooms behind an oversized white symbol in the lower half. The top remains dark enough for a small title and paragraph.

**Transfer:** Use the glow construction described under imagery with a new, readily legible symbol.

#### Warm interlocking panels · level 1

**Only for:** flagship product stories

**Use:** Editorial testimonial and product-quality explanation.

**CSS:** `background: #dbd9cf; border-radius: 32px; color: #121214`

**Observed:** Offset cream blocks interlock around a warm photograph with a pink side strip; dark negative-space channels separate the rounded shapes.

**Transfer:** Use staggered rectangles rather than a uniform bento grid.

#### Signal closing band · level 0

**Only for:** pricing pages

**Use:** Final conversion after objections.

**CSS:** `background: #0033ff; border-top: 1px solid rgba(255, 255, 255, 0.08); padding: 64px 0px`

**Observed:** White heading and support sit left, a compact white pill and reassurance sit right.

**Transfer:** Keep the band short, direct and visibly different from the preceding dark FAQ.

## Components

### Primary button

**Use:** Main conversion or media-entry action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #1253ff; color: #ffffff; border: 1px solid transparent; border-radius: 64px; padding: 13.5px 32px; height: 48px; box-sizing: border-box`

**Text style:** `button` — InterVariable 500 · 16px/1.2

**Observed:** Centered single label; may expand across the preview column. The opening version is 400px wide, about 51px tall and uses hero-button type.

**States:** Declared: hover color #528fff, background #0033ff, border-color #0033ff and underline; active background and border-color #0029cc with white text.

### White navigation action

**Use:** Persistent conversion at the far right of navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; color: #121214; border: 1px solid #c8c9cc; border-radius: 100px; padding: 8px 20px; height: 42px; box-sizing: border-box`

**Text style:** `nav-label` — InterVariable 500 · 16px/1.5

**Observed:** Compact and content-width, separated from the login link; not the large opening action.

**States:** Declared: hover transform scale(1.03), color #528fff and underline; focus-visible transform scale(1.03).

### Global navigation

**Use:** Dark horizontal brand and category bar above the main stage.

**CSS:** `display: flex; align-items: center; background: #121214; padding: 10px 20px 0px; height: 56px; box-sizing: border-box`

**Text style:** `nav-label` — InterVariable 500 · 16px/1.5

**Observed:** White brand mark left, muted category links across the middle, login and White navigation action right. Active product categories become white with a thin blue or pink underline. The bar stays visible while the content moves.

### Media button

**Use:** Secondary film action inside the opening annotation band.

**CSS:** `background: transparent; color: #ffffff; border: 1px solid #45464d; border-radius: 8px; padding: 11px 32px; height: 48px; box-sizing: border-box`

**Text style:** `button` — InterVariable 500 · 16px/1.2

**Observed:** Text followed by an outlined play triangle; deliberately squarer than conversion pills.

**States:** Declared: hover and active background #45464d, border-color #45464d and white text.

### Category chip

**Use:** Compact filtering above preview rows.

**CSS:** `background: transparent; color: #ffffff; border: 1px solid #63656d; border-radius: 8px; padding: 5px 16px; height: 32px; box-sizing: border-box`

**Text style:** `small-label` — InterVariable 400 · 14px/1.43

**Observed:** Wraps across rows with 8px horizontal gaps. Active chip reverses to pale blue with deep-blue text; the extra-categories link uses link blue.

### Preview play control

**Use:** Hands-on artifact preview beside cover art.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 50px; height: 50px; background: #232426; color: #ffffff; border: 1px solid #63656d; border-radius: 50%`

**Observed:** Solid white triangular icon centered inside a circular outline. A 72px square cover precedes it; filename, linked collection title and waveform follow. Larger cover overlays use black 70px circles.

**States:** Declared: hover white background and #121214 foreground.

**Transfer:** For non-audio output, use the circle to launch a short preview rather than decorating a static row.

### Editorial preview panel

**Use:** Rich human-story carousel item.

**CSS:** `display: grid; grid-template-columns: 1fr 1.15fr; background: #232426; border-radius: 128px 8px 8px 8px; overflow: hidden`

**Text style:** `editorial-title` — SoehneBreit 400 · 48px/1.25

**Observed:** Portrait and bottom-aligned story headline on the left; two cover previews above compact artifact rows on the right; Primary button across the bottom. A centered row of 48px by 8px pill tracks sits below the panel.

### Promotion strip

**Use:** Short time-sensitive announcement above navigation.

**CSS:** `background: #0033ff; color: #ffffff; padding: 16px; text-align: center`

**Text style:** `nav-label` — InterVariable 500 · 16px/1.5

**Observed:** Single sentence with an inline underlined action; about 55px tall, with no icon or dismiss box.

### Footer directory

**Use:** Large quiet ending after the final narrative section.

**CSS:** `background: #121214; padding-bottom: 80px`

**Text style:** `footer-link` — InterVariable 400 · 12px/1.43

**Observed:** Five category columns with footer-heading titles and 8px link separation; the last is wider. Legal links form a separate low horizontal row, followed by copyright at left and five small social icons at right. The compact software variant keeps only utility links, copyright and social icons.

**States:** Declared: footer links hover to white with underline; color transition 0.2s.

### FAQ row

**Only for:** pricing and product support sections

**Use:** Resolve practical objections without separate cards.

**CSS:** `max-width: 1024px; border-bottom: 1px solid #303236`

**Text style:** `faq-question` — InterVariable 700 · 20px/1.25 · tracking -0.0042em

**Observed:** Question and small right chevron share a full-width summary with 20px vertical padding. Expanded answers use body type, an 850px maximum measure and a 32px bottom interval. Some flagship support sections show all answers openly rather than collapsed.

### Illuminated benefit tile

**Only for:** software product explanations

**Use:** Explain access, ownership or workflow promises.

**CSS:** `display: flex; flex-direction: column; gap: 20px; position: relative; background: #000a33; border-radius: 16px; padding: 24px; overflow: hidden`

**Text style:** `software-card-title` — SoehneBreit 400 · 20px/1.25 · tracking -0.0042em

**Observed:** Title and concise paragraph are grouped at the top. A large symbol sits over an electric blue-violet bloom below; three cards form a row.

### Pricing column

**Only for:** pricing pages

**Use:** Compare paid offers without heavy card boxes.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding-right: 32px`

**Text style:** `body` — InterVariable 400 · 16px/1.5

**Observed:** Plan name and audience line precede a large price, period and optional offer label. Feature rows use faint horizontal rules and small checks or information icons. Neighboring columns have faint vertical separators. The recommended offer uses green price text and a blue pill; the second uses muted white pricing and an outlined pill. A third column lists shared features.

## Imagery and graphics

### Working-life cinema

**Use:** Opening stage and large invitation imagery.

**Observed:** Candid creators using real equipment in lived-in workspaces, shown wide and close rather than as isolated cutouts. Natural window light, warm wood and muted greens remain visible beneath a dark lower fade. The opening image fills nearly the whole first screen behind relatively compact left-hand text.

**Transfer:** Photograph a real person using the new product in an authentic environment. Minimum version: one well-framed documentary still with clear dark space for type; retain the full-width scale.

### Signal trace

**Use:** Graphic punctuation in the opening information strip and artifact previews.

**Observed:** A thin irregular white oscillating line rises from low amplitude into tall loops near the center of the annotation band. Compact previews use dense gray vertical amplitude bars instead.

**Transfer:** Translate the product's activity into an irregular trace: audio amplitude, editing history or process output. Keep it integrated with a useful annotation or preview.

**Build:** Draw an unfilled SVG path in a 440px by 100px viewBox with a 2px white stroke. Begin with small shallow oscillations, increase amplitude toward the right half, and let the tallest loops exceed the band bounds. For row traces, use 2px vertical gray bars with 1px gaps and varied heights; never use a smooth decorative sine wave everywhere.

### Artifact and interface staging

**Use:** Catalog chapters, editorial proof and product demonstrations.

**Observed:** Square full-color covers sit against charcoal with very small corner radii. Large interface views retain legible controls and real dense content; some fill a near-full-width frame while smaller feature details float in open black space. Marketing text remains outside the interface.

**Transfer:** Show recognizable real outputs and selected interface detail. Preserve enough content to explain the feature rather than presenting empty ornamental windows.

### Bright split banner

**Use:** Signature change of pace within the dark narrative.

**Observed:** A near-full-width colored panel pairs short black copy and a blue action with an oversized interface or device image. Product media occupies more than half the width, often touching the panel edges. One very large corner cuts into the media side.

**Transfer:** Use a real outcome or close interface view on one side and a short benefit on the other; reproduce the bold framing even when the media is only a still.

**Build:** Use a two-column wrapper on the charcoal canvas, a solid pink, cyan or violet fill, and an overflow-hidden 180px single corner. Let the media cover its half and align the text to the ordinary content inset.

### Blue-violet bloom

**Only for:** software product demonstrations and benefit grids

**Use:** Tie floating interface fragments and benefit illustrations to the dark page.

**Observed:** Electric blue and violet light pools behind interface fragments, feathering into the canvas with no hard rectangular border. Benefit cards concentrate the light low in the frame beneath white symbols.

**Transfer:** Use light to frame the action being demonstrated, not to tint every paragraph or background.

**Build:** Place two overlapping elliptical radial gradients behind the media: a blue rgba(18,83,255,0.65) ellipse about 360px by 200px and a violet rgba(184,116,255,0.5) ellipse about 280px by 220px offset 80px right and 40px down. Blur the layer 50px, mask its outer edge to transparent and keep the upper text zone dark. In cards, center the bloom near the bottom edge; exact stops are not essential.

### Pricing light field

**Only for:** pricing pages

**Use:** Atmospheric backdrop behind a rotating outcome and initial comparison section.

**Observed:** A dim blue-violet-green field of soft vertical marks sits mostly to the right of the text and fades into charcoal. The outcome line is clipped to a bright cyan-to-violet gradient; alternate outcomes use warmer hues.

**Transfer:** Keep the price comparison readable by treating the pattern as low-contrast atmosphere rather than a vivid full-page gradient.

**Build:** Create repeated 4px by 14px rounded SVG marks on a 20px grid, stagger their opacity, blur 5px and mask into a broad right-hand ellipse. Tint with cyan and violet at low alpha. Clip a separate cyan-to-violet linear gradient to the outcome text.

### Warm editorial interlock

**Only for:** flagship product stories

**Use:** Human endorsement linked to a product-quality chapter.

**Observed:** A warm piano-room portrait is inset beside cream text blocks with broad rounded corners; a pink strip anchors the image edge. The cream blocks step around the photo with a dark rounded channel between them.

**Transfer:** Use a portrait of someone doing skilled work and two offset neutral text panels. Minimum version: a photo rectangle and staggered 32px-radius blocks separated by a visible charcoal gutter.

**Build:** Arrange an image across the upper-left half and a tall cream block on the right, then extend a second cream block beneath the left image. Use 32px corners and 32px dark spacing. Add a pink 108px-wide side strip to the photo wrapper.

### Creator proof rail

**Only for:** software and pricing proof sections

**Use:** Combine people, scale and endorsement without a logo wall.

**Observed:** Horizontal photographic cards extend beyond the viewport. Software portraits carry large bottom-aligned white names beside a bright numeric proof card; pricing cards put thin colored quotes below rounded video thumbnails, with small uppercase credits.

**Transfer:** Alternate a genuine customer story and a substantiated scale statement. Preserve the visual contrast between photographic proof and the bright graphic card.

**Build:** For a graphic proof card, use a 16px rounded rectangle with a blue-violet bloom, one 64px white growth symbol near the top and a 36px multiline number-led statement below. Add subtle translucent diagonal texture; keep details subordinate to the number.

### Icons

**Observed:** Simple high-contrast symbols: solid 24px controls, small 20px chevrons and information icons, and larger white benefit symbols. Play triangles are solid in circular controls; the opening secondary action uses an outlined triangle. Benefits use recognizable waveform, download, return-arrow, check and ownership metaphors.

**Transfer:** Choose direct functional silhouettes with consistent optical weight. Keep small icons gray or white; reserve cyan, green and pink for scoped proof and offer cues.

## Section recipes

How recurring sections are built.

### First screen: Cinematic working-person opening

**Observed:** The first 900px contains a 55px electric-blue promotion strip, a 56px charcoal Global navigation and a 789px full-width film stage. Back to front: black backing, candid working-life film, dark lower-left fade, white three-line promise, wide blue action, then the Media information strip. The promise uses promise type at 48px/60px and spans less than half the viewport, anchored low at the core content left edge; the person and working environment remain the larger object. Primary button sits 32px below it, 400px wide with hero-button type. The 105px bottom strip contains a 500px support paragraph on the left, an irregular white signal trace through the center and Media button on the right. The complete hero and annotation are visible within the first screen; catalog chapters start below it.

**Transfer:** Use an equally immersive film or documentary still of a new user's real work, not a generic product render. Make the activity the large object and retain low-left type, wide action and annotated bottom band. Company stories use the same photographic language with a simpler 48px opening and longer deck; software products use a 72px stacked product name at left and interface scene at right; flagship products use a 48px bold promise beside square artwork. Pricing opens with a white lead plus a 72px gradient outcome over a dim light field.

**Avoid:** Do not replace the stage with a centered headline above a small laptop mockup or move all support copy into a floating central card.

**Text style:** `promise` — SoehneBreit 400 · 48px/1.25 · tracking -0.0179em

### Category and hands-on catalog pair

**Observed:** Two equal columns inside Core content begin with a 14px yellow uppercase eyebrow, 16px gap and 36px white heading. One column uses Category chip controls and compact cover/play/trace rows; the other uses horizontal product-image and description rows. Both end in a short blue action.

**Transfer:** Pair two major product modes, with tangible examples on one side and explanations on the other. Keep the rows on the open canvas rather than boxing each one.

**Text style:** `section-heading` — SoehneBreit 400 · 36px/1.25 · tracking -0.0111em

### Human story with usable artifacts

**Observed:** Editorial preview panel combines a tall portrait and multiline title with cover art, playable rows and a broad action. Its Editorial stage surface carries the oversized asymmetric corner. Neighboring items peek into the horizontal carousel; muted pill indicators sit below.

**Transfer:** Show a customer or maker alongside the work they produced, including previewable output or meaningful detail rather than only a quote.

**Text style:** `editorial-title` — SoehneBreit 400 · 48px/1.25

### Unboxed assurance row

**Observed:** Three centered benefit groups stand directly on Canvas. White icons sit above 28px benefit-heading text and one short support sentence, with an 8px text gap and about 80px between groups.

**Transfer:** Use this for three concise risk reducers or practical assurances, not a second long feature grid.

**Text style:** `benefit-heading` — SoehneBreit 400 · 28px/1.25 · tracking -0.0069em

### Color-break product chapter

**Observed:** Color-break stage sits wider than ordinary text content, about 1376px by 515px at desktop. Brief text and a compact blue pill sit beside a large interface or device scene. Pink, cyan and violet variants punctuate the dark page; a carousel shows slim neighboring panels and pill indicators.

**Transfer:** Include a bright, asymmetric product-output banner somewhere in the story. Give each panel one benefit and enough actual product imagery to prove it.

**Text style:** `benefit-heading` — SoehneBreit 400 · 28px/1.25 · tracking -0.0069em

### Photographic invitation ending

**Observed:** A full-width 648px working-life photograph closes the marketing story. Centered closing-line type in white spans the content width above a blue action with a 45px interval. Dark overlays protect text without removing the warm lived-in environment. Footer directory follows after an 80px interval. A company-story variant uses a smaller 36px centered invitation over a darker studio collage.

**Transfer:** Close with the user's desired activity in view and one invitational line; use a strong still when film is unavailable.

**Text style:** `closing-line` — SoehneBreit 400 · 54.4px/77.7px

### Alternating software demonstrations

**Only for:** software product pages

**Observed:** A centered 36px section lead introduces a sequence of isolated feature demonstrations. Interface fragments float in Blue-violet bloom on one side, short white headings and gray body copy on the other; sides alternate with large 120px-scale chapter intervals. A large 1088px by 612px walkthrough follows as a rounded video stage.

**Transfer:** Explain one workflow action per scene. Enlarge the relevant interface fragment rather than repeating a complete small application window.

### Illuminated promise grid

**Only for:** software product explanations

**Observed:** A left-aligned section lead and support line precede a three-column, two-row grid with 24px gaps. Illuminated benefit tile uses a dark upper copy zone and a large white symbol over lower violet light.

**Transfer:** Use for concrete access, workflow or ownership assurances. Keep symbol vocabulary simple and headlines short.

**Text style:** `software-card-title` — SoehneBreit 400 · 20px/1.25 · tracking -0.0042em

### Open pricing comparison

**Only for:** pricing pages

**Observed:** A 36px bold heading leads a rounded monthly/yearly selector. Three open columns sit beneath: two plans and a shared-features list. Price type is 70.9px, with small period text and promotional green reserved for the featured offer. Faint row and column rules organize information without solid card backgrounds.

**Transfer:** Expose tradeoffs directly. Align actions toward the bottom and keep shared features separate from plan-specific ones.

**Text style:** `price` — Soehne 700 · 70.9px/82.8px · tracking -0.0156em

### Support-led endings

**Only for:** pricing and product support sections

**Observed:** Pricing ends with inset FAQ row components, Signal closing band and Footer directory. Software download pages end with a narrow left download block containing a three-step sequence, blue pill and format tags beside a wider FAQ accordion; only compact legal and social footer rows follow. Flagship product pages finish with long open FAQ answers and the full directory, without adding another photographic call.

**Transfer:** Choose the ending that resolves the page's actual decision: emotional invitation for broad marketing, one final offer for comparison, installation guidance for a download, or detailed compatibility answers for a technical purchase.

## Page flow

**Storyline:** Lived-in promise → tangible product experience → human proof and practical benefits → decision support → invitation or direct next step → quiet directory.

### Introduce a creative product ecosystem

1. **Promise** — Immersive human film with low-left headline, broad action and annotated media band.
2. **Product experience** — Two parallel catalog chapters with filters, artifact previews and product images.
3. **Human proof** — Editorial carousel joins a working portrait to actual output.
4. **Risk reduction** — Three centered unboxed assurances.
5. **Capability spotlight** — Bright wide product banners with asymmetric corners.
6. **Closing invitation** — Full-width work-life photo, centered large line and single action.
7. **Wayfinding** — Five-column directory followed by legal and social rows.

**Transfer:** Use the user's work to connect an ecosystem of tools; let previewable outcomes do more than abstract feature claims.

### Explain an organization through its people, credibility and offering

1. **Identity promise** — Full-width darkened creator collage with compact left title and explanatory deck.
2. **Context** — Video collage beside a longer company explanation.
3. **Credibility** — Alternating press or milestone image-and-copy pairs with small blue actions.
4. **Future direction** — Light cyan-to-neutral band with a product-interface collage and dark text.
5. **Offering overview** — Four centered illustrated pillars with short headings and inline links.
6. **Closing invitation** — Dark studio photo collage with centered 36px invitation and blue pill.
7. **Wayfinding** — Full directory, legal, copyright and social rows.

**Transfer:** Translate milestones and editorial coverage into genuine organizational proof; retain alternating visual weight rather than a uniform timeline.

### Help a visitor choose an offer and trust its terms

1. **Outcome promise** — White lead and oversized rotating gradient outcome over dim patterned light.
2. **Risk reduction** — Four compact icon-led assurances before the comparison.
3. **Pricing** — Billing selector, two open plan columns and shared-feature list.
4. **Trust** — Principles beside a large photo masked into an abstract diagonal emblem.
5. **Social proof** — Horizontal video cards with very light colored quotes and small uppercase credits.
6. **Objection handling** — Inset FAQ accordion.
7. **Closing action** — Short electric-blue band with white heading and white pill.
8. **Wayfinding** — Full directory and utility footer.

**Transfer:** Separate outcome, offer, trust and terms rather than adding every persuasion element inside plan cards.

### Demonstrate a downloadable software workflow

1. **Product promise** — 72px stacked name and download action beside a large interface film.
2. **Capability chapters** — Alternating glowing interface fragments with short action-led explanations.
3. **Demonstration** — Large playable walkthrough on charcoal.
4. **Human trust** — Full-width artist-work collage with a bottom fade and concise ethical promise.
5. **Practical benefits** — Six deep-blue cards with white symbols over violet light.
6. **Quantified and human proof** — Moving portrait rail punctuated by a bright scale-stat card.
7. **Closing action and support** — Download steps and action beside FAQ; compact utility, copyright and social footer.

**Transfer:** Carry one download action throughout, explain concrete workflow improvements and resolve installation questions at the end.

### Present a flagship creative tool and its subscription

1. **Capability promise** — Bold 48px promise beside square artwork, preview controls and two actions.
2. **Product demonstration** — Oversized detailed interface with numbered callouts.
3. **Breadth** — Tabbed cover-art rail of playable presets or outputs.
4. **Human proof** — Long testimonial above staggered warm-neutral editorial panels.
5. **Capability spotlight** — Large pink, blue and acid-yellow carousel panels.
6. **Compatibility** — Charcoal technical band with platform and format detail.
7. **Pricing** — Two-column subscription summary with pink price and broad blue action.
8. **Objection handling** — Long, openly expanded FAQ answers, then full directory and utility rows.

**Transfer:** Balance expressive artwork with precise interface and compatibility information; let support be the final persuasion instead of forcing another conversion banner.

## Writing

Confident, practical and creator-to-creator. It sells possibility with punchy promises, then earns trust through clear workflow verbs, ownership terms and straightforward reassurance.

**Do not copy:** Do not reuse Splice names, logos, product artwork, artist likenesses, quotes, catalog counts, pricing, discount offers, partnerships or rights and ethical claims. Replace them with verified facts and original assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. Use we or our for the provider's responsibilities; product names appear plainly when needed for technical clarity.
- **Rhythm:** Short outcome-led headlines alternate with compact conversational paragraphs. Fragments, repeated clauses and em dashes make the copy feel spoken; detailed FAQ answers become direct explanatory prose.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A category-strength claim immediately connected to a user benefit. | 7–13 words | “The industry’s top sample library—royalty-free for all.” |
| Feature headline | Concrete action or outcome, often split into two short clauses. | 4–10 words | “Play pianos, strings, synths and more.”<br>“Free to play. Free to create.” |
| Support | Explain the task in familiar verbs rather than abstract platform language. | 1–3 compact sentences | “Our catalog is stacked with samples from the best artists and producers out there. Yours to flip, chop, and turn into your next banger.” |
| Assurance | Brief ownership or flexibility statement followed by its practical consequence. | 2–5 word heading | “Yours forever”<br>“Cancel anytime” |
| Human trust | Balanced repeated clauses with explicit responsibility. | 4–8 words | “Artist made. Artist paid.” |
| Action | Direct verb plus object or clear access condition. | 2–6 words | “Explore sounds”<br>“Download free” |
| Closing invitation | Ask about readiness or name the next creative act. | 4–10 words | “Ready to make something?” |
| FAQ | Ask the real practical question in the visitor's words. | 4–14 words | “Can I cancel anytime?” |

**Words and phrasing to use:** make; play; create; your next; right in your; yours; free; keep; flow; start; download

**Avoid:** synergize; revolutionary ecosystem; unparalleled solutions; unlock limitless potential; enterprise transformation

**Rules:**

- Pair an emotional promise with a concrete task or ownership explanation.
- Use authentic domain verbs in place of generic productivity jargon.
- Keep buttons task-specific; place reassurance near offers rather than hiding conditions in decorative badges.
- Use scale numbers only when they prove a real benefit; explain what the number counts.
- Let technical support be explicit about compatibility, cancellation and what remains accessible.

## Do's and Don'ts

### Do

- Use a 48px extended grotesk promise against a full-width human scene.
- Keep the 36px/45px section hierarchy distinct from 16px/24px reading text.
- Use 32px gutters between major columns and 80px dark intervals between core chapters.
- Make default blue actions rounded at 64px, with 32px horizontal padding.
- Stage actual outputs alongside human stories; use 50px circular preview controls.
- Include a bright banner with an oversized 180px corner against the charcoal canvas.
- Keep footer navigation small at 12px with separate 20px bold category titles.
- Use faint #303236 rules for FAQs rather than solid filled accordion cards.

### Don't

- Do not use a narrow display substitute; it loses the extended headline silhouette.
- Do not make all buttons 8px rounded rectangles; that shape belongs to secondary media controls and chips.
- Do not wash the entire canvas in blue or purple; strong fills are discrete product chapters and conversion bands.
- Do not set body paragraphs in the extended display face; Inter at 16px/24px carries the explanation.
- Do not apply heavy drop shadows to every marketing card; most surfaces are flat and differentiated by fill or media.
- Do not replace pale-blue selected category chips with the blue primary-action fill; the two communicate different roles.
- Do not turn the open pricing columns into white elevated cards.
- Do not use the 40px ultralight colored quotation style for ordinary body text or core headings.

## Motion and responsive

### Motion

**Observed:**

- Primary controls declare 0.1s ease-out transitions for background, border, color, shadow and fill; utility links declare color 0.2s.
- White navigation actions declare scale(1.03) on hover and focus-visible.
- Carousel indicators declare width and background transitions of 0.2s; preview and product rails support horizontal progression.
- Pricing outcomes shift vertically and fade; a declared outcome opacity transition is 0.6s cubic-bezier(.16, 1, .3, 1). Software proof rails declare continuous linear marquee movement.

**Transfer:**

- Use motion to reveal real media and switch artifacts, with pill indicators reflecting the current chapter.
- Keep controls immediately recognizable while the media changes; do not make the promise depend on a long animation.

**Unknown:**

- Exact video playback cadence, scroll-trigger timing and marquee durations are not established.

### Responsive

**Observed:**

- A 440px width breakpoint is declared.
- The promise, editorial title and closing line use the supplied clamp formulas rather than a single fixed desktop size.

**Transfer:**

- On narrow layouts, keep human media full bleed and move annotation content into a compact vertical stack.
- Stack paired chapters and editorial portrait/output halves without shrinking artifact controls into illegibility.
- Preserve horizontal rails for cover art and bright product panels; reduce the number visible rather than compressing all cards.

**Unknown:**

- Mobile navigation, exact small-screen spacing, artwork positioning and breakpoint behavior beyond the declared width are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
