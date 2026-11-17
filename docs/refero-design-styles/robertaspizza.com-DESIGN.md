# Roberta’s Pizza — halftone and revelry

## Overview

A boisterous neighborhood-poster aesthetic pairs chunky, eccentric serif capitals with a narrow, handmade-feeling sans. White and charcoal stages alternate around vivid red accents, full-bleed photography and irreverent little illustrations. It suits tangible products, hospitality and culture-led services: spacious at section scale, intimate and lively inside each scene.

### Essentials

- Headlines behave like compact gig posters: Borensa at 120px/0.875 for openings, 80px/0.875 for section titles and 60px/1 for feature chapters, all regular-weight capitals with normal tracking.
- The opening is an immersive photograph, not a text-and-thumbnail split: a 900px-tall full-width scene carries a centered white two-line title, flanking four-point stars and a bottom row of 70px actions.
- Actions look like sturdy printed labels: 7.2px corners, 20px 30px padding and 22px Borensa capitals with -0.02em tracking; white and charcoal variants sit beside red conversion buttons.
- Neutral stages carry most of an ordinary service landing page: white editorial chapters and charcoal halftone callouts; red is concentrated in actions and illustrations. Commerce, community and people chapters expand red into full-width bands rather than tinting every surface.
- Pictures feel physically present: natural-color close-ups and candid people fill square-edged frames with 2px charcoal rules; cutout objects can run beyond the page edges. When product photography is unavailable, stage real materials, tools or people at work rather than substituting polished interface mockups.
- Printed mischief is structural: include fading halftone fields, four-point stars or spiky bursts, and irregular 23px–37px edge strips. Finish with a spacious charcoal newsletter stage, an 80px email bar and sparse edge-aligned footer links.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Poster red | `#ed2023` | `--color-signal` | action, accent, background, link | Conversion buttons and one-color drawings; full red canvases belong to commerce, community and people chapters. Directory labels and dotted leaders also use red. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Photographic black | `#000000` | `--color-black` | background | Media backing and transparent-to-black image scrims; not the default dark section color. |
| Charcoal ink | `#2b2f36` | `--color-ink` | text, background, border, action | Primary dark lettering, flat dark bands, photograph rules and dark buttons. |
| Menu edge gray | `#8c8e92` | `--color-menu-edge` | border, accent | Floating menu border and hamburger strokes; subordinate to charcoal rather than a general paragraph color. |
| White paper | `#ffffff` | `--color-paper` | background, surface, text, action | Editorial canvas, inverse lettering, form fields and light buttons. The floating menu uses white at 54% opacity over imagery. |

## Typography

- **Borensa** — Display titles, chapter headings, buttons and oversized dates. Broad, exuberant display serif with chunky contrast, flared terminals and unusual rounded forms; nominal regular weight reads visually heavy. If unavailable, use **DM Serif Display**. Use 400 uppercase; preserve the squat line spacing and broad headline footprint. Font stack: "Borensa", "DM Serif Display", Arial, sans-serif.
- **Offset TM** — Paragraphs, image-card labels, form headings and footer text. Narrow, irregular sans with a friendly hand-drawn sign-painter quality, tightly packed without looking geometric. If unavailable, use **Patrick Hand**. Use 400; retain narrow line measures and avoid adding letter spacing. Font stack: "Offset TM", "Patrick Hand", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Borensa | 400 | 120px | 0.875 | normal, uppercase | Centered opening titles and emphatic photographic conversion headlines. |
| heading | Borensa | 400 | 80px | 0.875 | normal, uppercase | Centered section leads, commonly stacked into two or three tight lines. |
| chapter | Borensa | 400 | 60px | 1 | normal, uppercase | Left-aligned feature titles and names in alternating image/text chapters. |
| body | Offset TM | 400 | 24px | 1.25 | normal | Conversational paragraphs, supporting lines and direct contact links. |
| action | Borensa | 400 | 22px | 30px | -0.02em, uppercase | Standard 70px buttons in all surface colors. |
| footer | Offset TM | 400 | 20px | 1.5 | normal, uppercase | Sparse utility links and centered copyright line. |
| compact-action | Borensa | 400 | 14px | 30px | -0.02em, uppercase | Compact fixed-header actions and directory menu selectors. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| history timelines | timeline-number | Borensa | 400 | 500px | 1 | normal | Oversized last two digits of a year, overlapped by a circular photograph. |
| commerce grids and directories | card-title | Offset TM | 400 | 54px | 60px | normal | Large informal image-card titles and directory title strips. |

