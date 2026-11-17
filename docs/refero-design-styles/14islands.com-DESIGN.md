# 14islands — split-scale digital craft

## Overview

An airy digital atelier aesthetic, pairing monumental regular-weight sans lettering with tiny utilitarian capitals. A pale gray canvas and black typography leave color to richly art-directed photography, interface compositions and playful three-dimensional experiments. It suits creative technology and premium product storytelling, with dark capability-led and warm people-led variants rather than a single uniform theme.

### Essentials

- Words become the opening artwork: 180px regular AftenScreen, 0.8 line height and -0.05em tracking, split into opposing left and right lines with a gray conjunction.
- The promise is deliberately small above the spectacle: 12px uppercase BentonSans at 1.4 line height sits in the right half of an 810px opening, beneath a 111px navigation band.
- The interface stays almost achromatic: #f2f2f2 is the default canvas, #070707 the ink, #a2a2a9 the secondary voice and #ffffff the closing field; saturated color belongs inside media rather than surrounding controls.
- Proof reads like an exhibition wall: two 661px-wide media cards with 10px gutters, 4.2px corners and 26.7px captions that join an ink title to a gray category with a short dash. Use composed product views when photography is unavailable.
- Actions are typographic, not pill-shaped: 12px uppercase arrow links and a 75px contact link are the default; the focused-offer variant uses an 83px-tall black rectangle with 4px corners.
- The ending is a monumental invitation, not a sitemap: a white 900px field, two 75px lines at the upper left, an equally large contact link in the right half, and tiny links along the bottom. Preserve this device on new pages.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool gray | `#a2a2a9` | `--color-secondary` | text, accent | Secondary phrases, opening conjunction and caption categories on the default canvas. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-paper` | background, surface, text | Closing canvas, case-story canvas, focused-offer panel and inverse text. |
| Light gray canvas | `#f2f2f2` | `--color-canvas` | background | Default marketing canvas and related-proof bands. |
| Mid gray | `#797979` | `--color-muted` | text, action | Utility text and inverse-theme secondary headings; focused-offer button hover. |
| Near black | `#070707` | `--color-ink` | text, background, action | Primary lettering and links; also the full-page inverse theme. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| people and company stories | Warm sand | `#eae5df` | `--color-warm-canvas` | background | Full people-led editorial canvas. |
| people and company stories | Warm gray | `#a59d92` | `--color-warm-secondary` | text, accent | Secondary headings, conjunction and caption categories on warm sand. |
| inverse showcase lists | Subtle dark rule | `#292929` | `--color-inverse-rule` | border | Visible result of rgba(120,120,120,0.3) over near black; row separators. |

## Typography

- **AftenScreen** — All expressive headings, prose and captions. Regular-weight humanist sans with open counters and a soft, slightly calligraphic rhythm; tightly spaced rather than heavy. If unavailable, use **Lato**. Use 400 and tune word widths before changing the tight tracking. Font stack: "AftenScreen", "Lato", sans-serif.
- **BentonSans** — Navigation, eyebrows, compact supporting copy and metadata. Small, straightforward grotesk capitals acting as editorial markings. If unavailable, use **Libre Franklin**. Use 400; maintain the 12px uppercase utility scale. Font stack: "BentonSans", "Libre Franklin", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| hero | AftenScreen | 400 | 180px | 0.8 | -0.05em | size 12.5vw | Two opposing headline lines, treated as the main graphic. |
| statement | AftenScreen | 400 | 100px | 1 | -0.04em | fixed | Large two-tone value proposition below the opening media. |
| heading-lg | AftenScreen | 400 | 75px | 1 | -0.04em | size max(1.875rem, 5.20833vw) | Full-width editorial statements, closing invitation and contact link. |
| body-caption | AftenScreen | 400 | 26.7px | 1.3 | -0.04em | size max(1.25rem, 1.85185vw) | Right-column prose, list titles and image captions; this is the main reading scale, not a small-print caption. |
| utility | BentonSans | 400 | 12px | 1.4 | normal, uppercase | size max(0.75rem, 0.810185vw) | Navigation, section labels, short support lines and footer metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| case studies | case-title | AftenScreen | 400 | 283.3px | 0.8 | -0.05em | size 19.6759vw | Single short project or product name near the bottom of the opening viewport. |
| capability and editorial chapters | chapter-heading | AftenScreen | 400 | 50px | 1.1 | -0.04em | size max(1.75rem, 3.47222vw) | Inline gray chapter name followed by a sentence, or focused-offer headline. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep all principal text at weight 400. Hierarchy comes from the dramatic jump between 12px utility text and the much larger reading and display sizes.
- Use gray spans inside otherwise black or white statements; emphasis is a color change, not bold or italic.
- The opening is more tightly tracked than prose: -0.05em versus -0.04em. Preserve word silhouettes when replacing the type family.

