# Fluz — glossy everyday abundance

## Overview

An exuberant, approachable style that makes practical products feel like an invitation to a richer everyday world. Tall condensed grotesk headlines sit alongside small, readable geometric sans paragraphs, with warm near-black and pale gray giving way to candy-colored gradients and glossy illustrated objects. Product interfaces, hands, portraits and surreal landscapes share rounded stages; the overall density is spacious, with concentrated bursts of visual abundance.

### Essentials

- Headlines behave like compact posters: condensed semibold grotesk, 205.2px/162px in the opening, 96px/0.91 for section leads and 64px/0.91 for split features, with negative tracking rather than wide luxury spacing.
- The default opening is a centered three-line proclamation on a green-to-periwinkle field: a 486px-high headline stack, 650px-wide support line and 56px pale pill action all fit within the first 900px beneath a 73px dark navigation bar.
- Actions are soft capsules, not rectangles: main buttons use 16px 32px padding, 200px radius and condensed 20px/24px text; the compact navigation action uses a horizontal blue–lavender–green gradient.
- Color arrives as a world, not a scatter of accents: pale #ededec and warm #221919 carry the long narrative, while the opening, media stages and scenic closing supply saturated green, lilac, turquoise and gold. A full-width #98bbf4 footer is the final color block.
- Products live in glossy miniature worlds: oversized phone or browser fragments occupy roughly half a split section, clipped into rounded stages, with shiny floating objects, soft clouds and layered hills. When no product imagery exists, use a simple readable interface panel and a small family of original faceted objects over the same scenic backing.
- The ending becomes brand artwork: a 40px-top-rounded blue footer combines dense condensed navigation with an almost edge-to-edge wordmark, 1360px × 680px at desktop. Every new page needs this monumental typographic sign-off, adapted to its own name.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sign-off blue | `#98bbf4` | `--color-footer-blue` | background | Large rounded footer. |
| Oxblood ink | `#1a0000` | `--color-ink` | text, background | Primary dark headings and deep product-story bands. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Fresh green | `#21ba4c` | `--color-green` | background, accent, action | Top opening gradient and final compact action stop. |
| Action blue | `#82beff` | `--color-button-blue` | action | Leading compact navigation action stop. |
| Sky blue | `#7db4f4` | `--color-sky` | background, accent | Lower opening gradient stop. |
| Blue lavender | `#93b4f6` | `--color-periwinkle` | background, accent | Opening gradient transition. |
| Action mint | `#5bb89a` | `--color-button-mint` | action | Compact action gradient transition. |
| Lavender | `#a6b4f7` | `--color-lavender` | background, action | Opening and compact action gradient stop. |
| Seafoam | `#68b8ab` | `--color-seafoam` | background | Opening transition from green to blue. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Button ink | `#170100` | `--color-action-ink` | background, text, action | Dark pill actions and some product-page headings. |
| Pale action text | `#000000` | `--color-action-text` | text | Text on pale page-level actions. |
| Warm charcoal | `#221919` | `--color-charcoal` | background, surface, text | Fixed navigation and default dark capability chapters. |
| Table charcoal | `#262221` | `--color-table-top` | surface | Comparison panel gradient top. |
| Dark table edge | `#3a3a3a` | `--color-rule` | border | Comparison panel outer hairline. |
| Table brown | `#564743` | `--color-table-bottom` | surface | Comparison panel gradient bottom. |
| Warm secondary text | `#514f4c` | `--color-muted` | text | Support copy on pale backgrounds. |
| Soft inverse gray | `#aeaea6` | `--color-muted-inverse` | text | Secondary paragraphs on charcoal. |
| Stone shade | `#d1c9c1` | `--color-stone-shade` | surface | Lower stop of audience-card gradients. |
| Warm stone | `#e2dbd4` | `--color-stone` | surface, background | Feature stage fill and gradient base. |
| Navigation gray | `#e3e3e3` | `--color-nav-text` | text, surface | Navigation labels, search fill and dark business hero text. |
| Inverse off-white | `#eaeaea` | `--color-inverse` | text | Body copy and titles in product-story dark chapters. |
| Warm light gray | `#ededec` | `--color-canvas` | background, surface | Default marketing canvas and label interiors. |
| Shell gray | `#f2f2f2` | `--color-shell` | background | Outer page and footer underlay. |
| Pink white | `#fff9fe` | `--color-cream` | text, surface, background | Opening display and pale conversion buttons; full canvas only for company storytelling. |
| White | `#ffffff` | `--color-white` | text, background, surface | Text on dark fields and product-detail page canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| business proof sections | Proof purple | `#bb80ff` | `--color-proof-purple` | background | Bright result-card lower stop. |
| business proof sections | Proof gold | `#d9a46b` | `--color-proof-gold` | background | Bright result-card upper stop. |
| company storytelling | Dusty lilac | `#e9e2e7` | `--color-lilac-card` | surface | Principle-carousel cards. |

