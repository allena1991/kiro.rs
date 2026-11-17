# Fidèle Éditions — blue ink, living paper

## Overview

A paper-warm editorial storefront with electric blue typography and exuberant physical imagery. Regular grotesk lettering meets a literary serif in compact headlines, while photographs of objects, people and working materials provide nearly all the other color. The result feels like an independent cultural publication: dense at the edges, expansive around the artwork, and direct rather than promotional.

### Essentials

- The first impression is an editorial shelf, not a billboard: a 70px navigation strip, 36px blue announcement, 41px identity sentence and 62px heading lead directly into square object images.
- Headlines change register within a phrase: regular grotesk at 62px/0.92 with -1px tracking meets an upright literary serif at 62px/0.92 with normal tracking.
- The interface behaves like blue ink on paper: #1664eb text and thin rules over #f8f7ef; large saturated areas belong to imagery, apart from the narrow announcement strip and monumental identity artwork.
- Products sit on a continuous shelf rather than inside raised cards: square #e2e2df image fields, square corners, compact 14px titles and 16px prices immediately underneath.
- Actions remain editorial: underlined 32px/1.5 text with a 25px right arrow, not pill buttons; the scoped contact form uses a flat 40px rectangular submit bar.
- Identity becomes an object at page scale: include a full-width blue word sculpture in a 1411px by 375px field and a bold geometric emblem alongside factual footer text. Fit a new short identity to the same silhouette if no existing artwork is available.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue ink | `#1664eb` | `--color-ink` | text, accent, background, link, action, border | Default interface ink, rules, identity graphics and narrow announcement fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Editorial link blue | `#006ce5` | `--color-link-blue` | link, action | Large underlined story links. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Object field grey | `#e2e2df` | `--color-object-field` | surface | Square product-image backing. |
| Warm paper | `#f8f7ef` | `--color-paper` | background, surface | Default marketing canvas and header. |
| Warm white lettering | `#fdf9f9` | `--color-announcement-text` | text | Announcement lettering on the blue strip. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| studio and contact pages | Studio charcoal | `#1e1e1e` | `--color-charcoal` | background, text | Full-page studio/contact background and submit lettering. |
| catalog pricing | Previous price grey | `#9b9b9b` | `--color-old-price` | text | Crossed-out comparison prices. |
| studio and contact pages | Studio grey ink | `#b0afac` | `--color-studio-grey` | text, border, action | Type, graphic artwork, form rules and submit fill against charcoal. |
| catalog pages | Base paper | `#f8f7ee` | `--color-base-paper` | background | Underlying page canvas; exposed across the edge-to-edge catalog. |

## Typography

- **BaselGrotesk** — Headlines, paragraphs, navigation, captions and prices; Book and Regular are the normal cuts, Bold is reserved for identity emphasis and selected navigation. Open, matter-of-fact grotesk with compact line spacing and little weight contrast. If unavailable, use **Inter**. Use 400 for most text and 700 only for emphatic identity or selected states. Font stack: "BaselGrotesk", "Inter", Arial, sans-serif.
- **OTMagisterUnlicensedTrial** — Literary words inside headline pairs and small form actions. Upright, contrasty editorial serif; it supplies a change of voice without changing size. If unavailable, use **Libre Caslon Display**. Use 400; adjust word length through copy rather than heavy tracking. Font stack: "OTMagisterUnlicensedTrial", "Libre Caslon Display", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | BaselGrotesk | 400 | 62px | 0.92 | -0.0161em | Default major section heading and the grotesk half of mixed-family headings. |
| heading-serif | OTMagisterUnlicensedTrial | 400 | 62px | 0.92 | normal | Emphasized subject in a mixed-family section heading. |
| identity-line | BaselGrotesk | 400 | 41px | 0.92 | normal | Single-line opening identity statement adjoining a compact wordmark. |
| statement | BaselGrotesk | 400 | 36.8px | 0.96 | normal | Broad editorial statements between media sections. |
| story-link | BaselGrotesk | 400 | 32px | 1.5 | normal | Underlined editorial action with right arrow. |
| footer-intro | BaselGrotesk | 400 | 32px | 0.92 | normal | Footer identity sentence. |
| footer-identity | BaselGrotesk | 700 | 32px | 0.92 | normal | Bold name starting the footer identity sentence. |
| body | BaselGrotesk | 400 | 28px | 1 | normal | Story introductions and short support paragraphs. |
| navigation | BaselGrotesk | 400 | 22px | 1.3 | normal | Compact header links. |
| footer-text | BaselGrotesk | 400 | 22px | 1 | normal | Footer practical information and links. |
| eyebrow | BaselGrotesk | 400 | 19.3px | 1 | 0.023em, uppercase | Centered labels for paired update columns. |
| card-meta | BaselGrotesk | 400 | 16px | 1 | normal | Landing-page authors, prices and announcement text. |
| card-title | BaselGrotesk | 400 | 14px | 1 | normal | Titles under landing-page product images. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| studio and contact pages | studio-heading | BaselGrotesk | 400 | 54.3px | 0.92 | -0.0184em | Centered two-line studio description beneath an identity graphic. |
| catalog pages | catalog-tab | BaselGrotesk | 500 | 32px | 1 | normal | Unboxed catalog categories; selected category becomes bold. |
| studio and contact pages | submit | OTMagisterUnlicensedTrial | 400 | 28px | 1 | -0.0357em | Single word on the flat submit bar. |
| catalog pages | catalog-title | BaselGrotesk | 400 | 22.4px | 1 | normal | Two-line product title and creator block. |
| studio and contact pages | form-copy | BaselGrotesk | 400 | 19.3px | 1 | normal | Centered form introduction and field labeling. |
| catalog pages | catalog-price | BaselGrotesk | 500 | 16px | 1.1 | normal | Current price aligned to the right of product metadata. |

