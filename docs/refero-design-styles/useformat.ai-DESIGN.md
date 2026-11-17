# Format — technicolor listening room

## Overview

A dark, cinematic style that makes software feel like a cultural experience rather than a dashboard pitch. Warm amber studio scenes, occasional electric blue and vivid red interrupt a near-black canvas, while delicate editorial serifs sit beside practical neo-grotesk text. It suits products with a human benefit and a tangible experience to demonstrate, combining spacious storytelling with compact controls and richly staged interface imagery.

### Essentials

- Editorial promises over a cinematic stage: a 72px PS Times headline at 350 weight, 0.88 line height and -0.9px tracking sits upper-left over a full-height human scene, with a small support paragraph anchored near the bottom.
- The darkness is warm, not technological blue-black: #0e0202 is the dominant canvas; #1a1a1a and #1e1e1e organize panels and the ending. Saturated color belongs inside photographic stages, selected proof names and small identity blocks, not every section background.
- Actions are small illuminated rectangles: 38px height, 6px corners and 14px medium text; white primary buttons pair with translucent bordered film buttons at a 24px gap.
- Chapter markers behave like listening cues: an 8px circular dot precedes sentence-case 14px/1.3 labels; hairlines and muted text establish active-versus-inactive emphasis.
- Proof becomes typography at architectural scale: two edge-clipped rows of 128px customer names alternate serif and sans, with most names at 25% white and a single vivid highlight. Use verified names or equivalent short proof labels when logos are unavailable.
- The human voice gets a monumental panel: 80px/1.1 serif quotation text, selective underlining and white-to-gray emphasis sit above a lower-right grayscale portrait joined to a #ff3601 attribution block.
- A cinematic return closes the experience: a 600px translucent form panel with 48px padding and 12px backdrop blur floats over the warm scene, which fades into a #1e1e1e footer. Use an art-directed still when moving footage is unavailable.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal vermilion | `#ff3601` | `--color-red` | surface, accent | Attribution block and small playback symbols. |
| Proof pink | `#ea53d8` | `--color-highlight` | text, accent | One highlighted name in the oversized proof field; highlight hue can change between names. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Light | `#ffffff` | `--color-white` | text, action, surface | Headlines, active labels, icons and primary buttons. |
| Burgundy black | `#0e0202` | `--color-canvas` | background | Dominant page canvas and warm dark navigation backing. |
| Charcoal panel | `#1a1a1a` | `--color-panel` | surface, text | Feature and demonstration cards, quotation band and dark text on white actions. |
| Dark hairline | `#261b1b` | `--color-hairline` | border, text | Visible 10% white on the canvas for separators and ghost headings. |
| Closing charcoal | `#1e1e1e` | `--color-footer` | background, surface | Footer and the final color of the closing scene fade. |
| Dark control | `#2a2a2a` | `--color-control` | action, surface | Full-width media actions. |
| Glass wash | `#3e3535` | `--color-glass` | surface | Visible white at 20% on the dark canvas; the same overlay brightens and picks up the scene beneath the conversion panel. |
| Logo tile | `#383838` | `--color-tile` | surface | Square integration logo backings. |
| Dimmed proof | `#4a4141` | `--color-quiet-name` | text | Visible 25% white proof typography over the canvas. |
| Field wash | `#4b4343` | `--color-input` | surface | Visible neutral field tint on the dark canvas, built with rgba(216,217,218,0.3). |
| Editorial gray | `#787878` | `--color-muted` | text | Inactive prose and unrevealed quotation words. |
| Secondary light | `#878181` | `--color-secondary` | text, border | Visible 50% white on the warm canvas; secondary text and rules use rgba(255,255,255,0.5). |
| Silver edge | `#dddddd` | `--color-button-edge` | border | Film action border. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| media demonstrations | Record red | `#cc2c15` | `--color-record-red` | surface | One colored demonstration artwork backing. |
| media demonstrations | Record blue | `#1680cc` | `--color-record-blue` | surface | Third demonstration artwork backing. |
| media demonstrations | Record magenta | `#bb42ad` | `--color-record-magenta` | surface | Second demonstration artwork backing. |

