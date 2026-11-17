# Endel — nocturnal signal sculptures

## Overview

A black-on-black product world where fine white signals emerge from sculpted darkness. Regular-weight grotesk typography, charcoal fades, diagrammatic line art and low-key device imagery combine a scientific feeling with a gently surreal mood. The result suits adaptive technology, creative tools and personal services, with spacious chapter introductions balanced by substantial explanatory cards.

### Essentials

- Headlines behave like calm labels above an instrument, not advertising shouts: regular 400 grotesk, 60px/72px opening title and 44px/56px centered chapter headings with 0.3px tracking.
- The opening is a centered promise over a dark product constellation: 564px support measure, 20px title-to-copy gap, 40px to a 56px outlined action, and a nearly full-width monochrome object stage filling the lower first screen.
- Black is the environment, not a panel: #000000 canvas, #ffffff headings, #bfbfbf explanation and #181818-to-transparent card fades. Saturation belongs only inside a narrow artwork collection band; the surrounding page and controls remain neutral.
- Actions are softly squared instruments: 12px corners, 2px white outlines on #262626, 22px regular labels; the compact 44px header action alone carries a 15px white halo.
- Fine signals make the technology tangible: white curves, grids, radial rays and small orbiting symbols sit over charcoal light pools. Include this diagrammatic imagery even without device assets, using original SVG curves and a simple dark product frame.
- Proof can become artwork: oversized white numerical marks with curved gradient arrows sit in 270px-wide units with 18px/24px captions, while human proof uses fading charcoal cards rather than bright quotation panels.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal white | `#ffffff` | `--color-primary` | text, border, accent | Titles, action labels, thin diagrams, action outlines and the compact conversion halo. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control charcoal | `#262626` | `--color-control` | surface, action | Button fills and accordion hover. |
| Absolute black | `#000000` | `--color-canvas` | background | Continuous page canvas and the destination of fades. |
| Fade charcoal | `#181818` | `--color-fade-top` | surface | Top of explanatory and review card gradients; fades to transparent black. |
| Accordion charcoal | `#191919` | `--color-panel` | surface, border | Solid question rows and the thin closing divider. |
| Focus ring gray | `#666666` | `--color-focus` | border | Six-pixel focus-visible shadow around actions. |
| Input edge | `#808080` | `--color-edge` | border, action | Input outlines; button hover uses CSS gray, the same visible value. |
| Explanation gray | `#bfbfbf` | `--color-secondary` | text | Supporting prose, evidence captions and secondary navigation. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial entry screens | Editorial control gray | `#4d4d4d` | `--color-editorial-control` | action | Filled entry action without a white outline. |

## Typography

- **apercuPro** — All standard marketing titles, paragraphs, captions and controls. Open, rounded grotesk with a single regular-weight voice; friendly rather than mechanical. If unavailable, use **DM Sans**. Use 400 throughout; preserve the open counters and measured line breaks. Font stack: "apercuPro", "DM Sans", Arial, sans-serif.
- **Roboto** (only for editorial entry screens) — Centered entry statement and action. Plain neo-grotesk with neutral regular forms. Font stack: "Roboto", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | apercuPro | 400 | 60px | 1.2 | 0.0058em | Short centered product name or opening promise. |
| heading | apercuPro | 400 | 44px | 56px | 0.008em | Centered chapter introductions, usually one or two lines. |
| footer-heading | apercuPro | 400 | 36px | 42px | 0.0097em | Newsletter heading. |
| body | apercuPro | 400 | 22px | 28px | normal | Lead explanations, feature prose, question rows and inline conversion links. |
| button | apercuPro | 400 | 22px | 1 | normal | Full-size conversion and reveal controls. |
| body-small | apercuPro | 400 | 18px | 24px | normal | Small benefit cards, reviews, statistics captions and footer links. |
| control-small | apercuPro | 400 | 16px | 1 | normal | Compact header controls and form labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial entry screens | editorial-title | Roboto | 400 | 40px | 1.125 | normal | Centered multiline statement beneath a symbol. |
| editorial entry screens | editorial-action | Roboto | 400 | 24px | 1.15 | normal | Entry action label. |

