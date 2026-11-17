# Bear — paper with a wink

## Overview

An approachable, airy product style that pairs rounded sans-serif lettering with a white paper world and small coral-red actions. Oversized interface scenes float over soft organic color shapes, while faint storybook line drawings make the technical product feel personal. It suits thoughtful consumer software and creative tools, with compact explanatory copy inside a spacious, mostly light composition.

### Essentials

- Friendly headlines feel bold without typographic aggression: bearsansheadline at 51.2px/1.1 for centered statements and 41.6px/1.1 for capability headings, with normal tracking.
- The opening is a centered product invitation rather than a billboard: a 64px white navigation bar, headline beginning after 208px of top space, a smaller platform line, selector row and download badge above a large floating interface scene.
- Actions are small coral rectangles, not pills: #dd4c4f with white 16px text, 8px corners and 8px 24px padding; the opening instead uses a monochrome marketplace badge.
- White remains the dominant field; color lives in isolated organic backdrops and short headings rather than full-width saturated bands. Capability titles use blue #456aa3, purple #884aa8 and green #2b6451 against pastel shapes.
- Demonstrations feel like loose paper objects: layered, occasionally tilted interface panels, soft 0px 13px 34px shadows and 16px media corners. If no interface exists, make a believable task-result panel rather than substituting generic stock photography.
- A hand-drawn second voice must accompany the polished product: an aqua underline and small rays, faint perimeter doodles and a broad low-contrast illustrated breathing space near a conversion. A simple original landscape in thin gray SVG lines is the minimum equivalent.
- Rounded secondary cards are deliberately softer than the media: #f3f5f7 fields with 40px corners, while testimonials stay unboxed with a narrow 4px coral ribbon.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral red | `#dd4c4f` | `--color-accent` | action, link, accent | Compact filled actions, text links, selected checks and testimonial ribbons; not a page-sized background. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Capability blue | `#456aa3` | `--color-chapter-blue` | text, accent | Short capability heading and matching bullets in a blue-backed demonstration chapter. |
| Capability purple | `#884aa8` | `--color-chapter-purple` | text, accent | Short capability heading and matching bullets in a purple-backed demonstration chapter. |
| Capability green | `#2b6451` | `--color-chapter-green` | text, accent | Short capability heading and matching bullets in a green-backed demonstration chapter. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, surface, text | Dominant canvas and floating panels; reversed button and badge lettering. |
| Cool paper | `#f3f5f7` | `--color-soft-panel` | surface, border | Secondary capability cards and very faint pricing separators. |
| Input edge | `#d9d9d9` | `--color-edge` | border | Thin outline around email fields. |
| Pencil gray | `#888888` | `--color-muted` | text | Centered explanatory subtitles, secondary price units and subdued attribution. |
| Charcoal ink | `#444444` | `--color-ink` | text | Default headings, body, navigation and monochrome conversion graphics. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| premium capability labels | Golden label | `#fcb827` | `--color-premium-yellow` | surface, accent | Tiny premium badge accompanying a yellow-backed capability chapter. |

## Typography

