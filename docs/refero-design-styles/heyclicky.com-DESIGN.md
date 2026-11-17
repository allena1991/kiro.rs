# heyclicky — desktop playground nostalgia

## Overview

An affectionate, slightly chaotic desktop world surrounds very simple lowercase messaging. Pale gray space and tightly tracked grotesk type keep the page readable while glossy blue controls, silver application windows, candid video and internet ephemera supply personality. It suits approachable consumer software and creative tools, with airy storytelling around compact, tactile objects rather than a dense enterprise dashboard.

### Essentials

- The promise sits inside a desktop collage, not above an illustration: an 88px Inter headline at weight 500 and -0.03em tracking occupies the clear center of a dotted field, with small media windows orbiting it.
- Controls feel like translucent candy: 40px-high pills use 1px dark outlines, silver or five-stop blue gradients, a narrow white gloss near the top and a 0px 10px 24px shadow.
- Most of the page remains pale gray and black: #f5f5f5 is the continuous canvas, #0f7fff marks links, and saturated color is concentrated in media, tiny stickers and one immersive sky-backed commercial chapter rather than every section.
- Proof is staged as old desktop software: silver title bars, traffic-light controls, 8px inner corners and 16px outer media frames contain real demonstrations and compact social posts.
- Digital objects become expressive artwork: repeated folder-like tiles form a rainbow wave behind a document and a monumental cyan word sculpture at the ending. Rebuild these with original SVG objects when there is no product-specific equivalent.
- The voice lowers the stakes while the visuals raise the energy: mostly lowercase, a 20px/1.5 supporting line, 16px/1.5 body copy and plain invitations such as short verb-led actions, punctuated by tiny 12px uppercase capsule labels.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| System blue | `#0f7fff` | `--color-action` | action, link, accent | Text links and the blue wash on the recommended plan; not a default page fill. |
| Sky blue | `#2a6fb5` | `--color-sky-deep` | background | Top of the immersive sky-backed commercial scene. |
| Blue outline | `#221898` | `--color-blue-edge` | border | Fine indigo edge of blue candy buttons. |
| Sky haze | `#7db0dd` | `--color-sky-middle` | background | 52% stop of sky backing. |
| Clear blue base | `#99cbf8` | `--color-blue-lower` | surface | 80% stop of blue controls. |
| Periwinkle body | `#a2c7ff` | `--color-blue-middle` | surface | 50% stop of blue controls. |
| Cyan reflection | `#a2d2f7` | `--color-blue-bottom` | surface | Bottom reflection in blue controls. |
| Marker yellow | `#fff8bb` | `--color-highlight` | surface | Visible yellow marker over white, made with rgba(254,234,61,0.35), for a short emphasized sentence. |
| Pale blue shoulder | `#d6e7ff` | `--color-blue-upper` | surface | 18% stop of blue controls. |
| Sky mist | `#dcecf7` | `--color-sky-bottom` | background | Bottom of sky backing before it fades to the canvas. |
| Icy blue highlight | `#edf4ff` | `--color-blue-top` | surface | Top of the blue control gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border | Headlines, primary copy, fine window outlines and symbols. |
| Body gray | `#626262` | `--color-body-muted` | text, border | Footer links use black at 60% over the canvas; silver button edges use solid #626262. |
| Menu gray | `#6e6e6e` | `--color-nav-muted` | text | Black at 55% over canvas for menu links. |
| Secondary gray | `#7b7b7b` | `--color-secondary` | text | Visible equivalent of black at 50% over the page canvas; supporting prose. |
| Caption gray | `#939393` | `--color-caption` | text | Black at 40% over canvas for filename and compatibility captions. |
| Faint markings | `#acacac` | `--color-faint` | text, border | Black at 30% over canvas for status markings and capsule outlines. |
| Silver sides | `#d6d5d7` | `--color-silver-edge` | surface | Sides of horizontal metallic title-bar gradients. |
| Glass edge | `#e1e1e1` | `--color-glass-edge` | border | Visible black at 8% over canvas for subtle glass outlines. |
| Button foot | `#e4e4e4` | `--color-button-bottom` | surface | Base of silver buttons. |
| Menu hairline | `#e9e9e9` | `--color-hairline` | border | Visible black at 5% over canvas beneath the menu. |
| Button middle | `#ededed` | `--color-button-mid` | surface | 42% stop in silver buttons. |
| Silver highlight | `#f0f0f0` | `--color-silver-light` | surface | Center of metallic window gradients. |
| Desktop gray | `#f5f5f5` | `--color-canvas` | background | Continuous page canvas. |
| Button highlight | `#fbfbfb` | `--color-button-top` | surface | Top of silver controls and lower glass gradient stop. |
| Document white | `#ffffff` | `--color-white` | surface, text | Document and feedback interiors; reversed headings against sky. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| special-offer panels | Terminal charcoal | `#303030` | `--color-offer-dark` | surface | Visible rgba(26,26,26,0.9) over the canvas in the special-offer window. |

