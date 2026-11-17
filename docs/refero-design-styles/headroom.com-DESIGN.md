# Headroom — electric bespoke worlds

## Overview

Electric blue surrounds humane, matter-of-fact promises and miniature worlds of work. A tightly tracked contemporary grotesk gives the large statements a conversational rather than corporate feel, while warm off-white and pale gray make the explanatory areas feel tangible and uncluttered. Interface dioramas, perspective card landscapes and a striped abstract figure supply the spectacle; the overall density alternates between immersive scenes and very readable, airy explanations.

### Essentials

- A blue world, not a blue accent: #123bff fills the immersive opening and the closing/footer, while long explanatory stretches use #efefef and #fbfbf8 with white cards. Preserve this substantial blue/neutral alternation rather than scattering many colored sections.
- Promises sound spoken and look tightly joined: TWK Lausanne 64px/1.02, weight 400, -0.035em tracking in the opening, with just the resolving phrase at 600; ordinary section leads use 52px/1.06 and -0.025em.
- The opening is a room made of the product: centered two-line text occupies about three fifths of the width above a full-bleed perspective corridor of blue work cards, with a white striped emblem at its vanishing point. Recreate the depth with meaningful simplified cards when there is no interface.
- Navigation and conversion are small white capsules inside the spectacle: a centered floating navigation capsule about 53px high, and white 42px-high action pills with blue text, 12px 16px 12px 24px padding and a small right arrow.
- Explanations nest materials rather than decorating them: 28px-radius white chapter panels hold 20px-radius warm-gray demonstration trays and 16px-radius white interface slips. The surrounding gray band and 16px panel gaps do the separating.
- Personal ownership gets a physical highlight: a concluding key word is blue on a white rounded rectangle, paired with a monumental 112px regular line and 112px semibold highlighted word. Carry this signature to the new promise, not necessarily to the same word.
- A small graphic organism anchors the system: a white horizontal-stripe silhouette appears within the blue product landscape and returns as a larger or ghosted emblem in editorial contexts. Make an original striped symbol or abstract organism, not a generic gradient orb.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep scene blue | `#0029f5` | `--color-scene-deep` | surface | Blue cards within immersive marketing scenes; keeps depth monochromatic. |
| Electric blue | `#123bff` | `--color-blue` | background, text, action, link, accent | Immersive blue world, closing band, links and small section markings. |
| Raised scene blue | `#294dff` | `--color-scene-light` | surface | Alternating lighter blue planes in perspective scenes. |
| Blue-band hairline | `#3658ff` | `--color-blue-rule` | border | Visible white at 15% over electric blue; footer dividing rules. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale blue icon backing | `#e7ebff` | `--color-blue-wash` | surface | Visible 10% electric blue over white; small icon tiles. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, action | Type on blue, cards, navigation and primary action pills. |
| Near-black ink | `#171717` | `--color-ink` | text | Primary text on light surfaces. |
| Reading gray | `#5d5d5d` | `--color-body-secondary` | text | Visible equivalent of 70% ink on white for denser explanatory copy. |
| Secondary gray | `#747474` | `--color-muted` | text | Visible equivalent of 60% ink on white; support copy uses ink at 0.6 alpha so it follows the backing. |
| Light divider | `#e8e8e8` | `--color-rule` | border | Visible equivalent of 10% ink on white; ruled lists and faint panel edges use alpha to follow the backing. |
| Gallery gray | `#efefef` | `--color-band` | background | Long product explanation bands behind white panels. |
| Warm demonstration gray | `#f3f3f1` | `--color-tray` | surface | Nested backing for simplified demonstrations. |
| Warm paper | `#fbfbf8` | `--color-canvas` | background | Light-page canvas and prose sections. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| illustrated audience campaigns | Illustration pink | `#ff8ac0` | `--color-pink` | text, accent | Punctuation, emphasized closing phrase and hard offset card shadow. |
| capability directories | Black tile | `#111111` | `--color-tile-dark` | surface | Selective dark tiles contrasting with the featured blue tile. |
| capability directories | Utility tile gray | `#e4e4e4` | `--color-tile-gray` | surface | Alternating tile backings in the capability mosaic. |

## Typography

