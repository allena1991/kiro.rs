# Eclipse — orbital poster energy

## Overview

A high-contrast, retro-futurist editorial style with oversized condensed capitals, delicate narrow serifs and technical uppercase annotations. Black and white alternate with flat mint green, while illustrated space scenes and simple orbital geometry give infrastructure products a playful, cinematic identity. Dense information lives inside rigid ruled grids, surrounded by expansive typographic interludes.

### Essentials

- Headlines splice industrial force with editorial delicacy: Barlow Condensed 700 at 182px/0.8 and -0.03em tracking in the opening, paired with a 120px/0.8 thin condensed serif connector at -0.04em.
- The opening is an illustrated poster rather than a dashboard: a 900px black stage, centered three-line promise, a huge faintly luminous oval behind it, and foreground landscape art along the bottom. Use a custom geometric orbital scene when narrative illustration is unavailable.
- Mint is structural, not confetti: #a1fea0 fills alternating square proof panels and the entire closing footer; black and white occupy most of the remaining page. Keep ordinary copy monochrome rather than mint.
- Actions are small capsules against monumental typography: 100px radius, 41px height, 10px 18px padding and 12px uppercase condensed labels with 0.13em tracking; use the 70px variant for isolated resource calls.
- A continuous editorial ticker and open-parenthesis framing carry the identity beyond the hero: 84px ruled marquee bands with 44px mixed-family text; thin oval side arcs surround centered category labels or proof names.
- Finish with a typographic monument: a centered 96px uppercase invitation on black, an elongated mint identity mark, and a #a1fea0 footer with a near-full-width black wordmark. Recreate this with the new product's own name as vector lettering if it lacks a custom mark.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric mint | `#a1fea0` | `--color-mint` | surface, background, accent, action | Flat proof panels, footer, primary hero capsule and graphic motifs. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Absolute black | `#000000` | `--color-ink` | text, background, border, action | Primary ink, hairline rules, dark stages and inverse actions. |
| Black-backed glass | `#151515` | `--color-glass` | surface | Visible result of rgba(255,255,255,0.082) over black in the top navigation; fades vertically rather than forming an opaque bar. |
| Graphite action | `#585858` | `--color-nav-action` | action, surface | Muted navigation capsule on the dark opening. |
| Muted action label | `#a7a7a7` | `--color-nav-label` | text | Label inside the graphite navigation capsule. |
| Pure white | `#ffffff` | `--color-paper` | background, surface, text, action | Light canvas and cells; reversed display copy and the light hero action. |

## Typography