**Notes:**

- Display letters are already heavy in construction: keep weight 400 instead of adding artificial bold. Titles depend on tight stacked line height, not negative tracking.
- Only actions carry the consistent -0.02em tracking. Body copy and display headings use normal tracking.
- Use a narrow paragraph measure, about 352px–454px within split chapters and up to 768px for centered introductions. Avoid expanding conversational copy across the full page.
- Form-group headings are a deliberate sans exception: 54px uppercase Offset TM rather than the decorative serif. Keep the serif for the invitation above the form.

## Layout

**Density:** Airy section pacing with tightly stacked display lettering and relatively dense handwritten-feeling paragraphs.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Wrapped action groups and paired form-column separation. |
| 16px | Button internal flex gaps and closely related details. |
| 20px | Global side padding, card gutters and directory card padding. |
| 30px | Chapter title-to-copy-to-action rhythm. |
| 40px | Centered heading-to-support and support-to-action gaps. |
| 96px | Space before directory grids and inquiry form. |
| 128px | Large section padding and separation between alternating chapters. |
| 136px | Desktop split-chapter gap between media and copy. |

### Containers and grids

- **editorial container**: max width 1160px · side padding 20px. Centered chapter rows and directory grids; at 1440px this leaves 140px to each side.
- **wide gallery**: max width 1400px · 3 columns · gap 20px · side padding 20px. Edge-near commerce imagery; two-card related-product variants use the same outside margins.
- **centered invitation**: max width 768px · side padding 20px. Centered heading/support blocks and the upper footer invitation.
- **alternating chapter**: max width 1160px · 2 columns · gap 136px. Media approximately 570px wide beside a text block up to 454px wide; alternate image side. A portrait variant is 450px wide.
- **directory grid** (only for directories): max width 1160px · 2 columns · gap 20px. Two square-edged information cards per row on charcoal.
- **inquiry form** (only for inquiry pages): max width 668px · gap 10px. Narrow centered form; paired short fields become approximately 324px columns, long fields span 658px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action labels | 7.2px |
|  | floating menu | 10px |
|  | media and inputs | 0px |
| history timelines | timeline portrait | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| community galleries | loose photo print | `0px 4px 4px 0px rgba(0, 0, 0, 0.25)` | Small physical lift under white-bordered, rotated social photographs. |

### Surfaces

#### White editorial paper · level 0

**Use:** Default service and feature canvas.

**CSS:** `background-color: #ffffff; color: #2b2f36`

**Observed:** A very faint printed halftone texture adds material without becoming a visible gray panel.

**Transfer:** Keep the white ground bright and text dark; use the halftone recipe as a separate decorative layer.

#### Charcoal printed band · level 0

**Use:** High-contrast interludes and the common closing newsletter stage.

**CSS:** `background-color: #2b2f36; color: #ffffff`

**Observed:** Halftone density is strongest near the top and fades toward the plain dark lower portion; boundaries may ripple gently.

**Transfer:** Use a full-width surface rather than a rounded inset card.

#### Photographic scrim · level 1

**Use:** Legibility over opening media.

**CSS:** `background-color: rgba(43, 47, 54, 0.3)`

**Observed:** A uniform dark veil sits over cover imagery; an additional 204px upper black-to-transparent gradient at 40% opacity supports the header.

