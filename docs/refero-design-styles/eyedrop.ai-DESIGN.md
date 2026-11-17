# EyeDrop — violet lenses, literary charm

## Overview

A light, gently tactile style that pairs literary serif headings with humanist sans-serif copy and jewel-like violet product art. White and pale lavender dominate, while deep navy lettering and small saturated purple accents keep the page legible and playful. It suits focused software and personal productivity products, with sparse centered compositions, large demonstrations and a personable maker-led ending.

### Essentials

- The opening is an object reveal, not a text billboard: a 562px sculptural object rises behind a white elliptical edge within a 400px stage, followed by a wide split-color wordmark and a 25px supporting promise.
- Literary headings hinge on one italic word: meno-display at 56px, weight 300, line height 1.15 and normal tracking, with matching italic emphasis rather than a second color.
- Conversion comes in a matched pair: 220px × 64px rounded download actions, navy beside violet, with a 12px preface over a 20px main label and a 25px gap.
- Color behaves like perfume rather than paint: most of the page stays white or a 5% violet wash; saturated violet belongs to the main object, partial wordmark, actions, 24px icons and selected feature chips.
- Soft containers are unusually round: 80px card corners, 60px circular icon wells and borderless white surfaces; shadows belong mainly to floating pills and the circular demonstration.
- Product explanation becomes an orbit: a 350px circular demonstration with a 4px violet edge sits in an 896px × 600px stage, connected by delicate curves to floating feature pills. A simple working UI illustration is the fallback when video is unavailable.
- A second wordmark is the closing monument: repeat the broad two-tone identity above a short 25px invitation and paired actions, with 250px of breathing room above and a small single-line maker footer below.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Midnight navy | `#181d4a` | `--color-ink` | text, action | Default lettering and trial-action fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#8c34ea` | `--color-violet` | action, accent, link | Secondary download action, outline icons, link hover and brand artwork accents. |
| Orbit purple | `#8b5cf6` | `--color-orbit` | action, border, accent | Selected orbit label, circular demonstration outline and purple glow. |
| Orchid hover | `#da82eb` | `--color-hover` | action | Hover fill for download actions and inactive feature pills. |
| Lilac well | `#f4ebfd` | `--color-icon-wash` | surface | Visible 10% violet over white in circular icon wells; source hue #8c34ea at 0.1 alpha. |
| Lavender air | `#f9f5fe` | `--color-band-wash` | background | Visible 5% violet over white in broad fading bands; source hue #8c34ea at 0.05 alpha. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Slate | `#374151` | `--color-secondary` | text | Inactive orbit labels. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Page ground, cards and inverse button lettering. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| circular product demonstrations | Media black | `#000000` | `--color-media-matte` | background | Backing behind the clipped circular video, not a page theme. |

## Typography

- **optima-lt-pro** — Supporting promises, body copy, controls and footer. Humanist flared sans-serif with a soft calligraphic feel; more organic than a geometric UI face. If unavailable, use **Belleza**. Use regular for body and light-looking headings; check line wraps carefully. Font stack: "optima-lt-pro", "Belleza", sans-serif.
- **meno-display** — Section leads, feature titles and questions. Fine, high-contrast literary display serif with an expressive flowing italic. If unavailable, use **Cormorant Garamond**. Use 300 roman and italic; preserve the generous line height. Font stack: "meno-display", "Cormorant Garamond", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | meno-display | 300 | 56px | 1.15 | normal | Centered section leads. |
| heading-emphasis | meno-display | 300 italic | 56px | 1.15 | normal | One meaningful word within a section lead. |
| opening-promise | optima-lt-pro | 300 | 25px | 1.15 | normal | Single-line promise under the opening identity and invitation under the closing identity. |
| card-title | meno-display | 300 | 25px | 1.5 | normal | Feature titles and accordion questions. |
| support | optima-lt-pro | 400 | 20px | 1.5 | normal | One-line section explanations. |
| action-label | optima-lt-pro | 700 | 20px | 1.5 | normal | Main line of the trial action. |
| feature-pill | optima-lt-pro | 500 | 16px | 1.5 | normal | Orbit control labels. |
| footer | optima-lt-pro | 400 | 16px | 1.5 | normal | Small maker attribution and text links. |
| body | optima-lt-pro | 400 | 15px | 1.6 | normal | Compact feature descriptions and demonstration captions. |
| requirements | optima-lt-pro | 400 | 15px | 1.5 | normal | Compatibility notes and short secondary reassurance. |
| action-preface | optima-lt-pro | 400 | 12px | 1.5 | normal | Small introductory line inside a download action. |

