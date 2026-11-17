# Chronicle — outcomes on a stage

## Overview

A light, gallery-like software style that makes finished work feel more important than the tool itself. A pale gray and near-black shell, tightly set regular grotesk type, and small rectangular actions surround oversized interface scenes and richly varied output examples. It suits professional creative tools and business products whose value is best explained through the quality of what people make; the overall density is low, with compact controls inside expansive chapters.

### Essentials

- Headlines speak at conversational weight, not billboard boldness: Diatype 54px/1.05, weight 400, -0.03em tracking; major section titles use 48px with the same proportions.
- The opening is a deliberately unequal product stage: a short left promise occupies roughly two fifths, while a large framed interface runs off the right edge; a 54px navigation bar and a 607px hero leave room for proof within the first 900px.
- Actions are compact black rectangles, never pills: 4px corners, white 14px medium labels, 36px ordinary height and 44px closing-action height.
- The marketing shell stays almost entirely neutral: #f3f3f3 canvas, #050505 headlines, muted black at 56% for support, and #e2e2e2 hairlines. Strong color belongs inside bounded product examples or comparison artwork, not across the page.
- Finished work is the signature visual proof: large landscape examples, fine borders, 4px corners, partial adjacent slides, and a soft shadow on the active example. Without ready-made media, compose a believable finished artifact plus a small editing overlay rather than a generic illustration.
- Subtle material and linework anchor the page: a vertical #e1e1e1-to-#ebe7e6 gradient supports workflow and quote cards, and a faint, vertically striped field sits behind the closing navigation. Retain both devices somewhere in a new composition.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action black | `#000000` | `--color-action` | action, text | Primary action fill, active workflow text, and selected direct statements. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | surface, text | Pricing cards, finished output sheets, and labels on black actions. |
| Pale gray canvas | `#f3f3f3` | `--color-canvas` | background, surface | Continuous page and header background; also the resting fill of outlined plan actions. |
| Warm stone | `#ebe7e6` | `--color-gradient-bottom` | surface | Lower end of the workflow and testimonial gradient. |
| Hairline gray | `#e2e2e2` | `--color-edge` | border | Header bottom edge, logo cells, outlined cards and FAQ rows. |
| Cool stone | `#e1e1e1` | `--color-gradient-top` | surface | Upper end of the workflow and testimonial gradient; small carousel-control fill. |
| Structural gray | `#b3b3b3` | `--color-divider` | border | Stronger horizontal and vertical feature-grid rules. |
| Inactive gray | `#929292` | `--color-inactive` | text | Visible inactive workflow tone; black at 40% over the canvas, becoming slightly darker on the stone panel. |
| Support gray | `#6b6b6b` | `--color-muted` | text | Visible support tone; black at 56% opacity over the pale gray canvas. |
| Link ink | `#151515` | `--color-link` | link, text | Footer navigation, darker than supporting prose. |
| Headline ink | `#050505` | `--color-ink` | text, accent | Headlines, small outline icons, and dark badges. |

## Typography

