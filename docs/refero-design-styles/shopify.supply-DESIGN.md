# Shopify Supply — studio goods, electric edges

## Overview

A tactile, people-first retail style with the attitude of a small creative label and the clarity of a useful store. Warm cream and sand photography give way to deep black galleries, with acid lime actions and a narrow rainbow interruption. Regular grotesk text, compact mono labels and occasional extra-wide bold lettering keep the interface direct while portraits, still lifes and floating objects provide the personality. It suits product launches and community-minded brands that can balance spare copy with substantial imagery.

### Essentials

- The opening is a photograph, not a typographic billboard: a full-width 558px studio image carries the visual promise, with 18px/28px support at bottom left and a 148×52px lime action at bottom right, inside 90px side margins.
- Headlines speak normally while artwork shouts: section headings use Inter at 36px/42px, weight 450, -0.005em tracking; the centered manifesto uses 48px/1.1, weight 400, -0.02em with italic phrase changes against enormous pale condensed lettering.
- Actions are cut rectangles, not soft badges: primary buttons have 12px 32px padding and square corners; only carousel controls become 56px circles with 2px gray outlines.
- Color lives in the goods and a few sharp interruptions: cream #f2f0e2 and black #000000 carry the large bands, lime #d0f224 occupies small actions, and the mint-to-blue-to-lilac gradient is concentrated in a 68px ticker rather than washing the page.
- Products alternate between human context and weightless display: 330×550px portrait cards carry 14px white attribution captions, while isolated objects float on black with clipped neighbors and subtle dot trails. Without original photography, use carefully lit still lifes and clean object cutouts, not generic UI cards.
- A loud community ribbon and a pale word wall are signature devices: repeat short uppercase phrases in 32px extra-wide bold type separated by four-point stars on the gradient ribbon; place oversized low-contrast condensed lettering behind a centered statement elsewhere. New wording and simple SVG lettering preserve both devices without bespoke artwork.
- The ending behaves like a graphic grid: an email strip leads into the ticker, then black brand and social panels are divided by 1px #999999 rules, with 30px white social glyphs and a final compact utility row.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid lime | `#d0f224` | `--color-lime` | action | Small primary conversion rectangles. |
| Ribbon mint | `#2bff8c` | `--color-ribbon-mint` | background | Left stop of the narrow signature ribbon. |
| Ribbon blue | `#587ae9` | `--color-ribbon-blue` | background | Middle stop of the narrow signature ribbon. |
| Orchid | `#da9dff` | `--color-orchid` | text, accent | Social invitation accent and editorial category glyphs. |
| Ribbon lilac | `#e9abff` | `--color-ribbon-lilac` | background | Right stop of the narrow signature ribbon. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Studio sand | `#cab28c` | `--color-sand` | background | Backing for the full-width people photograph; match photographic seamless-paper tones. |
| Black | `#000000` | `--color-ink` | text, background, border | Primary dark canvas, light-section text and strong outlines. |
| Dark separator | `#3d3f40` | `--color-dark-rule` | border | Subtle separation between black sections and under the dark navigation. |
| Middle gray | `#999999` | `--color-rule` | border | Footer panel grid and email input outline. |
| Control gray | `#ababab` | `--color-control-edge` | border, text | Circular carousel control outlines and arrow glyphs. |
| Cream white | `#eeece2` | `--color-nav-text` | text | Navigation text against black. |
| Warm cream | `#f2f0e2` | `--color-cream` | background | Light product browsing and manifesto bands. |
| Utility white | `#f4f4f4` | `--color-utility-text` | text, link | Footer utility links. |
| White | `#ffffff` | `--color-white` | text, background, action | Text on black and white signup actions; also the editorial page canvas. |

## Typography

