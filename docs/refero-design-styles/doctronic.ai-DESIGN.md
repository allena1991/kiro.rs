# Doctronic — a human conversation

## Overview

A light, reassuring style that makes a technical service feel like an approachable person. Warm ivory, pale sage and restrained electric blue surround soft editorial serif headlines and tightly set grotesk text. Natural portraits, conversational input panels and a luminous green fabric-like flourish balance practical information with human warmth; the overall page is airy while individual controls and resource lists stay compact.

### Essentials

- The product introduces itself like a person, not a billboard: centered Fraunces at 48px/1.17, weight 400 and -0.01em tracking above a 548px-wide working input panel.
- Small, tactile conversion controls punctuate an almost entirely pale page: blue actions are 44px tall with 52px corners, 12px 24px padding and a blue-tinted 4px 7px shadow; account actions remain small and black.
- Color follows a conversation hierarchy: ivory #fdfdf7 dominates, sage #e1efe3 washes broad sections, blue #2463eb marks actions and selected phrases, and translucent lime speech labels provide brief bright interruptions rather than full-width fills.
- Human proof is staged at two scales: a tall device-centered photo collage with floating speech labels, and an edge-clipped rail of 254px × 448px candid portrait videos separated by 24px. Use real people or a working-product collage with similarly natural light when video is unavailable.
- Utility meets editorial warmth: Fraunces section headings at 40px/1.17 contrast with Geist body text at 16px/1.4 and uppercase Geist Mono price-list rows at 16px/1.4; dashed rules and dotted leaders replace heavy table chrome.
- A luminous green ribbon and a seal-backed personal commitment create an emotional landing after practical footer links: a broad grainy diagonal sweep over pale sage, then centered 28px/1.4 semibold text. Recreate the ribbon with layered blurred SVG curves and a simple circular typographic seal when custom art is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Atmospheric sage | `#e1efe3` | `--color-sage` | background | Broad soft gradients behind product explanation and the closing ribbon. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversion blue | `#2463eb` | `--color-blue` | action, link, accent | Main actions, selected words and price accents; small areas only. |
| Lime speech | `#e2fd9b` | `--color-lime` | surface, accent | Visible lime speech label over ivory, using #d9ff80 at 80% opacity; retain the translucent effect. |
| Soft lime speech | `#ebfebc` | `--color-lime-soft` | surface | Visible input prompt over ivory, using #d9ff80 at 50% opacity. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control black | `#0b0b0a` | `--color-black` | action, surface | Account buttons and small video play discs. |
| Warm charcoal | `#1b1b18` | `--color-ink` | text | Default headings, body text and outline icons. |
| List charcoal | `#3c3c39` | `--color-mono-ink` | text | Uppercase pricing labels. |
| Muted emphasis | `#585854` | `--color-emphasis` | text | Visible stronger support text on ivory, made with charcoal at 73% opacity. |
| Subtle charcoal | `#757571` | `--color-subtle` | text | Visible muted body text on ivory, made with charcoal at 60% opacity. |
| List muted | `#797972` | `--color-mono-muted` | text | Secondary mono pricing annotations. |
| Leader gray | `#a7a7a0` | `--color-dot` | text, border | Pricing dot leaders and subdued footer copyright. |
| Control outline | `#d0d0ca` | `--color-outline` | border | Visible charcoal-at-20% outlines on ivory secondary actions. |
| Slate mist | `#dbe2eb` | `--color-badge` | surface | Compact availability and payment badges. |
| Portrait sage | `#dbe6dc` | `--color-portrait` | surface | Portrait backings and experience badges. |
| Warm hairline | `#e4e4dc` | `--color-rule` | border | Dashed internal card separators and inactive carousel indicators. |
| Soft edge | `#ebebe5` | `--color-edge` | border | Visible charcoal-at-8% edges on ivory cards and dashed dividers. |
| Warm stone | `#f5f5f0` | `--color-band` | background, surface | Pricing band and compact credential backgrounds. |
| Ivory | `#fdfdf7` | `--color-canvas` | background, surface, text | Dominant page canvas, pricing panel and reversed account-button text. |
| Input white | `#ffffff` | `--color-white` | surface, text | Input panel and reversed blue-action text. |

