# Cultured Code — tactile everyday delight

## Overview

A light, approachable software style that makes a useful tool feel like a carefully made everyday object. Cool off-white and white grounds, charcoal system sans-serif type, and small touches of cornflower blue support dimensional app artwork and large, bright interface demonstrations. The pacing is spacious around the product and conversational in the denser walls of customer and editorial praise.

### Essentials

- A little product object carries the opening, not an oversized slogan: center a 250px × 301px artwork-and-name composition above a 440px-wide introduction set at 24px/1.25.
- Section titles feel like friendly illustrated signposts: 36px/1, weight 700, normal tracking, with a small pictorial symbol directly beside the words and a centered 440px support column.
- Color behaves like a useful affordance: nearly all structural area stays #f2f5f7, #fbfcfe or #ffffff; #5c9cf5 marks links and play controls, while stronger color lives in product art and small section symbols.
- Actions are light and compact rather than pill-shaped banners: transparent blue links have 6px corners; the filled form action is 36px tall with 7.6px corners.
- Product craft is demonstrated at two scales: a softly shaded dimensional emblem and a roughly 1000px-wide, front-facing interface ensemble. If there is no app or hardware, create a dimensional service emblem and an equally legible example of its output.
- Proof has a distinctly conversational material: 441px-wide pale speech bubbles with 18px corners, 27px padding, oversized faded quotation marks, an underlined key phrase and attribution outside the bubble. Preserve this device with genuine proof appropriate to the new product.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cornflower link | `#5c9cf5` | `--color-link` | link, action, accent | Video, feature and social-discovery affordances; not a full-band background. |
| Filled action blue | `#4f91fb` | `--color-action` | action, surface | Compact newsletter submit button. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | background, surface, text | Editorial and conversion bands, social cards, email field and reversed action labels. |
| Near-white blue | `#fbfcfe` | `--color-lightest` | background | Bright product demonstration band. |
| Cool canvas | `#f2f5f7` | `--color-canvas` | background, surface | Opening and alternating bands; also the flat fill of purchase and editorial quote cards. |
| Field edge | `#dfe3e8` | `--color-edge` | border | Email-field outline. |
| Footer hairline | `#d5dbe2` | `--color-rule` | border | Visible divider; rgba(0,28,70,0.12) on the cool canvas. |
| Fine-print gray | `#9299a4` | `--color-muted` | text | Newsletter reassurance and secondary policy links. |
| Navigation gray | `#8c95a1` | `--color-navigation` | text, link | Visible navigation ink; rgba(38,52,74,0.5) on the cool canvas. |
| Purchase metadata gray | `#888c92` | `--color-metadata` | text, link | Visible prices and requirements; rgba(0,7,18,0.44) on the cool canvas. |
| Footer gray | `#838b96` | `--color-footer` | text, link | Visible footer ink; rgba(0,15,36,0.46) on the cool canvas. |
| Editorial slate | `#55606e` | `--color-slate` | text, accent | Quote attributions, laurels and editorial symbols. |
| Soft charcoal | `#44474b` | `--color-body` | text | Introductory and section-support paragraphs. |
| Reading charcoal | `#303336` | `--color-ink` | text | Quotes, card titles and compact reading text. |
| Heading charcoal | `#2c3138` | `--color-heading` | text | Section headings and strong product identity. |

## Typography

