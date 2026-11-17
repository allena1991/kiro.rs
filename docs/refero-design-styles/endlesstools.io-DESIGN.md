# Endless Tools — blackboard meets render studio

## Overview

A black, gallery-like canvas pairs restrained grotesk typography with exuberant rendered objects and loose white pen marks. Hot pink and electric blue appear as tiny action accents while colorful materials, product scenes and creative output supply most of the energy. The feeling is exploratory and hands-on rather than corporate, suited to visual tools and products whose possibilities are best shown through artifacts. Text is compact, with large fields of breathing room around irregular image constellations.

### Essentials

- Headlines feel annotated rather than decorated: Inter 500 at 42px/46px with -0.03em tracking, split into compact centered lines and marked with thin, imperfect white circles, underlines or stepped outlines.
- The opening is a compact promise above a sprawling workbench: an 80px sticky header, a centered two-line headline, 350px-wide muted support and a 36px pink pill lead into a 1270px-wide constellation of small objects, imported assets and hand-drawn arrows.
- Controls are miniature capsules, not big sales banners: 12px/14px medium labels, 35–36px heights, 20px horizontal padding and fully rounded ends; white is the everyday action, pink marks the opening and blue distinguishes a targeted offer.
- Black is the uninterrupted ground: #000000 surrounds #080808 proof cards and #121212 pricing cards; #959595 supports white headings. Saturation belongs to imagery and small controls, not full-width colored bands.
- Creative possibility is shown as a constellation, not a uniform feature grid: isolated glossy or textured objects mingle with rounded photographs and output mockups, with white arrows and plus signs connecting ideas. A new product without 3D media still needs an equivalent collage of real inputs and finished artifacts.
- Human proof stays pocket-sized: dark rounded social cards and a floating 54px-high quote capsule with a 38px portrait provide warmth without giant quote typography; the page closes with a narrow 310px email form and small centered footer rows.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Exploration pink | `#ff13b1` | `--color-pink` | action | Opening action only; keep the colored area small. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-foreground` | text, action | Headlines, annotation strokes and white action fills. |
| Support grey | `#959595` | `--color-muted` | text, border | Support paragraphs, footer links and the login outline. |
| Proof edge | `#373737` | `--color-edge` | border, surface | Social card hairlines, input outline and header action hover. |
| Asset edge | `#343434` | `--color-asset-edge` | border | Thin outline around floating asset frames. |
| Pricing edge | `#222222` | `--color-pricing-edge` | border | Subtle inset line on pricing cards. |
| Field charcoal | `#1e1e1e` | `--color-field` | surface | Email input and solid login hover surface. |
| Pricing charcoal | `#121212` | `--color-card` | surface | Pricing card fill. |
| Action ink | `#0a0a0a` | `--color-ink` | text, surface | Text on white buttons and backing for broad media. |
| Proof black | `#080808` | `--color-proof` | surface | Social proof card fill, slightly separated from the canvas. |
| Absolute black | `#000000` | `--color-canvas` | background | Continuous page ground and the dark end of edge fades. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| targeted audience offers | Offer blue | `#2c5cff` | `--color-blue` | action | Targeted audience actions. |
| premium plan actions | Upgrade lime | `#b8ff45` | `--color-gradient-lime` | accent | First stop of the premium action gradient. |
| premium plan actions | Upgrade gold | `#ffcb45` | `--color-gradient-gold` | accent | Middle stop of the premium action gradient. |
| premium plan actions | Upgrade magenta | `#ff00b8` | `--color-gradient-pink` | accent | Final stop of the premium action gradient. |

## Typography

