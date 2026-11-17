# MasterClass — ambition on screen

## Overview

A cinematic, people-led style with the confidence of a premium entertainment service and the invitation of a personal mentor. Black space, white grotesk typography, compressed poster headlines and small raspberry actions frame richly lit photography. Warm parchment, elegant condensed serifs and electric lime form a distinct premium-offering variant. Dense browsing and practical forms sit between spacious photographic set pieces.

### Essentials

- Ambition reads like a film poster: the opening headline is condensed sans, uppercase, 80px/0.85 at weight 500 with 0.01em tracking; ordinary section headlines switch to a wider 48px/1.25 grotesk at weight 600.
- The opening pairs a personal invitation with a living portrait wall: a 500px text-and-choice column shares a 1200px content area with two staggered columns of 285×356px portraits, fading into black at their ends. Use people at work or tangible product results when personalities are unavailable.
- Actions are compact rectangles, not capsules: 44px height, 8px corners and 12px 24px padding; raspberry marks conversion while inset gray outlines mark preview and secondary actions.
- Black is the default stage across most of the page; color comes primarily from photography. Raspberry #e32652 stays in small actions and marks; lime #dcff00 is reserved for a premium offer, not a general background theme.
- Media is the proof, not decoration: combine tall 240×427px poster tiles with at least one wide cinematic showcase, using dark bottom or side gradients to carry short white captions. Without original film, use carefully art-directed stills with the same portrait and widescreen framing.
- A premium interlude changes register without losing the stage: a 16px-rounded split panel pairs olive-black #211d0d, a 64px/1.1 condensed serif promise and lime action with a warmly lit tangible outcome image.
- Human testimony has physical overlap: a slate 612×330px quote panel sits in front of a 336×448px environmental portrait; 20px/1.6 quotes and restrained attribution make the proof feel personal rather than statistical.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Raspberry | `#e32652` | `--color-action` | action, accent | Default conversion buttons, small divider marks and numbered capability badges. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric lime | `#dcff00` | `--color-premium` | action, accent | Premium-offering actions and highlights only; the warm premium theme also uses it for its signup panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-canvas` | background | Default page canvas and media fades. |
| Near black | `#0d0d0e` | `--color-utility` | background, surface, border | Upper navigation strip and category chip surfaces. |
| Blue black | `#191c21` | `--color-input` | surface | Email inputs and poster-caption fade endpoints. |
| Olive black | `#211d0d` | `--color-olive` | surface, text | Premium split-panel backing and text on its lime action. |
| Charcoal | `#222326` | `--color-panel` | surface | Choice rows, FAQ panels and business promotion backing. |
| Quote slate | `#272c33` | `--color-slate` | surface, border | Overlapping testimonial card and inset input edges. |
| Subtle divider | `#303136` | `--color-rule` | border, surface | Footer separator and hovered secondary controls. |
| Control edge | `#43454c` | `--color-edge` | border, surface | Inset secondary-action outlines and solid neutral actions. |
| Cool gray | `#9ea0a9` | `--color-muted` | text | Inactive category labels and secondary information. |
| Soft white | `#d4d5d9` | `--color-support` | text | Opening support line. |
| Question white | `#f4f4f5` | `--color-faq-text` | text | Question labels on dark accordion rows. |
| Ivory white | `#fffef2` | `--color-cream-text` | text | Premium serif headlines and support. |
| Screen white | `#ffffff` | `--color-text` | text | Primary headlines, body text and dark-theme actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| premium-offering landing pages | Parchment | `#e4d5c3` | `--color-parchment` | background | Warm premium-theme opening and catalog canvas. |
| premium-offering landing pages | Taupe | `#bfb0a1` | `--color-warm-light` | text | Secondary copy over warm night. |
| premium-offering landing pages | Warm gray | `#726855` | `--color-warm-muted` | text, border | Muted support, dotted benefit dividers and dashed question rules. |
| premium-offering landing pages | Warm night | `#0b0a06` | `--color-warm-dark` | background | Lower warm-theme canvas following the proof-image gradient. |
| premium-offering landing pages | Warm ink | `#16140c` | `--color-warm-ink` | text, background, action | Warm-theme primary text, dark buttons and footer. |
| premium-offering landing pages | Brown ink | `#52463a` | `--color-warm-copy` | text | Body copy over parchment and cream. |
| premium-offering landing pages | Cream paper | `#fefaf2` | `--color-paper` | surface | Warm catalog cards and promotional text panels. |

