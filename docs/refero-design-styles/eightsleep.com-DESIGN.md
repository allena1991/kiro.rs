# Eight Sleep — engineered for dusk

## Overview

A premium technology style that makes machinery feel at home in intimate, beautifully lit spaces. Spacious white and pale gray chapters alternate with midnight blue demonstrations and black proof sections; warm interiors soften the cool technical atmosphere. Medium-weight grotesk typography, small equipment-like labels, cinematic product renders and translucent data cards give it a measured but aspirational character.

### Essentials

- The product floats between sky and typography: a centered 200px/0.81 medium grotesk title with -0.02em tracking sits behind a dark isolated object, above a 24px support line and white action.
- Headings sound like short performance promises: 44px/1.1 at weight 500 with 0.01em tracking, balanced by compact 15px/19.6px explanation and 14px uppercase mono labels.
- Conversion is rectangular, not pill-shaped: 57px actions with 8px corners and 16px 32px padding, white on imagery and black on light chapters.
- Color is environmental rather than decorative: white and pale gray carry most reading sections; full-width midnight blue or black chapters hold immersive demonstrations and proof. Saturated blue is restricted to data glows and social mentions, not ordinary action fills.
- Domestic realism and engineering share the stage: warm daylight, timber, upholstery and charcoal hardware in rounded 16px–24px frames; a large isolated object against atmospheric sky is the required counterpoint. Use a carefully lit cutout if a cinematic render is unavailable.
- A fine orbital timeline and luminous instrument panel make invisible behavior tangible: thin curved paths, small nodes, 20px translucent cards and a blue glow blurred about 39px. Include this device around one meaningful process or metric rather than inventing ornamental dashboards.
- The closing conversion returns to a monumental scene, not a generic banner: centered product name, short benefit, starting price and white action over an 899px lifestyle image, followed by reassurance tiles and a deep black multi-column footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Midnight | `#031938` | `--color-midnight` | background | Immersive process and instrument chapters. |
| Deep teal blue | `#0b3049` | `--color-promo` | background | Narrow promotional strip. |
| Proof horizon | `#1b315f` | `--color-proof-blue` | background | Lower end of the black-to-blue proof atmosphere. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Instrument blue | `#4f7fff` | `--color-glow` | accent | Blue illumination at 0.5 opacity inside instrument compositions; never a general button color. |
| Mention blue | `#1862ff` | `--color-social-link` | link | Mentions and linked handles inside social proof. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text, action | Main canvas, inverse type and white image-overlay actions. |
| Pale chapter | `#f7f7f7` | `--color-pale` | background, surface | Light feature chapters and research grouping. |
| Social paper | `#f4f4f4` | `--color-card` | surface | Social quote cards and community review tiles. |
| Portrait gray | `#f0f0f0` | `--color-stone` | surface, background | Portrait cards, light supporting bands and inverse text variants. |
| Cool gray | `#8e8d92` | `--color-footer-muted` | text | Footer links and consent text. |
| Warm gray | `#696765` | `--color-muted` | text | Secondary descriptions and specifications. |
| Dark hairline | `#363636` | `--color-footer-rule` | border | Footer divider on black. |
| Soft black | `#151514` | `--color-headline` | text | Feature headings and technical labels. |
| Black | `#000000` | `--color-ink` | text, background, action | Primary text and dark actions; black proof chapters and footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product-detail and catalog closing scenes | Blue stage | `#1c3a63` | `--color-stage` | background | Studio closing product scene. |

## Typography

