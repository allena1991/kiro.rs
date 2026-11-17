# mymind — prismatic thought bubbles

## Overview

An expansive, light editorial style that makes software feel personal rather than industrial. Delicate, tightly fitted serif headlines sit inside warm prismatic halos, while straightforward sans-serif copy explains the useful details. White and cool gray dominate, with blush, sage, powder blue and occasional vivid orange chapters surrounding tactile interface collages. It suits thoughtful creative tools and consumer products with a visually rich story and an unhurried reading pace.

### Essentials

- A promise reads like a two-line literary poster: regular Louize at 140px/0.85 with -0.06em tracking, centered over a huge white oval surrounded by peach, pink and yellow light.
- Small colorful nouns interrupt otherwise plain sentences: 18px Nunito semibold inside 35px-high, 1px outlined capsules with 4px 18px padding and a nearly transparent wash.
- Actions are soft capsules, not rectangular controls: orange conversion buttons are 45px high with 120px radii; pale platform buttons are 50px high with 100px radii.
- Color changes the atmosphere rather than coloring every heading: white and near-white carry most of the long page; pastel feature panels, a vivid #ff5924 chapter and pink testimonial light supply concentrated breaks.
- Product proof is a curated collection, not a flat dashboard: floating image and text clippings overlap within large pastel cards, with 50px padding and 16px corners. Rebuild the collage with relevant sample outputs when no finished interface exists.
- The closing statement is a reading experience: centered 54px/60px serif paragraphs on blush, beneath a fine arch and a tiny emblem, followed by platform choices and a white inset footer with a conspicuous gray walkthrough tile.
- Navigation becomes a floating lozenge: a compact brand at left, three short links with colored pin-dots in the middle, and login plus an orange signup capsule at right; 18px link type and 42px inter-link gaps keep it airy.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Persimmon | `#ff5924` | `--color-orange` | action, accent, background, link | Conversion buttons, selected links, eyebrow accents and one immersive demonstration chapter. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lemon outline | `#ffcf27` | `--color-tag-yellow` | border, text | Yellow inline noun capsule. |
| Apricot outline | `#e98f53` | `--color-tag-orange` | border, text | Warm inline noun capsule. |
| Coral outline | `#ea726b` | `--color-tag-red` | border, text | Coral inline noun capsule. |
| Sky outline | `#99d2fb` | `--color-tag-blue` | border, text | Blue inline noun capsule. |
| Orchid outline | `#e48abf` | `--color-tag-pink` | border, text | Pink inline noun capsule. |
| Pale apricot | `#ffece5` | `--color-peach-panel` | surface | Summary feature card. |
| Muted jade | `#ccddd8` | `--color-sage` | surface | Large audience demonstration panel. |
| Pistachio | `#dde9d3` | `--color-green-panel` | surface | Reading feature card. |
| Powder blue | `#e5eaf2` | `--color-blue-panel` | surface | Feature collage cards. |
| Dusty rose | `#f4ecef` | `--color-pink-panel` | surface | Collection feature card. |
| Oat | `#f3f0e7` | `--color-cream-panel` | surface | Feature cards with notes and text examples. |
| Blush canvas | `#fff1f1` | `--color-blush` | background | Closing editorial chapter and warm footer surroundings. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue gray | `#748297` | `--color-muted` | text, link | Platform actions and secondary captions. |
| Editorial slate | `#3a475a` | `--color-editorial` | text | Long serif editorial passages and the large negation list. |
| Violet graphite | `#343552` | `--color-footer-ink` | text | Footer category labels and prominent destination links. |
| Slate copy | `#4a5465` | `--color-body` | text | Main sans-serif support copy. Navigation uses this hue at 80% opacity over light backgrounds. |
| Headline black | `#000000` | `--color-ink` | text | Primary serif headlines and feature titles. |
| Graphite gradient end | `#2f343c` | `--color-ink-end` | text | Lower end of the subtle black-to-graphite display text gradient. |
| Footer gray | `#717286` | `--color-footer-text` | link, text | Grouped footer links. |
| Cool divider | `#d5dae0` | `--color-rule` | border | Thin horizontal footer separator. |
| Warm divider | `#e6dbdb` | `--color-platform-rule` | border | Vertical rules between platform choices. |
| Walkthrough gray | `#f0f2f5` | `--color-soft-gray` | surface, background | Footer walkthrough tile and explanatory-page base. |
| Near-white panel edge | `#f2f4f6` | `--color-panel-edge` | border | Visible 50% #e4e8ec edge over the near-white demonstration panel. |
| Platform mist | `#f5f7f9` | `--color-button-gray` | surface | Pale platform button fill. |
| Cool canvas | `#f9fafc` | `--color-canvas` | background | Base canvas behind the white and tinted chapters. |
| Demonstration white | `#fcfcfe` | `--color-demo-white` | surface | Tabbed capability stage. |
| White | `#ffffff` | `--color-white` | background, surface, text | Hero oval, editorial sections, enclosing panels and text on stronger color. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| detailed use-case explainers | Audience green | `#e9f6ed` | `--color-audience-green` | surface | Pale green use-case panel. |
| detailed use-case explainers | Audience pink | `#fdf0f5` | `--color-audience-pink` | surface | Pale pink use-case panel. |
| detailed use-case explainers | Audience blue | `#f1f5fd` | `--color-audience-blue` | surface | Pale blue use-case panel. |
| detailed use-case explainers | Audience charcoal | `#232a35` | `--color-audience-dark` | surface, text | Dark audience panels and dark serif copy on pale audience panels. |
| detailed use-case explainers | Explainer mist | `#f3f4f7` | `--color-explainer-gray` | background | Explanatory page bands around the inset white collection. |
| detailed use-case explainers | Audience gray | `#f4f5f7` | `--color-audience-gray` | surface | Neutral use-case panel. |

