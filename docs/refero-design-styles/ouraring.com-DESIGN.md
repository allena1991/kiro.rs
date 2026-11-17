# Oura — human warmth, engineered depth

## Overview

An editorial, tactile style that makes sophisticated technology feel close to everyday life. Warm cream and sandstone surround slender serif headlines, plainspoken grotesk text, intimate lifestyle photography and polished product renderings. The pages are spacious and predominantly light, with substantial charcoal chapters for technical depth and independent proof; saturated color lives mostly in the imagery rather than the furniture.

### Essentials

- Human scale meets oversized product presence: the default opening is a 900px-tall warm studio scene, a narrow left-aligned 80px/1.1 light serif headline and a dramatically enlarged object or gesture occupying the right half. Without photography, use a carefully lit product still on a continuous warm backing.
- Headlines have the elegance of a narrow magazine masthead, not the weight of a technology dashboard: Editorial New at 80px, weight 300, -0.05em tracking for the opening; 68px/1.1, weight 400, -0.03em for centered chapter statements.
- Conversion is a small, decisive blue pill in a world of warm neutrals: 48px height, 12px 24px padding, fully rounded corners and bold 16px text. Exploratory actions use the same shape in sandstone ink with regular-weight text.
- Color belongs to people and materials: cream #f7f1e8 dominates the default page, #efe6db distinguishes quote and proof cards, and #1c1b1a creates full-width evidence chapters. Blue #2a72de stays concentrated in conversion actions rather than headings or large bands.
- Benefits become photographic windows: 493px-wide lifestyle cards sit in an overflowing rail with 24px gaps, 12px corners, translucent category capsules, a cream circular plus and 40px light sans text at the foot. Use contextual photographs or physical process details when the product itself is not photogenic.
- Proof receives editorial scale and the ending changes material: give a quantified result a full headline treatment or a serif number strip, then use a dark editorial proof chapter and a warm charcoal footer with a 40px serif newsletter invitation. The preceding page shell rounds away above the footer instead of ending at a hard rectangular seam.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversion blue | `#2a72de` | `--color-action` | action | Small purchase actions; not a decorative section color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action white | `#ffffff` | `--color-white` | text | Blue-button labels and very high contrast text over dark photography. |
| Warm cream | `#f7f1e8` | `--color-canvas` | background, text, surface | Default page canvas; inverse text and pale controls on dark or photographic surfaces. Also the source hue for 10% translucent cream glass. |
| Sandstone card | `#efe6db` | `--color-stone` | surface, background | Quote cards, research cards and warm photographic backing. |
| Light rule | `#d3d1ce` | `--color-rule` | border | Thin rail progress rules on light backgrounds. |
| Warm gray | `#a8a5a0` | `--color-muted` | text | Footer invitation, column labels and secondary footer copy. |
| Medium gray | `#838280` | `--color-secondary` | text, border | Qualifications and supporting references; 20% of this hue forms a faint reference separator. |
| Sandstone ink | `#4a4741` | `--color-ink` | text, action, border | Default headlines, body copy, exploratory buttons and dark footer input. A 10% layer of this hue supplies the translucent navigation tint. |
| Warm charcoal | `#1c1b1a` | `--color-dark` | background, action | Default dark editorial chapters and exploratory-button hover. |
| Quote black | `#000000` | `--color-quote-ink` | text | Testimonial text and selected editorial card headlines. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| immersive hardware product pages | Product porcelain | `#f3f1f0` | `--color-product-canvas` | background, text | Cooler product-story canvas and inverse type over metal renderings. |
| immersive hardware product pages | Product near-black | `#19191c` | `--color-product-ink` | text, surface | Hardware-page text, selected feature tabs and inset film backing. |
| hardware specification sections | Specification gray | `#e6e4e2` | `--color-technical-panel` | surface | Large inset technical-specification panel. |
| research and expert pages | Research charcoal | `#262626` | `--color-research-dark` | background | Research editorial and advisor chapters, slightly lighter and less warm than the default dark band. |

## Typography

