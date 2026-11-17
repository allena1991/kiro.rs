# Delphi — humanist warmth in orbit

## Overview

A light, conversational identity for products that turn complex knowledge into personal help. Soft humanist display lettering and restrained grotesk text sit on ivory and near-white paper, with burnt-orange actions and pockets of wine, forest and deep blue. Portrait photography, faint orbital diagrams and softly illuminated cards make the experience feel inhabited rather than technical; dense browsing gives way to spacious explanatory chapters.

### Essentials

- Humanist headlines sound like spoken reassurance: 50px/1.02, weight 500, -0.035em tracking for the opening; 40px/1.1, weight 600, -0.025em for chapter headings, often with a gray second phrase.
- The opening is an invitation inside an orbit: faint concentric arcs and a low-intensity peach glow behind centered copy, followed by a raised white interaction panel about 672px wide. Include this atmospheric orbit device even when the product has no photography.
- Actions are small warm capsules, not oversized banners: the default orange button is 40px high with 26px corners and 14px/20px medium text; secondary actions use a 1px neutral outline.
- Color lives in bounded objects on a predominantly near-white canvas: a compact three-column deck uses wine, deep blue, forest and plum at 347×280px, while orange remains concentrated in actions and selected phrases. Keep the explanatory chapters and closing area neutral.
- People are staged as interfaces, not decorative stock imagery: 272×360px rounded portrait cards, dark lower scrims, short credentials and a glass question strip. Use real product outputs or editorial subject photography with the same framing when people are not the product.
- A second, nearly invisible voice lives behind the foreground: 92px/1 etched phrases at 0.028 opacity inside pale situation cards. Preserve a low-contrast typographic echo somewhere in the design rather than turning every proof point into a statistic.
- The page resolves into a plain-language closing line, not a last sales billboard: centered 40px/44px type in a 672px measure with paired 40px actions, separated from the preceding chapter by 128px.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Burnt orange | `#fd5400` | `--color-orange` | action, accent | Primary actions, focus border and selected filter. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Wine | `#440411` | `--color-wine` | surface, text | First deck card and faint etched text. |
| Deep petrol | `#042f44` | `--color-blue` | surface | Blue deck card. |
| Forest | `#044438` | `--color-forest` | surface | Green deck card. |
| Plum | `#4a1d40` | `--color-plum` | surface | Purple deck card. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#21201c` | `--color-ink` | text, background | Default headings, body text and dark selected filters. |
| Deck charcoal | `#23211f` | `--color-deck-charcoal` | surface, text | Dark neutral card and text on the light deck variant. |
| Warm gray | `#63635e` | `--color-muted` | text, link | Supporting text and the second phrase of display headings. |
| Dust gray | `#82827c` | `--color-caption` | text | Eyebrows and secondary navigation. |
| Button outline | `#cfceca` | `--color-outline` | border | Secondary button perimeter. |
| Warm white lettering | `#f0eae4` | `--color-ivory-text` | text, surface | Lettering on colored cards and pale portrait actions. |
| Card hairline | `#ebebeb` | `--color-edge` | border | Visible edge of white question cards; built with ink at 9% over white. |
| Filter wash | `#f1f1f0` | `--color-chip` | surface, border | Pale neutral chip fill; gray #8d8d86 at 10–12% over white. |
| Pale stone | `#f7f3f0` | `--color-stone` | surface | Situation cards and the light variant within the colored deck. |
| Opening cream | `#fcf8f3` | `--color-cream` | background | Upper portion of the opening wash, fading to the default canvas. |
| Near-white paper | `#f9f9f8` | `--color-canvas` | background | Default marketing canvas. |
| White | `#ffffff` | `--color-white` | surface, text | Raised cards and text over dark objects. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and company pages | Orange body | `#f8500f` | `--color-gradient-mid` | action | Middle stop of the polished orange button. |
| pricing and company pages | Orange edge | `#ec4705` | `--color-gradient-bottom` | action | Bottom of the polished orange button. |
| pricing and company pages | Orange highlight | `#ff6b2c` | `--color-gradient-top` | action | Top of the polished orange button. |
| recruitment pages | Crimson atmosphere | `#8f1420` | `--color-culture-red` | background | Backing for the red-orange atmospheric recruitment hero. |
| premium pricing | Premium wine | `#4a0f16` | `--color-premium-wine` | surface | High-service plan card. |
| pricing and company pages | Brown ink | `#2b180a` | `--color-brown` | text | Primary lettering on ivory. |
| pricing and company pages | Brown secondary | `#5a4a3d` | `--color-warm-muted` | text, link | Footer links, answers and quote text. |
| founder letters | Letter ink | `#4a3a2e` | `--color-letter-ink` | text | Long-form narrative text. |
| pricing and company pages | Taupe | `#94877c` | `--color-taupe` | text | Soft heading continuations and footer labels. |
| pricing and company pages | Ivory rule | `#eae4dc` | `--color-warm-rule` | border | Separators on warm pages. |
| pricing and company pages | Ivory canvas | `#fdf6ee` | `--color-warm-canvas` | background | Warmer canvas with brown rather than charcoal lettering. |
| pricing and company pages | Porcelain | `#fff9f5` | `--color-warm-card` | surface | Inset-lit raised plan cards. |