- **TWK Lausanne** — Headlines, conversational support copy, action pills and footer text. Contemporary Swiss grotesk with open counters, compact proportions and a friendly unforced regular cut. If unavailable, use **Inter**. Use 400 and 600; retain tight tracking and check line breaks against the intended width. Font stack: "TWK Lausanne", "Inter", Arial, sans-serif.
- **Inter** — Explanatory text, labels, numerals and simplified product UI. Compact neutral sans that remains legible in small functional details. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-display | TWK Lausanne | 400 | 112px | 1 | -0.035em | Monumental closing phrase on blue. |
| closing-highlight | TWK Lausanne | 600 | 112px | 1.2 | -0.035em | Concluding word on a white rounded rectangle. |
| display | TWK Lausanne | 400 | 64px | 1.02 | -0.035em | Default opening promise; centered and typically two lines. |
| display-emphasis | TWK Lausanne | 600 | 64px | 1.02 | -0.035em | Resolving words within the opening promise. |
| heading | TWK Lausanne | 400 | 52px | 1.06 | -0.025em | Main centered section leads. |
| chapter-heading | TWK Lausanne | 400 | 40px | 1.08 | -0.02em | Left-aligned capability chapter title. |
| outcome | TWK Lausanne | 400 | 32px | 1.12 | -0.015em | Replacement outcome in a before/after card. |
| closing-prelude | TWK Lausanne | 400 | 26px | 1.3 | -0.01em | Short centered setup above the monumental closing line. |
| support | TWK Lausanne | 400 | 19px | 1.5 | normal | Conversational one-sentence support under chapter headings. |
| proof-title | Inter | 600 | 17px | 1.5 | normal | Short headings in trust columns. |
| action | TWK Lausanne | 400 | 16px | 18px | normal | Primary pills and quiet secondary action text. |
| before-label | Inter | 400 | 16px | 22px | normal | Crossed-out task above its replacement; ink at 0.5 opacity. |
| body | Inter | 400 | 15px | 1.5 | normal | Compact explanatory paragraphs in proof panels. |
| text-link | Inter | 500 | 15px | 18px | normal | Blue explanatory link with a right arrow. |
| footer-link | TWK Lausanne | 400 | 15px | 18px | normal | Footer navigation links. |
| chapter-number | Inter | 600 | 14px | 18px | normal | Small blue ordinal above a chapter title. |
| navigation-label | Inter | 400 | 14px | 18px | normal | Menu text and restrained functional labels. |
| footer-definition | TWK Lausanne | 400 | 13.5px | 20px | normal | Dictionary-like brand definition below the footer logo. |
| eyebrow | Inter | 600 | 13px | 18px | 0.14em, uppercase | Blue section labels above major leads. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| illustrated audience campaigns | audience-display | TWK Lausanne | 600 | 108px | 0.95 | -0.045em | Oversized short audience-specific premise. |
| brand essays | manifesto-display | TWK Lausanne | 700 | 88px | 1 | -0.02em | Strong two-line editorial thesis. |
| single-feature pages | feature-display | TWK Lausanne | 400 | 64px | 1.04 | -0.03em | Light editorial opening headline. |
| single-feature pages | feature-display-emphasis | TWK Lausanne | 600 | 64px | 1.04 | -0.03em | Semibold completion of the light opening headline. |
| personal-service landing pages | service-heading | TWK Lausanne | 400 | 56px | 1.06 | -0.025em | Problem, demonstration and reassurance section leads. |
| personal-service landing pages | service-heading-emphasis | TWK Lausanne | 600 | 56px | 1.06 | -0.025em | Semibold completion of service section leads. |
| capability directories | tile-title | TWK Lausanne | 400 | 34px | 1.08 | -0.025em | Large label at the base of a featured capability tile. |
| brand essays | manifesto-subhead | TWK Lausanne | 600 | 24.4px | 1.1 | -1px | Compact section statements inside an essay. |
| question-and-answer sections | faq-question | TWK Lausanne | 400 | 19px | 18px | -0.01em | Ruled accordion summaries. |
| brand essays | manifesto-body | TWK Lausanne | 400 | 18px | 26px | normal | Long-form white prose on blue. |
| detailed feature and audience pages | reading-body | Inter | 400 | 16px | 1.55 | normal | FAQ answers and longer capability explanations. |

**Notes:**

- Use the regular cut for most large promises and add semibold only to the completion; emphasis stays upright, not italic.
- Tracking tightens from -0.015em on outcomes to -0.035em on the default display. The illustrated campaign display is tighter still at -0.045em.
- Headlines should break by meaning rather than into evenly sized decorative lines. Keep support copy visibly smaller and lighter.
- The default closing is deliberately much larger than the opening. Service closings use a smaller 64px treatment, while illustrated audience closings use 104px/0.95 with -0.045em tracking.

## Layout

