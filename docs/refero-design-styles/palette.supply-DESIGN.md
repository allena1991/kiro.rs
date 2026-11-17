# Palette Supply — sunlit studio catalogue

## Overview

A photographic catalogue with the warmth of a working studio and the matter-of-fact labeling of a supply shop. White space, black type and restrained indigo frame sunlit interiors, tactile objects and carefully staged digital products. Medium-weight geometric sans headings meet light monospace descriptions and tiny spaced capitals; the imagery is expansive while the language and controls stay compact.

### Essentials

- The photograph is the opening argument: an 810px-tall, edge-to-edge environmental product scene sits beneath a 28px indigo announcement, with a transparent 60px navigation layer and a bottom-left 38px headline.
- Headlines stay human-sized beside enormous pictures: ES Build 500 at 38px/1.3 with -0.02em tracking, contrasted with PP Supply Mono 300 at 12px/18px for short supporting copy.
- Actions resemble small inventory labels rather than campaign badges: 10px/12px light mono capitals with 0.12em tracking, inside 36px-high grey buttons with 5px corners or beside a tiny triangular arrow.
- The interface withholds color so the pictures can carry it: white dominates the content canvas, indigo occupies the narrow 28px offer strip and the monumental closing artwork, and controls use #e3e3e3 with #d2d2d2 rules.
- Products are staged as tangible objects: square-cornered portrait images, approximately 3:4, sit only 4px apart in catalogue rows; paper stacks and devices are backed by pale warm studio fields or photographed in real directional light. Use a clean layered document or device composition when original photography is unavailable.
- The ending becomes a piece of signage: a compact white directory and newsletter give way to an indigo field about 617px tall with a pale wordmark filling roughly 92% of its width. Every new page carries this oversized brand-signature device using its own lettering.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Studio indigo | `#3651a2` | `--color-indigo` | background, accent | Announcement strip, small brand marks and the oversized closing signature field. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, accent, action | Primary typography, tiny arrow glyphs, selected license options and cart-count backgrounds. |
| Secondary ink | `#707070` | `--color-secondary` | text, link | Eyebrows, secondary metadata and subdued text-link hover. |
| Divider grey | `#d2d2d2` | `--color-rule` | border | Accordion separators, newsletter underline and category-link dividers. |
| Button grey | `#e3e3e3` | `--color-button` | action, surface | Inset face of primary and secondary rectangular actions; also a suitable pale finish for the closing signature. |
| Catalogue grey | `#f4f4f4` | `--color-band` | surface, background | Category link band and quantity selector. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page canvas and reversed text over photography. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| commerce modules | Comparison ink | `#757575` | `--color-compare` | text | Crossed-out comparison prices. |

## Typography

- **ES Build** — Headings, product titles, accordion questions and offer text. Rounded geometric grotesk with open forms and a friendly medium weight. OpenType features: "ss02". If unavailable, use **DM Sans**. Use weight 500 and preserve -0.02em tracking. Font stack: "ES Build", "DM Sans", sans-serif.
- **PP Supply Mono** — Body, support copy, navigation, metadata, prices and action labels. Light, utilitarian monospaced lettering; small labels gain unusually wide tracking. If unavailable, use **IBM Plex Mono**. Use 300 for copy and labels, 400 for navigation and footer headings. Font stack: "PP Supply Mono", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | ES Build | 500 | 38px | 1.3 | -0.02em | Hero headline, major section titles and large benefit statements. |
| heading-small | ES Build | 500 | 22.4px | 1.3 | -0.02em | Featured purchase title, journal titles and newsletter invitation. |
| product-title | ES Build | 500 | 19px | 1.2 | -0.02em | Product-card links below portrait imagery. |
| body | PP Supply Mono | 300 | 16px | 1.5 | normal | Expanded accordion answers, footer links and longer personal narrative. |
| navigation | PP Supply Mono | 400 | 14px | 1.5 | -0.02em, uppercase | Main navigation and bag label. |
| footer-heading | PP Supply Mono | 400 | 14px | 1.2 | -0.02em, features "ss02" | Small mixed-case directory headings. |
| question | ES Build | 500 | 14px | 1.3 | -0.02em | Accordion question labels. |
| support | PP Supply Mono | 300 | 12px | 1.5 | normal | Compact section descriptions, availability notes and pagination. |
| metadata | PP Supply Mono | 300 | 12px | 1.2 | -0.02em | Hero descriptor, prices, breadcrumbs and muted section eyebrow; apply strikethrough only to comparison prices. |
| announcement | ES Build | 500 | 12px | 1.3 | -0.02em | Single-line offer in the indigo strip. |
| action-label | PP Supply Mono | 300 | 10px | 1.2 | 0.12em, uppercase | Button text, arrow links and the category navigation band. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| commerce modules | purchase-price | PP Supply Mono | 300 | 14px | 1.2 | -0.02em | Purchase-panel prices, with the previous price struck through. |

