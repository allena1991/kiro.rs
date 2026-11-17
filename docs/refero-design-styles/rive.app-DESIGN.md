# Rive — angular type, electric stages

## Overview

A black, technical showroom with squared-off futuristic display type and restrained grotesk supporting text. Vivid animation, game-like illustration and working interfaces provide the spectacle while the surrounding architecture stays almost entirely charcoal. It suits creative tools, developer platforms and products whose output can be demonstrated visually; spacious feature chapters contrast with dense catalogs and proof cards.

### Essentials

- Headlines feel like lettering on a futuristic instrument: Orbitron uppercase, 40px/1.2 at weight 900 with 0.01em tracking; section titles step down to 24px/1.4 at weight 700.
- The default opening is an asymmetric live showroom, not a centered slogan: a 300px-wide vertical media reel beside a 631px text-and-action column within a 1000px container, separated by about 68px.
- Actions are compact charcoal keys rather than bright pills: 40px tall, 4px radius, 16px horizontal padding, with Tomorrow 12px/1.2 uppercase labels tracked 0.1em.
- Color belongs chiefly to the demonstrations: black and #111111 occupy the page architecture, #ffa41c marks small chapter labels, and intense lime, violet, cyan or pink stays inside framed media. Keep substantially more dark negative space than saturated area.
- Product output must be staged as something real: use a labeled vertical reel, a large working-interface view or a tactile illustrated object on a vivid backing. If finished animation is unavailable, make polished static demonstrations at the same scale rather than replacing them with abstract decoration.
- Technical markings bind the spectacle together: Tomorrow 14px/1 uppercase eyebrows tracked 0.1em, small utility icons, and low-contrast labels beneath media. Pair the dark stage with compact proof cards at 313px wide, 8px radius and 12px padding.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Amber chapter | `#ffa41c` | `--color-chapter` | text, link, accent | Small product chapter labels and their icons, never a general button fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White signal | `#ffffff` | `--color-foreground` | text, action | Hero titles, action labels and small symbols. |
| Soft white | `#f1f1f1` | `--color-heading` | text | Section headings and pricing numerals. |
| Email field | `#ebebeb` | `--color-input` | surface | Light newsletter input, a rare pale filled surface. |
| Secondary gray | `#aaaaaa` | `--color-label` | text | Secondary author metadata and catalog copy before local opacity. |
| Muted copy | `#999999` | `--color-muted` | text, link | Supporting copy and footer links; also the visible result of 60% white over black. |
| Dim quote | `#898989` | `--color-quote` | text | Visible 50% white quote text over the #121212 card. |
| Trust gray | `#888888` | `--color-trust` | text | Visible rgba(170,170,170,0.8) reassurance text on black. |
| Media backing | `#262626` | `--color-media-base` | surface | Backing behind the opening media reel. |
| Key charcoal | `#1d1d1d` | `--color-button` | action, surface | Default rectangular action background. |
| Translucent key | `#1a1a1a` | `--color-subtle-action` | action, surface | Visible white at 10% over black for newsletter submission. |
| Card black | `#121212` | `--color-card` | surface | Testimonial and pricing cards. |
| Charcoal band | `#111111` | `--color-band` | background, surface | Alternating feature chapters and terminal panel. |
| Dark separator | `#0d0d0d` | `--color-rule` | border | Visible white at 5% over black in comparison dividers. |
| Black canvas | `#000000` | `--color-canvas` | background, text | Default page and navigation canvas; inverted text on light strips. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dense capability catalogs | Catalog gray | `#555555` | `--color-catalog-copy` | text | Visible 50% #aaaaaa descriptions on black. |
| developer installation panels | Command lime | `#5ed413` | `--color-terminal-green` | text | Visible 80% #71ff19 over #111111 in terminal commands. |
| developer installation panels | Command cyan | `#17c5cf` | `--color-terminal-cyan` | text | Visible 80% #19f2ff over #111111 in terminal command verbs. |
| pricing pages | Plan mint | `#78facb` | `--color-plan-mint` | text, accent | Plan qualification notes and availability checks. |
| illustrated conversion panels | Electric pink stage | `#bf007b` | `--color-stage-pink` | background, accent | Saturated lower field of the illustrated closing stage. |
| illustrated conversion panels | Violet stage light | `#ac67bd` | `--color-stage-violet` | background, accent | Soft upper-center light within the pink closing stage. |

