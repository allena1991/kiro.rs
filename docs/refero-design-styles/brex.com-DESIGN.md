# Brex — sculptural business momentum

## Overview

A brisk, assured business style that makes operational software feel tangible and ambitious. Mostly white and cool pale gray, it pairs tightly set grotesk headlines with small orange actions, warm human photography, and sculptural product scenes. Spacious marketing chapters give way to denser comparison and question sections; near-black bands add weight without turning the default experience into a dark interface.

### Essentials

- Business promises land as compact, heavy-looking sentences without bold weights: Inter 500 at 72px/1 with -0.02em tracking, then 48px/1 section leads and 36px/1 capability headings.
- The opening balances a left-hand promise against a tangible product stage: 72px side gutters, an 840px-tall scene, a two-line headline, a narrow support line, and an inset email-and-action unit. A large perspective object enters from the right and extends beyond the viewport; recreate that physical staging even for a software-only product.
- Orange is an instrument, not the canvas: #ff3d00 marks actions, inline arrows and 48px proof figures against predominantly white and #f3f3f7 fields. Dark #000710 anchors the conversion band and footer; whole-page darkness belongs to the premium product variant.
- Conversion controls are rounded rectangles rather than capsules: standalone actions are 48px tall with 10px corners; the 40px inset action has 8px corners inside a 58px white form with 12px corners.
- Software is shown as an edited physical exhibit: large pale rounded backings, floating white interface fragments, soft shadows and one legible workflow rather than a full dashboard everywhere. Pair this device with warm, close human portraits to keep technical claims human.
- Proof changes typographic register: orange 48px numbers sit between 24px labels and 16px explanations; customer testimony shifts to a 36px/40px serif. Include both a concise proof treatment and a human testimony treatment, adapting their content rather than their subjects.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action orange | `#ff3d00` | `--color-orange` | action, link, accent | Primary actions, directional text links and numeric proof. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm orange | `#ff5900` | `--color-warm-orange` | accent, surface | Active action state; larger quote-card accents and calculator fill in scoped variants. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue black | `#000710` | `--color-night` | background | Conversion bands, announcement strip and footer; full canvas for the dark product variant. |
| Charcoal ink | `#15191e` | `--color-ink` | text, surface | Primary headings and strong text; also the raised card fill in the dark product theme. |
| Slate body | `#60646c` | `--color-body` | text | Support lines, paragraphs and secondary labels on light backgrounds. |
| Muted slate | `#6f737b` | `--color-muted` | text | Calculator explanation and inactive customer tabs. |
| Gray links | `#8b8d98` | `--color-footer-link` | text, link | Footer link lists and quieter controls. |
| Silver gray | `#b9bbc6` | `--color-dark-secondary` | text | Secondary text on dark backgrounds and footer disclosures. |
| Cool hairline | `#e3e6ed` | `--color-rule` | border | Visible result of rgba(66,87,138,0.15) on white; form edges, section and row rules. |
| Cool lavender gray | `#f3f3f7` | `--color-wash` | background, surface, border | Broad social-proof, audience and testimonial bands; pricing canvas. |
| Soft white | `#fcfcfd` | `--color-reverse` | text, surface | Text on dark bands and standard orange actions; culture filter fills. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page, navigation, form and card fill; compact button text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| culture and recruitment pages | Quote black | `#000000` | `--color-quote-black` | surface | High-contrast quotation panel among photographic tiles. |
| culture and recruitment pages | Culture navigation | `#101317` | `--color-culture-nav` | background | Dark sticky navigation. |
| interactive value calculators | Slider track | `#ebebf1` | `--color-track` | surface | Unfilled calculator rail. |

## Typography

