# Impossible Foods — oversized type, appetite appeal

## Overview

A loud, playful consumer style with poster-sized sans-serif lettering, skinny condensed labels and rich, tactile photography. Deep wine and electric red form the default dark setting, with blush highlights; aqua and leafy green create brighter editorial variants. Airy stages alternate with dense, useful product information, while irregular cutout edges keep the whole experience physical rather than corporate.

### Essentials

- Headlines behave like fitted posters: uppercase 700-weight words occupy a 520px stack, mixing broad and compressed letterforms at 127–230px with line heights of 0.73–0.75.
- The opening is a constellation, not a split hero: a centered 520px word stack sits inside an 840px stage, surrounded by four small shaped photographs, with a tiny foreground product cutout interrupting the lettering.
- Actions are compact, softened rectangles with emphatic skinny capitals: 48px main buttons, 24px/0.9 bold labels and 0.03em tracking; small actions use 36px height and 20px/0.9 labels.
- Color is the canvas, not an occasional accent: wine #4f0423 covers most of the default page, deeper #260212 grounds panels and the ending, red #e10600 carries headlines and actions, and blush #ffc7c6 supplies relief.
- Photography feels ready to touch: vivid close-ups and tabletop scenes fill wavy, scalloped or corner-cut masks, without drop shadows. Include a shaped photographic stage; when lifestyle media is unavailable, use sharply lit product or material still lifes.
- The ending is another billboard: a nearly full-width condensed word sculpture, 1290px wide at desktop, sits behind a large foreground product-in-use cutout. Preserve this oversized text/object overlap even when the equivalent is a hand holding a tool or a simple product silhouette.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Wine canvas | `#4f0423` | `--color-canvas` | background, text | Default long-form marketing canvas; reversed text on blush panels. |
| Deep wine | `#260212` | `--color-panel` | surface, background, text | Inset proof panels, product backings, accordion surfaces and footer. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric red | `#e10600` | `--color-signal` | text, action, background, accent | Default billboard headlines, fixed navigation ribbon, buttons and closing word sculpture. |
| Blush | `#ffc7c6` | `--color-relief` | text, surface, border, accent | Small headings, selected tabs, badges, pagination and the shaped conversion panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | Paragraphs and action labels on dark surfaces; newsletter input. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| purpose-led editorial storytelling | Bright aqua | `#79e5e8` | `--color-aqua` | background, text | Editorial canvas and reversed giant opening type. |
| technical education and ingredient explainers | Leaf green | `#66cb66` | `--color-green` | background | Educational product-detail canvas. |
| purpose-led editorial storytelling | Petrol ink | `#002426` | `--color-aqua-ink` | text, background | Editorial text and dark opening background. |
| technical education and ingredient explainers | Botanical ink | `#002416` | `--color-green-ink` | text, background, border | Educational headings, diagram labels and dark media backing. |
| purpose-led editorial storytelling | Deep teal | `#005f66` | `--color-teal` | text, action, link | Supporting editorial headings and action fills. |
| technical education and ingredient explainers | Forest action | `#005232` | `--color-forest` | action, link, surface | Educational buttons and interactive affordances. |
| technical education and ingredient explainers | Light leaf | `#a3eea3` | `--color-green-relief` | surface, background, text | Educational cards, explanatory bands and footer. |
| purpose-led editorial storytelling | Pale aqua | `#bcf8f9` | `--color-aqua-relief` | surface, background | Shaped editorial proof panels and footer. |

## Typography

