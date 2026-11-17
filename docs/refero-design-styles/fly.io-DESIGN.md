# Fly.io — storybook cloud machinery

## Overview

A buoyant, technically literate style that makes serious tools feel approachable. Light editorial sections pair expressive serif headlines with a soft grotesk, while lavender, sky blue, pink and vivid violet give the page a storybook atmosphere. Hand-drawn characters, fantastical machines and occasional jewel-toned illustration sit alongside practical tables and code. The overall density is spacious in storytelling and compact where readers compare details.

### Essentials

- Editorial promises with a handwritten wink: Mackinac 64px/1.15 at weight 500 and -0.045em tracking, with a whole italic phrase and a loose underline rather than a generic bold sans headline.
- An illustrated world, not an isolated product render: the 804px opening places left-aligned copy against a full-bleed pastel sky, with a large ink-outlined subject occupying the right third and ribbons passing behind the text. Supply an original drawn object and flowing paths even when no product imagery exists.
- Small, luminous controls float above the world: the centered navigation is a 44px pill with 24px backdrop blur; the principal action is a 48px violet-gradient pill with 20px horizontal padding.
- White space carries most of the story: use 128px chapter padding and two-column compositions within 1200px, interrupted by concentrated violet bands rather than tinting every card. Color returns as 64px-blurred sky-blue, periwinkle and pink light at section seams.
- Human-scale drawings explain abstract capabilities: approximately 384px-wide unframed vignettes oppose 536px text columns; keep visible pencil-like outlines, imperfect perspective and pastel fills instead of polished stock 3D.
- Proof has its own decorative vocabulary: 36px violet serif numbers beside 2px lavender left rules, plus a broad rounded pastel halftone panel holding translucent quote cards.
- A theatrical conversion flourish anchors the design: a 312px violet-to-indigo illustrated band combines 48px white serif copy, a mint-colored final phrase and a translucent pill action, resolving into a dark-plum directory footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action violet | `#7c3aed` | `--color-violet` | action, accent, link | Buttons, figures, badges and emphasized links. |
| Deep violet | `#6d28d9` | `--color-violet-hover` | link, action | Hover fill and small proof labels; also the middle of the closing gradient. |
| Deep plum ink | `#281950` | `--color-ink` | text | Default headline and strong text color. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Magenta violet | `#a02be4` | `--color-magenta` | background, action | Leading corner of bright violet gradients. |
| Closing purple | `#8919c9` | `--color-closing-purple` | background | Leading corner of the conversion-band gradient. |
| Electric indigo | `#4f46e5` | `--color-indigo` | background, action | Trailing corner of action and bright-band gradients. |
| Bright lavender | `#8b5cf6` | `--color-violet-light` | accent, link | Dark-footer link hover and bright band base. |
| Closing indigo | `#4338ca` | `--color-closing-indigo` | background | Trailing corner of the conversion-band gradient. |
| Sky light | `#7dd3fc` | `--color-sky` | accent, background | Blurred seam light and illustrated atmospheric blue. |
| Mint spark | `#6ee7b7` | `--color-mint` | text, accent | Short final phrase against the saturated conversion band. |
| Periwinkle light | `#a5b4fc` | `--color-periwinkle` | accent, background | Middle of blurred pastel seam light. |
| Pink light | `#f9a8d4` | `--color-pink` | accent, background | Warm edge of pastel seam light. |
| Lavender accent rule | `#ddd6fe` | `--color-lavender-rule` | border | Stat dividers and translucent announcement borders. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft plum body | `#5e537c` | `--color-body` | text | Visible body tone on white; constructed with rgba(40,25,80,0.75). |
| Slate plum | `#564c73` | `--color-muted` | text | Compact explanatory text in practical product and pricing content. |
| Footer lavender | `#a39ac1` | `--color-footer-muted` | text | Footer links and secondary copy against dark plum. |
| Input edge | `#42385f` | `--color-input-edge` | border | Dark form-field outlines. |
| Dark divider | `#282045` | `--color-dark-rule` | border | Footer newsletter divider. |
| Panel plum | `#22183c` | `--color-panel-ink` | text, surface | Panel headings and dark input or terminal grounds. |
| Midnight plum | `#191034` | `--color-footer` | background | Default footer ground. |
| Muted lavender | `#686082` | `--color-caption` | text | Attributions and subdued supporting copy. |
| Quote lavender edge | `#d5cfef` | `--color-quote-edge` | border | Quote-card outline. |
| Light lavender edge | `#e6e0fe` | `--color-panel-edge` | border | Large atmospheric panel outline. |
| Blue black | `#121226` | `--color-night` | background | Dark gradient undertone and editorial directory footer. |
| Pale violet rule | `#e7e6f4` | `--color-rule` | border | Practical cards, tables and section separators. |
| Cool canvas | `#f1f2f9` | `--color-canvas` | background | Cool underlying page ground fading into white. |
| Translucent quote paper | `#f7f6fc` | `--color-quote-wash` | surface | Visible pale card tone; rgba(244,243,251,0.75) on a light pastel panel. |
| White | `#ffffff` | `--color-white` | background, text, surface | Main chapter canvas and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial directories | Editorial metadata | `#676b89` | `--color-story-meta` | text | Byline and reading-time labels. |
| editorial directories | Editorial slate | `#4c4e67` | `--color-story-body` | text | Editorial excerpts. |
| pricing and editorial directories | Lavender canvas | `#f5f3ff` | `--color-wash` | background | Pale background for comparison bands and editorial card directories. |