- **inter** — All marketing headings, paragraphs, actions and navigation. Clean, compact grotesk with open counters; medium rather than bold headings make tight tracking do the work. OpenType features: "calt" 0, "cv01", "cv05" 0, "cv10", "liga" 0, "ss01" 0, "ss03", "zero" 0. Font stack: "inter", "Inter", Arial, sans-serif.
- **flecha** — Customer testimony. Expressive editorial serif with crisp contrast and a more conversational texture than the surrounding sans. If unavailable, use **DM Serif Display**. Use regular weight and preserve the broad 36px/40px setting. Font stack: "flecha", "DM Serif Display", Georgia, serif.
- **Space Mono** — Product chapter markers and culture labels. Mechanical monospace, uppercase and unembellished. Font stack: "Space Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | inter | 500 | 72px | 1 | -0.02em | fixed | Default marketing hero, also centered in the dark product opening. |
| section-heading | inter | 500 | 48px | 1 | -0.02em | fixed | Centered chapter titles, audience and social-proof headings. |
| emphasis-heading | inter | 500 | 48px | 1 | -0.03em | fixed | Orange proof figures and the dark conversion heading. |
| feature-heading | inter | 500 | 36px | 1 | -0.02em | fixed | Alternating product rows and strong feature titles. |
| quotation | flecha | 500 | 36px | 40px | normal | fixed | Customer quotations; keep the serif isolated to testimony. |
| card-heading | inter | 500 | 24px | 29px | -0.02em | fixed | Audience cards, resource titles and stat labels. |
| support | inter | 500 | 20px | 1.2 | -0.02em | fixed | Hero and section supporting lines. |
| body | inter | 400 | 16px | 1.5 | -0.02em | fixed | Paragraphs and card explanations. |
| text-link | inter | 400 | 16px | 1.5 | normal | fixed | Orange editorial links and muted footer links. |
| button | inter | 400 | 14px | 22px | normal | fixed | Standalone conversion buttons and navigation conversion action. |
| compact-button | inter | 500 | 14px | 20px | -0.02em | fixed | Inset email-submit labels and customer tabs. |
| navigation | inter | 600 | 14px | 20px | -0.01em | fixed | Short navigation links; dropdown labels use regular-weight 14px/21px text. |
| announcement | inter | 400 | 12px | 1.5 | -0.02em | fixed | Compact release message in the top strip. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| culture and recruitment openings | culture-display | inter | 400 | 144px | 0.8 | -0.05em, uppercase | size clamp(128px, 5.5325rem + 3.8554vw, 144px), tracking clamp(-7.2px, -0.2766rem - 0.1928vw, -6.4px) | Two monumental centered lines over workplace film. |
| detailed product and culture pages | tight-display | inter | 500 | 72px | 0.98 | -0.04em | fixed | Split banking-product opening, large light conversion statement, and culture chapter leads. |
| product detail and recruitment pages | utility-heading | inter | 500 | 30px | 1.2 | -0.02em | fixed | FAQ heading and filter-group headings. |
| pricing and detailed product pages | detailed-body | inter | 400 | 20px | 1.2 | -0.02em | fixed | Plan feature lists and product-detail bullet lists. |
| culture and recruitment pages | culture-label | Space Mono | 400 | 20px | 1.2 | normal, uppercase | fixed | Left-aligned culture chapter markers. |
| detailed product chapters | chapter-label | Space Mono | 500 | 16px | 19px | normal, uppercase | fixed | Small product category marker above a capability heading. |
| recruitment listings | filter | Space Mono | 400 | 16px | 1.2 | 0.05em, uppercase | fixed | Team and location filter chips. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use sentence case for ordinary marketing headlines. Reserve uppercase for monospace markers and the culture-film opening.
- The default hero and feature titles track at -0.02em. The 48px proof and closing treatment tightens to -0.03em; detailed-product and culture chapter display tightens to -0.04em.
- Use the serif as a deliberate pause in the grotesk system, not as a second general-purpose heading family.
- Do not let long supporting lines inherit display tightness or become bold; most body content remains weight 400.

## Layout

**Density:** Airy marketing chapters with compact controls and dense comparison or disclosure regions.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Most section padding, text offsets and vertical gaps follow multiples of 8px.

| Value | Use |
| --- | --- |
| 8px | Small heading-to-figure or title-to-description gap. |
| 16px | Heading-to-body gap and tight tile gaps. |
| 24px | Standard grid gutter, image-to-title gap and conversion-band text spacing. |
| 32px | Capability-card padding, label-to-culture-heading gap and support-to-action separation. |
| 48px | Wide gutters, testimonial-column separation and inner chapter breathing room. |
| 72px | Desktop outer content gutters. |
| 80px | Ordinary section padding and separation around product chapters. |
| 96px | Vertical padding only for interactive value calculators. |
| 160px | Major dark conversion padding, footer top and bottom padding, and culture chapter boundaries. |

### Containers and grids

- **Main grid**: max width 2500px · 24 columns · side padding 72px. Outer full-width section wrapper and aligned content grid. At 1440px this gives 1296px of usable content; media may bleed beyond it.
- **Tile container**: max width 1680px · side padding 72px. Centered product and plan tile regions.
- **Editorial rows**: max width 1080px · 2 columns · gap 108px. Two 486px columns at desktop for alternating software media and narrative.
- **Three-up grid**: 3 columns · gap 24px. Audience photographs and plan cards, each about 416px wide in the standard desktop gutter.
- **Numeric proof**: 3 columns · gap 48px. Three text-only measures; narrower content than the full outer grid.
- **Navigation container**: max width 1680px · side padding 24px. Compact edge-to-edge header; logo and menu left, sales and sign-in actions right.
- **Centered copy**: max width 760px. Readable centered section descriptions and short conversion messages.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Standalone actions | 10px |
|  | Inset action | 8px |
|  | Media and capability cards | 12px |
|  | Carousel arrows | 50% |
| pricing pages | Plan cards | 6px |
| culture and recruitment pages | Quote tiles | 16px |
| recruitment listings | Filter chips | 100px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Navigation edge | `rgba(66, 87, 138, 0.15) 0px 1px 0px 0px` | Single subtle line under the sticky light navigation. |
| Form lift | `rgba(0, 0, 0, 0.04) 0px 1px 1px 0px` | Almost-flat white conversion form; not a general card shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #15191e`