## Typography

- **PS Times** — Hero, editorial section headings, proof names and testimonial. Fine, high-contrast Times-like editorial serif with compact display proportions. If unavailable, use **Times New Roman**. Use regular; preserve the tight hero leading. Font stack: "PS Times", "Times New Roman", Times, serif.
- **Neue Haas Grotesk TX Pro** — Body copy, controls, chapter labels and sans proof names. Neutral neo-grotesk with compact, matter-of-fact text shapes. If unavailable, use **Inter**. Use 400–500 for copy and controls. Font stack: "Neue Haas Grotesk TX Pro", "Inter", Arial, sans-serif.
- **Neue Haas Grotesk DS Pro** — Closing headline and demonstration titles. Display-cut neo-grotesk with clean, slightly denser forms. If unavailable, use **Inter**. Use 500 for display titles. Font stack: "Neue Haas Grotesk DS Pro", "Inter", Arial, sans-serif.
- **NHaasGrotesk** — Light explanatory prose and bold form titles. Light and bold neo-grotesk cuts used as editorial contrast. If unavailable, use **Inter**. Use 300 for Light and 700 for Bold. Font stack: "NHaasGrotesk", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| ghost-heading | PS Times | 400 | 140px | 1 | normal | Low-contrast typographic backdrop behind demonstration cards. |
| proof-sans | Neue Haas Grotesk TX Pro | 400 | 128px | 1.3 | -0.0234em | Sans names in the oversized proof rows. |
| proof-serif | PS Times | 400 | 128px | 1.3 | -0.0234em | Serif names interspersed with the sans proof names. |
| quote | PS Times | 350 | 80px | 1.1 | 0.0125em | Large multiline testimonial with selected underlines. |
| hero | PS Times | 350 | 72px | 0.88 | -0.0122em | Two-line opening promise; text-balanced in a 962px maximum width. |
| editorial-heading | PS Times | 400 | 64px | 1.3 | 0.0156em | Centered chapter headline. |
| closing-heading | Neue Haas Grotesk DS Pro | 500 | 64px | 1.1 | 0.0156em | Centered two-line conversion promise over the closing scene. |
| heading | Neue Haas Grotesk TX Pro | 400 | 28px | 1.2 | -0.02em | Practical capability headings and feature-card titles. |
| form-heading | NHaasGrotesk | 700 | 24px | 1 | normal | Two-line invitation at the top of the conversion form. |
| attribution | Neue Haas Grotesk TX Pro | 400 | 20px | 1.3 | normal | Speaker name in the bright portrait block. |
| hero-support | Neue Haas Grotesk TX Pro | 500 | 17px | 1.3 | normal | Compact explanation pinned below a fine rule in the opening. |
| editorial-body | NHaasGrotesk | 300 | 17px | 1.3 | normal | Explanation and image-led step captions. |
| body | Neue Haas Grotesk TX Pro | 400 | 15px | 1.5 | normal | Capability paragraphs; white on open canvas and 50% white within charcoal cards. |
| label | Neue Haas Grotesk TX Pro | 400 | 14px | 1.3 | normal | Chapter markers and muted navigation anchors. |
| button | Neue Haas Grotesk TX Pro | 500 | 14px | 1 | normal | Opening action pair. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| media demonstrations | demo-title | Neue Haas Grotesk DS Pro | 500 | 20px | 1.4 | normal | Short title above each demonstration action. |
| media demonstrations | media-action | Neue Haas Grotesk TX Pro | 500 | 14px | 20px | normal | Full-width demonstration playback action. |

**Notes:**

