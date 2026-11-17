# Tally — doodles meet documents

## Overview

A bright, approachable software style that makes capable tools feel as easy as writing on paper. White space, warm charcoal sans-serif text and small blue actions provide the structure; wiry hand-drawn characters, pink pencil marks and lightly framed interface demonstrations supply the personality. It suits self-serve products with real workflows to show, balancing roomy marketing chapters with compact, document-like explanations.

### Essentials

- A plainspoken promise gets a handwritten wink: Inter 64px/1, weight 700, -2px tracking, centered above a 600px support line, with a pink scribble under one meaningful word.
- The opening is an invitation into a document, not a dashboard collage: a 60px header, 128px breathing room, a compact 36px blue action and a 976px browser stage entering the first screen at 528px.
- Small actions stay tool-like: blue #0070d7, 8px corners, 15px semibold labels and 13.5px horizontal padding; navigation uses a smaller 28px-high, 7px-corner version.
- Color behaves like annotation on white paper: almost all large surfaces stay white or #fefefe; pink #f81ce5 appears as thin marks, 24px icons and a standout double-ring benefit card, with violet-to-pink text confined to that emphasis.
- Human doodles and real working interfaces share the stage: dark irregular outlines, sparse pink hatching and halftone touches surround crisp 10px-corner browser frames. Include the drawing language even without custom art by using original loose SVG gestures and product-related objects.
- The page gets both an illustrated invitation and a human proof pause: a roughly 500px-wide line-art closing scene with peripheral pink/gray particles, plus centered 30px/1.15 gray quotes and a small author row. These devices can move to suit the story rather than dictate a fixed sequence.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#0070d7` | `--color-blue` | action, link, accent | Default conversion buttons and a few functional accents. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Annotation pink | `#f81ce5` | `--color-pink` | accent, border, action, link | Doodle marks, benefit-card ring and feature icons. A pricing variant uses it for the first paid-plan action. |
| Benefit gradient pink | `#f81ce0` | `--color-gradient-pink` | text, accent | Second stop of the exceptional benefit headline's clipped gradient. |
| Benefit violet | `#8a46ff` | `--color-violet` | text, accent | Start of the exceptional benefit headline's clipped gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Headline black | `#000000` | `--color-black` | text, action | Marketing headings and the secondary browse action. |
| Warm charcoal | `#37352f` | `--color-ink` | text | Body text, FAQ labels and editorial headings. |
| Soft charcoal | `#45433e` | `--color-footer-ink` | text | Footer links and compact attribution captions. |
| Explanatory gray | `#5f5e5a` | `--color-secondary` | text | Feature descriptions, price currencies and supporting details. |
| Quote gray | `#777672` | `--color-muted` | text | Large testimonials and subdued navigation labels. |
| Control edge | `#dfdfde` | `--color-edge` | border, surface | Subtle outlined controls and pale browser dots; also the visible result of charcoal at 16% on white. |
| Paper hairline | `#ededec` | `--color-rule` | border | Visible result of charcoal at 9% opacity over white; FAQ rows, footer rules and browser edges. |
| Near-white card | `#fefefe` | `--color-card` | surface | Raised feature and plan cards; the difference from the canvas is deliberately tiny. |
| White paper | `#ffffff` | `--color-canvas` | background, text | Main canvas, browser interiors and reversed button labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial and company pages | Editorial link gray | `#9b9a97` | `--color-faint-text` | text, link | Low-emphasis article links. |
| product demonstrations | Address gray | `#eaeaea` | `--color-address-bar` | surface | Compact URL bars in sharing demonstrations. |
| editorial and company pages | Editorial wash | `#f9f9fa` | `--color-editorial-wash` | surface | Visible 30% #ebeced wash over white behind callouts and press cards. |
| pricing pages | Savings green | `#1aa82b` | `--color-saving-ink` | text | Savings badge label. |
| pricing pages | Savings mint | `#d2f4d6` | `--color-saving-fill` | surface | Small savings badge backing. |

## Typography

