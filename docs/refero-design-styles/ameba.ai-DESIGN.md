# Ameba — operations in orbit

## Overview

A composed, technical style for products that turn complex work into dependable systems. Midnight blue bookends a spacious white middle, with electric blue actions, cyan signals and pale lavender proof areas. Regular-weight sans-serif headlines, practical grotesk body copy and tiny monospaced labels accompany a luminous particle sphere, framed interface vignettes and grounded customer photography. The density is low around the message and deliberately higher inside the demonstrations.

### Essentials

- An operational promise floats inside a data object: a centered two-line 53.6px regular headline sits over a dim blue particle sphere on a 900px midnight stage, with a small live-status pill above it.
- Headlines sound human while labels sound machine-readable: the heading sans at weight 400 with -0.008em tracking in the opening; IBM Plex Mono labels at 13px/1.5, weight 500, uppercase and 0.07em tracking.
- Conversion is a solid blue rectangle, not another capsule: primary buttons are 48px high with 8px corners and 12px 32px padding; capsules belong to status and process controls.
- Color is concentrated rather than spread evenly: white carries the long capability narrative, midnight carries the opening and trust/closing bands, and saturated blue/cyan is reserved for actions, signals, fine patterns and contained media backdrops.
- Product evidence is staged like a small instrument: 484px square, 16px-corner atmospheric mounts contain floating white interface panels; a 160px side rail guides tall 765px capability chapters.
- Data texture is a recurring signature: tiny sphere tiles in the opening and fading 14px-grid dots on proof and closing surfaces. Recreate these abstract devices even when no proprietary product artwork exists.
- Proof has a human counterweight: a midnight quotation card with a cyan 30px result faces an equal-width customer film on a lavender band, followed by a restrained centered call to action.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0428cb` | `--color-blue` | action, link, accent | Primary actions, mono labels, patterned dots and active progress states. |
| Deep blue glow | `#06105a` | `--color-hero-glow` | background | Subtle radial depth behind the opening data sphere. |
| Midnight | `#00052e` | `--color-midnight` | text, background, surface | Default dark canvas and primary text on white. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal cyan | `#34fcff` | `--color-cyan` | text, accent | Short highlighted proof numbers, security eyebrow and tiny event signals. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Midnight glass | `#0d1238` | `--color-dark-glass` | surface | Visible result of white at 5% on midnight for status pills and the metric strip. |
| Reverse hairline | `#262b4d` | `--color-dark-edge` | border | Visible result of white at 15% on midnight for pills and horizontal separators. |
| Slate body | `#4f5166` | `--color-body` | text | Long feature descriptions on white. |
| Muted slate | `#6b6b83` | `--color-muted` | text | Footer links, FAQ support and secondary descriptions. |
| Soft reverse text | `#b3b4c0` | `--color-dark-support` | text | Visible result of white at 70% on midnight for long reverse paragraphs; use white at 80–90% for opening support. |
| Lavender rule | `#e9e9f3` | `--color-rule` | border | FAQ separators, footer rule and media outlines; 60% alpha for translucent chips. |
| Lavender mist | `#efeff7` | `--color-lavender` | background, surface | Customer proof band and media backing. |
| White | `#ffffff` | `--color-white` | background, surface, text | Long-form capability canvas, floating panels and headline text on midnight. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Attention amber | `#f5a524` | `--color-amber` | accent | Tiny warning dots in the event ribbon, not marketing backgrounds. |
| Live mint | `#adffce` | `--color-mint` | accent | Small live-status indicator only. |

## Typography

