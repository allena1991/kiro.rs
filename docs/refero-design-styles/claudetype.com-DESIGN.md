# Claude — ornamental gallery windows

## Overview

A light, tactile editorial style where modest sans-serif labels introduce extravagant serif lettering and richly framed photography. Warm paper and stone support mint-and-blush atmospheres, near-black specimen stages and tiny electric-green markers. It suits design-led products, collections and portfolios whose visual proof can do most of the talking; text stays sparse while images feel immersive.

### Essentials

- The headline whispers while the pictures perform: regular 18px/1.4 sans-serif headings, with a centered 11px label 12px above; ornamental lettering lives separately as monumental artwork.
- The opening is a three-window editorial arcade: 16px gutters and side margins, three 459px-wide portrait images at desktop, 900px top radii, and a centered heading above rather than text over the photographs.
- Actions belong to soft capsules: 48px standalone buttons and 56px action segments within a 64px-high, 50px-radius tray; no hard rectangular conversion blocks.
- Neutral architecture carries the color: cream #fcfbf7 sections over #e7e4e0 stone; saturated color belongs mainly to photography, while #99ff66 is concentrated in 18px-high badges and product-purchase actions.
- A soft mint-and-blush atmospheric interlude and a giant ornamental word sculpture are signature devices: use a 682px-tall breathing space for the former and a full-width 32px-radius stage with 423–520px-high lettering artwork for the latter. With no equivalent product artwork, compose an original short serif phrase with swashes.
- Proof is an exhibition, not a dashboard: alternate 696px paired images with a 340px/696px/340px arrangement, mixing arches, ovals and rounded rectangles across 16px gaps.
- The ending is a typographic curtain call: small link columns and a compact subscription capsule sit above a nearly full-width ornamental closing line, with 180px separation and a centered 11px copyright below.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric mint | `#99ff66` | `--color-green` | accent, surface, action | Tiny quantity badges. Also the purchase capsule on dedicated product pages. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Clean white | `#ffffff` | `--color-white` | surface, text | Subscription card and reversed lettering. White also backs the interactive product presentation. |
| Cream paper | `#fcfbf7` | `--color-paper` | surface, background | Default opening, light specimen stages and footer. |
| Frosted stone | `#e9e7e3` | `--color-glass` | surface | Visible navigation wash on stone, made from #ebe9e6 at 55% opacity. |
| Warm stone | `#e7e4e0` | `--color-canvas` | background | Continuous canvas between editorial panels. |
| Soft control fill | `#d5d0cc` | `--color-control` | surface, action | Visible dark-ink 10% fill over stone. Action trays use a lighter 5% version; footer buttons use 10%. |
| Brown hairline | `#d4d0cc` | `--color-edge` | border | Visible brown 10% edge on stone; use rgba(43,27,27,0.1) so the edge adapts to cream or white. |
| Translucent caption stone | `#cbc6c2` | `--color-media-control` | surface | Brown at 15% over stone; actual caption controls pick up the photograph beneath them. |
| Chocolate ink | `#2b1b1b` | `--color-ink` | text, surface, action | Main text, dark resource card and subscription button; also the dark footer variant. |
| Interface black | `#0d0d0f` | `--color-action-ink` | text, action | Navigation and light-stage action labels. |
| Lettering black | `#000000` | `--color-black` | text, accent | High-contrast type specimens and badge text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark product showcases | Espresso stage | `#100401` | `--color-night` | surface | Reversed specimen-stage variant. |
| project portfolios | Gallery paper | `#f3f1ed` | `--color-studio-paper` | background | Warmer continuous gallery chapter surface. |
| project portfolios | Gallery footer beige | `#f7f1ea` | `--color-footer-beige` | background | Light footer variant for a project portfolio. |
| dedicated product pages | Forest action ink | `#384730` | `--color-purchase-ink` | text | Text on the electric-green purchase capsule. |

## Typography

