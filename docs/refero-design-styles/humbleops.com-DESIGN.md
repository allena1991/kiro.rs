# Humble — illustrated industrial optimism

## Overview

An optimistic industrial-future style that makes complex software feel human and immediately useful. Mostly off-white and black, it pairs tightly packed expressive grotesk headlines with small functional sans-serif copy, vermilion punctuation, painterly landscapes and carefully framed interface demonstrations. The overall density is airy, with compact information inside generously rounded, tactile panels.

### Essentials

- A three-part opening balances promise, person and explanation: a 58px/1.1 Bricolage Grotesque headline at weight 500 and -0.05em tracking sits left of a central illustrated user, with a compact supporting column on the right.
- Headlines end with a spark rather than a shout: black, tightly tracked display lettering uses a single #ff4000 full stop; recurring section titles use 44px/1.1 at weight 500 with -2.3px tracking.
- Conversion feels like a physical control: black pill actions are 50px high with 24px horizontal padding and 200px corners; the navigation version is 39px high.
- Color belongs to the world outside the interface: #fafafa dominates the reading areas, #ecebe8 cradles white cards, and orange marks labels, punctuation and one decisive comparison column rather than every panel. Painterly cyan, green, purple and peach are concentrated in wide illustrations.
- The product gets a substantial frame: the opening interface sits inside a 37px-radius black-edged device with a 6px rim, itself nested in a translucent 60px-radius surround; smaller demonstrations use 20px corners.
- A cinematic landscape must bridge the closing invitation into a black footer: a bright illustrated horizon fades through dark foreground foliage into black, followed by a two-line 41.9px promise in white and muted gray. Use an original illustrated environment relevant to the new product, or a layered SVG landscape as the minimum equivalent.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion | `#ff4000` | `--color-orange` | accent, text, surface, link | Full stops, short eyebrows, active links, timeline accents and the highlighted comparison column. |
| Vermilion wash | `#faede8` | `--color-orange-wash` | surface | Visible 7% vermilion over the off-white canvas behind section labels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action | Hero text, actions, FAQ shell and footer. |
| Soft black | `#1c1c1c` | `--color-heading` | text | Default section and feature headings. |
| Dark inset | `#1f1f1f` | `--color-faq-row` | surface | White at 12% over the black FAQ shell. |
| Muted body ink | `#6e6e6e` | `--color-body-muted` | text | Visible result of black at 56% over the off-white canvas; body and navigation text. |
| Footer promise gray | `#7a7a7a` | `--color-footer-muted` | text | White at 48% over black, used for the second footer line. |
| Secondary gray | `#828282` | `--color-secondary-muted` | text | Black at 48% over the off-white canvas; secondary text and subdued display lines. |
| Footer fine gray | `#848484` | `--color-fineprint` | text | Small footer metadata. |
| Footer link gray | `#8f8f8f` | `--color-footer-link` | link, text | White at 56% over black for footer links. |
| Light support gray | `#999999` | `--color-caption` | text | Closing invitation support. |
| Card edge | `#d9d9d9` | `--color-edge` | border | Visible black at 15% over white for fine panel separators. |
| Warm molded backing | `#ecebe8` | `--color-stone` | surface | Thick surrounds behind white content panels. |
| Device surround gray | `#f1f1f1` | `--color-glass` | surface | Visible 20% #cccccc over the off-white canvas. |
| Off-white canvas | `#fafafa` | `--color-canvas` | background | Default reading field. |
| White | `#ffffff` | `--color-white` | surface, text | Raised cards and text on black. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company pages | Badge slot | `#e7e6e3` | `--color-slot` | surface | Inset attachment slot on personnel cards. |
| pricing and company pages | Warm inner tray | `#f7f6f2` | `--color-cream` | surface | Inner effort tray and biography insets. |

## Typography

