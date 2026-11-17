# Svelte — an editorial workshop

## Overview

A welcoming, bookish take on technical marketing, with expressive serif headlines, literary body copy and compact sans-serif navigation. White space and dark ink frame a restrained burnt-orange accent, while a playful industrial illustration and candid photographic collages bring the product down to earth. It suits tools and platforms that want to feel approachable, capable and sustained by real people rather than corporate spectacle.

### Essentials

- Book typography meets utility chrome: DM Serif Display headlines at 54px/1.2 and EB Garamond prose at 22px/1.5 sit beneath Fira Sans navigation at 16px/1.5, all with normal tracking.
- The opening is a physical metaphor, not a dashboard: a 488px-tall full-width scene pairs a two-line, 486px-wide left headline with a substantial object to the right and a conveyor-like path crossing the lower foreground. Make an equivalent product-process illustration part of the design.
- The main action is deliberately unboxed: orange Fira Sans at 20px/1.5, uppercase, followed by a 20px arrow with a 5px gap; small utility buttons alone get 4px corners and beveled edges.
- Color belongs to actions and artwork, not section fills: white is the continuous canvas, #141414 leads and #262626 prose dominate, and #d43008 marks links and thin media progress. Stronger colors are confined to the pictures.
- Proof feels assembled rather than templated: overlap rectangular research or product evidence, and include a layered photographic montage with a large central image, smaller edge images, slight tilts and soft ground shadows. Without people photography, use genuine objects and working contexts instead.
- The ending recognizes the people behind the product: a short centered 22px serif reassurance sits above a 128px-high, three-row grayscale circular portrait field fading into white at both edges, followed by a single centered serif footer line with 100px vertical breathing room.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Burnt orange | `#d43008` | `--color-accent` | action, link, accent | Primary text action, inline links, focus outlines and video progress. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, surface | Continuous page and fixed navigation background. |
| Search gray | `#f2f2f2` | `--color-wash` | surface, border | Search field and upper-left utility button edges. |
| Lower edge | `#ebebeb` | `--color-edge` | border | Lower-right utility button edges and navigation hover rule. |
| Shortcut gray | `#808080` | `--color-hint` | text | Search keyboard shortcut hints. |
| Caption gray | `#666666` | `--color-muted` | text, accent | Photo credit and utility icon silhouettes. |
| Reading ink | `#262626` | `--color-ink` | text, surface | Body copy, navigation and dark dictionary-style labels. |
| Headline ink | `#141414` | `--color-headline` | text | Serif headlines. |

## Typography

- **DM Serif Display** — Hero and section headlines. High-contrast, rounded editorial serif with sturdy, friendly shapes. Font stack: "DM Serif Display", Georgia, serif.
- **EB Garamond** — Explanatory paragraphs, centered reassurance and footer. Literary old-style serif with flowing lowercase and an open reading rhythm. Font stack: "EB Garamond", Georgia, serif.
- **Fira Sans** — Navigation, actions, captions and utility labels. Humanist sans-serif with compact, practical shapes. Font stack: "Fira Sans", -apple-system, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | DM Serif Display | 500 | 54px | 1.2 | normal | Both the opening promise and major section headings; left aligned in the hero and centered in later chapters. |
| body | EB Garamond | 400 | 22px | 1.5 | normal | Explanatory prose, inline links, centered support lines and final footer. |
| primary-action | Fira Sans | 400 | 20px | 1.5 | normal, uppercase | Main text-only conversion action. |
| utility | Fira Sans | 400 | 16px | 1.5 | normal | Navigation, media links, definition gloss and photo credits. |

**Notes:**

- Use the same headline recipe for the hero and section leads rather than introducing a huge separate display tier.
- Keep tracking normal throughout. The serif-to-sans change, alignment and whitespace do the hierarchy work.
- Body links retain the serif recipe; media credits and navigation remain sans-serif. Headline copy is mostly lowercase, while the primary action uses uppercase.

## Layout

**Density:** Airy chapters with dense, useful navigation; large media is separated by white space rather than card boundaries.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Arrow and utility icon cluster gaps. |
| 10px | Tight flex gaps and media wrapper margins. |
| 16.5px | Paragraph separation, half a body line. |
| 40px | Two-column gap and separation around explanatory content. |
| 48px | Desktop container inner side padding and wide-media outer gutters. |
| 100px | Top and bottom padding on major media and closing sections. |

