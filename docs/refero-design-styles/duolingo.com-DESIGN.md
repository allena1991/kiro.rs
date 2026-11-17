# Duolingo — buoyant bite-sized delight

## Overview

An exuberant, approachable style that makes useful products feel like play rather than work. Mostly white space, leaf green and friendly gray rounded sans-serif lettering surround colorful character illustrations and simplified devices. The density is low and the mood optimistic, with occasional sky-blue expanses and a theatrical dark premium interlude. It suits consumer apps, habit-building services and products that need to make a complex activity feel welcoming.

### Essentials

- A modest promise beside an exuberant object: the default opening pairs a 424px illustration with a centered 32px bold headline, inside a 988px composition with an 80px gap; two 330px-wide actions do the conversion work.
- Headings smile rather than shout: rounded feather lettering at 48px/normal and weight 700, generally lowercase and leaf green; the larger 64px/normal moments tighten tracking to -0.02em.
- Buttons feel like toy keys: 50px height, 12px corners, uppercase 15px bold labels with 0.8px tracking, and a distinct 4px bottom edge rather than a floating blur shadow.
- White is the default stage, green is the punctuation and finale: most explanatory chapters stay white with gray body copy, while a full-width green illustrated landscape leads into a matching green footer.
- Illustration carries the personality: saturated, rounded vector characters, tilted devices and collectible-like symbols fill 424–530px stages beside short text. Every new landing page needs an equally playful illustrated object system; simple rounded geometric helpers and product-specific symbols are the minimum equivalent.
- The final invitation becomes scenery: a centered 64px rounded headline and one action sit above a full-width bowl-shaped white valley cut into green, with a central device and orbiting reward objects. The landscape continues seamlessly into the footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Leaf green | `#58cc02` | `--color-green` | text, background, action, accent | Rounded section headings, primary actions, closing landscape and expansive footer. |
| Light leaf | `#a5ed6e` | `--color-footer-link` | text, border | Footer links and the divider above the language directory. |
| Pale leaf | `#d7ffb8` | `--color-footer-heading` | text | Footer column headings and language-directory label. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Helpful blue | `#1cb0f6` | `--color-link` | link, text | Inline proof links and secondary-action labels. |
| Deep blue lettering | `#042c60` | `--color-sky-ink` | text | Large heading over the sky illustration chapter. |
| Air blue | `#ddf4ff` | `--color-sky` | background | Immersive device-and-symbol illustration chapter. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Friendly charcoal | `#4b4b4b` | `--color-ink` | text | Opening headline and dark headings. |
| Support gray | `#777777` | `--color-body` | text | Explanatory body copy and category labels. |
| Utility gray | `#afafaf` | `--color-muted` | text | Language controls, utility links and compact uppercase labels. |
| Soft edge | `#e5e5e5` | `--color-rule` | border, surface | Two-pixel dividers, secondary-action rims and FAQ rules. |
| Faint header edge | `#f1f1f1` | `--color-header-edge` | border | Visible result of a 53% soft-gray rule over white. |
| White stage | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, secondary actions and reversed labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| single-subject product landings | Subject mint | `#00cd9c` | `--color-mint` | action, text, accent | Subject-specific action labels and mint action system. |
| premium promotion chapters | Premium action ink | `#000437` | `--color-deep-ink` | text | Dark label on the white premium trial action. |
| premium promotion chapters | Midnight violet | `#100f3e` | `--color-premium` | background | Full-bleed premium presentation backdrop. |
| single-subject product landings | Pale mint stage | `#e6faf5` | `--color-mint-wash` | background | Visible 10% mint over white, used behind opening and closing illustrations. |
| research and results pages | Proof text | `#3c3c3c` | `--color-proof-ink` | text | Compact result-list text. |

## Typography

