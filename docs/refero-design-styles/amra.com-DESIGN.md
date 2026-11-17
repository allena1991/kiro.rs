# amra — luminous spheres of scale

## Overview

An airy, predominantly white technology style with human silhouettes and softly luminous spherical art. Regular-weight grotesk headlines and unusually substantial body copy give it a direct, unhurried confidence, while tiny uppercase utility labels keep the interface unobtrusive. Lavender, teal and icy blue live mainly in imagery, with a dark final act adding cinematic contrast. It suits infrastructure, platforms and services that need to make invisible processes feel tangible.

### Essentials

- The promise and its explanation share one typographic register: centered 50px/1.2 regular grotesk, normal tracking, with the first line in ink and the following lines in #a1a1a1 across an 819px text measure.
- The opening is a slow reveal rather than a conversion panel: an 80px header allowance, 160px upper breathing room, then an enormous luminous sphere entering at the bottom of the first 900px. Recreate the sphere with layered gradients when no specialist artwork exists.
- Actions are delicate dotted capsules, not dominant slabs: the main outline action is 48px high with a 24px radius, 16px horizontal padding and a lavender leading dot; the compact sign-in is 32px high with a 16px radius.
- Color is concentrated inside objects: white occupies most of the narrative, #f3f4f5 backs explanatory cards, and #acafff is reserved for small actions and scoped editorial cards. The final narrative chapters turn near-black, with white headings and muted gray support.
- Human and technical subjects share the same lighting: square 608px images of dark silhouettes or equipment against teal-to-lavender illumination; wide scenes magnify that treatment to the viewport. Use a backlit tool or abstract product silhouette when people are not relevant.
- Scale becomes an object and a field: include a thin wireframe process sphere with floating 44px-radius labels or an equivalent diagram, and a full-bleed field of small capsule items beneath a 50px proof statement. Use real entities or representative records rather than unrelated decorations.
- The ending repeats the opening light: a centered 50px two-line invitation above a 1152px luminous sphere cropped by the lower edge, with 14px uppercase utility links laid across its pale cap. It is a full 900px scene, not a conventional multi-column footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender | `#acafff` | `--color-lavender` | action, accent, surface | Compact sign-in, leading action dots, selection highlight and editorial card fills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#141414` | `--color-ink` | text, background | Primary text on white and the visually near-black canvas of the closing narrative. |
| Half-strength ink | `#8a8a8a` | `--color-subtle-ink` | text | Visible result of 50% near-black on white for tiny metadata and hover text. |
| Soft gray text | `#a1a1a1` | `--color-muted` | text, border | Secondary promise, body copy and fine separators. |
| Outline gray | `#d0d0d0` | `--color-edge` | border | Visible result of 20% near-black on white; outlined action edges. |
| Cool card gray | `#f3f4f5` | `--color-card` | surface | Explanatory cards and floating process labels. |
| White | `#ffffff` | `--color-canvas` | background, text | Default canvas and reversed headings. Also the source hue of the navigation's 40% white glass. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial news carousels | Lavender secondary ink | `#676999` | `--color-lavender-ink` | text | Secondary text on lavender editorial cards. |
| organizational principles and editorial lists | Faint rule | `#e8e8e8` | `--color-faint-edge` | border | Visible result of 10% near-black on white; numbered list dividers. |

## Typography

