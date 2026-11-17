# Sentry — neon mischief at work

## Overview

A developer-minded identity with a mischievous sci-fi streak: deep aubergine space, hot pink interruptions, acid-green signals and warm gradient edges. Rounded grotesk display lettering and a practical sans keep the language direct while illustrated machines, characters and real interfaces make technical work tangible. Dark, spacious landing pages are the default; white explanatory chapters and dense comparison tables provide a more utilitarian alternative.

### Essentials

- Headlines behave like a confident sentence with a heckler inside it: 88px/1.2 bold Dammit Sans in the opening, with one hot-pink phrase rotated -7.5deg; chapter headings use 60px/1.1 at weight 500 and put the pink answer on a second line.
- The first screen is a theatre, not a dashboard: a centered promise about 1004px wide sits over a grainy purple atmosphere, a 30px/36px support line and paired 40px actions; an illustrated product machine and floating interface panels enter from below.
- Color is a signal against near-black purple: #1f1633 occupies most of the default page, white carries reading, and #fd44b0 and #c2ef4e stay concentrated in headline fragments, 2px image frames and 4px selection rails rather than full-screen neon fills.
- Buttons are compact rounded rectangles, never routine pills: 8px corners, 12px 16px padding, uppercase 14px labels with 0.2px tracking; the main action reads white at rest beside a transparent warm-gradient outline.
- Technical proof gets a playful stage: include both a simplified purple product vignette in a pink-to-lime frame and a real interface detail with a circular purple magnifier. If finished artwork is unavailable, construct legible SVG panels and one oversized tool-shaped object rather than substituting stock photography.
- The page retains hand-made interruptions: include textured purple illumination and a fine wavy divider, plus a short centered closing command above the footer. The default closing uses a 60px heading, 27px support and 128px vertical padding; compact utility variants use 32px headings and a bottom-centered plum glow.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control violet | `#6a5fc1` | `--color-violet` | action, link, accent | Announcement fill, navigation hover and gradient-outline endpoint. |
| Newsletter purple | `#422082` | `--color-form` | surface | Default newsletter form and installation selector. |
| Violet atmospheric depth | `#30145f` | `--color-texture-depth` | background | Lower portion of the textured capability backdrop. |
| Aubergine canvas | `#1f1633` | `--color-canvas` | background, text, border | Default dark page, navigation and dark ink on white actions. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hot pink interruption | `#fd44b0` | `--color-pink` | text, accent, border | Emphatic headline fragments, illustration highlights and the start of image-frame gradients. |
| Electric rail | `#7553ff` | `--color-rail` | border, accent | Inactive capability rails and outlined enterprise FAQ edges. |
| Acid lime signal | `#c2ef4e` | `--color-lime` | accent, border, link | Gradient frame endpoint, tiny technical signals and newsletter fine-print links. |
| Warm red edge | `#c83852` | `--color-outline-red` | border, action | First stop of the secondary action's gradient edge. |
| Warm pink sheen | `#fa7faa` | `--color-peach-pink` | action, accent | First stop of the primary action's animated background. |
| Apricot sheen | `#ffb287` | `--color-apricot` | action, accent | Third stop of primary-action gradients. |
| Magenta edge | `#b44092` | `--color-outline-magenta` | border, action | Middle stop of secondary action edges. |
| Coral sheen | `#ff9691` | `--color-coral` | action, accent | Second stop of primary-action gradients. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dark hairline | `#352d47` | `--color-dark-edge` | border | Visible white at 10% over the dark canvas; use the alpha recipe for terminal and proof-card dividers. |
| Terminal recess | `#150f23` | `--color-recess` | surface | Code wells, darker than the surrounding canvas. |
| Input grey | `#cfcfdb` | `--color-input-edge` | border | Fine outline around white email fields. |
| White | `#ffffff` | `--color-white` | text, surface, action | Primary dark-theme text, resting primary actions and light explanatory bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product detail pages and light footers | Solid product purple | `#4e2a9a` | `--color-tile` | surface, link | Feature and use-case tiles; links in the white footer. |
| enterprise case studies | Proof gold | `#f5b944` | `--color-gold` | text, link | Case-study metrics and their text actions. |
| utility and product detail closings | Plum light | `#8d5494` | `--color-glow` | background | Soft bottom-centered illumination behind compact closing calls. |
| product detail FAQs | Pink-lilac hover | `#e2abe0` | `--color-faq-hover` | surface | Hover fill for white FAQ triggers. |
| pricing pages | Violet ink | `#362d59` | `--color-light-ink` | text | Pricing text and calculation totals. |
| pricing pages | Dusty violet | `#79628c` | `--color-soft-ink` | text | Pricing helper text. |
| enterprise pages | Muted violet | `#80708f` | `--color-muted` | text | Secondary explanations on white enterprise surfaces. |
| light chapters and enterprise pages | Near-black plum | `#181225` | `--color-dark-ink` | text, background | Text on white explanatory chapters and dark enterprise FAQ bands. |
| enterprise pages | Deep plum band | `#1b1228` | `--color-deep-band` | background | Enterprise hero and quantified-proof bands. |
| light utility surfaces | Light violet rule | `#ececf1` | `--color-light-edge` | border | Light calculator separators and quiet footer wave. |
| pricing pages | Lavender row wash | `#f2eff4` | `--color-stripe` | surface | Visible result of rgba(121,98,140,0.1) over white for alternating comparison rows. |