## Typography

- **Orbitron** — Hero, chapter and small capability headings. Wide geometric techno display with clipped corners and long horizontal strokes. Font stack: "Orbitron", sans-serif.
- **Tomorrow** — Navigation, actions, eyebrows, metadata and compact closing statements. Angular technical sans with a narrower, more utilitarian rhythm than the headline face. Font stack: "Tomorrow", sans-serif.
- **Inter** — Paragraphs, footer links and pricing numerals. Neutral grotesk; regular prose balances highly constructed headings. Font stack: "Inter", sans-serif.
- **Inter Display** — Quotes and catalog descriptions. Compact display-optimized grotesk used at small sizes. If unavailable, use **Inter**. Use 400 for quotes and 500 for catalog descriptions. Font stack: "Inter Display", Inter, sans-serif.
- **PragmataPro VF Variable** (only for developer installation panels) — Shell commands and operating-system tabs. Very narrow technical monospace that keeps installation text on one line. If unavailable, use **Fragment Mono**. Use 400; allow horizontal overflow rather than compressing glyphs. Font stack: "PragmataPro VF Variable", "Fragment Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Orbitron | 900 | 40px | 1.2 | 0.01em, uppercase | Main marketing headline; left aligned by default, centered for product and pricing variants. |
| heading | Orbitron | 700 | 24px | 1.4 | normal, uppercase | Capability chapter headings. |
| proof-heading | Orbitron | 700 | 24px | 1.3 | 0.0083em, uppercase | Centered reach or adoption statement above a logo field. |
| newsletter-heading | Orbitron | 700 | 20px | 1.2 | 0.01em, uppercase | Newsletter heading. |
| body | Inter | 400 | 16px | 1.6 | normal | Supporting paragraphs, generally muted rather than white. |
| footer-link | Inter | 500 | 16px | 1.2 | normal | Underlined footer destinations and muted legal copy. |
| eyebrow | Tomorrow | 500 | 14px | 1 | 0.1em, uppercase | Amber chapter label with a small leading icon; white for action-group headings. |
| small-copy | Inter | 400 | 14px | 1.2 | normal | Reassurance line and plan descriptions. |
| quote | Inter Display | 400 | 14px | 1.5 | normal | Compact customer quotations, locally dimmed. |
| footer-label | Tomorrow | 500 | 14px | 1.2 | normal, uppercase | Low-contrast footer column headings. |
| button | Tomorrow | 500 | 12px | 1.2 | 0.1em, uppercase | Compact conversion labels. |
| navigation | Tomorrow | 500 | 12px | 1.2 | normal, uppercase | Navigation and translucent illustrated-stage action. |
| attribution | Tomorrow | 400 | 11px | 1.6 | 0.01em, uppercase | Name and role in quote card headers. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | Inter | 700 | 28px | 1.4 | -0.0286em | Price with a much smaller muted per-seat suffix. |
| illustrated conversion panels | closing-title | Tomorrow | 500 | 20px | 1.4 | -0.01em, uppercase | Two centered lines beneath the illustrated object. |
| pricing pages | plan-title | Tomorrow | 500 | 20px | 1 | 0.07em, uppercase | Plan name at the top of each card. |
| dense capability catalogs | catalog-body | Inter Display | 500 | 15px | 1.4 | normal | One or two lines under a capability tile, with 50% local opacity. |
| developer installation panels | code | PragmataPro VF Variable | 400 | 14px | 1.2 | normal | Installation line and operating-system tabs. |
| dense capability catalogs | catalog-title | Orbitron | 700 | 14px | 1.4 | 0.05em, uppercase | Short capability title beside a small icon, with 70% local opacity. |

**Notes:**

