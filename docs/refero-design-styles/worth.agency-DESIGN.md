# Worth — pastel word sculpture

## Overview

A light, art-directed style that pairs oversized word sculptures with soft pink and mint fields, then gives the work room to speak in an editorial gallery. Rounded humanist sans typography moves between very light upright sentences and emphatic italics. Physical packaging photography, handheld device mockups and expansive interface compositions provide rich visual proof against sparse surroundings, ending in a dramatic black typographic signature. It suits creative products and services that want to feel thoughtful, approachable and visually memorable rather than corporate.

### Essentials

- The opening is a word sculpture, not a conventional headline-and-button stack: a pink 1440×900 stage, a red word spanning about 78% of its width, and a narrow reflective object interrupting its center; a two-line 24px/1.3 descriptor sits low beneath it. Recreate this typographic object even without product photography.
- Emphasis comes from a change of posture: Nunito Sans 300 upright pairs with 600 italic, at 80px/1 and -0.03em for gallery headings, or 48px/1.16 and -0.03em for centered statements. Green or vermilion colors only the selected words.
- Navigation floats like a small control object: a centered white 250×72 capsule with 24px corners, a 24px light label and an oversized thin plus; a separate 72px white mark tile joins it after the opening.
- Pastels are broad but bounded: pink owns the opening and the 1296×756 inquiry panel, mint marks secondary actions and selected language, while white and #f9f9f9 carry the long proof gallery. Saturated vermilion stays in the opening art, short emphasis and directional marks, never a run of ordinary content panels.
- Images are exhibits with small italic captions: 24px rounded media, 32px/1.2 weight-600 italic titles and 16px/1.4 subdued descriptions. A three-column gallery mixes single-width and double-width works with 36px gutters and 96px row gaps; use carefully staged product or interface compositions when no portfolio exists.
- The closing is monumental rather than administrative: a 48px-radius pastel inquiry panel sits inside a white sheet with 96px bottom corners, revealing a black footer with a huge pale word graphic about 1058×262 and small underlined links beneath. Keep both the oversized closing signature and the rounded-sheet reveal. 

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion | `#eb4726` | `--color-vermilion` | text, accent, link | Short italic emphasis, arrows, mark tile and light-background social-link hover. Opening artwork uses a visually similar rendered red. |
| Rose stage | `#f8d4d4` | `--color-pink` | background, surface, accent | Opening stage, inquiry panel and default pale closing word graphic; footer hover color. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Leaf green | `#65ab65` | `--color-green` | text, link, accent | Italic values within statements, company chapter labels and selected link hover. |
| Mint field | `#d2fdd1` | `--color-mint` | background, surface, action | Secondary action fill. Also the broad field and inquiry-panel variant for company and detailed work narratives. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action | Primary text, submission button and closing footer. |
| Caption gray | `#808080` | `--color-muted` | text | Visible approximation of black at opacity 0.5 on the pale gallery; implement caption text with rgba(0,0,0,0.5). |
| Gallery white | `#f9f9f9` | `--color-canvas` | background, text | Long gallery canvas and pale footer link text. |
| Paper white | `#ffffff` | `--color-white` | surface, background, text | Statement sheet, form fields and navigation; inverse text over imagery. |

## Typography

