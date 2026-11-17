# Two Create — objects at exhibition scale

## Overview

An exhibition-like editorial style that pairs outsized, regular-weight grotesk typography with immaculate product photography and cinematic material studies. Warm off-white and near-black form the architecture; rich color belongs to the objects and their photographic worlds. It suits design-led products, premium physical goods and visually articulate services, with sparse text around unusually expansive media.

### Essentials

- The promise reads as a three-line verbal sculpture: regular grotesk at 111px, 1.02 line height and -0.01em tracking, left aligned within roughly 71% of the width beneath a 72px navigation band.
- Actions remain typography, not furniture: uppercase 44.4px text toggles with a plus sign, or sentence-case 44.4px contact links with a 46px diagonal arrow; no filled button silhouette or rounded corners.
- The architecture stays entirely neutral: warm #f9f7f4 and ink #0c0c0c with 1px rules; saturated color can occupy almost an entire media frame but never becomes the surrounding interface palette.
- Product proof works as an oversized diptych: a nearly full-width image around 1400px wide paired with a 690px image and a deliberately empty half-column carrying a 33.3px uppercase name over a 66.6px proposition.
- Lists become display typography rather than logo wallpaper: stacked 66.6px names on 68px lines, with a floating rectangular image interrupting the list. Use meaningful product, partner or capability names and related photography.
- Every page finishes with a monumental horizontal identity: a single-line wordmark spanning 1400px inside 20px side margins, about 108px high, bounded by hairlines with small 22.2px utility text below. Render the new identity as fitted vector lettering if no dedicated wordmark exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#0c0c0c` | `--color-ink` | text, background, link | Default text and link color on the warm light canvas; inverted page ground for editorial case studies and company information. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Light hairline | `#e3e1dd` | `--color-rule` | border | Fine boundaries across light navigation and section bands. |
| Warm off-white | `#f9f7f4` | `--color-canvas` | background, text | Default marketing canvas; reversed text on near-black pages. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark editorial and company pages | Dark hairline | `#3d3d3d` | `--color-dark-rule` | border | Fine boundaries on reversed navigation and editorial bands. |

## Typography

- **PP Neue Montreal** — All live editorial text, headings, labels and links. A regular-weight neo-grotesk with open counters, economical spacing and a distinctly unadorned editorial presence. If unavailable, use **Inter**. Use weight 400 and preserve tight display tracking; fit line breaks to the same column proportions. Font stack: "PP Neue Montreal", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | PP Neue Montreal | 400 | 111px | 1.02 | -0.01em | fixed | Primary marketing promise and company introduction. |
| proposition | PP Neue Montreal | 400 | 66.6px | 1.02 | -0.01em | size 4.627vw | Project propositions, oversized proof lists and case-study titles. |
| section-heading | PP Neue Montreal | 400 | 44.4px | 1.02 | -0.01em | size 3.085vw | Ruled section headings, contact introduction and direct contact links. |
| text-action | PP Neue Montreal | 400 | 44.4px | 1.02 | -0.01em, uppercase | size 3.085vw | Plus-prefixed work toggles and contact navigation actions. |
| project-label | PP Neue Montreal | 400 | 33.3px | 1.1 | normal, uppercase | size 2.315vw | Project names over propositions; also accordion labels on company pages. |
| utility | PP Neue Montreal | 400 | 22.2px | 1.1 | normal | size 1.543vw | Footer links, copyright line and short service credits. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| case studies and company information | body-editorial | PP Neue Montreal | 400 | 33.3px | 1.1 | normal | size 2.315vw | Long editorial paragraphs, quotations and related-work propositions. |
| case studies | attribution | PP Neue Montreal | 400 | 22.2px | 1.1 | normal, uppercase | size 1.543vw | Quote authors and small related-project identifiers. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The hierarchy comes from scale rather than weight: all editorial recipes stay at 400.
- Display, proposition and section-heading share 1.02 line height and -0.01em tracking. Smaller editorial text opens to 1.1 and normal tracking.
- Uppercase is reserved for project identifiers and short actions; propositions remain sentence case. A project label is substantially larger than a conventional eyebrow.
- The closing identity is vector artwork rather than a live-text heading. Fit the new identity to the full horizontal band without using the body text recipe.

