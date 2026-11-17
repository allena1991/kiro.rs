# Auros — liquidity in luminous green

## Overview

A dark, fluid corporate style that makes technical infrastructure feel expansive rather than mechanical. Deep green and turquoise light support crisp grotesk typography, pale mint-to-lilac accents, abstract dot graphics and restrained institutional proof. The density alternates between spacious statements and information-rich panels; a soft pastel-light variant brings warmth to people-focused content.

### Essentials

- Compact promises sit inside an enormous atmosphere: a centered 60.8px/1 medium headline, 20px/1.3 support and a single 54px action occupy the upper middle of a full-width green light field, leaving the lower first screen to the glow.
- Words become spatial graphics between information blocks: 96px/1 gradient statements with -0.04em tracking and a viewport-scaled, 295.3px two-line word sculpture create pauses, not extra paragraphs.
- Actions are small luminous slabs, not pills: 6px corners, 20px 18px padding, 14px uppercase lettering with 0.12em tracking and a 12px northeast arrow; pale mint-to-lilac is the default conversion surface.
- Dark green owns the default page; color appears as turquoise atmospheric light, mint/lilac clipped type and isolated pastel proof surfaces rather than unrelated accent fills. Rounded panels use 16px corners and 40px outer gutters.
- Proof has a deliberate imbalance: a 600px-tall pastel statistic stands beside a 290px-tall wide dark statistic and two smaller dark cards, with 36px insets and 86.4px numerals anchored at the bottom.
- Abstract media behaves like illuminated matter: pale connected dots over a dark fine-dot field, plus an oversized luminous dotted sphere. Include a product-relevant abstract structure; a simple SVG node field with connected capsules is the minimum equivalent when no original media exists.
- The ending remains a designed scene: a two-line 60.8px promise faces a right-aligned 36px invitation and gradient action, followed by 160px breathing gaps before navigation and the final credit line, all over ambient light.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest panel and light ink | `#012624` | `--color-panel` | surface, text, action | Inset dark bands, text on pale surfaces and default light-button lettering. |
| Turquoise shadow | `#01534f` | `--color-teal-dark` | accent, border | Deep end of teal buttons; also 25% alpha separators on dark editorial rows. |
| Deep teal proof | `#003734` | `--color-stat` | surface | Dark statistic cards. |
| Active glass | `#02332f` | `--color-active-glass` | surface | Visible base-canvas result of 50% active green; media changes the apparent tint. |
| Dark glass | `#011d1c` | `--color-glass` | surface | Visible base-canvas result of 50% forest green; actual panel overlays illuminated media using rgba(1,38,36,0.5). |
| Deep green canvas | `#001413` | `--color-canvas` | background | Default page ground. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Living turquoise | `#02b9b0` | `--color-teal` | accent, action | Saturated light and teal-action transition. |
| Statement teal | `#00827c` | `--color-statement-start` | text, accent | Dark end of large gradient statements. |
| Luminous mint | `#cbfffc` | `--color-mint` | accent, action | Cool end of clipped type and button gradients. |
| Pastel lilac | `#fad1ff` | `--color-lilac` | accent, action | Warm end of pale actions and bright proof panels. |
| Lilac white numeral | `#fde9ff` | `--color-stat-ink` | text | Oversized numbers on dark green cards. |
| Ice white | `#edfffe` | `--color-ice` | text, accent | Dark-stat labels and pale gradient transitions. |
| Warm white | `#fffdfa` | `--color-cream` | accent | Neutral center of pastel gradients. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control glass | `#0d201f` | `--color-control-glass` | surface | White at 5% over the dark canvas; icon squares and navigation hover. |
| Charcoal | `#333333` | `--color-charcoal` | text | Editorial light-theme titles and FAQ section headings. |
| Reading gray | `#535757` | `--color-prose` | text | Long answers on white panels. |
| Muted gray | `#838b8b` | `--color-muted` | text | Secondary card paragraphs and light-theme support. |
| Silver green | `#bbc7c6` | `--color-silver` | text | Dark-theme body, attributions and footer navigation. |
| Light hairline | `#d9d9d9` | `--color-rule` | border | Accordion rules on white. |
| Toggle gray | `#eeeeee` | `--color-toggle` | surface | Square plus controls on light accordions. |
| Soft quote white | `#f2f2f2` | `--color-quote` | text | Testimonial body. |
| White | `#ffffff` | `--color-white` | text, surface | Primary dark-theme headings and white content panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| detailed product pages | Raised teal | `#004441` | `--color-feature` | surface | Capability cards on dark product sections. |
| light content panels | Green label start | `#012622` | `--color-light-label-start` | text | Start of gradient eyebrows on white. |
| light content panels | Green label light | `#06bfb6` | `--color-light-label-end` | text | End of gradient eyebrows on white. |
| leadership directories | Warm portrait ink | `#2b1e0a` | `--color-portrait-ink` | text | Portrait names. |
| people and recruiting pages | Light-theme gray | `#707777` | `--color-light-muted` | text | Light-theme hero support and footer navigation. |
| detailed product pages | Light gray card | `#f6f6f6` | `--color-card-light` | surface | Cards inside white product panels. |

