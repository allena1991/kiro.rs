# Raus — paper, pasture and play

## Overview

A sunlit editorial style that pairs cream paper, forest-green lettering and vivid little pockets of yellow and sky blue. Light grotesk headings share the page with delicate serif storytelling, large lived-in photographs and mischievous ink drawings. The mood is unhurried but the actions are unmistakable, suiting experiential products, considered services and lifestyle-led launches with sparse, asymmetric compositions.

### Essentials

- A compact promise sits beneath a disproportionately bold identity: a 365×130px green wordmark anchors the upper left while the landing headline stays at 36px/1, weight 300, within 416px.
- Photography behaves like a drifting editorial spread, not a hero wallpaper: 583×680px portraits stagger vertically by 180px, with tiny 14px uppercase identifiers beside 22px serif captions.
- Cream is the continuous ground, with color concentrated into functional islands: #fdf9ed dominates, #006434 marks identity and opening words, a 48px sky-blue announcement and a 1000×128px yellow conversion dock provide the bright interruptions.
- Actions are softened rectangles rather than full capsules: 48px height, 20px corners, 20px side padding and 22px sans text, finished with a small solid right arrow; the compact announcement action uses 32px height and 12px corners.
- The editorial voice is visibly two-handed: light 40px/38px grotesk section headings alternate with 40px/38px serif invitations and 36px/36px serif card titles, all tightly tracked rather than bold.
- Give every new page a hand-drawn pause and a sculptural identity ending: a spare dark ink vignette occupies a 390–524px image area, and an oversized green stacked letterform closes beside the newsletter and link directory. When photography is unavailable, stage tactile product still lifes or original line-drawn usage scenes at the same scale rather than shrinking the media.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest green | `#006434` | `--color-green` | text, accent | Identity artwork and opening headings; selected line drawings. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Booking yellow | `#fcbd1c` | `--color-yellow` | surface, action | The floating conversion dock, not the general page background. |
| Burnt orange | `#dd5000` | `--color-orange` | text, action, link | Announcement copy and compact action fill; text and arrows on blue actions. |
| Sky blue | `#a6dfff` | `--color-blue` | background, surface, action | Announcement ribbon and secondary calls to action. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft black | `#23212c` | `--color-ink` | text, background, border, action | Default copy, rules, outlined controls and primary actions. |
| Cream paper | `#fdf9ed` | `--color-canvas` | background | Continuous page and footer ground. |
| Clean white | `#ffffff` | `--color-white` | surface, text | Floating editorial labels and broad inset panels; reversed primary-action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| group-offer and inquiry pages | Group-offer lime | `#bdda0e` | `--color-lime` | surface, action | Alternate discovery actions. |
| group-offer and inquiry pages | Group-offer violet | `#592db5` | `--color-purple` | text, action | Text and arrow paired with lime actions. |

## Typography

- **neue-haas-unica** — Opening headlines, section headings, body, labels and controls. Light neo-grotesk with open, understated forms; regular weight for utility text. If unavailable, use **Inter**. Use 300 and 400; retain the tight tracking and compact leading. Font stack: "neue-haas-unica", "Inter", Arial, sans-serif.
- **fonts** — Editorial invitations, narrative captions, card titles, accordion labels and newsletter heading. Fine, high-contrast editorial serif with bracketed serifs and a bookish rhythm. If unavailable, use **Libre Caslon Display**. Use its regular cut for the light serif roles and match the line breaks. Font stack: "fonts", "Libre Caslon Display", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | neue-haas-unica | 300 | 40px | 0.95 | -0.02em | Major chapter headings and informational-page opening headlines. |
| editorial-heading | fonts | 300 | 40px | 0.95 | -0.02em | Invitations, illustrated calls and larger accordion labels. |
| opening | neue-haas-unica | 300 | 36px | 1 | -0.015em | Default landing promise, green and left-aligned. |
| editorial-title | fonts | 300 | 36px | 1 | -0.015em | Editorial card titles, smaller accordion labels and supporting invitations. |
| newsletter-heading | fonts | 300 | 28px | 30px | -0.015em | Narrow multi-line footer invitation. |
| lead-and-action | neue-haas-unica | 400 | 22px | 26px | -0.01em | Introductory paragraphs, navigation and full-size button labels. |
| narrative-caption | fonts | 300 | 22px | 26px | -0.01em | Image captions and expanded gallery-card descriptions. |
| body | neue-haas-unica | 400 | 18px | 22px | -0.01em | General paragraphs, directory links and compact announcement action. |
| eyebrow | neue-haas-unica | 400 | 14px | 18px | -0.01em, uppercase | Category labels, numbered idea markers and footer group labels. |