### Containers and grids

- **reading container**: max width 1200px · side padding 48px. Centered, border-box container yielding 1104px of usable width at desktop; aligns hero text, explanatory content and video.
- **explanation pair**: 2 columns · gap 40px. Equal columns of about 532px: prose on the left and overlapping evidence images on the right, with a definition strip spanning above.
- **wide media**: max width 2000px · side padding 48px. Collage spreads almost edge to edge, yielding 1344px of media width at the desktop reference size.
- **reassurance measure**: max width 594px · side padding 48px. Centered two-line statement immediately before the portrait field.

## Corner radius

| Element | Radius |
| --- | --- |
| utility controls and media | 4px |
| search field | 56px |
| portraits | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| media grounding | `5px 5px 10px rgba(0, 0, 0, 0.2)` | Soft ground shadow on the video frame; photographic overlaps use a similarly soft visual grounding rather than raised UI cards. |

### Surfaces

#### Paper canvas · level 0

**Use:** All editorial chapters.

**CSS:** `background: #ffffff; color: #262626`

**Observed:** Sections remain continuous rather than switching alternating colored bands.

**Transfer:** Let imagery provide localized atmosphere while maintaining the white reading surface.

#### Fixed navigation paper · level 1

**Use:** Compact persistent site chrome.

**CSS:** `background: #ffffff; position: fixed; z-index: 101`

**Observed:** A subtle fading gray veil below the bar is made with a linear gradient from rgba(0, 0, 0, 0.05) to transparent.

**Transfer:** Use only this understated separation between chrome and the content beneath it.

#### Media frame · level 1

**Use:** Wide documentary or product video.

**CSS:** `border-radius: 4px; overflow: hidden; filter: drop-shadow(rgba(0, 0, 0, 0.2) 5px 5px 10px)`

**Observed:** The image carries its own dark tones; there is no surrounding colored panel.

**Transfer:** Frame the media itself, not a larger card containing a title and description.

## Components

### Fixed navigation

**Use:** Persistent access to the product's learning and reference destinations.

**CSS:** `display: grid; position: fixed; grid-template-columns: auto 1fr 1fr; height: 60px; padding: 0 48px; background: #ffffff; z-index: 101`

**Text style:** `utility` — Fira Sans 400 · 16px/1.5

**Observed:** Brand mark sits at left, a compact row of links follows, and search, social icons and small preferences controls align right.

**Transfer:** Keep the bar utilitarian and single-row on desktop, with a clear separation between destinations and tools.

### Navigation link

**Use:** Compact destination links inside the fixed bar.

**CSS:** `display: flex; align-items: center; height: 60px; padding: 1px 8px 0; color: #262626`

**Text style:** `utility` — Fira Sans 400 · 16px/1.5

**Observed:** Some items include a small downward chevron; links have no filled background.

**States:** Declared: hover underline and inset 0 -1px 0 0 #ebebeb shadow; focus-visible outline 2px solid #d43008 with 4px border radius.

### Primary text action

**Use:** The main opening conversion.

**CSS:** `display: flex; align-items: center; gap: 5px; color: #d43008; background: transparent; text-transform: uppercase`

**Text style:** `primary-action` — Fira Sans 400 · 20px/1.5 · uppercase

**Observed:** A right-pointing outline arrow follows the label. There is no enclosing button silhouette.

**States:** Declared: hover underline; focus-visible outline 2px solid #d43008 with 4px border radius.

### Inline prose link

**Use:** Community, support and explanatory links within sentences.

**CSS:** `color: #d43008; background: transparent`

**Text style:** `body` — EB Garamond 400 · 22px/1.5

**Observed:** The link remains part of the serif sentence, rather than becoming a separate chip or button.

**States:** Declared: hover underline; focus-visible outline 2px solid #d43008 with 4px border radius.

### Search capsule

**Use:** Compact search inside navigation.

**CSS:** `width: 190px; height: 34px; background-color: #f2f2f2; border-radius: 56px; padding: 7px 7px 5.6px 28px`

**Observed:** A small pale search icon sits inside the left edge and a keyboard shortcut hint aligns right.

**Transfer:** Reserve the capsule shape for search rather than repeating it on every action.

### Raised utility control

**Use:** Small display-preference toggles.