- **Diatype** — All marketing headings, prose, navigation and actions. Compact neo-grotesk with regular-weight headlines and modest medium-weight controls. If unavailable, use **Inter**. Use 400 and 500; preserve tight tracking and check headline wrapping. Font stack: "Diatype", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Diatype | 400 | 54px | 1.05 | -0.03em | fixed | Opening promise; centered page title on pricing. |
| heading-lg | Diatype | 400 | 48px | 1.05 | -0.03em | fixed | Major visual chapters, proof headings, and FAQ titles. |
| heading | Diatype | 400 | 32px | 1.1 | -0.03em | size clamp(2.4rem, 2.13rem + 0.83vw, 3.2rem) | Workflow selectors, closing invitation and plan prices. |
| feature-title | Diatype | 400 | 20px | 1.2 | -0.02em | size clamp(1.4rem, 1.2rem + 0.63vw, 2rem) | Feature labels, gallery captions, and plan names. |
| question | Diatype | 400 | 20px | 1.4 | -0.02em | size clamp(1.8rem, 1.73rem + 0.21vw, 2rem) | Accordion questions. |
| body | Diatype | 400 | 16px | 1.4 | -0.02em | size clamp(1.4rem, 1.33rem + 0.21vw, 1.6rem) | Supporting paragraphs, eyebrows, quotes, lists and footer links. |
| navigation | Diatype | 500 | 14px | 1.4 | -0.02em | fixed | Header navigation and login. |
| button | Diatype | 500 | 14px | 1 | -0.023em | fixed | Closing and plan action labels. |
| header-button | Diatype | 500 | 14px | 1 | -0.02em | fixed | Compact header conversion action. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| use-case and educational landing pages | article-heading | Diatype | 400 | 28px | 1.05 | -0.03em | fixed | Narrow-column explanatory chapter headings. |
| educational landing pages | benefit-card-heading | Diatype | 400 | 24px | 1.4 | -0.02em | size clamp(1.6rem, 1.33rem + 0.83vw, 2.4rem) | Text-led gradient benefit cards. |
| educational landing pages | article-subheading | Diatype | 400 | 24px | 1.1 | -0.03em | fixed | Individual capabilities inside long-form explanatory chapters. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use weight and size sparingly: headings remain 400 even when making a strong claim; medium weight is mostly reserved for controls.
- Display tracking is -0.03em while body and compact titles use -0.02em. Do not replace the tight regular headline with a heavy geometric display face.
- Eyebrows are ordinary sentence-case body text, not uppercase technical labels. Supporting copy remains visibly subordinate through gray color rather than tiny type.

## Layout

**Density:** Airy chapters with compact, workmanlike navigation and actions; the large gaps make the finished artifacts feel exhibited.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Explains most section and component spacing; local type-driven offsets remain independent.
- **horizontal step** 6px, horizontal — Common alignment step for 12px, 24px, 30px and 60px spacing; 16px pricing gutters are a separate variant.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Icon-to-title gaps and footer-list gaps. | fixed |
| 16px | FAQ row gaps and pricing grid gutters. | fixed |
| 20px | Title-to-support or closing-title-to-button separation. | clamp(1.6rem, 1.47rem + 0.42vw, 2rem) |
| 24px | Quote-card padding, workflow column gap and gallery slide separation. | fixed |
| 30px | Container side padding. | fixed |
| 32px | Narrow article chapter breaks and landscape-preview breathing room. | fixed |
| 48px | Proof strip top padding and feature-to-art separation. | clamp(2.4rem, 1.6rem + 2.5vw, 4.8rem) |
| 60px | Workflow panel inner padding. | clamp(1.6rem, 0.13rem + 4.58vw, 6rem) |
| 128px | Separation between major chapters. | clamp(9.6rem, 8.53rem + 3.33vw, 12.8rem) |
| 170px | Air above and below the centered closing invitation. | clamp(14rem, 13rem + 3.13vw, 17rem) |

### Containers and grids

- **main container**: max width 1212px · side padding 30px. Centered desktop shell with 1152px of inner content at a 1440px window.
- **workflow grid**: 2 columns · gap 24px. Equal square visual and text selector columns inside the inset gradient panel.
- **logo rail**: 6 columns · gap 0px. One contiguous ruled row of equal-width customer marks.
- **feature row**: 4 columns · gap 48px. Compact supporting capabilities beneath two large illustrated feature columns.
- **faq column**: max width 912px · gap 16px. Centered accordion stack, narrower than visual chapters.
- **reading column** (only for use-case and educational landing pages): max width 640px. Centered single-column prose and inline demonstration art.
- **pricing container** (only for pricing pages): max width 1600px · 4 columns · gap 16px · side padding 30px. Expanded comparison grid; 333px-wide equal-height cards at desktop.

## Corner radius

| Element | Radius |
| --- | --- |
| cards and actions | 4px |
| carousel controls | 2px |
| header link hit areas | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| active output preview | `0px 3px 32px 0px rgba(5, 5, 5, 0.2)` | Lift the active landscape preview, not every card. |
| quote avatar | `0px 2.3px 32px 0px rgba(5, 5, 5, 0.16)` | Small square author portraits on gradient quote cards. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous marketing shell.