**Transfer:** Preserve the warmth and detail of the image below the veil.

#### Poster red band · level 0

**Only for:** commerce, community and people chapters

**Use:** Loud editorial changes of pace.

**CSS:** `background-color: #ed2023; color: #ffffff`

**Observed:** Flat saturated color backs photography and white display lettering without gradients.

**Transfer:** Reserve the full red field for a focused cultural or commercial chapter, rather than all ordinary sections.

#### Photo label scrim · level 1

**Only for:** commerce and related-product image cards

**Use:** White titles along the bottom of photographs.

**CSS:** `background-image: linear-gradient(rgba(0, 0, 0, 0), #000000); opacity: 0.4`

**Observed:** The overlay covers the picture but darkens its bottom most strongly; it is not a separate title panel.

**Transfer:** Put text above the scrim layer, keeping it opaque.

## Components

### Primary button

**Use:** Local conversion at the end of a chapter.

**CSS:** `display: flex; align-items: center; justify-content: center; background-color: #ed2023; color: #ffffff; padding: 20px 30px; height: 70px; border-radius: 7.2px; gap: 16px`

**Text style:** `action` — Borensa 400 · 22px/30px · tracking -0.02em · uppercase

**Observed:** Plain text centered in a solid label, normally left-aligned with the paragraph above; no icon or trailing chevron.

**States:** Declared: hover outline 0px; focus-visible outline .125rem solid #005fcc with .125rem offset; active outline 0px.

### Light button

**Use:** Action on photographic or dark stages.

**CSS:** `display: flex; align-items: center; justify-content: center; background-color: #ffffff; color: #2b2f36; padding: 20px 30px; height: 70px; border-radius: 7.2px`

**Text style:** `action` — Borensa 400 · 22px/30px · tracking -0.02em · uppercase

**Observed:** Shares its geometry with Primary button; frequently flanks a charcoal action in a bottom-centered hero row.

**States:** Declared: hover color white and outline 0px; focus-visible outline .125rem solid #005fcc with .125rem offset; active outline 0px.

### Dark button

**Use:** Contrasting secondary action on white or photographic stages.

**CSS:** `display: flex; align-items: center; justify-content: center; background-color: #2b2f36; color: #ffffff; padding: 20px 30px; height: 70px; border-radius: 7.2px`

**Text style:** `action` — Borensa 400 · 22px/30px · tracking -0.02em · uppercase

**Observed:** Equal visual mass to its light and red siblings; also expands across directory cards.

**States:** Declared: hover outline 0px; focus-visible outline .125rem solid #005fcc with .125rem offset; active outline 0px.

### Floating navigation

**Use:** Persistent access without a full-width navigation bar.

**CSS:** `position: fixed; top: 0px; height: 130px; width: 100%; z-index: 50`

**Observed:** At the opening, a hamburger sits left, a red handwritten identity sits centered and a red action sits right. During reading, compact actions cluster at the right with 10px gaps; the center clears. There is no painted full-width header background.

**Transfer:** Use an original handwritten identity or a simple text identity, retaining the open corners and unobstructed imagery.

### Floating menu

**Use:** Small hamburger control in the left header corner.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background-color: rgba(255, 255, 255, 0.54); border: 1px solid #8c8e92; border-radius: 10px; padding: 14.6px 13.7px; width: 64px; height: 53px`

**Observed:** Three horizontal strokes; this is a compact rounded rectangle rather than an icon floating without a hit area. On a dark photographic opening it reads as a light outlined control.

**States:** Declared: hover not specified; focus-visible outline .125rem solid #005fcc with .125rem offset.

### Compact header button

**Use:** Persistent secondary shortcuts while reading.

**CSS:** `display: flex; justify-content: center; align-items: center; padding: 4px 16px; height: 38px; background-color: #ffffff; color: #2b2f36; outline: 1px solid #2b2f36; border-radius: 7.2px`

**Text style:** `compact-action` — Borensa 400 · 14px/30px · tracking -0.02em · uppercase

