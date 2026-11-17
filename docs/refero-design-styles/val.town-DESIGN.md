# Val Town — a hand-drawn workshop

## Overview

A friendly developer-tool style that pairs real software with a lightly eccentric illustrated world. White space, black humanist sans typography, cyan actions and muted pastel line drawings make technical work feel approachable rather than corporate. Large floating interfaces and conversational testimonials give the spacious composition substance, while focused feature pages use more compact demonstrations and occasional black bands.

### Essentials

- The product lives in an illustrated world rather than a generic hero box: a floating 656×410px demonstration faces ink-outlined pastel objects above a left-aligned promise, inside a 1280px composition. Carry this illustrated setting into every new landing page; simple original SVG objects are the minimum fallback.
- Headlines sound and look like ordinary speech: Sprig Sans at 48px/1.2, weight 400, -0.025em tracking for the main promise; quotes use 32px/44px regular rather than bold display type.
- Conversion controls are compact rounded rectangles, not capsules: the main action is 48px high with 20px side padding and 12px corners; supporting choice chips are 32px high with 8px corners.
- The canvas stays overwhelmingly white: bright sky blue belongs to small action fills, dark blue to links, and dusty green, lilac and beige to ink illustrations. Black full-width bands are a focused-feature variant, not the default backdrop.
- Real interfaces float above the setting: the main 1280×640px product frame has 16px corners and a 0px 24px 64px -12px black shadow at 25% opacity; tiny centered progress marks sit beneath it.
- The page ends inside the same illustrated landscape, not at an unrelated conversion panel: oversized off-edge drawings and pale diagonal paths lead into a 1280px footer with a left identity-and-actions group and three link columns. Testimonials along the route remain unboxed, up to 672px wide.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky action | `#00bcff` | `--color-action` | action, background | Small primary action fills, kept subordinate to the white canvas. |
| Deep sky ink | `#082f49` | `--color-action-ink` | text | Text on the bright primary action. |
| Deep blue link | `#00598a` | `--color-link` | link, text | Underlined contextual links and setup guides. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Main page and floating panels; reverse text on black bands. |
| Cool mist | `#f8fafc` | `--color-soft` | surface, background | Secondary controls, technical panels and the center of faint section washes. |
| Warm porcelain | `#f8f4f2` | `--color-warm-panel` | surface | Warm backing of the large opening demonstration. |
| Cool edge | `#e2e8f0` | `--color-rule` | border | Fine panel outlines and navigation separators. |
| Black ink | `#000000` | `--color-ink` | text, background | Primary marketing text and illustrated outlines; black bands only on focused feature pages. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| focused feature pages | Deep blue action | `#0069a8` | `--color-dark-action` | action | White-label action on black bands. |
| focused feature pages | Live green | `#00c950` | `--color-green` | text, accent | A short outcome phrase in the feature headline. |
| product demonstrations | Terminal slate | `#1d293d` | `--color-terminal` | surface | Dark terminal backing. |
| product demonstrations | Slate detail | `#45556c` | `--color-slate` | surface, border | Terminal separators and chunky diagram objects. |
| capability illustrations | Clock face | `#0f172b` | `--color-clock` | surface | Dark digital clock backing. |

## Typography

