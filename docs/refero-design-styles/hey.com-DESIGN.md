# HEY — chunky type, human warmth

## Overview

An exuberant light style pairing massively weighted sans-serif headlines with friendly, slightly narrow everyday text. Warm off-white paper, bright violet, mint and coral make software feel personal rather than corporate. Large interface demonstrations, soft floating cards and small handmade graphic gestures suit opinionated products with a clear alternative to the status quo; the reading pace is spacious even when the story is long.

### Essentials

- Headlines feel like cheerful declarations, not elegant titles: Really Sans Large at 83.2px/1.1, weight 900, normal tracking, with violet-to-salmon text fill; section headlines use 48px/1.1 at 850.
- The opening is a white stage inside warm paper, with a floating capsule navigation: 32px outer gutters, 38.4px top canvas corners, a 1280px white card with 25.6px corners, centered review snippets, headline, bold support, one action and a tinted product preview.
- Actions look like candy lozenges: 62px main buttons, violet-to-salmon gradients, white small-cap lettering at 27.2px/1 and -0.0175em tracking; compact navigation actions are 46px high.
- Color punctuates a mostly neutral page: warm #f9f7f5 and white dominate the reading areas, violet appears in headings and links, mint backs small navigation pills, and a concentrated full-width violet announcement provides the loud contrast.
- Demonstrations float like tangible sheets: 896px or 1152px-wide interfaces, 22.4px rounded media corners and layered plum shadows. Include a tinted preview and an intelligible product scene; without interface media, draw a credible task/result diagram in the same white framed stage.
- The friendliness has graphic punctuation: a short pale wavy rule, small overlapping translucent blobs, and a scalloped violet announcement with mint-blue display text. Carry these devices into the new page, using simple SVG shapes rather than needing elaborate artwork.
- The ending is a warm send-off rather than a corporate directory: a 40px/1.1 violet wish, a 640px capsule email form, a centered wrapping cloud of mint navigation pills, then a prominent help line and compact maker credits.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#5522fa` | `--color-violet` | text, link, action, background, border | Main chromatic anchor: headline gradients, links, announcement fill and selected card outlines. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft mint | `#b3f4e0` | `--color-mint` | surface, accent | Footer link pills and the light end of mint panels. |
| Salmon | `#ec8580` | `--color-salmon` | accent, action | Warm end of headline and action gradients; announcement halo uses this hue at 10% opacity. |
| Coral | `#f95c5c` | `--color-coral` | action, accent | Warm contrasting action gradient and tiny new-item badges. |
| Fresh mint | `#5fddc5` | `--color-mint-strong` | surface, border, accent | Saturated end of mint panels, exclusive card edges and navigation hover underline. |
| Clear blue | `#0074e4` | `--color-blue` | action, accent | Blue end of the compact navigation action and blue pricing actions. |
| Ice blue | `#b6dbff` | `--color-ice-blue` | surface, accent | Testimonial gradient and cool announcement headline endpoint. |
| Pale sky | `#eef8ff` | `--color-ice-light` | surface | Light endpoint of testimonial cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White sheet | `#ffffff` | `--color-white` | background, surface, text | Outer page, cards, navigation, forms and reversed button text. |
| Warm paper | `#f9f7f5` | `--color-canvas` | background | Main inset page canvas. |
| Stone | `#edeae6` | `--color-stone` | surface, accent, text | Neutral sign-in button, wavy divider and subdued reversed announcement copy. |
| Muted plum | `#736c83` | `--color-muted` | text | Small italic reassurance beneath conversion actions. |
| Plum ink | `#231c33` | `--color-ink` | text | Default text and the hue beneath translucent shadows. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Plan inset paper | `#f7f4f0` | `--color-plan-inset` | surface | Small benefit rows inside white plan cards. |

## Typography

