# Ready — multiplayer on paper

## Overview

A warm, lightly speckled software style with friendly geometric headlines and vivid, softly blended product stages. Charcoal type and violet annotations sit on an ivory canvas, while interface windows float inside blue, peach and plum artwork. It suits collaborative tools and productivity products that want to feel human and playful without losing product detail; the text is sparse and the demonstrations are expansive.

### Essentials

- Headlines feel like a friendly poster with someone editing it live: GT Walsheim 700 at 64px/1 for the opening and 56px/1 for chapters, normal tracking, with a violet selection, caret and small collaborator flag on a meaningful phrase.
- Paper surrounds the software: #f5f4f1 with fine irregular grain remains the dominant canvas; saturated color belongs mainly inside 32px-radius feature stages and the lower product glow, not behind every section.
- The opening is a centered promise above a layered app scene: a 540px headline measure, 400px supporting paragraph, 96px gap before a 1280px-wide window, and a narrower 714px window floating in front.
- Controls stay lighter than the artwork: capability labels use 24px-radius outlines with 4px 12px padding and violet text; the visible composition has no prominent filled conversion button. Carry that restrained, rounded shape language into new controls.
- Product proof is a staggered collage rather than equal tiles: 16px gutters, wide and narrow 32px-radius stages, white 24px/30px titles, 16px/24px descriptions and cropped interface details.
- Handmade violet marks and a luminous finale keep the page personal: thin underlines, loops and three-stroke bursts accompany the geometry; a bottom-centered #351caf radial glow supports a full-width product view before a compact two-line closing statement. When media is unavailable, make a credible interface fragment and simple SVG marks rather than replacing these devices with stock photography.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Collaborator violet | `#7366fe` | `--color-violet` | accent, text | Opening eyebrow, caret and collaborator flag. |
| Deep violet glow | `#351caf` | `--color-glow` | background | Bottom-centered radial light behind the large product finale. |
| Annotation blue | `#5c6ae4` | `--color-annotation` | text, accent | Hand-drawn marks and capability labels. |
| Deep purple stage base | `#55269c` | `--color-stage-purple` | surface | Base for the smallest deep-purple feature stage. |
| Plum stage base | `#7b4096` | `--color-stage-plum` | surface | Base for a violet feature stage. |
| Blue stage base | `#6c77b0` | `--color-stage-blue` | surface | Base for the wide blue-to-peach feature artwork, not a flat page band. |
| Rose stage base | `#8f4d75` | `--color-stage-rose` | surface | Base for a warm plum feature stage. |
| Slate stage base | `#6873a5` | `--color-stage-slate` | surface | Base for a secondary wide interface stage. |
| Lilac stage base | `#817da6` | `--color-stage-lilac` | surface | Base for the tall tools stage, blended with blue and peach. |
| Violet selection wash | `#d5d1f4` | `--color-selection` | surface | Visible wash from #7366fe at 25% over paper, used behind selected headline words. |
| Capability outline | `#d6d8ee` | `--color-chip-edge` | border | Visible result of #5c6ae4 at 20% over paper; delicate capability-chip outline. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#333333` | `--color-ink` | text | Headlines and body copy. |
| Footer grey | `#8b8c96` | `--color-muted` | text, link | Small utility links. |
| Paper hairline | `#dddcd9` | `--color-edge` | border | Visible result of black at 10% over the paper canvas; sticky navigation separator uses rgba(0,0,0,0.1). |
| Sand paper | `#f5f4f1` | `--color-canvas` | background | Dominant warm page canvas. |
| White | `#ffffff` | `--color-white` | text, surface | Feature-stage text and light interface framing. |

## Typography