## Typography

- **Greed Condensed** — Display headlines, section titles, buttons and footer links. Tall condensed grotesk with substantial strokes and tightly packed lines. If unavailable, use **Barlow Condensed**. Use 600–700; retain the narrow silhouette and tight line spacing. Font stack: "Greed Condensed", "Barlow Condensed", sans-serif.
- **Greed** — Navigation, numerical proof and capsule labels. Compact solid grotesk, wider than the display face. If unavailable, use **DM Sans**. Use 600–700 and tighten numerical display tracking. Font stack: "Greed", "DM Sans", sans-serif.
- **Area** — Supporting copy, descriptions and testimonials. Geometric sans with open rounded counters; calmer and wider than the headings. If unavailable, use **Manrope**. Use 600–700; preserve small size and comfortable line spacing. Font stack: "Area", "Manrope", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Greed Condensed | 700 | 205.2px | 162px | -0.0049em | fixed | Centered stacked opening proclamation. |
| heading-lg | Greed Condensed | 700 | 96px | 0.91 | -0.025em | fixed | Default centered chapter heading and scenic closing title. |
| heading | Greed Condensed | 700 | 64px | 0.91 | -0.02em | fixed | Split feature heading. |
| stat | Greed | 600 | 54px | 0.92 | -0.03em | fixed | Three-column numerical proof. |
| audience-heading | Greed Condensed | 700 | 42px | 1.15 | -0.02em, uppercase | fixed | Short category title inside a tall audience card. |
| card-heading | Greed Condensed | 700 | 32px | 1 | -0.0187em | fixed | Icon-grid and media-column titles. |
| footer-heading | Greed Condensed | 600 | 24px | 28px | normal | fixed | Footer column titles. |
| hero-support | Area | 700 | 20px | 1.4 | normal | fixed | Centered two-line opening support. |
| button | Greed Condensed | 700 | 20px | 1.2 | normal | fixed | Main conversion and exploration actions. |
| body | Area | 700 | 16px | 1.5 | normal | fixed | Default paragraphs and feature descriptions. |
| footer-link | Greed Condensed | 700 | 16px | 1.25 | -0.0156em | fixed | Dense footer navigation. |
| eyebrow | Greed | 700 | 15px | 24px | normal, uppercase | fixed | Small outlined capsule above split feature headings. |
| navigation | Greed | 600 | 14px | 18px | normal | fixed | Top-level navigation labels. |
| navigation-action | Greed | 600 | 14px | 18px | normal | fixed | Compact navigation search and authentication actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| single-product spectacle openings | product-poster | Greed Condensed | 700 | 244.8px | 0.8 | -1.8px, uppercase | size 17vw | Two-line follow-through statement below the product object. |
| business landing pages | business-display | Greed Condensed | 700 | 194.4px | 0.82 | -8.6px | size 13.5vw, tracking -0.6vw | Wide left-aligned two-line promise on a deep dark field. |
| single-product spectacle openings | product-claim | Greed Condensed | 700 | 165.6px | 0.8 | -0.0109em, uppercase | size 11.5vw | Gradient-clipped opening claim above a very large product object. |
| company storytelling | company-display | Greed Condensed | 700 | 140px | 120px | -0.0114em | fixed | Large left-aligned editorial statements and recruitment close. |
| product detail pages | product-heading | Greed Condensed | 700 | 132px | 0.8 | -0.0258em | fixed | Oversized centered capability chapters. |
| product detail pages | feature-title | Greed Condensed | 700 | 36px | 24px | -0.0167em | fixed | Compact titles above individual demonstrations; keep single-line where possible. |
| product detail endings | explore-title | Greed | 600 | 21px | 20px | normal | fixed | Small related-capability title beside an icon tile. |
| product detail endings | explore-body | Area | 700 | 15.2px | 1.5 | normal | fixed | Short related-capability descriptions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the compressed display face and the wider body face visibly distinct. Do not simulate condensation by squeezing ordinary body text.
- The largest headings use unusually short line heights; line breaks should make compact word shapes, while paragraphs remain at 1.5.
- Declared semibold font cuts are visually semibold even where their CSS weight is 400. The normalized family names encompass those aliases.
- Gradient-clipped lettering is reserved for spectacle statements and special proof highlights, not routine body copy.

## Layout

