# Atlas — reflected worlds of access

## Overview

A cinematic, invitation-led style for premium products and services, pairing deep black editorial space with immersive photography and reflective product imagery. Large book-weight grotesk headlines feel sculptural rather than loud, while tiny uppercase mono labels add the character of destination markings. The palette is almost entirely black, silver and gray; color lives in the scenes rather than the interface. A lighter information-led variant trades the dark theater for pale studio imagery and orderly expandable lists.

### Essentials

- The opening feels like a portal, not a sales panel: a full-width 836px media stage contains a centered reflective object, a floating 65px × 64px navigation tile and restrained progress marks; explanatory copy and conversion sit below the first 900px.
- Headlines are silver objects in black space: Sequel Sans Display at 97px/1.03, weight 400, normal tracking, centered into short stacked lines with a white-to-transparent text gradient; chapter support begins 104px beneath.
- Information is a narrow island inside a wide cinema: full-width 1440px scenes alternate with a centered 744px column; feature rows split 5:9 with a 60px gutter, white 28px titles and gray 24px body copy.
- Actions have two deliberately different weights: the main conversion is a compact 48px metallic pill with 15px bold text; chapter exploration is an 80px charcoal rounded rectangle with 18px corners, 23px text and a 32px icon.
- Color belongs to lived scenes, not UI decoration: nearly all non-image area stays black, #141414, #1e1e1e and gray; full-bleed atmospheric photography supplies the blue, amber or red. Include a reflective product or object scene and a cinematic contextual scene, using a lit physical proxy when no finished product media exists.
- The ending returns to the monumental promise: a centered 97px stacked invitation, separated by 104px from its category label and gray support, gives way to a compact 744px footer with 12px uppercase mono navigation rather than another busy promotional grid.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Reflection white | `#ffffff` | `--color-white` | accent, background | Bright end of reflective headline treatment; light footer and editorial cards. |
| Soft white | `#f8f8f8` | `--color-primary` | text, background | Primary text on dark scenes and the pale information-list canvas. |
| Editorial gray | `#808080` | `--color-muted` | text | Supporting copy, secondary explanations and footer disclosures. |
| Dark rule | `#272727` | `--color-rule` | border, action | One-pixel feature separators and exploration-button hover fill. |
| Charcoal action | `#1e1e1e` | `--color-action` | action, surface | Chapter exploration buttons. |
| Near black | `#141414` | `--color-panel` | surface, background, border | Media panels, dark chapter gradient origin and the visible result of 8% white glass on black. |
| Metal button ink | `#0f0f0f` | `--color-button-ink` | text | Dark lettering on the metallic primary action. |
| Black theater | `#000000` | `--color-canvas` | background, text | Default marketing canvas; also primary text in the light information variant. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light information pages | Light secondary ink | `#999999` | `--color-light-muted` | text, border | Visible 40% black over white for secondary information text; over the soft-white canvas it appears slightly darker. |
| light information pages | Light divider | `#dfdfdf` | `--color-light-rule` | border | Visible 10% black hairline over soft white; use the alpha recipe for correct compositing. |
| light information pages | Studio silver | `#e5e5e5` | `--color-studio` | background | Dominant pale-gray backdrop of the light studio opening. |
| light information pages | Footer ultramarine | `#001391` | `--color-footer-blue` | text, border, link | Small navigation links, wordmark and divider in the white footer, not a general marketing accent. |

## Typography