- **Editorial New** — Default marketing display, section headings, quotations and prominent numbers. Tall, narrow, high-contrast editorial serif with delicate strokes and compact word shapes. OpenType features: "dlig" 0, "kern", "liga" 0, "onum" 0, "ss01" 0, "tnum" 0. If unavailable, use **Instrument Serif**. Use its regular and italic cuts; preserve narrow line lengths and tune wrapping rather than adding weight. Font stack: "Editorial New", "Instrument Serif", Georgia, serif.
- **AkkuratLL** — Body copy, navigation, actions, card headings and research-page display. Understated grotesk with open counters; light large headings balance regular utility text. OpenType features: "dlig" 0, "kern", "liga" 0, "onum" 0, "ss01" 0, "tnum" 0. If unavailable, use **Roboto**. Use 300, 400 and 700; keep the unusually tight tracking on larger supporting text. Font stack: "AkkuratLL", "Roboto", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Editorial New | 300 | 80px | 1.1 | -0.05em | Default opening headline, usually a short two-line phrase. |
| heading-lg | Editorial New | 400 | 68px | 1.1 | -0.03em | Centered chapter statements and headline-sized quantified promises. |
| heading | Editorial New | 400 | 56px | 1.1 | normal | Left-aligned split-section heading. |
| photo-heading | AkkuratLL | 300 | 40px | 1 | normal | Benefit headlines over photographic rail cards. |
| feature-article-heading | AkkuratLL | 400 | 40px | 1.25 | -0.05em | Large headline anchored near the bottom of a photographic feature article. |
| newsletter-heading | Editorial New | 300 | 40px | 1.25 | -0.025em | Footer newsletter invitation. |
| lead | AkkuratLL | 400 | 24px | 1.25 | -0.05em | Centered support line under a large serif chapter statement. |
| article-heading | AkkuratLL | 400 | 24px | 1.25 | normal | Editorial article-card headline. |
| quote | Editorial New | 100 | 24px | 1.25 | normal | Testimonial text, including a small opening quotation mark on its own line. |
| hero-support | AkkuratLL | 400 | 20px | 1.1 | -0.025em | Concise default opening support, within a 480px measure. |
| body | AkkuratLL | 400 | 20px | 1.5 | normal | Explanatory paragraphs in feature and trust sections. |
| utility | AkkuratLL | 400 | 16px | 1.5 | normal | Navigation, exploratory actions, footer links and short supporting labels. |
| utility-bold | AkkuratLL | 700 | 16px | 1.5 | normal | Conversion labels and footer column headings. |
| eyebrow | AkkuratLL | 700 | 16px | 1.5 | 0.1em, uppercase | Feature-chapter label above the heading. |
| caption | AkkuratLL | 400 | 12px | 1.5 | normal | Photographic capsule labels and newsletter reassurance. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| immersive hardware product pages | product-display | Editorial New | 400 | 128px | 1.5 | -0.05em | Centered hero line between dramatically enlarged product edges. |
| immersive hardware product pages | product-heading | Editorial New | 400 | 98px | 1.1 | normal | Monumental centered chapter headings within a 1024px measure. |
| benefit-explainer pages | photo-display | Editorial New | 300 | 80px | 1.25 | -0.05em | White editorial opening over full-height lifestyle photography. |
| immersive hardware product pages | product-number | Editorial New | 300 | 80px | 1.1 | -0.025em | Large percentage in a three-column hardware proof strip. |
| research and expert pages | research-display | AkkuratLL | 300 | 80px | 1.25 | -0.05em | Three-line opening promise over a dark product rendering. |
| research and expert pages | research-heading | AkkuratLL | 300 | 68px | 1.25 | -2px | Large research chapter heading, centered or split with body text. |
| expert portrait chapters | expert-heading | AkkuratLL | 300 | 68px | 1.1 | -2px | First line of a mixed-family expert introduction. |
| expert portrait chapters | expert-emphasis | Editorial New | 300 italic | 68px | 1.1 | -2px | Indented second line of an expert introduction. |
| technical research demonstrations | glass-number | Editorial New | 200 | 68px | 1.25 | -2px | Large metric in a translucent card over product imagery. |
| credibility summaries | credibility-number | Editorial New | 300 | 56px | 1 | normal | Large numerals above compact explanations in a credibility strip. |

**Notes:**

- The serif carries aspiration; the sans carries explanation and interaction. Research pages deliberately reverse the heading emphasis toward light sans, retaining serif numerals and a single italic expert-introduction line.
- Do not normalize tracking across the scale: the default opening and 24px centered support both use -0.05em, while the 56px split heading and 98px hardware heading retain normal tracking.
- Center chapter statements but left-align split-section copy and photographic card text. Serif headlines should have narrow, intentional wraps; body paragraphs retain natural reading width.

## Layout

**Density:** Airy: editorial statements and image-led chapters have long breathing spaces, while their controls remain compact.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Inline icon gap and small label-to-caption separation. |
| 16px | Heading-to-opening-support gap, paired-action gap and compact research-grid gutters. |
| 24px | Standard card padding, rail gutter and centered heading-to-support gap. |
| 32px | Feature-article inset and footer newsletter-grid row gap. |
| 40px | Support-to-action separation and testimonial-card padding. |
| 48px | Footer newsletter-to-link-grid separation. |
| 64px | Desktop side margin and dark editorial chapter padding. |
| 80px | Default major-section vertical padding and media separation. |
| 120px | Expanded credibility-section breathing room. |
| 128px | Centered statement-section top and bottom breathing room. |

### Containers and grids

