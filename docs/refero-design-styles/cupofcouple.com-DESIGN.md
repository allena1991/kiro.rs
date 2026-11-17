# Cup of Couple — the photographic ledger

## Overview

An art-directed photographic journal with the structure of a newspaper and the polish of a fashion title. Pale gray paper, charcoal lettering and fine gray rules support a mix of sculptural display lettering, classical titling serifs, literary body serif and utilitarian grotesk labels. Images carry the color and personality; the surrounding interface is deliberately monochrome, dense in its cataloguing and spacious around its photographs. It suits design-led products, creative services and collections that can demonstrate their character visually.

### Essentials

- Identity behaves like a magazine masthead, not a sales slogan: centered uppercase DisplaceKC at 72px, weight 400, line height 1.2, repeated as a substantial closing signature.
- The opening is an editorial front page: a 170px featured-image strip above a 135px masthead and a 58px ruled navigation row, followed after 36px by two 666×444px photographs.
- Headlines change scale with the column, not with promotional importance alone: PerpetuaTitlingMT at 48px/1.2 for half-width stories, 40px/1.2 for thirds and 32px/1.2 for quarters, all weight 400 with normal tracking.
- Actions are printed labels rather than filled buttons: uppercase Franklin Gothic at 16px/1.2, square transparent construction, 1px gray rules and a fine underline on hover.
- All interface color stays on the grayscale paper: #f0f0f0 canvas, #303030 visible ink and #808080 separators; saturated orange, blue and pink belong inside photographs, never in decorative panels.
- Photographs are the principal proof device: sharp rectangular frames, typically 3:2, no overlaid copy, and 36px gutters with fine vertical column dividers. Without campaign imagery, use carefully lit product still lifes or human-use photographs with the same editorial framing.
- The ending is a colophon rather than a conversion billboard: a 72px signature above three equally sized contact, subscription and connection cells, then a compact italic legal line separated by a 1px rule.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Printed charcoal | `#303030` | `--color-ink` | text, link, action | Visible result of black at 0.8 alpha over gray paper; primary lettering throughout. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ledger gray | `#808080` | `--color-rule` | border | Horizontal and vertical 1px dividers and fine link underlines. |
| Gray paper | `#f0f0f0` | `--color-canvas` | background, surface | Continuous page, header, article and footer ground; no distinct raised card fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| multilingual editorial pages | Inactive gray | `#787878` | `--color-muted` | text | Visible black at 0.5 alpha over gray paper for the inactive language option. |

## Typography

- **DisplaceKC** — Identity masthead and closing signature; short page titles. Sculptural uppercase lettering with sharp diagonal cuts and contrasting curved and straight strokes. If unavailable, use **Italiana**. Use weight 400; retain the narrow elegant capitals and open counters. Font stack: "DisplaceKC", "Italiana", serif.
- **PerpetuaTitlingMT** — Photographic story titles. Fine classical inscriptional capitals, less theatrical than the identity lettering. If unavailable, use **Cinzel**. Use weight 400 with normal tracking; preserve the single-line title treatment. Font stack: "PerpetuaTitlingMT", "Cinzel", serif.
- **Garamond** — Editorial paragraphs, descriptions, small footer text and italic annotations. Old-style literary serif with fine strokes and a compact lowercase texture. If unavailable, use **EB Garamond**. Use regular and italic 400; preserve the 1.2 body line height. Font stack: "Garamond", "EB Garamond", serif.
- **ITCFranklinGothicStdBook** — Navigation, section bars, metadata, dates and contact links. Plain book-weight grotesk, largely uppercase, deliberately subordinate to the serif titles. If unavailable, use **Libre Franklin**. Use weight 400 and normal tracking. Font stack: "ITCFranklinGothicStdBook", "Libre Franklin", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| masthead | DisplaceKC | 400 | 72px | 1.2 | normal, uppercase | Centered identity at the opening and the closing signature. |
| story-lead | PerpetuaTitlingMT | 400 | 48px | 1.2 | normal | Titles beneath half-width lead photographs. |
| story-medium | PerpetuaTitlingMT | 400 | 40px | 1.2 | normal | Titles beneath third-width photographs. |
| story-small | PerpetuaTitlingMT | 400 | 32px | 1.2 | normal | Quarter-width story titles and compact featured stories. |
| small-copy | Garamond | 400 | 17px | 1.2 | normal | Footer support text and subscription prompt. |
| colophon | Garamond | 400 italic | 17px | 1 | normal | Closing descriptor and legal links. |
| label | ITCFranklinGothicStdBook | 400 | 16px | 1.2 | normal, uppercase | Navigation, section names, metadata, dates, pagination and footer actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and service editorial pages | page-title | DisplaceKC | 400 | 72px | 1.05 | normal, uppercase | Centered title above the editorial column system. |
| company and service editorial pages | body | Garamond | 400 | 28px | 1.2 | normal | Long-form descriptions and editorial side-column copy. |
| company profile pages | category-italic | Garamond | 400 italic | 28px | 1.2 | normal | Category dividers within long proof lists. |
| company and service editorial pages | contact-link | ITCFranklinGothicStdBook | 400 | 24px | 1.35 | normal, uppercase | Email and social links in the information rail. |