**Notes:**

- Keep section headings light and navy; italic emphasis changes the voice without changing size, weight or color.
- Normal tracking is the default for all live text. The widely spaced uppercase identity is artwork, not a body-heading treatment.
- Section leads are considerably larger than the opening promise: the sculptural object and identity carry the opening scale.

## Layout

**Density:** Airy: centered text groups are compact internally, with long pauses before demonstrations, actions and the final invitation.

### Spacing

**Spacing system:**

- **vertical rhythm** 10px, vertical — Underlying rhythm of section padding and major vertical separations; half steps appear within text groups.

| Value | Use |
| --- | --- |
| 5px | Tight heading-to-support separation and download-action padding. |
| 15px | Feature title to body copy. |
| 20px | Accordion row gaps and icon-to-title spacing. |
| 25px | Gap between paired download actions and horizontal orbit-pill padding. |
| 30px | Feature-grid gap, accordion header padding and identity-to-promise spacing. |
| 40px | Desktop container side padding and feature-card vertical padding. |
| 50px | Action group to compatibility note. |
| 60px | Feature introduction to card grid. |
| 70px | Promise to actions and section support to orbit stage. |
| 80px | Standard section top padding. |
| 100px | Demonstration section opening and closing lower padding. |
| 120px | Benefit-band lower padding. |
| 250px | Exceptional breathing room above the closing identity. |

### Containers and grids

- **container**: max width 1200px · side padding 40px. Centered desktop wrapper; leaves a 1120px inner content span at a 1440px viewport.
- **benefit grid**: max width 1000px · 3 columns · gap 30px. Three equal centered cards; desktop cards are about 313px wide.
- **accordion**: max width 800px · 1 column · gap 20px. Narrow centered stack of question rows.
- **orbit stage**: max width 896px. Centered 600px-tall illustration field with a circular demonstration and radial labels.
- **footer container**: max width 900px · side padding 40px. Centered attribution line, visually narrower than the principal content.
- **identity**: max width 540px. Broad centered split-color wordmark, visually overflowing its art bounds slightly.

## Corner radius

| Element | Radius |
| --- | --- |
| cards and download actions | 80px |
| feature pills | 9999px (pill) |
| icon wells and circular media | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating pill | `0px 4px 6px -1px rgba(0, 0, 0, 0.1), 0px 2px 4px -2px rgba(0, 0, 0, 0.1)` | Inactive orbit labels. |
| selected pill | `0px 10px 15px -3px rgba(139, 92, 246, 0.3), 0px 4px 6px -4px rgba(139, 92, 246, 0.3)` | Selected orbit label. |
| circular demo glow | `0px 25px 50px -12px rgba(139, 92, 246, 0.3)` | Purple light beneath the circular product view. |

### Surfaces

#### Paper canvas · level 0

**Use:** Light ground throughout the page.

**CSS:** `background: #ffffff`

**Observed:** A very fine animated grain softens the white areas.

**Transfer:** Keep the grain faint enough that text and product art remain clean.

#### Lavender atmosphere · level 0

**Use:** Soft benefit, question and opening-information bands.

**CSS:** `background-image: linear-gradient(rgba(140, 52, 234, 0), rgba(140, 52, 234, 0.05) 200px, rgba(140, 52, 234, 0.05) calc(100% - 200px), rgba(140, 52, 234, 0))`

**Observed:** The pale tint dissolves into the canvas rather than producing hard section boundaries.

**Transfer:** Use broad low-opacity color behind grouped content, never saturated full-width panels.

#### White cushion · level 1

**Use:** Benefit cards and accordion items.

**CSS:** `background: #ffffff; border-radius: 80px; border: 0px; box-shadow: none`

**Observed:** White-on-lavender separation replaces outlines and heavy elevation.

**Transfer:** Use the same soft contour for short proof blocks and objection handling.

#### Elliptical reveal · level 1

**Use:** Opening object stage.