**Density:** Airy, with full-height illustrated chapters and small, tightly set navigation clusters.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Navigation cluster and icon-to-label gaps. |
| 12px | Section heading to supporting copy; number to stat caption. |
| 15px | Audience-card and company-carousel gutters. |
| 16px | Main action vertical padding. |
| 24px | Feature heading to body; compact feature-row gap. |
| 32px | Main action horizontal padding. |
| 36px | Audience-card text inset and feature-copy-to-action separation. |
| 40px | Footer side inset and company editorial outer gutter. |
| 57.6px | Half chapter padding and alternating feature top/bottom breathing room. |
| 86.4px | Intermediate chapter transition. |
| 115.2px | Major section padding and chapter separation. |
| 200px | Company-storytelling chapter separation and footer lead-in to the wordmark. |

### Containers and grids

- **page container**: max width 1400px · side padding 25px. Wide desktop marketing frame, near edge-to-edge at 1440px.
- **split feature**: 2 columns · gap 0px. A roughly 680px-wide media stage beside a narrow text block, vertically centered; alternate sides across capability chapters.
- **paragraph measure**: max width 360px. Default split-feature copy, with headings allowed roughly 409px.
- **centered lead**: max width 950px. Centered section heading; supporting paragraphs narrow to about 600px.
- **audience grid**: max width 1400px · 3 columns · gap 15px. Tall equal cards with 453px × 583px desktop proportions.
- **proof grid**: max width 1400px · 3 columns · gap 0px. Centered numbers or icon-led features without visible card containers.
- **footer columns**: max width 1728px · 4 columns · gap 96px · side padding 40px. Wrapped link columns above the giant wordmark; 35px row separation.
- **product demonstration grid** (only for product detail pages): 2 columns · gap 20px · side padding 40px. Paired rounded panels about 670px wide and 695–758px tall.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | main action | 200px |
|  | compact action | 100px |
|  | audience card | 20px |
|  | comparison panel | 24px |
|  | footer top corners | 40px |
|  | product media stage | 43.2px |
| company storytelling | principle card | 32px |
| business proof sections | proof card | 28.8px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Default broad marketing canvas.

**CSS:** `background: #ededec`

**Observed:** A continuous pale field ties the product chapters together.

**Transfer:** Use whitespace and imagery, not panel outlines, to separate ordinary content.

#### Dark chapter · level 0

**Use:** A sustained capability or reassurance chapter.

**CSS:** `background: #221919; color: #ffffff`

**Observed:** Several adjacent sections share one uninterrupted warm dark background.

**Transfer:** Group a meaningful narrative change into one dark world rather than alternating every small block.

#### Opening gradient · level 0

**Use:** The default marketing opening.

**CSS:** `background: linear-gradient(0deg, #7db4f4 25%, #93b4f6 38%, #a6b4f7 47%, #68b8ab 83%, #21ba4c 99%); border-radius: 15px 15px 0px 0px`

**Observed:** A smooth luminous vertical field, green at the top and blue-lavender below, without a noisy mesh.

**Transfer:** Keep this broad color migration behind the poster headline and a few floating objects.

#### Stone card · level 1

**Use:** Audience choices and neutral media backing.

**CSS:** `background: linear-gradient(#e2dbd4 0%, #d1c9c1 100%); border-radius: 20px; overflow: hidden`

**Observed:** Softly shaded warm gray, without a drop shadow.

**Transfer:** Let the main object supply detail; the backing stays quiet.

#### Comparison panel · level 1

**Use:** Dense side-by-side differentiation inside a dark chapter.

**CSS:** `background: linear-gradient(#262221 26%, #564743 100%); border: 1px solid #3a3a3a; border-radius: 24px; overflow: hidden`

**Observed:** The subtle brown lift separates the table from the surrounding charcoal.

**Transfer:** Use low-contrast internal separators and concise parallel rows.

#### Blue sign-off · level 0

**Use:** Shared final footer.

**CSS:** `background: #98bbf4; border-radius: 40px 40px 0px 0px; padding: 65px 40px; color: #1a0000`

**Observed:** A substantial blue field, not a narrow utility strip.

**Transfer:** Reserve enough vertical room for navigation and the monumental wordmark.

#### Product canvas · level 0

**Only for:** product detail pages

**Use:** White field between deep oxblood chapters.

**CSS:** `background: #ffffff; color: #1a0000`

**Observed:** Product-detail content is brighter than the default pale-gray marketing world.

**Transfer:** Use the same type, object treatment and rounded geometry rather than treating this as a separate brand.

#### Principle card · level 1

**Only for:** company storytelling

**Use:** Compact carousel of principles or cultural promises.

**CSS:** `background: #e9e2e7; border-radius: 32px; overflow: hidden`

**Observed:** Dusty lilac panels hold a large decorative object in the upper-right and text at the bottom.

**Transfer:** Give each principle one visual metaphor.

#### Bright proof card · level 1

**Only for:** business proof sections

**Use:** One highlighted result within a quote grid.