- Serif headlines are delicate rather than bold. The opening uses much tighter leading than the slower 1.3 chapter heading.
- Sans headings tighten to -0.02em at 28px, but the closing display expands to 1px tracking. Do not normalize these into one universal headline treatment.
- The quotation and proof rows deliberately compete with imagery in scale; practical explanatory copy remains 15–17px.
- Bold and Light legacy font files are visual weights 700 and 300, not regular merely because each cut has its own family declaration.

## Layout

**Density:** Airy between narrative chapters, compact inside actions and forms; the dark space is part of the pacing.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Dot-to-label and icon-to-action gaps. |
| 16px | Outer desktop frame, demonstration-card padding and repeated media gaps. |
| 24px | Action-pair separation, feature-card side padding and image-caption columns. |
| 32px | Feature heading-to-description gap, form heading-to-fields gap. |
| 40px | Chapter lead spacing and footer link gaps. |
| 48px | Conversion panel padding and explanatory group gaps. |
| 64px | Heading rule offset and split-section column gap. |
| 72px | Editorial section vertical padding. |
| 105px | Opening top inset and capability section vertical padding. |
| 120px | Large narrative breathing room and footer separation. |

### Containers and grids

- **page-frame**: max width 1512px · side padding 16px. Centered page with a narrow dark outer frame; media spans nearly the full viewport.
- **hero-copy**: max width 962px · side padding 56px. Left-inset headline over a wide photographic stage; bottom support is limited to 487px.
- **media-demonstrations**: max width 1200px · 3 columns · gap 16px. Centered, equal-width media cards beneath a monumental ghost heading.
- **feature-grid**: 3 columns · gap 14px · side padding 8px. Three equal charcoal capability panels; 370px maximum text width inside each.
- **split-story**: 2 columns · gap 64px · side padding 8px. 720px-wide landscape scene at left with a 480px text block at right, vertically centered.
- **conversion**: max width 600px · side padding 48px. Centered glass form near the base of the closing media stage.

## Corner radius

| Element | Radius |
| --- | --- |
| controls-and-media-insets | 6px |
| demonstration-cards | 8px |
| chapter-dot | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| primary-light | `0px 0px 18px 0px rgba(255,255,255,0.25)` | Soft local glow around the opening primary action. |
| field-edge | `0px 1px 2px 0px rgba(0,0,0,0.05)` | Subtle input definition, not a raised-card effect. |

### Surfaces

#### Warm dark canvas · level 0

**Use:** Default page background.

**CSS:** `background: #0e0202`

**Observed:** Most narrative space stays unboxed.

**Transfer:** Let the near-black field carry the section rhythm.

#### Charcoal panel · level 1

**Use:** Capabilities, quotation band and demonstration containers.

**CSS:** `background: #1a1a1a`

**Observed:** Large bands and feature cards are square; only demonstration cards gain 8px corners.

**Transfer:** Use shape changes sparingly rather than rounding every surface.

#### Navigation glass · level 2

**Use:** Persistent desktop navigation over media and text.

**CSS:** `background: rgba(14,2,2,0.549); backdrop-filter: blur(22px)`

**Observed:** Dark translucent strip with a centered identity and left/right navigation groups.

**Transfer:** Keep the imagery legible behind it without turning it into a bright floating island.

#### Conversion glass · level 2

**Use:** Closing form.

**CSS:** `background: rgba(255,255,255,0.2); backdrop-filter: blur(12px); padding: 48px; max-width: 600px`

**Observed:** Square panel; scene color remains visible through the neutral wash.

**Transfer:** Place it over a real image with enough tonal variation to make the material apparent.

#### Closing fade · level 1

**Use:** Join the last photographic stage to the footer.

**CSS:** `background: linear-gradient(rgba(0,0,0,0) 0%, rgba(0,0,0,0) 40%, #1e1e1e 100%)`

**Observed:** Full-stage overlay with the lower portion dissolving into charcoal.

**Transfer:** Match the footer color exactly so the closing is one continuous environment.

## Components

### Desktop navigation

**Use:** Orient readers while moving through long chapters.

