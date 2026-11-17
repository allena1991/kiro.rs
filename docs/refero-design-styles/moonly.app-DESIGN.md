# Moonly — cinematic soft enchantment

## Overview

A dark, emotionally warm style that pairs cinematic human scenes with playful, tactile product worlds. Cream geometric grotesk lettering floats over charcoal, while violet, pink, gold and sky blue live mostly inside imagery. Spacious chapters, glossy illustrations and oversized device scenes make it suited to consumer apps, personal services and experience-led products rather than dense technical catalogs.

### Essentials

- Human cinema comes before interface: a 1420×810px rounded opening scene sits inside a 10px outer gutter, with a centered two-line 52px/54px promise over the lower half.
- The lettering is friendly, not monumental: Roobert SemiBold at 52px/54px for the opening and 40px/40px with -0.02em tracking for chapter leads; short gold labels use 12px/1.4 capitals with 0.05em tracking.
- Darkness frames the color rather than becoming a neon theme: #16181d canvas and #222428 media beds dominate structural surfaces; cream #f3ece3 text and #f7b64d labels surround saturated artwork confined to rounded stages.
- Actions are soft white capsules, not glowing rectangles: 50px high, 60px radius, dark text at 18px/22px; the fixed navigation is a separate 1000×70px dark glass capsule with 27px backdrop blur.
- Product proof has a magical physical presence: upright black phones, projecting rounded objects and luminous violet or golden accents occupy 610–1240px-wide stages. Include a tactile object scene and a layered content constellation; when no device exists, use a genuine product artifact surrounded by simple modeled shapes.
- The closing identity becomes architecture: a low-contrast outlined wordmark spans 1200×320px beneath useful footer columns. Pair this signature with an immersive human conversion band using a 490×78px frosted action rail; these devices belong in the design even when their placement changes.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#8437f1` | `--color-violet` | text, accent | Small labels on white editorial and demo surfaces; larger purple fields belong to artwork. |
| Warm gold | `#f7b64d` | `--color-gold` | text, accent | Small uppercase feature labels and warm inset illumination; not the primary action fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Clear white | `#ffffff` | `--color-white` | text, surface, action | Opening headlines, action capsules and bright editorial cards. |
| Smoked glass | `#0f1014` | `--color-glass-dark` | surface | Visible dark navigation glass over the canvas, made with rgba(13,14,18,0.8); its appearance changes over imagery. |
| Charcoal canvas | `#16181d` | `--color-canvas` | background, text | Default page ground and dark lettering on white actions. |
| Blue charcoal | `#181c27` | `--color-article-ink` | text | Titles on white editorial cards and floating demo controls. |
| Raised charcoal | `#222428` | `--color-panel` | surface | Media beds and contributor cards, subtly separated from the ground. |
| Gradient shoulder | `#303238` | `--color-panel-highlight` | surface | Lighter start of the compact intent tile's diagonal charcoal gradient. |
| Frosted gray | `#5c5d61` | `--color-glass-light` | surface | Visible white 30% glass over the canvas; conversion rails use the same alpha over colorful media. |
| Stone gray | `#828282` | `--color-muted` | text | Default explanatory copy, locations and footer labels. |
| Half-white copy | `#8b8c8e` | `--color-secondary-light` | text | Visible rgba(255,255,255,0.5) over the canvas, used for inset feature explanations. |
| Warm cream | `#f3ece3` | `--color-text` | text | Chapter headings, quotations, support over imagery and footer navigation. |
| Blush porcelain | `#f9f4f2` | `--color-badge` | surface | Pale announcement lozenges on white editorial cards. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| focused feature pages | Feature charcoal | `#232427` | `--color-feature-panel` | surface | Slightly different media bed for focused feature grids. |
| founder stories | Silver byline | `#d9d9d9` | `--color-byline` | text | Author attributions in editorial storytelling. |
| founder stories and contributor profiles | Soft white | `#e8e8e8` | `--color-essay-text` | text | Visible white at 90% over charcoal for long reading. |

## Typography

