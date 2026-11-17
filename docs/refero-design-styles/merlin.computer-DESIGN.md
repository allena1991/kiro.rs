# Merlin — conversational machinery at rest

## Overview

A friendly desktop companion presented like a conversation rather than a conventional software pitch. Rounded sans-serif type and small charcoal interface scenes sit in deep black space, interrupted by crisp white explanatory chapters and restrained blue accents. Layered application windows, floating activity capsules and a low-contrast character-art landscape give the technical presentation a playful, lived-in feeling. It suits personal tools and workflow products with concrete actions to demonstrate, keeping the page spacious while the demonstrations stay dense.

### Essentials

- The opening speaks in little messages, not a billboard headline: 15.5px Open Runde, 400 weight, 21.7px line height, in 400px-wide charcoal bubbles beside a 36px avatar; the main action is aligned with the messages.
- Headlines are modest two-tone sentence fragments: 28px/1.15, weight 600, -0.035em tracking, with the first line #e8e8e8 and the changing continuation #969696; invert to dark ink and gray in white chapters.
- Conversion is a bright capsule in a dark conversation: white fill, near-black text, a 52px-high opening button with 24px horizontal padding and fully rounded ends; compact navigation uses a 32px version.
- Black and white chapters carry almost all the page area. Blue belongs to 14px explanatory labels and selected interface marks, pastel washes belong behind demonstrations, and rainbow color stays a tiny sheen rather than becoming a page background.
- Proof looks like miniature working software: arrange 24px-radius charcoal cards with 12px gutters, overlapping desktop windows, and a shallow ribbon of tilted activity pills fading into black at both edges. For products without interface media, construct readable task, status and result miniatures instead.
- The page ends with a return to chat and an unhurried character-art landscape: repeat the small message stack and white action, then place a 900×525px low-contrast ASCII-style scene below a hairline footer. Create an original dotted scene of rest or completion if no equivalent artwork exists.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sheen gold | `#ffb005` | `--color-sheen-gold` | accent | Small bright stop in the chromatic sheen. |
| Sheen electric blue | `#0358f7` | `--color-sheen-blue` | accent | Small cool stop in the chromatic sheen. |
| Sheen vermilion | `#fa3d1d` | `--color-sheen-red` | accent | Small warm stop in the chromatic sheen. |
| Paper blue | `#0064dc` | `--color-blue` | text, link | Small explanatory headings on white. |
| Stage cyan | `#38bdf8` | `--color-cyan` | text, accent | Small explanatory headings on black, focus rings and active capacity dots; large color is confined to local media or plan glows. |
| Sheen mauve | `#c679c4` | `--color-sheen-purple` | accent | Narrow chromatic sheen in the identity and button effects, not a content fill. |
| Sheen ice | `#e1e1fe` | `--color-sheen-ice` | accent | Pale transition in the identity sheen. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-white` | background, surface, action | Full-width explanatory chapters, primary buttons and small browser windows. |
| Black stage | `#000000` | `--color-canvas` | background | Default page canvas and the backing behind floating scenes. |
| Button ink | `#0b0b0c` | `--color-action-ink` | text | Text and platform icon on white buttons. |
| Light-theme ink | `#171717` | `--color-ink` | text | Headings on white. |
| Charcoal card | `#181818` | `--color-card` | surface | Message bubbles, feature cards and trust tiles. |
| Dark hairline | `#1a1a1a` | `--color-edge` | border | Visible result of white at 10% on the black canvas, used for FAQ and footer separators. |
| Paragraph ink | `#3f3f3f` | `--color-body-ink` | text | Paragraphs in white chapters. |
| Caption gray | `#828282` | `--color-caption` | text | Reassurance text below calls to action and minor labels. |
| Continuation gray | `#969696` | `--color-muted` | text, link | Second headline line, small descriptions and navigation. |
| Secondary silver | `#c4c4c4` | `--color-secondary` | text | Longer explanatory copy on black and plus-symbol strokes. |
| Soft white | `#e8e8e8` | `--color-text` | text | Main dark-theme headings and conversational copy. |
| Off-white card | `#fafafa` | `--color-paper-card` | surface | Light feature cards beneath localized pastel washes. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Plan well | `#0c0c0c` | `--color-plan-well` | surface | Backing around the interactive plan selector. |

## Typography

