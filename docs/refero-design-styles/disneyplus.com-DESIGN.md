# Disney+ — cinematic abundance, electric choice

## Overview

A cinematic, near-black style that turns a broad catalogue into an inviting product stage. Bold humanist sans-serif headings and compact offer copy sit in front of richly colored photography, character art and device compositions. Cyan actions and luminous teal frames bring energy to a dense but clearly grouped subscription experience.

### Essentials

- A catalogue becomes the opening backdrop: edge-to-edge portrait artwork darkens into #040714 behind a centered 44px/1.1, weight-700 promise and a compact row of offers.
- Choice is presented immediately, not hidden behind a demo: three black 304px offer cards use 10px corners, 1px #808080 outlines and 16px gaps beneath the headline.
- Conversion glows without taking over the canvas: #33ddff is concentrated in 48px pill actions with 16px uppercase labels and 0.025em tracking; most structural area remains near-black navy.
- Headings stay human-sized while media supplies the spectacle: section leads are 40px/1.2 bold, card titles 24px/1.2 bold, and immersive art often fills half or all of a section.
- Abundance spills beyond the viewport: horizontal media rails show clipped neighboring items; portrait cards are 238px by 380px with 12px corners and a black lower fade.
- A luminous frame is a signature product stage: a cyan ring or rounded rectangle surrounds a cutout subject against dark teal atmosphere. For products without cinematic media, use a real object or interface composition in the same light frame.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ocean detail face | `#056d85` | `--color-feature-detail` | surface | Reverse information face of feature cards; not a general page background. |
| Teal band light | `#1c4757` | `--color-band-top` | background | Upper end of the narrow announcement-band gradient. |
| Deep ocean | `#02172a` | `--color-feature` | surface | Default front face of illustrated feature cards. |
| Blue band base | `#091023` | `--color-band-bottom` | background | Lower end of the narrow announcement-band gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric cyan | `#33ddff` | `--color-cyan` | action, accent | Primary conversion fills; visually related cyan light is confined to artwork. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| True black | `#000000` | `--color-black` | surface, background | Offer cards, media card foundations and cinematic image fades. |
| Midnight canvas | `#040714` | `--color-canvas` | background | Default canvas throughout the marketing experience. |
| Violet black | `#0e0b14` | `--color-footer` | background, text | Footer band and dark lettering on pale actions. |
| Action ink | `#17171c` | `--color-action-ink` | text | Lettering on cyan conversion actions. |
| Charcoal panel | `#1e1f24` | `--color-panel` | surface | FAQ rows and the foundation beneath feature-card faces. |
| Subtle table rule | `#282a36` | `--color-rule` | border | Visible comparison separator: rgba(183,184,189,0.2) over the midnight canvas. |
| Selector gray | `#3c3e48` | `--color-control` | surface | Plan-family select control. |
| Control edge | `#6f717b` | `--color-control-edge` | border | Stronger login outline over background imagery. |
| Offer edge | `#808080` | `--color-card-edge` | border | Thin visible outline around black offer cards. |
| Supporting gray | `#b7b8bd` | `--color-muted` | text, border | Paragraphs, plan details, captions and comparison labels; full-opacity rules mark major table boundaries. |
| Footer gray | `#c0c0c0` | `--color-footer-copy` | text | Closing availability and copyright line. |
| Soft white headings | `#f9f9f9` | `--color-heading` | text | Opening headline and prominent centered section titles. |
| Bright foreground | `#fafafa` | `--color-foreground` | text, action | Feature headings, FAQ questions, icons and pale action variants. |

## Typography