## Typography

- **Geist** — Body copy, actions, resource titles and human-proof statements. Compact contemporary grotesk, tightly tracked without looking mechanical. Font stack: "Geist", system-ui, Arial, sans-serif.
- **Fraunces** — Opening headline, feature headings, quotes and italic editorial headings. Soft, characterful editorial serif with rounded details, used at regular weight. Font stack: "Fraunces", Georgia, "Times New Roman", serif.
- **Geist Mono** — Pricing labels and prices. Compact monospace in uppercase semibold, like a practical service menu. Font stack: "Geist Mono", ui-monospace, "Courier New", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Fraunces | 400 | 48px | 1.17 | -0.01em | Friendly centered opening headline. |
| heading | Fraunces | 400 | 40px | 1.17 | -0.01em | Main feature and pricing headings. |
| statement | Geist | 500 | 28px | 1.4 | -0.02em | Left-aligned introduction to human stories. |
| commitment | Geist | 600 | 28px | 1.4 | -0.02em | Centered closing commitment. |
| quote | Fraunces | 400 | 24px | 1.17 | -0.01em | Long-form expert testimonial. |
| editorial-heading | Fraunces | 400 italic | 24px | 1.25 | -0.01em | Small resource-section lead. |
| subhead | Geist | 500 | 20px | 1.4 | -0.02em | Two-line feature summary with an inline blue phrase. |
| card-title | Geist | 600 | 18px | 1.4 | -0.02em | Resource titles and compact platform summary. |
| body | Geist | 400 | 16px | 1.4 | -0.02em | Feature explanation paragraphs. |
| identity | Geist | 600 | 16px | 1.4 | -0.02em | Names and expert attribution. |
| price-list | Geist Mono | 600 | 16px | 1.4 | -0.02em, uppercase | Menu-like service rows and aligned prices. |
| support | Geist | 400 | 14px | 1.4 | -0.02em | Opening support and concise section descriptions. |
| action | Geist | 600 | 14px | 1.4 | -0.02em | Primary and resource buttons, emphasized support text and availability pills. |
| caption | Geist | 400 | 12px | 1.4 | -0.02em | Resource descriptions, footer navigation and specialist descriptions. |
| badge-label | Geist | 500 | 12px | 1.4 | -0.02em | Credentials and anonymous-mode label. |
| small-action | Geist | 600 | 12px | 1.4 | -0.02em | Account controls and footer group labels. |

**Notes:**

- Keep serif text regular and -0.01em tracked; sans and mono share -0.02em tracking and a 1.4 line-height.
- The opening is deliberately only 48px: intimacy comes from the working input and empty space, not oversized display lettering.
- Italic serif marks a small editorial subsection, while 28px sans statements carry human testimony and the closing promise.

## Layout

**Density:** Airy between narrative blocks, compact within controls and information rows.

### Spacing

**Spacing system:**

- **step** 8px — Principal structural rhythm for 8px, 16px, 24px, 32px, 48px and 64px gaps; 4px and 12px handle tighter text and badge groups.

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and heading-to-short-description spacing. |
| 12px | Stacked small support paragraphs, input trust row and price-list rows. |
| 16px | Input padding, article media gap and expert-card column gap. |
| 24px | Expert-card padding, feature-copy stack and portrait-video gaps. |
| 32px | Pricing panel padding and footer groups. |
| 48px | Resource-grid gaps, closing seal-to-statement gap and quote horizontal padding. |
| 64px | Opening copy-to-input separation and resource-section vertical padding. |
| 80px | Pricing inner vertical padding and sage feature-band lead-in. |
| 100px | Desktop header, resource band and footer side padding. |
| 140px | Lead-in above the portrait-story section. |

### Containers and grids