- **NeueMontreal** — All primary marketing headings, body and actions. Neutral contemporary grotesk with open counters; medium weight dominates headlines without becoming heavy. If unavailable, use **Inter**. Use 400 and 500; preserve the compact headline lines. Font stack: "NeueMontreal", "Inter", Arial, sans-serif.
- **IBM Plex Mono** — Technical eyebrows and equipment-like annotations. Small monospaced capitals with a functional, scientific tone. Font stack: "IBM Plex Mono", ui-monospace, monospace.
- **Oswald** — Ratings and instrument numerals. Tall condensed numerals sharply distinguish measured proof from prose. Font stack: "Oswald", sans-serif.
- **Bethany Elingston** — Large personal quotations in the proof carousel. Narrow expressive serif, contrasting with the technical grotesk. If unavailable, use **Instrument Serif**. Regular upright; keep quotations narrow and multiline. Font stack: "Bethany Elingston", "Instrument Serif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | NeueMontreal | 500 | 200px | 0.81 | -0.02em | fixed | Short centered launch name behind the main object. |
| closing-title | NeueMontreal | 500 | 72px | 74px | 0.01em | size clamp(40px, -5.5px + 7.5625vw, 72px), line height clamp(42px, -3.5px + 7.5625vw, 74px), tracking clamp(0.3px, -0.5px + 0.09375vw, 0.7px) | Large centered title in the lifestyle closing scene. |
| rating | Oswald | 400 | 54px | 1 | normal | fixed | Prominent condensed rating with stars and count. |
| heading | NeueMontreal | 500 | 44px | 1.1 | 0.01em | size clamp(32px, 15px + 2.84375vw, 44px), line height clamp(35.2px, 16.5px + 3.125vw, 48.4px), tracking clamp(0.4px, 0.5px + 0vw, 0.4px) | Default section headline and feature selector. |
| subheading | NeueMontreal | 500 | 28px | 1.1 | 0.01em | size clamp(24px, 18.5px + 0.9375vw, 28px), line height clamp(30px, 29px + 0.1875vw, 30.8px), tracking clamp(0.3px, 0.5px + 0vw, 0.3px) | Benefit titles and feature explanations. |
| hero-support | NeueMontreal | 500 | 24px | 1.25 | 0.0117em | fixed | Two-line opening support, kept narrower than the title. |
| media-heading | NeueMontreal | 500 | 22px | 1.09 | 0.008em | fixed | Titles within photographic cards. |
| quotation | Bethany Elingston | 400 | 22px | 1.455 | 0.008em | fixed | Personal quotation beside a portrait. |
| footer-heading | NeueMontreal | 400 | 20px | 1.2 | normal | fixed | Footer newsletter and column headings. |
| body | NeueMontreal | 400 | 18px | 1.333 | 0.01em | fixed | Primary supporting paragraph in feature chapters. |
| action | NeueMontreal | 500 | 18px | 1.4 | 0.2px | size clamp(16px, 13px + 0.46875vw, 18px), line height clamp(22.4px, 18.5px + 0.65625vw, 25.2px), tracking clamp(0.2px, 0px + 0vw, 0.2px) | Main action labels and compact card titles. |
| detail | NeueMontreal | 400 | 15px | 1.307 | 0.001em | fixed | Research captions, compact explanations and product descriptions. |
| eyebrow | IBM Plex Mono | 500 | 14px | 1.4 | normal, uppercase | fixed | Technical chapter marker above a headline. |
| navigation | NeueMontreal | 500 | 12px | 1.333 | 0.133em, uppercase | fixed | Navigation links and login. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| warm product-detail launch scenes | warm-launch | NeueMontreal | 500 | 120px | 0.81 | -0.02em | fixed | Longer introduction headline behind a vertically oriented object. |
| catalog and review-index openings | utility-title | NeueMontreal | 400 | 44px | 1.1 | 0.01em | size clamp(32px, 15px + 2.84375vw, 44px), line height clamp(35.2px, 16.5px + 3.125vw, 48.4px), tracking clamp(0.4px, 0.5px + 0vw, 0.4px) | Plain page title rather than an immersive product launch. |
| review filtering | filter | NeueMontreal | 500 | 16px | 1.2 | 0.02em | fixed | Compact review-category pills. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Only the monumental opening tightens tracking negatively. Normal section headings use slightly positive tracking and medium weight.
- Keep condensed numerals for rating or instrument roles; do not set ordinary headlines in Oswald.
- Headline text may be drawn into an animated scene; maintain the same visible grotesk hierarchy and semantic HTML fallback.

## Layout

