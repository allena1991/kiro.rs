# Niccolò Miranda — ink on spectacle

## Overview

An exuberant digital newspaper: warm grey paper, near-black ink and towering condensed serif lettering meet painterly illustration and richly colored project scenes. The feeling is handmade, theatrical and densely editorial rather than minimalist. It suits distinctive creative products, studios and launches that can turn their work into visual stories, with intimate serif prose balancing oversized typographic compositions.

### Essentials

- A masthead becomes the main object, not a logo above a conventional hero: uppercase Canopee at 532.8px/345.6px, weight 400, -0.05em tracking, reversed out of a near-black rectangular band spanning the paper.
- The opening behaves like a newspaper front page: a 97px masthead bar, a three-part editorial rail with 418×158px pictures flanking a centered 64.8px heading, then a monumental name band with 28.8px outer margins.
- Actions look printed, not software-native: the major action is a 441×187px ellipse with 50% radius, a 1px half-ink outline and 86.4px Canopee lettering; the closing action is a square-cornered ink rectangle.
- Color is enclosed inside pictures or tiny editorial markers: #cdc6be paper and #1d1d1b ink dominate all typography and structure; #c03f13 appears in roughly 30×23px novelty badges, never broad promotional fills.
- Pictures and words form a single typeset collage: sharp 1px image frames, close-up painterly subjects on muted brown backing, and 446.4px uppercase words fill complementary rectangular spaces. Without custom illustration, use tightly framed product still lifes in the same warm, tactile light.
- The page must retain physical-paper details and a moving invitation: a multiply texture at 0.3 opacity, hairline column dividers, inset dashed testimonial frames, and a 158px-high ruled closing ticker mixing 86.4px serif prose with reversed condensed action labels.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion marker | `#c03f13` | `--color-new` | accent, surface | Tiny New labels adjacent to project titles. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Illustration ground | `#e2dedb` | `--color-image-ground` | surface | Neutral backing beneath framed illustrations; the actual artwork supplies the visible brown and flesh tones. |
| Oval paper | `#d3cbc2` | `--color-action-paper` | surface, action | Slightly warmer fill for the oversized elliptical action. |
| Aged paper | `#cdc6be` | `--color-paper` | background, surface, text | Default warm grey canvas and reversed text inside ink bands. |
| Printing ink | `#1d1d1b` | `--color-ink` | text, background, border, action | All principal type, solid masthead bands and strong outlines. Half-opacity ink gives quiet column edges; 0.3-opacity ink gives lighter rules. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| case-study galleries | Gallery ground | `#ece9e6` | `--color-gallery-ground` | surface | Light underlying backing for large project imagery. |
| profile and career pages | Experience paper | `#beb5ab` | `--color-card-paper` | surface | Darker paper beneath career cards; keep the visible treatment close to the surrounding stock. |

## Typography