## Typography

- **Louize-Regular-205TF** — Display headlines, editorial passages, platform names and the footer walkthrough title. Fine, calligraphic old-style serif with a large expressive contrast between delicate details and dark strokes; true italic is used for selected phrases. If unavailable, use **Cormorant Garamond**. 400 and 500; tune wrapping carefully to retain the broad, tightly fitted headline silhouette. Font stack: "Louize-Regular-205TF", "Cormorant Garamond", Georgia, serif.
- **Inter** — Main body copy, navigation and feature-card titles. Plain contemporary grotesk; regular support text contrasts with medium-weight feature titles. Font stack: "Inter", Arial, sans-serif.
- **Nunito** — Capsules, actions, eyebrows, footer labels and explanatory card copy. Friendly rounded sans with regular and semibold cuts; small uppercase labels remain soft rather than technical. Font stack: "Nunito", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Louize-Regular-205TF | 400 | 140px | 0.85 | -0.06em | size clamp(58px, 10vw, 140px) | Two-line opening promise. |
| chapter | Louize-Regular-205TF | 400 | 96px | 0.875 | -0.0437em | fixed | Centered major chapter headlines, including light text on colored backdrops. |
| audience-display | Louize-Regular-205TF | 400 | 80px | 0.875 | -0.0225em | fixed | Title inside the large audience demonstration. |
| audience-italic | Louize-Regular-205TF | 400 italic | 80px | 0.875 | -0.0225em | fixed | Second phrase of the audience demonstration title. |
| closing-statement | Louize-Regular-205TF | 400 | 54px | 1.111 | -0.039em | fixed | Centered closing prose separated into spacious paragraphs. |
| negation-list | Louize-Regular-205TF | 400 | 52px | 1.3 | -0.025em | fixed | Large vertically stacked list paired with crossed-out symbols. |
| walkthrough-title | Louize-Regular-205TF | 500 | 48px | 0.916 | -0.0334em | fixed | Prominent footer walkthrough link. |
| editorial | Louize-Regular-205TF | 400 | 42px | 1.191 | -0.019em | fixed | Long-form left-aligned statement paragraphs. |
| feature-title | Inter | 500 | 40px | 1.35 | -0.035em | fixed | Left-aligned feature-card headings. |
| platform-name | Louize-Regular-205TF | 400 | 32px | 0.938 | -0.0624em | fixed | Platform names in the repeated installation strip; use this default consistently. |
| body | Inter | 400 | 20px | 1.4 | normal | fixed | Short support paragraphs beneath chapter titles and inside feature cards. |
| opening-support | Inter | 400 | 20px | 2.2 | -0.02em | fixed | Centered sentence that accommodates inline noun capsules. |
| footer-link | Nunito | 400 | 20px | 1.65 | -0.03em | fixed | Grouped footer destination links. |
| noun-capsule | Nunito | 600 | 18px | 1.4 | -0.01em | fixed | Colored inline nouns in the opening support sentence. |
| navigation | Inter | 400 | 18px | 1.11 | normal | fixed | Short primary navigation links. |
| platform-action | Nunito | 600 | 18px | 1.667 | -0.022em | fixed | Pale opening platform buttons. |
| eyebrow | Nunito | 600 | 16px | 1.75 | 0.125em, uppercase | fixed | Widely spaced chapter labels. |
| header-action | Nunito | 600 | 16px | 1.25 | normal | fixed | Login and signup labels. |
| conversion | Nunito | 600 | 15px | 1.667 | 0.053em, uppercase | fixed | Main orange conversion capsules. |
| footer-label | Nunito | 600 | 15px | 1.334 | 0.04em, uppercase | fixed | Footer group labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| detailed use-case explainers | explainer-display | Louize-Regular-205TF | 400 | 80px | 1.1 | -0.0351em | fixed | Large centered audience introduction and concluding statement. |
| detailed use-case explainers | explainer-prose | Louize-Regular-205TF | 400 | 48px | 1.083 | -0.0165em | fixed | Centered conversational explanations. |
| detailed use-case explainers | use-case-title | Louize-Regular-205TF | 400 | 48px | 1 | -0.0165em | fixed | Compact two-line title in a split audience card. |
| detailed use-case explainers | use-case-body | Nunito | 400 | 18px | 1.556 | -0.011em | fixed | Descriptive paragraph inside audience cards. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the largest serif promises regular rather than bold; density comes from negative tracking and compressed line height, not heavier cuts.
- Inter medium is used for feature headings while Nunito semibold carries small actions. These are different jobs, not interchangeable sans-serif styles.
- Use italic as a phrase-level change within an otherwise regular serif title, rather than introducing a new decorative family.
- Only the opening display has a confirmed fluid size rule; preserve the remaining desktop hierarchy and adapt line breaks deliberately.