- **Inspire** — All marketing headings, descriptions, controls and navigation. Friendly humanist sans-serif with open counters, compact widths and decisive bold headings. If unavailable, use **Lato**. Use 400 and 700; preserve compact line lengths and avoid expanded display proportions. Font stack: "Inspire", "Lato", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inspire | 700 | 44px | 1.1 | -0.0036em | Centered first-screen promise. |
| heading | Inspire | 700 | 40px | 1.2 | normal | Section leads, image-led promotional chapters and prominent offer prices. |
| card-heading | Inspire | 700 | 24px | 1.2 | normal | Centered feature-card titles beneath artwork. |
| question | Inspire | 700 | 20px | 1.2 | normal | FAQ questions and short plan names. |
| body-lead | Inspire | 400 | 18px | 1.4 | normal | Supporting paragraphs in cinematic promotional sections and prominent text links. |
| body | Inspire | 400 | 16px | 1.4 | normal | Plan explanations, feature detail faces and FAQ answers. |
| body-strong | Inspire | 700 | 16px | 1.4 | normal | Plan pricing labels, comparison attributes and inline step labels. |
| action | Inspire | 400 | 16px | 1 | 0.025em, uppercase | Primary and pale pill-action labels. |
| body-small | Inspire | 400 | 14px | 1.4 | normal | Compact offer-card descriptions and secondary plan-navigation links. |
| login | Inspire | 400 | 14px | 1 | 0.025em, uppercase | Compact outlined navigation action. |
| caption | Inspire | 400 | 12px | 1.4 | normal | Media metadata and compact qualifying copy under offers. |
| footer-link | Inspire | 400 | 12px | 22px | normal | Dense footer links and closing availability line. |

**Notes:**

- The opening headline is only slightly larger than section leads; scale and drama come mainly from artwork, not enormous typography.
- Use bold headings with normal tracking below the opening size. Body text is regular; uppercase and positive tracking belong to controls rather than prose.
- Use near-white for titles and muted gray for explanatory content; underline inline links rather than coloring them cyan.

## Layout

**Density:** Comfortable section framing around dense media and purchase information; broad dark margins separate compact cards and comparison rows.

### Spacing

| Value | Use |
| --- | --- |
| 12px | Feature-card internal flex gap and compact stacked content. |
| 16px | Offer-card and feature-grid gutters; vertical separation between FAQ rows. |
| 20px | Comparison-cell vertical padding and feature-title bottom padding. |
| 24px | Paragraph margins, promotional split gutters, FAQ-summary padding and card side padding. |
| 32px | Offer-card top padding. |
| 33.1px | Shallow top or bottom framing around catalogue rails and feature sections. |
| 40px | Feature-card top inset and desktop navigation side padding. |
| 55px | Visual separation between catalogue section titles and media rails. |
| 80.6px | Desktop side inset and deep promotional-section padding. |
| 144px | Opening content top inset. |

### Containers and grids

- **marketing inset**: side padding 80.6px. Most desktop sections frame content inside a broad inset, leaving a 1279px working area at 1440px.
- **opening choices**: 3 columns · gap 16px. Centered row of 304px offer cards under the promise, occupying about two thirds of desktop width.
- **feature grid**: max width 1600px · 3 columns · gap 16px · side padding 80.6px. Centered illustrated cards, each capped at 380px, arranged in two rows.
- **comparison**: max width 1025px · 3 columns. Centered comparison with 42% reserved for attributes and the remainder divided equally between two plans.
- **promotional split**: 2 columns · gap 24px. Copy occupies the left half; art dominates the right half and can extend into the full-bleed background.
- **footer columns**: max width 1024px · 6 columns · gap 24px. Narrow 136px link columns centered inside a restrained footer content width.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 1000px |
| offer cards | 10px |
| media and feature cards | 12px |
| FAQ rows | 8px |
| selector | 4px |

## Surfaces and depth

### Surfaces

#### Midnight canvas · level 0

**Use:** Default continuous page field.

**CSS:** `background: #040714; color: #b7b8bd`

**Observed:** A dark navy field joins media rails, pricing, benefits and objection handling without alternating light sections.

**Transfer:** Let imagery introduce variety while keeping the page structure consistently dark.

#### Black offer panel · level 1

**Use:** Purchase options on top of the opening artwork.

**CSS:** `background: #000000; border: 1px solid #808080; border-radius: 10px`

