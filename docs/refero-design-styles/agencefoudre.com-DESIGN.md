# Foudre — punchy pink card theatre

## Overview

A playful, emphatic editorial style where condensed block lettering and tactile stacks of portrait imagery turn a long page into a sequence of little stages. Bubblegum pink, raspberry, peach cream and forest green make it bright rather than stark, with occasional lavender interludes. Dense grotesk captions and warm, natural photography ground the theatrical scale; it suits personality-led products, creative services and visually rich launches.

### Essentials

- Headlines behave like tightly packed poster lettering: Beni 900 at 94px/0.7 for chapter titles, 130px/0.7 for display lines, and 230.4px/0.7 for monumental statements; tracking stays normal and a second phrase changes color.
- The opening is a full-height graphic stage rather than a conventional banner: 900px tall at desktop, 30px edges, an oversized upper word sculpture, a central 450px-wide media stack and a lower-left descriptor plus display promise.
- Color fills entire chapters, not just buttons: pink #f29ebd is the default canvas, cream and lavender relieve it, and raspberry #db3c8a and forest #00522d form opposing card faces. Each screen has one dominant flat field; no gradients or shadowed white dashboard grid.
- Cards feel dealt by hand: portrait media around 450×680px and numbered cards with 25px corners, 60px padding and slight alternating rotation. A new page includes this stacked-card device, using product details or simple typographic cards when photography is unavailable.
- Controls are tiny marks inside generous shapes: fixed 60px circular corner buttons, 30px story arrows and a 10px-radius primary action with 12px bold type and 20px padding; text actions are not giant pills.
- Warmth interrupts the posters through three-emoji thought bubbles: 30px glyphs, 15px padding, 20px corners and a slight tilt, beside rather than inside the main heading.
- The ending has its own spectacle: overlapping photo and raspberry contact cards above a forest-green, nearly edge-to-edge word sculpture on pink, with a fine 12px utility row underneath. Use the new product's name or a short closing word at the same monumental scale.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Bubblegum canvas | `#f29ebd` | `--color-pink` | background, surface, action, text | Default landing canvas, round corner controls, secondary headline phrase and small conversion buttons. |
| Raspberry ink | `#db3c8a` | `--color-raspberry` | text, background, surface, accent, action | Primary headline ink on light fields; saturated chapter fields and alternating process cards. |
| Forest counterpoint | `#00522d` | `--color-forest` | text, surface, accent, border | Alternating process faces, benefit cards, footer word sculpture, control icons and 2px focus outline. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender interlude | `#d1cfe4` | `--color-lavender` | background, text | Capability-stage field and occasional small descriptor; pairs with raspberry and cream. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm white | `#fff8f6` | `--color-cream` | text, background, surface, border | Reversed text, tags, thought bubbles, light chapters and fine rules. Story controls use this hue at 40% alpha; quiet stat controls use 20%. |
| Peach paper | `#fce5df` | `--color-peach` | background, surface, text | Process-stage relief, thought bubbles and large reversed words; related-content ending canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light photographic case studies | Rose proof face | `#e878b2` | `--color-case-pink` | surface, background | Text and statistic cards in a light, coastal photographic story. |
| earth-toned case studies | Earth proof face | `#604a34` | `--color-case-earth` | surface, background | Text and statistic cards accompanying warm leather, wool and workshop imagery. |
| portfolio indexes | Muted blush field | `#eacccc` | `--color-index-blush` | background | Final index chapter's muted canvas behind cream type. |
| case-study navigation | Soft return link | `#f1adcb` | `--color-return-pink` | link, text | Small fixed return link variant; change to raspberry against peach and cream against darker photography-led fields. |

## Typography