**CSS:** `position: fixed; height: 72px; width: 100%; padding: 16px; z-index: 50; background: rgba(14,2,2,0.549); backdrop-filter: blur(22px)`

**Text style:** `label` — Neue Haas Grotesk TX Pro 400 · 14px/1.3

**Observed:** Four small dot-prefixed chapter links on the left, centered wordmark, and utility links plus a white conversion action on the right. Active chapter labels are white; inactive ones are 50% white. The strip is absent from the initial cinematic opening and appears during the reading sequence.

**States:** Declared: hover chapter-link color rgba(255,255,255,0.8).

### Primary button

**Use:** Main conversion action in the opening.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 38px; padding: 9px 24px; background: #ffffff; color: #1a1a1a; border-radius: 6px; box-shadow: 0px 0px 18px 0px rgba(255,255,255,0.25)`

**Text style:** `button` — Neue Haas Grotesk TX Pro 500 · 14px/1

**Observed:** Text-only action beside the film control. The navigation version is 40px high with 12px 16px padding; the form version is a full-width 36px-high action without the glow.

**States:** Declared: hover opacity 0.9.

### Film button

**Use:** Secondary invitation to view a cinematic explanation.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 38px; padding: 9px 24px; background: rgba(221,221,221,0.27); color: #ffffff; border: 1px solid #dddddd; border-radius: 6px; backdrop-filter: blur(2px)`

**Text style:** `button` — Neue Haas Grotesk TX Pro 500 · 14px/1

**Observed:** White circular play symbol leads the label; it visually belongs to the scene rather than sitting on an opaque panel.

**States:** Declared: hover background-color rgba(221,221,221,0.4).

### Chapter marker

**Use:** Small section-entry cue.

**CSS:** `display: flex; align-items: center; gap: 8px; color: #ffffff`

**Text style:** `label` — Neue Haas Grotesk TX Pro 400 · 14px/1.3

**Observed:** An 8px solid circle precedes the label; centered for the editorial introduction and left-aligned for practical chapters.

**Transfer:** Name the reader's next topic in one or two plain words.

### Capability card

**Use:** Explain a focused product quality without adding another visual scene.

**CSS:** `background: #1a1a1a; padding: 32px 24px; height: 427px`

**Text style:** `heading` — Neue Haas Grotesk TX Pro 400 · 28px/1.2 · tracking -0.02em

**Observed:** Square, text-led panels with a compact title and a 15px paragraph set below it. Text is restrained to a 370px-wide inner column; descriptive text is 50% white.

**Transfer:** Keep generous internal breathing room; use one idea per card.

### Integration tile

**Use:** Show compatibility in a compact practical proof grid.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 56px; height: 56px; background: #383838; border-radius: 0px`

**Observed:** White monochrome logo, at most 32px high, centered in a square with a tiny gray caption beneath; five columns by two rows with 16px horizontal and 24px vertical gaps.

**Transfer:** Use only relevant integrations; group them as a small index, not a dominant logo wall.

### Glass field

**Use:** Collect the two pieces of information needed for the conversion.

**CSS:** `height: 36px; width: 100%; padding: 4px 12px; background: rgba(216,217,218,0.3); border: 1px solid rgba(255,255,255,0.5); border-radius: 6px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Observed:** Two stacked fields, then a white full-width submit action. Light placeholder text sits directly inside each field; a 16px gap separates fields.

### Portrait attribution

**Use:** Give a monumental quotation a human signature.

**CSS:** `display: flex; align-items: center; gap: 24px; background: #ff3601; height: 160px`

**Text style:** `attribution` — Neue Haas Grotesk TX Pro 400 · 20px/1.3

**Observed:** Grayscale, halftone-like square portrait flush to the left of a vivid red name-and-role block. The entire signature sits at the lower right of the quotation band.

**Transfer:** Use a real speaker portrait; retain the square treatment and bright adjoining block.

### Footer band

**Use:** Conclude with identity and compact utility navigation.