**Observed:** Small white labels sit beside a stronger red action. Their text is much smaller than the large chapter buttons; the corners remain the same.

**States:** Declared: hover color white and 1px solid #2b2f36 outline with 0px offset; focus-visible outline .125rem solid #005fcc with .125rem offset; active outline 0px.

### Newsletter bar

**Use:** Single-field signup inside the closing dark stage.

**CSS:** `display: flex; border: 2px solid #2b2f36; height: 80px; width: 546px`

**Observed:** A 466px by 76px white email field with 28px 18px padding meets a square red submit block labeled GO! The input and submit read as one unrounded horizontal bar.

**Transfer:** Keep signup to one field and a terse submit label; clamp the overall width to available space.

### Footer utility link

**Use:** Low-density final navigation.

**CSS:** `color: #ffffff; position: relative`

**Text style:** `footer` — Offset TM 400 · 20px/1.5 · uppercase

**Observed:** A pair of short links is pinned left, copyright centered, and one credit link right in a 1400px-wide three-part bottom row with 30px gaps.

**States:** Declared: hover outline 0px; focus-visible outline .125rem solid #005fcc with .125rem offset; active outline 0px.

### Image link card

**Only for:** commerce and related-product grids

**Use:** Turn a photograph into a large destination link.

**CSS:** `display: flex; position: relative; flex-direction: column; justify-content: flex-end; align-items: flex-start; border: 2px solid #2b2f36; padding: 0px 0px 30px 20px; overflow: clip`

**Text style:** `card-title` — Offset TM 400 · 54px/60px

**Observed:** Cover photograph and Photo label scrim sit behind a bottom-left white title. Three-card rows are about 453px by 560px; two-card rows widen to about 690px without changing the label language.

**Transfer:** Keep the whole image clickable rather than adding a second small button inside.

### Directory card

**Only for:** directories

**Use:** Structured operational information in a poster-like panel.

**CSS:** `display: flex; flex-direction: column; gap: 28px; padding: 20px; background-color: #ffffff; color: #ed2023; border-radius: 0px`

**Text style:** `body` — Offset TM 400 · 24px/1.25

**Observed:** Faint halftone paper holds a red title strip with white Card-title lettering, contact rows and schedules. Red dotted leaders connect labels to right-aligned values. A dark full-width action sits above a centered wrapping group of 40px menu labels.

**Transfer:** Adapt to stores, partners or service availability; preserve ragged practical density rather than turning each data point into a separate card.

### Inquiry field

**Only for:** inquiry pages

**Use:** Plain, human-scale contact form controls.

**CSS:** `height: 52px; border: 1px solid #2b2f36; padding: 8px 20px; margin-bottom: 20px; border-radius: 0px`

**Text style:** `body` — Offset TM 400 · 24px/1.25

**Observed:** Labels sit above fields. Short details pair across one row; long answers use full width. Selects keep a simple native indicator; a textarea grows to 155px. The form ends in a full-width Primary button.

## Imagery and graphics

### Lived-in photographic scenes

**Use:** Full-screen opening, chapter illustrations and wide transition photographs.

**Observed:** Overhead shared tables, charred food textures, cooks at work, candid dancing and rustic interiors; warm daylight or direct event flash. Color is rich but credible. Openings fill the viewport while chapter images occupy roughly half a row with square edges and thin dark framing.

**Transfer:** Photograph the product in use, its making process and its surrounding people. For intangible products, show the real workbench, workspace or materials rather than a generic abstract render.

### Halftone and edge printing

**Use:** Recurring material and section-boundary language on every new page.

**Observed:** Dark surfaces carry diagonal, varying-size print dots that fade down into flat charcoal; light surfaces have an almost invisible fine dot/check texture. Boundaries alternate low-amplitude waves and thin checker strips.

**Transfer:** Recreate the imperfect print atmosphere without overpowering the content; exact dot placement is not essential.