- **duolingo-sans** — Body copy, opening headline, controls and utility navigation. A rounded humanist sans with open counters, soft terminals and a sturdy bold cut. If unavailable, use **Nunito Sans**. Use 400 and 700; retain open spacing and rounded, friendly proportions. Font stack: "duolingo-sans", "Nunito Sans", sans-serif.
- **feather** — Large brand statements and rounded lowercase chapter headings. Plump, soft-edged display sans with single-storey forms and conspicuously rounded joins. If unavailable, use **Nunito**. Use 800 to approximate the heavier rounded silhouette while preserving the specified sizes. Font stack: "feather", "Nunito", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | feather | 700 | 64px | 80px | -0.02em | Centered immersive-stage and closing statements. |
| chapter-heading | feather | 700 | 48px | 60px | normal | Lowercase benefit statements and related-product chapter titles. |
| opening-heading | duolingo-sans | 700 | 32px | 44px | normal | Default marketing opening, centered beside the main illustration. |
| footer-heading | duolingo-sans | 700 | 19px | 1.4 | normal | Headings in the expansive green footer. |
| body | duolingo-sans | 400 | 17px | 24px | normal | Default support paragraphs, usually limited to a short block. |
| inline-link | duolingo-sans | 700 | 17px | 24px | normal | Blue emphasis within support copy. |
| action | duolingo-sans | 700 | 15px | 21px | 0.053em, uppercase | Default primary and secondary actions. |
| footer-link | duolingo-sans | 700 | 15px | 22px | normal | Footer navigation and language-directory label. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| research and results pages | research-heading | feather | 700 | 48px | 1.1 | normal | Centered headings over charts and customer stories. |
| single-subject product landings | subject-heading | duolingo-sans | 700 | 40px | 1.1 | normal | Left-aligned opening and final invitation. |
| single-subject product landings | feature-heading | duolingo-sans | 700 | 28px | 32px | normal | Centered headings opposite tall device demonstrations. |
| research and single-subject pages | body-large | duolingo-sans | 400 | 20px | 1.4 | normal | Introductory and feature support lines. |
| research and results pages | story-caption | duolingo-sans | 700 | 20px | 1.4 | normal | Outcome sentence beside a customer video. |
| single-subject product landings | faq-question | duolingo-sans | 700 | 20px | 1.2 | normal | Question labels in disclosure rows. |
| research and results pages | proof-body | duolingo-sans | 400 | 17px | 20px | normal | Compact check-mark result list. |
| single-subject product landings | eyebrow | duolingo-sans | 700 | 16px | 1 | 0.04em, uppercase | Muted compact category above a feature heading. |
| single-subject product landings | subject-action | duolingo-sans | 700 | 16px | 44px | 0.04em, uppercase | Solid mint actions. |
| research and single-subject pages | compact-footer | duolingo-sans | 700 | 15px | 1 | 0.053em, uppercase | Small centered footer link row. |

**Notes:**

- Default openings are deliberately smaller than later chapter headings: 32px sans first, 48px rounded display for benefits, 64px for immersive and closing moments.
- Only the 64px display uses negative tracking. Keep body text at normal tracking; uppercase controls use positive tracking.
- Normal line height is retained where used by the fonts rather than replaced by a fabricated ratio. Most headings are bold, not light or condensed.
- The premium promotional lettering is illustrated italic display artwork, not the ordinary heading font.

## Layout

**Density:** Airy: short text blocks occupy only part of each tall illustration chapter, with substantial uninterrupted white space.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight stacked-action separation in the subject variant. |
| 10px | Footer link-list gap and small icon-to-label gaps. |
| 12px | Default stacked-action separation; eyebrow-to-heading gap in the subject variant. |
| 16px | Subject heading-to-copy gap and small control padding. |
| 24px | Default heading-to-copy gap, footer-column gap and badge separation. |
| 32px | FAQ section stack gap. |
| 40px | Opening headline-to-actions offset and story media-to-caption gap. |
| 48px | Large centered headline-to-action-group gap. |
| 80px | Opening art-to-copy separation. |
| 96px | Major chapter-group vertical padding and footer top padding. |
| 101px | Alternating benefit art-to-copy separation. |

### Containers and grids

- **marketing-container**: max width 988px. Centered desktop anchor shared by header, text chapters and footer; illustrations can deliberately overhang it.
- **opening-pair**: max width 988px · 2 columns · gap 80px. 424px art stage at left and a 480px centered text column at right; actions narrow to 330px.
- **benefit-pair**: 2 columns · gap 101px. 473px support column paired with a 530px illustration stage; reverse direction on alternating chapters.
- **footer-grid**: max width 988px · 5 columns · gap 24px. Five 178px columns, with some columns containing a second link group.
- **research-container** (only for research and results pages): max width 1048px · side padding 30px. Padded outer container yielding a 988px content stage.
- **subject-features** (only for single-subject product landings): max width 910px · 2 columns. 295px-wide tall device beside a centered 442px text column; alternate the side of the device.
- **faq-column** (only for single-subject product landings): max width 643px · gap 32px. Narrow centered disclosure stack below the feature chapters.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 12px |
| single-subject product landings | subject-actions | 16px |

