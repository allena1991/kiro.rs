# Ragged Edge — worlds in motion

## Overview

An expansive editorial style with a cinematic, almost hallucinatory first impression and a remarkably plainspoken reading experience underneath. Broad, bold grotesk headings meet literary serif paragraphs on white, with pale mint controls and vivid color concentrated in imagery. It suits ambitious products and services that can demonstrate a distinctive point of view through richly art-directed work, human stories and concrete outcomes. The density alternates between immersive visual fields and spacious, ruled editorial layouts.

### Essentials

- Identity becomes a horizon: a full-width, flattened wordmark spans 1376px inside 32px margins, centered over a 900px-high atmospheric scene; navigation sits at the bottom rather than competing above it. Recreate this identity stage even without film, using a custom word treatment over blurred radial light.
- Broad sans statements meet unusually substantial serif prose: display headings use ABC Diatype Expanded Bold at 82px/1.1 with -0.02em tracking, while the manifesto paragraph uses Grit Regular at 56px/1.2. Ordinary chapter and closing headings use 78px/1.15 with -0.01em tracking.
- Controls feel like small floating lozenges, not corporate rectangles: serif labels at 16px/1, 40px height, 12px 16px padding, 64px corners and a mint translucent fill with 40px backdrop blur; dark variants are ink with white text.
- Color lives inside worlds rather than across the whole interface: the default long-form canvas is white with dark ink and 1px ink-at-20% rules. The opening is entirely cinematic color, followed by predominantly white editorial space; saturated fills belong to bounded media, not a rainbow of feature cards.
- Proof is an editorial spread, not a dashboard: on a 12-column grid with 12px gutters, the left three columns carry the title, compact sans claim and small result with serif explanation; an eight-column 913px × 514px image sits to the right. Keep the result compact at 20px/24px, never a giant KPI.
- Media edges occasionally bend like a sheet being pulled: preserve the signature inward-to-outward curved edge treatment on a visual or editorial card, alongside predominantly square image framing. Pair that device with a monumental 78px closing question, practical contact rows and a human-scale studio image; use an original workplace or product-making scene as the equivalent.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric pale cyan | `#96ebeb` | `--color-cyan` | accent, action | Hover fill for pills and one band of the multicolor transition field. |
| Transition amber | `#ffc240` | `--color-amber` | accent | Warm band in the full-screen transition field, not a default section background. |
| Transition pink | `#ffc4f4` | `--color-pink` | accent | Pink band in the full-screen transition field. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Default editorial canvas and reversed control text. |
| Solid mint | `#ebf7f3` | `--color-mint-solid` | surface, action | Solid selected control in the cinematic opening and light chapter-control hover. |
| Mint glass | `#eaf7f3` | `--color-mint-glass` | surface, action | Visible mint control wash on white; built with #dcf2eb at 60% opacity. Over imagery it takes on the colors beneath. |
| Fine rule | `#d1d2d2` | `--color-rule` | border | Visible 20% ink rule on white; implement with rgba(24,31,31,0.2). |
| Muted utility ink | `#a3a5a5` | `--color-muted` | text | Visible 40% ink for small Copy utilities on white. |
| Soft grey ink | `#737777` | `--color-secondary-ink` | text | Muted phase of the large introductory statement; settled editorial text uses primary ink. |
| Badge green-black | `#1f3233` | `--color-badge-ink` | surface | Tiny external-link capsules in editorial cards. |
| Green-black ink | `#181f1f` | `--color-ink` | text, background, action | Primary text, dark pills and strong graphic contrast. |
| Pure black | `#000000` | `--color-black` | text | Small navigation text on the mint-glass pills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| method and company pages | Cool method canvas | `#f7fcfa` | `--color-method-canvas` | background | Very pale cool canvas for explanatory company material. |

## Typography

