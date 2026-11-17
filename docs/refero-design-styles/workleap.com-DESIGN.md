# Workleap — intelligence in flowing ribbons

## Overview

A bright, approachable software style that gives useful technology a distinctly human, editorial edge. Regular grotesk headlines mingle with expressive serif italics, while electric blue, midnight navy and soft peach-lavender waves animate an otherwise white and warm-paper canvas. Floating interface fragments supply the product story; natural workplace photography brings warmth to company-oriented material. The density is spacious at section scale and practical within cards.

### Essentials

- Headlines sound conversational but occupy a display stage: regular grotesk at 96px/1 with -0.05em tracking, stepping to 48px/1.1 with -0.02em for sections; short serif-italic phrases provide the editorial countervoice.
- The default opening is a promise suspended over flowing color: a centered 960px text measure, a two-line headline, 16px supporting copy and one blue action, with overlapping blue-lavender and peach ribbons across the lower half. Recreate the ribbons even when there is no product media.
- Actions are compact pills, not oversized blocks: 44px height, 100px resting radius, 2px borders and 11.2px 32px padding; the header uses a 38px variant with 8px 24px padding.
- Color lives in scenery and conversion moments rather than every section: white and #f9f8f6 carry most of the reading, #2545ff marks actions and small emphasis, and a dark wave-backed conversion panel plus #0c1754 footer provide concentrated blue anchors.
- Product proof feels softly lifted off the canvas: white interface fragments overlap on pale neutral backings, 24px feature-card corners, 1px #e6e6e4 edges and blue-tinted shadows. Use a simplified, legible outcome card when a full interface does not exist.
- Include an editorial reversal at display scale: a large regular statement resolves in serif italic, staged on a 1280px-wide, 16px-radius dark ribbon panel with a white pill action. Its location is flexible; its strong typographic and atmospheric contrast is part of the style.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#2545ff` | `--color-blue` | action, link, accent, background, border | Filled and outlined actions, quotation marks, progress accents and the blue side of atmospheric gradients. |
| Midnight navy | `#0c1754` | `--color-navy` | background, text, surface | Footer, dark conversion scenery and institutional display text. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue wash | `#d3daff` | `--color-blue-wash` | surface | Visible soft blue tint made with the electric blue at 20% over white; feature-card gradients fade into this family rather than becoming solid blue. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#171417` | `--color-ink` | text | Headlines and main reading text. |
| Navigation ink | `#222222` | `--color-nav-ink` | text | Navigation labels and expanded FAQ prose. |
| Secondary ink | `#484747` | `--color-body-secondary` | text | Support copy and uppercase eyebrows. |
| Input edge | `#cccccc` | `--color-input-edge` | border | Consent checkbox outline. |
| Hairline | `#e6e6e4` | `--color-rule` | border, surface | Card edges, testimonial separators, comparison tables and inactive progress tracks. |
| Soft paper | `#f9f8f6` | `--color-paper` | background, surface, text, border | Warm alternating bands and pale text on navy. |
| Cool card | `#fafafa` | `--color-card` | surface | Capability cards and explanatory panels. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default marketing canvas, floating cards and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company fact mosaics | Vermilion | `#ff5822` | `--color-orange` | surface, accent | Small proof tile and hand-drawn statistic accent. |
| company fact mosaics | Vivid statistic blue | `#2a2bff` | `--color-stat-blue` | surface | High-impact quantified-proof tile. |
| pricing pages | Recommendation yellow | `#ffc13a` | `--color-yellow` | surface, accent | Recommended-plan cap, not the ordinary action color. |
| product transition announcements | Periwinkle announcement | `#c8d0ff` | `--color-announcement` | background | Pale full-width announcement ribbon with navy text. |
| company storytelling and footer controls | Sand | `#f0e9e1` | `--color-sand` | background, surface, border | Warm institutional hero and statistic panels; minor footer-control edges. |

## Typography