- **MagicUIPro** — All navigation, labels, section headings, supporting copy and forms. Unshowy regular grotesk with a soft, matter-of-fact editorial presence. If unavailable, use **Inter**. Use regular 400; do not turn small headings into bold display text. Font stack: "MagicUIPro", "Inter", Arial, sans-serif.
- **Romie** — Calligraphic word sculptures and the closing line. High-contrast editorial serif; the ornamental artwork uses italic forms, long flourishes, looping capitals and joined letter gestures. If unavailable, use **Cormorant Garamond**. Use italic 400, custom SVG swashes and carefully adjusted line breaks. Font stack: "Romie", "Cormorant Garamond", Georgia, serif.
- **Romie** (only for interactive type specimens) — Oversized editable roman specimen. Fine editorial roman with broad serifs and exuberant discretionary ligatures. If unavailable, use **Cormorant Garamond**. Use light 300 for the Light cut; tune letter joins manually. Font stack: "Romie", "Cormorant Garamond", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| opening-heading | MagicUIPro | 400 | 18px | 1.4 | 0.01em, features "dlig" | Centered opening promise; intentionally small against the imagery. |
| section-heading | MagicUIPro | 400 | 18px | 1.4 | normal, features "dlig" | Centered section introductions and project titles. |
| product-label | MagicUIPro | 400 | 18px | 1.4 | -0.002em, features "dlig" | Product name beside a quantity badge atop a specimen stage. |
| card-copy | MagicUIPro | 400 | 15px | 1.4 | -0.002em, features "dlig" | Compact subscription invitation and resource-card title. |
| navigation | MagicUIPro | 400 | 14px | 1.6 | 0.02em | Navigation links around the central identity. |
| stage-action | MagicUIPro | 400 | 14px | 1.6 | normal | Actions inside the segmented showcase tray. |
| button | MagicUIPro | 400 | 14px | 1.6 | 0.001em | Subscription and purchase capsules. |
| footer-heading | MagicUIPro | 400 | 12px | 1.4 | -0.002em, features "dlig" | Muted footer column labels. |
| footer-link | MagicUIPro | 400 | 12px | 2 | -0.002em, features "dlig" | Short stacked footer links. |
| eyebrow | MagicUIPro | 400 | 11px | 1 | 0.02em | Outlined category capsules and green quantity badges; retain mixed case. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| interactive type specimens | editable-specimen | Romie | 300 | 202.8px | 0.9 | normal, features "dlig", "liga", "ss01", "ss08", "ss09", "ss10", "ss11", "ss12", "ss13", "ss14", "ss15" | Dense centered roman word composition; this is a product demonstration rather than the marketing heading scale. |
| dedicated product pages | product-description | MagicUIPro | 400 | 16px | 1.46 | -0.01em, features "dlig" | Centered concluding product description. |

**Notes:**

- Keep informational hierarchy unusually flat: section headings remain 18px, labels 11px and controls 14px. Scale and ornamental complexity belong to artwork rather than bold sans-serif headlines.
- The principal word sculptures are vector or raster compositions, not ordinary paragraphs. Build them as responsive SVG lettering with an accessible text equivalent; retain a separate small semantic heading.
- Small text uses regular 400 throughout. Tracking is slightly positive on navigation and tiny labels, slightly negative on product labels, cards and footer links.

## Layout

**Density:** Airy exhibition pacing with compact controls: imagery fills the grid while tiny introductions sit in deep breathing spaces.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Badge-to-product-name gap and small action gaps. |
| 12px | Eyebrow-to-heading separation. |
| 16px | Desktop image gutters, side padding and compact card inset. |
| 32px | Footer column gaps and upper inset of the subscription card. |
| 80px | Breathing room between showcase heading, lettering artwork and lower controls. |
| 128px | Opening top inset and separation between major content groups. |
| 180px | Footer separation between utility row and ornamental closing line. |
| 300px | Vertical padding around a centered chapter heading. |
| 450px | Long vertical intervals between staggered portfolio images. |

### Containers and grids

