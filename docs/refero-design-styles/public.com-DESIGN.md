# Public — editorial meets machinery

## Overview

An editorial serif gives sophisticated software the bearing of a financial publication, while compact grotesk text keeps the product explanation practical. The default is white and pale gray with substantial black chapters, cool blue light, and occasional turquoise accents. Cinematic device scenes, restrained interface illustrations, and sparse modular grids make complex products feel tangible without making the surrounding page dense.

### Essentials

- Publication-sized promises above a machine-like stage: Denton 300 at 80px/1, normal tracking, left aligned within an 810px headline measure; a 1280px-wide cinematic product scene sits below.
- A small action can balance a very large sentence: the opening uses a 54px-high black pill with 40px horizontal padding on the right of a compact benefit row, not a cluster of oversized buttons beneath the title.
- Headlines speak in two tones: primary black or off-white statements acquire a second line in #a8b4bf at the same size and weight; section leads use 48px/54px or 52px/1.11 serif type.
- White explanation, black conviction: most explanatory grids stay white or #fafafa; full-width black chapters carry advanced capability, reassurance, and the closing invitation. Chromatic color stays concentrated inside media, fine data accents, and glows rather than becoming large flat brand-color bands.
- Interface illustrations dissolve into their backing: 16px-radius pale feature cards have centered 24px/28px titles, compact 14px/1.42 descriptions, and large lower-half interface compositions fading into #fafafa. Use a simplified working-state UI illustration when detailed product media is unavailable.
- A lit object anchors the promise and its return: include a cool-lit product stage and a substantial dark closing invitation, using devices, translucent objects, or an equivalent modeled interface on a reflective plane. The closing combines a 52px serif line, a restrained outlined pill, and a product object larger than the text.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Reference blue | `#0027b3` | `--color-link` | link | Contextual links and the hover color of feature links; not a primary button fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action | Primary headline ink, solid actions on light backgrounds, and full-width dark chapters. |
| Slate copy | `#516880` | `--color-body` | text | Default explanatory copy and small section labels on white. |
| Directory ink | `#1b222c` | `--color-footer-ink` | text | Footer navigation links. |
| Mist gray | `#a8b4bf` | `--color-muted` | text, accent | Second-line headline color and subdued supporting text on dark sections. |
| Cool edge | `#dce2ea` | `--color-edge` | border, text | Stronger light outlines and readable secondary text on black. |
| Directory rule | `#e9edf3` | `--color-footer-rule` | border | Footer boundary and the policy directory's top and bottom edges. |
| Light hairline | `#f1f4f7` | `--color-hairline` | border, surface, text | Low-contrast separators and utility-panel edges; also the large statistical numerals on dark technical sections. |
| Blue-gray paper | `#f3f6f9` | `--color-disclosure` | background | Continuous lower directory and policy field. |
| Feature porcelain | `#fafafa` | `--color-feature` | surface, text | Pale feature-card backing; softer white for type on black. |
| White canvas | `#ffffff` | `--color-canvas` | background, text, surface | Default page canvas and bright action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical product chapters | Technical cyan | `#52ffff` | `--color-cyan` | text, border, accent | Dark technical data, gradient headline highlights, and fine illuminated edges. |
| technical product chapters | Gradient teal | `#0a9393` | `--color-teal` | accent | Darker end of the cyan-to-teal headline gradient. |
| automation product finales | Metallic slate | `#4b6a87` | `--color-slate-light` | accent | Dark end of a slate-to-mist display-text gradient. |
| automation product finales | Night haze | `#3d526d` | `--color-night-haze` | background | Top atmospheric wash fading into a black automation chapter. |
| interactive calculators | Input edge | `#d3dedf` | `--color-input-edge` | border | Outline of editable calculator controls. |

## Typography

