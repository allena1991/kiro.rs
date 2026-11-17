# incident.io — editorial warmth under pressure

## Overview

An approachable technical style with bookish serif headlines, matter-of-fact sans-serif explanations and warm coral light. White and oatmeal spaces alternate with luminous orange scenes, layered interfaces and human customer photography. It suits sophisticated software that needs to feel capable without becoming cold, with spacious storytelling around relatively dense product demonstrations.

### Essentials

- Bookish authority rather than startup shouting: regular-weight serif headlines at 80px/1 with -0.04em tracking, stepping down to 44px/1.1 and 36px/1.15; explanatory text stays in a plain sans.
- A promise above a small product theatre: the centered opening uses a 794px text measure, two balanced headline lines, a 24px support line and paired 49px pill actions, followed by a broad cream-to-coral stage entering the first screen.
- Color behaves like heat, not wallpaper: most reading sits on white or #f8f5f0; #f25533 marks actions and thin active rules, then expands into a concentrated luminous demonstration band and the closing atmosphere.
- Soft pills against restrained rectangles: conversion actions use 9999px radii and 12px 20px padding; panels use 8px corners, story cards 12px and bright capability tiles 16px. Do not round every object into the same shape.
- Interfaces become layered objects: a large pale application window anchors smaller phone, chat or terminal panels over a warm glow. Every new landing page needs an equivalent staged demonstration; without mature UI, use a carefully typeset workflow with a few connected result cards.
- Proof feels like an editorial desk: large customer imagery sits beside serif storytelling, small white quote cards sit inside cream capability panels, and the prominent story selector uses a fanned stack of photographic cards rather than a generic logo carousel.
- The ending is a warm crescendo: a centered 80px white serif closing line shares one continuous coral-and-amber light field with a four-column footer; fine vertical rules and 16px serif column labels keep the glowing ending orderly.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral ember | `#f25533` | `--color-coral` | action, link, accent, background | Primary actions, discovery links, active underlines, selected figures and atmospheric gradients. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Golden stage light | `#f5cd8c` | `--color-hero-light` | accent | Hero glow source at 0.9 alpha, further softened by blur and layer opacity. |
| Amber light | `#f1c592` | `--color-amber-glow` | accent, background | Use at 0.5–0.55 alpha in the broad closing glow, blending into coral rather than appearing as a flat fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black headline | `#000000` | `--color-headline` | text | Default serif headlines and strongly contrasted details. |
| Charcoal ink | `#161618` | `--color-ink` | text, background | Primary sans-serif text and dark photographic backing. |
| Navigation ink | `#111827` | `--color-nav-ink` | text | Compact top navigation labels. |
| Secondary ink | `#656567` | `--color-muted` | text | Visible result of rgba(22,22,24,0.66) on white; retain that alpha on cream surfaces. |
| Deeper oatmeal | `#f1ebe2` | `--color-sand` | surface | Nested media backing, demonstration chrome and secondary-action hover. |
| Soft charcoal edge | `#ececed` | `--color-edge` | border | Visible rgba(22,22,24,0.08) edge on white; use the alpha recipe on tinted panels. |
| Oatmeal paper | `#f8f5f0` | `--color-cream` | surface, background, action | Capability panels, quieter bands and secondary buttons; also the culture-page canvas. |
| Warm white button label | `#f7f7f8` | `--color-action-label` | text | Text on coral conversion actions. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default page canvas, elevated cards and inverted headlines. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| announcements and culture artwork | Wine red | `#5a0a17` | `--color-burgundy` | background, accent | Short announcement strip; ticket and envelope artwork. |
| light footer variants | Peach divider | `#fabbae` | `--color-peach-edge` | border | Vertical footer dividers in light endings. |
| culture pages | Benefit ribbon pink | `#ffd2d9` | `--color-pink` | background | Tilted typographic culture ribbon. |
| customer stories | Article heading ink | `#101828` | `--color-article-ink` | text | Sans-serif long-form chapter titles. |
| pricing comparisons | Table rule | `#e5e7eb` | `--color-table-rule` | border | Dense comparison-table dividers. |

## Typography

