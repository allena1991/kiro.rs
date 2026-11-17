# GitBook — ribboned product optimism

## Overview

A bright, warm technical style that makes complex software feel approachable and thoughtfully crafted. Warm charcoal grotesk typography and small orange mono labels sit on white and pale stone, with sculptural orange ribbons, floating interface fragments and soft translucent layers. The density is airy at the page level and purposeful inside cards, suited to product platforms, technical tools and considered enterprise buying journeys.

### Essentials

- Promise-and-payoff headlines: General Sans at 45px/1, weight 700 and -0.02em tracking, with a short concluding phrase in #fe551b rather than a fully colored headline.
- An airy promise above a tangible product stage: centered 721px headline, 18px support, 38px pill actions, a muted logo strip and an 1120px-wide translucent browser entering the first 900px.
- Small dark pills do the selling: #1c1917 primary and #efeeed secondary, 99px radius, 16px/1 bold text, 10px 14px 12px padding and a small trailing arrow.
- Orange is sculptural, not a page theme: white and #fafaf9 dominate; #fe551b marks payoff words, mono labels and badges, while broad orange ribbons remain behind bounded product scenes.
- Product explanations feel assembled by hand: raised 44px icon tiles, 16px rounded cards, dotted orange connectors and softly shadowed white interface fragments on pale neutral stages. Use a simplified workflow diagram when no polished product media exists.
- A pale relief symbol anchors the closing invitation: a 570×517px near-white emblem behind centered 45px outcome copy in a 680px stone band. Recreate this with the new product's own simple emblem or an abstract folded shape.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#fe551b` | `--color-orange` | accent, text, border | Headline payoff, eyebrows, badges, selected-plan border and ribbon art. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Peach wash | `#fff7f4` | `--color-peach` | surface | Resource cards; visible result of orange at 5% over white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#1c1917` | `--color-ink` | text, action | Headings, iconography and primary action fills. |
| Warm gray | `#57534d` | `--color-body` | text | Paragraphs and navigation labels. |
| Muted stone ink | `#79716b` | `--color-muted` | text, link | Secondary support and footer links. |
| Soft neutral | `#efeeed` | `--color-soft` | surface, border | Secondary pills and hairline card edges. |
| Browser glass tint | `#f1f1f1` | `--color-browser-tint` | surface | Charcoal at 6% over white; the ribbon remains visible through the browser frame. |
| Media gray | `#f2f2f2` | `--color-media` | surface | Illustration backing in image-led capability cards. |
| Pale stone | `#fafaf9` | `--color-stone` | background, surface | Closing band, footer, image-led cards and icon tiles. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, floating UI sheets and inverse action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Selected plan wash | `#ffeee8` | `--color-plan-wash` | surface | Orange at 10% over white at the bright end of the selected-plan gradient. |
| sales forms | Input edge | `#dddddb` | `--color-input-edge` | border | Warm gray at 20% over white for field outlines. |

## Typography