- **bearsans** — Body copy, links, controls, platform selectors and prices. Soft, readable sans serif with open shapes and an informal humanist feel. If unavailable, use **Nunito Sans**. Use 400 for prose and 700 for emphatic short labels. Font stack: "bearsans", "Nunito Sans", Arial, sans-serif.
- **bearsansheadline** — Hero, section and card titles; compact footer group names. Rounded, sturdy headline cut that looks bold even though its declared weight is 400. If unavailable, use **Nunito Sans**. Use 800 to approximate the heavier headline cut without tightening tracking. Font stack: "bearsansheadline", "Nunito Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | bearsansheadline | 400 | 51.2px | 1.1 | normal | Centered hero and major section statements. |
| heading | bearsansheadline | 400 | 41.6px | 1.1 | normal | Left-aligned capability titles and plan names. |
| card-heading | bearsansheadline | 400 | 30.4px | 1.1 | normal | Secondary capability card headings. |
| hero-platform | bearsansheadline | 400 | 25.6px | 2.2 | normal | Compact centered availability line beneath the opening promise. |
| selector | bearsans | 400 | 24px | 1.133 | normal | Platform choices immediately below the opening title. |
| lead | bearsans | 400 | 22.4px | 1.4 | normal | Muted centered supporting copy and larger social text links. |
| quote-title | bearsans | 700 | 17.6px | 1.455 | normal | Short testimonial headline. |
| body | bearsans | 400 | 16px | 1.7 | normal | Benefit bullets, explanatory copy and ordinary navigation links. |
| button | bearsans | 400 | 16px | 1.7 | 0.031em | White labels inside compact filled actions. |
| quote-body | bearsans | 400 | 16px | 1.6 | normal | Testimonial quotation and attribution links. |
| footer-link | bearsans | 400 | 16px | 1.8 | normal | Stacked footer navigation links. |
| footer-heading | bearsansheadline | 400 | 16px | 1.8 | normal | Small footer group titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing comparisons | price | bearsans | 400 | 40px | 0.68 | normal | Plain regular-weight currency figures, paired with smaller muted billing units. |
| download collections | download-category | bearsans | 400 | 19.2px | 1.1 | normal | Device or format group names above a vertical set of links. |
| premium capability labels | premium-label | bearsans | 700 | 16px | 1.4 | normal | Small uppercase badge attached to a capability heading. |

**Notes:**

- Keep tracking normal at every headline size; rounded letterforms and the special headline cut provide the personality rather than compressed spacing.
- The declared headline weight is 400 but the face itself is visually bold. Do not render the substitute at a thin regular weight.
- Large centered headings pair with muted 22.4px copy capped at 582.4px; detailed benefits drop to 16px rather than retaining hero-sized text.

## Layout

**Density:** Airy: large narrative intervals surround compact benefit lists and small controls.

### Spacing

**Spacing system:**

- **vertical rhythm** 16px, vertical — Primary section intervals and many block margins follow multiples of 16px.
- **horizontal step** 8px, horizontal — Container insets and grid spacing commonly follow multiples of 8px.

| Value | Use |
| --- | --- |
| 8px | Vertical padding inside filled actions. |
| 16px | Heading-to-subtitle spacing. |
| 24px | Button horizontal padding and bullet indentation. |
| 32px | Wrapper side padding and footer grid gaps. |
| 40px | Text inset inside large secondary capability cards. |
| 48px | Gap before the newsletter form and inner pricing-list insets. |
| 64px | Gap before large demonstrations and testimonial row spacing. |
| 80px | Testimonial column gap and secondary capability chapter separation. |
| 96px | Footer links-to-credit separation. |
| 160px | Broad separation between capability scenes and around newsletter block. |
| 304px | Only for download collections: separation after each illustrated entry. |

### Containers and grids

- **standard-wrapper**: max width 960px · side padding 32px. Centered wrapper for opening text, pricing, community, newsletter and footer; leaves an 896px inner field.
- **lead-measure**: max width 582px. Centered explanatory lines kept narrow enough for two or three balanced lines.
- **capability-wrapper**: max width 1088px · 2 columns · side padding 32px. Alternating text and floating-media chapters; images and their organic backing intentionally reach beyond the wrapper.
- **demo-frame**: max width 1056px · side padding 8px. Wide central demonstration frame.
- **testimonials**: 2 columns · gap 80px. Two columns of unboxed quotations with a 64px row gap.
- **footer-grid**: 4 columns · gap 32px. Four auto-width navigation groups spaced across the inner wrapper.
- **collection-entry** (only for download collections): max width 960px · 2 columns · side padding 32px. A 358px text-and-download area beside an overlapping illustration stack; alternate left and right between entries.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 8px |
| media | 16px |
| capability-and-price-cards | 40px |
| email-field | 8.8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating-paper | `rgba(0, 0, 0, 0.12) 0px 13px 34px 0px` | Demonstration panels and the raised paid plan. |
| download collections | gallery-art | `rgba(34, 113, 140, 0.3) 0px 13px 34px 0px` | Cool-tinted shadow behind overlapping art previews. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default page field and fixed navigation backing.

