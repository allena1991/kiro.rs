# JetBrains — sculptural software confidence

## Overview

A dramatic technical marketing style where luminous purple sculptures float in deep black space and blunt grotesk headlines make ambitious promises. Dense, practical explanations sit inside orderly tinted panels, punctuated by white pricing cards and human testimony. It suits developer tools and capable business software; a cooler light-gray variant favors product discovery and interface demonstrations.

### Essentials

- Monumental names sit in front of luminous geometry: the default opening uses 142px/1, weight 600 type with -0.02em tracking over a purple, black-centered sculpture, followed by a 29px/39px light support line.
- Black is the breathing room, not a card color applied everywhere: #000000 grounds the default page, #19191c anchors navigation and footer, and 20% violet fills organize most feature panels. Saturated color concentrates in artwork, testimony, a highlighted noun and the selected purchase action.
- Actions are rounded capsules against rectangular information: main buttons are 52px high with 26px radii and 12px 32px padding; compact actions are 40px high with 20px radii. Use white for the primary action on dark sections and an outlined companion.
- Software gets a sculptural alter ego: repeat one purple layered object in the opening and later promotional or pricing art. Without custom 3D, construct overlapping gradient petals with dark centers and luminous rims; do not replace the device with an unrelated stock illustration.
- Hierarchy alternates loud claims with useful detail: 72px/1 chapter statements, 43px/49px section headings, 20px/28px semibold card labels and 16px/24px descriptions share one sans family. Proof numerals switch to a thin 69px/71px cut.
- Panels form a deliberate size hierarchy: 389px three-column cards or 600px half-width cards use 24px padding and 16px corners; full-width feature stages use 48px padding and 24px corners. A 32px gutter ties them together.
- The ending returns to persuasion before becoming infrastructure: a monumental closing promise or vivid resource destination leads into a charcoal directory with six desktop columns, 13px/20px links, a hairline divider, social utilities and locale controls.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet panel wash | `#151133` | `--color-panel` | surface | Visible 20% #6b57ff fill over black; feature and proof cards. |
| Electric violet text | `#af1df5` | `--color-highlight` | text, accent | A product name or emphatic noun inside an otherwise white headline. |
| Purchase purple | `#8d48ff` | `--color-purchase` | action | Recommended purchase button on a white pricing card. |
| Testimonial purple | `#850fba` | `--color-testimonial` | surface | Saturated top of testimonial cards, darkened toward the bottom. |
| Testimonial indigo | `#170c59` | `--color-testimonial-depth` | surface | Gradient overlay that shades purple testimonial cards. |
| Closing indigo | `#241961` | `--color-closing-depth` | background | Low end of the black-to-indigo closing form background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White foreground | `#ffffff` | `--color-white` | text, surface, action | Headings, primary capsules and bright pricing or case-study cards. |
| Muted white on charcoal | `#bababb` | `--color-footer-muted` | text | White at 70% over charcoal for directory links. |
| Muted white on black | `#b3b3b3` | `--color-muted` | text | Visible result of white at 70% on black for supporting copy; on charcoal the same alpha becomes #bababb. |
| Charcoal rule | `#474749` | `--color-footer-rule` | border | White at 20% over charcoal. |
| Dark-stage rule | `#333333` | `--color-rule` | border | White at 20% over black, used for subtle dividers and field edges. |
| Charcoal infrastructure | `#19191c` | `--color-charcoal` | background, surface, text | Navigation, footer and form fields; primary ink on white surfaces. |
| Black stage | `#000000` | `--color-canvas` | background | Default marketing canvas and dark cavities in artwork. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product discovery pages | Cool discovery canvas | `#e2e7ea` | `--color-light-canvas` | background | Light canvas with charcoal text and subtle linear texture. |
| ecosystem benefit grids | Solid ecosystem purple | `#693bd1` | `--color-ecosystem-purple` | surface | Solid violet benefit cards, more saturated than ordinary feature panels. |
| multi-audience overview pages | Audience pink | `#f31199` | `--color-portal-pink` | text, accent | Business-audience labels and monumental proof emphasis. |
| learning-platform proof bands | Learning green | `#21d789` | `--color-learning-green` | background | Bright top of a green-to-black customer band. |
| learning-platform sections | Learning purple | `#b74af7` | `--color-learning-purple` | background | Bright top of purple-to-black proof bands. |
| learning-platform sections | Learning purple depth | `#612186` | `--color-learning-depth` | background | Intermediate purple gradient stop. |
| learning-platform category icons | Learning icon green | `#1dd486` | `--color-icon-green` | accent | Green end of diagonal green-purple icon fills. |
| learning-platform category icons | Learning icon purple | `#b84bf8` | `--color-icon-purple` | accent | Purple end of diagonal category icon fills. |