- **Abcfavoritvariable** — Headlines, card titles and uppercase section labels. Open, contemporary grotesk, kept regular rather than bold; closely fitted at display sizes. OpenType features: "ss01", "ss04". If unavailable, use **DM Sans**. 400; retain tight tracking and check line breaks against the intended measure. Font stack: "Abcfavoritvariable", "DM Sans", Arial, sans-serif.
- **Inter hosted** — Body prose, navigation, actions, quotes and utility copy. Clear practical sans with a neutral reading texture. OpenType features: "ss01", "ss04". If unavailable, use **Inter**. Font stack: "Inter hosted", "Inter", sans-serif.
- **Martinaplantijn** — Short expressive italic phrases within headings. High-contrast literary serif italic with energetic entry and exit strokes. If unavailable, use **Libre Caslon Display**. Use italic styling for the sloping editorial accent; retune phrase width if needed. Font stack: "Martinaplantijn", "Libre Caslon Display", Georgia, serif.
- **Abcfavoritmono** (only for pricing recommendation labels) — Widely spaced uppercase recommendation label. Light utilitarian monospace, visibly distinct from ordinary eyebrows. If unavailable, use **IBM Plex Mono**. Use 300–400. Font stack: "Abcfavoritmono", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Abcfavoritvariable | 400 | 96px | 1 | -0.05em | size clamp(3.5rem, 2.7857rem + 3.5714vw, 6rem) | Main centered promise and monumental conversion headline. |
| display-italic | Martinaplantijn | 500 italic | 96px | 1 | -0.05em, features "ss01", "ss04" | fixed | Short concluding phrase in the monumental conversion statement. |
| heading | Abcfavoritvariable | 400 | 48px | 1.1 | -0.02em | size clamp(2rem, 1.7143rem + 1.4286vw, 3rem) | Standard section lead. |
| heading-italic | Martinaplantijn | 400 italic | 48px | 1.1 | normal, features "ss01", "ss04" | fixed | One emotionally significant phrase within a section lead. |
| subheading | Abcfavoritvariable | 400 | 40px | 1.1 | -0.02em | size clamp(1.75rem, 1.5357rem + 1.0714vw, 2.5rem) | FAQ title and medium editorial statement. |
| subheading-italic | Martinaplantijn | 400 italic | 40px | 1.1 | normal, features "ss01", "ss04" | fixed | Italic opening word or phrase within the medium editorial statement. |
| quote-mark | Abcfavoritvariable | 400 | 32px | 1.1 | -0.02em | size clamp(1.5rem, 1.3571rem + 0.7143vw, 2rem) | Small electric-blue opening quotation mark beside the quote body. |
| card-title | Abcfavoritvariable | 400 | 24px | 1.1 | -0.02em | size clamp(1.25rem, 1.1786rem + 0.3571vw, 1.5rem) | Feature names, supporting tab titles and compact card headings. |
| body | Inter hosted | 400 | 16px | 1.4 | normal | fixed | Paragraphs, navigation and practical explanation. |
| button | Inter hosted | 500 | 16px | 1.1 | normal | fixed | Main and secondary conversion actions. |
| eyebrow | Abcfavoritvariable | 400 | 14px | 1.4 | normal, uppercase | fixed | Small category line before the heading, normally secondary ink. |
| small | Inter hosted | 400 | 14px | 1.4 | normal | fixed | Testimonial text, plan details and compact feature descriptions. |
| caption | Inter hosted | 400 | 12px | 1.4 | normal | fixed | Attribution details, consent and footer utility text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company manifesto statements | company-display-italic | Martinaplantijn | 400 italic | 96px | 1 | normal, features "ss01", "ss04" | fixed | Expressive insertion in a company promise, with looser fit than the conversion-panel italic. |
| product-detail, pricing and recruitment openings | compact-hero | Abcfavoritvariable | 400 | 64px | 1 | -0.05em | size clamp(3rem, 2.7143rem + 1.4286vw, 4rem) | More compact headline when an adjacent product illustration, photograph or plan grid shares the opening. |
| product-detail and pricing openings | compact-hero-italic | Martinaplantijn | 400 italic | 64px | 1 | normal, features "ss01", "ss04" | fixed | Inline expressive phrase inside the compact hero. |
| company and recruitment storytelling | editorial-lead | Inter hosted | 400 | 20px | 1.4 | normal | fixed | Introductory prose for people-led sections. |
| pricing recommendation labels | recommendation | Abcfavoritmono | 350 | 14px | 1.4 | 0.171em, uppercase, features "ss01", "ss04" | fixed | Small label centered in the yellow recommended-plan cap. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The grotesk is regular throughout the headline hierarchy. Tighten from -0.02em at 24–48px to -0.05em at 64–96px; do not manufacture emphasis by adding bold weight.
- Serif accents are genuine family changes, not an italic version of the sans. Standard inline serif phrases use normal tracking; the closing display variant alone carries the tightly tracked 500-weight treatment.
- Keep body copy much smaller than the promise. A 96px display over 16px support is intentional, while people-led editorial introductions step up to 20px.
- Balance headline lines by meaning and reserve the serif for a short phrase; do not italicize every title.

## Layout

**Density:** Airy between narrative blocks, with compact, practical copy inside cards and generous space around product scenes.

### Spacing

**Spacing system:**

- **grid** 8px — Primary layout rhythm; 16px, 24px, 32px, 40px, 48px, 64px and 80px form the main scale. Fine control uses 4px or 12px where needed.

| Value | Use |
| --- | --- |
| 8px | Small icon-label and control gaps. |
| 16px | Eyebrow to heading, heading to prose, action-pair gaps and compact grid spacing. |
| 24px | Default card-grid gutters and narrative group spacing. |
| 32px | Testimonial padding and horizontal pricing-card padding. |
| 40px | Hero prose-to-action separation and spacious editorial-card padding. |
| 48px | Split-section gutters and heading-to-large-media separation. |
| 64px | Large panel padding or introductory-copy-to-portrait-grid separation. |
| 80px | Default section top and bottom breathing room and footer padding. |
| 96px | Vertical padding within the large conversion panel. |
| 128px | Default opening text inset beneath navigation and the warm integration-band top space. |

### Containers and grids

- **container**: max width 1280px · side padding 40px. Centered principal content width. At a 1440px desktop window it leaves 80px visible side margins; the outer wrapper has 40px minimum side padding.
- **hero measure**: max width 960px. Centered headline and support region; the text composition spans roughly two thirds of the desktop width.
- **editorial measure**: max width 896px. Centered statements and conversion-panel headline.
- **three-column grid**: 3 columns · gap 24px. Equal 411px feature, quote and editorial cards; a lead capability tile can span two columns.
- **split feature**: 2 columns · gap 48px. 616px product scene against a similar-width text column. Alternate the image side between capability chapters.
- **footer grid**: 5 columns · gap 32px. One broad brand-and-newsletter column followed by four narrow link columns; the proportional construction is 2.5fr 1fr 1fr 1fr 1fr.
- **portrait grid** (only for company team sections): 4 columns · gap 16px. Square 304px portraits arranged in two rows.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 100px |
|  | capability cards | 24px |
|  | editorial cards and conversion panel | 16px |
|  | logo bubbles | 50% |
|  | consent checkbox | 2px |
| product onboarding and recruitment listings | explanatory inset panel | 40px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| capability lift | `0px 4px 8px 0px rgba(37, 69, 255, 0.1)` | Subtle blue-tinted lift beneath pale capability cards. |
| editorial lift | `0px 4px 8px 0px rgba(37, 69, 255, 0.1), 0px 12px 24px 0px rgba(37, 58, 177, 0.05), 0px 32px 40px 0px rgba(37, 58, 177, 0.05)` | White editorial cards and pricing panels. |
| logo bubble | `0px 4px 16px 0px rgba(0, 0, 0, 0.1)` | Floating integration discs. |