- **Denton** — Editorial headlines, paired section statements, and the product-name word field. Light, high-contrast serif with expressive curves and a compact editorial texture. If unavailable, use **DM Serif Display**. Use 400; preserve the generous size and normal tracking rather than synthesizing a thin cut. Font stack: "Denton", "DM Serif Display", "Times New Roman", serif.
- **Invest Pro** — Navigation, actions, card titles, short labels, and prominent sans numerals. Regular-to-medium neutral grotesk with crisp compact labels. If unavailable, use **Inter**. Use 400 and 500, with normal tracking. Font stack: "Invest Pro", "Inter", Helvetica, Arial, sans-serif.
- **Inter** — Explanatory paragraphs, compact feature descriptions, and footer navigation. Practical, highly legible sans with an open small-text texture. Font stack: "Inter", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Denton | 300 | 80px | 1 | normal | Default opening headline; also monumental late-page statements. |
| heading-dark | Denton | 300 | 52px | 1.11 | normal | Dark capability chapters and closing invitation. |
| heading | Denton | 300 | 48px | 54px | normal | Default centered section heading and two-tone heading pairs. |
| sans-heading | Invest Pro | 400 | 32px | 42px | normal | Compact standalone proof and larger instructional card titles. |
| card-title | Invest Pro | 400 | 24px | 28px | normal | Centered titles above large feature illustrations. |
| body | Inter | 400 | 16px | 1.5 | normal | Lead explanations and expanded answers. |
| eyebrow | Invest Pro | 400 | 16px | 22px | normal | Sentence-case label above a section heading; also short chapter subheads. |
| button | Invest Pro | 500 | 16px | 1.37 | normal | Primary and illuminated conversion actions. |
| navigation | Invest Pro | 400 | 16px | 1 | normal | Top-level navigation labels and short hero benefit markers. |
| question | Invest Pro | 400 | 16px | 1.5 | normal | Accordion question labels. |
| compact-body | Inter | 400 | 14px | 1.42 | normal | Default feature-card descriptions and compact proof paragraphs. |
| small-button | Invest Pro | 400 | 14px | 1.28 | normal | Header account actions and compact secondary actions. |
| text-link | Invest Pro | 400 | 14px | 18px | normal | Plain feature links accompanied by a small right arrow. |
| directory-heading | Inter | 600 | 14px | 1.5 | normal | Footer column headings. |
| directory-link | Inter | 400 | 14px | 1.5 | normal | Footer column links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| technical product chapters | stat | Invest Pro | 400 | 102px | 1 | normal | Paired monumental numeric proof with small cyan annotations. |
| dark technical landing pages | technical-display | Denton | 300 | 80px | 75px | normal | First line of a dark technical-product opening. |
| dark technical landing pages | technical-highlight | Denton | 300 | 80px | 1.1 | normal | Short gradient-colored response line below the technical opening promise. |
| focused product landing pages | product-display | Denton | 300 | 76px | 1 | normal | Focused product landing-page promises, centered or split beside a main object. |
| focused product landing pages | product-heading | Denton | 300 | 52px | 58px | normal | Explanatory section headings on focused product pages. |

**Notes:**

- Keep display type at weight 300 and normal tracking. The serif's shape, not artificial negative tracking or heavy weight, creates the editorial impression.
- The 48px section lead is the default. Focused product pages use the 52px/58px variant; do not flatten all heading recipes into a single compromise.
- Use the same serif recipe and size for both parts of a heading pair; distinguish the second phrase by color, not a smaller subtitle.
- Use sans type for explanatory titles and numbers, serif for promises. The pale panels carry intentionally compact descriptions compared with their generous image areas.

## Layout

**Density:** Airy at the page level and compact inside product explanations: large chapter pauses surround small, practical descriptions.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-heading gap and short heading-to-copy gap in dark columns. |
| 16px | Feature title-to-description and description-to-link gaps. |
| 24px | Default grid gutter and grouped support-to-action gap. |
| 32px | Opening title-to-action row separation, card top inset, and container internal side padding. |
| 40px | Dark capability-card inner inset and lead-to-support separation on product sections. |
| 64px | Section heading block-to-grid separation. |
| 80px | Wide desktop content inset at 1440px; alternative instruction-section vertical padding. |
| 96px | Dark capability chapter vertical padding. |
| 112px | Default major explanatory section vertical padding. |
| 128px | Premium split callout vertical padding. |
| 160px | Opening top padding and deep reassurance-chapter padding. |

### Containers and grids

- **Main container**: max width 1344px · side padding 32px. Centered outer box; at 1440px it produces a 1280px content field with 80px effective viewport insets.
- **Headline measure**: max width 810px. Left-aligned opening headline occupies roughly two thirds of the main content field.
- **Section lead**: max width 780px. Centered section-heading block above a broad feature field.
- **Feature grid**: 2 columns · gap 24px. Two 628px-wide pale cards at desktop with occasional full-width 1280px features.
- **Dark capability grid**: 3 columns · gap 0px. Three contiguous columns inside a single hairline frame; each approximately 426px wide.
- **Trust grid**: 3 columns · gap 24px. Open dark reassurance items arranged in two rows with top rules.
- **Questions container**: max width 878px · side padding 32px. Centered 814px reading field for question-and-answer rows.
- **Footer container**: max width 1552px · 5 columns · side padding 32px. Wide directory: four practical link groups plus an identity and regulatory-reference column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Conversion pill | 100px |
|  | Header pill | 9999px (pill) |
|  | Pale feature card | 16px |
|  | Framed dark panel | 6px |
| dark technical landing pages | Technical feature card | 12px |
| interactive calculators | Tool and input | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Illuminated action | `8px -8px 20px 0px rgba(255,196,250,0.25), -8px 8px 30px 0px rgba(56,205,255,0.25)` | Tightly contained pink and cyan light around the conversion pill on black. |
| interactive calculators | Tool lift | `0px 24px 24px 0px rgba(0,0,0,0.06)` | Low-contrast lift under a white interactive proof panel. |