- **Sprig Sans** — All marketing headings, prose, navigation, quotes and controls. Open, rounded humanist sans with a friendly single-storey feel; mostly regular, with bold reserved for controls and attribution. If unavailable, use **DM Sans**. Use 400 and 700; preserve the loose lowercase feel and measured headline tracking. Font stack: "Sprig Sans", "DM Sans", -apple-system, sans-serif.
- **iA Writer Mono** (only for technical demonstrations and cinematic feature captions) — Code, clocks and a large explanatory caption. Readable, uncompressed monospace with conspicuous punctuation. If unavailable, use **IBM Plex Mono**. Use 400 for code and 700 for the digital clock. Font stack: "iA Writer Mono", "IBM Plex Mono", Menlo, Consolas, ui-monospace, monospace.
- **system-ui** (only for embedded assistant demonstrations) — The assistant prompt headline, not the surrounding marketing text. Neutral operating-system interface sans. Font stack: "system-ui", -apple-system, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Sprig Sans | 400 | 48px | 1.2 | -0.025em | Default landing-page promise, normally two lines. |
| section-heading | Sprig Sans | 400 | 32px | 1.5 | normal | Simple headings introducing trust or the large product demonstration. |
| quote | Sprig Sans | 400 | 32px | 44px | normal | Unboxed testimonial statements. |
| footer-line | Sprig Sans | 400 | 20px | 1.4 | normal | Two-line conversational footer description. |
| lead | Sprig Sans | 400 | 18px | 1.6 | normal | Support below the main promise. |
| action | Sprig Sans | 700 | 16px | 1.5 | normal | Primary and secondary actions; capability-card titles. |
| small-action | Sprig Sans | 700 | 14px | 20px | normal | Navigation and compact option chips. |
| small | Sprig Sans | 400 | 14px | 20px | normal | Footer links and secondary setup links. |
| attribution-name | Sprig Sans | 700 | 14px | 1.25 | normal | Name next to a testimonial portrait. |
| attribution-detail | Sprig Sans | 400 | 14px | 1.25 | normal | Role and organization beneath the name. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| capability illustrations | clock-number | iA Writer Mono | 700 | 60px | 1 | normal | A large digital clock as a capability illustration, not a marketing statistic. |
| focused feature pages | feature-display | Sprig Sans | 400 | 48px | 1.25 | normal | Focused feature-page promise, with a short colored span. |
| focused feature pages | feature-heading | Sprig Sans | 400 | 36px | 40px | normal | Alternating feature chapters and closing black band. |
| cinematic feature demonstrations | cinematic-caption | iA Writer Mono | 400 | 36px | 1.25 | normal | Two-line explanatory statement over the large demonstration film. |
| embedded assistant demonstrations | assistant-prompt | system-ui | 400 | 30px | 1.2 | -0.025em | Centered question inside the warm assistant demonstration. |
| focused feature pages | body | Sprig Sans | 400 | 16px | 1.5 | normal | Feature descriptions and card support. |

**Notes:**

- Regular-weight headings carry the personality. Bold belongs to small controls, card titles and names, not the main promise.
- The default display tightens its tracking; feature-page displays and quotes keep normal tracking. Do not average the 57.6px and 60px headline line heights.
- Technical monospace is a scoped contrast, not the default body face.

## Layout

**Density:** Airy outside the interfaces, compact inside controls; the illustrated setting needs room around text and objects.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Major vertical padding and most layout gaps follow this rhythm.

| Value | Use |
| --- | --- |
| 8px | Navigation and choice-chip gaps. |
| 16px | Headline-to-support spacing and paired footer actions. |
| 20px | Footer link-column gaps and horizontal button padding. |
| 24px | Quote-to-attribution spacing. |
| 32px | Capability-card padding and grid gaps. |
| 48px | Desktop side padding and opening grid column gap. |
| 64px | Feature chapter grid gap and plain footer vertical padding. |
| 80px | Vertical padding around the large product demonstration. |
| 96px | Feature chapter vertical padding. |
| 128px | Feature opening padding and testimonial section breathing room. |
| 160px | Separation before the opening trust statement. |

### Containers and grids

- **landing container**: max width 1280px · side padding 48px. Centered default landing-page content; at 1440px this leaves 80px outer margins.
- **opening grid**: 2 columns · gap 48px. Asymmetric 7:4 composition: wide demo and promise on the left, illustrated world and conversion cluster on the right; the demo itself leaves 128px breathing room within its grid track.
- **testimonial measure**: max width 672px. Quotes alternate left and right within the wider landing container.
- **footer links**: 3 columns · gap 32px. Three narrow link columns on the right; 20px vertical link gaps.
- **feature container** (only for focused feature pages): max width 1152px · side padding 48px. Centered feature-page content, narrower than the illustrated landing composition.
- **feature pair** (only for focused feature pages): 2 columns · gap 64px. Vertically centered text and working demonstration; alternate 3:2 and 2:3 proportions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | main controls | 12px |
|  | compact controls | 8px |
|  | product stage | 16px |
|  | portrait | 50% |
| embedded assistant demonstrations | assistant input | 24px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | product stage | `0px 24px 64px -12px rgba(0,0,0,0.25)` | Large landing-page product window. |
|  | warm demo | `0px 0px 0px 1px rgba(0,0,0,0.1), 0px 28px 38px 0px rgba(0,0,0,0.12), 0px 10px 14px 0px rgba(0,0,0,0.1)` | Opening assistant demonstration. |
| focused feature pages | raised card | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Select capability cards and small product demonstrations. |