**CSS:** `background: linear-gradient(0deg, #bb80ff 50%, #d9a46b 92%); border-radius: 28.8px; transform: rotate(-5deg)`

**Observed:** A slightly tilted warm-gold-to-purple result card contrasts with upright dark quote cards.

**Transfer:** Highlight one verified outcome, with a large faint typographic watermark behind the result.

## Components

### Fixed navigation

**Use:** Shared compact top navigation.

**CSS:** `position: fixed; background: #221919; height: 73px; width: 100%; z-index: 10`

**Text style:** `navigation` — Greed 600 · 14px/18px

**Observed:** Small wordmark at left, four audience/product menus with small downward chevrons, search and help on the right, then the gradient account action. A tiny utility row sits above the main row and visually recedes on scroll.

**Transfer:** Keep navigation compact and darker than every light page section.

### Primary button

**Use:** Default exploration or conversion action on pale fields.

**CSS:** `background: #170100; color: #ffffff; border-radius: 200px; padding: 16px 32px; height: 56px`

**Text style:** `button` — Greed Condensed 700 · 20px/1.2

**Observed:** A text-only capsule with width determined by its label. Pale companion actions share the silhouette.

**States:** Declared: hover opacity 1; color black.

### Pale button

**Use:** Main conversion on the colorful opening or scenic close.

**CSS:** `background: #fff9fe; color: #000000; border-radius: 200px; padding: 16px 32px; height: 56px`

**Text style:** `button` — Greed Condensed 700 · 20px/1.2

**Observed:** One centered capsule rather than a row of competing hero actions. Business dark openings use a light-gray version.

**States:** Declared: hover opacity 1; color black.

### Gradient account action

**Use:** Compact persistent conversion in navigation.

**CSS:** `background: linear-gradient(90deg, #82beff, #a6b4f7 47.21%, #5bb89a 73.75%, #21ba4c 91.26%); border: 1.5px solid transparent; border-radius: 100px; padding: 10px 20px; height: 38px; display: flex; align-items: center`

**Text style:** `navigation-action` — Greed 600 · 14px/18px

**Observed:** Tucked into the far-right navigation cluster, separate from the large page-level pills.

**States:** Declared: hover filter brightness(80%).

### Search capsule

**Use:** Small utility search action in navigation.

**CSS:** `background: #e3e3e3; color: #1a0000; border: 1px solid transparent; border-radius: 100px; padding: 8px 16px; height: 38px; gap: 8px; display: flex`

**Text style:** `navigation-action` — Greed 600 · 14px/18px

**Observed:** Magnifying-glass icon before the short label.

**States:** Declared: hover background-color #d2d2d0; border-color #d2d2d0.

### Feature capsule

**Use:** Small category label above a split feature.

**CSS:** `background: #ededec; border-radius: 500px; padding: 2px 10px 1px`

**Text style:** `eyebrow` — Greed 700 · 15px/24px · uppercase

**Observed:** The inner capsule sits inside a 2px outer frame with a faint multicolor edge; it reads as a small label, not an action.

**Transfer:** Wrap it with a thin gradient ring using the opening palette; preserve the pale interior.

### Audience card

**Use:** A small set of major paths through the product.

**CSS:** `background: linear-gradient(#e2dbd4 0%, #d1c9c1 100%); border-radius: 20px; overflow: hidden; position: relative`

**Text style:** `audience-heading` — Greed Condensed 700 · 42px/1.15 · tracking -0.02em · uppercase

**Observed:** Each tall card combines a short uppercase title, one short explanatory line and a large isolated product object. One card reverses the text/object order for rhythm. Text inset is 36px.

**Transfer:** Use different object poses, not three identical tiny icons.

### Comparison table

**Use:** Compact proof of practical advantages.

**CSS:** `background: linear-gradient(#262221 26%, #564743 100%); border: 1px solid #3a3a3a; border-radius: 24px; overflow: hidden`

**Text style:** `body` — Area 700 · 16px/1.5

**Observed:** Two equal-width columns, short uppercase condensed column labels and parallel rows with small outlined check/cross marks. Row separators stay faint; the panel spans nearly the full container.

**Transfer:** Compare concrete differences in consistent grammatical form.

### Footer link

**Use:** Dense navigation on the blue sign-off.

**CSS:** `color: #1a0000; text-decoration: none; transition: 0.3s ease-out`

**Text style:** `footer-link` — Greed Condensed 700 · 16px/1.25 · tracking -0.0156em

**Observed:** Links form vertical lists with 4px gaps beneath 24px condensed column headings.

**States:** Declared: hover opacity 0.7.

### Related capability row

**Only for:** product detail endings

**Use:** Small links to adjacent capabilities before the footer.

**CSS:** `display: flex; align-items: center; gap: 24px; padding: 24.5px; border-radius: 16px; max-width: 550px`

