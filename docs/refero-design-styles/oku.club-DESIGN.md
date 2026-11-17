# Oku — ink and companionship

## Overview

A light, bookish product style with a playful human streak: regular editorial serifs sit beside an unassuming sans serif, on white and pale gray. Black pencil-like illustrations give personality to an otherwise restrained presentation of crisp interfaces and devices. It suits approachable tools, member-supported services and products that want to feel made by people, with spacious storytelling rather than dense sales machinery.

### Essentials

- Editorial headlines stay modest rather than monumental: FabricSerifWeb at 48px/1.3, weight 400, -0.006em tracking; feature-card headings step down to 36px/1.3 with the same tracking.
- The opening is a sideways storybook scene: a two-line, 460px-wide promise at the left and a roughly 758px square monochrome illustration on the right, inside a 1360px container with 48px side padding.
- Actions are little black rectangles, not pills: 8px corners, 54px height for conversion actions and 40px for navigation and plans, with white Inter at weight 500.
- The marketing shell is almost entirely white, #f3f4f4 feature panels and a #f6f6f6 closing band; stronger color lives inside product media. Sage and mauve washes belong to the pricing variant, not the default landing page.
- Product proof is physically staged: large browser windows and black-framed phones overlap, emerge from the edges of 8px-radius pale panels and are clipped at their bottoms; alternate full-width stages with paired 620px panels.
- Hand-drawn ink returns at the ending: a shallow 120px curved transition leads into an illustrated closing invitation with floating small objects and a character at the lower right. Carry this device into every new landing page using original textured line drawings; simple SVG line-and-hatch objects are the minimum fallback.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, surface, text | Default page, interface frames, secondary actions and inverted button text. Navigation uses white at 0.635 alpha over this canvas. |
| Closing gray | `#f6f6f6` | `--color-closing` | background | The illustrated closing invitation and utility footer. |
| Feature gray | `#f3f4f4` | `--color-panel` | surface, background | Broad feature stages and paired panels; secondary-button hover fill. |
| Hairline gray | `#e8e8e9` | `--color-edge` | border | Testimonials, separators and the closing utility divider. |
| Paragraph gray | `#46474e` | `--color-body` | text | Support paragraphs and small descriptive text. |
| Soft text ink | `#131314` | `--color-text` | text, link | Navigation, small headings, plan descriptions and prices. |
| Printed black | `#000000` | `--color-black` | text, action | Serif headings, primary action fills and monochrome drawing. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| social proof cards | Social slate | `#697882` | `--color-metadata` | text | Attribution handles and timestamps in social proof cards. |
| pricing pages | Inactive gray | `#8c8c90` | `--color-inactive` | text | Unselected billing-period label. |
| pricing pages | Sage wash | `#ecf2eb` | `--color-sage-wash` | surface | The middle paid-plan card. |
| pricing pages | Mauve wash | `#f7f1f4` | `--color-mauve-wash` | surface | The higher-support plan card. |
| pricing pages | Sage label | `#6f9965` | `--color-sage` | accent, surface, text | Small tier label, corner savings ribbon and billing savings note. |
| pricing pages | Mauve label | `#bf90ac` | `--color-mauve` | accent, surface | Higher-support tier label and diagonal savings ribbon. |
| pricing promotions | Cream offer | `#fefaee` | `--color-offer` | surface | Small, centered promotion box above the billing control. |

## Typography