**CSS:** `background: #f3f3f3; color: rgba(0, 0, 0, 0.56)`

**Observed:** Header, chapter backgrounds and footer share one pale gray rather than alternating contrasting bands.

**Transfer:** Keep the shell neutral so the content inside the product examples can vary.

#### Stone gradient · level 1

**Use:** Workflow panel, testimonial cards and text-led benefit cards.

**CSS:** `background: linear-gradient(#e1e1e1, #ebe7e6); border-radius: 4px`

**Observed:** The gradient is restrained and vertical, with a faint warm shift at the base; it is not a saturated mesh.

**Transfer:** Use as a bounded backing, not as a full-page ambient wash.

#### Outlined panel · level 1

**Use:** FAQ rows, previews and comparison frames.

**CSS:** `border: 1px solid #e2e2e2; border-radius: 4px`

**Observed:** Fine edges organize content without thick framing or obvious elevation.

**Transfer:** Let media or the continuous canvas supply the interior fill.

#### White plan sheet · level 1

**Only for:** pricing pages

**Use:** Plan comparison cards.

**CSS:** `background: #ffffff; border: 1px solid #e2e2e2; border-radius: 4px`

**Observed:** All plans share the same white material; recommendation is a small dark badge rather than a colored card.

**Transfer:** Make hierarchy through labels, not a loud featured-plan surface.

## Components

### Fixed header

**Use:** Persistent wayfinding and one compact conversion action.

**CSS:** `position: fixed; height: 54px; background: #f3f3f3; border-bottom: 1px solid #e2e2e2; z-index: 999`

**Text style:** `navigation` — Diatype 500 · 14px/1.4 · tracking -0.02em

**Observed:** A centered main container aligns the brand left, six short category links in the middle and login plus a black action right. Link hit areas have 12px side padding and 8px corners; the action is 36px high.

**States:** Declared: hover navigation color rgb(0,0,0); active outline 0px. Focus-visible styling is unspecified.

**Transfer:** Use a small symbol or compact wordmark so the centered navigation remains light.

### Primary button

**Use:** Main conversion and closing invitation.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #000000; color: #ffffff; border: 1px solid transparent; border-radius: 4px; height: 44px; padding: 0px 24px`

**Text style:** `button` — Diatype 500 · 14px/1 · tracking -0.023em

**Observed:** The closing version inserts a small white brand symbol between the verb and product name. Ordinary header and hero actions use the compact 36px variant. Secondary hero action is plain text beside the black button.

**States:** Declared: hover outline 0px; active outline 0px. Focus-visible styling is unspecified.

**Transfer:** Keep the label short and the rectangle content-sized.

### Logo cell

**Use:** Compact trust strip under the opening.

**CSS:** `height: 80px; border-right: 1px solid #e2e2e2`

**Observed:** Six equally sized cells sit within a top, bottom and left outer rule. Marks are small, monochrome and low contrast; a single gray proof sentence sits above the rail.

**Transfer:** Use genuine customer or partner marks at comparable optical sizes.

### Workflow panel