## Layout

**Density:** Airy: large empty fields separate tiny metadata, monumental type and tightly spaced media grids.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 10px | Grid column gutter. | max(0.625rem, 0.578704vw) |
| 24px | Offer button vertical padding and benefit-list gap. | max(1.5rem, 1.38889vw) |
| 25px | Media-to-caption margin and portfolio row gap. | 1.73611vw |
| 54.2px | Desktop horizontal page inset. | fixed |
| 66.7px | Spacing between stacked prose groups and opening headline bottom padding. | 4.62963vw |
| 100px | Standard section vertical padding. | max(6.25rem, 5.78704vw) |
| 120px | Media chapter vertical padding. | max(7.5rem, 6.94444vw) |
| 135px | Focused-offer panel inner padding. | fixed |
| 160px | Extended bottom space after major statements. | fixed |

### Containers and grids

- **fluid page**: side padding 54.2px. At 1440px the content spans 1332px. Keep the canvas fluid rather than imposing a centered fixed maximum.
- **editorial grid**: 12 columns · gap 10px. Underlying alignment grid; prose commonly occupies the right six columns, leaving the left half for a small label or open space.
- **portfolio grid**: 2 columns · gap 10px. Equal-width 661px media cards with 25px vertical row separation.
- **chapter media grid** (only for capability and editorial chapters): 4 columns · gap 10px. One half-width lead image beside two quarter-width supporting images; alternate the wide image from left to right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media | 4.2px |
| focused offers | offer button | 4px |

## Surfaces and depth

### Surfaces

#### Default canvas · level 0

**Use:** Ordinary marketing and portfolio pages.

**CSS:** `background: #f2f2f2; color: #070707`

**Observed:** Flat, uninterrupted pale gray behind both large text and colorful imagery.

**Transfer:** Let spatial composition and media provide depth rather than raised boxes.

#### White field · level 0

**Use:** All page endings and case-story content.

**CSS:** `background: #ffffff; color: #070707`

**Observed:** The ending is a complete background switch, not an inset card.

**Transfer:** Use the white field to give the final invitation its own room.

#### Inverse canvas · level 0

**Only for:** capability and focused-solution pages

**Use:** Long capability narratives and technical showcases.

**CSS:** `background: #070707; color: #ffffff`

**Observed:** A continuous near-black field through imagery, prose and proof; gray headings remain visible. Ends on White field.

**Transfer:** Choose it as a page-level variant, not alternating arbitrary dark cards.

#### Warm editorial canvas · level 0

**Only for:** people and company stories

**Use:** Human-led narrative and photographic mosaics.

**CSS:** `background: #eae5df; color: #070707`

**Observed:** Warm gray secondary text replaces the cool gray of the default theme.

**Transfer:** Pair this variant with candid, natural-light media.

#### Focused offer panel · level 1

**Only for:** focused offers

**Use:** One high-contrast conversion island within an inverse page.

**CSS:** `background: #ffffff; color: #070707; padding: 135px; box-shadow: none`

**Observed:** A broad square-cornered panel aligned to the page margins, with headline, metadata, benefits and a full-width button.

**Transfer:** Use for a concrete consultation, trial or guided session with clear practical details.

## Components

### Navigation

**Use:** Persistent, minimal wayfinding.

**CSS:** `position: fixed; height: 111px; display: flex; align-items: center; z-index: 2`

**Text style:** `utility` — BentonSans 400 · 12px/1.4 · uppercase

**Observed:** Small wordmark at left; navigation starts in the right half, with the contact destination isolated at the far right. Colors follow the current page theme.

**Transfer:** Use a compact text identity and a few destinations rather than a button-heavy toolbar.

### Arrow text link

**Use:** Default secondary action after a short support line.

**CSS:** `color: #070707; margin-top: 20px`

**Text style:** `utility` — BentonSans 400 · 12px/1.4 · uppercase

**Observed:** Unboxed uppercase text ending in a thin right arrow.