### Surfaces

#### White canvas · level 0

**Use:** The main continuous page backing.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Illustrations cross section boundaries without turning the canvas into a stack of colored cards.

**Transfer:** Keep the surrounding page white and let original line art provide continuity.

#### Warm demonstration · level 1

**Use:** Large opening product interaction.

**CSS:** `background: #f8f4f2; border-radius: 12px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.1), 0px 28px 38px 0px rgba(0,0,0,0.12), 0px 10px 14px 0px rgba(0,0,0,0.1)`

**Observed:** A warm panel floats over a pale diagonal route; its inner white interaction panel is more rounded.

**Transfer:** Show one plausible interaction rather than an entire application dashboard.

#### Product stage · level 1

**Use:** Wide, high-fidelity interface demonstration.

**CSS:** `background: #ffffff; border-radius: 16px; overflow: hidden; box-shadow: 0px 24px 64px -12px rgba(0,0,0,0.25)`

**Observed:** A broad landscape frame lifts above the illustrated ground.

**Transfer:** Preserve the landscape framing and clean edges with a real product view.

#### Mist band · level 0

**Only for:** focused feature pages

**Use:** Backing for capability clusters.

**CSS:** `background: linear-gradient(rgba(0,0,0,0) 0%, #f8fafc 50%, rgba(0,0,0,0) 100%)`

**Observed:** The wash is almost white and fades away rather than creating a hard section boundary.

**Transfer:** Use it to support white cards without adding another strong brand color.

#### Black band · level 0

**Only for:** focused feature pages

**Use:** A concentrated feature promise, film stage or closing call.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Clean black, without grain or atmospheric color glow.

**Transfer:** Reserve this contrast for focused technical storytelling.

#### Frosted caption · level 2

**Only for:** cinematic feature demonstrations

**Use:** Readable explanatory statement over a large product film.

**CSS:** `background: rgba(255,255,255,0.9); color: #000000; border-radius: 12px; padding: 32px; backdrop-filter: blur(24px)`

**Observed:** A wide pale caption lies across the lower area of a black-backed demonstration.

**Transfer:** Pair it with actual workflow footage; keep the text to two lines.

## Components

### Navigation bar

**Use:** Compact, full-width navigation above the illustrated page.

**CSS:** `display: flex; align-items: center; flex-wrap: wrap; column-gap: 8px; height: 64px; padding: 0px 8px 0px 16px; background: #ffffff; border-bottom: 1px solid #e2e8f0`

**Text style:** `small-action` — Sprig Sans 700 · 14px/20px

**Observed:** Small wordmark and primary links sit together on the left; login and a pale compact signup control sit at the far right. It is visually secondary to the scene.

### Primary button

**Use:** Default conversion action on white.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 20px; border: 1px solid transparent; border-radius: 12px; background: #00bcff; color: #082f49; column-gap: 8px`

**Text style:** `action` — Sprig Sans 700 · 16px/1.5

**Observed:** Text-only, content-sized rather than full width. Appears alone in the opening action cluster and beside a secondary action in the footer.

### Secondary button

**Use:** A companion setup or connection action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 20px; border: 1px solid #e2e8f0; border-radius: 12px; background: #f8fafc; color: #000000`

**Text style:** `action` — Sprig Sans 700 · 16px/1.5

**Observed:** Pale solid backing rather than an empty outline; equal height to the primary action.

### Compact choice

**Use:** Small integration choices and header signup.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 32px; padding: 0px 12px; border: 1px solid #e2e8f0; border-radius: 8px; background: #f8fafc; color: #000000`

**Text style:** `small-action` — Sprig Sans 700 · 14px/20px

