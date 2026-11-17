# PamPam — sunlit tools for everyone

## Overview

An approachable, lightly nostalgic product style that pairs a slender editorial serif with rounded, friendly sans-serif text. White space, cream surfaces and periwinkle actions keep the interface light, while hazy sunlit imagery and colorful product windows add a sense of discovery. It suits creative tools and accessible software, with roomy storytelling around compact, useful demonstrations.

### Essentials

- Editorial promises, not oversized software slogans: regular-weight nineties serif at 80px/1.08 for the opening, 48px/1.08 for section leads and 28px/1.08 for small headings, all with normal tracking.
- A dreamy landscape holds a usable tool: a full-width, roughly 888px-high opening fades from soft green foliage and sky into white, with a centered 600px text stack, a 406px-wide prompt and three 127×92px mode tiles.
- Buttons feel like small physical controls: 64px-high rounded rectangles with 12px corners, 20px 32px padding, a 1px edge and shallow shadows; the primary is #4b72f3, never a pill.
- Color lives in the scenery rather than the typography: white dominates the page, #faf2ec supports small tiles and the footer, and blue is concentrated in actions. Include a hazy atmospheric backdrop and a framed product demonstration; use softly blurred landscape shapes behind a simplified interface if finished imagery is unavailable.
- Product proof is a picture worth pausing over: a 1100×642px rounded scene presents a browser window against blue, lilac and peach cloud-like streaks; smaller 500×400px scenes alternate with narrow text columns.
- The closing invitation stays human-sized: a centered 48px serif line, muted 19px support and paired raised buttons lead into a full-width cream footer with 64px vertical padding and a five-column grid including the identity column.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Periwinkle blue | `#4b72f3` | `--color-action` | action | Primary action fills, in small concentrations rather than full-page bands. |
| Deep blue edge | `#2b3ea7` | `--color-action-edge` | border | Primary button outline. |
| Blue bevel | `#6387f4` | `--color-action-highlight` | accent | Two-pixel inset highlight at the top of primary buttons. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Dominant page canvas, prompt field and text on blue actions. |
| Porcelain | `#fefefe` | `--color-secondary-surface` | surface | Secondary button fill. |
| Warm cream | `#faf2ec` | `--color-cream` | background, surface | Footer band, category tiles and icon blocks. |
| Light gray rule | `#e6e6e6` | `--color-rule` | border | Visible result of 10% black over white for button, prompt and FAQ edges. |
| Pearl base | `#e5e5e5` | `--color-mode-base` | surface | 60% light gray over white forms the base beneath the white-to-translucent-white mode tile gradient. |
| Preview outline | `#d9d9d9` | `--color-media-edge` | border | Visible result of 15% black over white around example preview images. |
| Lavender gray | `#9894a8` | `--color-muted` | text, link | Support copy, navigation, footer links and restrained icon strokes. |
| Prompt gray | `#8f8f8f` | `--color-prompt-text` | text | Example text in the opening prompt. |
| Button gray | `#8a8a8a` | `--color-secondary-text` | text | Secondary action labels. |
| Warm near-black | `#1b1917` | `--color-ink` | text | Serif headings, footer group labels and emphasized text. |
| Black | `#000000` | `--color-black` | text, action | Compact prompt action, small mode labels and pricing numerals. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Cool plan white | `#fbfcfd` | `--color-plan` | surface | Pricing card fill. |
| pricing pages | Lavender plan edge | `#dde1f1` | `--color-plan-edge` | border | Two-pixel recommended-plan outline. |
| pricing pages | Savings green | `#00a917` | `--color-saving` | text | Savings label text. |
| pricing pages | Savings mint | `#e5ffe8` | `--color-saving-surface` | surface | Small savings badge fill. |
| pricing pages | Billing green | `#006e0b` | `--color-switch` | action | Selected annual-billing switch. |
| company storytelling pages | Story charcoal | `#2c2936` | `--color-story-ink` | text | Longer first-person editorial paragraphs. |

## Typography

