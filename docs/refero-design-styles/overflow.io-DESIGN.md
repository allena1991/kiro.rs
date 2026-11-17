# Overflow — luminous product storytelling

## Overview

A bright, spacious software-marketing style that pairs emphatic grotesk typography with soft clouds of violet and blue. Oversized interface scenes carry most of the story, with pale sculptural illustrations, friendly human details and occasional workplace photography. The atmosphere is playful and polished rather than technical or dense; most of the page remains almost white.

### Essentials

- Bold words float above a luminous product stage: Inter 56px/1.14 at weight 800 with -1.2px tracking, white over a blurred violet-to-cyan field, followed by a centered 24px support line and a black action.
- The opening promises, then immediately shows: a 96px fixed navigation, 148px of breathing room before the headline, and a 1224px-wide product window beginning at 674px so its upper portion enters the first 900px.
- Actions are compact black blocks, not colorful pills: 56px tall, 8px corners, 19px 24px padding and 16px weight-550 labels; the navigation version is 48px tall.
- Color is concentrated around demonstrations, not poured over every section: broad #fafafc and white fields dominate the long body, with a violet-blue media surround, one vivid blue tile among white cards, and a faint cool glow at the footer.
- Product scenes are much larger than their explanations: 1224px-wide canvases or 664px-wide close-ups sit inside 12px–28px rounded frames, backed by blue, yellow or violet rims. Use an original simplified interface scene when polished product media is unavailable.
- The serious typography gets small moments of tactile play: inset word labels, a blue selected-word treatment, pale raised UI objects, speech bubbles and cutout portraits. Include a restrained editorial accent of this kind alongside the luminous stage and footer glow, without turning every heading into artwork.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage violet | `#7272fb` | `--color-violet` | accent, background | Violet end of the broad product-demo gradient and the cool luminous atmosphere. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vivid blue | `#007bff` | `--color-blue` | surface, accent | Saturated end of a standout capability card gradient. |
| Sky blue | `#62aeff` | `--color-sky` | surface, accent | Light end of the standout capability card gradient. |
| Stage ice blue | `#b8e1ff` | `--color-ice` | background, accent | Pale blue end of the product-demo surround. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action | Headings, normal body copy, solid primary buttons and circular checkmarks. |
| Muted text | `#666666` | `--color-muted` | text | Visible result of black at 0.6 alpha on white; used for support lines and footer links. |
| Secondary action gray | `#f0f0f2` | `--color-secondary` | surface, border | Secondary buttons and subtle navigation separators. |
| Deeper pale gray | `#f2f2f4` | `--color-band` | background, surface | Editorial callout bands and selected tab backing. |
| Input wash | `#f5f5f5` | `--color-input` | surface | Visible black at 0.04 alpha over white in the newsletter field. |
| Pale tile | `#f5f5f7` | `--color-tile` | surface | Illustration wells and soft proof bands. |
| Cool near-white | `#fafafc` | `--color-canvas` | background | Default extended marketing canvas and alternating capability chapters. |
| White | `#ffffff` | `--color-white` | background, surface, text | Product windows, raised cards, footer and white hero text. Navigation uses white at 0.655 alpha. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| audience-specific workflow pages | Cyan demonstration wash | `#d5f3ff` | `--color-demo-wash` | background | Large backing behind the selectable workflow demonstration. |
| pricing pages | Feature rule | `#ededef` | `--color-rule` | border | Thin rules under pricing feature-category headings. |

## Typography

