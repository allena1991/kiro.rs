# Weav — ribboned color, human tools

## Overview

A warm, assertive software style that pairs electric blue and blush with unusually tactile product demonstrations. Tight medium-weight grotesk headlines sit above light, conversational body text, while broad flat color fields alternate with white and warm gray. Real hands, crisp device frames and isolated interface fragments give the spacious compositions a human scale. It suits products that want to feel capable and approachable rather than futuristic or corporate.

### Essentials

- Color acts as architecture, not decoration: electric blue #2052eb and blush #fadbe5 occupy whole opening and interlude bands, while white and #e7e7e2 carry extended demonstrations. Keep the opening fully saturated and alternate it with broad light chapters rather than scattering bright cards everywhere.
- Headlines compress ordinary speech into emphatic blocks: STK Bureau Sans Medium at 66px/1.1, weight 500, -0.06em tracking; smaller interludes use 42px/1.1 and -0.04em. Light 20px/1.4 paragraphs provide the counterweight.
- The opening gives a human-held product the same status as the promise: a 520px text column in a 1120px composition faces an oversized cutout device on flat blue. Both headline, supporting paragraph, 48px actions and most of the device are visible within 900px.
- Actions are soft rectangles, not capsules: 12px corners, 48px height, medium 18px text, and a fine right arrow separated by 8px. White is the conversion fill on blue; blue is the conversion fill on light surfaces.
- A repeating ribbon seam joins contrasting chapters: a full-width 120px patterned strip with rounded diagonal interlocking shapes, repeated at 236px tile width. Carry this device into every new design using an original tile in the same two-color, soft-edged rhythm.
- Product proof is staged at two scales: monumental black-framed devices across a 1280px stage and small isolated UI fragments floating inside 10px-radius paired cards. If finished product media is unavailable, use a carefully typeset miniature workflow with real content, never an abstract empty screen.
- The ending is a roomy conversion statement integrated with the footer: a 66px two-line heading, 24px copy/action gaps, then a distant logo opposite three 240px link columns. Default to a white panel with 20px top corners; keep the dark commerce version scoped to pricing.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#2052eb` | `--color-blue` | background, text, action, accent | Default saturated canvas, light-section headlines, interface emphasis and light-section conversion buttons. |
| Blush | `#fadbe5` | `--color-blush` | background, text, action | Contrasting chapter canvas, headline color on blue, ribbon seams and compact navigation conversion fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blush on blue wash | `#3660ea` | `--color-blue-wash` | surface, action | Visible blush at 10% over blue for secondary actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#262320` | `--color-ink` | text, background | Primary reading text and technical reassurance bands; full canvas for the commerce theme. |
| Warm gray | `#e7e7e2` | `--color-stone` | background, surface, text | Workspace chapters, secondary neutral stages and light text on charcoal. |
| Light charcoal rule | `#e9e9e9` | `--color-rule` | border | Visible result of rgba(38,35,32,0.1) on white; thin accordion and footer dividers. |
| Light stone wash | `#ecece8` | `--color-stone-wash` | surface | Visible white at 20% on stone for paired proof cards. |
| White | `#ffffff` | `--color-white` | background, surface, text, action | Main proof panels and closing canvas; primary conversion fill on blue and text on blue buttons. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| detailed product tours | Aqua | `#a5f0f3` | `--color-aqua` | background, text, action | Opening canvas and reversed text for the teal product-tour theme. |
| detailed product tours | Deep teal | `#194249` | `--color-teal` | background, text, action | Replaces blue for the detailed product-tour theme, paired with aqua. |
| pricing pages | Commerce orange | `#ff5a15` | `--color-orange` | action, accent, border | Recommended plan marks and outline, featured plan action and final conversion action; do not spread it to the default blue theme. |
| pricing pages | Muted warm gray | `#9a9994` | `--color-muted-dark` | text | Secondary descriptions on charcoal, using stone at 60% opacity. |
| detailed product tours | Pale teal gray | `#f4f6f6` | `--color-teal-wash` | surface | Visible deep teal at 5% on white for product-tour proof cards. |

## Typography

