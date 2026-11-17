# Griffin — engraved systems, human warmth

## Overview

A dark, editorial style that makes technical infrastructure feel established and approachable. Warm ivory serif headlines sit alongside light grotesk explanations and tiny monospaced controls on an almost-black canvas. Fine ruled grids, engraved system diagrams and character-based textures supply the technical character, while vivid water and mountain photography bring occasional daylight into an otherwise restrained, spacious page.

### Essentials

- Editorial headlines meet equipment labels: Cambon 300 at 72px/1 with -0.02em tracking opens the default landing composition; 40px/1.1 with -0.05em tracking leads sections, while controls use 12px uppercase mono with 0.06em tracking.
- The opening is deliberately lopsided: a two-line promise and 616px-wide support sit at the left of a 1400px frame, leaving the right half mostly dark; a 252px-tall full-width character field anchors the lower first screen.
- Actions are small ivory capsules, not oversized slabs: default buttons are 40px tall with 12px 20px padding, 9999px radius and 12px/16px mono labels; the secondary capsule is black with a 1px inset edge.
- Color lives inside demonstrations rather than washing the page: #0c0c0b remains the dominant canvas, #f9f5ef carries headlines, and #363533 supplies rules; isolated mint checks and tiny colored diagram markers punctuate the monochrome.
- Technical material is a signature, not decoration pasted on top: include a low-contrast character field and an engraved or dotted system visual. Use domain-relevant characters and an abstract layered workflow when no physical product object exists.
- Photography supplies a concentrated window of daylight: stage a 440px-wide black interface over a roughly half-page photograph of reflective water or alpine terrain, leaving the explanatory half on black. A real output preview over similarly cool natural texture is the fallback.
- The closing promise becomes a small editorial monument: a centered 480px-wide serif statement at 40px/44px, one ivory action 32px below, and 120px of breathing room above and below, followed by a finely ruled, multi-column footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Confirmation mint | `#85eda5` | `--color-mint` | accent | Small circular confirmation checks in technical benefit lists; also used inside demonstration interfaces. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ivory capsule | `#e6e1d9` | `--color-action` | action, surface | Primary action fill. |
| Carbon black | `#0c0c0b` | `--color-canvas` | background, surface, text | Dominant page canvas, demonstration panels and dark text on ivory actions. |
| Warm charcoal | `#1a1918` | `--color-panel` | surface | Raised information panels and media backing; keep ordinary feature sections on the canvas. |
| Graphite rule | `#363533` | `--color-rule` | border, accent | Solid and dashed separators, inset control edges and dotted diagram fields. |
| Inactive graphite | `#514e4b` | `--color-inactive` | text, accent, surface | Inactive system step numbers and navigation backing. |
| Focus stone | `#7c7771` | `--color-focus` | border | Keyboard-focus outline on navigation. |
| Warm grey | `#959089` | `--color-muted` | text, link | Secondary explanations, inactive links and metadata. |
| Stone label | `#c2bcb2` | `--color-tertiary` | text | Subdued capsule labels such as the story archive action. |
| Pale stone | `#d4cfc6` | `--color-body` | text, link | Longer editorial paragraphs, footer group labels and brighter link hover. |
| Warm chalk | `#f9f5ef` | `--color-headline` | text | Headlines, main labels and leading support copy. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| system storytelling sections | System rose | `#f35c95` | `--color-pink` | accent | Tiny active chapter marker and narrow progress stroke in the system explanation. |

## Typography

