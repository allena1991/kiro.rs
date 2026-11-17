# basement.studio — industrial type playground

## Overview

An abrasive, playful digital workshop with black canvases, hot orange signals and monumental letterforms. Expanded grotesks collide with tiny monospaced controls, while three-dimensional typography, wireframe lettering and stark photography make the work feel tactile. It suits creative tools and ambitious digital products: dense at the control level, theatrical at the object level. Editorial and organizational pages use a softer gray grotesk hierarchy without losing the black industrial frame.

### Essentials

- The opening is an object, not a slogan template: a 1146×630px orange-and-black typographic sculpture fills the main column beside a 270px utility rail, with a 14px uppercase mono ticker above it.
- Letterforms behave like exhibits: 120px expanded black grotesk with 0.95 line height and 0.01em tracking sits inside 362px-high bordered stages; the interface around it stays at 14px/16px mono.
- Actions resemble instrument labels: 1px outlines, 2.8px corners and 4.2px horizontal padding, with orange reserved for the purchase/action variant and white for exploration.
- Black owns the page; orange owns the signal and the opening artwork: #000000 canvas, #121212 toolbars, #3a3a3a hairlines and #efefef specimens. Outside the sculpture, color stays in short labels, counts, links and active states.
- Maintain the workshop furniture: a persistent index with boxed labels and small exposed counts, a clipped uppercase ticker, and a monumental outlined word sculpture near the ending. If no product render exists, build these from the new product's own letters and geometric parts.
- Make scale changes abrupt: tiny mono metadata meets enormous objects, then the ending opens into a full-width wireframe word above compact link columns. The editorial variant instead closes with a 1408×142px solid wordmark band and oversized text navigation.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff4d00` | `--color-accent` | accent, text, border, action, link | Opening sculpture, identity, active labels, purchase outlines, counts, hover links and selection. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Absolute black | `#000000` | `--color-canvas` | background, surface | Default canvas and the void around objects. |
| Toolbar charcoal | `#121212` | `--color-toolbar` | surface | Thin control strips inside specimen stages. |
| Panel edge | `#3a3a3a` | `--color-rule` | border, surface | Stage outlines, inactive FAQ rules and technical tracks. |
| Utility gray | `#747474` | `--color-muted` | text, border | Ticker, inactive modes, descriptions and supporting information. |
| Specimen white | `#efefef` | `--color-text` | text, border | Primary specimen lettering, mono controls and outlined actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial footers | Input charcoal | `#1a1a1a` | `--color-input` | surface, border | Flat newsletter input fill and matching edge. |
| editorial, organization and case-study pages | Editorial hairline | `#2e2e2e` | `--color-editorial-rule` | border | Visible result of rgba(230,230,230,0.2) on black. |
| editorial, organization and case-study pages | Editorial chapter rule | `#454545` | `--color-editorial-strong-rule` | border | Visible result of rgba(230,230,230,0.3) on black, separating major rows and closing identity bands. |
| editorial, organization and case-study pages | Editorial secondary | `#757575` | `--color-editorial-muted` | text | Section labels, secondary metadata and counts. |
| editorial, organization and case-study pages | Editorial gray | `#c4c4c4` | `--color-editorial-text` | text | Main headings and paragraphs; closed listing text uses this hue at 30% opacity over black, appearing near #3b3b3b. |
| editorial, organization and case-study pages | Editorial highlight | `#e6e6e6` | `--color-editorial-bright` | text, border | Prominent links, testimonial and footer navigation. |

## Typography