- **page**: max width 1440px. Full light page stage, with broad atmospheric bands.
- **main-content**: max width 1233px · side padding 24px. Centered quote and pricing composition; text block about 420px wide beside a 640px panel.
- **opening**: max width 548px. Centered input and hero group; support text stays within 468px.
- **resources**: max width 1200px · 2 columns · gap 48px. Two-column resource list, each item 576px wide with a 150px square image.
- **experts**: 5 columns · gap 16px · side padding 24px. Centered horizontal collection of narrow 234px expert cards.
- **stories**: max width 1312px · gap 24px · side padding 24px. Clipped horizontal video rail with partially visible final item.
- **closing-statement**: max width 723px. Centered multi-line commitment below a circular seal.

## Corner radius

| Element | Radius |
| --- | --- |
| primary-action | 52px |
| account-action | 32px |
| resource-action | 40px |
| expert-card | 32px |
| price-panel | 24px |
| input-panel | 16px |
| portrait-and-thumbnail | 12px |
| credential | 6px |
| input-speech | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| input | `0px 2px 24px 0px rgba(0, 0, 0, 0.06)` | Soft, diffuse lift only under the working input. |
| blue-action | `0px 4px 7px 0px rgba(36, 99, 235, 0.39)` | Compact colored shadow under the main blue pill. |
| price-panel | `0px 15px 30px -10px rgba(0, 0, 0, 0.15), 0px 1px 1px 0px inset rgba(255, 255, 255, 0.8), 0px -1px 1px 0px inset rgba(0, 0, 0, 0.05), 1px 0px 1px 0px inset rgba(255, 255, 255, 0.8), -1px 0px 1px 0px inset rgba(0, 0, 0, 0.05), 0px 0px 20px 0px inset rgba(255, 255, 255, 0.4)` | Tactile lifted pricing card with fine inset highlights. |

### Surfaces

#### Ivory canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #fdfdf7; color: #1b1b18`

#### Sage explanation wash · level 0

**Use:** Product explanation and expert-proof grouping.

**CSS:** `background: linear-gradient(#e1efe3 0%, #fdfdf7 60%, #fdfdf7 100%)`

**Observed:** The mint tone fades away before the lower expert cards.

**Transfer:** Let atmospheric color connect several related blocks without giving each its own container.

#### Stone pricing band · level 0

**Use:** Separates the cost explanation from adjacent pale content.

**CSS:** `background: #f5f5f0`

#### Closing atmosphere · level 0

**Use:** Full footer backing under navigation, ribbon and commitment.

**CSS:** `background: linear-gradient(#fdfdf7 0%, #e1efe3 100%); position: relative; overflow: hidden`

**Observed:** An uninterrupted light gradient, with the green ribbon on a separate layer behind content.

**Transfer:** Keep the commitment area light and let the ribbon provide the concentrated color.

#### Quiet outlined card · level 1

**Use:** Expert cards and wide quotation panel.

**CSS:** `border: 1px solid rgba(27, 27, 24, 0.08); border-radius: 32px`

**Observed:** Same ground as the page; edges do the grouping, without a general card shadow.

**Transfer:** Use restrained outlines for credentials rather than strongly elevated dashboard cards.

#### Lime glass speech · level 2

**Use:** Floating conversational labels near inputs and product media.

**CSS:** `background: rgba(217, 255, 128, 0.5); border-radius: 16px 18px 18px 2px; padding: 8px 12px; backdrop-filter: blur(3.6px)`

**Observed:** The input label uses the lighter lime; larger media labels use 80% lime and 36px 36px 36px 0px corners with a soft shadow. Layered blur and edge reflections make them feel gelatinous rather than flat.

**Transfer:** Carry the short, bottom-left-tailed speech silhouette and luminous translucent fill to new benefit labels.

## Components

### Sticky navigation

**Use:** Persistent, minimal orientation and account access.

**CSS:** `height: 58px; padding: 8.9px 100px; background: #fdfdf7; backdrop-filter: blur(6px); display: flex; align-items: center`