## Typography

- **Dammit Sans** — Expressive opening and chapter headings. Broad, rounded grotesk with assertive lowercase and a friendly, blunt silhouette. If unavailable, use **Rubik**. Use 500 for chapters and 700 for the hero; preserve the broad line lengths. Font stack: "Dammit Sans", "Rubik", sans-serif.
- **Rubik** — All supporting copy, controls, statistics, practical headings and footers. Rounded, sturdy sans that remains readable in dense technical copy. Font stack: "Rubik", -apple-system, system-ui, Segoe UI, Helvetica, Arial, sans-serif.
- **Monaco** (only for installation examples) — Readable command and code specimens. Even-width technical lettering, distinct from the marketing sans. If unavailable, use **IBM Plex Mono**. Font stack: "Monaco", "IBM Plex Mono", Menlo, Ubuntu Mono, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Dammit Sans | 700 | 88px | 1.2 | normal | Centered opening promise, including the pink inserted phrase. |
| chapter | Dammit Sans | 500 | 60px | 1.1 | normal | Two-part chapter headings and the default closing command. |
| hero-support | Rubik | 400 | 30px | 1.2 | normal | Centered opening description with room for two lines. |
| chapter-support | Rubik | 500 | 27px | 1.25 | normal | Conversational explanation below a chapter heading; inline technical links can be underlined. |
| closing-support | Rubik | 400 | 27px | 1.25 | normal | Centered default closing description. |
| card-heading | Rubik | 500 | 24px | 1.25 | normal | Feature captions and tile titles. |
| quote | Rubik | 400 italic | 20px | 1.25 | normal | Unboxed testimonials with compact line spacing. |
| body | Rubik | 400 | 16px | 1.5 | normal | Short feature descriptions and FAQ answers. |
| body-relaxed | Rubik | 400 | 16px | 2 | normal | Longer explanatory paragraphs and installation support copy. |
| footer-heading | Rubik | 600 | 16px | 1.5 | normal | Pink footer group titles. |
| action | Rubik | 700 | 14px | 16px | 0.014em, uppercase | Compact primary and secondary actions. |
| nav | Rubik | 500 | 14px | 18px | 0.014em, uppercase | Top-level navigation controls. |
| footer-link | Rubik | 500 | 14px | 18px | normal, uppercase | Footer destinations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| enterprise proof bands | stat | Rubik | 700 | 48px | 1.25 | normal | Centered organizational-scale metrics. |
| enterprise and product detail pages | practical-hero | Rubik | 500 | 40px | 1.25 | normal | Left-aligned, two-line promise beside a video. |
| pricing pages | pricing-hero | Rubik | 700 | 40px | 1.25 | normal | Centered pricing introduction. |
| enterprise white chapters | light-chapter | Rubik | 700 | 36px | 1.15 | normal | Short headings beside large product interfaces. |
| enterprise, pricing and product detail pages | utility-heading | Rubik | 500 | 32px | 1.25 | normal | FAQ, proof and compact closing headings. |
| pricing pages | plan-price | Rubik | 400 | 32px | 24px | normal | Short price or custom-price label; keep isolated from adjacent lines. |
| enterprise case studies | case-metric | Rubik | 700 | 28px | 1 | normal | Gold outcome figures inside proof cards. |
| enterprise FAQs | faq-dark-title | Rubik | 500 | 24px | 1.2 | normal | Question inside a violet outlined trigger. |
| pricing pages | plan-title | Rubik | 700 | 24px | 1.25 | normal, capitalize | Centered plan names. |
| product detail FAQs | faq-light-title | Rubik | 700 | 20px | 1.25 | 0.025em | Dark title on a white FAQ trigger. |
| pricing pages | comparison-category | Rubik | 700 | 16px | 2 | normal, uppercase | Section labels above groups of comparison rows. |

**Notes:**

- Keep tracking normal even in the biggest headings; the character comes from rounded width, line breaks and the pink interruption rather than fashionable negative tracking.
- The headline face is not used for body copy. Practical detail pages switch to Rubik headings instead of shrinking the expressive display into every role.
- A chapter heading commonly uses a white setup and a pink second-line payoff. Leave about 34.8px before its supporting paragraph.
- Action wrappers and their inner labels have slightly different line boxes; keep the rendered control at 40px rather than letting padding enlarge it.

## Layout

**Density:** Airy chapter pacing around dense, useful proof. Large pauses and broad media contrast with compact controls and captions.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small title-to-description gaps and compact grouped controls. |
| 16px | Paragraph separation, action-pair gaps and FAQ spacing. |
| 24px | Form and plan-card padding; gap from media to feature captions. |
| 32px | Container side padding and enterprise proof-card padding. |
| 40px | Capability-selector row gaps and closing support-to-action pause. |
| 48px | Two-column feature-grid gutters. |
| 64px | Utility-section vertical padding and hero-text-to-art pause. |
| 128px | Default large chapter spacing and closing-section vertical padding. |