- **Sequel Sans Display** — Monumental marketing titles, exploration text and information-page descriptions. Smooth neo-grotesk with open counters and closely fitted book-weight display forms. If unavailable, use **Inter**. Use weight 400 and retain normal tracking on monumental titles. Font stack: "Sequel Sans Display", "Inter", Arial, sans-serif.
- **Sequel Sans Headline** — Section labels, support copy, feature rows and the compact conversion action. Unembellished grotesk, with a book-weight base and selected bold feature titles. If unavailable, use **Inter**. Use 400 for support and 700 for feature titles. Font stack: "Sequel Sans Headline", "Inter", Arial, sans-serif.
- **ApercuMono Pro** — Image captions and footer navigation. Compact monospaced capitals with a utilitarian destination-label feel. If unavailable, use **Roboto Mono**. Use 500 for medium labels. Font stack: "ApercuMono Pro", "Roboto Mono", ui-monospace, monospace.
- **Sequel Sans Super Display** (only for light information pages) — Large left-aligned information headings and category headings. Tightly drawn optical display grotesk, visually more assertive than the dark marketing titles. If unavailable, use **Inter**. Use 400 with normal tracking; match line breaks before adding weight. Font stack: "Sequel Sans Super Display", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Sequel Sans Display | 400 | 97px | 1.03 | normal | Centered cinematic promise, chapter headline and closing invitation. |
| lead | Sequel Sans Headline | 400 | 28px | 1.3 | -0.0082em | Centered chapter support and opening explanation. |
| feature-title | Sequel Sans Headline | 700 | 28px | 1.3 | -0.0082em | Short bright feature titles and centered chapter category labels. |
| body | Sequel Sans Headline | 400 | 24px | 1.3 | 0.0083em | Muted explanations in split feature rows; numeric proof stays in this same prose style. |
| explore-action | Sequel Sans Headline | 400 | 23px | 1.174 | normal | Chapter exploration buttons. |
| note | Sequel Sans Headline | 400 | 16px | 1.4 | normal | Centered qualification below the primary action. |
| primary-action | Sequel Sans Headline | 700 | 15px | 1.267 | normal | Compact conversion pill. |
| technical | ApercuMono Pro | 500 | 12px | 1.667 | normal, uppercase | Location captions and footer navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| light information pages | information-display | Sequel Sans Super Display | 400 | 90px | 1 | normal | Left-aligned opening title and overview heading. |
| light information pages | information-category | Sequel Sans Super Display | 400 | 60px | 1 | normal | Icon-led category headings above expandable lists. |
| light information pages | information-row | Sequel Sans Headline | 300 | 38px | 1 | normal | Expandable row labels. |
| light information pages | information-body | Sequel Sans Display | 400 | 24px | 1.1 | normal | Expanded detail explanations, with dark short summary and muted longer description. |
| light information pages | information-intro | Sequel Sans Display | 400 | 24px | 1.15 | normal | Opening support line on the light studio background. |
| light information pages | information-action | Sequel Sans Display | 400 | 18px | 1.166 | normal | Outlined information-page action. |

**Notes:**

- The largest marketing titles stay book weight, not bold. Their apparent silver shading comes from clipped background fill rather than gray text alone.
- Bright category labels and gray support share the same 28px scale; hierarchy comes from color, weight and the 104px separation from the headline.
- Body copy is unusually substantial at 24px. The 16px recipe is a qualification, not the main reading size.
- Mono is reserved for captions and navigational markings, not full-size marketing paragraphs.

## Layout

**Density:** Airy and theatrical: viewport-size scenes and near-viewport heading chambers surround a deliberately narrow reading column.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-caption gap. |
| 16px | Compact pill horizontal padding and top inset of the floating navigation tile. |
| 24px | Qualification gap below conversion and footer link spacing. |
| 32px | Horizontal padding around heading chambers and reading columns on constrained widths. |
| 60px | Gutter between feature-title and description columns. |
| 64px | Media panel to exploration action; light footer vertical padding. |
| 88px | Top and bottom breathing room inside each dark feature row. |
| 104px | Monumental headline to category/support group. |
| 128px | Default dark footer vertical padding. |
| 176px | Major separation around feature lists and between explanation and conversion group. |

### Containers and grids