## Typography

- **Mackinac** — Promises, section headings, statistics and editorial titles. Soft, personable serif with broad forms, lively italic and gently irregular literary character. If unavailable, use **Lora**. Use 500 for display and tune line breaks before changing tracking. Font stack: "Mackinac", "Lora", ui-serif, Georgia, Cambria, "Times New Roman", Times, serif.
- **Fricolage Grotesque** — Body copy, navigation, actions and metadata. Friendly, slightly idiosyncratic grotesk with light body weight and compact utility labels. If unavailable, use **Bricolage Grotesque**. Use variable weights 325, 450, 500 and 575; preserve the light body texture. Font stack: "Fricolage Grotesque", "Bricolage Grotesque", ui-sans-serif, system-ui, sans-serif.
- **ui-monospace** (only for code demonstrations) — Terminal commands and code comments. System monospace; technical contrast to the expressive serif. Font stack: "ui-monospace", SFMono-Regular, "Fragment Mono", Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Mackinac | 500 | 64px | 1.15 | -0.045em | Default opening headline, with deliberate two-line composition. |
| display-italic | Mackinac | 500 italic | 64px | 1.15 | -0.045em | Emphasized phrase within the opening promise. |
| closing | Mackinac | 500 | 48px | 1.25 | -0.025em | Large conversion line; also suits a centered major product-section heading. |
| heading | Mackinac | 500 | 36px | 1.325 | -0.025em | Capability chapter headings and prominent proof figures. |
| body | Fricolage Grotesque | 325 | 19px | 1.5 | normal | Default narrative paragraph. |
| closing-action | Fricolage Grotesque | 500 | 19px | 1.5 | normal | Large translucent conversion action. |
| quote | Fricolage Grotesque | 450 | 19px | 1.5 | normal | Plain-spoken customer quotation with more weight than body copy. |
| hero-support | Fricolage Grotesque | 325 | 18px | 1.5 | normal | Concise supporting sentence in the first screen. |
| action | Fricolage Grotesque | 450 | 15.5px | 1.5 | normal | Default principal button label. |
| utility | Fricolage Grotesque | 450 | 14.5px | 1.5 | normal | Navigation, announcement copy and compact actions. |
| eyebrow | Fricolage Grotesque | 575 | 14.5px | 1.5 | 0.05em, uppercase | Small proof-section label, violet and centered. |
| footer-copy | Fricolage Grotesque | 325 | 14.5px | 24px | normal | Muted newsletter description. |
| attribution | Fricolage Grotesque | 575 | 14.5px | 1.5 | normal | Quote author role above a lighter organization description. |
| footer-label | Fricolage Grotesque | 575 | 12px | 1.5 | 0.05em, uppercase | Footer category and newsletter labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| technical product landing pages | product-display | Mackinac | 500 | 72px | 1.1 | -0.04em | Bigger, tighter two-line opening beside a live code example. |
| pricing pages | pricing-display | Mackinac | 325 | 60px | 1.25 | normal | Lighter, untracked pricing promise. |
| company and culture pages | culture-display | Mackinac | 500 | 60px | 1.25 | -0.025em | Centered white title over a painterly panorama. |
| editorial directories | directory-display | Mackinac | 500 | 44px | 1.25 | -0.025em | Centered heading on a dark introductory band. |
| pricing pages | pricing-heading | Mackinac | 325 | 36px | 1.325 | normal | Pricing table, support and reassurance headings. |
| editorial directories | story-title | Mackinac | 500 | 22.4px | 1.375 | -0.025em | Multi-line article-card heading. |
| technical product cards and FAQs | small-serif | Mackinac | 500 | 19px | 1.5 | -0.025em | Use-case card titles and FAQ questions. |
| pricing pages | plan-title | Fricolage Grotesque | 575 | 19px | 1.5 | normal | Plan and resource-category names. |
| editorial directories | story-copy | Fricolage Grotesque | 325 | 17px | 1.6 | normal | Three-line article excerpt. |
| pricing pages | compact-copy | Fricolage Grotesque | 325 | 14.5px | 1.4 | normal | Plan descriptions and comparison explanations. |
| code demonstrations | code-comment | ui-monospace | 325 | 12px | 1.5 | normal | Muted comments in a dark terminal. |
| editorial directories | story-meta | Fricolage Grotesque | 575 | 11px | 1.6 | 0.05em, uppercase | Byline and reading time separated by a fine rule. |

**Notes:**

- The serif does the expressive work; do not make every heading bold. Default narrative headings and figures share the 36px recipe.
- Serif tracking tightens to -0.045em in the main opening, while ordinary section headings use -0.025em. Body and action copy retain normal tracking.
- Keep the light 325 body weight visibly distinct from 450 actions and quotations. The pricing variant uses the lighter serif weight and normal tracking instead of inheriting the default headline styling.

## Layout

**Density:** Airy narrative chapters with compact, carefully ruled comparison content.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Action-to-icon gaps and tight form details. |
| 12px | Form gaps and compact explanatory stacks. |
| 16px | Heading-to-body spacing and standard card-grid gutters. |
| 20px | Logo-tile and editorial-card gutters. |
| 24px | Stat-grid gap, short content stacks and narrow panel margins. |
| 32px | Card padding and desktop container side padding. |
| 40px | Footer category gaps, team row gaps and major conversion alignment. |
| 64px | Two-column chapter gutter and heading-to-quote-grid separation. |
| 80px | Compact product chapters, footer top padding and comparison bands. |
| 96px | Closing-band vertical padding and practical page sections. |
| 128px | Default narrative-chapter vertical padding. |

