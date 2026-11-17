# Fourmula — orbit to orange

## Overview

An airy, image-led style that pairs almost-black neo-grotesk typography with white and pale-gray editorial grids. Small floating photographic objects give way to immersive orange-ended gradient stages, making creative software feel tactile and fashion-conscious rather than technical. The density alternates between sparse statements and rich product imagery, with a playful dot-field ending.

### Essentials

- The promise sits below the spectacle: a 900px white opening holds a central orbit of eight rounded image tiles around an upload tile, with a 73.2px two-line headline anchored bottom-left.
- Headlines behave like editorial slabs, not bold slogans: regular-weight grotesk at 99.8px/1 with -0.03em tracking for major statements, and 73.2px/0.94 for the opening.
- Navigation is a miniature floating instrument: a 206×40px black capsule combines Menu, a circular theme control and a progress readout; conversion remains a separate 40px pill at the right.
- Color arrives as an immersive chapter rather than decoration: white and #f7f7f7 dominate roughly two thirds of the long page, while 900px workflow stages move from orange, blue, violet or deep red into orange with white type.
- Media lives in soft geometry: 39.9px pale-gray feature shells, 20px rounded photographs and 33.3px orbit tiles; use authentic output examples or carefully composed artifact images when no photography exists.
- The ending is a graphic event: a rounded pale-gray footer carries compact links above a 52-column dot field, with 13.3px circles and 13.3px gaps forming a dark central silhouette. Reinterpret that silhouette as a product-relevant glyph.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Golden orange | `#fd7b03` | `--color-orange-end` | background | Shared bottom of every immersive chapter gradient. |
| Media fade orange | `#fc7303` | `--color-orange-fade` | background | Bottom overlay merging demonstration imagery into chapter backgrounds. |
| Hot orange | `#f94a00` | `--color-orange-start` | background | Top of the default immersive chapter gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text, action | Main page canvas, light buttons, image supports and reversed chapter text. |
| Near-black | `#020108` | `--color-ink` | text, background, action | Primary headings, navigation capsule, dark conversion pills and dot artwork. |
| Secondary ink | `#5d5c61` | `--color-muted` | text | Supporting descriptions; visible equivalent of 64% near-black over white. |
| Soft ink | `#818084` | `--color-soft-ink` | text | Secondary opening line and subdued navigation text; 50% near-black over white. |
| Control edge | `#ccccce` | `--color-edge` | border | Faint outlines on white upload and tag controls; 20% near-black over white. |
| Hairline gray | `#d7d7d6` | `--color-rule` | border | Editorial dividers and row rules; also used behind opening image tiles. |
| Pale gray | `#f7f7f7` | `--color-panel` | surface | Feature shells, logo tiles and the footer enclosure. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| immersive workflow chapters | Electric blue | `#3a54ff` | `--color-violet-blue` | background | Alternate chapter gradient top above a violet midpoint. |
| immersive workflow chapters | Deep red | `#9a0101` | `--color-red` | background | Alternate chapter gradient top for a warm final demonstration. |
| immersive workflow chapters | Sky blue | `#48a3d1` | `--color-blue` | background | Alternate chapter gradient top, blending into golden orange. |
| immersive workflow chapters | Violet midpoint | `#7a67c5` | `--color-violet` | background | 23% stop between electric blue and golden orange. |

## Typography