- **Barlow Condensed** — Display capitals, statistics, navigation and actions. Tall compressed sans with emphatic heavy verticals, set bold for headlines and medium for controls. Font stack: "Barlow Condensed", sans-serif.
- **Gt Alpina Condensed** — Connectors inside headlines, editorial titles and oval-framed names. Very narrow high-contrast serif; thin upright and italic cuts counterbalance the heavy sans. If unavailable, use **Instrument Serif**. Use regular and italic; tune horizontal fit to retain the narrow silhouette. Font stack: "Gt Alpina Condensed", "Instrument Serif", serif.
- **Atlas Typewriter** — Uppercase supporting copy, labels, dates and technical annotations. Typewriter-like technical rhythm, contrasting with the compressed display faces. If unavailable, use **IBM Plex Mono**. Use 400; preserve label spacing and deliberately short line lengths. Font stack: "Atlas Typewriter", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Barlow Condensed | 700 | 182px | 0.8 | -0.03em | size calc(11.375 * (-1.1px + 1.18973vw)) | Main dark-stage headline; uppercase lettering. |
| display-connector | Gt Alpina Condensed | 100 | 120px | 0.8 | -0.04em | fixed | Thin central linking word in the opening. |
| heading-lg | Barlow Condensed | 700 | 120px | 0.9 | -0.03em, uppercase | fixed | Major section and split-panel statements. |
| heading-connector | Gt Alpina Condensed | 100 | 120px | 0.8 | -0.04em, uppercase | fixed | Upright serif words embedded within major section statements. |
| closing-display | Barlow Condensed | 700 | 96px | 0.83 | -0.03em, uppercase | fixed | Centered invitation above the footer. |
| editorial-display | Barlow Condensed | 700 | 80px | 0.8 | -0.02em, uppercase | fixed | Secondary proof statements and editorial narrative emphasis. |
| oval-label | Gt Alpina Condensed | 100 italic | 64px | 1.125 | -0.06em | fixed | Category names inside open oval arcs. |
| stat | Barlow Condensed | 700 | 48px | 1.2 | -0.03em | fixed | Large quantities or short capability titles in proof columns. |
| proof-name | Gt Alpina Condensed | 100 | 46px | 16px | -0.0104em | fixed | Vertically centered single-line names within arc frames; the tight line box is not for wrapping. |
| ticker | Barlow Condensed | 700 | 44px | 1 | -0.02em | fixed | Bold words in horizontal marquee bands. |
| ticker-serif | Gt Alpina Condensed | 100 | 44px | 1 | -0.04em | fixed | Serif emphasis within a ticker sentence. |
| footer-connector | Gt Alpina Condensed | 100 | 33px | 1.2 | -0.03em | fixed | Parenthesized linking word within the compact footer positioning line. |
| compact-heading | Barlow Condensed | 700 | 32px | 38px | -0.03em | fixed | Short bold subheads and the footer's compact positioning line. |
| row-title | Gt Alpina Condensed | 250 | 32px | 38px | -0.03em | fixed | Feature disclosure titles and text-led list items. |
| editorial-title | Gt Alpina Condensed | 100 | 24px | 1.16 | -0.03em | fixed | Title at the bottom of an update card. |
| eyebrow | Atlas Typewriter | 400 | 18px | 1 | 0.2em, uppercase | fixed | Opening identity label and short supporting declaration. |
| body | Atlas Typewriter | 400 | 16px | 25px | normal, uppercase | fixed | Supporting paragraphs and stat captions. |
| section-label | Atlas Typewriter | 400 | 16px | 25px | 0.2em, uppercase | fixed | Small centered labels over proof or closing invitations. |
| button-lg | Barlow Condensed | 500 | 16px | 1.25 | 0.13em, uppercase | fixed | Isolated large conversion capsules. |
| caption | Atlas Typewriter | 400 | 12px | 1.6 | normal, uppercase | fixed | Update metadata, compact descriptions and fine supporting copy. |
| button | Barlow Condensed | 500 | 12px | 1.6 | 0.13em, uppercase | fixed | Compact capsule action labels. |
| navigation | Barlow Condensed | 500 | 12px | 1.6 | 0.1em, uppercase | fixed | Header links. |
| footer-link | Barlow Condensed | 700 | 12px | 1.6 | 0.13em, uppercase | fixed | Compact stacked footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| technical explainer openings | light-display | Barlow Condensed | 700 | 160px | 0.8 | -0.03em, uppercase | fixed | Black display text in the light opening variant. |
| technical explainer closing calls | light-closing-serif | Gt Alpina Condensed | 100 | 88px | 0.9 | -0.06em, uppercase | fixed | Second line beneath an 80px bold invitation. |
| long-form explanations and culture statements | explanation-italic | Gt Alpina Condensed | 100 italic | 80px | 0.7 | -0.03em | fixed | Sentence fragments interwoven with bold editorial display. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The defining contrast is heavy compressed sans versus featherweight narrow serif, often within one heading rather than in separate sections.
- Display tracking is usually -0.03em for the sans and -0.04em for the 120px serif; technical labels reverse the rhythm with 0.2em positive tracking.
- Body text remains uppercase at 16px/25px; long text belongs in short columns, not wide editorial paragraphs.
- Apply the viewport-relative root scale to rem-based dimensions together; do not shrink only the headline while leaving its graphic stage unchanged.

## Layout

**Density:** Airy at the section level, tightly packed inside ruled grids; small annotations coexist with monumental display blocks.

### Spacing

| Value | Use |
| --- | --- |
| 1px | Shared grid seams and section rules. |
| 16px | Heading-to-label spacing and paired hero actions. |
| 20px | Header link spacing and ticker item gaps. |
| 24px | Grouped closing content and proof-grid gaps. |
| 32px | Update-card padding and dense panel insets. |
| 40px | Paragraph-to-action gaps and narrative side insets. |
| 48px | Footer padding and internal section rhythm. |
| 52px | Primary editorial section side inset. |
| 64px | Medium section padding and category-column top inset. |
| 100px | Large separation between compact panel title and description. |
| 120px | Major heading bands and dark closing vertical padding. |
| 240px | Long-form explanation chapter spacing. |

