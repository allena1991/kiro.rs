# Arc — scalloped digital optimism

## Overview

An optimistic software style that makes digital tools feel personal, tactile and a little mischievous. Electric blue, creamy paper and white surround rounded, tightly packed grotesk headlines, with occasional literary serif introductions and tiny monospaced labels. Oversized working interfaces carry most of the story; grain, wavy seams and sticker-like details keep the spacious presentation from feeling corporate.

### Essentials

- Soft words, tightly packed: rounded Marlin Soft SQ headlines use 700 weight, 40px/39px and -0.04em tracking; the introductory serif uses 36px/36px and -0.02em.
- A centered invitation above an enormous working object: the opening pairs a short headline, one support sentence and one action with a 1200px-wide interface that continues beyond its cream stage.
- Color is architectural, not sprinkled everywhere: white carries the long demonstration chapters, while #3139fb fills the navigation, a major proof stage and the closing band; cream separates proof from demonstration.
- Actions are small rounded rectangles rather than pills: the standard download is 273px by 45px with 10px corners; the opening app-icon action is 214px by 76px with 22px corners.
- Digital paper has a handmade seam: saturated bands carry fine grain and repeated scalloped edges; the closing action and footer are separated by a thin cream wave. Recreate these with SVG noise and tiled wave paths.
- The product is the scenery: large front-facing windows show colorful, believable work rather than abstract dashboards. If no polished interface exists, construct one convincing workflow at comparable scale.
- Proof is friendly and collectible: cream quote strips and bold 28px testimonials end in blue-outlined, uppercase mono attribution badges rather than conventional review cards.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep violet | `#2702c2` | `--color-violet` | action, text, background | Text on white download actions, alternate solid actions and announcement strips. |
| Electric blue | `#3139fb` | `--color-blue` | background, text, border, link | Primary identity: full-width textured bands and chapter headings. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Serif ink | `#000000` | `--color-black` | text | Opening serif headline. |
| Soft black action | `#262626` | `--color-charcoal-action` | action | Visible opening action; black at 0.85 alpha over its pale stage. |
| Opening gray | `#595959` | `--color-intro-muted` | text | Visible dark gray of opening support; black at 0.65 alpha over the near-white portion of its atmospheric stage. |
| Body gray | `#696969` | `--color-body` | text | Default supporting copy on white. |
| Cream paper | `#fffcec` | `--color-paper` | background, text | Proof bands and warm reversed text. |
| White | `#ffffff` | `--color-white` | background, surface, text | Long demonstration canvas, white actions and reversed navigation. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| feature launch pages | Activation red | `#ff3333` | `--color-red-action` | action | Small activation button against blue. |
| youth and community campaigns | Cornflower | `#458aff` | `--color-tile-blue` | surface | First feature-gallery backing. |
| youth and community campaigns | Lime paper | `#d3e081` | `--color-tile-lime` | surface | Second feature-gallery backing. |
| technical audience landing pages | Slate blue | `#36566b` | `--color-slate` | background | Textured opening and closing instead of electric blue. |
| youth and community campaigns | Lilac paper | `#cdccdf` | `--color-tile-lilac` | surface | Third feature-gallery backing. |
| feature launch pages | Lavender canvas | `#e0e0f7` | `--color-lavender` | background | Continuous feature-tour canvas. |
| feature launch pages | Tour ink | `#171717` | `--color-tour-ink` | text | Compact feature titles. |
| youth and community campaigns | Warm charcoal | `#3c3b3a` | `--color-warm-ink` | text, action | Campaign headings and primary actions. |
| feature launch pages | Tour gray | `#6f6f6f` | `--color-tour-muted` | text | Instructional feature descriptions. |
| youth and community campaigns | Warm gray | `#766e6a` | `--color-warm-muted` | text | Campaign support and captions. |
| youth and community campaigns | Label gray | `#97928f` | `--color-label-gray` | text | Campaign eyebrow and inactive inline heading words. |
| youth and community campaigns | Warm hairline | `#deded2` | `--color-rule` | border | Visible FAQ separator: rgba(14,15,16,0.1) over warm ivory. |
| youth and community campaigns | Putty | `#e1e0ce` | `--color-stone` | surface, background | Campaign band, secondary action and window backing. |
| youth and community campaigns | Warm ivory | `#f5f4e2` | `--color-campus-paper` | background | Continuous warm campaign canvas. |

## Typography