## Layout

**Density:** Airy at chapter scale and tight within text groups: near-touching headline lines contrast with long media-led pauses.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 10px | Inner column padding; paired with adjacent column padding to create a 20px separation. | fixed |
| 20px | Desktop side margins, top inset beneath navigation and separation between media rows. | fixed |
| 14.4px | Top inset of narrow section-heading bands. | 1vw |
| 36px | Right-hand arrow allowance on contact links. | 2.5vw |
| 40px | Paragraph separation in editorial introductions. | fixed |
| 50px | Breathing space between major projects in the light portfolio. | fixed |
| 180px | Large chapter inset and closing contact/footer lead-in. | fixed |
| 360px | Pause between images, quotations and related-work chapters in case studies. | fixed |

### Containers and grids

- **fluid editorial canvas**: side padding 20px. No centered maximum width: text and navigation track the viewport, leaving 1400px of content at 1440px.
- **half-column diptych**: 2 columns · gap 20px · side padding 20px. Two 690px content columns at desktop; imagery can bleed to the edge while text retains its gutter.
- **inset media stage** (only for case studies): max width 1080px. Case-study image or video set at three quarters of the desktop viewport, centered or offset to one edge.
- **statement and disclosure** (only for company and capability pages): 2 columns · gap 118px · side padding 20px. A large statement at left and a narrow, roughly 453px disclosure list at right; the list takes about one third of the viewport.

## Corner radius

| Element | Radius |
| --- | --- |
| media and actions | 0px |

## Surfaces and depth

### Surfaces

#### Warm canvas · level 0

**Use:** Default marketing page ground.

**CSS:** `background: #f9f7f4; color: #0c0c0c`

**Observed:** A flat, uninterrupted paper-colored field continues through hero, portfolio, proof list, contact and footer.

**Transfer:** Keep all interface color neutral; let photography supply the shifts in atmosphere.

#### Ruled band · level 0

**Use:** Navigation and chapter boundaries.

**CSS:** `background: #f9f7f4; border-bottom: 1px solid #e3e1dd`

**Observed:** Hairlines run to the viewport edge. The dark variant uses the dark hairline role against near-black.

**Transfer:** Use a rule to mark a change in reading mode, not a boxed surface around every object.

#### Reversed canvas · level 0

**Only for:** case studies and company pages

**Use:** Immersive editorial and company information ground.

**CSS:** `background: #0c0c0c; color: #f9f7f4`

**Observed:** The same grid and typography reverse without raised panels, shadows or rounded containers.

**Transfer:** Choose this as a whole-page editorial theme rather than interleaving decorative dark cards into the default canvas.

## Components

### Split navigation

**Use:** Persistent site orientation.

**CSS:** `position: fixed; height: 72px; width: 100%; z-index: 400; background: #f9f7f4; border-bottom: 1px solid #e3e1dd; overflow: hidden`

**Observed:** Two typographic identity/navigation anchors sit at opposite outer edges with 20px gutters. Initial identity wording gives way to Work and About while browsing. Lettering is graphic, not a set of small menu items. Reversed pages retain the same construction.

**States:** Declared: hover text-decoration none.

**Transfer:** Use one short identity or primary destination per edge, keeping the center empty.

### Project diptych link

**Use:** Large linked proof block combining media and a concise proposition.

**CSS:** `display: flex; position: relative; flex-wrap: wrap; justify-content: space-between; color: #0c0c0c`

**Text style:** `proposition` — PP Neue Montreal 400 · 66.6px/1.02 · tracking -0.01em

**Observed:** A single linked block contains a wide media frame, a half-width detail frame and a text half-column. The Project label sits immediately over the proposition with a 5px separation; text is padded away from its neighboring image. Left/right media placement alternates.