**Density:** Airy at chapter scale, compact inside cards; broad imagery carries more area than text.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight card and inline grouping. |
| 16px | Media gutters and compact card insets. |
| 20px | Catalog card padding and grid gap. |
| 24px | Three-column feature grid gutters and research band padding. |
| 32px | Button horizontal padding, media overlay insets and support-to-action gap. |
| 40px | Feature text groups and glass stat-band padding. |
| 48px | Large internal group separations. |
| 64px | Desktop side gutters. |
| 80px | Feature-selector chapter vertical padding. |
| 112px | Major chapter vertical padding. |

### Containers and grids

- **marketing container**: max width 1440px · side padding 64px. Centered desktop chapter shell; 1312px usable content at a 1440px viewport.
- **benefit grid**: 3 columns · gap 24px. Equal photographic benefit columns with compact captions.
- **feature split**: 2 columns · gap 64px. 426px text rail beside a 640px square demonstration; vertical align by intent rather than equal text height.
- **footer container**: max width 1440px · side padding 75px. Newsletter at left and four link groups at right; wider black breathing room around the utility content.
- **catalog grid** (only for catalog pages): 3 columns · gap 20px. 424px product cards with aligned media, detail and action rows.
- **review masonry** (only for review-index pages): 4 columns · gap 32px. 300px columns of independently stacked social, editorial and portrait tiles.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 8px |
|  | feature photography | 24px |
|  | research grouping | 16px |
|  | glass and social cards | 20px |
| catalog pages | catalog cards | 8px |
| review-index pages | review filters | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| catalog pages | catalog lift | `0px 36px 72px -18px rgba(0,0,0,0.18)` | Broad soft lift behind white catalog cards. |
| review-index pages | review tile | `2px 2px 12px 0px rgba(0,0,0,0.05)` | Barely raised pale social cards. |

### Surfaces

#### Reading canvas · level 0

**Use:** Main reading chapters.

**CSS:** `background: #ffffff; color: #000000`

#### Pale research band · level 1

**Use:** Group photographic evidence without turning each benefit into a raised card.

**CSS:** `background: #f7f7f7; border-radius: 16px; padding: 24px 0px`

**Observed:** A single broad rounded band encloses three equal image-and-caption columns.

**Transfer:** Group related outcomes in one shared surface.

#### Midnight atmosphere · level 0

**Use:** Process demonstrations.

**CSS:** `background: #031938; color: #ffffff`

**Observed:** Low-contrast blue atmospheric image sits beneath floating translucent cards.

**Transfer:** Use a dark blue environment to make small pieces of measured behavior glow.

#### Proof horizon · level 0

**Use:** Review collage chapter.

**CSS:** `background: linear-gradient(#000000, #1b315f); color: #ffffff`

**Observed:** White quote cards overlap the lower part of a black-to-blue field.

**Transfer:** Keep the horizon subdued so portraits and quotation remain the brightest objects.

#### Instrument glass · level 2

**Use:** Data panel within product demonstrations.

**CSS:** `background: rgba(34,38,45,0.75); border-radius: 9.9px; backdrop-filter: blur(31.8px); box-shadow: 0px 55.2px 110.4px -20.7px rgba(0,0,0,0.4)`

**Observed:** Thin colored edge, subtle blue illumination and white condensed numerals; a larger 20px translucent card groups it with explanatory text.

**Transfer:** Represent one real state, measurement or adjustment rather than an entire application.

#### Black utility ground · level 0

**Use:** Footer and authority chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Footer uses gray links; authority cards contrast as pale portrait rectangles.

**Transfer:** Use black as a substantial chapter, not just a narrow bottom bar.

## Components

### Primary button

**Use:** Main conversion over photography or atmospheric scenes.

**CSS:** `background: #ffffff; color: #000000; border-radius: 8px; padding: 16px 32px; height: 57px; display: grid; align-items: center`

**Text style:** `action` — NeueMontreal 500 · 18px/1.4 · tracking 0.2px

**Observed:** Centered short label, usually without an icon; dark companion reverses foreground and background on white chapters. Catalog buttons span the card width and use 4px corners.