- **Marlin Soft SQ** — Core headlines, navigation and quotes. Rounded, soft-square grotesk with dense, friendly bold forms. If unavailable, use **Lato**. Use 700 for headlines and 500 for navigation; preserve tight tracking. Font stack: "Marlin Soft SQ", "Lato", -apple-system, system-ui, sans-serif.
- **InterVariable** — Supporting prose and footer links; Inter is the static equivalent in campaign prose. Neutral high-x-height sans that lets the softer display face lead. If unavailable, use **Inter**. Font stack: "InterVariable", Inter, system-ui, sans-serif.
- **Exposure VAR** — Literary introductory headline. Expressive dark serif, lending a personal editorial tone to a software invitation. If unavailable, use **EB Garamond**. Use 700 and match the compact single-line silhouette. Font stack: "Exposure VAR", "EB Garamond", Georgia, serif.
- **ABC Oracle** — Opening support and app-icon action. Open, unforced contemporary grotesk. If unavailable, use **DM Sans**. Font stack: "ABC Oracle", "DM Sans", Helvetica, sans-serif.
- **ABC Favorit Mono** — Attribution badges, footer labels and campaign microcopy. Straightforward monospace, usually uppercase and positively tracked. If unavailable, use **IBM Plex Mono**. Font stack: "ABC Favorit Mono", "IBM Plex Mono", Menlo, Monaco, monospace.
- **system-ui** — Download buttons and compact feature-launch titles. Familiar operating-system typography that reinforces the working-app feel. Font stack: "system-ui", -apple-system, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Marlin Soft SQ | 700 | 45.5px | 0.928 | -0.04em | Large reversed quote on a textured hero stage. |
| heading | Marlin Soft SQ | 700 | 40px | 0.975 | -0.04em | Default centered chapter headline. |
| intro-display | Exposure VAR | 700 | 36px | 1 | -0.02em | Centered opening invitation. |
| quote | Marlin Soft SQ | 700 | 28px | 1.071 | -0.05em | Large testimonial text. |
| closing | Marlin Soft SQ | 700 | 28px | 1.1 | -0.05em | One-line closing invitation. |
| closing-emphasis | Marlin Soft SQ | 700 italic | 28px | 1.1 | -0.05em | One personal word in the closing invitation. |
| intro-action | ABC Oracle | 400 | 24px | 1.2 | normal | Large app-icon action label. |
| intro-body | ABC Oracle | 400 | 20px | 1.2 | normal | Opening support sentence. |
| body | InterVariable | 500 | 17px | 1.5 | normal | Default centered support sentence. |
| download | system-ui | 600 | 14px | 2.071 | -0.01em | Standard download action. |
| navigation | Marlin Soft SQ | 500 | 14px | 1.286 | -0.02em | Horizontal navigation links. |
| attribution | ABC Favorit Mono | 700 | 12px | 1.333 | 0.05em, uppercase | Outlined testimonial handle badge. |
| footer-link | InterVariable | 600 | 12px | 1.25 | 0.033em | Compact utility links. |
| footer-label | ABC Favorit Mono | 700 | 12px | 1.333 | 0.033em, uppercase | Footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| youth and community campaigns | campaign-display | Marlin Soft SQ | 700 | 56px | 0.857 | -0.05em | Two-line audience promise and closing headline. |
| youth and community campaigns | campaign-heading | Marlin Soft SQ | 700 | 40px | 1.15 | -0.05em | Campaign chapter headline. |
| youth and community campaigns | campaign-body | InterVariable | 500 | 20px | 1.3 | -0.01em | Campaign support and gallery captions. |
| feature launch pages | tour-heading | system-ui | 600 | 20px | 1.4 | normal | Feature title next to small outline icon. |
| youth and community campaigns | campaign-eyebrow | Marlin Soft SQ | 500 | 16px | 3 | 0.075em, uppercase | Audience label above promise. |
| youth and community campaigns | faq | InterVariable | 500 | 16px | 1.188 | normal | Collapsed questions. |
| feature launch pages | tour-body | InterVariable | 400 | 16px | 1.5 | normal | Instructional feature prose. |
| feature launch pages | tour-intro | Marlin Soft SQ | 400 | 16px | 1.5 | -0.02em | Two-line support under illustrated launch lettering. |
| feature launch pages | step-caption | system-ui | 400 | 15px | 1.3 | normal | Centered short setup instruction. |
| youth and community campaigns | campaign-mono | ABC Favorit Mono | 400 | 14px | 1.714 | 0.1em, uppercase | Platform availability and repeating campaign strip. |
| feature launch pages | activation | system-ui | 600 | 12px | 2.417 | -0.01em | Small activation action. |

**Notes:**

- Default landing pages combine the editorial serif invitation with soft grotesk chapter headings; do not extend the serif through every section.
- The headline scale is unusually compressed: 40px type sits on 39px lines, while the 56px campaign display sits on 48px lines. Keep bold forms and deliberate line breaks together.
- Body text remains neutral and more open. Mono appears as a tiny framing voice, not as paragraph typography.
- Only the campaign uses the roomier 40px/46px chapter recipe and 20px support; do not average it into the default scale.