- **main-container**: max width 1312px · side padding 64px. Centered desktop content at a 1440px viewport. The underlying composition uses 22 equal internal tracks between outer margins; images can escape the main container to the right.
- **statement-measure**: max width 1024px. Large centered section statements. Supporting copy occupies a narrower centered measure around 835px.
- **split-feature**: 2 columns · gap 0px. A roughly 477px text column on the left with a wider 839px image extending to the right edge. Text is vertically centered against the media.
- **photo-rail**: 3 columns · gap 24px. 493px-wide cards intentionally extend past the right viewport edge. Show part of the next card, then a thin progress rule and right-aligned round controls below.
- **proof-grid**: 3 columns · gap 16px. Compact research publication cards across the main container; testimonial variant uses 30px gutters and 40px inner padding.
- **footer-grid**: 4 columns · gap 24px. Four link columns sit beside a 384px newsletter column, separated by 48px. A top row pairs a subdued identity mark with payment or trust badges.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | text-cards | 8px |
|  | photo-cards-and-input | 12px |
|  | film-and-large-media | 24px |
| hardware specification sections | specification-panel | 40px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| input-inner-edge | `inset 0px 1px 0px 0px rgba(255,255,255,0.06)` | A subtle top edge inside the newsletter input; cards otherwise rely on tonal separation rather than elevation. |

### Surfaces

#### Cream canvas · level 0

**Use:** Default marketing page foundation.

**CSS:** `background: #f7f1e8; color: #4a4741`

#### Sandstone card · level 1

**Use:** Quotes and compact research proof.

**CSS:** `background: #efe6db; border-radius: 8px; box-shadow: none`

**Observed:** Low-contrast, flat cards without visible perimeter borders.

**Transfer:** Separate the card from the canvas through warmth and tone rather than a raised white-panel effect.

#### Dark editorial band · level 0

**Use:** Independent proof, material demonstrations and lower-page editorial content.

**CSS:** `background: #1c1b1a; color: #f7f1e8`

**Observed:** Full-width dark chapters contain a mixture of photography and pale article cards.

**Transfer:** Use a sustained dark chapter, not a scattered collection of black boxes.

#### Navigation glass · level 2

**Use:** Subtle navigation backing as it passes over the page.

**CSS:** `background: rgba(74,71,65,0.1); backdrop-filter: blur(32px); border-radius: 8px`

**Observed:** Inset 24px from each side, around 65px tall; the glass is visually subordinate to the logo and navigation.

**Transfer:** Let the underlying scene determine its visible tone.

#### Photographic glass · level 2

**Use:** Legible category capsules and technical overlays on photographs.

**CSS:** `background: rgba(34,36,40,0.4); backdrop-filter: blur(24px); border-radius: 24px`

**Observed:** Dark tinted glass labels sit inside the lifestyle card; technical research cards instead use 10% cream tint with 12px corners.

**Transfer:** Keep the photograph visible through the surface; never substitute opaque dashboard chrome.

#### Footer atmosphere · level 0

**Use:** Shared ending beneath the rounded page shell.

**CSS:** `background: radial-gradient(ellipse at top left, #4a4741 0%, #1c1b1a 100%); color: #a8a5a0`

**Observed:** A very soft warm-gray illumination at the upper left fades into charcoal. It is not a logo-sized graphic or a bright colored glow.

**Transfer:** Match the soft tonal drift; exact gradient stops are not essential.

#### Porcelain product canvas · level 0

**Only for:** immersive hardware product pages

**Use:** Cooler ground for product renderings and finish galleries.

**CSS:** `background: #f3f1f0; color: #19191c`

#### Specification panel · level 1

**Only for:** hardware specification sections

**Use:** A distinct technical reference area near the end of a product story.

**CSS:** `background: #e6e4e2; border-radius: 40px; margin-left: 16px; margin-right: 16px`

**Observed:** One large inset panel groups a product accessory still and a two-column specification grid.

**Transfer:** Use dense factual content here without turning the entire marketing page into a table.

#### Research metric glass · level 2

**Only for:** technical research demonstrations

**Use:** Numbers over macro product imagery and metric lists over lifestyle cards.

**CSS:** `background: rgba(247,241,232,0.1); backdrop-filter: blur(24px); border-radius: 12px`

**Observed:** The visible warm gray or brown is inherited from the photograph beneath the translucent cream layer.

**Transfer:** Use real image texture behind the glass so the panel feels materially connected to the scene.

## Components

### Navigation

**Use:** Persistent brand navigation across the opening and scroll.

**CSS:** `padding: 8px 0px; color: #4a4741`

**Text style:** `utility` — AkkuratLL 400 · 16px/1.5

**Observed:** Identity at left, a small centered group of four text destinations with understated chevrons, and an outlined circular cart at right. The Navigation glass is a separate backing layer; navigation on dark imagery switches to pale text.

**States:** Declared: hover cart border becomes #4a4741 with a 10% sandstone-ink fill; focus-visible outline is 2px solid #3184ff with 4px offset.

**Transfer:** Use a short product-oriented information architecture; keep the header a light overlay rather than a heavy toolbar.

### Primary button

**Use:** Primary conversion action in the opening and purchase-oriented chapters.

**CSS:** `background: #2a72de; color: #ffffff; border-radius: 9999px; padding: 12px 24px; height: 48px`

**Text style:** `utility-bold` — AkkuratLL 700 · 16px/1.5