- **Inter-Variable** — All everyday headings, paragraphs, commerce labels and actions. Matter-of-fact neo-grotesk with regular display settings and subtle medium-weight interface text. If unavailable, use **Inter**. Font stack: "Inter-Variable", "Inter", ui-sans-serif, system-ui, sans-serif.
- **Fraktion** — Uppercase browsing and collection eyebrows. Compact utilitarian monospace, like an inventory marking. If unavailable, use **IBM Plex Mono**. Use weight 400 and preserve the compact 16px labels. Font stack: "Fraktion", "IBM Plex Mono", "Courier New", system-ui, monospace.
- **Grtsk-Bold-Tera** — Extra-wide bold ticker lettering and the scoped editorial introduction. Broad, flat, heavy grotesk with a deliberately wide stance. If unavailable, use **Archivo Black**. Widen modestly to match the broad lettering; keep its heavy cut. Font stack: "Grtsk-Bold-Tera", "Archivo Black", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| manifesto | Inter-Variable | 400 | 48px | 1.1 | -0.02em | Centered editorial statement above the pale word wall. |
| manifesto-emphasis | Inter-Variable | 400 italic | 48px | 1.1 | -0.02em | Short turning-point phrases within the manifesto. |
| photo-heading | Inter-Variable | 450 | 40px | 1.25 | -0.005em | People-led full-width feature heading. |
| heading | Inter-Variable | 450 | 36px | 42px | -0.005em | Default section and newsletter headings. |
| ticker | Grtsk-Bold-Tera | 800 | 32px | 1 | normal | Repeated uppercase phrases on the gradient ribbon. |
| lead | Inter-Variable | 450 | 22px | 26px | normal | Square-tile labels, newsletter supporting copy and social invitation lines. |
| signup-action | Inter-Variable | 500 | 20px | 1.4 | normal | Inset white newsletter submit action. |
| hero-support | Inter-Variable | 400 | 18px | 28px | normal | The opening's only live copy; two short lines rather than a separate oversized headline. |
| card-title-action | Inter-Variable | 500 | 18px | 28px | normal | Portrait-card titles and lime primary actions. |
| navigation | Inter-Variable | 450 | 18px | 24px | normal | Navigation links and centered featured-object name. |
| eyebrow | Fraktion | 400 | 16px | 1 | normal, uppercase | Dark-gallery category labels, 12px above their heading. |
| body | Inter-Variable | 400 | 16px | 1.5 | normal | Body paragraphs, prices and small footer text; underlines only on inline links. |
| photo-attribution | Inter-Variable | 500 | 14px | 20px | normal | White text pinned inside the lower edge of portrait imagery. |
| caption | Inter-Variable | 400 | 14px | 20px | normal | Small supporting credit beneath the full-width people feature copy. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial and company introductions | editorial-display | Grtsk-Bold-Tera | 800 | 40px | 1.2 | -0.005em | Broad bold statement in a narrow left-aligned block. |
| editorial lists | story-title | Inter-Variable | 400 | 24px | 32px | -0.01em | Article title beside a landscape thumbnail. |
| editorial lists | read-action | Inter-Variable | 500 | 18px | 1.5 | normal | Outlined read action below article metadata. |
| editorial lists | story-category | Inter-Variable | 420 | 14px | 18px | normal | Small category label preceded by a colored glyph. |

**Notes:**

- Keep everyday headings lighter than the extra-wide ticker. The bold display cut is a separate voice, not the default heading font.
- Inter tracking is nearly neutral at 36–40px; only the 48px manifesto tightens to -0.02em. Its italics change emphasis without changing size or family.
- The opening has no separate live display headline. The physical lettering on the photographed garment carries that visual role; do not turn its script into a new interface font.
- The pale condensed word wall is decorative artwork, vertically stretched to fill its band; it is not another body or heading font.

## Layout

**Density:** Airy imagery with compact commerce details: substantial picture fields and 64px section padding contrast with tightly paired titles and prices.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Portrait product name to price. |
| 8px | Small label and title separation, social prompt to accent line. |
| 12px | Gallery eyebrow to heading; portrait caption inset. |
| 16px | Square tile gutters and tile image to label. |
| 24px | Portrait image to product information. |
| 32px | Heading group to media; portrait carousel controls below the cards. |
| 40px | Newsletter top and bottom padding; navigation link spacing. |
| 48px | Portrait carousel gaps and hero copy bottom inset; editorial paragraph spacing. |
| 64px | Core product-gallery vertical padding. |
| 80px | People-feature text bottom inset and editorial read-action separation. |
| 90px | Desktop outer content inset. |
| 144px | Editorial introduction to story section separation. |

