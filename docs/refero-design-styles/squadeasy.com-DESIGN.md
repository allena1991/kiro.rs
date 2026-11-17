# SquadEasy — big type, paper people

## Overview

A buoyant, people-first style with the confidence of a poster and the informality of a handmade collage. Heavy grotesk capitals sit on warm tan and white, interrupted by electric lime, lavender and sky-blue panels. Natural photography, skewed paper cutouts and crisp phone demonstrations make it especially suited to participatory products and approachable B2B services; the overall density is low even when individual proof cards are text-rich.

### Essentials

- Poster-sized promises with a colored payoff: black grotesk capitals at 80px/1, -2px tracking, with the final phrase in pink rather than a gradient.
- A people-framed opening, not a dashboard banner: a centered headline occupies roughly half the screen width on tan, surrounded by irregular portrait cutouts; the lime action and small downward arrow remain visible within 900px.
- Soft capsules against hard paper edges: black action pills use 100px radii and 14px uppercase labels; content cards remain square and carry only a shallow 0px 1.5px 8px shadow.
- Color arrives in broad chapters: tan dominates the opening and early storytelling, white separates chapters, and blue, lavender and lime fill whole proof or conversion panels; pink is concentrated in headline words and small annotations.
- Human proof looks pasted together: natural-color photos in angular masks, alternating slight rotations, compact stat notes and hand-drawn underlines. Use real customer activity or contextual product-use photos when portrait assets are unavailable.
- Make proof monumental as well as intimate: include a colored poster-proof device with oversized black type and a contrasting sticky-note numeral, alongside smaller quote or result cards.
- The ending is a designed object: a lime conversion poster above an inset black footer sheet, both held within a 1240px width and separated by white space; the footer finishes with a subtly oblique lower edge.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric lime | `#e4ff60` | `--color-lime` | background, surface, action, accent | Hero action, inset conversion posters, numeral stickers and small directional accents. It occupies whole selected panels, not every section. |
| Sky-blue paper | `#7fb6e6` | `--color-blue` | background, surface | Inset logo-proof poster and occasional quote or explanatory panels. |
| Lavender paper | `#adabff` | `--color-lavender` | background, surface | Monumental proof band, testimonial cards and result notes; also the backdrop for offer comparison. |
| Warm tan | `#e1c19e` | `--color-tan` | background, surface | Default opening stage and early narrative canvas; also the alternate proof-card fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hot pink annotation | `#ea5da3` | `--color-pink` | text, accent, surface, border | Highlighted hero phrase, drawn underlines, small result notes and active pagination. Keep pink secondary to black typography. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, border, action | All primary text, hairline outlines, black action capsules and the footer sheet. |
| Pale grey paper | `#f6f6f6` | `--color-muted-canvas` | background | Awards and explanatory feature bands; remains nearly white. |
| White paper | `#ffffff` | `--color-canvas` | background, surface, text | Default page canvas, white cards and reversed footer or button lettering. Navigation uses white at 50% alpha over the current section. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| campaign case studies | Campaign red | `#e0493c` | `--color-red` | background | Client-specific opening and implementation chapter canvas, with black text and white content panels. |
| customization demonstrations | Customization teal | `#358a79` | `--color-teal` | text | Single emphasized word in a customization demonstration. |
| environmental benefit pages | Soft green paper | `#c2ebb8` | `--color-green` | surface | Result notes and content cards within environmental benefit storytelling. |

## Typography

