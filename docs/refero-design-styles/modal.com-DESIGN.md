# Modal — luminous glyph machinery

## Overview

A near-black, green-tinted technical world with surprisingly modest grotesk headlines and luminous sculptures made of tiny symbols. Pale gray-green proof sections interrupt the darkness, while compact controls and finely ruled diagrams give the page an engineering character. It suits developer tools and complex platforms that need both visual wonder and credible operational detail; interface vignettes carry more weight than lifestyle imagery.

### Essentials

- Headlines speak softly while the machine glows: ABC Diatype at 44px/48px, weight 400, normal tracking, with only the decisive phrase in #7fee64.
- The opening is a centered promise above a luminous object, not a giant typographic billboard: 48px top padding, a 403.2px support measure, 36px actions, and a glyph-built sculpture occupying the lower half of the first screen.
- Conversion controls are miniature capsules: 48px radius, 14px/24px text, 6px 16px padding and 8px between a pale primary and translucent secondary action.
- Darkness owns most of the journey: #040804 canvas, #10120f media stages and #131412 chapter bands; green is concentrated in words, small labels and symbolic light rather than whole feature backgrounds.
- Technical imagery is constructed, not pasted: 7px edged stages hold floating dark UI, fine wireframe diagrams or thousands of tiny green glyphs; include a glyph sculpture and an echo of its light near the closing call, using a simple geometric glyph lattice when no product object exists.
- Proof gets a daylight reversal: #e3e5e1 full-width bands, #daded7 inset panels, dark 28px/36px quotations and monochrome logo tiles give a distinct release from the black technical chapters.
- The ending is a second product stage: a 640px dark closing call pairs a two-tone 44px headline on the left with luminous glyph art on the right, then a 527px footer with five compact link columns and a faint bottom glow.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric leaf | `#7fee64` | `--color-green` | accent, text, background | Key headline phrases, small labels, selection, focus rings and luminous glyph art; the thin announcement strip is the principal solid green fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep leaf | `#124f11` | `--color-light-accent` | text, accent | Small labels and focus rings within pale proof and editorial bands. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale mineral | `#e3e5e1` | `--color-primary` | text, background, action | Primary dark-theme text, primary button fill, and light proof bands. |
| Announcement black | `#000000` | `--color-announcement-ink` | text | Text in the bright green announcement strip. |
| Green black | `#040804` | `--color-canvas` | background | Default page canvas and closing field. |
| Forest ink | `#10120f` | `--color-ink` | text, surface | Light-theme text and dark demonstration stages. |
| Action glass | `#111411` | `--color-glass` | surface | Visible white at 5% over #040804 for secondary capsules and small controls. |
| Chapter charcoal | `#131412` | `--color-band` | background | Alternate technical chapter bands. |
| Stage edge | `#171916` | `--color-edge` | border | Visible white at 3% over #10120f for demonstration outlines. |
| Technical rule | `#1d211d` | `--color-rule` | border | Visible white at 10% over #040804 for tables and vertical column divisions. |
| Muted gray green | `#a8aba6` | `--color-secondary` | text, link | Support paragraphs, navigation and captions. |
| Inset sage gray | `#daded7` | `--color-proof` | surface | Quotation panels and monochrome logo tiles on light bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and careers pages | Pale mint | `#def0dd` | `--color-career` | background | Long inset directory panel. |
| pricing pages | Plan charcoal | `#151714` | `--color-plan` | surface | Pricing plan card fill. |
| company and careers pages | Directory ink | `#242424` | `--color-career-text` | text | Job titles and locations on mint. |
| company and careers pages | Moss edge | `#485346` | `--color-career-edge` | border | Outline of the pale mint directory. |

## Typography