**Notes:**

- The identity is vector lettering, not an extra-bold version of the text face. Preserve that contrast between heavy identity and light prose.
- Heading sizes cluster closely at 36px and 40px; family switches do more hierarchy work than giant differences in size.
- Keep serif and sans leading compact and tracking negative. Do not apply the uppercase labels' casing to narrative headings.
- Use the 22px sans recipe for long introductory text, but the denser 18px recipe for explanatory sections. Body copy is not globally underlined; reserve underlines for text links.

## Layout

**Density:** Airy at section scale and compact within controls: long paper intervals separate closely set type and small functional groups.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small paragraph separation and announcement vertical padding. |
| 12px | Outer media gutter and small label-to-control spacing. |
| 16px | Button-pair gap and introductory paragraph separation. |
| 20px | Card padding and full-size button side padding. |
| 24px | Heading-to-support gap. |
| 26px | Inner text-column side padding layered inside the outer gutter. |
| 40px | Text-to-action distance and section-heading-to-gallery gap. |
| 48px | Intro top padding and conversion-dock side padding. |
| 96px | Inset-panel top and bottom breathing room. |
| 192px | Separation between major editorial sections. |

### Containers and grids

- **Full-width editorial grid**: gap 12px · side padding 12px. Nearly edge-to-edge photography. Text sits at an effective 32px left inset through nested columns; avoid a universal centered narrow wrapper.
- **Reading column**: max width 640px · side padding 26px. Invitations and paired explanatory copy; narrower opening promise uses 416px, and informational intro text can span 960px.
- **Journal triptych**: 3 columns · gap 12px. Equal portrait images, each 464px wide at desktop, with inset white editorial labels.
- **Offset portrait spread**: 2 columns · gap 12px. 583px-wide portraits shifted toward the right; one column begins 180px lower, leaving a conspicuous cream pocket at the left.
- **Inset feature pair**: 2 columns · side padding 96px. Broad white panels pair a 390px illustration or photograph with a text column; content begins about 126px from the viewport edge.

## Corner radius

| Element | Radius |
| --- | --- |
| Full-size buttons and editorial labels | 20px |
| Compact buttons and gallery arrows | 12px |
| Accordion toggles | 10px |
| Conversion dock | 40px |
| Broad feature panels | 72px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Whole page, including the long closing directory.

**CSS:** `background: #fdf9ed; color: #23212c`

#### Editorial label · level 1

**Use:** Readable islands laid over photographs.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 20px; box-shadow: none`

**Observed:** Compact white blocks float inside the lower left of images, leaving photography visible on every side.

**Transfer:** Size to the title or description, not the entire image width.

#### Broad white panel · level 0

**Use:** Illustrated calls, thematic accordions and detailed product profiles.

**CSS:** `background: #ffffff; border-radius: 72px; padding: 96px 0; box-shadow: none`

**Observed:** Inset from the cream page with large round corners; the panel feels like a sheet laid down, not an elevated dashboard card.

**Transfer:** Use for a meaningful change in narrative pace, not around every section.

## Components

### Navigation

**Use:** Simple top-level orientation beside the identity.

**CSS:** `display: flex; justify-content: flex-end; padding: 0 12px; color: #23212c`

**Text style:** `lead-and-action` — neue-haas-unica 400 · 22px/26px · tracking -0.01em