- **General Sans** — All marketing headings, paragraphs and actions. Open geometric grotesk with rounded bowls, clear counters and compact headline spacing. If unavailable, use **DM Sans**. Use weights 500 and 700 with the same tight heading tracking. Font stack: "General Sans", "DM Sans", system-ui, sans-serif.
- **Geist Mono** — Orange uppercase section labels and footer category labels. Small technical markings that contrast with the friendly grotesk. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | General Sans | 700 | 45px | 1 | -0.02em | Opening promise and closing outcome; same recipe in charcoal and orange. |
| heading-lg | General Sans | 700 | 38px | 1 | -0.02em | Major chapter headings, centered or left aligned. |
| heading | General Sans | 700 | 32px | 1.2 | -0.02em | Split narrative panels and secondary section headings. |
| quote | General Sans | 700 | 24px | 1.2 | -0.02em | Customer quotations, plan prices and compact section leads. |
| card-heading | General Sans | 700 | 20px | 1.3 | -0.02em | Card titles and footer group headings. |
| lead | General Sans | 500 | 18px | 1.6 | -0.01em | Hero support and major section introductions. |
| body | General Sans | 500 | 16px | 1.5 | normal | Card explanations, narrative paragraphs, FAQ questions and attribution. |
| action | General Sans | 700 | 16px | 1 | -0.03em | Main pill button labels. |
| small-link | General Sans | 700 | 14px | 1.6 | normal | Footer links and inline resource actions. |
| navigation | General Sans | 700 | 14px | 1.5 | 0.01em | Header navigation. |
| eyebrow | Geist Mono | 600 | 14px | 1.3 | -0.02em, uppercase | Orange chapter and feature labels. |
| category | Geist Mono | 600 | 12px | 1 | 0.02em, uppercase | Footer subcategory markings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| sales forms | form-heading | General Sans | 700 | 30px | 28px | -0.0133em | Heading inside the sales form. |
| company storytelling pages | manifesto | General Sans | 700 | 22px | 1.5 | -0.02em | Long-form founder statement in warm gray. |

**Notes:**

- Keep headings close-set but body copy open: heading tracking stays at -0.02em while body tracking is normal.
- The display is compact rather than monumental; the large illustration supplies the scale. Preserve the two-line promise instead of inflating it to fill the viewport.
- Use the bold recipe weights even though the open letterforms give headings an unheavy appearance. Keep mono labels orange, not the body font in spaced capitals.

## Layout

**Density:** Airy between chapters, with tightly assembled interface fragments and restrained card padding.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-card-title and compact heading grouping. |
| 10px | Action icon gap, paired action gap and close content stacks. |
| 12px | Card title-to-body spacing and compact repeated items. |
| 16px | Narrative title-to-paragraph spacing; resource card padding. |
| 24px | Default card padding, grid gap and action separation from support copy. |
| 32px | Heading-to-diagram gap and footer major-group separation. |
| 40px | Desktop side gutters, quote column gap and larger internal group spacing. |
| 48px | Feature introduction-to-card-grid gap. |
| 80px | Top-level section rhythm on supporting page types and between hero subgroups. |
| 112px | Default vertical gap between major marketing chapters. |
| 128px | Breathing space beneath customer story carousel. |
| 200px | Vertical padding around the closing invitation. |

### Containers and grids

- **marketing container**: max width 1160px · side padding 40px. Centered desktop content; at 1440px it leaves 140px side margins.
- **product stage**: max width 1120px. Wide hero browser, slightly inset from the chapter container.
- **reading column**: max width 766px. Customer quotations and company story panel.
- **four card grid**: 4 columns · gap 24px. 272px feature cards across the marketing container.
- **three card grid**: 3 columns · gap 24px. 371px illustration-led capability cards.
- **two card grid**: 2 columns · gap 24px. 568px illustrated capability cards.
- **narrative split**: 2 columns · gap 64px. Text and product diagram of similar visual weight.
- **faq column**: max width 800px. Centered compact question list.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action pills | 99px |
|  | content cards | 16px |
|  | icon tiles | 8px |
|  | resource cards | 12px |
| sales forms | sales panel | 20px |
| sales forms | fields | 10px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| browser | `rgba(0, 0, 0, 0.15) 0px 4px 12px 0px` | Hero product frame only. |
| floating fragments | `rgba(0, 0, 0, 0.1) 0px 6px 14px 0px` | Small white interface fragments in product scenes. |
| icon tile | `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px` | Small raised icon squares; not full-size cards. |

### Surfaces

#### White canvas · level 0

**Use:** Main marketing page.

**CSS:** `background: #ffffff; color: #1c1917`

#### Stone band · level 0

**Use:** Closing call and deep footer.

**CSS:** `background: #fafaf9`

**Observed:** A barely darker continuous plane, without a heavy top border.

**Transfer:** Use to lower visual intensity toward the end of the page.

#### Quiet card · level 1