**States:** Declared: hover text-decoration none.

**Transfer:** Give each proof item one wide context view and one detailed view; use a diagram or an art-directed interface close-up if the product is not physical.

### Ruled section header

**Use:** Name a chapter without a separate title panel.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; padding-top: 14.4px; padding-right: 10px; padding-left: 10px`

**Text style:** `section-heading` — PP Neue Montreal 400 · 44.4px/1.02 · tracking -0.01em

**Observed:** A 72px desktop band spans the viewport, with the title aligned to the text gutter and a short action at the far right where needed.

**Transfer:** Keep chapter names literal and brief.

### Plus text toggle

**Use:** Open more proof or jump to contact.

**CSS:** `color: #0c0c0c; text-transform: uppercase; text-align: center; background: transparent; border-radius: 0px`

**Text style:** `text-action` — PP Neue Montreal 400 · 44.4px/1.02 · tracking -0.01em · uppercase

**Observed:** A simple plus precedes the uppercase label at the far edge of a ruled header. It is a typographic action, not an outlined or filled button.

**Transfer:** Use the same treatment for a concise secondary disclosure, with no pill container.

### Display proof list

**Use:** An emphatic inventory of relevant names or capabilities.

**CSS:** `position: relative; color: #0c0c0c`

**Text style:** `proposition` — PP Neue Montreal 400 · 66.6px/1.02 · tracking -0.01em

**Observed:** One name per roughly 68px line, flush left, without logo tiles or bullets. A rectangular photographic preview floats above and partly overlaps the textual field.

**Transfer:** Use real partner, collection or capability names and connect each image to the relevant name rather than introducing decorative thumbnails.

### Direct contact link

**Use:** High-visibility conversion in the closing contact section.

**CSS:** `position: relative; padding-right: 36px; color: #0c0c0c`

**Text style:** `section-heading` — PP Neue Montreal 400 · 44.4px/1.02 · tracking -0.01em

**Observed:** Email and telephone stack as plain text. A diagonal up-right arrow sits after the email; the dark variant reverses text and icon together.

**States:** Declared: hover text-decoration none.

**Transfer:** Make the actual destination the label rather than adding a generic sales button.

### Monumental identity footer

**Use:** The signature closing artwork on every page.

**CSS:** `padding-top: 180px; background: #f9f7f4; overflow: hidden`

**Observed:** A full-width single-line vector identity appears between hairlines, inset 20px on both sides. Its graphic box is 1400px by 108px at desktop. Below it, copyright stays left and two utility links align right. Dark editorial pages invert this exact composition.

**Transfer:** Build fitted vector lettering for the new identity so the band still feels monumental even with a shorter name.

### Utility underline link

**Use:** Small footer destinations.

**CSS:** `color: #0c0c0c; background-image: linear-gradient(#0c0c0c, #0c0c0c); background-size: 0px 1px; background-position: 0px 100%; background-repeat: no-repeat; transition: background-size 0.45s cubic-bezier(0.645, 0.045, 0.355, 1)`

**Text style:** `utility` — PP Neue Montreal 400 · 22.2px/1.1

**Observed:** Two compact inline links occupy the right side of the footer, with 15px between list items. The underline is a background treatment, not a filled link surface.

**States:** Declared: hover text-decoration none.

### Disclosure row

**Only for:** company and capability pages

**Use:** Compact explanations beside a large statement.

**CSS:** `position: relative; color: #f9f7f4; margin-top: 10.8px`

**Text style:** `project-label` — PP Neue Montreal 400 · 33.3px/1.1 · uppercase

**Observed:** Uppercase labels form a right-hand stack of approximately 50px rows. Circled numerals distinguish stages; service names omit numbering. Hairlines separate rows, with a small downward arrow aligned at the far right.

**Transfer:** Use stages or service categories appropriate to the product. Keep the explanation in the disclosure rather than making a card grid.

### Related work pair

**Only for:** case studies

