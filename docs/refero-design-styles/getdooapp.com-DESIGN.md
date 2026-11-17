# Doo — pastel cards, floating devices

## Overview

An airy, white product showcase with a friendly geometric sans, charcoal headlines and soft gray explanations. Pastel cards and miniature illustrations soften the realism of oversized device renders, while violet actions provide a small, decisive point of contrast. It suits approachable software and personal tools that benefit from showing the experience rather than making grand claims.

### Essentials

- Headlines sound conversational and look unforced: Avenir Next at 65px/1.2, weight 400, -0.04em tracking for the opening; 39px/1.2 with the same tracking for chapters.
- The opening is a centered promise above a product stage: a 700px two-line headline, 19.5px supporting line, a single violet 52px-high pill and the top of a large device composition entering within the first 900px.
- Color is concentrated in the things being demonstrated: white dominates the page, charcoal and gray carry the copy, and violet is reserved for primary actions; pale blue and gray back selected illustration cards rather than entire alternating bands.
- Product imagery has exhibition scale: realistic black-and-metal devices float or lean on white, sometimes extending beyond the content width; use a polished interface-in-frame composition when physical product renders are unavailable.
- A playful process sculpture turns behavior into pictures: 337×500px panels with 30px corners, a typed phrase, a miniature grid and an enlarged completion motif, followed by understated 16.3px captions. Carry this device into new content as a simple illustrated transformation.
- Buttons are small words inside long curves: 13px/1 semibold labels, 39px corner radii, a filled violet primary action and 2px pale outlined secondary actions.
- The close returns the product to everyday life: a centered 39px two-line invitation and paired outlined actions above a broad workspace photograph, followed by a tiny centered mark, three links and gray ownership text. Use a convincing in-context product scene if a workspace is not relevant.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet | `#5141b1` | `--color-action` | action | Solid primary conversion pills; do not spread this saturation into large page bands. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender wash | `#e8ecfb` | `--color-promo` | surface | Contained closing promotion and text selection; the promotion is limited to capability catalogs. |
| Ice blue | `#e7efff` | `--color-process-blue` | surface | An illustrated process panel, not a general page background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#111111` | `--color-strong` | text, link | Small feature titles, demonstration text and hover emphasis. |
| Charcoal | `#383938` | `--color-ink` | text | Headlines, active navigation and footer links. |
| Warm gray | `#6e6d7a` | `--color-muted` | text, link | Body copy, eyebrows, inactive navigation and outlined action labels. |
| Pale edge | `#edeef3` | `--color-rule` | border | Section hairlines and the 2px outline on secondary buttons. |
| Chalk gray | `#f7f7f7` | `--color-process-gray` | surface | Soft backing for miniature process artwork. |
| White | `#ffffff` | `--color-canvas` | background, text | The continuous page canvas and labels on filled actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| capability catalogs | Aside gray | `#b2b2b2` | `--color-aside` | text | The parenthetical second line of a catalog opening. |
| capability catalogs | Tag gray | `#f5f5f5` | `--color-tag` | surface | Small platform badges beneath capability descriptions. |

## Typography

