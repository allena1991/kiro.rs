# Alt Studios — antithesis as architecture

## Overview

A light, uncompromising editorial style in which a wall of paired statements becomes the main visual object. Black grotesk typography sits on white or warm stone, while natural color belongs to photographs, physical models and carefully framed project imagery. It suits design-led products and portfolios that can express a clear point of view with very little explanatory copy; dense typographic fields alternate with orderly, image-led browsing.

### Essentials

- The manifesto is the image: paired opposing phrases fill two equal columns in 74.9px grotesk, line-height 1 and -0.02em tracking, with approximately 75px between successive rows.
- The opening reads like a full-window printed sheet, not a centered hero: text begins at the top edge, left statements near an 18px inset and their counterparts near the horizontal midpoint; a 58px navigation strip anchors the bottom.
- Actions are words rather than button objects: 18px text, no fill, border, shadow or rounded enclosure, with black underline feedback.
- Color stays inside the work: the ordinary canvas is #ffffff with #000000 text; the catalogue variant uses #e3dfdc across its entire backing. There are no chromatic marketing fills.
- A miniature editorial index replaces promotional cards: four 327px-wide columns, 28.8px gutters, 327×229px rectangular images and single-line 18px captions beneath.
- The closing gesture is persistent navigation rather than a new sales panel: an uppercase brand link at lower left, comma-separated internal links around the midpoint and social/subscription links at lower right remain visually subordinate to the content.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, link, action | All display statements, captions, brand lettering and link feedback. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White sheet | `#ffffff` | `--color-canvas` | background, surface | Default marketing canvas and the matching bottom navigation backing. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| catalogue and portfolio index pages | Warm stone | `#e3dfdc` | `--color-catalogue` | background, surface | Continuous backing behind the image index and its persistent utilities. |

## Typography

- **UniversalSans** — All text; the 600 cut carries statements and labels, and the 750 cut distinguishes the uppercase brand link. Direct neo-grotesk with a large x-height, open counters and compact, unembellished letterforms. If unavailable, use **Inter**. Use 600 for text and 750 for the brand; preserve tight display tracking. Font stack: "UniversalSans", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | UniversalSans | 600 | 74.9px | 1 | -0.02em | size 5.2vw | Paired manifesto statements; the main graphic and highest heading role. |
| label | UniversalSans | 600 | 18px | 1 | normal | size 1.25vw | Navigation, subscription actions and image titles; one shared small-text scale. |
| brand | UniversalSans | 750 | 18px | 1 | normal, uppercase | size 1.25vw | Compact brand-name link in the persistent bottom corner. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The hierarchy has just two sizes: display is 4.16 times the label size. The brand changes cut rather than size.
- Only display text tightens to -0.02em; small labels retain normal tracking and sentence/title case except for the brand.
- Use the paired statements as headings in their own right. Do not introduce a separate eyebrow, support paragraph and intermediate headline scale.

## Layout

**Density:** Dense in the manifesto and economical in the catalogue; vertical space follows the letter size or the image-caption module rather than expansive chapter padding.

### Spacing

| Value | Use |
| --- | --- |
| 18px | Display left inset and vertical padding around navigation labels. |
| 24.3px | Outer index inset, bottom-corner horizontal padding and spacing below each index tile. |
| 14.4px | Image-to-caption separation. |
| 28.8px | Horizontal index gutter. |
| 72px | Index top padding, reserving room for its internal navigation. |
| 49.5px | Index bottom padding. |
| 74.9px | Manifesto row rhythm; exactly one display line. |

### Containers and grids

- **Manifesto field**: 2 columns · gap 22px · side padding 18px. Full viewport width without a centered max-width. Two nearly equal statement fields align row by row; each measures about 706px at 1440px, with the right text beginning near the midpoint.
- **Bottom utility strip**: side padding 24.3px. A 58px-tall full-width bottom strip. The brand sits at the left edge; internal links align with the second half of the page and external links align right.
- **Index grid** (only for catalogue and portfolio index pages): 4 columns · gap 28.8px · side padding 24.3px. Full-width grid of 327px image-caption modules. The final row remains left aligned even when it contains only two items.

## Corner radius

| Element | Radius |
| --- | --- |
| Image windows and flat sheets | 0px |

## Surfaces and depth

### Surfaces

#### White sheet · level 0

**Use:** Default marketing field and navigation backing.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** A flat, untextured plane; content is not divided into raised panels.

**Transfer:** Let typography define the structure rather than adding decorative materials.

