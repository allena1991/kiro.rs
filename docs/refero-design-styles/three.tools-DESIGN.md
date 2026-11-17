# three.tools — molten objects, developer candor

## Overview

A black-box product showcase with soft metallic lettering, dense bold system sans and a vivid molten-red object at its center. It suits creative software and technical tools that can balance a polished demonstration with a candid maker's voice. Most of the page is monochrome, with charcoal interface panels, restrained orange actions and occasional saturated color inside demonstrations. The composition alternates spacious theatrical stages with compact, practical feature cards.

### Essentials

- A sculptural object leads before the pitch: center a roughly 530px-wide red-orange, softly lit object above a 46px/1 bold two-line headline; add fine wireframe selection windows as a technical counterpoint.
- The hierarchy gets bigger after the opening: use 46px/1 with -0.5px tracking for the promise, then 68px/1 with -1px tracking for major capability and credibility headings; all text uses weight 700 system sans.
- Black is the stage, not a dark-blue dashboard: use #000000 canvas, #111111 bands and #1a1a1a cards with #343434 hairlines; reserve saturated color for the signature object, demonstrations and small orange conversion controls.
- Actions are small polished objects: the header uses a 116×31px pale pill with 99px radius; the form action is 140×44px, orange, with 16px corners and a translucent white top sheen.
- Feature explanations sit above cropped evidence: 398×525px cards form an 820px-wide two-column grid with 24px gaps, 20px corners, 32px caption padding and a bottom fade into black.
- Include both a human-made proof device and a low-key ending: a slightly rotated square media stack with a small creator identity strip, and rounded FAQ rows followed by a 52px charcoal footer. Adapt the proof to a real person or real work rather than adding corporate decoration.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hot orange | `#ff4300` | `--color-orange` | action, accent | Compact primary conversion buttons; do not extend into large section fills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White highlight | `#ffffff` | `--color-white` | text, surface | Headlines, emphasized card phrases and input surfaces. |
| Pale button | `#e9e6e6` | `--color-pearl` | action | Header action under its white-to-transparent sheen. |
| Soft white | `#cacaca` | `--color-text` | text | Supporting text; white at 0.792 opacity appears this color over black. |
| Silver | `#999999` | `--color-silver` | text | Conversion feature list and lower endpoint of the opening text gradient. |
| Caption gray | `#8d8d8d` | `--color-secondary` | text | Explanatory half of feature captions. |
| Letter gray | `#666666` | `--color-muted` | text | Low-contrast maker letter. |
| Toggle gray | `#393939` | `--color-control` | surface | FAQ plus-button backing. |
| Card edge | `#343434` | `--color-edge` | border, surface | Fine feature outlines and small carousel controls. |
| Footer charcoal | `#2b2a2a` | `--color-footer` | background | Thin closing footer strip. |
| Video hairline | `#262626` | `--color-video-edge` | border | White at 0.15 opacity over black for the large video frame. |
| Feature charcoal | `#1a1a1a` | `--color-card` | surface | Default feature-card backing. |
| Media charcoal | `#181818` | `--color-panel` | surface | Square media backing and visible FAQ fill; FAQ uses rgba(237,237,237,0.1) over black. |
| Deep charcoal | `#111111` | `--color-band` | background, surface | Full-width maker story and darker feature-card variant. |
| Absolute black | `#000000` | `--color-canvas` | background, text | Main canvas and text on pale controls. |

## Typography