- **Avenir Next** — All marketing text, headings, actions and captions. Rounded geometric-humanist sans with an open, friendly regular cut; semibold is reserved for small functional emphasis. If unavailable, use **Nunito Sans**. Use weights 400 and 600; retain the tight display tracking. Font stack: "Avenir Next", "Nunito Sans", -apple-system, system-ui, "Helvetica Neue", Helvetica, "Gill Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Avenir Next | 400 | 65px | 1.2 | -0.04em | Centered two-line opening promise. |
| heading | Avenir Next | 400 | 39px | 1.2 | -0.04em | Section chapters, two-line feature summaries and the closing invitation. |
| process-text | Avenir Next | 400 | 29.3px | 1 | normal | A short typed phrase within process artwork. |
| lead | Avenir Next | 400 | 19.5px | 1.8 | normal | Opening support and main feature explanations. |
| feature-title | Avenir Next | 600 | 16.9px | 1.8 | normal | Compact title above a description in the illustrated feature list. |
| body | Avenir Next | 400 | 16.3px | 1.8 | normal | Captions, quotations, short feature descriptions and footer text. |
| eyebrow | Avenir Next | 400 | 13px | 1 | 0.1em, uppercase | Small chapter labels immediately above a heading. |
| action | Avenir Next | 600 | 13px | 1 | normal | Both filled and outlined pill labels. |
| navigation | Avenir Next | 400 | 13px | 1.8 | normal | Small top navigation links. |
| navigation-active | Avenir Next | 600 | 13px | 1.8 | normal | Current top navigation link, differentiated by weight and charcoal rather than an underline. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| capability catalogs | promo-heading | Avenir Next | 400 | 32.5px | 1.3 | -0.01em | Centered question in the contained closing promotion. |
| capability catalogs | catalog-title | Avenir Next | 600 | 22.8px | 1.8 | normal | Individual capability names in a long-form catalog. |
| capability catalogs | platform-label | Avenir Next | 600 | 12.2px | 1.8 | normal | Small platform identifiers beneath relevant capability copy. |

**Notes:**

- Display and section headings share weight 400 and -0.04em tracking; their distinction is scale, not boldness.
- Body and lead text share a relaxed 1.8 line height; the wider leading contrasts with the compact 1.2 heading rhythm.
- Use natural sentence case everywhere except the 13px tracked chapter eyebrows. Keep semibold for actions and small item titles.

## Layout

**Density:** Airy: narrow text islands sit above or beside much larger product scenes, with long stretches of white separating chapters.

### Spacing

| Value | Use |
| --- | --- |
| 16.3px | Catalog paragraph-to-media and badge-group spacing. |
| 19.5px | Heading-to-support margin and eyebrow-to-heading margin. |
| 26px | Navigation padding, footer link-group margins and secondary action horizontal padding. |
| 32.5px | Illustration-panel-to-caption spacing. |
| 48.8px | Spacing beneath compact illustrated feature rows. |
| 52px | Support-to-action or heading-to-secondary-action separation. |
| 78px | Chapter heading to process artwork and actions to closing photograph. |
| 104px | Opening text block bottom space, major media separation and footer bottom padding. |
| 130px | Major section vertical padding and chapter starts. |

### Containers and grids

- **outer stage**: max width 1440px · side padding 86px. Centered wide stage; at a 1440px viewport the visible inner width is 1267px. Broad product scenes and section rules use this outer alignment.
- **inset content**: max width 1050px. Proof strips, process panels and two-column feature layouts sit one inset inside the outer stage.
- **chapter text**: max width 460px. Left-aligned prose is inset another level, beginning about 303px from the viewport edge at desktop.
- **opening text**: max width 700px. Centered promise and supporting line.
- **process grid**: 3 columns · gap 20px. Three equal portrait illustration panels, each 337px wide, with separate centered captions.
- **split chapter**: 2 columns · gap 42px. Two approximately 504px columns: chapter title or invitation on the left and a stacked illustrated list on the right.
- **catalog promotion** (only for capability catalogs): max width 800px. Centered contained promotion rather than a full-width colored band.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action pills | 39px |
|  | process panels | 30px |
|  | media panels | 20px |
| capability catalogs | platform badges | 4px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Continuous light background across navigation, feature chapters and footer.

**CSS:** `background: #ffffff`

**Observed:** Sections are distinguished by space and occasional hairlines rather than alternating background fills.

**Transfer:** Let the product scenes provide most of the color.

#### Ruled chapter · level 0

**Use:** Start of substantial product chapters.

**CSS:** `border-top: 1px solid #edeef3; padding-top: 130px`

**Observed:** The rule aligns with the outer stage, while text sits further inset.

**Transfer:** Separate changes in narrative scale without boxing the whole section.

#### Process panel · level 1

**Use:** Portrait-format artwork backing.

**CSS:** `background: #e7efff; border-radius: 30px; overflow: hidden`

**Observed:** A 337×500px pale-blue panel accompanies a gray-backed variant and a full-bleed illustrated variant. No cast card shadows.