## Layout

**Density:** Airy at section scale, compact inside text groups; the working interface consumes far more area than the surrounding copy.

### Spacing

**Spacing system:**

- **layout step** 8px — Dominant layout rhythm; the 32px declared padding is four steps. Button internals and campaign details also use 10px, 18px and 55px.

| Value | Use |
| --- | --- |
| 8px | Default heading-to-support gap and footer link rhythm. |
| 12px | Adjacent standard download actions. |
| 16px | Closing heading-to-action, testimonial grid and setup-card gap. |
| 24px | Quote-to-attribution gap and campaign heading-to-support gap. |
| 32px | Core side padding and technical hero text-group spacing. |
| 48px | Proof-band vertical padding. |
| 72px | Opening stage top padding. |
| 128px | White demonstration group top and bottom breathing room. |
| 160px | Campaign chapter separation and themed hero top allowance. |

### Containers and grids

- **navigation-container**: max width 1344px · side padding 32px. Centered outer navigation container; logo and compact links form a left-weighted cluster rather than spanning the whole width.
- **intro-media**: max width 1200px. Centered opening object occupying most of the horizontal canvas.
- **heading-container**: max width 900px · side padding 32px. Centered chapter heading, typically one or two short lines; support sits in a narrower measure below.
- **testimonial-row**: 4 columns · gap 16px. Four centered quote columns, up to 340px each with text constrained to 250px.
- **technical-media** (only for technical audience landing pages): max width 1198px. Large centered front-facing interface in technical benefit chapters.
- **tour-container** (only for feature launch pages): max width 1024px · side padding 32px. 960px inner feature tour with alternating 448px text and media columns separated by 64px.
- **setup-grid** (only for feature launch pages): max width 800px · 3 columns · gap 16px. Three equal 256px setup cards.
- **campaign-container** (only for youth and community campaigns): max width 1272px · side padding 55px. 1162px inner object width; campaign support remains around 608px.
- **campaign-gallery** (only for youth and community campaigns): gap 24px. Horizontal overflow rail of 600px-wide media cards, deliberately showing a partial next item.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | standard-actions | 10px |
|  | nav-and-badges | 8px |
|  | intro-action | 22px |
| youth and community campaigns | campaign-actions | 14px |
| youth and community campaigns | campaign-media | 20px |
| feature launch pages | setup-cards | 16px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | download | `rgba(0, 0, 0, 0.1) 0px 5px 5px 0px` | White and violet standard actions. |
|  | intro-action | `rgba(0, 0, 0, 0.25) 0px 2px 8px 0px` | App-icon action. |
| youth and community campaigns | window | `rgba(0, 0, 0, 0.25) 0px 14px 40px 0px` | Large campaign product windows. |
| feature launch pages | setup-card | `rgba(0, 0, 0, 0.1) 0px 2px 2px 0px` | Small cream setup cards. |

### Surfaces

#### White demonstration canvas · level 0

**Use:** Default long-form feature narrative.

**CSS:** `background: #ffffff`

**Observed:** Text floats directly on the canvas above enormous media, without enclosing every chapter in a card.

**Transfer:** Reserve card boundaries for actual grouped tasks or gallery objects.

#### Cream proof band · level 0

**Use:** Full-width press strip and testimonial field.

**CSS:** `background: #fffcec`

**Observed:** Warm cream interrupts white and saturated blue without adding another strong color.

**Transfer:** Use for real outside validation.

#### Grained blue paper · level 0

**Use:** Navigation, major proof stage and closing field.

**CSS:** `background-color: #3139fb; color: #fffcec`

**Observed:** Fine irregular light grain gives the fill a printed-paper quality. Scalloped seams distinguish bands; the closing divider is a hairline wave.

**Transfer:** Apply the grain as an independent low-contrast SVG layer, not a noisy text treatment.

#### Atmospheric opening paper · level 0

**Use:** Editorial invitation and product stage.

**CSS:** `background-color: #fffcec`

**Observed:** The center reads almost white; pale pink and buttery light gather along the upper corners, with a cool blue haze at the bottom. The lower object dissolves into that haze.

**Transfer:** Keep the central text field clear; match the soft glow rather than emphasizing gradient stops.

#### Slate paper · level 0

**Only for:** technical audience landing pages

**Use:** Technical opening and closing.

**CSS:** `background-color: #36566b; color: #fffcec`

**Observed:** Same grain and wavy seams as Grained blue paper, with a more restrained blue-gray field.

**Transfer:** Change the theme, not the chapter structure.

#### Lavender tour canvas · level 0

**Only for:** feature launch pages

**Use:** Continuous instructions and capabilities beneath a blue introduction.

**CSS:** `background: #e0e0f7`

**Observed:** Small cream setup cards sit above alternating media-and-copy rows.

