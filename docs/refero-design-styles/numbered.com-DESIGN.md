# Numbered — image theatre, monumental signatures

## Overview

An image-led editorial style with the confidence of a fashion campaign and the restraint of a gallery. Near-black and white frame richly tactile photography, while regular grotesk text contrasts with an enormous, high-contrast serif signature. It suits design-conscious products, creative services and premium commerce, with very little interface chrome and expansive pauses between visual statements.

### Essentials

- Identity behaves like a magazine masthead, not a corner logo: a white serif word-image spans 1200px within a 1440px canvas, about 204px high, and returns at monumental scale in the closing area. Make an equally prominent word-image for the new identity.
- The first screen is a campaign, not a pitch deck: edge-to-edge 1440×900 photography, a masthead across the upper third, a single centered 15px bold uppercase contact link and a 22px centered descriptor near the bottom. The explanatory 75px statement follows below the fold.
- The interface is almost entirely unboxed: actions are uppercase text, with 3px underline clearance rather than filled buttons, pills or elevated cards. Use 15px actions and 13px/2 footer links; reserve weight 700 for the persistent contact action.
- Color belongs to the work rather than the chrome: near-black #0e0e0e and white #ffffff govern text bands and navigation, while photographs occupy entire viewport-width panels or two flush 720px columns. Keep colored material inside those image fields; use a light full-width chapter only for a deliberate case-study or institutional variant.
- Words alternate between manifesto and marginalia: 75px/1 regular sentence-case introduction, 55px/1 centered statements, 55px/1 uppercase chapter headings and 15px/1.5 uppercase captions. Tracking stays normal, so scale and casing do the separating.
- Proof is staged as an uninterrupted visual exhibition: full-width scenes alternate with flush paired portraits, captions sit 40px from the left and 35px from the top, and centered text interludes have 180px above and below. If campaign assets are unavailable, make tightly lit material or product close-ups rather than substituting a feature-card dashboard.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, background, link | Primary text, word-images and link underlines on dark ground; full-width light chapter background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black canvas | `#0e0e0e` | `--color-canvas` | background, text | Default page ground and text on light chapters. |
| Dark-ground rule | `#4f4f4f` | `--color-rule` | border | Single-pixel boundary above the closing navigation. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| institutional directories | Muted text on white | `#868686` | `--color-muted-light` | text | Secondary directory text: near-black at 0.5 opacity over white. |
| institutional directories | Muted text on dark | `#878787` | `--color-muted-dark` | text | Secondary directory text: white at 0.5 opacity over the near-black ground. |
| warm-toned product case studies | Warm mineral panel | `#e4ded9` | `--color-warm-panel` | background, surface | Full-width backing for a warm-toned product's responsive demonstrations. |
| recognition sections | Light-ground rule | `#e6e6e6` | `--color-light-rule` | border | Visible hairline from black at 0.1 opacity over white in recognition rows. |
| institutional proof statements | Oval outline | `#e7e7e7` | `--color-oval-rule` | border | Visible outline from rgb(13,13,13) at 0.1 opacity over white. |

## Typography