- **nineties** — Headlines, section leads, feature names and questions. Tall, narrow editorial serif with expressive, gently nostalgic forms and fine contrasts. If unavailable, use **Instrument Serif**. Use regular 400; preserve the narrow silhouette and balanced line breaks. Font stack: "nineties", "Instrument Serif", Georgia, serif.
- **inter** — Support copy, actions, navigation, captions and plan details. Friendly, highly readable sans with softened details; medium 550 is the everyday marketing weight. OpenType features: "cv02", "cv03", "cv04", "cv06", "cv11". Font stack: "inter", Arial, sans-serif.
- **-apple-system** — Small audience tags. Compact system sans at semibold weight. Font stack: "-apple-system", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | nineties | 400 | 80px | 1.08 | normal | Centered opening promise and utility-page titles. |
| heading | nineties | 400 | 48px | 1.08 | normal | Section leads and closing invitations; also the left-aligned editorial opening. |
| small-heading | nineties | 400 | 28px | 1.08 | normal | Feature names, FAQ questions and personnel section labels. |
| proof-caption | nineties | 400 | 24px | 1.08 | normal | Centered, muted serif caption introducing external recognition. |
| lead | inter | 550 | 19px | 28px | normal | Opening support, centered section introductions, large action labels and profile names. |
| body | inter | 550 | 18px | 28px | normal | Split-section paragraphs and feature descriptions. |
| label | inter | 550 | 16px | 24px | normal | Navigation, footer links and profile metadata. |
| caption | inter | 400 | 16px | 24px | normal | Descriptions below example previews. |
| compact-label | inter | 550 | 14px | 20px | normal | Opening mode labels; plan details use the same compact recipe. |
| eyebrow | -apple-system | 600 | 13px | 1 | normal | Tiny audience labels in cream lozenges above split-section headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | inter | 700 | 32px | 24px | normal | Price numerals with smaller inline billing unit. |
| company storytelling pages | story-body | inter | 400 | 19px | 28px | normal | Longer editorial paragraphs in dark charcoal. |
| pricing pages | savings | inter | 550 | 14px | 28px | normal | Green savings text within compact badges. |

**Notes:**

- Keep serif headings regular and naturally tracked at every size; hierarchy comes from scale and placement, not bold weight or capitals.
- Sans support is medium 550 by default, with regular 400 reserved for preview captions and longer editorial prose.
- Balanced headline wrapping and narrow text columns keep the page conversational. A split section's 340px text column intentionally produces two- or three-line serif headings.

## Layout

**Density:** Airy around sections and compact inside the working tool; generous pauses frame small, legible interface controls.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Preview-to-caption separation and compact plan-list spacing. |
| 12px | Footer link spacing, mode-tile gaps and control internals. |
| 20px | Heading-to-support separation and split-section text-stack gaps. |
| 24px | Card padding, FAQ vertical padding and audience-tile gaps. |
| 32px | Container side padding and horizontal button padding. |
| 40px | Template and feature-grid gutters. |
| 56px | Section introduction to the main grid or action group. |
| 64px | Standard section top and bottom padding; footer separation. |
| 72px | Image-to-copy gap in alternating feature chapters. |

### Containers and grids

- **main-container**: max width 976px · side padding 32px. Centered outer wrapper; 912px of usable desktop content.
- **text-container**: max width 600px. Centered opening and closing copy; left-aligned editorial prose uses the same width.
- **split-chapter**: 2 columns · gap 72px. Within the main container, pair a 500×400px image with a 340px text column and vertically center the two.
- **preview-grid**: 3 columns · gap 40px. Three 277px-wide example previews, each with text underneath; additional items continue onto a second row.
- **feature-grid**: 2 columns · gap 40px. Two 436px-wide columns of icon-and-copy rows.
- **wide-media**: max width 1100px. A centered product scene wider than the normal text wrapper.
- **audience-grid**: 4 columns · gap 24px · side padding 64px. Four 310×225px image links stretch wider than the main content.
- **footer-grid**: 5 columns · gap 24px. One identity column and four link groups within the 912px content width.
- **pricing-grid** (only for pricing pages): max width 1080px · 4 columns · gap 32px. Equal 246px-wide plan cards extend beyond the normal wrapper.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons-and-prompt | 12px |
| cards-and-media-scenes | 16px |
| example-previews | 10px |
| mode-tiles-and-prompt-action | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| secondary-button | `0px 1px 3px 0px rgba(0, 0, 0, 0.1)` | Subtle secondary action lift. |
| primary-button | `0px 1px 2px 0px rgba(0, 0, 0, 0.3), inset 0px 2px 0px 0px #6387f4` | Small physical bevel and bottom shadow on blue actions. |
| mode-tile | `0px 0px 0px 1px rgba(0, 0, 0, 0.08), 0px 1px 4px 0px rgba(0, 0, 0, 0.1)` | Pearly tool choices floating over the opening scenery. |

