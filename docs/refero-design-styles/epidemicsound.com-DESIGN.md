# Epidemic Sound — editorial sound in color

## Overview

A confident editorial style with a playful, tactile streak, suited to creative tools and products that combine professional capability with personal expression. Warm off-white space and black serif headlines give way to bubblegum pink, lemon yellow, electric blue and charcoal chapters. Grotesk interface text grounds cinematic photography, cutout collages and oversized product demonstrations; the overall density is spacious rather than dashboard-like.

### Essentials

- Headlines turn a key phrase into a change of voice: Sebenta 500 at 80px/1 with -0.03em tracking in the opening, 64px/68px in chapters, with true serif italics embedded in the sentence.
- The opening sells the outcome before showing the machinery: centered two-line headline, three compact benefits, paired 56px pill actions, then a near-edge-to-edge rail of 432px square cinematic media beginning within the first 900px.
- Navigation floats like a white capsule above every color chapter: 1359px maximum width, 68px height, 12px inner padding and 44px nested controls; main actions are black pills with white 16px/24px semibold text.
- Color belongs to entire scenes, not tiny decorative accents: keep the opening and utility ending off-white, use pink and yellow full-width capability stages, charcoal gallery chapters and ecru editorial space. On an expressive landing page, colored and dark chapters occupy more of the story than the neutral opening.
- Media has two complementary registers: authentic cinematic square footage and deliberately impossible cutout compositions over flat colored rectangles. Include a collage stage; when specialist artwork is unavailable, combine one crisp product or human cutout, one landscape fragment and two offset color blocks.
- A monumental typographic statement is a signature punctuation mark: 128px/1 serif, -0.04em tracking, upright first line shifted left and italic second line shifted right, centered black pill below, all on an uninterrupted pink field.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Bubblegum pink | `#ff82c2` | `--color-pink` | background, surface, accent | Signature feature stages, editorial overlay cards and monumental statement. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#20afff` | `--color-blue` | background, surface | Flat collage rectangles and product announcement stage. |
| Hot orange | `#ff6138` | `--color-orange` | surface | Portrait proof card information panel and vivid imagery backing. |
| Lemon yellow | `#ffda40` | `--color-yellow` | background, surface | Full-width capability stage and bright portrait information panels. |
| Fresh green | `#5ad363` | `--color-green` | surface | Portrait proof card information panel; not a success-status convention. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action | Primary text, primary actions and compact image labels. |
| Dark portrait backing | `#1d1f24` | `--color-portrait-dark` | surface | Low-key studio portrait backing. |
| Gallery charcoal | `#292c33` | `--color-charcoal` | background | Deep gallery chapters with white headings. |
| Charcoal lift | `#363a41` | `--color-gallery-card` | surface | Gallery tile footer, pale blue-gray #cfd6e5 at 8% over charcoal. |
| Secondary ink | `#60605e` | `--color-muted` | text | Secondary text on warm off-white; black at 60% opacity. |
| Muted mauve block | `#9793a5` | `--color-mauve` | surface | Offset lower block in geometric product collages. |
| Olive portrait backing | `#bfbda8` | `--color-olive-gray` | surface | Warm muted portrait stage. |
| Blue-gray stage | `#cfd6e5` | `--color-blue-gray` | surface, background | Geometric collage backing and cool portrait stage. |
| Editorial ecru | `#e4d9cf` | `--color-ecru` | background, surface | Editorial chapters and warm portrait backing. |
| Cool pill | `#dbdcdd` | `--color-secondary-action` | action, surface | Secondary action fill on warm off-white; blue-gray #3d4d74 at 12% opacity. |
| Fine edge | `#deddd8` | `--color-rule` | border | Visible hairlines on warm off-white, using black at 8% opacity. |
| Cool gray wash | `#e6e6e4` | `--color-soft-panel` | surface | FAQ surfaces on warm off-white; blue-gray #3d4d74 at 6% opacity. |
| Warm off-white | `#f1f0eb` | `--color-canvas` | background | Default opening, informational sections, FAQs and footer. |
| White elevation | `#ffffff` | `--color-white` | surface, text | Floating navigation, pricing cards and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing modules | Pale periwinkle | `#f0f4ff` | `--color-pricing-wash` | surface | Blue #6792ff at 10% over white within plan cards. |
| pricing modules | Warm segmented track | `#ebe9e4` | `--color-segment-wash` | surface | Warm gray #b1a9a2 at 10% over the canvas. |

## Typography