- **Editorial image grid**: 24 columns · gap 16px · side padding 16px. Full-width grid at desktop. A half-width panel spans 12 columns; a quarter-width panel spans 6. Pair two 696px panels or flank one with two 340px panels.
- **Opening arcade**: 3 columns · gap 16px · side padding 16px. Three equal portrait windows, 459px wide at 1440px, beneath the centered heading.
- **Resource measure**: max width 608px · side padding 16px. Centered resource card with text on the left and a near-square artwork on the right.
- **Footer columns**: 4 columns · gap 32px · side padding 42px. Right-side utility groups, each beginning with a muted label; identity and form balance them on the left.
- **Description measure** (only for dedicated product pages): max width 655px · side padding 16px. Centered text-only product conclusion.

## Corner radius

| Element | Radius |
| --- | --- |
| Showcase panels | 32px |
| Section bottom corners | 40px |
| Arch top corners | 900px |
| Arch softened bottom corners | 64px |
| Oval windows | 900px |
| Action tray | 50px |
| Subscription card | 28px |
| Resource card | 20px |
| Label capsules | 10px |
| Buttons and forms | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Stone canvas · level 0

**Use:** Continuous background for media and conversion islands.

**CSS:** `background: #e7e4e0; color: #2b1b1b`

#### Cream stage · level 1

**Use:** Default full-width product showcase.

**CSS:** `background: #fcfbf7; border-radius: 32px; padding: 16px 0; box-shadow: none`

**Observed:** A product label and quantity badge sit above a giant lettering composition, with a small action tray centered below.

**Transfer:** Give one product or core proposition a complete stage instead of placing several ordinary feature cards inside it.

#### Atmospheric interlude · level 0

**Use:** A soft transition behind a small centered heading pair.

**CSS:** `background: radial-gradient(ellipse at 90% 55%, rgba(83,224,139,0.32), rgba(83,224,139,0) 70%), radial-gradient(ellipse at 15% 100%, rgba(244,164,180,0.3), rgba(244,164,180,0) 65%), #e7e4e0`

**Observed:** Diffuse mint collects toward the right and blush toward the lower left; no hard boundaries or visible grain. The field extends across a 682px-tall interlude.

**Transfer:** Match the soft glow; exact stops are not essential. Keep the text small and the atmospheric area broad.

#### Frosted capsule · level 2

**Use:** Navigation and photographic caption controls.

**CSS:** `background: rgba(235,233,230,0.55); backdrop-filter: blur(48px); border-radius: 24px`

**Observed:** Navigation is a narrow floating lens. Media controls instead use brown at 15% opacity to retain contrast against photography.

**Transfer:** Keep glass confined to small utility layers, not every card.

#### Espresso stage · level 1

**Only for:** dark product showcases

**Use:** Reversed showcase variant.

**CSS:** `background: #100401; color: #ffffff; border-radius: 32px; padding: 16px 0`

**Observed:** White ornamental letters dominate the stage; controls use translucent white rather than light neutral fills.

**Transfer:** Use as a deliberate chapter contrast, not as the overall page theme.

#### Portfolio paper · level 0

**Only for:** project portfolios

**Use:** Continuous case-study chapters.

**CSS:** `background: #f3f1ed; border-radius: 0 0 40px 40px`

**Observed:** Project introductions are separated by generous vertical space; imagery is staggered rather than packed.

**Transfer:** Use for a curated collection with substantial project imagery.

## Components

### Floating navigation

**Use:** Persistent compact navigation above the visual story.

**CSS:** `width: 640px; height: 48px; border-radius: 24px; background: rgba(235,233,230,0.55); backdrop-filter: blur(48px); display: flex; align-items: center; justify-content: space-between; padding: 0 4px`

**Text style:** `navigation` — MagicUIPro 400 · 14px/1.6 · tracking 0.02em

**Observed:** Centered near the top with 16px breathing room. Two links flank either side of a central identity. Link targets are 40px high with 16px horizontal inset; the central identity can alternate between roman wordmark and ornamental signature.

**States:** Declared: hover opacity 0.9 on links; focus-visible outline-style none with zero-valued shadow layers.

**Transfer:** Use a compact name or original wordmark in the middle and only a few short navigation nouns.

### Category capsule

**Use:** The tiny category label above a heading.

**CSS:** `border: 1px solid rgba(46,26,27,0.1); border-radius: 10px; padding: 3px 8px 4px; backdrop-filter: blur(48px); color: #2b1b1b`

