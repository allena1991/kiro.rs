# Hilos — inked characters, editorial warmth

## Overview

An amiable editorial style for collaborative software and tools that need to feel inhabited rather than automated. Warm off-white grounds, near-black ink, and occasional buttery pastel panels pair expressive serif headlines with compact grotesk text. Black-and-white cartoon characters give the page its personality, while small interface scenes and a human-led film keep the product tangible. The body is spacious and restrained after a deliberately crowded opening.

### Essentials

- A crowded ink world surrounds a calm message: an edge-to-edge field of overlapping monochrome characters backs a centered white panel, 672px wide with 40px padding and 24px corners.
- Headlines sound and look like editorial statements: regular serif at 48px/1.05 with -0.01em tracking for the opening; a contrasting manifesto reaches 86.4px/0.98 with -0.02em tracking.
- Actions have emphatic cartoon contours: fully rounded pills, 14px semibold labels, 12px 24px padding, and a dark filled primary paired with a 2px black outlined film action.
- Color lives in bounded islands rather than across the page: #f1f2ee dominates the long body; blue, yellow, pink and peach fill the feature mosaic and peach conversion panel; #141510 anchors the ending.
- Illustration is a repeatable language, not a single mascot: small black-and-white figures punctuate headings and cards, with white bodies, black outlines and playful props. Carry the same device with original characterful objects when a product has no cast.
- A monumental typographic sign-off completes the brand world: a near-black full-width footer carries compact serif promise text, small link columns, then an oversized tightly tracked sans wordmark spanning the content width.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter yellow | `#f5df8d` | `--color-yellow` | surface | Feature-card backgrounds. |
| Apricot peach | `#f9b59f` | `--color-peach` | surface, text | Feature cards and conversion island; reversed label on its dark brown button. |
| Powder blue | `#b5d5f4` | `--color-blue` | surface | Feature-card backgrounds. |
| Warm chocolate | `#3c180f` | `--color-brown` | text, action | Peach-panel headline and action fill. |
| Deep blue ink | `#0f253b` | `--color-blue-ink` | text | Tone-matched text on blue cards. |
| Candy pink | `#f6cedf` | `--color-pink` | surface | Feature-card backgrounds. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Olive black | `#141510` | `--color-ink` | text, background, action, border | Headlines, primary action and full-width footer. |
| Outline black | `#000000` | `--color-black` | border, background | Outlined film action, strong illustrated contours and film backing. |
| Olive gray | `#6a6c62` | `--color-muted` | text | Support copy, small labels and numbering. |
| Paper hairline | `#d6d7d3` | `--color-rule` | border | Visible 12% ink separators over paper. |
| Soft stone | `#e8e9e5` | `--color-quiet-card` | surface | Visible neutral testimonial fill: #dbdbd7 at 40% over the paper canvas. |
| Warm paper | `#f1f2ee` | `--color-canvas` | background, text | Dominant page ground and reversed text on dark areas. |
| Clean white | `#ffffff` | `--color-white` | surface, background | Hero panel, navigation capsule, interface scenes and illustrated character interiors. |

## Typography

