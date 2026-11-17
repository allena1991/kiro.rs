# Replay — jewelbox desktop delight

## Overview

A bright, tactile software showcase with the charm of a beautifully made desktop utility. System sans typography and abundant white space let jewel-colored app icons, floating interface windows and vivid desktop scenes do the emotional work. The default is light with black text and pale grey cards; a darker, green-accented variant gives technical mobile products a more cinematic stage. The density moves from expansive product theatre to compact, useful feature collections.

### Essentials

- Product first, promise second: a centered 900px × 560px desktop scene with 24px corners leads the light landing page, with a 208px app icon overlapping its lower edge and a 96px product name beneath.
- The name behaves like a polished object: system sans at 96px/1, weight 600, -0.025em tracking, black-to-#444444 clipped gradient; release numerals can punctuate it at weight 900.
- Headings are emphatic but unornamented: 48px/1 weight 700 with normal tracking, paired with 24px/32px support and miniature 12.8px/1.5 uppercase chapter labels at 0.05em tracking.
- Conversion controls are little capsules, not broad banners: 56px high, 9999px radius, 24px horizontal padding, 18px/28px semibold labels; black store action sits beside a pale direct-purchase action with an inset price badge.
- Color belongs to the product theatre: white and #f9fafb dominate the default page, while blue-to-cyan desktop panels, mint waves and jewel icons carry saturated color. Small chapter labels change hue; ordinary paragraphs stay black.
- Software feels physically present: use layered floating windows, soft cast shadows, glossy rounded app icons and detailed real interface views against wallpaper-like backdrops. If no finished product media exists, construct one convincing interface fragment and an original shaded app tile rather than substituting generic lifestyle photography.
- The ending stays helpful and human: repeat compact conversion controls, then a question-led support area with 16px-radius resource cards and a fine-rule maker footer; use 40px card gutters and a 64px footer top inset rather than a giant final slogan.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Chapter blue | `#0d9eff` | `--color-chapter-blue` | text | Small chapter labels associated with appearance and themes. |
| Desktop blue | `#0e95ee` | `--color-stage-blue` | background, accent | Lower-left stop of the blue desktop stage. |
| Chapter red | `#dd3107` | `--color-chapter-red` | text | Small integration chapter labels. |
| Desktop cyan | `#27c9f5` | `--color-stage-cyan` | background, accent | Upper-right stop of the blue desktop stage. |
| Chapter purple | `#783af5` | `--color-chapter-purple` | text | Small customization chapter labels. |
| Support green | `#53bc2a` | `--color-support-green` | link, text, action | Support labels and resource links, not default purchase fills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action | Default text and primary action fill. |
| Secondary ink | `#333333` | `--color-secondary` | text, action | Visible 80% black text on white; also the primary-button hover fill. |
| Graphite sheen | `#444444` | `--color-display-end` | text | Lower stop of the default product-name gradient. |
| Grey chapter label | `#777777` | `--color-label-neutral` | text | Neutral chapter eyebrows. |
| Muted copy | `#808080` | `--color-muted` | text | Visible black at 50% opacity on white for compatibility and purchase notes. |
| Inset edge | `#f2f2f2` | `--color-edge` | border | Visible result of a 5% black inset hairline on white; use rgba(0,0,0,0.05) on pale cards. |
| Footer rule | `#f3f4f6` | `--color-rule` | border | Fine footer dividers and pressed secondary actions. |
| Cloud card | `#f9fafb` | `--color-card` | surface, background, action | Feature cards, support cards, selected navigation and secondary actions. |
| White canvas | `#ffffff` | `--color-canvas` | background, text, surface | Default page canvas, primary-button text and lifted control fills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| appearance-focused utility campaigns and portfolio tiles | Sky blue | `#2baffb` | `--color-sky` | accent, text, background | Final stop of the identity gradient. |
| technical mobile product campaigns | Terminal green | `#00ae70` | `--color-technical-green` | link, accent, text | Chapter labels, outlined icons and support actions. |
| appearance-focused utility campaigns and portfolio tiles | Lavender | `#9f7eff` | `--color-lavender` | accent, text, background | Middle stop of the identity gradient. |
| appearance-focused utility campaigns and portfolio tiles | Orchid | `#e98bd4` | `--color-orchid` | accent, text, background | First stop of the pink-purple-blue product identity gradient. |
| technical mobile product campaigns | Forest stage | `#021a10` | `--color-forest` | background | Full-width expanded-device chapter. |
| technical mobile product campaigns | Near-black theatre | `#0d0e10` | `--color-night` | background | Dark product landing canvas. |
| technical mobile product campaigns | Silver display stop | `#cccccc` | `--color-silver` | text | Lower stop of white-to-silver headline gradient. |
| technical mobile product campaigns | Soft grey band | `#f4f4f4` | `--color-band` | background | Broad light interlude behind compatible-tool chips and phone imagery. |

