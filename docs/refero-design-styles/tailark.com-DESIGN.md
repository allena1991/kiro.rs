# Tailark — miniature worlds on paper

## Overview

A light, gallery-like style for developer tools and thoughtfully made digital products. Small system-sans headlines, handwritten green emphasis and technical mono labels sit above expansive collections of interface miniatures. White and pale gray dominate, with lavender and blue-gray display stages bringing occasional depth; the prose is compact while the visual demonstrations are abundant.

### Essentials

- An understated promise ends in a human flourish: a centered 576px headline block uses 30px medium system sans with -0.025em tracking, punctuated by a 48px Caveat word in a mint-to-green gradient.
- The first screen is a showroom, not a billboard: 96px of space above the headline, paired 32px actions, a compact trust strip, then a three-column preview collage beginning around 510px into the page.
- Actions feel like tiny native controls: 6px corners, 14px/20px medium labels, 12px horizontal padding and a near-black primary surface with a fine ring and low shadow.
- Color belongs to the exhibits: the surrounding canvas stays white or a 2.5% ink wash; large lavender and blue-gray fills are confined to 24px-radius media stages, while saturated color appears as small interface details and the handwritten emphasis.
- Product proof is rendered as little physical objects: white 12–16px-radius panels, hairline edges, soft shadows and bottom fades. Include a miniature interface scene even without finished product media; a few purposeful cards and connectors are the minimum equivalent.
- Chapter headings behave like a sentence with two tones: 14px mono label, 48px gap, then 30px/36px medium text with a dark short lead and gray continuation; a small exploration link follows 24px later.
- The ending is a spacious index rather than a sales banner: centered 30px gray destination links on 60px rows, a small mark above and a compact social/contact/theme row below, within 96px top and 128px bottom padding.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Emerald highlight | `#009966` | `--color-green` | accent | Lower end of the handwritten word gradient and small positive details. |
| Mint highlight | `#5ee9b5` | `--color-mint` | accent | Upper end of the handwritten word gradient. |
| Lavender stage | `#c6d2ff` | `--color-lavender-stage` | background | Broad framed presentation surfaces behind white page miniatures. |
| Blue-gray stage | `#b7cbd7` | `--color-blue-stage` | background | Layered desktop-and-mobile presentation backdrop. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#09090b` | `--color-ink` | text, action, background | Headlines, primary buttons and the narrow announcement band. |
| Navigation gray | `#474748` | `--color-nav-muted` | text | Visible 75% ink over white for navigation. |
| Body gray | `#52525c` | `--color-muted` | text | Supporting paragraphs and subdued interface labels. |
| Index gray | `#71717b` | `--color-secondary` | text | Large footer links and secondary text. |
| Sentence gray | `#787879` | `--color-lead-muted` | text | Visible 55% ink on white for heading continuations and mono chapter labels. |
| Stone stage | `#d4d4d4` | `--color-gray-stage` | background | Alternative neutral presentation stages. |
| Divider gray | `#e4e4e7` | `--color-rule` | border | FAQ row separators and small keyboard key borders. |
| Hairline gray | `#ededed` | `--color-edge` | border | Visible 7.5% near-black edges on white; build with alpha ink. |
| Gallery wash | `#f9f9f9` | `--color-band` | background | Visible 2.5% near-black wash over white behind collections. |
| Soft neutral | `#fafafa` | `--color-soft` | surface, text | Understated plan cards, preview panels and text on dark actions. |
| White paper | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas and raised cards; white alpha layers soften media. |

## Typography

