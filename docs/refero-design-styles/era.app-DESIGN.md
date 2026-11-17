# Era — domestic life, working systems

## Overview

A warm, paper-like digital style that makes capable software feel at home in ordinary life. Dark plum grotesk typography, pastel highlighter marks and finely ruled product windows sit beside sunlit architectural photography. The default is a spacious light editorial presentation with dense, credible demonstrations; shorter technical and audience pages take a cooler, more utilitarian form.

### Essentials

- An everyday-life overture leads into serious software: a shallow full-width photograph precedes a split opening with a 96px/1.02, weight 500 headline and a roughly 576px-wide working interface, not an abstract mascot.
- Headlines sound like useful promises and look like tight typesetting: Saans VF at 56px/1.06, weight 500, -0.025em tracking for chapters; 96px display tightens to -0.035em. Keep the dark plum lettering on warm paper.
- Chapters have a marginal highlighter voice: a 144px label rail, 24px gutter and a 1152px content field at desktop; 14px labels sit on mint, lavender, peach or lime rectangles with square edges.
- Color behaves like stationery rather than atmosphere: most of the page stays #f7f5f2 or #eeebe8, with accents in tiny markers, interface annotations and an 8px segmented rule in lavender, pink and blue, divided 4:2:2.
- Demonstrations are sheets of evidence: near-white square-cornered browser windows, hairlines, small plain-language captions and a purple-tinted 0px 28px 65px -18px shadow. Present one meaningful workflow in detail rather than a collage of floating devices.
- Actions are small and practical beside the oversized type: 48px-high dark plum buttons, 6px corners, 14px weight 550 text, paired with modest underlined links; navigation actions shrink to 38px.
- Include a human respite and a small computational ornament: overhead sunlit photography balances the interface chapters, and a mint-and-lavender square-pixel wave accompanies the closing invitation. Use a real everyday setting and a simple SVG wave when bespoke media is unavailable.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lime | `#d9eb68` | `--color-lime` | accent | Highlighter category labels and small pricing savings badges. |
| Pink | `#f785c9` | `--color-pink` | accent | Middle quarter of the signature rule. |
| Peach | `#ffb28d` | `--color-peach` | accent | Highlighter category labels. |
| Sky blue | `#8fc9ff` | `--color-blue` | accent | Final quarter of the signature rule and occasional marginal markers. |
| Mint | `#77dac1` | `--color-mint` | accent, surface | Highlighter labels, positive proof accents and pixel art. |
| Lavender | `#bbaaf9` | `--color-lavender` | accent, surface | Highlighter marks, pixel art, the longest segment of the signature rule and the recommended pricing tier. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Plum ink | `#241e2b` | `--color-ink` | text, action, border | Default headlines, primary actions and strong outlines. |
| Annotation plum | `#302036` | `--color-plum` | text | Text on colored markers and the lavender pricing panel. |
| Muted plum | `#625a69` | `--color-muted` | text, link | Support paragraphs and footer links. |
| Plum hairline | `#cec8d0` | `--color-rule` | border | Editorial dividers, window edges and pricing rows. |
| Putty | `#eeebe8` | `--color-band` | background, surface | Alternating editorial bands, navigation backing and closing invitation. |
| Warm paper | `#f7f5f2` | `--color-canvas` | background, text | Default marketing canvas and light text on primary actions. |
| Raised paper | `#fffdfb` | `--color-paper` | surface | Product-window sheets and pricing cards. |
| White | `#ffffff` | `--color-white` | text, surface | Reversed navigation over photography; feature-card surfaces on cooler pages. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Focus violet | `#5530c9` | `--color-focus` | border | 2px focus-visible outlines on default editorial controls. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| audience and technical product pages | Blue-black | `#0f1720` | `--color-cool-ink` | text, background | Text and dark closing panels in the cooler variant. |
| audience and technical product pages | Cool gray text | `#84898d` | `--color-cool-muted` | text | Visible half-opacity blue-black over cool white; authored as rgba(15, 23, 32, 0.5). |
| audience and technical product pages | Cool hairline | `#e6e6e4` | `--color-cool-rule` | border | Feature-card edges, FAQ rules and footer separators. |
| audience and technical product pages | Cool footer gray | `#f7f7f8` | `--color-cool-footer` | background | Slightly differentiated footer canvas. |
| audience and technical product pages | Cool white | `#f8faf9` | `--color-cool-canvas` | background, text | Cool page canvas and reversed closing-panel text. |

## Typography

