# Counterprint — chromatic objects, blunt type

## Overview

An image-led editorial shopfront with the directness of a printed catalogue. White space and dark Helvetica give saturated physical objects room to speak, with dense product shelves balanced by oversized plainspoken statements. It suits design-conscious products, collections and cultural publishing, pairing tactile photography with deliberately modest interface furniture.

### Essentials

- The opening is a photographic diptych rather than a sales headline: two 705px square images below an 83px masthead, separated by 7.5px and captioned in 15px Helvetica. Preserve the two-image encounter; use staged product artifacts when no campaign photography exists.
- Headlines speak with the blunt weight of a catalogue manifesto: Helvetica 700 at 63.1px/1 with -0.025em tracking for the large statement; ordinary section headings stay at 20px/1 with the same tracking.
- The interface stays almost entirely monochrome: #ffffff canvas and #1c1c1c text and edges across every section. Saturated red, blue, green and yellow occupy the photographs, not decorative page bands.
- Actions are tiny outlined capsules, not oversized conversion blocks: 1px ink borders, 9999px radius, 3.8px by 7.5px padding and 15px/18px regular text, about 28px high.
- Objects form a tightly spaced visual inventory: six columns of 230px square media or four columns of 349px square media, with 7.5px horizontal gaps, unboxed captions and prices directly below.
- Tactility comes from the images, not the UI: hard rectangular media edges, pale studio backings, visible paper thickness and soft photographic shadows; no raised interface cards. A full-width bold statement interrupts the shelves as an essential second register.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hover green | `#4fff99` | `--color-interaction` | action, text | Text-only hover accent on outline actions; the background stays white. Never use it as a resting page fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, surface | Continuous page, section and control background; white gutters separate the photography. |
| Charcoal ink | `#1c1c1c` | `--color-ink` | text, border, action, link | All interface lettering, outline controls and line icons. |

## Typography

- **Helvetica** — All live headings, captions, prices, navigation and body copy. Neutral neo-grotesk; regular utilitarian labels against tightly tracked bold statements. If unavailable, use **Arimo**. Use 400 and 700; preserve Helvetica-like widths, compact line heights and negative tracking on bold roles. Font stack: "Helvetica", "Arimo", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Helvetica | 700 | 63.1px | 1 | -0.025em | Large editorial statement spanning nearly the full content width, rather than an obligatory opening headline. |
| heading | Helvetica | 700 | 20px | 1 | -0.025em | Section headings, paired with a small action or sitting above brief explanatory copy. |
| body | Helvetica | 400 | 15px | 1.2 | normal | Body text, product titles and prices, image captions, dates, actions and utility links. |
| small-heading | Helvetica | 700 | 15px | 1.2 | -0.025em | Compact footer group labels. |

**Notes:**

- Use only regular and bold for the live interface. Large and small bold type share -0.025em tracking; regular text keeps normal tracking.
- The opening has captions, not a superimposed display headline. Graphic lettering printed on photographed objects is separate from the live type hierarchy.
- Titles and prices have equal size and weight; separate them with a line break rather than a new typographic tier.

## Layout

**Density:** Compact shelves and near-edge imagery alternate with open white statement and feature sections.

### Spacing

**Spacing system:**

- **step** 7.5px — Horizontal media gutters and caption offsets; 15px is two steps, 22.5px is three. Smaller control padding uses a half-step.

| Value | Use |
| --- | --- |
| 3.8px | Vertical button and input padding; newsletter control gap. |
| 7.5px | Horizontal media gutters, caption top margin and horizontal control padding. |
| 11.3px | Left and right page inset. |
| 15px (2 × 7.5px) | Product grid row gap and masthead top and bottom padding. |
| 18.8px | Masthead icon spacing. |
| 22.5px (3 × 7.5px) | Structural column gaps in split content and footer layouts. |
| 28.1px | Section top and bottom padding and heading-row bottom margin. |
| 30px (4 × 7.5px) | Space before the action in a split promotional feature. |

### Containers and grids

- **edge-to-edge wrapper**: side padding 11.3px. Fluid full-width content with narrow matching left and right insets; no centered narrow max-width shell.
- **product shelf**: 6 columns · gap 7.5px · side padding 11.3px. Six equal desktop columns; 15px row gaps. Images are about 230px square at 1440px.
- **editorial shelf**: 4 columns · gap 7.5px · side padding 11.3px. Four equal columns with 349px square images at 1440px, for editorial stories or larger product displays.
- **opening diptych**: 2 columns · gap 7.5px · side padding 11.3px. Two equal 705px square photographs with captions outside the image.
- **split feature**: 2 columns · gap 22.5px · side padding 11.3px. Two equal 698px columns at 1440px: a square photograph on the left and top-aligned text on the right.

## Corner radius

