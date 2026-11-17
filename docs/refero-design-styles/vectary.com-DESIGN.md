# Vectary — connected objects on display

## Overview

An airy, light product style that feels like a working design board opened into a showroom. Thin humanist sans headlines sit above intricate interface imagery and softly lit three-dimensional objects, with gray and white doing most of the work and yellow providing a small editorial signal. It suits visual software, collaborative tools, and products whose workings are worth showing; prose is practical and relatively dense beneath the spacious introductions.

### Essentials

- A lightweight headline explains a transformation rather than shouting a slogan: Fira Sans 300 at 60px/1 with -2px tracking, centered across a 1008px headline area.
- The opening is a connected visual board, not a boxed illustration: a two-line promise and paired actions float above an edge-clipped collage on #f0f0f0, with imagery entering from the sides and filling the lower first screen.
- Small squared actions keep the product larger than the sales pitch: 8px corners, 14px/21px Inter, 35px default height, a #222222 primary and a white outlined companion.
- Color belongs to the work, not the page furniture: gray canvases dominate, a 37px yellow announcement strip supplies the recurring brand signal, and rich color stays within product imagery. Preserve this strip and a connected product collage on new pages.
- Showroom-scale demonstrations alternate with unboxed explanations: media reaches 1260px wide with 16px corners; feature copy uses three 380px columns separated by 60px rather than a wall of cards.
- The closing image hands off to a dense black directory: a layered workspace-and-object composition can run directly into the #0b0b0b footer, whose six columns use 22px white titles and 14px gray links. If no three-dimensional asset exists, use layered real interface views and material/detail tiles.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Announcement yellow | `#fbd302` | `--color-signal` | background, accent | Narrow announcement band and tiny release-status badges, not primary buttons. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Media white | `#ffffff` | `--color-white` | surface, text | Media framing, secondary actions and footer headings. |
| Inverse text | `#f7f7f7` | `--color-inverse` | text | Text on dark actions. |
| Board gray | `#f0f0f0` | `--color-canvas` | background, surface | Default marketing canvas and the enterprise closing panel. |
| Muted gray | `#949494` | `--color-muted` | text, border | Footer links and utility text; outlines on white buttons. |
| Paragraph gray | `#595959` | `--color-body` | text | Support paragraphs and uppercase section labels. |
| Section charcoal | `#313131` | `--color-heading` | text, action | Section titles; also the compact login button fill. |
| Primary ink | `#252525` | `--color-ink` | text, border | Display headings, navigation and action text. |
| Action charcoal | `#222222` | `--color-action` | action, border | Default primary action background and border. |
| Directory black | `#0b0b0b` | `--color-footer` | background | Full-width closing directory. |
| Feature black | `#000000` | `--color-black` | text | Unboxed feature titles and release-badge lettering. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| detail and pricing pages | Detail paper | `#fcfcfc` | `--color-detail-canvas` | background | Near-white canvas in detailed product, collaboration and purchase journeys. |
| pricing pages | Plan outline | `#d0d0d0` | `--color-plan-edge` | border | Thin outline around subscription and add-on cards. |
| pricing and objection-handling sections | Question gray | `#f2f3f5` | `--color-faq` | surface | Rounded question bars. |
| pricing pages | Allowance gray | `#f0f0f1` | `--color-summary` | surface | Inset plan allowance and credit-package panels. |
| pricing pages | Allowance edge | `#ececee` | `--color-summary-edge` | border | Faint border on allowance panels. |
| cross-device product demonstrations | Device-stage violet | `#6100ff` | `--color-violet` | accent, background | Saturated violet family for the isolated device montage backing; keep it within the artwork. |

## Typography