### Surfaces

#### White canvas · level 0

**Use:** The dominant page field.

**CSS:** `background: #ffffff`

**Observed:** Mostly unpainted sections keep imagery and thin serif lettering distinct.

**Transfer:** Preserve the white field between visual chapters.

#### Cream support · level 1

**Use:** Footer band, category tiles and icon backings.

**CSS:** `background: #faf2ec; border-radius: 16px`

**Observed:** Warm and flat, without a heavy card shadow. The footer uses this color edge-to-edge with square outer corners.

**Transfer:** Use cream to organize supporting information, not to tint every section.

#### Pearl tool tile · level 2

**Use:** Small mode choices in the atmospheric opening.

**CSS:** `background-color: rgba(211, 211, 211, 0.6); background-image: linear-gradient(#ffffff, rgba(255, 255, 255, 0.6)); border-radius: 8px; box-shadow: 0px 0px 0px 1px rgba(0, 0, 0, 0.08), 0px 1px 4px 0px rgba(0, 0, 0, 0.1)`

**Observed:** Soft white tops and translucent lower edges sit above the hazy landscape without becoming dark glass.

**Transfer:** Use this material only for compact choices over imagery.

#### Plan panel · level 1

**Only for:** pricing pages

**Use:** Plan comparison cards.

**CSS:** `background: #fbfcfd; border-radius: 16px; padding: 24px`

**Observed:** Near-white cards remain visually quiet; one recommended tier gains a 2px lavender outline.

**Transfer:** Highlight a plan through its edge, not a saturated full-card fill.

## Components

### Navigation

**Use:** Persistent identity and site-level destinations.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 100px; display: flex; align-items: center; justify-content: space-between; gap: 20px; padding: 28px 40px 28px 28px; z-index: 2`

**Text style:** `label` — inter 550 · 16px/24px

**Observed:** A compact black-and-white identity sits left; muted text destinations and a small white sign-in control sit right. The opening scenery remains visible behind the header; over later content the bar reads white with a faint lower rule.

**Transfer:** Use a compact, high-contrast identity rather than enlarging the brand mark into the hero.

### Primary button

**Use:** Main conversion actions and chapter-level next steps.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 64px; padding: 20px 32px; gap: 10px; background: #4b72f3; color: #ffffff; border: 1px solid #2b3ea7; border-radius: 12px; box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.3), inset 0px 2px 0px 0px #6387f4; text-shadow: 0px 1px 0px rgba(0, 0, 0, 0.35)`

**Text style:** `lead` — inter 550 · 19px/28px

**Observed:** Centered text; full text-column width in split chapters and content width in closing pairs.

### Secondary button

**Use:** Lower-pressure exploration, examples and documentation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 64px; padding: 20px 32px; gap: 10px; background: #fefefe; color: #8a8a8a; border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 12px; box-shadow: 0px 1px 3px 0px rgba(0, 0, 0, 0.1)`

**Text style:** `lead` — inter 550 · 19px/28px

**Observed:** Sits alongside the blue action in closing groups or fills a narrow copy column on its own.

### Prompt composer

**Use:** A usable product invitation at the center of the opening.