## Typography

- **ui-sans-serif** — All marketing headings, paragraphs, labels and controls. Native system sans with familiar platform proportions; bold headings and readable regular body text, without a separate display or mono marketing face. Font stack: "ui-sans-serif", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji".

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ui-sans-serif | 600 | 96px | 1 | -0.025em | Centered product name beneath the hero scene. |
| heading | ui-sans-serif | 700 | 48px | 1 | normal | Section headings, capability chapter titles and the opening benefit statement. |
| lead | ui-sans-serif | 400 | 24px | 32px | normal | Centered support copy and descriptive text in expansive feature chapters. |
| card-heading | ui-sans-serif | 600 | 24px | 32px | normal | Feature and support card headings. |
| body | ui-sans-serif | 400 | 18px | 28px | normal | Feature-card and resource-card paragraphs. |
| action | ui-sans-serif | 600 | 18px | 28px | normal | Main purchase and download actions. |
| text-action | ui-sans-serif | 500 | 18px | 28px | normal | Resource and guide links. |
| footer | ui-sans-serif | 400 | 16px | 24px | normal | Maker attribution and compact utility descriptions. |
| small | ui-sans-serif | 400 | 14px | 20px | normal | Navigation and compatibility notes. |
| eyebrow | ui-sans-serif | 600 | 12.8px | 1.5 | 0.05em, uppercase | Tiny colored chapter labels above headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| major-version launches | release-heavy | ui-sans-serif | 900 | 96px | 1 | -0.025em | Heavy release numeral attached to the product name. |
| appearance-focused utility campaigns | release-light | ui-sans-serif | 300 | 96px | 1 | -0.025em | Lightweight decimal version appended to the gradient name. |
| technical mobile product campaigns | dark-display | ui-sans-serif | 700 | 96px | 1 | -0.025em | Short emphatic benefit headline below cinematic device imagery. |
| portfolio index pages | tile-display | ui-sans-serif | 600 | 72px | 1 | -0.025em | Lead product tile title. |
| portfolio index pages | tile-heading | ui-sans-serif | 700 | 48px | 1 | -0.025em | Secondary product tile titles. |
| portfolio index pages | studio-intro | ui-sans-serif | 500 | 36px | 40px | normal | Conversational two-line studio introduction. |

**Notes:**

- Display tracking tightens to -0.025em; the 48px chapter headings deliberately retain normal tracking.
- Default product names have a black-to-graphite vertical gradient. The appearance-focused identity uses a horizontal orchid-lavender-sky gradient on both its name and benefit line; the technical variant uses white-to-silver.
- Do not introduce a mono marketing face simply because the product itself contains code. Preserve interface typography within product media separately.

## Layout

**Density:** Airy around hero scenes and chapter introductions, then compact within feature mosaics and resource cards.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-label and tight title-support gaps. |
| 12px | Main button icon gaps. |
| 16px | Stacked card text gaps and paired purchase-action gutter. |
| 24px | Hero text stack gap and button side padding. |
| 28px | Action-to-compatibility-note gap. |
| 32px | Chapter heading stack gaps and container side padding. |
| 36px | Default feature-card vertical padding. |
| 40px | Feature and support grid gutters. |
| 48px | Wide card horizontal padding and header bottom padding. |
| 64px | Header top padding, heading-to-media breathing room and footer top inset. |
| 96px | Default separation between major chapters. |
| 128px | Broad technical-product chapter vertical padding. |

### Containers and grids