- **Nunito Sans** — All marketing headings, descriptive text, controls and links. Soft humanist sans with open counters, light strokes and fluid true italics; the italic weight change is central to its personality. Font stack: "Nunito Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | Nunito Sans | 300 | 80px | 1 | -0.03em | Centered gallery section heading, paired with the italic emphasis recipe. |
| heading-emphasis | Nunito Sans | 600 italic | 80px | 1 | -0.03em | Colored concluding word within a gallery section heading. |
| closing-heading | Nunito Sans | 300 | 80px | 1 | -0.04em | First line of the inquiry heading. |
| closing-emphasis | Nunito Sans | 600 italic | 80px | 1 | -0.04em | Second line of the inquiry heading, in black. |
| statement | Nunito Sans | 300 | 48px | 1.16 | -0.03em | Centered two-line positioning statement. |
| statement-emphasis | Nunito Sans | 600 italic | 48px | 1.16 | -0.03em | Green emphasized words inside the positioning statement. |
| item-title | Nunito Sans | 600 italic | 32px | 1.2 | -0.02em | Media captions and capability titles. |
| support | Nunito Sans | 300 | 24px | 1.3 | -0.02em | Opening descriptor, inquiry support, navigation label and large secondary actions. |
| footer-link | Nunito Sans | 600 | 24px | 1.3 | -0.02em | Underlined social and resource links on black. |
| body | Nunito Sans | 300 | 16px | 1.4 | -0.02em | Descriptions, small support lines and footer prompts. |
| action | Nunito Sans | 600 | 16px | 1.4 | -0.02em | Submit and inline links. |
| caption | Nunito Sans | 300 | 12.8px | 1.4 | -0.02em | Form support and detailed project metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| individual case studies | project-title | Nunito Sans | 400 | 88px | 1 | -0.04em, features "salt" | Centered title above a device presentation. |
| company and collection introductions | editorial-display | Nunito Sans | 300 italic | 80px | 1.1 | -0.04em | Left-aligned, wrapping sentence headline. |
| company introductions | editorial-emphasis | Nunito Sans | 500 italic | 80px | 1.1 | -0.04em | Green concluding phrase in the editorial headline. |
| collection introductions | collection-emphasis | Nunito Sans | 600 italic | 80px | 1.1 | -0.04em | Vermilion opening phrase in the editorial headline. |
| individual case studies | next-title | Nunito Sans | 500 italic | 80px | 1 | -0.04em | White centered title over next-work photography. |
| company and collection introductions | editorial-body | Nunito Sans | 300 | 32px | 1.2 | -0.02em | Long company introduction or short collection label. |
| company chapters | chapter-label | Nunito Sans | 600 italic | 24px | 1.3 | -0.02em | Green left-rail section labels. |

**Notes:**

- Use sentence case. Italics are a structural emphasis device, not an occasional decorative flourish.
- Body and small text retain -0.02em tracking; display recipes tighten to -0.03em or -0.04em. Keep the light/heavier-italic pairing instead of making whole headings bold.
- The giant opening and closing lettering is artwork, distinct from the Nunito Sans text system. Fit a custom heavy vector word to the specified visual span rather than enlarging a light heading.
- Company inquiry text has a tighter -0.06em variant, with a weight-500 italic second line; keep the default inquiry pairing for ordinary marketing.

## Layout

**Density:** Airy: full-screen stages and large inter-section pauses contrast with tightly grouped captions and controls.

### Spacing

**Spacing system:**

- **vertical rhythm** 6px, vertical — Most major vertical values follow multiples of 6px; compact control gaps are exceptions.

| Value | Use |
| --- | --- |
| 10px | Compact inline and small flex gaps. |
| 24px | Media-to-caption gap, form field stack gap and button inner padding. |
| 36px | Gallery outer gutters and column gaps; title-to-description gap in case-study openings. |
| 48px | Inquiry column gap and footer group spacing. |
| 60px | Inquiry panel inset and capability item separation. |
| 72px | Inquiry section outer padding. |
| 96px | Gallery row gaps and large content pauses. |
| 120px | Major editorial section vertical padding. |

### Containers and grids

- **wide container**: max width 1920px · side padding 36px. Centered broad canvas for gallery and editorial content; content width is 1368px at a 1440px viewport.
- **featured gallery**: 3 columns · gap 36px. Three base columns of 432px; selected works span two columns for a 900px image. Use 96px row gaps, balancing wide and tall images.
- **inquiry split**: 2 columns · gap 48px. Equal 564px text and form columns inside a 1176px content area.
- **collection gallery** (only for work collections): 2 columns · gap 36px · side padding 36px. Two independently stacked 666px columns, mixing square, landscape and portrait art with title and description below.
- **editorial rail** (only for company chapters): 2 columns · gap 0px · side padding 36px. Left label occupies roughly 40% of the content width; right text occupies 60%. Long introduction begins in the right column below a full-width title.
- **case gallery** (only for individual case studies): 2 columns · gap 36px · side padding 36px. Alternate 1368px-wide compositions with pairs of 666px-wide panels; media height follows its aspect ratio.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media and navigation | 24px |
|  | controls | 32px |
|  | inquiry panel | 48px |
|  | sheet corners | 96px |
| individual case studies | case opening | 72px |
| individual case studies | case closing sheet | 60px |