## Typography

- **Sohne** — Body, navigation, buttons and ordinary section headings. Direct contemporary grotesk with open counters and a substantial semibold. If unavailable, use **Inter**. Use 400 and 600; preserve the slightly positive tracking. Font stack: "Sohne", "Inter", Helvetica, Arial, sans-serif.
- **Sohne Schmal** — Poster-like opening and business-promotion headlines. Very narrow upright sans with compressed line spacing and emphatic capitals. If unavailable, use **Barlow Condensed**. Use 600 if needed to match the dark narrow strokes of the 500 display cut. Font stack: "Sohne Schmal", "Barlow Condensed", Impact, Helvetica, Arial, sans-serif.
- **Ivar Display Condensed** — Premium-offer editorial headlines. Tall high-contrast condensed serif, delicate joins and expressive curved forms. If unavailable, use **Instrument Serif**. Use 400; retain narrow text measures and the 1.1 line height. Font stack: "Ivar Display Condensed", "Instrument Serif", Georgia, serif.
- **Sohne Mono** (only for premium-offering landing pages) — Uppercase benefit and availability labels. Widely tracked small monospace gives editorial sections a credential-like marking. If unavailable, use **IBM Plex Mono**. Font stack: "Sohne Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Sohne Schmal | 500 | 80px | 0.85 | 0.01em, uppercase | Two-line opening promise in a narrow text column. |
| premium-heading | Ivar Display Condensed | 400 | 64px | 1.1 | 0.005em | Premium split-panel headline. |
| business-display | Sohne Schmal | 500 | 64px | 0.9 | -0.01em, uppercase | Compact business-promotion headline. |
| heading-lg | Sohne | 600 | 48px | 1.25 | 0.03em | Centered discovery and conversion section leads. |
| heading | Sohne | 600 | 32px | 1.25 | 0.03em | Benefits, proof, FAQ and content-rail section leads. |
| premium-support | Sohne | 400 | 22px | 1.6 | 0.012em | Centered premium-panel support. |
| prompt | Sohne | 600 | 20px | 1.25 | 0.03em | Opening question and newsletter heading. |
| quote | Sohne | 400 | 20px | 1.6 | 0.01em | Featured overlapping testimonial. |
| body | Sohne | 400 | 16px | 1.5 | 0.02em | Benefits, short descriptions and navigation links. |
| body-strong | Sohne | 600 | 16px | 1.5 | 0.02em | Opening support, FAQ labels and group titles. |
| action | Sohne | 600 | 16px | 1.25 | 0.01em | Button and category-chip text. |
| choice | Sohne | 400 | 16px | 1.5 | 0.01em | Selectable intent rows. |
| small | Sohne | 400 | 14px | 1.5 | 0.02em | Footer links and concise product summaries. |
| utility-label | Sohne | 600 | 12px | 1.45 | 0.02em | Compact upper navigation strip. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| premium-offering landing pages | editorial-statement | Ivar Display Condensed | 400 | 96px | 1.1 | normal | Two-line centered statement introducing the dark editorial chapter. |
| premium-offering landing pages | editorial-display | Ivar Display Condensed | 400 | 74px | 1.1 | 0.0068em | Warm-theme hero and major section promises. |
| premium-offering landing pages | editorial-heading | Ivar Display Condensed | 400 | 64px | 1.1 | 0.0063em | Offer panel and FAQ headings. |
| premium-offering landing pages | editorial-tab | Ivar Display Condensed | 400 | 48px | 1.1 | 0.0133em | Feature-tab titles. |
| premium-offering landing pages | editorial-card-title | Sohne | 500 | 26px | 1.35 | 0.0173em | Course-card and FAQ titles; use the medium Kraftig cut. |
| premium-offering landing pages | editorial-body-lg | Sohne | 400 | 22px | 1.6 | 0.009em | Warm-theme hero support and expanded answers. |
| individual product-detail pages | compact-quote | Sohne | 400 | 18px | 1.5 | 0.018em | Centered quote in three equal testimonial cards. |
| premium-offering landing pages | editorial-body | Sohne | 400 | 16px | 1.45 | 0.0094em | Warm-theme feature and panel descriptions. |
| premium-offering landing pages | editorial-eyebrow | Sohne Mono | 500 | 12px | 1.65 | 0.133em, uppercase | Availability, benefit and offer labels. |

**Notes:**