- **sans-meat** — All display, body, navigation and labels; a single family changes dramatically in width between roles. Heavy broad poster capitals coexist with extremely condensed upright headings and labels; paragraphs have ordinary readable sans-serif proportions. If unavailable, use **Barlow Condensed**. Use 400–700 for condensed roles; horizontally expand the short broad display words to fill their stage, keeping paragraph widths readable. Font stack: "sans-meat", "Barlow Condensed", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| section-poster | sans-meat | 700 | 230px | 0.73 | normal, uppercase | fixed | Single-word chapter statement in a centered 520px stage. |
| display | sans-meat | 700 | 162px | 0.75 | normal, uppercase | fixed | Broad first word of the default opening; fitted to the central word stack. |
| display-compressed | sans-meat | 700 | 127px | 0.73 | normal, uppercase | fixed | Compressed qualifier under the broad opening word; fit the same width rather than keeping every word the same size. |
| card-title | sans-meat | 400 | 40px | 0.9 | normal, uppercase | fixed | Narrow titles for product cards, accordions and newsletter invitation. |
| lead | sans-meat | 400 | 32px | 1.4 | normal | fixed | Readable multi-line proof-panel statement and educational card titles. |
| small-heading | sans-meat | 400 | 28px | 1.1 | normal | fixed | Quiet introduction above an enormous word stack; metadata below imagery. |
| action | sans-meat | 700 | 24px | 0.9 | 0.03em, uppercase | fixed | Primary action labels and prominent footer links. |
| tab | sans-meat | 400 | 24px | 0.9 | 0.03em, uppercase | fixed | Narrow category selectors and vertical tab labels. |
| body | sans-meat | 400 | 22px | 1.4 | normal | fixed | Section support and short editorial paragraphs. |
| ribbon | sans-meat | 700 | 20px | 1.7 | normal, uppercase | fixed | Tiny broad all-caps connector, centered between decorative marks above or within a headline. |
| action-small | sans-meat | 700 | 20px | 0.9 | 0.02em, uppercase | fixed | Navigation and smaller card actions. |
| body-small | sans-meat | 400 | 18px | 1.4 | normal | fixed | Detailed explanations and accordion content. |
| badge | sans-meat | 700 | 12px | 0.9 | 0.06em, uppercase | fixed | Compact outlined classification stamp on a photographic card. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| purpose-led manifesto openings | monumental-display | sans-meat | 700 | 511px | 0.77 | normal, uppercase | fixed | An enormous broad word that enters from below the first screen and continues into a multi-screen statement. |
| company-history storytelling | timeline-year | sans-meat | 700 | 300px | 0.74 | normal, uppercase | fixed | Monumental year paired with small explanatory copy and miniature imagery. |
| quantified impact storytelling | impact-word | sans-meat | 700 | 120px | 0.8 | normal, uppercase | fixed | Oversized repeated comparison word next to a bold pictogram, with a tiny category underneath. |
| editorial text-and-media sections | editorial-heading | sans-meat | 700 | 80px | 0.88 | normal, uppercase | fixed | Condensed multi-line heading beside a large photograph. |
| technical education and ingredient explainers | education-heading | sans-meat | 700 | 80px | 1 | normal, uppercase | size max(40px, 26.7px + 3.7037vw) | Heading of an explanatory text-and-media band. |
| editorial proof and educational sections | education-subheading | sans-meat | 400 | 56px | 1 | normal | fixed | Lighter condensed section title above diagrams or card collections. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep broad headline words and tall condensed words in deliberate contrast. The centered poster stack is width-led, not a conventional uniform-size h1.
- Display lines are unusually tight, usually 0.73–0.77, while explanatory text breathes at 1.4. Do not apply display leading to paragraphs.
- Use normal tracking on display type. Tracking belongs primarily to action labels and small classification stamps.
- For a substitute font, use separate width treatments for broad words and compressed qualifiers rather than using one condensed cut everywhere.

## Layout

**Density:** Airy at the section scale, compact within controls; enormous headings and close photographs interrupt generous stretches of saturated color.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Explains the dominant vertical rhythm; inline spacing also uses smaller independent values.

| Value | Use |
| --- | --- |
| 8px | Stacked tab gap and decorative ribbon spacing. |
| 16px | Footer link rhythm and compact content stacks. |
| 24px | Outer navigation inset, card content padding and newsletter inset. |
| 32px | Proof content stack and headline-to-paragraph separation. |
| 40px | Routine section padding and educational grid gutters. |
| 56px | Media-to-text separation within proof panels and carousel spacing. |
| 64px | Grid lead-in and inner shaped-panel vertical padding. |
| 80px | Major section padding and wide photographic pair gap. |
| 120px | Footer top padding. |
| 160px | Impact-section vertical padding. |

