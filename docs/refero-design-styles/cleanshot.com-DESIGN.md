# CleanShot — luminous native utility

## Overview

A bright, friendly software style with the polish of a native desktop app. Rounded grotesk type, electric blue actions and faint icy-blue light sit on a predominantly white canvas, while richly colored interface demonstrations carry the visual excitement. The density alternates between spacious explanations and compact illustrated feature collections, ending in a dark, softly illuminated conversion area. It suits practical tools whose value becomes obvious when people can see them working.

### Essentials

- Headlines finish with a flash of blue rather than becoming rainbow lettering: 60px/1.1, weight 600, -0.02em tracking, with a horizontal ink-to-blue gradient holding ink through 60%.
- The promise gets a calm center stage before proof arrives: an 890px headline, 16px gap to 18px supporting copy, 32px to paired 48px actions, then a wide demonstration beside a human quote. A pale blue atmospheric wash connects these layers.
- Actions feel like little native controls, not flat pills: 14px corners, 48px height, 20px side padding, blue fill with a cyan inset highlight and small underside shadow; white secondary controls retain a fine shadow-defined edge.
- Color belongs to demonstrations and light, not to every section: the main reading canvas stays white; saturated blue, violet and near-black live inside 20px-rounded media stages and mixed-width tiles. Carry this illustrated product-stage device into every new landing page, using a credible simplified workflow if no finished interface exists.
- Feature collections have an uneven, image-led rhythm: a four-column grid of 280px modules and 24px gutters combines 584px wide tiles with narrow ones, all 418px tall, with 30px inset captions.
- The ending changes the lighting, not the typographic language: a near-black full-width closing region with blurred colored light, a 112px product emblem, 40px/1.2 centered closing line and white action continues into a ruled newsletter band and four compact link columns.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0d44e8` | `--color-action` | action, link, accent | Primary buttons, short exploration links and fine outline icons. |
| Headline blue | `#174ef2` | `--color-headline-blue` | accent | Right-hand finish of the display headline gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Main page canvas, raised cards, secondary buttons and inverse headings. |
| Control wash | `#f1f1f1` | `--color-control-wash` | surface | Billing-switch track and ghost-action hover wash; ink at 0.06 alpha on white. |
| Light divider | `#e3e3e3` | `--color-rule` | border | Fine comparison and tool-grid separators; ink at 0.12 alpha over white. |
| Inverse secondary | `#bcbdbd` | `--color-inverse-muted` | text | White at 0.72 alpha over closing charcoal; background light can subtly change the visible gray. |
| Secondary gray | `#6a6a6b` | `--color-muted` | text | Secondary copy on white; implemented with ink at 0.64 alpha. |
| Inverse control edge | `#49494b` | `--color-inverse-edge` | border, surface | White at 0.24 alpha over closing charcoal; outlines the email field and fills its adjoining action. |
| Inverse hairline | `#222225` | `--color-inverse-rule` | border | White at 0.08 alpha over closing charcoal, separating newsletter and navigation content. |
| Soft black ink | `#161618` | `--color-ink` | text | Default text, card headings and the starting color of headline gradients. |
| Closing charcoal | `#0f0f12` | `--color-night` | background, surface | Full closing region and small dark announcement badge. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| feature catalogues | Panel edge | `#d0d0d1` | `--color-panel-edge` | border | Outlined detail panels; ink at 0.2 alpha over white. |

## Typography

