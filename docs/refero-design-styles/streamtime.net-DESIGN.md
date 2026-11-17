# Streamtime — paper play at work

## Overview

A light, playful editorial identity that makes business software feel like a creative studio rather than an enterprise suite. Warm paper neutrals, black grotesk lettering and occasional acid green, yellow and hot pink blocks sit alongside tactile geometric cutouts, candid workplace photography and expansive interface demonstrations. The density alternates between sparse poster-like statements and detailed product proof, with an unusually conversational tone.

### Essentials

- A small spoken promise above a giant visual name: the opening uses centered 30px/1.2 regular display text with -0.06em tracking, a broad white interval, then a nearly full-width black letter sculpture and textured shapes along the bottom of the first 900px.
- Paper toys, not polished 3D: circles, triangles, scalloped discs, asterisks and concave crosses carry graphite grain, dry pencil strokes or halftone dots. Include this tactile geometric vocabulary on every new landing page; SVG masks with noise and hatching are the minimum equivalent.
- Buttons are little physical labels: 28px/1.1 regular text, 8px 16px padding and a shallow two-layer shadow; mix 5px rectangular corners with 96px pills rather than making every control identical.
- Color arrives as punctuation and chapters: white, #eadcce paper and #2f2c29 charcoal occupy the broadest areas; #ff4dd5 makes a compact 244px conversion band, while lime and yellow inhabit cutouts and proof cards. Full lime or yellow capability bands belong to feature-detail pages.
- Product proof is big enough to inspect: 893×558px interface images with 10px corners and restrained shadows travel across a warm paper stage; captions sit below, not inside decorative device mockups. If the product has no interface, use equally large process or outcome panels.
- Conversational type stays regular and tightly fitted: 30px/36px section statements coexist with 18px/21.6px supporting copy; 100px/100px conversion questions meet a charcoal pill with 68px/68px text. Preserve the difference between modest narrative headings and monumental calls to action.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm paper | `#eadcce` | `--color-paper` | background, surface | Broad product demonstration stages and neutral cutouts. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hot pink | `#ff4dd5` | `--color-pink` | background, accent | Compact full-width conversion bands and small graphic accents. |
| Chartreuse | `#c6dc3c` | `--color-lime` | surface, accent | Quote cards, resource cards and textured graphic accents; full-width capability bands on feature-detail pages. |
| Paper yellow | `#ffde3b` | `--color-yellow` | action, surface, accent | Default demonstration action, resource cards and geometric accents; full-width capability bands on feature-detail pages. |
| Cutout blue | `#6483ff` | `--color-blue` | surface, accent | Resource card and textured shape accent, not default links. |
| Quote yellow | `#ffdb00` | `--color-gold` | surface | A stronger yellow quote-card variant. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, text, surface | Default canvas, form panels, and reversed text on charcoal. |
| Off-white | `#fbf8f5` | `--color-cream` | background, surface | Light quote card and softer product chapter canvas. |
| Pale warm grey | `#f1eeeb` | `--color-stone` | surface, background | Secondary sign-up control and subdued editorial bands. |
| Oat paper | `#f1e8de` | `--color-oat` | background, surface | Testimonial stage, neutral labels and option tiles. |
| Putty | `#c3b7ac` | `--color-taupe` | surface, accent | Quote and resource cards, neutral menu stickers and shapes. |
| Muted label grey | `#999999` | `--color-muted` | text | Footer headings: black at 0.4 alpha over white. |
| Warm charcoal | `#2f2c29` | `--color-charcoal` | background, surface, text, action | Dark editorial chapters, logo strips, menu label and oversized conversion pills. |
| Black lettering | `#000000` | `--color-ink` | text, accent | Default lettering, word sculptures and graphic marks. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| expanded navigation | Soft sticker pink | `#ee84d5` | `--color-menu-pink` | surface | Audience link in the expanded sticker menu. |
| pricing forms | Currency grey | `#dce1e5` | `--color-choice-grey` | surface | Unselected currency pills and slider track. |
| feature-detail endings | Inactive warm grey | `#b3ae98` | `--color-inactive-link` | text | Inactive feature-directory links. |

## Typography