- **Main container**: max width 1264px · side padding 32px. Centered outer box giving 1200px usable content at desktop; aligns navigation, grids and footer.
- **Hero stage**: max width 900px. Centered visual stage, narrower than the feature container.
- **Lead copy**: max width 768px. Centered opening description; section introductions can expand to 896px.
- **Feature grid**: 3 columns · gap 40px. Equal feature and resource tiles; larger mosaic tiles span columns and rows rather than forcing uniform heights.
- **Capability split**: 2 columns · gap 40px. Left-aligned explanatory copy beside a tall wallpaper-backed demonstration; media occupies about half the content width.
- **Technical container** (only for technical mobile product campaigns): max width 1024px · side padding 32px. Narrower feature bento and expanded-device presentation inside full-width color bands.
- **Portfolio grid** (only for portfolio index pages): 8 columns · gap 32px. Lead tile spans five columns and full height; two smaller tiles each span three columns and half height. Desktop tile field is 1200px × 540px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Stage and feature cards | 24px |
|  | Resource cards | 16px |
|  | Actions and navigation | 9999px (pill) |
|  | Floating interface windows | 12px |
| technical mobile product campaigns | Theme screens | 32px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Fine inset edge | `inset 0px 0px 0px 1px rgba(0,0,0,0.05)` | Pale cards, selected navigation and media boundaries. |
| Hero lift | `0px 20px 25px -5px rgba(0,0,0,0.05), 0px 8px 10px -6px rgba(0,0,0,0.05)` | Main desktop stage. |
| Floating window | `0px 0px 0px 1px rgba(0,0,0,0.1), 0px 12px 24px -8px rgba(0,0,0,0.4), 0px 8px 24px 0px rgba(0,0,0,0.2), 0px 2px 4px 0px rgba(0,0,0,0.2)` | Isolated interface-window demonstrations, not every marketing card. |

### Surfaces

#### White canvas · level 0

**Use:** Default landing-page ground.

**CSS:** `background: #ffffff; color: #000000`

#### Feature cloud · level 1

**Use:** Bento features and grouped product details.

**CSS:** `background: #f9fafb; border-radius: 24px; box-shadow: inset 0px 0px 0px 1px rgba(0,0,0,0.05)`

**Observed:** Subtle inset boundary, without a conspicuous elevated card shadow; content mixes text with interface fragments.

**Transfer:** Use pale surfaces to group practical details while letting product imagery supply color.

#### Blue desktop stage · level 1

**Use:** Primary light-page hero and panoramic demonstration strips.

**CSS:** `background: linear-gradient(to top right, #0e95ee, #27c9f5); border-radius: 24px; box-shadow: 0px 20px 25px -5px rgba(0,0,0,0.05), 0px 8px 10px -6px rgba(0,0,0,0.05); overflow: hidden`

**Observed:** Cyan sky above layered turquoise wallpaper waves, with desktop metadata and product content.

**Transfer:** Add the layered wave artwork described in Desktop theatre; the gradient alone is not the finished stage.

#### Dark theatre · level 0

**Only for:** technical mobile product campaigns

**Use:** Cinematic mobile-product canvas.

**CSS:** `background: #0d0e10; color: #ffffff`

**Observed:** A white feature bento and pale grey interlude interrupt the dark ground; the footer returns to white.

**Transfer:** Keep technical scenes legible and save saturated green for small emphasis.

#### Forest device band · level 0

**Only for:** technical mobile product campaigns

**Use:** Expanded-device capability chapter.

**CSS:** `background: #021a10; padding: 128px 0px; color: #ffffff`

**Observed:** Centered tablet media with a green edge and a row of translucent green capability cards.

**Transfer:** Use a wide device or workspace scene to demonstrate expanded capability.

#### Appearance gradient · level 1

**Only for:** appearance-focused utility campaigns and portfolio tiles

**Use:** Product identity gradient and compact catalog tile backing.

**CSS:** `background: linear-gradient(to top right, #e98bd4, #9f7eff, #2baffb); border-radius: 16px`

**Observed:** The same three hues run left-to-right through the large product name and benefit line.

**Transfer:** Reserve this identity for a distinct product variant rather than applying rainbow text throughout the default page.

## Components

### Product navigation

**Use:** Compact centered product switcher within a spacious header.

**CSS:** `display: flex; align-items: center; height: 40px; padding: 0px 16px; gap: 6px; border-radius: 9999px; background: #f9fafb; box-shadow: inset 0px 0px 0px 1px rgba(0,0,0,0.05)`

**Text style:** `small` — ui-sans-serif 400 · 14px/20px