#### Stone index sheet · level 0

**Only for:** catalogue and portfolio index pages

**Use:** One continuous backing for the entire browsing grid.

**CSS:** `background: #e3dfdc; color: #000000`

**Observed:** Images and labels sit directly on the same sheet as the lower utility links.

**Transfer:** Use a single warm neutral field across the collection; individual tiles do not get separate card fills.

## Components

### Manifesto pair

**Use:** Repeatable headline unit and the signature typographic artwork.

**CSS:** `position: relative; height: 74.9px; color: #000000`

**Text style:** `display` — UniversalSans 600 · 74.9px/1 · tracking -0.02em

**Observed:** Two left-aligned halves contrast a repeated short qualifier and a changing noun. Counterpart phrases share a baseline; the first and last visible rows can run beyond the field edges.

**Transfer:** Write paired product-specific contrasts, keeping each half short enough for one line at desktop.

### Bottom navigation strip

**Use:** Persistent page orientation and the understated closing device.

**CSS:** `position: fixed; bottom: 0px; height: 58px; background: #ffffff; color: #000000`

**Text style:** `label` — UniversalSans 600 · 18px/1

**Observed:** Brand at left, internal navigation near the centerline and external utilities at right. On the index, the brand and external utilities remain below while internal navigation moves above the grid; the backing matches the stone sheet.

**Transfer:** Keep the three alignment anchors rather than centering all links in one cluster.

### Brand link

**Use:** Persistent homeward identity anchor.

**CSS:** `color: #000000; text-transform: uppercase; transition: text-decoration-color 0.2s`

**Text style:** `brand` — UniversalSans 750 · 18px/1 · uppercase

**Observed:** A compact text wordmark, heavier than neighboring navigation, positioned within the lower-left padded corner.

**States:** Declared: hover text-decoration-color #000000; focus-visible and active treatment are unspecified.

**Transfer:** Set the new product's name as plain uppercase type instead of adding a symbol.

### Navigation link

**Use:** Internal page selection.

**CSS:** `color: #000000; background: none; transition: text-decoration-color 0.2s`

**Text style:** `label` — UniversalSans 600 · 18px/1

**Observed:** Short inline labels separated by commas. The current index label has a visible underline; labels are otherwise visually bare until underline feedback.

**States:** Declared: hover text-decoration-color #000000; focus-visible and active treatment are unspecified.

### Subscription link

**Use:** The small conversion action in the right-hand utility group.

**CSS:** `color: #000000; background: none; text-align: right; transition: text-decoration-color 0.2s`

**Text style:** `label` — UniversalSans 600 · 18px/1

**Observed:** Appears directly after the social link, separated by a comma. It has no stronger visual container than the other links.

**States:** Declared: hover text-decoration-color #000000; focus-visible and active treatment are unspecified.

**Transfer:** Use one short verb appropriate to the new product without turning it into a filled CTA.

### Index tile

**Only for:** catalogue and portfolio index pages

**Use:** Clickable image-led proof or collection item.

**CSS:** `margin-right: 28.8px; margin-bottom: 24.3px`

**Text style:** `label` — UniversalSans 600 · 18px/1

**Observed:** One link wraps an image followed by its title. Desktop tiles measure 327×261px, with the image consuming almost all of the module. No descriptions, badges, rules or overlays interrupt the grid.

**Transfer:** Use named examples, applications or customer outcomes as concise image-caption pairs.

### Index image

**Only for:** catalogue and portfolio index pages

**Use:** Uniform visual window within each index tile.

**CSS:** `object-fit: cover; position: absolute`

**Observed:** A relative image wrapper provides a 327×229px window and 14.4px separation before its caption. Mixed photographic, model and illustrated media share the same rectangular framing.

**Transfer:** Crop deliberately to the common landscape ratio rather than letting intrinsic image heights drive the grid.

### Index caption

**Only for:** catalogue and portfolio index pages

**Use:** The only heading under each collection image.

**CSS:** `color: #000000; font-size: 18px; line-height: 1; letter-spacing: normal`

**Text style:** `label` — UniversalSans 600 · 18px/1

**Observed:** A left-aligned title immediately beneath the image; it uses the same size as navigation rather than a separate card-heading scale.

**Transfer:** Name the item rather than adding a miniature marketing paragraph.

## Imagery and graphics

### Typographic contrast wall

**Use:** The required signature graphic for an ordinary marketing page.