- **FabricSerifWeb** — Headlines and pricing numerals; sentence-case editorial hierarchy. Regular, softly bracketed serif with a literary, slightly old-fashioned warmth. If unavailable, use **Libre Baskerville**. Use weight 400; tune line breaks to preserve the compact two-line headline silhouette. Font stack: "FabricSerifWeb", "Libre Baskerville", Georgia, Cambria, "Times New Roman", Times, serif.
- **Inter** — Body copy, navigation, actions, names and utility labels. Neutral grotesk, mostly regular with medium-weight action labels. Font stack: "Inter", -apple-system, system-ui, "Segoe UI", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | FabricSerifWeb | 400 | 48px | 1.3 | -0.006em | Opening promise, major editorial sections and closing invitation. |
| feature-heading | FabricSerifWeb | 400 | 36px | 1.3 | -0.006em | Centered headings in broad and paired feature stages. |
| body-lead | Inter | 400 | 17px | 1.8 | normal | Editorial support, trust explanations and closing support. |
| body | Inter | 400 | 16px | 1.8 | normal | Feature captions and objection-handling paragraphs. |
| small-heading | Inter | 500 | 16px | 1.3 | normal | Compact question labels and their answer headings. |
| navigation | Inter | 400 | 16px | 1.5 | normal | Header navigation links. |
| action | Inter | 500 | 15px | 54px | normal | Text vertically centered in 54px conversion buttons. |
| person-name | Inter | 500 | 15px | 1.8 | normal | Names below circular illustrated portraits. |
| action-compact | Inter | 500 | 14px | 40px | normal | Header and plan actions. |
| helper | Inter | 400 | 13px | 1.5 | normal | Returning-member line beneath opening actions. |
| caption | Inter | 400 | 13px | 1.8 | normal | Location captions and closing copyright. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing feature chapters | feature-heading-editorial | FabricSerifWeb | 400 | 48px | 1.2 | -0.006em | Left- or right-aligned headings beside oversized interface media. |
| pricing pages | price | FabricSerifWeb | 400 | 39px | 1 | normal | Plan price as a large editorial number, with smaller period information alongside. |
| pricing pages | billing-label | FabricSerifWeb | 400 | 16px | 1.8 | normal | Labels flanking the black billing switch. |
| social proof cards | quote | Inter | 400 | 15px | 1.375 | normal | Compact, authentic social-proof text. |
| pricing promotions | offer-copy | Inter | 400 | 15px | 1.8 | normal | Short promotion text with the deal emphasized in bold. |
| pricing pages | plan-body | Inter | 400 | 14px | 1.8 | normal | Plan descriptions and feature lists. |
| pricing pages | tier-label | Inter | 700 | 9px | 0.8 | 0.07em, uppercase | Tiny white lettering inside colored paid-tier badges. |

**Notes:**

- The same 48px serif recipe handles both the first promise and the final invitation; hierarchy comes from context and whitespace, not exaggerated size.
- Serif headline tracking is consistently -0.006em. Sans text uses normal tracking except the tiny uppercase tier badges.
- Paragraphs are unusually open at 1.8 line height; quotes compress to 1.375. Keep interface media distinct from the marketing type scale.
- Use sentence case, with deliberate short multi-line headings rather than uppercase display copy.

## Layout

**Density:** Airy: large narrative pauses surround closely grouped feature stages and small, practical controls.

### Spacing

**Spacing system:**

- **grid** 8px — Primary rhythm for padding, margins and grid gaps; small optical corrections exist outside this grid.

| Value | Use |
| --- | --- |
| 8px | Small heading-to-answer gaps and badge spacing. |
| 16px | Feature support spacing, action-row gaps and plan-grid gutters. |
| 24px | Editorial heading-to-paragraph gap and navigation side padding. |
| 32px | Headline-to-action gap, body-to-closing-action gap and editorial side padding. |
| 40px | Plan-card inner padding. |
| 48px | Wide-container side padding and paragraph-to-portrait gap. |
| 64px | Feature heading inset, media separation and compact editorial-row separation. |
| 120px | Large pauses between trust sections and below the people section. |
| 128px | Separation after the feature-panel sequence. |
| 190px | Closing invitation top and bottom padding. |

### Containers and grids