## Layout

**Density:** Airy: large reading pauses and full demonstration stages separate relatively short blocks of copy.

### Spacing

**Spacing system:**

- **step** 10px — Dominant spacing rhythm for panel padding and major chapter intervals; not an exclusive grid.

| Value | Use |
| --- | --- |
| 10px | Vertical action padding. |
| 20px | Inner column gutter and compact label spacing. |
| 30px | Inset white feature-shell padding. |
| 40px | Feature-row gutter, vertical walkthrough padding and platform-cell padding. |
| 50px | Feature-card padding and separation between detailed audience panels. |
| 70px | Desktop section side padding. |
| 80px | Audience demonstration top padding and gaps after longer text blocks. |
| 100px | Major chapter top padding and feature-shell top inset. |
| 140px | Major chapter bottom breathing room. |
| 200px | Closing statement top padding and larger editorial separations. |

### Containers and grids

- **page-frame**: max width 1440px · side padding 70px. Centered desktop page; ordinary chapter content spans about 1300px.
- **feature-shell**: max width 1370px · side padding 30px. Inset white shell surrounding the pastel feature mosaic.
- **feature-pair**: 2 columns · gap 40px. Alternate roughly 5:7 and 7:5 width cards; occasional full-width cards interrupt the pair rhythm.
- **opening-support**: max width 500px. Centered two-line sentence with inline capsules.
- **editorial-column**: max width 742px. Narrow, left-aligned serif essay centered in the page.
- **footer-groups**: 4 columns. A wide primary-destination column beside three narrower grouped link columns.
- **use-case-panels** (only for detailed use-case explainers): max width 1228px · 2 columns · gap 50px. Stack wide split panels with copy in the left half and large product imagery in the right; the gap is vertical between panels.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | conversion capsules | 120px |
|  | platform capsules | 100px |
|  | inline nouns | 36px |
|  | header signup | 30px |
|  | feature cards | 16px |
|  | feature shell | 12px |
|  | footer tile | 20px |
| detailed use-case explainers | audience panels | 18px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | warm feature shell | `0px 57px 60px -54px rgba(255, 167, 129, 0.44), 0px -27px 50px -40px rgba(255, 128, 36, 0.27)` | Warm reflected light at the edge of the enclosing white feature shell. |
|  | capability panel | `0px 4px 7px -4px rgba(140, 142, 151, 0.32)` | Very faint lift for the near-white tabbed demonstration. |
| detailed use-case explainers | use-case image | `-16px 4px 48px 0px rgba(0, 0, 0, 0.12)` | Soft left-cast shadow under a product image emerging from the right edge. |

### Surfaces

#### Canvas · level 0

**Use:** Underlying page field.

**CSS:** `background: #f9fafc`

**Observed:** Most reading chapters layer pure white or a pale band over this field.

**Transfer:** Let the canvas recede behind distinct editorial and demonstration stages.

#### Pastel feature card · level 1

**Use:** Default feature demonstration backing.

**CSS:** `background: #e5eaf2; border-radius: 16px; padding: 50px`

**Observed:** Flat, softly colored panels vary among blue, oat, pistachio, dusty rose and apricot; no heavy outline.

**Transfer:** Use one muted tint per capability, with actual product content above a bottom-aligned title and paragraph.

#### Warm feature shell · level 1