- **ABC Diatype** — All marketing headings, body copy, controls and captions. Matter-of-fact contemporary grotesk with open counters and restrained regular-weight display text. OpenType features: "cv11". If unavailable, use **Inter**. Use 400 and 500; preserve normal tracking and the compact headline measure. Font stack: "ABC Diatype", "Inter", Arial, ui-sans-serif, system-ui, sans-serif.
- **DM Mono** — Technical figure numbering, axes and command labels. Small, evenly spaced monospace with lightly expanded tracking. Font stack: "DM Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ABC Diatype | 400 | 44px | 48px | normal | Hero promise and closing call; highlight one phrase without changing weight. |
| heading | ABC Diatype | 400 | 37px | 44px | normal | Major section leads and large plan prices. |
| heading-small | ABC Diatype | 400 | 28px | 36px | normal | Feature chapter headings and large quotations. |
| body | ABC Diatype | 400 | 16px | 1.5 | normal | Hero support and substantive introductory paragraphs. |
| body-medium | ABC Diatype | 500 | 16px | 1.5 | normal | Editorial card titles. |
| regular | ABC Diatype | 400 | 14px | 24px | normal | Navigation, secondary buttons, table labels and compact descriptions. |
| button | ABC Diatype | 500 | 14px | 24px | normal | Primary capsule labels. |
| announcement | ABC Diatype | 500 | 14px | 20px | normal | Thin green announcement strip. |
| caption | ABC Diatype | 400 | 13px | 20px | 0.01em | Small feature summaries, attribution details and conversion footnotes. |
| eyebrow | ABC Diatype | 500 | 12px | 20px | 0.03em | Sentence-case section markers paired with a tiny icon. |
| technical | DM Mono | 400 | 12px | 20px | 0.03em, features "ss02" | Figure numbers and chart axes; commands within demonstrations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company pages | company-display | ABC Diatype | 500 | 64px | 1 | normal, features "ss01" | Centered editorial opening. |
| careers pages | directory-heading | ABC Diatype | 400 | 54px | 1.1 | normal, features "ss01" | Main directory title on mint. |
| company pages | company-heading | ABC Diatype | 400 | 40px | 1.1 | normal, features "ss01" | Editorial section leads. |
| pricing and billing sections | question | ABC Diatype | 400 | 21px | 28px | normal | FAQ questions and resource-cost figures. |
| careers pages | directory-row | ABC Diatype | 400 | 20px | 1.3 | normal, features "ss01" | Job titles and location columns. |

**Notes:**

- Regular weight and normal tracking persist even in display text; color, line breaks and scale carry the hierarchy rather than boldness.
- Keep marketing copy in the sans family. Monospace belongs to technical annotations, not every eyebrow.
- The default feature heading can be smaller than the major section lead; quotations share the 28px feature recipe rather than becoming oversized pull quotes.

## Layout

**Density:** Airy chapter structure with compact internal controls: 144px section padding surrounds 12px–32px text and action gaps.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Icon-to-label gaps. |
| 8px | Paired actions and small title/support groups. |
| 12px | Paragraph groups and footer link lists. |
| 16px | Eyebrow-to-heading gap and column-rule inset. |
| 20px | Desktop grid gutters. |
| 24px | Card content groups and image-to-title gap. |
| 32px | Support-to-actions gap. |
| 48px | Proof panel padding and footer group separation. |
| 64px | Desktop outer content inset. |
| 72px | Heading-to-card-grid gap and footer vertical padding. |
| 80px | Major heading-to-content gap and FAQ lead separation. |
| 144px | Standard desktop chapter padding and product feature-row separation. |
| 200px | Spacing between long-form capability demonstrations. |

### Containers and grids

- **marketing container**: max width 1546px · side padding 64px. Centered desktop shell; at 1440px the content is 1312px wide.
- **structural grid**: 24 columns · gap 20px. Underlying desktop grid for narrow headings, half-width demonstrations and asymmetric chapter arrangements.
- **three column cards**: 3 columns · gap 20px. 424px cards across the desktop content width; used for editorial, enterprise and plan comparisons.
- **split demonstration**: 2 columns · gap 20px. 646px media stage beside explanation; inset text can narrow to 459px or 508px.
- **company shell** (only for company pages): max width 1400px · side padding 48px. Slightly wider editorial shell, with mint directory extending to the shell edges.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action capsules | 48px |
|  | media and proof panels | 7px |
|  | small badges | 4px |
| product demonstrations | floating interface panels | 10px |
| careers pages | directory panel | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | primary inset | `inset 0px 0px 0px 1px rgba(0,0,0,0.05)` | Subtle definition of pale primary capsules. |
| product demonstrations | floating interface | `0px 1px 3px rgba(4,8,4,0.5), 0px 2px 32px rgba(4,8,4,0.6)` | Floating command chips and interface fragments only. |

