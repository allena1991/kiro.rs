# Dia — sunlit workday theatre

## Overview

A sunlit, editorial take on useful software: warm paper, buttery yellow, black ink and delicate serif headlines make technology feel personal rather than industrial. A light grotesk and small monospaced markings support generous, low-density compositions, while large interface scenes supply the detail. The default is theatrical and optimistic; more practical pages become spare and instructional, while audience campaigns add pixel graphics and cut-and-paste energy.

### Essentials

- A modest promise sits above a monumental identity: the opening pairs a white 38.8px serif headline with an approximately 763px-wide ornamental word sculpture and a 1115px-wide product scene.
- Sunlight is concentrated, not distributed: a full 900px yellow opening gives way to #fbfaf6 paper for almost all remaining content; interface imagery carries the smaller pastel colors.
- Conversion rises on a curved horizon: a paper ellipse about 2034px by 978px carries a black 443px by 56px pill with 20px light sans text. Preserve this curved conversion stage and its closing reprise.
- Serifs supply humanity without shouting: section headings use Exposure VAR at 48px/56px, weight 500, -0.05em tracking; explanatory feature text uses a light 20px/1.5 grotesk.
- The product is treated like an illuminated object: large 12px-rounded interface windows float with soft layered shadows; smaller feature scenes dissolve into the paper rather than filling every card edge.
- Control becomes a graphic rhythm: a fine dotted enclosure holds a split serif statement interrupted by a horizontal stream of 35px-high status chips; use an equivalent meaningful control or proof motif for any product.
- The ending reads like a maker's imprint: four small footer link groups in 13px uppercase mono with 0.1em tracking, a separate emblem and a hairline above centered maker credit.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Golden sunlight | `#ffcb30` | `--color-sun` | background, accent | Full-bleed opening atmosphere, followed by predominantly paper sections. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter glow | `#ffe48c` | `--color-glow` | accent | Blurred ellipse behind the curved conversion horizon, at 70% opacity. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pure white | `#ffffff` | `--color-white` | text, surface | Opening promise and identity artwork, small feature labels and campaign cards. |
| Warm paper | `#fbfaf6` | `--color-canvas` | background | Default page canvas and curved conversion horizon. |
| Porcelain | `#f8f8f8` | `--color-navigation` | surface, text | Floating navigation surface and pale text on the main black conversion button. |
| Control wash | `#f0f0ee` | `--color-chip` | surface | Visible wash of rgba(235,235,235,0.7) over warm paper in demonstration chips. |
| Light gray action | `#efefef` | `--color-secondary-action` | action, surface | Small supporting pill links. |
| Soft edge | `#e7e6e2` | `--color-edge` | border | 8% black edge over paper; floating panels use the same alpha over porcelain. |
| Imprint rule | `#e5e5e1` | `--color-rule` | border | 8.6% black footer divider over paper. |
| Fine card outline | `#b0afac` | `--color-card-edge` | border | 30% black at 0.5px around transparent feature cards. |
| Faded imprint | `#91908e` | `--color-footer-ink` | text | Footer links; 42.4% black over warm paper. |
| Secondary ink | `#646462` | `--color-secondary` | text | Support paragraphs; visible result of 60% black on warm paper. |
| Feature ink | `#4b4b4a` | `--color-feature-ink` | text | Feature explanations; visible result of 70% black on paper. |
| Soft black ink | `#262625` | `--color-ink` | text, border | Primary marketing text; rgba(0,0,0,0.85) appears this way over warm paper. |
| Solid black | `#000000` | `--color-black` | text, action, surface | Primary buttons, selected campaign panels and strongest text. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lemon-lime indicator | `#f2fcb3` | `--color-on` | accent | 12px on-state dots in the control demonstration. |
| Yellow indicator | `#ffdc5c` | `--color-off` | accent | 12px off-state dots in the control demonstration. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| release articles | Release gray | `#979694` | `--color-muted` | text | Release item descriptions; 40% black over paper. |
| business information pages | Question rule | `#e2e1dd` | `--color-faq-rule` | border | 10% black FAQ divider over paper. |
| release articles | Release violet | `#6038f0` | `--color-release-accent` | text, border, accent | Platform badge icon, text and edge. |
| release articles | Release lavender | `#eeeafd` | `--color-release-wash` | surface | Platform badge fill. |

## Typography