- **STK Bureau Sans** — All marketing headings, paragraphs, navigation and actions; Light, Book and Medium cuts. Compact contemporary grotesk with open counters and soft, everyday forms; highly compressed tracking in headlines. If unavailable, use **Inter Tight**. Use 300, 400 and 500; preserve tight headline tracking and check line breaks. Font stack: "STK Bureau Sans", "Inter Tight", Arial, sans-serif.
- **Geist Mono** (only for numbered product-tour chapters) — Two-digit chapter indices. Small light monospace, subordinate to the grotesk headings. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | STK Bureau Sans | 500 | 66px | 1.1 | -0.06em | Opening promises, major feature chapter headings and closing statements. |
| heading | STK Bureau Sans | 500 | 42px | 1.1 | -0.04em | Interludes, technical reassurance headings and centered FAQ titles; also price numerals in commerce layouts. |
| heading-small | STK Bureau Sans | 500 | 28px | 1.3 | -0.03em | Accordion titles, short editorial assertions and smaller section headings. |
| editorial-body | STK Bureau Sans | 300 | 28px | 1.3 | -0.01em | Long-form belief statements and concluding editorial explanations. |
| body | STK Bureau Sans | 300 | 20px | 1.4 | normal | Primary supporting copy under headlines. |
| label | STK Bureau Sans | 500 | 18px | 1 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Centered proof-card titles and footer column titles. |
| action | STK Bureau Sans | 500 | 18px | 1.4 | normal | Main 48px button labels. |
| body-small | STK Bureau Sans | 300 | 16px | 1.4 | normal | Card explanations, benefit lists and technical support copy. |
| navigation | STK Bureau Sans | 400 | 16px | 1.4 | -0.01em | Header links and footer links. |
| action-small | STK Bureau Sans | 500 | 16px | 1.4 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Compact 40px header action. |
| eyebrow | STK Bureau Sans | 500 | 14px | 16px | normal | Sentence-case pill labels above feature headings. |
| hero-kicker | STK Bureau Sans | 500 | 14px | 1.1 | -0.06em | Small unboxed category line immediately above the opening promise. |
| query-caption | STK Bureau Sans | 400 | 12px | 16px | normal | Tiny conversational query in the rectangular question chip. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | plan-title | STK Bureau Sans | 500 | 20px | 1.32 | -0.029em | Plan names, add-on names and minor price labels. |
| FAQ and comparison content | faq-body | STK Bureau Sans | 300 | 18px | 1.4 | normal | Expanded answers and denser explanatory copy. |
| pricing pages | billing-label | STK Bureau Sans | 500 | 16px | 1.32 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Billing selector labels. |
| numbered product-tour chapters | chapter-index | Geist Mono | 300 | 12px | 16px | normal | Two-digit indices beside the small chapter marker. |

**Notes:**

- Headline tracking tightens from -0.03em at 28px to -0.06em at 66px; do not substitute a heavy bold weight for this compression.
- Body copy stays light at weight 300. Book 400 is reserved for navigation and small query text; Medium 500 handles headings and actions.
- Use sentence case throughout. A small category line can be visually subordinate even when the main promise dominates the page.
- Keep the default headline scale consistent across opening, feature chapters and closing; the closing is not reduced to an ordinary footer label.

## Layout

**Density:** Airy at section scale, compact within the product fragments: broad 80px chapter intervals frame tight 8px and 10px details.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Arrow-to-label gaps and compact benefit or link groups. |
| 10px | Paired proof-card gutters, opening copy group gaps and adjacent actions. |
| 16px | Card heading-to-description gap and footer heading-to-link grouping. |
| 24px | Standard heading, body and action separation. |
| 32px | Opening copy-to-actions interval. |
| 40px | Proof-card padding and media-to-caption breathing room. |
| 60px | Media-to-editorial explanation separation and footer subdivisions. |
| 80px | Major chapter padding, chapter content gaps and desktop side inset. |
| 120px | Pattern seam height and spacious interlude lead-in. |
| 160px | Opening text lead-in beneath the navigation. |

### Containers and grids

- **main-container**: max width 1280px · side padding 80px. Centered desktop content inside full-width color fields; keeps all major headings, cards and footer columns aligned.
- **opening-container**: max width 1120px · gap 80px. Narrower text-and-object opening with a 520px text column and an oversized object to the right; media can extend beyond the container.
- **paired-proof**: max width 1280px · 2 columns · gap 10px. Two equal 635px cards, each with a generous media area and lower caption.
- **editorial-column**: max width 800px. Centered long-form manifesto and FAQ text; headings remain left-aligned within the column.
- **centered-call**: max width 720px. Centered pricing or conversion interludes with constrained supporting copy.
- **resource-grid**: max width 1280px · 3 columns · gap 40px. Three 400px article previews with wide, short images above title and date.
- **plan-grid** (only for pricing pages): max width 1280px · 4 columns · gap 14px. Equal 310px plan columns, aligned prices, benefits and bottom actions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 12px |
|  | proof-cards | 10px |
|  | chapter-panels | 20px |
|  | question-chip | 6px |
|  | eyebrow-pill | 9999px (pill) |
| pricing pages | billing-control | 100px |