**Use:** Text-led feature cards.

**CSS:** `background: #ffffff; border: 1px solid #efeeed; border-radius: 16px; overflow: hidden`

**Observed:** The outline is just visible against the white page; no broad drop shadow.

**Transfer:** Separate related benefits without making a dashboard.

#### Illustration card · level 1

**Use:** Capability panels with a large image followed by text.

**CSS:** `background: #fafaf9; border-radius: 16px; overflow: hidden`

**Observed:** Image backing is #f2f2f2, usually 320px high; text remains on pale stone.

**Transfer:** Give each capability a single simplified visual.

#### Browser glass · level 2

**Use:** Main opening demonstration.

**CSS:** `background: rgba(28, 25, 23, 0.06); border-radius: 16px; padding: 0px 8px 8px; backdrop-filter: blur(5px); box-shadow: rgba(0, 0, 0, 0.15) 0px 4px 12px 0px`

**Observed:** Translucent outer browser chrome over orange ribbon art, with a mostly white working area.

**Transfer:** Let color show through the frame, not through essential product text.

#### Peach resource panel · level 1

**Use:** Small editorial resource promotions in the footer.

**CSS:** `background: rgba(254, 85, 27, 0.05); border-radius: 12px; padding: 16px`

#### Recommended plan · level 1

**Only for:** pricing pages

**Use:** Selected plan among adjacent comparison cards.

**CSS:** `background: linear-gradient(225deg, rgba(254, 85, 27, 0.1) 3%, rgba(254, 85, 27, 0) 61%); border: 1px solid #fe551b; border-radius: 16px 0px 0px 16px; padding: 24px`

**Observed:** A thin orange perimeter and localized tint, not a filled orange card.

**Transfer:** Highlight only the recommended tier.

## Components

### Floating navigation

**Use:** Persistent top navigation.

**CSS:** `background: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); border-radius: 8px; height: 48px; max-width: 1176px; padding: 8px 16px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `navigation` — General Sans 700 · 14px/1.5 · tracking 0.01em

**Observed:** Logo at left, compact central menu with down chevrons, login plus pale and dark pill actions at right. Header action labels use the small-link recipe and are 32px high.

### Primary button

**Use:** Main conversion and story actions.

**CSS:** `background: #1c1917; color: #ffffff; border-radius: 99px; height: 38px; padding: 10px 14px 12px; display: inline-flex; align-items: center; gap: 10px`

**Text style:** `action` — General Sans 700 · 16px/1 · tracking -0.03em

**Observed:** Short label with a small trailing right arrow; width is content driven. The sales submit variant stretches across the form.

### Secondary button

**Use:** Alternative route beside the main action.

**CSS:** `background: #efeeed; color: #1c1917; border-radius: 99px; height: 38px; padding: 10px 14px 12px; display: inline-flex; align-items: center; gap: 10px`

**Text style:** `action` — General Sans 700 · 16px/1 · tracking -0.03em

**Observed:** Sits directly beside the dark pill. A white variant appears on colored artwork; provider sign-up can use a leading provider icon.

### Text link

**Use:** Editorial story links and contextual navigation.

**CSS:** `color: #1c1917; text-decoration-line: underline`

**Text style:** `small-link` — General Sans 700 · 14px/1.6

**Observed:** Inline and compact, not a large outlined button. Footer directory links use muted ink without persistent underlining.

**States:** Declared: hover retains #1c1917 text with #fe551b underline, 3px thickness and 4px underline offset; focus-visible not specified.

### Feature card

**Use:** Small text-led benefits in a grid.

**CSS:** `background: #ffffff; border: 1px solid #efeeed; border-radius: 16px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `card-heading` — General Sans 700 · 20px/1.3 · tracking -0.02em

**Observed:** Raised icon tile first, title and body below, small neutral pill at the bottom when a dedicated route exists. Body uses the body recipe; cards align in equal-height rows.

### Icon tile

**Use:** Visual anchor in feature and support cards.

**CSS:** `background: #fafaf9; width: 44px; height: 44px; padding: 10px; border-radius: 8px; box-shadow: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px; display: flex; align-items: center; justify-content: center`

