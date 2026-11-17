# Antimetal — editorial systems in orbit

## Overview

An editorial serif gives technical software an unusually literary, assured presence, while tiny monospaced markings and bracketed frames make it feel engineered. The default is light, with warm gray paper, near-black ink and restrained earth-colored annotations; deep blue-black atmospheric scenes punctuate the reading. Sparse node diagrams, blueprint illustrations and carefully staged interface windows carry more weight than decorative photography. It suits complex products that need both an intelligible explanation and a sense of depth.

### Essentials

- Literary promises, not oversized grotesk slogans: regular Test Signifier headlines at 54px/1.1 with -0.037em tracking, supported by 24px/1.2 serif copy.
- An asymmetric first impression: a left-aligned promise and two actions sit over warm #d7d7d0 paper, with a large sparse node constellation occupying the right half; use a simple SVG network when bespoke interactive art is unavailable.
- Frames read like technical drawings: 1px dashed ink at 10% opacity, square content panels and 7px corner brackets recur on cards, diagrams, secondary actions and footer cells.
- Controls are capsules, content is not: primary actions are 46px tall with 12.5px 24.5px padding and full rounding; three separate frosted navigation islands float inside 30px outer gutters.
- Color is an annotation or an atmosphere, never a blanket theme: most reading remains gray and ink; rust and olive label diagrams, while full-width blue-black scenes stage a bright product window and a centered closing promise.
- A technical register offsets the serif: 10px Geist Mono capitals with 1px tracking mark section numbers, categories and small status badges; pair them with 14px/1.5 sans descriptions.
- A landing page needs both abstract system art and an atmospheric conversion moment: connect sparse nodes with almost invisible lines, then use a dark textured scene with a cream 54px closing line and one italic keyword. A static SVG and layered low-contrast gradients are the minimum equivalents.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Atmospheric night | `#090d13` | `--color-night` | background | Full-width product theater and closing action scenes. |
| Network night | `#0d1418` | `--color-diagram-night` | background | Dark inset node-network artwork. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Rust annotation | `#bd4a28` | `--color-rust` | text, accent | Small comparative diagram labels; not primary actions. |
| Olive annotation | `#6e7a34` | `--color-olive` | text, accent | Counterpoint labels in comparative diagrams; not large marketing fills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cream light | `#f4f4e7` | `--color-cream` | text, action, surface | Text on dark scenes, inverse primary actions and small diagram-label backing. |
| Frosted silver | `#e2e2e0` | `--color-glass` | surface | Visible navigation glass, rgba(232,232,232,0.67) over gray paper. |
| Gray paper | `#d7d7d0` | `--color-canvas` | background | Default page canvas, including card interiors. |
| Dashed edge | `#c4c4bd` | `--color-rule` | border | Default faint rule: ink at 10% over gray paper. |
| Equipment marking | `#888681` | `--color-faint` | text, border | Small muted markings; ink at 42% over gray paper. Also the stronger solid separator in role listings. |
| Secondary ink | `#66635f` | `--color-muted` | text | Supporting captions and navigation; ink at 60% over gray paper. |
| Paragraph ink | `#53504c` | `--color-body-ink` | text | Longer marketing explanations and serif support; ink at 70% over gray paper. |
| Warm ink | `#1a1614` | `--color-ink` | text, action, background | Headlines, strong copy, primary actions and active content panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| educational articles | Editorial paragraph ink | `#4b4845` | `--color-article-ink` | text | Article body; ink at 74% over gray paper. |
| resource browsing controls | Control edge | `#b5b4ae` | `--color-control-edge` | border | Secondary browse controls: ink at 18% over gray paper. |
| product demonstrations | Interface paper | `#f7f6f3` | `--color-product-paper` | surface | Bright interface inside the staged product window. |

## Typography