- **Fira Sans** — Hero and section headings, plus smaller editorial feature headings. Humanist sans with narrow, open forms; light weight gives the headline its explanatory rather than promotional character. Font stack: "Fira Sans", sans-serif.
- **Inter** — Body copy, navigation, actions, labels, pricing and footer. Compact neutral sans, often unusually light in explanatory prose and tightly tracked. Font stack: "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Fira Sans | 300 | 60px | 1 | -0.0333em | Centered opening promise, usually two lines. |
| heading | Fira Sans | 300 | 36px | 1.25 | -0.0267em | Main chapter title and closing invitation. |
| footer-title | Inter | 400 | 22px | 1.09 | -0.0245em | White directory column headings. |
| feature-title | Inter | 500 | 20px | 1.4 | -0.035em | Titles in unboxed feature columns and the trust statement. |
| body | Inter | 300 | 16px | 1.5 | -0.034em | Centered introductions and unboxed feature paragraphs. |
| eyebrow | Inter | 700 | 14px | 1.5 | -0.0386em, uppercase | Centered product or chapter marker above a section title. |
| action | Inter | 400 | 14px | 1.5 | -0.03em | Primary actions, companion actions and account navigation. |
| explore-action | Inter | 500 | 14px | 1.5 | -0.03em | Outlined learn-more actions under chapters and demos. |
| utility | Inter | 400 | 14px | 1.5 | -0.0386em | Footer links and copyright. |
| announcement | Inter | 400 | 12px | 2.25 | -0.045em | Single-line centered announcement with bold product phrase and inline link. |
| badge | Inter | 700 | 9px | 1 | -0.06em, uppercase | Tiny yellow release-status marker. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | Inter | 600 | 36px | 1.111 | -0.0028em | Paid-plan amounts and the custom-price label. |
| pricing pages | pricing-heading | Inter | 500 | 28px | 1.3 | -0.025em | Left-aligned add-on and comparison headings. |
| detailed product and collaboration pages | detail-heading | Fira Sans | 400 | 24px | 1.25 | -0.03em | Split explanatory sections, use-case cards and sales close. |
| pricing pages | plan-title | Inter | 300 | 20px | 1.36 | normal | Plan and add-on names. |
| pricing and objection-handling sections | question | Inter | 400 | 16px | 1.4 | -0.034em | Accordion question text. |
| pricing pages | plan-body | Inter | 400 | 14px | 1.43 | normal | Compact plan audience descriptions. |
| detailed product and collaboration pages | detail-label | Inter | 700 | 12px | 1.5 | -0.035em, uppercase | Local labels in split sections and use-case cards. |

**Notes:**

- Use light Fira Sans for the large hierarchy, not bold Inter. Inter feature titles are stronger but remain much smaller.
- Tracking stays negative even in small body and utility text; uppercase eyebrows are compact rather than widely letterspaced.
- Centered support lines occupy about 819px beneath a 1008px opening headline; feature prose switches to narrow left-aligned columns.
- The pricing hierarchy is a separate Inter-led variant, not a replacement for the marketing heading system.

## Layout

**Density:** Airy at chapter scale, compact inside explanations and utilities; wide media and long text blocks coexist.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Footer link separation and compact action vertical padding. |
| 10px | Centered eyebrow to section title. |
| 12px | Feature title to paragraph and use-case card content gaps. |
| 15px | Opening action-pair gap. |
| 16px | Compact action side padding and plan-grid gap. |
| 20px | Heading to support text, support to action and accordion row separation. |
| 24px | Plan card padding. |
| 30px | Container side padding and footer column gap. |
| 60px | Chapter breathing space, three-column gutters and footer vertical padding. |
| 120px | Opening headline offset below navigation. |

### Containers and grids

- **container**: max width 1320px · side padding 30px. Centered outer container, including its side padding; at 1440px the usable content is 1260px and starts 90px from either edge.
- **opening text**: max width 1008px. Centered headline zone with a narrower support paragraph.
- **feature grid**: 3 columns · gap 60px. Three unboxed 380px text columns across the usable desktop width.
- **footer grid**: 6 columns · gap 30px. Six 185px directory columns followed by a full-width utility row.
- **split story** (only for detailed product and collaboration pages): 2 columns · gap 60px. Two 600px columns, vertically centered, alternating text and media.
- **plan grid** (only for pricing pages): 4 columns · gap 16px. Four equally weighted 303px subscription cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 8px |
|  | media | 16px |
|  | status badge | 9999px (pill) |
| pricing pages | plan cards | 20px |
| pricing pages | allowance panels | 10px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| footer language menus | language menu | `rgba(0, 0, 0, 0.28) 0px 8px 28px 0px` | Raised white language menu above the footer utility bar. |

