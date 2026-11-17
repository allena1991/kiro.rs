# Synthesia — people on a luminous stage

## Overview

A bright, businesslike style that makes complex software feel approachable through human presenters and carefully staged interfaces. Tightly fitted grotesk headlines, white and mist-gray space, near-black navy, and restrained indigo give it a confident but welcoming character. Rounded demonstrations carry most of the color and visual richness, with luminous blue closing scenes providing a more theatrical finish. It suits product platforms, workflow tools, and enterprise services that need both hands-on clarity and credibility.

### Essentials

- Headlines feel compact rather than heavy: medium-weight grotesk at 72px/1 with -0.065em tracking for the opening, 44px/46px with -0.05em tracking for major chapters, and 34px/38px for feature explanations.
- The promise sits above a working product stage: a centered 768px text column leads into a 1216px-wide rounded demonstration with a gray segmented header, secondary tabs, and real media. The first 900px shows the promise, paired actions, reassurance, and the upper part of the stage.
- Conversions use small softened rectangles, not pill buttons: the default pair is 48px high with 10px corners and 12px 18px padding, dark navy primary beside outlined white secondary; closing actions grow to 58px with 12px corners.
- Color is concentrated inside demonstrations and selected full-width chapters: most explanatory space is white or #f7f7f7, text is #090b22, and #3e57da is reserved for small labels and accents. A luminous navy-to-periwinkle scene must appear as a visual punctuation point, not as a wash over the whole page.
- Interfaces are presented as tangible layered scenes: white floating panels over soft blue, mint, warm yellow, or deep olive fields, usually occupying a 592px-wide half of a split section. If no rich product media exists, construct one convincing workflow panel over the same atmospheric backing.
- Proof is human and editorial: portrait cards carry a logo at the top, a compact category badge, and a 26px/30px quote over a dark lower fade; compact monochrome logo rows counterbalance the photographic detail.
- The finish changes register: a 484px-high luminous closing band with a 56px/1 invitation and larger white actions gives way to a substantial #0d0f2c footer with a broad brand column and four narrow link columns.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep indigo navy | `#0d0f2c` | `--color-navy` | background, text | Footer, luminous dark scenes, and headings in extended feature layouts. |
| Action indigo | `#3e57da` | `--color-indigo` | accent, link, action | Small workflow labels; filled conversion actions on detailed feature and company layouts. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale blue light | `#e3ebff` | `--color-glow-light` | surface, accent | Light end of luminous text and small icon backplates. |
| Soft periwinkle | `#c6d7fe` | `--color-glow-mid` | accent, border | Middle of luminous text and outlined caption borders. |
| Blue-violet light | `#8098f9` | `--color-glow-deep` | accent | Saturated end of luminous lettering and blue halo details. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, floating interface panels, and inverted text. |
| Mist gray | `#f7f7f7` | `--color-subtle` | background, surface | Grouped demonstrations, benefit cards, and alternate workflow bands. |
| Soft gray rule | `#e9e9eb` | `--color-rule` | border, surface, text | Default dividers, tab backing, and secondary text on navy. |
| Button edge | `#dadadd` | `--color-edge` | border | Inset outline of secondary actions and stronger neutral panel borders. |
| Secondary gray | `#68686a` | `--color-muted` | text | Reassurance, navigation, and low-emphasis text. |
| Charcoal | `#363636` | `--color-body` | text | Default support copy and card paragraphs. |
| Midnight ink | `#090b22` | `--color-ink` | text, background, action | Default headings, primary actions, and dark demonstration chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| extended feature and company pages | Slate body | `#333b52` | `--color-cool-body` | text | Body copy in the extended feature and company treatment. |
| extended feature and company pages | Ice lavender | `#f2f4fd` | `--color-cool-wash` | background, surface | Cool alternate bands and feature-switcher shells. |
| extended feature and company pages | Cool panel edge | `#e6eaf4` | `--color-cool-rule` | border, text | Hairlines on extended feature panels and pale footer text. |
| lead forms and extended feature controls | Slate edge | `#d1d6e5` | `--color-input-edge` | border | Form fields and thin raised-control outlines. |

## Typography

