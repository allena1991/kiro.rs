# MindMarket — exuberant human ribbons

## Overview

An exuberant, people-first style that makes serious services feel approachable rather than corporate. Cream and warm stone grounds alternate with spring green and a vivid yellow finale, while tightly packed grotesk headlines sit beside loose, oversized cartoon characters. Flat illustration carries the personality; natural portraits and contextual photography bring credibility. The overall density is airy and theatrical, with compact passages of explanation.

### Essentials

- Headlines feel like friendly typographic posters: Inter 500, 139.7px/0.95 with -0.06em tracking for the opening and closing statements; 80.8px/0.95 for major section leads.
- The opening is a green stage rather than a boxed hero: a centered two-line promise, a 29.8px support line separated by 51px, and a large playful illustration rising from below the first 900px. A floating white navigation bar carries the first conversion action.
- Actions are little rectangular containers with a round companion: 10px corners, 10.6px padding and a 43px colored circle holding a thin arrow; ordinary buttons are about 66px tall, not pills.
- Color comes in big cheerful chapters, not a constant rainbow: cream and stone carry the long explanatory stretches; spring green owns the opening and major invitation, yellow owns the closing panel, and coral, blue and lilac punctuate art and individual actions.
- Illustration escapes its box: oversized flat-color people, dramatically foreshortened hands and shoes, small clouds and confetti follow broad green ribbons around white text cards. Every new landing page needs an expressive illustrated scene; a simple custom vector figure and looping ribbon is the minimum substitute.
- A wave is a recurring mark of emphasis: underline one meaningful word with a thick lilac, green or yellow sine-wave strip, and repeat the gesture beneath the monumental two-line closing invitation.
- Proof has physical scale: 424×550px stat cards with 50px corners and 144px numerals, plus edge-clipped rails of 106px-tall cream identity capsules. Retain a large proof device and a bright yellow closing invitation rather than ending with a small conventional footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Spring green | `#8ed462` | `--color-green` | background, accent, action | Opening stage, large invitation bands, illustration ribbons and circular action accents. |
| Electric yellow | `#f5e211` | `--color-yellow` | background, action, accent | Closing panel, carousel controls, numbering and selected feature actions. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral | `#ff705d` | `--color-coral` | surface, accent, action | Illustrated clothing, a proof card, feature actions and required-field marks. |
| Sky blue | `#2ba0ff` | `--color-blue` | surface, accent, action, text | Illustration, circular badges, feature actions and the white proof card's numerals. |
| Soft lilac | `#ebc1ff` | `--color-lilac` | accent, action | Wavy word emphasis, illustration and a feature action. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | surface, text, border | Floating navigation, text cards, form fields and inverse text on colored proof cards. |
| Cream | `#f5f1e4` | `--color-canvas` | background, surface | Default reading canvas and identity capsules. |
| Warm stone | `#e0dbce` | `--color-stone` | background, surface, border | Secondary chapters, editorial links, accordion surfaces and fine comparison dividers. |
| Stone edge | `#c2bcad` | `--color-rule` | border | Single-pixel separators between long editorial or catalogue chapters. |
| Muted charcoal | `#80827f` | `--color-muted` | text | Secondary contact information uses charcoal at 60% opacity, yielding this neutral over white; it takes on the underlying panel's hue over colored surfaces. |
| Warm charcoal | `#2c2e2a` | `--color-ink` | text | Main headings and prose throughout. |
| Action black | `#000000` | `--color-black` | text | Action labels and arrow strokes; keep warm charcoal for main prose. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| network or ecosystem storytelling pages | Orchid stage | `#f4acff` | `--color-pink-stage` | background | Full illustrated opening background. |

## Typography