### Containers and grids

- **display container**: max width 1400px · side padding 36px. Centered display and carousel region; 1368px usable width at a 1440px viewport.
- **editorial inset**: side padding 52px. Ruled heading bands, list sections and split editorial calls.
- **square comparison**: 2 columns · gap 1px. Edge-to-edge equal square cells, 720px per side at desktop, alternating copy and symbolic media.
- **proof columns**: 3 columns · gap 1px. Full-width equal cells separated by black seams.
- **name grid**: 3 columns · gap 24px. Oval-framed social proof with open white backing.
- **narrative column**: max width 542px · side padding 40px. Long-form explanation on the left opposite a compact sticky schematic.
- **closing block**: max width 680px. Centered invitation with a wide identity mark as its middle line.

## Corner radius

| Element | Radius |
| --- | --- |
| capsule actions | 100px |
| update cards | 25px |
| oval frames | 50% |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default light editorial ground.

**CSS:** `background: #ffffff; color: #000000`

#### Black stage · level 0

**Use:** Opening art, media interludes, updates and the final invitation.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat black creates cinematic pauses between white or mint structural bands.

**Transfer:** Use black as a whole scene, not as a small floating card.

#### Mint panel · level 0

**Use:** Proof panels and footer.

**CSS:** `background: #a1fea0; color: #000000`

**Observed:** Opaque flat color with no gradient, bevel or shadow.

**Transfer:** Let mint occupy complete cells or bands.

#### Ruled grid · level 0

**Use:** Contiguous proof, comparison and disclosure sections.

**CSS:** `display: grid; gap: 1px; background: #000000`

**Observed:** White or mint children expose the black ground as hairline seams; most panels have square corners.

**Transfer:** Choose two or three equal columns based on content.

#### Navigation glass · level 1

**Use:** Background layer of the dark-stage navigation.

**CSS:** `background: rgba(255, 255, 255, 0.082); backdrop-filter: blur(20px); mask-image: linear-gradient(#ffffff 0%, rgba(0, 0, 0, 0) 100%)`

**Observed:** A subtle fading haze behind the header rather than a bounded glass card.

**Transfer:** Keep the mask on the background layer so labels remain crisp.

## Components

### Navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: fixed; height: 65px; z-index: 100`

**Text style:** `navigation` — Barlow Condensed 500 · 12px/1.6 · tracking 0.1em · uppercase

**Observed:** Left-aligned compact links with small chevrons, an independently centered identity mark, then social glyphs and a compact action at the right. The background uses Navigation glass. Over light content the identity and links become black; technical explainers use a white sticky bar with a 1px black lower rule.

**States:** Declared: hover opacity 0.7 on navigation links; focus-visible behavior for dropdown triggers is unknown.

**Transfer:** Keep the central mark optically centered regardless of left and right group widths.

### Mint button

**Use:** Primary action on a black opening.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #a1fea0; color: #000000; border: 1px solid transparent; border-radius: 100px; padding: 10px 18px; height: 41px; gap: 4.8px`

**Text style:** `button` — Barlow Condensed 500 · 12px/1.6 · tracking 0.13em · uppercase

**Observed:** Short uppercase label, typically paired with a white secondary action.

**States:** Declared: hover background white and color black; focus-visible 2px solid #d14424 outline with 2px offset.

### Light button

**Use:** Secondary hero action.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid transparent; border-radius: 100px; padding: 10px 18px; height: 41px; display: flex; align-items: center; gap: 4.8px`

**Text style:** `button` — Barlow Condensed 500 · 12px/1.6 · tracking 0.13em · uppercase

**Observed:** A small northeast arrow follows the label.

**States:** Declared: hover background #a1fea0 and color black; focus-visible 2px solid #d14424 outline with 2px offset.

### Black button

**Use:** Conversion inside a mint proof panel.

**CSS:** `background: #000000; color: #ffffff; border: 1px solid transparent; border-radius: 100px; padding: 10px 18px; height: 41px; max-width: 140px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — Barlow Condensed 500 · 12px/1.6 · tracking 0.13em · uppercase

