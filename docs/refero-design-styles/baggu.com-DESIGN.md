# BAGGU — playful catalogue bluntness

## Overview

An image-first, matter-of-fact retail style with playful graphic interruptions. White space and black grotesk lettering provide a practical frame for colorful products, direct studio photography and candid everyday scenes. It suits tactile consumer goods and visually expressive collections, balancing dense little catalogue labels with expansive photographs and an outsized graphic farewell.

### Essentials

- The photograph is the headline's stage, not its background: a full-width 1440×600px triptych sits above a separate 65px title strip with an action at the left and collection name at the right.
- Headlines behave like shop signage: the default campaign label is bold uppercase studioPro at 41px/1 with -0.05em tracking; catalogue section labels drop directly to 18px/1, weight 700.
- Most actions are naked words, not buttons: black type on white, with pink #e45dbf hover; the compact signup button is the exception at 160×28px, black with a 24px radius and 1.5px border.
- Color belongs overwhelmingly to the objects and photographs: the surrounding page stays #ffffff and #000000, with a small #90912b campaign-label accent rather than colored section fills.
- Images form unboxed sheets: three flush 480×600px editorial panels alternate with horizontal product rails whose 344×430px pictures are divided by 4px white gutters; 64px separates merchandising chapters.
- The closing identity becomes an object: include a full-width, edge-clipped black word sculpture with a repeated pink outline motif, preceded by a 250px-high alternating photo-and-word social ribbon. If no photo collection exists, use tightly framed product details and repeated short invitation labels.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Playful pink | `#e45dbf` | `--color-interaction` | link, accent | Link hover and the playful family of pink outline decorations; keep page-sized surfaces white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | All page chrome and open content areas; reversed text on black. |
| Secondary count gray | `#808080` | `--color-muted` | text | Secondary variant counts; black at 50% alpha over white. |
| Black ink | `#000000` | `--color-ink` | text, background, border, action | Headings, labels, navigation, announcement band and signup button. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| the dotted seasonal campaign | Olive label | `#90912b` | `--color-campaign` | text, accent | Right-aligned campaign name in the split title strip. |

## Typography

- **studioPro** — All headings, labels, navigation and prose. Compact contemporary grotesk with blunt terminals and tight, practical proportions; strong bold labels contrast with regular editorial capitals. If unavailable, use **Inter**. Use weights 400–700 and preserve tight tracking; check line lengths against the compact original. Font stack: "studioPro", "Inter", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| campaign-title | studioPro | 700 | 41px | 1 | -0.05em, uppercase | The opposing action and collection-name labels beneath the opening image. |
| section-label | studioPro | 700 | 18px | 1 | -0.025em | Centered merchandising section labels and category captions. |
| navigation | studioPro | 700 | 18px | 1.25 | -0.01em, features "case", "ss02" 0, "ss03", "ss06", "ss07", "ss08", "ss09" | Shop, info and cart navigation. |
| tile-action | studioPro | 700 | 18px | 0.9 | normal | Compact two-line action captions beneath editorial triptychs. |
| social-label | studioPro | 700 | 16px | 1 | -0.025em, uppercase | Centered invitation and handle cells in the social ribbon. |
| footer-link | studioPro | 700 | 16px | 22px | -0.025em | Dense stacked footer navigation. |
| product-name | studioPro | 700 | 14px | 1.25 | -0.025em | Product title in the small two-line rail caption. |
| product-variant | studioPro | 700 italic | 14px | 1.25 | -0.0086em | Color or pattern name below a product title. |
| variant-count | studioPro | 700 | 14px | 1.25 | -0.0086em, uppercase | Muted inline additional-variant count. |
| announcement | studioPro | 700 | 12px | 1 | -0.01em | Underlined utility message on the black top band. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial information pages | editorial-title | studioPro | 400 | 48px | 1 | -0.05em, uppercase | Plain left-aligned page title above the first image-and-prose row. |
| editorial information pages | editorial-heading | studioPro | 400 | 40px | 1 | -0.05em, uppercase | Large chapter names aligned to the right-hand prose column. |
| editorial information pages | body | studioPro | 500 | 16px | 1.25 | -0.01em | Explanatory paragraphs; inline links use underlines. |
| editorial information pages | subheading | studioPro | 500 | 16px | 2 | -0.01em | Sentence-case topic labels preceding indented paragraphs. |

