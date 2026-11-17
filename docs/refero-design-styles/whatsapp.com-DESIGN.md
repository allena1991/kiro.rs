# WhatsApp — everyday closeness, vivid green

## Overview

A warm, people-first style that makes technical products feel familiar and emotionally useful. Cream expanses, deep blue-black chapters and fresh green accents surround relaxed regular-weight sans-serif typography. Candid photography and floating interface fragments do much of the storytelling, with low-density layouts giving each benefit its own breathing room.

### Essentials

- Big promises sound conversational rather than monumental: regular 400-weight sans-serif headlines at 80px/80px and section headings at 60px/60px, with normal tracking and short stacked lines.
- The opening is an inhabited scene, not an abstract product pedestal: a 1376px-wide, 720px-high photograph with 25px corners, white copy on the left and a translucent conversion panel on the right, inside 32px cream gutters.
- Actions feel like rounded everyday objects: 50px-radius pills with 1px dark outlines, green primary fills and trailing small directional icons; supporting links keep a green underline beneath just the words.
- Cream is the dominant canvas, not bright green: #fcf5eb carries most chapters, #111b21 provides a contrasting trust chapter and footer, #e6ffda carries the closing discovery band, and #25d366 is concentrated in actions and selected headline words.
- Human experience and product evidence overlap: tall interface panels around 325–339px wide and 629–654px high float directly on the canvas, with detached messages, photos or expressive stickers escaping their edges. Use an original lightweight workflow fragment over real human photography when full product media is unavailable.
- The ending has a soft lip rather than a hard cutoff: a pale-green horizontally overflowing card rail ends in 45px lower corners over a dark footer, with 48px circular navigation controls and a persistent green conversion action.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Fresh green | `#25d366` | `--color-green` | accent, action, text | Primary actions, short highlighted phrases and link underlines. Large saturated backings belong to device-promotion artwork, not the default canvas. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale green | `#e6ffda` | `--color-mint` | background, surface | Closing discovery rail and feature-exploration bands. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep blue-black | `#111b21` | `--color-night` | background, text, surface | Contrasting benefit chapters and shared footer; also dark text on green. |
| Charcoal text | `#1c1e21` | `--color-ink` | text, border, action | Main dark typography, thin button outlines and dark hover fills. |
| Dark green-gray edge | `#33463f` | `--color-dark-rule` | border | Footer divider and dark help-card outlines. |
| Muted gray | `#5e5e5e` | `--color-muted` | text | Small explanatory notes beneath the main photograph. |
| Warm cream | `#fcf5eb` | `--color-canvas` | background | Default marketing canvas and light navigation. |
| White | `#ffffff` | `--color-white` | text, surface, background | Text on dark fields and photography, editorial cards, input fields and light help bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark educational pages | Recessed blue-black | `#0b141a` | `--color-deep` | background, surface | Secondary resource and help bands within dark educational pages. |
| light help sections | Light cool rule | `#f0f4f9` | `--color-rule` | border | Subtle separators on white help lists. |

## Typography

- **WhatsApp Sans Var** — All marketing headings, paragraphs, controls and captions. Open, friendly sans-serif with a large x-height, soft curves and an unforced regular display weight. If unavailable, use **Inter**. Use 400 and 500; preserve open line breaks and normal tracking rather than tightening for drama. Font stack: "WhatsApp Sans Var", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | WhatsApp Sans Var | 400 | 80px | 1 | normal | Main photographic opening and dark educational opening. |
| heading | WhatsApp Sans Var | 400 | 60px | 1 | normal | Default benefit chapter and discovery-band headings. |
| statement | WhatsApp Sans Var | 400 | 48px | 1 | normal | Centered emotional statement and long-form connective headings. |
| card-title | WhatsApp Sans Var | 400 | 32px | 1 | normal | Editorial card titles; also the conversion-panel heading. |
| body | WhatsApp Sans Var | 400 | 18px | 25px | normal | Benefit descriptions, opening support and footer navigation links. |
| card-body | WhatsApp Sans Var | 400 | 16px | 22px | normal | Editorial card descriptions and compact supporting copy. |
| action | WhatsApp Sans Var | 500 | 16px | 1 | normal | Button labels, navigation and short action links. |
| footer-label | WhatsApp Sans Var | 400 | 12px | 1.3 | normal | Small sentence-case headings above footer link columns. |
| note | WhatsApp Sans Var | 400 | 12px | 16px | normal | Explanatory line beneath the opening media. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| focused feature landing pages | feature-display | WhatsApp Sans Var | 400 | 80px | 1.1 | normal | Text-led opening beside an oversized device demonstration. |
| focused feature and dark educational pages | feature-heading | WhatsApp Sans Var | 400 | 60px | 1.1 | normal | More open leading in feature chapters and dark discovery sections. |
| help, instruction and device-promotion sections | subheading | WhatsApp Sans Var | 400 | 24px | 1 | normal | Help questions, instructional grid titles and device-card captions. |
| interactive feature demonstrations | feature-tab | WhatsApp Sans Var | 400 | 24px | 1.25 | normal | Selectable capability titles in pale-green demonstration bands. |
| dark educational help sections | help-link | WhatsApp Sans Var | 500 | 18px | 25px | -0.03em | Single-line questions in dark outlined help cards. |

