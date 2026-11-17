# Milanote — editorial creative workbench

## Overview

An approachable editorial style that pairs sturdy literary serifs with clean sans-serif explanations and expansive visual demonstrations. Slate blue, white and cool paper gray form the setting, with small orange actions and a concentrated electric-blue interruption. Interface scenes, loose visual collages and playful geometric characters make useful software feel like a creative studio rather than an enterprise dashboard. The density is low in the marketing copy and deliberately richer inside the product imagery.

### Essentials

- Literary confidence without oversized typography: Tiempos headlines at 64px/1.333, weight 600, with almost neutral 0px tracking; supporting Inter at 28px/1.25 makes the promise friendly rather than monumental.
- A centered promise sits above a real work surface: an 84px slate navigation, one-line headline, support line and compact orange action lead into an 1116×630px interface panel beginning within the first screen.
- The action is a small orange rectangle, not a pill: white 16px bold type, 10px 16px padding and 6px corners; the form version becomes 40px high with 4px corners.
- Color belongs to the work more than the page: most explanatory space is white or cool gray, slate anchors the opening and ending, orange stays concentrated in actions, and a single 596px electric-blue band supplies a high-energy counterpoint.
- Demonstrations are physical-looking sheets of work: 10.3px corners and a two-part 0px 16px 56px 4px / 0px 2px 10px shadow lift the broad interface above the page. Use a believable composed workflow when a working interface is unavailable.
- Creative abundance appears as a clipped horizontal gallery: 312×453px cool-gray cards, 24px corners and 20px gaps combine serif labels, brief descriptions and colorful work collages.
- Conversion ends with a smile: a centered 440px white registration panel on finely textured cool gray, surrounded near its base by orange-and-charcoal geometric characters, scribbles and dashed trajectories. Recreate this as simple original vector shapes if bespoke illustration is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Studio slate | `#303b4b` | `--color-slate` | background, text | Default dark opening, gallery and footer; heading ink on white. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action orange | `#f4511c` | `--color-orange` | action, link, accent | Primary conversion actions and contextual guide links; small areas rather than general section backgrounds. |
| Device blue | `#1465ff` | `--color-blue` | background | A concentrated full-width device or access capability band. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-paper` | background, surface, text | Explanatory canvas, raised panels and text on dark backgrounds. |
| Cool work surface | `#ebedee` | `--color-cool-paper` | background, surface | Gallery cards, interface backing and illustrated conversion stage. |
| Blue-band silver | `#d3dfff` | `--color-blue-copy` | text | Supporting copy on the electric-blue band. |
| Input edge | `#bbbec3` | `--color-field-edge` | border | Inset 1px outlines on default registration fields and provider buttons. |
| Muted silver | `#a2a7af` | `--color-muted-on-dark` | text | Opening support line and footer links. |
| Chapter rule | `#757c87` | `--color-rule` | border | Short centered dividers between expansive demonstration chapters. |
| Form gray | `#5f6672` | `--color-form-copy` | text | Form labels, provider button text and account help. |
| Slate body | `#5d6673` | `--color-body` | text | Default explanatory paragraphs and gallery descriptions. |
| Raised slate | `#46505f` | `--color-secondary-action` | action, surface | Secondary login action against slate. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| audience and detailed product pages | Editorial charcoal | `#31303a` | `--color-charcoal` | background, text | Dark bands and primary ink in audience and detailed product pages. |
| audience and detailed product pages | Light gray band | `#f2f2f2` | `--color-soft-gray` | background | Alternating explanatory bands and large overview stage. |
| audience and detailed product pages | Editorial gray | `#6e6e71` | `--color-editorial-body` | text | Longer feature paragraphs and bullet lists. |
| audience and detailed product pages | Editorial lead gray | `#818181` | `--color-editorial-lead` | text | Centered overview descriptions. |
| audience and detailed product pages | Editorial silver | `#cacaca` | `--color-editorial-silver` | text | Opening description against charcoal. |
| template showcases | Template action paper | `#f8f8f8` | `--color-template-paper` | action | Light secondary conversion button inside a dark template showcase. |
| template showcases | Selected tab silver | `#e5e5e5` | `--color-selected-copy` | text | Selected template tab label. |
| product-positioning callouts | Explanatory violet | `#4f5eff` | `--color-violet` | surface | A single overlapping information strip with white explanation. |
| audience and detailed product pages | Closing gradient gray | `#d7d7d7` | `--color-gradient-base` | background | Bottom of the illustrated conversion background gradient. |

## Typography