**Notes:**

- Use all type at weight 400; contrast comes from four distinct constructions, case and size rather than bold emphasis.
- Titling glyphs read as capitals even where the underlying title uses mixed case. Keep the utility sans uppercase and the prose in sentence case.
- Long card titles stay in a constrained single-line window; the title treatment permits lateral continuation instead of turning each card into a tall multiline block.
- Use normal tracking throughout. The identity's distinctive cuts should come from the face rather than added letter spacing.

## Layout

**Density:** Airy photographs inside a compact editorial ledger: tight ruled labels and side rails contrast with broad image areas and restrained whitespace.

### Spacing

**Spacing system:**

- **rhythm** 6px — Main spacing rhythm for margins, label padding and section breathing room; 15px article insets are a recurring exception.

| Value | Use |
| --- | --- |
| 12px | Compact label and colophon padding. |
| 15px | Inner editorial column inset and lower padding of ruled navigation cells. |
| 18px | Half-gutter around story cards and upper metadata padding. |
| 21px | Upper padding inside navigation cells. |
| 24px | Separation within sidebar information groups. |
| 33px | Upper padding of the closing signature band. |
| 36px | Outer desktop side padding, story gutters, story row separation and editorial block padding; 6 × 6px. |
| 72px | Separation between editorial gallery rows; 12 × 6px. |

### Containers and grids

- **page frame**: max width 1368px · side padding 36px. At 1440px, content occupies the width between equal outer margins. Treat this as a broad fluid frame rather than a narrow centered reading container.
- **lead stories**: 2 columns · gap 36px. Two equal 666px image columns; each article occupies a 702px module including its half-gutters.
- **catalog tiers**: 4 columns · gap 36px. The index shifts from two columns to three 432px images and then four 315px images. Fine vertical rules sit in the gutters.
- **footer cells**: 3 columns · gap 0px. Three equal 456px cells for contact, subscription and social connections, divided by vertical rules.
- **editorial rails** (only for company and service editorial pages): 3 columns · gap 0px · side padding 15px. A 342px information rail, 684px central story and 342px proof rail, with 1px column rules. The central text is 652px wide after borders and insets.
- **split proof rail** (only for company profile pages): 2 columns · gap 0px · side padding 18px. The right quarter divides into two 171px list columns with 135px text widths.

## Corner radius

| Element | Radius |
| --- | --- |
| images and controls | 0px |

## Surfaces and depth

### Surfaces

#### Gray paper · level 0

**Use:** The whole marketing canvas.

**CSS:** `background: #f0f0f0; color: rgba(0, 0, 0, 0.8)`

**Observed:** The same ground continues through stories, sticky navigation and the footer; photography supplies the only chromatic fields.

**Transfer:** Keep surrounding UI on one uninterrupted paper tone.

#### Ruled band · level 0

**Use:** Metadata and compact structural navigation.

**CSS:** `background: #f0f0f0; border-top: 1px solid #808080; border-bottom: 1px solid #808080; border-radius: 0px`

**Observed:** Thin rules establish the hierarchy without an enclosing rounded box.

**Transfer:** Separate content by lines and shared alignment, not by raised panels.