**CSS:** `background: #ffffff; color: #444444`

**Observed:** Broad uncolored spaces continue through the page; there are no heavy section dividers.

**Transfer:** Let objects, not section backgrounds, define the hierarchy.

#### Floating paper · level 1

**Use:** Wide demonstration and raised comparison panel.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: rgba(0, 0, 0, 0.12) 0px 13px 34px 0px`

**Observed:** A slim white rim surrounds the central demo. The paid-plan variant uses 40px corners.

**Transfer:** Use a restrained lifted sheet, not a bordered dashboard shell.

#### Soft capability field · level 0

**Use:** Secondary feature cards.

**CSS:** `background: #f3f5f7; border-radius: 40px; overflow: hidden`

**Observed:** Tall cards mix centered heading, brief copy and a large illustrative demonstration with no visible outline.

**Transfer:** Vary card heights around the demonstration rather than forcing identical tiles.

#### Organic chapter backing · level 0

**Use:** Color behind selected capability demonstrations.

**CSS:** `position: absolute; background: rgba(68, 162, 170, 0.5); border-radius: 44% 56% 62% 38% / 38% 35% 65% 62%`

**Observed:** Flat aqua, dusty purple, sage and warm yellow shapes extend beyond the page edge, leaving the text on white. There is no luminous gradient or texture.

**Transfer:** Match the soft flat pigment; exact contour and color stops are not essential.

## Components

### Fixed navigation

**Use:** Persistent lightweight site orientation.

**CSS:** `position: fixed; height: 64px; background: #ffffff; z-index: 3; display: flex; align-items: center`

**Text style:** `body` — bearsans 400 · 16px/1.7

**Observed:** A compact colored symbol and dark word label sit left; five plain text links sit right inside Standard wrapper. The brand mark is about 38px square.

**Transfer:** Keep the bar editorial and unobtrusive; no oversized conversion button is needed here.

### Primary button

**Use:** Newsletter submission and compact continuation actions.

**CSS:** `background: #dd4c4f; color: #ffffff; border-radius: 8px; padding: 8px 24px; text-align: center; letter-spacing: 0.5px`

**Text style:** `button` — bearsans 400 · 16px/1.7 · tracking 0.031em

**Observed:** Content-width rectangle, about 43px high, aligned beside a field or centered on its own.

**Transfer:** Use short verb-led labels rather than lengthy pitches.

### Text link

**Use:** Inline attribution, social or download destinations.

**CSS:** `color: #dd4c4f; text-decoration: none`

**Text style:** `body` — bearsans 400 · 16px/1.7

**Observed:** No chip or button backing. Social links use Lead sizing; quotation attribution uses Quote body sizing.

**Transfer:** Keep repeated destinations typographic instead of turning each into a filled button.

### Platform selector

**Use:** Opening choice of product format or device.

**CSS:** `display: flex; align-items: center; padding: 19.2px`

**Text style:** `selector` — bearsans 400 · 24px/1.133

**Observed:** Three choices form one centered row with small device silhouettes; selected choice has a hand-drawn aqua underline and short rays, inactive choices are gray.

**Transfer:** Use equivalent meaningful modes for the new product, retaining the informal selected marking.

### Demonstration frame

**Use:** Central wide product demonstration.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 8px; max-width: 1056px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.12) 0px 13px 34px 0px`

**Observed:** Placed beneath a centered statement and subtitle with a 64px gap.

**Transfer:** Show a complete useful task or a polished still of it.

### Capability card

**Use:** Secondary benefits with an illustrative product scene.

**CSS:** `background: #f3f5f7; border-radius: 40px; display: flex; flex-direction: column; overflow: hidden`