### Surfaces

#### White canvas · level 0

**Use:** Default reading field.

**CSS:** `background: #ffffff; color: #171417`

#### Soft paper band · level 0

**Use:** Warm pause around integration and editorial content.

**CSS:** `background: #f9f8f6`

**Observed:** A full-width band, not a small beige box around each paragraph.

**Transfer:** Use it to change narrative pace without adding a dark section.

#### Capability shell · level 1

**Use:** Product-capability tiles.

**CSS:** `background: linear-gradient(135deg, rgba(0, 0, 0, 0) 66%, rgba(37, 69, 255, 0.2)), #fafafa; border: 1px solid #e6e6e4; border-radius: 24px; box-shadow: 0px 4px 8px 0px rgba(37, 69, 255, 0.1); overflow: hidden`

**Observed:** Almost neutral above and left; a faint blue glow concentrates at the bottom-right, behind the product fragment.

**Transfer:** Keep the blue corner subordinate to the feature title.

#### Dark ribbon panel · level 0

**Use:** High-contrast conversion moment.

**CSS:** `background: linear-gradient(120deg, #2545ff, #0c1754 60%); border-radius: 16px; color: #ffffff; padding: 96px 64px`

**Observed:** The base is covered by grainy blue-to-navy scenery and layered waves along the lower edge; use the Flowing ribbons construction.

**Transfer:** Preserve the dark center behind the headline and keep wave highlights below the text.

#### Navy footer · level 0

**Use:** Final site-wide utility field.

**CSS:** `background: #0c1754; color: #f9f8f6; padding: 80px 0px`

**Observed:** Full bleed with no rounded outer corners.

**Transfer:** End with a solid color field rather than another pale card.

#### Editorial card · level 1

**Only for:** company storytelling and pricing

**Use:** Raised narrative cards.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: 0px 4px 8px 0px rgba(37, 69, 255, 0.1), 0px 12px 24px 0px rgba(37, 58, 177, 0.05), 0px 32px 40px 0px rgba(37, 58, 177, 0.05)`

**Observed:** The lift is broad and low-contrast, never a hard black drop shadow.

**Transfer:** Raise the foreground card above a pale atmospheric band.

#### Pricing atmosphere · level 0

**Only for:** pricing pages

**Use:** Plan-selection opening.

**CSS:** `background: linear-gradient(98deg, #0c1754 -6.06%, #2545ff 94.39%); color: #ffffff`

**Observed:** A broad blurred periwinkle light streak crosses the blue field behind white plan cards.

**Transfer:** Add the soft light treatment described in Atmospheric glow; do not turn the entire site into a blue theme.

#### Inset explainer · level 1

**Only for:** product onboarding and recruitment listings

**Use:** A self-contained process or list panel within a larger opening.

**CSS:** `background: #fafafa; border-radius: 40px; padding: 64px 48px`

**Observed:** Large, calm corners distinguish this panel from the 24px feature cards. Recruitment uses a white version.

**Transfer:** Reserve it for a substantial grouped explanation rather than every feature.

## Components

### Navigation

**Use:** Persistent site navigation above the narrative.

**CSS:** `background: #ffffff; border-bottom: 1px solid rgba(230, 230, 228, 0.42); height: 60px; padding: 0px 72px; display: flex; align-items: center; position: sticky`

**Text style:** `body` — Inter hosted 400 · 16px/1.4

**Observed:** Brand at left, five compact navigation choices in the middle-left, then login, outlined chat and filled demo actions at right. Menu items have 18px 16px padding and 14px chevrons. A 44px navy announcement strip can sit above. Company storytelling uses paper backing; pricing reverses the navigation over blue.

**States:** Declared: hover navigation text becomes #2545ff; focus-visible navigation can receive layered pale-blue rings; active text becomes a deeper blue.

**Transfer:** Keep this bar slim relative to the hero and preserve the hierarchy of text link, outline action and filled action.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #2545ff; color: #ffffff; border: 2px solid #2545ff; border-radius: 100px; padding: 11.2px 32px; height: 44px; box-sizing: border-box`

**Text style:** `button` — Inter hosted 500 · 16px/1.1

**Observed:** Centered text with no compulsory arrow. The compact navigation variant uses 8px 24px padding and a 38px height.

**States:** Declared: hover changes border-radius to 8px and sets outline to 0px; focus-visible styling is not established for this button; active sets outline to 0px.

### Secondary button

**Use:** Supporting action beside the primary action or a targeted feature exploration.

**CSS:** `background: transparent; color: #2545ff; border: 2px solid #2545ff; border-radius: 100px; padding: 11.2px 32px; height: 44px; box-sizing: border-box`

**Text style:** `button` — Inter hosted 500 · 16px/1.1

**Observed:** Same construction as Primary button with the fill removed; its width grows with the label.

**States:** Declared: hover changes border-radius to 8px and sets outline to 0px; focus-visible is not established; active sets outline to 0px.

### Reversed button

**Use:** Conversion on dark scenery.

**CSS:** `background: #ffffff; color: #2545ff; border: 2px solid #ffffff; border-radius: 100px; padding: 11.2px 32px; height: 44px; box-sizing: border-box`

**Text style:** `button` — Inter hosted 500 · 16px/1.1

**Observed:** One white action under the large closing statement; on pricing it pairs with a transparent white-outline comparison action.

### Capability tile

**Use:** A compact, illustrated product benefit.

**CSS:** `background: linear-gradient(135deg, rgba(0, 0, 0, 0) 66%, rgba(37, 69, 255, 0.2)), #fafafa; border: 1px solid #e6e6e4; border-radius: 24px; box-shadow: 0px 4px 8px 0px rgba(37, 69, 255, 0.1); overflow: hidden; display: flex; flex-direction: column; gap: 8px`

**Text style:** `card-title` — Abcfavoritvariable 400 · 24px/1.1 · tracking -0.02em

**Observed:** A line icon sits beside a regular title, supported by concise secondary-ink copy. The leading double-width card puts text at upper-left and a large interface fragment at lower-right; smaller cards stack art above text. Other tiles can be shallow text-led rows.

**States:** Declared: hovering the parent can turn the linked title #2545ff.

**Transfer:** Use one clear outcome per tile; vary tile span to create hierarchy, not a dashboard of identical boxes.

### Media tabs

**Use:** Three explanatory captions beneath one wide product scene.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(200px, 1fr)); gap: 16px`

**Text style:** `card-title` — Abcfavoritvariable 400 · 24px/1.1 · tracking -0.02em

**Observed:** Each caption has a 4px pill-ended hairline at top, a centered icon-title row and body copy. The active track is blue; inactive tracks are the neutral rule color. The scene above is 1280px by 400px.

**Transfer:** Let the tabs describe three distinct perspectives on the same scene rather than repeat the feature grid.

### Testimonial column

**Use:** Human proof without heavy card chrome.

**CSS:** `padding: 32px; border-left: 1px solid #e6e6e4`