**Use:** Continue exploration at the end of a detailed narrative.

**CSS:** `position: relative; padding-right: 10px; padding-left: 10px; margin-top: 20px`

**Text style:** `body-editorial` — PP Neue Montreal 400 · 33.3px/1.1

**Observed:** Two equal 690px by 431px images sit under a ruled section header; sentence-case proposition follows each image with a roughly 15px gap, then a smaller uppercase project identifier. No card border, backing or button is added.

**Transfer:** Offer two related products or stories, preserving image-first hierarchy.

## Imagery and graphics

### Material-led product tableau

**Use:** The dominant proof language across the light marketing canvas.

**Observed:** Highly finished photographs and 3D renders isolate packaging, bottles, tools and printed matter. Wide scenes alternate with square or portrait close-ups; reflective chrome, brushed metal, embossed paper, tinted glass and satin plastic are described through controlled studio light. Backgrounds belong to each product world: cool pale gray, muted green, lilac or deep charcoal. Media occupies far more page area than copy.

**Transfer:** Create a wide arrangement and a detail portrait for each new product. Use one coherent backing, believable contact shadows and light that reveals material. The minimum equivalent is excellent studio photography of a real object or a tightly framed, high-resolution product/interface detail, not a generic abstract illustration.

### Floating photographic preview

**Use:** A visual interruption within a large display proof list.

**Observed:** A borderless rectangular image floats in the middle-right of the list, sometimes overlapping names. Examples include stacked pale pink cartons, clear bottles and printed fabric. Color and photographic detail contrast with the plain surrounding typography.

**Transfer:** Pair each relevant name with one image in a consistent floating frame; ensure names remain accessible without relying on the preview.

**Build:** Place the list in a relative container and layer an absolutely positioned rectangular image above it, centered around the middle third of the viewport. Use a roughly 430px-wide frame on the light desktop treatment, object-fit cover, no border, radius or shadow; move the preview beside or below the list when space is insufficient.

### Identity as closing artwork

**Use:** Required signature graphic in the closing footer.

**Observed:** A very wide, all-capital neo-grotesk wordmark has thin regular strokes and fills almost the entire content width. It is pure black on paper or paper on black, with no emblem or texture.

**Transfer:** Use the new brand name or a concise identity line as one fitted horizontal artwork.

**Build:** Set uppercase regular grotesk lettering in an SVG with a viewBox fitted to its actual glyph outlines. Scale the SVG to the content width within 20px side gutters; use currentColor fill and preserve its proportions. Place it in a 150px desktop band with approximately 20px above and below a 108px-high mark, bounded by 1px rules. Adjust the artwork proportions for the new lettering rather than stretching individual glyphs.

### Golden geological still life

**Only for:** warm-metal luxury case studies

**Use:** An immersive material story on the reversed canvas.

**Observed:** Brushed and polished gold containers sit among coarse dark rocks, sometimes in exploded lid-and-vessel arrangements. Warm low light catches metal edges and illuminates crevices against a smoky brown-gray photographic background. Paired images have unequal scale, and one large centered overhead image follows.

**Transfer:** Use a material contrast meaningful to the new object: machined surface against rough mineral, precise geometry against organic texture. A single real object on a textured dark plinth under warm side light is a sufficient version; do not replace the scene with a gold CSS gradient.

### Cobalt and chrome study

**Only for:** cool-material luxury case studies

**Use:** A more saturated editorial product narrative.

**Observed:** Cobalt glass and mirrored silver closures are shown on intense blue-to-navy studio backings. Macro views cut objects beyond the frame, while exploded assemblies and angled bottles use reflective surfaces and broad white specular highlights. Frames alternate between full-bleed, half-width and centered 1080px media.

**Transfer:** Choose one deep hue intrinsic to the new product and preserve its pairing with crisp reflective highlights. Show material detail, assembly and the whole object using the same photographic lighting world.

### Icons