**Density:** Airy outer narrative with tightly packed interface scenes; the contrast between broad section breathing room and dense miniature cards is essential.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon/text separation and before-to-after text gap. |
| 12px | Stacks inside interface slips and footer link rows. |
| 16px | Heading-to-support gap and separation between chapter panels or outcome cards. |
| 24px | Copy-to-list spacing and small action groups. |
| 32px | Main desktop side padding and outcome-card padding. |
| 48px | Trust-panel padding and lead-to-grid spacing. |
| 56px | Chapter-panel inner padding and two-column gap. |
| 64px | Heading-to-timeline spacing and large split-section gaps. |
| 96px | Separation before the trust panel. |
| 108px | Feature explanations and audience-page sections. |
| 126px | Broad neutral chapter vertical padding. |
| 144px | Timeline section vertical padding and blue closing bottom padding. |
| 198px | Default blue closing top padding. |

### Containers and grids

- **wide-stage**: max width 1240px · side padding 32px. Centered explanatory chapter panels and footer inner rule.
- **reading-stage**: max width 1040px · side padding 32px. Centered outcome grids, timelines, FAQ and audience compositions.
- **chapter-split**: 2 columns · gap 56px. Equal columns for text and demonstration; alternate the visual side across chapters.
- **outcome-grid**: max width 1040px · 2 columns · gap 16px. Two by two white cards, each about 512px wide at desktop.
- **feature-opening** (only for single-feature pages): max width 1152px · 2 columns · gap 64px · side padding 32px. Large headline on the left with a 340px support column aligned near its bottom.
- **capability-mosaic** (only for capability directories): max width 1040px · 12 columns · gap 10px. A six-column double-height blue tile, three-column double-height dark tile and stacked three-column light tiles; smaller varied spans continue below.
- **essay-column** (only for brand essays): max width 640px · side padding 32px. Narrow left-aligned prose centered inside a larger blue field.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | pills | 9999px (pill) |
|  | chapter-panels | 28px |
|  | outcome-cards | 24px |
|  | demonstration-trays | 20px |
|  | interface-slips | 16px |
|  | icon-tiles | 14px |
| capability directories | capability-tiles | 26px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | action-lift | `0px 18px 40px -20px rgba(0,0,40,0.7)` | White primary action on blue. |
|  | interface-edge | `0px 0px 0px 1px rgba(23,23,23,0.06), 0px 1px 0px rgba(0,0,0,0.04)` | Subtle edge on nested white demonstration slips. |
| illustrated audience campaigns | pink-offset | `8px 8px 0px 0px #ff8ac0` | Hard pink backing of an audience-page checklist. |

### Surfaces

#### Paper canvas · level 0

**Use:** Light prose and editorial openings.

**CSS:** `background: #fbfbf8; color: #171717`

#### Gray gallery band · level 0

**Use:** Backs white chapter panels and outcome grids.

**CSS:** `background: #efefef; color: #171717`

**Observed:** Full-width and flat, not a gradient or a bordered container.

**Transfer:** Let whole narrative stretches share one gray field.

#### Blue world · level 0

**Use:** Immersive opening, closing and footer.

**CSS:** `background: #123bff; color: #ffffff; overflow-x: clip`

**Observed:** The blue is saturated and flat; depth comes from foreground card planes.

**Transfer:** Use blue as space around the product, not as a generic decorative wash.

#### Chapter panel · level 1

**Use:** Large capability explanation.

**CSS:** `background: #ffffff; border-radius: 28px; padding: 56px`

**Observed:** White silhouette against the gray gallery band, generally without an exterior shadow.

**Transfer:** Group one promise and one demonstration.

#### Demonstration tray · level 2

**Use:** Backs simplified product activity inside a chapter panel.

**CSS:** `background: #f3f3f1; border-radius: 20px; padding: 32px`

**Observed:** A warm near-gray inset surrounds smaller white slips.

**Transfer:** Keep the backing visible around all edges so the demo reads as a composed illustration.

#### Interface slip · level 3

**Use:** A message, answer, handoff or record in a product illustration.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 20px; box-shadow: 0px 0px 0px 1px rgba(23,23,23,0.06), 0px 1px 0px rgba(0,0,0,0.04)`

**Observed:** Tiny internal labels and restrained source chips make it feel functional.

**Transfer:** Use just enough UI to communicate a change; do not reproduce a whole app.

#### Pink-backed checklist · level 1

**Only for:** illustrated audience campaigns

**Use:** A tangible list of current manual work.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 32px; box-shadow: 0px 0px 0px 1px rgba(23,23,23,0.06), 8px 8px 0px 0px #ff8ac0`

**Observed:** Hard offset pink edge, small checkboxes, blue label and ruled rows.

**Transfer:** Contrast a familiar burden list with the later resolved workflow.

## Components

### Floating navigation

**Use:** Compact persistent access without occupying a full-width header bar.

**CSS:** `background: #ffffff; color: #171717; border-radius: 9999px; height: 53px; width: 280px; overflow: hidden`