**Observed:** Black text itself occupies the full white field. Repeated short qualifiers and varied nouns form a two-column texture, with roughly eleven complete rows visible above the bottom utilities in a 900px-high view.

**Transfer:** Create the visual from the new product's own concise contrasts; no photography or bespoke illustration is needed for this opening.

**Build:** Use real HTML text in two equal-width columns on #ffffff. Set UniversalSans or Inter to 74.9px/1 at 1440px, weight 600, tracking -0.02em. Repeat paired rows at one line-height intervals, keep the left inset 18px, and align the second column around the midpoint. Mask overflow at the viewport edges and layer the matching 58px bottom strip above it. If implementing a repeating field, duplicate its visual sequence but hide duplicate text from accessibility APIs.

### Material-led catalogue imagery

**Only for:** catalogue and portfolio index pages

**Use:** Primary proof in the image index.

**Observed:** Architectural views mix with a close textile detail, a coastal aerial, wooden site models, a small pale building model and an illustrated isometric cutaway. Light is soft and natural or studio-diffused; muted earth, cream and green dominate, with occasional stronger textile and illustration colors. Models sit on pale studio backgrounds with real contact shadows. Each image fills a hard-edged landscape window, with captions outside the image.

**Transfer:** Mix contextual photography, tactile details, prototypes and explanatory illustrations for the new product. Keep material texture and believable light; the minimum equivalent is a set of well-composed photographs plus a simple physical or digital prototype on a neutral backing, all framed consistently.

## Section recipes

How recurring sections are built.

### First screen: Full-window contrast opening

**Observed:** A white viewport carries the typographic contrast wall from edge to edge; there is no top masthead above it. Two aligned columns of 74.9px text fill nearly all the first 900px, with words starting close to the top and left edges and the second phrase anchored around the midpoint. The typography is the main object and headline at once. From back to front: White sheet, repeated Manifesto pair rows, then Bottom navigation strip masking the lower text. About eleven complete rows and the start of another fit above the 58px utilities. The brand, three compact internal destinations and two external/action labels are visible; there is no separate support paragraph, hero image or large button. More text continues beyond the window rather than introducing a second visual chapter.

**Transfer:** Make an equally forceful opening with a series of concise contrasts about the new product's approach or outcomes. Keep the field populated on initial render. Collection pages instead open directly on the Stone index sheet with navigation above a four-column proof grid; the contrast wall remains the marketing signature, not a mandatory backdrop behind every page type.

**Avoid:** Do not reproduce an empty first viewport with only the tops of letters at the bottom. Do not shrink the manifesto into a centered slogan above a generic product mockup.

**Text style:** `display` — UniversalSans 600 · 74.9px/1 · tracking -0.02em

### Repeated contrast field

**Observed:** Manifesto pair rows retain the same type size and rhythm through a sequence of paired ideas. The repetition provides chapter structure without eyebrow labels, divider rules or explanatory blocks.

**Transfer:** Use as many pairs as the argument warrants, preserving the repeated grammatical frame and aligned counterparts.

**Text style:** `display` — UniversalSans 600 · 74.9px/1 · tracking -0.02em

### Persistent utility ending

**Observed:** The visual ending is the same compact lower-corner identity and utility system, not a separate footer chapter. The marketing field continues behind its white bottom strip; the index finishes in its last partially occupied row against the stone backing, with brand and external actions still anchored below.

**Transfer:** Finish with the last meaningful statement or proof item and keep navigation available. Do not invent a monumental final pitch or multi-column corporate footer.

**Text style:** `label` — UniversalSans 600 · 18px/1

### Direct image index

**Only for:** catalogue and portfolio index pages

**Observed:** Stone index sheet contains Index tiles in four columns with 24.3px side insets, 28.8px gutters and 72px top padding. Navigation begins over the right half above the grid. Images lead and captions follow; the last row has two items at the left with unused space to their right.

**Transfer:** Open collection-oriented pages with the work itself instead of a separate promotional introduction. Let an incomplete final row retain its natural alignment.

**Text style:** `label` — UniversalSans 600 · 18px/1

## Page flow

**Storyline:** Point of view or direct proof → repeated exploration within one visual system → persistent routes to more detail and contact.

### A point-of-view marketing landing page

1. **Promise** — A full-window wall of paired contrasts communicates a position without a conventional lead paragraph.
2. **Capability framing** — Successive statement pairs deepen that position while preserving one unbroken type treatment.
3. **Closing action** — Persistent bottom navigation offers work, information and subscription routes rather than a separate CTA section.

