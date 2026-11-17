# Typewolf — a typographer’s sales letter

## Overview

A warm, bookish editorial style with the intimacy of an independent expert’s recommendation. Dusty rose paper, brown-plum ink, narrow high-contrast serif headlines and small heavy sans-serif labels give long product stories a distinctly literary character. Flat product specimens, framed examples and candid customer correspondence carry the visual argument rather than decorative illustration. It suits expert tools, educational products and curated collections that reward sustained reading.

### Essentials

- The landing page reads like a beautifully typeset sales letter: a centered 704px paper panel contains a 608px left-aligned text column, with 48px side padding and 18px/1.45 serif prose.
- A ceremonial masthead precedes the pitch: a centered white serif wordmark in a 415×122px image area, a 24px/1.5 serif tagline, and 14px heavy uppercase navigation beneath a 1px rose rule.
- The hero’s signature is a typographic seal, not a cinematic product render: a 240×240px emblem area above a 46px/1.2 bold narrow-serif title and 28px/1.25 serif lead. Recreate the seal with an original single-glyph medallion when no product symbol exists.
- The shell stays almost entirely pale and tonal: #e6ddde canvas, #f8f5f5 paper, #443235 prose and #654a4e headlines. Stronger colors belong inside bounded product examples rather than full-page marketing bands.
- Conversion is deliberately rectangular and verbal: square-cornered #654a4e buttons, white 14px/1.3 heavy uppercase labels and 18px 20px padding; purchase actions state the price directly.
- Examples look like prints laid on paper: 12px white frames and a rose-tinted 0px 6px 24px shadow, used at 610px reading-column width or in 516px and 234px gallery sizes. If no interface exists, use a real deliverable or a typographic specimen.
- The ending remains useful rather than monumental: a ruled resource footer starts with tightly packed rectangular rose tags, continues into two link columns and a compact newsletter form, and closes with another rule and a small utility line.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep muted plum | `#654a4e` | `--color-heading` | text, action, background | Headings, heavy sans labels, primary buttons and tag hover fills. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dusty mauve | `#916a70` | `--color-rose` | border, action, background, link | Rules, tag fills, active navigation and button hover fills; not a bright highlight. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Print white | `#ffffff` | `--color-white` | text, surface, border | Masthead lettering, framed-image edges, input surfaces and reversed button text. |
| Warm ivory sheet | `#f8f5f5` | `--color-paper` | surface | The central sales-letter panel and inset promotional letter. |
| Pale underline wash | `#f5f1f2` | `--color-link-wash` | border, surface | Inset underline and hover background of links embedded in prose. |
| Dusty rose paper | `#e6ddde` | `--color-canvas` | background | The continuous outer canvas behind the masthead, reading sections and footer. |
| Blush hairline | `#e3d7d7` | `--color-panel-edge` | border | Delicate purchase-box outlines and separators within paper panels. |
| Warm gray edge | `#cfc6c7` | `--color-input-edge` | border | Newsletter input outline. |
| Brown-plum ink | `#443235` | `--color-ink` | text, link | Serif paragraphs and ordinary text links. |

## Typography