- Keep the futuristic construction in headings and labels, not in long paragraphs.
- Heading weight drops from 900 to 700 below the hero. Tracking becomes conspicuously open on tiny action and eyebrow text.
- Use white for the promise, soft white for chapter titles and dim gray for explanatory text. Quote and catalog text deliberately have lower contrast than main prose.
- No viewport-relative typography formula is prescribed; the desktop scale uses a restrained 40px headline rather than monumental oversized lettering.

## Layout

**Density:** Airy at chapter scale, compact inside controls and catalogs. Large dark fields surround relatively small text groups.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label separation in actions and chapter labels. |
| 10px | Heading-to-body spacing and internal text-group rhythm. |
| 12px | Quote card padding and media-to-caption stack gap. |
| 15px | Newsletter input padding and form column gap. |
| 16px | Button horizontal padding and pricing card padding. |
| 20px | Pricing column gap and terminal vertical padding. |
| 30px | Default content gutter, three-column grid gap and separated hero groups. |
| 40px | Separation before chapter actions and footer side padding. |
| 60px | Major chapter and footer vertical padding. |
| 68px | Opening reel-to-copy separation. |
| 80px | Catalog collaboration chapter vertical padding. |

### Containers and grids

- **marketing container**: max width 1000px · side padding 30px. Centered default content width; full-width black or charcoal bands extend beyond it.
- **opening columns**: max width 1000px · 2 columns · gap 68px. Asymmetric 301px reel and 631px copy/action column.
- **chapter split**: max width 1000px · 2 columns · gap 30px. Approximately 470px media beside copy limited to 408px; the large demonstration variant can overflow beyond the right content edge.
- **proof grid**: max width 1000px · 3 columns · gap 30px. 313px-wide testimonial cards; variable content heights inside a stable column system.
- **footer columns**: max width 1000px · 6 columns · side padding 40px. Unequal link columns distributed across the full content width.
- **capability catalog** (only for dense capability catalogs): max width 1000px · 3 columns · gap 30px. Media-first capability tiles with 313px-wide previews.
- **plan grid** (only for pricing pages): max width 1000px · 4 columns · gap 20px. Four equal 235px cards; comparison uses a label column plus four aligned value columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action keys | 4px |
|  | cards and media | 8px |
| dense capability catalogs | platform media tiles | 10px |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default page background.

**CSS:** `background: #000000`

**Observed:** The canvas stays flat and untextured; depth comes from the demonstrations rather than ambient page effects.

**Transfer:** Let black negative space separate content and hold bright media.

#### Charcoal chapter · level 0

**Use:** Alternating feature and social-proof bands.

**CSS:** `background: #111111; padding: 60px 30px`

**Observed:** Full-bleed band with centered content; some chapters fill 900px vertically while product detail chapters fit their media.

**Transfer:** Alternate chapter tone without introducing a separate light theme.

#### Low-rise card · level 1

**Use:** Customer proof and plans.

**CSS:** `background: #121212; border-radius: 8px; box-shadow: none`

**Observed:** A slight tonal lift, not a floating sheet; dark edges remain visually understated.

**Transfer:** Distinguish groups through fill and spacing, not heavy strokes.

#### Fine separator · level 0

**Use:** Comparison group divisions and subtle footer separation.

**CSS:** `background: rgba(255, 255, 255, 0.05); height: 1px`

**Observed:** Thin rules structure dark space without boxing each row.

**Transfer:** Separate groups rather than drawing a bright table grid.

#### Illustrated conversion stage · level 1

**Only for:** illustrated conversion panels

**Use:** High-color conversion break on product, catalog and pricing layouts.

**CSS:** `background: radial-gradient(ellipse at 50% 0%, #ac67bd 0%, rgba(172, 103, 189, 0) 70%), #bf007b; border-radius: 8px; overflow: hidden; max-width: 1000px; height: 360px`

**Observed:** A vivid magenta field with soft violet light above a small glossy blue object; centered white statement and translucent action sit below it.

**Transfer:** Match the soft light and strong color field; exact gradient stops are not essential. Keep this treatment bounded, never page-wide.

## Components

### Fixed navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: fixed; top: 0px; height: 64px; z-index: 10; background: #000000; padding: 0px 20px`

