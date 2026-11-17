# Websmith — cream canvas, vivid proof

## Overview

An approachable studio style that pairs oversized, tightly set grotesk headlines with a warm cream canvas and richly staged digital work. Black text and compact dark buttons keep the interface direct, while blue, mint and pink capability cards add a playful counterpoint. It suits design-led services and products with tangible work to show, using sparse copy, broad gutters and substantial imagery rather than dense interface chrome.

### Essentials

- A promise reads like a single confident sign: 96px/1 semibold sans, -0.025em tracking, left aligned, with 20px/28px support limited to 580px.
- The opening leaves air before the proof: a 76px sticky masthead, 112px opening padding and 40px headline-to-support gap; two image stages enter the first screen rather than a centered conversion stack.
- Color belongs to contained proof and capability panels: the dominant canvas is #f8f8f2, with white, #bedbff, #a4f4cf and #ffc9c9 cards at 12px radius. Keep these pastel fills localized to a capability cluster, not full-page bands.
- Actions are small black blocks, not pills: #1a1a1a fill, white 20px/28px labels, 16px 32px padding, 60px height and 8px corners.
- Digital proof has physical presence: device or product scenes fill 5:3 frames in a two-column grid with 32px gaps, white upper-left titles and 14px collaborator captions. If no device media exists, stage the actual output as an angled object against a tactile, lit backing.
- The ending is another headline-sized gesture: a white closing plane emerges below the cream wrapper's 24px lower corners, with an 88px/1 invitation, a single dark action and a 1px rule above the utility row.
- Small signs of human presence punctuate the system: a 12px green dot beside local time in the masthead and footer, plus bold black pictograms in the upper-right corners of pastel cards.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pastel mint | `#a4f4cf` | `--color-capability-mint` | surface | Contained capability card fill, paired with ink text. |
| Pastel blue | `#bedbff` | `--color-capability-blue` | surface | Contained capability card fill, paired with ink text. |
| Pastel pink | `#ffc9c9` | `--color-capability-pink` | surface | Contained capability card fill, paired with ink text. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#1a1a1a` | `--color-ink` | text, background, border, action | All primary text, action fills and structural rules. |
| Warm cream | `#f8f8f2` | `--color-canvas` | background, surface | Dominant page wrapper and opaque sticky masthead. |
| Clear white | `#ffffff` | `--color-white` | text, surface, background | Closing plane, first capability card and reversed image and button labels. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Presence green | `#00c950` | `--color-presence` | accent | Tiny local-time status markers; not a general conversion accent. |

## Typography

- **-apple-system** — All marketing text, from display headlines to captions. System grotesk with open lowercase shapes and a compact, firmly weighted display silhouette. Font stack: "-apple-system", system-ui, "Segoe UI", Inter, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | -apple-system | 600 | 96px | 1 | -0.025em | Main promise or project title. |
| closing | -apple-system | 600 | 88px | 1 | -0.025em | Monumental final invitation. |
| heading | -apple-system | 600 | 48px | 1 | -0.025em | Section headings and extended project introductions. |
| statement | -apple-system | 500 | 30px | 1.2 | -0.025em | Capability descriptions and testimonial text. |
| body | -apple-system | 400 | 20px | 1.4 | normal | Opening support, card titles, section labels and primary actions. |
| brand-label | -apple-system | 500 | 20px | 1.4 | -0.025em | Compact masthead word label. |
| utility | -apple-system | 400 | 16px | 1.5 | normal | Navigation and local-time utility text. |
| caption | -apple-system | 400 | 14px | 20px | normal | Collaborator or publication-date line over media. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case studies | case-body | -apple-system | 600 | 20px | 1.4 | normal | Project metadata values and substantial overview paragraphs. |

**Notes:**

- Display, closing, heading and statement recipes share -0.025em tracking; regular body and small labels retain normal tracking.
- Headlines use sentence case and semibold rather than extra-bold. Extended introductions use the heading recipe as a paragraph, not the smaller body recipe.
- Card titles remain regular even when the description below is larger and medium weight. Media captions use white at 0.8 opacity.