- **Sebenta** — Headlines, editorial titles, card names and expressive italic emphasis. Sturdy contemporary editorial serif with broad lowercase, emphatic round forms and a fluent contrasting italic. If unavailable, use **Source Serif 4**. Use 500 and its true italic; tune line breaks to preserve broad headline silhouettes. Font stack: "Sebenta", "Source Serif 4", Georgia, "Times New Roman", "Noto Serif", serif.
- **Inter** — Body copy, benefits, navigation, labels, buttons and supporting data. Matter-of-fact grotesk, usually medium rather than light. Font stack: "Inter", Arial, "Helvetica Neue", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | Sebenta | 500 | 128px | 1 | -0.04em | Monumental statement on the pink stage. |
| statement-italic | Sebenta | 500 italic | 128px | 1 | -0.04em | Second, offset line of the monumental statement. |
| display | Sebenta | 500 | 80px | 1 | -0.03em | Default centered landing-page headline. |
| display-italic | Sebenta | 500 italic | 80px | 1 | -0.03em | Meaningful final phrase inside the opening headline. |
| heading-lg | Sebenta | 500 | 64px | 68px | -0.03em | Major capability chapters; also the default headline size for focused informational pages. |
| heading-lg-italic | Sebenta | 500 italic | 64px | 68px | -0.03em | One emphasized phrase within a major chapter headline. |
| heading-md | Sebenta | 500 | 48px | 54px | -0.03em | Editorial overlay title and centered process-section heading. |
| heading | Sebenta | 500 | 40px | 1.2 | -0.03em | FAQ headings, story titles, process steps and main price figures. |
| heading-sm | Sebenta | 500 | 32px | 1.25 | -0.03em | Portrait names and image/text feature headings. |
| tile-title | Sebenta | 500 | 24px | 1.25 | -0.02em | Gallery tile labels and short capability subheads. |
| media-caption | Inter | 500 | 24px | 32px | normal | Customer name below a cinematic proof image. |
| editorial-caption | Sebenta | 500 | 20px | 1.2 | -0.02em | Centered sentence beneath a collage, with selected words in true italic. |
| lead | Inter | 500 | 18px | 28px | normal | Opening benefits and short chapter support lines. |
| body | Inter | 500 | 16px | 1.5 | normal | Explanatory paragraphs and editorial support. |
| action | Inter | 600 | 16px | 1.5 | normal | Main action labels, standalone links and FAQ questions. |
| small | Inter | 500 | 14px | 24px | normal | Reassurance, card details and footer links. |
| nav | Inter | 600 | 14px | 24px | normal | Navigation labels and compact header actions. |
| eyebrow | Inter | 600 | 14px | 24px | 0.1em, uppercase | Section labels and story classifications. |
| micro-label | Inter | 500 | 12px | 16px | 0.1em, uppercase | Footer column headings and plan feature-group labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing modules | price-fraction | Sebenta | 500 | 20px | 1 | -0.06em | Raised fractional amount beside a 40px price. |
| pricing modules | plan-name | Inter | 500 | 20px | 1.2 | normal | Plan name above the serif price. |

**Notes:**

- Use serif italics as semantic emphasis within otherwise upright sentences, not as a separate script accent or an italic treatment for all copy.
- Display tracking stays at -0.03em through the main heading sizes; the monumental statement tightens to -0.04em. Small serif roles relax to -0.02em.
- Maintain the contrast between expressive serif headings and neutral Inter controls. Body copy is predominantly 500, main actions 600.
- The centered hero may wrap into two balanced lines; the monumental statement deliberately offsets its two lines rather than sharing a rigid left edge.

## Layout

**Density:** Airy in narrative sections, compact inside controls and data modules; broad editorial pauses surround unusually large imagery.

### Spacing

**Spacing system:**

- **small gutter** 16px, horizontal — Declared small grid padding and gutter; desktop grids retain this gap.
- **medium inset** 32px, horizontal — Declared medium grid padding and plan-card side padding.

| Value | Use |
| --- | --- |
| 8px | Inline icon gaps, FAQ row separation and footer heading-to-list gap. |
| 12px | Capsule navigation padding and internal group gaps. |
| 16px | Grid gutters, paired action gaps and reassurance offset. |
| 24px | FAQ padding, feature paragraph rhythm and portrait panel sides. |
| 32px | Benefit-to-action rhythm and demonstration spacing. |
| 48px | Editorial action separation and compact chapter breathing room. |
| 64px | Section title to process grid or FAQ stack; statement to action. |
| 80px | Opening vertical padding, feature-section separation and footer top padding. |
| 128px | FAQ chapter breathing room and comparison-table band padding. |
| 144px | Top padding on dark gallery chapters. |
| 240px | Top and bottom breathing room around the monumental statement. |