**Text style:** `navigation` — Tomorrow 500 · 12px/1.2 · uppercase

**Observed:** A compact brand symbol starts a 1000px inner row. Dropdown destinations cluster left; documentation and Primary button sit right. Ordinary labels render at half white opacity.

**Transfer:** Preserve the sparse utility-bar feel and align its contents to the main container.

### Primary button

**Use:** Conversion and feature navigation.

**CSS:** `display: flex; align-items: center; gap: 8px; height: 40px; padding: 0px 16px; border-radius: 4px; background: #1d1d1d; color: #ffffff`

**Text style:** `button` — Tomorrow 500 · 12px/1.2 · tracking 0.1em · uppercase

**Observed:** Short labels pair with small leading utility symbols or a right arrow. Multiple actions share the same charcoal treatment; pricing actions stretch across the card.

**Transfer:** Make hierarchy through placement and label, not a bright primary fill.

### Quote card

**Use:** Dense proof wall.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; background: #121212; border-radius: 8px; padding: 12px`

**Text style:** `quote` — Inter Display 400 · 14px/1.5

**Observed:** Avatar or organization mark at left, two lines of Attribution at right, then quote text separated by 16px. Quote text is white at 50% opacity; cards sit in three columns.

**Transfer:** Use actual concise endorsements or verified results with a visible attribution.

### Newsletter field

**Use:** Shared page-ending subscription row.

**CSS:** `background: #ebebeb; border-radius: 8px; padding: 15px; height: 52px; box-sizing: border-box`

**Observed:** A 510px-wide email input sits beside Newsletter submit with a 15px gap. The form occupies the right side of a row whose left side contains Newsletter heading and support text.

**Transfer:** Keep the pale input as the main light-filled utility surface.

### Newsletter submit

**Use:** Submit the email form.

**CSS:** `background: rgba(255, 255, 255, 0.1); border-radius: 8px; padding: 15px; height: 52px; width: 90px; box-sizing: border-box; color: #ffffff`

**Observed:** A plain mixed-case form control, distinct from the tightly tracked uppercase marketing keys.

**Transfer:** Keep this form-specific variant rather than enlarging every button.

### Footer link

**Use:** Navigation in the shared ending.

**CSS:** `color: #999999; text-decoration-line: underline`

**Text style:** `footer-link` — Inter 500 · 16px/1.2

**Observed:** Underlined text in six unequal columns, with small uppercase column labels. Link rows have about 10px spacing.

**States:** Declared: hover color #fff and underline retained; focus-visible unknown.

**Transfer:** Group destinations by user task rather than putting every link into a uniform card.

### Installation panel

**Only for:** developer installation panels

**Use:** Fast technical entry alongside a conventional sign-up path.

**CSS:** `display: flex; flex-direction: column; background: #111111; border: 1px solid #000000; border-radius: 4px; padding: 20px 0px; gap: 9px`

**Text style:** `code` — PragmataPro VF Variable 400 · 14px/1.2

**Observed:** White eyebrow, operating-system tabs with an underlined active tab, a hairline, a lime-and-cyan command and copy icon; a second action group underneath holds sign-up and desktop controls. Child groups inset content by 20px.

**Transfer:** Use real installation or integration content. For a nontechnical product, keep the grouped action tray but replace the command with a compact task preview.

### Capability tile

**Only for:** dense capability catalogs

**Use:** Browsable media-led feature inventory.

**CSS:** `display: flex; flex-direction: column; gap: 12px; width: 313px`

**Text style:** `catalog-title` — Orbitron 700 · 14px/1.4 · tracking 0.05em · uppercase

**Observed:** 313×242px media with 8px rounded corners leads; small icon and uppercase title follow, then a dim Catalog body paragraph. A small status badge can sit at the title's far end. The text has no card fill.

**Transfer:** Show one behavior per tile; frame a legible part of the interface rather than shrinking an entire application.

### Plan card

**Only for:** pricing pages

**Use:** Compare commercial options.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; background: #121212; border-radius: 8px; padding: 16px; gap: 30px; width: 235px; box-sizing: border-box`

