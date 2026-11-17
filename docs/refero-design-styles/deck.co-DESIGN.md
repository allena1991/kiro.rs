# Deck — moss and machines

## Overview

A dark, expansive technical style with almost-black green canvases, pale grotesk headlines and restrained sage actions. Soft violet skies and tactile green landscapes make dense software interfaces feel like objects in an unfamiliar natural world. It suits infrastructure and automation products that need both operational credibility and a memorable visual atmosphere; large editorial statements alternate with compact, orderly proof.

### Essentials

- Headlines behave like wide architectural slabs: Plain at weight 500, a 137.4px opening with line height 1 and -0.03em tracking; section leads step down to 72px and feature titles to 56px.
- The opening separates promise from demonstration: a full-width two-line headline above a 440px support paragraph on the left and paired 44px pill actions on the right; the violet product stage starts within the first 900px.
- Most of the page stays green-black: #0d100f canvas, 3% white card washes, #f6f6f6 headings and sage #77ab97 links. Reserve saturated violet, blue and green for contained media or the full-width demonstration stage, not text-heavy bands.
- Software floats above synthetic terrain: dark windows sit inside 18px translucent glass shells with 7px padding and 12px backdrop blur, backed by green textured hills and lavender skies. Include this atmospheric product staging; without finished artwork, use layered SVG hills, grain and a real workflow panel.
- Conversion controls are small green capsules, not oversized billboards: #24684f fill, 44px height, 22px horizontal padding, 16px medium text, paired with a #262827 capsule and a 12px gap.
- The ending has two graphic signatures: a centered 72px call over a fading dot field, followed by a monumental white wordmark spanning the 1284px content width. Recreate both with the new identity, using a heavy extended text wordmark when no custom lettering exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest action | `#24684f` | `--color-green` | action | Primary pill buttons. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dusk blue | `#5b6eb8` | `--color-blue` | background, accent | Lower demonstration-stage gradient. |
| Violet midtone | `#8859a5` | `--color-violet` | background, accent | Middle of the demonstration-stage gradient. |
| Lilac light | `#cb91cd` | `--color-lilac` | background, accent | Upper demonstration-stage gradient and atmospheric sky. |
| Sage | `#77ab97` | `--color-sage` | link, accent | Text arrows, short exploration links and check marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Green black | `#0d100f` | `--color-canvas` | background, text | Default page canvas and dark ink on pale actions. |
| Washed black | `#141716` | `--color-card` | surface | Visible 3% white wash over the canvas; grouped cards and feature bands. |
| Forest backing | `#151917` | `--color-media-base` | surface | Backing behind customer media. |
| Fine edge | `#1c1e1d` | `--color-edge` | border | Visible 6% white hairline on the canvas; table rows, FAQ dividers and technical panels. |
| Section rule | `#252827` | `--color-rule` | border | Visible 10% white over the canvas; footer boundary and stronger separators. |
| Charcoal capsule | `#262827` | `--color-secondary-action` | action | Secondary sales action. |
| Frosted gray | `#343635` | `--color-glass` | surface | 16% white glass, shown as its visible result on the canvas; actual transparency allows the landscape through. |
| Fine gray | `#6e706f` | `--color-fine-text` | text | Visible 40% white over the canvas for low-emphasis utility text and FAQ answers. |
| Muted gray | `#8a8a8a` | `--color-muted` | text | Footer links and small utility actions. |
| Secondary gray | `#9e9f9f` | `--color-secondary-text` | text | Visible 60% white over the canvas for card descriptions. |
| Lead gray | `#a8a9a9` | `--color-hero-copy` | text | Visible 64% white over the canvas for opening support. |
| Navigation gray | `#b6b7b7` | `--color-nav-text` | text | Visible 70% white over the canvas for navigation. |
| Body gray | `#bbbcbb` | `--color-body` | text | Visible 72% white over the canvas for feature descriptions. |
| Silver | `#cdcdcd` | `--color-closing-copy` | text | Closing support line. |
| Chalk | `#f6f6f6` | `--color-heading` | text, border | Headlines, button labels and focus outlines. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| focused use-case pages | Pale lemon | `#fdfac3` | `--color-yellow` | action | Specialized product-page actions rather than default marketing capsules. |
| pricing pages | Table chalk | `#e7e7e7` | `--color-table-text` | text | Visible 90% white over the canvas for comparison values. |
| focused use-case pages | FAQ chalk | `#f5f5f5` | `--color-faq-text` | text | Question labels. |

## Typography