**Notes:**

- Keep the default landing page typographic hierarchy unusually shallow: bold 41px campaign names, 18px section labels and 14px product details. Let photographs supply drama.
- Regular editorial capitals use the same -0.05em tracking as campaign labels, but not their bold weight.
- The giant closing identity is graphic artwork rather than an ordinary headline. Size its outlines to the available width instead of applying the prose type scale.

## Layout

**Density:** Compact in controls and captions, expansive between image-led chapters; the page feels like a catalogue rather than a stack of padded cards.

### Spacing

| Value | Use |
| --- | --- |
| 4px | White image-rail gutters and product-caption top padding. |
| 16px | Navigation gaps and horizontal editorial prose inset. |
| 20px | Signup button horizontal padding. |
| 24px | Gap between the price and product-title block. |
| 32px | Editorial chapter bottom padding and heading-to-topic space. |
| 44px | Desktop footer side inset. |
| 64px | Separation between merchandising chapters. |
| 128px | Desktop footer utility area's bottom padding. |

### Containers and grids

- **Full bleed media**: max width 1440px · side padding 0px. At a 1440px desktop width, images run from edge to edge rather than inside a centered narrow container.
- **Editorial triptych**: 3 columns · gap 0px · side padding 0px. Three equal 480px panels, with captions on white directly below.
- **Product rail**: gap 4px. Horizontal overflowing row of 344px-wide product pictures, allowing partial items to show at both edges.
- **Footer utility grid**: 2 columns · gap 0px · side padding 44px. Signup occupies the left half; three compact link groups share the right half.
- **Signup measure**: max width 448px. Form field stack within the footer's left column.
- **Information split** (only for editorial information pages): 3 columns · gap 0px · side padding 0px. Left third is a 480px-wide portrait photograph; right two thirds hold copy with 16px side padding.
- **Prose measure** (only for editorial information pages): max width 804px. Detailed paragraphs nest inside the right-hand area rather than filling its entire width.

## Corner radius

| Element | Radius |
| --- | --- |
| Signup button | 24px |
| Email field | 4px |
| Media tiles | 0px |

## Surfaces and depth

### Surfaces

#### Open white sheet · level 0

**Use:** Default page canvas, image captions and footer.

**CSS:** `background: #ffffff; color: #000000; box-shadow: none`

**Observed:** Content is grouped through placement and photography, not tinted boxes or raised panels.

**Transfer:** Use the same continuous canvas around different content types.

#### Black utility band · level 1

**Use:** Narrow announcement at the page top.

**CSS:** `background: #000000; color: #ffffff; height: 32px`

**Observed:** One centered, underlined message; separate from the sticky white navigation.

**Transfer:** Keep the message useful and short; do not turn it into a large promotional hero.

## Components

### Utility announcement

**Use:** Top-of-page transactional information.

**CSS:** `height: 32px; background: #000000; color: #ffffff; text-align: center; text-decoration: underline`

**Text style:** `announcement` — studioPro 700 · 12px/1 · tracking -0.01em

**Observed:** Single centered line above the navigation.

**Transfer:** Use an actual service benefit with its qualification.

### Compact navigation

**Use:** Persistent shopping and information access.

**CSS:** `background: #ffffff; color: #000000; height: 40px; position: sticky; top: -1px; z-index: 100; padding: 0px 16px; gap: 16px`

**Text style:** `navigation` — studioPro 700 · 18px/1.25 · tracking -0.01em

**Observed:** Shop, info and a search glyph sit left; the identity is independently centered; cart count anchors the right.

**States:** Declared: hover color #e45dbf; focus-visible outline-offset 2px and transparent 2px solid outline.

**Transfer:** Keep the central identity visually centered even when side labels differ in width.

### Split campaign link

**Use:** Primary campaign action and collection naming.

