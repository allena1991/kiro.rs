# Wynde — bold utility, playful layers

## Overview

A bright, practical software-marketing style with chunky grotesk headlines, compact pill actions and large, cool-gray stages. Mostly white and black, it makes room for deep green and navy feature panels, soft blue illustrations and a surprisingly painterly layer behind real interface fragments. The feeling is approachable and useful rather than technical or luxurious, with spacious section composition and moderately dense explanatory copy.

### Essentials

- The opening is a split product stage, not a centered slogan: a 1280px-wide, 612px-high gray panel with 24px corners, equal columns and 32px inner padding; headline at the top left, support and actions anchored near the bottom left.
- Headlines have the heft of signage: bold grotesk at 68px/64px with -0.03em tracking in the opening, then 44px/50px with -0.01em tracking for section leads; body copy stays in Inter at 18px/27px.
- Actions are black lozenges rather than colored rectangles: 48px high, 52px radius, 12px 20px padding and 20px semibold labels; the companion action is filled cool gray, not outlined.
- Color arrives in contained chapters: most of the page remains white or cool gray, punctuated by 1280px-wide green and navy panels with 24px corners and pale lime or ice-blue text. Color does not become the default page background.
- Product proof is a layered collage: a roughly 300px-wide painterly image behind a floating white interface, a heatmap-like analytical overlay and a 259px-wide translucent summary card in front. Recreate the layering with a simplified original interface and abstract painted tile when finished product media is unavailable.
- Proof and the final invitation remain low-key: 20px-corner gray quotation cards with attribution along the bottom; the ending returns to a left-aligned 44px headline, one support line and one black pill on plain white, followed by a compact 75px footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep forest | `#00604a` | `--color-forest` | background, accent, text | Contained feature panel and emphasized savings phrase in quantified proof. |
| Deep marine | `#012b4b` | `--color-navy` | background | Contained reporting or product-output chapter. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale lime | `#efffb7` | `--color-lime` | text | Headings and support copy on the forest panel. |
| Ice blue | `#def0ff` | `--color-ice` | text | Headings and support copy on the navy panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, accent | Opening headline, body text, pictograms and primary action fills. |
| Near-black heading | `#181818` | `--color-heading` | text | Standard section headings and closing statement. |
| Secondary action ink | `#2b2b2b` | `--color-secondary-ink` | text | Label on the gray companion action. |
| Slate body | `#4c5259` | `--color-body-muted` | text | Secondary paragraphs, attributions and footer text. |
| Opening support | `#505459` | `--color-intro-muted` | text | Medium-weight support copy in the opening. |
| Muted statement | `#a2a6ab` | `--color-statement` | text | Large transitional brand-benefit statement. |
| Secondary action gray | `#dadfe5` | `--color-secondary-action` | action | Filled companion action beside the black primary pill. |
| Quote gray | `#edf0f4` | `--color-quote` | surface | Testimonial card backing; keep its role separate from the opening stage. |
| Cool stage | `#edf1f5` | `--color-stage` | surface | Opening product stage and compact secondary navigation action. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Primary page canvas, interface cards and reversed action labels; also used at 95% alpha in the navigation and 90% alpha in floating summaries. |

## Typography