#### Editorial column · level 0

**Only for:** company and service editorial pages

**Use:** Long central article.

**CSS:** `border-left: 1px solid #808080; border-right: 1px solid #808080; padding: 0px 15px`

**Observed:** The column edges extend beside text and gallery figures while the background remains continuous.

**Transfer:** Use when a narrative needs persistent information and proof rails.

## Components

### Identity masthead

**Use:** Opening identity and closing signature.

**CSS:** `color: rgba(0, 0, 0, 0.8); text-align: center; text-transform: uppercase; padding: 33px 18px 15px; border-bottom: 1px solid #808080`

**Text style:** `masthead` — DisplaceKC 400 · 72px/1.2 · uppercase

**Observed:** A centered typographic identity occupies an entire broad band, separate from the navigation cells. The closing instance uses a top rule instead of the opening bottom rule.

**Transfer:** Use the new identity or a very short brand phrase; preserve its sculptural type treatment.

### Navigation cell

**Use:** Primary destinations and compact section tabs.

**CSS:** `padding: 21px 18px 15px; border-bottom: 1px solid #808080; text-align: center; background: #f0f0f0`

**Text style:** `label` — ITCFranklinGothicStdBook 400 · 16px/1.2 · uppercase

**Observed:** Equal-width cells share a row, with fine vertical separators inset slightly from the row edges. The final search cell uses italic serif rather than uppercase sans.

**States:** Declared: hover uses background-image linear-gradient(rgba(0, 0, 0, 0) 50%, grey 0px); focus-visible unknown.

**Transfer:** Use concise noun labels, not explanatory sentences.

### Photographic story card

**Use:** Primary visual proof and browsable stories.

**CSS:** `background: #f0f0f0; padding: 0px 18px; margin-top: 36px; border-radius: 0px`

**Text style:** `story-lead` — PerpetuaTitlingMT 400 · 48px/1.2

**Observed:** A linked photograph precedes a single-line title and a Metadata strip. There is no overlaid copy or separate colored card panel. Smaller widths use story-medium or story-small.

**Transfer:** Map the story to a customer use, product detail or editorial demonstration. Maintain the hierarchy of image, title, classification.

### Metadata strip

**Use:** Classification and date beneath each story.

**CSS:** `border-top: 1px solid #808080; border-bottom: 1px solid #808080; padding: 18px 0px 12px`

**Text style:** `label` — ITCFranklinGothicStdBook 400 · 16px/1.2 · uppercase

**Observed:** Category links align left, separated by vertical strokes; a day.month.year date aligns right.

**Transfer:** Replace with relevant classification and publication information; avoid turning these labels into pills.

### Newsletter line

**Use:** Low-key subscription action in the footer.

**CSS:** `background: transparent; border: 0px; border-bottom: 1px solid #808080; border-radius: 0px; max-width: 125px; text-align: center`

**Text style:** `small-copy` — Garamond 400 · 17px/1.2

**Observed:** A short italic email field sits beneath a serif invitation. It has only an underline, no surrounding input box and no conspicuous filled submit button.

**Transfer:** Keep the prompt human and short; use the same understated field for a mailing list or editorial update.

### Legal text link

**Use:** Fine-print navigation in the colophon.

**CSS:** `color: rgba(0, 0, 0, 0.8); background-image: linear-gradient(rgba(0, 0, 0, 0) 50%, #808080 0px); background-size: 1px 2px; background-position: 0px 90%`

**Text style:** `colophon` — Garamond 400 italic · 17px/1

**Observed:** Italic inline links sit alongside a descriptor and copyright text, with slash separators between groups. Their underline is a fine background treatment.

### Pagination band

**Only for:** multi-page collections

**Use:** Navigating an extensive index.

**CSS:** `background: #f0f0f0; border-top: 1px solid #808080; height: 56px`

**Text style:** `label` — ITCFranklinGothicStdBook 400 · 16px/1.2 · uppercase

**Observed:** Three equal cells place previous navigation at left, numeric page links centrally and next navigation at right. Each cell is centered.

### Editorial contact link

**Only for:** company and service editorial pages

**Use:** Direct human contact and social links in a side rail.