## Typography

- **Delphi Inter** — Paragraphs, controls, browsing headers and labels. An unobtrusive grotesk with open counters and compact medium-weight controls. OpenType features: "cv03", "cv04", "cv06", "cv09", "cv11", "ss08". If unavailable, use **Inter**. Use weights 400–600 and preserve the role-specific tracking. Font stack: "Delphi Inter", "Inter", ui-sans-serif, system-ui, sans-serif.
- **Delphi Pythia** — Headlines, topic cards, names and small category stamps. Soft, narrow humanist display lettering with gently flared strokes; it reads closer to a calligraphic sans than a conventional book serif. If unavailable, use **Lato**. Use 500–600; retain tight tracking and avoid a geometric substitute. Font stack: "Delphi Pythia", "Lato", Georgia, serif.
- **Martina Plantijn** (only for classic pricing pages) — Pricing headline and testimonial. A true light editorial serif, unlike the humanist default display face. If unavailable, use **Newsreader**. Use weight 300 with negative tracking. Font stack: "Martina Plantijn", "Newsreader", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| etch | Delphi Pythia | 500 | 92px | 1 | -0.045em | size clamp(56px, 6.4vw, 92px) | Ghosted background phrase, never the reading layer. |
| display | Delphi Pythia | 500 | 50px | 1.02 | -0.035em | size clamp(34px, 3.8vw, 50px) | Centered opening headline. |
| heading | Delphi Pythia | 600 | 40px | 1.1 | -0.025em | size clamp(28px, 4vw, 40px) | Feature chapter and closing headline. |
| question | Delphi Inter | 500 | 23px | 1.3 | -0.02em | size clamp(19px, 1.7vw, 23px) | Question-card copy with dark highlighted phrases inside gray sentences. |
| topic | Delphi Pythia | 600 | 22px | 1.15 | -0.025em | fixed | Multiline colored topic-card copy. |
| browse-heading | Delphi Inter | 500 | 20px | 1.4 | -0.025em | fixed | Compact collection section headers. |
| lead | Delphi Inter | 400 | 19px | 1.4 | -0.01em | size clamp(16px, 1.4vw, 19px) | One-line opening support. |
| body | Delphi Inter | 400 | 17px | 1.625 | normal | fixed | Explanatory prose beside product objects. |
| body-compact | Delphi Inter | 400 | 16px | 1.5 | normal | fixed | Short card paragraphs and input text. |
| control | Delphi Inter | 500 | 14px | 20px | normal | fixed | Actions, filter pills and sentence-case eyebrows. |
| stamp | Delphi Pythia | 600 | 11px | 24px | 0.09em, uppercase | fixed | Category marks pinned near card bottoms. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| recruitment pages | culture-display | Delphi Pythia | 600 | 72px | 1.02 | -0.03em | size clamp(42px, 6.2vw, 72px) | Two-tone centered recruitment invitation. |
| premium pricing | plans-display | Delphi Pythia | 600 | 60px | 1.04 | -0.03em | size clamp(34px, 4.4vw, 60px) | Premium plans opening. |
| classic pricing pages | classic-display | Martina Plantijn | 300 | 56px | 1.2 | -0.04em | fixed | Headline and closing atmospheric call. |
| founder letters | letter-display | Delphi Pythia | 600 | 54px | 1.02 | -0.03em | size clamp(36px, 5vw, 54px) | Two-line opening within the narrow letter panel. |
| pricing and company pages | warm-heading | Delphi Pythia | 600 | 52px | 1.08 | -0.03em | size clamp(32px, 4.4vw, 52px) | Major section leads on ivory. |
| classic pricing pages | classic-quote | Martina Plantijn | 300 | 40px | 1.32 | -0.02em | fixed | Centered testimonial. |
| premium pricing | plan-price | Delphi Pythia | 600 | 38px | 1 | -0.03em | fixed | Annual price; smaller currency marker sits at the upper baseline. |
| founder letters | letter-heading | Delphi Pythia | 600 | 36px | 1.08 | -0.03em | size clamp(28px, 3.4vw, 36px) | Narrative chapter titles. |
| classic pricing pages | classic-price | Delphi Inter | 500 | 35px | 1 | normal | fixed | Monthly price numerals. |
| premium pricing | plan-title | Delphi Pythia | 600 | 28px | 1.1 | -0.03em | size clamp(22px, 2.4vw, 28px) | Plan names. |
| founder letters | letter-question | Delphi Pythia | 600 italic | 26px | 1.3 | -0.02em | fixed | Centered question between prose chapters. |
| pricing and company pages | warm-title | Delphi Pythia | 600 | 26px | 1.2 | -0.03em | fixed | Principle titles and footer tagline. |
| founder letters | letter-body | Delphi Inter | 400 | 17.5px | 1.7 | normal | fixed | Sustained narrative paragraphs. |
| pricing and company pages | warm-link | Delphi Inter | 400 | 14px | 1.55 | normal | fixed | Footer links. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The default display face is humanist, not the book serif used by the classic pricing variant. Keep those two looks separate.
- Display continuations change color rather than weight or size. Do not turn the muted second phrase into a small subtitle.
- Small collection headings use sans while the contents of colored cards use the display family. Uppercase is confined to the tiny stamps.
- Tracking tightens with scale: -0.025em chapter type, -0.035em opening type and -0.045em ghost lettering.