### Containers and grids

- **container**: max width 1200px · side padding 32px. Centered default desktop shell; its inner width is 1136px at full size. Header, chapters and footer share alignment.
- **chapter split**: 2 columns · gap 64px. Two equal columns, usually a 536px text block opposite a smaller centered drawing; reverse the sides to create a conversational cadence.
- **reading column**: max width 576px. Maximum width for feature copy; supporting centered FAQ content uses a wider 768px column.
- **card grid**: 3 columns · gap 16px. Use-case and comparison cards; quote cards also use three equal columns.
- **editorial directory** (only for editorial directories): max width 1400px · 3 columns · gap 20px · side padding 32px. Wider article directory, with cards aligned in rows and a final incomplete row allowed.
- **comparison container** (only for pricing pages): max width 1152px · side padding 24px. Narrower practical layout; paired resource panels and a three-column support-plan band.
- **team directory** (only for company and culture pages): 3 columns · gap 32px. Three compact person rows across, with 40px vertical spacing rather than boxed profile cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions and navigation | 9999px (pill) |
|  | quote cards | 10px |
|  | large atmosphere panel | 20px |
|  | logo tiles | 16px |
|  | practical cards and fields | 8px |
| editorial directories | article cards | 16px |
| technical product landing pages | technical explainer | 24px |
| company and culture pages | portraits | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | atmosphere panel | `0px 2px 25px 0px rgba(0,0,0,0.1)` | Soft lift under the broad pastel proof panel. |
| editorial directories | article card | `0px 1px 4px 0px rgba(52,20,169,0.15)` | Tiny violet lift, not a large neutral drop shadow. |
| technical product landing pages | explainer panel | `0px 0px 0px 1px rgba(25,16,52,0.1), 0px 24px 70px -36px rgba(24,20,55,0.35)` | Deep but diffuse grounding beneath the large interactive explanation. |

### Surfaces

#### White narrative canvas · level 0

**Use:** Default chapter background.

**CSS:** `background: #ffffff`

**Observed:** A cool underlying canvas fades toward white; most middle-page chapters read as white rather than as individual cards.

**Transfer:** Keep the narrative open and reserve boxed material for evidence, comparisons and interaction.

#### Pastel seam light · level 0

**Use:** Atmospheric chapter boundaries.

**CSS:** `background: linear-gradient(to left, #7dd3fc, #a5b4fc, #f9a8d4); filter: blur(64px); transform: rotate(3deg)`

**Observed:** Oversized light strips extend beyond both viewport edges and dissolve into white, sometimes paired with a very low-opacity full-section wash.

**Transfer:** Place the strip behind content, clipped by the section, so the light is a transition rather than a colored box.

#### Violet showcase band · level 0

**Use:** Concentrated color chapter for compatibility or breadth.

**CSS:** `background: linear-gradient(to bottom right, #a02be4, #7c3aed, #4f46e5); color: #ffffff; padding: 128px 0px`

**Observed:** White text and translucent tiles sit over faint oversized linework; the color belongs to the whole band, not separate rainbow cards.

**Transfer:** Use one clear subject for the band and keep all marks reversed.

#### Pastel proof panel · level 1

**Use:** Large inset testimonial or proof destination.

**CSS:** `background: linear-gradient(135deg, rgba(125,211,252,0.22), rgba(249,168,212,0.18), rgba(125,211,252,0.22)); border: 1px solid #e6e0fe; border-radius: 20px; box-shadow: 0px 2px 25px 0px rgba(0,0,0,0.1); overflow: hidden`

**Observed:** Near-full-width panel inset 24px, with blue and pink pools around a pale center and a white halftone veil. It holds a centered heading, action and three quotes.

**Transfer:** Match the soft glow; exact stops are not essential. Keep center text clear and add the halftone on a separate decorative layer.

#### Closing violet stage · level 0

**Use:** The emphatic conversion flourish.

**CSS:** `background: linear-gradient(to bottom right, #8919c9, #6d28d9, #4338ca); color: #ffffff; overflow: hidden`

**Observed:** Dark, enlarged illustration linework shows through the saturated field; a mint phrase breaks the white heading.

**Transfer:** Use original low-contrast drawing as the backdrop, preserving the typography-first reading order.

#### Dark directory ground · level 0

**Use:** Footer and newsletter base.

**CSS:** `background: linear-gradient(to bottom right, rgba(18,18,38,0.5), rgba(34,24,60,0.5), rgba(25,16,52,0.5)), #191034; color: #a39ac1; padding: 80px 0px 32px`

**Observed:** A nearly black plum base, without loud glows, supports small white category labels and muted links.

**Transfer:** Let the previous conversion band be the bright final moment; make the directory a restful, useful ending.

#### Pale comparison band · level 0

**Only for:** pricing pages

**Use:** Support or plan comparisons.

**CSS:** `background: #f5f3ff; border-top: 1px solid #e7e6f4; border-bottom: 1px solid #e7e6f4; padding: 80px 24px`

**Observed:** White practical cards sit on the faint lavender field.

**Transfer:** Use this restrained variant for dense decisions rather than making practical content theatrical.

#### Dark editorial introduction · level 0

**Only for:** editorial directories

**Use:** Opening of a story library.

**CSS:** `background: linear-gradient(#121226, #281950); color: #ffffff; padding: 192px 0px`

**Observed:** Centered title and muted support on a 546px band; the first card row overlaps its lower boundary.