- **Canopee** — Uppercase headlines, masthead words, actions, names and footer links. Extremely tall, narrow display serif with dramatic stroke contrast and sharp wedge-like terminals. If unavailable, use **Bodoni Moda**. Use weight 500 and condense display lettering horizontally to retain the narrow silhouette. Font stack: "Canopee", "Bodoni Moda", Georgia, serif.
- **Editorial New** — Body copy, descriptions, invitations and expressive sentence-case statements. Light, high-contrast editorial serif with narrow proportions and delicate hairlines. If unavailable, use **Cormorant Garamond**. Use weights 300 and 500; retain tight tracking and compact measures. Font stack: "Editorial New", "Cormorant Garamond", Georgia, serif.
- **Domaine Display** — Selected rounded letters embedded inside uppercase Canopee headings. Broader sculptural serif shapes interrupt the very condensed lettering, especially C, G and O. If unavailable, use **DM Serif Display**. Use regular weight for substituted glyphs and tune baseline alignment. Font stack: "Domaine Display", "DM Serif Display", Georgia, serif.
- **Germgoth** — Oversized proof numerals. Tall elegant numerals with a calligraphic serif silhouette. If unavailable, use **Bodoni Moda**. Use weight 400 for isolated numerals. Font stack: "Germgoth", "Bodoni Moda", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| masthead | Canopee | 400 | 532.8px | 345.6px | -0.05em, uppercase | fixed | Single-word first-screen identity inside an ink band. |
| collage-word | Canopee | 400 | 446.4px | 288px | -0.05em, uppercase | fixed | Large words arranged alongside illustrations as a typographic mural. |
| word-band | Canopee | 400 | 432px | 288px | -0.05em, uppercase | fixed | Monumental short chapter word on ink. |
| proof-number | Germgoth | 400 | 158.4px | 86.4px | -0.0039em | fixed | Large proof numeral beside a two-line description. |
| section-heading | Canopee | 400 | 122.4px | 95px | -0.05em, uppercase | fixed | Stacked capability lines, each sitting above a fine rule. |
| alternate-letter | Domaine Display | 500 | 122.4px | 95px | -0.02em, uppercase | fixed | Rounded substitute glyphs within section-heading lettering. |
| oval-label | Canopee | 400 | 86.4px | 1 | -0.04em, uppercase | fixed | Main elliptical action text. |
| closing-line | Editorial New | 300 | 86.4px | 115.2px | -0.04em | fixed | Repeating sentence-case invitation in the closing ticker. |
| email-label | Canopee | 400 | 86.4px | 57.6px | -0.0072em | fixed | Reversed rectangular action embedded in the closing ticker. |
| proof-title | Canopee | 400 | 72px | 1 | -0.045em, uppercase | fixed | Bold-looking but regular-weight bottom line of a proof label. |
| rail-heading | Canopee | 400 | 64.8px | 1 | -0.05em, uppercase | fixed | Centered editorial rail titles. |
| rail-deck | Editorial New | 300 | 37.4px | 1.154 | -0.03em | fixed | Centered two-to-three-line explanation beneath a rail title. |
| body | Editorial New | 300 | 32.4px | 1.2 | -0.019em | size 2.25vw | Primary explanatory paragraphs, often beginning with a reversed drop capital. |
| quote | Editorial New | 300 | 31.7px | 1.364 | -0.03em | fixed | Underlined endorsement text inside overlapping paper cards. |
| attribution | Canopee | 400 | 31.7px | 0.909 | -0.03em, uppercase | fixed | Endorser names beside circular portraits. |
| proof-label | Editorial New | 300 | 24.5px | 1.176 | -0.03em, uppercase | fixed | Smaller top line of a proof label. |
| footer-link | Canopee | 400 | 21.6px | 1 | -0.0287em, uppercase | fixed | Compact social link row at the foot of the paper. |
| caption | Editorial New | 300 | 17.3px | 1.25 | -0.01em | fixed | Short project abstracts, tips and small supporting copy. |
| badge | Canopee | 400 | 17.3px | 1.25 | -0.036em | fixed | Tiny reversed novelty marker. |
| nav-note | Editorial New | 300 | 16.2px | 1.11 | normal | fixed | Small location or contextual text at the left of the masthead bar. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| profile pages | profile-masthead | Canopee | 400 | 475.2px | 0.697 | -0.05em, uppercase | fixed | Full-width reversed profile title. |
| case studies | case-heading | Canopee | 400 | 273.6px | 187.2px | -0.05em, uppercase | fixed | Stacked editorial story heading beside a project image. |
| case studies | case-reverse | Canopee | 400 | 244.8px | 0.647 | -0.05em, uppercase | fixed | Final word of the story heading reversed on ink. |
| profile pages | manifesto | Editorial New | 300 | 105.1px | 108px | -0.05em | fixed | Large sentence-case positioning statement beneath a profile masthead. |
| profile and career pages | career-heading | Editorial New | 300 | 60.5px | 1.024 | -0.04em | fixed | Two-line career card heading. |
| editorial archives | archive-title | Editorial New | 500 | 43.2px | 1 | -0.04em | fixed | Publication or resource title in a numbered index. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The display face remains weight 400 even when it feels bold; its width, contrast and tight spacing create the impact.
- Treat very large words as fitted compositions. Keep their cap-height visually close to the band edges, using padding rather than normal prose leading.
- Use broader alternate serif glyphs selectively inside condensed uppercase headings; do not replace entire headings with the alternate family.
- Sentence-case editorial copy provides the contrast to all-caps display lettering. Drop capitals sit on small square ink grounds and occupy several text lines.

## Layout