## Layout

**Density:** Airy explanatory chapters follow compact browsing grids; a small control scale keeps the page from feeling like a presentation deck.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Compact icon and filter gaps. |
| 12px | Eyebrow-to-heading gap, stacked paragraphs and paired controls. |
| 16px | Topic and question grid gutters. |
| 20px | Topic-card padding. |
| 24px | Question-card padding and space before a chapter action. |
| 32px | Footer bands and group separations. |
| 64px | Two-column feature gutter. |
| 80px | Separation between compact browsing collections. |
| 96px | Warm-page major section padding. |
| 128px | Feature chapter and closing-call separation. |

### Containers and grids

- **Default container**: max width 1152px · side padding 40px. Centered desktop outer container, leaving 1072px of usable width.
- **Topic grid**: 3 columns · gap 16px. Equal-height colored objects, 347px wide at desktop.
- **Question grid**: 2 columns · gap 16px. 528px-wide white question cards.
- **Feature split**: 2 columns · gap 64px. Equal 504px columns; vertically center short copy against the product object and alternate sides.
- **Interaction stage**: max width 672px. Centered opening panel and final reassurance line.
- **Warm container** (only for pricing and company pages): max width 1180px · side padding 24px. 1132px usable width for three plan cards, two-column principles and the footer.
- **Letter** (only for founder letters): max width 680px · side padding 56px. Narrow centered paper panel with a 568px text measure.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Default actions | 26px |
|  | Topic and question cards | 24px |
|  | Portrait cards | 28px |
|  | Stamps | 6px |
|  | Filter pills | 9999px (pill) |
| pricing pages | Plan cards | 25px |
| recruitment pages | Culture image | 22px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Raised interaction | `0px 12px 12px 0px rgba(0,0,0,0.09), 0px 17.2px 17.2px -8.6px rgba(0,0,0,0.03), 0px 8.6px 8.6px -4.3px rgba(0,0,0,0.03), 0px 4.3px 4.3px -2.1px rgba(0,0,0,0.03), 0px 1.1px 1.1px -0.5px rgba(0,0,0,0.03), inset 0px -2.1px 2.1px #ffffff, inset 0px 2.1px 2.1px #ffffff` | Opening interaction panel; soft downward weight with white inset rims. |
| premium pricing | Porcelain plan | `inset 0px 2px 2px #ffffff, inset 0px -2px 2px #ffffff, 0px 0px 0px 1px rgba(0,0,0,0.04), 0px 1px 1px -0.5px rgba(0,0,0,0.03), 0px 4px 4px -2px rgba(0,0,0,0.03), 0px 8px 8px -4px rgba(0,0,0,0.03), 0px 16px 16px -8px rgba(0,0,0,0.03), 0px 31px 31px rgba(0,0,0,0.06)` | Substantial but soft plan-card elevation. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default page backing.

**CSS:** `background: #f9f9f8`

#### Opening wash · level 0

**Use:** Warmth behind the orbital opening.

**CSS:** `background: linear-gradient(#fcf8f3 62%, #f9f9f8)`

**Observed:** The cream disappears into the body without a hard section boundary.

**Transfer:** Keep the wash subdued enough for dark text and faint arc lines.

#### White card · level 1

**Use:** Question and reading objects.

**CSS:** `background: #ffffff; border: 1px solid rgba(33,32,28,0.09); border-radius: 24px`

#### Colored deck · level 1

**Use:** Concentrated chromatic browsing area.

**CSS:** `background: radial-gradient(140% 85% at 50% 118%, rgba(180,76,40,0.27), rgba(0,0,0,0) 72%), #440411; border-radius: 24px`

**Observed:** Dark wine, petrol, forest, charcoal and plum alternate with one pale stone card; low radial illumination pools just beneath the lower edge.

**Transfer:** Assign colors by content group, not status. Match the low glow; exact light stops are not essential.

#### Glass strip · level 2

**Use:** Short question affordance on portrait imagery.

**CSS:** `background: rgba(255,255,255,0.18); border-radius: 12px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.22); backdrop-filter: blur(8px)`

#### Ivory canvas · level 0

**Only for:** pricing and company pages

**Use:** Warmer informational-page backing.

**CSS:** `background: #fdf6ee; color: #2b180a`

#### Porcelain plan · level 1

**Only for:** premium pricing

**Use:** Raised purchase objects.

**CSS:** `background: #fff9f5; border-radius: 25px; box-shadow: inset 0px 2px 2px #ffffff, inset 0px -2px 2px #ffffff, 0px 0px 0px 1px rgba(0,0,0,0.04), 0px 1px 1px -0.5px rgba(0,0,0,0.03), 0px 4px 4px -2px rgba(0,0,0,0.03), 0px 8px 8px -4px rgba(0,0,0,0.03), 0px 16px 16px -8px rgba(0,0,0,0.03), 0px 31px 31px rgba(0,0,0,0.06)`

#### Wine plan · level 1

**Only for:** premium pricing

**Use:** High-service tier.