## Surfaces and depth

### Surfaces

#### White stage · level 0

**Use:** Default marketing page and benefit chapters.

**CSS:** `background: #ffffff`

**Observed:** Open canvas rather than a dashboard of cards; graphic objects float directly on white.

**Transfer:** Separate subjects through spacing and illustration, not enclosing panels.

#### Sky stage · level 0

**Use:** Immersive device chapter.

**CSS:** `background: #ddf4ff; overflow: hidden`

**Observed:** Pale blue reaches both viewport edges and backs a much wider field of floating objects.

**Transfer:** Reserve a broad pale-color stage for a major experiential statement.

#### Green finale · level 0

**Use:** Closing landscape and expansive footer.

**CSS:** `background: #58cc02`

**Observed:** A white curving valley interrupts the upper edge, while the lower green plane continues into footer navigation.

**Transfer:** Make the illustration and footer one continuous color environment.

#### Premium stage · level 0

**Only for:** premium promotion chapters

**Use:** High-contrast upgrade interlude.

**CSS:** `background: #100f3e`

**Observed:** Flat midnight backdrop, bright multicolor graphic, white orbit shape and a small white action; not a gradient page background.

**Transfer:** Use a single theatrical chapter to distinguish an upgrade from the core offering.

#### Mint stage · level 0

**Only for:** single-subject product landings

**Use:** Subject opening and closing bands.

**CSS:** `background: rgba(0, 205, 156, 0.1); overflow: hidden`

**Observed:** Very pale mint behind an illustration that rests on the bottom edge.

**Transfer:** Use the subject accent as a low-opacity wash while keeping the explanatory chapters white.

## Components

### Fixed navigation

**Use:** Persistent brand anchor and conversion access.

**CSS:** `height: 72px; position: fixed; z-index: 2; background: #ffffff; border-bottom: 2px solid rgba(229, 229, 229, 0.53)`

**Observed:** Centered inner navigation aligns with the marketing container. The opening shows a wordmark at left and language selector at right; the scrolled presentation uses a compact green action at right. Research navigation instead includes uppercase topic tabs.

**Transfer:** Keep the header sparse, using only one right-hand utility or conversion group.

### Primary button

**Use:** Main conversion action.

**CSS:** `height: 50px; width: 330px; padding: 0px 16px; border-radius: 12px; background: #58cc02; color: #ffffff; border-bottom: 4px solid rgba(0, 0, 0, 0.15); display: flex; align-items: center; justify-content: center`

**Text style:** `action` — duolingo-sans 700 · 15px/21px · tracking 0.053em · uppercase

**Observed:** A solid, toy-key face with a darker lower lip. In the premium chapter the face is white and the label is deep blue; that action is narrower.

**Transfer:** Use a short verb-led invitation and preserve the physical lower edge.

### Secondary button

**Use:** Returning-user and lower-priority actions.

**CSS:** `height: 50px; width: 330px; padding: 0px 16px; border-radius: 12px; background: #ffffff; color: #1cb0f6; border: 2px solid #e5e5e5; border-bottom-width: 4px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — duolingo-sans 700 · 15px/21px · tracking 0.053em · uppercase

**Observed:** Same footprint as the primary action, stacked below it with a 12px gap; the face stays white.

### Inline proof link

**Use:** Credible, low-friction route from a benefit paragraph to supporting material.

**CSS:** `color: #1cb0f6; text-decoration: none`

**Text style:** `inline-link` — duolingo-sans 700 · 17px/24px

**Observed:** Bold blue words live within gray prose rather than becoming a separate pill.

### Category rail

**Use:** Horizontal range-of-offering navigation under the opening.

**CSS:** `height: 80px; padding: 0px 40px; border-top: 2px solid #e5e5e5; border-bottom: 2px solid #e5e5e5; display: flex; align-items: center; justify-content: center`

**Observed:** One row of uppercase gray labels paired with colorful 36px by 28px category emblems; small chevrons sit at the outer edges. The centered inner rail is 1090px wide.

**Transfer:** Use product families or use cases, not generic social-proof logos.

### Green footer columns

**Use:** Full site directory after the illustrated close.

**CSS:** `background: #58cc02; display: grid; grid-template-columns: repeat(5, 178px); gap: 24px; max-width: 988px; padding: 96px 0px 64px`

