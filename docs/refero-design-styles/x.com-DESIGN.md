# X — monochrome product theater

## Overview

An almost entirely white and pale-gray product world, with black grotesk typography and small, matter-of-fact interface labels. Physical product renders and isolated interface fragments give the sparse layout substance, while tiny black pill actions keep the presentation unusually restrained. It suits consumer technology and service launches that can pair a bold promise with tangible demonstrations and carefully qualified proof.

### Essentials

- The desktop page behaves like a product manual beside a showroom: a 208px sticky left rail, 24px rail padding, and an 1120px content field inside a 1152px article.
- The opening sells through a small sculptural object rather than oversized typography: a centered two-line 48px/52px medium headline above a 547×273px monochrome product stage, with a 40px separation.
- Headings speak in black-and-gray pairs: 32px/36px at weight 500 with -0.01em tracking, followed immediately by a same-size secondary line in 60% black.
- Actions look like compact interface controls: black pills only 24px high with 12px side padding and 13px/20px labels; the peripheral sign-in action is a 32px outlined pill.
- Color is a signal, not an environment: white and #f2f2f2 occupy virtually all the canvas; #00ba7c is confined to small positive-result annotations, never a section fill.
- Proof becomes a shallow spatial field: white miniature data cards float around a centered 48px claim on a pale-gray stage, with varying scale, fading, and selective blur. Use real product outcomes in equivalent cards when no physical product exists.
- The ending turns identity into architecture: a thin-outline wordmark spans the footer's 1184px inner width at about 270px high, after compact resource columns. An original outlined product name supplies the same monumental closing device.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Positive green | `#00ba7c` | `--color-positive` | text, accent | Small favorable metric annotations within marketing data cards, not broad decoration. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, accent | Primary headings, controls, pictograms, and filled primary actions. |
| Secondary gray | `#666666` | `--color-secondary` | text | Supporting headline lines and paragraphs; produced with rgba(0,0,0,0.6) over white. |
| Tertiary gray | `#b3b3b3` | `--color-tertiary` | accent, text | Tiny square section markers and subdued peripheral details; produced with rgba(0,0,0,0.3) over white. |
| Hairline gray | `#e6e6e6` | `--color-rule` | border | Section rules and the outlined action edge; produced with rgba(0,0,0,0.1) over white. |
| Pale gray stage | `#f2f2f2` | `--color-stage` | surface, background | Product media backings, data field, and expanded question background; also the visible result of 5% black over white. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas, miniature cards, and inverse button labels. |

## Typography

- **xVF** — Body, navigation, question lists, and utility section headings. Compact contemporary grotesk with a high x-height and modestly rounded forms. OpenType features: "ss11". If unavailable, use **Inter**. Use 400 and 500, with 580 for the selected navigation label. Font stack: "xVF", "Inter", ui-sans-serif, system-ui, sans-serif.
- **xVFDisplay** — Opening headline, editorial section headings, large proof claim, and data-card numbers. Tightly fitted display grotesk, visually close to the text family, without a heavy bold effect. OpenType features: "ss11". If unavailable, use **Inter**. Use 500 and preserve -0.01em tracking. Font stack: "xVFDisplay", "Inter", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | xVFDisplay | 500 | 48px | 52px | -0.01em | Centered opening promise and central proof statement. |
| heading | xVFDisplay | 500 | 32px | 1.125 | -0.01em | Editorial benefit headings and their equally prominent gray continuation. |
| utility-heading | xVF | 500 | 32px | 1.125 | -0.01em | Capability index and questions section heading pairs. |
| data-number | xVFDisplay | 500 | 24px | 28px | -0.01em | Principal numerical value in floating proof cards. |
| eyebrow | xVFDisplay | 500 | 13px | 20px | 0.04em | Sentence-case editorial labels and floating-card titles. |
| body | xVF | 400 | 13px | 20px | 0.01em | Compact explanatory paragraphs and question answers. |
| control | xVF | 500 | 13px | 20px | 0.010006em | Actions, questions, and numbered capability titles. |
| selected-nav | xVF | 580 | 13px | 20px | 0.010006em | Selected item in the desktop product navigation. |
| availability | xVF | 400 | 13px | 20px | normal | Single centered availability line beneath the opening object. |
| footer-heading | xVF | 500 | 13px | 1 | 0.01em | Resource column labels in the footer. |
| caption | xVF | 400 | 11px | 18px | 0.01em | Short qualification beneath the central claim and positive-result annotations. |