- **ui-sans-serif** — Marketing headlines, body copy, navigation and actions. Unembellished system grotesk with medium-weight headings and compact UI labels. Font stack: "ui-sans-serif", system-ui, sans-serif.
- **Geist Mono** — Chapter labels, counts and technical notation. Even-width technical lettering, kept small and lightly tracked. Font stack: "Geist Mono", "Fira Code", monospace.
- **Caveat** — One expressive word within the opening promise. Sloping handwritten strokes that interrupt the otherwise systematic type. Font stack: "Caveat", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| handwritten-emphasis | Caveat | 500 | 48px | 1 | -0.0156em | One benefit-bearing word at the end of the opening headline. |
| opening-headline | ui-sans-serif | 500 | 30px | 18px | -0.025em | Centered opening promise; use the handwritten inline word to give the two-line block its visual breathing room. |
| heading | ui-sans-serif | 500 | 30px | 1.2 | -0.025em | Chapter lead plus gray continuation, FAQ heading and large closing links. |
| price | ui-sans-serif | 600 | 30px | 1.2 | normal | Current plan amount, with a muted struck-through previous amount alongside. |
| subheading | ui-sans-serif | 500 | 18px | 28px | normal | FAQ category headings. |
| body | ui-sans-serif | 400 | 16px | 1.5 | normal | Supporting paragraphs, plan explanations and testimonial text. |
| eyebrow | Geist Mono | 400 | 14px | 20px | 0.025em | Default chapter identifier in sentence case. |
| proof-eyebrow | Geist Mono | 400 | 14px | 20px | 0.05em | Slightly wider chapter label for pricing and testimonials. |
| action | ui-sans-serif | 500 | 14px | 20px | normal | Buttons and exploration links. |
| navigation | ui-sans-serif | 500 | 13px | 1.5 | normal | Compact global navigation links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| illustration library pages | gallery-title | ui-sans-serif | 500 | 30px | 1.2 | normal | Title embedded in the first row of an illustration index. |

**Notes:**

- Most hierarchy comes from placement, contrast and space rather than enormous size: 30px is both the opening sans size and the chapter headline size.
- Keep the 30px heading at weight 500 with -0.025em tracking; do not make it a heavy display face.
- The opening's compact line box is paired with an inline 48px handwritten word. Preserve the visible separation between lines when adapting copy.
- Mono is a label voice, not the default body font. Typeface variations inside showcased interfaces are not additional marketing fonts.

## Layout

**Density:** Airy around compact text and controls, dense inside visual collections.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Between paired actions and tight visual elements. |
| 12px | Horizontal action padding and compact caption insets. |
| 16px | Gallery gutters and outer media margins. |
| 24px | Testimonial padding and heading-to-exploration-link spacing. |
| 32px | Plan card padding and internal row spacing. |
| 48px | Eyebrow-to-heading interval and heading-block-to-media interval. |
| 96px | Opening top space, presentation-stage padding and footer top space. |
| 128px | Major chapter separation and footer bottom space. |

### Containers and grids

- **Marketing container**: max width 1280px · side padding 16px. Centered desktop container; yields 1248px of inner width at 1440px.
- **Heading measure**: max width 576px. Centered two-line promise and chapter heading sentences.
- **Media canvas**: max width 1520px · side padding 16px. Near-full-width product presentation area extending beyond the prose container.
- **Preview columns**: 3 columns · gap 16px. Uneven-height miniature panels in a masonry-like collection.
- **Paired stages**: 2 columns · gap 16px. Half-width presentation stages, interrupted by a full-width hero exhibit.
- **Social proof grid**: max width 1280px · 4 columns · gap 16px · side padding 16px. Four staggered columns of small quote cards with a bottom fade.
- **FAQ split**: 5 columns · gap 48px. Heading occupies two columns; grouped accordion occupies three, with a 672px question measure.
- **Library shell** (only for searchable catalog pages): max width 1440px. 288px filter rail beside 1152px results region, with a 49px toolbar above results.

## Corner radius

| Element | Radius |
| --- | --- |
| Actions | 6px |
| Small cards | 12px |
| Preview frames | 16px |
| Presentation stages | 24px |
| Avatars | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Fine card | `0 0 0 1px rgba(9,9,11,0.075), 0 1px 3px rgba(0,0,0,0.065), 0 1px 2px -1px rgba(0,0,0,0.065)` | Testimonial cards and small white interface objects. |
| Presentation frame | `0 0 0 1px rgba(0,0,0,0.05), 0 25px 50px -12px rgba(0,0,0,0.06)` | White page miniatures on colored stages. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing page.

**CSS:** `background: #ffffff; border-radius: 16px`

**Observed:** White sheet against a near-black outer root, with rounded corners visible at the top and ending.