**Notes:**

- Keep the regular weight and compressed leading even at display sizes; hierarchy comes from size, placement and family rather than a ladder of bold weights.
- The serif emphasis is upright, not an italic substitute. It can sit inline after a colon or on a slightly indented second line.
- The monumental closing identity is vector artwork, not a paragraph heading. Fit its outline to the wide identity field rather than using the ordinary heading recipe.

## Layout

**Density:** Compact editorial density: narrow outer margins and small caption gaps alternate with large image fields and unoccupied paper.

### Spacing

| Value | Use |
| --- | --- |
| 2px | Catalog grid seams. |
| 5px | Landing product metadata side inset. |
| 6.4px | Gaps within catalog price groups. |
| 12px | Catalog metadata padding and category spacing. |
| 14.4px | Desktop marketing-page side inset. |
| 16px | Repeated flex gaps and equal-column separation. |
| 21px | Default section top and bottom padding. |
| 42px | Extra separation above paired updates. |
| 80px | Breathing space between the opening product shelf and process video. |

### Containers and grids

- **page-edge**: max width 1440px · side padding 14.4px. Nearly full-bleed desktop marketing composition; images occupy 1411px of the 1440px window.
- **editorial-pair**: 2 columns · gap 16px. Equal image and text columns, approximately 698px each; align their tops.
- **catalog-grid** (only for catalog pages): 3 columns · gap 2px · side padding 0px. Edge-to-edge square imagery with compact metadata below each image.
- **studio-grid** (only for studio and contact pages): 3 columns · gap 28px · side padding 14.4px. Three equal 452px columns: informational artwork, monochrome photograph, informational artwork.
- **studio-intro** (only for studio and contact pages): max width 1100px · side padding 14.4px. Centered identity and introductory statement.
- **contact-form** (only for studio and contact pages): max width 690px · gap 14px. Centered single-column form below oversized calligraphic artwork.

## Corner radius

| Element | Radius |
| --- | --- |
| product fields and actions | 0px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing page and navigation.

**CSS:** `background-color: #f8f7ef; color: #1664eb`

**Observed:** Untextured warm paper; blue horizontal rules separate editorial chapters.

**Transfer:** Let material texture live in photographs, not as a distressed background overlay.

#### Object backing · level 0

**Use:** Product image fields.

**CSS:** `background-color: #e2e2df; border-radius: 0px; box-shadow: none`

**Observed:** A continuous neutral field behind isolated objects; apparent shadows belong to the photographed objects.

**Transfer:** Match backing color across assets to make adjacent tiles read as a shelf.

#### Announcement band · level 0

**Use:** Short transactional message near the top.

**CSS:** `background-color: #1664eb; color: #fdf9f9; padding: 10px 14.4px`

**Observed:** A narrow full-width strip, not a second hero panel.

**Transfer:** Use for one useful condition or timely notice.

#### Charcoal studio canvas · level 0