**CSS:** `width: 32px; height: 32px; border-style: solid; border-width: 1px 2px 2px 1px; border-color: #f2f2f2 #ebebeb #ebebeb #f2f2f2; border-radius: 4px`

**Observed:** Icon-only square controls use a restrained bevel rather than a drop shadow.

**States:** Declared: hover border-color #ebebeb #dbdbdb #dbdbdb #ebebeb; focus-visible outline 2px solid #d43008 with 4px border radius; active border-color #dbdbdb #ebebeb #ebebeb #dbdbdb and border-width 2px 1px 1px 2px.

### Photo credit

**Use:** Attribution immediately beneath a wide collage.

**CSS:** `color: #666666; text-align: center`

**Text style:** `utility` — Fira Sans 400 · 16px/1.5

**Observed:** The prefix is plain, and the photographer name is underlined; the caption is modest rather than a prominent label.

**States:** Declared: hover underline on the attribution link; focus-visible outline 2px solid #d43008 with 4px border radius.

### Editorial footer

**Use:** Simple final legal and stewardship line.

**CSS:** `padding: 100px 0; color: #262626; text-align: center`

**Text style:** `body` — EB Garamond 400 · 22px/1.5

**Observed:** One centered sentence, with one orange inline link, closes the white page. No sitemap columns or oversized closing sales panel.

**Transfer:** Use the product's actual legal or ownership information at normal reading size.

## Imagery and graphics

### Industrial process scene

**Use:** Signature opening image.

**Observed:** A low oblique 3D view shows a metallic conveyor crossing the full width and bending into an orange-red machine on the right. Small irregular gray inputs become tidy orange parcels. White sculptural shapes, metallic perforations, soft contact shadows and a pale blue-gray studio floor make a technical process feel tangible. The upper left stays open for text.

**Transfer:** Turn the product's transformation into a small physical workshop with recognizable input, central apparatus and output. A minimum version uses a simple extruded geometric device and a curved pathway rather than a branded sculptural asset.

**Build:** Create a full-width SVG or 3D-rendered composition with a cool near-white floor fading into the page. Run a gray path from the lower-left edge through a large rounded machine on the right and out toward the upper-right edge. Layer gray rectangular rails, small perforation dots and irregular input solids; give the machine orange-red translucent walls and a white extruded top. Add broad blurred black contact shadows at low alpha underneath the apparatus and belt. Keep the top-left third unoccupied; use the brand accent for the apparatus and outputs, not the whole background.

### Overlapping evidence sheets

**Use:** Visual proof alongside introductory prose.

**Observed:** Light and dark research panels overlap in a slightly skewed stack to the right of the text. Rectangular edges and soft shadows suggest documents placed on a desk; interface details are subordinate to the overall stack.

**Transfer:** Layer two or three authentic product results, independent reviews or workflow panels. Keep enough legible context to establish what each artifact proves.

### People montage

**Use:** Signature human-scale proof graphic.

**Observed:** A large central group photograph anchors a wide collage. Smaller candid shots of talks, conversation and working sessions rise above it and overlap its side edges with slight rotations. Natural color, uneven image sizes and soft shadows feel handmade rather than like uniform testimonial cards.

**Transfer:** Use real customer, team or working-context photographs. If a people archive is unavailable, assemble genuine process and artifact photographs with one wide central scene and smaller contextual details.

**Build:** Use a wide relative-positioned figure. Place one landscape photograph across roughly the central three quarters of its width, aligned near the lower edge. Place a shallow row of smaller rectangular photographs behind its upper edge and two or three taller images around the left and right sides. Vary rotations by a few degrees, overlap edges without decorative borders and add soft low-opacity ground shadows. Keep white visible around the irregular silhouette, then place Photo credit below.

### Portrait field

**Use:** Closing reassurance and collective proof.

**Observed:** Three tight rows of small circular portraits and organization marks span beyond both viewport edges. Images are grayscale and softly fade to white at the edges. The whole field is 128px high and reads as a texture of contributors rather than individually labeled cards.

**Transfer:** Use legitimate portraits or customer marks to express a real supporting ecosystem; do not fabricate an apparent roster. For a new product, a smaller genuine set can repeat as a clearly decorative field.

