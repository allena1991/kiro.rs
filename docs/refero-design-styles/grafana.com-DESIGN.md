# Grafana — pastel power, technical warmth

## Overview

An approachable technical style that makes a complex software platform feel expansive rather than intimidating. A pale gray canvas, peach-to-lilac-to-aqua atmosphere, blue actions and black geometric sans headlines surround substantial interface imagery. Dense product detail alternates with open, warmly human sections, while a playful oversized closing identity keeps the experience from becoming purely corporate.

### Essentials

- Confident headlines sound like paired promises: Poppins 600, 60px/1.25 with -0.025em tracking for the opening and 48px/1.125 with -0.025em for major section headings.
- The opening is a compact promise, not a giant device mockup: a 1152px centered headline above a 672px support line, two labeled 48px actions, a glowing 1024px question bar and a monochrome proof strip within the first 900px.
- Actions are blue rectangles with softened corners, not pills: #1b55f5, 8px radius, 12px 20px padding and Inter 18px/28px 600; the secondary action blends into the pale canvas.
- Color lives around the machinery: most reading areas stay #f4f4f6 or white; full-width pastel gradients mark opening and conversion moments, and lilac, blue and peach 24px-radius frames hold dark product views.
- Technical breadth gets a diagrammatic pause: fine concentric rings carry small white circular tool badges around a centered message. Recreate the rings and neutral category glyphs when recognizable integrations are unavailable.
- The ending has a memorable scale change: a 1248px-wide identity artwork with a dimensional playful emblem and pale wordmark, followed by a black 30px Poppins invitation. Use the new product’s own oversized name and a simple dimensional emblem rather than ending with links alone.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric action blue | `#1b55f5` | `--color-action` | action, link, text | Primary actions, inline links and arrow links. |
| Signal orange | `#ff671d` | `--color-orange` | accent, border | Active tab underline, short heading dashes and category markers; not the default button fill. |
| Blue action edge | `#1440e1` | `--color-action-edge` | border, action | Primary button border and hover fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Peach edge | `#ffae70` | `--color-peach-edge` | border | Outline paired with peach framing. |
| Blue frame edge | `#8ec0ff` | `--color-blue-edge` | border | Outline paired with blue media framing. |
| Atmospheric aqua | `#7be7e7` | `--color-gradient-aqua` | background | Cool end of the pastel gradient. |
| Atmospheric peach | `#f7bfa3` | `--color-gradient-peach` | background | Warm end of the full-width pastel gradient. |
| Atmospheric sky | `#a3d8f7` | `--color-gradient-blue` | background | Cool middle of the pastel gradient. |
| Lilac edge | `#eeaafd` | `--color-lilac-edge` | border | Outline paired with lilac framing. |
| Warm human-story backing | `#fad8ac` | `--color-community` | surface | Visible warm backing made with rgba(255,187,98,0.5) over the canvas. |
| Atmospheric lilac | `#e6b3e6` | `--color-gradient-lilac` | background | Middle of the pastel gradient. |
| Peach media wash | `#ffe8dd` | `--color-peach` | surface | Product media framing and a product-benefit panel. |
| Lilac media wash | `#f9e8ff` | `--color-lilac` | surface | Product media frame. |
| Blue media wash | `#eaf0ff` | `--color-blue-wash` | surface | Product media frame and small submit-button backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Headline black | `#000000` | `--color-ink` | text | Headlines and high-emphasis labels. |
| Editorial charcoal | `#2b2d32` | `--color-dark-panel` | surface | Occasional editorial feature cards, not the page canvas. |
| Secondary action charcoal | `#2e2e38` | `--color-secondary-ink` | text | Text on pale secondary actions and editorial cards. |
| Body charcoal | `#454554` | `--color-body` | text | Default explanatory text. |
| Muted slate | `#67677e` | `--color-muted` | text | Hero support, secondary paragraphs, navigation and metadata. |
| Panel hairline | `#d8d8df` | `--color-rule` | border | Cards, fields, quote panels and tab baselines. |
| Catalog gray | `#e6e6ea` | `--color-soft-panel` | surface, border | Capability catalog backing, footer dividers and secondary button hover. |
| Cool pale canvas | `#f4f4f6` | `--color-canvas` | background, surface | Default marketing background and secondary action fill. |
| Near-white footer | `#f9f9fa` | `--color-footer` | background, text | Long footer band; also light text on dark contact actions. |
| White panels | `#ffffff` | `--color-white` | surface, text | Cards, fields, navigation and text over dark panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and product plan comparisons | Contact black | `#17171c` | `--color-contact` | action | Sales-contact button fill. |
| pricing pages | Savings mint edge | `#73e2a7` | `--color-savings-edge` | border | Outline of cost-saving callouts. |
| pricing pages | Savings mint | `#d1f0e1` | `--color-savings` | surface | Cost-saving explanatory callouts. |

## Typography