**CSS:** `background: radial-gradient(120% 70% at 100% 0%, rgba(255,255,255,0.1), rgba(0,0,0,0) 55%), #4a0f16; border-radius: 25px; box-shadow: inset 0px 1px 1px rgba(255,255,255,0.08), 0px 0px 0px 1px rgba(0,0,0,0.2), 0px 31px 31px rgba(0,0,0,0.12)`

**Observed:** The included-features box is white at 8% opacity, with pale warm text and a light action.

**Transfer:** Reserve this inversion for a genuinely different level of service.

## Components

### Navigation

**Use:** Persistent lightweight header.

**CSS:** `height: 64px; position: fixed; display: flex; align-items: center; gap: 12px; padding: 0px 20px 0px 12px; z-index: 40`

**Text style:** `control` — Delphi Inter 500 · 14px/20px

**Observed:** Small identity at left, sign-in and orange action at right; a white fading blur veil separates content as it scrolls beneath. Warm informational pages instead use a 68px sticky three-part header with centered links.

### Primary button

**Use:** Main conversion or demonstration action.

**CSS:** `background: #fd5400; color: #ffffff; height: 40px; padding: 0px 16px; border: 1px solid transparent; border-radius: 26px; display: inline-flex; align-items: center; justify-content: center; gap: 6px`

**Text style:** `control` — Delphi Inter 500 · 14px/20px

**Observed:** Compact text-first capsule; the header version is 36px high and small expansion actions are 32px high.

**States:** Declared: hover background #df4000; focus-visible border #fd5400; active scale 0.98.

### Secondary button

**Use:** Low-pressure alternate action.

**CSS:** `color: #21201c; background: transparent; border: 1px solid #cfceca; border-radius: 26px; height: 40px; padding: 0px 16px`

**Text style:** `control` — Delphi Inter 500 · 14px/20px

**Observed:** Sits beside the primary action rather than competing with it.

**States:** Declared: hover border #8d8d86; focus-visible border #fd5400; active scale 0.98.

### Filter pill

**Use:** Horizontal browsing choices.

**CSS:** `background: rgba(141,141,134,0.1); border-radius: 9999px; padding: 10px 16px; height: 40px; color: #63635e`

**Text style:** `control` — Delphi Inter 500 · 14px/20px

**Observed:** A single horizontal row with 8px gaps. The current all-items choice is orange; a personalized choice is charcoal with a small orange star.

**States:** Declared: hover gray wash at 15% and text #21201c; active scale 0.98.

### Topic card

**Use:** Browse a category through a concrete use case.

**CSS:** `background: #440411; color: #f0eae4; border-radius: 24px; padding: 20px; height: 280px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `topic` — Delphi Pythia 600 · 22px/1.15 · tracking -0.025em

**Observed:** Small identity mark at the top, tightly stacked premise and emphasized clause, then substantial empty space before a Stamp at the bottom. Uses Colored deck illumination.

**States:** Declared: hover translate 0px -3px; focus-visible outline 2px solid #21201c with 4px offset.

**Transfer:** Use a specific reader situation, not a feature name.

### Question card

**Use:** Show a recognizable problem in the reader's words.

**CSS:** `background: #ffffff; border: 1px solid rgba(33,32,28,0.09); border-radius: 24px; padding: 24px 24px 18px; height: 192px; display: flex; flex-direction: column; gap: 12px`

**Text style:** `question` — Delphi Inter 500 · 23px/1.3 · tracking -0.02em

**Observed:** Sentence at top, Stamp at lower left, a short overlapping cluster of portrait thumbnails at lower right. Gray setup and dark key clause share one text size.

### Stamp

**Use:** Tiny category label.

**CSS:** `background: rgba(255,255,255,0.14); color: #f0eae4; border-radius: 6px; padding: 0px 9px; height: 24px`

**Text style:** `stamp` — Delphi Pythia 600 · 11px/24px · tracking 0.09em · uppercase

**Observed:** Anchored at the bottom of a topic card. On white cards the fill changes to ink at 6% and the text becomes muted gray.

### Interaction panel

**Use:** An immediately usable opening object.

**CSS:** `background: #ffffff; border: 1px solid rgba(141,141,134,0.2); border-radius: 24px; max-width: 672px; box-shadow: 0px 12px 12px rgba(0,0,0,0.09), 0px 17.2px 17.2px -8.6px rgba(0,0,0,0.03), inset 0px -2.1px 2.1px #ffffff, inset 0px 2.1px 2.1px #ffffff`

**Text style:** `body-compact` — Delphi Inter 400 · 16px/1.5

**Observed:** A shallow white input with muted example text and a microphone at the right; its shadow makes it the main object below the headline. It becomes a more compact sticky capsule while browsing.

**Transfer:** Use a relevant search, prompt or one-step product control. If interaction is unavailable, show a real sample input and output rather than a decorative empty field.

### Plan card

**Only for:** premium pricing

**Use:** Compare service levels.

**CSS:** `background: #fff9f5; border-radius: 25px; padding: 28px 22px 22px; display: flex; flex-direction: column`

**Text style:** `plan-title` — Delphi Pythia 600 · 28px/1.1 · tracking -0.03em