**Observed:** Long white capability stretches are interrupted by broad pale bands rather than individually outlined sections.

**Transfer:** Let whitespace separate chapters before adding containers.

#### Pale band · level 0

**Use:** Audience segmentation, social proof and testimonial regions.

**CSS:** `background: #f3f3f7`

**Observed:** Full-bleed cool gray with dark text and little texture.

**Transfer:** Use this surface to gather related content into one chapter.

#### Night band · level 0

**Use:** High-emphasis conversion and footer regions.

**CSS:** `background: #000710; color: #fcfcfd`

**Observed:** Deep blue-black, flat and full bleed; the closing message is centered with abundant empty space.

**Transfer:** Keep it a strong change of tone within the default light experience.

#### White tile · level 1

**Use:** Capability groups on pale fields.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 32px; box-shadow: none`

**Observed:** Soft corners and clean fill carry the grouping without visible elevation.

**Transfer:** Group one feature or one concise list per tile.

#### Dark product tile · level 1

**Only for:** dark product landing pages

**Use:** Benefit grids, interface demonstrations and large feature panels.

**CSS:** `background: #15191e; border-radius: 12px; color: #fcfcfd`

**Observed:** Slightly lighter than the night canvas; diagrams and product renders emerge from the same dark material.

**Transfer:** Use charcoal panels, not white cards recolored with inverted interface art.

#### Culture quote tile · level 1

**Only for:** culture and recruitment pages

**Use:** Large statements in a moving portrait-and-quote rail.

**CSS:** `background: #000000; color: #ffffff; border-radius: 16px; padding: 48px`

**Observed:** Black and warm-orange statement variants alternate with warm environmental portraits of different heights; attribution sits at the bottom beneath a fine white rule.

**Transfer:** Use candid voices with short, emphatic excerpts and unequal photographic heights.

## Components

### Sticky navigation

**Use:** Persistent compact wayfinding.

**CSS:** `position: sticky; z-index: 10; height: 60px; background: #ffffff; box-shadow: rgba(66, 87, 138, 0.15) 0px 1px 0px 0px`

**Text style:** `navigation` — inter 600 · 14px/20px · tracking -0.01em

**Observed:** Logo at left, menu groups with small downward chevrons, then customer and pricing links; sign-in, demo link and a smaller orange action align right. The release strip above it is 50px tall and scrolls away. Culture pages use the dark navigation surface with reverse text.

**Transfer:** Keep menu labels short and avoid turning the header into a large hero element.

### Primary button

**Use:** Standalone conversion in section endings and plan cards.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 48px; padding: 0px 20px; background: #ff3d00; color: #fcfcfd; border: 1px solid #ff3d00; border-radius: 10px`

**Text style:** `button` — inter 400 · 14px/22px

**Observed:** Centered label with no decorative icon. The header variant is 36px tall with 12px horizontal padding; pricing comparison actions can be 40px tall.

**States:** Declared: hover background and border #ff6b18, text #fcfcfd; focus-visible 2px solid #ff3d00 outline with 2px offset, hover fill and reverse text; active background and border #ff5900, text #ff3d00.

### Inset submit button

**Use:** Compact conversion inside an email form.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 16px; margin: 8px; background: #ff3d00; color: #ffffff; border: 1px solid rgba(66,87,138,0.15); border-radius: 8px`

**Text style:** `compact-button` — inter 500 · 14px/20px · tracking -0.02em

**Observed:** Lives inside the right edge of a white email-and-action shell, not beside a separately bordered input.

**States:** Declared: hover background #ff6b18, text #ffffff; focus-visible 2px solid rgba(0,110,245,0.8) outline with 2px offset; active background #ff5900, text #ffffff.

### Email conversion form

**Use:** Low-friction lead collection in openings and selected closing sections.

**CSS:** `display: flex; align-items: center; gap: 4px; height: 58px; padding-left: 12px; background: #ffffff; border: 1px solid rgba(66,87,138,0.15); border-radius: 12px; box-shadow: rgba(0, 0, 0, 0.04) 0px 1px 1px 0px`

**Text style:** `compact-button` — inter 500 · 14px/20px · tracking -0.02em