**Text style:** `plan-title` — Tomorrow 500 · 20px/1 · tracking 0.07em · uppercase

**Observed:** Plan name, mint eligibility note when needed, Price with per-seat suffix, full-width Primary button, suitability copy, then a feature list. Equal-height dark columns remain understated; there is no oversized bright recommended card.

**Transfer:** Keep the plan price legible and use mint for qualifiers, not a broad tint.

### Closing action

**Only for:** illustrated conversion panels

**Use:** Conversion inside the saturated object stage.

**CSS:** `background: rgba(255, 255, 255, 0.2); border-radius: 8px; padding: 7px 15px; height: 28px; box-sizing: border-box; color: #ffffff`

**Text style:** `navigation` — Tomorrow 500 · 12px/1.2 · uppercase

**Observed:** Small translucent rounded key beneath the centered two-line closing statement; the illustration carries the visual weight.

**Transfer:** Do not compete with the object by turning this into a large solid-white button.

## Imagery and graphics

### Labeled output reel

**Use:** Signature default opening device.

**Observed:** A narrow vertical filmstrip of real applications and animated output: physical screens, dark game interfaces and a vivid lime phone scene. Each 300px-wide image has a black caption cap; the strip continues beyond both viewport edges. Dark, realistic material and neon output alternate.

**Transfer:** Create three or four polished scenes showing the new product in distinct contexts. If video is unavailable, use static interface mockups on believable devices plus one saturated graphic scene.

**Build:** Stack 300px-wide media tiles with 10px gaps in a clipped 900px-tall rail. Add a 30px black top cap with centered uppercase 14px technical labeling and 8px top corners; clip the image below to 8px bottom corners. Offset the stack so the first and last tiles are only partially visible. Keep media vivid and the frame neutral.

### Working interface stage

**Use:** Large chapter demonstrations and centered product opening.

**Observed:** Dark application chrome surrounds brightly colored artwork, state-machine nodes or timelines. One demonstration is 815×493px and extends beyond the content edge; split chapters use approximately 470px media. The centered product variant introduces a 1060×678px interface containing a large blue-and-magenta illustrated creature.

**Transfer:** Use authentic product chrome with one visually strong task visible. Minimum acceptable version is a static, sharply rendered interface view with a clear result, not a generic dashboard.

**Build:** Compose a dark rectangular application frame with an 8px clip, a thin top utility row, narrow side panels and a dominant central result. Keep fine controls subdued; reserve saturated color for the result. For a nonscreen product, substitute a carefully lit object with a narrow explanatory UI overlay.

### Platform symbol matrix

**Use:** Compact compatibility or ecosystem proof.

**Observed:** Fourteen or fifteen recognizable symbols at about 50px with small gray labels, arranged in five columns and three rows. Most marks are white, with native brand colors retained on selected symbols; black surrounds every item.

**Transfer:** Use genuine integrations or supported output types. Without an ecosystem, make an equally compact matrix of product modes or supported workflows rather than an invented partner wall.

### Monochrome customer field

**Use:** Reach statement before testimonial proof.

**Observed:** Two centered rows of customer wordmarks in muted gray; a 610px-wide uppercase heading sits above and a roughly 730px paragraph below.

**Transfer:** Use authorized customer marks in a single muted treatment; keep the proof statement modest in scale.

### Glossy object on pink

**Only for:** illustrated conversion panels

**Use:** Distinctive closing conversion scene.

**Observed:** A small rounded blue vehicle-cabin-like object floats in the upper center of a 1000×360px magenta stage. Pale edge highlights, layered indigo glass and a short cast shadow give it tactile depth; a soft violet pool of light sits behind it. White text and a small translucent action form the lower half.

**Transfer:** Make an original rounded object that represents the new product's output, not an unrelated decorative mascot. Minimum acceptable version is an SVG cutaway with two or three shaded planes and crisp specular edge strokes.