- **Inter** — All marketing headings, support copy, prices and controls. Neutral contemporary grotesk, medium rather than bold headings and tightly packed display lines. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 500 | 42px | 46px | -0.03em | Opening promise and major section headings; usually centered in two short lines. |
| heading | Inter | 500 | 24px | 26px | -0.03em | Collage labels and smaller chapter headings. |
| feature-title | Inter | 400 | 18px | 20px | -0.025em | Short benefit titles in a centered feature stack. |
| body | Inter | 400 | 14px | 18px | normal | Muted support paragraphs and footer links. |
| social-body | Inter | 500 | 14px | 18px | normal | User-authored text inside social proof cards. |
| quote | Inter | 400 | 14px | 20px | normal | Single-line quote in the floating proof capsule. |
| action | Inter | 500 | 12px | 14px | normal | Button labels and compact metadata. |
| attribution | Inter | 400 | 12px | 18px | normal | Muted name and role below the small quote. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing sections | price | Inter | 500 | 42px | 1 | -0.03em | Plan price; aligned beside the plan label. |
| pricing sections | plan-description | Inter | 400 | 18px | 20px | normal | White plan descriptions above feature lists. |

**Notes:**

- The display and 24px heading share -0.03em tracking; support copy and action labels return to normal tracking.
- Keep medium headings at weight 500, not heavy bold. Large visual impact comes from imagery and pen outlines rather than oversized type.
- Use narrow support measures, generally 300–440px; the opening support is 350px wide. Do not stretch paragraphs to the image container width.

## Layout

**Density:** Airy at section scale, compact within text and controls; small captions float in large black intervals.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Feature title to support copy. |
| 10px | Header action gap and stacked form controls. |
| 15px | Card padding and pricing column gaps. |
| 20px | Button side padding, ordinary support-to-action spacing and footer row gaps. |
| 25px | Benefit-stack separation and plan description offset. |
| 30px | Audience action to media and benefit introduction to imagery. |
| 40px | Desktop outer page padding. |
| 80px | Large section breathing room and header height. |
| 150px | Footer top padding. |
| 200px | Long pauses after major pricing and audience chapters. |

### Containers and grids

- **Main media container**: max width 1270px · side padding 40px. Centered large illustrations, audience scenes and three-part feature compositions; side padding belongs to the outer wrapper.
- **Heading container**: max width 900px · side padding 40px. Centered major heading area, with narrower paragraphs nested inside.
- **Demo stage**: max width 1300px. Broad landscape product demonstration, 700px tall on desktop.
- **Pricing row**: max width 1100px · 3 columns · gap 15px. Equal-height plan cards, approximately 357px wide.
- **Benefits triptych**: max width 1270px · 3 columns · gap 20px. Two 410px-wide image compositions flank a centered 410px-wide text column.
- **Newsletter**: max width 310px. Centered single-column input and submit control.

## Corner radius

| Element | Radius |
| --- | --- |
| Actions and proof capsule | 9999px (pill) |
| Social cards | 12px |
| Floating asset frames | 16px |
| Large media | 20px |
| Pricing cards | 33px |
| Embedded social media | 7px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Proof card inset | `inset 0 0 0 1px #373737` | Fine boundary around social cards. |
| Plan card inset | `inset 0 0 0 1px #222222` | Fine boundary around pricing cards. |
| Quote capsule outline | `0 0 0 1px rgba(255,255,255,0.1)` | A barely visible edge on the floating testimonial. |

### Surfaces

#### Black canvas · level 0

**Use:** Unbroken page background.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Sections blend into one another with black negative space rather than alternating bands.

**Transfer:** Let media establish chapter changes.

#### Plan shell · level 1

**Use:** Grouped purchase options.

**CSS:** `background: #121212; border-radius: 33px; box-shadow: inset 0 0 0 1px #222222; padding: 15px`

**Observed:** Large soft corners and an almost invisible inset edge; not a lifted shadow.

**Transfer:** Keep all plans materially equal and distinguish offers through small badges and actions.

#### Social shell · level 1

**Use:** Authentic user proof.

**CSS:** `background: #080808; border-radius: 12px; box-shadow: inset 0 0 0 1px #373737; padding: 15px`

**Observed:** Darker than the pricing cards, with a slightly clearer outline.