**Text style:** `navigation-label` — Inter 400 · 14px/18px

**Observed:** Centered near the top, with a small logo at left and a two-line menu icon at right. It expands to include a blue conversion pill on later scroll states; widths vary with the contents.

**Transfer:** Use a compact original wordmark and keep the shell content-sized rather than spanning the viewport.

### Primary button

**Use:** Main conversion action on blue.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; background: #ffffff; color: #123bff; border-radius: 9999px; padding: 12px 16px 12px 24px; height: 42px; box-shadow: 0px 18px 40px -20px rgba(0,0,40,0.7); text-decoration: none`

**Text style:** `action` — TWK Lausanne 400 · 16px/18px

**Observed:** Text followed by a small right arrow. A blue-filled 38px-high variant lives inside the white navigation capsule.

**States:** Declared: hover background-color color-mix(in oklab, hsl(0 0% 100%) 90%, transparent); focus-visible not specified.

**Transfer:** Make the label a concrete first step, not an abstract conversion slogan.

### Arrow text link

**Use:** Secondary explanatory action on neutral bands.

**CSS:** `display: inline-flex; align-items: center; gap: 6px; color: #123bff; text-decoration: none`

**Text style:** `text-link` — Inter 500 · 15px/18px

**Observed:** A slim right arrow completes the text, generally centered beneath a proof device.

**States:** Declared: hover text-decoration-line underline and text-decoration-color currentcolor; focus-visible not specified.

### Capability chapter

**Use:** A large, readable explanation paired with product proof.

**CSS:** `display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); gap: 56px; padding: 56px; background: #ffffff; border-radius: 28px`

**Text style:** `chapter-heading` — TWK Lausanne 400 · 40px/1.08 · tracking -0.02em

**Observed:** Small blue ordinal, heading, one support line and three compact checkmarked benefits in one column; Demonstration tray in the other. The text is vertically centered and alternating chapters reverse the sides.

**Transfer:** One chapter should explain a single verb or job rather than a catalog of unrelated features.

### Outcome card

**Use:** Make a manual task and its replacement instantly comparable.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-radius: 24px; padding: 32px; min-height: 240px`

**Text style:** `outcome` — TWK Lausanne 400 · 32px/1.12 · tracking -0.015em

**Observed:** Small pale blue icon tile at top left; ample open middle; the bottom stack crosses out the old task with 0.5-opacity ink and presents a larger replacement 8px below it.

**Transfer:** Write a specific old habit and a short new state, not two vague benefit slogans.

### Trust panel

**Use:** Bounded reassurance after the practical explanation.

**CSS:** `background: #ffffff; border-radius: 28px; padding: 48px; max-width: 1000px`

**Text style:** `proof-title` — Inter 600 · 17px/1.5

**Observed:** A short 36px two-weight title sits above three equal icon-led columns, separated by 1px 8%-ink rules. Each has a compact bold heading and a smaller explanatory paragraph.

**Transfer:** Use verifiable operating safeguards rather than a wall of badges.

### Footer columns

**Use:** A compact directory that remains inside the blue world.

**CSS:** `display: grid; grid-template-columns: minmax(0px, 1.3fr) minmax(0px, 2fr) repeat(3, minmax(0px, 1fr)); column-gap: 32px; row-gap: 48px; padding: 56px 48px 64px; border-top: 1px solid rgba(255,255,255,0.15); color: #ffffff`

**Text style:** `footer-link` — TWK Lausanne 400 · 15px/18px

**Observed:** The wider brand column includes a dictionary-style definition and two outlined assurance pills. An audience directory takes two internal columns, followed by company, legal and social groups. Small bottom text sits on a separate ruled baseline.

**States:** Declared: hover link color hsl(0 0% 100%); focus-visible not specified.

**Transfer:** Retain the definition-like brand statement and compact directory, adapting the categories to the product.

### FAQ row

**Only for:** question-and-answer sections

**Use:** Resolve concrete setup or control objections.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; padding: 20px 0px; border-top: 1px solid rgba(23,23,23,0.1); color: #171717`

**Text style:** `faq-question` — TWK Lausanne 400 · 19px/18px · tracking -0.01em

**Observed:** Native disclosure construction with a plus on the far right, no filled card. The final row also closes with a bottom rule. Answers use reading-body, a 704px maximum and 24px bottom padding.

**Transfer:** Keep each question operational and answer directly before adding explanation.

### Capability tile

**Only for:** capability directories

**Use:** Linked product ecosystem mosaic.

**CSS:** `display: flex; flex-direction: column; position: relative; overflow: hidden; padding: 28px; border-radius: 26px; background: #111111; color: #ffffff`