## Surfaces and depth

### Surfaces

#### Gallery canvas · level 0

**Use:** Main long-form proof areas.

**CSS:** `background: #f9f9f9`

**Observed:** Flat near-white ground; no decorative shadow system.

**Transfer:** Let image color and changes in scale create the hierarchy.

#### Rose stage · level 0

**Use:** Opening word sculpture.

**CSS:** `background: #f8d4d4; overflow: hidden`

**Observed:** Single uninterrupted pastel field behind the red word and reflective object.

**Transfer:** Keep the scene tonal, graphic and uncluttered.

#### Rounded statement sheet · level 1

**Use:** Transition from the opening into a centered positioning statement.

**CSS:** `background: #ffffff; border-radius: 96px 96px 0px 0px; overflow: hidden`

**Observed:** The full-width white sheet rolls over the pink stage with very broad upper corners.

**Transfer:** Use the oversized curvature at major page transitions, not on every small block.

#### Inquiry panel · level 1

**Use:** Main conversion area.

**CSS:** `background: #f8d4d4; border-radius: 48px; padding: 60px`

**Observed:** A substantial pastel panel inside a white surround; mint replaces pink for company and case-study narratives.

**Transfer:** Keep the tint flat and fields white; use the same color family for any associated closing signature.

#### Closing sheet · level 1

**Use:** End of the light content above the footer.

**CSS:** `background: #ffffff; border-radius: 0px 0px 96px 96px; overflow: hidden`

**Observed:** The rounded lower edge sits in front of black, making the content feel like a single physical sheet.

**Transfer:** Preserve the visible black wedges outside the lower corners.

#### Black closing ground · level 0

**Use:** Monumental signature footer.

**CSS:** `background: #000000; color: #f9f9f9`

**Observed:** A fixed black layer is revealed beneath the rounded content sheet.

**Transfer:** Reserve this solid dark field for the closing, not a dark-mode reinterpretation of all sections.

#### Mint editorial field · level 0

**Only for:** company narratives

**Use:** Company introduction, proof list and capabilities.

**CSS:** `background: linear-gradient(#f9f9f9 0%, #d2fdd1 45%)`

**Observed:** The opening fades into a broad mint field, holds solid mint through the middle chapters, then fades from mint to white through contacts.

**Transfer:** Make the background a continuous environment across chapters rather than separate cards.

#### Collection wash · level 0

**Only for:** work collections

**Use:** Editorial collection opening.

**CSS:** `background: linear-gradient(#f8d4d4 5.67148%, #f9f9f9 45%)`

**Observed:** Pink is strongest above the text and has faded to gallery white before the media grid.

**Transfer:** Keep the gradient vertical and soft.

#### Next-work scrim · level 1

**Only for:** individual case studies

**Use:** Readable next-work title over full-bleed media.

**CSS:** `background: rgba(0,0,0,0.3)`

**Observed:** Black translucent overlay over a tightly framed image.

**Transfer:** Darken the image as a whole, leaving its material and subject visible.

## Components

### Floating navigation

**Use:** Persistent compact page identity and menu control.

**CSS:** `display: flex; justify-content: space-between; align-items: center; background: #ffffff; border-radius: 24px; width: 250px; height: 72px; padding: 6px 8px 6px 20px`

**Text style:** `support` — Nunito Sans 300 · 24px/1.3 · tracking -0.02em

**Observed:** Fixed at the top center with a 16px top inset. Current section name sits left, a large thin black plus sits right. A separate white mark tile appears adjacent as the user moves beyond the opening; case studies replace the mark with a red back arrow.

**Transfer:** Use a short current-section name and a custom single-character mark, keeping the control detached from full-width header bars.

### Mint secondary button

**Use:** Low-pressure exploration after a statement or gallery.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #d2fdd1; color: #000000; border-radius: 32px; padding: 32px 48px`

**Text style:** `support` — Nunito Sans 300 · 24px/1.3 · tracking -0.02em

**Observed:** A soft rounded rectangle, not a full pill; text alone is centered. A more compact exploration variant appears below the gallery.

**Transfer:** Use this larger light-weight action for exploratory navigation, leaving black for form submission.

### Primary button

**Use:** Submission action inside the inquiry form.