- **Bricolage Grotesque** — Display, section titles, feature titles and timeline numerals. Expressive, compact grotesk with softly irregular shapes; medium weight and unusually tight tracking. Font stack: "Bricolage Grotesque", sans-serif.
- **Geist** — Paragraphs, navigation, eyebrows and actions; use the variable family for regular-weight actions. Clean functional sans with compact small-size rhythm. Font stack: "Geist", sans-serif.
- **Inter** — Comparison labels, FAQ questions, footer links and card labels. Compact neutral sans; medium and semibold weights. Font stack: "Inter", sans-serif.
- **Geist Mono** (only for pricing effort summaries) — Time commitments anchored to the bottom of effort cards. Small functional monospaced numerals and notation. Font stack: "Geist Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Bricolage Grotesque | 500 | 58px | 1.1 | -0.05em, features "cv01", "cv05", "cv09", "cv11", "ss03" | Opening promise, typically three lines. |
| section-heading | Bricolage Grotesque | 500 | 44px | 1.1 | -0.0518em | Centered chapter introductions and closing invitation. |
| footer-promise | Bricolage Grotesque | 500 | 41.9px | 1.1 | -0.0363em | Two-line statement in the black footer. |
| feature-heading | Bricolage Grotesque | 500 | 32px | 1.2 | -0.03em | Feature chapters and major timeline numbers. |
| item-heading | Bricolage Grotesque | 500 | 24px | 1.2 | -0.03em | Timeline step titles and compact problem statements. |
| question | Inter | 500 | 18px | 1.4 | -0.04em | FAQ questions and inset card titles. |
| action | Geist | 400 | 17px | 1.4 | normal | Main pill button labels. |
| body | Geist | 500 | 16px | 1.3 | normal | Section support paragraphs and short explanatory lines. |
| eyebrow | Geist | 500 | 15px | 1.4 | -0.007em | Unboxed orange feature labels. |
| badge | Geist | 500 | 15px | 1.4 | normal | Centered tinted section labels. |
| navigation | Geist | 500 | 15px | 1.3 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11", "ss01", "ss03", "ss04" | Header text links. |
| header-action | Geist | 400 | 14px | 1.3 | normal | Compact navigation pill. |
| card-label | Inter | 600 | 14px | 1.4 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Comparison row labels and compact feature labels. |
| footer-link | Inter | 500 | 14px | 1.2 | -0.01em | Footer links and metadata. |
| detail | Geist | 500 | 13px | 1.4 | normal, features "cv01", "cv05", "cv09", "cv11", "ss03" | Feature descriptions and comparison details. |
| timeline-label | Geist | 400 | 12px | 1 | normal, uppercase, features "ss01", "ss02", "ss03", "ss04" | Tiny outlined time-unit labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company mission openings | mission-display | Bricolage Grotesque | 500 | 50px | 1.1 | -0.05em, features "cv01", "cv05", "cv09", "cv11", "ss03" | Centered single-sentence mission. |
| personnel cards | person-name | Bricolage Grotesque | 500 | 38px | 1.1 | -0.06em | Name beside circular portrait. |
| pricing effort summaries | effort-number | Geist Mono | 500 | 12px | 1.4 | normal, features "cv01", "cv05", "cv09", "cv11", "ss03" | Orange time and participation commitments. |

**Notes:**

- The display face supplies character without heavy bold: keep headings at 500 and tighten tracking, especially the 58px opening.
- Use 44px centered headings for chapter-level pauses and 32px left-aligned headings for explanations. Body information is deliberately much smaller, at 13–16px.
- Geist Variable is the regular-weight cut used for actions and time-unit labels; it belongs to the same text family rather than a separate visual system.

## Layout

**Density:** Airy outside, compact inside: large pauses separate chapters while card copy uses short 8–10px gaps.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-support gaps and FAQ row separation. |
| 10px | Repeated small groups, detail paragraphs and effort-card gutters. |
| 16px | Nested panel inset and compact group separation. |
| 24px | Standard text inset, centered heading groups and pill side padding. |
| 32px | Container side padding and feature row gaps. |
| 40px | Heading-group top and bottom padding. |
| 64px | Large stacked groups and footer separation. |
| 80px | Timeline section vertical padding. |
| 320px | Opening text-to-device layout gap, occupied visually by the central illustration. |

### Containers and grids