**Transfer:** Treat these as illustration stages, not interactive dashboard cards.

#### Miniature artwork backing · level 1

**Use:** Neutral variant within the process illustration group.

**CSS:** `background: #f7f7f7; border-radius: 30px; padding: 30px; overflow: hidden`

**Observed:** A centered miniature grid of softly rounded tiles sits within the larger backing.

**Transfer:** Render a small abstraction of the product's choices or states.

#### Contained promotion · level 1

**Only for:** capability catalogs

**Use:** Closing conversion panel after a long capability list.

**CSS:** `background: #e8ecfb; border-radius: 20px; max-width: 800px; padding: 130px 0; text-align: center`

**Observed:** The 429px-high panel has abundant internal breathing room and sits within a white section with 130px padding above and below.

**Transfer:** Use one brief question, one support line and the Primary button.

## Components

### Top navigation

**Use:** Lightweight site orientation.

**CSS:** `position: relative; padding: 26px 0; background: #ffffff`

**Text style:** `navigation` — Avenir Next 400 · 13px/1.8

**Observed:** A tiny 60×20px image mark is left aligned on the outer stage. Four plain links form a right-aligned row, with about 39px separation. The current link uses navigation-active.

**Transfer:** Keep the mark small and the destination set short; use the new product's own mark.

### Primary button

**Use:** One decisive conversion action in the opening and catalog close.

**CSS:** `position: relative; background: #5141b1; color: #ffffff; border-radius: 39px; padding: 19.5px 39px; border: 0px; text-align: center`

**Text style:** `action` — Avenir Next 600 · 13px/1

**Observed:** A single centered label, without an icon. The fill is carried by a rounded layer behind the text; the action is 52px high.

**States:** Declared: hover removes text decoration, retains white text and makes the border transparent.

**Transfer:** Use a direct verb appropriate to the next step.

### Secondary button

**Use:** Lower-intensity navigation and paired platform choices.

**CSS:** `position: relative; background: transparent; color: #6e6d7a; border: 2px solid #edeef3; border-radius: 39px; padding: 13px 26px; box-shadow: none`

**Text style:** `action` — Avenir Next 600 · 13px/1

**Observed:** The outline encloses a 43px-high compact pill. Closing choices sit side by side; a feature-summary link sits below its heading.

**States:** Declared: hover removes text decoration, changes text and border to #383938 and keeps box-shadow none.

### Chapter heading

**Use:** Introduce one product benefit before its demonstration.

**CSS:** `max-width: 460px; color: #383938`

**Text style:** `heading` — Avenir Next 400 · 39px/1.2 · tracking -0.04em

**Observed:** A tracked Eyebrow sits above the regular-weight heading. A lead paragraph follows, with no decorative underline or icon appended.

**Transfer:** Use a short benefit headline, then explain a concrete mechanism.

### Process illustration card

**Use:** Make a simple product process legible and playful.

**CSS:** `width: 337px; height: 500px; background: #e7efff; border-radius: 30px; position: relative; overflow: hidden; margin-bottom: 32.5px`

**Text style:** `process-text` — Avenir Next 400 · 29.3px/1

**Observed:** A short typed phrase is vertically centered. Companion panels replace the phrase with miniature tiles and a large success motif. Captions sit outside the colored panel in body type.

**Transfer:** Keep the illustrated change readable without requiring detailed UI knowledge.

### Illustrated feature row

**Use:** Compact secondary capability summary.

**CSS:** `position: relative; padding-left: 90px; margin-bottom: 48.8px`

**Text style:** `feature-title` — Avenir Next 600 · 16.9px/1.8

**Observed:** A 60×57px pastel-backed outlined icon sits to the left. A near-black semibold title and muted body description occupy the right, inside a 504px-wide column.

**Transfer:** Use one recognizable object per icon and one short explanation per item.

### Centered footer

**Use:** A small, conclusive site ending.

**CSS:** `background: #ffffff; text-align: center; padding-bottom: 104px`