**CSS:** `width: 406px; height: 66px; background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 12px; display: flex; flex-direction: column; margin-bottom: 16px; box-shadow: 0px 1px 0px -1px rgba(0, 0, 0, 0.05), 0px 1px 1px -1px rgba(0, 0, 0, 0.05), 0px 1px 2px -1px rgba(0, 0, 0, 0.05), 0px 2px 4px -2px rgba(0, 0, 0, 0.05), 0px 3px 6px -3px rgba(0, 0, 0, 0.05)`

**Text style:** `label` — inter 550 · 16px/24px

**Observed:** Example prompt is truncated on the left; an embedded black 40px-high action with 8px corners and a white sparkle sits right. The inner row has 12px top, right and bottom margins and a 20px left margin.

**Transfer:** Use one plausible task input with a short action. When text generation is not relevant, make this a compact search or configuration starter.

### Mode tile

**Use:** Three concrete outputs below the opening composer.

**CSS:** `width: 127px; height: 92px; padding: 12px; display: flex; flex-direction: column; align-items: flex-start; gap: 12px; background-color: rgba(211, 211, 211, 0.6); background-image: linear-gradient(#ffffff, rgba(255, 255, 255, 0.6)); border-radius: 8px; box-shadow: 0px 0px 0px 1px rgba(0, 0, 0, 0.08), 0px 1px 4px 0px rgba(0, 0, 0, 0.1)`

**Text style:** `compact-label` — inter 550 · 14px/20px

**Observed:** A colored circular icon badge sits above a short black label; three equal tiles share a row with 12px gutters.

**Transfer:** Present three meaningful outputs or ways to begin rather than three abstract benefits.

### Feature item

**Use:** Scannable capability lists.

**CSS:** `display: flex; align-items: center; gap: 20px`

**Text style:** `small-heading` — nineties 400 · 28px/1.08

**Observed:** An 80×80px Cream support block with 16px corners and a centered 40px outline icon anchors the left. Right-hand copy stacks a serif name and muted body description with an 8px gap.

**Transfer:** Keep each capability to a short name and one or two lines of explanation.

### Example preview

**Use:** Visual starting points and reusable examples.

**CSS:** `border: 1px solid rgba(0, 0, 0, 0.15); border-radius: 10px; width: 100%; height: auto`

**Text style:** `caption` — inter 400 · 16px/24px

**Observed:** Portrait product preview above unboxed text. A darker 18px title precedes a muted regular 16px description; preview-to-text gap is 8px. Cards do not have an enclosing painted body.

**Transfer:** Show varied real outcomes rather than repeating the same generic dashboard.

### Question row

**Use:** Objection handling before a closing invitation.

**CSS:** `border-top: 1px solid rgba(0, 0, 0, 0.1); padding: 24px 0px`

**Text style:** `small-heading` — nineties 400 · 28px/1.08

**Observed:** A 912px-wide list with approximately 79px-tall collapsed rows. Serif question left and a plain black 24px plus right; no enclosing card or filled background.

### Footer link

**Use:** Dense but readable secondary navigation.

**CSS:** `color: #9894a8; text-decoration: none`

**Text style:** `label` — inter 550 · 16px/24px

**Observed:** Links stack beneath darker group labels with 12px gaps; long labels wrap naturally within equal-width columns.

**States:** Declared: hover color #1b1917; focus-visible not specified.

### Audience tag

**Use:** Small contextual label above a split chapter.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #faf2ec; color: rgba(0, 0, 0, 0.5); padding: 4px 12px; border-radius: 12px`

**Text style:** `eyebrow` — -apple-system 600 · 13px/1

**Observed:** Sentence case and intrinsic width; the small lozenge is much quieter than a badge announcing a promotion.

### Plan card

**Only for:** pricing pages

**Use:** Equal-height subscription comparisons.