- **Ease Display** — Marketing statements, headings and prominent actions. Friendly low-contrast grotesk with open forms and a slightly idiosyncratic, tightly fitted rhythm; regular weight throughout. If unavailable, use **DM Sans**. Use 400; retain the tight tracking and check line breaks. Font stack: "Ease Display", "DM Sans", Arial, sans-serif.
- **Ease Standard** — Supporting text, credits, footer links and form labels. A companion grotesk for smaller reading sizes, still unusually tightly tracked. If unavailable, use **DM Sans**. Use 400; do not introduce a heavier UI hierarchy. Font stack: "Ease Standard", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| conversion-heading | Ease Display | 400 | 100px | 1 | -0.06em | Large conversion question or invitation; also suitable for a short editorial title. |
| conversion-action | Ease Display | 400 | 68px | 1 | -0.0141em | Oversized charcoal conversion pill. |
| statement | Ease Display | 400 | 30px | 1.2 | -0.06em | Default opening promise and support line, section headings, editorial paragraphs and testimonial quotations. |
| action | Ease Display | 400 | 28px | 1.1 | -0.0343em | Header actions and menu labels. |
| body | Ease Standard | 400 | 18px | 1.2 | -0.0533em | Supporting copy, captions, bylines and underlined detail links. |
| footer-link | Ease Standard | 400 | 18px | 1.1 | -0.06em | Compact footer navigation; allow two-line labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| manifesto and culture chapters | travelling-statement | Ease Display | 400 | 172.8px | 1 | -0.06em | White letter-by-letter statement crossing a charcoal editorial stage. |
| feature-detail and pricing pages | detail-title | Ease Display | 400 | 48px | 1 | -0.06em | Feature-detail or pricing opening title. |
| manifesto, culture and pricing pages | editorial-lead | Ease Display | 400 | 48px | 1.2 | -0.06em | Manifesto section lead, form invitation, and long-form principles. |
| pricing forms | option-label | Ease Standard | 400 | 30px | 1.2 | -0.06em | Centered labels within large choice tiles. |
| feature-detail endings | directory-link | Ease Standard | 400 | 18px | 1.3 | -0.0533em | Vertical feature-directory links, including wrapped active items. |

**Notes:**

- Keep headings at weight 400; scale and arrangement create emphasis rather than bold weight.
- The recurring statement is both heading and larger prose. Do not automatically enlarge every section title to the conversion-heading size.
- Tracking is generally -0.06em for statements and large titles, but action and body recipes keep their own -1px tracking.
- The monumental black opening name is vector lettering, not the regular text face. Rebuild it as individually arranged heavy letterforms rather than stretching a text heading.
- The root sizing context uses calc(0.398664rem + 0.668151vw); use this as the fluid basis for rem-based implementation, while retaining the desktop recipes at 1440px.

## Layout

**Density:** Airy poster-like sections surrounding inspectable product imagery; compact navigation and footer details provide contrast.

### Spacing

**Spacing system:**

- **horizontal step** 8px, horizontal — Common side padding and layout gaps; 20px, 30px and 50px are deliberate exceptions.

| Value | Use |
| --- | --- |
| 8px | Separation between stacked pricing panels. |
| 16px | Footer link rhythm, related paragraph gaps and option-grid gaps. |
| 20px | Resource card padding, card-grid gaps and directory row gaps. |
| 24px | Global desktop page inset and top inset of floating navigation labels. |
| 30px | Quote-card padding and internal gaps; vertical quote-card separation. |
| 32px | Feature heading-to-body gap and conversion-row gap. |
| 40px | Conversion-band vertical padding and product-caption offset. |
| 48px | Footer top padding and oversize action vertical padding. |
| 80px | Opening support offset below the header and medium section spacing. |
| 96px | Long-form principle separation. |
| 120px | Default major section top and bottom padding. |

### Containers and grids

- **wide canvas**: max width 1392px · side padding 24px. At 1440px, broad marketing compositions, navigation and footer leave only the global edge inset; allow the content width to follow the window.
- **feature container**: max width 1152px · 2 columns · gap 50px. Centered feature-detail stage with narrower text beside larger imagery; opening columns use a 0.8:1 proportion.
- **quote stage**: max width 1200px · side padding 24px. 800px quotation cards stagger horizontally within a wider centered stage.
- **resource grid**: 4 columns · gap 20px. Four equal 333px resource cards within the wide canvas; image inset makes each picture 293px square.
- **audience grid**: 3 columns · gap 20px. Three 333px square photographs with text links, alongside a narrow introductory text column.
- **form column** (only for pricing pages): max width 920px · gap 8px. Centered stack of pricing panels on charcoal.
- **team grid** (only for culture pages): 6 columns · gap 24px. 212px portraits and interspersed standalone cutouts; names and roles beneath.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | label rectangle | 5px |
|  | product image | 10px |
|  | header pill | 96px |
|  | conversion pill | 160px |
| expanded navigation | menu rectangle | 4px |
| pricing forms | counter circle | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| label lift | `rgba(0, 0, 0, 0.08) 2px 2px 4px 1px, rgba(0, 0, 0, 0.13) 1px 0px 5px 0px` | Small navigation labels; a tactile shallow lift rather than a glow. |
| product lift | `rgba(115, 115, 115, 0.16) 0px 3px 10px 0px, rgba(115, 115, 115, 0.16) 0px 2px 4px 0px` | Large interface images on the warm paper stage. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #000000`

#### Warm product stage · level 0

**Use:** Expansive horizontal product demonstrations.

**CSS:** `background: #eadcce; overflow: hidden`