- **Inter** — All marketing, editorial and functional text. Straightforward sans-serif with a tall x-height; bold headlines feel direct rather than ornamental. Font stack: "Inter", "Inter Fallback", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 700 | 64px | 1 | -2px | Centered marketing promise; keep a short headline on one line when the available width permits. |
| heading | Inter | 700 | 36px | 1.15 | normal | Major capability chapters, closing invitation and questions heading. |
| quote | Inter | 700 | 30px | 1.15 | normal | Centered customer quotations in muted gray. |
| benefit-highlight | Inter | 800 | 26px | 1.15 | normal | Exceptional promise inside the pink-ring card; apply a clipped violet-to-pink gradient. |
| lead | Inter | 500 | 22px | 1.25 | normal | Hero and section support; centered in openings and left aligned in capability chapters. |
| feature-heading | Inter | 800 | 18px | 1.15 | normal | Feature-card titles and compact audience group headings. |
| attribution | Inter | 700 | 18px | 1.15 | normal | Name beneath a testimonial. |
| body | Inter | 400 | 16px | 1.5 | normal | Card paragraphs and editorial prose. |
| feature-description | Inter | 500 | 16px | 1.5 | normal | Short explanatory text in open feature grids and pricing cards. |
| label | Inter | 600 | 16px | 1.5 | normal | Inline feature names, integration links and FAQ questions. |
| button | Inter | 600 | 15px | 1 | normal | Primary and secondary conversion labels. |
| footer-link | Inter | 400 | 15px | 1.8 | normal | Footer navigation and copyright. |
| footer-label | Inter | 600 | 15px | 1.8 | normal | Footer category labels and trust statement. |
| nav | Inter | 600 | 14px | 1 | normal | Header actions and billing-period labels. |
| caption | Inter | 400 | 13px | 1.15 | normal | Small action reassurance and testimonial credentials. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial and company pages | editorial-title | Inter | 600 | 40px | 1.2 | normal | Left-aligned article-style opening. |
| pricing pages | price | Inter | 800 | 38px | 1.15 | normal | Right-aligned plan price numeral. |
| pricing pages | currency | Inter | 400 | 28px | 1.15 | normal | Smaller gray currency sign beside the price. |
| editorial and company pages | editorial-heading | Inter | 600 | 24px | 1.3 | normal | Team and press subsection headings. |
| pricing pages | saving | Inter | 500 | 12px | 1 | normal | Billing discount badge. |

**Notes:**

- Only the 64px display recipe uses negative tracking; the 36px section headings and smaller roles retain normal spacing.
- Heavy 18px feature titles are distinct from 16px semibold inline labels. Keep the latter in the same sentence as their descriptions.
- The hierarchy relies on weight and scale rather than uppercase eyebrows, decorative fonts or wide letterspacing.
- Default marketing text is black or warm charcoal; large quotes recede to gray even though they remain bold.

## Layout

**Density:** Airy between narrative chapters and compact inside explanations; large blank intervals separate groups without making every control oversized.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Feature title to paragraph and compact control groups. |
| 16px | Section heading to lead, FAQ vertical padding and billing control to plan grid. |
| 24px | Main container side padding and quote-to-author spacing. |
| 32px | Card padding, card gutters, grid gutters and display-to-support spacing. |
| 64px | Lead to main action, opening text group to browser stage and testimonial breathing space. |
| 100px | Footer top and bottom padding. |
| 128px | Space after the header before the marketing opening. |
| 192px | Separation between major marketing chapters. |

### Containers and grids