**Text style:** `card-heading` — bearsansheadline 400 · 30.4px/1.1

**Observed:** Text is inset 40px; media occupies the lower portion. Cards form staggered columns rather than a uniform row.

**Transfer:** Dedicate each card to one concrete task.

### Quote ribbon

**Use:** Left marker for unboxed testimonial copy.

**CSS:** `position: absolute; width: 4px; background: #dd4c4f; border-radius: 16px`

**Observed:** The ribbon follows the quote text height; a bold short title, regular quote and coral attribution are indented about 20px to its right.

**Transfer:** Keep the quote on the page canvas instead of adding a card.

### Email field

**Use:** Single-field newsletter signup.

**CSS:** `background: #ffffff; border: 1px solid #d9d9d9; border-radius: 8.8px; padding: 0px 17.6px; max-width: 387.2px; height: 44px`

**Observed:** A wide field shares a centered row with Primary button, separated by about 9px.

**Transfer:** Keep signup visually lighter than the main product scene.

### Footer link group

**Use:** Final site navigation.

**CSS:** `color: #444444; line-height: 28.8px`

**Text style:** `footer-link` — bearsans 400 · 16px/1.8

**Observed:** Four groups have small Footer heading labels; links are plain charcoal text. A tiny maker symbol and subdued copyright are centered 96px below the groups.

**Transfer:** Use concise functional destinations, leaving the footer white.

### Raised plan

**Only for:** pricing comparisons

**Use:** Emphasized paid option beside an unboxed baseline.

**CSS:** `background: #ffffff; border-radius: 40px; padding: 64px 16px; box-shadow: rgba(0, 0, 0, 0.12) 0px 13px 34px 0px`

**Text style:** `heading` — bearsansheadline 400 · 41.6px/1.1

**Observed:** Title and colored tier badge precede aligned check rows; the trial statement and two billing prices sit at the bottom. A hand-drawn lime oval highlights the annual option.

**Transfer:** Emphasize one option through elevation rather than a dark inverse card.

### Art preview stack

**Only for:** download collections

**Use:** Preview the same artwork in several aspect ratios.

**CSS:** `border-radius: 16px; box-shadow: rgba(34, 113, 140, 0.3) 0px 13px 34px 0px; max-width: 380px`

**Observed:** A tall 380px by 670px front panel overlaps landscape and smaller panels behind it. Rear panels can be slightly transparent.

**Transfer:** Use real aspect-ratio variations rather than drawing hardware bezels.

## Imagery and graphics

### Floating interface scenes

**Use:** Opening object and capability demonstrations.

**Observed:** The opening has one broad desktop interface with a soft shadow; later scenes use detached editor, sidebar and task panels layered at slight angles. Most panels are white; some dark or warm theme variants appear only inside the product scene. Content is legible and functional, not abstract UI decoration.

**Transfer:** Show the new product doing a recognizable task. If no interface exists, construct a convincing result sheet with a title, content and a few restrained controls, keeping the same layered paper treatment.

### Pastel organic shapes

**Use:** Signature backing for feature chapters.

**Observed:** Large irregular flat shapes in pale aqua, muted purple, sage and yellow sit behind the product panels, often cut off by the viewport edge. Their area is substantial locally but the text and most surrounding page remain white.

**Transfer:** Pair each chapter with a related heading color and one quiet organic silhouette.

**Build:** Use an absolutely positioned SVG with an asymmetric closed path made from 5–7 broad cubic curves. Size it roughly 900px across behind a 500–600px panel cluster; let 200px or more extend past the page edge. Use flat rgba(68,162,170,0.5), rgba(110,57,122,0.62), rgba(43,100,81,0.48) or rgba(226,188,32,0.7) on white. Do not blur or add a gradient.

### Pencil world and handwritten accents