- **marketing-container**: max width 1200px · side padding 32px. Centered desktop stage; nested media and copy commonly occupy 1136px inside it.
- **section-heading-container**: max width 900px · side padding 16px. Centered section heading groups and timeline rows.
- **compact-panel**: max width 1000px. FAQ, roadmap and pricing effort panels.
- **feature-pair**: 2 columns · gap 32px · side padding 32px. Alternating text and media, with a roughly 536px text region beside a 568–576px media frame.
- **editorial-column** (only for company narrative pages): max width 600px. Narrow, left-aligned narrative writing on company pages.
- **effort-grid** (only for pricing effort summaries): 4 columns · gap 10px. Four equal 219px cards inside a warm nested tray.
- **team-grid** (only for company pages): 2 columns · gap 8px. Paired personnel badges inside a 1200px molded backing.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action-pill | 200px |
|  | section-badge | 70px |
|  | feature-media | 20px |
|  | problem-card | 30px |
|  | panel | 40px |
|  | device-surround | 60px |
|  | device-rim | 37px |
|  | faq-row | 24px |
| company pages | portrait | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | device | `0px 0px 0px 6px #000000, 0px 50px 48px 0px rgba(0,0,0,0.59)` | Opening product frame only. |
| company pages | badge-slot | `0px 2px 4px 0px rgba(0,0,0,0.25) inset` | Recessed slot on personnel badges. |

### Surfaces

#### Canvas · level 0

**Use:** Default page field.

**CSS:** `background: #fafafa`

#### Molded tray · level 1

**Use:** Group white cards as a single tactile object.

**CSS:** `background: #ecebe8; border-radius: 40px; padding: 16px`

**Observed:** A broad warm-gray rim remains visible around the content; the large role demonstration and personnel wall use 48px outer corners.

**Transfer:** Nest a smaller white radius inside a larger warm backing, rather than drawing heavy outlines.

#### White panel · level 2

**Use:** Main role demonstration and content cards.

**CSS:** `background: #ffffff; border-radius: 40px; box-shadow: rgba(0, 0, 0, 0.03) 0px 0.7px 0.7px -0.4px, rgba(0, 0, 0, 0.03) 0px 1.8px 1.8px -0.8px, rgba(0, 0, 0, 0.03) 0px 3.6px 3.6px -1.3px, rgba(0, 0, 0, 0.03) 0px 6.9px 6.9px -1.7px, rgba(0, 0, 0, 0.03) 0px 13.6px 13.6px -2.1px, rgba(0, 0, 0, 0.03) 0px 30px 30px -2.5px`

**Observed:** Soft layered elevation makes panels feel molded rather than glossy.

#### Device glass surround · level 1

**Use:** Large opening interface stage.

**CSS:** `background: rgba(204,204,204,0.2); border-radius: 60px; padding: 26px; backdrop-filter: blur(5px)`

#### FAQ shell · level 1

**Use:** Dense objection-handling block.

**CSS:** `background: #000000; border-radius: 26px; padding: 8px; display: flex; flex-direction: column; gap: 8px`

#### Landscape-to-black ending · level 0

**Use:** Closing invitation, illustration and footer as one continuous scene.

**CSS:** `background: linear-gradient(#fafafa 38%, #000000 49%); padding-bottom: 40px`

**Observed:** The illustrated foreground masks the color transition, so it reads as a landscape falling into shadow, not an exposed gray gradient.

**Transfer:** Overlay an original wide landscape and its dark foreground on the transition.

#### Warm inset · level 2

**Only for:** pricing and company pages

**Use:** Secondary tray inside effort panels and biography boxes.

**CSS:** `background: #f7f6f2; border-radius: 30px; padding: 16px`

**Observed:** Biography boxes use 20px corners and 22px padding.

## Components

### Navigation

**Use:** Persistent orientation and compact conversion.

**CSS:** `position: fixed; height: 64px; background: #fafafa; display: flex; justify-content: space-between; align-items: center; padding: 0px 16px 0px 6px; z-index: 3`

**Text style:** `navigation` — Geist 500 · 15px/1.3

**Observed:** Small symbol and wordmark at left, a centered cluster of muted links with 36px gaps, compact black action at right. Current-page links turn orange.