- **ABC Oracle** — Body copy, feature explanations, navigation, buttons and practical page headings. Open, low-contrast grotesk; light weights give large text an unforced conversational quality. If unavailable, use **Inter**. Use weights 300–500 and retain tight tracking on large headings. Font stack: "ABC Oracle", "Inter", Helvetica, sans-serif.
- **Exposure VAR** — Editorial promises and section headings. Expressive high-contrast serif with curved, calligraphic terminals; campaign weights become rounded and emphatic. If unavailable, use **Source Serif 4**. Use 400–650; preserve the short line measures and negative tracking. Font stack: "Exposure VAR", "Source Serif 4", Georgia, serif.
- **ABC Favorit Mono** — Footer imprint and campaign descriptions. Small monospaced letters; widely spaced capitals for the imprint, compact sentence case for campaign copy. If unavailable, use **IBM Plex Mono**. Font stack: "ABC Favorit Mono", "IBM Plex Mono", monospace.
- **ABC Oracle Triple** — Control chips and platform badges. Compact utilitarian companion to the main grotesk. If unavailable, use **Inter**. Font stack: "ABC Oracle Triple", "Inter", Helvetica, sans-serif.
- **Ammer Handwriting** (only for release articles) — Contributor first-name signatures. Loose sloping pen strokes that contrast with the tidy two-column list. If unavailable, use **Caveat**. Font stack: "Ammer Handwriting", "Caveat", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| section-heading | Exposure VAR | 500 | 48px | 56px | -0.05em | Default section leads and closing question. |
| opening-promise | Exposure VAR | 500 | 38.8px | 1.1 | -0.04em | Centered white sentence above identity artwork. |
| chapter-title | Exposure VAR | 500 | 24px | 1.25 | -0.03em | Short titles in the sticky product chapter index. |
| support | ABC Oracle | 400 | 22px | 30px | normal | Centered reassurance paragraphs. |
| feature-copy | ABC Oracle | 350 | 20px | 1.5 | -0.02em | Explanations inside feature cards; prose serves as the heading rather than a separate bold title. |
| primary-action | ABC Oracle | 350 | 20px | 1.2 | normal | Black conversion pill. |
| body | ABC Oracle | 400 | 16px | 1.5 | normal | FAQ questions and answers; ordinary informational copy. |
| navigation | ABC Oracle | 400 | 16px | 1.25 | normal | Floating header links and secondary download action. |
| control-label | ABC Oracle Triple | 400 | 16px | 35px | normal | Control demonstration chips. |
| supporting-action | ABC Oracle | 400 | 16px | 35px | normal | Small gray pill links. |
| imprint | ABC Favorit Mono | 400 | 13px | 16px | 0.1em, uppercase | Footer links and maker credit. |
| imprint-heading | ABC Favorit Mono | 400 | 13px | 17px | 0.1em, uppercase | Footer group headings. |
| feature-label | ABC Oracle | 400 | 12px | 30px | 0.06em, uppercase | White capsule label above feature prose. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| business information pages | business-display | ABC Oracle | 300 | 72px | 84px | -0.04em | Restrained, centered sans opening. |
| playful audience campaigns | audience-display | Exposure VAR | 650 | 56px | 62px | -0.05em | Heavy centered multi-line promises and closing call. |
| onboarding and help pages | practical-heading | ABC Oracle | 300 | 54px | 60px | -0.04em | Two-line installation heading and FAQ title. |
| playful audience campaigns | campaign-heading | Exposure VAR | 650 | 48px | 58px | -0.05em | Secondary campaign section heading. |
| release articles | release-heading | Exposure VAR | 400 | 44px | 50px | -0.05em | Left-aligned article title. |
| release articles | signature | Ammer Handwriting | 350 | 36px | 24px | -0.0044em | Handwritten contributor first names. |
| playful audience campaigns | campaign-card-title | Exposure VAR | 650 | 28px | 30px | -0.04em | Card and role titles. |
| playful audience campaigns | campaign-question | Exposure VAR | 650 | 24px | 28px | -0.04em | Large question labels in heavier ruled accordions. |
| playful audience campaigns | campaign-command | Exposure VAR | 650 | 24px | 1.5 | -0.05em | Short command title beneath context tags in a paper card. |
| onboarding pages | instruction | ABC Oracle | 400 | 18px | 1.5 | -0.02em | Numbered captions below instructional illustrations. |
| release articles | release-title | ABC Oracle | 400 | 18px | 23px | -0.02em | Individual change titles. |
| release articles | release-intro | ABC Oracle | 350 italic | 18px | 26px | -0.02em | Short editorial summary above the change list. |
| release articles | release-body | ABC Oracle | 350 | 16px | 23px | -0.01em | Muted change descriptions and contributor attribution prefix. |
| release articles | platform-label | ABC Oracle Triple | 400 | 16px | 18px | -0.02em | Compact platform badge. |
| playful audience campaigns | campaign-body | ABC Favorit Mono | 400 | 14px | 1.5 | -0.02em | Compact typewritten explanations. |

**Notes:**

- The main opening sentence is smaller than the default section heading because the ornamental identity and product window carry its visual scale.
- The serif tightens to -0.05em for section headings. Body text is mostly regular or light, not semibold; footer hierarchy comes from ink contrast rather than size.
- Use the heavy serif and typewritten descriptions together only in the playful campaign variant. Practical information pages use light sans headings instead.

## Layout

**Density:** Airy at section scale, compact within interface scenes and the footer; text occupies much less space than demonstrations.

### Spacing

**Spacing system:**

- **rhythm** 10px, vertical — Dominant vertical cadence; 20px, 30px, 40px, 60px and 80px are recurring multiples, not an exclusive grid.

