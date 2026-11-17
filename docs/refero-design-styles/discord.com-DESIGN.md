# Discord — playful worlds in orbit

## Overview

An exuberant dark style that makes software feel like a place to spend time, rather than a tool to operate. Broad, chunky grotesk headlines sit in blue and violet atmospheres, with luminous product scenes, toy-like objects and enormous soft-cornered frames. The pacing is spacious and theatrical even when the content is practical; institutional and business variants trade the continuous blue world for black stages and concentrated pools of color.

### Essentials

- Headlines behave like compact word sculptures: broad Abcgintodiscordnord capitals, 56px/48px at 700 for the opening and 36px/0.93 at 800 for feature chapters, both with -0.01em tracking.
- The opening is a world, not a dashboard card: a 1240px-wide composition pairs a roughly 491px text column with an 832×480px product-and-object scene, then centers two 65px-high actions beneath both.
- Controls are compact rounded rectangles inside much softer architecture: 12px action corners and a 16px login corner contrast with 120px feature-panel corners. Do not turn the actions into pills.
- Color fills the environment, not the letters: white copy rides a continuous indigo canvas, #1a2081, with #5865f2 actions; pink and green energy stays in media stages and objects. Black editorial variants concentrate color in the opening, proof cards and closing call.
- Demonstrations are nested worlds: 1240×610px translucent feature frames hold about 727×554px of media beside a 384px copy column. Floating foreground objects break their edges; when bespoke art is unavailable, use a readable product composite with original rounded geometric props and colored rim light.
- Give the page a playful interruption and a monumental goodbye: a 140px-high full-width word ribbon uses 61px capitals, while the closing call uses centered 48px/1.2 capitals above a character or object ensemble. Finish with a nearly edge-to-edge wordmark artwork, inset 40px, on a violet-rising footer; use a fitted original name when no wordmark artwork exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Indigo environment | `#1a2081` | `--color-canvas` | background | Default marketing canvas beneath atmospheric imagery. |
| Deep violet | `#1f1d5d` | `--color-deep-violet` | surface, background | Dark end of blue action shading and luminous violet panels. |
| Indigo glass wash | `#31368e` | `--color-glass` | surface | Visible result of white at 0.1 over the indigo canvas. The translucent recipe adapts to the local atmosphere rather than painting a fixed flat blue. |
| Blurple action | `#5865f2` | `--color-blurple` | action, accent, background | Colored actions, active navigation and blue illumination. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White foreground | `#ffffff` | `--color-white` | text, action, accent | Headings, paragraphs, icons and light actions; translucency produces secondary text and glass. |
| Light-action hover | `#c7c8ce` | `--color-hover-gray` | action | Hover fill for the compact login action and closing download action. |
| Secondary white | `#babcd9` | `--color-muted` | text | White at 0.7 over indigo, used for footer category labels; the visible shade changes over the footer gradient. |
| Action ink | `#23272a` | `--color-ink` | text | Text and download icon on the default white action. |
| Black stage | `#000000` | `--color-black` | background, text | Login text and underlying footer backing; the main editorial canvas in institutional and business variants. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| institutional and business pages | Charcoal card | `#1a1a1a` | `--color-dark-card` | surface | White at 0.1 over black for practical information cards. |
| question and solution sections | Dark-stage divider | `#1a1a1a` | `--color-rule` | border | White at 0.1 over black, used as a 2px accordion separator. |
| business solution sections | Solution gray | `#b2b2b2` | `--color-secondary` | text | Expanded solution descriptions on black. |
| business campaign pages | Campaign plum | `#381f2c` | `--color-plum` | surface, background | Dark backing for pink-rising procedural cards and sales calls. |

## Typography