- **Moniker** — Paragraphs, navigation, captions and actions. Human, informal sans with a slightly narrow profile, open shapes and friendly curves. OpenType features: "case", "liga". If unavailable, use **Lato**. Use 400, 500 and 700; retain negative tracking and generous line heights. Font stack: "Moniker", "Lato", sans-serif.
- **Really Sans Large** — Headlines and emphatic feature titles. Very heavy, broad, tightly fitted sans with blunt terminals and lively chunky silhouettes. If unavailable, use **Archivo Black**. Match breadth first; keep normal tracking rather than compressing the heavy letters. Font stack: "Really Sans Large", "Archivo Black", sans-serif.
- **Shantell Sans** (only for playful inline headline ornaments) — Occasional handwritten arithmetic sign within a headline. Loose marker-like italic gesture, contrasting with heavy upright display letters. Font stack: "Shantell Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Really Sans Large | 900 | 83.2px | 1.1 | normal, features "case", "liga", "ss04" | Centered promise and large announcement headline. |
| heading | Really Sans Large | 850 | 48px | 1.1 | normal, features "case", "liga", "ss04" | Primary section heading; gradient by default in capability chapters, ink for social proof. |
| support-heading | Really Sans Large | 850 | 40px | 1.2 | normal, features "case", "liga", "ss04" | Bold secondary promise directly beneath the opening headline. |
| send-off | Really Sans Large | 900 | 40px | 1.1 | normal, features "case", "liga", "ss04" | Friendly violet newsletter closing wish. |
| body | Moniker | 400 | 27.2px | 1.4 | -0.0125em | Centered chapter descriptions, conversion support and newsletter invitation. |
| button | Moniker | 500 | 27.2px | 1 | -0.0175em, features "c2sc", "smcp" | Main conversion actions; use actual small caps rather than widely tracked uppercase. |
| compact-button | Moniker | 500 | 20.8px | 1 | -0.0175em, features "c2sc", "smcp" | Navigation and newsletter capsule actions. |
| navigation | Moniker | 500 | 20.8px | 1 | -0.0125em | Header links and footer mint pills. |
| reassurance | Moniker | 400 italic | 17.6px | 1.2 | -0.0125em | Quiet friction-removing note under the main action. |
| review-snippet | Moniker | 500 italic | 17.6px | 1.2 | -0.0125em | Short review phrases above the opening headline. |
| quote | Moniker | 400 | 17.6px | 1.45 | -0.0125em | Blue testimonial cards; selected phrases are bold. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | Really Sans Large | 800 | 64px | 1 | normal, features "case", "liga", "ss04" | White price with small period label alongside. |
| walkthrough and reassurance pages | lead | Moniker | 400 | 35.2px | 1.3 | -0.0125em | Introductory prose with selected bold phrasing. |
| walkthrough and reassurance pages | detail-heading | Really Sans Large | 850 | 32px | 1.1 | normal, features "case", "liga" | Violet heading in alternating mint explanation panels. |
| pricing pages | question | Really Sans Large | 850 | 30px | 1.1 | normal, features "case", "liga", "ss04" | Left-aligned question heading in expanded FAQ articles. |
| feature catalogs | feature-title | Really Sans Large | 850 | 27.2px | 1.1 | normal, features "case", "liga", "ss04" | Centered violet title inside catalog cards. |
| walkthrough, reassurance and pricing pages | detail-body | Moniker | 400 | 24px | 1.4 | -0.0125em | Left-aligned explanations and FAQ answers. |
| founder or editorial letters | letter | Moniker | 400 | 24px | 1.45 | -0.0125em | Long-form personal letter. |
| feature catalogs | feature-body | Moniker | 400 | 20.8px | 1.4 | -0.0125em | Centered paragraphs inside catalog cards. |

**Notes:**

- Display families use normal tracking even at their heaviest sizes; ordinary text consistently uses -0.0125em, while small-cap actions tighten to -0.0175em.
- The second line of an opening is unusually forceful: a 40px heavy display face, not a small gray paragraph. Detailed page introductions can instead use the scoped 35.2px lead.
- Gradient fill is clipped to the letters at 135deg, violet toward salmon. In the violet announcement, reverse the palette to mint toward ice blue.
- Inline italics, bold phrases and a handwritten plus sign keep centered copy conversational. Do not italicize entire blocks except short review and reassurance lines.

## Layout

**Density:** Airy: large type and generous pauses make lengthy explanations feel like a series of friendly demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 12.8px | Catalog title-to-body and detail panel text gaps. |
| 19.2px | Navigation item gaps and action/reassurance grouping. |
| 44.8px | Two neutral units: default card padding, column gutters and major internal stack gaps. |
| 64px | Media side padding, card-stack separation and smaller section pauses. |
| 96px | Intro side padding and larger section starts. |
| 128px | Large ending pauses and separation before the footer. |
| 150px | Top and bottom space in the full-width announcement. |

### Containers and grids