## Surfaces and depth

### Surfaces

#### Blue canvas · level 0

**Use:** Default opening and conversational interludes.

**CSS:** `background: #2052eb; color: #fadbe5`

**Observed:** Flat, intense color rather than a luminous gradient; headings and main cutout object sit directly on the field.

**Transfer:** Let full-width color carry the personality.

#### Blush chapter · level 0

**Use:** Warm feature chapter canvas.

**CSS:** `background: #fadbe5; color: #2052eb`

**Observed:** A broad warm field containing blue headings and white or blue demonstration cards.

**Transfer:** Use behind a substantial demonstration, not as a tiny decorative badge.

#### White panel · level 1

**Use:** Feature chapters and default final conversion/footer block.

**CSS:** `background: #ffffff; border-radius: 20px 20px 0px 0px; color: #262320`

**Observed:** Large rounded upper corners create a sheet placed over the previous color field. Some chapters are inset by 10px on blue.

**Transfer:** Keep the large sheet treatment distinct from smaller proof-card corners.

#### Stone chapter · level 0

**Use:** Large device demonstrations and workspace explanations.

**CSS:** `background: #e7e7e2; color: #262320`

**Observed:** Warm matte neutral separates black device hardware from bright blue chapters.

**Transfer:** Use as an uninterrupted backdrop for detailed product imagery.

#### Proof card · level 1

**Use:** Paired media cards on stone.

**CSS:** `background: rgba(255, 255, 255, 0.2); border-radius: 10px; overflow: hidden`

**Observed:** Almost-flat tonal separation, without a hard border or drop shadow.

**Transfer:** Keep the surrounding canvas visible through the subtle tint.

#### Technical band · level 0

**Use:** Developer or trust reassurance.

**CSS:** `background: #262320; color: #e7e7e2; border-radius: 20px 20px 0px 0px`

**Observed:** A dark interruption with light text, a small question chip and a framed technical illustration.

**Transfer:** Reserve it for a more technical argument rather than making the entire default page dark.

#### Teal chapter · level 0

**Only for:** detailed product tours

**Use:** Reversed product-tour chapters.

**CSS:** `background: #194249; color: #a5f0f3; border-radius: 20px`

**Observed:** Alternates with white chapters and uses aqua headings; pale cards contain the product details.

**Transfer:** Keep this palette together as a complete tour theme.

#### Pale tour card · level 1

**Only for:** detailed product tours

**Use:** Isolated workflow fragments.

**CSS:** `background: rgba(25, 66, 73, 0.05); border-radius: 10px`

**Observed:** Cool near-white on the white canvas, much lighter than the teal chapter.

**Transfer:** Give each fragment an uncluttered field.

#### Commerce canvas · level 0

**Only for:** pricing pages

**Use:** Opening, plans, add-ons and closing.

**CSS:** `background: #262320; color: #e7e7e2`

**Observed:** Mostly monochrome with orange restricted to the recommended option and conversion.

**Transfer:** Preserve the dark opening and ending around a light comparison/FAQ middle.

## Components

### Navigation

**Use:** Low-profile header shared across page types.

**CSS:** `background: #2052eb; height: 90px; padding: 0px 80px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — STK Bureau Sans 400 · 16px/1.4 · tracking -0.01em

**Observed:** Small wordmark at left, compact central link cluster with a downward chevron on the product link, sign-in and a blush 40px conversion button at right. The product-tour variant uses aqua/teal and the commerce variant charcoal/stone.

**Transfer:** Use the new identity at a similarly modest scale, retaining the three-part alignment.

### Primary button

**Use:** Main action on light chapters and in the default closing.

**CSS:** `background: #2052eb; color: #ffffff; border-radius: 12px; height: 48px; padding: 1px 20px 2px 24px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `action` — STK Bureau Sans 500 · 18px/1.4

**Observed:** Text precedes a thin right arrow. Width follows label length. Product tours replace blue with teal; the pricing closing uses orange.

**Transfer:** Keep a single strong action per local argument.