**Text style:** `small-action` — Geist 600 · 12px/1.4 · tracking -0.02em

**Observed:** Wordmark at left; outlined login, black signup and menu at right. A fine dashed vertical divider separates the menu from the account controls; the outer wrapper is sticky with z-index 5.

**Transfer:** Keep full navigation out of the top bar; put secondary destinations behind the menu.

### Primary button

**Use:** Main product-start action.

**CSS:** `height: 44px; padding: 12px 24px; border-radius: 52px; background: #2463eb; color: #ffffff; display: flex; align-items: center; gap: 8px; box-shadow: 0px 4px 7px 0px rgba(36, 99, 235, 0.39)`

**Text style:** `action` — Geist 600 · 14px/1.4 · tracking -0.02em

**Observed:** Text followed by a small right arrow. Width follows the label; the opening example is 136px wide.

**States:** Declared: hover unspecified; focus-visible outline none and box-shadow 0px 4px 7px rgba(36, 99, 235, 0.39), 0 0 0 2px #0b0b0a.

**Transfer:** Use one direct action verb and a product-specific noun.

### Account button

**Use:** Compact signup action in navigation and footer.

**CSS:** `padding: 8px 12px; border-radius: 32px; background: #0b0b0a; color: #fdfdf7; display: flex; align-items: center; gap: 4px`

**Text style:** `small-action` — Geist 600 · 12px/1.4 · tracking -0.02em

**Observed:** Paired with a transparent outlined login using a 1px charcoal-at-20% border; the black painted face is 33px high while login is 35px.

**States:** Declared: hover unspecified; focus-visible outline 2px solid #3c83f6.

### Secondary pill

**Use:** Resource links and low-priority exploration.

**CSS:** `height: 44px; padding: 8px 16px; border: 1px solid rgba(27, 27, 24, 0.2); border-radius: 40px; color: #1b1b18; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Geist 600 · 14px/1.4 · tracking -0.02em

**Observed:** Unfilled, text-only pill; does not compete with blue conversion controls.

**States:** Declared: hover unspecified; focus-visible outline 2px solid #3c83f6.

### Conversation input

**Use:** Working product entry at the center of the opening.

**CSS:** `width: 548px; height: 148px; padding: 16px; border: 1px solid rgba(27, 27, 24, 0.08); border-radius: 16px; background: #ffffff; box-shadow: 0px 2px 24px 0px rgba(0, 0, 0, 0.06); display: flex; flex-direction: column`

**Text style:** `support` — Geist 400 · 14px/1.4 · tracking -0.02em

**Observed:** Open text area above a bottom action row: anonymous mode on the left, Primary button on the right. A Lime glass speech prompt overlaps the top-left edge; a small trust row sits outside below.

**Transfer:** If the product is not a chat service, make this a genuine search, brief or task-entry panel rather than a decorative empty field.

### Expert card

**Use:** Credibility through identifiable specialists.

**CSS:** `width: 234px; padding: 24px; border: 1px solid rgba(27, 27, 24, 0.08); border-radius: 32px; display: flex; flex-direction: column; align-items: center; gap: 19px`

**Text style:** `identity` — Geist 600 · 16px/1.4 · tracking -0.02em

**Observed:** Portrait first in a 120px × 160px sage-backed frame; dashed divider; centered name and specialty; small credential and experience badges below. Credential badges have 6px corners and 5px 9px padding.

**Transfer:** Use real experts, makers or operators with concise verifiable credentials.

### Price menu panel

**Use:** A tangible menu of included benefits and costs.

**CSS:** `width: 640px; padding: 32px; background: #fdfdf7; border-radius: 24px; box-shadow: 0px 15px 30px -10px rgba(0, 0, 0, 0.15), 0px 1px 1px 0px inset rgba(255, 255, 255, 0.8), 0px -1px 1px 0px inset rgba(0, 0, 0, 0.05), 1px 0px 1px 0px inset rgba(255, 255, 255, 0.8), -1px 0px 1px 0px inset rgba(0, 0, 0, 0.05), 0px 0px 20px 0px inset rgba(255, 255, 255, 0.4); position: relative; overflow: hidden`

