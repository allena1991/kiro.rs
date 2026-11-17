# Bauhaus Clock — soft machined delight

## Overview

A light, object-loving product style with the feeling of carefully finished consumer hardware. Cool gray and watery mint surround dark grotesk typography, glossy controls and oversized product imagery. Domestic photography, tactile interface close-ups and softly embossed lettering make a sparse page feel personal rather than clinical. It suits crafted software and design-led products whose details reward a closer look.

### Essentials

- A single thought becomes a wide typographic object: centered 96px/1 grotesk at weight 600 with -0.0125em tracking and a subtle dark-to-translucent text gradient.
- The opening gives the product room to breathe: a floating identity-and-purchase bar, a 48px cyan announcement capsule, then a broad headline above a 1340px-wide rounded media stage with 50px side margins.
- Controls feel machined rather than flat: dark radial-gradient purchase pills use 100px radii, white lettering, top-edge inset light and layered downward shadows; the smaller header action is 64px high.
- Color lives in objects and selected stages: the long default canvas is #eef0f2 with white cards; mint marks quotes and one expansive product stage, while richly colored texture remains bounded inside 30px-rounded panels.
- Show details at nearly physical scale: use a broad environmental product scene plus oversized isolated details in asymmetric cards, separated by 50px gutters. Without photography, stage one crisp product rendering against a softly lit teal material.
- End with a pale typographic relief: the product name spans almost the entire container at 215px/1.2, weight 500, -0.015em tracking, with #d6d9db lettering and opposing light/shade text shadows; small maker and legal links sit underneath.
- Proof feels like a collection of personal notes: white 30px-rounded review cards, 30px padding, mint highlighted phrases and horizontally overflowing rows whose ends fade into the canvas.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Watery mint stage | `#a1e5e4` | `--color-mint-stage` | surface | Expansive product-detail stage, with a brighter cyan texture or softly lit product artwork layered over it. |
| Ice blue | `#d6f6ff` | `--color-capsule-top` | surface | Upper stop of the announcement capsule. |
| Mint quote backing | `#c8eaea` | `--color-quote-tint` | surface | Featured conversion quotation. |
| Mint text marker | `#d5efef` | `--color-highlight` | surface | Inline backing behind selected bold testimonial phrases. |
| Ice white | `#f2ffff` | `--color-capsule-bottom` | surface | Lower stop of the announcement capsule. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#04080d` | `--color-ink` | text, action | Primary headings and the darkest purchase-button stop. |
| Charcoal | `#121317` | `--color-body` | text | Support statements, quotations and card titles; also the translucent end of the headline gradient. |
| Secondary link gray | `#4a4e52` | `--color-muted` | link, text | Visible result of 70% near-black over the default canvas, used for maker and legal links. |
| Graphite highlight | `#6d6f73` | `--color-button-light` | surface | Upper radial highlight of dark purchase pills. |
| Relief gray | `#d6d9db` | `--color-relief` | text | Monumental closing product name. |
| Cool gray canvas | `#eef0f2` | `--color-canvas` | background | Default marketing background. |
| Porcelain white | `#ffffff` | `--color-white` | surface, text | Feature cards, review cards, inverted button text and inset highlights. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| mobile-app product landing pages | Aqua relief | `#c7d9d9` | `--color-app-relief` | text | Closing product-name lettering against the aqua canvas. |
| mobile-app product landing pages | Aqua canvas | `#dfeeee` | `--color-app-canvas` | background | Full-page mint-tinted background instead of cool gray. |

## Typography