- **Poppins** — Headlines, feature titles, tab labels, quotes and the closing invitation. Rounded geometric sans with a friendly single-storey character; semibold headings feel substantial without condensed aggression. Font stack: "Poppins", sans-serif.
- **Inter** — Body text, actions, navigation, plan detail and metadata. Compact, practical sans for technical explanations and dense comparison content. Font stack: "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Poppins | 600 | 60px | 1.25 | -0.025em | Centered marketing promise. |
| heading-lg | Poppins | 600 | 48px | 1.125 | -0.025em | Major section leads; also the default headline for narrower split product and company openings. |
| heading | Poppins | 600 | 36px | 1.25 | normal | Compact centered chapters and conversion headings. |
| feature-heading | Poppins | 600 | 30px | 1.25 | -0.025em | Titles beside product media and FAQ group headings. |
| footer-heading | Poppins | 600 | 30px | 1.35 | -0.02em | Question and newsletter prompts in the footer. |
| closing-line | Poppins | 600 | 30px | 1.25 | -0.02em | Playful invitation under the monumental footer identity. |
| label-heading | Poppins | 600 | 24px | 1.25 | -0.025em | Subsection titles and short labels above larger headings; not tiny uppercase eyebrows. |
| quote | Poppins | 500 | 24px | 1.25 | -0.025em | Customer quotations inside wide white panels. |
| hero-support | Inter | 400 | 20px | 1.4 | normal | Centered one-line support beneath the main promise. |
| tab-label | Poppins | 600 | 20px | 1.375 | normal | Customer and demonstration tab labels; also accordion questions. |
| action | Inter | 600 | 18px | 28px | normal | Opening and major conversion buttons. |
| directory-heading | Inter | 600 | 18px | 1.375 | normal | Footer directory column headings. |
| body | Inter | 400 | 16px | 1.5 | normal | Default explanatory paragraphs and inline links. |
| action-compact | Inter | 600 | 16px | 1.5 | normal | Feature arrow links and compact conversion buttons. |
| tile-label | Inter | 500 | 16px | 1.25 | -0.025em | Compact capability catalog entries. |
| directory-link | Inter | 500 | 14px | 1.375 | normal | Footer directory links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing and product plan comparisons | plan-name | Poppins | 600 | 30px | 1.25 | -0.025em, capitalize | Plan titles. |
| pricing and product plan comparisons | plan-detail | Inter | 400 | 14px | 1.5 | normal | Dense plan descriptions, billing units and qualifiers. |

**Notes:**

- Poppins owns the expressive hierarchy; Inter carries practical reading and actions. Keep large Poppins headlines at 600 rather than escalating to 800.
- Tracking is -0.025em for the largest headings and 30px feature titles, but normal at 36px and for 20px tab labels. Do not mechanically tighten every role.
- Section leads can be centered; split feature titles align left. The closing identity is artwork rather than a normal display heading.
- Use sentence case, including descriptive labels above headings. Reserve all-capital labels for narrowly scoped comparison navigation.

## Layout

**Density:** Airy marketing chapters surround compact, information-rich cards and comparison rows.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small label-to-heading gaps and stacked footer link gaps. |
| 12px | Small control groups and capability grid gutters. |
| 16px | Heading-to-support gaps and ordinary text stacks. |
| 24px | Catalog panel padding, card interiors and compact section gaps. |
| 32px | Heading-to-tabs gap, paired action gap and footer column gutter. |
| 36px | Three-column plan-card gutters. |
| 48px | Split feature column gutter and heading-to-card gap. |
| 64px | Standard section vertical padding, feature-row separation and quote-panel padding. |
| 80px | Desktop footer vertical padding. |
| 96px | Top breathing room for the broad gradient conversion scene. |

### Containers and grids

- **container**: max width 1280px · side padding 16px. Centered outer wrapper. At 1440px it starts at 80px; interior text and media occupy 1248px.
- **opening-copy**: max width 1152px. Broad centered headline block with a 672px support measure.
- **text-island**: max width 672px. Centered explanation surrounded by a diagram or generous open canvas.
- **feature-split**: 2 columns · gap 48px. Equal 600px columns inside the content wrapper, vertically centered; alternate the media side.
- **capability-grid**: 4 columns · gap 12px. Compact white entries on a single pale-gray rounded backing.
- **footer-directory**: 6 columns · gap 32px. Long narrow columns separated from the question/newsletter row by a hairline.
- **plan-grid** (only for pricing and product plan comparisons): 3 columns · gap 36px. Equal 392px cards with aligned title, price, action and benefits rows.
- **comparison-detail** (only for pricing pages): max width 1000px · gap 24px. Detailed comparison panels beside a 224px category rail; panels stack with 32px gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 8px |
|  | small-panels | 12px |
|  | quote-and-media | 16px |
|  | feature-media-and-plans | 24px |
|  | human-story-panel | 32px |
|  | tool-badges | 50% |
| company and team pages | portrait-cards | 48px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| button | `0px 1px 2px 0px rgba(0,0,0,0.05)` | Subtle grounding on filled actions. |
| tile | `0px 1px 3px 0px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)` | Small white capability tiles; large media frames rely on outlines instead. |
| question-glow | `0px 0px 20.4px 0px rgba(255,141,54,0.4)` | Warm halo around the opening question bar. |