**Use:** Enclosing surface for the feature mosaic.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 100px 30px 30px; box-shadow: 0px 57px 60px -54px rgba(255, 167, 129, 0.44), 0px -27px 50px -40px rgba(255, 128, 36, 0.27)`

**Observed:** White inset enclosure bridges orange surroundings into the pale lower page.

**Transfer:** Use the warm reflected edge rather than outlining every child card.

#### Orange chapter · level 0

**Use:** Immersive demonstration break.

**CSS:** `background: #ff5924; padding: 100px 70px 140px`

**Observed:** A black serif promise sits above pale support copy and a large interaction scene.

**Transfer:** Reserve the saturated fill for an emphatic product moment; keep neighboring chapters lighter.

#### Closing blush · level 0

**Use:** Long final statement.

**CSS:** `background: #fff1f1; padding: 200px 70px 128px`

**Observed:** Thin arch art introduces centered black serif paragraphs.

**Transfer:** Keep this stage visually sparse so the concluding prose feels intentional.

#### Capability stage · level 1

**Use:** Tabbed demonstrations beneath the feature mosaic.

**CSS:** `background: #fcfcfe; border: 1px solid rgba(228, 232, 236, 0.5); border-radius: 16px; padding: 50px; box-shadow: 0px 4px 7px -4px rgba(140, 142, 151, 0.32)`

**Observed:** A very faint edge contains a row of text tabs and an open composition of caption plus product artwork.

**Transfer:** Use it for several views of one capability instead of another grid of cards.

#### White footer panel · level 1

**Use:** Final navigational destination.

**CSS:** `background: #ffffff; border-radius: 20px 20px 0px 0px; padding: 0px 70px`

**Observed:** Inset 70px from the page sides over warm prismatic light; the explainer variant sits on plain cool gray.

**Transfer:** Make the footer a large readable panel, not a dark utility bar.

#### Audience charcoal panel · level 1

**Only for:** detailed use-case explainers

**Use:** Dark variant of the wide split use-case panel.

**CSS:** `background: #232a35; border-radius: 18px; color: #ffffff`

**Observed:** Alternates with pale pink, blue, green and gray panels; product imagery changes to match the light or dark backing.

**Transfer:** Use dark panels for select audiences only, not as the default page theme.

## Components

### Navigation links

**Use:** Primary routes in the top navigation.

**CSS:** `display: flex; gap: 42px; color: rgba(74, 84, 101, 0.8)`

**Text style:** `navigation` — Inter 400 · 18px/1.11

**Observed:** Three short route names occupy the center; each is preceded by a tiny colored dot. The brand sits separately at left and account actions at right. At scroll depth the header contracts into a translucent white rounded lozenge.

**States:** Declared: hover color #000000.

**Transfer:** Keep route names brief and preserve the centered group rather than stretching all links across the bar.

### Header signup

**Use:** Persistent conversion action.

**CSS:** `background: #ff5924; color: #ffffff; border-radius: 30px; padding: 11px 20px; height: 42px; box-sizing: border-box`

**Text style:** `header-action` — Nunito 600 · 16px/1.25

**Observed:** Small filled capsule sits beside an unfilled login link.

**States:** Declared: hover label color #000000.

### Primary button

**Use:** Conversion at the end of a reading or demonstration block.

**CSS:** `background: #ff5924; color: #ffffff; border-radius: 120px; padding: 10px 22px; height: 45px; display: inline-flex; align-items: center; box-sizing: border-box`

**Text style:** `conversion` — Nunito 600 · 15px/1.667 · tracking 0.053em · uppercase

**Observed:** Short uppercase label, sometimes with a small right chevron. The longer closing label uses 32px horizontal padding.

**States:** Declared: hover on ancestor keeps the label #ffffff.

**Transfer:** Use a short invitation, not a long sentence.

### Platform button

**Use:** Immediate access to installation options below the opening promise.

**CSS:** `background: #f5f7f9; color: #748297; border-radius: 100px; padding: 10px 24px; height: 50px; display: inline-flex; align-items: center; box-sizing: border-box`

**Text style:** `platform-action` — Nunito 600 · 18px/1.667 · tracking -0.022em

**Observed:** A recognizable full-color platform icon precedes each title; three compact actions sit in a centered row.

**States:** Declared: hover color #000000; hover on ancestor color #ff5924.

**Transfer:** Use the actual distribution channels; preserve the icon-plus-label balance.

### Inline noun capsule

**Use:** Add gentle category color inside the opening support sentence.

**CSS:** `color: #e98f53; border: 1px solid #e98f53; border-radius: 36px; padding: 4px 18px; background-image: linear-gradient(rgba(233, 143, 83, 0.06) 0%, rgba(233, 143, 83, 0) 100%); display: inline-block`