- **Basement Grotesque** — Expanded black cut for core specimen statements and graphic lettering; other cuts belong to type-testing demonstrations. Extremely broad, heavy grotesk with flat terminals and blunt geometric counters. If unavailable, use **Archivo Black**. Use horizontal expansion for the broad black cut; preserve width before fitting copy. Font stack: "Basement Grotesque", "Archivo Black", Arial Black, sans-serif.
- **JetBrains Mono** — Core navigation, toolbar labels, ticker, answers and footer utilities. Technical monospace, usually uppercase, lightly tracked rather than tiny condensed sans. Font stack: "JetBrains Mono", ui-monospace, monospace.
- **Inter** — FAQ questions and descriptive product-detail prose. Neutral, legible regular sans that recedes behind the specimens. Font stack: "Inter", Arial, sans-serif.
- **Geist** (only for editorial, organization and case-study pages) — Headings, paragraphs, metadata and navigation. Semibold grotesk with compressed line spacing and increasingly negative tracking at display sizes. OpenType features: "ss01". Font stack: "Geist", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Basement Grotesque | 900 | 120px | 0.95 | 0.01em, uppercase | fixed | Expanded two-line specimen headline; centered and fitted to almost the full stage width. |
| question | Inter | 400 | 18px | 1.5 | normal | fixed | Readable FAQ questions against the tiny mono answer column. |
| control | JetBrains Mono | 400 | 14px | 16px | 0.04em, uppercase | size max(14px, 0.729167vw), line height max(16px, 0.833333vw) | Toolbar names, mode switches and compact outlined actions. |
| index | JetBrains Mono | 400 | 14px | 18px | 0.06em, uppercase | size max(14px, 0.729167vw), line height max(18px, 0.9375vw) | Boxed navigation labels and catalog links. |
| ticker | JetBrains Mono | 400 | 14px | 1.3 | 0.01em, uppercase | size max(14px, 0.729167vw) | Top marquee and compact opening support copy. |
| answer | JetBrains Mono | 400 | 14px | 1.32 | -0.02em, uppercase | fixed | FAQ explanations; denser than navigation labels. |
| footer-utility | JetBrains Mono | 400 | 12px | 1.5 | 0.06em, uppercase | fixed | Legal, social, support and copyright links in the compact ending. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| editorial and organization pages | editorial-title | Geist | 600 | 98px | 88px | -0.04em | fixed | Page title anchoring an asymmetric opening grid. |
| editorial and organization pages | editorial-statement | Geist | 600 | 76px | 68px | -0.04em | fixed | Chapter headings, a standalone testimonial, exposed headcount and closing invitation. |
| editorial and organization pages | editorial-lead | Geist | 600 | 38px | 36px | -0.04em | fixed | Capability descriptions and introductory manifesto paragraphs. |
| editorial, organization and case-study pages | editorial-footer-link | Geist | 600 | 38px | 0.89 | -0.04em | fixed | Large stacked links in the editorial footer. |
| editorial and organization pages | editorial-label | Geist | 600 | 24px | 1 | -0.03em | fixed | Section labels, ledger titles and job roles; secondary labels use gray, not uppercase. |
| editorial and organization pages | editorial-body | Geist | 600 | 20px | 1 | -0.02em | fixed | Supporting paragraphs, ledger details and newsletter invitation. |
| product-detail pages | detail-body | Inter | 400 | 18px | 1.33 | normal | fixed | Description and specification-table values. |
| editorial, organization and case-study pages | editorial-meta | Geist | 600 | 13px | 16px | normal | fixed | Case-study metadata, directory details and small labels. |
| editorial, organization and case-study pages | editorial-nav | Geist | 600 | 12px | 16px | normal | fixed | Compact fixed top navigation. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use the expanded black cut as the core display voice; the declared family names separate cuts, but the visual weight is black, not regular.
- The opening's primary statement is sculptural lettering rather than a conventional text headline. Keep the display recipe for readable statements and use the sculpture recipe for the main object.
- Mono labels remain 14px even beside immense artwork. Do not scale the interface up in proportion to the exhibit.
- Specimen galleries can demonstrate sharply different silhouettes—pixelated blackletter, modular blocks, soft blobs, slanted segmented forms and hairline serifs. Those are exhibited products, not additional fonts for ordinary page copy.
- The editorial hierarchy is deliberately tight: tracking is -0.04em at 38px and above, while labels relax to -0.03em and body to -0.02em.

## Layout

**Density:** Dense control surfaces and compact utility copy alternate with oversized, isolated visual stages.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Action pairs, navigation item separation and compact grids. | fixed |
| 10px | Horizontal control-strip inset. | max(10px, 0.625vw) |
| 12px | FAQ row vertical padding and editorial column gutters. | fixed |
| 16px | Editorial page edge, chapter-row padding and text-to-heading separation. | fixed |
| 24px | Core main-column edge and opening object-to-caption separation. | max(24px, 1.66667vw) |
| 30px | Separation between repeated specimen stages. | max(30px, 1.66667vw) |
| 60px | FAQ heading-to-questions offset. | fixed |
| 90px | FAQ column separation at desktop. | fixed |
| 100px | Opening-to-gallery pause and FAQ top inset. | fixed |
| 176px | Major chapter separation in the editorial variant. | fixed |

### Containers and grids

- **Workshop frame**: max width 1574px · side padding 24px. Main content sits to the right of a 270px persistent rail. At 1440px, the main region is 1170px and bordered stages are 1122px wide; the ending expands across both regions.
- **Question and answer split**: 2 columns · gap 90px · side padding 24px. Equal-width question and answer areas spanning the entire page rather than staying inside the main rail offset.
- **Editorial grid** (only for editorial, organization and case-study pages): max width 1920px · 12 columns · gap 12px · side padding 16px. Titles, photos, paragraphs and tables align to a full-width twelve-column grid.
- **Three-part chapter** (only for organization pages): 3 columns · gap 12px. Three equal 461px columns at desktop: statement, square photo and dense supporting paragraph.
- **Case-study rail** (only for case-study pages): max width 1920px · 12 columns · gap 12px · side padding 16px. A 225px sticky metadata rail occupies two grid columns; media fills the remaining ten, 1171px wide at desktop.