**Notes:**

- Use medium rather than heavy bold for all main headings. Both text and display families share the ss11 feature.
- Large type uses -0.01em tracking; small text usually switches to +0.01em, while display-family labels open to +0.04em.
- Black and gray heading lines have equal size and weight. The gray line is a continuation of the thought, not a smaller paragraph.
- The giant closing identity is outline SVG artwork, not an additional text-scale step.

## Layout

**Density:** Airy at section level and compact inside controls: 80px chapter padding surrounds 13px body text and very small actions.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-label and section-marker separation. |
| 12px | Eyebrow-to-heading gap, miniature-card padding, and support-line-to-action gap. |
| 16px | Desktop grid gutters and article side padding. |
| 18px | Question-item horizontal padding. |
| 24px | Navigation padding and media-tile interior. |
| 32px | Editorial column separation and footer column gutters. |
| 40px | Opening headline-to-object separation and footer row separation. |
| 48px | Capability grid row gaps and proof-heading-to-stage separation. |
| 56px | Capability heading-to-grid gap. |
| 64px | Opening bottom padding and footer top padding. |
| 80px | Main chapter top and standard bottom padding. |
| 96px | Footer resource area to outline identity separation. |
| 120px | Bottom padding after expansive proof and capability sections. |

### Containers and grids

- **site-shell**: max width 1440px · side padding 0px. Desktop flex shell with a 208px left navigation rail and remaining width devoted to the page.
- **article**: max width 1152px · side padding 16px. Centered within the space to the right of the rail; yields an 1120px working width.
- **opening-stack**: max width 656px · gap 40px. Centered headline and object stack; headline text itself spans about 560px.
- **editorial-triptych**: 3 columns · gap 32px. At desktop, a 328px headline column, 400px product-media column, and 328px supporting-information column.
- **capability-grid**: 8 columns · gap 16px. Media and adjacent copy generally span two columns each, making 268px cells; selected media spans four columns for a 552px-wide panel. Rows are separated by 48px.
- **questions-split**: 2 columns · gap 16px. Equal 552px columns: heading plus small action on the left, question list on the right.
- **footer-resources**: 3 columns · gap 32px · side padding 24px. Resource links in three columns beside a separate 160px theme-and-copyright lane; outline identity spans the full 1184px footer interior.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 9999px (pill) |
| expanded-question | 14.4px |
| media-panels | 0px |
| data-cards | 0px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Untextured and open; the navigation shares the same white rather than sitting on a different colored rail.

**Transfer:** Let the composition and objects supply depth instead of tinting the whole page.

#### Ruled chapter · level 0

**Use:** Boundaries between narrative chapters.

**CSS:** `border-top: 1px solid rgba(0,0,0,0.1); padding: 80px 0px`

**Observed:** Rules are inset to the article's working width. Larger content chapters finish with 120px bottom space.

**Transfer:** Separate ideas using a hairline and breathing room rather than boxed sections.

#### Gray product stage · level 1

**Use:** Backings for object renders, interface fragments, and the proof field.

**CSS:** `background: #f2f2f2; border-radius: 0px; box-shadow: none; overflow: hidden`

**Observed:** Rectangular and flat. White UI fragments appear to hover inside through their own scale and gentle layering, not a raised marketing-card shadow.

**Transfer:** Keep the backing neutral even when the demonstrated product has a stronger palette.

#### White proof card · level 2

**Use:** Miniature result cards in the gray field.

**CSS:** `background: #ffffff; padding: 12px; border-radius: 0px; box-shadow: none`

**Observed:** Small pictogram and title above a green annotation and black numerical value.

**Transfer:** Use a handful of legible, truthful output fragments; avoid turning the field into a dashboard.

#### Expanded question · level 1

**Use:** The revealed item in the question list.

**CSS:** `background: #f2f2f2; border-radius: 14.4px`

**Observed:** Only the open item gains a backing. Closed questions remain on white.

**Transfer:** Reserve the rounded panel treatment for interactive disclosure, not all content cards.

#### Stage edge fades · level 2

**Use:** Softened edges of the floating-card field.

**CSS:** `background: linear-gradient(#f2f2f2 0%, rgba(0,0,0,0) 100%); height: 97px; pointer-events: none`