- **marketing-container**: max width 1024px · side padding 24px. Centered outer container yields 976px of usable desktop content.
- **hero-copy**: max width 600px. Centered lead below a headline that can span the full marketing container.
- **feature-grid**: 3 columns · gap 32px. Open text features, each about 304px wide within the marketing container.
- **asymmetric-cards**: 2 columns · gap 32px. A 566px primary demonstration beside a 378px supporting card or stacked cards, inside 976px.
- **integration-grid**: 4 columns · gap 32px. Unboxed logo, linked name and short description arranged in compact desktop rows.
- **editorial-container** (only for editorial and company pages): max width 720px · side padding 16px. A centered document column with 688px of readable content; paired 328px callouts use a 32px gutter.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | cards-and-browsers | 10px |
|  | primary-buttons | 8px |
|  | compact-controls | 7px |
|  | avatars | 50% |
| editorial and company pages | editorial-cards | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| paper-card | `rgba(0, 0, 0, 0.12) 0px 1px 1px 0px, rgba(61, 59, 53, 0.16) 0px 0px 0px 1px, rgba(61, 59, 53, 0.08) 0px 3px 9px 0px, rgba(61, 59, 53, 0.08) 0px 2px 5px 0px` | Feature cards and plan panels; fine edge plus shallow layered lift. |
| browser | `rgba(0, 0, 0, 0.09) 0px 3px 12px 0px` | Large interface frames. |
| pink-ring | `#f81ce5 0px 0px 0px 2px, rgba(248, 28, 229, 0.36) 0px 0px 0px 4px` | Standout benefit card; a double outline rather than a diffuse glow. |

### Surfaces

#### Canvas · level 0

**Use:** Entire marketing page.

**CSS:** `background: #ffffff`

**Observed:** White remains continuous behind text, drawing and UI; sections are not separated by alternating colored bands.

**Transfer:** Separate chapters with space and composition instead of background changes.

#### Paper card · level 1

**Use:** Feature demonstrations and plan panels.

**CSS:** `background: #fefefe; border-radius: 10px; box-shadow: rgba(0, 0, 0, 0.12) 0px 1px 1px 0px, rgba(61, 59, 53, 0.16) 0px 0px 0px 1px, rgba(61, 59, 53, 0.08) 0px 3px 9px 0px, rgba(61, 59, 53, 0.08) 0px 2px 5px 0px; overflow: hidden`

**Observed:** Large white panels can be full width or asymmetrically paired; text occupies a padded top area above the demonstration.

**Transfer:** Use one coherent working example per panel.

#### Browser stage · level 2

**Use:** Hero demonstration and large feature interfaces.

**CSS:** `background: #ffffff; border: 2px solid rgba(55, 53, 47, 0.09); border-radius: 10px; box-shadow: rgba(0, 0, 0, 0.09) 0px 3px 12px 0px; overflow: hidden`

**Observed:** A shallow browser bar with three pale dots sits above the interface. Some chapter examples extend beyond the surrounding panel's right or bottom edge.

**Transfer:** Keep browser chrome minimal so a readable workflow is the main object.

#### Pink-ring benefit · level 1

**Use:** One exceptional product promise.

**CSS:** `background: #fefefe; border-radius: 10px; box-shadow: #f81ce5 0px 0px 0px 2px, rgba(248, 28, 229, 0.36) 0px 0px 0px 4px; overflow: hidden`

**Observed:** A wide, shallow panel holds text at upper left and rolling line-art terrain across its lower half.

**Transfer:** Give a genuinely differentiating benefit this special treatment, not every feature.

#### Editorial callout · level 1

**Only for:** editorial and company pages

**Use:** Paired values and press cards.

**CSS:** `background: rgba(235, 236, 237, 0.3); border: 1px solid rgba(55, 53, 47, 0.09); border-radius: 8px; padding: 16px 16px 16px 12px`

**Observed:** Very pale gray, low-relief cards; values have a small icon beside prose, press cards center monochrome publication marks above a subdued article link.

**Transfer:** Use as document annotations rather than conversion panels.

## Components

### Navigation

**Use:** Minimal site-wide orientation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 20px; background: #ffffff; height: 60px; box-sizing: border-box`

**Text style:** `nav` — Inter 600 · 14px/1

**Observed:** Small wordmark at far left; subdued short links and a Compact action grouped at far right. Company pages simplify to signup and creation actions; their header is 69px tall.

**Transfer:** Keep the brand mark visually small; avoid expanding this into a dense mega-navigation.

### Primary button

**Use:** Default conversion action.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 7.5px; height: 36px; padding: 0px 13.5px; background: #0070d7; color: #ffffff; border-radius: 8px`

**Text style:** `button` — Inter 600 · 15px/1

**Observed:** Content-sized label, often followed by a white right arrow. A black version supports template browsing; a pink version belongs to the first paid plan while the other plan stays blue.