### Containers and grids

- **desktop wrapper**: max width 2560px · side padding 90px. At 1440px the shared inner content spans 1260px. Media, background bands and the ribbon extend edge to edge; the footer social half reaches the outer edge.
- **portrait rail**: 4 columns · gap 48px. 330px-wide portrait cards with 550px images; the fourth card runs beyond the right viewport to advertise horizontal browsing.
- **square collection grid**: 4 columns · gap 16px. Four 303px square images across the 1260px wrapper, with labels outside the pictures.
- **manifesto measure**: max width 736px · side padding 24px. Centered statement set in roughly three lines over the full-width pale word wall.
- **editorial rows** (only for editorial lists): 2 columns · gap 126px. Two 567px-wide columns, each 45% of the 1260px wrapper, separated by 10% of its width. Image at left, vertically centered story details at right.
- **editorial introduction** (only for editorial and company introductions): max width 845px. Left-aligned paragraphs; bold display above is narrower at 599px. Preserve substantial white space on the right.

## Corner radius

| Element | Radius |
| --- | --- |
| rectangular content | 0px |
| carousel controls | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| carousel control | `0px 0px 8px 0px rgba(0,0,0,0.1)` | Only the small translucent circular arrows, not cards or buttons. |

### Surfaces

#### Black stage · level 0

**Use:** Dark navigation, object gallery and footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat black rather than a textured or blue-tinted dark mode. Adjacent galleries are separated by dark rules.

**Transfer:** Use as an image stage and a strong closing field.

#### Cream browsing band · level 0

**Use:** Portrait browsing rail and centered statement.

**CSS:** `background: #f2f0e2; color: #000000`

**Observed:** Warm, low-saturation flat ground; pictures and live text remain unboxed.

**Transfer:** Let the warm ground connect real-world photography with clean black text.

#### Sand studio · level 0

**Use:** Full-width people feature.

**CSS:** `background: #cab28c; color: #000000`

**Observed:** The image's warm seamless paper fills the feature; the backing supports the photograph, not a separate colored card.

**Transfer:** Light subjects against a warm studio sweep with an open area for copy.

#### Photo legibility scrim · level 1

**Use:** Lower edge of hero and portrait images.

**CSS:** `background: linear-gradient(rgba(0,0,0,0) 0%, rgba(0,0,0,0.6) 100%)`

**Observed:** The hero scrim is deeper than the 110px-tall portrait-caption scrims; it fades away rather than outlining a text box.

**Transfer:** Reserve the darkening for the picture edge holding white text.

#### Electric ribbon · level 0

**Use:** Signature horizontal slogan ticker.

**CSS:** `background: linear-gradient(to right in oklab, #2bff8c 0%, #587ae9 50%, #e9abff 100%); color: #000000; overflow: hidden`

**Observed:** A 68px band, not a page-wide atmospheric backdrop.

**Transfer:** Keep a single hard-edged strip with black lettering and star separators.

#### White editorial canvas · level 0

**Only for:** editorial and company pages

**Use:** Long-form introduction and article list.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** No card fills or shadows around the repeated story rows; white navigation has a black bottom rule.

**Transfer:** Use the lighter variant for reading-oriented pages while retaining the shared black ending.

## Components

### Navigation bar

**Use:** Persistent primary navigation.

**CSS:** `background: #000000; color: #eeece2; height: 70px; border-bottom: 1px solid #3d3f40; position: sticky; top: 0px; z-index: 60`

**Text style:** `navigation` — Inter-Variable 450 · 18px/24px

**Observed:** Two links sit left, a compact wordmark is centered independently, and utility links sit right. There is a 24px repeated-message strip above it at the opening. The editorial variant is white with black text and a black bottom rule.

**Transfer:** Use an original wordmark and equally terse navigation; preserve the central anchor and balanced side groups.

### Primary button

**Use:** Main conversion on photographic features.