**CSS:** `background: #ffffff; color: #000000; height: 65px; padding: 3px 13px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `campaign-title` — studioPro 700 · 41px/1 · tracking -0.05em · uppercase

**Observed:** Two equal-width halves carry opposing left and right labels. The seasonal right label uses olive.

**States:** Declared: hover opacity 0.7.

**Transfer:** Pair a direct verb with a short collection or feature name.

### Rail heading

**Use:** Identify and navigate a horizontal assortment.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding-bottom: 2px; color: #000000`

**Text style:** `section-label` — studioPro 700 · 18px/1 · tracking -0.025em

**Observed:** A centered text action is flanked by simple left and right arrows at the page edges.

**States:** Declared: hover label color #e45dbf.

**Transfer:** Use a two-to-four-word assortment heading, not a paragraph.

### Product caption

**Use:** Compact product identity directly below rail imagery.

**CSS:** `display: flex; flex-direction: row-reverse; justify-content: space-between; gap: 24px; padding-top: 4px; color: #000000`

**Text style:** `product-name` — studioPro 700 · 14px/1.25 · tracking -0.025em

**Observed:** Price sits at the left; the larger remaining block contains a bold product name above an italic variant and muted additional-variant count. No border or enclosing card.

**Transfer:** Keep functional product naming separate from expressive color names.

### Editorial tile caption

**Use:** Action under a full-height triptych image.

**CSS:** `height: 41px; padding-top: 3px; display: flex; justify-content: center; align-items: flex-start; color: #000000`

**Text style:** `tile-action` — studioPro 700 · 18px/0.9

**Observed:** The short action breaks into two very tight lines and is repeated beneath related photographs.

**Transfer:** Treat each image as a complete link target with an explicit category caption.

### Social ribbon cell

**Use:** A lively bridge from content into footer.

**CSS:** `width: 200px; height: 250px; display: flex; align-items: center; justify-content: center; padding-right: 4px; color: #000000`

**Text style:** `social-label` — studioPro 700 · 16px/1 · tracking -0.025em · uppercase

**Observed:** Alternating cells contain 196×250px everyday photographs or centered invitation/handle text. The strip extends beyond both edges.

**Transfer:** Alternate original detail images with short community invitations.

### Email field

**Use:** Unboxed signup input in the footer.

**CSS:** `background: #ffffff; border: 0px; border-radius: 4px; width: 448px; height: 38px; padding: 6px 0px 8px; box-shadow: none`

**Observed:** Sits between an uppercase signup label and the small subscribe button; the field blends into the page rather than appearing as a bordered control.

**Transfer:** Retain an explicit label and the compact vertical stack.

### Subscribe button

**Use:** Footer mailing-list submission.

**CSS:** `background: #000000; color: #ffffff; border: 1.5px solid #000000; border-radius: 24px; width: 160px; height: 28px; padding: 0px 20px; font-family: studioPro, ui-sans-serif, system-ui, sans-serif; font-size: 16px; font-weight: 600; line-height: normal; letter-spacing: -0.01em; text-transform: uppercase`

**Observed:** Left-aligned beneath the email field, with social icons below rather than beside the label.

**States:** Declared: hover background #ffffff and color #000000.

**Transfer:** Reserve this compact filled shape for form submission rather than replacing every text action with a pill.

### Footer link group

**Use:** Shopping help, information and contact destinations.

**CSS:** `color: #000000; display: block; width: 204px`

**Text style:** `footer-link` — studioPro 700 · 16px/22px · tracking -0.025em

**Observed:** Three dense vertical groups occupy the right half of the utility footer; contact uses an underline and sits beneath the last group.

**States:** Declared: hover color #e45dbf.

**Transfer:** Group links by task without adding oversized column headings.

### Editorial topic

**Only for:** editorial information pages

**Use:** Organize explanatory paragraphs without card boundaries.

**CSS:** `display: flex; align-items: center; gap: 4px; margin-bottom: 16px; color: #000000`

**Text style:** `subheading` — studioPro 500 · 16px/2 · tracking -0.01em

**Observed:** A plain topic line precedes the paragraph block. Paragraphs are inset farther than the topic line; desktop content remains expanded.

**Transfer:** Use precise subject labels; do not imply a collapsed accordion merely because the topic can be a button.

## Imagery and graphics

### Campaign photo triptych

**Use:** Default marketing opening and related merchandising chapters.