- **Google Sans Flex** — All marketing headings, paragraphs, actions and labels. A rounded, open grotesk with approachable shapes; semibold headings and slightly heavier-than-regular body text make the interface feel native. If unavailable, use **Inter**. Use weights 450, 550 and 600; preserve the tight display tracking and open body leading. Font stack: "Google Sans Flex", "Inter", "SF Pro Display", "SF UI Text", "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Google Sans Flex | 600 | 60px | 1.1 | -0.02em | Main promise, centered by default; ink-to-blue clipped gradient. |
| heading | Google Sans Flex | 600 | 40px | 1.2 | -0.02em | Capability chapters, proof headings and inverse closing statement. |
| tile-heading | Google Sans Flex | 600 | 20px | 1.4 | -0.02em | Bento captions and small capability cards. |
| body | Google Sans Flex | 450 | 18px | 1.67 | 0.01em | Hero support, section descriptions, testimonial quotes and sentence-case proof eyebrows. |
| body-small | Google Sans Flex | 450 | 15px | 1.6 | 0.01em | Tile descriptions, compact supporting copy and newsletter support. |
| control | Google Sans Flex | 550 | 15px | 1.6 | 0.01em | Buttons, top navigation and compact feature labels. |
| caption | Google Sans Flex | 450 | 14px | 1.43 | 0.01em | Attribution secondary lines, footer links and rating captions. |
| label | Google Sans Flex | 550 | 14px | 1.43 | 0.01em | Announcement text, testimonial names and footer column titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| detail chapters, offer cards and expanded customer proof | subheading | Google Sans Flex | 600 | 24px | 1.333 | -0.02em | Nested capability headings and substantial quotation text. |
| pricing pages | plan-name | Google Sans Flex | 550 | 21px | 1.67 | 0.01em | Plan labels above large 40px prices. |
| feature catalogues | catalogue-body | Google Sans Flex | 450 | 18px | 1.89 | 0.01em | Longer introductory explanations above large demonstrations. |
| pricing pages | question | Google Sans Flex | 600 | 18px | 1.67 | 0.01em | Accordion questions and guarantee headline. |
| pricing controls and assurance badges | micro-control | Google Sans Flex | 550 | 13px | 1.23 | 0.01em | Billing options and compact certification controls. |

**Notes:**

- Headings use -0.02em throughout; body and controls use +0.01em. Keep these two tracking families rather than progressively tightening every size.
- Body weight is 450, not 400; actions and small labels are 550, not bold. The 600 heading weight supplies the strongest emphasis.
- Section labels remain sentence case. A proof eyebrow uses the body recipe rather than tiny, widely spaced capitals.

## Layout

**Density:** Airy at chapter level and compact inside product tiles; long white pauses frame tightly composed demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Attribution stacks and compact label-to-description gaps. |
| 12px | Section heading-to-body gap, icon-label spacing and newsletter field-to-button gap. |
| 16px | Hero headline-to-description gap and paired-action gutter. |
| 24px | Bento and carousel gutters. |
| 30px | Bento text inset. |
| 32px | Hero support-to-actions gap, quotation-card and plan-card padding. |
| 40px | Catalogue introduction-to-media gap and spacing between compact detail panels. |
| 48px | Newsletter vertical padding and spacing above footer links. |
| 64px | Large chapter heading group-to-media separation. |
| 80px | Gap between text and media in split features; catalogue subsection lead-in. |
| 120px | Main content lead-in/out and closing conversion block bottom padding. |
| 180px | Separation after major chapters in feature catalogues. |
| 200px | Major landing-page chapter separation. |

### Containers and grids

- **marketing-container**: max width 1232px · side padding 20px. Centered border-box container; 1192px usable width at desktop, shared by navigation, demonstrations and feature groups.
- **split-feature**: 2 columns · gap 80px. 432px text beside 680px media, vertically centered; reverse the direction between selected chapters.
- **bento-grid**: 4 columns · gap 24px. Four 280px modules; wide cards span two modules for a 584px width.
- **hero-copy**: max width 890px. Centered two-line main promise; narrower supporting text beneath.
- **footer-container**: max width 1344px · side padding 20px. Wider closing region with 1304px usable width, four link columns and a two-part newsletter band.
- **catalogue-content** (only for feature catalogues): max width 888px · gap 24px. Right-hand editorial column alongside a persistent narrow contents rail.
- **plan-pair** (only for pricing pages): 2 columns · gap 25px. Two centered 432px plan cards; comparison below expands to the main container.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 14px |
|  | media-and-cards | 20px |
|  | email-field | 16px |
|  | circular-navigation | 50% |
| pricing pages | billing-selection | 12px |
| large customization demonstrations | halo-demonstration | 35px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | primary-control | `rgba(4, 24, 85, 0.28) 0px 2px 6px -1px, rgba(66, 174, 247, 0.48) 0px 6px 14px 0px inset` | Blue actions get both an underside shadow and a luminous inner top edge. |
|  | secondary-control | `rgba(22, 22, 24, 0.2) 0px 2px 6px -1px, rgba(22, 22, 24, 0.16) 0px 0px 0px 1px` | White actions and selected compact controls. |
|  | soft-card | `rgba(22, 22, 24, 0.02) 0px 7px 20px -8px, rgba(22, 22, 24, 0.02) 0px 29px 33px -4px, rgba(22, 22, 24, 0.05) 0px 22px 30px -8px, rgba(22, 22, 24, 0.06) 0px 0px 0px 1px` | White proof and carousel cards float subtly above white. |
| pricing and expanded proof sections | raised-panel | `rgba(22, 22, 24, 0.04) 0px 9px 26px -6px, rgba(22, 22, 24, 0.05) 0px 29px 47px -4px, rgba(22, 22, 24, 0.02) 0px 50px 63px -8px, rgba(22, 22, 24, 0.08) 0px 0px 0px 1px` | Plan cards and larger quotation panels. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing surface.