**Observed:** Compact standalone pill, usually without an icon. A hardware product opening instead uses a pale pill over its metal-gray scene; the compact sticky product action is 40px tall.

**States:** Declared: hover background #2056a6; focus-visible outline 2px solid #3184ff with 4px offset.

### Secondary button

**Use:** Exploration, education and membership actions.

**CSS:** `background: #4a4741; color: #f7f1e8; border-radius: 9999px; padding: 12px 24px; height: 48px`

**Text style:** `utility` — AkkuratLL 400 · 16px/1.5

**Observed:** Regular-weight label; pairs sit 16px apart. On dark imagery a cream variant reverses the contrast and can include an up-right arrow.

**States:** Declared: hover background #1c1b1a; focus-visible outline 2px solid #3184ff with 4px offset.

### Round control

**Use:** Expand photographic cards and navigate horizontal rails.

**CSS:** `background: #f7f1e8; color: #4a4741; border-radius: 9999px; padding: 20px; width: 53px; height: 53px`

**Observed:** A small plus is centered in the pale disc at the upper-right of an image. Rail navigation instead uses paired arrow discs below the content and progress rule; smaller arrow discs are about 45px wide.

**States:** Declared: focus-visible outline 2px solid #3184ff with 4px offset.

**Transfer:** Make the icon descriptive through its accessible label while keeping the visible control minimal.

### Lifestyle card

**Use:** Image-led benefit discovery in a horizontal rail.

**CSS:** `border-radius: 12px; overflow: hidden; width: 493px; color: #f7f1e8`

**Text style:** `photo-heading` — AkkuratLL 300 · 40px/1

**Observed:** Full-bleed portrait photography; a Photographic glass category capsule at upper-left, Round control at upper-right and a short headline at lower-left. Text and controls are inset 24px. Tall benefit cards and shorter closing discovery cards share the same visual language.

**Transfer:** Use one tangible reader outcome per card, not a feature checklist.

### Testimonial card

**Use:** Human proof in a three-column group.

**CSS:** `background: #efe6db; border-radius: 8px; padding: 40px; display: flex; flex-direction: column`

**Text style:** `quote` — Editorial New 100 · 24px/1.25

**Observed:** A small dark category tag precedes the opening quotation mark; the quote occupies the center and a small circular portrait plus bold attribution closes the card. Equal-height cards feel like printed editorial excerpts.

**Transfer:** Use authentic concise quotations and keep the subject tag visually smaller than the testimony.

### Article card

**Use:** Independent coverage and publication summaries.

**CSS:** `background: #f7f1e8; border-radius: 8px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `article-heading` — AkkuratLL 400 · 24px/1.25

**Observed:** Headline sits at top-left, with a dark circular up-right arrow at lower-right; research versions can add publication and date. Usually stacked beside a larger photographic article. Compact research-grid versions use Sandstone card instead.

**Transfer:** Let title length determine the interior whitespace, while keeping the arrow aligned across a group.

### Newsletter input

**Use:** Email subscription within the footer invitation.

**CSS:** `background: #4a4741; border-radius: 12px; padding: 8px 48px 8px 20px; width: 320px; height: 40px; box-shadow: inset 0px 1px 0px 0px rgba(255,255,255,0.06)`

**Text style:** `utility` — AkkuratLL 400 · 16px/1.5

**Observed:** One quiet rounded input with an embedded right-pointing submit arrow. Small muted privacy reassurance sits below; there is no separate large submit button.

**Transfer:** Keep the form subordinate to the editorial invitation.

### Footer columns

**Use:** The shared practical ending after the final editorial or conversion chapter.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); gap: 24px`

**Text style:** `utility` — AkkuratLL 400 · 16px/1.5

**Observed:** Muted bold category headings lead pale regular-weight links. Four columns sit to the right of the newsletter invitation. A thin ink-colored rule separates the main grid from a low legal row and an outlined language pill.

**Transfer:** Group destinations by reader intent instead of making every link a button.

### Credibility column

**Only for:** credibility summaries

**Use:** A proof strip with large numbers and compact explanatory copy.

**CSS:** `display: flex; flex-direction: column; align-items: center; padding: 0px 16px; border-right: 1px solid #4a4741`

**Text style:** `credibility-number` — Editorial New 300 · 56px/1

**Observed:** Three evenly divided columns have centered serif figures, a 20px gap before utility-sized explanation and a thin vertical rule between columns, omitted on the final item. Hardware variants use 80px numbers and a small circular icon above; dark technical variants use four smaller number groups.

**Transfer:** Use a small set of independently defensible metrics with a clear label and qualification.

### Finish tile

**Only for:** hardware choice galleries

**Use:** Final product-choice gallery rather than a generic closing banner.

**CSS:** `padding: 0px 32px; color: #19191c`

**Text style:** `article-heading` — AkkuratLL 400 · 24px/1.25

**Observed:** A 300px square isolated product render sits above a centered finish name and small optional descriptor. Tiles occupy a horizontally clipped rail with 48px gaps, under a 98px centered heading and paired outline arrow controls.