**Notes:**

- Sans headings use the same -0.02em tracking across the hierarchy; scale changes are modest, from 19px card titles to 38px section headlines.
- The smallest action text reverses that logic: 0.12em tracking gives the 10px capitals their label-like character.
- Keep supporting copy visually subordinate in narrow blocks, generally no wider than 380px. Most section descriptions use 12px mono rather than the 16px body recipe.
- The monumental closing wordmark is artwork, not a larger version of the heading scale.

## Layout

**Density:** Airy at the section level and tightly packed within catalogue rows; small labels sit against very large photographic fields.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Horizontal gutter between catalogue and journal images. |
| 8px | Headline-to-description spacing and price grouping. |
| 12px | Description-to-text-action spacing and compact accordion padding. |
| 14px | Product image-to-title inset and vertical padding of the category band. |
| 16px | Hero heading-to-button gap. |
| 24px | Newsletter title-to-field gap. |
| 32px | Desktop page side padding and section-header-to-media gap. |
| 48px | Opening product-section top padding and interior category-link spacing. |
| 64px | Standard catalogue-section top and bottom padding; hero content bottom inset. |
| 120px | Only for editorial story pages: vertical breathing room around a three-part principles row. |

### Containers and grids

- **page-container**: max width 1440px · side padding 32px. Full desktop content width with consistent outer gutters; photographic hero and split features can bleed to the edges.
- **catalogue-row**: 3 columns · gap 4px. Default marketing carousel: three 456px-wide portrait cards across the inner width.
- **split-feature**: 2 columns · gap 0px. Two equal 720px halves: large photography on the left, a narrow centered text block on the right. The FAQ variant reverses the image to the right and uses 32px outer gutters.
- **reading-block**: max width 380px. Support copy, split-feature text and accordion column.
- **newsletter-column**: max width 306px. Rightmost footer column; balanced by a brand column of similar width and three small directory columns in the middle.
- **commerce-grid** (only for collection and purchase pages): 4 columns · gap 4px. Four 341px-wide cards per row, also used for related products.
- **purchase-panel** (only for commerce modules): max width 340px. Narrow purchase or product-support block beside the product gallery.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 5px |
| photographs | 0px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** All default content sections and card backing.

**CSS:** `background: #ffffff; color: #000000; box-shadow: none`

**Observed:** The interface remains flat; photographic shadows belong inside the artwork rather than around HTML cards.

**Transfer:** Let scale and whitespace separate sections rather than raised containers.

#### Photo veil · level 1

**Use:** Legibility layer over the hero and image-led promotion tiles.

**CSS:** `background: rgba(0, 0, 0, 0.3)`

**Observed:** A restrained dark wash unifies bright wood and pale objects behind reversed text.

**Transfer:** Layer above the image and below text; preserve the texture and sunlight.

#### Category band · level 0

**Use:** Narrow navigation bridge into the footer.

**CSS:** `background: #f4f4f4; padding: 14px 0`

**Observed:** A full-width strip contains centered uppercase category links divided by hairlines.

**Transfer:** Keep it a slim directory, not a second primary navigation bar.

#### Indigo signature field · level 0

**Use:** Offer-strip color and monumental brand-signature backing.