**CSS:** `background: #d0f224; color: #000000; padding: 12px 32px; border-radius: 0px; height: 52px`

**Text style:** `card-title-action` — Inter-Variable 500 · 18px/28px

**Observed:** A plain lime rectangle; no icon and no shadow. It stands apart from the support text rather than attaching as a text-link arrow.

### Portrait product card

**Use:** Human-context product browsing.

**CSS:** `width: 330px; color: #000000; border-radius: 0px`

**Text style:** `card-title-action` — Inter-Variable 500 · 18px/28px

**Observed:** A 3:5 image with a Photo legibility scrim and Photo attribution at its lower edge; live product title follows after 24px and price after 4px. The whole image-and-details unit links as one item; no raised panel or enclosing outline.

**Transfer:** Show a person using the product or a tactile still life, then keep the item name and factual detail outside the image.

### Photo attribution

**Use:** Credit a real user or collaborator within a portrait card.

**CSS:** `color: #ffffff; padding-left: 12px; padding-right: 12px; margin-bottom: 12px`

**Text style:** `photo-attribution` — Inter-Variable 500 · 14px/20px

**Observed:** Single-line or short white credit aligned to the lower left over the scrim, not a floating chip.

**Transfer:** Credit the person, place or maker behind the image.

### Collection tile

**Use:** Compact visual category navigation on black.

**CSS:** `width: 303px; color: #ffffff; border-radius: 0px`

**Text style:** `lead` — Inter-Variable 450 · 22px/26px

**Observed:** Square edge-to-edge image followed by a left-aligned label after 16px. Four tiles share one row with 16px gutters. Different photographic backdrops supply the color; the wrapper stays black.

**Transfer:** Use distinct close-ups and still lifes for each category, not four identical icons.

### Carousel arrow

**Use:** Navigate the isolated-object stage.

**CSS:** `width: 56px; height: 56px; border-radius: 50%; border: 2px solid #ababab; background: rgba(255,255,255,0.1); color: #ababab; backdrop-filter: blur(4px); box-shadow: 0px 0px 8px 0px rgba(0,0,0,0.1)`

**Observed:** Thin directional arrows centered in circles; two controls form a centered pair with a 32px gap beneath the current object label.

### Email field

**Use:** Newsletter conversion in the closing strip.

**CSS:** `width: 512px; height: 66px; background: #000000; color: #ffffff; border: 1px solid #999999; border-radius: 0px; padding: 20px 20px 20px 24px`

**Text style:** `body` — Inter-Variable 400 · 16px/1.5

**Observed:** The white Signup button sits inset into the right end of this outlined field. Heading and supporting sentence occupy the left half of the strip.

### Signup button

**Use:** Submit the email form.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid transparent; border-radius: 0px; height: 58px; padding: 16px 48px`

**Text style:** `signup-action` — Inter-Variable 500 · 20px/1.4

**Observed:** Inset within the email outline rather than placed as a disconnected second block.

### Slogan ticker

**Use:** Signature graphic punctuation at the shared ending.

**CSS:** `height: 68px; padding: 16px 0px; overflow: hidden; color: #000000`

**Text style:** `ticker` — Grtsk-Bold-Tera 800 · 32px/1

**Observed:** Alternating uppercase phrases repeat beyond both viewport edges, separated by black four-point stars. Phrase spans have 32px side margins. A 40px pause/play control is pinned at the right over the Electric ribbon.

**Transfer:** Write two short complementary phrases about the new audience's shared identity; keep the wide bold type and star rhythm.

### Social grid

**Use:** Footer social invitation and links.

**CSS:** `display: flex; border-top: 1px solid #999999; color: #ffffff`

**Observed:** Four equal social cells, about 169×155px each, have vertical gray separators and centered 30px white filled social marks. Above them is a two-line invitation: white first line, orchid second line. A brand-description panel fills the left half.

**Transfer:** Choose relevant channels and keep each cell icon-led; retain the ruled construction.

### Read button

**Only for:** editorial lists

**Use:** Repeated secondary content action.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #000000; border-radius: 0px; padding: 12px 32px; height: 53px; margin-top: 80px`