**Transfer:** Keep action wording short and aligned to the right-column copy.

### Media card

**Use:** Visual proof in the portfolio grid.

**CSS:** `position: relative; overflow: hidden; border-radius: 4.2px; margin-bottom: 25px`

**Text style:** `body-caption` — AftenScreen 400 · 26.7px/1.3 · tracking -0.04em

**Observed:** A landscape image around 661px by 441px above the caption; the whole item is linked. No separate card fill or elevated frame.

**Transfer:** Replace the picture with a polished product composition while retaining the landscape ratio and external caption.

### Dashed caption

**Use:** Pair a proof title with a category or content type.

**CSS:** `color: #070707; max-width: 97%`

**Text style:** `body-caption` — AftenScreen 400 · 26.7px/1.3 · tracking -0.04em

**Observed:** Title and muted category flow together on one baseline, separated by a short horizontal dash. The suffix uses cool gray by default; inverse and warm themes use their corresponding secondary tones.

**Transfer:** Treat taxonomy as part of the sentence, not a badge.

### Archive link row

**Use:** Compact secondary proof list.

**CSS:** `height: 68px; position: relative; overflow: hidden`

**Text style:** `body-caption` — AftenScreen 400 · 26.7px/1.3 · tracking -0.04em

**Observed:** A right-half-width stack of linked title/category captions with fine horizontal divisions; the left half stays open.

**Transfer:** Use for additional examples, resources or available roles without introducing thumbnail clutter.

### Monumental contact link

**Use:** Principal conversion action in the closing field.

**CSS:** `color: #070707; background-image: linear-gradient(#070707, #070707); background-size: 0% 1px; background-position: 100% 82%; background-repeat: no-repeat`

**Text style:** `heading-lg` — AftenScreen 400 · 75px/1 · tracking -0.04em

**Observed:** Sits in the right half below the left-aligned invitation, sharing its scale. Underline is a fine drawn line rather than a filled button.

**Transfer:** Use a short contact address or equally concise conversion destination.

### Offer button

**Only for:** focused offers

**Use:** Single broad conversion action inside Focused offer panel.

**CSS:** `background: #070707; color: #ffffff; padding: 24px 12px; border-radius: 4px; text-align: center; transition: background .2s cubic-bezier(0.25,0.46,0.45,0.94)`

**Text style:** `body-caption` — AftenScreen 400 · 26.7px/1.3 · tracking -0.04em

**Observed:** Spans the panel's inner width, 1062px at desktop, with centered text and an overall height of 83px.

**States:** Declared: hover background #797979; focus-visible unknown.

**Transfer:** Reserve this rectangle for a focused offer, rather than replacing every ordinary text link.

### Showcase table row

**Only for:** inverse showcase lists