- **ui-sans-serif** — All marketing headlines, prose, controls and closing lettering. System grotesk with open counters, restrained regular text and firm semibold headlines; no separate decorative display face. Font stack: "ui-sans-serif", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| relief-name | ui-sans-serif | 500 | 215px | 1.2 | -0.015em | Oversized closing product-name lettering. |
| display | ui-sans-serif | 600 | 96px | 1 | -0.0125em | Centered opening headline, one broad line or two balanced lines. |
| heading | ui-sans-serif | 600 | 60px | 64px | -0.0167em | Core section lead and compact two-line proof headings. |
| closing-heading | ui-sans-serif | 600 | 60px | 1.2 | -0.0167em | Conversion and question-section leads. |
| card-heading | ui-sans-serif | 600 | 40px | 1.1 | -0.005em | Centered feature-card titles. |
| lead | ui-sans-serif | 400 | 32px | 1.3 | 0.0063em | Large introductory support under a section heading. |
| benefit | ui-sans-serif | 400 | 32px | 1.4 | 0.0063em | Comfortably spaced conversion benefit statements. |
| quote | ui-sans-serif | 400 | 32px | 1.2 | 0.0063em | Featured personal quotations. |
| button-large | ui-sans-serif | 400 | 32px | 1.2 | normal | Large standalone purchase action and header identity. |
| button | ui-sans-serif | 500 | 24px | 1.2 | 0.0083em | Compact header purchase action. |
| body | ui-sans-serif | 400 | 20px | 1.25 | 0.01em | Feature descriptions and practical purchase notes. |
| review | ui-sans-serif | 400 | 20px | 1.4 | -0.01em | Left-aligned text in the review collection. |
| review-emphasis | ui-sans-serif | 600 | 20px | 1.4 | -0.01em | Selected phrases within reviews, paired with a mint marker. |
| question | ui-sans-serif | 600 | 20px | 1.2 | normal | FAQ question labels. |
| announcement | ui-sans-serif | 500 | 20px | 1.25 | 0.01em | Short announcement capsule labels. |
| maker-link | ui-sans-serif | 500 | 20px | 1.2 | normal | Personal maker credit under the closing name. |
| footer-link | ui-sans-serif | 400 | 20px | 1.2 | normal | Small closing utility links. |

**Notes:**

- The strongest hierarchy comes from size and line length rather than many weights: 96px opening, 60px section statement, 40px feature title, 32px lead or quote, 20px body.
- Use negative tracking on headings, slight positive tracking on centered support, and tighter review prose. Do not apply one tracking value globally.
- The opening headline uses background-clipped text: a 140deg gradient from near-black to charcoal at 70% opacity. Keep the effect tonal, not rainbow-colored.

## Layout

**Density:** Airy: broad media fields and 100px–150px chapter pauses alternate with compact 15px–30px text stacks.

### Spacing

| Value | Use |
| --- | --- |
| 15px | Benefit-row spacing, review content gap and quotation-to-attribution separation. |
| 20px | Feature heading-to-description gap. |
| 25px | Header inner padding and compact featured-quote vertical padding. |
| 30px | Review-card padding, conversion heading gap and media-caption stacks. |
| 50px | Desktop page sides, feature-grid gutters and heading-to-object separation inside cards. |
| 75px | Feature-card top and side padding. |
| 100px | Within major product chapters and between opening headline group and media. |
| 150px | Separation between major narrative chapters. |

### Containers and grids

- **main container**: max width 1340px · side padding 50px. Centered desktop composition for wide media and feature chapters at a 1440px viewport.
- **floating header**: max width 1390px · side padding 25px. Wider than the main container, fixed above the page with identity left and purchase action right.
- **feature grid**: 6 columns · gap 50px. Six-column underlying grid allows a four-column wide feature beside a two-column stack; full-width demonstrations span all six.
- **statement**: max width 1040px. Centered section statements; support text is narrower than the heading.
- **questions**: max width 800px. Centered FAQ stack with 15px inner inset and 770px-wide rows.

## Corner radius

| Element | Radius |
| --- | --- |
| feature and review cards | 30px |
| action capsules | 100px |
| portraits | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| feature edge | `rgba(18, 19, 23, 0.02) 0px 0px 0px 1px` | Near-invisible dark edge around white feature panels. |
| purchase pill | `rgba(7, 15, 26, 0.09) 0px 0.6px 0.6px -0.4px, rgba(7, 15, 26, 0.1) 0px 1.7px 1.7px -0.8px, rgba(7, 15, 26, 0.12) 0px 4.5px 4.5px -1.1px, rgba(7, 15, 26, 0.2) 0px 14px 14px -1.5px, rgba(240, 252, 255, 0.2) 0px 2px 10px 1px inset, rgba(235, 251, 255, 0.2) 0px 0px 2px 1px inset, rgba(255, 255, 255, 0.2) 0px 2px 0.5px 0px inset` | Raised, polished dark purchase controls. |

### Surfaces

#### Canvas · level 0

**Use:** Default long-form marketing background.