**Density:** Dense editorial composition with narrow paper margins; breathing room comes from column separation and oversized type rather than empty hero space.

### Spacing

| Value | Use |
| --- | --- |
| 7.2px | Tiny badge-to-title separation and small label insets. |
| 14.4px | Image-to-title and title-to-description separation in editorial teasers. |
| 28.8px | Page side margins, archive top padding and footer information gap. |
| 36px | Navigation vertical padding and testimonial top inset. |
| 43.2px | Primary column gutters, card side padding and section inner spacing. |
| 57.6px | Major grid row separation and story-to-gallery gutter. |
| 72px | Case-study story separation and career-section bottom padding. |
| 135px | Opening content offset below the masthead bar. |

### Containers and grids

- **paper-width**: max width 1440px · side padding 28.8px. At desktop, the paper fills the viewport; the working content area is 1382px wide, not a narrow centered website column.
- **editorial-rail**: 3 columns · gap 43.2px. Two image-led teasers flank a centered text module. Teaser measures are capped at 417.6px; the center is separated by vertical rules.
- **asymmetric-feature**: 3 columns · gap 43.2px. One narrow text-and-portrait column beside a two-column-width picture and a stack of display lines.
- **story-spread** (only for case studies): 2 columns · gap 57.6px · side padding 28.8px. A 605px editorial story panel and a 720px framed project visual.
- **publication-grid** (only for editorial archives): 3 columns · gap 0px · side padding 28.8px. Continuous rows of numbered editorial links divided by light horizontal rules.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | main-ellipse | 50% |
|  | paper-cards | 11.5px |
|  | novelty-label | 2.9px |
| case studies | utility-controls | 8.6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| paper-overlap | `-4px 4px 6px 0px rgba(29,29,27,0.2)` | Small offset shadow on overlapping endorsement cards; not a general elevation system. |

### Surfaces

#### Paper canvas · level 0

**Use:** Continuous background for the whole editorial composition.

**CSS:** `background-color: #cdc6be; color: #1d1d1b`

**Observed:** Warm grey stock carries visible fibrous mottling. A separate texture layer uses opacity 0.3 and multiply blending across text, art and background.

**Transfer:** Keep the stock continuous between sections rather than alternating generic light panels.

#### Paper grain · level 1

**Use:** Fine tactile layer over the paper.

**CSS:** `opacity: 0.3; mix-blend-mode: multiply; pointer-events: none`

**Observed:** Fine irregular fibers and soft cloudy variations, not a regular dot pattern.

**Transfer:** Use a low-contrast seamless grayscale paper texture over the canvas.

#### Ink band · level 1

**Use:** Word-sized rectangular reversals and monumental mastheads.

**CSS:** `background-color: #1d1d1b; color: #cdc6be; border-radius: 0px`

**Observed:** Type almost fills the band, with no gradient or raised edge.

**Transfer:** Fit short, meaningful product words to the rectangle.

#### Framed illustration · level 1

**Use:** Large cropped portraits and product art.

**CSS:** `background-color: #e2dedb; border: 1px solid #1d1d1b; overflow: hidden; border-radius: 0px`

**Observed:** The frame is a sharp newspaper picture boundary, not a floating image card.

**Transfer:** Use the image itself to supply warmth, depth and richer color.

#### Career stock · level 1

**Only for:** profile and career pages

**Use:** Timeline and availability cards.

**CSS:** `background-color: #beb5ab; border: 1px solid #1d1d1b; border-radius: 11.5px`

**Observed:** Dashed inset detailing softens the formal card; the finish remains paper-like.

**Transfer:** Reserve this card stock for biographical or timeline content.

## Components

### Masthead navigation

**Use:** Persistent editorial identity and menu access.

**CSS:** `display: flex; justify-content: space-between; background-color: #cdc6be; padding: 36px 28.8px; height: 97px`

**Text style:** `nav-note` — Editorial New 300 · 16.2px/1.11

**Observed:** Small contextual note at left, a compact blackletter-style publication identity centered, and two thin menu lines at right. A fine bottom rule separates it from the paper.

**Transfer:** Create a compact publication-style identity for the new product rather than a long navigation link list.

### Editorial teaser

**Use:** Compact linked visual proof in opening and closing rails.