- **Basiersquare Webfont** — All marketing headings, paragraphs, controls, and captions. A clean square-influenced grotesk with open lowercase forms; medium headlines become dense through tracking, not bold weight. If unavailable, use **Inter**. Use 400 and 500; preserve the unusually tight display tracking and balanced line wraps. Font stack: "Basiersquare Webfont", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Basiersquare Webfont | 500 | 72px | 1 | -0.065em | Default centered opening headline, normally balanced over two lines. |
| closing-heading | Basiersquare Webfont | 500 | 56px | 1 | -0.055em | Centered final invitation over luminous blue. |
| heading | Basiersquare Webfont | 500 | 44px | 46px | -0.05em | Major chapter introductions and the left heading of proof or question sections. |
| feature-heading | Basiersquare Webfont | 500 | 34px | 38px | -0.045em | Default split-section capability headline. |
| quote | Basiersquare Webfont | 500 | 26px | 30px | -0.04em | Short outcome quotes over portrait media and prominent plan names. |
| closing-support | Basiersquare Webfont | 400 | 20px | 26px | -0.02em | One-line supporting invitation in the default closing scene. |
| body-lead | Basiersquare Webfont | 400 | 18px | 24px | -0.015em | Opening support and explanatory feature paragraphs. |
| question | Basiersquare Webfont | 500 | 18px | 24px | -0.015em | Accordion question labels. |
| action-large | Basiersquare Webfont | 500 | 18px | 26px | -0.008em | Large closing buttons. |
| body | Basiersquare Webfont | 400 | 16px | 22px | -0.01em | Benefit copy and answers. |
| action | Basiersquare Webfont | 500 | 16px | 1.5 | -0.004em | Default action text. |
| eyebrow | Basiersquare Webfont | 500 | 14px | 18px | normal, uppercase | Small workflow markers and credibility badges. |
| caption | Basiersquare Webfont | 400 | 14px | 20px | -0.005em | Reassurance, footer links, and secondary metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| immersive feature launches | immersive-display | Basiersquare Webfont | 500 | 88px | 1 | -0.05em | Two-line immersive opening, with a luminous second phrase. |
| extended feature and company pages | feature-display | Basiersquare Webfont | 500 | 72px | 74px | -0.05em | Broad centered opening on a detailed feature or company page. |
| extended feature and company pages | feature-section-heading | Basiersquare Webfont | 500 | 56px | 58px | -0.04em | Large explanatory and benefit section headings. |
| extended feature and company pages | panel-heading | Basiersquare Webfont | 500 | 40px | 1.1 | -0.04em | Heading inside large framed feature panels and the detailed question section. |
| outcome-led feature pages | outcome-heading | Basiersquare Webfont | 500 | 28px | 34px | -0.035em | Short quantified outcomes directly below illustrative media. |
| extended feature pages | tile-heading | Basiersquare Webfont | 500 | 24px | 28px | -0.03em | Use-case tiles and feature-switcher labels. |
| extended feature and company pages | cool-body-lead | Basiersquare Webfont | 400 | 18px | 26px | -0.008em | Support copy for larger framed feature chapters. |
| extended feature and company pages | pill-caption | Basiersquare Webfont | 500 | 14px | 20px | 0.04em, uppercase | Outlined section labels. |
| extended feature pages | cool-caption | Basiersquare Webfont | 400 | 14px | 22px | -0.002em | Feature-switcher descriptions. |

**Notes:**

- Headlines stay at weight 500; their close spacing is a defining part of the voice. Keep paragraph tracking much looser.
- Balance display copy into deliberate lines; the default opening has a compact two-line silhouette, not a long thin sentence.
- The larger extended-feature scale is a separate treatment, not a replacement for every ordinary 44px chapter title.

## Layout

**Density:** Airy at section level, compact within controls and demonstrations; broad white intervals separate closely assembled UI and media.

### Spacing

**Spacing system:**

- **horizontal step** 8px, horizontal — Main layout gaps and inset spacing.
- **vertical rhythm** 12px, vertical — A frequent rhythm for stacked content; 16px and 8px are also explicit supporting tokens.

| Value | Use |
| --- | --- |
| 8px | Icon gaps and compact metadata. |
| 12px | Paired-action gap and footer link spacing. |
| 16px | Heading-to-copy gap and compact form spacing. |
| 24px | Copy-to-action gap and smaller card padding. |
| 32px | Default grid gap and benefit-card padding. |
| 40px | Desktop page side padding and large panel inset. |
| 48px | Larger heading-to-content interval and logo-row gaps. |
| 56px | Space below centered section introductions. |
| 64px | Feature opening vertical padding. |
| 80px | Footer vertical padding. |
| 96px | Major section padding and spacing between capability chapters. |

### Containers and grids