- **GeistSans** — Body copy, controls, labels and the monumental wordmark. Compact contemporary grotesk; matter-of-fact alongside the expressive serif. If unavailable, use **Geist**. Font stack: "GeistSans", "Geist", -apple-system, system-ui, "Segoe UI", sans-serif.
- **marketingDisplay** — Editorial headings, feature titles, questions and footer promise. Soft, high-contrast editorial serif with rounded details and warm, slightly quirky forms. OpenType features: "calt", "kern", "liga". If unavailable, use **Fraunces**. Use 400–600 weights with restrained softness and the specified negative tracking. Font stack: "marketingDisplay", "Fraunces", Georgia, Cambria, serif.
- **GeistMono** — Two-digit FAQ indexes. Small regular monospaced numerals acting as an organizational counterpoint to serif questions. If unavailable, use **Geist Mono**. Font stack: "GeistMono", "Geist Mono", ui-monospace, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| wordmark | GeistSans | 600 | 250px | 1.5 | -0.07em | fixed | Monumental footer identity; fit the final lettering to the full content width. |
| manifesto | marketingDisplay | 400 | 86.4px | 0.98 | -0.02em | size clamp(2.4rem, 7vw, 5.4rem) | The largest editorial statement, broken into short lines and interrupted by small illustrations. |
| questions-heading | marketingDisplay | 400 | 72px | 0.98 | -0.02em | size clamp(2.6rem, 6vw, 4.5rem) | Short oversized heading in the narrow left rail of the FAQ. |
| section-heading | marketingDisplay | 400 | 54.4px | 1.03 | -0.01em | size clamp(1.9rem, 4.5vw, 3.4rem) | Default substantial section title, left aligned. |
| hero | marketingDisplay | 400 | 48px | 1.05 | -0.01em | size clamp(1.9rem, 4.5vw, 3rem) | Centered opening headline, about two lines within a 490px measure. |
| closing-heading | marketingDisplay | 600 | 48px | 1.05 | -0.01em | size clamp(2rem, 5vw, 3rem) | Centered conversion headline on peach. |
| mosaic-heading | marketingDisplay | 400 | 44.8px | 1.05 | -0.01em | size clamp(1.7rem, 4vw, 2.8rem) | More compact two-line heading above the feature mosaic. |
| card-title | marketingDisplay | 600 | 23.2px | 1.1 | -0.01em | fixed | Pastel feature-card titles. |
| column-title | marketingDisplay | 600 | 22.4px | 1.1 | -0.01em | fixed | Titles in the separated three-column value row. |
| footer-promise | marketingDisplay | 600 | 22px | 1.25 | normal | fixed | Two-line closing statement above the wordmark. |
| question | marketingDisplay | 500 | 21.6px | 1.25 | normal | fixed | Accordion questions. |
| intro-label | GeistSans | 600 | 19px | 27px | 0.2em | fixed | Lowercase widely spaced introduction marker above the manifesto. |
| lead | GeistSans | 400 | 19px | 1.5 | normal | fixed | Manifesto support within a 512px measure. |
| quote | GeistSans | 400 | 17px | 28px | normal | fixed | Customer quotations in neutral cards. |
| body | GeistSans | 400 | 14px | 1.6 | normal | fixed | Opening support and explanatory section paragraphs. |
| button | GeistSans | 600 | 14px | 1.5 | normal | fixed | Conversion and film action labels. |
| answer | GeistSans | 400 | 14px | 1.65 | normal | fixed | Accordion answers aligned with question text. |
| card-body | GeistSans | 400 | 13.5px | 1.55 | normal | fixed | Concise descriptions below illustrated capabilities. |
| small-link | GeistSans | 400 | 13px | 1.5 | normal | fixed | Footer links and small reassurance text. |
| index | GeistMono | 400 | 12px | 1.5 | normal | fixed | Two-digit question indexes. |
| eyebrow | GeistSans | 600 | 11px | 15px | 0.24em, uppercase | fixed | Muted section labels, normally 16px above the headline. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep serif headline weights regular; reserve 600 for small card titles and the final conversion headline.
- Tighten serif tracking from -0.01em to -0.02em for the largest editorial statements. Eyebrows move in the opposite direction at 0.24em.
- The oversized footer lettering is sans, not the serif used for the promise above it. Preserve the contrast in both family and scale.

## Layout

**Density:** Airy between sections, compact inside product scenes and cards; the opening is deliberately dense around a calm central panel.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card title to description. |
| 12px | Opening action gap. |
| 16px | Eyebrow to section title and mosaic gutters. |
| 20px | Testimonial gutters and introduction label to statement. |
| 24px | Container side padding. |
| 28px | Feature and testimonial padding; support-to-action gap. |
| 40px | Hero-panel padding and heading-to-proof spacing. |
| 48px | Major split-layout gap and mosaic heading-to-grid gap. |
| 64px | FAQ column gap. |
| 80px | Conversion-island vertical padding and footer top padding. |
| 96px | Default major-section vertical padding and space above the giant footer identity. |

### Containers and grids