| Value | Use |
| --- | --- |
| 10px | Small paragraph separations and footer list gaps. |
| 16px | Navigation item gaps and conversion support-line gap. |
| 20px | Grid gutters, chip gaps and feature-label-to-copy separation. |
| 30px | Feature copy panel padding and campaign support gap. |
| 40px | Support-to-action gap and pauses within reassurance panels. |
| 60px | Practical heading-to-illustration gap; campaign closing panel padding. |
| 80px | Section title to feature grid and footer group spacing. |
| 100px | Information page section margins and release article breathing room. |
| 120px | Major marketing section separation. |
| 160px | Audience opening top padding and campaign chapter separations. |

### Containers and grids

- **site-grid**: max width 1440px · 12 columns · gap 20px · side padding 10px. Centered outer site grid. Feature chapters and footer occupy the central ten columns, giving an effective 1180px content band at desktop.
- **demonstration-chapters**: max width 1400px · 12 columns · gap 20px · side padding 10px. A four-column sticky text index sits beside an eight-column image lane; images themselves stop at 760px.
- **feature-pair**: max width 1180px · 10 columns · gap 20px. Alternate six/four and four/six column cards rather than equal tiles; typical widths are 700px and 460px.
- **questions**: max width 800px · 1 column · gap 10px · side padding 20px. Narrow centered FAQ stack with restrained row separators.
- **release-list** (only for release articles): max width 980px · 2 columns · gap 50px. Two 465px columns, 51px row spacing; article header stays at 615px and a back link sits outside the article on the left.
- **onboarding-triptych** (only for onboarding pages): max width 1440px · 12 columns · gap 20px · side padding 20px. Three illustration/caption groups occupy three, four and three columns inside the centered grid, making the middle image wider.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary-pill | 9999px (pill) |
|  | feature-and-media | 12px |
|  | floating-navigation | 16px |
|  | supporting-pills | 20px |
| playful audience campaigns | campaign-button | 14px |
| playful audience campaigns | campaign-cards | 16px |
| onboarding pages | instruction-images | 20px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | product-window | `0px 1px 2px 0px rgba(0,0,0,0.04), 0px 12px 28px -12px rgba(0,0,0,0.1), 0px 28px 56px -28px rgba(0,0,0,0.12)` | Large demonstration windows. |
|  | floating-navigation | `0px 2px 8px 0px rgba(0,0,0,0.06), 0px 0px 2px 0px rgba(0,0,0,0.04)` | Floating header islands. |
| playful audience campaigns | cut-paper-offset | `-3px 3px 0px 0px #000000` | Hard-edged offset beneath media and the central closing panel. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default long-form background.

**CSS:** `background: #fbfaf6; color: rgba(0,0,0,0.85)`

#### Sunlit stage · level 0

**Use:** Immersive marketing opening.

**CSS:** `background-color: #ffcb30; overflow: hidden; position: relative`

**Observed:** Soft, out-of-focus leaf shadows cross the yellow field; white identity artwork and a luminous product window sit above it.

**Transfer:** Keep a single warm, saturated stage against an otherwise paper-dominant page.

#### Transparent feature card · level 1

**Use:** Capability scenes.

**CSS:** `border: 0.5px solid rgba(0,0,0,0.3); border-radius: 12px; overflow: hidden; display: flex; flex-direction: column`

**Observed:** The page paper shows through. A label and prose sit above bottom-anchored media; the card is not given a heavy floating shadow.

**Transfer:** Use the edge to group the explanation without making the whole page a dashboard.

#### Floating porcelain · level 3

**Use:** Header islands.

**CSS:** `background: #f8f8f8; border: 1px solid rgba(0,0,0,0.08); border-radius: 16px; backdrop-filter: blur(12px); box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.06), 0px 0px 2px 0px rgba(0,0,0,0.04)`

#### Campaign paper · level 2

**Only for:** playful audience campaigns

**Use:** Command cards and overlapping closing call.

**CSS:** `background: #f8f8f8; border: 2px solid rgba(0,0,0,0.85); border-radius: 16px; box-shadow: -3px 3px 0px 0px #000000`

**Observed:** A bolder paper-and-ink system; context cards can instead be pure white without the offset shadow.

**Transfer:** Keep this visibly separate from the delicate default feature system.

## Components

### Floating navigation

**Use:** Persistent compact navigation above the page.

**CSS:** `display: flex; align-items: center; gap: 16px; height: 52px; padding: 0px 24px 0px 6px; background: #f8f8f8; border: 1px solid rgba(0,0,0,0.08); border-radius: 16px; backdrop-filter: blur(12px); box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.06), 0px 0px 2px 0px rgba(0,0,0,0.04)`

**Text style:** `navigation` — ABC Oracle 400 · 16px/1.25

**Observed:** A centered island about 307px wide, fixed 28px below the viewport top. A 40px logo hit area precedes three links; no full-width header bar.

**Transfer:** Use a small original emblem and three short destinations.

### Primary button

