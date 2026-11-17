# Koto — cinema meets studio index

## Overview

A dark, editorial identity with the confidence of a creative studio and the scale of a film screen. Light condensed grotesk headlines sit beside tiny monospaced labels, while photography, moving image and vivid graphic work carry the emotion. Almost-black and grey framing makes small flashes of acid yellow feel electric; content is locally compact but surrounded by unusually expansive pauses. It suits design-led products, ambitious services and culture-rich organizations.

### Essentials

- Cinema first, proposition second: a full-bleed 1440×900 media stage carries a two-line, bottom-left 48px/1 condensed introduction at weight 300; longer explanation starts below the fold.
- Headings sound like a sentence changing emphasis: white lead phrases run into #989898 continuation text, both at 38px/1.1 with -0.01em tracking, rather than separate oversized slogan and subtitle tiers.
- The interface behaves like a studio index: 11px/1 uppercase mono labels, bracketed links and 1px white-at-10% rules organize the work without competing with it.
- Color belongs to the work, not the furniture: #060606 dominates the reading canvas, #141414 holds restrained controls, and #ffe800 is a tiny identity accent. Vivid color can fill individual media frames, never whole text sections.
- Asymmetry stages the proof: a 16-column grid with 8px gutters pushes 877×493 work films into the right side, while news uses one 599px image beside two 381px images. Include a strong media stage even without films, using a tightly framed photograph or product-detail sequence.
- Actions are small instrument panels, not pills: 2px corners, 16px padding, 45px height, translucent white-at-5% fill and 11px mono text with an outgoing arrow.
- A human-scale closing device anchors the black space: retain an image-led contact or work-preview tile near the lower left and a spare right-side closing message or ruled contact directory; legal links stay at 14px in #595959.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#ffe800` | `--color-accent` | accent | Tiny identity mark; larger luminous yellow treatments are confined to graphic media. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control wash | `#121212` | `--color-control` | surface, action | Visible white-at-5% over near black; understated action backgrounds. |
| Near black | `#060606` | `--color-canvas` | background | Continuous reading canvas. |
| Off black | `#141414` | `--color-panel` | surface | Compact navigation backing and media backing. |
| Subtle edge | `#1f1f1f` | `--color-rule` | border, surface | Visible white-at-10% over near black; section rules and category tags use the alpha recipe. |
| Deep grey | `#595959` | `--color-muted` | text, accent | Legal links, inactive names and tiny status dots. |
| Mid grey | `#989898` | `--color-secondary` | text | Heading continuations, descriptions, dates and secondary links. |
| White | `#ffffff` | `--color-primary` | text, link | Primary headings, active labels and action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| partner proof sections | Partner tile | `#0e0e0e` | `--color-partner` | surface | Visible rgba(18,18,18,0.7) over near black. |
| capability detail chapters | Capability grey | `#c1c1c1` | `--color-capability-text` | text | Light grey capability explanation; keep the ordinary heading continuation mid grey. |

## Typography

- **gtKotoheimCondensed** — Introductions, section statements, closing messages and quotations. Narrow, light grotesk with tall compact letterforms and an informal editorial feel. OpenType features: "salt". If unavailable, use **Barlow Condensed**. Use weight 300; retain the narrow proportions and restrained headline size. Font stack: "gtKotoheimCondensed", "Barlow Condensed", sans-serif.
- **gtKotoheim** — Body copy, news titles, lists and directory text. Plainspoken grotesk with a light regular weight. OpenType features: "salt". If unavailable, use **Inter**. Use variable weight 350 where available. Font stack: "gtKotoheim", "Inter", sans-serif.
- **gtKotoheimMono** — Navigation labels, section markings, category chips and dates. Small utilitarian monospace; compact uppercase labels without exaggerated letterspacing. OpenType features: "salt". If unavailable, use **IBM Plex Mono**. Font stack: "gtKotoheimMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | gtKotoheimCondensed | 300 | 48px | 1 | -0.01em | Two-line introduction over opening media. |
| statement | gtKotoheimCondensed | 300 | 38px | 1.1 | -0.01em | Main explanatory statements, paired section headings and closing copy. |
| body | gtKotoheim | 350 | 16px | 1.25 | normal | News titles, capability lists and place names. |
| small-body | gtKotoheim | 350 | 14px | 1.25 | normal | Descriptions and secondary text links. |
| metadata | gtKotoheimMono | 400 | 12px | 1.2 | normal | Dates and multiline addresses. |
| label | gtKotoheimMono | 400 | 11px | 1 | normal, uppercase | Section labels, navigation, buttons and chips. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| capability detail chapters | capability | gtKotoheimCondensed | 300 | 32px | 1.15 | normal | Capability chapter names and explanations. |
| partner proof sections | quote | gtKotoheimCondensed | 300 | 24px | 1.2 | normal | Long testimonial next to project artwork. |
| culture and principles sections | value-title | gtKotoheim | 350 | 13px | 1.25 | normal | Short title beside explanatory copy beneath graphic cards. |