- **editorial-container**: max width 1100px · side padding 24px. Centered desktop container producing a 1052px content area.
- **hero-panel**: max width 672px · side padding 40px. A compact island centered in the first viewport.
- **product-split**: 2 columns · gap 48px. Text occupies the left portion while a roughly 543px white interface scene occupies the right.
- **feature-mosaic**: 3 columns · gap 16px. Equal-width columns with 273px short cards, 562px tall cards and a 696px two-column wide card.
- **testimonial-grid**: max width 1400px · 4 columns · gap 20px · side padding 24px. Wider-than-normal proof band; four equal cards with aligned bottoms.
- **faq-split**: 2 columns · gap 64px. A 0.8fr heading-and-illustration rail beside a 1.2fr question stack.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 9999px (pill) |
| hero-and-conversion | 24px |
| feature-cards | 16px |
| quotes-and-scenes | 18px |
| film | 36px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| hero-lift | `0px 18px 80px 0px rgba(0,0,0,0.18)` | Lift the calm white hero panel above the dense illustration field. |
| scene-lift | `0px 24px 60px -30px rgba(0,0,0,0.28), inset 0px 0px 0px 1px rgba(20,21,16,0.12)` | White product conversation panels. |
| film-lift | `0px 24px 80px 0px rgba(20,21,16,0.16)` | Wide film frame. |

### Surfaces

#### Paper canvas · level 0

**Use:** Continuous background for most of the page.

**CSS:** `background: #f1f2ee`

#### Outlined hero island · level 2

**Use:** Calm promise over busy illustration.

**CSS:** `background: #ffffff; border: 3px solid #000000; border-radius: 24px; box-shadow: 0px 18px 80px 0px rgba(0,0,0,0.18)`

**Observed:** A strong black contour keeps the white panel distinct even where the surrounding characters have white interiors.

**Transfer:** Keep the high-contrast perimeter when changing the surrounding illustration.

#### Product paper · level 1

**Use:** Small realistic interface demonstrations.

**CSS:** `background: #ffffff; border-radius: 18px; box-shadow: 0px 24px 60px -30px rgba(0,0,0,0.28), inset 0px 0px 0px 1px rgba(20,21,16,0.12)`

**Observed:** Compact conversation fragments float on the paper ground without a browser mockup.

#### Pastel tile · level 1

**Use:** Illustrated capability mosaic.

**CSS:** `background: #b5d5f4; border-radius: 16px; padding: 28px`

**Observed:** Flat blue, butter, pink and peach variants have no heavy shadow; each carries monochrome art and dark tone-matched text.

#### Quiet quote · level 1

**Use:** Customer proof cards.

**CSS:** `background: rgba(219,219,215,0.4); border-radius: 18px; padding: 28px`

**Observed:** Subtle stone tint creates grouping without white panels or conspicuous outlines.

#### Peach conversion island · level 1

**Use:** Warm final invitation.

**CSS:** `background: #f9b59f; color: #3c180f; border-radius: 24px; padding: 80px 48px`

#### Dark ending · level 0

**Use:** Full-width final identity field.

**CSS:** `background: #141510; color: #f1f2ee`

**Observed:** The only sustained dark page region, with generous room for oversized typography and a fine closing divider.

## Components

### Navigation capsule

**Use:** Compact top-level orientation over the illustrated opening.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 6px; background: #ffffff; border: 2px solid #141510; border-radius: 9999px; box-shadow: 0px 8px 30px 0px rgba(28,29,24,0.12)`

**Text style:** `body` — GeistSans 400 · 14px/1.6

**Observed:** Centered near the top rather than stretched into a full-width bar. Brand link leads, five small links follow, and a compact dark sign-in pill ends the row.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #141510; color: #f1f2ee; border-radius: 9999px; padding: 12px 24px`

**Text style:** `button` — GeistSans 600 · 14px/1.5

**Observed:** The hero's dark action sits to the right of the film action. A smaller sign-in variant uses 6px 16px padding; the peach-panel variant reverses peach text from chocolate.

**States:** Declared: hover and focus-visible styling are not specified for this action; active filter brightness(0.92).

### Film button

**Use:** Secondary opening action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; border: 2px solid #000000; border-radius: 9999px; padding: 12px 24px; color: #141510; background: transparent`

**Text style:** `button` — GeistSans 600 · 14px/1.5

**Observed:** A small outlined circular play glyph precedes the label. Equal prominence in shape but not fill beside the primary action.

**States:** Declared: hover and focus-visible styling are not specified for this action; active filter brightness(0.92).

### Hero message panel

**Use:** Opening promise, explanation and action group.