- **Black** — Poster headlines, section headings, card titles and large numerals. Very heavy, compact grotesk with blunt terminals and tightly packed capitals. If unavailable, use **Archivo Black**. Use its black cut; retain tight spacing and deliberate line breaks. Font stack: "Black", "Archivo Black", Arial, sans-serif.
- **Body** — Paragraphs, card descriptions, lists and smaller labels. Plain, highly legible sans-serif that lets the heavy display face dominate. If unavailable, use **DM Sans**. Use 400 for paragraphs and 700 for bold action labels. Font stack: "Body", "DM Sans", Arial, sans-serif.
- **Regular** — Navigation, editorial supporting paragraphs and underlined links. Clean geometric-leaning sans with friendly round forms. If unavailable, use **DM Sans**. Use 400; keep the small negative tracking. Font stack: "Regular", "DM Sans", Arial, sans-serif.
- **Medium** — Black pill labels, punchlines, quote emphasis and award captions. A sturdier text sans cut, distinct from the massive display lettering. If unavailable, use **DM Sans**. Use 500 for the medium cut. Font stack: "Medium", "DM Sans", Arial, sans-serif.
- **Sharpie** — Handwritten numeral sticker and compact annotation marks. Slanted, energetic marker lettering with visibly irregular strokes. If unavailable, use **Kalam**. Use 700 for the handwritten numeral. Font stack: "Sharpie", "Kalam", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| monumental-number | Black | 900 | 220px | 1.025 | -0.3px | Single dominant result above the monumental proof statement. |
| monumental-heading | Black | 900 | 110px | 96px | -0.0182em, uppercase | Full-width lavender proof poster. |
| display | Black | 900 | 80px | 1 | -0.025em, uppercase | Default opening promise and major centered chapter headlines. |
| marker-number | Sharpie | 400 | 62px | 0.7 | -0.028em, uppercase | Handwritten numeral inserted into the blue proof headline. |
| benefit-heading | Black | 900 | 62px | 1.025 | -0.0323em, uppercase | Left-aligned benefit opening title and compact product chapter title. |
| result-number | Black | 900 | 60px | 1.025 | -0.0042em, uppercase | Standalone rows of result notes. |
| section-heading | Black | 900 | 56px | 59px | -0.0357em, uppercase | Proof-slider headings and split feature chapters. |
| closing-heading | Black | 900 | 56px | 1.025 | -0.0357em, uppercase | Centered conversion poster statement. |
| floating-stat | Black | 900 | 50px | 1.025 | -0.005em | Small colored result notes layered around photography. |
| card-heading | Black | 900 | 30px | 1.025 | -0.0083em, uppercase | Tall story-card headings and compact explanatory column titles. |
| quote | Body | 400 | 22px | 1.2 | -0.0114em | Long testimonial cards and expanded proof descriptions. |
| editorial-support | Regular | 400 | 22px | 1.2 | -0.0114em | Short mission-style paragraph beside an oversized statement. |
| intro-support | Body | 400 | 20px | 1.2 | -0.0125em | Supporting paragraph in a benefit or story-index opening. |
| text-link | Regular | 400 | 18px | 1.2 | -0.014em, uppercase | Underlined editorial actions. |
| body | Body | 400 | 16px | 1.2 | -0.0156em | Default explanatory text and compact result captions. |
| hero-action | Body | 700 | 16px | 1.2 | -0.0156em, uppercase | Lime action label in the default opening. |
| navigation | Regular | 400 | 14px | 1.214 | -0.018em | Floating navigation labels. |
| button | Medium | 500 | 14px | 1.2 | -0.018em, uppercase | Black action capsule labels. |
| footer-link | Body | 400 | 14px | 1.214 | -0.018em | White footer link rows. |
| tag | Body | 400 | 14px | 1.214 | -0.018em, uppercase | Outlined topic capsules. |
| award-caption | Medium | 500 | 12px | 1.2 | -0.021em, uppercase | Compact outlined award badges. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| culture pages | culture-ticker | Black | 900 | 146px | 0.9 | -6.5px, uppercase | Two oversized moving lines behind a central collage. |
| story index pages | index-heading | Black | 900 | 64px | 1.025 | -0.0313em, uppercase | Editorial introduction above the mixed card grid. |
| campaign case studies | case-heading | Black | 900 | 62px | 1.025 | -0.0484em, uppercase | Client campaign opening title. |
| offer comparison sections | offer-title | Black | 900 | 34px | 1.025 | -0.0074em, uppercase | Heavy suffix paired with a regular-weight product-family prefix. |
| offer comparison sections | offer-list | Body | 400 | 16px | 1.625 | -0.0156em | Feature rows inside white offer sheets. |

**Notes:**

- Display hierarchy is created by size and mass, not a succession of semibold weights. Uppercase headings keep unusually tight tracking; body and navigation retain -0.3px.
- The 80px display is the default. The 62px left-aligned opening belongs to benefit-led layouts; the 64px index title, 62px campaign title and 146px culture ticker are scoped alternatives.
- Keep headline endings deliberate: three to five centered lines in the main opening, two or three in split sections. Paragraphs stay narrow enough to read as compact blocks.
- Offer titles pair the 34px heavy suffix with a 34px regular text-sans prefix; the suffix gets a short hand-drawn underline.

## Layout

**Density:** Airy at section scale, with compact paper-card interiors and dramatic pauses around the headline collages.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Topic-pill horizontal padding and small badge details. |
| 15px | Default desktop grid gutters. |
| 16px | Compact button inset, common text spacing and narrow viewport section gutters. |
| 20px | Result-note side padding and spacing between result columns. |
| 24px | Result-note vertical padding and testimonial side padding. |
| 30px | Story-index grid gaps and case-study result-note inset. |
| 36px | Tall story-card side and top padding. |
| 40px | Testimonial top inset and separation before some editorial actions. |
| 60px | Story-card bottom padding and offer-card vertical inset. |
| 80px | Standard split-feature band vertical padding. |
| 100px | Default section breathing room and desktop outer inset for framed posters. |
| 120px | Editorial introduction and awards-band top spacing. |
| 140px | Comparison chapter vertical padding and testimonial lower reserve. |
| 200px | Specialized hero top spacing and deeply staged conversion entrances. |

### Containers and grids

- **main-container**: max width 1240px · side padding 16px. Centered desktop content; at 1440px the content edges sit 100px from the viewport. Framed posters and footer share these edges.
- **base-grid**: 12 columns · gap 15px. Underlying desktop grid. Split chapters use unequal text and media spans rather than equal generic tiles.
- **floating-header**: max width 1074px. A narrower centered navigation capsule floating over every section, 17px below the viewport top.
- **opening-copy**: max width 800px. Centered promise block; deliberately narrower than the photograph constellation.
- **proof-copy**: max width 858px · side padding 16px. Centered monumental statement with portraits escaping toward the edges.
- **story-grid** (only for story index pages): 3 columns · gap 30px. Mixed tall stories, short statistics and quotations in three columns inside a further 108px side inset.
- **offer-grid** (only for offer comparison sections): 3 columns · gap 15px. Three tall white sheets against a lavender chapter backdrop.