**Observed:** A matching reversed fade sits at the bottom; the field loses detail toward its outer edges.

**Transfer:** Use fades to recess peripheral cards while protecting the center claim.

## Components

### Primary button

**Use:** Compact conversion or further-reading action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 24px; padding: 0px 12px; gap: 8px; background: #000000; color: #ffffff; border-radius: 9999px`

**Text style:** `control` — xVF 500 · 13px/20px · tracking 0.010006em

**Observed:** One-line text, content-width construction, centered under the opening object or aligned under a section heading.

**States:** Declared: hover background-color #000c; focus-visible outline 2px solid #1d9bf0 with outline-offset 1px; active background-color #000000b3.

**Transfer:** Use one short verb phrase without increasing the visual weight of the action.

### Outlined button

**Use:** Persistent peripheral account action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 32px; padding: 0px 16px; border: 1px solid rgba(0,0,0,0.1); color: #000000; border-radius: 9999px`

**Text style:** `control` — xVF 500 · 13px/20px · tracking 0.010006em

**Observed:** Anchored near the bottom of the navigation rail, subordinate to the main page action.

**States:** Declared: hover background-color #0000000d; focus-visible outline 2px solid #1d9bf0 with outline-offset 1px; active background-color #0003.

### Product navigation

**Use:** Persistent desktop orientation.

**CSS:** `position: sticky; top: 0px; width: 208px; height: 900px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between`

**Observed:** Brand and product switcher at top, five short vertical destinations beneath, and Outlined button at bottom. It occupies the viewport height.

**Transfer:** Use viewport-height sizing in implementation; preserve the narrow, white, unboxed rail and terse destinations.

### Navigation link

**Use:** Single destination in the left rail.

**CSS:** `display: flex; align-items: center; height: 32px; padding: 4px 0px; max-width: 160px; border-radius: 9999px`

**Text style:** `selected-nav` — xVF 580 · 13px/20px · tracking 0.010006em

**Observed:** The selected label is black at weight 580; other labels are secondary gray at weight 500. Label interiors have 8px horizontal and 2px vertical padding.

**Transfer:** Indicate location with weight and color, not a filled selection bar.

### Square marker label

**Use:** Introduce editorial benefits.

**CSS:** `display: flex; align-items: center; gap: 8px; color: #000000`

**Text style:** `eyebrow` — xVFDisplay 500 · 13px/20px · tracking 0.04em

**Observed:** A 4×4px tertiary-gray square precedes the sentence-case label; heading begins 12px below.

**Transfer:** Use a functional category name rather than an all-caps promotional kicker.

### Product media tile

**Use:** Back a small capability demonstration.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 24px; background: #f2f2f2; overflow: hidden; border-radius: 0px`

**Observed:** Default panel is 268×238px; wider object demonstrations span 552px. The numbered caption and paragraph are outside the tile in a neighboring white cell.

**Transfer:** Center one product output or object in each tile and give it generous breathing room.

### Floating result card

**Use:** Give the central proof scene tangible detail.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; background: #ffffff; padding: 12px; border-radius: 0px`

**Text style:** `data-number` — xVFDisplay 500 · 24px/28px · tracking -0.01em

**Observed:** Small icon and title occupy the top; a positive annotation sits above the main number below. Cards vary in visible size from roughly 129px to 199px wide through spatial scaling.

**Transfer:** Populate with meaningful outcomes and let only some cards be fully sharp.

### Question disclosure

**Use:** Answer likely objections without a long prose wall.

**CSS:** `display: flex; flex-direction: column; padding: 16px 18px; border-radius: 14.4px; overflow: hidden`

**Text style:** `control` — xVF 500 · 13px/20px · tracking 0.010006em

**Observed:** A full-width question button has a plus at right, becoming minus when open. Body copy appears just below in secondary gray. Closed rows are 52px tall with a 4px list gap; the shown expanded row is 96px tall and uses Expanded question.

**States:** Declared: hover not specified; focus-visible outline 2px solid #1d9bf0 with outline-offset 1px.

**Transfer:** Keep question headings visually small and let the answer remain a compact paragraph.

### Resource footer

**Use:** Close with utility and monumental identity.

**CSS:** `background: #ffffff; border-top: 1px solid rgba(0,0,0,0.1); padding: 64px 24px 32px`

**Text style:** `footer-heading` — xVF 500 · 13px/1 · tracking 0.01em