- **reading-column**: max width 744px · side padding 32px. Centered default content island for feature lists, framed media and footer content.
- **feature-split**: 2 columns · gap 60px. Within the reading column, a 5:9 split yields a 244px title area and 440px explanation at desktop.
- **heading-chamber**: max width 744px · side padding 32px. Centered short-line headline and support, vertically centered inside a 1024px chapter chamber.
- **information-column** (only for light information pages): max width 912px. Wider left-aligned information content.
- **editorial-grid** (only for light information pages): 2 columns · gap 20px. Two 446px photographic summary cards per row inside the information column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary-action | 9999px (pill) |
|  | exploration-action | 18px |
|  | media-panel | 24px |
|  | navigation-tile | 16px |
|  | media-caption | 24px |
| light information pages | information-action | 600px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| navigation-glass | `0px 4px 64px 0px rgba(0, 0, 0, 0.16)` | Soft ambient elevation around the floating navigation tile; feature rows remain flat. |

### Surfaces

#### Black canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #000000; color: #f8f8f8`

#### Chapter fade · level 0

**Use:** Long atmospheric capability bands and the default footer.

**CSS:** `background: linear-gradient(in oklab, #141414 0%, #000000 100%)`

**Observed:** The top is only subtly lighter than black; there is no saturated interface glow.

**Transfer:** Use the fade to distinguish a chapter without drawing a boxed section.

#### Media panel · level 1

**Use:** Framed product demonstrations and object close-ups inside the reading column.

**CSS:** `background: #141414; border-radius: 24px; overflow: clip; max-width: 744px`

**Observed:** Broad, low-contrast backing, typically 558px or 585px high; artwork is the content, not a decorative border.

**Transfer:** Place a real product visualization or a carefully lit proxy here, keeping the backing dark.

#### Caption glass · level 2

**Use:** Small location/context label over a full-bleed image.

**CSS:** `background: linear-gradient(rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0.09)); backdrop-filter: blur(50px); border-radius: 24px`

#### Light information canvas · level 0

**Only for:** light information pages

**Use:** Expandable information directory.

**CSS:** `background: #f8f8f8; color: #000000`

#### Studio opening · level 0

**Only for:** light information pages

**Use:** Pale portrait/product opening.

**CSS:** `background: #e5e5e5`

**Observed:** A nearly flat silver-gray field supports a dark full-height figure; the subtle vertical shading is subordinate to the image.

**Transfer:** Use pale studio light and a sharply isolated subject instead of the default dark immersive stage.

## Components

### Floating navigation tile

**Use:** Persistent compact navigation entry above the cinematic content.

**CSS:** `position: fixed; top: 16px; width: 65px; height: 64px; z-index: 10; background: rgba(255, 255, 255, 0.08); border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 16px; backdrop-filter: blur(50px); box-shadow: 0px 4px 64px 0px rgba(0, 0, 0, 0.16)`

**Observed:** Horizontally centered, with a compact pale metallic symbol and no conventional horizontal link bar.

**States:** Declared: hover background-color rgba(0, 0, 0, 0.32); focus-visible not specified.

**Transfer:** Use the new product's simple symbol and an accessible menu label, retaining the single floating entry.

### Primary button

**Use:** Main conversion after the introductory explanation.

**CSS:** `height: 48px; padding: 0px 16px; border: 1px solid rgba(255, 255, 255, 0.32); border-radius: 9999px; background: linear-gradient(oklch(0.8861 0.0112 63.34), oklch(0.5759 0.0275 83.37)); color: #0f0f0f`

**Text style:** `primary-action` — Sequel Sans Headline 700 · 15px/1.267

**Observed:** A small warm-silver capsule centered by itself, with a qualification underneath rather than a second competing action.

**States:** Declared: hover text-decoration underline; focus-visible not specified.

### Exploration button

**Use:** Substantial secondary action after a chapter's proof panel.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 20px; height: 80px; padding: 0px 24px 0px 32px; background: #1e1e1e; color: #f8f8f8; border-radius: 18px`

**Text style:** `explore-action` — Sequel Sans Headline 400 · 23px/1.174

**Observed:** Long descriptive label followed by a 32px circular icon; width follows content rather than filling the reading column.

**States:** Declared: hover background-color #272727; focus-visible background-color #272727; active background-color #1e1e1e and color gray.