- **-apple-system** — All marketing text, captions and controls. Native system sans with compact grotesk proportions, consistently bold rather than alternating regular body and heavy headings. Font stack: "-apple-system", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| chapter | -apple-system | 700 | 68px | 1 | -0.0147em | Major capability and maker-proof headings. |
| word-list | -apple-system | 700 | 48px | 1 | normal | Oversized technical nouns inside the typographic capability tile. |
| hero | -apple-system | 700 | 46px | 1 | -0.0109em | Centered opening promise and FAQ section title. |
| card-caption | -apple-system | 700 | 24px | 1.25 | normal | Feature title and explanation run together, separated by white versus gray. |
| letter | -apple-system | 700 | 22px | 1.25 | normal | Personal story paragraphs and conversion capability list. |
| question | -apple-system | 700 | 20px | 1.25 | normal | FAQ row labels. |
| support | -apple-system | 700 | 18px | 1.25 | normal | Two-line opening support copy. |
| quote | -apple-system | 700 | 16px | 1.25 | -0.0156em | Compact customer quotations. |
| brand-label | -apple-system | 700 | 16px | 1.25 | -0.011em | Compact header identity. |
| action | -apple-system | 700 | 14px | 1.25 | normal | Form actions, status line and creator name. |
| header-action | -apple-system | 700 | 12px | 1 | -0.008em | Small pale access button. |
| attribution | -apple-system | 700 | 10px | 1.25 | -0.025em | Subordinate quote attribution. |

**Notes:**

- Keep the unusually bold body copy: differences in brightness, size and proximity create hierarchy, not a switch to light weights.
- The opening headline is smaller than the capability heading. Use compact line breaks and a white-to-silver text fill where a metallic emphasis is wanted.
- Feature captions are a single thought: a white identifying phrase immediately followed by a gray benefit, not an eyebrow plus separate paragraph.

## Layout

**Density:** Airy at section scale, compact within captions and controls; long black intervals make the media feel exhibited rather than packed into a dashboard.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Header action text-to-icon gap. |
| 10px | FAQ row separation. |
| 20px | Header vertical padding and FAQ question vertical padding. |
| 22px | Maker paragraph separation. |
| 24px | Feature-grid gap and testimonial avatar-to-text gap. |
| 32px | Feature-caption inset. |
| 40px | Conversion columns gap and testimonial outer margins. |
| 48px | Testimonial group gap and media-block lead-in. |
| 56px | Maker story column gap. |
| 100px | Main chapter vertical padding and large heading separation. |
| 128px | Conversion block vertical breathing room. |
| 200px | Maker story band vertical padding. |

### Containers and grids

- **core column**: max width 820px · side padding 10px. Centered header, feature grid, principal video and closing footer alignment.
- **opening copy**: max width 603px. Centered promise and support below the sculpture.
- **feature grid**: max width 820px · 2 columns · gap 24px. Two equal 398px cards at desktop.
- **wide editorial**: max width 1107px · 2 columns · gap 56px · side padding 24px. Maker story: square media and heading on one side, letter on the other.
- **faq column**: max width 640px. Narrow centered questions beneath a left-aligned title in the core column.
- **testimonials**: 3 columns · gap 48px. Three compact unboxed quotations, each up to 380px wide, arranged across a wider row.

## Corner radius

| Element | Radius |
| --- | --- |
| feature and video frames | 20px |
| maker media | 24px |
| faq rows | 25px |
| faq toggle | 15px |
| form field | 22px |
| orange action | 16px |
| header action | 99px |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default page field.

**CSS:** `background: #000000; color: rgba(255, 255, 255, 0.792)`

#### Horizon glow · level 0

**Use:** Opening and conversion atmosphere.

**CSS:** `background-image: radial-gradient(300% 120% at 50% 100%, rgba(255, 255, 255, 0.25) 0px, rgba(0, 0, 0, 0) 50%)`

**Observed:** A broad neutral light rises from the lower center, leaving the upper object surrounded by near-black. The later conversion glow is a wider, lower-intensity variant.

**Transfer:** Use a broad gray horizon behind copy or a product object, never a colored aurora.

#### Feature shell · level 1

**Use:** Repeated capability panels.

**CSS:** `background: #1a1a1a; border: 1px solid #343434; border-radius: 20px; overflow: hidden`

**Observed:** Some panels use the darker band color. Media descends to the card edge beneath an inset caption and fades to black at the bottom.

**Transfer:** Preserve contrast between the shell, its hairline and dark product content.

#### Maker band · level 0

**Use:** Personal credibility interlude.

**CSS:** `background: #111111; padding: 200px 24px`

#### Metallic text

**Use:** Opening promise and FAQ title.

**CSS:** `background-image: linear-gradient(45deg, #ffffff, #999999); background-clip: text; -webkit-text-fill-color: transparent`