- **Inter** — All marketing headings, paragraphs, navigation and actions. High-x-height sans serif with broad, heavy headings and open, readable regular text. Font stack: "Inter", "Helvetica Neue", Arial, "Noto Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 800 | 56px | 1.14 | -0.0214em | fixed | Hero promise and the strongest section statements; white on the luminous opening, black in the body. |
| heading | Inter | 800 | 48px | 1.16 | -0.0167em | fixed | Main capability and proof section headings. |
| heading-small | Inter | 800 | 32px | 1.25 | -0.0125em | size calc(32px + 0vw) | Dense editorial calls and customer-story titles. |
| quote | Inter | 700 | 32px | 1.25 | -0.0125em | size calc(32px + 0vw) | Large testimonial text beside a cutout portrait. |
| card-heading | Inter | 800 | 24px | 1.33 | -0.0083em | size calc(24px + 0vw) | Feature card headings and headings inside split media sections. |
| lead | Inter | 500 | 24px | 1.58 | -0.0167em | fixed | Centered hero support and large introductory paragraphs. |
| body | Inter | 400 | 16px | 1.75 | normal | fixed | Explanatory paragraphs, checklists and feature descriptions. |
| button | Inter | 550 | 16px | 1 | 0.0125em | fixed | Main and secondary action labels. |
| footer-heading | Inter | 700 | 16px | 1.15 | -0.006em | fixed | Small footer column headings. |
| navigation | Inter | 400 | 15px | 1.75 | normal | fixed | Top navigation and sign-in links. |
| header-action | Inter | 550 | 15px | 16px | 0.013em | fixed | Compact navigation action. |
| tab | Inter | 500 | 15px | 1.75 | -0.019em | fixed | Product-demonstration mode tabs. |
| footer-link | Inter | 400 | 14px | 1.75 | normal | fixed | Muted footer navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | utility-heading | Inter | 800 | 40px | 1.2 | -0.0125em | size calc(40px + 0vw) | Feature-list and FAQ section headings. |
| pricing pages | price | Inter | 800 | 40px | 1.2 | -0.0168em | fixed | Main price digits with smaller currency and fractional digits. |
| audience and use-case pages | split-lead | Inter | 500 | 20px | 1.6 | -0.0125em | fixed | Introductory support in left-aligned photographic openings. |
| pricing pages | question | Inter | 700 | 20px | 1.2 | -0.005em | fixed | Questions, feature-list categories and plan names. |
| illustrated onboarding sections | step | Inter | 800 | 16px | 1.5 | 0.069em | fixed | Short uppercase step labels below large onboarding illustrations. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The display and section hierarchy relies on weight 800, not on an extreme range of sizes. Keep body text at weight 400 and large support at 500.
- Tracking is negative on headings but slightly positive on button labels. Keep the complete recipes together rather than applying one universal tracking rule.
- Centered hero support can span three lines within 830px; ordinary feature descriptions are much narrower, often 392px–408px.

## Layout

**Density:** Airy: large chapter breaks surround compact, readable text groups and very large demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 12px | Column half-gutters and tight title-to-copy spacing. |
| 16px | Default title-to-body gap and separation between checklist paragraphs. |
| 24px | Grid gutters, illustration-well padding and heading/support spacing. |
| 26px | Both axes of the asymmetrical capability-card grid. |
| 32px | Support-to-action gap and container side padding. |
| 40px | Demo-surround inset and illustration-to-caption separation. |
| 64px | Subfeature separation and compact promotional-band padding. |
| 72px | Major spacing within a tabbed product presentation. |
| 128px | Footer top padding and social-proof band spacing. |
| 148px | Opening content breathing room below navigation. |
| 156px | Default major chapter top and bottom padding. |

### Containers and grids

- **main-container**: max width 1288px · side padding 32px. Centered outer container. At a 1440px viewport its inner content is 1224px wide with 108px margins.
- **feature-grid**: 3 columns · gap 24px. Equal-width capability columns; 392px illustration wells within 416px column tracks.
- **capability-masonry**: 3 columns · gap 26px. Unequal 4:5:3 tracks with staggered white cards; the middle column is widest.
- **reading-column**: max width 704px. Centered section introductions and larger supporting paragraphs.
- **feature-copy**: max width 408px. Short explanations next to a large media scene.
- **faq-column** (only for pricing pages): max width 600px. Single-column questions centered in the page.
- **plan-pair** (only for pricing pages): max width 808px · 2 columns · gap 24px. Two calm equal-height plan cards, narrower than the main media container.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-inputs | 8px |
|  | hero-window | 12px |
|  | feature-well | 24px |
|  | capability-card | 24px |
|  | closeup-window | 28px |
|  | selected-tab | 22px |
| feature catalogue pages | catalogue-well | 16px |
| testimonial carousels | carousel-arrow | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| raised-card | `rgba(0, 0, 0, 0.08) 0px 4px 16px -8px` | White capability cards and plan cards. |
| product-stage | `rgba(0, 0, 0, 0.08) 0px 8px 20px -7px` | Hero product window and large colorful demo frame. |