- **Inter** — All headings, prose, navigation, numbers and labels. Contemporary grotesk with open counters and a high x-height; medium weight and unusually tight tracking create a compact, friendly editorial voice. Font stack: "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| stat | Inter | 400 | 144px | 0.95 | -0.06em | fixed | Oversized proof numerals. |
| display | Inter | 500 | 139.7px | 0.95 | -0.06em | size 9.7vw | Opening promise, major invitation and monumental closing line. |
| heading-lg | Inter | 500 | 80.8px | 0.95 | -0.06em | fixed | Major narrative section leads and compact service or contact openings. |
| heading | Inter | 500 | 53.1px | 1.15 | -0.06em | fixed | Centered proof headings and statement-length editorial passages. |
| heading-sm | Inter | 500 | 40.4px | 1.2 | -0.06em | fixed | Feature-card headlines, catalogue chapter titles and long-form section headings. |
| lead | Inter | 500 | 29.8px | 1.2 | -0.06em | fixed | Hero support line, substantial section introductions and process-card titles. |
| body | Inter | 500 | 20.2px | 1.25 | -0.04em | fixed | Main paragraphs and feature-card descriptions. |
| body-sm | Inter | 500 | 18.1px | 1.25 | -0.04em | fixed | Navigation labels, compact explanatory copy and embedded story titles. |
| button | Inter | 500 | 18.1px | 1.5 | normal | fixed | Conversion and section-navigation actions. |
| contact-detail | Inter | 500 | 18.1px | 1.25 | normal | fixed | Secondary addresses and hours in the closing panel. |
| utility | Inter | 500 | 17px | 1.5 | normal | fixed | Footer links, copyright and compact in-page navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| long-form service explainers | accordion-title | Inter | 500 | 25.5px | 1.2 | -0.06em | fixed | Question titles and key-takeaway headings. |
| contact and enquiry forms | form-label | Inter | 500 | 16px | 1.5 | normal | fixed | Labels above white form fields. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display and heading recipes retain -0.06em tracking even at smaller heading sizes. Main prose and compact editorial labels relax to -0.04em; buttons and utility links use normal tracking.
- Hierarchy is made through scale and composition rather than bold weight, uppercase eyebrows or additional font families.
- Wave-underlined words retain the same type weight and ink as the surrounding headline. The color belongs beneath the word, not in the letters.

## Layout

**Density:** Airy theatrical sections with compact text blocks, broad intervals between narrative moments, and close-knit controls.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8.5px | Button label-to-icon gap and small inline groups. | fixed |
| 10.6px | Button padding and form-label separation. | fixed |
| 17px | Identity-rail row gaps and navigation top inset. | fixed |
| 20px | Grid gutters and outer container padding. | fixed |
| 26.6px | Feature-card content gaps. | fixed |
| 34px | Proof and carousel card padding; form row gaps. | clamp(25.5px, 22.5px + 0.8696vw, 34px) |
| 51px | Opening headline-to-support gap. | fixed |
| 85px | Section internals, figure spacing and closing-panel row gaps. | fixed |
| 136px | Top padding of proof and closing chapters. | fixed |
| 170px | Major chapter padding and closing space after proof. | fixed |

### Containers and grids

- **page grid**: max width 1440px · 16 columns · gap 20px · side padding 20px. Desktop composition uses sixteen columns inside the viewport. Main text and navigation occupy the inner fourteen columns, about 1223px wide with side insets near 109px.
- **split narrative**: 2 columns · gap 20px. Unequal text and media balance: large left heading, compact right paragraph; proof uses roughly 690px of left content beside a 424px card stack.
- **reading column** (only for service explainers and contact forms): max width 690px. Long-form content sits right of a persistent left context rail. Contact forms use the same width centered on the page.
- **process grid** (only for process and company storytelling): 3 columns · gap 20px. White numbered process cards arranged as a staggered three-column group.

## Corner radius

| Element | Radius |
| --- | --- |
| chapter panels and proof cards | 50px |
| feature cards and buttons | 10px |
| carousel cards and photographs | 20px |
| identity capsules | 63.8px |
| icon companions | 50% |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default reading ground.

**CSS:** `background: #f5f1e4; color: #2c2e2a`

**Observed:** Large calm fields let the illustrated sequence and occasional colored chapter dominate.

**Transfer:** Use as the main connective material between high-color moments.

#### Stone chapter · level 0

**Use:** Editorial, comparison and catalogue chapters.

**CSS:** `background: #e0dbce; border-radius: 50px; box-shadow: none`

**Observed:** Full-width rounded bands read as stacked sheets rather than floating cards.

**Transfer:** Group substantial related content inside one band; do not give every paragraph its own panel.

#### Green stage · level 0