- **DomaineDisplayNarrow** — Product titles, editorial headlines and section headings. Narrow, high-contrast serif with a dark, sculpted bold cut and compact editorial proportions. OpenType features: "calt", "clig", "kern", "liga", "onum". If unavailable, use **Bodoni Moda**. Use 700; preserve the narrow headline measure and generous line height. Font stack: "DomaineDisplayNarrow", "Bodoni Moda", Georgia, serif.
- **DomaineText** — Lead paragraphs, long-form prose, link lists and small supporting copy. Readable literary serif with a warm texture and expressive italic. OpenType features: "calt", "clig", "kern", "liga", "onum". If unavailable, use **Newsreader**. Use 400 with optical sizing suitable for text; keep the measured line lengths. Font stack: "DomaineText", "Newsreader", Georgia, serif.
- **Dia** — Navigation, buttons, compact captions, questions and footer labels. Heavy, broad, blunt sans-serif used as a small counterpoint to the dominant serifs. OpenType features: "calt", "clig", "kern", "liga", "lnum". If unavailable, use **Archivo**. Use 900; preserve the tight -0.03em tracking in mixed-case labels. Font stack: "Dia", "Archivo", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | DomaineDisplayNarrow | 700 | 46px | 1.2 | normal | Default product title and inset promotional title. |
| section-heading | DomaineDisplayNarrow | 700 | 36px | 1.2 | normal | Major proof, example and FAQ sections outside the panel; also a directory introduction title. |
| heading | DomaineDisplayNarrow | 700 | 30px | 1.25 | normal | Benefit headings inside the paper panel. |
| lead | DomaineText | 400 | 28px | 1.25 | normal | Large explanatory sentence immediately below the product title. |
| tagline | DomaineText | 400 | 24px | 1.5 | normal | Centered editorial descriptor below the wordmark. |
| body | DomaineText | 400 | 18px | 1.45 | normal | Sales-letter paragraphs, benefits, answers and long quotations. |
| question | Dia | 900 | 18px | 1.3 | -0.03em, features "calt", "clig", "kern", "liga", "onum" | Expanded FAQ question headings. |
| utility-body | DomaineText | 400 | 16px | 1.5 | normal | Footer search guidance and inline links. |
| footer-link | DomaineText | 400 | 16px | 1.4 | normal | Stacked footer resource links. |
| action-label | Dia | 900 | 14px | 1.3 | normal, uppercase | Primary actions and footer group labels. |
| navigation | Dia | 900 | 14px | 2.2 | normal, uppercase, features "calt", "clig", "kern", "liga", "onum" | Centered masthead navigation. |
| small-body | DomaineText | 400 | 14px | 1.5 | normal | Short footer author/support paragraph. |
| tag | Dia | 900 | 13px | 1.3 | -0.03em | Ranked resource tags and compact footer utility text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| collection sales pages | collection-display | DomaineDisplayNarrow | 700 | 58px | 1.2 | normal | A short collection title in the same letter-panel opening. |
| editorial galleries | article-title | DomaineDisplayNarrow | 700 | 42px | 1.2 | normal | Centered multi-line editorial titles below wide images. |
| editorial galleries and directories | gallery-heading | DomaineDisplayNarrow | 700 | 26px | 1.2 | normal | Ruled category titles above four-column lists. |
| editorial galleries and directories | gallery-caption | Dia | 900 | 15px | 1.2 | -0.03em | Centered compact titles underneath category thumbnails. |
| collection sales pages | purchase-note | DomaineText | 400 italic | 14px | 1.45 | normal, features "calt", "clig", "kern", "liga", "lnum" | Centered payment-alternative note directly beneath a purchase button. |

**Notes:**

- Serifs carry both expressive headlines and almost all reading. The sans-serif is heavy even when tiny; do not substitute a light modern UI voice.
- Display and text serifs retain normal tracking. Mixed-case sans captions, questions and tags tighten to -0.03em, while uppercase navigation and action labels use normal tracking.
- Use oldstyle numerals with prose and serif headlines; action labels and ranked tags use lining numerals. The masthead is artwork rather than another headline-size token.

## Layout

**Density:** Comfortable reading within a narrow column; dense resource indexes and footer lists contrast with the wide empty outer margins.

### Spacing

**Spacing system:**

- **horizontal step** 8px, horizontal — The horizontal spacing tendency behind 16px, 24px and 48px offsets; special button and input padding stays independent.

| Value | Use |
| --- | --- |
| 8px | Title-to-lead gap and FAQ question-to-answer separation. |
| 12px | White image frame thickness and tight list/item offsets. |
| 16px | Body paragraph separation and heading-to-benefit content. |
| 24px | Outer column padding and lead-to-body separation. |
| 27px | Top padding of the paper sales panel and FAQ heading top margin. |
| 30px | Benefit-heading top margin. |
| 36px | Bottom padding beneath attributed quotations and purchase-box content. |
| 40px | Collection product separators and stacked example gaps. |
| 48px | Paper-panel side padding, panel clearance beneath navigation and proof-section top margin. |
| 60px | Footer clearance after the preceding content. |
| 84px | Top clearance above the masthead image. |

### Containers and grids

- **outer container**: max width 1128px · side padding 24px. Centered desktop row; inner edges create a 1080px wide masthead rule and footer.
- **sales letter**: max width 704px · side padding 48px. Centered paper panel with a 608px reading measure.
- **proof column**: max width 658px · side padding 24px. Centered unboxed proof and FAQ column with a 610px inner measure, aligned to the paper panel’s text.
- **resource footer**: 2 columns · gap 48px. Two equal 516px content columns within the main inner width.
- **feature gallery** (only for editorial galleries): 2 columns · gap 48px. Two 516px image-and-caption columns.
- **category gallery** (only for editorial galleries and directories): 4 columns · gap 48px. Four 234px framed thumbnails across the 1080px inner width; incomplete final rows remain left aligned.

