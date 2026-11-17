# Ingmar Coenen — monolithic letters, slender stories

## Overview

An outsized geometric word sculpture meets delicate condensed serif statements and very small utilitarian sans-serif copy. The default is a white, image-led editorial canvas, with deep plum and burnt orange reserved for immersive informational variants. It suits creative products and design-led services that can communicate through art-directed work rather than dense persuasion: visually expansive, verbally compact, and deliberately asymmetric.

### Essentials

- Identity acts as architecture: a near-edge-to-edge geometric word sculpture occupies a 1432×266px band at a 1440px viewport, above tiny navigation.
- The promise lives at the far right, not in the center: a 466px-wide, 36px/0.94 condensed serif statement sits in the last third of the opening, leaving the other two thirds open.
- Controls look like small editorial tabs: 34px-high pills, 100px radii, 13px/1.1 sans-serif text with -0.02em tracking, separated by 4px gaps.
- Color belongs primarily to the work: the default canvas is white with charcoal copy and black identity; full-bleed plum/lilac and orange/gray are separate informational themes, not scattered accent cards.
- Proof is staged as a nearly seamless exhibition: two columns of 710×798px image or video panels, 4px gutters, 8px outer margins, and 12px visible media corners. Use art-directed product compositions when no portfolio imagery exists.
- Endings remain unusually spacious: a 60px monochrome logo rail leads to a 480px footer with six-column alignment, tiny contact and social links at the top, and 320px of breathing room before the legal baseline.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black identity | `#000000` | `--color-ink` | text, background, action | Geometric identity artwork, selected controls, primary actions, and small navigation text. |
| Charcoal copy | `#3a4042` | `--color-text` | text, link | Default serif introduction, body copy, and footer links. |
| Silver gray | `#cccccc` | `--color-muted` | text, surface | Muted footer details; identity, copy, and pill surfaces on the warm editorial theme. |
| Pale gray control | `#f2f2f2` | `--color-control` | surface, border | Resting navigation pills and the faint edge on controls. |
| White canvas | `#ffffff` | `--color-canvas` | background, text, surface | Default page ground, reverse button labels, and the visible white of the floating navigation; its glass recipe uses white at 96% opacity. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and biography pages | Burnt orange | `#d97127` | `--color-orange` | background | Continuous warm editorial ground, paired with silver-gray identity and copy. |
| expertise and service-detail pages | Deep plum | `#280a1c` | `--color-plum` | background, text | Whole-page ground and reversed pill text for the dark expertise theme. |
| expertise and service-detail pages | Pale lilac | `#dcc7df` | `--color-lilac` | text, surface | Identity, copy, links, and navigation pills on the dark expertise theme. |

## Typography

- **Neue Haas Unica Pro** — Navigation, compact body paragraphs, lists, footer, and capability labels. A medium-cut neo-grotesk with an understated editorial utility character. If unavailable, use **Inter**. Use 500 with the same tight tracking; keep paragraphs small and compact. Font stack: "Neue Haas Unica Pro", "Inter", Arial, sans-serif.
- **ITC Garamond Std Light Condensed** — Opening statements and conversational closing invitations. Very narrow, light old-style serif with pronounced thick/thin contrast and tall, delicate forms. If unavailable, use **Cormorant Garamond**. Use 300 and condense horizontally if needed to preserve narrow line lengths. Font stack: "ITC Garamond Std Light Condensed", "Cormorant Garamond", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | ITC Garamond Std Light Condensed | 300 | 36px | 0.94 | normal | Main introduction in the rightmost third of the page. |
| body | Neue Haas Unica Pro | 500 | 13px | 1.1 | -0.02em | Shared compact recipe for body paragraphs, navigation, numbered lists, links, and footer copy. |
| media-caption | Neue Haas Unica Pro | 500 | 12px | 1.1 | -0.02em | Small status labels placed over media. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| expertise and company pages | closing-statement | ITC Garamond Std Light Condensed | 300 | 54px | 1 | -0.01em | Two-line conversational invitation with the address inline on the second line. |
| expertise and service-detail pages | chapter-heading | Neue Haas Unica Pro | 500 | 24px | 1 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Unboxed capability chapter names in the middle column. |

**Notes:**