- Positive tracking is characteristic in the ordinary grotesk headings: 0.03em at both 32px and 48px. Do not replace it with fashionable tightly tracked display text.
- Keep compressed uppercase display and regular mixed-case section headings as different voices. Serif type signals a premium editorial offer rather than replacing the default sans hierarchy.
- Sohne Kraftig is treated as the medium cut of Sohne, not a separate visual family.

## Layout

**Density:** Airy section staging with compact controls: photographic chapters breathe while browsing rows and forms remain closely packed.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Separation between stacked intent rows. |
| 8px | Heading-to-support gap and wrapping category-chip gap. |
| 12px | Button vertical padding and short icon gaps. |
| 16px | FAQ row separation, choice-group margins and small content gaps. |
| 24px | Quote-to-attribution gap and descriptive card spacing. |
| 32px | Container side padding and premium-panel action separation. |
| 48px | Quote vertical padding and FAQ category separation. |
| 64px | Default major-section separation and premium-panel vertical padding. |
| 96px | Opening headline inset below navigation and featured quote horizontal padding. |
| 160px | Warm editorial chapter separation and statement padding. |

### Containers and grids

- **container**: max width 1264px · side padding 32px. Centered shell; its inner content is 1200px wide at desktop. Most sections align to this common edge.
- **opening split**: 2 columns · gap 0px. Equal 600px desktop halves; the text occupies a narrower 500px measure while the right half contains staggered media.
- **capability grid**: 4 columns · gap 16px. Four 288px-wide image cards across the content width on individual product pages.
- **benefit triptych**: 3 columns · gap 8px. Three almost touching photographic benefit panels; headings and outcome lines belong inside each image.
- **FAQ column**: max width 795px. Default centered question stack. Keep heading centered over a narrower reading column.
- **warm proof pair** (only for premium-offering landing pages): 2 columns · gap 32px. Equal 584px square images with titles and descriptions below.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 8px |
|  | inputs and FAQ | 4px |
|  | general panels | 12px |
|  | premium split and editorial cards | 16px |
|  | status badge | 20px |
|  | round controls | 50% |
| premium-offering landing pages | editorial offer panel | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| secondary control inset | `0px 0px 0px 2px #43454c inset` | Secondary buttons and circular media controls; an edge, not elevation. |
| input inset | `0px 0px 0px 1px #272c33 inset` | Email fields on the black canvas. |

### Surfaces

#### Black stage · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Long continuous black fields connect photographic chapters without alternating pale bands.

**Transfer:** Let layout and photography create chapter changes rather than adding background colors.

#### Charcoal panel · level 1

**Use:** Utility content, business backing and compact testimonials.

**CSS:** `background: #222326; border-radius: 12px`

**Observed:** Flat charcoal distinguishes content without drop shadows. FAQ uses 4px corners instead.

**Transfer:** Reserve this lift for bounded functional or proof content.

#### Premium split backing · level 1

**Use:** Editorial promotional interlude.

**CSS:** `background: #211d0d; color: #fffef2; padding: 64px 48px`

**Observed:** A text half meets a full-height photograph inside a shared 16px rounded wrapper.

**Transfer:** Use for a distinct premium offer or tangible outcome.

#### Poster fade · level 1

**Use:** Caption legibility over tall imagery.

**CSS:** `background: linear-gradient(0deg, #191c21 0px, rgba(25, 28, 33, 0.5) 50%, rgba(25, 28, 33, 0) 90%)`

**Observed:** The bottom becomes an opaque caption shelf while the face remains unobscured.

**Transfer:** Apply as a separate overlay, not a dimming filter over the entire image.

#### Parchment chapter · level 0

**Only for:** premium-offering landing pages

**Use:** Warm editorial opening and catalog.

**CSS:** `background: #e4d5c3; color: #16140c`

**Observed:** Cream cards sit on warm beige; later the canvas transitions to warm night.

**Transfer:** Use this complete warm theme for a premium destination, not random alternating sections on a default black page.

#### Paper card · level 1

**Only for:** premium-offering landing pages

**Use:** Warm catalog and offer panels.

**CSS:** `background: #fefaf2; border-radius: 16px; overflow: hidden`

**Observed:** No visible elevation; a colored image cap and dotted separators supply structure.

**Transfer:** Keep print-like hierarchy and restrained edges.

#### Warm night chapter · level 0

**Only for:** premium-offering landing pages

**Use:** Dark feature chapter and objections.

**CSS:** `background: #0b0a06; color: #fffef2`

**Observed:** A full-width gradient from parchment to warm night surrounds a large proof image before the dark chapter.