**Transfer:** Keep the introduction short and let the illustrated articles provide the visual variety.

## Components

### Floating navigation

**Use:** Main desktop wayfinding.

**CSS:** `display: flex; align-items: center; height: 44px; padding: 0px 12px; background: linear-gradient(to right, rgba(251,207,232,0.4), rgba(221,214,254,0.4), rgba(199,210,254,0.4)), rgba(255,255,255,0.75); border: 1px solid rgba(255,255,255,0.5); border-radius: 9999px; backdrop-filter: blur(24px); box-shadow: 0px 0px 0px 1px rgba(32,34,55,0.075), 0px 10px 15px -3px rgba(32,34,55,0.05), 0px 4px 6px -4px rgba(32,34,55,0.05)`

**Text style:** `utility` — Fricolage Grotesque 450 · 14.5px/1.5

**Observed:** The wordmark sits separately at left; a centered link capsule and a smaller right account capsule balance the 96px header. Account controls use adjoining rounded ends, with violet sign-up on the right. Dark editorial and culture openings use bare reversed navigation instead.

**States:** Declared: hover navigation links turn #7c3aed.

**Transfer:** Keep the capsule compact rather than stretching it from logo to account controls.

### Primary button

**Use:** Principal action on light chapters and the opening.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 48px; padding: 0px 20px; color: #ffffff; background: linear-gradient(to bottom right, #a02be4, rgba(0,0,0,0), #4f46e5), #7c3aed; border: 1px solid transparent; border-radius: 9999px; box-shadow: inset 0px 0px 0px 1px rgba(67,56,202,0.25)`

**Text style:** `action` — Fricolage Grotesque 450 · 15.5px/1.5

**Observed:** Short verb-led label followed by a small chevron. A plain secondary action can sit beside it with a copy or calculator icon. Practical pricing actions use 8px or 10px corners instead of the default pill.

**States:** Declared: hover color white; background-color #6d28d9; border-color rgba(255,255,255,0); inset shadow remains.

**Transfer:** Give each decision area one clear violet action.

### Announcement capsule

**Use:** Small timely message above the opening promise.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; height: 32px; padding: 4px 12px 4px 4px; background: rgba(255,255,255,0.7); color: #281950; border: 1px solid rgba(221,214,254,0.8); border-radius: 9999px; backdrop-filter: blur(4px)`

**Text style:** `utility` — Fricolage Grotesque 450 · 14.5px/1.5

**Observed:** A tiny solid violet badge leads the sentence; a right arrow closes it. The message truncates instead of growing to several lines.

**States:** Declared: hover background-color #ffffff; border becomes a stronger lavender.

**Transfer:** Use a real release or current announcement, with one short line.

### Glass conversion button

**Use:** Action on the saturated conversion stage.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; padding: 16px 32px; color: #ffffff; background: rgba(255,255,255,0.15); border-radius: 9999px; backdrop-filter: blur(4px); box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.3), 0px 10px 15px -3px rgba(0,0,0,0.2), 0px 4px 6px -4px rgba(0,0,0,0.2)`

**Text style:** `closing-action` — Fricolage Grotesque 500 · 19px/1.5

**Observed:** A full right arrow replaces the smaller chevron; the button sits opposite the large heading, not beneath a long paragraph.

**States:** Declared: hover background-color rgba(255,255,255,0.25).

### Reversed logo tile

**Use:** A grid of supported tools or compatible partners within a violet showcase.

**CSS:** `display: grid; place-items: center; padding: 32px 16px; background: linear-gradient(to bottom right, rgba(255,255,255,0.075), rgba(255,255,255,0.075), rgba(255,255,255,0.2)); border: 1px solid rgba(255,255,255,0.25); border-radius: 16px; color: #ffffff; box-shadow: 0px 5px 5px -2px rgba(91,33,182,0.1), 0px 2px 4px -2px rgba(91,33,182,0.1)`

**Observed:** Three columns of approximately 163px by 98px tiles, with monochrome white marks centered inside. No descriptive copy competes with the marks.

**States:** Declared: hover background-color rgba(255,255,255,0.1); border-color rgba(255,255,255,0.35).

**Transfer:** If no partner logos exist, use original single-color capability emblems with similarly varied silhouettes.

### Ruled stat

**Use:** Compact quantified proof beside a narrative block.

**CSS:** `display: flex; flex-direction: column; border-left: 2px solid #ddd6fe; padding: 16px 24px; color: #7c3aed`

**Text style:** `heading` — Mackinac 500 · 36px/1.325 · tracking -0.025em

**Observed:** The serif figure precedes a muted sans label. Four items form a two-by-two grid with 24px gaps and no enclosing card.

**Transfer:** Use substantiated short measures; preserve the small typographic scale rather than inflating figures to billboard size.

### Quote card

**Use:** Human proof within the pastel panel.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 32px; padding: 32px; background: rgba(244,243,251,0.75); border: 1px solid #d5cfef; border-radius: 10px`

**Text style:** `quote` — Fricolage Grotesque 450 · 19px/1.5

**Observed:** Quotation at top, role and organization anchored at bottom. Quotes have unequal lengths but the cards align in height. Attribution uses the attribution recipe and a lighter secondary line.

**Transfer:** Let honest, detailed language drive card height rather than adding oversized quote-mark ornaments.

### Newsletter field

**Use:** Name and email fields in the dark footer.

**CSS:** `height: 40px; padding: 8px 12px; background: #22183c; color: #ffffff; border: 1px solid #42385f; border-radius: 8px`