**Text style:** `eyebrow` — MagicUIPro 400 · 11px/1 · tracking 0.02em

**Observed:** Content-sized, centered and mixed case. The outline is intentionally faint.

**Transfer:** State the product category or chapter type, not an advertising claim.

### Quantity badge

**Use:** Small bright proof next to a product name.

**CSS:** `background: #99ff66; color: #000000; border-radius: 10px; padding: 3px 8px 4px; backdrop-filter: blur(48px)`

**Text style:** `eyebrow` — MagicUIPro 400 · 11px/1 · tracking 0.02em

**Observed:** A compact 18px-high pill adjacent to the product label, separated by 8px.

**Transfer:** Use a true compact count or availability fact.

### Showcase action tray

**Use:** Grouped explore, trial and purchase decisions.

**CSS:** `display: flex; gap: 8px; padding: 4px; height: 64px; border-radius: 50px; background: rgba(46,26,27,0.05)`

**Text style:** `stage-action` — MagicUIPro 400 · 14px/1.6

**Observed:** Three equal 114px-wide, 56px-high segments; a darker translucent capsule highlights the purchase segment. Two-action variants use 173px-wide segments and a 4px gap. White translucent fills replace brown in the dark showcase.

**States:** Declared: hover opacity 0.9 on segment links; focus-visible outline-style none with zero-valued shadow layers.

**Transfer:** Keep the actions together beneath the main artifact instead of scattering buttons around it.

### Arched media window

**Use:** Dominant photographic proof panel.

**CSS:** `position: relative; overflow: hidden; border-radius: 900px 900px 64px 64px`

**Observed:** A half-width portrait panel is 696px by 870px. Other windows have square lower corners, fully oval ends or 32px rounded rectangles; images fill the mask without inner borders.

**Transfer:** Use the same geometric family across product photography, use cases and original typographic art. Keep key subjects inside the arch's central safe area.

### Media credit reveal

**Use:** Discreet attribution attached to photographic proof.

**CSS:** `position: absolute; height: 32px; padding: 0 14px; background: rgba(43,27,27,0.15); backdrop-filter: blur(48px); border-radius: 32px; color: #ffffff`

**Text style:** `footer-link` — MagicUIPro 400 · 12px/2 · tracking -0.002em

**Observed:** Resting presentation reads as a small translucent plus circle near a lower image corner; the full capsule reveals a credit. Some credits remain fully expanded and use 12px/20px text. The control overlays the image, never forms a separate card footer.

**Transfer:** Keep attribution factual and close to the work; preserve the small plus affordance.

### Subscription card

**Use:** A compact conversion island after the visual exhibition.

**CSS:** `width: 482px; display: flex; flex-direction: column; align-items: center; gap: 16px; padding: 32px 16px 16px; background: #ffffff; border-radius: 28px; overflow: hidden`

**Text style:** `card-copy` — MagicUIPro 400 · 15px/1.4 · tracking -0.002em

**Observed:** Centered title, two-line muted invitation, email capsule and a broad lower artwork combining abstract black lettering with editorial photography. Lower image area is 450px by 310px.

**Transfer:** Make the art part of the invitation, not a decorative thumbnail beside a long form.

### Email capsule

**Use:** One-field subscription in the card or footer.

**CSS:** `display: flex; gap: 4px; height: 56px; padding: 3px 4px 3px 20px; border: 1px solid rgba(43,27,27,0.1); border-radius: 9999px`

**Text style:** `button` — MagicUIPro 400 · 14px/1.6 · tracking 0.001em

**Observed:** Transparent input grows to fill available space, with the Subscribe button nested at the right. Width is 450px in the card and 294px in the footer. The dark-footer variant uses a faint white edge and translucent white backing.

**Transfer:** Keep to a single short field and inline action.

### Subscribe button

**Use:** Primary form submission.

