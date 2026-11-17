# Basedash — copper dust circuitry

## Overview

An airy, white software-marketing style with a faintly digital, experimental edge. Regular grotesk headlines fracture into small pixel-like interruptions, while warm copper halftones surround crisp interface demonstrations. Small neutral navigation and old-style serif testimonials give the technical imagery a human counterweight; dark, luminous product art provides a concentrated moment of drama.

### Essentials

- Digital damage is confined to the headline layer: regular-weight display lettering at 58px/1.08 for the opening, 52px/1.1 for chapter statements and 44px/1.1 for feature headings, with normal tracking and scattered stepped glyph fragments.
- The opening sells through a working object, not a decorative symbol: a centered headline and paired actions precede an approximately 1104px-wide white application panel with 20px corners; its copper stippled halo spreads beyond the panel and its lower content continues past the first fold.
- Actions are compact black rectangles softened at the corners: 42px high, 10px radius, 8px 20px padding and 16px/24px semibold labels. The companion action is translucent white with a faint outline, not a second accent-colored button.
- Color behaves like copper dust on white paper: white occupies nearly all the marketing canvas; #d67a3b marks small labels, links and point-cloud art. Saturated chart colors stay inside demonstrations, except for a concentrated dark luminous product-art panel.
- Product proof floats just above the page: 15px–20px rounded interface panels, 1px translucent dark outlines and downward shadows sit over copper stippling. Include this textured technical staging; without product imagery, use a simplified working interface and an SVG dotted geometric object.
- Human proof changes the typographic register: 112px square monochrome illustrated portraits sit beside 24px/1.25 light old-style serif quotations, with small sans-serif names and case-study links underneath.
- The ending carries a monumental identity stamp: beneath small four-column footer navigation, a 976px by 271px copper wordmark artwork dissolves at its edges into halftone dots. Recreate this device with the new product's own wordmark; a plain typeset name with dotted edge diffusion is the minimum equivalent.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Copper | `#d67a3b` | `--color-copper` | accent, link, text | Sentence-case feature labels, editorial links and the warm dotted artwork; not the main action fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#171717` | `--color-ink` | text, action, border | Headlines, primary labels and filled actions. |
| Luminous art backing | `#0b0b0b` | `--color-art-black` | background | Black portrait tiles and the concentrated dark product-art vignette. |
| Soft body ink | `#585858` | `--color-body` | text | Supporting prose; visible result of rgba(23,23,23,0.72) over white. |
| Secondary gray | `#7f7f7f` | `--color-muted` | text, link | Navigation, footer links and small attribution; rgba(23,23,23,0.55) over white. |
| Hairline gray | `#e3e3e3` | `--color-rule` | border | Section dividers, table rules and panel edges; rgba(23,23,23,0.12) over white. |
| Warm shell edge | `#e7e5e3` | `--color-warm-edge` | border | White hero application edge; rgba(73,53,39,0.13) over white. |
| Hover wash | `#f3f3f3` | `--color-control-fill` | surface | Faint interaction fill; rgba(23,23,23,0.05) over white. |
| Porcelain panel | `#fafafa` | `--color-panel` | surface | Floating product demonstrations and small technical panels. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Page, white application shells and reversed action labels. Translucent white also forms navigation and secondary actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| feature and company introductions | Light copper | `#de9558` | `--color-light-copper` | text | Uppercase monospace opening labels. |

## Typography

