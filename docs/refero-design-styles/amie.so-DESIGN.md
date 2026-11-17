# Amie — friendly workday autopilot

## Overview

A light, candid software style that makes powerful automation feel like an approachable everyday utility. Bold grotesk headlines and conversational explanations sit on an almost-white canvas, with sky-blue actions and small green, purple and orange chapter markers. Large pale interface scenes, modest customer proof and softly edged panels keep the presentation tangible rather than futuristic; the overall pace is spacious while the explanations remain substantial.

### Essentials

- An editorial promise above a working product: a left-aligned 56px/64px Inter 700 headline fills a 976px content column, followed by 20px/28px support, paired actions and a full-column interface scene entering the first screen.
- Buttons feel like friendly desktop controls, not pills: the main blue action is 50px high with 12px corners and 12px 28px padding; navigation uses a smaller 32px-high, 8px-corner version.
- Color behaves like a chapter index on near-white paper: #fafafa and white dominate; #11a8ff drives actions, while green, purple and orange mostly occupy 16px semibold labels, checks and quote rules. Keep broad saturated areas inside contained product illustrations rather than page-wide bands.
- Proof looks like something a person actually sent: use compact attributed reviews or a white email-style note, with 16px gray text, small avatars and restrained stars or a 4px colored left rule.
- A highlighted phrase turns a promise into a tangible milestone: use a 4px-radius #cfeeff inline rectangle with #2c76a0 text, alongside bold black type; gray-highlighted 56px statements provide a second version of the same device.
- Close with a friendly getting-started panel, not a dark finale: a 12px-corner near-white card carries a black-and-gray 40px heading pair, three 48px blue numbered circles and a blue action over a huge faint white emblem. For a product without interface media, draw one believable task-to-result scene and use an abstract rounded emblem behind the closing panel.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky blue | `#11a8ff` | `--color-blue` | action, accent, text | Primary actions, numbered steps and selected chapter labels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Orange | `#fe6600` | `--color-orange` | text, accent | Chapter marker and small plan icon; not a broad canvas fill. |
| Fresh green | `#01ca45` | `--color-green` | accent, text, border | Checks and chapter labels; pricing uses it for the annual-billing toggle and incentive. |
| Bright sky | `#41baff` | `--color-blue-bright` | background | Brighter end of the contained sky-gradient media stage. |
| Violet | `#a050ff` | `--color-purple` | text, border | Chapter marker and matching 4px testimonial rule. |
| Recognition coral | `#ff6154` | `--color-coral` | text, accent | Recognition badge text and emblem. |
| Deep sky text | `#2c76a0` | `--color-blue-text` | text | Text inside sky-wash inline highlights. |
| Sky wash | `#cfeeff` | `--color-blue-pale` | surface | Milestone phrase highlight and lower-intensity end of a contained media backdrop. |
| Recognition wash | `#fbebe9` | `--color-coral-wash` | surface | Visible coral at 0.1 opacity over the canvas, confined to the recognition badge. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, surface | Primary headings and text; also the solid conversion action in plan cards. |
| Secondary gray | `#5c5c5c` | `--color-secondary` | text | Paragraphs, supporting text and secondary actions. |
| Mid gray | `#737373` | `--color-muted` | text, surface | Gray-highlighted statement text and current-stage timeline pill. |
| Soft gray | `#a0a0a0` | `--color-tertiary` | text | Subordinate headline line, captions and small chevrons. |
| Highlight gray | `#ebebeb` | `--color-highlight-gray` | surface, border | Inline neutral highlight and visible separators between grouped columns. |
| Hairline | `#f0f0f0` | `--color-separator` | border | Visible result of black at 0.04 opacity on the canvas; fine separators in FAQs and footer. |
| Almost white | `#fafafa` | `--color-canvas` | background, surface | Default page canvas and closing panel. |
| White | `#ffffff` | `--color-paper` | surface, text | Raised panels and secondary buttons; inverse text on filled actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Plan headline ink | `#171717` | `--color-pricing-ink` | text | Primary pricing headline. |

## Typography