**CSS:** `height: 48px; padding: 0 20px; border-radius: 9999px; background: #2b1b1b; color: #ffffff; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — MagicUIPro 400 · 14px/1.6 · tracking 0.001em

**Observed:** Compact nested capsule. The light footer uses a 10% dark-ink fill and dark label instead; the dark footer uses a 15% white fill.

**States:** Declared: hover opacity 0.9; focus-visible outline-style none with zero-valued shadow layers.

### Resource card

**Use:** Low-pressure downloadable entry offer.

**CSS:** `max-width: 608px; padding: 16px; background: #2b1b1b; color: #ffffff; border-radius: 20px; overflow: hidden`

**Text style:** `card-copy` — MagicUIPro 400 · 15px/1.4 · tracking -0.002em

**Observed:** Landscape card centered in open stone space. Small status and title occupy the left; a white 72px by 40px download capsule sits at its lower edge. A 272px square cream-backed letter study occupies the right half.

**Transfer:** Use a useful sample, preview or guide with an original enlarged detail as its artwork.

### Footer link

**Use:** Small utility navigation beneath muted column headings.

**CSS:** `color: #2b1b1b; line-height: 24px; max-width: 100%`

**Text style:** `footer-link` — MagicUIPro 400 · 12px/2 · tracking -0.002em

**Observed:** Left-aligned columns rather than a dense centered menu. Column headings are at 50% opacity with 12px bottom spacing; dark-footer links reverse to white.

**States:** Declared: hover opacity 0.8; focus-visible 1px bottom border at 50% black and outline-style none.

### Product purchase capsule

**Only for:** dedicated product pages

**Use:** A persistent purchase action during an extended proof gallery.

**CSS:** `height: 48px; width: 169px; padding: 0 14px; border-radius: 100px; background: #99ff66; color: #384730`

**Text style:** `button` — MagicUIPro 400 · 14px/1.6 · tracking 0.001em

**Observed:** Centered near the bottom of the viewport, independent of the gallery columns.

**States:** Declared: hover background-color #d5fec6; focus-visible outline-style none with zero-valued shadow layers.

**Transfer:** Reserve this bright floating treatment for a single-product journey.

## Imagery and graphics

### Editorial material photography

**Use:** Opening arcade and most of the proof gallery.

**Observed:** Fashion portraits, tactile objects, close-ups of textiles, printed books, architectural signage and lived-in scenes. Lighting ranges from warm natural daylight to controlled editorial contrast. Rich turquoise, burgundy, pink and olive appear inside photographs while the surrounding canvas stays neutral. Images occupy far more space than their captions.

**Transfer:** Photograph the product in a believable cultural or material setting, include one close detail and one human-scale use scene. For an intangible product, art-direct printed outputs, a real screen in a workspace or a hand-held object rather than a floating generic interface.

### Ornamental word sculpture

**Use:** Signature showcase artwork and the monumental closing line.

**Observed:** High-contrast serif and italic letters overlap, curl into generous swashes and form carefully balanced two- or three-line compositions. Default showcase art is warm dark grey on cream; reversed specimens are cream or white on near-black. Artwork uses the full width, with image boxes 1440px by 423–520px. The closing SVG spans 1356px by 119px.

**Transfer:** Compose a brief original product promise or name as lettering. Minimum acceptable treatment is a well-kerned italic serif composition with two custom terminal flourishes; it must feel authored rather than a stock script font.

**Build:** Create a responsive SVG with a 1440px-wide viewBox. Set two or three centered lines in the ornamental family, give each line its own horizontal offset and manually adjust letter joins. Extend selected capital and terminal strokes with thin cubic Bezier paths, matching the glyph hairline and heavier downstrokes. Keep flourishes within the viewBox and use currentColor. For the closing line, create a separate shallow 1356px by 119px composition, fitted as a single sweeping line.

### Mint and blush atmosphere

**Use:** Signature breathing space between major visual chapters.

**Observed:** Large, blurred pastel color fields wash across the stone canvas: mint on the right and blush near the bottom left, leaving a low-contrast central area for tiny text.

**Transfer:** Use as an atmospheric pause rather than a rainbow panel or a gradient text effect.

**Build:** Layer two full-area radial gradients over the Stone canvas: green rgba(83,224,139,0.32) centered at 90% 55% fading by 70%, and pink rgba(244,164,180,0.3) centered at 15% 100% fading by 65%. Keep the transition broad and smooth across about 682px of section height.