**CSS:** `background: #ffffff; color: #161618`

**Observed:** White remains visible between chapters; blue atmospheric light is concentrated around the opening and selected proof areas.

**Transfer:** Keep the explanatory reading area white even when demonstrations are dark.

#### Soft raised card · level 1

**Use:** Proof and carousel content.

**CSS:** `background: #ffffff; border-radius: 20px; box-shadow: rgba(22, 22, 24, 0.02) 0px 7px 20px -8px, rgba(22, 22, 24, 0.02) 0px 29px 33px -4px, rgba(22, 22, 24, 0.05) 0px 22px 30px -8px, rgba(22, 22, 24, 0.06) 0px 0px 0px 1px`

**Observed:** A faint shadow-defined outline and broad diffuse lift, without a contrasting gray fill.

**Transfer:** Use for real content groups; keep image-led tiles visually distinct from white quote cards.

#### Dark illuminated ending · level 0

**Use:** Closing conversion, newsletter and footer.

**CSS:** `background: #0f0f12; color: #ffffff; position: relative; overflow: hidden`

**Observed:** Colored light is diffused behind the top conversion region, fading into almost uniform charcoal around the links; a 60px backdrop blur softens the decorative layer.

**Transfer:** Place the closing-light artwork behind content, never as a textured overlay on text.

#### Newsletter band

**Use:** Separates conversion from utility links.

**CSS:** `border-top: 1px solid rgba(255, 255, 255, 0.08); border-bottom: 1px solid rgba(255, 255, 255, 0.08); padding: 48px 0`

**Observed:** Copy on the left, a short horizontal form on the right; no additional card fill.

**Transfer:** Let the ending surface remain continuous through the band.

#### Outlined detail panel · level 1

**Only for:** feature catalogues

**Use:** Capability matrices and compact text/media explanations.

**CSS:** `border: 1px solid rgba(22, 22, 24, 0.2); border-radius: 20px; overflow: hidden`

**Observed:** White interior; two-column matrices add lighter 0.12-alpha ink internal rules.

**Transfer:** Use thin outlines for exhaustive detail, reserving soft lifted cards for proof and purchase.

## Components

### Navigation

**Use:** Persistent product navigation above the marketing content.

**CSS:** `position: sticky; padding: 12px 0; z-index: 10`

**Text style:** `control` — Google Sans Flex 550 · 15px/1.6 · tracking 0.01em

**Observed:** A 73px header contains a centered marketing-container row: small app icon and word label on the left, navigation next, account action and blue purchase control on the right. The purchase control is 40px tall with 16px side padding. The bar appears translucent and softly frosted over scrolling content; dropdown labels have 20px chevrons.

**Transfer:** Use short product and support menus rather than a large editorial masthead.

### Primary button

**Use:** Main conversion and feature exploration.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #0d44e8; color: #ffffff; border-radius: 14px; height: 48px; padding: 0 20px; box-shadow: rgba(4, 24, 85, 0.28) 0px 2px 6px -1px, rgba(66, 174, 247, 0.48) 0px 6px 14px 0px inset; transition: background 0.15s, transform 0.2s, box-shadow 0.2s`

**Text style:** `control` — Google Sans Flex 550 · 15px/1.6 · tracking 0.01em

**Observed:** Label-only by default; width follows text. Paired with a white secondary action, not another competing filled color.

**States:** Declared: hover background #0a31a6; active translateY(2px), remove the outer shadow while retaining the cyan inset highlight.

### Secondary button

**Use:** Demonstration, learn-more and inverse closing actions.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; color: #161618; border-radius: 14px; height: 48px; padding: 0 20px; box-shadow: rgba(22, 22, 24, 0.2) 0px 2px 6px -1px, rgba(22, 22, 24, 0.16) 0px 0px 0px 1px`

**Text style:** `control` — Google Sans Flex 550 · 15px/1.6 · tracking 0.01em

**Observed:** Demo version places a 20px outline play triangle before the label. The same white control becomes the dominant action on the dark ending.