- **Inter** — All marketing headings, paragraphs, labels, buttons and numerals. High-x-height contemporary grotesk; bold headlines, ordinary readable body text and compact medium-weight utility labels. Font stack: "Inter", "Inter Fallback", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 700 | 56px | 64px | -0.0125em | Opening promise, large declarative statement and pricing opening. |
| heading | Inter | 700 | 40px | 1.36 | -0.0125em | Capability chapters, centered milestones, FAQs and closing heading pair. |
| subheading | Inter | 600 | 20px | 1.4 | -0.025em | Editorial subheads and small feature titles. |
| lead | Inter | 500 | 20px | 1.4 | 0em | Opening support paragraph, narrower than the headline. |
| step-number | Inter | 700 | 20px | 1.4 | 0em | White numerals in blue step circles. |
| body | Inter | 400 | 16px | 1.75 | 0em | Explanatory paragraphs, feature lists and closing support. |
| review | Inter | 400 | 16px | 1.5 | 0em | Compact review text and comparison-table labels. |
| quote | Inter | 400 | 16px | 1.6 | 0em | Inline attributed quotation beside a colored rule. |
| chapter-label | Inter | 600 | 16px | 1.75 | 0em | Colored sentence-case chapter labels; uppercase for the closing process label. |
| action | Inter | 600 | 16px | 1.6 | -0.0125em | Primary and secondary marketing buttons. |
| question | Inter | 500 | 16px | 1.75 | normal | FAQ disclosure questions and billing-control labels. |
| utility | Inter | 500 | 14px | 20px | 0em | Compact header action, footer links and small attributions. |
| badge | Inter | 600 | 14px | 20px | 0em | Recognition badge. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | Inter | 600 | 30.8px | 36px | -0.012em | Plan price numerals aligned with the smaller per-user qualifier. |
| pricing pages | plan-action | Inter | 600 | 14px | 20px | normal | Full-width black trial actions. |
| pricing pages | incentive | Inter | 700 | 11px | 1.5 | 0.025em, uppercase | Green annual-billing incentive label. |

**Notes:**

- Keep one family throughout. The contrast comes from 700 display weight against 400 gray prose, not a decorative second face.
- The 56px and 40px headings share -0.0125em tracking; 20px editorial subheads are tighter at -0.025em.
- Use a subordinate gray line at the same size and weight as its black heading, rather than reducing it to body copy. Inline colored highlights inherit the heading recipe.

## Layout

**Density:** Airy between chapters and comfortable within substantial explanations; small controls remain compact.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Label-to-heading and subhead-to-copy spacing; compact icon/text gaps. |
| 10px | Opening action-pair gap. |
| 12px | Footer link gaps and checklist spacing. |
| 16px | Heading-to-paragraph spacing, plan-grid gap and quote inset. |
| 20px | Opening headline/support/action rhythm and FAQ padding. |
| 24px | Container side padding and badge-to-headline separation. |
| 32px | Default within-chapter vertical rhythm and milestone column padding. |
| 40px | Closing card side and bottom inset; review-grid gap. |
| 48px | Opening vertical padding, action-to-product lead-in and footer-column inset. |
| 64px | Closing panel top padding and heading-to-numbered-row separation. |
| 192px | Desktop separation between major capability chapters. |

### Containers and grids

- **main container**: max width 1024px · side padding 24px. Centered border-box container; usable width is 976px at desktop. Align header, editorial chapters, product panels and footer to the same edges.
- **hero support**: max width 672px. Opening support stays narrower than the full-column headline.
- **review grid**: 2 columns · gap 40px. Two unboxed customer reviews share a row.
- **feature grid**: 3 columns · gap 48px. Small illustrated feature explanations beneath a major product scene.
- **closing steps**: 3 columns · gap 20px. Three centered numbered steps within the inset closing card.
- **plan grid** (only for pricing pages): 2 columns · gap 16px. Equal 480px plan panels inside the main content column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | panels and main buttons | 12px |
|  | compact controls | 8px |
|  | inline highlight | 4px |
|  | recognition badge | 9999px (pill) |
|  | step marker | 50% |
| pricing pages | plan card | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| natural edge | `0 0 0 1px rgba(0,0,0,0.06), 0 1px 1px -0.5px rgba(0,0,0,0.06), 0 3px 3px -1.5px rgba(0,0,0,0.06)` | Secondary buttons, white panels, FAQ enclosure, closing card and pricing cards. |
| media ring | `inset 0 0 0 1px rgba(0,0,0,0.1)` | Fine boundary around large interface media. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous page background.

**CSS:** `background: #fafafa`

**Observed:** Almost-white across the entire page, including footer.

**Transfer:** Let neutral space connect chapters instead of alternating broad colored bands.

#### Natural panel · level 1

