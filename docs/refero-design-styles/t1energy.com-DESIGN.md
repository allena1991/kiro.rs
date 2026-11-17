# T1 Energy — monumental industrial optimism

## Overview

An industrial, cinematic style that pairs human-scale work with monumental machinery and restrained technical language. Warm white and near-black grounds frame desaturated documentary photography and finely lit, monochrome product renders. Light grotesk typography and tiny monospaced markings make the spacious compositions feel both ambitious and materially credible.

### Essentials

- The opening is a working world, not a slogan poster: full-bleed 900px-tall media, a lower-left 52px/1 light headline limited to 520px, and one small glass action 48px below it.
- Lightweight type carries the ambition while equipment-like labels carry the detail: sans weight 300 at 52px, 32px and 96px; uppercase mono at 12px/1.3 with 0.01em tracking and a small square section marker.
- White space and tightly joined media coexist: narrative sections use 60px or 120px padding, but square imagery sits within 8px gutters and 80px rounded corners.
- Controls feel like soft industrial housings: ordinary actions use 16px corners and 17.5px 22.4px padding; image links use 56px-high glass capsules with a 48px circular arrow inset.
- Color belongs to the real world, not the interface: white dominates the default body, warm off-white backs the technical chapter, and near-black closes the page. Greens, blue skies and safety colors live inside subdued photography; there are no bright marketing fills.
- Show the product as a material object: include a large grayscale technical study beside a compact accordion, using a layered isometric diagram if polished 3D is unavailable. Pair this with 96px proof figures and tiny uppercase captions.
- End with a monumental identity imprint: a near-black 613px footer places four numbered mono link columns above a 470px-wide white identity graphic, with a long interval of open space between. Use an original oversized wordmark or geometric monogram for the new identity.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Almost black | `#0f0e12` | `--color-night` | background, surface, text | Footer and dark media backing; inverse button text. Entire technical-detail pages use this as their canvas. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text, action | Default page ground; inverse text, toggle disks and subscription action. |
| Warm charcoal | `#322d2a` | `--color-ink` | text, border | Default text and dark product-panel hairline. |
| Secondary graphite | `#625b58` | `--color-muted` | text | Inactive accordion headings and secondary descriptive text. |
| Smoked glass | `#8b8b8b` | `--color-glass` | surface | Neutral appearance of rgba(23,23,23,0.5) over white; on imagery it retains the underlying image color. Used for floating navigation and media controls. |
| Warm silver | `#bfb8b5` | `--color-edge` | border, text, action | Outlined action edges, hover fills and softened second lines of editorial headlines. |
| Warm chalk | `#f0efe9` | `--color-chalk` | surface, background | Technical accordion band and light product-comparison panel. |

## Typography