**Observed:** Two short fields and a compact violet Subscribe button share one row opposite the newsletter description, beneath a dark divider.

**Transfer:** Use visible labels or accessible names; retain the restrained rectangular field shape.

### Footer directory

**Use:** Useful final navigation and subscription destination.

**CSS:** `padding: 80px 0px 32px; background: linear-gradient(to bottom right, rgba(18,18,38,0.5), rgba(34,24,60,0.5), rgba(25,16,52,0.5)), #191034; color: #a39ac1`

**Text style:** `footer-copy` — Fricolage Grotesque 325 · 14.5px/24px

**Observed:** Wordmark left, five compact categories across the remainder. White uppercase labels lead muted link stacks. An inset divider introduces the newsletter row, followed by tiny centered copyright. The editorial-directory variant ends with a shorter plain blue-black directory and no newsletter row.

**States:** Declared: hover default footer links turn #8b5cf6.

**Transfer:** Preserve this directory ending even when the preceding conversion flourish moves elsewhere.

### Story card

**Only for:** editorial directories

**Use:** Illustrated editorial or customer narrative previews.

**CSS:** `display: flex; flex-direction: column; padding: 32px; background: #ffffff; border-radius: 16px; box-shadow: 0px 1px 4px 0px rgba(52,20,169,0.15)`

**Text style:** `story-title` — Mackinac 500 · 22.4px/1.375 · tracking -0.025em

**Observed:** A 416px by 256px illustration reaches to 8px from the card edge, with rounded corners. Beneath it: byline and read time linked by a hairline, serif title, three-line excerpt and violet Read more arrow. Text is more deeply inset than the image.

**Transfer:** Give each story its own colored illustration rather than using a uniform logo wall.

### Practical comparison card

**Only for:** pricing pages

**Use:** Plans and resource or assistance choices.

**CSS:** `display: flex; flex-direction: column; padding: 32px; background: #ffffff; border: 1px solid #e7e6f4; border-radius: 8px`

**Text style:** `plan-title` — Fricolage Grotesque 575 · 19px/1.5

**Observed:** A small whimsical illustration appears before a sans plan title, serif price, compact description and ruled checklist. Resource panels use a similar shell with dense aligned rate tables. Support plans are visually equal, not a giant highlighted middle card.

**Transfer:** Keep illustrations small enough that labels and rates remain the useful content.

## Imagery and graphics

### Pastel flight world

**Use:** Signature opening illustration and occasional decorative scene extensions.

**Observed:** An airy blue-to-lilac-to-pink sky fills the opening. A large purple anthropomorphic machine with wings and loose black contours leads a receding group of smaller creatures on the right. Ribbons, tiny birds, grain and soft blurred shapes animate the space behind the left copy. The picture is full bleed, with no browser frame or inset rectangle.

**Transfer:** Create an original personified object related to the new product, using imperfect perspective, flat pastel facets and expressive ink edges. Minimum acceptable version: one large original outlined object with two small companions, flowing colored ribbons and a textured pastel background.

**Build:** Layer a full-size pale blue sky over pale pink lower light using broad radial gradients. Draw a faceted object in SVG on the right third, with purple faces, off-white detail and dark plum irregular contours. Add three curving SVG paths in pink, sky blue and mint behind it, varying their thickness and opacity; scatter tiny bird-like V shapes and a fine low-opacity noise texture. Keep the left half low contrast for text.

### Capability vignettes

**Use:** Recurring visual companion to feature chapters.

**Observed:** Small, unframed colored drawings depict playful machines, creatures, storage containers and magical work scenes. Each sits around 384px wide, smaller than its text column, with white or near-white surroundings and minimal grounding shadow. Pastel purple, green, cyan and peach fills have visible sketch texture.

**Transfer:** Illustrate the effect or feeling of the capability rather than rendering a literal UI. Minimum acceptable version is a small original hand-drawn object with two or three pastel fills, irregular plum strokes and a few motion or sparkle marks.

**Build:** Use an SVG viewBox around 384 by 320, with a compact central group of irregular polygons and curved organic shapes. Give selected shapes offset double strokes and add sparse short hatch marks. Keep surrounding space empty and use a faint soft ellipse beneath the group instead of a hard card.

### Halftone light field

**Use:** Signature atmospheric proof panel and quieter technical surfaces.

**Observed:** Dense tiny white dots float over broad blue and pink light pools. In technical explanations, the dots become faint purple and fade away near the content. This is a printed, almost iridescent surface, not a starfield.

**Transfer:** Retain the combination of fine dot texture and soft broad color; do not substitute sharp geometric mesh art.

**Build:** Overlay two radial-gradient dot layers with 1.4px circles ending at 1.5px, on an approximately 6px staggered grid. Use white dots at opacity 0.6 over the pastel panel; for technical surfaces use purple dots at opacity 0.12 to 0.2 with a linear or radial fade mask. Place all dots behind text.

### Illustrated violet relief

**Use:** Signature saturated conversion-stage backdrop.

**Observed:** Large dark outlines of whimsical figures and machinery are enlarged until only fragments remain visible. The image blends into the purple field at low contrast, while the headline and action stay crisp.

**Transfer:** Reuse fragments of the new product's original illustration as relief texture, not a second competing hero.

**Build:** Place a monochrome plum SVG drawing behind the closing copy at full-band size, enlarged and clipped at edges. Apply an overlay blend at opacity 0.3, then add a blurred sky/periwinkle/pink light strip near an edge at opacity 0.5. Keep facial or mechanical linework broad enough to read as texture.

