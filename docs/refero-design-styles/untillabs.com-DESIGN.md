# Until Labs — science with soft edges

## Overview

A cinematic, human-facing scientific style pairs warm cream editorial space with lush green imagery, tactile glass and softly rendered technical objects. Tightly set neo-grotesk headlines and small monospaced annotations make complex work feel tangible rather than clinical. Sparse text sits beside oversized imagery; olive, sky blue and burnt orange create distinct chapter moods within a predominantly light experience.

### Essentials

- The opening is a scene, not a sales panel: full-bleed imagery fills a 900px desktop screen, with a 69.4px medium grotesk line anchored near the bottom and a small scroll invitation beneath it.
- Headlines compress without becoming heavy: display weight 500, 0.95 line height and -0.03em tracking at 56px; body copy remains 16px/24px at weight 400.
- Navigation floats like a glass instrument: a 54px-high translucent bar sits 16px below the top, compressing to a 432px logo-and-action capsule as the story advances.
- Color lives in the scene and in deliberate chapter fields: cream #f7f3ec dominates the editorial canvas, olive #6c853b carries expressive text, and black #121212 grounds 36px-high, 18px-radius buttons. Blue and orange full-field treatments belong to specialist page variants, not every section.
- Imagery shifts between human and microscopic scales: include an atmospheric human scene and an isolated technical object on cream; when no physical product exists, use a carefully lit process model or material study rather than a generic dashboard.
- Conversation becomes a physical word sculpture: include stacked white 64px-radius text capsules, slight alternating rotations, connecting round blobs and an underlined final action, with 56px olive display text.
- Dense proof stays tactile and contained: editorial cards use 32px outer corners, 24px inner corners, 8px inset framing and subtle inset highlights instead of flat outlined tiles.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Living olive | `#6c853b` | `--color-olive` | text, accent, background | Expressive closing text and human-facing accents; full-field recruitment atmosphere. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sculptural white | `#ffffff` | `--color-white` | surface, background | Contact capsules and footer navigation band. White at 10% provides glass fill and edge highlights, not an opaque white navigation panel. |
| Warm cream | `#f7f3ec` | `--color-canvas` | background, text, surface | Default editorial canvas, light text over imagery, and cream card framing. |
| Light grey | `#bebebe` | `--color-rule` | border, text | Small footer group labels and listing hairlines; at 30% in button radial highlights. |
| Off black | `#121212` | `--color-ink` | text, action, background | Default body and heading ink; primary action fill. |
| True black | `#000000` | `--color-black` | text, background | Footer links; deep contrast field for advanced technical chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| recruitment content | Deep forest | `#293423` | `--color-forest` | background, text | Benefits field and related mission text. |
| people and culture pages | Sky blue | `#5880bd` | `--color-blue` | background, text, link | Atmospheric opening, values field, footer links and final strip. |
| people and culture pages | Pale sky glow | `#abc1e3` | `--color-blue-glow` | accent | Soft light behind connected glass cards. |
| technical storytelling | Burnt orange | `#cb350f` | `--color-orange` | background, accent | Immersive technical opening and feather-edged assessment chapter; also selection background. |

## Typography