**Transfer:** Keep related features on one uninterrupted field.

#### Launch media glass · level 1

**Only for:** feature launch pages

**Use:** Frame around the large opening demo.

**CSS:** `background: rgba(135, 135, 135, 0.22); border: 1px solid rgba(208, 208, 208, 0.19); border-radius: 16px; padding: 6px; box-shadow: rgba(0, 0, 0, 0.3) 0px 1px 6px 0px; backdrop-filter: blur(2px)`

**Observed:** A slim translucent rim surrounds a 1010px-wide video, overlapping the change from blue to lavender.

**Transfer:** Use a narrow protective frame rather than a giant frosted panel behind the copy.

#### Campaign ivory · level 0

**Only for:** youth and community campaigns

**Use:** Warm continuous campaign narrative.

**CSS:** `background: #f5f4e2; color: #3c3b3a`

#### Campaign putty band · level 0

**Only for:** youth and community campaigns

**Use:** Collectible-sticker campaign interlude.

**CSS:** `background: #e1e0ce`

**Observed:** Dark oversized lettering, edge-cropped stickers and a tiny mono repeat strip sit on the putty field.

**Transfer:** Treat the interlude as a printed event broadside.

## Components

### Navigation link

**Use:** Compact top navigation cluster.

**CSS:** `display: flex; align-items: center; gap: 6px; padding: 8px 10px; border: 1px solid transparent; border-radius: 8px; color: #ffffff; height: 36px; box-sizing: border-box`

**Text style:** `navigation` — Marlin Soft SQ 500 · 14px/1.286 · tracking -0.02em

**Observed:** Small logo precedes the cluster; a few entries have tiny pictograms. The fixed header carries the theme's grain and scalloped bottom edge. Campaign navigation reverses to warm charcoal on ivory.

### Download button

**Use:** Default conversion on colored paper and closing bands.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; background: #ffffff; color: #2702c2; border-radius: 10px; width: 273px; height: 45px; padding: 8px 0px; box-sizing: border-box; box-shadow: rgba(0, 0, 0, 0.1) 0px 5px 5px 0px`

**Text style:** `download` — system-ui 600 · 14px/2.071 · tracking -0.01em

**Observed:** A small filled platform mark precedes a single-line label. A second platform action can sit beside it with deep violet fill and white text; it is not an outline variant.

### App icon action

**Use:** Prominent opening invitation.

**CSS:** `display: flex; align-items: center; gap: 16px; background: rgba(0, 0, 0, 0.85); color: #ffffff; border-radius: 22px; padding: 8px 22px 8px 8px; height: 76px; box-sizing: border-box; box-shadow: rgba(0, 0, 0, 0.25) 0px 2px 8px 0px; backdrop-filter: blur(3px)`

**Text style:** `intro-action` — ABC Oracle 400 · 24px/1.2

**Observed:** A 60px rounded app icon sits at the left; the short label and gray right arrow complete a compact 214px-wide object. A smaller repeated version uses a 20px label and 18px corners.

**Transfer:** Use the new product's own icon, or a simple rounded colored symbol with a white rim.

### Attribution badge

**Use:** Credit beneath bold testimonial copy.

**CSS:** `background: #ffffff; color: #3139fb; border: 2px solid #3139fb; border-radius: 8px; padding: 4px 16px; text-transform: uppercase`

**Text style:** `attribution` — ABC Favorit Mono 700 · 12px/1.333 · tracking 0.05em · uppercase

**Observed:** A centered handle badge follows each quote by 24px; it reads like a little printed label rather than an avatar card.

### Testimonial column

**Use:** Readable social proof across a cream field.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 24px; max-width: 340px; color: #3139fb`

**Text style:** `quote` — Marlin Soft SQ 700 · 28px/1.071 · tracking -0.05em

**Observed:** Quote text has a narrow 250px measure and irregular natural line counts. Attribution badge ends the column; there is no enclosing card background.

### Footer link column

**Use:** Dense utility navigation beneath the final invitation.

**CSS:** `display: flex; flex-direction: column; gap: 8px; color: #fffcec`

**Text style:** `footer-link` — InterVariable 600 · 12px/1.25 · tracking 0.033em

**Observed:** Two small columns group product and resources beneath mono labels. An outline logo anchors the left, social marks sit under the links and a small editorial company signature is parked at the far lower right.

### Campaign download button

**Only for:** youth and community campaigns

**Use:** Heavier audience-specific conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; background: #3c3b3a; color: #ffffff; border-radius: 14px; padding: 18px 32px 18px 29px; height: 58px; box-sizing: border-box`

**Observed:** 18px semibold system text follows a filled platform icon. Primary and putty-filled secondary actions sit together with a 20px gap; the secondary uses warm charcoal text and is wider.