**Use:** Grouped proof, milestones and FAQ enclosure.

**CSS:** `background: #ffffff; border-radius: 12px; box-shadow: 0 0 0 1px rgba(0,0,0,0.06), 0 1px 1px -0.5px rgba(0,0,0,0.06), 0 3px 3px -1.5px rgba(0,0,0,0.06)`

**Observed:** A fine edge plus very shallow elevation, with no heavy border.

**Transfer:** Group related content inside one panel; use thin internal rules instead of nesting raised cards.

#### Navigation glass · level 2

**Use:** Sticky header.

**CSS:** `background: rgba(250,250,250,0.8); backdrop-filter: blur(16px); border-bottom: 1px solid rgba(0,0,0,0.01)`

**Observed:** Subtle translucent neutral strip, not a floating island.

**Transfer:** Keep the glass effect confined to utility chrome.

#### Product tab glass

**Use:** Tabbed header above a large interface demonstration.

**CSS:** `background: rgba(0,0,0,0.2); backdrop-filter: blur(16px); border-bottom: 1px solid rgba(0,0,0,0.05); border-radius: 8px 8px 0px 0px`

**Observed:** Three equal cells with white icons and semibold labels; pale underlying artwork gives the strip a soft gray appearance.

**Transfer:** Use for a small set of related views of one feature, not for every editorial section.

#### Sky media stage

**Use:** Contained hardware or interface demonstration.

**CSS:** `background: linear-gradient(to right top, #cfeeff, #41baff); border-radius: 12px; overflow: hidden; padding: 40px 40px 0px`

**Observed:** A full-column, 290px-high stage with a partial device frame, clouds and a floating product element.

**Transfer:** Place a tightly framed workflow detail against a light blue sky; keep the color inside the panel.

#### Closing panel

**Use:** Friendly process-led conversion block.

**CSS:** `background: #fafafa; border-radius: 12px; overflow: hidden; position: relative; box-shadow: 0 0 0 1px rgba(0,0,0,0.06), 0 1px 1px -0.5px rgba(0,0,0,0.06), 0 3px 3px -1.5px rgba(0,0,0,0.06)`

**Observed:** Near-white embossed emblem behind centered content; panel remains light like the surrounding page.

**Transfer:** Use a recognizable abstract shape as a low-contrast watermark, never as competing foreground art.

## Components

### Sticky navigation

**Use:** Persistent compact site navigation.

**CSS:** `height: 60px; position: sticky; top: 0px; z-index: 50; display: flex; align-items: center; background: rgba(250,250,250,0.8); backdrop-filter: blur(16px); border-bottom: 1px solid rgba(0,0,0,0.01)`

**Observed:** Small black symbol and two links sit left; login and Compact action sit right within the main container. Link hit areas use 6px 10px padding and 8px corners.

**Transfer:** Keep the navigation sparse; use a symbol rather than a giant wordmark.

### Primary button

**Use:** Default marketing conversion action.

**CSS:** `background: #11a8ff; color: #ffffff; border-radius: 12px; padding: 12px 28px; height: 50px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 600 · 16px/1.6 · tracking -0.0125em

**Observed:** Text-only blue action; appears left-aligned in the opening and centered in conversion panels.

### Secondary button

**Use:** Companion platform or download action.

**CSS:** `background: #ffffff; color: #5c5c5c; border-radius: 12px; padding: 12px 28px; height: 50px; display: flex; align-items: center; gap: 8px; box-shadow: 0 0 0 1px rgba(0,0,0,0.06), 0 1px 1px -0.5px rgba(0,0,0,0.06), 0 3px 3px -1.5px rgba(0,0,0,0.06)`

**Text style:** `action` — Inter 600 · 16px/1.6 · tracking -0.0125em

**Observed:** A small gray download icon precedes the label; it sits beside Primary button.

### Compact action

**Use:** Header conversion control.

**CSS:** `background: #11a8ff; color: #ffffff; border-radius: 8px; height: 32px; padding: 6px 16px; display: flex; align-items: center`

**Text style:** `utility` — Inter 500 · 14px/20px · tracking 0em

**Observed:** Smaller and lighter than the main conversion action.

**States:** Declared: hover background-color #218fcd; focus-visible unspecified.

### Recognition badge

**Use:** Compact external proof above the opening headline.

**CSS:** `background: rgba(255,97,84,0.1); color: #ff6154; border-radius: 9999px; padding: 6px 12px; display: inline-flex; align-items: center; gap: 6px`