### Containers and grids

- **page grid**: max width 1440px · 12 columns · gap 16px · side padding 56px. Centered desktop grid; usable width is 1328px at a 1440px viewport. Backgrounds bleed to the edges.
- **navigation capsule**: max width 1359px · side padding 12px. Independent floating container inside a 16px outer header inset.
- **hero headline**: max width 1104px. Wide, centered headline that still leaves visible side space.
- **support measure**: max width 640px. Focused product introductions and longer support paragraphs.
- **three column**: 3 columns · gap 16px. 432px-wide process, story or pricing columns at desktop.
- **split chapter**: 2 columns · gap 16px. Two 656px columns; image and vertically centered copy alternate sides.
- **gallery grid**: 4 columns · gap 16px. 320px square image tiles with caption footers.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsules | 9999px (pill) |
|  | cards and accordions | 8px |
| expanded locale controls | locale menu | 16px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating navigation | `0px 2.2px 4.3px 0px rgba(0, 0, 0, 0.043)` | Very faint separation under the white capsule. |
| expanded locale controls | locale dropdown | `0px 8px 16px 0px rgba(0, 0, 0, 0.25)` | Raised white language menu, not ordinary content cards. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default page field.

**CSS:** `background: #f1f0eb; color: #000000`

**Observed:** Opening and utility ending share the same warm field.

**Transfer:** Let this neutral ground separate vivid narrative scenes.

#### Color stage · level 0

**Use:** Full-width capability chapter and statement.

**CSS:** `background: #ff82c2; color: #000000`

**Observed:** Pink is the signature fill; yellow and electric blue form distinct scene variants. Fields are flat and edge-to-edge, not pastel gradients.

**Transfer:** Assign one saturated field to each strong visual idea, keeping text black.

#### Dark gallery · level 0

**Use:** Image-rich exploration and portrait chapters.

**CSS:** `background: #292c33; color: #ffffff; padding: 144px 0px 72px`

**Observed:** White serif text frames vivid imagery and colorful card bases.

**Transfer:** Use charcoal to make a collection feel curated rather than like a utility list.

#### Editorial ecru · level 0

**Use:** News, updates and collage caption zones.

**CSS:** `background: #e4d9cf; color: #000000`

**Observed:** A warmer field supports layered photography and a bright rectangular title panel.

**Transfer:** Use for editorial storytelling rather than another white card grid.

#### Soft panel · level 1

**Use:** FAQ rows.

**CSS:** `background: rgba(61, 77, 116, 0.06); border-radius: 8px`

**Observed:** A faint cool wash distinguishes rows without outlines or shadows.

**Transfer:** Reserve the subtle surface for utility content so it contrasts with the vivid chapters.

#### Plan elevation · level 1

**Only for:** pricing modules

**Use:** Plan cards.

**CSS:** `background: #ffffff; border-radius: 8px; box-shadow: none`

**Observed:** White-on-off-white separation; no heavy keyline.

**Transfer:** Keep plan differences in content, not competing material effects.

#### Allowance inset · level 2

**Only for:** pricing modules

**Use:** Grouped allowances within a white plan card.

**CSS:** `background: rgba(103, 146, 255, 0.1); border-radius: 8px; padding: 16px`

**Observed:** Pale periwinkle inset with small uppercase label and a short checked list.

**Transfer:** Use for a meaningful feature bundle, not a decorative recommended-plan halo.

## Components

### Floating navigation

**Use:** Persistent top-level navigation.

**CSS:** `display: flex; align-items: center; gap: 12px; max-width: 1359px; height: 68px; padding: 12px; background: #ffffff; border-radius: 9999px; box-shadow: 0px 2.2px 4.3px 0px rgba(0, 0, 0, 0.043)`

**Text style:** `nav` — Inter 600 · 14px/24px

**Observed:** Compact symbol at left, topical links through the middle, a subtle divider before business links, then login and account actions at right. A sticky 100px header wrapper leaves 16px above and below the capsule. Nested actions are 44px tall; the white capsule persists over dark and bright scenes.

**Transfer:** Use a compact product symbol rather than a long logotype in the top capsule.

### Primary button

**Use:** Main conversion or product-entry action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 56px; padding: 9.6px 24px; background: #000000; color: #ffffff; border-radius: 9999px`

**Text style:** `action` — Inter 600 · 16px/1.5

**Observed:** Content-sized in narrative sections and full-width in plan cards. Compact header variant is 44px high with 4px 16px padding and the nav recipe.

**States:** Declared: hover background #272727; focus-visible outline 2px solid #000000 with 2px offset; active background #333333.