### Surfaces

#### Canvas · level 0

**Use:** Default reading surface.

**CSS:** `background: #f4f4f6`

**Observed:** A continuous pale-gray field unifies separate feature chapters.

**Transfer:** Let whitespace and media carry chapter boundaries rather than boxing every paragraph.

#### Pastel atmosphere · level 0

**Use:** Opening background.

**CSS:** `background-image: linear-gradient(rgba(255,255,255,0), #f4f4f6 80%), linear-gradient(120deg, #f7bfa3 10%, #e6b3e6 40%, #a3d8f7 75%, #7be7e7)`

**Observed:** Warm left, lilac center, aqua right; strongest immediately below the white navigation and fading downward into the canvas.

**Transfer:** Keep the black headline legible over a soft continuous gradient, without separate colored blobs.

#### Conversion atmosphere · level 0

**Use:** Broad late-page conversion scene.

**CSS:** `background-image: linear-gradient(#f4f4f6 20%, rgba(255,255,255,0)), linear-gradient(120deg, #f7bfa3 10%, #e6b3e6 40%, #a3d8f7 75%, #7be7e7)`

**Observed:** Reverses the opening fade: text begins on near-neutral space and color strengthens behind overlapping light interface windows.

**Transfer:** Give the product scene a colorful landing area while leaving the heading calm.

#### Pastel media frame · level 1

**Use:** Backing for a feature’s dark interface view.

**CSS:** `background: #f9e8ff; border: 1px solid #eeaafd; border-radius: 24px; overflow: hidden`

**Observed:** Blue wash with blue edge and peach wash with peach edge are sibling variants. The interface is inset from the top and left, but runs out of the right and bottom edges.

**Transfer:** Use a single tonal pair per feature, not a multicolor border.

#### Catalog backing · level 1

**Use:** A grouped capability directory.

**CSS:** `background: #e6e6ea; border: 1.5px solid #d8d8df; border-radius: 24px; padding: 24px`

**Observed:** A single backing holds many smaller white entries, with category labels between groups.

**Transfer:** Make breadth readable as a map rather than many independent large cards.

#### Human-story backing · level 1

**Use:** Warm editorial chapter with photography.

**CSS:** `background: rgba(255,187,98,0.5); border-radius: 32px; overflow: hidden`

**Observed:** Text occupies the left half while narrow staggered photo columns fill the right and are clipped by the panel.

**Transfer:** Use a warm backing for an authentic human proof story, not for ordinary technical detail.

#### Footer band · level 0

**Use:** Shared question, newsletter, directory and identity ending.

**CSS:** `background: #f9f9fa; padding-top: 80px; padding-bottom: 80px`

**Observed:** Slightly lighter than the main page and divided internally by subtle rules.

**Transfer:** Preserve the light ending even when a dark demonstration appears earlier.

#### Savings callout · level 1

**Only for:** pricing pages

**Use:** Explain a cost-saving mechanism between plan rows and FAQs.

**CSS:** `background: #d1f0e1; border: 1px solid #73e2a7; border-radius: 8px; padding: 24px`

**Observed:** A quantified lead sits over a small orange dash, mechanism heading, support paragraph and blue arrow link.

**Transfer:** Tie the bright callout to a concrete efficiency mechanism rather than a generic promotional offer.

## Components

### Primary button

**Use:** Default opening and major conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #1b55f5; color: #ffffff; border: 1px solid #1440e1; border-radius: 8px; padding: 12px 20px; height: 48px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `action` — Inter 600 · 18px/28px

**Observed:** Paired with a pale secondary button. A short qualifying label sits above each action in the major conversion groups. Compact product and plan variants use 44px height, 10px 18px padding and action-compact type; the sales-contact variant is near-black.

**States:** Declared: hover background #1440e1 and border #1734b6; focus-visible retains the subtle 0px 1px 2px rgba(0,0,0,0.05) shadow.

### Secondary button

**Use:** Plan exploration beside the main conversion action.

**CSS:** `background: #f4f4f6; color: #2e2e38; border: 1px solid #f4f4f6; border-radius: 8px; padding: 12px 20px; height: 48px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `action` — Inter 600 · 18px/28px

**Observed:** Equal height to the primary, but quiet enough to merge with the canvas; not an outlined blue button.

**States:** Declared: hover background and border #e6e6ea; focus-visible retains the subtle button shadow.

### Arrow text link

**Use:** Feature-level exploration rather than primary conversion.

**CSS:** `display: inline-flex; align-items: center; color: #1b55f5; padding: 10px 0px; border-radius: 8px; gap: 2px`