### Surfaces

#### Canvas · level 0

**Use:** Main marketing field.

**CSS:** `background: #040804; color: #e3e5e1`

**Observed:** Almost black with a green cast rather than neutral gray.

**Transfer:** Keep visual separation subtle; let light proof bands provide the strong contrast.

#### Chapter band · level 0

**Use:** Broad technical explanations.

**CSS:** `background: #131412`

**Observed:** A restrained step lighter than the main canvas.

**Transfer:** Apply to a complete chapter rather than alternating every small block.

#### Demonstration stage · level 1

**Use:** Framing diagrams and product vignettes.

**CSS:** `background: #10120f; border: 1px solid rgba(255,255,255,0.03); border-radius: 7px; overflow: hidden`

**Observed:** Broad, almost flat stage; the meaningful object floats inside instead of filling the frame edge-to-edge.

**Transfer:** Show one working mechanism per stage.

#### Daylight proof band · level 0

**Use:** Customer proof and editorial material.

**CSS:** `background: #e3e5e1; color: #10120f`

**Observed:** A full-width light reversal, not a white card on black.

**Transfer:** Group trust-building content into a coherent light chapter.

#### Proof inset · level 1

**Use:** Quotation panels and logo tiles.

**CSS:** `background: #daded7; border: 1px solid rgba(0,0,0,0.03); border-radius: 7px`

**Observed:** Slightly darker than the surrounding pale field, with no heavy drop shadow.

**Transfer:** Use for a large editorial quote and a disciplined tile grid.

#### Bottom atmosphere · level 0

**Use:** Subtle lift underneath the hero and footer.

**CSS:** `background: radial-gradient(50% 100% at 50% 100%, rgba(20,26,19,0.7) 0%, rgba(20,26,19,0) 100%); mix-blend-mode: plus-lighter`

**Observed:** Low-contrast green-black light at the bottom edge, distinct from the bright glyph sculpture.

**Transfer:** Layer behind content and keep exact glow stops secondary to the soft effect.

#### Mint directory · level 1

**Only for:** careers pages

**Use:** Dense browsable listings.

**CSS:** `background: #def0dd; border: 1px solid #485346; border-radius: 8px; padding: 64px 0px`

**Observed:** Long inset light panel bounded by dark surroundings.

**Transfer:** Reserve this mint variant for people-oriented directories rather than default technical proof.

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #e3e5e1; color: #10120f; border-radius: 48px; padding: 6px 16px; height: 36px; box-shadow: inset 0px 0px 0px 1px rgba(0,0,0,0.05)`

**Text style:** `button` — ABC Diatype 500 · 14px/24px

**Observed:** Text-only capsule paired with a secondary action. Navigation and compact program cards use a 32px-high version with 4px 12px padding.

**States:** Declared: hover background #040804 and text white; focus-visible 2px solid #7fee64 outline with 2px offset.

### Secondary button

**Use:** Contact, documentation or secondary conversion.

**CSS:** `background: rgba(255,255,255,0.05); color: #e3e5e1; border-radius: 48px; padding: 6px 16px; height: 36px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.05); backdrop-filter: blur(6px)`

**Text style:** `regular` — ABC Diatype 400 · 14px/24px

**Observed:** Visually recedes beside the pale primary capsule.

**States:** Declared: hover background rgba(0,0,0,0.0314) and color #040804; focus-visible 2px solid #7fee64 outline with 2px offset.

### Navigation bar

**Use:** Persistent global wayfinding.