- **Inter** — Headlines, quotations and proof numerals. Open, softly geometric sans with round forms and an unforced regular weight. If unavailable, use **DM Sans**. Alternative display substitute; use weight 400 and retain the loose line heights and gently negative tracking. Font stack: "Inter", "DM Sans", Inter, sans-serif.
- **Open Sauce Sans** — Body paragraphs, buttons and navigation support. Practical, even-width grotesk with a generous x-height. If unavailable, use **Inter**. Use weights 400 and 500. Font stack: "Open Sauce Sans", Inter, sans-serif.
- **IBM Plex Mono** — Navigation, eyebrows, status labels and metric captions. Compact technical monospace, spaced uppercase at weight 500. Font stack: "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| heading-xl | Inter | 400 | 54px | 1.3 | -0.008em | size clamp(2.25rem, 4.5vw, 3.375rem) | Centered problem statement immediately beyond the first screen. |
| display | Inter | 400 | 53.6px | 1.35 | -0.008em | fixed | Two-line centered opening promise. |
| heading-lg | Inter | 400 | 40px | 1.25 | -0.006em | size clamp(1.75rem, 3.5vw, 2.5rem) | Capability chapter titles and closing invitation. |
| heading | Inter | 400 | 33px | 1.3 | -0.006em | size clamp(1.5rem, 2.3vw, 2.0625rem) | Process introduction, FAQ title and trust heading. |
| stat | Inter | 400 | 30px | 1.2 | normal | fixed | Compact operational metrics and the cyan customer result. |
| quote | Inter | 400 | 27px | 1.35 | -0.004em | size clamp(1.25rem, 1.9vw, 1.6875rem) | Customer quotation in the dark proof card. |
| body-lg | Open Sauce Sans | 400 | 18px | 1.625 | normal | fixed | Capability descriptions and centered trust explanation. |
| body | Open Sauce Sans | 400 | 16px | 1.5 | normal | fixed | Opening and closing support, FAQ introduction. |
| action | Open Sauce Sans | 500 | 16px | 1.5 | normal | fixed | Primary buttons, FAQ question labels and customer names. |
| small | Open Sauce Sans | 400 | 14px | 20px | normal | fixed | Event chips, footer links and attribution support. |
| small-action | Open Sauce Sans | 500 | 14px | 20px | normal | fixed | Compact navigation button and film title. |
| eyebrow | IBM Plex Mono | 500 | 13px | 1.5 | 0.07em, uppercase | fixed | Section markers, navigation and footer column headings. |
| chapter-label | IBM Plex Mono | 500 | 12px | 16px | 0.07em, uppercase | fixed | Small setup or continuous-operation labels above chapter titles. |
| status | IBM Plex Mono | 500 | 11.2px | 1.5 | 0.07em, uppercase | fixed | Live-status capsule above the opening headline. |
| metric-caption | IBM Plex Mono | 500 | 10.4px | 1.5 | 0.07em, uppercase | fixed | Tiny labels under the metric strip numerals. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display text remains regular, not bold. Tracking eases from -0.008em at the largest sizes to -0.004em in quotations; labels use positive 0.07em tracking.
- Use 18px descriptions for explanatory chapters but 16px support for the opening so the particle object remains dominant.
- Keep interface typography subordinate inside media; do not promote the miniature UI text into the marketing scale.

## Layout

**Density:** Airy around narrative blocks, compact inside proof and product demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Inline icon gaps and tight label spacing. |
| 12px | Chapter eyebrow-to-title spacing and ribbon chip gaps. |
| 16px | Capability title-to-description spacing and standard label spacing. |
| 24px | Opening heading-to-support spacing and standard mobile-side inset guidance. |
| 32px | Desktop container inset and paired proof-card gap. |
| 40px | Opening support-to-action gap and space between side rail and chapter content. |
| 48px | Feature column gap and quotation-card padding. |
| 64px | FAQ column gap and footer top padding. |
| 80px | Vertical padding of the dark trust band. |
| 96px | Proof, FAQ and closing-band vertical padding. |
| 128px | Deep section breathing room around the long capability narrative. |

### Containers and grids

- **main-container**: max width 1280px · side padding 32px. Centered desktop wrapper; 1216px usable width at a 1440px window. Navigation uses 24px inner side padding.
- **opening-copy**: max width 780px · side padding 24px. Centered promise stack; support paragraph is constrained further to 520px.
- **centered-explanation**: max width 768px. Problem and trust text read as compact centered blocks.
- **chapter-shell**: 2 columns · gap 40px. A 160px progress rail beside the remaining 1016px narrative area.
- **capability-pair**: 2 columns · gap 48px. Equal 484px columns: text left, square visual right, centered vertically in a 765px chapter.
- **proof-pair**: 2 columns · gap 32px. Equal 592px quote and customer-film columns.
- **faq-pair**: 2 columns · gap 64px. Introductory title and contact left; 576px-wide question stack right.
- **footer-grid**: 5 columns · gap 32px. Company identity spans the first two tracks; three link groups fill the rest.