**Text style:** `noun-capsule` — Nunito 600 · 18px/1.4 · tracking -0.01em

**Observed:** Colored outlines and matching text vary through apricot, orchid, sky, coral and lemon. Capsules remain integrated into two lines of prose, not a separate filter bar.

**Transfer:** Choose concrete nouns that explain the product's range.

### Feature card

**Use:** Show one capability through a substantial product scene.

**CSS:** `background: #e5eaf2; border-radius: 16px; padding: 50px`

**Text style:** `feature-title` — Inter 500 · 40px/1.35 · tracking -0.035em

**Observed:** Art fills the upper majority; title and a short paragraph align at the bottom. Cards alternate narrow and wide widths; one photographic device scene spans the full row.

**Transfer:** Use a distinct output or interaction in every card, keeping the same text baseline logic.

### Platform installation cell

**Use:** Repeated availability strip before or after major storytelling.

**CSS:** `border-right: 1px solid #e6dbdb; padding: 40px 24px; text-align: center; box-sizing: border-box; width: 240px`

**Text style:** `platform-name` — Louize-Regular-205TF 400 · 32px/0.938 · tracking -0.0624em

**Observed:** Five equal cells combine a roughly 48px platform mark, serif platform name and a small orange install link; final cell has no right rule.

**Transfer:** Adapt the number of choices to real availability without turning the strip into pricing cards.

### Walkthrough tile

**Use:** Oversized secondary action in the footer.

**CSS:** `background: #f0f2f5; border-radius: 20px; padding: 40px 0px; text-align: center`

**Text style:** `walkthrough-title` — Louize-Regular-205TF 500 · 48px/0.916 · tracking -0.0334em

**Observed:** A large serif text link sits over a smaller gray walkthrough descriptor. The tile takes the right side of the footer's top row opposite a small brand-and-tagline lockup.

**States:** Declared: hover title color #000000 and opacity 0.5.

**Transfer:** Link to a useful guided next step rather than repeating the primary conversion button.

### Footer link group

**Use:** Low-pressure navigation after the closing statement.

**CSS:** `color: #717286`

**Text style:** `footer-link` — Nunito 400 · 20px/1.65 · tracking -0.03em

**Observed:** Small uppercase group label above a relaxed vertical list. A wider left column uses larger Inter links; a thin bottom rule separates legal and origin notes.

**States:** Declared: hover color #000000 and opacity 0.5; transition 0.2s linear.

### Audience split card

**Only for:** detailed use-case explainers

**Use:** Explain a product through a particular user's needs.

**CSS:** `background: #232a35; border-radius: 18px; color: #ffffff; display: flex; overflow: hidden`

**Text style:** `use-case-title` — Louize-Regular-205TF 400 · 48px/1 · tracking -0.0165em

**Observed:** Small audience capsule at top left; left column contains serif title, short paragraph, small benefit-list label and four play-dot links. The right half is a large interface composition bleeding to the outer edge; light variants use dark copy.

**Transfer:** Organize by real customer situations, with a tailored example rather than the same repeated image.

## Imagery and graphics

### Prismatic oval halo

**Use:** Signature opening atmosphere, echoed around the footer.

**Observed:** A huge clean white oval occupies the center; its perimeter glows in peach, orange, pink and pale yellow, with a trace of lavender near the lower right. Light diffuses toward white at the page edges while the oval boundary remains relatively crisp. Headline and actions sit in front; the interface begins across the lower rim.

**Transfer:** Always retain this light-surrounded opening field even if the product has no artwork. Pair it with a minimal custom output collage.

**Build:** Use a full-width isolated backdrop with an approximately 1050px-wide by 1200px-high white ellipse centered behind the copy. Behind it, layer a larger conic-gradient ellipse in warm orange, coral, orchid, pale yellow and lavender, blur 60px, and fade the outer edge with a radial mask. Keep the white ellipse unblurred above the glow. For the footer remove the white ellipse and use broad overlapping peach, pink and lavender radial washes. Match the soft glow; exact stops are not essential.

### Curated product collage

**Use:** Opening product reveal and capability-card illustrations.

**Observed:** Interface fragments mingle with photos of furniture, books, posters, editorial imagery, short notes and quotes. Clippings use varied heights, subtle shadows and occasional floating colored labels. Objects are front-facing, cleanly cut out or softly backed; photography is editorial rather than stock-office lifestyle.

**Transfer:** Use relevant artifacts from the new product: three to seven varied sample outputs, real content fragments and one recognizable interaction. Minimum acceptable artwork is a carefully composed set of real output cards with overlapping depth, not generic blank rectangles.