- **aktiv-web** — All editorial text, navigation, headings and captions. Neutral neo-grotesk with open counters, regular stroke weight and unforced spacing. If unavailable, use **Roboto**. Use 400 for almost everything and 700 only for the persistent contact action. Font stack: "aktiv-web", "Roboto", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Arial** — Centered descriptor action within the photographic opening. Plain utilitarian sans that remains subordinate to the signature artwork. Font stack: "Arial", Helvetica, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| manifesto | aktiv-web | 400 | 75px | 1 | normal | size 5.2083333333vw | Large left-aligned introductory statement below the first screen. |
| statement | aktiv-web | 400 | 55px | 1 | normal | size 3.8194444444vw | Centered prose interludes separating image groups. |
| chapter | aktiv-web | 400 | 55px | 1 | normal, uppercase | size 3.8194444444vw | Short section headings, often broken over two lines; also case-study titles. |
| closing-heading | aktiv-web | 400 | 25px | 1.2 | normal, uppercase | size 1.7361111111vw | Compact closing invitation above the contact address. |
| action | aktiv-web | 400 | 15px | 1 | normal, uppercase | size 1.0416666667vw | Small editorial actions beside headings or after a manifesto. |
| persistent-contact | aktiv-web | 700 | 15px | 1 | normal, uppercase | size 1.0416666667vw | The centered persistent contact action. |
| media-caption | aktiv-web | 400 | 15px | 1.5 | normal, uppercase | size 1.0416666667vw | Two-line name and discipline caption over media. |
| footer-link | aktiv-web | 400 | 13px | 2 | normal, uppercase | size 0.9027777778vw | Closing navigation, social links and address lines. |
| micro-action | aktiv-web | 400 | 12px | 1 | normal, uppercase | size 0.8333333333vw | Newsletter action in the bottom line. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| institutional pages | monumental-proof | aktiv-web | 400 | 90px | 1 | normal, uppercase | size 6.25vw | Oversized centered proof statement inside an ellipse and image-backed institutional closing heading. |
| case studies | case-chapter | aktiv-web | 400 | 55px | 1.1 | normal, uppercase | size 3.8194444444vw | Heading beside a stacked image demonstration. |
| institutional pages | institutional-introduction | aktiv-web | 400 | 54px | 1.1 | normal | size 3.75vw | Wide editorial introduction beneath a masthead on dark ground. |
| institutional directories | directory-heading | aktiv-web | 400 | 50px | 1 | normal, uppercase | size 3.4722222222vw | Left-hand heading alongside grouped lists. |
| case studies | case-introduction | aktiv-web | 400 | 35px | 1.15 | normal | size 2.4305555556vw | Substantial project-context paragraph in a narrower column. |
| institutional proof and directories | directory-title | aktiv-web | 400 | 25px | 1 | normal, uppercase | size 1.7361111111vw | Category titles and unembellished recognition rows. |
| technical case-study chapters | technical-body | aktiv-web | 400 | 20px | 1.25 | normal | size 1.3888888889vw | Longer technical explanation on dark ground beside a portrait. |
| collection indexes | filter | aktiv-web | 400 | 20px | 1 | normal, uppercase | size 1.3888888889vw | Centered taxonomy navigation beneath the masthead. |
| case studies | case-body | aktiv-web | 400 | 15px | 1.6 | normal | size 1.0416666667vw | Compact explanatory prose beneath light-chapter headings. |
| case studies | service-label | aktiv-web | 400 | 15px | 1.33 | normal, uppercase | size 1.0416666667vw | Stacked role and service labels below a project introduction. |
| institutional directories | directory-item | aktiv-web | 400 | 15px | 2 | normal, uppercase | size 1.0416666667vw | Dense secondary lists beneath directory titles. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Maintain regular weight and normal tracking throughout the editorial scale. Use sentence case for prose statements and uppercase for functional headings, labels and actions.
- The signature is high-contrast serif vector lettering, not the 75px grotesk manifesto. Preserve the strong distinction between identity artwork and reading text.
- Desktop rem dimensions follow the viewport root rule calc(.0694444444vw - 0px / 1440); the scales express the resulting size relationships. Adapt narrow-screen reading sizes independently rather than shrinking every label indefinitely.

## Layout

**Density:** Airy in editorial bands and image transitions; deliberately dense in small utility lists. Large media fields carry far more area than interface text.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Gap below stacked case-study service labels. |
| 20px | Space between directory titles and tightly related content, and side margins of taxonomy items. |
| 25px | Chapter heading to supporting paragraph; directory title spacing. |
| 35px | Top inset of image captions and gap before the case introduction. |
| 40px | Left inset of over-image captions. |
| 50px | Space before the closing bottom line. |
| 60px | Manifesto-to-action space, closing word-image top margin and directory column separation. |
| 80px | Closing navigation top padding and bottom-line bottom padding. |
| 96px | Upper inset of the opening word-image. |
| 110px | Space below the heading pair before the image exhibition. |
| 120px | Primary side inset and repeated spacing between case-study media. |
| 130px | Top and bottom padding of light demonstration chapters. |
| 180px | Top and bottom margins around centered editorial interludes. |
| 350px | Extended pause between the introductory action and the exhibition heading. |

### Containers and grids