**CSS:** `background: #ffffff; height: 400px; clip-path: ellipse(60% 400px at 50% 0%); overflow: hidden`

**Observed:** A broad concave-looking lower edge cuts across the large object, revealing only its upper portion.

**Transfer:** Mask the lower part of a product sculpture or symbolic object with the same shallow curved horizon.

## Components

### Trial button

**Use:** Primary conversion action.

**CSS:** `display: flex; flex-direction: column; justify-content: center; align-items: center; width: 220px; height: 64px; padding: 5px; background: #181d4a; color: #ffffff; border-radius: 80px; overflow: hidden`

**Text style:** `action-label` — optima-lt-pro 700 · 20px/1.5

**Observed:** A tiny action-preface sits above the main label; the pair reads like a compact store badge. It sits beside a violet destination badge.

**States:** Declared: hover background-color #da82eb; focus-visible and active are unspecified.

**Transfer:** Keep the two-line construction even when the destination changes.

### Destination badge

**Use:** Companion conversion route.

**CSS:** `display: block; width: 220px; height: 64px; padding: 5px; background: #8c34ea; border-radius: 80px; overflow: hidden`

**Observed:** A white platform mark and two-line store graphic occupy the interior. It shares the trial button's footprint.

**States:** Declared: hover background-color #da82eb; focus-visible and active are unspecified.

**Transfer:** Use an appropriate destination mark or simple white icon with a two-line label.

### Benefit card

**Use:** Short reassurance or product advantage.

**CSS:** `background: #ffffff; border-radius: 80px; padding: 40px 20px; text-align: center; overflow: hidden`

**Text style:** `card-title` — meno-display 300 · 25px/1.5

**Observed:** Icon well first, then serif title and a short centered body paragraph. Three cards form an equal desktop row.

**Transfer:** Give each card one concrete benefit and no more than a few short lines of support.

### Icon well

**Use:** Shared icon backing in benefit cards and question controls.

**CSS:** `display: flex; justify-content: center; align-items: center; width: 60px; height: 60px; border-radius: 50%; background: rgba(140, 52, 234, 0.1); color: #8c34ea`

**Observed:** Benefit wells contain simple outline symbols; question wells contain a downward chevron.

### Orbit pill

**Use:** Feature selector surrounding a central product view.

**CSS:** `background: #ffffff; color: #374151; border-radius: 9999px; padding: 17.5px 25px; box-shadow: 0px 4px 6px -1px rgba(0, 0, 0, 0.1), 0px 2px 4px -2px rgba(0, 0, 0, 0.1)`

**Text style:** `feature-pill` — optima-lt-pro 500 · 16px/1.5

**Observed:** Short labels float around the central circle and connect to it with fine curves. The selected variant is purple with white text and a purple shadow; one longer label wraps to two lines.

**States:** Declared: hover background-color #da82eb and color #ffffff; transform translate(0,0) rotate(0) skew(0) skewY(0) scaleX(1) scaleY(1); focus-visible and active are unspecified.

**Transfer:** Use four or five succinct capability names rather than surrounding the object with paragraphs.

### Circular demo

**Use:** Focal product demonstration within the feature orbit.

**CSS:** `width: 350px; height: 350px; border-radius: 9999px; overflow: hidden; background: #000000; border: 4px solid #8b5cf6; box-shadow: 0px 25px 50px -12px rgba(139, 92, 246, 0.3)`

**Observed:** A square product video fills the circle within the border. Light UI dominates the visible interior; the black backing is only a media matte.

**Transfer:** Choose a close product interaction readable inside a circle, with no tiny explanatory text required.

### Question row

**Use:** Objection-handling accordion.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 20px; padding: 30px; min-height: 120px; background: #ffffff; border-radius: 80px; overflow: hidden`

**Text style:** `card-title` — meno-display 300 · 25px/1.5

**Observed:** Left-aligned serif question and right-hand icon well sit in a centered single-column stack. Questions remain concise enough to fit beside the chevron.

**Transfer:** Use real adoption questions; retain the generous end padding.

### Maker link

**Use:** Understated personal attribution in the footer.

**CSS:** `color: #181d4a; text-decoration: underline; transition: 0.3s ease-in-out`

**Text style:** `footer` — optima-lt-pro 400 · 16px/1.5