**Use:** Signature humanizing layer around demonstrations and a broad conversion breathing space.

**Observed:** Near-white line art depicts little stars, planets, landscape contours, trees and a friendly character; it surrounds rather than competes with text. A large landscape stretches around a compact dark download badge. The footer includes similarly faint illustrations at its edges. The opening underline is aqua and the annual-price highlight is a loose lime oval.

**Transfer:** Create original small motifs relevant to the product, plus a simple scenic illustration around one conversion. Preserve the pencil-light contrast and whimsical scale rather than replacing it with heavy brand illustration.

**Build:** Draw SVG paths with 1–2px rounded strokes in rgba(68,68,68,0.1), minimal rgba(68,68,68,0.025) fills and no shadow. Across a 1200px-wide scene, layer hills, sparse objects and one friendly focal silhouette, leaving open space for the action. For the opening, add a slightly uneven 4px aqua underline and three short rays. For a highlighted price, use two imperfect overlapping lime ellipses with low-opacity 5px strokes.

### Illustrated collection art

**Only for:** download collections

**Use:** Primary media in each resource entry.

**Observed:** Colorful flat storybook scenes fill tall and landscape rounded panels. Palettes vary dramatically by entry, including night blue, spring green, turquoise, purple and festive red; the surrounding page remains white. Three aspect ratios overlap without device chrome.

**Transfer:** Give each resource its own coherent palette and original scene, then repeat it in format-specific previews. Keep saturated color inside the art rather than tinting the whole page.

### Icons

**Observed:** Small device silhouettes accompany platform choices and download categories; checks appear at about 18px in pricing rows. Feature symbols are compact coral filled shapes around 18–26px. The site mark is a simple colored silhouette rather than an outlined icon tile.

**Transfer:** Choose a consistent small silhouette family for device or format labels and restrained checks for comparisons. Avoid placing every symbol inside a colored square.

## Section recipes

How recurring sections are built.

### First screen: Centered product invitation

**Observed:** White Paper canvas behind a fixed 64px navigation. The centered headline starts around 208px from the page top and spans roughly half the desktop width at 51.2px/1.1, with its final emotional word underlined in aqua. A 25.6px availability line sits immediately beneath it, followed by Platform selector and a monochrome marketplace download badge. The interface image box is 1258px wide including its generous internal margins; the visible panel spans roughly three quarters of the viewport. In the first 900px the title, availability, choices, action and upper portion of the interface are visible; the rest of the interface and proof marks continue below. Layers are white canvas, faint hand-drawn accents, then interface and its shadow.

**Transfer:** Keep the centered promise and a large recognizable product/result object. Without a ready interface, compose one polished working-result panel and a compact custom download or start action. Collection pages use a shorter centered title and muted lead beginning around 144px, then let the first illustrated entry enter the first screen.

**Avoid:** Do not replace this with a giant left-aligned typographic poster, a full-bleed colored hero or a wall of generic dashboard tiles.

**Text style:** `display` — bearsansheadline 400 · 51.2px/1.1

### Centered heading pair and demo

**Observed:** A Display statement is paired with a Lead subtitle capped at 582.4px; Demonstration frame follows after 64px. Small pale drawings surround the group without interrupting its center alignment.

**Transfer:** Use for a product thesis followed by one substantial working demonstration.

**Text style:** `display` — bearsansheadline 400 · 51.2px/1.1

### Alternating capability scene

**Observed:** Within Capability wrapper, a roughly 399px text block holds a colored Heading and three compact Body bullets, capped at 352px. Floating interface scenes occupy the other side over Organic chapter backing; the next scene reverses sides. About 160px separates the narrative blocks.

**Transfer:** Choose one concrete benefit for each scene. Use color to distinguish chapters while keeping reading areas on white.

**Text style:** `heading` — bearsansheadline 400 · 41.6px/1.1

### Secondary capability mosaic

**Observed:** A centered Display statement introduces staggered columns combining short text benefits and Capability cards. Cards have Card heading titles, 40px text insets and large task demonstrations below.