**States:** Declared: hover color #0d44e8 and white background; active translateY(2px), remove the lower shadow and retain the 1px shadow edge.

### Announcement badge

**Use:** Small release hook above the opening promise.

**CSS:** `display: flex; align-items: center; gap: 6px; height: 36px; padding: 8px 13px 8px 8px; background: #0f0f12; color: #ffffff; border-radius: 14px; box-shadow: rgba(22, 22, 24, 0.2) 0px 2px 6px -1px, rgba(13, 108, 232, 0.3) 0px 0px 10px 0px`

**Text style:** `label` — Google Sans Flex 550 · 14px/1.43 · tracking 0.01em

**Observed:** A small outline play symbol precedes a sentence-case release label; the badge is centered in its own breathing space.

### Bento tile

**Use:** Illustrated feature collections.

**CSS:** `position: relative; border-radius: 20px; overflow: hidden; max-width: 584px`

**Text style:** `tile-heading` — Google Sans Flex 600 · 20px/1.4 · tracking -0.02em

**Observed:** Full-bleed illustration behind top-aligned title and body-small copy, inset 30px. Narrow tiles are 280px wide; wide tiles are 584px; both are 418px tall. Captions switch between ink and white according to the local artwork.

**Transfer:** Design an individual image composition around each benefit, leaving a deliberate low-detail caption area.

### Testimonial card

**Use:** Human proof in a horizontally overflowing gallery.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 32px; max-width: 480px; box-shadow: rgba(22, 22, 24, 0.02) 0px 7px 20px -8px, rgba(22, 22, 24, 0.02) 0px 29px 33px -4px, rgba(22, 22, 24, 0.05) 0px 22px 30px -8px, rgba(22, 22, 24, 0.06) 0px 0px 0px 1px`

**Text style:** `body` — Google Sans Flex 450 · 18px/1.67 · tracking 0.01em

**Observed:** Avatar and two attribution lines come first, with a 36px gap before the quote. Label recipe for name, caption recipe for handle. Cards have 24px gutters; 40px circular next/previous controls sit beneath the gallery. A compact rating cluster sits opposite the section heading.

**Transfer:** Use varied, credible voices and allow the next card to peek beyond the content edge.

### Newsletter input

**Use:** Email collection within the dark ending.

**CSS:** `height: 48px; max-width: 330px; padding: 0 18px; border: 1px solid rgba(255, 255, 255, 0.24); border-radius: 16px`

**Observed:** A transparent dark field sits beside the Subscribe button, with compact consent copy underneath. The form is right-aligned opposite newsletter title and description.

### Subscribe button

**Use:** Newsletter submission on charcoal.

**CSS:** `height: 48px; padding: 0 20px; border-radius: 14px; background: rgba(255, 255, 255, 0.24); border: 1px solid rgba(255, 255, 255, 0.24); color: rgba(255, 255, 255, 0.64); box-shadow: rgba(22, 22, 24, 0.5) 0px 0px 6px -2px, rgba(22, 22, 24, 0.25) 0px 6px 4px -2px`

**Text style:** `control` — Google Sans Flex 550 · 15px/1.6 · tracking 0.01em

**Observed:** A subdued translucent control keeps the main closing action more prominent.

**States:** Declared: active translateY(2px).

### Footer link

**Use:** Compact utility navigation in the ending.

**CSS:** `display: flex; margin: 8px 0; color: rgba(255, 255, 255, 0.72); transition: color 0.1s`

**Text style:** `caption` — Google Sans Flex 450 · 14px/1.43 · tracking 0.01em

**Observed:** Four columns use brighter label-recipe titles with 16px below them; lower edge carries copyright, a compact assurance badge and small social marks.

**States:** Declared: hover color #ffffff.

### Plan card

**Only for:** pricing pages

**Use:** Compare purchase models without hiding the common product.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-radius: 20px; padding: 32px; max-width: 432px; box-shadow: rgba(22, 22, 24, 0.04) 0px 9px 26px -6px, rgba(22, 22, 24, 0.05) 0px 29px 47px -4px, rgba(22, 22, 24, 0.02) 0px 50px 63px -8px, rgba(22, 22, 24, 0.08) 0px 0px 0px 1px`

**Text style:** `plan-name` — Google Sans Flex 550 · 21px/1.67 · tracking 0.01em

**Observed:** Short audience ribbon above each card; name, 40px price, billing explanation, icon-led feature groups and full-width blue action. Subscription variant adds a 195px by 36px billing switch: 2px inset, 14px track corners, white 12px-corner selected segment and micro-control labels.