**CSS:** `background: #000000; color: #ffffff; border-radius: 32px; padding: 24px; width: 160px; height: 70px; display: flex; justify-content: center; align-items: center`

**Text style:** `action` — Nunito Sans 600 · 16px/1.4 · tracking -0.02em

**Observed:** Aligned to the right of the form's final row, opposite a small consent sentence.

**Transfer:** Keep a short direct verb and the compact black mass.

### Form field

**Use:** Name, email, selectors and a short project message.

**CSS:** `background: #ffffff; border-radius: 32px; height: 67px; padding: 24px; border: 0px solid transparent; display: flex; align-items: center`

**Observed:** Four vertical rows: two full-width fields, two half-width selectors on one row, then a full-width short message field. Selector chevrons sit at the far right. No visible outline; the white silhouette separates the field from its pastel backing.

**Transfer:** Adapt questions to the new product while keeping the compact four-row structure and low visual weight.

### Project card

**Use:** Image-led proof in the featured gallery.

**CSS:** `display: flex; flex-direction: column; gap: 24px; overflow: clip`

**Text style:** `item-title` — Nunito Sans 600 italic · 32px/1.2 · tracking -0.02em

**Observed:** A linked composition with 24px-radius media above an unboxed caption. Large cards place title and muted description side by side; small cards stack them. Media is cover-framed, with a 900×720 wide-card variant.

**Transfer:** Use real product outcomes, object photography or designed interface scenes rather than generic feature icons.

### Inline link

**Use:** Social references, external destinations and contact details.

**CSS:** `color: #000000; text-decoration-line: underline; text-decoration-thickness: 0.05em; text-underline-offset: 0.15em`

**Text style:** `action` — Nunito Sans 600 · 16px/1.4 · tracking -0.02em

**Observed:** Inline underlined text without an arrow container or surrounding border.

**States:** Declared: hover #eb4726 on statement social links, retaining underline at 0.05em thickness and 0.15em offset; contact links use #65ab65. Focus-visible and active styling unknown.

**Transfer:** Use a brief destination or channel name.

### Footer links

**Use:** Final social and downloadable-resource navigation.

**CSS:** `color: #f9f9f9; text-decoration-line: underline; text-decoration-thickness: 0.05em; text-underline-offset: 0.15em`

**Text style:** `footer-link` — Nunito Sans 600 · 24px/1.3 · tracking -0.02em

**Observed:** Two small prompt-and-link groups sit beneath the word graphic, with copyright aligned to the far right. Social destinations form one comma-and-ampersand sentence rather than separate buttons.

**States:** Declared: hover #f8d4d4 with underline retained; focus-visible and active styling unknown.

### Inquiry block

**Use:** Primary conversion conversation.

**CSS:** `background: #f8d4d4; border-radius: 48px; padding: 60px; display: flex; align-items: center; justify-content: center; gap: 96px`

**Text style:** `closing-heading` — Nunito Sans 300 · 80px/1 · tracking -0.04em

**Observed:** A 1296×756 panel in a 900px-high section with 72px outer insets. Inside, an equal-width two-column layout places a two-line heading and support on the left, fields on the right. Mint is the company and case-study variant.

**Transfer:** Ask for enough information to start a useful conversation; preserve the split between invitation and input.

### Slash proof list

**Only for:** company narratives

**Use:** Dense but typographic social proof.

**CSS:** `display: flex; flex-wrap: wrap; gap: 10px; color: #000000`

**Text style:** `editorial-body` — Nunito Sans 300 · 32px/1.2 · tracking -0.02em

**Observed:** Underlined names use weight 600, separated by green forward slashes. The list occupies the right 60% of the editorial rail, with a green italic chapter label on the left.

**States:** Declared: hover #65ab65 on names, with underline thickness 0.05em and offset 0.15em; focus-visible unknown.

**Transfer:** Use genuine partners, integrations or press references as a flowing linked sentence, not a logo wall.

### Next-work banner

**Only for:** individual case studies

**Use:** Continue exploration after an inquiry section.

**CSS:** `height: 630px; padding: 96px; display: flex; justify-content: center; align-items: center; overflow: clip; color: #ffffff`

**Text style:** `next-title` — Nunito Sans 500 italic · 80px/1 · tracking -0.04em