**Build:** Compose a clipped relative-positioned scene: a pale interface plane at the back, two to four unequal image cards in front, and a small colored label or cursor detail. Use 12px to 16px corners, soft low-opacity shadows and gentle white or matching-panel fades at the edge where imagery meets text.

### Thought-bubble proof

**Use:** Human social proof on a luminous pink field.

**Observed:** White horizontal oval quote bubbles are staggered left and right under an enormous white serif headline. Two small white dots lead from each bubble to a circular avatar below; broad shadows make them hover above the pink-peach atmosphere.

**Transfer:** Use genuine short customer quotes. If proof is unavailable, preserve the bubble device as clearly labeled questions and answers rather than fabricating endorsements.

**Build:** Create white rounded capsules with generous horizontal inset and two offset circular pseudo-elements leading toward a 60px circular avatar. Back the group with overlapping pink and peach radial gradients fading into blush. Offset the bubbles horizontally instead of using equal cards in a grid.

### Fine arch and emblem

**Use:** Signature introduction to the closing reading passage.

**Observed:** A very wide, thin arch descends toward both page edges on blush; a small monochrome emblem sits at its crown above the centered prose.

**Transfer:** Use a small original product symbol or a simple geometric monogram. The arch, tiny mark and large serif conclusion remain the closing device regardless of subject.

**Build:** Draw a single SVG elliptical arc across a 1440px-wide viewBox with a 1px dark-slate stroke fading to transparent at both ends. Center a small monochrome symbol at the highest point; leave about 200px of upper air before the main prose.

### Conversational speech sculpture

**Only for:** detailed use-case explainers

**Use:** Opening question and later conversational checkpoints.

**Observed:** A large white speech lozenge with a tiny lower-left tail floats over a blurred pink, orange and purple ring. Its serif question is dark and substantial; inset shading gives the bubble a gently inflated, almost ceramic edge.

**Transfer:** Open explanatory pages with one reader question rather than the default giant promise. Reuse the bubble to punctuate the explanation.

**Build:** Use a white 700px-wide rounded lozenge with a small curved SVG tail at lower left; add faint inset gray shading along the bottom and a diffuse outer shadow. Place a blurred elliptical conic ring behind it, with purple at left, lavender at top and warm peach at right on a pink field. Set the question in the serif at about 80px, maintaining a single line when practical.

### Icons

**Observed:** Platform marks are recognizable full-color icons around 48px in the installation strip and 24px beside opening actions. Small arrows and play circles accompany text actions. Navigation uses tiny colored circular markers rather than line icons.

**Transfer:** Prefer actual platform marks where relevant; elsewhere use simple arrows or circles. Do not introduce an extensive decorative line-icon set.

## Section recipes

How recurring sections are built.

### First screen: Halo promise opening

**Observed:** Within the first 900px, a narrow navigation row sits above a centered two-line 140px serif promise occupying most of the page width. Behind it are diffuse prismatic light, a sharply white giant oval, then the dark headline with a subtle graphite finish. Directly below is a 500px-wide two-line support sentence with colored Inline noun capsules. A centered row of three Platform buttons follows a substantial pause. The top of a roughly 1100px-wide product interface enters the bottom of the first screen at about 735px; most of that demonstration continues below the fold. The main conversion capsule remains at the top right rather than becoming a huge central hero button.

**Transfer:** Use a short paired promise with similar line lengths and keep the halo as the dominant atmosphere. Without a finished interface, create a substantial curated collage of believable product outputs entering the lower rim. Explanatory pages instead open with the Conversational speech sculpture and a centered serif explanation.

**Avoid:** Do not replace the oval field with a standard left-copy/right-dashboard hero or push all product proof beyond the first viewport.

**Text style:** `display` — Louize-Regular-205TF 400 · 140px/0.85 · tracking -0.06em

### Editorial declaration

**Observed:** White field, centered uppercase eyebrow, then a narrow 742px serif column at 42px/50px. The first word becomes a larger italic lead-in; paragraphs breathe before a centered list of large negations with crossed-out symbols and an orange action.

**Transfer:** Use this as a thoughtful explanation of what the product changes or removes; preserve the editorial column and symbolic list without requiring a manifesto topic.

**Text style:** `editorial` — Louize-Regular-205TF 400 · 42px/1.191 · tracking -0.019em

### Capability chapter

**Observed:** Centered eyebrow and 96px serif headline with 84px line height; a narrow 20px support paragraph follows by about 26px to 33px, then a large demonstration scene. Backgrounds distinguish white, warm off-white and the Orange chapter.

**Transfer:** Give each main promise one focused demonstration rather than packing several small claims beside a thumbnail.

**Text style:** `chapter` — Louize-Regular-205TF 400 · 96px/0.875 · tracking -0.0437em