**CSS:** `background: #eef0f2`

#### Porcelain panel · level 1

**Use:** Feature demonstrations and grouped explanatory content.

**CSS:** `background: #ffffff; border-radius: 30px; box-shadow: rgba(18, 19, 23, 0.02) 0px 0px 0px 1px`

**Observed:** Very low edge contrast; the object and title supply the hierarchy instead of a strong border.

**Transfer:** Use white as a product stage, not a generic dashboard tile.

#### Mint product stage · level 1

**Use:** A large color-led detail demonstration.

**CSS:** `background: #a1e5e4; border-radius: 30px; overflow: hidden`

**Observed:** Broad turquoise field with pale, softly mottled lighting behind a giant product detail.

**Transfer:** Keep this bounded by the main container, and let it occupy a full feature row.

#### Floating glass · level 2

**Use:** The translucent backing of the fixed navigation.

**CSS:** `background: linear-gradient(rgba(245, 247, 249, 0.97) 0%, rgba(241, 242, 243, 0.97) 100%); border-radius: 100px; backdrop-filter: blur(9px); box-shadow: inset 0px 2px 0.5px #ffffff, inset 0px 1px 1px rgba(255, 255, 255, 0.5), 0px 10px 10px -1.5px rgba(0, 0, 0, 0.08)`

**Observed:** The backing is faint at the opening and becomes a clearly visible pill over scrolling content; identity and action remain crisp.

**Transfer:** Separate the glass backing from foreground content so transparency never fades the labels.

#### Aqua canvas · level 0

**Only for:** mobile-app product landing pages

**Use:** A product-line theme variant.

**CSS:** `background: #dfeeee`

**Observed:** The same sparse typography and white cards sit on a continuous aqua field.

**Transfer:** Use this as a whole-page variant rather than mixing alternate canvases section by section.

## Components

### Floating navigation

**Use:** Persistent product identity and one conversion action.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 25px; border-radius: 100px; max-width: 1390px`

**Text style:** `button-large` — ui-sans-serif 400 · 32px/1.2

**Observed:** A small product-shaped emblem leads the identity; a lower-contrast platform suffix follows inline. The Purchase pill occupies the opposite end. The bar floats inside a 25px outer inset. A mobile-app variant adds a QR code beside the action.

**Transfer:** Use one recognisable object or simple emblem, an identity and a single action, not a menu of many destinations.

### Purchase pill

**Use:** Main conversion control in the persistent header.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; height: 64px; padding: 15px 25px; border-radius: 100px; color: #ffffff; background: radial-gradient(53% 128% at 36.4% -18.1%, #6d6f73 0%, #04080d 95.8527%); box-shadow: rgba(7, 15, 26, 0.09) 0px 0.6px 0.6px -0.4px, rgba(7, 15, 26, 0.1) 0px 1.7px 1.7px -0.8px, rgba(7, 15, 26, 0.12) 0px 4.5px 4.5px -1.1px, rgba(7, 15, 26, 0.2) 0px 14px 14px -1.5px, rgba(240, 252, 255, 0.2) 0px 2px 10px 1px inset, rgba(235, 251, 255, 0.2) 0px 0px 2px 1px inset, rgba(255, 255, 255, 0.2) 0px 2px 0.5px 0px inset; box-sizing: border-box`

**Text style:** `button` — ui-sans-serif 500 · 24px/1.2 · tracking 0.0083em

**Observed:** Platform symbol precedes the label; price may be included inline. The standalone conversion variant is 90px high with 25px 35px padding, a 12px icon gap and the button-large recipe.

**Transfer:** Preserve the polished dark material and compact verb-led label.

### Announcement capsule

**Use:** Cross-product or availability link above the hero.

**CSS:** `display: flex; align-items: center; padding: 8px 6px 8px 16px; height: 48px; box-sizing: border-box; border-radius: 100px; color: #04080d; background: linear-gradient(#d6f6ff 0%, #f2ffff 100%); box-shadow: rgba(255, 255, 255, 0.5) 0px 2px 0.5px 0px inset, rgba(255, 255, 255, 0.5) 0px 1px 1px 0px inset, rgba(0, 141, 176, 0.05) 0px 0px 1px 0px, rgba(0, 140, 140, 0.1) 0px 8px 15px 0px, rgba(0, 141, 176, 0.15) 0px 0px 0px 1px`