- **Saans VF** — All marketing headings, paragraphs, labels, actions and demonstration text. A contemporary grotesk with broad, open lowercase forms; medium headlines feel editorial rather than mechanically bold. If unavailable, use **Inter**. Use weights 400–600, including variable 550; retain the tight heading tracking and test line breaks. Font stack: "Saans VF", "Inter", "Saans Fallback", "Noto Sans Devanagari", "Noto Sans JP", "Noto Sans KR", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Saans VF | 500 | 96px | 1.02 | -0.035em | fixed | Default two-line landing-page promise. |
| heading-lg | Saans VF | 500 | 56px | 1.06 | -0.025em | fixed | Editorial chapter titles, FAQ headings and closing promise. |
| outcome | Saans VF | 500 | 32px | 1.1 | -0.025em | fixed | Quantified result summaries and plan prices; use the same restraint as headings rather than giant display numerals. |
| heading | Saans VF | 500 | 28px | 1.15 | -0.025em | fixed | Narrow side-column chapter titles, plan names and secondary card titles. |
| intro | Saans VF | 400 | 24px | 1.35 | -0.015em | fixed | Opening support paragraph; also the pricing introduction. |
| faq-question | Saans VF | 500 | 18px | 1.55 | normal | fixed | Editorial accordion questions. |
| body | Saans VF | 400 | 16px | 1.55 | normal | fixed | Editorial explanatory copy and open FAQ answers. |
| footer-link | Saans VF | 400 | 16px | 1.2 | normal | fixed | Footer navigation links. |
| marker | Saans VF | 500 | 14px | 1.55 | normal | fixed | Marginal highlighter labels and plain section labels. |
| availability | Saans VF | 500 | 14px | 1.4 | -0.01em | fixed | Compact opening availability or credibility statement. |
| button | Saans VF | 550 | 14px | 1.2 | normal | fixed | Default conversion buttons. |
| text-link | Saans VF | 380 | 14px | 1.2 | normal | fixed | Underlined secondary actions, often followed by a small chevron. |
| nav | Saans VF | 500 | 13px | 1.4 | normal | fixed | Navigation strip labels. |
| nav-action | Saans VF | 500 | 13px | 1.55 | normal | fixed | Compact sign-in and conversion actions in the header. |
| pager | Saans VF | 550 | 13px | 1.2 | normal | fixed | Numbered demonstration selectors. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| audience and technical product pages | utility-display | Saans VF | 600 | 56px | 1.1 | -0.02em | size clamp(40px,7vw,56px) | Text-led audience or technical opening. |
| pricing pages | pricing-display | Saans VF | 500 | 54px | 1.06 | -0.025em | fixed | Compact two-line promise above the comparison grid. |
| audience and technical product pages | utility-heading | Saans VF | 600 | 38px | 1.1 | -0.02em | fixed | Capability, FAQ and closing-panel headings. |
| audience and technical product pages | utility-intro | Saans VF | 400 | 21px | 1.35 | normal | fixed | Hero and section support paragraphs. |
| audience and technical product pages | feature-title | Saans VF | 600 | 17px | 1.5 | -0.01em | fixed | Small feature-card titles and capability-row leads. |
| audience and technical product pages | feature-body | Saans VF | 400 | 16px | 1.45 | normal | fixed | Cool gray feature-card descriptions. |
| technical product pages | technical-eyebrow | Saans VF | 600 | 16px | 1.2 | 0.16em, uppercase | fixed | Spaced uppercase category labels above the technical introduction and capability sections. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use sentence case throughout the default editorial system. The technical eyebrow is a scoped exception, not the standard chapter label.
- Display and chapter headings stay at weight 500; the cooler utility system is weight 600. Do not average these into one heading style.
- Keep body copy substantially smaller than the 56px chapter titles. Introductory copy rises to 24px, while most explanations remain 16px.
- The same font carries numbers and prose; do not introduce a separate mono face for marketing statistics.

## Layout

**Density:** Airy at chapter scale, compact within the working demonstrations and footer.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Pager gaps and compact header clusters. |
| 12px | Icon-to-label gaps and small content stacks. |
| 16px | Eyebrow-to-title and compact title-to-copy spacing. |
| 20px | Pager-to-caption separation and horizontal primary-button inset. |
| 24px | Main grid gutters, title-to-body gaps, card inset and action-pair gaps. |
| 32px | Opening headline-to-support spacing and larger stack breaks. |
| 40px | Chapter introduction-to-media separation and add-on-card inset. |
| 48px | Footer vertical padding and major internal group gaps. |
| 64px | Default editorial chapter and closing-band vertical padding. |
| 72px | Cool utility sections' vertical padding and the gap to secondary opening integrations. |
| 96px | Large document-grid breaks and pricing bottom inset. |

### Containers and grids