**Text style:** `footer-link` — duolingo-sans 700 · 15px/22px

**Observed:** Pale-leaf headings use the footer-heading recipe above lighter-leaf links. Links form unbulleted vertical lists with 10px gaps. A full-width pale-green rule divides these columns from a wrapping language directory below.

**Transfer:** Group navigation by intent and retain the unusually bright, low-contrast tonal footer treatment.

### Download badge pair

**Use:** Platform-specific acquisition in the immersive chapter.

**CSS:** `display: flex; justify-content: center; gap: 24px`

**Observed:** Two white toy-key badges sit side by side. Each has 12px corners, a 63px height, 9.5px by 14px padding, a 34px charcoal platform symbol and two-line left-aligned label. Introductory text is 14px/17px bold; destination is 17px/20px bold.

**Transfer:** Use a pair only when there are genuinely different destinations; maintain the compact two-line hierarchy.

### Compact footer

**Only for:** research and single-subject pages

**Use:** Restrained ending for focused information and product pages.

**CSS:** `border-top: 2px solid #e5e5e5; padding: 30px 25px; background: #ffffff`

**Text style:** `compact-footer` — duolingo-sans 700 · 15px/1 · tracking 0.053em · uppercase

**Observed:** Centered wrapping row of eight utility links rather than the green directory. Each link has 12px margins and 0.8 opacity; there is no added conversion panel on the research variant.

### Result checklist

**Only for:** research and results pages

**Use:** Compact quantified proof near the opening.

**CSS:** `padding-left: 44px; background-size: 32px 32px; background-position: 0px 0px; color: #3c3c3c`

**Text style:** `proof-body` — duolingo-sans 400 · 17px/20px

**Observed:** Three short result statements, each preceded by a green circular check. Important phrases are bold blue inline links; the proof is verbal rather than giant standalone numerals.

**Transfer:** Use real, attributable outcomes and turn the meaningful result phrase into the link.

### FAQ row

**Only for:** single-subject product landings

**Use:** Objection handling after demonstrations.

**CSS:** `max-width: 643px; display: flex; justify-content: space-between; align-items: flex-start; gap: 16px; padding-bottom: 32px; border-bottom: 2px solid #e5e5e5`

**Text style:** `faq-question` — duolingo-sans 700 · 20px/1.2

**Observed:** Bold sentence-case question at left, 24px downward chevron at right. Closed rows form a plain ruled list, not separate cards.

**Transfer:** Keep a single focused question per row.

### Subject primary button

**Only for:** single-subject product landings

**Use:** Subject-specific conversion action in opening and close.

**CSS:** `height: 48px; width: 300px; padding: 0px 12px; border-radius: 16px; background: #00cd9c; color: #ffffff; border-bottom: 4px solid rgba(0, 0, 0, 0.15); text-align: center`

**Text style:** `subject-action` — duolingo-sans 700 · 16px/44px · tracking 0.04em · uppercase

**Observed:** The mint variant uses a slightly rounder silhouette. Repeated chapter actions use a white outlined face with mint text instead of a solid face.

## Imagery and graphics

### Buoyant vector scenes

**Use:** Opening and alternating benefit chapters; essential expressive layer.

**Observed:** Rounded human and animal helpers, tilted phones, coins and game-like symbols are assembled in airborne clusters. Rich green is joined by yellow, cyan, pink and purple. Flat fills and a few darker side faces imply depth without realistic lighting; there are no enclosing image cards. The opening art occupies a 424px square; chapter stages expand to 530px.

**Transfer:** Create original rounded helpers and tangible symbols of the new product's outcomes. Minimum equivalent: a simplified device with one expressive geometric helper and three to five colorful outcome tokens.

**Build:** Use SVG groups with rounded silhouettes and flat fills. Put a tilted rounded-rectangle device near the lower center, scale the main helper larger than the surrounding tokens, and rotate smaller token groups in different directions. Give tokens a darker offset side face rather than blurred shadows; leave transparent space around the whole cluster.

### Floating device field

**Use:** Immersive acquisition chapter.

**Observed:** Phones and beveled icon tiles float at opposing angles across a pale sky stage. Artwork extends beyond both viewport edges; central headline and badges remain unobstructed above the busy lower field. The source artwork spans 2000px by 1122px.

**Transfer:** Use the new interface on three or four simplified devices and float product-specific outcome symbols around it.