**Notes:**

- Keep the entire marketing voice at weight 400; contrast comes from scale, white versus gray and alignment, not bold emphasis.
- Centered titles retain slight positive tracking; left-aligned card titles use normal tracking. Do not tighten the whole scale into a fashionable condensed display.
- Feature titles are as prominent as chapter titles but have normal line height and left alignment; captions step down to 18px rather than becoming tiny interface text.

## Layout

**Density:** Airy chapter rhythm with comfortable, prose-heavy cards; black intervals make dense explanations feel unhurried.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label or arrow-to-link separation. |
| 12px | Review content stacks and footer link rhythm. |
| 16px | Compact benefit and review card padding. |
| 20px | Heading-to-support and feature text stack gaps. |
| 24px | Main grid gutters, large-card padding and question-row padding. |
| 40px | Opening support-to-action separation. |
| 48px | Chapter introduction to its media or feature grid. |
| 64px | Desktop container side padding and major group spacing. |
| 100px | Separation before recurring chapter introductions and footer main-block bottom space. |
| 120px | Opening top space and gap before the closing footer. |

### Containers and grids

- **content**: max width 1152px · side padding 64px. Centered content region; at a 1440px viewport its usable content edges are 144px from either side. Treat the 64px padding as additional outer container protection, not as the final viewport inset.
- **chapter-intro**: max width 760px. Centered title and paragraph block, narrower than grids.
- **hero-support**: max width 564px. Two-line opening explanation centered under the title.
- **feature-pair**: 2 columns · gap 24px. Two equal 564px image-and-text columns inside the content region.
- **proof-grid**: 4 columns · gap 24px. Four 270px statistics or small benefit cards.
- **review-waterfall**: 3 columns · gap 24px. Three 368px columns with uneven review heights and a masked bottom edge.
- **newsletter**: max width 466px. Right-hand footer form alongside compact navigation columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls-and-questions | 12px |
|  | feature-text-panel | 8px |
|  | media-and-reviews | 20px |
|  | play-controls | 50% |
| editorial entry screens | editorial-action | 10px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| header-conversion-halo | `0px 0px 15px 0px #ffffff` | The compact main conversion action in navigation, not every button. |

### Surfaces

#### Black environment · level 0

**Use:** Continuous page backing.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Dark media merges into the canvas without alternating light chapter bands.

**Transfer:** Keep the environment continuous across product chapters.

#### Dissolving card · level 1

**Use:** Feature text and small benefit panels.

**CSS:** `background: linear-gradient(#181818 0%, rgba(0, 0, 0, 0) 100%); border-radius: 8px`

**Observed:** The top has a visible soft charcoal edge; the bottom disappears into the page. Small benefit panels use 12px corners and review panels use 20px.

**Transfer:** Use a restrained vertical fade instead of a floating elevated card.

#### Question panel · level 1

**Use:** Accordion titles and their answer regions.

**CSS:** `background: #191919; border-radius: 12px`

**Observed:** The solid surface is reserved for practical information rather than every content block.

**Transfer:** Use for expandable objections or documentation-like details.

#### Navigation veil · level 2

**Use:** Fixed header over moving page content.

**CSS:** `background: linear-gradient(#000000 0%, rgba(0, 0, 0, 0.65) 50%, rgba(0, 0, 0, 0) 100%)`

**Observed:** A black veil dissolves downward rather than forming a hard toolbar edge.

**Transfer:** Let dark imagery remain faintly visible underneath without a glass blur.

## Components

### Navigation