**Build:** Create three staggered horizontal rows in a full-width overflow-hidden wrapper. Clip images to circles, apply grayscale and use tight regular gaps. Layer white-to-transparent horizontal gradients at both ends, or apply a mask with transparent edges and an opaque center. Keep the total band height at 128px and omit visible name labels.

### Icons

**Observed:** Navigation chevrons and action arrows are 20px outline SVGs with 2px round strokes, colored with the adjacent text. Social and preference icons are small gray silhouettes or simple glyphs.

**Transfer:** Choose a consistent rounded stroke set for directional actions, and reserve filled silhouettes for recognized utility or social symbols.

## Section recipes

How recurring sections are built.

### First screen: Workshop opening

**Observed:** A 60px Fixed navigation sits above a 488px full-width illustrated hero. The display headline occupies a 486px measure on the left, wraps to two lines and leaves the right half to the main machine. Its top is about 95px below the hero's top; the Primary text action follows with 37px of visual separation. Layers run from pale studio floor to the conveyor path and right-hand object, then the dark headline and orange action. The path sweeps through the lower foreground without crossing the words. Within the first 900px, the whole hero, the definition strip and the upper introductory prose and overlapping evidence are visible. Later proof and video remain below the fold.

**Transfer:** Create a product-specific physical transformation scene, keeping the upper-left text area clear and the main object to the right. Without 3D production, use the simplified SVG workshop recipe with genuine input/output artifacts. Other informational page types can begin with the same serif promise and restrained action, using a smaller contextual illustration instead of a dense product dashboard.

**Avoid:** Do not center a giant headline over a busy full-bleed photograph, or replace the physical scene with a large rounded software-window card.

**Text style:** `display` — DM Serif Display 500 · 54px/1.2

### Definition and explanation pair

**Observed:** A reading container holds a baseline-aligned strip: an orange pronunciation-style word graphic, a small dark part-of-speech label and a sans-serif gloss. Below it, explanation pair places 22px serif prose beside Overlapping evidence sheets, with a 40px grid gap. Paragraphs are separated by 16.5px.

**Transfer:** Introduce a useful product concept with a short definition or plain-language translation, then connect it to tangible proof rather than a generic feature-card grid.

### Surrounded proof headline

**Observed:** A centered 54px serif headline is flanked by recognizable customer logos about 40px tall, arranged as a wide horizontal proof ribbon with some content extending beyond the viewport.

**Transfer:** Use a short conversational confidence statement surrounded by a real set of endorsing organizations. Keep logos visually subordinate to the headline.

**Text style:** `display` — DM Serif Display 500 · 54px/1.2

### Wide media chapter

**Observed:** A Media frame spans 1104px of usable reading-container width, with 100px section padding above and below. The video is panoramic, about 1104px by 469px, with a thin orange progress indicator and a small left-aligned orange sans-serif viewing link beneath.

**Transfer:** Give a demonstration, origin story or customer story enough uninterrupted width to hold attention. Preserve the caption-like action rather than surrounding it with more promotional copy.

### People-led invitation

**Observed:** A centered display headline leads a two-line serif support paragraph with orange links, separated by about 16px. People montage then expands to the wide media gutters, with Photo credit centered underneath and generous white margins.

**Transfer:** Use this chapter to move from functional proof to real human participation, collaboration or usage. Preserve the montage's irregular silhouette and image-size hierarchy.

**Text style:** `display` — DM Serif Display 500 · 54px/1.2

### Collective reassurance ending

**Observed:** A centered two-line reassurance uses a 594px measure including side padding. Portrait field follows beneath it; Editorial footer closes with one serif line and 100px top and bottom padding.

**Transfer:** End by answering who sustains the product and why it can be trusted, then state essential ownership or legal details. The human texture carries the emotional close instead of a last oversized conversion button.

## Page flow

**Storyline:** approachable promise → plain-language explanation and evidence → recognizable adoption → immersive story → human invitation → continuity reassurance → simple legal close

### Marketing landing page that makes a technical product approachable and trustworthy

1. **Promise** — Two-line editorial headline and a single orange text action over a physical process illustration.
2. **Explanation and product proof** — Dictionary-like introduction, readable serif paragraphs and overlapping external evidence.
3. **Social proof** — A conversational centered headline surrounded by recognizable logos.
4. **Immersive story** — A large panoramic video with a small viewing link.
5. **Human invitation** — Centered heading and support line above a layered photographic montage.
6. **Continuity reassurance** — Short support statement and grayscale portrait field establish the people sustaining the product.
7. **Legal close** — One centered serif sentence with an inline orange link.