- The giant identity is vector artwork, not an enlarged body heading. Keep its block-like construction distinct from the fragile serif statement.
- The serif lead uses slightly overlapping vertical rhythm, while utility text uses a compact 1.1 line height. Do not introduce a conventional ladder of bold sans-serif marketing headings.
- The medium sans-serif and light serif are separate cuts; retain their visual contrast even when substituting families.

## Layout

**Density:** Airy at section scale and very compact within text and controls; long empty fields make small editorial material feel intentional.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Pill groups and exhibition-grid gutters. |
| 8px | Media-grid outer margin and media-caption inset. |
| 10px | General content edge padding and compact content gaps. |
| 16px | Floating navigation inset and service-section padding. |
| 20px | Paragraph separation. |
| 24px | Space from the opening navigation area to the statement. |
| 80px | Capability chapter gaps and exhibition bottom spacing. |
| 104px | Top and bottom spacing around the dark-theme closing invitation. |
| 320px | Opening breathing room and footer bottom breathing room. |
| 360px | Long separation between introductory and detailed prose on informational pages. |

### Containers and grids

- **edge-to-edge identity**: side padding 4px. Full-width graphic identity with almost no side margin; 1432px wide at a 1440px viewport.
- **editorial thirds**: 3 columns · gap 10px · side padding 10px. Full-width grid, not a centered max-width container. The statement and long-form prose occupy the last third, about 466px; chapter labels use the middle third.
- **exhibition grid**: 2 columns · gap 4px · side padding 8px. Equal-width, slightly portrait panels; each is 710×798px at desktop.
- **footer alignment**: 6 columns · gap 4px · side padding 10px. Six equal desktop columns of about 233px. Contact starts in the first column; greeting and social links occupy the fifth and sixth.

## Corner radius

| Element | Radius |
| --- | --- |
| navigation pills | 100px |
| floating navigation | 200px |
| media panels | 12px |
| current-page marker | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating navigation | `rgba(0, 0, 0, 0.03) 0px 0.6px 0.6px -1px, rgba(0, 0, 0, 0.03) 0px 2.3px 2.3px -2px, rgba(0, 0, 0, 0.02) 0px 10px 10px -3px` | Only the floating white navigation; panels themselves remain flat. |

### Surfaces

#### White exhibition canvas · level 0

**Use:** Default marketing-page ground.

**CSS:** `background: #ffffff; color: #3a4042`

**Observed:** A continuous white field connects the opening, work grid, proof rail, and footer.

**Transfer:** Let media supply the chromatic variety instead of adding alternating colored section bands.

#### Floating white capsule · level 2

**Use:** Persistent navigation while moving through content.

**CSS:** `background: rgba(255, 255, 255, 0.96); border-radius: 200px; backdrop-filter: blur(7px); box-shadow: rgba(0, 0, 0, 0.03) 0px 0.6px 0.6px -1px, rgba(0, 0, 0, 0.03) 0px 2.3px 2.3px -2px, rgba(0, 0, 0, 0.02) 0px 10px 10px -3px`

**Observed:** The capsule floats above imagery or colored editorial grounds, with dark links and a black action.

**Transfer:** Reserve translucency and elevation for this navigation layer.

#### Dark expertise canvas · level 0

**Only for:** expertise and service-detail pages

**Use:** Immersive text-led informational theme.

**CSS:** `background: #280a1c; color: #dcc7df`

**Observed:** Plum continues uninterrupted through the footer; identity and text become lilac.

**Transfer:** Use the complete pairing throughout a page rather than isolated plum cards.

#### Warm editorial canvas · level 0

**Only for:** company and biography pages

**Use:** Personality-led editorial theme.

**CSS:** `background: #d97127; color: #cccccc`

**Observed:** Orange fills the complete page, including its unusually open footer.

**Transfer:** Keep the same grids and type hierarchy while changing the ground and foreground pair.

## Components

### Floating navigation

**Use:** Navigation after the large identity has left the main view.

**CSS:** `position: fixed; height: 60px; border-radius: 200px; background: rgba(255, 255, 255, 0.96); backdrop-filter: blur(7px); padding: 10px 0px; z-index: 3`