**Transfer:** For another product, show tangible editions, materials or configurations as consistently lit isolated objects.

## Imagery and graphics

### Warm studio gesture

**Use:** Default opening and key human-product scenes.

**Observed:** An oversized hand wearing a small reflective product enters from the top-right and makes a playful walking gesture on a warm seamless studio floor. Natural skin detail, patterned fabric, dark nail polish and a faint grounded contact shadow add specificity. The left half stays almost empty for text; the product is present without a diagram or callout.

**Transfer:** Photograph a human interaction that demonstrates the product's physical scale or benefit, with soft directional light and a cream seamless backing. Minimum acceptable alternative: a high-resolution isolated product still with believable contact shadow, placed asymmetrically at the same oversized scale.

### Intimate everyday photography

**Use:** Benefit rails, trust stories and film sections.

**Observed:** Tight views of resting faces, touching hands, exercise recovery and shared domestic moments. Warm daylight, real skin texture and muted fabric colors dominate. Subjects are cut close to the edges rather than posed in the middle of a clean stock-photo rectangle; panels frequently devote more area to image than text.

**Transfer:** Use candid scenes of the new product in ordinary life, emphasizing touch, proximity and natural light. Preserve enough dark or calm image area for pale labels and headings.

### Interface bouquet

**Use:** Product demonstration after a headline-sized result.

**Observed:** Five tall app screens form a fan-like stepped grouping on cream: the center screen sits highest and neighbors descend outward. Dark multicolored interface themes remain inside the devices. A second variant places three perspective phones over a dark rounded panel.

**Transfer:** Show a compact set of actual product screens as a single composed image, with a dominant center view and two subordinate views. For non-software products, arrange one primary object and supporting detail stills with the same stepped hierarchy.

**Build:** Place five rounded rectangular screen images in a centered row with slight overlap; raise the central screen, lower its two immediate neighbors, then lower the outside pair again. Clip overflow at the section base so the composition feels larger than its frame. Do not recreate interface controls as marketing-page decoration.

### Footer tonal illumination

**Use:** The shared atmospheric closing surface.

**Observed:** A restrained soft warm-gray lift in the upper-left fades to charcoal at the right and bottom. It supports small muted text rather than competing with it.

**Transfer:** Recreate the tonal material with Footer atmosphere; the new brand's identity remains a modest mark rather than monumental lettering.

**Build:** Use a full-width charcoal base and one broad radial layer centered near the upper-left, fading from sandstone ink to transparent over most of the footer width. Extend the background 48px behind the preceding rounded page shell so the seam remains continuous.

### Polished material macro

**Only for:** immersive hardware and technical explanation pages

**Use:** Immersive opening, construction proof, films and isolated finish galleries.

**Observed:** Reflective metallic curves appear at radically different scales: giant product edges clipped beyond opposite corners, an exploded stack floating over warm beige, and close interior details with tiny green or red sensor lights. Reflections are smooth and studio-controlled, never chrome clip art. A cool gray field backs the opening; pale porcelain supports isolated objects later.

**Transfer:** Use physically plausible 3D or macro photographs with broad softbox reflections. Minimum acceptable alternative: one excellent studio product photograph, enlarged and selectively framed, plus a clean side-by-side detail photograph. Keep technical lights local to the object.

**Build:** For a construction diagram, separate 6–10 actual product layers along one horizontal perspective axis, retain a shared center and consistent elliptical projection, and render with broad cream top light plus a dark side reflection. Use a warm neutral backing with a faint grounded shadow. For the hero, place two differently scaled object silhouettes beyond opposite corners over a broad cool-gray gradient, leaving the center readable; use a real product image rather than drawing generic metallic rings.

### Expert portrait rail

**Only for:** expert portrait chapters

**Use:** Human authority near the end of research-led pages.

**Observed:** Color portraits in 277px by 370px rounded panels, tightly framed from head to torso, with varied natural environments rather than a uniform cutout wall. Cream plus discs sit at the top-right; the rail reveals part of another portrait.

**Transfer:** Use real contributors with consistent framing, not identical artificial headshots. Keep photographic color and individualized backgrounds.

### Icons

**Observed:** Small simple monochrome SVG symbols inherit pale cream or sandstone ink. Arrows are commonly 18px, plus signs about 13px and category symbols around 20–24px. Up-right arrows mark outbound reading; right/left arrows navigate rails. Functional pictograms appear within discs or next to capsule labels, not as large decorative illustrations.

**Transfer:** Choose one restrained icon family with simple open forms and visually light strokes. Keep symbols optically small inside generous discs and avoid multicolor icon packs.

## Section recipes

How recurring sections are built.

### First screen: Human studio opening