### Surfaces

#### Cool canvas · level 0

**Use:** Long-form marketing body.

**CSS:** `background: #fafafc`

**Observed:** Broad near-white fields keep the small pale illustrations distinct without high-contrast section dividers.

**Transfer:** Use white sections where a clean chapter break is needed, and cool near-white for extended sequences.

#### White card · level 1

**Use:** Raised capability panels.

**CSS:** `background: #ffffff; border-radius: 24px; box-shadow: rgba(0, 0, 0, 0.08) 0px 4px 16px -8px`

**Observed:** Cards use almost invisible shadows, not heavy outlines.

**Transfer:** Reserve elevation for grouped benefits and plans, not every paragraph.

#### Illustration well · level 0

**Use:** Small self-contained product metaphors above descriptions.

**CSS:** `background: #f5f5f7; border-radius: 24px; padding: 24px`

**Observed:** A 392px by 300px rounded field contains a small centered object, then a 40px gap leads to text below. Catalogue wells use 16px corners.

**Transfer:** Keep text outside the well; center an original pale UI object inside.

#### Violet demo stage · level 1

**Use:** Large product presentation.

**CSS:** `background: linear-gradient(127deg, #7272fb 0px, #b8e1ff 99%); border-radius: 24px; padding: 40px; box-shadow: rgba(0, 0, 0, 0.08) 0px 8px 20px -7px`

**Observed:** The color reads as a wide rim around a nearly white interface.

**Transfer:** Preserve the pale center and saturated perimeter rather than tinting the entire interface.

#### Blue standout card · level 1

**Use:** A single high-energy benefit within a pale card grouping.

**CSS:** `background: linear-gradient(90deg, #007bff 0px, #62aeff 100%); border-radius: 24px; color: #ffffff; overflow: hidden`

**Observed:** White heading and tilted product fragments distinguish one card from the surrounding white panels.

**Transfer:** Use this contrast for one unusually valuable capability.

#### Editorial gray band · level 0

**Use:** Wide mid-page product-story call.

**CSS:** `background: #f2f2f4; padding: 64px 0px`

**Observed:** Text occupies one side while large angled interface fragments extend toward the opposite edge.

**Transfer:** Give the scene room to bleed beyond the content container.

#### Translucent navigation · level 2

**Use:** Fixed navigation above light content.

**CSS:** `background: rgba(255, 255, 255, 0.655); height: 96px; position: fixed; top: 0px; width: 100%`

**Observed:** A pale separator supports the header on scroll; an opaque white variant accompanies photographic openings.

**Transfer:** Keep the navigation visually light; no dark masthead or heavy frosted-glass effect.

## Components

### Navigation link

**Use:** Primary navigation within the fixed header.

**CSS:** `display: flex; align-items: center; padding: 8px 16px; color: #000000`

**Text style:** `navigation` — Inter 400 · 15px/1.75

**Observed:** Logo at left, a small group of links beside it, with sign-in and the compact primary action aligned right. The product entry has a small downward chevron.

**States:** Declared: hover color #259aef with no underline.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #000000; border: 1px solid #000000; border-radius: 8px; color: #ffffff; height: 56px; padding: 19px 24px`

**Text style:** `button` — Inter 550 · 16px/1 · tracking 0.0125em

**Observed:** Content-width black rectangle with a short label; some lower calls add a right arrow. The opening download action visually de-emphasizes its trial qualifier.

**States:** Declared: hover color #259aef, background and border stay black, transform translateY(-2px); active white text on black, no shadow, transform translateY(-1px).

### Header button

**Use:** Persistent conversion action in navigation.

**CSS:** `background: #000000; border: 1px solid #000000; border-radius: 8px; color: #ffffff; height: 48px; padding: 15px 12.8px`

**Text style:** `header-action` — Inter 550 · 15px/16px · tracking 0.013em

**Observed:** A compact sibling of Primary button, separated from the sign-in link.

**States:** Declared: hover color #259aef and translateY(-2px); active white text and translateY(-1px).

### Secondary button

**Use:** Editorial and lower-priority actions.

**CSS:** `background: #f0f0f2; border: 1px solid #f0f0f2; border-radius: 8px; color: #000000; height: 56px; padding: 19px 24px`

**Text style:** `button` — Inter 550 · 16px/1 · tracking 0.0125em