**Text style:** `body` — Avenir Next 400 · 16.3px/1.8

**Observed:** A 60×20px mark sits above a three-link row with 26px vertical group margins. A muted ownership line finishes the page. There are no dense columns, newsletter form or dark band.

**Transfer:** Reduce the ending to identity, key destinations and ownership.

### Catalog item

**Only for:** capability catalogs

**Use:** Explain individual capabilities without card chrome.

**CSS:** `padding-bottom: 16.3px; margin-bottom: 16.3px; width: 504px`

**Text style:** `catalog-title` — Avenir Next 600 · 22.8px/1.8

**Observed:** A semibold name, a muted paragraph, optional platform badges and a Media preview form a vertical entry. Entries without media remain simple text blocks.

**Transfer:** Group capabilities by the reader's task, not by internal implementation.

### Platform badge

**Only for:** capability catalogs

**Use:** Indicate availability beneath a capability description.

**CSS:** `background: #f5f5f5; color: #383938; border-radius: 4px; padding: 2.4px 9.8px`

**Text style:** `platform-label` — Avenir Next 600 · 12.2px/1.8

**Observed:** Small solid-neutral labels appear in a row with 5px separation, above the relevant preview. They are not pill-shaped buttons.

### Media preview

**Only for:** capability catalogs

**Use:** Show a precise interaction in the long-form feature column.

**CSS:** `width: 504px; height: 332px; border-radius: 20px; margin-top: 16.3px; overflow: hidden`

**Observed:** A device detail is embedded in a light neutral image backing; the device is often intentionally clipped by the image boundaries. The backing belongs to the artwork rather than a raised UI card.

**Transfer:** Use a consistent landscape frame and show only the part of the interface needed to explain the item.

## Imagery and graphics

### Floating product devices

**Use:** Opening stage and expansive capability demonstrations.

**Observed:** Realistic silver desktop hardware and black-edged phones carry bright but mostly pale interfaces on a seamless white backing. Some scenes are straight-on multi-device groups; others use large oblique phones, overlapping pairs or staggered vertical devices. Soft contact shadows anchor physical objects without turning the page into a shadowed card system. Media commonly occupies more area than the preceding text.

**Transfer:** Use your own interface in realistic restrained hardware. Without high-quality 3D, use a crisp flat device frame with one subtle contact shadow and a generous white surround; preserve the oversized composition.

### Pastel process sculpture

**Use:** Signature behavior-to-picture demonstration.

**Observed:** A typed phrase on pale blue leads into a miniature four-column tile matrix on chalk gray, then an oversized tilted field of mint tiles and a circular check. Pastel violet, yellow and mint appear as small selected cells. Portrait panels carry the visual weight; gray captions stay below them.

**Transfer:** Abstract a real transformation into input, selection and result. Preserve the tiny-to-oversized shift even when the product has no card metaphor.

**Build:** Use three 337×500px overflow-hidden stages with 30px corners. Center a short phrase in the first. In the second, draw a 236×316px four-column SVG matrix of rounded white rectangles, changing only a few cells to translucent mint, violet and yellow. In the third, enlarge the same matrix, rotate it roughly -30deg and clip it to the panel; overlay a mint-green circle and a thick white check. Use rgba(120,240,175,0.4), rgba(150,125,230,0.4) and rgba(235,210,85,0.5) for a similarly soft palette rather than saturated blocks.

### Paired conceptual detail

**Use:** A focused reassurance or technical-benefit chapter.

**Observed:** Two nearly square light-gray image panels sit side by side: a tiny tactile object centered in one, a drastically enlarged device detail cut off at the top and right in the other. A lock object and an authentication control demonstrate the small-symbol/large-interface contrast.

**Transfer:** Pair a simple physical metaphor with an actual product detail. Keep the neutral backing and the deliberate difference in scale.

### Everyday product photograph

**Use:** Signature closing scene on a marketing landing page.

**Observed:** A broad 1267×761px rectangular photograph shows a monitor on a wooden desk against large windows. Natural daylight, muted wood and pale walls make the vivid screen the focal point; books, a plant and a cup add lived-in credibility. The image is not rounded or overlaid with text.