**Transfer:** Keep both plans white, using a faint blue/violet ribbon rather than a fully saturated recommended card.

### FAQ question

**Only for:** pricing pages

**Use:** Purchase objections after plan comparison and alternative offers.

**CSS:** `padding: 18px 22px; margin-bottom: 5px; border-radius: 20px`

**Text style:** `question` — Google Sans Flex 600 · 18px/1.67 · tracking 0.01em

**Observed:** Questions occupy a 736px right-hand column beside a short help introduction; a small chevron aligns at the far right. Closed rows remain white and visually unboxed.

**Transfer:** Keep answers factual and short; blue inline links connect to the next useful action.

### Detail panel

**Only for:** feature catalogues

**Use:** Nested capability explanation with one focused visual.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr; align-items: center; gap: 80px; padding: 8px; border: 1px solid rgba(22, 22, 24, 0.2); border-radius: 20px`

**Text style:** `subheading` — Google Sans Flex 600 · 24px/1.333 · tracking -0.02em

**Observed:** An 888px-wide compact panel has text at left and a 395px by 267px image at right, with inset rounded media. The text uses a 24px heading, then body-small copy 16px below.

**Transfer:** Use for secondary details within an indexed catalogue, not as the default landing-page feature format.

## Imagery and graphics

### Native workflow stages

**Use:** Primary visual proof throughout the page.

**Observed:** Crisp desktop application windows, floating toolbars, cursor actions and small content examples sit on blue/violet wallpaper-like gradients or deep black abstract backdrops. Split stages measure 680px by 480px with 20px corners; broad demonstrations fill the 1192px content width. Some windows are deliberately enlarged and clipped to emphasize the action, not a whole desktop.

**Transfer:** Show one believable task in the new product, using its own interface. Minimum acceptable version: a carefully composed simplified window with real labels, one visible input and a clear output, backed by colored light; avoid an unreadable dashboard collage.

### Illustrated benefit tiles

**Use:** Image-led capability groups.

**Observed:** Warm peach, icy blue, violet and near-black tiles alternate. Cropped interface fragments fill the lower area beneath compact captions; webcam circles, keycaps, browser bars and shields make individual benefits tangible. Light and dark tiles mix within the same grid.

**Transfer:** Translate each benefit into one clear object or interface gesture. Use photography only as small content inside the workflow, not as generic full-bleed lifestyle imagery.

### Atmospheric page light

**Use:** Opening and selected proof galleries; a signature visual layer.

**Observed:** Extremely soft cool blue light washes a white background, strongest behind the promise, fading out before reading chapters. It has no hard edge or visible geometric grid. A wide background graphic uses 0.5 opacity at the opening and 0.25 in selected galleries.

**Transfer:** Keep the light subtle enough that white still reads as the canvas, with clear black text above it.

**Build:** On an absolute decorative layer behind content, overlap a broad pale cyan radial ellipse and a smaller blue ellipse centered behind the headline. Use rgba(66,174,247,0.12) and rgba(23,78,242,0.06) fading to transparent; blur about 60px and extend the layer beyond the container. Match the soft wash rather than emphasizing exact gradient stops.

### Closing colored light

**Use:** Top of the dark closing region; a signature inverse of the opening wash.

**Observed:** Low-intensity magenta, violet and blue illumination spreads across the upper charcoal background, dissolving before the newsletter and footer links. It is atmospheric rather than a sharp rainbow strip.

**Transfer:** Retain a colored horizon behind the centered product emblem and closing promise, even for a product without elaborate artwork.

**Build:** Behind the content, place three broad radial ellipses across the top: rgba(255,95,162,0.14) at left, rgba(23,78,242,0.2) near center and rgba(66,174,247,0.14) at right. Blur by 60px, mask the layer toward transparent below the conversion block, and leave the base charcoal solid.

### Customization halo

**Only for:** large customization demonstrations

**Use:** One highlighted editor or appearance-control demonstration.

**Observed:** A 988px by 626px editor window with roughly 35px corners floats above a diffuse multicolor rim. Peach and yellow light above the window transition into pink, violet, blue and cyan around its edges; a soft underside shadow grounds it.

**Transfer:** Use to emphasize a feature that genuinely changes the presentation of the output, rather than adding a halo to every image.

**Build:** Place an absolute pseudo-element at -1% inset behind the rounded stage. Use a conic gradient through peach, yellow, blue, cyan, violet and pink, set opacity to 0.5 and filter blur(50px). Ground the stage with 0px 24px 44px rgba(0,0,0,0.15); clip only the foreground window, not the surrounding light.

### Icons

**Observed:** Small functional outlines at 20px or 24px, usually about 1.7px stroke with rounded caps. Blue marks lead benefit lists; muted chevrons accompany navigation; play triangles sit inside demonstration actions. Decorative app-style emblems may be full color and dimensional.

**Transfer:** Choose a consistent rounded outline family for controls and lists. Reserve shaded or dimensional icons for product emblems and major illustrated benefits.

## Section recipes

How recurring sections are built.

### First screen: Centered promise and paired proof

**Observed:** A slim Navigation sits above a white canvas with Atmospheric page light. A dark Announcement badge is centered above an 890px-wide, two-line display promise. The headline occupies about two thirds of the viewport width; its ink-to-blue gradient runs horizontally through the full line. A centered 18px body support line sits 16px below, followed by paired Primary button and Secondary button actions after 32px, and a small reassurance line below. A 1192px proof row starts beneath a generous pause: 688px-wide video left, 480px white quote panel right, separated by 24px. Within the first 900px the badge, headline, support, actions, reassurance and most of the proof row are visible; the bottom of that row and logo proof continue below the fold. The layers are white canvas, broad pale light, text/actions, then tangible video and quote cards.

**Transfer:** For a new landing page, preserve the centered promise plus paired visual-and-human proof composition. Substitute a focused workflow animation or a designed still for the video, and a credible short quote or compact outcome explanation at right. Product-detail variants open left-aligned with a 60px headline and a large app window extending beyond the right edge. Pricing and catalogues use a compact centered title with support before their utility content.

**Avoid:** Do not replace the paired proof with a giant decorative device mockup, or turn the headline into outlined display lettering. Do not fill the first screen with a saturated blue background.

**Text style:** `display` — Google Sans Flex 600 · 60px/1.1 · tracking -0.02em

### Heading and exploration action

**Observed:** A 40px heading and 18px muted support line form a left-aligned group with 12px separation. A blue exploration action aligns to the right. The demonstration or Bento tile collection follows after 64px; centered variants constrain copy and omit the side action.

**Transfer:** Lead with one outcome, then let the media explain the mechanism; use the same heading rhythm for any capability.

### Alternating workflow explanation

**Observed:** Split-feature layout pairs a 432px explanation with a 680px by 480px Native workflow stage across an 80px gap. Heading and support use the standard pair; selected chapters add two or three icon-led benefit lines and a white Secondary button. Direction reverses between selected sections, with 200px chapter gaps.

**Transfer:** Alternate based on narrative emphasis, not mechanically for every paragraph. Give each stage a single action that visually supports the heading.

### Mixed-width feature collection

**Observed:** Bento-grid uses wide and narrow Bento tiles across two rows. Text remains at the top of each tile while the demonstration enters from below; 24px gutters and 20px clipping unify differently colored artwork.

**Transfer:** Group a related family of capabilities and vary tile widths according to visual complexity, not the length of the feature name.

### Overflowing proof gallery

**Observed:** A sentence-case body eyebrow sits 8px above a 40px heading. A small numeric rating, stars and review caption sit opposite it. Testimonial cards form a horizontal row with 24px gutters and a partially visible next card; round navigation is placed below at the right. Atmospheric page light softly backs the cards.

**Transfer:** Use actual proof in this compact review treatment, keeping the score visually smaller than the human quotes.

### Appearance demonstration

**Observed:** Centered heading and support precede the Customization halo stage after 50px. Beneath it, four icon-caption benefits form a row with fine vertical separators rather than four raised cards.

**Transfer:** Reserve this larger, luminous stage for a distinctive transformation in the new product.

### Purchase decision section

**Observed:** Two Plan cards sit under a compact centered display opening. A slim guarantee/rating panel follows, then a wide comparison table with fine horizontal rules, 15px row text and centered plan values. Three pastel alternative-offer tiles lead into the left-intro/right-accordion FAQ.

**Transfer:** Explain shared value before differences. Keep the table factual and airy; include only relevant purchase alternatives.

### Indexed capability catalogue

**Observed:** A narrow persistent left contents rail accompanies an 888px right column. Major 40px headings introduce 18px text with 1.89 leading, followed by large media after 40px and outlined two-column feature matrices. Nested 24px headings, Detail panels and smaller side-by-side demonstrations extend each chapter. The last chapter is a horizontally overflowing collection of settings windows with round navigation.

**Transfer:** Use this denser structure for exhaustive reference content. Keep the marketing opening and closing language, but avoid treating every subsection as a fresh hero.

### Illuminated closing and utility footer

**Observed:** Dark illuminated ending spans the full viewport. The top centers a 112px product emblem, then a 40px white closing statement within 584px, muted 18px reassurance and a Secondary button used as the main action. Top content has 100px padding and 120px below. Newsletter band follows with left copy and right form, then four Footer link columns after 48px, and copyright, assurance and social controls along the bottom. The service variant adds a bordered login action beside the main white action.

**Transfer:** Make this dark, softly lit closing device part of the page identity. Replace the emblem with a polished product icon or a simple rounded monogram; adapt the promise, reassurance and utility links to the new product.

## Page flow

**Storyline:** Promise → immediate visual proof → capability groups and workflow demonstrations → human or practical assurance → illuminated final action and useful footer.

### Broad product landing page

1. **Promise** — Centered display, release badge, paired actions and reassurance.
2. **Immediate proof** — Video beside a white quotation card, followed by a muted logo strip.
3. **Capability chapters** — A split workflow explanation, illustrated bento groups, an overflowing feature gallery and a broad editor demonstration.
4. **Focused benefits** — Alternating text/media sections and a final mixed-width everyday-use collection.
5. **Social proof** — Rating cluster and overflowing customer quotation cards.
6. **Closing call** — Dark illuminated conversion, newsletter, four link columns and bottom utility row.

**Transfer:** Introduce the simplest useful action early, expand into related capability families, then reinforce trust before the closing action.

### Purchase and plan selection

1. **Decision framing** — Compact centered gradient title and short explanation of what plans share.
2. **Pricing** — Two white raised plans with a billing switch for the subscription option.
3. **Risk reduction** — Guarantee panel with a small review score.
4. **Comparison** — Wide ruled comparison matrix.
5. **Alternative routes** — Three soft pastel offer tiles.
6. **Objection handling** — Left help prompt beside compact FAQ questions.
7. **Closing call** — The shared illuminated conversion and complete utility footer.

**Transfer:** Keep purchase choices at the top, then move from assurance to detailed differences and factual answers.

### Collaborative service landing page

1. **Promise** — Left-aligned gradient display and two actions beside an oversized app view with floating activity notifications.
2. **Audience fit** — Four illustrated use-case tiles beneath a centered heading.
3. **Workflow proof** — Split sharing demonstration followed by large quotation panels.
4. **Capability chapters** — Alternating views for presentation, organization and playback.
5. **Assurance** — Two tall illustrated panels, one dark and one light, covering trust and administration.
6. **Closing call** — Service-specific closing promise, signup and login, followed by the full newsletter and utility footer.

**Transfer:** Show who benefits before explaining the mechanics; end complex service claims with concrete trust and control signals.

### Focused capability landing page

1. **Promise** — Left headline and actions with an oversized editor window extending beyond the right edge.
2. **Orientation** — Centered heading above a wide toolbar demonstration.
3. **Product demonstration** — Vertical feature selector beside a large working view.
4. **Signature transformation** — Centered customization demonstration surrounded by multicolor light.
5. **Capability chapters** — Alternating split workflow stages with short icon-led benefits.
6. **Related value** — Centered cross-product invitation and two illustrated benefit cards.
7. **Closing call** — Shared dark illuminated conversion, newsletter and complete footer.

**Transfer:** Stay on one capability family, moving from overview to interactive detail to related workflow value.

### Exhaustive indexed capability catalogue

1. **Orientation** — Compact centered gradient title and a short introduction.
2. **Capability reference** — Persistent contents rail beside long-form chapters, large media and two-column ruled matrices.
3. **Nested detail** — Repeated compact outlined text/media panels and small demonstration collections.
4. **Customization proof** — An overflowing settings-window gallery closes the catalogue content.
5. **Closing call** — The same dark conversion area, newsletter and full utility footer as the landing pages.

**Transfer:** Let the contents rail carry navigation while visual demonstrations keep a long reference page approachable.

## Writing

Confident and practical, with warmth coming from everyday workflow language rather than jokes. Benefits are explained as concrete actions and useful outcomes; claims feel conversational rather than enterprise-heavy.

**Do not copy:** Do not reuse the CleanShot name, product emblems, interface artwork, customer identities, quotations, user totals, feature counts, review scores, prices, discounts, certifications or guarantee claims as facts for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader as you and your. The product name appears naturally when explaining what performs an action; we appears sparingly in support and policy contexts.
- **Rhythm:** Short, sentence-case benefit headings contrast with two or three explanatory sentences. Action labels are compact; support copy often moves from what happens to why it helps, ending with a plain-language reduction in effort.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A confident contrast or a clear outcome, with the differentiating idea at the end. | 4–12 words for simple titles; longer contrast promises can span two balanced lines. | “There are average capture apps. And there's [Brand].”<br>“Choose your setup” |
| Capability heading | Name the outcome or immediate action, not an abstract category of innovation. | 3–6 words. | “Always one drag away”<br>“Screen recordings worth sharing” |
| Supporting line | Explain the action, then remove a small everyday frustration. | About 20–40 words per feature explanation. | “Capture something and it's instantly ready to share. Save it, copy it, or drop it straight into any app. No folders to dig through, no flow to break.” |
| Primary action | Plain verb plus destination or product; exploration labels say what will be explored. | 2–6 words. | “Get [Brand] for Mac”<br>“How it works”<br>“Sign up now” |
| Newsletter | A familiar invitation followed by a candid statement of frequency and value. | One short title and one short sentence. | “New features, product news, and occasional deals. No spam.” |

**Words and phrasing to use:** ready to share; in one click; built right in; keep work moving; make it yours; without breaking your flow; polished; fast; native

**Avoid:** revolutionary ecosystem; unlock limitless potential; synergize; industry-disrupting; hypergrowth; excessive exclamation marks

**Rules:**

- Make a feature claim visible in the adjoining demonstration.
- Use concrete verbs in groups of two or three when explaining a workflow.
- Follow technical terms with their practical benefit; reserve acronyms for trust and administration details.
- Keep reassurance close to the action and state purchase conditions plainly.
- Use contractions naturally and keep headings in sentence case.

## Do's and Don'ts

### Do

- Keep the default display at 60px/1.1 and the chapter headings at 40px/1.2, both weight 600.
- Hold headline ink through 60% of the gradient before the blue finish.
- Use 48px actions with 14px corners; retain the primary control's inner cyan light.
- Pair 432px explanations with 680px media across an 80px gap.
- Mix 280px and 584px illustrated tiles with 24px gutters and 20px corners.
- Separate major capability chapters with 200px of breathing room.
- Carry the luminous product-stage device and dark illuminated ending into new landing pages.
- Keep compact body copy at 15px/1.6 and longer descriptions at 18px/1.67.

### Don't

- Do not make every heading blue; the gradient belongs to display promises, while section titles remain ink or white.
- Do not replace the 14px rounded rectangles with fully pill-shaped primary actions.
- Do not flatten raised white controls into borderless text when they are paired with blue conversion actions.
- Do not introduce a full-page gray card canvas; white space is the connective surface.
- Do not recolor all benefit tiles to one blue; warm, pale and dark image treatments provide the contrast.
- Do not use uppercase tracked micro-eyebrows in place of the sentence-case body-sized proof label.
- Do not enlarge the review number into a monumental statistic; it is a compact accompaniment to the quotes.
- Do not use generic office photography as the principal product proof; interface actions and tangible outputs carry that role.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary controls declare background 0.15s, transform 0.2s and box-shadow 0.2s transitions.
- Primary and secondary actions depress by 2px in active state; blue buttons darken on hover.
- Footer links declare color 0.1s transitions; compact billing-option text declares color 0.25s.
- Workflow video stages and horizontally navigable proof and feature galleries are part of the presentation.

**Transfer:**

- Preserve the small press-depth behavior of native-looking controls.
- Use workflow movement to demonstrate a single action inside its rounded stage, not as whole-page decoration.

**Unknown:**

- Video playback sequencing, gallery autoplay and entrance-animation timing are not established.
- Declared easing curves are not attributable to every specific component.

### Responsive

**Observed:**

- The defined composition is a 1440px desktop layout with centered max-width containers.

**Transfer:**

- On narrow screens, retain the centered promise and action hierarchy, then stack the paired proof panels.
- Collapse four-module benefit groups into fewer columns while preserving wide-versus-narrow emphasis through content priority.
- Keep atmospheric light behind the promise and closing action rather than shrinking it into a hard-edged banner.
- Replace the catalogue's side rail with a compact contents control before the chapter text.

**Unknown:**

- No mobile breakpoints or measured mobile typography are established; the collapse rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