- **neueHaasDisplay** — Headlines, editorial card titles, footer links and sculptural call to action. Neo-grotesk display face with compact spacing, broad lowercase forms and a firm medium cut. If unavailable, use **Inter**. Use weight 500 and retain close tracking; tune line breaks to preserve compact silhouettes. Font stack: "neueHaasDisplay", "Inter", Arial, Helvetica, sans-serif.
- **neueHaasText** — Body copy, action labels and larger benefit statements. Workmanlike neo-grotesk with readable small-size spacing and unshowy regular text. If unavailable, use **Inter**. Use 400 for paragraphs and 500 for actions. Font stack: "neueHaasText", "Inter", Arial, Helvetica, sans-serif.
- **Geist Mono** — Dates, tiny group labels and parenthesized chapter annotations. Modern monospaced lettering introduces a restrained laboratory notation. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| opening-line | neueHaasDisplay | 500 | 69.4px | 0.95 | -0.03em | Single sentence fragment set across the lower edge of a cinematic opening. |
| heading | neueHaasDisplay | 500 | 56px | 0.95 | -0.03em | Primary editorial section title and sculptural closing text. |
| statement | neueHaasDisplay | 500 | 56px | 0.9 | -0.0114em | Centered multi-line statement with a compact block silhouette. |
| feature-heading | neueHaasDisplay | 500 | 38.7px | 1 | -0.031em | Compact heading alongside a large product object or within a photographic montage. |
| principle | neueHaasDisplay | 500 | 32px | 1.1 | -0.02em | Centered principle or premise above a larger statement. |
| footer-link | neueHaasDisplay | 500 | 32px | 1 | -0.025em | Large stacked directory links. |
| card-title | neueHaasDisplay | 500 | 24px | 1 | -0.01em | Editorial card titles above short summaries. |
| body | neueHaasText | 400 | 16px | 1.5 | normal | Explanatory paragraphs and editorial card support. |
| button | neueHaasText | 500 | 16px | 1 | normal | Compact pill action labels. |
| date | Geist Mono | 400 | 14px | 1 | normal | Editorial dates. |
| group-label | Geist Mono | 500 | 12px | 1.4 | 0.05em, uppercase | Muted footer group labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| recruitment, people and technical overview pages | chapter-display | neueHaasDisplay | 500 | 132.2px | 0.9 | -0.03em | Bottom-weighted title over an atmospheric full-screen field. |
| technical explainers | technical-heading | neueHaasDisplay | 500 | 38.7px | 1.1 | -0.02em | Named capability or process chapter. |
| technical explainers and listings | subheading | neueHaasDisplay | 500 | 24px | 1.25 | -0.01em | Short mechanism claim below a chapter heading; also listing titles. |
| benefits and values sections | benefit-text | neueHaasText | 500 | 24px | 1.25 | -0.01em | One concise statement inside a connected glass card. |
| recruitment, people and technical overview pages | chapter-note | Geist Mono | 500 | 16px | 1.5 | normal | Small centered parenthesized sentence halfway down the opening. |
| benefits and values sections | benefit-label | Geist Mono | 400 | 16px | 1 | -0.01em, uppercase | Half-opacity label beside a small icon above the card statement. |

**Notes:**

- Use medium weight as the visual ceiling for display copy; scale and tight spacing create authority, not bold weight.
- Keep display tracking distinct from body: the 56px heading uses -0.03em while paragraphs use normal tracking. The centered statement deliberately uses looser -0.6px tracking.
- Balance line breaks into compact phrases. Full-screen specialist titles stretch widely across the bottom; ordinary editorial headings stay short and sit beside the visual.

## Layout

**Density:** Airy between chapters, compact within text and cards; object-led scenes occupy whole screens while supporting copy stays closely grouped.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card text stacks, icon-label separation and inset frames. |
| 12px | Heading-to-support gap in object-led features; footer link stack. |
| 16px | Paragraph rhythm and container inner side padding. |
| 24px | Portrait grid gaps and modest content stacks. |
| 32px | Glass-card inner padding and conversion-action separation. |
| 40px | Wide editorial side gutters and separation of listing categories. |
| 48px | Marquee card separation, statement pair gap and footer top padding. |
| 96px | Major editorial section padding. |
| 128px | Recruitment chapter padding. |
| 208px | Long-form technical chapter breathing room. |

### Containers and grids

- **Main container**: max width 1296px · side padding 16px. Centered desktop content shell, leaving 72px outer margins at a 1440px viewport before inner padding.
- **Reading container**: max width 1080px · side padding 16px. Narrow editorial shell; centered statement and connected-card content occupy 888px within it at desktop.
- **Object and explanation**: 12 columns · gap 16px. An isolated object occupies one side; explanation uses roughly five columns on the other with an open middle gutter. Reverse the sides across chapters.
- **Footer directory**: 4 columns · gap 32px. Equal company, knowledge, people and contact groups in the main container.
- **Portrait wall** (only for people directories): 4 columns · gap 24px. Square portraits with consistent framing rather than individual resume cards.
- **Connected proof grid** (only for benefits and values sections): 2 columns · gap 18px. 435px-wide cards joined by soft necks; rows remain closely grouped within an 888px field.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Actions | 18px |
|  | Framed cards | 32px |
|  | Inner media | 24px |
|  | Contact capsules | 64px |
|  | Compact navigation | 24px |
|  | Expanded navigation | 50px |
| recruitment listings | Listing panel | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Tactile edge | `inset 0 -1px 2px rgba(255,255,255,0.1), inset 0 1px 2px rgba(255,255,255,0.1), 0 0 2px rgba(0,0,0,0.1), 0 3px 17px rgba(0,0,0,0.05)` | Editorial cards and compact primary actions. |
| Navigation glass | `0 7.5px 30px rgba(0,0,0,0.043), inset 0 1px 1px rgba(255,255,255,0.3)` | Floating navigation capsule. |

### Surfaces

#### Cream canvas · level 0

**Use:** Default surface for marketing explanations and product stages.

**CSS:** `background: #f7f3ec; color: #121212`

**Observed:** Continuous paper-like cream supports unboxed text and technical objects.

**Transfer:** Keep most editorial content on this surface, reserving pure white for distinct objects and the footer.