## Corner radius

| Element | Radius |
| --- | --- |
| Instrument labels | 2.8px |
| Specimen stages | 8px |
| Theme controls | 50% |

## Surfaces and depth

### Surfaces

#### Black canvas · level 0

**Use:** All page regions and the empty space around staged objects.

**CSS:** `background: #000000; color: #efefef`

**Observed:** No raised-card shadows; depth comes from the artwork rather than interface elevation.

**Transfer:** Separate content with thin edges and scale instead of layered gray cards.

#### Dotted specimen stage · level 1

**Use:** Repeatable product demonstrations.

**CSS:** `background-color: #000000; background-image: radial-gradient(circle at 1px 1px, rgba(239,239,239,0.12) 0.5px, rgba(0,0,0,0) 0.6px); background-size: 8px 8px; border: 1px solid #3a3a3a; border-radius: 8px; overflow: hidden`

**Observed:** An almost invisible regular dot field backs large white specimens. Each stage has a dark control strip along its top.

**Transfer:** Use the faint matrix behind a product object, comparison or live preview, not behind all body text.

#### Control strip · level 1

**Use:** Narrow toolbar at the top of a stage.

**CSS:** `background: #121212; border-bottom: 1px solid #3a3a3a; padding: 0px 10px`

**Observed:** Reads as a thin mechanical header, not a floating toolbar.

**Transfer:** Keep metadata and actions on the same strip where space allows.

#### Editorial ruled plane · level 0

**Only for:** editorial and organization pages

**Use:** Lists, chapter rows and technical proof.

**CSS:** `background: #000000; border-top: 1px solid rgba(230,230,230,0.3)`

**Observed:** Flat black rows separated by hairlines, without rounded wrappers.

**Transfer:** Use as the alternate editorial surface language, not as an extra card layer.

#### Diagonal contact field · level 0

**Only for:** editorial closing invitations

**Use:** Subtle pattern behind the closing statement.

**CSS:** `background-color: #000000; background-image: repeating-linear-gradient(135deg, rgba(230,230,230,0.08) 0px, rgba(230,230,230,0.08) 1px, rgba(0,0,0,0) 1px, rgba(0,0,0,0) 4px)`

**Observed:** Fine diagonal hatching fades into black across a wide inset contact area.

**Transfer:** Fade the pattern with a mask toward the lower and right edges; keep text untextured and legible.

## Components

### Utility rail

**Use:** Persistent desktop orientation and secondary actions.

**CSS:** `position: sticky; top: 0px; width: 270px; height: 900px; padding: 24px 20px; display: flex; flex-direction: column`

**Text style:** `index` — JetBrains Mono 400 · 14px/18px · tracking 0.06em · uppercase

**Observed:** Orange two-line identity at top, indented index beneath an arrow-like group marker, theme dots below the index, and legal/social/support groups pushed toward the bottom. It releases before the full-width ending.

**Transfer:** Use a short section index or product family list; keep the lower utility groups distinct from the main index.

### Index label

**Use:** Boxed destinations in the persistent rail and compact footer.

**CSS:** `display: inline-flex; color: #efefef; border: 1px solid #efefef; border-radius: 2.8px; padding: 0.6px 4.2px 0px`

**Text style:** `index` — JetBrains Mono 400 · 14px/18px · tracking 0.06em · uppercase

**Observed:** The outline hugs the word rather than stretching to a common width. Small orange counts sit outside the outline.

**Transfer:** Expose useful counts as adjacent text, not filled badges.

### Explore action

**Use:** Secondary action inside a specimen toolbar.

**CSS:** `display: inline-flex; color: #efefef; border: 1px solid #efefef; border-radius: 2.8px; padding: 0px 4.2px; height: 18px`

**Text style:** `control` — JetBrains Mono 400 · 14px/16px · tracking 0.04em · uppercase

**Observed:** Paired at the far right with the orange action; its natural width follows the label.

**Transfer:** Choose a direct verb such as Explore, Preview or Inspect.

### Orange action

**Use:** Primary conversion action in a toolbar.

**CSS:** `display: inline-flex; color: #ff4d00; border: 1px solid #ff4d00; border-radius: 2.8px; padding: 0px 4.2px; height: 18px`

**Text style:** `control` — JetBrains Mono 400 · 14px/16px · tracking 0.04em · uppercase

**Observed:** The stronger action is still only a fine outline, not a filled orange rectangle.