### Surfaces

#### Board canvas · level 0

**Use:** Default marketing field.

**CSS:** `background: #f0f0f0`

**Observed:** Continuous neutral field behind text, connected image tiles and large media chapters.

**Transfer:** Let the work provide texture while the page stays visually continuous.

#### Media frame · level 1

**Use:** Wide demonstrations and interface films.

**CSS:** `background: #ffffff; border-radius: 16px; overflow: hidden`

**Observed:** Large, flat rounded aperture; usually 1260px by 709px, occupied by the demonstration rather than decoration.

**Transfer:** Fill with an actual screen, composed product scene or informative still.

#### Directory band · level 0

**Use:** Shared page ending.

**CSS:** `background: #0b0b0b; padding: 60px 0`

**Observed:** A sharp full-width shift from the pale content to a dense link directory.

**Transfer:** Keep the black band grounded in useful navigation.

#### Detail paper · level 0

**Only for:** detail and pricing pages

**Use:** Near-white detail-page background.

**CSS:** `background: #fcfcfc`

**Observed:** Keeps longer capability stories and dense comparisons bright.

**Transfer:** Use for deeper evaluation journeys without changing the type family.

#### Enterprise panel · level 1

**Only for:** team-oriented conversion sections

**Use:** Contained closing sales invitation.

**CSS:** `background: #f0f0f0; border-radius: 16px; overflow: hidden`

**Observed:** A 1260px by 400px pale panel with text at left and layered interface artwork bleeding through its right side.

**Transfer:** Pair a short benefit list with a tightly clipped product composition.

#### Allowance inset · level 1

**Only for:** pricing pages

**Use:** Plan limits and package denominations.

**CSS:** `background: #f0f0f1; border: 1px solid #ececee; border-radius: 10px; padding: 12px 16px`

**Observed:** Small flat inserts inside larger outlined plan cards.

**Transfer:** Separate numeric allowances from the prose list without using a colored highlight.

#### Language popover · level 2

**Only for:** footer language menus

**Use:** Utility selection menu.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 6px 0; box-shadow: rgba(0, 0, 0, 0.28) 0px 8px 28px 0px`

**Observed:** A narrow 144px menu rises above the utility bar.

**Transfer:** Reserve strong elevation for temporary utility layers.

## Components

### Announcement strip

**Use:** Recurring top-of-page release signal.

**CSS:** `background: #fbd302; height: 37px; text-align: center`

**Text style:** `announcement` — Inter 400 · 12px/2.25 · tracking -0.045em

**Observed:** One short sentence, bold product phrase, underlined destination and a right arrow; spans the entire viewport.

**Transfer:** Announce one real capability, not several promotional messages.

### Navigation

**Use:** Primary global navigation.

**CSS:** `display: flex; max-width: 1320px; padding: 0 30px; margin: 0 auto; height: 87px`

**Observed:** Logo at left, centered category links with small chevrons, pricing link, then a dark Login and white Sign up at right. Background follows the page rather than becoming a separate bar.

**Transfer:** Retain the three-part alignment and restrained account actions.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #222222; color: #f7f7f7; border: 1px solid #222222; border-radius: 8px; padding: 6px 16px; height: 35px`

**Text style:** `action` — Inter 400 · 14px/1.5 · tracking -0.03em

**Observed:** Content-width action with no ornamental icon. Longer explanatory calls use 8px 20px padding and 39px height; login uses the slightly lighter charcoal fill.

**States:** Declared: hover outline 0px; active outline 0px.

**Transfer:** Keep labels short and let the product demonstration remain dominant.

### Secondary button

**Use:** Companion action and chapter exploration.

**CSS:** `background: #ffffff; color: #252525; border: 1px solid #949494; border-radius: 8px; padding: 6px 16px; height: 35px`

**Text style:** `explore-action` — Inter 500 · 14px/1.5 · tracking -0.03em

**Observed:** Outlined chapter action uses medium text; the hero companion uses regular action text with 8px 20px padding and 39px height. Plan buttons expand to their card width.

**States:** Declared: hover outline 0px; active outline 0px.

**Transfer:** Use for education or a secondary sales path, not as a brightly colored CTA.

### Feature column