**Observed:** Selected product has a pale capsule and tiny app icon; other products are unfilled. Wordmark stays left and utility links plus social icon stay right. The header has 64px top and 48px bottom padding.

**States:** Declared: hover background #f9fafb and text rgba(0,0,0,0.9).

### Primary button

**Use:** Store or principal purchase action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 12px; height: 56px; padding: 0px 24px; border-radius: 9999px; background: #000000; color: #ffffff; border: 1px solid rgba(0,0,0,0.2); box-shadow: 0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Text style:** `action` — ui-sans-serif 600 · 18px/28px

**Observed:** A platform symbol precedes the label. The dark campaign inverts the capsule to white with black text and includes a small black price badge.

**States:** Declared: hover background #333333; active background #000000.

### Direct purchase button

**Use:** Alternative purchase route beside the primary action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 12px; height: 56px; padding: 0px 24px; border-radius: 9999px; background: #f9fafb; color: #000000; border: 1px solid rgba(0,0,0,0.1); box-shadow: 0px 1px 3px rgba(0,0,0,0.05), 0px 1px 2px -1px rgba(0,0,0,0.05)`

**Text style:** `action` — ui-sans-serif 600 · 18px/28px

**Observed:** Black price pill sits to the right inside the pale capsule. Pair with a small muted licensing and platform note below the action row.

**States:** Declared: hover background #ffffff; active background #f3f4f6.

### Resource link

**Use:** Support and documentation destinations inside resource cards.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 8px 16px; border: 1px solid transparent; border-radius: 9999px; color: #53bc2a`

**Text style:** `text-action` — ui-sans-serif 500 · 18px/28px

**Observed:** Trailing 12px arrow, search or export symbol. Link is unfilled at rest. Neutral versions serve integration guides; green changes to the technical accent on dark campaigns.

**States:** Declared: hover background #53bc2a; hover on ancestor border-color #53bc2a and background #ffffff.

### Resource card

**Use:** Helpful late-page support choices.

**CSS:** `background: #f9fafb; border-radius: 16px; box-shadow: inset 0px 0px 0px 1px rgba(0,0,0,0.05)`

**Text style:** `card-heading` — ui-sans-serif 600 · 24px/32px

**Observed:** Centered icon, title, brief body and Resource link in that order. Inner stack uses 36px vertical and 44px horizontal padding with 16px gaps. Default is three cards; technical variant uses two translucent white cards on dark ground.

**Transfer:** Choose resources that remove real purchase or usage friction.

### Feature mosaic card

**Use:** Detailed capability proof inside a mixed-size grid.

**CSS:** `position: relative; background: #f9fafb; border-radius: 24px; overflow: hidden`

**Text style:** `card-heading` — ui-sans-serif 600 · 24px/32px

**Observed:** Large tile combines left-aligned title, body and interface fragments, alongside smaller image-led tiles. A typical large tile has 36px vertical and 48px horizontal inner padding; a fine inset outline overlays the boundary.

**Transfer:** Vary the tile span according to the amount of useful demonstration, not just paragraph length.

### Maker footer

**Use:** Human-scale closing attribution and utilities.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 32px; padding-top: 64px; border-top: 1px solid #f3f4f6`

**Text style:** `footer` — ui-sans-serif 400 · 16px/24px

**Observed:** Overlapping 32px and 36px circular portraits precede two short lines of attribution. Theme control, social icon and wordmark sit at the opposite side. Outer footer adds 80px bottom padding. Portfolio index replaces attribution with a copyright line.

**Transfer:** Use real maker attribution or a succinct ownership statement, keeping the closing scale modest.

### Portfolio product tile

**Only for:** portfolio index pages

**Use:** Whole-tile product destination.

**CSS:** `display: grid; padding: 64px 0px; border-radius: 16px; background: linear-gradient(to top right, #0e95ee, #27c9f5); box-shadow: inset 0px 0px 0px 1px rgba(0,0,0,0.05)`

**Text style:** `tile-display` — ui-sans-serif 600 · 72px/1 · tracking -0.025em

**Observed:** Large app icon and white gradient title sit side by side, with one short promise below. Primary tile uses a 248px icon; secondary tiles use 124px icons and 48px headings. Their colored surfaces identify the products rather than separate call-to-action buttons.

### Flexible price control

**Only for:** pay-what-you-like utility pages

**Use:** Joined editable price and download action.