**Use:** Default marketing opening and large mid-page invitation.

**CSS:** `background: #8ed462`

**Observed:** Flat uninterrupted color beneath charcoal text and colorful illustration. The later invitation closes with rounded lower corners.

**Transfer:** Reserve the largest green fields for the promise and invitation.

#### White tile · level 1

**Use:** Explanatory text over artwork.

**CSS:** `background: #ffffff; border-radius: 10px; box-shadow: none`

**Observed:** White cards remain opaque against complex illustration; colored backing layers participate in their entrance.

**Transfer:** Let opacity and silhouette separate text from art without borders or blur.

#### Yellow finale · level 0

**Use:** Closing invitation and site footer.

**CSS:** `background: #f5e211; border-radius: 50px; padding-top: 136px; padding-bottom: 38.3px`

**Observed:** The closing chapter is a full-width luminous flat panel, not a dark footer.

**Transfer:** Keep the invitation, useful navigation and contact details together on this colored ground.

## Components

### Floating navigation

**Use:** Persistent desktop orientation and conversion.

**CSS:** `display: flex; justify-content: space-between; align-items: center; background: #ffffff; border-radius: 10px; padding-left: 17px; padding-right: 10.6px; height: 68px`

**Text style:** `body-sm` — Inter 500 · 18.1px/1.25 · tracking -0.04em

**Observed:** A broad white logo-and-links bar sits beside a separate white conversion tile with a small illustrated round face. The whole assembly is fixed 17px from the top, aligned to the inner content grid, with a 20px gap. A green circular two-line menu control remains visible alongside the desktop links.

**Transfer:** Keep the split silhouette and round playful action accent; use the new product's identity in the left slot.

### Primary button

**Use:** Main conversion and sectional navigation.

**CSS:** `display: inline-flex; align-items: center; gap: 8.5px; padding: 10.6px; background: #ffffff; color: #000000; border: 1px solid transparent; border-radius: 10px; min-height: 66px`

**Text style:** `button` — Inter 500 · 18.1px/1.5

**Observed:** Text comes first, followed by a 43px round green companion carrying a 21px right arrow. The white surface is the default on cream or colored bands; feature cards invert the pairing to a coral, yellow, blue or lilac rectangle and a white circle. The closing version uses a yellow circle. The navigation action uses an illustrated face instead of an arrow.

**States:** Declared: hover color #000.

**Transfer:** Use a short verb-led label; preserve the rectangular body plus circle rather than converting the whole action into a capsule.

### Feature story tile

**Use:** Benefit explanation placed within an illustrated scene.

**CSS:** `display: flex; flex-direction: column; gap: 26.6px; padding: 53.1px; background: #ffffff; border-radius: 10px; max-width: 513px`

**Text style:** `heading-sm` — Inter 500 · 40.4px/1.2 · tracking -0.06em

**Observed:** Heading, body paragraph and a color-paired Primary button share a left edge. Tiles alternate across the page instead of forming a uniform grid, allowing large figures and ribbons to pass behind them.

**Transfer:** Pair one short benefit with one explanatory paragraph and one relevant onward action.

### Proof card

**Use:** Quantified credibility as a large visual object.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #ffffff; color: #2ba0ff; border-radius: 50px; padding: 34px; width: 424px; min-height: 550px`

**Text style:** `stat` — Inter 400 · 144px/0.95 · tracking -0.06em

**Observed:** A 64px circular symbol sits upper-right, a huge regular-weight numeral occupies the main field, and a short explanation anchors the bottom. The first card is white with blue text; later cards are green or coral with white text. A right-hand sticky stack creates a layered, slightly tilted visual rhythm beside a left introduction.

**Transfer:** Use verified figures for the new product and retain the oversized, almost poster-like card treatment.

### Identity capsule

**Use:** Continuous social-proof rails.

**CSS:** `display: flex; align-items: center; gap: 21.3px; background: #f5f1e4; border-radius: 63.8px; padding: 21.3px 42.5px 21.3px 21.3px; height: 106px`

**Text style:** `body` — Inter 500 · 20.2px/1.25 · tracking -0.04em

**Observed:** A round white icon well precedes a name. Several rows run beyond the viewport edges on a stone ground, with 17px between rails and capsules.