**Transfer:** Make the transition a deliberate photographic threshold.

#### Purchase glass · level 2

**Only for:** individual product-detail openings

**Use:** Conversion card on the dark half of a split hero.

**CSS:** `background: linear-gradient(rgba(135, 135, 135, 0.2), rgba(0, 0, 0, 0.2)); border: 1px solid #303136; border-radius: 16px; backdrop-filter: blur(27px); padding: 16px 24px`

**Observed:** A compact 420px-wide purchase box stacks avatar proof, inclusion line, full-width raspberry action and price reassurance.

**Transfer:** Keep the translucent material confined to the purchase box.

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #e32652; color: #ffffff; border-radius: 8px; padding: 12px 24px; height: 44px`

**Text style:** `action` — Sohne 600 · 16px/1.25 · tracking 0.01em

**Observed:** Short centered label; placed beside a neutral or outlined secondary action. Disabled form actions use 0.3 opacity.

**States:** Declared: hover background #d61a46, white text and no underline; focus-visible white 2px solid outline with 2px offset; active background #c71a42.

### Secondary button

**Use:** Preview, gift or submit actions subordinate to conversion.

**CSS:** `background: transparent; color: #ffffff; border-radius: 8px; box-shadow: 0px 0px 0px 2px #43454c inset; padding: 12px 24px; height: 44px`

**Text style:** `action` — Sohne 600 · 16px/1.25 · tracking 0.01em

**Observed:** Can include a small play or gift icon; uses the same rectangle proportions as the primary action.

**States:** Declared: hover background #303136; focus-visible white 2px solid outline with 2px offset; active background transparent.

### Intent choice

**Use:** Personalize the opening by letting visitors name their goal.

**CSS:** `background: #222326; color: #ffffff; padding: 12px 16px; height: 48px; display: inline-flex; align-items: center; justify-content: flex-start`

**Text style:** `choice` — Sohne 400 · 16px/1.5 · tracking 0.01em

**Observed:** An empty square checkbox precedes the left-aligned label. Rows share one 8px-rounded clipping wrapper, with 4px black gaps; individual rows are not pills.

**States:** Declared: hover background #303136; focus-visible white 2px solid outline with 2px offset; active background #222326.

### Category chip

**Use:** Filter an image-led catalog.

**CSS:** `background: #0d0d0e; color: #9ea0a9; border: 1px solid #0d0d0e; border-radius: 8px; padding: 12px 16px; height: 48px`

**Text style:** `action` — Sohne 600 · 16px/1.25 · tracking 0.01em

**Observed:** Small category icon precedes the label. Chips wrap in centered rows with 8px gaps; the featured category has a restrained gold outline.

**States:** Declared: hover background #303136 and white text; focus-visible white 2px solid outline with 2px offset; active background #222326.

### Email field

**Use:** Sample-request and newsletter forms.

**CSS:** `background: #191c21; border-radius: 4px; box-shadow: 0px 0px 0px 1px #272c33 inset; height: 48px; display: flex; align-items: center`

**Text style:** `body` — Sohne 400 · 16px/1.5 · tracking 0.02em

**Observed:** Dark inset field pairs with a separate submit button; consent checkbox and brief legal support sit underneath.

### FAQ row

**Use:** Compact default objection handling.

**CSS:** `background: #222326; color: #f4f4f5; border-radius: 4px; padding: 16px; min-height: 56px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `body-strong` — Sohne 600 · 16px/1.5 · tracking 0.02em

**Observed:** Bold question at left, simple downward chevron at right. Rows are separated by 16px and grouped under understated category labels.

### Premium button

**Use:** Action within the premium split interlude.

**CSS:** `background: #dcff00; color: #211d0d; border: 2px solid transparent; border-radius: 8px; padding: 8px 20px; height: 44px`

**Text style:** `action` — Sohne 600 · 16px/1.25 · tracking 0.01em

**Observed:** A dark circular arrow concludes the text; this accent is not the default conversion color.

**States:** Declared: hover background #3b3227, ivory text and 2px solid lime border; focus-visible white 2px solid outline with 2px offset; active background #c71a42.

### Featured quote card

**Use:** Human proof over a portrait.

**CSS:** `background: #272c33; color: #ffffff; border-radius: 8px; padding: 48px 96px; position: relative; z-index: 1`

**Text style:** `quote` — Sohne 400 · 20px/1.6 · tracking 0.01em

**Observed:** A generous quote block overlaps the left edge of a taller photograph; attribution is below the quote, with circular previous/next controls at the outer edges.