### Specimen and use pairing

**Use:** Visual proof chapters between product stages.

**Observed:** A black-backed typographic poster often sits beside a real-world application. The poster uses enormous cream letters, a tiny emblem at the top and a tiny attribution at the bottom, framed in an arch or oval. Adjacent photography shows the result as a book, garment, object or campaign.

**Transfer:** Pair a clean original product study with its real use. If no finished application exists, create a simple physical mockup photographed under natural light.

**Build:** Place an original short word composition in a black SVG rectangle clipped by the Arched media window. Center a small original emblem above the words and a fine italic credit below. Use cream lettering and reserve a consistent safe margin inside the curved top.

### Icons

**Observed:** Utility glyphs are predominantly filled 14px icons, especially plus signs inside translucent photographic controls; a 16px download glyph sits in a white capsule. Decorative identity emblems are larger, intricate line-based monograms rather than UI icons.

**Transfer:** Use spare plus, arrow and download forms for utilities. Create one original ornamental emblem for identity; do not turn all navigation into ornate icons.

## Section recipes

How recurring sections are built.

### First screen: Arcade opening

**Observed:** Cream stage begins behind the Floating navigation, a centered 640px-wide, 48px-high lens with 16px top breathing room. A Category capsule appears at the 128px top inset, followed 12px later by the 18px Opening-heading. A 16px gap introduces three equal photographic arches spanning almost the whole width within 16px side padding. Each is 459px by 819px at desktop, with 900px top radii; the outer lower corners soften the group. The first 900px shows navigation, category, full heading and most of the three photographs, but not their bottoms. The complete cream section extends to 1028px and ends in 40px rounded lower corners. There is no hero button or long support paragraph; navigation carries the initial actions.

**Transfer:** Use three complementary original images: product detail, human-scale context and a tactile application. With limited media, create three carefully differentiated photographic or typographic studies of one product. Portfolio pages instead open with a small centered category/title and emblem surrounded by 300px vertical padding; dedicated product pages open with a green quantity badge and a large two-line roman/italic title artwork above one wide proof image and a purchase capsule.

**Avoid:** Do not replace the arcade with a left-aligned oversized sans-serif slogan beside a small device mockup, or place a conversion form over the photographs.

**Text style:** `opening-heading` — MagicUIPro 400 · 18px/1.4 · tracking 0.01em

### Atmospheric heading pair

**Observed:** Atmospheric interlude contains a Category capsule above a centered Section-heading, separated by 12px. The heading is usually one or two short lines. 300px top and bottom padding create a 682px-tall pause; the following Cream stage overlaps the lower edge by 32px.

**Transfer:** Use a concise benefit or chapter introduction. Keep the color field and tiny typography in tension rather than filling the space with more copy.

**Text style:** `section-heading` — MagicUIPro 400 · 18px/1.4

### Monumental product stage

**Observed:** Cream stage places Product-label and Quantity badge together at the upper center. Ornamental word sculpture occupies the middle; the Showcase action tray is centered beneath it. Stage heights are 736–833px with 32px radii. The Espresso stage is a reversed alternative, not the default.

**Transfer:** Present a product's expressive identity or one strong benefit as an authored word composition; keep explanatory copy elsewhere.

**Text style:** `product-label` — MagicUIPro 400 · 18px/1.4 · tracking -0.002em

### Editorial proof mosaic

**Observed:** Editorial image grid alternates paired half-width windows with one dominant middle panel flanked by quarter-width panels. Arches, ovals and rounded rectangles interrupt the grid without decorative borders. Media credit reveal controls sit on image corners. Some chapters expand to one full-width image or video.

**Transfer:** Alternate scale and mask to distinguish kinds of proof. Use genuine product output, human context and close detail rather than equally sized feature cards.

### Small conversion islands

**Observed:** A Resource card is centered within 146px top and bottom breathing room. A separate Subscription card sits later in stone space, with art below the email form. The surrounding page stays visually empty enough to make both objects feel intentional.

**Transfer:** Offer a useful low-pressure entry point, then a short ongoing invitation. Preserve the distinction between downloadable resource and email relationship.