**Transfer:** Choose white on dark media and black on light reading surfaces.

### Navigation

**Use:** Persistent site-level orientation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 0px 32px; height: 70px`

**Text style:** `navigation` — NeueMontreal 500 · 12px/1.333 · tracking 0.133em · uppercase

**Observed:** Three links at left, centered compact brand mark, login, region, cart and black shop action at right. A 42px deep-blue promotional strip sits above it initially; the hero version floats as translucent glass and the scrolled version becomes a full-width white bar.

**States:** Declared: hover navigation-link opacity 0.6; text-decoration none.

**Transfer:** Keep the logo centered independently of unequal side groups.

### Feature selector

**Use:** Introduce a small set of improvements beside a product demonstration.

**CSS:** `font-size: 44px; line-height: 48.4px; letter-spacing: 0.4px; color: #151514; text-align: left`

**Text style:** `heading` — NeueMontreal 500 · 44px/1.1 · tracking 0.01em

**Observed:** Stacked text-only selectors; active promise is black, inactive promises fade to about 0.16 opacity. A mono eyebrow precedes the stack, with a secondary title, paragraph and wide dark action below it.

**Transfer:** Use a short comparative phrase for each selectable benefit.

### Photographic feature card

**Use:** Explain the parts of a system.

**CSS:** `position: relative; overflow: hidden; border-radius: 24px; padding: 32px; color: #ffffff`

**Text style:** `media-heading` — NeueMontreal 500 · 22px/1.09 · tracking 0.008em

**Observed:** Full-bleed warm domestic photograph, bottom gradient, small translucent part label at top left and title at bottom left; expanded card adds a support sentence and close control.

**Transfer:** Use one large primary system tile beside smaller supporting tiles.

### Newsletter line input

**Use:** Footer subscription.

**CSS:** `display: grid; grid-template-columns: 1fr 24px; padding-bottom: 4px; box-shadow: 0px 1px 0px 0px #ffffff; max-width: 272px`

**Observed:** A bare transparent field and rightward submit arrow, with small consent copy beneath; no filled input box.

**Transfer:** Keep signup subordinate to the main conversion.

### Footer columns

**Use:** Final utility destination.

**CSS:** `background: #000000; color: #ffffff; padding: 90px 75px; max-width: 1440px`

**Text style:** `footer-heading` — NeueMontreal 400 · 20px/1.2

**Observed:** Small brand mark at upper left; region and payment marks at upper right. Newsletter then four link columns, social icons at lower right, a dark hairline, copyright and compact disclosures below. Link tone is cool gray, not white.

**Transfer:** Retain the substantial vertical black ending with distinct functional layers.

### Catalog card

**Only for:** catalog pages

**Use:** Repeated purchasable product summary.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 20px; display: grid; row-gap: 14px; box-shadow: 0px 36px 72px -18px rgba(0,0,0,0.18)`

**Text style:** `action` — NeueMontreal 500 · 18px/1.4 · tracking 0.2px

**Observed:** Neutral studio image first, then title with small compatibility tag, compact description, price and full-width black action. Media measures 384px by 273px inside a 424px-wide card.

**Transfer:** Align action rows across products even when descriptions differ.

### Review tile

**Only for:** review-index pages

**Use:** Mixed social proof in masonry columns.

**CSS:** `background: #f4f4f4; border-radius: 20px; padding: 16px; box-shadow: 2px 2px 12px 0px rgba(0,0,0,0.05)`

**Text style:** `detail` — NeueMontreal 400 · 15px/1.307 · tracking 0.001em

**Observed:** Social version has avatar, name, handle, platform mark, quote, optional image and date. Review version begins with stars and a small source tag. Tall video portraits instead use an edge-to-edge photograph with white play symbol and bottom caption.

**Transfer:** Mix authentic formats and heights; do not force every story into a uniform testimonial template.

### Review filter

**Only for:** review-index pages

**Use:** Filter categories above proof masonry.

**CSS:** `background: #000000; color: #ffffff; border-radius: 51px; padding: 12px 24px; height: 43px; display: flex`