**Text style:** `tile-title` — TWK Lausanne 400 · 34px/1.08 · tracking -0.025em

**Observed:** Product vignette takes the upper area; title and support sit at the bottom. The featured current capability is blue and double width, neutral neighbors alternate white and gray; a wide dark question tile closes the mosaic.

**States:** Declared: hover not specified; focus-visible outline-style none and zero box-shadow; active scale 0.985.

**Transfer:** Preserve the irregular scale hierarchy and emphasize one current capability.

## Imagery and graphics

### Perspective card corridor

**Use:** Signature immersive product opening.

**Observed:** Blue record cards form walls receding toward a central vanishing point. Near cards extend beyond the side edges and grow larger than the headline; the center remains open around a small white striped emblem. White type, subtle translucent fields and tiny warm/cool status marks keep the scene legible but subordinate to the promise.

**Transfer:** Arrange new product objects or simplified records into the same receding room. Minimum version: two perspective-transformed strips of meaningful blue cards with an original striped symbol at center.

**Build:** Create two CSS 3D rails around a shared central perspective origin. Rotate the left rail inward and mirror the right; progressively shrink and translate successive cards toward the center. Fill planes with #0029f5 and #294dff over #123bff, use white text and rgba(255,255,255,0.07) inner fields. Mask the far ends into the blue. Keep the center open rather than placing a large browser window there.

### Striped emblem

**Use:** Recurring signature symbol within blue scenes and as editorial atmosphere.

**Observed:** A small white figure made of disconnected horizontal strokes appears at the corridor's far end. Editorial use enlarges it into a central floating silhouette and lets a translucent version sit behind prose.

**Transfer:** Design an original abstract symbol or product-relevant organism using interrupted horizontal strokes. It must stay recognizable as a silhouette without detailed illustration.

**Build:** Draw an original silhouette as an SVG clipPath. Fill it with horizontal white rectangles, varying lengths and offsets, separated by clear blue gaps. Add several short detached strokes outside the contour to create the scanning effect. Use solid white in the opening and rgba(255,255,255,0.2) behind prose; scale the same drawing rather than changing its vocabulary.

### Nested product vignettes

**Use:** Practical proof inside capability chapters.

**Observed:** A warm-gray tray contains white answer cards, source chips, miniature rows or draft messages. Objects are front-on and crisp, not tilted mockups; hierarchy is much simpler than a production app. Blue connectors and tiny icons indicate cause and effect.

**Transfer:** Illustrate one before-input and one after-output using realistic short content. Keep surrounding labels quiet and use only small semantic color inside the UI.

### Card planet

**Only for:** personal-service landing pages

**Use:** Service opening and scroll-driven product landscape.

**Observed:** A large curved ground plane of translucent blue record tiles fills the lower half of the opening, with the striped symbol standing over a bright white selected tile. Cards farther away diminish and fade into a blue horizon; a few white cards interrupt the blue grid.

**Transfer:** Use a tilted grid of the new product's records and one highlighted result; keep the left headline clear above the horizon.

**Build:** Place a wide CSS grid inside a perspective wrapper, rotate it back around the x axis, and curve the perceived horizon with a large elliptical mask. Use rgba(255,255,255,0.1) tile fills, 16px corners and white 20%-alpha edge rings. Put a white selected tile with a soft pale blue halo near the emblem, then layer #123bff-to-transparent fades at the horizon and lower edge.

### Duotone editorial illustration

**Only for:** illustrated audience campaigns

**Use:** Square before/after scenes beside audience-specific claims.

**Observed:** A textured comic-like drawing of busy people, paper and tangled connections shifts to a coordinated team scene. Deep blue backing, hot pink contours and chalky white highlights create a limited-palette print feeling. Each is framed at 420px square with 20px corners and a deep soft blue shadow.

**Transfer:** Commission or draw an original paired scene of friction and resolution using navy/blue, pink and white. Minimum version: a clear three-person tabletop composition with pink connection lines and sparse grain; do not replace it with glossy generic 3D people.

**Build:** Layer flat dark-blue silhouettes and white paper/object shapes with pink contour strokes. Add a low-opacity stipple texture across the whole drawing, constrain it to a rounded square, and apply 0px 24px 48px rgba(0,0,40,0.28).

### Phone conversation triptych

**Only for:** personal-service demonstrations

**Use:** Show requests, approval and digest as familiar text conversations.

**Observed:** Three upright black phones with metallic outer edges, white screens and native blue/gray bubbles sit under paired short captions. Each phone is about 253px by 512px, with 52px outer corners and soft shadows; the screen remains the visual focus.

**Transfer:** Use three short real-world exchanges rather than decorative device photography. Keep screens front-on and captions centered.