- **wide-stage**: max width 1360px · side padding 48px. Centered opening and feature canvas; at 1440px this yields a 1264px painted content width and 88px outer inset.
- **feature-pair**: 2 columns · gap 24px. Two equal, approximately 620px-wide panels. Keep the pair compact and vary whether the device enters from above or below.
- **editorial**: max width 912px · side padding 32px. Trust, people and alternating feature narratives; media can extend outside this text container.
- **centered-prose**: max width 720px. Centered editorial explanations and people-section introductions.
- **closing-content**: max width 1136px · side padding 32px. Centered invitation with a 500px support paragraph and a hairline above the utility row.
- **plan-grid** (only for pricing pages): max width 1196px · 3 columns · gap 16px · side padding 16px. Three top-aligned plan cards about 377px wide; cards retain their content-dependent heights.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-panels | 8px |
|  | portraits | 50% |
| pricing pages | tier-badges | 4px |
| pricing pages | billing-switch | 27px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| action-lift | `rgba(0, 0, 0, 0.25) 0px 4px 4px -5px` | Almost imperceptible depth under black buttons. |
| secondary-edge | `rgba(19, 19, 20, 0.22) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.25) 0px 4px 4px -5px` | White secondary actions. |
| portrait-ring | `rgba(83, 84, 94, 0.1) 0px 0px 0px 1px` | Subtle circular portrait edge. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff`

**Observed:** Clear white space separates broad pale stages from small prose sections.

**Transfer:** Keep the page shell neutral and let product media carry detail.

#### Feature stage · level 1

**Use:** Broad product demonstrations and paired capability cards.

**CSS:** `background: #f3f4f4; border-radius: 8px; overflow: hidden`

**Observed:** Flat, borderless pale panels clip the lower edge of large devices and browser windows.

**Transfer:** Use a single product task per stage; retain generous internal blank space around the meaningful UI.

#### Header glass · level 2

**Use:** Fixed navigation over the scrolling content.

**CSS:** `background: rgba(255, 255, 255, 0.635); backdrop-filter: blur(6.6px); box-shadow: rgba(0, 0, 0, 0.067) 0px 0.7px 0px 0px`

**Observed:** Looks nearly white at the top, becoming softly translucent over later media.

**Transfer:** Keep this effect confined to navigation; do not turn feature cards into glass.

#### Illustrated closing band · level 0

**Use:** Final conversion and utility navigation.

**CSS:** `background: #f6f6f6; position: relative; overflow: hidden`

**Observed:** A shallow white concave sweep caps the gray field; small ink objects drift near its edges.

**Transfer:** Preserve the curved transition and peripheral ink artwork, adapting the objects to the new product.

#### Paid plan washes · level 1

**Only for:** pricing pages

**Use:** Differentiate paid tiers without loud promotional fills.

**CSS:** `background: #ecf2eb; border-radius: 8px; padding: 40px; overflow: hidden`

**Observed:** The middle plan uses sage; the higher tier uses #f7f1f4, with correspondingly colored badges and ribbons.

**Transfer:** Use these subdued variations only for tier differentiation.

#### Promotion note · level 1

**Only for:** pricing promotions

**Use:** Time-limited offer above the plan chooser.

**CSS:** `background: #fefaee; border-radius: 8px; padding: 16px; max-width: 420px`

**Observed:** Small centered cream box, two lines of text and a bold deal phrase.

**Transfer:** Keep urgency visually softer than the primary action.

## Components

### Fixed navigation

**Use:** Persistent orientation and account actions.

**CSS:** `position: fixed; height: 80px; width: 100%; background: rgba(255, 255, 255, 0.635); backdrop-filter: blur(6.6px); box-shadow: rgba(0, 0, 0, 0.067) 0px 0.7px 0px 0px; display: flex; align-items: center`

**Text style:** `navigation` — Inter 400 · 16px/1.5

**Observed:** Small black symbol-plus-wordmark at left, a centered row of five plain links, then white sign-in and black join actions at right. Inner row has 24px side padding; link items have 16px side margins.

**Transfer:** Use concise navigation labels and preserve the three-part balance.

### Primary button

**Use:** Opening and closing conversion.

**CSS:** `background: #000000; color: #ffffff; height: 54px; padding: 0px 24px; border-radius: 8px; box-shadow: rgba(0, 0, 0, 0.25) 0px 4px 4px -5px; text-align: center`

**Text style:** `action` — Inter 500 · 15px/54px

**Observed:** Text-only rectangle. The opening places an official platform-download badge beside it with a 16px gap; the closing version expands horizontal padding to 48px.

**States:** Declared: hover box-shadow rgba(0, 0, 0, 0.35) 0px 6px 6px -5px and transform translate3d(0px, -1px, 0px); focus-visible unspecified; active transform translate3d(0px, 0px, 0px).

### Compact primary button

**Use:** Header conversion and plan selection.