- **Tiempos** — Hero promises, section headings, gallery titles and conversion headings. Sturdy editorial serif with softly bracketed forms, expressive terminals and substantial semibold or bold weight. If unavailable, use **Source Serif 4**. Use 600 and 700; retain the broad editorial forms and generous line height. Font stack: "Tiempos", "Source Serif 4", Georgia, serif.
- **Inter** — Default marketing support copy, navigation, gallery descriptions and footer. Clean, direct sans-serif that contrasts with the warm serif. Font stack: "Inter", Arial, sans-serif.
- **Source Sans** (only for audience and detailed product pages) — Long-form product explanations, tabs and actions. Open humanist sans-serif, less geometric and more reading-oriented than the default sans. If unavailable, use **Source Sans 3**. Font stack: "Source Sans", "Source Sans 3", Helvetica, Arial, sans-serif.
- **system-ui** (only for registration forms) — Registration controls and labels. Compact familiar native interface typography. Font stack: "system-ui", "Segoe UI", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Tiempos | 600 | 64px | 1.333 | -0.0005em | Centered opening promise and large gallery introduction. |
| heading | Tiempos | 700 | 40px | 1.333 | -0.0008em | Demonstration chapter titles and device-band heading. |
| hero-support | Inter | 400 | 28px | 1.25 | -0.001em | Single centered sentence below the opening promise. |
| section-support | Inter | 400 | 24px | 1.25 | -0.001em | Short centered descriptions above product demonstrations. |
| conversion-heading | Tiempos | 700 | 24px | 1.333333 | -0.001em | Default registration panel heading. |
| device-support | Inter | 400 | 24px | 1.333 | -0.001em | Left-aligned supporting text on the electric-blue device band. |
| card-heading | Tiempos | 700 | 20px | 1.333 | -0.0015em | Centered gallery card labels. |
| body | Inter | 400 | 16px | 1.5 | -0.001em | Gallery descriptions and compact marketing copy. |
| action | Inter | 700 | 16px | 1.333 | -0.001em | Default navigation, orange actions and footer column headings. |
| small-label | Inter | 400 | 16px | 1.333 | -0.001em | Footer links and small social-proof introduction. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| audience and detailed product pages | editorial-display | Tiempos | 600 | 48px | 1.333 | normal | Left-aligned opening headline. |
| audience and detailed product pages | editorial-heading | Tiempos | 600 | 36px | 1.333 | normal | Centered overview and dark showcase titles. |
| audience and detailed product pages | editorial-conversion-heading | Tiempos | 600 | 30px | 1.3 | normal | Heading of the wider registration panel. |
| audience and detailed product pages | editorial-feature-heading | Tiempos | 600 | 24px | 1.333 | normal | Alternating feature-chapter titles. |
| audience and detailed product pages | editorial-hero-support | Source Sans | 400 | 24px | 1.6 | normal | Opening description on charcoal. |
| audience and detailed product pages | editorial-overview-support | Source Sans | 400 | 22px | 1.36 | normal | Centered overview explanation. |
| audience and detailed product pages | editorial-body | Source Sans | 400 | 20px | 1.35 | normal | Feature-chapter paragraphs and inline orange links. |
| template showcases | template-tab | Source Sans | 600 | 18px | 1.333 | normal | Template selector labels. |
| audience and detailed product pages | editorial-detail | Source Sans | 400 | 16px | 1.5 | normal | Feature lists and information-strip explanation. |
| audience and detailed product pages | editorial-action | Source Sans | 600 | 16px | 1.333 | normal | Orange actions and light template buttons. |
| product-positioning callouts | callout-heading | Source Sans | 700 | 16px | 1.333 | normal | Bold introductory statement in the violet information strip. |
| registration forms | form-action | system-ui | 600 | 14px | 20px | -0.001em | Provider buttons, form submission and account action. |
| registration forms | form-label | system-ui | 500 | 14px | 20px | -0.001em | Labels above fields and agreement text. |

**Notes:**

- The serif is reserved for promises and titles; explanations remain sans-serif. The default headline has generous leading, not a tight fashion-display setting.
- Tracking is almost neutral even at 64px. Do not substitute visibly compressed letterspacing for the serif's natural character.
- Use Inter for the default landing-page system; switch consistently to Source Sans for the scoped editorial page family rather than mixing both within a paragraph hierarchy.

## Layout

**Density:** Airy marketing composition around deliberately dense visual work surfaces; long pauses separate broad demonstrations, while forms and gallery captions are compact.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Gallery title-to-description gap and form label-to-field gap. |
| 12px | Provider-button stack and paired name-field gap. |
| 16px | Navigation action gap. |
| 20px | Gallery card gap and vertical field-group spacing. |
| 22px | Chapter heading-to-description gap and hero support-to-action gap. |
| 24px | Major groups inside the registration panel. |
| 48px | Description-to-demonstration gap and opening headline top padding. |
| 56px | Opening copy block-to-product stage pause. |
| 70px | Top and bottom space around editorial feature copy. |
| 96px | Top padding of the default illustrated registration section. |
| 112px | Chapter-rule-to-title pause. |
| 120px | Demonstration-to-next-chapter-rule pause and bottom padding of dark proof band. |
| 156px | Bottom breathing room of the default illustrated conversion stage. |