**Notes:**

- Display and section headings stay at weight 400; color and line breaks supply emphasis rather than bold weight.
- Normal tracking is the core rule even at 80px. The tighter help-link recipe is local to dark resource cards.
- Paragraphs retain a comfortable 25px line height beneath tightly stacked headings. Short action labels are denser at 16px/16px.

## Layout

**Density:** Airy: full-height benefit chapters surround compact paragraphs and controls with open cream space.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Primary section padding and many repeated vertical gaps; local text margins and pill padding use their own values.

| Value | Use |
| --- | --- |
| 8px | Tight supporting gaps. |
| 16px | Control clusters, small horizontal gaps and compact body separation. |
| 18px | Heading-to-paragraph separation and paragraph margins. |
| 24px | Container side padding and carousel card separation. |
| 32px | Outer opening inset, device-card padding and resource-card padding. |
| 34px | Default text-link separation after benefit copy. |
| 40px | Dark backing beneath the rounded closing band. |
| 50px | Download action separation on focused feature chapters. |
| 56px | Editorial card padding and centered-statement vertical padding. |
| 88px | Feature-section top padding and footer lower breathing room. |
| 96px | Default benefit-section and footer top padding. |
| 100px | Default benefit-section bottom padding. |

### Containers and grids

- **content**: max width 1080px · side padding 24px. Centered desktop content measure for benefit chapters; at 1440px the main content begins around 180px from the viewport edge.
- **opening-media**: max width 1376px · side padding 32px. Wide inset photograph; keep its inner copy and conversion panel aligned to the narrower content area.
- **benefit-pair**: 2 columns · gap 16px. One large media composition opposite a compact text block; alternate sides. Text measures are commonly 450px and media columns can occupy 528–540px.
- **footer**: max width 1050px · side padding 24px. Brand and conversion column beside four link columns, followed by a single divided utility row.
- **instruction-grid** (only for dark educational pages): 2 columns · gap 56px. Two rows of instructional cards with roughly 360px media widths and substantial open space between columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media-and-cards | 25px |
|  | pills | 50px |
|  | round-controls | 50% |
|  | closing-lip | 45px |
| photographic conversion openings | conversion-glass | 28.5px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default page background.

**CSS:** `background-color: #fcf5eb; color: #1c1e21`

**Observed:** A flat warm field connects the majority of benefit chapters.

**Transfer:** Let the surrounding canvas remain visible around media instead of enclosing every section in a card.

#### Night band · level 0

**Use:** High-contrast trust chapter and footer.

**CSS:** `background-color: #111b21; color: #ffffff`

**Observed:** Edge-to-edge dark color interrupts the cream flow; a selected word turns green.

**Transfer:** Use the same contrast shift for a consequential promise, reassurance or technical explanation.

#### Mint closing lip · level 0

**Use:** Discovery or editorial rail immediately above the dark footer.

**CSS:** `background-color: #e6ffda; border-radius: 0px 0px 45px 45px`

**Observed:** The light band curves down over dark backing, leaving a 40px dark join beneath its rounded bottom.

**Transfer:** Preserve the curved handoff even when the closing cards contain resources, integrations or use cases.

#### White editorial card · level 1

**Use:** Text-led editorial content in a horizontal rail.

**CSS:** `background-color: #ffffff; border-radius: 25px; box-shadow: none`

**Observed:** Opaque and flat against pale green or a recessed dark band.