**Transfer:** Keep the main reading environment light even when some exhibits are dark.

#### Gallery band · level 0

**Use:** Collection backing.

**CSS:** `background: rgba(9,9,11,0.025); border-top: 1px solid rgba(9,9,11,0.075); border-bottom: 1px solid rgba(9,9,11,0.075)`

**Observed:** Barely darker than the white cards it supports.

**Transfer:** Use tonal separation, not a conspicuous gray stripe.

#### White object · level 1

**Use:** Quotes and miniature UI groupings.

**CSS:** `background: #ffffff; border-radius: 12px; box-shadow: 0 0 0 1px rgba(9,9,11,0.075), 0 1px 3px rgba(0,0,0,0.065), 0 1px 2px -1px rgba(0,0,0,0.065)`

**Observed:** Thin edges and diffuse low elevation make panels look like paper objects.

**Transfer:** Reserve stronger shadows for the large presentation frames.

#### Lavender exhibit · level 0

**Use:** Large product presentation stage.

**CSS:** `background: #c6d2ff; border: 1px solid rgba(9,9,11,0.075); border-radius: 24px; padding: 96px; overflow: hidden`

**Observed:** A centered white framed page floats inside the color; stages can be full-width or paired. Stone gray is a neutral variant.

**Transfer:** Let the backing frame the product rather than compete with it.

#### Blue layered exhibit · level 0

**Use:** Multi-device proof scene.

**CSS:** `background: #b7cbd7; border-radius: 24px; padding: 96px 96px 0; overflow: hidden`

**Observed:** A tall desktop composition is overlapped by a narrower phone and another page; a translucent white bottom veil uses 40px backdrop blur.

**Transfer:** Use a broad pale stage to unite differently sized product views.

#### Dark exhibit · level 0

**Only for:** dark product demonstrations

**Use:** A bounded contrast variation inside an otherwise light page.

**CSS:** `background: linear-gradient(#71717b, #09090b); border-radius: 24px; overflow: hidden`

**Observed:** Dark desktop and phone frames overlap over a gray-to-black stage; a large blurred white halo softens the upper background, and a black translucent veil fades the bottom.

**Transfer:** Keep the dark look inside the exhibit rather than turning the entire marketing page dark.

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #09090b; color: #fafafa; border: 0.5px solid transparent; border-radius: 6px; padding: 0 12px; height: 32px; gap: 8px; box-shadow: 0 0 0 1px rgba(0,0,0,0.9), 0 4px 6px -1px rgba(0,0,0,0.15), 0 2px 4px -2px rgba(0,0,0,0.15)`

**Text style:** `action` — ui-sans-serif 500 · 14px/20px

**Observed:** Centered label without a decorative icon; paired with a ghost exploration action. Header version is 28px tall with 12px text; plan version is 36px tall and spans its card.

**States:** Declared: hover background becomes 90% ink; focus-visible removes the outline and retains a ring/shadow treatment.

### Ghost action

**Use:** Exploration beside a conversion action or below a chapter heading.

**CSS:** `background: transparent; color: #09090b; border-radius: 6px; padding: 0 12px; height: 32px; gap: 8px`

**Text style:** `action` — ui-sans-serif 500 · 14px/20px

**Observed:** Text-only in the opening; chapter variants add a tiny right-facing triangle.

**States:** Declared: hover background becomes 5% ink and text stays ink; focus-visible outline is none with a transparent ring.

### Navigation link

**Use:** Global destination navigation.

**CSS:** `color: rgba(9,9,11,0.75); border-radius: 6px; padding: 0 12px; height: 28px; gap: 8px`

**Text style:** `navigation` — ui-sans-serif 500 · 13px/1.5

**Observed:** Mark at left; search shortcut and destination links at right, then login and compact dark action. The marketing header uses the centered container; catalog headers stretch to 24px side insets.

**States:** Declared: hover uses 5% ink background and full ink text; focus-visible outline is none.

### Quote card