- **STKBureauSerif** — Display headlines, section titles, editorial quotes and small footer headings. A substantial editorial serif with rounded, readable forms; expressive at regular weight rather than bold. If unavailable, use **Lora**. Use weight 400; preserve the close tracking and balanced line lengths. Font stack: "STKBureauSerif", "Lora", Georgia, Cambria, serif.
- **STKBureauSans** — Body copy, navigation, controls and card headlines. Direct, compact grotesk with a friendly, practical tone and medium-weight controls. If unavailable, use **Inter**. Use 300 only in comparison tables, 400 for reading and 500 for controls. Font stack: "STKBureauSans", "Inter", system-ui, sans-serif.
- **Kalam** (only for personal letters on culture pages) — A brief handwritten salutation. Loose pen-written accent used sparingly, not a second headline system. Font stack: "Kalam", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | STKBureauSerif | 400 | 80px | 1 | -0.04em | Main promise, platform overview and luminous closing headline. |
| chapter-display | STKBureauSerif | 400 | 60px | 1.1 | -0.03em | A broad bridge headline introducing a family of capabilities. |
| heading | STKBureauSerif | 400 | 44px | 1.1 | -0.03em | Default major section heading; also the photographic story opening. |
| heading-small | STKBureauSerif | 400 | 36px | 1.15 | -0.025em | Capability panel titles, editorial testimonial and pricing figures. |
| lead | STKBureauSans | 400 | 24px | 1.3 | -0.01em | Hero explanation and closing support, subordinate to the serif display. |
| card-heading | STKBureauSans | 500 | 24px | 1.3 | -0.01em | Photographic story-card headline. |
| body | STKBureauSans | 400 | 18px | 1.4 | -0.01em | Main explanatory paragraphs. |
| emphasis | STKBureauSans | 500 | 18px | 1.4 | -0.01em | Default conversion actions, feature labels and capability-tile text. |
| serif-detail | STKBureauSerif | 400 | 18px | 1.4 | -0.01em | Secondary dates and short metadata; also checklist copy in the editorial closing variant. |
| small | STKBureauSans | 400 | 16px | 1.4 | -0.01em | Compact descriptions and footer links. |
| small-action | STKBureauSans | 500 | 16px | 1.4 | -0.01em | Discovery links, compact navigation actions and tabs. |
| nav | STKBureauSans | 500 | 16px | 1 | normal | Centered desktop navigation. |
| footer-label | STKBureauSerif | 400 | 16px | 1.4 | -0.01em | Editorial category labels above footer links. |
| caption | STKBureauSans | 400 | 13px | 1.4 | -0.01em | Inset testimonial text and supporting attribution. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| customer stories | article-heading | STKBureauSans | 500 | 27px | 36px | -0.0067em | Chapter titles in long-form reading. |
| customer stories | pullquote | STKBureauSerif | 400 | 24px | 1.4 | -0.01em | Quoted testimony set apart by a coral left rule. |
| personal letters on culture pages | letter-salutation | Kalam | 400 | 20.3px | 1 | normal | Small coral greeting at the top of a paper letter. |
| pricing comparisons | table-body | STKBureauSans | 300 | 16px | 1.5 | normal | Low-weight cells in the dense feature matrix. |
| directory filters | form-text | STKBureauSans | 400 | 16px | 1.5 | normal | Labels in dropdown filters. |
| product detail openings | product-eyebrow | STKBureauSans | 400 | 12px | 1.4 | 0.05em, uppercase | Small outlined category label above the headline. |

**Notes:**

- Keep serif weights at 400: size, tight tracking and line breaks supply hierarchy. Tracking tightens from -0.01em in details to -0.04em in the 80px display.
- Keep body text in sans, but allow the small serif footer labels and serif metadata to carry the editorial personality all the way down the page.
- Product interfaces can retain their native typography; monospace and chat-client fonts belong inside demonstrations, not in marketing paragraphs.
- The culture letter scales with its own container, with a serif title around 38.1px/1.1 and regular sans prose around 16.2px/1.4. Treat it as artwork with readable content rather than another global type step.

## Layout

**Density:** Airy narrative spacing around compact demonstrations: wide sections and substantial pauses frame dense, miniature interfaces.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gap and tightly paired title/support details. |
| 12px | Main heading-to-support gap, paired-action gap and footer link rhythm. |
| 16px | Grid gutters and paragraph/action stacks. |
| 24px | Quote-card padding, tile padding and hero support-to-action gap. |
| 32px | Closing action separation and smaller section stacks. |
| 40px | Editorial callout padding and directory-category separation. |
| 48px | Desktop capability-panel padding. |
| 60px | Space between large capability panels. |
| 80px | Default separation between narrative blocks and opening top padding below navigation. |
| 96px | Customer-proof section vertical padding and capability panel column gap. |
| 112px | Atmospheric band and culture chapter vertical padding. |
| 160px | Footer top padding and product-opening bottom space. |
| 200px | Top breathing room before the glowing closing headline. |

### Containers and grids

- **content**: max width 1192px · side padding 16px. Centered desktop storytelling measure; at 1440px it leaves 124px on either side.
- **navigation**: max width 1512px · side padding 20px. Wider than the reading container; logo left, primary links centered and small actions right.
- **opening-copy**: max width 794px. Centered balanced promise and supporting statement.
- **closing-copy**: max width 720px. Centered two-line closing display and support.
- **editorial-pair**: 2 columns · gap 16px. Equal 588px columns for photography and copy; the copy can have 80px of inner breathing room.
- **capability-panel**: 2 columns · gap 96px · side padding 48px. A 400px text column opposite a 600px media stage within the 1192px panel.
- **tile-grid**: 4 columns · gap 16px. 286px square capability tiles and four-column footer organization.
- **feature-grid** (only for product detail pages): 3 columns · gap 16px. 387px wide illustrated explanations or trust benefits.
- **article** (only for customer stories): max width 788px. Reading column beside a persistent left contents rail; cream callouts inset their content by 40px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | panels | 8px |
|  | story-cards | 12px |
|  | capability-tiles | 16px |
| culture pages | portrait | 50% |
| personal letters on culture pages | letter | 2px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-object | `0px 20px 50px -12px rgba(22,22,24,0.16), 0px 4px 6px 0px rgba(22,22,24,0.04)` | Layered application windows, featured story cards and paper photographs. |
| bright-tile | `0px 1px 2px 0px rgba(10,20,33,0.1), 0px 5px 14px 0px rgba(10,20,33,0.1)` | White capability squares over the luminous band. |