**Transfer:** Use contrast and padding for elevation rather than decorative shadows.

#### Conversion glass · level 1

**Only for:** photographic conversion openings

**Use:** Short signup panel layered over people photography.

**CSS:** `background-color: rgba(0, 0, 0, 0.4); backdrop-filter: blur(17.8px); border-radius: 28.5px; color: #ffffff`

**Observed:** Warm brown, olive and blue-gray tones pass through from the photograph; this is not a uniform gray card.

**Transfer:** Keep the backdrop recognizable but softened enough for white labels.

#### Recessed resources · level 0

**Only for:** dark educational pages

**Use:** Editorial updates and help material below instructional chapters.

**CSS:** `background-color: #0b141a; color: #ffffff`

**Observed:** A modest darkening rather than a change to pure black.

**Transfer:** Separate supporting resources from primary chapters while maintaining the dark theme.

## Components

### Navigation

**Use:** Persistent global wayfinding and compact conversion actions.

**CSS:** `position: sticky; top: 0px; z-index: 1000; background-color: #fcf5eb; padding: 16px 60px; height: 80px; box-sizing: border-box`

**Text style:** `action` — WhatsApp Sans Var 500 · 16px/1

**Observed:** Brand mark sits left, short plain-text links span the center, and an outlined login pill plus green download pill sit right. Dropdown and external-link arrows are small. Dark educational pages use the Night band with white links.

**Transfer:** Keep labels brief so the header remains one calm row.

### Primary button

**Use:** Default conversion action in the navigation; larger variant in feature sections and footer.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background-color: #25d366; color: #1c1e21; border: 1px solid #1c1e21; border-radius: 50px; padding: 12px 20px; overflow: hidden`

**Text style:** `action` — WhatsApp Sans Var 500 · 16px/1

**Observed:** Label precedes a downward arrow. Navigation size is 145×45px; feature actions use 16px 28px padding and 161×53px boxes, while the footer uses 16px 32px padding and 169×53px boxes.

**States:** Declared: hover background-color #1c1e21, color #ffffff, text-decoration none.

**Transfer:** Use one concrete conversion verb and an appropriate directional glyph.

### Outline button

**Use:** Secondary editorial action inside white cards.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background-color: #ffffff; color: #1c1e21; border: 1px solid #1c1e21; border-radius: 50px; padding: 16px 28px`

**Text style:** `action` — WhatsApp Sans Var 500 · 16px/1

**Observed:** Compact standalone pill anchored near the card's bottom. Header login is a distinct smaller variant with a trailing chevron, 1.5px outline and 14px 20px padding.

**States:** Declared: hover background-color #1c1e21, color #ffffff, text-decoration none.

### Underlined text link

**Use:** Low-pressure secondary action after benefit copy.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; color: #1c1e21`

**Text style:** `action` — WhatsApp Sans Var 500 · 16px/1

**Observed:** Only the words have a thin green underline; a small separated right chevron or external arrow sits after the label. Reverse the text to white on Night band.

**States:** Declared: hover color #00803e, text-decoration none.

**Transfer:** Construct the underline on a label span, not across the trailing icon.

### Editorial card

**Use:** News or resource summaries in an overflowing rail.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; background-color: #ffffff; border-radius: 25px; padding: 56px; width: 504px; min-height: 497px; box-sizing: border-box; overflow: hidden`

**Text style:** `card-title` — WhatsApp Sans Var 400 · 32px/1

**Observed:** A small outline brand icon starts the card, followed by the title, card-body copy and an Outline button. Adjacent cards are separated by 24px and the next one is intentionally partially visible.

**Transfer:** Use a modest product mark or topic symbol above the title; maintain the card's text-first hierarchy.

### Carousel control

**Use:** Paired previous and next controls beneath rail introductions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; width: 48px; height: 48px; border: 1px solid #1c1e21; border-radius: 50%; position: relative; overflow: hidden`

**Observed:** Small 7×12px chevrons are centered in circles separated by 16px. The unavailable previous direction is faded to opacity 0.4. Dark rails reverse outlines and icons to white.

**States:** Declared: hover color #ffffff for light-background controls.

### Footer

**Use:** Global ending with a clear conversion path and navigation.

**CSS:** `background-color: #111b21; color: #ffffff; padding-top: 96px`

**Text style:** `body` — WhatsApp Sans Var 400 · 18px/25px