- **Test Signifier** — Headlines, quotations, prominent support text and footer links. Literary high-contrast serif with tapered details and expressive italic. If unavailable, use **Noto Serif**. Use regular and italic 400; retain tight headline tracking and verify line breaks. Font stack: "Test Signifier", "Noto Serif", Georgia, serif.
- **Geist** — Explanatory copy, navigation, actions and practical listings. Neutral, compact contemporary grotesk, mostly regular with medium controls. Font stack: "Geist", ui-sans-serif, system-ui, sans-serif.
- **Geist Mono** — Section numbering, uppercase categories, metadata and status markings. Small, widely tracked equipment-label monospace. Font stack: "Geist Mono", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Test Signifier | 400 | 54px | 1.1 | -0.037em | size clamp(40px, 16.7px + 3.6458vw, 54px) | Opening promise and centered closing promise. |
| heading-lg | Test Signifier | 400 | 48px | 1.1 | -0.021em | size clamp(34px, 10.7px + 3.6458vw, 48px) | Main numbered section titles and directory introduction. |
| heading | Test Signifier | 400 | 36px | 1.1 | normal | size clamp(28px, 14.7px + 2.0833vw, 36px) | Feature cards, quotations and article section titles. |
| serif-body | Test Signifier | 400 | 24px | 1.2 | normal | size clamp(20px, 13.3px + 1.0417vw, 24px) | Hero support, heading-pair explanations, research titles, marketing FAQ questions and footer links. |
| body | Geist | 400 | 20px | 1.5 | normal | size clamp(17px, 12px + 0.7813vw, 20px) | Expanded FAQ answers and sustained explanatory reading. |
| caption | Geist | 400 | 14px | 1.5 | normal | fixed | Card descriptions and secondary notes. |
| action | Geist | 500 | 14px | 1.5 | normal | fixed | Navigation links and all principal action labels. |
| eyebrow | Geist Mono | 400 | 10px | 13px | 0.1em, uppercase | fixed | Section numbers, categories, metadata, footer labels and small badges. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| atmospheric closing calls | closing-emphasis | Test Signifier | 400 italic | 54px | 1.1 | -0.037em | fixed | One key noun within the dark closing headline. |
| recruitment pages | careers-display | Test Signifier | 400 | 45.4px | 1.08 | -0.037em | size clamp(40px, 3.15vw, 52px) | Recruitment opening title. |
| recruitment pages | team-heading | Test Signifier | 400 | 28.8px | 1.08 | normal | size clamp(28px, 2vw, 32px) | Team selector names. |
| company and recruitment pages | supporter-list | Test Signifier | 400 | 28.8px | 1.06 | -0.021em | size clamp(24px, 2vw, 32px) | Unbulleted list of supporters in a photo-grid cell. |
| resource directories and related entries | term-title | Test Signifier | 400 | 24px | 1.08 | -0.021em | fixed | Compact dictionary and related-entry cards. |
| recruitment pages | role-title | Geist | 500 | 16px | 1.4 | normal | fixed | Practical role-listing headings. |
| recruitment pages | role-detail | Geist | 400 | 16px | 1.42 | normal | fixed | Location, employment and compensation detail. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Regular serif dominates importance; increasing weight is not the hierarchy mechanism. Display tracking tightens to -0.037em, section headings to -0.021em, while 36px headings remain untracked.
- Use serif for statements and sans for explanations. Mono is a small metadata accent, never the default paragraph voice.
- Preserve sentence case and full stops in major promises. Reserve expressive italic for a word within the closing line.

## Layout

**Density:** Airy at the section scale, compact within instrument-like cards and navigation islands.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Navigation and filter gaps. |
| 10px | Tight image and card-grid gutters. |
| 12px | Eyebrow-to-card-title gap. |
| 16px | Paragraph rhythm and paired-action gap. |
| 24px | Card padding and section-marker-to-heading gap. |
| 32px | Feature-card padding, hero support offset and article chapter separation. |
| 48px | Two-column editorial heading gap. |
| 64px | Heading group to section content. |
| 80px | Standard section top and bottom padding; hero support-to-action separation. |
| 96px | Testimonial vertical breathing room. |
| 120px | Desktop reading-area side padding. |
| 240px | Dark closing call vertical padding. |

### Containers and grids