- **Plain** — All marketing headings, paragraphs, navigation and actions. Low-contrast contemporary grotesk with open counters, broad display proportions and firm medium-weight headings. If unavailable, use **Inter**. Use 400 and 500; preserve tight headline tracking and fit line breaks by width. Font stack: "Plain", "Inter", -apple-system, system-ui, "Segoe UI", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Plain | 500 | 137.4px | 1 | -0.03em | fixed | Default marketing opening; broad two-line statement. |
| heading-lg | Plain | 500 | 72px | 1.05 | -0.025em | fixed | Major capability and proof section leads. |
| closing-heading | Plain | 500 | 72px | 1.1 | -0.03em | size clamp(40px, 5vw, 72px) | Centered conversion statement. |
| feature-heading | Plain | 500 | 56px | 1.1 | -0.02em | size clamp(36px, 3.9vw, 56px) | Headline inside a split feature band. |
| hero-support | Plain | 400 | 22px | 1.5 | -0.01em | fixed | Narrow paragraph under the main headline. |
| section-support | Plain | 400 | 20px | 1.5 | -0.008em | fixed | Section and closing support. |
| feature-body | Plain | 400 | 18px | 1.55 | -0.009em | fixed | Feature-band explanations. |
| feature-link | Plain | 400 | 18px | 28px | -0.009em | fixed | Sage feature-band link with a fine arrow. |
| body | Plain | 400 | 16px | 1.5 | -0.01em | fixed | Card descriptions and short exploration links. |
| card-heading | Plain | 500 | 16px | 1.4 | -0.005em | fixed | Compact card and story titles. |
| button | Plain | 500 | 16px | 1 | -0.01em | fixed | Default conversion buttons. |
| nav | Plain | 400 | 14px | 1.3 | normal | fixed | Top navigation. |
| small-heading | Plain | 500 | 14px | 1.3 | normal | fixed | Footer column headings and small topic labels. |
| footer-link | Plain | 400 | 14px | 1.3 | -0.0114em | fixed | Footer navigation. |
| compact-button | Plain | 500 | 14px | 1.3 | -0.0114em | fixed | Compact navigation action and specialized rectangular actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| customer-story indexes | index-display | Plain | 500 | 165.7px | 1 | -0.03em | fixed | Single-line editorial index title. |
| pricing pages | pricing-display | Plain | 500 | 77.8px | 1.02 | -0.03em | size clamp(44px, 5.4vw, 80px) | Concise pricing introduction. |
| focused use-case pages | use-case-closing | Plain | 500 | 70px | 1.1 | -0.03em | size clamp(32px, 5vw, 70px) | Wider centered closing statement. |
| pricing pages | comparison-heading | Plain | 500 | 63.4px | 1.05 | -0.025em | size clamp(40px, 4.4vw, 68px) | Comparison table introduction. |
| focused use-case pages | use-case-display | Plain | 500 | 60px | 1 | -0.03em | size clamp(32px, 5vw, 60px) | Two-part problem-to-outcome opening. |
| focused use-case pages | use-case-heading | Plain | 500 | 60px | 1.1 | -0.03em | size clamp(28px, 4.5vw, 60px) | Capability, process and FAQ section leads. |
| pricing pages | price | Plain | 500 | 47.5px | 1 | -0.03em | size clamp(40px, 3.3vw, 52px) | Price or Custom label. |
| pricing pages | table | Plain | 400 | 15px | 1.45 | -0.011em | fixed | Aligned comparison values and plan inclusions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Headlines use medium weight, not bold. Tracking tightens from the card title's -0.005em to -0.03em in the opening and closing.
- Keep paragraphs markedly smaller than headlines. Large section titles can wrap to two lines while card titles stay deliberately modest.
- The wordmark is artwork, not an additional display text recipe. Software demonstrations can use system sans and monospace internally without changing the marketing font.

## Layout

**Density:** Airy at section scale, compact within software scenes and repeated cards; expansive dark intervals separate tightly organized information.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 6px | Inline text-to-arrow gap. | fixed |
| 12px | Default card grid and paired-button gap. | fixed |
| 20px | Card and split-band inner padding; split-band column gap. | fixed |
| 24px | Footer column gaps and pricing card side padding. | fixed |
| 28px | Feature title-to-paragraph gap. | fixed |
| 40px | Heading-pair column gap and feature paragraph-to-link interval. | fixed |
| 56.2px | Opening title-to-support row. | clamp(28px, 3.9vw, 72px) |
| 72px | Top padding of major proof and capability sections. | fixed |
| 76.3px | Vertical inset of the full-width product stage. | clamp(32px, 5.3vw, 96px) |
| 93.6px | Major section heading-to-card-grid gap. | fixed |
| 122.4px | Opening support row-to-product-stage interval. | clamp(64px, 8.5vw, 160px) |
| 158.4px | Bottom breathing room of major grid sections. | fixed |
| 160px | Footer navigation-to-wordmark interval. | fixed |