**Transfer:** Use a credible personal account and a portrait in a real environment.

### Utility navigation

**Use:** Small cross-offering navigation above the main header.

**CSS:** `background: #0d0d0e; height: 40px; padding: 4px 0px`

**Text style:** `utility-label` — Sohne 600 · 12px/1.45 · tracking 0.02em

**Observed:** A left-aligned run of small links inside the centered container. A separate 64px sticky black main header holds logo, browse control, search, account links and raspberry action.

### Editorial catalog card

**Only for:** premium-offering landing pages

**Use:** Compare substantial premium offerings.

**CSS:** `background: #fefaf2; color: #16140c; border-radius: 16px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `editorial-card-title` — Sohne 500 · 26px/1.35 · tracking 0.0173em

**Observed:** A 400×248px conceptual image tops a 400px-wide card. Inside 32px padding: identity, title, curator line, dashed rule, brief description, then duration and outlined action aligned along the bottom. Availability badges sit over the image.

**Transfer:** Make each card a distinct visual proposition while keeping metadata and action positions consistent.

### Editorial FAQ row

**Only for:** premium-offering landing pages

**Use:** Wide print-like objection handling.

**CSS:** `border-top: 1px dashed #726855; padding-top: 48px; margin-bottom: 16px; display: flex; align-items: center; color: #fffef2`

**Text style:** `editorial-card-title` — Sohne 500 · 26px/1.35 · tracking 0.0173em

**Observed:** Question spans the wide container with a lime circular plus at the far edge; expanded answer uses warm taupe large body text. The closed-row presentation is the default.

## Imagery and graphics

### Staggered portrait wall

**Use:** Signature opening proof of human expertise.

**Observed:** Two vertical columns of warm, natural-color head-and-torso portraits occupy the right half of the opening. Subjects look toward camera in real interiors. Tiles have softly rounded corners; unequal vertical starts and black fades at top and bottom make the wall extend beyond its viewport.

**Transfer:** Commission candid but controlled portraits of makers, customers or practitioners. If no people are appropriate, use tall close-ups of real product results and tools, not generic interface tiles.

**Build:** Use two equal columns of 285×356px object-fit:cover images with roughly 20px gutters. Offset one column vertically; clip the wall and place black-to-transparent gradient masks over its top and bottom. Keep a circular pause control at the lower right.

### Cinematic posters and showcase

**Use:** Discovery rails, wide launch spotlight and full-bleed demonstration.

**Observed:** Portrait posters combine close faces, editorial title artwork and dark caption fades. A wide showcase gives roughly two thirds to people and colorful scene lighting, fading to black behind a compact title and action at the right. The full-bleed demonstration places a tall list of white category links over darkened moving footage.

**Transfer:** Stage a recognizable person or meaningful product outcome at cinematic scale. Use portrait crops for browseable items and a wide still or film for the major demonstration; keep branding inside artwork subordinate to readable HTML titles.

**Build:** For the wide showcase, layer a cover photograph below a rightward black gradient: transparent around the middle, rgba(0,0,0,0.9) near the text and opaque black at the right edge. For full-bleed footage add a translucent black overlay and position the white text list above it.

### Warm tangible proof

**Use:** Premium split interlude and warm-theme proof chapter.

**Observed:** A framed cream-and-black document leans against honey-colored wood paneling under strong afternoon window light. Diagonal shadows cross both wall and floor. The object fills its half of the split panel; a later widescreen view lets the physical result dominate the page.

**Transfer:** Photograph the new product's tangible output, package, published work or finished artifact in a warm architectural setting. A clean rendered object with realistic daylight and diagonal window shadows is the minimum substitute; avoid a floating UI screenshot.

### Environmental testimony

**Use:** Featured testimonial and compact member-story variants.

**Observed:** The featured portrait is a full-body outdoor photograph beside an overlapping slate quote panel. Product-detail stories use small oval portraits above centered quotes in three charcoal cards.

**Transfer:** Favor credible, individual photography and modest attribution over a large corporate-logo wall.

### Portal illustration

**Only for:** premium-offering landing pages

**Use:** Image half of an all-access offer panel.

**Observed:** A dark olive architectural void contains several bright lime rectangular openings. A tiny human silhouette at the central doorway casts a long triangular beam into the foreground; soft haze makes the scene aspirational rather than technical.

**Transfer:** Express access or possibility with a simple abstract room and light apertures rather than reproducing the original art.