- **Roobert** — All marketing headings, labels, body text and controls; Regular, SemiBold and Bold cuts share one family. Rounded geometric grotesk with open counters and a warm, direct character; the semibold cut gives even small copy a substantial presence. If unavailable, use **DM Sans**. Use 400 for editorial prose, 600 for the semibold cut and 700 for profile names; tune wrapping before changing sizes. Font stack: "Roobert", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Roobert | 600 | 52px | 54px | normal | Centered opening promise, usually two lines in about 670px. |
| heading | Roobert | 600 | 40px | 1 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Centered chapter leads, conversion headings and short editorial statements. |
| feature-heading | Roobert | 600 | 32px | 36px | normal | Inset title on a large feature stage, left aligned. |
| card-heading | Roobert | 600 | 24px | 1 | normal | Titles beneath media, on bright cards and inside compact feature scenes. |
| lead | Roobert | 600 | 20px | 1.2 | normal | Hero support, chapter introductions, testimonials, footer links and FAQ questions. |
| body | Roobert | 600 | 18px | 22px | normal | Short explanatory paragraphs and default action labels. |
| caption | Roobert | 600 | 16px | 1.25 | normal | Intent tiles, customer names and compact supporting text. |
| eyebrow | Roobert | 600 | 12px | 1.4 | 0.05em, uppercase, features "blwf", "cv03", "cv04", "cv09", "cv11" | Feature categories, navigation labels, media endorsement captions and footer group names. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| founder stories | editorial-quote | Roobert | 600 | 40px | 1.1 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Centered personal statement interrupting long prose. |
| founder stories | editorial-body | Roobert | 400 | 18px | 1.45 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Sustained left-aligned personal storytelling. |
| founder stories | byline | Roobert | 600 | 14px | 20px | normal | Centered uppercase name and role below a personal statement. |

**Notes:**

- The semibold face is the default even where a text style uses a nominal regular CSS weight. Preserve its visual substance rather than making all body copy thin.
- Only the 40px heading tier tightens to -0.02em; the 52px hero and 32px feature title retain normal tracking.
- Do not scale the outlined identity as a normal text headline: it is vector artwork fitted to its own wide, shallow area.
- Marketing copy is compact at 18px/22px; sustained prose switches to the Regular cut at 18px/1.45 within a narrow column.

## Layout

**Density:** Airy between chapters and tightly grouped inside each chapter; media occupies much more area than prose.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card title to explanation and tightly grouped label stacks. |
| 10px | Outer opening gutter, compact tile gaps and carousel item gaps. |
| 16px | Testimonial padding, compact control padding and portrait-to-metadata spacing. |
| 20px | Paired media gutter, media-to-caption spacing and action separation. |
| 24px | Hero text-stack gaps and heading-to-support spacing. |
| 40px | Heading-to-stage gap and editorial paragraph/media separation. |
| 60px | Default distance between major sections. |
| 80px | Side padding inside a 1400px desktop chapter wrapper and deep feature section insets. |

### Containers and grids

- **chapter-wrapper**: max width 1400px · side padding 80px. Centered desktop wrapper leaving a 1240px working width at 1440px; full-bleed bands are wider than this content.
- **cinema-band**: max width 1400px · side padding 0px. Immersive conversion scene with about 20px outside space per side.
- **navigation**: max width 1000px. Fixed centered capsule, visually independent of the wider content grid.
- **feature-pair**: 2 columns · gap 20px. Equal 610px columns or an asymmetric 407px/823px split; a small phone card contrasts with a larger cinematic panel.
- **three-up**: 3 columns · gap 10px. Three 407px media-led cards under one centered heading.
- **four-up**: 4 columns · gap 10px. 303px illustration cards or roughly 292px testimonial columns, with consistent top alignment.
- **reading-column** (only for founder stories): max width 600px. Centered long-form prose, media and two founder profiles.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media-cards | 20px |
|  | intent-tiles | 30px |
|  | primary-actions | 60px |
|  | glass-capsules | 100px |
|  | conversion-band | 40px |
| craft and contributor pages | contributor-cards | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| warm-inset | `inset -11.2px -11.2px 11.2px -15px rgba(211,119,77,1), inset -6px -6px 2.2px -7.5px rgba(247,182,77,1)` | Compact intent tiles catch gold along an inner corner rather than casting a conventional drop shadow. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark ground.

**CSS:** `background: #16181d; color: #f3ece3`

**Observed:** Darkness continues through most sections and the footer rather than alternating light bands.

**Transfer:** Let imagery supply the major changes in color.

#### Media bed · level 1

**Use:** Rounded backing for a phone or illustration.

**CSS:** `background: #222428; border-radius: 20px; overflow: hidden`