**Transfer:** Use for the new product's shortest conversion label.

### Specimen panel

**Use:** Large repeatable proof unit.

**CSS:** `display: flex; flex-direction: column; align-items: center; border: 1px solid #3a3a3a; border-radius: 8px; height: 362px; overflow: hidden; margin-bottom: 30px`

**Text style:** `display` — Basement Grotesque 900 · 120px/0.95 · tracking 0.01em · uppercase

**Observed:** Toolbar first, then a centered oversized specimen occupying most of the remaining area. The expanded two-word example breaks across two lines; other exhibits are single-line silhouettes.

**Transfer:** Keep each exhibit focused on one capability or artifact rather than filling the stage with multiple marketing cards.

### Specimen toolbar

**Use:** Technical context and manipulation for each proof stage.

**CSS:** `display: flex; align-items: center; justify-content: space-between; height: 36px; padding: 0px 10px; background: #121212; border-bottom: 1px solid #3a3a3a`

**Text style:** `control` — JetBrains Mono 400 · 14px/16px · tracking 0.04em · uppercase

**Observed:** Left: name or dropdown plus style/weight metadata. Middle: case toggles, cube-like mode icon and text modes. Right: paired outlined actions. Active text is white; inactive modes are gray.

**States:** Declared: hover on inactive mode text changes to #ff4d00; focus-visible behavior is unspecified.

**Transfer:** Only offer controls that affect the preview; otherwise replace the middle cluster with concise factual metadata.

### Split FAQ row

**Use:** Resolve objections without a vertical stack of expanding cards.

**CSS:** `border-top: 1px solid #efefef; padding: 12px 0px; color: #ff4d00`

**Text style:** `question` — Inter 400 · 18px/1.5

**Observed:** Questions form a ruled left column; the selected question is orange with a brighter top edge. Its uppercase mono answer appears simultaneously in the right column. Inactive questions and edges are muted.

**Transfer:** Keep questions short enough to scan and answers compact enough to remain alongside them.

### Utility text link

**Use:** Understated footer and support navigation.

**CSS:** `display: inline-flex; position: relative; color: #efefef; text-decoration: underline; text-underline-offset: 2px; transition: color 0.15s ease-in-out`

**Text style:** `footer-utility` — JetBrains Mono 400 · 12px/1.5 · tracking 0.06em · uppercase

**Observed:** Grouped under small arrow-prefixed labels; links stack tightly, with copyright separated into its own area.

**States:** Declared: hover changes color to #ff4d00; focus-visible behavior is unspecified.

**Transfer:** Use plain destinations and an address instead of promotional footer buttons.

### Editorial top navigation

**Only for:** editorial, organization and case-study pages

**Use:** Thin fixed navigation above full-width editorial content.

**CSS:** `position: fixed; top: 0px; height: 36px; width: 100%; display: flex; align-items: center; color: #e6e6e6; background-image: linear-gradient(#000000 1px, rgba(0,0,0,0) 1px), linear-gradient(90deg, #000000 1px, rgba(0,0,0,0.7) 1px); background-size: 2px 2px`

**Text style:** `editorial-nav` — Geist 600 · 12px/16px

**Observed:** Small identity left, centered horizontal destinations and a contact action at the right. Current destination is orange; tiny content counts attach to selected links.

**States:** Declared: hover changes link color to #ff4d00; focus-visible uses a transparent 2px outline with 2px outline-offset.

**Transfer:** Use this instead of the utility rail for an editorial site section, not in addition to it.

### Proof ledger row

**Only for:** editorial proof lists

**Use:** Dense, verifiable proof without decorative metric cards.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); gap: 8px; align-items: center; padding: 6px 0px; border-bottom: 1px solid rgba(230,230,230,0.2)`

**Text style:** `editorial-label` — Geist 600 · 24px/1 · tracking -0.03em

**Observed:** Larger distinction name at left, smaller project name in the center, right-aligned date. A muted label and exposed count introduce the list.

**Transfer:** Use release records, certifications or completed outcomes with real dates; retain the tabular rhythm.

### Newsletter input

**Only for:** editorial footers

**Use:** Low-profile email signup beneath a short invitation.

**CSS:** `height: 24px; max-width: 420px; padding: 0px 4px; background: #1a1a1a; border: 1px solid #1a1a1a; border-radius: 0px`

**Text style:** `editorial-body` — Geist 600 · 20px/1 · tracking -0.02em

**Observed:** A flat rectangular input spans a compact left-hand column; the text submit action sits below it rather than inside a big button.

**Transfer:** Keep the signup visually subordinate to the oversized navigation.

### Monumental contact link

**Only for:** editorial closing invitations