**Text style:** `explore-title` — Greed 600 · 21px/20px

**Observed:** A 90px warm-gray icon tile at left, then a short title and a two-line smaller description. Three columns wrap to a second row; the link itself has no filled panel.

**States:** Declared: hover transform translateY(-2px); box-shadow rgba(0, 0, 0, 0.1) 0px 8px 25px.

**Transfer:** Keep these quieter than the main product demonstrations.

### Principle carousel card

**Only for:** company storytelling

**Use:** Human-scale editorial principles.

**CSS:** `background: #e9e2e7; border-radius: 32px; width: 376px; height: 374px; overflow: hidden`

**Text style:** `card-heading` — Greed Condensed 700 · 32px/1 · tracking -0.0187em

**Observed:** An oversized glossy metaphor enters from the top-right; a tiny dark category pill precedes title and body near the lower edge. A clipped next card suggests horizontal continuation; 44px circular previous/next controls sit below.

**Transfer:** Use one category, one principle and one brief explanation per card.

## Imagery and graphics

### Glossy object confetti

**Use:** Signature accents in the opening and around major illustrated stages.

**Observed:** Faceted green and cyan gems, violet butterflies, shiny orange disks, metallic locks and pearlescent hearts float at different sizes and rotations. Objects overlap selected headline edges or enter from off-canvas without obscuring the words; they have strong specular highlights and toy-like volume.

**Transfer:** Create a coherent original family of three to five motifs related to the new product. Use fewer high-quality objects rather than many generic flat symbols.

**Build:** Construct faceted SVG polygons with light, middle and dark green or cyan fills, a sharp white triangular highlight and a subtle translucent shadow. Add oval coin-like forms with orange/gold gradient fill, a darker narrow rim and white star glints. Rotate and scale instances between roughly 50px and 180px; cluster at outer edges, with one or two small foreground overlaps.

### Scenic product stages

**Use:** Default split features, demonstrations and the closing invitation.

**Observed:** Large phone and browser fragments stand in invented landscapes: smooth folded green hills, orange dunes, distant mountains, cloud puffs and rainbow skies. The UI remains crisp and readable while the surrounding scene is saturated and slightly surreal. Media is clipped to rounded rectangles, often cutting the device at the bottom or right edge.

**Transfer:** Use a real product view, or a simplified truthful three-control panel, enlarged over a scenic backing. Keep one clear focal object; do not populate every stage with different decorative styles.

**Build:** Layer an SVG sky rectangle with a vertical blue–pink–yellow gradient, then five to eight overlapping broad Bézier hill shapes in alternating light and dark greens. Put the horizon in the lower half, reduce contrast toward the horizon, and place a large device panel in front. Clip the entire scene to a 20px–43.2px rounded frame; add two or three glossy foreground motifs.

### Human cutouts in fantasy worlds

**Use:** Opening media bridge and reassurance imagery.

**Observed:** A real hand holds a nearly upright phone against clouds and a rainbow; another scene shows hands holding food. Portraits are clean close-ups backed with pastel skies and green foliage, sometimes combined with glossy butterflies. They are collages rather than documentary office photography.

**Transfer:** Choose tightly framed human gestures that show the new product's real use. Separate the person cleanly from the background and stage them in the same bright illustrated world.

### Staggered media bridge

**Use:** The transition from the default opening to the explanatory chapters.

**Observed:** A taller central hand-and-phone image rises above two side images; the outer images are clipped by the viewport. Rounded corners soften the collage and the blue opening background continues behind its upper portion.

**Transfer:** Make one primary usage scene and two complementary details; maintain the tall-center/low-sides silhouette.

**Build:** Arrange three rounded image or SVG panels in a horizontal track wider than the viewport. Lift the center panel by roughly a third of its height and let the side panels bleed beyond the frame; continue the opening sky behind the upper half and the pale canvas behind the lower half.

### Monumental wordmark

**Use:** Required final brand artwork inside the blue footer.

**Observed:** A dark custom wordmark almost fills the width, far larger than the navigation or footer menus. It occupies a 1360px × 680px artwork area with legal and utility text beneath.

**Transfer:** Use the new brand's own wordmark. If none exists, typeset its short name in a heavy grotesk and convert it to scalable SVG, preserving the broad edge-to-edge silhouette.

**Build:** Use an SVG with a wide viewBox, dark filled glyph paths and no effects; fit it to the footer width below the link columns. Keep a substantial 200px breathing space before the artwork and a small utility baseline after it.

### Object-wreath manifesto

**Only for:** company storytelling

**Use:** A celebratory statement between editorial chapters.

**Observed:** A deep oxblood rounded panel has a loose perimeter wreath of shiny everyday objects. The center stays clear for two lines of rainbow-gradient condensed capitals and a narrow white paragraph.