**Observed:** Flat warm paper color; texture belongs to the cutouts, not a noisy overlay over the entire page.

**Transfer:** Let real interface images supply detail against a calm warm ground.

#### Charcoal chapter · level 0

**Use:** Human story, editorial statements and logo proof.

**CSS:** `background: #2f2c29; color: #ffffff; overflow: clip`

**Observed:** Warm dark solid rather than true black, with white type and occasional bright cutouts.

#### Pink conversion band · level 0

**Use:** Short, emphatic conversion interruption.

**CSS:** `background: #ff4dd5; padding: 40px 24px`

**Observed:** A large black question at left and an oversized charcoal action at right; the default band is 244px tall.

#### Oat quote stage · level 0

**Use:** Staggered testimonial cards.

**CSS:** `background: #f1e8de; padding: 120px 24px`

#### Cream capability canvas · level 0

**Only for:** feature-detail pages

**Use:** Soft light chapters between saturated capability sections.

**CSS:** `background: #fbf8f5; padding: 120px 24px`

#### Lime capability band · level 0

**Only for:** feature-detail pages

**Use:** Single capability with substantial product detail.

**CSS:** `background: #c6dc3c; padding: 120px 24px`

**Observed:** Flat saturated field with black text and a pale interface panel; a yellow band uses the same construction.

**Transfer:** Assign one strong field to a complete capability rather than alternating color on every small card.

#### Principle paper · level 0

**Only for:** culture pages

**Use:** Large text-led sequential principles.

**CSS:** `background: #f1eeeb`

## Components

### Floating navigation

**Use:** Persistent sparse navigation above every page.

**CSS:** `position: sticky; top: 0px; z-index: 9990; height: 80px`

**Text style:** `action` — Ease Display 400 · 28px/1.1 · tracking -0.0343em

**Observed:** Transparent across the page background. A 48px circular logo chip and Menu label form the left cluster; login, demonstration and sign-up labels form the right cluster with 4px gaps. Labels begin 24px inside the page edges. Interior pages add a colored current-section label separated by a small geometric mark.

**Transfer:** Use a compact product monogram and one short current-location label instead of a full horizontal sitemap.

### Demonstration button

**Use:** Default prominent header action.

**CSS:** `background: #ffde3b; color: #000000; border-radius: 96px; padding: 8px 16px; box-shadow: rgba(0, 0, 0, 0.08) 2px 2px 4px 1px, rgba(0, 0, 0, 0.13) 1px 0px 5px 0px`

**Text style:** `action` — Ease Display 400 · 28px/1.1 · tracking -0.0343em

**Observed:** Text-only pill, approximately 193×47px for this label. Feature-detail and manifesto variants use a brighter lime fill.

### Secondary label button

**Use:** Secondary account or signup action.

**CSS:** `background: #f1eeeb; color: #000000; border-radius: 5px; padding: 8px 16px; box-shadow: rgba(0, 0, 0, 0.08) 2px 2px 4px 1px, rgba(0, 0, 0, 0.13) 1px 0px 5px 0px`

**Text style:** `action` — Ease Display 400 · 28px/1.1 · tracking -0.0343em

**Observed:** Rectangle for sign-up; the adjacent login variant is a white 96px-radius pill. Shape distinguishes the controls without icons.

### Menu label

**Use:** Compact left-side navigation trigger.

**CSS:** `background: #2f2c29; color: #ffffff; border-radius: 5px; padding: 8px 16px; box-shadow: rgba(0, 0, 0, 0.08) 2px 2px 4px 1px, rgba(0, 0, 0, 0.13) 1px 0px 5px 0px`

**Text style:** `action` — Ease Display 400 · 28px/1.1 · tracking -0.0343em

**Observed:** Sits beside the logo chip; culture and manifesto pages use a putty label, and the pricing variant uses lime.

### Oversized conversion pill

**Use:** Primary action in a pink conversion band.

**CSS:** `background: #2f2c29; color: #ffffff; border-radius: 160px; padding: 48px 80px; max-width: 100%`

**Text style:** `conversion-action` — Ease Display 400 · 68px/1 · tracking -0.0141em

**Observed:** Text-centered pill opposite a large black invitation; no shadow or arrow. Width follows the label; the short sign-up version is 393×164px.

**Transfer:** Use two or three everyday words with a clear next step.

### Quotation card

**Use:** Human proof in a staggered testimonial field.

**CSS:** `background: #c3b7ac; border-radius: 5px; padding: 30px; display: flex; flex-direction: column; gap: 30px; max-width: 800px`

**Text style:** `statement` — Ease Display 400 · 30px/1.2 · tracking -0.06em

**Observed:** Large quotation above a small graphic face and two-line attribution in body type. Variants use off-white, strong quote yellow and lime; cards shift left and right, and one is visibly tilted.

**Transfer:** Keep each quotation readable as a complete thought; vary placement without overlap over text.

### Resource card

**Use:** Editorial links near the page ending.