#### Fine grain · level 2

**Use:** Subtle unifying texture over scenes and fields.

**CSS:** `opacity: 0.2; mix-blend-mode: overlay; pointer-events: none`

**Observed:** A fine noise layer takes the digital edge off photography, blur and rendered materials.

**Transfer:** Use a monochrome SVG turbulence texture across the page; grain must remain subordinate to text.

#### Cream veil · level 1

**Use:** Transition from the immersive scene to a statement.

**CSS:** `background: rgba(247,243,236,0.9); backdrop-filter: blur(4px); padding: 96px 0`

**Observed:** The previous image remains faintly visible through a pale full-screen veil.

**Transfer:** Place the principle and statement pair above a softened remnant of the opening image.

#### Sculptural white · level 1

**Use:** Conversational closing forms.

**CSS:** `background: #ffffff; border-radius: 64px`

**Observed:** Solid white rounded word supports sit above cream, joined by rounded bridges and detached circles.

**Transfer:** Use distinct raised white shapes rather than a white rectangular CTA panel.

#### Forest field · level 0

**Only for:** recruitment benefits

**Use:** High-contrast field behind a connected card system.

**CSS:** `background: #293423; color: #f7f3ec; padding: 128px 0`

**Observed:** Dark green field with a soft olive glow behind translucent cards.

**Transfer:** Maintain a dark organic hue and cream lettering.

#### Connected glass · level 1

**Only for:** benefits and values sections

**Use:** Small statements on colored fields.

**CSS:** `background: radial-gradient(100% 100% at 50% 100%, rgba(247,243,236,0.2) 0%, rgba(247,243,236,0) 100%), rgba(247,243,236,0.05); border-radius: 32px; padding: 32px; box-shadow: inset 0 0.9px 1.8px rgba(255,255,255,0.1), inset 0 -0.9px 1.8px rgba(255,255,255,0.1), 0 2.7px 15.1px rgba(0,0,0,0.05), 0 0 1.8px rgba(0,0,0,0.1)`

**Observed:** Faint luminous edge, milky bottom illumination and soft connector necks make several cards feel like one material.

**Transfer:** Keep the translucency dependent on the underlying field. Do not replace it with opaque pastel cards.

#### Listing glass panel · level 1

**Only for:** recruitment listings

**Use:** A single contained directory of opportunities.

**CSS:** `background: radial-gradient(50% 100% at 50% 100%, rgba(255,255,255,0.5) 0%, rgba(255,255,255,0) 100%), rgba(247,243,236,0.9); border-radius: 24px; padding: 64px 48px; backdrop-filter: blur(25px)`

**Observed:** A softly raised cream panel contains the entire filter-and-row system, not one card per item.

**Transfer:** Group related rows in one substantial panel.

#### Black technical field · level 0

**Only for:** advanced technical chapters

**Use:** A dramatic shift for future-facing or research-heavy material.

**CSS:** `background: #000000; color: #f7f3ec`

**Observed:** Cream text and luminous scientific media sit on a deep black field.

**Transfer:** Keep this a deliberate chapter change, not the default page theme.

## Components

### Floating navigation

**Use:** Persistent orientation and one short conversion action.

**CSS:** `position: fixed; top: 16px; width: 432px; height: 54px; display: flex; align-items: center; justify-content: space-between; padding: 8px 10px 8px 12px; background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.1); border-radius: 24px; backdrop-filter: blur(25.5px) brightness(1.04) contrast(1.075); box-shadow: 0 7.5px 30px rgba(0,0,0,0.043), inset 0 1px 1px rgba(255,255,255,0.3)`

**Text style:** `button` — neueHaasText 500 · 16px/1

**Observed:** Centered over all content. The opening state expands across the main shell with a wordmark, horizontal destination links and a light action; the scrolling state reduces to a symbol on the left and a dark action on the right. Other page types use a 50px capsule radius.

**Transfer:** Use the new product's own compact symbol and keep the reduced state sparse.

### Primary button

**Use:** Main action within editorial content.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 0 32px; border-radius: 18px; background: radial-gradient(50% 100% at 50% 100%, rgba(190,190,190,0.3) 0%, rgba(190,190,190,0) 100%), #121212; color: #f7f3ec; box-shadow: inset 0 -1px 2px rgba(255,255,255,0.1), inset 0 1px 2px rgba(255,255,255,0.1), 0 0 2px rgba(0,0,0,0.1), 0 3px 17px rgba(0,0,0,0.05)`

**Text style:** `button` — neueHaasText 500 · 16px/1

**Observed:** A compact tactile pill without an arrow. Light cream inverse actions appear on blue and black fields; recruitment row actions use deep olive with an olive radial highlight.