## Typography

- **JetBrains Sans** — Marketing headings, descriptions, numbers, navigation and actions. Open geometric grotesk with broad round forms; firm semibold headlines contrast with light large descriptions and numerals. OpenType features: "calt", "kern", "liga". If unavailable, use **Inter**. Use weights 300, 400 and 600; preserve line breaks and tracking rather than increasing boldness. Font stack: "JetBrains Sans", Inter, system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif.
- **JetBrains Modul** (only for agent-product wordmark treatments) — Lowercase pixel-like wordmark within campaign headlines. Modular digital lettering, a distinctive identity accent rather than a body face. If unavailable, use **Pixelify Sans**. Use a light cut and keep it confined to a short identity line. Font stack: "JetBrains Modul", "Pixelify Sans", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | JetBrains Sans | 600 | 142px | 1 | -0.02em | Centered product-name opening; one short line at desktop. |
| chapter | JetBrains Sans | 600 | 72px | 1 | -0.005em | Major promise, pricing title and closing call; also a short highlighted phrase. |
| stat | JetBrains Sans | 300 | 69px | 71px | -0.005em | Survey percentages and large quantified proof. |
| heading | JetBrains Sans | 600 | 43px | 49px | -0.001em | Primary section headings and strong feature-panel headlines. |
| heading-small | JetBrains Sans | 600 | 35px | 1.2 | normal | Subsections, calculator questions and large destination-card titles. |
| lead | JetBrains Sans | 300 | 29px | 39px | normal | Hero support, generous introductory statements and large feature-panel prose. |
| body-large | JetBrains Sans | 400 | 20px | 1.4 | normal | Section support, large buttons and main navigation. |
| card-title | JetBrains Sans | 600 | 20px | 1.4 | normal | Feature names, author names and compact proof labels. |
| body | JetBrains Sans | 400 | 16px | 1.5 | 0.0015em | Card explanations, quotes, links and field labels. |
| caption | JetBrains Sans | 400 | 13px | 20px | 0.0045em | Role captions, directory links and compact supporting labels. |
| directory-title | JetBrains Sans | 600 | 13px | 20px | normal | Footer column titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| agent-product campaigns | campaign-wordmark | JetBrains Modul | 250 | 44px | 1 | normal, lowercase | Short identity line above a plain-language campaign promise. |
| cost calculators | price-result | JetBrains Sans | 300 | 40px | 1.1 | -0.005em | Comparison totals; strike through only the old total. |
| product discovery pages | discovery-label | JetBrains Sans | 600 | 28px | 34px | normal | Product-family label above the main promise and governance headings. |

**Notes:**

- Do not make all large text bold: 29px leads and 69px statistics use weight 300, while headings use 600.
- Most text uses normal or near-zero tracking; the 142px opening is the exception with -0.02em. Chapter text tightens only to -0.005em.
- Headlines use sentence case or the product's natural name. Small uppercase technical lettering is not a general eyebrow system.

## Layout

**Density:** Airy between narrative chapters, comfortable inside panels, and deliberately compact in the directory.

### Spacing

**Spacing system:**

- **flow** 24px, vertical — Declared prose flow unit; larger 48px and 96px pauses are two and four flow units.
- **horizontal-step** 8px, horizontal — Common gaps and padding; 32px is the main grid gutter, with 6px and 12px compact exceptions.

| Value | Use |
| --- | --- |
| 8px | Tight title-to-description spacing and icon/label groups. |
| 16px | Companion-action gap, compact card grids and internal rows. |
| 24px | Default card padding and heading-to-support gap. |
| 32px | Grid gutter, form-column gutter and action separation from short support. |
| 48px | Feature-stage padding and heading-to-grid separation. |
| 64px | Broad overview panel padding and footer top inset. |
| 96px | Major chapter bottom padding and footer bottom inset. |
| 192px | Vertical opening stage padding around the central composition. |

### Containers and grids