**Observed:** Three-column resource navigation uses 32px horizontal and 40px row gaps; theme controls sit in a separate left lane. Links are gray and compact. A full-width outline wordmark follows after 96px.

**Transfer:** Group the destination product's own resources by audience, then finish with an original outline identity.

## Imagery and graphics

### Monochrome unboxing object

**Use:** The opening's visual anchor.

**Observed:** A charcoal folding presentation envelope opens around a metallic silver card, viewed almost frontally from slightly above. The object is centered in a 547×273px canvas area on white, with restrained highlights and very little environmental shadow. Text takes less visual mass than the dark object.

**Transfer:** Render an original product or a sculptural representation of its output in graphite and brushed silver. Without 3D assets, use a carefully drawn folded sleeve and a single screen or document fragment rather than stock photography.

**Build:** Construct a shallow perspective scene: central charcoal trapezoid, two darker outward-opening side flaps, and a pale-gray rounded product rectangle centered in front. Use subtle gray linear gradients for folds and metallic sheen, a faint contact shadow, and a white surrounding canvas; fit the artwork inside the 547×273px stage.

### Cropped device demonstrations

**Use:** Editorial product and reassurance chapters.

**Observed:** Black-rimmed phone renders fill a 400px-wide gray-backed column, sometimes shown upright and sometimes enlarged until only the top corner and screen remain. Fine gray diagonal marks surround the phone; the UI is predominantly black and white with small green result labels. The device is sharply cut off by the bottom or side of its backing.

**Transfer:** Use a believable device shell or original app frame showing one relevant task. Favor a tight, purposeful crop over an entire generic dashboard.

**Build:** Place an original interface inside a black rounded device frame over #f2f2f2. Add a low-contrast SVG field of short diagonal strokes, each about 6px long, distributed loosely around the silhouette. Clip the composition to its panel and mask the lower edge softly where appropriate.

### Spatial proof field

**Use:** Signature quantitative proof device.

**Observed:** An 1120×560px pale-gray stage carries a centered black claim, while small white account-like cards sit around the edges, some clipped, some faded, some soft-focused. The center remains clear and the green appears only in tiny annotations.

**Transfer:** Create an equivalent field of original output or achievement cards surrounding one supported product result; the minimum version is a static composition with sharp near cards and faded distant cards.

**Build:** Use a relative gray stage with absolutely positioned White proof cards at the corners and sides, leaving a broad center exclusion zone. Vary scale roughly from 0.7 to 1.1, opacity from 0.4 to 1, and blur from 0px to about 2px. Layer the 48px claim and 11px qualifier above all cards; add 97px top and bottom gray-to-transparent masks.

### Outline closing identity

**Use:** Signature monumental ending.

**Observed:** An unfilled outlined brand/domain graphic spans 1184×270px at the bottom of the footer. Its very thin gray contour contrasts with the small solid text above; it stays inside the white field rather than becoming a dark closing banner.

**Transfer:** Draw the destination product's own short name or domain as outline lettering. If the name is too long, use a distinctive original abbreviated identity that can fill a wide, shallow frame.

**Build:** Convert a heavy grotesk wordmark to SVG paths, remove the fill, and apply a roughly 1px rgba(0,0,0,0.5) stroke with non-scaling-stroke. Use a wide viewBox near 4.4:1, stretch the artwork across the footer content width, and leave 96px above it.

### Icons

**Observed:** Small monochrome filled SVG pictograms, usually 16×16px in controls, 20×20px in feature lists, and 10–15px on miniature data cards. Gray square markers are geometric rather than pictorial. Question rows use a simple plus/minus.

**Transfer:** Choose restrained solid or near-solid utility symbols in black or secondary gray; keep them subordinate to the 13px labels and avoid multicolored illustration icons.

## Section recipes

How recurring sections are built.

### First screen: Object-centered opening

**Observed:** White canvas behind a persistent Product navigation rail. The remaining content area centers a 656px-wide stack: a balanced two-line 48px/52px headline at 80px from the top, a 40px gap, then the 547×273px Monochrome unboxing object. A single 13px availability line and Primary button complete the stack, with 12px between line and action. The opening ends around 617px with 64px bottom breathing room. Within the first 900px the whole headline, object, availability, and action are visible, followed by the top of a ruled editorial benefit chapter; the full later demonstration is below the fold.