**Observed:** Full-bleed photographic background, Next-work scrim and a centered italic title; the enclosing sheet has 60px bottom corners. A supporting description exists in the text structure but the title dominates visually.

**Transfer:** Feature one related story with a compelling image rather than a row of small recommendations.

## Imagery and graphics

### Reflective word sculpture

**Use:** Signature opening artwork.

**Observed:** A huge heavy red word stretches across the pink field. A vertical stack of pink translucent and mirror-red folded slabs interrupts its center, taller than the word's cap height. Hard red reflections and soft pink transparency produce the depth; there is no photographic environment.

**Transfer:** Make the new product name or one short concept into a vector word and intersect it with a simple reflective form. The minimum version is heavy live lettering plus a few shaded SVG planes; the sculptural interruption must remain.

**Build:** Use a 1440×900 viewBox on a pink stage. Fit a heavy red word into about 1120×280 near the vertical center. Overlay a narrow 130×410 central group of rounded pink planes, slightly rotated in opposing directions. Layer red reflective faces with linear gradients between transparent red, opaque red and pale white highlights; use pink cross-bands to conceal parts of the faces. Place the descriptor beneath with ample clear space. Scale the whole composition uniformly rather than moving the object away from the word.

### Monumental closing word

**Use:** Signature footer art on every page type.

**Observed:** A heavy custom vector word sits left-aligned, around 1058×262, occupying most of the visible footer width. It is pink on the main landing page, mint in the company variant and white in collection and case-study variants.

**Transfer:** Create an oversized vector word from the new identity, with assertive broad shapes and tight internal spacing. A heavy freely available sans converted to outlines is the minimum acceptable replacement.

**Build:** Place a single SVG word in a roughly 1060×262 artboard above the footer links, aligned left inside a 24px inset. Use flat pink fill over black, no shadow or outline. Fit the full word without stretching its letter proportions; adjust artboard width for the new name.

### Material product exhibits

**Use:** Featured proof and collection cards.

**Observed:** Handheld tablets and laptops show finished sites; packaging is photographed as stacks of kraft-and-green boxes, a coffee bag on a dark floor, or a patterned wrap held against cyan. Light is directional and tangible, with clear edges, real surface texture and substantial image area relative to captions.

**Transfer:** Show the new offering as a finished object or interface in use. Keep realistic material, strong framing and a deliberately chosen backing; allow image palettes to differ without recoloring the surrounding site.

### Case-study presentation boards

**Only for:** individual case studies

**Use:** Long-form visual demonstrations and identity documentation.

**Observed:** Large rounded boards alternate with paired portrait boards. One system uses cool pale-blue backing with framed web pages, laboratory photography and device mockups; another uses dark slate-green, camel gradients and rough floating rocks behind dark automotive interfaces. Typeface and palette specimens appear as artwork within these boards, not as marketing typography.

**Transfer:** Choose one cohesive backdrop family derived from the demonstrated product. Show whole desktop views, tall page compositions, mobile groups and details at varied scales. Do not turn the demonstrated product's type or color system into the surrounding site's UI.

### Icons

**Observed:** Sparse, oversized directional marks: a thin slightly irregular black plus inside a 60px navigation area, vermilion down/back arrows in 60–72px areas, and tiny simple selector chevrons. A single red letter mark sits in the separate white navigation tile.

**Transfer:** Use simple thin SVG strokes and generous empty bounds. Prefer plus and directional arrows over filled circular icon buttons or decorative icon sets.

## Section recipes

How recurring sections are built.

### First screen: Word sculpture opening

**Observed:** The first 900px is a full pink stage. Back to front: flat Rose stage, a red heavy vector word spanning roughly 78% of the width at mid-screen, a narrow reflective pink/red sculptural object crossing its center, a low centered two-line 24px/1.3 descriptor, and Floating navigation above everything. The word's visible cap height is about 280px; the object is about 410px tall. The navigation is the only prominent control: there is no hero CTA row. All artwork and descriptor fit within the first screen; the white statement sheet starts below it.

**Transfer:** Use a short new identity or concept as the giant word and rebuild the Reflective word sculpture if no suitable media exists. A concise descriptor should explain the offer without competing with the art. Collection and company pages instead open with left-aligned italic sentence headlines and a softly fading pastel background; individual stories open with a centered 88px title and begin revealing their first large media board near the lower part of the screen.