- **marketing-container**: max width 1276px · side padding 22px. Centered border-box container yielding 1232px of content and 104px side margins at a 1440px viewport.
- **feature-grid**: 3 columns · gap 32px. Three roughly 389px columns; switch to two 600px panels for longer explanations.
- **wide-feature**: 2 columns · gap 24px · side padding 48px. Full-width violet feature stage: explanation on one half, organized product or capability marks on the other.
- **pricing-cluster**: max width 811px · 2 columns · gap 16px. Two smaller comparison offers stacked on the left beside one tall recommended offer.
- **closing-form**: max width 705px · 2 columns · gap 32px. Centered paired fields; additional-details field spans the width. Closing heading and support can extend to 916px.
- **footer-directory**: 6 columns · gap 32px. Six 179px columns in the first row, remaining groups below with a 48px row interval.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary capsule | 26px |
|  | compact capsule | 20px |
|  | feature cards | 16px |
|  | feature stages and testimony | 24px |
|  | rich square panels | 32px |
| product discovery pages | discovery cards | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| testimony lift | `0px 16px 24px 0px rgba(0, 0, 0, 0.25)` | Saturated testimonial cards; not a universal elevation system. |
| field edge | `0px 0px 0px 1px rgba(255, 255, 255, 0.2) inset` | Charcoal form controls on dark backgrounds. |

### Surfaces

#### Black stage · level 0

**Use:** Default marketing page canvas.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Black space connects sections rather than enclosing every block in a new band.

**Transfer:** Let the canvas remain visible between colored chapters.

#### Charcoal infrastructure · level 0

**Use:** Global navigation and directory footer.

**CSS:** `background: #19191c; color: #ffffff`

#### Violet panel · level 1

**Use:** Capabilities and statistics.

**CSS:** `background: rgba(107, 87, 255, 0.2); border-radius: 16px; padding: 24px`

**Observed:** Flat translucent color without a drop shadow; larger full-width versions use more spacious construction.

**Transfer:** Keep this dark enough for white titles and muted descriptions.

#### Bright offer · level 1

**Use:** Purchase choices and long case-study stories.

**CSS:** `background: #ffffff; color: #19191c; border: 1px solid rgba(25, 25, 28, 0.2); border-radius: 24px`

**Observed:** White offers interrupt a purple art stage; case-study versions pair a square portrait with a wide text field.

#### Purple testimony · level 1

**Use:** Customer quotes.

**CSS:** `background-color: #850fba; background-image: linear-gradient(rgba(23, 12, 89, 0), #170c59 164.01%); border-radius: 24px; box-shadow: 0px 16px 24px 0px rgba(0, 0, 0, 0.25)`

#### Closing atmosphere · level 0

**Use:** Closing promise and inquiry form.

**CSS:** `background-image: linear-gradient(rgba(0, 0, 0, 0) 5%, #241961)`

**Observed:** A subtle full-width indigo rise under the centered closing headline, not a bounded card.

#### Cool discovery canvas · level 0

**Only for:** product discovery pages

**Use:** Lighter catalog and interface-led explanations.

**CSS:** `background: #e2e7ea; color: #19191c`

**Observed:** Faint oversized linear texture; white 8px-radius cards and translucent pale tiles replace the violet panel system.

**Transfer:** Keep the entire discovery page light rather than alternating it arbitrarily with the default dark theme.

#### Learning proof fade · level 1

**Only for:** learning-platform proof bands

**Use:** Broad customer or platform proof.

**CSS:** `background-image: linear-gradient(#21d789, #000000); border-radius: 24px; padding: 48px 0px`

**Observed:** A second band changes the top color to purple and passes through a dark-purple stop before fading to black.

## Components

### Primary button

**Use:** Main conversion action on a dark stage.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #19191c; height: 52px; padding: 12px 32px; border-radius: 26px`

**Text style:** `body-large` — JetBrains Sans 400 · 20px/1.4

**Observed:** Pairs with a transparent outlined companion. Compact variants use the body recipe and sit in navigation or secondary promotions; purchase cards reserve purple fill for the recommended offer.

**States:** Declared: hover outline none and text-decoration none; active outline none and text-decoration none. Color and background-color transition .1s ease.

**Transfer:** Use a concrete destination or next step, not a vague motivational slogan.

### Navigation action

**Use:** Global top-level navigation.

**CSS:** `display: flex; align-items: center; height: 72px; padding: 0px 10px; color: #ffffff; opacity: 0.7`

**Text style:** `body-large` — JetBrains Sans 400 · 20px/1.4

**Observed:** The identity mark sits at left; menu labels and small utility icons form a right-aligned row on Charcoal infrastructure.

**States:** Declared: hover color #fff, opacity 1 and text-decoration none; focus-visible color #fff, opacity 1, text-decoration none and outline none.