**Observed:** Brand and green action form the left column, with four link columns to the right. Column labels use footer-label above spacious 18px/25px links. The 530px-tall desktop footer ends in a 1050px-wide utility row with a #33463f top rule, 32px vertical padding, legal links, five 48px outlined social circles at 24px gaps and a language pill.

**Transfer:** Use only useful categories; preserve the conversion column and separated utility row.

### Conversion panel

**Only for:** photographic conversion openings

**Use:** A short signup task within the main scene.

**CSS:** `background-color: rgba(0, 0, 0, 0.4); backdrop-filter: blur(17.8px); border-radius: 28.5px; width: 396px; color: #ffffff`

**Text style:** `card-title` — WhatsApp Sans Var 400 · 32px/1

**Observed:** Centered heading and field instruction lead into a white pill input, full-width action and existing-user login link. The panel occupies roughly 390px of height. Fine print stays subordinate, not a second marketing paragraph.

**Transfer:** Replace the phone task with a single relevant entry field or compact conversion task; retain the same visual balance.

### Light FAQ row

**Only for:** light feature-page help sections

**Use:** Compact expandable question list below a help heading.

**CSS:** `background-color: #ffffff; border-bottom: 1px solid #f0f4f9; padding: 1px 6px 1px 0px; width: 100%; position: relative`

**Text style:** `subheading` — WhatsApp Sans Var 400 · 24px/1

**Observed:** A leading chevron precedes the question, with 40px left inset for the heading and 16px vertical heading padding. Rows span 1080px on desktop; the enclosing item also carries a 2px light separator.

### Dark help card

**Only for:** dark educational help sections

**Use:** Direct links to help topics rather than compact accordion rows.

**CSS:** `background-color: #0b141a; border: 1px solid #33463f; border-radius: 25px; width: 100%`

**Text style:** `help-link` — WhatsApp Sans Var 500 · 18px/25px · tracking -0.03em

**Observed:** A full-width 1080×102px outlined card contains a text link and a small circled external arrow at the far right. The inner link has 32px padding, and cards are separated by 32px.

**Transfer:** Keep each card to one question and one clear destination.

## Imagery and graphics

### Inhabited opening photograph

**Use:** Primary emotional context in the wide opening.

**Observed:** A candid person looking at a phone fills the scene, warmly backlit outdoors with soft bokeh and dark foliage. The subject sits near the center, leaving darker space for left white type and enough visual texture for glass at right. Color remains photographic rather than monochrome.

**Transfer:** Photograph a real moment in which the new product is useful. If location photography is unavailable, use a high-quality environmental portrait with authentic activity and strong negative space; add original interface fragments to show the product's role.

### Floating interface collage

**Use:** Signature product storytelling across the opening and benefit chapters.

**Observed:** White and pale-green message bubbles overlap the photo; below, tall rounded screens carry real faces, photos or everyday tasks. Small reactions, stickers and photo cards extend outside the device rectangle. The main screen is usually about 325px wide and 647px high, opposite a compact text column.

**Transfer:** Use the new product's recognizable workflow and real content, not a generic empty dashboard. Include at least one detached meaningful notification, output card or human detail in the composition.

**Build:** Layer a rounded 25px product panel or tall image on a transparent stage; place two small white and pale-green rounded output cards just beyond opposite edges. Add a small circular avatar or expressive reaction near one output. Keep large backings flat cream; use intrinsic media shadowing only, not a raised marketing card around the entire collage.

### Dark technical reveal

**Use:** Signature high-contrast product explanation within a Night band.

**Observed:** A tall dark interface overlaps a wider rounded near-black field. Large luminous green text cuts horizontally across the middle, with symbols fading toward the edges; the interface texture remains subtle. The media takes roughly half the centered chapter width, beside a short white-and-green heading.

**Transfer:** Replace cipher text with a meaningful product operation or result, retaining the layered dark interface and one vivid green line.

**Build:** Within a roughly 528px-wide transparent stage, place a wide rgba(0,0,0,0.25) rounded rectangle behind a narrower tall dark interface. Overlay a clipped horizontal green text strip at mid-height, fading its edges with a transparent-to-opaque-to-transparent mask. Use thin low-opacity line motifs inside the interface instead of elaborate illustration when original art is unavailable.

### Device promotion artwork

**Only for:** device-promotion sections

**Use:** More literal cross-device demonstrations and platform cards.