**Build:** Create an oversized SVG stage centered behind the content, clipped by the full-width section. Layer dark rounded device frames with pale-blue screens, rotate each roughly 15–30 degrees in opposing directions, and scatter small colored beveled squares between them. Keep the central upper text region empty.

### Landscape invitation

**Use:** Signature illustrated conversion close.

**Observed:** A central tilted phone rises inside a broad white valley, surrounded by oversized coins and celebratory symbols; green hills rise at the left and right edges. A centered headline and action sit above the object field. The artwork spans the viewport and joins the green footer without a seam.

**Transfer:** Turn the new product's completed task into a central object surrounded by a handful of tangible success symbols; keep the green landscape even when no character art is available.

**Build:** Draw a full-width green SVG base and a white top path with rounded cubic curves descending into a deep central bowl. Position a simple outlined device at the bowl center, layer five to eight rounded token symbols around it, and use flat darker offset shapes for contact shadows. Keep the top third clear for text and action.

### Premium spectrum emblem

**Only for:** premium promotion chapters

**Use:** Theatrical upgrade illustration and title lockup.

**Observed:** A neon green-to-cyan-to-purple emblem with a thick white contour floats over a broad white looping orbit on midnight violet. Small starbursts and a tiny tilted device complete the left cluster; italic multicolor title artwork and a small white action sit to the right.

**Transfer:** Use a product-specific emblem with a spectrum fill and a separate concise upgrade title. Keep the illustrated lettering treatment isolated from normal typography.

**Build:** Make a soft irregular SVG silhouette, fill with a green/cyan/violet gradient, and add a thick white stroke. Behind it, draw a broad white crescent or loop; add three four-point white sparkles and one miniature tilted device. Match the luminous color transitions without adding a hazy page-wide glow.

### Measured chart and human stories

**Only for:** research and results pages

**Use:** Quantified and qualitative proof.

**Observed:** A centered 533px by 389px chart image has a thin light-gray rounded frame, simple blue/green paired bars and small error marks. Below, real customer video thumbnails sit left of bold gray outcome captions; the lead video is larger than subsequent entries. Horizontal rules separate the stories.

**Transfer:** Use an honest, legible chart with only a few series, followed by real people in their own environments. Retain the simple framed chart and unboxed video-caption rows.

### Tall device demonstrations

**Only for:** single-subject product landings

**Use:** Repeated feature chapters.

**Observed:** 295px-wide, roughly 611px-tall straight-on devices have thick charcoal rounded frames and white screens. Visible interface or character scenes stay inside the device; adjacent text is centered. The opening and closing art instead uses a low-perspective tiled plane and oversized subject objects.

**Transfer:** Show one understandable task per device. For the opening and close, use an oversized product-specific object resting on a pale subject-colored floor.

### Icons

**Observed:** Utility chevrons are small gray marks; rail emblems are colorful rounded 36px by 28px illustrations. Platform icons are solid charcoal at 34px, and FAQ chevrons use 24px image boxes. Small inline arrow strokes use 2px rounded strokes.

**Transfer:** Use rounded, simple utility geometry and expressive colored category emblems; do not replace all illustrative symbols with thin technical line icons.

## Section recipes

How recurring sections are built.

### First screen: Illustrated promise opening

**Observed:** A white first screen has a sparse fixed navigation bar above a vertically centered two-column composition. A 424px illustration occupies the left; the right holds a centered 32px bold charcoal headline across a 480px text column. The 988px composition separates art and text by 80px. Two 330px-wide Primary button and Secondary button controls sit 40px below the heading with a 12px gap. Back to front: white canvas, transparent illustration, text and actions, then the navigation layer. Within the first 900px, the complete headline, art, both actions and the 80px Category rail are visible; there is no separate supporting paragraph. Benefit chapters begin below the fold.

**Transfer:** Give a different product an equally lively object cluster and a compact direct promise rather than enlarging the headline. If detailed art is unavailable, use the geometric helper/device/token construction. A research opening instead uses a green 64px rounded promise, linked explanatory prose, check-mark results and a right-side illustration. A subject landing opens with a left-aligned 40px sans heading, 20px support, mint actions and right-side art on a pale mint band.

**Avoid:** Do not turn the default opening into an oversized typographic billboard, a full-bleed photo hero or a centered card containing a tiny illustration.

**Text style:** `opening-heading` — duolingo-sans 700 · 32px/44px

### Alternating benefit stage