## Corner radius

| Element | Radius |
| --- | --- |
| primary-buttons | 8px |
| media-and-proof | 16px |
| capsules | 9999px (pill) |
| status-dot | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| media-mount | `0px 0px 0px 1px #e9e9f3, 0px 25px 50px -12px rgba(0,0,0,0.25)` | Square atmospheric media mounts on white. |
| floating-panel | `0px 2px 8px rgba(5,12,48,0.14), 0px 26px 55px -18px rgba(5,12,48,0.42)` | White interface panels inside product vignettes. |
| chip | `0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)` | Translucent event chips. |

### Surfaces

#### White canvas · level 0

**Use:** Long explanatory narrative and footer.

**CSS:** `background: #ffffff; color: #00052e`

#### Midnight stage · level 0

**Use:** Opening promise.

**CSS:** `background: radial-gradient(closest-side, #06105a 0%, #00052e 85%); color: #ffffff`

**Observed:** The glow stays dim; it gives depth without making the center a bright spotlight.

**Transfer:** Keep the glow behind, not on top of, the data object.

#### Midnight band · level 0

**Use:** Problem, explainer, quantified proof, trust and closing areas.

**CSS:** `background: #00052e; color: #ffffff`

#### Lavender proof band · level 0

**Use:** Customer evidence.

**CSS:** `background: #efeff7; padding: 96px 0px`

#### Atmospheric mount · level 1

**Use:** Square product demonstration framing.

**CSS:** `background: #efeff7; border-radius: 16px; overflow: hidden; box-shadow: 0px 0px 0px 1px #e9e9f3, 0px 25px 50px -12px rgba(0,0,0,0.25)`

**Observed:** The visible face is a dark softly lit color field, not a flat lavender tile. Slate/teal, indigo, forest green and burgundy distinguish adjacent demonstrations; a white panel floats above each.

**Transfer:** Choose one low-key color field per capability. Keep color inside the square rather than tinting the full section.

#### Reverse glass · level 1

**Use:** Status capsule and metric-band overlay.

**CSS:** `background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.15); backdrop-filter: blur(8px)`

#### Floating interface · level 2

**Use:** Product vignettes.

**CSS:** `background: #ffffff; border: 1px solid rgba(255,255,255,0.55); border-radius: 12.6px; box-shadow: 0px 2px 8px rgba(5,12,48,0.14), 0px 26px 55px -18px rgba(5,12,48,0.42)`

**Observed:** Panels occupy most of the mount while leaving a clearly visible colored perimeter.

**Transfer:** Show a short legible task or relationship, not a full dense application.

## Components

### Primary button

**Use:** Single main conversion action.

**CSS:** `background: #0428cb; color: #ffffff; border-radius: 8px; padding: 12px 32px; height: 48px; display: inline-flex; align-items: center`

**Text style:** `action` — Open Sauce Sans 500 · 16px/1.5

**Observed:** Text-only control centered beneath opening and closing copy. The compact header variant is 40px high with 10px 20px padding and the small-action recipe.

**States:** Declared: hover opacity 0.9; focus-visible not specified.

### Navigation

**Use:** Persistent orientation and conversion.

**CSS:** `height: 64px; display: flex; align-items: center; justify-content: space-between; padding: 0px 24px; max-width: 1280px`

**Text style:** `eyebrow` — IBM Plex Mono 500 · 13px/1.5 · tracking 0.07em · uppercase

**Observed:** Wordmark and widely spaced links sit left; locale, sign-in and a compact Primary button sit right. A 36px announcement strip sits above. Both are dark and reversed over the opening, changing to a translucent white shell with dark lettering as the content scrolls.

**States:** Declared: hover opacity 0.7 on navigation links; focus-visible not specified.

### Live status pill