**Observed:** The maker heading uses a diagonal white-to-gray variant; the main capability heading stays white.

**Transfer:** Keep the gradient neutral and subtle enough that the text still reads as silver-white.

## Components

### Minimal header

**Use:** Identity and one conversion shortcut.

**CSS:** `display: flex; position: relative; padding: 20px 0; max-width: 820px; margin: 0 auto`

**Text style:** `brand-label` — -apple-system 700 · 16px/1.25 · tracking -0.011em

**Observed:** A small icon, bold name and tiny status capsule sit left; a flexible spacer pushes the pale access control to the right. There is no full navigation menu.

**Transfer:** Use a compact identity and one action instead of introducing several menu links.

### Header access button

**Use:** Secondary shortcut into conversion.

**CSS:** `background-color: #e9e6e6; background-image: linear-gradient(#ffffff, rgba(255, 255, 255, 0)); color: #000000; border-radius: 99px; padding: 8px 12px 8px 16px; height: 31px; gap: 8px`

**Text style:** `header-action` — -apple-system 700 · 12px/1 · tracking -0.008em

**Observed:** A tiny orange circular arrow finishes the label on the right.

**States:** Declared: hover background #c9c9c9; focus-visible not specified.

**Transfer:** Retain the small pearl-like treatment rather than promoting it to the dominant orange action.

### Notification button

**Use:** Primary form submission.

**CSS:** `background-color: #ff4300; background-image: linear-gradient(rgba(255, 255, 255, 0.23), rgba(255, 255, 255, 0) 99%); color: #ffffff; width: 140px; height: 44px; border-radius: 16px; padding: 1px 6px; display: flex; justify-content: center; align-items: center`

**Text style:** `action` — -apple-system 700 · 14px/1.25

**Observed:** The orange control is inset at the right end of a pale field, centered vertically with a small outer margin.

### Conversion field

**Use:** Email or access-interest form.

**CSS:** `background: #ffffff; height: 60px; max-width: 500px; border-radius: 22px; padding: 0 165px 0 25px`

**Observed:** One long pale field contains the Notification button. A compact status and sign-up explanation sits below the field; the same assembly returns in the conversion chapter.

**Transfer:** Reserve space for the inset action and put availability information below, not in the headline.

### Feature card

**Use:** One capability with visual proof.

**CSS:** `background: #1a1a1a; border: 1px solid #343434; border-radius: 20px; overflow: hidden; display: flex; flex-direction: column; position: relative`

**Text style:** `card-caption` — -apple-system 700 · 24px/1.25

**Observed:** An inset caption precedes edge-reaching product imagery; white names the capability and gray explains it. A transparent-to-black overlay darkens the lower media edge. Default desktop size is 398×525px; a text-only variant uses large fading technical words.

**Transfer:** Show a convincing cropped workflow per card rather than a generic icon.

### Main demo frame

**Use:** Broad product demonstration.

**CSS:** `border: 1px solid rgba(255, 255, 255, 0.15); border-radius: 20px; overflow: hidden; position: relative; margin-top: 48px`

**Observed:** An 820×615px frame holds a nearly 4:3 video with a tiny rounded progress line near its lower center.

**Transfer:** Use a recorded product workflow or a deliberate still frame; keep controls visually subordinate.

### Maker media stack

**Use:** Human authorship supported by actual work.

**CSS:** `background: #181818; border-radius: 24px; overflow: hidden; transform: rotate(-1deg)`

**Observed:** Square media around 532px sits above small identity and social links. Other media cards overlap behind it and are dimmed; a small index lives in the lower corner and two compact arrows sit below.

**Transfer:** Use real experiments, outputs or process clips from the maker, with a small count and identity strip.

### FAQ row

**Use:** Practical objections at the end.

**CSS:** `background: rgba(237, 237, 237, 0.1); border-radius: 25px; padding: 0 20px 0 25px; margin-bottom: 10px`

**Text style:** `question` — -apple-system 700 · 20px/1.25

**Observed:** A 640px-wide row is usually 74px high, growing for wrapped questions. An inner flex row has 20px vertical padding and places the question left and FAQ toggle right.

### FAQ toggle