### Containers and grids

- **main container**: max width 1756px · side padding 77.8px. Centered outer container; at 1440px the usable content is 1284px wide. Shared alignment for navigation, opening, grids and footer.
- **capability grid**: 4 columns · gap 12px. Equal 312px cards across the desktop content width.
- **story grid**: 3 columns · gap 12px. Equal 420px cards with landscape media.
- **feature split**: 2 columns · gap 20px. Equal-width copy and visual, alternating sides across feature bands.
- **footer grid**: 6 columns · gap 24px. Compact link columns above an oversized identity.
- **use-case container** (only for focused use-case pages): max width 1348px · side padding 24px. Centered sections with 1300px usable width.
- **process grid** (only for focused use-case pages): 3 columns · gap 10px. Square technical diagrams or code panels with captions underneath.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action capsules | 9999px (pill) |
|  | product window | 10px |
|  | glass shell | 18px |
|  | inner software panels | 8px |
| focused use-case pages | technical panels | 12px |
| focused use-case pages | use-case actions | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| product stage window | `0px 0px 0px 1px rgba(255, 255, 255, 0.08), 0px 24px 80px 0px rgba(13, 16, 15, 0.35)` | One large app window above the violet stage. |
| glass inset | `0px 0px 0px 1px rgba(255, 255, 255, 0.1) inset` | Subtle lit rim around frosted shells. |

### Surfaces

#### Canvas · level 0

**Use:** Default background.

**CSS:** `background: #0d100f; color: #f6f6f6`

#### Washed card · level 1

**Use:** Capabilities, case studies, pricing cards and feature bands.

**CSS:** `background: rgba(255, 255, 255, 0.03)`

**Observed:** Flat, square outer grouping with almost no elevation; contrast comes from the wash rather than a heavy border.

**Transfer:** Keep informational cards visually subordinate to their art.

#### Violet stage · level 0

**Use:** Full-width product demonstration backing.

**CSS:** `background: linear-gradient(160deg, #cb91cd 0%, #8859a5 50%, #5b6eb8 100%); overflow: hidden; position: relative`

**Observed:** Soft color clouds surround a dark app window, with no hard decorative lines.

**Transfer:** Use as the principal chromatic interval, not as a repeated paragraph background.

#### Product window · level 2

**Use:** Large app scene on the stage.

**CSS:** `background: #0d100f; border-radius: 10px; box-shadow: 0px 0px 0px 1px rgba(255, 255, 255, 0.08), 0px 24px 80px 0px rgba(13, 16, 15, 0.35); overflow: hidden`

#### Glass shell · level 2

**Use:** Small floating software demonstrations over landscape art.

**CSS:** `background: rgba(255, 255, 255, 0.16); border-radius: 18px; padding: 7px; gap: 7px; box-shadow: 0px 0px 0px 1px rgba(255, 255, 255, 0.1) inset; backdrop-filter: blur(12px)`

**Observed:** The translucent lip frames darker inset panels rather than making the entire interface transparent.

**Transfer:** Put legible opaque content inside the rim.

#### Technical panel · level 1

**Only for:** focused use-case pages

**Use:** Code and process diagrams.

**CSS:** `background: rgba(13, 16, 15, 0.85); border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 12px`

**Observed:** Square visual area with small code, status rows and restrained syntax colors.

**Transfer:** Show only enough interface detail to make the process concrete.

## Components

### Fixed navigation

**Use:** Persistent top navigation.

**CSS:** `position: fixed; height: 64px; background: #0d100f; z-index: 1000; display: flex; align-items: center; box-shadow: 0px 1px 0px 0px rgba(255, 255, 255, 0.008)`

**Observed:** Small white wordmark at left, centered link cluster, sign-in and compact green action at right. Inner layout uses balanced side columns around an auto-width center.

### Primary button

**Use:** Default self-serve conversion.