- **__primaryFont_fb23f9** — All major headings, supporting paragraphs and medium labels. Neutral contemporary grotesk with open counters and a regular, relatively light texture. If unavailable, use **Inter**. Use 400 throughout; preserve broad line measures and restrained tracking. Font stack: "__primaryFont_fb23f9", "Inter", Arial, sans-serif.
- **__secondaryFont_85f780** — Navigation, action text, attribution and metadata. Compact utility face with a monospaced, technical appearance in short uppercase labels. If unavailable, use **IBM Plex Mono**. Use 400 and positive tracking. Font stack: "__secondaryFont_85f780", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | __primaryFont_fb23f9 | 400 | 50px | 1.2 | normal | Opening promise and explanation, centered section statements, large proof lines and closing invitation. |
| body-heading | __primaryFont_fb23f9 | 400 | 30px | 1.2 | -0.01em | Section labels, card headings and supporting paragraphs share this recipe. Distinguish hierarchy through color and placement, not weight. |
| object-label | __primaryFont_fb23f9 | 400 | 20px | 1.2 | -0.01em | Floating process labels, record capsules and video title. |
| utility | __secondaryFont_85f780 | 400 | 14px | 1 | 0.0286em, uppercase | Navigation, outline actions, article categories, attribution and footer links. |
| compact-action | __secondaryFont_85f780 | 400 | 14px | 32px | 0.0286em, uppercase | The compact filled header action. |
| micro-caption | __secondaryFont_85f780 | 400 | 10px | 1 | 0.03em, uppercase | Location or secondary metadata under the floating object label. |

**Notes:**

- The main scale is deliberately narrow: 50px statements, 30px explanatory copy, 20px object labels, then 14px and 10px utilities. Do not replace the large paragraphs with conventional 16px marketing text.
- Keep all text at regular weight. Black-to-gray changes do much of the hierarchy work; the opening explanation is as large as its lead.
- Normal tracking belongs to the largest recipe; 30px and 20px recipes use -0.01em, while utility text has positive tracking.

## Layout

**Density:** Airy, with long visual pauses and substantial paragraphs rather than dense UI controls.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — The dominant vertical spacing cadence; occasional 12px detail gaps sit between full rhythm steps.

| Value | Use |
| --- | --- |
| 8px | Heading-to-support gap inside explanatory cards. |
| 12px | Leading dot-to-label gap in outlined actions. |
| 16px | Support gaps in audience sections and icon-to-text gaps in process labels. |
| 24px | Grid gutters, action offsets and process-label padding. |
| 32px | Editorial card padding and feature text insets. |
| 40px | Numbered list upper padding and footer lower inset. |
| 56px | Audience-section separation and media-card internal separation. |
| 64px | Numbered list row gap and profile separation. |
| 80px | Section heading-to-grid or diagram gap and header allowance. |
| 104px | Separation between benefit chapters beside a sustained image. |
| 160px | Major section upper and lower breathing room. |

### Containers and grids

- **outer wrapper**: max width 1620px. Centered outer wrapper; at 1440px the working content spans 1240px with 100px side margins.
- **editorial grid**: 12 columns · gap 24px · side padding 100px. Desktop framework for alternating images, copy, and centered statements.
- **opening text**: max width 819px. Centered opening text spans eight of the twelve columns.
- **statement text**: max width 608px. Centered proof and coverage headings; also the square-image width.
- **inset card grid**: max width 1029px · 2 columns · gap 24px. Feature and media cards inset one column from each side; individual cards are 503px wide.
- **split narrative**: 2 columns · gap 24px. 608px square imagery balanced by a 397px or 503px text measure, leaving deliberate empty grid columns.

## Corner radius

| Element | Radius |
| --- | --- |
| cards and image panels | 8px |
| outlined actions | 24px |
| compact action | 16px |
| floating labels | 44px |
| circular artwork and thumbnails | 50% |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #ffffff; color: #141414`

**Observed:** Broad uninterrupted white fields; no visible drop shadows.

**Transfer:** Let scale and spacing separate narrative blocks rather than enclosing each one.

#### Dark final act · level 0

**Use:** Editorial proof, audience chapters and the default closing scene.

**CSS:** `background: #141414; color: #ffffff`

**Observed:** The light narrative changes to a nearly black field while retaining the same grid and type scale.

**Transfer:** Use a coherent dark chapter rather than alternating arbitrary dark cards.

#### Cool feature panel · level 1

**Use:** Technical explanations and diagram backing.

**CSS:** `background: #f3f4f5; border-radius: 8px; box-shadow: none`

**Observed:** Flat pale cards, often combined into a varied-height grid.

**Transfer:** Use for explanations, not as a border around every paragraph.

#### Navigation glass · level 2