**Avoid:** Do not replace the sculptural word with a left-column SaaS pitch, dashboard card and two hero buttons; do not scatter extra ornaments around the central object.

**Text style:** `support` — Nunito Sans 300 · 24px/1.3 · tracking -0.02em

### Centered positioning sheet

**Observed:** Rounded statement sheet fills a 900px stage. A centered 48px light statement is followed by a second line containing green heavier italics. Small social references sit below, then a Mint secondary button; the main content is vertically centered with substantial empty top and bottom space.

**Transfer:** Write a short promise and a compact set of differentiating qualities. Let the italic words carry the personality rather than adding feature badges.

**Text style:** `statement` — Nunito Sans 300 · 48px/1.16 · tracking -0.03em

### Heading and direction

**Observed:** A 630px-high gallery introduction centers the Heading and Heading-emphasis pairing above a 16px supporting line, with a large red down arrow below. The section has 120px top padding and ample separation from the first media row.

**Transfer:** Use the heading pair to introduce proof or demonstrations; keep the arrow visually isolated so it reads as a directional gesture.

**Text style:** `heading` — Nunito Sans 300 · 80px/1 · tracking -0.03em

### Asymmetric exhibit gallery

**Observed:** Project cards occupy the featured gallery, mixing 432px single-column images with 900px double-column images on a three-column base. Wide work appears on alternating sides, with smaller pieces clustered between it. Captions are outside the media, never overlaid; a centered exploration action follows.

**Transfer:** Balance one dominant result against several smaller views of the offering. Preserve varied aspect ratios and scale rather than forcing identical tiles.

**Text style:** `item-title` — Nunito Sans 600 italic · 32px/1.2 · tracking -0.02em

### Pastel inquiry

**Observed:** A 900px section frames the Inquiry block with 72px white margins. The left invitation uses Closing-heading plus Closing-emphasis over two lines, with 24px support below. The right column contains Form fields, a small consent line and the Primary button. Pink is default; mint belongs to company and detailed-story variants.

**Transfer:** Change the request and field semantics to match the offering. Keep the invitation conversational and the inputs visually lighter than the heading.

**Text style:** `closing-heading` — Nunito Sans 300 · 80px/1 · tracking -0.04em

### Revealed signature ending

**Observed:** The Closing sheet rounds away to reveal Black closing ground and Monumental closing word. Footer links form two prompt-and-link groups, with copyright at the right. The main landing ending exposes about 400px of the footer; detailed stories allow a taller 630px ending beneath a Next-work banner.

**Transfer:** Finish with a bold new identity word and only essential destinations. Keep it as a graphic final impression, not a multi-column sitemap.

**Text style:** `footer-link` — Nunito Sans 600 · 24px/1.3 · tracking -0.02em

### Editorial rail chapters

**Only for:** company narratives

**Observed:** A mint environment carries a full-width italic 80px opening sentence. The following 32px introduction is right-aligned as a column, not as text alignment. Subsequent sections keep a 24px green italic label in a left rail and content in the right: Slash proof list, stacked italic capability titles with 16px descriptions, then contact blocks with small green local times. Chapter padding is 120px; contacts fade toward white.

**Transfer:** Use this rail for an origin story, operating principles or capabilities. Textual references and factual contact modules can replace clients and offices while retaining the asymmetry.

**Text style:** `editorial-display` — Nunito Sans 300 italic · 80px/1.1 · tracking -0.04em

### Collection opening and masonry

**Only for:** work collections

**Observed:** Collection wash sits behind a left-aligned 80px italic sentence with its first phrase in vermilion. A 32px collection label appears below, followed by two 666px-wide stacks of varied-aspect media. The inquiry and signature ending follow the gallery.

**Transfer:** Use a broad editorial thesis followed by a visual index of examples, releases or applications.

**Text style:** `editorial-display` — Nunito Sans 300 italic · 80px/1.1 · tracking -0.04em

### Case-study title and brief

**Only for:** individual case studies

**Observed:** A 630px title area centers an 88px/1 upright heading over a 16px description separated by 36px. A 1440×1152 opening media stage has 72px upper corners. Below, a white brief section with 120px vertical and 48px horizontal padding places small service/industry/work metadata left and two 24px narrative paragraphs right, ending with an underlined website link.