- **Cambon** — Display promises, section headings and editorial numbers. Light, high-contrast editorial serif with a tall, elegant silhouette and tightly fitted large text. If unavailable, use **Cormorant Garamond**. Use 300; tune wrapping to preserve the narrow editorial silhouette. Font stack: "Cambon", "Cormorant Garamond", "Apple Garamond", Baskerville, "Times New Roman", serif.
- **Sohne** — Supporting copy, feature titles, editorial lists and resource links. Restrained grotesk, mostly light weight, with open and unforced reading texture. If unavailable, use **Inter**. Use 300 for body and 400 for compact titles. Font stack: "Sohne", "Inter", -apple-system, system-ui, "Segoe UI", Roboto, sans-serif.
- **Sohne Mono** — Navigation, capsules, technical labels, step markers and code. Compact monospaced lettering with widely tracked uppercase labels. If unavailable, use **IBM Plex Mono**. Font stack: "Sohne Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Cambon | 300 | 72px | 1 | -0.02em, features "clig", "liga" | Default landing promise, usually two lines. |
| heading | Cambon | 300 | 40px | 1.1 | -0.05em, features "clig", "liga" | Section leads and the centered closing statement. |
| accordion-active | Cambon | 300 | 32px | 1.25 | -0.05em | Expanded solution selector heading. |
| subheading | Sohne | 300 | 28px | 1.2 | normal | Product group headings and editorial row titles. |
| story-title | Sohne | 300 | 24px | 32px | normal | Multi-line linked outcome titles under story media. |
| lede | Sohne | 300 | 20px | 1.4 | normal | Hero support and introductory paragraphs; emphasis can shift from chalk to muted grey within a paragraph. |
| body | Sohne | 300 | 16px | 1.5 | normal | General explanations and resource-card descriptions. |
| caption | Sohne | 300 | 16px | 1.4 | normal | Compact editorial paragraphs, stat descriptions and biographies. |
| feature-title | Sohne | 400 | 16px | 22px | normal | Small feature headings above short descriptions. |
| feature-copy | Sohne | 300 | 14px | 20px | normal | Short descriptions in sparse icon feature grids. |
| technical-label | Sohne Mono | 400 | 14px | 1 | 0.06em, uppercase | Numbered steps, external links and small technical annotations. |
| trust-label | Sohne Mono | 400 | 14px | 16px | 0.06em, uppercase | Compact proof-band caption. |
| footer-heading | Sohne Mono | 700 | 14px | 1 | 0.06em, uppercase | Footer group labels and active numbered system labels. |
| footer-link | Sohne | 400 | 14px | 18px | normal | Dense secondary navigation. |
| action | Sohne Mono | 400 | 12px | 16px | 0.06em, uppercase | Capsule labels and login action. |
| navigation | Sohne Mono | 400 | 12px | 1 | 0.06em, uppercase | Main navigation controls. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product detail, pricing and company pages | content-display | Cambon | 300 | 48px | 1 | -0.05em, features "clig", "liga" | Centered opening headlines and large editorial statistics. |
| product detail pages | split-heading | Cambon | 300 | 32px | 36px | -0.05em, features "clig", "liga" | Paired benefit headings. |
| pricing pages | pricing-title | Sohne | 400 | 28px | 36px | normal | Titles inside stacked pricing panels. |
| company and team pages | team-group | Cambon | 300 | 28px | 1.2 | normal | Editorial subheads separating people groups. |
| technical demonstrations | code | Sohne Mono | 400 | 14px | 1.5 | normal, features "zero" | Legible code texture in technical demonstrations. |
| product detail, pricing and company pages | badge | Sohne Mono | 400 | 11px | 16px | 0.06em, uppercase | Outlined category tag above a centered headline. |

**Notes:**

- Serif section titles are more tightly tracked than the larger opening display: -0.05em versus -0.02em. Do not apply this negative tracking to the grotesk body.
- Most body text uses weight 300, not a heavy contemporary SaaS weight. The monospaced controls stay at 400 and use 0.06em tracking.
- Keep the light serif for large statistics rather than switching all numerical proof to dashboard mono. Mono belongs to technical interface information.

## Layout

**Density:** Airy sections with compact controls: broad 80px section insets contrast with tiny labels, 32–40px actions and dense footer navigation.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Declared extra-small token; icon-to-label gap in capsules. |
| 10px | Declared small token for compact grouping. |
| 16px | Declared medium token; card padding, paired action gaps and heading-to-support separation. |
| 20px | Declared large token; stacked pricing panel gaps and benefit-list spacing. |
| 24px | Declared extra-large token; opening content grid rhythm and demonstration-card padding. |
| 36px | Declared double-extra-large token; resource-card title-to-description separation. |
| 32px | Support-to-action separation, editorial row padding and closing action gap. |
| 40px | Content inset within the wide frame and ordinary multi-column grid gap. |
| 80px | Usual section top and bottom padding; sparse icon-grid gaps. |
| 120px | Closing-call top and bottom padding and the pricing opening inset. |

### Containers and grids