- **main container**: max width 1216px · side padding 40px. Centered desktop frame; at 1440px it leaves 112px on each side.
- **promise column**: max width 768px. Centered opening and chapter introductions; support copy shares the headline measure.
- **split feature**: max width 1216px · 2 columns · gap 32px. Equal 592px halves with vertically centered copy and media; alternate their sides across a capability sequence.
- **benefit grid**: 3 columns · gap 32px. Three 384px-wide benefit cards within the main container.
- **question split**: 12 columns · gap 32px. Heading occupies the left third; an 800px question stack occupies the right two thirds.
- **wide inset band**: max width 1344px · side padding 48px. Broad rounded artwork bands inset slightly from the viewport.
- **plan grid** (only for pricing pages): max width 1216px · 4 columns · gap 32px. Aligned plan cards with 279px-wide columns and continuous feature lists.
- **example gallery** (only for example-led feature pages): 2 columns · gap 24px. Wide landscape demonstrations with title and short description underneath.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | default actions | 10px |
|  | large actions | 12px |
|  | cards and stages | 16px |
|  | portrait tiles | 12px |
|  | caption pills | 9999px (pill) |
| extended feature and company pages | framed feature panels | 24px |
| lead forms | lead fields | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | action lift | `rgba(16, 24, 40, 0.08) 0px 2px 10px 0px` | Subtle default action lift. |
| extended feature and company pages | framed panel lift | `rgba(16, 24, 40, 0.08) 0px 2px 40px 0px` | Broad, pale shadow around white feature panels. |

### Surfaces

#### White canvas · level 0

**Use:** Default explanatory field.

**CSS:** `background: #ffffff; color: #090b22`

#### Mist stage · level 1

**Use:** Demonstrations and benefit groups.

**CSS:** `background: #f7f7f7; border-radius: 16px; overflow: hidden`

**Observed:** Flat rather than heavily elevated; the content and internal layering provide depth.

**Transfer:** Keep the outer shell understated so the staged product remains the focal point.

#### Navy chapter · level 0

**Use:** Developer-oriented demonstrations and dramatic changes of register.

**CSS:** `background: #090b22; color: #ffffff`

**Observed:** White text, pale support copy, and translucent panels create a second material vocabulary.

**Transfer:** Use a bounded chapter rather than turning the default page into a dark theme.

#### Cool feature shell · level 1

**Only for:** extended feature pages

**Use:** Backing for selectable capabilities and large product views.

**CSS:** `background: #f2f4fd; border-radius: 16px`

#### Framed white panel · level 1

**Only for:** extended feature and company pages

**Use:** One complete capability or editorial topic.

**CSS:** `background: #ffffff; border: 1px solid #e6eaf4; border-radius: 24px; padding: 40px; box-shadow: rgba(16, 24, 40, 0.08) 0px 2px 40px 0px`

**Observed:** Text and a large image sit side by side; the image is usually slightly larger than the text area.

**Transfer:** Frame one substantial topic, not every paragraph.

#### Translucent technical panel · level 1

**Only for:** developer-oriented chapters

**Use:** Code or technical architecture beside a capability list.

**CSS:** `background: rgba(255, 255, 255, 0.2); border: 1px solid rgba(255, 255, 255, 0.2); border-radius: 16px; padding: 32px`

**Observed:** A second, fainter translucent backing can group the code panel with a small live-status preview.

**Transfer:** Use system monospace only inside the technical artifact; retain the marketing font around it.

#### Luminous lettering · level 1

**Only for:** dark immersive feature and company scenes

**Use:** Emphasis on one display phrase.

**CSS:** `background-image: linear-gradient(90deg, #e3ebff, #c6d7fe 50%, #8098f9); background-clip: text; -webkit-text-fill-color: rgba(0, 0, 0, 0)`

**Transfer:** Keep most of the heading white and illuminate a single meaningful phrase.

## Components

### Primary button

**Use:** Default main conversion.

**CSS:** `background: #090b22; color: #ffffff; border-radius: 10px; padding: 12px 18px; height: 48px; display: flex; align-items: center; justify-content: center; gap: 8px; box-shadow: rgba(16, 24, 40, 0.08) 0px 2px 10px 0px`

**Text style:** `action` — Basiersquare Webfont 500 · 16px/1.5 · tracking -0.004em

**Observed:** Paired with a secondary action in the opening. Directional arrows are small and sit after the label where used.

**States:** Declared: hover background rgba(13, 15, 44, 0.8), box-shadow 0px 6px 20px 0px rgba(16, 24, 40, 0.08); active outline 0px. No focus-visible treatment established.

### Secondary button

**Use:** Demo, exploration, and supporting actions.

**CSS:** `background: #ffffff; color: #090b22; border-radius: 10px; padding: 12px 18px; height: 48px; box-shadow: #dadadd 0px 0px 0px 1px inset`

**Text style:** `action` — Basiersquare Webfont 500 · 16px/1.5 · tracking -0.004em

**Observed:** Equal width to the main action in the opening; content-sized in split feature sections.