**Use:** Floating centered navigation over both white and imagery.

**CSS:** `background: rgba(255, 255, 255, 0.4); backdrop-filter: blur(35px); border-radius: 8px`

**Observed:** Barely perceptible over white and visibly frosted over colored media.

**Transfer:** Keep the glass confined to compact utility controls.

#### Image-tinted editorial glass · level 1

**Use:** Two large story cards inside the dark narrative.

**CSS:** `background: rgba(107, 107, 107, 0.7); backdrop-filter: blur(100px); border-radius: 8px`

**Observed:** Blurred photo color makes one card cool charcoal and another brown-charcoal; the image colors remain low intensity.

**Transfer:** Place an enlarged, blurred copy of each photo behind the translucent content, preserving local image color rather than applying a uniform flat gray.

#### Lavender editorial panel · level 1

**Only for:** editorial news carousels

**Use:** Text-led news items.

**CSS:** `background: #acafff; border-radius: 8px; color: #141414`

**Observed:** Solid lavender cards hold ink headings and lavender-gray supporting copy.

**Transfer:** Keep this stronger fill in an editorial rail, not as the main page canvas.

## Components

### Floating navigation

**Use:** Persistent primary wayfinding.

**CSS:** `position: fixed; height: 64px; padding: 0px 24px; background: rgba(255, 255, 255, 0.4); backdrop-filter: blur(35px); border-radius: 8px`

**Text style:** `utility` — __secondaryFont_85f780 400 · 14px/1 · tracking 0.0286em · uppercase

**Observed:** Four short links form a centered island about 396px wide with 24px gaps. The wordmark starts separately at the left margin and the compact account action at the right; the island persists while scrolling.

**Transfer:** Use three or four short destinations; do not turn the island into a full-width colored bar.

### Outline dot action

**Use:** Main inline action after a section statement.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 16px; gap: 12px; border: 1px solid rgba(20, 20, 20, 0.2); border-radius: 24px; color: #141414`

**Text style:** `utility` — __secondaryFont_85f780 400 · 14px/1 · tracking 0.0286em · uppercase

**Observed:** A small lavender circular marker precedes the label. Width fits the label; the dark chapter reverses label and edge contrast while keeping the same construction.

**States:** Declared: hover border 1px solid rgba(20,20,20,.4); focus-visible unknown.

**Transfer:** Keep the marker, outline and compact uppercase label when changing the destination.

### Compact filled action

**Use:** Account or persistent utility action at the header edge.

**CSS:** `height: 32px; padding: 0px 12px; background: #acafff; border-radius: 16px; color: #141414`

**Text style:** `compact-action` — __secondaryFont_85f780 400 · 14px/32px · tracking 0.0286em · uppercase

**Observed:** A small filled capsule contrasts with the larger outlined section actions.

**States:** Declared: hover color rgba(20,20,20,.5); focus-visible unknown.

### Floating process label

**Use:** Annotate activity around a large explanatory object.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 24px; background: #f3f4f5; border-radius: 44px; color: #141414`

**Text style:** `object-label` — __primaryFont_fb23f9 400 · 20px/1.2 · tracking -0.01em

**Observed:** A solid dark service symbol sits beside a two-line stack: medium event name and tiny uppercase location. Labels vary in apparent scale around the wireframe sphere.

**Transfer:** Replace events and locations with meaningful activity and context; use the micro-caption recipe for the second line.

### Editorial photo card

**Use:** External proof and editorial links on the dark canvas.

**CSS:** `display: flex; flex-direction: column; gap: 56px; padding: 32px; background: rgba(107, 107, 107, 0.7); backdrop-filter: blur(100px); border-radius: 8px; overflow: hidden; color: #ffffff`

**Text style:** `body-heading` — __primaryFont_fb23f9 400 · 30px/1.2 · tracking -0.01em

**Observed:** A small uppercase category with a light dot sits above the headline; a large circular photo follows below. Two cards share an inset grid, with tinted blurred imagery behind each panel.

**Transfer:** Use an authentic portrait, place or artifact connected to the story, with the utility recipe for category text.