**Transfer:** Use real customer, integration or partner identities. Keep a mix of capsule widths driven by labels.

### Editorial footer link

**Use:** Compact useful navigation in the closing panel.

**CSS:** `color: #2c2e2a; text-decoration: none`

**Text style:** `utility` — Inter 500 · 17px/1.5

**Observed:** Links form two short unboxed columns above the contact details, with 6.4px vertical gaps.

**States:** Declared: hover text-decoration-line underline.

### Benefit carousel card

**Only for:** company and ecosystem storytelling

**Use:** Multiple comparable advantages within a horizontally clipped rail.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 17px; padding: 34px; background: #ffffff; border-radius: 20px; min-height: 500px`

**Text style:** `heading-sm` — Inter 500 · 40.4px/1.2 · tracking -0.06em

**Observed:** About 397px wide with 16px between cards. The heading sits high, explanatory body low, leaving a deliberately broad center. Three full cards and part of the next are visible; circular yellow previous/next controls sit above at the right.

**Transfer:** Use for a small set of distinct advantages rather than dense technical features.

### Enquiry field

**Only for:** contact and enquiry forms

**Use:** Lead-generation forms.

**CSS:** `background: #ffffff; border: 1px solid #ffffff; border-radius: 10px; padding: 0px 15px; height: 64px`

**Text style:** `form-label` — Inter 500 · 16px/1.5

**Observed:** Labels sit above fields, with small coral required markers. Full-width name and email rows lead into paired shorter fields and a 250px-tall textarea with 10px vertical padding. The form uses a 690px centered column, 20px column gutters and 34px row gaps.

**Transfer:** Keep labels visible and use a larger free-text field for the reader's challenge.

### Question accordion

**Only for:** long-form service explainers

**Use:** Scannable objection handling near the end of detailed explanations.

**CSS:** `background: #e0dbce; border-radius: 10px; margin-bottom: 5px`

**Text style:** `accordion-title` — Inter 500 · 25.5px/1.2 · tracking -0.06em

**Observed:** The summary is a 690px-wide row, at least 74px tall, with left-aligned question and a small white circular plus at right. Inner spacing is 15.9px vertically, 21.3px left and 10.6px right; longer questions wrap.

**Transfer:** Use real buyer questions. Preserve the compact stack and single circular disclosure cue.

## Imagery and graphics

### Exuberant vector scene

**Use:** The principal personality device in openings and feature storytelling.

**Observed:** Joyful flat-color people with huge hands, shoes and expressive faces tumble across the page. Clothing uses blue, yellow, coral, lilac and green; varied skin tones and thin charcoal contour details keep the cast human. Figures overlap cream or green grounds without rectangular frames. White clouds, tiny dots and squiggles occupy the surrounding air.

**Transfer:** Create a bespoke human metaphor for the new product: people cooperating, exploring or enjoying an outcome rather than literal software screens. Minimum version: one expressive vector figure with an oversized gesture, two simple props and several floating accents, anchored to a broad looping ribbon.

**Build:** Use SVG groups for rounded body shapes and disproportionately large hands or shoes. Fill broad shapes with the palette colors, add sparse 1–2px charcoal detail paths, and place small white cloud silhouettes and colored comma-like squiggles around them. Stage one main group roughly 700px wide rising from the lower third of the opening, with edges allowed beyond the viewport.

### Looping narrative ribbon

**Use:** Connect illustrated benefit moments into a continuous visual journey.

**Observed:** An enormous green strip curls through cream space behind white tiles and characters, sometimes crossing the full page width. It is smooth and solid, not textured; the overall path has generous bends rather than angular connectors.

**Transfer:** Use a ribbon to lead the eye between independent content beats. Keep tiles readable in front and allow art to overlap the ribbon.

**Build:** Draw a long SVG cubic Bézier path with no fill, a 200–350px green stroke and round joins. Curve it from one side of the page to the other in broad loops. Place it behind white tiles and in front of the cream canvas; put figures on selected turns. Avoid short repeated identical loops.

### Wave underline

**Use:** Emphasize one word in a section heading and the closing invitation.