**Observed:** A borderless text input fills the remaining space before the Inset submit button. The default opening form is 384px wide; narrower product variants use about 312px. The input has a proper work-email label.

**Transfer:** Use a single field rather than a multi-field lead form in the opening.

### Arrow text link

**Use:** Secondary exploration under capability and audience copy.

**CSS:** `color: #ff3d00; text-decoration: none`

**Text style:** `text-link` — inter 400 · 16px/1.5

**Observed:** A small right-pointing arrow follows the label on the same baseline. Links sit after a meaningful gap, not inline with every paragraph.

**States:** Declared: hover color #ff5900 without underline; active color #ff8b66 without underline.

### Capability tile

**Use:** Short product overview and concise benefit lists.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 32px; overflow: hidden`

**Text style:** `card-heading` — inter 500 · 24px/29px · tracking -0.02em

**Observed:** Image or illustration, title and short supporting text form one clickable unit. Five narrow overview tiles use 16px gaps; broader three-up list cards share the same white material. Dark-theme variants use charcoal fill with reverse text.

**Transfer:** Keep each tile about one distinct capability, not a miniature landing page.

### Footer link columns

**Use:** Complete site ending, navigation and trust material.

**CSS:** `background: #000710; padding: 160px 0px; color: #8b8d98`

**Text style:** `text-link` — inter 400 · 16px/1.5

**Observed:** Five columns in the standard gutters: logo then four categorized link lists. Labels are smaller and brighter than links; links have approximately 12px visual separation. Social and app-store rows follow, then a clearly subordinate dense disclosure region. This ending persists across both light and dark page types.

**States:** Declared: hover link color #ff6b18 without underline; active #ff5900.

**Transfer:** Retain the generous footer entrance and organized lists; let the actual need for disclosure determine its length.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side purchase choices.

**CSS:** `background: #ffffff; border-radius: 6px; padding: 24px; overflow: hidden`

**Text style:** `feature-heading` — inter 500 · 36px/1 · tracking -0.02em

**Observed:** Three equal-width cards on a pale band. Each contains plan name, audience line, price, full-width orange action, then a checkmarked feature list. Inner content has further breathing space; the tall desktop cards are 416px wide. A horizontal custom-offering card follows.

**Transfer:** Give every tier equal visual footing; differentiate by content rather than a gratuitous elevated recommended badge.

### FAQ row

**Only for:** product detail pages

**Use:** Compact objection handling near the end.

**CSS:** `padding: 16px 0px; border-bottom: 1px solid rgba(66,87,138,0.15)`

**Observed:** Full-width question button, small text at the left, tiny downward chevron at the right; rows are about 56px tall. First row also has a top rule. Light variant uses dark text; dark variant uses reverse text and rgba(97,106,136,0.3) separators.

**Transfer:** Keep questions in a restrained list beneath a left-aligned utility heading.

### Filter chip

**Only for:** recruitment listings

**Use:** Team and location selection.

**CSS:** `height: 40px; padding: 0px 20px; background: #fcfcfd; color: #15191e; border: 1px solid #15191e; border-radius: 100px`

**Text style:** `filter` — Space Mono 400 · 16px/1.2 · tracking 0.05em · uppercase

**Observed:** Outlined monospace capsules wrap into several rows with 12px horizontal and 16px vertical separation. Sectioned listings below pair a role name with a small uppercase location and orange arrow.

**States:** Declared: hover color and border-color #8b8d98.

## Imagery and graphics

### Sculptural product stage

**Use:** The signature first-screen product exhibit.

**Observed:** A black physical card and metallic phone lie on a softly lit off-white slab seen in perspective. The stage enters from the right and lower edge, much larger than the copy; faint orange technical marks and fine lines animate the otherwise pale backing. Lighting is diffuse, with warm blush reflections at the bottom and very soft contact shadows.

**Transfer:** Create an equivalent physical representation of the product: a device, package, tool or carefully edited interface mounted on a shallow slab. The minimum version is one sharply rendered device or UI plane on a beveled pale platform, not an unrelated stock photo.

**Build:** Make a large off-white rounded platform in the right half of the scene, rotate its top plane into perspective and let it overflow the right and bottom edges. Layer a dark rounded product plane and a detailed device render above it; add a subtle orange edge to the dark plane and soft low-opacity black contact shadows. Use an SVG overlay of thin orange paths, tiny plus signs and a single dot across the platform. Keep those marks much fainter than the action; warm the lower stage with a broad low-opacity orange radial wash.

### Edited interface exhibits

**Use:** Capability chapters and overview tiles.

**Observed:** Floating white panels, small graphs, receipts, approval badges and profile thumbnails sit against cool gray-blue rounded rectangles. Desktop row images are about 486px by 358px; the composition shows only the useful slice of a workflow. White page space surrounds these media panels.