- **ABCDiatypeExpanded** — Broad headings, compact editorial titles, labels and results. Bold extended grotesk with low, wide proportions; the width is as important as the weight. OpenType features: "kern". If unavailable, use **Archivo Expanded**. Use 700; preserve the broad proportions and restrained negative tracking. Font stack: "ABCDiatypeExpanded", "Archivo Expanded", sans-serif.
- **Grit** — Manifestos, narrative prose, captions, navigation and action labels. Lively contemporary text serif with a literary texture; it gives even the controls a human voice. OpenType features: "kern". If unavailable, use **Libre Caslon Text**. Use 400; check line wrapping against the spacious original proportions. Font stack: "Grit", "Libre Caslon Text", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ABCDiatypeExpanded | 700 | 82px | 1.1 | -0.02em | Primary introductory statement following the identity stage. |
| heading | ABCDiatypeExpanded | 700 | 78px | 1.15 | -0.01em | Major page titles, closing question and prominent section headings. |
| manifesto | Grit | 400 | 56px | 1.2 | normal | Large editorial introduction with a few deliberate lines of prose. |
| project-title | ABCDiatypeExpanded | 700 | 40px | 1.2 | -0.01em | Names at the top of project and proof spreads. |
| label-strong | ABCDiatypeExpanded | 700 | 20px | 1.2 | normal | Compact claims, result values and contact-row labels. |
| card-title | ABCDiatypeExpanded | 700 | 20px | 1.2 | -0.01em | Centered editorial card titles and small case-study name above a page title. |
| body | Grit | 400 | 20px | 1.2 | normal | Supporting captions, contact details and compact editorial prose. |
| action | Grit | 400 | 16px | 1 | normal | Small navigation, filter and social pills. |
| caption | Grit | 400 | 16px | 1.2 | normal | Attributions and footer navigation. |
| card-category | ABCDiatypeExpanded | 700 | 16px | 1.2 | normal | Short category centered above an editorial card title. |
| copy-utility | ABCDiatypeExpanded | 700 | 12px | 2 | normal | Copy action beside contact details. |

**Notes:**

- Headings are visually bold even though the font cut uses a regular CSS weight declaration. Do not render them with a regular-width sans.
- The largest introductory sans uses -0.02em tracking; the remaining headings use -0.01em, while body and small controls retain normal tracking.
- The first-screen wordmark is vector artwork, not an 82px text heading: its very wide, compressed silhouette is 1376px × 62px at desktop. Fit an original identity to that visual role instead of enlarging body type.
- Use primary ink for settled reading. The grey introductory text is a muted presentation phase, not the default contrast for every headline.

## Layout

**Density:** Airy: editorial blocks have long pauses, but navigation and utilities are tightly grouped.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 4px | Separation between adjacent navigation and social pills. | fixed |
| 12px | Grid gutters, paired-media gaps and short pauses within image sequences. | fixed |
| 16px | Top inset after a hairline and horizontal pill padding. | fixed |
| 24px | Vertical inset in editorial card text panels. | fixed |
| 32px | Desktop page side margins, contact-row spacing and bottom navigation inset. | fixed |
| 48px | Gap from introductory display heading to serif manifesto. | fixed |
| 64px | Horizontal inset in centered editorial card panels. | fixed |
| 120px | Short chapter and media-group separation. | fixed |
| 180px | Long separation between proof rows and between substantial image chapters. | fixed |
| 200px | Pause after a project list or editorial collection. | fixed |
| 240px | Major section exits and separation from closing material. | fixed |
| 119px | Top inset of secondary-page title regions. | calc(86.6px + 2.25vw) |

### Containers and grids

- **editorial container**: max width 1376px · side padding 32px. Desktop content spans almost the entire viewport, leaving narrow, constant-looking edges.
- **master grid**: 12 columns · gap 12px. The common alignment system for headings, project rows, contact details and utility lists.
- **proof spread**: 12 columns · gap 12px. Three-column text rail on the left, one column of breathing room, eight-column landscape visual at right; the rail is 335px and the image 913px wide at desktop.
- **editorial trio**: 3 columns · gap 12px. Three 451px-wide image-led editorial cards.
- **media container**: gap 12px · side padding 12px. Near-bleed case-study imagery, with occasional complete edge-to-edge images.
- **portrait wall** (only for company and people pages): 4 columns · gap 12px. Four 335px-wide portrait cards with 418px-tall images and plain captions beneath.

## Corner radius

| Element | Radius |
| --- | --- |
| small pills | 64px |
| chapter and external capsules | 54px |
| ordinary media | 0px |