## Corner radius

| Element | Radius |
| --- | --- |
| paper panel | 4px |
| buttons and framed images | 0px |
| seal and portrait | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| rose paper lift | `0px 6px 24px 0px rgba(145, 106, 112, 0.15)` | Paper panel, framed examples and primary actions share one soft warm shadow. |

### Surfaces

#### Rose canvas · level 0

**Use:** Continuous page background.

**CSS:** `background-color: #e6ddde`

**Observed:** The same field runs through the header, exposed proof sections and footer.

**Transfer:** Keep the shell tonal; let content imagery supply any strong color.

#### Paper letter · level 1

**Use:** Default product narrative and inset promotional pitch.

**CSS:** `background-color: #f8f5f5; border-radius: 4px; box-shadow: 0px 6px 24px 0px rgba(145, 106, 112, 0.15); padding: 27px 48px 24px`

**Observed:** One continuous tall sheet rather than a stack of individual benefit cards.

**Transfer:** Put a coherent explanation and its conversion block on the same sheet.

#### White print frame · level 1

**Use:** Product examples and gallery images.

**CSS:** `border: 12px solid #ffffff; border-radius: 0px; box-shadow: 0px 6px 24px 0px rgba(145, 106, 112, 0.15)`

**Observed:** The frame belongs to the image, while labels remain directly on the rose canvas.

**Transfer:** Treat each example like a flat printed artifact, not a browser floating in perspective.

#### Fine ruled grouping

**Use:** Section boundaries and footer divisions.

**CSS:** `border-top: 1px solid #916a70`

**Observed:** Full-width rules separate groups without a new background fill.

**Transfer:** Use rules to make an index-like hierarchy instead of enclosing every group in cards.

## Components

### Masthead navigation

**Use:** Primary links under the centered wordmark and tagline.

**CSS:** `border-top: 1px solid #916a70; padding-top: 14px; margin-top: 40px; text-align: center; color: #654a4e`

**Text style:** `navigation` — Dia 900 · 14px/2.2 · uppercase

**Observed:** Five compact destinations share a single centered row; links have 19px horizontal list-item padding. The current destination changes to dusty mauve.

**States:** Declared: hover retains deep-plum text and adds a 2px dusty-mauve bottom border; focus-visible unknown; active outline 0px.

**Transfer:** Use a small set of editorial destinations rather than a right-aligned utility bar.

### Primary button

**Use:** Purchase or learn-more action.

**CSS:** `background-color: #654a4e; color: #ffffff; padding: 18px 20px; border: 1px solid transparent; border-radius: 0px; box-shadow: 0px 6px 24px 0px rgba(145, 106, 112, 0.15); text-transform: uppercase`

**Text style:** `action-label` — Dia 900 · 14px/1.3 · uppercase

**Observed:** Content-sized and centered in sales panels. Price is part of the action; learn-more actions use a simple right arrow.

**States:** Declared: hover background #916a70 with white text; focus-visible unknown; active outline 0px.

**Transfer:** Use one explicit action at the end of a substantive explanation, not after every paragraph.

### Inline text link

**Use:** References inside running prose.

**CSS:** `color: #443235; border-bottom: 1px solid #f5f1f2; box-shadow: 0px -3px 0px 0px #f5f1f2 inset`

**Text style:** `utility-body` — DomaineText 400 · 16px/1.5

**Observed:** A pale underline wash sits under the text. Larger prose links inherit the body recipe; explicit purchase and author references also use conventional underlining.

**States:** Declared: hover background #f5f1f2 with text #443235; focus-visible unknown; active outline 0px.

**Transfer:** Keep references sentence-shaped rather than styling every link as a button.

### Ranked resource tag

**Use:** Compact discovery strip at the start of the footer.

**CSS:** `background-color: #916a70; color: #ffffff; padding: 15px 11px 12px; border: 1px solid transparent; border-radius: 0px; margin-bottom: 8px`

**Text style:** `tag` — Dia 900 · 13px/1.3 · tracking -0.03em

**Observed:** Content-width rectangles wrap into tightly spaced rows; each begins with a parenthesized rank and ends with a short title. A final tag links to more.

**States:** Declared: hover background-color #654a4e with white text; focus-visible unknown; active outline 0px.