## Layout

**Density:** Airy: substantial chapter breaks frame compact two-column groups and short blocks of text.

### Spacing

| Value | Use |
| --- | --- |
| 2px | Gap between media title and secondary caption. |
| 8px | Logo-to-label and status-dot-to-time gaps. |
| 16px | Button vertical padding and short testimonial paragraph separation. |
| 24px | Masthead vertical padding and case-introduction label gap. |
| 32px | Desktop grid gaps, card padding and media-caption inset. |
| 40px | Opening headline-to-support gap and navigation link spacing. |
| 64px | Heading-to-card grid spacing, centered action separation and final wrapper padding. |
| 80px | Case metadata separation and related-work heading-to-media separation. |
| 96px | Case media-to-introduction gap and footer bottom padding. |
| 112px | Opening vertical padding. |
| 128px | Closing plane top padding and case chapter breaks. |
| 176px | Major landing-page chapter separation. |

### Containers and grids

- **Main container**: max width 1340px · side padding 43.2px. Centered outer container. At 1440px the usable content width is 1254px, with approximately 93px visible side margins.
- **Proof and capability grid**: 2 columns · gap 32px. Equal columns, each 611px wide at desktop; used for image proof, capabilities and split testimony.
- **Opening support**: max width 580px. Short support paragraph beneath the left-aligned display headline.
- **Case overview** (only for case studies): max width 640px. A left-anchored text column beneath full-width project introduction and metadata.
- **Case metadata** (only for case studies): 4 columns · gap 32px. Four equal columns with regular labels above semibold values.

## Corner radius

| Element | Radius |
| --- | --- |
| Media and capability cards | 12px |
| Actions | 8px |
| Main wrapper lower corners | 24px |
| Presence indicator | 50% |

## Surfaces and depth

### Surfaces

#### Cream wrapper · level 1

**Use:** Main content plane above the white closing area.

**CSS:** `background: #f8f8f2; border-radius: 0px 0px 24px 24px; padding-bottom: 64px; position: relative; z-index: 40`

**Observed:** Continuous warm surface through opening, proof and capability content; no panel borders or decorative shadows.

**Transfer:** Treat the content as one connected sheet rather than separate alternating full-width backgrounds.

#### White closing plane · level 0

**Use:** Final contact section and utility row.

**CSS:** `background: #ffffff; padding-top: 128px; padding-bottom: 96px`

**Observed:** Sits visually below the rounded cream sheet, changing the material without changing the text color.

**Transfer:** Use the white reveal as a substantial final beat rather than a thin legal footer.

#### Pastel capability surfaces · level 1

**Use:** Short grouped capability explanations.

**CSS:** `background: #ffffff; border-radius: 12px; box-shadow: none`

**Observed:** A white card is paired with blue, mint and pink siblings. Fills are flat; edges have no visible outline.

**Transfer:** Use the four fills to distinguish related capabilities without assigning new text or icon colors.

#### Media legibility veil · level 2

**Use:** Upper portion of image cards behind reversed titles.

**CSS:** `background: linear-gradient(to bottom, rgba(26,26,26,0.6) 0%, rgba(0,0,0,0) 100%); height: 50%; border-radius: 12px`

**Observed:** The dark overlay occupies only the upper half of the image; it is a readability layer, not an independent card background.

**Transfer:** Keep the object visible and fade the veil away before the lower image edge.

## Components

### Sticky masthead

**Use:** Persistent orientation without a separate conversion button.

**CSS:** `position: sticky; top: 0px; z-index: 50; background: #f8f8f2; height: 76px`

**Text style:** `utility` — -apple-system 400 · 16px/1.5

**Observed:** Three-part alignment: compact symbol and word label left, five plain text links centered, green-dot local time right. Navigation is spaced by 40px; the label uses brand-label typography.

**Transfer:** Keep the navigation sparse and the right utility signal human rather than promotional.

### Navigation link

**Use:** Primary page selection.

**CSS:** `color: #1a1a1a; border-bottom: 2px solid #1a1a1a`

**Text style:** `utility` — -apple-system 400 · 16px/1.5