**CSS:** `display: flex; gap: 0px; height: 56px`

**Text style:** `action` — ui-sans-serif 600 · 18px/28px

**Observed:** 118px white price input with left capsule corners joins a 200px pale download button with right capsule corners and a shared 1px black-at-10% edge. Currency marker and stacked increment/decrement controls live inside the price side; a short payment note follows.

**Transfer:** Use only when the offer genuinely supports an editable amount.

## Imagery and graphics

### Desktop theatre

**Use:** Required signature product scene in the light landing-page visual language.

**Observed:** A vivid blue/cyan rounded desktop panel carries mint rolling wallpaper shapes, a sparse menu bar and a small working product view. An oversized glossy rounded-square app icon overlaps the bottom center. Colorful utility tiles and faint grey symbols float outside the stage, rotated slightly; the surrounding page remains white.

**Transfer:** Compose an original desktop-like workspace around the new product's central task. Minimum acceptable version is one legible interface fragment, one original shaded app tile and a deliberately drawn wallpaper, not a flat empty gradient.

**Build:** Use a 900px × 560px relative stage with 24px clipping and a diagonal #0e95ee-to-#27c9f5 base. Add two SVG paths in the lower 45%: broad undulating turquoise and mint hills, running left-high to right-low, with a softly darker translucent lower layer. Center the functional fragment in the upper-middle. Place a 208px app tile above the bottom edge with a soft cast shadow; add 3–5 smaller rounded-square capability symbols around the outer sides, mixing jewel-colored filled tiles with low-opacity grey glyphs. Shade the app tile with a lighter top edge, darker lower edge and inset symbol well; exact wallpaper stops are not essential.

### Wallpaper-backed interface studies

**Use:** Capability chapters and the closing product gallery.

**Observed:** Crisp light interface windows float over softly blurred blue, cream and silver diagonal wallpaper; detailed controls retain authentic proportions and cast layered shadows. Gallery pairs two wide settings scenes above three smaller expressive product scenes, using 24px outer corners and 40px gutters.

**Transfer:** Use true interface views, enlarge a meaningful settings group and remove unrelated chrome. Keep the backing luminous and abstract so small text remains secondary to the recognizable task.

**Build:** For a substitute backing, layer a pale cream radial glow over a blue field, add a broad diagonal silver-blue ribbon from lower-left to upper-right, and blur the background layer only. Place one or two light windows with 12px corners above it using Floating window shadows; never blur the interface itself.

### Pastel integration illustrations

**Use:** Paired capability or integration proof cards.

**Observed:** Two pale tinted cards pair floating translucent symbol tiles with a stronger colored foreground service icon; copy is centered beneath and colored to harmonize with each tint. Pink/red and pale green are local chapter colors, not full-page themes.

**Transfer:** Represent a real connection or workflow with two or three dimensional symbols over a very light local wash.

**Build:** Stack 2–3 rounded-square tiles offset horizontally, use white at 60–80% opacity and a restrained shadow, and put the key colored symbol in front at a slight angle. Back it with a vertical 5–10% tint gradient and ample empty space.

### Cinematic mobile devices

**Only for:** technical mobile product campaigns

**Use:** Dark opening, device expansion and theme selection.

**Observed:** Two tall perspective phones in contrasting light and dark UI dominate the first screen before the headline. Later, a three-phone group appears over a light grey band, a large tablet workspace over forest green, and six angled theme screens form a near edge-to-edge fan fading into the dark canvas.

**Transfer:** Stage accurate device frames with real product views and a common perspective. Keep device edges softly lit, backgrounds nearly black and the UI readable rather than neon.

**Build:** Use transparent device renders where available. For the theme fan, align six tall rounded screen panels with consistent perspective and small horizontal overlap, 32px corners and a faint white inset edge; mask the lower part with a transparent-to-#0d0e10 gradient. Do not invent a rotation angle as a fixed brand token.

### Scenic utility workspace

**Only for:** appearance-focused utility campaigns

**Use:** Hero and broad final demonstration for a wallpaper-related utility.

**Observed:** A soft pink-grey coastal landscape backs a compact white app window; faint sun and moon symbols sit outside the hero. The final wide mountain-and-sky scene fades to white at the bottom while two overlapping utility windows remain crisp.

**Transfer:** Use atmospheric scenery only when it relates to the product's job; preserve the light, spacious treatment and let the working interface remain the subject.