## Typography

- **Inter** — All ordinary headings, copy, navigation and actions. Modern grotesk with a high x-height, compact lowercase forms and consistently negative tracking. Font stack: "Inter", "Inter Fallback", -apple-system, system-ui, sans-serif.
- **Geist Mono** (only for special-offer panels) — Bracketed offer titles and explanatory copy. Friendly regular-width monospace that makes the offer read like a small terminal message. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 500 | 88px | 1.1 | -0.03em | Centered product-name hero headline. |
| heading | Inter | 500 | 56px | 1.2 | -0.03em | Major section titles and repeated proof headline. |
| lead | Inter | 400 | 20px | 1.5 | -0.03em | Hero and section support lines; document prose uses the same geometry with lowercase treatment. |
| question | Inter | 500 | 20px | 1 | -0.03em | FAQ question text. |
| button | Inter | 500 | 18px | 1.5 | -0.03em | Glossy primary and secondary controls and billing selection. |
| body | Inter | 400 | 16px | 1.5 | -0.03em | Explanations, footer links and answer copy. |
| navigation | Inter | 400 | 14px | 1 | -0.03em | Compact desktop menu links. |
| eyebrow | Inter | 500 | 12px | 1.5 | -0.03em, uppercase | Small metallic capsule labels above selected chapters. |
| caption | Inter | 400 | 12px | 1.5 | -0.03em | Filenames under media and compatibility notes under actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing comparisons | price | Inter | 500 | 56px | 1 | -0.03em | Large prices centered inside plans. |
| pricing comparisons | plan-title | Inter | 500 | 28px | 1 | -0.03em | Plan names; the highest tier alone uses weight 800. |
| special-offer panels | offer-title | Geist Mono | 500 | 20px | 1.5 | -0.03em, lowercase | Angle-bracketed offer heading. |
| special-offer panels | offer-body | Geist Mono | 400 | 16px | 1.5 | -0.03em, lowercase | Personal explanation below the bracketed title. |

**Notes:**

- Tracking stays at -0.03em across the core scale rather than switching to loose display lettering. Weight 500, not bold, carries the large hierarchy.
- Lowercase is the default verbal presentation; uppercase is reserved for tiny capsule labels. Prices keep a tighter line box than section headings.
- The sculptural closing word is object artwork, not another oversized text-font recipe.

## Layout

**Density:** Airy between scenes, compact within the desktop objects: the whitespace lets small playful details coexist without crowding the message.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Headline-to-subtitle gap, action-to-caption gap and FAQ row separation. |
| 10px | Icon-to-label gap and document paragraph rhythm. |
| 12px | Footer link stack gap and capsule horizontal padding. |
| 16px | Menu link gap, action group gap and grid gutters. |
| 20px | FAQ padding and button right padding. |
| 24px | Document horizontal padding, plan content padding and menu side inset. |
| 32px | Hero copy group to action group. |
| 48px | Vertical separation between demonstration rows. |
| 64px | Demonstration text-to-media gap and major heading-to-proof spacing. |
| 104px | Proof chapter and secondary-page listing section vertical padding. |
| 128px | Demonstration chapter vertical padding. |

### Containers and grids