- **Beni** — Display promises, section headings, card headings and large numerals. Extremely heavy, compressed, playful block sans with tight counters and irregular graphic energy. If unavailable, use **Anton**. Use its heaviest visual weight; tune horizontal scale to maintain the narrow poster silhouette. Font stack: "Beni", "Anton", Impact, sans-serif.
- **Clash Grotesk** — Body copy, labels, supporting statements and controls. Contemporary geometric grotesk with assertive bold cuts and compact small type. If unavailable, use **Space Grotesk**. Use weights 400, 500 and 700; preserve compact line heights. Font stack: "Clash Grotesk", "Space Grotesk", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| monumental | Beni | 900 | 230.4px | 0.7 | normal | size min(30rem, 16vw) | Large background statements and process numerals. |
| display | Beni | 900 | 130px | 0.7 | normal | fixed | Lower opening promise and short centered impact lines; also the large number treatment within proof cards. |
| heading | Beni | 900 | 94px | 0.7 | normal | fixed | Chapter titles and case-study titles, broken into emphatic short lines. |
| closing | Beni | 900 | 80px | 0.7 | normal | fixed | Short invitation in the overlapping contact card. |
| card-heading | Beni | 900 | 46px | 0.7 | normal | fixed | Process, capability and benefit-card headings. |
| summary | Clash Grotesk | 700 | 24px | 0.85 | normal | fixed | Accordion questions and centered proof-card labels. |
| lead | Clash Grotesk | 700 | 20px | 1.2 | normal | fixed | Small opening descriptor and one-sentence capability introduction. |
| body | Clash Grotesk | 400 | 16px | 1.2 | normal | fixed | Explanatory paragraphs and centered contact support. |
| body-compact | Clash Grotesk | 400 | 16px | 1.2 | normal | fixed | Short process descriptions and benefit-card paragraphs. |
| body-strong | Clash Grotesk | 700 | 16px | 1.2 | normal | fixed | Bold opening sentence before an explanatory paragraph. |
| label | Clash Grotesk | 500 | 12px | 0.85 | normal | fixed | Capability tags, media metadata and small utility text. |
| action | Clash Grotesk | 700 | 12px | 0.85 | normal | fixed | Primary action and compact project links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| case-study endings | related-caption | Clash Grotesk | 700 | 16px | 1.2 | normal, uppercase | fixed | Centered names beneath circular related-story links. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Beni supplies the capitals' compact silhouette; do not imitate it with a wide grotesk and extreme negative tracking. Its 0.7 line height is intentional, while surrounding blocks need enough separation to keep letters from colliding.
- Color changes emphasize a whole closing phrase rather than isolated random words. Emphasized display phrases stay upright.
- Small prose stays visually subordinate: 16px paragraphs beside 94px headings, not a smooth conventional heading ladder. Keep explanatory measures around 300–334px in three-part stages.

## Layout

**Density:** Airy stages with compact content: large full-height pauses surround closely set titles, labels and small paragraphs.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Wrapped tag gaps. |
| 10px | Small heading separation. |
| 12px | Tag padding. |
| 15px | Base column gutter, heading/support gaps and bubble padding. |
| 20px | Button padding and accordion item gap. |
| 30px | Outer page inset, media-column gaps and benefit-card padding. |
| 60px | Process and proof-card padding; contact-stage separation. |
| 90px | Related-story ending's vertical padding. |
| 120px | Introductory section padding and top clearance on case studies. |
| 140px | Capability chapter separation. |
| 280px | Deep vertical breathing room around the question section. |

### Containers and grids

- **stage-grid**: max width 1920px · 24 columns · gap 15px · side padding 30px. Full-width editorial scaffold. Three-part chapters assign roughly one third to the title, one third to a central portrait and the remaining third to compact explanation.
- **portrait-stack**: max width 450px. Centered portrait and process stack within the middle eight columns; side text remains comparatively small.
- **benefit-stage**: max width 1900px · 4 columns · gap 30px · side padding 30px. Four independent tilted benefit cards across a monumental background title.
- **case-media** (only for case studies): 2 columns · gap 30px. Right two thirds of a case study contain independent vertical media columns around 443px wide; left third holds sticky identity and tags.
- **related-row** (only for case-study endings): 5 columns · gap 15px. Five circular destinations across the right side of a full-height ending, title on the left.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action-and-tags | 10px |
|  | bubbles-and-benefits | 20px |
|  | process-and-contact-cards | 25px |
|  | round-controls-and-related-media | 50% |
| portfolio and case-study media | story-and-proof-cards | 30px |

## Surfaces and depth

### Surfaces

#### Pink stage · level 0

**Use:** Default marketing canvas.

**CSS:** `background-color: #f29ebd`

**Observed:** A continuous flat color field runs behind freely overlapping objects.