## Surfaces and depth

### Surfaces

#### Editorial canvas · level 0

**Use:** Default reading field.

**CSS:** `background: #ffffff; color: #181f1f`

**Observed:** The canvas carries hairlines and open space rather than boxed sections.

**Transfer:** Let photography and artwork provide most color; keep the surrounding editorial structure plain.

#### Mint glass · level 1

**Use:** Floating navigation and secondary controls.

**CSS:** `background: rgba(220, 242, 235, 0.6); backdrop-filter: blur(40px); border-radius: 64px; box-shadow: none`

**Observed:** A soft translucent lozenge remains legible above a colorful scene without becoming a glass dashboard.

**Transfer:** Keep the treatment confined to small controls.

#### Ruled editorial field · level 0

**Use:** Project spreads, contact sections and footer divisions.

**CSS:** `border-top: 1px solid rgba(24, 31, 31, 0.2); padding-top: 16px`

**Observed:** Only the top boundary is drawn; the content is not enclosed.

**Transfer:** Use one quiet separator to establish a new editorial beat.

#### Transition color field

**Use:** Full-screen color passage between visual states.

**CSS:** `background-image: linear-gradient(0deg, rgba(255, 194, 64, 0), #ffc240, #ffc4f4, #96ebeb, rgba(150, 235, 235, 0))`

**Observed:** An expansive vertical blend with transparent ends; it is separate from the image-rich cinematic opening.

**Transfer:** Use as a transition accent rather than as the permanent background of every block.

#### Cool explanatory canvas · level 0

**Only for:** method and company pages

**Use:** A subtly tinted opening for a text-led explanation.

**CSS:** `background: #f7fcfa; color: #181f1f`

**Observed:** A nearly white cool ground gives way to image and colored editorial chapters.

**Transfer:** Keep the tint extremely light; do not make every section mint.

## Components

### Navigation pill

**Use:** Primary navigation and secondary actions.

**CSS:** `background: rgba(220, 242, 235, 0.6); color: #000000; border-radius: 64px; padding: 12px 16px; height: 40px; backdrop-filter: blur(40px)`

**Text style:** `action` — Grit 400 · 16px/1

**Observed:** Navigation forms a left cluster and a separate pair at the far right. In the opening the current item has solid mint; in the persistent header current navigation is dark.

**States:** Declared: hover background-color #96ebeb and color #181f1f; focus-visible unknown.

**Transfer:** Use short editorial destination names rather than a row of verbose calls to action.

### Dark pill

**Use:** Selected filters, social links and compact conversion links.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #181f1f; color: #ffffff; border-radius: 64px; padding: 12px 16px; height: 40px; backdrop-filter: blur(40px)`

**Text style:** `action` — Grit 400 · 16px/1

**Observed:** A solid counterpart to Navigation pill; social actions are grouped at the opposite edge from the recruitment action. Larger editorial calls retain the same serif, lozenge vocabulary.

**States:** Declared: hover background-color #96ebeb and color #181f1f; focus-visible unknown.

### Text link

**Use:** Footer destinations and low-emphasis editorial navigation.

**CSS:** `color: #181f1f; text-decoration-line: underline`

**Text style:** `caption` — Grit 400 · 16px/1.2

**Observed:** Plain serif text without a container. Footer destinations form short vertical lists rather than a dense multi-column sitemap.

**States:** Declared: hover text-decoration-color rgba(24,31,31,0.4); focus-visible unknown.

### Copy utility

**Use:** Copying an email, telephone number or address.

**CSS:** `color: rgba(24, 31, 31, 0.4); background: transparent; line-height: 24px`

**Text style:** `copy-utility` — ABCDiatypeExpanded 700 · 12px/2

**Observed:** Small unboxed sans control aligns at the right of the detail column, not against the page edge.

**States:** Declared: hover color #181f1f; focus-visible unknown.

### Proof spread

**Use:** Image-led evidence or featured customer story.

**CSS:** `display: block; border-top: 1px solid rgba(24, 31, 31, 0.2); padding-top: 16px`