### Surfaces

#### White canvas · level 0

**Use:** Default explanatory ground.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Large uninterrupted white fields alternate with substantial black chapters.

**Transfer:** Keep the overall light opening and pale feature language as the default.

#### Pale feature · level 1

**Use:** Product capability illustrations.

**CSS:** `background: #fafafa; border-radius: 16px`

**Observed:** A nearly white inset field without a heavy outline; media fades into the lower edge.

**Transfer:** Separate cards through tone and whitespace rather than shadows.

#### Black chapter · level 0

**Use:** Advanced capabilities, reassurance, and closing invitation.

**CSS:** `background: #000000; color: #fafafa`

**Observed:** Full-width black bands contain restrained hairline grids and lit objects.

**Transfer:** Use black to signal a deliberate change in narrative emphasis, not every other small block.

#### Dark frame · level 1

**Use:** Grouped capability proof on black.

**CSS:** `border: 1px solid rgba(255,255,255,0.15); border-radius: 6px; overflow: hidden`

**Observed:** A single enclosing frame can contain multiple flush columns separated by vertical rules.

**Transfer:** Keep edges barely visible and avoid floating bright cards in this chapter.

#### Top-lit glass · level 1

**Use:** Premium benefit callout.

**CSS:** `background: linear-gradient(#000000 0%, rgba(0,0,0,0.08) 28.81%); border: 1px solid rgba(255,255,255,0.15); border-radius: 6px; backdrop-filter: blur(10px); padding: 32px 48px`

**Observed:** A narrow horizontal white light crowns the card while the list remains dark.

**Transfer:** Reserve for one high-emphasis benefit panel rather than applying glass to all cards.

#### Policy paper · level 0

**Use:** Directory strip and the complete policy tail.

**CSS:** `background: #f3f6f9; color: #516880`

**Observed:** After the white directory, the page continues as a continuous blue-gray text field with thin boundaries.

**Transfer:** Scale its length to the actual policy content; preserve the distinction between marketing footer and supporting documentation.

#### Cyan atmosphere · level 0

**Only for:** technical product chapters

**Use:** A centered technical callout backed by subtle blue-green light.

**CSS:** `background: radial-gradient(57.47% 57.47% at 50% 42.53%, rgba(82,226,255,0.21) 0%, rgba(82,255,255,0) 100%), #000000; border-bottom: 1px solid rgba(255,255,255,0.15)`

**Observed:** The light is concentrated behind a fine technical grid, with black left around the edges.

**Transfer:** Keep the glow dim enough that white serif text leads.

#### Featured comparison column · level 1

**Only for:** plan comparisons

**Use:** A single recommended column behind table content.

**CSS:** `background: linear-gradient(183.9deg, rgba(56,195,255,0.1) 0%, rgba(34,117,153,0.1) 96.81%), linear-gradient(193.34deg, rgba(151,205,255,0.25) 0%, rgba(56,165,255,0) 28.05%); border-radius: 16px; box-shadow: 4px -4px 31px 0px rgba(151,224,255,0.23)`

**Observed:** A translucent cool-blue vertical slab crosses the horizontal table rules and glows softly at its upper edge.

**Transfer:** Highlight only one plan and leave the surrounding comparison black.

## Components

### Fixed navigation

**Use:** Persistent top navigation.

**CSS:** `position: fixed; top: 0px; display: flex; align-items: center; justify-content: center; height: 58px; padding: 8px 0px; mix-blend-mode: exclusion`

**Text style:** `navigation` — Invest Pro 400 · 16px/1

**Observed:** Identity sits left, the main menu stays centered, and two account pills sit at the right with an 8px gap. Text appears black over light and white over dark; a separate 100px-tall masked backdrop has 15px blur.

**Transfer:** Preserve the three-part balance and invert the visible colors with the chapter behind it.

### Primary button

**Use:** Default conversion action on white.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #000000; color: #ffffff; border: 1px solid #000000; border-radius: 100px; height: 54px; padding: 0px 40px`

**Text style:** `button` — Invest Pro 500 · 16px/1.37

**Observed:** A short label precedes a small right arrow; width follows the label except for a wider opening action.

**States:** Declared: hover keeps white text and changes background to rgb(27, 33, 40); focus-visible unknown; active keeps white text.

**Transfer:** Use one clear action per major promise.

### Illuminated button

**Use:** Conversion within black chapters.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: rgba(0,0,0,0.01); color: #ffffff; border: 1px solid rgba(255,255,255,0.1); border-radius: 100px; height: 54px; padding: 0px 40px; box-shadow: 8px -8px 20px 0px rgba(255,196,250,0.25), -8px 8px 30px 0px rgba(56,205,255,0.25)`