**Observed:** Text labels wrap into a short chip row below a small explanatory label, with a setup link underneath.

**Transfer:** Use only for genuine ways to start or connect, not decorative category tags.

### Context link

**Use:** Secondary guides and inline elaboration.

**CSS:** `color: #00598a; text-decoration: underline; text-underline-offset: 2px`

**Text style:** `small` — Sprig Sans 400 · 14px/20px

**Observed:** A small underlined guide sits below option chips; the inline paragraph version inherits the lead recipe.

### Footer link

**Use:** Dense but calm utility navigation.

**CSS:** `color: #000000; display: block`

**Text style:** `small` — Sprig Sans 400 · 14px/20px

**Observed:** Plain text in three columns, without bold category headings; each column is a continuous list with 20px gaps.

### Testimonial figure

**Use:** Human proof dispersed through the illustrated world.

**CSS:** `max-width: 672px; color: #000000`

**Text style:** `quote` — Sprig Sans 400 · 32px/44px

**Observed:** Unboxed quote followed after 24px by a 48px circular portrait and a two-line attribution, with a 16px horizontal gap. Name is bold; role is regular.

**Transfer:** Use permissioned, specific observations and vary left/right alignment without centering the prose.

### Stage pagination

**Use:** Small progress controls below the main product view.

**CSS:** `padding: 8px; border-radius: 9999px`

**Observed:** Five tiny marks centered 16px beneath the stage; inactive marks are round and the active one extends horizontally. A black tooltip with a cyan halo calls out the current benefit inside the stage.

**Transfer:** Associate each mark with a real demonstration step, with an accessible descriptive label.

### Capability card

**Only for:** focused feature pages

**Use:** A large illustrated benefit in an asymmetric summary grid.

**CSS:** `padding: 32px; background: #ffffff; border-radius: 16px`

**Text style:** `body` — Sprig Sans 400 · 16px/1.5

**Observed:** A 240px-high card pairs a bold short title and one sentence with a large symbolic object. On a five-track grid, left cards span three tracks and right cards two. Selected cards use Raised card shadow; others remain flat.

### Technical detail card

**Only for:** focused feature pages

**Use:** A compact capability checklist.

**CSS:** `display: flex; flex-direction: column; row-gap: 8px; background: #ffffff; border: 1px solid #e2e8f0; border-radius: 12px`

**Text style:** `body` — Sprig Sans 400 · 16px/1.5

**Observed:** A 16px-padded inner group holds a white line icon on a black circle, a bold title and a short description. Six cards form a three-column grid with 32px gaps.

### Dark-band button

**Only for:** focused feature pages

**Use:** Primary action on the black opening or closing band.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 20px; border: 1px solid transparent; border-radius: 12px; background: #0069a8; color: #ffffff`

**Text style:** `action` — Sprig Sans 700 · 16px/1.5

**Observed:** The deep blue fill supports white type; it does not replace the bright sky action on white.

## Imagery and graphics

### Illustrated working world

**Use:** Signature background device across the opening, proof and ending of a new landing page.

**Observed:** Hand-drawn isometric storefronts, trees, lamps and small odd characters sit on pale diagonal streets. Black contours are slightly irregular, with sparse hatch shading, dusty green, lilac, beige and brown fills, and small soft ground shadows. Objects are isolated on white; the world extends beyond the viewport edges and leaves large open pockets for copy.

**Transfer:** Create an original miniature world related to the new product's work. Keep the dry ink, muted flat color and airy placement. The minimum version is several hand-outlined SVG objects, simple perspective faces and a continuous pale route; it must still frame the first screen and the ending.

**Build:** Use an oversized absolutely positioned SVG behind content, clipped at the page edges. Draw broad pale warm-gray diagonal polygons at about 27 degrees, crossing as a loose street network. Add black 2–3px irregular contour paths around skewed box forms, sparse 1px diagonal hatch marks, muted pastel faces and flattened gray ellipses beneath objects with a soft blur. Keep solid objects away from reading zones; let pale paths pass behind them.

### Floating product windows

**Use:** Functional proof, from the opening interaction to the large product stage.