- **editorial-rail**: max width 1360px · 8 columns · gap 24px · side padding 60px. At 1440px the working rail is 1320px wide. Reserve one column for the 144px marginal label; the other seven form a 1152px content field. Preserve this asymmetry instead of centering every heading.
- **opening-split**: 2 columns · gap 24px. Two equal 648px grid halves at desktop. Text occupies the left; a 576px-wide product scene sits within the right half.
- **body-measure**: max width 529px. Support copy beneath full-width chapter titles; let titles extend beyond the paragraph measure.
- **demonstration-track**: 3 columns · gap 24px. 576px-wide sheets in an overflowing horizontal track, with adjacent scenes partially visible; single full-width studies use the 1152px content field.
- **footer-columns**: 5 columns · gap 16px. Five compact link groups across the rail, followed by a separate download and utility area.
- **utility-grid** (only for audience and technical product pages): max width 1360px · 3 columns · gap 24px · side padding 24px. Inside the wider page shell, the content is 1264px wide at desktop; feature cards are about 405px wide. Auto-fill cards with a 320px minimum.
- **pricing-grid** (only for pricing pages): 4 columns · gap 24px. Four equal 312px plan columns across the editorial rail; add-ons switch to two columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 6px |
|  | editorial-sheets | 0px |
|  | locale-control | 2px |
| audience and technical product pages | utility-cards | 10px |
| audience and technical product pages | utility-closing-panel | 12px |
| pricing pages | small-badges | 3px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| product-sheet | `rgba(40, 18, 55, 0.19) 0px 28px 65px -18px` | Lift demonstration windows softly from the paper canvas without a heavy black halo. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default editorial marketing background.

**CSS:** `background: #f7f5f2; color: #241e2b`

#### Putty band · level 0

**Use:** Alternating chapters, navigation and closing call.

**CSS:** `background: #eeebe8`

**Observed:** A very small neutral shift defines a new chapter without introducing a dark theme.

**Transfer:** Use for changes of narrative mode, not as a different background behind every card.

#### Product sheet · level 1

**Use:** Detailed working-interface demonstrations.

**CSS:** `background: #fffdfb; border-radius: 0px; box-shadow: rgba(40, 18, 55, 0.19) 0px 28px 65px -18px`

**Observed:** A flat browser-like sheet with fine edges, a narrow top bar and ruled internal regions. The opening sheet rotates -0.8deg; most chapter sheets remain straight.

**Transfer:** Stage believable product work on a single paper plane; preserve readable hierarchy rather than reproducing every small interface label.

#### Bordered commercial card · level 1

**Only for:** pricing pages

**Use:** Add-ons and referral offer panels.

**CSS:** `background: #fffdfb; border: 1px solid #cec8d0; border-radius: 0px; padding: 40px`

**Observed:** Flat, square commercial panels with no decorative elevation.

**Transfer:** Give the offer, explanation and price or action their own stacked zones.

#### Recommended plan · level 1

**Only for:** pricing pages

**Use:** One emphasized plan column.

**CSS:** `background: #bbaaf9; color: #302036; border-radius: 0px`

**Observed:** The lavender fill runs down the whole long comparison column, not just its header.

**Transfer:** Select one tier only; leave neighboring plans on raised paper.

#### Cool canvas · level 0

**Only for:** audience and technical product pages

**Use:** Shorter text-led product and audience presentation.

**CSS:** `background: #f8faf9; color: #0f1720`

#### Utility card · level 1

**Only for:** audience and technical product pages

**Use:** Icon-and-copy capability grids.

**CSS:** `background: #ffffff; border: 1px solid #e6e6e4; border-radius: 10px; padding: 24px; box-shadow: none`

#### Dark utility close · level 1

**Only for:** audience and technical product pages

**Use:** Contained final conversion invitation.

**CSS:** `background: #0f1720; color: #f8faf9; border-radius: 12px; padding: 72px 0px`

**Observed:** A 1264px-wide contained panel, with centered text and pale actions, not a full-bleed dark footer.

**Transfer:** Keep the cool canvas visible around the panel.

#### Cool footer · level 0

**Only for:** audience and technical product pages

**Use:** Final legal and navigation area.

**CSS:** `background: #f7f7f8; border-top: 1px solid #e6e6e4; padding: 48px 0px`

## Components

### Layered navigation

**Use:** Global identity, conversion and navigation hierarchy.

**CSS:** `background: #eeebe8; border-bottom: 1px solid #cec8d0; padding: 0px 60px; color: #625a69`

**Text style:** `nav` — Saans VF 500 · 13px/1.4

**Observed:** An 80px identity row places a compact wordmark and light descriptive tagline left, with sign-in and conversion actions right. A 44px route strip follows, using a 2px selected underline. Optional contextual strips are 45px high on raised paper. Over the opening photograph, the identity and actions reverse to white; after scrolling, the header becomes putty and remains sticky.