**Observed:** Opaque panels keep compact offer copy legible despite the busy background.

**Transfer:** Use a clear edge rather than a drop shadow to distinguish competing choices.

#### Ocean feature face · level 1

**Use:** Illustrated capability cards.

**CSS:** `background: #02172a; border: 1px solid transparent; border-radius: 12px`

**Observed:** The front is dark ocean; the reverse information face uses #056d85 and 45px 25px 15px padding.

**Transfer:** Reserve the brighter reverse face for expanded explanation, not the entire feature grid.

#### Charcoal answer panel · level 1

**Use:** Collapsed FAQ rows.

**CSS:** `background: #1e1f24; border-radius: 8px`

**Observed:** Broad flat rectangles are separated by dark gaps, without bevels or shadows.

**Transfer:** Group each question and its revealed answer in one panel.

#### Poster lower fade · level 1

**Use:** Legibility treatment over the lower half of media cards.

**CSS:** `background: linear-gradient(to top, #000000, rgba(0, 0, 0, 0)); border-radius: 0px 0px 12px 12px`

**Observed:** The fade sits over the lower 190px of a 380px portrait card, carrying title art and metadata into black.

**Transfer:** Fade rich photography into its backing rather than adding a separate opaque caption slab.

#### Announcement gradient · level 0

**Use:** Compact full-width promotional notice.

**CSS:** `background: linear-gradient(0deg, #091023, #1c4757)`

**Observed:** A 98px strip holds a small visual, one bold sentence and a pale action horizontally.

**Transfer:** Use for one current product announcement, with much less visual weight than a full chapter.

#### Closing violet black · level 0

**Use:** Footer ending.

**CSS:** `background: #0e0b14`

**Observed:** Slightly warmer than the page field, enclosing columns, social marks and a centered brand sign-off.

**Transfer:** End with useful navigation and a compact identity, not another oversized sales billboard.

## Components

### Minimal navigation

**Use:** Brand orientation and account access.

**CSS:** `position: absolute; display: flex; justify-content: space-between; align-items: center; padding: 8px 40px; gap: 16px`

**Text style:** `login` — Inspire 400 · 14px/1 · tracking 0.025em · uppercase

**Observed:** Small white identity at left and one outlined login pill at right sit directly over the opening art; there is no desktop mega-menu.

### Primary button

**Use:** Offer selection and focused conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #33ddff; color: #17171c; height: 48px; padding: 12px 16px; max-width: 320px; border-radius: 1000px; text-transform: uppercase; letter-spacing: 0.4px`

**Text style:** `action` — Inspire 400 · 16px/1 · tracking 0.025em · uppercase

**Observed:** Buttons span the available offer-card interior. A pale white variant appears in image-led bundle chapters while retaining the same silhouette and label treatment.

### Login button

**Use:** Secondary navigation action over imagery.

**CSS:** `background: rgba(0, 0, 0, 0.8); color: #fafafa; border: 2px solid #6f717b; border-radius: 1000px; height: 36px; padding: 8px 12px`

**Text style:** `login` — Inspire 400 · 14px/1 · tracking 0.025em · uppercase

**Observed:** Compact width follows its label and stays visually subordinate to cyan purchase actions.

### Offer card

**Use:** Present a small number of purchasable configurations.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; background: #000000; border: 1px solid #808080; border-radius: 10px; width: 304px; padding: 32px 24px 24px`

**Text style:** `body-small` — Inspire 400 · 14px/1.4

**Observed:** Product identity row comes first, followed by a bold starting price, savings, a short description and an aligned bottom Primary button. One card can carry a small pale recommendation tab straddling the top border.

**Transfer:** Keep card heights aligned and compare meaningful differences rather than stacking long feature inventories.

### Poster card

**Use:** Dense visual discovery and ranked proof.

**CSS:** `position: relative; background: #000000; width: 238px; height: 380px; border-radius: 12px; overflow: hidden`