**Observed:** Left-aligned beneath short supporting text.

**States:** Declared: hover background rgba(161,254,160,0), color black and border-color black; focus-visible 2px solid #d14424 outline with 2px offset.

### Large capsule

**Use:** Standalone resource or closing conversion.

**CSS:** `background: #a1fea0; color: #000000; border: 1px solid transparent; border-radius: 100px; padding: 24px 40px; height: 70px; display: flex; align-items: center; justify-content: center; gap: 6.4px`

**Text style:** `button-lg` — Barlow Condensed 500 · 16px/1.25 · tracking 0.13em · uppercase

**Observed:** A larger action below stacked display lettering. On light explainer endings and referral bands, the inverse version is black with white text.

**States:** Declared: hover background black and color #a1fea0 for the mint version; focus-visible 2px solid #d14424 outline with 2px offset.

### Ticker band

**Use:** Continuous declarative ribbon between large scenes.

**CSS:** `height: 84px; display: flex; align-items: center; border-top: 1px solid #000000; border-bottom: 1px solid #000000; background: #ffffff; color: #000000; overflow: hidden; gap: 20px`

**Text style:** `ticker` — Barlow Condensed 700 · 44px/1 · tracking -0.02em

**Observed:** A repeated mixed sans/serif sentence runs beyond both viewport edges; short horizontal rules divide phrases.

**Transfer:** Use one compact positioning statement repeated as a seamless strip.

### Square proof panel

**Use:** A headline, supporting claim and action beside symbolic artwork.

**CSS:** `background: #a1fea0; color: #000000; display: flex; flex-direction: column; justify-content: space-between; padding: 60px 140px 60px 52px`

**Text style:** `heading-lg` — Barlow Condensed 700 · 120px/0.9 · tracking -0.03em · uppercase

**Observed:** Small top annotation, a mixed-family heading in the middle, then body text and Black button near the bottom. It fills half the desktop page width and pairs with an equally sized white media tile.

**Transfer:** Reserve the large heading for a single benefit and use a simple custom symbol in the neighboring cell.

### Arc frame

**Use:** Category labels and named social proof.

**CSS:** `border-left: 1px solid #000000; border-right: 1px solid #000000; border-radius: 50%; display: flex; align-items: center; justify-content: center`

**Text style:** `proof-name` — Gt Alpina Condensed 100 · 46px/16px · tracking -0.0104em

**Observed:** Only curved side edges are visible, like stretched parentheses rather than a complete oval. Name frames are 464px wide and 258px tall but clipped into a 152px-high wrapper; category frames use italic Oval label text.

**Transfer:** Clip elliptical side borders vertically to preserve the open ends.

### Update card

**Use:** Editorial announcements in a horizontal rail.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #000000; border-radius: 25px; padding: 32px; width: 380px; height: 320px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `editorial-title` — Gt Alpina Condensed 100 · 24px/1.16 · tracking -0.03em

**Observed:** Category with an 8px mint dot at top left, date at top right; title and compact description sit near the bottom, leaving a broad intentional middle space. Cards overflow to the right beneath giant serif word artwork.

**States:** Declared: hover transform translate(0px, -0.25rem); focus-visible 2px solid #d14424 outline with 2px offset.

### Text row

**Use:** Feature disclosures and editorial list entries.

**CSS:** `border-bottom: 1px solid #000000; display: flex; flex-direction: column; gap: 36px`

**Text style:** `row-title` — Gt Alpina Condensed 250 · 32px/38px · tracking -0.03em

**Observed:** A serif title is paired with a small category and right arrow in job lists, or a mint solid symbol in feature disclosures. Job-row links have 24px vertical padding and approximately 89px total row height.

**Transfer:** Retain the long ruled row instead of converting titles into independent rounded cards.

### Footer link

**Use:** Compact footer navigation and legal groups.

**CSS:** `color: #000000; text-decoration: none`

**Text style:** `footer-link` — Barlow Condensed 700 · 12px/1.6 · tracking 0.13em · uppercase