## Corner radius

| Element | Radius |
| --- | --- |
| black-buttons-and-tags | 100px |
| hero-action | 500px |
| floating-navigation | 14px |
| paper-cards | 0px |
| carousel-controls | 100px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| paper-lift | `rgba(0, 0, 0, 0.12) 0px 1.5px 8px 0px` | Shallow lift under result notes, story cards, offer sheets and the translucent header; not a heavy floating dashboard shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Default page background and breathing room between posters.

**CSS:** `background: #ffffff; color: #000000`

#### Tan stage · level 0

**Use:** Opening and early people-centered storytelling.

**CSS:** `background: #e1c19e; color: #000000`

**Observed:** An uninterrupted warm field supports separate cutout photographs and black typography.

**Transfer:** Use as the sustained emotional stage before switching to white editorial sections.

#### Colored chapter · level 0

**Use:** Lavender proof band and broad editorial chapter changes.

**CSS:** `background: #adabff; color: #000000`

**Observed:** Blue is used for an inset logo-proof poster; lime for conversion posters. Grey-white bands provide a quieter explanatory variation.

**Transfer:** Assign one flat fill per chapter, keeping the main text black.

#### Paper note · level 1

**Use:** Results and short proof cards.

**CSS:** `background: #adabff; border-radius: 0px; box-shadow: rgba(0, 0, 0, 0.12) 0px 1.5px 8px 0px`

**Observed:** Cards vary in height with the copy and rotate very slightly; small photographic result notes can rotate more visibly. Lime, blue and pink are supporting note colors.

**Transfer:** Let the physical-paper feeling come from a nearly imperceptible tilt and shallow shadow rather than bevels or texture.

#### Glass navigation · level 2

**Use:** Persistent navigation above every canvas color.

**CSS:** `background: rgba(255, 255, 255, 0.5); border-radius: 14px; box-shadow: rgba(0, 0, 0, 0.12) 0px 1.5px 8px 0px; backdrop-filter: blur(4px)`

**Observed:** It lightly inherits the current section color and softly blurs content beneath it.

**Transfer:** Confine glass to navigation; keep the narrative paper surfaces opaque.

#### Black footer sheet · level 0

**Use:** Final navigation and utility destination.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Inset on white with a gently slanted bottom edge, a generous upper logo area and two spacious information tiers.

**Transfer:** Build the sheet with a polygon mask while leaving all text on an untransformed inner layer.

#### Green result paper · level 1

**Only for:** environmental benefit pages

**Use:** Themed proof notes and related story cards.

**CSS:** `background: #c2ebb8; box-shadow: rgba(0, 0, 0, 0.12) 0px 1.5px 8px 0px`

#### Red case canvas · level 0

**Only for:** campaign case studies

**Use:** Campaign opening and implementation explanation.

**CSS:** `background: #e0493c; color: #000000`

**Observed:** White rectangular text panels and cutout activity imagery create contrast without reversing the headings.

**Transfer:** Reserve this stronger themed canvas for a specific campaign rather than applying it site-wide.

## Components

### Floating navigation

**Use:** Persistent site orientation and conversion.

**CSS:** `display: flex; position: fixed; max-width: 1074px; height: 83px; background: rgba(255, 255, 255, 0.5); border-radius: 14px; backdrop-filter: blur(4px); box-shadow: rgba(0, 0, 0, 0.12) 0px 1.5px 8px 0px; justify-content: space-between`

**Text style:** `navigation` — Regular 400 · 14px/1.214 · tracking -0.018em

**Observed:** Compact two-line identity on the left; navigation and small chevrons across the middle; language selection and a black action capsule to the right. It remains centered near the top through scrolling.

**States:** Declared: hover navigation labels underline and turn #ea5da3; focus-visible unknown.

**Transfer:** Keep the number of labels small enough to preserve the airy center.

### Black action pill

**Use:** Default action in navigation, conversion posters and supporting sections.

**CSS:** `display: flex; align-items: center; background: #000000; color: #ffffff; border-radius: 100px; padding: 16px 14px 16px 16px`

**Text style:** `button` — Medium 500 · 14px/1.2 · tracking -0.018em · uppercase

**Observed:** Label followed by a small lime right arrow; ordinary section examples are 49px tall, while the header action is 51px tall. Width follows the label.

### Lime hero action

**Use:** Primary action in the tan opening.

**CSS:** `background: #e4ff60; color: #000000; border-radius: 500px; padding: 14.4px 32px`

**Text style:** `hero-action` — Body 700 · 16px/1.2 · tracking -0.0156em · uppercase

**Observed:** Centered beneath the colored headline payoff; a separate pink downward arrow sits below. Benefit-led pages use a larger lime capsule with 19.2px 48px padding and a 20px bold label.