**Observed:** Three equal vertical panels fill the width. Large tactile objects, cropped hands and partial bodies dominate; a central standalone object rests on a simple pale green chair. Soft gray-white and pale green photographic backdrops keep the patterned products crisp, with natural contact shadows and no text overlay.

**Transfer:** Photograph the new object in three complementary views: in use, isolated on an ordinary prop, and a tighter handling detail. If no lifestyle shoot is available, use three real detail photographs with consistent neutral light, never empty decorative tiles.

### Catalogue product photography

**Use:** Product and collection rails.

**Observed:** Front-facing bags and neatly arranged small sets sit against warm light-gray photographic sweeps. Portrait 4:5 framing gives each object a generous field, with modest natural shadow and saturated product colors. Images dominate the small labels beneath them.

**Transfer:** Use real isolated product photography on a consistent pale sweep. Keep full silhouettes readable and scales comparable; retain shadows in the image rather than adding CSS elevation.

### Everyday social portraits

**Use:** Alternating image cells in the closing social ribbon.

**Observed:** Handheld-looking close-ups show hands, fruit, clothing, pavement and stairways. Portrait crops are narrow, sunlit and informal; faces are not necessary.

**Transfer:** Show actual use and familiar surroundings with tactile details, preserving casual framing rather than replacing the ribbon with logo badges.

### Monumental closing identity

**Use:** Signature final graphic beneath utility footer content.

**Observed:** A giant black wordmark spans beyond the side edges on white, its letterforms about 330px high at desktop. A row of pink circular smile motifs crosses the upper portion, alternating in front of and behind the letters. The utility content above leaves a broad breathing area before the graphic.

**Transfer:** Create an original oversized identity or short word sculpture plus a repeating simple outline symbol derived from the new product's personality. The minimum version is bold outlined SVG lettering and a repeated geometric motif, not a normal centered footer logo.

**Build:** Use an SVG with a 1440px-wide viewBox and a white backing. Fit heavy black letter outlines across the full width with slight edge clipping and about 330px cap height. Repeat roughly eight pink outline motifs at about 185px intervals, each about 130px across with a 9px stroke. Place a motif row over the upper third of the letters and split layers so selected letters mask motifs while others remain in front. Use #e45dbf for the transferable pink treatment; preserve flat color with no blur or shadow.

### Process and material documentary

**Only for:** editorial information pages

**Use:** Portrait chapter images and full-bleed visual interludes.

**Observed:** A person gathering flowers, printing fabric, stacks of cut cloth, thread shelves and workers around long production tables establish physical making. Portraits occupy the left third; expansive fabric folds and factory views fill the whole width. Strong pink, violet, yellow and blue live inside the photographs, not in UI surfaces.

**Transfer:** Show the equivalent real ingredients, tools, workshops or work process. Favor a clear documentary photograph over decorative sustainability icons.

### Icons

**Observed:** Small black utility glyphs: a 20×20px search outline, approximately 17×15px directional arrows and 24×24px social marks. Shapes are spare and sit close to labels or at rail edges.

**Transfer:** Use simple black search and directional glyphs with the same compact scale; reserve filled recognizable marks for social destinations.

## Section recipes

How recurring sections are built.

### First screen: Photographic campaign opening

**Observed:** The first 900px contains a 32px Black utility band, a 40px Compact navigation, then a 600px-high Campaign photo triptych. The image is the main object and fills two thirds of the viewport height. A separate 65px Split campaign link sits immediately beneath: bold uppercase action at the far left, equally strong collection name at the far right, no supporting paragraph. Layers are a white canvas, contiguous photos, then the navigation above them; no text is laid over the objects. After 64px of white separation, the centered Rail heading and the tops of product images enter the bottom of the first screen; product captions fall below it.

**Transfer:** Make the new product visually legible through three linked views and a terse split action/name strip. Keep the image-first opening even without lifestyle media by using real close details and one full object view. Information pages instead use the editorial-title recipe above a one-third portrait/two-thirds introduction row.

**Avoid:** Do not replace the triptych with a centered slogan, support paragraph and oversized pill floating over a darkened photo.

**Text style:** `campaign-title` — studioPro 700 · 41px/1 · tracking -0.05em · uppercase

### Assortment rail