**Observed:** An inline link is embedded among maker credit, a playful location note and copyright, separated by middle dots.

**States:** Declared: hover color #8c34ea; focus-visible and active are unspecified.

## Imagery and graphics

### Jewel object reveal

**Use:** Main opening visual and smaller identity motif within demonstrations.

**Observed:** A glossy dark lens is nested inside thick concentric purple discs, with grain, directional shading and a small white highlight. The 562px square object is centered near the top and its lower half disappears behind the curved white horizon. Its saturated color is far stronger than the surrounding page.

**Transfer:** Create a dimensional symbol for the new product: nested discs, a layered token or a simplified physical tool. The minimum version is a layered SVG with convincing shadows and one hard specular highlight, not a flat stock icon.

**Build:** Use three or four concentric circles in an approximately 562px square SVG. Shade the outer circles from deep violet toward #8c34ea with translucent black inner shading; put a dark navy center inside, add an off-center white highlight and a subtle reflected crescent. Overlay fine monochrome noise at low opacity. Place the lower half behind the Elliptical reveal surface.

### Split-color identity

**Use:** Opening identity and repeated closing monument.

**Observed:** A wide, heavy uppercase wordmark has exceptionally spaced letters; the first part is navy and the second part violet with subtle tonal variation. Its nominal art container is 540px wide and 59px tall, while the visible shapes spread wider.

**Transfer:** Set the new product's name as custom outlined geometric capitals or a bold wordmark; divide it at a meaningful syllable or word. Preserve the broad tracking and two-tone split rather than treating it as a conventional text headline.

**Build:** Construct an SVG with outlined uppercase lettering in a wide horizontal viewBox. Leave roughly a letter-stem's width or more between letters, fill the first segment #181d4a and the second #8c34ea with soft tonal shading. Center it as an identity object, not as body typography.

### Desktop demonstration theater

**Use:** Large product proof after the opening promise.

**Observed:** A light desktop application window with rounded corners and deep soft shadow sits centrally against a pale textured ground. Small image-file thumbnails float to either side, showing inputs moving toward a larger working product window. The demonstration occupies substantially more area than its short heading and support line.

**Transfer:** Show one recognizable input-to-result workflow inside a clean native-looking window; use a still sequence or illustrated UI if motion is unavailable. Keep peripheral objects small and purposeful.

### Feature orbit

**Use:** Signature capability illustration.

**Observed:** Five feature labels surround a circular product view, joined by slender lavender curved connectors. The selected upper label and circle edge are strongly purple; the other labels are white with gentle shadows.

**Transfer:** Connect a central working artifact to four or five useful capabilities. If no video exists, draw a static working state or output card within the circle.

**Build:** Use an 896px × 600px relative stage with a centered 350px circle. Draw SVG quadratic paths from the circle edge toward labels above, upper left, upper right, lower left and lower right; stroke #8b5cf6 at low opacity and roughly 1px–2px with no fill. Place Orbit pills above the connectors and use the selected variant on the top label.

### Fine paper grain

**Use:** Atmospheric unifier over pale backgrounds.

**Observed:** Very low-contrast monochrome texture adds tactile depth without looking like coarse paper or grunge.

**Transfer:** Keep this device on new pages even if all product imagery is vector-based.

**Build:** Generate a small seamless monochrome noise texture with SVG feTurbulence and repeat it in a pointer-events:none overlay at opacity 0.047. Keep text on a clean upper layer and avoid visible seams.

### Icons

**Observed:** Small violet outline SVGs are 24px square, with round caps and 2px strokes in benefit cards; chevrons use a 2.5px stroke. They sit centrally in 60px pale-lilac wells.

**Transfer:** Choose simple single-object outline symbols and retain the shared well rather than adding colorful illustrative icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Sculptural identity opening

**Observed:** The first 900px form one complete centered composition without a navigation bar: white ground, a 562px layered jewel object beginning after 80px of top space, a 400px curved reveal stage, then Lavender atmosphere behind the identity and copy. The object dominates the upper portion while the wide Split-color identity anchors the lower half. The opening-promise is a single 25px navy line beneath the identity; paired Trial button and Destination badge follow after 70px, with a compatibility note another 50px below. All of this is visible above the first fold; the large workflow demonstration starts below it.