**Transfer:** Use a short direct verb phrase and one action per content block.

### Editorial card

**Use:** Article or insight summaries in a horizontally moving collection.

**CSS:** `width: 450px; height: 290px; background: #f7f3ec; border-radius: 32px; overflow: hidden; box-shadow: inset 0 -1px 2px rgba(255,255,255,0.1), inset 0 1px 2px rgba(255,255,255,0.1), 0 0 2px rgba(0,0,0,0.1), 0 3px 17px rgba(0,0,0,0.05)`

**Text style:** `card-title` — neueHaasDisplay 500 · 24px/1 · tracking -0.01em

**Observed:** An 8px inset frame holds an inner 24px-radius composition. Date, title and summary occupy the left two thirds; a tall abstract image occupies the right third. Author and a tiny avatar sit at the bottom of the text area.

**Transfer:** Keep editorial metadata, not feature icons or numerical badges, as the organizing information.

### Contact capsule

**Use:** One line of the sculptural conversation invitation.

**CSS:** `background: #ffffff; border-radius: 64px; color: #6c853b; display: flex; align-items: center; justify-content: center; transform: rotate(-2.52deg)`

**Text style:** `heading` — neueHaasDisplay 500 · 56px/0.95 · tracking -0.03em

**Observed:** Multiple capsules alternate slight angles and widths, connect through white circular blobs and end in an underlined contact line. The technical variant uses black lettering instead of olive.

**Transfer:** Let capsule widths follow the new message while keeping a compact stacked silhouette.

### Footer directory link

**Use:** Clear navigation in the final white band.

**CSS:** `color: #000000; display: block; width: fit-content`

**Text style:** `footer-link` — neueHaasDisplay 500 · 32px/1 · tracking -0.025em

**Observed:** Large links stack under tiny grey uppercase mono group labels with a 12px vertical gap. Recruitment uses olive links; people pages use blue.

**States:** Declared: hover color color-mix(currentcolor, transparent); focus-visible outline-style none and zero box-shadow.

**Transfer:** Group the new destinations by reader intent, keeping the contact address prominent.

### Footer assembly

**Use:** Final directory and small identity strip.

**CSS:** `background: #ffffff; padding: 48px 0 0; overflow-x: hidden`

**Observed:** Four directory columns sit above an 87px strip. The strip places a small stacked identity left and rights text plus three social marks right. Default strip is cream with black details; recruitment and people variants use olive or blue with cream details.

**Transfer:** Preserve the split between a spacious directory and compact identity strip, including when a page ends without the contact sculpture.

### Connected proof card

**Only for:** benefits and values sections

**Use:** A small titled benefit or operating principle.

**CSS:** `display: flex; flex-direction: column; gap: 8px; padding: 32px; border-radius: 32px; background: radial-gradient(100% 100% at 50% 100%, rgba(247,243,236,0.2) 0%, rgba(247,243,236,0) 100%), rgba(247,243,236,0.05); color: #f7f3ec`

**Text style:** `benefit-text` — neueHaasText 500 · 24px/1.25 · tracking -0.01em

**Observed:** A faint icon and half-opacity uppercase mono label precede the larger sentence. Cards join via soft translucent necks across selected row and column gaps; blue and forest fields share the construction.

**Transfer:** Use brief principles with concrete explanations, not long feature inventories.

### Opportunity row

**Only for:** recruitment listings

**Use:** A scannable linked listing within the shared panel.

**CSS:** `display: flex; align-items: center; justify-content: space-between; border-top: 1px solid #bebebe; padding: 16px 0`

**Text style:** `subheading` — neueHaasDisplay 500 · 24px/1.25 · tracking -0.01em

**Observed:** Title and a compact location/work-model line sit left; a small olive Read more pill sits right. Categories are separated by extra breathing room and muted labels.

**Transfer:** Use a single row link with clear metadata rather than a collection of detached job cards.

### Listing filter

**Only for:** recruitment listings

**Use:** A compact filter above the opportunity list.

**CSS:** `background: #f7f3ec; border: 3px solid rgba(18,18,18,0.1); border-radius: 50px; padding: 20px; height: 46px; max-width: 179px`

**Observed:** Four compact equal-width controls run in a tight line; each places the text left and a small chevron right. Rounded goo-like contours echo the closing sculpture.

**States:** Declared: hover background-color #f7f3ec; focus-visible outline-style none and zero box-shadow.

**Transfer:** Use only the filtering dimensions the new listing needs.

## Imagery and graphics

### Pointillist human scene

**Use:** Full-screen narrative opening and return to a human outcome.