**CSS:** `background: #000000; color: #ffffff; height: 40px; padding: 0px 24px; border-radius: 8px; box-shadow: rgba(0, 0, 0, 0.25) 0px 4px 4px -5px; text-align: center`

**Text style:** `action-compact` — Inter 500 · 14px/40px

**Observed:** Header action is 112px wide; plan actions span their card's inner width. All plans receive the same black action treatment.

**States:** Declared: hover box-shadow rgba(0, 0, 0, 0.35) 0px 6px 6px -5px and transform translate3d(0px, -1px, 0px); focus-visible unspecified; active transform translate3d(0px, 0px, 0px).

### Secondary button

**Use:** Returning-user action in the header.

**CSS:** `background: #ffffff; color: #131314; height: 40px; padding: 0px 24px; border-radius: 8px; box-shadow: rgba(19, 19, 20, 0.22) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.25) 0px 4px 4px -5px`

**Text style:** `action-compact` — Inter 500 · 14px/40px

**Observed:** Pairs with the compact primary action, with a 16px gap and equal width.

**States:** Declared: hover background-color #f3f4f4, color #131314, inset edge rgba(19, 19, 20, 0.45), transform translate3d(0px, -1px, 0px); focus-visible unspecified; active transform translate3d(0px, 0px, 0px).

### Navigation link

**Use:** Unboxed header navigation.

**CSS:** `color: #131314; font-size: 16px; line-height: 24px`

**Text style:** `navigation` — Inter 400 · 16px/1.5

**Observed:** Plain text without an icon or permanent underline. The current pricing link has a dark lower underline.

**States:** Declared: hover color #000000 and transform translate3d(0px, -1px, 0px); focus-visible unspecified; active transform translate3d(0px, 0px, 0px).

### Feature panel

**Use:** Reusable capability card and media stage.

**CSS:** `background: #f3f4f4; border-radius: 8px; overflow: hidden`

**Text style:** `feature-heading` — FabricSerifWeb 400 · 36px/1.3 · tracking -0.006em

**Observed:** Centered serif title, optional support paragraph, then a large interface image. Full-width panels have 64px top inset; paired panels can reverse text and image positions.

**Transfer:** One clear outcome and one credible interface composition, not a row of generic icons.

### Social proof card

**Use:** Human recommendation beside editorial proof.

**CSS:** `background: #ffffff; border: 1px solid #e8e8e9; border-radius: 8px; width: 420px; padding: 24px`

**Text style:** `quote` — Inter 400 · 15px/1.375

**Observed:** Compact avatar and name/handle header, social mark at the top right, quote body, then subdued timestamp. Two cards are staggered horizontally and vertically rather than tiled into equal boxes.

**Transfer:** Use genuine attributable recommendations; preserve their conversational phrasing.

### Portrait identity

**Use:** A small human introduction within a centered trust section.

**CSS:** `width: 124px; height: 124px; border-radius: 50%; box-shadow: rgba(83, 84, 94, 0.1) 0px 0px 0px 1px`

**Text style:** `person-name` — Inter 500 · 15px/1.8

**Observed:** Circular black-and-white illustrated portrait above a name, then location in the caption recipe. Names sit 24px below the portrait; three 226px-wide identity columns form a centered row.

**Transfer:** Use original line-drawn people or work-life vignettes, not glossy corporate headshots.

### Plan card

**Only for:** pricing pages

**Use:** Compare membership levels.

**CSS:** `background: #f3f4f4; border-radius: 8px; padding: 40px; display: flex; flex-direction: column; justify-content: space-between; position: relative; overflow: hidden`

**Text style:** `plan-body` — Inter 400 · 14px/1.8

**Observed:** Tier name, serif price and billing detail, short description, icon-led feature list, then full-inner-width compact primary action. Neutral, sage and mauve variants are top-aligned, with unequal heights according to content. Paid cards have diagonal corner savings ribbons.

**Transfer:** List differences plainly and keep the lowest tier visually as credible as the paid options.

### Tier badge

**Only for:** pricing pages

**Use:** Compact paid-plan identity.

**CSS:** `background: #6f9965; color: #ffffff; border-radius: 4px; padding: 8px; display: flex; align-items: center`