**States:** Declared: hover underlines navigation text and changes it to #241e2b; focus-visible uses a 2px #5530c9 outline with 2px offset.

**Transfer:** Use the contextual strips only when the information architecture needs them; do not enlarge the route labels to match the headline.

### Primary button

**Use:** Main conversion action in editorial sections.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #241e2b; color: #f7f5f2; border: 1px solid transparent; border-radius: 6px; height: 48px; padding: 0px 20px; gap: 12px`

**Text style:** `button` — Saans VF 550 · 14px/1.2

**Observed:** Content-width action, paired with a secondary text link. Header actions use the nav-action recipe, 38px height and 12px horizontal inset. Pricing actions fill their available column width.

**States:** Declared: hover opacity .85 and underline; focus-visible outline 2px solid #5530c9 with 2px offset; active opacity .75.

### Outline button

**Use:** Secondary commercial action or sign-in.

**CSS:** `display: flex; align-items: center; justify-content: center; background: transparent; color: #241e2b; border: 1px solid #241e2b; border-radius: 6px; height: 48px; padding: 0px 20px`

**Text style:** `button` — Saans VF 550 · 14px/1.2

**Observed:** The larger outline variant appears in a commercial offer. Sign-in is the compact 38px-high variant with 12px inset and nav-action text. On photography its border and text reverse to white.

**States:** Declared: hover background-color #eeebe8 and underline; focus-visible outline 2px solid #5530c9 with 2px offset; active background-color #eeebe8.

### Text action

**Use:** Secondary action next to a filled button or below explanatory copy.

**CSS:** `color: #241e2b; text-decoration: underline; display: inline-flex; align-items: center`

**Text style:** `text-link` — Saans VF 380 · 14px/1.2

**Observed:** A small 14px chevron follows the text. Integration actions may lead with a 16px service icon instead.

**States:** Declared: hover underline; focus-visible outline 2px solid #5530c9 with 4px offset.

### Highlighter label

**Use:** Category annotation in the narrow chapter margin.

**CSS:** `background: #77dac1; color: #302036; padding: 0px 4px 0px 0px; box-shadow: rgb(119, 218, 193) 0px 3.8px 0px 0px, rgb(119, 218, 193) 0px -3.8px 0px 0px`

**Text style:** `marker` — Saans VF 500 · 14px/1.55

**Observed:** A rectangular text-width marker rather than a pill. Short labels can wrap in the margin; lavender, peach, lime and blue variants distinguish chapter subjects.

**Transfer:** Write a short conceptual label, not a second headline.

### Demonstration selector

**Use:** Small numbered controls above a horizontal workflow track.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 36px; height: 36px; padding: 0px 8px; border-radius: 6px; background: rgba(36, 30, 43, 0.906); border: 1px solid rgba(36, 30, 43, 0.094); color: #f7f5f2`

**Text style:** `pager` — Saans VF 550 · 13px/1.2

**Observed:** Numbers sit in an 8px-gap row. The selected example is dark; unselected examples use outlined or lightly tinted buttons. A short, small caption sits below the selector and above each scene.

**States:** Declared: selected hover opacity .85; focus-visible outline 2px solid #5530c9 with 2px offset; active opacity .75.

**Transfer:** Use selectors for alternate meaningful cases, not ornamental slide dots.

### Product window

**Use:** Frame for a trustworthy product demonstration.

**CSS:** `background: #fffdfb; border-radius: 0px; box-shadow: rgba(40, 18, 55, 0.19) 0px 28px 65px -18px; position: relative; max-width: 576px`

**Observed:** Narrow gray browser chrome with an ellipsis, a brand-and-context row, small navigation strips and a ruled workspace. The opening window is tilted -0.8deg; larger studies expand to 1152px.

**Transfer:** Show an input, a useful result and the supporting records. If no finished interface exists, build a minimal representative working view in the same frame.

### FAQ row

**Use:** Objection handling on editorial pages.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 16px; padding: 24px 0px; color: #241e2b; border-bottom: 1px solid #cec8d0`

**Text style:** `faq-question` — Saans VF 500 · 18px/1.55

**Observed:** Full-width question text on the left, plus at the far right; the open state uses a cross and reveals a body paragraph beneath. The first answer is open in the editorial examples. The cooler variant uses 21px weight 600 questions with 16px vertical padding and cool rules.

**States:** Declared: focus-visible outline 2px solid #5530c9 with -2px offset and 2px radius.

**Transfer:** Place the longest answers in a narrower reading measure inside the wide accordion.

### Footer link group

**Use:** Quiet multi-column utility navigation.