**Use:** Default landing-page conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; height: 56px; max-width: 443px; padding: 0px 22px 0px 24px; background: #000000; color: #f8f8f8; border-radius: 9999px`

**Text style:** `primary-action` — ABC Oracle 350 · 20px/1.2

**Observed:** Centered within the curved conversion horizon, with an understated downward arrow and availability note beneath. It remains present while the long product story scrolls.

**States:** Declared: focus-visible outline transparent solid 2px; outline-offset 2px; box-shadow 0 0 #0000,0 0 #0000,0 0 #0000.

**Transfer:** Keep the unusually broad pill and concise verb; availability becomes any useful compatibility or commitment note.

### Header action

**Use:** Secondary conversion at the top-right during the product story.

**CSS:** `display: flex; align-items: center; gap: 8px; height: 48px; padding: 0px 24px; background: #f8f8f8; color: rgba(0,0,0,0.85); border: 1px solid rgba(0,0,0,0.08); border-radius: 16px; backdrop-filter: blur(12px)`

**Text style:** `navigation` — ABC Oracle 400 · 16px/1.25

**Observed:** Separate from the centered navigation island, with a small platform symbol before the label.

**States:** Declared: hover background-color rgba(0,0,0,0.12).

### Feature card

**Use:** Default capability grid item.

**CSS:** `display: flex; flex-direction: column; border: 0.5px solid rgba(0,0,0,0.3); border-radius: 12px; overflow: hidden`

**Text style:** `feature-copy` — ABC Oracle 350 · 20px/1.5 · tracking -0.02em

**Observed:** A Feature label sits above explanatory prose in a 30px-padded text area. Media is anchored below; wide and narrow cards alternate.

**Transfer:** Give each card one behavior and one concrete scene, not an icon plus a generic slogan.

### Feature label

**Use:** Small category within a feature card.

**CSS:** `background: #ffffff; color: rgba(0,0,0,0.55); height: 30px; padding: 0px 12px; border-radius: 20px`

**Text style:** `feature-label` — ABC Oracle 400 · 12px/30px · tracking 0.06em · uppercase

**Observed:** A fitted capsule aligned near the text edge; much quieter than the body explanation.

### Status chip

**Use:** Interactive-looking demonstration strip within a reassurance section.

**CSS:** `display: flex; align-items: center; gap: 14px; height: 35px; padding: 0px 16px; border-radius: 20px; background: rgba(235,235,235,0.7); color: rgba(0,0,0,0.85)`

**Text style:** `control-label` — ABC Oracle Triple 400 · 16px/35px

**Observed:** A pale state dot precedes the label, and a small white rectangular state word follows it. Chips repeat across a clipped horizontal line.

**Transfer:** Show meaningful controls or verified capabilities; distinguish demonstration from actual preference controls.

### Supporting pill link

**Use:** Secondary explanation link beneath reassurance copy.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 12px; height: 35px; padding: 0px 24px; background: #efefef; border-radius: 20px; color: rgba(0,0,0,0.85)`

**Text style:** `supporting-action` — ABC Oracle 400 · 16px/35px

**Observed:** Right arrow after the text; lower contrast than the black conversion action.

### Question row

**Use:** FAQ disclosure in information and onboarding sections.

**CSS:** `position: relative; height: 44px; padding-left: 24px; text-align: left; color: rgba(0,0,0,0.85)`

**Text style:** `body` — ABC Oracle 400 · 16px/1.5

**Observed:** A 12px plus sits on the left, with a fine ruled wrapper and a 10px gap between rows. Expanded answers align to the question text and use secondary ink. Campaign questions instead use Campaign question type, right-side 20px plus, 30px vertical padding and 2px dark rules.

**Transfer:** Use the light version by default; do not show all answers as permanently expanded content.

### Footer imprint

**Use:** Shared ending after every page type.

**CSS:** `display: flex; gap: 80px; padding-bottom: 20px; border-bottom: 1px solid rgba(0,0,0,0.086)`

**Text style:** `imprint` — ABC Favorit Mono 400 · 13px/16px · tracking 0.1em · uppercase

**Observed:** Four link groups with darker Imprint heading titles and faded links, plus a separate 85px by 102px emblem on the right. A lower row has copyright at left and centered two-line maker credit.

**States:** Declared: hover link color rgba(0,0,0,0.85).

**Transfer:** Use the new company's compact seal or typographic emblem rather than enlarging a conventional footer logo.

### Campaign command card

**Only for:** playful audience campaigns

**Use:** Layered paper command examples.

**CSS:** `display: flex; flex-direction: column; padding: 20px; background: #ffffff; border: 2px solid rgba(0,0,0,0.85); border-radius: 16px; overflow: hidden`

**Text style:** `campaign-command` — Exposure VAR 650 · 24px/1.5 · tracking -0.05em

**Observed:** Context tags with small document icons come first, then a serif slash command and a Campaign body description. Cards overlap a wide browser strip at varied vertical offsets.

**Transfer:** Replace slash commands with the product's own short actions while retaining the context-to-action hierarchy.

### Campaign closing panel

**Only for:** playful audience campaigns