### Footer utility row

**Use:** Minimal legal and secondary links over the closing sphere.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 24px; color: #141414`

**Text style:** `utility` — __secondaryFont_85f780 400 · 14px/1 · tracking 0.0286em · uppercase

**Observed:** A single centered row mixes links and copyright; it sits 40px above the lower edge, over the pale artwork rather than in a separate panel.

**States:** Declared: hover color rgba(20,20,20,.5); focus-visible unknown.

### Feature card

**Only for:** product capability pages

**Use:** A short capability explanation paired with graphic proof.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #f3f4f5; border-radius: 8px; overflow: hidden`

**Text style:** `body-heading` — __primaryFont_fb23f9 400 · 30px/1.2 · tracking -0.01em

**Observed:** Text is inset 32px. A dark heading and gray supporting paragraph lead into a diagram or media object below. Cards combine a tall 503px-wide item, stacked shorter items and a full 1029px-wide strip.

**Transfer:** Give every diagram a distinct explanation; vary card span according to the content rather than making all cards equal.

### Lavender news card

**Only for:** editorial news carousels

**Use:** Text-led article summaries in a horizontal rail.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 8px; padding: 32px; background: #acafff; border-radius: 8px; color: #141414`

**Text style:** `body-heading` — __primaryFont_fb23f9 400 · 30px/1.2 · tracking -0.01em

**Observed:** Cards are 397px wide, separated by 24px, with a partially visible next card at the right edge. Heading comes first, lavender-gray support follows, and a dot-led utility link anchors the bottom.

**Transfer:** Let the short headline and summary determine card height while preserving the open bottom area.

### Numbered principle

**Only for:** organizational principles and editorial lists

**Use:** Longer beliefs or operating principles without colored cards.

**CSS:** `display: flex; position: relative; padding-top: 40px; border-top: 1px solid rgba(20, 20, 20, 0.1)`

**Text style:** `body-heading` — __primaryFont_fb23f9 400 · 30px/1.2 · tracking -0.01em

**Observed:** Two columns of open list items; a tiny two-digit number occupies an 80px left rail, followed by ink heading and gray paragraph in the same type size.

**Transfer:** Apply to principles or stages that merit real paragraphs, not generic icon features.

### Video teaser capsule

**Only for:** pages with an introductory film