### Containers and grids

- **main-stage**: max width 1116px. Centered default product panels and footer; leaves 162px side margins at a 1440px viewport.
- **heading-pair**: max width 893px. Centered explanatory heading and support copy, narrower than the product stage.
- **gallery-track**: gap 20px · side padding 20px. Single horizontally scrolling row of 312px-wide cards, with a partial next card visible at the right.
- **proof-row**: 6 columns · gap 24px. A restrained horizontal row of 166×83px logo cells on slate.
- **registration**: max width 440px · side padding 40px. Centered conversion panel with 360px usable control width.
- **editorial-container** (only for audience and detailed product pages): max width 1170px · side padding 30px. Alternating feature chapters; approximately 459px copy column with a 735px visual allowed to extend past the container edge.
- **editorial-overview** (only for audience and detailed product pages): max width 1000px. Centered full-interface overview.
- **template-stage** (only for template showcases): max width 946px. Centered template demonstration beneath heading and action.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing-actions | 6px |
|  | product-panel | 10.3px |
|  | gallery-card | 24px |
|  | registration-panel | 16px |
|  | registration-controls | 4px |
|  | gallery-arrow | 50% |
| audience and detailed product pages | editorial-controls | 3px |
| audience and detailed product pages | editorial-overview | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | product-panel | `rgba(0, 0, 0, 0.16) 0px 16px 56px 4px, rgba(0, 0, 0, 0.08) 0px 2px 10px 0px` | Broad floating product panels and circular gallery control. |
|  | gallery-card | `rgba(0, 0, 0, 0.1) 0px 5px 10px 0px` | Cool-gray gallery cards on slate. |
|  | registration-panel | `rgba(27, 37, 54, 0.08) 0px 12px 28px 0px, rgba(27, 37, 54, 0.03) 0px 8px 8px -2px, rgba(27, 37, 54, 0.04) 0px 3px 3px -1.5px` | Soft elevation under the default white conversion panel. |
| audience and detailed product pages | editorial-overview | `rgba(0, 0, 0, 0.2) 0px 5px 10px 0px, rgba(0, 0, 0, 0.2) 0px 10px 30px 0px` | Smaller centered interface overview. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default explanatory page field.

**CSS:** `background: #ffffff`

#### Slate band · level 0

**Use:** Opening, gallery, social proof and footer.

**CSS:** `background: #303b4b; color: #ffffff`

**Observed:** Broad uninterrupted fields, not dark cards nested inside light sections.

**Transfer:** Use slate as the structural frame surrounding white explanation.

#### Raised product sheet · level 1

**Use:** Large product demonstrations.

**CSS:** `background: #ffffff; border-radius: 10.3px; box-shadow: rgba(0, 0, 0, 0.16) 0px 16px 56px 4px, rgba(0, 0, 0, 0.08) 0px 2px 10px 0px; overflow: hidden`

**Observed:** The interface occupies almost the entire sheet, including a narrow toolbar.

**Transfer:** Show a complete believable workspace, not an empty browser frame.

#### Textured conversion stage · level 0

**Use:** Illustrated registration ending.

**CSS:** `background-color: #ebedee`

**Observed:** A very fine low-contrast grain or dotted paper texture under a white panel and low-positioned collage.

**Transfer:** Use a subtle repeating SVG noise texture at roughly 12px tile scale; preserve the pale cool-gray field rather than turning it into a patterned wallpaper.

#### Electric-blue band · level 0

**Use:** A concentrated access or cross-device chapter.

**CSS:** `background: #1465ff; color: #ffffff; overflow: hidden`

**Observed:** One uninterrupted field behind white serif text and overlapping device images.

**Transfer:** Reserve this high-saturation treatment for one contrasting capability statement.

#### Editorial alternating band · level 0

**Only for:** audience and detailed product pages

**Use:** Longer feature explanations.

**CSS:** `background: #f2f2f2`

**Observed:** Alternates with white; one audience chapter also uses cool work-surface gray.

**Transfer:** Alternate broad bands instead of adding bordered feature cards.

#### Editorial dark stage · level 0

**Only for:** audience and detailed product pages

**Use:** Split opening, template showcase and footer.

**CSS:** `background: #31303a; color: #ffffff`

#### Editorial closing gradient · level 0

**Only for:** audience and detailed product pages

**Use:** Illustrated registration stage behind the wider panel.

**CSS:** `background: linear-gradient(to bottom, #ffffff 10%, #d7d7d7 85%)`

**Observed:** Large orange, black and gray geometric characters occupy the sides, with charcoal extending behind the panel's bottom.

**Transfer:** Keep the gradient neutral so the illustration and action supply the color.

## Components

### Navigation

**Use:** Persistent default brand and conversion controls.