- **Abcgintodiscordnord** — Broad capital headlines, word ribbons and monumental numbers. Extended, very heavy geometric display sans with rounded bowls and emphatic horizontal shapes. If unavailable, use **Archivo Black**. Use the broadest natural setting; preserve compact line heights and adjust line breaks rather than condensing. Font stack: "Abcgintodiscordnord", "Archivo Black", Arial, sans-serif.
- **Abcgintodiscord** — Marketing paragraphs, navigation, cards and controls. Friendly, open, rounded grotesk with a substantial x-height; regular body and medium labels. If unavailable, use **DM Sans**. Use 400 and 500; preserve the generous body size. Font stack: "Abcgintodiscord", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| ribbon | Abcgintodiscordnord | 700 | 61px | 25px | -0.01em, uppercase | Oversized words vertically centered in a deep word ribbon; allow glyphs to overflow their line box. |
| display | Abcgintodiscordnord | 700 | 56px | 48px | -0.01em, uppercase | Default marketing opening headline, compactly stacked. |
| closing-heading | Abcgintodiscordnord | 700 | 48px | 1.2 | -0.01em, uppercase | Centered final invitation above the large object ensemble. |
| feature-heading | Abcgintodiscordnord | 800 | 36px | 0.93 | -0.01em, uppercase | Benefit headlines inside the large feature frames. |
| body | Abcgintodiscord | 400 | 20px | 1.3 | normal | Default support paragraphs and centered introductory copy. |
| opening-body | Abcgintodiscord | 400 | 20px | 1.3 | 0.016em | Opening support and the first feature paragraph. |
| hero-action | Abcgintodiscord | 400 | 20px | 1.3 | 0.0125em | The two prominent opening actions. |
| navigation | Abcgintodiscord | 500 | 16px | 1.2 | normal | Primary navigation links. |
| login | Abcgintodiscord | 500 | 16px | 1.2 | 0.0156em | Compact login control. |
| utility | Abcgintodiscord | 400 | 16px | 1.5 | normal | Footer links and language selector. |
| footer-label | Abcgintodiscord | 400 | 16px | 1.25 | normal | Muted footer category labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| institutional and business pages | centered-display | Abcgintodiscordnord | 700 | 72px | 0.9 | -0.03em, uppercase | Centered institutional and business openings and institutional closing invitations. |
| business quantified proof | stat | Abcgintodiscordnord | 700 | 72px | 0.96 | -0.01em, uppercase | Large compact figures with suffixes kept at the same scale. |
| careers and business pages | section-heading | Abcgintodiscordnord | 700 | 48px | 1 | -0.02em, uppercase | Centered benefit, proof and collection headings. |
| company storytelling | editorial-heading | Abcgintodiscordnord | 700 | 48px | 1 | -0.01em, uppercase | Centered history, leadership and media headings. |
| company timelines | timeline-date | Abcgintodiscordnord | 400 | 36px | 1 | -0.01em, uppercase | Broad date headings in alternating history cards. |
| business process explanations | step-heading | Abcgintodiscordnord | 700 | 28px | 1 | -0.01em, uppercase | Numbered procedural card headings. |
| institutional and business card grids | card-heading | Abcgintodiscord | 500 | 24px | 1.2 | normal | Sentence-case listing and benefit card titles. |
| question sections | question | Abcgintodiscord | 500 | 20px | 1.4 | normal | Multi-line FAQ questions. |
| business stories | story-tag | Abcgintodiscord | 500 | 20px | 1.2 | normal | Short title chips over story imagery. |
| company timelines | timeline-body | Abcgintodiscord | 400 | 18px | 24px | normal | Muted historical descriptions beneath dates. |
| institutional and business pages | compact-action | Abcgintodiscord | 500 | 16px | 1.5 | normal | Business conversion actions and institutional closing actions. |

**Notes:**

- The display face is deliberately much broader and heavier than the paragraph face. Preserve its shape before trying to match line breaks.
- The default feature heading uses a heavier cut than the larger opening. Uppercase styling does not extend to body copy or ordinary button labels.
- Tracking is usually -0.01em in display sizes; the centered 72px variant tightens to -0.03em. Body copy stays mostly untracked.
- Use 10px between feature headings and paragraphs; centered institutional heading pairs use 24px. Do not introduce a universal small uppercase eyebrow above every chapter.

## Layout

**Density:** Airy, with large cinematic panels and long vertical breathing spaces; practical card interiors remain deliberately spacious.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and compact card title-to-description gaps. |
| 16px | Three-column card gutters and story chip-to-description spacing. |
| 20px | Listing and story-grid gutters. |
| 24px | Centered heading-to-support spacing and opening action separation. |
| 28px | Media-side inset in the large feature frames. |
| 40px | Global desktop side padding for navigation and footer; story-card text inset. |
| 48px | Stat-card padding and section-intro-to-controls separation. |
| 56px | Editorial card padding and split solution gutter. |
| 64px | Listing-card padding and major heading-to-media spacing. |
| 80px | Business section vertical padding. |
| 95px | Vertical feature-panel breathing room. |
| 120px | Campaign-call top spacing and internal vertical padding. |
| 160px | Institutional chapter spacing and campaign-call bottom spacing. |
| 190px | Expanded breathing room around feature and ribbon transitions. |

### Containers and grids

- **marketing container**: max width 1240px · side padding 40px. Centered feature frames and opening composition; at a 1440px viewport the frames have 100px outer margins.
- **feature split**: 2 columns · gap 42px. A 384px text block beside a roughly 727px media stage; alternate which side carries the media.
- **footer container**: max width 1762px · gap 20px · side padding 40px. Broad utility area with a large left identity/language/social block and four narrower link columns.
- **editorial container** (only for institutional and business pages): max width 1200px · side padding 120px. Centered black-stage sections, proof and collections.
- **two-column listings** (only for institutional listings): 2 columns · gap 20px. 590px-wide cards at desktop, paired in consistent rows.
- **three-column proof** (only for business proof and process sections): 3 columns · gap 16px. Approximately 389px-wide cards across the editorial container; story collections use a 20px gutter instead.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | feature frames | 120px |
|  | primary actions | 12px |
|  | login and utility selects | 16px |
| institutional and business pages | information cards | 56px |
| company timelines | timeline cards | 48px |
| business campaign pages | campaign call | 72px |
| business stories | story chips | 14px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| download hover | `0px 8px 15px rgba(0,0,0,0.2)` | Declared hover emphasis on the opening white download action; not a default card elevation. |

### Surfaces

#### Orbital canvas · level 0