**CSS:** `background: #3651a2; overflow: hidden`

**Observed:** The closing version is a flat, untextured color field with giant pale lettering; no gradient or glow.

**Transfer:** Use the same solid indigo at both extremes of the page, with the large field reserved for the signature.

#### Ruled disclosure · level 0

**Use:** FAQs and product information.

**CSS:** `border-bottom: 1px solid #d2d2d2; background: #ffffff`

**Observed:** Thin rules, not boxed cards; the first open item can also have a top rule.

**Transfer:** Use repeated horizontal lines to organize concise questions.

## Components

### Announcement strip

**Use:** A short offer above the primary navigation.

**CSS:** `background: #3651a2; color: #ffffff; height: 28px; padding: 0 32px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `announcement` — ES Build 500 · 12px/1.3 · tracking -0.02em

**Observed:** Offer is left aligned; a tiny spaced-capitals Close control sits at the far right.

### Overlay navigation

**Use:** Default header over an environmental hero.

**CSS:** `height: 60px; padding: 0 32px; display: flex; align-items: center; justify-content: space-between; color: #ffffff; background: transparent`

**Text style:** `navigation` — PP Supply Mono 400 · 14px/1.5 · tracking -0.02em · uppercase

**Observed:** Six compact links occupy the left, a 125px-wide logo is centered independently, and underlined search, account outline and bag counter occupy the right. Commerce pages use the white-canvas version with black labels and an indigo logo.

**States:** Declared: hover opacity 0.6 on navigation links; focus-visible outline .1rem solid white over photography, offset 0.2rem, with a white alpha shadow.

### Grey action

**Use:** Hero action and purchase/detail actions.

**CSS:** `background: #e3e3e3; color: #000000; border: 1px solid transparent; border-radius: 5px; height: 36px; padding: 10px 13px; display: inline-flex; align-items: center; justify-content: center; box-sizing: border-box; overflow: hidden`

**Text style:** `action-label` — PP Supply Mono 300 · 10px/1.2 · tracking 0.12em · uppercase

**Observed:** The real construction has an outer interactive border and an inset animated face. Hero width follows its label; purchase actions stretch across the narrow panel.

**States:** Declared: hover border-color #d2d2d2; focus-visible outline .1rem solid white over photography, outline-offset 0.2rem, box-shadow 0 0 .2rem rgba(255,255,255,0.3).

**Transfer:** Retain the compact face rather than enlarging the action to match the photograph.

### Arrow text link

**Use:** Section-level navigation below a short description.

**CSS:** `color: #000000; display: inline-flex; align-items: center; gap: 6px; text-decoration: none`

**Text style:** `action-label` — PP Supply Mono 300 · 10px/1.2 · tracking 0.12em · uppercase

**Observed:** A tiny solid right-pointing triangle terminates the label; it is not a long line arrow or a circled icon.

**States:** Declared: hover color #707070; focus-visible outline .1rem solid black with offset 0.2rem and black alpha shadow.

### Product card

**Use:** Catalogue carousels, collections and related products.

**CSS:** `background: #ffffff; border-radius: 0px; overflow: hidden; position: relative`

**Text style:** `product-title` — ES Build 500 · 19px/1.2 · tracking -0.02em

**Observed:** Unframed portrait artwork comes first; information has a 14px top inset and 8px horizontal inset. Title precedes the small mono price. Current and crossed-out comparison prices sit on the same line; sale status can sit to the right. No card shadow or enclosing outline.

**States:** Declared: hover opacity 0.6 on title links.

**Transfer:** Keep product names descriptive and let an original artwork carry the card's color.

### Carousel controls

**Use:** Right edge of catalogue and journal heading rows.

**CSS:** `display: inline-flex; align-items: center; gap: 6px; color: #000000`

**Text style:** `support` — PP Supply Mono 300 · 12px/1.5

**Observed:** Small 24px arrow hit areas flank a mono current/total counter. The disabled previous arrow is at opacity 0.2.

**States:** Declared: hover on next arrow transform translate(2px), opacity 0.6; focus-visible black outline with offset and alpha shadow.