- **wide-frame**: max width 1400px · side padding 16px. Centered outer frame; at 1440px it begins 20px from the window edge. Inner content normally adds 40px on each side, creating a 1320px working area.
- **split-stage**: 2 columns · gap 0px. Two 700px halves in the wide frame; left text is inset 40px and the right media can run to the frame edges. Use a vertical rule to mark the seam.
- **editorial-columns**: 2 columns · gap 40px. Two 640px columns within the 1320px content area for lists and grouped capabilities.
- **story-grid**: 3 columns · gap 40px. Three 413px-wide media cards with shallow landscape pictures above linked outcomes.
- **resource-grid**: 4 columns · gap 16px. Four compact outlined cards spanning the content width.
- **closing-column**: max width 480px. Centered short statement and a single conversion action.
- **pricing-stack** (only for pricing pages): max width 768px · gap 20px. Narrow centered column for broad horizontal panels, not a row of tall plan cards.
- **portrait-grid** (only for company and team pages): 4 columns · gap 40px. Four 300px portrait columns with biographies; rows separated by 64px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsules | 9999px (pill) |
|  | editorial-cards | 8px |
|  | demonstration-panels | 12px |
| technical demonstrations | code-panels | 4px |
| system storytelling sections | chapter-markers | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| inset-control-edge | `0px 0px 0px 1px #363533 inset` | Dark capsules and category badges; edges replace drop shadows. |

### Surfaces

#### Carbon canvas · level 0

**Use:** All ordinary marketing sections.

**CSS:** `background: #0c0c0b; color: #f9f5ef`

**Observed:** Continuous warm black across the page; full-width horizontal rules articulate sections without changing the background.

**Transfer:** Let typography and rules establish hierarchy before adding more surface colors.

#### Outlined editorial card · level 1

**Use:** Resource links, people summaries and supporting content.

**CSS:** `background: #0c0c0b; border: 1px solid #363533; border-radius: 8px; box-shadow: none`

**Observed:** A nearly flush edge, with no floating-card effect. Media can occupy the full upper edge.

**Transfer:** Keep related content in a clean ruled shell rather than making every item a bright tile.

#### Dotted drafting field · level 0

**Use:** Backing for the engraved system diagram.

**CSS:** `background-color: #0c0c0b; background-image: radial-gradient(circle, #363533 1px, rgba(0, 0, 0, 0) 1px); background-size: 16px 16px; border-left: 1px solid #363533`

**Observed:** The dots are low contrast and sit behind the entire diagram half, not inside each layer.

**Transfer:** Use the field to ground a diagram while preserving ample negative space.

#### Warm information panel · level 1

**Only for:** pricing pages

**Use:** Stacked information and package panels.

**CSS:** `background: #1a1918; border: 1px solid #363533; border-radius: 12px; overflow: clip`

**Observed:** Slightly lighter than the page, with header and body separated by a fine rule.

**Transfer:** Use for financial or comparison information that needs a distinct internal grid.

#### Technical inset panel · level 1

**Only for:** technical demonstrations

**Use:** Code, result and output windows over photography.

**CSS:** `background: #0c0c0b; border: 1px solid #363533; border-radius: 4px; padding: 12px`

**Observed:** Several black rectangular modules form a single demonstration; one body can be open while adjacent headers remain compact.

**Transfer:** Keep the preview legible enough to explain the product, without adopting its internal interface as the marketing type system.

## Components

### Navigation

**Use:** Persistent desktop navigation centered between identity and account actions.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 4px; height: 40px; border-radius: 9999px; backdrop-filter: blur(12px)`

**Text style:** `navigation` — Sohne Mono 400 · 12px/1 · tracking 0.06em · uppercase

**Observed:** The header is 64px tall. Identity sits left, login and a compact ivory action right. The central cluster remains fixed while scrolling and gains its own contact action; individual controls are 32px tall with 16px side padding. The cluster stays visually almost black rather than becoming a bright grey bar.

**States:** Declared: hover behavior is unspecified; focus-visible on navigation controls uses outline 3px solid #7c7771 with 2px outline-offset.

**Transfer:** Use a short set of content categories; preserve the centered small mono cluster rather than enlarging it into a full-width toolbar.

### Primary button

**Use:** Primary trial or sales conversion.

**CSS:** `display: flex; align-items: center; gap: 6px; background: #e6e1d9; color: #0c0c0b; border-radius: 9999px; padding: 12px 20px; height: 40px`

**Text style:** `action` — Sohne Mono 400 · 12px/16px · tracking 0.06em · uppercase

**Observed:** A small right arrow follows the label on major calls. Header actions use a compact 32px version with 8px 14px padding. The light fill is the strongest routine contrast on the page.

**Transfer:** Use one light action in a cluster; pair with Secondary button where a second path matters.

### Secondary button

**Use:** Sales, documentation and secondary exploration actions.

**CSS:** `display: flex; align-items: center; gap: 6px; background: #0c0c0b; color: #f9f5ef; box-shadow: 0px 0px 0px 1px #363533 inset; border-radius: 9999px; padding: 12px 20px; height: 40px`

**Text style:** `action` — Sohne Mono 400 · 12px/16px · tracking 0.06em · uppercase