**Text style:** `tier-label` — Inter 700 · 9px/0.8 · tracking 0.07em · uppercase

**Observed:** Small uppercase badge above the price. Higher-support version changes to mauve and adds a tiny white star.

**Transfer:** Use no more than a short tier name; keep the badge secondary to the price.

### Billing switch

**Only for:** pricing pages

**Use:** Select monthly or annual billing.

**CSS:** `background: #000000; width: 42px; height: 27px; border-radius: 27px; position: relative`

**Text style:** `billing-label` — FabricSerifWeb 400 · 16px/1.8

**Observed:** White rounded thumb inside a black track, with serif period labels 24px to either side; inactive label is #8c8c90 and the selected annual option has a small sage savings note below.

**Transfer:** Keep the selected state clear without coloring the whole control.

## Imagery and graphics

### Storybook ink scene

**Use:** The primary personality device in the opening and echoed at the close.

**Observed:** A large black-and-white drawing combines a floating person, a shelf-like object and a cat. Thin, irregular outlines mix with grainy black fills and sparse hatching, isolated directly on white without a frame or colored backdrop. The drawing occupies about the right half of the first screen and extends to the edge.

**Transfer:** Commission an original human-scale scene of a person interacting with the new product's world. Minimum version: a few expressive outline objects and a human gesture, with one textured black mass and ample unpainted paper.

**Build:** Use a transparent SVG viewBox around 758 by 758. Draw irregular 1–2px black paths with round joins; leave faces and large body areas white. Fill a few hair, fabric or object regions black and break them with thin white hatch paths and a low-opacity turbulence texture clipped to those regions. Arrange the main object toward the upper left of the drawing and a diagonal human figure toward the lower right; avoid a rectangular background.

### Device and browser proof

**Use:** Large feature stages and paired product cards.

**Observed:** White browser interfaces sit inside subtle browser chrome; black phone hardware creates a strong dark silhouette. Front-facing screens overlap, with soft hardware shadows, colorful content concentrated inside the UI and lower portions cut off by the pale stage. Broad browser compositions reach roughly 1057px wide; paired phone images use roughly 380px-wide canvases.

**Transfer:** Show actual relevant tasks in similarly light UI. When no finished interface exists, create a believable task-focused mockup rather than abstract decorative tiles; retain the black phone edge and white browser framing.

### Peripheral closing drawings

**Use:** The signature final invitation around its centered content.

**Observed:** Small black textured objects float at upper left, upper right and lower left. A larger outlined animal-like character anchors the bottom right and overlaps the utility zone. The gray field is capped by a shallow white curve.

**Transfer:** Repeat the opening's drawing language with new product-related objects and a character; keep the center clear for the invitation.

**Build:** Create a full-width SVG top cap with viewBox 0 0 1440 120: fill a path M0 0 H1440 Q720 240 0 0 with white above the gray band. Place three transparent ink-object SVGs around 92–120px wide at opposing perimeter positions, with visibly different rotations. Add a roughly 270 by 240px outlined character at bottom right, partly beyond the edge; keep all art behind the text layer.

### Illustrated people

**Use:** Human trust sections.

**Observed:** Three small circular black-and-white vignettes include people, pets and everyday activity. They share the rough ink treatment of the large drawings rather than photographic portrait lighting.

**Transfer:** Draw the actual makers or representative users in the same spare line style. Crop the scenes within circles and keep names and locations outside.

### Community activity strip

**Use:** A wide proof-of-life band between testimonials and practical reassurance.

**Observed:** A horizontal sequence of compact activity cards extends beyond both viewport edges. Each has a pale image field, a small avatar/status marker, a centered colorful content object with a soft shadow, and two compact lines of activity text below.

**Transfer:** Use real recent activity relevant to the new product. Show small tangible outputs or artifacts in the cards, rather than inventing a separate marketing illustration style.

### Alternating browser chapters

**Only for:** pricing feature chapters

**Use:** Explain paid capabilities with less panel framing.

**Observed:** Large approximately 687 by 525px browser compositions alternate left and right of a narrow text column. Media is slightly angled, with a faint edge and tiny shadow on white; thin centered horizontal dividers separate the chapters.