**Text style:** `card-copy` — MagicUIPro 400 · 15px/1.4 · tracking -0.002em

### Ornamental curtain footer

**Observed:** Light cream footer is 551px tall with 64px top, 42px side and 48px bottom padding. The upper row balances emblem and Email capsule on the left against four utility columns on the right. A 180px separation leads to a 1356px-wide ornamental closing line; tiny centered copyright follows. The portfolio variant is beige; dedicated product pages reverse the footer to chocolate with white artwork and links.

**Transfer:** Finish every page with an original sweeping typographic sign-off. Keep the closing artwork distinct from a conventional heading and retain the small functional navigation above it.

**Text style:** `footer-link` — MagicUIPro 400 · 12px/2 · tracking -0.002em

### Portfolio chapter

**Only for:** project portfolios

**Observed:** Portfolio paper carries an isolated Category capsule, 18px project title and a small emblem. Introductions use 300px vertical padding. A central 577px by 800px image anchors staggered 399px-wide supporting images, often separated vertically by 450px.

**Transfer:** Give each case study an exhibition-like pause and a dominant central image. Vary project length with the available proof rather than repeating a rigid card template.

**Text style:** `section-heading` — MagicUIPro 400 · 18px/1.4

### Descriptive product close

**Only for:** dedicated product pages

**Observed:** A centered 655px text measure uses Product-description with 128px vertical padding. A dark More Info capsule sits about 32px below the prose; the floating purchase action remains present before the dark footer.

**Transfer:** Conclude a visual product journey with craft, use and distinguishing character rather than another oversized promise.

**Text style:** `product-description` — MagicUIPro 400 · 16px/1.46 · tracking -0.01em

## Page flow

**Storyline:** visual identity → small editorial promise → expressive product stage → real-world proof → low-pressure action → ornamental sign-off

### A collection-oriented marketing landing page

1. **Visual promise** — Three tall arched photographs beneath a restrained category and headline.
2. **Positioning** — Small centered benefit statement in a pastel atmospheric field.
3. **Product demonstration** — Monumental lettering stages punctuate extensive image mosaics.
4. **Conversion** — Centered resource card and art-led subscription card.
5. **Closing identity** — Utility footer with sweeping ornamental line.

**Transfer:** Let product expression and actual use alternate; adapt the number and order of chapters to the story.

### A curated portfolio of substantial projects

1. **Chapter introduction** — Tiny category capsule, centered project title and small emblem.
2. **Proof** — Central portrait anchor with staggered supporting images.
3. **Closing proof** — Final lettering project followed by a rounded end to the gallery surface.
4. **Closing identity** — Stone breathing space then the beige utility and ornamental footer.

**Transfer:** Use isolated chapter titles to pace heterogeneous case studies without descriptive essays.

### An immersive single-product detail journey

1. **Product identity** — Large roman/italic title artwork, tiny quantity badge and wide contextual image.
2. **Product demonstration** — Editable oversized type specimen with compact controls.
3. **Proof** — Extended image gallery with a centered persistent green purchase capsule.
4. **Context and final action** — Centered descriptive paragraph and More Info button.
5. **Closing identity** — Chocolate reversed footer with the shared ornamental line.

**Transfer:** Replace the type tester with the product's own focused demonstration; keep UI internals subordinate to the gallery and singular purchase action.

## Writing

Cultured, warm and assured without a sales pitch. Most copy acts like a gallery label; the occasional longer description is tactile, referential and expressive.