**Text style:** `body` — Neue Haas Unica Pro 500 · 13px/1.1 · tracking -0.02em

**Observed:** Inset roughly 16px from the viewport sides. Three plain links sit at left and a black project-action pill at right; a tiny dot marks the current page. The opening instead uses individual pale pills beneath the identity.

### Primary pill

**Use:** Conversion action in the floating navigation.

**CSS:** `background: #000000; color: #ffffff; height: 34px; border-radius: 100px; padding: 9px 14px 0px; display: flex; gap: 4px`

**Text style:** `body` — Neue Haas Unica Pro 500 · 13px/1.1 · tracking -0.02em

**Observed:** A bent arrow precedes the action. The label is compact and left-aligned inside the pill, not a large centered banner.

**Transfer:** Use a short verb-led action and retain the small arrow.

### Opening navigation pill

**Use:** Navigation and action row immediately beneath the word sculpture.

**CSS:** `background: #f2f2f2; color: #000000; height: 34px; border-radius: 100px; padding: 9px 14px 0px; display: flex; gap: 4px`

**Text style:** `body` — Neue Haas Unica Pro 500 · 13px/1.1 · tracking -0.02em

**Observed:** Three pills group at the left; the conversion pill aligns to the far right. Current-page pills include a 4px circular marker and 20px left padding. Dark expertise pages use lilac pills with plum text; warm company pages use gray pills with black text.

### Media panel

**Use:** Large visual proof without a conventional card body.

**CSS:** `border-radius: 12px; overflow: hidden; aspect-ratio: 710 / 798; object-fit: cover`

**Observed:** Images and videos occupy the entire panel. There is no separate title-and-description footer. Occasional tiny status text sits 8px inside the upper-left edge.

**Transfer:** Use an art-directed scene of the new product, not a generic icon tile.

### Arrow text link

**Use:** Compact footer destinations.

**CSS:** `color: #3a4042; text-decoration-line: underline`

**Text style:** `body` — Neue Haas Unica Pro 500 · 13px/1.1 · tracking -0.02em

**Observed:** Bent arrows form a narrow leading column; the destination labels form a vertically stacked underlined list.

**States:** Declared: hover keeps charcoal color and underline on destination labels; arrow-only links keep no underline; focus-visible behavior is unspecified.

**Transfer:** Keep arrows visually separate from the underlined words.

### Spacious footer

**Use:** Shared contact and utility ending.

**CSS:** `padding: 10px 10px 320px; display: flex; gap: 4px; color: #3a4042`

**Text style:** `body` — Neue Haas Unica Pro 500 · 13px/1.1 · tracking -0.02em

**Observed:** An upper contact row uses six-column alignment, with deliberate empty columns between contact and social destinations. A separate bottom utility row completes the 480px footer. It inherits the page ground; colored themes also inherit their light foreground.

### Monochrome proof rail

**Use:** A low-profile trust device before the footer.

**CSS:** `height: 60px; overflow: hidden; display: flex; align-items: center`

**Observed:** Many small monochrome client marks spread horizontally across the full width without cards, captions, or oversized logo containers. Marks are dark on white and light on colored grounds.

**Transfer:** Use legitimate customer, integration, or credential marks; if unavailable, make a restrained typographic proof rail of verified categories or compatible tools.

### View switch

**Only for:** work or product-exhibition indexes

**Use:** Compact mode choice above a repeated media grid.

**CSS:** `display: flex; gap: 4px; padding: 14px 8px 14px 14px`

**Text style:** `body` — Neue Haas Unica Pro 500 · 13px/1.1 · tracking -0.02em

**Observed:** Two separate 34px-high pills; the selected Grid option is black with white text, while List is white with black text. The pair stays at the left edge, with most of the row empty.

### Numbered capability row

**Only for:** expertise and service-detail pages

**Use:** Detailed service explanation without boxed feature cards.

**CSS:** `display: flex; gap: 10px; padding: 0px 10px 4px; color: #dcc7df`

**Text style:** `body` — Neue Haas Unica Pro 500 · 13px/1.1 · tracking -0.02em

**Observed:** A chapter heading occupies the middle third and its compact description plus numbered subitems occupies the final third. Numbering uses parenthesized two-digit hierarchies. Rows are separated by 80px; a small square media scene occupies the left region.