### Inverse button

**Use:** Primary conversion on blue.

**CSS:** `background: #ffffff; color: #2052eb; border-radius: 12px; height: 48px; padding: 1px 20px 2px 24px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `action` — STK Bureau Sans 500 · 18px/1.4

**Observed:** Sits first in the opening action pair, with a right arrow. Pricing plans also use white actions, with charcoal text and one orange featured action.

### Secondary button

**Use:** Lower-emphasis action beside the main conversion.

**CSS:** `background: rgba(250, 219, 229, 0.1); color: #fadbe5; border-radius: 12px; height: 48px; padding: 1px 24px 2px 24px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — STK Bureau Sans 500 · 18px/1.4

**Observed:** Translucent tonal fill rather than outline; the developer variant can add a right arrow. On white, a blue 10% wash replaces the blush tint.

### Eyebrow pill

**Use:** Small sentence-case feature identifier.

**CSS:** `border-radius: 9999px; padding: 6px 12px 5px 12px; display: inline-flex; align-items: center; gap: 6px; color: #2052eb`

**Text style:** `eyebrow` — STK Bureau Sans 500 · 14px/16px

**Observed:** A small rounded label precedes the headline; its low-contrast edge is subordinate to the text rather than a heavy badge fill.

### Question chip

**Use:** Conversational introduction to a feature or technical argument.

**CSS:** `background-color: rgba(32, 82, 235, 0.1); background-image: conic-gradient(from 180deg, rgba(32, 82, 235, 0.1) 0deg, rgba(32, 82, 235, 0.1) 360deg); border-radius: 6px; padding: 12px 12px 11px 12px; display: inline-flex; align-items: center; gap: 6px`

**Text style:** `query-caption` — STK Bureau Sans 400 · 12px/16px

**Observed:** Small identity mark, tiny assistant prefix and a natural-language question form one strip. Dark bands reverse to blush at 10%; tours use teal at 8%.

**Transfer:** Use a real buyer question as the caption, not an abstract category name.

### Proof card

**Use:** A single benefit illustrated through a focused product fragment.

**CSS:** `background: rgba(255, 255, 255, 0.2); border-radius: 10px; padding: 40px; display: flex; flex-direction: column; align-items: center; justify-content: flex-end; gap: 40px; overflow: hidden`

**Text style:** `label` — STK Bureau Sans 500 · 18px/1 · tracking -0.02em

**Observed:** Media takes most of the height; centered title and body-small description sit at the bottom with 16px between them. Tour cards use pale teal-gray and more media space.

**Transfer:** Show one coherent task, not an entire dense dashboard inside every card.

### FAQ row

**Use:** Objection handling in a constrained reading column.

**CSS:** `max-width: 800px; display: flex; flex-direction: column; gap: 24px; padding-bottom: 10px`

**Text style:** `heading-small` — STK Bureau Sans 500 · 28px/1.3 · tracking -0.03em

**Observed:** Question left, small chevron at right, hairline separator across the row. The expanded answer uses faq-body; one answer is open while other rows stay compact.

**Transfer:** Answer practical questions in complete sentences rather than slogan fragments.

### Footer columns

**Use:** Navigation following the final conversion statement.

**CSS:** `display: flex; align-items: flex-start; justify-content: flex-start; row-gap: 40px`

**Text style:** `navigation` — STK Bureau Sans 400 · 16px/1.4 · tracking -0.01em

**Observed:** Identity at left, three 240px link columns aligned on the right, each with a label heading, 16px lead gap and tightly stacked links. A full-width 1px rule separates this from legal links left and copyright right. Pricing reverses the whole ending onto charcoal.

**Transfer:** Keep the footer visually attached to the final call rather than introducing another boxed block.

### Compact conversion

**Use:** Header action.

**CSS:** `background: #fadbe5; color: #2052eb; border-radius: 12px; height: 40px; padding: 0px 18px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action-small` — STK Bureau Sans 500 · 16px/1.4

**Observed:** Text-only compact version; not a pill. Tours reverse teal and aqua; commerce uses stone with charcoal text.

### Plan card

**Only for:** pricing pages

**Use:** Comparable plan summaries.

**CSS:** `border-radius: 20px; padding: 24px 20px; display: flex; flex-direction: column; align-items: flex-start; gap: 40px; overflow: hidden`

**Text style:** `plan-title` — STK Bureau Sans 500 · 20px/1.32 · tracking -0.029em