**Text style:** `read-action` — Inter-Variable 500 · 18px/1.5

**Observed:** A standalone outlined rectangle beneath the story metadata, with much more separation than a commerce card's price.

## Imagery and graphics

### Warm campaign photography

**Use:** Opening, portrait rail and people-led feature.

**Observed:** A navy work jacket fills the opening so closely that the head and body are cropped; cream embroidery and fabric texture carry the message. Portrait cards show actual wearers and one playful backpack-and-balloon still life. A six-person studio portrait leaves sand-colored space at left for copy. Light is soft and dimensional, colors warm and grounded, and the imagery is much larger than its text.

**Transfer:** Photograph the new product in use against warm seamless paper. Crop close enough to show touch, seams or materials, and reserve a readable edge for the short live copy. A well-lit tabletop still life is the minimum alternative when people are unavailable.

### Pale word wall

**Use:** Signature backdrop behind the centered manifesto.

**Observed:** Extremely tall condensed uppercase lettering extends nearly the full height of the 405px cream band and is clipped at the horizontal edges. Its tonal difference is faint, allowing the regular black sentence to dominate.

**Transfer:** Use one original audience or benefit word, not a logo; keep it almost the same tone as the backing so it reads as a wall graphic.

**Build:** Create an SVG spanning the full band with a single uppercase sans-serif word. Use textLength to distribute it across slightly more than the viewport width, independently stretch the glyphs vertically to fill roughly 400px, and clip overflow. Fill the lettering black at about 3% opacity over #f2f0e2. Put the centered 736px live-text layer above it.

### Colorful square still lifes

**Use:** Category tiles within the black gallery.

**Observed:** Four square images vary their staging: purple geometric packaging, a yellow bag against a night-time taxi, a black hat on gray, and a macro crop of green keyboard keys. These are full photographs rather than tinted interface panels.

**Transfer:** Vary scale and setting across categories while retaining deliberate studio or editorial lighting. Let the image own its color and keep the surrounding page black.

### Floating object procession

**Use:** Featured-item carousel on the black stage.

**Observed:** A reflective silver push button is centered, with a graphic magnet and translucent green keycap at either side. Object cutouts sit directly on black, side items tilt and clip past the page edges, and small dark dots bridge the gaps. The central label and price sit well below the object, with arrows lower still.

**Transfer:** Use clean transparent cutouts or simple rendered objects with believable material highlights. For software, isolate a physical tool or a single crisp product artifact rather than introducing a full dashboard frame.

**Build:** Place three transparent object images in an overflow-clipped black stage; reserve approximately 460–472px square image areas at desktop. Keep the middle object upright, rotate side objects in opposing directions, and offset them toward the viewport edges. Insert three 12px low-opacity white dots in each gap along a shallow rising or falling diagonal. Keep the copy layer below the object images, not over them.

### Gradient star ribbon

**Use:** Signature graphic field beneath the newsletter.

**Observed:** A crisp mint-to-blue-to-lilac strip combines black wide lettering and repeated four-point stars, with no blur, noise or glow.

**Transfer:** Carry the energetic color into a narrow horizontal punctuation mark, not a generalized gradient theme.

**Build:** Apply the Electric ribbon gradient to a 68px-high overflow-hidden band. Build each black star as an SVG concave four-point path in a roughly 35×36px box. Alternate stars with the Ticker type recipe and repeat the sequence beyond both edges; overlay the 40px animation control at the right.

### Editorial landscape thumbnails

**Only for:** editorial lists

**Use:** Images accompanying repeated article rows.

**Observed:** 567×366px landscape images range from a torn-paper blue-and-cream interview cover to real working scenes and product illustrations. Images remain square-cornered and unboxed; their own embedded text is part of the artwork rather than the page hierarchy.

**Transfer:** Use subject-specific landscape photography or commissioned editorial graphics with a consistent aspect ratio. Keep readable live titles beside them even when artwork contains lettering.

### Back-to-top eye sticker

**Only for:** long product-browsing pages

**Use:** Playful return control near the lower object gallery.