### Editorial cover art

**Only for:** editorial directories

**Use:** Images at the top of story previews.

**Observed:** Wide narrative illustrations vary from purple and orange ink scenes to underwater blues and dark painterly landscapes. Characters and metaphorical objects dominate, with rich color confined to the image window rather than tinting the whole card.

**Transfer:** Commission or draw distinct editorial metaphors for each narrative. A limited-color ink scene is preferable to repeating product logos.

### Painterly panorama

**Only for:** company and culture pages

**Use:** Emotional introduction before people or company information.

**Observed:** A full-width fantasy shoreline with sailboats, balloons, a crescent moon and futuristic buildings. Purple, pink and blue twilight provides a luminous but low-detail area behind centered white text; image is bottom aligned and covers the 639px introduction.

**Transfer:** Use an original panoramic landscape that suggests exploration or shared purpose; preserve a low-detail central text area, colored atmospheric depth and a readable horizon.

### Person row portraits

**Only for:** company and culture pages

**Use:** A compact team directory.

**Observed:** 90px circular portraits mix informal photos and illustrated avatars. A small circular location flag overlaps the lower-left edge; name, role and tiny muted social icons form a text block to the right.

**Transfer:** Use authentic portraits or chosen avatars consistently sized, not corporate stock headshots. Locality badges should represent genuine information rather than decoration.

### Icons

**Observed:** Controls use tiny arrows and chevrons, usually 11px to 16px; copy-style utility icons are 16px with 2px round strokes. Social and partner symbols are solid silhouettes at 20px to 24px. Violet marks and checks punctuate otherwise muted text.

**Transfer:** Use simple rounded-stroke utility icons beside text and recognizable monochrome silhouettes for external destinations. Keep expressive character drawing separate from functional icons.

## Section recipes

How recurring sections are built.

### First screen: Illustrated promise opening

**Observed:** A full-bleed illustrated sky fills an 804px-tall stage beneath an overlaid 96px header. Back to front: pastel sky and grain, distant companions and ribbon paths, the large right-hand character, then left-aligned text and glass navigation. The copy starts well below the header, centered in the left portion rather than vertically pinned to the top. A 32px Announcement capsule precedes a 64px two-line serif promise; the lower phrase is italic with a loose colored underline. The headline spans roughly half the viewport, while the main character occupies the right third and almost the full stage height. A single 18px support line leads to a 48px Primary button and a muted icon-led alternative. Within 900px, the complete navigation, announcement, promise, supporting line, both actions and the main drawing are visible; only the atmospheric beginning of the next chapter appears below the stage.

**Transfer:** Keep this as the default landing-page composition: original storybook object right, literary promise left, and an airy illustrated world connecting them. Without artwork, construct the minimum outlined-object and flowing-ribbon scene in Pastel flight world. Technical products can instead open with the larger product-display recipe opposite an actual terminal; pricing uses a 60px lighter promise over a related sky illustration; editorial directories use the centered dark introduction; culture introductions use a painterly panorama.

**Avoid:** Do not replace the stage with a centered text stack over a generic gradient or put the illustration inside a rounded screenshot card. Do not let a long heading collide with the focal object.

**Text style:** `display` — Mackinac 500 · 64px/1.15 · tracking -0.045em

### Alternating capability chapter

**Observed:** White narrative canvas with 128px vertical padding and the chapter split layout. A heading and paragraph are separated by 16px; one or two brief checklist lines and a Primary button can follow. The unframed Capability vignette is centered in the opposing column, and successive chapters reverse sides. Pastel seam light sometimes bridges the boundary.

**Transfer:** Choose a small number of distinct user outcomes and pair each with a visual metaphor rather than making every feature a card.

**Text style:** `heading` — Mackinac 500 · 36px/1.325 · tracking -0.025em

### Saturated breadth showcase

**Observed:** Violet showcase band pairs a white heading and light support paragraph on the left with a three-by-three grid of Reversed logo tiles on the right. The tile grid has 20px gutters; the split has an 80px gap. A translucent secondary action follows the paragraph.

**Transfer:** Use to demonstrate compatibility, breadth or a family of capabilities. If no logos apply, use original monochrome emblems instead of inventing partnerships.

**Text style:** `heading` — Mackinac 500 · 36px/1.325 · tracking -0.025em

### Ruled quantitative proof

**Observed:** Narrative copy occupies one half; a two-by-two grid of Ruled stat components occupies the other. Figures use the same 36px serif as chapter titles, with violet rather than larger size providing emphasis.

**Transfer:** Pair a growth or reliability promise with a few substantiated, readable measures.

**Text style:** `heading` — Mackinac 500 · 36px/1.325 · tracking -0.025em

### Inset human proof

**Observed:** Pastel proof panel sits 24px from viewport edges. Centered heading, short support and compact action precede a quote grid by 64px. Three Quote cards sit on the Halftone light field with 16px gutters; attribution blocks align at the bottom.

**Transfer:** Use the panel for voices, evaluation results or detailed proof. Keep the soft field and small-pattern texture even when the proof format changes.

**Text style:** `heading` — Mackinac 500 · 36px/1.325 · tracking -0.025em

### Conversion flourish and directory

**Observed:** Closing violet stage is 312px tall with 96px vertical padding. A two-line 48px heading sits left, its final phrase mint; Glass conversion button sits right. Illustrated violet relief covers the background. The Footer directory follows with white labels, muted links and the newsletter row. In technical product pages this flourish can precede FAQs and a smaller trial invitation rather than being the last content block.