**Observed:** Phones tilt and overlap in feature chapters; laptop and phone pairs sit directly on pale green. Device carousel artwork places a tablet or laptop on a saturated green upper panel, above a white caption area; the artwork occupies 504×367px above the text.

**Transfer:** Show actual supported form factors with legible screen silhouettes. Keep strong green confined to the media backing, not the surrounding cream chapter.

### Dark educational portrait and instruction tiles

**Only for:** dark educational pages

**Use:** Humanize a technical topic and show practical steps.

**Observed:** A tall rounded bedroom portrait uses cool teal bedding and warm lamplight, with pale-green message cards above and white messages plus an emoji below. Instruction tiles use enlarged rounded interface details about 360×264px, sitting directly on dark backgrounds rather than inside outer cards.

**Transfer:** Use a reassuring ordinary environment, then isolate the few interface details that explain the action. Keep all surrounding type white with short green highlights.

### Icons

**Observed:** Mostly simple monochrome SVG arrows, chevrons, download glyphs and recognizable social symbols. Inline icon boxes commonly measure 29×15–16px including separation; the visible chevron can be only 7×12px. Rail and social icons sit within 48px outlined circles.

**Transfer:** Choose lightweight filled or fine-outline utility glyphs, aligned after text except for the leading help chevron. Match the text color rather than introducing another accent palette.

## Section recipes

How recurring sections are built.

### First screen: Photographic conversion opening

**Observed:** An 80px sticky Navigation precedes cream padding and a wide photograph inset 32px on each side, beginning 32px below the header. The image is 1376×720px at a 1440px viewport, with 25px corners. Back-to-front layers are environmental photography, floating message fragments, a left white headline and support block, and a right Conversion panel. The headline occupies roughly 403px of width in two 80px/80px lines, leaving the person's face prominent near the center. Support sits 18px below it; small product messages occupy the area underneath. The glass task panel is about 396×390px and vertically balanced against the left copy. Within the first 900px, the header, complete image, headline, support, input/action/login task and small right-aligned note are visible; the next product chapter starts below.

**Transfer:** For a new landing page, use an original inhabited photograph, benefit headline and concise conversion task over the image. If a signup task is inappropriate, put a compact action group in the same softened right-hand panel. Focused feature pages instead open on cream with an 80px/88px headline beside an oversized tall device; dark educational pages use a white-and-green 80px/80px headline beside a portrait collage on Night band.

**Avoid:** Do not center a headline over a generic gradient, cover the face with text, or replace the right-hand task with a grid of unrelated features.

**Text style:** `display` — WhatsApp Sans Var 400 · 80px/1

### Centered emotional bridge

**Observed:** A 900px-wide centered statement uses statement type with 56px vertical padding. It is a single flowing thought rather than a headline plus paragraph.

**Transfer:** Use a human outcome to bridge the opening demonstration and specific capabilities; let the thought wrap across several balanced lines.

**Text style:** `statement` — WhatsApp Sans Var 400 · 48px/1

### Alternating benefit pair

**Observed:** Inside the content layout, one dominant floating interface composition sits opposite a roughly 450px text block. Heading is followed by body copy at 18px separation and an Underlined text link about 34px after the copy. Default top and bottom space are 96px and 100px; media often reaches about 647px tall. The opposite side is used in the next chapter.

**Transfer:** Give each section one benefit and one demonstration; vary media placement without changing typography or packing multiple cards around it.

**Text style:** `heading` — WhatsApp Sans Var 400 · 60px/1

### Dark assurance chapter

**Observed:** Night band carries the Dark technical reveal on one side and a compact heading, explanatory paragraph and white Underlined text link on the other. One important word is green, still weight 400. Desktop section height is about 846px with 96px top and 100px bottom breathing room.

**Transfer:** Use for an important reassurance or invisible capability, not necessarily security; keep the green phrase short.

**Text style:** `heading` — WhatsApp Sans Var 400 · 60px/1

### Editorial closing rail

**Observed:** Mint closing lip holds a left introduction with a 60px heading, body support and Carousel controls anchored lower, while 504×497px Editorial cards overflow horizontally on the right. Top padding is 96px. The rounded lower edge hands off to Footer rather than another cream chapter.

**Transfer:** Make this the closing discovery device using relevant resources, release stories or adjacent use cases. The rail can appear elsewhere too; keep its partially visible next card.