**CSS:** `display: flex; position: sticky; top: 0px; height: 84px; padding: 0px 24px; justify-content: space-between; align-items: center; background: #303b4b; z-index: 2; box-shadow: rgba(0, 0, 0, 0.192) 0px 1.3px 8.3px 0px`

**Text style:** `action` — Inter 700 · 16px/1.333 · tracking -0.001em

**Observed:** Compact circular mark and serif wordmark at left; usage menu with down-chevron, secondary login and orange action at right. The action group uses a 16px gap. Editorial pages instead use a 100px non-sticky charcoal header within the centered content width.

**Transfer:** Keep the left identity and right conversion cluster; avoid turning the menu into a long sitemap.

### Primary button

**Use:** Main marketing conversion action.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #f4511c; color: #ffffff; border-radius: 6px; padding: 10px 16px`

**Text style:** `action` — Inter 700 · 16px/1.333 · tracking -0.001em

**Observed:** Text-only compact rectangle, centered below opening support and repeated in navigation. The default label yields about 151×41px. Registration uses the form-action recipe, 4px corners, 10px 14px padding and full 360px width. Editorial pages use Source Sans semibold, 3px corners and a 40px height.

**Transfer:** Keep a short verb-led label and consistent orange rather than making the opening button oversized.

### Secondary button

**Use:** Login alongside the main conversion action.

**CSS:** `background: #46505f; color: #ffffff; border-radius: 6px; padding: 10px 16px`

**Text style:** `action` — Inter 700 · 16px/1.333 · tracking -0.001em

**Observed:** Same vertical construction as the primary action but reduced visual contrast. Editorial headers instead use a transparent 3px-radius button with a 1px gray outline.

**Transfer:** Use the slate-on-slate version by default.

### Product panel

**Use:** Primary visual proof throughout the default page.

**CSS:** `max-width: 1116px; aspect-ratio: 1116 / 630; background: #ffffff; border-radius: 10.3px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.16) 0px 16px 56px 4px, rgba(0, 0, 0, 0.08) 0px 2px 10px 0px`

**Observed:** Broad straight-on application view with a white toolbar over a cool-gray work area. The same frame is reused for different modes of work.

**Transfer:** Change the actual workflow content, not the surrounding frame treatment.

### Gallery card

**Use:** Audience or application discovery on a dark band.

**CSS:** `width: 312px; height: 453px; background: #ebedee; border-radius: 24px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.1) 0px 5px 10px 0px`

**Text style:** `card-heading` — Tiempos 700 · 20px/1.333 · tracking -0.0015em

**Observed:** Centered serif title, two-line sans description and full-width collage below. Header padding is 29px 32px 24px, title-to-copy gap 6px, image about 312×320px. Cards sit in a horizontally clipped row with a 44px white circular arrow at the right.

**Transfer:** Use distinct examples of the new product's work, not generic feature icons.

### Registration panel

**Use:** Full conversion form at the narrative ending.

**CSS:** `display: flex; flex-direction: column; gap: 24px; max-width: 440px; padding: 32px 40px; background: #ffffff; border-radius: 16px; box-shadow: rgba(27, 37, 54, 0.08) 0px 12px 28px 0px, rgba(27, 37, 54, 0.03) 0px 8px 8px -2px, rgba(27, 37, 54, 0.04) 0px 3px 3px -1.5px`

**Text style:** `conversion-heading` — Tiempos 700 · 24px/1.333333 · tracking -0.001em

**Observed:** Heading and reassurance, provider buttons, ruled OR divider, paired name fields, email, password with eye control, agreement and update checkboxes, orange submit, account link and small legal line. Editorial variant is 520px wide with 35px 30px padding, 6px corners and 1px rgba(48,48,58,0.2) edge; there the provider buttons follow submission.

**Transfer:** Preserve the floating form and reassuring hierarchy; adjust field requirements to the new service.

### Text field

**Use:** Default registration inputs.

**CSS:** `height: 40px; border-radius: 4px; padding: 10px 14px; background: #ffffff; box-shadow: rgb(187, 190, 195) 0px 0px 0px 1px inset`

**Text style:** `form-label` — system-ui 500 · 14px/20px · tracking -0.001em

**Observed:** Persistent label sits above the input with a 6px gap; field groups have 20px spacing. First and last name share a row with a 12px gap. Password includes a small right-side eye.

**Transfer:** Keep the labels external and the border thin rather than using filled floating-label controls.

### Provider button

**Use:** Alternative registration paths.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 12px; height: 40px; padding: 10px 14px; background: #ffffff; color: #5f6672; border-radius: 4px; box-shadow: rgb(187, 190, 195) 0px 0px 0px 1px inset`

**Text style:** `form-action` — system-ui 600 · 14px/20px · tracking -0.001em

**Observed:** Recognizable 20px provider icon precedes the centered label; two full-width controls form a stack.

**Transfer:** Use only supported providers and their official small marks.

### Footer column

**Use:** Utility navigation at the true page ending.