**Transfer:** Make color a stage, not a frame around a white site.

#### Peach relief · level 0

**Use:** Breathing space for process and related-content compositions.

**CSS:** `background-color: #fce5df`

**Observed:** Raspberry headings and cream or green card objects sit against warm peach.

**Transfer:** Use between visually saturated chapters.

#### Lavender stage · level 0

**Use:** Capability storytelling.

**CSS:** `background-color: #d1cfe4`

**Observed:** Raspberry title and active category contrast with cream inactive category headings.

**Transfer:** Keep the field solid and pair with natural portrait photography.

#### Raspberry poster · level 1

**Use:** Numbered method cards and the contact card.

**CSS:** `background-color: #db3c8a; color: #fff8f6; border-radius: 25px; box-shadow: none`

**Observed:** Opposed by forest faces in stacks; no border or simulated paper texture.

**Transfer:** Use the contrast between flat color and warm media to create depth.

#### Forest face · level 1

**Use:** Alternating process cards and smaller benefit cards.

**CSS:** `background-color: #00522d; color: #fff8f6; border-radius: 20px; box-shadow: none`

**Observed:** Benefit cards are narrower and more compact than numbered process cards; process faces retain 25px corners.

**Transfer:** Use green as the deliberate opposing card color, not a general dark theme.

#### Rose proof panel · level 1

**Only for:** light photographic case studies

**Use:** Text, statistic and social-destination panels.

**CSS:** `background-color: #e878b2; color: #fff8f6; border-radius: 30px; padding: 60px`

**Observed:** Panels match the width of adjacent portrait media and interrupt the two-column flow.

**Transfer:** Keep the same panel family for all proof within one story.

#### Earth proof panel · level 1

**Only for:** earth-toned case studies

**Use:** Text, statistic and social-destination panels.

**CSS:** `background-color: #604a34; color: #fff8f6; border-radius: 30px; padding: 60px`

**Observed:** Warm brown panels echo the material-led photography without adding texture to the page itself.

**Transfer:** Use for a material-rich story, not as the default landing palette.

#### Translucent media control · level 2

**Only for:** story media

**Use:** Small navigation circles over photography.

**CSS:** `background-color: rgba(255, 248, 246, 0.4); border-radius: 50%`

**Observed:** These controls borrow the underlying image color; they are not frosted-glass panels.

**Transfer:** Keep alpha limited to small controls and progress tracks.

## Components

### Corner navigation

**Use:** Persistent menu on the left and contact shortcut on the right.

**CSS:** `position: fixed; width: 60px; height: 60px; border-radius: 50%; background-color: #f29ebd; color: #00522d; display: flex; align-items: center; justify-content: center; z-index: 81`

**Observed:** Each control sits 30px from a top corner with a small centered pictogram. There is no full navigation bar.

**States:** Declared: hover unspecified; focus-visible outline #00522d solid 2px.

**Transfer:** Use menu plus a product-appropriate direct-contact destination.

### Primary button

**Use:** Low-friction conversion inside the closing invitation.

**CSS:** `background-color: #f29ebd; color: #fff8f6; border-radius: 10px; padding: 20px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Clash Grotesk 700 · 12px/0.85

**Observed:** A short, plain label sits inside the raspberry contact card. Its apparent size follows the card's tilt rather than a separate floating treatment.

**States:** Declared: hover unspecified; focus-visible outline #00522d solid 2px.

### Process card

**Use:** A memorable numbered explanation of a method or product sequence.

**CSS:** `background-color: #db3c8a; color: #fff8f6; border-radius: 25px; padding: 60px; display: flex; flex-direction: column; justify-content: space-between; text-align: center`

**Text style:** `card-heading` — Beni 900 · 46px/0.7

**Observed:** Heading at top, monumental two-digit numeral in the middle, short body-compact description near the foot. Alternating forest faces and tiny rotations let previous cards remain visible behind the current face.

**Transfer:** Use a real sequence of tasks or benefits, not decorative numbers detached from content.

### Benefit card

**Use:** Concrete reasons to believe a short promise.

**CSS:** `background-color: #00522d; color: #fff8f6; border-radius: 20px; padding: 30px; max-width: 400px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 15px; text-align: center`