**States:** Declared: hover background #e4ff60; focus-visible unknown.

### Underlined action

**Use:** Secondary editorial action beneath a paragraph or proof block.

**CSS:** `display: flex; align-items: center; color: #000000; padding-bottom: 6px; border-bottom: 1px solid #000000`

**Text style:** `text-link` — Regular 400 · 18px/1.2 · tracking -0.014em · uppercase

**Observed:** Only the content width is underlined; a small colored arrow terminates the line.

### Result note

**Use:** Quantified proof in a three- or four-note row.

**CSS:** `background: #adabff; padding: 30px; transform: rotate(0.5deg); box-shadow: rgba(0, 0, 0, 0.12) 0px 1.5px 8px 0px`

**Text style:** `result-number` — Black 900 · 60px/1.025 · tracking -0.0042em · uppercase

**Observed:** Dominant black numeral first, short explanation second, a stronger conversational punchline last. Taller editorial notes use 24px 20px insets and 60px numerals; compact campaign results use 62px numerals with 43.4px line height. Heights follow content, not a forced equal-height grid.

**Transfer:** Use verified product outcomes; retain the number–meaning–human payoff structure.

### Testimonial strip card

**Use:** Horizontal social-proof slider beside a fixed left heading.

**CSS:** `background: #adabff; padding: 40px 24px 140px; position: relative`

**Text style:** `quote` — Body 400 · 22px/1.2 · tracking -0.0114em

**Observed:** Roughly 304px-wide cards mix photo-led stories and text-first quotations. Tiny portrait, role and customer logo sit toward the bottom. The card group slightly tilts and extends beyond the right viewport edge. Tan cards are the case-study variant.

**Transfer:** Mix formats rather than repeating identical quote boxes.

### Circular slider control

**Use:** Paired previous and next controls below feature or testimonial content.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 38px; height: 38px; border: 1px solid #000000; border-radius: 100px`

**Observed:** A simple black chevron is centered in each unfilled circle; the pair sits independently below the content.

### Topic capsule

**Use:** Category label above a story image or an outlined benefit line.

**CSS:** `padding: 8px 10px; border: 1px solid #000000; border-radius: 100px; color: #000000`

**Text style:** `tag` — Body 400 · 14px/1.214 · tracking -0.018em · uppercase

**Observed:** Thin outline with no fill; long labels can wrap while retaining the capsule shape.

### Award badge

**Use:** Compact external validation in a centered wrapped collection.

**CSS:** `display: flex; align-items: center; padding: 10px 16px; border: 1px solid #000000; border-radius: 100px`

**Text style:** `award-caption` — Medium 500 · 12px/1.2 · tracking -0.021em · uppercase

**Observed:** Small 24px emblem at the left, uppercase caption at the right; source name or rating sits beneath, outside the outline. Badge widths follow their text.

### Footer link column

**Use:** Secondary navigation inside the black sheet.

**CSS:** `color: #ffffff; padding-bottom: 14px`

**Text style:** `footer-link` — Body 400 · 14px/1.214 · tracking -0.018em

**Observed:** Four compact columns under uppercase 16px group labels with lime chevrons. A separate lower tier contains download or contact actions, address information, social glyphs and legal links; the language control stays off to the right.

### Story sheet

**Only for:** story index pages

**Use:** Photo-led story in a mixed proof grid.

**CSS:** `background: #e1c19e; position: relative; padding: 36px 36px 60px; transform: rotate(0.5deg); box-shadow: rgba(0, 0, 0, 0.12) 0px 1.5px 8px 0px`

**Text style:** `card-heading` — Black 900 · 30px/1.025 · tracking -0.0083em · uppercase

**Observed:** Topic capsule, angular photo with small pasted customer mark, heavy uppercase title, short description and underlined action. Lime quote cards and lavender stat cards interrupt the tall tan stories.

### Offer sheet

**Only for:** offer comparison sections

**Use:** Compare service formats without a conventional price table.

**CSS:** `position: relative; padding: 60px 26px`

**Text style:** `offer-title` — Black 900 · 34px/1.025 · tracking -0.0074em · uppercase

**Observed:** White paper backing is separately skewed and rotated by 0.5deg with paper-lift shadow; foreground copy remains upright. Title combines light prefix and black suffix, then an outlined proposition, short bold description, colored diamond-bullet list and underlined action.

**Transfer:** Compare meaningful use cases rather than inventing prices; keep different feature-list lengths readable.

## Imagery and graphics

### Angular people collage

**Use:** Opening, emotional chapter illustrations and human proof.

**Observed:** Natural-color portraits and candid groups are cut into irregular four- to six-sided paper shapes. Faces stay recognizable, backgrounds are retained, and individual tiles tilt independently. The opening spreads six portraits around a central text clearing; later scenes use one large portrait with two smaller satellites.

**Transfer:** Use warm, credible people interacting with the new product in daylight. If portraits are unavailable, photograph real hands, tools or product use and give these the same asymmetric paper masks; do not replace the collage with generic icon tiles.