**Observed:** Unboxed White stage chapters pair a 473px copy column with a 530px illustration and 101px gap, alternating the art side. A green chapter-heading is followed by gray body copy with 24px separation. Chapters are about 530px tall and center content vertically; a group receives 96px top and bottom padding.

**Transfer:** Give each chapter one benefit and one visual metaphor; use the image to explain what the short paragraph cannot.

**Text style:** `chapter-heading` — feather 700 · 48px/60px

### Immersive acquisition stage

**Observed:** Sky stage holds a centered deep-blue display heading constrained to 583px, then Download badge pair after 48px. Floating device field fills the sides and lower area of a 1289px chapter, with text layered in front.

**Transfer:** Use this as a major experiential pause rather than another alternating feature row.

**Text style:** `display` — feather 700 · 64px/80px · tracking -0.02em

### Premium interlude

**Observed:** Premium stage fills a 900px band. A 530px emblem stage sits left of an approximately 605px-wide illustrated title, with a small white action 48px below the lockup. The pair is vertically centered with broad empty space above and below.

**Transfer:** Apply only to a distinct upgrade offer; use Premium spectrum emblem as the construction language.

### Illustrated green close

**Observed:** A centered green display heading sits above one Primary button with 48px separation. Landscape invitation expands to the viewport edges and its green base continues into Green footer columns. Footer columns begin with 96px top padding; a 2px pale-green divider introduces the wrapping language directory, which has 40px top and 64px bottom padding.

**Transfer:** Make the invitation feel like the rewarding end of a journey and keep the artwork connected to the footer.

**Text style:** `display` — feather 700 · 64px/80px · tracking -0.02em

### Proof and story chapters

**Only for:** research and results pages

**Observed:** Centered green research-heading, centered 20px support paragraph, then a compact chart separated by 64px. A second heading introduces video-caption rows; the lead row is larger and later rows are compact, with 40px media-to-copy gaps and divider rules. The page ends after the stories in Compact footer, without an extra sales close.

**Transfer:** Move from verifiable outcomes to relatable human consequences; let this page type end quietly after its proof.

**Text style:** `research-heading` — feather 700 · 48px/1.1

### Focused device chapter

**Only for:** single-subject product landings

**Observed:** White stage alternates tall straight-on devices with centered text: muted uppercase eyebrow, 12px gap, 28px feature heading, 16px gap to 20px body, then an outlined mint action after 36px. A narrow FAQ stack follows. The final 400px Mint stage pairs a left 40px heading and solid action with right-side celebratory art; Compact footer comes afterward.

**Transfer:** Explain one task per chapter and resolve practical objections before the last invitation.

**Text style:** `feature-heading` — duolingo-sans 700 · 28px/32px

## Page flow

**Storyline:** Friendly promise → visual benefit demonstrations → confidence-building proof or product detail → rewarding invitation → page-appropriate navigation ending.

### Broad consumer-product introduction and acquisition

1. **Promise** — Small bold headline and two actions balance a large playful illustration, followed by a category rail.
2. **Benefit chapters** — Alternating illustrations and short green-headed explanations make the product approachable.
3. **Acquisition** — A sky-colored immersive device field presents platform destinations.
4. **Offer differentiation** — A midnight premium interlude and a white related-product chapter distinguish secondary offers.
5. **Closing call** — A green-headed invitation becomes an illustrated landscape flowing into a five-column green directory and language links.

**Transfer:** Use a buoyant illustrated narrative with one main action; vary the number and order of benefit and offer chapters to fit the product.

### Explain effectiveness and establish trust

1. **Proof promise** — Large green rounded heading, explanatory links, short check-mark result list and friendly illustration.
2. **Quantified proof** — Centered headline and support introduce a simple framed comparative chart.
3. **Human proof** — A sequence of videos paired with concise outcome captions makes the results personal.
4. **Navigation ending** — A ruled white compact utility footer closes directly after the stories.

**Transfer:** Use verified data and authentic outcome stories; preserve the quiet ending instead of importing the broad landing-page finale.

### Introduce a focused product capability and encourage first use

1. **Promise** — Pale mint opening pairs a left-aligned sans headline, support and stacked actions with subject art.
2. **Product demonstration** — Alternating tall device scenes explain one approachable feature at a time with eyebrows and repeated actions.
3. **Objection handling** — A narrow ruled FAQ answers practical questions.
4. **Closing call** — Pale mint band repeats a direct invitation beside celebratory subject art, then a compact white utility footer.