**Text style:** `announcement` — ui-sans-serif 500 · 20px/1.25 · tracking 0.01em

**Observed:** A glowing turquoise status dot or small product symbol leads; a soft gray chevron closes the capsule.

**Transfer:** Use a short piece of genuine availability news rather than an uppercase category label.

### Feature panel

**Use:** A focused product capability paired with a large visual.

**CSS:** `background: #ffffff; border-radius: 30px; padding: 75px; display: flex; flex-direction: column; align-items: center; gap: 50px; box-shadow: rgba(18, 19, 23, 0.02) 0px 0px 0px 1px`

**Text style:** `card-heading` — ui-sans-serif 600 · 40px/1.1 · tracking -0.005em

**Observed:** Title and brief description form a centered group above isolated objects. Full-width comparison panels crop the lower edges of the hardware; a tall material-backed variant holds a floating settings window.

**Transfer:** Vary panel proportions around the shape of the product demonstration rather than making every panel equal.

### Review card

**Use:** Personal proof in horizontally overflowing collections.

**CSS:** `background: #ffffff; border-radius: 30px; padding: 30px; width: 350px; display: flex; flex-direction: column; gap: 15px`

**Text style:** `review` — ui-sans-serif 400 · 20px/1.4 · tracking -0.01em

**Observed:** Left-aligned quotation with selected bold mint-backed phrases and the author at the bottom. Two rows have different card heights; the row fades at both ends. The mobile-app variant uses stars, title, date and body in 360px-wide cards.

**Transfer:** Keep real wording and varying text lengths; retain the selected-phrase marker and edge fade.

### Featured quote

**Use:** A compact endorsement between benefits and conversion.

**CSS:** `background: #c8eaea; border-radius: 30px; padding: 25px 20px; width: 502px; display: flex; flex-direction: column; align-items: center; gap: 15px; box-shadow: rgba(18, 19, 23, 0.02) 0px 0px 0px 1px inset`

**Text style:** `quote` — ui-sans-serif 400 · 32px/1.2 · tracking 0.0063em

**Observed:** Centered quotation over a circular portrait and a two-line author attribution. The mobile-app variant is white, 771px wide with 40px padding and a longer quotation.

**Transfer:** Place one credible human voice close to the action, distinct from the surrounding review collection.

### Question row

**Use:** Low-contrast objection handling in a centered FAQ stack.

**CSS:** `max-width: 770px; min-height: 97px; padding: 30px; box-sizing: border-box; border-radius: 30px; backdrop-filter: blur(9px); display: flex; align-items: center; gap: 50px; color: #04080d`

**Text style:** `question` — ui-sans-serif 600 · 20px/1.2

**Observed:** The resting row blends into the canvas without a visible fill or rule. A small down-chevron sits at the far right; rows are separated by 15px.

**Transfer:** Keep questions concise and left aligned; do not turn this section into another white card grid.

### Relief footer

**Use:** Large, low-contrast brand sign-off and minimal utilities.

**CSS:** `max-width: 1340px; display: flex; flex-direction: column; align-items: center; gap: 15px`

**Text style:** `relief-name` — ui-sans-serif 500 · 215px/1.2 · tracking -0.015em

**Observed:** The product name is almost container-wide, pale gray and lightly embossed. Beneath it a single line places the maker credit left and legal links right; no sitemap columns. The aqua theme changes the large lettering to aqua relief.

**Transfer:** Fit the new name to the available width while preserving its monumental scale; retain the shallow relief instead of using a dark logo.

### Maker link

**Use:** A personal finishing touch beneath the monumental name.

**CSS:** `color: rgba(4, 8, 13, 0.7); text-decoration: none`

**Text style:** `maker-link` — ui-sans-serif 500 · 20px/1.2

**Observed:** An outbound arrow is part of the text; adjacent utility links use footer-link at regular weight.

**States:** Declared: hover color #04080d and no underline; focus-visible not specified.

**Transfer:** Keep the credit personal and brief.

## Imagery and graphics

### Environmental product film

**Use:** Broad opening media stage.

**Observed:** A real desktop monitor fills a bright, lived-in studio with an articulated lamp, framed art and plants. Cool mint screen light is balanced by soft natural room colors. The scene is wide, rounded at 30px, and occupies much more area than the opening text.