### Containers and grids

- **main-stage**: max width 1440px · side padding 100px. Wide centered composition with 1240px of content at desktop; full-bleed color continues beyond it.
- **poster-stack**: max width 520px. Width-led centered display sculpture; support may extend to a separate 728px measure.
- **support-copy**: max width 728px. Centered support below poster headings.
- **accordion-column**: max width 616px. Narrow centered FAQ stack.
- **footer-links**: 3 columns · gap 40px. Three compact link groups on the right beside social, locale and ownership information.
- **educational-grid** (only for technical education and ingredient explainers): max width 920px · 3 columns · gap 40px. Three 280px cards, centered wrapping rows; the last incomplete row stays centered.

## Corner radius

| Element | Radius |
| --- | --- |
| input and educational cards | 38px |
| classification badge | 5px |
| newsletter submit | 16px |
| pagination | 50% |

## Surfaces and depth

### Surfaces

#### Wine canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #4f0423; color: #ffffff`

**Observed:** The same saturated field runs behind multiple sections; it is not a series of white cards.

**Transfer:** Keep the background continuous across several narrative beats.

#### Shaped proof panel · level 1

**Use:** Inset interactive explanations and deeper tonal relief.

**CSS:** `background: #260212; box-shadow: none`

**Observed:** A wide panel has softened corners and shallow peaked upper and lower edges rather than a plain rectangular silhouette.

**Transfer:** Use an SVG mask with symmetric shallow curves and a central rise, retaining a solid flat fill.

#### Blush conversion placard · level 1

**Use:** A contrasting utility or conversion call.

**CSS:** `background: #ffc7c6; color: #4f0423; box-shadow: none`

**Observed:** A centered 832px-wide placard with a gently peaked top carries one giant utility word and short support.

**Transfer:** Give one useful next step a physical sign-like shape.

#### Editorial aqua canvas · level 0

**Only for:** purpose-led editorial storytelling

**Use:** Bright long-form narrative alternative.

**CSS:** `background: #79e5e8; color: #002426`

**Observed:** Dark petrol reverses the opening, while pale aqua panels and footer soften the main field.

**Transfer:** Keep all surfaces inside one related hue family.

#### Educational green canvas · level 0

**Only for:** technical education and ingredient explainers

**Use:** Long-form educational alternative.

**CSS:** `background: #66cb66; color: #002416`

**Observed:** Light leaf cards and bands distinguish interactive information from the main green field.

**Transfer:** Use tonal contrast, not neutral white dashboard panels.

#### Educational card · level 1

**Only for:** technical education and ingredient explainers

**Use:** Photo-led and text-only explainer tiles.

**CSS:** `background: #a3eea3; border-radius: 38px; box-shadow: none`

**Observed:** Cards sit flat without outlines; images fill their upper square, and text-only variants retain the same rounded silhouette.

**Transfer:** Use these for a genuine information taxonomy, not every marketing claim.

## Components

### Floating navigation

**Use:** Persistent orientation and quick conversion.

**CSS:** `position: fixed; top: 24px; left: 24px; right: 24px; height: 48px; background: #e10600; color: #ffffff; z-index: 7`

**Text style:** `action-small` — sans-meat 700 · 20px/0.9 · tracking 0.02em · uppercase

**Observed:** A narrow, softened ribbon holds a small left wordmark, centered topic links with tiny downward chevrons, and two darker utility controls at right. Its corner shape is assembled graphically. Editorial variants switch the ribbon to their light theme color and use dark labels.

**Transfer:** Retain the unusually slim bar and leave most of the screen to the poster.

### Primary button

**Use:** Main conversion beneath a poster or proof statement.

**CSS:** `display: grid; align-items: center; justify-content: center; height: 48px; padding: 0px 26px; background: #e10600; color: #ffffff`

**Text style:** `action` — sans-meat 700 · 24px/0.9 · tracking 0.03em · uppercase

**Observed:** A custom softened-rectangle silhouette backs a narrow label. Hero actions have small decorative seed-like marks at both ends and sit side by side; simpler content buttons omit the ornaments. Teal and forest fills belong to the bright editorial themes.