**Observed:** Near-black gray subtly separates the object stage from the page; large scenes can replace this fill with photographic or violet artwork.

**Transfer:** Keep a real focal object present rather than treating the backing as the content.

#### Smoked navigation · level 2

**Use:** Floating navigation material.

**CSS:** `background: rgba(13,14,18,0.8); border-radius: 100px; backdrop-filter: blur(27px)`

**Observed:** The pill remains dark over both photographs and the page ground.

**Transfer:** Keep translucency localized to this small navigational layer.

#### Frosted action rail · level 2

**Use:** Conversion action over moving imagery.

**CSS:** `background: rgba(255,255,255,0.3); border-radius: 100px; backdrop-filter: blur(24px)`

**Observed:** A pale translucent rail holds an invitation on the left and white circular platform icons on the right.

**Transfer:** Use the background scene's color through the glass instead of an opaque gray fill.

#### Intent tile · level 1

**Use:** Small outcome-led navigation tiles.

**CSS:** `background: linear-gradient(135deg, #303238 0%, #16181d 100%); border-radius: 30px; box-shadow: inset -11.2px -11.2px 11.2px -15px rgba(211,119,77,1), inset -6px -6px 2.2px -7.5px rgba(247,182,77,1)`

**Observed:** The warm edge is concentrated, not a glow halo around the entire tile.

**Transfer:** Carry the same dark-to-darker gradient beneath a small tactile object.

#### Porcelain editorial card · level 1

**Use:** A small contrasting resource carousel.

**CSS:** `background: #ffffff; color: #181c27; border-radius: 20px; padding: 32px 16px`

**Observed:** White is confined to compact cards, each with colorful illustration, title and short gray explanation.

**Transfer:** Use bright cards as local editorial accents, not as a new page theme.

## Components

### Floating navigation

**Use:** Persistent top-level wayfinding and acquisition.

**CSS:** `width: 1000px; height: 70px; padding: 10px 11px 10px 20px; display: flex; align-items: center; justify-content: space-between; background: rgba(13,14,18,0.8); border-radius: 100px; backdrop-filter: blur(27px)`

**Text style:** `eyebrow` — Roobert 600 · 12px/1.4 · tracking 0.05em · uppercase

**Observed:** Fixed centered 20px from the top. Identity at left, compact category links in the middle, then a divider and two circular white platform actions. The capsule floats above every scene.

**Transfer:** Use a compact identity, three short destinations and one acquisition group rather than a full-width header.

### Primary button

**Use:** Opening conversion and next-step actions.

**CSS:** `height: 50px; padding: 20px; display: flex; align-items: center; justify-content: center; background: #ffffff; color: #16181d; border-radius: 60px`

**Text style:** `body` — Roobert 600 · 18px/22px

**Observed:** Label-sized capsule with a 161px opening example; longer feature-page actions extend to 279px. Repeated Learn more variants use 16px padding and the same height.

**Transfer:** Let label width vary without enlarging the button vertically.

### Intent tile

**Use:** Choose an outcome before exploring feature chapters.

**CSS:** `width: 198px; height: 170px; padding: 8px; border-radius: 30px; background: linear-gradient(135deg, #303238 0%, #16181d 100%); display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `caption` — Roobert 600 · 16px/1.25

**Observed:** Short first-person desire at the top, small glossy symbolic illustration toward the bottom and a small directional cue; uses the Intent tile surface's warm inset edge.

**Transfer:** Write each choice as a desired change, not an internal module name.

### Media feature card

**Use:** Repeatable capability demonstration.

**CSS:** `background: #222428; border-radius: 20px; overflow: hidden; display: flex; justify-content: center; align-items: flex-start`

**Text style:** `card-heading` — Roobert 600 · 24px/1

**Observed:** The rounded media bed holds an upright phone cut off at its bottom. Caption stack sits outside below: gold eyebrow, cream title, gray support and optional Primary button. A large variant puts copy inside the cinematic image instead.

**Transfer:** Use real interface content, then give it a separate, legible marketing caption.

### Testimonial

**Use:** Personal evidence in a dense but calm wall.

**CSS:** `width: 292px; padding: 16px 16px 24px; border-radius: 20px; display: flex; flex-direction: column; gap: 16px; color: #f3ece3`

**Text style:** `lead` — Roobert 600 · 20px/1.2