**CSS:** `background: #1e1e1e; color: #ffffff; padding: 50px 32px 60px`

**Observed:** A 200px-wide wordmark sits left; a compact circular assurance mark and a single row of utility links, language switch and copyright sit right. Muted legal text occupies the lower-right half after 120px of separation.

**Transfer:** Keep a low, horizontal ending rather than a sitemap; include an assurance mark only when warranted.

### Demonstration card

**Only for:** media demonstrations

**Use:** Offer concrete examples to explore.

**CSS:** `display: flex; flex-direction: column; padding: 16px; background: #1a1a1a; border-radius: 8px; overflow: hidden`

**Text style:** `demo-title` — Neue Haas Grotesk DS Pro 500 · 20px/1.4

**Observed:** Title, muted dated metadata, full-width playback control, then a nearly square artwork region. Three equal cards share a centered row; artwork backings change red, magenta and blue.

**Transfer:** Show genuine sample outputs or examples appropriate to the new product.

### Playback button

**Only for:** media demonstrations

**Use:** Explore a media example.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 46px; padding: 12px 0px; background: #2a2a2a; color: #ffffff; border: 1px solid transparent; border-radius: 6px`

**Text style:** `media-action` — Neue Haas Grotesk TX Pro 500 · 14px/20px

**Observed:** Small vermilion circular play icon precedes centered text; control spans the artwork width.

**States:** Declared: hover background-color rgb(58,58,58).

## Imagery and graphics

### Cinematic human stage

**Use:** Opening, closing and a contrasting mid-page scene.

**Observed:** A person at a laptop sits within a studio-built island of plants, rocks and branches. Amber light blooms overhead against an ochre cyclorama; the floor and foreground fall into deep shadow. A second scene uses blue lighting and a person interacting with a phone. Scenes occupy most of the opening, not a small card.

**Transfer:** Art-direct a real human using or benefiting from the new product in a tactile studio environment. Keep amber as the main scene and blue as a contrast. The minimum version is one carefully lit still with physical props and a dark lower foreground, not a generic office photograph.

**Build:** Use a full-bleed photographic layer with object-fit: cover, subject near center and open upper-left space for text. Add a transparent-to-warm-black lower gradient and subtle dark side vignette. Light a plain warm backdrop from above, place plants or material props in the foreground, and keep the brightest area above the subject; exact glow stops are not essential.

### Interface in a scene

**Use:** Immediate product grounding after the opening and in image-led feature chapters.

**Observed:** Dark desktop and mobile interfaces overlap on the warm black field; the larger desktop screen is behind and the upright phone overlaps its lower-right edge. Later panels embed close-up interfaces over amber or blue footage. Device edges are subdued; the content is more important than the hardware.

**Transfer:** Use one credible primary interface and a second responsive or contextual view; retain the dark stage and restrained framing even when the product UI is light.

### Oversized proof field

**Use:** Typographic social proof between explanatory chapters.

**Observed:** Two horizontal rows of large names extend beyond both edges. Serif and sans names alternate, mostly very dim, while a single name lights up in a saturated hue.

**Transfer:** Use verified customer names or short validated proof labels. Preserve the word-field composition even without polished logo assets.

**Build:** Make two overflow-hidden rows with width-max flex tracks; use 128px/1.3 text, -3px tracking, 48px side padding per name and a 24px row gap. Alternate serif and sans, set inactive names to rgba(255,255,255,0.25), and assign one active name the highlight color. Clip at the page frame.

### Speaker portrait

**Use:** Quotation signature.

**Observed:** Black-and-white headshot with a coarse, printed halftone quality; square crop and no circular avatar framing.

**Transfer:** Convert the real speaker's portrait to grayscale with strong tonal contrast and a fine dot texture; keep face detail legible.

### Record artwork

**Only for:** media demonstrations

**Use:** Tactile artwork for sample audio outputs.

**Observed:** Near-square colored artwork regions sit under media controls, with vinyl-themed imagery and distinct red, magenta and blue backings.