**Text style:** `small` — Inter hosted 400 · 14px/1.4

**Observed:** Three columns, each with monochrome customer mark at top, a small blue opening quotation mark, compact quote, then bold small name and lighter role. Omit the leading separator on the first column. Round arrow and pause controls align at the lower right. Pricing switches to 302px-wide white rounded cards with faint yellow, blue or coral corner glow.

**Transfer:** Keep real quote text compact enough to retain generous space between the logo and attribution.

### FAQ row

**Use:** Low-chrome objection handling.

**CSS:** `padding: 24px; border-radius: 16px`

**Text style:** `body` — Inter hosted 400 · 16px/1.4

**Observed:** Question and small downward chevron share a horizontal row; an inner 1px bottom rule continues the reading rhythm. The question has 24px vertical space. Expanded answers use 16px/1.6 secondary reading ink. Default appearance is collapsed; recruitment also shows an expanded-answer variant.

**Transfer:** Group questions in a calm text list beside an editorial heading, not in filled accordion boxes.

### Newsletter form

**Use:** Subscription in the footer's broad left column.

**CSS:** `display: flex; flex-direction: column; gap: 16px`

**Text style:** `body` — Inter hosted 400 · 16px/1.4

**Observed:** A 24px display-family invitation sits above an underlined 310px by 38px email field and an outlined Subscribe pill. Consent follows with an 18px checkbox, 1px gray edge and 12px copy. No large input rectangle or filled submit block.

**Transfer:** Keep the input and subscription action on one line when space allows, with consent on its own line.

### Footer

**Use:** Shared site ending.

**CSS:** `background: #0c1754; color: #f9f8f6; padding: 80px 0px`

**Text style:** `body` — Inter hosted 400 · 16px/1.4

**Observed:** Broad logo/newsletter/trust area on the left and four narrow grouped-link columns on the right. Category labels are uppercase regular sans at 16px. A faint full-width divider separates the lower row: circular social marks left, copyright center, trust and language controls right. The footer is about 760px tall at desktop.

**Transfer:** Retain the strong solid-navy finish, practical multi-column density and roomy left brand column.

### Plan card

**Only for:** pricing pages

**Use:** Commercial choices within the blue opening.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 24px 32px; box-shadow: 0px 4px 8px 0px rgba(37, 69, 255, 0.1), 0px 12px 24px 0px rgba(37, 58, 177, 0.05), 0px 32px 40px 0px rgba(37, 58, 177, 0.05); display: flex; flex-direction: column`

**Text style:** `card-title` — Abcfavoritvariable 400 · 24px/1.1 · tracking -0.02em

**Observed:** Three equal columns. Plan name leads, then compact checked inclusions, a thin divider and additional-capabilities disclosure, with price and action at the base. The recommended center card has a 36px yellow cap with Recommendation text and squared upper body corners. The recommended action is filled blue; alternatives are outlined.

**Transfer:** Align the bases and commercial details; recommendation should change the cap and action hierarchy rather than enlarge the entire middle card.

### Editorial value card

**Only for:** company and recruitment storytelling

**Use:** Short principles or differentiators.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 40px; box-shadow: 0px 4px 8px 0px rgba(37, 69, 255, 0.1), 0px 12px 24px 0px rgba(37, 58, 177, 0.05), 0px 32px 40px 0px rgba(37, 58, 177, 0.05)`

**Text style:** `card-title` — Abcfavoritvariable 400 · 24px/1.1 · tracking -0.02em

**Observed:** Regular title, 16px gap and paragraph. Five cards fill a three-column grid whose first cell is an unboxed section heading, all above a bottom-heavy blue-purple atmospheric wash.

**Transfer:** Use this offset-grid device for a genuinely editorial argument; preserve the unboxed title cell.

## Imagery and graphics

### Flowing ribbons

**Use:** Signature atmosphere in the opening and dark conversion scene.