**Build:** Use object-fit: cover images in SVG clipPaths or CSS polygons such as polygon(8% 4%,96% 0%,100% 78%,87% 100%,0% 91%,2% 23%). Vary the polygon for each photo; apply rotations around -6deg to 6deg as design guidance. Stage a central 300px-wide image beside 196px satellites, or distribute 200px–300px tiles around the opening. No rounded frame, thick border or color filter.

### Phone and product-use stage

**Use:** Product reveal following the opening, split feature demonstrations and personalization proof.

**Observed:** A tall black-framed phone with rounded hardware corners, pale screen and lime rim or backing floats above soft natural shadow. The first reveal is centered over a blurred retreating headline. Other chapters combine the phone with an angular lime or green polygon, a small white result card, or an activity photograph; device scale is about 299px–331px wide by 522px–570px tall.

**Transfer:** Show one believable core interaction in a single device or narrow product panel. For a product without a phone UI, use one crisp workflow or output sheet at the same visual scale; keep surrounding photographs and paper accents.

**Build:** Create a black rounded device outline with an inset white interface and restrained shadow; place a flat angular lime polygon behind it, slightly offset. Add at most one small paper annotation crossing an edge. Keep interface colors subordinate to the marketing canvas.

### Paper annotations

**Use:** Handwritten proof numeral, key-word underlines and small emotive stickers.

**Observed:** A lime numeral note interrupts a black headline on blue. Thin hand-drawn curves underline individual words; black hearts or thumbs-up silhouettes sit on small rotated white or lime paper scraps. These are punctuation, not a wallpaper texture.

**Transfer:** Use the same physical-paper vocabulary around a meaningful new claim, number or action.

**Build:** Make the number sticker a flat lime rectangle around 219px by 121px, rotated -6deg, with a 62px marker numeral. Draw an SVG quadratic underline with a shallow upward bend, no fill and a 3px stroke in pink, lavender or lime. Build a sticker from an irregular white quadrilateral, rotate it slightly and center a single black solid symbol; a shallow paper shadow is enough.

### Logo proof row

**Use:** Lower edge of the blue proof poster.

**Observed:** Small largely monochrome customer marks form a single horizontal run below the oversized headline and bordered action; whitespace separates each mark and the row can extend beyond the poster edge.

**Transfer:** Use genuine integrations, endorsements or partner marks at optically balanced heights; when those are unavailable, use concise verified proof labels rather than fabricated logos.

### Cut-paper footer backing

**Use:** Final full navigation block.

**Observed:** A broad black sheet on white, 1240px wide at desktop, with straight upper edge and lower edge rising slightly to the right. Its silhouette provides the handmade quality without a distressed texture.

**Transfer:** Retain the physical-paper finish with the new identity and utility content.

**Build:** Use a black pseudo-element behind the footer content with clip-path: polygon(0% 0%,100% 0%,100% 96.5%,0% 100%). Give the foreground around 80px top, 106px side and 136px bottom inset; keep all content upright and clear of the cut edge.

### Culture collage and ticker

**Only for:** culture pages

**Use:** Express the organization’s personality in the opening and team section.

**Observed:** Two enormous, slightly oblique lines of black type run beyond both viewport edges on lime, behind three angular workplace photographs. A separate six-person portrait collage uses colored polygon backings and a heart sticker rather than a conventional avatar grid.

**Transfer:** Use a short internal belief as the repeated phrase and candid images of the actual team. The minimum version is two clipped text lines and three differently sized photographs, not an illustrated mascot.

**Build:** Duplicate the uppercase 146px phrase in two overflow-hidden horizontal tracks, rotate the tracks about -2deg and layer a roughly 385px-wide central image above them with smaller satellites. For the team collage, arrange six masked head-and-shoulders portraits around an irregular white heart sticker, using lime, lavender, tan, green and red paper backings.

### Campaign media collage

**Only for:** campaign case studies

**Use:** Opening evidence, gallery and video testimonial.

**Observed:** A large angular activity photo occupies the right side of a red hero, with a pasted white customer mark. The following white gallery lays out four differently skewed event photographs. The video story uses a small thumbnail and translucent round play control over a tall colored polygon, beside an oversized title and customer identity.

**Transfer:** Use actual process or customer activity material. Keep the gallery informal and the video clearly identifiable as playable; do not turn the full-width composition into a decorative empty rectangle.

### Icons

**Observed:** Simple filled glyphs and tiny directional arrows rather than a large outline-icon system. Action arrows are around 16px–17px and lime on black or pink on white; carousel controls contain black 17px chevrons. Social marks are white on the black sheet. Hearts and thumbs-up are solid black paper-sticker motifs.

**Transfer:** Choose a small, consistent solid-glyph set. Use arrows for actions, diamonds for comparison bullets and one expressive sticker symbol where emphasis is useful.

## Section recipes

How recurring sections are built.

### First screen: People-framed poster opening

