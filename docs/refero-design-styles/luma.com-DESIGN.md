# Luma — floating invitations to delight

## Overview

An airy white world of floating, colorful artwork and friendly system-sans typography. Warm rainbow lettering and softly raised picture frames give an otherwise restrained interface a celebratory, tactile character. It suits approachable creative tools, consumer products and community-oriented services, balancing an expressive opening with compact, useful browsing grids.

### Essentials

- A small promise becomes a three-line centerpiece: centered system sans at 80px, weight 500, line-height 0.92 and -0.01em tracking, with only the final phrase colored by a violet–pink–orange–gold gradient.
- The opening is a floating gallery, not a split layout: a 900px-high white stage surrounds a roughly 450px text column with differently sized framed pictures, some clipped by the viewport and the lower ones fading into white. Recreate the gallery with original output samples or illustrated use cases when photography is unavailable.
- Conversion feels like a small physical object: the main action is a black 46px-high capsule with 100px radius, white 18px medium text and a long, soft layered shadow; its secondary action is a muted text link below it.
- Color is concentrated in pictures, small category symbols and two brief gradient statements; the full-width canvas and the entire browsing body remain white, with #151515 text and #ececec hairlines rather than tinted section bands.
- Browsing is deliberately modest beneath the spectacle: a 960px centered container, 16px grid gaps, 20px semibold section titles, 16px medium item titles and white cards edged by 12px rounded shells.
- A pale dot-field flourish and a gradient closing sentence form the second signature scene: use a 40px/1.2 centered statement, a 40px gap to two small capsules, and a compact footer over the same fading field.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gradient violet | `#ab46dd` | `--color-violet` | accent | First stop in the signature text gradient. |
| Gradient pink | `#f31a7c` | `--color-pink` | accent | Second stop in the signature text gradient. |
| Gradient orange | `#f8712b` | `--color-orange` | accent | Third stop in the signature text gradient. |
| Gradient gold | `#eaab26` | `--color-gold` | accent | Final stop in the signature text gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Main page and card interiors; inverse button text. |
| Soft control fill | `#f6f6f6` | `--color-soft` | surface | Low-emphasis capsules and media backing; rgba(21,21,21,0.04) over white. |
| Hairline gray | `#ececec` | `--color-edge` | border | Card edges and footer divider; rgba(21,21,21,0.08) over white. |
| Light gray text | `#ababab` | `--color-muted` | text, link | Support copy and metadata; visible result of rgba(21,21,21,0.36) over white. |
| Medium gray text | `#696969` | `--color-secondary` | text, link | Utility actions and footer navigation; rgba(21,21,21,0.64) over white. |
| Outline charcoal | `#353535` | `--color-outline` | border, text | Outlined closing action. |
| Near-black ink | `#151515` | `--color-ink` | text, action | Headlines, card titles and the primary capsule. |

## Typography

- **-apple-system** — All marketing text, headings, cards and controls. Native system sans with compact forms, open counters and medium rather than heavy display weights. Font stack: "-apple-system", system-ui, "Apple Color Emoji", Inter, Roboto, "Segoe UI", "Helvetica Neue", Arial, "Noto Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | -apple-system | 500 | 80px | 0.92 | -0.01em | Centered opening promise, broken into three short lines. |
| closing | -apple-system | 500 | 40px | 1.2 | normal | Two-line gradient closing statement. |
| section-heading | -apple-system | 600 | 20px | 1.2 | normal | Compact left-aligned browsing section titles. |
| intro | -apple-system | 400 | 20px | 1.5 | normal | Two-line centered hero support with inline example links. |
| primary-action | -apple-system | 500 | 18px | 1.5 | normal | Main conversion capsule. |
| item-title | -apple-system | 500 | 16px | 1.3 | normal | Media-card titles, directory names and category labels. |
| action | -apple-system | 500 | 16px | 1.5 | normal | Secondary action labels and closing capsules. |
| card-description | -apple-system | 400 | 14px | 1.486 | normal | Muted two-line descriptions inside directory cards. |
| caption | -apple-system | 400 | 14px | 1.5 | normal | Single-line metadata and footer navigation. |
| utility-action | -apple-system | 500 | 14px | 1.5 | normal | Small account capsule in the top navigation. |