### Campaign feature tile

**Only for:** youth and community campaigns

**Use:** Horizontal gallery of concrete capabilities.

**CSS:** `background: #458aff; border-radius: 20px; width: 600px; height: 400px; overflow: hidden; position: relative`

**Text style:** `campaign-body` — InterVariable 500 · 20px/1.3 · tracking -0.01em

**Observed:** An inset working interface fills most of the colored tile. The title and one-sentence caption sit below, outside the colored backing. Subsequent backings are lime and lilac.

### FAQ row

**Only for:** youth and community campaigns

**Use:** Compact objection handling before footer.

**CSS:** `border-bottom: 1px solid rgba(14, 15, 16, 0.1); padding-bottom: 10px`

**Text style:** `faq` — InterVariable 500 · 16px/1.188

**Observed:** A blue plus is placed at the left of each question, not the far right. Inner question row has 8px padding and an 8px icon gap; rows are separated by 10px. The final row has no bottom rule.

**Transfer:** Keep answers factual; expanded styling is not prescribed.

### Setup step card

**Only for:** feature launch pages

**Use:** Short numbered activation instructions.

**CSS:** `display: flex; flex-direction: column; gap: 20px; background: #fffcec; border-radius: 16px; width: 256px; height: 306px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.1) 0px 2px 2px 0px`

**Text style:** `step-caption` — system-ui 400 · 15px/1.3

**Observed:** A 150px-tall interface detail tops the card; a raised number tile and centered instruction follow. The number tiles use different soft colors, thick white edges and small shadows.

### Activation button

**Only for:** feature launch pages

**Use:** Small, immediate feature activation.

**CSS:** `background: #ff3333; color: #ffffff; border-radius: 10px; height: 29px; padding: 0px 12px; box-shadow: rgba(0, 0, 0, 0.1) 0px 5px 5px 0px`

**Text style:** `activation` — system-ui 600 · 12px/2.417 · tracking -0.01em

**Observed:** The red action is unusually small relative to the blue stage and large demo, creating a single bright focal point.

## Imagery and graphics

### Working product windows

**Use:** Primary narrative imagery throughout the page.

**Observed:** Large, front-facing desktop windows show a believable task with colorful sidebars, browser chrome and real content: photography grids, shopping, editorial pages or maps. Windows occupy roughly four fifths of page width, often continuing beyond a viewport; gentle shadows lift them off white without device mockups.

**Transfer:** Show the new product doing one valuable thing. At minimum, construct a coherent window with a narrow navigation area and a richly populated task view; make the text and assets credible rather than scattering decorative widgets.

### Grain and scalloped seams

**Use:** Signature treatment for navigation and colored paper stages, including the ending.

**Observed:** Very fine cloudy grain modulates electric blue or slate. Small repeating rounded waves form band boundaries; the footer's upper divider is a thin cream sinusoidal line rather than a straight rule.

**Transfer:** Preserve both the tactile grain and the wave geometry in every new landing page, even when the product's imagery is minimal.

**Build:** Overlay a seamless SVG feTurbulence fractalNoise texture on the solid theme color at about 0.05 opacity. Tile a 16px-wide SVG wave with about 4px peak-to-trough relief along band edges; use a filled path for scallops and a 1px cream stroke with no fill for the footer divider. Keep the grain layer pointer-events:none and below text.

### Opening atmospheric wash

**Use:** Backing and lower fade for the editorial opening.

**Observed:** Pale pink glows in the top corners, soft yellow across the upper center and a blue mist along the bottom. The main interface emerges sharply at the top and becomes obscured below, allowing a dense object to meet a clean band boundary.

**Transfer:** Use a soft backlit stage behind the new product's main object; if no media is available, place one carefully built task window in the same haze.

**Build:** On cream paper, layer oversized radial gradients: pink rgba(235,160,225,0.35) at the upper left and right, warm rgba(255,224,130,0.25) across the top center, and blue rgba(115,170,220,0.35) at the bottom. Keep broad transparent centers. Put a matching pale-to-blue transparent gradient over the lower part of the interface; exact stops are not essential.

### Leaf-backed feature demo

**Only for:** feature launch pages

**Use:** Large introductory demo and smaller capability illustrations.

**Observed:** Dense dark green succulent leaves serve as a photographic wallpaper behind a light editorial document and a floating preview. The scene sits inside Launch media glass; the real-world texture contrasts with the artificial blue stage.

**Transfer:** Use a dark, closely framed botanical or similarly tactile natural texture behind a legible demonstration, not as a full-page background.

### Community scrapbook

**Only for:** youth and community campaigns

**Use:** Broad social-proof composition beneath a centered quantified headline.

**Observed:** A loose wall mixes portrait creator videos, landscape product videos, white social posts and chunky outlined stickers. Elements rotate slightly in both directions, overlap and vary in size. Cream gaps keep the irregular composition airy, with no equal-card grid.