**Observed:** Plan name, short audience sentence, Plan price, full-width capsule action and nested included-features panel. Equal desktop cards are 367×495px with 16px gaps. The first paid plan gets orange, the next gets a cream action, and the high-service Wine plan gets a light action.

**Transfer:** Keep the price and decision action above the denser feature list.

### Polished button

**Only for:** pricing and company pages

**Use:** Warm-page conversion action.

**CSS:** `background: linear-gradient(#ff6b2c 0%, #f8500f 55%, #ec4705 100%); color: #ffffff; border-radius: 9999px; height: 38px; padding: 0px 17px; box-shadow: inset 0px 1px rgba(255,255,255,0.35), inset 0px -1px rgba(120,30,0,0.25), 0px 0px 0px 1px rgba(200,60,0,0.55), 0px 1px 2px rgba(120,30,0,0.25), 0px 6px 14px -4px rgba(236,71,5,0.45)`

**Text style:** `control` — Delphi Inter 500 · 14px/20px

**Observed:** White lettering over a slightly convex warm surface. Section actions grow to 46px high with 22px side padding; full-width plan actions are 40px high.

**States:** Declared: hover translateY(-1px), brightness(1.04); focus-visible styling unknown; active translateY(0px) scale(0.985).

### FAQ row

**Only for:** pricing pages

**Use:** Objection handling.

**CSS:** `padding: 20px 0px; border-top: 1px solid rgba(149,135,124,0.22)`

**Text style:** `body-compact` — Delphi Inter 400 · 16px/1.5

**Observed:** Native disclosure rows with an 18px/28px medium question, plus sign at far right and 16px/26px answer. Closed rows remain a spare ruled list, not cards.

### Footer link

**Only for:** pricing and company pages

**Use:** Grouped secondary navigation.

**CSS:** `color: #5a4a3d; padding: 4px 0px`

**Text style:** `warm-link` — Delphi Inter 400 · 14px/1.55

**Observed:** Five columns with muted labels and a final social-icon group. A small identity on the left balances a 26px display tagline on the right above the first rule.

**States:** Declared: hover color #2b180a.

## Imagery and graphics

### Orbital invitation

**Use:** Signature opening atmosphere on ordinary marketing pages.

**Observed:** Hairline concentric arcs rise behind the centered headline and interaction panel. A very pale peach-orange glow sits high in the middle; small neutral capsules ride the arcs. The effect is mostly empty paper, not a diagram with strong outlines.

**Transfer:** Use brief domain labels around the product promise. The minimum version is three faint arcs and one soft warm glow behind real text.

**Build:** Create a full-width SVG with a 1440×520 viewBox. Draw three to four concentric circle outlines centered below the copy, using rgba(141,141,134,0.10), 1px strokes, with radii around 300px, 390px and 480px. Mask the lower and side edges into the canvas. Place a 520×300px radial orange light at 50% horizontal, fading from rgba(253,84,0,0.04) to transparent at 70%. Add 32px-high pale capsules sparingly along the arcs.

### Portrait deck

**Use:** Human proof and interactive subject selection.

**Observed:** Natural-color, close-framed people in vertical 272×360px windows with 28px corners. Names and one-line credentials sit on a lower black scrim; a Glass strip carries the question prompt. Selected cards gain a thin orange perimeter and a soft warm underglow. The horizontal rail fades at its right edge.

**Transfer:** Use real practitioners, customers or relevant subject photographs with similar face-to-frame scale. Without people, use authentic outputs in the same vertical framing and keep labels on a dark lower scrim.

**Build:** Use object-fit: cover; overlay a bottom gradient from transparent to rgba(0,0,0,0.35) at 50% to rgba(0,0,0,0.8). Place text and a translucent rounded strip above it. For emphasis add a 2px orange outline and a diffuse orange shadow below, not a full neon border.

### Etched phrase

**Use:** Signature quiet typography within situation objects.

**Observed:** An enlarged fragment is tucked behind readable prose, clipped by the rounded card and faded nearly to paper. At 92px with 0.028 opacity it is texture rather than a second headline.

**Transfer:** Repeat a meaningful short phrase from the foreground in the background layer.

**Build:** Position Etch type absolutely at the top of a Pale stone card, color wine, opacity 0.028. Mask horizontally from opaque through 40% to transparent at 92%, and vertically from opaque through 55% to transparent at the bottom. Keep foreground text in normal flow.

### Warm light field

**Only for:** recruitment pages and classic pricing calls

**Use:** A bounded emotional emphasis panel.

**Observed:** Soft red, crimson, orange and apricot bands cross a rounded rectangular field. The recruitment version is predominantly dark red with an apricot diagonal entering from the lower left; the pricing call is brighter with broad orange-red folds. White copy sits directly over the image.

**Transfer:** Use an abstract light field rather than a literal industry illustration; keep it inside a single rounded object.

**Build:** Layer a crimson base with a dark wine radial pool at upper left, a broad red central glow and an apricot rgba(255,190,125,0.85) ellipse entering from lower left. Rotate the ellipse about 20deg and blur it 45px; add a second faint orange diagonal across the lower half. Use 28px corners for a recruitment hero and keep the center calm enough for white text.

### People mosaic