**Text style:** `project-title` — ABCDiatypeExpanded 700 · 40px/1.2 · tracking -0.01em

**Observed:** The whole spread is a link. The title sits at the top of a narrow left rail; a compact sans claim and Stat proof sit near its bottom. The wide right image is a separate visual world, not a background behind the text.

**Transfer:** Use one capability, customer or outcome per spread, with the product doing something visibly distinctive.

### Stat proof

**Use:** A short result inside the text rail of a Proof spread.

**CSS:** `color: #181f1f`

**Text style:** `label-strong` — ABCDiatypeExpanded 700 · 20px/1.2

**Observed:** A tiny dark oval with a white plus or upward arrow precedes the compact value. A plain serif explanation underneath supplies timeframe and meaning; the value is not enlarged beyond the surrounding labels.

**Transfer:** Keep the proof small and accountable; pair every number with its context.

### Editorial card

**Use:** Updates, articles and opportunities.

**CSS:** `display: flex; flex-direction: column; overflow: hidden`

**Text style:** `card-title` — ABCDiatypeExpanded 700 · 20px/1.2 · tracking -0.01em

**Observed:** A square image sits above a pale mint panel. The panel uses centered category, title and serif attribution, with text insets of 24px vertically and 64px horizontally. An external destination receives a tiny capsule at the upper right of the text panel. The bottom edge can flare outward in the signature sheet-like curve.

**Transfer:** Mix genuinely different image subjects while preserving equal framing and the category-title-attribution hierarchy.

### External capsule

**Use:** External destinations within Editorial card.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 36px; height: 24px; background: #1f3233; border-radius: 54px; backdrop-filter: blur(40px)`

**Observed:** A white 12px external-link arrow is centered inside the small dark oval.

**Transfer:** Use only for destination metadata, not as a decorative badge on every card.

### Contact row

**Use:** The practical detail layer beneath the closing question.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); column-gap: 12px`

**Text style:** `body` — Grit 400 · 20px/1.2

**Observed:** A bold sans label spans two columns, a serif detail spans three, and Copy utility sits in the following column. Rows are separated by 32px; address details can wrap. The right-hand portion of the section stays available for a warm workplace image.

**Transfer:** Replace agency contacts with equivalent sales, support or location details, retaining the deliberately useful directory-like structure.

### Chapter control

**Only for:** long-form case studies

**Use:** Persistent navigation within a very long visual story.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: rgba(220, 242, 235, 0.6); color: #181f1f; border-radius: 54px; padding: 10px 10px 10px 16px; height: 40px; backdrop-filter: blur(40px)`

**Text style:** `action` — Grit 400 · 16px/1

**Observed:** Anchored near the lower left with a small plus inside a lighter oval at the right. Expanded destinations form a short vertical list above it.

**States:** Declared: hover background-color #ebf7f3 and color #181f1f; focus-visible unknown.

## Imagery and graphics

### Radial light world

**Use:** The immersive opening identity stage.

**Observed:** A full-screen abstract field converges near the middle: cyan light surges horizontally and downward through dark teal shadows, while ochre and brown rays sweep across the upper field. Blurred, streaked folds suggest rapid movement through a landscape; white identity artwork remains crisp in front.

**Transfer:** Make an original atmosphere that suggests the product's ambition. A still radial-light composition is the minimum acceptable alternative to a rendered film; it must retain depth and directional tension.

**Build:** Place a dark teal base beneath an oversized conic-gradient centered at 50% 50%. Alternate translucent cyan wedges with near-black teal wedges, add broad amber-brown wedges across the upper half, then blur by roughly 24px. Stretch several translucent cyan ellipses horizontally through the center and apply an SVG turbulence displacement to bend the rays into folds. Keep the top and corners darker and put the sharp white word treatment above all blur.

### Sheet-like media edge

**Use:** Signature distortion on selected images, cards and visual transitions.

**Observed:** Most framing is square, but selected edges bow inward along the side and flare outward at the bottom, as though a flexible rectangular sheet is being tugged. The effect appears in both large visual spreads and small editorial panels, rather than as conventional rounded corners.

**Transfer:** Carry this edge behavior into at least one prominent media field or editorial panel. Keep the interior image readable and flat enough to remain a piece of communication.