- **Open Runde** — All marketing text, conversation, labels and actions. Soft rounded sans-serif with a compact friendly silhouette; semibold headings retain the same conversational scale as the interface. If unavailable, use **Nunito Sans**. Use 400–600 weights and retain tight tracking; rounded details will not match exactly. Font stack: "Open Runde", "Nunito Sans", system-ui, -apple-system, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | Open Runde | 600 | 28px | 1.15 | -0.035em | Two-line section statements, centered by default; left aligned in sticky demonstration chapters. |
| trust-statement | Open Runde | 600 | 21px | 1.2 | -0.03em | Trust tiles: bright claim continues directly into a muted explanation at the same weight and size. |
| faq-question | Open Runde | 600 | 19px | 1.3 | -0.022em | Full-width accordion question rows. |
| body | Open Runde | 400 | 16px | 1.65 | -0.01em | Explanatory paragraphs in two-column grids; dark ink on white, silver on black. |
| primary-action | Open Runde | 600 | 16px | 1.6 | -0.01em | Opening conversion button. |
| conversation | Open Runde | 400 | 15.5px | 1.4 | -0.01em | Opening and closing messages; these carry the opening promise instead of a display headline. |
| card-heading | Open Runde | 600 | 15px | 1.6 | -0.015em | Compact heading beneath a miniature interface. |
| feature-label | Open Runde | 600 | 14px | 1.6 | -0.005em | Blue or cyan headings directly above explanatory paragraphs. |
| footer-link | Open Runde | 400 | 14px | 1.6 | -0.0114em | Small footer utility navigation. |
| card-copy | Open Runde | 400 | 13.5px | 1.45 | -0.012em | Short feature-card explanations. |
| navigation | Open Runde | 500 | 13px | 1.6 | -0.012em | Header links and compact conversion button. |
| caption | Open Runde | 400 | 13px | 1.6 | -0.012em | Centered reassurance below conversion actions. |
| chapter-mark | Open Runde | 500 | 11px | 1.6 | 0.025em, uppercase | Small chapter-divider caption beside a symbol and a wavy hairline. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | plan-heading | Open Runde | 600 | 21px | 1.2 | -0.024em | Selected plan name. |
| pricing pages | billing-label | Open Runde | 500 | 13px | 1.6 | -0.006em | Monthly and annual segmented-control labels. |

**Notes:**

- Keep the scale intentionally restrained: section statements are only 28px, not oversized display type. Negative tracking tightens from body copy to the 28px heading.
- The muted second line is a continuation of the sentence, not a subtitle. Changing words keep the same semibold upright appearance.
- Trust copy uses a distinctive inline hierarchy: a bright short statement immediately followed by gray explanation, both 21px and weight 600.
- Use sentence case throughout except the 11px chapter markings. Product demonstrations may use their own native UI typography without changing the marketing font.

## Layout

**Density:** Airy outer composition with compact conversations and dense miniature software; broad chapter breaks contrast with close card gutters.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Gap between stacked conversation bubbles. |
| 10px | Gap between blue feature label and body paragraph; vertical message padding. |
| 12px | Card-grid gutters and avatar-to-message column gap. |
| 14px | Reassurance gap below the opening button. |
| 24px | Feature-card text insets and primary-button horizontal padding. |
| 26px | Trust-tile text insets. |
| 30px | Heading-to-grid gap, opening message-to-action gap and footer top inset. |
| 64px | Explanatory-grid row gap and footer-art separation. |
| 72px | Chapter-divider to demonstration-chapter content. |
| 84px | Explanatory-grid column gap. |
| 104px | White explanatory-band vertical padding. |
| 110px | Large separation before selected chapter headings and closing message stack. |
| 120px | Major dark chapter separation and footer separation. |

### Containers and grids

- **marketing-column**: max width 900px. Centered default width for header, card grids, prose grids and footer; at 1440px it leaves 270px of black or white on each side.
- **conversation-column**: max width 560px · gap 12px. Centered conversation stage with a 36px avatar column and message area; message and button widths cap at 400px.
- **explanation-grid**: 2 columns · gap 84px. Two equal 408px text columns within the marketing column; use a separate 64px row gap.
- **feature-bento**: 3 columns · gap 12px. A tall slightly wider left tile beside two upper tiles and one lower double-width tile. Keep media larger than captions.
- **trust-grid**: 12 columns · gap 12px. Asymmetric trust mosaic: first row splits seven and five tracks, subsequent rows support three equal-width cards.
- **demonstration-chapter**: 2 columns · gap 56px. A short sticky statement at left and a 520px-wide sequence of media demonstrations at right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | conversation-bubbles | 20px |
|  | feature-cards | 24px |
|  | trust-cards | 28px |
|  | browser-windows | 16px |
|  | media-backdrops | 22px |
| pricing pages | plan-shell | 30px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| dark-card-edge | `inset 0px 0px 0px 1px rgba(255, 255, 255, 0.06)` | Subtle edge on charcoal feature cards; not an exterior drop shadow. |
| trust-edge | `inset 0px 0px 0px 1px rgba(255, 255, 255, 0.06), inset 0px 1px 0px 0px rgba(255, 255, 255, 0.05)` | Slightly more tactile edge for trust tiles. |
| floating-browser | `0px 0px 0px 1px rgba(0, 0, 0, 0.08), 0px 24px 50px -20px rgba(0, 0, 0, 0.45)` | White browser cards over local gray or blue media backdrops. |