**Use:** Compact expand control.

**CSS:** `background: #393939; width: 34px; height: 34px; border-radius: 15px; display: flex; justify-content: center; align-items: center`

**Observed:** A muted gray 24px plus, drawn with a 2px rounded stroke, sits inside the softened-square control.

### Technical word tile

**Use:** Breadth-of-capability proof without another interface image.

**CSS:** `border: 1px solid #343434; border-radius: 20px; overflow: hidden; padding: 0 32px; mask-image: linear-gradient(rgba(0, 0, 0, 0) 10%, rgb(0, 0, 0) 50%, rgba(0, 0, 0, 0) 90%)`

**Text style:** `word-list` — -apple-system 700 · 48px/1

**Observed:** A vertical list of oversized technical names fills one card. Individual words vary in opacity while the entire list fades away at top and bottom.

**Transfer:** Use the new product's real supported objects or formats, with enough terms to feel abundant.

### Footer strip

**Use:** Quiet final identity and legal closure.

**CSS:** `background: #2b2a2a; padding: 16px 0`

**Observed:** A 52px full-width strip uses an 820px inner alignment, with muted icon and name left and small copyright right. It is not a multi-column sitemap.

**Transfer:** End with a compact identity bar after the objection-handling space.

## Imagery and graphics

### Molten product sculpture

**Use:** Signature opening object and later conversion callback.

**Observed:** A three-armed inflated tubular emblem glows in coral, orange and deep red on black. Broad soft highlights and dark creases create volume without a ground plane. It fills roughly 530×480px above the headline. Several rectangular windows reveal a dark curved wire mesh, with thin white selection boxes and square corner handles.

**Transfer:** Create a similarly tactile object based on the new product's own concept. A minimum version is a layered SVG of rounded tubular segments with warm gradients and dark seam shading, plus a few mesh-selection windows; it must remain the opening's focal object.

**Build:** Use three thick, round-ended bent paths arranged radially around a central negative space in an approximately 540px square SVG. Shade each tube with coral-orange highlights, crimson midtones and deep red seams, using clipped blurred shadow paths for volume. Overlay three or four rectangular clips containing a dark field and thin gray curved grid lines; outline each clip in white with small square handles. Keep the background transparent over the Black stage; no outer neon glow.

### Dark interface closeups

**Use:** Feature cards and main demonstration.

**Observed:** Product imagery is dark-on-dark, framed by browser or tool chrome and cropped tightly enough that one workflow dominates. Orange selections and the warm sculpture carry color within otherwise charcoal panels. The lower imagery fades into black.

**Transfer:** Show the new product's real interface with one selected item or action, using a dark contextual frame rather than a floating generic dashboard.

### Maker experiment footage

**Use:** Credibility media beside a personal letter.

**Observed:** Square clips show playful 3D experiments, including a blue balloon-like figure against a dark grid with bright manipulation handles. Slightly rotated framing, overlapping cards and a tiny index make it feel like a working portfolio, not stock photography.

**Transfer:** Choose authored work or process footage with one vivid object on a dark background. If there is no motion asset, use a carefully composed still of an actual output.

### Neutral horizon light

**Use:** Atmosphere beneath hero and conversion content.

**Observed:** A wide, diffuse gray pool rises from the lower center of black, strongest near the bottom and weak behind the object.

**Transfer:** Carry this lighting into every new page as the foil to the warm object; keep it neutral.

**Build:** Apply the Horizon glow surface behind content across full width. Anchor the radial ellipse at 50% 100%, use white at 0.25 alpha at the origin and transparent black by 50%; let black dominate the upper half.

### Icons

**Observed:** Functional symbols are small and subdued: FAQ plus icons are 24px with 2px rounded strokes; carousel arrows are 12px with 2px rounded strokes; compact orange filled marks punctuate the capability list.

**Transfer:** Use simple rounded-stroke utility icons in gray, reserving filled orange for conversion-adjacent markers. Keep illustrative detail in the sculpture and demonstrations rather than the icon set.

## Section recipes

How recurring sections are built.

### First screen: Sculpture-first opening