**Text style:** `price-list` — Geist Mono 600 · 16px/1.4 · tracking -0.02em · uppercase

**Observed:** Six compact rows connect uppercase labels to right-aligned prices with dotted leaders. List gap is 12px; each row uses 8px gaps. Blue picks out the paid amount, with payment information below. A screen-blended texture layer adds material depth.

**Transfer:** Adapt to any transparent list of services, allowances or benefits; keep the menu-like alignment instead of a conventional multi-tier price grid.

### Dotted leader

**Use:** Connects service label and price without a table grid.

**CSS:** `background-image: radial-gradient(circle, #a7a7a0 1px, rgba(0, 0, 0, 0) 1.5px); background-size: 6px 100%; background-position: 0px 60%; height: 14px; flex-grow: 1`

**Observed:** The leader expands into the space between text ends, with a short fade at the right edge.

### Video play disc

**Use:** Clickable testimonial overlay.

**CSS:** `width: 32px; height: 32px; padding: 8px; border-radius: 100px; background: #0b0b0a; display: flex; align-items: center; justify-content: center`

**Observed:** Centered on each portrait with a 12px ivory play triangle; navigation arrows sit beneath the rail at the right.

**States:** Declared: hover transform translate(-50%, -50%) scale(1.125); focus-visible unspecified.

### Resource item

**Use:** Compact editorial content without enclosing card chrome.

**CSS:** `display: flex; align-items: flex-start; gap: 16px; width: 576px`

**Text style:** `card-title` — Geist 600 · 18px/1.4 · tracking -0.02em

**Observed:** 150px square image at left, then title, 12px description and Secondary pill. The text stack uses 4px between title and description and 16px before the action.

**Transfer:** Use short practical learning topics, not generic feature tiles.

## Imagery and graphics

### Human product collage

**Use:** Large visual explanation beside a narrow text column.

**Observed:** A roughly 302px × 614px black-edged phone displays a naturally lit video call; two smaller rounded photos overlap behind it, one upright and one tilted. Faces and ordinary environments dominate over interface chrome. Bright lime labels float across the media, not in a separate legend.

**Transfer:** Stage the product in a tall device or app window with two human context images behind it; preserve natural light, muted backgrounds and the small lime benefit annotations. If people are not relevant, use authentic working contexts and a clear product view.

### Candid portrait rail

**Use:** Human stories presented as playable media.

**Observed:** Tall 254px × 448px portrait frames show imperfect selfie-video moments in ordinary rooms or outdoors, with rounded corners, small black play discs and no dramatic color grading. Five items run horizontally, the last clipped by the rail edge.

**Transfer:** Use genuine customer or practitioner video stills. Without video, use a candid portrait-and-quote rail with the same tall framing, but do not imply it is playable.

### Practical editorial thumbnails

**Use:** Resource index beside short copy.

**Observed:** Small 150px square photographs with 12px corners: close everyday objects, people and professional portraits. Neutral illumination and modest saturation keep them secondary to titles.

**Transfer:** Choose specific tangible subjects connected to each topic; use tight square framing rather than abstract gradients.

### Green light ribbon

**Use:** Signature atmospheric graphic in the extended closing region.

**Observed:** A broad translucent green fabric-like sweep runs diagonally from a thick lower-left fold toward a narrow upper-right crest. Fine grain and luminous pale ridges soften its edges into the sage background; it occupies much more area than nearby text without becoming a dark panel.

**Transfer:** Preserve this luminous diagonal sweep on every marketing composition, placing it where an emotional pause or close is needed. A layered SVG fabric silhouette is the minimum equivalent.