**Transfer:** Keep navigation visually subordinate to the illustrated opening.

### Primary button

**Use:** Main conversion in the opening and closing invitation.

**CSS:** `background: #000000; color: #ffffff; border-radius: 200px; height: 50px; padding: 0px 24px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Geist 400 · 17px/1.4

**Observed:** Centered text, a soft downward shadow and no visible icon. The prominent opening action floats just above the product frame; typical width is 230px.

**Transfer:** Use an action tied to a concrete next step rather than a vague discovery verb.

### Header button

**Use:** Compact navigation action.

**CSS:** `background: #000000; color: #ffffff; border-radius: 200px; height: 39px; padding: 0px 24px; display: flex; align-items: center; justify-content: center`

**Text style:** `header-action` — Geist 400 · 14px/1.3

**Observed:** The same black pill construction at a smaller scale, without the opening button's pronounced shadow.

### Navigation link

**Use:** Secondary navigation and page selection.

**CSS:** `color: rgba(0,0,0,0.56); text-decoration-line: none; transition: color 0.4s cubic-bezier(0.44, 0, 0.56, 1)`

**Text style:** `navigation` — Geist 500 · 15px/1.3

**Observed:** Text-only links; orange indicates the current page.

**States:** Declared: hover color #000000 and no underline; focus-visible unknown.

### Section badge

**Use:** Short topic marker above centered headings.

**CSS:** `background: rgba(255,64,0,0.07); color: #ff4000; border-radius: 70px; padding: 10px 19px`

**Text style:** `badge` — Geist 500 · 15px/1.4

**Observed:** A faint warm lozenge with short sentence-case text. Unboxed orange eyebrows are used within feature chapters.

### Device frame

**Use:** Opening product demonstration.

**CSS:** `border-radius: 37px; box-shadow: 0px 0px 0px 6px #000000, 0px 50px 48px 0px rgba(0,0,0,0.59); overflow: hidden`

**Observed:** An inset interface is held inside a substantial rounded device, layered over Device glass surround. Its desktop stage is 1084px wide.

**Transfer:** Show one believable product task, not a collage of unrelated floating windows.

### FAQ row

**Use:** Objection-handling question.

**CSS:** `background: rgba(255,255,255,0.12); color: #ffffff; border-radius: 24px; padding: 24px; display: flex; gap: 16px`

**Text style:** `question` — Inter 500 · 18px/1.4 · tracking -0.04em

**Observed:** Question text sits left; a small plus sits in a 28px circular dark translucent control at right. Rows are grouped in FAQ shell.

**Transfer:** Write questions in the customer's language. Expanded-answer styling is unspecified.

### Roadmap card

**Use:** Compact future-progress summary.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 32px; border-top: 1px solid rgba(0,0,0,0.15); border-right: 1px solid rgba(0,0,0,0.15); border-bottom: 1px solid rgba(0,0,0,0.15)`

**Text style:** `detail` — Geist 500 · 13px/1.4

**Observed:** Four near-touching cards share a Molded tray. Short period labels accompany orange points and fine black vertical tick marks; body text explains the outcome. The first card has 30px padding.

### Footer link

**Use:** Company and policy navigation on black.

**CSS:** `color: rgba(255,255,255,0.56); text-decoration-line: none; transition: color 0.4s cubic-bezier(0.44, 0, 0.56, 1)`

**Text style:** `footer-link` — Inter 500 · 14px/1.2 · tracking -0.01em

**Observed:** One narrow right-side column with 16px gaps; active page uses orange. Social symbols and a small assurance mark sit in the lower right.

**States:** Declared: hover color #ffffff and no underline; focus-visible unknown.

### Effort card

**Only for:** pricing effort summaries

**Use:** Explain participation alongside the offer.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 22px; height: 365px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `question` — Inter 500 · 18px/1.4 · tracking -0.04em

**Observed:** Small black icon, title and muted detail occupy the top; orange monospaced time commitment is pinned at the bottom. Four cards sit inside Warm inset.

**Transfer:** Expose the buyer's required contribution, not just a list of benefits.

### Personnel badge

**Only for:** company pages

**Use:** Introduce people and their experience.

**CSS:** `background: #ffffff; border-radius: 40px; padding: 66px 24px 24px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `person-name` — Bricolage Grotesque 500 · 38px/1.1 · tracking -0.06em