**Transfer:** Populate this strip with genuine popular resources, use cases or examples for the new product.

### Email field

**Use:** Newsletter signup in the footer.

**CSS:** `background-color: #ffffff; border: 1px solid #cfc6c7; border-radius: 0px; height: 47px; width: 328px; padding: 10.5px`

**Observed:** A plain white rectangular input sits beside a compact dark submit control under a heavy uppercase invitation.

**Transfer:** Keep signup as a small editorial utility, not a modal-sized conversion scene.

### Newsletter submit

**Use:** Action beside the email field.

**CSS:** `background-color: #654a4e; border: 1px solid transparent; border-radius: 0px; height: 47px; padding: 15px 18px 13px; box-shadow: 0px 6px 24px 0px rgba(145, 106, 112, 0.15)`

**Text style:** `action-label` — Dia 900 · 14px/1.3 · uppercase

**Observed:** Narrower and shorter than the main sales action, aligned with the adjacent input.

### Purchase summary

**Use:** Concluding offer inside the product letter.

**CSS:** `border: 1px solid #e3d7d7; padding-top: 8px; padding-bottom: 36px; margin-top: 52px; text-align: center`

**Observed:** The Primary button comes first; a compact bonus-material heading and a centered list of underlined inclusions follow beneath it.

**Transfer:** List tangible inclusions or deliverables with simple type rather than a tier-comparison table.

### FAQ entry

**Use:** Open objection-handling content in the reading column.

**CSS:** `margin-top: 27px; margin-bottom: 8px; color: #654a4e`

**Text style:** `question` — Dia 900 · 18px/1.3 · tracking -0.03em

**Observed:** Heavy sans question followed by full serif paragraphs or bullets; answers are expanded, with no chevrons or accordion boxes.

**Transfer:** Answer real fit, access, price and support questions at the level of detail needed to decide.

### Footer resource link

**Use:** Plain link lists grouped under uppercase labels.

**CSS:** `color: #443235; border-bottom: 2px solid transparent`

**Text style:** `footer-link` — DomaineText 400 · 16px/1.4

**Observed:** Links stack in short groups with about 26px row pitch, without bullets.

**States:** Declared: hover bottom border 2px solid #916a70; focus-visible unknown; active outline 0px.

### Category thumbnail

**Only for:** editorial galleries and directories

**Use:** Small discovery cards grouped under ruled headings.

**CSS:** `border: 12px solid #ffffff; border-radius: 0px; box-shadow: 0px 6px 24px 0px rgba(145, 106, 112, 0.15); max-width: 100%`

**Text style:** `gallery-caption` — Dia 900 · 15px/1.2 · tracking -0.03em

**Observed:** Image above a centered one- to three-line heavy sans caption, with roughly 11px visual separation. The surrounding item has no card fill.

**Transfer:** Use a legible detail of the deliverable rather than a generic symbolic icon.

## Imagery and graphics

### Typographic seal

**Use:** The signature emblem at the beginning of a product letter.

**Observed:** A dusty-mauve circle contains an elegant white ampersand, centered above the left-aligned title. The square image area is 240px; the visible circle occupies most, but not all, of it.

**Transfer:** Create an original one-glyph or one-monogram seal with the same contrast and restraint. It must serve as the page’s central graphic even for a product with no visual interface.

**Build:** Use a 240px square flex container with a centered roughly 200px circle filled #916a70. Place a white high-contrast serif glyph inside, vertically balanced with optical rather than mathematical alignment. Use an SVG text outline or a font glyph; no rings, texture or extra badges.

### Flat product specimens

**Use:** Visual proof in the narrow reading column and editorial galleries.

**Observed:** Flat, front-facing examples of designed pages and interfaces, often tightly framed around typography. Product examples are stacked at 610px width; gallery images use 516×319px or 234×150px framed boxes. White edges and a soft rose shadow distinguish them from the canvas.

**Transfer:** Show real output, a document, a working interface or a clearly typeset example. Keep it flat and legible; if no interface is available, make a useful sample artifact in the new product’s own content.

### Customer correspondence

**Use:** Social proof after the pitch and in inset promotional letters.

**Observed:** A vertical sequence of white email-message images retains recognizable mail headers, dates and irregular paragraph lengths; identities are softened. Some social proof retains the native social-post card styling. Authored quotations instead sit directly on rose paper with a small circular portrait and a bottom rule.