**Build:** Use the Illustrated conversion stage surface. Center an approximately 230×120px SVG object above the statement: dark indigo outer silhouette, two inset blue planes, a translucent pale-blue rim and two narrow white highlights on one edge. Add a low black ellipse with 20% opacity below it. Behind the object, layer a wide translucent lavender ellipse or radial light; keep it soft and the object edges sharp.

### Icons

**Observed:** Small solid white utility glyphs, usually 17–20px, accompany action labels; chapter icons use amber. Capability captions use fine outline-like symbols. Platform illustrations are larger, about 50px. Social symbols form a compact white row at the footer's right.

**Transfer:** Use simple technical glyphs with consistent optical weight; do not make large decorative icon badges for every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Asymmetric output opening

**Observed:** Black stage beneath Fixed navigation. Within a centered 1000px frame, the left third is a clipped 300px output reel and the wider right column carries a small spaced brand mark, Display headline wrapping to two lines, muted Body paragraph, Installation panel and a dim reassurance line. The columns are separated by about 68px. The right stack is vertically centered with room for the navigation; headline width is about 631px. Within the first 900px, the headline, three-line support, both entry paths and trust line are visible; the reel deliberately runs beyond the top and bottom. The following charcoal chapter begins below the fold. Layers are flat black, reel media and captions, text, then the slightly lifted action tray.

**Transfer:** Use the Labeled output reel and a concrete short promise even when the product has no video: polished static scenes provide the same visual strength. For a product detail opening, center the eyebrow and headline above a large Working interface stage. For a catalog, center a promise and support above a compact release carousel; for pricing, center a promise above equal plan columns.

**Avoid:** Do not replace this default with a full-width gradient hero, giant centered headline or a generic single dashboard floating behind the text.

**Text style:** `display` — Orbitron 900 · 40px/1.2 · tracking 0.01em · uppercase

### Alternating capability chapter

**Observed:** Charcoal chapter and Black stage alternate. A 1000px split row pairs 408px-limited copy with media, with 30px gap and 60px vertical padding. Eyebrow, Heading and Body are spaced by about 10px; Primary button sits about 40px after copy. Reverse media and copy between chapters. A flagship demonstration can grow to 815px wide and run past the right container boundary.

**Transfer:** Explain one meaningful capability per chapter and give its demonstration more space than its title.

**Text style:** `heading` — Orbitron 700 · 24px/1.4 · uppercase

### Reach and proof wall

**Observed:** On Charcoal chapter, Proof heading is centered above Monochrome customer field, followed by muted explanatory copy. Quote cards then form a three-column 1000px wall with 30px gaps. The reach statement uses the same 24px scale as chapters; there is no enormous isolated numeral.

**Transfer:** Pair a substantiated adoption or performance statement with credible identities and compact firsthand proof.

**Text style:** `proof-heading` — Orbitron 700 · 24px/1.3 · tracking 0.0083em · uppercase

### Newsletter and utility ending

**Observed:** A black newsletter row uses 50px top padding: Newsletter heading and a two-line Body note at left, light Newsletter field and Newsletter submit at right. A quiet rule introduces six Footer link columns with 60px vertical padding. Another rule separates the bottom identity area: compact wordmark and legal copy at left, a small white social row at right. The full footer is about 758px tall. The default landing layout ends directly with this utility sequence after the proof wall; detail, pricing and catalog variants place the illustrated invitation before it.

**Transfer:** Retain the clear return to utility: a single subscription request, organized destination columns, then identity and social links. Adapt column contents to the new product instead of adding a second loud pitch.

**Text style:** `newsletter-heading` — Orbitron 700 · 20px/1.2 · tracking 0.01em · uppercase

### Capability index

**Only for:** dense capability catalogs

**Observed:** A left-aligned chapter label and Heading introduce a short Body summary, then Capability tiles form three columns with 30px horizontal gaps. Each preview is roughly 313×242px; title and description remain directly on black. Repeated chapters distinguish interactive behavior, creation, collaboration and delivery without changing the basic tile grammar. A charcoal release tray near the opening shows several small landscape story thumbnails and previous/next controls.

**Transfer:** Group a long inventory by user outcome; reuse the same media-led tile for each behavior rather than making every capability a full-height chapter.