**States:** Declared: hover background #f7f7f7, box-shadow 0px 0px 0px 1px #dadadd, 0px 6px 20px 0px rgba(16, 24, 40, 0.08); active outline 0px. No focus-visible treatment established.

### Closing button

**Use:** High-emphasis conversion over a dark luminous scene.

**CSS:** `background: #ffffff; color: #090b22; border-radius: 12px; padding: 16px 24px; height: 58px; box-shadow: rgba(16, 24, 40, 0.08) 0px 2px 10px 0px`

**Text style:** `action-large` — Basiersquare Webfont 500 · 18px/26px · tracking -0.008em

**Observed:** White primary with a right arrow; companion demo action is transparent with a faint white inset outline.

### Credibility capsule

**Use:** Brief reassurance above an opening or chapter.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; background: #f7f7f7; border: 1px solid #e9e9eb; border-radius: 9999px; padding: 8px 12px`

**Text style:** `eyebrow` — Basiersquare Webfont 500 · 14px/18px · uppercase

**Observed:** A small information icon can finish the label; keep the text on one line.

### Stage segment

**Use:** Top-level switching within a broad demonstration stage.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 12px 24px; height: 48px`

**Text style:** `eyebrow` — Basiersquare Webfont 500 · 14px/18px · uppercase

**Observed:** Three equal-width choices sit in an 8px-inset gray rail with 4px gaps. Active choice is white; a second row of smaller topic pills sits below.

### Benefit card

**Use:** Practical reassurance on ease of use, governance, or value.

**CSS:** `background: #f7f7f7; border-radius: 16px; padding: 32px; overflow: hidden`

**Text style:** `body` — Basiersquare Webfont 400 · 16px/22px · tracking -0.01em

**Observed:** A compact medium-weight lead sits above supporting copy; the arrow text link anchors the bottom. Three cards align in a row.

### Question row

**Use:** Objection handling.

**CSS:** `border-bottom: 1px solid #e9e9eb; overflow: hidden`

**Text style:** `question` — Basiersquare Webfont 500 · 18px/24px · tracking -0.015em

**Observed:** Question and right-pointing arrow share a row; open rows show an upward arrow and a paragraph below. A common closed row is 73px tall; the answer expands the row without a filled background.

### Footer link

**Use:** Dense navigation at the end of a page.

**CSS:** `color: #e9e9eb; display: block`

**Text style:** `caption` — Basiersquare Webfont 400 · 14px/20px · tracking -0.005em

**Observed:** Four narrow groups have stronger headings and 12px vertical link gaps. A broader brand column contains language, a short product description, disclosure, trust marks, and address; the bottom rule separates copyright and social icons.

### Outlined chapter label

**Only for:** extended feature and company pages

**Use:** Named section or capability marker.

**CSS:** `border: 1px solid #c6d7fe; border-radius: 9999px; padding: 6px 12px; display: flex; align-items: center; gap: 8px`

**Text style:** `pill-caption` — Basiersquare Webfont 500 · 14px/20px · tracking 0.04em · uppercase

**Observed:** A compact cool outline replaces the default bare blue-dot workflow marker.

### Lead field

**Only for:** lead-generation endings

**Use:** Stacked personal and work details in a white form card.

**CSS:** `background: #ffffff; border: 1px solid #d1d6e5; border-radius: 8px; padding: 12px 16px; height: 50px`

**Observed:** Five fields stack with 16px gaps inside a compact white raised card; phone includes a country selector. The continue action spans the form width and begins with reduced emphasis.

## Imagery and graphics

### Human product demonstrations

**Use:** Opening stage, capability chapters, and hands-on product examples.

**Observed:** Natural-looking presenters are framed at waist or chest height in softly lit offices and living spaces. Rounded video or interface frames keep the subjects inside the product story; warm skin and neutral clothing contrast with cooler marketing surfaces.

**Transfer:** Show the people or real-world work your product affects with similar natural light and candid professionalism. Without human media, show a realistic completed output within a clean workflow frame rather than adding decorative stock portraits.

### Layered workflow vignette

**Use:** The media half of a split capability section.

**Observed:** A nearly square rounded field holds one central white interface card and a few offset panels or previews. Backings vary between periwinkle, cyan-gray, pale yellow, mint, and olive; the UI stays crisp while the backdrop is broad and softly blended.

**Transfer:** Create a simplified but believable workflow with one input, one decision, or one result; use only enough detail to make the interaction legible.

**Build:** Use a 592px-wide rounded scene with hidden overflow. Layer two or three oversized radial gradients using pale blue, muted green, or warm neutral hues; add a bottom navy fade at low alpha. Center a white panel at roughly 70% of scene width, soften it with a 16px corner radius and a low-alpha shadow, then place one smaller offset preview behind it.