- **Inter** — Body, actions, navigation, card headings and numeric proof. Neutral sans-serif with a compact, readable lowercase and restrained medium-to-semibold emphasis. Font stack: "Inter", ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, Helvetica, Arial, sans-serif.
- **Basedash Glitch** — Marketing headlines, section statements and closing calls. Regular sans-serif letterforms with selective stepped digital fragmentation, rather than a fully pixelated alphabet. If unavailable, use **Inter**. Use 400; add sparse stepped glyph fragments as a separate visual layer, without damaging readability. Font stack: "Basedash Glitch", Inter, ui-sans-serif, system-ui, sans-serif.
- **Iowan Old Style** — Customer quotations. Light old-style serif with conventional quotation marks and tight tracking. If unavailable, use **Libre Baskerville**. Use regular with the same compact line length; avoid bold quotation text. Font stack: "Iowan Old Style", "Libre Baskerville", "Palatino Linotype", "Book Antiqua", Palatino, "URW Palladio L", serif.
- **ui-monospace** — Small uppercase opening labels and technical excerpts. System monospace, used as a technical annotation rather than the main voice. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Basedash Glitch | 400 | 58px | 1.08 | normal | Centered primary landing promise. |
| chapter | Basedash Glitch | 400 | 52px | 1.1 | normal | Centered chapter statement separating groups of capabilities. |
| closing | Basedash Glitch | 400 | 48px | 1 | normal | Closing conversion statement and centered informational section leads. |
| heading | Basedash Glitch | 400 | 44px | 1.1 | normal | Left-aligned feature headings, generally two or three lines. |
| quote | Iowan Old Style | 300 | 24px | 1.25 | -0.025em | Customer quotations paired with illustrated portrait tiles. |
| card-heading | Inter | 600 | 20px | 28px | normal | Plan titles and evidence-row headings. |
| body-lead | Inter | 400 | 18px | 1.625 | normal | Feature explanation, limited to 480px width in split sections. |
| action | Inter | 600 | 16px | 1.5 | normal | Primary and secondary actions, plus compact emphatic labels. |
| mini-heading | Inter | 500 | 16px | 24px | normal | Small capability-grid title beside a tiny icon. |
| label | Inter | 400 | 14px | 20px | normal | Copper section eyebrows, footer links and small support copy. |
| navigation | Inter | 500 | 14px | 20px | normal | Navigation and small case-study links. |
| footer-heading | Inter | 600 | 14px | 20px | normal | Small footer column titles. |
| faq-answer | Inter | 400 | 14px | 28px | normal | Expanded explanatory answers and comparison-table prose. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| feature landing pages | feature-opening | Basedash Glitch | 400 | 48px | 1.1 | normal | Centered product-feature promise. |
| company and pricing pages | information-opening | Basedash Glitch | 400 | 48px | 1.15 | normal | Company promise or left-aligned pricing title. |
| pricing pages | price | Inter | 600 | 36px | 40px | -0.025em | Plan price or custom-price label. |
| company evidence sections | stat | Inter | 400 | 36px | 1 | -0.03em | Standalone numeric or abbreviated proof in the narrow left column of a ruled evidence row. |
| pricing and company information pages | faq-heading | Inter | 400 | 30px | 36px | normal | Plain informational FAQ heading. |
| pricing and company information pages | faq-question | Inter | 400 | 18px | 28px | normal | Question labels in broad ruled accordions. |
| company information pages | evidence-body | Inter | 400 | 16px | 28px | normal | Longer factual explanations in company proof and service rows. |
| feature and company introductions | technical-eyebrow | ui-monospace | 600 | 12px | 16px | 0.1em, uppercase | Copper technical category label above an opening headline. |

**Notes:**

- Keep the main display hierarchy at weight 400 and normal tracking; the distinctiveness comes from glyph fragmentation, not heavy weight or extreme negative spacing.
- Tight tracking is reserved for old-style quotations and large Inter numerals. Do not apply numeral tracking to all body text.
- Display lettering remains near-black and readable. Introduce small stepped interruptions in selected glyphs rather than applying a pixel font to every character.
- Keep labels and navigation much smaller than feature headings; dense prose belongs inside proof, pricing and informational variants rather than in the main display layer.

## Layout

**Density:** Airy marketing composition with compact controls and intentionally dense but contained product proof.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight heading-price gaps and icon-to-label spacing. |
| 12px | Paired action gap and related-card grid gap. |
| 16px | Eyebrow-to-feature-heading gap and portrait-to-quotation gap. |
| 20px | Feature heading-to-paragraph gap and compact panel padding. |
| 24px | Container side padding and small content group spacing. |
| 32px | Paragraph-to-action gap and testimonial column gap. |
| 48px | Opening section padding, hero text-to-object separation and internal proof-grid gap. |
| 56px | Footer top and bottom content padding; capability grid separation. |
| 64px | Desktop feature split gap. |
| 96px | Default section top and bottom padding; pricing plan column gap. |

### Containers and grids