**Transfer:** Retain natural post heights rather than imposing identical content lengths.

#### Media backing · level 1

**Use:** Large photographic or product scenes.

**CSS:** `background: #0a0a0a; border-radius: 20px; overflow: hidden`

**Observed:** A 1270px-wide, approximately 16:10 scene appears beneath a centered audience pitch.

**Transfer:** Fill the frame with real contextual media, not a colored placeholder.

#### Asset frame · level 1

**Use:** Small floating imported assets.

**CSS:** `border: 1px solid #343434; border-radius: 16px; overflow: hidden`

**Observed:** Minimal frames hold isolated objects or source images in an otherwise open collage.

**Transfer:** Mix framed assets with cutout objects to avoid a wall of identical tiles.

## Components

### Sticky navigation

**Use:** Persistent brand and account actions.

**CSS:** `position: sticky; top: 0px; height: 80px; z-index: 50; background: linear-gradient(#000000 14.73%, rgba(0,10,10,0) 100%)`

**Observed:** A small white stacked logo is left aligned; login and white signup capsules sit at the far right. The inner row uses 40px side padding and 20px vertical padding.

**Transfer:** Use a compact identity and two short utility actions instead of a full menu bar.

### Opening button

**Use:** Primary action under the opening promise.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 0px 20px; border-radius: 9999px; background: #ff13b1; color: #ffffff`

**Text style:** `action` — Inter 500 · 12px/14px

**Observed:** Content-width capsule, centered and visually isolated beneath muted support.

**States:** Declared: hover background-color #ff4bc4; focus-visible not specified.

### White button

**Use:** Default conversion control in feature and pricing sections.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 0px 20px; border-radius: 9999px; background: #ffffff; color: #0a0a0a`

**Text style:** `action` — Inter 500 · 12px/14px

**Observed:** Content-width in a feature section and full inner width on plan cards. The header version is 35px high and uses a 16px backdrop blur; the newsletter submit is also 35px high.

**States:** Declared: hover background-color #c4c4c4; header variant hover background-color #373737 and color #ffffff; focus-visible not specified.

### Login button

**Use:** Low-emphasis header utility.

**CSS:** `display: inline-flex; align-items: center; height: 35px; padding: 0px 20px; border-radius: 9999px; background: rgba(30,30,30,0.8); color: #959595; box-shadow: inset 0 0 0 1px #959595; backdrop-filter: blur(16px)`

**Text style:** `action` — Inter 500 · 12px/14px

**Observed:** Sits directly beside the brighter signup capsule; the translucent fill reads almost black.

**States:** Declared: hover background-color #1e1e1e and color #ffffff; focus-visible not specified.

### Social proof card

**Use:** Community-made outputs and user testimony.

**CSS:** `background: #080808; border-radius: 12px; box-shadow: inset 0 0 0 1px #373737; padding: 15px`

**Text style:** `social-body` — Inter 500 · 14px/18px

**Observed:** Avatar and identity come first, then a short post and a rounded media attachment. Desktop cards are 390px wide inside 400px slide slots; heights vary and bottoms align.

**Transfer:** Use real user work and attributable remarks, retaining each artifact's color palette.

### Email input

**Use:** Low-friction closing signup.

**CSS:** `height: 35px; width: 310px; padding: 0px 20px; border-radius: 9999px; background: #1e1e1e; box-shadow: 0 0 0 1px #373737; text-align: center`

**Text style:** `action` — Inter 500 · 12px/14px

**Observed:** A centered dark pill above a same-width white submit; below it sit a small circular consent control and muted privacy text.

**Transfer:** Keep this as a single-field form rather than turning it into a multi-field sales form.

### Footer links

**Use:** Contact, social and legal navigation at the end.

**CSS:** `display: flex; justify-content: center; gap: 20px; color: #959595`

**Text style:** `body` — Inter 400 · 14px/18px