### Surfaces

#### Black stage · level 0

**Use:** Default canvas.

**CSS:** `background: #000000; color: #e8e8e8`

**Observed:** No full-page gradient or texture; black is uninterrupted between groups.

**Transfer:** Keep atmosphere concentrated in the objects rather than behind the whole page.

#### White chapter · level 0

**Use:** Explanatory and capability chapters.

**CSS:** `background: #ffffff; color: #3f3f3f; padding: 104px 0px`

**Observed:** Hard full-width transition from black to white; content remains in the same centered column.

**Transfer:** Use the inversion to mark a different reading mode, not as a separate visual identity.

#### Charcoal feature · level 1

**Use:** Grouped feature proof.

**CSS:** `background: #181818; border-radius: 24px; box-shadow: inset 0px 0px 0px 1px rgba(255, 255, 255, 0.06); overflow: hidden`

**Observed:** Media fills most of each tile and may extend to an edge; captions sit inside the lower edge.

**Transfer:** Use finished miniatures of one task instead of generic pictograms.

#### Trust tile · level 1

**Use:** Control, reliability and ownership explanations.

**CSS:** `background: #181818; border-radius: 28px; box-shadow: inset 0px 0px 0px 1px rgba(255, 255, 255, 0.06), inset 0px 1px 0px 0px rgba(255, 255, 255, 0.05); overflow: hidden`

**Observed:** Text sits at the top, with a larger tactile proof illustration beneath.

**Transfer:** Show a specific user decision or visible outcome for each claim.

#### Pastel proof tile · level 1

**Use:** Capabilities in white chapters.

**CSS:** `background: #fafafa; border-radius: 24px; overflow: hidden`

**Observed:** A gold, lavender, mint or blue wash begins near the top and fades to off-white. A thin tinted edge follows the card. The white nested interface fades softly toward the lower boundary.

**Transfer:** Use one gentle hue per capability; keep the lower half almost neutral. Add the wash as a separate layer rather than tinting all the text.

#### Selected plan stage · level 1

**Only for:** pricing pages

**Use:** Current plan detail inside the darker plan well.

**CSS:** `background: radial-gradient(80% 105% at 100% 0%, rgba(56, 189, 248, 0.5), rgba(56, 189, 248, 0.2) 34%, rgba(56, 189, 248, 0.06) 58%, rgba(0, 0, 0, 0) 78%), #181818; border-radius: 22px; padding: 28px 30px; overflow: hidden`

**Observed:** A fine reflective edge surrounds the detail stage; cyan illumination occupies the upper-right corner behind the billing control.

**Transfer:** Localize the bright corner to the selected detail, leaving the plan list dark.

## Components

### Primary button

**Use:** Main conversion below the opening messages.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 9px; background: #ffffff; color: #0b0b0c; border-radius: 9999px; height: 52px; max-width: 400px; padding: 0px 24px; overflow: hidden`

**Text style:** `primary-action` — Open Runde 600 · 16px/1.6 · tracking -0.01em

**Observed:** A small platform silhouette precedes the label. It shares the message width rather than expanding across the page. Closing uses an intrinsic-width 48px-high version; plan detail uses a 44px-high version.

**States:** Declared: hover opacity 1; focus-visible not specified for this variant; active transform scale(0.97).

### Compact button

**Use:** Header and contextual conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; color: #0b0b0c; border-radius: 9999px; height: 32px; padding: 0px 14px`

**Text style:** `navigation` — Open Runde 500 · 13px/1.6 · tracking -0.012em

**Observed:** Short label only in the header; the same white capsule appears at the right end of the contextual activity dock.

**States:** Declared: hover color #0b0b0c, background #ffffff, opacity 0.92; focus-visible unspecified; active transform scale(0.97).

### Navigation link

**Use:** Small utility navigation next to the compact action.

**CSS:** `display: flex; align-items: center; gap: 5px; padding: 6px 11px; border-radius: 9999px; color: #969696; height: 32px`

**Text style:** `navigation` — Open Runde 500 · 13px/1.6 · tracking -0.012em

**Observed:** Brand symbol and word sit left; a short right-aligned link group contains a disclosure control, a pricing link and the white action. Header height is 60px.