**Observed:** Same silhouette as the primary action but almost merged with the canvas. Small archive and learn-more variants use 32px height and 8px 14px padding; an archive label can use stone grey.

### Resource card

**Use:** Low-friction routes into practical next steps.

**CSS:** `display: grid; grid-template-columns: minmax(0px, 1fr) auto; row-gap: 36px; column-gap: 12px; border: 1px solid #363533; border-radius: 8px; padding: 16px`

**Text style:** `lede` — Sohne 300 · 20px/1.4

**Observed:** A short linked title sits at upper left and a 20px right arrow at upper right. The description uses Body in muted grey below. Four cards sit in Resource grid; the shell has no contrasting fill.

**Transfer:** Link to concrete next steps rather than using the card for vague feature claims.

### Proof cell

**Use:** Compact logo and credibility bands.

**CSS:** `display: grid; align-items: center; border-left: 1px dashed #363533; min-height: 64px`

**Text style:** `trust-label` — Sohne Mono 400 · 14px/16px · tracking 0.06em · uppercase

**Observed:** The broad proof band has six equal tracks and two 64px rows. Its central caption spans two tracks, with small monochrome logos around it. Outer side edges are solid; internal seams are dashed. A product variant uses three wider logo cells in one row.

**Transfer:** Use actual proof in subdued monochrome, or comparable certifications or integrations when appropriate.

### Editorial row

**Use:** Audience, application or capability explanations in a ruled list.

**CSS:** `display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); row-gap: 8px; column-gap: 40px; border-top: 1px dashed #363533; padding: 32px 0px`

**Text style:** `subheading` — Sohne 300 · 28px/1.2

**Observed:** Left column holds a light grotesk title; right column holds a compact Caption paragraph around 394px wide. First item can omit the top seam. Rows occupy the full content width instead of becoming detached cards.

**Transfer:** Match an audience or task with a concrete result; retain the half-width alignment even when paragraphs are short.

### Footer link

**Use:** Dense secondary wayfinding under mono group labels.

**CSS:** `display: inline-flex; color: #959089`

**Text style:** `footer-link` — Sohne 400 · 14px/18px

**Observed:** Links sit in vertical lists with 4px row gaps. A 360px identity-and-legal column sits beside four evenly distributed navigation columns; social icons share the final column.

**States:** Declared: hover changes color to #d4cfc6; focus-visible behavior is unspecified.

### Solution selector

**Use:** Expanded editorial selector paired with a product demonstration.

**CSS:** `padding: 16px 0px; color: #f9f5ef`

**Text style:** `accordion-active` — Cambon 300 · 32px/1.25 · tracking -0.05em

**Observed:** One expanded item includes a short paragraph, a small icon benefit list and a compact Secondary button. Inactive headers use the same light serif at 24px/32px with -0.05em tracking and muted grey. Fine top rules divide collapsed rows; the selected visual fills the neighboring half.

**States:** Declared: hover on inactive headings changes color to #f9f5ef; focus-visible behavior is unspecified.

**Transfer:** Use a few meaningfully different use cases, with one representative output per selection.

### Category badge

**Only for:** product detail, pricing and company pages

**Use:** Small category marker above centered openings.

**CSS:** `display: flex; align-items: center; padding: 6px 12px; border-radius: 8px; box-shadow: 0px 0px 0px 1px #363533 inset`

**Text style:** `badge` — Sohne Mono 400 · 11px/16px · tracking 0.06em · uppercase

**Observed:** The category marker is a small outlined rounded rectangle, not a filled pill. A 32px gap separates it from the headline.

### Pricing panel

**Only for:** pricing pages

**Use:** Explain fees and packages as a sequence of broad information blocks.

**CSS:** `background: #1a1918; border: 1px solid #363533; border-radius: 12px; overflow: clip`

**Text style:** `pricing-title` — Sohne 400 · 28px/36px

**Observed:** A header with 20px vertical and 16px horizontal padding places a faded mono-style step index before the title, and can align a price at right. Ruled bodies contain support copy or a four-cell package comparison with 8px gaps. Panels stack in Pricing stack; each package cell is lightly outlined rather than brightly recommended.

**Transfer:** Explain the buying model in understandable steps, not just a row of promotional plans.

## Imagery and graphics

### Character current

**Use:** Signature full-width technical texture, especially beneath the opening.

**Observed:** Dense small currency symbols and slashes form slanted wave-like bands on black. The field is monochrome, grainy and subdued, bounded by fine horizontal rules. It is 252px tall under the default opening and 126px in smaller editorial openings.