**Notes:**

- Headline weight stays 300; hierarchy comes from placement and contrast rather than boldness.
- Use -0.01em tracking at 38px and 48px, but normal tracking on 32px capability text and all smaller copy.
- White and mid-grey phrases can share one statement size. Small uppercase mono belongs to navigation and labels, not prose.

## Layout

**Density:** Airy overall, with compact reading clusters and long black intervals between them.

### Spacing

| Value | Use |
| --- | --- |
| 6px | News title to description. |
| 8px | Primary grid gutter and small tag padding. |
| 12px | Media-to-title gap, metadata gap and three-card gutter. |
| 16px | Outer media margin and main action padding. |
| 24px | Rule-header vertical padding and closing-copy-to-action gap. |
| 36px | Header-to-grid spacing and legal link gap. |
| 48px | Separated content groups and capability text-to-list gap. |
| 64px | Location row bottom padding and proof section group gaps. |
| 96px | News section top padding. |
| 108px | Capability chapter bottom padding. |
| 120px | Major closing block inner top spacing and culture section bottom padding. |
| 172px | Contact directory top spacing. |

### Containers and grids

- **desktop scaffold**: 16 columns · gap 8px · side padding 16px. Fluid edge-to-edge grid, 1408px wide at 1440px. Text receives an additional 12px inset for a 28px visual edge.
- **right media rail**: max width 877px. Work films occupy roughly the right ten columns at desktop; keep the left side available for a short statement or deliberate open space.
- **news grid**: 3 columns · gap 12px. Unequal columns: 599px lead and two 381px supporting cards at desktop, aligned at the image tops.
- **culture grid** (only for culture and principles sections): 3 columns · gap 12px. Three equal 453px-wide graphic cards within the inset text edges.
- **location grid** (only for location directories): 2 columns · gap 8px. Two 561px-wide photos to the right of a narrow region selector; natural 4:3 frames.

## Corner radius

| Element | Radius |
| --- | --- |
| action and tag | 2px |
| navigation panel | 4px |
| media and proof tiles | 6px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** All reading sections and negative space.

**CSS:** `background: #060606; color: #ffffff`

#### Navigation backing · level 2

**Use:** Collapsed fixed navigation.

**CSS:** `background: #141414; border-radius: 4px`

#### Ruled content

**Use:** Section headers, capability lists and contact directory rows.

**CSS:** `border-top: 1px solid rgba(255,255,255,0.1); box-shadow: none`

**Observed:** Only a top hairline; no enclosed card border.

**Transfer:** Separate editorial groups with a line rather than a box.

#### Glass action · level 1

**Use:** Subtle conversion controls.

**CSS:** `background: rgba(255,255,255,0.05); border-radius: 2px; backdrop-filter: blur(40px)`

#### Partner tile · level 1

**Only for:** partner proof sections

**Use:** Low-contrast monochrome logo grid.

**CSS:** `background: rgba(18,18,18,0.7); border-radius: 6px`

**Observed:** A six-across row with centered grey marks and no shadows.

## Components

### Navigation panel

**Use:** Persistent compact site identity and section control.

**CSS:** `position: fixed; top: 16px; left: 16px; height: 48px; background: #141414; border-radius: 4px`

**Text style:** `label` — gtKotoheimMono 400 · 11px/1 · uppercase

**Observed:** Yellow identity at left, current section label beside it, tiny dot at the end. On the media opening the navigation expands into an unboxed horizontal list; a small UTC clock and grid-like utility mark sit at the far right.

**Transfer:** Keep identity compact and preserve the contrast between expanded opening navigation and collapsed reading navigation.

### Primary action