- **GT Walsheim** — Opening, chapter and closing headlines. Bold geometric sans with circular counters and an approachable, substantial silhouette. If unavailable, use **Outfit**. Use 700; preserve the compact line height and moderate headline width. Font stack: "GT Walsheim", "Outfit", sans-serif.
- **GT America Standard** — Supporting paragraphs, feature titles, labels and utility text. Straightforward neo-grotesk that balances the rounder display face. If unavailable, use **Public Sans**. Use 300, 400 and 500 with normal tracking except the eyebrow. Font stack: "GT America Standard", "Public Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | GT Walsheim | 700 | 64px | 1 | normal | Centered opening promise, usually two tightly stacked lines. |
| heading | GT Walsheim | 700 | 56px | 1 | normal | Chapter leads and the compact closing statement. |
| card-heading | GT America Standard | 500 | 24px | 1.25 | normal | White feature-stage titles. |
| body-lead | GT America Standard | 400 | 18px | 24px | normal | Short supporting paragraphs on paper. |
| body | GT America Standard | 400 | 16px | 1.5 | normal | Feature descriptions and capability chips. |
| collaborator | GT America Standard | 500 | 16px | 1.5 | normal | Small white name flag attached to the headline caret. |
| caption | GT America Standard | 400 | 14px | 20px | normal | Footer sign-off. |
| utility-link | GT America Standard | 300 | 14px | 20px | normal | Muted footer links. |
| eyebrow | GT America Standard | 500 | 12px | 16px | 2px, uppercase | Small violet category label above the opening headline. |

**Notes:**

- Keep the large geometric headings bold and at a line height of 1; do not add negative tracking merely to make them look fashionable.
- The 18px lead copy and 16px card descriptions share a 24px line height. Limit their measures rather than filling the available width.
- Uppercase tracking is reserved for the 12px eyebrow; feature titles and chips remain mixed case.

## Layout

**Density:** Airy around chapter introductions, compact inside interface demonstrations; large media carries most of the information.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Footer link gap and small horizontal chip separations. |
| 10px | Feature-title to description spacing. |
| 16px | Main grid gutters, outer minimum side padding and eyebrow-to-title gap. |
| 24px | Chapter heading to support copy; support copy to capability labels. |
| 32px | Opening headline to support copy and gallery card spacing. |
| 40px | Feature-stage text inset from the top. |
| 48px | Feature-stage horizontal text inset, chapter vertical padding and final footer bottom margin. |
| 80px | Chapter introduction to feature mosaic; offset of the tall narrow card above its neighbor. |
| 96px | Opening copy to main product window and closing section top padding. |
| 120px | Space above the small utility footer row. |
| 128px | Opening section top padding below navigation. |

### Containers and grids

- **main-container**: max width 1280px · side padding 16px. Centered product and feature width; at a 1440px viewport its visible sides sit 80px from the edges.
- **heading-container**: max width 640px. Centered chapter introduction, with a narrower headline and paragraph inside.
- **opening-headline**: max width 540px. Two-line centered opening promise.
- **opening-support**: max width 400px. Compact centered opening paragraph, three lines at desktop.
- **feature-copy**: max width 420px. White stage copy, reduced further inside narrow cards.
- **capability-labels**: max width 470px. Centered wrapping chip cluster over a product overview.
- **feature-mosaic**: max width 1280px · 3 columns · gap 16px. Two flexible columns plus a narrow rail up to 400px wide; the wide card spans the flexible pair, the rail begins 80px higher, and the lower wide card is indented. A second arrangement uses a 560px rail with a 192px downward offset.
- **example-rail**: gap 32px. Horizontal run of 403px-wide portrait product examples extending beyond the viewport rather than shrinking to fit.

## Corner radius

| Element | Radius |
| --- | --- |
| feature-stages | 32px |
| example-cards | 24px |
| capability-chips | 24px |
| product-windows | 16px |
| selection-left-edge | 12px |
| collaborator-flag | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| product-window | `rgba(0, 0, 0, 0.1) 0px 16px 128px 0px, rgba(0, 0, 0, 0.1) 0px 1px 1px 0px` | Broad soft lift below the large opening window, plus a crisp contact edge. |
| foreground-window | `rgba(0, 0, 0, 0.2) 0px 1px 128px 0px` | The overlapping central window. |
| example-card | `rgba(0, 0, 0, 0.1) 11px 11px 40px 0px` | Repeated portrait product examples. |

### Surfaces

#### Paper canvas · level 0

**Use:** Continuous background under every chapter.

**CSS:** `background-color: #f5f4f1; color: #333333`

**Observed:** Fine, irregular grey flecks create a tactile paper texture; the grain remains subtle behind both text and media.