### Containers and grids

- **container**: max width 1152px · side padding 32px. Centered desktop shell with 1088px of readable interior; shared by navigation, chapters and footer.
- **feature grid**: 2 columns · gap 48px. Two equally weighted product vignettes, each 520px wide at desktop, with caption below.
- **capability split**: 2 columns · gap 64px. Narrower text-selector column beside a larger interface image; a 597px media panel balances roughly 411px of text.
- **closing measure**: max width 704px. Centered closing headline, support and paired actions.
- **faq measure** (only for FAQ sections): max width 896px. Question stacks centered inside the main shell.
- **plan grid** (only for pricing pages): max width 1120px · 4 columns · gap 24px. Four equal 262px plan panels with aligned bottom actions.
- **enterprise proof grid** (only for enterprise pages): max width 1000px · 2 columns · gap 24px. Two outcome-rich case-study cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 8px |
|  | vignette frame | 12px |
|  | vignette inner | 10.6px |
|  | email field | 6px |
| enterprise case studies | case study | 16px |
| pricing pages | plan panel | 6px |
| pricing pages | calculator | 13px |
| product detail FAQs | light faq | 3px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | email inset | `inset 0px 2px 10px rgba(0,0,0,0.15)` | Subtle depth in a white email field. |
| pricing pages | calculator lift | `0px 8px 32px rgba(123,80,137,0.1)` | Soft purple lift for the white calculator. |
| product detail FAQs | faq ledge | `0px 2px 0px rgba(54,45,89,0.15)` | A thin bottom ledge, not a floating card shadow. |

### Surfaces

#### Dark canvas · level 0

**Use:** Default landing-page ground.

**CSS:** `background: #1f1633; color: #ffffff`

**Observed:** The dark canvas continues across most chapters instead of boxing every section.

**Transfer:** Use uninterrupted darkness as the default and let imagery and headline accents mark chapters.

#### Textured capability atmosphere · level 0

**Use:** A more saturated chapter ground behind framed vignettes.

**CSS:** `background: linear-gradient(#1f1633 0%, #30145f 52.4%, #30145f 100%)`

**Observed:** A repeat of small dark doodles and a grainy purple glow gives the band a printed, worked-on quality.

**Transfer:** Layer the texture described in Atmospheric workshop behind the content, keeping text areas clear.

#### Gradient vignette frame · level 1

**Use:** Edge around simplified technical illustrations.

**CSS:** `background: linear-gradient(to right in oklab, #fd44b0 0%, #c2ef4e 100%); padding: 2px; border-radius: 12px`

**Observed:** Only the media is framed; caption and supporting copy sit below on the page. Inner media is a dark 3:1 panel with 10.6px corners.

**Transfer:** Use the same thin multicolor perimeter for a product-specific diagram, not for every paragraph card.

#### Terminal well · level 1

**Use:** Installation command demonstration.

**CSS:** `background: #150f23; border-radius: 10px`

**Observed:** A 949px-wide desktop code area has a narrow language header with a white-at-10% bottom rule and a small copy control.

**Transfer:** Show one useful command or compact technical setup example.

#### White explanation band · level 0

**Only for:** enterprise and product detail pages

**Use:** Clear, practical product explanation between dark brand moments.

**CSS:** `background: #ffffff; color: #181225`

**Observed:** Large interface panels alternate sides with text; pink wavy separators punctuate the chapters.

**Transfer:** Use for extended evaluation content rather than changing the entire default landing page to white.

#### Case study glass · level 1

**Only for:** enterprise case studies

**Use:** Company quote followed by measured outcomes.

**CSS:** `background: linear-gradient(135deg, rgba(108,95,199,0.15), rgba(69,38,80,0.2)); border: 1px solid rgba(108,95,199,0.25); border-radius: 16px; padding: 32px`

**Observed:** A low-contrast purple translucent panel on a deeper plum band, without blur.

**Transfer:** Keep the company, quote, person, divided metric row and case-study link in that hierarchy.

#### Comparison stripe · level 1

**Only for:** pricing pages

**Use:** Alternating rows in a white feature comparison.

**CSS:** `background: rgba(121,98,140,0.1); padding: 4px`

**Observed:** Most rows are 48px tall; wrapped details create 50px, 72px or 80px rows.

**Transfer:** Let row content determine height while preserving aligned feature and plan columns.

#### Calculator panel · level 1

**Only for:** pricing pages

**Use:** White interactive estimate inside a dark atmospheric band.

**CSS:** `background: #ffffff; color: #1f1633; border-radius: 13px; box-shadow: 0px 8px 32px rgba(123,80,137,0.1)`

**Observed:** A top settings bar spans a three-part workspace: narrow category rail, wide volume/rate area and itemized total. Fine light dividers separate them.

**Transfer:** Use the same left-input-right-summary hierarchy for an appropriate interactive decision tool.

#### Closing glow · level 0

**Only for:** utility and product detail closings

**Use:** Soft illuminated ending above a white footer.

**CSS:** `background: radial-gradient(52.19% 95.83% at 50% 100.82%, #8d5494 0%, #1f1633 100%)`