**CSS:** `max-width: 417.6px; margin-right: 43.2px; overflow: hidden`

**Text style:** `caption` — Editorial New 300 · 17.3px/1.25 · tracking -0.01em

**Observed:** A wide, shallow framed picture leads; a compact title or wordmark follows, then a two-to-three-line abstract. A novelty badge sits inline with selected titles.

**Transfer:** Use real product imagery or a composed still life; keep the short abstract specific to what the linked item does.

### Rail centerpiece

**Use:** Invitation to explore the neighboring visual stories.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 0px 43.2px; border-left: 1px solid rgba(29,29,27,0.5); border-right: 1px solid rgba(29,29,27,0.5)`

**Text style:** `rail-heading` — Canopee 400 · 64.8px/1 · tracking -0.05em · uppercase

**Observed:** Uppercase title, centered editorial deck, then a small Tip line instructing lateral exploration. It shares the height of the adjacent teasers rather than becoming a separate banner.

**Transfer:** Use the title for the collection and the deck for a concise reason to browse.

### Elliptical action

**Use:** Dominant action within a narrow editorial column.

**CSS:** `display: flex; justify-content: center; align-items: center; width: 441px; height: 187px; background-color: #d3cbc2; color: #1d1d1b; border: 1px solid rgba(29,29,27,0.5); border-radius: 50%; overflow: hidden`

**Text style:** `oval-label` — Canopee 400 · 86.4px/1 · tracking -0.04em · uppercase

**Observed:** A deliberately oversized horizontal oval occupies almost the whole column. Case-study versions expand to 569×216px.

**Transfer:** Keep labels short enough to preserve the generous ellipse around the lettering.

### Novelty badge

**Use:** Small status marker next to selected teaser titles.

**CSS:** `background-color: #c03f13; color: #cdc6be; border-radius: 2.9px; padding: 1.4px 3.6px 0px; margin-left: 7.2px`

**Text style:** `badge` — Canopee 400 · 17.3px/1.25 · tracking -0.036em

**Observed:** The only recurring saturated interface accent is a very small warm red rectangle.

**Transfer:** Apply sparingly to genuinely fresh content.

### Proof strip

**Use:** Quantified proof integrated into a newspaper rule band.

**CSS:** `display: flex; justify-content: space-between; border-top: 1px solid #1d1d1b; border-bottom: 1px solid #1d1d1b; padding: 50.4px 0px 43.2px`

**Text style:** `proof-number` — Germgoth 400 · 158.4px/86.4px · tracking -0.0039em

**Observed:** Four compact groups each place a huge numeral to the right of a centered two-line label: small editorial capitals above a larger condensed noun. Numerals are not stacked above explanations.

**Transfer:** Replace accolades with substantiated product metrics while keeping the side-by-side number treatment.

### Endorsement card

**Use:** Tactile overlapping social proof.

**CSS:** `width: 576px; height: 360px; background-color: #cdc6be; border: 2.5px solid #1d1d1b; border-radius: 11.5px; box-shadow: -4px 4px 6px 0px rgba(29,29,27,0.2); padding: 36px 43.2px 43.2px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `quote` — Editorial New 300 · 31.7px/1.364 · tracking -0.03em

**Observed:** Cards overlap heavily into a horizontal fan. Each includes an inset dashed frame, underlined quotation, a 43px circular portrait and uppercase attribution above a small role line.

**Transfer:** Preserve the fan and printed border treatment; use authentic endorsements and enough width for readable quotations.

### Ticker action

**Use:** Conversion label repeated inside the closing invitation.

**CSS:** `background-color: #1d1d1b; color: #cdc6be; padding: 7.2px 11.5px 11.5px; margin-left: 21.6px; border-radius: 0px`

**Text style:** `email-label` — Canopee 400 · 86.4px/57.6px · tracking -0.0072em

**Observed:** Reversed condensed lettering interrupts the flowing sentence-case invitation like a pasted printing block.

**Transfer:** Make the action a short direct phrase and preserve its strong rectangular reversal.

### Closing ticker

**Use:** Signature final invitation above the small footer.

**CSS:** `display: flex; align-items: center; height: 158px; border-top: 1px solid #1d1d1b; border-bottom: 1px solid #1d1d1b; overflow: hidden`