**Only for:** premium pricing

**Use:** A visual counterweight to a broad entry-level offering card.

**Observed:** Two rows of small natural-color portraits, each 44×58px with arched tops and 7px lower corners, on a pale warm backing; the rightmost portraits dissolve into the panel.

**Transfer:** Show a varied set of real users or outputs; keep the compact repeated rhythm.

**Build:** Lay out two horizontal rows with 6px gaps, each thumbnail using border-radius:22px 22px 7px 7px. Mask the right edge with a linear fade to transparent.

### Place photography

**Only for:** recruitment pages

**Use:** Ground the workplace benefits in a real environment.

**Observed:** Warm late-day city and neighborhood photography, with houses in the foreground and skyline beyond, fills a 585×433px rounded frame beside a pale benefits panel.

**Transfer:** Choose an honest image of the new team's setting, warm natural light and enough environmental context; avoid staged office high-fives.

### Letter ornaments

**Only for:** founder letters

**Use:** Separate long narrative chapters and finish with a personal signature.

**Observed:** Tiny orange identity ornaments centered between prose chapters, followed by a handwritten signature and restrained author credit near the end. A monochrome press-logo strip sits outside the letter.

**Transfer:** Use the new identity's simplest mark as a divider and an authentic author signature. Keep press marks monochrome and optically balanced.

### Icons

**Observed:** Small neutral SVGs, generally 14–20px, with 18px filled action icons and 16–18px rounded 2px outline feature icons. Shuffle and rail arrows sit at the far right of collection headings. Portrait thumbnail groups have softly arched silhouettes rather than circular avatars.

**Transfer:** Use restrained outline glyphs for functions and recognizable filled marks for social links; preserve the small scale and pair them with clear text.

## Section recipes

How recurring sections are built.

### First screen: Orbit and interaction opening

**Observed:** A 64px transparent-to-white fixed Navigation frames an almost full-width cream-to-paper atmospheric field. Orbital invitation sits behind a centered single-line 50px display headline spanning about half the viewport, with a 19px support sentence beneath. The raised Interaction panel is narrower than the headline and occupies the middle of the composition; a small contribution link sits under it. Filter pills begin around the lower third of the first screen, followed by a compact Browse heading and the first row of Colored deck cards. Within 900px the headline, support, main interaction, navigation action, filters and most of the first card row are visible; the rest of the deck falls below.

**Transfer:** Lead with one concrete reader outcome and one immediately understandable product action. Without custom media, the orbit, raised input and colored use-case objects supply the main visual. Premium pricing opens with the same arcs, a 60px title and paired buttons instead of the input; recruitment uses a red light field and 72px two-tone invitation; a company letter opens directly inside a narrow paper panel.

**Avoid:** Do not replace the interactive center with a huge floating dashboard, a giant abstract logo or a full-screen orange background. Do not stretch the opening into a whole empty viewport.

**Text style:** `display` — Delphi Pythia 500 · 50px/1.02 · tracking -0.035em

### Browsing collection

**Observed:** Browse heading at 20px/28px sits opposite small shuffle or rail controls. A 16px gap leads to Topic cards in three columns, Question cards in two columns or a horizontal Portrait deck. Collection transitions use 80px of breathing room.

**Transfer:** Offer several concrete entry points to the product rather than repeating generic benefits.

**Text style:** `browse-heading` — Delphi Inter 500 · 20px/1.4 · tracking -0.025em

### Situation rail

**Observed:** Wide pale cards around 707×249px sit in a horizontal rail. Etched phrase lettering lives behind quoted foreground copy; Stamp and a right arrow finish the bottom edge. The next card peeks in and dissolves at the right boundary.

**Transfer:** Use long-tail real-world situations or customer tasks; keep the ghost lettering subordinate to the readable problem.

**Text style:** `question` — Delphi Inter 500 · 23px/1.3 · tracking -0.02em

### Alternating explanation

**Observed:** A two-column Feature split pairs a short eyebrow, two-tone Heading and 17px prose with a 504px-wide product object. Side placement alternates between chapters, with 128px separation. White expert-response cards, a conversation panel and a knowledge-to-link diagram are treated as discrete objects on the unchanged canvas.

**Transfer:** Explain an input, the resulting product behavior and its next use through separate focused objects. Keep internal UI simpler than a full dashboard.

**Text style:** `heading` — Delphi Pythia 600 · 40px/1.1 · tracking -0.025em

### Reassuring close

**Observed:** A centered two-line Heading sits in the Interaction stage measure with 24px before a Primary button and Secondary button, separated by 12px. The chapter starts 128px after the previous object; the background stays neutral. The compact default footer places identity and social links on the left, two short navigation columns on the right and a ruled legal row beneath.

**Transfer:** Resolve the original reader tension with one plain sentence, then offer a direct action and a lower-pressure learning path.

**Text style:** `heading` — Delphi Pythia 600 · 40px/1.1 · tracking -0.025em

### Premium comparison

**Only for:** premium pricing

**Observed:** An entry offering spans the full Warm container with text at left and People mosaic at right. A 52px section lead precedes three equal Plan cards. A warm raised pair is contrasted with the Wine plan. Below, Questions sits in the narrow left column while a 704px ruled FAQ list occupies the right. The ending is the five-column warm footer, not another hero.