**Observed:** Light rises from the bottom center, leaving the upper corners dark.

**Transfer:** Match the soft glow; exact stops are less important than the low, centered pool of light.

## Components

### Navigation

**Use:** Sticky top-level wayfinding across dark and light page variants.

**CSS:** `height: 72px; background: #1f1633; position: sticky; top: 0px; z-index: 50`

**Text style:** `nav` — Rubik 500 · 14px/18px · tracking 0.014em · uppercase

**Observed:** A white mark anchors the left, compact uppercase menu controls span the middle, and sign-in plus paired conversion controls anchor the right. Dropdown chevrons are small, not decorative badges.

**States:** Declared: hover menu background #6a5fc1 and text #ffffff; active uses the same fill and text.

**Transfer:** Preserve the restrained horizontal bar, not a floating pill navigation.

### Primary button

**Use:** Main conversion action.

**CSS:** `height: 40px; box-sizing: border-box; padding: 12px 16px; border: 2px solid transparent; border-radius: 8px; color: #1f1633; background-image: linear-gradient(120deg, #fa7faa 0%, #ff9691 25%, #ffb287 50%, #ffffff 55%, #ffffff 100%); background-size: 250% 100%; background-position: 98% 0px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Rubik 700 · 14px/16px · tracking 0.014em · uppercase

**Observed:** Reads as a white action at rest; the warm portion of the oversized gradient is parked outside the visible area. Width follows the label.

**States:** Declared: hover retains #1f1633 text; background-position and outline-width transition over 0.2s.

**Transfer:** Keep one visually dominant white action beside a secondary outline.

### Secondary button

**Use:** Demo, contact, sandbox or supporting action beside the main conversion.

**CSS:** `height: 40px; box-sizing: border-box; padding: 12px 16px; border-radius: 8px; color: #ffffff; background-image: linear-gradient(120deg, #c83852 0%, #b44092 25%, #6a5fc1 50%, rgba(0,0,0,0) 55%, rgba(0,0,0,0) 100%); background-size: 250% 100%; background-position: 98% 0px; position: relative`

**Text style:** `action` — Rubik 700 · 14px/16px · tracking 0.014em · uppercase

**Observed:** A masked pseudo-element supplies the warm red-to-magenta-to-violet perimeter while leaving the center transparent. Use an inset outline layer with the same corners; do not paint the entire control purple.

**States:** Declared: hover keeps white text; background-position and outline-width transition over 0.2s.

**Transfer:** On white utility chapters use dark text with the same fine gradient edge.

### Framed feature

**Use:** Compact capability proof with caption.

**CSS:** `display: flex; flex-direction: column; border-radius: 12px`

**Text style:** `card-heading` — Rubik 500 · 24px/1.25

**Observed:** Gradient vignette frame contains a simplified technical scene. The title starts 24px below the media; body text follows with an 8px visual gap. The whole text area is not enclosed in another border.

**Transfer:** Use a concrete product operation, a short outcome title and one supporting sentence.

### Capability selector

**Use:** Explain connected benefits beside a changing product detail.

**CSS:** `display: flex; flex-direction: column; gap: 40px`

**Text style:** `chapter-support` — Rubik 500 · 27px/1.25

**Observed:** Each row has a 4px vertical rail and inset text. Selected copy is white with a pink-to-lime rail; inactive rows are muted with violet rails. The text in the rows is 24px/30px regular rather than the heavier chapter introduction.

**Transfer:** Tie each row to one legible interface detail and use color plus text contrast for the active state.

### Open testimonial

**Use:** Human proof without a wall of framed cards.

**CSS:** `display: flex; flex-direction: column; gap: 20px; padding: 24px 32px 24px 0px`

**Text style:** `quote` — Rubik 400 italic · 20px/1.25

**Observed:** A tiny slanted warm-gradient quotation mark sits above italic copy. A small round company mark, person and role sit below. Default arrangement is three columns; product-detail pages use a two-column grid with small outline reading actions.

**Transfer:** Keep real words prominent and attribution compact.

### Newsletter panel

**Use:** A warm secondary conversion late in a long page.

**CSS:** `background: #422082; border-radius: 8px; padding: 24px`

**Text style:** `body` — Rubik 400 · 16px/1.5

**Observed:** Visible email label, full-width white field, consent checkbox, italic consent/legal line and small white submit button. A large cartoon machine occupies adjacent space. Product-detail variant uses a muted plum panel with peach-pink painted shapes behind it.

**Transfer:** Give the form a playful companion visual without compromising the plain field hierarchy.

### Email field

**Use:** Single-field newsletter signup.

**CSS:** `height: 42px; box-sizing: border-box; background: #ffffff; border: 1px solid #cfcfdb; border-radius: 6px; padding: 8px 12px; box-shadow: inset 0px 2px 10px rgba(0,0,0,0.15)`

**Observed:** The label sits above the input, not only inside a placeholder. Checkbox consent is separate below.

**Transfer:** Keep the input conventional and bright against its saturated form backing.

### Footer directory

**Use:** A substantial end-of-page navigation area.

**CSS:** `background: #1f1633; color: #ffffff; padding: 64px 0px 22px`