**Text style:** `card-heading` — Beni 900 · 46px/0.7

**Observed:** A cream doodle sits above the display title and a small centered paragraph. Independent rotations make the cards cross the giant title behind them.

**Transfer:** Explain one reason per card, with an everyday symbol rather than a technical feature icon.

### Thought bubble

**Use:** An irreverent emotional annotation next to a title.

**CSS:** `background-color: #fff8f6; border-radius: 20px; padding: 15px; display: inline-flex; position: relative; transform: rotate(8deg)`

**Observed:** Three emoji fill the face; two round tail dots extend below an edge. Peach faces and opposite tilt occur in other chapters.

**Transfer:** Choose a compact trio that makes sense for the new promise.

### Question row

**Use:** Practical objection handling without another card grid.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 15px; padding-bottom: 20px; color: #f29ebd; border-bottom: 1px solid #f29ebd`

**Text style:** `summary` — Clash Grotesk 700 · 24px/0.85

**Observed:** An open, unboxed row on a warm-white chapter; a pink circular plus control with forest mark sits at the far right. Questions can wrap across two very tight lines.

**Transfer:** Use native details/summary for a small set of specific questions.

### Capability tag

**Use:** A compact category label beside project identity or media.

**CSS:** `background-color: #fff8f6; color: #db3c8a; border-radius: 10px; padding: 12px`

**Text style:** `label` — Clash Grotesk 500 · 12px/0.85

**Observed:** Tags wrap with 5px gaps. On the capability stage the active labels invert to raspberry faces and cream text.

**Transfer:** Name short capabilities or use cases, not whole sentences.

### Story frame

**Use:** Portrait image and video galleries.

**CSS:** `position: relative; border-radius: 30px; overflow: hidden; padding: 30px; display: flex; flex-direction: column; gap: 30px`

**Observed:** Full-bleed image underlays thin 2px progress segments along the top. Circular previous/next controls sit midway down; plus, heart, play and mute controls occupy the bottom. Frames are around 443×669px in detailed stories and 421×636px in indexes.

**Transfer:** Keep this social-story grammar for product use in the real world; do not surround it with device chrome.

### Story arrow

**Use:** Previous and next controls within portrait media.

**CSS:** `width: 30px; height: 30px; border-radius: 50%; background-color: rgba(255, 248, 246, 0.4); color: #fff8f6; display: flex; align-items: center; justify-content: center; position: absolute; transform: translateY(-50%)`

**Observed:** A small directional arrow is centered inside the translucent circle; the previous arrow reverses direction.

**States:** Declared: hover unspecified; focus-visible outline #00522d solid 2px; active transform translateY(-50%) scale(0.9).

### Proof card

**Only for:** case studies

**Use:** A quantified result within an image-led story.

**CSS:** `background-color: #e878b2; color: #fff8f6; border-radius: 30px; padding: 60px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 15px; text-align: center`

**Text style:** `summary` — Clash Grotesk 700 · 24px/0.85

**Observed:** Summary label above a display numeral at 130px; a small body caption can qualify the result. A 46px circle at 20% cream alpha sits at the bottom-right for more detail. The earth-toned variant uses the Earth proof panel.

**Transfer:** Show a verified metric, its period or denominator, and one clear interpretation.

### Related circle

**Only for:** case-study endings

**Use:** A visual next destination at the end of a detailed story.

**CSS:** `width: 159px; height: 159px; max-width: 160px; border-radius: 50%; overflow: hidden; display: flex; align-items: center; justify-content: center`

**Text style:** `related-caption` — Clash Grotesk 700 · 16px/1.2 · uppercase

**Observed:** Circular photographic detail above a centered uppercase caption with 15px top separation. The final destination is a raspberry circle with a cream +1 instead of photography.

**Transfer:** Link to adjacent cases, use cases or product stories; keep the row visually compact.

## Imagery and graphics

### Human portrait deck

**Use:** Main central object in editorial and capability stages.

**Observed:** Warm, naturally lit people in a lived-in workplace, a team posed among shelves and furniture, or hands working at a laptop. A tall rounded frame occupies roughly one third of the screen, with smaller differently tilted photographs peeking from behind. Color is realistic and softly lit, not tinted to match the canvas.