**CSS:** `background: #c6dc3c; border-radius: 5px; padding: 20px; display: flex; flex-direction: column; gap: 20px; overflow: clip`

**Text style:** `body` — Ease Standard 400 · 18px/1.2 · tracking -0.0533em

**Observed:** Square image first, then short title and author. Four-card desktop row uses lime, yellow, blue and putty fills; no raised shadow.

**Transfer:** Use monochrome editorial images with a single colored graphic intervention or a geometric composition.

### Footer link column

**Use:** Compact directory in the white ending.

**CSS:** `display: flex; flex-direction: column; gap: 16px; max-width: 117px; color: #000000`

**Text style:** `footer-link` — Ease Standard 400 · 18px/1.1 · tracking -0.06em

**Observed:** Muted body-sized heading above black links. Multiple narrow directory columns sit beside a certification area, small legal copy and a wider world-clock column.

**Transfer:** Let long names wrap naturally; keep the footer utilitarian rather than another conversion panel.

### Sticker menu link

**Only for:** expanded navigation

**Use:** Playful destination choices below the menu trigger.

**CSS:** `background: #ee84d5; color: #000000; border-radius: 96px; padding: 7.2px 16px 8.8px; box-shadow: rgba(0, 0, 0, 0.13) 1px 0px 5px 0px, rgba(0, 0, 0, 0.08) 2px 2px 4px 1px`

**Text style:** `action` — Ease Display 400 · 28px/1.1 · tracking -0.0343em

**Observed:** A vertical loose stack, each label tilted independently. Other destinations use yellow, putty, warm paper, pale grey or lime rectangles with 4px corners.

**Transfer:** Keep destinations as short spoken questions, with a small mix of shapes rather than a uniform dropdown list.

### Pricing panel

**Only for:** pricing forms

**Use:** One question at a time in an approachable custom-pricing form.

**CSS:** `background: #ffffff; border-radius: 10px; padding: 44.8px 44.8px 40px; margin-bottom: 8px`

**Text style:** `statement` — Ease Display 400 · 30px/1.2 · tracking -0.06em

**Observed:** White panel on charcoal with a centered question, generously separated control group and body-sized reassurance beneath. Choice tiles use oat fill, 10px corners and 16px padding; four labels use option-label type. Later panels hold paired counters, currency pills and a revenue slider.

**Transfer:** Ask only inputs that genuinely influence the commercial conversation.

### Counter control

**Only for:** pricing forms

**Use:** Large approachable plus/minus input controls.

**CSS:** `background: #f1e8de; border-radius: 50%; width: 64px; height: 64px; display: flex; align-items: center; justify-content: center`

**Observed:** A 24px black minus or plus sits in the circle, on either side of a white numeric input; groups are centered beneath question labels.

**States:** Declared: hover background-color #ffde3b; focus-visible outline-offset 0rem and outline rgb(0, 0, 0) solid 0rem.

## Imagery and graphics

### Letter sculpture and paper cutouts

**Use:** Signature opening artwork and smaller recurring accents throughout a landing page.

**Observed:** Nearly edge-to-edge black uppercase vector name, with heavy, irregular letterforms balanced at different heights and angles above a row of colorful geometric objects. The objects combine grey graphite, beige pencil rubbings, lime scalloped discs, pink half-discs, yellow rays and blue bursts. They look printed, rubbed and cut rather than softly shaded.

**Transfer:** Set the new product name or a short benefit word as individual heavy black vector letters. Always include the cutout vocabulary; if bespoke art is unavailable, simple original SVG silhouettes with visible hatching and halftone texture are sufficient.

**Build:** Create individual SVG letter groups fitted across the available width with an approximately 156px cap height at 1440px, shifting selected letters upward or downward and rotating a few by about 5–10 degrees. Beneath them place 100–176px circles, triangles, notched crosses and scalloped discs. Clip diagonal 1–2px pencil lines, fine low-opacity noise, or 2px halftone dots into the shapes; use black/putty neutrals plus lime, yellow, pink and blue. Keep edges crisp and texture dry, without drop shadows.

### Inspectable product panels

**Use:** Main product showcase and detailed capability illustrations.

**Observed:** Large pale interface images, commonly 893×558px with 10px corners and the product lift shadow, sit on warm paper and extend beyond the viewport during horizontal travel. Detail-page compositions isolate panels, sometimes tilt one, and place small textured shapes between them; broad table-like views span 1152px.

**Transfer:** Show real meaningful tasks and outcomes, with readable hierarchy inside each panel. For a non-software product, use process sheets, annotated deliverables or before/after documents at equivalent visual scale.

### Human workplace collage

**Use:** Human story on the charcoal chapter, and audience-specific photographic links.

**Observed:** Natural-light color photographs of people talking or working in creative interiors. Circles, small rounded rectangles and tall rectangular frames mix with bright halftone blocks and cutouts around a narrow column of white 30px text. Audience links use unfiltered 333px square photographs on white.