**CSS:** `max-width: 672px; padding: 40px; text-align: center; background: #ffffff; border: 3px solid #000000; border-radius: 24px; box-shadow: 0px 18px 80px 0px rgba(0,0,0,0.18)`

**Text style:** `hero` — marketingDisplay 400 · 48px/1.05 · tracking -0.01em

**Observed:** Small illustrated emblem precedes a two-line headline, then support, paired actions and a low-key reassurance with an underlined link.

**Transfer:** Keep the message compact enough for the surrounding visual world to remain visible.

### Illustrated feature tile

**Use:** Explain one capability in the pastel mosaic.

**CSS:** `display: flex; flex-direction: column; padding: 28px; background: #b5d5f4; color: #0f253b; border-radius: 16px`

**Text style:** `card-title` — marketingDisplay 600 · 23.2px/1.1 · tracking -0.01em

**Observed:** Tall tiles place a large centered illustration above bottom-aligned title and description. Wide tiles arrange illustration and copy side by side; shorter tiles use an illustration above text.

### Testimonial card

**Use:** Human validation in a wider proof band.

**CSS:** `display: flex; flex-direction: column; padding: 28px; border-radius: 18px; background: rgba(219,219,215,0.4)`

**Text style:** `quote` — GeistSans 400 · 17px/28px

**Observed:** A small portrait comes first, then an open unquoted text block. Name and role sit at the bottom with substantial breathing room, keeping the row aligned.

**Transfer:** Use real short testimonials and consistent attribution hierarchy, not star ratings or oversized quotation marks.

### Numbered accordion

**Use:** Direct answers to practical objections.

**CSS:** `border-top: 1px solid rgba(20,21,16,0.12); padding: 4px 0px`

**Text style:** `question` — marketingDisplay 500 · 21.6px/1.25

**Observed:** Each full-width trigger has 20px vertical padding, a 28px index column, 16px gap, serif question, and a plus at the far edge. Expanded copy aligns 44px in from the row edge and carries 24px bottom padding. The first row is open.

### Footer link

**Use:** Small secondary destinations in the dark ending.

**CSS:** `color: #f1f2ee; opacity: 0.7`

**Text style:** `small-link` — GeistSans 400 · 13px/1.5

**Observed:** Links sit in three compact columns; category labels are muted capitals. The account column includes a small white rounded-rectangle action rather than another large pill.

**States:** Declared: hover opacity 1; focus-visible styling is not specified; active filter brightness(0.92).

### Launch film frame

**Use:** A human explanation between technical proof and capability summaries.

**CSS:** `background: #000000; border-radius: 36px; overflow: hidden; aspect-ratio: 16 / 9; box-shadow: 0px 24px 80px 0px rgba(20,21,16,0.16)`

**Observed:** A wide presenter video, roughly 947px by 533px in the desktop composition, sits alone with ample surrounding paper.

## Imagery and graphics

### Inked crowd field

**Use:** Signature full-bleed opening background.

**Observed:** A dense crowd of friendly animals, robot faces and odd characters overlaps from edge to edge. Thick irregular black outlines, white interiors, black spot fills and tiny dot eyes produce a lively screen-printed comic effect. The figures are roughly 156px source tiles, stacked with substantial overlap; the center is covered by the white message panel.

**Transfer:** Create an original family of friendly figures or anthropomorphic tools related loosely to the new product. Keep the crowd and its monochrome density, not specific animals. The minimum version is a set of six original SVG figures repeated with varied overlap, scale and small rotation.

**Build:** Draw rounded irregular SVG silhouettes with 2px–4px black strokes, white fills, dot eyes and solid black patches. Use several head, ear and prop variants. Repeat approximately 150px figures on staggered rows with a 45px–65px horizontal advance and roughly 90px vertical advance. Clip to the viewport edges, vary stacking order, and place the bordered white panel above the field. Do not introduce gradients or colored outlines.

### Editorial character vignettes

**Use:** Recurring personality in headings, value columns, pastel cards, FAQ and final invitation.

**Observed:** Isolated black-and-white cartoon figures carry simple visual metaphors: a scooter, laptop, key or walking computer. Most are about 96px–220px wide; the opening emblem is 65px by 64px. Some overlap the large statement's words; others occupy generous empty regions of pastel cards.