**Use:** Conversion panel in a collage ending.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 40px; padding: 60px; background: #f8f8f8; border: 2px solid rgba(0,0,0,0.85); border-radius: 16px; box-shadow: -3px 3px 0px 0px #000000`

**Text style:** `audience-display` — Exposure VAR 650 · 56px/62px · tracking -0.05em

**Observed:** A central panel about 807px wide stands in front of photographs, portrait video and a vertical pixel-icon strip. The black campaign action is compact, 56px high with a 14px radius rather than the default wide pill.

**Transfer:** Keep surrounding imagery subordinate to the central promise and button.

### Platform badge

**Only for:** release articles

**Use:** Platform metadata below an article title.

**CSS:** `display: flex; align-items: center; gap: 7px; height: 30px; padding: 0px 11px; background: #eeeafd; color: #6038f0; border: 1px solid #6038f0; border-radius: 100px`

**Text style:** `platform-label` — ABC Oracle Triple 400 · 16px/18px · tracking -0.02em

**Observed:** A small platform icon precedes the text; a neutral version badge sits beside it.

**Transfer:** Reserve this violet accent for metadata rather than introducing violet throughout the marketing page.

## Imagery and graphics

### Sunlight and identity theatre

**Use:** Signature marketing stage, before the paper product story.

**Observed:** A warm yellow field is crossed by blurry leaf silhouettes like sunlight through a tree. White ornamental identity letters occupy about half the width behind the upper portion of a large frontal browser window. The window's lower edge glows into the curved paper foreground.

**Transfer:** Create a new oversized typographic identity, not a generic stock-photo hero. Without polished motion artwork, a carefully typeset ornamental name, blurred botanical shadows and one crisp product still are the minimum acceptable scene.

**Build:** Layer a #ffcb30 field, then SVG clusters of elongated leaf-like ellipses in rgba(0,0,0,0.16) and rgba(0,0,0,0.08), at varied diagonal angles, blurred 18px–40px. Place an original white serif word sculpture in an approximately 763px by 284px frame behind a 1115px-wide product window. Let the shadow field cover the entire opening; keep highlights warmer than white.

### Curved conversion horizon

**Use:** Signature foreground across the long marketing story and its closing call.

**Observed:** A broad cream arc rises from the bottom edges to a high center, carrying the black action. Its upper edge has a soft warm glow in the opening and a subtle shadow on later paper sections.

**Transfer:** Retain the horizon as the recurring conversion device even when the product is not downloadable.

**Build:** Clip a centered 2034px by 978px paper ellipse with border-radius:50% inside a full-width foreground wrapper. Place a 1424px by 285px #ffe48c ellipse behind it, opacity 0.7 and blur(40px). Keep the primary action centered on top; position the ellipse so only its upper cap is visible, not a complete oval.

### Luminous interface windows

**Use:** Primary evidence throughout capability chapters.

**Observed:** Large straight-on browser scenes, usually around 760px by 562px, show real documents, messages and organized sidebars. Pale yellow, blue, green and pink live inside the windows; the surrounding page stays cream. Feature-card windows have soft reflections and bottom fades instead of hard cutout edges.

**Transfer:** Show a credible task in the new product with readable hierarchy, not decorative dashboard noise. If no interface exists, make a faithful task-output mockup using the same straight-on framing and restrained pastel backing.

### Dotted control enclosure

**Use:** Signature reassurance or proof motif.

**Observed:** An approximately 1180px by 600px dotted boundary surrounds a centered serif statement divided by status chips. Small outline lock and chat-like motifs interrupt the top and bottom edges.

**Transfer:** Use this enclosure for a product's genuine guardrails, configuration or verifiable benefits; preserve the interrupted-border and chip rhythm without requiring a privacy topic.

**Build:** Use a 12px-rounded rectangular SVG path with a fine rgba(0,0,0,0.35) dashed stroke and short round dashes to read as dots. Place small original outline symbols centered over the top and bottom boundary with paper backing. Clip a duplicated horizontal flex track of Status chips between the two heading lines, using 20px gaps.

### Pixel paper campaign collage

**Only for:** playful audience campaigns

**Use:** Audience opening ornament, stacked feature examples and closing surround.

**Observed:** Chunky monochrome pixel icons float around the opening text. Hard black-edged command cards, a fanned deck and offset media windows introduce red, blue and golden yellow backings. The ending combines casual library photographs, portrait social video, gradient poster art and stacked invitation slips behind the large paper panel.

**Transfer:** Use candid context imagery and original pixel symbols appropriate to the audience. Keep all images rectangular and edge-defined; the paper call remains in front.

**Build:** Draw 8px-grid black SVG silhouettes for useful objects, at roughly 60px inside 85px tiles. Fan four 240px by 300px paper cards with small diagonal offsets and 2px edges. For the close, layer three or four bordered rectangular photos of different aspect ratios behind a centered panel; add a vertical strip of four icon tiles and several offset 352px by 65px invitation slips below.

### Business atmospheric wash

**Only for:** business information pages