**Transfer:** For audio, use a simple record metaphor; for other products, use a similarly tangible sample-output object rather than an unrelated music motif.

**Build:** For an audio sample, draw a dark circular disc in SVG with concentric thin rings, a small center label and a pinhole, clipped within a 6px-radius square. Set the backing to one of the three demonstration colors and keep each disc consistent in scale.

### Icons

**Observed:** Chapter cues are solid 8px dots. Film actions use an 18px circular play icon, demonstration actions a 16px vermilion play icon. Integration marks are white silhouettes on square dark tiles.

**Transfer:** Choose compact filled playback symbols and monochrome partner marks. Do not replace the chapter dots with a library of decorative line icons.

## Section recipes

How recurring sections are built.

### First screen: Cinematic promise

**Observed:** A 16px outer frame surrounds a 1408px-wide, 900px-high photographic stage. The warm human scene fills the background, with darkened ground below and a bright amber upper field. In front, a dot label sits upper-left after 105px top padding; the 72px serif hero occupies two compact lines across roughly two thirds of the width. The Film button and Primary button sit 36px below the heading with 24px between them. A 487px-wide ruled support paragraph anchors the bottom-left while a compact identity mark balances the lower-right. The first 900px show the promise, both actions, human subject and supporting explanation; the overlapping product-interface scene starts below the fold. Navigation does not compete with the opening scene.

**Transfer:** Start with a human outcome expressed as a short two-line promise, then stage the product's context as a theatrical environment. Without footage, use a lit still with enough empty upper-left area for type. A more functional page can shorten the scene and lead into an interface sooner, while keeping the serif promise and small action pair.

**Avoid:** Do not turn this into a centered SaaS headline above a floating dashboard, or shrink the photograph into a thumbnail beside the copy.

**Text style:** `hero` — PS Times 350 · 72px/0.88 · tracking -0.0122em

### Editorial chapter

**Observed:** Chapter marker centers above the Editorial-heading. A fine 10% white rule sits 64px beneath the heading. A narrow 472px explanatory text block follows in the middle of the page, using white first and muted gray for subsequent thoughts, with selected underlined phrases.

**Transfer:** Use a short metaphorical heading followed by plain explanation; keep the explanation narrower than the heading and media.

**Text style:** `editorial-heading` — PS Times 400 · 64px/1.3 · tracking 0.0156em

### Image-led steps

**Observed:** Three roughly 448px-wide visual panels sit in a row. Each has a fine rule and short title/body caption below, with active content white and adjacent steps subdued. Product views are layered into warm or cool cinematic scenes rather than isolated on blank neutral cards.

**Transfer:** Explain a workflow in a few self-contained scenes; keep captions brief and use emphasis to indicate the current step.

**Text style:** `editorial-body` — NHaasGrotesk 300 · 17px/1.3

### Proof as word field

**Observed:** Oversized proof field spans nearly the full page and clips names at both edges. Alternating font classes and one colored name provide the composition, with no separate card for each company.

**Transfer:** Let verified proof names become a visual texture; adapt placement and repetition to the page's story.

**Text style:** `proof-sans` — Neue Haas Grotesk TX Pro 400 · 128px/1.3 · tracking -0.0234em

### Ghost headline and samples

**Observed:** A dot chapter cue introduces a 140px serif ghost heading at 10% white. A 1200px-wide row of three Demonstration cards overlaps the heading's lower edge. Each card offers an immediately usable example rather than only describing a capability.

**Transfer:** Use a low-contrast oversized phrase behind a row of tangible, explorable sample outputs.

**Text style:** `ghost-heading` — PS Times 400 · 140px/1

### Human scene and practical proof

**Observed:** A 720px by 480px blue-lit human scene occupies the left side. A 480px-wide block to the right contains the 28px Heading, a 15px explanation and a compact Integration tile grid; the 64px column gap gives the image room.