**Observed:** A first row holds contact and social links; a second holds legal links; copyright sits on a third line. Rows are separated by 20px.

**States:** Declared: hover color #ffffff; focus-visible not specified.

### Quote capsule

**Use:** A small persistent layer of human endorsement.

**CSS:** `display: flex; align-items: flex-start; gap: 12px; padding: 8px 24px 8px 8px; border-radius: 9999px; box-shadow: 0 0 0 1px rgba(255,255,255,0.1); backdrop-filter: blur(12px)`

**Text style:** `quote` — Inter 400 · 14px/20px

**Observed:** A dark translucent capsule, 54px high, contains a 38px circular portrait and two lines: white quote and grey attribution. It stays centered 16px above the viewport bottom, with changing endorsements.

**Transfer:** Use a real concise quote and keep the layer small enough not to obscure the main artwork.

### Audience button

**Only for:** targeted audience offers

**Use:** A dedicated audience-specific conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 0px 20px; border-radius: 9999px; background: #2c5cff; color: #ffffff`

**Text style:** `action` — Inter 500 · 12px/14px

**Observed:** Centered below support copy or stretched across the related plan card.

**States:** Declared: hover background-color #5a65ff; focus-visible not specified.

### Premium button

**Only for:** premium plan actions

**Use:** The standout paid-tier action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 0px 20px; border-radius: 9999px; color: #0a0a0a; background-image: linear-gradient(97.25deg, #b8ff45 3%, #ffcb45 22%, #ff00b8 100%); background-size: 200% 200%`

**Text style:** `action` — Inter 500 · 12px/14px

**Observed:** A narrow animated color strip at the bottom of the plan; the card itself remains charcoal.

### Pricing card

**Only for:** pricing sections

**Use:** Comparable purchase options.

**CSS:** `display: flex; flex-direction: column; background: #121212; border-radius: 33px; box-shadow: inset 0 0 0 1px #222222; padding: 15px`

**Text style:** `plan-description` — Inter 400 · 18px/20px

**Observed:** Plan badge and price share the top row; a short white description follows. Compact feature rows or a hand-drawn smile occupy the middle, with the action pinned to the bottom. Desktop cards are 562px tall.

**Transfer:** Use similarly sized cards even when entry-tier content is sparse; a simple pen illustration can balance the empty area.

## Imagery and graphics

### White pen annotations

**Use:** Signature emphasis on headlines, diagrams and the closing form.

**Observed:** Imperfect thin white marks encircle individual words, underline phrases, form clouds or stepped boxes around headings, and draw arrows between clusters. A small heart introduces community proof and a simple smile fills an entry plan. These marks contrast with polished media.

**Transfer:** Annotate a key phrase and connect a pair of related artifacts on every new marketing page. Keep the marks human and sparse.

**Build:** Place transparent SVGs behind or beside text with overflow visible. Use unfilled white paths, approximately 1–2px stroke, round caps and joins. Draw an asymmetric ellipse with a small overlap, a slightly wavy underline, or a stepped outline around two unequal text lines. Draw long curved arrows with separate two-stroke open arrowheads; use a plain crossed pair of lines for a plus sign. Scale paths with their text wrapper rather than the whole viewport.

### Artifact constellation

**Use:** Opening capability workbench and exploration-to-output chapters.

**Observed:** Small floating 3D objects, source files and rounded photos orbit compact text islands on pure black. Materials include polished chrome, mint and lime plastic, cloth, rough stone, cloud-like white volume and particles. Later collages mix these cutouts with a tablet, phone, apparel and campaign imagery; asymmetric sizes and overlaps imply active experimentation.

**Transfer:** Show the new product's raw inputs on one side and credible outputs on the other. Minimum version: a handful of distinct artifact images with transparent cutouts and rounded context shots, connected by pen arrows; do not substitute generic icons.