**Use:** Default page environment.

**CSS:** `background-color: #1a2081`

**Observed:** A continuous dark-indigo world with broad blurred violet light, sparse star-like marks and occasional out-of-focus floating objects. Light changes across sections without hard band boundaries.

**Transfer:** Use the Atmospheric field recipe to create a continuous setting behind the content.

#### Soft glass frame · level 1

**Use:** Large product benefit chapters.

**CSS:** `background: linear-gradient(135deg, rgba(255,255,255,0.2), rgba(255,255,255,0.12) 12%, rgba(255,255,255,0.04) 50%, rgba(255,255,255,0.1)); border-radius: 120px; backdrop-filter: blur(10px)`

**Observed:** A softly illuminated translucent shell, not a high-contrast outlined glass pane; another feature uses 80px backdrop blur. The media receives its own darker or saturated inset world.

**Transfer:** Match the soft directional highlight; exact glow stops are not essential.

#### Rising violet footer · level 0

**Use:** Shared page ending.

**CSS:** `background: linear-gradient(180deg, #1f1d5d, #5865f2); color: #ffffff`

**Observed:** The dark-violet upper utility area becomes brighter toward the enormous pale wordmark at the bottom.

**Transfer:** Let the footer feel like the final illuminated scene, not an unrelated black legal strip.

#### Black editorial stage · level 0

**Only for:** institutional and business pages

**Use:** Long-form stories, practical collections, processes and proof.

**CSS:** `background-color: #000000; color: #ffffff`

**Observed:** Deep black separates chapters from the blue opening; rounded photos and luminous proof cards supply the color.

**Transfer:** Use black as the dominant support-page ground rather than importing the blue environment into every listing.

#### Charcoal information surface · level 1

**Only for:** institutional and business pages

**Use:** Listings and benefit cards.

**CSS:** `background: rgba(255,255,255,0.1); border-radius: 56px`

**Observed:** Borderless, shadowless raised-looking blocks on black. Spacious padding does the organizing.

**Transfer:** Keep the card quiet so its title, pictogram or tag can carry the hierarchy.

#### Blue proof surface · level 1

**Only for:** quantified proof sections

**Use:** Luminous numerical cards.

**CSS:** `background: radial-gradient(ellipse at 50% 120%, #5865f2, #1f1d5d); border-radius: 56px; backdrop-filter: blur(120px)`

**Observed:** A deep-violet upper field rises to brighter electric blue along the lower edge.

**Transfer:** Recreate the luminous lower pool, not a glossy metallic texture.

#### Pink campaign surface · level 1

**Only for:** business campaign pages

**Use:** Procedure cards and sales closing call.

**CSS:** `background: radial-gradient(ellipse at 50% 120%, rgba(255,0,220,0.65), #381f2c); border-radius: 72px`

**Observed:** Plum at the top, saturated pink illumination below. Process cards use 56px corners, while the wide closing banner uses 72px.

**Transfer:** Keep this warmer glow concentrated in campaign explanations and conversion moments.

## Components

### Navigation link

**Use:** Primary navigation within the transparent top header.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; padding: 10px 16px; border-radius: 12px; color: #ffffff`

**Text style:** `navigation` — Abcgintodiscord 500 · 16px/1.2

**Observed:** A broad row of links sits between the left identity and right login action; dropdown links add small chevrons. At scroll depth the identity and login remain as compact corner anchors rather than a full-width opaque bar.

**States:** Declared: hover background-color #5865f2; focus-visible white 2px outline with -2px offset and 1px radius; active outline 0px.

### Login button

**Use:** Persistent compact utility action at the top right.

**CSS:** `background-color: #ffffff; color: #000000; border-radius: 16px; padding: 10px 16px`

**Text style:** `login` — Abcgintodiscord 500 · 16px/1.2 · tracking 0.0156em

**Observed:** Small white rounded rectangle, visually subordinate to the opening conversion pair.

**States:** Declared: hover background-color #c7c8ce; focus-visible #5865f2 solid 2px outline with 4px offset and 1px radius; active outline 0px.

### Primary button

**Use:** Default high-contrast opening conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 65px; padding: 15px 24px; background-color: #ffffff; color: #23272a; border-radius: 12px`

**Text style:** `hero-action` — Abcgintodiscord 400 · 20px/1.3 · tracking 0.0125em

**Observed:** A dark 24px download icon precedes the label. The light action comes first in the paired row. Closing download retains the same silhouette; business calls use a 52px-high, 16px medium-label version.

**States:** Declared: hover shadow 0px 8px 15px rgba(0,0,0,0.2) and color #23272a; focus-visible #5865f2 solid 2px outline with 4px offset and 1px radius; active outline 0px.

### Secondary button

**Use:** Alternative browser or immediately available action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 65px; padding: 19.5px 24px; background-color: #5865f2; color: #ffffff; border-radius: 12px; overflow: hidden`

**Text style:** `hero-action` — Abcgintodiscord 400 · 20px/1.3 · tracking 0.0125em

**Observed:** Label-only alternative beside the light action, with a subtle downward deep-violet shading layer. Institutional and business actions use 16px medium labels at 48–52px height; institutional closing buttons use 8px corners.