**Text style:** `caption` — Inspire 400 · 12px/1.4

**Observed:** Portrait imagery fills the upper region, with Poster lower fade, centered title artwork and one small bottom metadata line. Ranked artwork places a bright numeral on a diagonal teal corner. Landscape rail variants use 238px by 134px art.

**Transfer:** Use original product results, customer outcomes or use-case images; keep card furniture minimal.

### Feature information card

**Use:** Explain benefits without making the default grid text-heavy.

**CSS:** `display: flex; flex-direction: column; gap: 12px; background: #02172a; border: 1px solid transparent; border-radius: 12px; max-width: 380px; height: 482px; padding-top: 40px`

**Text style:** `card-heading` — Inspire 700 · 24px/1.2

**Observed:** A large central illustration occupies the upper region and a centered title anchors the bottom. A 24px information icon sits at the upper right. The reverse face repeats the title and adds centered body copy on Ocean detail face.

**Transfer:** Pair each capability with one tangible object or device scene instead of a generic line icon.

### FAQ row

**Use:** Resolve detailed questions near the end of the journey.

**CSS:** `background: #1e1f24; border-radius: 8px; min-height: 80px`

**Text style:** `question` — Inspire 700 · 20px/1.2

**Observed:** Native disclosure construction uses a padded summary, question at left and plus at right. Summary padding is 24px; expanded prose uses the body recipe and muted gray.

**Transfer:** Keep long answers inside disclosures so the resting section remains a regular stack.

### Comparison row

**Use:** Detailed feature and price evaluation.

**CSS:** `display: grid; grid-template-columns: 42% repeat(2, 1fr); border-bottom: 1px solid rgba(183, 184, 189, 0.2)`

**Text style:** `body` — Inspire 400 · 16px/1.4

**Observed:** Attribute names are left-aligned and bold; plan values, checks and dashes are centered. Rows range from 66px to 91px as labels wrap. Large white checks provide strong scanning cues.

### Plan selector

**Use:** Switch the family of products being compared.

**CSS:** `background: #3c3e48; border-radius: 4px; width: 300px; height: 49px; padding: 12px 32px 12px 12px; border: none`

**Observed:** A compact gray select is centered between the heading/support pair and plan columns, with a light down-chevron at the trailing edge.

### Footer directory

**Use:** Utility, exploration and final brand closure.

**CSS:** `background: #0e0b14; padding: 19px 0px 24px`

**Text style:** `footer-link` — Inspire 400 · 12px/22px

**Observed:** A language control precedes six narrow columns; category headings are 16px and links 12px/22px. Below the columns, muted social icons sit in a centered row, followed by a white identity mark and one subdued availability/copyright line.

**Transfer:** Finish with navigational depth rather than a repeated purchase CTA.

## Imagery and graphics

### Darkened catalogue wall

**Use:** Opening atmosphere behind the promise and offer cards.

**Observed:** Tall colorful posters form multiple edge-to-edge rows. The upper row remains readable as imagery while lower rows sink into navy. A restrained dark wash protects the white headline; opaque black offers sit above it.

**Transfer:** Assemble a wall of authentic outcomes, objects or use cases for the new product. With limited media, create distinct art-directed product stills rather than repeating a single image.

**Build:** Lay portrait images in a tightly spaced CSS grid that overflows both edges. Overlay a uniform rgba(0,0,0,0.4) scrim, then a vertical gradient from transparent at the top to #040714 near the lower half. Keep navigation and headline above both layers; keep offer panels fully opaque.

### Luminous product frame

**Use:** Signature stage for a promotional object or capability.

**Observed:** A tilted physical card floats over a bright teal ring in one promotion. Another uses a rounded cyan rectangle with cutout figures breaking its top edge. Black and deep teal atmosphere surround the object, with concentrated glow rather than a luminous entire canvas.

**Transfer:** Stage a real product object, interface panel or sharply masked customer scene inside a luminous frame. The minimum version is a clean cutout over a cyan outline and soft teal halo.