**Transfer:** Use symbols meaningful to the new product, but retain the same low-contrast flowing density. A static SVG character field is the minimum acceptable equivalent.

**Build:** Create a full-width SVG with repeated 12px monospaced characters on roughly 12px rows. Mix slashes with 2–3 domain-relevant symbols; stagger rows and modulate opacity with diagonal sine-wave bands. Use #959089 at roughly 0.15–0.55 opacity over #0c0c0b, a subtle dark grain overlay, and 1px #363533 top and bottom rules. Fit the pattern into 252px or 126px height without enlarging the glyphs.

### Engraved exploded system

**Use:** Signature technical explanation on Dotted drafting field.

**Observed:** Four thin black plates are pulled apart in an isometric stack. Hairline grey edges, short engraved labels, bars and internal grid markings replace glossy rendering. Fine leaders terminate in tiny colored dots; numbered chapter controls on the text side correspond to layers on the right.

**Transfer:** Represent the new product as layers of inputs, orchestration and outcome. If detailed illustration is unavailable, three or four clean SVG parallelograms with meaningful internal marks and a few labels are sufficient.

**Build:** In an SVG about 560px wide, draw 3–4 parallelogram plates with a common 2:1 diamond perspective, separated vertically. Fill with #0c0c0b and stroke with #363533 at 1px; duplicate lower edges by 12–24px to suggest thickness. Add narrow #514e4b bars, a faint internal grid, 14px mono annotations and elbow leaders. Back with the 16px dotted field. Use 8px circular chapter markers, with tiny mint or rose endpoint accents and concentric low-opacity rings; never turn the plate faces into bright fills.

### Daylight product stage

**Use:** A concentrated color and material contrast within a split demonstration section.

**Observed:** One scene uses dark teal water with rippled coral and pale-blue reflections behind a centered black account panel; another uses bright snowy mountains, blue sky and conifers behind stacked code/result modules. Photography occupies approximately half the section while the text remains on black. Black foreground windows are about 440px wide, leaving visible scenery around every side.

**Transfer:** Use a genuine natural photograph with cool daylight, texture and depth. Put the new product's key result or compact output in a black window over it; retain natural light instead of tinting the whole picture into a brand gradient.

**Build:** Use a cover-fitted photograph in a half-width panel, center a 440px-max black preview with 40px minimum side breathing room, and add a fine #363533 border with 4px corners for code or 12px for an application preview. For water, retain reflected highlights; for mountains, keep the pale sky and snowy ridges visible above and beside the preview.

### Customer story media

**Use:** Landscape media above outcome-led links in a three-column proof section.

**Observed:** Three approximately 413px by 232px pictures sit above 24px light grotesk titles, without heavy card frames.

**Transfer:** Use relevant customer or output imagery at a consistent shallow landscape ratio; keep the result in the title rather than adding badge clutter.

### Human editorial photography

**Only for:** company and team pages

**Use:** Opening photo ribbon, portraits and company-resource images.

**Observed:** The opening ribbon mixes single large team photos with stacked smaller group shots, clipped beyond both viewport edges with 12px corners. Portraits are natural-color, shoulder-up, consistently framed at 300px by 400px with 8px corners, subdued backgrounds and soft daylight. Resource cards mix documentary team photography, report covers and monochrome landscape imagery.

**Transfer:** Photograph real people and working relationships rather than generic staged collaboration. Keep consistent portrait framing and let documentary images provide the warmth.

### Icons

**Observed:** Small monochrome functional symbols sit next to labels or above compact feature headings, generally 20–32px. Product-list symbols sit in 52px square outlined holders with 4px corners. Technical benefits use 26px mint confirmation discs; button arrows are 16px. Shapes are visually simple, with restrained line detail.

**Transfer:** Use a consistent simple icon set in warm grey or chalk, and reserve mint discs for confirmed benefits. Keep the linework light enough to sit comfortably beside weight-300 text.

## Section recipes

How recurring sections are built.

### First screen: Asymmetric editorial opening

**Observed:** A 64px header tops a dark opening with roughly 80px top inset inside Wide frame. The promise uses Display in two left-aligned lines and occupies much less than the full width; the right half stays open. Below it, a Lede paragraph spans about 616px, with the second thought fading to muted grey. Primary button and Secondary button sit 16px apart below the copy. A small uppercase technical story link sits toward the lower right. Behind everything is Carbon canvas; beneath the content is Character current, a 252px full-width band starting around 518px down the page. The first 900px contains the complete headline, support, action pair, character field and two-row proof band. The first major explanatory chapter begins below that screen; there is no giant floating interface in the hero.