**Observed:** A small repeated ribbon mark indicates tier, followed by name, heading-sized price, subdued cadence, short description, divider, checked benefits and bottom action. A faint rounded outline defines each column; the recommended tier has an orange outline, tiny popularity pill and orange action.

**Transfer:** Align the repeated content and bottom actions; highlight only one tier.

### Billing selector

**Only for:** pricing pages

**Use:** Choose payment cadence above plan columns.

**CSS:** `background: rgba(231, 231, 226, 0.05); border-radius: 100px; padding: 6px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `billing-label` — STK Bureau Sans 500 · 16px/1.32

**Observed:** White selected segment with charcoal text, 10px 18px padding and 100px radius; unselected label remains light directly on the dark tray.

## Imagery and graphics

### Human-held device

**Use:** Main opening object and occasional large secondary proof.

**Observed:** Photoreal hands hold a bright, black-edged phone with legible conversational product UI. The hand and device are cut out onto a flat saturated canvas without a rectangular photo frame. The phone stands tall opposite the text, while the hand extends beyond the lower edge.

**Transfer:** Use a real interaction with the new product, isolated cleanly against the chapter color. If physical interaction is not relevant, create a polished black-framed device rendering with a meaningful, populated product state; keep the same scale and asymmetry.

### Monumental interface

**Use:** Large demonstration stages.

**Observed:** Crisp white software interfaces sit inside black tablet or laptop bezels, often with a camera notch. The device occupies nearly the full 1280px content width and is cropped at a stage edge, leaving the surrounding matte gray or pale teal surface visible.

**Transfer:** Show the new product's actual hierarchy and realistic content at readable scale. Use one strong frame rather than a stack of generic browser windows.

### Exploded workflow

**Use:** Paired benefit cards and explanatory media.

**Observed:** Small message bubbles, knowledge rows, source lists and settings fragments float in ample white, blue or pale neutral space. Dotted connectors and tiny avatars explain a process without requiring the entire application shell.

**Transfer:** Isolate a short input → processing → result workflow. Minimum version: three carefully aligned HTML/SVG fragments, a subtle dotted connector and a short human-readable result.

### Ribbon seam

**Use:** Signature chapter transitions across the design.

**Observed:** A 120px full-width strip repeats soft diagonal interlocking ribbon shapes, using the colors of the adjacent fields. Edges are rounded and concave, not zigzag points; the pattern feels woven rather than like a standard wave.

**Transfer:** Create an original tile using the new identity's geometry, retaining the repeating diagonal rhythm and two-color transition.

**Build:** Make a 236px by 120px SVG pattern tile with repeated rounded diagonal necks connecting wider lobes; use cubic curves to create opposing concave sides and rounded ends. Stagger two rows so their lobes interlock, and repeat horizontally at 236px width. Fill with blush against blue, stone against charcoal, or the two neighboring chapter colors; clip to a 120px band without blur or shadow.

### Resource preview

**Use:** Editorial article grids.

**Observed:** Three landscape 400px by 180px previews sit above medium 28px titles and small dates on blue, with blush text.

**Transfer:** Use relevant editorial artwork with a consistent short landscape aspect, distinct from the oversized product stages.

### Assisted-response glow

**Only for:** product-assistance demonstrations

**Use:** A small active response fragment, never the whole canvas.

**Observed:** A centered white response box has a thin rainbow perimeter and soft localized multicolor glow; a pale spectral haze fills the top of its otherwise white card. The effect is contained within the proof media, surrounded by matte teal.

**Transfer:** Use the treatment around a single assisted or generated output, while keeping all reading surfaces white.

**Build:** Place a white rounded rectangle over a slightly larger rounded SVG stroke with a purple-to-blue-to-cyan-to-lime-to-orange gradient. Duplicate the stroke behind with low opacity and roughly 20px blur. Put broad low-opacity cyan, violet and lime radial washes along the upper card edge, fading into white; keep exact stops subordinate to the soft glow.

### Icons

**Observed:** Small flat filled utility symbols are mostly 24px; navigation chevrons and action arrows use 24px outlines with 1.5px round strokes. Benefit lists use compact checked squares; tour chapters pair a small patterned marker with a two-digit mono index.

**Transfer:** Choose restrained filled utility icons for feature lists and thin outline arrows for navigation. Match each chapter's foreground color, and keep them smaller than the text hierarchy.

## Section recipes

How recurring sections are built.

### First screen: Human-scale promise opening

**Observed:** A 90px Navigation shares the uninterrupted Blue canvas. Below it, a 1120px composition places a 520px text block toward the left, inset more deeply than ordinary sections, and an oversized hand-held phone on the right. The text begins with hero-kicker, then a tightly tracked display promise wrapping into four emphatic lines, a three-line body paragraph and an Inverse button plus Secondary button separated by 10px. The copy-to-action interval is 32px. Layers run from flat blue to cutout device and hand, then foreground text/actions and the Ribbon seam at the bottom. Within the first 900px the headline, support, actions and almost the entire phone are visible; the hand and repeating seam continue below, with proof and detailed content further down.

**Transfer:** Retain the equal rhetorical weight of a concrete human benefit and a tangible product object. Without custom photography, use a polished device rendering containing one convincing task outcome. Detailed tours open in aqua/teal with one primary action and a Question chip; pricing opens centered on charcoal above plan summaries; a company narrative opens with a centered title and the Ribbon seam rather than the device.

**Avoid:** Do not center the default promise above a small dashboard thumbnail, put the phone in a photo card, or replace the saturated field with a generic pastel gradient.

**Text style:** `display` — STK Bureau Sans 500 · 66px/1.1 · tracking -0.06em

### Feature chapter lead

**Observed:** Eyebrow pill, display heading and body copy occupy the left two-thirds of the 1280px container; a narrow checked-benefit list is aligned toward the lower right. Standard internal separation is 24px; the media stage follows after 80px. Some chapters add a Primary button below the paragraph.

**Transfer:** State one meaningful outcome and support it with three compact benefits; let the subsequent media substantiate the claim.

**Text style:** `display` — STK Bureau Sans 500 · 66px/1.1 · tracking -0.06em

### Paired proof and editorial pair

**Observed:** Two Proof cards use a 10px gutter, contrasting white/blue or pale neutral fills, and deep media space. A follow-up row places a short heading-small assertion left and body text right, separated by the column structure rather than a box.

**Transfer:** Pair two complementary aspects of one capability, then translate the visual into a concise takeaway.

**Text style:** `heading-small` — STK Bureau Sans 500 · 28px/1.3 · tracking -0.03em

### Conversational interlude

**Observed:** A Blue canvas band uses a 720px text measure, heading and body 24px apart. Some are left-aligned with 120px lead-in; conversion-oriented bands center display copy and a blush action, with 80px top/bottom padding.

**Transfer:** Interrupt detailed proof with a short, human-scale promise or next-step invitation.

**Text style:** `heading` — STK Bureau Sans 500 · 42px/1.1 · tracking -0.04em

### Technical reassurance

**Observed:** Technical band places a Question chip, heading, body-small and tonal action opposite a 640px illustration area. Technical imagery uses real request or key-management fragments, not decorative code rain.

**Transfer:** Use a specific technical fact and a credible diagram or interface fragment, keeping supporting detail subordinate.

**Text style:** `heading` — STK Bureau Sans 500 · 42px/1.1 · tracking -0.04em

### Objection handling

**Observed:** Centered 720px heading/support block leads to an 800px column of FAQ rows. Questions use heading-small, answers faq-body, separators span the column and a small chevron sits at the far right.

**Transfer:** Use fewer concrete questions when content is short; preserve the visual contrast between the compact questions and the expanded explanation.

**Text style:** `heading` — STK Bureau Sans 500 · 42px/1.1 · tracking -0.04em

### Integrated conversion ending

**Observed:** A White panel starts with an 80px inset and display statement spanning roughly two lines. Support text and Primary button follow at 24px intervals. About 142px separates the button from the footer column headings; Footer columns then lead to a rule and legal row. The same structure closes the default landing, company narrative and product tour; the tour changes headings/actions to teal, while pricing keeps charcoal, stone text and an orange action.

**Transfer:** End the argument with a confident invitation, then let site navigation share the same generous field. Keep the statement left-aligned and much larger than footer labels.

**Text style:** `display` — STK Bureau Sans 500 · 66px/1.1 · tracking -0.06em

### Numbered capability chapter

**Only for:** detailed product tours

**Observed:** Small patterned marker and chapter-index sit above a display heading. White chapters with teal type alternate with Teal chapter panels and aqua type. Media can be paired cards, a full-width device or three narrow workflow cards; editorial explanation follows below.

**Transfer:** Use numbering to make a long product tour navigable without applying it to every short landing page.

**Text style:** `display` — STK Bureau Sans 500 · 66px/1.1 · tracking -0.06em

### Plan choice and comparison

**Only for:** pricing pages

**Observed:** Centered display promise and short body line on Commerce canvas lead to Billing selector and four Plan cards. Add-ons follow in a two-column grid of low-contrast outlined cards with prices lower left and compact actions lower right. A Ribbon seam introduces a stone comparison chapter containing a white table with category headings, evenly aligned plan columns and very pale alternating bands. A large light-weight testimonial precedes the FAQ.

**Transfer:** Separate the fast plan decision from exhaustive comparison; restrict orange to the recommended option and conversion.

**Text style:** `display` — STK Bureau Sans 500 · 66px/1.1 · tracking -0.06em

### Manifesto column

**Only for:** company narrative pages

**Observed:** A centered 800px reading column on blush follows a blue title band and Ribbon seam. A small pill precedes the display statement. Nine light editorial-body paragraphs, separated by 32px, build an argument without photos, portraits or card grids.

**Transfer:** Write a coherent point of view about the problem being changed, keeping the long text exceptionally readable.

**Text style:** `editorial-body` — STK Bureau Sans 300 · 28px/1.3 · tracking -0.01em

## Page flow

**Storyline:** Human benefit → tangible demonstration → capability proof → practical reassurance → a clear next step and integrated navigation.

### Broad marketing landing page

1. **Promise** — Blue split composition balances a direct reader problem with a human-held device.
2. **Social proof** — A narrow trust statement and row of single-color customer marks sit before the feature story.
3. **Product orientation** — A vertical capability accordion sits beside a large changing device demonstration.
4. **Capability proof** — Alternating blush, white and stone chapters combine oversized headings, checked benefits, paired fragments and full-width device stages.
5. **Conversion interludes** — Blue bands introduce brief promises and a centered pricing invitation.
6. **Discovery and reassurance** — Small feature links and article previews precede a dark technical/API argument.
7. **Closing call** — White conversion statement flows directly into the three-column footer and legal row.

**Transfer:** Borrow the alternating scale of promise, media and detail rather than reproducing the original number of chapters.

### Detailed product tour

1. **Promise** — Aqua opening with a query chip, dark teal promise and hand-held phone.
2. **Orientation** — A dark teal grid of compact feature links introduces the tour.
3. **Capability chapters** — Numbered white/teal chapters show paired workflow fragments, large devices and short editorial explanation.
4. **Objection handling** — White FAQ chapter with one answer expanded.
5. **Technical reassurance** — Dark privacy and API rows pair explanatory copy with technical media.
6. **Next step** — Teal pricing invitation leads into a white teal-accented conversion/footer ending.

**Transfer:** Use this complete color variant when the page is a deep tour, not as isolated teal accents inside the default blue theme.

### Pricing and purchase confidence

1. **Promise** — Centered light headline on charcoal introduces a straightforward cost proposition.
2. **Plan choice** — Billing selector and four outlined plan columns with one orange recommendation.
3. **Expansion options** — Two-by-two add-on cards pair explanations, prices and compact purchase actions.
4. **Detailed comparison** — A ribbon transition introduces a light comparison table and a large testimonial.
5. **Objection handling** — White FAQ resolves billing and capacity questions.
6. **Product reassurance** — Stone panel pairs cropped device imagery with a product-discovery action, then a ribbon returns to dark.
7. **Closing call** — Charcoal conversion/footer with a light display statement and orange action.

**Transfer:** Keep choices fast to scan before presenting the dense comparison, and preserve the intentionally dark ending.

### Company point of view

1. **Identity** — Centered blush title on blue with a small ribbon mark and patterned seam.
2. **Belief** — Blush reading field with a small mission label and large blue thesis.
3. **Argument** — A single 800px column of light 28px paragraphs builds from observed frustration to a positive belief.
4. **Closing call** — White conversion/footer repeats the shared blue-accented ending.

**Transfer:** Replace product demonstration with a clear editorial argument, not an unrelated team-photo collage.

## Writing

Direct, warm and slightly impatient with ineffective software. Confidence comes from concrete jobs and practical outcomes, not technical mystique; the product sounds helpful and competent.

**Do not copy:** Do not reuse Weav's name, wordmark, customer marks, exact ribbon artwork, customer quotations, plan prices, performance percentages, compliance claims or branded product claims. Examples demonstrate voice only; replace them with substantiated content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your team. Refer to the product by name when explaining what it does; use we mainly for beliefs and commitments.
- **Rhythm:** Conversational promises can be full sentences, balanced contrasts or two short clauses. Headline lengths range from brief 5-word assertions to 12-word reader problems; supporting copy is usually one short paragraph. Contractions and sentence fragments keep the language human.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the burden the reader did not sign up for, or promise a concrete outcome rather than a technology category. | 8–14 words | “You didn’t start a business to answer support emails all day.” |
| Feature headline | Contrast the desired result with the ineffective alternative. | 5–10 words | “Solve real problems, not just questions.”<br>“Clarity through outcomes, not guesswork.” |
| Supporting line | Explain mechanism and reader benefit with ordinary verbs. | 15–40 words | “Add your training content, adjust the tone, and let [Brand] sound like your best agent on their best day.” |
| Section label | Short sentence-case outcome or capability label. | 2–3 words | “Zero effort setup”<br>“Continuous improvement” |
| Action | A plain verb and clear next step; mention free only when true. | 2–4 words | “Get started free”<br>“Explore pricing”<br>“Developer docs” |
| Closing statement | Move from understanding to action, or pair operational scale with a human result. | 6–14 words | “You’ve seen how it works. Now put it to work.”<br>“Automate the volume, humanize the interaction.” |

**Words and phrasing to use:** actually; your team; in minutes; first time; real problems; get started; one workspace; clear outcomes

**Avoid:** revolutionary ecosystem; unlock limitless potential; AI magic; synergize; disruption for its own sake

**Rules:**

- Lead with the task made easier, then explain the mechanism.
- Use paired contrasts sparingly but prominently: results versus activity, human benefit versus operational burden.
- Write natural-language questions for question chips and FAQs.
- Tie speed claims to a real action; ground numerical claims in verified facts.
- Keep technical copy specific about interfaces, workflows or privacy rather than changing into a grandiose enterprise voice.

## Do's and Don'ts

### Do

- Keep the 66px headline recipe at weight 500 with -0.06em tracking.
- Pair large medium headlines with light 20px/1.4 support text.
- Give major chapters 80px breathing room and maintain the 1280px alignment.
- Use the 120px repeating ribbon seam to make color changes feel connected.
- Stage a real product task at both monumental device scale and isolated-fragment scale.
- Keep primary actions 48px tall with 12px corners and an 8px arrow gap.
- Use 10px card gutters to make large paired demonstrations feel like one argument.
- Carry the spacious conversion statement into the footer instead of treating the footer as an afterthought.

### Don't

- Do not make 700-weight headlines; the compressed 500-weight grotesk is the intended emphasis.
- Do not turn every button into a 9999px capsule; reserve that silhouette for small pills and the billing selector.
- Do not add global gradients, glass navigation or neon glows to the flat blue and blush architecture.
- Do not use orange as a general marketing accent; it belongs to the charcoal commerce theme.
- Do not shrink every product image into a small browser tile; some stages must use the full 1280px measure.
- Do not put heavy shadows under the marketing card grid; tonal fills and rounded clipping carry the separation.
- Do not uppercase and widely track section labels; they are compact sentence-case markings.
- Do not mix the aqua/teal tour theme piecemeal with blue/blush chapter colors. Use it as a scoped page-level variant.

## Motion and responsive

### Motion

**Observed:**

- No action transitions or keyframe animations are established; the settled design includes expandable FAQ and capability-accordion structures.

**Transfer:**

- Keep each accordion's text and associated media understandable in its settled state; the layout and chapter seams should carry the identity without depending on motion.

**Unknown:**

- Hover, focus-visible and active-state treatments; transition durations and easing; timing or mechanism of changing hero and accordion media.

### Responsive

**Observed:**

- Desktop composition uses the 1280px content measure and 1120px opening measure. Width rules include boundaries near 600px, 810px and 1200px; the company narrative additionally has rules near 780px and 1280px.

**Transfer:**

- On narrow layouts, preserve the promise before the product object, stack paired demonstrations and footer columns, and keep the ribbon seam horizontally repeating rather than scaling the entire desktop tile into tiny shapes.
- Use the 66px recipe as the desktop target; reduce size to preserve compact line blocks without losing the contrast against light body text.

**Unknown:**

- Exact mobile typography, object cropping, navigation collapse, side padding and breakpoint-specific grid behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