**States:** Declared: hover background #005bb5; focus-visible outline rgba(58, 152, 255, 0.36) solid 4px. The black variant hovers to #37352f; the pink plan variant to #d915c4.

**Transfer:** Use short verb-led actions; reserve full-width buttons for card-contained actions.

### Compact action

**Use:** Header conversion and light utility links.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 28px; padding: 0px 9.8px; background: #0070d7; color: #ffffff; border-radius: 7px`

**Text style:** `nav` — Inter 600 · 14px/1

**Observed:** Blue conversion control shares a line with transparent gray navigation controls. The editorial signup variant has a thin pale edge.

**States:** Declared: hover background #005bb5; focus-visible outline rgba(58, 152, 255, 0.36) solid 4px. Transparent utilities hover to rgba(0, 0, 0, 0.04).

### Feature panel

**Use:** Explain and show a capability together.

**CSS:** `background: #fefefe; border-radius: 10px; padding: 32px; box-shadow: rgba(0, 0, 0, 0.12) 0px 1px 1px 0px, rgba(61, 59, 53, 0.16) 0px 0px 0px 1px, rgba(61, 59, 53, 0.08) 0px 3px 9px 0px, rgba(61, 59, 53, 0.08) 0px 2px 5px 0px; overflow: hidden`

**Text style:** `feature-heading` — Inter 800 · 18px/1.15

**Observed:** Pink outline icon, title, short paragraph, then a purposeful interface demonstration. Some browser media extend to the panel edge rather than retaining text padding.

**Transfer:** Use the Paper card surface and show the smallest real workflow that substantiates the title.

### Open feature item

**Use:** Secondary capabilities that do not need their own panel.

**CSS:** `color: #5f5e5a; max-width: 304px`

**Text style:** `feature-description` — Inter 500 · 16px/1.5

**Observed:** A 24px pink outline icon sits above an inline semibold feature name and medium-weight description; no card outline or shadow.

**Transfer:** Group related benefits in three-column rows; integration variants use partner marks in four columns.

### Testimonial

**Use:** Human proof between capability groups.

**CSS:** `color: #777672; text-align: center; margin-top: 64px; margin-bottom: 64px`

**Text style:** `quote` — Inter 700 · 30px/1.15

**Observed:** A bold gray quote spreads across the content width; 24px below it is a centered author row with a small circular portrait or drawing, bold name and much smaller credential line.

**Transfer:** Keep authentic conversational wording and enough space for the quote to act as a pause.

### FAQ row

**Use:** Objection handling near the end.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 16px 0px; border-bottom: 1px solid rgba(55, 53, 47, 0.09); color: #37352f`

**Text style:** `label` — Inter 600 · 16px/1.5

**Observed:** Full-width question left, slim right-pointing chevron right. The first row also has a top hairline; closed rows are about 57px high.

**Transfer:** Keep the list spare; use only actual decision-blocking questions.

### Footer

**Use:** Shared final site directory.

**CSS:** `display: flex; justify-content: space-between; padding: 100px 0px; border-top: 1px solid rgba(55, 53, 47, 0.09)`

**Text style:** `footer-link` — Inter 400 · 15px/1.8

**Observed:** Brand and trust/copyright/social stack at left; three directory columns at right with smaller category groups stacked where needed. Link rows use a 27px line rhythm and semibold category labels.

**States:** Declared: hover links change to #37352f and underline.

**Transfer:** Carry the same footer into product, pricing and editorial pages rather than ending each with a different visual theme.

### Editorial card

**Only for:** editorial and company pages

**Use:** Document callouts and press references.

**CSS:** `background: rgba(235, 236, 237, 0.3); border: 1px solid rgba(55, 53, 47, 0.09); border-radius: 8px; padding: 16px 16px 16px 12px`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** Two equal-width cards sit beside one another; values combine an inline icon with a semibold label and brief explanation. Press variants place a black publication mark above a gray underlined article action.

**Transfer:** Use actual company practices or external references in the same compact document treatment.

### Savings badge

**Only for:** pricing pages

**Use:** Billing-period incentive beside the switch.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 20px; padding: 0px 7px; border-radius: 10px; background: #d2f4d6; color: #1aa82b`