**Use:** Closing conversion or recruitment action.

**CSS:** `padding: 16px; height: 45px; background: rgba(255,255,255,0.05); color: #ffffff; border-radius: 2px; backdrop-filter: blur(40px); display: inline-flex; align-items: center`

**Text style:** `label` — gtKotoheimMono 400 · 11px/1 · uppercase

**Observed:** Content-width rectangular control, with a small diagonal outgoing arrow after the label.

**Transfer:** Use one direct verb-led destination rather than a row of competing conversions.

### Category tag

**Use:** Small category marker beside a date under editorial cards.

**CSS:** `padding: 8px; height: 27px; background: rgba(255,255,255,0.1); border-radius: 2px; backdrop-filter: blur(40px); color: #ffffff`

**Text style:** `label` — gtKotoheimMono 400 · 11px/1 · uppercase

**Observed:** Compact label followed by unboxed metadata, separated by 12px.

### Section index header

**Use:** Mark the beginning of a chapter or news group.

**CSS:** `border-top: 1px solid rgba(255,255,255,0.1); padding: 24px 0px; display: flex; justify-content: space-between`

**Text style:** `label` — gtKotoheimMono 400 · 11px/1 · uppercase

**Observed:** White chapter name and grey explanatory label share the left edge; a bracketed view-all link sits at the far right.

### News card

**Use:** Editorial proof and recent activity.

**CSS:** `background: transparent; color: #ffffff; display: flex; flex-direction: column; gap: 12px`

**Text style:** `body` — gtKotoheim 350 · 16px/1.25

**Observed:** 16:9 media above a small title; the lead card also has grey two-line description, with a 6px title-to-description gap. Category tag and date finish the card. No enclosing panel or shadow.

**Transfer:** Let the lead article be physically larger, not typographically louder.

### Legal link row

**Use:** Final low-emphasis utility navigation.

**CSS:** `display: flex; gap: 36px; color: #595959`

**Text style:** `small-body` — gtKotoheim 350 · 14px/1.25

**Observed:** Copyright and legal links align to the right-side content grid in a 108px-tall footer. A small utility icon finishes the far edge.

**Transfer:** Keep the footer sparse rather than building a conventional multi-column sitemap.

### Capability row

**Only for:** capability detail chapters

**Use:** List concrete deliverables beneath a capability explanation.

**CSS:** `border-top: 1px solid rgba(255,255,255,0.1); padding-bottom: 4px; height: 45px`

**Text style:** `body` — gtKotoheim 350 · 16px/1.25

**Observed:** Single-line text in an inner block with 8px top and 12px bottom padding; repeated rows form a narrow right-hand list.

### Partner logo tile

**Only for:** partner proof sections

**Use:** Repeated visual credibility markers.

**CSS:** `background: rgba(18,18,18,0.7); border-radius: 6px; width: 226px; height: 266px; display: flex; align-items: center; justify-content: center`

**Observed:** Six tiles across with 8px gaps. Grey logos are centered with abundant room around them.

**Transfer:** Normalize optical size, not logo bounding-box width.

## Imagery and graphics

### Cinematic media stage

**Use:** Required emotional anchor for the opening and selected proof sections.

**Observed:** Full-bleed opening film shows an extreme close architectural form, pale cool blue-grey against an off-white sky, with soft grain and monumental vertical cropping. Subsequent project films are large right-aligned 16:9 frames and may be saturated. Typography is secondary to the imagery.

**Transfer:** Use an atmospheric close-up of the product, its materials or its real environment. Without a film, use one excellent full-bleed photograph and a second tight detail view; retain the huge scale and low density.

### Editorial photography

**Use:** News and supporting human proof.

**Observed:** Mix of black-and-white portraiture, naturally lit group photographs and colorful identity work. All share simple landscape framing; subjects, not decorative UI, supply the color.

**Transfer:** Use real people and actual work. Keep portraits conversational, not glossy corporate headshots.

### Contact preview tile

**Use:** Required small image-led anchor within the closing area.

**Observed:** A warm office interior appears as a compact lower-left landscape tile with softly rounded corners, a dark bottom fade, tiny uppercase contact text and a copy control. A culture-oriented ending instead uses a smaller dark work-preview tile.

**Transfer:** Show a real workspace, product-in-use or focused work detail. Keep it small enough that the surrounding black area remains the dominant closing material.