**Transfer:** Replace services with meaningful product capabilities, retaining the aligned number column and unboxed prose.

### Conversational closing link

**Only for:** expertise and company pages

**Use:** Large editorial invitation before the proof rail.

**CSS:** `font-size: 54px; line-height: 1; letter-spacing: -0.01em; color: #dcc7df`

**Text style:** `closing-statement` — ITC Garamond Std Light Condensed 300 · 54px/1 · tracking -0.01em

**Observed:** Two lines start at the middle third, not the page center. The second line continues directly into a linked email address. The warm theme uses gray text instead of lilac.

**States:** Declared: hover on the dark-theme address retains lilac and no underline; on the warm theme it changes to white with an underline; focus-visible behavior is unspecified.

**Transfer:** Use a short human question followed by a direct contact route, not a form panel.

## Imagery and graphics

### Geometric word sculpture

**Use:** Signature identity device at the top of every page.

**Observed:** A flat single-color vector name fills nearly the whole width. Extreme black geometric letterforms join rectangular masses, broad curves, circular counters, and very narrow gaps; the visible artwork is about 236px tall inside a 266px band at desktop. It reverses to lilac or gray on themed grounds.

**Transfer:** Create an original graphic treatment of the new product name. A minimum viable version is a heavy geometric wordmark converted to outlines, width-fitted to the band, with tightened spacing and simplified counters.

**Build:** Use a responsive SVG with a 1432×266 viewBox. Draw or outline a short word with flat fills, no strokes or shadows; occupy almost the full horizontal span and about 236px vertically. Combine rectangular stems, semicircular bowls, and circular holes. Use black on white, lilac on plum, or gray on orange. Preserve the graphic proportions as width changes rather than treating this as body text.

### Art-directed proof panels

**Use:** Dominant visual material in the exhibition grid.

**Observed:** Panels alternate tactile material photography, graphic identity studies, device mockups, and website presentations. Examples include close oak joinery, phones on a soft gray stage, a browser composition centered in deep green, a warm lamp scene behind an interface, a rocky sculptural phone scene, and a dramatically lit monochrome portrait. Each panel has its own art direction; UI compositions often occupy the middle of a much larger colored or photographic backing.

**Transfer:** Make each panel a complete visual argument: place a real interface or product object on a considered material, neutral studio stage, or saturated field. If photography is unavailable, use a clean product render or interface on a deliberately composed backing. Preserve the balance of near-monochrome scenes and occasional intense color; do not spread the colors of individual projects into the page chrome.

### Small circular scene study

**Only for:** expertise and service-detail pages

**Use:** A single supporting media object beside the chapter list.

**Observed:** A 320×320px rounded white square shows a loose ring of softly shaded circular portrait bubbles around a pale sculptural emblem. Its light, soft-edged forms contrast with the flat dark page.

**Transfer:** Use a compact explanatory animation or arranged product-detail collage with soft dimensional circles on a white square, rather than another full-width hero.

**Build:** Within a 320px white square with 12px corners, arrange about six pale gray or lilac circular masks around a central opening. Add very soft internal shading and place authentic small subject images inside the masks. Keep this light media treatment confined to the square.

### Icons

**Observed:** Iconography is mainly typographic: a bent rightward arrow before actions and links, plus 4px solid circular current-page markers. There is no broad decorative icon system.

**Transfer:** Use simple text-weight bent arrows aligned to the 13px labels and solid dots for active locations; avoid introducing large feature-icon badges.

## Section recipes

How recurring sections are built.

### First screen: Word sculpture and right-column promise

**Observed:** The white ground is the back layer. A black geometric identity fills a 1432×266px top band with only 4px side padding. Immediately beneath it, Opening navigation pills group at left and an action aligns far right. The 36px condensed serif statement begins below the row in the last third, about 466px wide; its first line is indented while subsequent lines align to that column. The left two thirds remain open. About 320px of breathing room sits below the statement. Within the first 900px the identity, navigation, complete statement, and View switch are visible; the large visual proof grid starts just below the fold. The Floating navigation is not layered over the initial identity.