**CSS:** `color: rgba(0, 0, 0, 0.8); text-transform: uppercase; background: transparent; position: relative`

**Text style:** `contact-link` — ITCFranklinGothicStdBook 400 · 24px/1.35 · uppercase

**Observed:** Uppercase sans contact details sit immediately beneath sentence-case serif labels. Long addresses wrap within the narrow rail; social links form a simple vertical list.

**States:** Declared: hover uses background-image linear-gradient(rgba(0, 0, 0, 0) 50%, grey 0px); focus-visible unknown.

### Numbered figure caption

**Only for:** service and process galleries

**Use:** Identify photographs in an editorial gallery.

**CSS:** `background: #f0f0f0; border-bottom: 1px solid #808080; padding: 20px 0px 16px`

**Text style:** `label` — ITCFranklinGothicStdBook 400 · 16px/1.2 · uppercase

**Observed:** A small left-aligned, zero-padded figure number sits between the photograph and its bottom rule. No descriptive headline competes with the image.

**Transfer:** Number a coherent demonstration series while leaving the imagery prominent.

## Imagery and graphics

### Editorial color photography

**Use:** Featured strip and the main story grid; the primary visual proof on new landing pages.

**Observed:** Warm architectural interiors, fashion scenes, designed objects and tactile still lifes alternate between soft daylight and strongly colored theatrical light. A blue bag with flowers and dappled shadows contrasts with an orange-lit performer and a warm curtained bedroom. Images occupy most of each story card, use hard rectangular edges and retain natural shadows and material texture.

**Transfer:** Photograph the new product in a credible environment and include closer material or usage studies. Favor soft window light and a restrained backdrop, with a few concentrated saturated images for contrast. For a nonphysical product, use art-directed human-use scenes and carefully framed demonstrations rather than a wall of generic interface tiles.

### Portrait and editorial essay

**Only for:** company profile pages

**Use:** The main profile image above a long-form narrative.

**Observed:** A large monochrome portrait shows two people facing each other, framed at the upper torso against a plain gray wall. It is a 648×751px image inside the central column, with no decorative mount or overlaid caption.

**Transfer:** Use a deliberately composed grayscale portrait of the people behind the product; keep the plain backing and intimate framing.

### Numbered studio gallery

**Only for:** service and process galleries

**Use:** A central photographic essay that alternates paired portraits with full-width landscapes.

**Observed:** Pairs of 308×462px photographs show a person holding branches and a chair with flowers against pale studio walls. Wider images show objects, working space and people using the space. The palette is cream, gray, beige and natural green, with open diffuse light; a 652px full-width image alternates with half-width pairs.

**Transfer:** Show process, people and artifacts in a coherent light-filled setting. Preserve mixed image aspect ratios and Numbered figure caption construction rather than forcing all pictures into identical cards.

## Section recipes

How recurring sections are built.

### First screen: Editorial front page

**Observed:** On Gray paper, a 170px-high featured strip spans the content frame, showing three compact horizontal image-and-title stories with vertical separators. A small uppercase label sits on the first story's upper-left edge. Beneath it, the Identity masthead occupies a 135px band, centered at 72px; a six-cell Navigation cell row takes another 58px. After 36px of breathing room, two Photographic story cards begin side by side, their 666×444px landscape photographs dominating the lower half of the first screen. Layers are paper, hairline rules, photographs and then typography; text never floats over the large images. Within the first 900px the full featured strip, masthead, navigation and lead photographs are visible; the first 48px titles begin at the bottom edge, while metadata and further rows remain below. There is no supporting sales paragraph or filled hero action; navigation and linked stories provide the actions.

**Transfer:** Use a short sculptural identity and a curated strip of visual proof, followed by two strong demonstrations. Without campaign photographs, create two considered product still lifes or human-use scenes instead. Company and service editorial pages open with a compact 56px utility header, a 72px page-title and ruled column labels above the main image and side rails.

**Avoid:** Do not replace this front page with a centered slogan, long subtitle and pill CTA above a floating product mockup.

**Text style:** `masthead` — DisplaceKC 400 · 72px/1.2 · uppercase

### Descending catalog scale