- **Suisse Int'l** — Headlines, benefit statements and pricing amounts. Direct neo-grotesk with heavy, compact headline shapes; bold for headings and medium for pricing. If unavailable, use **Inter**. Use 700 for headlines and 500 for prices; preserve tight display tracking. Font stack: "Suisse Int'l", "Inter", Arial, sans-serif.
- **Inter** — Body copy, navigation, buttons, quotations and feature descriptions. Open, functional sans with clear numerals; regular paragraphs and medium or semibold short labels. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Suisse Int'l | 700 | 68px | 0.941 | -0.03em | Two-line opening promise. |
| heading | Suisse Int'l | 700 | 44px | 1.136 | -0.01em | Default section leads and closing invitation. |
| statement | Suisse Int'l | 700 | 36px | 1.222 | normal | Muted transitional benefit statement. |
| proof-heading | Suisse Int'l | 700 | 36px | 1.222 | -0.01em | Long benefit-led social-proof heading. |
| quantified-heading | Suisse Int'l | 700 | 36px | 1.194 | -0.01em | Quantified benefit statement with an inline forest-colored result. |
| button | Inter | 600 | 20px | 1 | -0.01em | Primary and secondary full-size action labels. |
| feature-title | Inter | 500 | 20px | 1.2 | normal | Short capability titles and method-list labels. |
| quotation | Inter | 500 | 20px | 1.4 | normal | Customer quotation card copy. |
| body | Inter | 400 | 18px | 1.5 | 0.01em | Default explanatory paragraphs. |
| opening-support | Inter | 500 | 18px | 1.556 | -0.01em | Support line at the bottom of the opening text column. |
| navigation | Inter | 500 | 15px | 1.8 | normal | Navigation links and compact header actions. |
| caption | Inter | 400 | 15px | 1.8 | 0.01em | Subordinate footer copy and legal links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| forest feature panels | forest-heading | Suisse Int'l | 700 | 44px | 1.091 | normal | Compact multiline headline against the forest surface. |
| navy feature panels | marine-heading | Suisse Int'l | 700 | 44px | 1.023 | normal | Tight headline above explanatory output copy. |
| pricing comparisons | price | Suisse Int'l | 500 | 28px | 0.57 | 0.02em | Plan amount or short sales-contact value; allow glyph overflow rather than clipping the tight line box. |
| pricing comparisons | plan-body | Inter | 400 | 18px | 1.556 | normal | Checkmarked plan benefits. |

**Notes:**

- Use the actual bold cut for headlines; the visual hierarchy is heavy, not regular-weight display typography.
- Tracking tightens from normal in the muted 36px statement to -0.01em at section size and -0.03em in the opening. Default body tracking is slightly positive.
- Section headings are usually sentence case and left aligned, without a preceding uppercase eyebrow. Pricing alone has short mixed-case plan labels.

## Layout

**Density:** Airy section framing around practical, moderately dense interface and explanatory content.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label spacing and compact list details. |
| 12px | Vertical gaps between pricing benefit rows; floating summary vertical padding. |
| 16px | Gap between opening actions and between feature titles and descriptions. |
| 24px | Heading-to-support and support-to-action gaps; testimonial padding; pricing grid gutters. |
| 32px | Opening inset, main two-column gutters and feature-media grid gutters. |
| 36px | Three-column text feature and trust-grid gutters. |
| 48px | Closing invitation vertical padding and proof heading band padding. |
| 64px | Major white-section vertical padding. |
| 96px | Longer bottom breathing room in supporting feature chapters. |

### Containers and grids

- **main-container**: max width 1280px · side padding 32px. Centered marketing content; at 1440px the content edges sit 80px from the viewport. Side padding protects the container as the window narrows.
- **split-stage**: max width 1280px · 2 columns · gap 0px. Equal halves for the opening, each 640px wide; text in one half, clipped layered product art in the other.
- **feature-pair**: 2 columns · gap 32px. 624px columns for explanatory copy, method lists and wide media.
- **text-features**: 3 columns · gap 36px. Approximately 403px-wide columns for compact icon-led benefits and trust information.
- **media-features**: 3 columns · gap 32px. Approximately 405px-wide illustrated capability cards.
- **pricing-grid**: 3 columns · gap 24px. Approximately 411px-wide plan cards; auto-fill columns use a 360px minimum.
- **statement-measure**: max width 880px. Limit long bold benefit statements and social-proof headlines; leave room at the right for a compact rating.

## Corner radius

| Element | Radius |
| --- | --- |
| major-stages | 24px |
| cards | 20px |
| floating-summary | 16px |
| full-size-actions | 52px |
| header-actions | 38px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| chapter-edge | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px` | Subtle separation beneath deep-colored chapter panels. |
| floating-summary | `rgba(41, 42, 52, 0.15) 0px 3.7px 32.8px 0px` | Diffused elevation on the translucent summary overlay. |

### Surfaces

#### Canvas · level 0

**Use:** Main background and unboxed text chapters.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Broad white fields separate the rounded media stages.

**Transfer:** Let whitespace organize prose instead of enclosing every feature in a card.

#### Product stage · level 1

**Use:** Opening product collage backing.

**CSS:** `background: #edf1f5; border-radius: 24px; overflow: hidden`

**Observed:** A single uninterrupted cool-gray rectangle ties together the text and art.

**Transfer:** Keep the backing flat and low-contrast so the collage supplies the complexity.

#### Forest chapter · level 1