**States:** Declared: hover color rgb(232 232 232), background rgb(40 40 40 / .7); focus-visible box-shadow 0 0 0 2px rgb(56 189 248 / .7).

### Conversation bubble

**Use:** First-person opening and closing promise.

**CSS:** `background: #181818; color: #e8e8e8; border-radius: 20px; padding: 10px 15px; max-width: 400px`

**Text style:** `conversation` — Open Runde 400 · 15.5px/1.4 · tracking -0.01em

**Observed:** Left-aligned stack with a small standalone greeting above two longer bubbles. A 36px circular assistant avatar sits beside the bottom of the stack. Inline overlapping people or app tokens interrupt the sentence like familiar references; later bubbles may have a 7px lower-left corner.

**Transfer:** Let the new product explain itself in two small messages; use relevant compact tokens only when they help the sentence.

### Feature tile

**Use:** One capability proved by a small working scene.

**CSS:** `display: flex; flex-direction: column; background: #181818; border-radius: 24px; box-shadow: inset 0px 0px 0px 1px rgba(255, 255, 255, 0.06); overflow: hidden`

**Text style:** `card-heading` — Open Runde 600 · 15px/1.6 · tracking -0.015em

**Observed:** A large media stage comes before a bright heading and muted card-copy paragraph, inset 24px. Tiles mix tall, short and double-width forms instead of identical boxes.

**Transfer:** Choose one recognizable input, operation or outcome per tile.

### Trust card

**Use:** Concrete reassurance paired with visible proof.

**CSS:** `display: flex; flex-direction: column; background: #181818; border-radius: 28px; box-shadow: inset 0px 0px 0px 1px rgba(255, 255, 255, 0.06), inset 0px 1px 0px 0px rgba(255, 255, 255, 0.05); overflow: hidden`

**Text style:** `trust-statement` — Open Runde 600 · 21px/1.2 · tracking -0.03em

**Observed:** Claim and explanation run together at the top with 26px insets, changing from soft white to gray. Below are miniature encrypted rows, approval totals, permission dialogs or local-file lists.

### FAQ row

**Use:** Objection handling near the close.

**CSS:** `border-top: 1px solid rgba(255, 255, 255, 0.1); padding: 23px 0px; display: flex; align-items: center; justify-content: space-between; gap: 24px; color: #e8e8e8`

**Text style:** `faq-question` — Open Runde 600 · 19px/1.3 · tracking -0.022em

**Observed:** Full-width question with a 28px circular plus control at the far right. No enclosing card; rules define the list. The last row is an open invitation to ask another question, with muted text and an arrow.

**Transfer:** Use brief real objections, then a freeform question invitation rather than another sales claim.

### Footer link

**Use:** Single-row footer utilities above the landscape.

**CSS:** `display: flex; align-items: center; gap: 5px; color: #969696; height: 32px`

**Text style:** `footer-link` — Open Runde 400 · 14px/1.6 · tracking -0.0114em

**Observed:** Text identity left, compact utility links right with 28px horizontal gaps. A hairline and 30px top inset separate this row from the closing conversation. Contact includes a small diagonal arrow.

**States:** Declared: hover color rgb(232 232 232); focus-visible unspecified for this link variant.

### Plan selector

**Only for:** pricing pages

**Use:** Interactive choice instead of a row of independent pricing cards.

**CSS:** `display: grid; grid-template-columns: 296px minmax(0px, 1fr); background: #0c0c0c; border-radius: 30px; box-shadow: inset 0px 0px 0px 1px rgba(255, 255, 255, 0.05); overflow: hidden`

**Text style:** `plan-heading` — Open Runde 600 · 21px/1.2 · tracking -0.024em

**Observed:** A narrow vertical plan list sits beside one large selected-plan stage. Names, allowance and right-aligned prices live in the list; selected rows have a translucent gray 18px-radius highlight. Detail contains name, one-line description, oversized price, dot meter and action.

**Transfer:** Use a quantity ladder when plans share capabilities; do not invent feature differences to fill the layout.

### Billing switch

**Only for:** pricing pages

**Use:** Monthly and annual cadence control at the upper-right of the selected plan.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr; background: rgba(0, 0, 0, 0.38); border-radius: 9999px; box-shadow: inset 0px 0px 0px 1px rgba(255, 255, 255, 0.07); padding: 3px; width: 214px; height: 36px`

**Text style:** `billing-label` — Open Runde 500 · 13px/1.6 · tracking -0.006em

**Observed:** Selected half is a soft gray capsule; the unselected label is muted, with a tiny green discount badge attached to the annual option.

**States:** Declared: hover unspecified; focus-visible box-shadow 0 0 0 2px rgb(56 189 248 / .7) on each option; active transform scale(0.97).

### Capacity dot

**Only for:** pricing pages

**Use:** Quantified allowance proof below the selected price.

**CSS:** `width: 8px; height: 8px; border-radius: 30%; background: #38bdf8`