### Surfaces

#### Canvas · level 0

**Use:** Main reading background.

**CSS:** `background: #ffffff; color: #161618`

**Observed:** Cream is introduced as a distinct section or inset panel, not as a tint over the whole default page.

**Transfer:** Let most explanatory content remain on this neutral field.

#### Cream panel · level 0

**Use:** Large capability chapters and quiet visual groupings.

**CSS:** `background: #f8f5f0; border-radius: 8px`

**Observed:** Nested product artwork uses a slightly deeper #f1ebe2 backing.

**Transfer:** Keep text and demonstration together inside a single pale panel.

#### Floating white card · level 1

**Use:** Photographic story cards and focal demonstration objects.

**CSS:** `background: #ffffff; border: 1px solid rgba(22,22,24,0.08); border-radius: 12px; box-shadow: 0px 20px 50px -12px rgba(22,22,24,0.16), 0px 4px 6px 0px rgba(22,22,24,0.04)`

**Observed:** The heaviest shadow belongs to the selected or front object, not to every card.

**Transfer:** Use the same elevation language for a featured proof card or a foreground result.

#### Hero light stage · level 0

**Use:** Backing beneath the layered product scene.

**CSS:** `background-color: #f1ebe2; background-image: radial-gradient(92% 74% at 40% 104%, #f25533 0%, #f25533 44%, rgba(242,85,51,0.55) 78%, rgba(242,85,51,0) 104%); overflow: hidden; border-radius: 8px`

**Observed:** A cream upper field turns coral toward the bottom, with diffuse golden light and tiny bright particles.

**Transfer:** Match the soft, warm light rather than adding a sharply delineated gradient stripe.

#### Radiant capability band · level 0

**Use:** Concentrated brand-color chapter behind white capability tiles.

**CSS:** `background-image: linear-gradient(in oklab, #f25533 30%, #ffffff 100%); padding: 112px 32px; overflow: hidden`

**Observed:** White heading and support sit above the cards; faint node-and-line art recedes behind them.

**Transfer:** Use one saturated conceptual chapter rather than tinting every feature section.

#### Closing atmosphere · level 0

**Use:** One uninterrupted luminous backing for the final call and footer.

**CSS:** `background-image: radial-gradient(52% 48% at 74% 56%, rgba(241,197,146,0.55) 0%, rgba(241,197,146,0) 72%), radial-gradient(54% 52% at 37% 80%, rgba(242,85,51,0.75) 0%, rgba(242,85,51,0) 72%), radial-gradient(170% 1010px at 50% 100%, rgba(242,85,51,0.95) 0%, rgba(242,85,51,0.94) 52%, rgba(242,85,51,0.55) 85%, rgba(242,85,51,0) 100%); color: #ffffff`

**Observed:** A broad amber glow sits toward the right while lower coral light stays saturated; the top dissolves into the preceding white field.

**Transfer:** Make the closing call and navigation feel lit by the same atmosphere; exact glow stops are less important than continuity.

#### Dark photographic opening · level 0

**Only for:** customer stories

**Use:** Full-width customer-led hero.

**CSS:** `background-color: #161618; color: #ffffff; background-image: linear-gradient(to right, rgba(0,0,0,0.9) 0%, rgba(0,0,0,0.4) 50%, #161618 100%)`

**Observed:** A sunset workplace photograph remains visible beneath the dark gradient with additional edge vignetting.

**Transfer:** Use contextual customer photography and preserve a calm, readable left text zone.

## Components

### Navigation

**Use:** Persistent global orientation.

**CSS:** `height: 80px; background: rgba(255,255,255,0.8); backdrop-filter: blur(12px); position: sticky; top: 0px; z-index: 100`

**Text style:** `nav` — STKBureauSans 500 · 16px/1

**Observed:** Logo sits at the left edge of the wide navigation container; links stay visually centered and login/conversion actions sit right. The compact actions use 38px height and 8px 16px padding.

**States:** Declared: hover navigation-label color #f25533; focus-visible navigation-label color #f25533 with outline-style none.

### Primary button

**Use:** Main conversion action on white or cream.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #f25533; color: #f7f7f8; border-radius: 9999px; padding: 12px 20px; min-height: 49px`

**Text style:** `emphasis` — STKBureauSans 500 · 18px/1.4 · tracking -0.01em

**Observed:** Short centered label with no oversized arrow. The navigation and pricing variants use small-action typography with 8px 16px padding.

**States:** Declared: hover background #dd340d; focus-visible outline-style none and zero box-shadow; active background #a8280b.

### Secondary button

**Use:** Alternative conversion beside the primary, and the main action on the glowing ending.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #f8f5f0; color: #161618; border-radius: 9999px; padding: 12px 20px; min-height: 49px`

**Text style:** `emphasis` — STKBureauSans 500 · 18px/1.4 · tracking -0.01em