- **ui-sans-serif** — All marketing headings, descriptions, navigation and proof text. Native system sans-serif with practical proportions, open small text and sturdy bold headings. Font stack: "ui-sans-serif", -apple-system, "system-ui", Roboto, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | ui-sans-serif | 700 | 36px | 1 | normal | Illustrated section titles, centered and usually short enough for one line. |
| hero-lead | ui-sans-serif | 400 | 24px | 1.25 | normal | The opening's principal live-text statement beneath the product-name artwork. |
| video-action | ui-sans-serif | 600 | 24px | 1 | normal | Prominent introduction-video link. |
| support | ui-sans-serif | 400 | 20.3px | 1.3 | normal | Centered descriptions below section titles. |
| feature-action | ui-sans-serif | 600 | 20.3px | 1.3 | normal | Short blue links below section support. |
| card-title | ui-sans-serif | 700 | 20.3px | 1.2 | normal | Names of product editions in purchase cards. |
| quote-body | ui-sans-serif | 400 | 18px | 1.35 | normal | Long-form editorial endorsements. |
| metadata | ui-sans-serif | 400 | 15.3px | 1.2 | normal | Prices, requirements and footer links. |
| footer-heading | ui-sans-serif | 700 | 15.3px | 1.2 | normal | Small footer category headings. |
| small-body | ui-sans-serif | 400 | 15.2px | 1.3 | normal | Compact social endorsements and form reassurance. |
| navigation | ui-sans-serif | 600 | 15px | 1.6 | normal | Top-level navigation links. |
| award | ui-sans-serif | 800 | 14.4px | 1 | normal, uppercase | Laurel-framed recognition labels within editorial proof. |
| attribution | ui-sans-serif | 400 | 13.5px | 1.2 | normal | Author names outside quote bubbles; publication names use weight 700. |

**Notes:**

- Keep normal tracking throughout; hierarchy comes from weight and scale rather than tight display lettering or spaced labels.
- The opening product name is lettering within the identity artwork, visually about 50px high in type size at desktop. It is not a giant editorial headline.
- Use regular-weight descriptions against bold headings. Italic emphasis is limited to an occasional meaningful word; do not italicize whole support paragraphs.

## Layout

**Density:** Airy at section scale, compact within proof and purchase cards; narrow centered introductions sit above much wider product and proof compositions.

### Spacing

| Value | Use |
| --- | --- |
| 9px | Quote-to-attribution separation. |
| 16px | Social proof grid gutters. |
| 18px | Purchase-card padding and purchase/editorial grid gutters. |
| 24px | Footer grid gutters and spacing beneath its columns. |
| 26px | Visual gap from section title to description. |
| 27px | Editorial bubble padding and heading margins. |
| 36px | Separation beneath the opening identity artwork. |
| 40px | Section introduction wrapper margins; footer top padding. |
| 50px | Opening column top and bottom padding. |
| 57.6px | Desktop container side padding. |
| 81px | Major section vertical padding; the introduction wrapper adds another 40px before its title. |
| 240px | Lower purchase-section artwork stage. |

### Containers and grids

- **Main container**: max width 900px · side padding 57.6px. Center the content area; side padding is additional to the 900px content width in a content-box implementation.
- **Introduction column**: max width 440px. Opening and section descriptions are centered and narrow, making roughly four short lines of support.
- **Demonstration stage**: max width 1000px. Front-facing product ensemble extends slightly beyond the normal content edges.
- **Social grid**: max width 900px · 4 columns · gap 16px. Compact varied-height social cards aligned to the bottom of each row.
- **Editorial grid**: max width 900px · 2 columns · gap 18px. 441px-wide quote bubbles in paired rows, with sources attached below.
- **Newsletter column**: max width 500px. One full-width email field and privacy copy, followed by a centered submit button.
- **Footer grid**: max width 900px · 4 columns · gap 24px. Four equal, left-aligned resource columns beneath a single hairline.
- **Purchase grid** (only for purchase sections): max width 900px · 4 columns · gap 18px. Four equal edition cards on desktop, each about 212px wide.

## Corner radius