**Use:** A major capability chapter.

**CSS:** `background: #00604a; color: #efffb7; border-radius: 24px; box-shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px; overflow: hidden`

**Observed:** 1280px by 600px contained panel, with the prose occupying roughly two fifths of its width.

**Transfer:** Use for a major capability rather than small decorative badges.

#### Marine chapter · level 1

**Use:** A product-output or analytical capability chapter.

**CSS:** `background: #012b4b; color: #def0ff; border-radius: 24px; box-shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px; overflow: hidden`

**Observed:** Same 1280px by 600px scale as the forest chapter; large report imagery extends toward the right.

**Transfer:** Pair ice-colored prose with a bright original output demonstration.

#### Quote backing · level 1

**Use:** Customer proof cards.

**CSS:** `background: #edf0f4; border-radius: 20px`

**Observed:** Flat gray fill without a heavy outline or visible elevation.

**Transfer:** Reserve the bottom of each card for attribution and a compact identity mark.

#### Floating summary · level 2

**Use:** Foreground annotation within a product collage.

**CSS:** `background: rgba(255, 255, 255, 0.9); border-radius: 16px; backdrop-filter: blur(12px); box-shadow: rgba(41, 42, 52, 0.15) 0px 3.7px 32.8px 0px; padding: 12px 16px`

**Observed:** A small white reading panel overlaps the lower-left part of the main interface.

**Transfer:** Summarize a believable product result in a short heading and a few lines.

## Components

### Sticky navigation

**Use:** Persistent global navigation.

**CSS:** `height: 64px; background: rgba(255, 255, 255, 0.95); backdrop-filter: blur(8px); padding: 0px 32px; display: flex; align-items: center; justify-content: center`

**Text style:** `navigation` — Inter 500 · 15px/1.8

**Observed:** Centered inner row follows the main container. A small black wordmark sits at left; right side contains plain section links, a play-icon demo link, a gray login pill and a black conversion pill.

**Transfer:** Use a compact original wordmark and a small number of purposeful links.

### Primary button

**Use:** Main conversion action in opening and ending.

**CSS:** `background: #000000; color: #ffffff; border-radius: 52px; padding: 12px 20px; height: 48px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — Inter 600 · 20px/1 · tracking -0.01em

**Observed:** Content-width pill; text-only default. Repeated at the end without enlarging or changing the treatment.

### Secondary button

**Use:** Companion demo or consultation action.

**CSS:** `background: #dadfe5; color: #2b2b2b; border-radius: 52px; padding: 12px 20px; height: 48px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — Inter 600 · 20px/1 · tracking -0.01em

**Observed:** Sits beside the Primary button with a 16px gap; same silhouette and visual label size, lower tonal contrast.

### Compact conversion pill

**Use:** Header conversion action.

**CSS:** `background: #000000; color: #ffffff; border-radius: 38px; padding: 2px 8px; height: 31px`

**Text style:** `navigation` — Inter 500 · 15px/1.8

**Observed:** A smaller version of the primary action, paired with a pale-gray login pill.

### Navigation link

**Use:** Plain header section links.

**CSS:** `color: #000000; text-decoration: none; transition: color 0.3s cubic-bezier(0.44, 0, 0.56, 1)`

**Text style:** `navigation` — Inter 500 · 15px/1.8

**Observed:** No enclosing card; the demo variant has a solid black play triangle to its left.

**States:** Declared: hover color rgba(0, 0, 0, 0.7), no underline; focus-visible and active treatments are unknown.

### Testimonial card

**Use:** Paired customer quotations.

**CSS:** `background: #edf0f4; border-radius: 20px; padding: 24px; height: 256px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `quotation` — Inter 500 · 20px/1.4

**Observed:** Two approximately 625px-wide cards share a row. Quote is at top; attribution is bottom left and customer logo bottom right. Short quotes retain the same roomy card height.

**Transfer:** Use authentic, differently sized quotations while keeping a common baseline for attribution.

### Footer row

**Use:** Compact legal and social ending.

**CSS:** `padding: 24px 32px; display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; color: #4c5259`

**Text style:** `caption` — Inter 400 · 15px/1.8 · tracking 0.01em

**Observed:** Copyright at left; small social icons and two legal links at right. White background continues uninterrupted from the closing invitation.

**Transfer:** End with a narrow functional row, not a second marketing section.