**States:** Declared: hover treatment is not established for this variant; focus-visible outline 2px solid #c2abb5, outline-offset 2px, border-radius 5px and box-shadow 0 0 0 2px #000; active color #fff.

**Transfer:** Approximate the graphic silhouette with a 16px rounded rectangle if no SVG construction is available.

### Vertical topic tab

**Use:** Switch between proof chapters without stacking every explanation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; height: 48px; padding: 1px 46px 1px 20px; color: #ffc7c6; background: #260212`

**Text style:** `tab` — sans-meat 400 · 24px/0.9 · tracking 0.03em · uppercase

**Observed:** A right chevron is held clear of the label. Tabs stack at 8px gaps; the selected tab reverses to blush with wine lettering. Horizontal category tabs use the same compact softened shape.

**States:** Declared: hover is unspecified for this variant; focus-visible outline 2px solid #c2abb5, outline-offset 2px and border-radius 5px; active color #4f0423.

### Photographic story card

**Use:** Practical inspiration and use-case browsing.

**CSS:** `display: flex; flex-direction: column; align-items: center; color: #ffffff`

**Text style:** `card-title` — sans-meat 400 · 40px/0.9 · uppercase

**Observed:** A large irregularly masked photograph precedes an outlined badge, a centered condensed title, three short metadata fragments, a hairline and a small action. Adjacent cards differ in image size, creating an editorial rather than rigidly uniform pair.

**Transfer:** Adapt the metadata to time, difficulty, compatibility or usage context.

### Classification badge

**Use:** A small editorial stamp on a story card.

**CSS:** `display: flex; align-items: center; border: 1px solid #ffc7c6; border-radius: 5px; padding: 1px 7px 0px 7px; color: #ffc7c6`

**Text style:** `badge` — sans-meat 700 · 12px/0.9 · tracking 0.06em · uppercase

**Observed:** A very small outlined label sits between the image and title; a light photographic placard can reverse its colors.

### FAQ accordion

**Use:** Objection handling in a narrow centered column.

**CSS:** `max-width: 616px; padding: 30px 32px; background: #260212; color: #ffffff; display: flex; justify-content: space-between; align-items: center`

**Text style:** `card-title` — sans-meat 400 · 40px/0.9 · uppercase

**Observed:** Soft graphic corners enclose the uppercase question with a strong downward arrow on the right. Expanded content uses body-small text with 32px side insets. The educational theme reverses the text and surface colors.

**Transfer:** Keep the question visibly larger than the answer; do not compress it into a standard small FAQ row.

### Newsletter field

**Use:** Email signup near the end of the narrative.

**CSS:** `display: flex; position: relative; align-items: center; height: 88px; max-width: 520px; padding: 0px 24px; background: #ffffff; border-radius: 38px`

**Observed:** A small label and entry line occupy the left, with a compact colored Submit control embedded at the right. Consent and linked terms sit below the white field, not inside it.

**Transfer:** Preserve the single long rounded field beside a multi-line condensed invitation.

### Footer link group

**Use:** Dense secondary navigation above the closing artwork.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 16px; color: #ffffff`

**Text style:** `action` — sans-meat 700 · 24px/0.9 · tracking 0.03em · uppercase

**Observed:** Three groups occupy the right side; each link uses a small right chevron. Social icons, locale and ownership information sit separately at left. Smaller legal links form an additional tier before the oversized word sculpture.

**States:** Declared: hover color #ffc7c6; focus-visible outline 2px solid #c2abb5, outline-offset 2px and border-radius 12px; active color #ffc7c6.

### Explainer tile

**Only for:** technical education and ingredient explainers

**Use:** Open a focused information detail.

**CSS:** `position: relative; width: 280px; background: #a3eea3; border-radius: 38px; color: #002416`

**Text style:** `lead` — sans-meat 400 · 32px/1.4

**Observed:** The content area has 24px padding; a round forest plus control is pinned toward its lower right. Photo-led tiles add a square image above the text. Text-only tiles begin at 185px height and grow for wrapped titles.