**Use:** Make contact itself the conversion element.

**CSS:** `color: #e6e6e6; background: #000000; display: inline-flex`

**Text style:** `editorial-statement` — Geist 600 · 76px/68px · tracking -0.04em

**Observed:** A large email address follows a two-line gray invitation. The whole group is inset by one grid column above the footer identity band.

**States:** Declared: hover is unspecified; focus-visible uses a transparent 2px outline with 2px outline-offset.

**Transfer:** Use a short address or equally direct text action at statement scale.

## Imagery and graphics

### Orange type machine

**Use:** Signature opening object occupying most of the main column.

**Observed:** A tightly packed field of extruded letters, numerals and symbols tumbles in varied orientations. Orange faces emerge from black shadow; dot and crosshatch textures make the forms feel printed and computational. The object is hard-clipped at the main column edges rather than isolated in a rounded card.

**Transfer:** Translate the new product into a pile of its initials, symbols or modular parts. The minimum version is a densely layered SVG collage of letter outlines and orange faces with visible black negative space.

**Build:** Use heavy letter paths and geometric modules, each with a front face in #ff4d00 and an offset darker side made from black overlays at 35–70% opacity. Rotate individual groups between opposing diagonals and overlap at several depths. Clip the composition to a wide 1146×630px stage. Add a repeating 3px black dot mask over faces and denser dots in shadow; avoid blur and smooth neon lighting.

### Wireframe closing word

**Use:** Signature monumental graphic near the ending, spanning the full page width.

**Observed:** Huge condensed capitals appear as a shallow three-dimensional extrusion drawn only in thin gray lines on black. The word almost touches both sides and extends far above the compact footer links.

**Transfer:** Use a short product initialism or a single forceful product word. Keep this word sculpture present even when the product has no photographic asset.

**Build:** Convert a bold condensed word to SVG paths, stretch to nearly the full width and roughly 550px visible height at desktop. Draw front and back contours with no fill and a 1px stroke in #747474, offset the back contour diagonally by about 40px horizontally and 45px vertically, and connect corresponding corners with fine straight segments. Let some top edges pass beyond the view box.

### Analog product object

**Only for:** product-detail openings

**Use:** A solitary artifact above descriptive copy and live previews.

**Observed:** A transparent plastic cassette floats on black, with reflective edges, red-and-black printed labeling, small screws and slight RGB fringing. It occupies the center of a broad 1122×477px region and leaves generous black around its silhouette.

**Transfer:** Use a tactile object associated with the product—a cartridge, tool, device or package—lit to reveal its material. A sharply cut-out still with subtle edge separation is sufficient; preserve isolation rather than adding a scene.

### Monochrome applied work

**Only for:** product-detail and editorial pages

**Use:** Show practical output between demonstrations or chapters.

**Observed:** Black-and-white street posters, architectural landscapes, studio equipment and sunlit interiors. Poster photographs fill wide bordered stages; editorial photographs use stark rectangular frames, deep shadows and hard natural light.

**Transfer:** Photograph the new product's real output in use, favoring structural lines and physical texture over polished stock-office scenes.

### Human documentary and portrait grid

**Only for:** organization and recruitment pages

**Use:** Give a serious directory a candid human counterweight.

**Observed:** Square monochrome photographs show play, conversation and shared studio activity. Portraits are tightly framed heads on dark backgrounds in a six-column grid with 8px gaps and fine edges; a large gray count sits beside the heading.

**Transfer:** Mix candid working-life scenes with consistently lit portraits. Keep the count typographic and exposed rather than enclosing it in a badge.

### Case-study media wall

**Only for:** case-study pages

**Use:** Make the delivered product the dominant proof.

**Observed:** Wide media alternates immersive product photographs, complete interface compositions, paired details and mobile screens. Warm cream, moss green, sunlight and amber occur inside the showcased project, while the surrounding shell stays black. The left metadata rail remains visually steady as the media scrolls.

**Transfer:** Preserve each project's own palette within its media. Use complete designed scenes rather than extracting project colors into the outer navigation.

### Icons

**Observed:** Small utility graphics rather than an illustrated icon system: 20px mixed-fill cube symbols in toolbars, 8×6px chevrons, bent-arrow group markers, 16px arrows and 16px circular theme swatches. Paint follows white, muted gray or orange state colors.

**Transfer:** Choose simple pixel-legible utility symbols. Use icons to indicate modes, direction and state; leave feature storytelling to the main objects.

## Section recipes

How recurring sections are built.

### First screen: Object-led workshop opening