**Observed:** Two dense left-side columns with 2px vertical gaps, balancing a compact positioning line and social icons at the right.

**States:** Declared: hover opacity 0.7 and text-decoration none; focus-visible 2px solid #d14424 outline with 2px offset.

### Monument footer

**Use:** The final identity statement and navigation destination.

**CSS:** `background: #a1fea0; color: #000000; display: grid; gap: 48px; padding: 48px`

**Observed:** A compact top row of links, positioning line and social glyphs sits above an almost full-width black custom wordmark measuring 1344px by 144px. The section is 413px tall at desktop.

**Transfer:** Use the new product's own identity as a wide vector or strongly fitted lettering; preserve the abrupt flat mint ending.

## Imagery and graphics

### Orbital illustrated stage

**Use:** The primary opening and large cinematic media interludes.

**Observed:** A huge black tilted oval is rim-lit in pale green behind white centered type. Mint cloud banks and rocky terrain rise from both lower corners around a small illustrated rider and motorcycle at bottom center. The supporting film scene uses a low-angle hand-drawn futuristic vehicle, roadside sign and dark blue-purple environment. Illustration is full-bleed, with crisp sketch outlines and large flat shaded areas.

**Transfer:** Create a product-specific travel or exploration metaphor with the same black sky, mint foreground and central negative space for type. Minimum version: an orbital silhouette, contour-line terrain and one small original geometric object near the horizon.

**Build:** Place a black background behind an SVG ellipse about 1000px wide and 1150px tall, rotated 20deg, extending above the viewport. Stroke its edge with rgba(161,254,160,0.45), duplicate with 12px blur and keep the center black. Add layered mint SVG paths along the bottom 250px with black contour strokes and uneven scalloped cloud silhouettes; place a small original object at bottom center. Keep text above every art layer.

### Orbital flat geometry

**Use:** Graphic interludes, heading-band edges, media cells and text-backed calls.

**Observed:** Oversized mint ovals, wedges and starburst cutouts sit on white. A large green disk with radiating white slits is cut off by the right edge of a heading band; an oblique oval fills most of the right half of a resource call. The shapes are flat, bold and much larger than annotation text.

**Transfer:** Use a custom family of ellipse-based symbols that repeat across the page instead of unrelated stock icons.

**Build:** Use an SVG viewBox of 660 by 620 with a mint ellipse centered at 330,310, radii 300 and 270, rotated -20deg. For the starburst variant, subtract 8 narrow irregular triangular wedges converging slightly off-center; let the disk extend outside its container. Put black uppercase body copy on top of a solid central area.

### Monumental word artwork

**Use:** An editorial chapter title and the final brand signature.

**Observed:** A huge thin italic serif chapter word stretches across a black section and fades into black near its lower edge; the footer instead uses crisp, broad, forward-slanted custom black lettering on mint.

**Transfer:** Include a word-as-art device using a relevant short chapter word and a separate near-full-width rendering of the product identity.

**Build:** Set a short uppercase word in the narrow serif italic inside a 1368px by 432px SVG, fitting it with textLength and lengthAdjust. Use a white-to-transparent vertical fill gradient, not a colored glow. For the footer render the new name as a fitted vector in a heavy oblique face within a 1344px by 144px art box.

### Perspective checker field

**Only for:** culture and technical explainer pages

**Use:** A horizon under the alternate opening and a warped geometric payoff in the explainer.

**Observed:** Mint-and-black or mint-and-white checks recede toward a central vanishing point at the bottom of the hero. Later, a vertical rectangular checker field bends in perspective behind a centered identity statement.

**Transfer:** Use the same playful spatial depth without importing a complex narrative illustration.

**Build:** Make an SVG checker plane with 8 columns and 6 rows, alternating mint and transparent cells. Compress successive row heights toward a centered horizon. For a CSS fallback apply perspective(500px) rotateX(65deg) to a 1440px by 400px checker grid, anchor it at bottom center and clip overflow.

### Team documentary mosaic

**Only for:** culture and hiring pages

**Use:** Human proof between mission and practical benefits.

**Observed:** Candid workplace, shared meals, group outings and presentation photographs form a flush three-column, two-row mosaic. Each tile is 479px by 320px with 1px seams, square corners and natural photographic color.