**Build:** Use an SVG clipPath or displacement mesh on a rectangle. Keep the upper edge straight; draw each side nearly vertical for most of its height, then use a broad cubic curve over the final approximately 80px to flare toward the outer edge. For moving images, distort only the edge strip rather than rippling text across the entire image.

### Art-directed proof landscape

**Use:** Main visual in proof spreads and full-width case-study chapters.

**Observed:** The visual occupies much more area than its caption: 913px × 514px in a spread or 1416px × 797px near bleed. Photography, product interfaces, identity graphics, packaging and motion stills are treated as finished compositions with their own palettes. Everyday people, objects and rooms give digital work a physical life.

**Transfer:** Show the product in a credible world, not a generic browser mockup repeated on a neutral gradient. Without a campaign library, create one strong product scene with deliberate light, tactile backing and a legible focal object.

### Closing workplace scene

**Use:** Human counterweight to the final conversion prompt.

**Observed:** A right-aligned, roughly one-third-width scene shows the material life of a studio: warm daylight, hands, drinks, timber, brick and windows. It is intimate rather than a glossy corporate panorama.

**Transfer:** Use a real place where the product is made or used, with warm light and a tightly framed detail. Pair it with useful contact information rather than promotional copy.

### Case-study visual sequences

**Only for:** long-form case studies

**Use:** A visual argument between short explanatory passages.

**Observed:** Wide landscapes alternate with centered pairs of 451px × 563px portraits, half-width 702px × 878px panels and occasional full-bleed fields. One story uses strong green identity graphics and naturally lit payment scenes; another uses grainy paper, cut-and-paste landscapes, warm wood desks, human faces and screen content. These are project-specific worlds, not new site-wide fonts or colors.

**Transfer:** Keep each case's own visual language intact while the surrounding caption grid stays consistent. Switch scale to create pacing, not random masonry.

### Metaphorical object triptych

**Only for:** method and company pages

**Use:** Three visual ideas attached to an explanatory chapter.

**Observed:** Tall atmospheric scenes show a glowing mushroom, a turquoise sculptural spinning form and a sunlit mountain. Each is a single centered subject in a lush or hazy environment, framed as an equal-width vertical image with curved lower edges.

**Transfer:** Use three original physical metaphors for the new product's principles; a carefully lit still life is sufficient. Preserve the single-subject focus and rich environmental light, not the original objects.

**Build:** Make three 451px-wide portrait scenes with one object occupying most of each frame. Use a dark forest-green field with tiny light flecks, a warm backlit natural surface, and a pale hazy landscape as distinct lighting structures. Apply the sheet-like edge only at their lower corners.

### Human portrait wall

**Only for:** company and people pages

**Use:** A substantial team directory.

**Observed:** Four columns of chest-up studio portraits share consistent scale but alternate teal, ochre and coral backdrops. Warm directional lighting and unforced poses replace corporate white-background headshots. Small serif names and roles sit directly below each image.

**Transfer:** Use real people, a consistent camera distance and a limited set of colored studio grounds. Preserve individuality without changing the grid for each person.

### Icons

**Observed:** Small functional glyphs only: a 12px white external arrow in a dark oval, a 10px dark plus in the chapter control, and compact white plus/up-arrow markers beside proof values.

**Transfer:** Choose simple filled utility marks, not a feature-icon library. Keep them subordinate to text and use pills only where they communicate a destination or control.

## Section recipes

How recurring sections are built.

### First screen: Cinematic identity opening

**Observed:** The first 900px is a single immersive 1440px × 900px stage. Radial light world fills the back layer; a sharp white, horizontally flattened wordmark spans the width inside 32px margins and is centered around the visual horizon, with a 1376px × 62px silhouette. Navigation pill controls sit along the bottom with a left destination cluster and a right action pair, about 32px from the edges. There is no supporting paragraph or central sales-button stack on this screen. The actual display statement and serif support sit below the fold, after a long white pause.

**Transfer:** For a new landing page, create an original full-width identity or short word sculpture against the same deep, directional light and preserve the bottom navigation. If no film exists, build the still atmosphere described in Radial light world. Text-led index and method pages instead open under a compact top identity/header with a left-aligned 78px heading and generous space below; case studies add a small project label above a longer outcome-led title.