**Text style:** `footer-link` — Rubik 500 · 14px/18px · uppercase

**Observed:** Four unequal link columns use pink group headings and uppercase white links; a fine white wavy divider separates the directory from legal links, centered marks and right-aligned social icons. Copyright is centered below. Light variant uses white ground, dark titles, purple links and a pale wave, with a gold wave crossing the top boundary.

**States:** Declared: hover links underline and keep their theme color.

**Transfer:** Retain a real directory and the handcrafted wave rather than ending after the conversion button.

### Outlined FAQ

**Only for:** enterprise FAQs

**Use:** Objection handling on a near-black band.

**CSS:** `display: flex; align-items: center; justify-content: space-between; border: 2px solid #7553ff; border-radius: 8px; padding: 16px; color: #ffffff`

**Text style:** `faq-dark-title` — Rubik 500 · 24px/1.2

**Observed:** Wide question rows are 896px across at desktop with 16px between them; question at left and a small white down-chevron at right. Answers reveal underneath, not simultaneously inside every closed trigger.

**States:** Declared: hover border rgb(133,102,255); active transform scale(0.99).

**Transfer:** Use for procurement questions requiring a reassuring, technical tone.

### White FAQ

**Only for:** product detail FAQs

**Use:** Compact questions against a dark page.

**CSS:** `display: flex; align-items: center; background: #ffffff; color: #1f1633; border-radius: 3px; padding: 16px; box-shadow: 0px 2px 0px rgba(54,45,89,0.15)`

**Text style:** `faq-light-title` — Rubik 700 · 20px/1.25 · tracking 0.025em

**Observed:** A 57px single-line question strip contrasts sharply with the canvas. A small right-side chevron and stacked rows create a compact accordion.

**States:** Declared: hover background #e2abe0.

**Transfer:** Keep the practical white-strip variant scoped rather than making all dark-page cards white.

### Plan panel

**Only for:** pricing pages

**Use:** Side-by-side product tiers.

**CSS:** `background: #ffffff; color: #362d59; border-radius: 6px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between; gap: 16px`

**Text style:** `plan-title` — Rubik 700 · 24px/1.25 · capitalize

**Observed:** Centered tier name, short audience description and regular-weight price lead into a left-aligned check list. Actions align along the bottom. Paid trial controls are dark plum; the sales action remains outlined. Loose pink brush zigzags sit behind, never across the reading area.

**Transfer:** Keep equal-height tiers with honest feature differences and comparable price units.

## Imagery and graphics

### Atmospheric workshop

**Use:** Signature environment behind the opening and selected dark capability chapters.

**Observed:** Mottled, grainy violet light blooms within aubergine darkness; sparse tiny stars and hand-drawn crosses interrupt the haze. It feels printed and slightly scuffed, not like clean glass or a glossy abstract mesh.

**Transfer:** Retain this environment around a new product's own hero object. Minimum version is a grainy purple radial bloom, a few drawn spark marks and three useful product panels.

**Build:** Start with #1f1633. Add two overlapping violet radial ellipses centered behind the headline and art, using rgba(78,42,154,0.35), fading to transparent across about 65% of the section width. Overlay SVG fractal noise at low opacity with multiply or soft-light blending. Scatter small four-point crosses in rgba(255,255,255,0.2), avoiding text. For the capability band, repeat tiny dark outlined triangles, tools and rectangles on a 200px tile over the deeper #30145f gradient.

### Illustrated machine theatre

**Use:** Large opening object and playful late-page companion.

**Observed:** A purple cartoon operator with exaggerated hands, angular tools and neon lime details works amid floating interface panels. Other art shows a multi-armed pink creature operating a keyboard and a retro monitor with portal-like green rings. Dark purple contours, violet planes and speckled highlights keep it unified; art takes nearly full page width below the centered opening, or roughly half the width beside a form.

**Transfer:** Invent an original tool or machine metaphor for the product. Preserve angular purple construction, expressive poses and a few acid signals. Minimum acceptable art is a dimensional SVG machine with oversized control surfaces and floating product cards.

**Build:** Construct layered SVG polygons for a central tool body in #4e2a9a and lighter violet tints, dark #1f1633 edge shapes and #fd44b0 controls. Add two or three skewed interface rectangles to either side and narrow #c2ef4e beam triangles behind. Add a noise mask for tactile shading; keep the head or main control clear of the headline.

### Product vignettes

**Use:** Simplified capability media in Gradient vignette frame.

**Observed:** Wide 3:1 dark purple panels compress a terminal, root-cause explanation, trace tree or chat into only a few meaningful signals. Pink labels, violet lines and lime highlights make technical content legible without reproducing a whole screen.

**Transfer:** Reduce each new feature to one recognizable operation; use actual terminology and one useful text fragment.

**Build:** Draw a dark rounded SVG panel, a few purple rule bars, small circular status dots and one hot-pink label. Highlight one selected row or result with lime. Place inside the 2px pink-to-lime frame; leave the caption outside.

### Magnified interface proof

**Use:** Signature technical demonstration beside capability selectors.