- **Helvetica** — Headlines, large narrative copy, statistics and controls. Open, restrained grotesk with light strokes and uncomplicated rounded forms. If unavailable, use **Inter**. Use 300 for large copy and 400 for controls; keep normal display tracking. Font stack: "Helvetica", "Inter", Helvetica, Arial, sans-serif.
- **Courier New** — Section labels, proof captions, dates and numbered footer navigation. Small utilitarian monospace, usually uppercase rather than display-sized. If unavailable, use **IBM Plex Mono**. Use 400 with 0.01em tracking. Font stack: "Courier New", "IBM Plex Mono", "Courier New", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| stat | Helvetica | 300 | 96px | 1 | normal | fixed | Proof figures with currency, units and punctuation at the same scale; facility title on technical-detail pages. |
| display | Helvetica | 300 | 52px | 1 | normal | fixed | Hero headline, paired editorial headline and closing invitation. |
| narrative | Helvetica | 300 | 32px | 1.2 | normal | fixed | Main explanatory prose, section statements and pull quotes; also product-panel titles. |
| item-heading | Helvetica | 300 | 24px | 1.3 | normal | fixed | Accordion headings and article titles. |
| body | Helvetica | 400 | 14px | 1.3 | 0.01em | fixed | Navigation, announcement copy, names and secondary information. |
| action | Helvetica | 400 | 14px | 1 | normal | fixed | Hero and subscription buttons; profile actions. |
| action-tracked | Helvetica | 400 | 14px | 1 | 0.01em | fixed | Outlined narrative actions and image-link captions. |
| label | Courier New | 400 | 12px | 1.3 | 0.01em, uppercase | fixed | Section markers, dates, technical explanations, stat captions and numbered footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| facility or operational proof features | overlay-stat | Helvetica | 300 | 43.2px | 1.2 | normal | size max(2.8rem, min(3vw, 7rem)) | Capacity figures within large glass overlays. |
| technical product comparisons | spec-tag | Helvetica | 400 | 20px | 1 | normal | fixed | Compact outlined specifications next to panel titles. |
| technical product comparisons | product-body | Helvetica | 300 | 16px | 1.3 | 0.01em | fixed | Centered panel descriptions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Large text is light, not bold, and uses normal tracking. Contrast comes from scale, alignment and shifts of background rather than typographic weight.
- Keep units as large and light as the number. Small mono captions sit immediately below, not inside colored badges.
- Editorial paired headlines keep both lines at 52px/1 and distinguish the second through warm silver, not a heavier or smaller cut.

## Layout

**Density:** Airy narrative fields alternate with tightly packed edge-to-edge media; controls and labels remain compact.

### Spacing

**Spacing system:**

- **rhythm** 12px, vertical — Primary vertical rhythm for 24px, 48px, 60px, 96px and 120px intervals; media gutters and controls are separate exceptions.

| Value | Use |
| --- | --- |
| 8px | Outer media inset, tile gutters, footer link spacing and small copy stacks. |
| 12px | Accordion row gap. |
| 24px | Announcement content-to-thumbnail gap and compact text groups. |
| 36px | Fixed-header top and side inset. |
| 48px | Narrative-to-action separation and accordion content padding. |
| 60px | Compact narrative section padding and profile grid row gap. |
| 96px | Hero bottom clearance and space between stacked proof items. |
| 120px | Major proof-section padding and editorial side inset. |

### Containers and grids

- **narrative container**: max width 1400px · 2 columns · gap 0px · side padding 60px. Small label takes the left half; explanatory copy begins at the central axis and fills the right half. At 1440px the content is 1320px wide.
- **deep inset container**: max width 1400px · 2 columns · gap 0px · side padding 120px. Editorial headlines, proof and footer content; 1200px usable width at desktop.
- **media pair**: 2 columns · gap 8px · side padding 8px. Two 708px square scenes share the viewport; asymmetric variants use one-third and two-thirds widths.
- **news strip**: 4 columns · gap 8px · side padding 8px. Four 350px square images across the viewport with metadata and titles beneath.
- **technical split**: 2 columns · gap 8px · side padding 8px. A 712px technical illustration occupies the left half; the right half centers a 360px accordion with 48px inner padding.
- **people directory** (only for organization and people pages): 3 columns · gap 8px · side padding 120px. A three-column grid occupies only the right half of the narrative container; 60px row gaps and 195px-wide portraits.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | ordinary controls | 16px |
|  | media panels | 80px |
|  | image action capsules | 100px |
|  | icon disks | 50% |
| subscription invitations | subscription button | 12px |
| facility or operational proof features | proof overlays | 72px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default marketing body.

**CSS:** `background: #ffffff; color: #322d2a`

**Observed:** Flat unboxed narrative content; shadows do not separate sections.

**Transfer:** Let white intervals carry the prose between large visual chapters.

#### Night canvas · level 0

**Use:** Shared footer and dark media stages.

**CSS:** `background: #0f0e12; color: #ffffff`

**Observed:** A continuous near-black field, not a collection of elevated black cards.