**Text style:** `heading` — WhatsApp Sans Var 400 · 60px/1

### Conversion and directory ending

**Observed:** Footer closes every page with a brand/action column and four link groups, followed by its thin-rule utility row. It is not a giant final headline or an isolated centered CTA.

**Transfer:** Let the final discovery content blend into a useful directory with a persistent conversion action.

### Selectable demonstration band

**Only for:** focused feature landing pages

**Observed:** A pale-green band pairs a capability list on the left with a device composition on the right. The selected 24px/30px title expands into 18px/25px copy and a small download link; inactive titles sit in roughly 90px rows separated by thin rules. A thin green progress segment and small pause control accompany the active item.

**Transfer:** Use when related capabilities share one demonstration area; keep the selected explanation clearly larger than its collapsed siblings.

**Text style:** `feature-tab` — WhatsApp Sans Var 400 · 24px/1.25

### Instructional reassurance

**Only for:** dark educational pages

**Observed:** A centered 48px/48px heading highlights one green word, with centered body support underneath. A two-column Instruction grid follows, each item consisting of enlarged interface detail, 24px title, 18px/25px explanation and Underlined text link. Further short 60px chapters alternate supporting illustrations with action-led explanations.

**Transfer:** Convert an intimidating subject into a few practical steps and concise recovery paths.

**Text style:** `statement` — WhatsApp Sans Var 400 · 48px/1

### Help and adjacent discovery

**Only for:** focused feature and dark educational pages

**Observed:** A help heading pairs with a small all-questions link. Light feature pages use Light FAQ rows on white, then a pale-green rail of 328×248px photographs above 32px titles and links. Dark educational pages use Recessed resources with Dark help cards, then a Night band discovery rail before the shared Footer. Discovery imagery may share the page canvas rather than sit in white cards.

**Transfer:** Resolve practical objections, then offer adjacent paths without repeating the opening sales pitch.

**Text style:** `heading` — WhatsApp Sans Var 400 · 60px/1

## Page flow

**Storyline:** Human promise → concrete product demonstration → benefit chapters and reassurance → useful resources or help → adjacent discovery → conversion and directory.

### Broad marketing landing page

1. **Promise and conversion** — Wide human photograph, short white headline and integrated glass signup task.
2. **Product demonstration** — A newly useful capability gets a large interface example and short explanatory heading.
3. **Emotional framing** — Centered outcome statement bridges into the product story.
4. **Capability chapters** — Alternating cream pairs with a contrasting dark reassurance chapter and detached interface details.
5. **Freshness and discovery** — Pale-green editorial rail with white text-led cards and circular controls.
6. **Final action and directory** — Shared dark footer retains a green action beside navigation columns.

**Transfer:** Use this as the default broad landing-page model; preserve human context, product fragments, a dark contrast moment and the curved discovery-to-footer handoff without fixing the number of chapters.

### Focused feature landing page

1. **Focused promise** — Cream two-column opening with large headline and oversized device evidence.
2. **Capability explanation** — Alternating simple feature pairs and pale-green selectable demonstrations.
3. **Availability** — Device cards with saturated green artwork backings in a horizontal rail.
4. **Objection handling** — White help heading and thin-rule expandable question list.
5. **Adjacent discovery** — Pale-green related-feature rail with photographic thumbnails.
6. **Final action and directory** — Shared dark footer and utility strip.

**Transfer:** Choose one capability, show it in several real situations and answer practical questions before offering adjacent paths.

### Dark educational or reassurance page

1. **Reassurance** — White-and-green headline beside a human portrait and floating interface details on a deep field.
2. **Principles** — Centered connective statement and three short assurance columns.
3. **Practical guidance** — Two-column instructional interface tiles followed by alternating action-led chapters.
4. **Updates** — White editorial cards over a slightly deeper dark resource band.
5. **Objection handling** — Outlined dark help cards spanning the content measure.
6. **Adjacent discovery** — Dark related-feature rail flowing into the shared footer.

**Transfer:** Keep the visual identity but switch the dominant canvas to dark for a sustained explanatory subject; use specific helpful actions rather than fear-based messaging.

## Writing

Warm, direct and reassuring. Product capabilities are explained through everyday relationships and useful actions rather than technical spectacle.