**Build:** Use an SVG ellipse or rounded rectangle behind the subject, with a 4px cyan stroke and a duplicate stroke blurred by 20px at 0.35 opacity. Add a broad rgba(51,221,255,0.15) radial halo behind the frame. Mask the subject cleanly, overlap the upper edge, and fade its lower edge into the dark backing. These are construction guidance, not fixed gradient stops.

### Cinematic split artwork

**Use:** Full-width product-family promotional chapters.

**Observed:** The left half is nearly black for copy. On the right, large figures or product art are backed by stadium light, colored streaks or blue-violet atmosphere; the image fades into black toward the copy and lower edge. Smaller landscape tiles continue the visual catalogue underneath.

**Transfer:** Use one strong hero composition per chapter, not an evenly lit stock-photo rectangle. For software, composite a primary interface or device with related outputs, lighting it from the right.

### Illustrated benefit objects

**Use:** Front faces of Feature information cards.

**Observed:** Device groups, a phone, a profile avatar and luminous membership-like cards are centered on deep ocean panels. Each is isolated with generous negative space and occupies far more area than its title.

**Transfer:** Use tangible metaphors and recognizable product screens; retain a consistent scale, dark backing and high-quality cutout edges. Keep interface internals subordinate to the benefit.

### Icons

**Observed:** Mostly near-white filled SVGs: 24px information marks, 32px FAQ plus signs and solid comparison checks. Small globe and chevron symbols support the language and plan selectors; social marks become muted gray at the ending.

**Transfer:** Use simple solid or optically sturdy icons at these sizes. Place information at upper-right card corners and disclosure symbols at the far-right edge of summaries.

## Section recipes

How recurring sections are built.

### First screen: Catalogue-backed choice opening

**Observed:** A full-bleed Darkened catalogue wall supplies the back layer of a 961px opening. Minimal navigation overlays its top. The centered display promise begins after a 144px top inset and spans roughly two thirds of the viewport as one line at desktop. A row of three Offer cards follows, using about two thirds of the page width, with black faces, large identity rows and cyan actions. Within the first 900px, the headline, all three cards, secondary discount link, qualifying copy and plan-navigation link are visible. The next announcement strip begins below this screen; there is no separate hero subtitle competing with the offers.

**Transfer:** Keep an immediate choice architecture over an atmospheric wall of product outcomes. If no media library exists, commission several original product stills or use-case compositions. A single-offer page can use one broad purchase panel while preserving the backdrop, centered promise and electric action. Detail pages can open with the Cinematic split artwork treatment.

**Avoid:** Do not replace the offer-led center with a giant abstract word, a bare gradient or a conventional left-copy/right-browser hero.

**Text style:** `display` — Inspire 700 · 44px/1.1 · tracking -0.0036em

### Compact announcement band

**Observed:** Announcement gradient creates a 98px horizontal strip with a small visual, a bold 20px message, pale pill action and compact terms link.

**Transfer:** Use a concise current update between larger chapters; maintain the strip's compressed proportions.

**Text style:** `question` — Inspire 700 · 20px/1.2

### Catalogue rail

**Observed:** A centered 40px heading stands above a horizontal overflow rail, separated from the imagery by about 55px. Landscape tiles provide breadth; portrait Poster cards add ranked discovery with bottom metadata. Neighboring items remain clipped at the edge.

**Transfer:** Show breadth through concrete visual examples, with category headings that explain why this group matters.

**Text style:** `heading` — Inspire 700 · 40px/1.2

### Plan evaluation

**Observed:** A centered heading and body support pair introduces Plan selector and a 1025px Comparison row system. Plan identities and names sit above cyan actions; subtle row rules, checks and short attributes handle detail. Dense qualifying text is kept below.

**Transfer:** Use for considered purchases with genuine plan differences; the control selects a family and the table compares within it.

**Text style:** `heading` — Inspire 700 · 40px/1.2

### Offer with luminous object