**Build:** On the Closing atmosphere surface, draw three broad SVG Bézier bands across a 1440px-wide stage, rising from left to right. Fill with green rgba(50, 183, 101, 0.3), overlay a thinner rgba(115, 224, 147, 0.4) ridge and an offset rgba(255, 255, 255, 0.5) highlight. Blur broad bands by 24px and the crest by 8px; feather the outer edge with a gradient mask. Add a subtle monochrome feTurbulence layer clipped to the bands at low opacity. Keep text on a separate foreground layer and match the soft luminous folds rather than hard exact stops.

### Circular trust seal

**Use:** Small emblem over the closing commitment and at a section transition.

**Observed:** Circular fine-line badge with uppercase lettering along the perimeter and a small luminous emblem at center. The closing seal is airy, lime and charcoal rather than a solid accreditation disc; the transition badge encloses a soft green organic form.

**Transfer:** Use a truthful product principle around the circle and a simple custom central symbol; preserve a circular lettered seal even without custom illustration.

**Build:** Use SVG circles with a 1px charcoal-at-8% outline and a circular textPath. Set small uppercase sans lettering around the rim with generous tracking. Draw a simple lime line emblem or a few connected ellipses in the middle; keep the ground transparent and leave ample empty space.

### Icons

**Observed:** Mostly 16px and 24px outline SVG icons with 2px round strokes. Arrows follow action labels; availability and privacy use small supporting symbols; social icons are compact solid marks. Video triangles are 12px.

**Transfer:** Use one consistent round-stroke outline family in charcoal, white only on blue actions, and reserve solid glyphs for social identities and play controls.

## Section recipes

How recurring sections are built.

### First screen: Conversational opening

**Observed:** An ivory first screen under Sticky navigation. A compact centered group leaves about 200px of breathing room above and below. The one-line 48px Fraunces headline introduces the product with a subtle dashed underline on its name. Two restrained centered support paragraphs sit beneath, within 468px; selected phrases become semibold. After 64px, the 548px Conversation input becomes the main object, with an overlapping lime speech label, anonymous-mode control and blue action. Within the first 900px, the complete headline, support, input, actions and trust row are visible. The lower edge begins a circular green availability emblem; the full sage feature composition lies below the fold. Layers are ivory ground, text, raised white input, lime label and blue control.

**Transfer:** Lead with a personal introduction or direct helpful promise, then a usable entry point suited to the new product. Without a chat workflow, use a search or task brief at the same scale. Supporting page types can open with a concise serif title and a compact functional object rather than adding a large campaign illustration.

**Avoid:** Do not turn the opening into a giant 90px headline, a split-screen dashboard hero or a row of feature cards; its defining object is a small working input surrounded by space.

**Text style:** `display` — Fraunces 400 · 48px/1.17 · tracking -0.01em

### Explanation with staged media

**Observed:** Sage explanation wash backs a 420px left copy column and a tall Human product collage on the right. Use heading, subhead, a dashed divider, body copy, a concise cost line and Primary button in a 24px stack. One phrase in the subhead is blue; lime speech tags sit on the imagery.

**Transfer:** Pair one clear benefit explanation with a tangible product-use scene, keeping the left column short enough for the image to lead.

**Text style:** `heading` — Fraunces 400 · 40px/1.17 · tracking -0.01em

### Expert quotation and credentials

**Observed:** A wide Quiet outlined card contains a 608px serif quotation, expert attribution, dashed rule and restrained carousel controls. Beneath it, five Expert cards form a horizontal 16px-gap collection.

**Transfer:** Let one thoughtful quote establish the claim, then use portraits and compact credentials as supporting detail rather than repeating marketing blurbs.

**Text style:** `quote` — Fraunces 400 · 24px/1.17 · tracking -0.01em

### Menu-like pricing

**Observed:** Stone pricing band contains a centered 1233px composition with a 420px heading-and-support column on the left and Price menu panel on the right. Availability pills and Primary button sit under the left description. Inner vertical padding is 80px; the tactile card is 640px × 384px.

**Transfer:** Explain affordability or inclusions through a short serif promise and a precise mono menu. Keep costs aligned and visible without multiplying tiers.