**Observed:** A full-height tan first screen sits behind the narrow Floating navigation. Six angular portrait tiles orbit the perimeter, with some deliberately cut off by the left and right edges; none occupies the central reading space. The centered 80px/1 headline spans about half the width in five close lines, with the final two lines pink. Back-to-front layers are flat tan, scattered photographs, central lettering and Lime hero action, then navigation. The headline begins well below the header and the lime capsule sits beneath it with a pink downward arrow. Within the first 900px, headline, portraits and action are all visible; no supporting paragraph is present. The 331px-wide phone appears in the subsequent reveal below the initial viewport, centered in front of the receding headline.

**Transfer:** Frame a sharply phrased promise with people using the new product. If no people library exists, make three to six original contextual use photographs with angular masks. Preserve the centered text clearing and single lime action. Benefit pages instead open with left-aligned 62px type, short explanatory text and one large right-hand photo; indexes use a white editorial opening; campaign stories use the red split composition; culture pages use the oversized ticker collage.

**Avoid:** Do not put the phone, six portraits, paragraph and headline all into one crowded initial screen. Do not replace the asymmetrical portrait orbit with a symmetric three-card feature grid.

**Text style:** `display` — Black 900 · 80px/1 · tracking -0.025em · uppercase

### People-and-result chapter

**Observed:** A centered display headline at 80px precedes a three-photo collage with one dominant 300px-wide tile and two smaller satellites. Compact colored result notes layer around the image group and an Underlined action sits below. Tan continues between the headline and media rather than enclosing each in a card.

**Transfer:** Give each chapter one human outcome and a small number of verified results. Preserve the contrast between a bold verbal statement and an informal photographic cluster.

**Text style:** `display` — Black 900 · 80px/1 · tracking -0.025em · uppercase

### Blue proof poster

**Observed:** An inset blue panel uses the main 1240px width, a centered 80px black statement and a lime Marker-number sticker inside the line. A bordered action sits near the lower region above a low horizontal logo row. The surrounding white border-space is 100px on the sides and below.

**Transfer:** Use this as a signature proof interruption wherever the story needs credibility; insert a real count or short proof phrase into the poster rather than reproducing the same claim.

**Text style:** `display` — Black 900 · 80px/1 · tracking -0.025em · uppercase

### Monumental proof band

**Observed:** Lavender spans the viewport with 80px vertical padding. A centered 220px numeral sits above a 110px/96px uppercase statement in an 858px-wide text zone. Portrait fragments emerge from the outer edges without competing with the central claim.

**Transfer:** Turn one defensible outcome into an oversized typographic event. If the product lacks a meaningful count, use a short factual phrase with the same black-on-lavender scale contrast.

**Text style:** `monumental-heading` — Black 900 · 110px/96px · tracking -0.0182em · uppercase

### Split editorial feature

**Observed:** White, pale grey, lavender or lime bands pair a roughly 397px by 516px masked photo or product object with compact text. Major bands use 80px vertical padding. The 56px/59px heading gets a curved accent underline, followed by one short explanation and sometimes a second smaller paragraph. Media and text alternate sides across chapters.

**Transfer:** Explain one mechanism per split, showing either real usage or a single legible product outcome; keep the heading and illustration visually larger than the copy.

**Text style:** `section-heading` — Black 900 · 56px/59px · tracking -0.0357em · uppercase

### Proof strip with anchored heading

**Observed:** A 56px/59px heading occupies the left portion while Testimonial strip cards flow out to the right, with a partial next card visible. Circular slider controls sit below the strip. The tan chapter uses lavender cards; the white case-study variant uses tan cards.

**Transfer:** Combine quotes, activity images and outcome stories in the same horizontal paper strip rather than forcing all proof into identical testimonials.

**Text style:** `section-heading` — Black 900 · 56px/59px · tracking -0.0357em · uppercase

### Conversion poster and footer

**Observed:** A lime inset panel, 1240px wide and 450px tall, holds a centered 56px uppercase invitation, a tiny white heart scrap and one Black action pill. Its inner padding is 100px vertically and 106px horizontally. The following footer is separated by 100px white space and uses Black footer sheet with a large white identity, four navigation columns, a language control and a lower utility tier.

**Transfer:** Use a brief invitation tied to the new product’s main next step. Retain the lime poster and inset black sheet as the default close; the offer-comparison variant supplies its conversion action within the sheets instead.

**Text style:** `closing-heading` — Black 900 · 56px/1.025 · tracking -0.0357em · uppercase

### Mixed story index

**Only for:** story index pages

**Observed:** A 64px uppercase headline and 20px support paragraph open on white with about 196px top padding. A small sector filter precedes a three-column, 30px-gap grid. Tall tan Story sheets are interrupted by lime quotations and lavender result notes; understated pagination follows. A lime conversion poster then leads into the black footer.

**Transfer:** Use mixed card heights and content formats to make the archive feel curated; maintain a clear category, title and action hierarchy.

**Text style:** `index-heading` — Black 900 · 64px/1.025 · tracking -0.0313em · uppercase

### Campaign explanation

**Only for:** campaign case studies

**Observed:** A red split opening is followed by a white activity gallery. The red implementation chapter has a large left heading, stacked white context/objective/result panels on one side and a product/photo collage on the other. A video proof panel follows, then a three-note lavender result row and a lime quote band before related proof cards.

**Transfer:** Map this to problem, approach and outcome. Let the campaign color organize the narrative, while white panels provide readable long-form detail.