| Element | Radius |
| --- | --- |
| Flat cards and quote bubbles | 18px |
| Social cards | 12.8px |
| Navigation and feature links | 6px |
| Video control | 9.6px |
| Email field | 6.4px |
| Submit button | 7.6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Social card | `0px 2px 8px 0px rgba(0,0,0,0.1), 0px 0px 2px 0px rgba(0,0,0,0.1)` | Subtle lift for small white social cards on the cool canvas. |
| Editorial media | `0px 2px 10px 0px rgba(0,0,0,0.1), 0px 0px 0px 1px rgba(0,0,0,0.05)` | A framed recognition image beside editorial quotes. |
| Navigation rule | `0px 1px 0px 0px rgba(38,52,74,0.15)` | A nearly invisible rule under the top bar. |

### Surfaces

#### Cool canvas · level 0

**Use:** Primary page ground and alternating bands.

**CSS:** `background-color: #f2f5f7`

**Observed:** A very light cool gray, with no texture or broad saturated wash.

**Transfer:** Let the product artwork, not the page ground, carry vivid color.

#### White band · level 0

**Use:** Purchase and editorial-proof sections.

**CSS:** `background-color: #ffffff`

**Observed:** Full-width white separates chapters without borders.

**Transfer:** Alternate this with the Cool canvas for long pages.

#### Demonstration band · level 0

**Use:** Large product interface staging.

**CSS:** `background-color: #fbfcfe`

**Observed:** Near-white backing lets white interface windows remain luminous without a heavy panel.

**Transfer:** Use for the largest functional demonstration.

#### Flat pale card · level 1

**Use:** Editorial bubbles and purchase cards.

**CSS:** `background-color: #f2f5f7; border-radius: 18px`

**Observed:** No border or drop shadow; its silhouette provides separation from the white band.

**Transfer:** Use tails only for speech, never for ordinary edition cards.

#### Raised social card · level 1

**Use:** Compact customer posts.

**CSS:** `background-color: #ffffff; border-radius: 12.8px; box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.1), 0px 0px 2px 0px rgba(0,0,0,0.1)`

**Observed:** Small softly lifted white rectangles, with text fading near the lower edge of long posts.

**Transfer:** Reserve the raised treatment for short human proof rather than every content block.

## Components

### Navigation

**Use:** Restrained top-level wayfinding.

**CSS:** `color: rgba(38,52,74,0.5); padding: 2px 5px; border-radius: 6px; line-height: 24px`

**Text style:** `navigation` — ui-sans-serif 600 · 15px/1.6

**Observed:** A small monochrome identity sits left, three short links sit right, and a thin rule spans the 900px bar. The bar has 25px top padding and is not a floating capsule.

**States:** Declared: hover color rgba(38,52,74,0.7), background rgba(4,15,26,0.05); active color rgba(4,15,26,0.7), background rgba(4,15,26,0.1), transform scale(0.98).

### Video invitation

**Use:** The opening's main exploratory action.

**CSS:** `color: #5c9cf5; padding: 6px 8.4px; border-radius: 9.6px`

**Text style:** `video-action` — ui-sans-serif 600 · 24px/1

**Observed:** A solid blue circular play symbol precedes the text. The control is transparent, centered and visually more prominent than navigation.

**Transfer:** Use a short guided introduction or product demonstration rather than a second competing sales button.

### Feature link

**Use:** Continue from a short promise to fuller capability information.

**CSS:** `color: #5c9cf5; padding: 4px 10.1px; border-radius: 6px`

**Text style:** `feature-action` — ui-sans-serif 600 · 20.3px/1.3

**Observed:** A small right-pointing chevron finishes the label; the text is centered below the support paragraph.

**States:** Declared: hover background rgba(92,156,245,0.2); active color rgb(38,52,74), background rgba(38,52,74,0.1).

### Social post card

**Use:** Brief customer reactions with a recognizably human source.

**CSS:** `background-color: #ffffff; border-radius: 12.8px; padding: 12.8px; box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.1), 0px 0px 2px 0px rgba(0,0,0,0.1)`

**Text style:** `small-body` — ui-sans-serif 400 · 15.2px/1.3