**Build:** Overlay an SVG pattern of staggered circles spaced about 10px apart, radius varying from 1px to 4px, filled white at 8%–14% over charcoal. Mask with a top-to-bottom transparency fade across roughly 450px; add broad diagonal masked bands to break uniformity. For light paper use charcoal dots at 2% opacity. Use a 37px SVG edge strip with a shallow 8px wave; use a 23px two-row checker strip with alternating 12px squares in white and charcoal or red.

### Stars and cheeky spot drawings

**Use:** Heading companions and punctuation between photos and chapters.

**Observed:** White or charcoal four-point sparkles, spiky starbursts, red line-art party objects and playful cartoon figures. Heading companions are generally 42px–48px; large figures can reach about 342px by 404px and overlap photographic stages.

**Transfer:** Include original one-color spot art related to the new product. The minimum version is a confident silhouette or simple line drawing plus the star vocabulary, not a full complex mascot.

**Build:** Draw a four-point sparkle as a concave SVG path inside a 48px square, with long cardinal tips and inward-curving edges. Make a second burst from 12 alternating long and short triangular rays. Fill with white, charcoal or red according to the backing. Pair stars loosely around titles with about 40px of separation; place one original 2px-stroke red object drawing off-axis near a chapter image.

### Oversized edge cutouts

**Only for:** product-story interludes

**Use:** Frame short centered copy with tangible objects.

**Observed:** Two roughly 700px product cutouts extend well beyond opposite page edges on light halftone paper, leaving a clear central paragraph and red action.

**Transfer:** Use an isolated product, component or material photographed against a removable background. Preserve physical texture and let the object exceed the frame rather than fitting it into a tile.

### Loose social photo prints

**Only for:** community galleries

**Use:** Human proof on a red stage.

**Observed:** Five candid pictures overlap in a loose horizontal fan, with 8px white outlines, small shadows and differing rotations; outer pictures continue beyond the viewport. Faces, hands and products mix without a uniform studio look.

**Transfer:** Use real user, team or making-process photographs. Mix portrait and near-square formats rather than manufacturing identical testimonials.

**Build:** Arrange 330px–494px-wide rectangular images in an overflowing flex row. Apply 8px white outlines, the Loose photo print shadow and alternating rotations of roughly -7deg to 10deg; overlap neighboring prints by about 30px and keep one central print upright.

### Cultural portrait collage

**Only for:** company-story pages

**Use:** Origins and people chapters.

**Observed:** Square-edged candid work portraits and celebratory scenes float at different heights on charcoal, with white 2px borders and scattered stars. Later formal profiles alternate media and text on solid red.

**Transfer:** Show founders or makers in their actual spaces, retaining clothing, walls and tools rather than replacing them with cutout corporate headshots.

### Icons

**Observed:** Mostly solid one-color SVGs: four-point sparkles and spiky bursts at about 42px–48px, arrows about 46px by 21px, and social marks at 26px. Social marks are centered below the section title; decorative symbols flank headings.

**Transfer:** Keep functional icons sparse and solid. Use the original decorative vocabulary for personality rather than adding a uniform thin-stroke UI icon to every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Immersive poster opening

**Observed:** A 1440px-wide photographic stage fills the first 900px. Back to front: warm overhead product scene, 30% charcoal veil and dark upper scrim, open fixed navigation, centered white Display title with a four-point star at either side, then a bottom-centered row of Light button, Dark button and Light button. The two-line title occupies roughly the middle half of the width and about 210px of line height. The header identity is handwritten red; the left menu and right red action frame it. The three 70px buttons sit near the bottom with 20px gaps. No paragraph competes with the title; the editorial invitation begins below the first screen.

**Transfer:** Default new marketing pages use this photographic poster opening. Stage tools, materials or people at work if the new product has no hero photograph of its own. A directory can use an interior scene and a one-line title; a company story can use an expressive mural or environmental scene. Keep the same stars and low action row.