**Transfer:** Write a short two-part promise that balances like a compact left-aligned editorial title, and use the domain-specific character texture as the principal object when no hero media exists. Product detail and company openings instead center Category badge, Content-display and Lede with 32px gaps; detail pages add paired actions and a 126px character strip, company pages add a documentary photo ribbon. Pricing uses the centered form with 120px vertical inset and no photographic stage.

**Avoid:** Do not center the default landing promise, fill its empty right half with a stock dashboard, or turn the character texture into a bright oversized illustration.

**Text style:** `display` — Cambon 300 · 72px/1 · tracking -0.02em

### System chapter stage

**Observed:** Split stage pairs a text chapter with Engraved exploded system on Dotted drafting field. The stage is sticky and viewport-height on desktop. Numbered mono chapters and colored markers form a vertical rail; the active chapter expands into a 40px serif heading, short support and sometimes a Secondary button. The diagram emphasizes the matching layer.

**Transfer:** Tell a layered product story through a few meaningful stages. Preserve the rail, active explanation and layer correspondence; the number of stages should follow the product, not a fixed page length.

**Text style:** `heading` — Cambon 300 · 40px/1.1 · tracking -0.05em

### Use-case demonstration split

**Observed:** Solution selector fills the left half while Daylight product stage fills the right. Text content receives 80px vertical and 40px horizontal insets. The demo window is centered in the photographic half; switching between interface and API output uses a small capsule control under it.

**Transfer:** Choose use cases with genuinely different outcomes and maintain a one-to-one relationship between selected explanation and preview.

### Ruled capability index

**Observed:** A Heading introduces two Editorial columns, separated by a 40px gap. Light 28px subheads group linked entries with square outlined icons, 20px labels and short muted descriptions. Horizontal rules separate groups rather than boxing the entire grid.

**Transfer:** Group a broad offering into a few understandable areas; retain ruled hierarchy instead of making a sea of equally weighted feature cards.

### Editorial proof and resources

**Observed:** A left Heading and right archive capsule introduce Story grid with a 48px gap below the heading row. Practical next-step content uses Resource grid, with a short muted introduction and four Resource cards. Photo-backed editorial variants use three Outlined editorial cards with edge-to-edge landscape media.

**Transfer:** Separate evidence of outcomes from practical routes to action. Keep image-led storytelling sparse and utility links more compact.

### Compact icon benefits

**Observed:** Heading sits above a three- or four-column feature row with 80px gaps, 28px icons, Feature-title and Feature-copy. Titles and descriptions are separated by just 4px; the whole section receives 80px top and bottom padding.

**Transfer:** Use brief mechanism-level benefits that can be read independently. Preserve the large spaces between columns and small local text gaps.

### Editorial closing and directory footer

**Observed:** Closing column contains a three-line Heading, centered and capped at 480px, with Primary button 32px below and 120px vertical padding. A full-width top rule introduces the footer: identity and compact legal copy left, four navigation columns right, mono group labels, muted Footer links and social icons. A final thin ruled strip holds copyright left and a short location line right. This closing statement and directory ending recur across page types; detail pages insert a paired assurance section between them.

**Transfer:** End with one concise product-level ambition, one clear action, then a useful directory. Keep any required legal text secondary and separate from the conversion message.

**Text style:** `heading` — Cambon 300 · 40px/1.1 · tracking -0.05em

### Split editorial argument and statistics

**Only for:** company and institutional pages

**Observed:** A 40px serif heading occupies the left half while a 28px light grotesk statement and 20px explanation occupy the right. A stat row follows with top rules, 32px inner top padding and 48px serif figures; its asymmetric desktop grid leaves a wider first interval. Small 16px captions sit 12px beneath the figures.

**Transfer:** Use an institutional argument plus a few verifiable measures. Let the numbers feel editorial rather than like dashboard counters.

**Text style:** `content-display` — Cambon 300 · 48px/1 · tracking -0.05em

### Detail-page paired arguments

**Only for:** product detail pages

**Observed:** Two equal halves share a central vertical rule, each containing a 32px serif benefit heading and 16px body paragraph with 16px separation. The closing assurance variant places simple icons above 40px serif headings and uses compact learn-more capsules; it appears after the centered closing call and before the footer.

**Transfer:** Pair two distinct value perspectives or two final trust questions without forcing them into a single large card.

**Text style:** `split-heading` — Cambon 300 · 32px/36px · tracking -0.05em

### Stacked buying explanation

**Only for:** pricing pages