- **editorial-container**: max width 1200px · side padding 120px. At 1440px, wide prose, the signature and closing content share the same side alignment. This is a proportional inset rather than a fixed maximum-width shell.
- **statement-container**: max width 960px · side padding 240px. Centered prose interludes and monumental proof text; narrower than the main editorial container.
- **flush-media-pair**: 2 columns · gap 0px. Two 720px-wide portrait media fields span the entire 1440px canvas. Mix with single full-width scenes rather than repeating a uniform card grid.
- **inset-demonstration** (only for case studies): max width 1080px · side padding 180px. Case-study interface compositions sit centered on near-black, with 120px separation between images.
- **chapter-asymmetry** (only for case-study demonstration chapters): 2 columns · gap 180px. A 360px text column begins at a 240px inset, alongside a 540px media column beginning at 780px. Long media stacks outlast the text.
- **directory** (only for institutional directories): 3 columns · gap 60px. Three 240px list columns beside a 360px left title area, inside 120px outside insets.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media-and-actions | 0px |
| institutional proof statements | proof-ellipse | 50% |

## Surfaces and depth

### Surfaces

#### Dark editorial canvas · level 0

**Use:** Default marketing ground and the frame around media.

**CSS:** `background: #0e0e0e; color: #ffffff`

**Observed:** Flat and continuous, with no raised panels or gradients between text chapters.

**Transfer:** Let the dark canvas supply separation; do not introduce card backplates around ordinary text.

#### Closing boundary

**Use:** Transition into the common closing area.

**CSS:** `border-top: 1px solid #4f4f4f; padding-top: 80px`

**Observed:** A single thin rule, without a boxed footer panel.

**Transfer:** Use the same boundary whether the preceding chapter is imagery, dark prose or a light band.

#### White chapter · level 0

**Only for:** case studies and institutional pages

**Use:** Long-form demonstration or proof bands.

**CSS:** `background: #ffffff; color: #0e0e0e; padding: 130px 0px`

**Observed:** A complete ground change across the page, not a light card floating in the dark.

**Transfer:** Use a light chapter to distinguish detailed product explanation or institutional proof from the exhibition.

#### Warm mineral chapter · level 0

**Only for:** warm-toned product case studies

**Use:** Backing for a responsive interface sequence.

**CSS:** `background: #e4ded9; color: #0e0e0e; padding: 130px 0px`

**Observed:** Warm, flat mineral color behind tall, tightly arranged mobile layouts.

**Transfer:** Keep the warm surface limited to the product's demonstration chapter.

## Components

### Persistent contact

**Use:** The solitary top-level action throughout a page.

**CSS:** `color: #ffffff; padding-bottom: 3px; background-image: linear-gradient(90deg, #ffffff 0px, #ffffff); background-size: 0px 1px; background-position: 0px 100%; transition: background 0.6s cubic-bezier(0.77, 0, 0.175, 1)`

**Text style:** `persistent-contact` — aktiv-web 700 · 15px/1 · uppercase

**Observed:** Centered in a fixed, transparent header strip 20px from the top. There is no conventional logo-and-menu navigation bar.

**Transfer:** Use one short direct conversion label; preserve its isolated position.

### Opening descriptor

**Use:** Small supporting action over the first-screen photograph.

**CSS:** `color: #ffffff; width: 720px; padding: 1px 6px; text-align: center; position: absolute`

**Observed:** Arial, 22px, weight 400, normal tracking and normal line height. Centered near the lower edge of the photograph, with one line allowed to wrap to two. It has no visible button enclosure.

**Transfer:** State the product's territory or offer rather than adding a second oversized promotional headline.

### Editorial text action

**Use:** Continuation links beside chapter headings or below introductory statements.

**CSS:** `color: #ffffff; text-transform: uppercase`

**Text style:** `action` — aktiv-web 400 · 15px/1 · uppercase

**Observed:** Unboxed text. The introduction places its action 60px beneath the prose; a heading row aligns its continuation action to the lower right.

**Transfer:** Keep the label short enough to remain visually marginal.

### Media tile

**Use:** Primary image-led proof and linked exhibition items.

**CSS:** `position: relative; overflow: hidden; border-radius: 0px`

**Text style:** `media-caption` — aktiv-web 400 · 15px/1.5 · uppercase