**Transfer:** Use real people in plausible work settings, soft daylight and restrained natural color; stage several scales around one reading column rather than using a single full-bleed stock hero.

### Graphic quote avatars

**Use:** Attribution marker beneath large quotations.

**Observed:** Small lime scalloped smile, pink triangular face and other simple friendly graphic faces replace headshots. They contrast with the sober two-line attribution.

**Transfer:** Use original tiny geometric mascots with two dot eyes and a curved smile, not emoji or detailed character illustration.

**Build:** Draw a 48–64px scalloped disc, triangle or polygon in SVG with a solid accent fill and a few black facial marks; apply a faint halftone texture within the silhouette.

### Editorial square graphics

**Use:** Resource-card imagery.

**Observed:** Square monochrome photographs receive one vivid pink stroke or lime zigzag; another square uses a flat geometric color assembly. The card fill remains visible around the picture.

**Transfer:** Use a restrained black-and-white photograph with one original fluorescent intervention tied to the article's theme.

**Build:** Place a square grayscale photograph inside the card inset. Overlay one SVG zigzag or rounded diagonal stroke in lime or pink, occupying a small part of the picture, with dry-grain masking rather than glow.

### Portrait cutout wall

**Only for:** culture pages

**Use:** A personable team directory and culture opening.

**Observed:** Color head-and-shoulders portraits on warm neutral discs, rounded tilted squares, polygons and scalloped masks, 212px wide in a six-column grid. Standalone textured shapes occupy some grid positions. Captions give role then name in compact black body type. The opening combines closely packed circles of color, candid group photographs and star-like cutouts.

**Transfer:** Use consistent portrait scale with varied masks and natural expressions; intersperse original geometric shapes rather than filling every cell with a headshot.

**Build:** Make circle, rounded-square, octagon and scalloped SVG clipPaths; alternate oat, paper, stone and putty backing. Use the same dry-grain cutout process for occasional non-portrait cells; keep text outside the mask.

### Balance illustration

**Only for:** manifesto pages

**Use:** Two alternative actions presented as complementary choices.

**Observed:** A roughly 390px lime disc and 408px yellow polygon sit on a long thin black-and-white halftone beam with a textured concave-cross fulcrum. Each shape contains a centered heading, short copy and charcoal pill.

**Transfer:** Use it to express complementary approaches or a genuine trade-off, not as a generic feature grid.

**Build:** Place two equal-weight SVG shapes at opposite ends of a 1200×23px horizontal beam, with a central 90px cross-like support. Clip halftone dots into the beam and pencil grain into the colored shapes; align their lower edges to the beam.

### Icons

**Observed:** Small graphic marks are solid black or colored SVG silhouettes rather than a repeated thin-line icon library. The header uses a 40px logo artwork inside a 48px white circular chip and a 16px menu marker. Pricing plus/minus artwork is 24px.

**Transfer:** Reserve functional icons for clear tasks; use simple filled geometry for decorative separators and keep cutout shapes distinct from interface controls.

## Section recipes

How recurring sections are built.

### First screen: Letter sculpture opening

**Observed:** The first 900px is a white poster beneath the Floating navigation. Two centered 30px statement lines sit near the upper fifth: a short promise, then a longer explanatory line. Most of the middle remains open. A nearly full-width black letter sculpture dominates the lower third, with individual letters rising or dipping and a row of textured geometric shapes along its baseline. Layers are white canvas, black letter groups, then colorful paper objects. The circular logo and Menu are left, while login, yellow demonstration and pale sign-up labels sit at right; there is no duplicate hero action row. Both lines, the complete main artwork and these actions are visible by 900px. The warm product stage starts below the fold.

**Transfer:** Use the new product name or a short central benefit as an original letter sculpture, retaining the wide air gap and tactile cutouts even without bespoke media. Feature-detail pages instead open with a 48px left title, 30px support and a right-hand collage of interface fragments on cream; pricing opens with a centered 48px white title and a white questionnaire on charcoal. Culture pages use a compact centered introduction above a field of masked photos and shapes; manifesto pages use a 100px left statement with staggered supporting text on warm paper.

**Avoid:** Do not replace the letter sculpture with an ordinary oversized text headline above a centered laptop, or move the entire product demonstration into the first screen.

**Text style:** `statement` — Ease Display 400 · 30px/1.2 · tracking -0.06em

### Horizontal product chapter

**Observed:** Warm product stage supports a horizontally moving sequence of large Inspectable product panels. Images are about 893×558px and neighboring panels remain partly visible. A 30px statement anchors the lower left; a row of 18px capability captions follows beneath the imagery. A bright hand-drawn zigzag marks the active caption.

**Transfer:** Choose a few meaningful workflow views and synchronize their movement with the active caption. Preserve large readable panels rather than shrinking all views into a thumbnail strip.