**Text style:** `closing-line` — Editorial New 300 · 86.4px/115.2px · tracking -0.04em

**Observed:** A continuous single-line invitation and Ticker action repeat past both edges of the paper. Below it, identity and legal sit left while uppercase social links sit right, separated by dots.

**Transfer:** Retain the oversized invitation even when the conversion is purchase, subscription or a demonstration rather than email.

### Career card

**Only for:** profile and career pages

**Use:** Availability, role or timeline entries.

**CSS:** `width: 504px; height: 432px; padding: 43.2px; margin-right: 57.6px; background-color: #beb5ab; border: 1px solid #1d1d1b; border-radius: 11.5px; overflow: hidden`

**Text style:** `career-heading` — Editorial New 300 · 60.5px/1.024 · tracking -0.04em

**Observed:** Horizontal rail extends beyond the right viewport edge. A large sentence-case role sits above a small date and either an underlined paragraph or ink-backed skill labels; an inset dashed outline frames the content.

**Transfer:** Use for people and chronology, not as the default feature-card grid.

### Publication entry

**Only for:** editorial archives

**Use:** Resource, press or publication index.

**CSS:** `padding: 28.8px 0px 43.2px; border-bottom: 1px solid rgba(29,29,27,0.3)`

**Text style:** `archive-title` — Editorial New 500 · 43.2px/1 · tracking -0.04em

**Observed:** A large parenthesized number anchors the left, with small publisher and year above a heavier serif title. A tiny media or external-link symbol accompanies the metadata.

**Transfer:** Use a dense three-column index for material worth browsing beyond the main narrative.

## Imagery and graphics

### Paper material

**Use:** Continuous tactile foundation across the page.

**Observed:** Warm aged paper with fine fibers, faint scuffs and cloudy tonal variation; the pattern remains subordinate to the ink.

**Transfer:** Use a seamless neutral paper field, not stains or burnt edges.

**Build:** Generate a seamless grayscale texture with SVG feTurbulence at fine scale, add a second low-frequency cloud layer at much lower contrast, and overlay the result on #cdc6be at opacity 0.3 with mix-blend-mode:multiply. Keep it non-interactive.

### Painterly editorial collage

**Use:** Large capability spreads and typographic murals.

**Observed:** Close-up illustrated face fragments, a profile with gold star glasses, a trophy and a split portrait/object composition occupy large crisp rectangular frames. Soft painted brown grounds, warm flesh and gold contrast with almost-black hair. Type and art alternate in tightly packed rectangles rather than floating freely.

**Transfer:** Commission an illustrated product, founder or object in warm painterly light. Minimum acceptable equivalent: one carefully lit product still life, reused at several close framing scales alongside fitted words.

**Build:** Construct a rectilinear collage grid with a tall narrow detail tile, a larger near-square subject tile and huge condensed word blocks. Use 1px ink outlines and 28.8px internal separations; alternate unbacked ink words with one reversed band. Fill imagery with warm brown studio lighting rather than synthetic interface gradients.

### Project teaser pictures

**Use:** Wide shallow pictures in editorial rails.

**Observed:** Rich color stays inside small landscape frames: a glowing amber object in a dark interior, a cool blue retail room, illustrated portraits and gold-toned objects. No device shell surrounds them.

**Transfer:** Show a memorable product environment or detail rather than an entire page reduced to unreadable scale.

### Postage detail

**Use:** Small physical-print ornament beside an oversized chapter word.

**Observed:** A pale perforated stamp carries a red-orange fan of sun rays, a fine black signature-like squiggle and tiny registry text. It contrasts with the severe rectangular masthead.

**Transfer:** Create a new product-specific miniature seal with the same paper-object logic.

**Build:** Use an SVG rectangle with repeated circular cutouts along all four edges; draw thin radial lines in the vermilion accent across its upper half, a simple ink wave below and two small registration lines. Place it on pale paper at approximately 280×330px and keep it secondary to the adjacent word.

### Torn-paper project cover

**Only for:** case studies

**Use:** Full-screen opening for a single project.

**Observed:** A colored illustrated scene fills the upper portion of a 900px-high cover. A broad, irregular white-fiber tear curves upward at the center into the paper field. A wide black title overlaps the tear region, with a short subtitle on one version and metadata along the bottom rule.