**CSS:** `background: #fbfcfd; border-radius: 16px; padding: 24px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `compact-label` — inter 550 · 14px/20px

**Observed:** Plan name, bold price with inline billing unit, optional mint savings badge, checkmarked feature list, action and a small learn-more link. Four cards share a desktop row; the recommended middle tier has a 2px #dde1f1 outline. Entry tiers use secondary actions while higher tiers use blue actions. Savings badges use 12px corners and 0px 8px padding; the annual switch is green, 56×36px, with a white 20px knob.

**Transfer:** Keep the price hierarchy sans-serif and reserve green for actual savings and billing selection.

### Profile card

**Only for:** company storytelling pages

**Use:** People and collaborators.

**CSS:** `display: flex; flex-direction: column; background: #faf2ec; border-radius: 16px; overflow: hidden`

**Text style:** `lead` — inter 550 · 19px/28px

**Observed:** A 436×200px candid portrait spans the top; a 24px-padded lower area contains name, 16px role, muted short biography and small social links. Two columns with 40px gutters.

**Transfer:** Retain the informal portrait variety and concise biographies rather than uniform corporate headshots.

## Imagery and graphics

### Sunlit haze

**Use:** Signature atmospheric layer in the primary opening.

**Observed:** Soft-focus green leaves, pale blue sky and creamy sunlight fill the opening. Leaf shadows are most legible in the upper left; the middle is washed out behind the text, and the bottom dissolves almost completely into white. Fine grain prevents the image from looking like a sterile software gradient.

**Transfer:** Create a new sunlit natural scene or an abstract version with the same green, blue and cream light. Keep the type and tool readable in a pale central clearing.

**Build:** Layer broad pale green and sky-blue radial gradients over white; place a creamy oval glow toward the upper right. Add blurred, low-opacity leaf-like SVG ellipses and diagonal branch shapes in the upper-left third, then a very fine monochrome noise layer. A white linear-gradient overlay grows opaque through the lower quarter. Match the soft light rather than sharply delineating gradient stops.

### Cloud-backed product windows

**Use:** Signature proof scene and smaller product chapters.

**Observed:** A large browser-style product window floats over saturated blue with lilac, peach and white cloud streaks. The wide scene is 1100×642px with 16px outer corners; the interface occupies most of the image, with enough background visible to create a dreamy frame. Smaller 500×400px scenes use either cloudy blue skies or a dark navy-to-blue field and overlapping app windows.

**Transfer:** Frame a real product output in a simple browser window. If no polished output exists, use a legible schematic interface with a sidebar and a meaningful main result; retain the atmospheric border and restrained window chrome.

**Build:** Make a rounded overflow-hidden backing. Use a blue field with elongated lilac and peach radial gradients rotated diagonally and softened with blur. Center a white rounded browser frame at roughly three quarters of the backing width, add tiny window dots, and insert the product view. For an import story, offset a second window behind the main one on a navy-to-muted-blue vertical gradient.

### Dreamlike audience pictures

**Use:** Wide row of links connecting the product to different contexts.

**Observed:** Four rounded 310×225px pictures show a breaking wave, a pastel mountain, people in a bright meadow and blurred city lights. Saturated color, soft focus, painterly grain and motion blur make these feel like memories rather than conventional stock images. White labels and chevrons sit over a black-to-transparent lower gradient.

**Transfer:** Choose new contexts relevant to the product but maintain the lush light, blur and simple compositions. Keep label contrast through the lower scrim.

**Build:** Use a landscape image in a 16px-rounded overflow-hidden frame. Soften detail slightly, boost luminous midtones and overlay fine grain. Add a bottom strip using linear-gradient(0deg, rgba(0,0,0,0.4), rgba(0,0,0,0)); position a 16px label left and a 20px white chevron right.

### Outcome previews

**Use:** Three-column example galleries.

**Observed:** Tall previews reveal actual maps with sidebars, imagery, varied color themes and small decorative markers. Their fine outlines and rounded corners make them read as useful artifacts rather than detached illustrations.

**Transfer:** Show finished outputs in the product's own formats; vary the data, visual theme and use case while keeping consistent image proportions.

### Documentary photography

**Only for:** audience-specific and company storytelling pages

**Use:** Human context, onboarding and team stories.

**Observed:** Audience stories use direct, naturally colored photos such as market produce and children at a table, in 500×400px rounded crops. The editorial opening uses a large 912×730px photo of people in a lived-in workspace; personnel cards use wide candid portraits with varied surroundings.