**Use:** Capability explanation without card chrome.

**CSS:** `display: flex; flex-direction: column; gap: 12px`

**Text style:** `feature-title` — Inter 500 · 20px/1.4 · tracking -0.035em

**Observed:** A compact title sits over a body paragraph. Three columns share a baseline and 60px gutters, without fill, outline or icons.

**Transfer:** Give each column one distinct capability; let text length vary naturally.

### Demonstration frame

**Use:** Large working-product proof.

**CSS:** `background: #ffffff; border-radius: 16px; overflow: hidden; position: relative`

**Observed:** A wide 16:9 media aperture exposes interface chrome around a hero object. Video controls may overlay the scene; they do not become marketing navigation.

**Transfer:** Use a complete task or clear transformation rather than a featureless loop.

### Release badge

**Use:** Tiny state marker beside a chapter name.

**CSS:** `background: #fbd302; color: #000000; border-radius: 9999px; padding: 4px 8px; margin-left: 6px`

**Text style:** `badge` — Inter 700 · 9px/1 · tracking -0.06em · uppercase

**Observed:** Inline pill aligned with an uppercase eyebrow; much smaller than any action.

**Transfer:** Use only for a meaningful release state.

### Footer directory

**Use:** Consistent page close.

**CSS:** `background: #0b0b0b; padding: 60px 0`

**Text style:** `footer-title` — Inter 400 · 22px/1.09 · tracking -0.0245em

**Observed:** Six columns: identity and contact/legal links first, then five titled lists. Small mark, gray links, copyright and language choice at lower left, small social links at lower right. There is no giant closing slogan.

**Transfer:** Use the Footer link component and preserve the compact directory hierarchy.

### Footer link

**Use:** Directory destinations and legal links.

**CSS:** `color: #949494; margin-bottom: 6px; transition: color 0.2s`

**Text style:** `utility` — Inter 400 · 14px/1.5 · tracking -0.0386em

**Observed:** Left-aligned links; longer editorial links wrap to two lines without enlarging the text.

**States:** Declared: hover color white and outline 0px; active outline 0px.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side subscription choice.

**CSS:** `border: 1px solid #d0d0d0; border-radius: 20px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `plan-title` — Inter 300 · 20px/1.36

**Observed:** Name, audience, price with compact billing qualifier, full-width action, muted inclusion label, Allowance inset and checkmarked feature list. All four cards have equal visual rank; free has an outlined button and paid plans dark buttons.

**Transfer:** Use price for the amount, plan-body for audience copy, and align conversion actions across cards.

### Question bar

**Only for:** pricing and objection-handling sections

**Use:** Compact collapsed FAQ.

**CSS:** `background: #f2f3f5; border-radius: 16px; padding: 12px 30px; min-height: 60px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `question` — Inter 400 · 16px/1.4 · tracking -0.034em

**Observed:** Full-width sentence at left and small plus at right, in a 32px control area. Rows are separated by 20px.

**Transfer:** Group concrete buying and operating questions; retain sentence case.

### Allowance panel

**Only for:** pricing pages

**Use:** Numeric summary inside a plan.

**CSS:** `background: #f0f0f1; border: 1px solid #ececee; border-radius: 10px; padding: 12px 16px`

**Observed:** Two compact label/value rows with labels left and stronger numeric values right; subdued enough to remain secondary to the price.

**Transfer:** Show only the allowances that most clearly distinguish tiers.

## Imagery and graphics

### Connected board collage

**Use:** Signature opening composition.

**Observed:** A panoramic network of product renders, image variations, tiny white annotation cards and material swatches. Soft gray backing joins the page. Predominantly black and gray objects with small warm accents; fine curved connectors link clusters. The sides are clipped and the center stays open beneath the headline.

**Transfer:** Show the new product's inputs, iterations and output in one connected field. Minimum acceptable version: real output thumbnails, several detail tiles and concise annotation cards linked by faint curves; no stock illustration substitute.

**Build:** Create an overflow-hidden stage beneath the centered copy. Use an SVG layer with 1px curves in rgba(148,148,148,0.22), connecting irregular clusters of rounded image tiles. Arrange small annotations and 2-by-3 thumbnail arrays near the edges, larger output tiles along the bottom, leaving a broad shallow valley under the actions. Blend the backing into #f0f0f0; use soft contact shadows on objects, not strong panel elevation.