**Transfer:** Pair an emotional use context with concrete interoperability or capability proof.

**Text style:** `heading` — Neue Haas Grotesk TX Pro 400 · 28px/1.2 · tracking -0.02em

### Text-led capability triptych

**Observed:** Three Capability cards share a row with 14px gutters, framed by 105px vertical section padding. Each is 427px high, with restrained text occupying a centered inner column.

**Transfer:** Use this as a quieter pause between rich media scenes. Give each panel one distinct product quality.

**Text style:** `heading` — Neue Haas Grotesk TX Pro 400 · 28px/1.2 · tracking -0.02em

### Monumental customer voice

**Observed:** A square charcoal band uses 24px padding and an 80px serif quotation across nearly the full width. Early words are bright while later words recede to gray; the key endorsement is underlined. Portrait attribution sits lower-right with substantial empty space to its left.

**Transfer:** Select a conversational quote long enough to form several sweeping lines; use the bright signature block as the visual punctuation.

**Text style:** `quote` — PS Times 350 · 80px/1.1 · tracking 0.0125em

### Return to the scene

**Observed:** An 810px-high closing scene returns to warm studio imagery. The Closing-heading centers in a 962px-wide area above Conversion glass. The panel holds a compact two-line form invitation, two Glass fields and a full-width white action. Closing fade dissolves directly into Footer band.

**Transfer:** Revisit the opening environment so conversion feels like the conclusion of the same story. Ask only for the minimum useful information.

**Text style:** `closing-heading` — Neue Haas Grotesk DS Pro 500 · 64px/1.1 · tracking 0.0156em

### Horizontal utility ending

**Observed:** Footer band is 330px tall at desktop, with identity at left and a single compact utility row to the right. A circular assurance symbol sits with the links, while legal copy is kept low and right-aligned.

**Transfer:** Close with a concise identity-and-trust strip, not a second promotional hero or a many-column directory.

## Page flow

**Storyline:** human promise → tangible product view → editorial explanation → use-context chapters → social proof → explorable examples → practical capabilities → customer voice → cinematic conversion → compact utilities

### Introduce a product experience and make its value understandable through both feeling and concrete examples

1. **Promise** — Full-height warm human scene with delicate serif outcome headline and paired actions.
2. **Product demonstration** — Overlapping desktop and mobile interface views establish what the product actually does.
3. **Explanation** — Centered editorial chapter heading, narrow explanatory prose and three image-led workflow moments.
4. **Social proof** — Monumental two-row proof names with one saturated highlight.
5. **Hands-on proof** — Three sample outputs beneath a ghost headline.
6. **Capability chapters** — Blue human scene with integration index, followed by restrained charcoal text panels.
7. **Customer validation** — Large conversational quotation with bright portrait signature.
8. **Closing call** — Return to the warm scene with a translucent two-field conversion panel.
9. **Utilities** — Low horizontal identity, assurance and legal footer.

**Transfer:** Keep the alternation of emotional stage, concrete product detail and typographic proof. Change the chapter count and sequence to fit the product; a product without media playback can offer interactive samples or real output previews instead.

## Writing

Sensory and humane in headlines, straightforward and practical in explanations. Confident without sounding combative; the product is presented as a way to make real work fit naturally into life.

**Do not copy:** Do not reuse Format's name, marks, customer names, speaker identity, testimonial, integration claims, dates, legal text or product-specific promises. Examples illustrate syntax and tone only; use verified content belonging to the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your'; refer to the product by its name in explanatory sentences rather than repeatedly saying 'we'.
- **Rhythm:** Short memorable headline fragments alternate with complete explanatory sentences. Capability titles are compact noun phrases; supporting paragraphs usually fit within a few lines. Actions use direct verbs with no hype punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a personal benefit and the concrete form in which it arrives. | 6–10 words | “Personalized customer insights in weekly podcasts.” |
| Editorial chapter | A brief sensory metaphor with a period. | 3–5 words | “Hear the color.”<br>“Hearing is believing.” |
| Capability title | Short noun phrase describing a useful quality. | 2–4 words | “Personalized intelligence”<br>“Listen & read along” |
| Supporting explanation | Describe the mechanism and end with the benefit to the reader. | One or two sentences | “[Brand] continuously learns what matters to you, so you get only the most valuable insights for your work. [Brand] delivers what you need to know, and filters out the rest.” |
| Action | Plain verb plus the object or next step. | 1–4 words | “Watch the film”<br>“Book a demo”<br>“Listen” |