**Transfer:** Overlay a low-opacity monochrome noise tile over the warm base; it should read as paper, not distressed concrete.

#### Feature stage · level 1

**Use:** Colored backing for feature copy and interface details.

**CSS:** `background-color: #6c77b0; border-radius: 32px; position: relative`

**Observed:** Soft blue, lilac, peach and plum blends have fine grain; white copy sits over the calmer upper region. Other stages use the lilac, slate, rose, plum and deep-purple bases.

**Transfer:** Use diffuse overlapping color fields rather than a flat token fill; keep the brightest detail away from body copy.

#### Product glow · level 0

**Use:** Atmospheric backing behind the large final product overview.

**CSS:** `background-image: radial-gradient(circle farthest-side at 50% 100%, #351caf, rgba(245, 244, 241, 0) 80%); padding: 48px 16px 0px`

**Observed:** The top stays paper-colored and readable while violet light gathers behind the lower window.

**Transfer:** Keep the glow centered beneath the media; match its soft spread rather than making a full purple section.

#### Light window · level 2

**Use:** Foreground product framing.

**CSS:** `background-color: #ffffff; border-radius: 16px; box-shadow: rgba(0, 0, 0, 0.2) 0px 1px 128px 0px`

**Observed:** A light content pane sits below a vivid gradient title bar and overlaps a larger, quieter application window.

**Transfer:** Use a representative workflow detail, not a second full dashboard at unreadable scale.

## Components

### Sticky navigation

**Use:** Small persistent brand anchor above the product story.

**CSS:** `height: 48px; position: sticky; top: 0px; padding: 0px 16px; border-bottom: 1px solid rgba(0, 0, 0, 0.1); backdrop-filter: blur(16px); z-index: 9999`

**Observed:** A 1280px inner row places a small wordmark left and five overlapping colorful circular avatars right. No menu columns or large CTA compete with the opening.

**Transfer:** Keep identity and a small human-presence motif at opposite ends; use original avatar artwork.

### Live headline selection

**Use:** Signature collaborative annotation on the opening promise.

**CSS:** `background-color: rgba(115, 102, 254, 0.25); border-radius: 12px 0px 0px 12px; position: absolute; height: 64px`

**Observed:** The wash highlights part of the second line rather than the entire title. A 4px violet caret sits at its right edge with a name flag attached above.

**Transfer:** Anchor the wash and caret to a phrase span so their geometry follows new copy.

### Collaborator flag

**Use:** Human label attached to the headline selection.

**CSS:** `background-color: #7366fe; color: #ffffff; border-radius: 8px 8px 8px 0px; padding: 2px 8px; position: absolute`

**Text style:** `collaborator` — GT America Standard 500 · 16px/1.5

**Observed:** The flag grows rightward from the caret's upper edge and stays small enough not to become a badge headline.

### Product window

**Use:** Large opening demonstration behind the foreground detail.

**CSS:** `max-width: 100%; border-radius: 16px; box-shadow: rgba(0, 0, 0, 0.1) 0px 16px 128px 0px, rgba(0, 0, 0, 0.1) 0px 1px 1px 0px`

**Observed:** The 1280px-wide rear window is level, front-facing and softly subdued; a 714px-wide detailed window floats over its center.

**Transfer:** Use the broad window for context and the smaller one for the product's most convincing interaction.

### Example card

**Use:** Repeated workflow examples in a horizontal demonstration rail.

**CSS:** `width: 403px; border-radius: 24px; position: relative; box-shadow: rgba(0, 0, 0, 0.1) 11px 11px 40px 0px`

**Observed:** Portrait app documents pair colored gradient headers with white content; neighboring examples are partially clipped at viewport edges.

**Transfer:** Show genuinely different useful outcomes, keeping the same front-facing framing.

### Feature card

**Use:** One capability explained with concise copy and a focused interface fragment.

**CSS:** `background-color: #6c77b0; border-radius: 32px; position: relative`

**Text style:** `card-heading` — GT America Standard 500 · 24px/1.25

**Observed:** Title and description sit 40px from the top and 48px from the sides, with a 420px maximum text measure. Large interface fragments fill the lower area and may fade into the colored backing; the default wide stage is 864px by 507px.