**Text style:** `action-compact` — Inter 600 · 16px/1.5

**Observed:** A right arrow follows the wording. Inline paragraph links use body type with an underline instead.

**States:** Declared: hover for inline blue links changes color to #1734b6; focus-visible for arrow links adds an underline.

### Framed feature media

**Use:** A focused interface proof beside a short benefit explanation.

**CSS:** `position: relative; background: #f9e8ff; border: 1px solid #eeaafd; border-radius: 24px; overflow: hidden`

**Observed:** A 600px by 427px desktop frame encloses a 566px by 393px interface view inset 32px from the top and left. Its right and bottom edges bleed into the rounded clipping. Blue and peach frames rotate across chapters.

**Transfer:** Show one legible work surface from the new product, not a full browser reduced to a tiny thumbnail.

### Capability tile

**Use:** Compact linked capability entry inside Catalog backing.

**CSS:** `display: flex; align-items: center; gap: 12px; height: 68px; padding: 0px 20px; background: #ffffff; border: 1px solid rgba(230,230,234,0.5); border-radius: 12px; box-shadow: 0px 1px 3px 0px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Text style:** `tile-label` — Inter 500 · 16px/1.25 · tracking -0.025em

**Observed:** A small rounded colored square precedes a label limited to two lines; the desktop entries are 298px wide.

**Transfer:** Group entries by meaningful capability families and keep titles short.

### Underlined tabs

**Use:** Switch between customer stories or product demonstrations.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; position: relative; padding: 8px 32px; height: 44px; color: #000000`

**Text style:** `tab-label` — Poppins 600 · 20px/1.375

**Observed:** Centered tab group sits on a 2px gray baseline. The selected item has a thin orange underline with 2px-rounded ends; inactive text is muted. The content panel begins 24px below.

**States:** Declared: focus-visible uses a 1px solid #f4f4f6 outline and matching border color.

### Customer quote panel

**Use:** Substantial social proof rather than a tiny quote card.

**CSS:** `background: #ffffff; border: 1.5px solid #d8d8df; border-radius: 16px; padding: 64px; display: grid; gap: 64px`

**Text style:** `quote` — Poppins 500 · 24px/1.25 · tracking -0.025em

**Observed:** A 1248px-wide panel holds a square photographic customer tile on the left and a vertically centered quotation with name and role on the right. The quote takes about two thirds of the content width.

**Transfer:** Use a customer’s own environment or product context behind a simple logo, with a short outcome-oriented quotation.

### Question input

**Use:** Footer self-service question field.

**CSS:** `background: #ffffff; border: 1px solid #d8d8df; border-radius: 8px; padding: 12px 44px; max-width: 600px`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** An orange sparkle leads the prompt; a small circular arrow submit sits inside the right edge. The email companion uses ordinary side padding and a blue Subscribe button outside the field.

**Transfer:** Make the question concrete and low-effort rather than presenting a generic contact form.

### Glowing question bar

**Use:** Prominent self-service entry under the opening actions.

**CSS:** `display: flex; align-items: center; gap: 12px; background: #ffffff; border: 1.5px solid rgba(255,183,29,0); border-radius: 12px; padding: 12px 16px; max-width: 1024px; box-shadow: 0px 0px 20.4px 0px rgba(255,141,54,0.4)`

**Text style:** `label-heading` — Poppins 600 · 24px/1.25 · tracking -0.025em

**Observed:** The bold short label sits beside a sparkle, a slim vertical divider, a quiet input prompt and a pale-blue circular submit arrow.

**Transfer:** Retain the warm halo as a small accent against the otherwise cool opening; the field can search documentation if an assistant is not appropriate.

### Plan card

**Only for:** pricing and product plan comparisons

**Use:** Top-level plan comparison.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 32px 8px; display: grid; row-gap: 8px; column-gap: 24px; box-shadow: none`

**Text style:** `plan-name` — Poppins 600 · 30px/1.25 · tracking -0.025em · capitalize

**Observed:** Inner rows have another 24px of side padding. Title and small plan badge share a row, followed by qualifier, 24px price, billing unit, description, full-width action and checkmarked benefits. Cards align across rows rather than emphasizing one with a large scale change. Detailed catalog variants join three columns with vertical rules inside one 12px-radius outlined panel.

**Transfer:** Keep payment qualifiers adjacent to the price; use blue actions for self-service and near-black for sales contact.

### FAQ row

**Only for:** pricing pages

**Use:** Objection handling within each detailed comparison panel.

**CSS:** `border-bottom: 1px solid #d8d8df`

**Text style:** `tab-label` — Poppins 600 · 20px/1.375

**Observed:** A full-width question button has 24px top and 32px bottom padding, with a small chevron at the far right. Repeated rows are about 85px high when closed, with no separate card background. The last row drops the divider.