**Transfer:** Use believable working environments and everyday activity. Keep natural color and informal framing; do not apply the dreamy illustration treatment to every portrait.

### Icons

**Observed:** Marketing feature icons are dark, thin outline drawings centered at 40px inside 80px cream squares. Pricing checkmarks are 24px, muted lavender gray, with 2px rounded strokes. Tiny opening badges use bright circles with white symbols; audience links use white chevrons.

**Transfer:** Choose friendly, rounded outline symbols with few details. Preserve the cream icon backing as a repeated device rather than turning each feature into a full painted card.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric tool opening

**Observed:** A roughly 896px-tall, edge-to-edge opening layers Sunlit haze behind a centered tool stack. Navigation sits above it. The two-line 80px serif promise spans a 600px column in the upper-middle of the viewport; a muted 19px support line follows after 20px. The 406×66px Prompt composer contains the main black action, with three Mode tiles below. All of the headline, support, input and tiles are visible within the first 900px; the large product demonstration belongs below the fold. The scenery is the main visual object, not a giant dashboard behind the text.

**Transfer:** Use an equally compact real starting interaction for the new product and keep the surrounding scene luminous. Feature and audience pages instead open on white with a centered 80px title and support; an audience page adds a tabbed large demo, while a company story opens left-aligned at 48px with prose and a large candid photograph.

**Avoid:** Do not replace the centered tool stack with a conventional left-copy/right-dashboard hero, or cover the central clearing with an opaque panel.

**Text style:** `display` — nineties 400 · 80px/1.08

### Heading and demonstration

**Observed:** A centered 48px heading introduces Cloud-backed product windows, separated by 64px. The media extends to 1100px, beyond the usual content width. A muted 24px serif proof caption follows below the scene.

**Transfer:** Let one compelling output carry the proof. Use the smaller proof caption for genuinely external recognition, not a second competing headline.

**Text style:** `heading` — nineties 400 · 48px/1.08

### Example gallery

**Observed:** A heading and muted introduction sit above a three-column Example preview grid, with 56px between intro and grid and 40px gutters. The broad product opening uses a left-aligned lead here; audience-specific variants center their introduction.

**Transfer:** Offer visual starting points that make adopting the product feel easy. A second row can extend the library without changing the card construction.

**Text style:** `heading` — nineties 400 · 48px/1.08

### Alternating capability chapter

**Observed:** A 500×400px image sits beside a 340px copy stack across a 72px gap. Copy uses an Audience tag when needed, 48px heading, 18px paragraph and a full-column Primary button or Secondary button. Sections use 64px top and bottom padding; image and copy sides alternate.

**Transfer:** Give each chapter one outcome. Alternate product scenes with genuine context photography when explaining a service or audience need.

**Text style:** `heading` — nineties 400 · 48px/1.08

### Icon capability directory

**Observed:** A centered heading pair sits 56px above a two-column grid of Feature items with 40px gutters. Serif 28px names and muted 18px descriptions contrast with the cream icon blocks. A pricing variant uses a left-aligned section lead.

**Transfer:** Group secondary capabilities in this low-chrome directory rather than expanding each into a large card.

**Text style:** `small-heading` — nineties 400 · 28px/1.08

### Questions

**Observed:** A centered 48px section heading has a generous pause before a 912px-wide Question row list. Five to eight questions use only horizontal top rules and plus signs.

**Transfer:** Answer the practical doubts specific to the product. Keep this region visually lighter than the example gallery.

**Text style:** `small-heading` — nineties 400 · 28px/1.08

### Friendly closing and cream directory

**Observed:** A centered 600px copy block combines a 48px serif invitation, 19px muted support after 20px and a button group after 56px. Most endings pair blue and white; the company variant pairs two blue community actions. After 64px of separation, the Cream support footer spans the full width with 64px vertical padding. The five-column footer includes a compact identity and four muted link groups; no giant closing wordmark or legal-heavy dark strip.