**Observed:** Fifty columns and five rows form a dense meter with 3px gaps. Active dots are cyan; inactive dots are white at 9% over charcoal. A small caption explains the unit and the current quantity underneath.

**Transfer:** Keep a fixed total matrix so quantity changes remain legible; provide the actual amount in text too.

## Imagery and graphics

### Activity ribbon

**Use:** A signature shallow scene below the opening conversation.

**Observed:** Two overlapping bands of tilted charcoal and metallic-gray capsules span beyond the viewport. Each holds a circular avatar or app token, a short task and a dim status line. Central capsules are sharp and bright while outer capsules fade into black. This is a low horizontal ribbon, not a large hero illustration.

**Transfer:** Use a set of plausible activities for the new product. If no interface exists, compose compact outcome cards with initials, a verb and a status.

**Build:** Create two flex tracks of pill-shaped cards with 5px inner padding and 17px right padding. Layer gray vertical gradients, vary card widths, rotate individual cards slightly in alternating directions, and overlap the tracks. Add circular tokens with inset white-alpha edges. Mask the whole scene with a horizontal transparent-to-black-to-transparent alpha mask and dim rear cards; keep the center luminous without neon.

### Browser proof on soft backing

**Use:** Repeated demonstrations in white chapters.

**Observed:** A 456×388px browser window sits inside a 520×452px, 22px-radius media board with 32px padding. Chrome is minimal, with three dots and a pill address bar. Backings alternate cool sky-blue illumination and soft gray; the browser throws a broad shadow. Completed views show concrete controls, products or seat selections rather than abstract illustration.

**Transfer:** Rebuild one believable workflow with readable major controls and a finished outcome. The minimum is a simplified browser frame showing a real input and result, not an empty rectangle.

**Build:** Place a white 16px-radius browser over a 22px-radius board. Layer broad radial highlights from the upper-left and upper-right, a subdued darker lower edge, and the floating-browser shadow. For the blue version use cyan diluted heavily with white; for the gray version use white and translucent black. Keep browser edges crisp while the backing stays diffuse.

### Layered desktop demonstration

**Use:** A broad product-context stage in the dark chapters.

**Observed:** Several familiar desktop windows overlap. The active window is large and bright toward the right, older windows recede leftward with lower opacity and darker treatment. A compact assistant input floats over the active application. Under the stage, small app tabs and a narrow explanatory label sit on black.

**Transfer:** Use original or permitted interface examples relevant to the new product. For an interface-less product, use layered document, list and result panels with one clearly active foreground panel.

**Build:** Arrange rounded rectangular window layers in a 900px-wide stage; dim the rear pair and offset them left. Give the front panel a fine light edge and a deep black shadow. Add a small translucent dark input strip over the panel and a row of subdued tab labels beneath.

### Pastel capability light

**Use:** Media cards within white chapters.

**Observed:** Soft gold, lavender, mint and blue light washes the upper part of off-white cards, fading to neutral below. Nested white UI panels and slight bottom fades make the illustrations feel integrated into the card rather than pasted on top.

**Transfer:** Choose muted hues to distinguish capabilities without assigning each a loud brand color.

**Build:** Overlay a radial gradient sized 130% by 62%, centered at 50% -8%, using the chosen hue at 30% alpha, then 8% at 46% and transparent at 74%. Add a faint vertical wash at 7% alpha. Use a masked 1px edge that is tinted near the top and neutral near the bottom; keep the 24px outer radius.

### Character-art epilogue

**Use:** Signature landscape beneath footer navigation on every page.

**Observed:** A wide, very dark gray ASCII-style seaside scene occupies 900×525px on black: a tall palm at left, a reclining person and small side table toward the center-right, sparse horizon lines and two bird silhouettes above. Tiny characters form contours instead of filled vector shapes; the scene stays subordinate to the links.

**Transfer:** Create an original character-art tableau conveying completion or relief. A simpler landscape made of dots, short dashes and a single resting object is the minimum acceptable equivalent; retain the expansive framing and low contrast.

**Build:** Draw an original silhouette scene in SVG within a 900×525 viewBox. Sample its contours on a fine grid and replace samples with small monospace dots, plus signs, hashes and dashes; vary opacity to shade forms. Use muted gray on black, leave large open areas, and place thin broken horizontal lines near the bottom. Keep any tiny bird silhouettes darker than the main scene.