### Luminous principles

**Only for:** culture and principles sections

**Use:** Three distinct abstract images that turn intangible ideas into visual experiences.

**Observed:** Black 4:3 frames contain soft yellow light: one pool emerging from below, several blurred circles partly cut by the edges, and a bright central point fading to an olive-yellow halo. Images are 453×340px with 6px corners; captions split into a narrow name column and wider paragraph.

**Transfer:** Use one family of luminous forms with three variations. Match the soft glow; exact stops are not essential.

**Build:** On a black SVG rectangle, layer circles filled acid yellow with 0.3–0.9 opacity. Use Gaussian blurs of 18–45px, a smaller bright core and larger dim halo. Place one circle below the lower edge, three circles partly outside corners in the second frame, and concentric centered circles in the third. Clip to the 4:3 frame.

### Printed collage banner

**Only for:** culture introductions

**Use:** Wide graphic contrast below a spare text introduction.

**Observed:** A shallow banner is packed with overlapping printed stickers and card shapes: acid yellow, cream, red, brown and black; rough illustrative linework, rotated rectangles and cropped symbols create a tactile studio-wall feeling.

**Transfer:** Create original paper ephemera reflecting the new product's culture, not an unrelated decorative sticker pack.

**Build:** Use an SVG banner clipped to a 6px rounded rectangle. Overlap 8–12 rotated rectangular and die-cut shapes, about 180–400px wide, extending outside the frame. Give each a flat warm paper color and one rough black or red line illustration. Avoid shadows and glossy gradients.

### Place photography

**Only for:** location directories

**Use:** Ground organizational reach in physical places.

**Observed:** Warm, naturally lit 4:3 interiors and straightforward exterior architecture; 561×421px images appear in pairs, with small place names and mono addresses underneath.

**Transfer:** Photograph real environments with visible tools, furniture and ordinary detail; preserve warmth against the black canvas.

### Icons

**Observed:** Tiny 10px utility glyphs and arrows, thin 1px strokes; media controls use 24px outlines at 1.3px with butt caps. Most are white or grey, never multicolor.

**Transfer:** Use simple outgoing arrows, directional controls and copy glyphs; reserve icons for actual operations rather than decorating each paragraph.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** A 900px-tall full-bleed Cinematic media stage fills the first screen. Back to front: near-black fallback, edge-covering film, exclusion-blended introduction at the lower left, then small top navigation and far-right clock. The 48px/1 light condensed headline is two modest lines rather than a giant central slogan: identity in white, descriptor in grey. It occupies the left third, with a 28px text edge and about 24px of breathing room beneath it. There is no prominent conversion button; only a tiny playback control at lower right. The first 900px shows film, navigation and introduction; the 38px explanation and right-aligned project rail begin below it.

**Transfer:** Make the new product feel tangible through a cinematic full-screen image or film, then give a short identity-and-category introduction. Detail-oriented page types instead open on black: a 38px title at left, same-size grey explanatory paragraph beginning around the right half, a small jump-link row beneath, then a shallow wide media strip.

**Avoid:** Do not replace the media stage with a centered SaaS headline, two pill CTAs and a floating dashboard. Do not turn the modest bottom-left title into giant lettering across the image.

**Text style:** `display` — gtKotoheimCondensed 300 · 48px/1 · tracking -0.01em

### Two-tone statement

**Observed:** Section index header precedes a left-aligned 38px statement by roughly 120px. A short white lead phrase is immediately followed by grey continuation text at the same size and weight, typically spanning about half the desktop width.

**Transfer:** Use a terse topic and a concrete one-sentence explanation as one continuous typographic thought.

**Text style:** `statement` — gtKotoheimCondensed 300 · 38px/1.1 · tracking -0.01em

### Offset project rail

**Observed:** 877×493px landscape films align to the right ten columns, separated by about 12px. A short statement near the left edge introduces the proof; the work remains larger than its labels.

**Transfer:** Use a sequence of product demonstrations, editorial case images or real-use scenes; preserve the offset rather than making a uniform centered card grid.

### Unequal news group

**Observed:** Section index header and a bracketed view-all action lead into the unequal news grid. The first News card has the widest media and an excerpt; the other two are smaller and title-led. The section uses 96px top padding and substantial black space beneath the metadata.