### Layered workspace sculpture

**Use:** Closing visual punctuation and team-product introductions.

**Observed:** Overlapping white application windows on pale gray, a dotted board, material spheres and labeled cursors; a large dark ribbed bottle with a cork-like base overlaps the interface at an angle. It feels tangible, with soft shadows and one dominant object rather than equal-sized windows.

**Transfer:** Layer two or three real views with a large output detail in front. For nonphysical products, enlarge a result panel or diagram rather than inventing a decorative object.

**Build:** Place a wide back workspace window low in the frame, a board layer slightly higher, and an output layer over the right half. Stagger tops and use modest soft gray shadows. Add a sparse dot field with radial-gradient(rgba(148,148,148,0.25) 1px, transparent 1px) on a 12px grid within the board only. Mask the lower edge to meet the section boundary cleanly.

### Working interface films

**Use:** Broad chapter demonstrations.

**Observed:** Browser and editor chrome stays visible around large photoreal objects: sculpted surfaces, exploded mechanisms, material panels and collaboration tools. Interface is mostly white and gray with small violet, mint or tool-color details. Wide framing makes the work legible before the controls.

**Transfer:** Show a real task with an enlarged result and supporting UI; keep tool colors local to the depicted interface.

### Monochrome proof strip

**Use:** Trust and ecosystem proof between chapters.

**Observed:** Low-contrast gray logos in 120px by 32px slots with 64px gaps, blend-multiplied against the canvas. A centered statement introduces the row. An ecosystem variant ends with a stronger continuation line.

**Transfer:** Use actual authorized customer or integration marks in consistent visual weight; text names can stand in when marks are unavailable.

### Device stage

**Only for:** cross-device product demonstrations

**Use:** One broad compatibility proof graphic.

**Observed:** A headset, upright phone, open laptop and tablet overlap a horizontal violet capsule. Dark glass and metallic surfaces catch studio highlights; grounded shadows sit below the hardware. The laptop is central and largest.

**Transfer:** Use only devices that demonstrate meaningful contexts. A simpler front-facing device montage with real screen content is sufficient.

**Build:** Place a violet rounded capsule across roughly four fifths of the image width, behind transparent device cutouts. Center the largest device, overlap two smaller contexts at left and one at right. Use soft gray ground shadows and a gently varying violet fill; exact color stops are not essential.

### Use-case renders

**Only for:** use-case galleries on detailed product pages

**Use:** Three-column demonstration gallery.

**Observed:** 380px by 347px rounded images depict physical assemblies, consumer products and environments. Backdrops vary from neutral studio gray to warm orange gradients; cutaways and callouts communicate behavior. Beneath each: local label, 24px heading, short paragraph and outlined demo action.

**Transfer:** Give each image a distinct outcome or context. Let stronger color live inside these image bounds rather than tinting the surrounding cards.

### People-led sales film

**Only for:** enterprise closing sections on detailed product pages

**Use:** Human context beside final sales copy.

**Observed:** A rounded film thumbnail shows a small team gathered around a laptop, with darkened photography, white editorial title and centered playback control. It occupies the right 600px column, balancing restrained text and a dark action at left.

**Transfer:** Use authentic collaborative activity and one legible caption rather than posed headshots.

### Icons

**Observed:** Navigation chevrons are small and understated; utility glyphs are monochrome. Footer language icon is 14px with 1.3px strokes in gray. FAQ uses a tiny plus; pricing checkmarks and pluses are similarly restrained.

**Transfer:** Choose simple outline icons at utility scale. Do not add illustrated icons above every feature paragraph.

## Section recipes

How recurring sections are built.

### First screen: Connected stage opening

**Observed:** Board canvas under Announcement strip and Navigation. After 120px of breathing room beneath the navigation, the centered display headline spans about two thirds of the viewport, usually in two lines. A narrower body paragraph follows with a 20px gap, then a brief friction-removal line and centered Primary button plus Secondary button, separated by 15px. Behind and below the copy, Connected board collage extends beyond both viewport edges: small tiles rise at the sides, larger results occupy the lower field. In the first 900px, the announcement, navigation, whole headline, support, both actions and the upper-to-middle collage are visible; the collage continues below the fold.

