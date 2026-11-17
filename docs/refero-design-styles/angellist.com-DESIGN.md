# AngelList — lavender over deep teal

## Overview

An institutional but approachable style for complex software and service businesses. Deep green-black openings and pale stone chapters are punctuated by lavender, with regular-weight sans display typography and restrained grotesk body text. Product interfaces, sculptural symbols and intimate portraiture sit in clean, substantial frames; the pace is spacious rather than dashboard-dense.

### Essentials

- The promise reads as a calm institutional declaration: regular 80px display type, 1.05 line height and -0.01em tracking, centered in a 900px text measure on deep teal.
- The opening sells through words before spectacle: an 80px header, lavender two-line headline, muted 18px support, a 48px ivory action and a low-contrast proof strip; the first pale chapter enters within the first 900px.
- Chapters behave like overlapping sheets: #f3f4f2 full-width panels with 40px top corners, -40px overlap and an upward 100px shadow; include this layered chapter device on a new landing page rather than replacing everything with floating cards.
- Actions are compact rectangles, not capsules: 48px high, 4px corners, 16px horizontal padding and 16px regular text. Capsules belong to navigation and small category labels.
- Color is held in reserve: most reading space is white or pale stone, large dark bands anchor the beginning and ending, and lavender appears in the headline, selected actions and proof. Richer hues stay within framed media rather than coloring every section.
- A substantial square media stage balances each chapter: 541px square at desktop, 12px corners, with a legible interface, tightly framed person or isolated sculptural symbol. When bespoke media is unavailable, stage one real workflow on a deep teal backing.
- The ending retains a point of view: a 38px lavender mission line beside four compact link columns on deep teal, followed by a larger wordmark, social controls and thin legal separators.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep teal ink | `#001d21` | `--color-ink` | text, background, action | Primary text on light fields and the default dark opening and closing canvas. |
| Lavender | `#bdbbff` | `--color-lavender` | text, accent, action, surface | Opening headline, selected actions, testimonial contrast and plan emphasis. |
| Raised teal | `#002b31` | `--color-raised-teal` | surface | Navigation capsule and dark testimonial panel, subtly lighter than the dark canvas. |
| Active teal | `#00363d` | `--color-active-teal` | action, surface | Dark button active and focus backgrounds; secondary dark controls. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender wash | `#deddff` | `--color-badge` | surface | Compact announcement and inclusion badges. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | background, surface | Light product and pricing page canvas, interface and comparison panels. |
| Ivory | `#f9f9f7` | `--color-ivory` | text, background, action | Text and primary actions on deep teal; warm section backgrounds and pricing cards on light pages. |
| Pale stone | `#f3f4f2` | `--color-stone` | surface, background | Layered chapters, feature cards and light navigation capsules. |
| Soft edge | `#ebeceb` | `--color-edge` | surface, border, action | Neutral media backing, pale control fills and subtle solid rules. |
| Teal hairline on white | `#ccd5d6` | `--color-hairline` | border | Visible result of rgba(0,43,49,0.2) on white; comparison, FAQ and footer separators. |
| Blue gray | `#b2bfc1` | `--color-muted-on-dark` | text, accent | Support copy and footer links on dark fields; understated pricing cap. |
| Secondary gray | `#68706f` | `--color-secondary` | text, link | Support copy and secondary navigation on light fields. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light product and pricing pages | Muted bronze | `#8a744a` | `--color-bronze` | text, accent, border | Section labels, tiny dot markers and mission text in the light theme. |
| light product and pricing conversion panels | Closing lavender | `#cdcbff` | `--color-gradient-lavender` | background | Dominant stop in the closing call gradient. |
| light product and pricing conversion panels | Closing rose | `#ffb1b1` | `--color-gradient-rose` | background | Distant warm stop in the closing call gradient; the visible panel remains mostly lavender and dusty pink. |

## Typography