**Text style:** `saving` — Inter 500 · 12px/1

**Observed:** Small mint lozenge follows monthly/yearly labels and a dark switch with a white circular thumb.

**Transfer:** Use only for a real, plainly stated billing advantage.

## Imagery and graphics

### Handwritten annotation system

**Use:** Hero word emphasis and recurring chapter headings; a signature layer throughout marketing.

**Observed:** Loose pink zigzag underlines, circles, arrows, short sparks and faint textured brush marks interrupt otherwise straight typesetting. Characters and objects use thin irregular dark strokes with abundant white interior, with pink restricted to a few gestures.

**Transfer:** Draw original product-relevant objects and expressions; at minimum pair a rough pink underline with a small dark outline object in each major illustrated chapter.

**Build:** Use SVG paths with no fill and rounded caps. Make the underline from an uneven sequence of short up/down strokes, about 12px high beneath the chosen word. For supporting art, layer 2px–3px charcoal paths in a roughly 340px by 240px viewBox, then a few pink paths and a clipped halftone patch made from a sparse circle pattern. Keep most of the viewBox transparent; do not turn the line art into solid cartoon stickers.

### Working browser demonstrations

**Use:** Large opening object and feature proof.

**Observed:** Lightweight browser frames show real document-like forms and specific editing actions. Media are mostly white with dark text, faint separators and restrained functional UI colors; the opening frame is 976px wide and 704px high. Chapter media can be oversized or partially framed, creating depth without colored backplates.

**Transfer:** Use a real interface or a carefully constructed representative workflow. If no interface exists, design a credible paper-like task/result example inside the Browser stage, not a generic dashboard.

### Floating expressions

**Use:** Peripheral personality around the opening demonstration.

**Observed:** Oversized line-drawn faces, speech-like shapes and small pink/gray strokes flank the browser, extending beyond the content container and clipping at viewport edges. They leave the headline and button unobstructed.

**Transfer:** Create a loose cloud of original reactions or tool-related symbols, keeping the center clear.

**Build:** Place transparent SVG groups behind the browser at the left and right viewport edges. Draw 2px–3px dark looping paths and sparse pink diagonals, at mixed sizes around 60px–180px. Use a few pale halftone swashes rather than full-background texture; clip only the outer groups with page overflow.

### Illustrated invitation

**Use:** Large closing conversion scene.

**Observed:** A cheerful line-art person raises an arm above a tablet-like work object; small symbols float nearby. The main scene is about 500px by 373px, centered above the heading; sparse pink and pale gray particles run down both outer margins across an approximately 649px-high section.

**Transfer:** Use an original person-and-tool or object-in-use drawing that conveys readiness to begin. Minimum version: a loose outline hand interacting with the new product's central object, with surrounding symbols and the same clear center.

**Build:** Center a transparent SVG with dark open paths and a few pink strokes above the copy. Add a separate edge layer of short diagonal strokes, loose arrowheads and 2px dot-pattern swashes in pink at low opacity. Keep particles outside the 600px copy column and avoid a solid backdrop.

### Editorial diagram and press marks

**Only for:** editorial and company pages

**Use:** Team introduction and external recognition.

**Observed:** An approximately 205px by 235px hand-drawn abstract interface diagram sits beside a narrow subsection introduction. People are listed as text in columns rather than a portrait wall; press cards use centered black publication wordmarks on a barely gray surface.

**Transfer:** Use an original loose diagram and honest text roster; render actual external marks monochromatically when permitted.

### Icons

**Observed:** Most feature symbols are 24px outline SVGs with 2px round strokes, usually pink. Pricing includes 20px black checkmarks; button arrows are 18px white outlines; social marks are small solid glyphs.

**Transfer:** Choose simple rounded outline icons with consistent 2px strokes; use pink as annotation, blue for selected plan capabilities and black for plain inclusions.

## Section recipes

How recurring sections are built.

### First screen: Document invitation opening