**CSS:** `display: flex; flex-direction: column; gap: 4px; color: #625a69`

**Text style:** `footer-link` — Saans VF 400 · 16px/1.2

**Observed:** Five groups have slightly stronger headings, links below, and hairline boundaries above and below the group area. Legal copy precedes the groups; download badges and a small copyright line follow, with a 124px by 38px locale control aligned right.

**States:** Declared: link hover underlines and changes color to #241e2b; focus-visible outline 2px solid #5530c9 with 2px offset.

**Transfer:** Preserve the clear legal → navigation → utility hierarchy; include download links only for products with downloads.

### Feature card

**Only for:** audience and technical product pages

**Use:** Compact capability explanations.

**CSS:** `background: #ffffff; border: 1px solid #e6e6e4; border-radius: 10px; padding: 24px; display: flex; flex-direction: column; gap: 12px`

**Text style:** `feature-title` — Saans VF 600 · 17px/1.5 · tracking -0.01em

**Observed:** A 30px outlined icon shares a row with the title; feature-body text sits beneath in half-opacity blue-black. Equal-width cards form a three-column grid without drop shadows.

**Transfer:** Use one literal capability per card and keep the descriptions comparable in length.

### Plan column

**Only for:** pricing pages

**Use:** Dense side-by-side commercial comparison.

**CSS:** `background: #fffdfb; border-radius: 0px; padding: 40px; color: #241e2b`

**Text style:** `heading` — Saans VF 500 · 28px/1.15 · tracking -0.025em

**Observed:** Plan name and icon lead, then an audience or capability statement, short description, an outcome-size price, billing qualifiers, full-width action and long ruled feature lists. One recommended column uses the Recommended plan surface. Tiny rectangular 3px-radius badges mark status. Current-plan action is outlined at opacity .45.

**Transfer:** Align major pricing and action zones across tiers so the long lists compare cleanly.

## Imagery and graphics

### Sunlit domestic photography

**Use:** Shallow opening banner and full-width pauses between demonstration chapters.

**Observed:** High oblique views of people reading a phone, working at a timber table, or discussing papers in a plant-filled home. Large windows cast long geometric shadows over slate floors; woven rugs, pale walls and natural wood keep the palette muted and tactile. The opening image is a panoramic slice; chapter images are 1152px by 768px with square edges and no text overlay.

**Transfer:** Photograph the everyday setting in which the new product gives time or confidence back. Keep people small within the architecture, natural side light, sober greens and warm wood. A single carefully lit interior photograph can serve as both panoramic opening and wider editorial respite.

### Working product scenes

**Use:** The dominant visual proof throughout editorial chapters.

**Observed:** Near-white browser sheets contain real-looking conversations, account or record lists, approvals and simple charts. Lavender marks an input or chosen rule; mint emphasizes useful results; fine gray separators organize dense information. Half-width scenes sit in tracks, while a complete study can occupy the full 1152px content field.

**Transfer:** Replace the subject with an authentic task for the new product. Keep the useful input, resulting output and an audit trail visibly related. A simplified HTML reconstruction is preferable to an unreadable screenshot mosaic.

### Square-pixel wave

**Use:** A required computational counterpoint beside the closing action.

**Observed:** A compact 564px by 188px SVG field of tiny mint squares with scattered lavender squares forms loose wave-like bands. There is no glow, gradient or dark backing; paper remains visible between the cells.

**Transfer:** Use abstract movement or organization rather than a literal product icon. The minimum version is a static square-cell wave in the same two pastels.

**Build:** Use an SVG viewBox of 564 by 188. As a reconstruction recipe, place 5px squares on an 8px lattice; vary occupancy around two shallow sine bands crossing the field. Fill most cells mint and a minority lavender, leaving irregular gaps and open edges. Keep squares crisp, unrounded and unblurred; no connecting lines.

### Segmented signature rule

**Use:** A required colored punctuation device at a major transition and near the footer.

**Observed:** An 8px horizontal line across the 1320px rail; lavender occupies half, pink one quarter and blue one quarter. It has hard joins and no border or radius.

**Transfer:** Use the same restrained strip as a deliberate chapter boundary rather than introducing more colorful section backgrounds.

**Build:** Create an 8px-high grid with grid-template-columns: 4fr 2fr 2fr and gap: 0px. Give its three children #bbaaf9, #f785c9 and #8fc9ff backgrounds.

### Icons

**Observed:** Utility feature icons are 30px or 32px outline SVGs with 2px rounded strokes in blue-black. Text-link chevrons are 14px; compact action and integration symbols are 16px. Simple pictograms appear beside labels rather than inside oversized circular badges.