**Do not copy:** Do not reuse the WhatsApp name, marks, interface artwork, distinctive stickers, source customer conversations, proprietary claims, security guarantees, availability claims or numerical limits. Source quotations are voice examples, not copy for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your. Use we for a concrete commitment or explanation, and name the product when clarity requires it.
- **Rhythm:** Short conversational headlines, usually two to eight words, lead into one compact paragraph. Imperatives are gentle and specific; longer explanatory sentences are broken by ordinary examples.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A plain verb or human outcome, without a slogan preamble. | 2–7 words | “Message privately”<br>“Connection is a call away” |
| Benefit heading | Name what the person gets to do or feel. | 3–10 words | “Keep in touch with your groups”<br>“Say what you feel” |
| Support paragraph | Explain with recognizable daily situations, then name the enabling capability. | 1–3 compact sentences | “From a group call to classmates to a quick call with mom, feel like you’re in the same room with voice and video calls.” |
| Action | Use a familiar verb; reserve explanation for nearby copy. | 1–3 words | “Try it”<br>“Learn more”<br>“Download” |
| Help question | Use the reader's practical question as the link itself. | 6–12 words | “How do I protect my [Brand] account?” |

**Words and phrasing to use:** you; your; stay connected; feel close; simple; reliable; everyday moments; help; keep; share

**Avoid:** revolutionary; disruptive; unparalleled; unlock your potential; enterprise-grade synergy; fear-heavy warnings

**Rules:**

- Lead with the person's outcome before explaining the mechanism.
- Use concrete everyday examples instead of sweeping lifestyle claims.
- Make reassurance specific and supportable; place conditions in a small note close to the relevant statement.
- Keep section headings sentence case and let one word carry emphasis through color, not shouting.
- Treat help copy as a service to the reader, not another promotional pitch.

## Do's and Don'ts

### Do

- Keep default display and benefit type at weight 400 with normal tracking.
- Use 80px/80px for the main photographic promise and 60px/60px for benefit chapters.
- Keep the desktop content measure at 1080px and the wide photographic opening inset by 32px.
- Use cream for the main journey, one meaningful blue-black contrast chapter and pale green for closing discovery.
- Pair 18px/25px supporting text with compact 16px/16px actions.
- Preserve 25px media corners, 50px pill radii and 48px circular rail controls.
- Let product fragments overlap their media edges while leaving surrounding text uncluttered.
- Carry the closing band's 45px lower corners into the dark footer handoff.

### Don't

- Do not use bold 700-weight hero typography or aggressively negative tracking; the regular open letterforms provide the character.
- Do not replace the warm #fcf5eb canvas with a pure-white page throughout.
- Do not spread saturated #25d366 across every section; broad marketing color fields are cream, pale green or blue-black.
- Do not apply a drop-shadow system to marketing cards; their flat white fill and generous padding separate them.
- Do not shrink the editorial rail into a dense three-column grid of small text cards; retain its 504px card scale and horizontal continuation.
- Do not underline an entire action including its arrow; the green line belongs beneath the words.
- Do not style dark resource links as the 24px light accordion; they use 18px medium-weight text inside rounded outlined panels.
- Do not import the 24px/30px selectable demonstration titles into the main benefit heading role.

## Motion and responsive

### Motion

**Observed:**

- Pill actions declare color 0.33s linear 0.5s, border-color 0.5s ease-out and background-color 0.33s linear transitions, with circular dark pseudo-element fills.
- Navigation declares background-color 0.33s ease-out and color 0.33s ease-out.
- Help chevrons declare transform 0.48s ease-in-out.
- Selectable demonstration bands include progress and pause controls.

**Transfer:**

- Retain the dark-fill/white-label contrast change on green and outlined pills.
- If using an automatically cycling capability demonstration, pair its progress indication with a visible pause control.

**Unknown:**

- Actual entrance-animation sequencing, scroll choreography and runtime durations for illustration loops are unknown.

### Responsive

**Observed:**

- Desktop uses an 80px sticky header and two-column centered sections. CSS contains breakpoint families around 640px, 768px and 1024px, among numerous component-specific widths.

**Transfer:**

- On narrow layouts, stack the benefit copy and its media while preserving detached fragments around a single dominant panel.
- Adapt the photographic opening into a readable scene plus conversion task rather than compressing both desktop columns across the subject's face.
- Keep rails horizontally navigable and retain the rounded closing-to-footer handoff.

**Unknown:**

- Mobile type sizes, navigation behavior, stacking order and exact breakpoint-specific spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