**Transfer:** Photograph the people using or making the new product. Without a shoot, use one tightly framed, believable real-world product photograph and two detail views; retain the portrait deck silhouette.

### Word sculpture

**Use:** Oversized opening identity and monumental closing object.

**Observed:** Custom solid letter silhouettes form a tightly packed, nearly edge-to-edge word. The closing version is forest green on pink, around 364px high per letter at desktop, with overlapping contact objects above it.

**Transfer:** Make a similarly compressed graphic word from the new product's own name, or a short outcome word if its name is long. A heavy condensed text-to-SVG version is the minimum acceptable treatment.

**Build:** Use SVG text converted to outlines or a heavy condensed uppercase face in an SVG viewBox. Fit the entire word to a 1380px-wide region with a target height around 364px; use forest fill, no stroke, no shadow, and very narrow inter-letter spaces. Adjust individual glyph widths rather than adding loose tracking. Place the contact objects on a higher layer.

### Thought-bubble sticker

**Use:** Small signature annotation across editorial headings.

**Observed:** Cream or peach rounded face with two trailing circular dots, three colorful emoji and a casual tilt. It is flat, smooth and unshadowed.

**Transfer:** Use the same visual punctuation for the new product's emotional tone; do not turn it into a large illustration.

**Build:** Create an inline-flex face with 20px radius and 15px padding. Place two pseudo-element circles below one side, approximately 14px and 7px across, with the same cream or peach fill. Rotate the whole group by 8deg or -8deg; set the emoji line to 30px.

### Cream doodles

**Use:** One symbol per forest benefit card.

**Observed:** Simple hand-drawn cream outline symbols: a laptop, a hand gesture, a lightning bolt and a face. They read as friendly sketches rather than a uniform enterprise icon library.

**Transfer:** Choose equally familiar symbols tied to the benefit.

**Build:** Draw a small SVG in an approximately 83px square with no fill, a rounded cream stroke and gently irregular paths. Keep the silhouette legible with few interior marks; center it above the heading.

### Lifestyle story media

**Only for:** portfolio and case studies

**Use:** Portfolio cards and detailed proof galleries.

**Observed:** Tall, edge-to-edge photography alternates people, close material details and places. The light story uses ocean blues, white bedding, sunny terraces and airy interiors. The earth story uses full-grain leather, wool, tools, sheep, green countryside and human portraits around a vintage car. Editorial color stays inside the media, with no page-wide photographic background.

**Transfer:** Show outcome, material/process detail and context for a different product. Preserve natural light, tactile close-ups and portrait framing rather than copying the subjects.

### Icons

**Observed:** Functional menu, arrows, plus, heart, play, mute and social marks are small, typically 12–20px, centered in circles. Forest marks appear on pink or cream; reversed marks appear over media. Benefit doodles are a separate illustrative family.

**Transfer:** Use simple recognizable functional glyphs with accessible labels, and reserve hand-drawn outlines for benefit illustrations.

## Section recipes

How recurring sections are built.

### First screen: Word-and-card opening

**Observed:** A 900px desktop stage with 30px outer padding. Layers run from the flat Pink stage to an upper identity sculpture spanning about four fifths of the width, a centered 450px-wide media wrapper, then a lower-left text group. The upper sculpture is about 295px high; the lower group pairs a 20px descriptor with the 130px display promise, with a contrasting phrase embedded in it. Corner navigation sits above these layers. The intended first-screen composition contains identity, central object and lower promise; the next explanatory chapter begins below the fold. There is no conventional hero button row.

**Transfer:** Use the new product's own word sculpture and a portrait deck as the focal object, with a short category descriptor and two-part promise below. If product media is scarce, create a colored typographic card deck rather than abandoning the central object. Detailed story pages open directly with sticky identity and adjacent portrait columns; an index opens with persistent editorial identity beside a featured story.

**Avoid:** Do not replace this with a centered SaaS headline, two horizontal buttons and a wide dashboard image. Do not put long explanatory copy over the word sculpture.

**Text style:** `display` — Beni 900 · 130px/0.7

### Editorial triptych