**CSS:** `background: #24684f; color: #f6f6f6; height: 44px; padding: 0px 22px; border-radius: 9999px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — Plain 500 · 16px/1 · tracking -0.01em

**Observed:** Usually paired with a neutral sales action. A fine arrow can reveal at the trailing edge; the navigation variant is 36px high with 18px horizontal padding and compact-button text.

**States:** Declared: hover background #2B7A5D; focus-visible outline 2px solid #F6F6F6 with 2px offset; active transform scale(0.98).

### Secondary button

**Use:** Sales-led conversion beside the primary action.

**CSS:** `background: #262827; color: #f6f6f6; height: 44px; padding: 0px 22px; border-radius: 9999px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — Plain 500 · 16px/1 · tracking -0.01em

**Observed:** Equal height and visual weight of label to the green action, but deliberately lower chromatic emphasis.

**States:** Declared: hover background #313432; focus-visible outline 2px solid #F6F6F6 with 2px offset; active transform scale(0.98).

### Navigation link

**Use:** Top-level menus and destinations.

**CSS:** `height: 32px; padding: 0px 12px; border-radius: 9999px; color: rgba(255, 255, 255, 0.7); display: flex; align-items: center`

**Text style:** `nav` — Plain 400 · 14px/1.3

**Observed:** Plain text resting on the canvas, with a capsule-shaped hover target.

**States:** Declared: hover background rgba(255, 255, 255, 0.08) and color #F6F6F6; focus-visible outline 2px solid #F6F6F6 with -2px offset.

### Exploration link

**Use:** Quiet movement from a card into a detail page.

**CSS:** `color: #77ab97; display: flex; align-items: center; gap: 6px`

**Text style:** `body` — Plain 400 · 16px/1.5 · tracking -0.01em

**Observed:** Sentence-case verb plus destination followed by a fine right arrow. Feature bands use feature-link text and a 40px separation from the paragraph.

### Capability card

**Use:** Summarize one capability with tangible visual proof.

**CSS:** `background: rgba(255, 255, 255, 0.03); padding: 20px; display: flex; flex-direction: column`

**Text style:** `card-heading` — Plain 500 · 16px/1.4 · tracking -0.005em

**Observed:** Title, short muted description, Exploration link, then a clipped square purple-backed miniature workflow. Equal-width cards align their bottoms.

**States:** Declared: hover background-color rgba(255, 255, 255, 0.055); focus-visible outline 2px solid #F6F6F6 with 3px offset.

**Transfer:** Use a small real action or result, not a generic feature icon.

### Split feature band

**Use:** Explain a major product benefit.

**CSS:** `background: rgba(255, 255, 255, 0.03); display: grid; grid-template-columns: 1fr 1fr; gap: 20px; padding: 20px; overflow: hidden`

**Text style:** `feature-heading` — Plain 500 · 56px/1.1 · tracking -0.02em

**Observed:** One side vertically centers a headline, paragraph and link; the other holds landscape art with a glass-framed software scene. Desktop band is 576px tall with a 612px by 536px media area.

**States:** Declared: hover background-color rgba(255, 255, 255, 0.055); focus-visible outline 2px solid #F6F6F6 with 3px offset.

### Story card

**Use:** Social proof presented as a compact editorial tile.

**CSS:** `background: rgba(255, 255, 255, 0.03); padding: 20px; display: flex; flex-direction: column`

**Text style:** `card-heading` — Plain 500 · 16px/1.4 · tracking -0.005em

**Observed:** Outcome-led title above a sage story link, then 380px by 253px customer art. Three equal cards per desktop row; customer art may be a centered logo on a saturated field or photography.

**States:** Declared: hover background-color rgba(255, 255, 255, 0.055); focus-visible outline 2px solid #F6F6F6 with 3px offset.

**Transfer:** Use genuine proof and preserve the consistent media ratio.

### Plan card

**Only for:** pricing pages

**Use:** Offer comparison before detailed rates.

**CSS:** `background: rgba(255, 255, 255, 0.03); padding: 28px 24px 24px 24px; display: flex; flex-direction: column`

**Text style:** `price` — Plain 500 · 47.5px/1 · tracking -0.03em

**Observed:** Small plan name, large price with baseline suffix, muted one-line positioning, a hairline, sage-check inclusion list and bottom-aligned full-width action. All plans use the same neutral card surface; self-serve plans use green actions and enterprise uses the neutral action.

### Comparison cell

**Only for:** pricing pages

**Use:** Dense but readable technical plan comparison.

**CSS:** `padding: 15px 16px; border-bottom: 1px solid rgba(255, 255, 255, 0.06); color: rgba(255, 255, 255, 0.9)`

**Text style:** `table` — Plain 400 · 15px/1.45 · tracking -0.011em