**Transfer:** Use the product name as the graphic object and write a short, specific serif promise in the last third. No product photography is needed for this first screen. Informational pages keep the same identity and right-column introduction but use the complete dark or warm theme and continue into compact prose instead of the view switch.

**Avoid:** Do not turn this into a centered SaaS headline with a screenshot underneath, or shrink the identity to a conventional small corner logo.

**Text style:** `statement` — ITC Garamond Std Light Condensed 300 · 36px/0.94

### Nearly seamless exhibition

**Observed:** The exhibition grid uses Media panels in two equal columns with 4px gaps and 8px outer margins. Image and video compositions are the content; status labels use media-caption. A final unpaired panel is allowed, followed by 80px of separation before the proof rail.

**Transfer:** Curate a sequence of product scenes or demonstrations with genuinely different art direction, keeping the consistent panel geometry rather than a fixed project count.

**Text style:** `media-caption` — Neue Haas Unica Pro 500 · 12px/1.1 · tracking -0.02em

### Proof rail and open footer

**Observed:** The Monochrome proof rail occupies a 60px strip. The Spacious footer follows with a contact block at left and greeting plus Arrow text links in the final two columns. Most of the 480px area is unoccupied; location/copyright and legal destinations sit on a separate low baseline. The page ground continues unchanged to the bottom.

**Transfer:** Make the ending a calm directory, with contact easy to find and proof kept visually small. The image-led default ends here without an additional large serif invitation.

**Text style:** `body` — Neue Haas Unica Pro 500 · 13px/1.1 · tracking -0.02em

### Right-aligned editorial chapters

**Only for:** expertise and company pages

**Observed:** The last third holds dense 13px prose, while the middle third carries short labels. The expertise variant uses 24px chapter headings, Numbered capability rows, and a small left-side media study. The company variant uses the body recipe for modest labels, long customer-name lists, and dated résumé entries, retaining broad empty space to the left.

**Transfer:** Use this for capabilities, company context, a chronology, or technical detail. Keep labels in the middle column and explanatory content in the right column; do not fill every empty region.

**Text style:** `body` — Neue Haas Unica Pro 500 · 13px/1.1 · tracking -0.02em

### Large conversational invitation

**Only for:** expertise and company pages

**Observed:** The Conversational closing link spans two 54px serif lines starting at the middle third. The dark variant has 104px top and bottom padding around the invitation; the warm variant uses a more compact 240px overall section. A Monochrome proof rail follows after the closing space.

**Transfer:** Adapt the question and contact route to the new business, preserving the inline action and narrow serif rather than introducing a colorful CTA box.

**Text style:** `closing-statement` — ITC Garamond Std Light Condensed 300 · 54px/1 · tracking -0.01em

## Page flow

**Storyline:** graphic identity → concise promise → visual or editorial proof → optional direct invitation → monochrome trust rail → spacious contact directory

### Image-led marketing or product exhibition

1. **Identity and promise** — Full-width word sculpture, small navigation, and a serif introduction isolated in the final third.
2. **Visual proof** — Compact view switch followed by a nearly seamless two-column sequence of art-directed media.
3. **Trust and contact** — Small monochrome marks lead directly to the open contact footer, without a large closing headline.

**Transfer:** Use this as the default for a landing page whose value can be demonstrated visually; replace the work collection with product use cases or designed outcomes.

### Expertise and service explanation

1. **Promise** — Lilac identity and a right-column serif statement on continuous plum.
2. **Positioning** — Compact right-column paragraphs with a long vertical separation from the opening statement.
3. **Capability chapters** — Small left media study, middle-column chapter labels, and right-column numbered descriptions.
4. **Closing call** — Two-line serif invitation and inline contact link.
5. **Trust and contact** — Monochrome rail and spacious inherited-color footer.

**Transfer:** Use for service detail or product capability depth, where concise text must explain the visual promise.

### Company or founder context

1. **Point of view** — Gray word sculpture and serif positioning statement on a continuous warm ground.
2. **Human context** — Compact biographical prose and short lettered principles in the last third.
3. **Credibility** — Middle-column labels with long right-column customer and dated experience lists.
4. **Closing call** — Large serif conversational contact invitation.
5. **Trust and contact** — Monochrome rail and open footer continue the warm theme.