| Element | Radius |
| --- | --- |
| action capsule | 9999px (pill) |
| email field | 15px |
| media edges | 0px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Continuous foundation for every section.

**CSS:** `background: #ffffff; color: #1c1c1c`

**Observed:** Section boundaries are made with space rather than contrasting fills or rules.

**Transfer:** Let the media establish local color and texture while the page remains white.

#### Unboxed tile · level 0

**Use:** Product and editorial media with labels outside the image.

**CSS:** `background: #ffffff; border-radius: 0px; box-shadow: none`

**Observed:** Pale studio backgrounds belong to the photographs; they are not rounded UI cards. The text sits on the page canvas below.

**Transfer:** Keep image backing inside the media asset, with no surrounding frame or raised panel.

## Components

### Masthead

**Use:** Compact brand anchor and utility navigation above the opening media.

**CSS:** `background: #ffffff; padding: 15px 11.3px; color: #1c1c1c`

**Observed:** A small black dotted mark occupies an 80px by 53px slot on the left. Menu, search and cart are grouped on the far right as 23px line icons with 18.8px gaps. The complete row is 83px tall.

**Transfer:** Use a compact monochrome identity in the same visual footprint; keep utility actions icon-only with accessible names.

### Outline action

**Use:** Section-level browsing actions and newsletter submission.

**CSS:** `color: #1c1c1c; background: #ffffff; border: 1px solid #1c1c1c; border-radius: 9999px; padding: 3.8px 7.5px`

**Text style:** `body` — Helvetica 400 · 15px/1.2

**Observed:** Content-sized capsules sit at the far edge of heading rows, below short feature copy, or beside an email field. All actions use the same understated treatment.

**States:** Declared: hover background white and text rgb(79 255 153 / 1); focus-visible ink outline, 1.5px wide with 3px offset.

**Transfer:** Use short action labels and preserve the approximately 28px overall height rather than increasing visual prominence.

### Section heading row

**Use:** Introduce a product or editorial shelf.

**CSS:** `display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 15px; padding: 0px 11.3px; margin-bottom: 28.1px`

**Text style:** `heading` — Helvetica 700 · 20px/1 · tracking -0.025em

**Observed:** A bold left-aligned heading is balanced by an Outline action aligned to the right edge; the label remains much less imposing than the imagery beneath.

**Transfer:** Use a literal category noun rather than a promotional slogan.

### Product tile

**Use:** Repeated products or comparable offerings in a shelf.

**CSS:** `position: relative; border-radius: 0px`

**Text style:** `body` — Helvetica 400 · 15px/1.2

**Observed:** Square photograph first, then a caption block 7.5px below it. Title wraps naturally; price and currency sit on the next line with no extra gap. No enclosing border, button or badge is added.

**Transfer:** For non-commerce content use the second line for a concise factual attribute instead of a price.

### Feature image tile

**Use:** Large image-led entry points in pairs.

**CSS:** `position: relative; overflow: hidden; border-radius: 0px`

**Text style:** `body` — Helvetica 400 · 15px/1.2

**Observed:** A square photograph dominates; a small left-aligned category caption sits below, never over the photograph. The opening uses two equal tiles and the same construction returns for paired offers.

**Transfer:** Give each tile a different visual rhythm, such as a close handheld object against a repeated overhead arrangement.

### Editorial tile

**Use:** Four-column news or release stories.

**CSS:** `position: relative; border-radius: 0px`

**Text style:** `body` — Helvetica 400 · 15px/1.2

**Observed:** A 349px square photograph leads into a plain title and date below. The visual scene can be more expressive than the consistent studio product shelf, including outdoor light and colored backdrops.

**Transfer:** Use dated updates or concise feature notes; keep metadata at the same scale as the title.

### Email field

**Use:** Newsletter subscription alongside the Outline action.

**CSS:** `border: 1px solid #1c1c1c; border-radius: 15px; padding: 3.8px 7.5px; background: transparent`

**Text style:** `body` — Helvetica 400 · 15px/1.2

**Observed:** A long shallow field occupies most of the right-hand half of the signup row; the submit capsule sits beside it with a 3.8px gap. The field is about 28px high.

**Transfer:** Keep the input and button visually related, without a filled conversion panel.

### Utility footer

**Use:** Finish with social, information and transaction utilities.

**CSS:** `background: #ffffff; padding-top: 28.1px; padding-bottom: 28.1px; color: #1c1c1c`

**Text style:** `body` — Helvetica 400 · 15px/1.2

**Observed:** Social icons under a small bold label sit left; comma-separated informational links align right. A lower register places copyright and platform text left, region/currency and a compact payment-mark strip right. No contrasting closing band or oversized closing CTA.

**Transfer:** Retain the two-register utility layout; use relevant legal, locale and service marks rather than inventing trust badges.

## Imagery and graphics

### Photographic diptych