**Observed:** The opening shows a warm assistant panel beside the drawn world. The later wide editor view includes a code workspace and rendered application, with a small black benefit tooltip. Feature pages use reduced browser, terminal and editor fragments with fine cool outlines, lightly tinted chrome and soft shadows.

**Transfer:** Use authentic product views with one legible task per fragment. For a non-software product, use a faithful step-by-step process diagram within the same window proportions rather than inventing interface controls.

### Capability objects

**Only for:** focused feature pages

**Use:** Large symbolic objects inside Capability card.

**Observed:** A chunky keyboard shortcut key, dark digital clock, rounded code capsule and crossed-out configuration symbol act as illustrations. They use cool slate neutrals and white, with 60px clock figures rather than decorative photography.

**Transfer:** Translate four benefits into immediately recognizable objects; keep one object per card and avoid a collection of tiny line icons.

**Build:** Construct a keyboard key as a light cool-gray rounded rectangle with a 2px darker edge and oversized dark shortcut glyph; a clock as an 8px-rounded dark rectangle with white 60px bold monospace digits; a code pill as a slate capsule with one short code line. Place each in a centered area about 128px high.

### Workflow film

**Only for:** cinematic feature demonstrations

**Use:** Immersive proof between the opening and capability chapters.

**Observed:** A real browser and editor are paired on a black field, followed by a wide pale frosted caption with a few cyan and magenta words. The interface occupies most of the central width, with strong black margins.

**Transfer:** Use a real before-and-after or paired workflow recording. Preserve the black stage and readable foreground caption, not continuous blur as a decorative effect.

### Icons

**Observed:** Social marks are solid black 24px symbols. Feature-card icons are white 2px round-stroked glyphs on black circular disks; small interface icons are 16px. The illustrated setting uses its own irregular pen line rather than the UI icon style.

**Transfer:** Keep utility icons monochrome and small. Use original drawn objects for personality rather than enlarging a stock icon set into the hero.

## Section recipes

How recurring sections are built.

### First screen: Illustrated interaction opening

**Observed:** A 64px Navigation bar precedes a white illustrated scene. In a centered 1280px field, a 656×410px Warm demonstration occupies the upper left while an ink-and-pastel cluster anchors the upper right. Pale diagonal paths sit behind both; the floating interaction sits above them. Below the demo, the regular 48px two-line promise and 18px support are left aligned, while Primary button, a small connection label, Compact choice row and Context link occupy the lower right. The first 900px contains the navigation, both large objects, promise, support and complete action cluster; the trust heading and logos begin below it.

**Transfer:** Make the first screen a working vignette beside original line art, then split promise and actions beneath them. If no interface exists, use one concrete product interaction or process card with the same warm backing. Focused feature pages instead open with a 1152px two-column promise-and-demo pair, 128px vertical padding and 64px gap; the code-intelligence variant uses black backing and a green headline phrase.

**Avoid:** Do not substitute a centered headline above a symmetrical row of cards, or put the whole illustrated scene inside a rounded container.

**Text style:** `display` — Sprig Sans 400 · 48px/1.2 · tracking -0.025em

### Wide working proof

**Observed:** A Section heading introduces Product stage with 16px separation. The landscape product frame is 1280×640px, with Stage pagination 16px beneath it and 80px section padding.

**Transfer:** Show the product doing one comprehensible job, then let the callout and progress controls explain the surrounding capabilities.

**Text style:** `section-heading` — Sprig Sans 400 · 32px/1.5

### Quotes along a route

**Observed:** Testimonial figure blocks alternate left and right across the 1280px canvas, leaving irregular vertical breathing room for the Illustrated working world. Quotes remain horizontal and black even where the diagonal pale paths cross underneath.

**Transfer:** Use a few substantial customer observations as stops along a visual route, not a rigid card grid.

**Text style:** `quote` — Sprig Sans 400 · 32px/44px

### Landscape footer

**Observed:** The Illustrated working world expands into oversized off-edge buildings and a broad diagonal path before resolving into a 1280px footer. The left group contains the wordmark, two-line 20px description, six 24px social icons and two 48px actions after a 48px gap. Three link columns occupy the right, with 32px horizontal and 20px vertical gaps; a tiny legal row follows below. Feature pages use the same footer content in a plain 509px-high white region with a top hairline and 64px vertical padding.