**Transfer:** Ask billing and usage questions in the reader’s language.

## Imagery and graphics

### Technical interface proof

**Use:** Feature rows, product openings and demonstration chapters.

**Observed:** Mostly dark, crisp application views with tiny colored charts, tables and controls; displayed front-on rather than in tilted devices. Feature views occupy roughly half a row inside Pastel media frame. A large tabbed demonstration can span the full 1248px content width.

**Transfer:** Use real product work surfaces when available. Otherwise create a credible static interface with readable hierarchy, a sidebar and one meaningful work area; do not replace the product with abstract floating cards.

### Concentric ecosystem field

**Use:** A diagrammatic visual pause establishing connectedness.

**Observed:** Five fine concentric circular outlines extend beyond the viewport; white circular badges carrying colored tool marks float along them. Fades soften the top and bottom so the centered 672px text island remains the focus.

**Transfer:** Keep this diagrammatic pause in the page vocabulary. If there are no integrations, use neutral icons representing inputs, teams or outputs.

**Build:** Center five 1px rgba(0,0,0,0.06) circles ranging from 612px to 1620px in diameter inside a 720px-high overflow-hidden canvas. Place 40px–56px white circular badges on ring coordinates, with tiny grounding shadows. Layer canvas-to-transparent gradients over the upper and lower 192px edges; keep a clear central area for text.

### Overlapping light product windows

**Use:** Large gradient conversion scene.

**Observed:** A 1280px-wide composite rises from the bottom edge: the largest light interface is centered in front, with smaller windows stepped lower behind it. White surfaces, soft depth shadows and pastel charts replace the darker feature imagery.

**Transfer:** Make a layered front-on composition of the new product’s primary work surface and two supporting views. Minimum version: one convincing light interface with two simpler contextual panels; keep all windows grounded to the section bottom.

**Build:** Use absolutely positioned rounded interface panels in a 1280px-wide, 434px-high clipping area. Center the tallest panel in the foreground; place narrower rear panels lower on either side, with a small additional lower-left panel. Add soft black alpha shadows and place the assembly over Conversion atmosphere. Keep the top browser/tool bars subtle.

### Human photo columns

**Use:** Warm editorial proof and company storytelling.

**Observed:** Candid people working, talking and presenting, with natural light and occasional saturated event lighting. Two staggered narrow columns mix 192px-wide landscape and portrait frames. Some images have ordinary rounded corners while others end in a deep U-shaped curve; the warm panel clips the columns at top and bottom.

**Transfer:** Use authentic people in the new product’s working context, not isolated stock portraits. Preserve the alternating silhouettes and edge clipping.

**Build:** Place two 192px-wide vertical photo stacks with a 16px gap on the right half of Human-story backing. Offset one stack vertically, mix 176px–256px image heights and alternate rounded rectangles with semicircular lower corners. Clip at the outer 32px-radius panel.

### Dimensional footer identity

**Use:** The final branded scale change after the link directory.

**Observed:** A wide pale-gray wordmark spans most of a 1248px-wide by 267px-high image. At its left a small glossy, golden, sprinkled pastry-like emblem supplies rich material and humor against the extremely restrained lettering.

**Transfer:** Use the new product’s own name at monumental width plus a dimensional emblem that relates to its identity. Minimum version: oversized pale lettering and a shaded SVG emblem with a highlight, bevel-like inner contour and a soft contact shadow.

**Build:** Create a single horizontal SVG or HTML composition: pale oversized wordmark on the right, emblem occupying roughly the left sixth. Construct the emblem from a rounded silhouette with a warm gradient, inset highlight and soft shadow; add a few bright small marks if appropriate. Keep the wordmark flat and low contrast so the object supplies the material interest.

### Company portraits and quantified art

**Only for:** company and team pages

**Use:** People introductions and company-scale proof.

**Observed:** Three square head-and-shoulders portraits have 48px corners and subtle colored light near their lower edge. Separate narrative rows use 600px-square photographic or illustrated assets with large asymmetric corner curves. One quantified illustration contains a two-by-two set of pastel outlined tiles, each with an outline icon, large saturated numeral and small dark caption.

**Transfer:** Use real team portraits with light color grading. For quantified proof, pair each metric with its own tonal icon and backing; keep numbers as honest business evidence rather than decorative counters.

**Build:** For the quantified illustration, arrange four equal rounded rectangles in a two-column SVG or CSS grid, using peach, blue, mint and lilac tonal families. Put an outline symbol upper left, a prominent number below it and a two-line caption at the bottom; avoid photographic texture behind numbers.

### Icons

**Observed:** Marketing utility icons are generally 16px or 18px outline SVGs with 2px rounded strokes. Arrows follow blue links, small chevrons trail navigation and accordion controls, and orange sparkles mark question tools. Category entries use tiny solid rounded squares instead of a full icon library.