**Observed:** Text links align in one row at the top right, with a small outlined language switch at the end. The large identity occupies the left independently rather than sharing equal columns.

**States:** Declared: hover opacity 0.8 and underline on most navigation links; focus-visible not specified.

### Primary button

**Use:** Main editorial conversion or exploration action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0 20px; border-radius: 20px; background: #23212c; color: #ffffff`

**Text style:** `lead-and-action` — neue-haas-unica 400 · 22px/26px · tracking -0.01em

**Observed:** Label precedes a solid right arrow with an 8px gap. Adjacent alternative actions use a transparent background and a 1px ink outline with the same dimensions.

**States:** Declared: hover outline none; focus-visible not specified.

**Transfer:** Keep width content-driven and pair no more than two actions in a 16px-spaced row.

### Blue button

**Use:** Newsletter signup and supporting discovery actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0 20px; border-radius: 20px; background: #a6dfff; color: #dd5000`

**Text style:** `lead-and-action` — neue-haas-unica 400 · 22px/26px · tracking -0.01em

**Observed:** The arrow shares the orange label color. It appears beside the narrow serif newsletter invitation rather than as a full-width form.

**States:** Declared: hover outline none; focus-visible not specified.

### Compact announcement action

**Use:** Action inside the top announcement ribbon.

**CSS:** `display: flex; align-items: center; height: 32px; padding: 0 10px; border-radius: 12px; background: #dd5000; color: #ffffff`

**Text style:** `body` — neue-haas-unica 400 · 18px/22px · tracking -0.01em

**Observed:** Short label and right arrow sit inline with the orange announcement sentence on a 48px blue ribbon; a small dismiss control sits at the far right.

**States:** Declared: hover outline none; focus-visible not specified.

### Conversion dock

**Use:** Persistent conversion utility on consumer-oriented landing and guide pages.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 1000px; height: 128px; padding: 0 48px; border-radius: 40px; background: #fcbd1c`

**Observed:** Centered near the bottom of the viewport with 32px clearance. It contains three underlined input groups followed by a compact dark search action. It remains over the story but is absent from the footer and from group-inquiry pages.

**Transfer:** Make a product-appropriate selector or qualification dock with a few decisive inputs; keep the functional yellow island distinct from the editorial panels.

### Dock field

**Use:** An input-like selector within the conversion dock.

**CSS:** `padding: 4px 0 8px; border-bottom: 2px solid #23212c; color: #23212c`

**Text style:** `lead-and-action` — neue-haas-unica 400 · 22px/26px · tracking -0.01em

**Observed:** Small uppercase label above the selected value, with a tiny selector glyph at the right. Date-like paired values use a directional arrow between them.

**Transfer:** Keep labels quiet and choices readable; do not turn these fields into white input boxes.

### Editorial photo label

**Use:** Journal links and expanded photo-gallery descriptions.

**CSS:** `position: absolute; background: #ffffff; padding: 20px; border-radius: 20px; max-width: 352px`

**Text style:** `editorial-title` — fonts 300 · 36px/1 · tracking -0.015em

**Observed:** An uppercase category precedes the serif title. In galleries the active label grows to a 448px-wide narrative description with small previous/next controls and a position counter; inactive items retain a short category tab.

**Transfer:** Keep label width independent of image width and anchor it inside the lower-left image corner.

### Accordion toggle

**Use:** Reveal supporting details beside large serif topic names.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 24px; height: 24px; border: 1px solid #23212c; border-radius: 10px; color: #23212c; margin-left: 12px`

**Observed:** Tiny plus glyph sits in the outlined rounded square beside the text, not at the far edge of a ruled row. Topic labels use editorial-heading or editorial-title.

**States:** Declared: hover outline none; focus-visible not specified.

### Footer directory

**Use:** The expansive final section shared by all page types.

**CSS:** `background: #fdf9ed; padding: 32px 12px 24px; color: #23212c`

**Text style:** `body` — neue-haas-unica 400 · 18px/22px · tracking -0.01em