**Transfer:** Photograph or render the new product in a believable, design-conscious setting with diffuse daylight. Minimum acceptable treatment is a carefully framed product still in the same wide media stage, not a blank player.

### Tactile product detail

**Use:** At least one expansive feature demonstration and smaller capability panels.

**Observed:** Giant dial details, dimensional ticks, softly raised hands, circular finish swatches and light/dark hardware comparisons turn software into an object. White panels isolate the product; the mint panel gives it an immersive color field.

**Transfer:** Enlarge the new product's most distinctive detail. For nonvisual software, create one clear interface specimen with physical depth and intentional light rather than a collage of tiny screens.

**Build:** For a minimum product stage, use a 30px-clipped mint rectangle, a broad pale cyan radial wash behind the object, and a centered SVG or rendered interface occupying roughly three quarters of the width. Give object edges one narrow highlight and one soft downward shadow; keep headings above, never over the object.

### Teal material panel

**Use:** One tall, immersive capability card.

**Observed:** Deep turquoise, mottled stone-like material fills the rounded panel, with visible grain and pale irregular seams. White title and support sit above a sharply rendered, light-colored settings panel that casts a substantial soft shadow.

**Transfer:** Use a tactile teal material behind a clean product-detail specimen; the material should remain subordinate to the foreground interface.

**Build:** Make an SVG backdrop with low-frequency fractal noise colored in deep teal and cyan, overlay fine grain at low opacity, and add one or two thin irregular pale seam paths near the lower half. Clip to 30px. Center the foreground panel below the white text and give it a dark teal drop shadow; match the material's depth rather than exact noise patterns.

### Embossed name artwork

**Use:** Signature closing graphic.

**Observed:** The large name nearly disappears into the cool canvas while retaining a shallow pressed or raised edge.

**Transfer:** Use the new product name as typography, not a replacement illustration.

**Build:** Set the relief-name recipe in the relief color. Apply text-shadow: 0px 2px 3px rgba(255,255,255,0.5), 0px -2px 3px rgba(0,0,0,0.04). Keep it on the uninterrupted page canvas.

### Rating seal

**Only for:** mobile-app product landing pages

**Use:** Compact quantitative proof directly under the opening support line.

**Observed:** A subdued dark rating numeral sits beside five stars and a small average-rating label, bracketed by symmetrical laurel branches. The complete graphic is 324px by 66px.

**Transfer:** Use a real rating or equivalent independently supported metric; preserve the small monochrome seal treatment rather than introducing a colorful stat dashboard.

**Build:** Use a horizontal SVG with a large numeral on the left of the central group, five small filled stars above a short label on the right, and mirrored leaf stems at the ends; render the entire seal in near-black at 70% opacity.

### Icons

**Observed:** A small analog-object emblem leads the navigation. Platform symbols are solid white inside dark pills; small chevrons are subdued gray. Conversion benefits use 32px circular, beveled gray check badges rather than bare checkmarks.

**Transfer:** Keep symbols product-relevant. Use rounded-stroke chevrons and white checks on shallow dimensional discs; avoid a large decorative line-icon library.

## Section recipes

How recurring sections are built.

### First screen: Object-led opening

**Observed:** On the cool Canvas, Floating navigation occupies a 115px-high pill inside a 25px outer inset, with emblem and identity left and Purchase pill right. The central opening group begins below the header: Announcement capsule above a single-line, centered display headline spanning about four fifths of the viewport. A dark tonal text gradient adds slight depth. A 100px pause follows the heading group, then the 1340px-wide environmental product film begins in a 30px-rounded frame. Within the first 900px, the navigation, announcement, complete headline and upper 426px of the main scene are visible; the rest of the scene and first testimonials lie below. There is no separate support paragraph or duplicate purchase button in this opening.

**Transfer:** Use one benefit-led sentence and a large real product scene. Without film, use a strong still or rendering with the same lighting and occupied area. Mobile-app product pages use an aqua canvas, a balanced two-line display, a 32px support line and Rating seal above the media stage; they may add a QR code to navigation.

**Avoid:** Do not substitute a left-copy/right-thumbnail split or crowd the opening with a feature list and several competing actions.