**CSS:** `width: 190px; color: #a2a7af`

**Text style:** `small-label` — Inter 400 · 16px/1.333 · tracking -0.001em

**Observed:** Four columns of white bold headings and muted links on slate, within an 1116px content grid. Brand and language control occupy a wider left zone; small social icons finish the lower left and copyright the lower right. Link rows have roughly 18.5px top separation. Editorial endings use four 225px columns in a 1000px container, 40px line height, and a centered small brand lockup below.

**Transfer:** Keep the footer spacious and useful; do not end the page at the conversion card.

### Template tab

**Only for:** template showcases

**Use:** Selection among concrete starting points.

**CSS:** `background: rgba(255, 255, 255, 0.15); color: #e5e5e5; border-radius: 3px; padding: 5px 17px 7px`

**Text style:** `template-tab` — Source Sans 600 · 18px/1.333

**Observed:** Small introductory label and horizontal text tabs above the title; selected tab has a subtle translucent white fill, other tabs are unfilled white text.

**Transfer:** Name outputs the new product can genuinely create.

### Template action

**Only for:** template showcases

**Use:** Light action between showcase title and interface.

**CSS:** `background: #f8f8f8; color: #31303a; border-radius: 3px; padding: 8px 40px 10px`

**Text style:** `editorial-action` — Source Sans 600 · 16px/1.333

**Observed:** Centered text-only rectangle with the demonstration starting about 49px below.

**Transfer:** Link the selected example directly to its usable starting point.

### Information strip

**Only for:** product-positioning callouts

**Use:** Explain how the product complements a familiar tool or workflow.

**CSS:** `position: relative; background: #4f5eff; color: #ffffff; padding: 24px 30px 30px 150px; transform: translate3d(0px, -90px, 0px); box-shadow: rgba(0, 0, 0, 0.15) 0px 15px 15px 0px, rgba(0, 0, 0, 0.15) 0px 2px 8px 0px`

**Text style:** `callout-heading` — Source Sans 700 · 16px/1.333

**Observed:** A square-cornered strip about 802×180px extends from the left viewport edge across the opening-to-overview boundary. A white circular information symbol sits left of a bold lead and 16px/24px explanation.

**Transfer:** Use for a specific category distinction, not a generic announcement banner.

## Imagery and graphics

### Living product workbench

**Use:** Opening and repeated demonstration chapters.

**Observed:** Straight-on wide interface sheets combine photos, text cards, colored notes, file icons, video thumbnails, curved connectors and small annotations on cool-gray backing. Photography ranges from monochrome portraits and architecture to colorful tactile objects. The surrounding page stays neutral; the work carries most of the color. One demonstration uses a dark interface without changing the white marketing canvas.

**Transfer:** Create a coherent example project for the new product with readable high-level groups, several media types and visible progress. If no interface exists, compose an original prototype with real example content, a slim toolbar and 4–8 meaningful work objects rather than empty rectangles.

**Build:** Inside the Product panel, place a slim white toolbar over #ebedee. Arrange uneven white note sheets, two photographic rectangles and small colored file symbols in loose columns; add a few thin SVG connector curves. Keep most objects aligned but allow selective overlaps and handwriting-like annotations. Use original content and product-specific control shapes.

### Gallery work collages

**Use:** Images inside Gallery card.

**Observed:** Media fills the lower portion of each tall card and is clipped at its rounded edges. Portraits, product photography, bright note strips and miniature interface objects overlap like work pinned to a board.

**Transfer:** Use a distinct small collage per application or audience, with the same cool-gray backing and a mix of photographic and functional elements.

**Build:** Keep the top approximately 134px for the title and description. Fill the remaining 320px with three or four rectangular media objects at varied sizes, a small colored note and one curved connector; allow bottom and side objects to bleed beyond the clipping boundary.

### Geometric studio characters

**Use:** Signature illustrated conversion ending.

**Observed:** Orange spheres and faceted gems, gray blocks and cylinders with simple faces, black drawn hands, dashed orbital paths and halftone or fine-hatched circles surround the white form. The default version keeps most objects low along the base; the editorial version uses taller side compositions. Materials are grainy and tactile rather than polished glossy 3D.

**Transfer:** Create original abstract mascots from geometry; the minimum is a small set of expressive SVG shapes with texture and a few gestural lines. Keep the panel's readable center clear.

**Build:** Layer a pale #ebedee field with low-opacity gray dot texture; add off-center circles and polygons near the bottom corners, using #f4511c for 2–3 focal shapes and #303b4b for dark hands or outlines. Shade spheres with a radial gradient from orange to slate, apply subtle SVG turbulence grain, and give gray blocks alternating light and dark faces. Add sparse dashed curved paths, diagonal hatch circles and simple dot eyes or single-line smiles. Keep these behind and outside the 440px panel.

### Device family

**Use:** Electric-blue access chapter.