**Observed:** A complete 900px opening uses a warm seamless image as its back layer, an understated navigation overlay above it, then left-aligned text and a small Primary button. The studio gesture occupies most of the right half and nearly the full height; the text occupies substantially less than half the width. The 80px display breaks into two short lines, followed by a 20px support sentence within 480px, separated by 16px, then the action after 40px. Main content aligns to the 64px margin and is centered vertically within the screen. The identity, navigation, whole headline, support, action and oversized object are all visible before the first 900px ends; the next editorial statement starts below it. A slim 52px promotional strip is a campaign-specific addition, not part of the core composition.

**Transfer:** Create one enlarged human-product interaction on a continuous warm ground, with clean space on the left. If no suitable photograph exists, use a beautifully lit isolated object with a real shadow, not a row of cards. Benefit explainers can open with full-height lifestyle photography, pale photo-display text at upper-left and support low on the left; research pages use research-display text and a dark studio object. Immersive hardware pages use product-display centered between oversized material details, a small product identity above it and a pale purchase action near the foot.

**Avoid:** Do not turn the default into a centered SaaS hero with a dashboard below, an evenly balanced two-box split, or a background image so busy that the headline needs an opaque text panel.

**Text style:** `display` — Editorial New 300 · 80px/1.1 · tracking -0.05em

### Centered editorial statement

**Observed:** A large heading-lg sits alone over the Cream canvas with 128px breathing room at the top, 24px before centered lead copy, then 40px before Secondary button actions. The title can exceed the support measure; actions are 16px apart. A large media composition or rail follows after another spacious interval.

**Transfer:** Use one declarative promise or verified result; give it a single supporting thought rather than a paragraph wall.

**Text style:** `heading-lg` — Editorial New 400 · 68px/1.1 · tracking -0.03em

### Benefit photo rail

**Observed:** Lifestyle cards occupy an overflowing Photo rail within the cream page. Category labels and expansion controls sit at the top; outcome headlines sit low. A Light rule progress track spans the main content width below the cards, with round arrows aligned to the right. A dark closing variant uses shorter photographic cards and a compact uppercase discovery label.

**Transfer:** Translate a product's benefits into human situations and retain the clipped next-card cue. This discovery device can introduce benefits or reopen exploration near the ending.

**Text style:** `photo-heading` — AkkuratLL 300 · 40px/1

### Headline proof and demonstration

**Observed:** A headline-sized quantified statement uses heading-lg over cream, with a centered lead and one Secondary button. An Interface bouquet occupies almost the full content width beneath it. The percentage is part of the sentence rather than a bright standalone badge.

**Transfer:** Pair a defensible result with visible product evidence. Where no numeric result is supportable, use a concrete verifiable outcome in the same editorial treatment.

**Text style:** `heading-lg` — Editorial New 400 · 68px/1.1 · tracking -0.03em

### Printed testimonial group

**Observed:** Three Testimonial cards sit side by side with 30px gaps and generous outer space. Each has the same sandstone surface, a small topic tag, a light serif quotation and a portrait attribution at the bottom.

**Transfer:** Group a few diverse first-person outcomes; keep a common card height even when the quotations differ.

**Text style:** `quote` — Editorial New 100 · 24px/1.25

### Offset feature and image

**Observed:** A left column around 477px wide contains an eyebrow, 56px heading, 20px body copy and a Secondary button; a much wider image extends from the middle of the page to the right edge. The text is vertically centered. The whole section uses 80px vertical padding, with the media rounded at its exposed left corners.

**Transfer:** Use for one new capability or a trust objection, alternating between interface media and human photography without changing the typographic hierarchy.

**Text style:** `heading` — Editorial New 400 · 56px/1.1

### Editorial evidence chapter

**Observed:** Dark editorial band encloses a small uppercase label and an asymmetric two-column composition: one roughly 775px photographic feature and a right-hand stack of roughly 477px Article cards with 24px vertical gaps. A dark-to-transparent image overlay supports a 40px feature headline, pale reading action and small featured tag. References continue on the same dark ground below.

**Transfer:** Give independent proof its own visual chapter. Use one lead story and a compact set of supporting sources instead of a uniform news grid.

**Text style:** `feature-article-heading` — AkkuratLL 400 · 40px/1.25 · tracking -0.05em

### Rounded shell and practical ending

**Observed:** The final content shell includes a fine reference separator and rounds down into the Footer atmosphere. The footer overlaps behind it by 48px. Its top row pairs a subdued identity with small trust or payment marks; below, a 384px newsletter invitation and Newsletter input sit beside Footer columns. A final rule introduces legal links, copyright and an outlined language selector. The footer content is about 660px tall with 64px vertical padding; it is not a second giant sales headline.

**Transfer:** Retain the change from page canvas to atmospheric charcoal and the newsletter-led utility grid. A product-led page can close its sales narrative with a Finish tile rail, an explainer with a short discovery rail, and a research page with a split contact invitation before the common reference-and-footer ending.

**Text style:** `newsletter-heading` — Editorial New 300 · 40px/1.25 · tracking -0.025em

### Metric strip

**Only for:** credibility summaries

**Observed:** Credibility columns form a three-part centered strip with fine vertical separators and 56px serif numbers. Hardware chapters use product-number with small icon discs above. Dark technical explanations instead use four smaller metric groups or vertically stacked Research metric glass panels over macro imagery.