**Observed:** Centered Heading and Lede introduce Warm information panels in a 768px stack. Pricing panel headers are 28px grotesk, with numbered steps and prices aligned across the header. Ruled bodies explain onboarding, recurring packages and usage. Comparison cells sit within the broad panel rather than competing as tall separate cards.

**Transfer:** Make the payment model legible in sequential concepts, separating one-time setup, recurring commitment and variable usage when relevant.

**Text style:** `pricing-title` — Sohne 400 · 28px/36px

### People and institutional depth

**Only for:** company and team pages

**Observed:** A section Heading introduces Team-group subheads, then Portrait grid. Names and roles sit directly below each image, with compact biographies and small uppercase external links. A second group can use a three-column grid of text-only Outlined editorial cards with 32px padding.

**Transfer:** Keep people authentic and readable; distinguish portrait-led leadership from text-led advisory or governance content.

## Page flow

**Storyline:** Promise → credibility → explanation of the system → useful applications → proof and practical entry points → concentrated closing promise → directory, with trust questions placed where the page needs them.

### Broad marketing landing page establishing both confidence and developer accessibility

1. **Promise** — Asymmetric editorial opening with small actions, character texture and a compact proof grid.
2. **System explanation** — Sticky chapter rail and exploded layers make the underlying offering comprehensible.
3. **Application** — Expanded use cases are paired with photographic product previews.
4. **Capability map** — A ruled two-column product index organizes the breadth of the offer.
5. **Social proof** — Three outcome-led customer stories add external validation.
6. **Practical entry** — A technical benefit list and scenic code stage lead into compact resource cards.
7. **Closing call** — Centered serif ambition, one light capsule and the directory footer.

**Transfer:** Use the long form when the product needs both a mental model and a practical path to try it; combine or shorten beats without losing the technical texture and editorial closing.

### Institutional story with credible human and organizational depth

1. **Identity** — Centered badge, headline and support above a documentary photo ribbon and character field.
2. **Quantified proof** — Split editorial statement with a sparse ruled statistic row.
3. **Capabilities and differentiation** — Compact icon benefits and a split heading with ruled explanation rows.
4. **Human credibility** — Portrait biographies followed by text-only institutional profiles.
5. **Further exploration** — Three photo-backed resource cards.
6. **Closing call** — Shared centered promise and directory footer.

**Transfer:** Adapt to the new organization's argument and actual team; use photography and measured facts to add human credibility without changing the black editorial canvas.

### Make the buying model easy to understand without becoming a sales brochure

1. **Commercial promise** — Centered category badge and two-part 48px headline, short support and dark contact capsule.
2. **Credibility** — The compact two-row logo proof band.
3. **Pricing** — Two centered offering groups explain recurring fees and transaction-based costs using broad stacked panels.
4. **Closing call** — Shared centered promise and directory footer.

**Transfer:** Keep the commercial model in one narrow information column and use panel subdivisions for comparisons rather than bright plan-card promotion.

### Focused product detail page translating one capability into operational and customer benefits

1. **Product promise** — Centered badge, two-line headline, support and paired actions over a short character strip and three-logo band.
2. **Benefit framing** — Two ruled half-width arguments explain complementary value perspectives.
3. **Differentiation** — Four compact icon benefits provide mechanism-level reassurance.
4. **Application** — Wide dashed editorial rows connect audiences to results.
5. **Closing call** — Centered serif promise and one ivory sales action.
6. **Objection handling** — Paired assurance blocks answer eligibility and protection questions before the directory footer.

**Transfer:** Use this more concise centered opening for a focused product; explain who benefits and why, then place any sensitive trust requirements close to the final action.

## Writing

Measured, capable and unusually plainspoken for technical infrastructure. It makes serious systems feel usable through concrete verbs, short explanations and lightly conversational invitations rather than hype.