**Text style:** `badge` — Inter 600 · 14px/20px · tracking 0em

**Observed:** Small solid recognition emblem before the short claim; a subdued laurel-style endorsement may sit alongside.

**Transfer:** Use a genuine short recognition fact or a product-status label.

### Phrase highlight

**Use:** Make one milestone or useful outcome stand out within a headline.

**CSS:** `background: #cfeeff; color: #2c76a0; border-radius: 4px; padding: 0px 4px; display: inline-block; position: relative`

**Text style:** `heading` — Inter 700 · 40px/1.36 · tracking -0.0125em

**Observed:** A text-sized rectangular backing, not a detached badge. The large statement variant uses gray backing and gray text with display typography.

### Ruled quotation

**Use:** Inline customer proof attached to a capability chapter.

**CSS:** `border-left: 4px solid #a050ff; padding-left: 16px; margin-top: 24px; margin-bottom: 24px`

**Text style:** `quote` — Inter 400 · 16px/1.6 · tracking 0em

**Observed:** Quote text first, smaller gray attribution below; desktop width can be three quarters of the content column. The rule matches the chapter accent; green is another variant.

**Transfer:** Use a specific first-person experience rather than another headline claim.

### FAQ row

**Use:** Objection-handling disclosure within Natural panel.

**CSS:** `display: flex; align-items: center; padding: 20px; gap: 16px; width: 100%; text-align: left; color: #000000`

**Text style:** `question` — Inter 500 · 16px/1.75

**Observed:** Question left, 16px gray downward chevron at the far right. Rows are about 68px high, separated by black at 0.04 opacity; the first has no separator.

**Transfer:** Enclose the whole stack in one panel rather than making separate question cards.

### Footer columns

**Use:** Resource and company navigation at the end of both page types.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: space-between; border-top: 1px solid rgba(0,0,0,0.04); padding: 48px 0px`

**Text style:** `utility` — Inter 500 · 14px/20px · tracking 0em

**Observed:** Three widely spaced, untitled columns: a long resources list, a shorter company/contact list, and a short social list. Links have 12px vertical gaps; a separate bottom row has a small location sentiment on the left and muted legal links and copyright on the right.

**Transfer:** Preserve the uneven column lengths and wide empty areas rather than filling every column.

### Numbered step

**Use:** Process row in the closing conversion panel.

**CSS:** `background: #11a8ff; color: #ffffff; width: 48px; height: 48px; border-radius: 50%; display: flex; align-items: center; justify-content: center`

**Text style:** `step-number` — Inter 700 · 20px/1.4 · tracking 0em

**Observed:** Circle sits above a centered subheading and one or two lines of gray body text; three steps form an evenly spaced row.

### Plan card

**Only for:** pricing pages

**Use:** Compact plan comparison before the detailed feature table.

**CSS:** `background: #ffffff; border-radius: 16px; display: flex; flex-direction: column; overflow: hidden; box-shadow: 0 0 0 1px rgba(0,0,0,0.06), 0 1px 1px -0.5px rgba(0,0,0,0.06), 0 3px 3px -1.5px rgba(0,0,0,0.06)`

**Observed:** Equal-height cards with 20px inner insets. Small outline icon, plan name and billing note precede a rule, price with inline per-user qualifier, green-check feature list and Plan trial action pinned to the bottom.

**Transfer:** Keep plans visually equal; distinguish value with content and small icons rather than a loud recommended ribbon.

### Plan trial action

**Only for:** pricing pages

**Use:** Conversion at the bottom of every plan card.

**CSS:** `background: #000000; color: #ffffff; border-radius: 12px; padding: 8px 0px; height: 36px; width: 100%; display: flex; align-items: center; justify-content: center`

**Text style:** `plan-action` — Inter 600 · 14px/20px

**Observed:** The same black action is used in both plans; the site header keeps the blue Compact action.

## Imagery and graphics

### Pale working interface

**Use:** Opening and major capability demonstrations.

**Observed:** Large front-facing white desktop software views show real work: sidebars, documents, tasks and scheduling. The opening image is 976px wide and 630px high, lightly framed with shallow shadow; later panels show enlarged partial windows beneath a three-cell gray tab strip. Colors inside the interface are subordinate to black and gray structure.

**Transfer:** Construct a believable small workflow with a navigation rail and one finished output. If there is no mature interface, a polished HTML document/task mockup is the minimum equivalent; keep it concrete, pale and full-column.