**Observed:** The closing alternative is transparent with a 1px white border at 0.4 alpha, white text and 4px backdrop blur. On white, a transparent outline variant uses the faint charcoal edge.

**States:** Declared: hover background #f1ebe2; focus-visible outline-style none and zero box-shadow; active background #e4d9c8.

### Discovery link

**Use:** Move from a capability summary to deeper content.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; color: #f25533`

**Text style:** `small-action` — STKBureauSans 500 · 16px/1.4 · tracking -0.01em

**Observed:** A small right arrow follows the label; sits directly beneath the supporting paragraph rather than in a full-width action bar.

**States:** Declared: hover color #dd340d; focus-visible outline-style none and zero box-shadow; active color #dd340d.

### Inset quote card

**Use:** Human validation within a capability panel.

**CSS:** `display: flex; flex-direction: column; gap: 24px; max-width: 336px; padding: 24px; background: #ffffff; border: 1px solid rgba(22,22,24,0.08); border-radius: 8px`

**Text style:** `caption` — STKBureauSans 400 · 13px/1.4 · tracking -0.01em

**Observed:** Customer mark first, small quoted text next, then name and muted role; an unobtrusive diagonal arrow occupies the upper corner. It sits well below the capability introduction.

### Story card

**Use:** Selected customer proof in a fanned stack.

**CSS:** `background: #ffffff; border: 1px solid rgba(22,22,24,0.08); border-radius: 12px; overflow: hidden; box-shadow: 0px 20px 50px -12px rgba(22,22,24,0.16), 0px 4px 6px 0px rgba(22,22,24,0.04)`

**Text style:** `card-heading` — STKBureauSans 500 · 24px/1.3 · tracking -0.01em

**Observed:** Landscape customer photo occupies the top; headline and coral text link form the lower block. Slightly rotated rear cards peek around the selected front card; a grid of logo selectors sits in the neighboring text column.

**Transfer:** Use a few real outcomes with contextual imagery; keep the front card readable and rear cards secondary.

### Capability tile

**Use:** Short, high-confidence explanation in the radiant band.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 40px; min-height: 286px; padding: 24px; background: #ffffff; border-radius: 16px; box-shadow: 0px 1px 2px 0px rgba(10,20,33,0.1), 0px 5px 14px 0px rgba(10,20,33,0.1)`

**Text style:** `emphasis` — STKBureauSans 500 · 18px/1.4 · tracking -0.01em

**Observed:** Tiny coral pictogram on a cream square at top left; the claim is anchored near the bottom with a deliberate open middle.

### Footer column

**Use:** Quiet navigation beneath the closing call.

**CSS:** `display: flex; flex-direction: column; gap: 12px; padding-left: 16px; border-left: 1px solid rgba(255,255,255,0.2)`

**Text style:** `small` — STKBureauSans 400 · 16px/1.4 · tracking -0.01em

**Observed:** Three link columns follow a brand/social column in a four-column grid. Each link column begins with footer-label typography. White links at 0.9 alpha are the default over the glow. Light endings use charcoal links, coral labels and peach dividers.

**States:** Declared: hover link color #ffffff on the glowing variant; focus-visible outline-style none and zero box-shadow. Light-ending links hover to #f25533.

### Plan card

**Only for:** pricing pages

**Use:** Compare packages before the detailed feature matrix.

**CSS:** `display: flex; flex-direction: column; padding: 16px; background: #f8f5f0; border-radius: 12px`

**Text style:** `small` — STKBureauSans 400 · 16px/1.4 · tracking -0.01em

**Observed:** Four equal columns align package name, 36px serif price, billing qualifiers, short positioning, feature list, platform chips and bottom action. The promoted plan is white with a faint border and floating-object shadow; its price is coral.

**Transfer:** Highlight one plan through elevation and a coral figure rather than a loud badge.

### Comparison cell

**Only for:** pricing comparisons

**Use:** Compact feature availability matrix.

**CSS:** `padding: 12px 8px; text-align: center; border-right: 1px solid #e5e7eb; color: #161618`

**Text style:** `table-body` — STKBureauSans 300 · 16px/1.5

**Observed:** Rows are about 49px high, with a wider left description column and four centered package columns. Cream category rows break up the matrix. A cream plan/action header remains visible as the matrix scrolls.

### Directory row

**Only for:** careers and opportunity directories

**Use:** Scannable listings grouped under serif category labels.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 20px 0px; border-bottom: 1px solid rgba(22,22,24,0.08)`

**Text style:** `emphasis` — STKBureauSans 500 · 18px/1.4 · tracking -0.01em

**Observed:** A three-column inner grid carries a medium sans title, muted serif location and muted serif compensation. The row is the link, with an apply affordance rather than a repeated coral button.

**States:** Declared: hover background #f8f5f0; focus-visible outline-style none and zero box-shadow.

### Directory filter

**Only for:** directory pages

**Use:** Filter long categorized listings.

**CSS:** `display: flex; align-items: center; justify-content: space-between; height: 46px; padding: 0px 16px; background: #ffffff; border: 1px solid rgba(22,22,24,0.08); border-radius: 8px; box-shadow: 0px 1px 2px 0px rgba(22,22,24,0.06)`