**Text style:** `button` — Invest Pro 500 · 16px/1.37

**Observed:** The glow is contained by a rounded wrapper, producing a fine luminous rim rather than a broad neon halo. Technical variants use a cyan translucent border.

**States:** Declared: hover background rgba(255,255,255,0.1) and white text; focus-visible unknown; active keeps white text.

### Header account pill

**Use:** Compact account navigation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #000000; border: 1px solid #dce2ea; border-radius: 9999px; height: 42px; padding: 0px 16px; backdrop-filter: blur(4px)`

**Text style:** `small-button` — Invest Pro 400 · 14px/1.28

**Observed:** Paired 90px-wide pills invert with the background: on white the login appears black and signup outlined; on black login appears white and signup outlined.

**Transfer:** Keep both much smaller than the main conversion action.

### Feature link

**Use:** Low-pressure continuation inside pale cards.

**CSS:** `color: #000000; margin-top: 16px; text-decoration: none`

**Text style:** `text-link` — Invest Pro 400 · 14px/18px

**Observed:** Plain centered label followed by a small right-pointing arrow; no surrounding pill.

**States:** Declared: hover color #0027b3; focus-visible and active unknown.

### Illustrated feature card

**Use:** Reusable capability explanation.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; position: relative; background: #fafafa; border-radius: 16px`

**Text style:** `card-title` — Invest Pro 400 · 24px/28px

**Observed:** Centered title, compact supporting paragraph, Feature link, then a large lower-half interface illustration. Text block has a 32px top inset and a 640px maximum width; lower artwork dissolves into the card backing.

**Transfer:** Mix half-width cards with a full-width demonstration instead of making every card identical.

### Dark capability frame

**Use:** A compact family of related capabilities.

**CSS:** `display: flex; border: 1px solid rgba(255,255,255,0.15); border-radius: 6px; overflow: hidden`

**Text style:** `eyebrow` — Invest Pro 400 · 16px/22px

**Observed:** Three contiguous columns on black each put a short title and explanation above a lower illustration. Inner content uses 40px insets, with fine vertical separators and muted disclosures near the bottom.

**Transfer:** Group related capabilities into one frame rather than separate elevated tiles.

### Question accordion

**Use:** Objection handling on focused product pages.

**CSS:** `position: relative; padding: 20px 30px 20px 0px; color: #516880; border-top: 1px solid #f1f4f7`

**Text style:** `question` — Invest Pro 400 · 16px/1.5

**Observed:** Full-width question labels carry a small downward chevron at the right. The first answer is open; answers use the body recipe. Rows occupy a centered 814px reading field. Dark variants use off-white questions and 15%-white separators.

**Transfer:** Use real product questions; keep the question controls visually simpler than feature cards.

### Footer directory link

**Use:** Practical multi-column navigation.

**CSS:** `display: block; color: #1b222c; padding: 6px 0px`

**Text style:** `directory-link` — Inter 400 · 14px/1.5

**Observed:** Placed beneath a semibold column heading with 14px separation; contact and social links share a column with two small app-download badges.

**States:** Declared: hover color rgb(0, 56, 223); focus-visible unknown; active color #1b222c.

### Top-lit benefit panel

**Use:** A high-emphasis benefit summary within a dark split callout.

**CSS:** `position: relative; background: linear-gradient(#000000 0%, rgba(0,0,0,0.08) 28.81%); border: 1px solid rgba(255,255,255,0.15); border-radius: 6px; backdrop-filter: blur(10px); padding: 32px 48px; max-width: 410px`

**Observed:** Small centered caption above a short checked list and Illuminated button; a white horizontal light rests on its top edge.

**Transfer:** Pair the panel with a large serif eligibility or invitation statement, keeping the list short.

### Numbered instruction card

**Only for:** step-by-step product explanations

**Use:** Explain an unfamiliar setup or workflow.

**CSS:** `border: 1px solid #f1f4f7; padding: 32px`

**Text style:** `sans-heading` — Invest Pro 400 · 32px/42px

**Observed:** Three flush upright cards: small two-digit step marker, 32px sans title, interface illustration, and body explanation. Shared borders make the set feel like an editorial diagram rather than three floating cards.

**Transfer:** Give each step one image with a clear highlighted detail.

### Calculator field

**Only for:** interactive calculators

**Use:** Editable assumptions in a quantified proof tool.

**CSS:** `background: #ffffff; border: 1px solid #d3dedf; border-radius: 6px; height: 58px; padding: 16px`

**Observed:** A vertical form uses labeled inputs, a select, and a range slider in the left side of a white panel; comparison bars occupy the wider right side. The select is 60px tall.

**Transfer:** Expose only inputs that materially affect the outcome, then show directly comparable outputs.

## Imagery and graphics

### Cinematic device stage