**Transfer:** Use the arrangement suited to the amount of supporting detail; keep the metric, label and comparison basis adjacent.

**Text style:** `credibility-number` — Editorial New 300 · 56px/1

### Technical product chapter

**Only for:** immersive hardware product pages

**Observed:** A centered 98px product-heading within a 1024px measure introduces a pair of large rounded images: an expressive human portrait and a close material detail. Wide inset films use 24px corners. Later, category pills expose image-and-interface rails; a 40px-corner Specification panel separates dense facts from the story.

**Transfer:** Alternate sensory material evidence with compact explanations. Reserve this immersive treatment for products with meaningful construction or material differences.

**Text style:** `product-heading` — Editorial New 400 · 98px/1.1

### Research library and expert chapter

**Only for:** research and expert pages

**Observed:** Light sans research-heading introduces compact three-column sandstone publication cards, with source and date beneath each title and a circular reading action. Later a Research charcoal band pairs a light sans expert-heading with an indented italic expert-emphasis line, a short right-side explanation and an Expert portrait rail below.

**Transfer:** Separate publication proof from personal authority. Use an italic second line only for the expert introduction, not throughout the research page.

**Text style:** `research-heading` — AkkuratLL 300 · 68px/1.25 · tracking -2px

## Page flow

**Storyline:** A tangible promise → human outcomes → visible product explanation → quantified or independent proof → focused capability or trust chapter → renewed exploration or product choice → references and a practical atmospheric footer.

### Broad product and brand introduction

1. **Promise** — Warm studio gesture with short serif promise and blue conversion pill.
2. **Outcome discovery** — Centered statement and tall overflowing benefit-photo rail.
3. **Product demonstration** — Headline-sized result above a stepped interface grouping.
4. **Human proof** — Three sandstone quotation cards.
5. **Capability chapter** — Offset text and wide device scene.
6. **Independent proof** — Dark editorial feature beside stacked pale articles.
7. **Practical ending** — References remain on dark ground, then the rounded shell gives way to the atmospheric newsletter footer.

**Transfer:** Use this as the default balance of editorial storytelling, people and tangible product evidence.

### Explain differentiation and remove trust objections

1. **Promise** — Full-height candid photograph, pale serif headline and low support text.
2. **Outcome proof** — A large centered result statement followed by a heading-and-support split above three photographs.
3. **Authority** — A serif credibility headline and a divided numeric strip.
4. **Mechanism** — Dark construction chapter with exploded product film, split explanation and four qualified metrics.
5. **Personal relevance** — A wide lifestyle scene with a floating interface and segmented time controls.
6. **Trust** — Privacy split section, then a rounded dark panel of monochrome organization marks.
7. **Renewed exploration** — Short photographic discovery rail on dark ground.
8. **Practical ending** — Numbered qualifications, rounded dark shell and common newsletter footer.

**Transfer:** Expand the explanation and trust chapters when the product requires more reader confidence, rather than simply repeating the default hero.

### Immersive hardware launch and product selection

1. **Promise** — Enormous metallic product edges frame a centered serif headline on gray.
2. **Introduction** — A short uppercase introduction and large sans explanation continue the same material scene.
3. **Product demonstration** — Isolated object comparison, a human-scale still and a wide rounded film.
4. **Performance proof** — Monumental serif chapter title, portrait/material pair and three large qualified figures.
5. **Material benefit** — A macro battery detail and lifestyle film make durability and comfort tangible.
6. **Capability chapters** — Category pills switch an overflowing rail of lifestyle and interface cards.
7. **Factual reference** — Large cool-gray inset specification panel.
8. **Product choice** — An airy finish gallery of isolated consistently lit products.
9. **Practical ending** — Qualifications on porcelain, rounded shell, common charcoal footer.

**Transfer:** Use when material, scale and configuration deserve a cinematic story; do not replace the default cream marketing treatment on every page.

### Establish scientific authority and invite professional collaboration

1. **Promise** — Dark studio rendering beside a large light sans headline and pale reading action.
2. **Authority** — Centered research heading, concise explanation and four serif credentials.
3. **Mechanism and validation** — Macro product imagery with technical copy and a right-hand stack of glass metric cards.
4. **Independent proof** — Split heading-and-paragraph row above compact publication cards.
5. **Capability explanation** — Tall lifestyle panels with translucent metric lists.
6. **Research depth** — Centered library invitation, a six-card publication grid and organization case summaries.
7. **Editorial proof and experts** — Dark lead-story layout followed by a mixed-family heading and color portrait rail.
8. **Collaboration invitation** — Cream split contact section with a professional photograph and two actions.
9. **Practical ending** — References, rounded light shell and shared atmospheric footer.

**Transfer:** Use the sans-led variant for evidence-rich professional audiences while retaining the same cream, serif-number and tactile-media system.

## Writing