**Transfer:** Use real candid team imagery with similarly varied indoor and outdoor settings; keep the grid equal and avoid portrait-card framing.

### Icons

**Observed:** Predominantly solid social and brand glyphs, around 18–32px in navigation and footer; compact 14px action arrows use a thin square-capped stroke. Mint solid symbols introduce feature disclosures.

**Transfer:** Use recognizable monochrome social glyphs and simple directional arrows. Keep decorative orbit symbols separate from functional UI icons.

## Section recipes

How recurring sections are built.

### First screen: Orbital poster opening

**Observed:** A 900px Black stage fills the first screen. Navigation floats in the top 65px. The centered content begins with an 18px tracked identity label around a 128px top inset, then a three-line headline: two heavy 182px condensed lines separated by a thin 120px serif connector. The longer headline line occupies roughly half the page width, leaving orbital negative space around it. Behind the type is a near-viewport-size tilted rim-lit black oval; mint landscape rises in front at both lower corners with a small illustrated object at bottom center. A short uppercase support line and a paired white and mint 41px capsule row sit beneath the headline, with 16px between actions. The entire headline, support, actions and foreground object fit in the first 900px; the ticker begins below the fold.

**Transfer:** Center a compact two-part promise around one serif linking word. Recreate the Orbital illustrated stage with original geometric art if bespoke illustration is unavailable. Hiring openings retain the black poster and replace landscape with a checker horizon; technical explanations use the scoped white opening, black 160px headlines and a checker floor.

**Avoid:** Do not substitute a left-copy/right-dashboard SaaS hero, or let the art erase the centered hierarchy and paired actions.

**Text style:** `display` — Barlow Condensed 700 · 182px/0.8 · tracking -0.03em

### Ruled moving declaration

**Observed:** Ticker band spans the entire page between illustration and content, mixing Ticker and Ticker-serif text with 20px gaps and black rules.

**Transfer:** Introduce a concise positioning refrain that remains readable as a repeated strip.

**Text style:** `ticker` — Barlow Condensed 700 · 44px/1 · tracking -0.02em

### Alternating square argument

**Observed:** Square comparison layout pairs Square proof panel with white symbolic media cells, then reverses their positions on the next row. Headlines combine Heading-lg and Heading-connector, and supporting copy uses Body.

**Transfer:** Use this for two complementary product advantages, assigning each a distinct original geometric symbol.

**Text style:** `heading-lg` — Barlow Condensed 700 · 120px/0.9 · tracking -0.03em · uppercase

### Heading band with cropped emblem

**Observed:** A white 460px band uses 120px 52px padding, black rules and an oversized mint radial symbol clipped at the right. A mixed-family statement occupies the left two thirds.

**Transfer:** Use the band to change narrative scale before a dense grid, keeping the emblem secondary to the words.

**Text style:** `heading-lg` — Barlow Condensed 700 · 120px/0.9 · tracking -0.03em · uppercase

### Arc-topped proof columns

**Observed:** Three equal white columns use Ruled grid seams. Italic category names sit within open Arc frames above two vertically separated stat or capability groups; 48px bold quantities pair with 16px uppercase captions.

**Transfer:** Mix quantities and named capabilities without changing the shared column construction.

**Text style:** `stat` — Barlow Condensed 700 · 48px/1.2 · tracking -0.03em

### Editorial rail on black

**Observed:** Black stage has 150px top and 72px bottom padding. Monumental word artwork occupies a 1368px by 432px header area above horizontally overflowing Update cards.

**Transfer:** Use for research, product updates or editorial proof; keep the oversized chapter word and compact lower card text.

### Named proof field

**Observed:** A tracked section label and centered 80px bold title precede a three-column field of Arc frames with 24px gaps. Thin serif names are centered within the clipped ellipses.

**Transfer:** Frame real partners, expert contributors or customer names as editorial proof rather than a wall of small grayscale logos.

**Text style:** `proof-name` — Gt Alpina Condensed 100 · 46px/16px · tracking -0.0104em

### Monument closing

**Observed:** A 640px Black stage with 120px vertical padding centers a tracked label, 96px invitation split above and below a 680px-wide mint identity mark. It transitions directly into Monument footer. The technical explainer variant is a 520px white call with mint orbital shapes entering from both sides, an 80px bold line, an 88px thin serif line and a black Large capsule, followed by the same footer.