**Observed:** Almost merges into the canvas. Small rounded avatar and a name/location stack precede a substantial left-aligned quote. Two unequal-height testimonials stack per column; locations use the Eyebrow recipe in gray.

**Transfer:** Retain the uneven quote lengths and restrained framing rather than forcing every item into equal-height panels.

### Journal card

**Use:** Horizontal resource browsing.

**CSS:** `width: 272px; height: 351px; padding: 32px 16px; background: #ffffff; color: #181c27; border-radius: 20px; display: flex; flex-direction: column; align-items: center; gap: 10px`

**Text style:** `card-heading` — Roobert 600 · 24px/1

**Observed:** Illustration first, then a pale New badge in violet, centered title and gray summary. Cards are separated by 10px, with the final card fading into the edge and a small next control.

**Transfer:** Keep resources short and visually lighter than the product chapters.

### FAQ row

**Use:** Objection handling after visual proof.

**CSS:** `height: 60px; background: #16181d; display: flex; align-items: center; color: #f3ece3`

**Text style:** `lead` — Roobert 600 · 20px/1.2

**Observed:** Full working-width question with a muted plus at the left, a faint horizontal divider and no enclosing card. Rows sit 20px apart.

**Transfer:** Use concise questions and preserve the low-contrast structure; expanded content can follow the Body recipe.

### Conversion rail

**Use:** Final invitation within a cinematic band.

**CSS:** `width: 490px; height: 78px; padding: 16px 16px 16px 24px; background: rgba(255,255,255,0.3); border-radius: 100px; backdrop-filter: blur(24px); display: flex; align-items: center; gap: 20px`

**Text style:** `lead` — Roobert 600 · 20px/1.2

**Observed:** Invitation at left and two white circular platform actions at right. A small outlined user-count pill sits above the heading; a star-rating lockup sits below the rail.

**Transfer:** For a non-app product replace platform glyphs with an appropriate acquisition action, preserving the rail's split composition.

### Footer navigation

**Use:** Useful directory before the monumental identity.

**CSS:** `display: flex; flex-direction: column; gap: 24px; color: #f3ece3`

**Text style:** `lead` — Roobert 600 · 20px/1.2

**Observed:** Uppercase gray group label above links; several columns cover product, learning and company, while store badges and social glyphs occupy the right. Legal links sit beneath the outlined identity.

**Transfer:** Keep actual destinations useful and leave the identity enough uninterrupted width.

### Floating demo plaque

**Use:** Make a product scene feel interactive without overwhelming the artwork.

**CSS:** `width: 362px; height: 123px; padding: 16px 24px 0px 16px; background: #ffffff; border-radius: 30px; transform: rotate(-2deg); color: #181c27`

**Text style:** `card-heading` — Roobert 600 · 24px/1

**Observed:** Overlaps the lower center of an upright phone in a content constellation. A violet uppercase label, dark title and compact audio controls occupy a slightly tilted white plaque.

**Transfer:** For another product use a compact real interaction or result preview with the same hierarchy, not a decorative empty sticker.

## Imagery and graphics

### Human cinema

**Use:** Opening and immersive conversion bands.

**Observed:** Full-width people in an environment, not isolated cutouts: sunset meditation, sun-filled collaborative rooms, twilight fields and joyous low-angle outdoor action. Soft focus, shallow depth, warm skin, cream clothing, teal sky, lens bloom and foreground flowers make the image sensorial. The subject is larger than the central text and fills almost the whole first screen.

**Transfer:** Commission or select people genuinely using or benefiting from the product. Minimum acceptable version is a strong full-bleed still with warm side light, atmospheric foreground and a calm text-safe lower-center area.

**Build:** Layer a cover image inside a 20px-radius opening container; add a transparent-to-rgba(22,24,29,0.45) vertical scrim only where type crosses busy detail. Keep the foreground sharpness softer than the product scenes; warm light and teal shadows should come mainly from the image.

### Tactile product theater

**Use:** Signature feature demonstrations between centered chapter headings.

**Observed:** Black upright phones rise from the bottom edge of rounded stages; objects float in front of and beyond their screens. Violet cards, pink sculptural symbols, cream stars, planets and gold highlights have inflated bevels and satin-plastic shading. Some scenes sit in an indigo-to-pink illustrated horizon; others use a flat violet theater or charcoal bed. Images occupy about two thirds or more of a feature panel.