**Transfer:** Use for smaller useful details after the larger scene-led benefits, not as a substitute for all narrative chapters.

### Community proof

**Observed:** Centered Display heading and coral social links precede a two-column testimonial grid with 80px column and 64px row gaps. Quote ribbon marks each unboxed story; bold short titles introduce regular copy and attribution.

**Transfer:** Use authentic short customer stories, keeping them compact enough to preserve the open page.

### Newsletter and quiet ending

**Observed:** A centered Display heading and muted Lead invite subscription. The form follows after 48px, with Email field and Primary button in one row. The newsletter has 160px of separation around it; Footer link group forms four columns and the tiny centered maker credit closes the page. Faint drawings decorate the lower edges.

**Transfer:** End marketing pages with a low-pressure ongoing relationship, then functional navigation rather than a second oversized sales billboard.

### Gentle price comparison

**Only for:** pricing comparisons

**Observed:** Centered Display heading and muted Lead precede two columns. The free baseline remains unboxed; Raised plan has more width and elevation. Rows use subtle cool-paper rules, checked availability and gray struck-through omissions. Prices are 40px regular sans, with a hand-drawn lime annual highlight; a compact download badge follows above the faint illustrated landscape.

**Transfer:** Explain a genuine commercial distinction with a small amount of pricing emphasis rather than a loud promotion.

### Alternating resource entry

**Only for:** download collections

**Observed:** A Heading title, Body paragraph and two-column device download list sit beside Art preview stack. Desktop and tablet categories share one column while the longer phone list uses the other. Entries alternate sides and have 304px bottom separation. A single centered Primary button follows the final entry, then the standard footer after 64px.

**Transfer:** Use for downloadable assets or resource catalogs; substitute relevant format categories while keeping plain coral text links.

**Text style:** `heading` — bearsansheadline 400 · 41.6px/1.1

## Page flow

**Storyline:** promise → tangible product or resource preview → useful capability chapters → decision support → friendly continuation → functional footer

### Flagship product marketing landing page

1. **Promise** — Centered emotional utility headline, platform choices and compact download action over a large interface object.
2. **Credibility** — Small pale award marks followed by a centered product thesis and wide demonstration.
3. **Capability chapters** — Alternating text and layered interface scenes on irregular pastel backing, followed by a smaller-feature mosaic.
4. **Decision support** — Unboxed baseline against a raised paid plan and understated currency figures.
5. **Conversion** — Compact marketplace badge placed inside a very faint illustrated landscape.
6. **Social proof** — Community destinations and unboxed ribbon-marked customer stories.
7. **Ongoing relationship** — Friendly newsletter signup followed by four functional footer columns and a tiny maker credit.

**Transfer:** Borrow the balance of large product scenes, concise explanatory passages and friendly proof; choose the number and placement of chapters to suit the new product.

### Illustrated download and resource collection

1. **Orientation** — Short centered title and friendly muted lead with faint edge doodles.
2. **Resource demonstration** — Repeated alternating entries pair a named illustrated scene with a paragraph, format-grouped links and overlapping aspect-ratio previews.
3. **Continuation** — One centered coral action extends the collection.
4. **Functional ending** — The shared four-column footer ends with a small centered maker credit, without a newsletter or large closing pitch.

**Transfer:** Use this variant for asset or template collections, allowing each item its own artwork palette while maintaining the same white frame and coral link system.

## Writing

Warm, capable and gently playful. Benefits are concrete and simple; a small joke or cozy metaphor softens the technical explanation without turning the whole page into comedy.