### Pastel feature mosaic

**Observed:** Warm feature shell contains alternating unequal Feature card pairs with 40px gutters, 50px inner padding and 16px corners. Images occupy the upper majority and the heading/body pair sits low. A full-width photographic device panel breaks the pairs; the Capability stage adds text tabs and a large image-and-caption view.

**Transfer:** Vary width to suit the demonstration; retain a consistent bottom text anchor and the muted-card family.

**Text style:** `feature-title` — Inter 500 · 40px/1.35 · tracking -0.035em

### Luminous conversational proof

**Observed:** Thought-bubble proof floats over a pink-peach light field below a white chapter headline. Quotes are staggered and avatars hang outside their bubbles. A restrained uppercase link sits below the scene.

**Transfer:** Make proof feel like individual human thoughts rather than a wall of corporate logos.

**Text style:** `chapter` — Louize-Regular-205TF 400 · 96px/0.875 · tracking -0.0437em

### Audience demonstration

**Observed:** Large black serif heading over a horizontal audience selector; active label is orange. A broad sage panel below contains a tiny uppercase label and a two-line 80px serif title whose second phrase is italic. A dense but orderly collage rises from the bottom through a soft matching-color fade.

**Transfer:** Use audience choices to change the demonstration, not only the selected tab color.

**Text style:** `audience-display` — Louize-Regular-205TF 400 · 80px/0.875 · tracking -0.0225em

### Closing reading and availability

**Observed:** Closing blush supports the Fine arch and emblem, centered 54px serif prose with several separated paragraphs, then a compact orange conversion action. The Platform installation cell strip returns before the footer. The detailed explainer uses larger 80px/88px closing prose on cool gray instead of blush.

**Transfer:** End with a short human statement of the product's approach, then offer a practical route to use it. Keep the arch-and-emblem treatment on a general landing page.

**Text style:** `closing-statement` — Louize-Regular-205TF 400 · 54px/1.111 · tracking -0.039em

### Inset navigational ending

**Observed:** White footer panel has a brand-and-tagline lockup at upper left, Walkthrough tile at upper right, then one wide list and three Footer link groups. A 1px rule precedes a small origin/legal row. Prismatic light surrounds the panel in the default ending; detailed explainers use plain cool gray.

**Transfer:** Make the final region useful and hospitable; retain the prominent guided-next-step tile without turning the footer into another conversion billboard.

**Text style:** `walkthrough-title` — Louize-Regular-205TF 500 · 48px/0.916 · tracking -0.0334em

### Split use-case explanation

**Only for:** detailed use-case explainers

**Observed:** Wide 1228px by 743px Audience split cards stack with 50px vertical separation inside an inset white rounded enclosure. Left copy is indented about 110px; right product imagery is about 594px by 583px with a soft left-cast shadow and an edge bleed.

**Transfer:** Use this variant for a deep audience or use-case page with richer benefit lists, not for every ordinary feature tile.

**Text style:** `use-case-title` — Louize-Regular-205TF 400 · 48px/1 · tracking -0.0165em

## Page flow

**Storyline:** Personal promise → concrete product demonstration → a slower explanation of the approach → capability and audience proof → human reassurance → practical access and guided next step.

### Broad marketing landing page that makes a useful product feel emotionally inviting

1. **Promise** — Monumental centered serif promise, halo, inline category nouns and platform actions.
2. **Approach** — Editorial statement and symbolic list of burdens removed.
3. **Product demonstration** — Large individual capability chapters, including one saturated orange stage.
4. **Capability breadth** — Pastel unequal-card mosaic and a tabbed demonstration.
5. **Social proof** — Floating thought bubbles against pink light.
6. **Audience fit** — Audience selector and a large sage collage panel.
7. **Closing reassurance** — Fine arch, emblem and generously spaced serif prose with a compact conversion action.
8. **Practical access** — Platform strip followed by inset white footer and walkthrough tile.

**Transfer:** Adapt the number and sequence of chapters to the product while preserving the halo, curated product proof, bubble device and expressive closing reading passage.

### Detailed explanation organized around real ways people use the product

1. **Reader question** — Inflated white speech lozenge on prismatic pink light.
2. **Mechanism** — Centered conversational serif explanation and large product sequence.
3. **Objection handling** — A second question bubble with a short reassuring answer.
4. **Audience fit** — Large serif introduction followed by split light and dark audience panels with tailored product views and benefit links.
5. **Closing reassurance** — Small emblem above large centered serif prose on cool gray and a compact orange action.
6. **Practical access** — Platform choices and the same white navigational footer, without the warm footer light.

**Transfer:** Use this more structured variant when readers need to understand mechanics or compare their own workflow to concrete examples.