**Transfer:** Model objects relevant to the new product with the same soft bevels and luminous pastel shading. Minimum version: one convincing device or physical artifact, three softly shaded SVG objects and a deeply colored stage; do not substitute a flat icon grid.

**Build:** Use a bottom-aligned upright device occupying roughly 35% of a wide stage, with layered SVG ellipses or rounded extruded silhouettes at three scales crossing its edge. Shade violet objects with a pale upper-left highlight and dark purple lower-right rim. Put a soft pink horizon glow behind them using blurred radial gradients; keep all artwork clipped by the 20px stage radius.

### Content constellation

**Use:** Signature breadth-of-product demonstration.

**Observed:** Three horizontal rows of small colorful portrait-format content tiles extend behind a larger central phone or hero card. A dark edge fade hides both ends. The central object overlaps all rows, with a bright floating demo plaque in one variation. Saturated peach, aqua, violet and soft green tile art stays inside this bounded scene.

**Transfer:** Use the product's actual content, outputs or templates; when there is no library, create a set of representative outcomes and enlarge one. Preserve the three-depth arrangement instead of displaying a conventional gallery.

**Build:** Within a 1250×540px scene, make three rows of rounded portrait cards with 20px gutters, offset each row horizontally, and apply a left/right transparent mask over the outer edges. Center a tall foreground artifact across the rows and overlap its lower half with the Floating demo plaque. Use the Canvas color as a soft vignette at all edges.

### Warm light bloom

**Use:** Emotional bridge between photography and product objects.

**Observed:** Sun rays and prismatic flare pass through human scenes; a large white-gold bloom sits behind glossy conversation bubbles in a feature panel. Warm inset glints also appear on small dark navigation tiles.

**Transfer:** Keep light attached to a believable source or focal object; it should suggest warmth and support rather than a science-fiction laser.

**Build:** Place a small rgba(255,255,255,0.9) core behind the focal object, a broader rgba(247,182,77,0.35) radial gradient and a still wider translucent peach halo; blur the outer layers by 40px. For photographic rays, use a very low-opacity conic fan masked to a localized oval. Match the soft glow; exact stops are not essential.

### Outlined identity

**Use:** Signature footer artwork.

**Observed:** The brand name becomes a near-full-width unfilled vector outline, about 1200×320px, with a barely visible gray stroke against the canvas. It sits after the directory, followed by small legal text, rather than serving as a loud headline.

**Transfer:** Create an equally wide outline treatment of the new brand's own identity; preserve low contrast and large empty counters.

**Build:** Convert the identity lettering to SVG paths, set fill to none and stroke to rgba(255,255,255,0.16) at about 1px, and fit it into a 1200×320px viewBox with preserved aspect ratio. Leave a broad dark interval around the lettering.

### Craft documentary

**Only for:** craft and contributor pages

**Use:** Explain how the product is made and who makes it.

**Observed:** Warm candid photographs of recording, collaboration and instruments alternate with polished product images. Three landscape images sit above centered captions; a wider candid panel can carry left-aligned copy inside. Contributor portraits are presented in dark 16px-radius cards.

**Transfer:** Show actual materials, workspaces and people. Keep the same warmth and shallow-focus treatment, not corporate headshots on white.

### Editorial portraits and interludes

**Only for:** founder stories

**Use:** Humanize long-form origin narratives.

**Observed:** 600px-wide reading column alternates prose with 600×338px rounded media and large personal statements. Two 280px-square portraits sit side by side below; one is naturally lit and cream-toned, the other has vivid blue-green ambient light.

**Transfer:** Use authentic contrasting portraits and media breaks to sustain a personal narrative without turning it into a full-width feature grid.

### Illustrated transformation band

**Only for:** subscription-focused feature pages

**Use:** Visualize the value of full access.

**Observed:** A wide rounded domestic scene splits cool blue shadow on the left from honey-gold illumination on the right, with softly modeled characters occupying both sides. Centered copy and a white action sit above a compact two-row inventory of softly lit icons.

**Transfer:** Show a credible before-and-after state through light and posture, not exaggerated performance claims; retain a quiet center for text.

**Build:** Split a wide scene into cool and warm lighting zones with overlapping radial washes, place the two subjects toward the outer thirds and leave the central column visually calm. Anchor a two-row icon collection below the action; use soft rounded dark icon beds with warm inner rim light.

### Icons