**Transfer:** Compose a few real product fragments into a clear workflow illustration. Preserve pale backing, realistic interface scale and readable visual hierarchy rather than shrinking a complete application screen.

**Build:** Use a 12px rounded cool pale backing. Center two or three white interface cards with gentle contact shadows; vary their depth and allow one fragment to overlap another. Use a single diagram, graph or state badge as the focal point. Keep accent colors inside this demonstration subordinate to the orange page actions.

### Warm editorial people

**Use:** Audience cards and customer testimony.

**Observed:** Close environmental portraits with warm orange walls, golden light, natural skin and softly defocused offices. Audience images are landscape, about 408px by 255px; testimony uses a larger 648px by 482px portrait beside serif copy. Faces feel observed rather than posed as a corporate team row.

**Transfer:** Photograph actual users in their working context. Use warm side light or a warm architectural color field; keep photographic saturation inside the image rather than tinting the entire section.

### Editorial resource thumbnails

**Use:** Late-page insight rail.

**Observed:** Landscape thumbnails mix cinematic photography, product compositions and designed report covers; image then 24px title then a small explanation. A fourth item continues beyond the right edge with circular navigation arrows underneath.

**Transfer:** Use a coherent set of landscape editorial images, allowing each article its own subject but retaining clean framing and high production value.

### Dark product material

**Only for:** dark product landing pages

**Use:** Premium-product opening, broad feature panels and sculptural closing.

**Observed:** Large charcoal objects with satin black faces, subtle metallic edges and orange edge reflections float over blue-black space. Wide panels introduce soft teal-green and warm gold illumination, while the closing scene places one object above a restrained pool of light. Product repetitions are arranged diagonally with thin vertical annotation stems.

**Transfer:** Translate the product into a dark satin object or interface plane. Keep most of the frame dark, with narrowly controlled glints and a broad faint glow rather than neon outlines.

**Build:** Back a 12px rounded panel with blue black. Layer broad translucent teal and warm amber radial gradients near opposite upper corners and fade them into darkness. Arrange dark rounded product planes in receding perspective with fine warm edges. Add a few pale annotation pills on thin stems when explaining variants; for the closing, reduce to one suspended object and a blurred elliptical pool beneath it. Match the soft light rather than relying on exact gradient stops.

### Culture documentary rail

**Only for:** culture and recruitment pages

**Use:** Full-bleed workplace film, long-form people story and alternating portrait/quote rail.

**Observed:** Workplace film shows people at desks and moving through a sunlit office beneath a 40% black overlay. Other frames are warm and cinematic, including a dramatically lit desk scene. Portrait tiles mix standing and seated subjects in real interiors; unequal tile heights alternate with black or orange quotation panels.

**Transfer:** Use real working moments and varied environmental portraits, not a decorative collage of anonymous faces. A static documentary image can carry the large reverse opening typography if film is unavailable.

### Icons

**Observed:** Small filled SVG arrows and functional marks are mostly 14px or 16px. Navigation chevrons are about 11px by 7px with rounded strokes; comparison tables use 24px checks. Orange marks exploratory actions, gray marks utility, and white marks dark-theme controls.

**Transfer:** Choose compact, simple functional icons rather than a large decorative outline-icon system. Let larger illustrations, not icons, carry product personality.

## Section recipes

How recurring sections are built.

### First screen: Product stage opening

**Observed:** A 50px blue-black release strip sits above a 60px white Sticky navigation. Beneath it, an 840px full-width pale scene layers a soft neutral background, the Sculptural product stage on the right, then left-aligned text and controls. The headline is a compact two-line 72px/1 Inter 500 sentence, visually occupying the left half despite a wider available text box. The 20px support line is narrower, wrapping in about two lines; the Email conversion form sits below it, followed by an orange play-marked exploration link. The platform and phone extend beyond the right and bottom edges rather than fitting into a framed card. Within the first 900px the headline, support, full form, secondary action and most of the product object are visible; the stage continues to 950px and the social-proof band begins below the fold.

**Transfer:** Preserve the balance of a short promise at left and an oversized tangible demonstration at right. Without product photography, build the slab and device/UI-plane equivalent described in Sculptural product stage. A detailed-product variant may open with an even split between tight-display text and an interface image; premium dark product pages center the display above one huge dark object. Pricing opens with a centered 48px heading and plan choices; recruitment opens with culture-display over documentary film.

**Avoid:** Do not replace the physical scene with a small floating dashboard beside vertically top-aligned copy, or center all text in the default light opening. Do not fit the entire object neatly above the fold.

**Text style:** `display` — inter 500 · 72px/1 · tracking -0.02em

### Centered chapter heading pair