**Transfer:** Use as the default ending; extend through the body only for a technical-detail variant.

#### Chalk chapter · level 0

**Use:** Light technical explainer band.

**CSS:** `background: #f0efe9; color: #322d2a`

**Observed:** The full band backs both a grayscale object and its accordion.

**Transfer:** Choose one concentrated technical chapter rather than alternating tinted boxes for every feature.

#### Rounded media stage · level 1

**Use:** Facility scenes and product imagery.

**CSS:** `border-radius: 80px; overflow: hidden; background: #0f0e12`

**Observed:** Very large corners belong to square or near-square panels with only 8px between them.

**Transfer:** Keep image dominant and avoid inset card padding.

#### Smoked glass · level 2

**Use:** Floating content over photographs or renders.

**CSS:** `background-color: rgba(23, 23, 23, 0.5); border-radius: 16px; backdrop-filter: blur(25px)`

**Observed:** Different controls use 10px, 25px or 50px blur; the backing is neutral and translucent rather than frosted white.

**Transfer:** Retain enough of the scene beneath to make the controls feel attached to the image.

#### Large proof glass · level 2

**Only for:** facility or operational proof features

**Use:** Capacity overlays on a panoramic scene.

**CSS:** `background-color: rgba(23, 23, 23, 0.5); border-radius: 72px; backdrop-filter: blur(25px); padding: 40px 40px 54px`

**Observed:** 377px square panels sit at the right edge of a large photographic asset, separated by 8px.

**Transfer:** Use operational facts or a genuine location context, not decorative dashboard widgets.

## Components

### Floating navigation

**Use:** Persistent compact navigation over imagery and narrative sections.

**CSS:** `display: flex; align-items: center; justify-content: flex-end; gap: 60px; padding: 4px 24px; background-color: rgba(23, 23, 23, 0.5); border-radius: 16px; height: 44px; box-sizing: border-box`

**Text style:** `body` — Helvetica 400 · 14px/1.3 · tracking 0.01em

**Observed:** A standalone identity mark sits at upper left; the navigation floats at upper right within a fixed header inset by 36px. White text and small northeast arrows mark external destinations. The backing includes a translucent white pseudo-layer.

**Transfer:** Use a short set of primary destinations; preserve the slim bar rather than a full-width header slab.

### Hero button

**Use:** The single opening action over media.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 17.5px 22.4px; background-color: rgba(23, 23, 23, 0.5); color: #ffffff; border-radius: 16px; backdrop-filter: blur(50px); border: 0px`

**Text style:** `action` — Helvetica 400 · 14px/1

**Observed:** Text-only action below the opening headline, not a bright conversion banner.

**States:** Declared: hover transform scale(0.985), background-color #ffffff and color #0f0e12; focus-visible unknown.

**Transfer:** Use a short exploratory verb suited to the page's next chapter.

### Outline button

**Use:** Secondary exploration after narrative statements.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 17.5px 22.4px; border: 1px solid #bfb8b5; border-radius: 16px; color: #322d2a; background: transparent`

**Text style:** `action-tracked` — Helvetica 400 · 14px/1 · tracking 0.01em

**Observed:** The default body action is outlined. Profile cards use the same shell with the untracked action recipe and a shorter label.

**States:** Declared: hover transform scale(0.985) and background-color #bfb8b5; focus-visible unknown.

### Media capsule

**Use:** Image-centered link to a visual chapter or detailed feature.

**CSS:** `display: inline-flex; align-items: center; gap: 23.8px; padding: 4px 4px 4px 22.4px; border-radius: 100px; background-color: rgba(23, 23, 23, 0.5); backdrop-filter: blur(50px); color: #ffffff`

**Text style:** `action-tracked` — Helvetica 400 · 14px/1 · tracking 0.01em

**Observed:** Label precedes a right arrow in a 48px circle with rgba(255,255,255,0.2) fill. Capsule floats near the center of a rounded photograph; technical detail tiles use the untracked action recipe.