**States:** Declared: hover background-color #5865f2 and box-shadow none.

### Feature panel

**Use:** One focused product capability paired with a demonstration.

**CSS:** `display: flex; flex-direction: column; max-width: 1240px; min-height: 610px; padding: 28px 52px 28px 28px; border-radius: 120px; backdrop-filter: blur(10px)`

**Text style:** `feature-heading` — Abcgintodiscordnord 800 · 36px/0.93 · tracking -0.01em · uppercase

**Observed:** Uses Soft glass frame. Inside is a horizontal composition with a much larger media side, a vertically centered text block and a short support paragraph. The reversed variant shifts the larger text-side inset and uses 80px backdrop blur.

**Transfer:** Show one comprehensible task per frame; position decorative props outside the text block, crossing the frame edge.

### Utility select

**Use:** Language selection in the footer.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 8px; width: 314px; height: 56px; padding: 17.5px 16px 17.5px 24px; background-color: rgba(255,255,255,0.1); border-radius: 16px; color: #ffffff`

**Text style:** `utility` — Abcgintodiscord 400 · 16px/1.5

**Observed:** Left-aligned label with a right-side chevron, below a muted category label and above social icons. Collection filters share this softened silhouette; institutional filters use a darker solid fill and 12px corners.

**States:** Declared: hover white at 0.1 background and transparent border; focus-visible white 2px outline with 2px offset.

### Footer link

**Use:** Navigation within the four footer categories.

**CSS:** `display: block; margin-top: 12px; color: #ffffff`

**Text style:** `utility` — Abcgintodiscord 400 · 16px/1.5

**Observed:** Text-only links beneath muted category headings; the 24px line and 12px top margin give a 36px vertical cadence.

**States:** Declared: hover text-decoration underline; focus-visible white 2px outline with 2px offset and 1px radius; active outline 0px.

### Listing card

**Only for:** institutional listings

**Use:** Whole-card destinations for a catalog of opportunities or resources.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; padding: 64px; background-color: rgba(255,255,255,0.1); border-radius: 56px; overflow: hidden`

**Text style:** `card-heading` — Abcgintodiscord 500 · 24px/1.2

**Observed:** A small category chip is placed high in the card, with a long breathing space before the title and compact location line. Two columns fill the black editorial stage. Benefit variants use 56px padding and a small toy-like pictogram instead of a category chip.

**States:** Declared: hover outline 0px; focus-visible #5865f2 solid 2px outline with 4px offset and 1px radius; active outline 0px.

### Stat card

**Only for:** quantified proof sections

**Use:** A bold number, short explanation and source affordance.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; gap: 40px; padding: 48px; border-radius: 56px; background-color: #1f1d5d; backdrop-filter: blur(120px)`

**Text style:** `stat` — Abcgintodiscordnord 700 · 72px/0.96 · tracking -0.01em · uppercase

**Observed:** Uses Blue proof surface in a three-column row. Huge figures remain left-aligned; 18px medium explanatory copy sits below, followed by a muted 16px source link and information symbol. Occasional floating props overlap outside the row.

**Transfer:** Keep suffixes as large as numerals and use a genuinely relevant, attributable metric.

### Accordion row

**Only for:** question and solution sections

**Use:** Expandable questions or selectable solution explanations.

**CSS:** `position: relative; border-bottom: 2px solid rgba(255,255,255,0.1); margin-bottom: -2px`

**Text style:** `question` — Abcgintodiscord 500 · 20px/1.4

**Observed:** Full-width text trigger with a plus at the far right; the trigger has 32px vertical padding, 40px right padding and 4px left padding. FAQ rows sit beside an introductory text block. The solution variant pairs the row stack with a rounded demonstration and displays a minus on its expanded row.

### Story tile

**Only for:** business story collections

**Use:** Image-backed case-study links.

**CSS:** `display: flex; position: relative; flex-direction: column; justify-content: flex-end; padding: 0px 40px 40px; border-radius: 56px; overflow: hidden`

**Text style:** `body` — Abcgintodiscord 400 · 20px/1.3

**Observed:** Edge-to-edge editorial artwork backs a violet-darkened lower text area. A frosted title chip uses 12px 20px padding, 14px corners, 20px/24px medium type and 130px backdrop blur; short descriptive text sits 16px below. Three columns use 20px gutters. Carousel versions enlarge the center tile and darken the neighbors.

**Transfer:** Use a real outcome image, with a lower gradient strong enough to hold several white lines.

### Campaign call

**Only for:** business campaign pages

**Use:** Wide concluding sales conversion panel.

**CSS:** `display: flex; flex-direction: column; align-items: center; padding: 120px 80px; background-color: #381f2c; border-radius: 72px; max-width: 1200px`

**Text style:** `section-heading` — Abcgintodiscordnord 700 · 48px/1 · tracking -0.02em · uppercase

**Observed:** Uses Pink campaign surface, centered support text and a white compact action. Original toy-like props overlap diagonally opposed corners. The surrounding section gives 120px above and 160px below the panel.