**Text style:** `catalog-title` — Orbitron 700 · 14px/1.4 · tracking 0.05em · uppercase

### Pricing and comparison

**Only for:** pricing pages

**Observed:** Centered Display promise begins after 134px top padding, followed by two short muted support blocks and a compact yearly/monthly switch. Four Plan cards span 1000px with 20px gaps. Their headers and actions appear in the first 900px, but their full lists extend below it. A long comparison follows with one label column, four aligned values, 30px-high rows separated by about 40px, subtle group rules and mint or blue checks. The table repeats compact plan names, rates and action keys above its values.

**Transfer:** Keep plan cards calm and equal; use aligned comparison columns for detail, with plain-language row labels.

**Text style:** `price` — Inter 700 · 28px/1.4 · tracking -0.0286em

### Illustrated final invitation

**Only for:** product, catalog and pricing layouts

**Observed:** Illustrated conversion stage sits inside the 1000px content width, introduced with 30px top space. Glossy object on pink anchors the upper center; Closing title and Closing action sit underneath. Catalog layouts precede it with a small centered updates invitation and changelog key.

**Transfer:** Use this distinct bright scene as a product-specific final invitation, then return to black for the shared utility ending.

**Text style:** `closing-title` — Tomorrow 500 · 20px/1.4 · tracking -0.01em · uppercase

## Page flow

**Storyline:** promise with visible output → explain how it works → show breadth or proof → invite action → shared subscription and utility ending

### Flagship marketing landing page

1. **promise** — Asymmetric output reel beside a compact technical headline and two entry paths.
2. **product demonstration** — One spacious editor-like chapter followed by a compatibility matrix chapter on alternating dark bands.
3. **social proof** — Centered reach statement, subdued customer marks and compact testimonial wall.
4. **utility ending** — Newsletter form, six destination columns, identity, legal text and social symbols; no illustrated conversion banner in this variant.

**Transfer:** Use the asymmetric opening as the default; select chapters and proof appropriate to the new product without treating this sequence as a fixed template.

### Commercial evaluation and plan selection

1. **promise** — Centered outcome-and-price headline with a frank limitation note and billing switch.
2. **pricing** — Four equal dark plan cards with full-width charcoal actions.
3. **objection handling** — Long aligned comparison grouped by feature category, with repeated plan controls.
4. **closing call** — Illustrated conversion stage before shared newsletter and footer.

**Transfer:** Use concise plan summaries first and detailed availability second; carry the same restrained dark controls into the comparison.

### Deep capability browsing

1. **promise** — Centered technical promise, amber label and concise support.
2. **freshness proof** — Charcoal carousel of release thumbnails with compact controls.
3. **capability chapters** — Media-first three-column catalogs organized around user jobs.
4. **closing call** — Centered updates invitation, bright illustrated stage, newsletter and complete utility footer.

**Transfer:** Let repeated previews carry the long page; vary chapter subjects, not tile styling.

### Dedicated product explanation

1. **promise** — Centered amber eyebrow and wide uppercase headline, a white inverted support strip, two actions and a large colorful working interface.
2. **product demonstration** — Alternating split chapters with 470px media showing behavior, creation and collaboration.
3. **breadth proof** — Five-column platform matrix paired with export or delivery copy.
4. **closing call** — Pink illustrated object stage, then newsletter and the full utility ending.

**Transfer:** Use the centered opening only for a focused product page; follow with alternating concrete demonstrations rather than a long unstructured gallery.

## Writing

Direct, technically confident and outcome-driven. The voice treats creative work as something that becomes a real shipped product, combining plain explanation with brief, emphatic contrasts.

**Do not copy:** Do not reuse the Rive name, wordmarks, proprietary artwork, customer logos, product names, quoted endorsements, adoption figures or performance claims. Source examples illustrate syntax only; replace them with truthful material for the new product.