**Observed:** A half-width left text block uses a 40px heading with old and new prices on the headline line, then bold step labels, a cyan action and compact qualifiers. The right half holds Luminous product frame around a tilted object; the section has 80.6px framing.

**Transfer:** Use a special offer or onboarding incentive with a concrete object metaphor. Keep the old price struck through rather than detached into a separate badge.

**Text style:** `heading` — Inspire 700 · 40px/1.2

### Immersive promotional chapter

**Observed:** Cinematic split artwork carries the right half while a left-aligned 40px heading, 18px paragraph and optional pale action sit on the dark side. Content is framed by 80.6px padding. Related landscape tiles can form a rail along the bottom.

**Transfer:** Build a focused chapter for a product family or major benefit, giving one artwork and one short text block the entire stage.

**Text style:** `heading` — Inspire 700 · 40px/1.2

### Illustrated capability grid

**Observed:** A centered heading introduces six Feature information cards in three columns with 16px gutters. Repeated dark ocean fronts show large objects above 24px titles; information controls reveal richer teal detail faces.

**Transfer:** Use only as many cards as the content warrants, but preserve illustration-led fronts and hidden supporting detail.

**Text style:** `heading` — Inspire 700 · 40px/1.2

### Objections and directory ending

**Observed:** A centered 40px FAQ heading precedes eight broad FAQ rows with 16px dark gaps. The page then closes in Closing violet black with Footer directory, a language control, six link columns, centered social marks, identity and muted legal line. No monumental closing headline or final purchase panel interrupts the ending.

**Transfer:** Resolve practical hesitation, then end with useful navigation and a compact identity sign-off. Adapt the categories to the new product without turning the footer into another campaign.

**Text style:** `heading` — Inspire 700 · 40px/1.2

## Page flow

**Storyline:** Immediate promise and choice → breadth of examples → detailed evaluation → focused promotional chapters → practical benefits → objection handling → utility and identity closure.

### A subscription marketing landing page balancing immediate purchase with extensive discovery and reassurance

1. **Promise and conversion** — Cinematic catalogue backdrop, centered promise and three purchase options.
2. **Freshness and breadth** — A compact announcement followed by landscape and ranked portrait media rails.
3. **Evaluation** — A plan selector and restrained feature-comparison matrix.
4. **Targeted incentive** — A special price and simple steps opposite a glowing product object.
5. **Capability chapters** — Large split-background promotions, each supported by relevant visual examples.
6. **Practical benefits** — Illustration-led information cards explain everyday usage.
7. **Objection handling** — Collapsed FAQ stack contains detailed service and plan answers.
8. **Utility closure** — Dense footer directory, social icons and a centered identity finish the experience.

**Transfer:** Lead with a purchasable promise, then let examples earn interest and comparison resolve choice. Select and reorder the middle chapters to suit the product while retaining cinematic imagery, visible choice and a practical ending.

## Writing

Direct, welcoming and benefit-led, with the enthusiasm of a catalogue invitation rather than a technical manifesto. Claims become concrete through named inclusions, clear prices and straightforward conditions.

**Do not copy:** Do not reuse Disney identities, franchise artwork, partner logos, entertainment titles, prices, savings percentages, availability claims or legal language. Source quotations illustrate voice only.

- **Addressing the reader:** Speak to the reader as you and your. Refer to the product by name when explaining access, eligibility or plan differences; avoid a self-congratulatory we narrative.
- **Rhythm:** Short rhythmic promises contrast with longer descriptive offer headings. Supporting copy is usually one or two information-rich sentences; actions use short literal verbs. Detailed qualifications remain visually secondary.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Parallel compact clauses ending in a reader-centered benefit. | 8–12 words | “Every Story. Every Genre. Bundled Your Way.” |
| Section invitation | Plain imperative or reader benefit, without an eyebrow. | 3–7 words | “Choose your plan”<br>“Watch the way you want” |
| Promotional headline | Lead with what is newly available or what the reader gets; name the offer explicitly. | 8–18 words | “New: Watch ESPN College Football all season long with [Brand]” |
| Supporting line | Explain the task and remove a practical concern in short direct clauses. | 12–20 words | “Use the drop-down menu to compare plans.* Switch or cancel** anytime.” |
| Primary action | Literal selection or benefit-claiming verb, displayed in capitals. | 1–4 words | “SELECT”<br>“CLAIM YOUR DISCOUNT” |
| Benefit title | Action plus concrete capability, with no abstract slogan. | 3–9 words | “Set parental controls”<br>“Watch on multiple devices at once” |
| FAQ | Ask the reader's real practical question, often combining definition and distinction. | 7–18 words | “What is ESPN Unlimited? How is it different from ESPN Select (formerly ESPN+)?” |