**Use:** Compact operating proof above the promise.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; padding: 6px 16px; background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.15); border-radius: 9999px; backdrop-filter: blur(8px)`

**Text style:** `status` — IBM Plex Mono 500 · 11.2px/1.5 · tracking 0.07em · uppercase

**Observed:** An 8px mint dot leads the label. The pill is separated from the headline by 24px.

**Transfer:** Use an honest live or scale signal, with a short neutral status if no volume claim is available.

### Event chip

**Use:** Two-row ribbon of operational triggers.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; padding: 8px 16px; background: rgba(255,255,255,0.6); border: 1px solid rgba(233,233,243,0.6); border-radius: 9999px; backdrop-filter: blur(12px); box-shadow: 0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Text style:** `small` — Open Sauce Sans 400 · 14px/20px

**Observed:** Short event labels follow 6px cyan, blue or amber dots. Rows extend beyond their container and fade at both ends.

### Capability stage

**Use:** Contained visual proof beside each capability.

**CSS:** `width: 484px; height: 484px; position: relative; border-radius: 16px; overflow: hidden; box-shadow: 0px 0px 0px 1px #e9e9f3, 0px 25px 50px -12px rgba(0,0,0,0.25)`

**Observed:** A colored Atmospheric mount backs a floating white interface panel. Examples show connected nodes, a process checklist, a message thread and a drafted action.

**Transfer:** Use one concrete operation per stage, with enough context to understand input and output.

### Quote card

**Use:** Customer result in the proof pair.

**CSS:** `background: #00052e; border-radius: 16px; padding: 48px; display: flex; flex-direction: column; justify-content: space-between; position: relative; overflow: hidden`

**Text style:** `quote` — Inter 400 · 27px/1.35 · tracking -0.004em

**Observed:** Quote above, person and role below left, cyan result below right. A fading blue dot grid occupies the right three fifths behind the content.

### Metric strip

**Use:** A compact band of quantified operating proof.

**CSS:** `background: #00052e; border-top: 1px solid rgba(255,255,255,0.15); border-bottom: 1px solid rgba(255,255,255,0.15); padding: 40px 0px; display: flex; justify-content: center; gap: 48px`

**Text style:** `stat` — Inter 400 · 30px/1.2

**Observed:** White regular numerals sit above tiny metric-caption labels with 6px separation. A secondary press-logo row uses another fine top rule.

**Transfer:** Use a small set of real measures; keep labels concise and the visual emphasis on scale.

### FAQ row

**Use:** Low-friction objection handling.

**CSS:** `padding: 20px 0px; border-bottom: 1px solid #e9e9f3; color: #00052e`

**Text style:** `action` — Open Sauce Sans 500 · 16px/1.5

**Observed:** A full-width text button aligns its question left and a blue 20px plus icon right. Rows are about 65px tall and are not individual cards.

### Film link

**Use:** Customer film title beneath a wide portrait.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 12px 24px 12px 12px; background: #ffffff; border: 1px solid #e9e9f3; border-radius: 16px`

**Text style:** `small-action` — Open Sauce Sans 500 · 14px/20px

**Observed:** A 48px dark play tile leads the title; a smaller muted duration sits directly below it. The link is detached from the image by a narrow gap.

### Footer columns

**Use:** A matter-of-fact finish after the dark invitation.

**CSS:** `background: #ffffff; padding: 64px 0px 32px; color: #6b6b83`

**Text style:** `small` — Open Sauce Sans 400 · 14px/20px

**Observed:** Blue mono column headings above sparse link lists; identity, address and a small trust badge occupy a wider left block. A fine full-width rule separates the copyright and privacy row.

**States:** Declared: hover color #00052e on footer links; focus-visible not specified.

## Imagery and graphics

### Particle sphere

**Use:** Signature object behind the opening message.

**Observed:** A dim, vertically elongated sphere formed from hundreds of blue rectangular particles and occasional cyan tiles. Its center remains transparent enough for white type. It occupies the middle third to half of the width and extends above the badge and below the button; no solid globe silhouette or photographic texture.

**Transfer:** Represent the new product's many moving parts as a contained data field. The minimum version is a static SVG particle ellipsoid with front/back depth, not a generic gradient blob.

**Build:** In SVG or canvas distribute small rectangles across a projected ellipsoid about 600px wide and 620px high at desktop. Use electric-blue tiles with varied alpha, sparse cyan highlights, smaller/dimmer back-facing particles and subtle perspective skew near the edge. Place a broad deep-blue radial glow beneath it and HTML copy above it. Keep the central field dim and the outer silhouette soft; do not outline the sphere.

### Atmospheric product vignettes

**Use:** Capability proof, repeated within square mounts.