**Notes:**

- Only the display tightens tracking and compresses line height. Smaller headings retain normal tracking and are distinguished by weight, not oversized scale.
- Most text uses weights 400–500; reserve 600 for the small section headings. The closing statement is half the opening display size.
- Keep titles short enough for two lines in cover cards, one line in compact horizontal cards, and two lines of muted explanation in directory cards.

## Layout

**Density:** Airy at the opening and ending, compact through the browsing body; large scene-level breathing room surrounds tightly organized cards.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Item title to metadata or description. |
| 8px | Compact flex gaps and footer link padding. |
| 12px | Cover to title, logo to title and horizontal closing-action gap. |
| 16px | All repeated grid gaps and main card side padding. |
| 20px | Section heading to grid and opening stack gaps. |
| 32px | Space above the hero secondary link. |
| 40px | Closing statement to its action pair. |
| 48px | Bottom of browsing region and closing-action section. |
| 64px | Separation between browsing chapters; footer top padding. |
| 96px | Transition from opening stage into browsing content. |
| 112px | Top padding of the final call to action. |

### Containers and grids

- **browse-container**: max width 960px · side padding 16px. Centered browsing body, roughly two thirds of the desktop width.
- **hero-copy**: max width 450px · side padding 20px. Centered support-copy column with the display title above.
- **closing-copy**: max width 600px · side padding 20px. Centered two-line closing statement.
- **cover-grid**: 6 columns · gap 16px. Square image cards with text below; 147px-wide items at desktop.
- **directory-grid**: 4 columns · gap 16px. 228px-wide compact cards, directory cards and category tiles sharing the same column alignment.

## Corner radius

| Element | Radius |
| --- | --- |
| primary capsule | 100px |
| closing capsules | 19px |
| utility capsule | 15px |
| card shell | 12px |
| card inset | 11px |
| square cover exterior | 24px |
| square cover interior | 16px |
| small logo | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| primary action depth | `rgba(0, 0, 0, 0.03) 0px 3px 3px 0px, rgba(0, 0, 0, 0.04) 0px 8px 7px 0px, rgba(0, 0, 0, 0.05) 0px 17px 14px 0px, rgba(0, 0, 0, 0.06) 0px 35px 29px 0px, rgba(0, 0, 0, 0.07) 0px 96px 80px 0px` | Broad soft elevation beneath the black hero capsule; the gallery uses similarly diffuse visual depth rather than crisp drop shadows. |

### Surfaces

#### White canvas · level 0

**Use:** Continuous background from opening through footer.

**CSS:** `background: #ffffff; color: #151515`

#### Hairline card shell · level 1

**Use:** Repeated browsing cards.

**CSS:** `position: relative; background: rgba(21, 21, 21, 0.08); border-radius: 12px; overflow: hidden`

**Observed:** A white inset sits 1px inside the shell with an 11px radius; the result reads as a nearly white card with a faint edge, not a gray slab.

**Transfer:** Use one inset layer shared by all compact, directory and category card variants.

#### White card inset · level 1

**Use:** Interior layer inside Hairline card shell.

**CSS:** `position: absolute; inset: 1px; background: linear-gradient(rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.8)), #ffffff; border-radius: 11px`

#### Rainbow lettering

**Use:** Last hero phrase and complete closing statement.

**CSS:** `background-image: linear-gradient(100deg, #ab46dd 0%, #f31a7c 36%, #f8712b 51%, #eaab26 77%); background-clip: text; color: transparent`

**Observed:** The opening phrase uses a radial gradient centered at 12px 12px with the same stops; the closing text uses the linear variant.

**Transfer:** Keep the spectrum within the letters, with black text carrying the rest of the opening promise.

## Components

### Primary button

**Use:** The opening's single main conversion action.