**Transfer:** Show the new product convincingly in a calm, naturally lit setting with restrained props. If photography is unavailable, compose a believable product-in-context render with the same broad crop and neutral surroundings.

### Catalog interaction details

**Only for:** capability catalogs

**Use:** Repeated instructional previews.

**Observed:** 504×332px landscape images with 20px corners use a light gray backing and a centered upright device, often clipped to emphasize one screen region. A dark-mode example remains local to its product preview; the surrounding marketing canvas stays white.

**Transfer:** Maintain consistent framing across many features and allow product UI themes to vary only inside the previews.

### Icons

**Observed:** Compact friendly black outlines over irregular pale pastel shapes; 60×57px image assets accompany summary rows. Subjects are simple functional symbols such as a waveform, widgets, a cloud or a book, not an all-purpose dense icon grid.

**Transfer:** Choose recognizable thin outlined symbols with rounded joins and a small translucent pastel patch behind each; align them with the title rather than centering them over the whole paragraph.

## Section recipes

How recurring sections are built.

### First screen: Centered promise and product stage

**Observed:** White canvas behind a small Top navigation, then a centered 700px-wide two-line display heading beginning after 130px of breathing room below the navigation. Its 65px regular letters and tight tracking span about half the viewport. A single muted lead line follows at 19.5px margin; the Primary button follows at 52px. After 104px of space below the text block, a large straight-on desktop device begins the product stage at about 656px down the page. Within the first 900px the full headline, support and action are visible, together with the upper part of the main screen. The rest of the device group and proof sit below the fold. Layers are white canvas, product hardware with soft contact shadow, then readable interface imagery; there is no text over the device.

**Transfer:** Use a short benefit promise over one polished product composition, not a collage of unrelated features. With no device artwork, stage the core interface in a carefully framed large window. A capability catalog opens with the same display scale but replaces the support/action stack with a light-gray parenthetical second line and a multi-device group.

**Avoid:** Do not force the whole product scene above the fold, switch to a left-copy/right-dashboard hero or replace the white stage with a purple gradient.

**Text style:** `display` — Avenir Next 400 · 65px/1.2 · tracking -0.04em

### Quiet proof strip

**Observed:** Three centered quotation columns span the inset content width beneath the opening device group, each pairing a small dark publication mark with muted body text. A separate pair of award images follows with ample white space.

**Transfer:** Use short attributed proof and small visual credentials that the new product can substantiate; maintain the low-contrast typesetting rather than enclosing testimonials in cards.

**Text style:** `body` — Avenir Next 400 · 16.3px/1.8

### Illustrated process

**Observed:** A Ruled chapter starts with Chapter heading, followed 78px later by a three-column process grid. Process illustration cards dominate, with centered body captions below rather than text inside every illustration.

**Transfer:** Explain a meaningful transformation through a small set of visual states. This is a reusable device, not a requirement to mirror a particular product workflow.

**Text style:** `heading` — Avenir Next 400 · 39px/1.2 · tracking -0.04em

### Oversized demonstration chapter

**Observed:** Chapter heading and a lead paragraph form a 460px left-aligned text island, inset from the wide media stage. Large floating devices below may overlap, stagger or extend beyond the stage width; 104px media gaps and 130px section breathing room keep the compositions unhurried.

**Transfer:** Alternate readable explanation with one visually strong demonstration. Let the product's interaction determine the device arrangement instead of using an identical grid for every benefit.

**Text style:** `heading` — Avenir Next 400 · 39px/1.2 · tracking -0.04em

### Reassurance pair

**Observed:** A Ruled chapter and narrow explanation precede Paired conceptual detail imagery. The panels sit on the wide stage and convey both an abstract promise and its concrete interface mechanism.

**Transfer:** Use for a substantiated trust, reliability or control benefit; keep its explanation direct and its imagery simple.

### Feature summary split

**Observed:** A two-line heading and Secondary button occupy the left 504px column while Illustrated feature rows stack in the right column. The list is more compact than the preceding device chapters but remains unboxed.