### Portrait proof reel

**Use:** Human evidence near a major promise.

**Observed:** Tall 384px by 496px portrait cards run beyond the container edges. Customer logos sit at upper left, translucent category pills at upper right, and short white quotes sit low over a near-black fade. Circular white arrow controls straddle the visible reel.

**Transfer:** Use licensed customer portraits or interview stills with their own verified quotes. With no portraits, stage real customer work in the same tall frame and retain the logo, category, and short quotation hierarchy.

### Luminous closing atmosphere

**Use:** A required visual punctuation scene, usually the final conversion band.

**Observed:** The default finish is a smooth vertical transition from deep navy through blue-violet to pale periwinkle. Larger feature scenes add huge curved translucent ribbons with fine light edges, dark space behind text, and concentrated blue light behind the product or form.

**Transfer:** Preserve the soft luminous blue atmosphere even without custom artwork; the minimal equivalent is a continuous dark-to-periwinkle gradient behind a strong invitation.

**Build:** For the default band, use a 484px-high full-width navy base, a vertical blue-violet-to-periwinkle gradient, and a broad blurred pale-blue glow along the lower edge. For ribbon scenes, overlay two oversized SVG elliptical arcs extending beyond the viewport, with white strokes at 0.15 alpha and translucent blue fills; concentrate a radial blue glow behind the right-side object. Match the soft glow; exact stops are not essential.

### Outcome illustrations

**Only for:** outcome-led feature pages

**Use:** Above three concise quantified benefit headlines.

**Observed:** Landscape tiles show a lavender analytical chart, a floating white CTA on cyan light, and a small support interface on yellow-green light. Numbers remain in the normal heading below the illustration rather than becoming enormous decorative figures.

**Transfer:** Give each claimed outcome one concrete visual mechanism: a trend, a conversion control, or a self-service result. Keep the colorful field inside the tile.

### Company people collage

**Only for:** company and recruiting pages

**Use:** Human editorial chapters and the recruiting finish.

**Observed:** Company chapters combine naturally lit team portraits with white framed panels. The recruiting scene layers slightly rotated photos, conversation cards, cursors, and a saturated brand tile over a very pale pink-and-blue ribbon background.

**Transfer:** Use your own team photography and genuine collaboration artifacts; create an airy collage rather than a dense scrapbook.

**Build:** Place three small rounded photos at slightly different rotations around a central collaboration card. Add two compact comment cards, a few cursor labels, and one solid brand-color rectangle. Back with low-alpha pink and blue radial gradients and one oversized thin white curved ribbon.

### Icons

**Observed:** Small utility SVGs are mostly 16px with thin rounded strokes; arrow and chevron strokes range around 1px–1.8px. Dropdown chevrons are 12px. Blue dots introduce workflow labels, and compact blue or pale-blue square backplates distinguish feature icons.

**Transfer:** Use a consistent thin rounded-stroke icon family, mostly 16px. Put arrows after text, chevrons beside navigation, and reserve colored backplates for capability markers.

## Section recipes

How recurring sections are built.

### First screen: Promise above a working stage

**Observed:** A white first screen places a restrained 72px-high navigation bar above a centered 768px promise column. A compact Credibility capsule precedes the dense two-line display headline; support follows after 16px, paired Primary button and Secondary button after 24px, then a muted reassurance line. A 1216px-wide Mist stage begins below the copy: a gray rail holds three Stage segments, a second row holds smaller topic choices, and the main content uses rounded presenter or output cards. The headline takes roughly the middle half of the viewport width; the stage spans most of the remaining width. Within the first 900px, headline, support, actions, reassurance, both tab levels, and the top of the demonstration are visible; the lower media, caption, and following proof continue below the fold. A slim gradient announcement strip can sit above navigation for a live release.

**Transfer:** Replace the media with a believable working example of the new product, retaining the broad segmented shell and the compact centered promise. Detailed feature pages can open with a 72px/74px title and an edge-clipped square media reel; immersive launches use an 88px luminous title over navy with a large demonstration below. Pricing opens with a smaller 44px title and plan cards, while company storytelling uses a dark 72px title above a wide video.

**Avoid:** Do not replace the stage with a lone floating dashboard or push all product evidence below the first screen. Do not make the default opening dark just because a feature launch uses navy.

**Text style:** `display` — Basiersquare Webfont 500 · 72px/1 · tracking -0.065em

### Centered chapter introduction

**Observed:** A 768px-wide center-aligned block combines a short category or trust label, a 44px chapter heading, 18px support, and a paired action row. Support sits about 16px below the headline; actions sit 24px lower, with 56px below the introduction before its chapter media.