- **angellistDisplay** — Headlines, introductory paragraphs, mission lines, large numbers and quotes. Open, regular-weight sans display with a broad, softly humanist rhythm and unforced lowercase forms. If unavailable, use **Manrope**. Use weight 400 and preserve the broad measures and restrained negative tracking. Font stack: "angellistDisplay", "Manrope", Arial, sans-serif.
- **angellist** — Body text, navigation, buttons, section labels and metadata. Readable contemporary sans with a neutral businesslike texture; regular body and modest medium-weight subheads. If unavailable, use **Inter**. Use 400 and 500; avoid heavy UI-style labels. Font stack: "angellist", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | angellistDisplay | 400 | 80px | 1.05 | -0.01em | size clamp(2.813rem, 1.912rem + 3.43vw, 5rem) | Main promise, usually two centered lines; lavender on the dark opening. |
| heading-lg | angellistDisplay | 400 | 60px | 1.15 | -0.015em | size clamp(2.375rem, 1.809rem + 2.16vw, 3.75rem) | Chapter names and broad FAQ or editorial headings. |
| mission | angellistDisplay | 400 | 37.9px | 1.25 | normal | size clamp(1.563rem, 1.228rem + 1.27vw, 2.375rem) | Closing mission statement and trust-section introductory statements. |
| intro | angellistDisplay | 400 | 22px | 1.4 | normal | size clamp(1.25rem, 1.199rem + 0.2vw, 1.375rem) | Chapter support paragraphs and linked category tile titles. |
| body-lg | angellist | 400 | 18px | 1.6 | -0.0025em | fixed | Opening support, FAQ questions, section labels and feature explanations. |
| subtitle | angellist | 500 | 18px | 1.4 | -0.005em | fixed | Footer column headings and small benefit titles. |
| body | angellist | 400 | 16px | 1.5 | -0.002em | fixed | Actions, navigation and standard support paragraphs. |
| caption | angellist | 400 | 14px | 1.5 | normal | fixed | Footer links, supporting detail and comparison rows. |
| badge | angellist | 400 | 12px | 1.5 | -0.003em | fixed | Small announcement badges above chapter names. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| product and pricing pages | heading | angellistDisplay | 400 | 48px | 1.2 | -0.005em | size clamp(2rem, 1.588rem + 1.57vw, 3rem) | Capability and pricing section headlines, plus centered conversion calls. |
| product and pricing pages | card-heading | angellistDisplay | 400 | 28px | 1.3 | normal | size clamp(1.375rem, 1.221rem + 0.59vw, 1.75rem) | Plan names, feature card titles and testimonial quotations. |
| editorial resource sections | metadata | angellist | 500 | 11px | 16px | 0.08em, uppercase | fixed | Reading duration and date attached to editorial cards. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Headlines remain weight 400; size, color and line breaks carry emphasis rather than boldness.
- Tracking is mildly negative on major headlines and body text, normal on mid-size display text; only small editorial metadata is widely tracked.
- Use the fluid size formulas for display roles rather than scaling the whole page. Introductory display paragraphs differ visibly from the smaller sans body.

## Layout

**Density:** Airy at section scale, compact within controls and footer link groups; long pauses separate a few substantial ideas.

### Spacing

**Spacing system:**

- **step** 8px, horizontal — Primary horizontal rhythm, expressed in navigation gaps, padding and 32px column gutters.

| Value | Use |
| --- | --- |
| 4px | Badge padding and tight inline details. |
| 8px | Paired action and icon gaps. |
| 12px | Card title to explanation. |
| 16px | Headline to standard support; button side padding. |
| 24px | Chapter title to introduction; pricing inner padding; FAQ vertical padding. |
| 32px | Grid gutter and support-to-action spacing. |
| 40px | Mission-to-actions spacing, editorial title-to-grid gap and chapter overlap. |
| 48px | Desktop outer gutters and feature-card inset. |
| 64px | Top padding within layered chapters. |
| 80px | Standard section padding and separation of large content groups. |
| 96px | Bottom padding within layered chapters. |
| 128px | Conversion panel vertical padding. |

### Containers and grids

- **main-container**: max width 1536px · 12 columns · gap 32px · side padding 48px. Centered desktop shell. At 1440px, usable width is 1344px; use the twelve-column grid for both full-width content and asymmetric chapters.
- **chapter-split**: 2 columns · gap 32px. Text occupies the left six grid columns, square media the right five, leaving one column of breathing room. At desktop the text block is 656px and the media is 541px square.
- **hero-measure**: max width 900px. Centered opening promise and supporting sentence.
- **label-and-content** (only for product and pricing pages): 12 columns · gap 32px. Light product and pricing sections place a label in the first two columns and the content in the remaining ten; desktop content width 1115px.
- **feature-grid** (only for product pages): 2 columns · gap 32px. Substantial 656px-wide explanatory cards, with integrated demonstration graphics.
- **category-grid** (only for product catalogs): 4 columns · gap 32px. Tall category tiles, 312px wide at desktop.
- **closing-measure** (only for light product and pricing conversion panels): max width 660px. Centered copy inside the inset gradient conversion panel.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-badges | 4px |
|  | media | 12px |
|  | chapter-top-corners | 40px |
|  | navigation | 9999px (pill) |
| product pages | feature-cards | 8px |
| pricing pages | pricing-top-corners | 3px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| stack-separation | `0px -40px 100px 0px rgba(0, 0, 0, 0.1)` | Upward shadow on later overlapping pale chapters, not on ordinary cards. |