**Text style:** `heading` — Fraunces 400 · 40px/1.17 · tracking -0.01em

### Stories without studio polish

**Observed:** A 28px sans statement within 640px leads into a row of short checkmarked themes and a fine dashed divider. After 40px, Candid portrait rail fills the width; Video play disc overlays sit centrally and arrows follow underneath. Section lead-in is 140px, lower breathing room 92px.

**Transfer:** Organize human outcomes under a plain-language introduction, then let actual voices carry proof. Use portrait quotes if no real video exists.

**Text style:** `statement` — Geist 500 · 28px/1.4 · tracking -0.02em

### Editorial resource band

**Observed:** A small italic serif heading and Secondary pill align on opposite ends of a 1200px header row above a dashed divider. Resource items form two columns and two rows with 48px gaps, within 64px vertical padding.

**Transfer:** Present a few useful learning paths as an editorial list, keeping imagery small and titles practical.

**Text style:** `editorial-heading` — Fraunces 400 italic · 24px/1.25 · tracking -0.01em

### Extended atmospheric ending

**Observed:** Closing atmosphere begins with a brand summary, social icons and small account actions, then a dashed horizontal rule. Compact categorized links and app badges sit left; a short right-aligned disclosure sits right. A Green light ribbon crosses the broad open region below these utilities. A Circular trust seal leads to a centered 723px-wide commitment at 28px/1.4, with 48px separation. A small local-origin note at lower left balances pale copyright at lower right. The ending stays light all the way to the bottom.

**Transfer:** Combine practical navigation with a distinct emotional close: a truthful first-person product commitment, the circular seal and luminous ribbon. Adapt the link groups and app badges to relevant destinations; let utility content and emotional artwork coexist rather than finishing with a conventional dark CTA strip.

**Text style:** `commitment` — Geist 600 · 28px/1.4 · tracking -0.02em

## Page flow

**Storyline:** personal promise → useful product entry → explained experience → expert credibility → transparent costs → human outcomes → learning paths → utility links and personal commitment

### A service landing page that makes unfamiliar technology feel safe, useful and human

1. **promise** — A brief serif introduction and restrained support address the reader personally.
2. **product entry** — A working conversation panel makes trying the service the central action.
3. **product explanation** — A sage-backed text-and-device collage connects availability with human support.
4. **credibility** — A serif expert quotation and credential cards identify real people behind the service.
5. **pricing** — A mono menu card resolves cost concerns with explicit inclusions and prices.
6. **social proof** — An unpolished portrait-video rail shows first-person experiences.
7. **education** — A compact two-column resource list supports continued exploration.
8. **closing commitment** — Utility footer links give way to a grainy green ribbon, circular seal and centered personal promise.

**Transfer:** Use these narrative functions as a flexible pattern, not a required section order. Preserve functional entry, tangible human proof, transparent terms and the atmospheric commitment device while adapting each to the new product.

## Writing

Warm, direct and practical, with the product speaking like a helpful person. Confidence rests on concrete access, costs and identified experts rather than dramatic technological superlatives.

**Do not copy:** Do not reuse Doctronic's name, logo, seal artwork, medical oath, testimonials, doctor identities, rankings, usage totals, pricing, availability, insurance, privacy or clinical claims as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the visitor as you and your. The assistant can say I for its help and commitment; organizational explanations use our and we.
- **Rhythm:** A short personal opening, compact benefit headings and one- or two-sentence support. Fragment pairs such as 'Less time explaining. More time getting better.' add pace to otherwise straightforward prose.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Friendly greeting plus product identity, without a slogan. | 3–5 words | “Hi, I’m [Brand]” |
| Feature headline | Service category followed by a broad, conversational benefit. | 7–10 words | “Urgent and Primary care that does it all” |
| Pricing headline | Plain subject plus a gentle subject-specific turn of phrase. | 6–9 words | “Pricing that won’t make you sick” |
| Supporting line | Explain what the reader gives and what they receive; follow with concrete reassurance. | One or two short sentences | “Less time explaining. More time getting better.” |
| Primary action | Verb plus a simple task, optionally reducing cost anxiety. | 2–6 words | “Start chat”<br>“Start a free chat now” |
| Input prompt | A human question, not a technical field label. | 4–6 words | “What brings you in?” |
| Resource heading | An invitation to learn, followed by specific practical titles. | 5–7 words | “Learn more about your health” |