**Transfer:** Choose a consistent rounded-stroke outline family for capabilities, retaining literal database, shield, document or workflow metaphors. Keep partner symbols small and visually subordinate.

## Section recipes

How recurring sections are built.

### First screen: Life above the working page

**Observed:** The opening layers a sunlit panoramic photograph behind a lower-edge identity-and-action row, followed by ruled navigation strips, then a warm-paper split hero. The image and overlaid identity occupy roughly the first 377px; route and context strips bring the content start to 467px. Below a 32px top inset, a small availability line precedes the 96px two-line headline on the left half, with 16px between label and title and 32px before 24px support copy. A 576px-wide Product window begins alongside the headline, subtly rotated -0.8deg. Within the first 900px, the photograph, navigation, availability, whole headline, support and upper working window are visible; the 48px Primary button begins at the lower edge, while secondary integrations, fine print and the signature rule fall below the fold.

**Transfer:** For a new landing page retain the life-scene-to-working-sheet contrast, a compact descriptive identity and one strong promise broken into two lines. Without finished media, pair a naturally lit everyday photograph with a representative HTML Product window. Audience and technical variants instead open directly beneath navigation with the utility-display recipe, 72px vertical padding, a 21px explanation and pale actions; pricing uses pricing-display and places billing controls opposite the promise.

**Avoid:** Do not turn the opening into a centered startup headline over a gradient, or replace the working sheet with an isolated phone mockup. Do not move every secondary integration into the first viewport.

**Text style:** `display` — Saans VF 500 · 96px/1.02 · tracking -0.035em

### Marginal chapter introduction

**Observed:** Within the editorial-rail, a Highlighter label occupies the narrow left column; heading-lg and a 529.1px-wide body explanation begin in the seven-column content field. The heading-to-support gap is 24px, followed by roughly 40px to media; ordinary chapter padding is 64px. Some compact chapters use heading in a narrower text column next to a much larger product study.

**Transfer:** Use the margin for a short concept and the headline for a benefit; let the same rail carry the rest of the chapter.

**Text style:** `heading-lg` — Saans VF 500 · 56px/1.06 · tracking -0.025em

### Numbered workflow track

**Observed:** A chapter title and explanation lead to Demonstration selector controls, a plain small caption, and 576px Product windows on a 24px-gap track. Adjacent sheets intentionally enter or exit the viewport. The title and controls hold while the examples change through a long scrolling chapter.

**Transfer:** Use two to four complementary cases that demonstrate the same promise. Keep the content readable on each sheet and let the track carry overflow, not the page's text.

**Text style:** `heading-lg` — Saans VF 500 · 56px/1.06 · tracking -0.025em

### Quantified working proof

**Observed:** A full-width Product window follows the marginal chapter heading. Three restrained outcome-size summaries pair a small icon and label with 32px figures; a ruled line chart and supporting records occupy the rest of the sheet. Mint marks the beneficial result and lavender distinguishes a comparison, while caveats stay close to the figures.

**Transfer:** Show a defensible outcome with inputs and qualifications, not an unsupported oversized statistic.

**Text style:** `outcome` — Saans VF 500 · 32px/1.1 · tracking -0.025em

### Editorial photographic pause

**Observed:** A square-cornered 1152px by 768px domestic image fills the content field beneath a detailed collaborative or work-oriented demonstration. No caption panel, color overlay or decorative frame competes with the light and architecture.

**Transfer:** Use a real human context after a dense explanation to restore scale and emotional relevance.

### Wide questions with narrow answers

**Observed:** A plain marginal label and heading-lg introduce a seven-column accordion of FAQ rows. The questions span the field; expanded answers occupy a much narrower measure. A small underlined all-questions action finishes the section. Cooler pages use utility-heading and wider answer paragraphs.

**Transfer:** Choose objections arising from the product's real limitations, permissions, cost or setup rather than generic promotional questions.

**Text style:** `faq-question` — Saans VF 500 · 18px/1.55

### Closing invitation and utility footer

**Observed:** The default close is a 64px-padded Putty band with a marginal identity label, heading-lg promise, body support and Primary button plus Text action on the left; Square-pixel wave occupies the right-hand media space. A Segmented signature rule separates it from legal copy and five Footer link groups on Warm canvas. Pricing replaces the wave area with a bordered referral offer. Cool audience and technical variants close in the Dark utility close surface with centered 38px heading, 21px support and pale actions, followed by a Cool footer; the technical variant also has a centered all-questions link before the footer.

**Transfer:** End on the time or effort the product gives back, followed by a practical action. Preserve the full legal/navigation/utility ending rather than stopping at the conversion panel.

**Text style:** `heading-lg` — Saans VF 500 · 56px/1.06 · tracking -0.025em