**Do not copy:** Do not reuse Bear, Shiny Frog, mascot artwork, award claims, product capabilities, platform availability, prices, testimonials or licensed cultural references as claims or assets for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work. Use we for honest commitments or reassurance, and refer to the product by name sparingly.
- **Rhythm:** Main headlines usually use two to five words; the opening combines a concrete category with an emotional promise. Support lines are one or two sentences, and benefit bullets explain one outcome apiece.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the useful category and end with a simple feeling. | 4–7 words | “Markdown notes you’ll love” |
| Capability heading | A short verb phrase or adjective plus a concrete benefit. | 2–5 words | “Write naturally”<br>“Organize easily”<br>“Resize and crop images” |
| Supporting line | Plain-language utility with a reassuring human note. | 15–30 words | “[Brand] is a beautiful, powerfully simple Markdown note taking app to capture, write, and organize your life.” |
| Action | Direct verb or continuation label without urgency. | 1–3 words | “Subscribe”<br>“More wallpapers” |
| Reassurance | Brief practical promise with one light punchline. | Two short fragments after the explanation | “No spam, ever. Maybe bear hugs, though.” |
| Collection description | Describe a small scene and invite the reader into it; a topical emoji can punctuate the ending. | 2–4 sentences | “Happy Halloween! [Brand] is all dressed up and ready to scare. Update your Home Screen and celebrate the spooky season in style.” |

**Words and phrasing to use:** beautiful; simple; naturally; your way; cozy; keep your ideas; write; organize; if you want

**Avoid:** revolutionary; disruptive; 10x; unlock your potential; limited time only; enterprise-grade everything

**Rules:**

- Favor familiar verbs and recognizable tasks over abstract capability nouns.
- Make reassurance specific: explain what happens to the reader's work rather than merely saying trustworthy.
- Reserve playful puns and emoji for friendly support or collection copy; keep detailed product bullets clear.
- Describe premium features and prices calmly; no countdown, scarcity or aggressive upsell language.

## Do's and Don'ts

### Do

- Keep core titles at 51.2px or 41.6px with 1.1 line height and normal tracking.
- Use the 960px wrapper with 32px side insets for ordinary centered sections.
- Let 22.4px muted leads remain within a 582.4px measure.
- Preserve the distinction between 16px media corners and 40px secondary card corners.
- Keep interface paper shadows broad and restrained at 0px 13px 34px with 0.12 black alpha.
- Use coral for short links, compact buttons and 4px testimonial markers.
- Retain a hand-drawn marking and a faint illustrated breathing space in the new design.
- Keep the final navigation in four plain text groups with 28.8px link line height.

### Don't

- Do not tighten headline tracking or replace the sturdy rounded headline cut with an ultra-heavy condensed face.
- Do not turn the coral accent into a full-width red sales band; most of the page is white.
- Do not use pill-shaped controls for the standard action; its corners are 8px.
- Do not make every benefit a bordered card; large chapters rely on free-floating scenes.
- Do not add dark inverse pricing panels; emphasis comes from a white raised surface.
- Do not turn the faint pencil illustrations into high-contrast black cartoon art.
- Do not color the surrounding collection layout to match each artwork; saturation stays inside previews.
- Do not give footer links the coral treatment of download lists; the footer is charcoal and understated.

## Motion and responsive

### Motion

**Observed:**

- No action or surface transitions and no keyframe animations are established. Product demonstrations include video or animated media; the navigation remains fixed.

**Transfer:**

- Let task demonstrations communicate motion within the media frame while keeping surrounding copy and the paper composition stable.

**Unknown:**

- Timing, easing, selector behavior and scroll-triggered behavior are not established.

### Responsive

**Observed:**

- The measured composition is desktop. Declared width breakpoints span 368px through 1280px, including 480px, 640px and 960px.

**Transfer:**

- As adaptation guidance, stack the text and its paper scene on narrow screens, keeping organic shapes behind media rather than under readable copy.
- Keep the first-screen promise, format choice and action before the product object; reflow download categories instead of shrinking all links.
- Reduce testimonial and footer column counts while preserving their unboxed treatment.

**Unknown:**

- Actual mobile headline sizes, navigation collapse, art stacking and breakpoint-specific spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