**Transfer:** Use the scoped mint and sans variant for a focused capability, keeping its device-led pacing distinct from the broad illustrated landing.

## Writing

Warm, encouraging and cheerfully matter-of-fact. Practical benefits sound easy to start, while scientific claims are supported with links and specific results rather than solemn institutional language.

**Do not copy:** Do not reuse Duolingo names, mascots, character designs, logos, proprietary illustration assets, product lockups, customer stories or unverified claims and numerical results. Source examples illustrate tone only.

- **Addressing the reader:** Speak directly to you and your; use we for the makers explaining how the product helps. Prefer inclusive, low-pressure invitations over commands that imply expertise.
- **Rhythm:** Short, punchy benefit headings, often lowercase. Supporting paragraphs are usually one or two compact sentences; subject features often use a single sentence. Uppercase belongs to controls and eyebrows rather than body prose.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Lead with pleasure or an accessible result, not a technical specification. | 6–14 words | “The most fun way to learn languages, chess, and more!” |
| Benefit heading | Use a compact lowercase phrase, sometimes a three-beat sequence with periods. | 2–4 words | “free. fun. effective.”<br>“stay motivated” |
| Support line | Explain a small action and useful benefit in ordinary words. | 10–25 words for focused features | “Learn the game one piece, one puzzle, one tactic at a time.” |
| Primary action | Short verb plus a simple start or trial cue. | 2–5 words | “Get started”<br>“Try 1 week free”<br>“Start playing” |
| Proof caption | State an activity followed by the real-life connection it enabled. | 10–18 words | “Learning French with [Brand] made it easier for Peter to travel” |
| Closing invitation | A friendly readiness question can echo the product's vocabulary. | 5–8 words | “Ready to make your move?” |

**Words and phrasing to use:** fun; bite-sized; delightful; at your level; your pace; get started; backed by science; easy to form a habit

**Avoid:** enterprise-grade synergy; dominate; disruptive ecosystem; unlock infinite potential; expert-only jargon

**Rules:**

- Pair emotional reassurance with a concrete explanation of how the product works.
- Make research language readable and link the specific meaningful claim.
- Let playful wordplay appear in a short heading or invitation, not in every sentence.
- Keep most paragraph copy calm even when illustrations are exuberant.

## Do's and Don'ts

### Do

- Keep default opening headlines at 32px bold, allowing the 424px illustration to share the spotlight.
- Use 48px rounded green benefit headings with a 24px gap before 17px/24px gray paragraphs.
- Preserve 330px-wide, 50px-high paired actions and their 12px stack gap.
- Let 530px illustration stages overhang the centered 988px text anchor.
- Use 64px display statements selectively, with -0.02em tracking.
- Carry the green closing landscape directly into the five-column footer.
- Use 2px light-gray rules to organize focused information without card boxes.
- Keep the 28px centered sans heading and tall device pairing limited to focused product chapters.

### Don't

- Do not use pill-shaped default actions; the characteristic corners are 12px, not 9999px.
- Do not replace the lower button lip with a soft floating drop shadow.
- Do not set every headline at 64px; the small opening and larger later statements are intentional.
- Do not put gray copy on dark panels throughout the page; white remains the dominant explanatory canvas.
- Do not spread the premium spectrum treatment across ordinary headings or navigation.
- Do not make research proof into giant decorative numbers; the result list uses compact 17px text and linked phrases.
- Do not use monochrome technical outline icons in place of colorful category emblems.
- Do not turn the compact white footer variant into a second expansive sales section.

## Motion and responsive

### Motion

**Observed:**

- No action or surface transition and no marketing animation timing is established.

**Transfer:**

- Compose tilted devices and floating tokens so their static arrangement already communicates buoyancy.

**Unknown:**

- Hero and scroll-animation sequencing, durations and easing are unspecified; interactive hover, focus-visible and active appearance are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 400px, 426px, 530px, 550px, 600px and 896px.

**Transfer:**

- For a narrower implementation, stack illustration and promise while preserving the modest headline-to-art balance; keep the action pair equal in width.
- Keep the landscape valley centered on its main object and allow peripheral tokens to clip rather than shrinking the whole illustration into a thumbnail.
- Allow footer columns to wrap while retaining the uninterrupted green field.

**Unknown:**

- Actual narrow-screen typography, stacking order, rail behavior and header substitutions are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