**Observed:** The icon vocabulary is restricted to simple directional arrows and plus signs. Contact uses a 46px filled SVG arrow turned up-right; company disclosures use 20px by 26px downward arrows. Icons share the text color and sit directly beside or at the far end of an action.

**Transfer:** Use minimal single-direction glyphs rather than a feature-icon library. Match the regular typographic stroke impression and avoid circles or badges around them.

## Section recipes

How recurring sections are built.

### First screen: Typographic promise opening

**Observed:** The Warm canvas sits behind a fixed Split navigation. Beneath its 72px band, a regular grotesk promise starts with 20px top and side insets, spanning three tight lines inside about 71% of the viewport. Display type is 111px with 1.02 line height and -0.01em tracking. Its right side remains open; a 180px breathing space follows the text. A Ruled section header begins around 612px down, followed by the leading edge of a nearly full-width cinematic product image around 700px. Within the first 900px the viewer sees navigation, the entire promise, the proof chapter title and only the top of the first media scene. There is no support paragraph, foreground product cutout or hero button.

**Transfer:** Write a compact, rhythmic proposition with deliberate three-line breaks and put the first compelling proof scene immediately after the open typographic field. Without product photography, use a sharply art-directed interface detail, diagram or real use-context image. Detailed case studies instead open with a 66.6px title in the left half, service credits below it and 33.3px editorial paragraphs in the right half on the Reversed canvas. Company introductions use the Display recipe in a broad dark field with a supporting editorial paragraph.

**Avoid:** Do not turn the opening into a centered headline with a pair of pill CTAs, or place a decorative gradient behind the promise.

**Text style:** `display` — PP Neue Montreal 400 · 111px/1.02 · tracking -0.01em

### Alternating proof diptych

**Observed:** The Project diptych link joins one wide context scene and one half-width detail scene to a half-column text block. Project label is uppercase above the much larger proposition. Alternate which side holds the image and which holds the text; use 20px inner gaps and roughly 50px between projects. Warm canvas stays visible around all media.

**Transfer:** Build chapters around distinct benefits or use cases. Give each a different photographic composition while keeping the text grid stable.

**Text style:** `proposition` — PP Neue Montreal 400 · 66.6px/1.02 · tracking -0.01em

### Display inventory with preview

**Observed:** A Ruled section header introduces the Display proof list, with Plus text toggle on the right. Names stack with virtually no inter-row whitespace; a Floating photographic preview introduces visual specificity without converting the list to tiles.

**Transfer:** Use this device for credible names, product families or capabilities. It can replace a conventional logo wall.

**Text style:** `proposition` — PP Neue Montreal 400 · 66.6px/1.02 · tracking -0.01em

### Direct closing invitation

**Observed:** A 180px top pause leads to a ruled contact area. A short invitation uses Section-heading and wraps into a compact left-aligned block; stacked Direct contact links follow, leaving most of the right side empty. The Monumental identity footer follows after another generous pause. Reversed company pages retain the same geometry; detailed case studies substitute Related work pair before the footer.

**Transfer:** Finish a landing page with an unambiguous human contact route or equally direct destination. Preserve the wide empty right field and the large identity sign-off rather than adding a multi-column sitemap.

**Text style:** `section-heading` — PP Neue Montreal 400 · 44.4px/1.02 · tracking -0.01em

### Editorial media chapter

**Only for:** case studies

**Observed:** On Reversed canvas, major media chapters are separated by 360px pauses. One image may bleed across 1440px, another sit at 1080px centered or edge-aligned, and another pair a 710px image with a smaller 453px image. Text-and-image chapters use opposing half columns with 33.3px editorial copy, sometimes inset farther from the image than the standard gutter.

**Transfer:** Vary scale to move from whole-object understanding to material detail; leave negative space as part of the narrative instead of adding UI chrome.

**Text style:** `body-editorial` — PP Neue Montreal 400 · 33.3px/1.1

### Inset quote and prose proof

**Only for:** case studies