**Transfer:** Finish the visual story in the same world as the opening, then provide an orderly utility area. Use the plain bordered variant for focused feature pages.

**Text style:** `footer-line` — Sprig Sans 400 · 20px/1.4

### Alternating capability chapter

**Only for:** focused feature pages

**Observed:** Each chapter uses the Feature pair layout, 96px vertical padding, Feature heading and a 16px gap before Body. A 96×8px pale blue rounded rule precedes headings on the CLI and overview variants. The code-intelligence variant instead turns parts of the heading into selected text, caret or squiggle motifs matching the adjacent demonstration.

**Transfer:** Alternate concise benefit explanations with small working demonstrations; use one product-native editorial mark consistently rather than adding unrelated decoration.

**Text style:** `feature-heading` — Sprig Sans 400 · 36px/40px

### Capability summary

**Only for:** focused feature pages

**Observed:** Mist band backs a five-track grid with 32px gaps; four Capability card panels form two rows, with 3:2 width proportions. The keyboard, clock, code capsule and crossed-out configuration illustration alternate above and below their labels. A separate compact variant uses six Technical detail card panels in three columns.

**Transfer:** Give each benefit a distinct recognizable object and one short explanation. Preserve asymmetry rather than making every panel equal.

**Text style:** `body` — Sprig Sans 400 · 16px/1.5

### Concentrated closing call

**Only for:** focused feature pages

**Observed:** Black band uses 96px vertical and 48px side padding, with a 1152px inner width. A short white rounded 96×8px rule sits above a 36px regular closing line at left; Dark-band button aligns at right. Two variants add one short support line; the overview ends with only the headline and action.

**Transfer:** Restate the page's promised outcome briefly and offer one action; do not introduce a new feature list here.

**Text style:** `feature-heading` — Sprig Sans 400 · 36px/40px

## Page flow

**Storyline:** Working vignette and promise → credible product proof → capabilities or human proof → concise invitation → useful footer.

### Broad product landing page

1. **Promise** — Illustrated interaction opening splits the working object from the promise-and-action row.
2. **Social proof** — A conversational trust heading and a row of company marks.
3. **Product demonstration** — A wide live-product view with benefit tooltip and progress marks.
4. **Human proof** — Alternating unboxed quotes along the illustrated route.
5. **Closing invitation** — An expanded landscape leads into identity, actions and utility links.

**Transfer:** Use the scene to make the product approachable, then let real product detail and real people carry credibility.

### Single intelligent capability explained through small examples

1. **Promise** — Black opening with a green outcome phrase and an inline code demonstration.
2. **Capability chapters** — Four alternating text-and-demo pairs use product-native wordplay in headings.
3. **Capability summary** — Six compact icon cards followed by the four-object capability grid.
4. **Closing call** — Short black outcome band, then plain bordered footer.

**Transfer:** Make a complex capability tangible through small observable behaviors before summarizing breadth.

### Workflow and integration landing page

1. **Promise** — White split opening combines a benefit, terminal and familiar tool marks.
2. **Product demonstration** — Black cinematic workflow stage with a large frosted mono caption.
3. **Capability chapters** — Alternating application views, terminal fragments and a browser result.
4. **Capability summary** — Four asymmetric object cards.
5. **Closing call** — Black outcome band followed by the plain utility footer.

**Transfer:** Show continuity with the reader's existing tools, demonstrate the workflow, then explain the payoff.

### Broad capability overview

1. **Promise** — White split opening pairs a short promise with overlapping browser and code windows.
2. **Capability breadth** — A narrow black strip of colored monospace use cases.
3. **Capability chapters** — Alternating explanatory text and realistic code examples, with pale blue heading rules.
4. **Capability summary** — The four-object capability grid.
5. **Closing call** — A minimal black invitation and the plain footer.

**Transfer:** Organize breadth around concrete tasks and working outputs rather than a catalog of abstract feature names.

## Writing

Conversational, technically fluent and lightly mischievous. The language promises immediate utility through concrete actions, while occasional puns keep the tone human.