### Icons

**Observed:** Small mostly solid functional icons at 14px, 18px or 20px, blue on light backgrounds. Action arrows are 14px outline drawings with 1.8px round strokes; assurance shields use 16px white outlines at 1.6px. Larger card icons sit within 44px pale-blue rounded squares.

**Transfer:** Choose a consistent compact functional set; use small check circles, arrows, locks and context symbols instead of colorful illustrated badges.

## Section recipes

How recurring sections are built.

### First screen: Immersive product room opening

**Observed:** A flat Blue world fills the first 900px. Centered two-line display type spans about three fifths of the width in the upper third; the final product phrase changes to semibold without becoming a separate logo. Behind and below it, the Perspective card corridor occupies most of the lower view, extends beyond both side edges and converges on the Striped emblem at center. The headline stays in front of the scene. Floating navigation is a small centered top layer during the persistent navigation state. There is no separate explanatory paragraph: the second headline line supplies the resolution. A Primary button is constructed beneath the central scene; the immersive scene can dominate its initial visible state. The later neutral explanation and chapter cards lie below the first screen, not beside the hero.

**Transfer:** Make the promise acknowledge the reader's effort, then resolve it with the product. Rebuild the room from simplified meaningful objects if full interface art is unavailable; preserve side-to-center depth and an original striped emblem. Single-feature pages instead open on Paper canvas with a left headline and lower-right support paragraph, bringing a broad demo into the bottom of the first screen. Illustrated audience pages use a compact blue split opening with a square scene; essays use a large emblem above a narrow thesis column.

**Avoid:** Do not turn the opening into a conventional centered browser screenshot with a paragraph and two equal buttons; do not shrink the scene into a bordered card or put the headline inside the corridor walls.

**Text style:** `display` — TWK Lausanne 400 · 64px/1.02 · tracking -0.035em

### Transformation theater

**Observed:** A gray stage moves from a pale, isolated manual-work card to a saturated blue built-around-you card beneath a short centered statement. A second scene contrasts a five-by-three grid of repeated white cards with a smaller blue card floating in front; faded surrounding cards establish sameness versus specificity.

**Transfer:** Use a controlled change of one physical object or grid to express the product's central difference. This signature demonstration can sit wherever the story needs a turning point; it is not a required section sequence.

### Heading and chapter panels

**Observed:** A blue eyebrow sits 16px above a centered 52px heading. Capability chapter panels follow with a 32px top separation and 16px between panels. Each alternates text and demonstration, using the Chapter panel and Demonstration tray surfaces.

**Transfer:** Choose a small set of action verbs that explain the new system and make each demonstration show the corresponding result.

**Text style:** `heading` — TWK Lausanne 400 · 52px/1.06 · tracking -0.025em

### Workaround replacements

**Observed:** A centered heading leads a two-column Outcome card grid 48px below. Icons sit high; old and new task text sit low. Gray gallery band provides the surrounding space.

**Transfer:** Compare recognizable habits with concise replacement states, using the same crossed-out-to-large hierarchy.

**Text style:** `outcome` — TWK Lausanne 400 · 32px/1.12 · tracking -0.015em

### Progress as proof

**Observed:** A centered 52px two-weight promise and one support line introduce a 1000px-wide row of fourteen 64px rounded squares with 8px gaps. Blue intensity grows toward the last checked square. Four captions below use thin blue rules and uppercase day labels. Arrow text link sits 40px beneath the caption row; Trust panel follows with 96px separation.

**Transfer:** Translate a real process into a finite set of small cells and grouped milestones. The device can represent onboarding, completion or stages; do not invent speed claims to fit the illustration.

### Monumental ownership close

**Observed:** Blue world returns with 198px top and 144px bottom padding. A 26px prelude introduces a centered 112px line, then the resolving word appears semibold in blue on a white rectangle with about 9px corners. A white Primary button and quieter secondary text action sit beneath. This blue continues directly into Footer columns, separated only by a faint rule.

**Transfer:** End on the reader's changed state. Highlight a single meaningful conclusion using the same white backing; keep the footer in the same color world. Smaller service closes use 64px paired lines with the same highlighted-word device; audience campaigns use 104px lines with pink emphasis; single-feature closes use a concise 52px two-weight statement.

**Text style:** `closing-display` — TWK Lausanne 400 · 112px/1 · tracking -0.035em

### Ruled explanation and questions

**Only for:** detailed feature and audience pages

**Observed:** A left-aligned short heading pairs with a right column of compact capability explanations separated by hairlines. FAQ rows below are full-width within 1040px, with plus controls and no enclosing cards.

**Transfer:** Use this quieter pattern for operational detail after visual proof rather than adding another card grid.