**Observed:** Body text comes first, then a tiny square avatar, author and date at the lower edge. Variable-height cards form compact bottom-aligned rows; longer text uses a white fade and a small expansion affordance.

**Transfer:** Use real, short reactions with attribution; preserve varied lengths rather than making a wall of identical testimonials.

### Editorial quote bubble

**Use:** Longer independent validation.

**CSS:** `position: relative; background-color: #f2f5f7; border-radius: 18px; padding: 27px; color: #303336`

**Text style:** `quote-body` — ui-sans-serif 400 · 18px/1.35

**Observed:** Faded oversized opening and closing quotation marks bracket the text. A pale blue-gray underline calls out one phrase. A small downward tail connects the bubble to a publication mark and author placed outside it, inset 27px and separated by 9px.

**Transfer:** Build the tail with a small rounded triangular SVG in the card fill. Highlight a genuine, brief takeaway without enlarging it into a separate heading.

### Email field

**Use:** Single-field newsletter signup.

**CSS:** `background-color: #ffffff; border: 1px solid #dfe3e8; border-radius: 6.4px; padding: 8px; width: 500px; max-width: 100%; height: 37px; box-sizing: border-box`

**Observed:** The email field spans the form. Left-aligned privacy reassurance follows below; submission is on its own centered line.

### Submit button

**Use:** Newsletter form completion.

**CSS:** `background-color: #4f91fb; color: #ffffff; border: 1px solid transparent; border-radius: 7.6px; padding: 7.1px 17px; height: 36px`

**Observed:** A small filled rounded rectangle rather than a full-width action; white semibold lettering sits centered.

### Resource footer

**Use:** A quiet ending with practical links.

**CSS:** `border-top: 1px solid rgba(0,28,70,0.12); padding: 40px 0px 20px; color: rgba(0,15,36,0.46)`

**Text style:** `metadata` — ui-sans-serif 400 · 15.3px/1.2

**Observed:** Four left-aligned columns use small bold category titles and closely spaced links. Social marks sit within a column; a small monochrome company signature is centered on a separate final line.

**Transfer:** Retain the understated final signature rather than replacing the footer with another giant sales claim.

### Edition card

**Only for:** purchase sections

**Use:** A compact purchase choice for a product edition.

**CSS:** `background-color: #f2f5f7; border-radius: 18px; padding: 18px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `card-title` — ui-sans-serif 700 · 20.3px/1.2

**Observed:** A large gray device outline sits above a bold title, small requirements, a modest price and a currency link. Dark store badges align near the base. One edition has an additional bright trial badge above its store badge.

**Transfer:** Keep pricing subordinate to the edition name; use matching channel badges or concise purchase actions suitable to the product.

### Laurel recognition label

**Only for:** editorial recognition sections

**Use:** A compact recognition detail inside a quote.

**CSS:** `color: #55606e; opacity: 0.75; padding: 13px 28.8px; border-radius: 10.8px; text-transform: uppercase`

**Text style:** `award` — ui-sans-serif 800 · 14.4px/1 · uppercase

**Observed:** Small gray laurel sprigs flank a heavy uppercase label; this reads as an inscription, not a colored badge.

**Transfer:** Use only for a real recognition. Draw two simple mirrored leaf branches as SVG beside the label.

## Imagery and graphics

### Dimensional identity object

**Use:** The opening signature and a playful reappearance beneath the purchase choices.

**Observed:** A softly shaded blue app object has thick rounded walls, a dark inner rim, bright paper-like center and a grounding shadow. It is shown front-on with slight depth, isolated on the cool canvas, followed by dark product-name lettering. The later version rises from the bottom of a white band and is intentionally cut off by the next band.

**Transfer:** Create an original dimensional emblem using the new product's defining shape. The minimum version is a layered vector or CSS object with a bright front edge, darker extrusion, inset face and soft contact shadow; keep the product name as live text below.