**Transfer:** Make the opening equally tangible using a graphite-and-silver object or a folded geometric presentation of the new product's output. Keep the same centered mass and short promise. A support or feature-focused page can use a more specific promise and representative output while retaining this object-led composition.

**Avoid:** Do not replace the object-centered opening with a full-bleed photo, a huge background headline, or a two-column CTA-heavy SaaS hero.

**Text style:** `display` — xVFDisplay 500 · 48px/52px · tracking -0.01em

### Editorial benefit triptych

**Observed:** Ruled chapter with Square marker label and black/gray heading pair at left, a 400px device demonstration in the middle, and a short paragraph plus stacked icon facts at right. Columns read as 328px, 400px, and 328px with 32px gutters. The supporting facts sit toward the lower part of the right column.

**Transfer:** Match a capability to one visual demonstration and two or three concise supporting facts. A reassurance variant uses a tighter device crop and a small certification-like graphic only where justified.

**Text style:** `heading` — xVFDisplay 500 · 32px/1.125 · tracking -0.01em

### Central claim with peripheral outcomes

**Observed:** A marker label sits at left of the heading region while the black/gray heading pair is aligned in the right half. After a 48px gap, Spatial proof field supplies a centered 48px claim with a small qualification line and Floating result cards around its perimeter.

**Transfer:** Use one verifiable high-value result, with peripheral examples making the number tangible rather than competing with it.

**Text style:** `display` — xVFDisplay 500 · 48px/52px · tracking -0.01em

### Numbered capability weave

**Observed:** Utility heading pair followed by a 56px gap and an eight-column grid. Product media tiles and separate white caption cells alternate, with 16px gutters and 48px row gaps. Two-column media cells are 268×238px; selected wide panels span four columns. Two-digit sequence numbers sit near caption tops, with title and compact paragraph nearer the bottom.

**Transfer:** Use this staggered image/copy weave for a concise set of product tasks. Vary media spans to create rhythm without putting every feature in an identical rounded card.

**Text style:** `utility-heading` — xVF 500 · 32px/1.125 · tracking -0.01em

### Split questions and onward action

**Observed:** Two 552px halves separated by 16px. The left has a black/gray utility heading pair and Primary button 24px below; the right has Question disclosure items. The first answer is open against a pale-gray rounded backing while others remain plain white.

**Transfer:** Place common objections opposite a calm invitation to deeper help, using short direct questions and compact answers.

**Text style:** `utility-heading` — xVF 500 · 32px/1.125 · tracking -0.01em

### Qualified utility ending

**Observed:** A ruled, small-print qualification area precedes Resource footer. The footer has theme controls and copyright in a narrow lane, grouped resource columns to the right, then Outline closing identity across the full inner width. There is no oversized final CTA banner.

**Transfer:** Add only the qualifications the new product actually needs, then close through useful destinations and the monumental outline identity rather than another sales pitch.

## Page flow

**Storyline:** Promise and tangible object → benefit demonstration → quantified proof → capability detail → reassurance → objections → qualifications and utility-led identity close.

### Introduce a consumer product with concrete demonstrations and carefully bounded claims

1. **Promise** — Centered two-line statement, monochrome object, concise availability note, and a tiny action.
2. **Product demonstration** — Editorial triptych combines heading pair, device render, and short supporting facts.
3. **Quantified proof** — A central result stands within a gray spatial field of white outcome cards.
4. **Capability chapters** — Numbered media/copy weave explains practical tasks with alternating tile widths.
5. **Reassurance** — A closer device crop, short confidence-building heading pair, and compact explanatory copy.
6. **Objection handling** — Split heading and accordion list, with an onward help action.
7. **Qualification** — Compact numbered explanations and inline terms links separated from the marketing argument.
8. **Utility close** — Resource columns, theme controls, and a very large thin-outline identity.

**Transfer:** Use the storyline as a set of narrative functions, not a fixed section count. Preserve the physical-feeling opening, spatial proof device, and outline identity while adapting the balance of demonstration and reassurance to the product.

## Writing

Assured, spare, and practical. Strong benefit statements are paired with specific mechanisms and visible qualifications rather than exuberant sales language.