**Use:** Persistent route selection and conversion.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 72px; display: flex; justify-content: center; background: linear-gradient(#000000 0%, rgba(0, 0, 0, 0.65) 50%, rgba(0, 0, 0, 0) 100%); z-index: 200`

**Text style:** `body-small` — apercuPro 400 · 18px/24px

**Observed:** A 40px outlined symbol sits at the left, topic links occupy the center, and a glowing main action plus a plain sign-in control sit at the right.

**Transfer:** Use a short topic navigation rather than a sprawling menu.

### Primary button

**Use:** Opening conversion and content reveal actions.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #262626; color: #ffffff; border: 2px solid #ffffff; border-radius: 12px; height: 56px; padding: 0px 24px; gap: 8px; transition: background-color 0.2s, border-color 0.2s`

**Text style:** `button` — apercuPro 400 · 22px/1

**Observed:** The opening control is label-width, 172px in its short-label form; reveal and community controls expand to 368px. Newsletter submission retains the same shape but its border matches the fill.

**States:** Declared: hover background-color gray and border-color gray; focus-visible box-shadow rgb(102, 102, 102) 0px 0px 0px 6px.

### Compact conversion

**Use:** Main header action.

**CSS:** `background: #262626; color: #ffffff; border: 2px solid transparent; border-radius: 12px; height: 44px; padding: 0px 12px; box-shadow: 0px 0px 15px 0px #ffffff`

**Text style:** `control-small` — apercuPro 400 · 16px/1

**Observed:** The luminous edge differentiates the main conversion from the adjacent plain dark sign-in button.

**States:** Declared: hover background-color gray and border-color gray; focus-visible box-shadow rgb(102, 102, 102) 0px 0px 0px 6px.

### Arrow text link

**Use:** Low-friction feature actions beneath explanations.

**CSS:** `color: #ffffff; display: inline-flex; gap: 8px`

**Text style:** `body-small` — apercuPro 400 · 18px/24px

**Observed:** A northeast text arrow follows a short action; larger feature cards use the 22px body recipe for their action. These links do not sit in button boxes.

**States:** Declared: hover unspecified; focus-visible outline 2px solid var(--color-focus-ring), outline-offset 2px and box-shadow rgb(102, 102, 102) 0px 0px 0px 6px.

### Feature card

**Use:** Detailed product capabilities in pairs.

**CSS:** `display: flex; flex-direction: column; border-radius: 20px; overflow: hidden`

**Text style:** `heading` — apercuPro 400 · 44px/56px · tracking 0.008em

**Observed:** A 564×360px illustration or product image leads into a Dissolving card text panel with 24px padding, then title, explanation and an Arrow text link. Text stacks use 20px gaps.

**Transfer:** Pair a mechanism illustration with a practical use case rather than two unrelated sales slogans.

### Review card

**Use:** Dense human proof.

**CSS:** `background: linear-gradient(#181818 0%, rgba(0, 0, 0, 0) 100%); border-radius: 20px; padding: 16px`

**Text style:** `body-small` — apercuPro 400 · 18px/24px

**Observed:** An avatar and reviewer name precede stars, a brief title and an unabridged-looking paragraph. Unequal heights form a three-column waterfall; a black bottom fade carries the centered Primary button.

**Transfer:** Keep quotes legible and naturally varied rather than equal-height testimonial tiles.

### Question row

**Use:** Expandable practical questions.

**CSS:** `background: #191919; color: #ffffff; border-radius: 12px; padding: 24px; display: flex; align-items: center; justify-content: space-between; gap: 24px`

**Text style:** `body` — apercuPro 400 · 22px/28px

**Observed:** A full-width question sits left and a thin downward chevron sits right. Closed rows are 76px high, separated by 24px; expanded answers use gray body prose and inline links.

**States:** Declared: hover background-color #262626; focus-visible box-shadow rgb(102, 102, 102) 0px 0px 0px 6px.

### Email field

**Use:** Newsletter signup within the footer.

**CSS:** `background: #000000; border: 2px solid #808080; border-radius: 12px; height: 56px; padding: 16px 12px 14px 12px; width: 100%`

**Text style:** `control-small` — apercuPro 400 · 16px/1

**Observed:** The persistent label is outside and above the input, with 6px below it. A full-width dark Primary button follows 24px below the field.

**Transfer:** Keep the field visibly outlined rather than filling it with a lighter card color.

### Footer navigation

**Use:** Utility ending beneath the primary story.

**CSS:** `display: flex; align-items: center; gap: 24px; border-top: 1px solid #191919; padding: 24px 0px; color: #bfbfbf`

**Text style:** `body-small` — apercuPro 400 · 18px/24px

**Observed:** Compact legal links wrap at the left with 16px horizontal spacing; a line of 24px social icons occupies the right with 20px gaps. This strip ends the page without a giant conversion slogan.

### Editorial entry action

**Only for:** editorial entry screens

**Use:** Enter a focused editorial experience.

**CSS:** `background: #4d4d4d; color: #ffffff; height: 60px; padding: 0px 60px; border-radius: 10px`

**Text style:** `editorial-action` — Roboto 400 · 24px/1.15

**Observed:** A simple filled control beneath the centered statement, without the marketing button's outline or halo.

**States:** Declared: hover background rgb(51, 51, 51); focus-visible unspecified.

## Imagery and graphics

### Monochrome product constellation

**Use:** The main opening object stage and larger demonstration scenes.

**Observed:** Dark phones, watches, screens and hardware overlap in a wide, low-key arrangement. Thin silver rim light reveals black glass, satin metal and rounded silhouettes. A central landscape of layered charcoal waves, pinprick stars and radiating white lines ties the objects together; bases fade completely into black. It occupies most of the lower first viewport while the title remains unobstructed above.

**Transfer:** Stage the new product's actual interface or object in a similarly monochrome composition. Without photorealistic assets, use one dark rounded product frame with a crisp original interface and a broad radial-line field behind it; retain the cinematic scale rather than substituting a stock photograph.

**Build:** Use an SVG behind the object: several low-amplitude overlapping hill paths filled with #191919 and black at varied opacity, sparse 1px white dots at 0.2–0.6 opacity, and 16–24 hairline rays spreading upward from a low center. Fade the sides and bottom with black gradient masks. Add narrow white rim highlights at 0.15–0.4 opacity to a black rounded product frame; avoid a bright outer glow around the whole object.

### Signal diagrams

**Use:** Recurring feature media; a signature device across a new page.

**Observed:** White and gray sine curves, axes, dashed guides, circular state symbols and connecting lines sit on dark grids or a soft graphite light pool. Media is 564×360px in paired cards, using rounded upper corners and no colorful chart legend. Bright strokes are sparse enough that most of each panel remains dark.

**Transfer:** Draw the new product's inputs, relationships or transformations as an abstract instrument diagram. A few meaningful curves and symbols are the minimum acceptable artwork.

**Build:** Create a 564×360 SVG with a #000000 backing and a radial gradient from #262626 at the upper center to black at the edges. Lay a 54px square grid at 0.15 white opacity; draw 1–2px white curves with dim echo curves at 0.2 opacity. Add one small white node, short arrowheads and dashed vertical guides, or replace the grid with 6–8 outlined circular symbols connected by fine radial spokes.

### Sculptural proof marks

**Use:** Quantified evidence alongside short captions.

**Observed:** Four 270×166px graphic areas show very large white numerals and compact suffixes. Curved arrows arc above the values, bright at their triangular head and dark at their tail; one downward arrow reverses the visual direction. Gray captions and small source markers sit beneath on the bare canvas.

**Transfer:** Use only substantiated metrics. Keep the high-contrast numeral and directional arc treatment; if numerical proof is unavailable, use a concise factual milestone with the same white mark and supporting caption.

**Build:** In each 270×166 SVG draw a broad cubic curve above the metric, roughly 9–12px thick, with a white triangular arrowhead. Apply a black-to-white gradient along the curve. Center a bold sans numeral beneath it at roughly 96px, leaving room for a small suffix. Keep the caption outside the SVG so it remains accessible.

### Artwork collection ribbon

**Only for:** catalog or creative-output showcases

**Use:** A brief full-bleed burst of saturation between neutral chapters.

**Observed:** Several staggered rows of colorful square cover art run beyond both viewport edges within a 350px-high band. Blue, green, violet and warm red imagery remains inside the artwork, while top and bottom masks blend the collection back into black.

**Transfer:** Use actual product outputs, templates or editorial covers with varied color. Keep color confined to the media rather than turning it into the site's action palette.

**Build:** Arrange small square artworks in three tightly spaced rows, offset adjacent rows horizontally, extending past both sides of the viewport. Overlay a black-to-transparent-to-black vertical mask so the middle rows are clearest.

### Expressive line-art gathering

**Only for:** community invitations

**Use:** Friendly illustrated transition before an invitation.

**Observed:** A loose group of white outlined faces in irregular masks floats over bulbous graphite forms. The 760×482px illustration is much larger than the paragraph below, but keeps the monochrome environment.

**Transfer:** Commission an original cluster of expressive symbols or characters appropriate to the audience, preserving the spare white outlines and soft sculptural backing.

**Build:** Overlap four or five softly rounded black-to-gray SVG blobs. Place original irregular closed outlines over them with 2px white strokes, adding only a few curved facial or symbolic marks. Avoid colored fills and heavy cartoon shading.

### Icons

**Observed:** White outline symbols use 1.5px round strokes, normally at 20px or 24px. Dark circular audio-preview controls are 44px; large video play controls are 72px white circles with black 36px symbols. Award laurels and organic state symbols extend the fine-line visual language.

**Transfer:** Choose rounded, spare outline icons and use filled shapes only for directional play glyphs or small accents. Preserve the circular controls and do not introduce colorful icon badges.

## Section recipes

How recurring sections are built.

### First screen: Product constellation opening

**Observed:** A 72px Navigation floats over Black environment. The title starts with 120px of top space, centered in the upper portion using display; a two-line gray explanation is 564px wide with 20px above it. A centered Primary button follows after 40px. Behind and below the action, the monochrome product constellation stretches essentially edge to edge: tall devices balance the sides while a larger central screen and low foreground objects form a broad base. Text stays in front, not printed across the objects. Within the first 900px the complete title, support, action and almost all the product stage are visible; the press marks begin below the fold.

**Transfer:** Use a short product name or promise, one explanation and one action above an original low-key product stage. With no hardware, enlarge a single dark interface frame and surround it with Signal diagrams. Editorial entry screens instead use a centered symbol, a 600px-wide statement and the Editorial entry action; do not turn that treatment into the normal product opening.

**Avoid:** Do not replace the product stage with a generic split-screen hero, a colorful stock image or a huge multiline slogan that pushes all product imagery below the fold.

**Text style:** `display` — apercuPro 400 · 60px/1.2 · tracking 0.0058em

### Chapter introduction and feature pair

**Observed:** A 760px centered heading and gray body block use a 20px gap. Typically 100px separates a chapter from the previous group and 48px separates the introduction from a 1152px-wide pair of Feature cards. Titles can pair a product context with a short benefit sentence on the next line.

**Transfer:** Explain one coherent capability family, then use two complementary demonstrations below. Repeat the format only where the product story needs another chapter.

**Text style:** `heading` — apercuPro 400 · 44px/56px · tracking 0.008em

### Quantified proof stage

**Observed:** A centered chapter introduction leads to four unboxed Sculptural proof marks with 24px gutters. Each has an 18px caption under the artwork; source explanations sit centrally beneath the row rather than in the main headline.

**Transfer:** Separate the metric, its meaning and its substantiation; preserve the dramatic arrows and neutral palette without importing claims.

**Text style:** `body-small` — apercuPro 400 · 18px/24px

### Immersive demonstration

**Observed:** A narrow centered introduction precedes a large product-screen scene. The screen is approximately 1152×648px, while the atmospheric landscape extends wider than the viewport. A white circular play control sits on the main object.

**Transfer:** Give an important experience a full-width interruption between smaller paired chapters; let the backdrop merge with the same black environment.

### Recognition and review waterfall

**Observed:** A centered heading and explanation lead to award-like marks with white laurel outlines, then the three-column Review card waterfall. The review area is clipped with a lower black fade and a centered Primary button.

**Transfer:** Combine concise institutional proof with longer first-person accounts; use real recognition or an equivalent verified credential rather than decorative invented badges.

### Practical ending

**Observed:** A centered heading introduces stacked Question rows in the main content width. After a 120px separation, the footer brings a small symbol and compact navigation columns on the left beside a 466px newsletter form on the right. Footer-heading, short gray explanation, Email field and a full-width dark submission button form the final invitation. A 100px lower interval separates the main footer block from Footer navigation.

**Transfer:** Close with answers and a useful ongoing-contact action, then compact utility links; preserve the split between discovery links and a practical signup rather than forcing an oversized final sales pitch.

**Text style:** `footer-heading` — apercuPro 400 · 36px/42px · tracking 0.0097em

### Editorial entry

**Only for:** editorial entry screens

**Observed:** An isolated white outlined identity symbol sits above a centered regular statement, with a 30px gap before Editorial entry action. The statement uses a 600px measure on an uninterrupted black field.

**Transfer:** Use this restrained entry for a focused essay or vision experience, keeping a clear way into the content. Let subsequent editorial structure follow the actual material rather than extending an entry screen through the whole document.

**Text style:** `editorial-title` — Roboto 400 · 40px/1.125

## Page flow

**Storyline:** Centered promise → tangible experience → substantiated mechanism → capability chapters → recognition and human proof → practical answers and ongoing contact.

### Comprehensive product marketing with multiple ways to experience the product

1. **Promise** — Centered title, explanation and outlined action over a monochrome product constellation.
2. **Credibility** — Muted press marks precede a large product demonstration and four compact use-case controls.
3. **Quantified proof** — Scientific explanation with four sculptural numerical graphics and source captions.
4. **Capability chapters** — Repeated centered introductions with paired illustrated feature cards; occasional oversized screen scenes interrupt the rhythm.
5. **Social proof** — Creative-output ribbon, recognition laurels and a masked review waterfall.
6. **Participation** — Large monochrome character gathering above a centered invitation and outlined action.
7. **Objection handling** — Eight full-width expandable questions.
8. **Ongoing contact** — Navigation directory and newsletter form followed by a fine divider, legal links and social icons.

**Transfer:** Use as a library of narrative moves, not a required number of chapters. Preserve the contrast between narrow explanations, large staged media and practical closing information.

### Focused editorial entry into a vision statement

1. **Identity** — White outlined identity symbol isolated on black.
2. **Premise** — Centered three-line regular statement explaining the editorial ambition.
3. **Entry action** — One filled gray action under the statement.

**Transfer:** Borrow the sparse entry composition for an essay or vision experience; use the default marketing closing pattern when a complete utility ending is needed.

## Writing

Reassuring, explanatory and scientifically confident without sounding clinical. Benefits feel personal and everyday while the mechanism is described in direct, accessible language.

**Do not copy:** Do not reuse Endel names, logos, proprietary diagrams, artwork, testimonials, award wins, partner associations, scientific claims or performance numbers. Replace them with the new product's own assets and verified evidence. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Talk directly to you and your day. Refer to the product by name for explanatory statements; use we or our when describing its underlying work.
- **Rhythm:** Short sentence-case chapter titles often form two balanced clauses. Support paragraphs are longer and explanatory, followed by very short action labels; occasional compact imperative sentences add momentum.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening title | The product name stands alone rather than carrying a full persuasive sentence. | 1–3 words | “[Brand]” |
| Supporting line | Describe the useful outcome, then append a short credibility statement. | 12–20 words | “Personalized soundscapes to help you focus, relax, and sleep. Backed by neuroscience.” |
| Chapter heading | Product context followed by a short, human benefit sentence. | 6–12 words | “[Brand] on desktop. Work, rest, and play.”<br>“[Brand] for Amazon Alexa. Just a phrase away.” |
| Feature heading | Name the capability plainly, or convert it into a practical instruction. | 3–6 words | “Detailed personal inputs”<br>“Keep your phone at home” |
| Primary action | Short verb-led invitation with no extra persuasion. | 2 words | “Try Today”<br>“Try Now”<br>“Find Out” |

**Words and phrasing to use:** personalized; real-time; adapt; supports you; on the go; just press start; everyday benefit phrasing

**Avoid:** revolutionary; disruptive; crush your goals; magic bullet; all-caps urgency; unqualified superlatives

**Rules:**

- Explain a useful result before listing technical inputs.
- Give substantive claims a source or a clearly delimited context.
- Use plain short verbs in controls, reserving fuller explanation for the surrounding paragraph.
- Keep the voice gently affirmative; avoid fear-based problem statements.

## Do's and Don'ts

### Do

- Use 400 weight for both 60px opening titles and 44px chapter headings.
- Keep supporting copy at 22px/28px in #bfbfbf, allowing proper explanatory paragraphs.
- Center chapter introductions within 760px while letting feature content occupy 1152px.
- Use 24px gutters for paired features, four-part proof and question stacks.
- Make outlined primary actions 56px high with 12px corners and 2px white edges.
- Carry diagrammatic white curves and charcoal light pools into original product imagery.
- Reserve the 15px white conversion halo for the compact header action.
- End full marketing stories with solid question rows and a split directory/newsletter footer.

### Don't

- Do not turn the dark page into a navy or violet gradient environment; the base is #000000.
- Do not use saturated brand-colored CTA fills; saturation is confined to artwork collections.
- Do not make all panels solid #262626; explanatory panels dissolve from #181818 into black.
- Do not give every control a pill radius; the standard action radius is 12px.
- Do not bold all feature titles or replace the regular grotesk with a condensed display face.
- Do not apply drop shadows to the feature-card grid; separation comes from fades and 24px gutters.
- Do not normalize review quotes into identical short cards; keep the uneven waterfall.
- Do not enlarge footer controls into another hero; preserve the 466px signup column and compact utility strip.

## Motion and responsive

### Motion

**Observed:**

- Buttons and question controls declare background-color 0.2s and border-color 0.2s transitions.
- Editorial entry declares a 1s ease-in-out fade-in after a 1s delay.
- The pages include video playback controls and source-declared entry and exit animations.

**Transfer:**

- Use the declared color transition on the squared dark controls; the fine-line product stage should remain legible in its settled state.
- Keep interactive demonstrations distinct from the still diagram cards so playback is signaled by the circular play control.

**Unknown:**

- Exact behavior and timing of product-scene animation and scroll interactions are not established.

### Responsive

**Observed:**

- Marketing CSS declares width breakpoints at 380px, 440px, 548px, 640px, 724px, 940px, 1024px and 1280px.
- Editorial CSS declares width breakpoints at 671px, 672px and 1100px.

**Transfer:**

- As a design adaptation, stack paired feature cards and reduce the four-part proof row to fewer columns while retaining the dark environment and white line artwork.
- Preserve the opening's title–support–action above the product object; simplify the object constellation to one legible frame rather than shrinking every device.
- Place the newsletter below the link directory on narrow screens, retaining its outlined field and full-width submit action.

**Unknown:**

- Actual narrow-screen layouts, type sizes and navigation collapse behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