**Build:** Use a relative 1270px-wide stage with independently positioned image wrappers and generous black gaps. Alternate transparent object renders with 16px-rounded crops; stagger their vertical positions. Keep short centered text islands clear, add a white plus between paired concepts, and route curved SVG arrows through the negative space. Avoid a shared panel behind the full constellation.

### Product demonstration

**Use:** Large proof of the working tool.

**Observed:** A broad landscape editor scene shows small dark toolbars around a brightly colored dimensional result. A lime word object and reflective metallic spiral dominate one example; the interface is subordinate to the artwork.

**Transfer:** Show one memorable result within a believable working environment. If no editor exists, use a large outcome scene with a few truthful process details rather than fabricating controls.

### Shared-work triptych

**Use:** Explaining collaboration or reusable outcomes.

**Observed:** A left-side composition combines small portraits and role tags around an asset panel; the right stacks overlapping output cards. A quiet central column holds three short benefits and a white action, all within a 1270px-wide row.

**Transfer:** Use genuine participants or input types on one flank and repeatable outputs on the other. Preserve the contrast between busy visual wings and a sparse text center.

### Contextual product photograph

**Only for:** audience-specific chapters

**Use:** Making an audience offer feel tangible.

**Observed:** A rounded 1270px-wide, 16:10 image shows a large display in a warm neutral lecture space, people in soft motion and vivid green and purple objects on screen. The room stays natural and subdued so the digital content carries the color.

**Transfer:** Stage the new product in a credible real setting with warm neutral surroundings, then let its output become the saturated focal point.

### Icons

**Observed:** Tiny monochrome feature pictograms accompany compact pricing rows. Carousel arrows use small simple chevrons inside 40px circular dark controls. The freehand arrows and symbols are visibly different from these functional icons.

**Transfer:** Use restrained white functional symbols; reserve rough strokes for explanatory annotations rather than every control.

## Section recipes

How recurring sections are built.

### First screen: Annotated workbench opening

**Observed:** The first 900px contains the 80px Sticky navigation, a compact centered two-line display promise, a two-line grey support paragraph and the Opening button. The headline is about 450px wide within a 900px heading container, not a full-width billboard; one inline word is circled and the audience phrase underlined. Behind everything is Black canvas; pen paths sit close to the words, then text and the action sit above them. Below and partly beside the action, an Artifact constellation spreads over a 1270px-wide, 820px-tall stage: small source objects at the left, imported photo and model tiles at the right, short capability labels between them, and long white arrows connecting groups. Only part of the constellation fits above the fold; the rest continues below. A Quote capsule floats near the viewport bottom.

**Transfer:** Use a two-line promise with one concept annotated, followed by a compact support line and one pink action. Populate the workbench with real inputs and outputs for the new product; non-visual products can use document fragments, deliverable previews and process artifacts. More focused page types can open with a smaller artifact set while retaining the annotated promise and black stage.

**Avoid:** Do not replace this with a giant left-aligned headline beside one dashboard, or contain the whole first screen inside a colored hero card.

**Text style:** `display` — Inter 500 · 42px/46px · tracking -0.03em

### Annotated chapter heading

**Observed:** Centered display text usually spans one or two short lines, followed by grey body copy with a 15–35px pause. Pen outlines vary by message: underline, cloud, stepped box or spiky burst. Chapter labels inside collages use the 24px heading instead.

**Transfer:** Choose one mark that supports the meaning of the headline, keeping support plain and narrow.

**Text style:** `display` — Inter 500 · 42px/46px · tracking -0.03em

### Wide working demonstration

**Observed:** A compact centered chapter introduction precedes a 1300px by 700px Product demonstration. The visual carries far more area than the paragraph and blends its dark perimeter into the page.

**Transfer:** Follow a conceptual claim with one convincing visual result at generous scale rather than several tiny feature screenshots.

### Input and output constellation

**Observed:** A small centered heading branches into two text islands, linked by hand-drawn downward arrows and separated by a white plus. Irregular cutouts and rounded context photos flank both sides across nearly the full page width.