**Build:** Place a scenic image inside a 16px rounded wide panel, overlay a bottom white gradient, then position two light 12px-radius windows with one offset forward and lower. Keep a soft shadow beneath the windows.

### Icons

**Observed:** Navigation app icons are small filled color tiles. Main store symbols are about 22px × 27px; social and theme icons are 18–24px. Utility features use bold monochrome 36px symbols, while technical support uses green outlined document and conversation symbols. Decorative capability tiles are richer and more dimensional than functional icons.

**Transfer:** Keep functional symbols simple, platform-familiar and aligned to text. Reserve glossy multicolor tiles for product identity and illustrative capability groups.

## Section recipes

How recurring sections are built.

### First screen: Desktop-stage opening

**Observed:** A white first screen begins with Product navigation in a 1264px centered header, 64px top and 48px bottom padding. Beneath it sits the narrower 900px × 560px Blue desktop stage, centered within a 1200px content area. Layers run from white canvas to wallpaper stage, tiny menu-bar details and a small live product example, then oversized colored capability tiles around the sides and a 208px app icon bridging the bottom edge. The 96px display product name sits immediately beneath, with a black-to-graphite sheen and an emphatic release numeral when relevant. Within the first 900px, the header, whole stage, overlapping icon and product name are visible; the 48px benefit statement begins at the fold, while support copy and purchase actions fall below. The following centered stack uses Lead copy and paired Primary button / Direct purchase button controls, separated by 16px, with a muted compatibility note below.

**Transfer:** Lead with an equally crafted depiction of the new product's task and its own app identity; create a plausible interface fragment and shaded icon when finished media is unavailable. A technical mobile campaign instead opens with oversized dark device imagery before the headline, while a portfolio index opens with a conversational introduction and linked product tiles.

**Avoid:** Do not compress this into the conventional left headline/right laptop hero, or pull every action above the fold at the expense of the product scene.

**Text style:** `display` — ui-sans-serif 600 · 96px/1 · tracking -0.025em

### Chapter heading stack

**Observed:** Centered colored Eyebrow, 48px Heading and 24px Lead copy use 32px stack gaps, followed by 64px breathing room before media. Some compact dark chapters use 16px stack gaps. Chapter labels change color without changing the typography.

**Transfer:** Use concise task-oriented chapter names and a short explanatory paragraph; align the next visual to the same container.

**Text style:** `heading` — ui-sans-serif 700 · 48px/1

### Capability split chapter

**Observed:** A small jewel capability icon precedes a left-aligned 48px heading. Short 24px/32px paragraphs sit below, separated by 40px; a tall wallpaper-backed product study fills the right half. Multiple chapters repeat the same side-by-side framing rather than alternating direction every time.

**Transfer:** Give each major capability one concrete task and one focused interface view; keep the text column visually lighter than the media.

**Text style:** `heading` — ui-sans-serif 700 · 48px/1

### Feature catalogue mosaic

**Observed:** Chapter heading stack introduces a Feature cloud grid with 40px gutters. One large Feature mosaic card anchors smaller cards; subsequent rows use three or four equal cards. Miniature product fragments, shaded app symbols and 18px body text create dense proof without heavy borders.

**Transfer:** Group related details into a readable mosaic, varying spans around the strongest demonstration instead of adding a generic icon to every card.

**Text style:** `card-heading` — ui-sans-serif 600 · 24px/32px

### Visual proof gallery

**Observed:** A centered heading is followed after 80px by two wide wallpaper-backed studies, then three smaller product scenes 40px apart. Media has 24px corners and a fine inset edge. Paired purchase capsules recur below with a compatibility note.

**Transfer:** Show the product in a few meaningful states or contexts and finish the visual proof with a restrained conversion opportunity.

**Text style:** `heading` — ui-sans-serif 700 · 48px/1

### Helpful closing

**Observed:** A tiny colored support label and a direct question headline introduce a short human support message. Resource cards sit in a three-column 40px-gutter row. Fine ownership notes, when needed, precede the Maker footer. The dark campaign keeps two support cards on near-black, then returns to white for the maker strip; the simpler utility uses a compact inline help sentence with two grey capsule links before that same footer.

**Transfer:** End by resolving the reader's remaining uncertainty: documentation, recovering a purchase, contact or a suitable equivalent. Match the amount of support to the complexity of the offer.