**Use:** Small social-proof objects.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 24px; box-shadow: 0 0 0 1px rgba(9,9,11,0.075), 0 1px 3px rgba(0,0,0,0.065), 0 1px 2px -1px rgba(0,0,0,0.065)`

**Text style:** `body` — ui-sans-serif 400 · 16px/1.5

**Observed:** Quote first, then a compact attribution row with circular avatar, name and muted handle. Variable heights form staggered columns; a few lead cards carry a faint cool tint.

**Transfer:** Use short authentic remarks rather than uniform-length promotional blurbs.

### Plan card

**Use:** Compare purchase options.

**CSS:** `background: #fafafa; border-radius: 12px; padding: 32px; display: grid; gap: 32px; box-shadow: 0 0 0 1px rgba(9,9,11,0.1)`

**Text style:** `body` — ui-sans-serif 400 · 16px/1.5

**Observed:** Three aligned cards: plan name and description, current and previous price, payment note, full-width action, then green-check benefits. Featured middle card is white, softly raised, with a mint popularity badge and dark action; other actions are white.

**Transfer:** Align the major content rows across plans instead of positioning buttons at arbitrary heights.

### FAQ row

**Use:** Resolve grouped purchase and product questions.

**CSS:** `border-bottom: 1px solid #e4e4e7; padding: 16px 0; min-height: 56px; font-weight: 500`

**Text style:** `body` — ui-sans-serif 400 · 16px/1.5

**Observed:** Question aligned left and tiny chevron at right. Categories use the subheading recipe with 48px separation; last rows can omit their bottom rule.

### Closing index link

**Use:** Large, calm destination list at the end of a marketing page.

**CSS:** `color: #71717b; padding: 12px 0; display: block; text-align: center`

**Text style:** `heading` — ui-sans-serif 500 · 30px/1.2 · tracking -0.025em

**Observed:** Full-width hit areas form a single centered column. Small mark sits above the list; social, contact and theme icons form a separate row below.

**States:** Declared: hover color becomes full ink.

### Catalog tile

**Only for:** searchable catalog pages