**Observed:** A chunky flat sine-wave band follows the word width just beneath the baseline. Smaller headlines often use lilac or yellow; the large closing line uses green. It is clearly separate from the text, with multiple broad undulations.

**Transfer:** Underline the emotionally meaningful word, not every line or every heading.

**Build:** Create an SVG strip with matching upper and lower sine-like paths separated by 8–12px for section titles and about 20px for the large closing display. Repeat broad curves across the word width, fill with lilac, yellow or green, and position directly below the letters. Scale horizontally with the word while keeping the band visibly thick.

### Human and contextual photography

**Use:** Credibility within editorial sections and catalogue chapters.

**Observed:** Warm natural-light portraits, collaborators, real consumer environments and recognizable city scenes. Images have full photographic color rather than a duotone wash, with rounded 20px corners. Service articles use wide images around 690×388px, catalogue rows pair text with approximately 557×371px photographs, sometimes gently rotated.

**Transfer:** Use people and environments tied to the new product's real use. Preserve warm light and honest detail rather than cold office stock imagery.

### Portrait constellation

**Only for:** company and team pages

**Use:** Humanize an organizational opening and a later community chapter.

**Observed:** Small rounded portraits float around the central display title on cream. Later, circular 106px portraits form continuous rails. Named team members receive enormous centered names accompanied by playful illustrated avatars rather than standard headshot cards.

**Transfer:** Use a diverse set of real portraits around a compact statement; give key people a distinctive illustrated scene only on team-focused pages.

**Build:** Arrange independent rounded portrait images around the outer edges of the opening, leaving a clear central text zone. For the community treatment, mask portraits to circles and repeat in horizontally clipped rows with varied starting offsets.

### Process loop

**Only for:** process storytelling

**Use:** Large graphic transition between a monumental statement and process cards.

**Observed:** A broad blue loop sweeps across stone, wrapping around a centered portrait and intersecting the two-sided display phrase.

**Transfer:** Make the loop express continuity or support around a relevant human or product detail.

**Build:** Use a single open SVG ellipse-like cubic path with a thick blue stroke around 150px, extending beyond the sides of the viewport; put a 360×432px rounded portrait inside the loop and split display text across upper left and upper right.

### Icons

**Observed:** Navigation and action glyphs are thin charcoal or black SVG strokes, mostly 21px with 1.5px butt-ended lines; tiny 10px chevrons accompany menu labels. Circles are 43px for button companions and 64px for proof badges. Illustrated faces add warmth to conversion controls.

**Transfer:** Choose sparse outline arrows, chevrons and simple proof symbols; reserve filled playful faces for a small number of primary controls.

## Section recipes

How recurring sections are built.

### First screen: Illustrated promise opening

**Observed:** The first 900px is a flat Green stage with a Floating navigation assembly at the top. A centered display headline occupies roughly two-thirds of the content width, broken into two compact lines around the upper-middle of the screen. Its 139.7px type is charcoal, medium and very tightly tracked. The 29.8px support line follows after 51px. A large unframed vector group rises into the lower third and continues below the fold; the figures are visually in front of the background and below the text, with clouds and small accents around them. The visible conversion action lives in navigation; the more explanatory paragraph and another action belong in the next cream panel, which scrolls up over the stage with 50px upper corners.

**Transfer:** For a new landing page retain the green field, restrained central promise, short support and expressive oversized figure. Without elaborate character art, use the minimum Exuberant vector scene plus a Looping narrative ribbon rather than an interface mockup. Organizational pages open on cream with portrait constellations; ecosystem pages use an orchid illustrated scene and split left/right display phrases; detailed service pages use stone, an 80.8px headline and a smaller contextual photograph; contact pages open with a centered 690px column.

**Avoid:** Do not replace this first impression with a left-copy/right-dashboard split, a gradient sphere, a full-bleed stock photo, or a row of three call-to-action buttons under the headline.

**Text style:** `display` — Inter 500 · 139.7px/0.95 · tracking -0.06em

### Illustrated benefit journey

**Observed:** A cream rounded chapter connects alternating Feature story tiles with the Looping narrative ribbon. The art is much larger than the text cards and can extend beyond the page edges. Individual tiles are about 513px wide, with a heading, paragraph and colored action; the journey breathes across several viewport heights.