**Observed:** Oversized stacked green identity at left; the right side starts with a narrow serif newsletter invitation and Blue button, then a two-column directory. Uppercase group labels lead close-set links; social buttons and payment marks sit beneath, with legal links at the bottom.

**Transfer:** Keep the identity sculpture and invitation prominent even when the new directory has fewer links.

### Lime discovery button

**Only for:** group-offer and inquiry pages

**Use:** Discovery and inquiry actions in detailed white feature panels.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0 20px; border-radius: 20px; background: #bdda0e; color: #592db5`

**Text style:** `lead-and-action` — neue-haas-unica 400 · 22px/26px · tracking -0.01em

**Observed:** Uses the same solid right-arrow construction as the primary button. Blue and orange remain an alternate pairing within this page type.

**States:** Declared: hover outline none; focus-visible not specified.

## Imagery and graphics

### Lived-in environmental photography

**Use:** Opening spread, editorial triptych and horizontal story galleries.

**Observed:** Natural daylight, meadow greens, pale timber, cream bedding and dark architectural edges. Images show interiors, landscape, food and people at ease rather than polished studio poses. Portraits are tightly framed but retain context; landscape views supply wider breathing room. Most media corners are nearly square, while the opening portraits carry a strongly rounded upper-left corner.

**Transfer:** Show the product embedded in ordinary, desirable use. For a digital product, photograph its work setting, hands, paper or tools in warm daylight; use tactile still lifes when people or locations are unavailable. Preserve environmental color rather than adding a brand-color wash.

### Loose ink vignettes

**Use:** A signature pause beside invitations and practical guidance.

**Observed:** Playful black contour figures, leafy loops, oversized hands and a small open book sit without scenery in a 390–524px area. Related guidance uses a rain-and-umbrella figure; inquiry content has a green, roughly drawn object vignette. White or cream backing remains open and untextured.

**Transfer:** Draw an original small scene about the new product's human benefit. The minimum is one expressive object, one gestural figure or hand and a few environmental marks, not a generic polished icon.

**Build:** Use an SVG viewBox of 0 0 524 524. Draw 8–15 irregular open Bézier paths with rounded caps, dark 4–7px strokes and no fills except a few small ink dots. Cluster the subject in the central 390px, leave at least 40px breathing room, vary stroke thickness subtly, and add two or three loose looping curves. Use forest green instead of dark ink only for the inquiry illustration.

### Identity letter sculpture

**Use:** Dominant identity at the opening and a distinctive closing anchor.

**Observed:** Heavy forest-green uppercase shapes with rounded geometric counters. The opening is a 365×130px horizontal mark; the footer rearranges it into a stepped two-line 392×380px block. Informational openings use a smaller 246×87px horizontal mark.

**Transfer:** Make an original word sculpture or monogram from the new identity. Retain the mass, circular negative spaces and stepped closing silhouette; long names can use initials.

**Build:** Set original initials in a very heavy condensed sans, convert to SVG outlines and soften small corners. Fill with #006434. Fit a horizontal version inside a 365×130px viewBox, then create a 392×380px version by stacking two short groups and shifting the lower group right by roughly one letter width. Keep this artwork separate from the light heading font.

### Icons

**Observed:** Compact solid SVG arrows and selector glyphs, mostly 16px or 18px. Accordion plus signs are 14px inside a 24px outline control; gallery navigation uses 32px outlined buttons. Action icons match their label color.

**Transfer:** Use simple filled directional glyphs for actions and small plus signs for disclosure. Avoid a broad decorative icon vocabulary competing with the drawings.

## Section recipes

How recurring sections are built.

### First screen: Offset editorial opening

**Observed:** Cream canvas under a full-width 48px blue announcement. A 365×130px green Identity letter sculpture sits upper left; Navigation aligns top right. A green 36px opening promise spans two lines beneath the mark in a 416px column. Below, two 583×680px photographs occupy the right-hand majority: the right image begins first and the left image starts 180px lower, with a broad empty cream margin at the left. Each has a strongly rounded upper-left corner and otherwise restrained edges. Conversion dock floats over their lower portion. Within the first 900px, the announcement, identity, navigation, promise, upper photographs and dock are visible; narrative captions and the remainder of the photo sequence continue below the fold.