### Surfaces

#### Dark canvas · level 0

**Use:** Default opening and ending; dark proof bands.

**CSS:** `background: #001d21; color: #f9f9f7`

**Observed:** A solid green-black field, without a decorative texture or luminous edge.

**Transfer:** Use it for a sustained visual pause rather than as a small floating dark card.

#### Layered sheet · level 1

**Use:** Default large capability chapters.

**CSS:** `background: #f3f4f2; color: #001d21; border-radius: 40px 40px 0px 0px; box-shadow: 0px -40px 100px 0px rgba(0, 0, 0, 0.1)`

**Observed:** Full-bleed sheets overlap the preceding chapter by 40px; the first sheet has no upward shadow.

**Transfer:** Preserve the large top arc and slight layering for new capability chapters.

#### Media stage · level 1

**Use:** Framing substantial square chapter media.

**CSS:** `background: #ebeceb; border-radius: 12px; overflow: hidden`

**Observed:** The media itself supplies the dominant color; the neutral backing is not intended as empty content.

**Transfer:** Fill with a meaningful workflow, portrait or sculptural symbol.

#### Light canvas · level 0

**Only for:** light product and pricing pages

**Use:** Long-form detail and structured comparison.

**CSS:** `background: #ffffff; color: #001d21`

**Observed:** Alternates with warm ivory section bands rather than a checkerboard of accent fills.

**Transfer:** Use white for detailed reading and ivory to gather related proof.

#### Ivory band · level 0

**Only for:** light product and pricing pages

**Use:** Comparison, feature and editorial bands.

**CSS:** `background: #f9f9f7; color: #001d21`

#### Feature panel · level 1

**Only for:** product pages

**Use:** Grouped explanation and demonstration.

**CSS:** `background: #f3f4f2; border-radius: 8px; overflow: hidden`

#### Gradient call · level 1

**Only for:** light product and pricing conversion panels

**Use:** One substantial conversion pause before objections or final navigation.

**CSS:** `background: linear-gradient(191deg, #cdcbff 33.8%, #ffb1b1 177.07%); border-radius: 12px; padding: 128px 48px; overflow: hidden`

**Observed:** Broad lavender with subdued rose toward the lower left, not a saturated rainbow.

**Transfer:** Center one promise and one primary action; maintain the mostly lavender balance.

## Components

### Navigation capsule

**Use:** Centered primary navigation within the sticky 80px header.

**CSS:** `display: flex; height: 56px; padding: 0px 8px; background: #002b31; border-radius: 9999px`

**Text style:** `body` — angellist 400 · 16px/1.5 · tracking -0.002em

**Observed:** Wordmark is separate at left, sign-in and lavender sales action at right. Items have 18px side padding; small chevrons mark menus and northeast arrows mark external destinations. Light-theme capsule uses pale stone with dark text.

**Transfer:** Keep the center group visually independent of the conversion controls.

### Primary button

**Use:** Primary action on the default dark opening and closing.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #f9f9f7; color: #001d21; height: 48px; padding: 0px 16px; border-radius: 4px; text-decoration: none`

**Text style:** `body` — angellist 400 · 16px/1.5 · tracking -0.002em

**Observed:** Content-sized and regular-weight; generally one centered action below the opening support line.

**States:** Declared: hover background #bdbbff and color #001d21; focus-visible background #ebeceb, color #001d21 and 1px solid outline; active background #ebeceb and color #001d21.

### Ink button

**Use:** Primary action on pale chapters and light product sections.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #001d21; color: #f9f9f7; height: 48px; padding: 0px 16px; border-radius: 4px; text-decoration: none`

**Text style:** `body` — angellist 400 · 16px/1.5 · tracking -0.002em

**Observed:** Can sit beside a lavender secondary action; external destinations include a small northeast arrow.