**Observed:** Rail heading sits directly above an edge-clipped horizontal row. Product pictures are 344×430px with 4px white separations and Product caption underneath. Collection rails use 310×387px images and centered section-label captions without detailed metadata.

**Transfer:** Use the detailed rail for purchasable items and the simpler rail for collections or use cases.

### Flush editorial trio

**Observed:** Three equal 480×600px editorial pictures form one continuous sheet, each followed by Editorial tile caption. The complete row is 641px high and separated from neighboring merchandising sections by 64px.

**Transfer:** Use related views that communicate one collection or three specific uses. Captions can repeat a shared action when the images point to one destination.

### Social and monumental farewell

**Observed:** A 250px-high strip of Social ribbon cell items alternates photographs and centered text. After 32px comes the Footer utility grid: signup and icons on the left, compact link groups on the right. The utility region uses 128px bottom padding before the Monumental closing identity takes over the lower page. Both content-rich and retail pages end with this same combination rather than a conventional small-logo footer.

**Transfer:** Include the alternating social device and outsized original identity wherever they best support the new page's closing rhythm. Keep utility links practical and separate from the graphic spectacle.

### Information chapter

**Only for:** editorial information pages

**Observed:** Information split pairs a 480px-wide portrait with a two-thirds copy area. The editorial-heading leads the text column with 32px below it. Editorial topic lines precede body paragraphs, inset further than the topics. Chapter rows have 32px bottom padding; long prose can continue below the photograph, leaving the left side open.

**Transfer:** Explain complex product decisions through modest topic labels and literal prose; use the photograph as a chapter anchor, not a card illustration.

**Text style:** `editorial-heading` — studioPro 400 · 40px/1 · tracking -0.05em · uppercase

### Documentary full-width interlude

**Only for:** editorial information pages

**Observed:** Uncaptioned full-width photographs interrupt the detailed information rows: material folds occupy a 1440×843px field, and a workshop view occupies 1440×854px. There is no floating copy panel.

**Transfer:** Use a substantial material detail or real working environment as a visual pause between dense explanation chapters.

### Direct feedback close

**Only for:** editorial information pages

**Observed:** A final Information split pairs thread-and-material shelving with a regular uppercase question heading and a very short body invitation containing an underlined email link. The photograph retains its full 640px portrait height even though the copy is brief.

**Transfer:** Close detailed explanation with a real way to ask questions, using a simple invitation instead of a sales banner.

**Text style:** `editorial-heading` — studioPro 400 · 40px/1 · tracking -0.05em · uppercase

## Page flow

**Storyline:** Visual invitation → browsable choices or explanatory chapters → tactile proof → community invitation → practical utility → graphic farewell.

### Image-led retail or collection landing page

1. **Visual invitation** — Full-width photographic triptych with a split action and collection-name strip.
2. **Product discovery** — A detailed assortment rail introduces individual items and variants.
3. **Use-case exploration** — Flush editorial trios alternate with a simpler collection rail.
4. **Community invitation** — Alternating everyday photographs and terse follow labels.
5. **Utility and identity** — Newsletter, compact help links and the monumental graphic close.

**Transfer:** Lead with a small coherent visual collection and let each following image sheet or rail offer a different way to choose.

### Long-form product, process or responsibility explanation

1. **Context** — Regular uppercase title followed by an asymmetrical portrait-and-introduction row.
2. **Explanation** — Repeated one-third image and two-thirds prose chapters with small subject labels.
3. **Tactile proof** — Full-width material and workshop photography breaks the reading rhythm.
4. **Objection handling** — Detailed paragraphs explain tradeoffs in plain language, including numbers within the prose.
5. **Open conversation** — A brief feedback invitation and underlined direct contact.
6. **Utility and identity** — The shared social ribbon, signup, link columns and oversized graphic ending.

**Transfer:** Keep complex reasoning in readable chapters; give numbers context rather than converting every fact into a giant statistic.

## Writing

Practical, friendly and unceremonious. Retail language names things directly; longer explanations are candid about constraints and concrete about how things work.

**Do not copy:** Do not reuse BAGGU's name, wordmark, social handles, smile artwork, product names, collection names, shipping thresholds, environmental percentages, founding history or manufacturing claims. Source examples illustrate voice only.