## Typography

- **Matter** — All marketing typography, from display to navigation. Open, clean contemporary grotesk with round forms; regular prose and medium headlines rather than bold contrast. If unavailable, use **DM Sans**. Use 400 and 500; preserve tight headline tracking and compact line breaks. Font stack: "Matter", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| word-sculpture | Matter | 500 | 295.3px | 1 | -0.0118em | size clamp(86px, calc(86px + (400px - 86px) * ((100vw - 480px) / (1920px - 480px))), 400px) | Oversized two-line graphic language with horizontal overflow clipped. |
| statement | Matter | 500 | 96px | 1 | -0.04em | fixed | Centered gradient interlude statements. |
| stat | Matter | 500 | 86.4px | 1 | -0.0463em | size clamp(40px, 6vw, 96px) | Proof-card numbers and short numeric phrases. |
| heading | Matter | 500 | 60.8px | 1 | -0.0401em | fixed | Hero, section leads and closing promise. |
| card-title | Matter | 500 | 36px | 1 | normal | fixed | Exploration links and editorial row titles. |
| invitation | Matter | 400 | 36px | 1.3 | normal | fixed | Closing conversational invitation beside the promise. |
| quote | Matter | 400 | 24px | 1.3 | -0.0133em | fixed | Partner quotations in three columns. |
| small-heading | Matter | 500 | 24px | 1.2 | -0.03em | fixed | FAQ questions, numbered capability headings and portrait names. |
| body | Matter | 400 | 20px | 1.3 | -0.02em | fixed | Hero support, ordinary paragraphs and card explanations. |
| eyebrow | Matter | 500 | 20px | 1.4 | 0.24em, uppercase | fixed | Gradient section identifiers; 31px below the label before the heading. |
| stat-label | Matter | 500 | 20px | 1.4 | 0.08em, uppercase | fixed | Top-aligned proof labels. |
| attribution | Matter | 400 | 20px | 1.4 | 0.08em, uppercase | fixed | Names and roles beneath quotations. |
| footer-link | Matter | 400 | 20px | 1.3 | normal, uppercase | fixed | Footer navigation, distinct from tiny header lettering. |
| reading | Matter | 400 | 16px | 1.4 | -0.02em | fixed | Long FAQ answers and compact overview prose. |
| action | Matter | 400 | 14px | 1 | 0.12em, uppercase | fixed | Gradient button labels. |
| metadata | Matter | 400 | 13px | 1.5 | 0.055em, uppercase | fixed | Editorial dates and application labels. |
| nav | Matter | 400 | 12px | 1.4 | 0.12em, uppercase | fixed | Header links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| recruiting pages | culture-heading | Matter | 500 | 48px | 1.1 | -0.02em | fixed | Photo-and-text culture stories. |
| detailed product pages | feature-title | Matter | 500 | 36px | 1.1 | -0.04em | fixed | Capability grid card titles. |
| recruiting pages | job-title | Matter | 500 | 30px | 1 | -0.04em | fixed | Open-role list titles. |
| leadership directories | portrait-role | Matter | 400 | 16px | 1.3 | 0.08em, uppercase | fixed | Job titles under portrait names. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Medium weight does the work of bold. Main headings are compact at one line-height; prose opens to 1.3 and dense reading to 1.4.
- Labels expand as headlines contract: eyebrow tracking is 0.24em, action and navigation tracking 0.12em, and the 96px statement tracking is -0.04em.
- Preserve a small centered hero headline block rather than enlarging the headline to match the later word sculpture. Gradient typography is decorative emphasis, not the body-text treatment.

## Layout

**Density:** Airy at section scale, with compact text groups inside broad panels and long atmospheric pauses between them.

### Spacing

| Value | Use |
| --- | --- |
| 20px | Grid gutters, action icon gaps and portrait gaps. |
| 24px | Editorial content stack and invitation-to-action gap. |
| 31px | Eyebrow-to-heading separation. |
| 32px | Capability card insets and culture text stack. |
| 36px | Statistic card insets. |
| 40px | Outer page gutters, editorial row insets and footer bottom padding. |
| 48px | Headline-to-support and support-to-action spacing in the hero; recurring content stack. |
| 80px | Inner section padding for white overviews; culture media-to-copy gap. |
| 120px | Default large panel top and bottom spacing and distance between culture stories. |
| 140px | Footer top padding. |
| 160px | Hero top padding, expanded product chapters and footer row gaps. |