- **landing-container**: max width 1152px · side padding 24px. Centered outer container for the main product narrative, giving 1104px of usable width.
- **information-container**: max width 1024px · side padding 24px. Navigation, footer, customer proof and pricing content; 976px usable width.
- **feature-split**: 2 columns · gap 64px. A flexible copy column beside a demonstration capped at 544px; alternate the media side across capability chapters.
- **hero-copy**: max width 896px. Centered promise, support and action cluster above the large application shell.
- **body-column**: max width 480px. Readable left-aligned feature explanation.
- **testimonials**: 2 columns · gap 32px. Two independent quotation blocks within the information container.
- **footer-grid**: 4 columns · gap 32px. Wider brand-summary column and three narrower navigation columns; proportions 1.7fr 1fr 1fr 1fr.
- **related-grid** (only for feature landing pages): 3 columns · gap 12px. Compact related-feature links near a feature-page ending.
- **faq-container** (only for pricing and company information pages): max width 896px. Single broad accordion list on informational pages.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-related-links | 10px |
|  | floating-small-panels | 15px |
|  | application-shells | 20px |
| product demonstrations | small-inset-controls | 7.5px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-feature-panel | `0px 24px 60px -32px rgba(0,0,0,0.55)` | A broad downward shadow under a large light feature demonstration. |
| small-technical-panel | `0px 18px 40px -22px rgba(0,0,0,0.6)` | Small overlapping interface excerpts and technical cards. |
| hero-shell | `0px 1px 3px rgba(51,33,19,0.04), 0px 18px 50px -22px rgba(17,17,17,0.18)` | Very restrained warm depth beneath the main opening application. |

### Surfaces

#### Canvas · level 0

**Use:** All marketing sections.

**CSS:** `background: #ffffff; color: #171717`

**Observed:** Sections remain on a continuous white plane rather than alternating colored bands.

**Transfer:** Use spacing and typography to separate narrative chapters.

#### Glass navigation · level 3

**Use:** Sticky navigation above the continuous page.

**CSS:** `background: rgba(255,255,255,0.85); border-bottom: 1px solid rgba(23,23,23,0.12); backdrop-filter: blur(8px)`

**Observed:** Content beneath the header is softened while its bottom edge remains a fine horizontal line.

**Transfer:** Keep this translucent white treatment even when the content beneath it is darker.

#### Application shell · level 1

**Use:** Opening product demonstration.

**CSS:** `background: #ffffff; border: 1px solid rgba(73,53,39,0.13); border-radius: 20px; box-shadow: 0px 1px 3px rgba(51,33,19,0.04), 0px 18px 50px -22px rgba(17,17,17,0.18); overflow: hidden`

**Observed:** A large credible application surface stands in front of a much broader warm dotted field.

**Transfer:** Show a legible real task and result; preserve a white shell around the product's own interface.

#### Floating demonstration · level 2

**Use:** Feature scenes and overlapping excerpts.

**CSS:** `background: #fafafa; border: 1px solid rgba(23,23,23,0.12); border-radius: 20px; box-shadow: 0px 24px 60px -32px rgba(0,0,0,0.55); overflow: hidden`

**Observed:** Smaller excerpts use 15px corners and more localized shadows. Multiple panels can overlap asymmetrically.

**Transfer:** Compose a few precise UI fragments rather than enclosing every marketing paragraph in a card.

#### Ruled content · level 0

**Use:** FAQs, comparison tables, fact lists and editorial feature summaries.

**CSS:** `border-bottom: 1px solid rgba(23,23,23,0.12)`

**Observed:** Rows have no rounded outer card or raised fill; first and last rules can frame the list.

**Transfer:** Use this low-chrome surface for evidence and long explanations.

## Components

### Sticky navigation

**Use:** Persistent site orientation.

**CSS:** `position: sticky; top: 0px; z-index: 40; height: 71px; background: rgba(255,255,255,0.85); border-bottom: 1px solid rgba(23,23,23,0.12); backdrop-filter: blur(8px)`

**Text style:** `navigation` — Inter 500 · 14px/20px

**Observed:** A small black identity anchors the left, centered navigation has category chevrons, and login plus a compact black action sit at the right. The inner container is 1024px wide with 24px side padding. The header action uses a 14px semibold label and is 38px high.

### Primary button

**Use:** Main conversion or capability exploration.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #171717; color: #ffffff; border: 1px solid #171717; border-radius: 10px; padding: 8px 20px; height: 42px`

**Text style:** `action` — Inter 600 · 16px/1.5