**Observed:** Photographic story cards move between two-, three- and four-column tiers, with 48px, 40px and 32px titles respectively. Images remain rectangular, rows are separated by 36px and Metadata strip anchors each entry. Vertical hairlines lend the grid the character of newspaper columns.

**Transfer:** Use changes in column size to distinguish lead proof from smaller supporting stories; the number and sequence of rows should suit the content.

### Signature and colophon close

**Observed:** The story finishes at a full-width rule, followed by a 56px transitional band. On collections, Pagination band occupies this area. A 135px signature band repeats Identity masthead. Below, three equal ruled cells contain direct contact, a Newsletter line and social connections; footer content uses 16px uppercase sans and 17px serif copy. A final top rule introduces the small copyright, italic descriptor and Legal text link group. The closing area is 314px on editorial pages and 338px on the index.

**Transfer:** Finish with a substantial typographic signature and practical connection choices. Keep the colophon integrated with the page's paper and rules rather than introducing a new high-contrast sales panel.

### Information and proof rails

**Only for:** company and service editorial pages

**Observed:** A 25/50/25 composition sets contact information to the left, an image and 28px/1.2 serif narrative in the center, and proof to the right. A ruled 56–57px section-label row aligns all columns. The main story has 15px insets and fine vertical boundaries. Information and section headings remain available as the article scrolls.

**Transfer:** Place practical context in the left rail and supporting proof in the right, letting the center carry the narrative. A service presentation can use compact related stories; a company profile can split the proof rail into two narrow lists.

### Literary proof lists

**Only for:** company profile pages

**Observed:** Two 171px columns contain 28px/1.2 serif names and links. Italic category labels divide the lists; linked publication names have fine gray underlines. The list treatment is textual rather than a logo cloud.

**Transfer:** Use categorized third-party references, collaborators or credentials where they substantiate the story.

### Numbered photographic essay

**Only for:** service and process galleries

**Observed:** A central Editorial column alternates pairs of portrait photographs and full-width landscape photographs. Numbered figure caption sits directly below each image; gallery row groups use 72px lower separation. A large centered uppercase email invitation is framed by rules before the gallery.

**Transfer:** Use the essay to show a process or service in tangible detail, with a direct text invitation instead of a conventional button.

## Page flow

**Storyline:** Curated visual invitation → identity and orientation → visual or literary proof → practical connection → signature and colophon.

### An editorial landing page that invites browsing through visual proof

1. **Visual invitation** — A compact horizontal selection of photographed stories precedes the masthead.
2. **Orientation** — A centered identity and evenly ruled destination cells establish the publication.
3. **Demonstration** — Large paired photographs lead into progressively smaller story-grid tiers with titles, classifications and dates.
4. **Continuation** — Previous, numeric and next pagination extend the collection.
5. **Closing connection** — The repeated signature, contact, subscription and social cells end in a fine-print colophon.

**Transfer:** Make the default landing page image-led, using a curated collection of demonstrations or use cases rather than a catalogue of claims.

### A profile page that combines a human portrait with an extended account and external credibility

1. **Identity** — Compact utility header, centered title and column labels.
2. **Human introduction** — A large monochrome portrait leads the central story.
3. **Narrative and proof** — Long serif paragraphs run alongside categorized reference and publication lists, with a contact rail at left.
4. **Closing connection** — The ruled transition and shared signature-colophon ending repeat.

**Transfer:** Use this variant when readers need to understand the people and credentials behind a product.

### A service presentation grounded in a place, process and visible work

1. **Identity** — A short centered title and ruled information, story and featured-work headers.
2. **Service introduction** — A large photographic opener, language tabs, serif description and direct email invitation.
3. **Demonstration** — A numbered mixed-format gallery sits between practical information and related visual work.
4. **Closing connection** — A ruled end to the gallery leads to the common signature and contact colophon.

**Transfer:** Use this variant for a service, process or creative offering with a story substantial enough to need a central essay.

## Writing

Cultured, personal and matter-of-fact, like a small independent design publication. The interface names things plainly; longer writing describes people, work and process with editorial warmth.