**Transfer:** Select a few genuinely different user benefits and stage them along a continuous illustrated path. Compress the number of beats when the story is shorter, preserving the contrast between oversized art and concise white explanation.

### Heading and explanation pair

**Observed:** An 80.8px section heading on the left balances a compact 20.2px paragraph on the right within the inner fourteen-column area. One key word receives the Wave underline. Variants place a small rounded photograph below the heading or use a 53.1px statement paragraph across most of the width.

**Transfer:** Introduce a substantive chapter using one strong claim and one grounded explanation, not a centered eyebrow on every section.

**Text style:** `heading-lg` — Inter 500 · 80.8px/0.95 · tracking -0.06em

### Large invitation band

**Observed:** A green chapter uses 170px vertical padding, a centered display invitation, a 29.8px supporting statement, one Primary button and a low row of three concise reassurance lines. Illustration remains part of the scene.

**Transfer:** Create a generous pause after the product argument with one approachable invitation and a few terse reassurances.

**Text style:** `display` — Inter 500 · 139.7px/0.95 · tracking -0.06em

### Stacked quantified proof

**Observed:** Within Cream canvas, a large left headline and short body-sm explanation remain alongside a right-hand sequence of Proof cards. The chapter starts with 136px top padding and finishes with 170px. The cards have different fills and prominent round symbols; the sequence reads as objects rising and stacking rather than a small metrics strip.

**Transfer:** Use fewer cards if fewer reliable figures exist. Keep the scale and contextual explanation rather than filling space with unsupported numbers.

**Text style:** `stat` — Inter 400 · 144px/0.95 · tracking -0.06em

### Editorial mosaic and identity rails

**Observed:** A Stone chapter holds an asymmetric article layout with one large story, a medium story and smaller supporting stories. Photography leads each title; small white category capsules sit beneath. A centered heading then introduces several edge-clipped rows of Identity capsules with 17px vertical spacing.

**Transfer:** Combine a small amount of practical editorial proof with a generous identity rail. Use the same rail construction for integrations or partners if that better supports the new product.

### Monumental closing invitation

**Observed:** Yellow finale fills about one desktop viewport. At upper left a compact 20.2px invitation paragraph and Primary button face two utility-link columns at right. Lower left is a two-line display invitation at 139.7px, with a green Wave underline beneath the second line; right aligns contact locations, hours and email. The bottom holds copyright, a small credential mark and a social link. The same ending is shared across marketing, company, enquiry, detailed-service and ecosystem content.

**Transfer:** Always provide the bright closing panel and large conversational closing line. Adapt contact details and navigation to the product while retaining the strong upper/lower and left/right hierarchy.

**Text style:** `display` — Inter 500 · 139.7px/0.95 · tracking -0.06em

### Long-form reading chapter

**Only for:** detailed service explainers

**Observed:** A stone asymmetric opening leads into a cream 50px-rounded reading chapter. A narrow left rail keeps the topic and a back action visible, while a 690px right column holds 40.4px section headings, 20.2px prose, bold lead-ins, simple lists, white comparison tables, stone-backed inline links and 1px rules. Wide rounded photographs have short captions. A compact Question accordion stack leads to a short recap and action. A stone next-item teaser precedes the shared Yellow finale.

**Transfer:** Keep detailed education genuinely readable and separate from the illustrated landing-page default. Use question-led sections, comparisons, explicit limitations and a concise recap.

**Text style:** `heading-sm` — Inter 500 · 40.4px/1.2 · tracking -0.06em

### Catalogue chapter rows

**Only for:** network or ecosystem storytelling pages

**Observed:** Inside a rounded Stone chapter, successive rows pair a 40.4px category heading and compact paragraph at left with a large rounded contextual photograph at right. An embedded white story teaser under the copy pairs a small image with title and quiet Read link. Rows have 85px internal spacing and 1px stone-edge separators. A centered cream invitation precedes Yellow finale.

**Transfer:** Use this rhythm to explain regions, applications or product families without turning them into a dense tile directory.

**Text style:** `heading-sm` — Inter 500 · 40.4px/1.2 · tracking -0.06em

### Centered enquiry

**Only for:** contact and enquiry forms