**Transfer:** Use product-specific art above a torn stock edge; replace the scene rather than copying its religious or manuscript subject matter.

**Build:** Layer a full-width image behind a #cdc6be panel. Make the panel's upper boundary an irregular SVG path with a broad central rise, then add fine pale fibers along the edge using a displacement filter. Place the title over the paper below the crest, not inside a rounded card.

### Project gallery plate

**Only for:** case studies

**Use:** Tall framed visual alongside the work story.

**Observed:** One tall image dominates the right half of the spread: either a warmly lit three-dimensional seated figure and books or densely drawn manuscript-style architecture. The base includes a restrained Gallery control on the paper frame.

**Transfer:** Use a full-height demonstrative product image with enough detail to reward scrolling; avoid a stack of generic thumbnail cards.

### Icons

**Observed:** Sparse thin ink arrows, outlined circular down arrows and a small four-tile Gallery sign. Utility arrows measure about 25×14px; circle symbols are about 36×36px. The menu is two short horizontal strokes.

**Transfer:** Choose line-drawn utilitarian symbols, kept near the text and printed in ink; do not introduce a colorful icon library.

## Section recipes

How recurring sections are built.

### First screen: Newspaper front-page opening

**Observed:** The opening is a paper front page rather than a centered headline and button. A 97px masthead bar sits above an editorial rail beginning around 135px down. Two 418×158px framed pictures flank Rail centerpiece, whose 64.8px condensed heading and 37.4px serif deck are separated from the teasers by vertical hairlines. Beneath the roughly 279px rail, 43.2px of separation leads into a nearly full-width Ink band: a single uppercase name in masthead type at 532.8px, with 28.8px outer paper margins. Paper, multiply grain, frames and typography form the layers. The first 900px contains the masthead bar, teaser imagery, browse instruction and nearly all the giant word band; the large illustrated capability spread begins below it. The initial entrance presents this whole paper sheet diagonally against ink before it becomes the straight reading surface. Exploration through the teasers is the first action; no separate bright conversion button competes with the masthead.

**Transfer:** Create two compelling product proof images around a central browse invitation, then typeset a short product name or defining word as the monumental masthead. Use composed still lifes if there is no custom art. Profile pages instead open with a reversed title and a huge serif positioning statement; single-project pages use the Torn-paper project cover.

**Avoid:** Do not turn this into a standard centered SaaS hero with a small logo, paragraph and paired capsule buttons; do not leave the reading surface permanently diagonal.

**Text style:** `masthead` — Canopee 400 · 532.8px/345.6px · tracking -0.05em · uppercase

### Asymmetric capability spread

**Observed:** A narrow left column carries a two-line condensed heading, a framed close-up and a drop-cap paragraph. A vertical half-ink rule and 43.2px gutter separate it from a broad illustration and four tight ruled capability lines using section-heading. The full spread feels typeset edge to edge.

**Transfer:** Let the narrow column explain the product's approach and the broad column dramatize its capabilities. Match the image and the line lengths as a single composition.

### Chapter word and action spread

**Observed:** A huge reversed word in Ink band sits beside a postage-like detail. A subsequent asymmetric spread balances an editorial teaser and large picture on the wide side with a stacked condensed heading, drop-cap copy and Elliptical action on the narrow side.

**Transfer:** Use a short chapter word to reset the scale, then connect it to a concrete demonstration and a short action; the ornament remains a physical printed detail, not a badge cloud.

### Quantified proof and word mural

**Observed:** Proof strip uses four horizontal groups inside strong top and bottom rules. The neighboring mural mixes collage-word typography with small image fragments and one much larger portrait; a final reversed word sits beside a compact credibility paragraph.

**Transfer:** Pair measurable proof with a vivid product-defining phrase. Fit the words to the available rectangles and replace the portraits with product-specific close-ups.

### Overlapping endorsement rail

**Observed:** Endorsement cards form a low horizontal fan with strong outlines, tiny offset shadows and dashed inset frames. The next editorial rail is separated by 57.6px of vertical space.

**Transfer:** Keep the theatrical overlap as the recognizable device while allowing readable inspection or horizontal browsing.

### Editorial return and closing invitation