**Text style:** `form-text` — STKBureauSans 400 · 16px/1.5

**Observed:** Two dropdowns and a search field share a three-column row above the listings; a small chevron or search icon sits apart from the text.

## Imagery and graphics

### Layered product theatre

**Use:** The main product demonstration and smaller capability illustrations.

**Observed:** A wide cream-and-coral stage holds a pale desktop window, with smaller phone, chat and dark terminal objects overlapping its front and sides. It is almost page-wide, whereas the headline above it is much narrower. Soft shadows, rounded application chrome and a few particles make it physical without becoming glossy 3D.

**Transfer:** Compose one legible primary interface with two or three complementary interaction views. Without finished UI, construct a credible workflow from labeled inputs, a central result and one supporting message; retain the depth and warm staging.

**Build:** Use the Hero light stage as a clipped backing about 1305px wide at desktop. Place a central application object about 930px wide with a 0.5px rgba(22,22,24,0.08) edge and the floating-object shadow; overlap a narrow phone at left and a smaller dark or white output card at right/front. Add a broad 1175px circular rgba(245,205,140,0.9)-to-transparent glow with 50px blur at roughly 0.72 opacity. Keep micro-particles sparse and behind the interfaces.

### System diagrams and ambient network

**Use:** Conceptual explanation alongside product proof.

**Observed:** Diagrams use thin warm-gray connections, cream icon tiles and coral focal nodes. One overview is a large semicircular layered system; another warm band has a ghostly spherical node network, barely visible behind white tiles.

**Transfer:** Use the product's own relationships, not a literal recreation of the same model. A clean radial or branching diagram is the minimum acceptable substitute for sophisticated data art.

**Build:** For the semicircular diagram, use nested SVG arcs in cream, pale coral and coral with 1px rgba(22,22,24,0.08) radial dividers and small labeled icon tiles. For the ambient network, distribute circles on an elliptical outline, connect nearby points with 1px rgba(255,255,255,0.15) lines, and vary node radii from 2px to 7px at white alpha 0.2–0.5. Keep it behind text and cards.

### Warm closing light

**Use:** Signature atmospheric transition into the final call and footer.

**Observed:** A soft orange-red field rises from the bottom with an amber highlight on the right, leaving white serif text clearly legible. There is no hard seam between call-to-action and footer.

**Transfer:** Keep this luminous ending on ordinary marketing pages even if the main product has no visual media.

**Build:** Place the Closing atmosphere beneath both final sections, extending roughly 1125px upward from the page bottom. Add a wider coral radial overlay centered near the lower middle, using alpha 0.98 near its center and fading fully at the outer edge. Preserve the pale upper fade and the stronger lower coral; avoid a discrete orange rectangle.

### Customer editorial photography

**Use:** Customer story sections, proof cards and testimonial portraits.

**Observed:** Naturalistic portraits, workplaces and architectural scenes retain full color but are not aggressively saturated. A face can fill a 588px square beside a restrained text column; story cards use landscape photos in white frames. Story openings darken an environmental image with broad vignettes.

**Transfer:** Choose a real setting or person connected to the outcome. Use an environmental photograph when a portrait is unavailable, keeping product interfaces as separate objects rather than compositing them onto faces.

### Circuit-line opening

**Only for:** product detail pages

**Use:** Frame a split text-and-video introduction.

**Observed:** Fine coral and pale amber paths turn at softened right angles around and behind a 588×331 video card. Circular endpoints and fading segments suggest connected information without filling the reading area.

**Transfer:** Use the line system around the edges of a new feature's demo, with very few paths crossing the text zone.

**Build:** Draw SVG orthogonal polylines with rounded joins, 1px–2px coral strokes and occasional amber endpoints of 4px–8px radius. Fade most lines toward white, leaving only several segments at full strength. Back the video preview with a warm translucent tint and place a cream pill play action at its center.

### Culture paper and photographs

**Only for:** culture and recruiting pages

**Use:** Humanize organizational storytelling through physical keepsakes.

**Observed:** Circular employee portraits fan across the opening; coral starbursts extend off the cream page edges. Elsewhere candid team photographs form a Polaroid-like stack with wide white lower margins, mild warm texture and soft shadows. A personal letter emerges from a burgundy envelope with an orange wax seal, surrounded by tilted photos.

**Transfer:** Use genuine everyday team scenes, not posed corporate stock. The minimum version is a readable white letter with a simple folded envelope and two real printed-photo frames.

**Build:** Make print frames from white rectangles with roughly 10px image-side borders, a 70px lower margin, a 1px warm-gray edge and floating-object shadow. Fan rear frames with small alternating rotations. Add a faint warm radial wash and subtle inset vignette to photos. Construct the envelope from burgundy SVG triangles; overlay a white 2px-radius letter and an orange circular seal with inset rings. Keep this paper language confined to organizational storytelling.

### Tilted benefit ribbon

**Only for:** culture pages

**Use:** A playful full-width interruption between substantial chapters.

**Observed:** A pale pink strip is rotated slightly, with 36px serif sentence fragments, wine-colored emphasis and coral starburst separators; its text extends beyond both edges.