**Transfer:** Choose one meaningful task per chapter and preserve the asymmetry: compact copy beside media that extends past the editorial container.

### Icons

**Observed:** Plan lists use small black checks, back arrows and an occasional outline heart, positioned within 32px SVG boxes; the heart uses a 1.5px round stroke. Small marks remain secondary to text. The brand mark combines a black symbol with a wordmark.

**Transfer:** Choose restrained monochrome check and arrow forms for lists, and use an original small symbol with the new product's name. Do not turn these into large colorful feature icons.

## Section recipes

How recurring sections are built.

### First screen: Sideways storybook opening

**Observed:** A fixed 80px Fixed navigation sits above a white scene. Inside the wide-stage container, the text occupies the left half and is vertically centered against a 758px-square Storybook ink scene on the right. A 460px-wide, 48px serif headline wraps into two lines; the main illustration is appreciably taller than the whole text stack and may extend beyond the right viewport edge. Primary button and platform badge sit 32px below the heading with a 16px gap, followed by a 13px helper line after 24px. Back to front: white canvas, unframed ink illustration, headline/action stack, translucent navigation. Within the first 900px the full headline, actions, helper line and nearly all of the main scene are visible; the first product stage starts below the fold, around 966px.

**Transfer:** Replace the story with an original human-and-object scene of equal visual presence, not the original subject. If illustration resources are limited, use the SVG line-and-hatch fallback at the same scale. Pricing-oriented pages instead open with a centered 48px title, a 17px support paragraph, a small cream offer and billing control before the plan grid.

**Avoid:** Do not convert this into a centered oversized headline above a dashboard, add a colored hero gradient or crowd the large upper whitespace with badges.

**Text style:** `display` — FabricSerifWeb 400 · 48px/1.3 · tracking -0.006em

### Broad product stage

**Observed:** Feature stage spans the 1264px content area. Feature panel heading begins 64px down, centered at a maximum width near 480px. Optional body support follows after 16px; media starts after a further 64px and emerges from the panel's clipped bottom edge.

**Transfer:** Use the broad format to establish the product's central working surface, with enough meaningful UI detail to reward attention.

**Text style:** `feature-heading` — FabricSerifWeb 400 · 36px/1.3 · tracking -0.006em

### Paired capability stages

**Observed:** Two Feature panels sit 24px apart. Both use centered 36px headings and large phone compositions; one pair reverses the arrangement, with a device entering from the top and its title below while its neighbor has title above and device below.

**Transfer:** Pair complementary tasks and vary the text/media order to create a gentle visual rhythm without changing materials.

**Text style:** `feature-heading` — FabricSerifWeb 400 · 36px/1.3 · tracking -0.006em

### Editorial social proof

**Observed:** Inside the 912px editorial container, a left-aligned 48px title and 17px paragraph sit beside two staggered Social proof cards, which extend beyond the text column. A Community activity strip adds real-use texture across the viewport beneath this quieter endorsement block.

**Transfer:** Blend one simple quantified or behavioral proof point with genuine voices and an artifact strip; do not require the original industry or metric.

**Text style:** `display` — FabricSerifWeb 400 · 48px/1.3 · tracking -0.006em

### Plainspoken reassurance rows

**Observed:** A 912px container with 48px side padding holds three two-column rows. A short 16px medium question occupies the narrow left column, while a same-weight answer heading and 16px/1.8 paragraph occupy the right. Rows are separated by 64px; a faint bottom rule concludes the block.

**Transfer:** Address switching costs, ownership and sustainability with precise, practical answers instead of a dense accordion.

**Text style:** `small-heading` — Inter 500 · 16px/1.3

### Human introduction

**Observed:** Centered 48px heading, 720px-wide 17px support paragraph, then a row of three Portrait identity items after 48px. The section has 120px bottom breathing room.

**Transfer:** Explain who is responsible for the product in a short collective voice, then show a small number of real people or representative human vignettes.

**Text style:** `display` — FabricSerifWeb 400 · 48px/1.3 · tracking -0.006em

### Illustrated invitation and utility close