**Observed:** A desktop monitor sits behind an overlapping tablet and phone; the three share a related workspace. Devices dominate the right two thirds and meet the lower edge, while the left column contains a two-line serif heading and narrow pale-blue support copy.

**Transfer:** Use actual supported form factors. Without device renders, create flat bezel silhouettes with consistent screens and restrained shadows; preserve the size hierarchy and overlap.

### Editorial collage chapters

**Only for:** audience and detailed product pages

**Use:** Alternating detailed feature bands.

**Observed:** A roughly 735×700px visual alternates left and right of a smaller text column. Some are complete interface views extending offscreen; others remove the browser chrome and scatter photos, white note sheets, thin arrows, a hand-drawn circle or star, and small file nodes directly over white or gray.

**Transfer:** Show the specific outcome of each feature with 3–5 related objects instead of repeating identical full-interface views.

**Build:** Use a broad transparent SVG or HTML composition: a large rectangular photo, two smaller white note cards, one small file tile and a thin curved SVG connector. Align some edges while letting one object overlap. Keep any saturated note or symbol local to the visual, never as a whole-band tint.

### Icons

**Observed:** Icons are sparse outside product scenes: compact chevrons, a 44px circular gallery next control, 20px provider marks and eye control, and 24px social icons. Functional outlines use about 2px round strokes in muted slate; provider marks retain their own colors.

**Transfer:** Choose simple legible round-stroke utility icons and keep them subordinate to text. Use a single small arrow for gallery navigation rather than adding decorative feature icons everywhere.

## Section recipes

How recurring sections are built.

### First screen: Centered workbench opening

**Observed:** The 84px Navigation and slate hero form one continuous background. A centered 64px semibold serif promise spans roughly two thirds of the screen and is padded 48px from the hero top. A 28px muted support sentence follows almost immediately; the compact Primary button sits 22px below. After a 56px pause, the 1116×630px Product panel begins at about 373px down the viewport and occupies most of the remaining first screen. Back to front: slate field, a gently rising diagonal white transition near the lower right, softly shadowed interface sheet, then its dense photographic and note-card content. Within 900px the headline, support, action and most of the interface are visible; its final portion extends below the fold.

**Transfer:** Keep the centered promise, compact action and dominant work surface for the default new landing page. Build an original plausible example workspace if live media is unavailable. Audience and detailed product pages instead use a 48px left-aligned serif headline in a narrow column, Source Sans support, and an oversized slightly tilted interface spilling off the right edge of a charcoal stage.

**Avoid:** Do not replace the dominant work surface with a tiny floating dashboard, an abstract gradient orb or a symmetrical grid of feature cards. Do not force the whole demonstration above the fold by shrinking it.

**Text style:** `display` — Tiempos 600 · 64px/1.333 · tracking -0.0005em

### Demonstration chapter

**Observed:** On Paper canvas, a 119px short Chapter rule separates chapters with 120px space above and 112px below. A centered heading/support pair uses heading and section-support within 892.8px; the title-to-description gap is 22px and description-to-Product panel gap is 48px. The demonstration is 1116×630px and the chapter occupies about 1053px vertically.

**Transfer:** Give each chapter one distinct outcome and show a different relevant state of the same product. Retain the expansive pause and repeatable frame rather than varying every section's geometry.

**Text style:** `heading` — Tiempos 700 · 40px/1.333 · tracking -0.0008em

### Dark discovery gallery

**Observed:** Slate band carries a centered display heading about 114px from its top. Gallery cards follow in a single horizontal track; all are the same size, with a partial next card and a white circular arrow fading over the right side.

**Transfer:** Use this device to show breadth across examples or audiences; let rich small work collages carry the differences rather than long paragraphs.

**Text style:** `display` — Tiempos 600 · 64px/1.333 · tracking -0.0005em

### Restrained social proof

**Observed:** A small centered sans introduction sits over a six-cell logo row on Slate band, with 59px title-to-row spacing and 120px bottom padding. The editorial audience version places five logos on white below a 22px Source Sans introduction.

**Transfer:** Use real permissioned logos or equivalent compact proof marks. Keep proof visually quieter than the product demonstrations.

**Text style:** `small-label` — Inter 400 · 16px/1.333 · tracking -0.001em

### Blue access interlude

**Observed:** Electric-blue band is 596px high. A narrow left text column carries the white heading and pale-blue device-support. Device family overlaps on the right and reaches the bottom edge within the 1116px stage.

**Transfer:** Use for continuity across contexts or supported environments; keep one strong text column opposite one layered product family.

**Text style:** `heading` — Tiempos 700 · 40px/1.333 · tracking -0.0008em

### Illustrated conversion ending

**Observed:** Textured conversion stage has 96px top and 156px bottom padding around Registration panel. Geometric studio characters sit behind it and gather toward the lower edge. The panel remains a calm white island; it is followed by a complete dark utility footer rather than acting as the page's final pixel.