**Observed:** Broad translucent fabric-like curves overlap across the lower half of a white opening: cool blue and lavender sweep from the left, warm peach-coral rises toward the right. The lower edges dissolve into pale light, with very fine grain rather than shiny plastic. The dark version shifts to deep navy, cobalt and muted mauve with a pale lavender crest.

**Transfer:** Recreate this flowing landscape for any product. A small set of carefully shaped SVG waves is the minimum acceptable version; a generic radial blob is not equivalent.

**Build:** Use a full-width SVG with a 1440 by 900 viewBox. Draw three to five closed cubic-Bezier bands whose upper edges dip near the center and rise at the right edge; put the broadest crests in the lower 400px. Layer white-to-transparent electric-blue gradients with blue alpha from 0.1 to 0.65, then a peach band using orange at 0.12–0.35 alpha. Offset duplicate bands by 24–80px to form thin overlapping folds. Fade the bottom to white with a mask, soften selected lower layers with 24px blur and add monochrome turbulence noise at very low opacity. For the dark panel, change the base to navy, remove the white fade, keep one pale crest at low opacity and move the brightest cobalt light toward the upper-left.

### Floating interface scenes

**Use:** Primary product explanation in capability tiles and full-width demonstrations.

**Observed:** White rounded interface fragments overlap at different heights, with pale lavender edges, small portraits, blue signals and hairline charts. Dotted orbit arcs and little integration symbols can surround them. Most scenes are clean, front-facing or very slightly tilted, without laptop or phone hardware. The wide settings scene is clipped into a pale, grainy 1280px by 400px backing.

**Transfer:** Select a readable outcome and two supporting fragments from the new product. If no interface exists, compose a truthful status card, compact list and one action-state fragment; leave enough quiet space that the surrounding headline still leads.

### Atmospheric glow

**Use:** Soft staging behind large product scenes; a stronger variant supports editorial cards and pricing.

**Observed:** Diffuse cobalt, lavender and faint warm light spread near the lower edge of pale sections. The center behind text remains clean. Pricing uses a much broader periwinkle sweep over blue; editorial cards sit in front of a blue-purple cloud.

**Transfer:** Match the soft glow rather than exact color stops. Keep product sections mostly white; use the fuller glow only for grouped editorial or commercial panels.

**Build:** Position two oversized elliptical gradient layers behind the content, electric blue at 0.2–0.55 alpha on the lower-left and orange at 0.08–0.2 alpha toward the right. Blur by 50px, let their edges extend outside the section, and mask the top to transparent. On blue pricing backgrounds, add a broad white ellipse at 0.25 alpha slanting upward from lower-left to upper-right. Add a faint noise overlay to prevent a flat vector feel.

### Integration constellation

**Use:** Visual counterweight to a warm-paper integration statement.

**Observed:** Unequal white circular logo discs occupy the left half, with neutral soft shadows. Discs vary from small, faint peripheral marks to prominent roughly 100px circles; the right half holds eyebrow, heading, support and outline action.

**Transfer:** Use actual compatible-service symbols or abstract neutral connectors. The varying sizes and opacity should make an airy constellation, not a row of partner badges.

**Build:** Place 8–12 white discs on a loose oval path in the left column. Use diameters from 24px to 107px, with larger discs close to the visual center and much lower opacity at the perimeter. Apply the Logo bubble shadow and retain ample paper-colored negative space.

### Blue-backed feature demonstration

**Only for:** product-detail chapters

**Use:** A stronger demonstration treatment for alternating split sections.

**Observed:** A 616px square rounded blue-to-navy backdrop holds layered white survey, feedback or report fragments, some extending toward the frame edge. Orange hand-drawn arrows connect steps; blue actions and occasional small circular avatars keep the human scale. Text takes the opposite half of the section.

**Transfer:** Keep the backing saturated but the demonstration itself light; visualize one cause-and-effect story instead of shrinking a whole application into the square.

**Build:** Create a 616px square with 24px corners and a navy-to-electric-blue diagonal gradient. Overlay two or three white cards with 16px corners and soft blue lift. Connect them with one thin orange SVG curve and open arrowhead. Use only the information needed to explain the outcome.

### People photography

**Only for:** company and recruitment storytelling

**Use:** Human context, leadership and workplace culture.

**Observed:** Natural daylight, warm timber, plants and real working spaces, with people doing ordinary work rather than posing around a stock meeting table. Recruitment uses 640px by 480px and 600px square images with softened corners. Team portraits are tight waist-up studio photographs on consistent light gray backings, arranged in a four-column square grid.

**Transfer:** Choose candid work scenes with warm natural materials; use consistent lighting and scale across formal portraits.

### Wave lattice and shaped photography

**Only for:** company storytelling

**Use:** More graphic institutional identity beside manifesto copy and audience proof.

**Observed:** A repeated bent-ribbon lattice fills the right side of a sand-colored opening, colored from vivid blue through purple to orange. A later workplace image is cut into related sweeping strips, with customer marks around it rather than a rectangular photo frame.

**Transfer:** Derive a small repeated curve module from the ribbon language; apply it as either colored geometry or a photograph mask, never as a new ornamental logo.

**Build:** Define one S-curved strip as an SVG path with opposing concave corners. Repeat it in staggered rows and columns with shared edges, then apply a single blue-to-orange gradient across the whole group. For the photo variant, use the same paths as a clipPath over one continuous image.

### Stat mosaic

**Only for:** company fact sections

**Use:** Unusually expressive quantified proof.

**Observed:** Three 416px columns with 16px gaps mix stacked vivid-blue and navy numerical tiles, a tall sand tile with a very large central number encircled by an orange hand-drawn oval, and an informal founder photograph above a short orange tile. Small explanatory prose and a serif-italic name caption keep the facts editorial.