**Transfer:** Open a new marketing page with a dimensional product symbol, wide two-tone identity and one useful sentence rather than a giant conventional slogan. Use layered SVG art when no rendered object exists. A narrower feature-focused page can open with the same object-and-promise relationship at reduced scale while preserving the curved reveal.

**Avoid:** Do not replace the composition with a left-copy/right-dashboard template, a navigation-heavy header or a full-bleed purple rectangle.

**Text style:** `opening-promise` — optima-lt-pro 300 · 25px/1.15

### Literary heading pair

**Observed:** Centered 56px light serif lead with one italic word, followed closely by a 20px humanist support line. Heading blocks sit within the main container and have no eyebrow or rule.

**Transfer:** Choose one useful idea for italic emphasis, including a verb or negation rather than always the last word.

**Text style:** `heading` — meno-display 300 · 56px/1.15

### Workflow proof stage

**Observed:** A Literary heading pair opens after 100px of section-top space. A large Desktop demonstration theater follows on white, occupying nearly the rest of a 959px section.

**Transfer:** Prove the core promise with one legible workflow, not a collage of unrelated screens.

### Benefit cushion row

**Observed:** Lavender atmosphere contains a Literary heading pair, optional short reassurance and three Benefit cards in the 1000px grid. The band uses 80px top and 120px bottom padding; the card grid follows its introduction after 60px.

**Transfer:** Use three distinct reasons to trust or value the product; let the title and supporting sentence do most of the work.

### Orbit chapter

**Observed:** A Literary heading pair precedes the Feature orbit by 70px. The 896px stage contains the Circular demo and floating Orbit pills; a centered card-title and body caption below explain the selected capability. Section padding is 80px above and below.

**Transfer:** Make this a capability explorer rather than another row of cards; keep the central artifact and connected labels as the organizing device.

### Questions on lavender

**Observed:** A Literary heading pair sits above a centered 800px accordion. White Question rows are 120px tall when closed and separated by 20px against Lavender atmosphere. Each row ends in an Icon well with a violet chevron.

**Transfer:** Scale the number of questions to actual objections; retain the broad rounded rows and narrow reading width.

### Identity reprise and maker ending

**Observed:** After the question stack, 250px of upper space introduces the Split-color identity again. A 25px invitation follows after 30px, then the paired conversion actions after 70px. The closing block has 100px lower padding. Below it a separate 88px footer, with 32px vertical padding and 40px horizontal padding, carries a centered single attribution line with middle-dot separators, an underlined Maker link, a lighthearted location note and copyright.

**Transfer:** End with identity, an uncomplicated invitation and the same conversion options used earlier. Let a brief human sign-off replace a corporate sitemap.

## Page flow

**Storyline:** Identity-led promise → working proof → reassurance → capability exploration → objections → identity reprise and conversion → human sign-off.

### A focused product landing page that moves from recognition to confidence and download

1. **Promise** — A dimensional object and wide two-tone identity frame one short benefit sentence, paired conversion routes and practical requirements.
2. **Product demonstration** — A large application workflow shows input becoming useful output beneath a three-part action headline.
3. **Reassurance** — A pale lavender band holds a centered claim and three soft white benefit cards.
4. **Capability exploration** — A circular demonstration connects to floating feature selectors and a concise selected-state caption.
5. **Objection handling** — A narrow column of broad rounded question controls answers adoption concerns.
6. **Closing call** — The identity returns with substantial breathing room, a short invitation and the original action pair.
7. **Human sign-off** — One small line credits the maker with a playful location aside.

**Transfer:** Adapt the sequence to the product's decision process; preserve the sculptural identity, literary emphasis, orbit device and personal ending without requiring an identical section count.

## Writing

Clear, friendly and practical, with gentle confidence rather than enterprise grandeur. Benefits are stated plainly and the occasional playful aside keeps the product personable.