**Observed:** Exploration buttons append a small right arrow; opening conversion actions use plain text. Adjacent actions are separated by 12px.

**States:** Declared: hover unspecified; focus-visible unspecified; active scale 0.97.

### Secondary button

**Use:** Sales-assisted action beside the primary action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: rgba(255,255,255,0.25); color: #171717; border: 1px solid rgba(23,23,23,0.12); border-radius: 10px; padding: 8px 20px; height: 42px; backdrop-filter: blur(8px)`

**Text style:** `action` — Inter 600 · 16px/1.5

**Observed:** The outlined action remains visually subordinate to the filled action, with the same label scale and baseline.

**States:** Declared: hover background-color color-mix(in oklab, #17171738 60%, transparent); focus-visible unspecified; active scale 0.97.

### Navigation link

**Use:** Small utility and navigation destinations.

**CSS:** `color: rgba(23,23,23,0.55); font-size: 14px; font-weight: 500; line-height: 20px`

**Text style:** `navigation` — Inter 500 · 14px/20px

**Observed:** Links use text alone, with small chevrons only for grouped destinations.

**States:** Declared: hover color #171717; focus-visible unspecified.

### Testimonial block

**Use:** Human endorsement between technical chapters.

**CSS:** `display: flex; gap: 16px`

**Text style:** `quote` — Iowan Old Style 300 · 24px/1.25 · tracking -0.025em

**Observed:** A square illustrated monochrome portrait is beside a narrow quotation. Name, small role/company line, logo and a case-study link follow. Quotations are not enclosed in cards; two blocks share a row.

**Transfer:** Use a short specific account of a changed workflow, keeping the serif contrast and portrait treatment.

### FAQ row

**Use:** Objection handling in broad informational accordions.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 20px 16px; cursor: pointer`

**Text style:** `faq-question` — Inter 400 · 18px/28px

**Observed:** A semantic disclosure row sits within Ruled content, with a 20px thin chevron on the right. Expanded prose uses faq-answer. Feature-page FAQs instead pair a narrow 36px display introduction at left with a 624px list at right, 16px/24px questions and 16px 0px row padding.

**States:** Declared: hover background-color #1717170d; focus-visible unspecified.

### Footer

**Use:** Full site navigation and closing identity.

**CSS:** `background: #ffffff; border-top: 1px solid rgba(23,23,23,0.12)`

**Text style:** `label` — Inter 400 · 14px/20px

**Observed:** A four-column information grid contains a brand summary, social glyphs, legal and language links at left, followed by grouped navigation. Column headings use footer-heading; links use muted label text. The large copper identity artwork sits below the columns with 32px bottom padding.

### Capability item

**Use:** Low-chrome technical reassurance grid.

**CSS:** `padding: 0px 24px 40px 24px; border-left: 1px solid rgba(23,23,23,0.12)`

**Text style:** `mini-heading` — Inter 500 · 16px/24px

**Observed:** A tiny icon sits beside the title, followed by muted 14px/1.625 prose. Four columns with two rows sit beneath a wide feature introduction; outermost items can omit the leading rule.

**Transfer:** Use concise independent assurances, not long boxed feature descriptions.

### Related feature link

**Only for:** feature landing pages

**Use:** Compact onward navigation after a feature explanation.

**CSS:** `display: flex; flex-direction: column; padding: 20px; border: 1px solid rgba(23,23,23,0.12); border-radius: 10px`

**Text style:** `action` — Inter 600 · 16px/1.5

**Observed:** A small icon and semibold title sit above a muted 14px description, with a fine arrow at the right. Three equal links form one row.

### Comparison row

**Only for:** pricing pages

**Use:** Side-by-side plan entitlements.

**CSS:** `display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); column-gap: 12px; border-bottom: 1px solid rgba(23,23,23,0.12)`

**Observed:** Each side has a small green check or neutral minus and a plain feature label. Cells have 24px horizontal and 20px vertical padding. A separate multi-vendor comparison uses a pale header, uppercase small labels and five text columns.

**Transfer:** Use plain ruled rows and aligned terms, not a stack of heavily rounded pricing cards.

### Proof row

**Only for:** company evidence sections

**Use:** Verifiable company or product differentiators.

**CSS:** `display: grid; grid-template-columns: 240px 1fr; gap: 48px; padding: 36px 0px; border-bottom: 1px solid rgba(23,23,23,0.12)`

**Text style:** `stat` — Inter 400 · 36px/1 · tracking -0.03em

**Observed:** The left column has a large regular numeral or short abbreviation and a small muted caption. The right has a semibold card-heading, factual body paragraph and a small arrow link.

**Transfer:** Pair one compact proof token with its explanation and a way to inspect the claim.

## Imagery and graphics

### Copper stipple field

**Use:** Signature backing for the main product stage and selected technical feature scenes.

**Observed:** Warm copper dots make a diffuse halo around the white hero shell. Smaller scenes contain dotted rings, cylindrical stacks or angular line objects behind floating panels. Fine regular point spacing creates a digital halftone rather than photographic grain.

**Transfer:** Keep the copper point-cloud material even when the underlying product changes. A simple dotted ring, folded frame or stacked cylinder is sufficient when complex artwork is unavailable.

**Build:** Use an SVG mask of a cylinder, ring or broad elliptical halo over a 2px–4px repeating dot pattern. Fill dots with copper at roughly 0.12–0.5 alpha; fade the outer mask over 40px–100px into white. Layer two offset contours and a blurred warm silhouette beneath the sharp dots. At hero scale spread the field wider than the 1104px shell; at feature scale use a roughly 500px square field behind the UI.

### Working interface scenes

**Use:** Primary product explanation and proof.

**Observed:** The hero shows charts, tabular records and a conversation side by side in a white application shell. Feature scenes isolate a chart, a message, a terminal or a settings view, often with a second smaller excerpt overlapping the lower edge. Charts carry the strongest ordinary colors while the surrounding application remains very pale.

**Transfer:** Show one plausible task, its result and enough application framing to feel functional. If no finished product exists, construct a coherent compact task/result view instead of abstract empty boxes.

### Monochrome portrait tiles

**Use:** Customer proof.

**Observed:** Head-and-shoulders faces are transformed into high-contrast black-and-white illustrated or engraved-looking portraits on 112px square dark tiles, with thin diagonal line details. These are small anchors beside the larger serif quote.

**Transfer:** Use tightly framed portraits with a thresholded or engraved treatment and a nearly black backing; keep recognizable faces and avoid colorful circular avatars.

**Build:** Place a tightly cropped grayscale portrait over a black square, increase contrast, and add a sparse diagonal line overlay with a mask that leaves the face clear. Retain a crisp rectangular edge.

### Luminous product vignette

**Use:** Concentrated visual drama in a conversion section.

**Observed:** A broad, shallow black product close-up appears beneath centered conversion copy. Charts and numerals recede diagonally in perspective; bright white marks have green and magenta chromatic fringes. A stepped, dotted gray-white perimeter dissolves the dark image back into the white page.

**Transfer:** Use the new product's own output in a dark luminous close-up. For a minimal equivalent, create an SVG chart or workflow with sharp white marks and slight colored ghost edges on a perspective plane; keep the surrounding page white.

**Build:** Use a black landscape panel about 1104px wide and roughly 400px high. Place two or three dark UI planes with perspective rotation, thin bright marks and a few readable output tokens. Duplicate bright strokes with 1px–3px green/magenta offsets and a soft blur. Surround the panel with 20px–50px of repeated dotted inset contours, fading their opacity outward. Do not turn the whole section into a dark band.

### Dissolving identity artwork

**Use:** The final visual signature below footer navigation.

**Observed:** An oversized copper identity spans the 976px inner footer width inside a 3.6:1 art area. Most letters remain solid, while edges and selected portions break into small regular dots and soft displaced fragments.

**Transfer:** Use the new product's own logotype, or a plain sans-serif name when no custom mark exists, with the same oversized copper treatment.

**Build:** Create a 976px by 271px SVG viewBox containing an own-brand wordmark centered vertically. Duplicate the lettering into a fine dot-pattern mask, expanding the masked version beyond a few selected edges. Blend solid copper centers with dotted edge falloff and slight blur on isolated fragments; preserve a readable silhouette.

### Icons

**Observed:** Small monochrome glyphs dominate navigation and feature labels: 14px filled arrows and 15px feature symbols. FAQ chevrons are 20px, 1.5px round strokes in muted ink; pricing checks use 20px rounded line icons with green details. Footer social glyphs are 20px.

**Transfer:** Choose compact simple symbols with restrained detail. Keep colored semantic checks within proof and pricing, and avoid large colorful icon badges in the marketing grid.

## Section recipes

How recurring sections are built.

### First screen: Product stage opening

**Observed:** A 71px Glass navigation bar leads into a white opening padded 48px vertically. Center the regular 58px display promise within an 896px text group, followed by a short two-line gray explanation and paired Primary button and Secondary button. The text cluster occupies about the upper third of the first screen. After 48px, a 1104px-wide Application shell shows the working product; a broad Copper stipple field glows behind it, while the shell and its fine edge remain sharp in front. Within the first 900px the full headline, support and actions are visible and most of the product task can be understood; the bottom of the demonstration and subsequent social proof fall below the fold.

**Transfer:** Stage a believable result for the new product at the same visual scale. Without finished UI, create a focused task/result panel, backed by the copper stipple device. Feature introductions use a 48px headline, a monospace category label and a trial note; company introductions replace the big application with a compact four-fact strip; pricing introductions are left aligned above two simple plan columns.

**Avoid:** Do not replace the opening with a full-bleed photo, left-heavy giant slogan or a small disconnected mockup. Do not apply the copper texture across the text itself.

**Text style:** `display` — Basedash Glitch 400 · 58px/1.08

### Chapter statement

**Observed:** A centered 52px chapter heading separates major capability groups, with 96px top padding and little extra decoration. The following feature scene provides the visual density.

**Transfer:** Use a short unifying benefit to introduce a new idea cluster rather than another boxed banner.

**Text style:** `chapter` — Basedash Glitch 400 · 52px/1.1

### Alternating capability scene

**Observed:** Within landing-container, Feature-split pairs a copy block with Floating demonstration or Copper stipple field. The copy order is copper label, heading after 16px, body after 20px and action after 32px. Sections have 96px top and bottom padding, and the media side alternates.

**Transfer:** Explain one capability through a concrete workflow, letting the media show the result and the paragraph explain why it matters.

**Text style:** `heading` — Basedash Glitch 400 · 44px/1.1

### Social proof interlude

**Observed:** A centered muted adoption line and a horizontal monochrome logo strip lead to two Testimonial blocks. Logos fade at the strip edges; quotations remain on white with no card surround.

**Transfer:** Use verified adoption proof and human stories to interrupt long technical sequences without adding another dramatic color block.

**Text style:** `quote` — Iowan Old Style 300 · 24px/1.25 · tracking -0.025em

### Capability assurance matrix

**Observed:** A left-aligned feature introduction sits above a four-column, two-row group of Capability items, separated by fine vertical rules. A Primary button can align to the far right of the introduction rather than below its paragraph.

**Transfer:** Use for operational guarantees or practical details that benefit from scanning; keep the headline and body in a narrower column.

**Text style:** `heading` — Basedash Glitch 400 · 44px/1.1

### Objection handling

**Observed:** Broad FAQ rows sit below a 30px plain Inter heading on information pages. The feature variant uses a smaller display introduction beside the list; related feature links follow it before the conversion call.

**Transfer:** Choose the centered broad list for general purchasing questions and the side-intro list for product-specific objections.

**Text style:** `faq-heading` — Inter 400 · 30px/36px

### Closing conversion scene

**Observed:** A centered 48px statement, one short support line and paired actions lead into Luminous product vignette, framed by 96px section padding. The feature variant is a shorter text-and-actions close without the dark image; the pricing variant uses an integrated white booking calendar with event details, month grid and time choices beneath the closing line.

**Transfer:** Close with a practical next step and low-friction reassurance. Use the luminous vignette as a concentrated signature moment somewhere in the main landing narrative, not necessarily at this exact position.

**Text style:** `closing` — Basedash Glitch 400 · 48px/1

### Identity footer ending

**Observed:** Footer begins with a thin full-width top border, then a 1024px outer container with 56px vertical padding and four text columns. Dense small links stay muted. Dissolving identity artwork occupies a separate 976px-wide final stage beneath the columns.

**Transfer:** Keep the final identity oversized relative to the navigation, and leave enough white around it to feel like a visual sign-off rather than another link row.

**Text style:** `label` — Inter 400 · 14px/20px

### Plan and comparison system

**Only for:** pricing pages

**Observed:** A left-aligned 48px title introduces two unboxed plan summaries with 96px between them, 20px semibold plan names and 36px semibold prices. Long Comparison rows follow, then a centered comparison heading and a pale-header text table. Three top-ruled adoption scenarios add explanation before the FAQ.

**Transfer:** Keep plans spare and compare concrete inclusion terms. Let longer tables answer purchasing questions instead of compressing everything into decorative cards.

**Text style:** `information-opening` — Basedash Glitch 400 · 48px/1.15

### Editorial proof and facts

**Only for:** company information pages

**Observed:** Centered 48px section statements introduce top-ruled three-column feature summaries, Proof rows, paired audience lists, and two-column service explanations. A narrower facts table uses small labels and dark values on white with thin row separators.

**Transfer:** Use for company information or evidence-heavy narratives. Trade floating UI for inspectable text and numerals while retaining the regular display voice.

**Text style:** `closing` — Basedash Glitch 400 · 48px/1

## Page flow

**Storyline:** Promise → tangible product proof → human trust → capability chapters → verifiable details → practical next step → monumental identity sign-off.

### Broad product landing narrative

1. **Promise and product proof** — Centered display promise and paired actions above a large working application with copper stippling.
2. **Social proof** — Monochrome logos and two illustrated-portrait serif quotations.
3. **Capability chapters** — Centered chapter statements and alternating copy/interface scenes, with another quotation interlude.
4. **Operational reassurance** — A sparse icon-and-rule capability matrix.
5. **Closing call** — Practical conversion promise, paired actions and luminous dark product artwork.
6. **Identity sign-off** — Small footer navigation over a dissolving copper wordmark.

**Transfer:** Adapt the number and order of chapters to the product, preserving the alternation of functional proof, human proof and material-rich art.

### Commercial decision and objection resolution

1. **Pricing promise** — Short left-aligned title and straightforward terms.
2. **Plan choice** — Two unboxed plan summaries and a long aligned inclusion comparison.
3. **Decision support** — Pricing-model table and three plain adoption scenarios.
4. **Objection handling** — Broad ruled FAQ.
5. **Sales conversation** — Centered closing invitation with an embedded booking calendar.
6. **Identity sign-off** — Shared footer and copper wordmark artwork.

**Transfer:** Keep commercial pages more textual and comparative; preserve material-rich identity in the shared ending rather than adding decorative pricing-card gradients.

### Focused feature adoption

1. **Feature promise** — Monospace eyebrow, centered display headline, support, paired actions and a large in-context application.
2. **Social proof** — Muted adoption line and logo strip.
3. **Implementation and capability proof** — Alternating code, account-separation, conversation and customization scenes.
4. **Technical reassurance** — Fine-rule assurance matrix followed by serif customer quotations.
5. **Objection handling and onward navigation** — Side-intro FAQ and three related-feature links.
6. **Closing call and identity** — Compact text-and-actions close, then shared footer artwork.

**Transfer:** Explain the feature from both the buyer's and implementer's perspective, using code only when it clarifies integration.

### Company credibility and inspectable product context

1. **Company promise** — Centered headline, fuller introduction, compact four-fact strip and paired actions.
2. **Trust** — Logo strip and illustrated-portrait quotations.
3. **Offering summary** — Top-ruled three-column text summaries.
4. **Quantified proof** — Large numerals or abbreviations in a narrow left column beside factual explanations.
5. **Fit and service** — Paired audience lists and two-column working-relationship details.
6. **Reference facts and objections** — Narrow ruled facts table and broad FAQ.
7. **Closing call and identity** — Conversion invitation with dark luminous product art, then shared footer.

**Transfer:** Use the same visual grammar for an evidence-led company narrative; substitute the new organization's verifiable facts rather than adding unrelated culture imagery.

## Writing

Direct, technically literate and calmly assertive. Benefits are explained through concrete workflows, with operational details and inspectable proof instead of vague ambition.

**Do not copy:** Do not reuse Basedash's name, logomark, customer identities, quotations, prices, adoption counts, benchmark results, security claims or product-specific promises. Source examples illustrate syntax and tone only.

- **Addressing the reader:** Address the reader as you and your team; use we for help and service. Product explanations can name the product as the actor, then return quickly to what the reader can do.
- **Rhythm:** Short sentence-case headlines of roughly 4–10 words, followed by two or three connected explanatory sentences. Small labels categorize the section; action labels are brief and literal. Technical terms appear naturally without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category and the change in context, or describe the capability inside the reader's environment. | 5–9 words | “Analytics for the AI era”<br>“An AI analyst inside your product” |
| Capability heading | State a usable capability with a trust or effort benefit. | 6–10 words | “Self-serve analytics you can actually trust”<br>“A few lines of React and a token from your server” |
| Supporting explanation | Start with the action the reader can take; follow with the mechanism and its practical consequence. | 2–3 sentences | “Connect Claude, ChatGPT, or Cursor over MCP, call the REST API from your own apps, or ask in Slack. Every path runs on the same models and permissions, so your data stays governed and you're never locked in.” |
| Primary action | Use a direct verb plus destination or outcome. | 2–5 words | “Start free”<br>“Read the SDK docs”<br>“Explore the context engine” |
| Proof introduction | Present a claim as something the buyer can inspect. | One short sentence | “Five specifics you can check before you sign anything.” |
| Closing call | Invite a practical next step, linking value to use rather than abstract transformation. | 5–9 words | “Get started in under 30 minutes”<br>“Ship analytics your customers will use”<br>“Talk through pricing with us.” |

**Words and phrasing to use:** your team; plain English; governed; connect; built in; shows; verify; without building; your own; get started

**Avoid:** revolutionary; supercharge; unleash; game-changing; magic; limitless; !!!

**Rules:**

- Lead with a user action or a usable outcome, then explain the implementation.
- Pair ambitious claims with an inspectable mechanism or genuine proof.
- Use technical language when it removes uncertainty; do not turn all copy into developer documentation.
- Make the secondary action a helpful conversation rather than an artificially urgent sales demand.

## Do's and Don'ts

### Do

- Keep the main display at weight 400, with 44px feature headings and normal tracking.
- Use 96px vertical section padding to let floating demonstrations breathe.
- Limit ordinary feature prose to about 480px and pair it with a 544px media column.
- Use 10px button corners and maintain a 12px gap between paired actions.
- Give application shells a 1px warm translucent edge and 20px corners.
- Retain serif 24px quotations and 112px square portraits as a distinct proof register.
- Use fine ruled rows for comparisons and facts instead of raised cards.
- End with the oversized copper identity artwork below the small footer columns.

### Don't

- Do not turn the copper accent into full-width orange section backgrounds or orange primary buttons.
- Do not make all text monospace; monospace is reserved for tiny technical labels and excerpts.
- Do not set the display hierarchy in bold grotesk; it loses the light fragmented character.
- Do not round primary actions into pills; their 10px corners are deliberately rectangular.
- Do not spread saturated demonstration chart colors across headings, navigation or page chrome.
- Do not use huge colorful feature-icon badges; the marketing glyphs are mainly 14px–20px and monochrome.
- Do not give editorial proof rows thick borders, heavy fills or drop shadows.
- Do not carry the black vignette background through the footer or the entire closing section.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions use 0.15s cubic-bezier(.22, 1, .36, 1) for color, background-color, border-color and scale.
- Primary and secondary actions declare active scale 0.97.
- Logo tracks declare leftward and rightward marquee motion at 60s linear infinite.
- Small technical tabs declare a 2px solid copper focus-visible outline with 1px offset.

**Transfer:**

- Keep interaction feedback small and quick; reserve continuous movement for the slow logo tracks.
- Maintain a readable stable headline silhouette even when using fragmented letter treatment.

**Unknown:**

- Timing and behavior of the display fragmentation and point-cloud scenes are not established.
- No observed focus-visible treatment is established for the primary conversion actions.

### Responsive

**Observed:**

- Desktop composition uses a two-column capability split, four-column reassurance grid and four-column footer.
- Responsive utility rules describe single-column product shells at smaller widths and two-column shells with a 320px conversation pane at larger widths; numeric breakpoint thresholds are not established.

**Transfer:**

- On narrow screens, stack the copy and product scene while keeping the copper field attached to the media, not behind the paragraph.
- Reduce multi-column proof and footer groups to fewer columns; preserve the oversized final identity as a width-fitting artwork.
- Let action pairs wrap and grow across the available row rather than reducing their label size.

**Unknown:**

- Mobile layouts and precise breakpoint thresholds are not established.
- No viewport-relative type formula is established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