**Transfer:** Separate the basic participation offer from paid service levels, then answer ownership, selection and upgrade concerns.

**Text style:** `warm-heading` — Delphi Pythia 600 · 52px/1.08 · tracking -0.03em

### Classic pricing and light call

**Only for:** classic pricing pages

**Observed:** A 56px light serif headline with taupe continuation opens above monthly/annual pills and four comparison columns. A centered 40px serif testimonial interrupts the purchase density. A 1200×417px warm light panel carries a white serif call, support line and small light action; three numbered warm step cards sit below. The footer ends with a left identity, right editorial promise, grouped links and a small operational-status pill.

**Transfer:** Use this serif-led variant for traditional plan comparison; let a genuine testimonial and short process explanation lower purchase anxiety.

**Text style:** `classic-display` — Martina Plantijn 300 · 56px/1.2 · tracking -0.04em

### Recruitment and culture

**Only for:** recruitment pages

**Observed:** A 1408×560px Warm light field sits 16px from each viewport edge with 28px corners. Centered white and translucent-white lines use Culture display. A glass capsule action leads to roles. A compact founder contact strip separates the hero from a centered section heading, grouped ruled job rows and a two-column principles grid with 56px gutters. A place photograph and a 36px-padded benefits panel close the content before the warm footer.

**Transfer:** Keep logistics explicit and culture claims short; use a real place image and ruled lists rather than a gallery of perks.

**Text style:** `culture-display` — Delphi Pythia 600 · 72px/1.02 · tracking -0.03em

### Personal letter

**Only for:** founder letters

**Observed:** A centered Letter panel begins beneath the navigation with a 54px two-tone heading and 17.5px/1.7 paragraphs. Chapter headings use 36px/1.08, orange ornaments separate chapters and a centered italic 26px question provides a pause. The letter ends with a two-tone conviction, handwritten signature and author credit. Outside it, monochrome press marks lead to a 52px two-tone closing invitation with an orange action, then the warm footer.

**Transfer:** Tell the motivating problem, personal origin, mechanism and wider consequence as a signed narrative; place external proof after the letter rather than in its margins.

**Text style:** `letter-display` — Delphi Pythia 600 · 54px/1.02 · tracking -0.03em

### Warm footer

**Only for:** pricing and company pages

**Observed:** 72px top and 32px bottom padding in the Warm container. An identity-left, 26px tagline-right row has 32px bottom padding and a hairline. Five link groups follow with 24px gutters and 32px vertical padding; the legal baseline is ruled above.

**Transfer:** Finish with a succinct product promise and a modest directory, not a new conversion panel.

**Text style:** `warm-title` — Delphi Pythia 600 · 26px/1.2 · tracking -0.03em

## Page flow

**Storyline:** Personal promise → concrete entry points or offer → credible human proof → focused explanation → decision support → reassuring resolution and restrained directory.

### Product discovery and adoption

1. **Promise** — Centered outcome and immediately usable prompt in an orbital field.
2. **Entry points** — Colored use-case deck, question grid, portrait rail and wide situation cards.
3. **Product explanation** — Short mission bridge followed by alternating input, response and sharing objects.
4. **Closing call** — Centered reassurance and paired actions, then compact social and navigation footer.

**Transfer:** For another product, move from recognizable user tasks to how the product handles them before inviting adoption.

### Classic plan comparison

1. **Promise** — Two-tone serif outcome headline and short support.
2. **Pricing** — Billing selector and four offer columns.
3. **Social proof** — One centered editorial testimonial and small author credit.
4. **Activation** — Red-orange light call above three numbered setup steps.
5. **Ending** — Editorial promise, directory, social links, operational status and legal baseline.

**Transfer:** Use familiar purchase structure while separating pricing detail from a visually warmer activation explanation.

### Premium service selection

1. **Promise** — Orbital title, supporting sentence, paired actions and short tab navigation.
2. **Offer architecture** — Full-width basic offer with compact portrait mosaic, then three paid plans.
3. **Objection handling** — Ruled disclosure list beside a short heading.
4. **Ending** — Tagline and five-column footer with social and legal links.

**Transfer:** Make the free or base layer understandable before comparing increasing service commitments.

### Recruitment

1. **Invitation** — Red atmospheric invitation and glass action.
2. **Personal trust** — Compact founder contact card.
3. **Opportunity** — Centered roles heading and grouped ruled job rows.
4. **Expectations** — Two-column principles followed by place photography and benefits.
5. **Ending** — Warm footer with tagline and five navigation groups.

**Transfer:** Balance emotional invitation with explicit roles, logistics and daily expectations.

### Company narrative

1. **Conviction** — Two-tone opening and sustained letter prose.
2. **Origin** — Personal story with ornamental chapter breaks.
3. **Mechanism** — Plain-language explanation in the same narrow reading column.
4. **Vision** — Wider consequence, closing conviction, signature and author credit.
5. **External proof** — Monochrome press strip outside the letter.
6. **Closing invitation** — Large two-tone invitation and orange action before the warm footer.

**Transfer:** Let a credible author explain the reason the product exists, then offer proof and one relevant next step.

## Writing