### Connected-tools diagram

**Use:** A capability chapter that explains inputs, transformation and outputs.

**Observed:** A large white rounded panel contains gray curved connectors from small colored service icons at left, through one enlarged glossy purple/pink product tile in the center, to destination icons at right. Tiny pale vertical edge labels describe the direction; color is concentrated in the icons.

**Transfer:** Use relevant inputs and outputs around an original central product symbol. The minimum is a clean flat icon tile with curved connectors, not a stock network photograph.

**Build:** Use a 976px-wide white SVG-backed panel with 12px corners. Draw symmetric cubic Bezier branches using #ebebeb strokes about 8px wide; converge them behind a centered rounded tile about 220px square. Place small icon tiles near both side edges, keeping ample white space. Concentrate any violet-to-pink color in the central tile, and add subtle lower-right shading to suggest a tactile app icon.

### Faint closing emblem

**Use:** Signature low-contrast artwork in the closing conversion panel.

**Observed:** An oversized white lobed symbol sits behind the top half of the near-white card, clipped by its edges and fading toward the numbered row. It is discernible through a very faint outline rather than color contrast.

**Transfer:** Use the new product's simplest rounded symbol; if none exists, use a four-lobed abstract shape. Keep the black-and-gray heading fully legible over it.

**Build:** Place an approximately 816px-square white SVG emblem centrally behind the content, extending above a 976px-wide panel. Combine overlapping rounded lobes into one silhouette, use a 1px rgba(0,0,0,0.03) outline and a vertical opacity mask fading the lower half. Clip the layer to the 12px panel corners.

### Human proof fragments

**Use:** Proof interspersed with longer capability explanations.

**Observed:** Small circular portraits and warm star rows accompany short unboxed reviews. A separate white email-like note uses sender/subject lines, compact body paragraphs, a handwritten green annotation and a tiny understated caption; the note is centered and narrower than the product media.

**Transfer:** Use authentic attributed feedback presented in its natural format. A simple bordered message with sender, subject and a short excerpt is enough; preserve the human-scale detail and low visual noise.

### Icons

**Observed:** Utility icons are mostly 16px outline SVGs with 2px round strokes; larger white tab icons are 24px. Checks are green, chevrons and secondary icons gray. Small plan icons use thin colored outlines; product/service icons retain their own colors.

**Transfer:** Use a consistent rounded outline set for marketing controls. Keep full-color service marks inside explanatory diagrams rather than mixing them into body typography.

## Section recipes

How recurring sections are built.

### First screen: Working-product opening

**Observed:** The first screen has a 60px sticky navigation strip, then a left-aligned editorial stack in the 976px usable column. After 48px top space, a compact Recognition badge and muted endorsement precede the headline by 24px. The black display headline wraps into two lines and spans nearly the entire column. A 672px-wide gray lead follows after 20px, then Primary button and Secondary button after another 20px. After 48px, a tiny update line introduces the Pale working interface. Layers are near-white canvas, text and controls, then a softly edged white product view. Within 900px the entire promise, support and actions are visible plus the upper portion of the interface; the rest of the 630px-high product view and trust logos continue below.

**Transfer:** Lead with the outcome a user can picture, followed by a specific mechanism and two distinct actions. Replace the product view with a believable task-to-result mockup when necessary. Decision pages use a centered black-and-gray two-line display heading and compact billing control instead, with the choices visible in the first screen.

**Avoid:** Do not turn this into a centered splash, a split-screen illustration hero or a full-viewport artwork that pushes the working product entirely below the fold.

**Text style:** `display` — Inter 700 · 56px/64px · tracking -0.0125em

### Editorial capability chapter

**Observed:** A colored chapter-label sits 8px above a black heading. A gray body paragraph follows with 16px separation, then longer paragraphs or subheadings use the 32px internal rhythm. Chapters can include compact replacement comparisons, customer proof, a full-column Pale working interface, then two or three smaller illustrated explanations. Desktop chapters are separated by 192px.

**Transfer:** Group several related capabilities under one benefit. Give the reader an explanation and a visible result, not just a title over a generic card grid.

**Text style:** `heading` — Inter 700 · 40px/1.36 · tracking -0.0125em

### Milestone proof panel

**Observed:** A centered two-line heading includes Phrase highlight. A thin timeline with three gray pills precedes one white panel divided into three columns with 32px padding, semibold titles and green-check body lists. A centered Primary button follows. The current pill is darker than future milestones.