**Observed:** A quotation occupies only the right 690px half, leaving the entire left half empty. Body-editorial text is followed by uppercase Attribution with about 30px separation; the chapter is surrounded by 360px pauses. Quantified improvements elsewhere stay inside the same editorial paragraphs, not oversized statistic cards.

**Transfer:** Use a short attributable endorsement or a substantiated outcome. Keep numerical proof in a readable sentence beside the relevant product scene.

**Text style:** `body-editorial` — PP Neue Montreal 400 · 33.3px/1.1

### Statement with disclosure stack

**Only for:** company and capability pages

**Observed:** A Ruled section header sits above a broad 66.6px left statement and a narrow right stack of Disclosure rows. The right stack takes about one third of the viewport, separated by an open gutter. A 180px chapter pause follows the process treatment; services use the same arrangement.

**Transfer:** Explain a process, product range or service system with a large unifying statement and concise expandable categories.

**Text style:** `proposition` — PP Neue Montreal 400 · 66.6px/1.02 · tracking -0.01em

## Page flow

**Storyline:** Verbal promise → expansive visual proof → named credibility or explanatory chapters → direct continuation → monumental identity sign-off.

### Marketing overview that establishes an approach through a curated body of visual proof

1. **Promise** — Three-line typographic statement in a warm open field.
2. **Product demonstration** — Repeated wide-and-half-width media diptychs with uppercase identifiers and large propositions.
3. **Social proof** — Oversized name inventory with floating photographic previews and a more-work toggle.
4. **Closing call** — Plainspoken invitation, direct email and telephone, then full-width identity and utility links.

**Transfer:** Adapt the number and order of proof chapters to the product; preserve the contrast between immense media and concise editorial labels.

### A focused material-led case study

1. **Context** — Dark two-column opening: title and service credits left, two editorial paragraphs right.
2. **Product demonstration** — Unequal paired portraits, a centered overhead image, then a text-and-image explanation.
3. **Validation** — Award information in prose and a right-half quotation.
4. **Continuation** — Two related stories followed directly by reversed identity footer.

**Transfer:** Use a compact visual narrative when one material or design decision explains the product.

### An extended product-development story

1. **Context** — Two-column dark introduction with title, service credits and product history.
2. **Product demonstration** — Full-width family portrait, explanatory half-column chapter and extreme material detail.
3. **Validation** — Isolated right-half quotation.
4. **Capability proof** — Exploded assembly, sustainability outcomes in prose, centered video and unequal detail pair.
5. **Continuation** — Related-work pair followed by the same reversed footer, without the large contact invitation.

**Transfer:** Use a longer narrative for products needing assembly, lifecycle or performance explanation; keep quantitative outcomes integrated with the product imagery.

### Explain the organization, its credibility and how engagement works

1. **Positioning** — Large reversed introduction with a substantial supporting paragraph under a narrow chapter/action band.
2. **Social proof** — Display-sized name inventory with photographic interruption.
3. **Objection handling** — Process statement and stage disclosures, followed by a services statement and category disclosures.
4. **Closing call** — Direct contact invitation followed by the monumental reversed identity footer.

**Transfer:** For an organization or capability page, emphasize a clear point of view and a navigable method rather than adding portraits or dashboard cards.

## Writing

Confident, cultured and commercially literate, with design decisions expressed in tangible material and business terms. The writing is restrained but not impersonal; concise portfolio propositions sit beside fuller editorial explanations.