**Observed:** A white circular seal sits at the lower right, containing two black cartoon eyes and repeated curved back-to-top wording. It feels like a sticker rather than an interface badge.

**Transfer:** Use a small original character or simple eye motif paired with functional circular wording.

**Build:** Create a white circle approximately 150px across, add two narrow black-outlined white ellipses with black pupils, then wrap short uppercase return wording around an inset circular SVG textPath. Keep the circle isolated on black and make the entire seal the return link.

### Icons

**Observed:** Interface marks are sparse: small chevrons, thin directional arrows, filled white social glyphs at 30px, and black four-point stars around 35×36px on the ticker. Editorial category symbols are approximately 14×15px and may use orchid.

**Transfer:** Choose a compact set with matching optical weight. Prefer plain arrows for navigation and filled recognizable social marks; keep decorative symbols confined to the ribbon and playful return seal.

## Section recipes

How recurring sections are built.

### First screen: Photographic opening

**Observed:** A 24px black announcement strip and 70px dark Navigation bar precede a full-width 558px Warm campaign photography field. The main object is a closely cropped jacket back, much larger than the live copy, with physical embroidered script as the image's headline-like feature; there is no additional live display heading. Back to front: warm studio photograph, lower Photo legibility scrim, then a two-line 18px support sentence aligned left and Primary button aligned right inside 90px side margins and 48px above the image edge. Within the first 900px, the whole opening image, sentence and action are visible, followed by the cream browsing eyebrow and the tops of portrait cards. Complete card details are below the fold.

**Transfer:** Lead with a similarly tactile, tightly framed product-in-use image and a short statement plus one action. If no campaign image exists, stage a close tabletop photograph or detailed object render on warm paper with physical lettering or a strong material detail supplying the visual hook. Editorial pages instead open on white with a small 22px title, narrow 40px extra-wide statement, two 22px paragraphs and a down arrow.

**Avoid:** Do not overlay a huge centered SaaS headline, add multiple competing actions, or shrink the product into a small hero card.

**Text style:** `hero-support` — Inter-Variable 400 · 18px/28px

### Portrait browsing rail

**Observed:** Cream browsing band with 64px vertical padding. A 16px uppercase mono label precedes the rail by 32px. Portrait product cards form a horizontally overflowing row, beginning at the common wrapper edge, with 48px gaps. Small arrows and a thin progress track follow after 32px.

**Transfer:** Use this for a concrete set of offers or examples that benefit from human context and factual captions; allow a partial next item rather than squeezing every card into view.

**Text style:** `card-title-action` — Inter-Variable 500 · 18px/28px

### People-led feature

**Observed:** A 691px full-bleed Sand studio image puts people on the right and live content in the lower left. The text block takes about 42% of the inner width and ends 80px above the band edge: Photo heading, body support and small Caption separated by 16px, then Primary button after 32px.

**Transfer:** Pair genuine people or a collaborative scene with one grounded benefit and a factual credit. Preserve negative space inside the photograph instead of covering subjects with text.

**Text style:** `photo-heading` — Inter-Variable 450 · 40px/1.25 · tracking -0.005em

### Word-wall statement

**Observed:** A 405px Cream browsing band holds Pale word wall artwork from edge to edge. A centered 48px Manifesto is limited to 736px and roughly three lines. Two short phrases switch to Manifesto emphasis without adding another color.

**Transfer:** Write a single purpose statement with a small rhetorical turn, retaining the pale oversized lettering as its backdrop.

**Text style:** `manifesto` — Inter-Variable 400 · 48px/1.1 · tracking -0.02em

### Dark category gallery

**Observed:** Black stage with a 1px dark top rule and 64px vertical padding. Eyebrow sits 12px above Heading; the Collection tile row follows after 32px. Four square pictures create a concentrated color field while the labels remain white.

**Transfer:** Use the gallery as a change of visual register and a concise navigation menu for capabilities or product families.

**Text style:** `heading` — Inter-Variable 450 · 36px/42px · tracking -0.005em

### Object theater