**Observed:** A real interface occupies about 597×398px. A large circular detail lens overlaps it, outlined in purple and pink, with the relevant UI enlarged inside. The underlying interface is subdued so the selected evidence wins.

**Transfer:** Use a genuine product state and enlarge the decisive detail rather than presenting an unreadable full application.

**Build:** Place a rounded product image or authored UI panel on the dark canvas. Overlay a circular duplicate clipped with border-radius:50%, enlarge the duplicate around the chosen detail, and add a thick purple-to-pink ring plus a soft dark shadow. Size the lens to roughly half the media height.

### Handmade waves and paint

**Use:** Signature dividers and accents around utilitarian blocks.

**Observed:** A thin, slightly tilted pink wave separates white product chapters; white waves finish the dark footer and gold waves cross dark-to-white closing boundaries. Rough peach-to-pink brush marks peek from behind product forms, while loose pink and purple zigzags back the pricing tiers.

**Transfer:** Use a wave as a structural separator and reserve brush marks for secondary conversion or pricing areas. Keep the reading surface clean.

**Build:** Use an SVG path built from repeating shallow quadratic curves across a 729px chapter divider or 1088px footer rule; stroke about 2px with no fill. Rotate the chapter rule slightly. For paint, use broad angular SVG strokes with a turbulence/displacement mask, fill with a warm pink-to-apricot gradient and put behind the card, exposed at two corners.

### White chapter media

**Only for:** enterprise and product detail pages

**Use:** Longer practical explanation.

**Observed:** Large bright interface panels, generally about 608px wide, have restrained 8px corners and a faint grey outline. Some include purple sidebars or an overlay panel. Alternating left/right placement and ample white surround keep the flow editorial.

**Transfer:** Show authentic states with a clear focal task; prefer one meaningful panel over a collage of tiny windows.

### Icons

**Observed:** Small navigation chevrons use 14px SVGs with 2px round strokes. Product tile icons are white outlined 32px symbols with round ends and roughly 2.7px strokes; utility icons use 24px/2px. Tiny copy and check symbols use 16px filled forms.

**Transfer:** Choose simple functional symbols with the same round-ended geometry. Keep the neon personality in the illustrations rather than multicoloring every icon.

## Section recipes

How recurring sections are built.

### First screen: Illustrated promise opening

**Observed:** A 72px dark Navigation sits above a centered opening. An announcement chip starts after 64px of air, followed by a 48px pause before the 88px display promise spanning about 1004px. White words form one broad line at desktop; one inserted hot-pink phrase leans -7.5deg and dips below the baseline. The 30px support line wraps to two centered lines in roughly 653px. After about 61px, Primary button and Secondary button sit together. Another 64px opens onto a nearly full-width 1366×540px illustrated machine stage. Back-to-front: aubergine canvas, grainy violet atmosphere and stars, floating interface panels and central machine, text and actions. Within the first 900px, navigation, chip, headline, support, both actions and the upper portion of the main object are visible; the lower art and following proof continue below.

**Transfer:** Use a short product promise with one visually interrupting word or clause. Without bespoke art, make a substantial SVG tool-object and floating feature panels using Illustrated machine theatre; keep the art entering below the action pair. Enterprise and detail-page openings instead use a left 40px Rubik promise and a 608×353px video illustration at right with 64px vertical padding. Pricing opens with a centered 40px bold promise, billing toggle and tier panels.

**Avoid:** Do not replace the illustrated lower stage with a generic full-screen application window or cover the entire first screen with text; do not rotate the whole headline or apply a gradient to every word.

**Text style:** `display` — Dammit Sans 700 · 88px/1.2

### Heading with a pink answer

**Observed:** Left-aligned chapter heading uses chapter: white setup followed by a pink continuation, usually on a second line. The supporting paragraph is chapter-support and occupies roughly 70% of the content width; its technical nouns can be underlined links.

**Transfer:** Write a concrete assertion and use the second line to add attitude or resolve the assertion. Adapt the line break to the new phrase rather than forcing identical word counts.

**Text style:** `chapter` — Dammit Sans 500 · 60px/1.1

### Two-column capability cards

**Observed:** Textured capability atmosphere supports a two-column, 48px-gutter grid of Framed feature components. Media is 3:1, followed by a short title and compact body rather than a tall bordered text card.

**Transfer:** Group related benefits with four distinct visual operations, or a smaller complete set suited to the product.

### Connected product chapter

**Observed:** Heading with a pink answer and a broad supporting line lead into a 64px-gap split. Capability selector sits left and Magnified interface proof sits right. The active row has white text and a gradient rail; inactive copy recedes without disappearing.

**Transfer:** Explain a sequence of product benefits using one visible result at a time rather than three competing full-size images.

### Human proof constellation

**Observed:** An expressive chapter heading introduces three Open testimonial columns on the dark canvas. Tiny gradient quote marks, italic text and circular marks create rhythm without enclosing panels.

**Transfer:** Use authenticated short quotes with a named person and role; vary lengths naturally.

### Late-page invitation

**Observed:** A two-line expressive heading leads to Newsletter panel, with the field and submit at left and large comic art extending to the right. The form is not a full-width banner.