**Text style:** `statement` — Ease Display 400 · 30px/1.2 · tracking -0.06em

### Human story collage

**Observed:** Charcoal chapter combines several differently framed photographs and large textured cutouts around a narrow white statement column. The text is 30px/36px, with 16px paragraph gaps and an underlined concluding phrase; composition is intentionally asymmetrical.

**Transfer:** Explain the human stakes of the new product with a short honest contrast and images of actual use, not a second feature checklist.

**Text style:** `statement` — Ease Display 400 · 30px/1.2 · tracking -0.06em

### Emphatic conversion interruption

**Observed:** Pink conversion band pairs a 100px conversion-heading at left with Oversized conversion pill at right, using a 32px gap and vertically centered alignment. The band is compact compared with the surrounding chapters and is not necessarily the last section.

**Transfer:** Use one brief question or invitation suited to the next step. This strong device can sit wherever a narrative reaches conviction.

**Text style:** `conversion-heading` — Ease Display 400 · 100px/1 · tracking -0.06em

### Heading pair and audience links

**Observed:** Two consecutive 30px statements introduce a three-image audience grid. A slim text column sits left; square photographs and simple 30px text links fill the remaining width. There are no card backgrounds or button boxes beneath these images.

**Transfer:** Use for distinct reader needs or applications, with straightforward names rather than decorative category badges.

**Text style:** `statement` — Ease Display 400 · 30px/1.2 · tracking -0.06em

### Staggered testimonial papers

**Observed:** Oat quote stage holds 800px Quotation cards with 30px separation inside a 1200px stage. Cards shift horizontally; a yellow card is tilted while others remain level. Graphic quote avatars and compact bylines give each card a human signature.

**Transfer:** Use verified quotations about different outcomes. Preserve irregular placement and card-color changes without sacrificing reading order.

**Text style:** `statement` — Ease Display 400 · 30px/1.2 · tracking -0.06em

### Logo proof ribbon

**Observed:** A 356px Charcoal chapter has a centered 30px question, then white customer marks around 64px high arranged in a horizontal marquee with wide separation.

**Transfer:** Use only legitimate proof marks. When none are available, use equally restrained typographic proof statements rather than invented logos.

**Text style:** `statement` — Ease Display 400 · 30px/1.2 · tracking -0.06em

### White directory ending

**Observed:** The ending returns to white with 24px side insets and 48px top space. Five compact directory columns, certification, legal text and a world-clock column share an eight-column desktop row. Links use 18px/1.1 type with 16px gaps; muted headings use body type. Manifesto, feature-detail and pricing endings extend below this directory into a nearly full-width straight black vector wordmark, about 156px high. The default marketing and culture endings finish after the directory without that lower wordmark.

**Transfer:** Retain the quiet practical directory and a small human detail such as relevant local times. Use a large lower wordmark only in the extended ending variant, and include certification only when earned.

**Text style:** `footer-link` — Ease Standard 400 · 18px/1.1 · tracking -0.06em

### Feature demonstration pair

**Only for:** feature-detail pages

**Observed:** Within the 1152px feature container, a short 30px heading and 18px paragraph stand left of a roughly 560px wide interface fragment, with 120px top and bottom space. Lime capability band and yellow variants alternate with Cream capability canvas. A separate broad product table sits above its heading and support rather than beside them.

**Transfer:** Let each chapter demonstrate one task and its payoff. Alternate composition and field color by meaning, not as a uniform card system.

**Text style:** `statement` — Ease Display 400 · 30px/1.2 · tracking -0.06em

### Feature onward directory

**Only for:** feature-detail endings

**Observed:** A three-part composition sits in a 1152px container with 50px gaps: narrow 'Up next' directory, a 554×483px product image on warm paper, and a 30px explanatory statement with an underlined body link. Inactive directory items are warm grey; the active item is black, displaced right by 40px with a pink zigzag to its left. This ends the feature narrative before the white footer.

**Transfer:** Offer one clear next capability while retaining a browsable directory; keep the current preview substantially larger than the menu.

**Text style:** `directory-link` — Ease Standard 400 · 18px/1.3 · tracking -0.0533em

### Travelling editorial statement

**Only for:** manifesto and culture chapters

**Observed:** A charcoal stage carries a 172.8px white sentence with independently moving letters. It crosses the width during a long scroll passage before yielding to staggered 30px supporting paragraphs. The sentence is the main object, not background decoration.

**Transfer:** Use a short original conviction that warrants theatrical emphasis; keep a readable settled version and supporting argument.

**Text style:** `travelling-statement` — Ease Display 400 · 172.8px/1 · tracking -0.06em

### Sequential principle reading

**Only for:** culture pages

**Observed:** Principle paper carries a 48px introductory statement and similarly sized principle titles and explanations. Text blocks are separated by 96px. A lime geometric marker accompanies the currently emphasized block; other blocks are faded before becoming dark as reading progresses.