**States:** Declared: hover transform scale(0.985), background-color hsla(0,0%,9%,.5) and color #ffffff; focus-visible unknown.

### Accordion toggle

**Use:** Expand compact technical explanations beside a material study.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 48px; height: 48px; border-radius: 50%; background-color: #ffffff; color: #0f0e12; overflow: hidden`

**Observed:** A 24px plus becomes a short minus when open. The disk is aligned to the right edge of a 360px-wide row; heading and mono explanation sit to its left. One row is visibly open and others muted.

**States:** Declared: hover transform scale(0.95); focus-visible unknown.

**Transfer:** Keep explanations compact and the illustration synchronized with the selected subject.

### Announcement card

**Use:** Small timely story on the opening media stage.

**CSS:** `display: flex; align-items: center; gap: 24px; padding: 8px 8px 8px 18px; border-radius: 16px; background-color: rgba(23, 23, 23, 0.5); backdrop-filter: blur(25px); color: #ffffff; width: 346px; box-sizing: border-box`

**Text style:** `body` — Helvetica 400 · 14px/1.3 · tracking 0.01em

**Observed:** Tiny square-marked mono eyebrow and short copy sit left of a 100px square thumbnail. Card aligns with the hero action baseline on the lower right.

**States:** Declared: hover transform scale(0.99); focus-visible unknown.

**Transfer:** Use a current story with a genuine thumbnail; keep it subordinate to the opening promise.

### Numbered footer

**Use:** Shared ending and navigational index.

**CSS:** `background-color: #0f0e12; color: #ffffff; padding: 0px 120px 30px`

**Text style:** `label` — Courier New 400 · 12px/1.3 · tracking 0.01em · uppercase

**Observed:** Four link columns begin 82px below the top, with 8px row gaps. Number prefixes are softer than names. Below a long open interval, a large white identity graphic anchors the left and compact rights information aligns on the right.

**States:** Declared: hover link opacity 0.66; focus-visible unknown.

**Transfer:** Index product, organization, social and legal destinations using decimal prefixes; preserve the oversized identity finish.

### Inline subscription form

**Only for:** subscription invitations

**Use:** A single-field conversion embedded in a photographic closing band.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 42px; max-width: 470px; padding: 4px; border-radius: 16px; background-color: rgba(23, 23, 23, 0.5); backdrop-filter: blur(10px); overflow: hidden`

**Text style:** `body` — Helvetica 400 · 14px/1.3 · tracking 0.01em

**Observed:** A transparent email field and white inset action form one horizontal bar, visually balanced against the invitation on the left.

**Transfer:** Limit the form to one field and one action so the landscape remains dominant.

### Subscription button

**Only for:** subscription invitations

**Use:** Inset submission control for the inline form.

**CSS:** `padding: 17.5px 22.4px; border-radius: 12px; background-color: #ffffff; color: #0f0e12; border: 0px`

**Text style:** `action` — Helvetica 400 · 14px/1

**Observed:** Contrasts with the surrounding smoked form rather than using a chromatic action color.

**States:** Declared: hover transform scale(0.985), background-color #0f0e12 and color #ffffff; focus-visible unknown.

### Operational proof panel

**Only for:** facility or operational proof features