**Observed:** Navigation uses 50px circular white platform actions with dark glyphs; footer social marks are compact white silhouettes around 24px. Outcome tiles use small glossy symbolic illustrations rather than thin outline UI icons. FAQ rows use restrained gray plus signs.

**Transfer:** Choose simple solid utility glyphs for navigation, and reserve modeled symbolic objects for outcomes. Keep social and platform marks optically consistent instead of adding colored brand squares.

## Section recipes

How recurring sections are built.

### First screen: Cinematic promise

**Observed:** A 1420×810px scene sits in 10px outer gutters with 20px corners. Back to front: cover photography or video, localized darkening, centered white Display headline, cream Lead support, Primary button, then small proof lockups at the two bottom corners. Floating navigation remains centered over the top. The human subject fills the frame behind text; the promise spans about half the screen width and sits in the lower middle, with the support constrained to about 427px. Text and action are separated by 24px. Within the first 900px the navigation, main human scene, two-line promise, support, action and bottom endorsements are visible; only the start of the next centered chapter appears below the scene.

**Transfer:** Use a scene showing the emotional result of the new product. Without motion footage, use a carefully art-directed still with comparable light, framing and subject scale. Focused feature pages add a gold Eyebrow and can project a small product artifact below the scene; craft and purpose pages use the same cinematic composition but omit the primary action in favor of a descriptive promise.

**Avoid:** Do not replace the immersive scene with a half-width stock portrait beside a giant text block, or cover the whole scene with a heavy black veil.

**Text style:** `display` — Roobert 600 · 52px/54px

### Centered chapter introduction

**Observed:** Heading at 40px/40px, -0.02em, centered over a narrow support paragraph. Support sits 24px below in gray Lead or Body text; a 30–40px gap leads to media, with larger 60px chapter separation.

**Transfer:** Frame one desired outcome per chapter and let the visual demonstrate it.

**Text style:** `heading` — Roobert 600 · 40px/1 · tracking -0.02em

### Asymmetric capability pair

**Observed:** Within 1240px, a 407px Media feature card sits beside an 823px cinematic panel with a 10px gutter. The small card uses a caption below; the large panel places a 32px title and short explanation inside its upper-left or lower-left area. Equal-width variants use two 610px cards with a 20px gap.

**Transfer:** Pair a concrete product capability with a larger emotional or experiential demonstration, changing the wide side when it suits the story.

### Full-width product theater

**Observed:** Centered introduction precedes a 1240px rounded stage. A large upright device and projecting tactile objects occupy most of the image while a narrow right-hand text column contains Eyebrow, Feature heading, Body and Primary button. Deep purple or illustrated horizons remain inside the panel.

**Transfer:** Give one important capability enough space to feel like a small world rather than distributing equal emphasis across every feature.

### Library constellation

**Observed:** Centered heading, short support and action sit above the Content constellation. One enlarged item overlaps three rows of colorful cards; the outer artwork fades into the canvas and a Floating demo plaque interrupts the foreground.

**Transfer:** Make breadth feel abundant while keeping one output clearly foregrounded.

### Human proof wall

**Observed:** A centered Heading introduces four roughly 292px columns separated by 10px. Testimonial components stack with different lengths rather than rigid rows. A related proof variant is a horizontal carousel of 277×466px portrait videos with rounded corners and a small circular next control.

**Transfer:** Use permissioned personal experiences and authentic vertical clips, matching their naturally different lengths.

### Cinematic conversion

**Observed:** A 1400px-wide human scene with 40px corners carries a small outlined proof pill, centered 40px Heading, 20px Lead support and Conversion rail. A compact star-rating lockup sits underneath, and small endorsement groups occupy the lower corners. The reference band is 647px high; related editorial pages use 700px.

**Transfer:** Close the emotional argument with a human outcome and one clear invitation. Adapt the proof to facts the new product can support, retaining the immersive composition.

### Directory and outlined signature

**Observed:** The 1240px footer panel uses 24px top padding and 20px internal sides. Product, learning and company links form a useful directory alongside download and social actions. The Outlined identity occupies a 1200×320px lower region; small legal links finish the page. All page types share this ending.

**Transfer:** Retain the large, faint identity artwork even for a short page; adjust the directory's link count to the new product.

### Personal editorial column

**Only for:** founder stories

**Observed:** A 600px centered column opens with a Heading and uppercase Byline. Regular 18px/1.45 paragraphs are left aligned, separated by 40px media and quote breaks. A 40px/44px Editorial quote supplies a larger voice. Two founder portraits conclude the story before the common conversion and footer.