**Observed:** The entire figure is linked. A name sits above a discipline line in an absolute caption 40px from the left and 35px from the top. Tiles alternate between full-width landscape scenes and paired portrait fields with no gutters.

**Transfer:** Use the same caption treatment for a product, use case or outcome; make the image carry the main story.

### Underlined utility link

**Use:** Contact addresses, social and closing navigation links.

**CSS:** `color: #ffffff; padding-bottom: 3px; background-image: linear-gradient(90deg, #ffffff 0px, #ffffff); background-size: 100% 1px; background-position: 100% 100%; transition: background 0.6s cubic-bezier(0.77, 0, 0.175, 1)`

**Text style:** `footer-link` — aktiv-web 400 · 13px/2 · uppercase

**Observed:** Underline is a one-pixel background line rather than a filled control. Links in vertical columns follow a 26px line rhythm.

**Transfer:** Use for compact practical destinations rather than promotional chips.

### Closing navigation

**Use:** The shared contact and navigation area at the end.

**CSS:** `display: flex; flex-wrap: wrap; border-top: 1px solid #4f4f4f; padding-top: 80px`

**Text style:** `closing-heading` — aktiv-web 400 · 25px/1.2 · uppercase

**Observed:** A 360px invitation-and-email block starts at the main inset; a 300px open interval separates it from three 180px columns for navigation, social links and address. The monumental signature and a thin utility baseline follow beneath.

**Transfer:** Preserve the contrast between a compact practical header and an oversized identity below it.

### Monumental signature

**Use:** The dominant identity object in the opening and closing.

**CSS:** `width: 1200px; height: 204px; margin-left: 120px`

**Observed:** White high-contrast serif vector lettering with fine hairlines and broad strokes. The closing version begins 60px below the navigation; the opening version floats over the image with a 96px upper inset.

**Transfer:** Create a fitted vector word-image for the new name. Preserve its visual scale rather than its exact letterforms.

### Collection filters

**Only for:** collection indexes

**Use:** Navigation among media categories.

**CSS:** `color: #ffffff; padding-bottom: 3px; background-image: linear-gradient(90deg, #ffffff 0px, #ffffff); background-size: 0px 1px; background-position: 0px 100%; transition: background 0.6s cubic-bezier(0.77, 0, 0.175, 1)`

**Text style:** `filter` — aktiv-web 400 · 20px/1 · uppercase

**Observed:** Centered wrapping text row below the signature. Each item has 20px side margins; the group has 140px above and 110px below. No category pills or enclosed tabs.

**Transfer:** Use a short taxonomy appropriate to the new content.

### Recognition row

**Only for:** recognition sections

**Use:** Quantified proof or a chronological credential list.

**CSS:** `border-top: 1px solid rgba(0, 0, 0, 0.1); padding: 23px 0px 20px; color: #0e0e0e`

**Text style:** `directory-title` — aktiv-web 400 · 25px/1 · uppercase

**Observed:** A plain full-width 1200px row, approximately 69px high, on white. Count and recognition name read together on the same line; the last row also closes with a bottom rule.

**Transfer:** Use actual figures or milestones, not a dashboard of separate stat cards.

### Directory column

**Only for:** institutional directories

**Use:** Categorized capabilities, partners or other long lists.

**CSS:** `width: 240px; margin-right: 60px; display: flex; flex-direction: column`

**Text style:** `directory-title` — aktiv-web 400 · 25px/1 · uppercase

**Observed:** Uppercase category title above small, half-opacity Directory item text on a 30px line rhythm. Three columns sit beside a larger heading. The light-ground counterpart reverses text color but keeps the same architecture.

**Transfer:** Group related terms by meaningful category rather than decorating each with an icon.

## Imagery and graphics

### Campaign photography

**Use:** The first screen and the large visual exhibition throughout a marketing page.

**Observed:** Close fashion portraits, bodies, fabrics, family gestures and product still lifes fill their frames. Skin, glass, hair, paper and textile remain tactile and naturally lit. Some scenes are theatrically saturated, but the surrounding interface stays monochrome. Images are edge-to-edge or paired without rounded corners; subjects are frequently cut by the frame rather than presented as small isolated objects.