**Text style:** `display` — ui-sans-serif 600 · 96px/1 · tracking -0.0125em

### Centered statement pair

**Observed:** A heading at 60px/64px sits over a narrower 32px/1.3 lead with 20px separation. Both are centered directly on the canvas, not in a card.

**Transfer:** Use this for the product's central promise or a transition into a capability chapter.

**Text style:** `heading` — ui-sans-serif 600 · 60px/64px · tracking -0.0167em

### Asymmetric product chapter

**Observed:** A full-width Mint product stage gives way to an asymmetric six-column composition: a tall four-column Teal material panel with a floating interface next to a two-column stack of smaller porcelain or colored cards. Gutters are 50px. Titles use card-heading; descriptions use body. Later, a full-width Porcelain panel shows two large hardware variants side by side.

**Transfer:** Build around one major capability and a few smaller details; vary the media shape while keeping panel corners and text placement consistent.

**Text style:** `card-heading` — ui-sans-serif 600 · 40px/1.1 · tracking -0.005em

### Collected human proof

**Observed:** A centered statement introduces rows of Review cards. White cards vary in height, use mint-backed emphasized phrases and fade into the canvas at row edges. A preceding editorial proof variant pairs two 645px-wide videos with quotations and centered attributions.

**Transfer:** Make the proof feel plentiful but readable. Use a static overflow collection when movement is unnecessary; keep edge fading and text emphasis.

**Text style:** `review` — ui-sans-serif 400 · 20px/1.4 · tracking -0.01em

### Reassurance and conversion

**Observed:** A closing-heading leads a centered stack of three benefit statements with dimensional check badges. The heading-to-benefits gap is 30px and row gaps are 15px. A Featured quote sits below, then the larger Purchase pill and 20px practical notes at reduced opacity. Major groups have 60px separation.

**Transfer:** State the actual purchase or adoption terms, add one human endorsement and one conversion control, then answer compatibility or setup concerns in a short centered note.

**Text style:** `closing-heading` — ui-sans-serif 600 · 60px/1.2 · tracking -0.0167em

### Open question stack

**Observed:** A closing-heading introduces an 800px-wide stack of Question rows. The rows remain nearly invisible against the canvas. A short centered support invitation ends the stack.

**Transfer:** Use for detailed buying objections on longer pages, without making the FAQ the visual climax.

**Text style:** `question` — ui-sans-serif 600 · 20px/1.2

### Monumental soft sign-off

**Observed:** The Relief footer follows a broad 150px chapter pause. Its name fills almost the whole width; a small maker credit and right-aligned legal links sit immediately beneath. The mobile-app product variant reaches the same ending after its final purchase and compatibility notes, without a FAQ.

**Transfer:** Finish with the new product name as shallow relief and minimal human-scale utilities. Keep the artwork device even when the preceding narrative differs.

**Text style:** `relief-name` — ui-sans-serif 500 · 215px/1.2 · tracking -0.015em

## Page flow

**Storyline:** Emotional promise → product as an object → detail or human proof → reassurance and purchase → soft monumental sign-off.

### Long-form crafted-product marketing

1. **Promise** — Single wide headline and availability capsule above an environmental product scene.
2. **Early social proof** — Three short quotations with portraits and affiliations.
3. **Product explanation** — Centered positioning statement followed by a mint detail stage and asymmetric feature panels.
4. **Social proof** — Editorial videos and a broad collection of highlighted personal reviews.
5. **Conversion** — Three reassuring benefits, a featured endorsement and a large purchase pill.
6. **Objection handling** — Unfilled question rows and a personal support invitation.
7. **Sign-off** — Pale oversized name with maker and legal utilities.

**Transfer:** Use the long form when the product has tactile details worth exploring; select chapter order around the decision rather than preserving a fixed section count.

### Focused mobile-app product launch

1. **Promise** — Two-line display with a rhythmic support statement and a monochrome rating seal on aqua.
2. **Product demonstration** — Wide media stage.
3. **Social proof** — Two-line proof heading and horizontally overflowing review cards with stars, dates and review titles.
4. **Product demonstration** — Large phone-and-tablet hardware pairing.
5. **Conversion** — Centered reassurance statements, a white featured endorsement, purchase pill and compact compatibility notes.
6. **Sign-off** — Aqua relief name and the same minimal utility line.