- **Addressing the reader:** Address the reader as you or your when describing the work; refer to the product by name when explaining its architecture. Use we sparingly and keep customer quotations clearly attributed.
- **Rhythm:** Headlines are compact verb phrases or category declarations. Supporting paragraphs can be several sentences, but sharp fragments break up technical explanations; action labels are usually one to three words. No exuberant punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the category or promise in a compact declarative phrase; uppercase is a visual treatment, not a reason to shout verbally. | 4–10 words | “The Interactive experience engine”<br>“Ship everywhere For free” |
| Capability heading | Lead with a concrete verb and its outcome. | 3–7 words | “Design, code, and animate”<br>“Build once, ship anywhere”<br>“Collaborate in real-time” |
| Supporting explanation | Explain a real workflow and contrast it with unnecessary work. | 1–5 short sentences | “No mockups, no prototypes, no handoff. The real thing.” |
| Primary action | Literal task or destination, not a witty slogan. | 1–3 words | “Sign up”<br>“Download desktop app”<br>“Get in touch” |
| Commercial caveat | State a limitation and the way to remove it without euphemism. | Two short sentences | “Free exports play a [Brand] splash screen. Upgrade to remove it.” |
| Closing invitation | Imperative followed by the thing the reader can produce. | Two short lines | “Start building production-ready graphics” |

**Words and phrasing to use:** build; ship; native; production-ready; real-time; interactive; open source; design and develop; what you build

**Avoid:** revolutionary magic; effortlessly transform everything; delightful journey; unlimited possibilities; best-in-class without qualification

**Rules:**

- Name the behavior before explaining the implementation.
- Use concrete platform, file or workflow terms when they help evaluation; avoid stacking jargon just to sound technical.
- Make commercial limitations as plain as commercial benefits.
- Use short contrastive fragments after an explanatory paragraph, not as every line of body copy.
- Keep CTA destinations literal and consistent across the page.

## Do's and Don'ts

### Do

- Keep the hero at Orbitron 40px/1.2, weight 900, with 0.01em tracking.
- Use the 1000px content width to align navigation, chapters, proof and endings.
- Preserve the 300px output reel and wider text column in the default desktop opening.
- Limit ordinary action keys to 40px height and 4px radius.
- Set main support text at Inter 16px/1.6 and a muted gray.
- Use 60px chapter padding and 30px grid gaps to separate compact content from large dark fields.
- Keep quote cards compact with 12px padding and 11px uppercase technical attribution.
- Return to black utility surfaces after any saturated conversion stage.

### Don't

- Do not use a generic neutral sans for the angular 40px display role.
- Do not turn the entire black canvas into an atmospheric purple glow; vivid fields belong inside media or the bounded closing stage.
- Do not promote amber labels into orange primary buttons.
- Do not replace 4px action corners with capsule shapes.
- Do not brighten every supporting paragraph to white; preserve the #999999 reading tier.
- Do not render the reach statement as a giant numeric counter; it stays a 24px uppercase sentence.
- Do not put filled cards behind catalog descriptions; only their media is framed.
- Do not strip underlines from the 16px footer links or replace the six-column ending with a minimal copyright bar.

## Motion and responsive

### Motion

**Observed:**

- The opening uses a vertically translated media ticker with clipped partial tiles. Product demonstrations are videos or interactive graphics.
- Footer and descriptive links declare white hover text with underline retained.
- No action transition durations or animation timings are established.

**Transfer:**

- Keep moving output within its framed stage; the navigation and reading column remain visually stable.
- Use a clipped reel for diverse outputs and focused loops for individual behaviors, rather than animating every text block.

**Unknown:**

- Ticker speed, looping duration, playback triggers, scroll choreography and focus-visible treatment are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints around 389px, 640px and 949px; the catalog also has a declaration near 960px.

**Transfer:**

- As a narrow-layout adaptation, stack the promise and action tray before a shortened output rail; preserve a partially visible next tile so it still reads as a reel.
- Reduce three-column capability and proof grids before shrinking their type. Stack split chapters while keeping output close to the explanation.
- Allow pricing comparisons to scroll horizontally rather than crushing four value columns into unreadable text.

**Unknown:**

- Only the desktop compositions are established; exact mobile order, navigation behavior, type sizes and responsive gaps are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