**Use:** Subdued product introduction.

**Observed:** A light sans heading sits above a wide, softly faded interface. Very pale lavender, blue and peach light pools occupy the perimeter, leaving the center close to white; the image fades down into paper.

**Transfer:** Keep this version less saturated and less ornamental than the default marketing stage; match the soft glow, exact stops are not essential.

**Build:** Over paper, place broad radial light pools at the top corners and lower sides using rgba(180,185,230,0.18), rgba(230,174,146,0.2) and rgba(255,230,145,0.18), blurred 60px. Mask the bottom of the product still to transparent.

### Instruction triptych

**Only for:** onboarding pages

**Use:** Three-step practical introduction.

**Observed:** Three pale gray 300px-high panels show close details: account fields, an import action between app symbols, and a cropped control in a window corner. Fine outlines and 20px radii keep them soft; captions start with inline black numerals below the images.

**Transfer:** Give each step a single zoomed action rather than a full-screen tutorial. Match image heights while allowing a wider center panel.

### Icons

**Observed:** The default header uses a simple solid black emblem in a 40px target, small 15px-wide platform symbols, a downward CTA arrow and 12px FAQ pluses. Campaigns switch to bold pixel silhouettes; reassurance graphics use delicate outlines.

**Transfer:** Keep these vocabularies distinct: solid compact utility icons for navigation, fine outline motifs for reassurance, and pixel icons only in the campaign variant.

## Section recipes

How recurring sections are built.

### First screen: Sunlit product opening

**Observed:** The entire first 900px is a yellow Sunlit stage. From back to front: blurred leaf shadows, a centered white Opening promise near the top below Floating navigation, oversized white ornamental identity lettering, a frontal product window about 1115px wide, and the Curved conversion horizon. The identity spans roughly half the page and is partially hidden behind the product; the product fills most of the lower half and extends behind the horizon. The black Primary button and small availability line are visible within the first screen. There is no separate support paragraph here. The first paper section heading falls below the opening.

**Transfer:** Use the new product's benefit sentence, an original oversized name treatment and a credible interface or output still. Preserve strong layering even without animation. Audience campaigns instead open on paper with a heavy serif, short support line, compact black button and scattered pixel symbols; business information uses a light sans promise over a pale atmospheric product scene. Onboarding starts with a practical two-line heading and instruction images, while release articles open with date, serif title and badges.

**Avoid:** Do not replace the scene with a left-aligned headline beside a small generic illustration, or move every action below the fold. Do not treat the identity artwork as an enormous ordinary body heading.

**Text style:** `opening-promise` — Exposure VAR 500 · 38.8px/1.1 · tracking -0.04em

### Indexed product demonstration

**Observed:** A centered Section heading introduces a four/eight-column split. Short Chapter title buttons sit in a sticky left index with tiny mono numbers and an active vertical rule. The right lane holds successive 760px-wide Luminous interface windows with soft shadows and 40px bottom breathing room.

**Transfer:** Use a small set of distinct work outcomes. Associate each index title with one concrete scene; keep supporting copy short enough that the index remains secondary to the imagery.

**Text style:** `chapter-title` — Exposure VAR 500 · 24px/1.25 · tracking -0.03em

### Alternating feature pairs

**Observed:** A centered Section heading leads into the Feature pair layout after an 80px pause. Each Feature card contains Feature label, Feature copy and a bottom-aligned product scene. The wide card switches sides between rows, with 20px gutters and 12px outer corners.

**Transfer:** Alternate visual emphasis according to the new content; a narrow scene may isolate one control while a wide one shows a workspace.

**Text style:** `feature-copy` — ABC Oracle 350 · 20px/1.5 · tracking -0.02em

### Statement interrupted by controls

**Observed:** The Dotted control enclosure uses 70px top and bottom padding. Two Section heading lines are separated by a clipped status-chip stream with 20px space above and below. Centered Support copy sits beneath in an approximately 676px measure, followed after 40px by the Supporting pill link.

**Transfer:** Make an abstract promise tangible through meaningful controls or proof labels; retain the dotted boundary and the interruption device.

**Text style:** `section-heading` — Exposure VAR 500 · 48px/56px · tracking -0.05em

### Closing horizon and imprint

**Observed:** A short centered Section heading question floats in open paper above a reprise of the Curved conversion horizon, Primary button and availability note. The Footer imprint follows with four link groups, separate right-side emblem, fine rule and lower maker credit.

**Transfer:** Echo the opening benefit as a short question rather than introducing a new value proposition. Preserve the curved call and compact imprint even when earlier sections change.

**Text style:** `section-heading` — Exposure VAR 500 · 48px/56px · tracking -0.05em

### Practical questions

**Observed:** An 800px-centered stack of Question rows follows product content. Information and onboarding versions use light rules and 16px sans questions; onboarding introduces the stack with Practical heading type. The campaign version uses Campaign question type, 2px rules and right-aligned pluses. All versions finish with Footer imprint.

**Transfer:** Choose the question treatment according to the surrounding page type and answer real adoption friction.