**Observed:** White task panels float in softly illuminated dark slate/teal, indigo, green and burgundy squares. The panel is near frontal, with a broad grounded shadow and around 34px of mount padding. Fine grain keeps the gradient from feeling like glossy 3D.

**Transfer:** Rebuild a small realistic process using native HTML or SVG. If a full interface is unavailable, show labeled nodes, three workflow rows or a short input-to-action thread on the same white panel.

**Build:** Fill a 484px square with a dark diagonal base gradient. Add one radial light pool at 26% 14% using a related midtone at 35–45% alpha, fading by 52%; add a weaker cool or warm highlight at 84% 92% at 8–10% alpha, fading by 55%. Overlay fine SVG fractal noise using soft-light at 0.4 opacity. Inset the white panel, round it to about 13px and apply the Floating interface shadow.

### Fading dot field

**Use:** Signature texture for the dark quotation and closing invitation.

**Observed:** Small electric-blue dots form a disciplined rectangular grid, strong at one edge and disappearing into midnight. Closing dots are much dimmer and clipped into opposite corners.

**Transfer:** Preserve this technical texture as a recurring device; keep it behind text and away from dense copy.

**Build:** Use radial-gradient(circle, #0428cb 1.6px, transparent 1.8px) with background-size 14px 14px. On the quote, cover the right 60% and mask from transparent at the left to opaque at 70%. For the closing band, clip separate fields into the upper-left and lower-right corners and reduce opacity.

### Customer film portrait

**Use:** Human proof beside the quotation.

**Observed:** A chest-up person centered in a wide 592px by 297px frame, looking toward camera. Natural skin tones and neutral clothing stand against a cool softly blurred working environment. The corners match the 16px card radius.

**Transfer:** Use a real user in their own context with soft light and shallow depth of field; retain the wide crop and quiet cool background.

### Explainer poster

**Use:** Large media bridge between the problem and the metrics.

**Observed:** A 960px by 548px rounded media frame shows an application dashboard within a saturated indigo/violet surround. A compact dark translucent play capsule carries a title and duration.

**Transfer:** Use an authentic demo poster with visible application content. Keep the frame narrower than the main container and let it anchor the dark section.

### Icons

**Observed:** Simple outline utility symbols, mainly 14px and 20px with 2px round strokes. FAQ plus signs are blue; status and progress indicators are tiny filled dots or squares. Play icons are compact white triangles in dark controls.

**Transfer:** Use a consistent outline set for actions and utilities. Reserve filled marks for state, play and the small progress cursor; avoid decorative pictograms beside every heading.

## Section recipes

How recurring sections are built.

### First screen: Orbital promise

**Observed:** A 900px midnight first screen layers radial glow, a centered particle ellipsoid, then an HTML promise stack. The fixed 36px announcement plus 64px navigation occupy the top. A status pill begins the stack around the upper third, followed by two balanced 53.6px/1.35 white headline lines inside a 780px wrapper. Support is 520px wide and 16px/24px, with 24px above it and 40px before one Primary button. The main object wraps the stack rather than sitting in a separate column. Badge, headline, support, action and the full visual are all visible within 900px; the next problem statement starts below the fold.

**Transfer:** Use two short complementary outcomes and an honest operating signal. Recreate the Particle sphere as abstract data art if product-specific media is unavailable. A focused product page can use the same stage with a more specific promise; keep the object behind the message.

**Avoid:** Do not replace the sphere with a giant screenshot beside left-aligned text, add a row of competing actions, or turn the regular white headline into bold gradient lettering.

**Text style:** `display` — Inter 400 · 53.6px/1.35 · tracking -0.008em

### Problem and benefit trio

**Observed:** On Midnight band, a centered heading-xl and broad support paragraph precede three left-aligned benefit columns. Each column begins with a fine reverse rule and a small blue mono number, followed by a short white title and muted one-line result. The columns use 32px gaps and about 304px width.

**Transfer:** Explain the cost of the problem in plain language, then give three distinct outcomes with concise proof.

### Process introduction and ribbon

**Observed:** An eyebrow and a 33px two-line heading align to the main container's left edge. A compact horizontal sequence of pill controls sits below, with one blue active step and outlined white steps joined by arrows. Two rows of Event chips follow, 40px lower, with softly masked ends.

**Transfer:** Use a short lifecycle relevant to the new product and populate the ribbon with realistic events rather than category keywords.

**Text style:** `heading` — Inter 400 · 33px/1.3 · tracking -0.006em

### Guided capability chapters

**Observed:** The chapter-shell holds a sticky vertical rail with a 2px track, cyan-to-blue progress fill and a small square blue cursor. In the content area, each capability-pair has a tiny chapter-label, heading-lg and body-lg left, Capability stage right. The repeated chapters share 765px height, so the copy remains brief and the interface object has room.

**Transfer:** Choose a few meaningful transitions in how the product works. Preserve the rail-plus-stage device while adapting chapter count and subjects.

**Text style:** `heading-lg` — Inter 400 · 40px/1.25 · tracking -0.006em

### Paired customer proof

**Observed:** Lavender proof band carries a Quote card and equally wide Customer film portrait with Film link. A Primary button is centered 48px below the pair. Attribution and cyan result sit at opposite lower corners of the dark quote.

**Transfer:** Pair a substantiated customer account with a person or working environment. Preserve the dark/light contrast and the short numeric proof treatment.

**Text style:** `quote` — Inter 400 · 27px/1.35 · tracking -0.004em

### Trust interlude

**Observed:** A centered midnight band uses 80px vertical padding, a cyan eyebrow, 33px heading and 18px explanatory paragraph in a roughly 720px measure. A modest white text link and small compliance marks finish the block.

**Transfer:** Address the buyer's real risk with specific verifiable assurances rather than a large decorative badge wall.

**Text style:** `heading` — Inter 400 · 33px/1.3 · tracking -0.006em

### Split FAQ

**Observed:** White canvas with 96px vertical padding. A two-line 33px heading on the left colors its concluding word blue, followed by short muted support and a contact link with Copy control. FAQ rows occupy the right half with 64px column separation.

**Transfer:** Use actual buying objections, keep questions compact and maintain a visibly simple contact fallback.

**Text style:** `heading` — Inter 400 · 33px/1.3 · tracking -0.006em

### Dotted closing invitation and footer

**Observed:** A 620px Midnight band closes the sales narrative with centered 40px white invitation, short 16px support and one Primary button. Dim dot fields enter opposite corners without framing the text. The next area switches sharply to White canvas: Footer columns occupy 465px with 64px top and 32px bottom padding, a broad identity block, three sparse link groups and a separate ruled legal row.

**Transfer:** Offer a concrete low-effort next step, then end on an administrative white footer rather than extending the dark hero treatment indefinitely.

**Text style:** `heading-lg` — Inter 400 · 40px/1.25 · tracking -0.006em

## Page flow

**Storyline:** outcome promise → problem and benefits → product demonstration → operating proof → guided capabilities → human proof → trust and objections → concrete invitation → administrative finish

### A product-led marketing landing page that makes an unfamiliar service feel operational and trustworthy

1. **Promise** — A paired outcome headline inside a data sphere with a live-status capsule and one action.
2. **Problem framing** — Centered explanation and a numbered trio connect increased demand to everyday friction and measurable benefits.
3. **Product demonstration** — A wide explainer poster shows the application before a short strip of scale metrics and press marks.
4. **Capability chapters** — A process summary and event ribbon lead into tall text/interface pairs navigated by a progress rail.
5. **Social proof** — A dark quote and cyan result face a real customer film on a lavender band.
6. **Risk reduction** — A compact dark trust statement is followed by a split white FAQ.
7. **Closing call** — A centered practical invitation rests on midnight with fading corner dots; a sparse white footer provides final navigation.

**Transfer:** Adapt the narrative to the buyer's uncertainty rather than preserving a fixed number of sections. Keep the sphere, guided product evidence, dotted proof texture and contrasting administrative finish as recognizable devices.

## Writing

Calm, practical and unusually explicit about what the product does. Technical credibility comes from familiar work, concrete conditions and accountable outcomes rather than futurist language.

**Do not copy:** Do not reuse the Ameba name, wordmark, proprietary interface artwork, customer identities, quotations, funding details, numerical performance claims or compliance claims. Source examples illustrate the voice only.

- **Addressing the reader:** Talk directly to 'you' and 'your team'. Describe the product as an active helper using straightforward verbs; use 'we' when making an invitation or taking responsibility.
- **Rhythm:** Short outcome headlines are paired with fuller explanatory paragraphs. Repetition builds momentum; fragments and contractions make operational detail conversational. Exclamation marks are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Two parallel outcome sentences, each starting with a verb. | 3–5 words per line | “Win more orders.”<br>“Deliver more on time.” |
| Capability title | A short instruction or a direct statement of what the system does. | 4–6 words | “Give them your tools”<br>“They watch every order” |
| Support | Describe inputs, behavior and the user's control using familiar nouns. | 2–4 sentences | “Teach your AI workforce your processes once, in simple language: what they should look out for, what they should do, and when they should involve you.” |
| Primary action | A plain verb plus a specific next step. | 3–4 words | “Book a demo” |
| Closing invitation | Make the product tangible using the reader's own work. | 6–9 words | “See it run on your own orders.” |
| Reassurance | Negate specific setup burdens with clipped parallel clauses. | 6–10 words | “Nothing to migrate, nothing to learn.” |

**Words and phrasing to use:** your team; the way you taught them; once; every; already use; when to involve you; on your own; nothing to learn

**Avoid:** revolutionary; limitless; supercharge; game-changing; magical; unleash the future

**Rules:**

- Make each headline a business outcome or an observable action.
- Explain what happens automatically and what remains under the user's control.
- Put quantified claims next to their relevant evidence, not into every headline.
- End with a bounded, concrete demonstration instead of a vague invitation to transform.

## Do's and Don'ts

### Do

- Keep the main headline at regular weight and -0.008em tracking.
- Use the 1280px wrapper with 32px desktop insets for the long white narrative.
- Retain 48px-high blue primary buttons with 8px corners.
- Stage capability art in 484px square mounts rather than loose screenshots.
- Use 13px uppercase mono labels with 0.07em tracking as the technical counterpoint.
- Let chapter descriptions breathe at 18px/1.625 with 16px below the title.
- Include the fading 14px dot grid on a dark proof or closing surface.
- Give the footer a clear white reset with sparse columns and a separate legal rule.

### Don't

- Do not make conversion buttons fully pill-shaped; that silhouette belongs to state chips.
- Do not use cyan for large background fills; it is a signal and proof accent.
- Do not turn every feature into a lavender card grid; the narrative uses open white space.
- Do not set major headings at 700 weight or compress their line heights into a poster-like stack.
- Do not use a solid globe outline or a bright neon halo around the particle sphere.
- Do not tint whole capability sections green or burgundy; those colors stay inside media mounts.
- Do not put oversized percentage numerals behind the quotation; its result is a compact 30px corner detail.
- Do not enlarge mono labels into major headlines or use mono for explanatory body paragraphs.

## Motion and responsive

### Motion

**Observed:**

- Primary buttons declare opacity transitions of .15s cubic-bezier(.4, 0, .2, 1) with hover opacity 0.9.
- Opening text declares a 0.5s fade-up animation using cubic-bezier(0.22, 1, 0.36, 1).
- Product scenes declare node entry, check entry, message entry and status pulses; the event ribbon uses horizontally translated rows and a reduced-motion class.
- The fixed header changes from reverse-on-dark to a translucent light treatment over the scrolled page.

**Transfer:**

- Use motion to reveal operational state: connected nodes, completed checks, incoming messages and progress-rail position.
- Keep the particle object subordinate to the stationary readable promise; preserve a static ellipsoid and ribbon fallback when motion is reduced.

**Unknown:**

- Particle simulation speed and easing, scroll activation thresholds, and the full reduced-motion behavior are not established.

### Responsive

**Observed:**

- Fluid heading clamps exist for 54px, 40px, 33px and 27px roles.
- Class declarations distinguish desktop sticky chapters from a separate smaller-screen presentation; navigation and sign-in are hidden at narrower layouts.
- Container classes specify 24px side padding before the desktop 32px inset.

**Transfer:**

- On narrow screens, preserve the centered orbital promise and scale the data object behind it rather than moving it alongside the copy.
- Replace the vertical rail with a compact process indicator and stack each description above its square stage; retain the white/dark section contrast.
- Stack quote and portrait without losing their shared proof grouping.

**Unknown:**

- Exact breakpoint widths, mobile menu composition and the smaller-screen chapter interaction are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