**Use:** Compact project proof on a focused-solution page.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 32px 0px; border-bottom: 1px solid rgba(120,120,120,0.3)`

**Text style:** `body-caption` — AftenScreen 400 · 26.7px/1.3 · tracking -0.04em

**Observed:** A 100px row with a gray title on the left, 12px uppercase discipline metadata in the second half and a small case-study link at the right when available.

**Transfer:** Use text-first proof where a full media grid would overwhelm a concise story.

## Imagery and graphics

### Art-directed product proof

**Use:** Main proof grid and wide reel beneath the opening.

**Observed:** Color is concentrated in media: jewelry and apparel photography, devices staged on furniture or colored sets, glass-like 3D ribbons, and crisp website views suspended over atmospheric photographs. The outer page remains neutral. Landscape rectangles dominate, with tiny corners and captions outside.

**Transfer:** Create a product view centered over a high-quality photo or a simple material study. Minimum version: one clean interface view on a softly lit physical backdrop, not a bare browser screenshot.

**Build:** For a media-only stage, place a crisp interface rectangle at roughly two thirds of the frame width over a full-bleed photograph or a dark material background. For an abstract fallback, use two overlapping curved SVG ribbons with cyan-to-violet fills, thin pale highlights and a dark backing; keep these hues inside the media bounds.

### Typographic opening sculpture

**Use:** Required signature opening device.

**Observed:** Two oversized sans words are separated across two lines, with the first anchored left and the second ending at the right inset. A gray ampersand balances the lower line. The form is flat lettering, not a beveled 3D logo.

**Transfer:** Choose two short complementary concepts relevant to the new product. If there is no product photography, this word composition still carries the opening.

**Build:** Use live heading spans in a two-row grid with the hero type recipe. Left-align row one, right-align the main word in row two, and position a secondary-colored conjunction at the left of row two. Keep a 66.7px bottom breathing zone.

### Candid mosaic

**Only for:** people and company stories or capability introductions

**Use:** Photographic introduction following a split-word opening.

**Observed:** Natural-light people working, objects on desks, shared activities and landscape travel photographs form an asymmetric four-column mosaic. Small quarter-width images coexist with a half-width lead image and deliberately open canvas cells.

**Transfer:** Use authentic people, tools and environments connected to the product. Preserve the varied scale and irregular occupancy rather than making a uniform staff grid.

### Case-study gallery

**Only for:** case studies

**Use:** Long-form demonstration of craft and responsive layouts.

**Observed:** Alternates full-width, paired and isolated half-width media. Luxury portraits, object photography and editorial web layouts are backed by pale stone or near-black fields. Mobile views float centrally in broad mats; a diagonal sheet of repeated article views creates a culminating overview.

**Transfer:** Show the new product at several scales, with material close-ups and responsive interface compositions. Keep client-interface typography inside the demonstration, separate from the marketing typography.

**Build:** For an overview, arrange actual interface exports in a regular three-column sheet, rotate the sheet approximately -30deg and clip it inside a landscape media frame. For mobile demonstrations, center one or two narrow interface exports on a neutral mat with generous empty backing.

### Icons

**Observed:** Iconography is sparse: fine right arrows for actions and short 19px by 2px dashes for caption separators, colored to match secondary text.

**Transfer:** Prefer typographic arrows and simple line marks. Do not add a pictogram to every feature.

## Section recipes

How recurring sections are built.

### First screen: Split-word opening

**Observed:** Default canvas behind Navigation, tiny right-half metadata and the Typographic opening sculpture. The 111px header leaves a broad open upper field; a 12px eyebrow and support sentence sit around the upper-middle of the right half. Two 180px headline lines occupy the lower part of the 810px opening: first word at the left, second word right-aligned, gray conjunction on the lower left. Within the first 900px, all headline lettering, support text and navigation are visible and the top strip of the following media appears; the main reel continues below. There is no central filled CTA: the navigation contact link is the visible conversion route.

**Transfer:** Use two short product-relevant ideas and a compact statement of purpose, keeping the same opposing alignments. Stage a product composition or material study in the following media frame if a reel is unavailable. Case studies use a single larger name with metadata above; focused-solution pages can open with a right-biased photograph and a 75px statement overlapping its lower edge. People-led pages retain the split-word opening on warm sand.

**Avoid:** Do not turn this into a centered headline, paragraph and pair of rounded buttons. Do not cram the media into the remaining space above the headline or shrink the words to ordinary heading size.

**Text style:** `hero` — AftenScreen 400 · 180px/0.8 · tracking -0.05em

### Two-tone proposition

**Observed:** A full-width 100px statement uses a gray concept followed by an ink outcome across two lines. A tiny uppercase supporting sentence and Arrow text link sit below in the right half. Standard top padding is 100px, with 160px after the content.

**Transfer:** Make the relationship between product category and customer outcome visible through color and line breaks.

**Text style:** `statement` — AftenScreen 400 · 100px/1 · tracking -0.04em

### Editorial label and prose

**Observed:** A 12px uppercase section label occupies the left edge while 26.7px prose occupies the right half. Subheadings use the secondary theme color directly above their paragraphs, with roughly 66.7px between groups. Standard section padding is 100px.

**Transfer:** Use for capabilities, principles, process or objections. The alignment system matters more than the subject.

**Text style:** `body-caption` — AftenScreen 400 · 26.7px/1.3 · tracking -0.04em

### Portfolio proof wall

**Observed:** Media card and Dashed caption repeat in a two-column grid with 10px gutters and 25px row gaps. A large photographic field does the selling; names and taxonomy remain plain text below.

**Transfer:** Use a curated selection of different visual proof types, then move lesser examples into Archive link row.

### Monumental closing

**Observed:** White field fills a 900px closing section with 100px top padding and the standard page inset. A two-line 75px invitation sits at the upper left; Monumental contact link sits in the right half approximately 85px below the invitation. Bottom metadata is 12px uppercase with 50px bottom padding, copyright left and a sparse line of social and legal links right. All themes return to this white ending; the invitation can be tailored to the page's promise.

**Transfer:** Close with a warm collaborative invitation and one direct route to act. Keep the vast open center and avoid replacing it with a dense footer navigation tree.

**Text style:** `heading-lg` — AftenScreen 400 · 75px/1 · tracking -0.04em

### Alternating chapter

**Only for:** capability and editorial chapters

**Observed:** A 50px paragraph begins with a gray chapter phrase and dash, followed inline by the main sentence. Below it, Chapter media grid pairs a large image with two smaller images and Dashed caption. Alternate the large image's side. The chapter has 120px top and bottom padding and 100px between its heading and media.

**Transfer:** Organize benefits or use cases into distinct visual chapters, varying the lead image position rather than adding card chrome.

**Text style:** `chapter-heading` — AftenScreen 400 · 50px/1.1 · tracking -0.04em

### Focused offer

**Only for:** focused offers

**Observed:** Focused offer panel interrupts Inverse canvas. A 50px two-line headline with gray inline emphasis spans the top; utility metadata sits at left and three 26.7px benefit lines at right. Offer button closes the panel across its inner width.

**Transfer:** State an actionable offer, its practical format and a few concrete outcomes. Preserve the stark white-on-black contrast without adding decorative badges.

**Text style:** `chapter-heading` — AftenScreen 400 · 50px/1.1 · tracking -0.04em

### Case-study exhibition

**Only for:** case studies

**Observed:** Single 283.3px name under two columns of 12px metadata opens onto a wide lead photograph. A 75px summary precedes right-half 26.7px explanatory prose and an underlined visit link. Case-study gallery then alternates full and paired media with 10px gutters. A pale related-proof band with two Media cards precedes the white closing field.

**Transfer:** Explain the challenge briefly, then let a varied sequence of finished product views carry the story.

**Text style:** `case-title` — AftenScreen 400 · 283.3px/0.8 · tracking -0.05em

## Page flow

**Storyline:** Expressive promise → visual demonstration → editorial explanation → selected proof or capability chapters → human reassurance → monumental invitation.

### Broad marketing and portfolio landing

1. **Promise** — Split-word opening and a compact purpose statement.
2. **Demonstration** — Wide reel followed by Two-tone proposition.
3. **Proof** — Portfolio proof wall, then a quieter right-column archive.
4. **Reassurance** — Large two-tone organization statement with a small supporting link.
5. **Closing call** — Monumental closing on white.

**Transfer:** Use this light, media-led narrative as the default for a new product landing page.

### Detailed product or project story

1. **Identity** — Oversized single name with industry and recognition metadata.
2. **Context** — Wide lead media, large summary, right-column narrative and visit link.
3. **Demonstration** — Long exhibition of desktop, mobile, motion and material details.
4. **Related proof** — Two related media cards in a pale band.
5. **Closing call** — Shared white invitation and contact link.

**Transfer:** Replace project-specific detail with a product story while retaining the varied exhibition scale.

### Capability-led marketing

1. **Promise** — Inverse split-word opening with candid mosaic.
2. **Approach** — Label and right-column prose, then a full-width belief statement.
3. **Capabilities** — Stacked secondary subheads and plain text lists.
4. **Demonstration** — Alternating chapters with mixed-size media.
5. **Social proof** — Client names in text columns and a long right-column recognition ledger.
6. **Closing call** — Large reassurance statement then white closing field.

**Transfer:** Use for a multi-capability product suite; let named proof replace unsupported claims.

### Focused solution and concrete conversion offer

1. **Promise** — Right-biased cinematic image under navigation, with an overlapping 75px introductory statement.
2. **Proof** — Label and prose followed by sparse Showcase table rows.
3. **Conversion offer** — White focused-offer panel in a dark field.
4. **Capabilities** — Small media strip and right-column concept-to-delivery explanations.
5. **Closing call** — Page-tailored two-line invitation on white.

**Transfer:** Adapt to a focused product launch, consultation or guided trial rather than requiring the same subject matter.

### People-led trust and recruitment

1. **Identity** — Split-word opening on warm sand.
2. **Human proof** — Asymmetric candid photographic mosaic.
3. **Principles** — Left label and four right-column prose groups.
4. **Depth** — Alternating editorial chapters with photographic and experimental media.
5. **Opportunity** — Single right-column linked opening row.
6. **Closing call** — Shared white invitation.

**Transfer:** Use for an about or community story; substitute authentic human detail relevant to the new organization.

## Writing

Confident about craft but warm and collaborative about outcomes. Plain statements about usefulness sit alongside short, playful conceptual phrases; the overall voice is editorial rather than sales-heavy.

**Do not copy:** Do not reuse the brand name, contact address, project and client identities, awards, office locations, dates, proprietary artwork or factual performance claims. Source examples illustrate tone only.

- **Addressing the reader:** Use we for the maker and you or your for the reader; closing language invites joint work through let’s.
- **Rhythm:** Opening concepts are one or two words each. Utility copy is compact and uppercase; prose is sentence case, often one or two full sentences per group. Larger statements can extend over several lines without becoming slogan fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening concept pair | Two complementary disciplines or ideas joined by an ampersand. | 2–4 words plus conjunction | “Design & Technology”<br>“Services & Solutions” |
| Purpose line | A plain we statement naming what is made. | 6–12 words | “We craft digital products and brands” |
| Chapter lead | An evocative short phrase with an em dash introduces a concrete explanation. | Short phrase plus one or two sentences | “Love to explore —”<br>“Branded Experiences —” |
| Offer headline | Ask a relevant question, then offer a specific next step. | Two short sentences | “Ready to explore your AI potential?” |
| Action | Use an unembellished destination or action. | 1–3 words | “Visit site”<br>“Contact Us” |
| Closing invitation | A collaborative let’s statement, split across two balanced lines. | 5–8 words | “Let’s make something great together”<br>“Let’s unlock your AI opportunities” |

**Words and phrasing to use:** craft; build; explore; meaningful; people; together; functional; fun; collaboration

**Avoid:** revolutionary synergy; 10x everything; crush the competition; unmatched world-class solutions; urgent scarcity language

**Rules:**

- Lead with what the product enables, then explain how it is made or used.
- Name practical activities and outcomes in lists instead of decorating them with superlatives.
- Use a gray category or concept phrase to organize prose, not a bold sales claim.
- Keep conversion language personable and direct.

## Do's and Don'ts

### Do

- Keep the ordinary page pale gray and switch the ending to white.
- Pair 180px opening words with 12px metadata to preserve the scale contrast.
- Keep the right-half prose alignment on the 12-column grid.
- Use 10px horizontal gutters even when media itself is large.
- Put 26.7px captions outside the image, with muted category suffixes.
- Give editorial groups roughly 66.7px separation instead of boxed containers.
- Return dark and warm themes to the same 900px white closing composition.

### Don't

- Do not use weight 700 to compensate for large headings; the principal recipes are 400.
- Do not give ordinary media cards 16px or 24px corners; keep the subtle 4.2px rounding.
- Do not spread image colors into navigation, body copy and page backgrounds.
- Do not reduce all reading text to conventional 16px body type; the main prose is 26.7px.
- Do not use pills for categories; keep the title–dash–suffix construction.
- Do not add drop shadows to distinguish every surface; the system uses flat fields.
- Do not convert the long proof lists into raised dashboard tiles.

## Motion and responsive

### Motion

**Observed:**

- Navigation uses transform .3s cubic-bezier(0.25,0.46,0.45,0.94).
- Page background transitions use background .5s cubic-bezier(0.25,0.46,0.45,0.94).
- Closing text declares opacity 1.2s and transform 0.5s; the contact underline has a 0.5s ease drawing/undrawing animation.
- Offer button changes background over .2s cubic-bezier(0.25,0.46,0.45,0.94).

**Transfer:**

- Keep the oversized lettering as a stable readable composition while letting media carry the more expressive movement.
- Use fine underline drawing for the large contact action, rather than turning it into an animated filled control.

**Unknown:**

- Exact scroll-linked choreography, media playback timing and canvas interaction behavior.
- Focus-visible and active appearance except where explicitly described.

### Responsive

**Observed:**

- Width breakpoints are declared at 600px, 899px, 900px and 1400px.
- The statement and chapter scales use viewport formulas with minimum sizes of 30px and 28px respectively; utility text retains a 12px minimum.

**Transfer:**

- On narrow screens, preserve the two-line concept relationship and gray conjunction, but allow shorter words and a single-column media flow.
- Stack right-half prose beneath its label while keeping the contrast between tiny uppercase labels and larger sentence-case text.
- Let the closing contact line wrap or resize to fit rather than maintaining desktop half-width alignment.

**Unknown:**

- Exact mobile menu behavior, mobile hero sizing and small-screen section heights.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