- **Inset canvas**: max width 1376px · side padding 32px. At 1440px, warm paper sits within white outer gutters; these are desktop target widths, not a universal fixed max-width system.
- **Opening card**: max width 1280px · side padding 44.8px. White opening stage within the inset canvas.
- **Reading column**: max width 768px · side padding 64px. Centered chapter prose and left-aligned FAQ answers; headings may extend beyond it.
- **Product stage**: max width 1152px · side padding 64px. Wide product demonstration, centered; compact stages use 896px.
- **Card columns**: 3 columns · gap 44.8px · side padding 44.8px. Masonry-like testimonial columns with independent heights; feature catalog uses the same gap with 64px side padding.
- **Plans** (only for pricing pages): 2 columns · gap 44.8px · side padding 44.8px. Two equally prominent white plan cards, 608px wide at desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Canvas top | 38.4px |
|  | Cards | 25.6px |
|  | Product media | 22.4px |
|  | Main actions | 74.8px |
|  | Compact actions | 57.2px |
|  | Footer pills | 43.7px |
|  | Navigation | 40.4px |
| founder or editorial letters | Letter sheet | 2.4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Floating sheet | `rgba(35, 28, 51, 0.02) 0px 0px 0px 1px, rgba(35, 28, 51, 0.2) 0px 6.4px 51.2px -25.6px, rgba(35, 28, 51, 0.3) 0px 12.8px 76.8px -32px, rgba(35, 28, 51, 0.4) 0px 12.8px 25.6px -38.4px, rgba(35, 28, 51, 0.5) 0px 25.6px 38.4px -51.2px, rgba(35, 28, 51, 0.6) 0px 38.4px 51.2px -64px` | White cards and large product scenes; the first layer provides a nearly invisible plum edge. |
| Quote lift | `rgba(35, 28, 51, 0.1) 0px 25.6px 12.8px -25.6px, rgba(35, 28, 51, 0.15) 0px 38.4px 25.6px -38.4px, rgba(35, 28, 51, 0.2) 0px 51.2px 38.4px -51.2px` | Soft shadow gathered beneath blue quotes. |
| Announcement halo | `rgba(236, 133, 128, 0.1) 0px 0px 38.4px 19.2px, rgba(236, 133, 128, 0.1) 0px 0px 48px 28.8px, rgba(236, 133, 128, 0.1) 0px 0px 57.6px 38.4px` | Warm glow around the violet announcement band. |

### Surfaces

#### Warm inset canvas · level 0

**Use:** Primary reading background.

**CSS:** `background: #f9f7f5; border-radius: 38.4px 38.4px 0px 0px; margin-left: 32px; margin-right: 32px`

**Observed:** Surrounded by white and tucked behind the navigation capsule.

**Transfer:** Keep the body warm and the outer gutters white.

#### White floating sheet · level 1

**Use:** Opening stage, cards and product grouping.

**CSS:** `background: #ffffff; border-radius: 25.6px; box-shadow: rgba(35, 28, 51, 0.02) 0px 0px 0px 1px, rgba(35, 28, 51, 0.2) 0px 6.4px 51.2px -25.6px, rgba(35, 28, 51, 0.3) 0px 12.8px 76.8px -32px, rgba(35, 28, 51, 0.4) 0px 12.8px 25.6px -38.4px, rgba(35, 28, 51, 0.5) 0px 25.6px 38.4px -51.2px, rgba(35, 28, 51, 0.6) 0px 38.4px 51.2px -64px`

**Observed:** White on warm paper, with soft depth rather than a strong visible outline.

**Transfer:** Use the layered shadow rather than replacing it with a dark border.

#### Blue quote paper · level 1

**Use:** Human proof cards.

**CSS:** `background: linear-gradient(135deg, #b6dbff 0px, #eef8ff 100%); border-radius: 25.6px`

**Observed:** Pale blue cards carry small dense quotes and white overlapping author chips.

**Transfer:** Keep quote backgrounds light enough for dark text.

#### Violet announcement · level 0

**Use:** Concentrated high-energy product announcement.

**CSS:** `background: #5522fa; padding-top: 150px; padding-bottom: 150px; box-shadow: rgba(236, 133, 128, 0.1) 0px 0px 38.4px 19.2px, rgba(236, 133, 128, 0.1) 0px 0px 48px 28.8px, rgba(236, 133, 128, 0.1) 0px 0px 57.6px 38.4px`

**Observed:** Full bleed with scalloped upper and lower edges and faint tilted interface imagery underneath the text.

**Transfer:** Keep the saturated field concentrated here rather than behind all chapters.

#### Mint explanation panel · level 1

**Only for:** walkthrough and reassurance pages

**Use:** Paired explanatory prose and compact interface illustrations.

**CSS:** `background: linear-gradient(135deg, #5fddc5 0px, #b3f4e0 100%); border-radius: 25.6px; padding: 44.8px; gap: 44.8px; transform: rotate(-1deg)`

**Observed:** Alternates image and text, left/right offset and slight opposing rotations.

**Transfer:** Use for a small group of concrete assurances or closely related mechanisms.

#### Letter paper · level 1

**Only for:** founder or editorial letters

**Use:** A sustained personal argument.

**CSS:** `background: #ffffff; border-radius: 2.4px; padding: 90px 96px; transform: rotate(-0.8deg)`

**Observed:** A narrow white sheet with offset paper layers behind it and a handwritten signature at the bottom.

**Transfer:** Use the paper metaphor only for genuine personal prose.

## Components

### Capsule navigation

**Use:** Top-level navigation.