**Transfer:** Use a short actionable conclusion and retain the theatrical violet-and-mint device somewhere meaningful. Let page purpose determine its position; finish with a useful directory, not an abrupt color stop.

**Text style:** `closing` — Mackinac 500 · 48px/1.25 · tracking -0.025em

### Practical pricing explanation

**Only for:** pricing pages

**Observed:** The lighter serif opening gives way to a 36px heading, underlined resource tabs and two equal outlined resource panels with rate rows. A pale calculator callout spans below. Pale comparison band holds three Practical comparison cards. A centered reassurance block uses a small illustration and pill badges; two outlined invitation cards then lead directly into Footer directory without another large violet call.

**Transfer:** Separate resource costs, assistance choices and reassurance instead of compressing all decisions into a single giant pricing table.

**Text style:** `pricing-heading` — Mackinac 325 · 36px/1.325

### Technical product explanation

**Only for:** technical product landing pages

**Observed:** A 72px two-line promise and underlined phrase face a dark 654px-wide terminal with code-language tabs, operating-system controls and copy affordances. Below, a 1136px-wide, 24px-rounded explainer splits a 473px tinted numbered rail from detailed content. White three-column illustrated use-case cards, an integration strip, a three-column rate panel and two worked invoice cards build concrete understanding. FAQs use a centered 768px column with fine horizontal rules and a Show more pill.

**Transfer:** Use real executable steps and clear worked examples. Let mono stay within the demonstration while marketing headings remain serif.

**Text style:** `product-display` — Mackinac 500 · 72px/1.1 · tracking -0.04em

### Editorial directory

**Only for:** editorial directories

**Observed:** Dark editorial introduction carries a centered 44px title and short support. A three-column grid of Story cards begins across the lower edge, then continues on lavender canvas with 20px gutters. The final row may contain one card; 96px of breathing room precedes a compact dark directory footer without subscription fields.

**Transfer:** Use the wider container for a browsable collection and preserve the natural last row instead of adding filler cards.

**Text style:** `directory-display` — Mackinac 500 · 44px/1.25 · tracking -0.025em

### Panorama and people

**Only for:** company and culture pages

**Observed:** Painterly panorama supports a centered 60px white heading and short introductory paragraph. White content begins cleanly beneath it; an uppercase violet label introduces the three-column Person row portraits directory, with 96px vertical container padding. After the final real person row, the standard newsletter Footer directory closes the page.

**Transfer:** Make the company introduction emotional and the people information compact and authentic; the people need not become promotional cards.

**Text style:** `culture-display` — Mackinac 500 · 60px/1.25 · tracking -0.025em

## Page flow

**Storyline:** promise → concrete capabilities or demonstration → breadth and proof → decision support → an invitation → useful directory

### Broad product marketing landing page

1. **promise** — Illustrated world, expressive serif promise, brief support and primary plus utility actions.
2. **capability chapters** — Alternating unframed drawings and concise text; one concentrated violet breadth showcase.
3. **quantified and social proof** — Ruled figures, moving logo strip and practical reassurance checklist.
4. **human proof** — Large pastel halftone panel containing detailed quotes.
5. **closing call** — Violet-and-mint conversion stage followed by dark newsletter directory.

**Transfer:** Use the full expressive language for a general product introduction, adjusting the number and order of chapters to the actual product.

### Technical product landing page

1. **promise and demonstration** — Contrarian two-line headline beside a functional terminal.
2. **mechanism** — Numbered split explainer with an active feature and detailed text.
3. **use cases and compatibility** — Illustrated use-case cards and a compact integration-symbol strip.
4. **pricing** — Rate panel plus two worked cost examples with ruled rows and serif totals.
5. **closing call** — Illustrated violet contact invitation.
6. **objection handling** — FAQ rows and a separate compact trial-credit invitation with tiny decorative cross-diamond-cross separator.
7. **directory** — Standard dark footer with newsletter.

**Transfer:** Make the demonstration and cost reasoning concrete; a strong invitation can appear before objections, with a smaller action after them.

### Transparent pricing and purchase evaluation

1. **promise** — Illustrated sky with a restrained 60px serif pricing promise.
2. **pricing** — Tabs, paired rate panels, aligned rows and a calculator callout.
3. **decision support** — Three equal assistance-plan cards in a lavender band.
4. **reassurance** — Centered certification or policy package with illustration, badges and compact action.
5. **alternative paths** — Two invitation cards for exceptional needs.
6. **directory** — Standard dark newsletter footer; no additional conversion banner.

**Transfer:** Keep practical detail readable and let small illustrations supply personality rather than adding a decorative upsell at every turn.

### Editorial proof library

1. **orientation** — Centered title on dark plum with a short explanation.
2. **social proof** — Overlapping first row leads into a wide illustrated story-card collection.
3. **directory** — The incomplete final card row and generous breathing room lead to a shorter dark footer without newsletter.

**Transfer:** Treat this as an editorial catalog, not a second sales landing page; the stories carry the persuasion.

### Company identity and people

1. **orientation** — Centered white introduction over a painterly fantasy panorama.
2. **human proof** — Compact portrait, name, role, locality and social links in an open three-column directory.
3. **directory** — After the last people row, the standard dark newsletter footer.

**Transfer:** Lead with a clear personality statement, then make real people easy to scan. Do not pad the ending with invented company-value sections.

## Writing

A capable engineer with an illustrator's sense of fun: direct, informal and occasionally mischievous, but willing to explain exactly how a thing works. Benefits sound human; operational details are concrete.