**Transfer:** Commission intimate product-in-use photography or a strong material close-up. For a digital product, photograph its real-world context and combine that with genuine interface demonstrations. Minimum acceptable treatment is one high-resolution close-up with directional light, rich material detail and a deliberate off-center subject.

### Serif word-image

**Use:** Signature graphic in the opening and again in the closing area.

**Observed:** An enormous white serif signature spans almost the full editorial width. Hairline stems, broad swelling curves and pointed serifs create a fashion-masthead silhouette, with no outline, glow, bevel or shadow.

**Transfer:** Make a new identity word-image with similarly dramatic stroke contrast; keep it a single dominant silhouette. A typeset high-contrast serif name fitted to the same width is the minimum acceptable substitute.

**Build:** Use an SVG with a 1200×204 viewBox. Set the new name in a high-contrast display serif such as Bodoni Moda at regular weight, fit the text to 1200px width, and convert to paths when final. Fill white; no stroke. Retain generous counters and very fine hairlines. Scale the SVG proportionally, align it to the 120px editorial insets at desktop, and use the same artwork in the closing area.

### Inset interface exhibition

**Only for:** case studies

**Use:** Demonstrating finished digital work between photographic scenes.

**Observed:** Large flat interface images sit in 1080px-wide compositions on near-black with 180px side margins. Arrangements range from a single long desktop page to two adjoining page views, a three-column montage, or desktop views with small overlapping phone frames. Screens carry their own visual identities and are not the typography or palette of the surrounding site.

**Transfer:** Use genuine UI views, alternating one comprehensible large view with a denser montage. Keep the surrounding frame flat; avoid adding a fake browser toolbar or a floating-device shadow to every image.

### Long image chapter

**Only for:** case-study demonstration chapters

**Use:** A sustained explanation of product details or production.

**Observed:** A short heading and paragraph occupy the left while the right carries a much taller sequence. Warm mineral ground backs paired columns of mobile layouts; white ground backs square studio photographs, behind-the-scenes camera views and CGI material studies. Text remains visually anchored while the image sequence continues.

**Transfer:** Build a concise explanatory column next to a series of product details, real process views or interface states, matching the same backing and image widths.

### Loose photographic collage

**Only for:** institutional pages

**Use:** Humanizing an organization or giving physical proof a tactile presence.

**Observed:** Office-window photographs overlap on dark ground; a trio of tall work and award images overlap on white with small opposing rotations. The images remain rectangular and unframed, without paper borders or drop shadows.

**Transfer:** Use two or three real contextual photographs with varied vertical starts and shallow overlap rather than a perfectly aligned team grid.

**Build:** Place three portrait images approximately 500px wide in a relative 1440px stage. Stagger their upper edges, overlap adjacent images by about 100px, and rotate the left image slightly counterclockwise and the center slightly clockwise. Keep the right image nearly upright, allow foreground images to cover lower corners, and retain the white ground without shadows.

### Elliptical proof graphic

**Only for:** institutional proof statements

**Use:** A celebratory recognition or thank-you statement.

**Observed:** A faint horizontal ellipse surrounds 90px uppercase centered text and a much smaller explanatory line on white. The contour is barely visible; the words, not the border, dominate.

**Transfer:** Use for one genuine collective milestone or recognition statement, retaining the unusually broad ellipse rather than turning it into a badge.

**Build:** Use a centered 1200px-wide elliptical pseudo-element with border-radius:50% and a 1px rgba(13,13,13,0.1) border. Place a 960px text block in front with 90px/1 uppercase type. Give the enclosing white section 130px vertical padding; place a narrow 13px uppercase explanatory line 20px below the statement.

## Section recipes

How recurring sections are built.

### First screen: Campaign masthead opening

**Observed:** The full first 900px is a photograph, backed by the Dark editorial canvas and covered by white identity and utility text. A close face fills most of the image; fabric and a raised hand reach the edges. The Monumental signature occupies the upper third, aligned to the 120px editorial insets, about 1200×204px with its top around 96px. Persistent contact sits above it at the center. Opening descriptor spans a centered 720px near the bottom and wraps to two lines. The first screen contains the complete masthead, contact action, descriptor and main image; the explanatory manifesto and exhibition heading are below the fold. There is no separate oversized sans sales headline over the photograph.