**Observed:** A centered 48px section-heading introduces a chapter; a narrower 20px support line follows at 16px. White and Pale band treatments alternate. Typical top breathing room is 64px to 80px, and the following content starts after 48px.

**Transfer:** Write a single outcome-led chapter statement and one plain-language support sentence before showing the product demonstration.

**Text style:** `section-heading` — inter 500 · 48px/1 · tracking -0.02em

### Trust band

**Observed:** Pale band with centered section-heading, followed by two compact rows of subdued monochrome partner logos. The detailed-product variant uses a small monospace trust label and one broad logo row on white.

**Transfer:** Use real adoption proof, retaining low visual contrast so logos validate rather than compete with the hero.

### Audience portrait trio

**Observed:** Three-up grid on Pale band, landscape Warm editorial people images, then card-heading after 24px, body after 8px and Arrow text link after 24px. The full region uses 72px outer gutters and about 80px bottom padding.

**Transfer:** Organize by meaningful reader contexts, not necessarily company size. Keep all three image framings similarly intimate.

**Text style:** `card-heading` — inter 500 · 24px/29px · tracking -0.02em

### Alternating capability chapter

**Observed:** Editorial rows pair Edited interface exhibits with feature-heading, body and Arrow text link. Media and text swap sides between chapters. The standard media is 486px by 358px, within the narrower 1080px two-column composition; 16px separates title and prose. Detailed variants add a chapter-label and checklists.

**Transfer:** Explain one job and its visible result per row. Alternate alignment to create rhythm without introducing a different card style each time.

**Text style:** `feature-heading` — inter 500 · 36px/1 · tracking -0.02em

### Numeric proof trio

**Observed:** Three text-only columns on white use a 24px label, orange 48px emphasis-heading after 8px, then 16px explanation after 16px. The columns have a 48px gutter and no enclosing cards. A small qualifier is centered well below them.

**Transfer:** Use substantiated measures in this label-number-explanation pattern; use concise qualitative evidence when a numeric claim is unavailable.

**Text style:** `emphasis-heading` — inter 500 · 48px/1 · tracking -0.03em

### Customer testimony pause

**Observed:** Pale band with a thin-rule tab row and short active underline, then a large warm portrait left and serif quotation right. Attribution and Arrow text link follow the quote. The portrait has 12px corners; the copy is separated from it by 48px.

**Transfer:** Bring a human voice into the otherwise functional story. Keep the quote specific and the surrounding furniture minimal.

**Text style:** `quotation` — flecha 500 · 36px/40px

### Dark conversion pause

**Observed:** Night band centers a 48px emphasis-heading, a short 20px support line after 24px and a Primary button after 32px. Top and bottom padding are 160px. This conversion pause can precede an editorial rail rather than being the literal end of the page.

**Transfer:** Use it as a decisive tonal break and single-action invitation. The light detailed-product variant instead uses Pale band, tight-display and Email conversion form.

**Text style:** `emphasis-heading` — inter 500 · 48px/1 · tracking -0.03em

### Resource rail and complete ending

**Observed:** A centered heading introduces landscape editorial cards on white. Image, title and explanation form each item; the rail extends past the right gutter and uses 50px circular arrows below. Footer link columns then establish a deep blue-black ending with generous top padding, social/app links and subordinate disclosures.

**Transfer:** Use relevant next-step reading only when useful. Always finish with a complete organized footer, not just the conversion band.

### Pricing comparison chapter

**Only for:** pricing pages

**Observed:** Centered 48px opening headline, a low-contrast logo row, three Plan cards and a broad custom-offering row all sit on Pale band. Below, a four-column comparison uses a broad feature column plus three aligned tier columns. Its tier/action header remains visible while category rows fold; expanded rows alternate pale and white fill with centered green checks.

**Transfer:** Let visitors compare the same attributes across all options. Finish after the comparison with the shared dark footer rather than inserting a generic extra sales banner.

**Text style:** `section-heading` — inter 500 · 48px/1 · tracking -0.02em

### Interactive value demonstration

**Only for:** interactive value calculators

**Observed:** White centered region with 96px vertical padding. A section-heading and short support line precede monumental dark monetary numerals with a much smaller baseline annual suffix. A 625px by 22px slider below uses a pale track, warm-orange fill, a white circular thumb and an orange value label; a compact explanatory sentence and numeric field follow. A small two-column rate table completes the demonstration.

**Transfer:** Make one live result dominate the section. For a comparable calculator, use a recommended 180px numeral setting at desktop with tight grotesk spacing, then scale it to fit the result rather than preserving a long string. Keep assumptions below the control and visibly separate from the headline.

### Culture manifesto and listing

**Only for:** culture and recruitment pages