**Observed:** An inset rounded attachment slot is centered above a circular 180px illustrated portrait and name/role pair. Biography sits in a separate warm inset below. A black recruitment variant replaces the profile with a centered invitation and white pill.

**Transfer:** Preserve the physical badge metaphor with original portraits and concise credentials.

## Imagery and graphics

### Human-centered opening illustration

**Use:** Central protagonist in the opening, integrated with the device stage.

**Observed:** A side-profile operator with gray wavy hair, yellow safety glasses, light workwear and a tablet bridges the text and product. Fine dark outlines and painterly cel shading keep the figure warm and approachable. The body dissolves toward the device; bright orange structural arcs and glimpses of a cyan-green environment frame the lower stage.

**Transfer:** Commission an original user in the new product's context. Minimum equivalent: an original outlined SVG half-body figure with softly shaded clothing, one warm accessory and a relevant handheld object, layered between headline columns and the device.

**Build:** Use a transparent central SVG figure about 440px wide with charcoal outlines and flat light-gray clothing shapes. Place two broad vermilion curved bands behind the lower device corners, and a full-width environmental strip behind those. Fade the lower figure into the canvas with a mask; retain readable separation from both text columns.

### Painterly environmental panorama

**Use:** Full-width atmospheric punctuation and the signature closing transition.

**Observed:** An optimistic landscape with turquoise sky, luminous peach clouds, yellow-green distant hills and deep blue-purple industrial architecture. At the ending, a broad building with solar panels sits beyond a sunlit courtyard; large cactus and foliage silhouettes darken toward the foreground and merge into the black footer.

**Transfer:** Use a future-facing environment specific to the new product, with a simple architectural focal point and bright horizon. The minimum acceptable equivalent is an original layered SVG landscape, not generic stock photography.

**Build:** Create a wide SVG with a pale cyan sky, soft peach cloud silhouettes, layered olive-green hills, one dark indigo architectural mass and a warm peach ground plane. Add dense dark foreground vegetation at both lower corners. Overlay a transparent-to-black vertical gradient across the lower third so the bottom joins the footer without a seam. Keep these illustration colors inside artwork rather than marketing text tokens.

### Interface demonstrations

**Use:** Opening device and alternating capability chapters.

**Observed:** Mostly pale interfaces with fine gray edges, small black text and sparse orange actions. Demonstrations include workflows on dotted technical fields, close-up forms and chat panels. Frames are roughly 568–576px by 447–453px with 20px corners and soft shadows.

**Transfer:** Show real UI or a credible simplified task in a single stable frame; preserve the pale, restrained backing and legible hierarchy. Internal UI tokens remain separate from marketing colors.

### Isometric process objects

**Use:** Timeline steps and technical capability illustrations.

**Observed:** Small white extruded lozenges and black-topped rounded chips float on white, often connected by fine dotted paths. Light gray depth and soft contact shadows make them tactile; narrow orange, pink and cyan edge accents appear on active chips. Timeline images occupy 400px by 212px beside text.

**Transfer:** Use short labels from the new process and a few objects per scene.

**Build:** Construct SVG rounded rectangles transformed into a shallow isometric plane. Offset two light-gray duplicate layers downward to create thickness, add a blurred black shadow at low alpha, and place either a white or black top face. Connect centers with fine dotted gray paths; give the active object a thin warm edge with a restrained cyan offset.

### People and story media

**Only for:** company pages

**Use:** Large story video and personnel wall.

**Observed:** The story video is a warmly lit, real interior interview framed across most of the content width. Personnel instead use clean illustrated circular busts with thin dark outlines; a larger group illustration has bright pastel architectural glazing behind it.

**Transfer:** Use original human interviews for the story and a consistent illustration treatment for personnel. Keep the two media roles distinct.

### Icons