**Text style:** `filter` — NeueMontreal 500 · 16px/1.2 · tracking 0.02em

**Observed:** Selected pill is black; inactive pills use a pale warm fill. Centered in a single horizontal row above the wall.

**States:** Declared: hover background-color #000000; color #ffffff.

**Transfer:** Use short categories; preserve horizontal scrolling when needed.

### Glass stat band

**Only for:** product-detail and catalog closing scenes

**Use:** Quantified improvements beneath a studio closing product scene.

**CSS:** `background: rgba(255,255,255,0.3); border-radius: 16px; backdrop-filter: blur(20px); padding: 40px; display: flex; gap: 20px`

**Text style:** `heading` — NeueMontreal 500 · 44px/1.1 · tracking 0.01em

**Observed:** Three columns pair large 44px figures with bold short descriptors and 14px explanatory copy; subtle vertical separators distinguish columns.

**Transfer:** Use comparable, substantiated improvements, not three unrelated vanity metrics.

## Imagery and graphics

### Sky product sculpture

**Use:** Required opening product stage and selected return-to-product moments.

**Observed:** Dark ribbed hardware floats at a three-quarter angle over a blue sky with soft cloud wisps; it overlaps the lower edge of the giant title. Lighting draws silver highlights across charcoal surfaces; the object occupies roughly the central third of the screen width.

**Transfer:** Use a large isolated render or carefully masked product photograph with directional edge light. For a nonphysical product, stage one meaningful interface or visual artifact as the same single sculptural object.

**Build:** Create a full-width blue atmospheric backing with a lighter lower horizon. Layer several very broad white radial gradients at low alpha with 60px–100px blur; place a transparent object above them and the title behind it. Preserve soft atmospheric transitions rather than a hard two-color split.

### Warm lived-in photography

**Use:** Feature stories, benefits and lifestyle closing scene.

**Observed:** Architectural bedrooms with timber, stone, cream bedding, teal upholstery and window greenery; people are relaxed and naturally framed. Daylight is warm and directional, nighttime blue stays low-key. Rounded images consume half to two-thirds of most feature rows.

**Transfer:** Photograph the new product in a credible daily environment, using tactile natural materials and believable human use. Match lighting between product and room rather than pasting a cutout onto stock scenery.

### Orbital process and illuminated instruments

**Use:** Required signature device for explaining invisible behavior.

**Observed:** A thin gently curved timeline links tiny nodes and time labels above warm scene photography, short text and floating data glass. Other chapters condense the same idea into a center-active carousel on midnight blue. Blue and warm red light indicate distinct zones on product surfaces.

**Transfer:** Map a real workflow or state change to a restrained timeline and one luminous measurement. Minimum version is an SVG curve, a single authentic scene and one legible stat panel.

**Build:** Draw a 1px SVG cubic path spanning beyond the viewport with a shallow downward arc; add small circular nodes and one larger translucent halo. Place a 218px by 173px ellipse of instrument blue at 0.5 opacity, blur 39px, behind the upper-left edge of Instrument glass. Add a 1px masked gradient rim shifting blue to warm orange with low alpha; retain a dark central panel.

### Human proof collage

**Use:** Authority cards and testimonial carousel.

**Observed:** Large monochrome expert portraits on pale gray cards contrast with candid color member photos and short serif quotations. Social posts appear as smaller pale cards, while tall performers' portraits receive a black bottom fade and small white captions.

**Transfer:** Use your own real expert, user and practitioner material with distinct editorial formats; retain the contrast between formal authority and everyday testimony.

### Studio catalog still life

**Only for:** catalog and ecosystem sections

**Use:** Product cards and add-on family grid.

**Observed:** Charcoal products and folded textiles sit on warm gray-beige floor planes, often in the corner of a softly lit room. Similar camera angle, contact shadow and rectangular framing make unrelated products read as a family.

**Transfer:** Keep the floor, camera and light consistent across a catalog; show scale and material rather than decorative props.

### Warm launch atmosphere