**Observed:** A wider feature-label column precedes four equal plan columns. Standard rows are 53px tall; multiline rows expand. Category headings add substantial top space; sticky column headers remain visible below navigation. Dotted label underlines indicate contextual help.

### Use-case button

**Only for:** focused use-case pages

**Use:** Compact primary action on a focused product story.

**CSS:** `background: #fdfac3; color: #0d100f; border-radius: 4px; padding: 10px 20px; display: flex; align-items: center; gap: 8px`

**Text style:** `compact-button` — Plain 500 · 14px/1.3 · tracking -0.0114em

**Observed:** Pale rectangular action with a persistent right arrow. Paired with an outlined 4px-radius demo action rather than a charcoal pill.

**States:** Declared: hover opacity 0.85 and transform translateY(-1px).

### FAQ question

**Only for:** focused use-case pages

**Use:** Handle specific implementation objections.

**CSS:** `padding: 20px 0px; display: flex; justify-content: space-between; align-items: center; gap: 16px; color: #f5f5f5`

**Observed:** Full-width 15px medium-weight question row with a small plus at right and a 6% white divider beneath its container. Closed rows form a compact list; expanded answer text is smaller and much more muted.

## Imagery and graphics

### Atmospheric software terrain

**Use:** Signature feature illustrations and focused product demonstrations.

**Observed:** Green velvety hills roll beneath violet skies, sometimes cut by a luminous green stream. Light is soft but directional, with dark valley shadows, fine granular texture and lavender haze. Dark, front-facing software windows sit at the center, occupying roughly two thirds of the media width; the landscape remains clearly visible around them.

**Transfer:** Stage the new product's authentic workflow over a similarly tactile synthetic landscape. The minimum version is a textured SVG terrain with a legible dark result panel inside a Glass shell, not a bare gradient rectangle.

**Build:** Layer a lilac-to-dusk sky behind three broad SVG hill paths: deep green at the back, a brighter moss ridge across the middle, near-black foreground. Add a soft pale-green rim on upper hill edges and SVG feTurbulence at low opacity for the velvety grain. Keep the horizon in the upper third and a central open zone for the glass-framed interface; use the Violet stage palette for the sky and forest action tones for terrain.

### Ambient product stage

**Use:** The large product reveal accompanying the marketing opening.

**Observed:** One wide, dark app window fills nearly the content width on a full-bleed lavender, violet and blue field. Fine bright edging and a broad dark shadow give the window physical depth. Real light interface content can appear within the dark app chrome.

**Transfer:** Show a coherent task in progress and its outcome, not an inventory of unrelated screens. Without a complete app, construct one credible workflow with a sidebar, working area and result pane.

**Build:** Use the Violet stage surface; add oversized low-opacity radial violet and blue clouds behind the Product window. At desktop, inset the window by the main container padding and 76.3px vertically. Preserve a crisp 10px corner against the blurred field.

### Clipped workflow miniatures

**Use:** Bottom halves of capability cards.

**Observed:** Small forms, payment summaries and account rows overlap inside purple-and-blue square backdrops. Some panels extend beyond the square's edge, making the workflow look larger than the available tile.

**Transfer:** Use one recognizable operation per card, with a short result state rather than a miniature full dashboard.

**Build:** Create a square violet-to-blue gradient, place a translucent rounded frame slightly off-center, and stack two or three dark 8px-radius rows within it. Clip the outer square so selected interface edges run beyond the boundary.

### Fading dot field

**Use:** Signature atmosphere around the closing conversion statement.

**Observed:** Tiny, faint gray dots form a softly warped field around the centered text. Density and brightness fade at the top, bottom and behind the headline; it never becomes a bright starfield. Focused use-case closings compress the dots into a low horizontal band.

**Transfer:** Always include the field as a subtle counterpoint to the typography, preserving an undistracted center.

**Build:** Draw small SVG circles in offset rows with modest sinusoidal row displacement. Use white at low opacity, vary radius subtly, then apply a vertical mask transparent at 0%, opaque at 22% through 78%, transparent at 100%. Add a radial dark mask behind the copy; exact dot positions are not essential.

### Monumental identity

**Use:** Signature footer anchor on every page type.

**Observed:** An extended, heavy white custom wordmark spans nearly the entire content width, 1284px by 275px at desktop, after a substantial empty interval below navigation columns.

**Transfer:** Use the new identity at the same architectural scale. If no wide custom mark exists, set a short name in a heavy extended sans and fit it as vector lettering rather than inflating ordinary body type.