**Transfer:** Give a short closing invitation and the product identity comparable visual weight; preserve the full-width mint footer across page types.

**Text style:** `closing-display` — Barlow Condensed 700 · 96px/0.83 · tracking -0.03em · uppercase

### Long-form schematic argument

**Only for:** technical explainers

**Observed:** A white page opens with centered 160px heavy type and a 120px serif connector above a checker horizon. A mint numbered overview uses three ruled columns. Later, a 542px left text column advances in chapters separated by 240px gaps; mixed 80px sans and italic serif phrases face a compact 300px sticky schematic on the right. Flat bordered blocks distinguish system layers. A warped checker identity payoff leads to a half-width headline beside stacked feature disclosure rows.

**Transfer:** Use this variant when a product needs a staged explanation: establish the old model, expose a constraint, then progressively simplify the schematic. Keep diagram labels factual and limit colors to semantic distinctions.

**Text style:** `light-display` — Barlow Condensed 700 · 160px/0.8 · tracking -0.03em · uppercase

### Culture and opportunity sequence

**Only for:** culture and hiring pages

**Observed:** Black poster opening gives way to a centered mixed-family mission statement over a soft mint oval haze, then split mint/white editorial panels and Team documentary mosaic. A ruled three-column benefits grid alternates white and mint cells, with 32px inner padding and 100px title-to-description separation. Open opportunities use Text rows; a flat mint referral band uses a 64px narrow serif statement and Large capsule.

**Transfer:** Replace the content with the actual workplace story and practical opportunities while retaining the change from cinematic promise to candid proof to utility.

## Page flow

**Storyline:** cinematic promise → reframed proposition → concrete advantages → capability or human proof → editorial or practical detail → monumental invitation → identity-led footer

### Flagship marketing landing page

1. **Promise** — Black illustrated orbital poster with a centered mixed-family headline and paired actions.
2. **Product atmosphere** — Ruled ticker around a full-width illustrated film interlude.
3. **Core advantages** — Alternating mint copy squares and symbolic media squares.
4. **Capability proof** — Emblem heading band, three arc-topped stat columns and a resource call.
5. **Continuing proof** — Monumental editorial chapter word above update cards, followed by an arc-framed named-proof field.
6. **Closing invitation** — Black typographic identity invitation and mint monument footer.

**Transfer:** Adapt the argument length to the product; retain the orbital stage, typographic refrain, ruled proof and identity-led ending rather than the exact section sequence.

### Hiring and organizational culture

1. **Recruitment promise** — Black centered poster and mint action over a checker horizon.
2. **Mission** — Mixed-family centered statement and split mint/white editorial description.
3. **Human proof** — Flush documentary photo mosaic.
4. **Practical offer** — Ruled checkerboard benefit cells followed by opportunity rows.
5. **Additional participation** — Mint referral call with large serif wording and black capsule.
6. **Closing invitation** — Shared black invitation and mint monument footer.

**Transfer:** Separate emotional recruitment from practical information without losing the display-heavy identity.

### Detailed product rationale and technical education

1. **Positioning** — White mixed-family centered promise with checker horizon.
2. **Orientation** — Ticker and numbered mint overview.
3. **Problem and solution** — Widely spaced editorial chapters alongside a sticky evolving schematic.
4. **Synthesis** — Warped checker identity payoff and split feature disclosure section.
5. **Closing action** — White orbital call with black capsule, then shared mint footer.

**Transfer:** Translate a complex distinction into a few concrete visual stages; retain the white editorial variant for reading-intensive explanations.

## Writing

Bold, technically literate and optimistic. The voice makes short declarative promises, then grounds them in concrete mechanics, numbers or practical opportunities; playful visual character does not turn the copy into jokes.