**Observed:** Illustrated closing band begins with the 120px concave white cap. Centered content uses 190px top and bottom padding inside closing-content. A 48px invitation, 500px-wide support paragraph after 16px and Primary button after 32px form the central stack. Peripheral closing drawings enliven the edges. A 1px hairline leads to an 80px utility row with plain links at left and a 13px copyright at right.

**Transfer:** End with a welcoming question, a brief restatement of the product's usefulness and one account-oriented action. Preserve the curved field and original ink details even when the rest of the page is short.

**Text style:** `display` — FabricSerifWeb 400 · 48px/1.3 · tracking -0.006em

### Membership chooser

**Only for:** pricing pages

**Observed:** Centered title and warm explanation in a 720px text container precede Promotion note and Billing switch, with 48px gaps. Plan-grid follows with neutral, sage and mauve Plan cards. The cards are top-aligned, not forced to equal height. Serif prices, tiny Tier badges and clipped diagonal savings ribbons establish a light hierarchy.

**Transfer:** Make tier differences intelligible in plain text; explain support or value before asking for payment.

**Text style:** `price` — FabricSerifWeb 400 · 39px/1

### Alternating capability chapters

**Only for:** pricing feature chapters

**Observed:** A compact text column and approximately 687 by 525px browser image swap sides between chapters. Headings use the 48px/1.2 editorial variant, body copy follows after 24px, and centered 720px hairlines punctuate the wide whitespace.

**Transfer:** Expand the most important paid capabilities with task evidence, rather than repeating the complete comparison list.

**Text style:** `feature-heading-editorial` — FabricSerifWeb 400 · 48px/1.2 · tracking -0.006em

### Centered candid explanation

**Only for:** pricing pages

**Observed:** Question-shaped 48px serif headings sit over centered 17px paragraphs, inside a restrained editorial width. Each explanation receives 64px bottom padding, before the shared people and illustrated closing treatments.

**Transfer:** Answer a real business-model objection with direct reasoning and a human voice.

**Text style:** `display` — FabricSerifWeb 400 · 48px/1.3 · tracking -0.006em

## Page flow

**Storyline:** Useful promise → tangible product proof → human evidence → candid reassurance → personal invitation.

### Introduce an approachable product and make joining feel easy

1. **Promise** — A spare split scene pairs a concise serif proposition with large monochrome narrative illustration and immediate actions.
2. **Product demonstration** — Broad browser stages alternate with paired phone panels, showing complementary capabilities.
3. **Social proof** — A behavioral proof point, staggered conversational recommendations and a horizontal real-activity strip establish use.
4. **Objection handling** — Short question-and-answer rows explain migration, ownership and how the service sustains itself.
5. **Human trust** — A collective maker story and circular illustrated identities make the product feel accountable.
6. **Closing call** — A curved pale field, edge drawings, centered invitation and single action lead into the utility row.

**Transfer:** Choose only the capability and reassurance beats the new product needs; retain the alternation between tangible interfaces and human editorial moments.

### Explain membership value and the reasons to pay

1. **Value framing** — A centered title and warm paragraph explain the extra benefits and supporting relationship.
2. **Pricing** — A small offer, billing control and three softly tinted, top-aligned plan cards establish the choices.
3. **Capability chapters** — Alternating oversized browser media and compact editorial copy demonstrate the main benefits.
4. **Objection handling** — Centered question headings explain the economic model in candid prose.
5. **Human trust** — A personal introduction reprises the maker relationship.
6. **Closing call** — The same illustrated curved invitation ends with a free-account action and utility links.

**Transfer:** Use the pricing variant without importing its sage and mauve fills into the default product opening.

## Writing

Warm, literate and matter-of-fact, with the occasional colloquial wink. The product feels like something a small group of people made thoughtfully, not a grand technological revolution.

**Do not copy:** Do not reuse the brand name, logo, original characters or drawings, team identities, member statistics, dates, prices, savings claims, testimonials or competitor-specific migration promises. Examples illustrate syntax and tone, not claims for a new product.