### Accordion row

**Use:** FAQ and explanatory information beside a large photograph.

**CSS:** `border-bottom: 1px solid #d2d2d2; max-width: 380px; background: #ffffff`

**Text style:** `question` — ES Build 500 · 14px/1.3 · tracking -0.02em

**Observed:** A compact question and tiny disclosure marker share a row; toggle padding is 12px above and 10px below. The expanded answer uses body type, with 24px right padding and 12px below. Default marketing treatment can show the first answer expanded; story-page questions begin closed.

**Transfer:** Use answer text for concrete reassurance rather than adding a separate feature-card grid.

### Newsletter field

**Use:** Right-hand footer signup.

**CSS:** `border-bottom: 1px solid #d2d2d2; padding: 0 70px 10px 0; width: 306px; box-sizing: border-box; background: transparent`

**Text style:** `body` — PP Supply Mono 300 · 16px/1.5

**Observed:** A single underline with a tiny submit triangle at the far right; it sits 24px beneath a two-line heading-small invitation.

**Transfer:** Keep the field inline with the directory rather than in a colored signup card.

### Category link

**Use:** Navigation inside Category band.

**CSS:** `display: flex; align-items: center; gap: 6px; padding: 0 48px; border-right: 1px solid #d2d2d2; border-radius: 5px; color: #000000`

**Text style:** `action-label` — PP Supply Mono 300 · 10px/1.2 · tracking 0.12em · uppercase

**Observed:** Centered categories have very short dividers and tiny triangle suffixes; the first link uses 32px left padding.

**States:** Declared: hover color #767676.

## Imagery and graphics

### Environmental product hero

**Use:** The dominant first-screen object.

**Observed:** A desktop monitor on a timber cabinet is photographed almost front-on, slightly angled, with a sculptural white lamp and stacked books to one side. Warm vertical wood grain, realistic sunlight and dark image overlay give the large digital product a tactile setting. The monitor fills most of the central and upper image while the title sits unobtrusively below it.

**Transfer:** Stage the new product in a credible workspace with one main object and a restrained supporting prop. If photography is unavailable, composite a crisp original product image into a simple warm interior with directional light; retain the believable physical frame.

### Layered product still life

**Use:** Portrait product cards and large demonstration pairs.

**Observed:** Overlapping paper or slide sheets float above warm off-white or grey-green backing; soft directional shadows make the files feel physical. Phones appear upright and isolated, and some images instead show actual paper on a wooden table with a camera. The backing is inside the artwork, not an interface card fill.

**Transfer:** Arrange three to five original sheets or a single device within a 3:4 composition. Preserve readable silhouettes rather than shrinking an entire dashboard into a card.

**Build:** Use a portrait SVG or image composition with a pale warm backing. Center one main rectangular document, place two slightly offset rectangles behind it, and apply a soft shadow below the sheets inside the artwork. Limit offsets to a small fraction of sheet width; use original product content and muted photographic colors.

### Sunlit material photographs

**Use:** Full-height split features, paired promotions and collection cards.

**Observed:** Tactile cloth, paper, cream walls, folding chairs, olive objects and studio furniture are lit by directional window light. Crops often omit faces or cut close to an object; deep shadows remain rich without glossy studio effects. Occasional pale blue or chartreuse exists inside photographs, not as interface decoration.

**Transfer:** Use a restrained natural-light shoot with real material texture and a single clear subject. For a nonphysical product, show the object or document in use in a similarly lit room.

### Paired image labels

**Use:** Two-up image-led promotions.

**Observed:** Two 720px square images meet without a gutter, each darkened slightly with a centered white mono label on a translucent white rounded patch.

**Transfer:** Pair contrasting contexts of use or two product families while keeping both labels equally small.

**Build:** Create two equal square image containers with object-fit cover. Add a subtle black overlay, then center a 12px mono label with 4px 6px padding, 5px radius and rgba(255,255,255,0.2) backing.

### Monumental wordmark

**Use:** Required oversized brand-signature device, especially the final reveal.