**Transfer:** Vary wide, tall and small card silhouettes instead of repeating identical tiles.

### Capability chip

**Use:** Lightweight product capabilities beneath an overview heading.

**CSS:** `color: #5c6ae4; border: 1px solid rgba(92, 106, 228, 0.2); border-radius: 24px; padding: 4px 12px`

**Text style:** `body` — GT America Standard 400 · 16px/1.5

**Observed:** Five non-button labels wrap into two centered rows, with no leading icons or solid fill.

**Transfer:** Use short factual capabilities; do not imply click behavior unless the label really navigates.

### Footer utility link

**Use:** Low-priority legal navigation below the closing statement.

**CSS:** `color: #8b8c96; font-weight: 300; transition: color 0.2s ease-out`

**Text style:** `utility-link` — GT America Standard 300 · 14px/20px

**Observed:** Two links sit beside one another below a small brand sign-off; compact social icons occupy the far right of the footer container.

**States:** Declared: hover color #1b1e2a and outline 0px; active outline 0px. Focus-visible treatment is unknown.

**Transfer:** Preserve the light hierarchy while providing a distinct keyboard focus treatment in implementation.

## Imagery and graphics

### Layered software scenes

**Use:** Primary product proof in the opening and within feature stages.

**Observed:** Front-facing desktop windows, not angled device mockups. White content panes, colorful gradient title bars, small participant portraits and focused popovers show real collaborative activity. The main window is wider than all copy, with a second pane lifted in front; feature fragments are often clipped by the stage's lower edge or softly faded into its background.

**Transfer:** Create an authentic simplified interface for the new product with one salient workflow and a smaller detail layer. If full UI assets are unavailable, construct a few credible rows, controls and a foreground popover rather than abstract blank panels.

### Grain and color fields

**Use:** Signature material for the paper canvas and colorful feature stages.

**Observed:** Fine paper-like grain ties the neutral background to the softly blurred blue, peach, mauve and violet artwork. Colors blend across broad areas rather than forming sharp geometric shapes.

**Transfer:** Keep the page mostly warm neutral; concentrate stronger color in the rounded stages. The minimum version is a layered gradient with subtle monochrome grain.

**Build:** For paper, place a repeating SVG feTurbulence fractalNoise tile over #f5f4f1 at about 0.04 opacity. For a stage, start with #6c77b0, add a broad rgba(244,145,91,0.85) radial field near the right edge and rgba(57,92,195,0.8) near the left edge, blend through lilac, and overlay the same fine grain. Swap the base to #8f4d75 or #55269c for plum variants; keep transitions diffuse and text zones calm.

### Editorial pen marks

**Use:** Signature emphasis on a few headline words and beside staggered card corners.

**Observed:** Violet hand-drawn underlines, an imperfect oval around one word, a long curved arrow through an example, and small three-ray bursts add movement without becoming illustrations.

**Transfer:** Draw marks around important phrases and junctions in the new layout; they must follow the actual text rather than use fixed page coordinates.

**Build:** Use inline SVG paths with no fill, #5c6ae4 stroke, rounded caps and slightly imperfect curves. Give underlines a gently bowed baseline, loops unequal radii, and corner bursts three separated strokes of different lengths. Use roughly 3px–4px strokes for large headline marks and lighter strokes for corner rays; keep all marks behind or outside letterforms.

### Violet product halo

**Use:** Signature light behind the final broad product view.

**Observed:** A full-width dark-mode application window is surrounded by violet light that fades into the paper above. A small rounded gradient app icon overlaps the transition into the closing section.

**Transfer:** Finish product proof with a large complete view, using a darker product theme only when the product supports it. Use an original app symbol at the transition.

**Build:** Apply Product glow to a full-width band, place a 1280px-wide front-facing window above it, and center a 64px app symbol across the lower seam. Keep the upper half of the gradient nearly transparent and the deepest violet behind the media.

### Icons

**Observed:** Colorful illustrated circular avatars are the human motif, clustered in the navigation and product scenes. Small violet pen marks are decorative, not a generic outlined icon grid. Footer social marks are 16px.