**Do not copy:** Do not reuse the EyeDrop name, logo, lens artwork, maker identity, product claims, compatibility requirements or platform promises. Source examples demonstrate voice only; replace them with substantiated facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader using you and your; refer to the product by name when explaining how it works. Avoid an institutional we-led narrative.
- **Rhythm:** Short action phrases alternate with single explanatory sentences. Headings usually carry one idea; supporting copy is one or two sentences. An exclamation mark belongs to a warm invitation or playful aside, not every benefit.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the job, then add a compact list of practical differentiators after an em dash. | About 8–12 words | “Automatic image captions — private, instant, on your Mac.” |
| Section headline | Use a memorable sequence of verbs or a direct reassurance with one emphasized word. | About 3–8 words | “Drag. Drop. Describe.”<br>“Your images never leave your Mac” |
| Supporting line | Explain a concrete mechanism or purpose without hype. | One short sentence | “Powered entirely by Apple Silicon, [Brand] processes everything locally.”<br>“Small details that make [Brand] even better.” |
| Primary action | A small imperative preface above a named destination or offer. | About 4–6 words total | “Download the Trial Version” |
| Reassurance | Use parallel short negatives or a compact benefit label when facts support it. | About 2–6 words | “No cloud, no tracking, no limits.” |
| Human sign-off | Credit a person and allow a tiny local joke. | One brief inline aside | “Made in Canada, brrrr! 🥶” |

**Words and phrasing to use:** your; instant; small details; automatically; private; locally; trial; simple action verbs

**Avoid:** revolutionary; enterprise-grade synergy; unlock limitless potential; disrupt; best-in-class; vague AI superlatives

**Rules:**

- Lead with the useful outcome, then explain its mechanism.
- Keep requirements explicit and subordinate to the main invitation.
- Write questions in the reader's own language.
- Use warmth in small doses, especially at the ending; keep functional explanations literal.

## Do's and Don'ts

### Do

- Keep section leads at 56px/1.15 and weight 300, with same-size italic emphasis.
- Use 25px/1.15 humanist copy beneath the broad opening identity.
- Preserve the 220px × 64px action pair and 25px gap.
- Use 80px corners for white benefit cards and accordion shells.
- Stage the capability illustration around a 350px circle within an 896px-wide field.
- Keep the palette mostly white and 5% lavender, with violet concentrated in focal details.
- Repeat the identity at the ending and keep the personal footer to one centered line.
- Retain faint grain at opacity 0.047 rather than making pale surfaces perfectly sterile.

### Don't

- Do not turn the 56px literary headings into bold geometric sans-serif headlines.
- Do not apply the wordmark's wide uppercase spacing to paragraphs or controls.
- Do not replace white cushion cards with outlined rectangles or heavy drop-shadow tiles.
- Do not spread the selected orbit purple to every feature pill; contrast selected and inactive states.
- Do not use the media matte as a dark page-section background.
- Do not enlarge the 24px outline symbols into multicolor illustration tiles.
- Do not add a dense multi-column corporate sitemap to the small maker ending.
- Do not hide practical notes inside the main button label; give them a separate 15px line.

## Motion and responsive

### Motion

**Observed:**

- Download actions declare background-color transitions of 1s.
- Orbit controls declare all 0.5s cubic-bezier(0, 0, 0.2, 1).
- Question rows declare box-shadow 0.3s, their headers padding-bottom 0.3s, and chevron wells background-color 1s.
- Fine grain declares a repeating 0.2s steps(3, jump-none) random-static animation.
- Opening information groups declare 1s fadeInSlideUpSmooth with cubic-bezier(0.25, 0.46, 0.45, 0.94), staggered by 0.2s, 0.4s and 0.6s.

**Transfer:**

- Keep the opening reveal's motion subordinate to the object and promise; maintain the light stagger between identity, actions and practical note.
- Use soft color transitions on the rounded controls rather than sharp flashes.

**Unknown:**

- Exact runtime path of object interaction and orbit float motion is not established.
- Focus-visible and active treatments are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 767px, 768px, 1024px, 1200px, 1280px and 1536px.
- The download-action group declares flex-wrap.

**Transfer:**

- On narrow screens, keep the object, identity and promise centered; scale the reveal and wordmark together rather than preserving desktop-sized overflow.
- Stack the benefit cards and let the action pair wrap. Recompose orbit labels into a readable compact arrangement around or below the central artifact while retaining visible connectors.
- Let question labels wrap beside the icon well without shrinking the serif question text into microcopy.

**Unknown:**

- Actual narrow-screen typography, layout and visibility changes are not established; these adaptation rules are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