**Text style:** `case-heading` — Black 900 · 62px/1.025 · tracking -0.0484em · uppercase

### Culture belief chapters

**Only for:** culture pages

**Observed:** The lime ticker opening is followed by a narrow 26px editorial manifesto. Blue three-column statements, a pale-grey image/text band, a lime trio of playful animal-photo value cards, four lavender result notes, two blue leader quotations and an awards band build the middle. A six-portrait collage and a monumental lavender partner poster carry the final proof.

**Transfer:** Translate the format to the new organization’s real beliefs, working methods and people. Animal imagery is a culture-specific humorous metaphor, not a requirement for ordinary landing pages.

**Text style:** `culture-ticker` — Black 900 · 146px/0.9 · tracking -6.5px · uppercase

### Offer comparison ending

**Only for:** offer comparison sections

**Observed:** A lavender chapter begins with a centered 56px heading and compact support copy, then three white Offer sheets. Each sheet has a mixed-weight title, drawn underline, outlined proposition and diamond-bullet feature list. The chapter goes directly into white spacing and the Black footer sheet, without a separate lime conversion poster.

**Transfer:** Use for comparing engagement formats or packages. Preserve the paper sheets and strong section color even when prices are absent.

**Text style:** `section-heading` — Black 900 · 56px/59px · tracking -0.0357em · uppercase

## Page flow

**Storyline:** Emotional promise → tangible product use → human and quantified proof → focused benefit chapters → external validation → a simple conversion invitation and substantial footer.

### Flagship marketing landing page: make the product feel human before explaining its mechanics

1. **promise** — Tan portrait-orbit poster with pink payoff and lime action.
2. **product demonstration** — Centered phone reveal over a retreating promise.
3. **capability chapters** — Large statements, activity-photo collages and small colored result notes, interrupted by the blue logo-proof poster.
4. **brand rationale** — Oversized identity statement paired with a short conversational mission paragraph.
5. **quantified proof** — Monumental lavender result band.
6. **product demonstration** — Tabbed copy and a single large phone with circular controls.
7. **social proof** — Mixed testimonial strip and compact awards badges.
8. **conversion paths** — A lime invitation panel and a white customization demonstration.
9. **closing call** — Lime conversion poster followed by the inset black footer.

**Transfer:** Use the same contrast between emotional staging, tangible demonstration and proof without inheriting the source’s topics or chapter count.

### Detailed customer story: connect a specific challenge to credible outcomes

1. **promise** — Red split hero with campaign title, narrative introduction and customer activity photograph.
2. **social proof** — Angular four-photo gallery on white.
3. **approach** — White explanation panels and product-use collage on the red campaign canvas.
4. **customer testimony** — Video thumbnail panel with explicit play affordance.
5. **quantified proof** — Three lavender result notes.
6. **human proof** — Lime quote band and tan related-story strip.
7. **closing call** — Lime invitation and shared black footer sheet.

**Transfer:** Build a challenge–approach–outcome account with real activity media; use the campaign palette only in its own narrative.

### Story index: make a large proof library enjoyable to browse

1. **introduction** — White editorial opening with heavy title and friendly support line.
2. **navigation** — Small outlined category filter.
3. **social proof** — Three-column mixed story, quote and stat paper grid.
4. **continuation** — Compact numbered pagination with pink current-page outline.
5. **closing call** — Lime invitation and black footer sheet.

**Transfer:** Mix content forms while keeping filters and pagination visually secondary.

### Culture and company narrative: establish personality and shared conviction

1. **belief** — Lime oversized two-track ticker with overlapping people photographs.
2. **rationale** — Narrow manifesto and blue three-column explanation.
3. **identity** — Team history split and playful photographic values trio.
4. **quantified proof** — Four lavender notes, two blue leader quotes and compact awards.
5. **human proof** — Team collage and monumental lavender partner poster.
6. **closing call** — Lime invitation and shared black footer sheet.

**Transfer:** Borrow the expressive typography and real-people collage, but structure the story around the new team’s own beliefs and evidence.

### Benefit-led solution landing page: move efficiently from promise to practical offer

1. **promise** — White split opening with 62px headline, short benefit text, large right photo and lime action.
2. **quantified proof** — Three soft-green result notes.
3. **capability chapters** — Alternating photo and product splits on grey, white and lavender; a pair of green and lavender story cards adds concrete examples.
4. **offer selection** — Lavender chapter with three white offer sheets and underlined conversion actions.
5. **ending** — Direct transition from offers into white spacing and the shared inset black footer; no separate lime closing poster.

**Transfer:** Lead with one clear benefit, substantiate it early, then explain mechanisms and compare suitable formats.

## Writing

Confident, warm French with a conspiratorial smile. It makes business outcomes approachable through wordplay, everyday expressions and lightly cheeky asides, then grounds them in specific proof.

**Do not copy:** Do not reuse the identity, customer names or logos, product names, campaign titles, proprietary artwork, numerical claims, awards, quotations or participant results. Source examples illustrate voice only; replace all factual content with verified material for the new product.