**Observed:** An overhead scene of two people resting on a blue blanket in grass occupies the whole screen. Dense colored circular particles build recognizable figures, with blurred foliage and depth softness at the edges. The scene zooms into particle structure and later resolves back to the human scale.

**Transfer:** Show a believable human moment enabled by the new product, not a person posing with it. Minimum version: an overhead photograph rendered into irregular colored dots with a softly blurred photographic backing.

**Build:** Sample a photograph into an SVG or canvas point cloud on a 3–8px irregular grid. Draw small circles colored from each sample, jitter positions, vary radius, and layer a blurred full-bleed copy underneath. Increase point spacing and camera scale for the transition into an abstract process scene; keep the central subject recognizable.

### Technical object stage

**Use:** Large unboxed visual explanation beside small text blocks.

**Observed:** Translucent organ containers, frosted hardware, soft grey housings, pastel connectors and copper coils are isolated on cream. Views shift from a single object to extreme close-up and repeated equipment arrays. Large rounded media windows sometimes contain the more complete scene.

**Transfer:** Use an accurate model of the new product or its mechanism with diffuse studio lighting, transparent materials where meaningful, and cream backing. For nonphysical products, build a simple dimensional process model with a small number of purposeful parts rather than floating interface windows.

**Build:** Create a soft-lit orthographic or mild-perspective object render with ambient contact shadows and no hard horizon. Use an off-white environment, grey structure, translucent shell, and restrained colored internal details; place the render directly on the matching cream field.

### Molecular depth field

**Use:** Immersive explanation within the cinematic narrative.

**Observed:** Milky clusters of shaded spheres float across warm-to-cool colored fields. Near spheres are large and blurred; smaller background clusters suggest depth. A slender temperature scale and short lower-left statements introduce an instrument-like reading.

**Transfer:** Translate the new product's process into repeatable, softly lit geometric units and one meaningful progress scale. Keep units volumetric and sparse enough for annotations.

**Build:** Use canvas or SVG clusters of three overlapping radial-gradient circles with cream highlights and low-opacity dark lower edges. Scatter clusters at multiple scales, blur only the nearest and farthest layers, and interpolate a muted warm-to-blue backdrop as progress changes. Keep annotations above the art.

### Conversational word sculpture

**Use:** Signature closing invitation.

**Observed:** A compact cluster of four white word-bearing capsules alternates gentle rotations. White discs and narrow organic bridges join some forms while others detach; soft shadows lift the group off cream. The final line has a plain underline.

**Transfer:** Retain the physical pile of words for a new invitation. Minimum version: independently rotated white rounded text strips plus connecting circles and one detached disc; keep text sharp and readable.

**Build:** Wrap each text line in a white 64px-radius capsule, with widths ranging from a short prompt to a broad question. Alternate roughly -2.5deg and 2.2deg rotations. Place 108–120px white circles around the edges and short connecting shapes behind; use an SVG blur-and-alpha-threshold goo filter only on a duplicate shape layer, never the lettering. Add a faint diffuse shadow to the unified backing.

### Documentary mosaic

**Use:** Human proof after technical explanation and within recruitment stories.

**Observed:** Candid laboratory work, instruments, forest hikes and informal gatherings appear in mixed landscape and portrait rectangles. Rounded corners and narrow cream gutters unify an asymmetric, horizontally expansive collage; oversized quotation marks and short text occupy deliberate gaps. Captions use a triple-slash prefix.

**Transfer:** Mix actual work scenes and off-duty moments at natural saturation. Keep people engaged with each other or their work, and allow some images to extend beyond the viewport.

### Editorial image sliver

**Use:** Right-hand visual strip in article cards.

**Observed:** Soft foliage bokeh, green defocus, warm orange-yellow blur and red light streaks occupy a tall narrow third of each card; these are atmospheric fragments rather than literal article thumbnails.

**Transfer:** Choose abstract material or light details tied loosely to the article's theme. Keep the narrow framing and let the text carry the specific subject.

### Atmospheric chapter field

**Only for:** recruitment, people and technical overview pages

**Use:** A full-screen alternative to a recognizable narrative scene.

**Observed:** Strongly defocused organic color fills the opening: olive with dark forest shadows, sky blue with cloudlike pale light, or orange with dark red shadows. Fine grain makes the surface feel photographic rather than a clean vector gradient.

**Transfer:** Keep one dominant chapter hue and broad patches of light and darkness. Match the soft glow; exact stops are not essential.

**Build:** Start with the scoped hue as a full-bleed fill. Overlay several 400–800px radial light and dark patches at uneven positions, blur 80–160px, and add low-contrast monochrome grain. Avoid evenly spaced multicolor gradient blobs.

### Connected card glow

**Only for:** benefits and values sections

**Use:** Shared illumination behind the connected glass system.