### Secondary button

**Use:** Sales or alternate path beside the main action.

**CSS:** `height: 56px; padding: 9.6px 24px; background: rgba(61, 77, 116, 0.12); color: #000000; border-radius: 9999px`

**Text style:** `action` — Inter 600 · 16px/1.5

**Observed:** Sits alongside the primary action with a 16px gap; cool gray fill rather than a black outline.

**States:** Declared: hover background #3D4D742E; focus-visible outline 2px solid #000000 with 2px offset; active background #3D4D743D.

### Standalone arrow link

**Use:** Editorial story and comparison actions.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; padding: 4px 0px; height: 44px; color: #000000`

**Text style:** `action` — Inter 600 · 16px/1.5

**Observed:** Text plus small directional arrow, right-pointing for story links and down-pointing for comparison navigation. No pill backing.

**States:** Declared: hover border-bottom 2px solid; active border-bottom-color currentcolor.

### FAQ row

**Use:** Objection handling near the utility ending.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 24px; background: rgba(61, 77, 116, 0.06); border-radius: 8px`

**Text style:** `action` — Inter 600 · 16px/1.5

**Observed:** Closed row is 72px high with the question at left and a small chevron at right; rows are separated by 8px. Expanded answer uses body text below, generally in secondary ink.

**States:** Declared: hover background #3D4D741F; focus-visible outline 2px solid #000000 with 2px offset; active background #3D4D742E.

### Gallery tile

**Use:** Visual category navigation in a dark chapter.

**CSS:** `display: grid; overflow: hidden; background: rgba(207, 214, 229, 0.08); border-radius: 8px`

**Text style:** `tile-title` — Sebenta 500 · 24px/1.25 · tracking -0.02em

**Observed:** 320px square art above a 62px caption footer with 16px padding. Four columns separated by 16px. Artwork is dense and expressive; footer text is white.

**Transfer:** Group new product use cases by visual mood, with one unmistakable object or scene per tile.

### Portrait proof card

**Use:** People-led credibility in a horizontal rail.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; background: #ffda40; border-radius: 8px`

**Text style:** `heading-sm` — Sebenta 500 · 32px/1.25 · tracking -0.03em

**Observed:** 432px square portrait above a bright information panel, total card height 652px. Small black category tab hugs the bottom of the image; below are the serif name, a short 'Featured in' lead and two icon-led reach metrics in body type. Panel padding is 16px 24px 24px. Yellow, green, pink and orange variants sit together on charcoal; 56px circular back/next controls sit beneath.

**Transfer:** Use makers, customers or experts with truthful compact proof. Keep statistics subordinate to the person, not giant isolated counters.

### Editorial overlay card

**Use:** Featured update over a wide photograph.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #ff82c2; padding: 16px 32px 16px 16px`

**Text style:** `heading-md` — Sebenta 500 · 48px/54px · tracking -0.03em

**Observed:** Bright rectangular title slab overlaps the lower-left of a large image; body support sits toward its lower edge. Narrow numbered previews stack along the image's right edge. No floating glass, border or corner rounding.

**Transfer:** Use a real in-context product photograph and a short editorial title rather than putting text directly over a busy image.

### Footer directory

**Use:** Shared final utility section.

**CSS:** `padding: 80px 0px 0px; background: #f1f0eb`

**Text style:** `small` — Inter 500 · 14px/24px

**Observed:** Brand lockup and locale pill occupy the left; an 880px block at right contains four 220px link columns, with the final column subdivided into integration and app groups. Micro-label headings precede 40px link rows. A fine black-at-8% top rule separates the bottom legal strip from the main directory; social icons align to the opposite edge.

**Transfer:** End with organized utility, not an enormous second brand graphic.

### Plan card

**Only for:** pricing modules