**Transfer:** Introduce the result plainly, then explain context, problem and intervention before the media sequence. Keep the metadata subordinate to the narrative.

**Text style:** `project-title` — Nunito Sans 400 · 88px/1 · tracking -0.04em

### Case-study visual sequence

**Only for:** individual case studies

**Observed:** Case-study presentation boards alternate full-width and paired layouts with 36px outer insets and gaps. Identity palette and type boards, desktop views, mobile mockups and expansive tilted page collages create a long visual story. It ends with the mint inquiry variant, Next-work banner and white-on-black signature footer.

**Transfer:** Demonstrate one product through coherent art direction, increasing detail and different viewport scales; let the product's actual content determine the number of boards.

**Text style:** `body` — Nunito Sans 300 · 16px/1.4 · tracking -0.02em

## Page flow

**Storyline:** graphic promise → concise positioning → visual proof → useful detail → conversational conversion → monumental signature, with related discovery on detailed stories

### A visually memorable marketing landing page

1. **Identity hook** — Full-screen pastel word sculpture and a concise low descriptor.
2. **Positioning** — Centered two-line statement with green italic values and a soft exploration action.
3. **Visual proof** — Mixed-scale exhibit gallery introduced by a light/italic heading pair and a directional arrow.
4. **Conversion** — Pink split inquiry panel.
5. **Signature** — Rounded light sheet reveals black footer and giant pale word.

**Transfer:** Replace the portfolio with product demonstrations or outcomes while retaining the sculptural hook, editorial emphasis and graphic ending.

### Explain an organization and make its expertise approachable

1. **Point of view** — Italic contrast statement on a mint fade, followed by a right-column introduction.
2. **Social proof** — Flowing underlined name list separated by green slashes.
3. **Capabilities** — Left chapter rail beside stacked italic titles and short practical descriptions.
4. **Contact access** — Location blocks with local clocks and direct text links.
5. **Conversion and signature** — Mint inquiry followed by a mint word on black.

**Transfer:** Use a broad narrative and editorial rail to explain the people, system or service behind a product.

### Help visitors browse a body of work

1. **Framing thesis** — Vermilion-and-black italic sentence over a pink-to-white wash.
2. **Browsable proof** — Two independent image stacks with varied aspect ratios and restrained captions.
3. **Conversion and signature** — Pink inquiry and white word on black.

**Transfer:** Adapt to use cases, applications or a release collection without flattening the media into identical cards.

### Explain a complex digital transformation visually

1. **Result introduction** — Centered upright title and subtitle above a large device scene.
2. **Context and intervention** — Small metadata alongside larger narrative paragraphs and a live destination link.
3. **Demonstration** — Cool-backed identity boards, desktop and mobile examples, then expansive interface collages.
4. **Conversion** — Mint inquiry panel.
5. **Related discovery and signature** — Full-width image banner for another story, then a white word on black.

**Transfer:** Present a platform or product through brief context and an extended coherent demonstration rather than unsupported metric cards.

### Show a premium visual system and its implementation

1. **Result introduction** — Centered title above a dark device presentation.
2. **Context and intervention** — Two-column metadata and project explanation.
3. **System and detail** — Palette and type specimens followed by desktop, mobile and feature compositions on dark slate/camel boards with rocky materials.
4. **Conversion** — Mint inquiry panel.
5. **Related discovery and signature** — Photographic next-story banner, followed by white word art on black.

**Transfer:** Let the featured product supply a cohesive visual world within the boards, while keeping the outer marketing frame pale and consistent.

## Writing

Confident and thoughtful, with a warm conversational invitation. Descriptions favor tangible deliverables, clear structure and practical implementation over grand promises.