### Blue editorial letter

**Only for:** brand essays

**Observed:** An enlarged white Striped emblem floats above a 640px thesis column. An outlined uppercase tag precedes an 88px bold two-line thesis. White 18px/26px paragraphs follow in 32px-spaced blocks, broken by 24.4px semibold subheads and dash-led beliefs. The letter ends with a white action pill, three handwritten signatures with compact names/roles, then a social line; generous blue space and the ghosted emblem lead into the shared footer.

**Transfer:** Use a founder letter or conviction essay with real specific beliefs and a personal sign-off rather than a standard feature landing layout.

**Text style:** `manifesto-display` — TWK Lausanne 700 · 88px/1 · tracking -0.02em

## Page flow

**Storyline:** human promise → tangible transformation → practical capability proof → process and control reassurance → personal closing invitation → blue directory footer

### Broad product introduction through an immersive visual argument

1. **promise** — Two-line blue-world headline over a perspective corridor.
2. **transformation** — Manual-work object becomes tailored product; repeated standard cards contrast with one specific blue card.
3. **capability chapters** — Numbered alternating white panels with nested product vignettes.
4. **outcome proof** — Two-by-two crossed-out workaround replacements.
5. **process and reassurance** — Finite progress cells and milestone captions followed by three trust columns.
6. **closing call** — Monumental highlighted-word close and integrated blue directory footer.

**Transfer:** Use the visual argument to make a complex product feel specific to the reader before explaining its parts.

### Audience-specific friction and resolution

1. **promise** — Oversized blue/pink premise beside a square duotone illustration.
2. **problem recognition** — Split headline and pink-backed manual checklist, followed by a centered situational statement.
3. **transformation** — Paired resolved illustration and three white capability cards with blue product art.
4. **process and reassurance** — Progress cells and trust panel.
5. **objection handling** — Ruled FAQ disclosures.
6. **closing call** — Large white/pink two-line service promise, supporting commitment, white action pill and shared blue footer.

**Transfer:** Borrow the reader's specific daily vocabulary while retaining the same measured surfaces and process proof.

### Explain one capability with lower theatrical density

1. **promise** — Light split opening: two-weight headline at left, support at lower right.
2. **product demonstration** — Wide gray-backed live-workflow scene with a compact trigger sidebar and main interface.
3. **capability explanation** — Left heading paired with a ruled right-hand list of specific behaviors.
4. **objection handling** — Full-width FAQ rows.
5. **product context** — Asymmetric blue, black, gray and white capability mosaic.
6. **closing call** — Concise blue-band statement and pill, then shared footer.

**Transfer:** Make the single capability demonstrable, explain edge cases, then show where it fits within a larger system.

### Present a personalized service through familiar requests and control

1. **promise** — Left white headline with a boxed blue resolving word above a curved card world.
2. **problem recognition** — Timestamped ruled incidents, ending with red urgency.
3. **product demonstration** — Three front-on phone conversations under paired captions.
4. **reassurance** — Two-by-two icon-led white cards about personalization and control.
5. **closing call** — Smaller highlighted-word close, one support line and white action pill, flowing into shared footer.

**Transfer:** Start with the user's personal burden, then demonstrate relief in an already familiar interaction channel.

### Express an opinionated brand conviction in a personal letter

1. **thesis** — Striped emblem above a bold two-line thesis on uninterrupted blue.
2. **argument** — Narrow prose column, short subheads and dash-led beliefs.
3. **commitment** — Specific description of how the company works with the reader.
4. **personal sign-off** — White action pill, three handwritten signatures and compact social line.
5. **ending** — Generous blue continuation with a ghosted emblem, then the same directory footer.

**Transfer:** Give a brand essay its own editorial density and personal ending instead of forcing it through a product-card sequence.

## Writing

Warm, candid and operationally specific. It respects the effort the reader has already invested and makes confident promises through recognizable situations rather than inflated technology language.

**Do not copy:** Do not reuse Headroom's name, logo, striped figure, customer or founder identities, quotations, claims, monetary examples, timeline commitments, guarantees or certification claims as assets or facts for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. We describes the people doing the building; the product is described through concrete actions rather than a distant corporate persona.
- **Rhythm:** Short spoken headlines often split into setup and resolution; one-sentence support lines; plain lists of everyday things. Contractions are normal. Longer essays become more combative, but ordinary product copy remains reassuring.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Recognize what the reader has already done, then propose a more supported future. | Two short spoken clauses | “You built your business by hand.”<br>“Now let's run it with [Brand].” |
| Section lead | A concise action sequence or a tension followed by its resolution. | 3–10 words | “Capture. Understand. Act.”<br>“The daily workaround, gone.” |
| Supporting line | Plain input/output language; reassure without introducing a new concept. | One sentence, usually under 15 words | “Every email, call, doc and chat, in one place.”<br>“You keep working. We do the building.” |
| Proof and control | State who acts, who approves and what remains visible. | One compact statement plus a practical explanation | “Agents do the busywork. You approve what matters.”<br>“Every change is on the record.” |
| Primary action | Name the low-friction first human step, with duration when useful. | 4–6 words | “Book your first call”<br>“Book a 30-minute call” |
| Closing line | Remove a burden in a blunt two-part statement or turn the final promise toward the reader. | 2–8 words | “Next, it's”<br>“yours.”<br>“You don't set it up.”<br>“We do.” |