**Use:** Persistent compact invitation to watch a short introduction.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 0px 32px 0px 4px; height: 88px; background: rgba(243, 244, 245, 0.4); backdrop-filter: blur(35px); border-radius: 44px`

**Text style:** `object-label` — __primaryFont_fb23f9 400 · 20px/1.2 · tracking -0.01em

**Observed:** Fixed near the lower right, approximately 219px wide. An 80px circular thumbnail with a white play triangle precedes a title and utility-sized duration.

**Transfer:** Retain this only when there is a real short film; keep its scale secondary to the main object.

## Imagery and graphics

### Luminous sphere

**Use:** Signature opening object and closing horizon.

**Observed:** A smooth enormous orb floats on white. Its upper cap is milky lavender and icy cyan, with a rich teal lower hemisphere; light appears inside the material rather than as an exterior shadow. The full orb spans about 1152px, while the ending shows only its pale upper arc.

**Transfer:** Use the sphere as the minimum acceptable abstract product metaphor even when no 3D assets exist; match the soft glow rather than making it shiny chrome.

**Build:** Create a 1152px circular mask. Fill it with layered radial gradients: broad pale lavender light near 45% 5%, white light near 80% 0%, cyan at the left rim, and deep teal across the lower middle. Blend rgba(172,175,255,0.45), rgba(100,235,235,0.35), rgba(0,115,119,0.9) and white. Blur the internal color layers by 60px while keeping the circular silhouette crisp. Add very fine low-opacity grain. For the ending, hide the lower portion below the section edge.

### Wireframe activity sphere

**Use:** Signature explanation of reach, connected activity or process scale.

**Observed:** A very fine gray latitude-longitude sphere, about 913px square, fills the right side and runs beyond the content margin. Pale floating process labels orbit its surface, using scale changes to suggest depth; a narrow large-text statement and outlined action balance it on the left.

**Transfer:** Turn the new product's invisible network into a wireframe sphere or comparably light curved process structure with real activity labels.

**Build:** Use SVG ellipses clipped to a circle: concentric horizontal latitude ellipses plus vertical meridian ellipses rotated around the center. Use 0.5px near-black strokes at about 15% opacity, no fill. Place four or more HTML labels over the mesh, varying scale from 0.55 to 1. Keep the geometry faint enough to disappear behind the labels.

### Backlit human and product scenes

**Use:** Benefits, audience chapters and immersive introductions.

**Observed:** Dark human profiles, hands on equipment and a low-angle monitor appear against teal, icy blue and lavender backgrounds. Square scenes are tightly framed with 8px corners; the immersive treatment fills the viewport and holds a centered white statement. The subject remains nearly silhouetted rather than brightly exposed.

**Transfer:** Photograph or render a person using the new product, or a relevant tool, with deep foreground shadows and luminous cool backing. A cutout dark silhouette over a soft two-color light field is the minimum alternative.

### Capsule proof field

**Use:** Signature quantified proof with tangible records.

**Observed:** A centered large statement sits well above multiple edge-cropped rows of pale capsules. Each capsule combines a circular thumbnail, a dark record name and tiny gray uppercase metadata. One scene uses a few large rows; another shows many smaller items to make scale visible.

**Transfer:** Use customer artifacts, projects, records or meaningful entities. When thumbnails do not exist, use simple circular monograms and honest record names.

**Build:** Lay out repeated horizontal rows of inline-flex capsules on #f3f4f5 with fully rounded ends. Insert circular image masks, then a two-line label stack using object-label and micro-caption. Offset successive rows horizontally and clip the field at viewport edges; vary the overall scale between proof scenes rather than distorting individual capsules.

### Photo arc rail

**Only for:** partner ecosystems and culture pages

**Use:** A broad visual interlude showing people or ecosystem members.

**Observed:** Portrait-format photographs form a shallow arc across the entire page, with outer cards tilting outward and clipping at the edges. Corners are subtly rounded; ecosystem versions place a white logo over darkened photography, while culture versions use candid office scenes.

**Transfer:** Use authentic partner or team imagery only on the relevant page type.

**Build:** Arrange portrait cards in one overflow-hidden row. Rotate outer cards outward by roughly 12–15 degrees and near-center cards by about 4 degrees. Raise central cards relative to the outer cards, keep generous white space above and below, and apply 8px corners.

### Technical diagram art

**Only for:** product capability pages

**Use:** Graphic proof within pale feature cards and coverage sections.

**Observed:** Packed colored discs within a circular boundary, thin vertical trend marks with a lavender cursor, small gradient nodes connected by dotted curves, and a very pale lavender territory map. These are spacious illustrations rather than dense application screenshots.

**Transfer:** Illustrate one mechanism per card; reserve more saturated colors for the graphic itself and retain the pale backing.

**Build:** Use SVG circles clipped to a circle for volume; use evenly spaced low-opacity vertical strokes plus one lavender marker for trends; use pill-shaped teal-to-lavender nodes and dotted Bezier connectors for architecture. Coverage graphics use 20% lavender fills with thin lavender-gray edges on white.

### Candid leadership portraits

**Only for:** company and team pages

**Use:** Humanize long-form profiles.

**Observed:** 608px square portraits show seated people in real workplaces, with natural subdued warm or cool lighting and shallow focus. A narrow large-type biography sits opposite the image.

**Transfer:** Use unforced moments at work rather than uniformly cut-out headshots; preserve the substantial image-to-text contrast.

### Icons

**Observed:** Service marks are predominantly solid dark silhouettes inside floating capsules, typically 22–43px. A white 24px by 28px play triangle appears over an 80px round thumbnail. Small filled dots act as action and category markers.

**Transfer:** Use recognizable solid symbols for entities, simple play geometry for video, and filled dots for links; do not add a decorative outlined icon library to every heading.

## Section recipes

How recurring sections are built.

### First screen: Promise above a rising sphere

**Observed:** White canvas behind a sparse header: small wordmark left, Floating navigation centered, Compact filled action right. After the 80px header allowance and 160px top breathing room, the centered promise occupies an 819px measure. Its short ink lead is followed immediately by three gray lines in the same 50px recipe, without a size drop. Text ends around the middle of the screen. A 1152px Luminous sphere begins to rise from below, its pale cap visible in the lower third of the first 900px; the full sphere and subsequent narrative remain below the fold. The Video teaser capsule sits at lower right where a film exists. There is no main inline hero button.

**Transfer:** Write one compact promise followed by a more descriptive same-size explanation. Keep the sphere as the anchor when no product image exists, rather than replacing it with a dashboard rectangle. Product capability and company variants open with only the centered ink statement and bring a full-width backlit scene into the lower portion of the first screen.

**Avoid:** Do not inflate the headline to billboard scale, shrink the supporting explanation to a small paragraph, or insert a centered pair of oversized conversion buttons.

**Text style:** `display` — __primaryFont_fb23f9 400 · 50px/1.2

### Immersive statement

**Observed:** A viewport-filling backlit subject or product scene carries a centered 50px white statement. Text occupies the same restrained central measure as the opener and reveals line by line while the scene persists.

**Transfer:** Use one substantial statement over a dark focal area of the image; keep the background subject large enough to feel physical.

**Text style:** `display` — __primaryFont_fb23f9 400 · 50px/1.2

### Image and benefit chapters

**Observed:** A 608px square backlit image holds one side while a 397px text column presents short ink headings and gray 30px support. Chapters are separated by 104px, with 160px section breathing room. Audience versions reverse the arrangement to copy left, image right and use a thin separator with 56px surrounding space.

**Transfer:** Pair a sustained physical image with a small number of distinct benefits; the dark audience variant can explain different users without adding new visual vocabulary.

**Text style:** `body-heading` — __primaryFont_fb23f9 400 · 30px/1.2 · tracking -0.01em

### Process object and action

**Observed:** The Wireframe activity sphere dominates the right side, balanced by a 397px left column of 50px text. Outline dot action follows the statement after 24px. The 913px object extends beyond the grid and its labels overlap the wireframe.

**Transfer:** Explain scale or connectivity with one airy diagram and meaningful activity labels rather than a dense dashboard.

**Text style:** `display` — __primaryFont_fb23f9 400 · 50px/1.2

### Statement and record field

**Observed:** A 608px centered proof statement in 50px type floats over a wide gap and edge-to-edge rows of Capsule proof field. Larger records communicate recognizable examples; a denser small-record treatment communicates volume.

**Transfer:** Use one verified quantified claim per scene, allowing the record field to embody it rather than placing a giant isolated numeral.

**Text style:** `display` — __primaryFont_fb23f9 400 · 50px/1.2

### Editorial proof on dark

**Observed:** Two Editorial photo cards sit within the inset grid on Dark final act. Category, headline and circular image read vertically; the understated utility labels contrast with large prose headlines.

**Transfer:** Use external recognition, a customer story or a grounded editorial item as proof without changing the palette or typography.

### Closing luminous horizon

**Observed:** A full 900px scene gives a centered 50px invitation its own broad dark field. The pale cap of a 1152px Luminous sphere enters well below the statement, taking over the bottom edge. Footer utility row overlays that cap near the bottom. On company and product capability pages, White canvas replaces the dark field but the scale, line treatment and sphere stay the same.

**Transfer:** End with a succinct invitation about the new product's possible impact, then repeat the opening object's light. Keep the invitation and minimal utility row rather than adding a dense sitemap.

**Text style:** `display` — __primaryFont_fb23f9 400 · 50px/1.2

### Inset feature mosaic

**Only for:** product capability pages

**Observed:** A centered 50px section heading precedes a 1029px two-column feature grid after 80px. Use Feature card in tall, short and double-width forms, 24px gutters and pale gray backing. Copy remains 30px, with 8px between title and support.

**Transfer:** Let card span follow the explanation and graphic proportions; keep ample white margin outside the mosaic.

**Text style:** `body-heading` — __primaryFont_fb23f9 400 · 30px/1.2 · tracking -0.01em

### Open editorial structures

**Only for:** company and organizational pages

**Observed:** A large left-aligned 50px quotation uses a central 773px measure and ends with a tiny uppercase inline attribution. Numbered principle items use a two-column open grid below a 30px section label. Profiles then alternate a narrow biography with a 608px square portrait; split-heading sections pair a short left label with right-side body copy.

**Transfer:** Use the quotation, open list and profiles as scoped structures for mission, team and organizational material rather than adding them to every landing page.

### Lavender article rail

**Only for:** editorial news carousels

**Observed:** A split heading places the section label left and gray explanatory text plus Outline dot action right. Below, a full-width rail of Lavender news card begins after 80px and clips the next card at the right edge.

**Transfer:** Use for recurring updates or articles whose summaries matter more than thumbnail imagery.

## Page flow

**Storyline:** Promise → immersive explanation → tangible mechanisms and evidence → relevance to people → luminous closing invitation.

### Broad marketing landing page connecting an abstract service with concrete value

1. **Promise** — Centered two-tone headline above a rising luminous sphere.
2. **Explanation** — Large centered prose gives the mechanism in plain terms.
3. **Benefits** — A sustained square image sits beside short benefit chapters.
4. **Scale and quantified proof** — Wireframe activity object and record fields turn reach and volume into visible forms.
5. **External proof** — Photo-based editorial cards begin a dark narrative chapter.
6. **Audience relevance** — Two sparse copy-and-image treatments explain different users.
7. **Closing invitation** — Dark luminous horizon and a minimal utility row.

**Transfer:** Keep the abstract-to-concrete progression, adjusting the number and placement of proof scenes to the new product.

### Company narrative establishing mission, people and credibility

1. **Promise** — Centered ink statement followed by a full-width silhouetted human scene.
2. **Mission** — Immersive text gives way to an oversized quotation and attribution.
3. **Human context** — A tilted photo arc makes the organization tangible.
4. **Operating principles** — Numbered open two-column paragraphs communicate beliefs.
5. **People** — Long biographies contrast with square candid portraits.
6. **Invitation and activity** — A split recruitment message and lavender news rail broaden the story.
7. **Closing invitation** — White luminous horizon with the same minimal utility row.

**Transfer:** Replace mission, people and editorial material with authentic organizational content, preserving the open list and photographic pacing.

### Product capability page demonstrating systems, functionality and reach

1. **Promise** — Centered ink headline introduces a large cinematic product scene.
2. **Product demonstration** — White explanatory statement reveals over a dark angled monitor.
3. **Capability chapters** — An inset pale mosaic alternates mechanisms, comparisons and visual proof.
4. **Ecosystem proof** — A tilted photographic partner rail expands beyond the viewport.
5. **Coverage** — Centered heading and support lead into a pale large-format territory map.
6. **Closing invitation** — White luminous horizon ends the page without a dense sitemap.

**Transfer:** Use mechanisms and ecosystem evidence relevant to the new product; a pale network or service-area diagram can replace geography.

## Writing

Confident, plain-speaking and infrastructure-minded, with a human reason behind the technical capability. Claims are direct and explanatory rather than playful or aggressively sales-led.

**Do not copy:** Do not reuse amra's name, logo, artist and partner assets, quotes, proprietary platform claims, royalty figures, territory counts, audit promises or editorial headlines as claims for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use 'we' for the organization and 'your' when describing the reader's work or results. Headlines usually state an outcome without addressing the reader directly.
- **Rhythm:** Short benefit labels punctuate substantial explanatory paragraphs. Major statements often span two to four lines; supporting prose is full-sentence and can be longer than a typical landing-page blurb.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the desired outcome and simplify its perceived difficulty. | 4–9 words | “Global royalties made simple” |
| Opening explanation | State the product category and distinctive operating model in one sentence fragment. | 12–20 words | “The only platform built for global, direct music licensing and administration” |
| Benefit heading | A single plain adjective names the advantage. | 1–3 words | “Fast”<br>“Transparent” |
| Feature heading | Name a concrete capability rather than a vague emotional payoff. | 3–6 words | “Performance at scale”<br>“Full audit access” |
| Supporting paragraph | Explain the operating mechanism and its practical consequence. | 20–45 words | “Our no-middleman approach means no leakage – maximizing your income through our complete global licensing and administration platform.” |
| Action | A direct verb plus a familiar destination, not a slogan. | 2–4 words | “Explore the platform”<br>“Read Press” |

**Words and phrasing to use:** direct; transparent; global; scale; access; collect; process; your work; full picture

**Avoid:** magic; crush it; game-changer; effortless everything; !!!

**Rules:**

- Pair every broad advantage with the mechanism that makes it credible.
- Use verified numbers as complete readable statements, not decorative counters.
- Keep action labels concrete and short even when the nearby paragraph is substantial.
- Use one-word benefit labels sparingly to create pauses between explanatory chapters.

## Do's and Don'ts

### Do

- Keep the opening lead and gray explanation at the same 50px/1.2 regular recipe.
- Preserve 30px/1.2 body copy in major narrative and feature sections.
- Use 24px grid gutters and 160px major section breathing room.
- Keep the lavender header action to 32px high and section actions to 48px.
- Repeat the luminous spherical form at the opening and the ending.
- Make diagrams faint and spacious so floating labels remain legible.
- Reserve 8px corners for rectangular panels and circular masks for editorial images.
- Carry the 14px uppercase utility style through navigation, categories and footer links.

### Don't

- Do not make the site an all-dark dashboard; most of the marketing narrative is white.
- Do not use solid lavender as the default hero background; it belongs in objects, small actions and scoped news cards.
- Do not replace the flat pale feature cards with raised cards or heavy drop shadows.
- Do not bold every heading; hierarchy depends on color, measure and placement at weight 400.
- Do not fill explanatory cards with tiny dense interface controls; illustrations communicate a single mechanism.
- Do not round rectangular cards into exaggerated 24px tiles; reserve that radius for actions.
- Do not enlarge utility navigation to compete with the 30px explanatory text.
- Do not expose human subjects evenly with bright stock-photo lighting; preserve the cool backing and deep silhouette treatment.

## Motion and responsive

### Motion

**Observed:**

- Action color, background, border, opacity and fill transitions are declared at 0.1s.
- Reveal elements declare transform and opacity transitions lasting 1s, with cubic-bezier(0.28,1.1,0.74,1) and cubic-bezier(0.59,0.41,0.68,0.49) respectively.
- Immersive text progressively becomes fully legible while its background scene remains prominent.
- Circular platform elements declare 10s linear infinite rotation, with reverse and normal directions.

**Transfer:**

- Use the declared reveal pairing for major statements and let imagery remain visually stable beneath the text.
- Keep utility changes much faster than large object or section reveals.
- If implementing rotational diagram details, confine the motion to the graphic, not the surrounding typography.

**Unknown:**

- Exact scroll thresholds, sphere animation implementation and full timing of scene-to-scene theme changes.
- Keyboard focus appearance beyond the declared action states.

### Responsive

**Observed:**

- Styles declare width breakpoints at 650px, 1024px, 1280px and 1700px.
- The desktop composition uses a twelve-column grid and centered maximum-width wrappers.

**Transfer:**

- On narrow screens, retain the centered promise-over-object composition and crop the luminous sphere rather than squeezing it into a small icon.
- Stack copy and square imagery while retaining distinct narrative chapters; collapse the feature mosaic to a single readable column.
- Keep the capsule proof field horizontally clipped so scale remains perceptible without shrinking every record to unreadable text.

**Unknown:**

- Actual small-screen typography, side margins, navigation controls and breakpoint-specific stacking rules.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