- **Sf Pro Display** — All meaningful marketing typography, labels and actions. Compact neo-grotesk with open counters, a tall x-height and tightly spaced regular display cuts. If unavailable, use **Inter**. Use 400 and 500; preserve compact line heights and negative tracking. Font stack: "Sf Pro Display", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Sf Pro Display | 400 | 99.8px | 1 | -0.03em | Major editorial statements, capability rows and chapter numerals. |
| hero | Sf Pro Display | 400 | 73.2px | 0.94 | -0.03em | Two-line bottom-aligned opening promise and major transition headings. |
| chapter-heading | Sf Pro Display | 400 | 53.2px | 1 | -0.03em | White two-line headings on immersive gradient stages. |
| feature-heading | Sf Pro Display | 500 | 43.3px | 1.05 | -0.0308em | Compact benefit headings inside pale-gray feature shells. |
| chapter-copy | Sf Pro Display | 500 | 20px | 1.15 | -0.009em | Short chapter descriptions with a white opening clause and half-opacity continuation. |
| question | Sf Pro Display | 500 | 16.6px | 1.25 | normal | FAQ question rows. |
| section-label | Sf Pro Display | 400 | 15px | 1.5 | normal | Editorial rail labels and short transition support copy. |
| action | Sf Pro Display | 400 | 14.1px | 1.2 | -0.02em | Pill actions and navigation labels. |
| body | Sf Pro Display | 400 | 13.3px | 1.25 | normal | Short feature descriptions, normally secondary ink. |
| tag | Sf Pro Display | 500 | 13.3px | 1.5 | -0.013em | Small output-category tags beside the opening orbit. |
| micro | Sf Pro Display | 500 | 8.3px | 1 | -0.02em, uppercase | Tiny opening date and scroll direction markings. |

**Notes:**

- Regular-weight major headings use -0.03em tracking; feature headings gain weight rather than growing to the major statement scale.
- Use deliberately short lines: two lines for the opening and editorial statements, two or three for feature benefits. Supporting copy remains dramatically smaller.
- The opening's second line is soft ink rather than a second accent color.
- Typography and rem-based geometry follow a fluid root size: calc((-0.009345794392523143rem + 0.9345794392523362vw) * 1). Desktop values above describe the 1440px composition.

## Layout

**Density:** Airy at section level, compact inside controls; large image stages and empty fields separate tightly set headlines and short copy.

### Spacing

| Value | Use |
| --- | --- |
| 6.7px | Narrow gaps between feature shells and page-edge inset for rounded enclosures. |
| 10px | Compact repeated-item gaps. |
| 13.3px | Feature heading-to-description gap and dot-grid spacing. |
| 20px | Navigation internal gap and chapter information-cell padding. |
| 26.6px | Default page gutter, editorial cell padding and FAQ row padding. |
| 66.5px | Large feature-shell inner padding. |
| 99.8px | Top inset of immersive chapter content. |
| 133.1px | Major white-space breathing interval and separation before FAQ and footer. |

### Containers and grids

- **page-stage**: max width 1440px · side padding 26.6px. Full-width desktop stage; header and editorial content share side gutters.
- **editorial-rail**: 2 columns · gap 0px. A narrow label rail takes about 26% of the page, separated by a vertical hairline from the 74% content field. At desktop the rail is 379px and the main field 1061px.
- **feature-pair**: 2 columns · gap 6.7px · side padding 6.7px. Two nearly touching pale-gray feature shells with media-led tops and copy toward the bottom.
- **demo-stage**: max width 1240px · side padding 0px. Centered demonstration artwork below the chapter header; typical artwork width is 1065px, with wider variants extending toward the edges.

## Corner radius

| Element | Radius |
| --- | --- |
| pills | 9999px (pill) |
| feature-shell | 39.9px |
| photographic-cards | 20px |
| orbit-tiles | 33.3px |
| tags | 6.7px |
| dots | 50% |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #020108`

**Observed:** Untextured white with thin gray editorial divisions.

**Transfer:** Keep most narrative and objection handling on this neutral field.

#### Feature shell · level 1

**Use:** Large media-led capability cards and footer enclosure.

**CSS:** `background: #f7f7f7; border-radius: 39.9px; box-shadow: none`

**Observed:** Almost edge-to-edge shells use a narrow white gap, not a raised-card shadow.

**Transfer:** Let imagery and curvature create hierarchy without extra borders or depth.

#### Orange chapter · level 0

**Use:** Default immersive demonstration backdrop.

**CSS:** `background-image: linear-gradient(#f94a00, #fd7b03); color: #ffffff`

**Observed:** A full 900px stage. Alternate tops are sky blue, electric blue with violet at 23%, and deep red; each resolves to golden orange.

**Transfer:** Keep the shared warm endpoint so distinct stages feel like one system.

#### Chapter media fade · level 2

**Use:** Merge the lower demonstration edge into the color stage.