**Observed:** Culture-label sits 32px above tight-display chapter leads with 160px major section boundaries. Dark chapters mix a three-column short-value grid, a wide environmental photo and numbered 36px statement rows separated by thin rules. Pale benefits and investor chapters lead into white recruitment filters, categorized roles and then the shared footer. The portrait rail uses 448px tiles with 24px gutters, 16px corners and alternating image and statement heights.

**Transfer:** Use these editorial devices for organizational storytelling, then change density decisively when the visitor reaches actionable listings.

**Text style:** `tight-display` — inter 500 · 72px/0.98 · tracking -0.04em

## Page flow

**Storyline:** Promise → tangible product exhibit → trust → reader fit and capability chapters → quantified or human proof → conversion invitation → relevant questions or reading → organized dark footer.

### Broad platform marketing

1. **Promise and product demonstration** — Split pale first screen combines the compact promise, email action and oversized physical product stage.
2. **Social proof and reader fit** — Pale logo band, compact product tiles and a warm three-portrait audience grid.
3. **Capability chapters** — Alternating edited-interface exhibits and short outcome-led explanations.
4. **Quantified and human proof** — Orange numeric trio followed by a tabbed portrait-and-serif quotation.
5. **Conversion and continued exploration** — Deep dark single-action band, then a light editorial carousel.
6. **Ending** — Five-column dark footer, social and app links, then dense subordinate disclosures.

**Transfer:** Use the light stage-led story as the default for a new multi-capability product; choose only the chapters that strengthen its promise.

### Purchase comparison

1. **Orientation** — Centered compact headline and monochrome credibility row on a pale canvas.
2. **Pricing** — Equal-width white plan cards, then a horizontal custom-offering card.
3. **Detailed comparison** — Tier-aligned matrix with persistent action header and folding feature categories.
4. **Ending** — Comparison ends into the shared deep dark footer; no distinct closing promotion.

**Transfer:** Prioritize comparison over spectacle; keep the same typography, orange action language and restrained materials.

### Detailed functional product explanation

1. **Promise** — Tight split headline, short benefit bullets and inset email action opposite a large interface view.
2. **Trust** — Monospace adoption label and one low-profile logo row.
3. **Capability chapters** — Alternating category-labelled explanations with interface fragments, followed by a pale timeline and three list cards.
4. **Interactive proof** — Monumental calculator result, orange slider and a compact supporting rate table.
5. **Conversion** — Large centered tight-display statement and inset email form on pale gray.
6. **Objection handling and resources** — Light ruled FAQ followed by an editorial image rail.
7. **Ending** — Shared dark link columns and extensive disclosures.

**Transfer:** Use this denser light variant for products where mechanics and tangible value need explanation before purchase.

### Premium product positioning

1. **Promise and product demonstration** — Centered reverse headline over a huge dark satin product object.
2. **Benefits** — Six charcoal illustrated cards in a three-column grid on a night canvas.
3. **Capability chapters** — Broad glow-backed feature panel, narrow use-case cards and interface-focused control panels.
4. **Human proof** — Centered customer logo and serif testimony.
5. **Scale proof** — Large repeated-product perspective scene with small annotations, then concise supporting columns.
6. **Conversion** — Centered invitation above one floating product object and a soft pool of light.
7. **Objection handling and ending** — Dark ruled FAQ joins the same dark footer without changing canvas.

**Transfer:** Reserve the continuous dark variant for a materially distinctive, premium offering with strong object or interface art.

### Culture storytelling and recruitment

1. **Emotional promise** — Monumental uppercase reverse statement over workplace film, with one orange role-finding action.
2. **Credibility** — Large dark typographic assertion, then a light chapter lead and documentary video.
3. **Human proof** — Unequal-height warm portrait and quotation rail.
4. **Principles** — Dark value grid, wide working-environment photograph and numbered ruled statements.
5. **Support and trust** — Pale benefits chapter and investor logos.
6. **Actionable listings** — White filters and categorized role rows replace the editorial density.
7. **Ending** — Listings finish directly into the shared dark footer and disclosures.

**Transfer:** Keep the ambitious editorial voice and film-led scale scoped to organizational stories; make the final actionable directory more compact.

## Writing

Confident, energetic and operationally specific. Ambition is expressed through useful outcomes and direct verbs, with occasional conversational turns that soften technical detail.