**Use:** Compact statistics over a wide photograph.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 40px; padding: 40px 40px 54px; border-radius: 72px; background-color: rgba(23, 23, 23, 0.5); backdrop-filter: blur(25px); overflow: hidden`

**Text style:** `overlay-stat` — Helvetica 300 · 43.2px/1.2

**Observed:** A small mono contextual caption sits above two large capacity figures and their uppercase labels; panel occupies the right side of the photographic stage.

**Transfer:** Replace capacity with validated operational measures relevant to the new product.

## Imagery and graphics

### Documentary working world

**Use:** Opening media, capability scenes and supporting proof.

**Observed:** Wide factory footage shows people actually handling equipment, with deep perspective, overhead fluorescent light and large foreground machinery. The grade is subdued, slightly cool and gray-green; safety clothing provides small natural color accents. Facility photographs include pale industrial buildings and construction sites under muted skies.

**Transfer:** Show the new product being made, used or maintained. Use a full-width still with comparable depth and real human activity if film is unavailable. Apply a restrained darkening veil so white type remains clear without turning the scene into black texture.

### Material object studies

**Use:** Technical chapter and product media panels.

**Observed:** Monochrome 3D objects are presented as tangible assemblies: dark finely patterned surfaces, reflective edge frames and translucent exploded layers. A large isometric object fills most of the left half while a compact accordion sits right. The light chapter uses chalk backing; the dark variant places pale transparent layers on a warm gray rounded stage.

**Transfer:** Render the product's structure or a meaningful system of layers rather than a generic floating cube. Minimum acceptable version is a crisp isometric SVG with believable ordering, material contrast and a few thin edge highlights.

**Build:** Construct an isometric assembly with SVG polygons sharing the same four-corner parallelogram. Stack 5–7 planes separated vertically by 24px–40px, spanning about 560px inside a 712px stage. Use warm silver, white at 0.15–0.45 alpha and charcoal side faces, with 1px low-opacity white edge strokes. Add fine repeated lines or a clipped grid to one functional layer. Keep the same angle and registration across every layer; no neon glow.

### Monumental identity graphic

**Use:** Every page's footer.

**Observed:** A flat white geometric identity mark is 470px wide and 176px tall on near-black, separated from the navigation above by roughly 210px of open space.

**Transfer:** Use the new identity at comparable optical scale; a simple original typographic lockup is sufficient.

**Build:** Place an original wordmark or geometric monogram in an SVG viewBox with about a 2.7:1 aspect ratio. Use a single white fill with no stroke, embossing or shadow. Fit it to 470px width at desktop and anchor to the left content inset.

### Product closeups

**Only for:** technical product pages

**Use:** Dark opening and asymmetric detail image pairs.

**Observed:** Oversized grayscale components are cropped beyond the upper and right frame edges on black. Grazing light reveals thin frames, fine repeated conductor lines and translucent surfaces. Detail pairs use one small square and one much larger square, both with 80px corners.

**Transfer:** Photograph or render material edges and functional textures at macro scale; use a strong directional light and retain dark negative space for the headline.

### Aerial landscape

**Only for:** subscription invitations

**Use:** 700px-tall closing conversion scene.

**Observed:** Straight-down landscape photography shows dark green woodland, stone, open earth and meandering paths. It is darkened and desaturated, with a white invitation on the left and smoked form on the right, both vertically centered.

**Transfer:** Choose an environment meaningfully connected to the new product, viewed from above with broad organic masses; the image must remain readable behind a restrained conversion layer.

### Portrait directory

**Only for:** organization and people pages

**Use:** Leadership or expert directories.

**Observed:** Small vertical portraits measure 195px by 237px and are followed by name, muted role text and an outlined View action. Three columns sit on the right half of a largely open white composition.

**Transfer:** Use consistently framed original portraits with restrained backgrounds and genuine credentials; do not inflate these into large promotional cards.

### Icons

**Observed:** Accordion controls use 24px filled black plus/minus symbols in 48px white disks. Media actions use 24px white right arrows, 2px square-ended strokes, inside translucent disks. Section labels have a small solid square marker; external navigation has a northeast arrow.

**Transfer:** Use geometric plus, minus, square and straight arrows rather than a broad illustrative icon family. Keep symbols visually secondary to the imagery and type.

## Section recipes

How recurring sections are built.

### First screen: Cinematic working-world opening

**Observed:** The first 900px is a full-bleed film stage. From back to front: documentary activity with machinery spanning the frame, restrained darkening for contrast, a fixed header with separate upper-left identity and slim upper-right Floating navigation, then a lower-left two-line 52px/1 headline in a 520px measure. Text starts at the 120px narrative inset, occupying roughly the left third while the working scene dominates. Hero button sits 48px below it, with 96px breathing room to the bottom. Announcement card balances the lower right. Headline, action, main activity and announcement are all visible in the first screen; the white narrative chapter begins below it. There is no separate support paragraph in the opening.

**Transfer:** Use real work or use-context footage for a different product; a high-quality still can carry the same composition. Keep the headline compact enough that the activity remains the main object. Technical-detail openings use the same low headline and action over an oversized grayscale product on black. Organization pages instead open on white with a two-line 52px headline, a silver second line, 240px top padding and a rounded asymmetric image pair beginning below.

**Avoid:** Do not center the headline across the entire video, add several bright CTAs, or replace the working scene with a small object inside an ordinary card.

**Text style:** `display` — Helvetica 300 · 52px/1

### Offset narrative statement

**Observed:** Within narrative container, a square-marked label anchors the left half and 32px/1.2 explanatory prose starts on the central axis. Outline button follows after 48px. Compact chapters use 60px padding; deeper proof introductions use 120px.

**Transfer:** Use the small label as a chapter name and the right column for one specific argument. Let the empty left field remain intentional.

**Text style:** `narrative` — Helvetica 300 · 32px/1.2

### Rounded evidence pair

**Observed:** Media pair places two square photographs edge to edge with 8px gaps and 80px corners. Each has a centered Media capsule. Asymmetric detail variants use one-third and two-thirds widths.

**Transfer:** Pair two different scales or contexts of the same product, not two unrelated stock photographs.

### Technical study with accordion

**Observed:** Chalk chapter contains technical split: large isometric material study on the left and 360px-wide list on the right. Item headings use 24px/1.3, 48px Accordion toggles and 12px gaps. The selected item exposes uppercase mono explanation; inactive headings use secondary graphite. The technical-detail variant uses Night canvas.

**Transfer:** Explain a real mechanism or material stack with one concise description per layer. Keep diagram and selected row semantically connected.

**Text style:** `item-heading` — Helvetica 300 · 24px/1.3

### Stacked monumental proof

**Observed:** A 120px-inset white chapter combines a small left label, right-side narrative and Outline button. After 120px, three proof figures stack on the right with 96px between entries. Each uses Stat type with same-sized units and tiny mono captions. A small rounded architectural photograph anchors the otherwise open left side lower in the section. Technical-detail proof uses the same hierarchy in white on Night canvas.

**Transfer:** Choose a few meaningful measured outcomes, with context and time period in the caption; retain the contrast of huge figures and miniature labels.

**Text style:** `stat` — Helvetica 300 · 96px/1

### Editorial update strip

**Observed:** An inset label and 32px introduction lead into the full-width news strip. Four square images have dates and 24px article titles below; there are no surrounding card shells. Gaps between metadata blocks are about 26px.

**Transfer:** Use recent proof, research or updates. Let image, date and title do the work rather than adding category pills and summaries.

**Text style:** `item-heading` — Helvetica 300 · 24px/1.3

### Indexed identity ending

**Observed:** Numbered footer closes the default marketing page directly after editorial updates; longer editorial and technical pages precede it with Landscape invitation. It is 613px tall with four mono link columns above a monumental white identity graphic and compact rights line.

**Transfer:** Always preserve the numbered index and identity imprint, while choosing whether a conversion scene is relevant before it.

**Text style:** `label` — Courier New 400 · 12px/1.3 · tracking 0.01em · uppercase

### Contrasting product pair

**Only for:** technical product comparisons

**Observed:** Two 708px square panels with 80px corners contrast Night canvas and Chalk chapter. Centered 32px titles share a line with 20px outlined spec tags; 16px descriptions sit beneath after 48px. Product imagery rises from and is cropped by the lower panel edges. The dark panel has a 1px warm charcoal outline.

**Transfer:** Compare genuinely distinct formats or applications, keeping each description short and the physical object dominant.

**Text style:** `product-body` — Helvetica 300 · 16px/1.3 · tracking 0.01em

### People and credibility chapter

**Only for:** organization and people pages

**Observed:** A small label remains on the left while people directory fills the right half. Portraits are followed by name, role and Outline button; 60px row gaps separate successive rows. A 32px pull quote and full-width working-world video introduce the human material before the directory.

**Transfer:** Use the offset grid for named experts or contributors with relevant responsibilities rather than generic testimonials.

### Landscape invitation

**Only for:** subscription invitations

**Observed:** Aerial landscape occupies 700px full width. A 52px white invitation sits at the left 120px inset; Inline subscription form sits on the right, both vertically centered. The scene meets the dark footer without a light divider.

**Transfer:** Use a simple relationship-building action against a meaningful environment instead of ending a long editorial or technical page with a dense form.

**Text style:** `display` — Helvetica 300 · 52px/1

## Page flow

**Storyline:** Cinematic promise → concise purpose → material or operational demonstration → mechanism explanation → quantified credibility → editorial or relational close → indexed identity ending.

### Broad marketing landing page connecting a promise to real capability

1. **Promise** — Working-world film, low white headline, exploratory action and small current-story card.
2. **Purpose** — Offset label and large narrative statement.
3. **Capability demonstration** — Rounded location pair and split product stage.
4. **Mechanism explanation** — Light technical study with compact accordion.
5. **Quantified proof** — Huge stacked figures with small contextual captions.
6. **Editorial proof** — Four-image update strip.
7. **Closing navigation** — Dark numbered footer and monumental identity.

**Transfer:** Alternate narrative breathing space with physical proof; choose the specific demonstrations according to the product rather than reproducing the same topic sequence.

### Organization narrative that connects place, people and credibility

1. **Positioning** — White editorial opening with a softened second headline line.
2. **Context** — Asymmetric rounded photographs establish place and people.
3. **Human demonstration** — Offset team statement, full-width workplace film and pull quote.
4. **Credibility** — Right-half portrait directories with short roles and profile actions.
5. **Relationship invitation** — Landscape scene with invitation and single-field subscription.
6. **Closing navigation** — Shared numbered dark footer.

**Transfer:** Use this light editorial variant for people-led stories, with real work imagery connecting the opening to the experts.

### Detailed product narrative emphasizing structure, formats and performance

1. **Product promise** — Dark oversized material rendering with low headline and exploratory action.
2. **Product demonstration** — Asymmetric closeups followed by a two-tone format comparison.
3. **Quantified proof** — Large white performance figures on near-black.
4. **Capability explanation** — Short durability statement, four image-linked features and exploded material accordion.
5. **Operational credibility** — Wide facility scene with contextual glass capacity panels.
6. **Relationship invitation** — Landscape subscription scene.
7. **Closing navigation** — Shared numbered dark footer and oversized identity.

**Transfer:** Keep this continuous dark variant for technically rich products; demonstrate physical structure and outcomes before ending with the same human-scale invitation.

## Writing

Declarative, materially grounded and optimistic. Ambition is expressed through plain assertions about building, producing and improving, with technical specifics doing more work than emotional adjectives.

**Do not copy:** Do not reuse T1 Energy's names, logos, facility identifiers, geographic claims, financial results, performance figures, proprietary technology claims, fund announcements or attributed quotations. Source phrases below illustrate structure, not reusable claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly third-person brand statements and impersonal technical descriptions. First-person plural appears sparingly; direct reader address is concentrated in actions and invitations.
- **Rhythm:** Short noun-like section labels, compact four-to-eight-word headlines, then one or two substantive sentences. Technical explanations can be denser but stay factual; actions are usually one or two words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A concise claim of capability plus product category; no long setup. | 4–8 words | “Advanced American Solar and Storage”<br>“Industry Leading TOPCon Solar” |
| Section statement | Plain subject, active construction verb and practical consequence. | One or two sentences | “T1 delivers durable solar components that efficiently convert sunlight into electricity.” |
| Paired headline | Two compact, parallel phrases, with the second expanding the first. | 3–7 words per pair | “Two form factors. Powerful possibilities.” |
| Section label | Single technical or organizational noun. | 1–2 words | “Mission”<br>“Efficiency” |
| Proof caption | Measurement context, period or comparison; avoid rhetorical praise. | 3–8 words | “Q1 2026 Adjusted EBITDA”<br>“Electricity produced per acre vs competitor” |
| Action | Short familiar verb or verb phrase. | 1–2 words | “Discover”<br>“Learn More”<br>“Join the movement” |

**Words and phrasing to use:** build; produce; advance; durable; reliable; efficient; capacity; materials; future

**Avoid:** magical; game-changing; supercharge; crush it; effortless everything; emoji-led slogans

**Rules:**

- Tie ambitious positioning to a concrete mechanism, material or measurable result nearby.
- Use specific units and comparison contexts for proof figures.
- Keep technical terms where they clarify the mechanism, not as decorative jargon.
- Let tiny section labels orient the reader while the larger prose supplies the argument.

## Do's and Don'ts

### Do

- Keep the default body white with warm charcoal copy and reserve near-black for media and the ending.
- Set major headlines at 52px/1 and weight 300 rather than bold display type.
- Keep the 8px media gutter conspicuously tighter than the 60px and 120px narrative padding.
- Use 80px corners on large image panels and 16px corners on ordinary controls.
- Give 96px proof figures tiny 12px uppercase mono context rather than a competing headline.
- Pair one large technical study with a 360px accordion and 48px circular controls.
- Keep photographic color subdued and let real materials provide color variation.
- Use the dark numbered footer and an original oversized white identity graphic on every page.

### Don't

- Do not turn ordinary text buttons into full pills; the pill silhouette belongs to image capsules.
- Do not add drop shadows to white narrative sections or news cards; the surface hierarchy is flat.
- Do not use the map provider's blue or warning-dialog styling as marketing accents.
- Do not set long narrative statements in 14px body type; their prominence comes from the 32px light recipe.
- Do not shrink percent signs or units into superscripts next to 96px figures.
- Do not fill the open left half of offset chapters with decorative cards.
- Do not use vivid synthetic gradients behind the monochrome material studies.
- Do not extend 80px rounding to the small portrait directory or every text block.

## Motion and responsive

### Motion

**Observed:**

- Declared button transitions are background-color .25s,color .25s, with hover scale(0.985); announcement hover scale is 0.99 and circular accordion control hover scale is 0.95.
- Footer links declare opacity .25s and hover opacity 0.66. Some navigation items declare color 0.5s.
- Opening stages use video; content includes sticky and layered media arrangements.

**Transfer:**

- Keep the slight inward scaling and restrained color inversion on actions; do not substitute bouncing or glowing interaction effects.
- Retain the still-image composition when motion cannot run so the low headline and working scene remain legible.

**Unknown:**

- Exact film playback, scroll animation choreography, trigger thresholds and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 767px, 768px, 1180px and 1180px; an organization-page stylesheet also includes 1400px.

**Transfer:**

- On narrow layouts, preserve the low-anchored opening headline over full-width media; move the announcement beneath the main action if space is insufficient.
- Stack the technical illustration above the accordion and keep the selected explanation visibly attached to its heading.
- Reduce multi-column image and footer arrangements while retaining the tight media gutters, numbered links and oversized identity proportion.

**Unknown:**

- Exact mobile type sizes, spacing, navigation form and corner-radius changes are not established; narrow-layout rules here are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