**Use:** Main opening product scene and the large object in the dark closing invitation.

**Observed:** Angled desktop and phone displays show bright, realistic interfaces against deep black with cool silver-blue rim light. The opening's 1280×600 media field has rounded corners; the devices fill most of it and extend beyond its lower edge. The closing re-stages the devices on a reflective dark tabletop.

**Transfer:** Show the new product in a credible device or physical context, emphasizing one useful state. Minimum version: a clean perspective interface panel and a smaller companion view, lit on a dark reflective ground.

**Build:** Place a bright rectangular interface in perspective over a black stage, with a smaller upright rounded rectangle in front at the right. Add a broad blue-white radial light behind the upper edge, a low soft elliptical reflection beneath, and dark masks at the outer edges. Keep text and controls readable rather than treating the screen as abstract texture.

### Dissolving interface illustration

**Use:** Pale feature cards and numbered explanations.

**Observed:** White interface fragments, charts, menus, and notifications float over nearly white backings. Select details are sharp while peripheral fragments blur or fade. The artwork occupies substantially more height than the copy above it.

**Transfer:** Reduce a new feature to one meaningful interaction and a few surrounding UI fragments. Use real labels, restrained green or blue data, and no decorative dashboard clutter.

**Build:** Layer two or three white UI panels over #fafafa, with very soft low-opacity shadows. Keep the foremost panel crisp; blur or lower opacity on background fragments. Overlay a bottom linear gradient from rgba(250,250,250,0) to #fafafa to dissolve the lower part.

### Edge light

**Use:** The premium benefit panel and restrained dark actions.

**Observed:** A thin luminous white horizontal oval crowns a dark panel. Smaller cyan and blush lights catch the edge of pill actions without filling them.

**Transfer:** Use light as a material cue, not an ambient page-wide glow. Include this concentrated lighting language in the dark invitation or proof area.

**Build:** Above a 410px-wide panel, stack a 410×14px radial white ellipse with 84% central opacity and 6.4px blur, a 328×10px sharper white center with 1px blur, and a softer 410×14px outer ellipse with 12px blur. Center the layers along the top boundary and retain black around them.

### Translucent comparison objects

**Only for:** quantified outcome product openings

**Use:** A sculptural alternative to a device hero.

**Observed:** Tall transparent blue-glass prisms and a low block sit on a black cylindrical pedestal, viewed close and partly cut off at the right edge. White and cyan specular edges, ribbed clear caps, blue backlight, and sparse floating numeric labels make a chart feel physical.

**Transfer:** Turn the product's comparative outcome into two or three geometric objects of different heights. Minimum version: extruded translucent columns with convincing highlights rather than flat chart bars.

**Build:** Use SVG or a 3D scene with two rectangular prisms on an elliptical-topped cylinder. Give each prism a nearly black front, translucent blue side, thin cyan edge, and white top highlight; add vertical narrow rounded ribs to the tallest cap. Back the objects with a broad low blue light and black left-side falloff, leaving clear space for copy.

### Contextual lifestyle photograph

**Only for:** human-context product openings

**Use:** Split hero beside a numerical or practical promise.

**Observed:** A square, softly rounded photograph shows a seated person's hands and laptop, cropped below the face. Brown leather, neutral clothing, and deep navy shadows feel tactile rather than cheerful stock photography. A bright white interface card floats centrally over the photograph.

**Transfer:** Show a real use context through hands, tools, or a close material detail; overlay one relevant UI result instead of a full dashboard.

### Workflow field and pedestal finale

**Only for:** automation product pages

**Use:** Opening explanation and the large late-page product invitation.

**Observed:** Fine orthogonal connector lines and small labeled action nodes spread across black. A slate-blue horizon illuminates a central device on a dark round pedestal, while large paired serif statements remain centered above it.

**Transfer:** Visualize the new product's input-to-result relationship with a small set of connectors and labeled outcomes; the main product object stays the focus.

**Build:** Draw thin vertical and horizontal SVG paths with low-opacity white strokes, small bright circular junctions, and dark rounded result labels. Keep the network sparse, heavier at the sides. Behind the device add a soft blue radial horizon above a black ellipse with a subtle top rim; fade outer connectors into black.

### Dark technical data art

**Only for:** dark technical landing pages

**Use:** Hero, numerical proof, and technical capability callouts.

**Observed:** Dark trading interfaces fan around a larger central screen with turquoise edge light. Other chapters use a dim cyan grid, outlined candlesticks, or gradient-filled step bars instead of photography.

**Transfer:** Use authentic domain data rather than unrelated finance graphics. Minimum version: one detailed dark interface with subdued supporting panels and a dim technical grid.

**Build:** On black, draw a fine orthogonal grid with cyan strokes at low opacity, masked radially toward the edges. Layer the central dark interface above it and smaller dark panels receding left and right. For proof, use thin outlined data marks and cyan-to-transparent fills, with the brightest line reserved for the primary result.