### Contextual activity dock

**Use:** Small bottom-centered companion during long demonstrations.

**Observed:** A dark translucent rounded capsule floats over either theme, holding an assistant symbol, current task icon or status, and a small white conversion pill. Its short copy changes with the demonstration; it never becomes a full-width navigation bar.

**Transfer:** Tie its status to the visible demonstration and keep it compact enough that the product scene remains dominant.

**Build:** Use a charcoal translucent capsule with a faint white-alpha edge, a compact symbol at left, one short status line, and Compact button at right. Center it near the bottom of the viewport; preserve the same dark material when the underlying chapter turns white.

### Icons

**Observed:** Small rounded-stroke SVG marks, generally 12–14px with approximately 1.6–2.2px strokes, in gray or contextual cyan. White buttons use a dark filled platform silhouette around 15×18px. FAQ plus marks sit inside 28px low-contrast circles. Colorful app tokens are tiny accents inside product scenes.

**Transfer:** Choose compact rounded line icons for utility actions and filled silhouettes only where a familiar platform or application needs recognition. Avoid large feature-icon badges replacing the miniature demonstrations.

## Section recipes

How recurring sections are built.

### First screen: Conversation opening

**Observed:** A 60px header sits above a black open stage. A centered 560px conversation composition occupies the upper middle, with a short greeting and two left-aligned charcoal messages capped at 400px, a 36px avatar at the lower-left, and inline token clusters. There is no large headline: the conversation recipe at 15.5px carries the promise. Primary button follows after 30px, aligned to the bubble edge, with a centered caption 14px below it. A shallow viewport-wide Activity ribbon appears lower down, leaving a broad black pause between action and objects. Within the first 900px, the entire conversation, action, reassurance and ribbon are visible, followed by the next 28px two-tone heading and the top edge of its cards; the full proof grid falls below.

**Transfer:** Write an intimate two-message promise in the new product's voice and build original task capsules for the ribbon. If no media is available, the messages, token clusters and readable activity capsules provide the full opening object. Pricing opens with the same conversation but changes its message to choice and commitment, then brings the plan selector into the lower part of the first screen.

**Avoid:** Do not replace the conversation with a 72px slogan, a centered paragraph or an enormous laptop mockup. Do not let the capsule ribbon crowd the primary action or read like a testimonial logo wall.

**Text style:** `conversation` — Open Runde 400 · 15.5px/1.4 · tracking -0.01em

### Two-tone chapter statement

**Observed:** A short 28px heading splits into a bright first line and muted continuation at the same size. Centered headings sit 30px above their scene; the continuation can change words while preserving the sentence stem. Light chapters use dark ink and mid-gray. The demonstration-chapter version is left-aligned and remains beside the changing media.

**Transfer:** Use an incomplete sentence that naturally completes with several concrete user situations; a static continuation is sufficient when no meaningful alternatives exist.

**Text style:** `heading` — Open Runde 600 · 28px/1.15 · tracking -0.035em

### Proof bento

**Observed:** Feature tile components fill a 900px-wide, 12px-gutter grid beneath a Two-tone chapter statement. A tall list-based card anchors one side, two small media cards sit above a broad lower scene on the other side. Media dominates, with compact headings and descriptions at the bottom.

**Transfer:** Compose a hierarchy of related proof instead of equalizing every capability. Let the richest scene take the tall or broad card.

### Explanation band

**Observed:** White chapter contains a two-column explanatory grid of 408px text blocks separated by 84px horizontally and 64px vertically. Blue feature-label headings precede 16px body paragraphs by 10px. Dark variants use cyan labels and silver body copy without adding boxes.

**Transfer:** Pair each concise label with one mechanism or outcome, keeping comparable paragraph lengths across each row.

**Text style:** `body` — Open Runde 400 · 16px/1.65 · tracking -0.01em

### Sticky demonstration chapter

**Observed:** A Chapter-mark divider combines a tiny symbol, uppercase label, wavy segment and straight hairline. Below a 72px pause, a narrow left heading accompanies a 520px right column of Browser proof on soft backing. Each media board is followed by a blue label and explanatory paragraph; the left sentence continuation responds to the active scene.

**Transfer:** Use this for several concrete examples sharing one promise. The heading should remain a short companion to the demonstration, not compete with it.

### Pastel capability mosaic

**Observed:** White chapter starts with a centered Two-tone chapter statement. A three-track grid uses Pastel proof tile surfaces with 12px gaps, alternating two-track and one-track cards. Small headings and copy sit at the top while readable UI occupies the lower stage; an Explanation band follows.