**Transfer:** Use short concrete personal outcomes rather than slogans.

**Build:** Use a clipped full-width band, 105px tall before rotation, pink fill and a 1deg rotation; repeat serif text runs with starburst SVG separators. Extend the band beyond the edges so no angled corner exposes a gap.

### Icons

**Observed:** Most marketing icons are small solid SVG marks at 16px or 20px, charcoal or coral. Comparison tables also use 16px outline marks with 1.5px round strokes. Arrows are compact and aligned with the label baseline; category icons often sit inside pale square tiles.

**Transfer:** Choose a coherent solid set for marketing and a light outline set for comparison/status details. Keep colorful partner marks inside product or integration demonstrations, not as decorative confetti.

## Section recipes

How recurring sections are built.

### First screen: Promise over product theatre

**Observed:** A slim wine announcement strip is inset 20px from the edges above the 80px Navigation. Below it, the centered opening-copy measure carries an 80px regular serif display balanced into two lines, then a 12px gap to a muted 24px lead and 24px to Primary button plus Secondary button with a 12px gap. The copy is visually about the middle half of the viewport width. Back-to-front layers are white canvas, warm light stage, pale application window and smaller overlapping interaction objects. Within the first 900px, the entire headline, support and actions are visible, and the upper portion of the broad stage and application window enters below them. The full layered scene and logo proof unfold further down; the hero is not an all-at-once dashboard wall.

**Transfer:** Preserve the centered editorial promise and below-copy theatre for a new landing page. A product without mature media still gets a warm stage with a central outcome and supporting interaction cards. Pricing opens with a shorter centered economic promise and package cards; product detail uses left-aligned display beside video; a story opens with dark contextual photography and a smaller 44px serif headline; culture opens on cream with edge starbursts and people.

**Avoid:** Do not put the full scene beside the headline in the default opening, cover the reading area with particles, or shrink the headline into a generic 48px sans hero.

**Text style:** `display` — STKBureauSerif 400 · 80px/1 · tracking -0.04em

### Heading and explanation

**Observed:** Centered section headings use heading typography with a 12px gap to an 18px supporting paragraph, generally in a 700px–840px measure. Capability-panel titles use heading-small with 16px between title, paragraph and Discovery link.

**Transfer:** Name an outcome in the heading and explain the mechanism in the paragraph; alternate centered chapter introductions with left-aligned, narrower capability copy.

**Text style:** `heading` — STKBureauSerif 400 · 44px/1.1 · tracking -0.03em

### Editorial customer pair

**Observed:** An equal two-column composition sets a 36px serif story headline and compact description opposite a large square customer portrait/video. A quote and name sit lower in the text column; a subtle divider precedes the story link. The image has softly rounded corners and a white pill play overlay.

**Transfer:** Use this for substantial customer proof, not a row of interchangeable testimonial cards.

**Text style:** `heading-small` — STKBureauSerif 400 · 36px/1.15 · tracking -0.025em

### Cream capability chapter

**Observed:** Cream panel spans the content measure with 48px padding. The narrow text side contains title, explanation, Discovery link and Inset quote card below; the media side carries a deeper oatmeal demonstration backing. Beneath the demo, four evenly spaced text-and-icon tabs use thin rules, coral active indicator and muted inactive labels. Consecutive panels are separated by 60px.

**Transfer:** Let each panel prove one capability with a different meaningful interface state. Keep the inset quote secondary to the demonstration.

### Radiant conceptual chapter

**Observed:** Radiant capability band sets a centered white 44px serif heading, explanatory copy and a restrained outline action above a four-column Capability tile row. The ambient network sits behind all reading layers and the band fades into white below.

**Transfer:** Explain the model or principle that unifies a product, using short benefit statements and an abstract relationship diagram rather than a list of unrelated features.

### Photographic proof deck

**Observed:** Left column holds a rating cue, 44px serif headline, outline action and a compact logo-selector grid. Right column holds the Story card deck, with one clear image/headline/link and several subtly rotated cards behind. Small third-party proof badges sit below with ample white space.

**Transfer:** Use actual validated proof; preserve the selectable deck as a physical stack, not a horizontal strip of identical cards.

### Glowing close and footer

**Observed:** Closing atmosphere begins fading in above a centered 720px text measure. A white 80px two-line display, 24px low-opacity support and cream action sit above the footer. Closing top padding is 200px, action separation 32px, and footer top padding 160px. The footer is four columns with 16px gutters, a small brand symbol/social group and Footer columns separated by fine white rules.

**Transfer:** Finish ordinary marketing pages with a confident, slightly witty line and one clear next step. Pricing and culture keep their lighter, functional endings instead of forcing this conversion scene.

**Text style:** `display` — STKBureauSerif 400 · 80px/1 · tracking -0.04em

### Product detail accordion

**Only for:** product detail pages

**Observed:** A 588px near-square product image sits opposite a text column with 80px inner breathing room. A 36px serif title and short paragraph lead to a set of roughly 57px accordion triggers; 1px faint rules separate them, a plus sits at right and expanded copy uses 16px text. A thin coral line marks the active explanation.