**Avoid:** Do not replace the immersive scene with a white split hero, a floating dashboard, a gradient orb or a paragraph-heavy banner.

**Text style:** `display` — Borensa 400 · 120px/0.875 · uppercase

### Centered illustrated invitation

**Observed:** A Heading title sits centered within a 768px wrapper, with stars or larger red spot drawings loosely to its sides. Major padding is 128px; a centered support paragraph sits 40px below when present.

**Transfer:** Use a short welcoming statement to bridge the visual promise and detailed chapters. Scale surrounding drawings independently of the text.

### Alternating photographic chapter

**Observed:** An Alternating chapter layout sits on White editorial paper. A thin-framed image about 570px by 582px faces a narrow text stack: Chapter title, Body paragraph, Primary button with 30px gaps. Consecutive rows reverse the image side and are separated by 128px.

**Transfer:** Use one concrete capability or mode of use per row, balancing long titles by shortening support copy rather than shrinking the type.

**Text style:** `chapter` — Borensa 400 · 60px/1 · uppercase

### Dark centered callout

**Observed:** A full-width Charcoal printed band has a centered two-line Heading, a narrow white paragraph 40px below and Primary button after another 40px. A white sparkle punctuates one side; generous empty lower space leads into an irregular white edge.

**Transfer:** Use for a broad promise, service tier or conversion checkpoint, not a dense feature matrix.

**Text style:** `heading` — Borensa 400 · 80px/0.875 · uppercase

### Newsletter constellation ending

**Observed:** Every page ends with the same roughly 870px charcoal stage under a shallow wavy edge. A white two-line Heading and two-line support copy center above Newsletter bar; four white stars and bursts occupy the surrounding negative space. The main wrapper is 768px wide with 234px top and 206px bottom padding. Footer utility link groups then form a sparse 1400px-wide bottom row: left links, centered copyright, right credit.

**Transfer:** Retain a large, welcoming subscription or follow-up invitation as the ending, rather than compressing it into a conventional many-column sitemap. Change the offer to suit the product while keeping the one-field bar and star field.

**Text style:** `heading` — Borensa 400 · 80px/0.875 · uppercase

### Red commerce and community stages

**Only for:** commerce and community pages

**Observed:** Commerce uses a white Heading above three Image link cards in Wide gallery. Community uses the same red backing, a centered Heading and social icons followed by Loose social photo prints extending off both edges. Major padding is 128px.

**Transfer:** Choose the appropriate grid or collage for the content; preserve one assertive red canvas instead of separating everything into pale cards.

**Text style:** `heading` — Borensa 400 · 80px/0.875 · uppercase

### Photographic conversion poster

**Only for:** multi-action product landing pages

**Observed:** A full-width overhead photo is bounded by irregular edges. A large original cartoon figure anchors the left, a two-line Display headline anchors the right, and three contrasting action labels are scattered across the image rather than confined to one centered row.

**Transfer:** Create a memorable action checkpoint with an original spot illustration and a short playful headline. Keep the three actions distinct in purpose and color.

**Text style:** `display` — Borensa 400 · 120px/0.875 · uppercase

### Operational directory

**Only for:** directories

**Observed:** Charcoal printed band backs centered white Heading titles, 96px gaps before a two-column Directory card grid and 20px card gutters. The lower transition is a full-viewport environmental photograph with a large spot character before the common newsletter close.

**Transfer:** Group availability or partner information into practical paper panels, then return to atmosphere before the closing form.

**Text style:** `heading` — Borensa 400 · 80px/0.875 · uppercase

### Monumental timeline

**Only for:** company-history pages

**Observed:** A thin horizontal rule crosses a White editorial paper stage. A dark 80px node with a 20px red center anchors a year and short story at left. A 336px circular candid image overlaps 500px Timeline-number lettering on the right. Edge-hugging red arrow tabs are 90px by 70px with outer 80px curved ends; four 14px pagination dots sit centered below.