**Only for:** studio and contact pages

**Use:** Alternative full-page studio/contact theme.

**CSS:** `background-color: #1e1e1e; color: #b0afac`

**Observed:** The dark theme continues through header, forms and footer rather than becoming an isolated dark card.

**Transfer:** Keep photographs monochrome and form outlines grey within this theme.

## Components

### Sticky navigation

**Use:** Persistent page orientation.

**CSS:** `position: sticky; top: 0px; z-index: 100; height: 70px; background-color: #f8f7ef; padding: 0px 14.4px; display: grid; grid-template-columns: 1fr auto 1fr; column-gap: 32px; align-items: center`

**Text style:** `navigation` — BaselGrotesk 400 · 22px/1.3

**Observed:** Three plain links at left, compact mixed-family identity in the center, language selector plus search and shopping bag at right. The dark variant uses grey navigation and suppresses the central identity.

**Transfer:** Keep the small editorial navigation, substituting a few meaningful destinations rather than a broad mega-menu.

### Announcement strip

**Use:** Useful compact notice above the identity sentence.

**CSS:** `background-color: #1664eb; color: #fdf9f9; padding: 10px 14.4px; text-align: center`

**Text style:** `card-meta` — BaselGrotesk 400 · 16px/1

**Observed:** One centered line with globe symbols bracketing the message.

**Transfer:** Keep a single concrete condition; the small symbols may reflect the message.

### Shelf product card

**Use:** Landing-page selection of products or outputs.

**CSS:** `display: flex; flex-direction: column; border-radius: 0px`

**Text style:** `card-title` — BaselGrotesk 400 · 14px/1

**Observed:** Square Object backing above a paper metadata strip. Title and creator are left aligned; price sits at upper right. Default opening images are 316px square; focused series images are 351px square. A horizontal shelf reveals part of its next item.

**Transfer:** For a nonphysical product, use a carefully framed artifact or output image rather than an abstract feature icon.

### Editorial arrow link

**Use:** Main story action, without a button container.

**CSS:** `color: #006ce5; padding: 0px 35px 0px 0px; line-height: 48px; text-decoration: underline; background-size: 25px auto; background-position: 100% 50%; background-repeat: no-repeat; transition: 0.3s`

**Text style:** `story-link` — BaselGrotesk 400 · 32px/1.5

**Observed:** An outlined right arrow is placed after the underlined label; it is separate artwork, not an inline emoji.

**States:** Declared: hover fills blue and switches lettering and arrow to warm white, with a 5px underline offset; focus-visible adds an outline and layered focus shadow; active lettering returns to blue.

**Transfer:** Use a simple 25px SVG arrow in current ink and keep labels short.

### Practical footer

**Use:** Close the page with identity and usable contact information.

**CSS:** `background-color: #f8f7ef; color: #1664eb; padding: 21px 14.4px`

**Text style:** `footer-text` — BaselGrotesk 400 · 22px/1

**Observed:** A compact 299px desktop block: legal list at left, 210px emblem in the middle, and a broad right area with a 32px identity sentence over a thin blue rule. Two practical-information columns follow, with direct underlined email and phone links. Copyright anchors the lower left and credits close the right. The studio theme retains this composition in grey on charcoal.

**Transfer:** Use an original emblem and a concise identity sentence, then factual contact, availability and location details rather than a conversion slogan.

### Catalog category links

**Only for:** catalog pages

**Use:** Switch among product groups.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: center; gap: 12px`

**Text style:** `catalog-tab` — BaselGrotesk 500 · 32px/1

**Observed:** Centered text-only categories below the navigation; selection is bold rather than boxed or underlined.

**Transfer:** Use a small set of plain category names.

### Underlined form field

**Only for:** studio and contact pages

**Use:** Single-line contact inputs.

**CSS:** `height: 37px; padding: 6px 0px; border: 0px; border-bottom: 2px solid #b0afac; background: transparent; color: #b0afac; border-radius: 0px`

**Text style:** `form-copy` — BaselGrotesk 400 · 19.3px/1

**Observed:** Labels remain visible on the dark ground. The multiline message field changes to a complete rectangular outline and is 132px tall.

**Transfer:** Retain the unboxed line treatment for short fields and a full outline only for the message.

### Submit bar

**Only for:** studio and contact pages

**Use:** Final contact-form action.