**CSS:** `height: 133.1px; background-image: linear-gradient(rgba(252, 115, 3, 0), #fc7303)`

**Observed:** A foreground wash dissolves imagery instead of enclosing it in a hard rectangular frame.

**Transfer:** Use the fade only at the lower boundary; leave the central product detail legible.

## Components

### Navigation capsule

**Use:** Persistent compact menu and reading-progress cluster.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 20px; padding: 6.7px; height: 40px; width: 206px; background: #020108; color: #ffffff; border-radius: 9999px`

**Text style:** `action` — Sf Pro Display 400 · 14.1px/1.2 · tracking -0.02em

**Observed:** Centered within a fixed 92px header, independent of the left symbol and right account/action group. Menu has two thin horizontal lines; a ringed theme icon and translucent percentage badge follow.

**Transfer:** Preserve the small central instrument rather than replacing it with a full-width link bar.

### Primary button

**Use:** Conversion action on immersive colored stages.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; color: #020108; border-radius: 9999px; padding: 11.6px 20px; height: 40px`

**Text style:** `action` — Sf Pro Display 400 · 14.1px/1.2 · tracking -0.02em

**Observed:** A short text-only pill, centered between the chapter description and demonstration. The header and white capability overview use the inverse dark version.

**States:** Declared: hover color #ffffff and background-color #020108, outline 0px; active outline 0px. Transition 0.2s; focus-visible unknown.

### Output tag

**Use:** Small category labels in the opening's right-edge vertical ticker.

**CSS:** `background: #ffffff; border: 1px solid rgba(2, 1, 8, 0.2); border-radius: 6.7px; padding: 4.7px 13.3px 5.3px`

**Text style:** `tag` — Sf Pro Display 500 · 13.3px/1.5 · tracking -0.013em

**Observed:** Right-aligned tags stack with narrow gaps and fade at the top and bottom of the ticker.

**Transfer:** Use concise output or use-case nouns, not long feature descriptions.

### Feature card

**Use:** Large output proof and a compact benefit statement.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #f7f7f7; border-radius: 39.9px; padding: 66.5px`

**Text style:** `feature-heading` — Sf Pro Display 500 · 43.3px/1.05 · tracking -0.0308em

**Observed:** Small dot-prefixed category at the top, dominant photo or interface collage, then a bottom-left heading and short secondary description. A circular action sits at the lower right.

**Transfer:** Give each card a different visual proof composition while retaining shared shell geometry.

### Circular feature action

**Use:** Small independent action inside a feature shell.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 53px; height: 53px; border-radius: 9999px; background: #ffffff`

**Observed:** A black abstract four-part symbol is centered in the circle; the control is anchored to the card's lower-right corner.

**States:** Declared: hover background-color #ff6b02 and transform scale(0.9), outline 0px; active outline 0px. Focus-visible unknown.

**Transfer:** Use a simple compact product-relevant glyph with an accessible action label.

### FAQ row

**Use:** Objection handling under a monumental editorial heading.

**CSS:** `display: flex; flex-direction: column; border-bottom: 1px solid #d7d7d6; padding: 26.6px`

**Text style:** `question` — Sf Pro Display 500 · 16.6px/1.25

**Observed:** Question aligns left and a plain plus sign aligns far right; collapsed rows are about 75px tall and fill the wide column, without individual card backgrounds.

### Footer enclosure

**Use:** Closing navigation and signature dot artwork.

**CSS:** `display: flex; flex-direction: column; gap: 26.6px; padding: 26.6px; background: #f7f7f7; border-radius: 39.9px`

**Observed:** Large wordmark at upper left, two compact link columns at upper right, a broad open middle, fine legal lines near the bottom of the link area, then a full-width dot field. The outer page inset is 6.7px.

**Transfer:** End with the graphic enclosure rather than appending a separate oversized conversion banner.

## Imagery and graphics

### Orbit of outputs

**Use:** Signature central object in the opening.

**Observed:** Eight fashion photographs surround a small square upload target. Cropped portraits and full-body looks alternate, with muted clothing, white or natural backgrounds, rounded squares and gently rotated diamond-like tiles. The cluster occupies roughly the middle third of the page width and reaches from the upper-middle into the lower-middle of the opening.