**Transfer:** Translate an abstract capability into a family of inputs and finished applications; adjust the number of artifacts to the content, not to a fixed card count.

**Text style:** `heading` — Inter 500 · 24px/26px · tracking -0.03em

### Soft-corner pricing row

**Observed:** An outlined display heading and narrow support introduce a centered billing choice and three Pricing cards in an 1100px row with 15px gaps. Large prices sit beside small pill labels. Actions align at the bottom; the premium action is a gradient and a targeted audience action is blue.

**Transfer:** Keep the purchase explanation plain and legible; use color on the action rather than tinting an entire recommended card.

**Text style:** `display` — Inter 500 · 42px/46px · tracking -0.03em

### Visual wings and benefit center

**Observed:** A stepped-outline heading introduces the Shared-work triptych. Three compact benefits use feature-title and body recipes, with 20px between groups and a content-width White button below.

**Transfer:** Explain a workflow benefit through a calm text spine between two artifact compositions.

### Audience scene

**Observed:** An annotated centered display heading, narrow muted paragraph and Audience button sit above Media backing containing a full-width contextual product photograph. The image is the dominant proof.

**Transfer:** Use this scoped variant for a distinct audience whose setting adds useful context, not for every ordinary feature.

**Text style:** `display` — Inter 500 · 42px/46px · tracking -0.03em

### Community output carousel

**Observed:** A small hand-drawn heart sits above a two-line centered heading and muted support. Social proof cards form a horizontally clipped, bottom-aligned row with uneven tops. Small circular arrows sit at the edges, a black gradient fades the outgoing edge and a short progress indicator sits below.

**Transfer:** Collect genuine work in varied formats while retaining consistent card shells and metadata order.

### Compact closing signup and footer

**Observed:** A centered display heading introduces a 310px Email input and White button stacked 10px apart. Consent text follows after 20px, with a pen arrow pointing toward it. The footer begins after a 150px top pause, uses Footer links in two centered rows and a copyright line, and ends with 75px bottom padding. The Quote capsule remains above the viewport edge.

**Transfer:** End with a small useful invitation, a single input and an intentionally modest footer instead of another monumental sales pitch.

**Text style:** `display` — Inter 500 · 42px/46px · tracking -0.03em

## Page flow

**Storyline:** Compact promise → exploratory possibilities → working proof → real applications → purchase paths → audience value → community proof → small ongoing invitation.

### Introduce a visual product through possibility, use and credible outputs, then make entry feel easy

1. **Promise** — Annotated compact headline, pink action and scattered input artifacts.
2. **Capability exploration** — Text islands connect a library, generated objects and imported assets through white arrows.
3. **Product demonstration** — A short challenge statement precedes a broad working scene with vivid artwork.
4. **Outcome range** — An asymmetric collage links experimentation to finished real-world applications.
5. **Pricing** — Three equal charcoal plan shells with large prices and differentiated small actions.
6. **Audience value** — A visual triptych explains shared work; a separate scene-led pitch addresses another audience.
7. **Social proof** — Authentic posts and their media appear in a bottom-aligned horizontal carousel.
8. **Closing invitation** — A narrow email signup leads into spare centered contact and legal rows.

**Transfer:** Borrow the shift from promise to tangible artifacts to trust. Reorder or combine chapters for the new product while preserving annotated headlines, visual experimentation, compact actions and a restrained ending.

## Writing

Direct, encouraging and creatively literate. It talks like a maker inviting another maker to try things, grounding possibilities in concrete actions and outputs rather than grand category claims.

**Do not copy:** Do not reuse the Endless Tools name, logo, recognizable spiral artwork, customer identities, testimonials, pricing, performance claims or exact product promises. Source examples illustrate voice, not reusable claims.