**Use:** Browse visual categories or full-page templates.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 4px; box-shadow: 0 0 0 1px rgba(9,9,11,0.075), 0 4px 6px -1px rgba(0,0,0,0.05), 0 2px 4px -2px rgba(0,0,0,0.05)`

**Observed:** Large miniature preview above left-aligned name and smaller count or style label. Captions sit inside 12px horizontal insets. Category previews vary in height; complete-page previews use a consistent tall proportion.

**Transfer:** Retain actual representative content in previews and label it plainly.

## Imagery and graphics

### Miniature product collection

**Use:** Opening proof and capability chapters.

**Observed:** Three uneven columns of complete interface or page previews, nearly filling the available width. White cards sit on a faint gray band; small colorful UI accents survive inside mostly monochrome scenes. The bottom dissolves into white rather than ending with a hard rectangular cut.

**Transfer:** Show several distinct product outcomes at miniature scale. Without final media, construct real representative cards with headings, rows and tiny charts rather than generic empty rectangles.

**Build:** Use a three-column grid with 16px gutters, 12px-radius white panels and a 1px low-alpha ink ring. Give panels varying heights. Overlay or mask the lower edge with a white fade; a radial mask stays opaque through roughly 80% of the composition before fading.

### Floating interface vignettes

**Use:** Signature capability proof inside bento cells.

**Observed:** Small invoices, file sheets, conversations, checklists and workflow nodes float in much larger white cells. Some are slightly tilted or stacked, with soft shadows, tiny colored chips, dotted connectors and a progressive fade at the bottom. Occasional portraits or video stills provide human detail without becoming full-bleed photography.

**Transfer:** Reduce a meaningful product operation to one small scene surrounded by ample air; use a document, result card or linked process when no interface is available.

**Build:** Place a 220–300px white card in a broad cell, use 12–16px corners and the Fine card shadow. Add two offset outline sheets behind it for a stack, or SVG 1px dotted curves between small nodes. Use color only on status chips and short highlights. Mask the lower content with a white gradient so the object feels embedded in the page.

### Framed page exhibits

**Use:** Large visual proof between compact text chapters.

**Observed:** Single tall white page frames on lavender or stone backings alternate with overlapping desktop-and-phone arrangements on blue-gray. Frames have 16px outer corners, 6px white mats and 10px inner corners. Large stages have 24px corners and generous backing visible around each object.

**Transfer:** Present your own app, document or output in a framed portrait composition; one well-composed product board is preferable to an unrelated stock photograph.

**Build:** Use a 24px-radius stage with 96px inset space. Center a white frame up to 672px wide at a 4:5 proportion, with 6px padding and the Presentation frame shadow. For a layered variant put one broad frame behind a narrower phone-like frame at the right; clip both at the stage bottom and add a white translucent gradient veil with 40px backdrop blur.

### Handwritten green word

**Use:** Signature opening emphasis.

**Observed:** One large handwritten word is embedded at the end of an otherwise plain black sans headline; its green changes from pale mint above to deeper emerald below.

**Transfer:** Choose a short outcome or feeling word, not an entire sentence.

**Build:** Set the word in Caveat 48px/48px weight 500, tracking -0.8px. Apply a vertical gradient from mint to emerald, background-clip:text and transparent text fill.

### Illustration index grid

**Only for:** illustration library pages

**Use:** Browse a large collection of small rendered scenes.

**Observed:** Four columns separated by 1px hairlines, with small crosshair-like marks at corners. White translucent cells hold centered UI objects; wide scenes span two cells and occasional black cells display dark art. The title occupies a double-width first-row cell and ends with a thin mono count.

**Transfer:** Let each item have enough breathing room to read as an independent specimen.

**Build:** Use a four-column grid with 1px gaps over an 8% ink backing and 75% white cells. Add 4px corner brackets with 1px low-alpha ink strokes. Allow selected items to span two columns; keep dark cells local.

### Icons

**Observed:** Small rounded outline SVGs, usually 14px or 16px with 2px round strokes, follow the text color. Tiny triangles distinguish exploration links; social and brand marks use their own silhouettes.

**Transfer:** Use a consistent rounded-stroke set for controls; reserve filled colored marks for product or integration objects.

## Section recipes

How recurring sections are built.

### First screen: Small promise above a showroom

**Observed:** A 36px near-black announcement strip precedes a 60px white header on the rounded Paper canvas. The centered 576px promise begins after 96px of top space and reads as two compact lines of 30px medium sans, ending in the 48px green Handwritten green word. Primary button and Ghost action sit together with an 8px gap, below the promise. There is no separate hero support paragraph. A muted trust caption and small horizontal monochrome logo row follow. The Miniature product collection begins around 510px into the page, so the first 900px show the full headline, both actions, proof strip and the upper portions of three preview cards; the rest of the collection continues below the fold. Layers are white canvas, faint gallery backing, then raised miniature content.

**Transfer:** Use a concise product-category promise, one handwritten outcome word and two small actions. Supply several miniature product results as the main visual, including purpose-built interface vignettes if necessary. Searchable catalogs instead open directly into filters and visual results; illustration libraries begin with a title cell within the exhibit grid.

**Avoid:** Do not replace this with an oversized 80px headline, a full-screen photograph or a single huge dashboard that displaces all first-screen proof.

**Text style:** `opening-headline` — ui-sans-serif 500 · 30px/18px · tracking -0.025em

### Two-tone chapter sentence

**Observed:** Centered mono eyebrow above a 576px-wide heading block, with 48px separation. Heading uses a dark short lead followed inline by a muted continuation in the same 30px/36px recipe; the whole sentence typically wraps to two lines. Ghost action follows after 24px; media begins after another 48px.

**Transfer:** Name the capability briefly, then describe its value in plain language; keep emphasis in contrast rather than extra sizes.

**Text style:** `heading` — ui-sans-serif 500 · 30px/1.2 · tracking -0.025em

### Bento capability specimens

**Observed:** White object cells fill a near-full-width Gallery band. Narrow file or identity objects sit beside wider conversation and workflow scenes; text remains small relative to the cell. The Floating interface vignettes supply the detail.

**Transfer:** Mix narrow single-object cells with wider scenes that explain a process. Vary spans according to the complexity of the product story.

### Large exhibit chapter

**Observed:** Paired stages and full-width Framed page exhibits use 16px gutters and 24px outer corners. Broad lavender and stone fields frame single page views, while blue-gray and bounded dark stages hold overlapping devices.

**Transfer:** Use the presentation system to show distinct workflows or output families, not just more decorative cards.

### Purchase comparison

**Observed:** Two-tone chapter sentence introduces three Plan cards within the Marketing container. The middle plan is emphasized through white elevation, mint badge and dark action rather than a large saturated fill. Prices use the price recipe and small payment notes.

**Transfer:** Make the most useful option easy to identify without making the other options look disabled.

### Staggered social proof

**Observed:** Mono label and short 30px heading above four columns of Quote cards, 16px apart. A pale neutral atmospheric band and lower fade keep the long collection from ending abruptly; a small exploration action continues the proof.

**Transfer:** Use authentic varied-length quotes and visible attribution; keep their visual scale conversational rather than monumental.

### Grouped objections

**Observed:** FAQ split places the 30px section title on the left and 672px question groups on the right. Subheadings use 18px/28px medium type, with 48px between groups. FAQ rows end in subtle chevrons. A brief contact invitation follows the groups.

**Transfer:** Organize questions by reader concern and leave the heading side mostly open.

**Text style:** `heading` — ui-sans-serif 500 · 30px/1.2 · tracking -0.025em

### Index ending

**Observed:** Closing index links form a centered vertical list with 60px rows; 96px of top padding and 128px below frame a small mark, the destination list and a final social/contact/theme icon row. Illustration libraries use a smaller left-aligned horizontal link row, with 64px bottom padding. Searchable catalogs end instead in a 62px bottom status bar with a page-size selector and result count; paginated results add compact previous, numbered and next controls.

**Transfer:** End marketing stories with the spacious index. Use functional count and pagination endings only for browsable catalogs.

**Text style:** `heading` — ui-sans-serif 500 · 30px/1.2 · tracking -0.025em

## Page flow

**Storyline:** compact promise → abundant visual proof → capability chapters → deeper product exhibits → purchase clarity → social reassurance → objections → destination index

### Product marketing landing page

1. **Promise** — Small centered headline, handwritten emphasis, paired actions and trust strip.
2. **Product demonstration** — Three-column preview collage fading into white.
3. **Capability chapters** — Two-tone heading sentences introduce bento specimens, category collections and large framed exhibits.
4. **Pricing** — Three aligned comparison cards with a raised middle option.
5. **Social proof** — Staggered quote wall with attributed remarks.
6. **Objection handling** — Grouped split-layout FAQ and a contact invitation.
7. **Closing navigation** — Large centered destination index with small utility icons.

**Transfer:** Adapt the number and order of capability chapters to the product while retaining the small-text/abundant-proof contrast.

### Browse categories of reusable or purchasable items

1. **Orientation** — Compact shared header, left filter rail and search toolbar.
2. **Exploration** — Three masonry-like columns of category previews with names and item counts.
3. **Result status** — Bottom page-size selector and result count; rail retains utility links.

**Transfer:** Use for a template, extension or resource catalog, not as the default landing-page composition.

### Browse complete solutions or templates

1. **Orientation** — Shared catalog shell with style and category filters.
2. **Comparison** — Three columns of tall complete-page previews with a name and style caption.
3. **Continuation** — Bottom result status plus compact numbered pagination.

**Transfer:** Use consistent tall preview ratios to compare complete offerings; keep navigation functional and small.

### Browse visual specimens

1. **Orientation** — Double-width title cell with a thin mono count inside a four-column grid.
2. **Product demonstration** — Sequence of document, data, communication, workflow and phone-like interface specimens; some cells span wider or turn dark.
3. **Closing navigation** — Small left-aligned mark, horizontal destination links and utility icons.

**Transfer:** Group related specimens without inserting repeated marketing headlines between every row.

## Writing

Confident but restrained, with a maker's attention to useful finished details. Benefits are expressed through clear product nouns and practical verbs rather than theatrical claims.

**Do not copy:** Do not reuse Tailark names or logos, customer identities, testimonials, interface content, specific prices, counts, discounts or performance claims. Replace them with the new product's own substantiated content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Usually speaks directly to founders or builders, using you and your in support copy; product descriptions can be impersonal noun phrases.
- **Rhythm:** Short chapter leads paired with one compact explanatory clause. Actions are two to four words; longer functional questions stay plain and specific.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Product category for an audience who values a particular outcome; emphasize the final value word. | About 10–15 words | “The shadcn marketing kit for founders who care about design.” |
| Chapter lead | Short noun phrase ending in a period, then a practical explanation. | 2–4 words plus one short sentence | “Crafted visuals.”<br>“Designed to integrate seamlessly” |
| Supporting paragraph | Audience or workflow first, then useful qualities without a feature dump. | One compact sentence | “For solo founders building polished marketing sites with clarity and control.” |
| Action | Plain verb plus destination or access object. | 2–4 words | “Explore the kit”<br>“Get full access” |
| Objection heading | Common concerns named without cleverness. | 2–3 words | “Common questions”<br>“General questions” |

**Words and phrasing to use:** crafted; complete; designed; workflow; clarity; control; explore; access; integrate

**Avoid:** revolutionary; mind-blowing; unprecedented; 10x everything; limitless magic

**Rules:**

- Use category nouns to orient readers before describing benefits.
- Let the visual proof do most of the persuasive work; avoid long paragraphs above each exhibit.
- Keep navigation labels literal and sentence case.
- Separate payment terms and feature lists from the main plan description.
- Use conversational language in genuine quotes, but keep the surrounding marketing copy polished and compact.

## Do's and Don'ts

### Do

- Keep opening and chapter sans headlines at 30px and weight 500.
- Give the opening promise a 576px centered measure and one 48px handwritten emphasis.
- Use 6px action corners and 32px default action height.
- Keep 16px gutters between media panels and plan cards.
- Use 24px corners on broad colored stages, with 96px desktop inset space.
- Use 14px mono chapter labels and 48px label-to-heading separation.
- Keep comparison cards at 32px padding with aligned content rows.
- Finish marketing pages with 30px closing links rather than a tiny dense sitemap.

### Don't

- Do not spread Caveat into paragraphs, navigation or whole chapter headings.
- Do not turn the lavender media backing into the main reading canvas.
- Do not use pill-shaped marketing buttons; the 6px rectangle is the default.
- Do not make all shadows equally strong: small objects stay low, large framed exhibits can float more.
- Do not enlarge navigation to body-heading scale; it stays 13px.
- Do not set chapter support text as a separate tiny paragraph when it belongs in the same 30px two-tone sentence.
- Do not import the vivid buttons or alternate typefaces inside demonstrations into the surrounding marketing system.
- Do not give catalog result bars the spacious vertical rhythm of the marketing closing index.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions use all .15s cubic-bezier(.4,0,.2,1). Many gallery elements use opacity .15s with the same easing.
- Interface scenes include declared breathing 1.25s infinite, pulse 2s, spin 1s linear, hue-rotate 4s and scan 3s animations.

**Transfer:**

- Keep marketing-control feedback brief; localize animated detail to small interface specimens rather than moving the whole page.
- Use a static arrangement that still communicates the scene before adding any breathing or scan effects.

**Unknown:**

- Actual playback of every scene, scroll-trigger behavior and complete focus-ring declarations are not known.

### Responsive

**Observed:**

- Declared width breakpoints: 600px, 640px, 768px, 1024px, 1280px and 1536px.
- Global desktop navigation is hidden below 1024px. Media stages declare 24px small-screen insets, 48px medium insets and 96px extra-wide insets.
- Several chapter separations reduce from 128px to 64px below 768px. Quote grids declare one column, then two, three and four as width increases.

**Transfer:**

- Reduce presentation padding before shrinking the miniature objects; stack paired stages and keep one coherent specimen per narrow row.
- Reflow the opening promise naturally, preserving the contrast between sans and handwritten emphasis.
- Move the FAQ heading above its groups when the five-column split no longer fits.

**Unknown:**

- Mobile layouts, menu interaction and exact breakpoint behavior of every catalog control were not visually reviewed.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