**Observed:** One 24px dark icon, softly raised like a small keycap; no colored circular badge.

### Resource card

**Use:** Footer editorial promotions.

**CSS:** `background: rgba(254, 85, 27, 0.05); border-radius: 12px; padding: 16px; width: 280px`

**Text style:** `small-link` — General Sans 700 · 14px/1.6

**Observed:** Compact thumbnail or document icon above title, a brief explanation and Text link. Neighboring sales promotion uses bright orange artwork and a white pill.

**Transfer:** Choose one helpful report and one real customer example rather than more directory links.

### FAQ row

**Use:** Objection handling below capabilities.

**CSS:** `max-width: 800px; padding: 15px 10px 15px 15px; min-height: 54px`

**Text style:** `body` — General Sans 500 · 16px/1.5

**Observed:** One question left, small right chevron, faint horizontal separation. Collapsed questions make a compact list rather than separate rounded cards.

**Transfer:** Group questions by buyer concern.

### Sales input

**Only for:** sales forms

**Use:** Short contact forms.

**CSS:** `background: #ffffff; border: 1px solid rgba(87, 83, 77, 0.2); border-radius: 10px; height: 40px; padding: 10px; margin-bottom: 16px`

**Observed:** Label sits above the field; select uses the same frame, multiline input is 80px high. The 483px-wide pale panel has a 20px radius and 24px side padding.

### Plan card

**Only for:** pricing pages

**Use:** Recommended option in a side-by-side plan family.