- **page-stage**: max width 1440px. Centered desktop art stage; full-width bands sit inside the same broad canvas.
- **content-stage**: max width 1090px. Demonstration rows, social proof wall and footer content centered on desktop.
- **demo-row**: max width 1090px · 2 columns · gap 64px. A narrow text rail beside a 706px-wide media object; alternate sides across repeated rows.
- **proof-grid**: 3 columns · gap 16px. Three 353px columns of independently stacked social windows.
- **question-column**: max width 834px · gap 8px. Centered FAQ with a narrower 480px answer measure.
- **footer-columns**: max width 1090px · 4 columns · gap 31px. Four evenly sized columns for navigation, resources, social links and a short assurance.
- **culture-stage** (only for recruitment pages): max width 1440px · side padding 32px. Centered introductory text over nearly edge-to-edge team photography.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | pills | 9999px (pill) |
|  | window-and-card | 8px |
|  | outer-media | 16px |
|  | document-inner | 4px |
| pricing comparisons | billing-shell | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-object | `0px 10px 24px 0px rgba(0,0,0,0.12)` | Buttons, glass plan windows and document objects. |
| feedback-card | `0px 4px 12px 0px rgba(0,0,0,0.08)` | Small social proof windows. |
| glass-relief | `0px 10px 24px 0px rgba(0,0,0,0.12), 0px 1px 1px 0px rgba(255,255,255,0.8) inset, 0px 0px 0px 1px rgba(255,255,255,0.25) inset` | Transparent plan and billing shells. |

### Surfaces

#### Desktop canvas · level 0

**Use:** Continuous neutral backing.

**CSS:** `background-color: #f5f5f5`

#### Dotted desktop · level 0

**Use:** Opening scene texture.

**CSS:** `background-color: #f5f5f5; background-image: radial-gradient(rgba(0, 0, 0, 0.13) 1px, rgba(0, 0, 0, 0) 1.3px); background-size: 34.2px 34px`

**Observed:** Tiny low-contrast dots extend behind floating media and leave the typography legible.

**Transfer:** Keep the dots subordinate to the desktop objects.

#### Silver window chrome · level 1

**Use:** Application-style media frames.

**CSS:** `background-image: linear-gradient(90deg, #d6d5d7, #f0f0f0 50%, #d6d5d7); border: 0.5px solid #000000; border-radius: 8px; padding: 8px 4px 4px; filter: drop-shadow(0px 10px 12px rgba(0,0,0,0.12))`

**Observed:** A white inset highlight catches the top edge; a small title bar separates the chrome from media.

**Transfer:** Use the material as a frame, not as a full-page metallic background.

#### Glass window · level 1

**Use:** Plan cards and the billing shell.

**CSS:** `background-image: linear-gradient(rgba(255,255,255,0.3) 0%, rgba(231,231,231,0.3) 42%, rgba(251,251,251,0.3) 100%); border-radius: 8px; box-shadow: 0px 10px 24px 0px rgba(0,0,0,0.12), 0px 1px 1px 0px rgba(255,255,255,0.8) inset, 0px 0px 0px 1px rgba(255,255,255,0.25) inset; backdrop-filter: blur(8px) saturate(1.3)`

**Observed:** The blue scene remains visible through the lower body. The recommended card adds a blue wash from the top.

**Transfer:** Preserve transparency and edge light rather than replacing the material with opaque blue.

#### Sky scene · level 0

**Use:** Immersive commercial chapter backing.

**CSS:** `background-image: linear-gradient(#2a6fb5 0%, #7db0dd 52%, #dcecf7 100%); border-radius: 16px`

**Observed:** Soft photographic clouds float across a deep blue sky, fading toward the pale canvas at the bottom.

**Transfer:** Layer a cloud texture or soft SVG cloud field over this backing; keep card text on bright interiors.

#### Marker sentence · level 2

**Use:** A single emphasized fragment in document prose.

**CSS:** `background-color: rgba(254,234,61,0.35); color: #000000; border-radius: 2px; padding: 1px 2px`

#### Dark offer window · level 1

**Only for:** special-offer panels

**Use:** A narrow personal offer underneath a commercial comparison.

**CSS:** `background-color: rgba(26,26,26,0.9); border-radius: 8px; padding: 0px 4px 4px; box-shadow: 0px 10px 24px 0px rgba(0,0,0,0.12)`

**Observed:** Traffic-light controls sit above a darker inner panel, with white mono title and half-white body copy.

**Transfer:** Use this as a short exception to the light canvas, with a direct contact action at the right.

## Components

### Desktop menu

**Use:** Persistent navigation across page types.