**Words and phrasing to use:** by hand; your people; the work; one place; the whole picture; you approve; built around you; what matters; we do

**Avoid:** revolutionary platform; unlock your potential; seamless synergy; enterprise-grade transformation; AI-powered everything; supercharge every workflow

**Rules:**

- Make benefits observable: name a thread, a record, an owner or an approval instead of a vague efficiency gain.
- Use paired regular/semibold phrases to mirror setup and resolution in the language.
- Give product capabilities active verbs and keep humans visibly in control.
- Use literal first steps in actions, not aspirational button slogans.
- Reserve the confrontational manifesto register for a belief-driven essay; everyday conversion copy should sound helpful.

## Do's and Don'ts

### Do

- Keep the default opening headline at 64px/1.02 with -0.035em tracking and a regular-to-semibold resolution.
- Use substantial #123bff opening and closing fields around long gray/white explanatory areas.
- Retain a perspective card world and an original horizontal-stripe emblem as the distinctive graphic system.
- Nest 16px white slips inside 20px warm-gray trays inside 28px white chapter panels.
- Keep chapter panel gaps at 16px and their internal desktop split at 56px.
- Pair a 16px crossed-out task with a 32px replacement in outcome cards.
- Let the closing word sit blue-on-white within the blue band, with the default 112px type treatment.
- Continue the closing blue through a ruled 1240px footer rather than ending on a disconnected neutral block.

### Don't

- Do not use pink as an all-site secondary brand fill; it belongs to the illustrated audience variant.
- Do not set every heading in 700: the ordinary promise and section leads rely on 400 with selective 600.
- Do not add broad drop shadows to all white chapter cards; their separation is primarily white against #efefef.
- Do not make every action blue-filled; the principal action on blue is a white 42px pill.
- Do not replace the compact floating capsule with a full-width menu link bar.
- Do not turn demonstration UI colors into a multicolor marketing palette; the scenes remain overwhelmingly blue and neutral.
- Do not use 24px or 28px rounding for every nested object; preserve the 28/20/16px material hierarchy.
- Do not force a capability mosaic or illustrated square scene into every page type; those have distinct directory and audience roles.

## Motion and responsive

### Motion

**Observed:**

- Declared color/background transitions use .15s cubic-bezier(.4,0,.2,1).
- The navigation shell declares width, height, border-radius and box-shadow transitions at 0.64s cubic-bezier(0.16,1,0.3,1).
- Product tiles declare transform transitions at 0.3s cubic-bezier(.4,0,.2,1), with active scale 0.985.
- The immersive opening is sticky while the card world transforms through the scroll narrative; the neutral transformation scenes continue that staged storytelling.

**Transfer:**

- Use scroll progression to change the spatial product metaphor, not to make every paragraph fly into view.
- Keep small arrows and pills responsive with the short declared transitions, and reserve the longer shell morph for the compact navigation.

**Unknown:**

- Exact choreography, scroll thresholds and full durations of the immersive scene are not specified.
- Reduced-motion behavior and keyboard focus styling beyond the stated declarations are unknown.

### Responsive

**Observed:**

- Desktop composition uses 1240px and 1040px centered stages with 32px side padding.
- Utility variants indicate one-column chapter panels before the desktop two-column composition, and smaller headline settings of 32px for section leads and 30px for chapter titles. Numerical breakpoint widths are not established.

**Transfer:**

- On narrow screens, stack copy before its demonstration while preserving the nested tray/slip construction; reduce chapter padding to 20px and use 16px outer gutters.
- Keep the blue scene immersive but simplify the number of visible cards rather than squeezing desktop card text into the screen.
- Let the floating navigation remain a compact capsule and keep the single highlighted closing word intact as its own short line.
- Collapse directory tiles and phone demonstrations into readable single-column blocks instead of miniaturizing the whole desktop composition.

**Unknown:**

- Mobile imagery framing, navigation expansion layout and exact breakpoint widths are not known.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