**Transfer:** Close with one approachable next step and one lower-pressure path, then a genuinely useful directory. Let the invitation echo the opening promise without forcing identical wording.

**Text style:** `heading` — nineties 400 · 48px/1.08

### Plan comparison opening

**Only for:** pricing pages

**Observed:** A centered 80px title and 19px support lead into a small annual-billing switch and a four-card, 1080px-wide Plan card grid. Cards use 24px padding, 20px internal gaps and compact checkmarked lists; price numerals are bold sans-serif, not display serif.

**Transfer:** Show meaningful differences and one restrained recommended edge; follow with explanation, capabilities, questions and the shared closing treatment.

**Text style:** `display` — nineties 400 · 80px/1.08

### Editorial people story

**Only for:** company storytelling pages

**Observed:** A left-aligned 600px-wide 48px heading and dark 19px regular prose precede a 912px-wide candid photograph after 56px. Subsequent prose remains left-aligned; people appear in a two-column Profile card grid under modest 28px labels.

**Transfer:** Use a human motivation and a believable workplace before introducing individuals. Keep corporate storytelling visually distinct from the centered product promise.

**Text style:** `heading` — nineties 400 · 48px/1.08

## Page flow

**Storyline:** Promise → useful demonstration → ways to begin → focused benefits → capability or audience breadth → practical reassurance → friendly invitation and cream directory.

### Broad product landing page

1. **Promise and activation** — Atmospheric tool opening with a compact input and three tangible outputs.
2. **Product proof** — Wide cloud-backed demonstration and a modest external-recognition caption.
3. **Ways to begin** — Small category tiles followed by a portrait example gallery.
4. **Capability and audience breadth** — Alternating illustrated chapters followed by dreamy audience links.
5. **Objection handling** — Ruled serif question list.
6. **Closing call** — Centered invitation, paired blue and white actions and cream footer.

**Transfer:** Move from an immediate usable promise to visual outcomes and specific reassurance; adapt the number and order of proof chapters to the product.

### Audience-specific solution page

1. **Audience promise** — White centered title and support above three tabs and a large, softly shadowed product view.
2. **Context and incentive** — Alternating photo-and-copy chapters explaining useful outcomes and an audience-specific offer.
3. **Capabilities** — Compact two-column icon directory.
4. **Starting points** — Three relevant outcome previews.
5. **Closing call** — Short product explanation with demo and self-serve actions, then shared cream footer.

**Transfer:** Localize examples and reassurance to the audience while retaining the common type hierarchy and low-chrome composition.

### Capability overview

1. **Orientation** — Centered white title and concise product definition.
2. **Key workflows** — Two alternating product scenes with secondary documentation actions.
3. **Capability breadth** — Extended two-column icon directory under a friendly counted heading.
4. **Closing call** — Centered invitation with start and guide actions, followed by the cream footer.

**Transfer:** Lead with the two most useful workflows before the scannable directory; do not make every capability a full-width chapter.

### Plans and purchase reassurance

1. **Pricing** — Centered title, billing control and four quiet plan panels.
2. **Proof and added value** — Small recognition caption, embedding demonstration and human onboarding story.
3. **Capability coverage** — Two-column icon directory.
4. **Objection handling** — Longer ruled question list about limits, billing and setup.
5. **Closing call** — Start and chat actions above the shared cream footer.

**Transfer:** Pair clear comparisons with practical reassurance and access to a human; keep the main visual system light rather than switching to a sales-heavy theme.

### Company and community story

1. **Motivation** — Left-aligned editorial heading and prose above a large workplace photograph.
2. **Trust** — A candid explanation of who makes the product and a support action.
3. **People** — Small serif labels introduce team and collaborator portrait cards.
4. **Closing call** — Collaboration invitation with two blue community actions, then the common footer.

**Transfer:** Use the editorial variant for human motivation and real people, not the interactive tool opening.

## Writing

Warm, direct and maker-friendly. Benefits are explained with everyday verbs and concrete outputs, with a casual confidence that lowers the perceived effort of getting started.

**Do not copy:** Do not reuse the brand name, logo, artwork, employee identities, customer material, proprietary product claims, exact discounts, prices or limits. Examples illustrate voice, not claims for a new product.