### Feature card

**Use:** Compact benefit and capability explanations.

**CSS:** `background: rgba(107, 87, 255, 0.2); border-radius: 16px; padding: 24px; color: #ffffff`

**Text style:** `card-title` — JetBrains Sans 600 · 20px/1.4

**Observed:** A large icon precedes the title; a short body paragraph follows, usually in muted white. Cards align into equal-width rows.

**Transfer:** Keep one benefit per card and use body for its explanation.

### Wide toolkit panel

**Use:** Explain a suite or group of capabilities.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr; gap: 24px; background: rgba(107, 87, 255, 0.2); padding: 48px; border-radius: 24px`

**Text style:** `heading` — JetBrains Sans 600 · 43px/49px · tracking -0.001em

**Observed:** Large title and body-large explanation occupy the left half. The right half is a tightly organized array of small black identity tiles, not an arbitrary illustration.

### Testimonial card

**Use:** Short attributed customer proof in an overflow carousel.

**CSS:** `background-color: #850fba; background-image: linear-gradient(rgba(23, 12, 89, 0), #170c59 164.01%); border-radius: 24px; padding: 24px; width: 390px; box-shadow: 0px 16px 24px 0px rgba(0, 0, 0, 0.25)`

**Text style:** `body` — JetBrains Sans 400 · 16px/1.5 · tracking 0.0015em

**Observed:** Circular grayscale portrait, author and smaller role caption sit above the quote. The next card peeks past the viewport; small previous/next circles and a fraction sit below.

**Transfer:** Use authentic, specifically attributed testimony; allow longer learning-platform cards at 604px with 32px padding and green or purple fades.

### Directory link

**Use:** Footer destinations and utility links.

**CSS:** `color: rgba(255, 255, 255, 0.7); padding-bottom: 1px; border-bottom: 1px solid transparent`

**Text style:** `caption` — JetBrains Sans 400 · 13px/20px · tracking 0.0045em

**Observed:** Directory-title headings precede vertically stacked links. Social links, country/language controls, legal links and copyright follow a horizontal rule.

**States:** Declared: hover text-decoration none.

### Pricing card

**Only for:** purchase sections

**Use:** Compare individual offers with the complete package.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; color: #19191c; border: 1px solid rgba(25, 25, 28, 0.2); border-radius: 24px; padding: 31px`

**Text style:** `lead` — JetBrains Sans 300 · 29px/39px

**Observed:** Identity and name first, period and price next, action below. The taller recommended offer adds a two-column inclusion list and a full-width purple purchase capsule. Billing frequency is a segmented control above the cluster.

### Form field

**Only for:** business inquiry sections

**Use:** Labeled paired text fields and selectors.

**CSS:** `display: flex; height: 40px; background: #19191c; box-shadow: 0px 0px 0px 1px rgba(255, 255, 255, 0.2) inset; color: #ffffff`

**Text style:** `body` — JetBrains Sans 400 · 16px/1.5 · tracking 0.0015em

**Observed:** Labels sit above the controls, not as floating text. Two columns of fields lead to one full-width 88px details area and a centered Primary button.

### Destination card

**Only for:** multi-audience overview endings