**Transfer:** Show a credible progression from immediate usefulness to a larger outcome. The milestones can be stages rather than literal days.

**Text style:** `heading` — Inter 700 · 40px/1.36 · tracking -0.0125em

### Process-led closing call

**Observed:** Closing panel is 976px wide and 562px high at desktop, with 64px top, 40px side and 40px bottom padding. Faint closing emblem sits behind an uppercase blue chapter-label and black-and-gray heading pair. Three Numbered step groups start 64px beneath the heading region, followed by a centered Primary button.

**Transfer:** Make adopting the new product feel finite and simple. Use three short steps ending in a user outcome, and keep the faint emblem as a visual anchor.

**Text style:** `heading` — Inter 700 · 40px/1.36 · tracking -0.0125em

### Objections and quiet footer

**Observed:** Centered FAQ heading and short gray support lead into one Natural panel of FAQ rows. Footer columns follow on the same canvas, using a top hairline and substantial inset; the final row pairs a small human location sentiment with subdued legal text. Both page types end this way, without a giant wordmark or dark band.

**Transfer:** Answer real adoption barriers, then let the page finish with useful understated navigation.

**Text style:** `heading` — Inter 700 · 40px/1.36 · tracking -0.0125em

### Compact pricing decision

**Only for:** pricing pages

**Observed:** A centered display heading pairs a dark question with an equally large gray reassurance. Below sits a green 44px by 24px annual-billing switch with a 16px white thumb, monthly/yearly labels and a tiny uppercase incentive plus hand-drawn curved green arrow. Two Plan cards begin after 48px; a full-width comparison table follows with faint row rules, two plan columns and small white Select controls. Its repeated column heading floats over a neutral fade.

**Transfer:** Keep the decision area compact and explicit. List shared features plainly, keep black actions equal across plans, and reserve green for the billing incentive and availability checks.

**Text style:** `display` — Inter 700 · 56px/64px · tracking -0.0125em

## Page flow

**Storyline:** Promise → tangible product proof → explained capability and human proof → adoption or purchase decision → objections → useful navigation.

### An expansive product landing page that turns an automation promise into understandable everyday value

1. **Promise** — Left-aligned bold promise, concrete support, paired actions and a large pale product view.
2. **Social proof** — A restrained logo strip and a bold highlighted outcome statement.
3. **Capability chapters** — Color-coded labels introduce substantial explanations, small customer reviews and large interface demonstrations.
4. **Value progression** — Centered highlighted milestone headline over a three-stage timeline panel and action.
5. **Product demonstration** — Further chapters use message-style proof, a connected-tools illustration, tabbed product panels and small illustrated feature rows.
6. **Closing call** — Faint-emblem panel with a black-and-gray heading pair, three blue numbered steps and a centered action.
7. **Objection handling** — FAQ stack followed by sparse resource, company and social columns and a muted legal row.

**Transfer:** Choose the chapters needed to explain the new product; retain the mix of real output, human proof, highlighted outcome and a process-led conversion device without copying the chapter count.

### A focused plan-selection page with enough detail to make an informed choice

1. **Decision framing** — Centered question and gray trial reassurance, followed by green annual-billing incentive and switch.
2. **Pricing** — Two equal white cards with compact price, checklists and identical black trial actions.
3. **Detailed comparison** — Hairline-separated feature table with repeated plan headings and small selection controls.
4. **Objection handling** — Shared FAQ panel and the same understated three-column footer.

**Transfer:** Use this shorter decision pattern when the user already understands the offer; do not import the long capability story into the price comparison.

## Writing

Conversational, useful and gently opinionated. It acknowledges the reader's existing tools and practical frustrations, then explains the mechanism in ordinary language rather than hiding behind abstract innovation claims.