- **Addressing the reader:** Use imperative invitations and occasional you/your. Refer to the product plainly by its name; avoid a heavy institutional we.
- **Rhythm:** Short headlines often pair two clauses or contrast an obstacle with an outcome. Supporting copy uses one or two compact sentences or a concise list of concrete media and deliverables. Actions are two to four words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the tool's kind and the person or activity it serves. | 6–10 words | “A visual tool for graphic designers.” |
| Chapter heading | Pair a simple action with an expansive result; use a full stop to create a second beat. | 4–7 words | “Create once. Reuse everywhere.”<br>“Teach ideas, not software.” |
| Support | Invite action with tangible nouns, then explain the practical benefit. | 12–28 words | “Bring your assets. Try materials, effects, type, 3D, AI and motion. Find a look worth developing.” |
| Action | A short verb-led invitation with little friction. | 2–4 words | “Start exploring”<br>“Try for free”<br>“Stay updated” |

**Words and phrasing to use:** try; bring; combine; explore; make; reuse; shared; one workspace; from idea to outcome

**Avoid:** revolutionary; unprecedented; enterprise-grade synergy; unlock limitless potential; disrupt; best-in-class

**Rules:**

- Use concrete input and output nouns instead of strings of adjectives.
- Let a headline make one point; put the how in a short support paragraph.
- Use parallel verbs for linked capabilities.
- Keep targeted audience offers specific to what that audience can do.

## Do's and Don'ts

### Do

- Keep major headings at 42px/46px, weight 500 and -0.03em tracking.
- Use #959595 for narrow support paragraphs against uninterrupted #000000.
- Keep ordinary action capsules 35–36px high with 20px side padding.
- Make the white pen annotation a recurring counterpart to polished imagery.
- Use 15px card padding and a 1px inset edge instead of deep elevation.
- Let broad visual chapters use a 1270px container while text stays much narrower.
- Keep social cards naturally unequal in height and aligned at the bottom.
- Finish with the 310px-wide signup and small centered footer rows.

### Don't

- Do not inflate the interface into 52–64px-high sales buttons; the controls are deliberately small.
- Do not make headings weight 700 or introduce a second display family.
- Do not turn pink or blue into full-section backgrounds; their role is a small action accent.
- Do not apply the 33px pricing radius to every image; media uses 16–20px and social cards 12px.
- Do not add luminous box shadows or glass panels behind every chapter; boundaries are restrained 1px lines.
- Do not normalize all collage media into one aspect ratio or a uniform tile grid.
- Do not stretch muted body copy across the 1270px media width.
- Do not end with a multi-column corporate sitemap or a huge repeated hero pitch.

## Motion and responsive

### Motion

**Observed:**

- Actions and plan surfaces declare .15s transitions with cubic-bezier(.4,0,.2,1), including color, background-color, opacity, shadow and transform properties.
- The premium gradient declares a 1.5s ease-in-out infinite alternate move-gradient animation, with background-size 200% 200%.
- The small floating endorsement changes content while remaining centered near the lower edge.

**Transfer:**

- Keep the moving color treatment confined to the premium capsule rather than animating the whole page background.
- Preserve a stable black stage and crisp white pen marks around any moving product media.

**Unknown:**

- Exact pen-drawing timing, scrolling choreography, carousel timing and endorsement rotation interval are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 480px, 640px, 720px, 768px, 980px, 1024px and 1240px.
- The outer padding changes from 20px to 40px; the major heading switches between secondary and primary sizes.
- The benefit composition declares two columns before its three-column layout; the central text follows the two visual wings at narrower widths.
- Pricing and social card wrappers declare narrow-screen widths of 85%, allowing partial neighboring cards.

**Transfer:**

- On narrow screens, preserve the collage idea but arrange artifacts in a shorter readable sequence rather than shrinking every desktop coordinate.
- Keep the two image wings together and move the benefit text below; let plan and social rows expose a neighboring card.
- Keep the narrow form within the available width and let compact footer rows wrap.

**Unknown:**

- Mobile appearance and the exact alternative opening constellation arrangement are not established; the narrow-screen transfer is design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