**Observed:** A tall black band continues the gallery treatment. The heading pair stays left; Floating object procession fills the broad center, leaving substantial black space above and below. Current item name and price are centered under the main object, followed by Carousel arrows. The Back-to-top eye sticker occupies the lower right.

**Transfer:** Give a small set of distinctive offers room to be looked at rather than packing them into more tiles.

**Text style:** `heading` — Inter-Variable 450 · 36px/42px · tracking -0.005em

### Ruled community ending

**Observed:** A shared 644px black ending starts with a 176px newsletter strip: Heading and Lead at left, Email field and Signup button at right, with 40px top and bottom padding. The 68px Slogan ticker follows. Below it a 305px-high ruled grid combines a brand mark and 16px description on the left, a two-line 22px social invitation and Social grid on the right. The final 95px utility strip has compact links on the left and a small platform credit on the right. This same ending follows both commerce and editorial content.

**Transfer:** Use a genuine subscription or contact invitation, a short identity ribbon, a brand-purpose panel and real social channels. Keep the graphic divisions and compact utility finish even when the preceding page is white.

**Text style:** `heading` — Inter-Variable 450 · 36px/42px · tracking -0.005em

### Editorial introduction and rows

**Only for:** editorial and company pages

**Observed:** White editorial canvas with black Navigation bar variant. The introduction starts 72px below navigation, uses a 22px page label and an extra-wide bold 40px statement within 599px, then two 22px paragraphs within 845px separated by 48px. A large downward arrow ends the introduction. After a 144px breathing interval, a 22px section label and 36px Heading introduce repeated two-column story rows. Each row has 32px vertical padding, a landscape thumbnail on the left and category, 24px title, date/byline and Read button on the right.

**Transfer:** Use this variant for reading-oriented pages, with a succinct mission introduction followed by a consistent list of useful resources. Keep the same shared ending rather than inventing a separate editorial footer.

**Text style:** `editorial-display` — Grtsk-Bold-Tera 800 · 40px/1.2 · tracking -0.005em

## Page flow

**Storyline:** Tangible invitation → concrete things to explore → human or editorial context → shared identity → direct participation and a graphic utility ending.

### Image-led product discovery and purchase

1. **Invitation** — A large tactile campaign photograph with two lines of copy and one lime action.
2. **Product demonstration** — Warm portrait browsing rail with real-user credits and factual product details.
3. **Human proof** — Full-width people photograph and a concise contextual story.
4. **Identity** — Centered manifesto over faint monumental lettering.
5. **Discovery** — Black category gallery followed by a floating-object showcase.
6. **Closing call** — Email invitation, gradient identity ticker and ruled social/utility footer.

**Transfer:** Move between contextual photography and isolated objects so the product feels both lived-in and collectible. Retain the identity devices without treating this exact sequence as a fixed template.

### Explain a point of view and help readers discover useful stories

1. **Purpose** — White text-first introduction with a narrow heavy statement and two supporting paragraphs.
2. **Editorial proof** — A section heading followed by seven landscape-image article rows, category labels, bylines and outlined actions.
3. **Closing call** — The same black newsletter, ticker and ruled footer used by the product experience.

**Transfer:** Use the white variant for a longer explanation or resource library; replace the repeated stories with relevant educational material and preserve the high-contrast ending.

## Writing

Warm, commercially direct and lightly cheeky. It celebrates the reader's agency through concrete things, real people and small wordplay rather than grand technical claims.

**Do not copy:** Do not reuse Shopify names, logos, branded merchandise, proprietary artwork, audience claims, named people, quoted endorsements, shipping promises, discount percentages or platform claims. Source examples illustrate tone only.