**Build:** Create an SVG with the new wordmark, preserve its aspect ratio and scale to the content width. Keep the surrounding canvas dark, with 160px above and a compact utility row below.

### Customer proof media

**Only for:** customer proof collections

**Use:** Story cards and logo bands.

**Observed:** Landscape images combine centered white customer logos on flat branded color fields, softly glowing abstract art, and occasional candid people photography with the logo overlaid. A separate logo band is monochrome white on black.

**Transfer:** Use approved customer assets and consistent media framing. Keep photography inside the tiles rather than making it a general page backdrop.

### Icons

**Observed:** Fine outline SVG arrows dominate: 16px, 1.5px round strokes in sage, with 18px checks on plan lists. Small utility symbols use muted gray; larger security glyphs sit low within cards and remain subdued.

**Transfer:** Choose simple rounded line icons, not filled multicolor pictograms for marketing navigation. Colorful service marks belong only inside demonstrations or proof media.

## Section recipes

How recurring sections are built.

### First screen: Wide promise and product reveal

**Observed:** A fixed 64px Fixed navigation sits above a dark opening. The main content begins 130.2px from the top with a full-content-width, two-line display headline. Its 137.4px type dominates the upper half of the first screen, aligned left rather than centered. A 56.2px interval separates it from a support row: a 440px paragraph on the left, Primary button and Secondary button aligned to the row's top at the far right. After a 122.4px dark interval the full-width Violet stage begins at about 683px; its Product window begins around 759px and occupies nearly the full content width. Within the first 900px, the complete promise, support and actions are visible, plus the top of the product window. Most of the working interface continues below the fold. Layers run from Canvas to Violet stage to Product window and app content.

**Transfer:** Write a similarly broad benefit statement and pair it with one concrete task scene. A constructed workflow panel is sufficient when no finished product media exists. Story indexes instead open with a one-line index-display and logo band; pricing opens with pricing-display, a short explanation and plan cards. Focused use-case pages use a small topic label, use-case-display, a support/action row and a landscape-backed product scene beginning within the first screen.

**Avoid:** Do not turn the opening into a centered title above a tiny floating app thumbnail, or place the colorful art behind the headline itself.

**Text style:** `display` — Plain 500 · 137.4px/1 · tracking -0.03em

### Wide section heading pair

**Observed:** Major section leads use heading-lg, often wrapping across two lines. Supporting copy starts 40px below, while an Exploration link can sit far right on the same support row. Grids follow after 93.6px. On focused use-case pages a 60px heading and muted paragraph share two bottom-aligned columns with a 40px gap.

**Transfer:** Use the large title to name an outcome, then let a short paragraph and one link establish context without adding an eyebrow to every section.

**Text style:** `heading-lg` — Plain 500 · 72px/1.05 · tracking -0.025em

### Capability shelf

**Observed:** Four Capability cards span the main container with 12px gaps. Each uses modest text above a clipped workflow miniature. A broad heading introduces the shelf; the individual titles stay at 16px despite the large section scale.

**Transfer:** Organize sibling capabilities into a small, scannable family and let each illustration demonstrate one operation.

### Alternating feature chapters

**Observed:** Split feature bands pair equal copy and media columns. The copy is vertically centered, with a feature-heading, 28px paragraph gap and 40px link interval. Atmospheric software terrain fills the media half. Bands alternate media sides and are separated by 160px dark intervals.

**Transfer:** Use independent benefit chapters; preserve the alternating visual weight without forcing a fixed number of sections.

**Text style:** `feature-heading` — Plain 500 · 56px/1.1 · tracking -0.02em

### Proof and assurance shelves

**Observed:** Story cards form a three-column proof shelf. A related assurance shelf uses four shorter washed cards with small headings, one-sentence descriptions and subdued line glyphs low in each tile. Both sit beneath major titles and generous dark breathing room.

**Transfer:** Separate demonstrated customer outcomes from technical assurances; use modest card typography for both.

### Dot-field closing

**Observed:** A 655px full-width closing uses a centered 600px heading within a 640px content group, with 16px to support and 32px to paired capsule actions. The Fading dot field occupies the background. The focused use-case version widens the heading to 960px, uses use-case-closing and rectangular actions, then places a shallow dot band below.

**Transfer:** Conclude with a direct invitation that addresses the product's practical use; retain the dark dot-field atmosphere and compact action pair.

**Text style:** `closing-heading` — Plain 500 · 72px/1.1 · tracking -0.03em

### Identity footer