**Do not copy:** Do not reuse the brand name, personal names, photography, project titles, contact addresses, client lists, publication names, awards, dates or career claims as the new product's assets or proof. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Navigation is impersonal and noun-led. Editorial biography uses third person; service invitations switch naturally to we and you.
- **Rhythm:** Short noun phrases for labels and story titles contrast with flowing multi-sentence paragraphs. Contact invitations are direct and conversational, not slogan-heavy.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening identity | A concise name or descriptive identity, without a promotional promise. | 2–4 words | “[Brand]”<br>“Creative Studio” |
| Section label | A compact editorial category or utility noun. | 1–3 words | “Featured projects”<br>“Space”<br>“Clients” |
| Story title | Name the subject or place in a magazine-like title. | 2–7 words | “Out of the office”<br>“The Hoxton Poblenou, Barcelona” |
| Service invitation | Ask a simple question, then offer a direct personal next step. | One short question plus one explanatory sentence | “Do you want to work with us? Drop us an e-mail and book our services of photo, video, content creation or art direction.” |
| Subscription prompt | A gentle invitation to stay in touch, followed by an unadorned email field. | 7–10 words | “Get updated, subscribe to Sunday Folio here:”<br>“Your Mail” |
| Utility action | Literal destination or task rather than persuasive CTA copy. | 1–3 words | “Contact us”<br>“Next Page” |

**Words and phrasing to use:** Featured; Info; Connect; Follow us on; Drop us an e-mail; personal vision; creations and projects

**Avoid:** Unlock your potential; game-changing; 10x; frictionless; limited-time offer; revolutionary platform

**Rules:**

- Let visual subjects carry interest; labels should explain where a reader is going.
- Describe concrete work, people and materials before making evaluative claims.
- Keep metadata distinct from narrative: short categories and day.month.year dates in compact uppercase labels.
- Use a human contact invitation for conversion rather than manufactured urgency.

## Do's and Don'ts

### Do

- Keep the interface on #f0f0f0 with #303030 visible lettering.
- Use 1px #808080 rules to define bands and columns.
- Set the identity at 72px and weight 400, with a dedicated band rather than embedding it in a small nav corner.
- Pair 48px story titles with half-width images and 32px titles with quarter-width images.
- Keep images square-edged and generally 3:2 in the index.
- Use 36px story gutters and 18px half-gutter padding.
- Repeat the substantial identity above the three-cell closing colophon.
- Use 28px/1.2 serif text for editorial essays, with italic category labels where lists need subdivision.

### Don't

- Do not introduce colored CTA fills; interface actions are transparent text on gray paper.
- Do not replace classical titling with bold geometric sans headlines.
- Do not add rounded image masks, raised card shadows or floating white panels.
- Do not add wide letter spacing to uppercase labels; their tracking is normal.
- Do not put promotional copy directly on photographs; images and title bands remain separate.
- Do not turn metadata categories into badges; retain their 16px uppercase text and vertical-stroke separators.
- Do not reduce the closing identity to a tiny footer logo; its 72px treatment is a major visual anchor.
- Do not use a logo cloud for the profile proof rail; it uses categorized serif lists.

## Motion and responsive

### Motion

**Observed:**

- Text links declare a fine gray background-image underline on hover.
- No action or surface transition durations are established. A marquee keyframe is declared for the site.

**Transfer:**

- Retain the printed underline response for links.
- If titles continue laterally, keep them within their single-line title window without shifting the card geometry.

**Unknown:**

- Whether and at what speed featured stories or long titles move.
- Focus-visible and active appearances, transition timings and the assignment of declared easing curves.

### Responsive

**Observed:**

- Desktop layouts use two-, three- and four-column story modules and a 25/50/25 editorial split.
- Width breakpoints include 599px, 600px, 782px, 960px, 1103px, 1246px, 1389px and 1440px; additional wide-screen breakpoints also exist.

**Transfer:**

- On narrow layouts, prioritize image, title and metadata as one unit; collapse the editorial rails into sequential content instead of compressing the 28px essay into a tiny middle column.
- Keep the identity and gray-rule vocabulary as the layout simplifies, and preserve natural image aspect ratios.

**Unknown:**

- Exact mobile typography, breakpoint-to-layout mappings, navigation collapse behavior and sticky rail behavior on touch screens.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