**Transfer:** Use for origin, purpose or personal essays, preserving intimacy instead of inflating the prose into a marketing grid.

**Text style:** `editorial-body` — Roobert 400 · 18px/1.45

### Illustrated feature education

**Only for:** focused feature pages

**Observed:** Focused feature pages alternate three 407px phone demonstrations with four 303px image-led use cases. Centered 24px titles and 18px explanations sit 20px and 8px below media. Later chapters use tactile concept illustrations and a course-like four-up sequence, followed by an Illustrated transformation band and the common footer.

**Transfer:** Move from practical use to underlying explanation and deeper engagement without requiring the original subject matter.

## Page flow

**Storyline:** Emotional promise → recognizable desires → tangible product worlds → human credibility → deeper engagement → objections or expanded value → immersive invitation → useful directory and monumental identity.

### Broad consumer-product landing page

1. **Promise** — Cinematic promise with human subject, centered copy and one action.
2. **Audience needs** — Compact outcome-choice tiles introduce the transformations visitors want.
3. **Capability chapters** — Large product theater, explanatory media panel, asymmetric pairs and content constellation vary the scale of proof.
4. **Credibility** — Collaborator story and immersive community invitation combine people with product.
5. **Deeper engagement** — Bright resource carousel, testimonial wall and vertical creator clips add multiple forms of social context.
6. **Objection handling** — Full-width understated FAQ rows.
7. **Wayfinding and identity** — Directory ends in the enormous outlined wordmark and legal links.

**Transfer:** Use varied media scale to sustain a broad landing page; chapter count and order can change while the tactile theater, human invitation and outlined identity remain recognizable.

### Focused capability or product-category page

1. **Promise** — Human cinema with category eyebrow, direct action and a product artifact projecting below.
2. **Product demonstration** — Three phone-based ways to use the capability.
3. **Use cases** — Four atmospheric portraits show recognizable life situations.
4. **Invitation and proof** — Immersive trial band followed by a personal testimonial wall.
5. **Education** — Three tactile concept illustrations explain how it works.
6. **Deeper engagement** — Four-up learning cards introduce extended practice.
7. **Expanded value** — Illustrated full-access transformation band and compact feature inventory.
8. **Wayfinding and identity** — Common directory and outlined signature.

**Transfer:** Tell a narrower story from use through understanding to wider product value; retain the scoped illustrative variants only where they help explain a specialized offering.

### Craft and production credibility page

1. **Promise** — Warm collaborative cinema opens with descriptive copy rather than an acquisition button.
2. **Process proof** — Three documentary cards explain making, sound and delivery.
3. **Principles in practice** — Asymmetric candid image and device demonstration connect lived experience to product content.
4. **Expert credibility** — Dark contributor portrait carousel.
5. **Craft demonstration** — Content constellation reveals the breadth of finished work.
6. **Culture** — A compact centered statement shifts attention to the people behind the product.
7. **Closing invitation** — Human cinematic conversion band.
8. **Wayfinding and identity** — Shared directory and outline artwork.

**Transfer:** Show real methods and materials, then reconnect the craft story to the user's experience and the common acquisition language.

### Founder-led purpose and origin story

1. **Purpose** — Atmospheric human cinema with a values-led promise.
2. **Personal narrative** — Narrow essay with bylines, media breaks and large first-person statements.
3. **Human credibility** — Two compact founder profiles with contrasting square portraits.
4. **Closing invitation** — Shared immersive conversion scene.
5. **Wayfinding and identity** — Shared directory and outlined signature.

**Transfer:** Use the narrow editorial variant for sustained storytelling, then return to the same visual conversion and identity system as the product pages.

## Writing

Warm, intimate and aspirational, with confident invitations and practical explanations beneath the poetic promise. The product speaks as a supportive guide rather than a demanding productivity coach.

**Do not copy:** Do not reuse Moonly's name, identity artwork, proprietary character illustrations, specific astrology claims, NASA references, audience counts, awards, endorsement logos, ratings or customer quotations. Source examples illustrate cadence only; use substantiated facts and permissioned quotes for the new product.