- **Editorial container**: max width 1512px · side padding 120px. Centered outer container; 1200px content width at a 1440px viewport. Narrow-screen side padding is 24px.
- **Heading pair**: 2 columns · gap 48px. A numbered serif title on the left, a serif explanatory sentence aligned to its top on the right.
- **Tight paired stage**: 2 columns · gap 10px. Equal 595px columns at desktop for feature list and artwork, or photo mosaics.
- **Research grid**: 3 columns · gap 10px. Three approximately 393px cards, with full-width artwork above their text.
- **Footer grid**: 5 columns · gap 9px · side padding 30px. Four equal navigation cells and a fifth double-width status cell; desktop footer is about 287px tall.
- **Directory grid** (only for resource directories): 4 columns · gap 10px. Four approximately 293px cards per desktop row.
- **Article rail** (only for educational articles): max width 760px · gap 112px. 760px reading column beside a 260px contents rail, inside the editorial container.
- **Recruitment split** (only for recruitment pages): 2 columns · gap 110px. Team selectors and role listings in two 545px columns.

## Corner radius

| Element | Radius |
| --- | --- |
| Action capsules | 9999px (pill) |
| Navigation glass | 82px |
| Content panels | 0px |
| Metadata badges | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Glass inset | `inset 0px 0px 10px 0px rgba(0,0,0,0.08)` | Subtle inward shading on navigation glass. |
| Product window | `0px 30px 60px -30px rgba(26,22,20,0.25)` | The large staged product window, not ordinary content cards. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default light reading ground.

**CSS:** `background: #d7d7d0; color: #1a1614`

#### Bracketed paper panel · level 1

**Use:** Feature cards, directory entries and footer cells.

**CSS:** `background: transparent; border: 1px dashed rgba(26,22,20,0.1); border-radius: 0px; box-shadow: none`

**Observed:** Four small right-angle corner marks sharpen an otherwise faint frame. Active storytelling cards invert to ink and cream.

**Transfer:** Use a shared corner-bracket decoration rather than adding a heavy frame.

#### Navigation frost · level 2

**Use:** Separated floating navigation islands.

**CSS:** `background: rgba(232,232,232,0.67); border-radius: 82px; padding: 6px; box-shadow: inset 0px 0px 10px 0px rgba(0,0,0,0.08); backdrop-filter: blur(2.6px) saturate(1.8) brightness(1.1)`

**Observed:** A very fine white gradient rim catches the upper edge; the islands remain translucent on both light paper and dark atmosphere.

**Transfer:** Add a masked 0.5px linear-gradient rim at 122deg, white at the start, 45% white at 40%, 5% white at 78%. Keep the interior soft rather than mirror-like.

#### Night atmosphere · level 0

**Use:** Product theater and closing conversion band.

**CSS:** `background-color: #090d13; color: #f4f4e7; overflow: hidden`

**Observed:** Subtle grain and extremely dim blue-green and reddish edge light soften the darkness without becoming a bright gradient.

**Transfer:** Use the Atmospheric field recipe, leaving text contrast strong.

#### Product window shell · level 1

**Use:** One large interface demonstration.

**CSS:** `border: 0.5px solid rgba(26,22,20,0.1); box-shadow: 0px 30px 60px -30px rgba(26,22,20,0.25); overflow: hidden; border-radius: 0px`

**Observed:** A 1200px by 740px bright window sits on the dark scene. A translucent 34px title bar carries centered mono naming and three tiny window dots; the body is interface paper.

**Transfer:** Keep the frame credible and flat; use the new product's actual interface or a concise representative workflow.

## Components

### Floating navigation

**Use:** Persistent global navigation.

**CSS:** `position: sticky; top: 0px; z-index: 50; padding: 30px 30px 0px`

**Text style:** `action` — Geist 500 · 14px/1.5

**Observed:** Three separate Navigation frost islands: compact links at left, a wider centered identity capsule and sign-in plus compact dark action at right. There is no full-width painted navigation bar. The centered identity contracts to a small symbol farther down the page.

**Transfer:** Keep the three-part balance and shorten labels to fit; maintain independent islands.

### Primary button

**Use:** Default conversion action on paper.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #1a1614; color: #f4f4e7; border-radius: 9999px; padding: 12.5px 24.5px; height: 46px`

**Text style:** `action` — Geist 500 · 14px/1.5

**Observed:** Plain text without an arrow. On the dark closing scene the fill and label reverse. The navigation version uses 6px 14px padding, 33px height and 0.8 opacity.