**Observed:** Same silhouette and label treatment as Primary button, but less visual weight.

**States:** Declared: hover color #259aef, background and border #e8e8ea, translateY(-2px); active black text on #f0f0f2 and translateY(-1px).

### Mode tab

**Use:** Switch between views of one product story.

**CSS:** `padding: 10px 20px; border-radius: 22px; color: #000000; background: #f2f2f4`

**Text style:** `tab` — Inter 500 · 15px/1.75 · tracking -0.019em

**Observed:** The active tab has a subtle rounded backing; inactive tabs have muted text and no visible backing. Tabs sit in a loose horizontal row above the large demo stage.

**States:** Declared: hover text becomes black at 0.6 alpha.

### Feature tile

**Use:** Repeated small capability explanations.

**CSS:** `background: #f5f5f7; border-radius: 24px; padding: 24px; height: 300px; display: flex; justify-content: center; align-items: center`

**Text style:** `card-heading` — Inter 800 · 24px/1.33 · tracking -0.0083em

**Observed:** This component's painted area is only the illustration well. A bold title and regular description follow outside it; three columns form a calm catalogue.

**Transfer:** Put one tiny UI scene or sculptural metaphor inside, not a full miniature dashboard.

### Benefit card

**Use:** Compact headline-led benefit collections.

**CSS:** `background: #ffffff; border-radius: 24px; box-shadow: rgba(0, 0, 0, 0.08) 0px 4px 16px -8px; overflow: hidden`

**Text style:** `card-heading` — Inter 800 · 24px/1.33 · tracking -0.0083em

**Observed:** Heading sits above a large illustration that can run into the lower edge. Unequal card heights and one blue standout break the otherwise regular structure.

**Transfer:** Use short benefit-led headings and image-led interiors, not dense descriptions.

### Check list item

**Use:** Concrete benefits next to product scenes and inside plan summaries.

**CSS:** `position: relative; padding-left: 35.2px; margin-bottom: 16px; color: #000000`

**Text style:** `body` — Inter 400 · 16px/1.75

**Observed:** A black circular check sits in the left gutter, aligned with the first line. Copy remains normal-weight paragraph text rather than a badge.

**Transfer:** Use for verifiable actions and inclusions.

### Footer link

**Use:** Grouped destination lists at the end of the page.

**CSS:** `display: inline-flex; align-items: center; color: rgba(0, 0, 0, 0.6)`

**Text style:** `footer-link` — Inter 400 · 14px/1.75

**Observed:** Four link columns occupy roughly two thirds of the footer, with small bold group headings. Rows have 24px separation.

**States:** Declared: hover black text with no underline.

### Newsletter input

**Use:** Email subscription beside footer navigation.

**CSS:** `background: rgba(0, 0, 0, 0.04); border-radius: 8px; height: 48px; padding: 16px; margin-right: 8px; box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px 0px`

**Observed:** A quiet field sits beside a compact black Subscribe button beneath one short update sentence. No prominent surrounding form card.

**Transfer:** Keep the signup subordinate to the main page action.

### FAQ row

**Only for:** pricing pages

**Use:** Objection handling in a narrow central column.

**CSS:** `background: #ffffff; position: relative; padding: 32px 48px 32px 0px`

**Text style:** `question` — Inter 700 · 20px/1.2 · tracking -0.005em

**Observed:** An unboxed question sits left with a simple plus at right. A one-line closed row is 88px tall; longer questions wrap naturally.

**Transfer:** Keep closed rows visually spare. Answers should use the regular body recipe.

### Plan card

**Only for:** pricing pages

**Use:** Two clearly separated purchase paths.

**CSS:** `background: #ffffff; border-radius: 24px; box-shadow: rgba(0, 0, 0, 0.08) 0px 4px 16px -8px; display: flex; flex-direction: column`

**Text style:** `question` — Inter 700 · 20px/1.2 · tracking -0.005em

**Observed:** Centered colored plan label, generous price or inheritance summary area, fine divider, checkmarked inclusions and a bottom action. The self-serve plan uses black; the organization plan uses Secondary button. Labels are blue and violet rather than filled badges.

**Transfer:** Preserve the spacious pair and calm comparison; do not highlight a plan with a thick colored outline.