**Do not copy:** Do not reuse the Worth name, wordmark, project names, client list, contact details, exact positioning claims or the clients' artwork. Source quotations are examples of cadence, not replacement-product claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker and you/your in invitations. Project descriptions are concise third-person summaries.
- **Rhythm:** Short title phrases and one-sentence captions contrast with longer explanatory paragraphs on editorial pages. Sentence case, few exclamation marks, and lists joined naturally with commas and and.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening descriptor | A plain category statement naming what the organization makes and who it serves. | 8–14 words | “A design agency for brands, websites, and visual systems.” |
| Positioning statement | One confident promise, followed by a triad of qualities that can receive italic emphasis. | 6–10 words per line | “Distinctive design for brands worth remembering.”<br>“Built with clarity, taste, and purpose.” |
| Editorial headline | A constructive contrast, or an outcome followed by the means. | 7–12 words | “Branding and websites with structure, not noise”<br>“Work shaped through strategy, visual systems, and digital craft” |
| Proof caption | Name the kind of result, the audience and one meaningful differentiator. | 8–16 words | “A premium digital platform for a collectible design and interiors brand” |
| Conversion invitation | An open invitation followed by a helpful, non-salesy explanation. | 5–12 words | “Tell us about your project”<br>“We’ll help you understand what it’s worth shaping into” |
| Action | Direct verb or destination, without promotional padding. | 1–4 words | “Submit”<br>“More projects”<br>“View Website” |

**Words and phrasing to use:** shape; structure; clarity; visual systems; thoughtful; direction; built; craft; purpose

**Avoid:** revolutionary; game-changing; disrupt everything; 10x; best-in-class; unlock limitless potential

**Rules:**

- Use captions to explain what a visitor is looking at, not to repeat a vague benefit.
- Let a headline's contrast or final noun carry emphasis; do not italicize arbitrary filler words.
- Explain complex work as context, needed change and concrete intervention.
- Keep the final invitation open and human rather than introducing artificial urgency.

## Do's and Don'ts

### Do

- Keep the 24px low-centered descriptor visually subordinate to the opening word sculpture.
- Use 300 upright and 600 italic as the default typographic contrast.
- Maintain 36px gallery gutters and 96px row gaps so large media feels exhibited.
- Place 32px italic titles outside the image and mute 16px descriptions with 0.5 black opacity.
- Make inquiry fields 67px high with 32px corners against the flat pastel panel.
- Keep the submission button black, 160×70px, with a 32px radius.
- Use 96px sheet corners only at major transitions and the footer reveal.
- End with an oversized pale vector word above concise underlined destinations.

### Don't

- Do not turn every heading into a heavy upright grotesk; it erases the light/italic contrast.
- Do not make all buttons 9999px pills; the measured controls are rounded rectangles.
- Do not add soft card shadows or glass navigation; the surfaces are flat and opaque.
- Do not convert the proof gallery into equal-height white cards with enclosed captions.
- Do not repeat saturated vermilion as a background behind every feature; its ordinary role is brief emphasis and direction.
- Do not use the dark, camel or blue palettes inside featured product boards as the global marketing theme.
- Do not replace the slash-separated proof sentence with a uniform grid of monochrome logos.
- Do not fill the signature footer with dense sitemap columns or a second form.

## Motion and responsive

### Motion

**Observed:**

- The navigation remains fixed while section labels change with context; the footer sits fixed beneath the foreground sheet.
- Text wrappers include perspective, scale, opacity and rotateX transforms; the intended settled text is fully readable.
- No action transition durations or complete animation timelines are established. Link hover colors and underline treatments are declared.

**Transfer:**

- Let the light content sheet uncover the dark signature rather than fading to an unrelated footer.
- If animating the statement or heading pairs, keep both typographic voices together as a single unit and settle them to full readability.
- Maintain the reflective object's visual intersection with the opening word throughout any motion.

**Unknown:**

- Exact sculpture behavior, scroll choreography, duration and easing assignments; no complete menu-open state is established.

### Responsive

**Observed:**

- Declared width thresholds include 810px, 1200px, 1500px and 1900px; only the 1440px composition is established.

**Transfer:**

- On narrow screens, scale the word and reflective object together so the interruption stays central; keep the descriptor beneath them.
- Collapse the inquiry into invitation above fields, preserving the paired selector relationship only when labels remain readable.
- Reduce gallery columns while retaining a difference between dominant and supporting exhibits; stack the editorial label above its content when the rail becomes too narrow.
- Scale the closing vector word proportionally and stack footer prompt groups rather than shrinking the links excessively.

**Unknown:**

- Exact mobile sizes, spacing, column counts, navigation expansion and breakpoint-specific behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