**Text style:** `heading` — ui-sans-serif 700 · 48px/1

### Portfolio selection

**Only for:** portfolio index pages

**Observed:** A 36px/40px conversational introduction sits above Portfolio product tiles: one dominant blue tile next to two smaller green and pink-purple-blue tiles, all inside a 1200px field. A fine divider and compact copyright footer finish the short page.

**Transfer:** Use this for a small product family, not as the default single-product landing-page opening.

**Text style:** `studio-intro` — ui-sans-serif 500 · 36px/40px

### Compatibility interlude

**Only for:** technical mobile product campaigns

**Observed:** A light grey full-width band carries a centered heading and lead, then two rows of white icon-and-label pills with softly faded horizontal edges. A large group of devices follows. The two chip rows travel in opposite directions.

**Transfer:** Use the device to communicate a real ecosystem or breadth of supported workflows; use actual compatible tools rather than invented endorsements.

**Text style:** `heading` — ui-sans-serif 700 · 48px/1

## Page flow

**Storyline:** Product theatre → clear promise and purchase → focused capability demonstrations → practical detail and visual proof → helpful resources → human-scale attribution.

### Flagship desktop product landing page

1. **Product demonstration** — A colorful desktop stage with floating capability tiles and overlapping app identity.
2. **Promise and conversion** — Large product name, bold benefit, explanatory copy, two purchase capsules and compatibility note.
3. **Capability chapters** — Panoramic theme demonstration and repeated split text/interface studies.
4. **Practical proof** — Local-tint integration cards, keyboard illustration and compact shortcut tiles.
5. **Detailed proof** — Mixed-size feature mosaic, device scene and wallpaper-backed product gallery.
6. **Closing conversion** — Repeated purchase capsules followed by helpful support resources.
7. **Attribution** — Fine ownership notes and maker footer.

**Transfer:** Use the length that the product deserves; retain crafted product theatre, concrete capability proof and a helpful human ending without requiring every chapter.

### Small studio product portfolio

1. **Introduction** — Conversational studio description with inline maker identities.
2. **Selection** — One dominant product destination beside two stacked secondary destinations.
3. **Attribution** — Copyright strip, theme and social utilities, wordmark.

**Transfer:** Use a short selection page when visitors need to choose among a few distinct products.

### Technical mobile-product campaign

1. **Product theatre** — Huge light and dark perspective phones on near-black.
2. **Promise and conversion** — White-to-silver short display statement, product explanation and white store capsule.
3. **Capabilities** — White feature bento with small interface details and a dark technical highlight.
4. **Ecosystem proof** — Grey interlude with two moving rows of compatible-tool chips and three-device imagery.
5. **Expanded capability** — Forest-green tablet chapter and three small capability cards.
6. **Choice** — Angled screen fan demonstrates visual variants.
7. **Objection handling** — Two dark support cards, then the white maker footer.

**Transfer:** Use the dark variant when detailed mobile UI and technical functionality benefit from a cinematic frame; keep light bands as deliberate contrast.

### Compact appearance utility landing page

1. **Product theatre** — Scenic desktop stage and overlapping bright app icon.
2. **Promise and pricing** — Gradient name and benefit, short explanation and a joined editable-price download control.
3. **Capabilities** — Three raised task cards, two update cards and smaller utility tiles.
4. **Visual demonstration** — Wide scenic backdrop with overlapping app windows fading into white.
5. **Help and attribution** — Inline FAQ and purchase lookup links above the maker footer.

**Transfer:** Use the shorter utility story for a focused product; use editable pricing only if it is a real part of the offer.

## Writing

Warm, direct and lightly playful, with the confidence of people who care about native software details. Benefits are grounded in specific actions and practical compatibility information rather than grand transformational claims.

**Do not copy:** Do not reuse product or studio names, logos, app icons, maker identities, artwork, prices, version numbers, compatibility claims, third-party endorsements or product-specific claims. Source examples illustrate cadence only.