**Transfer:** Use a few verifiable measures with different hierarchy; preserve the contrast of solid color, warm neutral and human image instead of using identical metric cards.

**Build:** Use a three-column grid with 16px gutters and 16px tile radii. Give the first column two stacked color panels, the second one tall sand panel and the third a portrait with a shallow orange panel underneath. Draw a loose 1–2px orange SVG ellipse around the central metric, slightly rotated and with an open or irregular ending.

### Icons

**Observed:** Small black outline feature symbols, commonly 24px with round-ended 1.5px strokes; blue checked circles introduce benefit bullets. Navigation chevrons are about 14px with 1.8px round strokes. Carousel controls sit in 40px pale circles with blue marks and a soft lift. Social marks are simple reversed line circles.

**Transfer:** Choose an internally consistent outline set for marketing features, keep marks near text scale, and reserve richer multicolor symbols for integrations and product imagery.

## Section recipes

How recurring sections are built.

### First screen: Ribbon promise opening

**Observed:** A 44px announcement ribbon and 60px white Navigation leave the rest of the first screen to a centered promise on white. Within the 900px-high hero, the eyebrow starts after 128px of top space, followed by a 96px two-line Display headline in a 960px measure, about two thirds of the desktop width. Support follows after 16px and occupies two short 16px lines; the Primary button sits 40px below. Layers run white canvas, broad lower-half Flowing ribbons, faint grain, then crisp text and action. The headline, support, action and ribbon scene all appear within the first 900px of the page; the compact customer-proof line starts just below that first viewport, and capability cards are farther down. There is no dashboard or device dominating the opening.

**Transfer:** Use a plain, audience-specific promise of similar line density and retain the ribbon landscape even without product art. Product-detail openings instead use Compact hero on the left with Floating interface scenes on the right and logos below; pricing centers Compact hero above white Plan cards on Pricing atmosphere. Recruitment opens in a balanced text/photo split; company storytelling uses a sand field with an oversized mixed-family statement and a graphic lattice.

**Avoid:** Do not replace the lower ribbon landscape with a generic gradient blob, insert a large laptop under the headline, or fill the first screen with feature cards.

**Text style:** `display` — Abcfavoritvariable 400 · 96px/1 · tracking -0.05em

### Eyebrow and heading pair

**Observed:** Eyebrow above Heading with a 16px gap, followed by body support where useful. Left-aligned section leads share a row with a right-aligned Primary button; centered statements use an 896px measure. A short Heading italic phrase completes selected claims.

**Transfer:** Label the chapter plainly and let the headline carry the human benefit; use the italic to turn or resolve the thought.

**Text style:** `heading` — Abcfavoritvariable 400 · 48px/1.1 · tracking -0.02em

### Capability bento

**Observed:** Three-column grid with 24px gutters, Capability shell and Capability tile. The leading tile spans two columns and pairs copy with a large clipped interface fragment; supporting tiles carry smaller scenes or shallow text-led variants. The section begins and ends with about 80px breathing room.

**Transfer:** Select different tile spans according to benefit importance rather than forcing all features into the same visual weight.

### Wide demonstration with media tabs

**Observed:** A section heading and support share the top with a two-action group. After 48px comes a 1280px by 400px Floating interface scene. Media tabs sit directly underneath in three equal columns with 16px gutters.

**Transfer:** Make the demonstration explain a system-level promise, then use the captions to unpack its three most useful controls or outcomes.

### Warm integration pause

**Observed:** Soft paper band around a two-column composition, Integration constellation left and heading/support/action right. The right content begins with 128px top space; its heading ends in Heading italic.

**Transfer:** Use the constellation to communicate connection and compatibility without turning the band into a technical compatibility table.

### Editorial proof row

**Observed:** A large left-aligned claim followed by a short serif-italic reversal introduces three Testimonial columns separated by hairlines. Logos stay monochrome and quote bodies use Small text. Controls are grouped at lower-right. Pricing uses the rounded, corner-glow card variant with horizontal overflow on paper.

**Transfer:** Let the introduction state the problem or change, then let compact real voices provide proof.

### Monumental conversion

**Observed:** After 80px outer spacing, Dark ribbon panel fills the 1280px container and is about 476px tall. Display and Display italic form a centered two-line resolution within an 896px measure. One Reversed button sits 40px below, above the low ribbon crests.

**Transfer:** End an argument with a decisive sentence and one action. Keep this signature device somewhere in the experience without forcing every page type into the same section sequence.

**Text style:** `display` — Abcfavoritvariable 400 · 96px/1 · tracking -0.05em

### Site ending

**Observed:** Footer supplies the final 760px navy band with 80px vertical padding. Navigation groups are denser than the preceding sections, but the brand/newsletter column stays spacious. Product marketing and pricing arrive from the Monumental conversion panel; the product-detail variant has FAQ content between conversion and footer. Recruitment moves from a centered FAQ list directly to this band; company storytelling arrives from its three choice cards.

**Transfer:** Preserve a decisive shift into solid navy and retain subscription, grouped navigation and a separate bottom utility row.

### Alternating feature chapter

**Only for:** product-detail pages

**Observed:** A 1280px container divides into two 616px columns with a 48px gap and 80px top/bottom space. A Blue-backed feature demonstration occupies one side, while a 48px Heading, body explanation, checked benefit lines and action occupy the other. Following chapters reverse the image side; a lighter celebratory card illustration breaks the rhythm.

**Transfer:** Use a series of distinct outcomes, keeping each text block shorter than its image panel rather than repeating the same generic benefit.