**Transfer:** State how the reader can actually proceed, especially when access requires a sales conversation.

## Imagery and graphics

### Atmospheric field

**Use:** Continuous setting behind the default opening, feature frames and final invitation.

**Observed:** Deep indigo and near-black clouds with large violet-blue light pools; tiny squares, dots and four-point stars are widely scattered. Some background props are blurred and translucent, giving depth without interfering with white text.

**Transfer:** Keep the field dark near copy and brightest around the product; retain this atmosphere even for products without playful character art.

**Build:** Start with the indigo canvas. Add two absolutely positioned ellipses about 800×600px, filled with rgba(88,101,242,0.5), blurred 120px, one low-left and one high-right. Layer a near-black translucent radial vignette. Scatter an SVG field of 2–6px dots and occasional 12–20px four-point stars at white opacity 0.1–0.25; vary blur rather than making a regular dot grid.

### Product-and-prop diorama

**Use:** Main opening object and foreground accents around feature frames.

**Observed:** A large angled dark desktop screen, smaller upright phone, controller and a mixed 2D/3D character ensemble share a stage. Soft plastic, rounded bevels, purple-blue shadows and magenta rim lights connect them. The scene occupies more horizontal space than the copy, and isolated props float in front of and behind the main plane.

**Transfer:** Compose the new product's real interface on one primary device and one secondary object, with original abstract accessories that communicate the benefit. The minimum version is a crisp interface composite, a softly shaded bevel frame and two simple original 3D-style props.

**Build:** Use perspective transforms on the main interface plane with a small rotation, add a thick deep-violet side extrusion, and layer a secondary upright card or device in front. Build simple props from SVG ellipses, rounded rectangles and short cylinders; use a pale upper-left highlight, blue lower-right shade and a narrow magenta edge glow. Keep a few props sharp in front and blur distant ones.

### Nested demonstration stage

**Use:** The dominant media area within feature frames.

**Observed:** Dark interface panels float over richly lit rounded environments, alternating pink-plum, emerald-green and violet-blue treatments. Video portraits and activity tiles remain legible; the colored surround is generous enough to read as a world rather than a screenshot border.

**Transfer:** Show an authentic product state at useful scale, backed by one saturated lighting environment. Preserve clear interface edges and avoid reproducing incidental internal interface styling as marketing tokens.

**Build:** Place the demonstration in a roughly 727×554px rounded stage. Use a dark upper radial gradient and a saturated rgba(255,0,220,0.65) or rgba(0,255,130,0.65) light pool below; inset the interface or video cards rather than filling the entire stage. Use soft contact shadows only inside this media composition.

### Monumental identity artwork

**Use:** The bottom of every page.

**Observed:** An immense pale wordmark stretches almost the full available width below the utility columns. It is treated as a graphic, with broad rounded letterforms and no accompanying slogan.

**Transfer:** Use the new product's own wordmark or fit its name as a single broad typographic silhouette. Preserve the massive scale and restrained single-color treatment.

**Build:** Create a tightly fitted SVG wordmark or convert original display lettering to outlines. Fit it to the footer width with 40px side clearance and about 40px bottom clearance. Use a near-white fill with slight translucency; reserve a deep clear gap above it so it reads as the final visual event.

### Human editorial photography

**Only for:** institutional pages

**Use:** Culture stories, leadership and workplace galleries.

**Observed:** Warm natural indoor light, casual human expressions and real environments. Tall culture photographs are about 468×629px; leadership images are wide at about 1100×547px. Deeply rounded framing sits directly on black, without colored image borders. Galleries show a large central photograph and partial neighbors.

**Transfer:** Choose candid, grounded images with lived-in materials, not studio headshots or saturated corporate stock.

### Campaign artwork and partner strip

**Only for:** business pages

**Use:** Proof collections, feature stories and partner validation.

**Observed:** Cinematic promotional images retain their varied hues but receive dark violet lower overlays behind text. A featured image is much wider than its accompanying copy. Partner marks appear white on black over a restrained pink glow.

**Transfer:** Use licensed outcome imagery and monochrome partner identities; unify disparate art through the lower gradient rather than recoloring everything.

**Build:** For image tiles, add an absolute linear gradient from transparent at the upper third to rgba(31,29,93,0.95) at the bottom. Behind partner marks, place a wide thin magenta ellipse with opacity 0.2 and 60px blur. Keep the logos themselves flat white.

### Icons

**Observed:** Navigation chevrons are 16px outline SVGs with 2px round strokes; carousel arrows are 24px with the same construction. Social and download marks are compact solid symbols. Larger benefit pictograms are colored 3D objects, not UI line icons.

**Transfer:** Use round-capped white outline chevrons and arrows for navigation, dark download marks on white actions, and separate sculptural pictograms for expressive benefits.

## Section recipes

How recurring sections are built.

### First screen: Orbital product opening

**Observed:** The first 900px contains the transparent header, full headline, support paragraph, entire main diorama and paired actions. A 1240px container starts below 176px of opening space. The left copy occupies about two fifths of the composition, with a 491px maximum width and a three-line 56px/48px capital headline. The much larger angled device ensemble fills the right side and projects slightly beyond the container. Behind it are a dark indigo atmosphere, scattered star marks and blurred props; sharp foreground devices and figures sit in front. A centered action row sits 64px beneath the main scene, with white Primary button first and blue Secondary button second, separated by 24px. The first benefit frame falls below this opening screen.