**Transfer:** Choose simple rounded outline symbols for utilities; use color sparingly and do not turn every tile into a large illustrated icon.

## Section recipes

How recurring sections are built.

### First screen: Centered atmospheric opening

**Observed:** A 78px white sticky header has a 33px announcement tier over a 45px navigation tier. Beneath it, Pastel atmosphere backs a centered 1152px-wide promise, set in display type over two balanced lines at desktop. The headline begins after 64px of breathing room. A 672px support measure follows after 16px; a paired action group follows after 32px. Each action has a short qualifying line above it, and the buttons are separated by 32px. The Glowing question bar follows on the neutral canvas, then a centered trust sentence and a horizontal strip of small black customer marks. Within the first 900px, the complete promise, support, both actions, question bar, proof strip and next major heading are visible. There is no giant product object in this opening; the first pastel-framed interface begins at the lower edge and continues below the fold.

**Transfer:** For a new product, write an equally broad but concrete two-part promise, keep the labeled action pair and glowing question/search entry, and use a credible partner or customer proof strip. Put the main interface in the next chapter rather than forcing it behind the headline. A narrower product page can instead open with 48px left-aligned text beside a 604px-wide interface; a company page opens with text beside staggered candid photographs; a pricing page opens with a compact centered 48px position statement and plan cards.

**Avoid:** Do not make a full-screen dark dashboard hero, add a floating 3D device above the actions, or push all proof and the next chapter below the first viewport.

**Text style:** `display` — Poppins 600 · 60px/1.25 · tracking -0.025em

### Section lead and support

**Observed:** Major chapter heading uses heading-lg, with support after 16px and a restrained measure. A smaller label can sit 8px above it in label-heading rather than tiny widely tracked capitals.

**Transfer:** State a benefit or chapter idea first, then explain the mechanism in one short paragraph.

**Text style:** `heading-lg` — Poppins 600 · 48px/1.125 · tracking -0.025em

### Alternating feature proof

**Observed:** Feature-split holds a colored outline icon, feature-heading, body copy and Arrow text link beside Framed feature media. Successive rows swap media side and have 64px separation. Text and media are vertically centered rather than aligned to the top of a large empty card.

**Transfer:** Give each row one outcome and one interface detail that makes it believable; use the three tonal frame families to distinguish capabilities.

**Text style:** `feature-heading` — Poppins 600 · 30px/1.25 · tracking -0.025em

### Ecosystem pause

**Observed:** Concentric ecosystem field surrounds a centered heading and a short explanation, followed by a blue arrow link. A 720px-high field gives this technical proof an unusually spacious, almost diagrammatic rhythm.

**Transfer:** Use this as a connecting idea between denser capability chapters, keeping the center legible.

**Text style:** `heading` — Poppins 600 · 36px/1.25

### Capability map

**Observed:** Centered heading-lg and support lead into Catalog backing. Category labels divide a four-column set of Capability tiles; white entries use small colored markers and compact two-line labels. A separate trust row places six small certification tiles beside a short title and blue link.

**Transfer:** Present breadth in grouped, scan-friendly entries. Use only substantiated trust marks and let them stay visually smaller than the product story.

**Text style:** `heading-lg` — Poppins 600 · 48px/1.125 · tracking -0.025em

### Immersive demo invitation

**Observed:** A wide dark interface image fills a roughly 1280px-wide by 418px-high rounded banner. White heading and short support sit centered over subdued charts, with a white arrow link below.

**Transfer:** Darken or soften a representative product view just enough to support centered invitation text; this is a localized visual contrast, not a dark theme for the whole page.

**Text style:** `heading` — Poppins 600 · 36px/1.25

### Editorial carousel

**Observed:** Wide 24px-radius cards alternate charcoal and pale-blue backings. A card combines headline, concise paragraph and text action with a photographic panel; neighboring cards peek beyond the content area. Small 32px circular previous/next buttons sit below.

**Transfer:** Use for timely stories or independent proof assets, not to hide core capabilities behind slides.

**Text style:** `heading` — Poppins 600 · 36px/1.25

### Tabbed customer proof

**Observed:** Centered heading-lg precedes Underlined tabs by 32px; Customer quote panel begins 24px below the tabs. A square photographic logo tile balances a black Poppins quote and smaller Inter attribution.

**Transfer:** Let readers choose among different use cases while preserving one substantial proof story at a time.

**Text style:** `quote` — Poppins 500 · 24px/1.25 · tracking -0.025em

### Warm human chapter

**Observed:** Human-story backing holds a left-aligned heading-lg and 18px explanatory paragraph, then a vertical list of blue arrow links. Human photo columns fill the right half; the 1248px-wide panel is 600px high.

**Transfer:** Use for a people-centered reason to trust or participate in the product, without requiring a company-community topic.

**Text style:** `heading-lg` — Poppins 600 · 48px/1.125 · tracking -0.025em

### Gradient conversion stage