**CSS:** `height: 40px; width: 690px; padding: 4px 10px; background-color: #b0afac; color: #1e1e1e; border: 2px solid #b0afac; border-radius: 0px; transition: 0.3s`

**Text style:** `submit` — OTMagisterUnlicensedTrial 400 · 28px/1 · tracking -0.0357em

**Observed:** Full form-width action immediately below the message area; serif text distinguishes it from the grotesk labels.

**States:** Declared: hover changes fill to warm paper and text to blue; focus-visible adds an outline and layered focus shadow.

**Transfer:** Keep the label a single verb and make the bar follow the form width on narrow screens.

## Imagery and graphics

### Physical object shelf

**Use:** Opening product selection and smaller focused grids.

**Observed:** Front-facing books, prints, tote bags and garments sit centered in square pale-grey fields, with modest realistic shadows and generous space around their outlines. Artwork remains brightly colored; there is no global blue duotone.

**Transfer:** Photograph the new product or its tangible output front-on under soft even light. The minimum equivalent is a clean cutout with a subtle contact shadow on the shared grey field.

### Process and material photography

**Use:** Wide visual interludes and half-width editorial stories.

**Observed:** Hands at machinery, a taped shipping carton, fan-arranged colored paper, portraits and shelves of repeated colorful objects. Images retain incidental studio surroundings, paper grain and natural light. A material fan nearly fills a 1411px by 859px field; portrait and press imagery occupy roughly half the page.

**Transfer:** Use close photographs of tools, ingredients, packaging or outputs that reveal how the product is made. Preserve believable clutter and tactile detail rather than replacing them with polished floating renders.

### Monumental identity artwork

**Use:** A signature identity punctuation before the practical footer.

**Observed:** Heavy blue sans lettering occupies almost the full width, with a low, broad silhouette in a 1411px by 375px field. It is separate from ordinary text hierarchy.

**Transfer:** Fit a short original name or product word to the wide field; if no identity exists, use a short bold typographic word sculpture with equivalent visual mass.

**Build:** Create an SVG with a 1411 by 375 viewBox; set one short word in a heavy grotesk, convert to outlines, and scale uniformly to the widest fit with minimal internal margins. Fill with #1664eb over #f8f7ef; use no texture, outline or shadow.

### Geometric ink emblem

**Use:** Signature graphic punctuation beside a photograph and within the footer.

**Observed:** A flat blue, thick-bar star-like identity symbol on warm paper, displayed at large scale opposite a carton photograph and at 210px square in the footer.

**Transfer:** Develop an original simple mark with comparable mass and few straight-edged parts; it must still read at footer size.

**Build:** Use an SVG square field with a few equal-width rectangular bars intersecting around one center. Combine orthogonal and diagonal directions, trim outer ends square, and merge to one flat #1664eb silhouette. Keep surrounding negative space generous; use #b0afac for the dark-theme version.

### Studio monochrome and lettering

**Only for:** studio and contact pages

**Use:** Informational studio panels and contact heading.

**Observed:** A monochrome close-up of printed matter sits between typographic panels: one uses stacked serif letter tiles, the other an angled handwritten location label. A wide flowing calligraphic contact line spans above the form in grey on charcoal.

**Transfer:** Use one documentary monochrome image and original typographic sign artwork. Avoid requiring a custom illustration: composed letter tiles and a freely available calligraphic face are sufficient.

**Build:** Compose serif letter tiles as small grey rectangles with charcoal glyphs in a staggered rising stack. For a contact sign, set a short phrase in an elegant script, convert to SVG outlines and fit within a 1129px by 217px field using #b0afac without effects.

### Icons

**Observed:** Blue utility symbols in the header: small filled chevron in a 16px by 10px box, search in a 32px square, and shopping bag in a 44px by 70px box. Despite SVG fill implementation, visible search and bag contours read as fine outlines. Studio utilities use grey.

**Transfer:** Choose fine, unembellished search and bag outlines and a small downward chevron; keep them secondary to text and identity.

## Section recipes

How recurring sections are built.

### First screen: Editorial shelf opening

**Observed:** Warm paper sits behind a 70px Sticky navigation. Below it, the 36px Announcement strip and a 46px identity row compress the brand introduction into the top of the screen. A compact bold name precedes a 41px identity sentence. The next heading is left aligned at 62px, with a grotesk prompt and serif subject on the same line. A shelf of 316px square object images stretches across the page within 14.4px side margins, showing four complete items and part of the next. Small title/creator and price lines sit directly below. A thin blue horizontal rule then leads to a broad process-video image; its upper portion is already visible within the first 900px, while most of that media lies below. There is no separate filled hero CTA: object cards and navigation provide the immediate actions.