**Transfer:** Make the new product the largest object in a small original world: one recognizable interface, a secondary device or output artifact and two shaded geometric props are enough. Preserve the left-copy/right-world imbalance and put the action pair beneath the entire composition. Institutional pages instead center a 72px headline and paragraph above a rounded collage or photo gallery; business pages center the same headline scale over darkened campaign imagery and use a single compact action.

**Avoid:** Do not replace this with a centered headline over a tiny flat screenshot, a white SaaS dashboard layout, or actions buried inside the device artwork.

**Text style:** `display` — Abcgintodiscordnord 700 · 56px/48px · tracking -0.01em · uppercase

### Alternating capability frame

**Observed:** Feature panel rests in the Orbital canvas with 95–190px vertical breathing room. A vertically centered 384px copy column faces a much larger Nested demonstration stage. Feature-heading and body pair with a 10px gap. Successive frames reverse media and text, while floating props cross selected edges.

**Transfer:** Make each chapter a distinct human benefit and demonstrate one interaction. Vary the inset stage color without changing the panel architecture.

**Text style:** `feature-heading` — Abcgintodiscordnord 800 · 36px/0.93 · tracking -0.01em · uppercase

### Word ribbon interruption

**Observed:** A full-bleed, 140px-high ribbon carries repeated short activity words in 61px capitals, interspersed with small decorative graphics. The ribbon clips horizontally and words share a centered baseline despite a deliberately short line box.

**Transfer:** Use a few short verbs relevant to the new product. Include this energetic word device somewhere in the narrative, without treating its location as a fixed section order.

**Text style:** `ribbon` — Abcgintodiscordnord 700 · 61px/25px · tracking -0.01em · uppercase

### Playful closing invitation

**Observed:** A centered 48px/1.2 headline addresses the end of the scroll directly. A white download action follows after 110px; a broad original character/object ensemble fills the lower part of the approximately 904px scene, still inside the starry environment. The ensemble bridges into the footer.

**Transfer:** Write a warm final nudge tied to the reader's next action and create a concluding ensemble from the product artifacts already introduced. The closing scene should feel like a curtain call, not a generic rectangular banner.

**Text style:** `closing-heading` — Abcgintodiscordnord 700 · 48px/1.2 · tracking -0.01em · uppercase

### Identity-sized footer

**Observed:** Rising violet footer supports a broad left identity block with language select and social icons, plus four 200px link categories. The utility content begins about 100px below the section edge. Muted 16px labels contrast with white links at a 36px vertical cadence. Monumental identity artwork occupies the entire lower width with 40px side clearance.

**Transfer:** Preserve both utility and spectacle: keep useful destinations readable, then give the new identity its own immense final silhouette.

**Text style:** `utility` — Abcgintodiscord 400 · 16px/1.5

### Centered editorial introduction

**Only for:** institutional and business pages

**Observed:** A 48px capital heading centers above a 20px paragraph with 24px separation. Copy is constrained to roughly 820–897px, inside the 1200px editorial container. Black negative space separates the introduction from practical grids, media or proof.

**Transfer:** Use this as the bridge between an emotional opening and a concrete chapter; do not force an eyebrow label onto it.

**Text style:** `section-heading` — Abcgintodiscordnord 700 · 48px/1 · tracking -0.02em · uppercase

### Alternating milestone spine

**Only for:** company histories and progress narratives

**Observed:** A centered vertical 5px spine and 28px circular nodes connect alternating left/right cards. Cards are 536px wide with 48px corners, 56px padding and 96px bottom separation. Dates use 36px broad capitals; 18px descriptions sit 24px below at half-opacity white. Original floating 3D objects punctuate the unused opposite side.

**Transfer:** Use only when time or progress is genuinely the organizing principle. Maintain the alternating rhythm and quiet charcoal cards without inventing unnecessary milestones.

**Text style:** `timeline-date` — Abcgintodiscordnord 400 · 36px/1 · tracking -0.01em · uppercase

### Practical collection and benefit grid

**Only for:** institutional listings and benefit sections

**Observed:** Two 590px columns separated by 20px hold Listing card or its pictogram-led variant. Large centered introductions and paired filters precede the collection. Long lists keep their generous interior spacing; benefit cards group explanatory copy under a small colorful object.

**Transfer:** Adapt to a finite resource collection, program directory or useful benefit set; let content determine length rather than reproducing an enormous list.

**Text style:** `card-heading` — Abcgintodiscord 500 · 24px/1.2

### Three-step explanation

**Only for:** business process sections

**Observed:** Three cards about 389×572px use Pink campaign surface with 56px corners, 16px media inset and 40px bottom padding. Large dark demonstrations occupy the upper area; numbered 28px capital headings and short explanations sit below. Cards share a 16px gutter.

**Transfer:** Explain a real beginning, action and result with clear illustrated states, retaining the rich media-to-text ratio.