**Observed:** A 270px sticky Utility rail anchors the left edge. The main region begins with a muted 14px uppercase ticker at the top, followed after 20px by the Orange type machine, 1146px wide and 630px high. Black is the back layer; orange extruded forms and their printed texture are the dominant foreground. There is no conventional hero headline over the object: its letterforms are the headline-scale event. Below, a 24px gap leads to a three-part mono caption line: a short introduction at left, a centered downward invitation, and a small linked credit at right. Within the first 900px the entire object and support line are visible, the rail's links remain available, and only the top of the first Specimen panel enters at the bottom; its large readable display sits below the fold.

**Transfer:** Lead with the new product's own sculptural symbols rather than a generic headline-and-device mockup. If there is no render, use the SVG collage build. Keep a real text statement available in the support copy and subsequent stage. Product-detail openings replace the collage with one Analog product object plus a description, technical facts and an outlined action. Editorial openings use a 98px title and asymmetric text/photo grid; case studies start with project identity and metadata beside immediate media.

**Avoid:** Do not place a centered white slogan over the sculpture, add a row of oversized filled CTA buttons, or imitate the empty space of an unrendered opening scene.

**Text style:** `display` — Basement Grotesque 900 · 120px/0.95 · tracking 0.01em · uppercase

### Exhibit sequence

**Observed:** Specimen panels repeat in one main-column stack, each 362px high with a 36px Specimen toolbar and 30px separation. Bright, centered output dominates; names and controls remain very small.

**Transfer:** Present independent product capabilities as exhibits. Vary the artifact silhouette while keeping identical panel furniture.

**Text style:** `display` — Basement Grotesque 900 · 120px/0.95 · tracking 0.01em · uppercase

### Objection desk

**Observed:** The page widens beyond the rail for a FAQ: 24px side insets, 100px top space, a small uppercase heading over a full-width rule, then two equal columns separated by 90px. Split FAQ rows sit left; the active answer sits right in compact uppercase mono.

**Transfer:** Use for compatibility, purchase, implementation or usage concerns. Preserve the question/answer contrast rather than expanding every answer at once.

**Text style:** `question` — Inter 400 · 18px/1.5

### Sculptural utility ending

**Observed:** The Wireframe closing word expands across the full canvas. Beneath it, compact groups distribute a two-column boxed index at left, copyright alongside, legal/social/support farther right and circular theme controls at the far edge. The persistent rail no longer competes with this full-width composition.

**Transfer:** End with a memorable word sculpture plus useful destinations. Adapt the index to the new product's offering instead of reproducing a catalog taxonomy.

**Text style:** `footer-utility` — JetBrains Mono 400 · 12px/1.5 · tracking 0.06em · uppercase

### Detail laboratory

**Only for:** product-detail pages

**Observed:** A single isolated object opens the page, followed by description, file-format/version facts and a small orange outline action. Adjustable specimen stages mix large and small type samples, interrupted by wide monochrome application photographs. A sticky single-glyph preview anchors a dense glyph inventory; a final two-column specification table and download link lead into the sculptural utility ending.

**Transfer:** Combine interactive proof, real applications, a browsable inventory and specifications. For a non-type product, replace glyphs with parts, features, formats or a compatibility catalog.

**Text style:** `detail-body` — Inter 400 · 18px/1.33

### Editorial heading and capability grid

**Only for:** editorial and organization pages

**Observed:** A 98px title sits asymmetrically across a twelve-column grid with 16px side insets. An editorial opening can pair it with a 343×515px monochrome photo and a 20px paragraph, or use three equal columns with two 38px manifesto paragraphs. Capability blocks use muted 24px labels above 38px descriptions, with thin rules and a 56px row gap.

**Transfer:** Use this quieter variant for explanation-heavy content. Keep substantial type blocks and asymmetry rather than converting everything into cards.

**Text style:** `editorial-title` — Geist 600 · 98px/88px · tracking -0.04em

### Statement proof and ledger

**Only for:** editorial proof pages

**Observed:** A centered 76px testimonial is followed by a 96px portrait and small attribution. A separate ledger begins with a muted label and inline count, then repeats Proof ledger rows with bright distinction titles, gray project details and right-aligned dates.

**Transfer:** Balance one memorable human statement with dense factual records. Use actual proof, not decorative percentages.

**Text style:** `editorial-statement` — Geist 600 · 76px/68px · tracking -0.04em

### Three-column human chapters

**Only for:** organization pages

**Observed:** Ruled chapter rows are 494px high, padded 16px vertically. Each uses a 76px statement at left, a 461px square monochrome photograph in the middle and 20px supporting copy at right. The chapter label remains above the sequence. A later directory pairs compact departmental lists with six columns of portraits and a large exposed count; recruitment rows align role, discipline, location and status.

**Transfer:** Apply the pattern to principles, processes or working methods only when the page's purpose is organizational. Keep open and unavailable opportunities visibly distinct.