**Observed:** The first 900px contains a 71px Minimal header, a large centered warm sculpture in the upper-middle stage, then a centered two-line promise at 46px/1 and a two-line 18px support statement. The object spans roughly a third of the page width and more than half the available stage height; the headline occupies about 600px beneath it. Layers run black canvas, neutral bottom glow, sculpture with wireframe selection windows, then silver headline and soft-white support. The main conversion field begins below the first fold, while the small Header access button is visible immediately. The hero as a whole continues beyond the viewport.

**Transfer:** Preserve the hierarchy of tiny header, large tactile object, compact promise and restrained support. For another product, build a simple original tubular or rounded sculpture with technical selection overlays. Other informational page types can shorten the stage but should retain the object-and-neutral-light visual language.

**Avoid:** Do not replace this with a conventional split hero, a large left-aligned text wall or a dashboard that crowds the sculpture.

**Text style:** `hero` — -apple-system 700 · 46px/1 · tracking -0.0109em

### Demonstration and peer proof

**Observed:** Main demo frame sits alone in the 820px core column with substantial black breathing room. A later row of three unboxed quotes uses 16px bold text, small avatars and 10px dimmed attributions, separated by 48px.

**Transfer:** Follow the promise with something observable, then compact peer testimony; adapt the number of quotes to available credible material.

**Text style:** `quote` — -apple-system 700 · 16px/1.25 · tracking -0.0156em

### Capability gallery

**Observed:** A centered two-line chapter heading at 68px precedes the Feature card grid. Six cards occupy two columns with 24px gutters. Captions combine white lead phrases with gray benefits, above large media; Technical word tile contributes a different kind of proof within the same shell.

**Transfer:** Group real capabilities into visual demonstrations and include a typographic breadth device rather than making every panel identical.

**Text style:** `chapter` — -apple-system 700 · 68px/1 · tracking -0.0147em

### Authored credibility band

**Observed:** Maker band widens the composition to 1107px. The left side holds a 68px two-line heading, Maker media stack and small identity; the right side is a dim 22px bold personal letter with 22px paragraph gaps. Desktop column gap is 56px.

**Transfer:** Explain why the product exists through a real maker, team or user's work. Keep the narrative intimate and the visual evidence specific.

**Text style:** `letter` — -apple-system 700 · 22px/1.25

### Conversion recap

**Observed:** A wide two-column block pairs a large product icon and status artwork with a 22px gray capability list, small orange markers and the repeated Conversion field. A low neutral horizon light grounds the section; columns are separated by 40px.

**Transfer:** Recap practical value before asking for access, pairing the signature object with a concise list of real outcomes.

**Text style:** `letter` — -apple-system 700 · 22px/1.25

### Questions and thin closure

**Observed:** A 46px metallic FAQ title leads to a narrower 640px stack of seven FAQ rows with 10px gaps and right-side plus controls. Substantial black space separates the final question from the Footer strip, which is only 52px high.

**Transfer:** End with practical buying or setup questions and a small identity bar, not an additional oversized sales slogan.

**Text style:** `hero` — -apple-system 700 · 46px/1 · tracking -0.0109em

## Page flow

**Storyline:** Sculptural promise → observable workflow → peer confidence → capability gallery → authored credibility → conversion recap → practical objections → restrained closure.

### A creative technical product landing page that makes a developer tool feel tangible and personal

1. **Promise** — Object-first stage, compact centered benefit and support, then an access form.
2. **Product demonstration** — An isolated large video in a hairline rounded frame.
3. **Social proof** — A short horizontal row of compact peer quotations.
4. **Capability chapters** — Monumental benefit heading and a paired gallery of captioned interface closeups, including a fading word tile.
5. **Credibility** — A full-width charcoal maker letter paired with a stack of authored media.
6. **Conversion** — Warm product artwork, practical capability list and repeated access form.
7. **Objection handling** — Narrow rounded FAQ rows with small plus controls.
8. **Closure** — Black breathing room and a thin gray identity-and-copyright strip.

**Transfer:** Use these narrative functions as adaptable building blocks, keeping tangible product proof and a personal credibility moment even when the number and order of chapters change.

## Writing