**Build:** Make a dark olive rectangular scene with five perspective-skewed lime apertures of varied sizes. Put a small charcoal human silhouette in the lowest central opening; extend two translucent lime polygons diagonally toward the lower-right foreground. Blur duplicate aperture layers by 16–32px at low opacity and add fine low-opacity monochrome noise.

### Contour capability art

**Only for:** individual AI-oriented product pages

**Use:** Four numbered capability cards and coordinated hero backing.

**Observed:** Soft mint, pink, coral and yellow fields carry thin dashed contour paths and a fine dot texture. Each tall card has a raspberry numbered circle at top left and a white benefit title at the bottom, with a dark lower fade.

**Transfer:** Use a coordinated family of abstract contours for related capabilities rather than treating this colorful treatment as the default page background.

**Build:** Layer blurred radial gradients in pale mint, pink, coral and ochre inside four 288×361px rounded cards. Add SVG dashed elliptical or rounded-rectangle contours with a thin dark low-opacity stroke, plus a faint repeated dot pattern. Overlay a transparent-to-black bottom gradient, then the number badge and title.

### Icons

**Observed:** Mostly simple filled SVG controls in white at 16–24px; category symbols are muted gray at 20px. Warm-theme arrows and benefit symbols use round-ended strokes around 1.7px at 20px. Plus, chevron and play shapes are visually spare.

**Transfer:** Use familiar compact symbols, matched to text color. Keep category icons secondary and reserve circular icon backgrounds for arrows, numbers and media controls.

## Section recipes

How recurring sections are built.

### First screen: Personal invitation opening

**Observed:** Above the black stage sits a 40px utility strip and a 64px main navigation. The inner 1200px composition divides into equal halves. Left: an uppercase condensed 80px/0.85 headline fills two lines in a 500px measure, beginning 96px below the main navigation; an 8px gap leads to semibold support. A tiny raspberry rule separates the promise from a 20px question. Intent choice rows follow with 16px separation from the prompt. Right: the Staggered portrait wall extends upward and downward through a clipped area, with dark edge fades and a pause control. In the first 900px the full headline, support, prompt, choice stack and main portrait wall are visible; the continue action reaches the bottom edge and the next benefits section is below the fold.

**Transfer:** Preserve the balance of a bold two-line invitation and an immersive human or tangible-result wall. Adapt the goal choices to the new product, ending in one action. An individual product-detail opening instead uses a 700px-tall equal split: edge-to-edge cinematic image on the left, centered title, concise summary and Purchase glass box on the right. A premium destination opens on Parchment chapter with a 74px serif promise, dark action and square warm object photograph.

**Avoid:** Do not center a giant headline over a generic dashboard, shrink the portrait wall to a decorative thumbnail or turn the choice stack into a bright multicolor quiz.

**Text style:** `display` — Sohne Schmal 500 · 80px/0.85 · tracking 0.01em · uppercase

### Benefits and conversion strip

**Observed:** A 32px heading and paired Primary button and Secondary button sit on the left; a concise icon-led benefit list sits on the right. The black canvas remains uninterrupted.

**Transfer:** Explain what the customer receives immediately after the opening without another massive headline.

### Discovery theater

**Observed:** A centered 48px headline introduces a wide photographic spotlight. A later headline leads to Category chips and a horizontal rail of 240×427px posters. Edges may show a partial next tile; small arrows and compact pagination indicate more content.

**Transfer:** Move from one hero example to a browseable family of outcomes, products or use cases. Keep captions and preview actions on the media rather than adding long paragraphs below.

### Compact conversion pause

**Observed:** A centered 48px promise sits above one line of price and reassurance, followed by a raspberry action and neutral browsing action. The entire block remains on black.

**Transfer:** Use a short commercial pause between content chapters; supply truthful terms and a clear next step.

### Premium interlude

**Observed:** A shared 16px-rounded 1216×488px split panel joins Premium split backing and Warm tangible proof. The centered serif promise, 22px support and Premium button are vertically balanced in the text half.

**Transfer:** Include an editorial premium-offer device for a higher-value route, advanced capability or tangible outcome; retain the warm image and contrasting serif register without inventing a separate product tier.

### Business invitation

**Observed:** A 460px square people-and-work image overlaps a Charcoal panel. A 64px condensed uppercase headline, short body and paired conversion/link actions occupy the right.

**Transfer:** Use this compact two-part construction for a second audience or team-oriented use case.

### Personal proof