**Observed:** A cream opening places an 80.8px two-line conversation headline in a 690px column, with a green Wave underline, a call-booking action and an email alternative. White Enquiry fields continue below, ending with a proposal action, reassurance and a small legal note before Yellow finale.

**Transfer:** Focus on the reader's actual challenge and offer both a direct conversation and a form, with no competing decorative scene.

**Text style:** `heading-lg` — Inter 500 · 80.8px/0.95 · tracking -0.06em

## Page flow

**Storyline:** Human promise → clear explanation → differentiated capability → tangible proof → approachable invitation and useful closing information.

### Brand-led marketing landing page

1. **Promise** — Green illustrated opening with a short central promise and support line.
2. **Capability chapters** — Cream introduction followed by alternating white explanation tiles along a large illustrated ribbon.
3. **Invitation** — Large green conversational call with a single action.
4. **Quantified and social proof** — Oversized stat-card stack, editorial mosaic and moving identity capsules.
5. **Closing call** — Yellow invitation panel with monumental closing words, contacts and useful links.

**Transfer:** Adapt the narrative length to the product; retain expressive art, large-scale proof and the colored final invitation.

### Company credibility and people

1. **Identity** — Cream central display framed by floating portraits.
2. **Differentiation** — Large green statement, heading-and-explanation pair and white benefit carousel.
3. **Process** — Stone display transition with blue loop and numbered white process cards.
4. **Trust** — Comparison panel, editorial team introduction and large illustrated individual profiles.
5. **Invitation** — Community portraits, centered onward action and shared yellow closing panel.

**Transfer:** Use the extra people and process treatments for an organization story, not as obligatory landing-page chapters.

### Conversion through an enquiry

1. **Invitation** — Compact conversation headline, call action and email alternative.
2. **Enquiry** — Centered labeled white-field form with a substantial challenge textarea and reassuring final action.
3. **Closing information** — Full shared yellow closing panel rather than a stripped-down legal footer.

**Transfer:** Keep the form focused and preserve the same brand-rich ending as the editorial pages.

### Detailed service education and buyer qualification

1. **Specific promise** — Stone opening with an explicit offering headline, contextual photo and compact summary.
2. **Education** — Cream right-hand reading column with persistent left context, question-led chapters, lists, tables and real examples.
3. **Objection handling** — Limitations, cost discussion, practical questions and compact accordions.
4. **Conversion and continuation** — Short recap with a quote action, next-service teaser and yellow closing panel.

**Transfer:** Use the editorial variant for complex purchase decisions, without bringing the extremely long article format into a simple landing page.

### Ecosystem breadth and local relevance

1. **Breadth promise** — Orchid illustrated opening with display phrases anchored to opposite sides.
2. **Credibility** — Large statement, supporting image and map visualization.
3. **Differentiation** — White benefit carousel on cream.
4. **Capability catalogue** — Stone chapter of text/photo rows with embedded related stories.
5. **Closing call** — Centered cream invitation followed by shared yellow ending.

**Transfer:** Use the map only when geography genuinely matters; otherwise visualize the ecosystem with a comparably simple graphic and keep the chapter-row rhythm.

## Writing

Warm, capable and plainspoken, combining the confidence of a coordinated expert team with a cheerful human invitation. Claims work best when they explain a concrete operational advantage, then show what it means for the reader.

**Do not copy:** Do not reuse MindMarket's name, identity, character artwork, client logos, employee names, testimonials, proprietary claims or numeric achievements. Source examples demonstrate cadence only; substitute the new product's own verified facts and assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you; the organization speaks as we. Favor collaborative language over impersonal corporate descriptions.
- **Rhythm:** Short, punchy headlines often use parallel fragments. Supporting passages are compact and conversational, with contractions, occasional em dashes and an invitation rather than a hard sales close. Longer educational writing becomes specific and question-led.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A short human outcome, not a feature inventory. | 3–6 words | “Real human insights”<br>“One global partner” |
| Benefit headline | Parallel fragments or an ordinary phrase given a confident twist. | 3–5 words | “One brief. One team.”<br>“Global, for real.”<br>“No more chaos.” |
| Support | Describe a familiar difficulty and how working together makes it manageable. | One short paragraph | “Managing multiple vendors, juggling time zones, translating insights across cultures — it adds up fast.” |
| Primary action | Name a clear next step in everyday language. | 2–4 words | “Get a quote”<br>“Book a call”<br>“Get Your Proposal” |
| Educational heading | Ask the buyer's direct practical question, including limitations. | 4–10 words | “What is mystery shopping?”<br>“When mystery shopping is not the answer” |
| Closing invitation | Friendly readiness and a conversational imperative. | 2–5 words for the display | “Ready when you are!”<br>“Let’s Connect” |