**Transfer:** Choose original personable avatars and sparse single-purpose symbols; preserve their small size relative to the typography and interface.

## Section recipes

How recurring sections are built.

### First screen: Edited promise opening

**Observed:** Paper canvas continues behind Sticky navigation. Below the 48px navigation, the hero adds 128px of top space, then a violet Eyebrow, a centered two-line Display headline within 540px, and Live headline selection on part of its second line. A 32px gap leads to a 400px-wide Body-lead paragraph. After another 96px, Product window spans the 1280px container and a 714px foreground pane overlaps its center, slightly higher than the rear window. Within the first 900px, the entire text group and upper portion of both windows are visible; the windows continue well below the fold. There is no visible conversion button in this composition.

**Transfer:** Lead with a short product-category promise and a phrase that can be highlighted as if a teammate selected it. Rebuild the main object as one complete interface plus one meaningful detail pane. A focused secondary landing page can use a narrower workflow but should retain paper, bold stacked type, the live annotation and a substantial product object.

**Avoid:** Do not replace the layered software scene with a tiny centered icon, add a dense navigation menu, or turn the first screen into a full-bleed purple banner.

**Text style:** `display` — GT Walsheim 700 · 64px/1

### Centered demonstration rail

**Observed:** A centered 56px Heading introduces a narrow supporting paragraph. Below it, Example cards run horizontally with 32px spacing, showing several document variants and partial neighboring cards; a hand-drawn arrow passes through one example.

**Transfer:** Use this as breadth-of-use proof for new workflows or outputs, with varied content inside consistent frames.

**Text style:** `heading` — GT Walsheim 700 · 56px/1

### Annotated feature mosaic

**Observed:** Heading and Body-lead introduce the chapter with a 24px separation, followed by 80px before the Feature cards. One chapter is left-aligned; another is centered. Feature-mosaic uses 16px gutters and deliberate vertical offsets. White Card-heading and Body copy occupy upper stage areas while larger interface details sit below. Editorial pen marks decorate selected outside corners.

**Transfer:** Group a few related benefits into unequal stages with purposeful offsets; choose the chapter alignment to balance the following composition.

**Text style:** `heading` — GT Walsheim 700 · 56px/1

### Whole-product finale

**Observed:** A centered two-line Heading with hand-drawn underlines, a short support paragraph and Capability chips precede the large overview. Product glow gathers behind a 1280px-wide dark interface view, with a small app icon crossing its lower seam.

**Transfer:** Consolidate earlier capabilities into a complete product view, keeping chips descriptive and the luminous backing tied to media.

**Text style:** `heading` — GT Walsheim 700 · 56px/1

### Compact emotional close

**Observed:** Back on Paper canvas, a 96px top inset leads to a bold two-line 56px Heading. Two short centered Body-lead paragraphs sit below the title with a generous 48px title-to-copy separation. The closing text is narrow rather than a giant banner; no filled button is visible. After 120px of breathing space, the footer has a left sign-off and two utility links, right-aligned social marks, and 48px bottom space.

**Transfer:** End with a short emotional assertion followed by an invitation tied to the product's everyday value. Keep any necessary action restrained so the closing line remains the visual anchor.

**Text style:** `heading` — GT Walsheim 700 · 56px/1

## Page flow

**Storyline:** Category promise → layered product proof → breadth of outcomes → focused capability chapters → whole-product synthesis → emotional invitation → small utility footer.

### A product landing page that makes a familiar category feel newly collaborative and lively

1. **Promise** — Centered bold headline, collaborative selection detail and compact explanatory copy.
2. **Product demonstration** — A large context window with a focused workflow pane floating over it.
3. **Breadth of outcomes** — An edge-clipped rail of differently populated product documents.
4. **Capability chapters** — Short chapter introductions followed by staggered gradient-backed feature stages.
5. **Product synthesis** — Capability chips over a complete large product view with violet under-light.
6. **Closing invitation** — A two-line emotional closing headline, two brief paragraphs and a tiny utility footer.

**Transfer:** Use the same movement from simple promise to tangible detail to an emotional close; expand or shorten capability chapters according to the new product rather than treating their count or order as fixed.

## Writing