**Transfer:** Use for company history, team point of view, or credentials without converting the content into boxed stat cards.

## Writing

Direct, personal, and confident without sounding corporate. It combines craft-focused conviction with conversational warmth, using precise work descriptions rather than hype.

**Do not copy:** Do not reuse the source person's name, wordmark artwork, email address, biography, client marks, employer references, project imagery, career dates, or unverified experience and performance claims. Source quotations below demonstrate voice only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The speaker uses first-person singular and contractions, addressing prospective collaborators implicitly. For a product or team, use a consistent first-person plural with the same directness.
- **Rhythm:** The opening is a short multi-sentence statement rather than a slogan. Detailed paragraphs stay compact; labels and list items are terse. The closing uses a short question and a direct invitation, with no exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | State what the speaker helps achieve, then name the work or approach in ordinary language. | About 35–50 words | “I help good ideas take shape, stand out, and stick around.” |
| Positioning support | Use a concrete conviction and contrast it with what the speaker refuses to optimize for. | Two or three compact sentences | “I don't design to play it safe.” |
| Capability label | Plain noun phrase, no marketing superlatives. | Two or three words | “Digital Experiences”<br>“Product Narrative” |
| Primary action | Brief, direct invitation to begin a conversation. | Three words | “Start a project” |
| Closing invitation | A human question followed by a simple conversational response. | About eight words before the contact route | “Got a project in mind? Let’s talk” |

**Words and phrasing to use:** take shape; clarity; craft; intention; clear, useful; honesty; originality; Let’s talk

**Avoid:** revolutionary; best-in-class; 10x; unlock your potential; game-changing; vanity metrics as proof

**Rules:**

- Prefer a specific description of the work over an abstract benefit slogan.
- Use a small number of convictions and make the following proof substantiate them.
- Keep navigation literal and short; keep the contact invitation human.
- Use hierarchical numbering only where it clarifies a real set of capabilities.

## Do's and Don'ts

### Do

- Keep the lead at 36px with a 0.94 line height and the compact utility copy at 13px/1.1.
- Give the identity a full-width 266px graphic band at desktop.
- Preserve the last-third alignment of the introductory statement and detailed prose.
- Stage the main visual proof in 710×798px panels with 4px gutters at desktop.
- Keep ordinary actions 34px high with 100px radii and small arrow labels.
- Use the 60px monochrome proof rail as a bridge into the footer.
- Retain the 320px footer breathing room rather than expanding its text.
- Use plum/lilac or orange/gray as complete scoped page themes.

### Don't

- Do not use the 54px closing recipe as the default opening headline; the ordinary lead is 36px.
- Do not add drop shadows or raised white card bodies to the media exhibition.
- Do not enlarge the utility copy into a conventional 18px marketing-body system.
- Do not turn each numbered capability into an icon badge with a rounded background.
- Do not carry project-specific neon, green, or photographic colors into the global navigation.
- Do not give the white canvas a narrow centered max-width container with wide side gutters.
- Do not replace the small proof marks with oversized boxed sponsor tiles.
- Do not add gradients, outlines, or dimensional shadows to the flat word sculpture.

## Motion and responsive

### Motion

**Observed:**

- A floating navigation capsule is visible over scrolled content while the opening uses its own inline pill row.
- The exhibition and small expertise study include video media.
- No action or surface transition durations are established.

**Transfer:**

- Keep the inline opening row and floating navigation as distinct presentations.
- Use moving media inside the same panel geometry as still media; preserve a coherent still composition.

**Unknown:**

- Exact scroll-trigger timing, easing, media playback behavior, and logo-rail movement are not established.

### Responsive

**Observed:**

- Width boundaries are declared around 810px and 1440px.
- The desktop composition is full-width and uses two-column exhibition, three-column editorial, and six-column footer alignment.

**Transfer:**

- On narrow layouts, scale the vector identity proportionally and stack the exhibition panels rather than compressing their compositions.
- Collapse editorial columns into label-then-content order, keeping the distinction between fragile serif statements and compact sans-serif details.
- Keep the contact block and social list separated in the footer even when six-column alignment no longer fits.

**Unknown:**

- Exact mobile font sizes, spacing, navigation substitution, and column-collapse rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