**CSS:** `background: #ffffff; border-radius: 40.4px; width: 1141px; height: 81px; display: flex; align-items: center; justify-content: space-between; box-shadow: rgba(35, 28, 51, 0.02) 0px 0px 0px 1px, rgba(35, 28, 51, 0.2) 0px 6.4px 38.4px -12.8px, rgba(35, 28, 51, 0.3) 0px 12.8px 64px -25.6px, rgba(35, 28, 51, 0.4) 0px 12.8px 12.8px -25.6px, rgba(35, 28, 51, 0.5) 0px 25.6px 25.6px -38.4px, rgba(35, 28, 51, 0.6) 0px 38.4px 38.4px -51.2px`

**Text style:** `navigation` — Moniker 500 · 20.8px/1 · tracking -0.0125em

**Observed:** A centered floating bar near the top, logo left, short links through the middle, neutral sign-in and blue-violet trial actions right. New-item badges perch above a link.

**Transfer:** Keep labels short enough to preserve the capsule silhouette.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: linear-gradient(135deg, #5522fa 0px, #ec8580 100%); color: #ffffff; border-radius: 74.8px; padding: 23.8px 29.9px; display: flex; align-items: center; justify-content: center; overflow: clip`

**Text style:** `button` — Moniker 500 · 27.2px/1 · tracking -0.0175em

**Observed:** The visible pill is 62px high; label spans use optical negative vertical margins. A faint pointer-centered radial highlight overlays the gradient. The announcement variant runs salmon to coral; the persistent lower-right version adds a white hand-like icon before the label.

**States:** Declared: hover keeps white text; color transitions over 0.15s ease. Focus-visible and active treatments are unknown.

**Transfer:** If rebuilding without optical text offsets, use a 62px border-box height and center the label; do not add the full padding to an uncompensated line box.

### Compact action

**Use:** Navigation trial and sign-in controls.

**CSS:** `background: linear-gradient(135deg, #5522fa 0px, #0074e4 100%); color: #ffffff; border-radius: 57.2px; padding: 16.6px 21.3px; display: flex; align-items: center; justify-content: center`

**Text style:** `compact-button` — Moniker 500 · 20.8px/1 · tracking -0.0175em

**Observed:** 46px visible height, with optical label offsets like the main action. Sign-in uses stone fill with plum ink; the newsletter version uses the violet-salmon gradient.

**States:** Declared: hover retains white for the gradient action and plum for sign-in; color 0.15s ease.

### Text navigation link

**Use:** Links inside the navigation capsule.

**CSS:** `color: #231c33; padding: 10.9px 0px 8.3px`

**Text style:** `navigation` — Moniker 500 · 20.8px/1 · tracking -0.0125em

**Observed:** Links sit on white without their own backing; underline is visually subdued until interaction.

**States:** Declared: hover color #5522fa, underline color #5fddc5 and thickness 0.1em; color and underline transitions 0.15s ease.

### Footer link pill

**Use:** A wrapping index of destinations.

**CSS:** `background: #b3f4e0; color: #5522fa; border-radius: 43.7px; padding: 12.5px 18.7px 10.4px; display: flex`

**Text style:** `navigation` — Moniker 500 · 20.8px/1 · tracking -0.0125em

**Observed:** Many text-width pills wrap into centered rows, with 9.4px row and 7.3px column gaps. Occasional tiny coral new-item labels sit above the top-left edge.

**States:** Declared: hover background #5522fa and text #ffffff; background and color transition 0.15s ease.

### Testimonial card

**Use:** Person-to-person proof.

**CSS:** `background: linear-gradient(135deg, #b6dbff 0px, #eef8ff 100%); border-radius: 25.6px; padding: 44.8px; box-shadow: rgba(35, 28, 51, 0.1) 0px 25.6px 12.8px -25.6px, rgba(35, 28, 51, 0.15) 0px 38.4px 25.6px -38.4px, rgba(35, 28, 51, 0.2) 0px 51.2px 38.4px -51.2px`

**Text style:** `quote` — Moniker 400 · 17.6px/1.45 · tracking -0.0125em

**Observed:** Independent-height cards form three columns. A tiny white author pill with circular portrait overlaps the upper-left corner. Selective bold words carry the emotional claim, while inline links remain violet.

**Transfer:** Use real attributed experiences, varying lengths, and restrained bold emphasis.

### Newsletter capsule

**Use:** Email subscription form near the footer.

**CSS:** `background: #ffffff; border-radius: 76.8px; width: 640px; padding: 9.6px; display: flex; align-items: center; gap: 9.6px; box-shadow: rgba(35, 28, 51, 0.05) 0px 0px 0px 1px, rgba(35, 28, 51, 0.2) 0px 6.4px 38.4px -12.8px, rgba(35, 28, 51, 0.3) 0px 12.8px 64px -25.6px, rgba(35, 28, 51, 0.4) 0px 12.8px 12.8px -25.6px, rgba(35, 28, 51, 0.5) 0px 25.6px 25.6px -38.4px, rgba(35, 28, 51, 0.6) 0px 38.4px 38.4px -51.2px`

**Observed:** A borderless email input occupies most of the width; Compact action nests at the right. The whole unit is about 65px high.

**Transfer:** Keep one field and one action, not a stacked lead-generation form.

### Feature catalog card

**Only for:** feature catalogs

**Use:** Browsable inventory of capabilities.

**CSS:** `background: #ffffff; border-radius: 25.6px; padding: 44.8px; display: inline-flex; flex-direction: column; align-items: center`

**Text style:** `feature-body` — Moniker 400 · 20.8px/1.4 · tracking -0.0125em

**Observed:** A small multicolor blob precedes Feature-title and centered body copy. Three independent-height columns make a lively masonry wall. Exclusive variants add a 1px mint or violet edge and a tiny matching badge centered across the top.

**Transfer:** Let copy length determine card height instead of forcing equal rows.

### Price panel

**Only for:** pricing pages

**Use:** Highly visible cost and conversion inside a white plan card.

**CSS:** `background: #5522fa; border-radius: 14.4px; padding: 41.6px; display: flex; flex-direction: column; color: #ffffff`

**Text style:** `price` — Really Sans Large 800 · 64px/1

**Observed:** Large amount and small billing period share one line; a blue pill CTA sits underneath. Below, white plan cards stack warm inset benefit rows with short linked headings and smaller explanations.

**Transfer:** Give both offers equally legible cost panels rather than using a dashboard-like comparison matrix.

### FAQ question

**Only for:** pricing pages

**Use:** Anchored questions in expanded FAQ sections.

**CSS:** `color: #231c33`

**Text style:** `question` — Really Sans Large 850 · 30px/1.1

**Observed:** Questions are bold text anchors followed by visible 24px answers, not closed accordion controls. Question-answer pairs have about 44px between them; larger groups are separated by 96px and centered gradient headings.

**States:** Declared: hover retains #231c33 with color 0.15s ease.

## Imagery and graphics

### Tinted product preview

**Use:** Hero demonstration invitation.

**Observed:** A real interface is visible underneath a strong violet-to-salmon wash inside an 896px-wide white-backed rounded frame. A small white play capsule is centered over it. This preview enters the first screen near its bottom and continues below the fold.

**Transfer:** Use a genuine task view or a clean diagram of the product's main transformation, retaining the tinted invitation layer and white play control.

**Build:** Layer an interface image beneath a full-frame linear-gradient(135deg, rgba(85,34,250,0.8), rgba(236,133,128,0.8)); clip the stage to 25.6px top corners, then place a centered white 54px-high play lozenge with plum text. Match the visible wash; exact opacity is not essential.

### Floating interface demonstrations

**Use:** Main capability chapters.

**Observed:** Large light interfaces show useful, populated tasks rather than generic device mockups. They occupy substantially more width than the prose above them, have rounded white edges and soft plum shadows, and are shown straight-on. Smaller detail illustrations isolate one action rather than an entire application.

**Transfer:** Show one legible user task per chapter; if no interface exists, compose a white task/result illustration with real content and the same visual depth.

### Scalloped announcement artwork

**Use:** Signature saturated contrast band.

**Observed:** A violet field is edged with small regular waves. An enlarged, slightly rotated calendar interface is barely visible beneath the color, while a warm salmon glow softens the perimeter.

**Transfer:** Use the new product's task view as a low-contrast underpainting; a simple faint grid and content blocks is the minimum substitute.

**Build:** Back a full-width band with violet. Add an oversized interface layer rotated about -5deg and washed almost completely in violet. Repeat a shallow SVG sine-wave edge along top and bottom, then apply Announcement halo. Put mint-to-ice-blue clipped display text above all image layers.

### Wavy rule and friendly line art

**Use:** Between narrative chapters and above the closing wish.

**Observed:** The divider is a short, pale stone squiggle centered within a much taller whitespace interval. The closing wish is crowned by small hand-drawn violet-blue outline art.

**Transfer:** Preserve the small informal gesture, replacing it with a simple product-appropriate line drawing.

**Build:** Draw a centered SVG path using repeated smooth quadratic waves, about 240px wide with 6px stroke in stone, inside a 192px-tall divider region. For the closing marker, draw one rounded-line friendly symbol at roughly 80px high in violet/blue; keep it sparse, not a detailed mascot.

### Translucent blob emblems

**Only for:** feature catalogs

**Use:** Small decorative markers above each catalog title.

**Observed:** Overlapping irregular translucent ovals in violet, mint, coral, blue and occasional yellow form tiny pebble-like emblems. They are colorful but flat, not glossy 3D objects.

**Transfer:** Create a few repeatable abstract emblems rather than a different literal icon for every capability.

**Build:** In an approximately 90px by 72px SVG, overlap three asymmetric rounded paths or skewed ellipses, each 55–75px wide. Offset centers by 8–16px, rotate individual shapes about 15–35deg and use 0.55–0.85 opacity. Combine mint/blue with violet or coral/violet so intersections visibly darken; no shadow or extrusion.

### Stacked personal letter

**Only for:** founder or editorial letters

**Use:** Long-form authored statement.

**Observed:** A tall white letter sheet with subtly offset and tilted white sheets behind it, generous inner margins and a dark handwritten signature. No portrait dominates the letter.

**Transfer:** Set genuine first-person prose on an approximately 841px-wide sheet and finish with a name, role and signature if appropriate.

**Build:** Place two white pseudo-element rectangles behind Letter paper, offset by 10–20px and rotated in opposing directions under 1deg. Use soft plum shadows and retain the nearly square corners.

### Icons

**Observed:** Marketing iconography is sparse: play triangle, a hand-like outline beside signup, small review stars and dark filled partner marks around 24–28px. Catalog blobs are decoration rather than functional symbols.

**Transfer:** Use simple, friendly silhouettes or rounded line drawings; avoid filling every paragraph with an icon.

## Section recipes

How recurring sections are built.

### First screen: White stage opening

**Observed:** A floating Capsule navigation sits over the top of Warm inset canvas. Inside it, a 1280px White floating sheet creates a centered stage. Three small italic star-review phrases span the upper area. The 83.2px gradient display headline occupies about two thirds of the viewport width and wraps to two lines, with a handwritten plus as a playful inline accent. Beneath it is a substantial two-line 40px ink Support-heading, followed by Primary button and the 17.6px italic reassurance note. The 896px Tinted product preview begins near the bottom of the first 900px; its top is visible but most of the object and its central play control continue below the fold. Layers are white outer page, warm inset canvas, shadowed white stage, text/action stack, then tinted media.

**Transfer:** Make a direct, forceful promise that fits two broad lines, use a short credibility strip, and stage the product's key task below the action. If video is unavailable, use a tinted task diagram as the same invitation. Pricing and catalog pages open directly on warm paper without the big white stage; walkthrough and reassurance pages can use Lead prose instead of the bold support line.

**Avoid:** Do not turn this into a left-copy/right-device SaaS hero, shrink the promise to a normal heading, or move the product object above the primary action.

**Text style:** `display` — Really Sans Large 900 · 83.2px/1.1

### Capability heading and demonstration

**Observed:** A centered 48px gradient Heading leads a 768px-wide Body description with selected bold phrases. A Floating interface demonstration follows about 44.8px later at 1152px width. Subsequent chapter headings sit roughly 160px after the previous image, making each capability feel like a fresh thought.

**Transfer:** Explain one change in the user's working life, then show the task that proves it. Use fewer stronger chapters for a shorter page.

**Text style:** `heading` — Really Sans Large 850 · 48px/1.1

### Human proof wall

**Observed:** An ink Heading with an italic emphasized word introduces a centered Body paragraph. Testimonial cards then flow through three columns with 44.8px gutters and variable heights; white portrait author pills overlap their tops. A bold concluding line and underlined violet continuation link finish the proof.

**Transfer:** Use actual varied-length reactions and place the proof where it best answers skepticism.

### Scalloped bright announcement

**Observed:** Violet announcement forms a 603px full-width contrast band. Mint-blue Display, a white Heading, stone Body copy and a salmon/coral Primary button form a centered stack over Scalloped announcement artwork. About 150px of breathing space sits above and below the content.

**Transfer:** Give an important adjacent benefit, launch or next step its own concentrated burst of color; preserve this graphic device without requiring the original subject.

**Text style:** `display` — Really Sans Large 900 · 83.2px/1.1

### Friendly newsletter and link-cloud ending

**Observed:** After a 128px pause, white returns. Small outline art crowns the violet 40px Send-off, followed by newsletter prose with a bold proof phrase. Newsletter capsule sits below; Footer link pills wrap in centered rows rather than columns. A larger help sentence with underlined violet destination follows, then small dark maker marks and copyright. All five page types share this ending, while the adjective in the wish varies.

**Transfer:** Finish warmly, offer one low-pressure way to stay connected, and provide a useful index of real destinations. Keep the help line distinct from small credits.

**Text style:** `send-off` — Really Sans Large 900 · 40px/1.1

### Alternating mint explanations

**Only for:** walkthrough and reassurance pages

**Observed:** Mint explanation panels alternate image/text sides and slight tilt, with 44.8px padding and gaps, 64px between panels, violet Detail-heading and left-aligned Detail-body. Compact white interface scenes take about half each panel.

**Transfer:** Use for tightly related mechanisms, policies or assurances that merit reading rather than fast scanning.

**Text style:** `detail-heading` — Really Sans Large 850 · 32px/1.1

### Catalog wall

**Only for:** feature catalogs

**Observed:** A centered gradient Display and bold Support-heading precede a tour action. Three independent-height columns of Feature catalog cards start about 96px later, each containing a Translucent blob emblem, violet Feature-title and centered Feature-body. White space and shadows separate the cards, not grid rules.

**Transfer:** Organize an extensive inventory without turning it into tiny icon lists; include fewer cards when content is limited.

**Text style:** `feature-title` — Really Sans Large 850 · 27.2px/1.1

### Two offer comparison and open FAQ

**Only for:** pricing pages

**Observed:** A gradient Display promise and bold Support-heading lead two equal white plan cards. Each starts with name and explanation, then Price panel, then warm benefit rows. A smaller centered offer note follows, then Wavy rule and friendly line art separates the FAQ area. Narrow expanded FAQ sections use centered gradient Heading, left-aligned Question and Detail-body answers.

**Transfer:** Make pricing understandable before discussing edge cases. Keep answers readable without requiring interaction.

**Text style:** `price` — Really Sans Large 800 · 64px/1

### Authored paper argument

**Only for:** founder or editorial letters

**Observed:** An ink Heading and centered Body summary lead into Stacked personal letter. Letter text is 24px/1.45, left aligned with generous paragraph pauses; the sheet ends with handwritten signature, name and role.

**Transfer:** Reserve the sustained format for a personal explanation with a real point of view.

**Text style:** `letter` — Moniker 400 · 24px/1.45 · tracking -0.0125em

## Page flow

**Storyline:** Bold promise → concrete demonstration or offer → proof and explanation → reassurance → bright adjacent invitation → warm newsletter and useful link cloud.

### Flagship marketing landing page

1. **Promise** — White stage with review strip, oversized gradient declaration, bold contrast statement and trial action.
2. **Social proof** — Blue testimonial masonry with portrait chips.
3. **Capability chapters** — Centered gradient heading/body pairs above wide white interface scenes.
4. **Personal conviction** — Paper-stacked authored letter after a synthesis paragraph.
5. **Closing invitation** — Scalloped violet announcement, then friendly newsletter, mint link cloud, help and maker credits.

**Transfer:** Choose the strongest demonstrations and proof for the new product, retaining the paper-and-color contrast rather than matching the number of chapters.

### Pricing and objections

1. **Offer framing** — Short gradient declaration over a forceful value statement.
2. **Pricing** — Equal white plan cards with violet price panels and warm benefit rows.
3. **Secondary offer** — Centered short offer note with inline links.
4. **Objection handling** — Expanded FAQ groups in a narrow reading column.
5. **Closing invitation** — Shared violet announcement followed by newsletter, link pills, help and maker credits.

**Transfer:** State the economic model directly, then answer practical billing and cancellation questions in plain language.

### Detailed product walkthrough

1. **Promise** — Gradient display and large introductory prose above a wide interface scene with playful abstract backing.
2. **Deep demonstration** — Long-form tour action, followed by capability headings and screenshots.
3. **Mechanism explanation** — Alternating tilted mint panels and smaller side-by-side workflow illustrations.
4. **Synthesis** — Centered conclusion after a pale wavy rule.
5. **Closing invitation** — Violet announcement and shared newsletter/link-cloud ending.

**Transfer:** Move from a familiar overall task to the surprising details; vary large scenes with smaller explanation pairs.

### Focused reassurance or policy story

1. **Trust promise** — Short gradient headline, bold support statement and large prose intro.
2. **Concrete assurances** — Alternating mint panels pairing readable explanations with proof views.
3. **Low-pressure conversion** — Warm paragraph, trial action and small italic friction-removing note.
4. **Closing invitation** — Violet announcement and shared friendly footer.

**Transfer:** Translate promises into explicit user rights or controls, then end without pressure.

### Extensive capability catalog

1. **Discovery promise** — Gradient display, heavy support line and tour action.
2. **Capability inventory** — Three-column masonry of white text cards with overlapping translucent emblems and occasional exclusive badges.
3. **Closing invitation** — Violet announcement then the same newsletter, link cloud, help and maker ending.

**Transfer:** Let card lengths vary and give every feature a user-facing benefit rather than a technical category name.

## Writing

Opinionated, conversational and openly delighted with a better way of doing familiar work. Confident claims are grounded in concrete behaviors, while reassurance sounds like a person taking your side.

**Do not copy:** Do not reuse HEY or 37signals names, logos, signature hand artwork, personal signatures, customer quotes, subscriber counts, prices, trial terms or product claims; create truthful equivalents for the new brand. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and describe the team as we. Name concrete product mechanisms when explaining them; avoid impersonal enterprise language.
- **Rhythm:** Short declarative headlines alternate with readable conversational paragraphs. Fragments, contractions, rhetorical questions, a little italics and occasional exclamation marks make the pitch lively, not breathless.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Promise | Familiar frustration meets a blunt announcement of change. | 3–10 words | “We didn’t reinvent the wheel, only email”<br>“Email, unexpected” |
| Capability heading | Make a benefit tangible with a familiar action or analogy. | 4–10 words | “Screen emails like you screen your calls”<br>“Surface files, don’t dig for them” |
| Supporting statement | State a principle in ordinary human words, with a reversal or contrast. | One or two sentences | “We’re not here to lock you in, we’re here to help you out.” |
| Primary action | Direct verb plus product, outcome or trial term. | 3–7 words | “Try [Brand] free for 30-days”<br>“Take a closer look” |
| Reassurance | Remove a specific worry without legalese. | One short sentence | “No obligation, no CC required.”<br>“100% your call, no surprises.” |
| Transition | A spoken phrase that promises more without sounding like an index. | 5–10 words | “And that’s just the tip of the iceberg” |

**Words and phrasing to use:** you’re in control; fresh start; out of your way; take a closer look; we fixed it; here to help; feels like magic

**Avoid:** leverage; unlock synergies; enterprise-grade transformation; best-in-class solutions; seamless ecosystem

**Rules:**

- Name the old irritation before explaining the new mechanism.
- Use bold to emphasize the practical payoff, not every product noun.
- Keep reassuring copy specific about what will and will not happen.
- Use colorful language sparingly; give longer paragraphs real explanatory content.
- Make the final wish sound generous, not like another sales demand.

## Do's and Don'ts

### Do

- Keep the headline heavy: 900 at 83.2px, with normal tracking.
- Use the 40px bold support line when opening with a strong contrast statement.
- Preserve 44.8px card padding and gutters so small text feels comfortably framed.
- Make long explanations readable in a 768px column even when images span 1152px.
- Give main actions a 62px visible capsule with small-cap lettering, not a compact rectangular control.
- Use variable-height blue quotes and white catalog cards rather than forcing all content into equal-height tiles.
- Keep the footer's mint pills as a centered wrapping cloud and retain its distinct help line.
- Give saturated violet a concentrated full-width moment, with scalloped edges and a warm halo.

### Don't

- Do not replace plum #231c33 with pure black throughout; the neutral tone should remain warm and slightly purple.
- Do not apply negative display tracking just because the font is heavy; its recipe uses normal tracking.
- Do not use glass blur or shiny 3D chrome for the cards; these are opaque paper-like surfaces.
- Do not flatten every surface into off-white; white cards must remain visibly separate from #f9f7f5.
- Do not make every button the same blue: main conversion is violet-salmon, compact header conversion is violet-blue, announcement contrast is salmon-coral.
- Do not stretch the catalog into a tidy equal-row dashboard; 44.8px gutters and independent heights are part of its character.
- Do not close all FAQ answers behind chevrons; the pricing treatment reads as open articles.
- Do not use a conventional dark multi-column footer in place of the white send-off and mint link cloud.

## Motion and responsive

### Motion

**Observed:**

- Links and pills declare 0.15s ease color/background transitions; navigation underline color and thickness use the same duration.
- Author chips declare hover rotate(-2deg) scale(1.05); other transforms include 0.15s and 0.3s ease transitions.
- Gradient actions declare a subtle pointer-positioned radial highlight. A persistent lower-right signup action is fixed, while the top navigation is positioned absolutely.
- The closing wish changes its adjective; flipIn, flipOut and pill keyframe names are declared.

**Transfer:**

- Keep action feedback short and color-led, with the playful small author-chip tilt reserved for attributed proof.
- Retain the discreet lower-right conversion pill on long pages without obscuring text.

**Unknown:**

- Focus-visible and active appearances, timing of the signup entrance, adjective-change interval and keyframe choreography are unknown.

### Responsive

**Observed:**

- Declared width breakpoints are 512px, 576px, 768px and 1024px. No viewport-relative size formula is available for the desktop type recipes.

**Transfer:**

- Recommended: collapse the independent card columns progressively while preserving 44.8px-style breathing room relative to available width.
- Recommended: stack the mint panel's image and explanation on narrow screens and reduce its tilt if needed to avoid clipping.
- Recommended: scale the heavy centered headline to preserve its broad two-line impact, and keep the media after the action rather than switching to a split hero.

**Unknown:**

- Exact mobile sizes, gutters, navigation replacement and breakpoint-specific layouts were not observed.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