**Transfer:** Use a short benefit promise and a paired environmental or tactile product scene with the same offset and visual mass. If original photography is unavailable, create two large original ink-and-object compositions rather than replacing the spread with a small interface image. Informational pages open with the smaller horizontal mark, a 40px green heading and 22px lead copy; editorial-purpose and inquiry variants place an approximately 821px-wide landscape image to the right of a narrower text column.

**Avoid:** Do not center a giant headline over a full-bleed darkened photograph or place a conventional hero button stack beneath it; the identity, offset media and floating utility carry the opening.

**Text style:** `opening` — neue-haas-unica 300 · 36px/1 · tracking -0.015em

### Numbered editorial spread

**Observed:** Offset portrait spread continues with image-led stories. Beneath each image, a 14px uppercase idea identifier sits inline with a 22px serif narrative caption, separated from the photo by about 17px. Long cream intervals preserve the drifting rhythm.

**Transfer:** Use short numbered observations, use cases or sensory benefits tied to each image, without forcing a card background around the caption.

**Text style:** `narrative-caption` — fonts 300 · 22px/26px · tracking -0.01em

### Illustrated invitation

**Observed:** Editorial-heading in a 640px text column, 24px to body support and 40px to Primary button, with Loose ink vignettes opposite. A plain cream version uses a 524px illustration; a Broad white panel version uses a 390px vignette with 96px vertical breathing room.

**Transfer:** Use a helpful selection prompt or a concise benefit reminder. Keep the ink scene as the friendly counterweight to the action.

**Text style:** `editorial-heading` — fonts 300 · 40px/0.95 · tracking -0.02em

### Journal triptych

**Observed:** Heading above Journal triptych with 40px separation. Three tall photographs carry Editorial photo labels at the bottom left. A single Primary button follows after 48px.

**Transfer:** Show stories, customer perspectives or practical articles. Keep the photos much larger than their labels.

**Text style:** `heading` — neue-haas-unica 300 · 40px/0.95 · tracking -0.02em

### Wide story gallery

**Observed:** Near-edge-to-edge portrait rail with 583×680px images and 12px visual gaps; the next image peeks beyond the right edge. The first item has an expanded white narrative label and counter, while neighboring items show small category tabs. Some sections pair a left text introduction with the rail starting near the page center.

**Transfer:** Use for capability stories or use cases that benefit from substantial photography and optional detail, not a grid of equal text boxes.

**Text style:** `narrative-caption` — fonts 300 · 22px/26px · tracking -0.01em

### Split topic accordion

**Observed:** A light sans section heading and brief 18px introduction sit at left; the right column lists 36px or 40px serif topics, each followed immediately by Accordion toggle. Rows are unruled, with 8px vertical padding. A Broad white panel variant uses 96px top and bottom space.

**Transfer:** Make supporting detail feel editorial: short topics first, explanations behind disclosure. Choose cream for practical details and white for a thematic pause.

**Text style:** `editorial-title` — fonts 300 · 36px/1 · tracking -0.015em

### Alternating explanatory pair

**Observed:** A 40px sans heading with 18px copy is paired with a roughly 524px square or landscape photograph. Following sections reverse image and text. Actions sit 40px below the copy; the cream ground continues between sections.

**Transfer:** Develop one substantiated idea per pair, using an image that adds context rather than repeating the headline.

**Text style:** `heading` — neue-haas-unica 300 · 40px/0.95 · tracking -0.02em

### Sculptural directory ending

**Observed:** Footer directory gives the left portion to the 392×380px stepped Identity letter sculpture. The right area is a narrow 28px serif newsletter invitation alongside Blue button, then four grouped link lists in two columns. Small social squares, payment marks and legal links complete the bottom. All four page types end on cream rather than a dark band.