**Transfer:** Use this pattern for recent research, customer stories or releases, with a clear lead item.

### Ruled contact directory

**Observed:** After 172px top spacing, a two-line white-and-grey 38px heading sits left. The right side is a sparse three-row directory: category labels, short explanation and grey destination links, with top rules. Contact preview tile anchors the lower left; Legal link row finishes the right side.

**Transfer:** Close a broad landing page with two or three useful routes and a small human image instead of a dense sitemap.

**Text style:** `statement` — gtKotoheimCondensed 300 · 38px/1.1 · tracking -0.01em

### Capability chapter

**Only for:** capability detail pages

**Observed:** A small chapter label and introductory paragraph sit at left. A modest thumbnail occupies the lower left; the middle column carries a 32px capability name; a wider far-right column carries the 32px explanation and Capability rows separated from it by 48px. Chapters have about 108px bottom spacing.

**Transfer:** Organize a few genuinely distinct capabilities, each with a short outcome statement and concrete deliverables.

**Text style:** `capability` — gtKotoheimCondensed 300 · 32px/1.15

### Partner proof and quotation

**Only for:** partner proof sections

**Observed:** Two-tone statement leads into six Partner logo tiles. Beneath them, a project artwork card sits at left and a 24px testimonial occupies the right side, with a top rule, tiny numerical progress marker and Previous/Next controls.

**Transfer:** Pair recognizable proof with one attributable, specific outcome story rather than a wall of praise.

**Text style:** `quote` — gtKotoheimCondensed 300 · 24px/1.2

### Principle cards and people index

**Only for:** culture pages

**Observed:** Two-tone statement leads into three Luminous principles cards. Farther down, a centered 38px statement introduces a dense grey field of names with a compact translucent location filter; photography and addresses then ground the people in physical places.

**Transfer:** Use abstract light to distinguish principles, a text-first index for a large community, and real photography for place. Keep these distinct editorial treatments rather than identical feature cards.

### Focused closing invitation

**Only for:** service and culture detail pages

**Observed:** An almost-screen-height black closing area aligns a tiny chapter label left with a 612px-wide, 38px invitation on the right. Primary action follows after 24px. About 330px of space precedes the main text; Contact preview tile and Legal link row sit low in the composition.

**Transfer:** Use one short invitation tied to the page's intent: contact, trial, application or exploration. Preserve the unequal scale between tiny label and substantial paragraph.

**Text style:** `statement` — gtKotoheimCondensed 300 · 38px/1.1 · tracking -0.01em

## Page flow

**Storyline:** Atmospheric identity → concise proposition → tangible work or capability proof → human or editorial credibility → useful closing route.

### Broad brand or product landing page

1. **Emotional hook** — Full-screen film with a small bottom-left two-line introduction.
2. **Promise** — A short light condensed statement explains the ambition.
3. **Demonstration** — Large work films run down an offset right rail.
4. **Editorial credibility** — Unequal news cards show current activity.
5. **Closing routes** — Ruled contact directory, small photographic contact tile and low-contrast legal row.

**Transfer:** Let the imagery establish feeling before the details; use several strong demonstrations instead of numerous text features.

### Capability-focused service or product detail page

1. **Orientation** — Split title and explanatory statement, jump links and a wide media strip.
2. **Capability chapters** — Offset thumbnail, middle-column chapter name and far-right explanation plus ruled deliverables.
3. **Social proof** — Six monochrome partner tiles followed by a project image and testimonial slider.
4. **Closing invitation** — Right-aligned substantial paragraph and one small rectangular action above the sparse footer.

**Transfer:** Use chapters to explain what the product enables, and put specific third-party proof after those details.

### Culture, team or organization page

1. **Orientation** — Split opening statement with jump links and a colorful printed-collage banner.
2. **Principles** — Three luminous abstract cards with compact split captions.
3. **Human proof** — Centered statement and dense name field with filters.
4. **Physical credibility** — Region selector, paired place photographs and mono address captions.
5. **Current activity** — Unequal editorial news cards.
6. **Closing invitation** — Recruitment-style statement and one compact action; dark work-preview tile and legal row end the page.

**Transfer:** Balance abstract culture with actual people and places; use a focused invitation rather than repeating every directory link.

## Writing

Direct, optimistic and craft-minded, with confidence carried by plain language rather than theatrical claims. Warm collective language meets short editorial declarations.