- **Addressing the reader:** Address the reader as vous and vos; speak as nous, on or notre. The tone is conversational but remains appropriate for organizational buyers, with occasional colleague-to-colleague phrasing.
- **Rhythm:** Headlines are short poster statements, usually 4–10 words, with deliberate line breaks. Supporting copy is compact and spoken; one plain explanation is often followed by a wry sentence or rhetorical question. Exclamation marks appear selectively.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Rework a familiar phrase into an emotionally concrete product promise. | 4–14 words | “Vous n'avez jamais été aussi proche de rapprocher vos salariés”<br>“Voyez la vie en vert” |
| Section heading | Use a colloquial turn of phrase, parallelism or a small pun rather than a feature noun. | 3–10 words | “La cohésion, oui mais pas pour rien !”<br>“UNE MAIN LAVE L’AUTRE” |
| Support line | Explain the practical action in plain language, then add a brief human aside. | 1–3 compact sentences | “Personnalisez l'application aux couleurs de votre marque. Ni vu, mais connu.” |
| Proof introduction | Hand the authority to other people rather than claiming superiority directly. | 6–12 words | “C'est pas nous, c'est eux qui le disent.” |
| Result punchline | Follow the factual outcome with a recognizably human business benefit. | 5–12 words | “De quoi donner le sourire à la compta.” |
| Primary action | Direct infinitive or invitation, short enough for a capsule. | 2–4 words | “Demander une démo”<br>“En savoir plus” |

**Words and phrasing to use:** ensemble; vous / vos; on / nous; de quoi…; car entre nous…; qui dit mieux ?; concrete verbs; familiar expressions with one purposeful twist

**Avoid:** bureaucratic abstractions; unearned superlatives; dense technical jargon; relentless jokes; aggressive scarcity language

**Rules:**

- Let a headline carry the joke; let the paragraph explain the actual mechanism.
- Attach a number to a clear outcome, time frame or audience, not a decorative percentage without context.
- Use one light aside after a result, not several competing punchlines.
- Keep actions literal even when surrounding headings are playful.
- Prefer human consequences and collective agency over faceless corporate transformation language.

## Do's and Don'ts

### Do

- Set the main poster promise at 80px/1 with -2px tracking and deliberate uppercase line breaks.
- Use 1240px as the shared desktop edge for inset blue, lime and black sheets.
- Keep the navigation narrower at 1074px, with 14px corners and 4px backdrop blur.
- Pair square paper cards with 100px-radius action capsules rather than one universal radius.
- Keep the default text at 16px and expand testimonial copy to 22px where it becomes the main content.
- Use shallow rgba(0,0,0,0.12) paper shadows and slight independent tilts.
- Keep black as the principal text color even on lime, blue, lavender and campaign red.
- Give split image/text bands 80px vertical breathing room and conversion posters 100px inner vertical padding.

### Don't

- Do not soften the heavy uppercase display into a medium-weight rounded headline system.
- Do not use gradient headline fills; emphasis is one flat pink or scoped teal phrase.
- Do not apply the navigation’s glass treatment to story cards or result notes.
- Do not give paper cards 14px rounded corners; that corner treatment belongs to navigation.
- Do not turn the page into an all-black theme; the dark region is the inset footer sheet and action pills.
- Do not align every photo to a uniform rounded rectangle or identical aspect ratio.
- Do not turn small result notes into glossy dashboard widgets with deep shadows or bevels.
- Do not spread hot pink across all section backgrounds; use tan and white for continuity and the broad blue, lavender or lime chapters for contrast.

## Motion and responsive

### Motion

**Observed:**

- The opening changes from a clear portrait-framed promise to a centered product object while the headline behind it recedes and blurs.
- The hero label declares a transform transition of 0.5s cubic-bezier(0, 0, 0.2, 1).
- Other declared motion includes 0.2s color and transform transitions, 0.4s opacity/transform transitions and a 28s linear horizontal translation loop with 1s delay.
- Counters display final nonzero values in settled views; result notes and headings participate in reveal motion.

**Transfer:**

- Retain the two-part promise-to-product reveal rather than showing both at equal emphasis immediately.
- Keep the culture ticker behind the photo collage and confined to that page type.
- Reveal paper notes as opaque readable objects once settled; motion must not become a permanently translucent card treatment.

**Unknown:**

- Exact scroll mapping, counter durations, transition timing for every component and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 568px, 767px/768px, 991px/992px, 1139px, 1280px and 1383px; additional opening-specific breakpoints occur at 380px.
- Desktop uses a 12-column grid with 15px gutters and fixed maximum content widths.

**Transfer:**

- On narrow screens, preserve the centered promise and lime action; reduce the number of perimeter portraits and let them hug outer edges rather than blocking the copy.
- Stack split chapters and offer sheets while keeping the angular media and flat chapter colors.
- Keep the blue proof numeral note attached to its sentence and retain the black footer sheet inside white outer spacing.
- Let the culture ticker continue beyond the viewport, but keep its supporting sentence and main photograph readable.

**Unknown:**

- Only desktop composition is established; exact mobile sizes, menu behavior and breakpoint-specific rearrangements are not known.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