**Transfer:** Use the original geometric-character recipe to give the final action personality. Preserve an actual conversion path, short reassurance and a genuine footer.

**Text style:** `conversion-heading` — Tiempos 700 · 24px/1.333333 · tracking -0.001em

### Utility footer ending

**Observed:** The default slate footer is 616px high, with an 1116px content grid, about 85px top and 121px bottom padding. A brand/language zone sits left of four Footer columns; social icons and copyright make a low secondary row. Editorial pages end in a 786px charcoal footer: four columns above a small centered circular mark and serif wordmark.

**Transfer:** Keep the full ending architecture appropriate to the chosen page family; put product, help and company links in clearly labeled columns.

**Text style:** `small-label` — Inter 400 · 16px/1.333 · tracking -0.001em

### Editorial overview

**Only for:** audience and detailed product pages

**Observed:** A centered editorial-heading and 22px support paragraph sit over a 1000×563px application view with 6px corners and deeper shadow. The light-gray or light-gray-to-white band has 58px top and 86px bottom padding.

**Transfer:** Use to explain the whole system before exploring individual outcomes.

**Text style:** `editorial-heading` — Tiempos 600 · 36px/1.333

### Alternating editorial feature

**Only for:** audience and detailed product pages

**Observed:** Broad 700px white and gray bands alternate image side. A roughly 459px copy column is vertically centered with a 24px serif heading, 22px gap, 20px/27px explanation and optional 16px/24px bullets. The 735px visual can spill beyond the centered container. The compact reassurance variant is 382px high, with a 158×186px emblem opposite wider text and a three-item factual list.

**Transfer:** Use one concrete workflow per band and add factual reassurance where the reader needs it. Keep photo-and-note collages specific to the claim.

**Text style:** `editorial-feature-heading` — Tiempos 600 · 24px/1.333

### Dark template selector

**Only for:** template showcases

**Observed:** A charcoal band about 969px high places an introductory label and Template tabs above a centered 36px serif title, Template action and a 946×532px interface view. The view has 3px corners and a compact 0px 3px 10px shadow; the bottom has about 114px breathing room.

**Transfer:** Show useful starting points or example configurations for the new product, with each tab representing a concrete output.

**Text style:** `editorial-heading` — Tiempos 600 · 36px/1.333

## Page flow

**Storyline:** Promise → visible working example → concrete capability demonstrations → breadth and trust → contextual reassurance or access → illustrated conversion → useful dark footer.

### Broad product introduction and creative discovery

1. **Promise** — Centered serif benefit pair, one explanatory sentence, orange action and dominant working interface.
2. **Capability chapters** — Repeated centered heading pairs and large interface demonstrations show four distinct modes of work.
3. **Breadth** — Dark horizontal gallery of use-case collages.
4. **Social proof** — Restrained logo row continues the dark field.
5. **Access** — Electric-blue interlude with overlapping device family.
6. **Closing call** — White registration card on textured, playfully illustrated gray.
7. **Utility ending** — Slate footer with left brand/language zone, four link columns and lower social/copyright row.

**Transfer:** Use the centered workbench system as the default; choose the chapter count and ordering to fit the new product rather than reproducing every topic.

### Audience-focused explanation with a sequence of relatable workflows

1. **Audience promise** — Charcoal split opening with 48px serif headline and oversized tilted interface.
2. **System overview** — Centered title, explanatory paragraph and complete app view on a light gradient.
3. **Capability chapters** — Alternating broad bands pair copy with image-and-note collages or cropped interface examples.
4. **Objection handling** — Compact emblem-and-factual-list reassurance band.
5. **Starting point** — Dark tabbed template selector with a large example and light action.
6. **Social proof** — Small neutral logo row on white.
7. **Closing call** — Wider white registration panel amid taller geometric characters.
8. **Utility ending** — Four charcoal footer columns and small centered brand lockup.

**Transfer:** Use this denser editorial system for a defined audience, preserving the whole-to-part explanation and concrete starting points.

### Category-specific product positioning and deeper feature explanation

1. **Category promise** — Charcoal split opening, 48px serif promise and large angled product view.
2. **Category distinction** — Violet information strip overlaps the opening boundary to explain complementary positioning.
3. **System overview** — Centered whole-product view on light gray.
4. **Capability chapters** — Alternating white and gray feature bands use collages, photos, notes and interface fragments.
5. **Objection handling** — Factual reassurance list with a compact emblem.
6. **Starting point** — Charcoal template selector presents practical example outputs.
7. **Closing call** — Contextual serif invitation in a wide white form panel over geometric illustration.
8. **Utility ending** — Four charcoal footer columns and small centered wordmark beneath.

**Transfer:** Use a category-specific opening and one carefully scoped positioning strip; retain the editorial page family's type and footer rather than partially importing the default layout.

## Writing