**Do not copy:** Do not reuse Koto's identity, client names, artwork, named people, office counts, addresses, project claims or testimonial language as facts about another product. Source quotations below illustrate rhythm only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker or organization and you/your when describing a partner's situation; invitations are conversational.
- **Rhythm:** Short declarative fragments alternate with compact explanatory sentences. Parallel three-part phrases and deliberate full stops create pace; headlines need not be loudly promotional.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Introduction | Simple identity followed by a category descriptor. | 2–5 words per line | “We’re [Brand]”<br>“The Creative Company” |
| Proposition | A direct collective verb and a parallel object; ambition is attached to something concrete. | 7–12 words | “We make ambitious ideas for ambitious brands.” |
| Section statement | Short topic phrase followed by a rhythmic explanation. | 10–20 words | “Built on optimism. Driven by collaboration. Defined by craft.” |
| Capability explanation | Name the practical function and the outcome in one sentence. | 15–25 words | “Visual and verbal systems that define how brands show up, stand out, and stay ahead.” |
| Primary action | Plain invitation or direct view verb; no urgency device. | 3–4 words | “Get in touch”<br>“See open roles” |

**Words and phrasing to use:** make; built; craft; together; ambitious; what’s next; show up; humanly possible

**Avoid:** revolutionary solution; unlock limitless potential; best-in-class platform; hurry; game-changing ecosystem

**Rules:**

- Let concrete work support a confident proposition; avoid stacking abstract superlatives.
- Use fragments for rhythm, not for withholding the actual purpose.
- Keep labels factual and short; brackets belong to utility links, not every sentence.
- Match the final invitation to the reader's next useful step.

## Do's and Don'ts

### Do

- Keep the opening introduction at 48px and weight 300, letting the film supply scale.
- Use 38px white-to-grey statements rather than adding a new oversized headline tier.
- Align text to the 28px visual edge while wide media can start at 16px.
- Keep grid gutters narrow: 8px for the scaffold and 12px for editorial cards.
- Give buttons 2px corners and 16px padding, with uppercase 11px mono text.
- Keep editorial media at 16:9 and place photography at 4:3.
- Use 1px alpha-white rules for chapter changes and deliverable rows.
- Retain a small image-led closing anchor and a low-contrast legal row.

### Don't

- Do not use weight 700 grotesk headings; light condensed type is the defining text texture.
- Do not apply acid yellow to body links, conversion fills or full-width prose backgrounds.
- Do not give all news items equal widths; the lead image must retain greater physical scale.
- Do not surround editorial cards with raised panels or drop shadows; their media and text stand on black.
- Do not add wide uppercase tracking to the mono labels; their tracking is normal.
- Do not increase all body copy to 20px; 14px descriptions and 16px titles keep the editorial texture compact.
- Do not replace 6px media corners with conspicuous 24px rounded cards.
- Do not make the footer a bright full-width promotional band.

## Motion and responsive

### Motion

**Observed:**

- The opening has a pinned 900px media stage within an 1800px scroll region.
- Declared color transitions commonly use 0.167s linear; tag background transitions include 83ms linear.
- The navigation backing declares an all-properties transition of 0.75s cubic-bezier(0.28, 0, 0, 1).
- Text reveal masks and moving project media accompany scrolling.

**Transfer:**

- Preserve the distinction between cinematic opening motion and restrained, fast interface feedback.
- Use masked statement reveals only where they help the media-to-reading transition; do not animate every card independently.

**Unknown:**

- Exact playback sequence and scroll synchronization are not specified.
- Hover, focus-visible and active appearance of most actions is not established.

### Responsive

**Observed:**

- Declared width breakpoints: 768px, 834px, 1024px, 1194px, 1440px, 1536px and 1728px.
- Opening text classes include a 36px compact variant; ordinary statement classes include a 26px variant. Desktop grids use 16 columns, with 8-column structures in base classes.

**Transfer:**

- On narrow screens, keep the film dominant and the introduction bottom-left; stack split title and description rather than centering them.
- Collapse the right media rail into the content width while retaining short labels and compact gutters.
- Turn unequal news and paired place grids into a readable vertical sequence, preserving the lead item's prominence.

**Unknown:**

- Actual small-screen composition, navigation expansion and breakpoint-specific media behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