**Transfer:** Keep an open center and put the new product's visible workflow around it. Without three-dimensional assets, use connected output tiles and actual interface details. Detailed product pages use the same headline and actions over Detail paper, then begin a contained Demonstration frame around 595px down; collaboration pages introduce a layered product montage, while pricing opens with a short centered title and visible plan cards.

**Avoid:** Do not turn the default opening into a left-copy/right-stock-art split, a full-bleed dark hero, or a collage that obscures the promise.

**Text style:** `display` — Fira Sans 300 · 60px/1 · tracking -0.0333em

### Chapter introduction

**Observed:** Centered eyebrow, 10px gap, heading, 20px gap and a restrained body paragraph; chapter content begins with 60px upper breathing space. Secondary button may follow the support. A broad Demonstration frame sits about 60px below the introduction.

**Transfer:** Use a short category marker and a benefit-led heading; reserve detailed mechanics for the next block.

**Text style:** `heading` — Fira Sans 300 · 36px/1.25 · tracking -0.0267em

### Unboxed capability grid

**Observed:** Feature column repeated three times across the 1260px content width with 60px gutters. Titles align; paragraphs begin 12px below them. Repeated rows remain unboxed and use 60px lower breathing room.

**Transfer:** Translate complex features into three clearly differentiated benefits per row.

**Text style:** `feature-title` — Inter 500 · 20px/1.4 · tracking -0.035em

### Trust interval

**Observed:** A centered feature-title statement above Monochrome proof strip, with 60px vertical padding. The row stays low-contrast and relatively shallow compared with product media.

**Transfer:** Use compact, credible proof between large chapters rather than a saturated testimonial block.

**Text style:** `feature-title` — Inter 500 · 20px/1.4 · tracking -0.035em

### Visual handoff close

**Observed:** A chapter introduction and unboxed capability row lead into Layered workspace sculpture, approximately 1280px wide and 499px high. Its lower edge meets Footer directory directly, so the product image is the final marketing statement.

**Transfer:** End a broad overview with an informative visual synthesis rather than another repeated conversion headline.

### Alternating detail story

**Only for:** detailed product and collaboration pages

**Observed:** Split story grid pairs vertically centered text and 600px by 417px imagery, reversing sides between stories. Detail-label sits 4px above detail-heading; paragraph and action follow at 20px intervals.

**Transfer:** Alternate only when it helps explain different tasks; preserve equal column weight and ample gutters.

**Text style:** `detail-heading` — Fira Sans 400 · 24px/1.25 · tracking -0.03em

### Workflow diagram and paired explanation

**Only for:** collaboration pages

**Observed:** A centered 960px-wide connection diagram precedes two explanatory columns. Small browser/source image at left branches through delivery methods and access controls toward stakeholder cards; fine gray orthogonal curves, arrows and small avatar circles keep it practical.

**Transfer:** Map one meaningful input-to-audience relationship, then use paired text columns to explain the two main responsibilities.

**Text style:** `detail-heading` — Fira Sans 400 · 24px/1.25 · tracking -0.03em

### Contained enterprise close

**Only for:** team-oriented conversion sections

**Observed:** Enterprise panel holds a left-aligned heading, five compact bullet lines and a Primary button, while interface artwork fills and clips through the right side. The panel is 400px high; 60px of pale space separates it from Footer directory.

**Transfer:** Summarize a few operational outcomes, then provide one sales path.

**Text style:** `heading` — Fira Sans 300 · 36px/1.25 · tracking -0.0267em

### Consultative film close

**Only for:** detailed product pages

**Observed:** A centered heading introduces a two-column close: a 24px left-aligned subheading, two short paragraphs and a dark action on the left; People-led sales film on the right. After 60px of breathing room comes Footer directory.

**Transfer:** Use a human explanation of the next step, not an oversized price promotion.

**Text style:** `detail-heading` — Fira Sans 400 · 24px/1.25 · tracking -0.03em

### Plan evaluation

**Only for:** pricing pages