**Do not copy:** Do not reuse Claude's names, wordmarks, monograms, ornamental artworks, client names, project credits, proprietary specimen phrases, claims or product counts. Source examples demonstrate structure and tone only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Short labels are largely impersonal. Benefits can address the reader's work as 'your designs'; product descriptions refer to the product in the third person.
- **Rhythm:** Headings are brief noun phrases or one restrained benefit sentence. Controls are one or two words. Credits are factual fragments; long expressive prose is reserved for the product conclusion.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A concise statement of the product's world or craft, not a shouted claim. | 4–7 words | “Maison of Ornamental Letters” |
| Section heading | Quality plus object plus benefit to the reader's work. | 5–9 words | “Elegant Typefaces to Enhance Your Designs” |
| Category | Compact designation of discipline or format. | 2–5 words | “Custom Rug & Lettering”<br>“French Type Foundry” |
| Action | Plain, familiar verb; no persuasive flourish. | 1–2 words | “Explore”<br>“More Info”<br>“Subscribe” |
| Invitation | Name the publication or offer, then state the kind of content. | One short sentence | “THE TWO: Design reflections, inspirations, and exclusive content on Substack” |
| Product description | Begin with a vivid distinction, then describe craft and use through concrete qualities. | One considered paragraph | “An editorial roman headline typeface without the dusty pastiche” |

**Words and phrasing to use:** ornamental; editorial; craft; reflections; inspirations; custom; in use; designed by

**Avoid:** revolutionary; 10x; unlock your potential; game-changing; limited-time urgency; excessive exclamation marks

**Rules:**

- Treat visual proof captions as credits, not miniature advertisements.
- Prefer specific material or formal qualities to unsupported superlatives.
- Use title case sparingly; mixed-case labels keep the atmosphere approachable.
- Keep ornamental display phrases short enough to be shaped into a composition.

## Do's and Don'ts

### Do

- Keep ordinary headings at 18px and weight 400, even when surrounded by monumental artwork.
- Use 16px gutters and side padding for the desktop image grid.
- Give showcase panels 32px corners and the opening section 40px lower corners.
- Keep badges at 11px with 0.02em tracking and an 18px-high bright quantity treatment.
- Place one original ornamental word sculpture on a spacious stage and a separate sweeping line in the footer.
- Keep standalone subscription actions 48px high inside 56px email capsules.
- Mix 696px and 340px image widths rather than repeating one uniform tile size.
- Reserve a broad mint/blush atmosphere for a tiny centered heading pair.

### Don't

- Do not make the informational sans-serif typography bold or substitute a large 64px marketing heading for the 18px role.
- Do not use electric green as the general page background; it is concentrated in small badges and the scoped purchase action.
- Do not replace 900px arches with uniformly rounded 8px cards.
- Do not add visible drop shadows to every media window; separation comes from masks, cream surfaces and stone gaps.
- Do not turn the centered action tray into disconnected rectangular buttons.
- Do not fill the 300px chapter breathing spaces with decorative charts or extra paragraphs.
- Do not add a color overlay that flattens the natural turquoise, burgundy, pink and olive in the photographs.
- Do not shrink the ornamental closing line to a small logo in a conventional utility footer.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions are declared at 0.15s cubic-bezier(.4,0,.2,1); a small number use 0.3s with the same curve.
- Navigation and main actions declare hover opacity 0.9; footer links use 0.8. The dedicated purchase capsule changes to pale green on hover.
- Media controls use clipped capsules whose resting appearance is a plus circle. Navigation identity alternates between a roman wordmark and an ornamental signature.
- Some gallery wrappers carry a translateY(-50px) transform.

**Transfer:**

- Keep interactions subordinate to the artwork: small opacity shifts and caption disclosure, not bouncing buttons.
- Preserve the plus-to-credit reveal as a discreet way to attach attribution without permanent text blocks.

**Unknown:**

- Timing and easing of the media-control reveal, identity alternation, scrolling effects and page transitions are not established.

### Responsive

**Observed:**

- Declared width breakpoints: 640px, 768px, 1024px, 1280px and 1536px.
- Below the medium breakpoint, outer opening photographs are hidden and the center spans all three columns with 32px rounding.
- Gallery classes change half-width desktop panels to full-width panels below the medium breakpoint. Footer utility columns become a two-column grid below the large breakpoint.

**Transfer:**

- Keep the single central opening photograph visually dominant on narrow screens; retain the small centered heading above it.
- Allow word sculptures to scale as SVG artwork rather than wrapping with ordinary text flow.
- Let the Subscription card fit the available width and stack the Resource card's text and artwork where necessary.

**Unknown:**

- Exact narrow-screen appearance, mobile navigation expansion and artwork fit have not been established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