**Do not copy:** Do not reuse Val Town names, logos, town artwork, customer identities, quotations, deployment-time claims or compatibility claims. Replace them with original assets and truthful product-specific proof. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader as you or your. Name the product naturally in explanations; keep actions as short imperatives.
- **Rhythm:** Short, sentence-case headlines; one- or two-sentence support paragraphs; compact imperative buttons. Playful lines are punctuated by plain technical explanations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Main promise | Immediate practical outcome, addressed to the reader. | 6–10 words | “Instant deployments for you & your agents”<br>“Code locally, deploy instantly” |
| Supporting line | Explain what the reader can do, using recognizable tools or actions. | 10–25 words | “Use your favorite editor with the [Brand] CLI”<br>“Quickly spot typos and bugs with realtime code diagnostics” |
| Chapter heading | Mix literal task labels with occasional technically relevant wordplay. | 2–7 words | “You complete me”<br>“Hot reload in the browser”<br>“Import from npm” |
| Primary action | A short verb-led invitation, without marketing qualifiers. | 2–3 words | “Start building”<br>“Sign Up” |
| Footer description | A memorable two-line analogy that makes technical utility sound enjoyable. | 8–14 words | “If GitHub repos could run, And AWS Lambda were fun” |

**Words and phrasing to use:** instantly; your favorite; build; run; ship; live; one click; no waiting; zero config

**Avoid:** revolutionary ecosystem; unlock limitless potential; enterprise-grade synergy; the future of everything

**Rules:**

- Put the concrete task before the implementation detail.
- Keep technical terms when they make the behavior clearer; explain the payoff in ordinary speech.
- Use a pun only when the nearby demonstration makes it understandable.
- Let customer quotes contain specifics and enthusiasm; keep the surrounding marketing voice restrained.

## Do's and Don'ts

### Do

- Keep the main promise at 48px, weight 400, with -0.025em tracking.
- Pair the 656×410px opening interaction with original ink-outlined objects rather than a second interface.
- Keep default content within 1280px and feature explanations within 1152px.
- Use 48px-high primary controls and 32px-high compact choices.
- Leave quotes unboxed at 32px/44px, with 48px portrait attributions.
- Continue the pale diagonal route into the closing landscape.
- Keep raised product windows at 16px corners with broad downward shadows.
- Use 96px vertical padding for technical capability chapters.

### Don't

- Do not turn the white canvas into a full-page cyan or pastel background.
- Do not use 700-weight display headings just because the action labels are bold.
- Do not make the default action pill-shaped; its corners are 12px.
- Do not replace muted hand-drawn scenery with glossy 3D icons or photo collages.
- Do not use large monospace text for ordinary landing-page prose.
- Do not give every quote a border, fill and equal-height card shell.
- Do not use the 60px clock figures as a default marketing statistics style.
- Do not make the footer link columns into bold uppercase category panels; their 14px labels are plain and regular.

## Motion and responsive

### Motion

**Observed:**

- The product tooltip declares a 0.42s entrance with cubic-bezier(0.34,1.56,0.64,1) and a 2.4s ease-in-out infinite pulse.
- The main product demonstration has five progress controls; their inner marks declare a 300ms transition.

**Transfer:**

- Confine the buoyant entrance and pulse to a small in-product benefit callout; the surrounding illustrations should remain calm.
- Use the small progress marks to indicate actual product-demo changes.

**Unknown:**

- Automatic demo advancement timing and complete interaction states are not established.

### Responsive

**Observed:**

- The opening has a one-column base layout and an asymmetric desktop grid. Heading classes step through smaller sizes before 48px.
- Side padding has 24px and 48px variants. Footer links use two columns at the base and three at wider widths.
- Feature pairs become columns and capability grids reduce to a single column at narrow widths.

**Transfer:**

- On narrow layouts, stack the working vignette, promise and action cluster; simplify and clip the illustrated world to keep the text clear.
- Keep the original landscape feel through a few off-edge drawn objects rather than shrinking the entire town scene into an illegible thumbnail.

**Unknown:**

- Exact breakpoint widths and actual narrow-screen line breaks are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