**Do not copy:** Do not reuse Fly.io names, mascots, logos, framework or customer marks as endorsements, exact commercial offers, performance claims, customer quotations, employee identities or proprietary illustrations. Write original claims and examples supported by the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Use we for the makers, contractions naturally, and product names when explaining mechanisms rather than repeating a slogan.
- **Rhythm:** Short benefit-led headings alternate with two or three explanatory sentences. A plain factual statement can be followed by a conversational aside. Action labels are usually two to four words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An immediate verb or a pointed challenge to the existing category. | 2–8 words | “Launch”<br>“Sandboxes aren't enough” |
| Supporting line | Name the audience and desired outcome in everyday language. | One short sentence | “The platform for devs and agents who just want to ship.” |
| Chapter heading | A benefit with a small human metaphor, not a feature taxonomy. | 3–7 words | “Grow Without Drama”<br>“Storage That Keeps Up” |
| Mechanism | Explain actual behavior, then a memorable consequence. | Two to four sentences | “Real hardware-isolated Linux computers for agents, evals, and tools. The bill goes to zero when nobody's home.” |
| Action | Verb plus the thing the reader gets or does. | 2–4 words | “Deploy your app”<br>“Calculate your cost” |
| Informal aside | A brief conversational wink after useful information. | One short sentence | “Works with your agent. Yes, that one too.”<br>“Create, like, 500 Sprites free.” |
| Newsletter invitation | Describe what the makers actually share, with understated humor. | One or two short sentences | “What we shipped, what we learned, like ... stuff you put in a newsletter. Get it monthly.” |

**Words and phrasing to use:** ship; run; build; your team; keeps up; no problem; here's what it costs; real; like; when you need it

**Avoid:** revolutionary ecosystem; unlock limitless potential; synergize; enterprise-grade as an unexplained promise; frictionless everything; overly formal purchasing language

**Rules:**

- Pair a playful heading with a concrete explanation; humor must not replace product meaning.
- Name billing units, constraints and lifecycle behavior when they matter to the reader.
- Use real questions as FAQ labels, including awkward practical problems.
- Make the utility action literal; save the more playful phrasing for supporting copy.
- Keep quoted proof in the speaker's own cadence rather than polishing it into slogans.

## Do's and Don'ts

### Do

- Use the 64px serif promise with a whole italic phrase and a loose underline.
- Align default chapter content to the 1200px shell with 32px side padding.
- Let 128px chapter padding and 64px split gutters create the rhythm before adding dividers.
- Keep most narrative backgrounds white; concentrate vivid violet into showcase and conversion bands.
- Use 48px pill actions by default, retaining compact rectangular variants for practical pricing content.
- Keep proof figures at 36px and distinguish them with violet and a 2px lavender rule.
- Stage drawings at roughly 384px wide without UI frames in alternating chapters.
- Make the footer useful with compact white uppercase labels, muted lavender links and restrained 40px dark fields.

### Don't

- Do not substitute a bold geometric sans for the literary headline or make the 325-weight body look semibold.
- Do not turn every chapter into a pastel rounded card; the large 20px atmosphere panel is a distinct proof destination.
- Do not use fluorescent gradients on every button and table row; violet actions sit within predominantly light content.
- Do not use glossy metallic 3D or generic isometric SaaS dashboards in place of textured ink drawings.
- Do not enlarge small stat figures to 100px; the proof is intentionally integrated with section typography.
- Do not put pale lavender body text on white; use the soft plum body tone and save light lavender for dark ground.
- Do not force all controls to share a pill shape; footer fields and practical cards have 8px corners.
- Do not extend mono type into prose or navigation; its role is technical demonstration.
- Do not add a violet sales banner to every page ending; practical and editorial page types have quieter directory endings.

## Motion and responsive

### Motion

**Observed:**

- Declared principal-button transition is 0.2s; navigation uses 300ms cubic-bezier(0.4,0,0.2,1) across color, opacity, shadow and transform-related properties.
- Declared opening phrase changes use opacity and translate over 300ms cubic-bezier(0,0,0.2,1), with reduced-motion transition suppression.
- Declared logo strips use infinite-scroll 60s linear infinite.
- Declared conversion-button transition is all 150ms cubic-bezier(0.4,0,0.2,1).

**Transfer:**

- Keep the opening's changing phrase within a stable typographic composition so its underline and actions do not jump.
- Use slow, continuous movement for repeated proof marks rather than rapid carousel paging; the rest of the page should remain readable.

**Unknown:**

- Exact illustration animation behavior and all scroll-entry sequencing are unspecified.

### Responsive

**Observed:**

- Declared breakpoints include 480px, 640px, 768px, 1024px, 1200px and 1400px, with additional wide-screen rules.
- Default container classes move side padding from 16px to 24px to 32px; split chapters become columns at desktop.
- Use-case grids declare one, two and three columns; the people directory declares two columns before three; editorial cards declare two columns before three.
- Desktop capsule navigation is hidden below its large-screen layout.

**Transfer:**

- On narrow screens, put the literary promise before the drawing, preserve a reduced illustrated sky and keep ribbon paths behind rather than across small text.
- Stack chapter copy and vignettes without introducing new card shells; reduce 128px chapter spacing before shrinking body type.
- Stack conversion copy and action while preserving white-and-mint contrast; allow practical tables to remain aligned within a readable narrow region.

**Unknown:**

- Exact narrow-screen art direction, navigation replacement and type sizes are not established. Responsive transfer statements are implementation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