**Do not copy:** Do not reuse Eclipse names, logos, mascot, proprietary artwork, ecosystem names as endorsements, investor lists, token claims, performance figures, financial totals, compensation offers or source-specific quotes as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Direct imperatives address the reader; explanatory copy generally names the product, while culture copy uses we and you.
- **Rhythm:** Display headlines are usually two to seven words, often broken into emphatic fragments linked by a serif word. Support copy is compact and uppercase; long-form arguments alternate one short assertion with one explanatory paragraph.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Combine two familiar strengths with a minimal linking word. | 3–7 words | “SOLANA ON ETHEREUM” |
| Section headline | Use an imperative and a product or category noun, with a light serif connector. | 3–6 words | “push onchain with eclipse” |
| Supporting line | Name the mechanism and then its practical advantage. | One compact paragraph | “Superior speed, security, and scalability for powerful apps” |
| Primary action | Verb plus destination or direct next step. | 2–4 words | “BUILD ON ECLIPSE”<br>“SEE OPEN ROLES” |
| Narrative pivot | A blunt uppercase question or objection that earns the next explanation. | 2–4 words | “BUT HOW?”<br>“BUT IT’S NOT” |
| Closing invitation | Invite participation rather than restating a technical specification. | 3–6 words | “join the community” |

**Words and phrasing to use:** build; scale; powerful; speed; future; access; combine; challenge conventions

**Avoid:** revolutionary magic; effortless everything; cute mascot dialogue; luxury lifestyle language; unsupported superlatives

**Rules:**

- Lead with a compressed proposition and explain the mechanism after it.
- Use sentence logic across mixed typefaces; the serif word should link or qualify the bold words.
- Put units and qualifiers alongside quantified claims.
- Keep action labels literal and short; reserve personality for headline rhythm.
- Uppercase is a visual treatment, not a reason to fill every line with shouting punctuation.

## Do's and Don'ts

### Do

- Pair 700-weight condensed sans with 100-weight narrow serif inside major headings.
- Keep technical body copy at 16px/25px and short enough for panel-width reading.
- Use 1px black seams between full-bleed white and mint cells.
- Give the primary desktop editorial inset 52px and the footer 48px.
- Preserve 41px compact capsules and the separate 70px large-action scale.
- Make the final identity artwork nearly full width, with a 1344px by 144px desktop art box.
- Use open ellipse side arcs around category and proof labels.
- Let the primary orbital composition and the ticker recur as identity devices, even when all content changes.

### Don't

- Do not replace uppercase condensed display with a wide geometric sans; it changes the poster proportions.
- Do not round the main comparison or benefit cells to 25px; that radius belongs to update cards.
- Do not spread mint across body text, every border and every icon; it works as a flat structural field.
- Do not add drop shadows to the ruled panel system; its depth comes from contrast and art.
- Do not turn the footer into a small neutral legal strip; the mint identity field is a major scene.
- Do not use a full oval outline where the side-arc motif should have open top and bottom edges.
- Do not increase compact action labels to body size; the 12px tracked label is intentionally small beside display type.
- Do not apply the 46px/16px proof-name recipe to multi-line prose; it is a vertically centered single-line treatment.

## Motion and responsive

### Motion

**Observed:**

- Ticker tracks declare a 20s linear infinite scroll animation.
- Links declare opacity 0.2s ease transitions; buttons declare 0.3s background and color transitions with cubic-bezier(0.165,0.84,0.44,1) for shadow and border changes.
- Update cards declare transform 0.3s ease and opacity 0.2s ease; named proof items declare 0.8s cubic-bezier(0.4,0,0.2,1).

**Transfer:**

- Preserve the continuous ticker as the main repeated motion motif and the small upward update-card response.
- Keep typographic and diagram changes subordinate to readable chapter stops.

**Unknown:**

- Illustrated video timing and scroll choreography are not established.
- Exact reveal thresholds and reduced-motion behavior are unknown.

### Responsive

**Observed:**

- The root font-size uses calc(-1.1px + 1.18973vw), with rem-based dimensions scaling alongside it.
- Declared width breakpoints include 479px, 767px, 768px, 991px, 992px and 1600px.

**Transfer:**

- On narrow screens, preserve the centered mixed-family promise and orbital rim while reducing peripheral scenery; keep the foreground object out of the action row.
- Stack alternating copy and symbolic media cells in their reading order, and turn proof columns into single-width ruled cells.
- Keep the update rail horizontally traversable; fit the footer identity to its available width rather than wrapping the name.

**Unknown:**

- Exact mobile navigation, breakpoint-specific stacking and small-screen type values are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