**Observed:** A 32px centered section heading sits above Featured quote card overlapping Environmental testimony. Circular arrows flank the composition and tiny pagination sits underneath. Individual product details use three equal charcoal quote cards with small oval portraits instead.

**Transfer:** Let the human story interrupt the catalog rhythm; keep the featured quote spacious and the alternative triptych concise.

### Immersive category demonstration

**Observed:** A full-width tall video stage carries a 32px left-aligned prompt and stacked 24px category links at the upper left. A pause control sits near the upper right; footage and a dark overlay fill the backing.

**Transfer:** Use this large cinematic device for demonstrating the breadth of the product. If film is unavailable, use a strong full-bleed still whose subject leaves a clear text area.

### Objections and true ending

**Observed:** A sample-request email strip precedes a centered FAQ heading and narrow categorized FAQ row stacks. The ending is a substantial black footer, not a final giant slogan: a newsletter block at left, four link columns to its right, app-download badges in the last column, then ample black space and a small identity/copyright/security line at the bottom. The footer is about 896px tall. The warm variant uses wide Editorial FAQ rows, then a 531px warm-ink footer with two link columns, a larger identity at lower left and legal/security text at lower right.

**Transfer:** Close with useful questions and a functional newsletter-and-navigation destination. Use only relevant download links; preserve the roomy bottom area rather than compressing the footer into one line.

### Warm editorial feature chapter

**Only for:** premium-offering landing pages

**Observed:** Parchment chapter carries a centered 74px heading and two square image-led benefits. A broad warm-to-dark gradient surrounds a 1200×666px proof image. Warm night chapter follows with a centered 96px statement, 160px staging gaps, three text tabs with lime mono labels and a lime 2px active underline above a large demonstration image.

**Transfer:** Use the theme shift as a premium narrative arc: practical benefit, tangible proof, then deeper explanation. Keep large serif text and the photographic threshold together.

## Page flow

**Storyline:** Personal promise → concrete experience → breadth and value → premium route → human proof → objections → useful subscription and navigation ending.

### Broad discovery and membership conversion

1. **Promise and qualification** — Condensed invitation beside a staggered portrait wall, with intent choices.
2. **Value explanation** — Included benefits and paired actions.
3. **Product demonstration** — Wide launch spotlight followed by category filters and portrait catalog.
4. **Conversion and alternate paths** — Centered price reassurance, premium split interlude and business invitation.
5. **Social proof** — Overlapping personal quote and environmental portrait.
6. **Breadth demonstration** — Full-bleed video with category links.
7. **Objection handling and ending** — Email samples, categorized FAQ, then newsletter-led multi-column footer and small security line.

**Transfer:** Use this pattern when visitors need both a reason to care and a way to discover a broad offering; shorten the catalog without losing cinematic media and personal proof.

### Premium-offering education and comparison

1. **Outcome promise** — Parchment serif opening paired with a warmly lit physical proof object and four dotted-divider benefits.
2. **Offer comparison** — Cream cards with conceptual image caps and bottom-aligned metadata/actions.
3. **Expanded value** — Split all-access panel with portal illustration and lime action.
4. **Capability and authority** — Two square benefit images followed by a large physical proof image.
5. **Deeper demonstration** — Transition to warm night, monumental serif statement and lime-labeled feature tabs.
6. **Lead generation** — Bright lime rounded signup panel.
7. **Objections and ending** — Wide dashed-rule FAQ followed by a warm-ink two-column footer, low identity and security line.

**Transfer:** Carry the entire warm editorial variant into a dedicated premium destination; do not mix its typography and palette arbitrarily into the default catalog.

### Explain one product and convert within a larger catalog

1. **Product promise and purchase** — Cinematic equal-split hero with centered summary and translucent purchase card.
2. **Capabilities** — Four numbered visual outcome cards with a lesson-plan link.
3. **Product demonstration** — Wide trailer/sample player.
4. **Related value** — Related portrait rail and three illustrated membership benefits.
5. **Conversion and proof** — Compact price action and three personal testimonial cards.
6. **Alternate routes** — Premium split interlude and business invitation.
7. **Objections and ending** — Sample email form, narrow categorized FAQ and full newsletter/navigation footer.

**Transfer:** Lead with one concrete result, show capabilities and a real demonstration before expanding into ecosystem value.

## Writing

Aspirational but direct: personal improvement is presented with the confidence of exceptional expertise and the friendliness of a guide. Short emotional promises give way quickly to practical benefits, access and reassurance.