**Do not copy:** Do not reuse Amie's name, symbol, product artwork, third-party endorsements, customer identities or quotations, awards, prices, trial duration, speed claims or quantified productivity promises. Replace these with substantiated facts and original assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work. Use we and our for the team behind the product, and refer to the product by name when explaining what it does.
- **Rhythm:** Benefit headlines are generally short sentences or fragments; explanations can be multiple full paragraphs. Mix terse action verbs with candid longer sentences and occasional conversational asides.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Lead with the user's desired result, then identify the mechanism. | 8–12 words | “Run your workday on autopilot with AI agents” |
| Capability headline | Concrete verb plus useful object or outcome, often with a friction-removing qualifier. | 5–9 words | “Summarize any meeting, without a bot”<br>“Keep your tools updated, with one click” |
| Explanation | Name a familiar problem before explaining how the product differs; contractions keep it personal. | 2–4 sentences per paragraph | “There are 27 meeting notes apps out there. If summaries is all you need, any of them will do. Many of them will even be cheaper.” |
| Action | Simple verb-led invitation or explicit trial proposition. | 1–6 words | “Get started”<br>“Download”<br>“Start 7 day free trial” |
| Closing reassurance | A short question followed by a direct low-effort promise. | Two brief lines | “Ready to get started?”<br>“Start recording in seconds.” |
| Decision framing | Ask the reader a straightforward choice question, then reassure them. | Two sentences | “Which plan is right for you?”<br>“Use our 7 day free trial.” |

**Words and phrasing to use:** your; we; get started; with one click; in the background; next steps; works with; without; ask; save time

**Avoid:** revolutionary; unleash; next-generation platform; seamless ecosystem; synergize; enterprise transformation

**Rules:**

- Describe what happens to the reader's actual work, not only the category of technology.
- Acknowledge existing habits and tools rather than pretending the product replaces every part of life.
- Use exact, supportable outcomes when making a highlighted milestone claim.
- Keep button labels literal and FAQs phrased as real user questions.
- Allow small witty asides in supporting copy, while keeping the main promise useful and direct.

## Do's and Don'ts

### Do

- Keep the usable desktop content width at 976px within a 1024px container with 24px side padding.
- Use 56px/64px bold Inter for the opening and 40px/1.36 for capability headings.
- Pair black headings with #5c5c5c body copy and same-size #a0a0a0 subordinate headline lines.
- Make the main action sky blue with 12px corners, while compact header controls use 8px corners.
- Keep product views front-facing and pale, with fine rings and shallow natural shadows.
- Include a text-sized highlighted promise and a light process-led conversion panel.
- Give chapters 192px separation at desktop while preserving a 32px explanation rhythm.
- Finish with uneven, widely separated footer columns using 14px links and 12px gaps.

### Don't

- Do not replace the grotesk with a decorative serif, monospaced heading or ultra-thin display face.
- Do not turn all accents into blue; small green, purple and orange chapter markers provide the taxonomy.
- Do not make the default marketing actions black just because the plan actions are black.
- Do not round main actions to capsules; reserve full rounding for badges, timeline pills and circles.
- Do not use deep floating shadows or thick card outlines where a 0.06-opacity fine edge is enough.
- Do not tint whole capability chapters with their label colors; the page stays almost white.
- Do not enlarge every review into a hero quote; most proof remains human-scale and interleaved with explanation.
- Do not give the footer an oversized logo or dark contrasting background.

## Motion and responsive

### Motion

**Observed:**

- Declared action and surface color transitions use 0.15s cubic-bezier(0.4,0,0.2,1). Opacity transitions use the same duration and curve.
- Navigation link hover uses black at 0.05 opacity; Compact action hover darkens blue to #218fcd. Billing labels hover to 0.8 opacity.
- Two horizontal scroll animations are declared at 70s linear infinite.
- FAQ chevrons declare a 300ms transform transition and rotate for the open state.

**Transfer:**

- Keep utility feedback quick and understated; retain the slow linear movement only for a repeated logo or proof strip.
- Use the FAQ chevron to signal disclosure without animating the whole surrounding chapter.

**Unknown:**

- Exact scroll-trigger choreography and timing of product demonstrations are not established.
- Open FAQ content appearance and focus-visible treatment are unspecified.

### Responsive

**Observed:**

- Styles declare width breakpoints at 640px, 768px, 1024px, 1280px, 1536px and 2000px.
- Heading classes step through smaller sizes before the desktop display size; review and feature grids declare one-column narrow layouts.
- The three-stage panel declares a vertical narrow layout and hides its desktop timeline; major chapter margins switch from 192px to 64px at narrower widths.

**Transfer:**

- Preserve the full-width product-after-copy composition; reduce headline size rather than forcing desktop line breaks.
- Stack divided milestone columns and numbered steps vertically, changing vertical separators into horizontal rules.
- Keep the same neutral canvas and blue action hierarchy when the navigation condenses.

**Unknown:**

- No narrow-screen layout was visually verified; exact mobile navigation behavior and demonstration overflow remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