## Imagery and graphics

### Luminous atmosphere

**Use:** Signature opening backdrop and a softer echo at the lower-right footer.

**Observed:** A broad blurry violet core blends into blue and cyan on the right, with warm peach and yellow appearing near the lower-left of the product stage. White feathers into the top and outside edges. The footer is much paler, concentrated in one corner.

**Transfer:** Recreate the light field around an original product scene. Match the soft glow; exact stops are not essential.

**Build:** On an isolated white wrapper, layer oversized radial ellipses: violet centered near 40% 55%, blue near 65% 60%, cyan near 85% 55%, and a smaller peach glow near 5% 85%. Use rgba(114,114,251,0.9), rgba(0,123,255,0.65), rgba(80,205,235,0.65) and rgba(255,160,75,0.65), fading each to transparent over roughly 500px–900px. Blur the layer about 90px and keep white space above. For the footer use only cool ellipses at 0.15–0.35 alpha, clipped to the bottom-right area.

### Oversized interface stage

**Use:** Opening product proof and major demonstrations.

**Observed:** A large near-white desktop window with small toolbar details, sparse screens and connectors, front-facing rather than device-mockup perspective. The opening window is 1224px wide and 726px tall, with a faint shadow and 12px corners. A later presentation uses Violet demo stage.

**Transfer:** Show an actual meaningful task in the new product. Minimum acceptable artwork is a clean original window containing two or three legible objects and their relationship, with a restrained toolbar and ample empty working space.

### Color-rim closeups

**Use:** Long capability explanations.

**Observed:** Large rounded interface excerpts occupy about half the content width; bright cyan, yellow or violet appears as a wide offset rim along one or two sides. UI is white, pale and softly shadowed. Adjacent copy is substantially smaller.

**Transfer:** Use a cropped detail that makes one benefit tangible, with a single colored rim rather than a busy decorative background.

### Pale sculptural UI metaphors

**Use:** Feature wells and benefit cards.

**Observed:** White raised tiles, ghosted phone frames, folders, controls, cursor arrows and speech bubbles sit on very pale gray. Small blue, violet or yellow details are the only saturated parts. Some scenes add tiny circular human portraits.

**Transfer:** Reduce the new capability to two or three UI objects, preserving the low-contrast white-on-gray mass and small colored focal detail.

**Build:** Use rounded white rectangles and simple SVG outlines centered in Illustration well. Add a low-opacity black shadow with a short vertical offset; keep most shapes white or pale gray. Add one small blue control, connector or cursor. For comment scenes layer a white speech bubble with a thin black outline over two faded panels and one or two circular portraits.

### Editorial type accents

**Use:** Selected section headings and social proof.

**Observed:** Audience words sit on white raised label shapes, a pale pencil and a loose drawn stroke sit nearby, and one emphatic word is white on a slanted blue selection-like patch with a cursor.

**Transfer:** Highlight one meaningful word or audience phrase; use a small work-related object rather than a mascot.

**Build:** Wrap a short heading fragment in an inline-block white rounded rectangle with a faint offset shadow. For the energetic variant place a skewed blue quadrilateral behind white text and a small SVG cursor at its lower-right. Keep the rest of the heading black and unadorned.

### Human proof photography

**Use:** Testimonial and customer-story sections.

**Observed:** A grayscale cutout portrait fills a tall capsule beside a large quote. Customer-story photography is also monochrome, showing someone working at a desktop, framed in a wide rounded rectangle; small colored author avatars and a bright geometric corner accent supply warmth.

**Transfer:** Use real customer or user photography with honest attribution; retain monochrome main images and small color details.

### Workplace photo compositions

**Only for:** audience and use-case pages

**Use:** Split openings and teamwork explanations.

**Observed:** Bright natural office photography appears as one rounded landscape image or three tall staggered rounded strips. Later collages overlap two work scenes and a floating pale folder panel; small reaction bubbles can hover over photos.

**Transfer:** Choose believable working contexts and softly lit spaces, not glossy studio team lineups.

### Icons

**Observed:** Interface-adjacent illustrations use small colored controls and cursors; marketing lists use solid black circular checks. Integration marks sit as compact colored logos beside a short caption. Footer social icons are black, about 20px, in a horizontal row.