Warmly confident and conversational, with a little playful exaggeration. The language makes software feel alive while quickly naming what it does.

**Do not copy:** Do not reuse Ready's name, collaborator names, product-specific claims, branded phrasing, interface content or artwork. Source examples illustrate tone only; write substantiated claims for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your team'; use the product name as a noun and occasionally use 'let’s' to invite participation.
- **Rhythm:** Short stacked headlines, compact one-sentence introductions and two-sentence feature descriptions. Occasional contractions and light humor keep the technical explanations human.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name a familiar category and give it a friendly, slightly surprising human turn. | 6–10 words | “The calendar you need to meet” |
| Supporting line | Say what familiar thing becomes, who benefits, and why it matters. | 18–28 words | “[Brand] evolves your calendar into a living, breathing multiplayer workspace for teams to instantly make your meetings better.” |
| Chapter headline | Use a plain-spoken upgrade or outcome rather than a technical taxonomy. | 5–9 words | “Meetings just got an upgrade”<br>“Leave every meeting feeling [Brand]” |
| Feature title | Two-word capability label that stays concrete. | 1–3 words | “Automated Templates”<br>“Smart Tasks” |
| Feature description | Explain a simple action, then show the work the product takes away. | 20–35 words | “[Brand] connects your meetings together. Jump back in time to see what was discussed or leap forward to get a head start.” |
| Closing invitation | A short time-to-change assertion followed by an active invitation. | 2–5 words in the headline | “It's time. Get [Brand]” |

**Words and phrasing to use:** your team; together; in one place; effortless; instantly; make it better; living, breathing; power-up

**Avoid:** enterprise-grade synergy; revolutionary ecosystem; unparalleled solutions; formal corporate throat-clearing; long strings of technical acronyms

**Rules:**

- Pair playful headline language with concrete capability explanations.
- Use direct verbs and everyday benefits before implementation details.
- Keep a little personality in the closing invitation; do not make every sentence a joke.
- Use short factual labels for chips, not promotional mini-headlines.

## Do's and Don'ts

### Do

- Keep opening headlines at 64px/1 and chapters at 56px/1 with weight 700.
- Use the 1280px product container and much narrower 400px–640px text measures.
- Preserve the headline's translucent 25% violet selection and attached 4px caret.
- Give feature stages 32px corners and ordinary product windows 16px corners.
- Set feature copy 40px from the top and 48px from the sides where the card width permits.
- Use 16px mosaic gutters and 32px example-rail spacing.
- Keep fine paper grain visible in open neutral areas.
- Reserve the strongest whole-section violet light for the product overview.

### Don't

- Do not set main headings in the body grotesk; the rounded bold display face carries the personality.
- Do not tighten every heading with negative tracking; the main recipes use normal tracking.
- Do not turn 24px-radius capability chips into chunky filled CTA buttons.
- Do not flatten the staggered cards into an equal-height three-column grid.
- Do not put long paragraphs over the most luminous peach or violet parts of a stage.
- Do not add thick outlines around feature cards; the colored artwork and corners define them.
- Do not put heavy shadows on every surface; broad shadows belong to floating product windows and examples.
- Do not enlarge the tiny utility footer into a multi-column sitemap.

## Motion and responsive

### Motion

**Observed:**

- Utility links declare color 0.2s ease-out; two elements also declare opacity 0.2s transitions.
- The layout includes live-selection and drawn-mark animation structures, but no reliable full movement sequence is specified.

**Transfer:**

- Make the collaborative selection and drawn emphasis meaningful even at rest; movement must not be necessary to read the headline.

**Unknown:**

- The timing and sequence of the headline selection, SVG pen marks and horizontal example movement are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 479px, 767px, 768px, 991px, 992px, 1280px, 1440px and 1920px.

**Transfer:**

- On narrow screens, preserve the phrase-attached selection and caret while reducing headline size to fit.
- Collapse the staggered mosaic to a readable vertical sequence rather than retaining 80px and 192px desktop offsets.
- Keep the foreground product detail legible even if the broad context window must be clipped; retain the paper border around it.

**Unknown:**

- Mobile type sizes, navigation behavior and exact card stacking are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