**Observed:** A 10% white top rule introduces six link columns with 24px gaps and 60px top padding. Headings are 14px medium and links are 14px muted with 12px gaps. One column offers AI-assistant prompts and a copy-prompt utility. After 160px, Monumental identity spans the content width. A small bottom row contains copyright, a green operational-status point, language and legal links. This same ending follows all page types.

**Transfer:** Keep the oversized identity and understated utility row; adapt link groups to the new product, including a useful shareable product-summary prompt.

### Technical triptych

**Only for:** focused use-case pages

**Observed:** Focused use-case chapters use three 427px-wide columns with 10px gaps. Square diagrams or Technical panels sit above the text captions. A small service-mark grid, authentication checklist or structured response makes the capability tangible; process panels then show inputs and outputs with status rows.

**Transfer:** Use three concise stages or principles for the new product, keeping each diagram readable as an operation rather than a decorative code wall.

### Pricing and comparison

**Only for:** pricing pages

**Observed:** Four equal Plan cards share one neutral treatment, then a substantial gap introduces the comparison-heading. A wider label column plus four equal plan columns forms a ruled table; category headers create open vertical intervals without heavy boxes. Column headings remain pinned beneath the navigation while scrolling.

**Transfer:** Distinguish plans through content and button intent, not a dramatically colored recommended tier.

**Text style:** `comparison-heading` — Plain 500 · 63.4px/1.05 · tracking -0.025em

### Objection rows

**Only for:** focused use-case pages

**Observed:** The use-case-heading introduces a full-width FAQ list with 40px before the first question. FAQ question rows end in a small plus and faint rules; answer text expands below rather than occupying a separate card.

**Transfer:** Use specific implementation questions rather than broad slogans.

**Text style:** `use-case-heading` — Plain 500 · 60px/1.1 · tracking -0.03em

## Page flow

**Storyline:** Promise → tangible product operation → capability and proof chapters → trust or objection handling → invitation → monumental identity.

### Broad product marketing landing page

1. **Promise** — Wide display statement with separated support and actions.
2. **Product demonstration** — Full-width violet stage carrying one working app window.
3. **Capability chapters** — A compact capability shelf followed by alternating atmospheric feature bands.
4. **Social proof** — Outcome-led story cards under a large section statement.
5. **Trust** — Short assurance tiles with subdued glyphs.
6. **Closing call** — Dot-field invitation and shared identity footer.

**Transfer:** Use the strongest operational proof near the promise; rearrange later chapters around buyer concerns.

### Customer proof index

1. **Orientation** — Monumental one-line title and a monochrome logo band.
2. **Social proof** — Three-column story grid with outcome headlines and branded landscape media.
3. **Closing call** — Shared dot-field invitation followed by six-column footer and giant wordmark.

**Transfer:** Keep this type more editorial and grid-led than the default product story.

### Focused use-case landing page

1. **Promise** — Topic label, smaller two-part headline, separated support/actions and landscape product film.
2. **Capability proof** — Three illustrated principles with captions.
3. **Process explanation** — Three technical request/result panels.
4. **Audience fit** — Four compact icon-led applications.
5. **Objection handling** — Full-width FAQ rows.
6. **Closing call** — Wide centered outcome statement, rectangular actions, low dot band and shared giant-wordmark footer.

**Transfer:** Explain the new workflow through concrete inputs, operations and outputs before addressing implementation objections.

### Pricing and purchasing decision

1. **Orientation** — Short page title and concise explanation of the charging model.
2. **Pricing** — Four aligned plan cards with bottom-aligned full-width buttons.
3. **Detailed comparison** — Long grouped rate table with sticky column labels, faint rules and contextual help.
4. **Closing call** — Shared dot-field conversion section and monumental identity footer.

**Transfer:** Make pricing legible through alignment and category spacing rather than promotional badges.

## Writing

Direct, technically fluent and calmly confident. Benefits are expressed as practical operations and outcomes, with approachable wording rather than an abstract AI manifesto.

**Do not copy:** Do not reuse Deck's name, custom lettering, customer logos, customer stories, security certifications, portal counts, pricing figures or performance claims. Source quotations below illustrate cadence only; substitute substantiated facts and the new product's identity.