**Avoid:** Do not replace the opening with a conventional two-column SaaS hero, a floating app screenshot, a generic gradient blob or a headline-and-two-buttons stack. Do not confuse the wide vector wordmark with a normal text heading.

**Text style:** `display` — ABCDiatypeExpanded 700 · 82px/1.1 · tracking -0.02em

### Editorial manifesto

**Observed:** A broad sans statement is followed by a 56px serif paragraph with a 48px gap, spanning nearly the full content width. The composition is left aligned and surrounded by much more space than a normal paragraph block.

**Transfer:** Write a concise point of view and one substantial supporting thought. Keep the serif visually important instead of shrinking it to a conventional subtitle.

**Text style:** `manifesto` — Grit 400 · 56px/1.2

### Image and outcome spread

**Observed:** Proof spread pairs a top-aligned project name with a lower-left claim and Stat proof, beside a wide landscape image. Repeated spreads have approximately 180px pauses and a fine top rule.

**Transfer:** Use this as a repeatable evidence chapter for a different product: a use case, artifact and accountable result in each spread.

**Text style:** `project-title` — ABCDiatypeExpanded 700 · 40px/1.2 · tracking -0.01em

### Editorial trio

**Observed:** A ruled heading pair introduces three Editorial card components separated by 12px. Square images dominate the upper portion, with pale text panels underneath; a centered dark editorial action follows after generous white space.

**Transfer:** Use articles, resources or product stories that add a second kind of evidence after the main demonstration. Keep categories and attributions short.

**Text style:** `card-title` — ABCDiatypeExpanded 700 · 20px/1.2 · tracking -0.01em

### Newsletter invitation

**Observed:** A fine rule leads into a full-width broad sans invitation, then a simple outlined email lozenge beside a dark serif Sign up action. Tiny explanatory copy stays directly below the field. The whole area remains white and open rather than a filled promotional banner.

**Transfer:** Make the invitation sound editorial, not like an interruption. Retain the single-field form and leave breathing room before the contact section.

**Text style:** `heading` — ABCDiatypeExpanded 700 · 78px/1.15 · tracking -0.01em

### Monumental useful ending

**Observed:** A ruled section opens with a 78px closing question at left and Closing workplace scene at right. The left side then becomes Contact row entries with a long pause between the question and details. A small credibility mark sits beneath the image. Another rule separates a left recruitment pill from right social pills; the final footer is a separate ruled area with two narrow serif link columns and a small copyright line low at left. This structure ends every page type.

**Transfer:** End with a strong short question, then make the next step practical: real contact or support details, useful links and an original human scene. Preserve the hierarchy and openness even when the product's conversion is self-serve.

**Text style:** `heading` — ABCDiatypeExpanded 700 · 78px/1.15 · tracking -0.01em

### Ruled chapter and caption

**Only for:** case studies and explanatory pages

**Observed:** Long-form chapters use a small sans label on the left and a larger reading column offset to the right. A rule extends across the container. Short labels and serif captions introduce the imagery beneath; the image is not overlaid with the explanatory text.

**Transfer:** Separate the label's navigational job from the prose's explanatory job. Use a wider reading column for chapter narratives and a narrower one for image captions.

**Text style:** `body` — Grit 400 · 20px/1.2

### Testimonial and recognition field

**Only for:** deep proof and case-study pages

**Observed:** A large serif quotation occupies the central reading column, with oversized quote marks positioned at the far left and right. Attribution sits below in the same serif. Case-specific saturated color can fill this proof field. Recognition lists use a left-side label and a right-side ruled ledger of title, detail and year rather than a logo cloud.

**Transfer:** Use a credible quotation with a named role. If recognition matters, present it as a factual ledger; keep the bright field specific to this proof chapter.

### Numbered explanation

**Only for:** method and company pages

**Observed:** A colored explanatory field contains small left-aligned sequence numbers, broad sans chapter titles and serif paragraphs offset into a shared reading column. Long vertical spaces separate the ideas.