**Transfer:** Use genuine creators and product-in-use moments with permission. A minimum version combines two real customer photos, two short quotes and simple die-cut symbols.

**Build:** Arrange mixed portrait and landscape rectangles across a wide relative container, using 10px–20px corners, rotations between -6deg and 6deg and shallow overlaps. Add a few original SVG doodles with thick white outer strokes and blue or pastel inner strokes, plus a light drop shadow.

### Campaign word sculpture and seals

**Only for:** youth and community campaigns

**Use:** Printed-broadside interlude.

**Observed:** A nearly full-width black, extremely heavy word sculpture dominates a putty band. Bright circular seals overlap and run off both lower side edges; small uppercase mono copy repeats across the top. Centered support and one dark action remain readable beneath the lettering.

**Transfer:** Create an original short campaign phrase as tightly packed vector lettering. If custom lettering is unavailable, use a very heavy extended sans compressed into one dramatic line; make simple original circular seals.

**Build:** Set an original 2–4-word phrase in a heavy extended face or custom SVG across about 90% of the band. Cluster 3–4 circles per lower corner, cropped by the band, with alternating blue, lime and warm colors; add curved uppercase text on SVG textPath and a central simple symbol. Keep the main action area free of overlap.

### Icons

**Observed:** Platform symbols are filled 16px marks in action text color; navigation pictograms are about 14px. Social marks and closing logos use cream. Feature-tour icons are 24px outline drawings with 2px round-ended strokes; the campaign FAQ uses a fine blue plus at the left.

**Transfer:** Use recognizable filled platform marks for downloads, restrained outline icons for capability labels and original larger doodles only in campaign art.

## Section recipes

How recurring sections are built.

### First screen: Editorial product invitation

**Observed:** A fixed grained blue navigation band with a scalloped lower edge crowns a 617px cream atmospheric stage, beginning after a 90px top allowance. Back to front: pale corner light, centered text, App icon action, enormous working interface and lower blue mist. The black 36px serif headline is a single compact line at desktop, about two fifths of the viewport width; support follows after 20px. The action is centered beneath, with a prominent rounded product icon. The 1200px-wide main object begins roughly halfway through the opening stage, showing a legible task while its lower half fades into mist. Within the first 900px, the complete invitation and action, the upper main object and the start of the next textured blue proof stage are visible; the second stage's download controls and full object lie below.

**Transfer:** For a different product, pair a short editorial invitation with one immediately understandable working scene; build a realistic simplified task window when polished media is unavailable. Technical audience pages instead open on slate paper with an attributed rounded-sans quote and one white download action. Feature launches use small illustrated lettering and a small red action over blue, followed by an overlapping demo. Youth campaigns open with a 56px two-line charcoal promise on ivory and paired 58px actions.

**Avoid:** Do not replace the opening with a left-copy/right-laptop SaaS split, a gigantic serif paragraph or a full-bleed photo. Keep one centered object and one primary invitation.

**Text style:** `intro-display` — Exposure VAR 700 · 36px/1 · tracking -0.02em

### Colored proof stage

**Observed:** Grained blue paper carries a centered 45.5px reversed quote, small attribution, contextual copy and Download button pair. A large colorful interface rises from the lower part of the stage and is clipped at its edge. A narrow Cream proof band follows with horizontally repeated press quotes.

**Transfer:** Use a real outside claim or concise promise followed by concrete product proof; preserve the contrast between compressed text and expansive object.

**Text style:** `display` — Marlin Soft SQ 700 · 45.5px/0.928 · tracking -0.04em

### Centered capability chapter

**Observed:** Heading-container centers a blue 40px headline and gray 17px support with an 8px gap on White demonstration canvas. The large working scene dominates the rest of the chapter. Technical variants place a 1198px-wide image 32px below support; broad video chapters reach the full 1440px canvas.

**Transfer:** Give each chapter one user outcome and one visual demonstration. Repeat the typography and alignment rather than inventing a new layout for every feature.

**Text style:** `heading` — Marlin Soft SQ 700 · 40px/0.975 · tracking -0.04em

### Compact reassurance

**Observed:** A short centered headline, support and bold blue arrow link sits on white without media. The narrative contracts after the long demonstration scenes, then leaves generous space before the final colored field.

**Transfer:** Use for trust, privacy, compatibility or a link to deeper customer stories, with one factual paragraph.

**Text style:** `heading` — Marlin Soft SQ 700 · 40px/0.975 · tracking -0.04em

### Quote field

**Observed:** Cream proof band carries four Testimonial columns in a row, with 48px band padding, blue bold text, 24px text-to-badge gaps and Attribution badges. The words carry the visual weight rather than stars or portraits.