- **Addressing the reader:** Talk directly to 'you' about useful outcomes; use 'we' and 'our' when explaining responsibility and choices. Refer to users as members or friends when that relationship is truthful.
- **Rhythm:** Short sentence-case headlines, usually 4–9 words; support is one or two readable sentences. Longer trust passages remain conversational and specific, with contractions and occasional questions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the product's role in the reader's life, using a simple noun phrase. | 6–9 words | “The companion app for every book” |
| Capability heading | A practical verb followed by a clear personal benefit. | 4–9 words | “Track your reading and build your library”<br>“Kickstart your reading habit” |
| Support line | Plain usefulness followed by a small human aside. | 10–25 words | “Simple to use & easy on the eye - no spreadsheets needed.” |
| Trust explanation | A direct question answered with an accountable first-person statement. | 3–5 word heading; short paragraph | “Your data is your business, not ours.”<br>“Why charge money?” |
| Primary action | A short action with a clear entry cost or account outcome. | 2–5 words | “Join for free”<br>“Create a free account” |
| Closing invitation | A friendly question that asks for participation rather than urgency. | 4–6 words | “Ready to join us?” |

**Words and phrasing to use:** companion; your; we; members; simple; handy; no fuss; friends; support; take it with you

**Avoid:** revolutionary; disrupt; 10x; dominate; enterprise-grade everything; unlock limitless potential; act now

**Rules:**

- Lead with everyday outcomes and recognizable tasks.
- Explain trade-offs frankly instead of hiding them behind aspirational language.
- Use contractions and restrained colloquialisms to make longer explanations sound spoken.
- Keep claims specific and supportable; place real numbers in prose rather than oversized statistic billboards.
- Treat paid membership as a fair relationship, not a pressure funnel.

## Do's and Don'ts

### Do

- Keep major serif titles at 48px, weight 400 and -0.006em tracking.
- Use 36px serif titles inside feature stages so the interface remains the dominant object.
- Keep 16px and 17px support paragraphs at 1.8 line height.
- Use 8px corners for both actions and broad pale product panels.
- Keep the 24px feature-pair gutter and the tighter 16px plan-grid gutter distinct.
- Pair full-scale interface evidence with sparse original ink illustration.
- Carry the 120px curved cap and peripheral line drawings into the final invitation.
- Let plan cards remain content-height, top-aligned, with the same black action style across tiers.

### Don't

- Do not replace the serif hierarchy with heavy geometric sans headings.
- Do not turn 54px rectangular conversion actions into fully rounded capsules.
- Do not spread sage or mauve across ordinary landing sections; they identify pricing tiers.
- Do not add deep drop shadows to every pale feature panel; those panels are flat.
- Do not style prose like a compact dashboard; the 1.8 line height is part of the voice.
- Do not enlarge 9px uppercase tier lettering into general-purpose marketing eyebrows.
- Do not replace illustrated circular identities with a large glossy portrait wall.
- Do not turn the final utility row into a dense multi-column sitemap; it is a low 80px strip.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare 300ms cubic-bezier(0.23, 1, 0.32, 1) transitions and a 1px upward hover lift; active returns to the resting position.
- Plain navigation links declare 150ms ease-in-out transitions and the same 1px upward hover lift.
- The fixed translucent navigation surface declares a 600ms cubic-bezier(0.23, 1, 0.32, 1) transition.
- The billing switch declares 300ms cubic-bezier(0.23, 1, 0.32, 1).

**Transfer:**

- Keep interactions physically tiny: a 1px action lift, not a bouncing or scaling button.
- Retain the softly translucent fixed navigation as content passes beneath it.

**Unknown:**

- The timing and direction of any automatic activity-strip movement are unknown.
- The ending character's artwork suggests small tail movement; its timing is not specified.
- No focus-visible treatment or scroll-entry choreography is established.

### Responsive

**Observed:**

- Declared width breakpoints include 368px, 592px, 690px, 816px, 850px, 1088px and 1360px; pricing also includes 1632px.

**Transfer:**

- On narrow layouts, stack text before the large ink scene while retaining its unframed white backing; keep a recognizable figure and object rather than shrinking the entire scene to a thumbnail.
- Stack paired product stages and plan cards when their text and device silhouettes no longer fit; preserve clipped media within each pale panel.
- Wrap the low utility link row and keep edge illustrations away from actions; these are adaptation recommendations.

**Unknown:**

- Exact narrow-screen typography, navigation collapse, ordering and breakpoint-specific layouts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