**Transfer:** Use the pattern for a product's method or stages of use, not a feature-card grid. The number serves orientation rather than decoration.

## Page flow

**Storyline:** immersive identity or bold promise → editorial point of view → richly visual demonstration → accountable proof → continuing relationship → useful closing invitation

### Brand-led marketing landing page

1. **Identity** — Full-screen atmospheric identity stage and bottom-edge navigation.
2. **Promise** — Broad sans statement and large serif manifesto on white.
3. **Demonstration and proof** — Repeated editorial spreads pair vivid work with a compact claim and result.
4. **Continuing relationship** — Editorial card trio, collection link and newsletter invitation.
5. **Closing call** — Monumental question, contacts, workplace image, social pills and sparse footer.

**Transfer:** Use the visual worlds to establish difference, then make the case in a plain, accountable editorial rail.

### Detailed transformation story with an expansive identity system

1. **Outcome promise** — Small project name above a long, broad-sans outcome title and major visual.
2. **Context** — Large serif introduction, overview and compact results.
3. **Capability chapters** — Ruled strategy, creation and delivery passages alternate with large visual systems and physical-use scenes.
4. **Credibility** — Outcomes, attributed quotations and a ruled recognition ledger in project-colored fields.
5. **Closing call** — Collection return, newsletter, contact question and shared footer.

**Transfer:** Show the system working at many scales without importing its project palette into the default interface.

### Detailed product and campaign transformation story

1. **Outcome promise** — Long outcome-led title on white above a product demonstration.
2. **Context and proof** — Large serif account of the problem followed by overview and result markers.
3. **Capability chapters** — Short ruled explanations introduce identity, voice, illustration, digital and real-world applications; white and dark project worlds alternate.
4. **Results and endorsement** — Accountable outcome narrative followed by a bright testimonial and an acknowledgements row.
5. **Closing call** — Short paired closing caption, collection link, newsletter and shared contact/footer ending.

**Transfer:** Explain a product's character through artifacts, behavior and people rather than a catalogue of UI features.

### Browsable collection of proof stories

1. **Promise** — Left-aligned broad headline under the compact identity header.
2. **Orientation** — Two small pills distinguish featured from everything.
3. **Proof collection** — Long sequence of ruled project-and-result spreads.
4. **Continuation** — Centered collection action and newsletter.
5. **Closing call** — Shared question, directory-like contact section and footer.

**Transfer:** Let the image-led spreads do the selection work; keep filters deliberately minimal.

### Method, company and people explanation

1. **Point of view** — Broad title and large serif argument on a pale cool ground.
2. **Principles** — Atmospheric object triptych followed by a spacious numbered method on a colored field.
3. **Human credibility** — Large serif introduction and four-column portrait directory.
4. **Recognition** — A witty broad headline above a long ruled ledger on a colored field.
5. **Closing call** — Newsletter, useful contact question and the same sparse footer.

**Transfer:** Use physical metaphors and people for credibility while retaining the same editorial grid as product proof.

## Writing

Conviction without jargon: expansive in ambition, direct in syntax and grounded by specific outcomes. Warmth comes through a literary cadence, mild wit and human detail rather than hype.

**Do not copy:** Do not reuse the Ragged Edge wordmark, project identities, campaign artwork, proprietary phrases, client claims, results, valuations, testimonials, contact information or certification marks. Examples illustrate structure and tone only; substitute original product facts and authorized assets.

- **Addressing the reader:** Use we for the maker's point of view and you when inviting commitment. Case stories name the subject directly and use third person for outcomes.
- **Rhythm:** Short, decisive headlines sit beside longer flowing serif paragraphs. Sentence fragments are welcome for emphasis; an outcome can follow a full stop with a second sentence beginning With. Actions are compact destination names or conversational invitations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Point-of-view headline | A short irreversible change, not a feature description. | 4–8 words | “Never be the same again”<br>“It’s time to commit to a different reality” |
| Outcome-led title | Subject committed to a larger ambition. With a concrete intervention and outcome. | 15–25 words | “Wise committed to the world’s money. With a rebrand rolled out in 175 countries.” |
| Supporting manifesto | Define who the company is for, reject an unhelpful norm and invite a different future. | One substantial paragraph | “[Brand] is a brand company for people who refuse to settle for average. It’s time to commit to a different reality.” |
| Result caption | Plain explanation that anchors the number to a period or event. | 6–12 words | “Valuation within three months of the rebrand.” |
| Closing call | A brief question that asks for intent rather than pushing a transaction. | 3–5 words | “Time to commit?” |
| Action | Short familiar verb or destination, with occasional conversational collection links. | 1–4 words | “Join”<br>“All partnerships”<br>“Sign up” |