**Observed:** Small monochrome functional symbols, mostly black at 18–24px; pricing feature marks are simple and technical. Orange 30px symbols emphasize offer outcomes. Plus controls appear in subdued circles inside FAQ rows.

**Transfer:** Choose simple compact outline or solid technical symbols, not colorful emoji or elaborate illustrated pictograms.

## Section recipes

How recurring sections are built.

### First screen: Human and device opening

**Observed:** A fixed 64px Navigation leaves a large off-white breathing area before the main composition. Inside the 1200px stage, a three-line 58px display promise occupies roughly the left two fifths; the illustrated person stands centrally and a narrow right column pairs a 16px bold problem/answer line with smaller muted explanation. Faint vertical hairlines bracket the text. The headline ends in an orange dot. Behind the lower composition, environmental color and broad orange arcs lead into Device glass surround and Device frame. Primary button is centered immediately above the frame. Within the first 900px, the full headline, supporting copy, person, action and upper part of the device are visible; most of the product demonstration continues below the fold.

**Transfer:** Keep the promise/person/explanation triangle using an original user illustration, then let a believable product task emerge from the lower edge. Company pages open with a centered 50px mission sentence and wide interview video. Offer pages use a left title, right explanation and wide illustrated horizon followed by a slim proof strip.

**Avoid:** Do not replace the three-part composition with a centered headline over a generic dashboard, or shrink the illustration into a small decorative avatar.

**Text style:** `display` — Bricolage Grotesque 500 · 58px/1.1 · tracking -0.05em

### Centered chapter introduction

**Observed:** Section badge precedes a centered 44px section-heading, often in two short lines; muted 16px support follows. Heading groups sit in a 900px container with 40px vertical padding and 24px gaps. Some introductions deliberately combine orange introductory words, a black promise and a gray outcome line.

**Transfer:** Use brief topic labels and a single outcome-led title to create a pause between denser demonstrations.

**Text style:** `section-heading` — Bricolage Grotesque 500 · 44px/1.1 · tracking -0.0518em

### Role demonstration tray

**Observed:** A row of small uppercase role tabs with thin lower rules sits above Molded tray. The selected rule is orange. Inside White panel, a left explanation column balances a large right product task, with the heading near the top and supporting use cases lower down.

**Transfer:** Adapt tabs to genuine user contexts and show how the same product changes its task presentation for each.

### Problem and resolution stack

**Observed:** A compact 24px problem statement and action sit to the left of stacked white rounded cards. Each card has a protruding labeled tab, an upper muted current-state paragraph and a lower black resolution paragraph marked by an orange label and fine vertical rule.

**Transfer:** Use concrete before/after situations. Keep the resolution specific enough to be demonstrated, rather than inventing generic benefit tiles.

### Decisive comparison table

**Observed:** A centered chapter heading introduces a broad five-column matrix: row labels, a bright orange preferred column, and three pale alternatives. Rows have fine horizontal separators; orange cells use white small text and the preferred column has a rounded top cap. Header labels are darker and larger than cell descriptions.

**Transfer:** Reserve the strongest flat orange fill for one meaningful point of comparison; choose buyer-relevant criteria.

### Alternating capability pair

**Observed:** Feature-pair alternates text and Interface demonstrations. An orange eyebrow and 32px feature heading sit high in the text column; a short bold subclaim and 13px detail paragraph sit lower, creating a deliberate pause within the column. Demonstration panels use feature-media corners.

**Transfer:** Use one demonstrable capability per pair and vary the side without changing the type hierarchy.

**Text style:** `feature-heading` — Bricolage Grotesque 500 · 32px/1.2 · tracking -0.03em

### Process timeline

**Observed:** A narrow vertical line with small black dots and orange progress segments sits left of 900px rows. Each step combines a tiny outlined timeline-label, a 32px number with orange full stop, a 24px item-heading and 13px explanation. Isometric process objects occupy the right half. Rows are about 272px tall with substantial white space.

**Transfer:** Describe a real onboarding or transformation sequence with concrete checkpoints; retain the numerical punctuation and tactile objects.