**Transfer:** Use a small number of meaningful categories, with centered incomplete rows.

## Imagery and graphics

### Appetite close-ups

**Use:** Opening satellites and practical-inspiration cards.

**Observed:** Warm, saturated food close-ups show browned surfaces, glossy sauces, vegetables, hands, dishes and colorful tablecloths. Some scenes are overhead; others crop tightly into a sandwich or bowl. Small hero satellites occupy the corners while large paired photographs dominate later sections.

**Transfer:** Use close tactile evidence of the product in real use, with hard-to-ignore texture and colorful surroundings rather than sterile stock imagery.

### Flexible cutout masks

**Use:** Signature framing for photographs, placards and panels.

**Observed:** Edges bend gently inward and outward, corners can be clipped diagonally, and some small photos have scalloped silhouettes. The photography stays natural inside these graphic boundaries.

**Transfer:** Keep at least one large shaped image and use the same family of shapes on supporting scenes.

**Build:** Create SVG clipPaths in a 100×100 viewBox. For a wavy rectangle, use four cubic sides with control points displaced 3–5 units inward and outward; round the joins. For a corner-cut sticker use an octagon with 8–12-unit clipped corners. For a scallop use 8 broad alternating convex lobes, not a fine serrated seal. Use object-fit: cover inside; add no shadow or outline.

### Foreground product cutout

**Use:** A small interruption in the opening and a monumental closing overlap.

**Observed:** A small isolated plate crosses the opening headline. At the end, two hands holding a burger rise in front of giant condensed lettering, filling the lower center and extending beyond the page edge.

**Transfer:** Use a transparent product-in-use photograph with believable light; a clean product silhouette is the minimum fallback.

**Build:** Layer an oversized text or SVG word sculpture behind a centered transparent PNG. At desktop, the text stage is 1290px wide and 415px tall; the foreground image is 980px wide and extends past the bottom boundary. Keep the object in front of the lower portion of the letters and preserve readable upper letterforms.

### Material still lifes

**Only for:** technical education and ingredient explainers

**Use:** Educational opening and photo-led taxonomy tiles.

**Observed:** Grains, beans, plant leaves, glassware, oils and seeds are tightly arranged on bright white photographic backings. Strong natural greens and yellows contrast with the green page; the white is part of the photo, not a separate UI panel.

**Transfer:** Photograph the new product's ingredients, parts or materials as crisp arrangements, with consistent light and square framing.

### Pictogram stickers

**Only for:** impact and purpose storytelling

**Use:** Comparison facts and participation calls.

**Observed:** Bold filled droplets, trees and emissions symbols sit on pale irregular stickers, paired with oversized repeated words. Participation calls use small playful black drawings on pale stickers.

**Transfer:** Replace these with immediately recognizable symbols tied to the new proof, maintaining simple solid forms.

**Build:** Place one dark filled SVG pictogram on a pale themed tile. Use a 100×100 octagonal or softly scalloped path as backing, no border or shadow, and reserve roughly two thirds of the tile for the symbol.

### Icons

**Observed:** Tiny filled chevrons and location pins accompany links; plus controls use round colored backings, and FAQ arrows are bold downward marks. Typical inline symbols are 10–24px, modal triggers 36px and carousel arrows 56px.

**Transfer:** Use compact high-contrast filled shapes with the label color. Treat decorative seed marks as ornaments, not functional arrows.

## Section recipes

How recurring sections are built.

### First screen: Constellation product opening

**Observed:** A 900px-tall stage sits within a 1300px opening scroll region. Back to front: Wine canvas, four shaped lifestyle photos around the outer quarters, a centered 840px content stage with a 520px word stack, then a tiny isolated product cutout over the seam between its two giant lines. Floating navigation sits above everything. A small-heading introduction leads into a ribbon label, a broad 162px word and a compressed 127px qualifier in red. Two 48px Primary buttons sit beneath with an 18px gap. Within the first 900px the complete statement, small product, four satellites and both actions are visible; the product collection begins below this opening region.