**Transfer:** Use to announce a new capability family or audience outcome without imposing a fixed sequence.

**Text style:** `heading` — Basiersquare Webfont 500 · 44px/46px · tracking -0.05em

### Alternating workflow chapter

**Observed:** The split feature layout combines a small blue-dot uppercase eyebrow, feature-heading, support, and Secondary button on one side with a Layered workflow vignette on the other. Media measures 592px by 518px; successive chapters reverse sides and are separated by 96px.

**Transfer:** Tell a practical story about what users can do, one step or capability at a time, and alternate visual weight rather than inventing a different layout for each step.

**Text style:** `feature-heading` — Basiersquare Webfont 500 · 34px/38px · tracking -0.045em

### Human proof reel

**Observed:** A left-aligned chapter heading shares a top row with explanatory copy and a demo action at right. Below it the Portrait proof reel stretches beyond the container, with three principal cards and partial neighbors visible.

**Transfer:** Use short, outcome-specific testimony and preserve the contrast between a restrained white introduction and image-rich proof.

**Text style:** `quote` — Basiersquare Webfont 500 · 26px/30px · tracking -0.04em

### Hands-on light panel in a dark chapter

**Observed:** A Navy chapter surrounds a wide Mist stage. The left side presents a short title, compact selectable examples, a text input area, and a full-width action; a large rounded presenter preview occupies the right. The overall light panel is 1216px wide with generous internal separation.

**Transfer:** Offer a small meaningful trial action appropriate to the product, with a convincing preview. The interaction can be a calculator, template picker, or sample transformation.

### Questions with a side heading

**Observed:** A heading occupies the left third of the main container and an 800px-wide Question row stack occupies the remainder. One answer is open; closed questions are separated by thin rules with directional icons rather than boxed cards. Major vertical padding is 96px.

**Transfer:** Prioritize actual adoption objections, keeping answers practical and action-oriented.

**Text style:** `heading` — Basiersquare Webfont 500 · 44px/46px · tracking -0.05em

### Luminous invitation and substantial footer

**Observed:** The default closing band uses Luminous closing atmosphere, a centered closing-heading, a support line after 24px, and Closing button with a transparent companion after 48px. It is 484px high. The Footer follows directly on deep navy with 80px vertical padding, a broad brand column, four 176px link groups, and a bottom legal-and-social row. Detailed feature endings can instead use left-aligned invitation copy with a large editor view extending off the right edge; lead-generation endings place a white field card at right. Company storytelling ends with the pale people collage and a recruiting action before the same footer.

**Transfer:** End with a clear next step and a luminous change of material. Choose the centered invitation, split product invitation, or lead form according to conversion intent; retain the substantial footer.

**Text style:** `closing-heading` — Basiersquare Webfont 500 · 56px/1 · tracking -0.055em

### Framed editorial capability

**Only for:** extended feature and company pages

**Observed:** A Framed white panel groups a pill label, panel-heading, three concise checkmarked benefits or an editorial paragraph, an action, and a substantial rounded image. Media is approximately 648px wide, and panels are separated by 96px. The company version uses shorter 542px-high panels; detailed features use 649px-high panels.

**Transfer:** Keep each panel about one meaningful idea. Alternate media placement and swap checklists for prose where the story is editorial.

**Text style:** `panel-heading` — Basiersquare Webfont 500 · 40px/1.1 · tracking -0.04em

### Selectable capability showcase

**Only for:** extended feature pages

**Observed:** A large centered feature-section-heading leads into a Cool feature shell. A narrow left stack of icon-led capability names accompanies a much larger right interface scene; the active item becomes a white raised card with a short description. Some extended scenes use an exaggerated 80px lower-right corner.

**Transfer:** Group related capabilities around one changing product view rather than presenting a wall of unrelated cards.

**Text style:** `feature-section-heading` — Basiersquare Webfont 500 · 56px/58px · tracking -0.04em

### Quantified outcome trio

**Only for:** outcome-led feature pages

**Observed:** A pill label and large left-aligned heading share the section top with a small action. Three 389px-wide Outcome illustrations sit below, each followed by an outcome-heading and a brief paragraph. Numerical multipliers remain part of the sentence-sized headline.

**Transfer:** Use comparable verified outcomes and give each a concrete illustrative mechanism.

**Text style:** `outcome-heading` — Basiersquare Webfont 500 · 28px/34px · tracking -0.035em

### Aligned pricing decision

**Only for:** pricing pages