**Transfer:** Pair each trigger with a relevant demo state; alternate which side holds the media to maintain editorial pacing.

### Long-form customer story

**Only for:** customer stories

**Observed:** A 729px-tall dark photographic opening leads to a cream metadata strip, then a left contents rail beside a 788px article. Sans chapter titles, 18px body copy and serif Pullquotes create the reading hierarchy. Cream 40px-padded callouts group substantial sub-stories; coral 2px left rules mark quotes. Related stories precede a white editorial closing: small line illustration, two-color 44px serif promise and a split image/checklist/action panel, then a light footer.

**Transfer:** Preserve the change from cinematic introduction to utilitarian reading. End with relevant next stories and a modest product invitation rather than restarting the hero.

**Text style:** `article-heading` — STKBureauSans 500 · 27px/36px · tracking -0.0067em

### Pricing comparison

**Only for:** pricing pages

**Observed:** Centered 80px economic headline and 24px support lead to four Plan cards. A separate narrow add-on offer precedes the long ruled comparison matrix with its persistent plan header. A monochrome customer-logo strip and a wide cream image-and-quote carousel supply final proof; the page ends in the light Footer column variant without a glowing conversion section.

**Transfer:** Let package choice and detailed comparison dominate; use one elevated plan and avoid importing the full product theatre into this practical page.

### Culture chapters and directory

**Only for:** culture pages

**Observed:** Cream opening with coral starbursts and a circular portrait fan gives way to an editorial split with 44px serif statement, accordion explanations, coral 36px serif figures and fanned paper photos. Tilted benefit ribbon, portrait-format photo/video cards and the envelope letter create tactile interludes. A 36px serif listing title leads to Directory filters and categorized Directory rows; a cream light footer closes the page directly.

**Transfer:** Tell a concrete people story using the scoped tactile devices, then make opportunities easy to scan. Keep the functional directory distinct from the playful paper imagery.

## Page flow

**Storyline:** Promise → staged demonstration → human proof → explanatory chapters → deeper capability proof → reassurance → context-appropriate next step.

### Establish a broad product platform and invite exploration

1. **Promise** — Centered serif statement above paired actions and a layered warm product stage.
2. **Social proof** — Monochrome customer logos followed by a substantial editorial customer portrait/story pair.
3. **Conceptual explanation** — Problem/solution switch, large system diagram and luminous capability band.
4. **Capability chapters** — Cream split panels with demonstration tabs and small inset quotes.
5. **Proof and community** — Tactile campaign promotion and selectable photographic customer deck.
6. **Closing call** — Large white serif line and cream actions over a continuous warm footer atmosphere.

**Transfer:** Adapt the depth and sequence to the new product while retaining an intentional demonstration, substantial human proof and warm closing device.

### Help readers choose a package and inspect practical differences

1. **Economic promise** — Short centered value headline and supporting statement.
2. **Pricing** — Four aligned cards, one elevated, followed by a smaller standalone offer.
3. **Detailed comparison** — Long ruled feature matrix with persistent package labels and actions.
4. **Reassurance** — Customer logos and an image-led testimonial carousel.
5. **Ending** — Light four-column footer directly after proof.

**Transfer:** Keep commercial choice readable before asking readers to process detailed availability.

### Explain a sophisticated product capability and build technical trust

1. **Promise and demonstration** — Split serif hero and video over circuit-like connecting paths.
2. **Mechanism** — Cream branching system diagram, illustrated benefits and cost argument.
3. **Compatibility and proof** — Integration wheel and large portrait testimonial.
4. **Capability depth** — Alternating interface-and-accordion sections followed by a warm conceptual band and floating-card explanation.
5. **Objection handling** — Three-column illustrated trust and control grid.
6. **Closing call** — Shared glowing closing headline and footer.

**Transfer:** Explain how the capability works, demonstrate specific interactions, then address control and trust rather than relying on abstract AI claims.

### Build confidence through a detailed customer narrative

1. **Outcome framing** — Dark workplace photograph, serif outcome headline and small coral numeric proof.
2. **Context** — Cream metadata strip and an article with left contents rail.
3. **Transformation** — Before/after chapters, serif ruled pullquotes and cream editorial callouts.
4. **Expansion** — Concrete use cases, an inline chart and partnership commentary.
5. **Next step** — Related story cards, illustrated two-color closing statement, image/checklist invitation and light footer.

**Transfer:** Use real testimony to explain the decision, adoption and consequences; prioritize reading comfort over landing-page spectacle.

### Communicate a human organization and guide candidates to opportunities

1. **Invitation** — Cream serif hero, coral edge starbursts and employee portrait fan.
2. **Character and proof** — Editorial statement, accordion, coral figures and fanned candid paper photos.
3. **Human detail** — Pink outcome ribbon, portrait video cards and a personal envelope letter.
4. **Action** — Filters and categorized ruled role listings.
5. **Ending** — Direct transition from listings into a cream light footer.

**Transfer:** Balance a tangible people story with a highly functional directory; the page need not end with a sales call.

## Writing

Confident, technically literate and warm, with a small mischievous streak. Claims are practical and specific; the humor relieves pressure without making the product feel unserious.