**Transfer:** Use this treatment for a small set of real principles or editorial commitments; the active block must remain comfortably readable.

**Text style:** `editorial-lead` — Ease Display 400 · 48px/1.2 · tracking -0.06em

### Custom pricing conversation

**Only for:** pricing pages

**Observed:** A centered white 48px title and staggered white 30px reassurance sit above a 920px stack of Pricing panels on charcoal. Large option tiles come first, followed by paired counters, currencies and a revenue slider, then full-width contact fields with an inset dark submit control. A pink conversion invitation and dark logo ribbon lead into the white footer.

**Transfer:** Use the questionnaire as a transparent conversation about fit and value rather than disguising an arbitrary price behind many fields.

**Text style:** `detail-title` — Ease Display 400 · 48px/1 · tracking -0.06em

## Page flow

**Storyline:** Promise → inspectable product proof → human stakes → decisive invitation → audience or customer proof → useful onward paths → practical directory.

### Broad product marketing and brand introduction

1. **Promise** — Small centered statement above a giant playful letter sculpture.
2. **Product demonstration** — Large horizontal interface sequence on warm paper with synchronized captions.
3. **Human stakes** — Charcoal photographic collage and conversational value argument.
4. **Conversion** — Pink invitation and oversized dark pill.
5. **Audience fit** — Three square photographic applications beside a short introduction.
6. **Social proof** — Staggered colored quotations followed by a dark logo ribbon.
7. **Onward reading** — Four bright editorial resource cards.
8. **Ending** — White multi-column directory, certification/legal area and world clocks; no lower wordmark.

**Transfer:** Use the brand artwork to establish character, then let real product and customer material make the argument. Reorder proof and conversion around the new product's buying decision.

### Explain a specific capability through concrete tasks

1. **Focused promise** — Cream split opening with 48px title, 30px support and interface-fragment collage.
2. **Capability chapters** — Lime and yellow split demonstrations interspersed with a broad cream table view.
3. **Detailed proof** — Large horizontally travelling interface panels with concise explanatory copy beneath.
4. **Onward navigation** — Feature directory, warm-paper preview and explanatory link.
5. **Ending** — White directory followed by a straight monumental black wordmark.

**Transfer:** Keep the benefit specific and each product view tied to a practical task; use the directory as the closing action rather than forcing a conversion band.

### Explain a conviction and invite participation

1. **Problem framing** — Warm-paper opening with a large left statement and stepped supporting paragraphs.
2. **Position** — Centered 48px lead above a triangle, followed by a staggered 30px narrative.
3. **Participation** — Two textured geometric action choices balanced on a beam.
4. **Allied proof** — Charcoal travelling white statement followed by supporting text and inline links.
5. **Ending** — White directory and large straight wordmark.

**Transfer:** Replace industry-specific claims with a substantiated problem and a conviction that belongs to the new product; preserve the expressive typography and balanced-choice metaphor only where meaningful.

### Make an organization feel human and credible

1. **Human introduction** — Small centered sentence above packed circles, photographs and textured shapes.
2. **Organizational context** — Pale-grey split editorial section with a 100px title and 30px explanation.
3. **People proof** — Six-column portrait wall with varied masks and compact role/name captions.
4. **Invitation** — Pink question with oversized chat pill.
5. **Conviction** — Charcoal travelling statement and stepped explanatory paragraphs.
6. **Principles** — Large sequential reading on pale grey, with a lime active marker.
7. **Ending** — White directory and clocks without the lower wordmark.

**Transfer:** Use genuine people and concrete commitments. The organization-specific visual wall and principles stay scoped to culture content.

### Explain a flexible commercial model and qualify a conversation

1. **Commercial promise** — White 48px title and 30px reassurance on charcoal.
2. **Interactive qualification** — Centered stack of white question panels, feature choices, counters, revenue controls and contact fields.
3. **Objection handling** — Stepped white editorial paragraphs about value and adaptability.
4. **Conversion** — Pink question with a large dark chat pill.
5. **Social proof** — White marks on a dark horizontal ribbon.
6. **Ending** — White directory and large straight black wordmark.

**Transfer:** Make the inputs reflect the actual commercial model; do not substitute a conventional three-plan comparison merely for familiarity.

## Writing

Warm, plain-spoken and a little cheeky, with conviction about the people behind the work. The copy acknowledges everyday friction before describing a practical improvement; confidence comes from specificity rather than superlatives.

**Do not copy:** Do not reuse the Streamtime name, logo or distinctive letter artwork, customer names and marks, employee identities, quotations, certification, research statistics, dates, proprietary claims or campaign slogans as facts for another product. Source examples are references for tone only.