**Words and phrasing to use:** commit; different; real; possibility; progress; together; direct verbs; concrete timeframes

**Avoid:** seamless solutions; unlock potential; revolutionary platform; best-in-class without proof; feature-list jargon; excessive exclamation marks

**Rules:**

- Make the ambition bigger than a feature, then make the proof more specific than the ambition.
- Use contrast to sharpen an argument: average versus different, appearance versus real-world effect.
- Name the practical change and its timeframe instead of stacking superlatives.
- Keep small labels in sentence case; the voice is not uppercase shouting.
- Let the closing question carry the emotion and the contact details carry the action.

## Do's and Don'ts

### Do

- Preserve the 32px desktop margins and 12px grid gutters across unrelated section types.
- Give the serif real scale: 56px/1.2 for the central manifesto, not a tiny subtitle.
- Use 40px-high, 64px-radius controls with 16px serif labels for compact actions.
- Keep a proof image about eight columns wide against a three-column text rail.
- Make at least one media edge behave like a flexible sheet instead of applying ordinary corner rounding everywhere.
- Use 1px ink-at-20% top rules to divide editorial beats.
- Keep the closing question at the same 78px scale as major page titles.
- Separate short media gaps of 12px from chapter pauses of 120px or 180px.

### Don't

- Do not replace the expanded bold heading family with a narrow or regular-width grotesk.
- Do not put the 20px result values into giant dashboard-style KPI cards.
- Do not apply drop shadows to the editorial spreads; there are no raised card shadows.
- Do not turn all media into 16px-radius rounded rectangles; the default is square framing with selected sheet-like distortion.
- Do not spread cyan, pink and amber across every section as equal interface colors.
- Do not move every control into a large dark navigation bar; the small independent lozenges must remain visible as separate objects.
- Do not reduce serif text to legal copy while making all meaningful copy sans.
- Do not fill the footer with many equal-width columns; the small link lists occupy only the left portion.

## Motion and responsive

### Motion

**Observed:**

- Pill colors transition over 0.3s with cubic-bezier(0.4,0,0.2,1). Text-link and Copy utility color changes use 0.15s with the same easing.
- The fixed header declares transform transitions of 0.3s; the chapter-control container declares 0.5s transform transitions.
- Selected visual edges visibly bend and flare; large image and color fields change through the long editorial journey.

**Transfer:**

- Keep controls quick and restrained; the visual scene, not button choreography, carries the expressive motion.
- A still opening must preserve the radial depth and sharp identity layer. Keep utility text stable while any media edge distorts.

**Unknown:**

- Precise rendering algorithm, timing and easing of the cinematic scene and media-edge distortion.
- Exact scroll thresholds and complete sticky-header behavior.
- Focus-visible and pressed appearances are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 420px, 479px, 480px, 639px, 768px, 769px, 900px, 1200px, 1280px, 1400px, 1800px and 2300px.
- The opening has a shorter small-screen height expression and desktop full-screen framing; the desktop bottom navigation is hidden below the medium layout.
- Project-row markup places imagery before text at smaller widths; editorial cards also declare an intermediate image-and-text two-column mode.

**Transfer:**

- On narrow screens, retain the identity horizon and atmosphere but shorten the stage rather than shrinking the wordmark into an ordinary logo.
- Stack proof imagery above its editorial rail, preserving the title-claim-result hierarchy and fine rules.
- Reduce portrait-wall and editorial-card columns while keeping consistent image aspect ratios and plain captions.

**Unknown:**

- Exact mobile font sizes, margins, menu construction and settled mobile layouts are not established.
- No measured fluid type formulas are available; desktop type sizes should not be converted into invented viewport formulas.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