**Transfer:** End with a strong original identity silhouette and a useful low-friction invitation, not only navigation. Keep the closing artwork substantial even for short link lists.

**Text style:** `newsletter-heading` — fonts 300 · 28px/30px · tracking -0.015em

### Detailed offer and inquiry panels

**Only for:** group-offer and inquiry pages

**Observed:** Broad white panel pairs a 390px or 484px landscape photograph with heading, compact paragraphs and triangular-bullet facts. Subsequent panels reverse the sides. The final inquiry panel pairs a green ink vignette with a short numbered process and Lime discovery button.

**Transfer:** Use factual comparisons and a clear contact process for higher-consideration products. Preserve both the practical list and the playful illustrated closing call.

**Text style:** `heading` — neue-haas-unica 300 · 40px/0.95 · tracking -0.02em

## Page flow

**Storyline:** Benefit promise → lived-in visual evidence → helpful choices or capability stories → deeper explanation → illustrated invitation → identity-led directory.

### Experiential marketing landing page

1. **Promise** — Oversized identity, compact green promise, staggered environmental portraits and floating conversion utility.
2. **Emotional demonstration** — Numbered image captions describe small desirable moments.
3. **Decision assistance** — Serif prompt with explanatory copy, paired actions and an ink vignette.
4. **Conversion reminder** — Broad white illustrated invitation with a dark action.
5. **Editorial proof** — Three image-led stories with white serif labels.
6. **Closing invitation** — Sculptural identity, newsletter action and directory on cream.

**Transfer:** Let the customer feel the benefit before offering a helpful way to choose; use editorial stories instead of immediately listing specifications.

### Practical product or service guide

1. **Orientation** — Smaller identity, green heading and broad introductory copy.
2. **Product demonstration** — Horizontal portrait gallery with active narrative label.
3. **Objection handling** — Split introduction and large serif amenity accordion.
4. **Capability chapters** — Additional gallery rail beside explanatory copy.
5. **Next steps** — Illustrated white panel with practical bullets and a dark action.
6. **Preparation** — Ink vignette beside detailed guidance.
7. **Closing invitation** — Shared identity-led newsletter and directory.

**Transfer:** Separate what is included, what can be added and what happens next; retain the human imagery around practical detail.

### Values and substantiated impact explainer

1. **Position** — Green headline, reflective introductory paragraphs and large landscape photograph.
2. **Principle overview** — White panel with a question at left and serif topic accordion at right.
3. **Substantiated explanation** — Alternating photo/text chapters, with an occasional blue supporting action.
4. **Implementation detail** — Narrative gallery showing tangible materials and practices.
5. **Closing invitation** — Shared sculptural identity, newsletter and directory.

**Transfer:** Move from an accessible question to specific practices and partners; place quantified claims within prose rather than inventing a statistic dashboard.

### High-consideration group offer and inquiry page

1. **Audience promise** — Long green heading, narrow introduction and large landscape lifestyle image; no floating selector.
2. **Use-case demonstration** — Portrait rail with expanded narrative card.
3. **Offer comparison** — Alternating white panels with contextual photos, factual bullets and colored actions.
4. **Objection handling** — Serif topic accordion on cream.
5. **Process and closing call** — Green ink object drawing beside numbered inquiry steps and lime discovery action.
6. **Closing invitation** — Same cream identity-led directory as the consumer pages.

**Transfer:** Replace instant configuration with a concise inquiry process when the purchase needs coordination, keeping the colorful actions scoped to this offer type.

## Writing

Warm, direct and gently playful, with an editorial interest in ordinary pleasures. Practical explanations are candid and specific, while invitations sound like a helpful person rather than a sales pitch.