**Transfer:** Use authorized genuine messages with personal details protected, or typeset attributed customer quotations on the canvas. Keep the candid documentary tone and varied lengths rather than converting all proof into identical review tiles.

### Collection covers and bundle

**Only for:** collection sales pages

**Use:** Individual offers and a concluding collection offer.

**Observed:** Large 608×456px landscape covers rely almost entirely on expressive centered lettering and flat fields: black, dusty pink, olive, peach and blue. The bundle combines cover rectangles with a white circular savings badge overlapping the center; these are product artwork colors, not page themes.

**Transfer:** Create covers from each new deliverable’s own title and visual identity. A minimal acceptable bundle uses real cover thumbnails in a flat collage plus one truthful offer badge.

**Build:** Compose a 4:3 SVG with two equal upper rectangles and three lower rectangles; overlap a larger central lower cover. Overlay a white circle at the center seam containing two centered heavy-sans lines for the offer. Keep edges square, fills flat and all decorative type inside the artwork.

### Icons

**Observed:** Interface iconography is sparse. A plain right-arrow glyph ends calls to action; a small heart appears in the provenance-style footer utility line. Portraits are circular rather than enclosed in decorative icon containers.

**Transfer:** Prefer typographic arrows and simple inline symbols. Benefits should be explained with headings and bullets, not an icon grid.

## Section recipes

How recurring sections are built.

### First screen: Sealed sales-letter opening

**Observed:** The Rose canvas backs a ceremonial centered masthead. A white serif wordmark occupies a 415×122px image area after 84px of top space, with the tagline immediately below. A 1080px rose rule and centered Masthead navigation finish the header at 329px. After 48px, the 704px Paper letter begins with its centered 240px Typographic seal area, then the left-aligned 46px/1.2 title across the 608px text measure, an 8px gap and a 28px/1.25 lead. The first 900px show masthead, navigation, seal, title, lead and the beginning of 18px body prose; the benefit explanation, product examples and purchase action lie below the fold. Layers are canvas, soft panel shadow, ivory sheet, flat seal, then type. There is no adjacent product render or hero button pair.

**Transfer:** Default to this reading-first product opening. Write a title short enough to sit comfortably in the text measure and create an original glyph seal if the product has no emblem. Collection sales openings use the 58px collection title; editorial directories instead open directly on the rose field with a 36px title and compact introduction, while galleries lead with framed examples.

**Avoid:** Do not turn the opening into a split-screen SaaS hero, put the title at giant billboard scale or force an above-fold purchase button into the letter.

**Text style:** `display` — DomaineDisplayNarrow 700 · 46px/1.2

### Benefit chapters on one sheet

**Observed:** Within Paper letter, benefit headings use 30px/1.25 bold narrow serif, 30px top margin and 16px bottom margin. Supporting 18px/1.45 prose and rose bullet dots remain left aligned in the same measure. Chapters share the sheet instead of separate cards.

**Transfer:** Explain practical outcomes and how the product works with short headed passages and concrete bullet details.

**Text style:** `heading` — DomaineDisplayNarrow 700 · 30px/1.25

### Offer and inclusion box

**Observed:** Purchase summary concludes the long product explanation with a centered Primary button and a compact list of bonus deliverables. Collection offers use repeated cover-plus-button blocks separated by a 1px blush hairline and 40px clearance, followed by a bundle collage and payment note.

**Transfer:** Match offer structure to the product: one inclusion box for a single tool, repeated flat covers for separately purchasable deliverables.

### Exposed proof column

**Observed:** Outside the paper panel, a 610px inner measure sits directly on Rose canvas. Section-heading titles introduce stacked customer messages, authored quotations or White print frame examples; example stacks have roughly 31px separation. Quotations end with a fine rule and compact portrait attribution.

**Transfer:** Make proof tactile and readable: genuine correspondence, actual examples and specific attributed comments rather than abstract trust logos.

**Text style:** `section-heading` — DomaineDisplayNarrow 700 · 36px/1.2

### Open FAQ essay

**Observed:** A 36px section title precedes FAQ entry questions. Answers use 18px serif paragraphs with 16px separation, sometimes several paragraphs and bullets. The reading column remains exposed on the rose canvas all the way to the final answer.

**Transfer:** Use as much detail as necessary to resolve purchase objections, ending with a clear answer on satisfaction or support rather than an invented oversized closing CTA.

**Text style:** `question` — Dia 900 · 18px/1.3 · tracking -0.03em