**Transfer:** For a different product, choose an equally immersive product-in-use or tactile close-up as the full-height scene, then fit the new identity as a high-contrast white word-image. The masthead is the title object; use Opening descriptor for its short support. The Manifesto recipe belongs below the fold, not over the photograph. A case study opens with its own campaign scene beneath the same identity; a collection opens on dark ground with the signature and Collection filters; an institutional page opens with the signature above a large prose introduction.

**Avoid:** Do not replace the scene with a split-screen software hero, a small logo in a navbar, or a centered headline plus two pill buttons. Do not mistake the below-fold 75px manifesto for the opening masthead.

**Text style:** `manifesto` — aktiv-web 400 · 75px/1

### Manifesto and heading pair

**Observed:** Within the editorial-container, a 75px/1 sentence-case statement is followed by Editorial text action after 60px. A deliberate 350px pause leads into a Chapter heading at left and a small continuation action at the lower right. The heading can break into two compact lines; 110px separates this pair from the first large image.

**Transfer:** Express one positioning idea in a few broad lines, then let the next image group begin its own visual argument. Preserve the pause rather than filling it with secondary benefit cards.

**Text style:** `manifesto` — aktiv-web 400 · 75px/1

### Flush exhibition

**Observed:** Media tile units alternate between single full-width landscapes and two 720px-wide portrait fields. Captions are overlaid rather than placed in separate card bodies. Media dominates the page height, with occasional very tall scenes and no uniform thumbnail rhythm.

**Transfer:** Alternate scale according to the available photography or product proof, preserving the flush seams and small over-image labeling.

**Text style:** `media-caption` — aktiv-web 400 · 15px/1.5 · uppercase

### Centered editorial interlude

**Observed:** A Statement in a 960px centered column sits directly on Dark editorial canvas with 180px margins above and below. It is prose rather than a quotation card, occasionally broken into two related paragraphs.

**Transfer:** Use one outcome, belief or contextual proof statement to reset the reader between image chapters.

**Text style:** `statement` — aktiv-web 400 · 55px/1

### Signature closing

**Observed:** Closing navigation starts immediately after the final proof image or chapter, separated by Closing boundary. Its invitation, contact address and compact columns sit above a 1200×204px Monumental signature with 60px above it. The bottom line appears after 50px, aligning small legal text left and the newsletter action right, with 80px bottom padding. This shared ending is about 594px tall at desktop.

**Transfer:** Keep this identity-led ending on a new page. Replace the practical destinations and invitation with the product's own conversion route; retain the enormous word-image as the final emotional beat.

**Text style:** `closing-heading` — aktiv-web 400 · 25px/1.2 · uppercase

### Case context and services

**Only for:** case studies

**Observed:** After the full-screen image, an uppercase Chapter title and small project action introduce a 35px/1.15 paragraph in an 840px column inset 180px. A compact role-and-services list follows before the next inset media view.

**Transfer:** Explain the problem, intervention and result in readable prose, then list only the relevant disciplines. Keep the detailed discussion below the image-led opening.

**Text style:** `case-introduction` — aktiv-web 400 · 35px/1.15

### Asymmetric demonstration chapter

**Only for:** case studies

**Observed:** Long image chapter uses Chapter asymmetry: a narrow left text column, 25px heading-to-body spacing and a much taller right media column. White chapter and Warm mineral chapter are scoped light variants; the dark technical variant uses a wider 420px paragraph column and a tall photograph aligned beside it.

**Transfer:** Pair one concise explanatory idea with a sustained visual sequence. Let the media carry detail instead of expanding the text to match its height.

**Text style:** `case-chapter` — aktiv-web 400 · 55px/1.1 · uppercase

### Institutional directory and recognition

**Only for:** institutional pages

**Observed:** Directory heading anchors the left of three Directory column units. A dark services band changes to a white partner band while retaining the grid. A separate Elliptical proof graphic is followed by Loose photographic collage and Recognition row units; numbers sit inline with credential names, not oversized in dashboard cards.

**Transfer:** Use this architecture for a deep capability overview or trustworthy institutional proof, not as a default landing-page feature grid.