**Transfer:** Use the same original cast and outline language as the crowd, now acting out the benefit. Retain small scale and generous blank surroundings; for abstract products use expressive tools with faces and a single prop.

**Build:** Reuse the crowd SVG vocabulary. Draw one silhouette, two dot eyes, sparse curved limbs and one recognizable prop. Keep 2px–3px black round strokes and white body fills; use solid black for one clothing or prop region. Place the transparent SVG directly on paper or pastel without a badge, frame or shadow.

### Product conversation scenes

**Use:** Demonstrate a complete workflow and a routed parallel workflow.

**Observed:** White rounded panels contain small avatars, restrained status marks and short believable conversation snippets. One scene sits opposite explanatory copy; another forks from a conversation into compact task rows with thin curved arrows. The marketing ground stays visible around them.

**Transfer:** Show the new product's smallest complete useful interaction, not a whole dashboard. Keep internal UI colors and small typography subordinate to the editorial headings.

### Presenter film

**Use:** Human-led product explanation.

**Observed:** A chest-up speaker behind a laptop, centered against a matte blue backdrop, fills a wide rounded video frame. Photography is confined to this film and small testimonial portraits rather than used as page decoration.

**Transfer:** Use a warmly direct person explaining the product with simple even lighting and a single-color physical background; avoid cinematic dark montages.

### Fading wordmark ribbon

**Use:** A slim social-proof interlude.

**Observed:** Mixed typographic customer identities run horizontally beneath a widely tracked centered label. The line extends beyond the viewport and fades into paper through 112px-wide edge masks.

**Transfer:** Use legitimate customer identities in monochrome at comparable visual heights; the ribbon should feel lighter than the illustrated mosaic.