### Icons

**Observed:** Compact monochrome glyphs accompany benefits and actions: 14px arrows, small 10–12px utility symbols, 24px social marks, and simple checks in modest square backings. Icons generally inherit black, white, or muted text color rather than using multicolor badges.

**Transfer:** Choose simple compact arrows, checks, and domain symbols. Keep illustration-level detail in the product scene, not in oversized feature icons.

## Section recipes

How recurring sections are built.

### First screen: Editorial product-stage opening

**Observed:** A white first screen starts with Fixed navigation, then an 80px/1 light serif headline at 160px top padding, left aligned in an 810px measure. It spans roughly two thirds of the 1280px content width and breaks into two lines. Below, three compact benefit markers sit left while the 54px Primary button sits right on the same horizontal band. After a 32px gap a rounded 1280×600 cinematic device scene begins. Back to front: white canvas, editorial text and markers, black action, then a black media stage containing cool-lit bright device screens. Within the first 900px, the headline, benefit row, action, and substantial upper portion of the product object are visible; the bottom of the stage and the next chapter remain below the fold.

**Transfer:** Use a similarly concise category promise, three meaningful benefit markers, and one dominant product scene. Without device media, build the perspective interface composition described in Cinematic device stage. Focused product openings can instead center a 76px promise above a demonstration, split it beside a square contextual photograph, or place a left-aligned promise beside a translucent sculptural outcome on black.

**Avoid:** Do not replace the asymmetric headline-and-action composition with a generic centered headline, long paragraph, two buttons, and a small dashboard thumbnail. Do not shrink the scene to fit the whole page introduction above the fold.

**Text style:** `display` — Denton 300 · 80px/1

### Two-tone section lead

**Observed:** A small sentence-case Eyebrow sits 8px above a centered Heading in a 780px block; a second phrase uses muted gray at the same size. The heading block ends 64px before the feature field.

**Transfer:** Write a primary outcome followed by a concise reframing or reassurance. Keep both phrases in the same editorial voice.

**Text style:** `heading` — Denton 300 · 48px/54px

### Editorial word field

**Observed:** A broad white band carries several centered wrapping rows of 48px serif product links. Small 6px square gray separators with 16px side margins punctuate the words; compact black numeric badges sit beside selected entries. The band has faint top and bottom rules and 112px top padding.

**Transfer:** Use as a browsable field of the new product's categories or capabilities rather than a conventional tile index.

### Pale modular feature field

**Observed:** Illustrated feature card forms a 2-column grid with 24px gaps. Half-width cards are about 628×528px; selected 1280px-wide cards interrupt the pattern. Card text is centered above large dissolving interface artwork.

**Transfer:** Alternate concise independent benefits with a wide demonstration of the core interaction; the full-width feature is a narrative emphasis, not a fixed repeating ratio.

### Dark capability and trust chapters

**Observed:** A Black chapter uses 96px or 160px vertical padding and a two-tone serif lead. Dark capability frame groups three demonstrations; reassurance uses an open three-column grid with 24px gaps, top hairlines, 20px sans titles, and compact muted paragraphs. A cool-lit dark object can occupy one side behind the reassurance content.

**Transfer:** Move from impressive capabilities to concrete reasons to trust them. Support each trust assertion with an actual mechanism or operating fact.

### Quantified proof tool

**Observed:** A centered 52px serif claim and 16px supporting text lead into a 1060px white tool panel. The left form is 380px wide; the wider right side compares three aligned outputs with simple bars. A 6px radius, pale borders, and soft Tool lift distinguish the panel without colorful framing.

**Transfer:** Let readers change a meaningful assumption and see comparable outcomes with clear caveats.

**Text style:** `product-heading` — Denton 300 · 52px/58px

### Comparison on black

**Observed:** A large two-tone serif heading precedes a sparse ruled comparison. Plan names and short actions sit above aligned rows. One variant uses Featured comparison column to illuminate the recommended plan; another uses a conventional dark grid with compact white conversion pills at the bottom.

**Transfer:** Compare a few understandable choices with consistent row labels. Use the lit slab only when a recommended option deserves real emphasis.

### Example carousel

**Observed:** A centered two-tone heading introduces a horizontal row of compact white example cards with 16px gaps and 12px radii. A taller active card in the middle has a restrained glow while peripheral cards fade into the white edge. Small tags sit low inside the cards; two outlined 40px circular arrows sit below.

**Transfer:** Show believable tasks or use cases rather than generic testimonials. Make the focused example readable while neighboring cards indicate breadth.

### Monumental numeric proof

**Observed:** On black, a centered serif statement leads into two 102px sans statistics, each accompanied by short cyan annotations. A thin low-contrast data visualization spans the lower part, and a hairline closes the chapter.