**CSS:** `background: #151515; color: #ffffff; border: 2px solid transparent; border-radius: 100px; padding: 10px 16px; height: 46px; box-sizing: border-box; display: inline-flex; align-items: center; justify-content: center; backdrop-filter: blur(16px); box-shadow: rgba(0, 0, 0, 0.03) 0px 3px 3px 0px, rgba(0, 0, 0, 0.04) 0px 8px 7px 0px, rgba(0, 0, 0, 0.05) 0px 17px 14px 0px, rgba(0, 0, 0, 0.06) 0px 35px 29px 0px, rgba(0, 0, 0, 0.07) 0px 96px 80px 0px`

**Text style:** `primary-action` — -apple-system 500 · 18px/1.5

**Observed:** Content-width capsule centered below the support line. The original also applies difference blending to the action.

**States:** Declared: hover color #ffffff, background rgba(255,255,255,0.16), border 2px solid rgba(255,255,255,0.16), no shadow; focus-visible not specified.

**Transfer:** Use difference blending only on the isolated opening stage so the main action remains legible.

### Utility capsule

**Use:** Account action at the top-right corner.

**CSS:** `background: rgba(21, 21, 21, 0.04); color: #696969; border: 1px solid transparent; border-radius: 15px; height: 30px; padding: 7px 10px; display: flex; align-items: center; box-sizing: border-box`

**Text style:** `utility-action` — -apple-system 500 · 14px/1.5

**Observed:** Sits opposite a small brand symbol in a sparse absolute header padded 14px vertically and 18px horizontally; there is no navigation menu across the center.

**States:** Declared: hover white text over rgba(21,21,21,0.64); focus-visible 2px outline in rgba(21,21,21,0.64).

### Secondary text action

**Use:** Low-emphasis alternative beneath the main capsule.

**CSS:** `color: #ababab; display: inline-flex; align-items: center; background: transparent; text-decoration: none`

**Text style:** `action` — -apple-system 500 · 16px/1.5

**Observed:** A small right arrow follows the label; the wrapper provides 32px top padding.

**States:** Declared: hover rgba(21,21,21,0.64); focus-visible 2px solid #959595 outline, offset 6px.

### Outline capsule

**Use:** Leading closing action.

**CSS:** `color: #353535; background: transparent; border: 1px solid #353535; border-radius: 19px; height: 38px; padding: 10px 14px; display: inline-flex; align-items: center; justify-content: center; box-sizing: border-box`

**Text style:** `action` — -apple-system 500 · 16px/1.5

**Observed:** First in a centered pair of compact actions, without an arrow.

**States:** Declared: hover white text with #555 background and border; focus-visible 2px solid #353535 outline.

### Soft capsule

**Use:** Secondary closing action.

**CSS:** `background: rgba(21, 21, 21, 0.04); color: #696969; border: 1px solid transparent; border-radius: 19px; height: 38px; padding: 10px 14px; display: inline-flex; align-items: center; justify-content: center; box-sizing: border-box`

**Text style:** `action` — -apple-system 500 · 16px/1.5

**Observed:** Paired with Outline capsule using 12px horizontal and 8px wrap gaps.

**States:** Declared: hover white text over rgba(21,21,21,0.64); focus-visible 2px outline in rgba(21,21,21,0.64).

### Directory card

**Use:** Compact proof or discovery items with an identity and short description.

**CSS:** `position: relative; background: rgba(21, 21, 21, 0.08); border-radius: 12px; overflow: hidden`

**Text style:** `item-title` — -apple-system 500 · 16px/1.3

**Observed:** Uses Hairline card shell and White card inset. A foreground stack has 16px top and side padding and 12px bottom padding: 48px square logo, 12px gap, one-line title, 4px gap, two muted description lines. Desktop size is 228px by 154px. A short horizontal variant is 65px high with the logo beside title and metadata.

**States:** Declared: hover text #d5176d and a faint layered shadow; focus-visible 2px rgba(21,21,21,0.16) outline with 2px offset.

**Transfer:** Use for integrations, user groups, examples or customer resources; keep descriptions specific and short.

### Category tile

**Use:** Quick exploration by a simple topic or use case.

**CSS:** `position: relative; background: rgba(21, 21, 21, 0.08); border-radius: 12px; height: 108px; overflow: hidden`

**Text style:** `item-title` — -apple-system 500 · 16px/1.3