**Transfer:** Use broader tiles for wide outputs and narrower tiles for lists or repeated events.

### Trust mosaic

**Observed:** A Two-tone chapter statement precedes Trust card components on black. A seven/five-track pair introduces the largest claims; smaller cards form a lower row. Each combines an inline white/gray statement with an original mechanism illustration, not a decorative lock alone.

**Transfer:** Choose verifiable reassurances relevant to the new product and pair each with a visible control, boundary or result.

**Text style:** `trust-statement` — Open Runde 600 · 21px/1.2 · tracking -0.03em

### Questions and conversational close

**Observed:** A centered two-line heading introduces FAQ row components with fine separators and circular plus controls. The last line invites an unscripted question. After a 110px pause, a fresh Conversation bubble stack acknowledges the reader's progress, then offers an intrinsic-width white action and reassurance caption. Footer navigation follows after a 120px separation; Character-art epilogue sits 64px beneath its row with copyright below.

**Transfer:** Return to the same voice and message alignment as the opening. Let the final message make the product feel present, then leave room for a restful original character-art scene rather than a large repeated slogan.

### Quantity-based pricing stage

**Only for:** pricing pages

**Observed:** Conversation opening leads to a two-tone heading and Plan selector. Its 900×444px outer shell divides into a 296px list and a 596×428px selected stage. Billing switch sits upper-right; large price numerals dominate the left middle, followed by a Capacity dot matrix and a white action. Shared capabilities move to a white Explanation band, then questions and the conversational close.

**Transfer:** Use one active detail panel, a transparent unit explanation and clearly scaled quantities. Keep oversized price numerals around 72px as design guidance; the 28px section headings stay modest.

## Page flow

**Storyline:** Conversational promise → tangible working proof → plain-language explanation → confidence and choice → questions → personal closing exchange → restful illustrated epilogue.

### A product landing page that makes broad capabilities feel like specific everyday help

1. **Promise** — Small first-person message stack with a bright action and a shallow activity ribbon.
2. **Product proof** — Asymmetric miniature-interface bento beneath a changing sentence-fragment heading.
3. **Explanation** — White prose grid and sticky demonstration chapter with locally backed browser scenes.
4. **Capability chapters** — Dark feature scenes and layered desktop demonstration, then a white pastel capability mosaic.
5. **Trust** — Charcoal mosaic of explicit user boundaries and tactile proof controls.
6. **Objection handling** — Rule-separated questions and an invitation to ask another.
7. **Closing call** — Return to conversational messages and a small white action.
8. **Epilogue** — Utility footer and low-contrast character-art landscape.

**Transfer:** Adapt the number and order of capability chapters to the new product. Retain the conversational framing, working miniatures, theme inversion and restful ending rather than reproducing a long catalogue.

### A pricing page that frames cost as quantity rather than withheld functionality

1. **Promise** — Short conversation about starting and choosing, with the shared opening action.
2. **Pricing** — Vertical plan list and one selected detail panel, billing switch, large price and quantified dot meter.
3. **Capability confirmation** — White two-column grid explaining what is shared across the offer.
4. **Objection handling** — Pricing-specific questions in the same dark FAQ treatment.
5. **Closing call** — A fresh friendly message exchange followed by the white action.
6. **Epilogue** — Shared utility footer and character-art landscape.

**Transfer:** Keep the shared conversational shell and use a quantity selector only if the business model supports it; put billing mechanics in questions rather than dense comparison tables.

## Writing

Friendly, matter-of-fact and unusually personal for software. Concrete verbs and tiny scenarios explain the work; reassurance is stated as a visible boundary rather than corporate trust language.

**Do not copy:** Do not reuse Merlin's name, domain, logo, mascot, app artwork, ASCII beach scene, named sample people, exact pricing, credit allowances, free-forever promise or privacy claims. Source examples illustrate voice only; new claims must be true for the new product.