### Ruled discovery gallery

**Observed:** A 26px heading shares a full-width 1px top rule with 24px top and 12px bottom padding. Category thumbnail items form four columns; larger editorial entries use two columns and 42px centered serif Article-title text. Labels stay outside frames.

**Transfer:** Use this as a scoped browsing format for resources, use cases or an editorial library rather than the default product-benefit layout.

**Text style:** `gallery-heading` — DomaineDisplayNarrow 700 · 26px/1.2

### Promotional letter inset

**Observed:** A centered Paper letter within a browsing page carries a 46px product title, 28px lead, a 608px example image, a centered learn-more action and several customer-message images beneath it.

**Transfer:** Promote one substantial offer within a catalog using the same editorial letter language as the main landing page.

### Resource-rich ending

**Observed:** A 60px clearance leads to a 1080px ruled footer. Ranked resource tags wrap into two rows beneath an uppercase label. A short search-guidance sentence and rule lead into two columns of link groups, a small author/support note with circular portrait, newsletter form and social links. A small flat merchandise image sits near the social group. A final rule separates a compact utility row; the footer is about 893px tall at desktop.

**Transfer:** Always retain the compact discovery strip, useful grouped links and newsletter utility. Adapt the author/support area to the new product’s real operator; a small product artifact can replace merchandise without changing the footer’s editorial scale.

## Page flow

**Storyline:** editorial identity → promise or discovery → substantive explanation → tangible proof → offer and reassurance → useful resource ending

### Single-product expert-led landing page

1. **Identity** — Centered wordmark, tagline and ruled navigation.
2. **Promise** — Sealed Paper letter with title, large lead and a personal problem statement.
3. **Capability chapters** — Long-form benefit headings, explanations and practical bullets.
4. **Offer** — Centered purchase summary with included deliverables.
5. **Social proof** — Customer correspondence followed by attributed expert quotations.
6. **Product demonstration** — Stacked framed examples of the product and its output.
7. **Objection handling** — Fully expanded FAQ ends with satisfaction reassurance.
8. **Resource ending** — Ranked tags, discovery links, newsletter and utility footer.

**Transfer:** Use the depth of a personal sales letter for a product whose value needs explanation; shorten the number of chapters without losing the typographic seal, readable prose and tangible proof.

### Collection sales page

1. **Promise** — Same sealed letter with a larger short collection title and explanatory lead.
2. **Problem and solution** — Personal research-friction story followed by concise benefit chapters.
3. **Offer** — Flat individual covers, explicit-price buttons and payment alternatives, then a bundle collage.
4. **Product demonstration** — Framed full-size examples stacked on the exposed canvas.
5. **Social proof** — Customer email images.
6. **Objection handling** — Expanded practical FAQ through the last payment/access answer.
7. **Resource ending** — Shared ranked discovery footer and newsletter.

**Transfer:** Use for a family of related downloadable or creative deliverables; let the cover artwork vary while the shell remains unchanged.

### Editorial discovery portal

1. **Identity** — Shared centered masthead.
2. **Discovery** — Two-column stream of framed examples with compact title, date and supporting metadata.
3. **Editorial depth** — Two-column article images with large centered serif titles.
4. **Related offers** — Paired guide thumbnails and a compact collection action.
5. **Categorized discovery** — Ruled four-column category galleries.
6. **Offer and proof** — Inset promotional letter with real example and customer messages.
7. **Resource ending** — Shared ruled tag strip, links and subscription footer.

**Transfer:** Use when browsing examples is the primary job; preserve visual variety inside strict white image frames.

### Curated directory

1. **Orientation** — Shared masthead followed by a 36px serif title and short explanation directly on the canvas.
2. **Categorized discovery** — Repeated ruled category headings and four-column thumbnail lists.
3. **Related offer** — Inset promotional letter with product example, action and customer messages.
4. **Resource ending** — Shared complete footer.

**Transfer:** Use for resource indexes and recommendation hubs, not as a substitute for the default sales-letter opening.

## Writing

A knowledgeable independent maker speaking candidly to a fellow practitioner. The tone is explanatory, personal and strongly opinionated, with confidence grounded in detailed work rather than corporate slogans.

**Do not copy:** Do not reuse the Typewolf name, logo, ampersand artwork, product titles, customer names or messages, prices, audience numbers, research totals, guarantees or performance claims. Source examples illustrate cadence only; replace them with truthful product-specific content and authorized proof.