**Observed:** A diffuse 300px light source is blurred by 190px behind the central cards, olive over forest or pale blue over sky. Translucent short bridges make the card set read as a continuous soft material.

**Transfer:** Use the chapter color as the light source, keeping the glow behind the cards and the connector geometry aligned to selected gaps.

**Build:** Place a 300px circular element at the center of the card grid, use olive or pale sky fill and filter blur(190px). Draw short rounded rectangles in the card's translucent cream between selected adjacent cards; overlap their ends beneath the cards so only narrow soft necks remain visible.

### Portrait wall

**Only for:** people directories

**Use:** A dense human directory.

**Observed:** Square shoulder-up portraits alternate leafy outdoor backgrounds with real laboratory interiors. Cream inset framing, rounded corners and subtle edge shadows create a tactile wall without visible resume text on the resting face.

**Transfer:** Photograph people naturally in two consistent environments. Use real portraits rather than decorative filler tiles.

### Icons

**Observed:** Small social marks use 20px filled SVG silhouettes. Filters use 16px chevrons with 2px round strokes. Benefit-label icons are fine, low-contrast outlines and remain subordinate to the text.

**Transfer:** Use restrained mono icons with consistent proportions; preserve filled social marks and outline utility marks as separate roles.

## Section recipes

How recurring sections are built.

### First screen: Cinematic human opening

**Observed:** A full-bleed pointillist human scene fills the first 900px. Back to front: dark organic backing, blurred photographic depth, colored dot-cloud scene, fine grain, bottom-centered cream headline and small bracketed scroll invitation, then Floating navigation above it all. The human subject fills the middle majority of the viewport while foliage reaches every edge. The 69.4px opening-line occupies roughly four fifths of the width near the bottom, leaving the top half largely to imagery. Only the navigation action appears as a button; explanatory support, product detail and body sections fall below the fold.

**Transfer:** Stage a human outcome relevant to the new product with the same overhead or enveloping composition, particle treatment and lower-edge sentence. Without complex art, use the pointillist photograph recipe. Recruitment, people and technical overviews instead use Atmospheric chapter field, a small centered chapter-note and a broad 132.2px chapter-display anchored low.

**Avoid:** Do not replace the opening with a centered headline, two CTA buttons and a floating dashboard card. Do not put a long explanatory paragraph over the scene.

**Text style:** `opening-line` — neueHaasDisplay 500 · 69.4px/0.95 · tracking -0.03em

### Principle and implication

**Observed:** Cream veil covers a remnant of the scene. A centered 32px principle precedes a larger 56px statement by 48px within an 888px reading width. Both form compact multi-line blocks rather than long prose.

**Transfer:** State one simple governing idea and then the consequential benefit for the reader.

**Text style:** `statement` — neueHaasDisplay 500 · 56px/0.9 · tracking -0.0114em

### Object-led capability chapter

**Observed:** Technical object stage shares a broad cream screen with a short heading and explanation. A 38.7px feature-heading and 12px support gap make the text secondary to the object. The long-form variant uses technical-heading, a 24px subheading, then 16px/24px paragraphs separated by 16px; chapter padding reaches 208px.

**Transfer:** Explain one mechanism per scene and alternate the text/image sides. Use object close-ups to show progression rather than repeating the same feature-card layout.

**Text style:** `feature-heading` — neueHaasDisplay 500 · 38.7px/1 · tracking -0.031em

### Directional thesis

**Observed:** A thin horizontal line with small terminal marks enters from the left and points toward a right-hand 56px title, short paragraphs and a Primary button. Text occupies a narrower column while the line owns the open left half.

**Transfer:** Use the line as an abstract path toward a strategic proposition, keeping it sparse rather than turning it into a detailed timeline.

**Text style:** `heading` — neueHaasDisplay 500 · 56px/0.95 · tracking -0.03em

### Editorial ribbon

**Observed:** A centered title sits above two offset rows of Editorial cards. Cards are 450px by 290px, separated by 48px; both rows extend beyond the viewport. Cream edge fades hide the entrances and exits.

**Transfer:** Make a moving library of real articles or case notes, retaining dates, titles, summaries and authors rather than converting it into a generic benefit carousel.

**Text style:** `card-title` — neueHaasDisplay 500 · 24px/1 · tracking -0.01em

### Human proof montage

**Observed:** Documentary mosaic fills the width with mixed aspect ratios and a few compact display text interruptions. Recruitment captions include a triple-slash lead-in. Technical proof favors workbench and equipment scenes; culture proof includes outdoors and informal social moments.

**Transfer:** Show the people and environment that make the promise credible. Keep captions factual and short.

**Text style:** `feature-heading` — neueHaasDisplay 500 · 38.7px/1 · tracking -0.031em