**Use:** Signature first impression and recurring paired feature tiles.

**Observed:** One image shows a book held in a hand against a vivid red backing; the companion uses a diagonal repeated array of white objects with bold primary-colored graphics. Both fill their square frames edge to edge. Labels are small and external, so the photographs occupy nearly all of the first screen.

**Transfer:** Stage one close, tactile product interaction beside a broader arrangement of related objects. For digital products, print representative outputs or create clean physical mockups and photograph them; the minimum is a well-lit close-up plus an arranged artifact sheet, not an empty color square.

### Studio inventory

**Use:** Dense product shelves.

**Observed:** Individual covers, small groups or standing objects centered on very pale gray or white photographic backings. Objects usually leave a visible breathing margin within the square; gentle grounding shadows and paper edges convey material. Cover colors vary freely without changing the page palette.

**Transfer:** Use consistent framing and scale across each shelf, soft studio illumination and restrained natural shadows. For software or services, show designed outputs or substantial interface artifacts as flat, legible squares rather than miniature browser chrome.

### Editorial still life

**Use:** News tiles and the large split promotional feature.

**Observed:** Scenes include reflective silver cards, a blue cap on a luminous green shelf, a handheld book in dappled outdoor light, and a dense overhead scatter of colorful publications. Photography carries the richness; the surrounding text and surface stay austere.

**Transfer:** Photograph authentic materials, production details and collections in varied but deliberate settings. A scatter arrangement should overlap naturally and fill the frame, while reflective objects retain believable highlights rather than synthetic UI shadows.

### Icons

**Observed:** Header utility icons are 23px outline SVGs in ink, with 1.4px square-ended strokes. Social marks are 17px solid silhouettes; a small dropdown chevron uses the same restrained line language.

**Transfer:** Choose simple menu, search and task-specific utility glyphs; avoid filled icon containers and oversized decorative feature icons.

## Section recipes

How recurring sections are built.

### First screen: Photographic opening

**Observed:** White canvas behind an 83px Masthead, followed immediately by the opening diptych. Two equal 705px square photographs nearly span the width with 11.3px outer insets and a 7.5px center gutter. The back-to-front layers are white page, full rectangular photography, then separate live captions below. There is no live display headline, support paragraph or overlaid CTA: the category captions use the body recipe. Within the first 900px the entire diptych and its captions are visible, followed by the next Section heading row and its Outline action; the product shelf starts at the lower edge.

**Transfer:** Lead with two compelling, contrasting product scenes rather than adding a conventional headline stack. Where photography is unavailable, make tangible output artifacts or precise product compositions at the same scale. A collection-focused page can begin directly with its literal heading and shelf while retaining the image-led identity elsewhere.

**Avoid:** Do not substitute a centered slogan over a gradient, darken the photographs with text scrims, or shrink the diptych to make room for a large sales button.

**Text style:** `body` — Helvetica 400 · 15px/1.2

### Catalogue shelf

**Observed:** White canvas with 28.1px top and bottom padding. Section heading row precedes a six-column Product tile grid with 7.5px column gaps and 15px row gaps. Four-column Editorial tiles use the same small text and spacing logic with larger images.

**Transfer:** Use repeated visual evidence to demonstrate range. Choose the four-column variant when each scene needs more room; do not change the typography to make it feel more important.

**Text style:** `heading` — Helvetica 700 · 20px/1 · tracking -0.025em

### Editorial declaration

**Observed:** A full-width, left-aligned paragraph in the display recipe, with 28.1px top and bottom padding and 11.3px side insets. At desktop it forms four tightly packed lines across nearly the entire page, without an eyebrow, button or illustration.

**Transfer:** Write one concrete declaration of what the product does and how it is selected or made. Let a few long lines create the interruption between compact image sections.

**Text style:** `display` — Helvetica 700 · 63.1px/1 · tracking -0.025em

### Split photographic feature

**Observed:** A 698px square still life on the left and an equally wide text region on the right, separated by 22.5px. The right column begins with a heading and one short factual paragraph; the Outline action follows with 30px spacing. Text is top-aligned, leaving substantial white space below.

**Transfer:** Use this asymmetry for a special offering or an explanation that needs a little context; let the image carry more area than the prose.

**Text style:** `heading` — Helvetica 700 · 20px/1 · tracking -0.025em

### Signup and utility close

**Observed:** A short white signup row uses two equal halves on a 22.5px structural gap. Heading and one sentence occupy the left; Email field and Outline action occupy the right at the top. Utility footer follows on the same canvas, with social and informational navigation above the lower legal, locale and payment details.

**Transfer:** Close with a practical ongoing relationship and compact utilities, rather than another theatrical promise. Preserve the shallow field and capsule pairing.

**Text style:** `heading` — Helvetica 700 · 20px/1 · tracking -0.025em