- **Addressing the reader:** Address the reader as you. Use I for the maker’s experience and decisions; name the product plainly rather than relying on an anonymous corporate we.
- **Rhythm:** Short noun-based product titles contrast with full-sentence benefit headings and extended, readable paragraphs. Questions sound like the buyer’s actual concerns; action labels are terse. Parentheses, em dashes and occasional italics create a conversational essay cadence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Product title | Name the concrete deliverable rather than making an abstract transformation claim. | 3–5 words | “Flawless Typography Checklist”<br>“Type Pairing Lookbooks” |
| Supporting line | Explain both the format and what it helps the reader do. | One full explanatory sentence | “A typography master course that doubles as an interactive visual reference that helps you achieve flawless type on every design project” |
| Benefit heading | Lead with a practical outcome or an explicit improvement in workflow. | 5–18 words | “Font research done for you”<br>“Learn from visual examples that show what to do (and what not to do)” |
| Objection heading | Ask the exact question a cautious buyer would ask. | One direct question | “What if I’m too busy to go through the course?”<br>“How does purchasing work? Is it secure?” |
| Primary action | State the transaction and price, or a plain next step followed by an arrow. | 2–4 words plus price or arrow | “Purchase for $39”<br>“Learn More →” |

**Words and phrasing to use:** practical; visual examples; research; reference; pair; learn; use; included; one-time purchase; how does it work

**Avoid:** revolutionary; unlock limitless potential; supercharge; seamless ecosystem; disrupt; AI-powered magic

**Rules:**

- Explain why the product exists through a recognizable work problem, then show the concrete format of the solution.
- Use quantified details only when verifiable, and place them inside explanations rather than giant statistical displays.
- Let FAQs include limitations, access details, purchase mechanics and fit; reassurance is strongest when specific.
- Use bullets for tangible inclusions and useful outcomes, not a string of vague adjectives.

## Do's and Don'ts

### Do

- Keep default landing-page titles at 46px/1.2 in the bold narrow serif.
- Use a 608px reading measure within a 704px ivory sheet.
- Retain the 240px emblem area as a strong typographic opening device.
- Set sustained prose at 18px/1.45 and separate paragraphs by 16px.
- Use the same rose-tinted 0px 6px 24px shadow for panels, prints and primary actions.
- Frame visual examples with 12px white borders while leaving their captions outside.
- Keep footer discovery tags square, compact and 13px heavy sans.
- Keep expanded FAQ questions at 18px/1.3 with -0.03em tracking.

### Don't

- Do not turn the shell into white-on-black sections; its continuous #e6ddde field is part of the identity.
- Do not introduce pill buttons or rounded image cards; actions and print frames use 0px corners.
- Do not set prose in the sans-serif; reserve its 900 weight for compact functional text.
- Do not add colored benefit-card fills; benefit chapters share the #f8f5f5 paper sheet.
- Do not set headings with aggressive negative tracking; the serif recipes use normal tracking.
- Do not float example images at perspective angles or add glossy device-stage lighting.
- Do not replace the useful two-column footer with an isolated giant slogan.
- Do not use the collection cover colors as competing full-width marketing backgrounds.

## Motion and responsive

### Motion

**Observed:**

- Primary actions and ranked tags declare background-color 0.3s ease-out transitions.
- Framed images declare box-shadow 0.4s ease-out transitions.
- Inline links declare background 0.4s ease-out; many short text links declare 0.3s ease-out.
- Email fields declare box-shadow 0.5s and border-color 0.3s ease-in-out. No keyframe animation is declared.

**Transfer:**

- Keep motion confined to the paper, underline and color feedback of interactive elements; the editorial composition does not need an animated entrance.

**Unknown:**

- Focus-visible styling and actual interaction playback are not established. Do not infer scroll choreography.

### Responsive

**Observed:**

- The layout declares small-up-1 and medium-up-2 for editorial galleries, and small-up-2 with medium-up-4 for category galleries.
- Shared styles declare width boundaries including 500px, 600px, 640px, 960px, 1024px and 1200px.

**Transfer:**

- Preserve the reading-column hierarchy as the viewport narrows: reduce outer margins before changing the serif/sans relationship.
- Use a single column for the two-column editorial gallery and two columns for compact category galleries. Keep frames, captions and letter-panel padding proportional to the available width.

**Unknown:**

- Exact narrow-screen title sizes, masthead behavior, navigation wrapping and paper-panel padding are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