**Words and phrasing to use:** you; your; I’ll; real; free; available; learn; start; less time; more time

**Avoid:** revolutionary disruption; unparalleled ecosystem; unlock limitless potential; technical jargon in input prompts; unqualified guarantees

**Rules:**

- Pair emotional reassurance with a verifiable practical detail, such as a cost, access condition or real credential.
- Use contractions in the conversational voice and direct verb-led actions.
- Keep technical or legal boundaries explicit in supporting copy rather than hiding them in a cheerful promise.
- The closing commitment should name a user-centered decision principle, not repeat the opening sales pitch.

## Do's and Don'ts

### Do

- Keep the opening at 48px Fraunces with a 548px functional panel underneath.
- Use 40px regular serif for primary section headings and 28px sans for human statements.
- Reserve blue #2463eb for conversion pills, selected words and price accents.
- Preserve the 16px input corners, 24px price-panel corners and 32px expert-card corners as separate roles.
- Use 1px charcoal-at-8% borders for pale cards and dashed dividers for lightweight structure.
- Set service-menu rows in 16px semibold uppercase Geist Mono with dotted leaders.
- Pair candid tall portraits with small 32px black play discs, not large promotional overlays.
- Carry the green light ribbon, circular seal and centered commitment into the closing visual language.

### Don't

- Do not replace warm ivory #fdfdf7 with a stark all-white page; white belongs to the input and reversed text.
- Do not use blue or lime as a dominant full-page background; broad color fields are pale sage.
- Do not give every card the input's 24px diffuse shadow; expert cards use faint outlines instead.
- Do not round all media into pills; portrait and resource frames use 12px corners.
- Do not set ordinary body copy in serif or mono; Geist at 16px/1.4 is the explanation default.
- Do not inflate account buttons to the main 44px action scale; their labels are 12px and their faces about 33–35px high.
- Do not convert resource items into vertically stacked image-over-title tiles; keep their compact horizontal media-and-copy construction.
- Do not replace candid customer imagery with uniformly polished studio headshots; expert portraits and customer stories have different jobs.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background, border, shadow, color and opacity transitions at 0.15s ease-in and transform at 0.1s ease-in.
- Video overlays declare hover scale(1.125) while retaining their centering transform.
- The speech bubble declares a 0.5s entrance with cubic-bezier(0.34, 1.56, 0.64, 1). A circular badge declares a 36s linear infinite reverse rotation.
- Header padding declares a 0.35s cubic-bezier(0.4, 0, 0.2, 1) transition; the tactile pricing card declares transform and shadow transitions of 0.6s cubic-bezier(0.23, 1, 0.32, 1).

**Transfer:**

- Keep conversational accents lightly animated and conversion controls quick; use the slow rotation only for the circular seal or availability badge.
- Preserve a usable pause-animation control when the atmospheric scene is animated.

**Unknown:**

- The ribbon's exact animation path, shader, timing and interaction behavior are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 528px, 576px, 600px, 640px, 767px, 768px, 1024px, 1280px and 1440px.

**Transfer:**

- On narrow screens, keep the centered functional opening and allow the 548px panel to fit the available width with side gutters.
- Stack the 420px explanation column and media scene, preserving speech-label overlap within the media bounds.
- Collapse resource items to one column while retaining square side images where space allows; keep portrait stories in a horizontal rail.
- Reduce the ribbon stage without losing its diagonal crest, seal or centered closing statement.

**Unknown:**

- Mobile type sizes, exact breakpoint-to-layout mappings and mobile navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