**Transfer:** Use a short product promise that can be split into broad and condensed lines. Without lifestyle imagery, stage four materially distinct product details around one isolated central object. Educational openings retain centered fitted words but use larger edge-clipped material images; manifesto openings instead let one monumental word rise from the lower edge before the rest unfolds.

**Avoid:** Do not turn this into a left-aligned headline next to one rectangular image, enlarge the tiny foreground object into the entire hero, or place a paragraph-heavy sales pitch above the fold.

**Text style:** `display` — sans-meat 700 · 162px/0.75 · uppercase

### Product collection carousel

**Observed:** A small centered introduction precedes large narrow category names with small count stamps. Three full product cards and a clipped next item run across the page; packages sit against dark irregular square backings. Titles use card-title, with a compact action and a location link below. Edge arrows and 12px dot pagination frame the collection.

**Transfer:** Use a browsable family of offerings with consistent isolated packaging or product silhouettes; preserve lateral overflow rather than squeezing four complete cards into equal columns.

### Poster chapter heading

**Observed:** A centered 520px fitted uppercase stack pairs a ribbon connector with one or two giant words. Supporting body copy sits on a separate measure up to 728px wide, typically 40px below.

**Transfer:** Make a short assertion or question into a typographic object; use differing word widths to hold a strong rectangular silhouette.

**Text style:** `section-poster` — sans-meat 700 · 230px/0.73 · uppercase

### Unequal photographic pair

**Observed:** Photographic story cards sit as a staggered pair: one image is about 460px square and its companion about 620px square, separated by 80px. A poster heading and compact category tabs introduce the pair.

**Transfer:** Pair two real use cases with different visual emphasis, keeping the image larger than the supporting text.

### Tabbed proof placard

**Observed:** Shaped proof panel spans 1240px, with 64px inner vertical padding. A 245px vertical topic rail leads to a roughly 365px copy column and a narrow shaped image. Lead text uses 32px/1.4, details 18px/1.4 and a Primary button follows. Pale aqua is the purpose-led variant.

**Transfer:** Put related claims behind a concise topic rail, illustrating one claim at a time rather than turning the panel into many competing cards.

### Support and utility close

**Observed:** A giant question-style Poster chapter heading leads into the FAQ accordion column. A second oversized contact statement provides a small help action; a Blush conversion placard gives a separate useful next step.

**Transfer:** Use the close to resolve doubt and offer help, then foreground a relevant tool, trial or location action.

### Newsletter and monumental ending

**Observed:** An 80px-padded two-column signup pairs a 40px condensed invitation with the Newsletter field. The footer changes tonal surface, uses a shallow shaped boundary, and has 120px top padding and 76px bottom padding. Social and locale tools sit left of three Footer link groups. A huge 1290px word sculpture follows the utility tiers, with a 980px foreground product-in-use cutout rising over it. The dark variant uses red lettering; bright variants use dark themed lettering on a pale canvas.

**Transfer:** Close with functional navigation and then an unmistakable physical brand statement. Use the new identity or a short closing word behind an appropriate product object, not an ordinary text-only footer.

### Editorial image and statement

**Only for:** editorial and educational storytelling

**Observed:** A large square photograph sits beside an 80px condensed heading and body copy, aligned through a broad 1240px stage. Routine bands have 40px vertical padding. Educational versions may use the lighter tonal band and a photo about 600px square.

**Transfer:** Alternate the image side to sustain a long story without repeating identical centered headers.

**Text style:** `editorial-heading` — sans-meat 700 · 80px/0.88 · uppercase

### Horizontal milestone story

**Only for:** company-history storytelling

**Observed:** A viewport-height horizontal story holds an 80px introduction at left while giant 300px years, compact supporting text, arrows and small photographs unfold to the right. The sequence has a visible baseline and deliberately clips forthcoming content.

**Transfer:** Use only for genuinely chronological progress; keep each milestone a compact typographic scene.

**Text style:** `timeline-year` — sans-meat 700 · 300px/0.74 · uppercase

### Impact comparison row

**Only for:** quantified impact storytelling