**Transfer:** Use simple checks and arrows for navigation and benefits. Choose recognizable integration marks only where a real integration exists; decorative outline-icon grids are not a substitute for product scenes.

## Section recipes

How recurring sections are built.

### First screen: Luminous product opening

**Observed:** Back to front: a white-to-colored Luminous atmosphere, Translucent navigation, a centered white display headline, a white lead, Primary button, and an Oversized interface stage. The header is 96px tall; the content begins after 148px of air beneath it. The headline occupies a compact line within a 756px measure; support spans up to 830px, separated by 16px, and the action follows after 32px. Within the first 900px the entire promise, three-line support and action are visible, followed by the top 226px of the 1224px product window beginning at 674px. Most of the demonstration, its caption row and subsequent proof are below the fold.

**Transfer:** Default new marketing pages use this luminous centered opening. Stage an original simplified working canvas if product video is unavailable. Audience and use-case pages instead open with black left-aligned display text, a 20px split lead and an action beside natural workplace photography. Feature and pricing indexes use centered black display text with a 24px muted lead and only a corner glow.

**Avoid:** Do not replace the broad luminous field with a flat purple rectangle, put a tiny floating dashboard beside the default headline, or push all product proof beyond the next screen.

**Text style:** `display` — Inter 800 · 56px/1.14 · tracking -0.0214em

### Heading pair

**Observed:** A 48px Heading or 56px Display sits over a short support paragraph. Centered introductions use a 704px reading measure; left-aligned chapters connect directly to split media. Gaps are 16px–24px.

**Transfer:** State an outcome in the heading, then explain the mechanism in the support. Eyebrows are not needed.

### Tabbed product theater

**Observed:** A centered display promise precedes Mode tabs and Violet demo stage. Major internal gaps are 72px. A product view dominates the section, with a short bold caption and centered muted explanation below; a small floating example action can overlap the lower frame edge.

**Transfer:** Use two or three views of one coherent job, not unrelated feature tabs.

### Large media with narrow explanation

**Observed:** A 664px-wide rounded demonstration sits beside a roughly 408px copy column. Card-heading text, Body paragraphs and occasional compact attributed quotes form the right side; consecutive explanations can share a sticky media region. Main chapters use 156px vertical padding.

**Transfer:** Let the visual demonstrate the operation and let the text explain its value. Alternate orientation in other split sections.

### Asymmetrical benefit collection

**Observed:** A strong left-aligned display heads a 4:5:3 masonry arrangement with 26px gaps. Benefit cards contain compact titles and pale illustrations; a single Blue standout card adds contrast.

**Transfer:** Group benefits by importance and illustration shape rather than forcing every card into an equal height.

### Feature catalogue chapter

**Observed:** Three equal columns pair Illustration wells with bold 24px headings and 16px body descriptions outside the wells. Major categories alternate white and cool near-white backgrounds. On long catalogues a slim sticky category bar sits below the main navigation with an underline on the active category.

**Transfer:** Use this denser chapter format for a complete capability inventory; let the final row remain incomplete if the content calls for it.

### Tactile customer proof

**Observed:** An editorially accented heading leads into a large Quote beside a monochrome portrait in a tall capsule. Small author details follow the quote and pale circular previous/next controls flank the composition.

**Transfer:** Use one strong real statement at a time instead of a wall of tiny testimonials.

### Editorial closing story

**Observed:** The default marketing close is a substantial customer-story block rather than a giant final signup banner: a 32px bold title and Secondary button on the left, a 756px by 548px monochrome working photograph on the right, small author portraits and a blue corner shape. The cool near-white background continues into the block.

**Transfer:** Close on concrete proof or a useful next chapter, then allow the footer to provide navigation and subscription.

### Open footer with corner light

**Observed:** A white footer begins with 128px top padding. Four Footer-heading and Footer-link columns occupy the left two thirds; the right third holds a logo, short update sentence, Newsletter input and black Subscribe action, then social icons lower down. A delicate blue-violet light pool gathers behind the lower-right corner. Small legal links and copyright sit along the bottom edge.

**Transfer:** Preserve the asymmetrical information density and the corner glow. Keep the footer open, not enclosed in a dark card.

### Illustrated onboarding close

**Only for:** audience and use-case pages