**States:** Declared: hover background #bdbbff and color #001d21; focus-visible background #00363d, color #f9f9f7 and 1px solid outline; active background #00363d and color #f9f9f7.

### Sales button

**Use:** Persistent header conversion.

**CSS:** `background: #bdbbff; color: #001d21; height: 48px; padding: 0px 16px; border-radius: 4px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `body` — angellist 400 · 16px/1.5 · tracking -0.002em

**Observed:** The small lavender control provides a consistent accent even when the header is dark.

**States:** Declared: hover background #f9f9f7 and color #001d21; focus-visible background #f9f9f7, color #001d21 and 1px solid outline; active background #f9f9f7 and color #001d21.

### Announcement badge

**Use:** Short availability status immediately before a chapter name.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; background: #deddff; color: #001d21; border-radius: 4px; padding: 0px 4px`

**Text style:** `badge` — angellist 400 · 12px/1.5 · tracking -0.003em

**Observed:** Tiny flat highlighted text, not a large promotional banner.

### Footer link group

**Use:** Compact navigation in the substantial closing area.

**CSS:** `display: flex; flex-direction: column; gap: 6px; color: #b2bfc1`

**Text style:** `caption` — angellist 400 · 14px/1.5

**Observed:** A medium-weight subtitle sits 24px above the links. Four columns occupy the right side; related subgroups are separated by 32px. Light theme uses secondary gray links.

**States:** Declared: hover color #f9f9f7 on dark-theme links.

**Transfer:** Group by reader task and keep the left mission/action column separate.

### FAQ row

**Only for:** product and pricing pages

**Use:** Objection handling after the conversion call.

**CSS:** `border-bottom: 1px solid rgba(0, 43, 49, 0.2); padding: 24px 24px 24px 0px; display: flex; justify-content: space-between; align-items: flex-start; gap: 32px`

**Text style:** `body-lg` — angellist 400 · 18px/1.6 · tracking -0.0025em

**Observed:** Question at left, thin plus at right; a top rule starts the group. Closed rows are about 78px tall; answers expand inline rather than in a modal.

**Transfer:** Use concise, concrete questions about access, support and constraints.

### Feature card

**Only for:** product pages

**Use:** Explain a capability through a focused demonstration.

**CSS:** `background: #f3f4f2; border-radius: 8px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `card-heading` — angellistDisplay 400 · 28px/1.3

**Observed:** Title and support precede a large integrated graphic. Text inset is 48px at desktop; two cards share each row with 32px gutters. The lower media can extend to the panel edges.

**Transfer:** Show a single answer, artifact or outcome rather than a full miniature dashboard.

### Plan card

**Only for:** pricing pages

**Use:** Present two service levels with comparable construction.

**CSS:** `background: #f9f9f7; border-radius: 3px 3px 0px 0px; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `card-heading` — angellistDisplay 400 · 28px/1.3

**Observed:** A 12px top cap is blue gray for the baseline plan and lavender for the broader plan. Name, short suitability line and explanation precede a display-sized annual price formula; an inset action sits below a fine rule. Desktop cards are 541px wide with 24px internal padding. Detailed comparison repeats the caps on white panels and groups compact check-mark rows.

**Transfer:** Keep aligned price formulas and equivalent actions instead of using a large discount badge.

### Testimonial slide

**Only for:** product and pricing proof sections

**Use:** Human proof with a visible next story.

**CSS:** `background: #002b31; color: #f9f9f7; border-radius: 12px; overflow: hidden; display: flex`

**Text style:** `card-heading` — angellistDisplay 400 · 28px/1.3

**Observed:** A broad 1115px panel holds quote and bottom-aligned attribution at left, with a 300px-wide edge-to-edge portrait at right. The next lavender slide peeks beyond the right edge. Circular 48px previous/next controls and small dots sit below.

**Transfer:** Use an attributed operational outcome; retain a natural portrait and generous quote measure.

### Article card

**Only for:** editorial resource sections