**Observed:** A small left brand and right utility controls sit in a 60px white Navigation. After 128px of open space, a centered 64px black promise spans nearly the 976px content width, with a pink scribble beneath one word. A 600px-wide lead follows at 32px, then a Primary button at 64px and a 13px reassurance caption 10px beneath it. The Browser stage begins 64px below that text group, about 528px down the page. Floating expressions flank it behind the frame. Within the first 900px the complete headline, lead, action, caption and upper portion of the working interface are visible; the rest of the browser and customer-logo proof sit below the fold. Layers run white canvas, peripheral line art, browser, then the unobstructed central text/action group.

**Transfer:** State the new product's simplest promise and show one understandable task in a broad document-like frame. Without finished media, construct a credible task/result example and original outline symbols. Pricing openings retain the centered display and annotated word but substitute a three-column inclusion panel for the browser; company openings use a narrow, left-aligned editorial title and prose.

**Avoid:** Do not make a split-screen hero, inflate the CTA into a pill, or shrink the browser to a decorative thumbnail beside the headline.

**Text style:** `display` — Inter 700 · 64px/1 · tracking -2px

### Annotated capability chapter

**Observed:** Left-aligned 36px heading with a pink underline or circle on a meaningful word; a 22px lead sits about 16px below. An airy dark line-art vignette occupies the right side of the heading area, around 340px–412px wide. Feature panels or open feature grids follow, with 32px gutters; major chapters are separated by 192px.

**Transfer:** Lead with a user outcome, emphasize one word with the Handwritten annotation system, then choose a real demonstration or concise supporting list.

**Text style:** `heading` — Inter 700 · 36px/1.15

### Exceptional benefit panel

**Observed:** The Pink-ring benefit surface spans 976px and stands about 334px high. A 32px inset holds a 26px extra-bold gradient promise and 16px paragraph near the top left, while a hand-drawn wavy landscape with symbols and a person fills the lower area. Nearby cards return to ordinary Paper card styling.

**Transfer:** Use the double-ring panel for one unusually strong differentiator and give its lower half an original line-art metaphor.

**Text style:** `benefit-highlight` — Inter 800 · 26px/1.15

### Asymmetric demonstration pair

**Observed:** A 566px Feature panel sits beside a 378px panel or stacked panels with a 32px gap. Each starts with an outline icon, compact heavy title and paragraph; the larger card carries the browser or embedded workflow. Sharing examples add gray URL strips and a small live action in the narrower column.

**Transfer:** Allocate more width to the capability that needs demonstration and less to supporting options, rather than flattening every item into equal tiles.

### Open capability inventory

**Observed:** Unboxed secondary features use three 304px columns, 32px gutters and a small icon above inline semibold names and gray explanations. Integrations use four columns with small recognizable marks; audience examples use a three-column list within one Paper card and a black browse action.

**Transfer:** Use these denser modules to summarize breadth after a larger demonstration, without adding card borders around every item.

### Illustrated closing invitation

**Observed:** A centered Illustrated invitation scene occupies the top of a broad white section. Beneath it sit a 36px heading, a two-line 22px support statement and a small blue action. Edge particles extend beyond the normal content column; the section is about 649px high and has no enclosing panel.

**Transfer:** Retain a generous illustrated invitation as a signature conversion moment, changing the person, tool and promise to match the product.

**Text style:** `heading` — Inter 700 · 36px/1.15

### Human proof pause

**Observed:** The Testimonial component appears between major groups and again after the closing invitation. Gray 30px bold quotation text is followed by a centered author row with an 18px bold name and 13px credentials.

**Transfer:** Use attributable, specific praise rather than a styled product slogan.

**Text style:** `quote` — Inter 700 · 30px/1.15

### Questions and directory ending

**Observed:** Marketing and pricing finish with a 36px questions heading over four full-width FAQ rows, then a 192px chapter interval before the shared Footer. The footer top rule, 100px vertical padding, left identity stack and three right link columns create a restrained white ending rather than a colored final banner.

**Transfer:** Close decision-oriented pages with short practical objections and the same compact directory; the illustrated invitation can occur earlier in the closing sequence.

### Plan comparison

**Only for:** pricing pages