**Observed:** A three-part Editorial teaser and Rail centerpiece row returns near the bottom, becoming a next-project invitation on case studies. Closing ticker follows inside the paper margins, framed by 1px ink rules. The footer remains small: identity, legal and social links rather than a multi-column sitemap.

**Transfer:** Return the visitor to related work or relevant products, then end with the unmistakable oversized invitation and a restrained link row.

### Work story spread

**Only for:** case studies

**Observed:** A short drop-cap introduction sits beside an expanded Elliptical action. Below, a 605px dashed-outline story panel and a 720px gallery are separated by 57.6px. The story panel stacks case-heading across two lines and case-reverse on ink, followed by 32.4px explanatory prose. A small Gallery utility sits at the bottom of the image frame.

**Transfer:** Explain the challenge and the making of a product beside one strong visual result; preserve the oversized editorial heading rather than replacing it with a conventional case-study sidebar.

### Profile proof and index

**Only for:** profile and editorial pages

**Observed:** A monumental reversed title precedes a 105.1px serif positioning statement. Proof follows in an asymmetric illustration-and-accordion spread, then Career cards, a numbered three-column publication index, a celebratory reversed word and large prose containing inline ink-backed partner names.

**Transfer:** Use this richer biographical vocabulary for origin, expertise and institutional credibility, not ordinary product features.

## Page flow

**Storyline:** Visual selection → monumental identity → capability or project story → tangible proof → related exploration → oversized personal invitation.

### Express a creative product's identity and range through an editorial front page

1. **Visual hook** — Three-part teaser rail followed by a giant reversed identity word.
2. **Capability story** — Asymmetric illustrated spread and large ruled capability lines.
3. **Demonstration** — A chapter word, selected release and process copy balanced against a large picture.
4. **Quantified proof** — Four-group ruled metrics strip and typographic illustration mural.
5. **Social proof** — Overlapping endorsement cards.
6. **Related exploration** — Return of the three-part teaser rail.
7. **Closing call** — Continuous invitation ticker and small legal/social row.

**Transfer:** Use the editorial rhythm and scale changes for a new landing page; choose narrative blocks that suit the offering rather than repeating every section.

### Explain one visually rich project from impression to making

1. **Project promise** — Full-screen illustrated cover, torn-paper title region and bottom metadata.
2. **Context and action** — Drop-cap introduction beside the large Live Site ellipse.
3. **Making and result** — Oversized work-story panel beside a tall framed illustration.
4. **Related exploration** — Next-project teaser pair around a centered invitation.
5. **Closing call** — Ruled contact ticker followed by compact footer links.

**Transfer:** Use for a flagship product story where an immersive image can lead before the detailed explanation.

### Present a concept-heavy project with an explanatory subtitle

1. **Project promise** — Illustrated cover with a torn stock edge, huge title and short serif subtitle.
2. **Context and action** — Concise concept explanation paired with the large Live Site ellipse.
3. **Making and result** — Dashed work-story panel alongside a detailed illustrated gallery image.
4. **Related exploration** — Two related projects flank the next-project invitation.
5. **Closing call** — Same large moving contact invitation and small social row.

**Transfer:** Retain the subtitle when the product name alone does not explain its concept; put technical explanation in the story spread.

### Establish the people, craft and credibility behind an offering

1. **Positioning** — Reversed profile title above an oversized serif introduction.
2. **Proof of expertise** — Illustrated awards spread with ruled accordion categories.
3. **Background** — Horizontal career cards with dates and ink-backed skill labels.
4. **Editorial authority** — Numbered publication index in three columns.
5. **Recognition** — Celebratory word band followed by partner names embedded in large prose.
6. **Visual personality** — Paired large illustrations.
7. **Related exploration** — Return of the editorial teaser rail.
8. **Closing call** — Shared invitation ticker and small legal/social row.

**Transfer:** Use biography, resources and partners as scoped ways to deepen trust; let the type and paper remain continuous with the product-facing design.

## Writing

Confident, personal and craft-obsessed, with the warmth of a maker inviting collaboration. Claims sit next to visible work, named collaborators or quantified recognition rather than abstract corporate promises.