**Text style:** `directory-heading` — aktiv-web 400 · 50px/1 · uppercase

### Image-backed institutional closing

**Only for:** institutional pages

**Observed:** A full-width tactile product photograph supports a centered, two-line 90px uppercase heading and a small 15px uppercase continuation link. It ends in the common closing area rather than a separate conversion form.

**Transfer:** Use a final emotionally strong image to lead into more work, a collection or an experience before the shared contact ending.

**Text style:** `monumental-proof` — aktiv-web 400 · 90px/1 · uppercase

## Page flow

**Storyline:** Immersive identity → positioning → visual proof punctuated by editorial statements → deeper demonstration or credentials → compact invitation and monumental signature.

### Image-led marketing landing page

1. **Immersive hook** — Full-screen campaign photograph with oversized serif identity and a small descriptor.
2. **Positioning** — Wide regular-weight manifesto, a small continuation action and a spaced heading pair.
3. **Visual proof** — Alternating full-width and flush paired media, interrupted by centered prose proof and positioning statements.
4. **Closing invitation** — Final full-width product scene, compact contact columns, giant signature and bottom-line utilities.

**Transfer:** Use the same contrast of emotional imagery and spare declarations for a product; choose the amount and placement of proof according to the story.

### Extended product and digital-experience case study

1. **Immersive hook** — Full-screen tactile product campaign scene under the common signature.
2. **Context** — Project title, external action, substantial context paragraph and service labels.
3. **Outcome and demonstration** — Centered outcome statement alternates with large product photographs and inset desktop UI compositions.
4. **Detailed capability** — A light montage and a warm mineral responsive chapter give mobile views a sustained sequence.
5. **Next step** — A related-work heading and flush media pair precede the shared signature closing.

**Transfer:** Build a deep case study around genuine outcomes and design decisions; keep the warm mineral treatment scoped to compatible product imagery.

### Production and technical implementation case study

1. **Immersive hook** — Full-screen human product-in-use photograph with the common identity.
2. **Context** — Project introduction and a longer service list on dark ground.
3. **Demonstration** — Inset film-like images, a multi-column interface montage, product imagery and material close-ups.
4. **Technical explanation** — A narrow prose chapter sits beside a tall lifestyle portrait.
5. **Production proof** — White chapter with a long stack of studio, process and CGI imagery.
6. **Closing invitation** — Direct transition from the white chapter into the shared dark signature closing, without a related-work grid.

**Transfer:** Use alternating context, artifact and process chapters for a new product story. Related-work navigation is a page-type choice rather than a universal ending requirement.

### Visual collection index

1. **Orientation** — Large serif signature on dark ground above a centered line of category filters.
2. **Visual exploration** — Long exhibition of flush full-width, paired and occasionally stacked media with marginal captions.
3. **Editorial reset** — Centered statements break up the visual inventory and explain the approach.
4. **Closing invitation** — A final media pair leads into the same compact contact columns and monumental signature.

**Transfer:** Use this for an archive, use-case library or product collection; keep filters textual and images editorially varied.

### Institutional credibility and capabilities

1. **Positioning** — Dark-ground signature and large prose introduction.
2. **Human context** — Overlapping office photographs and a second expansive statement.
3. **Capabilities** — Left heading plus three capability lists on dark ground.
4. **Social proof** — The same directory architecture reverses to white for partner groups.
5. **Recognition** — A giant thank-you statement in a faint ellipse, loose photographic collage and ruled credential list.
6. **Continuation and closing** — Image-backed work invitation, then the common dark contact and signature ending.

**Transfer:** For an institutional page, use a broad introduction and categorized evidence; keep the oval and collage as distinctive proof devices within this page type.

## Writing

Confident, direct and editorial, with occasional conversational warmth. Broad declarations are grounded by tangible work, named disciplines and specific collaboration details rather than an abundance of promotional modifiers.

**Do not copy:** Do not reuse the source identity, wordmark artwork, project names, client roster, locations, awards, numerical claims or quoted business outcomes. Source examples illustrate verbal construction only; write original claims supported by the new product.