**Words and phrasing to use:** your; personalized; real; clear; hear; follow along; go deeper; what matters; just for you

**Avoid:** revolutionary; 10x; dominate; unleash; game-changing; AI-powered everything; enterprise-grade synergy

**Rules:**

- Let one sensory metaphor carry a chapter; explain the actual mechanism immediately afterward.
- Describe the reader's context with ordinary situations rather than abstract transformation language.
- Use underlining to make a phrase feel spoken or actionable, not to decorate every heading.
- Make action labels literal enough that the next step is predictable.

## Do's and Don'ts

### Do

- Keep the main canvas #0e0202 and use charcoal panels for structure rather than alternating bright section fills.
- Pair a 72px tightly led serif promise with compact 14px actions.
- Keep a 16px desktop outer frame around the major scenes.
- Use 6px corners for controls and 8px only for the rounded demonstration-card treatment.
- Let proof typography reach 128px and extend beyond the visible frame.
- Reserve #ff3601 for concentrated signatures and playback cues.
- Use 48px padding and 12px backdrop blur for the closing conversion panel.
- Maintain the continuous fade into the #1e1e1e footer.

### Don't

- Do not replace the editorial serif with a heavy geometric sans across all headline roles.
- Do not use pills for the main conversion buttons; the default is a 6px rectangle.
- Do not add broad neon glows behind every card; the light effect is localized around the opening white action.
- Do not make every proof name bright white; the 25% white field is essential to the single-name emphasis.
- Do not place partner logos in colorful rounded app-store badges; the integration index uses square #383838 tiles and white marks.
- Do not use circular portrait avatars for the testimonial signature; keep the square 160px portrait joined to the red block.
- Do not fill feature panels with decorative illustrations when text and negative space are doing the work.
- Do not expand the footer into a large multi-column sitemap; retain the horizontal utility treatment.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color and background transitions of .15s cubic-bezier(.4,0,.2,1).
- The fixed navigation declares an all-property transition of 0.3s cubic-bezier(.4,0,.2,1).
- Demonstration artwork declares all-property transitions of 0.3s cubic-bezier(0,0,.2,1).
- Proof tracks occupy translated horizontal positions; workflow captions use active and dimmed emphasis, and quotation text changes from white to gray across the sentence.

**Transfer:**

- Use motion to move emphasis through the proof field and workflow rather than animating every surface independently.
- Preserve the quiet chapter-dot navigation and active caption relationship when changing section content.

**Unknown:**

- Exact marquee speed, direction changes, quotation reveal timing and scroll-trigger logic are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 420px, 600px, 640px, 768px, 1024px, 1280px and 1536px.
- Hero classes specify smaller 48px, 56px, 64px and 68px steps before the 72px desktop treatment; outer page padding changes from 8px to 16px.
- Proof-name classes specify 48px with -1.5px tracking, then 80px with -2px tracking, then 128px with -3px tracking.

**Transfer:**

- On narrow layouts, keep the cinematic scene but place text clear of the person's face; reduce the serif size before sacrificing the short-line rhythm.
- Stack the split scene and practical copy, and convert three-column panels to a readable vertical flow. Keep the oversized proof rows clipped instead of shrinking them into ordinary body text.
- Let the conversion panel fill the available width with 32px inner padding and preserve the scene-to-footer fade.

**Unknown:**

- Mobile navigation, exact mobile chapter arrangements and the alternate small-screen demo layout are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