**Observed:** A 94px heading pair occupies the left third, Human portrait deck the center, and roughly 334px of explanation the right. A bold 16px opening sentence leads into body copy with 15px separation. Thought bubble overlaps the heading's outside edge. The composition uses the stage-grid rather than three bordered columns.

**Transfer:** Introduce the product's point of view through one clear promise, a human or real-world image and one concise explanation.

**Text style:** `heading` — Beni 900 · 94px/0.7

### Horizontal story theatre

**Observed:** A compact sticky title stays on the left while tall Story frames slide across the remaining width, with neighboring cards visibly peeking. Small circular destination thumbnails sit beneath the title. A final raspberry face presents a short invitation to explore more. Background color shifts with the active story.

**Transfer:** Use a handful of richly illustrated outcomes, letting each story have a dominant flat backing color. Keep the theatre as a browsing interlude, not the entire landing page.

### Capability selector stage

**Observed:** Lavender stage with left heading and short lead, Human portrait deck in the center, and a right-side list of 46px capability headings. The active capability is raspberry with wrapped Capability tags below; inactive titles are cream and separated by fine cream rules.

**Transfer:** Explain a small set of related product capabilities using a real image for each. Use the same category order in the selector and imagery.

**Text style:** `card-heading` — Beni 900 · 46px/0.7

### Numbered card performance

**Observed:** Peach relief supports a sticky raspberry/pink title at left, a central stack of Process cards and small right-side explanation. Numerals use monumental type; alternating forest and raspberry cards are individually tilted, with earlier cards peeking behind the active face.

**Transfer:** Use the card-performance device for a method, onboarding journey or set of outcomes. The number of cards follows the new story, not a prescribed count.

**Text style:** `monumental` — Beni 900 · 230.4px/0.7

### Reasons over a monumental statement

**Observed:** A raspberry full-screen field supports a centered, three-line monumental cream/peach statement. Forest Benefit cards rise in front, forming independent tilted columns rather than a tidy equal-height row. The large title remains a background graphic as the cards pass.

**Transfer:** Give one short product conviction architectural scale, then let specific reasons overlap it. Keep descriptions short enough to read within a single card.

**Text style:** `monumental` — Beni 900 · 230.4px/0.7

### Questions without boxes

**Observed:** Warm-white canvas, a two-tone 94px heading at left and a question column around 566px wide at right, with 280px vertical padding. Question rows use pink summaries, pink hairlines and round plus controls; a Thought bubble marks the title.

**Transfer:** Answer actual buying or adoption questions with terse, direct language. Keep the title playful but the answers practical.

**Text style:** `summary` — Clash Grotesk 700 · 24px/0.85

### Overlapping invitation and word ending

**Observed:** Pink stage carries a tall photo tilted -3deg and an overlapping raspberry contact card tilted 6deg. Both have 25px corners and a 500px maximum width. The contact card has 60px vertical and 30px horizontal padding, a small contact label, an 80px invitation, a centered paragraph with 300px measure and Primary button. Word sculpture stretches nearly edge-to-edge beneath them; a small forest utility row closes the page with social icons on one side and legal links opposite.

**Transfer:** Close a marketing page with a human invitation and a specific low-effort action. Use a new real-world photo or a product-detail photograph in the tall companion card; retain the giant word and overlap.

**Text style:** `closing` — Beni 900 · 80px/0.7

### Sticky case-study mosaic

**Only for:** case studies

**Observed:** Identity and Capability tags remain pinned in the left third. Two independent right-side columns contain rounded portrait media, text panels, Proof cards and social destinations separated by 30px. Cool pale slate supports the light coastal story; dark olive supports the material-led story. These themed fields give way to peach at the ending.

**Transfer:** Choose one photographic world and a harmonized backing field per story. Interleave concise explanation and measured outcomes rather than showing an uninterrupted image dump.

### Circular exploration ending

**Only for:** case-study endings

**Observed:** A 900px peach stage with 90px vertical padding places a raspberry 94px invitation at left and five Related circles across the right. A Thought bubble floats near the heading; a small underlined return destination stays lower-left. It ends with exploration links, not the giant marketing word footer.

**Transfer:** Offer neighboring stories plus one all-stories destination; preserve the expansive empty space around the compact row.

**Text style:** `related-caption` — Clash Grotesk 700 · 16px/1.2 · uppercase