**Text style:** `body` — ABC Oracle 400 · 16px/1.5

### Campaign role and command theatre

**Only for:** playful audience campaigns

**Observed:** Heavy serif section leads sit 60px above overlapping demonstrations. A dark selected role panel contrasts with pale stacked roles and a 590px-wide interface. Another chapter pairs a 780px-wide hard-edged demo with a fanned card deck and a narrow multicolor invitation strip. Feature scenes later use offset caption boxes and 2px dark outlines.

**Transfer:** Use the role panel for different jobs or modes, and the card deck for compact reusable actions. Preserve paper layering and mono descriptions rather than importing default delicate cards.

**Text style:** `audience-display` — Exposure VAR 650 · 56px/62px · tracking -0.05em

### Campaign collage close

**Only for:** playful audience campaigns

**Observed:** After the heavy ruled FAQ, a Campaign closing panel overlaps candid photos, portrait video and pixel tiles. A stack of invitation slips projects beneath it. The shared Footer imprint ends the page rather than another oversized message.

**Transfer:** Let one high-contrast panel dominate a lively audience collage. Use genuine contextual media and one secondary community or learning invitation.

**Text style:** `audience-display` — Exposure VAR 650 · 56px/62px · tracking -0.05em

### Release ledger with signatures

**Only for:** release articles

**Observed:** A narrow left back link sits outside the main article. Date, a 615px-wide Release heading, platform/version badges and an italic Release intro lead into two 465px columns of changes, 50px apart with 51px row gaps. Each item has a title, muted description and a 'Shipped by' attribution followed by a handwritten first name. After the last items, 100px of separation leads directly to Footer imprint; there is no conversion horizon.

**Transfer:** Turn a utilitarian change list into a human-authored ledger. Use real contributor credit; do not add cards, feature imagery or marketing CTAs just to fill the space.

**Text style:** `release-heading` — Exposure VAR 400 · 44px/50px · tracking -0.05em

### Instructional first steps

**Only for:** onboarding pages

**Observed:** A Practical heading introduces a three-part Instruction triptych after 60px. Equal-height 300px illustrations lead into 18px captions with inline bold numbers and selective emphasis. FAQs follow, then Footer imprint, with no extra closing sales pitch.

**Transfer:** Organize the first successful task into a few concrete actions, with each image tightly focused on the relevant interaction.

**Text style:** `practical-heading` — ABC Oracle 300 · 54px/60px · tracking -0.04em

## Page flow

**Storyline:** Human benefit → tangible product behavior → capability detail → reassurance or adoption help → purposeful ending and maker imprint.

### Flagship product landing

1. **Promise** — Sunlit identity and product theatre with persistent conversion horizon.
2. **Product demonstration** — Sticky outcome index beside successive large interface scenes.
3. **Capability chapters** — Alternating wide and narrow transparent feature cards.
4. **Reassurance** — Dotted statement enclosure with a stream of control chips.
5. **Closing call** — Short benefit question above the curved conversion stage, then the shared imprint.

**Transfer:** Keep the theatrical opening and distinctive conversion and proof devices; adapt the chapter count and order to the product's story.

### Audience campaign

1. **Belonging** — Heavy serif reassurance with surrounding pixel icons and compact action.
2. **Concrete examples** — Context tags and short action cards layered over a browser strip.
3. **Capability chapters** — Role selector, overlapping demo, fanned command deck and offset-caption scenes.
4. **Objection handling** — Heavy ruled serif questions.
5. **Closing call** — Paper promise panel in a candid collage, invitation slips and shared imprint.

**Transfer:** Use a more playful paper-and-pixel language when addressing a particular audience, with credible context rather than generic stock imagery.

### Product release article

1. **Orientation** — Back link, date, editorial title and small badges.
2. **Summary** — Short italic release introduction.
3. **Change details** — Two-column unboxed change ledger with contributor signatures.
4. **Ending** — Last change row followed directly by shared imprint.

**Transfer:** Prioritize scannable changes and human authorship, not a conversion funnel.

### Business information

1. **Promise** — Light sans heading and one-line support over a pale atmospheric product scene.
2. **Objection handling** — Narrow, lightly ruled questions about adoption and guardrails.
3. **Ending** — Shared imprint without a separate sales close.

**Transfer:** Use the calmer sans and low-saturation variant for evaluation-oriented pages.

### Post-conversion onboarding

1. **Orientation** — Practical two-line heading with a small chromatic sweep accent.
2. **First success** — Three tightly framed instructional images and numbered captions.
3. **Objection handling** — FAQ heading and light question rows.
4. **Ending** — Shared imprint without another acquisition pitch.

**Transfer:** Help the reader achieve the next useful action; trade theatrical brand art for clear interaction details.

## Writing

Warm, direct and gently witty, with confidence grounded in recognizable daily situations. It promises less friction and a better day rather than presenting technology as an abstract revolution.