- **Addressing the reader:** Address the reader as you. In chat the product speaks as lowercase i; explanatory sections refer to it by name. Use personal pronouns and ordinary relationships rather than abstract user categories.
- **Rhythm:** Messages are brief and informal. Headings are sentence fragments of roughly 4–9 words, often starting with For, And, Anywhere, Everything or But. Support copy commonly uses two or three short sentences: a situation, the action, then the reader's control.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening message | A small greeting followed by what the product does in first person, using familiar situations. | 3–18 words per message or clause | “hey, i'm merlin”<br>“and i do the errands you'd normally do in a” |
| Chapter heading | Sentence stem completed by a concrete situation; natural connective words make chapters feel conversational. | 4–9 words | “For everyone you owe a reply”<br>“But nothing you didn't ask for” |
| Explanatory paragraph | Describe the event, what happens next, and where the reader remains involved. | 20–45 words | “Mom asked on the call. [Brand] searches, picks the nonstop she'd want, and takes it to the last step. You approve the fare, and she's booked.” |
| Trust statement | Short direct boundary, often followed by an equally plain explanation. | 3–10 words before support | “Nothing happens without your tap.”<br>“It looks only when you say.” |
| Action and reassurance | Name the immediate action and platform; put a short factual reassurance underneath. | 1–4 words for action; 3–7 for reassurance | “Download for Mac”<br>“Free forever. No credit card.” |
| Pricing framing | State how choice works in ordinary conversational terms. | One or two short sentences | “Every plan is all of [Brand]. You only choose how much it does for you in a month.” |
| Closing message | Acknowledge the reader's arrival with a light, situational observation. | 6–12 words | “a minute of scrolling and you're at the bottom” |

**Words and phrasing to use:** say it once; ready for you; when you say; your yes; keeps; remembers; shows; waits; one list; yours to keep

**Avoid:** revolutionary; unlock potential; enterprise-grade synergy; seamless ecosystem; supercharge everything; autonomous magic

**Rules:**

- Explain mechanisms with verbs: reads, shows, files, waits, opens and keeps.
- Make reassurance specific to an actual boundary or permission.
- Use lowercase informality inside chat, but normal sentence casing in feature prose.
- Use contractions and concrete time or event cues instead of technical abstractions.
- Questions should sound like something a prospective customer would actually ask.

## Do's and Don'ts

### Do

- Keep ordinary section headlines at 28px/1.15 and weight 600, with a gray continuation at the same size.
- Align the opening 400px action with the message column, not with the avatar.
- Use 12px gutters between charcoal proof cards and 24px text insets.
- Let black and white occupy the broad bands; reserve cyan and blue for compact labels and local proof lighting.
- Keep explanatory grids to two 408px columns with 84px between them at desktop.
- Pair trust claims with a visible miniature control, using 21px inline white-to-gray statements.
- Maintain the low-contrast 900×525px character-art ending with open space around the forms.
- Use full capsule actions and the same near-black label on every white primary button.

### Don't

- Do not use a heavy display face or weight 800 to make the modest 28px headings feel more important.
- Do not recolor the main conversion button cyan; its white fill is the clearest action signal.
- Do not turn the 14px blue explanatory headings into pill tags or oversized feature titles.
- Do not apply a bright rainbow gradient across a hero or card grid; the chromatic sheen is a tiny localized effect.
- Do not make all proof cards identical squares; tall lists and broad scenes need different proportions.
- Do not replace the faint inset card edge with a thick gray outline or a glowing exterior border.
- Do not render the character-art ending as a high-contrast full-color illustration; its darkness is part of the decompression.
- Do not turn the compact activity dock into a full-width sticky banner or add several competing calls to action.

## Motion and responsive

### Motion

**Observed:**

- Declared button transition: transform .16s cubic-bezier(.23, 1, .32, 1), opacity .16s ease; active buttons scale to 0.97.
- Declared conversation pop: .42s cubic-bezier(.23, 1, .32, 1), staggered by 420ms with a 120ms initial delay.
- Declared identity-sheen transition: background-position 1.5s cubic-bezier(0.4, 0, 0.2, 1).
- Declared plan highlight transition: transform .34s cubic-bezier(.23, 1, .32, 1); capacity dots use background-color .3s ease with a per-dot 7ms delay.
- Declared bird drift runs over 4.7s ease-in-out, infinitely; chapter continuations and active desktop scenes change through the page.

**Transfer:**

- Keep conversions tactile with the small press scale, not dramatic bounce.
- Use message-by-message arrivals to reinforce the conversational opening and close.
- Preserve a calm moving detail in the character-art epilogue while leaving the main composition still.

**Unknown:**

- Precise scroll triggers, complete scene choreography and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Width breakpoints are declared between 430px and 1080px, with frequent rules around 480px, 520px, 560px, 600px, 720px, 820px, 860px and 900px.

**Transfer:**

- On narrow screens, prioritize the message column and its action; keep the avatar small instead of letting it steal message width.
- Stack the asymmetric proof mosaic while retaining a distinct wide-scene hierarchy. Move the sticky chapter heading above the demonstrations.
- Keep the character-art scene as a complete wide composition scaled to the content width. Let the activity ribbon remain edge-masked rather than wrapping into a dense wall.

**Unknown:**

- Exact mobile side padding, type changes, navigation replacement and stacking order are not established. These narrow-screen rules are adaptations rather than fixed layouts.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