**Transfer:** Lead with a short category identity and a curated shelf of tangible outputs. If no physical product exists, make convincing artifact panels showing results, documents or deliverables. Catalog pages open with centered categories and the three-column grid instead; studio/contact pages open with a centered identity graphic and the studio-heading on charcoal.

**Avoid:** Do not turn the opening into a centered slogan with two pill CTAs, a floating dashboard and a large empty gap before the products.

**Text style:** `heading` — BaselGrotesk 400 · 62px/0.92 · tracking -0.0161em

### Mixed-family heading pair

**Observed:** The heading and heading-serif share 62px size and 0.92 leading. A short grotesk introduction precedes the serif subject, either inline or on an indented second line above body copy.

**Transfer:** Make the grotesk phrase an editorial prompt and the serif phrase the new subject or release.

**Text style:** `heading` — BaselGrotesk 400 · 62px/0.92 · tracking -0.0161em

### Image and editorial introduction

**Observed:** Editorial-pair layout places a large portrait on the left and a mixed-family heading, 28px support paragraph and Editorial arrow link on the right. Both columns align at the top; a blue rule marks the section boundary.

**Transfer:** Pair a person, process or product image with a short contextual story rather than a long benefits checklist.

### Paired updates

**Observed:** Two equal text columns use centered uppercase eyebrow labels, then left-aligned compact 28px announcements and smaller underlined practical links. Section padding is 42px above and 21px below.

**Transfer:** Use the pair for two timely news items, availability notes or concise capability updates; keep the subject matter flexible.

### Material proof interlude

**Observed:** A nearly full-width photograph occupies a 1411px by 859px field with 21px section padding. Color and texture come from real materials rather than a decorative page background.

**Transfer:** Show one visually rich detail that proves the product's craft or construction.

### Focused selection

**Observed:** A large left-aligned heading introduces a centered two-by-two group of Shelf product cards. Images are 351px square, with much more paper around the compact grid than around the opening shelf.

**Transfer:** Give a small coherent product family or related output set a more intimate presentation without stretching cards to fill the page.

### Identity and factual close

**Observed:** Monumental identity artwork provides a broad blue final punctuation, followed by the Practical footer. Catalog pages instead allow 100px breathing space after the last grid row and go directly to that footer. The studio version closes with a form and the dark footer, without the wide blue identity band.

**Transfer:** Keep a strong identity punctuation on marketing pages and a useful factual ending across all page types; place the signature artwork where it best supports the new story.

### Studio information and contact

**Observed:** On the Charcoal studio canvas, a centered identity graphic and studio-heading lead into three columns of informational artwork and monochrome photography. Direct contact links follow. A wide calligraphic sign introduces a centered 690px form with Underlined form field and Submit bar components.

**Transfer:** Use this scoped theme for organization, location or contact information rather than applying the dark treatment to ordinary marketing sections.

## Page flow

**Storyline:** identity → selected outputs → process and context → editorial depth → focused selection or practical action → identity and contact

### An editorial marketing landing page that mixes commerce with the life of the product

1. **Orientation** — Compact identity sentence, notice and mixed-family heading.
2. **Product demonstration** — Horizontal shelf of selected outputs, followed by broad process media.
3. **Context** — Large emblem opposite working-material photography, then broad editorial statements.
4. **Editorial depth** — Portrait and interview pair, two short updates, then a full-width material photograph.
5. **Focused selection** — A compact two-by-two product family.
6. **External proof** — Short press introduction opposite a tall photographic image.
7. **Closing identity** — Monumental word artwork and factual contact footer.

**Transfer:** Alternate compact text and visually expansive proof; use editorial stories to connect products to people and process rather than inserting standard feature-card rows.

### A browse-first product catalog

1. **Orientation** — Sticky header and centered text-only category selector.
2. **Product exploration** — Edge-to-edge three-column grid of square product fields with title, creator and right-aligned prices; comparison prices are smaller, grey and crossed out.
3. **Practical close** — Space after the last row, then the shared identity/contact footer.

**Transfer:** Let repeated objects carry the page; use metadata, not promotional descriptions, to support comparison.

### A studio introduction and contact destination