**Transfer:** Offer a modest, specific recurring value. Utility/detail variant splits a smaller heading and conversational paragraph from the form and places rough warm paint behind it.

### Closing command and directory

**Observed:** The default closing is centered in 704px with a 60px short command, 27px support, 40px pause before paired actions and 128px vertical padding. Footer directory continues the dark background with pink titles. Utility variants reduce the headline to 32px, use 64px padding and Closing glow, then cross a gold wave into the white directory. All variants end with a lower wavy rule, legal row, marks, social links and centered copyright.

**Transfer:** End on a brief action-oriented statement, not another feature list. Keep the full directory and handcrafted boundary treatment appropriate to the chosen theme.

**Text style:** `chapter` — Dammit Sans 500 · 60px/1.1

### Fast-start demonstration

**Only for:** products with a technical installation step

**Observed:** Heading and 27px support lead to a centered purple platform selector, a short reassurance line and Terminal well. Cartoon figures flank the wide command area, extending toward the page edges.

**Transfer:** Offer one selected platform and one meaningful copyable command. For non-code products, replace the command with an equally concrete first task and keep the illustrated flanks.

### Practical alternating chapters

**Only for:** enterprise and product detail pages

**Observed:** White explanation band uses a narrow text column with short bold subheads and relaxed paragraphs opposite a 608px interface. Successive chapters reverse the media side and use pink wavy rules. Detail pages can add three uppercase anchored tabs with a thin purple active underline.

**Transfer:** Use this variant for evaluation depth; preserve the clear text/media alternation rather than converting it into a generic card grid.

### Measured reassurance

**Only for:** enterprise pages

**Observed:** A centered 32px heading and support lead into four equal statistics using stat, with 24px labels. A following two-column Case study glass area pairs quotes with gold 28px outcome metrics and reading links. White support cards and a large trust illustration extend the reassurance into operational concerns.

**Transfer:** Use verified scale and outcome numbers with units, then explain the service and trust implications. Never use decorative random numbers.

### Dense pricing evaluation

**Only for:** pricing pages

**Observed:** Dark introduction with a billing switch leads to four Plan panel columns, a wide white add-on strip and a purple promotional strip. A white comparison area follows with category labels, a sticky repeated plan summary and alternating Comparison stripe rows. A dark purple atmospheric band contains the Calculator panel before the compact closing.

**Transfer:** Separate quick plan choice, detailed entitlements and usage modeling so each has a useful density and clear action.

## Page flow

**Storyline:** Promise and playful product theatre → concrete operations → human or measured proof → easier adoption and objections → a short conversion command → a useful directory.

### Broad brand and product introduction

1. **promise** — Centered expressive headline, understated support, paired actions and a large illustrated machine.
2. **social proof** — Illustrated spotlight and a horizontal customer-logo strip.
3. **capability chapters** — Framed feature vignettes followed by connected interface demonstrations.
4. **human proof** — Three unboxed italic testimonials.
5. **adoption** — Platform selector, command example and trust explanation.
6. **secondary conversion** — Newsletter form with comic companion art.
7. **closing call** — Short display command, support and paired actions, then dark directory.

**Transfer:** Use the broadest brand expression for a new landing page; select the proof and adoption blocks that fit the product.

### Reassure complex organizational buyers

1. **promise** — Split dark hero with audience eyebrow and video thumbnail.
2. **social proof** — Dark logo strip.
3. **capability chapters** — Alternating white text-and-interface stories divided by pink waves.
4. **quantified proof** — Four large scale figures and two translucent outcome cards.
5. **trust** — White support cards and a dedicated trust visual.
6. **objection handling** — Dark violet-outlined FAQ stack.
7. **closing call** — Compact illuminated conversion area followed by gold wave and white directory.

**Transfer:** Trade theatrical display scale for task clarity, operational detail and verified outcomes; retain the dark frame and hand-drawn punctuation.

### Help visitors compare commitment and cost

1. **pricing** — Centered dark heading, frequency toggle, four white tiers and a wide add-on panel.
2. **comparison** — Long white striped entitlement table with recurring plan headers and actions.
3. **decision tool** — Three-column calculator on a purple radial atmosphere.
4. **closing call** — Compact short command and paired actions above a gold boundary wave and white directory.

**Transfer:** Use a dense utilitarian variant without flattening brand color into every table cell. Keep the decision tool separate from static comparisons.

### Explain one focused product and how it fits existing work

1. **promise** — Dark split hero with practical headline and neon illustrated video.
2. **product demonstration** — Three anchored white workflow chapters with screenshots and pink dividers.
3. **capability summary** — Dark region with solid purple icon tiles in three- and two-column rows.
4. **human proof** — Unboxed two-column quotes and outline reading actions.
5. **objection handling** — White question strips on dark ground.
6. **further exploration** — Horizontal illustrated content cards and a circular next control.
7. **secondary conversion** — Conversational newsletter introduction beside a plum form with painted accents.
8. **closing call** — Bottom-lit compact command and white directory beyond a gold wave.

**Transfer:** Focus on a few real tasks, show the product where the user already works, then offer deeper reading without replacing the final conversion.

## Writing

Blunt, technically fluent and lightly irreverent. Confidence comes from naming real work and removing friction, while small asides and comic understatement keep the pitch human.