### Media caption

**Use:** Contextual label over the lower center of a full-bleed scene.

**CSS:** `padding: 8px 16px; border-radius: 24px; background: linear-gradient(rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0.09)); backdrop-filter: blur(50px); color: rgba(255, 255, 255, 0.8)`

**Text style:** `technical` — ApercuMono Pro 500 · 12px/1.667 · uppercase

**Observed:** A small location-like symbol precedes a single uppercase destination line, with an 8px gap. The label is an interactive caption, not a large badge.

**States:** Declared: hover color #f8f8f8; focus-visible color #f8f8f8; active color rgba(255, 255, 255, 0.6).

### Feature row

**Use:** Explain a capability with minimal graphic noise.

**CSS:** `display: grid; grid-template-columns: 5fr 9fr; column-gap: 60px; margin-top: 88px; margin-bottom: 88px; max-width: 744px`

**Text style:** `body` — Sequel Sans Headline 400 · 24px/1.3 · tracking 0.0083em

**Observed:** A short bright title uses feature-title at left; a longer muted paragraph sits at right. Separate rows with full-column 1px dark rules, not cards.

### Footer navigation

**Use:** Compact grouped navigation after the closing narrative.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 24px; color: #f8f8f8`

**Text style:** `technical` — ApercuMono Pro 500 · 12px/1.667 · uppercase

**Observed:** A small wordmark sits beside three link columns within the reading column. A low horizontal rule and small figurative emblem separate navigation from dense muted disclosures. The light variant changes links and rule to ultramarine.

**States:** Declared: hover text-decoration underline; focus-visible not specified.

### Outline information button

**Only for:** light information pages

**Use:** Jump to a detailed information directory.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 228px; height: 52px; padding-bottom: 2px; border: 1.5px solid #000000; border-radius: 600px; color: #000000; background: transparent`

**Text style:** `information-action` — Sequel Sans Display 400 · 18px/1.166

**Observed:** Plain label ends with a right arrow. The opening version becomes gray on hover; the later in-page version becomes black with white text.

**States:** Declared: hover background-color rgb(126, 130, 135), border-color rgb(126, 130, 135), color rgb(255, 255, 255), text-decoration underline; focus-visible outline rgb(0, 175, 255) solid 3px with outline-offset 0px; active outline 0px.

### Information accordion

**Only for:** light information pages

**Use:** Dense categorized details without a wall of open paragraphs.

**CSS:** `position: relative; border-top: 1px solid rgba(0, 0, 0, 0.1); max-width: 912px`

**Text style:** `information-row` — Sequel Sans Headline 300 · 38px/1

**Observed:** Closed rows are 99px tall with 30px vertical toggle padding, a large light-weight label on the left and thin plus on the right. The final row also has a bottom rule. Expanded content uses a 450px left track plus remaining width, 20px column gap, 40px row gap and 50px bottom padding; summary precedes explanation and terms link.

**Transfer:** Use actual expandable controls with labels and associated detail panels; keep the resting state concise.

## Imagery and graphics

### Reflective portal

**Use:** Signature object scene in the opening and product-story interludes.

**Observed:** A vertically oriented rounded mirror-like card floats over a misty blue-gray skyline, reflecting a sharply framed architectural interior. The centered object occupies roughly one sixth of the scene width and nearly half its height. Cool atmospheric depth contrasts with crisp reflective edges; other scenes show hands, polished metal and devices emerging from black.

**Transfer:** Make the product an aperture into the result it enables. If no photoreal render is available, use a clean rounded reflective proxy containing a second photograph, with believable edge highlights and a real atmospheric background.

**Build:** Layer a full-bleed desaturated city or environment photograph, a faint rgba(255,255,255,0.15) haze near its base, then a centered portrait rounded rectangle about 250px wide and 395px high at desktop. Clip a sharply lit architectural or product-context image inside; add a 1px rgba(255,255,255,0.32) edge and a narrow pale side highlight. Keep the foreground crisp while the distant scene stays soft.

### Cinematic context photography