**Transfer:** Summarize supporting capabilities and provide a route to deeper detail without repeating all the preceding sections.

**Text style:** `heading` — Avenir Next 400 · 39px/1.2 · tracking -0.04em

### Life-size closing invitation

**Observed:** A Ruled chapter shifts back to centered text: a 39px two-line invitation, 52px to paired Secondary buttons, then 78px to Everyday product photograph on the outer stage. The Centered footer follows on white.

**Transfer:** End a marketing page with a concrete next step and an aspirational but believable everyday use scene. Keep the actions outside the photograph.

**Text style:** `heading` — Avenir Next 400 · 39px/1.2 · tracking -0.04em

### Catalog chapter

**Only for:** capability catalogs

**Observed:** A 1px ruled chapter with 130px top and bottom padding uses a broad two-column composition: a regular 39px category heading on the left and a long stack of Catalog items in the right 504px column. Much of the left column remains open as the right side explains details. Media preview frames and Platform badges punctuate the list rather than appearing on every item.

**Transfer:** Use for an exhaustive capability inventory; keep the category label distinct from the semibold individual titles. Do not make the left heading sticky without a reason.

**Text style:** `catalog-title` — Avenir Next 600 · 22.8px/1.8

### Catalog closing promotion

**Only for:** capability catalogs

**Observed:** Contained promotion centers a 32.5px question, a body support line and the Primary button. It is followed by 130px of white section padding and the same Centered footer, rather than the broad lifestyle-image ending.

**Transfer:** After long explanatory content, finish with a short human invitation inside a single pale panel.

**Text style:** `promo-heading` — Avenir Next 400 · 32.5px/1.3 · tracking -0.01em

## Page flow

**Storyline:** benefit promise → tangible product demonstration → confidence and capability explanations → concise next step → minimal identity ending

### A product marketing landing page that makes a simple tool feel desirable and understandable

1. **Promise** — Centered two-line benefit, brief support and a single filled action above oversized devices.
2. **Social proof** — Quiet quotations with small publication marks and a separate visual credential pair.
3. **Product explanation** — Pastel process sculpture followed by spacious benefit chapters and dramatic device compositions.
4. **Reassurance** — Plain-language trust explanation with paired concept/detail artwork.
5. **Capability summary** — Split heading and action beside compact illustrated feature rows.
6. **Closing call** — Centered invitation, paired outlined choices and a broad everyday product photograph.
7. **Identity ending** — Tiny centered mark, three navigation links and ownership text.

**Transfer:** Adapt the number and order of chapters to the new story while preserving the progression from an inviting promise to visible mechanisms and a concrete action.

### A detailed capability catalog that answers practical evaluation questions

1. **Inventory promise** — A two-line display title with a lighter parenthetical aside above a multi-device scene.
2. **Capability chapters** — Ruled two-column chapters pair broad category headings with long right-column lists, platform tags and selective device-detail previews.
3. **Closing call** — A contained lavender panel with a conversational question, support line and filled action.
4. **Identity ending** — The shared centered footer with substantial white breathing room.

**Transfer:** Use this variant when readers need detailed coverage rather than an emotional overview; preserve category structure and consistent media framing.

## Writing

Friendly, confident and practical, with a light conversational wit. Benefits are followed by plain explanations of how the experience works rather than technical posturing.