**Transfer:** Use eight compelling outputs, artifacts or customer outcomes related to the new product. If photography is unavailable, compose clean miniatures of finished work; retain the orbit and central action tile.

**Build:** Arrange eight 119–160px rounded square masks around a 106px center tile, using a ring roughly 520px across. Alternate upright tiles with rotated masks; counter-rotate the image inside each mask. Apply 33.3px corners, object-fit: cover and no shadow. Center tile is white with a 1px 20%-ink outline, 20px corners and a gray attachment glyph.

### Editorial output photography

**Use:** Capability shells and workflow demonstration cards.

**Observed:** Fashion models, apparel, perfume and personal-care products appear as polished campaign outputs. Warm stone, moss, glass and leaves supply tactile backing; studio images use pale neutral backgrounds. Staggered rounded images mix close details with full objects and people, often extending beyond shell edges.

**Transfer:** Show the result of using the product rather than generic people at laptops. Preserve directional studio light, tangible materials, varied crop scales and restrained saturation.

### Product demonstration artwork

**Use:** Lower half of immersive chapters and the large first capability shell.

**Observed:** Interface artwork shows rows of portrait presets, image generations, side-by-side choices and a floating export toolbar. Rounded image cells sit inside dark or translucent pale frames. Media is considerably larger than accompanying text and partially dissolves into orange at the bottom.

**Transfer:** Use a real or simplified interface with recognizable outputs; minimum acceptable artwork is a clean row of three completed examples in a shared rounded frame. Keep internal interface colors subordinate to the marketing gradient.

### Dot-field finale

**Use:** Signature graphic across the lower footer.

**Observed:** A wide, regular field of pale near-black dots contains an irregular darker central silhouette; circles vary in opacity near its boundary. It is monochrome and occupies nearly half the footer's height.

**Transfer:** Create a new product-relevant glyph, abstract silhouette or symbol through dot opacity rather than drawing an unrelated illustration.

**Build:** Create an SVG or CSS grid of 52 columns with 13.3px circular dots and 13.3px gaps over #f7f7f7, approximately 14 rows tall. Use #020108 at opacity 0.15 for the base field. Sample a central silhouette mask into the grid; raise interior dots to opacity 1 and edge dots to intermediate values around 0.2–0.8. Keep the silhouette centered and about one quarter of the field width.

### Icons

**Observed:** Sparse icons: two hairline menu strokes, a 13px white rounded-stroke moon, a gray attachment mark, and compact black filled abstract symbols in 53px circular actions. FAQ uses an unadorned plus, not an enclosing circle.

**Transfer:** Favor small utility glyphs and abstract filled symbols; keep decorative iconography out of major headings.

## Section recipes

How recurring sections are built.

### First screen: Orbit opening

**Observed:** A 900px white stage layers a fixed header over an airy photographic orbit. The symbol stays top-left, Navigation capsule centered, account and dark Primary button top-right. Eight rounded photographic tiles encircle the upload square in the central field, leaving wide empty margins. The Hero headline is anchored bottom-left, about one third of the width, in two 73.2px lines: near-black first, soft ink second. Output tags form a narrow right-edge ticker. A tiny date sits bottom-center and a scroll cue bottom-right. Within the first 900px the full orbit, central upload prompt, headline and header action are visible; the major explanatory statement and feature shells start below the fold. There is no long support paragraph in this opening.

**Transfer:** Keep the media orbit and low headline for a new landing page, replacing the tile subjects with tangible outputs. For narrower product or informational pages, retain the compact capsule header and introduce the subject with the same tightly set editorial heading language rather than inventing a new hero style.

**Avoid:** Do not turn this into a centered headline-and-paragraph stack with a generic dashboard beneath it, or fill the central whitespace with badges.

**Text style:** `hero` — Sf Pro Display 400 · 73.2px/0.94 · tracking -0.03em

### Editorial heading rail