**Do not copy:** Do not reuse incident.io names, marks, proprietary artwork, customer identities, quotations, commercial figures, ratings or unverified performance and security claims. Source examples illustrate voice only.

- **Addressing the reader:** Speak directly to you and your team. Use we for purpose and partnership, and name the product when explaining what it actually does.
- **Rhythm:** Short, balanced headlines contrast with explanatory paragraphs of two or three plain sentences. Use contractions and natural speech; a witty inversion can carry the main promise, while feature copy stays explicit.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A familiar phrase recast as a product promise, or a blunt value comparison. | 3–9 words | “With great product, comes great reliability”<br>“Cheaper than downtime” |
| Capability heading | Name the capability and the concrete result it produces. | 6–11 words | “On-call gets the right people in the room”<br>“You don't have to debug alone” |
| Support | Explain what changes for the reader and why; favor direct verbs over abstractions. | 20–45 words | “Automatically update customers as your incident progresses, reduce inbound support, and maintain trust when things go wrong.” |
| Action | Short verb phrase that names the next step. | 2–5 words | “Get a demo”<br>“See open roles” |
| Closing line | A playful, confident reversal of the reader's usual frustration. | 6–10 words | “So good, you’ll break things on purpose” |
| Culture explanation | Candid acknowledgement of difficulty followed by practical care. | 2–3 sentences | “Work is intense here, and we're honest about that. So we protect the things that make us human: the long weekends, the school runs, the moments that matter outside work.” |

**Words and phrasing to use:** your team; built to; works with; the work that matters; in lockstep; what broke and why; no more; gets you

**Avoid:** revolutionary ecosystem; unlock limitless potential; synergy; effortless magic without explanation; overheated superlatives

**Rules:**

- Lead with the outcome, then explain the mechanism in concrete terms.
- Use numerical proof only when it can be supported; let customer testimony retain a recognizable human voice.
- Distinguish capability claims from trust guarantees, and describe user control explicitly when relevant.
- Keep labels sentence case; reserve all capitals for the tiny product category tag.
- Let humor live in a few prominent lines rather than in every control and paragraph.

## Do's and Don'ts

### Do

- Keep the main display at 80px/1, weight 400, with -0.04em tracking on desktop.
- Use 1192px as the main content measure and let navigation breathe out to 1512px.
- Pair 49px coral pills with cream secondary pills; use the 38px variant only for compact actions.
- Keep chapter titles serif and the 18px explanatory body sans.
- Give capability panels 48px internal padding and a deeper oatmeal media backing.
- Use a few genuinely overlapping product objects with soft two-layer shadows.
- Keep thin 1px rules, 16px gutters and 12px footer-link rhythm even in expressive sections.
- Preserve a continuous amber/coral closing field with white type on ordinary landing pages.

### Don't

- Do not replace the serif system with a heavy geometric sans display.
- Do not spread coral tint across every reading section; its strongest fills belong to staged moments.
- Do not turn 8px panel corners into 24px rounded bento tiles.
- Do not apply the floating-object shadow to every small block; quote cards are flat and lightly outlined.
- Do not enlarge 13px inset quotes into oversized competing headlines.
- Do not make the footer a black slab detached from the warm closing atmosphere.
- Do not use handwritten type in general navigation, pricing or feature headlines.
- Do not carry the culture page's pink ribbon, paper envelope or edge starbursts onto routine product pages.

## Motion and responsive

### Motion

**Observed:**

- Declared primary-action and link transitions: color, background-color, border-color, opacity and transform over .15s cubic-bezier(.4, 0, .2, 1).
- Declared navigation background/backdrop/transform transition: 0.3s cubic-bezier(0.2, 0, 0, 1).
- Selectable story decks use small rotations and layered depth. Product panels show active tabs with coral rules; product detail accordions pair expanded copy with a relevant image.
- The product theatre has scroll-linked staging and the culture ribbon is a marquee; native interface shimmer and spinner effects remain inside demonstrations.

**Transfer:**

- Keep interaction movement subordinate to the editorial composition. Animate the active object or state, not every heading at once.
- Retain a convincing static composition of the product theatre and story deck when motion is reduced.

**Unknown:**

- Exact scroll timelines, marquee speed, scene choreography and reduced-motion runtime behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px and 1280px.
- Navigation links are a desktop layout from 1024px; the main container uses 16px side padding below 1280px.
- The hero action pair stacks before 640px. Capability panels use 24px padding before 768px and 48px thereafter; the two-column 400px/media composition starts at 1024px.
- Capability tiles use one column, then two from 640px and four from 1024px. Footer uses two columns before 768px and four thereafter; its brand/social block moves after navigation on narrow screens.
- Inset desktop quote cards are hidden below 768px. Pricing cards stack before their desktop row.

**Transfer:**

- On narrow screens, keep the serif promise first and the main result object second; simplify peripheral product panels rather than squeezing all miniature views into the width.
- Stack article contents and text, and retain readable pullquotes and cream callouts without forcing a persistent side rail.
- Preserve the uninterrupted closing glow while allowing footer columns and paired actions to stack.

**Unknown:**

- Exact small-screen heading values, menu treatment and mobile animation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