- **Addressing the reader:** Speak to the reader as you; use we for the team and our for shared products and community. Credit collaborators by name when factual.
- **Rhythm:** Short action labels and conversational section headings sit beside one- or two-sentence support. Longer explanatory paragraphs belong to the editorial variant; contractions and an occasional em dash keep them spoken rather than institutional.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening support | Announce what is available, then turn a familiar phrase toward the reader's independence. | Two short sentences | “The Entrepreneur Collection is open for business. Dress like you answer to no one—except yourself.” |
| Section heading | Plain invitation or compact parallel phrase, without a terminal period. | 4–7 words | “Real people, real businesses”<br>“Stock up on your Supply” |
| Manifesto | One audience-focused sentence with an italicized shift from possibility to action. | One sentence | “A new daily uniform for the builders, doers and dreamers turning what if into what’s next.” |
| Action | Literal verb plus simple time or object; no inflated benefit claim. | 2 words | “Shop now”<br>“Read now”<br>“Sign up” |
| Photo caption | Name the relationship between a person and what is pictured. | One short credit line | “Worn by Leandro from Famiglia Baldassarre” |
| Closing invitation | A friendly question followed by a concrete reason to participate. | Question plus one sentence | “Want more Supply?”<br>“Join our community and save 15% off your next order.” |

**Words and phrasing to use:** real people; builders, doers and dreamers; stock up; what if / what's next; open for business; we'd love to

**Avoid:** revolutionary ecosystem; unlock unparalleled potential; enterprise-grade synergy; hustle harder; limited-time urgency without a real deadline

**Rules:**

- Let concrete nouns and actual use cases carry the promise.
- Use playful language once per major block, not in every label.
- Keep action copy literal and short even when surrounding text is witty.
- Credits and metadata should provide real context, not decorative filler.
- Use paired phrases for rhythmic identity statements, and questions for friendly closing invitations.

## Do's and Don'ts

### Do

- Keep default section headings at 36px/42px and weight 450; reserve the heavy wide face for identity moments.
- Make hero copy subordinate to the material detail in the photograph and keep its action square at 52px high.
- Align section labels and gallery starts to the same 90px desktop inset.
- Use 3:5 portrait images for the warm browsing rail and 1:1 images for the dark category row.
- Keep the gradient concentrated in a 68px strip with black lettering and black stars.
- Use 1px #999999 rules to construct the footer rather than separate rounded cards.
- Preserve 24px between portrait imagery and product details, then only 4px between title and price.
- Keep italic emphasis in the 48px statement at the same scale as its surrounding sentence.

### Don't

- Do not use the extra-wide bold face for every navigation item, price or paragraph.
- Do not turn category image backdrops into a site-wide purple, yellow or green panel system.
- Do not give the lime primary action the circular shape used by the 56px carousel arrows.
- Do not add drop shadows to portrait or collection cards; their separation comes from gutters and canvas contrast.
- Do not use an all-white ending on the editorial variant; its shared footer remains black.
- Do not round landscape thumbnails, portrait images or newsletter fields.
- Do not use orchid for long paragraphs; it is a small social/category accent.
- Do not make the gradient a soft radial glow or glass-card background; the ribbon is sharp-edged and horizontal.

## Motion and responsive

### Motion

**Observed:**

- The slogan track declares a 30s linear infinite marquee and includes a pause/play control.
- A category image declares a 300ms transform transition; an exact hover scale is not established.
- Carousel controls, portrait rail progress and a return-to-top control are present.

**Transfer:**

- Keep the ticker as a continuous repeated strip with a working pause control; the identity must remain readable when paused.
- Use horizontal progression to expose adjacent products rather than replacing the object stage with a stacked list at desktop.

**Unknown:**

- Exact carousel durations, autoplay behavior and easing are not established.
- No complete hover or focus-visible state recipes are established for the actions.

### Responsive

**Observed:**

- Desktop uses four-item rails, two-column editorial rows and a split newsletter/footer.
- Declared layout classes switch editorial rows and newsletter content between column and row arrangements; small-screen rail items use a viewport-relative width and continue to overflow horizontally.

**Transfer:**

- On narrow screens, keep portrait and category content as swipeable rails with a partial next item; do not compress four portraits into miniature columns.
- Stack editorial image above text and newsletter copy above the form. Keep the ribbon full bleed and preserve its pause control.
- Reframe people photography to retain both the subject and a clear copy zone; let the hero sentence and action stack rather than overlap the subject.

**Unknown:**

- Exact viewport breakpoints, mobile type sizes, navigation controls and mobile image assets are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