**Observed:** Canvas with a top hairline; a roughly 26% label rail has a right border and 26.6px padding. The wide column contains a 99.8px statement broken into two short lines. This framing repeats for the capability introduction and FAQ.

**Transfer:** Use one small topical label against a large outcome or objection statement; keep the wide column dominant.

**Text style:** `display` — Sf Pro Display 400 · 99.8px/1 · tracking -0.03em

### Media proof shells

**Observed:** Feature shell spans almost the full width with 6.7px edge inset; another version is a two-column pair with the same narrow gutter. One large layout juxtaposes a 233×353px source image with an oversized 1014×599px interface. Paired cards stage staggered photo collages or portrait video above Feature card copy and Circular feature action.

**Transfer:** Pair an input with a visibly richer result, or alternate finished outputs and motion proof. Preserve the large media-to-copy ratio.

**Text style:** `feature-heading` — Sf Pro Display 500 · 43.3px/1.05 · tracking -0.0308em

### Capability ladder and logo strip

**Observed:** An editorial rail carries a 99.8px sentence fragment and dark action. The wide column stacks oversized capability lines separated by hairlines; non-leading lines fade through gray. A horizontal strip of six 213×166px pale logo tiles follows, with 20px gaps and white fade masks at the edges.

**Transfer:** Complete a short sentence fragment with a set of concrete capabilities, then support it with verified ecosystem or customer marks. Do not fabricate partnerships.

**Text style:** `display` — Sf Pro Display 400 · 99.8px/1 · tracking -0.03em

### Immersive numbered chapter

**Observed:** Orange chapter and its color variants fill a 900px stage. A white 53.2px two-line heading sits upper-left, a 99.8px two-digit number upper-right. Below, fine 20%-white rules form two equal information cells, with tiny square bullets and short labels. A brief 20px description highlights its first clause in white and softens the continuation. Primary button sits on the center axis; a large demonstration begins about 40px below it and uses Chapter media fade at the bottom.

**Transfer:** Explain a meaningful product transition with a numbered stage, a concise verb-led heading and one tangible visual. The device must appear, but its count and location should follow the new story.

**Text style:** `chapter-heading` — Sf Pro Display 400 · 53.2px/1 · tracking -0.03em

### FAQ editorial grid

**Observed:** Editorial heading rail continues above a single-column list of FAQ rows in the wide field. The heading is 99.8px; question text drops to 16.6px. Border rules organize the list without boxed cards.

**Transfer:** Use real pre-purchase concerns and direct questions; preserve the dramatic heading-to-row scale change.

**Text style:** `question` — Sf Pro Display 500 · 16.6px/1.25

### Dot-field closing enclosure

**Observed:** After a 133.1px white interval, Footer enclosure fills almost the entire width. Brand lockup and compact link columns occupy the top, open space separates them from legal lines, and Dot-field finale anchors the bottom. The pale shell has 39.9px corners and no shadow.

**Transfer:** Close with navigation, identity and the required dot silhouette. Let the final artwork, not a new sales claim, provide the ending.

## Page flow

**Storyline:** Visual promise → outcome statement → media-rich proof → capability summary and trust → immersive explanation → objections → graphic identity close.

### Marketing landing page that makes creative software feel concrete through its outputs

1. **Promise** — Sparse white orbit opening with a low two-line headline and compact header action.
2. **Outcome framing** — Hairline editorial rail and monumental regular-weight statement.
3. **Product proof** — Large pale feature shell followed by paired output collages and short benefit copy.
4. **Capabilities and social proof** — Oversized ruled capability ladder and moving logo strip.
5. **Process explanation** — Short white transition into numbered gradient demonstrations, with repeated conversion pills.
6. **Objection handling** — Large editorial FAQ headline above fine ruled rows.
7. **Identity close** — Rounded pale footer with links, legal details and a large monochrome dot silhouette.

**Transfer:** Borrow the shifts in scale and material rather than the exact number of blocks. Demonstrate the new product's outputs early, reserve immersive color for explanation, and preserve the graphic ending.

## Writing

Confident, practical and lightly playful. It promises visible outcomes in plain language, with a concise editorial wit rather than technical exposition.