- **Addressing the reader:** Use direct imperatives for shopping and first-person plural for explanations. Address the reader as you when offering help or inviting questions.
- **Rhythm:** Retail headings are short noun labels or verb-plus-category commands, often in capitals. Prose uses full explanatory sentences and occasional direct questions, with practical transitions rather than slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Campaign label | A short imperative paired with a concise collection descriptor. | 1–3 words per side | “SHOP”<br>“POLKA DOT” |
| Section action | Shop plus a plain category or recency label. | 2–4 words | “SHOP NEW ARRIVALS”<br>“SHOP ACCESSORIES” |
| Topic heading | A literal subject or practical design principle. | 2–6 words | “As Few Materials as Possible”<br>“Designing For Longevity” |
| Explanatory prose | State the choice, explain the mechanism, then acknowledge the tradeoff. | Several concise sentences per paragraph | “Part of the answer is about affordability, and part is about durability.” |
| Closing invitation | Ask a simple service-oriented question and offer direct contact. | 3–5 words for heading | “Questions or Feedback?”<br>“Sign up for updates” |

**Words and phrasing to use:** shop; new arrivals; collection; designed; materials; quality; function; value; questions; updates

**Avoid:** revolutionary; game-changing; unlock your potential; premium ecosystem; planet-saving; unqualified superlatives

**Rules:**

- Prefer exact product and category names to aspirational taglines.
- Keep prices and variant information factual and compressed.
- Explain limitations alongside benefits when discussing technical or ethical decisions.
- Use capitalization to mark retail hierarchy, not to shout through paragraphs.
- End help content with an approachable invitation and a real contact method.

## Do's and Don'ts

### Do

- Keep the desktop navigation 40px high with 18px bold labels and 16px gaps.
- Set campaign labels at 41px/1, weight 700 and -0.05em tracking.
- Use 64px separations between image-led merchandising chapters.
- Keep editorial trios flush: three equal columns with no gutters.
- Use 4px white divisions and tightly attached captions in product rails.
- Maintain 14px bold product names and italic variant names as distinct roles.
- Reserve the 160×28px rounded black action for signup.
- Make the closing graphic span the full width, much larger than the utility text.

### Don't

- Do not tint every section olive or pink; those colors are small accents outside photographs.
- Do not add shadows or rounded frames to the square product photographs.
- Do not expand every 18px merchandising label into a 60px promotional heading.
- Do not center long editorial paragraphs; keep them in the right two-thirds column.
- Do not turn variant labels into colorful pill tags; they are small italic inline text.
- Do not put detailed product descriptions between the rail image and its two-line caption.
- Do not replace the social ribbon with a conventional testimonial-card grid.
- Do not make the signup button tall and oversized; its compact 28px height is deliberate.

## Motion and responsive

### Motion

**Observed:**

- The white navigation remains sticky while the announcement scrolls away.
- Declared link opacity transitions use 0.15s cubic-bezier(0.4, 0, 0.2, 1). The subscribe control declares 0.2s duration.
- The social strip declares a linear horizontal marquee; repeated items extend beyond the viewport.
- Closing identity layers use sticky and clipped positioning.

**Transfer:**

- Preserve a continuous horizontally repeating social strip rather than treating the images as a static centered gallery.
- Use small color or opacity changes for naked text actions, retaining their shape and placement.

**Unknown:**

- Marquee duration, closing-art animation sequence and actual hover behavior beyond declared rules are unspecified.

### Responsive

**Observed:**

- At the 800px breakpoint the desktop campaign media and split title strip use flex layouts, editorial rows become three-column grids and the footer becomes two columns.
- The desktop editorial title uses 48px; narrower title classes declare 30px. Product labels remain compact.
- The wide closing identity has a desktop-specific image treatment.

**Transfer:**

- Below the desktop grid threshold, stack editorial photography and prose while retaining square edges and direct captions.
- Keep a horizontally navigable assortment rather than shrinking five product pictures to illegible sizes.
- Adapt the monumental graphic as its own narrow-width artwork, preserving bold clipping and motif overlap.

**Unknown:**

- Exact mobile navigation composition, campaign art direction, narrow-width closing artwork and tested touch behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