**CSS:** `background: linear-gradient(225deg, rgba(254, 85, 27, 0.1) 3%, rgba(254, 85, 27, 0) 61%); border: 1px solid #fe551b; border-radius: 16px 0px 0px 16px; padding: 24px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `card-heading` — General Sans 700 · 20px/1.3 · tracking -0.02em

**Observed:** Plan title, audience descriptor, 24px price with small billing suffix, credit allowance strip, full-width pill and compact feature list. The recommended and enterprise tiers get dark actions; lower tiers use pale actions. Two adjacent tiers share an outer group.

## Imagery and graphics

### Orange ribbed ribbons

**Use:** Signature sculptural accent behind the hero demonstration and selected capability scenes.

**Observed:** Broad continuous orange tubing loops and crosses itself, with parallel ridges, warm yellow-orange highlights and red-orange grooves. It is solid, softly lit and tactile rather than a neon light trail; sections extend beyond the frame and pass behind white UI layers.

**Transfer:** Make a custom looping ribbon in the new product's visual language. Minimum acceptable version is a layered vector ribbon with convincing ridges and an over-under crossing.

**Build:** Draw a broad looping cubic SVG path across a 1560×690 artboard. Use a 140px round stroke in #fe551b, then parallel inset strokes with rgba(255,255,255,0.18) and rgba(28,25,23,0.12) to suggest longitudinal ribs. Duplicate a crossing segment above the lower segment, adding a soft 12px shadow. Keep the product panel in front and let the ribbon exit both edges.

### Assembled product scenes

**Use:** Hero stage and capability demonstrations.

**Observed:** Mostly white interfaces, a pale gray backing, slightly rotated sheets, floating chat/status cards, small avatar discs and raised icon squares. Fine orange dotted routes connect pieces; soft shadows separate layers. Feature images occupy roughly half a split panel or the upper 320px of a card.

**Transfer:** Show one meaningful task, not an entire unreadable app. A white window plus a status chip and two linked icon tiles is the minimum equivalent.

**Build:** Layer a rounded white window over #f2f2f2; add a secondary sheet rotated slightly, one foreground notification with a 6px 14px soft black shadow, and SVG dashed paths in rgba(254,85,27,0.3). Use a few 44px icon tiles and small portrait discs; keep all text-bearing planes high contrast.

### Connected system diagram

**Use:** Explanatory bridge from promise to capability grid.

**Observed:** A central lightly tinted isometric object inside a broad capsule-like route, with four small white icon tiles at its cardinal points and orange dotted connections. The diagram stays pale enough that the section headline remains dominant.

**Transfer:** Represent the product's central operation and its inputs or outputs with a simple hub and a small number of linked nodes.

**Build:** Use an SVG rounded route about 928×334px, a translucent orange fill at 2–5% and thin dotted orange strokes at 30%. Place a simple three-face cube or folded polygon in the middle and white icon tiles at the route's top, bottom and ends.

### Relief closing emblem

**Use:** Signature background to the final conversion invitation.

**Observed:** An oversized near-white dimensional symbol, 570×517px, is barely raised from a pale stone field. It sits behind the text rather than functioning as a separate illustration.

**Transfer:** Use the new product's simple symbol, or an abstract folded polygon, with the same restrained relief treatment.

**Build:** Place a centered SVG emblem behind content in a 680px #fafaf9 band. Fill with #ffffff at low contrast, add a 2px blurred rgba(28,25,23,0.03) inset-like edge and a soft 18px rgba(28,25,23,0.03) outer shadow; keep the text in a separate top layer.

### Human proof and logos

**Use:** Trust strip, story carousel and quote interludes.

**Observed:** Trust strips are monochrome gray logos with faded side edges. Story tiles are 320px squares with centered black logos and a tiny circular outbound arrow near the bottom. Quotes use an 80px portrait inside a pale block beside a much wider text column.

**Transfer:** Use real proof at modest visual volume. If logos are unavailable, use credited practitioner quotations with portraits rather than invented brand marks.

### Team panorama

**Only for:** company storytelling pages

**Use:** Large emotional visual after a text-led mission opening.

**Observed:** A wide outdoor group portrait in a rounded 1080×477px frame, desaturated with faint warm tinted overlays, placed in front of a giant orange loop extending beyond the page width.

**Transfer:** Use a real team or working-context photograph with natural light and a muted palette; keep the orange sculpture behind it.

### Icons

**Observed:** Small dark utility symbols, mainly 24px inside 44px raised tiles; buttons use compact 13×10px arrows. Dotted connectors, branch symbols and restrained line icons give diagrams a technical character.

**Transfer:** Choose simple dark utility icons with even visual weight; retain the tiny trailing arrows and keycap framing rather than adding colorful icon circles.

## Section recipes

How recurring sections are built.

### First screen: Product stage opening

**Observed:** A compact Floating navigation sits above a centered announcement pill. The promise begins around 176px from the top and occupies a roughly 721px-wide, two-line block in display type, with the final short payoff orange. An 18px support line follows, then paired Primary button and Secondary button with a 10px gap. A low-contrast logo strip separates this text from the main object. Behind the object is a broad orange ribbon, then Browser glass, then the white working interface. At 900px height the full promise, support, actions, logos and upper portion of the 1120×647px browser are visible; the bottom of the product scene continues below the fold.

**Transfer:** Preserve the hierarchy and generous white breathing room for an ordinary marketing landing page. Build a credible simplified product window if finished artwork is unavailable, but retain the ribbed ribbon and translucent frame. Capability pages instead open with left-aligned eyebrow, display and actions opposite a floating product illustration; sales pages replace that illustration with a ribbon-backed contact form. Company storytelling opens with left-aligned mission text before a panorama; pricing opens centrally above plan families.

**Avoid:** Do not turn the first screen into a full-bleed orange poster, an oversized headline-only splash, or a dense feature dashboard. Do not shrink the product scene into a thumbnail beside the default centered promise.

**Text style:** `display` — General Sans 700 · 45px/1 · tracking -0.02em

### Chapter introduction

**Observed:** Orange eyebrow above heading-lg, with 11–16px separation and lead copy below. Centered introductions serve broad claims; left-aligned introductions lead grids or a split chapter. Cards start about 48px after the introduction.

**Transfer:** Make each chapter one clear buyer question or outcome rather than a list of internal feature names.

**Text style:** `heading-lg` — General Sans 700 · 38px/1 · tracking -0.02em

### Alternating narrative split

**Observed:** A 1160px row with similar-weight text and media, 64px gap, heading at 32px and body or lead support. Alternating sides keep long pages varied; diagrams use pale neutral backings and subtle orange routes.

**Transfer:** Pair a real problem with a single explanatory visual, then reverse the next chapter's emphasis.

**Text style:** `heading` — General Sans 700 · 32px/1.2 · tracking -0.02em

### Wide illustrated panel

**Observed:** A 16px-rounded pale panel about 1160×480px. Illustration takes the wider left area, around 658px, and text sits in the remaining portion: eyebrow, heading, body, dark pill. Orange ribbon portions are clipped behind the floating UI.

**Transfer:** Use for a deep workflow or integration story, keeping explanatory text on the calm side.

### Capability families

**Observed:** Two or three Illustration cards with 24px gaps. Each has a 320px image zone, then 24px spacing to eyebrow, 8px to card-heading and 12px to body. Four-column text-led grids instead use Feature card and Icon tile.

**Transfer:** Choose the grid by content depth: fewer cards for visual stories, four for concise benefits.

### Quotation interlude

**Observed:** Centered 766px reading area with a small portrait-and-logo block at left, 40px gap and a 552px quotation column. Quote recipe leads, body attribution follows, and one or two pills sit beneath. White canvas continues around the block.

**Transfer:** Use one attributed, specific experience as a pause between denser chapters.

**Text style:** `quote` — General Sans 700 · 24px/1.2 · tracking -0.02em

### Customer proof carousel

**Observed:** Left eyebrow and heading-lg with a right-aligned dark View all action. A horizontal run of 320px stone logo tiles has 24px gaps, clipped at the container edge. Small dark pagination dashes sit below left and 40px circular arrows below right.

**Transfer:** Present a curated proof set, not a multicolored wall of equal-volume logos.

### Objection handling

**Observed:** A short 24px heading above an 800px-wide stack of FAQ row components. Long question sets have 20px group headings; short sets remain one unboxed list.

**Transfer:** Use practical questions in the reader's own words, with no promotional preamble.

### Relief closing invitation

**Observed:** Stone band is 680px high with a centered Relief closing emblem. A short two-line display, muted 16px support and paired dark/pale pills sit over the emblem with 24px vertical gaps. A monochrome logo strip bridges the call and the footer.

**Transfer:** Reduce the product's benefit to two compact outcomes and retain the pale dimensional backdrop even when using an abstract emblem.

**Text style:** `display` — General Sans 700 · 45px/1 · tracking -0.02em

### Directory footer

**Observed:** A deep pale stone footer begins with logo left and small social icons right. The 1160px container divides into an 840px directory and 280px resource rail, separated by 40px. Directory has three major groups, each split into three small categories with orange mono labels and muted 14px links; faint vertical rules separate columns. The rail has an orange sales art card followed by two Peach resource panels. The end contains small assurance marks, copyright and address, an AI-summary icon row and a low-contrast legal row.

**Transfer:** Retain the useful directory plus editorial rail contrast. Adapt category count to real information architecture and use only applicable assurance marks.

### Pricing decision system

**Only for:** pricing pages

**Observed:** Centered display and lead above four plan options, grouped into two bordered families. Recommended option uses Plan card. A narrow explanation column introduces a larger pale calculator panel with selectable plans and a distinct total area. The detailed comparison uses 72px rows, 24px section headings and a persistent compact plan header. Credit packs appear as four 281×152px lightly tinted cards.

**Transfer:** Let readers compare by intent first, calculate second and inspect details third. Preserve subdued tints and thin selection outlines.

### Sales-led opening variant

**Only for:** enterprise sales pages

**Observed:** Left-aligned display and lead sit opposite a 661×678px ribbon-backed illustration stage. A 483×638px pale form panel floats over it, with form-heading, five labeled controls and a full-width dark submit pill. The logo strip follows the opening.

**Transfer:** Keep qualification concise and place the form directly in the visual narrative, not in an unrelated modal.

**Text style:** `form-heading` — General Sans 700 · 30px/28px · tracking -0.0133em

### Founder statement

**Only for:** company storytelling pages

**Observed:** Mission-led opening followed by Team panorama, then a centered 766px panel with 40px padding. Eyebrow and heading introduce warm-gray manifesto paragraphs, followed by a centered personal sign-off. A modest centered invitation and one dark pill close the story instead of the product relief call.

**Transfer:** Use a clearly authored point of view, a real visual of people and a relevant next step.

**Text style:** `manifesto` — General Sans 700 · 22px/1.5 · tracking -0.02em

## Page flow

**Storyline:** Promise → tangible product mechanism → evidence and capability chapters → buyer concerns → restrained invitation → useful directory.

### Broad product landing page

1. **Promise** — Centered payoff headline over ribbon-backed browser and quiet trust strip.
2. **Activation shortcut** — Small provider choice strip and copyable setup prompt.
3. **Problem and mechanism** — Two alternating visual narratives followed by a connected system diagram and compact benefits.
4. **Social and operational proof** — Quotation pauses, larger trust chapter and logo story carousel.
5. **Closing call** — Relief invitation, logo strip and directory footer.

**Transfer:** Translate the visitor's pain into a visible operating model, then prove the wider organizational value.

### Plan selection and detailed evaluation

1. **Pricing** — Centered introduction and four options arranged in two families.
2. **Social proof** — Customer quotation and a monochrome logo grid.
3. **Budget clarity** — Explanation beside an interactive calculator.
4. **Detailed comparison** — Grouped capability rows under a persistent plan header, interrupted by credit packs.
5. **Objection handling** — Testimonial, alternative entry routes and grouped FAQs.
6. **Closing call** — Relief invitation and full directory footer.

**Transfer:** Support both a quick plan choice and a careful procurement read without forcing equal detail on both audiences.

### Capability landing page

1. **Capability promise** — Left text and floating interface art, followed by trust logos.
2. **Product demonstration** — Two large image-led cards.
3. **Workflow depth** — Quote, wide illustrated panel and four compact benefits.
4. **Ecosystem and adjacent value** — Another quote, integration panel and three illustrated cards.
5. **Objection handling** — Short FAQ list.
6. **Closing call** — Relief invitation, logo strip and directory footer.

**Transfer:** Show the primary task early, then demonstrate how it connects to adjacent workflows.

### High-consideration sales page

1. **Sales invitation** — Specific audience promise opposite a ribbon-backed contact form.
2. **Operational value** — Wide visual narrative and concise supporting benefits.
3. **Social proof** — Customer quotation and story carousel woven among capability chapters.
4. **Risk reduction** — Governance workflows, support cards and migration panel.
5. **Objection handling** — Compact FAQs.
6. **Closing call** — Relief invitation and complete footer.

**Transfer:** Put the sales route early, then earn confidence with operational detail and attributable proof.

### Company narrative and recruiting

1. **Mission** — Left-aligned compact display and a short human statement.
2. **Human context** — Wide team panorama over giant orange loop.
3. **Point of view** — Narrow authored statement with personal sign-off.
4. **Invitation** — Centered recruiting call, a single pill and trust strip.
5. **Directory** — Shared deep footer, without the product relief call.

**Transfer:** Replace capability density with people and an authored belief while retaining the shared type, ribbon and footer language.

## Writing

Direct, warm and technically literate. Claims are framed as practical improvements to work, with confident contrasts and tangible verbs rather than grandiose promises.

**Do not copy:** Do not reuse GitBook names, logo artwork, customer marks, quotations, certification claims, prices, percentages, addresses or product-specific factual claims. Use verified equivalents for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your team. Product copy names the product as the active helper; company storytelling switches to we.
- **Rhythm:** Headlines are brief, often split into a problem and a payoff. Support is usually one sentence; body copy adds concrete mechanisms in compact paragraphs. CTAs use two to four words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | State the ongoing problem, then deliver an unusually short corrective payoff. | 8–14 words | “The docs platform that flags outdated content. Then fixes it.” |
| Supporting line | Name the outcome and the people or systems it serves. | 9–25 words | “[Brand] keeps docs accurate, for both people and AI” |
| Chapter heading | Contrast a shallow category promise with the deeper benefit. | 7–13 words | “A system built to keep docs accurate, not just create them.”<br>“Work the way that works for you” |
| Feature explanation | Lead with an action and specify the actual workflow. | 15–35 words | “Sync your repo, then branch, review, and merge documentation like a PR.” |
| Primary action | Short verb-led, low-friction next step. | 2–4 words | “Start for free”<br>“Talk to us” |
| Closing line | Two short outcome fragments, each ending with a period. | 4–8 words | “Accurate docs. Better answers.” |
| Question | Plain buyer language about a concrete concern. | 6–12 words | “Can I change my plan later?” |

**Words and phrasing to use:** built for; work the way; create, review, publish; your team; keeps; ready; together; without adding steps

**Avoid:** revolutionary; game-changing; unleash; synergy; magic; limitless; disrupt

**Rules:**

- Connect every capability to a visible workflow or reader outcome.
- Use technical terms when they explain how something works, not as decorative jargon.
- Use compact parallel outcomes for a closing invitation.
- Keep the human voice most evident in quotes and company narrative; keep interface and plan language factual.

## Do's and Don'ts

### Do

- Keep display at 45px/1 and chapter leads at 38px/1 with -0.02em tracking.
- Use 24px gaps for two-, three- and four-column capability grids.
- Give major chapters 112px of separation while keeping card title/body gaps near 12px.
- Reserve broad orange shapes for artwork behind white product layers.
- Use 44px pale raised icon tiles with 24px dark glyphs.
- Use 16px card corners and 99px action corners as different shape families.
- Close product-led pages with the 680px pale relief invitation.
- Retain the editorial resource rail beside the footer directory.

### Don't

- Do not give every white feature card a broad drop shadow; edges are 1px #efeeed.
- Do not change the 38px marketing pills into tall rectangular app buttons.
- Do not use orange as the default CTA fill; dark charcoal carries primary actions.
- Do not set body copy in the mono face; reserve it for 12px and 14px uppercase markings.
- Do not convert muted gray trust logos into a full-color sponsor mosaic.
- Do not give all plan tiers the selected orange border and gradient.
- Do not extend the 700-weight 22px manifesto treatment into ordinary body paragraphs.
- Do not place saturated backdrops behind long reading passages; keep them on white or pale stone.

## Motion and responsive

### Motion

**Observed:**

- Inline editorial links declare an orange 3px underline on hover with 4px offset.
- Product artwork includes dotted routing, small status badges and shifting layered UI scenes.

**Transfer:**

- If animating a product scene, preserve the settled hierarchy of ribbon behind, white interface in front and one legible status result.

**Unknown:**

- Action transition durations and easing are not established.
- The precise timing and triggers of diagram movement are not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 810px, 1200px and 1600px.

**Transfer:**

- As a design adaptation, stack split chapters with the promise before its illustration, and retain the orange ribbon as a clipped backdrop rather than a separate full-width banner.
- Reflow the footer directory before its resource rail. Keep FAQ rows in one reading column and retain the contrast between dark and pale pills.

**Unknown:**

- Narrow-screen type sizes, navigation behavior and exact grid collapse rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