**Use:** Full-viewport demonstrations of the product's world and alternating chapter media.

**Observed:** Architecture, interiors, tables and fast action fill the entire width. Hotel scenes have deep stone shadows and window light; dining is amber and tactile; action uses lateral motion blur. Overlaid copy is small and centered, leaving the photograph dominant.

**Transfer:** Choose authentic environments or outcomes for the new product, with strong architectural framing or a single readable action. Preserve shadow depth and natural color rather than applying a uniform brand-color wash.

### Black-stage product close-up

**Use:** Object and interface proof within or between capability chapters.

**Observed:** A hand holding a phone is lit softly from one side against pure black; the wrist fades into shadow and the object is large enough to read as a physical artifact. The interface stays within the device rather than becoming page typography.

**Transfer:** Photograph or render one real object at a time on black, with restrained side light and dark surroundings. A simple device mockup with believable material and one real screen is the minimum version.

### Studio silhouette and editorial cards

**Only for:** light information pages

**Use:** Human-scale opening and visual summaries.

**Observed:** A dark-clothed traveler with luggage stands on a pale-gray studio field, aligned to the right and cut off at the lower edge. Summary imagery uses warm low-saturation photographs in 446px × 251px wide frames with rounded corners; titles and a thin plus sit below.

**Transfer:** Use an isolated person or product silhouette against pale silver, paired with editorial photographs of relevant outcomes, not colorful illustration tiles.

### Icons

**Observed:** The dark page uses a pale compact navigation symbol, 13px caption symbols and 32px action icons. The light directory uses black category silhouettes around 32px–44px and fine open plus signs at the far right of rows.

**Transfer:** Use a restrained family of solid silhouettes for categories and lightweight line plus/minus controls for expansion. Avoid multicolor icon badges.

## Section recipes

How recurring sections are built.

### First screen: Reflective cinema opening

**Observed:** A full-width 836px media stage leads the first 900px, with black beneath it and a tiny uppercase access line in the lower strip. Back to front: atmospheric environmental image, crisp centered reflective object, the single Floating navigation tile at the top center, and narrow progress marks near the stage bottom. The image-led resting state gives the object center stage; the title treatment belongs to an alternate animated layer, centered in the upper portion at 97px. In the first 900px the object, navigation and media controls are visible; explanatory paragraphs and the Primary button fall below. There is no persistent two-column sales panel or hero button bank.

**Transfer:** Create one immersive environment and one sharply framed object or proxy that connects the product to its outcome. Use the same display recipe when the headline layer appears, and retain a concise accessible textual promise. Information-led pages instead open with the Studio opening, a left-aligned 90px title, 24px support, Outline information button and tall isolated subject to the right; a short provider strip closes that first screen.

**Avoid:** Do not permanently place the headline over the central reflective object or pull a dense conversion form into the image-led first screen.

**Text style:** `display` — Sequel Sans Display 400 · 97px/1.03

### Introductory invitation

**Observed:** Centered 28px muted explanation in a narrow column, followed after 176px by the Primary button; a 16px qualification sits 24px below it. The block is vertically centered in a 1024px chamber.

**Transfer:** Explain the outcome and admission or purchase mechanism in one restrained paragraph; give the action enough isolation to feel deliberate.

### Monumental heading chamber

**Observed:** A 1024px chamber on Black canvas or Chapter fade centers a 97px headline in roughly three short lines. After 104px, a bright feature-title category label sits directly above a gray lead paragraph. Typical content is around 650px–685px wide with 32px side protection.

**Transfer:** Make the headline a compelling outcome, and let the smaller category label identify the capability. Adapt chamber height to content while preserving the headline/support separation.

**Text style:** `display` — Sequel Sans Display 400 · 97px/1.03

### Scene and feature proof

**Observed:** A full-width cinematic contextual image with Media caption is followed by the centered reading column. Feature row repeats with 1px separators and 88px internal vertical breathing room; a Media panel and Exploration button can complete the chapter, separated by 64px.