**Do not copy:** Do not reuse Sentry names, logos, mascots, artwork, customer marks, quotations, proprietary feature names, pricing, compliance assertions or numerical claims. Source examples illustrate rhythm only; supply the new product's own facts and original assets.

- **Addressing the reader:** Speak directly to you and your team. Use we for practical commitments and the product name when explaining what does the work.
- **Rhythm:** Headlines are short sentence fragments or commands. Support often runs one or two compact sentences; lists name concrete tasks. A sudden short sentence or parenthetical aside can puncture a longer technical explanation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the familiar problem, then snap to the desired outcome. | 4–9 words | “Code breaks, fix it faster”<br>“Let your issues fix themselves” |
| Support | Plain category description followed by a small skeptical wink. | One or two sentences | “Application monitoring software considered "not bad" by millions of developers.” |
| Chapter heading | A direct assertion, then a punchy continuation. | 2–10 words | “Developer first. Always.”<br>“Debug wherever you work.” |
| Adoption reassurance | Quantify the first step and immediately remove anticipated hassle. | 2–4 short sentences | “Five lines of code. That's it. No complex setup, no performance hits, no waiting around.” |
| Primary action | Verb-led, concrete and low ceremony. | 2–5 words | “Get Started”<br>“Try in sandbox” |
| Late-page invitation | Promise a modest cadence with a candid conversational aside. | A short heading plus a compact paragraph | “And yes, it really is monthly. Ok, maybe the occasional twice a month, but for sure not like one of those daily ones that you just tune out after a while.” |
| Closing command | Very short imperative that restates the product's job. | 2–6 words | “Fix It” |

**Words and phrasing to use:** fix; ship; context; in the flow; that's it; real work; plain-language task verbs; specific technical nouns

**Avoid:** revolutionary ecosystem; unlock unparalleled synergies; frictionless digital transformation; empty AI superlatives; forced slang in every line

**Rules:**

- Pair a benefit with the mechanism that makes it believable.
- Use humor as a small interruption, not as the whole explanation.
- Name the user's actual tools and workflow only when the product truly supports them.
- Use numbers for verified setup effort, scale or outcomes and preserve their units.
- Trust copy should be straightforward; keep comic exaggeration away from security and billing commitments.

## Do's and Don'ts

### Do

- Keep the default ground #1f1633 and reading text white; use pink for selected words rather than every heading.
- Keep the main display at 88px/1.2 and chapter display at 60px/1.1 on wide screens.
- Frame compact technical vignettes with a 2px pink-to-lime edge and 12px outer corners.
- Give paired conversion controls 40px height and 8px corners.
- Use 48px gutters for the two-column feature grid and 128px pauses for major default chapters.
- Use a 4px active gradient rail to connect benefit copy to the selected interface detail.
- Stage real product proof with a readable focal enlargement rather than relying on a full UI at thumbnail size.
- Finish with a compact command, usable footer directory and a fine wavy rule.

### Don't

- Do not turn every dark surface into neutral charcoal; preserve the purple bias of #1f1633 and #150f23.
- Do not fill whole sections with #fd44b0 or #c2ef4e; those are concentrated signals.
- Do not use 9999px pills for routine conversion buttons; pills belong to special media controls and toggles.
- Do not apply letter-spaced capitals to body copy; the uppercase treatment belongs to compact navigation, actions and categories.
- Do not put feature captions inside the gradient image border; their text sits below it.
- Do not add generic floating-card shadows to the default feature grid; its depth comes from artwork and perimeter color.
- Do not substitute stock office photography for the grainy purple tool theatre.
- Do not carry the white FAQ strip or four-tier pricing grid onto an ordinary new landing page without its scoped purpose.

## Motion and responsive

### Motion

**Observed:**

- Action gradient backgrounds declare background-position 0.2s and outline-width 0.2s transitions.
- The tilted hero phrase declares swingDown 0.75s ease.
- Horizontal logo movement declares scroll-x 60s linear.
- Capability rails declare opacity 0.3s cubic-bezier(.4, 0, .2, 1).
- White FAQ triggers declare background-color 0.25s; outlined FAQs declare border-color 0.3s and transform 0.2s.

**Transfer:**

- Keep motion focused on the tilted phrase, selected benefit signal and small gradient actions rather than moving every paragraph.
- Preserve a stable readable hero and meaningful static product scene when motion is disabled.

**Unknown:**

- The full choreography and timing of illustrated scenes and scroll-linked transitions are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 576px, 768px, 992px and 1152px; page-specific rules also use 640px and 1024px.
- The shared desktop container is 1152px with 32px side padding.

**Transfer:**

- Recommended: stack media beneath the centered promise while preserving the pink interruption and useful upper portion of the illustrated machine.
- Recommended: collapse paired chapter columns into media plus copy, keeping caption and framed image adjacent.
- Recommended: allow comparison tables to retain column alignment in an overflow region rather than crushing technical labels.
- Recommended: keep the two conversion actions together when possible and let the form fill the reading width.

**Unknown:**

- Exact mobile type sizes, mobile navigation behavior and narrow-screen art composition are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