**Observed:** A 56px introductory heading leads to three horizontally arranged pictogram/word pairs with 32px gaps. Each pair is about 279px wide, joining an irregular pale icon tile to a 120px comparison word and a 20px uppercase category. A small qualification and centered action follow.

**Transfer:** Use a repeated directional word or substantiated number for each comparable metric; keep qualifications close to the claim.

**Text style:** `impact-word` — sans-meat 700 · 120px/0.8 · uppercase

### Technical comparison chapter

**Only for:** technical education and ingredient explainers

**Observed:** Two large ring diagrams compare composition with a compact legend above. A later table places category tabs on the left and a dense comparison panel on the right. Shaped upper and lower section edges separate this detailed chapter from the surrounding canvas.

**Transfer:** Use diagrams only when the data truly compares like with like. Preserve a strong heading and a small set of categories; keep the technical table secondary to the main product story.

### Photographic feature placard

**Only for:** featured use cases and editorial demonstrations

**Observed:** A wide photograph fills a shallow-peaked frame about 1240px wide. A contrasting sign-like inset sits over the left portion with a classification badge, condensed title, three metadata fragments and a button. Arrows flank the frame and pagination runs below.

**Transfer:** Feature one especially compelling application with a tactile image and concise practical details.

## Page flow

**Storyline:** Product promise → browsable offerings or explanatory context → vivid applications → deeper proof → questions and assistance → useful conversion → subscription and monumental sign-off.

### Consumer product discovery and conversion

1. **Promise** — Constellation product opening with fitted words and two actions.
2. **Product exploration** — Category-led product carousel.
3. **Applications** — Unequal photographic pair and practical metadata.
4. **Proof** — Poster heading and tabbed proof placard.
5. **Objection handling** — Large FAQ statement, accordion column and contact action.
6. **Conversion** — Shaped utility placard and email signup.
7. **Sign-off** — Deep tonal footer, grouped links and giant word/object overlap.

**Transfer:** Use this as the default landing-page mode, balancing immediate desirability with a later useful explanation.

### Purpose-led editorial narrative

1. **Manifesto** — Multi-screen monumental typography on a dark opening.
2. **Context** — Image-and-statement bands.
3. **Progress** — Horizontal milestone timeline.
4. **Proof** — Tabbed claims followed by qualifications and an impact row.
5. **Participation** — Giant typographic invitation with three illustrated action paths.
6. **Sign-off** — Newsletter and pale themed footer with the same giant foreground overlap.

**Transfer:** Use the aqua theme for a deep story about a problem and progress, not as the default product pitch.

### Technical product education and reassurance

1. **Promise** — Centered broad words framed by edge-clipped material photographs.
2. **Context** — Large regular-weight introduction and an image-led explanatory band.
3. **Education** — Photo-led taxonomy cards, fitted chapter headline and ring diagrams.
4. **Comparison** — Text-only explainer tiles and category-led data table.
5. **Applications** — Featured photographic demonstration with inset sign.
6. **Objection handling** — Related-resource tiles, FAQ and contact action.
7. **Sign-off** — Newsletter and pale green monumental footer.

**Transfer:** Use the green theme when readers need ingredients, materials, methods or safety information; keep the educational details separated into legible chapters.

## Writing

Confident, appetite-led and conversational, with knowingly exaggerated short headlines and grounded explanatory paragraphs. The humor is friendly and occasionally self-aware, while substantive claims carry qualifications.

**Do not copy:** Do not reuse the brand name, wordmark artwork, trademarks, product names, founder quotes, nutritional or environmental claims, certifications, statistics or proprietary imagery. Source examples illustrate tone only; replace them with truthful content for the new product.