**Transfer:** Pair each claim with either a real-world scene or a tangible product demonstration. Choose the number of feature rows for the argument, not for symmetry.

### Monumental close and compact footer

**Observed:** A dark product-motion interlude precedes a 1024px closing invitation chamber. The 97px invitation is followed after 104px by a category label and centered 28px support; the close itself has no extra visible button bank. The footer returns to Chapter fade with 128px vertical and 24px side padding, a 744px inner column, a small wordmark plus three Footer navigation columns, and muted disclosure text below. The light information variant uses white, 64px vertical padding and ultramarine links/rule.

**Transfer:** End the main narrative with one expansive invitation and then change pace into compact navigational utility. Keep any necessary disclosures separate from the large closing message.

**Text style:** `display` — Sequel Sans Display 400 · 97px/1.03

### Light editorial overview

**Only for:** light information pages

**Observed:** Two photographic summaries per row within 912px, with a 20px gutter. Wide photographs lead, then 38px titles and plus controls; detail text expands below rather than crowding the closed state. A centered Outline information button follows.

**Transfer:** Use this variant for a compact overview of a detailed offering, leaving exhaustive explanation to the directory.

### Categorized information directory

**Only for:** light information pages

**Observed:** Light information canvas starts with a 90px overview heading, then 60px category headings with black silhouette icons. Information accordion rows fill the 912px column; category groups have 125px separation. The closing category leads directly into the white footer rather than a second dark sales hero.

**Transfer:** Group extensive capabilities by reader intent, retaining large readable row labels and thin separators.

## Page flow

**Storyline:** Immersive promise → concise invitation → outcome-led capability chapters → tangible product proof → closing invitation → compact navigation and qualifications.

### A cinematic premium-product landing page that sells an entire experience before its mechanics

1. **Promise** — A reflective object in a full-width environment establishes the product as an entry into a different world.
2. **Conversion framing** — A centered explanation and isolated metallic conversion pill clarify the offer.
3. **Outcome proof** — Large environment scenes carry short contextual claims before deeper capability chapters.
4. **Capability chapters** — Monumental outcome headlines alternate with contextual images, split feature rows, dark proof panels and exploration actions.
5. **Product demonstration** — Physical materials and a hand-held interface make the intangible promise tangible.
6. **Closing invitation** — A suspended product scene resolves into another large centered invitation and support paragraph.
7. **Utility and qualifications** — Three mono navigation columns, compact emblem/divider and detailed disclosures finish the page.

**Transfer:** Keep the contrast between immersive scene, monumental sentence and narrow factual explanation; select only the chapters needed for the new argument.

### An information-rich companion page for understanding the scope of an offering

1. **Promise** — Pale studio hero pairs a large left-aligned title and outlined action with a dark isolated figure.
2. **Overview** — A two-column photographic summary grid introduces representative capabilities.
3. **Detailed explanation** — A large directory heading leads to icon-labeled categories and thin-rule expandable rows.
4. **Utility and qualifications** — A white footer with ultramarine mono links and gray disclosure text closes directly after the final list.

**Transfer:** Use the scoped light system for directories and detailed terms, preserving readable large labels rather than shrinking the page into small-text tables.

## Writing

Assured, aspirational and personal, with the polish of a private invitation rather than a hard sell. Concrete conveniences ground the occasional sweeping promise, and a little conversational wit prevents stiffness.

**Do not copy:** Do not reuse Atlas or partner names, logos, product artwork, invitation criteria, membership prices, rewards multipliers, financial protections, destination claims or exact promotional lines as claims for another product. Source examples illustrate voice only.