**Do not copy:** Do not reuse the studio name or wordmark, client and project names, contact details, quoted endorsements, awards, experience claims or sustainability figures. Replace them with the new brand's identity and substantiated claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use first-person plural for the organization and its work; describe products and outcomes directly. Address the reader gently in invitations rather than through repeated second-person sales language.
- **Rhythm:** Short, mostly three-to-eight-word propositions contrast with complete editorial paragraphs. Headlines are sentence case except labels and short navigation actions; punctuation is restrained and exclamation marks are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A plain declarative statement with verbal repetition or parallel structure. | About 8–14 words | “We create products for brands & brands for products” |
| Proof proposition | A concise outcome or cultural position, not a list of features. | 3–8 words | “Swiss precision engineered luxury”<br>“A more sustainable everyday”<br>“An object of pure decadence” |
| Editorial explanation | Connect a concrete design decision to the material or lifecycle result. | One developed paragraph per decision | “Packs are now more sustainable with a 15% reduction in weight, plus inclusion of 30% recycled content.” |
| Section heading | Literal noun phrase that names the content. | 1–2 words | “Selected work”<br>“Related work”<br>“Process” |
| Closing invitation | A polite practical invitation followed by the direct destination. | One short sentence | “To discuss a project or for more information, contact us:” |
| Action | Literal continuation or contact wording; no hype. | 1–2 words or a destination | “More Work”<br>“Contact” |

**Words and phrasing to use:** material; form; detail; identity; collection; innovation; industry leader; sustainable; working closely; elevating

**Avoid:** game-changing; supercharge; unlock your potential; revolutionary platform; don't miss out; !!!

**Rules:**

- Give each proof image one short proposition rather than a paragraph of selling points.
- Describe finish, geometry, production or performance with concrete nouns.
- Attach measurable claims to their actual product decision and state only defensible outcomes.
- Let chapter headings remain functional; reserve expressive language for the proposition.
- Use British editorial spelling where appropriate.

## Do's and Don'ts

### Do

- Keep every live-text role at weight 400; let 111px, 66.6px and 44.4px establish hierarchy.
- Keep the light marketing architecture at #f9f7f4 with #0c0c0c text.
- Align text to 20px outer gutters and preserve the 20px separation between half columns.
- Pair wide scenes with material details rather than reusing the same image at two sizes.
- Retain 180px and 360px pauses at the appropriate chapter scale.
- Use the required full-width closing identity artwork even on short pages.
- Set small footer destinations at 22.2px and keep them subordinate to the wordmark.
- Show outcome numbers inside editorial prose when using the dark case-study variant.

### Don't

- Do not introduce a bright interface accent simply because photography contains that hue.
- Do not turn the 33.3px project labels into tiny tracked mono eyebrows.
- Do not add bold headline cuts to manufacture hierarchy.
- Do not round media frames or raise them with drop shadows; their edges stay square.
- Do not shrink the 66.6px name inventory into a conventional tiled logo strip.
- Do not replace plain text actions with filled conversion buttons.
- Do not add decorative statistics dashboards to the prose-led case-study language.
- Do not mix unrelated photographic lighting styles inside one product chapter.

## Motion and responsive

### Motion

**Observed:**

- Text and media visibility elements declare opacity and transform transitions of 0.7s ease-in-out.
- Navigation declares background-color and border-bottom transitions of 0.5s.
- Contact links declare padding-left 0.3s; utility links declare background-size 0.45s cubic-bezier(0.645, 0.045, 0.355, 1).
- Navigation wording changes between the initial identity and browsing destinations; photographic previews appear over name lists.

**Transfer:**

- Keep reveals subordinate to the objects and type. Use the declared visibility transition for chapter text and media rather than bouncing or spinning the content.
- Retain the underline-based small-link treatment and simple directional cues.

**Unknown:**

- Exact reveal trigger positions and preview pointer behavior are not established.
- No focus-visible or active treatment is established.

### Responsive

**Observed:**

- Typography uses viewport-based sizes for propositions, section headings, project labels, editorial body and utility text.
- Styles include breakpoints at 768px, 992px, 1200px and 1400px, among others; no narrow-screen arrangement is established.

**Transfer:**

- On narrow screens, stack the media and text halves in reading order while preserving square corners and the distinction between context and detail images.
- Fit the closing identity to available width as vector artwork, keeping it on one line.
- Move floating list previews beside or below their associated names when overlap would obstruct reading.
- Keep small text readable instead of allowing viewport formulas to reduce it indefinitely.

**Unknown:**

- Exact mobile type floors, gutter changes, navigation replacement and disclosure-open layouts are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