**Use:** Subscription comparison.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-radius: 8px; padding: 8px 32px 24px`

**Text style:** `small` — Inter 500 · 14px/24px

**Observed:** Three equal 432px columns. Plan-name recipe above a 40px serif price, raised 20px fraction, subdued billing line, audience description, full-width Primary button, checked benefits and Allowance inset. CTA positions align across the row.

**Transfer:** Describe who each plan is for before listing the features.

### Audience segment

**Only for:** pricing modules

**Use:** Switch between two plan families.

**CSS:** `display: flex; gap: 8px; padding: 4px; background: rgba(177, 169, 162, 0.1); border-radius: 9999px`

**Text style:** `body` — Inter 500 · 16px/1.5

**Observed:** 456px-wide, 72px-high track with a white selected 220px by 64px pill and small icon. A separate monthly/yearly switch sits above the cards.

**Transfer:** Keep audience and billing cadence as separate decisions.

## Imagery and graphics

### Cinematic proof rail

**Use:** Opening proof below the promise.

**Observed:** Square film stills with natural light and moody real-world color: people, action and environments. Small centered white customer marks sit on images; names and linked media credits appear beneath. The rail spills offscreen rather than shrinking every item to fit.

**Transfer:** Use authentic scenes of a product's outcomes at 432px square, with a credited project caption. Without customer footage, photograph a real person using the product in a purposeful environment.

### Cutout collage stage

**Use:** Signature visual interruption within the narrative.

**Observed:** Photographic hands, devices, plants, landscapes and oversized everyday objects cross flat rectangular color fields. Sharp cutout edges and improbable scale create a tactile surreal mood. A hand-held screen floats over a blue-gray field, a blue horizontal block and a lower mauve block; its caption sits in an ecru strip.

**Transfer:** Use a recognizable tool or result held by a human, paired with a landscape or material fragment. Preserve crisp edges, saturated flat backing and intentional overlap; a simple two-object composition is enough.

**Build:** Create a relative 624px-high blue-gray stage. Place an electric-blue rectangle about 60% of the stage width across the upper-left and a mauve rectangle of the same width across the lower-right. Layer transparent photographic cutouts above both, with one tall hand or product crossing their seam. Keep rectangles unrounded, unblurred and shadowless; put the caption in a separate ecru band with 48px vertical padding.

### Surreal category art

**Use:** Art for Gallery tile collections.

**Observed:** Photomontage mixes landscapes, human figures, 3D objects and architectural fragments: floating screens, oversized objects, layered hills and unexpected animals. Pink, yellow, blue and purple backgrounds make the images loud against charcoal.

**Transfer:** Art-direct each category around one visual metaphor, not a generic line icon. Minimum version: one cutout object, one photographic landscape fragment and one solid backing field.

**Build:** Use square clipped canvases; stack a solid pink or yellow backing, a landscape occupying the lower half, a large isolated object across the middle and one smaller human-scale cutout near an edge. Allow clean diagonal overlaps; keep all detail within the image, not on the page canvas.

### Product demonstrations

**Use:** Capability stages, process cards and integration chapters.

**Observed:** Wide dark editing interfaces and timeline views are framed on pink, yellow or pale blue-gray. The interface is the dominant object, with no dense explanatory labels outside it. Process imagery breaks the workflow into three 432px by 304px panels with orange, blue-gray and blue backing.

**Transfer:** Show a real useful product state, enlarged enough to read its structure. If a full interface is unavailable, design one focused workflow fragment rather than simulating a complicated dashboard.

### Studio portraits

**Use:** Portrait proof cards.

**Observed:** Crisply lit subjects are isolated against muted ecru, olive-gray, blue-gray or near-black backdrops. Square framing gives the face and posture room; a saturated footer supplies the color contrast.

**Transfer:** Use genuine experts or customers, with consistent square framing and varied restrained backing colors.

### Editorial split imagery

**Only for:** company and customer-story pages

**Use:** Long-form credibility and company explanation.

**Observed:** Customer stories use rectangular location or campaign photographs with a large customer mark. Company chapters alternate large square-ish images and vertically centered text; images include a dancer on pink, an object on blue and tactile surreal landscape collages. The customer-story opening puts a tall human cutout at right with flat blue/yellow blocks and reflective sculptural props.

**Transfer:** Use people and objects specific to the new product, keeping the alternation of honest photography and playful staged art. Avoid adding the elaborate tall collage to every ordinary section.

**Build:** For a tall opening montage, place two offset flat blue and yellow rectangles behind a sharply masked human portrait. Add one reflective sphere or folded ribbon prop partly outside the image edge. Keep text on the neutral field rather than overlaying the figure.

### Icons

**Observed:** Mostly 20px or 24px monochrome SVG controls with 2px strokes and butt caps, mixed with filled play, check and platform symbols. Arrows accompany editorial links; chevrons sit at FAQ right edges. Social marks are compact and dark gray in the footer.

**Transfer:** Choose a consistent simple 2px stroke family for controls; use filled play and platform marks only where their silhouettes carry meaning.

## Section recipes

How recurring sections are built.

### First screen: Centered promise and cinematic rail

**Observed:** Warm canvas behind a floating white navigation capsule, then a centered serif headline occupying roughly three quarters of the content width. At 80px/1 it wraps to two lines with the final phrase in true italic. The headline begins after 80px of opening padding below the 100px header. A horizontal row of three 18px benefits with tiny square separators follows, then Primary button and Secondary button separated by 16px, with a small reassurance line beneath. The media rail begins around 608px down the page: three full 432px square film stills and part of the next are visible across the width. Within the first 900px the navigation, entire promise, benefits, actions and upper portion of the images are visible; project captions fall below the fold. Back-to-front layers are neutral field, text and controls, photographic rail, then sticky navigation.

**Transfer:** Replace the promise and benefit trio with the new product's user outcome, and supply real outcome imagery or an in-context product photograph for the rail. Focused product and company pages open with a 64px centered headline and one action above a wide demonstration or split chapter; customer-story indexes use a left text/right tall collage opening.

**Avoid:** Do not start with a dark dashboard, a huge isolated device above the headline, or a full-bleed photograph with text over it. Do not compress the media rail to fit four small cards above the fold.

**Text style:** `display` — Sebenta 500 · 80px/1 · tracking -0.03em

### Expressive capability stage

**Observed:** Color stage or Warm canvas, centered eyebrow, 64px upright/italic heading and short 18px support. Heading-to-support spacing is 16px; the wide demonstration follows after 32px or 64px. The image or video can span 1216px and meet the bottom edge of the section.

**Transfer:** Give each capability one simple action/outcome headline and one dominant product demonstration.

**Text style:** `heading-lg` — Sebenta 500 · 64px/68px · tracking -0.03em

### Charcoal collection chapter

**Observed:** Dark gallery with left-aligned eyebrow and 64px upright/italic heading. Gallery tile grid uses four columns; the adjacent people chapter switches to Portrait proof card rails that reveal a partial next item.

**Transfer:** Use a dark collection chapter for product breadth, with the objects or people carrying most of the visual information.

**Text style:** `heading-lg` — Sebenta 500 · 64px/68px · tracking -0.03em

### Collage and compact caption

**Observed:** Cutout collage stage above an ecru strip. The strip holds one centered 20px serif sentence with selected italic verbs, then paired distribution badges 48px lower.

**Transfer:** Pair a playful product-in-life montage with a deliberately small editorial caption and the relevant access action.

**Text style:** `editorial-caption` — Sebenta 500 · 20px/1.2 · tracking -0.02em

### Editorial feature stack

**Observed:** Editorial ecru, left-aligned eyebrow and 64px headline, then a wide in-context photograph. Editorial overlay card overlaps its lower-left; thin previews with small white serif numbers remain visible at the right.

**Transfer:** Turn a release, tutorial or new use case into one large story with compact adjacent previews, rather than equal-weight article tiles.

**Text style:** `heading-lg` — Sebenta 500 · 64px/68px · tracking -0.03em

### Monumental statement

**Observed:** Color stage with 240px top and bottom breathing room. Two 128px lines form an offset composition, upright first line slightly left and italic second line slightly right. One Primary button follows 64px below. No image competes with the type.

**Transfer:** Include this signature typographic punctuation somewhere in an expressive landing page; use a short product-outcome sentence that remains meaningful without artwork.

**Text style:** `statement` — Sebenta 500 · 128px/1 · tracking -0.04em

### Objections and directory ending

**Observed:** Warm canvas, left-aligned 40px serif FAQ heading with 128px top breathing room and 64px before FAQ row stack. Footer directory follows with 80px top padding and a subtle ruled legal strip. Product-specific FAQ headings can be smaller at 24px, with a 32px gap.

**Transfer:** For a broad landing page, place this utility ending after the monumental statement. Pricing ends with FAQs and directory; focused product pages end with product FAQs and directory; story collections end with plans and directory; company pages end with a practical information split and directory.

**Text style:** `heading` — Sebenta 500 · 40px/1.2 · tracking -0.03em

### Informational split chapter

**Only for:** company and focused product pages

**Observed:** Two 656px columns with 16px gutter; a roughly 636px-high image alternates sides with vertically centered text. Headings are 32px serif, body 16px/24px, followed by a Standalone arrow link. Sections separate by 80px.

**Transfer:** Use for mechanisms, principles or integrations that need more explanation than a colorful feature stage.

**Text style:** `heading-sm` — Sebenta 500 · 32px/1.25 · tracking -0.03em

### Process triptych

**Only for:** onboarding and product explanation

**Observed:** Centered 48px heading, 64px gap, then three equal columns. Each has a 432px by 304px product image, a numbered 40px serif title and 16px body copy. Text-only onboarding variant replaces images with uppercase step labels.

**Transfer:** Explain the user's actual progression with concrete verbs, retaining equal visual emphasis without forcing equal paragraph lengths.

**Text style:** `heading-md` — Sebenta 500 · 48px/54px · tracking -0.03em

### Customer story index

**Only for:** customer-story collections

**Observed:** One two-column featured story row leads into three-column editorial rows. Each entry has a 304px-high photograph, uppercase category, 40px serif title, body paragraph and Standalone arrow link. Entries sit directly on the canvas, without a card surface. Long titles create generous aligned text zones.

**Transfer:** Use verifiable outcomes as headlines and let images establish industry or context; keep a regular grid despite varied title lengths.

**Text style:** `heading` — Sebenta 500 · 40px/1.2 · tracking -0.03em

### Pricing and detailed comparison

**Only for:** pricing pages and conversion modules

**Observed:** Centered heading and Audience segment above three Plan cards. A proof-logo marquee separates cards from a white comparison band. Comparison uses a persistent header, serif group labels, 73px feature rows with 24px vertical padding, black checks, faint unavailable marks and dashed-underlined feature definitions.

**Transfer:** Start with an audience choice, then concise plan summaries; reserve the long matrix for users who need exact distinctions.

**Text style:** `heading` — Sebenta 500 · 40px/1.2 · tracking -0.03em

## Page flow

**Storyline:** Outcome promise → tangible creative proof → capability demonstration → breadth and human credibility → timely editorial story → conversion punctuation → objections and utility.

### Expressive general marketing landing page

1. **promise** — Centered upright/italic statement, benefit trio and paired actions above a cinematic proof rail.
2. **product demonstration** — Compact announcement and expansive colored capability stages.
3. **breadth and social proof** — Charcoal category tiles and portrait proof rails.
4. **editorial relevance** — Ecru update stack with bright overlay title.
5. **closing call** — Monumental offset serif sentence on pink with a single black action.
6. **objection handling and utility** — Off-white accordion stack and shared directory footer.

**Transfer:** Adapt the rhythm of emotional promise, real proof and colorful demonstration; retain the capsule, collage and monumental statement without treating the section order as fixed.

### Plan selection and detailed evaluation

1. **pricing** — 64px centered heading, audience and billing controls, three white plan cards.
2. **social proof** — Monochrome logo marquee.
3. **decision support** — Long white comparison matrix with persistent plan header and grouped features.
4. **objection handling and utility** — Large FAQ stack followed by shared directory.

**Transfer:** Keep decorative imagery restrained so the distinction between plans stays the main event.

### Explain one workflow-focused product

1. **promise** — Centered eyebrow, 64px title, 18px explanation, single action and format reassurance.
2. **product demonstration** — Large wide video stage.
3. **capability explanation** — Small left heading beside stacked benefit subheads and short paragraphs.
4. **onboarding** — Three illustrated steps under a centered 48px heading.
5. **integration proof** — Large product image beside explanatory copy.
6. **objection handling and utility** — Compact product FAQ and shared directory, without another giant promotional scene.

**Transfer:** Trade some spectacle for a clear demonstration of the workflow and its practical constraints.

### Build confidence through a broad library of outcomes

1. **promise** — Left-aligned 64px heading and action opposite a tall human collage.
2. **social proof** — Two featured stories followed by repeated three-column story grids with outcome-led headlines.
3. **conversion** — Audience-selected pricing cards near the end.
4. **utility** — Shared directory footer directly after the plans.

**Transfer:** Use a repeatable editorial grid and substantive stories rather than inventing a new visual style for every customer.

### Explain the organization and its approach

1. **identity** — Centered 64px introduction and single action.
2. **positioning** — Narrow text beside a large editorial film poster.
3. **principles and capability** — Alternating image/text chapters with playful physical collages and clear prose.
4. **onboarding** — Three text steps beneath a centered 48px heading.
5. **practical information** — Company-information split beside a vivid tactile image.
6. **utility** — Shared directory footer; no FAQ or monumental closing scene.

**Transfer:** Translate principles into concrete user benefits, then provide useful organizational details in the same editorial grid.

## Writing

Confident, direct and warmly enabling. Creative promises are paired with practical explanations; the reader remains in control while the product removes friction.

**Do not copy:** Do not reuse the brand name, logo, customer marks, artist identities, campaign artwork, catalog sizes, reach metrics, prices, licensing guarantees or superiority claims as facts for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to 'you' and 'your' work; use 'we' when stating what the company supplies. Name the product when explaining a specific mechanism.
- **Rhythm:** Short sentence-case headlines and occasional two-part statements. Supporting copy is one compact sentence or a short paragraph; deliberate fragments and three-part contrasts keep the prose energetic without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Contrast the reader's contribution with what the product supplies; emphasize the final outcome phrase. | 8–12 words | “You bring the idea. We bring the sound.” |
| Capability headline | Make the user's material or action the subject of an outcome. | 5–9 words | “Let your video do the work.”<br>“Use music to find music.” |
| Support line | Explain the mechanism or concrete benefit without another metaphor. | 8–22 words | “From rough cut to final soundtrack. Seamlessly synced to your edit.” |
| Reassurance | Remove a specific concern with clipped parallel phrases. | 5–15 words | “Human-made tracks and sound effects. No claims, no takedowns, no surprises.” |
| Primary action | Verb plus clear destination or low-friction commitment. | 2–4 words | “Create free account”<br>“Try now” |
| Story title | Named subject plus measurable or tangible improvement. | 7–14 words | “Bucketsquad cuts soundtracking time in half” |
| Monumental statement | Invite discovery of the product's broader possibility. | 5–8 words | “Discover what sound can do.” |

**Words and phrasing to use:** your way; creative control; flow; real; works where you work; in moments; discover; create

**Avoid:** revolutionary ecosystem; disruptive solution; unlock synergies; magic with no explanation; vague enterprise jargon

**Rules:**

- Pair an evocative headline with a concrete explanation of what happens next.
- Keep feature claims tied to a user task; avoid a list of abstract product adjectives.
- Use numbers as proof inside a meaningful story or compact card, not as unsupported spectacle.
- Write FAQ questions in the reader's own language and answer the practical issue first.

## Do's and Don'ts

### Do

- Set the default landing headline at 80px/1 and use a true italic phrase within it.
- Keep main chapter headings at 64px/68px with -0.03em tracking.
- Use the 56px desktop gutter and 16px column gap to align otherwise very different sections.
- Make primary actions black 56px pills and nested header actions 44px pills.
- Give the collage sharp, unrounded color rectangles and a crisp photographic cutout.
- Keep the monumental pink statement at 128px/1 with its two lines offset.
- Use 8px radii on gallery tiles, plan cards and FAQ rows.
- Keep the ending warm off-white, with small directory links and a fine ruled legal strip.

### Don't

- Do not replace the serif with a geometric sans for all headings; the editorial/utility contrast is fundamental.
- Do not color the main CTA pink, yellow or green; vivid fields belong behind content, while the action stays black.
- Do not make every card a 24px-radius floating panel; the core content radius is 8px and editorial slabs are rectangular.
- Do not apply the navigation's shadow to all media and plan cards; most surfaces are flat.
- Do not use a generic blurred gradient as the collage backdrop; the material is crisp flat rectangles and cutout photography.
- Do not render 16px body copy in light gray or weight 300; the default is black Inter 500 with 24px leading.
- Do not turn story entries into bordered boxed cards; those grids are open editorial columns.
- Do not enlarge portrait reach metrics into a detached wall of huge counters; keep them inside the colored information panel.

## Motion and responsive

### Motion

**Observed:**

- Control color transitions are declared at 0.15s cubic-bezier(.4,0,.2,1); navigation shadow transitions at 0.2s with the same curve.
- Collage blocks and offset statement lines declare 600ms transforms with cubic-bezier(0.9,0,0,1). The statement lines use opposing 10% horizontal translations.
- The proof-logo row declares a 60s linear infinite marquee. Some image entrances declare 1s with cubic-bezier(0.9,0,0,1).

**Transfer:**

- Animate collage pieces as independent sliding layers rather than fading a whole scene together.
- Let the monumental statement arrive as two opposing text parts while retaining its final staggered alignment.

**Unknown:**

- Exact scroll triggers, playback behavior, mobile timing and reduced-motion variants are unspecified.

### Responsive

**Observed:**

- Grid side padding tokens are 16px, 32px and 56px. Desktop uses the 56px inset.
- The plan grid declares a single-column base and three columns above its wide-screen condition. Audience buttons declare 170px base width and 220px at the medium condition.
- The navigation and footer declare alternate narrow layouts; breakpoint declarations include 768px, 960px and 1024px.

**Transfer:**

- On narrow screens, preserve the capsule silhouette with fewer visible controls rather than squeezing all desktop links.
- Stack split chapters and plan cards; preserve intentional horizontal rails for cinematic proof and portraits.
- Reduce the monumental sentence to fit without losing the upright/italic contrast or opposing offsets; keep collage layers overlapping instead of shrinking a whole desktop composition to illegibility.

**Unknown:**

- Exact narrow-screen type sizes, navigation expansion, collage rearrangement and comparison-table replacement are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