**Do not copy:** Do not reuse Raus names, wordmarks, illustrations, partner names, cabin facts, discounts, dates, impact claims, contact details or customer quotations. Source examples demonstrate voice only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your'; use 'we' for the organization when describing commitments or assistance.
- **Rhythm:** Short one- or two-sentence invitations alternate with longer explanatory paragraphs. Sentence case predominates; questions, parenthetical qualifications and occasional exclamation marks keep the tone conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A direct invitation linking a concrete product to a welcome change in the reader's routine. | 6–12 words | “Book restful space outside your daily routine.” |
| Image caption | A familiar everyday action redirected toward a small personal pleasure. | 6–10 words | “Schedule appointments. But just with yourself.”<br>“Watch the wind moving through the treetops.” |
| Decision prompt | Acknowledge uncertainty, then offer a simple route forward. | 8–15 words | “Not sure where to go? Find your cabin in one minute.” |
| Section heading | Plain-language promise or curious question rather than an abstract category. | 3–9 words | “Facilities that are always included.”<br>“Curious about details?” |
| Action | Verb plus concrete destination or task. | 2–6 words | “Choose your cabin”<br>“Find out more about our impact” |

**Words and phrasing to use:** take a break; close to you; find your; curious; together; carefully; here's what comes next

**Avoid:** revolutionary; disruptive; unlock limitless potential; premium solution ecosystem; hurry before it's gone

**Rules:**

- Connect product benefits to an observable moment or useful task.
- Keep practical qualifications visible instead of replacing them with sweeping promises.
- Use questions as helpful entry points, not a repetitive rhetorical pattern in every heading.
- When explaining values, describe specific actions, materials or processes and keep numerical claims attributable to the new product.

## Do's and Don'ts

### Do

- Keep opening and chapter headings light at weight 300, with 36px or 40px type rather than oversized bold display prose.
- Retain the green identity sculpture at both ends, using a wide horizontal opening and a stepped closing arrangement.
- Use the cream ground continuously through the footer; introduce white as discrete rounded sheets or photograph labels.
- Let 583×680px portraits carry the emotional story, with the 180px offset creating the opening's asymmetry.
- Keep primary actions 48px high with 20px corners, solid arrows and content-driven widths.
- Use 24px between heading and support, 40px before actions, and 96px inside broad panels.
- Let numbered or uppercase 14px labels sit alongside more expressive 22px serif captions.
- Preserve the illustrated pause, giving an original ink vignette a substantial 390–524px area.

### Don't

- Do not turn the 20px button corners into universal full pills; the 40px conversion dock and 12px compact actions have distinct geometry.
- Do not use forest green as a full-page fill; it is concentrated in identity, opening words and selected line art.
- Do not add drop shadows or glass blur to white panels or the yellow dock; separation comes from flat color and spacing.
- Do not place every paragraph in a bordered card; most explanations sit directly on cream.
- Do not make all type sans-serif; the 40px and 36px serif invitations and labels are essential to the editorial contrast.
- Do not set every paragraph at 22px; reserve that scale for lead copy and use 18px for explanatory passages.
- Do not give ordinary marketing actions the lime-and-purple pairing; it belongs to the group-offer inquiry variant.
- Do not replace warm environmental images with glossy isolated renders on saturated backgrounds.

## Motion and responsive

### Motion

**Observed:**

- Full-size buttons declare 0.2s transitions; text links declare hover opacity 0.8, with navigation underlines on most links.
- The conversion dock declares 0.4s cubic-bezier(0.665, 0.425, 0.44, 1.105) with 0.1s delay.
- The opening portrait spread uses translated layers, including a 180px vertical displacement.

**Transfer:**

- Use the declared dock transition for its entry or geometry change while retaining the stable, readable selector grouping.
- Preserve staggered photo placement without requiring movement to communicate the composition.

**Unknown:**

- Exact scroll choreography, mobile motion and focus-visible appearance are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 330px, 360px, 390px, 400px, 420px, 480px, 576px, 768px, 992px and 1200px.

**Transfer:**

- On narrow screens, keep the identity first and preserve the photo sequence as a single editorial column with a smaller stagger rather than squeezing two portraits side by side.
- Adapt the floating utility into a compact usable selector without covering the primary story; stack illustrated pairs and footer content while retaining the stepped identity.

**Unknown:**

- Mobile dimensions, actual breakpoint-specific type recipes and navigation collapse behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