**Text style:** `step-heading` — Abcgintodiscordnord 700 · 28px/1 · tracking -0.01em · uppercase

### Quantified proof row

**Only for:** institutional and business proof sections

**Observed:** Three Stat cards sit under a centered chapter lead, with 64–80px separation before the row. Broad 72px figures dominate the upper-left corner, with labels and source affordances below. Blue proof surface supplies the color; one or two floating objects overlap the row perimeter.

**Transfer:** Use a small set of comparable verified measures, keeping explanation and attribution close to each figure.

**Text style:** `stat` — Abcgintodiscordnord 700 · 72px/0.96 · tracking -0.01em · uppercase

### Split questions or solution browser

**Only for:** objection handling and solution selection

**Observed:** A text introduction faces a stack of Accordion rows. Institutional questions use the left side for a short heading and support, the right for questions and a small white secondary action. Business solutions put the selectable stack left and a roughly 572×321px demonstration right, separated by 56px.

**Transfer:** Use for real decisions or objections; pair the expanded item with a relevant demonstration rather than generic imagery.

**Text style:** `question` — Abcgintodiscord 500 · 20px/1.4

### Featured story and visual collection

**Only for:** business proof libraries

**Observed:** A featured story pairs left-aligned text and a title chip with a 660×372px rounded cinematic image. A later centered heading and category select introduce three columns of Story tiles. A compact blue load-more action ends the collection; carousel presentations instead emphasize a larger central tile with dimmed partial neighbors.

**Transfer:** Lead with one complete example, then allow scanning and filtering across related stories.

**Text style:** `section-heading` — Abcgintodiscordnord 700 · 48px/1 · tracking -0.02em · uppercase

### Scoped closing alternatives

**Only for:** institutional and business pages

**Observed:** Institutional endings center a 72px headline, 20px support and blue compact action on a black-to-violet field, framed by two floating objects. Business endings use Campaign call with a pink-rising fill, 48px heading, explanatory support and white compact action. Both resolve into Rising violet footer.

**Transfer:** Choose the closing treatment that belongs to the page purpose: editorial continuation for institutional content, clear sales contact for business campaigns.

**Text style:** `centered-display` — Abcgintodiscordnord 700 · 72px/0.9 · tracking -0.03em · uppercase

## Page flow

**Storyline:** Emotional promise → tangible product or human world → focused capability or context chapters → proof and practical detail → playful invitation → monumental identity ending.

### Consumer product landing page

1. **Promise** — Left-aligned compressed headline beside an oversized product diorama and paired actions.
2. **Capability chapters** — Alternating translucent frames each demonstrate a single benefit, interrupted by a full-width word ribbon.
3. **Closing call** — Direct conversational nudge, one light action and a large concluding ensemble.
4. **Utility and identity** — Shared violet footer with four navigation groups and immense identity artwork.

**Transfer:** Use the theatrical blue environment as the default for a new product landing page; choose the number and ordering of capability chapters to suit the product.

### Institutional storytelling

1. **Identity promise** — Centered large headline over a rounded collage of interface, people and original objects.
2. **Context and progress** — Introductory heading pair leads to alternating milestone cards on a vertical spine.
3. **Quantified proof** — Three luminous numerical cards.
4. **Human validation** — Large explainer video, warm leadership portraits and a rounded workplace gallery.
5. **Closing invitation** — Oversized centered continuation call with floating objects, then shared footer.

**Transfer:** Use a black editorial stage and tell only the history or context needed to explain the new organization.

### Recruiting or participation directory

1. **Invitation** — Centered headline, warm support and compact action above a workplace photo carousel.
2. **Human context** — Alternating portrait-led stories with large text blocks on black.
3. **Practical selection** — Paired filters and spacious two-column destination cards.
4. **Supporting reasons** — Pictogram-led benefits and a community carousel.
5. **Objection handling** — Split FAQ with plus-marked rows.
6. **Continuation and utility** — Centered appetite-building closing line, action and shared footer.

**Transfer:** Use this for participation catalogs as well as jobs; keep the human context and filters but size the collection to the real content.

### Outcome library

1. **Proof promise** — Centered headline and support above a featured image-and-text story.
2. **Browsable proof** — Centered collection heading, category filter and three-column image-backed story tiles.
3. **Collection continuation** — Small blue load-more action.
4. **Closing conversion** — Pink luminous sales call followed by shared footer.

**Transfer:** Lead with a strong example, then let users compare a varied collection without flattening the imagery into generic logo cards.

### Business product explanation

1. **Promise** — Centered capital headline over a dark campaign-art collage and one compact action.
2. **Process demonstration** — Three vivid image-led numbered cards.
3. **Solution exploration** — Selectable explanation rows beside a live product demonstration.
4. **Benefits and quantified proof** — Charcoal pictogram cards followed by blue numerical cards.
5. **Social proof** — White partner marks on a pink glow and a focused story carousel.
6. **Closing conversion** — Wide pink sales panel with white action, then shared footer.

**Transfer:** Combine concrete process, solution selection and verifiable outcomes for the new business audience; retain the stronger black-stage contrast rather than the continuous consumer atmosphere.