- **Addressing the reader:** Speak directly to you and your team; use we for the people making the product. Ask the reader questions in the same language they would use in a conversation.
- **Rhythm:** Short spoken headings, usually 3–8 words, followed by one or two sentences. Long arguments break into stepped paragraphs or compact lines. Contractions, occasional parentheses and a light aside keep the voice human.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A familiar expression made slightly more emphatic; focus on a better way, not a technical category. | 5–9 words | “A way better way of working” |
| Supporting line | An accessible benefit followed by a rhythmic list of active verbs. | 8–14 words | “Balance your workflow: plan, track, collaborate, thrive” |
| Capability heading | Use a light idiom to name a practical improvement. | 4–8 words | “The fastest job in the west”<br>“Groups for wrangling the big ones” |
| Capability explanation | Describe the user's actions plainly, allowing one small conversational aside. | 12–30 words | “Drop in dates, team mates, and estimated hours; and we’ll do all the maths for you (phew).” |
| Conversion invitation | Ask a compact human question rather than issue a sales command. | 2–6 words | “Ready to work well?”<br>“Need specifics?” |
| Primary action | A familiar verb phrase with a clear next step. | 2–4 words | “Book a demo”<br>“Let’s chat” |
| Human-stakes statement | Acknowledge one legitimate priority, then introduce its human counterweight. | 8–18 words | “We get it, profit matters. But so do your people.” |

**Words and phrasing to use:** better; ease; your team; work well; bring it together; balance; phew; let's chat; heads up; we get it

**Avoid:** leverage synergies; enterprise-grade transformation; revolutionary ecosystem; unlock limitless potential; best-in-class solution; impersonal stakeholder jargon

**Rules:**

- Tie each playful phrase to a concrete product benefit in the following sentence.
- Prefer active verbs and recognizable tasks over abstract platform language.
- Use reassurance under form controls to explain why an input matters.
- Allow questions in navigation and conversion copy; keep feature labels straightforward.
- Keep the human and commercial benefits in the same conversation rather than presenting them as opposites.

## Do's and Don'ts

### Do

- Keep core statement text at 30px/36px, weight 400, with -0.06em tracking.
- Use the 24px desktop edge inset for the wide compositions, not a narrow blog container.
- Combine 5px label rectangles and 96px header pills in the same navigation cluster.
- Give large product panels 10px corners and the restrained two-layer product shadow.
- Keep conversion bands compact: 40px vertical padding around a 164px-high dark pill.
- Use 30px padding on quotation cards but 20px on resource cards.
- Place small dry-grain shapes in several contexts so the opening artwork belongs to a coherent visual language.
- Keep footer links compact at 18px/1.1 with 16px row gaps.

### Don't

- Do not make the default canvas charcoal; dark fields are deliberate chapters within a light identity.
- Do not spread hot pink through every section; reserve its broad use for the compact conversion interruption.
- Do not use bold weight to emphasize regular 30px narrative headings.
- Do not give every card a 24px radius; the characteristic resource and quote cards use 5px.
- Do not add glass blur, luminous gradients or glossy dimensional shading to the paper cutouts.
- Do not wrap interface imagery in laptop or phone hardware frames; pale panels are the objects.
- Do not center every testimonial on the same axis; the 800px cards stagger within a 1200px field.
- Do not turn the default ending into another dark sales panel or add a lower monumental wordmark to every page type.

## Motion and responsive

### Motion

**Observed:**

- Large product stages translate horizontally during vertical scrolling while a caption indicator advances.
- Manifesto and culture statements travel letter by letter across charcoal stages before the supporting text becomes the focus.
- A marquee-horizontal animation is declared at 40s linear with infinite repetition for logo motion.
- Two background-color transitions are declared at 0.2s; these are not a universal animation token.
- The sequential principle treatment dims inactive blocks and emphasizes the current text beside a lime marker.

**Transfer:**

- Preserve the relationship between the moving product panel and its caption marker.
- Use motion to manipulate the paper-like objects or letter groups, not to add ambient glowing effects.
- For a static or reduced-motion implementation, show a complete readable statement and all essential product captions rather than reproducing the long pinned scroll distance.

**Unknown:**

- Scroll durations, precise easing for the pinned scenes and hover transforms are not established.
- The full interaction of the culture-opening canvas is not established.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 767px, 768px, 991px, 1280px, 1440px and 1920px.
- The root sizing context is calc(0.398664rem + 0.668151vw).
- The desktop wordmark sculpture, horizontal demonstration and several desktop directory layouts have mobile/tablet visibility variants; exact replacement geometry is not established.

**Transfer:**

- On narrow screens, preserve the centered spoken promise and a readable original letter-and-cutout composition, simplifying the number of objects instead of squeezing all desktop shapes.
- Replace pinned desktop panel travel with a readable sequence or horizontal swipe stage that keeps captions adjacent to each view.
- Stack the conversion question and pill while retaining their dramatic scale contrast; use the 5px-versus-pill distinction for smaller controls.

**Unknown:**

- Mobile typography sizes, navigation replacement, exact breakpoint behavior and the responsive footer arrangement are not established; the transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