**Words and phrasing to use:** real; human; one team; simple; clear; together; ready when you are; your challenge; from start to finish

**Avoid:** disruptive synergy; revolutionary platform; best-in-class without proof; corporate jargon; pushy urgency

**Rules:**

- Lead with the reader's outcome, then explain the mechanism.
- Use parallel constructions for headline rhythm, not adjective piles.
- Give numerical proof a plain-language explanation.
- Let detailed pages state when an offering is not the right answer.
- Keep action labels concrete and short; keep reassurance next to the action.

## Do's and Don'ts

### Do

- Use Inter 500 for headlines and body, with 400 reserved for giant stat numerals.
- Keep the primary display at 9.7vw with 0.95 line height and -0.06em tracking.
- Give desktop chapters 136px or 170px of major vertical breathing room.
- Keep the main grid's 20px gutters distinct from the tighter 8.5px action gap.
- Preserve 50px chapter corners, 20px photo/carousel corners and 10px button/tile corners.
- Use flat white text cards to protect readability over the illustrated journey.
- Emphasize a meaningful headline word with a thick colored wave.
- Make proof visually substantial with 144px numerals and a contextual explanation.

### Don't

- Do not introduce a serif, mono or ultra-heavy display font; the hierarchy comes from one tightly tracked grotesk.
- Do not turn warm cream into a stark white page ground; white belongs mainly to functional surfaces.
- Do not give every neutral card a gray outline or drop shadow; this is a flat layered system.
- Do not make all accents green: coral, blue, lilac and yellow carry distinct playful moments.
- Do not use pill-shaped primary buttons; the circle is a companion inside a 10px-cornered rectangle.
- Do not color the whole headline as emphasis; keep charcoal letters and put color in the wave.
- Do not shrink the final invitation into a legal-link strip; the yellow ending is a major brand moment.
- Do not bring orchid stage backgrounds or oversized employee profiles into an ordinary product landing page.

## Motion and responsive

### Motion

**Observed:**

- Declared action-circle transform transition: 0.4s cubic-bezier(.17,.67,.3,1.33).
- Declared feature-background transform transition: 0.6s cubic-bezier(.17,.67,.3,1.33); the white layer has a 0.2s delay.
- Declared card text transitions use transform and opacity over 0.4s with staggered delays.
- Identity and portrait rails have declared 10s linear infinite scroll animation; a map rail declares 35s linear infinite scroll-map and is paused.
- Navigation is fixed; the opening and stat sequence use sticky positioning.

**Transfer:**

- Keep motion tied to the physical scene: ribbons connect, cards layer into place, circular controls move independently, and identity rails continue beyond the frame.
- Use the declared short transform timings for the white/color card layers rather than a generic fade on every block.

**Unknown:**

- Exact scroll timelines, trigger thresholds, reduced-motion behavior and complete menu opening behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 400px, 500px, 640px, 700px, 1000px, 1200px, 1400px, 1600px, 1700px, 1800px, 2000px and 2400px.
- Layout classes describe six-column base grids and sixteen-column desktop grids. Display type has a 9.7vw size rule.

**Transfer:**

- On narrow screens, preserve the scene's headline-first hierarchy and allow decorative figures to extend outside the side edges while keeping faces and the central promise readable.
- Stack split narrative content and remove sticky competition when a 690px reading column cannot fit beside its context rail. Keep the rectangular action and round companion intact.
- Retain horizontal clipping for the capsule and carousel rails rather than squeezing all items into tiny columns.

**Unknown:**

- Mobile compositions, exact breakpoint-to-layout mappings and viewport-dependent type beyond the declared display rule are not verified; narrow-screen adaptations are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