### Offset editorial grid

**Only for:** company and recruitment storytelling

**Observed:** The first cell in a three-column, 24px-gutter grid is unboxed eyebrow and mixed-family heading. Five Editorial value cards occupy the remaining cells. Atmospheric glow builds at the bottom beneath the cards rather than behind the heading.

**Transfer:** Use for principles, differentiators or an editorial framework; the unboxed title provides the asymmetry.

### Company fact and story sequence

**Only for:** company storytelling

**Observed:** A centered 48px statement introduces Stat mosaic. A navy manifesto band then uses a 96px mixed-family statement. A centered story heading and 20px introduction lead into 800px white story cards with a square photo at left and text at right, horizontally extending beyond the central frame. Later content includes a shaped audience photo and the Portrait grid.

**Transfer:** Alternate concise facts, a bold belief and human stories; only use metrics and photographs that support the new organization's argument.

### Pricing comparison

**Only for:** pricing pages

**Observed:** Below the blue plan opening, a white comparison area uses a 48px heading and sticky condensed plan summaries. Feature names take half the 1280px width; three equal plan columns share the other half. Roughly 53px rows use hairline borders, 14px text, blue circled checks and muted crosses, organized by 20px group labels.

**Transfer:** Keep wide tables visually light and group features into meaningful decisions; preserve the same plan order from the opening.

### FAQ and alternate company close

**Only for:** product-detail and company pages

**Observed:** Two equal columns with a 48px gutter: Eyebrow and a 40px heading with Subheading italic at left, FAQ rows at right. Company storytelling follows with three 411px by 450px choice cards: navy/blue abstract exploration, a warm magenta ribbon demo card with centered white action, and a sand-colored recruiting invitation with faint outline art. Corners are 16px and gutters 24px.

**Transfer:** Resolve objections near the end, then offer multiple destinations only when the page genuinely serves distinct visitor intents.

## Page flow

**Storyline:** Clear promise → tangible product or human demonstration → useful capability or belief chapters → evidence and reassurance → decisive action → substantial utility ending.

### Introduce a broad product and make it feel useful immediately

1. **Promise** — Centered oversized headline over the ribbon landscape.
2. **Capability overview** — Asymmetric illustrated capability tiles.
3. **Product demonstration** — Wide interface scene with three explanatory media tabs.
4. **Compatibility** — Warm-paper integration constellation and compact explanation.
5. **Social proof** — Editorial reversal followed by three lightly divided testimonials.
6. **Closing call** — Dark ribbon panel, monumental mixed-family statement and white action.
7. **Utility ending** — Navy multi-column footer with newsletter and lower utility rail.

**Transfer:** Begin with one clear benefit, expand through increasingly concrete proof, and use the wave-backed statement as a high-contrast conversion moment.

### Help a buyer choose and compare commercial tiers

1. **Commercial promise** — Blue atmospheric opening with centered compact headline and paired actions.
2. **Pricing** — Three white plan cards, recommended yellow cap and aligned price bases.
3. **Detailed comparison** — White hairline feature matrix with sticky plan summaries and grouped rows.
4. **Social proof** — Rounded testimonial carousel on warm paper with colored corner glow.
5. **Closing call** — Monumental dark ribbon panel.
6. **Utility ending** — Small billing qualification then shared navy footer.

**Transfer:** Keep the full blue opening scoped to purchase decisions and make detailed comparisons lighter than the plan cards.

### Explain a focused product capability and remove adoption doubts

1. **Problem and promise** — Left compact mixed-family headline beside floating signal cards, then a three-step inset explainer.
2. **Capability chapters** — Alternating text and blue-backed demonstrations, followed by a lighter celebratory illustration.
3. **Compatibility** — Warm integration band.
4. **Social proof** — Large editorial statement and three quotation columns.
5. **Related capabilities** — Three illustrated capability tiles with carousel controls.
6. **Closing call** — Monumental ribbon panel.
7. **Objection handling** — Split FAQ section.
8. **Utility ending** — Shared navy footer.

**Transfer:** Build the narrative around a problem, a clear process and visible outcomes rather than making every chapter another feature list.

### Invite candidates and substantiate the working experience

1. **Invitation** — Compact text and natural workplace photograph split, with small recognition marks below.
2. **Opportunity discovery** — Large rounded inset listing grouped roles with counts and an application link.
3. **Practical proof** — Warm workplace image beside a long checked benefits list.
4. **Principles** — Offset editorial-card grid on a lower-edge atmospheric wash.
5. **Objection handling** — Centered, low-chrome FAQ with expanded answer variant.
6. **Utility ending** — Shared navy footer without the product conversion panel.

**Transfer:** Lead with people and specific working conditions; keep recruitment graphic treatments scoped rather than replacing the ordinary product opening.

### Explain an organization through beliefs, facts and people

1. **Belief** — Sand opening with navy mixed-family statement and blue-to-orange ribbon lattice.
2. **Quantified proof** — Centered explanation and asymmetric solid-color stat mosaic.
3. **Manifesto** — Short navy band with a monumental mixed-family statement.
4. **Origin story** — Photographic horizontal story cards above a soft glow.
5. **Audience and differentiation** — Shaped workplace photography, compact role labels and three raised editorial cards.
6. **Human credibility** — Four-column portrait grid.
7. **Principles and social scale** — Centered editorial proof statement and offset value-card grid.
8. **Objection handling** — Split FAQ.
9. **Next destinations** — Three illustrated choice cards.
10. **Utility ending** — Shared navy footer.

**Transfer:** Use the institutional palette and fact mosaic to support genuine company storytelling; do not impose this long narrative on an ordinary product landing page.

## Writing