**Build:** Arrange wordmarks in a single 45px-high flex row with generous spacing. Overlay 112px edge layers: linear-gradient(to right, #f1f2ee, rgba(241,242,238,0)) on the left and the reverse on the right.

### Icons

**Observed:** Small interface icons use 1.5px outlines, generally round caps and 14px–18px dimensions in muted olive gray or ink. Play glyphs are 16px; FAQ plus controls occupy about 25px.

**Transfer:** Use restrained outline symbols for controls; keep expressive character art separate from functional icons.

## Section recipes

How recurring sections are built.

### First screen: Crowded world, calm opening

**Observed:** The first 900px is a complete illustrated stage: warm paper behind an edge-to-edge black-and-white crowd, a compact white Navigation capsule centered near the top, and an Outlined hero island centered vertically. The island spans about 47% of the desktop width and is about 444px tall. Its 65px illustrated emblem sits over a centered 48px two-line serif headline spanning about 490px, followed by a small muted explanation. Film button is left of Primary button with a 12px gap; reassurance sits below. A separate small learn-more pill sits near the bottom, with two circular utility controls at the corners. The whole main illustration, headline, explanation and both actions are visible; the oversized editorial statement begins below the fold.

**Transfer:** Keep the visual contrast between an inhabited outer world and a concise inner promise. Without custom art, build an original repeated SVG character/tool crowd using Inked crowd field. For narrower-purpose pages, open with the same editorial headline language and a reduced cast around the content rather than an unrelated dashboard hero.

**Avoid:** Do not replace the crowd with a generic soft gradient, place the text directly on the busy artwork, or inflate the opening headline to manifesto scale.

**Text style:** `hero` — marketingDisplay 400 · 48px/1.05 · tracking -0.01em

### Illustrated manifesto

**Observed:** A 19px widely tracked lowercase introduction label precedes an 86.4px regular serif statement with 20px separation. Small character vignettes interrupt its short lines. A muted 19px paragraph sits 28px below in a 512px measure, with a larger isolated character off to the right.

**Transfer:** Turn the product promise into two concrete complementary actions and let two small illustrations punctuate the statement without becoming letter replacements.

**Text style:** `manifesto` — marketingDisplay 400 · 86.4px/0.98 · tracking -0.02em

### Explanation beside proof

**Observed:** An 11px uppercase eyebrow sits 16px above a compact serif title; support follows after 20px. A white Product paper scene sits beside the copy in a two-column composition. A subsequent explanation expands the demonstration into a forked conversation with small task rows and curved arrows.

**Transfer:** Pair each claim with a miniature end-to-end interaction. Let the proof become more specific as the reader moves down the page.

**Text style:** `hero` — marketingDisplay 400 · 48px/1.05 · tracking -0.01em

### Separated value columns

**Observed:** Three columns share the 1052px content width; 1px translucent ink vertical rules divide them. Each has a small vignette, a 22.4px semibold serif title and 13.5px support separated by 8px.

**Transfer:** Use this lightweight row for complementary principles or benefits that do not need full cards.

**Text style:** `column-title` — marketingDisplay 600 · 22.4px/1.1 · tracking -0.01em

### Pastel capability mosaic

**Observed:** Mosaic heading sits 48px above Illustrated feature tiles in a three-column, 16px-gutter grid. Tall blue and peach cards counterbalance a wide yellow card and shorter pink, yellow and blue cards. Each card keeps a large illustration-to-copy ratio and clear title/body grouping.

**Transfer:** Vary card spans according to narrative emphasis while retaining flat pastel fields, monochrome figures and restrained copy. The device is an illustrated mosaic, not a requirement for a particular number of features.

**Text style:** `mosaic-heading` — marketingDisplay 400 · 44.8px/1.05 · tracking -0.01em

### Expanded social proof

**Observed:** A fading identity ribbon creates a light interlude before a left-aligned eyebrow/title pair. Four Testimonial cards form a wider-than-normal row with 20px gutters and small portraits.

**Transfer:** Use the ribbon for breadth and individual human quotations for depth; preserve their very different densities.

**Text style:** `section-heading` — marketingDisplay 400 · 54.4px/1.03 · tracking -0.01em

### Editorial questions

**Observed:** A narrow left rail holds an eyebrow, a 72px serif heading on two lines and a 200px-wide cartoon person. A wider right rail contains Numbered accordion rows separated by hairlines; the first answer is expanded. The column gap is 64px.

**Transfer:** Answer practical objections directly and keep the illustration as a human counterweight to the orderly numbered list.

**Text style:** `questions-heading` — marketingDisplay 400 · 72px/0.98 · tracking -0.02em

### Warm invitation and monumental ending

**Observed:** Peach conversion island centers a 128px-tall character over a 48px semibold serif invitation, brief support and a chocolate pill action. Paper space separates it from Dark ending. The footer starts with a 22px serif promise left and three compact navigation columns right, then allows 96px before a giant tightly tracked sans identity across the content width. A fine divider and small three-part legal/status row finish the page.

**Transfer:** Include both a warm bounded invitation and a monumental typographic sign-off. Fit the new identity to the available width, using a short product name or concise brand phrase when the name is long; do not shrink it into a normal footer logo.

**Text style:** `closing-heading` — marketingDisplay 600 · 48px/1.05 · tracking -0.01em

## Page flow

**Storyline:** Inhabited promise → editorial explanation → concrete workflow proof → human explanation → capability breadth → customer validation → practical objections → warm invitation → monumental identity.

### Introduce a collaborative product, make its mechanics legible and reduce hesitation before signup

1. **Promise** — Dense monochrome illustrated world surrounding a calm centered message island.
2. **Positioning** — Oversized serif statement with small character interruptions and plain-language explanation.
3. **Product demonstration** — Compact conversation proof followed by a branching multi-step interaction.
4. **Human explanation** — A wide presenter film followed by three lightweight illustrated value columns.
5. **Capability chapters** — Asymmetric pastel mosaic with character metaphors and short explanations.
6. **Social proof** — Faded horizontal customer identities, then four substantial testimonial cards.
7. **Objection handling** — Split editorial FAQ with numbered hairline-separated questions.
8. **Closing call** — Peach invitation island with a single action, then a full-width dark typographic footer.

**Transfer:** Adapt the sequence to the product's decision journey; retain the crowded illustration, editorial serif voice, pastel mosaic and monumental ending as recognizable devices rather than duplicating the section count.

## Writing

Friendly, direct and operational. Confidence comes from describing what happens and who remains in control, with a little conversational wit rather than grand technology claims.

**Do not copy:** Do not reuse the Hilos name, domain, character artwork, customer identities, quotations, product-specific integrations or claims about cost, hosting, approvals and safety. Substitute accurate statements and licensed assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you in explanations. Product statements are often impersonal or use the product name; short human actions carry the story.
- **Rhythm:** Headlines usually contain 4–10 words, often two parallel clauses. Support combines a short explanatory sentence with clipped action sentences. Labels and actions stay literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the useful relationship in ordinary social language. | 7–10 words | “Your team and agents, in the same room.” |
| Editorial statement | Two concrete actions with parallel syntax and a period between them. | 6–10 words | “Plan in the channel. Ship from a thread.”<br>“Managers route. Specialists ship.” |
| Support | Explain the loop in plain words, ending with short sentences about the reader's role. | 20–35 words | “You ask in plain words. Agents ship to the repo and report back with a preview, a diff, and caveats. You review. They iterate.” |
| Action | Verb plus specific destination or result. | 2–5 words | “Create a workspace”<br>“Watch the launch film” |
| Objection handling | Ask the literal buyer question; answer the central issue immediately. | 3–10 words for questions | “What does it cost?”<br>“Fair questions.” |

**Words and phrasing to use:** plain words; room; together; ask; review; bring your own; the whole loop; real outcomes

**Avoid:** revolutionary; unlock limitless potential; next-generation synergy; magic that does everything; enterprise transformation jargon

**Rules:**

- Describe a visible action or useful relationship before naming a technical mechanism.
- Use paired short statements to express a contrast or shared responsibility.
- Keep reassurance specific and adjacent to the action or objection it resolves.
- Let the illustration supply the playfulness; keep interface labels and answers straightforward.

## Do's and Don'ts

### Do

- Keep most page area warm paper, using flat pastel panels as concentrated islands.
- Set the opening serif at 48px/1.05 and keep its text measure around 490px.
- Give major desktop sections 96px vertical padding within the 1100px container.
- Use 16px-radius feature tiles with 28px padding and 16px gutters.
- Keep the opening actions as dark and outlined pills with 14px semibold labels.
- Repeat the original monochrome character language at both crowd scale and vignette scale.
- Use the 11px/15px eyebrow with 0.24em tracking for section markers.
- End with an oversized sans identity on near-black, not just a row of links.

### Don't

- Do not make the whole body pure white; reserve white for raised message and interface panels.
- Do not add gradient fills or glossy shadows to the pastel mosaic.
- Do not turn all headings into bold sans; regular editorial serif carries the argument.
- Do not give feature tiles the 36px film radius; keep the shape hierarchy distinct.
- Do not oversize body text to compete with the serif headlines; default support is 14px.
- Do not use colorful stock illustrations or 3D mascots in place of flat ink drawings.
- Do not wrap every lightweight benefit in another card; the three-column row relies on separators.
- Do not recolor the entire footer with a pastel; its sustained #141510 field grounds the ending.

## Motion and responsive

### Motion

**Observed:**

- Opening panel entrance is declared at 0.55s with cubic-bezier(0.16, 1, 0.3, 1).
- Feature reveals declare opacity and transform transitions at 0.45s with cubic-bezier(.16, 1, .3, 1).
- Pressable actions declare 0.12s filter and color-related transitions; active uses brightness(0.92).
- FAQ expansion declares grid-template-rows transition at 280ms ease-out with a reduced-motion transition override.
- Status breathing and typing dots declare repeating 2s and 1.3s animations respectively.

**Transfer:**

- Keep the message panel's arrival distinct from the illustrated environment.
- Use subtle reveal and status motion without making the editorial copy or character art constantly bounce.

**Unknown:**

- Exact crowd interaction and movement paths, customer-ribbon timing and all animation choreography are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 600px, 640px, 767px, 768px, 1024px, 1280px and 1536px.
- Class rules indicate a one-column feature grid becoming two then three columns; opening actions stack before becoming a reversed desktop row.
- Testimonials declare horizontally scrollable, snap-centered cards at narrow sizes before becoming a four-column desktop grid.

**Transfer:**

- Preserve the crowd at screen edges while allowing the central panel to narrow and its actions to stack.
- Stack explanation/proof and FAQ rails, keeping each question's index and text aligned.
- Keep the footer identity monumental by fitting it to the available width rather than preserving its desktop font size.

**Unknown:**

- Exact mobile panel dimensions, navigation replacement behavior and rendered mobile layouts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