**Transfer:** Use at most a small set of strong, defensible numbers and a domain-relevant visualization; preserve the contrast between editorial heading and utilitarian numerals.

**Text style:** `stat` — Invest Pro 400 · 102px/1

### Closing product invitation

**Observed:** A Black chapter around 720px tall places a 52px serif invitation on the left with Illuminated button 28px below. A large bright device composition takes the right side and reaches the section edges. Low on the left are a compact review quote, small stars, and a fine-outlined review badge. The technical variant centers a 76px invitation above a dark screen; the automation variant uses the Workflow field and pedestal finale before a dark question section.

**Transfer:** Return to the product object with a clear invitation and a small independent proof cue. Reuse the lighting language of the opening rather than introducing an unrelated illustration.

**Text style:** `heading-dark` — Denton 300 · 52px/1.11

### Questions and complete ending

**Observed:** Question accordion sits in a centered narrow reading field with a 32px sans heading and about 40px before the rows. The white Footer directory follows the final marketing content, using five columns, 32px side padding, and 65px top padding. A thin-bordered blue-gray directory strip leads into a continuous Policy paper field with small paragraphs, grouped labels, inline blue references, and a final disclosures link. The automation format places questions after its large product finale; other product formats place questions before the closing invitation.

**Transfer:** Separate conversion, navigation, and policy content into distinct visual strata. Keep the real policy tail complete without treating its text density as the model for marketing copy.

## Page flow

**Storyline:** Promise → tangible product demonstration → capability breadth → quantified or operational proof → reassurance and objections → renewed invitation → practical navigation and policy detail.

### Broad platform marketing

1. **Promise** — Left editorial headline above a benefit row and cinematic product stage.
2. **Breadth** — Wrapping serif category field followed by a centered capability lead.
3. **Capability chapters** — Pale modular interface cards, a dark advanced-capability frame, and another feature field.
4. **Reassurance** — Compact numeric proof, premium split callout, and dark trust grid.
5. **Closing call** — Left invitation beside a large lit device, followed by white directory and blue-gray policy tail.

**Transfer:** Introduce the whole offering through one main product object, then let different grid formats communicate breadth and depth.

### Advanced technical-product conversion

1. **Promise** — Centered white serif promise and turquoise response over black with dark interface fan.
2. **Quantified proof** — Tiered step diagram and a sparse comparison table.
3. **Capability chapters** — Atmospheric technical callout, paired monumental statistics, and dark illustrated feature grid.
4. **Objection handling** — Contextual dark image callout and narrow dark accordion.
5. **Closing call** — Centered large invitation above the product screen; a short footnote bridge leads to the shared directory and policy ending.

**Transfer:** Use an immersive dark theme when expert functionality and measurable advantage are the central story.

### Outcome-led product with interactive comparison

1. **Promise** — Left serif outcome beside sculptural translucent comparison objects on a blue-lit black stage.
2. **Quantified proof** — White interactive calculator with comparable outputs.
3. **Choice** — Black plan comparison with one softly glowing column.
4. **Capability breadth** — White example carousel showing practical automation tasks.
5. **Objection handling** — Narrow white questions before the dark device-led closing invitation, directory, and policy tail.

**Transfer:** Move from an understandable outcome to personally adjustable proof, then explain the available choices.

### Explain a new packaged product

1. **Promise** — Split white opening combines a two-tone serif statement, practical benefit row, and contextual photograph with a floating result card.
2. **Product explanation** — Three numbered instructional cards introduce the mechanism.
3. **Capability chapters** — Pale half-width and full-width interface cards.
4. **Transparency** — Wide ruled inventory with expandable rows followed by a dark comparison table.
5. **Objection handling** — White accordion leads to a dark device invitation and the shared directory and full policy ending.

**Transfer:** Use process steps and inspectable detail to make an unfamiliar bundle feel comprehensible.

### Introduce a new interaction model

1. **Promise** — Centered 76px serif promise over a dark workflow demonstration.
2. **Onboarding** — Two alternative starting paths, then a wide cinematic video still.
3. **Use cases** — Example carousel with one active center card.
4. **Reassurance** — Control and auditability chapters use pale UI fragments with short explanatory columns.
5. **Capability expansion** — Dark research demonstration followed by a monumental category statement and workflow-pedestal invitation.
6. **Objection handling** — Dark accordion after the finale, then white directory and blue-gray policy tail.

**Transfer:** Teach the interaction through examples, then explain user control before expanding the ambition of the promise.

## Writing

Confident and editorial about the promise, practical and specific about the mechanism. Short declarative phrases carry ambition while detailed support stays matter-of-fact and openly qualifies variable outcomes.