**Do not copy:** Do not reuse the Fourmula name, logo, product imagery, customer marks, company registration details, performance claims or product-specific preset counts. Source quotations below illustrate tone, not reusable claims.

- **Addressing the reader:** Talk directly to the reader through your and imperative verbs; use we sparingly when describing the service's work.
- **Rhythm:** Headlines are usually four to eight words, often split into two terse clauses. Supporting copy is one short sentence; buttons use two words. Sentence fragments and full stops give the large type a decisive cadence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Reader-owned asset, followed by a quick transformation. | 4–8 words | “Your catalog, instantly re-shot.” |
| Benefit headline | Desirable professional result, without the familiar burden. | 4–7 words | “Studio-quality, without the studio.” |
| Supporting line | Simple input, concrete output, avoided friction. | 15–25 words | “Upload one product and get all the angles, looks and moods you need for PDPs and campaigns—without booking a studio.” |
| Editorial objection heading | A knowing contrast, followed by a direct reassurance. | 6–10 words | “Not AI-gen answers. Real ones here.” |
| Primary action | Low-friction imperative with no ornament. | 2 words | “Get started” |

**Words and phrasing to use:** your; on-brand; ready; create; choose; without; in minutes; new scenes

**Avoid:** revolutionary ecosystem; unlock limitless potential; synergize; next-generation paradigm; exclamation-heavy urgency

**Rules:**

- Lead with the user's finished result rather than the underlying model or architecture.
- Make support copy concrete enough to explain what the reader supplies and what they receive.
- Use benefit language in display text and functional nouns in small tags.
- Keep the playful contrast in a few major lines, not every label.

## Do's and Don'ts

### Do

- Keep major display text at weight 400 with -0.03em tracking and compact line heights.
- Maintain 26.6px editorial gutters and the narrow 6.7px gap between large curved shells.
- Use a 40px pill for text actions; preserve the compact action scale against monumental headings.
- Give feature shells 39.9px corners and photography about 20px corners.
- Use 1px gray rules to define the editorial rail and FAQ rows.
- Include both a tangible output orbit and the monochrome dot-field graphic as recognizable devices.
- Resolve immersive gradients into the same golden-orange lower edge.
- Keep supporting feature text near 13.3px so media carries the proof.

### Don't

- Do not make the default site dark; black belongs mainly to type, controls and graphic dots.
- Do not distribute bright colors across ordinary feature cards; keep them concentrated in immersive stages.
- Do not add drop shadows to the pale shells; their separation comes from fill and whitespace.
- Do not turn text pills into tall rectangular buttons or introduce chunky borders.
- Do not use bold 700-weight display type to simulate emphasis; the hierarchy comes from scale and tight tracking.
- Do not replace photographic results with a uniform grid of stock business portraits.
- Do not give each FAQ row its own rounded card; retain shared thin rules.
- Do not add glow effects or glass navigation; the header capsule is solid near-black.

## Motion and responsive

### Motion

**Observed:**

- Declared repeating hero-row, columnanima and marquee animations use 24s linear infinite loops.
- Actions declare 0.2s transitions. Text pills invert from white to near-black on hover; circular feature actions scale to 0.9.
- Numbered chapters use pinned stage structures; exact scroll interpolation is not specified.

**Transfer:**

- Use the slow loop for orbit-adjacent category movement and the horizontal logo strip, keeping the headline stable.
- Use chapter-to-chapter color changes as the primary dramatic movement rather than animating every text block.

**Unknown:**

- The exact orbit trajectory, dot-field animation behavior, scroll interpolation and full keyboard focus treatment are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 767px, 768px, 991px, 992px, 1728px and 2560px.
- A viewport-dependent root font size scales rem-based type and geometry.

**Transfer:**

- On narrow screens, reduce the orbit as a unified object rather than allowing tiles to collide with the low headline.
- Stack paired feature shells and move the editorial label above its main column while retaining the hairline division.
- Reduce dot-field column count to fit while keeping circles circular and the silhouette recognizable.

**Unknown:**

- Mobile composition, actual breakpoint-specific dimensions and touch behavior are not established. Narrow-screen transfers are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