**Transfer:** Replace the argument with the new product's differentiating trade-offs. Let the signature field carry the first impression and use restrained text routes for deeper exploration.

### An image-first portfolio or collection index

1. **Orientation** — A small internal navigation line sits over the right half of the warm neutral canvas.
2. **Proof** — A four-column image-caption grid presents varied examples at equal scale.
3. **Closing action** — The incomplete final row ends naturally while lower-corner identity and social/subscription links remain available.

**Transfer:** Use for collections of examples, applications or case studies, keeping the direct browse-first opening and small utility system.

## Writing

Terse, assertive and intellectually opinionated. Confidence comes from sharp contrasts and specific names rather than enthusiastic sales language.

**Do not copy:** Do not reuse the studio's name, project names, distinctive manifesto sequence, artwork or implied claims about its practice. Source examples illustrate cadence only; write a new argument and use the new product's real work.

- **Addressing the reader:** Mostly impersonal noun phrases; direct reader address and first-person selling are absent from the principal text.
- **Rhythm:** Two-word statement halves repeated in parallel, with one-word navigation labels and short proper-name captions. Commas connect utility links; display statements need no sentence punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Display statement | A repeated comparative qualifier followed by a single concept, paired with its desired counterpart. | 2 words per half | “Less Quantity”<br>“More Quality” |
| Navigation | A literal destination name rather than a persuasive sentence. | 1 word | “Work”<br>“Information”<br>“Index” |
| Conversion action | A direct, unmodified verb. | 1 word | “Subscribe” |
| Image title | A specific project or place name without explanatory subtitle. | 2–4 words | “Schoolhouse Lane”<br>“A Deadgood Workspace” |

**Words and phrasing to use:** short comparative frames; concrete nouns; meaningful oppositions; plain destination labels; specific item names

**Avoid:** superlative product hype; vague transformation promises; chatty greetings; long feature explanations; exclamation marks

**Rules:**

- Make each contrast meaningful on its own and coherent with the sequence.
- Let repeated syntax supply momentum; vary the concept rather than the sentence structure.
- Use concise labels that say where a link goes or what it does.
- Keep captions factual and omit decorative taglines.

## Do's and Don'ts

### Do

- Keep the 74.9px display and 18px labels as a deliberately stark two-size hierarchy at 1440px.
- Align statement counterparts row for row with a line-height of 1.
- Maintain the lower 58px utility zone as a calm, legible edge to the dense field.
- Use the same 18px recipe for index titles and navigation.
- Let muted material imagery provide color against the warm stone index backing.
- Preserve 14.4px between an index image and its caption, and 28.8px between columns.

### Don't

- Do not turn the one-word subscription action into a colored pill or oversized filled button.
- Do not add shadows, rounded photo corners or floating cards to the flat editorial sheets.
- Do not apply -0.02em tracking to the 18px labels; it belongs to display type.
- Do not use the stone catalogue background as the default marketing theme; ordinary openings are white.
- Do not add a third headline scale merely to make index captions look more important.
- Do not force each index media type into identical art direction; consistent rectangular framing, not a uniform subject, unites the collection.

## Motion and responsive

### Motion

**Observed:**

- Links declare text-decoration-color 0.2s transitions and black hover underline color.
- The page body declares background-color 0.6s and color 0.6s transitions; the main fixed wrapper declares a 0.5s transition.
- The statement field uses duplicated sequences within an infinite-scroll structure.

**Transfer:**

- Keep link feedback typographic and small.
- If repeating the statement field, preserve aligned rows and an opaque bottom utility layer rather than introducing independent animated cards.

**Unknown:**

- The wrapper transition's full intended behavior and trigger are unspecified.
- The continuous field's timing, direction and easing are not established; no automatic marquee speed is prescribed.

### Responsive

**Observed:**

- Root type sizing is viewport-relative at 1.25vw; the display resolves to 74.9px and the small text to 18px at 1440px.
- Styles declare width breakpoints at 600px, 1000px, 1024px and 1700px.

**Transfer:**

- On narrow screens, keep the paired argument readable by stacking each pair together before moving to the next pair; retain the repeated syntax and line-height relationship.
- Reduce index column count when its captions or media become cramped, keeping the image-caption relationship and left-aligned final row.
- Keep corner utilities distinct from content; adapt the label arrangement rather than allowing them to cover each other.

**Unknown:**

- Exact mobile sizes, breakpoint-specific column counts and mobile navigation positions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