**Only for:** warm product-detail launches

**Use:** Alternate immersive opening and warm review chapter.

**Observed:** A peach-gold cloudy sky sits behind a large black title and upright dark object. Review proof returns to the same golden atmosphere before transitioning to white specifications.

**Transfer:** Reserve this warmer environmental variant for an extended product narrative, not for every ordinary section.

**Build:** Layer broad peach and amber radial gradients over a muted tan field, blur their boundaries heavily, and keep a brighter low horizon. Add a subtle directional veil so black title and dark object retain separation.

### Icons

**Observed:** Small monochrome SVG marks, 16px inline and 24px in controls; larger white play triangles on portraits. Circular carousel controls use fine outlines at 40px or 56px, separate from rectangular conversion buttons.

**Transfer:** Use simple functional silhouettes and fine outlined arrows. Keep reassurance icons minimal and black on pale surfaces; avoid colorful icon badges.

## Section recipes

How recurring sections are built.

### First screen: Floating product opening

**Observed:** A full-width atmospheric blue sky fills a section 1117px tall. Initial chrome has a 42px promotional strip and a roughly 70px floating translucent Navigation. Behind the dark three-quarter product sculpture sits a centered white gradient-clipped display title, 200px/0.81 with -0.02em tracking, its edges fading toward transparency. The object overlaps the title and fills the central vertical span; below it sits a centered two-line hero-support block about 344px wide, then Primary button with a 32px gap. Within the first 900px the title, complete object, support and white action are all visible; rating and review count follow below the fold.

**Transfer:** Make one object the visual protagonist, even if it is a lit cutout or carefully composed interface artifact. Keep text short enough for the title to remain sculptural. Catalogs instead open with a plain left-aligned utility-title and immediate product grid; review indexes use a centered utility-title, condensed rating, stars and Review filter. Extended product-detail launches can use warm-launch over a golden sky with support and action below the first screen.

**Avoid:** Do not turn the first screen into a conventional left-copy/right-image split, add a feature-card dashboard around the object, or place a paragraph over the title.

**Text style:** `display` — NeueMontreal 500 · 200px/0.81 · tracking -0.02em

### Chapter heading pair

**Observed:** A small mono uppercase eyebrow introduces a medium 44px heading and a compact support paragraph. Centered versions precede proof and benefit grids; left-aligned versions introduce technical sections. Major sections use 112px vertical padding and 64px side gutters.

**Transfer:** Name the benefit or narrative chapter rather than repeating a product category.

**Text style:** `heading` — NeueMontreal 500 · 44px/1.1 · tracking 0.01em

### System anatomy cards

**Observed:** Photographic feature card repeats in a 1312px row with 16px gaps; the active card expands while two narrower tiles remain visible. The product-detail variant places an 872px main tile beside two 432px-wide stacked tiles. One centered dark action closes the group.

**Transfer:** Explain a system as primary artifact plus enabling parts, keeping captions inside the photographs.

### Alternating use-case chapter

**Observed:** A large rounded lifestyle scene alternates sides with a narrow centered text block, short benefit line and underlined text link. Instrument glass overlays the scene to explain behavior without removing the domestic context.

**Transfer:** Select a few distinct situations in which the product matters; alternate visual weight without repeating the same stock layout mechanically.

### Research proof grid

**Observed:** Centered chapter heading and support lead into Pale research band with three photographic columns, 28px benefit titles and 15px quantified captions. A second row of darker 421px by 167px study links uses 24px gutters.

**Transfer:** Pair each supported outcome with a recognizable human context and link to the supporting detail.

### Authority and living proof

**Observed:** Black utility ground hosts two 640px by 560px pale portrait cards. Proof horizon then carries a centered condensed rating, stars and large two-line statement above a horizontally overflowing mix of white portrait-and-serif-quote cards and smaller social cards. A faint orbital line ties the upper composition together.

**Transfer:** Separate formal authority from real experience while using the same atmosphere and visual rhythm.

### Scene-led closing and reassurance