**Text style:** `item-heading` — Bricolage Grotesque 500 · 24px/1.2 · tracking -0.03em

### Objections and cinematic closing

**Observed:** A Section badge and 44px title introduce FAQ shell and FAQ rows. The separate closing invitation returns to the light canvas with a centered 44px question, 16px gray support and Primary button. Painterly environmental panorama then spans the entire page and fades into Landscape-to-black ending. Below it, the left footer carries a small symbol and a two-line footer-promise; a single link column sits right, with metadata and social/assurance marks along the bottom.

**Transfer:** Keep the light invitation, illustrated horizon and dark footer as distinct but visually continuous layers. Adapt the invitation to the next real decision the reader can make.

**Text style:** `footer-promise` — Bricolage Grotesque 500 · 41.9px/1.1 · tracking -0.0363em

### Offer and participation

**Only for:** pricing pages

**Observed:** An illustrated horizon and four-cell assurance strip introduce a single engagement panel rather than a tiered price-card wall. A white rounded offer box sits inside a warm backing with a left invitation/action and a right checklist. Later, Effort cards make the user's time contribution explicit inside nested trays.

**Transfer:** For bespoke offers, state the starting engagement, what it includes and what the buyer contributes. Do not invent numeric prices when the offer requires a conversation.

### Personnel and recruitment wall

**Only for:** company pages

**Observed:** A centered team heading introduces a warm 48px-radius backing and tightly paired Personnel badges. A group illustration occupies the second cell of the opening row. The final cell is black, with a centered two-line recruitment invitation, orange period and white action.

**Transfer:** Keep the personnel layout visibly different from ordinary feature panels; end the wall with a practical invitation.

## Page flow

**Storyline:** Outcome promise → tangible product or human proof → concrete explanations → adoption and commitment → objections → illustrated closing invitation.

### Product marketing landing page

1. **Promise** — Three-part human-centered opening and a large framed product task.
2. **Positioning** — Centered introduction clarifies the offer and reassures readers about existing systems.
3. **Product demonstration** — Role-based demonstration tray shows a relevant task.
4. **Problem resolution** — Specific before/after scenarios in a long card stack.
5. **Comparison** — A matrix with one emphatically orange preferred column.
6. **Capability chapters** — Alternating explanation and interface media.
7. **Adoption** — Numbered vertical timeline and compact roadmap cards.
8. **Objection handling** — Dark inset FAQ block.
9. **Closing call** — Light invitation, landscape transition and black footer.

**Transfer:** Choose a useful subset of narrative beats for the new product while retaining the human opening, tangible product staging and cinematic ending.

### Company and trust narrative

1. **Mission** — Single centered sentence followed by a broad interview video.
2. **Belief and reassurance** — Narrow prose column contrasts current pain, future outcomes and commitment.
3. **Human credibility** — Illustrated personnel badges and group portrait in a warm molded wall.
4. **Participation** — Black recruitment cell with white action.
5. **Closing call** — Shared light invitation and landscape-to-black footer.

**Transfer:** Use specific people and working beliefs to support trust rather than turning the page into a second feature list.

### Offer clarification and purchase readiness

1. **Offer framing** — Split title/explanation above a full-width painted environment.
2. **Reassurance** — Four compact proof cells with technical icons.
3. **Engagement** — Single starting-offer panel with contact action and checklist.
4. **Included capabilities** — Five compact outlined feature cells.
5. **Adoption** — Shared timeline of checkpoints with isometric objects.
6. **Buyer commitment** — Four effort cards with bottom-aligned orange time notation.
7. **Closing call** — Shared invitation, illustrated landscape and black footer.

**Transfer:** Favor clear engagement scope and buyer effort over conventional subscription tiers when the purchase is consultative.

## Writing

Direct, practical and optimistic, with sympathy for people dealing with awkward tools. Confident claims are grounded in concrete tasks and a small, testable first step rather than abstract transformation language.

**Do not copy:** Do not reuse the Humble name, logo, artwork, team identities, proprietary descriptions, certifications, acquisition histories, promises, delivery timings or numerical claims. Source examples illustrate voice only; replace them with substantiated facts for the new product.