**Observed:** The default shown here is the selected link. Unselected links have no persistent underline; text remains unboxed.

**States:** Declared: hover border-bottom-color #1a1a1a; focus-visible unknown.

### Primary button

**Use:** Conversion and section-level onward navigation.

**CSS:** `background: #1a1a1a; color: #ffffff; border-radius: 8px; padding: 16px 32px; height: 60px; display: flex; align-items: center; gap: 8px`

**Text style:** `body` — -apple-system 400 · 20px/1.4

**Observed:** Width follows the label. Section-end buttons are centered beneath the grid; the final contact action aligns left with its heading.

**States:** Declared: hover background-color #444444; focus-visible unknown.

**Transfer:** Use one clear verb phrase, with the same treatment for contact and browse actions.

### Image proof card

**Use:** Project, product or editorial entry point.

**CSS:** `position: relative; overflow: hidden; border-radius: 12px; aspect-ratio: 5 / 3; color: #ffffff`

**Text style:** `body` — -apple-system 400 · 20px/1.4

**Observed:** Full-bleed object scene with Media legibility veil. Title and secondary caption sit 32px from the upper-left edge with a 2px gap; the latter uses caption typography at 0.8 opacity. There is no separate text well below the image.

**States:** Declared: hover image scale 1.025 with 0.5s transition duration; focus-visible unknown.

**Transfer:** Keep titles short and put attribution or date on the secondary line.

### Capability card

**Use:** Explain one capability or benefit in a distinctive colored cluster.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 32px; display: flex; flex-direction: column; position: relative; aspect-ratio: 16 / 9`

**Text style:** `statement` — -apple-system 500 · 30px/1.2 · tracking -0.025em

**Observed:** Regular body-sized label upper left, solid pictogram upper right, larger description anchored toward the bottom. Description gains 16px additional side and bottom inset. Blue, mint and pink siblings share the same construction.

**Transfer:** Use one short category label and a roughly four-line description; retain the tension between small label, bold symbol and larger statement.

### Split testimonial

**Use:** Human proof within the cream wrapper.

**CSS:** `display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); gap: 32px`

**Text style:** `statement` — -apple-system 500 · 30px/1.2 · tracking -0.025em

**Observed:** Square portrait area on the left and vertically centered quotation on the right. A large black opening-quote mark precedes the text; attribution sits 64px below. Name is bold body size, with a smaller role and underlined organization link beneath.

**Transfer:** Use a real portrait with a credible quote; preserve the balanced square-and-text composition.

### Presence marker

**Use:** Human-scale utility beside local time in the masthead and ending.

**CSS:** `background: #00c950; width: 12px; height: 12px; border-radius: 50%; margin-right: 8px`

**Observed:** Solid green disk directly before a plain local-time label; footer also includes location.

**Transfer:** Pair the marker with accurate local time or a truthful equivalent presence label.

### Closing contact

**Use:** Final invitation and practical contact route.

**CSS:** `padding-top: 128px; padding-bottom: 96px; background: #ffffff`

**Text style:** `closing` — -apple-system 600 · 88px/1 · tracking -0.025em

**Observed:** One large left-aligned line, then Primary button after 64px. A 1px ink rule sits 64px below the action, followed by a utility row after 96px: legal identity left, location and Presence marker right.

**Transfer:** Keep the invitation conversational and the action singular; use the same content gutter as the rest of the page.

### Case metadata row

**Only for:** case studies