### Connected principles

**Observed:** A centered heading and short support line precede Connected proof cards within an 888px field. Cards form two columns and three close rows, with a shared glow and soft necks. Recruitment uses Forest field; people-focused content uses a full blue field and finishes with a light action.

**Transfer:** Use this scoped construction for a small family of benefits or operating principles, adapting the number of cards to the content.

**Text style:** `benefit-text` — neueHaasText 500 · 24px/1.25 · tracking -0.01em

### Technical color immersion

**Observed:** An orange field with feathered upper and lower boundaries holds cream chapter text in one reading column. Elsewhere, advanced work shifts to Black technical field with luminous media and centered caveat copy.

**Transfer:** Use a bold chapter transition to separate a materially different level of explanation, not as alternating decoration.

**Text style:** `technical-heading` — neueHaasDisplay 500 · 38.7px/1.1 · tracking -0.02em

### Sculptural invitation and directory

**Observed:** Conversational word sculpture fills the middle of an 810–900px cream section, followed by Footer assembly. The underlined final capsule is the main contact action. People directories instead end their connected-principles field with a light action and proceed directly to the footer, without a second contact sculpture.

**Transfer:** Give a landing page a memorable conversational release before the practical directory. The sculpture can appear elsewhere when a page's own ending is better served by a focused conversion action.

**Text style:** `heading` — neueHaasDisplay 500 · 56px/0.95 · tracking -0.03em

## Page flow

**Storyline:** Human possibility → governing principle → mechanism made tangible → people and working proof → invitation → practical directory.

### Cinematic marketing landing page

1. **Emotional promise** — A full-screen human scene unfolds into microscopic process art and returns to the human outcome.
2. **Thesis** — A translucent cream veil introduces a principle and its larger implication.
3. **Product demonstration** — Large isolated technical objects advance through changes of state beside compact explanations.
4. **Strategic direction** — A line-led proposition connects near-term work to the broader ambition.
5. **Human proof** — A short work-photo sequence and recruitment invitation make the operation tangible.
6. **Knowledge proof** — Two horizontal editorial ribbons offer deeper reading.
7. **Closing call** — A white word sculpture invites contact above the four-column footer.

**Transfer:** Translate a complex product into a human-to-mechanism narrative. Adjust the number of chapters to the explanation rather than stretching the page to a fixed length.

### Recruitment and opportunities page

1. **Purpose** — An olive atmospheric opening pairs a tiny parenthesized line with a monumental lower title.
2. **Work proposition** — A large quotation and compact explanation establish the character of the work.
3. **Actionable inventory** — A single cream-glass panel contains filters and categorized opportunity rows.
4. **Culture proof** — A large asymmetric documentary montage shows work and shared life.
5. **Practical reassurance** — A mission bridge leads into a dark forest connected-card benefits field.
6. **Closing call** — Olive-lettered contact sculpture and matching footer accents conclude the page.

**Transfer:** Balance purpose with usable listings; let photographs substantiate the culture before stating benefits.

### People directory and values page

1. **Identity** — A sky-blue atmospheric title introduces the collective.
2. **Selection philosophy** — A blue statement band explains the shared working standard.
3. **Human proof** — A four-column tactile portrait wall supplies the main content.
4. **Operating principles** — Blue connected glass cards summarize short values and end in a light opportunities action.
5. **Practical ending** — The white directory and blue identity strip close the page directly.

**Transfer:** Make the actual people the dominant proof and keep values concise. This page type uses the blue treatment rather than borrowing the landing page's long cinematic sequence.

### Long-form technical explainer

1. **Chapter promise** — An orange atmospheric opening presents an oversized title low on the screen.
2. **Mechanism chapters** — Alternating text and isolated models explain successive technical capabilities.
3. **Immersive demonstration** — Large rounded equipment scenes expand into close-ups and repeated object arrays.
4. **Verification** — A feather-edged orange chapter gives assessment its own visual weight.
5. **Future ambition and caveats** — A black chapter distinguishes exploratory work from established mechanisms.
6. **Human proof** — A work-focused documentary mosaic introduces the people behind the system.
7. **Closing call** — Black-lettered contact sculpture and the default neutral footer conclude.

**Transfer:** Layer mechanism, validation and open questions. Keep uncertainty explicit and give complex visuals enough room to carry the explanation.

## Writing

Ambitious science spoken plainly, with human motivation close to the technical detail. Confidence comes from naming mechanisms and constraints, while warmth appears in invitations and short statements about people.

**Do not copy:** Do not reuse the Until name, logo shapes, proprietary artworks, employee portraits, named research programs, funding totals, scientific performance claims or employee quotations. Source examples illustrate cadence only; write new substantiated claims and use original assets.