Assured, empathetic and concrete. Aspirational headlines invite agency; support copy explains how a sophisticated product becomes useful without sounding like a spec sheet.

**Do not copy:** Do not reuse the Oura name, trademarks, product names, app artwork, partner logos, member quotations, health claims, study findings, percentages, credentials or superlatives. Source examples illustrate phrasing only; every new claim and endorsement must belong to the new product and be substantiated.

- **Addressing the reader:** Speak directly to you and your in promises and benefits. Use we or our for responsibility, research and commitments; use the product name when explaining a mechanism.
- **Rhythm:** Headlines are short phrases or balanced paired sentences. Support lines usually deliver one complete thought; explanatory sections use one or two short paragraphs. Action labels are brief verbs, with little punctuation and no hype-heavy exclamations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An active, personal benefit framed as a compact invitation. | 4–8 words | “Wear your best life”<br>“Navigate your health with clarity” |
| Chapter statement | Two balanced clauses that connect understanding with agency. | 5–10 words | “Understand your body. Own your health.”<br>“Built to last. Designed for comfort.” |
| Supporting line | Name a useful outcome, then the product mechanism that makes it possible. | 15–30 words | “Get a clearer picture of your health with the world's smallest smart ring.” |
| Trust statement | State a commitment plainly, with a human reason rather than abstract security jargon. | 6–12 words for the heading | “Your privacy always comes first” |
| Primary action | A direct verb with a short object or simple next step. | 1–4 words | “Shop Now”<br>“Explore Membership”<br>“View [Brand] in Research” |
| Evidence headline | Precise factual phrasing with a named mechanism or validation basis. | 4–12 words before supporting detail | “Independently validated sensors”<br>“Precision at every layer” |

**Words and phrasing to use:** understand; clarity; your; designed for; everyday; personalized; insights; validated; research; confidence

**Avoid:** game-changing; disruptive; crush it; hack your life; magic; guaranteed transformation; unlimited potential

**Rules:**

- Lead with lived benefit and explain the mechanism immediately afterward.
- Use paired clauses for rhythm, not strings of adjectives.
- Attach a readable comparison basis or qualification to a numerical claim.
- Use technical language where it increases trust, but translate the result into a human consequence.
- Keep exploratory and transactional labels distinct: learning verbs for education, purchase verbs for conversion.

## Do's and Don'ts

### Do

- Keep the default opening headline at 80px, weight 300 and -0.05em tracking with a compact two-line wrap.
- Use 64px desktop content margins and let selected large media extend beyond them deliberately.
- Separate centered heading and lead by 24px, then give the actions 40px of breathing room.
- Keep blue conversion pills 48px tall and regular exploratory pills the same height.
- Combine 12px photo-card corners with 8px editorial-card corners rather than forcing one radius everywhere.
- Use 24px rail gaps and show a clipped next item to signal discovery.
- Give serif numbers and their comparison captions an obvious shared grouping.
- Keep the newsletter invitation at 40px serif and the input at 320px by 40px within the dark ending.

### Don't

- Do not use bold geometric sans display as the default; the large marketing voice is slender serif.
- Do not paint whole sections conversion blue or apply it to every text link.
- Do not turn all photography into perfectly centered cutouts; tight human framing and asymmetry carry the warmth.
- Do not place white elevated cards with strong drop shadows on every cream section; tonal sandstone cards stay flat.
- Do not fill the footer with a giant logo or a second oversized purchase banner; its emphasis is the newsletter and useful links.
- Do not make all rounded elements equally pill-shaped: cards use 8px or 12px, while actions are fully rounded.
- Do not spread italic serif emphasis across ordinary benefit headlines; it belongs to a specific expert-introduction treatment.
- Do not reproduce dark app-screen colors as the marketing palette; keep those colors confined to the product views.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions commonly use 0.15s cubic-bezier(.4,0,.2,1) across color, background, border and transform-related properties. Navigation backing declares a 0.4s opacity transition with the same easing.
- Horizontal rails have previous/next controls and progress rules. The immersive hardware story changes between enlarged material details, comparison views and films during scroll.

**Transfer:**

- Keep control feedback subtle and immediate; the visual drama belongs to the product imagery and scene changes, not bouncing buttons.
- When using an immersive material story, preserve a readable settled state for every headline and action.

**Unknown:**

- Exact scroll-scene timing, pinning thresholds and video choreography are not established.

### Responsive

**Observed:**

- The desktop composition is based on 1440px width. Declared CSS includes major 768px, 1024px and 1280px breakpoints.
- Responsive classes indicate centered opening content below wide desktop, stacked testimonial cards before the medium breakpoint and footer link grids changing from two to three to four columns.

**Transfer:**

- On narrow screens, preserve the opening's human-product relationship by reframing the image rather than shrinking the entire desktop stage.
- Keep photographic discovery as a horizontally scrolling rail with a visible continuation cue.
- Stack split-section text and media, retain the cream breathing space and keep controls separate from the image focal point.

**Unknown:**

- Exact mobile headline sizes, image positions and navigation-menu construction are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