**Use:** Make the project facts quickly scannable.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); gap: 32px; margin-top: 80px; margin-bottom: 48px`

**Text style:** `case-body` — -apple-system 600 · 20px/1.4

**Observed:** Four regular body-sized labels above semibold values; no boxes or separators between facts.

**Transfer:** Choose four relevant project dimensions, such as audience, category, contribution and date.

## Imagery and graphics

### Physical digital proof

**Use:** Signature imagery for the first proof area and repeated image cards.

**Observed:** Devices are presented as substantial objects, not isolated browser rectangles: a tablet diagonally bridges wood and gray flooring; a phone floats over deep orange and navy; a tablet rests on woven upholstery; laptops appear in real hands and rooms. Directional light, natural texture and realistic reflections give the work depth. Images occupy more area than their captions.

**Transfer:** Stage the new product's actual output on a device, package or physical artifact. Minimum version: one convincing angled mockup on photographed wood, fabric or a softly lit plinth, with coherent contact shadow and restrained reflections.

**Build:** For a simple equivalent, place a rendered device or artifact diagonally across a 5:3 photo stage, filling roughly two thirds of the width. Use a natural-material photo as the backing, one directional light and a soft contact shadow. Clip to 12px corners, then add Media legibility veil and upper-left labels.

### Portrait testimony

**Use:** Human proof alongside quotation.

**Observed:** A square portrait region matches one grid column and the height of the adjacent quote composition.

**Transfer:** Use a natural, credible portrait with simple surroundings and no decorative border; keep the square framing.

### Immersive case stage

**Only for:** case studies

**Use:** Full-width project hero and supporting media chapters.

**Observed:** A 1254px by 752px frame carries one scene. One treatment places a dark laptop among translucent blue-gray frozen splash forms on a black background; another presents a silver laptop on a pale gray plinth with soft window-grid shadows across a textured wall. The product is the central object and the environment fills the entire rounded frame.

**Transfer:** Carry the project into a coherent physical setting. Use a daylight plinth scene when elaborate 3D materials are unavailable; keep the screen legible and perspective believable.

**Build:** For the daylight variant, combine a low rectangular gray plinth, a pale textured wall, a perspective device render and a blurred window-grid shadow angled across the background. For the dark variant, surround the device with irregular translucent cool forms, leaving central negative space; keep the atmospheric detail inside the media frame.

### Icons

**Observed:** Solid black pictograms rather than thin outline icons: compass, four-block cluster, lightning bolt and heart. Capability symbols are 48px high with natural widths around 31–55px, placed 24px from the upper-right edges; the masthead symbol is 16px.

**Transfer:** Choose similarly simple solid silhouettes for the new capabilities, with consistent visual mass and no colored icon badges. Use a bold quotation mark for testimony.

## Section recipes

How recurring sections are built.

### First screen: Promise above tangible proof

**Observed:** Cream wrapper and Sticky masthead form the back layer; left-aligned display text and support come next; two Image proof cards begin the visual proof below. The headline uses display typography and spans roughly two thirds of the content width as a short single-line promise. Opening content has 112px top and bottom padding, with a 40px gap to support limited to 580px. At 900px height the entire masthead, headline and two-line support are visible, followed by most of the first pair of 611px by 366px media cards starting at 556px. Their lower edges and the remaining grid continue below the fold. There is no opening button; the first grid's onward action comes after its second row.

**Transfer:** Write a concise audience-facing promise and introduce two tangible product-output scenes in the same first-screen hierarchy. Without finished renders, make two cohesive photographed or composited artifact scenes. Index pages use a category title and one support line with the same alignment; case studies use a project title and attribution followed by one full-width stage.

**Avoid:** Do not center the headline, place a pill CTA beside it or replace the paired proof scenes with a single abstract gradient orb.

**Text style:** `display` — -apple-system 600 · 96px/1 · tracking -0.025em

### Contained capability cluster

**Observed:** Heading typography introduces a two-column group with 64px separation. Capability card repeats in white, blue, mint and pink, with 32px gaps. Primary button sits centered 64px beneath the group. The next major chapter is separated by 176px.

**Transfer:** Use this device for a small set of benefits, workflow stages or product capabilities; retain the pastel-block identity wherever it best serves the narrative.

**Text style:** `heading` — -apple-system 600 · 48px/1 · tracking -0.025em

### Human proof split

**Observed:** Split testimonial pairs a 611px square portrait region with a same-width quote. The content sits directly on cream, without an enclosing card. Statement typography and an oversized quote glyph provide the visual weight.

**Transfer:** Use a verified customer or practitioner quote to interrupt image and capability grids with a more human rhythm.

**Text style:** `statement` — -apple-system 500 · 30px/1.2 · tracking -0.025em

### Editorial and related proof pair

**Observed:** Heading typography above two Image proof cards; 64px heading gap for editorial entries and 80px for related projects. Editorial entries add dates in caption typography and a centered onward button; related-project pairs lead directly toward the closing plane.

**Transfer:** Use the same visual card grammar for learning resources or adjacent examples, changing the secondary line to suit the content.

### Rounded sheet and monumental goodbye

**Observed:** Cream wrapper ends with 24px bottom corners, revealing White closing plane. Closing contact repeats across page types, using closing typography almost as large as the opening, then one action, a full-width 1px rule and the split utility row.

**Transfer:** Include this signature final invitation on every new page, even when the content before it is an index or detailed story.

**Text style:** `closing` — -apple-system 600 · 88px/1 · tracking -0.025em

### Project introduction and facts

**Only for:** case studies

**Observed:** A regular body-sized introductory label precedes a full-width heading-sized paragraph by 24px. Case metadata row follows after 80px. A regular overview label introduces a 640px left-aligned column of case-body paragraphs with 32px paragraph separation, leaving deliberate open space on the right.

**Transfer:** Explain what the project is before describing the contribution. Use a large concise context paragraph, then structured facts and a narrower implementation account.

**Text style:** `heading` — -apple-system 600 · 48px/1 · tracking -0.025em

### Case image chapters

**Only for:** case studies

**Observed:** Full-width Immersive case stage follows the overview after 128px; subsequent 5:3 media chapters are separated by 32px. A centered Primary button follows the final stage after 64px, before related proof.

**Transfer:** Use only meaningful views of the work: overall product, a useful detail and an important usage state. Maintain the same frame and lighting family.

## Page flow

**Storyline:** Clear proposition → tangible work → explanation or deeper proof → related discovery → conversational closing invitation.

### Introduce a design-led product or service and establish trust

1. **Promise** — Short display headline and narrow support above paired physical proof scenes.
2. **Demonstration** — Four Image proof cards and a centered browse action.
3. **Capability explanation** — Pastel capability cluster with solid pictograms and large descriptions.
4. **Social proof** — Portrait-and-quote split.
5. **Continued discovery** — Two editorial entries and an onward action.
6. **Closing call** — Rounded cream sheet gives way to a white contact invitation and utility row.

**Transfer:** Preserve the mix of sparse promise, tactile demonstration and personable proof; adapt the quantity and placement of narrative blocks to the new offer.

### Explain an individual creative or product engagement

1. **Identification** — Project title and collaborator line above a full-width device stage.
2. **Context** — Large introductory paragraph, four metadata fields and a narrow overview.
3. **Demonstration** — Two full-width supporting media chapters.
4. **External action** — Centered visit action.
5. **Related discovery** — Two related project cards.
6. **Closing call** — Shared white invitation and utility ending.

**Transfer:** Use the concise overview variant when the work can be explained in a short account; let the media carry most of the detail.

### Explain a feature-rich engagement in more depth

1. **Identification** — Project title, collaborator line and single full-width stage.
2. **Context and capability** — Large introduction, four facts and three short semibold overview paragraphs.
3. **Demonstration** — Three full-width media chapters for distinct product views.
4. **External action** — Centered visit action.
5. **Related discovery** — Two related project cards.
6. **Closing call** — Shared white contact plane and utility row.

**Transfer:** Give complex products more explanatory paragraphs and distinct demonstrations without changing the underlying typography or framing.

### Provide a curated visual index

1. **Orientation** — Category headline and a single explanatory sentence.
2. **Breadth of proof** — Long, evenly spaced two-column image-card collection with overlaid names and collaborator captions.
3. **Closing call** — Same rounded-sheet ending, contact invitation and local-time utility.

**Transfer:** Let the entries carry the index; keep introductory and filtering chrome minimal rather than turning the page into a dashboard.

## Writing

Direct, collaborative and warmly matter-of-fact. Confidence comes from explaining the work and its outcomes in plain language, with a conversational invitation rather than a hard sell.

**Do not copy:** Do not reuse the studio name, client identities, collaborator credits, testimonials, dates, legal details, technical architecture claims or experience claims as the new product's own assets or facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker and you or your for the reader's practical needs. Case studies name the subject in third person and use we to describe the contribution.
- **Rhythm:** Short two-to-five-word headings, single-sentence opening support and verb-led capability statements. Case overviews use short paragraphs; the final invitation is a simple conversational sentence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the audience relationship or core role in a compact phrase. | 2–5 words | “Partner for designers” |
| Supporting line | Say what the team makes and how it works, without a stack of slogans. | One sentence | “[Brand] Studio builds future-ready websites in collaboration with world-class designers.” |
| Capability label | Single active verb, with the explanation underneath. | 1 word | “Plan”<br>“Build”<br>“Deploy”<br>“Maintain” |
| Primary action | Plain verb phrase stating the destination or interaction. | 2–4 words | “Get in touch”<br>“View more collaborations”<br>“Visit Website” |
| Closing invitation | Human and informal, with a full stop. | 4–7 words | “Reach out and say hi.” |
| Editorial title | Short, provocative practical observation, sometimes addressed to the reader. | 3–7 words | “Your website is not for you”<br>“We cache too much” |

**Words and phrasing to use:** partner; collaborate; build; designed to last; your audience; get in touch

**Avoid:** disruptive revolution; unprecedented synergy; dominate; buy now!!!; world's number one

**Rules:**

- Lead capability descriptions with an action and end with a concrete reader benefit.
- Reserve technical names for the overview where they explain implementation.
- Use everyday headings rather than all-caps category jargon.
- Keep collaborator credits distinct from the primary product title.

## Do's and Don'ts

### Do

- Use 96px/1 semibold for the opening and 88px/1 for the final invitation.
- Keep 32px gaps between equal desktop proof columns.
- Give image captions a 32px upper-left inset and a 2px internal gap.
- Retain 12px media corners and 8px action corners as separate roles.
- Let 30px/36px descriptions carry the pastel cards instead of enlarging their labels.
- Keep the page canvas cream and the final contact plane white.
- Align the closing call to the same approximately 93px desktop gutter as the opening.
- Use black solid capability symbols at 48px high.

### Don't

- Do not turn the dark rectangular actions into 9999px pills.
- Do not spread blue, mint and pink across full-width alternating page bands.
- Do not add floating shadows to the flat capability cards.
- Do not move media titles into bordered white caption panels below the images.
- Do not use thin multicolor line icons in place of the solid black symbols.
- Do not tighten major landing-page chapter breaks to ordinary 32px card gaps.
- Do not make project overview text light gray and thin; it is ink-colored and semibold.
- Do not enlarge the 12px green presence marker into a decorative brand motif.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare a 0.3s color transition with cubic-bezier(.4, 0, .2, 1); hover fill is #444444.
- Media declares a 0.5s transition and image scale 1.025 on group hover.
- The masthead is sticky at the top; the footer is sticky at the bottom beneath a higher-layer cream wrapper.

**Transfer:**

- Keep image hover enlargement clipped within the rounded proof card.
- Preserve the layered cream-sheet-to-white-footer reveal rather than applying unrelated entrance effects.

**Unknown:**

- No keyframe animation was established; exact scrolling choreography beyond the layered sticky construction is unknown.
- Focus-visible and active action treatments are unknown.

### Responsive

**Observed:**

- Opening classes progress through smaller display sizes before the 96px desktop endpoint.
- Grid declarations change from one column to two; case metadata changes from two columns to four.
- Main navigation is hidden at the narrowest layout and becomes a flex row at a wider size.
- Media declarations change from square to 5:3; capability proportions vary between shallow, square and widescreen treatments.

**Transfer:**

- On narrow layouts, stack proof and capability cards in reading order and keep the caption inside each image.
- Scale the promise to fit a short multiline block while retaining tight tracking; reduce the large vertical chapter gaps before reducing text readability.
- Keep local-time presence compact and preserve the white closing plane with rounded cream corners.

**Unknown:**

- Exact breakpoint widths, mobile menu interaction and final mobile measurements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