- **Addressing the reader:** Address the reader as you and your when discussing control and personalization. Refer to the product by name in explanatory copy; use we sparingly for support and maker attribution.
- **Rhythm:** Headlines are commonly 3–7 words, often one short sentence or two punchy fragments. Support lines are one or two explanatory sentences; feature paragraphs stay compact. Playful headlines are followed immediately by literal explanations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Benefit headline | A compact category promise, sometimes with a small verbal twist. | 4–10 words | “The ultimate music accessory for your Mac.”<br>“Terminal. Velocity.”<br>“The missing app for Dark Mode.” |
| Chapter heading | Short task-led title or restrained pun. | 3–6 words | “Play all the right keys.”<br>“Make it yours.” |
| Capability explanation | Start with a concrete verb and describe the user's control. | One or two compact sentences | “Customize the layout, alignment and position to fit your setup.” |
| Primary action | Literal destination or action with platform or purchase route. | 2–4 words | “Buy Directly”<br>“Download for Mac” |
| Closing support | A friendly direct question followed by useful destinations. | One short question | “Have questions that need answers?” |
| Studio introduction | Small-team warmth and a plain statement of craft. | One conversational sentence | “A tiny studio making delightful apps for Mac & iOS, &” |

**Words and phrasing to use:** choose; customize; make it yours; built natively; simple; beautiful; crafted; your setup; check the docs

**Avoid:** revolutionary; disrupt; 10x; unlock your potential; enterprise-grade everything; effortless magic without explanation

**Rules:**

- Keep practical system requirements and payment terms close to purchase actions.
- Use one playful idea in a headline, then make the support copy literal.
- Describe visible actions and settings instead of abstract benefit lists.
- Make support copy welcoming but direct users toward the most useful self-service resource first.

## Do's and Don'ts

### Do

- Keep the default name at 96px/1 with -0.025em tracking and chapter headings at 48px/1 with normal tracking.
- Align major grids and footer rules to 1200px of usable content within the 1264px container.
- Use 24px corners for visual stages and feature tiles, 16px for resource cards.
- Keep purchase capsules 56px tall with 24px side padding and a 16px gap when paired.
- Separate major chapters by 96px and use 40px gutters for detailed feature grids.
- Pair vivid product imagery with black text on white rather than coloring every paragraph.
- Let the ending resolve support needs before the small maker strip.
- Maintain crisp interface layers over softly blurred wallpaper backings.

### Don't

- Do not turn the default page into an all-dark terminal aesthetic; dark green is a scoped product campaign.
- Do not apply -0.025em tracking to the normal-tracked 48px chapter headings.
- Do not replace the capsule purchase row with full-width colored rectangular buttons.
- Do not give every pale marketing tile the heavy shadow reserved for floating product windows.
- Do not use the orchid-purple-blue name gradient as a universal text decoration.
- Do not turn the maker footer into multi-column corporate navigation; its content is a small attribution plus utilities.
- Do not set all marketing text in a code font to match a technical interface.
- Do not force equal card heights across the mixed-span feature catalogue.

## Motion and responsive

### Motion

**Observed:**

- Actions commonly declare 0.15s transitions with cubic-bezier(0.4,0,0.2,1) across color, background, border and related visual properties; a smaller set of surfaces declares 0.5s with the same curve.
- The two compatibility chip rows declare marquee-left and marquee-right, each 25s linear and infinite.
- A compact floating purchase dock is visible in later technical-product chapters, with app identity and a white buy capsule.

**Transfer:**

- Keep hover feedback concentrated in capsule fills, edges and link treatments using the declared short transition.
- For a real compatibility roster, use two opposing slow chip rows rather than a single loud ticker.
- On long technical campaigns, a small floating purchase dock can preserve access to the action without adding a full-width sticky banner.

**Unknown:**

- The exact scroll triggers, device-scene animation timing, floating-dock activation threshold and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 480px, 640px, 768px, 1024px, 1280px and 1536px.
- Responsive classes set the desktop stage to 420px tall before the 560px variant, display names to 60px before 96px, chapter headings to 30px before 48px, and lead copy to 18px before 24px.
- Product navigation is hidden before the small breakpoint. Paired purchase actions change from a column to a row, and footer attribution changes from centered stacking to a horizontal alignment.

**Transfer:**

- At narrow widths, preserve the stage, overlapping app icon and name relationship while reducing surrounding decorative tiles before shrinking the working interface into illegibility.
- Stack split chapters and resource cards in reading order, with media staying attached to its explanation.
- Collapse the portfolio field into fewer columns while retaining the lead product's hierarchy.

**Unknown:**

- Mobile layouts, precise decorative repositioning and narrow-screen device transforms have not been visually verified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