- **Addressing the reader:** Speak to the reader as you and your. The product is named in explanatory sentences; we appears when discussing responsibilities and working commitments.
- **Rhythm:** Short headline fragments, compact one-sentence support and longer task-specific explanations. Use em dashes and contrasts for emphasis; occasional conversational shorthand makes technical material approachable.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Reader's future outcome, expressed as a compact noun phrase. | 6–10 words | “Your Factory's Next 10 Years of Productivity.” |
| Reassurance | Name a feared disruption, reject it, then offer an incremental route. | One short paragraph | “Start small, prove value, expand when ready.” |
| Feature headline | Plain capability with a useful human outcome. | 4–8 words | “An Interface Everyone Can Use” |
| Primary action | Verb plus concrete next step; first person can personalize the action. | 3–5 words | “Start my 24h Build”<br>“Book a Call” |
| Objection | A credible first-person customer concern, not a keyword heading. | One direct question | “My operators barely use our current systems. Why would they use this?” |
| Commitment | State the reader's contribution plainly alongside the promised speed. | One sentence plus short notation | “We compress 6 months into 2 weeks — but we need focused time:” |

**Words and phrasing to use:** your; real work; next step; start small; prove value; works alongside; daily; plain-language task names

**Avoid:** revolutionary platform; unlock unlimited potential; frictionless synergy; future-proof everything; unqualified superlatives

**Rules:**

- Pair every technical capability with a recognizable task or failure mode.
- Use concrete nouns and active verbs; explain what happens next.
- Acknowledge existing tools and sunk effort instead of belittling the buyer.
- Present constraints and buyer responsibilities as plainly as benefits.
- Let a short reassuring sentence close a dense paragraph.

## Do's and Don'ts

### Do

- Keep the opening headline at 58px, weight 500 and -0.05em tracking on desktop.
- Use 44px centered chapter titles and 32px left-aligned capability titles.
- Pair 40px panel corners with a wider warm-gray surrounding tray.
- Use a 50px black pill for principal actions and a 39px version in navigation.
- Keep detail copy compact at 13px/1.4, with 10px local gaps.
- Stage product media in substantial rounded frames, with 20px corners for repeated demonstrations.
- Give one comparison column the full orange emphasis when comparison is needed.
- Carry the illustrated closing environment all the way into the black footer.

### Don't

- Do not use heavy 700-weight display typography; the tight medium-weight face supplies the emphasis.
- Do not make orange the page canvas; reading sections stay off-white and orange fills remain localized.
- Do not substitute square controls or small-radius rectangular primary buttons for the 200px pill construction.
- Do not turn the 13px product explanations into oversized editorial paragraphs.
- Do not apply the 6px black device rim to every small media card.
- Do not use the personnel badge slot and circular portrait treatment for generic feature cards.
- Do not spread rainbow interface colors into navigation, headings or action fills.
- Do not replace the single footer link column with a dense multi-column directory.

## Motion and responsive

### Motion

**Observed:**

- Text links declare color 0.4s cubic-bezier(0.44, 0, 0.56, 1). Navigation links darken to black on hover; footer links lighten to white.
- The navigation stays fixed while content scrolls. Timeline content uses opacity and perspective translation.

**Transfer:**

- Keep text-link feedback limited to the declared color change.
- Keep the illustrated composition stable enough that the person, headline and device read as one scene.

**Unknown:**

- Exact scroll-trigger timing and easing, video playback behavior and button label animation are unspecified.
- Focus-visible and active button styles are unspecified.

### Responsive

**Observed:**

- Width rules occur around 810px, 1200px and 1440px; desktop containers are capped at 1200px.

**Transfer:**

- On narrower layouts, preserve promise → illustration → explanation → device reading order and move the supporting column below the headline.
- Stack alternating capability pairs without losing their eyebrow/title and lower supporting-copy relationship.
- Keep the closing panorama full bleed and preserve its dark foreground transition; stack footer content rather than compressing its promise into tiny text.

**Unknown:**

- Mobile type sizes, navigation replacement and exact breakpoint-specific layouts are unspecified. These collapse rules are adaptation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