Warm, direct and intellectually serious without sounding academic. The product is explained through lived situations, useful questions and clear boundaries rather than technical spectacle.

**Do not copy:** Do not reuse Delphi's name, identity mark, proprietary product terms, portraits, author signatures, customer quotes, press affiliations, prices or performance claims. Source examples illustrate tone and structure only.

- **Addressing the reader:** Speak to the reader as you; use we for the team and first-person sentences for authentic user situations. Product nouns are explained in ordinary language.
- **Rhythm:** Headlines are short spoken clauses, often paired as two sentences or a dark premise and softer continuation. Support is one compact sentence; explanations use brief paragraphs. Questions can be longer and specific, but actions remain short.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A practical invitation framed around the reader's need. | 5–9 words | “Find people who've been there” |
| Support | Two short actions that connect input to outcome. | 6–12 words | “Describe your situation. Get their perspective.” |
| Chapter pair | State the action, then the resulting benefit in a quieter continuation. | Two short clauses | “Describe your situation. Get their perspective.”<br>“Someone could use your perspective, too.” |
| Primary action | Verb plus concrete object; functional rather than promotional. | 2–4 words | “See open roles”<br>“Describe your situation” |
| Objection answer | Answer directly before elaborating. | One or two short sentences | “You do. Your content and data stay yours.” |
| Culture title | A compact metaphor followed by practical expectations. | 2–4 words | “Embrace the marathon”<br>“Protect the flame” |
| Closing reassurance | Resolve the emotional friction named at the beginning. | 8–12 words | “You don’t have to figure everything out alone.” |

**Words and phrasing to use:** your situation; what you're figuring out; ask; explore; share; grounded in; experience; learn from; your own

**Avoid:** revolutionary; supercharge; 10x everything; AI magic; dominate; unlock limitless potential

**Rules:**

- Start with the human task before naming the mechanism.
- Use realistic, specific situations rather than abstract personas.
- State ownership and product limits plainly, without legalistic reassurance.
- Keep labels sentence case except tiny category stamps.
- Give each paragraph one job; let the two-tone heading carry the rhetorical turn.

## Do's and Don'ts

### Do

- Keep the default opening at 50px/1.02 with -0.035em tracking.
- Use a gray continuation at the same 40px/44px size as the main chapter phrase.
- Keep three-column topic objects at 24px corners and 16px gutters.
- Anchor 11px uppercase stamps low in their cards.
- Preserve the 64px gap between feature text and product object.
- Use the 672px measure for both the opening interaction and centered closing line.
- Keep the orbital linework faint and the warm glow low in opacity.
- Use the inset-white rims and layered low-alpha shadows only on raised interaction or purchase objects.

### Don't

- Do not substitute a conventional high-contrast book serif for the default humanist display lettering.
- Do not make all section leads 72px; that size belongs to the recruitment hero.
- Do not turn category stamps into 14px bold badges with pill corners; they are 11px with 6px corners.
- Do not apply the polished orange gradient to every default control; ordinary landing actions are flat orange.
- Do not spread wine, petrol and plum into alternating full-page background bands; they belong to bounded cards.
- Do not replace 16px grid gutters with huge editorial gaps inside browsing collections.
- Do not darken the etched phrase into a competing headline; its opacity is 0.028.
- Do not use luminous purple-blue technology gradients or glossy 3D robots in place of the warm human imagery.

## Motion and responsive

### Motion

**Observed:**

- Declared default action transitions: color, background-color, border-color, box-shadow, transform and opacity over 0.15s cubic-bezier(0.165,0.84,0.44,1).
- Declared topic-card transition: translate and box-shadow over .26s cubic-bezier(.165,.84,.44,1), with -3px hover lift.
- Declared polished-button transition: transform 0.2s cubic-bezier(0.2,0.7,0.2,1), box-shadow 0.2s and filter 0.2s.
- Declared portrait flip peek: 1.1s cubic-bezier(0.22,1,0.36,1), delayed 0.9s; topic labels use continuous linear orbital appearances.

**Transfer:**

- Use small lifts and warm edge emphasis to make cards feel touchable; reserve longer flipping behavior for two-sided portrait objects.
- Keep the opening interaction available while browsing as a compact sticky capsule rather than animating a large product stage over the content.

**Unknown:**

- Exact orbital durations and interaction timing are not specified.
- Scroll-trigger behavior and reduced-motion behavior are not established.

### Responsive

**Observed:**

- The default layout declares width breakpoints including 640px, 768px, 1024px and 1280px.
- Default topic grids declare one column before their multi-column variants; question grids declare a flex-column base and two columns at medium widths.
- The outer default container uses 20px side padding at its narrow base, 32px at medium widths and 40px on desktop.
- Headline sizes use the clamp formulas in the typography recipes.

**Transfer:**

- Recommended: stack feature text before its demonstration when two 504px objects no longer fit; keep the orbital field behind the centered opening rather than shrinking it into a thumbnail.
- Recommended: preserve horizontal overflow for filters and portrait rails, with a soft edge fade. Stack plan cards and letter content without reducing body text size.

**Unknown:**

- Only desktop arrangements are established; exact mobile navigation, footer wrapping and sticky-panel dimensions remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