**Transfer:** Use genuine milestones or chapter numbers. Preserve the enormous numeric treatment and layered image, not the particular dates.

**Text style:** `timeline-number` — Borensa 400 · 500px/1

### Inquiry chapter

**Only for:** inquiry pages

**Observed:** A centered Heading and paragraph offer direct phone/email links, then a 96px gap introduces the narrow Inquiry form. Sans uppercase group headings divide contact details, selection and event details. Paired short fields alternate with full-width controls; a full-width Primary button ends the form before the common footer.

**Transfer:** Ask only questions necessary for the next conversation; use direct contact alternatives to keep the form human.

**Text style:** `heading` — Borensa 400 · 80px/0.875 · uppercase

## Page flow

**Storyline:** immersive promise → welcoming context → tangible capability chapters → atmospheric conversion pause → practical next step → spacious subscription close

### Broad brand and product discovery

1. **Immersion** — Full-screen media and three clear action paths.
2. **Context** — Centered proposition between oversized edge cutouts, followed by a red repeating-symbol strip.
3. **Capabilities** — Dark practical-service chapter, wide photographic pause and asymmetric event imagery.
4. **Discovery** — Dark current-activity carousel, red commerce grid and photographic conversion poster.
5. **Human proof** — Two large related-product image cards and a red candid-photo collage.
6. **Closing invitation** — Newsletter constellation ending with sparse utility links.

**Transfer:** Let a broad landing page weave functional choices with scenes of real life; retain the print devices while changing the number and order of chapters.

### Help visitors compare availability and act locally

1. **Promise** — Environmental photograph with large centered title and shared action row.
2. **Practical comparison** — Two groups of white paper directory cards on charcoal, with red title strips and dotted information rows.
3. **Atmospheric proof** — Full-screen interior photograph with a large playful figure.
4. **Closing invitation** — Newsletter constellation ending.

**Transfer:** Use for stockists, service regions or partner networks; keep detailed facts in panels, not in the hero.

### Explain service options and turn interest into an inquiry

1. **Promise** — Overhead product scene with two-line poster title and bottom action row.
2. **Welcome** — Centered illustrated invitation on white halftone paper.
3. **Capability chapters** — Three alternating image/text rows, each with a plain-language description and red local action.
4. **Conversion checkpoint** — Charcoal centered callout with white heading and red action.
5. **Next step** — Centered invitation, direct contact links and a narrow grouped inquiry form.
6. **Closing invitation** — Newsletter constellation ending after the form submit.

**Transfer:** Default structure for a service or product landing page: keep the tangible scenes, local actions and human invitation, adapting chapter quantity to the offering.

### Build affinity through origins and people

1. **Identity** — Expressive environmental mural behind a centered poster title.
2. **Origins** — Staggered candid-photo collage and white story copy on charcoal with spot art.
3. **Historical proof** — Light timeline with circular photo, giant two-digit year and red arrow tabs.
4. **People** — Alternating documentary portraits and biographies on solid red.
5. **Closing invitation** — Newsletter constellation ending.

**Transfer:** Reserve the oversized timeline and sustained red biography canvas for a genuinely people-led story rather than inserting them into every product page.

## Writing

Neighborly, exuberant and hands-on. Confidence comes through concrete making details and practical invitations, with the occasional cheeky slogan rather than a polished corporate manifesto.

**Do not copy:** Do not reuse the brand name, identity artwork, mascots, proprietary illustrations, addresses, founder names, dates, business claims or distinctive slogans. Source examples illustrate tone only.