**Text style:** `editorial-statement` — Geist 600 · 76px/68px · tracking -0.04em

### Project proof wall

**Only for:** case-study pages

**Observed:** A 36px fixed Editorial top navigation sits above a sticky 225px metadata rail. The broad right-hand wall begins with identity/palette media and product photography, then cycles complete interfaces, paired details, motion, checkout and mobile layouts. The nominal wide media frame is 1171×659px. Related-project links sit at the bottom of the rail.

**Transfer:** Introduce the problem and role in concise metadata, then let artifacts carry the narrative. Keep the client's visual design inside the media wall rather than restyling the black shell.

**Text style:** `editorial-meta` — Geist 600 · 13px/16px

### Editorial invitation and masthead ending

**Only for:** editorial, organization and case-study pages

**Observed:** Explanation-heavy pages close with an inset Diagonal contact field: muted 24px label, a 76px gray invitation and a bright address immediately below, with 64px top and 128px bottom padding. Then a nearly full-width solid expanded wordmark/year band sits above a hairline. The footer is 848px high overall: a long black interval separates the identity band from large stacked 38px navigation, a compact newsletter at lower left, and social/copyright at lower right. Case studies use the same footer without the preceding contact chapter.

**Transfer:** Use the product's short identity and current year for a bold masthead. Keep navigation, newsletter and direct contact readable without turning the footer into a boxed conversion banner.

**Text style:** `editorial-footer-link` — Geist 600 · 38px/0.89 · tracking -0.04em

## Page flow

**Storyline:** Object-led promise → tangible demonstrations → practical or human proof → questions or specifications → monumental identity and useful next steps.

### Product family or creative-tool landing page

1. **Promise** — Persistent utility index, clipped ticker and dominant orange sculptural object with compact support copy.
2. **Product demonstration** — Repeated framed exhibits with tiny controls and large contrasting output.
3. **Objection handling** — A split question-and-answer desk.
4. **Closing identity** — Full-width wireframe word followed by a compact multi-group utility footer.

**Transfer:** Keep the object, exhibit furniture and sculptural ending; vary the number and order of demonstrations to match the product.

### Detailed product evaluation

1. **Product introduction** — Isolated tactile artifact, concise positioning, facts and outline purchase action.
2. **Interactive proof** — Adjustable samples mixed with monochrome real-world applications.
3. **Breadth and compatibility** — Sticky preview beside a dense inventory, then a ruled specification table and download.
4. **Closing identity** — Wireframe word and compact index/utility links.

**Transfer:** Replace the font inventory with a relevant feature, component or compatibility library.

### Show completed work in depth

1. **Context** — Sticky compact metadata and narrative beside immediate project imagery.
2. **Demonstration** — Immersive product scenes, full interface compositions, paired details, video and mobile views.
3. **Next exploration** — Related links in the rail and a solid identity-band footer with navigation and signup.

**Transfer:** Keep the outer shell restrained while each project's media retains its own visual language.

### Explain expertise and establish credibility

1. **Positioning** — Asymmetric title/photo/paragraph introduction.
2. **Capability chapters** — Two-column ruled descriptions in oversized semibold type.
3. **Social proof** — Large testimonial followed by a dense dated ledger.
4. **Expanded offering** — Large statement with inline information link and broad monochrome photograph.
5. **Closing call** — Inset contact invitation, solid identity band, navigation and newsletter.

**Transfer:** Use capability language that connects craft to results; keep proof concrete and tabular.

### Explain a team and attract compatible contributors

1. **Belonging promise** — Title beside two substantial manifesto paragraphs.
2. **Working principles** — Ruled three-part statements, documentary photographs and explanatory copy.
3. **Human proof** — Department directory, portrait wall and exposed headcount.
4. **Opportunity** — Editorial recruitment photographs and a status-aware positions table.
5. **Closing call** — Large contact invitation and shared editorial footer.

**Transfer:** Retain the human/editorial variant for organization-focused pages, not as required landing-page content.

## Writing

Confident, craft-obsessed and knowingly irreverent. Technical facts are delivered plainly; the larger promises sound like makers talking to other makers rather than a corporate brand manifesto.

**Do not copy:** Do not reuse the studio's identity, logo, proprietary artwork, font names as product names, addresses, claims, award records, customer names, headcount, quotes or performance assertions. Examples illustrate voice only.