**CSS:** `position: sticky; top: 0px; height: 53px; padding: 0px 24px; background-color: #f5f5f5; border-bottom: 1px solid rgba(0,0,0,0.05); z-index: 200`

**Text style:** `navigation` — Inter 400 · 14px/1 · tracking -0.03em

**Observed:** A left-aligned product name and compact links balance a centered expressive symbol. Tiny system-status symbols, a time readout and a blue acquisition link sit on the right.

**Transfer:** Keep the menu visually like a computer menu bar rather than a floating rounded navigation island.

### Blue candy button

**Use:** Default primary conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; height: 40px; padding: 0px 20px 1px 16px; border: 1px solid #221898; border-radius: 9999px; color: #000000; background-image: linear-gradient(#edf4ff 0%, #d6e7ff 18%, #a2c7ff 50%, #99cbf8 80%, #a2d2f7 100%); box-shadow: 0px 10px 24px 0px rgba(0,0,0,0.12); transition: transform 0.12s, opacity 0.15s`

**Text style:** `button` — Inter 500 · 18px/1.5 · tracking -0.03em

**Observed:** An optional platform icon precedes the label. A narrow inset white gloss hugs the upper edge, with a darker reflected foot and white text relief; text-only plan actions use balanced side padding.

**States:** Declared: hover opacity 0.8; active transform scale(0.97).

**Transfer:** Use one emphasized blue action per local decision group. Build the gloss with an absolutely positioned rounded strip inset 4px from the top and 12px from the sides, about 12px high, fading white to transparent.

### Silver candy button

**Use:** Alternative platform or secondary conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; height: 40px; padding: 0px 20px 1px 16px; border: 1px solid #626262; border-radius: 9999px; color: #000000; background-image: linear-gradient(#fbfbfb 0%, #ededed 42%, #e4e4e4 100%); box-shadow: 0px 10px 24px 0px rgba(0,0,0,0.12); transition: transform 0.12s, opacity 0.15s`

**Text style:** `button` — Inter 500 · 18px/1.5 · tracking -0.03em

**Observed:** Shares the primary control's inset gloss and reflected foot. Text-only plan buttons use 20px padding on both sides.

**States:** Declared: hover opacity 0.8; active transform scale(0.97).

### Metal capsule label