**Build:** Within a 250px-wide transparent artboard, layer rounded silhouettes: a medium-blue front ring, a darker duplicate offset downward, an inset dark cavity and an off-white face. Add a simple dark central symbol and a blurred rgba(0,0,0,0.18) ellipse beneath. Use an original silhouette; a roughly 180px object plus a short name line should fit the 301px-high identity stage.

### Front-facing interface ensemble

**Use:** The main functional product demonstration.

**Observed:** Large bright interface windows and dark-edged handheld devices are assembled on a near-white ground, with soft gray shadows. A tall phone anchors the left foreground while a larger desktop window occupies the right; other supported devices continue the ensemble below. The artwork is around 1000px square and dominates its chapter.

**Transfer:** Show a real, readable workflow or tangible output with the same frontal, brightly lit staging. If there is no interface, arrange two or three clean examples of the deliverable at different scales instead of inventing a fake dashboard.

### Illustrated section signposts

**Use:** Friendly symbols immediately beside major section titles.

**Observed:** A small multicolor overlapping-circle motif, a download tile, a blue speech bubble, gray spectacles and a lightly dimensional envelope distinguish chapters. These are isolated symbols rather than large illustrations behind text.

**Transfer:** Use one simple pictorial metaphor per major narrative role, with restrained depth and a consistent visual size of roughly 40px–64px.

**Build:** Use compact SVGs with rounded geometry. For a capability symbol, overlap three translucent circles; for communication use a rounded speech rectangle with a small tail; for updates use a white envelope with thin gray fold lines, a blue edge and a faint shadow. Keep vivid pixels confined to the symbol.

### Editorial recognition media

**Only for:** editorial recognition sections

**Use:** A visual counterpoint to the first long endorsement.

**Observed:** A 441px-wide, lightly edged rectangular image places the app object in the center, surrounded by small colorful top-down human illustrations. A recognition inscription sits beneath the object; the rest of the artwork remains very pale.

**Transfer:** Use a real award image, product editorial still or comparable independently meaningful visual. Minimum treatment: one strong product image on a pale backing with a genuine short proof label, 5px corners and the Editorial media shadow.

### Icons

**Observed:** Section symbols are pictorial and sometimes shaded, while purchase-device drawings are gray outlines. Blue social platform marks sit in a centered row; smaller gray equivalents recur in the footer. The feature chevron is a light continuation cue, and the play control is a filled blue circle with a white triangle.

**Transfer:** Keep icon roles distinct: pictorial chapter markers, neutral edition silhouettes and tiny utilitarian action cues. Avoid turning every link into a large illustrated tile.

## Section recipes

How recurring sections are built.

### First screen: Object-led opening

**Observed:** A monochrome 900px navigation bar sits above a centered 440px hero column on Cool canvas. The 250px × 301px identity artwork combines a shaded product object above bold dark name lettering, visually about 50px in type size. The artwork starts after 50px of hero padding. About 36px beneath it, the hero-lead statement runs over four centered lines, followed by Video invitation. All of the identity, support and action are visible within the first 900px, with ample empty ground below. A faint diagonal white media-stage edge enters near the lower fold; the full introduction media and the next section lie below. The background stays behind everything; there is no boxed hero card.

**Transfer:** Use the new product's dimensional emblem and a short name, then a plain-language explanation and one exploratory action. Without polished 3D assets, use the layered-vector identity recipe. An informational page can use a role-specific illustrated object and a concise title while retaining the same centered column and restrained action.

**Avoid:** Do not substitute an enormous multi-line sales slogan, a split-screen SaaS layout or a row of competing filled buttons for this object-led first impression.

**Text style:** `hero-lead` — ui-sans-serif 400 · 24px/1.25

### Illustrated heading pair

**Observed:** A 440px-wide centered introduction combines Illustrated section signposts with the heading recipe, then support text after a 26px visual gap. Major bands use 81px vertical padding with a 40px introduction-wrapper margin. Feature link can complete the introduction.