**Observed:** One ending uses a near-white band with a 48px heading and three equal columns: large illustrations, uppercase Step labels, short 20px explanations and Primary button under the first step. Another uses a wide office photograph behind an offset white 845px card with three smaller text steps and an action.

**Transfer:** Offer a simple route from interest to first success. Choose either the illustrated row or the photo-backed card; do not combine both into a crowded close.

### Calm purchase and reassurance

**Only for:** pricing pages

**Observed:** A centered promise leads to two Plan cards, followed by low-pressure trial reassurance and a small demo invitation. A three-column checklist inventory, pale logo band, narrow FAQ rows and a soft 811px-wide support card lead into the footer. Pricing subsection headings use Utility-heading rather than the larger marketing heading.

**Transfer:** Separate choosing, checking inclusions and resolving objections. End with a human contact action rather than another sales pitch.

## Page flow

**Storyline:** Promise → visible product proof → credibility → outcome-led capability chapters → deeper proof or practical reassurance → useful next action → open navigation footer.

### Flagship product introduction

1. **promise** — Luminous centered opening and an oversized interactive product canvas.
2. **social proof** — Monochrome customer marks and one quiet trust sentence.
3. **product demonstration** — Tabbed theater followed by color-rim closeups and compact contextual quotes.
4. **capability chapters** — Editorial product-story band, asymmetrical benefit cards and a regular feature grid.
5. **customer proof** — Large portrait quote and a substantial monochrome customer story close.
6. **navigation ending** — Open footer with newsletter and corner light.

**Transfer:** Use the full visual vocabulary to introduce a product, but choose the capability and proof blocks that carry its real story.

### Focused use-case explanation

1. **promise** — Black left-aligned headline beside a rounded workplace image, then monochrome customer marks.
2. **product demonstration** — A simple progress timeline above a large interface view and three explanatory columns.
3. **capability chapters** — Alternating illustration-and-checklist sections with a centered white editorial question card between them.
4. **closing call** — Three onboarding steps on an offset white card over office photography.
5. **navigation ending** — Shared open footer.

**Transfer:** Show how the product resolves one specific job, with a practical start path rather than the flagship's customer-story ending.

### Audience-specific landing page

1. **promise** — Split hero with staggered photo strips, concise support, action and integration marks.
2. **product demonstration** — Selectable use-case list with an active vertical marker beside a large cyan-backed demonstration.
3. **capability chapters** — Large feedback scene, integration orbit and overlapping teamwork photos with checklist copy.
4. **closing call** — Three illustrated onboarding steps on near-white.
5. **navigation ending** — Shared open footer.

**Transfer:** Translate a product's benefits into the working context of one audience without changing the core type or action system.

### Complete capability catalogue

1. **promise** — Simple centered title and support with a warm corner glow.
2. **capability chapters** — Sticky category navigation organizes alternating large split demonstrations and three-column illustrated inventories.
3. **final capability** — A short three-item feedback chapter finishes the inventory without adding a separate conversion banner.
4. **navigation ending** — Shared open footer.

**Transfer:** Organize by workflow stage or user job; retain the pale illustration vocabulary even at higher information density.

### Purchase decision and objection handling

1. **promise** — Centered black promise over a pale cool corner glow.
2. **pricing** — Two spacious white plans, trial reassurance and a small demo invitation.
3. **inclusion proof** — Three-column category checklists followed by a monochrome logo band.
4. **objection handling** — Narrow unboxed FAQ rows with plus controls.
5. **closing call** — Pale centered support card with a black contact action.
6. **navigation ending** — Shared open footer.

**Transfer:** Keep the buying experience lighter and narrower than product storytelling, while preserving the same heavy headings and rectangular buttons.

## Writing

Confident, helpful and mildly playful. The product promises useful improvements, then explains them in concrete workflow terms rather than grand claims about transformation.