**Do not copy:** Do not reuse Brex names, logos, card designs, customer or investor identities, quotations, numeric claims, rates, adoption figures or regulatory promises. Replace them with the new product's actual assets and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; describe product actions directly. Use we sparingly for an organizational point of view, more openly in culture storytelling.
- **Rhythm:** Short sentence-case headlines, often 5–10 words and ending in a period. Support lines usually carry one sentence; capability paragraphs use two or three compact sentences. Actions stay short and verb-led.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Category or outcome plus an active promise; juxtapose two desirable qualities. | 6–12 words | “Finance built for speed and control.”<br>“Business banking that works as hard as you do.” |
| Supporting line | Make the promise concrete with capability scope or operational benefit. | 12–24 words | “Modern cards, banking, expenses, accounting, and more — in 120+ countries.”<br>“Earn competitive yield with no minimum required and same-hour liquidity.” |
| Capability heading | Imperative verb plus a specific job or avoided pain. | 4–8 words | “Control spend before it happens.”<br>“Pay vendors faster and easier.” |
| Primary action | Simple action or invitation; name the task rather than hype. | 2–5 words | “Get started”<br>“Contact sales”<br>“View open roles” |
| Culture statement | Punchy contrast or plainspoken maxim. | 4–12 words | “Think 10x, not 10%”<br>“No silos, no egos” |
| Question | Ask the reader's practical objection in ordinary language. | 8–16 words | “How do I open a [Brand] business banking account?” |

**Words and phrasing to use:** built for; control; automate; in real time; move faster; grow; simplify; get started; before it happens

**Avoid:** revolutionary; unleash limitless possibilities; game-changing ecosystem; magic with no explanation; dense abstract enterprise jargon

**Rules:**

- Lead with what the reader can do, then name the mechanism that makes it possible.
- Attach quantified claims to a clear unit, context and nearby qualification.
- Use conversational asides sparingly; they work best after the practical benefit is already clear.
- Make secondary actions name the next capability or resource rather than using the same vague label everywhere.
- Let pricing and FAQ copy become more literal and less rhetorical than hero copy.

## Do's and Don'ts

### Do

- Keep ordinary headline weights at 500 and reserve the 400 uppercase display for the culture opening.
- Use 72px desktop outer gutters for major content and 24px gutters inside the compact navigation.
- Keep support copy at 20px/24px and body paragraphs at 16px/24px so visual exhibits remain dominant.
- Use 12px media corners and near-flat surfaces; let lighting live in the artwork.
- Show one clear product workflow per 486px-wide capability image rather than an entire application at unreadable scale.
- Treat the 48px orange numeric proof row as typography, with no enclosing dashboard cards.
- Use 160px vertical padding to make the dark conversion invitation and footer feel substantial.
- Pair technical exhibits with warm environmental portraits and the isolated 36px serif quotation treatment.

### Don't

- Do not make ordinary headlines weight 700; the compact tracking already supplies their force.
- Do not make all buttons pills; 10px standalone and 8px inset corners are distinct from the scoped 100px filter chips.
- Do not turn the light marketing experience into a continuous orange or dark page; broad orange quote tiles and whole-page darkness have scoped roles.
- Do not give every white tile a heavy floating shadow; the form shadow is only 1px and 4% black.
- Do not use Space Mono for ordinary paragraphs, navigation or all section headings.
- Do not recolor customer photography into cool gray to match the UI panels; its warmth is intentional.
- Do not apply the premium teal-and-gold atmospheric lighting to every pale capability illustration.
- Do not mistake the conversion band for the entire ending; the footer still needs categorized links and subordinate trust material.

## Motion and responsive

### Motion

**Observed:**

- Standalone orange actions declare a 0.5s transition; capability and plan cards declare box-shadow 0.5s ease-in-out and border 0.5s ease-in-out.
- Recruitment filter chips declare a 0.2s transition.
- Documentary and product media use video; the portrait-and-statement region has horizontal translated rail positions.
- Sticky navigation remains at the top while the announcement strip leaves the viewport.

**Transfer:**

- Use the declared control transitions for the corresponding controls; preserve the distinction between a documentary film and a small interface exhibit.
- Keep the horizontal rail as a contained storytelling device, rather than making every section a sliding carousel.

**Unknown:**

- Exact video playback behavior, autoplay policies, scroll-trigger timing and the portrait rail's animation curve are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 766px, 767px, 960px, 1023px and 1024px; some layouts also use 830px, 900px, 1439px and 1680px.
- The culture opening has explicit clamped font-size and tracking formulas; ordinary desktop type sizes do not supply a measured fluid formula.

**Transfer:**

- Recommended adaptation: stack editorial pairs with the image still large and readable, then reduce three-up card grids to a single column.
- Recommended adaptation: retain the oversized stage's right-edge overflow while moving the text above the object on narrow screens; do not shrink the entire desktop composite until the UI becomes illegible.
- Recommended adaptation: allow filter chips to wrap, preserve a scrollable comparison structure, and collapse footer categories without losing their headings.

**Unknown:**

- Mobile layout, menu construction, exact breakpoint-specific type sizes and media substitutions were not observed.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