Warm, practical and creatively encouraging. Confidence comes from showing familiar tasks and tangible outcomes, with occasional gentle playfulness rather than grand technical claims.

**Do not copy:** Do not reuse Milanote's name, logo, artwork, customer logos, named example projects, product-specific claims, free-plan promises or security assertions. Source examples illustrate sentence structure only; replace them with truthful content for the new product.

- **Addressing the reader:** Talk directly to you and your team. Refer to the product by name when explaining its role; use imperative verbs for tasks and actions rather than a continual corporate we.
- **Rhythm:** Short task-led headings, often 3–7 words, balanced with one or two plain-language sentences. Longer editorial chapters can use a compact paragraph and a short factual list. Ampersands are natural in titles; exclamation is rare.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Two short imperative benefits, or a direct audience/category promise. | 4–9 words | “Get organized. Stay creative.”<br>“The ultimate app for creative writing” |
| Supporting line | Define the product in familiar terms and connect it to a concrete job. | One concise sentence | “[Brand] is an easy-to-use tool for organizing creative projects.”<br>“Organize your research, ideas, characters and outline in one place.” |
| Section heading | Begin with a useful action and name its outcome. | 3–7 words | “Take notes & collect research”<br>“Brainstorm and experiment” |
| Feature explanation | Start with a recognizable working situation, then describe what changes. | 2–4 sentences in editorial chapters | “Linear word documents are great for your final output, but on day one you need a flexible space to explore your ideas.” |
| Primary action | Direct action, with a short truthful friction reducer when appropriate. | 2–5 words | “Sign up for free” |
| Closing invitation | A modest invitation to try or plan the next piece of work. | 3–5 words | “Plan your next story” |

**Words and phrasing to use:** organize; collect; create; plan; ideas; inspiration; in one place; flexible; your team; start with

**Avoid:** revolutionary ecosystem; 10x your potential; enterprise-grade synergy; unlock limitless possibilities; dominate; disrupt

**Rules:**

- Name the task before describing the technology.
- Use familiar nouns and specific verbs; explain what can be combined, saved, rearranged or shared.
- Keep feature headings more concrete than the opening promise.
- Use short factual bullets for support details rather than repeating the heading in different words.
- Allow small human asides such as '(and fun)' without making every sentence whimsical.

## Do's and Don'ts

### Do

- Keep the main promise at 64px with 1.333 leading and restrained 0px tracking.
- Give product demonstrations an 1116px stage, visibly wider than the 892.8px explanatory text group.
- Keep orange marketing actions compact with 6px corners; use 4px corners for default form controls.
- Use the 20px horizontal card gap and 24px gallery-card corners together.
- Keep most saturation inside product imagery, with the 596px blue capability band as a concentrated exception.
- Pair a 440px white conversion panel with subtle cool-gray texture and original geometric characters.
- Retain the 119px short chapter rules and expansive 120px/112px pauses for repeated demonstration chapters.
- Maintain the complete dark footer after the illustrated conversion stage.

### Don't

- Do not set headings in an all-sans system; the 64px and 40px serif roles carry the editorial character.
- Do not tighten display leading to 1 or introduce conspicuously negative tracking; the serif needs its open cadence.
- Do not turn the 6px-radius orange actions into pills or 60px-high promotional slabs.
- Do not recolor every explanatory band; the large light fields and slate anchors do most of the structural work.
- Do not apply the 24px gallery radius to the main product panel, which uses 10.3px corners.
- Do not substitute glossy neon 3D mascots for the grainy orange, gray and dark geometric ending.
- Do not use the scoped violet information strip as a site-wide notification bar.
- Do not add boxed icon cards around the editorial feature paragraphs; those pages use broad alternating 700px bands.

## Motion and responsive

### Motion

**Observed:**

- The default navigation stays visible while the page scrolls.
- Gallery content is horizontally scrollable and includes a next-arrow control.
- No action or surface transitions were matched to declared state rules; product-scene timing is not specified.

**Transfer:**

- Keep text, primary action and example work legible without depending on an animation completing.
- Use horizontal navigation for the gallery without changing the fixed card proportions.

**Unknown:**

- Product animation timing, hover and focus appearance, easing assignments and template-transition behavior are not established.

### Responsive

**Observed:**

- Desktop composition uses a 1440px viewport with centered 1116px or 1170px stages.
- Declared width breakpoints include 400px, 425px, 426px, 500px, 530px, 550px, 600px, 768px, 769px, 890px, 896px, 897px, 1023px, 1024px and 1280px.

**Transfer:**

- Recommended narrow-screen adaptation: retain the centered promise over the work surface, reduce headline size to fit natural phrase breaks and keep the main action compact.
- Recommended narrow-screen adaptation: stack editorial text and media, keep gallery cards horizontally browsable, and move geometric characters toward the outer lower edges so they never cover form controls.

**Unknown:**

- Exact mobile type sizes, menu collapse behavior, card widths and device-art rearrangement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