**Do not copy:** Do not reuse the brand's name, logos, course artwork, instructor or partner identities, testimonials, superlative claims, prices, class counts, guarantees or credential assertions. Source examples illustrate cadence only; replace them with truthful product-specific copy.

- **Addressing the reader:** Speak directly to you and your ambitions. Refer to the product clearly by its new name; use we mainly for practical communication such as email delivery.
- **Rhythm:** Headlines favor compact parallel phrases, often two clauses or three short beats. Support is usually one sentence; catalog descriptions are brief and benefit-led. Controls use one to three words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Connect an exceptional input to the reader's future self through repetition. | 6–10 words | “Learn from the best, be your best.” |
| Discovery heading | A small emotional benefit followed by an everyday availability promise. | 7–12 words | “A dose of inspiration, whenever you need it.” |
| Benefit statement | Use clipped parallel clauses to promise practical progress. | 3 short clauses | “Lean in. Level up. Drive real results.”<br>“Practical. Applicable. Zero fluff.” |
| Support | State access or practical value in one concrete sentence. | 8–20 words | “Get unlimited access to thousands of bite-sized lessons.” |
| Primary action | Simple verb plus destination or task, not a clever slogan. | 1–3 words | “Explore Certificates”<br>“Watch Trailer”<br>“Contact Sales” |
| Newsletter invitation | A small sense of belonging followed by a useful explanation. | 4–6 words | “Join the inner circle.” |

**Words and phrasing to use:** your; learn; build; practical; proof; progress; possibilities; start; explore

**Avoid:** synergy; disruptive ecosystem; unlock unprecedented value; revolutionary solution; hustle harder

**Rules:**

- Pair every aspirational promise with a practical description or proof element nearby.
- Use questions to invite selection and resolve concerns, not as vague rhetorical filler.
- Write distinct benefit titles rather than repeating the product name on every card.
- Keep price, access and reassurance readable near the action; separate them from the emotional headline.

## Do's and Don'ts

### Do

- Use 80px condensed uppercase type only for the opening-level promise, with the tight 0.85 line height.
- Give ordinary section leads the wider 48px/1.25 or 32px/1.25 semibold grotesk treatment.
- Align most content to the 1264px shell with 32px side padding.
- Keep primary and secondary actions at 44px height and 8px corners.
- Use 16px gaps between dark FAQ rows and 48px between their groups.
- Make the premium split panel warm and tangible, with 64px serif text and a lime action.
- Keep human photographs large enough to carry the composition, including the overlapping featured testimony.
- Retain the spacious functional ending rather than substituting a generic final CTA strip.

### Don't

- Do not turn every card into a floating panel with a drop shadow; the hierarchy is flat black, charcoal and inset edges.
- Do not use pill-shaped conversion buttons; pill treatment belongs to small status badges only.
- Do not spread raspberry across full-width sections; it is a small conversion signal.
- Do not apply lime indiscriminately to default navigation or ordinary conversion buttons.
- Do not set all headings in condensed capitals; the wider grotesk headings establish the browsing hierarchy.
- Do not replace 4px-separated intent rows with disconnected rounded cards.
- Do not brighten all media uniformly; captions need local dark fades while faces retain natural color.
- Do not pull abstract AI contour art into an unrelated product's core visual language.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background and box-shadow transitions of 0.25s; category controls declare border-color transitions of 0.2s.
- Email controls declare color and box-shadow transitions of 0.2s.
- The portrait wall has vertical scrolling animation declarations; carousels and full-bleed video expose pause controls.

**Transfer:**

- Preserve pausable motion for the portrait wall and immersive media. A still image wall must retain the staggered composition and edge fades.
- Use the declared short color/edge transitions on controls rather than adding scale or spring effects to every button.

**Unknown:**

- Portrait-wall duration and the timing of individual cinematic media sequences are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 576px, 768px, 960px, 1200px and 1265px; desktop navigation has dedicated large-screen visibility rules.
- Warm-theme layout declarations include column-to-row switches for the hero and offer panels.

**Transfer:**

- On narrow screens, stack the invitation before a shorter portrait-wall window and keep goal choices full width; retain the condensed headline's short line rhythm.
- Keep poster rails horizontally browseable instead of shrinking portrait tiles into a dense grid.
- Stack split premium panels and reduce the editorial statement size while preserving the serif/mono contrast. These are adaptation rules, not fixed breakpoint prescriptions.

**Unknown:**

- Exact mobile type sizes, media order, padding and header behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