**Do not copy:** Do not reuse Dia, The Browser Company, identity artwork, proprietary product scenes, contributor names, audience-specific claims, security certifications, dates, version numbers or compatibility claims as facts for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. The product is named in the third person; we appears for candid company commitments or things still being prepared.
- **Rhythm:** Headlines are compact sentences or sentence fragments, often 4–9 words. Support lines are usually one or two sentences; feature copy gives a concrete situation and its consequence. Longer FAQ answers stay plainspoken.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Contrast the category with a human outcome, in two short clauses. | 6–10 words | “More than a browser. A better workday.” |
| Section heading | A familiar phrase turned toward the product's behavior. | 4–7 words | “[Brand] reads between the tabs”<br>“Ready for a better day?” |
| Feature explanation | Start with an ordinary problem, then describe the specific behavior that removes it. | 20–40 words | “Every call starts with the right meeting page, agenda, notes, and related docs open, with a gentle countdown so you're on time. All you have to do is show up.” |
| Audience promise | Reassure first, then allow a little playful exaggeration. | 6–10 words | “You don’t have to do it all alone.”<br>“Features so good, they feel illegal” |
| Practical support | Name the next small action with no ceremony. | 6–14 words | “Just enter your email and create a password.”<br>“We’re getting [Brand] ready for companies of all sizes.” |
| Primary action | Verb plus product or immediate outcome; qualify price only when factual. | 2–5 words | “Download [Brand] for free” |

**Words and phrasing to use:** your day; right where you work; pick up where you left off; all you have to do; one click; in control; feel right at home

**Avoid:** revolutionary ecosystem; unlock limitless potential; disrupt; supercharge everything; AI-powered synergy; enterprise jargon without an explanation

**Rules:**

- Describe the saved effort or useful output before naming the mechanism.
- Use concrete objects and verbs: notes, documents, tabs, import, ask, find, organize.
- Let practical questions sound like a person asking them; answer directly before adding qualifications.
- Keep humor concentrated in audience campaigns, not in security promises or setup instructions.
- Do not introduce unsupported statistics, customer counts or comparative claims for visual impact.

## Do's and Don'ts

### Do

- Keep the default page on #fbfaf6 after its single saturated yellow opening.
- Set editorial section leads at 48px/56px, weight 500, with -0.05em tracking.
- Preserve the broad 443px by 56px black conversion pill on the cream arc.
- Use 20px gutters and alternating 700px/460px card emphasis for the main capability grid.
- Give feature copy 30px inner padding and a light 20px/1.5 sans voice.
- Use the 12px media corner and layered soft shadow for large product windows.
- Retain the dotted proof enclosure and 35px status-chip interruption as a graphic device.
- End with 13px uppercase mono links, 0.1em tracking and a separate small maker emblem.

### Don't

- Do not turn every heading into a bold sans display; the light grotesk and expressive serif have different jobs.
- Do not apply the campaign's 2px outlines and hard offset shadow to ordinary feature cards.
- Do not spread yellow bands throughout the long page; the paper sections make the opening feel special.
- Do not replace the broad primary pill with the compact 14px-radius campaign button on a default landing page.
- Do not use equal-weight three-column icon tiles in place of the asymmetric media-led feature pairs.
- Do not make product scenes dark neon dashboards; keep their backing pale and luminous.
- Do not use violet as the main conversion color; it belongs to the small release metadata badge.
- Do not inflate footer type into ordinary 16px body links; the small tracked imprint is part of the ending.

## Motion and responsive

### Motion

**Observed:**

- Declared color transitions commonly use 0.2s cubic-bezier(0.4,0,0.2,1); footer links darken on hover.
- Declared product-window shadow transition is 0.3s cubic-bezier(0.4,0,0.2,1).
- Declared primary pill transition is transform 0.22s cubic-bezier(0.22,1,0.36,1) and box-shadow 0.42s with the same curve.
- The control strip is horizontally translated and repeated; the marketing action stays on a curved foreground while product chapters scroll.
- A chroma-sweep is declared for 0.9s ease-in-out with a 0.1s delay on the instructional heading accent.

**Transfer:**

- Keep movement tied to the recurring control strip, indexed product scenes and conversion foreground rather than animating every paragraph.
- Use the brief chromatic sweep only for a small emphasis, not continuous rainbow text.

**Unknown:**

- Exact timing and easing of the leaf-light scene, chapter switching and curved foreground progression are not established.
- No complete interaction sequence or reduced-motion behavior is established.

### Responsive

**Observed:**

- The desktop navigation is enabled at 800px; below that threshold a different header treatment is used.
- Feature cards use full-width twelve-column spans before becoming paired at 800px.
- Footer groups use a two-column grid before changing to a flex row at 800px.
- The wide context-card composition is enabled at 1200px.

**Transfer:**

- On narrow screens, stack product scenes beneath their corresponding explanations, keeping the light paper canvas and original hierarchy.
- Retain the oversized identity as a clipped background layer, but keep the benefit sentence and conversion action readable.
- Reduce the campaign collage to a smaller surround without covering the central panel.

**Unknown:**

- Exact mobile framing, type sizes and conversion-horizon behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