**Observed:** Pale lowercase geometric lettering nearly fills a solid indigo rectangle. About 617px of vertical space is devoted to this final field at desktop, with roughly 32px side breathing room. It is graphic artwork rather than a paragraph or a conversion headline.

**Transfer:** Replace with the new brand's own wordmark, retaining the nearly edge-to-edge size and contrasting pale-on-indigo treatment. If no logo exists, typeset the new name as a simple tightly fitted geometric wordmark.

**Build:** Make an SVG with a viewBox fitted to the new lettering, fill letters with #e3e3e3, and place it centered inside the Indigo signature field. Size the artwork to about 92% of the field width and preserve its aspect ratio; use a 617px desktop stage with overflow hidden. Scale to width rather than forcing the name to match a heading font size.

### Studio diary strip

**Only for:** editorial story pages

**Use:** A human, process-led interlude between short principles and detailed questions.

**Observed:** A horizontal strip of 344px by 459px portrait photographs with 4px gaps includes working papers, a studio light, an informal portrait through a window, sun on furniture and a collaborator. Partial images continue beyond the viewport.

**Transfer:** Use a mixed sequence of people, tools and spaces; keep candid texture and the shared portrait ratio rather than a uniform team headshot grid.

### Icons

**Observed:** Tiny 6px solid triangles finish text links. Account and search symbols use 1.3px round strokes at 22px and 16px; carousel controls occupy 24px squares. Disclosure graphics are small and black, without decorative icon containers.

**Transfer:** Choose minimal outline utility icons and solid triangle direction markers; reverse them to white only over photography.

## Section recipes

How recurring sections are built.

### First screen: Environmental opening

**Observed:** An indigo Announcement strip occupies the top 28px. Beneath it, an 810px full-bleed environmental image provides the stage, with Overlay navigation across its top 60px. The main object fills the middle and upper picture; a Photo veil lies between image and text. A narrow bottom-left content group, inset 32px from the side and 64px from the bottom, holds a one-line mono descriptor, the white heading at 38px, then Grey action after 16px. Headline width is limited to about 430px rather than spanning the canvas. Within the first 900px, the full scene, descriptor, headline, action and beginning of the next white section are visible; its supporting text and product gallery continue below the fold.

**Transfer:** Give a different product one equally legible physical or composited setting and let its main object dominate the frame. Do not depend on a large headline for impact. Purchase pages instead open on white with a 340px purchase column left, 516px-wide portrait gallery and vertical thumbnails in the center, and a support accordion right. Collection pages use a 22.4px category title and a compact toolbar before the product grid. Editorial stories use the environmental stage with a centered narrow block of white narrative text.

**Avoid:** Do not replace this with a centered oversized slogan over a gradient, or put a tiny product thumbnail below a large text-only hero.

**Text style:** `heading` — ES Build 500 · 38px/1.3 · tracking -0.02em

### Heading and catalogue

**Observed:** A left-aligned heading is followed after 8px by a narrow support paragraph and after 12px by Arrow text link. Carousel controls align to the right at the lower edge of the header. Leave 32px before media and use catalogue-row layout with Product card. Standard section padding is 64px above and below; the first purchase feature begins with 48px above.

**Transfer:** Use this for a family of capabilities, use cases or related products. Keep the header narrow even when the media spans the full width.

**Text style:** `heading` — ES Build 500 · 38px/1.3 · tracking -0.02em

### Immersive split feature

**Observed:** A 720px-wide photograph fills one half of a 900px-tall desktop feature while a white half contains a vertically centered reading-block, headline, short support and Arrow text link. The same framing can change image and message through the chapter.

**Transfer:** Use one image per capability and a compact outcome statement; let the photograph occupy half the page instead of placing it in a small rounded card.

**Text style:** `heading` — ES Build 500 · 38px/1.3 · tracking -0.02em

### Image and disclosure

**Observed:** An approximately 688px square studio photograph occupies the right half. The left half centers a 380px-wide content column with optional muted metadata eyebrow, a heading and Accordion row stack, then Arrow text link. Open-answer body text is visibly larger than the short section descriptions.

**Transfer:** Pair a real usage environment with practical questions, compatibility, process or support information.