**Observed:** Conversion atmosphere begins with 96px top space. A centered label-heading, heading-lg and support lead to labeled Primary button and Secondary button choices. Overlapping light product windows occupy the bottom 434px and are clipped flush where the footer begins.

**Transfer:** Restate the broad promise with a direct low-friction next step, and give the product a final luminous stage rather than another plain CTA card.

**Text style:** `heading-lg` — Poppins 600 · 48px/1.125 · tracking -0.025em

### Complete light ending

**Observed:** Footer band starts with a wide question area and narrower newsletter area, then a hairline and six directory columns with 32px gaps. Below another hairline, Dimensional footer identity spans the content width; closing-line sits 16px below the artwork. A small legal row and six 48px circular social links complete the ending.

**Transfer:** Keep the contrast between useful dense links and the oversized playful identity. Adapt the question/newsletter balance to real support and subscription needs while retaining the monumental close.

**Text style:** `closing-line` — Poppins 600 · 30px/1.25 · tracking -0.02em

### Plan comparison and detailed catalog

**Only for:** pricing pages

**Observed:** A short gradient position statement leads into three Plan cards. Supporting philosophy cards and a calculator explain the model before a long category rail plus white detailed panels. Each detail panel has a 36px service heading, description, three joined plan columns, optional Savings callout and FAQ rows. The closing call is a pale rounded inset panel with a 36px heading and blue plus near-black actions; Footer band follows.

**Transfer:** Start with decision clarity, then provide unit economics and local objections; keep the long catalog navigable with a category rail.

**Text style:** `plan-name` — Poppins 600 · 30px/1.25 · tracking -0.025em · capitalize

### Company narrative and principles

**Only for:** company and team pages

**Observed:** A pastel opening combines a 24px label, 48px promise and body text with three staggered photographs. A raised white origin-story panel is followed by alternating 600px media-and-text narratives, a three-person portrait row, quantified art and a four-column principle grid. Each principle begins with a 20px-wide orange dash, an 18px bold title and 16px support. A two-choice exploratory closing band precedes the shared footer.

**Transfer:** Tell the organization’s story through people and operating principles; use the dense principles grid only when the content warrants this page type.

**Text style:** `heading-lg` — Poppins 600 · 48px/1.125 · tracking -0.025em

## Page flow

**Storyline:** Promise → tangible capability proof → breadth and compatibility → trust and human proof → low-friction next step → useful directory and playful monumental close.

### Broad platform marketing landing page

1. **Promise** — Centered atmospheric headline, labeled action pair, glowing question entry and compact logo proof.
2. **Capability proof** — Alternating pastel-framed interface rows followed by the concentric ecosystem pause.
3. **Breadth and trust** — Grouped capability map, trust marks and immersive demonstration banner.
4. **Social and human proof** — Editorial cards, tabbed customer quotation and warm photographic story.
5. **Closing call** — Gradient conversion stage with overlapping light product windows, then the complete light ending.

**Transfer:** Use the reference rhythm of technical density and warm relief; choose the chapters that best support the new promise rather than reproducing a fixed count.

### Specific product explanation and evaluation

1. **Promise and demonstration** — Compact split opening puts a 48px promise beside a dark interface, followed by three concise benefit columns.
2. **Product exploration** — Large tabbed demonstrations lead into alternating explanations with stills or short videos.
3. **Social proof** — Tabbed customer quote panel.
4. **Commercial clarity** — Three compact plans followed by an explanatory accordion-like product panel and peach trust-and-benefit panel.
5. **Closing call** — Gradient conversion stage and the complete light ending.

**Transfer:** Bring the actual product surface forward earlier than on a broad platform page, then connect feature detail to proof and a buying decision.

### Pricing evaluation and detailed objection resolution

1. **Position and choice** — Compact centered statement above three equal plan cards.
2. **Model explanation** — Three philosophy cards and an interactive cost calculator.
3. **Detailed comparison** — A category rail tracks a long sequence of white three-plan comparison panels with local FAQs and savings explanations.
4. **Closing call** — Pale inset sign-up panel with blue self-service and dark contact actions, then the complete light ending.

**Transfer:** Let the page become denser as intent increases; maintain the same headings, rules and button language across every comparison.

### Company credibility and participation

1. **Mission with human context** — Split pastel opening with candid photographs and a compact mission statement.
2. **Origin and evolution** — White story panel, explanatory narrative and three generous portrait cards.
3. **Operating credibility** — Alternating photographic chapters, a quantified pastel illustration and a dense principle grid.
4. **Invitation** — People-focused invitation and two exploratory choices in a soft closing band.
5. **Shared ending** — Question and newsletter row, directory, oversized dimensional identity and closing invitation.

**Transfer:** Use a warmer and more photographic variant while preserving the geometric type hierarchy and pale canvas.

## Writing