**Do not copy:** Do not reuse the brand name, logo, proprietary artwork, customer marks, customer quotes, named people, customer stories, pricing, adoption figures or trial claims. Source examples demonstrate voice only; replace them with truthful content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader with you and your; imperative verbs invite action. Refer to the product by its name in explanatory paragraphs, with occasional we when presenting an opinion.
- **Rhythm:** Short, benefit-led headlines alternate with longer explanatory paragraphs. Actions are terse. Practical questions introduce reassurance; playful phrases appear occasionally, not in every line.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct promise about getting an important job right. | 4–9 words | “User flows done right”<br>“Take control of your next design presentation” |
| Section headline | Lead with a useful outcome, often an imperative. | 3–8 words | “Save time for creativity”<br>“Drive focus to what’s important”<br>“Discover your new superpowers” |
| Supporting explanation | Name the action, then connect it to a reader benefit using concrete product operations. | One to three sentences | “Present your work effectively, engage your team in design critique, and navigate faster through the different steps of product design.” |
| Feature label | Short verb-led phrase explaining what the reader can do. | 2–7 words | “Keep your design files tidy”<br>“Annotate and add context” |
| Primary action | Direct low-friction verb, optionally followed by a qualifier. | 2–5 words | “Start for free”<br>“Explore all features”<br>“Read case study” |
| Reassurance | Answer a real practical question in ordinary language. | One short question or sentence | “Can I cancel my subscription anytime?”<br>“Not seeing your question here?” |

**Words and phrasing to use:** create; share; present; sync; your team; in minutes; get feedback; tell your story; keep; work together

**Avoid:** revolutionary; disruptive; synergize; unparalleled; category-defining; unlock infinite possibilities

**Rules:**

- Let the heading carry the benefit and the paragraph carry the mechanics.
- Use concrete verbs for feature names; reserve the occasional metaphor for major section headings.
- Keep actions specific to the destination: a trial, examples, feature inventory or a story.
- Place low-pressure reassurance near purchase actions and answer practical questions plainly.

## Do's and Don'ts

### Do

- Keep display headings at Inter 56px, weight 800, with -1.2px tracking and 1.14 line height.
- Give major chapters 156px vertical breathing room and keep explanatory text near a 408px measure.
- Keep the main demo near the 1224px inner-container width so the product feels substantial.
- Use 8px corners on 56px actions, with the 48px compact version only in denser utility contexts.
- Put small sculptural illustrations on #f5f5f7 wells and keep their descriptions outside the painted area.
- Keep white benefit cards lightly raised with the 0px 4px 16px -8px shadow at 0.08 black alpha.
- Echo the opening's cool light subtly at the lower-right footer.
- Use one blue gradient benefit card as punctuation within a mostly white collection.

### Don't

- Do not turn the whole long page into alternating saturated rainbow bands; sustained content belongs on white or #fafafc.
- Do not make every action a 9999px capsule; the dominant action shape has 8px corners.
- Do not replace the 800-weight headings with thin fashionable display type.
- Do not put heavy black borders around every white panel; separation is usually tonal or softly shadowed.
- Do not center every text block: detailed capabilities need narrow left-aligned copy beside large media.
- Do not pack full dashboard interfaces into the small feature wells; they use sparse, pale metaphors.
- Do not use huge numeric stats as the default credibility device; quiet logos and human proof carry that role.
- Do not make the footer a dark, high-contrast sales wall; its open white field and corner light are part of the visual finish.

## Motion and responsive

### Motion

**Observed:**

- Actions declare color and background-color transitions of 0.35s, with hover translateY(-2px) and active translateY(-1px).
- Benefit cards declare box-shadow 0.6s cubic-bezier(0.25, 0.1, 0.25, 1).
- Mode tabs declare color transitions; active backing distinguishes the selected product view. The long capability sequence pairs changing media with adjacent explanations.
- A sticky category bar tracks the active feature chapter.

**Transfer:**

- Use the small upward action lift without enlarging buttons.
- Keep demonstration changes local to the large product stage, preserving the surrounding text layout.

**Unknown:**

- Exact scroll choreography, video timing and the timing of illustrative float effects are unspecified.
- No focus-visible treatment is established.

### Responsive

**Observed:**

- Styles declare width breakpoints around 440px, 520px, 768px, 1024px, 1224px and 1920px; the visual baseline is 1440px.

**Transfer:**

- For narrower layouts, stack split media and copy while keeping the product stage substantially wider than the reading column.
- Collapse feature and benefit grids without shrinking the tiny pale objects into illegibility; preserve the single standout blue card.
- Keep the glow behind the promise and the footer glow corner-biased rather than spreading both into flat color fills.

**Unknown:**

- Exact narrow-screen type sizes, navigation behavior, card order and responsive media framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