**Transfer:** Use the same signpost-plus-title relationship for capabilities, proof, conversion or updates; vary the metaphor, not the type hierarchy.

**Text style:** `heading` — ui-sans-serif 700 · 36px/1

### Demonstration chapter

**Observed:** Illustrated heading pair and Feature link sit on Demonstration band. After roughly 40px, Front-facing interface ensemble expands to 1000px wide, larger than the paragraph and normal container.

**Transfer:** Give a meaningful functional example enough space to be inspected; the text explains what the reader gains, and the image explains how it works.

### Edition selection stage

**Observed:** On White band, Illustrated heading pair leads to four Edition cards with 18px gutters. A larger Dimensional identity object emerges from the bottom-center backing; 240px of lower section padding makes room for this playful continuation.

**Transfer:** Use equal visual emphasis for parallel editions or channels, then echo the product object at a different scale. The exact count of choices follows the new offering.

### Compact customer chorus

**Observed:** On Cool canvas, Illustrated heading pair is followed by a centered blue social-icon row and a four-column Social post card grid with 16px gutters. Card heights vary; a freestanding next-chevron sits beyond the right edge.

**Transfer:** Mix concise and moderately detailed customer reactions, keeping author details attached and giving the grid a separate browsing action.

### Editorial conversation

**Observed:** On White band, Illustrated heading pair introduces two columns of Editorial quote bubbles with 18px gutters. Attributions and publication marks sit below each bubble; some bubbles carry Laurel recognition label. Editorial recognition media replaces one bubble near the beginning.

**Transfer:** Retain speech tails, selective underlines and external attributions as the signature proof language. Use fewer bubbles when the available proof is stronger or shorter.

### Reassuring signup and resource ending

**Observed:** A 620px-tall Cool canvas section uses Illustrated heading pair with an envelope signpost. The 500px Newsletter column contains Email field, left-aligned small-body privacy copy and centered Submit button. Considerable breathing space precedes Resource footer, whose 900px rule introduces four columns and a small centered company signature on the final line.

**Transfer:** End with a modest continuing-relationship action and practical navigation, not an aggressive monumental CTA. The reassurance should explain frequency and privacy in direct language.

## Page flow

**Storyline:** Product identity and promise → functional demonstration → purchase choices → human and editorial validation → low-pressure continuing relationship → resource navigation.

### A flagship consumer-software landing page that turns product craft into trust and action

1. **Identity and promise** — A dimensional emblem, product name, narrow explanatory paragraph and video invitation.
2. **Product demonstration** — An illustrated benefit heading above a large bright multi-device interface ensemble.
3. **Conversion** — Parallel edition cards with requirements, modest prices and distribution badges.
4. **Human proof** — Short varied-height customer posts beneath a friendly centered introduction.
5. **Independent validation** — A longer two-column conversation of editorial speech bubbles, sources and recognition details.
6. **Continuing relationship** — A single-field email signup with explicit reassurance and a small blue submit button.
7. **Practical ending** — Four subdued resource columns and a small company signature.

**Transfer:** Use this as an adaptable narrative, not a prescribed sequence or section count. Preserve the object-led identity, oversized functional example, conversational proof device and modest ending while choosing the amount of explanation and proof appropriate to the new product.

## Writing

Warm, plainspoken and assured. Capability is described through the reader's everyday progress, while stronger judgments are often entrusted to attributed customer and editorial voices.

**Do not copy:** Do not reuse Cultured Code or Things names, logos, product icon, review quotations, award claims, prices, platform requirements, customer identities or longevity claims. Source examples illustrate tone only.