**Observed:** A short display title above four Plan cards. Two outlined add-on cards follow, then a centered small billing note. A full-width comparison matrix uses quiet hairlines, a 12px outer radius and four aligned plan columns; category labels stay at left.

**Transfer:** Prioritize comparable constraints and a clear path for each audience, not a colorful featured-plan takeover.

**Text style:** `price` — Inter 600 · 36px/1.111 · tracking -0.0028em

### Question ending

**Only for:** pricing pages

**Observed:** A centered heading introduces stacked Question bars. The final row is followed by 60px of pale breathing space and then Footer directory; there is no additional sales banner.

**Transfer:** Let practical objections form the ending of a purchase journey.

**Text style:** `heading` — Fira Sans 300 · 36px/1.25 · tracking -0.0267em

### Use-case gallery

**Only for:** detailed product pages with multiple applications

**Observed:** Centered chapter title above two rows of three image-led, unboxed cards with 60px gutters. The image is followed by a local uppercase label, detail-heading, body text and compact Secondary button. Cards have no enclosing border.

**Transfer:** Group applications by genuinely different tasks, and keep imagery specific enough to explain the distinction.

**Text style:** `detail-heading` — Fira Sans 400 · 24px/1.25 · tracking -0.03em

## Page flow

**Storyline:** Transformation promise → visible working product → capability explanations → trust or ecosystem proof → broader operational value → page-appropriate close → shared directory.

### Broad product-platform overview

1. **Promise** — Connected stage opening with paired conversion paths.
2. **Product demonstration** — Two major centered chapters, each followed by broad working media.
3. **Capability chapters** — Unboxed three-column explanations extend each demonstration.
4. **Social proof** — Muted trust statement and scrolling logo row.
5. **Operational value** — Team-oriented chapter and another unboxed capability row.
6. **Closing synthesis** — Layered product artwork hands directly into the black directory.

**Transfer:** Introduce the product through its visible work, then widen from individual benefits to organization-level value.

### Subscription evaluation and objection handling

1. **Orientation** — Short centered title above four outlined choices.
2. **Pricing** — Plan cards followed by two add-on packages and a billing note.
3. **Comparison** — Long restrained feature matrix aligns the same four plans.
4. **Objection handling** — Full-width rounded question rows.
5. **Ending** — Pale breathing space then the shared black directory, without another CTA.

**Transfer:** Keep choice, comparison and practical questions visually distinct but on the same near-white canvas.

### Explain a shared operational workflow and motivate team sales

1. **Promise** — Centered headline and two actions above layered workspace imagery.
2. **Workflow explanation** — Centered chapter followed by alternating text/image pairs.
3. **System demonstration** — Connection diagram over paired collaboration and publishing explanations.
4. **Enterprise reassurance** — Centered introduction and two rows of unboxed capability text.
5. **Closing call** — Contained pale sales panel with a benefit list and clipped interface art.
6. **Ending** — 60px gap then the shared directory.

**Transfer:** Move from a unified promise into specific connected tasks, then reassure administrators before asking for a conversation.

### Deep capability education through rich product demonstrations

1. **Promise** — Centered headline, support and paired actions over a large working interface film.
2. **Compatibility proof** — Cross-device montage and feature introduction.
3. **Team reassurance** — Three-column capability row and a business-oriented action.
4. **Capability chapters** — Repeated centered introductions over wide films explain behavior and spatial use.
5. **Interactive proof** — A shareable dark viewer demonstrates a mechanical object with small annotations.
6. **Application proof** — Two rows of image-led use cases.
7. **Ecosystem proof** — Muted software-logo strip and continuation line.
8. **Closing call** — Consultative film close followed by the shared directory.

**Transfer:** Use repeated large demonstrations to teach different dimensions of a complex product, then connect them to concrete applications.

## Writing

Practical, enabling and design-literate. Confidence comes from showing what the tool lets people do, with occasional conversational contrasts rather than exaggerated superlatives.

**Do not copy:** Do not reuse Vectary names, logos, customer or integration marks, product artwork, proprietary interface layouts, plan prices, credit counts, security claims or customer claims. Source examples illustrate syntax, not reusable assertions.