### Plan card

**Only for:** pricing comparisons

**Use:** Side-by-side commercial choices.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 24px 20px; display: flex; flex-direction: column; gap: 32px`

**Text style:** `plan-body` — Inter 400 · 18px/1.556

**Observed:** Mixed-case plan label above a Price value; benefits use small black checks with 8px icon gaps and 12px row spacing. The contact-led plan includes a white pill with a right arrow. Cards are distinguished by content, not saturated full-card fills.

**Transfer:** Keep plan names, amounts and inclusions scannable; no giant decorative price numerals.

## Imagery and graphics

### Painterly product collage

**Use:** Signature visual proof in the opening; carry this layered device into each new landing page.

**Observed:** The right half of the stage contains a warm ochre and muted blue painting of someone at a laptop, a white mobile financial interface in front, a multicolor heatmap across its upper content, and a translucent summary card in the foreground. The painting is roughly 300px by 330px; the interface roughly 285px wide and extends below the stage edge. Rounded rectangles, soft broad shadows and bottom clipping unify the stack.

**Transfer:** Create a product-specific stack of one warm creative image, one readable interface fragment and one compact result annotation. If there is no finished interface, draw a simplified task/result card with credible hierarchy; preserve the same overlap and mix of tactile color with functional UI.

**Build:** Use a relative art stage occupying one half of the panel. Place a rounded painterly tile toward its upper-left using an original illustration or SVG made of irregular ochre, amber and dusty-blue patches. Overlap a tall white interface card to its lower-right with about 20px corners and a diffuse black shadow at low alpha. Add a transparent analysis layer of blurred red-centered, yellow-middle, green-edge ellipses over only a narrow portion of that interface, not over page text. Place the Floating summary in front near the lower-left of the interface. Clip the entire group at the Product stage boundary.

### Capability media

**Use:** Feature explanations below the opening.

**Observed:** Large builder and report interfaces are accompanied by smaller illustrative UI cards, pastel-blue backings, floating text snippets, language pills and small variation badges. Media is staged as designed fragments rather than browser screenshots with surrounding desktop chrome.

**Transfer:** Show one relevant task per fragment and keep the marketing heading outside the interface. Use restrained pale-blue supports and white UI cards; retain the hierarchy between one large demonstration and smaller explanatory tiles.

### Customer identity marks

**Use:** Proof-card attribution and compact rating cluster.

**Observed:** Small customer logos occupy the bottom-right of quote cards. The section heading has a separate black review mark, star row and numerical rating at the far right.

**Transfer:** Use real customer identities and verified ratings only; keep marks compact and subordinate to the benefit statement.

### Icons

**Observed:** Mostly simple solid black pictograms at about 24px, with smaller 16px checks and arrows; some 24px outline icons use 2px round strokes. The navigation demo uses a filled play triangle.

**Transfer:** Choose a small, consistent functional set. Prefer solid black shapes for feature and action markers, with checks for inclusion lists and a right arrow for contact actions.

## Section recipes

How recurring sections are built.

### First screen: Split collage opening

**Observed:** A 64px Sticky navigation sits directly above the Product stage. The stage is centered at 1280px wide and 612px high, with equal text/art halves. A heavy 68px/64px Display headline occupies two lines at top left, about 576px wide. A deliberate open middle separates it from the bottom-left Opening-support paragraph, then a 24px gap leads to Primary button and Secondary button. Back-to-front layers on the right are gray backing, warm painterly tile, tall white interface with analysis overlay, then Floating summary. The art occupies about half the panel and is clipped along its bottom. All headline, support, actions and main art are visible within the first 900px, followed by a 36px muted statement on white. Capability details fall below that first screen.

**Transfer:** Preserve the top-promise/bottom-action separation and the layered object in the other half. Use original task and outcome fragments instead of depending on a complex full application. A more focused product or pricing page can open with a narrower promise and relevant proof object while retaining the same left alignment and stage language.

**Avoid:** Do not collapse this into a centered headline above a full-width browser mockup, or fill the open middle with badges and extra copy.

**Text style:** `display` — Suisse Int'l 700 · 68px/0.941 · tracking -0.03em

### Muted bridge

**Observed:** A Statement sits on white within an 880px measure, 48px below the opening; its soft gray color lowers the volume after the bold hero.

**Transfer:** Use one concise product-wide benefit statement as a breath between the promise and detailed capabilities.

**Text style:** `statement` — Suisse Int'l 700 · 36px/1.222

### Heading and capability list

**Observed:** A 44px Heading and Body paragraph share the left 624px column with a 24px internal gap. The right column contains an icon-led method list using Feature-title text. Columns have a 32px gutter.

**Transfer:** Pair the overall outcome with a concrete set of ways to achieve it; keep method labels brief.

**Text style:** `heading` — Suisse Int'l 700 · 44px/1.136 · tracking -0.01em

### Media capability grid

**Observed:** A large product-builder demonstration leads into three approximately 405px-wide media-led feature columns with 32px gutters. Illustrated UI comes above the short title and explanatory prose.

**Transfer:** Show the product at work, then isolate a few meaningful tools or differentiators. Avoid making every media tile a separate full product screenshot.

### Colored capability chapter

**Observed:** Forest chapter and Marine chapter are 600px-high rounded panels. Text occupies roughly two fifths of the width with 32px insets and 24px headline-to-copy gaps; the remaining space carries larger product imagery. The forest version uses Forest-heading and lime Body text; the navy version uses Marine-heading and ice Body text.

**Transfer:** Use these contained dark-color chapters to give major capabilities their own visual atmosphere without turning the whole site dark.

### Quantified proof

**Observed:** A 36px Quantified-heading at left highlights the result phrase in forest green, with support copy 24px below. A compact three-row comparison sits to the right; the whole white block has 64px vertical padding.

**Transfer:** Highlight one substantiated outcome inline with a sentence, then show a small comparison rather than a wall of oversized counters.

**Text style:** `quantified-heading` — Suisse Int'l 700 · 36px/1.194 · tracking -0.01em

### Unboxed supporting benefits

**Observed:** White sections use a three-column grid with 36px gutters, small pictograms, short titles and 18px Body explanations separated by 16px. The trust chapter adds a Heading and support paragraph above the grid.

**Transfer:** Use this lighter format for practical secondary benefits and reassurance rather than repeating illustrated cards.

### Paired customer proof

**Observed:** Proof-heading spans up to 880px; a compact rating cluster aligns at its right. Below, two Testimonial cards share a row with a 31px gap and aligned attribution rows.

**Transfer:** Lead with the outcome customers experience; let two authentic quotations carry the proof.

**Text style:** `proof-heading` — Suisse Int'l 700 · 36px/1.222 · tracking -0.01em

### Commercial comparison

**Observed:** Heading and Body introduction precede a small annual-discount toggle and three Plan cards in a 24px-gutter grid. Prices stay at 28px, and lists use full 18px type.

**Transfer:** Use a small number of meaningful choices with readable inclusions; keep the comparison visually lighter than the product stages.

**Text style:** `heading` — Suisse Int'l 700 · 44px/1.136 · tracking -0.01em

### Plain closing invitation

**Observed:** The ending is left aligned on white, not a dark banner: Heading, a single support line 24px below, then Primary button after another 24px. The section has 48px vertical padding and is followed by Footer row; there is no large sitemap or giant closing artwork.

**Transfer:** Close on one benefit and one action. Keep the restrained ending even when the page includes vivid media earlier.

**Text style:** `heading` — Suisse Int'l 700 · 44px/1.136 · tracking -0.01em

## Page flow

**Storyline:** Promise and tangible product proof → broad benefit → capability demonstrations → quantified and customer proof → reassurance and commercial choices → simple closing action.

### A software landing page that explains practical value and makes starting feel straightforward

1. **Promise** — Split collage opening pairs a short outcome promise with visible interface proof and two actions.
2. **Benefit framing** — Muted bridge introduces the broader payoff before detailed explanation.
3. **Capability demonstration** — Heading/list pair, large task UI and smaller illustrated feature columns explain what the product enables.
4. **Quantified proof** — A contained colored chapter is followed by an inline highlighted result and a compact comparison.
5. **Capability expansion** — A second colored output chapter and unboxed supporting benefits show how results become useful.
6. **Social proof** — A long outcome-led heading, rating and two equal testimonial cards.
7. **Objection handling** — Trust heading and three unboxed reassurance columns.
8. **Commercial choice** — Readable three-column pricing comparison with a small billing toggle.
9. **Closing call** — Plain white invitation, black pill and minimal legal/social footer.

**Transfer:** Adapt the number and order of capability and proof chapters to the product. Preserve the contrast between layered product stages, simple white prose blocks, contained deep-color chapters and an understated ending.

## Writing

Confident, helpful and conversational. It promises practical improvements and explains mechanisms in ordinary language rather than presenting a grand technical manifesto.

**Do not copy:** Do not reuse Wynde's name, wordmark, customer logos, quotations, numerical claims, prices, coverage counts or compliance claims as another product's assets or facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Use we for assistance and reassurance, and refer to the product by name when explaining what it does.
- **Rhythm:** Short imperative headlines alternate with one or two explanatory sentences. Feature descriptions can be conversational and moderately long; action labels stay concise and concrete.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A short command that removes friction or uncertainty. | 4–7 words | “Take the guesswork out” |
| Capability headline | Lead with an action and a useful result, sometimes adding a time benefit. | 3–10 words | “Create your perfect research study in minutes”<br>“Get detailed reports” |
| Supporting copy | Explain the mechanism in plain language, then connect it to the reader's next step. | 1–2 sentences | “Inside the report you can find all of the necessary information for making decisions and moving forward in your product development.” |
| Action | Verb-led, low-friction commitment with a clear next step. | 3–5 words | “Get started for free”<br>“Book a demo” |
| Closing invitation | State the broader positive outcome, then offer immediate progress. | 6–10 words in the headline | “Great decisions start with your users” |

**Words and phrasing to use:** create; get; share; your team; in minutes; right away; easy to use; we've got you covered

**Avoid:** revolutionary paradigm; unlock limitless potential; disrupt everything; enterprise-grade synergy

**Rules:**

- Pair broad benefits with specific capabilities rather than stacking unqualified superlatives.
- Use contractions and occasional reassuring asides, but keep headlines direct.
- Make numerical comparisons and trust statements only when the product can substantiate them.
- Keep navigation labels literal; reserve conversational warmth for supporting copy.

## Do's and Don'ts

### Do

- Keep the opening at 68px/64px with tight -0.03em tracking and a visibly bold cut.
- Use a 1280px centered container with 32px protective side padding.
- Maintain 24px gaps in heading/support/action stacks.
- Give large visual stages 24px corners and supporting cards 20px corners.
- Repeat the 48px black action pill at the end rather than creating a new CTA style.
- Keep colorful analytics inside product media and use deep green or navy for contained capability panels.
- Align attribution and compact customer marks along the bottom of quotation cards.
- Use 18px paragraph text even in practical benefit lists; this is not tiny dashboard copy.

### Don't

- Do not use a thin or regular display face merely because a font file is declared at weight 400; the headlines are visually bold.
- Do not substitute bright brand-colored primary buttons for the black pills.
- Do not turn the 24px rounded chapter panels into full-bleed dark page backgrounds.
- Do not apply the collage's glass blur and large soft shadows to every ordinary content card.
- Do not inflate 28px plan amounts into giant display numerals.
- Do not make every section lead a 68px headline; 44px is the regular section size.
- Do not replace the muted 36px bridge statement with an uppercase eyebrow.
- Do not add a dense multicolumn sitemap below the compact closing invitation.

## Motion and responsive

### Motion

**Observed:**

- Navigation section links declare color 0.3s cubic-bezier(0.44, 0, 0.56, 1), moving from black to 70% black on hover.
- No matched keyframe animations are defined; the navigation remains sticky while scrolling.

**Transfer:**

- Keep link motion tonal and small; the layered stage should remain readable as a still composition.

**Unknown:**

- Entrance-animation timing, scroll choreography and button focus/active treatments are not established.

### Responsive

**Observed:**

- A source width breakpoint exists at 1024px.
- Pricing and supporting feature grids use auto-fill layouts with 360px minimum columns; illustrated capability grids use a 320px minimum.

**Transfer:**

- On narrow screens, preserve the promise before the product collage and keep the two full-size actions together where they fit; stack them when necessary.
- Reflow three-column grids into fewer columns while retaining readable Body text and the distinction between unboxed prose and rounded media.
- Scale the layered art as a single composition, retaining its overlaps and clipping instead of scattering the cards between paragraphs.

**Unknown:**

- Exact mobile headline sizes, navigation replacement and narrow-screen stage heights are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