**Use:** Offer several distinct next steps before the directory.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; border: 2px solid rgba(255, 255, 255, 0.4); border-radius: 24px; padding: 24px`

**Text style:** `heading-small` — JetBrains Sans 600 · 35px/1.2

**Observed:** Small monochrome icon above a short two-line heading; outlined capsule at the bottom. Four 284px cards share one row.

## Imagery and graphics

### Luminous layered sculpture

**Use:** Signature opening object and recurring promotional or pricing art.

**Observed:** A black-centered spherical rosette is made of many overlapping translucent purple lobes with hot magenta rims. It floats without a horizon or visible pedestal. In the opening it is roughly 700px across behind the type; later it is enlarged and clipped to the edge of a banner or rises behind white offer cards.

**Transfer:** Create one original repeated geometric object and reuse it at different scales. The minimum is a carefully shaded overlapping petal rosette, not a flat purple disk or a generic blurred glow.

**Build:** In an SVG viewBox of 800 by 800, place 16–24 elliptical petal paths around the center, each rotated by an equal angle. Shade each from rgba(175,29,245,0.9) at its exposed rim through rgba(107,87,255,0.35) to rgba(0,0,0,0.98) toward its inner edge. Offset successive petals slightly and overlap them to suggest a woven shell. Add a black radial center mask, subtle purple edge strokes and a faint 12px purple blur behind the perimeter. Render at about 700px across; keep text above it.

### Rich feature squares

**Use:** Large paired explanations between quieter utility cards.

**Observed:** Two 600px square panels carry light 29px prose above dark product-interface cutouts. Their 32px corners enclose luminous blue-violet fields, soft grain and sparse bright speckles; the art blends into the underlying tint.

**Transfer:** Use a genuine interface detail under a short capability statement. Keep the art atmospheric, with most bright particles away from the text.

**Build:** Layer a violet radial gradient across the square over the Violet panel. Add SVG turbulence at low opacity for fine grain and a sparse field of 1–3px white circles at varied opacity. Clip the result to 32px corners and anchor a dark 24px-radius interface panel near the lower edge.

### Product interface stages

**Use:** Concrete demonstrations and workflow chapters.

**Observed:** Dark editor windows are shown as crisp rectangular images with their own window chrome; learning dashboards can stay white. Large images often occupy about two thirds of a split layout while compact capability explanations sit alongside. The light discovery theme backs interfaces with muted teal textured fields.

**Transfer:** Use real interface content at readable scale, framed as working software rather than a tilted device mockup. Do not turn internal syntax colors into marketing palette tokens.

### Human proof imagery

**Use:** Attributed testimonials and case studies.

**Observed:** Small testimonial portraits are circular and grayscale. Large case-study portraits are full-color square images occupying roughly one third of a white horizontal story card.

**Transfer:** Use natural portraits without a universal purple duotone.

### Rotating slab fan

**Only for:** ecosystem marketing pages

**Use:** Oversized opening background, corner decoration and community closing artwork.

**Observed:** Thick rounded square slabs in electric violet, deep blue and magenta fan across black. Fine grain and lit beveled edges make them tangible. The closing composition brings the fan up from the bottom with a purple glow and a thin oversized outline illustration behind it.

**Transfer:** Use layered rounded slabs to symbolize breadth or connected capabilities, with an original outline motif appropriate to the new product.

**Build:** Stack 10–16 rounded rectangle SVG shapes, rotate each progressively around a common lower pivot, and scale them toward one end. Use deep indigo interiors, violet-to-magenta edges and a 1px lighter rim. Overlay low-opacity SVG noise. For the ending, place the fan below the resource cards and a 2px pale outline drawing behind the front slabs.

### Learning ribbon atmosphere

**Only for:** learning-platform marketing pages

**Use:** Opening backdrop, demonstration glows and closing purchase band.

**Observed:** Wide folded purple ribbon forms converge behind the opening; later mint-green and purple glow fields connect interface chapters. The ending uses repeated vertical rounded strips, purple faces and mint tips behind black offer panels.

**Transfer:** Carry green-purple color through proof, icons and closing artwork rather than adding a disconnected green button style.

**Build:** Create 6–10 broad SVG ribbon strips with rounded ends, overlapping at varied heights. Fill each vertically from mint green through violet to black, with purple side faces. Add broad blurred green and purple ellipses behind the interface chapters; keep their centers away from body text.

### Painterly campaign scene

**Only for:** agent-product campaigns and discovery update bands

**Use:** Editorial alternative to sculptural product artwork.

**Observed:** People at computer workstations appear in pointillist, slightly rough-edged scenes backed by desaturated teal. A wide scene can fill the opening media frame or sit behind white news cards.

**Transfer:** Commission an original work scene with a stippled or painterly treatment. Keep this distinct from the default black-and-purple sculptural opening.

### Icons

**Observed:** Navigation utilities are small 20px filled SVGs; content icons step up to 48px or 64px. Feature symbols are usually white on dark panels; product identity marks are multicolored and sit on black tiles. Learning categories use green-purple gradient masks.

**Transfer:** Choose simple monochrome symbols for capabilities and maintain consistent visual mass. Use original product marks only where identity is the subject; avoid making every utility icon a multicolor badge.

## Section recipes

How recurring sections are built.

### First screen: Sculptural product opening

**Observed:** A 72px Charcoal infrastructure navigation bar sits above an 816px black stage. Back to front: black canvas, a roughly 700px luminous rosette centered behind the copy, a compact audience switch, a 142px display product name across the middle, a 29px/39px lead constrained to about 916px, and a centered pair of actions separated by 16px. The support follows the title by 24px and the actions follow by 48px. The product name occupies roughly two thirds of the viewport width and overlaps the sculpture without a containing card. The complete object, headline, support and buttons are visible within the first 900px; the next proof heading only begins at the lower edge.

**Transfer:** Use the Luminous layered sculpture recipe for an original product object and fit a short product name or promise over its dark center. A discovery page instead opens left-aligned on Cool discovery canvas with a 28px family label, a 43px promise, a dark capsule and a broad interface stage beginning below. Learning and ecosystem pages use left-aligned 72px promises with oversized ribbon or slab art behind and to the right.

**Avoid:** Do not shrink the opening into a conventional left-copy/right-small-icon split, put the title inside a card, or let a bright center destroy text contrast.

**Text style:** `display` — JetBrains Sans 600 · 142px/1 · tracking -0.02em

### Promise heading and panel family

**Observed:** A chapter heading can emphasize one noun in electric violet. A Wide toolkit panel follows after 48px, then paired Rich feature squares and a smaller Feature card grid extend the explanation. Ordinary section headings use heading with a 24px support gap and 48px before the main group.

**Transfer:** Vary panel size according to the depth of the argument; do not merely repeat identical cards for every capability.

**Text style:** `chapter` — JetBrains Sans 600 · 72px/1 · tracking -0.005em

### Quantified proof strip

**Observed:** Three Violet panels display stat numerals above muted body explanations. The numbers are thin rather than bold and use only 4px separation from their explanations. A broad customer-logo row is monochrome, with logos about 56px tall.

**Transfer:** Use verifiable measurements with a clear denominator or explanation. Broader overview pages can turn one key number into a 72px colored line embedded in a white statement.

**Text style:** `stat` — JetBrains Sans 300 · 69px/71px · tracking -0.005em

### Cost calculator

**Observed:** A heading and 29px lead introduce a practical tool. A modest disclaimer strip precedes a 35px question and a long 5px multicolor slider. Its 24px circular handle has a white edge; tick labels sit above, a numeric input below-left, and two 40px totals align at right. The old total is struck through, then a divider and Primary button finish the section.

**Transfer:** Translate into a meaningful workload, savings or capacity calculator. Label assumptions and units; make the input control real rather than ornamental.

**Text style:** `heading` — JetBrains Sans 600 · 43px/49px · tracking -0.001em

### Purchase stage

**Observed:** A centered 72px title and lead sit above billing controls and the pricing-cluster layout. Bright offer cards stand against an enlarged sculpture and a black-to-indigo background. Smaller upgrade guidance follows rather than competing inside the offer headline.

**Transfer:** Make the recommended choice structurally taller through useful inclusion detail, not just a colorful badge.

**Text style:** `chapter` — JetBrains Sans 600 · 72px/1 · tracking -0.005em

### Human story carousel

**Observed:** A 35px heading introduces a wide white story panel with 24px corners. A full-color square portrait takes the left third; quote, author, muted role and bottom-aligned text action occupy the rest. The following card peeks at the right and arrows with a fraction sit underneath.

**Transfer:** Use this for deeper case studies; reserve Testimonial cards for shorter, faster proof.

**Text style:** `heading-small` — JetBrains Sans 600 · 35px/1.2

### Closing promise and inquiry

**Observed:** Closing atmosphere supports a centered 72px promise, muted 20px support and a 705px Form field grid. The title can break into two balanced lines. A full-width details field, centered Primary button and small consent text complete the form before the charcoal directory begins.

**Transfer:** For consultative products, end with a useful inquiry rather than a generic signup stripe. Keep the form narrower than the headline.

**Text style:** `chapter` — JetBrains Sans 600 · 72px/1 · tracking -0.005em

### Community and resource ending

**Only for:** ecosystem pages

**Observed:** A 43px heading and muted 20px support introduce three outlined resource cards with 16px corners and 24px padding. Below them, oversized slab artwork and an outline illustration fill the final space before the footer.

**Transfer:** Use three continuing-engagement destinations and a substantial artistic finish instead of forcing a sales form onto a community page.

**Text style:** `heading` — JetBrains Sans 600 · 43px/49px · tracking -0.001em

### Learning commerce ending

**Only for:** learning-platform pages

**Observed:** A full-width ribbon atmosphere backs a split close: 43px heading, 29px support and two capsules at left; a black 24px-radius subscription panel at right. A long black secondary-service strip spans below the pair, ending with a compact white action.

**Transfer:** Use this for one principal subscription plus a genuinely separate guided service, keeping both legible against the vivid backdrop.

**Text style:** `heading` — JetBrains Sans 600 · 43px/49px · tracking -0.001em

### Discovery questions and directory

**Only for:** product discovery pages

**Observed:** Governance proof and a heading-led FAQ conclude the light content. Questions form two 600px columns with 32px gutters and 52px rows, semibold 20px text and plus controls. The page then changes directly to the dark directory footer.

**Transfer:** Close a catalog by resolving selection and trust questions, not by inserting the business inquiry form automatically.

**Text style:** `heading` — JetBrains Sans 600 · 43px/49px · tracking -0.001em

## Page flow

**Storyline:** Promise → tangible product breadth → capability explanation → measurable and human proof → practical choice or next step → purpose-specific close → directory.

### Flagship business product landing

1. **Promise** — Centered monumental name over a luminous sculpture with paired conversion actions.
2. **Social proof** — Large trust statement and monochrome company marks.
3. **Capability chapters** — Wide toolkit panel, rich square features, utility cards, security band and percentage cards.
4. **Quantified value** — Interactive cost estimator with explicit assumptions and comparison totals.
5. **Human proof** — Saturated quote carousel, followed by deeper capability and subscription comparisons.
6. **Purchase choice** — White pricing cluster over enlarged purple sculpture.
7. **Objection handling** — Lifecycle support cards, large portrait case studies and compact organizational proof.
8. **Closing call** — Monumental centered promise and labeled inquiry form over indigo atmosphere, then directory.

**Transfer:** Use the strongest all-round default for a substantial technical product; keep practical decision tools where the buying process warrants them.

### Multi-audience portfolio overview

1. **Campaign hook** — Painterly full-width media, compact identity promise and audience tabs with product demonstrations.
2. **Audience chapters** — Repeated audience label, 72px promise and broad nested product panels; charcoal, teal and pink distinguish groups.
3. **Product proof** — Long interface-led explanation with a slim vertical progress rule and large inline trust numeral.
4. **Organizational proof** — Monumental pink count and muted logo row.
5. **Closing navigation** — Four outlined destination cards, then the shared directory and utilities.

**Transfer:** Use audience color as chapter navigation and end with several useful paths rather than a single forced conversion.

### Ecosystem story and resource gateway

1. **Promise** — Left-aligned large promise over an oversized grainy slab fan and three broad benefit statements.
2. **Product breadth** — Inset violet-tinted field containing a three-column tool grid with one gradient-highlighted card.
3. **Benefits** — Solid purple six-card benefit grid with corner artwork.
4. **Adoption proof** — Two-column outlined quote cards and a white action.
5. **Future direction** — Long-form vision beside four square platform tiles.
6. **Continuing engagement** — Three resource cards above an oversized illustrated slab-art finale, then directory.

**Transfer:** Explain connected parts without making every part equally prominent; finish with ways to participate or learn.

### Product discovery and selection

1. **Promise** — Cool-gray opening, restrained family label, compact promise and large editor demonstration.
2. **Workflow demonstration** — White image cards, split explanation panels and translucent percentage tiles over a media backing.
3. **Selection** — Language-filter controls above a dense three-column product grid.
4. **Social proof** — Compact white quote grid.
5. **Freshness** — Painterly update backdrop with white article cards.
6. **Objection handling** — Security badges and two-column FAQ before the dark directory.

**Transfer:** Keep the lighter theme and denser grids for comparison tasks, not as a random alternate section color.

### Learning-platform organizational sale

1. **Promise** — Left-aligned product identity and large benefit over purple ribbon art, followed by a broad video stage.
2. **Authority** — Expertise statement, green-fading customer band and purple-fading platform statistics.
3. **Breadth** — Three-column charcoal category cards with gradient icons and paired counts.
4. **Business case** — Large thin percentages and actionable benefit lists.
5. **Demonstration** — Alternating large interface images and vertical feature tabs across green-purple glows.
6. **Social proof** — Wide gradient quote cards in an overflow carousel.
7. **Purchase close** — Ribbon-backed split subscription offer and secondary service strip, then shared directory.

**Transfer:** Connect learning breadth to business outcomes and make the subscription ending visually distinct from a sales inquiry.

## Writing

Confident and technically literate, but focused on the reader's freedom, productivity and confidence rather than spectacle for its own sake. Practical details and measurable proof follow broad promises.

**Do not copy:** Do not reuse JetBrains names, logos, proprietary artwork, customer identities, testimonials, Fortune claims, prices, percentages or other business facts. Source quotations below illustrate voice only; replace them with truthful content for the new product.

- **Addressing the reader:** Address the reader as you or your team. Use we for accountable product expertise; name the product when explaining specific capabilities.
- **Rhythm:** Short sentence-case promises alternate with one or two complete explanatory sentences. Headings are usually 3–9 words; technical support can be longer but stays direct. Actions are compact verbs plus an object.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Assert a benefit and leave room for reader agency; two short clauses work well. | 4–9 words | “Build Across Platforms. Your Way.”<br>“Code your way. Ship with confidence.” |
| Section heading | Name the practical outcome or pose the buyer's next question. | 4–9 words | “Estimate the costs for your team”<br>“Solutions that scale with you as you grow” |
| Supporting explanation | Turn a capability into a concrete workflow benefit, naming relevant technical mechanisms. | 1–2 sentences | “Run, debug, and test your applications without leaving the IDE or the code view. All important tools are within reach.” |
| Primary action | Verb plus an explicit next step. | 2–4 words | “Request a quote”<br>“Find your IDE”<br>“Try for free” |
| Closing promise | A direct positive outcome for the team, not artificial urgency. | 5–8 words | “Set your team up for success”<br>“Unlimited learning for your team” |

**Words and phrasing to use:** build; your team; choose; confidence; built-in; integrated; code quality; workflow; scale; maintainable; without

**Avoid:** magic; 10x everything; revolutionary disruption; crush the competition; hurry; !!!

**Rules:**

- Lead with the outcome, then explain the mechanism in plain technical language.
- Pair quantified claims with a clear population, period or assumption.
- Keep acronyms in feature explanations, not as unexplained hero promises.
- Give companion actions a different intent: a conversation beside pricing, or trial beside an explanation.

## Do's and Don'ts

### Do

- Keep the main content aligned to the 1232px inner width at a 1440px desktop viewport.
- Use the 142px display only for the opening; use 72px for major promises and 43px for ordinary chapters.
- Preserve 32px gutters across feature grids and paired form fields.
- Use weight 300 for large leads and statistical numerals to contrast with 600-weight headings.
- Make vivid sculpture recur at a different scale in a later banner or purchase stage.
- Use 16px corners for ordinary feature cards and 24px for larger stages and quote cards.
- Leave 96px chapter pauses so dense product information does not become a continuous dashboard.
- Keep main actions white on black and reserve purple purchase fill for a recommended white offer card.

### Don't

- Do not make every paragraph white at full opacity; support is normally white at 70%.
- Do not replace the capsule system with 8px-radius rectangular primary buttons.
- Do not apply drop shadows to ordinary violet cards; their separation comes from tint and black gutters.
- Do not turn all statistics into semibold heading text; use the thin 69px recipe.
- Do not introduce monospace as the general technical marketing font; the primary text is a geometric sans.
- Do not combine green learning bands, pink audience labels and the cool discovery canvas indiscriminately on one default landing page.
- Do not shrink white pricing offers into generic equal-height three-card plans when a package-versus-parts comparison is the story.
- Do not finish with only a tiny copyright row; the directory has a real column hierarchy and a separate utility zone.

## Motion and responsive

### Motion

**Observed:**

- Primary capsules declare color .1s ease and background-color .1s ease transitions.
- Global navigation declares opacity .1s; hover and focus-visible restore opacity to 1.
- Carousel layouts expose horizontally overflowing content with controls and scroll-snap alignment.

**Transfer:**

- Keep interactive color changes quick and understated so the luminous artwork remains the main visual event.
- Use visible partial next cards to communicate horizontal continuation.

**Unknown:**

- Artwork animation timing, autoplay behavior and scroll choreography are not specified.
- Reduced-motion behavior is not established.

### Responsive

**Observed:**

- Desktop layout uses a 1276px container with 22px side padding.
- Business and learning CSS includes width breakpoints at 640px, 1000px, 1001px, 1276px and additional intermediate widths; breakpoint-specific visual behavior is not established.

**Transfer:**

- On narrow screens, prioritize the product promise and actions over the sculpture: scale the art as one coherent object behind the text rather than shrinking its petals separately.
- Stack split feature stages and form columns while preserving text-before-demonstration reading order. Keep carousels as horizontally continuing cards.
- Reduce the monumental title to fit the new name without clipping or forcing letter-by-letter wrapping; maintain the 600 versus 300 weight contrast.

**Unknown:**

- Exact mobile type sizes, navigation collapse, container margins and breakpoint mapping are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