- **Addressing the reader:** Speak to the reader as you and your. Refer to the product by name when identifying a capability; use we sparingly when describing curation or service.
- **Rhythm:** Headlines usually land in four to nine words and end with a period. Support uses a few flowing sentences, often connected by an em dash; feature labels are short title-case phrases and actions are literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Headline | An expansive personal outcome expressed as a compact sentence. | 4–9 words | “Your key to the world.”<br>“Impossible reservations made easy.” |
| Feature label | Name a benefit or a tactile quality without a slogan-length explanation. | 2–5 words | “Find a Room in Seconds”<br>“Buttery-Smooth Performance” |
| Support | Lead with a recognizable desire or friction, then reveal the product's practical difference. | 2–3 sentences | “You want to eat at great restaurants. So does everyone else. The difference is—you’ve got [Brand].” |
| Primary action | Use a plain verb naming the next step. | 3–6 words | “Join the Waitlist”<br>“See your benefits –>” |
| Closing invitation | Invite forward movement into the promised outcome, without escalating urgency. | 5–8 words | “Begin your adventure with [Brand].” |

**Words and phrasing to use:** designed for you; curated; discover; access; your next step; made easy; exceptional; in seconds

**Avoid:** disruptive ecosystem; 10x your life; hurry now; unbeatable deal; revolutionary platform; emoji-led hype

**Rules:**

- Pair aspirational headlines with an explanation of what the product actually lets the reader do.
- Write verified quantities into ordinary explanatory prose, not unsupported trophy statistics.
- Allow one tactile or lightly witty phrase in a product chapter; do not make every line a joke.
- Keep navigation and disclosure language literal even when the surrounding story is cinematic.

## Do's and Don'ts

### Do

- Keep the default reading island at 744px while letting scene imagery run full width.
- Set monumental dark-page titles at 97px/1.03 and weight 400 with silver clipped fill.
- Leave 104px between chapter headline and its category/support group.
- Use 28px bright feature labels beside 24px gray explanations with a 60px gutter.
- Give exploration actions 80px height and 18px corners; preserve the compact 48px primary pill as a distinct hierarchy.
- Use 12px uppercase mono for image-context labels and footer navigation.
- Finish with the monumental invitation device and then switch to compact grouped utility.

### Don't

- Do not turn every feature into a raised card; the default structure uses flat 1px #272727 separators.
- Do not spread the ultramarine footer color across dark marketing bands; it belongs to the light variant's utility layer.
- Do not replace the 24px main explanation scale with a conventional 14px interface body.
- Do not make all buttons pills: the 80px exploration rectangle is materially different from the compact conversion capsule.
- Do not add hard drop shadows to feature rows or media panels; ambient shadow belongs to the floating navigation glass.
- Do not make mono the headline face or apply uppercase to large promises.
- Do not inflate numeric claims into giant dashboard counters; their native treatment is 24px explanatory prose.

## Motion and responsive

### Motion

**Observed:**

- The large opening title declares opacity 4s ease-in-out, allowing an image-dominant resting state.
- Chapter entrances declare transform 0.75s cubic-bezier(0.28, 1.1, 0.74, 1) and opacity 0.75s cubic-bezier(0.59, 0.41, 0.68, 0.49).
- Exploration actions declare 0.15s ease-in-out; caption glass declares color and padding transitions at 0.15s ease-in-out.
- The floating tile declares background-color, border-radius and box-shadow transitions at 0.15s ease-in-out.

**Transfer:**

- Treat scene transitions and restrained upward entrances as part of the cinematic pacing; retain a legible static scene when media is stopped.
- Keep the opening title and reflective object from competing during transitions.

**Unknown:**

- Exact scroll pinning, video playback choreography, accordion animation timing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- The light information system declares width breakpoints at 479px, 480px, 767px, 768px, 991px, 1280px, 1440px and 1920px.
- The main marketing layout uses constrained reading widths and 32px protective side padding.

**Transfer:**

- On narrow screens, preserve the centered reflective object and floating navigation tile; crop the environment instead of shrinking the whole scene into a thumbnail.
- Stack feature labels above descriptions when the 5:9 split cannot remain readable, keeping thin full-width separators.
- Collapse the information grid to a single photographic column and keep expansion controls aligned to the outside edge.

**Unknown:**

- Mobile compositions, fluid font formulas and exact breakpoint-specific behavior are not established; the narrow-screen transfers are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