**Do not copy:** Do not reuse X names, logos, domain artwork, card designs, quoted claims, rates, insurance amounts, eligibility statements, or other product-specific facts as if they belong to a new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for reader benefits; use we sparingly for availability or support explanations. Name the product directly where clarity requires it.
- **Rhythm:** Short sentence-case headings, often two to five words, followed by one similarly short continuation. Body copy is usually one compact sentence; questions sound like things a customer would actually ask.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A reader-owned benefit followed by a broader promise, balanced across two lines. | 8–12 words | “Your money, on the world's most powerful network.” |
| Heading pair | Short concrete proposition in black, followed by an equal-sized outcome or explanation in gray. | 2–6 words per part | “Built to earn”<br>“Every dollar works harder on [Brand]” |
| Supporting line | Explain the mechanism in everyday verbs rather than abstract adjectives. | 15–25 words | “Your money shouldn’t sit idle. Earn yield, get cashback, and manage it all in one place.” |
| Primary action | Small, literal verb phrase describing the next step. | 2–4 words | “Follow for updates”<br>“See more FAQs” |
| Question | Plain first-person customer concern, phrased directly. | 5–9 words | “How do I get started?”<br>“Is my financial activity private?” |

**Words and phrasing to use:** Your; Built to; Everything; Get; Send; Protected; Up to; See terms

**Avoid:** revolutionary; game-changing; unleash; supercharge; incredible; exclamation-heavy urgency

**Rules:**

- State the practical benefit first and explain how it works immediately afterward.
- Pair superlative or numerical claims with applicable eligibility, comparison basis, or terms.
- Keep availability factual rather than turning restricted access into artificial scarcity.
- Use sentence case for section labels, titles, and actions; reserve two-digit numbering for the capability index.

## Do's and Don'ts

### Do

- Keep the desktop rail 208px wide and visually continuous with the white page.
- Use 48px/52px medium display type for the opening, not a massive billboard scale.
- Maintain equal 32px/36px black-and-gray heading pairs.
- Use 24px-high black pills for in-content actions and the 32px outlined variant for peripheral account access.
- Give gray media panels square corners and 24px interiors.
- Separate major ideas with 1px, 10%-black rules and 80px top padding.
- Keep data annotations green and small, generally 11px/18px.
- Include the full-width, thin-outline identity as an architectural closing gesture.

### Don't

- Do not spread the green accent into navigation, buttons, or large backdrops.
- Do not turn all panels into 14.4px rounded cards; that radius belongs to question disclosures.
- Do not substitute 16px body copy throughout; compact 13px/20px explanation is part of the contrast with the open layout.
- Do not make section support lines smaller than their black heading partners.
- Do not put numbers, title, and prose inside one generic feature card; media and caption occupy neighboring cells.
- Do not add decorative marketing-card drop shadows; the neutral backings are flat.
- Do not make the peripheral outcome cards equally sharp and equally prominent; preserve the center's hierarchy.
- Do not end with a saturated conversion strip that competes with the outline identity.

## Motion and responsive

### Motion

**Observed:**

- Opening words declare hero-word-in for 0.65s with cubic-bezier(.23, 1, .32, 1), applied word by word.
- Primary actions declare color-related transitions of .15s with cubic-bezier(.4, 0, .2, 1).
- Capability media declares opacity transitions of 0.5s with cubic-bezier(.32, .72, 0, 1).
- Navigation labels declare font-variation-settings and color transitions of 0.2s ease.
- Peripheral proof cards use transforms, opacity, and blur to create a shallow depth field.

**Transfer:**

- Animate the opening as discrete words rather than a continuous ticker.
- Keep the primary proof statement stable and readable while spatial changes are confined to peripheral cards.

**Unknown:**

- Exact word delays, complete object animation choreography, and floating-card cycle timings are not established.

### Responsive

**Observed:**

- Desktop uses a sticky left navigation; its CSS hides it below the tablet variant.
- Editorial and capability structures declare flex-column base layouts and desktop grid variants.
- The proof stage declares a 5:6 base aspect ratio and is 2:1 at desktop.
- The large outline footer identity is hidden below the desktop variant.

**Transfer:**

- On narrow screens, remove the rail's reserved width and stack editorial heading, media, and supporting copy.
- Keep capability demonstrations adjacent to their associated captions in reading order.
- When the wide outline identity is not displayed, retain a compact original identity in the utility footer rather than scaling the desktop artwork into illegibility.

**Unknown:**

- Exact breakpoint-to-variant mapping and the narrow-screen header composition are not established.
- Only the desktop composition defines measured typography and spacing defaults.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