**Observed:** A full-width 899px warm architectural photograph carries centered closing-title, one short benefit, bold starting price and Primary button near the top. The catalog and product-detail variant uses a 1102px blue studio product stage and Glass stat band below the main object. A white reassurance chapter follows with three pale icon-and-copy tiles and a centered 570px-wide shipping statement, then Footer columns.

**Transfer:** Return to one large desirable product scene after the proof. Adapt assurance subjects to the offer and keep them visually lighter than the conversion.

### Immersive process chapter

**Only for:** extended product-detail narratives

**Observed:** A long blue-to-night-to-dawn scene places an orbital timeline above a three-part composition: warm product photograph at left, brief stage explanation in the middle, floating instruments at right. A compact center-active carousel is the shorter marketing variant.

**Transfer:** Tell the sequence of actual product behavior. Use the compact variant when the process does not justify a long immersive story.

### Technical comparison

**Only for:** product-detail pages

**Observed:** A 44px headline precedes a ruled comparison table with product pictures above the columns; the current product column receives a blue backdrop. A compact four-column metric list follows. Warm-white rounded specification panels contain white subpanels and 1px warm-gray rules.

**Transfer:** Make comparison and specifications genuinely scannable; separate factual rows from narrative benefits.

### Review library

**Only for:** review-index pages

**Observed:** Centered utility-title, rating and filter row introduce four masonry columns. Review tile alternates with vertical edge-to-edge video portraits and occasional press imagery. After the long wall the page ends directly in Footer columns rather than another product-stage conversion.

**Transfer:** Let authentic content determine card height and mix; paginate or load more without imitating an unnecessarily long wall.

## Page flow

**Storyline:** Product promise → tangible system explanation → personally relevant capabilities → measured and human proof → return to the product → reassurance and utility.

### Broad product marketing landing page

1. **Promise** — Sky-stage object with monumental product name and one conversion.
2. **Product demonstration** — Expandable system cards and improvement selector beside close-up media.
3. **Capability chapters** — Alternating lifestyle use cases followed by an atmospheric instrument carousel.
4. **Quantified and human proof** — Research outcomes, authority portraits, mixed member collage and practitioner portraits.
5. **Closing call** — Large lifestyle conversion scene, reassurance tiles, shipping details and black footer.

**Transfer:** Use this as the default density and chapter vocabulary, adapting the order to the argument.

### Extended product-detail narrative

1. **Promise** — Warm launch sky, large title and upright object.
2. **Product demonstration** — Film, highlight rail, anatomy cards and immersive use-case scenes.
3. **Range and customization** — Size imagery, hotspot exploration and ecosystem grid.
4. **Process explanation** — Long day-to-night orbital sequence and data carousel.
5. **Objection handling** — Research, comparison, review proof and technical specifications.
6. **Closing call** — Blue studio stage with stat band, assurance and shared black footer.

**Transfer:** Use the immersive duration only for a product whose behavior needs explanation; keep facts close to the later decision stage.

### Product catalog

1. **Orientation** — Plain page title directly above three-column product grid.
2. **Selection** — Consistent studio thumbnails, descriptions, price and full-width actions.
3. **Closing call** — Flagship blue product stage and quantified band.
4. **Reassurance and utility** — Three assurance tiles, shipping note and black footer.

**Transfer:** Lead with purchase-ready content; keep cinematic storytelling in the closing cross-sell rather than before the grid.

### Social proof library

1. **Social proof promise** — Centered title, condensed aggregate rating and category pills.
2. **Evidence browsing** — Four-column masonry mixing posts, reviews, videos and press.
3. **Utility ending** — Shared black newsletter and link footer immediately after the wall.

**Transfer:** Preserve the credible mixture of content formats, not the sheer number of repeated posts.

## Writing

Confident consumer technology with the warmth of a personal coach. Benefits are plain and specific; engineering is explained through what it does for the reader rather than abstract innovation language.