### Portfolio index chapters

**Only for:** portfolio indexes

**Observed:** Persistent left title and support line, a central Story frame around 421×636px, and right-side 130px story name with tags, one short paragraph and a compact case action. Chapters have 90px gaps and use story-specific full-screen background colors. The last chapter keeps this structure on muted blush; a fixed lower-left return link is the final navigation, without a separate promotional footer.

**Transfer:** Use as an immersive catalog of outcomes. Let each entry have a coherent photographic identity instead of flattening the stories into equal tiles.

**Text style:** `display` — Beni 900 · 130px/0.7

## Page flow

**Storyline:** Graphic identity → point of view → visual outcomes → capability and method → reasons to believe → practical reassurance → invitation or onward exploration.

### Personality-led marketing landing page

1. **Identity and promise** — Word sculpture and central portrait deck with a compact descriptor and oversized two-part promise.
2. **Point of view** — Short contrast statement followed by an editorial triptych.
3. **Outcome proof** — Horizontal portrait-story theatre with a route into the full collection.
4. **Emotional emphasis** — A full-color typographic impact interlude with a graphic shape.
5. **Capability and method** — Image-backed selector stage followed by numbered card performance.
6. **Reasons to believe** — Forest benefit cards cross a monumental raspberry statement.
7. **Objection handling** — Open question rows beside a playful two-tone heading.
8. **Closing invitation** — Tilted photo/contact pairing, giant green word and compact utility row.

**Transfer:** Adapt the order and length to the product; retain the contrast between poster moments, portrait decks and small explanatory prose.

### A light photographic outcome story

1. **Context** — Sticky identity, category tags and a short positioning line next to two portrait columns.
2. **Demonstration** — Sunlit places, detail imagery, short text and video alternate down independent columns.
3. **Quantified proof** — Rose proof faces interrupt the imagery with large numerals and concise labels.
4. **Direct destination** — A themed panel links to the real-world channels or product.
5. **Onward exploration** — Peach ending with circular neighboring stories and an all-stories destination.

**Transfer:** Use bright, airy imagery for an experience or product whose value is visible in daily life.

### A material-led outcome story

1. **Context** — Sticky identity and a terse three-part positioning line.
2. **Demonstration** — Portrait media mixes makers, tools, materials, origins and product-in-use scenes.
3. **Quantified proof** — Earth proof faces present growth and engagement metrics amid the media.
4. **Direct destination** — A final themed social-destination panel closes the media columns.
5. **Onward exploration** — Same peach circular exploration ending, with a different set of neighboring stories.

**Transfer:** Preserve tactile material detail and the human context; change the subjects and metrics to the new product.

### An immersive index for a collection of visual stories

1. **Orientation** — Persistent left editorial title, supporting line and thought bubble.
2. **Browse proof** — Successive tall story frames pair with large names, tags, short descriptions and compact actions.
3. **Continuation** — Full-screen fields change with each story while the left identity remains stable.
4. **Return navigation** — The final story remains the ending, with a lower-left route back rather than a separate footer.

**Transfer:** Use for portfolios, customer outcomes or use-case collections rather than a generic product landing page.

## Writing

Confident, warm French copy with a playful electrical vocabulary and genuine human presence. It makes bold short statements, then explains the work plainly rather than sustaining a stream of hype.

**Do not copy:** Do not reuse Foudre's name, custom wordmark artwork, client names, source copy, claims of experience, percentages, growth figures or case-study results. Examples below illustrate rhythm only; replace every fact and promise with truthful product-specific content.

- **Addressing the reader:** Use nous for the team and vous/votre for the reader. Short invitations can switch to the conversational on for what happens next.
- **Rhythm:** Headlines are terse, often split into an assertion and a colored answer. Body paragraphs are compact and concrete; a bold first sentence can carry the thesis. Wordplay and three-part fragments provide rhythm without exclamation-heavy selling.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Display promise | A compact identity or promise, with a contrasting final phrase. | 2–7 words per phrase | “Human Social Club”<br>“Nous sommes le courant, vous êtes l’histoire.” |
| Chapter heading | A playful verbal hinge or contrast, broken into short poster lines. | 4–9 words | “Raisonner pour mieux: résonner.”<br>“Petites questions, grandes réponses” |
| Positioning line | A three-part, noun-led fragment with a full stop. | 3–6 words | “Tradition, matière, caractère.” |
| Support | Explain the mechanism and remove friction with concrete quantities and a human next step. | 1–3 short sentences | “Un mini quiz, 3 questions, moins d’une minute. On reçoit vos réponses et on revient vite vers vous.” |
| Primary action | A direct infinitive or short invitation naming the next action. | 2–4 words | “Lancer le quiz”<br>“Racontez-nous.”<br>“Retour aux projets” |
| Proof label | Plain metric name; numerals do the expressive work. | 2–7 words | “Taux d’engagement moyen”<br>“Évolution de la communauté sur une année” |