**Transfer:** Use short verified reactions with different line lengths. Retain the small mono signature contrast.

**Text style:** `quote` — Marlin Soft SQ 700 · 28px/1.071 · tracking -0.05em

### Wave-divided closing

**Observed:** A 230px-high grained colored invitation centers a 28px closing line, italicizing one personal word, with a white Download button 16px beneath. A thin cream wave divides it from roughly 264px of footer navigation. Small link columns and an outline logo sit left; a small editorial signature sits low on the far right. Technical pages use slate; feature launches return to blue.

**Transfer:** End with a warm destination metaphor and one action, followed by a deliberately small footer. Keep the tactile seam and asymmetry even with different legal links.

**Text style:** `closing` — Marlin Soft SQ 700 · 28px/1.1 · tracking -0.05em

### Feature launch tour

**Only for:** feature launch pages

**Observed:** A blue opening with illustrated outline lettering leads into Lavender tour canvas. Setup step cards sit in a three-column 800px row. Blue centered headings introduce an alternating two-column tour with 448px text/media sides and a 64px gap; the last demo expands across 960px. A centered FAQ heading and simple arrow link conclude the tour before Wave-divided closing.

**Transfer:** Use for a contained feature family that benefits from activation instructions, not for every general product page.

**Text style:** `tour-heading` — system-ui 600 · 20px/1.4

### Campaign collage and rail

**Only for:** youth and community campaigns

**Observed:** Campaign ivory holds a 40px centered proof headline and 20px support separated by 24px, followed by Community scrapbook. Subsequent chapters combine a large window with inline pictogram-and-word highlights; the feature rail uses Campaign feature tiles with colored backings and external captions.

**Transfer:** Adapt the audience language and authentic proof; retain the contrast between ordered text and informal collected media.

**Text style:** `campaign-heading` — Marlin Soft SQ 700 · 40px/1.15 · tracking -0.05em

### Campaign broadside and ending

**Only for:** youth and community campaigns

**Observed:** Campaign putty band carries Campaign word sculpture and seals, with a repeating mono strip and a dark action. The closing returns to ivory: a 56px promise, paired download actions and uppercase platform availability. Four left-plus FAQ rows come after the invitation, then a compact blue footer without a second colored closing invitation.

**Transfer:** Use a campaign identity interlude and an audience-specific final promise. Retain the unusual post-action FAQ placement when practical.

**Text style:** `campaign-display` — Marlin Soft SQ 700 · 56px/0.857 · tracking -0.05em

## Page flow

**Storyline:** Personal invitation → visible product proof → outcome-led demonstrations → trust or community validation → warm closing action and small utility footer.

### Broad product landing page with a newer-product invitation

1. **promise** — Editorial serif invitation on atmospheric paper, app-icon action and a large working window.
2. **product demonstration** — Blue quote-led conversion stage, oversized interface and cream press strip.
3. **capability chapters** — Repeated centered blue headings on white, one expansive working scene per benefit.
4. **reassurance** — Compact trust statement and deeper-reading link.
5. **social proof** — Cream quote field with mono attribution badges.
6. **closing call** — Grained blue invitation, white action, cream wave and compact asymmetrical footer.

**Transfer:** Use the main product's promise and proof; a second product pitch is not necessary to preserve the composition.

### Audience-specific technical landing page

1. **promise** — Slate textured hero, audience eyebrow, attributed quote with one italicized word, download and large split working window.
2. **social proof** — Narrow cream press strip.
3. **capability chapters** — Three large front-facing demonstrations beneath centered blue outcome headings.
4. **community validation** — Short text block and interview-series arrow link.
5. **closing call** — Slate version of the wave-divided closing and small footer.

**Transfer:** Lead with an audience-relevant endorsement, demonstrate their workflows and link to deeper practitioner proof.

### Contained feature-family launch and activation guide

1. **promise** — Small hand-drawn outline product lettering on blue, brief support, tiny red activation and glass-framed demo.
2. **onboarding** — Three cream numbered setup cards on lavender.
3. **capability chapters** — Alternating instructional text and media, ending with a wide demo.
4. **objection handling** — Centered FAQ heading and external question link.
5. **closing call** — Return to blue with wave-divided action and footer.

**Transfer:** Favor quick activation and literal instructions over long manifesto copy.

### Youth or community acquisition campaign

1. **promise** — Large charcoal audience promise on ivory, paired platform actions, mono availability and large window.
2. **quantified proof** — One proof number embedded in a rounded headline above a creator scrapbook.
3. **capability chapters** — Audience-life organization scene and horizontal colored feature rail.
4. **community invitation** — Putty broadside with huge word sculpture, cropped circular stickers and one action.
5. **closing call** — Return to a large personal promise and paired downloads on ivory.
6. **objection handling** — Left-plus FAQ rows after the action, then compact blue utility footer.