### Containers and grids

- **page-container**: max width 1440px · side padding 40px. Centered outer container creates 1360px inset bands at desktop.
- **inner-container**: max width 1360px · side padding 40px. A second inset yields a 1280px reading and card area inside broad bands.
- **hero-content**: max width 780px. Centered promise group. Support can use 585px for the compact default or 750px for longer secondary-page introductions.
- **proof-grid**: 3 columns · gap 20px. Tall left statistic spans two rows; right top spans two columns; two separate cards finish the lower right.
- **capability-grid** (only for detailed product pages): 2 columns · gap 20px. Equal-width product cards, on white or dark variants.
- **culture-row** (only for recruiting pages): max width 1000px · 2 columns · gap 80px. Alternating 420px text and 500px square photography.
- **portrait-grid** (only for leadership directories): 4 columns · gap 20px. 300px-wide portraits; flex-wrap and center an incomplete final row rather than stretching it.

## Corner radius

| Element | Radius |
| --- | --- |
| actions and icon controls | 6px |
| major panels and media | 16px |
| exploration overlay | 12px |
| active exploration row | 8px |

## Surfaces and depth

### Surfaces

#### Ambient canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #001413`

**Observed:** Deep green carries uneven turquoise pools of light rather than a flat black backdrop.

**Transfer:** Use the ambient light recipe behind the opening and closing, letting dark areas keep the copy legible.

#### Forest band · level 1

**Use:** Social proof and editorial groups.

**CSS:** `background: #012624; border-radius: 16px; padding: 120px 40px; box-shadow: none`

**Observed:** Broad inset bands contrast subtly with the page instead of floating above it.

**Transfer:** Group dense proof or reading without introducing shadows.

#### White band · level 1