Confident, practical and technically literate, but not cold. Big claims are expressed as useful outcomes, then supported by specific mechanisms; small moments of humor make the platform feel human.

**Do not copy:** Do not reuse Grafana names, logos, mascots, pastry artwork, customer identities, quotations, certification claims, event promotions, usage figures, prices or proprietary product claims. Source examples illustrate cadence only; write truthful equivalents for the new product.

- **Addressing the reader:** Speak directly to teams as you when explaining a benefit; use we for the organization’s convictions and working practices. Product explanations can use the product name as the subject.
- **Rhythm:** Short balanced headline clauses, often two or three punctuated promises. Support text is more explicit and technical; calls to action are short verbs with a clear destination. Humor is concentrated near invitation and closing moments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Balanced reciprocal or paired outcome statements, ending in a simple unifying promise. | 6–14 words across two or three clauses | “AI for observability. Observability for AI. One platform for both.”<br>“Dashboard anything. Observe everything.” |
| Section heading | Short parallel benefits or a memorable contrast. | 4–9 words | “See clearly. Act faster. Spend smarter.”<br>“Plug in, not lock in” |
| Supporting line | Name the actual product category or operating mechanism without inflated adjectives. | One short sentence; detailed feature paragraphs can run longer | “Full-stack observability with [Brand] Cloud”<br>“Automatically unlock volume discounts based on consumption.” |
| Primary action | Verb plus concrete next step, often reassuring about commitment. | 2–4 words | “Get started free”<br>“Create free account” |
| Closing invitation | A small verbal wink paired with a direct invitation. | One compact sentence pair | “Donut take our word for it. Try today.”<br>“Sign-up time” |

**Words and phrasing to use:** connect; understand; turn into action; built on; real; open; faster; only pay for; no lock-in; get started

**Avoid:** revolutionary synergy; unparalleled excellence; frictionless magic; disrupt everything; vague AI superlatives

**Rules:**

- Lead with a reader outcome, then explain the concrete feature that enables it.
- Use paired clauses when two ideas reinforce one another; do not make every paragraph a slogan.
- Put billing units, limits and commitments next to the associated price or action.
- Use technical nouns accurately and unpack the benefit for the team.
- Keep playful language rare enough that the closing moment feels earned.

## Do's and Don'ts

### Do

- Use the 60px/75px Poppins promise and the 48px/54px section lead as distinct hierarchy levels.
- Keep the default content wrapper at 1280px with 16px inner side padding.
- Balance 600px feature columns with a 48px gutter and alternate media sides.
- Pair pastel fills with their corresponding 1px tinted outlines and 24px corners.
- Keep major buttons 48px high with 8px corners; use the compact 44px variant in denser product contexts.
- Use 64px chapter padding and reserve 96px top space for the broad conversion stage.
- Keep customer proof substantial: 64px panel padding, a square photo tile and 24px Poppins quotation.
- Preserve the final identity artwork at content width rather than shrinking it to a normal footer logo.

### Don't

- Do not substitute a condensed display face or a serif for the geometric Poppins hierarchy.
- Do not turn the action system into orange pills; blue 8px-radius buttons are the default.
- Do not apply gradients to every card or to all headline text; headlines remain black.
- Do not use black as the whole marketing canvas just because product interfaces are dark.
- Do not give all card types the same radius: controls are 8px, quotes 16px and framed features 24px.
- Do not add heavy elevation shadows to large media frames; their thin tonal outlines do the work.
- Do not expand capability entries into oversized icon cards; their 68px height is part of the information rhythm.
- Do not apply the dense four-column principles treatment to an ordinary product story; it belongs to company narrative.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions commonly use .15s cubic-bezier(.4,0,.2,1); capability tiles use 0.2s with the same curve.
- Declared vertical photo marquees use 60s linear infinite.
- Customer tabs, accordions and editorial carousel controls indicate selectable or expandable content.

**Transfer:**

- Use the short declared transition for blue action and text-color changes.
- If animating the human photo columns, retain a slow vertical drift clipped inside the warm panel rather than a fast horizontal ticker.

**Unknown:**

- Scroll-trigger choreography, carousel autoplay behavior and motion-reduction behavior are not established.

### Responsive

**Observed:**

- Declared layout variants use 640px, 768px, 1024px and 1280px among the stylesheet breakpoints.
- Feature rows declare a single-column base and two columns at the medium layout; feature media is ordered first in the narrow variant.
- Footer directory declares two columns at base, three at medium and six at wider widths. The opening actions declare a vertical base and a horizontal small-screen variant.

**Transfer:**

- On narrow pages, keep the pastel media frame and its clipped interface treatment but stack it above the explanation.
- Stack the labeled action choices without separating a label from its button.
- Let the overlapping conversion windows reduce to a central legible work surface with supporting edges still visible; preserve the pastel landing area and oversized footer identity.

**Unknown:**

- Exact small-screen rendered type sizes, margins and image clipping have not been established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