**Do not copy:** Do not reuse the Doo name or logo, publication marks, awards, testimonials, customer claims, platform compatibility or privacy promises as assets or facts for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; refer to the product by name when explaining behavior. Imperatives are gentle and specific.
- **Rhythm:** Headlines are short benefit phrases, often split into two balanced lines. Paragraphs mix straightforward explanatory sentences with occasional clipped reassurance or a small joke.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a better version of the reader's experience, then attach a small tangible unit of progress. | 8–12 words | “A more productive you, one card at a time” |
| Support | One sentence identifies the product category and the everyday benefit. | 8–14 words | “Get the reminders app made for better habits.” |
| Chapter heading | A compact benefit or action phrase with conversational energy. | 3–7 words | “Swipe your way to success”<br>“Adapts to how you work” |
| Explanation | Describe the mechanism first; end with a short friction-removing reassurance when useful. | 25–45 words | “[Brand] uses a set of custom keyboards to keep controls within reach. Create one-off tasks or future appointments with ease. No interruption. No fuss.” |
| Catalog title | Name the capability plainly, without inventing a slogan. | 2–4 words | “Quick actions”<br>“Custom repeat intervals” |
| Primary action | A direct verb or verb plus destination. | 1–4 words | “Download”<br>“View all features” |
| Closing invitation | A short conversational question or an invitation to experience the outcome. | 4–9 words | “Like what you see?”<br>“Get the app that’s changing productivity” |

**Words and phrasing to use:** simple; made for; your way; keep; pick a few; without; with ease; No fuss.

**Avoid:** revolutionary ecosystem; enterprise-grade disruption; unlock limitless potential; synergize; hyper-optimized

**Rules:**

- Give each benefit a visible mechanism in its supporting paragraph.
- Use familiar everyday examples rather than abstract productivity rhetoric.
- Allow a parenthetical joke or a short reassuring fragment, but do not turn every heading into a pun.
- Keep action labels literal and distinguish choices by destination or platform.

## Do's and Don'ts

### Do

- Set primary headings in regular weight with -0.04em tracking at 65px or 39px.
- Keep explanatory text to a 460px island before letting the device composition expand.
- Use 130px major chapter padding and 1px pale rules for narrative separation.
- Keep action labels at 13px semibold, even when the product scene is enormous.
- Use 30px corners on portrait process panels and 20px on catalog preview frames.
- Place process captions outside their illustration panels with 32.5px separation.
- Use a small black-outline icon with a pastel backing for compact feature summaries.
- Keep the closing photograph broad and unoverlaid, then finish with the centered miniature footer.

### Don't

- Do not turn the 400-weight display hierarchy into bold geometric headline blocks.
- Do not spread violet across full-width section backgrounds; reserve it for decisive small actions.
- Do not add elevated shadows to every content card; the marketing surfaces are flat.
- Do not use the 22.8px semibold catalog title as the default landing-page chapter heading.
- Do not round all media alike: broad lifestyle photography is rectangular while previews have 20px corners.
- Do not enlarge the navigation to match body copy; it stays at 13px rather than 16.3px.
- Do not replace the pale 2px secondary outline with a heavy dark filled button.
- Do not turn the minimal ending into a dark multi-column sitemap.

## Motion and responsive

### Motion

**Observed:**

- Declared preview transitions use opacity 0.2s ease-out and transform 0.2s ease-in-out.
- Declared larger section transitions use transform and opacity 1s ease-in-out.
- Declared plain-link color changes use 150ms ease-in-out; secondary button border and color changes also use 150ms ease-in-out.
- The typed process phrase has an 800ms ease-in-out infinite cursor animation.

**Transfer:**

- Keep movement attached to the product explanation: a blinking insertion cursor and a small shift or reveal of the demonstration artwork, not continuous ambient motion behind the copy.
- Preserve short color/border feedback on small actions without adding card-lift effects.

**Unknown:**

- Full primary-button transition declaration is incomplete; exact animated padding and fill behavior are not specified.
- Scroll trigger positions and complete reveal choreography are unknown.

### Responsive

**Observed:**

- Styles declare width breakpoints at 375px, 414px, 767px, 768px, 1023px, 1024px, 1200px, 1280px and 1440px.

**Transfer:**

- On narrow screens, preserve the centered promise above the product stage, reducing the scene without forcing every device above the fold.
- Stack portrait process panels and split chapters when needed; keep captions attached to their artwork and place category titles before their detailed items.
- Retain deliberate device clipping within artwork frames, but prevent explanatory copy from being clipped.

**Unknown:**

- Exact mobile sizes, navigation collapse behavior and breakpoint-specific arrangements are not established.
- No viewport-relative type or spacing formula is established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