### Cool capability presentation

**Only for:** audience and technical product pages

**Observed:** The Cool canvas carries utility-heading, a utility-intro explanation and a 24px-gap three-column Feature card grid. Technical pages add technical-eyebrow labels. Later capability explanations can become full-width rows with a small leading icon, feature-title and gray paragraph; a small pale status badge sits above an unavailable action.

**Transfer:** Use for a short explanatory page where capability breadth matters more than cinematic demonstrations.

**Text style:** `utility-heading` — Saans VF 600 · 38px/1.1 · tracking -0.02em

### Commercial comparison

**Only for:** pricing pages

**Observed:** A compact pricing-display introduction sits left, with a three-part monthly/quarterly/yearly selector, currency control and audience toggle right. Four Plan columns follow, one fully lavender. A putty add-ons band uses a heading-lg lead and a two-column grid of Bordered commercial cards with heading, explanation, hairline and price.

**Transfer:** Keep core tier comparisons parallel; put optional upgrades in a distinct lower band.

**Text style:** `pricing-display` — Saans VF 500 · 54px/1.06 · tracking -0.025em

## Page flow

**Storyline:** Everyday-life promise → concrete capability → working proof → breadth and control → objections → invitation → practical utility ending.

### Flagship editorial landing page

1. **Promise** — A panoramic human scene introduces a split headline-and-working-sheet hero.
2. **Entry point** — Small integration examples and direct installation actions make the first step tangible.
3. **Capability chapters** — Marginal highlighter labels, large benefit headings and numbered workflow tracks explain increasingly capable work.
4. **Quantified proof** — A full working sheet shows restrained figures, charts, supporting records and caveats.
5. **Human context** — Broader collaboration examples alternate with sunlit photographic pauses.
6. **Control and trust** — A smaller text column sits beside a detailed activity and permissions demonstration.
7. **Objection handling** — Wide ruled accordion with the initial answer open.
8. **Closing call** — Putty invitation with a pixel-wave ornament, then a segmented rule and the complete footer.

**Transfer:** Choose the chapter count and order for the new product; preserve the alternation of useful demonstrations and human context rather than copying every topic.

### Concise audience landing page

1. **Promise** — Direct text-led opening in the cool utility theme.
2. **Capability breadth** — Three-column icon-and-copy card grid.
3. **Product choice** — Two unboxed product introductions with small actions.
4. **Objection handling** — Compact full-width FAQ rows.
5. **Closing call** — Contained dark panel above a cool legal and five-column utility footer.

**Transfer:** Use this condensed variant for a clearly defined audience; it does not need the flagship demonstration sequence.

### Technical product explanation

1. **Promise** — Breadcrumb, tracked uppercase eyebrow, utility-display title, practical explanation and paired actions.
2. **Mechanism** — A card grid describes compatibility, setup and boundaries.
3. **Capability detail** — Icon-led full-width rows explain actual operations, including status qualifiers.
4. **Compatibility proof** — A short partner-logo marquee supplies breadth without a large testimonial block.
5. **Objection handling** — Authentication and access questions in a ruled accordion.
6. **Closing call** — Contained dark invitation, a separate all-questions link and the cool footer.

**Transfer:** Explain how the product fits an existing workflow, identify permissions precisely and give a documentation action alongside signup.

### Pricing and purchase decision

1. **Promise** — Short benefit-led heading opposite billing and audience controls.
2. **Pricing** — Four aligned long plan columns with one lavender recommendation.
3. **Expansion** — Putty band with a two-column add-on grid.
4. **Objection handling** — Editorial FAQ makes trial and billing terms explicit.
5. **Closing call** — Free-entry invitation paired with a separate referral panel.
6. **Utility ending** — Segmented colored rule, legal copy, five navigation groups, downloads and locale control.

**Transfer:** Lead with the value model; isolate optional purchases and rewards from the core tier comparison.

## Writing

Practical, humane and confident without sounding omnipotent. Benefits are explained through ordinary tasks and visible work, with boundaries and qualifications stated directly.

**Do not copy:** Do not reuse Era's name, wordmark, product names, photography, partner identity assets, financial results, country coverage, regulatory language, pricing, referral rewards or customer scenarios as claims for another product. Source quotations here illustrate tone only.