**Transfer:** Use audience-specific wit, real social proof and original campaign art; do not turn the entire site into the campaign theme.

## Writing

Warm, optimistic and conversational, with confidence grounded in everyday relief rather than technical superiority alone. Small jokes and human metaphors soften concrete descriptions of what the tool does.

**Do not copy:** Do not reuse Arc, Dia, The Browser Company, their logos or artwork, customer handles and quotations, school counts, certification claims, update promises or campaign names as the new product's assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; the product is a helpful companion. Use we sparingly for responsibilities such as privacy.
- **Rhythm:** Short benefit-led headlines alternate with one-sentence explanations. Occasional fragments, em dashes, parentheses and a single italicized personal word give conversational emphasis.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening invitation | Direct introduction with a compact evolution or destination idea. | 7–10 words | “Meet Dia, the next evolution of [Brand]” |
| Capability headline | Name an everyday benefit, often with your, rather than a feature inventory. | 3–11 words | “Space for the different sides of you.”<br>“Switch between accounts in one click.” |
| Supporting line | Explain the outcome, then the mechanism in plain language. | 12–28 words | “Clean and calm, [Brand] shapes itself to how you use the internet.” |
| Primary action | Plain verb plus product or platform; minimal persuasion inside the button. | 2–5 words | “Download [Brand] for Mac”<br>“Get Started” |
| Audience wit | A familiar audience phrase with a playful overstatement or aside. | 5–12 words | “Features so good, they feel illegal”<br>“Multitask (or procrastinate) with up to three tabs side-by-side.” |
| Closing line | Invite the reader into a better everyday place, with personal emphasis. | 6–10 words | “Enter your new home on the internet” |

**Words and phrasing to use:** your perfect setup; space; feel; effortlessly; one click; let it do more; home; clean and calm

**Avoid:** revolutionary enterprise ecosystem; unlock unparalleled synergy; industry-leading solution; 10x everything; aggressive urgency

**Rules:**

- Write the user outcome before naming the mechanism.
- Use one small joke at a time; keep instructions literal.
- Qualify trust and safety statements with precise facts.
- Use real quotations as quotations, not invented endorsements.
- Let a short arrow link carry deeper explanation rather than swelling the support paragraph.

## Do's and Don'ts

### Do

- Keep core chapter headlines at 40px/39px, weight 700 and -0.04em tracking.
- Use an 8px heading-to-support gap for default demonstration chapters.
- Let working interfaces occupy about 1200px of a 1440px desktop canvas.
- Give blue and slate bands fine grain and repeating wavy seams.
- Use 273px by 45px white download actions on colored closing bands.
- Pair 28px testimonial text with 12px uppercase mono attribution badges.
- Keep default feature prose at 17px/25.5px while giving campaign prose its own 20px/26px recipe.
- Close with a warm invitation and a small asymmetrical footer, preserving the 230px action band where that ending is used.

### Don't

- Do not turn 10px standard button corners into fully rounded pills.
- Do not put every working scene in an equal-sized bento card; default demonstrations live directly on white.
- Do not apply the campaign's 56px charcoal headline and lime gallery palette to ordinary chapters.
- Do not substitute blue-gray body text for the default #696969 support on white.
- Do not turn fine paper grain into coarse distressed lettering or heavy photographic grit.
- Do not enlarge 12px footer links to compete with the final 28px invitation.
- Do not center all footer utilities into a symmetric stack at desktop; keep the link cluster left and signature low right.
- Do not use a full-page dark mode simply because a product demo contains a dark interface.

## Motion and responsive

### Motion

**Observed:**

- The press-proof strip is a horizontally translated marquee with repeated children and clipped overflow.
- Large product demonstrations use video; no action transitions or animation timings are established.

**Transfer:**

- Preserve the horizontal strip's continuous-proof character; keep individual quotes readable and avoid extending the ticker treatment to every heading.
- Use motion to show one product task inside the large window, not to animate the entire paper stage.

**Unknown:**

- Exact marquee speed, video timing, scroll triggers and easing assignments are not established.

### Responsive

**Observed:**

- Desktop compositions use centered maximum-width containers and a horizontally scrollable campaign feature rail.
- Styles declare width breakpoints including 480px, 600px, 650px, 800px and 960px; their full layout behavior is not established.

**Transfer:**

- For narrow layouts, retain the centered invitation and scalloped bands; reduce the product window proportionally rather than swapping to a generic phone mockup.
- Allow paired actions and quote columns to stack while retaining their own text recipes; keep campaign gallery overflow intentional.
- Simplify sticker clusters at the edges without covering the campaign action.

**Unknown:**

- Mobile type sizes, header collapse, exact breakpoint assignments and touch interactions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