- **Addressing the reader:** Use we and our for the makers and you or your for the reader; direct invitations sound like a real person arranging something together.
- **Rhythm:** Headings are usually 2–6 words; short supporting lines can sit beside longer factual paragraphs. Exclamation marks appear on welcoming or celebratory titles, not on every sentence. Actions are short verb-led labels.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening title | Name the offering directly in compact poster language. | 1–4 words | “CateringAnd Events”<br>“Locations” |
| Welcome heading | Warm inclusive promise, often with one exclamation mark. | 3–6 words | “We Make it Yours!” |
| Supporting line | A concrete use occasion followed by a relaxed everyday phrase. | 8–18 words | “Perfect for office lunches, casual hangs, or a no-fuss feast.”<br>“Turnkey event production — food, drinks, and everything in between. We handle it all!” |
| Action | Plain verb and object; no manufactured urgency. | 2–3 words | “Inquire Here”<br>“Book a Table”<br>“Contact us” |
| Closing reassurance | Specific benefit, then a brief anti-hype aside. | Two short sentences | “Be the first to access new drops, exclusive offers, and insider updates. No spam — just the good stuff.” |

**Words and phrasing to use:** casual hangs; no-fuss; bring the party; fresh; seasonal; we handle it; just let us know; good stuff

**Avoid:** synergy; best-in-class solutions; unlock your potential; frictionless ecosystem; revolutionary platform

**Rules:**

- Use tactile, observable details to earn quality claims.
- Name real modes of use before abstract benefits.
- Keep functional labels straightforward even when nearby illustration is mischievous.
- Let one colloquial turn soften a factual paragraph; do not force jokes into every line.

## Do's and Don'ts

### Do

- Keep opening Display lettering at 120px/0.875 and section Heading lettering at 80px/0.875 on desktop.
- Use the 1160px editorial width and 128px major spacing to give large photos room.
- Keep ordinary service chapters on white, with red concentrated in their 70px conversion labels.
- Use 7.2px corners on both large and compact action labels.
- Retain square 2px image framing and natural-color photographs of people or products in use.
- Carry stars, halftone and irregular edge printing into the new page even with entirely different imagery.
- Give the common ending an 80px signup bar and a sparse three-part footer.
- Keep practical directory details red on white paper against charcoal.

### Don't

- Do not bold the display font to 700; its 400 cut already supplies the heavy poster character.
- Do not turn every action into a 9999px pill; the rounded-label silhouette is distinctive.
- Do not spread red tint across every section; flat red belongs to specific editorial chapters.
- Do not add soft gray dashboard cards with 16px corners around ordinary feature copy.
- Do not apply the social-gallery shadow to every image; most frames are flat and ruled.
- Do not replace the narrow expressive body family with a wide geometric sans at a tiny 16px size.
- Do not shrink all secondary details into widely tracked mono labels; compact actions still use the display serif.
- Do not turn the final stage into a dense multi-column corporate sitemap.

## Motion and responsive

### Motion

**Observed:**

- Standard large buttons declare background-color 0.25s and color 0.25s transitions; several compact controls declare 0.3s transitions.
- Video controls declare hover opacity 0.75. Timeline arrow controls declare charcoal background and white text on hover.
- Arrow tabs and pagination indicate manually navigable carousels. No automatic playback cadence is established.

**Transfer:**

- Keep motion subordinate to the printed scenes: preserve the declared short color changes on labels and the obvious arrow-tab carousel controls.

**Unknown:**

- Scroll choreography, media playback behavior and carousel timing are not established; no extra easing curve is prescribed.

### Responsive

**Observed:**

- CSS width breakpoints are 479px, 767px, 768px, 991px and 1440px.
- A viewport-dependent root font-size affects rem-based dimensions, but a complete usable scaling formula is not established.

**Transfer:**

- On narrow screens, reflow the alternating chapter into image then copy, retaining square frames and the 30px internal rhythm.
- Clamp the signup bar to available width; keep input and red submit joined.
- Preserve the photographic opening, stars and low action group; wrap actions instead of allowing them to cover the title.
- Let oversized edge cutouts and loose photo prints remain deliberately clipped rather than reducing all artwork to small thumbnails.

**Unknown:**

- Mobile compositions and exact font sizes at each breakpoint are not verified; these reflow rules are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