## Page flow

**Storyline:** Image-led invitation → browsable range → editorial positioning → fresh stories and deeper range → contextual offer → ongoing relationship → practical utilities.

### An editorial commerce landing page that establishes taste through objects before explaining the organization

1. **Invitation** — Large paired photographs with minimal category captions.
2. **Product demonstration** — Dense square-image shelves with literal headings, equal-weight titles and prices.
3. **Positioning** — A bold, full-width editorial declaration.
4. **Freshness and breadth** — Dated editorial tiles, additional shelves and a large paired feature.
5. **Contextual offer** — A square still life beside brief explanatory copy and a small outline action.
6. **Relationship and utilities** — Shallow newsletter form followed by a two-register white footer.

**Transfer:** Adapt the balance of close-up imagery, range and editorial explanation to the new product. The photographic diptych and blunt declaration remain recognizable devices without requiring the same categories or number of shelves.

## Writing

Direct, knowledgeable and matter-of-fact, with enthusiasm expressed through selection rather than superlatives. The copy feels like a small specialist shop or publisher speaking plainly.

**Do not copy:** Do not reuse the brand name, dotted identity mark, book titles, product artwork, dates, prices, proprietary claims or organization-specific statements. Source quotations below illustrate voice only.

- **Addressing the reader:** Mostly impersonal category labels and factual descriptions; the organization uses we and our in its statement and newsletter invitation. Direct address is rare.
- **Rhythm:** One- or two-word section labels and brief verb-led actions; supporting copy is generally one complete sentence. The large declaration is a compact two-sentence paragraph rather than a punchy slogan.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Category heading | Literal name of the content group; no metaphor or benefit claim. | 1–3 words | “All Books”<br>“News” |
| Editorial statement | State identity and specialization, then explain the activity in plain verbs. | Two sentences | “[Brand] is an independent publisher and online store specialising in design and visual culture. We produce and curate a unique selection of books from around the world.” |
| Supporting line | Explain an offer or relationship with a concrete fact. | One short sentence | “Receive special offers and a first look at new titles.”<br>“Books within this section are being offered at a discounted rate as they contain a small defect.” |
| Action | Short verb or verb-plus-object; no exaggerated urgency. | 1–2 words | “View all”<br>“Browse Here”<br>“Subscribe” |

**Words and phrasing to use:** selection; produce; curate; independent; new; first look; browse

**Avoid:** revolutionary; game-changing; unlock your potential; ultimate; hurry; !!!

**Rules:**

- Name the thing first; let photography supply the emotional appeal.
- Use plain factual metadata directly below titles.
- Keep category headings in ordinary title or sentence case, not tracked capitals.
- Give an offer's reason in one clear sentence rather than hiding it in promotional language.

## Do's and Don'ts

### Do

- Keep the page wrapper at 11.3px per side on the desktop composition.
- Use 7.5px horizontal shelf gaps and 15px row gaps.
- Set bold declarations at 63.1px/1 with -0.025em tracking.
- Keep ordinary section headings at 20px and supporting labels at 15px.
- Preserve square media and external, left-aligned captions.
- Use 1px outline capsules with 3.8px by 7.5px padding.
- Let photographic colors fill the media while all sections retain a white canvas.
- Use the 22.5px structural gap for split feature and signup layouts.

### Don't

- Do not turn 15px product prices into bold promotional numbers.
- Do not add 12px or 24px rounded corners to photographic tiles.
- Do not add interface drop shadows to the unboxed shelves.
- Do not convert the catalogue into a narrow 1200px centered shell with broad margins.
- Do not introduce a secondary serif or monospaced eyebrow system.
- Do not turn colored photographic backings into alternating full-page UI color bands.
- Do not replace the compact footer links with a tall multi-column sitemap.
- Do not add a filled primary-button variant merely to create a stronger hierarchy.

## Motion and responsive

### Motion

**Observed:**

- Media declares a 0.3s transition with cubic-bezier(0.4, 0, 0.2, 1), including opacity and transform among the transition properties.
- Outline actions declare white background and bright green text on hover, plus a visible ink keyboard-focus outline.

**Transfer:**

- Keep interaction concentrated on media and compact controls rather than choreographing entire sections.

**Unknown:**

- The visible amount of hover zoom and any scroll-triggered choreography are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 375px, 640px, 749px, 768px, 989px, 990px and 1400px.
- Left and right wrapper tokens both resolve to 11.3px; a mobile section-spacing token is 42px and mobile media row-gap token is 7.5px.

**Transfer:**

- On narrow layouts reduce shelf column counts while retaining square media and captions outside it.
- Stack split text and imagery and allow signup controls to wrap; preserve the small monochrome control language.

**Unknown:**

- Exact mobile column counts, display font scaling, header rearrangement and breakpoint-specific behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