**States:** Declared: hover background-color color-mix(in oklab, #1a1614 86%, transparent); the compact navigation action changes opacity to 1.

**Transfer:** Use one short verb-led conversion label.

### Bracketed secondary button

**Use:** Research or supporting action beside the main conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; background: transparent; border: 1px dashed rgba(26,22,20,0.1); border-radius: 9999px; padding: 12.5px 24.5px; height: 48px; color: #1a1614`

**Text style:** `action` — Geist 500 · 14px/1.5

**Observed:** Four square corner brackets surround the rounded dashed capsule, creating a distinctive hybrid. The inverse closing variant uses a cream dashed edge and cream text.

### Feature panel

**Use:** Single capability or active storytelling chapter.

**CSS:** `display: flex; flex-direction: column; gap: 12px; padding: 32px; border: 1px dashed rgba(26,22,20,0.1); border-radius: 0px`

**Text style:** `heading` — Test Signifier 400 · 36px/1.1

**Observed:** Uppercase mono label, serif title, then small sans description with extra separation. In the sticky narrative, the active panel is ink-filled with cream type; the system diagram remains beside it.

**Transfer:** Explain one capability per panel; a short title and one paragraph are sufficient.

### Research card

**Use:** Editorial proof and deeper reading.

**CSS:** `display: flex; flex-direction: column; gap: 24px; padding: 24px; border-right: 1px dashed rgba(26,22,20,0.1); border-bottom: 1px dashed rgba(26,22,20,0.1); border-left: 1px dashed rgba(26,22,20,0.1); border-radius: 0px`

**Text style:** `serif-body` — Test Signifier 400 · 24px/1.2

**Observed:** The text panel follows a 393px by 236px blueprint image. Category and date share a mono line; title precedes caption; a small circular author portrait and name anchor the bottom left, reading-time badge the bottom right.

**Transfer:** Use a technical drawing related to the article rather than a generic stock thumbnail.

### Marketing accordion

**Use:** Address practical trust questions.

**CSS:** `border-left: 1px dashed rgba(26,22,20,0.1); border-right: 1px dashed rgba(26,22,20,0.1)`

**Text style:** `serif-body` — Test Signifier 400 · 24px/1.2

**Observed:** Full-width rows use serif questions, a plus/minus at the right, dashed horizontal separators and 24px trigger padding. Expanded answers use body text, 16px paragraph gaps and 28px bottom padding.

**States:** Declared: hover background rgba(255,255,255,0.16).

**Transfer:** Use the serif question recipe for marketing; educational articles use smaller 16px medium sans triggers.

### Footer cell

**Use:** Structured site ending.

**CSS:** `position: relative; padding: 78px 19.5px 19.5px; min-height: 220px; border: 1px dashed rgba(26,22,20,0.1); border-radius: 0px`

**Text style:** `serif-body` — Test Signifier 400 · 24px/1.2

**Observed:** Mono category labels sit near the upper-left corner; serif links form a compact stack below. A double-width final cell holds a dark status badge, pale location badge, tiny descriptor and a small symbol. The shared footer returns to paper after the dark conversion scene.

**Transfer:** Preserve the bracketed cell system and status/identity composition using truthful product metadata.

### Term card

**Only for:** resource directories and related entries

**Use:** Browseable definition previews.

**CSS:** `display: flex; flex-direction: column; padding: 24px; border: 1px dashed rgba(26,22,20,0.1); border-radius: 0px`

**Text style:** `term-title` — Test Signifier 400 · 24px/1.08 · tracking -0.021em

**Observed:** Title at the top, muted caption after 12px and uppercase category pinned near the bottom. The entire card is a link. Related entries use two columns instead of the directory's four.

**States:** Declared: hover background #1a1614; heading changes to #f4f4e7.

**Transfer:** Keep category position consistent even when title lengths vary.

### Filter chip

**Only for:** resource browsing controls

**Use:** Category filtering.

**CSS:** `padding: 8px 16px; border: 1px solid #1a1614; border-radius: 9999px; background: #1a1614; color: #f4f4e7; height: 39px`

**Text style:** `action` — Geist 500 · 14px/1.5

**Observed:** The active chip is solid; inactive chips are translucent white with dashed ink edges. Chips have 8px gaps and sit above search.

**States:** Declared: hover on inactive chips background-color color-mix(in oklab, #fff 25%, transparent); color #1a1614.

### Search capsule

**Only for:** resource browsing controls

**Use:** Search terms and definitions.

**CSS:** `width: 420px; padding: 12px 80px 12px 44px; background: rgba(255,255,255,0.12); border: 1px dashed rgba(26,22,20,0.2); border-radius: 9999px; height: 47px`

**Text style:** `caption` — Geist 400 · 14px/1.5

**Observed:** Small outline magnifier at left; a result count sits at the far right of the wider ruled toolbar.

### Role listing

**Only for:** recruitment pages

**Use:** Practical job information beside team selection.

**CSS:** `display: grid; grid-template-columns: 1fr auto; align-items: end; gap: 32px; padding: 22px 0px; border-top: 1px solid rgba(26,22,20,0.42)`

**Text style:** `role-title` — Geist 500 · 16px/1.4

**Observed:** Medium sans title above muted employment metadata, separated by 24px. Unlike most cards, these rows use a stronger solid top rule rather than a surrounding dashed frame.

## Imagery and graphics

### Node constellation

**Use:** Signature abstract opening object and inset capability artwork.

**Observed:** A dispersed cloud of dark circular nodes occupies the right side of the paper hero, ranging from pinpoints to roughly 30px discs. Extremely faint links form an airy spatial network rather than a dense graph. A dark inset version has pale nodes receding around a central vanishing point.

**Transfer:** Represent the new product's relationships, data or objects as a sparse network. A static vector composition is sufficient, but the broad empty spaces and mixed dot sizes are essential.

**Build:** Place an SVG behind the hero text with its dense region in the right half. Use roughly 60–90 circles, most 2–8px and a few 14–30px, in near-black; join only selected neighbors with 0.5px ink lines at 5–10% opacity. Scatter vertically and leave the left reading area largely clear. For the dark inset, use pale circles at 10–40% opacity on network night, with hairlines converging toward a central point; add a dark radial vignette.

### Exploded system drawing

**Use:** Explain a layered product architecture beside narrative panels.

**Observed:** Unfilled outlined rectangular layers float in shallow perspective on the same paper as the page. Serif labels and tiny sans descriptions sit inside panels. Dashed edges, dark corner marks and faint projection lines describe depth without solid 3D materials.

**Transfer:** Draw the new product's input, transformation and result as layered transparent panels. The minimum version is a flat SVG with slight skew and staggered vertical offsets.

**Build:** Use SVG groups of wide rectangles, a smaller right-hand cell and a lower base layer. Apply a subtle skew to the whole group, retain 1px dashed ink outlines at about 15% opacity, add 7px corner ticks, and extend thin construction lines down-right. Keep labels readable and fills transparent; use a simple neutral system symbol in place of ornamental art.

### Atmospheric field

**Use:** Signature backing for product theater and the final conversion moment.

**Observed:** Deep blue-black material with fine grain, faint soft teal-blue illumination and a trace of reddish light near an edge. It remains nearly black behind cream type. The product scene introduces a few dim network dots behind a large bright window.

**Transfer:** Create subdued depth rather than a neon glow. Keep the same dark scene as a visual counterweight to long paper reading sections.

**Build:** Start with atmospheric night. Layer very broad radial gradients of rgba(35,70,75,0.18) near the center and rgba(85,30,40,0.12) near a lower corner, allowing most of the dark base to remain visible. Overlay SVG feTurbulence monochrome noise at 3–6% opacity. Use soft gradients instead of hard light beams; exact stops are not essential.

### Blueprint editorial art

**Use:** Research-card thumbnails.

**Observed:** Pale off-white drawings with thin muted blue engineering linework: mechanical cutaways, an iceberg cross-section and branching tracks. Grids, construction lines and small plotted dots occupy the full rectangular image area; no rounded clipping.

**Transfer:** Illustrate an editorial metaphor for the new subject using two-tone technical drawings, not a product logo on a colored tile.

**Build:** Use a pale paper rectangle with a low-opacity blue SVG grid, a central line-art object and a few extended guide lines. Vary grid density, retain ample unpainted paper and keep all strokes fine. A simplified vector diagram is the minimum acceptable artwork.

### Bright interface stage

**Use:** Product demonstration within the dark full-width band.

**Observed:** A large nearly white desktop interface is framed as a flat browser-like window. It dominates the band, backed by dim floating dots. The interface carries restrained olive and warning accents, not a colorful marketing palette.

**Transfer:** Show a representative real workflow at readable scale inside Product window shell; do not reproduce its internal information architecture.

### Workplace mosaic

**Only for:** company and recruitment pages

**Use:** Human and cultural proof after practical listings.

**Observed:** Warm natural office photography with wooden floors, white walls, casual seating and lived-in details. A two-by-two grid combines video/photo cells with a plain bracketed supporter-list cell; images are approximately 595px by 395px with 10px gutters.

**Transfer:** Use authentic wide workplace images with warm materials and ordinary human presence. Keep full rectangular framing and pair imagery with a short serif proof list.

### Icons

**Observed:** The dominant small marks are 7px right-angle bracket SVGs using 1.5px butt-ended strokes. Utility icons are restrained 14–18px outlines; search uses a thin 1.4px stroke. Play controls are simple dark triangles inside pale 48px circles.

**Transfer:** Use corner brackets as the recurring graphic grammar. Keep utility symbols tiny and monochrome rather than adding colored feature-icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Paper constellation opening

**Observed:** A 76px sticky navigation area floats above a 780px paper hero. The back layer is an edge-to-edge Node constellation; the foreground is a left-aligned editorial block with 120px side inset and 180px top padding inside the hero. The 54px single-line serif promise occupies roughly half the screen width. A 600px-wide serif support paragraph begins 32px below it, followed after 80px by Primary button and Bracketed secondary button with a 16px gap. The abstract object fills the right half and reaches down toward the bottom edge, with no enclosing card. Within the first 900px, navigation, promise, support, both actions and the full main object are visible; the next proof section's content remains below.

**Transfer:** Choose a concise outcome promise and a sparse network related to the new product. Keep the text/object imbalance even with a static SVG. Resource directories instead open with a heading pair and filter tools; articles open with breadcrumb, category, question headline and definition; recruitment opens with a title/support pair above listings.

**Avoid:** Do not center the hero, enlarge its title into a giant sans slogan, put the art in a rounded card or move the primary actions below the first screen.

**Text style:** `display` — Test Signifier 400 · 54px/1.1 · tracking -0.037em

### Numbered heading pair

**Observed:** Inside Editorial container, 80px section padding surrounds a mono number and tiny descriptive label. The marker row precedes the title by 24px. Heading pair places heading-lg at left and serif-body explanation at right; the main section body follows after 64px.

**Transfer:** Use numbers as chapter markings, with a descriptive label rather than a bright eyebrow badge.

**Text style:** `heading-lg` — Test Signifier 400 · 48px/1.1 · tracking -0.021em

### Testimonial and visual argument

**Observed:** A wide video still and a 36px serif quotation share a two-column row with about 96px vertical breathing room. A following visual argument pairs a comparative line chart with 24px serif prose; tiny cream-backed rust and olive labels annotate the chart.

**Transfer:** Use a credible voice beside contextual media, then explain the underlying problem with one restrained visual comparison rather than a wall of statistics.

### Layered narrative stage

**Observed:** A narrow sticky Feature panel sits at left while Exploded system drawing occupies a larger right-hand stage. Chapters have viewport-height breathing room; the active panel turns dark with cream text as the diagram reveals another layer.

**Transfer:** Translate a complex mechanism into a few distinct explanatory states. Keep the diagram on paper and the active text panel visually decisive.

### Product theater

**Observed:** Night atmosphere spans the viewport. Product window shell is centered at approximately 1200px by 740px with about 100px of vertical space on either side. The bright interface is the dominant object and sits above faint nodes.

**Transfer:** Let a meaningful workflow become the proof moment; a static high-quality interface can replace an interactive demonstration.

### Capability list and dark network

**Observed:** Numbered heading pair precedes a Tight paired stage. Four Feature panels form the left stack, using mono category, heading and caption. A tall network-night Node constellation fills the right column.

**Transfer:** Pair a readable capability inventory with one coherent system visualization instead of separate icons for every feature.

### Research and objections

**Observed:** Marketing accordion follows its heading group. Editorial proof uses Research grid with Blueprint editorial art, category/date markings, serif titles, captions and author metadata.

**Transfer:** Keep questions practical and articles substantive; use the same bracket grammar for both.

### Atmospheric closing call

**Observed:** A roughly 725px Night atmosphere band centers a cream display line with one italic keyword. Serif support is narrower and two actions sit below it; headline, support and action groups use 40px gaps and the band uses 240px vertical padding. The shared Footer cell grid immediately returns to paper.

**Transfer:** Make the closing claim a distilled version of the opening outcome, and pair a direct conversion with a deeper-reading alternative.

**Text style:** `display` — Test Signifier 400 · 54px/1.1 · tracking -0.037em

### Resource directory

**Only for:** resource directories

**Observed:** A heading pair begins well below navigation, followed by a muted qualification note, Filter chip row, ruled Search capsule toolbar and Directory grid. Equal-height Term cards pin categories to the bottom. A 120px bottom pause leads directly to the shared footer without a dark sales band.

**Transfer:** Use this variant for a browsable educational library with genuine categorization.

### Definition article

**Only for:** educational articles

**Observed:** Breadcrumb and category metadata precede the 54px question headline and 20px definition. Below, Article rail pairs a small sticky table of contents with 760px prose. Numbered sections use 36px headings, 16px internal gaps and 32px chapter gaps. A bracketed 32px-padded takeaway panel leads to compact FAQ, two-column related Term cards, previous/next capsules, then the shared footer.

**Transfer:** Explain the term immediately, organize the argument into readable chapters, and end with useful continuation rather than a forced conversion.

### Recruitment listing and mosaic

**Only for:** recruitment pages

**Observed:** A careers-display headline and short serif support share the opening row after 100px top padding. Below, bracketed team selectors face Role listing rows across Recruitment split. Workplace mosaic follows with 80px padding and ends in the shared paper footer, without a separate dark sales close.

**Transfer:** Keep practical opportunities above cultural photography; supporter names can become another compact factual proof list.

## Page flow

**Storyline:** Outcome promise → evidence and explanation → mechanism and capabilities → trust-building detail → appropriate next step → structured paper footer.

### Product marketing landing page

1. **Promise** — Paper hero with editorial outcome, two actions and abstract node object.
2. **Social proof** — Video and substantial serif quotation.
3. **Problem framing** — Comparative chart and serif argument.
4. **Mechanism** — Numbered heading and layered scroll narrative.
5. **Product demonstration** — Bright interface inside dark atmospheric theater.
6. **Capabilities** — Feature list beside a dark network visualization.
7. **Objection handling** — Serif-question accordion.
8. **Editorial proof** — Three blueprint research cards.
9. **Closing call** — Centered inverse promise with italic emphasis and paired actions.
10. **Navigation ending** — Bracketed paper footer with status and identity.

**Transfer:** Adapt the narrative to the product; retain the abstract system graphic, framed content grammar and atmospheric conversion device without fixing the number or order of chapters.

### Recruitment and company opportunity page

1. **Invitation** — Title/support pair in serif.
2. **Practical selection** — Team selectors beside solid-ruled role listings.
3. **Cultural proof** — Warm office mosaic and supporter list.
4. **Navigation ending** — Shared paper footer.

**Transfer:** Lead with useful opportunity information and use authentic environment imagery as supporting proof.

### Educational resource directory

1. **Orientation** — Heading pair and qualification note.
2. **Discovery** — Category chips, search and result count.
3. **Browse** — Four-column bracketed definition cards.
4. **Navigation ending** — Paper footer after a generous pause.

**Transfer:** Use the directory system for a large library, not as the default landing-page aesthetic.

### Educational definition article

1. **Immediate answer** — Breadcrumb, category, question headline and plain definition.
2. **Explanation** — Contents rail beside numbered prose chapters.
3. **Synthesis** — Bracketed takeaways panel.
4. **Objection handling** — Compact FAQ.
5. **Continuation** — Related cards and previous/next pills.
6. **Navigation ending** — Shared paper footer.

**Transfer:** Answer before elaborating; maintain reading-column discipline and finish with useful adjacent knowledge.

## Writing

Assured, technically literate and unusually plainspoken for complex software. Editorial statements establish the point, then concrete mechanisms and limitations earn belief.

**Do not copy:** Do not reuse the brand name, dotted identity mark, customer or investor names, quotations, proprietary product names, compliance assertions, compensation figures or performance claims. Write truthful equivalents for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use direct you/your for the reader's situation, the product name for system behavior and we for authored research. Definitions mostly use impersonal explanatory language.
- **Rhythm:** Short declarative headlines, often with full stops; longer explanations remain orderly and causal. Occasional three-part fragments create emphasis without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the desired operational outcome in one compact sentence. | 4–7 words | “Production that runs itself.” |
| Section title | A compact conceptual shift, sometimes expressed as two short clauses. | 5–9 words | “One platform. An army of agents.” |
| Capability statement | Contrast current behavior with the stronger alternative. | 4–8 words | “Everyone else watches. We operate.” |
| Primary action | Plain verb and concrete commitment. | 2–4 words | “Book a demo” |
| Supporting line | Explain the next step and its purpose, not a promotional flourish. | One sentence | “Take a 30 minute demo to see if [Brand] is the missing layer in your stack.” |
| Definition | Distinguish the input, effect or mechanism precisely. | One to three sentences | “Noise is the input and fatigue is the effect.” |
| Culture invitation | A human, concrete invitation with a mildly unexpected contrast. | One short sentence | “For rockstars who love working like farmers.” |

**Words and phrasing to use:** understand; operate; continuously; systems; layer; context; what changes; how it works; designed to

**Avoid:** revolutionary; game-changing; supercharge; unleash; magic; effortlessly; !!!

**Rules:**

- Explain what the product does before listing abstractions about its category.
- Use concrete verbs in short sequences; support them with a mechanism nearby.
- State qualifications openly where terms or definitions vary.
- Technical writing should distinguish causes from effects and symptoms from solutions.
- Research titles can carry quantified results only when the surrounding content substantiates them.

## Do's and Don'ts

### Do

- Keep display serif regular at 54px/1.1 and tighten tracking to -0.037em.
- Use 10px tracked mono labels as small equipment markings beside editorial type.
- Preserve 120px desktop reading gutters and 10px gutters inside dense card grids.
- Repeat 7px corner marks on faint dashed content frames.
- Keep ordinary cards flat and square while actions remain fully rounded.
- Stage the main product window at roughly 1200px wide on a dark scene.
- Use 24px inner padding for research and directory cards, 32px for narrative panels.
- Return to a bracketed paper footer with serif links after the final content.

### Don't

- Do not apply the 30px product-window shadow to every card.
- Do not turn rust or olive annotations into full-width accent bands.
- Do not use 700-weight sans headlines in place of the regular serif hierarchy.
- Do not make every category label a filled badge; most are plain tracked text.
- Do not make the navigation a single opaque full-width bar.
- Do not use rounded 16px content cards; the visual contrast depends on square panels and pill controls.
- Do not substitute saturated neon blobs for the nearly black atmospheric field.
- Do not treat a resource directory's four-column grid as the default composition for a new product landing page.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary actions declare color-related transitions at 0.2s cubic-bezier(.4, 0, .2, 1). Filter controls use 0.15s; marketing accordion surfaces use 0.3s.
- The status indicator declares pulse 2s cubic-bezier(.4, 0, .6, 1) infinite.
- Narrative panels are sticky and have active dark states; the central identity contracts to a compact symbol during scrolling.

**Transfer:**

- Keep state changes restrained: color inversion carries the narrative more than bouncing or exaggerated scaling.
- A static node diagram must preserve the same sparse spatial arrangement when interactive rendering is unavailable.

**Unknown:**

- Exact network animation choreography and scroll interpolation are not specified.
- Focus-visible styling and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 640px, 767px, 768px, 1024px, 1280px, 1440px and 1536px.
- Container classes specify 24px side padding below the desktop 120px variant. Heading pairs become one column; the directory declares one, two, three and four-column variants.
- The tall dark capability illustration is hidden below the medium layout. Desktop recruitment's two-column selection layout is limited to the large layout.

**Transfer:**

- On narrow screens, keep serif hierarchy using the clamp recipes, place explanations after headings and maintain square bracketed frames.
- Recompose the opening constellation below or behind a clear text area rather than compressing text into a narrow side column.
- Keep the resource search field within available width and reduce directory columns before shrinking its type.

**Unknown:**

- Narrow-screen visual appearance, navigation menu behavior and recruitment interaction are not verified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