- **Addressing the reader:** Address the reader as you or your; use imperative verbs for actions and product-led declarative sentences for explanations.
- **Rhythm:** Headlines can be long explanatory phrases, often 7–15 words. Support commonly uses two or three practical sentences; short fragments remove friction. An occasional punchy contrast or exclamation is acceptable, but not every chapter.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a progression from a starting state to an understandable outcome. | 8–15 words | “From AI-accelerated ideation to 3D anyone can explore” |
| Chapter title | Frame an outcome in everyday language rather than listing a feature name. | 5–12 words | “Some things are better explored than explained”<br>“Don’t just showcase. Explain!” |
| Supporting line | Explain the connected workflow, then remove practical barriers with short fragments. | 20–55 words | “No downloads, no-code, all in the browser.” |
| Feature title | Concrete capability or task, in sentence case. | 2–6 words | “Centralized asset management”<br>“Embedding and sharing” |
| Primary action | Short verb-object command or conversational sales invitation. | 2–4 words | “Create account”<br>“Let's talk” |
| Exploration action | Specific verb plus the destination topic. | 4–7 words | “Explore sharing and embedding” |
| Question | Ask a practical operational or purchase question in the reader's words. | 6–15 words | “How do I invite team members to a workspace?” |

**Words and phrasing to use:** explore; develop ideas; workflow; share; together; one environment; interactive; from concept to outcome; in real time

**Avoid:** revolutionary; unprecedented; disrupt everything; magic without explanation; aggressive scarcity language

**Rules:**

- Lead with what people can understand or accomplish; follow with mechanisms.
- Use technical names where they clarify compatibility or operations, not to inflate a headline.
- Use friction-removal fragments only when they are true.
- Keep section labels short, categorical and uppercase; keep titles in sentence case.
- Distinguish exploratory actions from account creation and sales conversations.

## Do's and Don'ts

### Do

- Keep display weight at 300 and 60px/60px with -2px tracking.
- Use 36px/45px Fira Sans for chapter titles and 16px/24px light Inter for support.
- Hold broad media to the 1260px content field with 16px corners.
- Use 60px gutters for three-column feature prose and 12px between title and paragraph.
- Keep dark and outlined actions compact at 35px, with 8px corners.
- Use the 37px yellow band as a small recurring signal while the rest of the canvas stays neutral.
- Make the product collage connected and edge-clipped, with an open center around the message.
- Close with a genuinely useful six-column black directory using 14px gray links.

### Don't

- Do not make the primary CTA yellow; the measured primary is charcoal.
- Do not turn every explanatory paragraph into a bordered or shadowed card.
- Do not set uppercase eyebrows with positive luxury-style tracking; these labels use -0.5px.
- Do not enlarge all action heights to 48px or use pill-shaped CTA silhouettes.
- Do not spread the device-stage violet across ordinary content sections.
- Do not recolor trust marks into full-saturation brand mosaics; the proof row is muted gray.
- Do not make pricing amounts use the light headline face; they use Inter 600.
- Do not apply the language-menu shadow to all permanent surfaces; media and plan cards are flat.

## Motion and responsive

### Motion

**Observed:**

- Footer links declare color 0.2s transitions and turn white on hover.
- Logo strips declare client-logos-scroll 80s linear infinite.
- Other actions and surfaces include opacity 0.2s transitions; product demonstrations use video or interactive media.

**Transfer:**

- Keep trust-strip movement slow enough to read as a continuous quiet interval.
- Use rich motion inside the product stage, not as decorative motion applied to every paragraph.

**Unknown:**

- Specific film playback sequences, scroll-animation timings and component-specific easing beyond the listed declarations are not established.
- Focus-visible styling is not established.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 767px, 991px and 1440px, among others.
- The desktop content uses a centered 1320px container with 30px inner side padding.

**Transfer:**

- On narrow layouts, preserve the open center of the connected collage by clipping peripheral clusters rather than shrinking the whole board into illegibility.
- Stack feature and split-story columns while retaining the distinction between large proof media and compact prose.
- Let plan comparisons scroll horizontally or become deliberately structured stacked comparisons; retain clear label-to-plan relationships.

**Unknown:**

- Exact mobile navigation, headline sizes, stacking order and breakpoint-specific spacing are not established; the transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