**Observed:** An annotated chapter heading and right-side upgrade drawing precede monthly/yearly controls and Savings badge. Two unequal Paper cards align at the top: 566px for the broader feature inventory and 378px for advanced needs. Plan names sit left while 38px numerals with smaller gray currency signs sit right; a full-width pink action anchors the first card and a blue action the other. Descriptions use icons and inline semibold names; the wider card has two internal columns.

**Transfer:** Keep plan value concrete and use the asymmetric width only when one plan genuinely has more content to explain.

**Text style:** `price` — Inter 800 · 38px/1.15

### Editorial document

**Only for:** editorial and company pages

**Observed:** A 720px centered document with 16px side insets opens 48px below the simpler header. A 40px semibold title introduces 16px/1.5 prose. Paired pale Editorial cards follow the narrative; 24px subsection headings, text rosters, a small diagram and monochrome press cards continue the document. It ends after the press grid with open white space and the shared wider Footer, without the marketing invitation or FAQ.

**Transfer:** Use this quieter scale for company stories and long-form trust content; retain the common footer and sparse drawing language.

**Text style:** `editorial-title` — Inter 600 · 40px/1.2

## Page flow

**Storyline:** Simple promise → tangible product proof → differentiating benefits → breadth and human validation → invitation to begin → practical reassurance → shared directory.

### Product marketing landing page

1. **promise** — Centered annotated promise, short lead, small conversion action and low-friction reassurance.
2. **product demonstration** — Broad browser example flanked by doodles, then a compact customer-logo proof row.
3. **differentiation** — Pink-ring benefit panel and asymmetric explanation cards.
4. **capability chapters** — Annotated headings, right-side drawings, large workflow panels and denser open feature lists.
5. **social proof** — Conversational gray quotes with small author rows punctuate the capabilities.
6. **closing call** — Large illustrated invitation with centered heading and blue action.
7. **objection handling** — Another proof pause and a compact questions list.
8. **directory** — Hairline-separated white footer with identity left and grouped links right.

**Transfer:** Adapt the number and order of chapters to the product while preserving an understandable demonstration, handwritten personality and illustrated conversion moment.

### Pricing and upgrade decision page

1. **entry value** — Centered promise and annotated word, then a white three-column checklist of included capabilities and customer marks.
2. **pricing** — Upgrade heading with drawing, billing switch and savings lozenge, then two unequal plan cards with prices aligned to their upper-right corners.
3. **closing call** — Same spacious illustrated invitation with a short next-step action.
4. **reassurance** — Human quote followed by questions and the shared footer.

**Transfer:** Explain the useful entry tier before paid differences; reuse the marketing visual language rather than introducing a spreadsheet-heavy theme.

### Company story and trust page

1. **point of view** — Left-aligned document title and short narrative paragraphs in a narrow column.
2. **principles** — Four pale paired callouts describing working practices.
3. **people** — Small diagram beside a subsection introduction, recruitment link and text roster in columns.
4. **external validation** — Two-by-two press cards with black wordmarks and low-emphasis article links.
5. **directory** — Open white space transitions to the same wider footer.

**Transfer:** Use the editorial variant for trust stories that benefit from readable prose; finish after genuine validation rather than forcing a marketing CTA onto every page type.

## Writing

Friendly and plainspoken, confident about usefulness without sounding enterprise-heavy. It takes frustration seriously but answers it with short, upbeat explanations and occasional conversational asides.

**Do not copy:** Do not reuse Tally's name, logo, illustrations, customer marks, testimonial quotations, plan prices, user counts, free/unlimited claims or legal/compliance claims. Replace all names, proof and product promises with substantiated equivalents. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work; use we for the people building the product. The product is named naturally rather than described through impersonal corporate abstractions.
- **Rhythm:** Headlines are short outcome statements, usually three to eight words. Leads take one or two conversational sentences; features pair a compact noun label with one practical sentence. Occasional contractions, questions and enthusiastic punctuation soften the factual explanation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A superlative or clear outcome attached to the simplest core task. | 5–9 words | “The simplest way to create forms”<br>“Build beautiful forms for free” |
| Supporting line | Name a familiar frustration, then offer an easy alternative in direct language. | 15–30 words | “Say goodbye to boring forms. Meet [Brand] — the free, intuitive form builder you’ve been looking for.” |
| Capability heading | Plain verb and benefit with one emphasized word; short enough to work with a handwritten mark. | 3–6 words | “Make forms uniquely yours”<br>“Connect your favorite tools” |
| Feature explanation | Specific operation followed by a practical payoff; avoid feature-name jargon without explanation. | 10–30 words | “Use variables to create dynamic content and calculate values, scores, prices and more.” |
| Primary action | Start with a verb and name the immediate thing the user will do. | 2–5 words | “Create a free form”<br>“Get started” |
| Reassurance caption | A tiny factual removal of friction. | 2–5 words | “No signup required” |
| Editorial point of view | Short human statements about how good tools should feel, followed by practical commitments. | Short paragraphs of 2–4 sentences | “We build in public”<br>“We actually listen” |