**Use:** Overview, FAQ and people content.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 80px 40px; box-shadow: none`

**Observed:** A full-width inset panel gives a decisive tonal change; FAQ variants use 120px vertical padding.

**Transfer:** Use as a substantial content region, not a small white card sprinkled into every dark section.

#### Pastel proof · level 1

**Use:** One emphasized proof surface.

**CSS:** `background: radial-gradient(41288.3% 255.77% at -42.4% -22.13%, #fad1ff 0%, #fffdfa 44.72%, #edfffe 85.38%, #cbfffc 100%); border-radius: 16px; padding: 36px`

**Observed:** Lilac dominates the top, warming through near-white toward mint; dark numerals create the contrast.

**Transfer:** Reserve this materially brighter surface for the lead quantified outcome.

#### Exploration glass · level 2

**Use:** Text over abstract illuminated art.

**CSS:** `background: rgba(1,38,36,0.5); border-radius: 12px; padding: 40px 20px`

**Observed:** Tinted overlay takes half of a wide media band; the active row receives a separate green tint. There is no frosted blur treatment.

**Transfer:** Keep the backing translucent enough for the green scene to unify both halves.

#### Pastel atmosphere · level 0

**Only for:** recruiting pages

**Use:** Warm people-focused canvas.

**CSS:** `background: #ffffff`

**Observed:** Diffuse lilac clouds mingle with pale cyan and soft gray behind white panels and natural photography, continuing into the footer.

**Transfer:** Layer the pastel atmosphere graphic behind the whole page rather than changing each section to a different flat pastel.

## Components

### Fixed navigation

**Use:** Persistent desktop wayfinding.

**CSS:** `position: fixed; top: 0px; left: 0px; width: 100%; z-index: 20; padding: 12px 64px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `nav` — Matter 400 · 12px/1.4 · tracking 0.12em · uppercase

**Observed:** Brand mark at left, a compact horizontal navigation group in the middle and a pale gradient action at right. Header is 81px tall; dark pages have a green backing, light pages a pale translucent backing. A short dropdown label has a tiny chevron.

**Transfer:** Keep the header slender and let the illuminated stage remain dominant.

### Navigation link

**Use:** Header destinations.

**CSS:** `padding: 20px 16px; color: #ffffff; border-radius: 6px`

**Text style:** `nav` — Matter 400 · 12px/1.4 · tracking 0.12em · uppercase

**Observed:** Current-page treatment is a faint filled rectangle; recruiting uses black lettering on light backing.

**States:** Declared: hover background-color rgba(255,255,255,0.05), outline 0px; active outline 0px.

### Primary button

**Use:** Default conversion on dark scenes and the header.

**CSS:** `display: flex; align-items: center; gap: 20px; height: 54px; padding: 20px 18px; border-radius: 6px; color: #012624; background-image: linear-gradient(90deg, #fad1ff, #fffdfa, #edfffe, #cbfffc, #cbfffc, #edfffe, #fffdfa, #fad1ff); background-size: 200% 100%; background-position: 100% 0%; box-sizing: border-box`

**Text style:** `action` — Matter 400 · 14px/1 · tracking 0.12em · uppercase

**Observed:** Label followed by a thin northeast arrow; the header version has label only. Width follows content rather than filling the container.

**States:** Declared: hover outline 0px; active outline 0px. Background-position transition 600ms.

### Teal button

**Use:** Actions on white panels and secondary dark chapters.

**CSS:** `display: flex; align-items: center; gap: 20px; height: 54px; padding: 20px 18px; border-radius: 6px; color: #ffffff; background-image: linear-gradient(90deg, #cbfffc, #fad1ff, #02b9b0, #01534f); background-size: 280% 100%; background-position: 100% 0%; box-sizing: border-box`

**Text style:** `action` — Matter 400 · 14px/1 · tracking 0.12em · uppercase

**Observed:** Same label-arrow construction as Primary button; its resting appearance reads as turquoise fading to forest.

**States:** Declared: hover color #012624, outline 0px; active outline 0px. Background-position 600ms, color 200ms.

### Exploration row

**Use:** Linked capability summaries beside abstract art.

**CSS:** `display: flex; flex-direction: column; gap: 28px; padding: 32px 22px; border-radius: 8px; background: rgba(3,81,75,0.5)`

**Text style:** `card-title` — Matter 500 · 36px/1

**Observed:** Title and small arrow square share a top row; Body sits beneath. The shown fill identifies the active item, while neighboring items rest directly on Exploration glass.

**Transfer:** Use a small set of distinct entry points, each explained in a short paragraph.

### Statistic card

**Use:** Quantified proof.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 36px; border-radius: 16px; background: #003734; color: #fde9ff; height: 290px; box-sizing: border-box`

**Text style:** `stat` — Matter 500 · 86.4px/1 · tracking -0.0463em

**Observed:** Stat-label sits at top, Stat at bottom. The lead variant uses Pastel proof, dark lettering and twice the row height. Fine sparse dots give the cards a faint technical texture.

**Transfer:** Use genuine counts or short numeric outcomes; keep varied spans instead of equal tiles.

### Testimonial column

**Use:** Long-form social proof in Forest band.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 48px; padding: 48px 36px; border-radius: 16px; color: #f2f2f2`

**Text style:** `quote` — Matter 400 · 24px/1.3 · tracking -0.0133em

**Observed:** Three adjacent columns: quote above, uppercase attribution below, then a monochrome partner mark. Fine vertical green dividers separate columns; a horizontal strip of white partner marks follows the group.

**Transfer:** Keep quotes readable and logos monochrome rather than adding colorful badge cards.

### Editorial row

**Use:** Article or resource lists.

**CSS:** `border-bottom: 1px solid rgba(1,83,79,0.25); padding: 40px; display: flex; justify-content: space-between`

**Text style:** `card-title` — Matter 500 · 36px/1

**Observed:** A 250px by 160px landscape thumbnail is followed by a title, Body excerpt and Metadata date; the right edge holds a 50px translucent arrow square. The media-to-text gap is 97px and text stack gap is 24px.

**Transfer:** Keep this editorial and horizontal rather than reducing it to a standard three-card blog grid.

### FAQ row

**Use:** Objection handling inside White band.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 14px; padding: 30px 0px; border-top: 1px solid #d9d9d9; color: #012624`

**Text style:** `small-heading` — Matter 500 · 24px/1.2 · tracking -0.03em

**Observed:** Question takes the left side; a 50px square, 6px-radius light gray plus control sits on the right. Resting rows are collapsed. Reading text is contained below the question and is not permanently visible.

**Transfer:** Use real questions; keep a left-aligned section heading beside the question list.

### Footer navigation

**Use:** Low-density closing wayfinding.

**CSS:** `display: flex; flex-wrap: wrap; gap: 8px 16px; max-width: 717px; color: #bbc7c6`

**Text style:** `footer-link` — Matter 400 · 20px/1.3 · uppercase

**Observed:** Two lines of uppercase text links with slim 16px-tall vertical separators. Two outlined social marks align at the opposite edge; tiny credits occupy the bottom corners of the final row.

**States:** Declared: hover opacity 0.6, outline 0px; active outline 0px. Opacity transition 0.2s ease-in-out.

### Capability card

**Only for:** detailed product pages

**Use:** Scannable product advantages.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 24px; padding: 32px; border-radius: 16px; background: #004441; color: #ffffff`

**Text style:** `feature-title` — Matter 500 · 36px/1.1 · tracking -0.04em

**Observed:** Two columns with explanatory Body below each title. The light-panel variant uses light gray fill, forest title and muted gray prose; dark cards are shallow and concise.

**Transfer:** Use cards to express operational benefits, with no decorative icon required.

### Portrait card

**Only for:** leadership directories

**Use:** Introduce accountable people.

**CSS:** `width: 300px; overflow: clip`

**Text style:** `small-heading` — Matter 500 · 24px/1.2 · tracking -0.03em

**Observed:** A 300px by 380px portrait with rounded corners is followed after 24px by a warm-dark name and an uppercase Portrait-role line. Cards have no separate fill or border.

**Transfer:** Center the final incomplete row and keep image proportions consistent.

## Imagery and graphics

### Ambient light field

**Use:** Opening, interludes and closing; the default atmospheric signature.

**Observed:** A near-black green field contains enormous out-of-focus turquoise blooms, brighter toward the lower right of the opening. Their edges are soft and uneven, not hard radial discs. Most of the first screen is atmosphere, not an object or interface.

**Transfer:** Carry the same light around a new product promise. No literal product visual is needed in the opening, but the luminous field must remain.

**Build:** Use a #001413 base with two or three absolutely positioned radial-gradient ellipses: rgba(2,185,176,0.65) at center to rgba(2,185,176,0) at edge. Make them 600px–1000px wide, blur 100px–180px, place the brightest near the lower right and a weaker pool off the left edge. Layer a faint dark-green veil above; match the soft glow, exact stops are not essential.

### Connected matter

**Use:** Capability exploration and isolated overview media.

**Observed:** Pale mint circular nodes and soft linked capsules form a sparse geometric cluster, centered in the right half of a dark green band or a 520px square. A subtle regular dot lattice recedes behind it; lower-edge turquoise light makes the flat shapes luminous.

**Transfer:** Create a new geometric arrangement suggesting the product's relationships or movement. Preserve the light nodes, dark backing and generous empty perimeter rather than using generic stock technology imagery.

**Build:** In a square SVG draw a faint 24px-spaced dot grid using 1px circles at rgba(203,255,252,0.12). Place 12–20 mint nodes on a looser 72px grid; join selected diagonally adjacent nodes with thick rounded paths or smooth capsule silhouettes. Add tiny dark center dots. Back with forest green and a blurred turquoise ellipse near the bottom. Keep the foreground cluster within the middle two thirds.

### Luminous dotted sphere

**Use:** Wide scale, reach or ecosystem proof band.

**Observed:** An oversized pale mint globe is clipped by the right edge of a 1360px by 602px rounded band. Dotted continents cover the surface; bright bloom on its left limb spills into the dark teal copy half, and a pale haze gathers at the lower edge.

**Transfer:** Retain an oversized luminous dot-surface object to express reach or connected scale. For non-global products, use a dotted sphere, network volume or product-relevant silhouette rather than a literal map.

**Build:** Create an SVG circular clipping region roughly 800px across, pushed partly beyond the right edge. Fill with ice-to-mint shading, overlay a repeated dot pattern masked to a simple network or land-like silhouette in rgba(1,83,79,0.45), and add a blurred mint ellipse along the left limb. A radial mint glow and a pale lower-edge gradient integrate it with the canvas.

### Fine proof particles

**Use:** Statistic cards.

**Observed:** Very faint tiny specks sit across green and pastel proof surfaces; typography remains the dominant content.

**Transfer:** Keep the texture below the contrast of all labels and numerals.

**Build:** Overlay an SVG pattern of irregularly spaced 1px dots in rgba(187,199,198,0.12), with no dense noise or prominent grid. Clip to the 16px card corners.

### Editorial covers

**Use:** Resource-list thumbnails.

**Observed:** Small landscape covers are dark green with a restrained brand mark, fine line or wave detail, short pale headline and lower turquoise illumination.

**Transfer:** Design original covers in the same green-and-light palette; keep detail subordinate at 250px by 160px.

### Pastel light field

**Only for:** recruiting pages

**Use:** Background across the introduction, culture stories and closing.

**Observed:** Soft lilac pooling at the lower left blends with gray, cream and pale cyan; natural light photography sits above it without elaborate framing.

**Transfer:** Use the softer atmosphere only for a human-focused narrative, preserving white content panels and forest text.

**Build:** On white, layer broad radial gradients of rgba(250,209,255,0.55) at lower left and rgba(203,255,252,0.25) toward the upper right. Blur the layers by 120px and overlap broad translucent gray veils for depth. Avoid distinct rainbow bands.

### Culture photography

**Only for:** recruiting pages

**Use:** Alternating editorial stories about working life.

**Observed:** 500px square photographs show candid work and social settings, with natural daylight, modest saturation and visible surroundings. Rounded 16px edges; text is outside the image.

**Transfer:** Commission candid scenes of people doing real work or interacting, not isolated cutouts or staged stock handshakes.

### Leadership portraits

**Only for:** leadership directories

**Use:** Four-across people grid.

**Observed:** Consistent waist-up crops on light gray, off-white or muted cyan backdrops. Subjects wear natural business-casual clothing; skin tones stay realistic and the backgrounds remain low-contrast.

**Transfer:** Use consistent lighting and crop across new portraits; do not force every subject onto an identical artificial green background.

### Icons

**Observed:** Thin northeast arrows are 12px in gradient actions and 16px in row controls. Dropdown chevrons are 9px. FAQ plus signs are simple dark 16px glyphs centered in 50px controls. Social marks are outlined circles around recognizable glyphs, about 40px across.

**Transfer:** Choose spare line symbols and keep arrows as the main navigation cue; avoid a multicolor illustrative icon family.

## Section recipes

How recurring sections are built.

### First screen: Luminous promise opening

**Observed:** Fixed navigation sits above a full-width Ambient canvas and Ambient light field. A centered 780px content group begins with an Eyebrow, then a compact two-line Heading in white, followed by Body support limited to 585px and Primary button. The 160px top inset under the header gives the label breathing room; 31px separates label and heading, then 48px separates headline, support and action. At 1440px wide the actual headline occupies only about a quarter of the width, not the whole content container. Within the first 900px the header, label, headline, support, action and bright lower-right glow are visible; no separate product object competes with the promise. The full luminous stage continues below the fold before the enormous word sculpture begins.

**Transfer:** Use an outcome-led two-line promise with an original label and action. Recreate the light field with layered gradients when no bespoke media exists. Detailed product and directory pages use a shorter centered introduction without an in-hero action, allowing the next inset content band to enter the first screen. Recruiting uses Pastel atmosphere and forest text.

**Avoid:** Do not replace the opening with a giant UI dashboard, oversized full-width headline, split-screen photo or a card enclosing the centered promise.

**Text style:** `heading` — Matter 500 · 60.8px/1 · tracking -0.0401em

### Word sculpture and statement pauses

**Observed:** The Word-sculpture spans two tightly stacked lines at 295.3px, with mint-to-lilac clipped fill at 0.75 opacity and horizontal overflow hidden. Separate Statement sections are 675px tall, center two or three 96px lines in a 1200px maximum width and use a teal-to-mint clipped gradient.

**Transfer:** Include graphic language as a signature device, using short product-relevant verbs or outcomes. Choose placement and frequency to fit the story rather than repeating a fixed sequence.

**Text style:** `statement` — Matter 500 · 96px/1 · tracking -0.04em

### Section introduction

**Observed:** Gradient Eyebrow, Heading and Body form a centered stack. Label-to-heading gap is 31px; support follows after 48px. Section support is narrower than the outer panel and remains muted silver on dark. White-panel introductions can put the heading at left and prose/actions at right.

**Transfer:** Use the label to name the chapter and the heading to make its point. Keep explanations to one concise paragraph.

**Text style:** `heading` — Matter 500 · 60.8px/1 · tracking -0.0401em

### Exploration stage

**Observed:** A rounded full-width media band contains Exploration glass on the left and Connected matter on the right. Three Exploration rows share the left half; a Teal button anchors the top-right media area.

**Transfer:** Pair multiple routes into the offering with one coherent abstract illustration, not a separate unrelated image for every route.

### Asymmetric proof

**Observed:** A centered introduction leads into Proof-grid with Statistic cards and one Pastel proof surface. The left card is 600px tall; right-side cards are 290px high with 20px gutters. Labels stay at the top while large values align toward the bottom.

**Transfer:** Use the tallest bright card for the leading measurable outcome, and organize supporting counts by significance rather than string length.

**Text style:** `stat` — Matter 500 · 86.4px/1 · tracking -0.0463em

### Reach scene

**Observed:** Luminous dotted sphere fills and exceeds the right half of a 602px-tall rounded band. A left-aligned Eyebrow, Heading, Body and Teal button occupy the dark half, with broad inset space and luminous lower-edge haze.

**Transfer:** Use a product-relevant scale or ecosystem claim and preserve the oversized cropped object as an atmospheric counterweight to the text.

### Partner proof band

**Observed:** Forest band holds a centered section heading, three Testimonial columns and a continuous-looking strip of monochrome partner marks beneath. Quotes are much smaller than section headings but larger than body copy.

**Transfer:** Combine a few specific voices with compact visual proof; if partner marks are unavailable, use verified organization names in the same monochrome strip.

**Text style:** `quote` — Matter 400 · 24px/1.3 · tracking -0.0133em

### Editorial list band

**Observed:** Forest band begins with a centered Eyebrow, Heading and support. Editorial rows are separated by faint rules; a centered Teal button follows the list.

**Transfer:** Use for research, case studies or resources where a title and paragraph carry more weight than thumbnail art.

### FAQ split panel

**Observed:** White band puts Eyebrow and Heading on the left, FAQ rows in a roughly 726px-wide column on the right with a 100px composition gap. A centered Teal button sits below the list. Visible questions are collapsed; answers open beneath their labels.

**Transfer:** Answer practical objections in plain language without making the panel look like a dense documentation table.

**Text style:** `small-heading` — Matter 500 · 24px/1.2 · tracking -0.03em

### Ambient closing

**Observed:** The open footer is 699px tall with 140px top and 40px bottom padding. A left-aligned two-line Heading faces a right-aligned Invitation and Primary button, separated internally by 24px. After 160px comes Footer navigation with socials at right; another 160px separates the final tiny credits. Ambient light field continues behind everything. The people-focused light variant retains this composition with forest text, gray links and Teal button over Pastel atmosphere.

**Transfer:** Restate the product's central promise and invite a human next step. Keep the closing as a full scene rather than appending a small generic copyright bar.

**Text style:** `heading` — Matter 500 · 60.8px/1 · tracking -0.0401em

### Numbered capabilities

**Only for:** detailed product pages

**Observed:** A centered Heading and support introduce four equal vertical text columns on Ambient canvas. Each starts with a 36px number, then a 24px Small-heading and Body description separated by 24px. Thin forest rules divide the columns.

**Transfer:** Use for a small set of substantial solution categories; let their paragraphs vary naturally rather than boxing every column.

### Culture story

**Only for:** recruiting pages

**Observed:** Pastel atmosphere supports alternating Culture-row blocks, each a 500px square photo opposite a 420px text group. Culture-heading and Body are separated by 32px; successive stories are separated by 120px. A later Forest band holds a 1000px-wide open-role list with 30px titles, teal rules and application arrows.

**Transfer:** Tell human stories through real situations, then offer a direct route to relevant opportunities.

### Leadership directory

**Only for:** leadership directories

**Observed:** A compact dark centered introduction is followed by White band containing Portrait cards in four columns, then a centered incomplete row. A Teal button ends the panel before the ambient closing.

**Transfer:** Use a consistent people grid and restrained caption system, with no biographies added into the card face.

## Page flow

**Storyline:** Outcome promise → explanatory chapters with graphic pauses → measurable and human proof → deeper reading or practical objections → atmospheric invitation.

### Broad brand and offering introduction

1. **Promise** — Centered luminous promise and action followed by oversized graphic language.
2. **Orientation** — Short gradient statement and an exploration stage with linked offerings.
3. **Quantified proof** — Asymmetric statistic grid and a large typographic pause.
4. **Scale** — Dotted reach scene with a concise operational claim.
5. **Social proof** — Partner quotations and monochrome logo strip.
6. **Deeper engagement** — Editorial rows bracketed by gradient statements.
7. **Closing call** — Ambient promise, invitation, navigation and credits.

**Transfer:** Retain the alternation of information and breathing space; select chapters appropriate to the new offering.

### Recruiting and culture storytelling

1. **Promise** — Centered forest headline on pastel atmosphere.
2. **Value proposition** — White split introduction with actions and three compact principle statements.
3. **Human proof** — Alternating candid photo stories.
4. **Conversion** — Dark inset opportunity list with application controls.
5. **Objection handling** — White split FAQ panel.
6. **Closing call** — Light atmospheric closing with the same large promise and invitation composition.

**Transfer:** Keep people imagery and pastel atmosphere scoped to a human-focused page rather than changing the default marketing theme.

### Detailed service or product explanation

1. **Promise** — Compact dark centered introduction.
2. **Overview** — White split panel with explanatory copy and connected-node art.
3. **Quantified proof** — Pastel-and-green statistic grid.
4. **Trust** — White panel containing two-column light cards.
5. **Capabilities** — Numbered solution columns followed by a dark two-column feature grid.
6. **Depth** — A further numbered capability chapter.
7. **Objection handling** — White split FAQ panel and action.
8. **Closing call** — Dark atmospheric footer scene.

**Transfer:** Use light panels for analytical explanation and dark open chapters for confident benefit statements; avoid duplicating a capability chapter unless it adds distinct content.

### Introduce the people responsible for the offering

1. **Context** — Compact dark introduction with one short support paragraph.
2. **Human proof** — Large white rounded panel, consistent portrait cards and a centered action.
3. **Closing call** — Dark atmospheric footer scene.

**Transfer:** Let the directory remain short and image-led; borrow the broader identity without inventing extra marketing chapters.

## Writing

Institutional confidence with a future-facing, active vocabulary. Technical competence is expressed through operational specifics, while invitations remain direct and human.

**Do not copy:** Do not reuse Auros names, wordmarks, proprietary graphic arrangements, product names, partner logos, quotations, financial volumes, team biographies or performance claims. The example phrases illustrate tone; write original copy for the new product.

- **Addressing the reader:** Headlines often state outcomes without a pronoun. Use 'we' for organizational agency and 'you' or 'your' when discussing practical needs; name the product in explanatory chapters.
- **Rhythm:** Short compressed promises alternate with explanatory single-paragraph support. Benefit headings are noun phrases; actions are brief verbs. Longer paragraphs belong to solution details and FAQ answers, not the opening.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | An active transformation, or a service category followed by a reader-relevant qualifier. | 4–10 words | “Making Digital Markets Liquid”<br>“Institutional-grade OTC trading, tailored to your needs” |
| Support | Explain what is being enabled with one domain-specific operational phrase. | One sentence; approximately 10–30 words for a compact introduction | “Building next-gen liquidity infrastructure for the crypto economy.” |
| Section heading | Straightforward chapter title; let data or specific benefits establish credibility. | 3–8 words | “Insights and Perspectives”<br>“Work where excellence meets impact” |
| Primary action | Verb plus desired next step, with a human route available. | 2–4 words | “Unlock Liquidity”<br>“Get In Touch”<br>“View Open Roles” |
| Benefit | Concrete operational advantage, not abstract praise. | 2–5 words | “Best-venue pricing”<br>“Transparency & Accountability” |
| FAQ | A real question about process, fit or practical constraints. | 6–15 words | “What is the interview process like at [Brand]?” |

**Words and phrasing to use:** build; connect; enable; tailored; global; infrastructure; access; transparency; ownership; operational clarity

**Avoid:** moonshot hype; playful slang; revolutionary without explanation; emoji-led claims; exclamation-heavy calls; vague superlatives

**Rules:**

- Make an outcome concrete through a mechanism, service or measurable result.
- Use tightly edited headline lines; reserve technical detail for support and capability paragraphs.
- Pair institutional language with a simple invitation to speak to a team.
- Use capitals as a visual label treatment, not as a way to shout in prose.

## Do's and Don'ts

### Do

- Keep headline weight at 500 and body weight at 400; let size and line breaks create emphasis.
- Use 40px outer gutters and 16px corners for major inset bands.
- Keep default actions 54px high with 6px corners and a thin northeast arrow.
- Preserve 48px hero stack gaps so the compact centered copy feels deliberate.
- Anchor statistic values at the bottom of 36px-inset cards.
- Make pale proof surfaces exceptional against the dark green ground.
- Carry the atmosphere through the full closing scene, including navigation.
- Center incomplete portrait rows at 300px card width on directory pages.

### Don't

- Do not turn the 6px gradient buttons into fully rounded pills.
- Do not replace Matter's medium grotesk hierarchy with heavy 700-weight display typography.
- Do not use flat pure black as the default canvas; the ground is green #001413.
- Do not paint every feature card lilac; the bright proof surface depends on dark neighbors.
- Do not add drop shadows to separate bands; contrast, spacing and corners provide separation.
- Do not make uppercase eyebrow tracking as tight as the headlines; keep its 0.24em spread.
- Do not use the 12px navigation recipe for footer destinations; those are 20px.
- Do not replace natural people photography with neon duotone portraits or small circular avatars.

## Motion and responsive

### Motion

**Observed:**

- Gradient buttons declare background-position transitions of 600ms; teal versions also declare color 200ms.
- Header background and link opacity transitions are 0.2s ease-in-out.
- Accordion grid-template-rows transitions are declared at 0.6s cubic-bezier(0.625, 0.05, 0, 1).
- Oversized graphic text has a horizontal transform and its enclosing section clips overflow.

**Transfer:**

- Use gradient movement rather than scaling the conversion buttons.
- Keep the large typographic device spatial and clipped; let its words remain legible as graphic language.

**Unknown:**

- Timing and choreography of the ambient graphics and scroll-driven type are not specified.
- Exact hover gradient target positions and focus-visible appearance are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 767px, 768px, 991px, 992px, 1180px, 1280px and 1380px.
- Statistic and word-sculpture recipes have explicit fluid clamp formulas.

**Transfer:**

- As design guidance, stack the asymmetric proof cards on narrow screens while retaining one brighter lead card and bottom-aligned values.
- As design guidance, stack split text/media panels and footer invitation groups without losing the luminous full-width backdrop.
- Keep the word sculpture clipped and fluid rather than shrinking all typography by the same factor.

**Unknown:**

- Mobile navigation construction, exact gutter changes and column-collapse breakpoints are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