**Transfer:** Use a finite set of metaphors for the product's possibilities, with the central message carrying the story.

**Build:** Place 18–24 small SVG or rendered objects along the four edges of a rounded dark rectangle, varying scale and rotation; leave the middle half unobstructed. Clip a vertical pink–yellow–cyan–green gradient into the display text.

### Icons

**Observed:** Navigation uses small 18px monochrome symbols and chevrons; capability grids use larger 70px circular medallions or 90px stone tiles. Illustrative locks and gems are separate from the functional icon system.

**Transfer:** Use compact, simple monochrome functional icons for utilities and feature lists. Reserve glossy volume for the major visual metaphors rather than adding gradients to every small icon.

## Section recipes

How recurring sections are built.

### First screen: Gradient poster opening

**Observed:** A 73px fixed warm-charcoal navigation bar caps a full-width green-to-blue-lavender Opening gradient with gently rounded top corners. Back to front: smooth gradient, scattered glossy gems and butterflies, centered pale condensed headline, support copy and Pale button. The three headline lines use display type and form a 486px-high centered stack occupying roughly the central half of the width; each successive line widens into a poster silhouette. The support line is 650px wide in hero-support type, about 31px below the stack; the action follows by 50px. Within the first 900px the entire headline, two-line explanation, floating objects and action are visible. The large hand-and-device media bridge begins below that first screen, not beside the headline.

**Transfer:** Replace the slogan with a short three-part promise and keep its large narrow word shapes. Without rendered artwork, use the buildable faceted objects and a truthful simplified product panel in the media bridge. Business pages instead open with a left-aligned two-line business-display on oxblood, narrow copy, a horizontal benefit strip and pale action. Single-product spectacle pages use a gradient claim above an oversized object, with the support statement and action below the first fold. Company stories open with company-display at left and a rounded photographic collage at right.

**Avoid:** Do not turn the default into a conventional small heading plus laptop two-column hero, add a second equal CTA, or force the product interface into the first screen beside the poster.

**Text style:** `display` — Greed Condensed 700 · 205.2px/162px · tracking -0.0049em

### Centered chapter lead

**Observed:** A heading-lg centered within a 950px measure, then 12px to a short paragraph narrowed to about 600px. Major transitions commonly use 115.2px vertical padding; product detail chapters use product-heading for a larger poster scale.

**Transfer:** Use a brief outcome statement to introduce a capability family, not a label that merely repeats the navigation.

**Text style:** `heading-lg` — Greed Condensed 700 · 96px/0.91 · tracking -0.025em

### Alternating illustrated feature

**Observed:** A two-column composition pairs a Scenic product stage about 680px × 753px with a centered-in-height text stack: Feature capsule, 18px to heading, 24px to body and about 36px to Primary button. Text uses a roughly 409px heading measure and 360px body measure. Adjacent feature chapters swap text and image sides.

**Transfer:** Give each chapter one concrete user outcome and one legible product moment.

**Text style:** `heading` — Greed Condensed 700 · 64px/0.91 · tracking -0.02em

### Audience and numerical proof

**Observed:** Three Audience cards sit in a 15px-gap grid, followed by a quiet three-column stat row with 54px numbers and small centered captions separated by 12px. Cards carry the vivid product objects; the numerical row has no enclosing card surfaces.

**Transfer:** Show distinct user pathways and then verified scale or impact. Preserve the visual contrast between rich cards and unboxed numbers.

**Text style:** `stat` — Greed 600 · 54px/0.92 · tracking -0.03em

### Dark capability world

**Observed:** Dark chapter joins a large centered lead, a three-column icon grid and tall media columns on one uninterrupted warm-charcoal field. Icon-grid titles use card-heading and support copy uses muted inverse gray. The Comparison table is a broad inset panel later in the same dark world.

**Transfer:** Use one dark chapter to deepen confidence through controls, workflow or proof; vary the components without resetting the background each time.

### Scenic closing invitation

**Observed:** A nearly full-width 1390px × 631px Scenic product stage becomes a closing banner. Centered white heading-lg, one short paragraph and a Pale button sit above rolling green hills; glossy motifs frame the edges rather than the center. The blue footer begins after a visible pale gap.

**Transfer:** Close broad marketing pages with an inviting scene and a single action; adapt its imagery to the new product's world.

**Text style:** `heading-lg` — Greed Condensed 700 · 96px/0.91 · tracking -0.025em

### Blue monumental footer

**Observed:** Blue sign-off spans the viewport with 40px top corners and 65px 40px outer padding. Four columns of condensed navigation wrap into a second row, then 200px of breathing room precedes the huge Monumental wordmark. Tiny legal copy sits at lower left and utility links align at lower right.

**Transfer:** Keep this branded final scene on every page type; change the navigation content and use the new product's own wordmark.