## Writing

Warm, personal and quietly opinionated about removing work. The product is explained through familiar actions and emotional relief, with occasional playful references to magic rather than an engineering lecture.

**Do not copy:** Do not reuse the mymind name, logos, proprietary symbols, customer quotes, availability, privacy promises or unique product claims. Example phrases demonstrate tone and structure; write original, truthful claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your'; use 'we' for the maker's point of view. Refer to the product as a helpful personal place, not an enterprise platform.
- **Rhythm:** Short paired headline sentences alternate with longer flowing serif reading passages. Support copy usually fits two to four short lines; actions are brief verbs. Conversational questions and contractions soften the confidence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Two parallel sentences; one expands possibility and the other removes a burden. | 4–8 words | “Remember everything. Organize nothing.” |
| Capability headline | State an effortless action, then explain the helpful mechanism in plain language. | 8–14 words | “Just save it. Artificial Intelligence takes care of the rest.” |
| Supporting copy | Concrete user action followed by the work the product takes off their hands. | 20–35 words | “Save anything with a click and stay in the flow. [Brand] understands what it is and remembers the important details, so you don't have to.” |
| Primary action | Short invitation rather than an aggressive sales command. | 3–4 words | “TRY IT OUT”<br>“SIGN UP FOR FREE” |
| Reassurance | Answer the reader's implied question directly, then describe the simpler outcome. | 25–45 words | “Yes! No need to waste time categorizing or organizing anything, your new mind magically does it all for you.” |
| Guided next step | Describe what the visitor will understand or see. | 4–5 words | “See how it works” |

**Words and phrasing to use:** your; one place; save; find; remember; care about; simple; beautiful; in the flow; no need to

**Avoid:** enterprise-grade; leverage; synergy; 10x your productivity; disruptive ecosystem; AI-powered everything

**Rules:**

- Lead with what becomes easier for the reader, not a technology category.
- Make feature names concrete and short; let the following paragraph explain how they help.
- Use a decisive contrast occasionally, then return to a gentle explanatory voice.
- Long closing prose should convey a human point of view rather than adding a new feature inventory.

## Do's and Don'ts

### Do

- Keep the opening promise at regular weight with 0.85 line height and -0.06em tracking.
- Use a 500px support measure for the inline colored noun sentence.
- Keep orange conversion capsules compact at 45px high, distinct from the 50px pale platform actions.
- Alternate pastel feature widths around a 5:7 proportion with 40px gutters.
- Give feature cards 50px internal padding and bottom-aligned title/copy groups.
- Repeat the availability strip with equal 240px cells and thin warm vertical rules when distribution choices matter.
- Preserve a prominent 48px serif walkthrough title inside the footer's gray tile.
- Use the true serif italic for a selected phrase rather than synthetic slant.

### Don't

- Do not turn the 140px serif opening into a bold grotesk headline.
- Do not make every chapter orange; the saturated field is a concentrated interruption in a predominantly light page.
- Do not fill noun capsules with opaque saturated colors; their default treatment is a 1px outline and a 6% fading wash.
- Do not assign 30px or 40px corners to ordinary feature cards; their radius is 16px.
- Do not use heavy uniform drop shadows beneath every pastel card; depth belongs mainly to the artwork and enclosing surfaces.
- Do not turn the footer into a dense black bar or remove the large guided-next-step tile.
- Do not replace unequal feature panels with a uniform three-column icon grid.
- Do not apply the dark use-case panel treatment to the whole marketing page.

## Motion and responsive

### Motion

**Observed:**

- Text links declare 0.2s linear transitions; grouped footer links change to black at 0.5 opacity on hover.
- Header signup declares 0.25s ease-in-out; enclosing action surfaces declare box-shadow 0.5s.
- The header is fixed, with the full-width opening navigation becoming a narrower floating lozenge during the long reading sequence.

**Transfer:**

- Use the compact floating navigation to keep chapter reading unobstructed.
- Keep hover behavior text-led and restrained; do not animate every pastel panel as if it were a button.

**Unknown:**

- The exact timelines of product demonstrations, scroll transitions and halo animation are not established.

### Responsive

**Observed:**

- Styles define width breakpoints around 544px, 768px, 992px, 1170px and 1440px.
- The opening display uses a clamped 10vw rule with a 140px upper limit; desktop-only opening elements have a below-543px visibility variant.

**Transfer:**

- On narrow screens preserve the central halo and stacked promise; reflow the noun sentence and platform choices without shrinking their text into badges.
- Stack unequal feature pairs and split audience cards while preserving the image-first, text-below relationship and muted backing.

**Unknown:**

- Exact mobile compositions, replacement assets and narrow-screen padding are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