**Use:** Recent resources in a four-column band.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 40px; padding-bottom: 16px; border-bottom: 1px solid rgba(0, 43, 49, 0.2)`

**Text style:** `body-lg` — angellist 400 · 18px/1.6 · tracking -0.0025em

**Observed:** A roughly 2:1 thumbnail is followed by a small category chip, a sentence-case title and bottom-aligned uppercase date/read-time metadata. No enclosing white card or heavy shadow.

**Transfer:** Let distinctive thumbnails add variety while keeping all text and separators consistent.

## Imagery and graphics

### Square chapter media

**Use:** Signature counterweight to each pale chapter's text.

**Observed:** A 541px square stage sits at the right with 12px corners: a cropped white software interface on deep teal, monochrome close portraiture, or a single sculptural symbol on a dark warm field. Media is almost as tall as the chapter and visually denser than the text.

**Transfer:** Choose one meaningful interface or subject per chapter. For a product without commissioned artwork, use a crisp, enlarged real workflow on deep teal, not a stock illustration collage.

**Build:** For the workflow fallback, make a square deep-teal field, inset a white interface panel from the top and left by about 60px, give it 8px corners and allow its right and bottom edges to run out of the frame. Limit the interface to one header, a few data rows and one dark inset summary.

### Sculptural symbol stage

**Use:** A tactile, nonliteral identity moment inside chapter media.

**Observed:** A single symmetrical symbol is centered in a dark plum square, with low-contrast bronze-gray faceted shading and a small amount of grain. Another identity stage uses a cream line emblem on a restrained warm brown gradient. These are contained artworks, not page-wide palettes.

**Transfer:** Create an original symbol that represents the new product's behavior. Preserve the isolated object, subdued light and generous surrounding space.

**Build:** Use an SVG of four curved triangular blades rotated around a central negative-space diamond; fill each blade with a dark-to-muted warm-gray linear gradient at a different angle. Center the shape at about 70% of the square width, add subtle monochrome turbulence clipped to the blades, and place on a dark plum-to-near-black vertical field. A minimum version is one original cream monoline symbol on a muted two-stop warm gradient.

### Faceted lifecycle rings

**Only for:** full-service product openings

**Use:** Large abstract process object under a centered dark hero.

**Observed:** Five lavender polygonal loops recede diagonally upward to the right over deep teal. Faceted edges have soft grain rather than glossy chrome; tiny muted process labels sit below. The object continues below the first viewport.

**Transfer:** Translate an actual multistage process into repeated shapes with clear progression, keeping the lavender material and dark surrounding air.

**Build:** Draw five open-centered polygonal ellipses in SVG, each with roughly 16 segments, thick lavender front edges and darker offset side faces. Offset each successive loop right and upward while reducing scale slightly. Use subtle noise clipped to the faces; keep the canvas transparent over deep teal. Avoid bright reflections.

### Demonstration fragments

**Only for:** product capability sections

**Use:** Make benefits concrete within Feature card and comparison panels.

**Observed:** White message bubbles, pale lavender responses, slim data cards and cropped tables float on pale stone. Only a few oversized interface fragments are shown; light shadows are confined to these artifacts. A before/after example contrasts stacked email windows with a direct question and answer.

**Transfer:** Reconstruct the smallest understandable interaction for a new product; use readable fragments rather than copying an entire application.

### Natural portrait proof

**Only for:** testimonials and service-support sections

**Use:** Balance software with visible people.

**Observed:** Color portraits are cropped tightly, edge-to-edge in testimonial slides. A separate service image shows a person working in soft side light, with teal shadows and warm defocused background lights; a translucent score tile overlays a corner.

**Transfer:** Use candid, warmly lit working portraits rather than isolated cutout headshots. Keep any score tied to a real service outcome.

### Editorial data art

**Only for:** editorial resource sections

**Use:** Variety in small landscape thumbnails.

**Observed:** Dark teal fields hold glowing point clusters, connected pastel document slips and simplified interface diagrams; another thumbnail uses mint-backed layered chart terrain. The small images are richer than the surrounding restrained reading band.

**Transfer:** Use thematic abstract data imagery in a consistent landscape frame, with one clear focal point.

**Build:** For a point-field thumbnail, scatter small pale-mint circles on deep teal with radial density increasing toward one off-center focus; blur a duplicate layer at low opacity for a soft local glow. For a document diagram, connect a central stacked-disk symbol to small pastel rectangles with hairline curves.

### Icons

**Observed:** Arrows and plus signs are fine outline SVGs, commonly 20px with 1.3px strokes; secondary external-link marks are 16px with 1px strokes. Product category symbols are compact 32px geometric marks. Bronze outline symbols accompany small benefits; section labels use a 12px filled dot.

**Transfer:** Use restrained geometric line icons with square or butt-ended strokes. Keep filled symbols for category marks and dots, not an unrelated colorful icon family.

## Section recipes

How recurring sections are built.

### First screen: Institutional dark opening

**Observed:** Deep teal is the back layer; an 80px sticky header carries the small left wordmark, centered Navigation capsule and right Sales button. A two-line lavender display headline spans roughly half the viewport width in a centered 900px text area, beginning about 152px down the page. Muted body-lg support follows closely, then Primary button after 32px. A subdued six-cell proof strip sits below with 128px by 64px logo cells and 44px gaps, separated by thin vertical rules. There is no oversized hero artwork. The dark field ends at 645px, where a Layered sheet begins; within the first 900px its dot label, chapter name and upper square interface stage are visible. The chapter's full support and actions continue below the fold.

**Transfer:** Lead with one broad product promise and one explanatory sentence, then a credible proof strip. If customer logos are unavailable, use a few verified adoption or capability facts in the same subdued cells. Bring the first meaningful workflow into the emerging chapter. A light product opening uses the same centered display recipe in ink with a thin bronze category pill; a full-service opening adds Faceted lifecycle rings below. Pricing opens with a compact category switch, left-aligned promise and a simple comparison graphic.

**Avoid:** Do not turn the default first screen into a giant dashboard hero, add a vivid gradient behind the headline, or let a tall hero push every trace of the first chapter below 900px.

**Text style:** `display` — angellistDisplay 400 · 80px/1.05 · tracking -0.01em

### Layered capability chapter

**Observed:** Layered sheet contains a category-dot label near the top left, a heading-lg name, an intro paragraph 24px below and Ink button with optional lavender companion. The text fills the left six columns; Media stage occupies the right five. Content has 64px top and 96px bottom padding. Later sheets overlap by 40px and cast the stack-separation shadow.

**Transfer:** Use each sheet for one distinct capability or audience, with one strong square visual. Repeat the visual grammar without requiring a fixed number of chapters.

**Text style:** `heading-lg` — angellistDisplay 400 · 60px/1.15 · tracking -0.015em

### Label and content chapter

**Observed:** A bronze body-lg label with 12px dot sits in the first two columns; a heading and body support sit in the remaining ten. Heading-to-support gap is 16px and the next major block follows after about 80px. Detail pages alternate Light canvas and Ivory band.

**Transfer:** Use the label for a navigable category, not a second competing headline.

**Text style:** `heading` — angellistDisplay 400 · 48px/1.2 · tracking -0.005em

### Capability selector

**Observed:** An ivory section pairs a stack of ruled capability titles at left with a large dark demonstration at right. Active title is ink with support expanded below; inactive titles are gray. The visible demonstration uses concentric thin orbit lines, small pale nodes and lavender labels.

**Transfer:** Use the selector to reveal one coherent workflow per title, not four simultaneously competing diagrams.

**Text style:** `card-heading` — angellistDisplay 400 · 28px/1.3

### Quantified proof

**Observed:** A centered mission-sized lead sits above three enormous ink figures on white. Each figure is about 112px high with a compact 16px explanatory caption below; there are no card containers. The figures have abundant surrounding air.

**Transfer:** Use three or fewer independently defensible metrics. Preserve the oversized numeral-to-small-caption contrast; do not transfer the original claims.

### Human proof rail

**Observed:** Testimonial slide spans most of the container with the next slide intentionally visible. Some trust sections place a centered mission-sized lead and subdued six-logo strip above; controls sit 48px below the cards.

**Transfer:** Use this for proof with enough detail to deserve a full quotation, keeping the portrait integral to the panel.

**Text style:** `card-heading` — angellistDisplay 400 · 28px/1.3

### Conversion pause

**Observed:** Gradient call is inset 48px from the desktop edges. A centered heading, optional 16px support paragraph after 16px and Ink button after 32px sit in a 660px copy measure. Outer section padding is 80px.

**Transfer:** Use the broad soft-color panel for a concrete next step after proof; keep the message short enough to preserve the large surrounding field.

**Text style:** `heading` — angellistDisplay 400 · 48px/1.2 · tracking -0.005em

### Objection list

**Observed:** Label and content chapter places the heading above a group of FAQ row components, with 80px separating the heading area and the rules. Most rows are closed; an open answer remains in the same column.

**Transfer:** Answer the practical uncertainty that blocks conversion rather than repeating benefit slogans.

**Text style:** `heading-lg` — angellistDisplay 400 · 60px/1.15 · tracking -0.015em

### Mission-led ending

**Observed:** On the default Dark canvas, a lavender mission paragraph with a 341px text measure occupies the left four grid columns, with two actions 40px below. Footer link group components form four columns across the remaining eight. After the navigation area, a prominent wordmark sits at left and social squares at right. Thin top and bottom rules frame the legal utility row; compact disclaimer prose follows. The complete footer is roughly 1100px tall with 80px top and bottom padding. Light product and pricing endings keep the same construction on white, with bronze mission text and gray links; the editorial product page inserts Article card resources immediately before it.

**Transfer:** Close with a meaningful statement of the new product's purpose, not just another giant CTA. Retain the mission, structured navigation, wordmark and fine utility hierarchy; adapt legal content to actual needs.

**Text style:** `mission` — angellistDisplay 400 · 37.9px/1.25

## Page flow

**Storyline:** Broad promise → concrete product or service chapters → credible proof → focused next step → practical questions → mission-led navigation; depth and order adapt to page purpose.

### Portfolio or multi-capability marketing landing

1. **Promise** — Centered dark opening with subdued proof strip.
2. **Capability chapters** — Overlapping pale sheets pair short introductions with square product, portrait or symbol media.
3. **Closing call** — Dark mission-led footer combines actions, four navigation groups, wordmark and legal utility.

**Transfer:** Use this as the default visual system for a new landing page; the chapters can describe capabilities rather than separate businesses.

### Pricing and plan selection

1. **Promise** — Light opening with compact segmented plan-category switch, left display promise and a restrained comparison chart.
2. **Pricing** — Two aligned capped plan cards present annual formulas and equivalent sales actions.
3. **Comparison** — White feature matrices on ivory, with grouped check rows and a narrow additional-services strip.
4. **Social proof** — Dark trust band with logos and portrait-led quote rail.
5. **Closing call** — Inset soft-gradient conversion panel.
6. **Objection handling** — Ruled pricing FAQ.
7. **Navigation** — White mission-led ending with full utility and disclaimer area.

**Transfer:** Make pricing legible through aligned terms and comparable service levels, not competitive badge clutter.

### Full-service product explanation

1. **Promise** — Thin announcement, centered dark headline with lavender phrase, light action and faceted lifecycle loops.
2. **Product demonstration** — Light split introduction with a video, followed by ivory capability selector and a large workflow graphic.
3. **Capability breadth** — Four tall category tiles with small geometric icons and bottom-aligned arrow actions.
4. **Quantified proof** — Three monumental numbers on white, then a portrait testimonial rail.
5. **Closing call** — Inset lavender-rose conversion panel.
6. **Objection handling** — Ruled FAQ on white.
7. **Navigation** — White mission-led ending, wordmark and legal material.

**Transfer:** Combine software demonstration with service proof; use the loop object only when a staged lifecycle is meaningful.

### Focused software feature launch

1. **Promise** — Thin announcement and centered light hero with outlined category pill and one ink action.
2. **Product demonstration** — Large centered video, compatibility marks, then a dark before/after comparison.
3. **Social proof** — Warm-ivory quantified trust statement and subdued logos.
4. **Capability chapters** — Two-column substantial feature cards, four small benefits and a compact bronze quote band.
5. **Service proof** — Dark split section with large headline and warmly lit working portrait with score overlay.
6. **Closing call** — Soft-gradient conversion panel.
7. **Objection handling** — Long ruled FAQ.
8. **Further reading** — Four article cards on ivory with distinctive data-art thumbnails and uppercase read-time captions.
9. **Navigation** — White mission-led ending with full utility and product-specific caveats.

**Transfer:** Use the light variant for a narrowly scoped software launch; keep visible workflow fragments, human support and reading paths distinct.

## Writing

Clear, financially literate and assured without sounding grandiose. It pairs institutional scope with practical descriptions of what the customer can do and where service removes friction.

**Do not copy:** Do not reuse AngelList or its portfolio names, logos, distinctive symbol assets, customer names, testimonials, financial figures, claimed service scope, dates or performance claims. Source examples illustrate writing structure, not facts for another business.

- **Addressing the reader:** Use you and your for outcomes and operational problems. Use we for a service commitment; name the product when explaining what it concretely is.
- **Rhythm:** Headlines are short declarations or direct benefit statements, often split across two lines. Support usually takes one or two sentences; actions are two to five words. Periods add finality, while em dashes clarify a practical distinction.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | State the system's purpose or a concrete transformation, without an introductory flourish. | 5–12 words | “The financial system for private markets”<br>“Transform your fund into something you can talk to” |
| Supporting line | Name the category, then explain the operational outcome in plain language. | 14–30 words | “[Brand] is a portfolio of businesses that move capital through private markets.”<br>“An MCP server for GPs. Ask questions about your fund from any AI tool and get a verified answer in seconds.” |
| Section headline | Contrast the desirable work with the burden being removed. | 5–15 words | “Focus on deals, not admin, while delivering more to your investors”<br>“Bring your fund operations out of the email era” |
| Primary action | Simple verb plus destination or human next step. | 2–5 words | “Talk to an expert”<br>“Get started”<br>“Request access” |
| Closing mission | A broad participatory purpose expressed as an active sentence. | 8–12 words | “Give everyone a stake in the future of technology” |
| FAQ | Direct question about eligibility, cost, support or limits. | 7–15 words | “Does [Brand] support fund migrations from other fund administrators?” |

**Words and phrasing to use:** run; launch; scale; support; verified; transparent; one platform; built for; without the complexity

**Avoid:** revolutionary; game-changing; disrupt everything; magical; crush it; limitless; exclamation-heavy promises

**Rules:**

- Explain specialist terms at first mention when the reader may not share the domain vocabulary.
- Pair large claims with specific operational detail or verified proof nearby.
- Use contrasts such as 'not admin' to sharpen a benefit, not to mock the reader's current tools.
- Keep a human sales invitation available alongside self-serve exploration.

## Do's and Don'ts

### Do

- Keep major headlines regular weight and near 80px/1.05 at desktop rather than bolding key words.
- Use 48px outer gutters and a 32px grid gap at desktop.
- Give the overlapping chapter sheets 40px top corners and a restrained upward shadow.
- Use the ivory 48px action on dark fields and the ink equivalent on pale fields.
- Keep chapter media square with 12px corners and an identifiable focal subject.
- Retain the 38px mission column beside four navigation groups in the ending.
- Use muted blue-gray support on dark fields and secondary gray on light fields.
- Align comparison plans by content role and distinguish them with 12px top caps.

### Don't

- Do not apply capsule corners to every action; primary and secondary CTA controls have 4px corners.
- Do not turn the dark teal into neutral black or a bright blue SaaS background.
- Do not use heavy drop shadows on ordinary feature or pricing cards; the conspicuous shadow belongs to overlapping sheets.
- Do not spread bronze across the default dark theme; it belongs to the light detail-page vocabulary.
- Do not fill the reading canvas with plum, brown or mint merely because those colors occur inside media.
- Do not shrink full interface views until they become unreadable; demonstrate one enlarged fragment.
- Do not make every label uppercase and tracked; most section labels are 18px sentence-case text.
- Do not give editorial cards thick outlines or raised white surfaces; their structure comes from media, spacing and one bottom rule.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions use 0.2s cubic-bezier(.4, 0, .2, 1).
- Layered chapters declare a scroll-linked parallax-lag animation with auto duration and linear timing.
- Testimonial rails expose dot navigation and circular previous/next controls.

**Transfer:**

- Keep hover changes limited to the established ink, ivory and lavender relationship.
- Use overlap and gentle scroll-linked separation to reinforce the sheet metaphor rather than adding unrelated entrance effects.

**Unknown:**

- Exact parallax displacement and complete scroll choreography are not established.
- Autoplay behavior and timing of media and carousel slides are not established.

### Responsive

**Observed:**

- Main shell classes progress through 20px, 36px, 40px and 48px side padding.
- Primary desktop navigation is hidden below the medium layout; the four-column footer grid is medium-layout and above.
- Sheet top corners are 40px in the medium layout and above; desktop columns and display sizes use responsive rules.

**Transfer:**

- As a narrow-screen adaptation, stack chapter text before its square media and preserve the sheet silhouette.
- Reduce the proof strip into fewer columns while maintaining its subdued separators.
- Allow mission and navigation groups to stack without compressing the body type.

**Unknown:**

- Exact mobile menu construction, narrow-screen ordering and media animation behavior are not established.
- Only desktop layouts were directly reviewed; narrow-screen adaptations above are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