**Observed:** A minimal logo-and-login header precedes a centered 44px heading, product-category switch, and billing toggle. Four plan columns align names, prices, allowance strips, actions, and ruled feature lists. Basic tiers use pale gray headers, the recommended tier uses luminous indigo-to-periwinkle, and the enterprise tier uses a dark-to-muted-gold image treatment. Below, a three-input calculator sits beside a colored recommendation card, followed by a long comparison matrix with a persistent plan header, vertical rules, and 70px–72px rows.

**Transfer:** Preserve a clear low-to-high plan progression, aligned comparisons, and one emphasized recommendation; use the calculator only where the pricing model warrants it.

**Text style:** `heading` — Basiersquare Webfont 500 · 44px/46px · tracking -0.05em

## Page flow

**Storyline:** Promise → tangible product demonstration → human and organizational proof → capability or decision chapters → reassurance and objections → luminous next step → deep navigation footer.

### Broad platform landing page

1. **Promise and product demonstration** — Centered promise over a tabbed media stage and compact reassurance.
2. **Social proof** — Portrait quote reel and monochrome customer marks.
3. **Capability chapters** — Centered chapter introduction followed by alternating workflow splits; later families change to gray and navy fields.
4. **Hands-on trial** — A light interactive panel in a dark band provides a sample task and preview.
5. **Adoption reassurance** — Three compact benefit cards, logo proof, and a wide resource-support scene.
6. **Objection handling** — Side heading with a ruled question stack.
7. **Closing call** — Centered luminous invitation, paired actions, and substantial dark footer.

**Transfer:** Lead with a tangible output, then expand from practical capabilities to organizational confidence; adapt the number of chapters to the product.

### Detailed capability and catalog landing page

1. **Promise** — Centered large title, rating capsule, indigo action, and an edge-clipped square media reel.
2. **Capability chapters** — Large framed panels alternate text and media; checkmarked lists explain differences.
3. **Evidence and instruction** — Research-backed benefit cards, a dark numbered tutorial scene, and pale testimonial band.
4. **Breadth and reassurance** — Use-case grid, security cards, square media catalog, and selectable platform capabilities.
5. **Objection handling and discovery** — Question stack followed by a wrap of outlined discovery links.
6. **Closing call** — Left invitation over a dark ribbon scene, large editor image spilling right, then the dark footer.

**Transfer:** Use the catalog only when variety is part of the purchase decision; preserve distinct modes, proof, and clear progression toward a trial.

### Company credibility and recruiting story

1. **Positioning** — Luminous navy opening, centered large title, and broad naturally lit presenter video.
2. **Company rationale** — Three framed editorial panels combine mission, governance, and technical ambition with relevant media.
3. **Institutional proof** — Wide dark rounded logo band with an exaggerated lower-right curve.
4. **Human credibility** — Four-column portrait lineup with names and roles.
5. **Closing call** — Pale ribbon-backed collaboration collage and recruiting action, followed directly by the dark footer.

**Transfer:** Tell a company story through people, practices, and independent support; end with a relevant participation action rather than forcing a generic trial invitation.

### Pricing and plan selection

1. **Decision framing** — Minimal navigation, compact headline, category switch, billing controls, and four aligned plans.
2. **Decision support** — Monochrome logo row, colored add-on band, and calculator with recommendation.
3. **Detailed comparison** — Long category-grouped feature matrix with persistent plan headings and fine grid rules.
4. **Specialized conversion** — Compact developer band and a broad enterprise scene with white benefit cards.
5. **Proof and objections** — Pale review section and extensive ruled questions.
6. **Closing call** — Centered luminous invitation and the standard dark footer.

**Transfer:** Keep the decision at the top, expose detailed comparisons without making the opening dense, and explain usage or add-ons near the relevant pricing choice.

### Outcome-led feature launch with sales conversion

1. **Promise and demonstration** — Oversized luminous two-line title on navy above a large interactive example and inverted customer marks.
2. **Practical examples** — Category tabs and a two-column landscape example gallery.
3. **Quantified proof** — Three illustrative outcome tiles with concise sentence-sized metrics.
4. **Capability depth** — Selectable feature list beside a large interface scene.
5. **Independent reassurance** — Compact outlined review-and-award panel.
6. **Closing call** — Dark ribbon scene with expectation checklist and white lead form, then the standard footer.

**Transfer:** Use the immersive opening for a focused launch; connect demonstrations to outcomes before asking for detailed contact information.

## Writing

Direct, capable, and conversationally reassuring. Claims are tied to concrete tasks, measurable outcomes, or enterprise concerns rather than abstract technological excitement.