**CSS:** `background: rgba(4,8,4,0.9); border-bottom: 1px solid rgba(255,255,255,0.05); backdrop-filter: blur(20px); height: 65px`

**Text style:** `regular` — ABC Diatype 400 · 14px/24px

**Observed:** Sticky top header with a 64px inner row: compact symbol at left, centered links, login and compact Primary button at right. The light chapter switches navigation to dark text and a dark signup capsule.

**Transfer:** Keep the center navigation compact and the brand mark smaller than the page headline.

### Announcement strip

**Use:** A timely product release above navigation.

**CSS:** `background: #7fee64; color: #000000; padding: 8px 16px; display: flex; justify-content: center`

**Text style:** `announcement` — ABC Diatype 500 · 14px/20px

**Observed:** 36px strip with one short sentence and inline underlined link ending in a right arrow; it scrolls away while the header remains.

### Footer link

**Use:** Grouped secondary destinations.

**CSS:** `color: #a8aba6; display: inline-flex; align-items: center; gap: 6px`

**Text style:** `regular` — ABC Diatype 400 · 14px/24px

**Observed:** Five categorized columns, with 24px from category title to links and 12px between links. Brand wordmark occupies a separate wider area to the left.

**States:** Declared: hover color #e3e5e1; focus-visible 2px solid #7fee64 outline with 2px offset.

### Demonstration panel

**Use:** A compact visual explanation of product behavior.

**CSS:** `background: #10120f; border: 1px solid rgba(255,255,255,0.03); border-radius: 7px; position: relative; overflow: hidden`

**Observed:** A desktop stage around 646px by 499px, holding a centered command chip, orbiting icons, a matrix of resource tiles or a small interface. Its margins remain dark rather than showing a browser chrome wrapper.

**Transfer:** Use a single essential operation rendered as a believable visual mechanism.

### Quote panel

**Use:** Prominent customer or expert proof.

**CSS:** `background: #daded7; border: 1px solid rgba(0,0,0,0.03); border-radius: 7px; padding: 48px; display: flex; gap: 20px; overflow: clip`

**Text style:** `heading-small` — ABC Diatype 400 · 28px/36px

**Observed:** Quotation and small attribution occupy the left half; a large monochrome customer symbol sits amid sparse geometric glyphs on the right. Small previous/next circles sit above the panel.

**Transfer:** Use a real attributed statement with a meaningful emblem or abstract counterpart.

### Editorial card

**Use:** Updates and case-study links on a light field.

**CSS:** `display: flex; flex-direction: column; gap: 24px; border-radius: 7px`

**Text style:** `body-medium` — ABC Diatype 500 · 16px/1.5

**Observed:** 16:9 dark artwork above a two-line title, brief description and small category badge; three equal columns. Text sits slightly inset from the media edge.

**States:** Declared: focus-visible 2px solid #124f11 outline with 2px offset.

### Plan card

**Only for:** pricing pages

**Use:** Compare commercial tiers.

**CSS:** `background: #151714; border: 1px solid rgba(255,255,255,0.05); border-radius: 7px; padding: 24px 32px; display: flex; flex-direction: column; justify-content: space-between; gap: 24px`

**Text style:** `regular` — ABC Diatype 400 · 14px/24px

**Observed:** Tier symbol and name, brief audience description, 37px price, ruled checklist and a full-width capsule anchored at the bottom. The entry plan gets the pale Primary button while upgrade and enterprise use Secondary button.

**Transfer:** Maintain aligned action baselines even when benefit counts differ.

### FAQ row

**Only for:** pricing pages