- **Addressing the reader:** Use we for the makers and you for the reader. Address the reader directly in invitations and useful warnings; use factual noun labels for technical metadata.
- **Rhythm:** Short imperative labels contrast with dense uppercase mono notes. Editorial paragraphs use fluent, compact sentences and occasional punchy fragments; display statements are short enough to feel like physical objects.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening ticker | A playful category rejection plus a practical provocation, joined by em dashes. | One repeating sentence chain | “not your average font shop — 95% of the web is made out of fonts, choose wisely” |
| Support line | Explain obsessive care, then connect it to the reader's next project. | One compact paragraph | “We created a distinguished & ever-evolving catalog of typefaces — every glyph has been carefully crafted with obsessive attention to detail, ready to use on your next big project.” |
| Display statement | Blunt maker confidence balanced with a practical outcome. | 4–8 words | “We make cool shit that performs.” |
| Primary action | A short direct verb; use personality in a secondary invitation rather than obscuring purchase intent. | 1–3 words | “Buy now”<br>“Check them all, downstairs.”<br>“Roll Me In” |
| Closing invitation | A collaborative outcome, immediately followed by direct contact. | One short sentence | “Let's make an impact together.” |

**Words and phrasing to use:** crafted; obsessive attention; next big project; make; performs; choose wisely; crew; cool; together

**Avoid:** synergistic solutions; seamless excellence; unlock your potential; industry-leading innovation; revolutionary ecosystem without proof

**Rules:**

- Let technical metadata remain terse: format, version, count and compatibility need no persuasive adjectives.
- Pair expressive claims with a visible artifact or factual proof.
- Keep mild profanity rare and intentional; confidence should still work without it.
- Use uppercase for the workshop's utility voice, sentence case for editorial explanation.
- Write labels that fit the compact outlines; do not inflate them into full-sentence CTAs.

## Do's and Don'ts

### Do

- Keep core stages at 8px corners with 1px #3a3a3a edges.
- Use 14px mono controls around 120px expanded specimens to preserve the severe scale contrast.
- Keep the desktop rail 270px wide and the main-column inset 24px.
- Use the 18px-high outline action pair in toolbars, with orange reserved for conversion.
- Retain the 8px dot rhythm as a barely visible stage texture.
- Keep footer utility links at 12px/18px while the closing word dominates the page.
- For editorial pages, use 16px edges and 12px gutters instead of importing the rail layout.
- Keep gray editorial headlines semibold with -0.04em tracking at 38px and above.

### Don't

- Do not use pill-shaped CTAs as the default; the core action radius is 2.8px.
- Do not add soft card shadows; the interface separates through hairlines and black space.
- Do not spread orange across ordinary section backgrounds; its broad fill belongs to the opening sculpture.
- Do not set workshop labels in proportional sans; the 14px mono is part of the control language.
- Do not round all photographs to the stage's 8px radius; editorial documentary images are rectangular.
- Do not use the exhibited novelty typefaces for body copy or navigation.
- Do not turn exposed counts into colorful filled badges; keep them adjacent to labels or headings.
- Do not borrow the warm cream and amber of a showcased project's interface for the outer marketing shell.

## Motion and responsive

### Motion

**Observed:**

- Core outlined controls declare background-color, border-color and color transitions of 0.15s ease-in-out. Utility links declare color 0.15s ease-in-out.
- The opening ticker is horizontally translated within a clipped container; the visual language includes animated mode/object demonstrations.
- The editorial top bar declares transform 0.3s cubic-bezier(0.4,0,0.2,1). Navigation links declare calc(.3s / 5) linear transitions.
- Orange is the declared hover color for inactive modes, utility links and editorial navigation.

**Transfer:**

- Keep object and specimen motion inside the framed stages, while the utility rail remains a stable point of orientation.
- Use the clipped ticker as a continuous strip, not as large animated headline copy.
- Keep interface transitions short and utilitarian rather than adding elastic card movement.

**Unknown:**

- Ticker duration, object animation choreography, scroll reveal timing and mode transitions are not established.
- The editorial Human/Machine switch has a distinct alternate-mode role; its destination behavior is not specified here.

### Responsive

**Observed:**

- Core CSS includes width breakpoints at 600px, 900px, 1024px, 1280px, 1440px and 2560px.
- Editorial CSS includes 400px, 640px, 768px, 1024px, 1280px, 1536px and 1920px breakpoints. Desktop classes switch several columns and navigation visibility at 1024px.
- Core mono type and selected spacings use max() formulas rather than uniform proportional shrinking.

**Transfer:**

- On narrow screens, adapt the index into a compact accessible navigation and let stages fill the width; keep the object-led hierarchy and tiny outlined action language.
- Stack the question and active answer together, and stack editorial chapter columns in statement/photo/explanation reading order.
- Fit the closing word within the screen while retaining its extrusion and thin-line construction; avoid horizontal overflow in useful links.

**Unknown:**

- Exact mobile rail behavior, artwork framing, footer composition and small-screen type sizes are not established; the stacking guidance is a recommended adaptation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