**Text style:** `heading` — ES Build 500 · 38px/1.3 · tracking -0.02em

### Editorial carousel

**Observed:** A Heading and catalogue header introduces image-led reading cards. The default row has three large portrait images and heading-small titles; the story variant packs six 226px-wide images into the same inner width. Titles sit around 14px below the images, without visible card chrome.

**Transfer:** Offer educational material or practical guidance related to the new product, rather than filling every card with a sales claim.

**Text style:** `heading-small` — ES Build 500 · 22.4px/1.3 · tracking -0.02em

### Closing statement and signature

**Observed:** A centered 38px closing line can sit within a 300px-tall white interval. Category band precedes a white directory area about 307px high, whose content begins 56px from the top: brand and short descriptor left, three compact link columns in the middle, Newsletter field right. The Monumental wordmark then fills the Indigo signature field, extending the ending beyond the ordinary footer.

**Transfer:** Retain the oversized brand-signature device and compact directory relationship. A final benefit line can bridge from the last content block without demanding another large button.

**Text style:** `heading` — ES Build 500 · 38px/1.3 · tracking -0.02em

## Page flow

**Storyline:** immersive promise → concrete product demonstration → browseable choices → context and practical reassurance → useful reading → directory and oversized signature

### Marketing landing page: create desire and help visitors discover a product family

1. **Promise** — Environmental opening gives the offer a tangible setting.
2. **Product demonstration** — A short download-oriented introduction leads to two large examples beside a compact purchase panel.
3. **Capability chapters** — Catalogue rows alternate with immersive split features and paired use-case images.
4. **Reassurance** — A studio photograph and disclosure stack explain practical value.
5. **Useful reading** — An editorial carousel offers deeper guidance.
6. **Closing identity** — A brief centered statement, directory band, footer and monumental signature finish the page.

**Transfer:** Adapt the number and sequence of demonstrations to the product while preserving the alternation of immersive image and compact utility.

### Purchase detail: resolve selection and support questions with the product always prominent

1. **Selection and purchase** — White three-part opening: purchase information left, large gallery with seven vertical thumbnails center, support disclosures right.
2. **Cross-sell** — A smaller 22.4px heading introduces a four-card related-product carousel.
3. **Closing identity** — Category navigation, shared directory and giant indigo signature; a compact product purchase strip accompanies the later portion.

**Transfer:** Use descriptive product naming, visible choices, simple quantity control and nearby delivery reassurance; keep third-party checkout treatment separate from the brand's own button system.

### Collection browsing: maximize comparable visual choices

1. **Orientation** — Small category heading beneath white navigation.
2. **Selection controls** — Filter, grid-density icons and sort share a slim white toolbar.
3. **Product discovery** — A dense four-column grid uses consistent portrait imagery and small labels; the toolbar persists while browsing.
4. **Continuation** — Small centered current/total pagination appears beneath the final row.
5. **Closing identity** — Category band, directory, signup and monumental indigo artwork.

**Transfer:** Prioritize consistent image ratios and compact metadata over introductory marketing copy.

### Editorial story: establish the people and working philosophy behind a product

1. **Human introduction** — An informal studio image backs a centered narrow heading and narrative paragraph.
2. **Principles** — Three evenly spaced text columns use small mono headings and descriptions with 120px vertical breathing room.
3. **Process demonstration** — A horizontally overflowing studio diary strip connects people, spaces and tools.
4. **Objection handling** — A square environment image pairs with a closed FAQ stack.
5. **Useful reading** — Six compact journal cards broaden the conversation.
6. **Closing identity** — The same category directory, newsletter and oversized signature conclude the story.

**Transfer:** Translate principles into short working beliefs, then substantiate them with real process imagery and practical answers.

## Writing

Friendly, practical and studio-literate. The copy promises useful help and creative momentum, then names the tools, file formats or outcomes that make that help concrete.

**Do not copy:** Do not reuse the Palette name, wordmark, collaborator names, product titles, founder story, discount amounts, prices, page counts or claims as facts for another brand. Source examples illustrate voice only.