**Text style:** `footer-heading` — Greed Condensed 600 · 24px/28px

### Paired product demonstrations

**Only for:** product detail pages

**Observed:** Two large rounded panels use stone or saturated vertical-gradient backing, with 36px titles and small body text near the top and oversized interface fragments filling the lower part. At desktop the panels are about 670px wide, separated by 20px, with 43.2px corners.

**Transfer:** Teach one operation per panel and alternate neutral and scenic panels so that the grid does not become an all-gradient checkerboard.

**Text style:** `feature-title` — Greed Condensed 700 · 36px/24px · tracking -0.0167em

### Mixed testimonial proof

**Only for:** business proof sections

**Observed:** A large condensed centered lead introduces a three-column quote grid on oxblood. Upright dark brown quote cards use small bright quotation marks and generous inner breathing room; one Bright proof card tilts -5deg and carries a condensed result over a faint oversized watermark.

**Transfer:** Use genuine quotations plus one verified outcome; vary the proof medium while retaining one clear hierarchy.

### Company editorial close

**Only for:** company storytelling

**Observed:** After the lilac principle carousel, a 1359px × 678px rounded recruitment banner blends blue-purple into dusty pink. Small rounded portrait and object tiles enter from its edges; a 140px statement, short support and pale pill occupy the center. A 200px interval separates this from the shared blue footer.

**Transfer:** Use an equivalent invitation to participate, join or learn more, with people and object tiles drawn from the new organization.

**Text style:** `company-display` — Greed Condensed 700 · 140px/120px · tracking -0.0114em

### Related capabilities ending

**Only for:** product detail pages

**Observed:** The final content section is a large centered exploration heading above Related capability rows in a three-column, two-row grid. Simple stone icon tiles and short descriptions lead into generous white breathing room, then the shared blue footer. It is not another full scenic conversion banner.

**Transfer:** End detailed product stories by opening adjacent paths rather than repeating the broad marketing close.

## Page flow

**Storyline:** Bold promise → immersive product world → concrete pathways and capabilities → proof and reassurance → invitation or adjacent paths → monumental branded sign-off.

### Broad platform or marketing landing page

1. **Promise** — Centered gradient poster with floating glossy motifs and one action.
2. **Product world** — Staggered human/product media bridge.
3. **Orientation and quantified proof** — Centered lead, three audience cards and unboxed numerical proof.
4. **Capability chapters** — Alternating scenic product stages and narrow copy.
5. **Confidence** — Sustained dark controls, workflow and comparison chapter followed by pale security and objection-handling sections.
6. **Closing invitation** — Scenic banner and single pill action.
7. **Brand sign-off** — Blue link directory and monumental wordmark.

**Transfer:** Use this as the default expressive landing-page approach, shortening or expanding capability chapters to suit the new product.

### Company or movement story

1. **Human promise** — Left-aligned editorial statement, narrow story copy and colorful photographic collage.
2. **Shared purpose** — Portrait and large statement swap sides.
3. **Manifesto** — Dark object wreath around gradient lettering.
4. **Principles** — Short intro and lilac horizontal carousel.
5. **Participation invitation** — Gradient portrait-tile banner with an action.
6. **Brand sign-off** — Shared blue directory and wordmark.

**Transfer:** Use more conversational story paragraphs and people imagery; keep cultural graphics scoped to this editorial purpose.

### Business product landing page

1. **Promise** — Wide two-line headline on oxblood, compact explanation, benefit checks and pale action.
2. **Product demonstration** — Large rounded motion stage and three concise benefit columns.
3. **Catalog and differentiated value** — Centered lead with a broad logo field, followed by a dark special-value stage.
4. **Capability chapters** — Paired neutral demonstrations and a scenic technical integration band.
5. **Social proof** — Dark quote grid with one tilted colorful result card.
6. **Practical flexibility** — Large paired product-use panels and a compact dark reassurance strip.
7. **Adjacent paths** — Related capability grid, whitespace and shared blue footer.

**Transfer:** Balance spectacle with operational detail and honest proof. Use the tilted result treatment as a focal point, not on every card.

### Single-product feature story

1. **Promise and spectacle** — Gradient uppercase claim, oversized product object and a second monumental two-line statement; action follows below.
2. **Usage demonstration** — Centered terse lead over a wide human/device scene.
3. **Capability chapters** — White canvas with paired warm-gray and colorful demonstration panels.
4. **Reassurance** — Oxblood chapter combines feature lists, product scenes, a wide inset quote and a large metallic security metaphor.
5. **Ease of adoption** — Return to white with a short lead and two large scenic panels.
6. **Adjacent paths** — Related capability rows, white breathing room and shared blue footer.