- **Addressing the reader:** Speak directly to you and your in benefits and invitations; use we for craft and company stories, and I for clearly attributed personal narratives. Outcome-choice tiles use the visitor's first person.
- **Rhythm:** Headlines are short and often split into two balanced lines. Support is usually one or two compact sentences; emphatic fragments and questions vary the cadence. Selective capitalization emphasizes key concepts without making full headings uppercase.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category and personal benefit, or ask an inviting question. | 5–11 words | “Next-Gen Astrology and Self-Discovery”<br>“Ready to uncover your Path through Tarot?” |
| Chapter heading | Lead with an attainable change; pair a verb with a felt outcome. | 4–8 words | “Restore Strength and Inner Balance”<br>“Gain clarity for life's Big Decisions” |
| Supporting explanation | Connect a relatable situation to a plain-language benefit. | 12–30 words | “When you're confused, Tarot cuts through the noise and shows you what matters most” |
| Primary action | An accessible verb and concrete next step; learning actions stay understated. | 2–7 words | “Get Started”<br>“Pick a card — get your insight”<br>“Learn more” |
| Craft claim | Make the labor feel caring, tangible and human. | 4–7 words | “Meditations are made by hand”<br>“Wisdom, put into words” |
| Social proof heading | Short parallel phrases describe a human effect. | 4–7 words | “Real stories. Real transformations.” |

**Words and phrasing to use:** clarity; your path; discover; balance; with care; guidance; inner; meaningful; journey; tailored to you

**Avoid:** crush it; dominate; 10x your life; enterprise-grade; disruptive ecosystem; limited-time panic; clinical jargon without explanation

**Rules:**

- Promise an understandable personal benefit before explaining a mechanism.
- Keep category labels brief and literal; reserve metaphor for headings and image direction.
- Make invitations feel exploratory rather than urgent.
- Separate personal belief or experience from verifiable product facts.
- Use fragments deliberately in paired headings; keep longer explanations grammatical and accessible.

## Do's and Don'ts

### Do

- Keep the main canvas charcoal and let color concentrate inside 20px-radius media stages.
- Set the opening promise at 52px/54px and centered chapter headings at 40px/40px with -0.02em tracking.
- Use a 1400px desktop wrapper with 80px internal sides for the core 1240px working width.
- Alternate 610px pairs with 407px/823px asymmetry to change the scale of demonstrations.
- Keep primary actions white, 50px high and 60px rounded, even over vivid artwork.
- Use 12px uppercase gold labels with 0.05em tracking to identify capabilities.
- Include tactile product theater, a layered content constellation, a human conversion scene and a faint outlined identity as recurring visual signatures.
- Use 18px/1.45 Regular prose in the 600px editorial variant rather than stretching narrative text across the feature grid.

### Don't

- Do not turn the gold label color into a full-page background or a repeated yellow CTA fill.
- Do not replace semibold marketing copy with an ultra-light grotesk; the warmth depends on substantial rounded lettering.
- Do not apply the navigation's 27px glass blur to every content card; most media beds are opaque charcoal.
- Do not make every radius identical: media uses 20px, intent tiles 30px, actions 60px and glass capsules 100px.
- Do not surround testimonial columns with bright borders, colored fills or equal-height boxes; they nearly merge into the canvas.
- Do not make the footer identity solid white; it is a low-contrast outline in a 1200×320px artwork region.
- Do not enlarge small captions into giant all-caps slogans; uppercase is concentrated in 12px labels.
- Do not flatten the media library into a uniform thumbnail grid with no central foreground object.

## Motion and responsive

### Motion

**Observed:**

- Opening, feature and conversion scenes use video media; the navigation remains fixed during page traversal.
- No action or surface transitions or keyframe animations are established. Some text links declare underline changes on hover.

**Transfer:**

- Use motion inside the bounded cinematic and product stages rather than animating every text element. A still composition must retain the same hierarchy and light.

**Unknown:**

- Playback behavior, scroll triggers, durations and easing for the cinematic artwork are not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 810px, 1280px and 1420px across the page types. Additional declarations occur around 600px and 1200px for personal editorial content.

**Transfer:**

- On narrower layouts preserve the human subject and centered promise before preserving the wide scene's full background; keep the action separate from busy detail.
- Recommended adaptation: stack the asymmetric pair, reduce the content constellation's visible side tiles while retaining its central object, and fit the outlined identity to the available width.
- Keep the editorial column comfortably readable rather than replacing it with a broad multi-column layout.

**Unknown:**

- Exact mobile type sizes, navigation collapse, gutter values and media substitutions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