- **Addressing the reader:** Use you and your for benefits; we for beliefs and support. Product names can be descriptive and impersonal, while story text is warmer.
- **Rhythm:** Short three-to-six-word section headlines alternate with one or two compact explanatory sentences. Long descriptive product names use em dashes and lists; action labels are brief verbs plus objects.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the product or useful collection without a superlative. | 3–6 words | “The Photographer's Toolkit” |
| Benefit heading | Verb-led outcome in everyday language. | 3–7 words | “Land Your Next Client”<br>“Display your latest designs with mockups” |
| Supporting line | Say what the product makes easier, then mention familiar tools or a concrete operation. | 1–2 sentences | “Real photo mockups created by leading photographers and designers. Showcase your designs with just a few clicks.” |
| Action | Simple verb and destination or object. | 2–4 words | “Shop all products”<br>“Explore all tools” |
| Reassurance | Plain operational detail, not a promotional slogan. | 4–9 words | “Downloads ready immediately after purchase” |

**Words and phrasing to use:** useful; ready to customize; tools; showcase; built for; inspiration; organized files; no starting from scratch

**Avoid:** revolutionary; disruptive; game-changing; unlock limitless potential; enterprise-grade ecosystem

**Rules:**

- Lead with the user's task, then explain the practical means.
- Name compatibility where it removes uncertainty.
- Keep promotional language modest enough to sit beside documentary imagery.
- Use sentence case for prose and product names; uppercase is a visual treatment reserved for navigation and small actions.

## Do's and Don'ts

### Do

- Keep the main headline at 38px/1.3 and weight 500 even when the main photograph fills 810px of height.
- Use 32px outer gutters and only 4px between catalogue images.
- Keep short supporting descriptions at 12px/18px mono within a 380px text block.
- Use 5px corners for controls and square corners for photography.
- Keep the primary action 36px high with 10px spaced-capital labels.
- Let sunlight, paper and fabric supply most of the color and texture.
- Include a monumental own-brand wordmark on a solid indigo stage.
- Use 1px #d2d2d2 rules for disclosures and signup fields.

### Don't

- Do not turn the 38px heading scale into a 90px typographic campaign.
- Do not replace the compact 10px mono labels with bold 16px pill text.
- Do not add drop shadows to HTML catalogue cards; depth belongs inside the artwork.
- Do not turn the white content sections into repeated indigo panels; the large indigo field belongs to the signature.
- Do not widen short body descriptions across the full 1376px content area.
- Do not standardize every text role into sans; the light mono support is half the identity.
- Do not use 24px gutters between product images; the near-contact 4px rhythm is distinctive.
- Do not decorate disclosure rows with rounded containers or colored icon badges.

## Motion and responsive

### Motion

**Observed:**

- Links commonly declare 0.3s transitions, including opacity and color changes.
- Buttons declare border .1s; the inset button face has an overlay-animation construction.
- The next carousel arrow declares translate(2px) and opacity 0.6 on hover.
- Ticker lines declare infinite linear animation with a variable duration.
- The closing artwork is arranged as a sticky background reveal with an enlarged media layer.

**Transfer:**

- Retain the small next-arrow nudge and subdued link fade rather than adding large bouncing controls.
- Let the final indigo artwork read as an oversized reveal behind the white directory; a static full-width rendering preserves its identity if sticky staging is unsuitable.

**Unknown:**

- Ticker duration and complete animation choreography are unspecified.
- Timing of scroll-driven split-feature changes and the final reveal is not established.

### Responsive

**Observed:**

- CSS includes width boundaries around 575–576px, 749–750px and 989–990px, alongside several wider desktop adjustments.

**Transfer:**

- On narrower screens, preserve the portrait artwork and compact labels; stack the split-feature image and reading block instead of compressing both into narrow columns.
- Keep the closing signature fitted to width and let the footer directory wrap before reducing text size.
- Treat these as adaptation guidance; retain the same hierarchy rather than inventing a separate visual theme.

**Unknown:**

- Exact mobile stacking order, gutter sizes, type sizes and navigation behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