**Transfer:** Let one hero object dominate, then explain practical interactions. Preserve the long dark reassurance world and quiet cross-exploration ending.

## Writing

Confident, welcoming and a little cheeky: practical benefits are presented as freedom, control and an easier everyday life. Business copy stays operational while the surrounding headlines remain punchy.

**Do not copy:** Do not reuse Fluz names, logos, branded art, customer names, quotations, partner marks, financial rates, limits, certifications or performance claims. All new claims must be true of the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for the reader, we for the team and the product name when explaining what it does. Favor reader control over institutional authority.
- **Rhythm:** Short headline bursts contrast with one- or two-sentence supporting paragraphs. Full stops and three-part fragments create momentum; longer conversational paragraphs belong to company stories.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An everyday aspiration pushed to its maximum, or a clear product category followed by its audience. | 4–9 words | “YOUR MONEY ON MAX.”<br>“Gift card solutions, built for business.” |
| Section heading | A compact benefit, often paired clauses or a three-beat sequence. | 3–8 words | “Tap. Pay. Earn.”<br>“Move fast, scale faster.”<br>“People power that pays” |
| Supporting line | Start with a concrete action or practical reassurance, then explain the resulting freedom. | 15–40 words | “[Brand] is built to fit into how you already move money, working alongside your bank and existing payment methods.”<br>“There’s no physical card to wait for. It’s instant. Just link your bank and start earning.” |
| Action | Plain verb plus destination or outcome; remove unnecessary ceremony. | 2–5 words | “Get yours”<br>“Explore virtual cards”<br>“Sign up. It's free.” |
| Objection handling | Name the reader's worry directly with everyday language. | 2–7 word heading | “No sneaky fees”<br>“Trip-wire free” |

**Words and phrasing to use:** your way; built in; keep your existing; instant; control; easy; real; without; get more; no sneaky

**Avoid:** synergistic; enterprise-grade transformation; revolutionary ecosystem; unlock unparalleled potential; exclusive access for the elite

**Rules:**

- Lead with the outcome, then show the mechanism in the paragraph.
- Use inclusive language and concrete friction removed rather than status anxiety.
- Keep technical terms inside practical descriptions; a short heading should still make sense without them.
- When making a numerical claim, pair it with its conditions or a nearby disclosure path.

## Do's and Don'ts

### Do

- Use 96px/0.91 condensed chapter headings and 64px/0.91 split-feature headings in the default marketing treatment.
- Keep split-feature body text near 360px wide even when the media stage spans about 680px.
- Use 56px main capsules and 38px compact navigation actions as two distinct scales.
- Let major dark chapters continue across several components on #221919.
- Use 15px audience-card gutters and 20px product demonstration gutters rather than one universal card grid.
- Include a real product moment inside each major scenic stage, with large readable controls.
- Finish with the #98bbf4 rounded footer and a monumental dark wordmark.
- Keep ordinary cards shadowless; use strong color and object scale to create emphasis.

### Don't

- Do not set the main headings in the same wide geometric sans as the 16px body copy.
- Do not spread display letter spacing positively; the large type is tightly packed and usually uses negative tracking.
- Do not give 56px page actions square corners or the same dimensions as navigation controls.
- Do not turn all pale sections pure white; #ededec is the default broad marketing canvas.
- Do not apply glossy rainbow fills to every icon, paragraph or divider; functional controls remain simple.
- Do not give every proof card a tilt; the -5deg treatment marks one standout result.
- Do not replace the blue sign-off with a small dark legal bar.
- Do not put a filled card behind every icon-led capability; the three-column proof grids often sit directly on the canvas.

## Motion and responsive

### Motion

**Observed:**

- Main action text declares color 0.3s transitions; footer links declare 0.3s ease-out and hover opacity 0.7.
- Audience cards declare transform and box-shadow transitions of 0.4s cubic-bezier(0.22, 1, 0.36, 1).
- Related capability rows declare a 0.3s transition and a -2px hover lift with a soft shadow.

**Transfer:**

- Keep the audience cards and related capability rows as the hover-responsive surfaces; the large scenic artwork should not become an unrelated collection of bouncing utility controls.

**Unknown:**

- Scroll choreography, playback speed and moving-object trajectories are not established.
- Focus-visible and active appearances are not established.

### Responsive

**Observed:**

- Several display roles use viewport sizing: business-display 13.5vw with -0.6vw tracking; product-claim 11.5vw; product-poster 17vw.
- Related capability row padding follows 1.7vw.

**Transfer:**

- Preserve the tall condensed poster silhouette at smaller widths, reduce decorative-object count before reducing headline impact, and stack product stages with their matching copy.
- Keep the final wordmark scalable as SVG and wrap the footer directory before it.

**Unknown:**

- Exact mobile navigation, stacking breakpoints and mobile section heights are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