Warm, direct and operationally confident. The copy makes technology feel helpful by naming everyday friction and showing the next useful action, with occasional conversational wit.

**Do not copy:** Do not reuse Workleap or Officevibe names, logos, ribbon artwork files, customer marks, testimonials, proprietary claims, statistics, pricing, awards or employment promises. Source quotations below illustrate voice only; write truthful equivalents for the new product.

- **Addressing the reader:** Speak to the reader as you or your; use we for the organization and name the product when a concrete capability is the subject.
- **Rhythm:** Headlines are short conversational claims, often split across two lines, with a brief italic resolution. Support uses practical one- or two-sentence paragraphs; feature descriptions prefer active verbs, while a short fragment can land a point.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the tool's useful job and its audience, or expose the everyday problem. | 7–12 words | “The AI agent that works for managers”<br>“You can't fix issues if you're not paying attention” |
| Section headline | Make an everyday benefit concrete; contractions and plain language keep it human. | 4–11 words | “Built for managers, led by HR”<br>“We play nice with the tools you love” |
| Feature support | Start with an active verb and describe a specific practical outcome. | 12–25 words | “Show managers what needs attention, where to focus, and what steps to take.”<br>“Pulls together the whole year, drafts the review in your voice, and preps the conversation.” |
| Primary action | A short verb-led invitation with low ceremony. | 2–4 words | “Book a demo”<br>“Let’s chat”<br>“Explore surveys” |
| Closing statement | Challenge the unsatisfactory status quo, then resolve the thought in a short editorial phrase. | 5–10 words | “Stop leaving leadership to luck.”<br>“Good management today runs on luck. It shouldn't.” |
| People invitation | Use a familiar phrase with a small verbal turn, then make the invitation personal. | 4–8 words | “Let’s get to work, together”<br>“We walk the talk” |

**Words and phrasing to use:** clear direction; real context; out of the box; where to focus; takes the prep off your plate; we play nice; let’s; simple; act; make; better

**Avoid:** synergistic; revolutionary ecosystem; unparalleled; disruptive excellence; autonomous magic; dense technical noun stacks

**Rules:**

- Say what the product does before explaining the underlying technology.
- Pair a broad promise with concrete tasks or decisions in the next block.
- Use contractions naturally; avoid ceremonial corporate language.
- Let an italic phrase supply the emotional turn without adding an exclamation mark.
- Keep action labels stable through the page; reserve exploration verbs for secondary destinations.
- Use proof in attributed voices and verifiable facts, not unsupported superlatives.

## Do's and Don'ts

### Do

- Keep primary display type at 400 weight with -0.05em tracking and a 1 line height.
- Give ordinary section headings the 48px/1.1 recipe rather than making every section monumental.
- Stage the page on a centered 1280px container with 24px card gutters.
- Use 80px section breathing room to separate scenes rather than adding ornamental dividers.
- Concentrate the feature-card blue glow in the lower-right corner above a nearly neutral fill.
- Keep primary actions 44px high and use the compact 38px version in navigation.
- Preserve a high-contrast ribbon-backed statement with a white conversion pill.
- Use the solid navy footer with a broad newsletter column and four narrow link columns.

### Don't

- Do not make every headline bold; the regular grotesk and tightly fitted letters carry the scale.
- Do not replace serif accent phrases with a slanted sans or a handwriting font.
- Do not turn every pale card into glassmorphism; the feature shells are opaque and lightly outlined.
- Do not use black, sharply offset shadows on the interface scenes; use soft blue-tinted lift.
- Do not make orange the ordinary CTA fill; blue owns actions and orange belongs to scoped art and proof.
- Do not use the yellow recommendation cap as a generic eyebrow or badge across the page.
- Do not put every image in a laptop mockup; front-facing floating fragments are the normal product treatment.
- Do not give the footer rounded outer corners or a light neutral fill.
- Do not expand the slim 60px navigation into a tall app-style toolbar.

## Motion and responsive

### Motion

**Observed:**

- Buttons and capability surfaces declare 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94) transitions; button hover changes the resting pill to an 8px radius.
- Many actions and raised surfaces declare 0.3s cubic-bezier(0.215, 0.61, 0.355, 1).
- The blue tab-progress layer declares opacity 0.3s and width 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94).
- Carousel controls include previous, pause and next; the integration constellation uses varying scale and opacity.

**Transfer:**

- Preserve the distinctive pill-to-soft-rectangle hover transformation rather than substituting a bounce.
- Use the declared progress-layer transition when changing the wide demonstration's selected caption.
- Keep the signature ribbon scene effective as a static composition; do not depend on motion to make it readable.

**Unknown:**

- Ribbon animation trajectory and timing, carousel autoplay timing and integration-orbit timing are not established.
- Button-specific focus-visible appearance is not established; define an accessible treatment without treating outline removal as the complete focus design.

### Responsive

**Observed:**

- Styles declare width breakpoints at 376px, 479px, 640px, 767px, 768px, 991px, 992px, 1136px, 1200px, 1280px, 1440px and 1920px.
- Display and heading sizes use the clamp formulas supplied with their recipes; the root type also varies with viewport width.

**Transfer:**

- On narrow screens, retain the ribbon sweep as the opening's lower backdrop and allow headline lines to reflow without shrinking the action below its compact form.
- Stack split text/media chapters and reduce multi-column card groups while preserving readable interface fragments; treat this as adaptation guidance rather than a prescribed breakpoint behavior.
- Keep the newsletter consent below its field/action group, and reflow footer groups rather than squeezing four narrow columns into phone width.

**Unknown:**

- Exact mobile layouts, menu expansion, card-carousel replacement behavior and breakpoint-specific padding are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