- **Addressing the reader:** Speak directly to 'you' and 'your'; use 'we' for the people behind the product and its communication promises. Name the product naturally in explanatory sentences.
- **Rhythm:** Short two-to-five-word section titles, followed by a few readable sentences or one medium-length paragraph. Use contractions and occasional friendly exclamation marks, not a stream of slogan fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | Name the product category and connect several concrete activities to a meaningful outcome. | One sentence, roughly 20–30 words. | “Things is the award-winning personal task manager that helps you plan your day, manage your projects, and make real progress toward your goals.” |
| Section title | Compact, approachable phrasing that makes complexity feel manageable or invites the next step. | 2–5 words. | “Simply Powerful”<br>“Get Things, Get Done”<br>“Read All About It” |
| Support | State an everyday benefit, then describe what the reader can do. | 2–3 short sentences or one medium sentence. | “Whatever it is you want to accomplish in life, Things can help you get there. Install the app today and see what you can do!” |
| Action | Direct verb plus a concrete destination or object. | 1–3 words for routine actions; up to 4 for a guided introduction. | “See features”<br>“Watch Introduction Video” |
| Signup reassurance | Be specific about how rarely and why you will write. | One short paragraph. | “We only send it out a few times per year when we have something interesting to tell you.” |

**Words and phrasing to use:** easy; helps you; what matters; today; make progress; thoughtful; see what you can do

**Avoid:** revolutionize; 10x; dominate; unleash; next-generation platform; enterprise transformation

**Rules:**

- Explain utility before adding emotional flourish.
- Pair a practical activity with a human outcome rather than listing specifications in the introduction.
- Use attributed proof for superlatives; keep the brand's own narration approachable.
- State signup expectations plainly and avoid artificial urgency.

## Do's and Don'ts

### Do

- Keep section titles at 36px/1 and weight 700 with normal tracking.
- Center support in a 440px column even when the media below spans 1000px.
- Alternate the three pale grounds to separate chapters without heavy rules.
- Use 18px corners and flat fills for editorial bubbles, reserving shadows for small social cards and framed media.
- Keep purchase and editorial grid gutters at 18px; use 16px for the compact social grid.
- Give the opening one prominent blue video invitation rather than multiple equal-priority actions.
- Attach source names below speech bubbles with a 9px separation and a 27px inset.
- Let the closing form remain 500px wide with its compact submit button on a separate centered line.

### Don't

- Do not introduce tight negative tracking or widely spaced uppercase eyebrows into the core type hierarchy.
- Do not replace pale full-width bands with navy, black or saturated blue panels.
- Do not make prices into oversized display numerals; they use the 15.3px metadata treatment.
- Do not put the external source attribution inside the editorial bubble.
- Do not turn every corner into a pill; the core card radius is 18px and filled actions use 7.6px corners.
- Do not apply social-card shadows to the flat edition cards or quote bubbles.
- Do not add dashboard chrome or microscopic feature lists around the marketing descriptions.
- Do not scale the footer into another feature section; its links and category headings stay at 15.3px.

## Motion and responsive

### Motion

**Observed:**

- A background transition of 0.2s ease-out is declared on an interactive element.
- Navigation active state uses scale(0.98); feature-link hover introduces a translucent blue background.
- No keyframe animations are declared in the supplied styling context.

**Transfer:**

- Keep state feedback local to the small control: a faint rounded background and the existing navigation press scale suit the understated action hierarchy.

**Unknown:**

- Video-stage behavior, scroll choreography and timing beyond the declared transition are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 340px, 420px, 479px, 480px, 512px, 520px, 600px, 620px, 720px, 734px, 739px, 740px, 899px, 972px, 1002px and 1106px.
- The opening identity image has max-width 75%; the introduction column uses max-width 90%, and the email input uses max-width 100%.

**Transfer:**

- As a design adaptation, preserve the centered object-and-name stack and reduce outer gutters before compressing the text.
- On narrow layouts, reduce the number of proof and purchase columns while retaining speech tails and external sources; keep device artwork proportional rather than shrinking all text inside a desktop-wide montage.

**Unknown:**

- Exact mobile grid counts, navigation behavior and responsive font sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