**Do not copy:** Do not reuse Public's identity, product names, proprietary interface artwork, yield or rebate figures, regulatory claims, exclusivity claims, review quotations, or endorsements. Replace them with the new product's own substantiated content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for outcomes and control. Use we or our sparingly to explain the mechanism; product names can lead straightforward factual sentences.
- **Rhythm:** Headlines often use two brief sentence fragments separated by periods. Support is usually one or two compact sentences, with a practical verb near the start. Parenthetical asides add a little personality without overwhelming the professional tone.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A category-level promise or two compact outcome fragments. | 5–10 words | “The investing platform for the agentic age”<br>“AI Agents. For your portfolio.” |
| Section heading pair | Confident statement followed by a short reframing or reassurance. | 4–10 words | “Bond investing. Minus the complexity.”<br>“Stay in complete control. Always.” |
| Feature title | Direct verb plus useful outcome; occasional two-fragment contrast. | 3–8 words | “Track all your earnings”<br>“Reset the timeline. Keep the strategy.” |
| Supporting explanation | Explain an actual action and its reader benefit rather than repeating the headline. | 20–45 words | “View a monthly breakdown of your earnings from every income-generating asset you own. Plus, see a forecast of your earnings for the year ahead.” |
| Primary action | Short plain verb phrase, not a slogan. | 2–3 words | “Get started”<br>“Learn more” |
| Reassurance | State control or transparency in ordinary language before explaining the safeguard. | 4–12 words | “Agents only do what you explicitly tell them to do.”<br>“Secure by design. Transparent by choice.” |

**Words and phrasing to use:** your; get started; manage; track; choose; build; control; real-time; by default; no minimums; how it works

**Avoid:** revolutionary ecosystem; unlock limitless potential; magic; game-changing; effortlessly supercharge; guaranteed results

**Rules:**

- Put one understandable outcome in the heading and the actual mechanism in the supporting sentence.
- Let short parallel fragments carry emphasis instead of exclamation marks.
- Use numbers only when useful and defensible; place a concise qualification near the relevant claim.
- Name the user's choices and controls explicitly when explaining automation.
- Keep a light nerdy aside rare and parenthetical; do not turn the whole page into banter.

## Do's and Don'ts

### Do

- Use 80px/1 Denton 300 for the default opening, with an approximately 810px headline measure.
- Maintain the 1280px desktop content field and 24px feature gutters.
- Give the main conversion action a 54px height, 100px radius, and 40px horizontal padding.
- Use #a8b4bf for the second phrase of a paired headline at the same size as the first.
- Keep pale card titles at 24px/28px and descriptions at 14px/1.42.
- Use 112px vertical padding for major explanatory sections and 64px between heading blocks and grids.
- Keep black chapter outlines at 1px and roughly 15% white.
- Carry the cool-lit main product object into a substantial dark invitation near the end.

### Don't

- Do not turn serif promises into bold geometric sans headlines; the default display weight is 300.
- Do not apply negative tracking throughout; the main type recipes use normal tracking.
- Do not make the default conversion button a blue rectangle; it is a black 54px pill on white.
- Do not use 16px radii for every object: shared dark frames and tools use 6px, technical feature cards use 12px.
- Do not flood white explanatory sections with cyan; reserve saturated highlights for technical data and lit scenes.
- Do not put heavy shadows under every feature tile; the default card is a flat #fafafa field.
- Do not expand feature copy into large editorial paragraphs; compact cards use 14px descriptions.
- Do not end with only a conversion banner; retain distinct navigation and supporting policy strata.

## Motion and responsive

### Motion

**Observed:**

- Primary and illuminated actions declare 0.2s transitions.
- Pale feature cards declare transform 0.3s transitions.
- Illuminated border elements declare a 3s linear infinite borderTurn animation.
- Other declared behaviors include opacity reveals, gradient rotation, and workflow progress animation.

**Transfer:**

- Keep animated emphasis in luminous rims, product demonstrations, and active workflow details rather than making all editorial text move.
- Use the declared short action transitions to preserve the crisp contrast between static editorial copy and responsive product objects.

**Unknown:**

- Playback choreography, scroll trigger timing, and the visual path of every border animation are not established.
- No specific reduced-motion layout or mobile animation behavior is established.

### Responsive

**Observed:**

- Desktop composition is established at 1440×900px.
- Styles declare numerous width breakpoints, notably around 640px, 768px, 992px, 1024px, 1200px, and 1280px; no single simplified breakpoint system is established.

**Transfer:**

- On narrow layouts, preserve the headline before the benefit row and main scene; allow the right-side action to join the benefit block rather than shrinking its 54px height.
- Stack the two-column pale feature field and split photograph opening while preserving the large image-to-copy ratio.
- Keep comparison labels aligned and allow a dedicated horizontal reading area rather than compressing the numerical content into illegibility.

**Unknown:**

- Exact mobile type sizes, padding, navigation transformations, card order, and image framing are not established; narrow-screen rules above are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