Confident about concrete usefulness, informal about the person building it. Polished benefit statements coexist with a conversational, slightly rough-edged maker letter rather than enterprise jargon.

**Do not copy:** Do not reuse ThreeTools or three.tools identities, the tubular emblem, creator names, project names, customer quotations, availability status or compatibility and performance claims. Write truthful equivalents for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use direct imperatives and 'you' for capabilities; let a real maker speak as 'I' in the credibility passage. Product support copy names what the tool does plainly.
- **Rhythm:** Headlines are compact benefit statements, often split into two balanced lines. Card captions are short capability-plus-benefit pairs; the maker letter uses several short paragraphs with natural conversational joins.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A clear product category plus an appealing quality and broad practical applicability. | About 10 words | “A beautiful Three.js editor that works on every project*.” |
| Support | Two concrete sentences: what you do, then how the product is delivered. | Two short sentences | “Inspect and tweak any Three.js website. ThreeTools works as a browser extension.” |
| Chapter headline | Two parallel outcome phrases with active verbs. | Four to six words | “Work Smarter, Move Faster.” |
| Feature caption | Name the capability, then explain the immediate benefit. | Two compact phrases | “Inspect scenes.”<br>“Get visibility into your graph.” |
| Maker introduction | A simple greeting and an unpretentious personal motivation. | A brief greeting followed by short paragraphs | “Hey there,” |
| Action | A short invitation naming the next step, not an inflated outcome. | Two words | “Get access”<br>“Get Notified” |

**Words and phrasing to use:** inspect; tweak; adjust; live project; works; fun stuff; get access

**Avoid:** revolutionary ecosystem; unlock infinite possibilities; enterprise-grade synergy; effortless transformation

**Rules:**

- Tie every feature to an observable action or outcome.
- Give personal credibility its own voice rather than making every section sound like a founder letter.
- Keep setup and payment questions straightforward and literal.
- Use periods in benefit statements and let typography supply emphasis.

## Do's and Don'ts

### Do

- Keep the opening promise at 46px and capability headings at 68px on the desktop composition.
- Use weight 700 even for the 18px support and 22px narrative copy.
- Keep the main capability gallery at 820px with 24px gutters.
- Inset card captions by 32px and let imagery reach the lower edges.
- Use 1px #343434 outlines to separate charcoal cards from black.
- Repeat the 60px-high pale field with its 44px orange inset action at conversion moments.
- Give the human credibility band 200px vertical padding and a wider two-column composition.
- Keep FAQ rows narrowly centered and the footer to a 52px strip.

### Don't

- Do not tint the page navy or purple; this is true black with neutral charcoal elevation.
- Do not use orange as a full-section background; its marketing role is concentrated in small actions and the sculptural object.
- Do not switch body paragraphs to a thin or regular weight to make them look more conventional.
- Do not apply drop shadows to every card; separation comes from fine outlines and fill differences.
- Do not turn the 31px header shortcut into a large primary hero button.
- Do not insert uppercase tracked eyebrow labels above every heading; the bold benefit itself carries the hierarchy.
- Do not replace the fading technical-word tile with another generic illustrated icon card.
- Do not expand the thin ending into a large sitemap or social-link wall.

## Motion and responsive

### Motion

**Observed:**

- Header action declares a background transition of 0.1s linear and a gray hover fill.
- Small social links declare opacity 0.5 on hover with 0.1s ease-in transitions; carousel controls declare a background-color transition of 0.1s ease-in.
- Notification controls declare a 0.4s width transition using a detailed linear easing function.

**Transfer:**

- Keep utility hover changes brief and modest; reserve expressive behavior for the sculptural or product media rather than moving ordinary text blocks.

**Unknown:**

- The full notification width easing, trigger sequence, video playback behavior and scroll animation timing are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 370px, 440px and 860px.
- Core sections are constrained to the available width with narrow side margins.

**Transfer:**

- On narrow screens, stack paired feature cards and the maker story while preserving the sculpture-first hierarchy and the small header action.
- Keep the inset conversion action readable by allowing the form to use the available width rather than retaining its desktop fixed width.

**Unknown:**

- Exact mobile type sizes, column changes and artwork behavior at each breakpoint are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