**Use:** Explain a small set of sequential capabilities through one changing scene.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr; gap: 24px; padding: 60px; background: linear-gradient(#e1e1e1, #ebe7e6); border-radius: 4px`

**Text style:** `heading` — Diatype 400 · 32px/1.1 · tracking -0.03em

**Observed:** Left is a square photographic scene carrying a floating interface. Right is a stack of four large text selectors; active is black, inactive muted. Supporting copy and a thin progress line sit at the bottom, far from the selector list.

**Transfer:** Show input, transformation and output as succinct verbs; match each selector to an actual product scene.

### Quote card

**Use:** User proof in a horizontally clipped carousel.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; width: 368px; height: 468px; padding: 24px; background: linear-gradient(#e1e1e1, #ebe7e6); border-radius: 4px`

**Text style:** `body` — Diatype 400 · 16px/1.4 · tracking -0.02em

**Observed:** Customer mark at top, short black quote around the middle, author portrait and two-line identity at bottom. Portraits are 50px squares with 4px corners; adjacent cards are separated by 24px.

**Transfer:** Use specific lived outcomes rather than oversized decorative quotation marks.

### Output preview

**Use:** Display finished work in a gallery carousel.

**CSS:** `border: 1px solid #e2e2e2; border-radius: 4px; box-shadow: 0px 3px 32px 0px rgba(5, 5, 5, 0.2)`

**Observed:** The active landscape output is about 822px by 463px; another output peeks in from the right. Beneath it sit a short category title, a one-line caption and paired 32px square arrows with 2px corners.

**Transfer:** Keep a readable artifact at near-landscape proportions and show continuity into the next example.

### FAQ row

**Use:** Objection handling without visual noise.

**CSS:** `border: 1px solid #e2e2e2; border-radius: 4px; display: flex; flex-direction: column`

**Text style:** `question` — Diatype 400 · 20px/1.4 · tracking -0.02em

**Observed:** A 912px-wide stack uses 16px gaps. Each closed row is 78px high; the button has 24px padding and a small right-pointing chevron before the question with a 10px gap. Answers use body text below the trigger, not a separate floating card.

**Transfer:** Start with collapsed questions and keep the question color as subdued as the surrounding prose.

### Footer link

**Use:** Three understated navigation columns in the closing area.

**CSS:** `color: #151515; padding: 8px 0px; transition: color 0.2s linear`

**Text style:** `body` — Diatype 400 · 16px/1.4 · tracking -0.02em

**Observed:** Links have no visible underlines or column-heading hierarchy. A large empty interval separates the centered call to action from the brand-left, links-right footer row.

**States:** Declared: hover color rgb(0,0,0), outline 0px; active outline 0px. Focus-visible styling is unspecified.

**Transfer:** Group product, company/help and social destinations while keeping the labels visually equal.

### Plan card

**Only for:** pricing pages

**Use:** Compare paid and free tiers on equal footing.

**CSS:** `background: #ffffff; border: 1px solid #e2e2e2; border-radius: 4px; padding: 20px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `body` — Diatype 400 · 16px/1.4 · tracking -0.02em

**Observed:** Plan name, 32px price with small billing suffix, one-line tier context, checkmarked feature list and bottom-aligned full-width action. Cards are 635px tall at desktop. A small black recommendation badge sits near the upper right; all four plan actions share the outlined treatment.

**Transfer:** Use equal card heights and align conversion controls even when feature counts differ.

### Plan button

**Only for:** pricing pages

**Use:** Tier selection at the bottom of plan cards.

**CSS:** `height: 36px; background: #f3f3f3; color: #000000; border: 1px solid #e2e2e2; border-radius: 4px; display: flex; justify-content: center; align-items: center`

**Text style:** `button` — Diatype 500 · 14px/1 · tracking -0.023em

**Observed:** Spans the card interior rather than shrinking to label width. Separate sales and demo calls use the black action.

**States:** Declared: hover background rgb(255,255,255), outline 0px; active outline 0px. Focus-visible styling is unspecified.

## Imagery and graphics

### Oversized interface stage

**Use:** Signature first-screen visual on marketing and use-case openings.

**Observed:** A pale gray editor frame contains a crisp white or dark finished artifact, tiny tool controls and occasional collaboration cursors. Its fine white rim and soft surrounding shadow separate it from the canvas. The right edge dissolves into the background; a restrained row of category tabs sits below. The scene occupies more space than the headline.

**Transfer:** Create a real-looking output of the new product, then add only enough surrounding chrome to establish its editing context. Minimum version: one polished artifact, a slim toolbar, a pair of collaborator indicators and a cropped right edge.

**Build:** Use an oversized landscape frame on the right, pale gray backing, a thin white inset rim and a soft low-opacity black shadow. Place the output sheet inside with generous internal margins. Overlay a right-edge gradient from transparent to the canvas and a faint vertical-line field beneath the stage; keep labels and cursors tiny relative to the artifact.

### Photographic workflow collage

**Use:** Square scene within the Workflow panel.

**Observed:** A muted blue-sky city street photograph fills the square. A white prompt panel floats centrally over it, with document chips, small controls and a dark submit square; miniature file sheets overlap the lower edge. The photograph supplies atmosphere while the interface supplies the explanation.

**Transfer:** Choose one grounded photographic setting with low saturation and overlay a small purposeful UI task. The minimum version is a photo, one white task panel and two overlapping input/output cards.

**Build:** Fill the square with an object-fit cover photograph, slightly darkened for separation. Center a white rounded panel at roughly four fifths of the photo width. Layer two small document cards below it with slight opposing rotations and subtle shadows; keep their color limited to file-type marks.

### Finished-output gallery

**Use:** Template, workflow and audience proof.

**Observed:** Landscape slides mix editorial photography, large typographic statements, grids, charts and occasional vivid blue, orange, green or cyan. They remain flat finished documents, not perspective device mockups. The gallery overflows horizontally; active work is lifted with the Output preview treatment.

**Transfer:** Design outputs that reflect the new product's actual value. Keep their own palettes inside the document bounds and let them demonstrate variety without recoloring the marketing shell.

### Before and after artwork

**Use:** Visual quality comparison chapter.

**Observed:** A wide comparison frame is split vertically: one side has a highly detailed green leaf photograph behind a white analytic sheet, the other a pale peach and pink field behind a softer diagram. A small circular handle marks the split. The color is intense but confined to this media block.

**Transfer:** Contrast two treatments of the same underlying content at the same scale. Use a detailed natural backing against a softer light backing; retain a clear draggable dividing line rather than two unrelated cards.

**Build:** Stack two equal-sized scene layers in a 1152px-wide landscape frame. Clip the upper scene at 50% width. For the softer scene, layer peach and pale pink radial gradients behind a white document. Add a centered white circular divider handle with a two-direction arrow; use an actual botanical texture for the detailed side.

### Fading vertical line field

**Use:** Signature decoration behind the footer links and beneath the product stage.

**Observed:** Fine pale vertical lines become more visible toward the lower middle of the footer, fading away at the top and sides. They never overpower labels or turn the footer into a separate dark band.

**Transfer:** Retain this lightweight optical texture even when the new brand has no illustrative assets.

**Build:** Make an absolutely positioned SVG or repeating-linear-gradient with 1px gray vertical strokes spaced about 8–12px apart. Use low opacity and mask it with a vertical transparent-to-visible gradient plus horizontal edge fades. Keep the canvas visible through it and place all navigation above it.

### Inline educational demonstration

**Only for:** educational landing pages

**Use:** Explain features inside a narrow prose column.

**Observed:** A 640px-wide image area holds a smaller centered slide and floating editing menu, often with blue data or a soft warm halo. The media has much more breathing room than a dense tutorial screenshot.

**Transfer:** Use one focused editing interaction per image, framed with ample surrounding light space rather than a full application window.

### Icons

**Observed:** Small near-black line icons accompany features and controls, typically 20px with 1.5px rounded strokes. FAQ chevrons are narrow; plan checkmarks use an 18px footprint. Navigation relies on words rather than icon-heavy badges.

**Transfer:** Choose simple open-outline arrows, checks and tool symbols with matching optical weight. Keep solid marks limited to a brand symbol or a small action detail.

## Section recipes

How recurring sections are built.

### First screen: Unequal product-stage opening

**Observed:** The pale Canvas sits behind a Fixed header and a 607px hero, beginning after about 100px of top breathing room. Within the main container, a left text column takes roughly two fifths and is vertically centered against the large right stage. The 54px regular headline wraps to two or three lines; muted body support spans two or three shorter lines, followed by a black compact action and a plain video link. The oversized interface begins high on the right and extends beyond the content edge, with a soft white rim, gray backing and a fading right side. Category tabs sit underneath it. Within the first 900px, the header, full promise, support, actions, main object, category labels and the six-cell trust rail are visible. The workflow chapter starts below the fold.

**Transfer:** Keep the unequal relationship and show a convincing finished result, not a generic dashboard. If no media exists, assemble the minimum Oversized interface stage around one carefully designed output. Audience and educational openings reuse this composition with tailored copy and examples; pricing instead centers a short title and sales action over a broad plan comparison grid.

**Avoid:** Do not center the headline above a small symmetrical browser mockup, add a full-bleed color wash, or enlarge the hero type until it competes with the artifact.

**Text style:** `display` — Diatype 400 · 54px/1.05 · tracking -0.03em

### Ruled proof rail

**Observed:** A gray body-sized trust sentence sits above six contiguous Logo cells inside the main content width. The section uses 48px top padding; the rail is 82px overall including rules.

**Transfer:** Use one restrained proof statement and a consistent row of optically normalized marks; keep this as evidence rather than decorative wallpaper.

### Selectable workflow stage

**Observed:** The Workflow panel puts a square photographic collage left and text navigation right. Four 32px selectors are separated by 10px; description and progress line anchor the bottom. The panel is a single 1152px-wide stone object rather than four separate feature cards.

**Transfer:** Translate a complex process into a few short verb-led stages and keep a single coherent visual frame.

**Text style:** `heading` — Diatype 400 · 32px/1.1 · tracking -0.03em

### Heading pair and capability grid

**Observed:** A 48px title sits left with a narrow gray explanation aligned right. A ruled two-column feature area below uses 20px icon-led headings and body copy, with large softly fading interface illustrations. A compact four-column capability row follows with 48px gutters.

**Transfer:** Pair a broad outcome statement with a practical explanation, then divide capabilities into a few illustrated leads and shorter supporting details.

**Text style:** `heading-lg` — Diatype 400 · 48px/1.05 · tracking -0.03em

### Output exhibition

**Observed:** A two-line 48px heading and a support paragraph lead into the wide Output preview gallery. The first complete slide and a partial second slide establish breadth; captions sit underneath, with small square arrow controls at the right.

**Transfer:** Use high-quality finished results as the proof, allowing a different palette or layout within each output.

### Quality comparison

**Observed:** A body-size eyebrow precedes a 48px heading on the left, while support copy sits right. A wide Before and after artwork frame follows about 58px below the heading pair.

**Transfer:** Demonstrate a specific quality improvement with equivalent content on both sides, keeping the media block much larger than the explanation.

### User-proof carousel

**Observed:** A 48px heading and paired small arrows precede the Quote card rail. Three cards read fully at desktop while the next fades toward the edge; logos, modestly sized quotes and author portraits create a grounded proof rhythm.

**Transfer:** Keep the quotations body-sized and let spacing, customer identity and repetition do the persuasion.

### Question stack

**Observed:** A centered 48px FAQ heading is followed by a 912px-wide stack of FAQ rows, normally 16px apart. Pricing uses the same rows without a prominent FAQ title. Collapsed rows, not simultaneously expanded answers, define the visual rhythm.

**Transfer:** Answer the audience's actual risks and compatibility questions in concise prose.

### Spacious closing invitation

**Observed:** A centered 32px invitation has a 20px gap before the 44px Primary button, with 170px of air above and below the group. The footer beneath keeps the brand at left and three link columns right, set over the Fading vertical line field. It stays on the same pale Canvas, with 90px bottom padding; there is no giant wordmark or contrasting closing band.

**Transfer:** End on a personal outcome the reader can feel proud of, followed by one short action. Preserve the unusually spacious invitation and faint line texture while adapting navigation depth.

**Text style:** `heading` — Diatype 400 · 32px/1.1 · tracking -0.03em

### Narrow explanatory chapter

**Only for:** use-case and educational landing pages

**Observed:** A centered 640px reading column uses 28px headings, 16px support prose and roughly 32px chapter separation. Educational versions interleave 24px capability titles and 640px-wide demonstration image areas; a separate three-card stone-gradient benefits row can introduce the topic.

**Transfer:** Use this variant for search-led explanation and practical detail without turning the main marketing page into an article.

**Text style:** `article-heading` — Diatype 400 · 28px/1.05 · tracking -0.03em

### Tier comparison opening

**Only for:** pricing pages

**Observed:** Centered 54px page title, gray enterprise support line, black sales action and annual billing switch precede four equal Plan cards. The expanded container uses 30px side padding and 16px gutters. A faint warm halo behind the central area is subordinate to the white cards; the grid extends below the first screen.

**Transfer:** Give every tier the same material and keep the recommendation small. Separate billing controls from the card feature lists.

**Text style:** `display` — Diatype 400 · 54px/1.05 · tracking -0.03em

## Page flow

**Storyline:** Outcome promise → tangible product or output proof → trust → capabilities or practical explanation → objections or user proof → personal closing invitation.

### Flagship marketing landing page

1. **promise** — Unequal headline and oversized editor stage, with two actions and category tabs.
2. **social proof** — Compact ruled customer rail.
3. **product demonstration** — Selectable workflow panel.
4. **capability chapters** — Heading pair, two large illustrated leads and four compact supporting features.
5. **output proof** — Landscape gallery followed by a full-width quality comparison.
6. **user proof** — Gradient quote carousel.
7. **closing call** — Centered invitation, action and line-textured footer.

**Transfer:** Use the finished result as the narrative anchor, then choose workflow, capability and proof blocks that make that result believable.

### Self-serve commercial comparison

1. **pricing** — Centered title, sales contact and billing switch over four white plan sheets.
2. **sales conversion** — Separate demo action beneath the comparison.
3. **social proof** — Ruled customer rail.
4. **objection handling** — Untitled stack of billing and product questions.
5. **closing call** — Shared spacious invitation and footer.

**Transfer:** Make tier differences easy to scan while keeping the same restrained material and equal action hierarchy.

### Audience discovery landing page

1. **promise** — Audience-oriented headline and output stage with team-category tabs.
2. **social proof** — Customer rail.
3. **objection handling** — Centered FAQ title and broad question stack.
4. **closing call** — Shared invitation and footer.

**Transfer:** Use tailored artifacts and category labels to signal relevance without inventing unnecessary feature chapters.

### Role-specific use-case explanation

1. **promise** — Role-oriented outcome beside a framed output.
2. **social proof** — Ruled customer rail.
3. **output proof** — Wide carousel with partial neighboring examples.
4. **practical explanation** — 640px text column with 28px outcome headings and a short numbered benefit list.
5. **objection handling** — Role-specific FAQ stack.
6. **closing call** — Shared invitation and footer.

**Transfer:** Let examples show the role's work, then use concise prose to explain repeatable benefits.

### Educational acquisition landing page

1. **promise** — Outcome headline beside an oversized interface, with category tabs.
2. **benefit framing** — Three text-led stone-gradient cards beneath a large heading.
3. **instruction** — Narrow reading column with one inline visual and a short step list.
4. **capability explanation** — Long-form chapter with smaller regular headings and spaced inline demonstrations.
5. **objection handling** — Broad FAQ stack.
6. **closing call** — Shared invitation and footer.

**Transfer:** Keep educational detail in the narrow-column variant, while maintaining the visual opening and generous closing shared with richer marketing pages.

## Writing

Confident, practical and design-literate without sounding technical or exuberant. Value is framed as credible work, saved effort and professional pride rather than novelty alone.

**Do not copy:** Do not reuse the Chronicle name, symbol, proprietary artwork, customer logos, testimonials, competitor comparisons, prices, usage numbers or unsupported claims. Source phrases below illustrate structure, not content to transplant. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Name the product in concise explanatory sentences; use we sparingly for broad intent.
- **Rhythm:** Headlines tend to be 4–11 words and read as plain statements. Supporting lines are one or two compact sentences; longer educational passages remain practical and list-friendly. Punctuation is restrained, with occasional contractions and em dashes.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A credible outcome plus an explicit speed or alignment benefit. | 6–11 words | “Credible decks at the speed of AI”<br>“Go from idea to presentation in minutes” |
| Section headline | Short, memorable statement of stakes or professional quality. | 4–8 words | “Built for serious business.”<br>“Your reputation is on the slide.” |
| Supporting explanation | Concrete action, what it operates on, and useful outcome. | 1–2 sentences | “Paste raw notes, outlines, meeting docs, or existing decks. [Brand] pulls everything into a single presentation.” |
| Primary action | Simple verb and product or conversion intent. | 2–4 words | “Talk to sales”<br>“Try for free” |
| Closing invitation | Connect the action to personal pride in the result. | 6–10 words | “Create a presentation you’re proud of” |
| Question | Direct reader concern in ordinary language. | 5–10 words | “Do I need design skills to use [Brand]?” |

**Words and phrasing to use:** credible; clear; professional; on-brand; polished; teams; create; share; your; ready; in minutes

**Avoid:** revolutionary; magical; game-changing; unleash; 10x everything; world domination; excessive technical jargon

**Rules:**

- Tie speed claims to a concrete task or output.
- Use short active verbs for workflow labels.
- Explain complex features through familiar inputs and practical finished results.
- Let proof carry claims of quality; keep standalone superlatives sparse.
- Keep the final invitation personal rather than repeating the entire feature proposition.

## Do's and Don'ts

### Do

- Keep opening headlines at 54px, weight 400 and -0.03em tracking.
- Align core content to the 1212px container with 30px internal side padding.
- Use the 4px radius consistently on cards, previews and black actions.
- Reserve 128px between major visual chapters rather than compressing them into a dense feed.
- Keep body copy at 16px/1.4 and support color at black with 56% opacity.
- Show large finished artifacts with a partial next example and 24px slide spacing.
- Keep the closing invitation centered, with a 44px action and 170px breathing intervals.
- Use the stone gradient on bounded proof or workflow objects and the line field behind closing links.

### Don't

- Do not introduce a permanent saturated brand-color button; the action fill is black.
- Do not turn 4px card corners into 20px soft SaaS tiles or fully rounded pills.
- Do not make every card float; the 32px-blur shadow is reserved for active output previews and small portraits.
- Do not bold 48px or 54px headlines; professional emphasis comes from scale and tight setting.
- Do not turn body-sized eyebrows into tiny tracked uppercase labels.
- Do not place the entire FAQ at the full 1152px visual width; keep the question column at 912px.
- Do not highlight a recommended plan with a giant colored surface; retain the small dark badge and equal white sheets.
- Do not replace the pale closing canvas with a black promotional footer or a giant decorative wordmark.

## Motion and responsive

### Motion

**Observed:**

- Navigation and footer links declare color 0.2s linear transitions.
- Primary actions declare color, background and border 0.2s linear transitions.
- Workflow selectors declare color 0.4s; the workflow includes a linear progress-fill animation.
- Carousels use horizontal translation and previous/next controls; the comparison includes a central split handle.

**Transfer:**

- Keep changes focused on selecting a workflow scene or moving finished artifacts through a horizontal gallery.
- Preserve the understated linear color changes rather than using springy enlargement on every control.

**Unknown:**

- Workflow autoplay duration, full scroll-reveal choreography and reduced-motion behavior are unspecified.
- Focus-visible visual design is unspecified; provide an accessible focus treatment without treating the outline-removal declarations as a complete keyboard design.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1025px and 1280px.
- Selected heading sizes and large spacing values use the fluid formulas listed in their recipes.

**Transfer:**

- On narrower layouts, stack the promise above the product stage while preserving the stage as the dominant artifact; this is a recommended adaptation.
- Allow horizontal output galleries to retain partial neighbors rather than shrinking every artifact into tiny tiles.
- Collapse plan and feature grids into fewer columns while preserving document proportions and the restrained corners; this is a recommended adaptation.

**Unknown:**

- Exact narrow-screen compositions, navigation collapse behavior and mobile stage clipping are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