**Use:** Answer billing and purchase objections.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 24px; padding: 20px 0px; border-radius: 4px`

**Text style:** `question` — ABC Diatype 400 · 21px/28px

**Observed:** Full-width question button with a thin plus at the far right; enclosing rows have 1px white-at-10% bottom rules. The closed row is 69px including its rule.

**States:** Declared: focus-visible 2px solid #7fee64 outline with 2px offset.

## Imagery and graphics

### Glyph light sculpture

**Use:** Signature hero object and closing echo.

**Observed:** An isometric open cube is assembled from dense tiny circles, hexagons, stars, asterisks and branching symbols. Bright green ridges and occasional yellow-green highlights illuminate its volume; ghosted symbol trails extend diagonally into black. Product-specific art becomes stacked upright slabs in the same material. The object is much larger than the headline, but darkness separates it from the copy.

**Transfer:** Make a simple geometric model of the product's core operation; if no literal object exists, use an open cube, layered planes or linked volumes made from glyphs. Preserve the particulate surface and fading trails rather than substituting glossy solid 3D.

**Build:** In SVG or canvas, project an isometric cube or 3 parallel planes into a roughly 700px stage. Sample their edges and planes on a 7px–10px lattice; stamp 3px–6px circles, hexagons, stars and Y shapes. Use #7fee64 at varied alpha from 0.15 to 1 along lit edges, low-alpha #a8aba6 in receding trails and sparse pale highlight glyphs. Duplicate bright edges behind with 12px–24px blur at low opacity; fade outer trails with a radial mask. Keep black voids between planes.

### Technical wireframes

**Use:** Numbered capability columns.

**Observed:** Thin gray line geometry on charcoal: circle with radial spokes, stacked isometric planes and nested cube/hexagon. Dotted construction lines and a few colored vertex markers create diagrammatic depth without solid shading.

**Transfer:** Translate capabilities into simple geometric relationships; minimum acceptable art is a clean SVG diagram with a few purposeful vertices.

**Build:** Use a roughly 407px square SVG. Draw centered circles or isometric polygons with 1px gray strokes at about 40% opacity; add dotted back edges at 15% and 4px vertex markers. Limit each diagram to one accent hue and leave generous negative space.

### Floating product vignettes

**Use:** Capability demonstrations and enterprise assurance.

**Observed:** Dark controls, terminal output, member activity or metrics float on slightly lighter dark stages. Inner panels have 10px corners, faint top-edge light and green-black shadows. Terminal and charts are selectively readable rather than presented as full desktop applications.

**Transfer:** Show a realistic fragment with enough labels to explain the benefit; do not force unrelated products into code-terminal imagery.

### Proof glyph field

**Use:** Light quotation panels.

**Observed:** A large black customer symbol sits in a loose field of low-contrast cubes, diamonds, asterisks and Y forms; a small subset carries the customer's accent color. Text remains clear in the other half.

**Transfer:** Use the relevant customer's approved symbol or an abstract geometric emblem and keep decorative marks subordinate.

**Build:** Create an SVG layer restricted to the art half, distributing 12px–24px geometric symbols on a loose 48px lattice. Use dark ink at 3%–15% alpha, with a few higher-opacity accents; leave a clear central area behind the emblem.

### Editorial thumbnails

**Use:** Three-column updates.

**Observed:** Wide dark images mix soft green light, floating interface labels, glyph-surface macro views and restrained typography. Their contrast remains strong on the pale surrounding field.

**Transfer:** Make each thumbnail explain its story, but share dark backing and green technical atmosphere across the group.

### Human photography and maps

**Only for:** company pages

**Use:** Humanize the technical brand.

**Observed:** A centered founders portrait is framed as a simple wide photograph with a tiny caption; team scenes use natural light and 480px by 270px carousel images. Location cards use luminous green street maps with a black gradient rising from the bottom behind white place labels. Small pale line-art mascots sit outside the opening photograph.

**Transfer:** Use candid working portraits and real locations. Keep playful line drawings small, away from primary text.

**Build:** For a location card, render simplified street paths in pale green over deeper green land and water shapes; overlay a transparent-to-#040804 bottom gradient, then align place and address at the lower left with 24px inset.

### Icons

**Observed:** Most interface and feature icons are 16px outline SVGs with 2px round strokes in muted gray or pale primary text. Section markers are tiny green symbols, often in a 20px tinted square. Diagram icons and social marks can be solid; footer socials sit inside 26px circles.

**Transfer:** Choose simple cube, layers, branching, bolt and operational symbols with consistent stroke weight; do not enlarge them into colorful feature illustrations.

## Section recipes

How recurring sections are built.

### First screen: Luminous centered opening

**Observed:** A 36px Announcement strip and 65px Navigation bar precede a centered 44px Display headline, beginning 48px into the hero. It occupies about 587px of width, with the decisive final phrase green on the same baseline. A centered 403.2px support line sits 16px below the heading group; paired Primary button and Secondary button follow after 32px. Behind everything lies Canvas and Bottom atmosphere; beneath the controls a large Glyph light sculpture fills most of the lower first screen, extending toward its bottom. Within the first 900px the header, promise, support, actions and nearly the full luminous cube are visible. The trust strip is below the fold, near the base of the 1029px hero.

**Transfer:** Keep copy compact enough that the object remains the visual event. Use a geometric glyph lattice when no literal product object exists. A focused product opening instead uses left-aligned copy and actions beside the sculpture, with a small green product label. Pricing opens with a centered two-line promise followed by a narrow resource-cost list. Company storytelling opens with the larger company-display recipe and a centered portrait.

**Avoid:** Do not replace the object with a full-bleed stock photo, giant gradient headline, solid neon blob or large dashboard wedged immediately below the navigation.

**Text style:** `display` — ABC Diatype 400 · 44px/48px

### Marked chapter lead

**Observed:** A 12px green Eyebrow with tiny icon sits 16px above a 37px Heading. Support or a Primary button follows after 24px–32px, while the main grid starts 72px–80px later. Chapters generally have 144px top and bottom padding.

**Transfer:** Use labels to name a category and headings to state the benefit rather than repeating the label.

**Text style:** `heading` — ABC Diatype 400 · 37px/44px

### Capability demonstration chapters

**Observed:** A slim left navigation rail accompanies a narrower text column and a 646px Demonstration panel on the right. Each chapter has a small 16px lead, muted support, a two-column list of 13px feature summaries and a low-positioned Primary button. Long capability chapters are separated by 200px.

**Transfer:** Use the rail for multiple related capabilities, or omit the rail for a focused explanation while retaining the split visual stage.

### Alternating product explanation

**Observed:** A 646px by 536px dark stage alternates sides against a 28px feature heading, three short icon-led benefits and one capsule action. Text can be inset to a 459px measure. Rows are separated by 144px.

**Transfer:** Explain one user-visible advantage per row, with a believable interface fragment as visual proof.

**Text style:** `heading-small` — ABC Diatype 400 · 28px/36px

### Numbered technical triptych

**Observed:** Chapter band holds three 424px columns separated by 1px white-at-10% left rules and 16px inner insets. Each starts with a 12px mono numeral, then a large Technical wireframe, a 16px title and a 14px description.

**Transfer:** Use numbers for a small conceptual set; diagrams should have a consistent scale and line grammar.

### Expansive data field

**Observed:** A wide dark chapter places a heading and action at upper left over a large dot-and-glyph world map. Small colored region labels punctuate it; four rule-led feature descriptions sit below. The map is roughly 1310px by 701px.

**Transfer:** For other global or network products use a meaningful topology or spatial distribution, preserving the faint symbol field and tiny data labels.

### Light proof chapter

**Observed:** Daylight proof band contains Quote panel above four-column monochrome logo tiles of 313px by 144px, with 20px gutters. A related product variant uses one full-width quote followed by two half-width quotes.

**Transfer:** Include genuine qualitative proof and a compact visual roster; let the pale chapter interrupt the dark narrative.

### Editorial continuation

**Observed:** Daylight proof band continues into a 37px section title and three Editorial cards, with 72px between heading and media. Images are about 422px by 237px.

**Transfer:** Offer next reading without breaking the unified pale proof field.

### Resource pricing and quantified comparison

**Observed:** A 646px-wide rate list uses 14px resource names, 21px prices, thin rules and a capsule unit toggle. Full-width Plan cards follow elsewhere. Quantified explanation uses two side-by-side demand charts with identical axes, gray lines, red overload versus green utilized area, 12px mono axes and 37px cost totals.

**Transfer:** Separate consumption rates, tier entitlements and economic explanation; show the same underlying data in comparisons.

**Text style:** `question` — ABC Diatype 400 · 21px/28px

### Mint directory

**Observed:** A broad Mint directory begins with a 54px title and outlined filter pills. Categorized 72px rows align a 20px title, location column and small outlined action, separated by thin green rules.

**Transfer:** Use this scoped variant for a long people-oriented listing; filters should directly describe the contents.

**Text style:** `directory-heading` — ABC Diatype 400 · 54px/1.1

### Closing light echo and footer

**Observed:** A 640px Canvas stage aligns a two-line 44px closing promise to the left, with the second phrase green, actions 28px below and a 13px incentive line another 32px down. Glyph light sculpture occupies the right side and fades into the shared black ground. Footer follows with 72px vertical padding, brand wordmark at left and five link columns at right. A fine horizontal rule separates the social, legal and copyright row; Bottom atmosphere adds faint green light below.

**Transfer:** Close with a concrete time-to-value promise and truthful incentive or reassurance; preserve the sculpture echo and the spacious compact-link footer.

**Text style:** `display` — ABC Diatype 400 · 44px/48px

## Page flow

**Storyline:** Promise → working mechanisms → technical credibility → proof or commercial detail → low-friction closing call → categorized footer.

### Broad platform introduction

1. **Promise** — Centered two-tone headline over a luminous glyph object and paired actions.
2. **Capability chapters** — Rail-led demonstrations followed by numbered wireframes and an expansive network field.
3. **Operational proof** — Three product-interface assurance cards.
4. **Social proof** — Pale quotation, logo tiles and editorial continuation.
5. **Closing call** — Left-aligned time-to-value promise with glyph echo, then five-column footer.

**Transfer:** Move from an accessible promise into increasingly specific mechanisms, then let proof reverse the theme before the closing return to darkness.

### Focused product landing

1. **Promise** — Left copy, product label and glyph-built slab object.
2. **Product demonstration** — Alternating stage-and-benefit rows with small icon summaries.
3. **Pricing** — Dark rate section with unit toggle.
4. **Social proof** — One wide quotation and two supporting quotations on pale gray-green.
5. **Continuation** — Three editorial cards.
6. **Closing call** — Shared glyph closing and categorized footer.

**Transfer:** Focus the mechanism chapters on one workflow rather than retelling the whole platform.

### Commercial decision support

1. **Promise** — Centered value statement followed directly by resource rates.
2. **Pricing** — Three plan cards, purchasing options and usage explanation.
3. **Quantified proof** — Paired demand charts and large cost totals.
4. **Comparison** — Dense four-column feature table with ruled rows.
5. **Objection handling** — Full-width FAQ rows.
6. **Closing call** — Shared dark closing stage and footer.

**Transfer:** Prioritize billing clarity and distinctions; retain the visual signature without letting decoration obstruct comparison.

### Company trust and recruitment

1. **Human introduction** — Large centered promise, portrait, tiny caption and narrative paragraphs with small line-art characters.
2. **Institutional proof** — Investor marks, green location maps and ruled contact cells.
3. **Culture** — Wide natural-light team photo carousel.
4. **Directory** — Long mint panel of categorized roles and outlined actions.
5. **Practical information** — Legal information returns to the dark canvas.
6. **Closing call** — Shared product conversion scene and footer rather than a recruitment-only ending.

**Transfer:** Keep human content warmer and more editorial, with the mint directory scoped to recruitment.

## Writing

Confident engineering language with a small streak of magic and conversational wit. Benefits are immediately connected to actual mechanisms, and technical nouns are welcome when they clarify the promise.

**Do not copy:** Do not reuse Modal's name, logo, proprietary illustrations, customer marks, quotations, funding totals, pricing, credits, performance figures or product claims. Replace all examples with verified material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for company narrative and the product name for concrete capabilities.
- **Rhythm:** Short benefit headlines, one- or two-sentence support blocks, then compact feature explanations. Warmth comes from plain language rather than repeated exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A direct category statement with a short colored outcome phrase. | 5–9 words | “The platform for production AI” |
| Section lead | A technical category with a human benefit or restrained wordplay. | 5–10 words | “Container infrastructure that won’t box you in”<br>“Capacity that scales with your ambition” |
| Support | Name the audience and the concrete operation in one sentence. | 12–30 words | “Cloud infrastructure for teams that develop, train, and serve AI applications at scale.” |
| Feature heading | A plain operational advantage with a measurable implication. | 2–7 words | “Swap GPUs on the fly”<br>“Automatic idle shutdown” |
| Primary action | Small direct verb phrase. | 2–4 words | “Get started”<br>“Read the docs” |
| Closing promise | Short time-to-value statement paired with the thing the reader can make. | 5–8 words | “Ship your first app in minutes” |
| Objection handling | A literal question someone evaluating costs would ask. | 5–14 words | “What counts as billable time?” |

**Words and phrasing to use:** build; ship; iterate; scale; on-demand; by the second; from experiment to production; only pay for what you use

**Avoid:** revolutionary ecosystem; unleash limitless potential; enterprise-grade magic in every sentence; vague superlatives without mechanisms

**Rules:**

- Follow an evocative promise with an operational explanation.
- Use exact figures only when the new product can substantiate them.
- Let technical labels be short nouns and headings express outcomes.
- Use occasional wit in prominent headings, not in every table row.
- Prefer specific friction removed over a long list of abstract advantages.

## Do's and Don'ts

### Do

- Keep the default hero at 44px/48px and weight 400.
- Use 20px desktop gutters across split stages and three-column grids.
- Retain 7px corners on media stages and proof panels.
- Let small 36px capsule actions sit inside much larger areas of negative space.
- Use 144px chapter padding to distinguish the airy narrative from dense internal diagrams.
- Make the pale proof field a full-width theme reversal with dark ink.
- Carry the tiny-symbol light material into the closing stage.
- Keep technical numerals at 12px DM Mono with 0.03em tracking.

### Don't

- Do not turn normal-tracked regular headings into tightly tracked bold display type.
- Do not use pure white as the main page field; the light mode is gray-green #e3e5e1.
- Do not make green the default button fill; primary capsules are pale mineral.
- Do not give ordinary content cards 24px corners or heavy floating shadows.
- Do not apply mint directory colors to every technical feature chapter.
- Do not use monospace for all section labels; core eyebrows are sans.
- Do not wrap every product vignette in a generic browser-window frame.
- Do not replace the compact five-column footer with a giant decorative wordmark wall.

## Motion and responsive

### Motion

**Observed:**

- Declared action color transitions use 0.15s cubic-bezier(.4,0,.2,1); the header theme transition uses 0.25s with the same curve.
- Declared glow pulse is 3.2s ease-in-out infinite; marquee is 90s linear infinite; command-press animation is 0.56s cubic-bezier(.4,0,.2,1).
- Sticky navigation remains visible during scrolling and changes contrast over the pale chapters.

**Transfer:**

- Keep kinetic emphasis inside glyph fields and working-mechanism stages, leaving body copy visually stable.
- Retain the short capsule color transition and the slower, ambient quality of symbolic light.

**Unknown:**

- Scroll animation triggers, full sculpture motion path and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Desktop uses a 24-column structural grid; class declarations indicate single-column product rows at smaller widths.
- Footer grid declarations indicate two columns, then three, then five; navigation center links and account actions are hidden below a larger tablet tier.
- The mint directory gains side borders and rounded corners at 1400px.

**Transfer:**

- On narrow screens, stack promise and glyph stage without losing the luminous object; place paired actions directly beneath support.
- Collapse alternating product rows to one readable story per block and preserve dark stage backing.
- Keep diagram labels legible rather than proportionally shrinking every technical detail.

**Unknown:**

- Exact viewport thresholds for most named responsive tiers and mobile sculpture framing are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