- **Addressing the reader:** Speak to the reader as you and your; use we for the people behind the product. Product-definition lines may name the product in the third person.
- **Rhythm:** Short sentence-case headlines, often three to seven words, followed by one or two plain support sentences. Imperative verbs, occasional questions and contractions keep longer explanations accessible.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Make a personal outcome feel achievable in a compact, memorable phrase. | 5–8 words | “Put your world on the map.” |
| Capability heading | Lead with a familiar task or result rather than a technical category. | 3–7 words | “Create interactive maps in minutes.”<br>“Connect people to resources” |
| Support line | Define what readers can make and remove a practical barrier. | 1–2 short sentences | “Create beautiful, interactive maps in minutes. No code needed.” |
| Primary action | Use a simple verb and a concrete, low-risk next step. | 3–5 words | “Try it for free”<br>“Book a demo” |
| Question | Use the reader's actual practical question. | 6–12 words | “Can I embed or share my custom map?” |
| Closing invitation | Return to personal possibility or direct human contact. | 3–7 words | “Ready to share your world?”<br>“Collaborate with us” |

**Words and phrasing to use:** make; your own; share; start with; in minutes; without coding; we'll handle the rest; together

**Avoid:** revolutionary; enterprise-grade synergy; unlock limitless potential; dominate; next-generation ecosystem

**Rules:**

- Name a tangible output before explaining the mechanism.
- Put the benefit in the heading and the practical details in the support copy.
- Use reassuring specifics instead of grandiose adjectives.
- Keep audience labels conversational: For teams, not TEAM SOLUTIONS.
- Use contractions and direct invitations in human-support copy.

## Do's and Don'ts

### Do

- Keep 80px and 48px serif headings at weight 400 with normal tracking.
- Use 600px text blocks for centered introductions and closing invitations.
- Preserve the 500px image, 340px copy and 72px gap relationship in desktop split chapters.
- Use 12px corners and a shallow bevel on 64px blue buttons.
- Reserve cream for support surfaces and the full-width footer.
- Include both luminous atmosphere and a legible framed product outcome.
- Use 40px gutters for three-column previews and two-column capability lists.
- Keep compact mode tiles at 8px corners, distinct from the 16px supporting cards.

### Don't

- Do not make all headings bold sans-serif; the slender serif is the primary voice.
- Do not tighten headline tracking into a compressed tech-brand treatment; tracking is normal.
- Do not paint every section cream or blue; white is the dominant field.
- Do not turn the raised rectangular actions into fully rounded pills.
- Do not wrap every capability row in a bordered dashboard card; only its icon gets a cream backing.
- Do not apply heavy drop shadows to example galleries or profile cards; their outlines or flat fills do the organizing.
- Do not enlarge price figures into serif display statements; use the scoped 32px bold sans recipe.
- Do not replace the cream directory ending with a black footer or a giant wordmark.

## Motion and responsive

### Motion

**Observed:**

- Some controls declare transform, background and border-color transitions of 0.15s.
- Footer links declare a hover color change from lavender gray to warm near-black; header text actions declare hover opacity 0.5.

**Transfer:**

- Keep hover emphasis subtle enough that the luminous scenery and editorial type remain the focus.

**Unknown:**

- Exact runtime behavior of atmospheric imagery and any demonstration animation is not specified.
- Focus, pressed and loading treatments for the main buttons are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 500px, 600px, 640px, 720px, 768px, 800px, 900px, 1024px and 1200px.
- The opening title has a mobile 44px class; split chapters declare a 36px mobile gap, and capability grids declare a 20px mobile gap.

**Transfer:**

- On narrow screens, retain the pale center of the atmospheric opening and keep the prompt interaction ahead of the large proof scene.
- Stack split chapters without stretching their text measure; preserve separate image framing.
- Reduce multi-column galleries and footer groups to fewer columns while retaining the distinct cream footer band.

**Unknown:**

- Exact breakpoint-to-layout mappings and complete mobile typography recipes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