**Words and phrasing to use:** your way; choose; get; discover; access; new; included; plan; anytime

**Avoid:** revolutionary ecosystem; disruptive; unparalleled innovation; enterprise-grade synergy; vague lifestyle superlatives

**Rules:**

- Name what is included before decorating the claim with enthusiasm.
- Keep purchase actions literal and distinguish the main transaction from learn-more links.
- When pricing or eligibility needs qualification, attach a clear marker and compact explanation rather than weakening the headline with a paragraph of caveats.
- Use numbered steps for a small eligibility or onboarding process; keep the labels bold and the explanations regular.

## Do's and Don'ts

### Do

- Keep the page field #040714 and allow rich color primarily inside imagery and compact cyan actions.
- Set the opening promise at 44px/1.1 bold and section leads at 40px/1.2 bold.
- Use 48px pill conversion actions and a distinctly smaller 36px outlined login control.
- Give black purchase panels 10px corners and 1px #808080 edges.
- Keep media and feature cards at 12px corners, with 16px grid gutters.
- Preserve the 42% attribute column in desktop comparison layouts so long labels remain readable.
- Include the luminous cyan frame device around a tangible product scene.
- Close with charcoal disclosures and a violet-black directory rather than an unrelated light section.

### Don't

- Do not turn cyan into the dominant page background; its contrast depends on the near-black field.
- Do not add drop shadows to every card; flat surfaces and thin edges supply separation.
- Do not apply uppercase tracking to descriptive paragraphs or benefit headings.
- Do not make every corner a pill: 10px purchase panels, 12px media cards and 8px FAQ panels have distinct jobs.
- Do not use hairline outline illustrations as the primary benefit imagery; the cards depend on substantial colored objects.
- Do not replace subtle comparison rules with a bright boxed spreadsheet grid.
- Do not stretch purchase buttons taller than the 48px action rhythm to manufacture importance.
- Do not scatter bright accent colors into footer links; the ending stays white and gray on dark violet black.

## Motion and responsive

### Motion

**Observed:**

- Feature cards have separate front and reverse faces; the reverse is rotated 180 degrees around the vertical axis and both sides hide their back faces.
- Horizontal media rails expose additional items beyond the viewport.

**Transfer:**

- Keep the front-to-detail relationship of information cards understandable without relying on decorative movement.
- Retain the sense of catalogue continuation through horizontal scrolling rather than fitting every example into a static desktop grid.

**Unknown:**

- Transition durations, easing, autoplay behavior and hover/focus visual treatments are not established.

### Responsive

**Observed:**

- Styles define width breakpoints at 768px and 1025px.
- Desktop sections use broad proportional insets; feature fronts have a 380px maximum width and a narrower 258px maximum in smaller-width rules.
- Comparison rows switch toward wrapping flex layouts at narrower widths.

**Transfer:**

- On narrow screens, keep purchase actions easily reachable and let offer choices or catalogue examples scroll horizontally instead of shrinking their text.
- Stack promotional copy and artwork while preserving the luminous product frame and a dark text-safe region.
- Reflow comparison labels above their associated plan values rather than compressing the desktop matrix.

**Unknown:**

- Exact mobile ordering, typography sizes, footer disclosure behavior and artwork substitutions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