## Writing

Friendly, playful and assured, with the confidence of a product people already enjoy. Benefits sound like invitations to spend time together; practical sections become clearer and more direct without losing warmth.

**Do not copy:** Do not reuse Discord names, logos, characters, partner artwork, proprietary feature names, customer quotes, audience figures, employment promises or performance claims. Source examples illustrate voice and structure only.

- **Addressing the reader:** Speak directly to you and your group. Use we for the people behind the product, especially in institutional narratives, and the product name when explaining a concrete capability.
- **Rhythm:** Headlines are short, emphatic clauses, often 4–9 words and arranged into two or three broad lines. Support uses one to three conversational sentences; occasional parenthetical jokes and informal asides soften the certainty. Actions are literal and brief.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a familiar category, then recast it as an enjoyable everyday experience. | 6–10 words | “Group chat that’s all fun & games” |
| Capability headline | An invitation or a concrete social benefit, rather than an abstract feature noun. | 5–9 words | “Hop in when you're free, no need to call”<br>“stream like you’re in the same room” |
| Support paragraph | Explain what the reader can do, then add a human consequence or relaxed aside. | 25–55 words | “High quality and low latency streaming makes it feel like you're hanging out on the couch with friends while playing a game, watching shows, looking at photos, or idk doing homework or something.” |
| Primary action | Verb plus destination, platform or next step; avoid cleverness that obscures the result. | 2–6 words | “Download for Mac”<br>“See All Jobs”<br>“Get Started” |
| Business explanation | Describe the exchange and benefit in plain language, then summarize casually. | 15–30 words | “Players like our ad format because they are rewarded for engaging. It’s a win-win for players and advertisers.” |
| Closing line | A self-aware nudge that recognizes the reader has reached a decision point. | 3–11 words | “YOU CAN'T SCROLL ANYMORE. BETTER GO CHAT.”<br>“Hungry for more?” |

**Words and phrasing to use:** your own space; hop in; hang out; together; friends; play; build; show up your way; before, during, and after

**Avoid:** enterprise-grade synergy; revolutionary ecosystem; seamlessly leverage; unlock unparalleled potential; disruptive innovation

**Rules:**

- Lead with what a person can enjoy or accomplish, then explain the enabling capability.
- Let one informal aside add personality to a paragraph; keep filters, questions and actions literal.
- Keep proof attributable and distinguish audience scale from measured outcomes.
- Use uppercase as a display treatment, not as the prose voice.
- For business content, explain participation and the next step plainly instead of leaning on hype.

## Do's and Don'ts

### Do

- Keep the default headline at 56px/48px with -0.01em tracking and the broad display face.
- Give the product scene more room than the 491px opening text block.
- Use 120px frame corners against 12px main-action corners.
- Keep feature copy near 384px wide at 20px/1.3.
- Let colored media light spill through translucent shells rather than outlining every panel.
- Retain a full-width word device and a nearly edge-to-edge identity ending.
- Use 48px padding in luminous proof cards and keep numerical suffixes at full size.
- On institutional variants, let warm photography carry human detail against the black stage.

### Don't

- Do not use the 72px centered institutional headline as the default consumer opening.
- Do not replace the wide display face with a narrow condensed sports font.
- Do not turn every card into the same radius: 120px feature frames and 56px information cards have different jobs.
- Do not apply heavy drop shadows to the marketing cards; separation comes from light and translucency.
- Do not fill marketing paragraphs with pink, green or gradient lettering; keep their energy in the staged imagery.
- Do not put a 20px label into every navigation item; navigation uses 16px medium type.
- Do not shrink the footer identity to an ordinary small logo below legal text.
- Do not carry the campaign pink fill across an entire ordinary landing page.

## Motion and responsive

### Motion

**Observed:**

- Action and surface declarations commonly use 0.3s transitions; the opening actions also declare 0.2s ease-in-out timing.
- The navigation link declares font-variation-settings 0.4s; timeline cards declare opacity 0.3s.
- The word ribbon is horizontally translated; carousel progress declares a 9s linear animation. Exact ribbon cycle timing is unspecified.

**Transfer:**

- Keep the ribbon as a moving or clipped horizontal phrase field rather than a stack of static badges.
- Use slow visual continuity in the atmosphere and restrained control feedback; preserve the readable central demonstration when using video.

**Unknown:**

- Full scroll choreography, video loop durations, ribbon speed and reduced-motion behavior are not specified.

### Responsive

**Observed:**

- Styles declare major width breakpoints at 479px, 767px, 991px and 1280px among many others; the desktop composition is defined at 1440px.

**Transfer:**

- Recommended narrow-screen adaptation: stack copy before the demonstration, reduce decorative overlap near text, and keep the main interface large enough to understand.
- Recommended: wrap the action pair into a vertical group, collapse collection grids to one column, and fit the footer identity to the available width rather than reducing it to a small mark.
- Keep the broad display character and soft nested frames as the layout compresses; scale corner radii with the frame rather than leaving 120px corners on a narrow card.

**Unknown:**

- Exact mobile sizes, panel radii, menu behavior and breakpoint-specific rearrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