**Words and phrasing to use:** humain; histoire; incarner; révéler; résonner; concret; sur-mesure; racontez-nous

**Avoid:** révolutionnaire sans preuve; solution 360°; leader incontesté; synergie disruptive; performance garantie

**Rules:**

- Choose one coherent metaphor for a product, then balance it with plain operational language.
- State what happens after the click, how little effort it takes and who responds.
- Let the headline make a point; reserve the paragraph for how and why.
- Use emoji as visual annotations, not as replacements for meaningful action labels.

## Do's and Don'ts

### Do

- Keep the 94px chapter title visibly larger than the 16px explanatory paragraph.
- Alternate 25px-radius raspberry and forest process faces rather than inventing a new color for every step.
- Keep outer desktop margins at 30px and main scaffold gutters at 15px.
- Use 60px padding for central process and proof panels, but 30px for smaller benefit cards.
- Keep media tall and tactile, around a 450×680px silhouette in the central stage.
- Preserve fixed 60px corner controls instead of spending the top edge on a full navbar.
- Give a monumental statement 230.4px type at the desktop reference width and preserve its fluid 16vw rule.
- Use the overlapping contact-card and giant-word ending on a new marketing page.

### Don't

- Do not replace the condensed 900-weight poster face with a neutral medium-weight sans.
- Do not spread display lines to 1.2 line height; the compressed 0.7 rhythm is central.
- Do not add drop shadows to make overlapping cards legible; use rotation, silhouette and contrasting fills.
- Do not make every action a 9999px pill: main text buttons and tags have 10px corners.
- Do not turn all content into a three-column grid of white cards; the solid-color stage is the organizing surface.
- Do not apply heavy duotone filters to the warm natural photographs.
- Do not promote 12px capability tags into large badges that compete with the story name.
- Do not append the marketing contact/word footer to case-study endings; their circular exploration stage is a distinct variant.

## Motion and responsive

### Motion

**Observed:**

- Corner controls and media arrows declare transform 0.4s cubic-bezier(0.17, 0.67, 0.3, 1.33).
- Thought bubbles declare transform 0.4s cubic-bezier(0.23, 1, 0.32, 1); process faces declare background-color with the same duration and curve.
- Wordmark glyphs declare transform 1s cubic-bezier(.19,1,.22,1) with 0ms delay.
- Story progress elements declare opacity 0.4s cubic-bezier(0.23, 1, 0.32, 1).
- Sticky titles, portrait stacks, dealt process cards, rising benefit cards and full-field color changes form the scroll storytelling.

**Transfer:**

- Concentrate motion on dealing cards, passing stories and changing stage color while the chapter title remains anchored.
- Keep text controls crisp; use the elastic transform curve on the small circular controls, not on whole paragraphs.

**Unknown:**

- Complete scroll timelines, automatic story advance durations and all hover end states are unspecified.

### Responsive

**Observed:**

- CSS width boundaries include 767px, 768px, 960px, 961px, 1301px, 1601px and 2001px.
- Monumental type uses min(30rem, 16vw); the desktop scaffold uses 24 columns.

**Transfer:**

- On narrow screens, place a heading before its central portrait and explanatory copy; keep the portrait silhouette and color-paired display treatment.
- Let thought bubbles remain small adjacent annotations, and allow related circles to wrap rather than shrinking their labels to illegibility.
- Convert long sticky card performances into a readable vertical deck when a central portrait and side text cannot fit together.

**Unknown:**

- Exact mobile font sizes, insets, sticky offsets and card transforms are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