**Transfer:** For a smaller companion product, shorten the capability narrative and let credible proof and a clear platform action do more of the work.

## Writing

Warm, highly assured and unusually attentive to small pleasures. The language makes a practical utility feel like a thoughtfully finished object, then switches to plain, direct purchase terms.

**Do not copy:** Do not reuse the brand or maker names, clock artwork, original endorsements, reviewer identities, rating, audience counts, price, compatibility promises or lifetime-update claims. Replace all claims and quotations with facts belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your, especially around benefits and everyday situations. The product can be described in the third person; the maker's presence is personal rather than corporate.
- **Rhythm:** Short, balanced headlines with sentence case and full stops; longer positioning sentences appear only in support. Fragments and repetition create cadence, especially in reassurance copy.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Transform an ordinary moment with a compact verbal contrast. | 4–10 words | “Turn waiting into watching.”<br>“Most apps you open. This one you display.” |
| Feature heading | A playful, compressed promise that points to a specific detail. | 4–8 words | “Two ways to be right.”<br>“Settings get the full treatment, too.” |
| Supporting line | One concrete explanation carrying the care behind the feature. | 8–20 words | “Every control designed like someone actually cares about people who notice quality.” |
| Reassurance | Short declarative fragments, repeated syntax and explicit terms. | 3–14 words per statement | “Buy once. Own forever. Every future update included.”<br>“No subscription. No ads. No tracking. No account required.” |
| Action | Direct verb plus product destination or price. | 2–5 words | “Buy now — $19”<br>“Get the app” |

**Words and phrasing to use:** care; crafted; feel; beautiful; details; balanced; delight; simple

**Avoid:** revolutionary; disruptive; unlock your potential; enterprise-grade; synergy; all-in-one platform

**Rules:**

- Tie a feeling to a tangible product detail rather than stacking abstract adjectives.
- Let headings carry a small turn of phrase; keep practical explanations plain.
- Use parallel short statements for adoption reassurance, only when each is factually supported.
- Give testimonials the emotional language and keep action labels literal.

## Do's and Don'ts

### Do

- Keep the default long canvas cool gray, with white panels and bounded mint moments.
- Use 96px/1 weight-600 opening type with -0.0125em tracking.
- Keep feature titles at 40px/1.1 and their short descriptions at 20px/1.25.
- Preserve 50px desktop side space and 50px feature gutters.
- Make primary purchase controls dimensional with 100px rounding and inset light.
- Highlight selected review phrases with #d5efef and weight 600.
- Use a near-container-wide 215px relief name as a signature ending.
- Let large product details dominate their cards rather than adding extra copy.

### Don't

- Do not turn the whole default page black because some product demonstrations contain dark screens.
- Do not use saturated teal for every heading and action; the main text remains near-black.
- Do not replace polished pill actions with flat rectangular buttons.
- Do not make every feature the same-height three-column tile; preserve wide/tall contrasts.
- Do not underline all utility links by default; the declared hover only darkens them.
- Do not use 12px dashboard-style body copy for the marketing narrative; its default is 20px.
- Do not make the giant closing name a high-contrast black banner.
- Do not add dense footer navigation columns in place of the single maker-and-legal line.

## Motion and responsive

### Motion

**Observed:**

- The navigation remains fixed while content scrolls beneath its glass backing.
- Review rows extend horizontally and use transparent-to-opaque edge masks.
- Utility link hover darkens the text to #04080d without an underline. No action transitions or keyframe animations are specified.

**Transfer:**

- Keep the floating header legible over the colored product chapters.
- Preserve the edge-faded review-collection treatment without requiring a particular autoplay speed.

**Unknown:**

- Review movement timing and easing, header backing interpolation and media playback behavior are unspecified.

### Responsive

**Observed:**

- Width breakpoints occur around 800px–810px, 1200px and 1440px.

**Transfer:**

- On narrower screens, retain the order within the opening and keep one strong product scene below the headline.
- Collapse the asymmetric feature grid into a readable single stack while preserving the wide-card versus small-detail hierarchy.
- Fit the relief name to the viewport width instead of allowing it to break into ordinary paragraph lines.

**Unknown:**

- Exact mobile type sizes, header rearrangement and narrow-screen card widths are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