- **Addressing the reader:** Speak to the reader as you and your; describe what the product does by naming it. Use we sparingly for reassurance and invitations.
- **Rhythm:** Headlines favor compact clauses, sometimes paired by a period. Support is one to three short sentences; fragments such as No manual downloads add emphasis without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the actor and the boundary it removes, or contrast many inputs with one result. | 5–10 words | “Agents that connect where APIs don't”<br>“Thousands of portals. One structured invoice.” |
| Feature heading | Human, benefit-led statement rather than a taxonomy label. | 3–7 words | “Your users' logins, handled safely”<br>“Nothing happens in the dark” |
| Support | Describe a concrete operation, then explain its effect in ordinary language. | 20–40 words | “Describe the task in plain language, set the website, and choose the output format. [Brand] figures out the steps and learns each site as it goes.” |
| Process heading | A terse chain of active verbs. | 3 words | “Store. Fetch. Receive.” |
| Proof title | Customer plus achieved outcome; quantify only when verified. | 6–10 words | “Rampart built 20 integrations in a day” |
| Actions | Short verb-led invitation; direct rather than playful. | 2–4 words | “Get Started”<br>“Talk to Sales”<br>“View Customer Stories” |
| Closing | Put the product into the reader's work, followed by a low-pressure choice. | 6–9 words plus one short support line | “Put agents to work in your product.”<br>“Start building or talk to us about scale.” |

**Words and phrasing to use:** work; run; connect; built for; your users; structured; on your behalf; every run; start building

**Avoid:** revolutionary; magical; supercharge; unleash; next-generation; limitless; world-class

**Rules:**

- Explain the operation before naming a technical abstraction.
- Use concrete objects and verbs in card descriptions.
- Let practical contrasts carry emphasis: no manual step, one consistent result.
- State assurances in plain language and support them with specific mechanisms.
- Use the customer's outcome as the story title, not a decorative testimonial quote.

## Do's and Don'ts

### Do

- Keep the default opening at weight 500 with line height 1 and -0.03em tracking.
- Align opening text, card grids and footer to the same 77.8px desktop side inset.
- Keep card grid gaps at 12px and card inner padding at 20px.
- Use real workflow panels within 18px glass rims over tactile terrain.
- Keep default conversion buttons 44px tall and capsule-shaped, with a 12px pair gap.
- Preserve the faint 3% white informational surfaces against the green-black canvas.
- Give the closing statement a centered 600px measure and faint surrounding dots.
- Finish with a white identity filling the content width after 160px of breathing room.

### Don't

- Do not make all major headlines 700-weight; their broad medium-weight shapes carry the hierarchy.
- Do not replace the dark green-black canvas with neutral pure black throughout.
- Do not round every marketing card to 18px; that radius belongs to the glass shell.
- Do not apply colored gradients to prose-heavy cards; color belongs to the visual stages.
- Do not enlarge card titles to compete with the 56px feature-band titles.
- Do not make the green primary action white or neon; its forest tone is deliberately restrained.
- Do not emphasize one pricing plan with a bright full-card fill; the plan surfaces stay equal.
- Do not put bright multicolor syntax or service icons into general navigation.
- Do not reduce the footer to links alone; the monumental identity is part of the composition.

## Motion and responsive

### Motion

**Observed:**

- Headline and support entrances declare heroBlurIn at 0.6s ease; the main headline is delayed 0.05s and support 0.2s.
- The app window declares a 0.8s ease fade with a 0.4s delay; the ambient stage declares a 50s ease-in-out infinite cycle.
- Primary and secondary pills declare background-color 0.2s, transform 0.2s and padding 0.35s cubic-bezier(0.22, 1, 0.36, 1).
- Informational cards declare background-color 0.3s; footer links declare color 0.3s cubic-bezier(0.4, 0, 0.2, 1).
- Operational status points declare a 3s ease-in-out infinite pulse.

**Transfer:**

- Keep the headline's reveal brief and the surrounding atmosphere much slower than reading speed.
- Use working-state animation within product scenes rather than turning marketing paragraphs into continuous motion.

**Unknown:**

- Exact keyframe transforms and the dot field's runtime behavior are not specified here.

### Responsive

**Observed:**

- Width breakpoints include 480px, 640px, 768px, 900px, 960px and 1024px; focused use-case styles also include 1200px.
- Feature, closing, use-case and pricing type recipes use the explicit clamp formulas listed above.

**Transfer:**

- On narrow screens, stack the support paragraph and actions below the wide headline while preserving left alignment.
- Collapse split feature bands to copy followed by terrain and keep the software scene legible rather than scaling dense interface text indefinitely.
- Reflow card shelves into fewer columns and let the footer wordmark continue spanning its content width; preserve comparison alignment with horizontal overflow when necessary.

**Unknown:**

- Exact mobile rearrangements, header menu behavior and column-collapse thresholds are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