**Do not copy:** Do not reuse Eight Sleep or Pod names, logos, branded artwork, quoted testimonials, awards, review totals, clinical results, prices or performance claims. Replace them with the new product's own substantiated content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your; use the product name as a clear active subject. Use we sparingly for research, shipping and support.
- **Rhythm:** Short sentence-case headlines, often 3–8 words. Support usually fits one or two compact sentences; parallel benefit phrases make comparisons easy. Promotional chrome can use capitals; editorial headings do not.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Launch title | Short name or introduction, leaving the scene to explain desirability. | 2–4 words | “Pod 6”<br>“Introducing Pod 6” |
| Benefit headline | A concrete improvement, often comparative or personally relevant. | 3–8 words | “Smaller than ever”<br>“One sleep system.”<br>“More ways to make it yours.” |
| Supporting explanation | Explain the mechanism through a practical consequence. | One or two sentences | “Smaller, but mightier. Just one Hub still powers both sleepers’ nights on the Pod.” |
| Proof caption | Quantified outcome plus a clear qualifier. | 5–10 words | “Up to 44% less time to fall asleep” |
| Action | Direct verb plus specific destination or object. | 2–5 words | “See how it works”<br>“Book a virtual visit”<br>“Read more reviews” |

**Words and phrasing to use:** personalized; fits; responds; tracks; adjusts; built for; starting at; smaller; more powerful; your

**Avoid:** revolutionary ecosystem; unparalleled excellence; unlock limitless potential; hustle harder; miracle; guaranteed transformation

**Rules:**

- Make each technical detail answer an everyday concern.
- Use comparable grammar across a feature selector or benefit grid.
- Place qualifiers and supporting links near measured claims.
- Keep human quotations in their own voice rather than rewriting them as marketing headlines.

## Do's and Don'ts

### Do

- Keep ordinary chapter headlines at 44px/1.1 and weight 500.
- Use 64px desktop side gutters for a 1312px usable chapter width.
- Keep main conversion buttons 57px tall with 8px corners.
- Use 24px gutters for three-column benefit grids and 16px for anatomy media tiles.
- Pair dark engineering imagery with tactile daylight interiors.
- Make a real process visible through a fine orbital line and one luminous instrument.
- Keep footer navigation in cool gray on black and separate disclosures with a dark hairline.
- Use condensed 54px numerals for prominent ratings, distinct from body typography.

### Don't

- Do not replace all light reading chapters with dark blue; atmosphere belongs to selected immersive chapters.
- Do not use saturated blue as the default shop-button fill.
- Do not make conversion buttons pill-shaped just because filters and carousel arrows are round.
- Do not set normal headings in the condensed numeral font.
- Do not apply catalog drop shadows to every photographic feature tile.
- Do not make all portraits monochrome; the formal authority pair and candid member stories have different treatments.
- Do not turn compact specification rows into oversized promotional cards.
- Do not use dense paragraphs where a 15px caption and a clear photograph can carry the explanation.

## Motion and responsive

### Motion

**Observed:**

- Button transitions declare 0.2s ease-out; navigation opacity also declares 0.2s ease-out.
- Review tile shadows declare 0.25s ease-in-out.
- The opening title declares a 2.013s ease-in-out animation; product imagery and title use separate layered transforms.
- Carousel controls, dot pagination, expandable cards and horizontally overflowing proof strips are present.

**Transfer:**

- Keep the product sculpture and title on separate layers for restrained opening movement.
- Let selection alter the active card or demonstrated state rather than animating every text block.

**Unknown:**

- Exact video playback behavior, scroll timing and complete keyframe transforms are unspecified.

### Responsive

**Observed:**

- Desktop compositions use 64px side padding; utility chapter classes declare 20px narrow-screen side padding.
- Catalog layout declares auto-fill columns with minmax(min(424px, 100%), 1fr).
- Fluid heading and subheading formulas are included in their type recipes.

**Transfer:**

- On narrow screens retain the sky/object/title overlap but shorten copy and size the object so the action remains reachable.
- Stack benefit columns and system cards while retaining the image-first hierarchy.
- Keep review filters horizontally scrollable and reduce masonry columns without flattening all card heights.

**Unknown:**

- Mobile layouts and exact breakpoint-specific hero composition are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