- **Addressing the reader:** Uses a collective we to explain the approach and a restrained you or your when connecting it to the reader. Actions name the destination or invite direct contact.
- **Rhythm:** Functional headings are often two to four words. Centered interludes use one or two declarative sentences; case introductions can expand into a paragraph. Uppercase is primarily a visual convention for labels, not a reason to write in slogan fragments everywhere.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Positioning statement | State what the organization does, then reject a generic approach in plain speech. | Two short sentences | “[Brand] is a global creative agency elevating brands' ambitions. We don’t do one size fits all.” |
| Editorial interlude | A short first-person declaration built from concrete verbs. | One sentence, often under ten words | “We think, craft, and produce.” |
| Capability chapter | Use a specific discipline or delivery concern rather than a generic benefit slogan. | Two or three words | “Responsive design”<br>“Content Production” |
| Continuation action | Name the thing the reader will see. | Two or three words | “View project”<br>“View all” |
| Closing invitation | Use a human, collaborative invitation above a direct contact route. | Three or four words | “Let's work together” |

**Words and phrasing to use:** craft; create; collaboration; experience; strategy; design; production; tailor-made; ambitions

**Avoid:** unlock limitless possibilities; game-changing ecosystem; supercharge everything; disruptive synergy; feature-packed

**Rules:**

- Let images demonstrate taste; let prose explain intention and outcomes.
- Use discipline labels to orient the viewer, not long summaries over photographs.
- Make technical detail concrete when the page calls for it; keep marketing interludes broad and concise.
- Allow a lightly conversational phrase in a proof statement without making every heading jokey.

## Do's and Don'ts

### Do

- Align the opening and closing word-images to the same 120px desktop side inset.
- Use 75px/1 regular grotesk for the below-fold manifesto and 55px/1 for centered interludes.
- Set over-image captions at 15px/1.5 uppercase, 40px from the left and 35px from the top.
- Keep paired media flush with a 0px gutter and square corners.
- Give centered interludes 180px above and below to reset the exhibition rhythm.
- Make the footer's practical invitation 25px/1.2 while the serif identity remains the dominant closing object.
- Use a single 1px dark-gray rule above the closing navigation.
- Use white or mineral full-width chapters only in the scoped long-form variants.

### Don't

- Do not distribute the serif signature font across body copy or chapter headings; the reading system is grotesk.
- Do not bold the 55px and 75px editorial statements; their measured character is weight 400.
- Do not replace the 15px marginal captions with large card titles beneath every image.
- Do not round photographs into 12px cards or add drop shadows to the exhibition.
- Do not turn the category filters into filled 44px controls; the index uses 20px uppercase text links.
- Do not spread warm mineral or campaign colors into a sitewide navigation theme; the chrome stays near-black and white.
- Do not turn recognition counts into separate oversized number tiles; keep count and label together in ruled rows.
- Do not compress the closing signature to a small corner logo beneath a dense sitemap.

## Motion and responsive

### Motion

**Observed:**

- Underlined actions use background 0.6s cubic-bezier(0.77, 0, 0.175, 1).
- Opening image and identity layers use translated transforms during scrolling; the long-form media chapters keep explanatory text visually anchored beside continuing imagery.

**Transfer:**

- Retain the underline as the principal animated action detail rather than introducing color-filled button transitions.
- If implementing layered scroll movement, preserve the opening's full-frame image and legible word-image relationship; the editorial composition matters more than travel distance.

**Unknown:**

- Exact scroll-animation travel, sequencing and timing for the image and signature layers.
- Hover and focus-visible end-state declarations were not available; no specific end-state is prescribed.

### Responsive

**Observed:**

- Width breakpoints are declared at 768px, 1023px and 1024px.
- The desktop root is viewport-scaled, so the rem-based type and spacing respond proportionally.

**Transfer:**

- On narrow screens, keep the signature width-led and the campaign image full-bleed. Reframe the subject rather than reducing it to a small inline image.
- Recommended adaptation: stack paired exhibition images and move narrow chapter prose before its image sequence; keep captions on their corresponding images.
- Recommended adaptation: wrap taxonomy text and footer columns without turning them into pills or raised panels. Preserve useful reading sizes instead of scaling small labels without a floor.

**Unknown:**

- Mobile typography sizes, exact grid collapse rules, header changes and image focal-point adjustments.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