**Do not copy:** Do not reuse Synthesia names, logos, presenter identities, customer assets, testimonials, ratings, user counts, security certifications, comparative claims, or product-specific numbers without independent authorization and verification. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your; use direct verbs for tasks and the product name for definitions. Company narratives use we and our sparingly.
- **Rhythm:** Headlines are compact but can be full task-oriented phrases. Support usually takes one or two short sentences; lists favor parallel verbs. Friendly questions and contractions soften the enterprise vocabulary.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | State the category and business audience plainly, or promise a concrete transformation. | 6–12 words | “AI Video and Avatar platform for business”<br>“Turn your videos into interactive experiences” |
| Capability headline | Begin with an action and make the result specific. | 7–12 words | “Easily generate videos from docs, PowerPoints, or links”<br>“Practice hard conversations before they happen” |
| Supporting copy | Explain the action, then remove a practical obstacle or show how the result stays useful. | 20–40 words | “Need to make a change? Edit your video, and it automatically updates across shared links, website embeds, and your LMS.” |
| Reassurance heading | Use short parallel statements that speak to several decision-makers. | 8–14 words | “Loved by users. Approved by legal. Signed off by CFOs” |
| Action | A short direct verb phrase; name free access or a demo only when true. | 2–5 words | “Get started for free”<br>“Book demo”<br>“See open roles” |
| Questions and closing | Use the reader's own adoption question, then a low-pressure invitation. | 4–10 words | “You’ve likely got a few questions”<br>“Ready to try [Brand]?” |

**Words and phrasing to use:** create; build; your team; automatically; in minutes; at scale; get started; no need to; consistent; control; practice; confidence

**Avoid:** revolutionary paradigm; unleash limitless potential; disrupt everything; magic with no explanation; overly playful slang

**Rules:**

- Name inputs and outputs so readers can picture the workflow.
- Pair numerical claims with relevant proof and a meaningful unit.
- Translate enterprise concerns into plain-language benefits rather than acronyms alone.
- Use contractions and brief questions to make reassurance sound human.
- Keep buttons literal; reserve descriptive detail for adjacent support text.

## Do's and Don'ts

### Do

- Keep the default display at 72px, weight 500, and -0.065em tracking.
- Use the 1216px container and 768px promise column as the principal desktop proportions.
- Keep default actions 48px high with 10px corners and a 12px gap when paired.
- Give major capability chapters 96px of separation.
- Concentrate rich color inside 592px-wide media scenes and selected navy bands.
- Use 16px corners for default stages and 24px only for the extended framed treatment.
- Keep outcome figures in readable 28px headlines beneath their illustrations.
- Finish a standard landing page with the luminous invitation and the 80px-padded navy footer.

### Don't

- Do not replace medium-weight tight headlines with heavy 700-weight display type.
- Do not make every conversion control a pill; pills belong to badges and compact selectors.
- Do not spread saturated indigo across the entire white explanatory canvas.
- Do not use equally strong drop shadows on all cards; default gray benefit cards are flat.
- Do not style every metric as a giant isolated numeral; outcomes are phrased as readable claims.
- Do not turn the footer into a short copyright strip; its link architecture is substantial.
- Do not put 24px framed-panel corners on every small control or portrait.
- Do not apply the 88px immersive title and gradient text to ordinary capability sections.

## Motion and responsive

### Motion

**Observed:**

- Actions declare box-shadow and background-color transitions of 0.2s; text links commonly declare color 0.2s.
- Stage selection declares background-color 0.3s and color transitions.
- Logo strips declare a 30s linear infinite sliding animation.
- Selected media controls declare opacity 0.3s ease; some panels declare transform 0.2s.

**Transfer:**

- Use the declared short color-and-shadow changes for action feedback; let the luminous scene remain atmospheric rather than adding unrelated motion.
- Use a slow continuous logo strip only where a horizontal proof row warrants it.

**Unknown:**

- Full entrance choreography, autoplay behavior, timing relationships, and reduced-motion behavior are not established.

### Responsive

**Observed:**

- The root font-size uses calc(0.4rem + 0.666667vw); rem-based dimensions therefore change with viewport width.
- Declared width breakpoints include 479px, 767px, 991px, 1180px, 1440px, 1920px, and 2560px.
- Layout classes indicate centered tablet text and single-column tablet variants for some grids.

**Transfer:**

- As implementation guidance, stack split feature copy above its demonstration on narrow screens, preserving the rounded scene rather than reducing it to an unreadable thumbnail.
- Allow the edge-clipped portrait reel to remain horizontally navigable; wrap discovery pills and collapse footer groups while keeping the brand block distinct.
- Preserve the hierarchy of promise, action, and visible demonstration when reducing display size; do not let fluid root sizing make controls impractically small.

**Unknown:**

- Exact mobile sizes, gutters, navigation collapse, matrix overflow behavior, and breakpoint-specific art direction are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