**Use:** Compact chapter marker above a headline or document.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 28px; padding: 0px 12px 1px; border: 1px solid rgba(0,0,0,0.3); border-radius: 9999px; color: rgba(0,0,0,0.5); background-image: linear-gradient(#ffffff 0%, rgb(231,231,231) 42%, #fbfbfb 100%)`

**Text style:** `eyebrow` — Inter 500 · 12px/1.5 · tracking -0.03em · uppercase

**Observed:** A small centered capsule remains much quieter than the main title.

### Application media window

**Use:** Feature demonstration object.

**CSS:** `width: 688px; padding: 8px 4px 4px; border: 0.5px solid #000000; border-radius: 8px; background-image: linear-gradient(90deg, #d6d5d7, #f0f0f0 50%, #d6d5d7); filter: drop-shadow(0px 10px 12px rgba(0,0,0,0.12))`

**Text style:** `caption` — Inter 400 · 12px/1.5 · tracking -0.03em

**Observed:** Tiny red, yellow and green traffic lights sit at the upper left with a muted centered application title. The large demonstration variant nests inside a white 706px by 474px outer frame with 8px padding and 16px corners; smaller hero windows float freely.

**Transfer:** Use real workflows in the window, with a filename caption outside when it is a loose hero asset.

### Feedback window

**Use:** Compact third-party social proof.

**CSS:** `width: 353px; background-color: #ffffff; border-radius: 8px; box-shadow: 0px 4px 12px 0px rgba(0,0,0,0.08); overflow: clip`

**Text style:** `body` — Inter 400 · 16px/1.5 · tracking -0.03em

**Observed:** A softly colored 32px title bar with traffic lights tops a white post body: portrait and identity, quote, then faint time and engagement metadata. Window heights vary with content; the bottom of the wall fades away.

**Transfer:** Keep actual attributable proof and the window framing; do not turn every quote into a giant centered testimonial.

### Question row

**Use:** Objection handling.

**CSS:** `background-color: #ffffff; border-radius: 8px; padding: 20px; max-width: 834px`

**Text style:** `question` — Inter 500 · 20px/1 · tracking -0.03em

**Observed:** Question aligned left, 20px plus aligned right with a 16px separation from text. The open row replaces the plus with a close mark and shows body copy after 8px, limited to 480px wide.

### Footer link

**Use:** Navigation within the four-column ending.

**CSS:** `color: rgba(0,0,0,0.6); transition: transform 0.12s`

**Text style:** `body` — Inter 400 · 16px/1.5 · tracking -0.03em

**Observed:** Simple unboxed text stacks beneath darker column headings with a 12px gap.

**States:** Declared: hover color #000000; active transform scale(0.97).

### Plan window

**Only for:** pricing comparisons

**Use:** Comparable offers on the sky scene.

**CSS:** `width: 350px; padding: 8px 4px 4px; border-radius: 8px; background-image: linear-gradient(rgba(255,255,255,0.3) 0%, rgba(231,231,231,0.3) 42%, rgba(251,251,251,0.3) 100%); backdrop-filter: blur(8px) saturate(1.3); box-shadow: 0px 10px 24px 0px rgba(0,0,0,0.12), 0px 1px 1px 0px rgba(255,255,255,0.8) inset, 0px 0px 0px 1px rgba(255,255,255,0.25) inset`

**Text style:** `plan-title` — Inter 500 · 28px/1 · tracking -0.03em

**Observed:** Traffic-light bar, centered tier name, benefit sentence, small audience note, dotted separator, large price, billing note, candy action, then left-aligned checked inclusions. White interior fades transparent downward. The middle recommendation has a blue title-bar wash and a small floating popularity pill.

**Transfer:** Keep aligned decision zones and equal widths while changing the number and substance of offers.

### Billing selector

**Only for:** pricing comparisons

**Use:** Two billing-period choices above the plan windows.

**CSS:** `display: flex; align-items: center; width: 252px; height: 48px; padding: 4px; border-radius: 24px; background-image: linear-gradient(rgba(255,255,255,0.3) 0%, rgba(231,231,231,0.3) 42%, rgba(251,251,251,0.3) 100%); backdrop-filter: blur(8px) saturate(1.3); box-shadow: 0px 10px 24px 0px rgba(0,0,0,0.12), 0px 1px 1px 0px rgba(255,255,255,0.8) inset, 0px 0px 0px 1px rgba(255,255,255,0.25) inset`

**Text style:** `button` — Inter 500 · 18px/1.5 · tracking -0.03em

**Observed:** The selected period is a raised silver pill with black text; the other period and small savings lozenge remain white on transparent glass.

## Imagery and graphics

### Desktop collage

**Use:** Signature first-screen environment.

**Observed:** Candid demonstration videos in silver windows of mixed portrait and landscape proportions surround the central copy. Small folders, old-device cutouts, emoticons, name-tag stickers and low-resolution internet ephemera fill selected gaps. The composition is asymmetrical but the message has a protected empty center.

**Transfer:** Use original product clips, people using the product and a few relevant digital keepsakes. Without video, use still workflow images in the same mixed-aspect window frames; the desktop collage still needs to be present.

**Build:** Place a central text group over Dotted desktop. Position four to six framed media objects around its perimeter, approximately 120px–250px wide, with filename captions below. Add a few 30px–80px isolated SVG folders or device cutouts, rotated slightly in either direction; let some approach the stage edge without covering actions.

### Folder wave

**Use:** Signature sculptural interruption behind a document.

**Observed:** Rows of beveled folder shapes sweep in two broad sine-like arches behind a white note window, changing from violet and pink through green and yellow. The wave stretches beyond both edges and fades into the page near its ends; small stickers float in front.

**Transfer:** Repeat a simple original product-related object along a curved path. The minimum version is a layered SVG ribbon of shaded folder-like shapes, not an unrelated flat gradient blob.

**Build:** Define one SVG folder with a small raised tab, rounded rectangular front, bright top bevel and dark lower edge. Repeat it at 24px–40px horizontal intervals along two broad curved paths in a 1440px-wide field; overlap successive instances. Hue-shift the instances across the spectrum, apply a subtle 1px dark edge, and mask the outer 150px into transparent. Put the document above the wave.

### Cloud sky

**Use:** Atmospheric commercial backdrop.

**Observed:** A blue sky with recognizable soft white cloud masses fills the section behind transparent window cards. The blue becomes paler toward the lower edge rather than ending as a hard rectangle.

**Transfer:** Use a daylight cloud image or render broad soft cloud clusters. Avoid neon space or dark cinematic lighting.

**Build:** Use Sky scene as the base. Overlay an SVG with irregular overlapping white ellipses in several clusters, varying alpha between 0.2 and 0.65 and applying 8px–20px Gaussian blur. Keep open blue gaps behind the title and fade the lower layer into the page canvas.

### Object-built closing word

**Use:** Signature monumental ending on every page type.

**Observed:** A broad lowercase word sculpture assembled from many glossy cyan desktop folders spans roughly 1139px by 297px below footer links. Small standalone desktop objects flank it. The tiny centered copyright is beneath, with no additional sales banner.

**Transfer:** Spell the new product's short name or a short brand-relevant word using repeated original digital objects. Keep this sculptural ending even when no custom 3D art is available; an SVG object mosaic is the minimum version.

**Build:** Lay out a coarse lowercase letter skeleton as a grid. Stamp an original cyan folder SVG along the strokes, overlapping tabs and fronts slightly. Give each folder a pale upper bevel, cyan-to-blue vertical face gradient, darker tab, 1px translucent outline and a soft 1px–2px shadow. Vary stacking order modestly while keeping letters readable; center the group across about four fifths of the page.

### Candid workplace scene

**Only for:** recruitment pages

**Use:** Large people-led opening media.

**Observed:** A warm, sunlit working studio with brick, wood, plants, real monitors and people mid-task fills a nearly full-width rounded photograph. A glossy dark translucent action floats over its center.

**Transfer:** Show an actual workspace with active people and natural light, retaining imperfect lived-in details rather than staged corporate portraiture.

### Icons

**Observed:** Tiny system-status icons sit in the menu; platform icons precede CTA text. FAQ plus signs are black, 20px, with 1.6px rounded strokes. Repeated traffic-light dots are more important to the material language than a broad feature-icon library.

**Transfer:** Choose compact familiar desktop metaphors, keep ordinary strokes rounded and black, and reserve multicolor marks for platform identity or decorative objects.

## Section recipes

How recurring sections are built.

### First screen: Desktop collage opening

**Observed:** A 53px Desktop menu caps a pale dotted stage. Behind the foreground media is Dotted desktop, then scattered tiny digital objects and emoticons, then floating silver video windows, then a clear centered text-and-action group. The 88px display headline is a short lowercase product name, about a quarter of the viewport width; a single 20px support line sits 8px beneath it. Two candy actions sit side by side 32px below the copy group, 16px apart, each with a 12px muted compatibility caption after 8px. Loose media surrounds rather than replaces this center. An 800px by 440px main video begins below the action group and is already substantially visible within the first 900px; its bottom and subsequent demonstration chapter fall below the fold.

**Transfer:** Center a short product name or compact promise with the same hierarchy and protected readability. Surround it with original workflow stills when clips are unavailable, and put the main demonstration beneath the actions. Secondary people-led pages simplify to a capsule, 56px title, centered short paragraph and wide workplace image rather than the orbiting collage.

**Avoid:** Do not use a split hero with one polished dashboard on the right, or allow stickers to overlap the headline and conversion controls.

**Text style:** `display` — Inter 500 · 88px/1.1 · tracking -0.03em

### Conversational demonstration row

**Observed:** A 1090px-wide row pairs a narrow copy rail with Application media window across a 64px gap. The copy rail contains a small waveform, blue user speech bubble and warm reply bubble, then an underlined short benefit and muted 16px explanation. Successive rows alternate orientation, with 48px between rows and 128px chapter padding.

**Transfer:** Turn a product capability into a plain-language request and result. Give the real workflow more area than the explanatory prose.

### Note amid object sculpture

**Observed:** A Metal capsule label sits above a centered 480px-wide note window. A tinted metallic title bar tops a white document with 20px by 24px padding, 20px/1.5 lowercase prose, one Marker sentence, and a small personal signoff. Folder wave runs behind the note, with sparse foreground stickers.

**Transfer:** Use this device for an opinion, origin story or product philosophy, with a real human signoff when appropriate.

**Text style:** `lead` — Inter 400 · 20px/1.5 · tracking -0.03em

### Desktop proof wall

**Observed:** A small label precedes a 56px repeated headline band: the central statement is black, flanking repeats gray and clipped at the page edges. Beneath it sit three 353px columns of Feedback window with 16px gutters. The lower wall fades to the canvas; a narrow glass strip carries aggregate proof and a blue inline invitation.

**Transfer:** Use attributable proof in a visibly varied stack. The repeated phrase can change to a succinct outcome; motion is not needed to preserve its graphic effect.

**Text style:** `heading` — Inter 500 · 56px/1.2 · tracking -0.03em

### Sky-backed decision scene

**Observed:** A centered white 56px heading and short supporting sentence lead into Billing selector and three Plan window cards. Sky scene and Cloud sky back the whole chapter; the middle option gets blue emphasis, the others silver. A Dark offer window sits below the comparison as a narrow contrasting addendum.

**Transfer:** Use the immersive sky scene for a commercial or high-conviction decision moment, keeping information in window interiors. Offer panels are only needed for a genuine exception.

**Text style:** `heading` — Inter 500 · 56px/1.2 · tracking -0.03em

### Plain-language questions

**Observed:** A centered 56px heading and 20px support line lead to an 834px-wide stack of Question row, separated by 8px. The first answer is open. A small decorative picture sits outside the answer column rather than behind the text.

**Transfer:** Use the reader's actual doubts as questions and answer each directly without marketing preamble.

**Text style:** `heading` — Inter 500 · 56px/1.2 · tracking -0.03em

### Object-sculpture ending

**Observed:** The canvas continues into a four-column footer across 1090px, with plain 16px links and a short assurance in the final column. Object-built closing word sits below these columns, with small standalone desktop objects at the edges and tiny centered copyright at the very bottom. The same ending serves both expansive marketing and shorter recruitment layouts.

**Transfer:** Close with useful navigation and a memorable object-built brand word, not another generic conversion card.

### Open invitation listing

**Only for:** recruitment pages

**Observed:** After the large workplace image, a centered silver-gray application panel contains a 56px invitation heading, short support line and vertical opportunity rows. Each row has a dark title, muted description and compact metadata on the left, with a blue candy contact action on the right. Fine dotted rules divide entries; the final entry invites an unlisted proposal.

**Transfer:** Use the window-list construction for roles or participation opportunities. Keep direct personal contact instead of a dense enterprise application table.

**Text style:** `heading` — Inter 500 · 56px/1.2 · tracking -0.03em

## Page flow

**Storyline:** friendly promise → tangible experience → human conviction and proof → practical decision → reassurance → playful brand-memory ending

### Product marketing and acquisition

1. **Promise** — Protected central name and plain category line inside an expressive desktop collage, followed by dual download actions.
2. **Product demonstration** — Alternating conversational requests paired with large workflow windows.
3. **Point of view** — A personal note backed by a colorful repeated-object wave.
4. **Social proof** — Repeating outcome phrase and a masonry-like wall of small social windows.
5. **Commercial decision** — A cloud-sky scene containing transparent plan windows and a contrasting offer addendum.
6. **Objection handling** — Plain question rows with a first answer expanded.
7. **Brand-memory ending** — Four useful footer columns above a huge cyan object-built word.

**Transfer:** Use as a narrative toolkit, preserving the desktop collage, tactile control language and sculptural ending while choosing only the chapters the new product needs.

### Recruitment and personal outreach

1. **Invitation** — Small capsule, centered lowercase heading and personal paragraph.
2. **Human context** — Nearly full-width warm workplace photograph with an overlaid action.
3. **Opportunity and action** — A desktop-style list of opportunities, each with a direct outreach button, ending in an open-ended invitation.
4. **Brand-memory ending** — Shared four-column navigation and cyan folder-word sculpture.

**Transfer:** Use the simpler people-led opening and list panel for participation pages while retaining the shared menu, glossy controls and ending.

## Writing

Warm, informal and openly enthusiastic, like a maker showing a friend something useful on their computer. Specific everyday actions carry the promise; personal asides make the product feel approachable rather than institutional.

**Do not copy:** Do not reuse the brand name, mascot, founder identity, signatures, customer identities or quotes, product-specific claims, audience totals, pricing, discounts, compatibility requirements or privacy assurances. Replace all with truthful material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you'; use 'we' for the people making the product. The product can be described as a helpful companion, not an omniscient platform.
- **Rhythm:** Short lowercase headlines, one-sentence support lines and verb-led actions. Longer personal notes can use contractions, casual asides and occasional exclamation marks; questions stay plain and specific.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero name | Let a short lowercase product name carry the headline; put the category promise below. | 1–3 words | “[Brand]” |
| Supporting line | Explain what it is using a familiar metaphor and everyday location. | 7–12 words | “an ai buddy that lives on your computer” |
| Capability | Use a short outcome phrase, not a technical category. | 3–7 words | “finally do the thing”<br>“spawn agents with your voice” |
| Action | Plain lowercase verb plus destination, plan or invitation. | 2–4 words | “start free”<br>“reach out to us” |
| Question | State the reader's actual concern in their own voice. | 4–12 words | “is my data private?”<br>“do i need a mac?” |
| Commercial reassurance | A compact sentence lowers commitment anxiety. | 5–9 words | “three simple plans, cancel anytime.” |

**Words and phrasing to use:** your way; try it; buddy; reach out; the thing; we believe; come build

**Avoid:** enterprise-grade transformation; revolutionary ecosystem; unlock unparalleled synergy; best-in-class platform; leverage

**Rules:**

- Use lowercase in marketing copy while preserving meaningful proper names where required.
- Name a concrete action or experience before describing technology.
- Keep personal notes genuinely personal; allow a small informal aside rather than polishing every line into a slogan.
- Use tiny filenames and practical captions as part of the desktop-world storytelling.

## Do's and Don'ts

### Do

- Keep core headings at weight 500 with -0.03em tracking.
- Protect the centered 88px hero name with a clear area inside the media collage.
- Use 40px glossy pills with dark 1px outlines and inset highlights.
- Keep 16px gutters between proof cards and 64px between demonstration text and media.
- Use gray text through black alpha on the pale canvas, with solid black for the hierarchy.
- Keep the cloud-backed comparison as a distinct immersive scene against an otherwise pale page.
- Give each page a broad object-built word sculpture below its useful footer links.
- Use 8px corners on small windows and 16px on larger outer media frames.

### Don't

- Do not replace the candy controls with flat solid-blue rectangles.
- Do not set ordinary display text in weight 800; that heavy cut is a limited top-tier plan accent.
- Do not turn the main canvas black just because a narrow offer panel is dark.
- Do not put the rainbow treatment on ordinary body text or navigation.
- Do not give every card 24px or 32px corners; compact desktop windows use 8px.
- Do not replace the filename captions with oversized editorial captions.
- Do not spread mono through ordinary headings; it belongs to special-offer panels.
- Do not arrange every demonstration into equal square tiles; the media should outweigh its narrow conversational rail.

## Motion and responsive

### Motion

**Observed:**

- Candy actions declare transform 0.12s and opacity 0.15s, with hover opacity 0.8 and active scale(0.97).
- The expressive menu symbol declares a 7s ease infinite squish animation.
- Opening elements declare staggered 0.45s ease-out entrances; some later reveal elements use transform 0.62s cubic-bezier(0.2,0.9,0.25,1) with opacity 0.5s.

**Transfer:**

- Use the short press response on tactile controls and retain a lightly animated desktop-object character rather than moving the whole page continuously.
- The repeated headline remains legible as a static clipped band; do not infer a continuously scrolling ticker.

**Unknown:**

- Exact playback, trigger positions and complete reveal choreography are not established.

### Responsive

**Observed:**

- Styles define width breakpoints at 640px, 768px, 1023px, 1024px, 1280px, 1440px and 1536px.

**Transfer:**

- On narrower layouts, preserve the protected center of the desktop collage and reduce peripheral objects before reducing action legibility.
- Stack demonstration text and media, then plan windows and footer columns as needed; retain their materials and hierarchy. These are adaptation recommendations.

**Unknown:**

- Narrow-screen composition, exact responsive font sizes and menu-collapse behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