**Transfer:** Adapt the narrative to the product's strongest evidence and available media. Retain the contrast between a playful process scene, bookish explanation and genuine human proof, without requiring every chapter in the same order.

## Writing

Warm, unpretentious and quietly confident. Technical specificity coexists with affection and conversational invitations; proof is introduced as something readers can judge for themselves.

**Do not copy:** Do not reuse the Svelte name, logo sculpture, pronunciation artwork, customer roster, event images, research rankings, endorsement claims or source-specific legal and funding claims. Replace them with the new product's own truthful assets and facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you in explanations and invitations. Use our for community relationships, and refer to the product by name when explaining what it is.
- **Rhythm:** Short lowercase headlines of roughly four to eight words lead much longer, flowing explanatory sentences. A brief emotional sentence can punctuate technical prose; action labels stay compact.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the activity and make it feel inclusive rather than elite. | 8 words | “web development for the rest of us” |
| Explanation | Define what the product is and connect the mechanism to a useful result, then add a warmer short sentence. | One substantial sentence plus a short aside | “It’s a love letter to web development.” |
| Proof heading | Use familiar conversational language instead of institutional social-proof jargon. | 7 words | “used by companies you’ve heard of” |
| Invitation | A direct friendly verb and a human benefit. | 5 words | “join our friendly community” |
| Primary action | Simple verb phrase, made uppercase through styling. | 2 words | “get started” |

**Words and phrasing to use:** you already know; join; friendly; for the rest of us; plain technical nouns; concrete process verbs

**Avoid:** revolutionary; enterprise-grade synergy; dominate; 10x everything; manufactured urgency

**Rules:**

- Explain the mechanism before listing abstract benefits.
- Introduce proof in conversational language and let concrete results do the selling.
- Use contractions and restrained affection rather than slogans packed with superlatives.
- Embed relevant destinations in normal sentences instead of creating a separate button for every link.

## Do's and Don'ts

### Do

- Use 54px/1.2 DM Serif Display for both opening and major section headings.
- Keep paragraphs at 22px/1.5 EB Garamond, including the final footer line.
- Use 16px/1.5 Fira Sans for navigation and captions.
- Keep the main action text-only, uppercase and orange with a 20px arrow.
- Anchor normal content in a 1200px container with 48px inner side padding.
- Give major media chapters 100px top and bottom padding.
- Use 4px corners and subtle directional edges on small square utility controls.
- Use grayscale circular images and white edge fades for the 128px closing portrait field.

### Don't

- Do not turn the whole page orange; reserve #d43008 for actions, links and localized visual accents.
- Do not replace literary body copy with a default 16px sans-serif paragraph system.
- Do not tighten headline tracking or apply all-caps to editorial headings.
- Do not make every link a pill: the 56px radius belongs to search.
- Do not surround each proof artifact with a bordered feature card; overlap the actual evidence images.
- Do not round photographic collage images into uniform tiles.
- Do not use dark alternating chapter backgrounds; dark areas belong inside media.
- Do not shrink the final legal line into tiny muted fine print; it retains the 22px serif recipe.

## Motion and responsive

### Motion

**Observed:**

- The video progress indicator declares a height transition of 0.2s.
- Links declare underline on hover and a 2px orange focus-visible outline.
- Other action and media declarations include opacity 0.2s, filter 0.2s and filter/scale 0.2s ease.

**Transfer:**

- Keep hover behavior typographic on links and tactile on small beveled preference buttons.
- Confine media-specific transitions to the media and controls rather than imposing animated section entrances.

**Unknown:**

- Precise triggers and correspondence of the other transition declarations to visible effects are not established.
- Timing of any conveyor or portrait-field movement is not established.

### Responsive

**Observed:**

- The desktop composition uses a 60px fixed header, 1200px normal containers and 2000px wide-media containers.

**Transfer:**

- On narrow screens, stack the explanation pair and preserve a clear text area above or beside the simplified workshop scene.
- Scale the collage as one composition so the central image remains dominant; keep the portrait field edge-to-edge and clipped.
- Reduce utility chrome before allowing the navigation to crowd the reading area.

**Unknown:**

- Mobile breakpoints, navigation behavior and viewport-relative type scaling are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