**Do not copy:** Do not reuse Griffin's name, logo, proprietary illustrations, customer names, report artwork, testimonials, financial figures, regulatory status, protection claims, dates or performance promises. All such facts and claims must belong to the new product and be independently supportable. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the builder as you and your; use we for accountable product explanations. Refer to end users as your customers where this clarifies whose outcome matters.
- **Rhythm:** Short 3–8-word headlines alternate with one- or two-sentence support paragraphs. Lists are compact; longer institutional passages are confined to the explanatory column. Contractions soften the technical content; exclamation marks are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the capability and connect it immediately to the reader's ability to build or achieve something. | 5–9 words | “The bank you can build on”<br>“Bank accounts to power any product” |
| Section lead | Lead with a useful action or a concise proposition, not a decorative slogan. | 3–7 words | “Designed to help you build”<br>“Start coding today”<br>“Not just another virtual account” |
| Support | Explain the mechanism and resulting benefit in the same thought. | 15–40 words | “Embed bank accounts, payments, and all kinds of financial products quickly via our simple API.”<br>“Simplify complex payment flows and reconciliation by giving each customer their own bank account.” |
| Reassurance | Remove a concrete obstacle in plain language, sometimes with a short list of things the reader need not do. | 8–22 words | “Pay for what you use, scale as you grow. No hidden fees.”<br>“Start building today with no sales calls, time limits or NDAs.” |
| Action | Name the next activity directly; use warmer invitations for a conversation. | 2–4 words | “Try for free”<br>“View our docs”<br>“Let's chat” |
| Closing promise | Use a small progression of verbs followed by a unified product-level outcome. | 10–16 words | “Build, launch and scale your financial products on one powerful platform.” |

**Words and phrasing to use:** build; launch; scale; embed; simple; infrastructure; your customers; get started; no hidden fees; talk to us

**Avoid:** revolutionary; game-changing; unleash; supercharge; best-in-class; magical; limitless; guaranteed success

**Rules:**

- Tie each capability to an operational or customer result.
- Use precise technical terms where they explain a mechanism, and follow them with plain-language consequences.
- Keep financial, security and compliance statements specific and qualified.
- Distinguish a free test path from a sales conversation without making either sound coercive.
- Let headlines carry ambition and body copy supply the explanation.

## Do's and Don'ts

### Do

- Keep the main canvas #0c0c0b and use #363533 rules to separate sections instead of changing background colors repeatedly.
- Use 72px light serif for the default opening and 40px/44px for recurring section leads.
- Keep capsule labels at 12px mono with 0.06em tracking, regardless of whether the action is 32px or 40px high.
- Maintain 80px section padding and 40px inner horizontal insets in the wide desktop frame.
- Put black 440px preview modules over real cool-toned photographs with scenery still visible around them.
- Include a low-contrast domain-character texture and an engraved or dotted technical visual.
- Use solid outer borders and dashed inner seams to distinguish structural framing from repeated rows.
- Give the closing statement its own 480px column and 120px vertical padding.

### Don't

- Do not replace the warm black and ivory ramp with blue-black panels and pure-white text.
- Do not make all headings bold grotesks; the weight-300 serif is the main editorial identity.
- Do not apply 0.06em mono tracking to the 16px body paragraphs.
- Do not expand tiny mint or rose signals into large brand-color background bands.
- Do not add soft floating drop shadows to the 8px outlined cards; the edge is the elevation cue.
- Do not make every corner a pill: cards are 8px, pricing and application previews 12px, and code modules 4px.
- Do not convert the 768px pricing information stack into a full-width row of tall colorful plans.
- Do not turn the 300px by 400px portrait system into round avatars or glossy cutouts.

## Motion and responsive

### Motion

**Observed:**

- Navigation remains fixed while the page scrolls; the system explanation uses a sticky stage with changing chapter emphasis.
- Declared selector transitions change color, font size and line height over 0.3s.
- Declared technical reveals include clip-path 0.6s cubic-bezier(0.65, 0, 0.35, 1); chapter wipe and entrance animations use 0.5s ease-out with 0.05s and 0.18s delays.
- The company photo ribbon declares a 140s linear infinite animation. Resource-card borders declare a 0.2s transition.

**Transfer:**

- Keep motion tied to a selected layer or selected use case, so text and diagram remain synchronized.
- Use the slow photo ribbon as a background documentary rhythm rather than a fast promotional ticker.
- Ensure the character field has a composed static appearance even when animation is unavailable.

**Unknown:**

- Exact live timing of all scroll-triggered transitions and character-field animation is unknown. No unreported easing or duration is prescribed.

### Responsive

**Observed:**

- Desktop composition is defined at 1440px. Shared CSS width breakpoints include 576px, 640px, 700px, 768px, 960px, 1100px, 1120px and 1280px; additional page-specific breakpoints exist.

**Transfer:**

- On narrow screens, preserve the editorial promise and compact actions before the texture band; let lines reflow rather than shrinking the entire desktop scene.
- Stack explanation and media, keeping the black preview legible and visible scenery around it. A static vertically arranged layer diagram can retain the system-story relationship without a viewport-height sticky stage.
- Reduce proof and portrait columns while retaining the same solid frame and dashed internal-seam language.

**Unknown:**

- Mobile layouts, exact type reductions, navigation replacement and breakpoint-to-component mappings are not established; the narrow-screen treatments above are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