- **Addressing the reader:** Use we for the team doing the work and you in recruitment or direct invitations. Technical explanations can be impersonal before returning to why the work matters.
- **Rhythm:** Short title phrases and crisp contrast sentences alternate with explanatory paragraphs. Conversational fragments, parentheses and occasional exclamation marks soften the closing invitation; technical sections remain more measured.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A familiar human situation or a compact statement of meaningful work. | 3–9 words | “What looks like a peaceful afternoon,”<br>“Work On What Matters” |
| Mechanism subheading | A short declarative contrast or a simple description of the approach. | 4–10 words | “We don’t freeze. We vitrify.”<br>“We repurpose biology’s own delivery network.” |
| Operating principle | A concrete imperative or plain statement with human stakes. | 3–8 words | “Prove yourself wrong, fast.”<br>“Build for someone you love.” |
| Action | Direct, familiar wording with no exaggerated promise. | 2–6 words | “Learn More”<br>“Join the team”<br>“Feel free to reach out!” |
| Caveat | Name the unresolved boundary without abandoning ambition. | One or two short sentences | “We don’t claim it works. Yet.” |

**Words and phrasing to use:** build; work; principle; protocol; care; time; control; proof; together; ready; we’re developing

**Avoid:** revolutionary magic; game-changing platform; effortless everything; unprecedented breakthrough without proof; corporate family; disrupting the future

**Rules:**

- Start with the human consequence, then explain the mechanism that supports it.
- Use exact technical nouns when needed and explain their function in ordinary language.
- Separate current capability from ambition and speculation.
- Let short statements carry values; use paragraphs to show what those values mean in practice.
- Use parenthesized notes and triple-slash captions sparingly as annotation, not as decoration on every block.

## Do's and Don'ts

### Do

- Keep 16px/24px body copy in short readable columns beside substantially larger imagery.
- Use the 56px, weight-500, 0.95-line-height heading recipe for principal editorial titles.
- Give product objects a matching #f7f3ec stage so they feel embedded in the page.
- Retain 36px-high actions with 18px corners and 32px horizontal padding.
- Frame editorial media with an 8px inset and distinguish 32px outer corners from 24px inner corners.
- Keep footer navigation unusually prominent at 32px while group labels remain 12px mono.
- Carry the soft, tactile material language through navigation glass, card edges and white word forms.
- Use 96px or more of chapter breathing room where the object or explanation needs a screen-scale pause.

### Don't

- Do not turn display copy into weight-700 geometric sans headlines; medium neo-grotesk density is central.
- Do not substitute stark white for the continuous cream editorial canvas.
- Do not turn every action into an oversized 56px-high SaaS button; the ordinary action is only 36px tall.
- Do not scatter blue, olive and orange across ordinary feature cards; each field has a scoped narrative job.
- Do not frame every technical object inside a browser window or dashboard shell.
- Do not replace the editorial ribbon's narrow atmospheric image strips with full-bleed thumbnail cards.
- Do not convert the footer into tiny low-priority links or a dense legal sitemap.
- Do not make all photographs equal-sized studio headshots; reserve that regularity for the people directory.

## Motion and responsive

### Motion

**Observed:**

- Actions and editorial surfaces declare 0.382s transitions with cubic-bezier(0.4, 0.25, 0.2, 1). Footer links transition color; primary pills and editorial cards transition all properties.
- The navigation declares a 0.2s ease-out fade-in after a 0.2s delay.
- The visual narrative changes scale and material with scrolling; navigation changes from a broad link bar to a compact capsule. Editorial content uses marquee and reverse-marquee patterns.

**Transfer:**

- Tie camera zooms and process changes to meaningful explanatory stages rather than animating unrelated decorative shapes.
- Keep the reduced navigation stable over immersive media and use the same tactile transition timing for pills and editorial cards.

**Unknown:**

- Exact scroll-to-camera mappings, marquee speed and animation durations outside the stated CSS declarations are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 360px, 480px, 640px, 767px, 768px, 1024px, 1280px, 1536px, 1920px and 1921px.
- Footer classes declare one column, two columns at the small breakpoint and four at the large breakpoint. Opportunity rows declare column layout before switching to a desktop row.

**Transfer:**

- On narrow screens, preserve the lower-edge headline and immersive scene rather than moving the art into a small card.
- Stack object and explanation chapters with the technical object still visually dominant. Keep the contact sculpture's stacked, slightly rotated identity, scaling the group to fit rather than clipping the final action.
- Use the compact symbol-and-action navigation when full destination links cannot fit.

**Unknown:**

- Mobile compositions, exact fluid type formulas and the timing of navigation collapse are not established. These adaptations are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