**Words and phrasing to use:** simple; just; your; start; build; easily; tailored; favorite; no need to; grow with you

**Avoid:** enterprise-grade transformation; unlock synergies; revolutionary platform; leverage; seamless ecosystem; unsubstantiated superlatives

**Rules:**

- Explain what the user can do before describing architecture or implementation.
- Use concrete objects and verbs in feature descriptions; a short bold label can lead directly into the explanation.
- Put caveats near generous claims through a plainly named inline link.
- Let warmth come from contractions and small asides, not a joke in every paragraph.
- Keep the last action easy to understand and pair it with one factual reassurance when useful.

## Do's and Don'ts

### Do

- Set the main promise at 64px/1 and -2px tracking; keep section headings at 36px/1.15 with normal tracking.
- Use the 976px content span for broad browser proof and a 600px column for centered lead text.
- Keep 32px card insets and gutters consistent even when the cards have unequal widths.
- Use pink as a pen mark and 24px outline icon color on an overwhelmingly white canvas.
- Include original hand-drawn annotations and a generous illustrated invitation, even when the product has no photographic media.
- Keep centered testimonials bold but gray at 30px, with a clearly subordinate 13px credential line.
- Use the 36px-high action for conversion and the 28px version in the header.
- Carry the 100px-padded, hairline-topped footer across all page types.

### Don't

- Do not replace Inter with a bubbly display font; personality belongs to the drawn layer.
- Do not apply -2px tracking to 18px feature labels or 16px prose.
- Do not make all content panels equal tiles; preserve the 566px/378px demonstration balance where the content supports it.
- Do not fill whole sections with pink, violet or blue; the exceptional colored treatments are thin rings, text and compact controls.
- Do not put a heavy dark band or oversized word sculpture at the end; this ending stays white and directory-like.
- Do not use deep floating shadows or glossy glass effects; panels have fine edges and shallow lift.
- Do not enlarge ordinary controls to 56px-high pill buttons; this style's actions remain compact.
- Do not import the 40px editorial opening into the default marketing hero or stretch long-form prose across the full 976px.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-color, border-color and outline transitions at 100ms ease-in-out; their text declares opacity and color transitions at 100ms ease-in-out.
- Editorial links declare border-color and opacity transitions at 0.1s ease-in; the savings badge declares color and background-color at 200ms ease-in-out.

**Transfer:**

- Keep action feedback quick and localized to the small controls; use the declared blue hover and translucent blue focus ring.
- Use the browser demonstration to explain a task rather than adding unrelated motion to the doodle layer.

**Unknown:**

- Playback choreography, scroll animation triggers and timing are not established; stylesheet keyframes alone do not establish visible behavior.

### Responsive

**Observed:**

- Marketing CSS contains width breakpoints at 450px, 576px, 758px, 992px, 1024px and 1200px.
- Editorial CSS also includes 640px, 642px, 730px and 1300px breakpoints.

**Transfer:**

- On narrow layouts, preserve the centered promise and readable task demonstration; move peripheral doodles away from the text rather than shrinking the entire desktop composition.
- Stack asymmetric panels and reduce open feature columns as needed; keep the 16px body readable and the editorial prose narrow. These are adaptation recommendations, not fixed breakpoint recipes.

**Unknown:**

- Exact narrow-screen layouts, font sizes, navigation behavior and media cropping are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