1. **Identity** — Centered grey identity graphic and compact description on a continuous charcoal ground.
2. **Practical context** — Three-column information/photo composition with hours, location and access details.
3. **Direct contact** — Role-based contact links followed by a wide script sign and simple outlined form.
4. **Practical close** — The shared footer recolored grey on charcoal.

**Transfer:** Use the dark variant to distinguish institutional information from the image-rich marketing experience; maintain the same practical, typographic construction.

## Writing

Direct, personable and culturally editorial. Products and activities are named plainly, while short introductions provide human context instead of inflated value claims.

**Do not copy:** Do not reuse the original identity, emblem, artist or product names, contact details, address, prices, shipping thresholds, dates, publication claims or press references. Examples illustrate voice only.

- **Addressing the reader:** The organization speaks as we or through its name; practical requests address the reader directly and courteously.
- **Rhythm:** Headings are short editorial prompts or subjects; support text is one compact paragraph. Updates can be conversational and date-led, while practical information stays terse.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Identity line | Name followed by what the organization is and where it works. | One sentence | “is a publishing house and a risograph studio based in Paris, France” |
| Section heading | Short prompt followed by a subject, often with a colon. | 2–5 words | “What's on: Latest”<br>“Introducing” |
| Supporting statement | Describe what is made and the human care behind it. | One short sentence plus a direct invitation | “Fidèle publishes contemporary art books and comics—made with care, in close collaboration with artists and authors. Discover our catalog in the shop.” |
| Action | Plain verb and the kind of content reached. | 1–2 words | “Read interview”<br>“Read more”<br>“Send” |
| Practical invitation | Polite, useful request with a specific next step. | One sentence | “Please contact us to schedule a visit, a wholesale inquiery or any other matter.” |

**Words and phrasing to use:** Introducing; Latest; made with care; in close collaboration; Discover; Please contact us

**Avoid:** revolutionary; game-changing; unlock your potential; best-in-class; frictionless ecosystem

**Rules:**

- Use concrete names for outputs and activities; do not replace them with abstract benefits.
- Keep calls to action descriptive of their destination.
- Dates, times and conditions belong in practical notices rather than in heroic slogans.
- Retain conversational warmth but use correct spelling and clear grammar in new copy.

## Do's and Don'ts

### Do

- Keep default major headings at 62px, weight 400 and 0.92 leading.
- Pair grotesk and upright serif words at the same display size.
- Use 14.4px side insets to make photographs feel nearly full bleed.
- Keep object imagery square on #e2e2df with metadata directly below.
- Use 21px section padding as the ordinary editorial rhythm, and 42px for extra separation.
- Carry blue ink into rules, utility icons and identity artwork as well as text.
- Reserve the 690px flat submit bar and grey form rules for the charcoal contact theme.

### Don't

- Do not use 700 as the default heading weight; save it for identity emphasis and selected navigation.
- Do not add rounded cards or pill-shaped actions to the square editorial system.
- Do not paint every section a different accent color; keep the interface on warm paper.
- Do not add CSS drop shadows to card containers; apparent object shadows belong inside the imagery.
- Do not convert every 28px paragraph into small 16px body copy; large editorial support is characteristic.
- Do not recolor all photography blue; the media carries the broader palette.
- Do not place the dark studio theme inside a floating light-page panel; it is a full-page variant.

## Motion and responsive

### Motion

**Observed:**

- Editorial links and several image surfaces declare 0.3s transitions.
- Catalog surfaces declare background-color .3s ease.
- The header remains sticky while the body scrolls.

**Transfer:**

- Keep interactions local to links and product fields; the visual identity is already carried by scale and images.

**Unknown:**

- No specific entry-animation sequence or independently verified movement timing is established.

### Responsive

**Observed:**

- Desktop layouts use near-full-width media, a horizontal product shelf, paired editorial columns and three-column catalog imagery.
- Declared grid tokens distinguish 12px desktop spacing from 6px mobile spacing.

**Transfer:**

- On narrow screens, retain square object imagery and compact metadata; let the opening shelf scroll horizontally rather than shrinking all items to fit.
- Stack editorial image/text pairs and practical footer groups while retaining the mixed-family headline relationship.
- Let the submit bar track available form width; retain the rectangular shape and line-based fields.

**Unknown:**

- Exact mobile typography sizes, navigation collapse behavior and grid-column breakpoints are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