- **Addressing the reader:** Use we for the maker and you for the reader. Speak directly in invitations and questions; use plain factual prose when explaining technical matters.
- **Rhythm:** Poster headlines are often one to four emphatic words, with small connectors and parenthetical qualifiers. Support uses one or two conversational sentences; technical answers may be longer and more careful.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A blunt product noun followed by an unexpected clarifying parenthesis. | 1–4 words plus qualifier | “Steak (From Plants)” |
| Section invitation | Ask an informal question and immediately answer with reassurance. | 6–9 words | “Want Recipe Inspo? We Got You.” |
| Supporting line | State the useful promise in ordinary language with a conversational tag. | One sentence | “We've got answers to the most common questions about our products, preparation methods, nutrition – you name it.” |
| Primary action | A direct verb and clear next step. | 2–4 words | “Learn More”<br>“Measure your impact” |
| Technical chapter | Plain curiosity-led explanation rather than academic terminology. | 3–6 words | “What We're Made Of” |
| Editorial aside | A quick joke followed by a concrete navigation cue. | One short sentence pair | “The rest is history. Kidding, check out our timeline.” |

**Words and phrasing to use:** we got you; let's; made of; better; curious; find; learn; real; short sensory adjectives

**Avoid:** enterprise-grade; synergistic; revolutionary platform; unlock potential; unqualified health promises; stiff institutional phrasing

**Rules:**

- Make the short headline feel like a sign someone would read across a room.
- Use colloquial connectors sparingly, so the supporting explanation remains useful.
- Lead with sensory or practical benefit; place substantiation and necessary qualifications nearby.
- Keep action labels literal even when the surrounding heading is playful.
- Use questions to invite learning, not to manufacture anxiety.

## Do's and Don'ts

### Do

- Keep the default canvas wine with deeper wine proof surfaces; let red typography and blush relief carry the contrast.
- Fit major words into a 520px stage and preserve the 0.73–0.75 display line-height relationship.
- Use 22px/1.4 support copy and 18px/1.4 detailed answers, clearly separated from condensed headings.
- Keep the fixed navigation 24px from the viewport edges and 48px tall.
- Use shallow peaks and soft irregular edges on at least one photographic stage and one large panel.
- Leave 40–80px section padding around most narrative modules rather than packing them together.
- Pair slim 24px bold action labels with 48px controls.
- End with oversized condensed text behind a physical foreground object.

### Don't

- Do not replace the wine default with a mostly white layout and red accent links.
- Do not add gradient glows, glass panels or floating card shadows to these flat saturated surfaces.
- Do not use a single ordinary-width grotesk for both the broad poster words and the skinny labels.
- Do not spread normal display tracking into widely letterspaced luxury typography.
- Do not give every control a full pill silhouette; reserve strong 38px rounding for inputs and educational cards, and keep button shapes softly rectangular.
- Do not shrink FAQ questions into 18px body-size rows; their 40px condensed labels are part of the hierarchy.
- Do not turn every section into equal boxed cards; the main rhythm is open canvas, large imagery and occasional shaped panels.
- Do not place an entire page of technical information in the default opening; the first screen is a short typographic product stage.

## Motion and responsive

### Motion

**Observed:**

- Color and background-color transitions commonly use 300ms cubic-bezier(0.445,0.05,0.55,0.95).
- Opacity transitions include 600ms linear and 300ms cubic-bezier(0.445,0.05,0.55,0.95).
- Left and right appearance animations are declared at 600ms cubic-bezier(0.39,0.575,0.565,1).
- The opening uses a sticky content stage; the timeline is a horizontal story within a longer scroll region.

**Transfer:**

- Let the opening's words and peripheral media form distinct depth layers, while keeping the conversion controls legible.
- Use the declared color transition for themed controls and tab selections; retain the graphic shapes through state changes.

**Unknown:**

- Exact parallax distances, scroll choreography and reduced-motion behavior are not established.

### Responsive

**Observed:**

- CSS includes width breakpoints at 480px, 768px, 834px, 1024px, 1200px, 1280px and 1440px, among others.
- The education-heading size follows max(40px, 26.7px + 3.7037vw).

**Transfer:**

- On narrow screens, prioritize the fitted word stack and actions; keep supporting cutouts peripheral and partly clipped rather than stacking four photos before the promise.
- Allow the educational tiles to wrap while keeping their incomplete final row centered.
- Retain the closing foreground overlap even when its text and object must shrink.

**Unknown:**

- Exact mobile navigation, stacking order and mobile headline-size formulas are not established; these narrow-screen adaptations are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