- **Addressing the reader:** Address the reader as you and your. Use the product's name for the actor and we for operational explanations; make the reader's approval and choices explicit.
- **Rhythm:** Short sentence-case benefit headlines, commonly four to nine words, followed by one concrete explanatory sentence. Longer technical and billing explanations use plain sequential sentences rather than slogans. Exclamation marks are not part of the voice.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A broad new possibility expressed through the reader's familiar domain. | 5–9 words | “A new era for your money.”<br>“Personal finance that pays for itself.” |
| Chapter heading | Start with a plain verb or name a reduced burden; promise one useful change. | 4–10 words | “Keep your financial documents in one place.”<br>“Get help with the big decisions.” |
| Supporting line | Explain an action and its guardrails using specific nouns. | One or two sentences | “Approve actions one by one, or let a routine run within your limits. Change those limits or pause the routine whenever you need.” |
| Technical heading | Describe the connection or behavior in ordinary language before adding implementation detail. | 4–8 words | “Connect once, then just ask”<br>“Typed tools, not text dumps” |
| Primary action | Imperative verb with a low-friction qualifier or clear destination. | 2–5 words | “Get started free”<br>“Read the setup docs” |
| Closing line | Return from features to the reader's life and time. | 6–10 words | “Make room for the rest of your life.” |
| FAQ question | Ask the direct question a cautious buyer would ask. | 4–10 words | “Can my AI assistant move money?”<br>“Can I try a paid plan before paying full price?” |

**Words and phrasing to use:** one place; together; connect once; your limits; approve; review; routine; show; keep; free to start; what changes the answer

**Avoid:** revolutionary; unleash; limitless; magic; guaranteed gains; frictionless ecosystem; game-changing

**Rules:**

- Translate capabilities into everyday work before naming the underlying technology.
- Put an important permission, beta status or billing qualification near the action it qualifies.
- Give examples enough specificity to be intelligible, and label hypothetical outcomes honestly.
- Keep secondary labels utilitarian; do not make every marginal label a miniature campaign slogan.

## Do's and Don'ts

### Do

- Keep the default 96px display and 56px chapter hierarchy at weight 500, with the measured tight tracking.
- Use the 144px marginal label column and 24px gutter to anchor editorial chapters.
- Keep the signature color rule 8px high with 4:2:2 segments and hard joins.
- Pair 48px filled buttons with quiet 14px underlined actions rather than matching large buttons.
- Use the purple-tinted product-sheet shadow only where an interface needs physical separation.
- Let sunlit wide photographs interrupt dense demonstrations without explanatory overlays.
- Keep a recommended pricing tier lavender all the way through its feature list.
- End with legal context, five compact link groups and a separate utility row after the conversion invitation.

### Don't

- Do not apply the cooler variant's weight 600 headings to the default editorial landing page.
- Do not round the principal demonstration windows or commercial cards to the utility cards' 10px radius.
- Do not replace pastel highlighter rectangles with pill tags or circular icon backgrounds.
- Do not spread lavender, mint and pink into full-viewport gradients; their ordinary role is annotation and punctuation.
- Do not turn 32px outcome summaries into huge hero statistics detached from supporting work.
- Do not put deep black shadows under flat feature cards; those use a 1px cool edge and no shadow.
- Do not enlarge navigation labels beyond the compact 13px recipe to fill the generous header space.
- Do not extend the contained blue-black utility close into a full dark-page theme.

## Motion and responsive

### Motion

**Observed:**

- Default text actions declare color .15s cubic-bezier(.16, 1, .3, 1). Numbered selectors declare background-color, border-color and color transitions with the same duration and easing.
- The opening product sheet declares a .3s reveal using cubic-bezier(0, 0, .2, 1) on a view timeline.
- Workflow tracks use sticky content and numbered changes as the page scrolls.
- The partner-logo strip declares a 29s linear infinite marquee.

**Transfer:**

- Keep demonstrations spatially stable while changing the selected example; retain a clear numbered selected state.
- Use the short declared color transitions for interaction rather than adding prominent spring effects.
- Keep the square-pixel ornament legible as a static field; animation is not necessary to its identity.

**Unknown:**

- Exact scroll-to-track mapping and pixel-wave animation timing are not established.

### Responsive

**Observed:**

- The utility hero declares clamp(40px,7vw,56px). Feature grids use auto-fill with minmax(min(320px, 100%), 1fr).
- Declared width breakpoints include 600px, 768px, 1024px, 1200px and 1280px; mobile compositions are not specified here.

**Transfer:**

- As a design adaptation, stack the opening text and product sheet when the two halves cannot keep their reading width; keep the photograph shallow and the headline dominant.
- Move marginal highlighter labels above their headings when the rail becomes too narrow, retaining square marker geometry.
- Keep each workflow sheet readable in a horizontally navigable track rather than shrinking every interface to fit a multi-column row.
- Allow auto-fill feature cards to become fewer columns while retaining 24px gaps; preserve the 8px signature rule and its segment proportions.

**Unknown:**

- Exact mobile header, pricing-comparison behavior and editorial display scaling are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