**Observed:** Uses White card inset, with a small colored outline illustration at the upper left and a label near the lower left. Desktop tiles are 228px wide; four columns align with the directory cards.

**Transfer:** Use a different subdued hue for each simple pictogram, not a colored tile background.

### Cover card

**Use:** Image-led examples or current activity.

**CSS:** `display: block; color: #151515; text-decoration: none`

**Text style:** `item-title` — -apple-system 500 · 16px/1.3

**Observed:** A 147px square cover appears above a two-line title and muted single-line metadata. Cover backing uses rgba(21,21,21,0.04), a 24px exterior radius and a 16px inner image radius; 12px separates the image from text, 4px separates title and metadata.

**Transfer:** Keep image assets varied and expressive, while making text lengths and image aspect ratios consistent.

### Compact footer

**Use:** Useful links and social contact after the closing invitation.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; border-top: 1px solid rgba(21, 21, 21, 0.08); padding-top: 16px; margin: 16px 16px 0px`

**Text style:** `caption` — -apple-system 400 · 14px/1.5

**Observed:** A 960px wrapper has 64px top padding; the inner divider spans 928px. Small wordmark and four utility links sit left, three social/contact icons sit right, and a lighter legal row follows below. Footer links use 8px padding and medium-gray text.

**States:** Declared: navigation links turn #151515 on hover without underlining.

## Imagery and graphics

### Floating framed gallery

**Use:** Signature opening scene, surrounding rather than replacing the headline.

**Observed:** Vivid illustrated posters, photographic covers and playful graphic compositions float as individual square or near-square objects around a clear center. White translucent rims, fine gray edges, softly rounded corners and broad low-contrast shadows make the images feel like raised physical tiles. Sizes vary from roughly 130px to 220px; top and side items are partly outside the viewport, while lower items dissolve into the white floor.

**Transfer:** Create a family of original product outputs, use-case illustrations or customer-work cards. A minimum version uses six richly colored original compositions in the same framed, shadowed treatment; keep the center readable rather than substituting one giant interface image.

**Build:** Place square image objects in an absolute full-width layer behind the content, in staggered left and right clusters with one cropped top-center item. Use a translucent white outer frame, 1px rgba(21,21,21,0.08) edge, roughly 12px inset, 16–24px corners, and broad shadows such as 0px 24px 40px rgba(0,0,0,0.16). Size objects irregularly within 130–220px, leaving the central 490px clear. Add a foreground white linear-gradient fade at the lower edge so the gallery merges into the next section.

### Cover thumbnails and identity marks

**Use:** Browsing grids.

**Observed:** Square covers range from photographic scenes to dense colorful typography and illustrations. They are cropped to fill, not rendered as tiny floating browser windows. Small organization marks retain their own colors against white cards.

**Transfer:** Use actual output or editorial imagery for cover grids and small square identity art for directory cards; preserve image variety while keeping framing consistent.

### Fading dot-field flourish

**Use:** Signature closing backdrop beneath the final statement and footer.

**Observed:** A very pale, regularly spaced dot matrix spans the full width. Slightly stronger pink, purple and gold dots form sparse organic ripple-like clusters. The field fades into white at the top and remains behind the compact footer, never becoming a dark or saturated panel.

**Transfer:** Retain the dotted atmosphere for any product, using abstract loose waves instead of literal product symbols. The fine field should barely register until viewed beside the colored headline.

**Build:** Use an SVG pattern of 1px-radius circles on an 8px grid in rgba(21,21,21,0.04) across a 520px-high white region. Overlay sparse enlarged dots in rgba(243,26,124,0.12), rgba(171,70,221,0.10) and rgba(234,171,38,0.10), arranged in loose vertical waves. Mask the top with a white-to-transparent gradient and soften cluster edges with radial opacity masks; exact wave paths are not essential.

### Icons

**Observed:** Utility arrows and chevrons are small filled SVGs around 15–16px in muted gray. Footer social/contact symbols are compact outline marks. Category illustrations are simple colored outline pictograms, visually around 24px, with no enclosing colored badges.

**Transfer:** Use small neutral utility symbols for actions and lightly colored outline pictograms for categories; preserve the distinction between navigation icons and expressive topic art.

## Section recipes

How recurring sections are built.

### First screen: Floating gallery opening

**Observed:** A full-width 900px white stage with a sparse corner header. Behind the content, Floating framed gallery surrounds a clear center with clipped edge objects and a lower white fade. A small gray wordmark sits above a centered three-line promise spanning roughly a quarter of the screen width. The first two lines are black and the third is Rainbow lettering; display typography is 80px, weight 500, line-height 0.92 and -0.01em tracking. Two lines of light-gray support fit in a 450px column, followed by Primary button and Secondary text action. The complete message, both actions and surrounding gallery are visible within the first 900px; browsing begins below the fold after a 96px pause.

**Transfer:** Use an emotional benefit, a product noun and a short invitation as the three headline lines. Stage a varied family of original outputs around that message; when the product lacks media, commission or assemble colorful use-case illustrations in tactile frames. More utilitarian page types can open with the same centered promise and smaller surrounding gallery while keeping the expressive scene present elsewhere.

**Avoid:** Do not turn this into a left-aligned SaaS hero with a full-width dashboard below, or let the gallery cover the support text and actions.

**Text style:** `display` — -apple-system 500 · 80px/0.92 · tracking -0.01em

### Cover-led discovery row

**Observed:** A section-heading title with an inline location-like selector leads a six-column Cover card grid. Heading-to-grid gap is 20px; images are square with 12px to the title. Section ends with 64px of breathing room.

**Transfer:** Present recent work, use cases or useful examples; the inline selector can filter by audience, context or region.

**Text style:** `section-heading` — -apple-system 600 · 20px/1.2

### Compact directory chapters

**Observed:** Section headings remain only 20px semibold. Four-column grids use Directory card in short horizontal or taller stacked forms, sharing 16px gaps and consistent left edges. Descriptions are muted and clamped rather than expanding cards unevenly.

**Transfer:** Use the same card grammar for proof, resources or ecosystem entries, varying only the content density and identity placement.

**Text style:** `section-heading` — -apple-system 600 · 20px/1.2

### Category browse field

**Observed:** A plain heading precedes a four-column field of Category tile components. Small colored outline symbols occupy the upper-left area, with labels lower down and substantial empty space within each 108px tile.

**Transfer:** Reduce a product's capabilities or audiences to easy-to-scan topics, not explanatory paragraphs.

**Text style:** `section-heading` — -apple-system 600 · 20px/1.2

### Dotted closing invitation

**Observed:** A 520px full-width ending shares Fading dot-field flourish across call to action and footer. The call starts with 112px top padding; a 600px-wide centered Rainbow lettering statement uses 40px/1.2 medium type across two lines. A 40px gap leads to Outline capsule and Soft capsule. Compact footer follows with the same backdrop, a faint horizontal rule, utility links on the left, icons on the right and a quieter legal row below.

**Transfer:** End with an emotionally concrete future benefit, not a feature summary. Keep the gradient words and pale dotted field as the signature flourish regardless of the new subject.

**Text style:** `closing` — -apple-system 500 · 40px/1.2

## Page flow

**Storyline:** Emotional promise → tangible examples → broader ecosystem or capability discovery → simplified choices → warm closing invitation and utilities.

### Expressive marketing landing page that also serves as a practical discovery surface

1. **Promise** — A centered three-line benefit in a floating picture gallery, followed by one main action and a quieter discovery path.
2. **Tangible proof** — A compact row of colorful square examples with titles and metadata.
3. **Breadth** — Small horizontal highlights and taller identity-led directory cards make the offering feel active and populated.
4. **Choice simplification** — A regular grid of short category labels with colored outline symbols.
5. **Closing call** — A gradient future-facing sentence over pale dots, two capsules and an understated utility footer.

**Transfer:** Borrow the contrast between an imaginative opening and useful compact content. Adapt the examples and discovery chapters to the product's actual proof; the gallery and dotted closing can move or repeat without making the browsing sequence compulsory.

## Writing

Warm, uncomplicated and lightly celebratory. The promise is emotional and approachable, while supporting sections behave like useful labels rather than elaborate sales arguments.

**Do not copy:** Do not reuse Luma's name, wordmark, sparkle artwork, poster designs, community names, event listings, claims or customer facts. Replace them with the new product's own assets and supportable statements. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your in invitations; describe the product by name in the support sentence. Browsing labels are usually impersonal nouns.
- **Rhythm:** A short headline broken into clear rhythmic lines, one support sentence, then verb-led actions. Browsing titles are concise and descriptions stay within a couple of lines.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | An inviting adjective, a concrete noun, then a short starting-point phrase. | 4–6 words | “Delightful events start here” |
| Supporting line | A range of relatable examples followed by a simple ease-of-use promise. | One sentence | “From run clubs to launch parties and firework shows, [Brand] makes every event feel effortless.” |
| Primary action | Verb + your first + concrete result. | 4–5 words | “Create Your First Event” |
| Section title | Straightforward discovery verb or contextual noun phrase. | 3–4 words | “Explore Global Communities”<br>“Browse by Category” |
| Closing line | A future benefit addressed to the reader, expressed as an invitation rather than urgency. | 5–8 words | “Your next unforgettable memory awaits.” |

**Words and phrasing to use:** delightful; effortless; your next; your first; explore; discover; create; awaits

**Avoid:** revolutionary platform; enterprise-grade synergies; dominate; act now; 10x everything

**Rules:**

- Make the headline about the experience or outcome, not the internal technology.
- Use concrete examples to make breadth believable instead of stacking abstract adjectives.
- Let functional section labels be more literal than the opening and closing.
- Keep action labels specific enough that the result of clicking is obvious.

## Do's and Don'ts

### Do

- Keep the main headline at weight 500 with tight 0.92 line height; let its line breaks create the sculpture.
- Reserve the full rainbow for a short opening phrase and a two-line closing statement.
- Use a 960px common grid alignment with 16px gaps across browsing chapters.
- Make 20px semibold headings intentionally modest beneath the opening spectacle.
- Use 12px shell and 11px inset radii to produce faint-edged white cards.
- Keep support and metadata light gray, using #151515 for the information people must scan first.
- Give the black hero capsule its long soft shadow while keeping ordinary browsing cards almost flat.
- Carry the pale dot field behind both the closing call and the utility footer.

### Don't

- Do not use 700–900 display weights; the large promise relies on medium system-sans forms.
- Do not paint browsing sections in full-width rainbow gradients; color belongs to letters, images and small symbols.
- Do not make every button black: the closing pair uses one charcoal outline and one pale fill.
- Do not turn the 228px directory cards into spacious feature panels with oversized headings.
- Do not apply the hero's long layered shadow to every grid item.
- Do not replace the square cover row with wide cinematic thumbnails; its dense rhythm depends on equal squares.
- Do not add an elaborate multi-column sitemap ending; use compact inline navigation and a separate lighter legal row.
- Do not give category symbols heavy filled badges or colored tile backgrounds.

## Motion and responsive

### Motion

**Observed:**

- The opening title declares a 1.2s landing-title-rise animation with cubic-bezier(0.16,1,0.3,1).
- Most actions declare all .3s cubic-bezier(.4,0,.2,1); repeated cards declare box-shadow .3s with the same curve.
- The hero secondary link declares color .2s cubic-bezier(.4,0,.2,1); outlined and soft capsules exclude outlines from timed transitions.

**Transfer:**

- Reveal the short opening lines through clipped masks rather than adding motion to all the browsing copy.
- Keep card interaction primarily in faint elevation and text color; do not scale the dense grids dramatically.

**Unknown:**

- Gallery and dot-field animation paths, timing and interaction behavior are not established.
- Reduced-motion behavior is not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 450px, 451px, 650px, 800px, 820px, 1000px and 1921px.
- Closing actions use flex wrapping with 8px row and 12px column gaps.

**Transfer:**

- On narrow layouts, preserve the centered promise and clear middle column; move the floating frames toward edges and reduce their count in view rather than squeezing them into the text.
- Reduce browsing column counts while retaining square covers and the shared 16px gap; keep the closing sentence balanced and allow its action pair to wrap.

**Unknown:**

- Exact mobile headline sizes, gallery positions, column counts and breakpoint-specific behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