**Do not copy:** Do not reuse the source identity, publication wordmark, portraits, stamp signature, client names, project names, award counts, experience durations or endorsement quotations as new-brand assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** First-person singular for the maker, direct you and your for the reader; use we for a team only when it is true.
- **Rhythm:** Very short uppercase display phrases interrupt longer light-serif paragraphs. Em dashes, ampersands, slash-separated roles and occasional exclamation marks give it the cadence of editorial captions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Identity headline | A short name or emphatic noun made into a masthead. | 1–3 words | “Miranda”<br>“Website” |
| Capability headline | Compact active sequence, with the final word dramatically larger. | 2–4 words | “Think, Create Deliver” |
| Supporting explanation | A specific description of collaboration, craft and outcome. | 1–3 sentences | “A strong project is created by deep collaboration. I design, develop, and deliver websites that drive results and win awards.” |
| Browse invitation | Editorial curation rather than a feature inventory. | 6–12 words | “Handpicked highlights – spanning the last few years.” |
| Primary action | Very short direct destination or contact phrase. | 2 words | “Email Me”<br>“Live Site” |
| Closing invitation | Warm collaborative sentence, suitable for repetition. | 4–7 words | “Let's create something together” |

**Words and phrasing to use:** create; craft; collaboration; selected; handpicked; iconic; raw matter; design & development; together

**Avoid:** enterprise-grade synergy; seamless solutions; 10x everything; frictionless ecosystem; unlock your potential

**Rules:**

- Keep big display copy short enough to form a convincing printed shape.
- Give every teaser an actual subject and a useful descriptive sentence.
- Use first-person language for process, evidence for praise and a warm invitation for conversion.
- Place browsing guidance in a small Tip line rather than lengthy interface instructions.

## Do's and Don'ts

### Do

- Keep the outer paper margins at 28.8px in the 1440px desktop composition.
- Use weight 400 and -0.05em tracking for the principal condensed display words.
- Pair the 32.4px light-serif body with a 1.2 line height and narrow editorial measures.
- Keep picture edges sharp with 1px ink outlines.
- Preserve the large 50%-radius ellipse as an editorial action, not a normal pill.
- Use dashed inset borders and a small offset shadow only for tactile paper-card moments.
- Keep the closing invitation at the same theatrical scale as the rest of the page.
- Let picture color remain rich while the surrounding interface stays paper and ink.

### Don't

- Do not use bright white as the default page background; retain the warm grey stock.
- Do not round all media corners to match the 11.5px paper cards; pictures remain rectangular.
- Do not make the vermilion badge color into a hero fill or a dominant CTA color.
- Do not replace the light editorial body face with a neutral sans-serif UI font.
- Do not add diffuse floating shadows to every panel; the page is printed, not layered glass.
- Do not move proof numerals above their labels as generic dashboard statistics.
- Do not shrink the giant words into ordinary 64px marketing headlines.
- Do not build a large multi-column sitemap under the closing ticker; the footer is deliberately compact.

## Motion and responsive

### Motion

**Observed:**

- The closing invitation repeats horizontally with a declared 4s linear marquee animation.
- The opening paper sheet is shown in a rotated entrance presentation against an ink field; subsequent reading frames use a straight page.
- An opacity transition of 1s ease-out is declared on one surface.

**Transfer:**

- Keep the closing invitation as a continuous print-like ticker with repeated action blocks.
- If using the paper entrance, resolve it into a straight, legible reading plane; keep it separate from the content layout.

**Unknown:**

- Exact entrance duration and transform path, scroll parallax timings and most interaction states are not established.
- Hover and focus-visible styles for primary actions are not established.

### Responsive

**Observed:**

- Desktop composition is 1440×900px.
- Styles declare width boundaries at 479px, 768px, 769px, 991px, 992px and 1440px, with fewer boundaries on the profile layout.
- Main explanatory copy declares viewport-relative size and line height.

**Transfer:**

- On narrower screens, preserve the masthead-as-object by fitting short words to the paper width instead of letting them wrap like prose.
- Recompose asymmetric spreads into a readable vertical sequence while keeping rule lines, reversed words and close-up imagery.
- Keep editorial rails laterally browsable so the centered invitation and neighboring pictures still feel like a newspaper strip.

**Unknown:**

- Exact mobile type values, menu expansion, rail gestures and breakpoint-specific layout changes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
